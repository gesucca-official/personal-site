---
title: Batch Jobs Execution Service
date: 2023-06-15T12:13:40+00:00
thumbnail: images/portfolio/batch.png
service: Architecture and Development
client: Private Company
shortDescription: Architecture and development of a service that asynchronously manages batch jobs of various time consuming programs through a REST API, with advanced in-depth error tracking and total modularity in chaining batches of programs and piping their outputs.
challenge: The client wanted to freshen up their managing of batch job, which was a gigantic Windows BAT file called by all sorts of configurator applications, also adding the possibility to check outputs and logs for errors and making said items available through a REST API for web applications to consume. 
solution: After failing to persuade them to use one of the various commercial solutions, I resigned to just create one from scratch which perfectly fit all the requirements down to every quirk.  
skill:
  - title: Java (Spring Boot)
    percent: 80
  - title: SQL
    percent: 10
  - title: Windows CMD
    percent: 10
---
This has been one of my favourite projects since I love working with back-end services.

First I obtained the required modularity by structuring existing batch jobs in Run Modes composed by atomic chunks of Run Blocks, which are in turn composed by individual commands, and stored all this information in a plain old relational DB, with a few procedures to ease the process of creating and editing modes and blocks.

The actual spawning of Windows processes and waiting for them to complete was trivial, as was the REST API to query for active processes and the likes.

The logic for checking the logs and the outputs for errors was once again stored in a relational db. I had to invent a simple pseudo language to indicate what should be present or not in which file produced by each command, but that gave the entire system an amazing flexibility and was totally worth the effort.