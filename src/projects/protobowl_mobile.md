---
tags: projects
title: Protobowl Mobile
description: A Flutter application that extends antimatter15's Protobowl trivia site
image: img/protobowl_logo.png
link: https://github.com/jrachele/protobowl-mobile
permalink: false
---
In 2019, I wrote a cross-platform mobile app for the real-time trivia website Protobowl. Protobowl is written in Coffee Script and uses socket.io, but (at the time), there was no support for socket.io in Dart/Flutter. Therefore, I had to write a wrapper in Dart that processed it, and updates the widgets accordingly.

For data persistence I use SQLite, and for data management in the application I use flutter-redux.