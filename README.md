# Movie Shot Processing with Face Depth Frame Mancer Plugin

This repository contains the raw and processed videos, Blender files, and Unreal Engine project files for processing movie shots using the **Face Depth Frame Mancer Unreal Engine Plugin**. The project demonstrates how to process facial capture data and create MetaHuman identities.


## Branches

### `empty-tutorial` Branch
The `empty-tutorial` branch is the starting point for processing videos. Download and open the `.uproject` file to begin. Use the Face Depth Frame Mancer plugin to process your videos.

### `full-project` Branch
The `full-project` branch contains the final result of the processed videos. It includes:
- All frames and capture data.
- Audio files.
- MetaHuman identities and performances.
- Level sequences and animation sequences.

This branch **does not require the Face Depth Frame Mancer plugin** to be enabled. If you want to check the final result without processing the videos yourself, download this branch to see how the plugin created these animations.

---

## Repository Structure

### Key Folders and Files
- **`MovieShot1-SquidGame`**: Contains raw and processed videos, along with Blender files for the "Squid Game" movie shot.
- **`MovieShot2-OsamaRomoh`**: Contains raw and processed videos, along with Blender files for the "OsamaRomoh" movie shot.
- **`UE55Project`**: The Unreal Engine project used to process the videos.
  - **`UE55Project/Content/EditorOnly`**: Contains plugin values and camera settings used for processing.
  - **`UE55Project/Content/MovieShotPerformances/(MovieShots)/MHI`**: Contains frame structures for creating MetaHuman identities (neutral and teeth pose frame numbers).
  - **`UE55Project/Content/MovieShotPerformances/MovieShot1_Ingested`** and **`UE55Project/Content/MovieShotPerformances/MovieShot2_Ingested`**: Contain camera calibration assets referenced in the plugin settings.

---

## Getting Started

### Prerequisites
- **Unreal Engine**: Ensure you have Unreal Engine installed.
- **Metahuman Plugin**: Ensure you have Official Metahuman Plugin installed.
- **Face Depth Frame Mancer Plugin**: You need this plugin to process the videos. Install and enable it in your Unreal Engine project.

### Setup
1. Clone or download this repository.
2. Open the `UE55Project.uproject` file in Unreal Engine.
3. Navigate to the `UE55Project/Content/EditorOnly` folder to review the plugin values and camera settings used for processing.

---

## Reusing Plugin Values
To quickly process new videos, reuse the plugin values and camera settings located in:
- `UE55Project/Content/EditorOnly`




