# pagoda-model

# Bringing Architecture to Life - Modeling the Dragon and Tiger Pagoda

**Helen He & Bozhen Peng**

**Google Drive Link:**
[Project Files](https://drive.google.com/drive/u/1/folders/1Nbq1Do6WW0JxeIT3PHu9fUFIQhF90QZq)

**File List:**

1. `UnityExecutable-HelenBozhen-175Final-win64.zip`: Executable for Windows (x64) compressed.
2. `UnityExecutable-HelenBozhen-175Final-macos.zip`: Executable for macOS (Intel & Arm) compressed.
3. `SketchUp-Longhuta-Model.skp`: The Longhuta model created on SketchUp.
4. `UnityProject-CS175Final-HelenBozhen.zip`: Unity Project files compressed.

<img width="287" alt="image" src="https://github.com/user-attachments/assets/d8cc2078-1387-48aa-af4d-cb9584d28e8e" />


---

## Introduction

The Longhuta (Dragon and Tiger Pagoda) is a monument facing the Thousand-Buddha Cliff north of Mount Tai in Shandong Province, China. Dated to the 8th century CE, the pagoda was commissioned by imperial family members of the Tang Dynasty as well as local prefects. It is a significant program in the history of architecture and a key monument in Pure Land Buddhism.

This project aims to:

1. Model the pagoda to capture its architectural complexity using SketchUp.
2. Reconstruct a historical scene surrounding the pagoda in Unity.

<img width="519" alt="image" src="https://github.com/user-attachments/assets/1876847b-e83b-4b16-b551-2c3863449c2f" />

<img width="441" alt="image" src="https://github.com/user-attachments/assets/8eef07d3-786b-49ad-9eac-3de030b71683" />

<img width="442" alt="image" src="https://github.com/user-attachments/assets/fab8c6c6-83f4-40f6-8125-9c57e9b09e6d" />

<img width="459" alt="image" src="https://github.com/user-attachments/assets/2987ccf0-34d1-4580-a75a-caf20e0e70a4" />

<img width="263" alt="image" src="https://github.com/user-attachments/assets/f90fae82-8e63-41ef-a4b8-19839ba4cba4" />

<img width="433" alt="image" src="https://github.com/user-attachments/assets/9f73b9f1-5d39-4b3a-beb7-8f584298b514" />


---

## Preparation

We consulted scholarship on Buddhist art history to understand the architecture. Key details:

- **Dimensions:** 42 5/8 feet high, with a three-tier stonework base.
- **Key Feature:** A cell (9 3/4 feet on a side) made from four large stone slabs, adorned with relief sculptures representing Buddhist Pure Lands.

### Sources

1. Pictures of the architecture from various angles.
2. Scholarly line drawing.
3. High-resolution photos provided by Harvard CAMLab.

---

## SketchUp Modeling Process

### Initial Steps

1. Imported the line drawing to SketchUp and adjusted its position.
2. Traced the 2D contour of the architecture.
3. Used the `push/pull` function to expand the 2D model into 3D.

### Focus Areas

- Focused on the exterior due to the inaccessibility of the interior cell.
- Simplified the complex **"dougang"** structure using rectangles and freehand lines.

### Additional Features

- Created recesses on the bottom layer of the base using `offset` and `push/pull`.
- Incorporated rotational elements for overhanging eaves based on photographic observations.
- Detailed the stupa at the pagoda's apex.

---

## Unity Scene Development

### Navigation Controls

- **Arrow Keys:** Move forward, backward, left, and right.
- **Space Bar:** Jump.
- **Mouse:** Look around.

### Unity Assets Used

1. **Fantasy Skybox FREE**
   - Simulated a dynamic sky.
   - Applied a lush grass texture.
2. **Lowpoly Environment - Nature Free**
   - Added tree prefabs for naturalistic details.
3. **Terrain Sample Asset Pack**
   - Sculpted unique topographical features.
4. **Modular First Person Controller**
   - Enabled navigation within the 3D space.

---

## Unity Techniques

### Terrain and Texture

- Sculpted the terrain using the Unity Terrain Editor.
- Applied grass textures to enhance depth and realism.
- 
<img width="736" alt="image" src="https://github.com/user-attachments/assets/f813703a-f573-4d0f-a616-026fc1d863cf" />

<img width="732" alt="image" src="https://github.com/user-attachments/assets/5ba88e43-29af-4be4-bba4-0c37a35f32d0" />

### Placement of Trees

- Used the **"Mass Place Trees"** function for efficient placement of trees.
  
<img width="726" alt="image" src="https://github.com/user-attachments/assets/43137006-0aa2-4eb6-a4ad-6c2e49746dbc" />


### Fog and Lighting Effects

- Added environmental fog for depth and atmosphere.
- Used a dynamic skybox for natural lighting.
<img width="730" alt="image" src="https://github.com/user-attachments/assets/542f0d7a-65ae-4c1e-b86c-398ce4625365" />

<img width="724" alt="image" src="https://github.com/user-attachments/assets/6a5c2b59-6f5a-4d6b-92ba-80f574d3080b" />

---

## Final Remarks

We built both the SketchUp model and Unity scene entirely from scratch, ensuring originality and fidelity to the architectural design. The project captures the intersection of spirituality and nature, encouraging users to explore the pagoda's historical and cultural significance.
