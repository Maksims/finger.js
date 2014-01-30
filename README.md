finger.js
=========

Lightweight library to abstract mouse/touch/pointer events into "taps" for gaming.

Allows event-based and direct access to taps, clicks, dragging, gestures, path.

Library is not made for DOM applications, as taps will not contain any information about elements or collisions. Events are screen based (window), and have only coordinates of their presence, as well as state.  
This is perfect for gaming applications with canvas, or applications based on gestures rather than element events.
