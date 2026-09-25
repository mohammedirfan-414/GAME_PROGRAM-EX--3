# GAME_PROGRAM-EX--3
## Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

## Procedure

1. **Import New Character Mesh and Animations:**
   - In the **Content Browser**, import a new **Skeletal Mesh** along with its **Animations** (FBX files).
   - Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).

2. **Replace Character Mesh:**
   - Open the **ThirdPersonCharacter Blueprint** (usually found in `ThirdPersonBP/Blueprints`).
   - Select the **Mesh** component.
   - In the **Details Panel**, change the **Skeletal Mesh** to the newly imported mesh.

3. **Set Animation Blueprint:**
   - If available, assign a matching **Animation Blueprint** in the **Details Panel** under the **Animation** section.
   - If not available, create one:
     - Right-click in the Content Browser → **Animation → Animation Blueprint**.
     - Choose the correct skeleton.
     - In the AnimGraph, set up state machines or direct animation nodes.
     - Compile and save.

4. **Preview and Test:**
   - Place the character in the level.
   - Press **Play** to test idle, walk, and run animations based on character movement.
  
## Output
<img width="591" height="428" alt="image" src="https://github.com/user-attachments/assets/538345ec-969a-46ab-8350-ecbf55639fc7" />
<img width="345" height="306" alt="image" src="https://github.com/user-attachments/assets/921f0458-d232-4a9a-bf0e-f5e690b31add" />
<img width="618" height="366" alt="image" src="https://github.com/user-attachments/assets/f514c665-5d22-4dde-b568-3180a371e14b" />






## Result
The default Third Person C
