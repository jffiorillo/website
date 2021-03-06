---
title: Background processes
---

Have you ever wanted to execute Dart code in the background—even if
your app wasn’t the currently active app? Perhaps you wanted to implement
a process that watches the time, or that catches camera movement.
In Flutter, you can execute Dart code in the background.

The mechanism for this feature involves setting up an isolate. _Isolates_
are Dart’s model for multithreading, though an isolate differs from a
conventional thread in that it doesn’t share memory with the main program.
You’ll set up your isolate for background execution using callbacks and
a callback dispatcher.

For more information and a geofencing example that uses background
execution of Dart code, see [Executing Dart in the Background with
Flutter Plugins and
Geofencing](https://medium.com/flutter-io/executing-dart-in-the-background-with-flutter-plugins-and-geofencing-2b3e40a1a124),
an article in the Flutter Publication on Medium. At the end of this article,
you’ll find links to example code, and relevant documentation for Dart,
iOS, and Android.

