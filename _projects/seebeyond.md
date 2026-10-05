---
title: "See Beyond"
excerpt: "Single Page Application for mobile devices with real-time support for assisting visually impaired people."
collection: projects
order: 2
---

<div style="text-align: justify;" markdown="1">

<div style="text-align: center;">
  <img src="/images/seebeyond.png" width="250" style="float: left; margin-right: 20px; margin-bottom: 10px;">
</div>

According to the latest data from the World Health Organization, approximately 4% of the global population (about 253 million people) are affected by visual impairments. Of these, over 80% have low vision (i.e., individuals who retain a residual level of vision).

*See Beyond* is a project conceived to mitigate these challenges, with the objective of assisting people with visual impairments in their daily lives by providing real-time audio feedback. Its primary goal is to recognize and calculate, through triangulation, the distance of objects surrounding the user, compensating for the physical limitations of individuals with low vision. Among its secondary features are a voice assistant, which provides support and companionship; optical character recognition, useful for reading any text; and a navigation assistant based on Google Maps, aiding movement in unfamiliar locations.

The entire system is implemented on the client side as a Progressive Web App (PWA) for mobile devices, built as a Single-Page Application using React and JavaScript. On the server side, a Python backend hosts a Convolutional Neural Network (Faster R-CNN, implemented in PyTorch) dedicated to object and animal recognition. For hosting and database management, Firebase is employed.

The app is available [here](https://seebeyond-8bdb7.web.app/) (it is recommended to open it on a mobile device).

For further information or access to the documentation, please contact me via [email](mailto:davideverditto).

</div>