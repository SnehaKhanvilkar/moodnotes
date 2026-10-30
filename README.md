# MoodNotes – connected smart home (single file, Three.js r128 bundled)
Run: cd moodnotes-house && python3 -m http.server 8080  -> http://localhost:8080 (localhost/HTTPS needed for WebXR)
Desktop: WASD, mouse, E/click interact (again = undo), Esc pause, R reset, N/B simulate day, M mute.
VR: Enter VR button (if supported). Stick forward+release = teleport, stick sideways = snap turn, trigger = interact, grip = mute.
Models: all procedural (bevelled furniture, puffy cushions, draped cloth, pleated curtains, leaf meshes). No GLB files are bundled
(no network access when this was built, and the bundled Three.js has no GLTFLoader).
Music: generated in-browser (original). State persists in localStorage.
Start: you spawn in the apartment lobby. Look at the front door and press E / click (VR: trigger) to open it, then walk in.
