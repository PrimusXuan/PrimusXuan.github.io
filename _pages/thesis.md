---
layout: archive
title: "Thesis"
permalink: /thesis/
author_profile: true
---

<h1>Master&apos;s Thesis</h1>

<b>Enhancing Language Learning with Extended Reality, 3D Avatars and Large Language Models</b><br>
MSc Information Technology, University of Glasgow (2025)
<br><br>

My master&apos;s thesis explores how Extended Reality (XR), 3D avatars and large language models can work together to support language learning on the Meta Quest 2. I built a VR prototype in Unity where learners can practise conversations in English, Chinese and Japanese with an AI-driven avatar.

The system connects several components into a real-time loop:

<ul>
  <li>Capturing the user&apos;s speech on the Meta Quest 2.</li>
  <li>Using Azure Speech-to-Text to obtain a transcript.</li>
  <li>Constructing prompts and querying a large language model to generate context-aware replies.</li>
  <li>Using Azure Text-to-Speech to synthesize the avatar&apos;s voice.</li>
  <li>Synchronizing subtitles, lip motion and dialogue history inside Unity.</li>
</ul>

The technical focus is on keeping this loop stable under latency and hardware constraints: handling asynchronous API calls, avoiding blocking operations, managing errors and timeouts, and still maintaining a smooth user experience in VR.

Key aspects include:

<ul>
  <li>Designing a modular C#/Python interaction architecture for speech recognition, prompt construction and response validation.</li>
  <li>Supporting multiple languages (English, Chinese, Japanese) and allowing language switching during interaction.</li>
  <li>Using prompt engineering to simulate different conversational roles, emotional tones and levels of difficulty.</li>
  <li>Iterating based on pilot tests with learners to refine avatar positioning, subtitle timing and interaction flow.</li>
</ul>

[📘 Download MSc thesis (PDF)](/files/MSc_project_2745883w.pdf)

<br><br>

<!-- YouTube video embed -->
<div style="position: relative; padding-bottom: 56.25%; height: 0; margin-bottom: 40px;">
  <iframe 
      src="https://www.youtube.com/embed/o5BAKsWjyx0"
      style="position: absolute; top:0; left:0; width:100%; height:100%;"
      frameborder="0" allowfullscreen>
  </iframe>
</div>

<hr>
<br>


<h1>Bachelor&apos;s Thesis</h1>

<b>Research and Implementation of Shock Wave Detection Technology for Compressible Flows</b><br>
BEng Aerospace Engineering, Dalian University of Technology (2020)
<br><br>

My bachelor&apos;s thesis focuses on detecting and reconstructing shock waves from large, noisy CFD datasets in compressible flows. The goal is to convert raw solver outputs into clear, engineer-ready shock surfaces that can be inspected and used in design decisions.   

I implemented a C++ post-processing pipeline that:

<ul>
  <li>Reads mesh and flow-field data for three-dimensional compressible flows relevant to aircraft configurations.</li>
  <li>Flags shock candidates by analysing local discontinuities in flow variables while filtering numerical noise.</li>
  <li>Uses two geometric models: a point-source model with a spherical partition, and a line-source model with a cylindrical mesh to better capture elongated shock structures.</li>
  <li>Compares a least-squares fitting approach with a simpler averaging scheme for reconstructing continuous shock surfaces.</li>
</ul>

On representative datasets, the pipeline reduces thousands of scattered shock-indicator points to a much smaller number of surface elements while producing smoother and more physically plausible shock surfaces. I also outlined how hybrid point–line models, adaptive meshing and machine-learning techniques could further automate and scale the detection process.   

[📘 Download BEng thesis (PDF)](/files/BEng_Shockwave.pdf)

<br><br>
<hr>
<br>

<h1>Looking Ahead</h1>

Both theses reflect how I like to work at the boundary between modelling and systems:

<ul>
  <li>At the MSc level, combining XR, avatars and large language models into a usable, real-time system for language learning.</li>
  <li>At the BEng level, turning raw CFD data into geometric objects that engineers can interpret and use.</li>
</ul>

In the future I hope to continue building systems that connect data, models and human interaction — whether in education, engineering or other applied domains.

Add this page