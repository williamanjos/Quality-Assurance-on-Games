stone.creek/
# QA Test Report & Feedback — Cave Creek
**Date:** May 26, 2026  
**Tester:** [Your Name / GitHub Username]

---

## 1. Environment & Session Info
* **Platform:** PC (Steam)
* **Testing Type:** Functional, Usability & Camera Mechanics
* **Status:** Initial Gameplay Session

---

## 2. Positive Feedback (What is working well)
* **Character Movement:** The movement mechanics feel very fluid and responsive.
* **Camera Angle (Top-Down):** The overall camera angle looks great when viewing the game world from above.
* **UI / UX:** The menus are intuitive, easy to interact with, and both the menu and inventory systems are fully functional.
* **AI Behavior:** Enemy movement is working as intended, and the core concept of enemies hunting down the player is well-implemented and engaging.

---

## 3. Bug Reports (Defects Found)

### 🐛 BUG 001: Mouse Scroll Wheel Zoom Limit
* **Description:** The mouse scroll wheel fails to reach the intended maximum zoom distance.
* **Steps to Reproduce:**
  1. Launch the game and enter a session.
  2. Attempt to zoom out completely using the mouse scroll wheel.
* **Expected Result:** The camera should smoothly zoom out to its maximum predefined limit.
* **Actual Result:** The scroll function bugs out and blocks the player from reaching the maximum zoom-out distance.

### 🐛 BUG 002: Camera Stuck on Spawn / Intro
* **Description:** At the very beginning of the game, the camera spawns extremely close to the character and locking the zoom function.
* **Steps to Reproduce:**
  1. Start a new game session.
  2. Observe the initial camera placement.
  3. Try to zoom out immediately.
* **Expected Result:** The camera should start at a default playable distance or allow the player to zoom out instantly.
* **Actual Result:** The camera bugs out, gets stuck too close to the character, and refuses to zoom out during the initial moments.


---

## 4. Usability & UX Suggestions (Improvements)

### 📌 Item 01: Vertical Camera Tilt Angle Limit
* **Observation:** The current camera constraints restrict the vertical viewing angle.
* **Impact on Player:** I can't see far into the horizon because the camera can't tilt down any further. This limits situational awareness and makes it harder to spot and avoid oncoming enemies.
* **Suggestion:** Increase the vertical camera tilt limits to give players a wider field of view, allowing them to spot dangers from a safer distance.

---

## 5. Conclusion
The game has a solid foundation with functional menus, fluid movement, and a promising enemy AI loop. Fixing the camera zoom bugs and tweaking the vertical field of view will significantly improve player comfort and the overall gameplay experience.
