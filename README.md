<div align="center">

# Kyr4vex's Debug Panel

A compact in-game debug panel for Roblox with live game stats, a player list and detailed mouse data, built to be forked and edited.

<div align="center">
  <video src="https://github.com/Kyr4vex/Debug-Panel/raw/main/assets/showcase.mp4" width="640" controls muted loop></video>
</div>

</div>

## Features
* **Game Tab:** Shows the essentials at a glance: game name, player count, PlaceID, Job ID, FPS, frame time, ping, memory usage, instance count, camera FOV and network and physics traffic.
* **Players Tab:** Lists every player as `@user (display) HP | X, Y, Z`, with your own entry pinned to the top in green and the rest sorted alphabetically. Names are escaped, so symbols in display names can't break RichText.
* **Mouse Tab:** Tracks 15 mouse parameters in real time: screen position, viewport size, movement delta and speed, mouse behavior, icon visibility, pressed buttons, wheel total and last input type. A raycast under the cursor adds the world hit position, target name, class and material, distance from the camera and surface normal.
* **Lightweight Updates:** Everything runs on a single `Heartbeat` connection with throttled refresh, and connections are cleaned up when the GUI is destroyed.
* **Safe Readouts:** Unavailable stats fall back to `N/A` instead of throwing errors.
