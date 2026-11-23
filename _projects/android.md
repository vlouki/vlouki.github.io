---
layout: page
title: LoukIt! - Daily Task Management Application
description: Android Development with Java
img: assets/img/LookIt!_project.png
importance: 3
category: academic
github: https://github.com/vlouki/mobdev-project-2026
---

## Overview

LoukIt! is an Android application developed in Java for organizing and managing daily tasks. The application focuses on task creation, organization, tracking, and completion.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/LookIt!_project.png" title="Launcher Icon" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    App Demonstration
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/main_page.png" title="Main Page" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/tasks_page.png" title="Tasks Page" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/task_details_page.png" title="Task Details Page" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/new_task_page.png" title="New Task Page" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/config_page.png" title="Configuration Page" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Key Features

- Create, manage, and complete daily tasks.
- Store application data locally using Room.
- Store user preferences and default task settings.
- Perform background operations with WorkManager.
- Support task data access through a Content Provider.
- Integrate location-based functionality using Google Maps.

## Technologies Used

- Java
- Android SDK
- Room / SQLite
- WorkManager
- Content Provider
- Google Maps

## Video Demonstration

Watch LoukIt! running in the Android Studio emulator.

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9;">
  <iframe
    src="https://www.youtube.com/embed/u5axN2hvB-Y"
    title="LoukIt! Android Application Demonstration"
    style="width: 100%; height: 100%; border: 0; border-radius: 10px;"
    referrerpolicy="strict-origin-when-cross-origin"
    loading="lazy"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen>
  </iframe>
</div>

## Download LoukIt!

Interested in trying LoukIt! on your Android device?

Download the latest beta release (**v0.1.0**) using the button below.

[![Download APK](https://img.shields.io/badge/Download_APK-21262D?style=for-the-badge&logo=android&logoColor=white)](https://github.com/vlouki/mobdev-project-2026/releases/download/v0.1.0-beta/LoukIt.apk)

**Note:** This is a beta version. Some features may not work as expected.

[View Release Notes](https://github.com/vlouki/mobdev-project-2026/releases/tag/v0.1.0-beta)
