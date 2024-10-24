---
title: Raw Factory
date: 2024-10-01T12:13:40+00:00
thumbnail: images/portfolio/raw_fact.png
service: Full Product Managing 
client: Private Company
shortDescription: Architecture, development and deployment of a software library and its related tools designed to work with some of the major frameworks (Angular, React and Vue.js), created with the goal of simplify managing relationships among interconnected data points in complex software applications. 
challenge: My employer wanted a library that abstracts away the complexities of managing dependencies among interconnected entities in web based GUIs, to factor away that overhead and reduce the developing time or many similar products. 
solution: I crafted an npm package that do just that by modeling data as nodes on a graph. I implemented it by extending the RxJS Library to manage node updates and API calls by importing a configuration file which can be easily managed by a CLI tool.
skill:
  - title: TypeScript
    percent: 70
  - title: NodeJS and NPM
    percent: 15
  - title: AWS 
    percent: 15
---
This was somewhat fun, and a big headache at the same time. The original idea from the employer was to squeeze into a library all the common techniques that competent coders uses all the times to manage complex situations of interactive GUIs that continuously have to validate inputs and dependencies before triggering API calls. 

The employer fully intend to extract value from this effort by selling the library to other companies, as well as from its obvious use in the company itself. While I was --- and I still am --- dubious about the commercial potential of something like this, I worked towards the intended goal and delivered everything needed to reach it, from designing the software architecture to the final product landing page and everything in between.
