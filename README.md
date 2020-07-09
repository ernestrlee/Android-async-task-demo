# Android Async Task Demo

The demo app opens a dialog box with a progress bar. The progress bar is updated using an
asynchronous task that runs in the background. Async tasks can be interrupted by configuration
changes, so should only be used for items that do not take a long time or do not need to update UI.

For async tasks that do not get interrupted by configuration changes, use async task loader.

This demo was part of Android Development Fundamentals, Unit 3: Lesson 7.1.