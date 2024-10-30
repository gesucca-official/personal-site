---
title: Modeling and Drafting Automation
date: 2023-03-05T12:13:40+00:00
thumbnail: images/portfolio/mop.png
service: Architecture and Development 
client: Private Company
shortDescription: Architecture and development of a customization for a widely-used CAD and modeling software, enabling the creation of 3D models through exposed APIs and the extraction of fully-dimensioned 2D drafts. The final drafts are then imported into a separate PLM software.
challenge: The client needed a way to significantly reduce the time spent manually drafting connection layouts for products, which were already composed of highly standardized components. 
solution: Collaborating with a modeling engineer, I first created placeholder models for each component type. Next, I developed a GUI that allowed the client’s engineers to select components, set parameters, and generate a 3D model. From this, I finally extracted a fully-dimensioned 2D draft, complete with all necessary annotations.
skill:
  - title: C#
    percent: 85
  - title: C
    percent: 15
---

This was... complicated. Lots of moving things, so many of them I barely remember how much trial and error it took. 

Due to the nature of the beast we were working with, the provided APIs were chaotic and not comprehensive of all the features we needed to achieve the results we wanted, so I resorted to find many creative solutions using an old but surprisingly working C API. 

I can't really share project specifics without breaching confidentiality, but beside all troubles and technical challenges faced -- the algorithm needed to properly place dimensions on the drafting was nothing short of evil --- the end result was simply beautiful: engineers use this tool to create fully dimensioned 2D layouts in minutes instead of days. 

