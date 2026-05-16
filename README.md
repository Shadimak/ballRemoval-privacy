# Ball Removal - 2D Casual Mobile Game

A fast-paced, color-matching 2D arcade game built from scratch using Google's Flutter SDK and the Dart programming language. This project represents my foundational entry into independent mobile software development, focusing heavily on real-time state management, directional swipe collision detection, and dynamic UI rendering.

## Technical Features & Core Logic

As the sole developer and architect of this project, I engineered the entire gameplay lifecycle. Key technical implementations include:

*   **Directional Input & Swipe Handling:** Implemented full-screen gesture detectors to calculate and process velocity-based swipes (Left, Right, Top, and Bottom) for immediate player interaction.
*   **Color-Matching Algorithmic Logic:** Developed a dynamic game state tracker that monitors the changing color arrays of the central asset and cross-references them upon collision with the moving peripheral boundary bars.
*   **Dynamic Boundary Animation:** Engineered real-time linear translations for boundary bars moving along the edges of the screen, tracking coordinate shifts to trigger precise game-over or score-increment states.
*   **State & Score Management:** Built a lightweight, non-blocking score synchronization architecture that updates the user interface instantly upon successful color alignment without dropping frames.
*   **Responsive Framework Layout:** Utilized Flutter's layout engine to ensure that game coordinates, swipe sensitivities, and asset dimensions automatically adapt to varying mobile aspect ratios.

## Tech Stack & Tools

*   **Framework:** Flutter SDK
*   **Programming Language:** Dart
*   **UI Components:** Custom Flutter Canvas/Containers for performance-optimized rendering
*   **Target Platform:** Android Ecosystem

##  Gameplay & Media Demonstration

To review the functional application interface and design architecture, please refer to the following resources:

*   **Google Play Store Link:** [Insert your active Google Play link here]
*   **GitHub Repository (Source Code):** https://github.com/Shadimak/ballRemoval-privacy
*   **Gameplay Walkthrough Video:** [Insert your Google Drive or YouTube video link]

---
*Developed independently by Shadi Ahmad Shafik Zarea — 2023*
