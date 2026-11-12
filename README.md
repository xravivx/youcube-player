# YouCube Player

A tiny relay page for the YouCube home TV app. The app loads from `file://`, which the
YouTube embedded player rejects (error 152/153), so it embeds this page instead and controls
it with `postMessage`. This page contains no keys and collects no data.
