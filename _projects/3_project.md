---
layout: page
title: Distate
description: A custom protocol over UDP for virtual workspaces.
img: assets/img/distate_workspace.png
importance: 3
category: school
---

This project was for a class. I worked with another student on developing a custom protocol over UDP. The custom protocol was designed for virtual workspace applications. Virtual workspaces are collaboration enviroments for companies that resemble RPGs for interactivity, check out WorkAdventure. For this project we developed the protocol, Distate, and implemented a model virtual workspace using Python Arcade for the client application. The server was developed in Elixir. We evaluated our protocol against TCP (the default for these applications) measuring network jitter and network latency. We compiled our research into a paper for the class where we were peer-reviewed by our classmates.

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/distate_workspace.png" title="Model Workspace" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    GUI for Distate model virtual workspace.
</div>

