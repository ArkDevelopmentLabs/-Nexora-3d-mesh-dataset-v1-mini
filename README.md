# Nexora 3D Mesh Dataset v1 Mini

The **Nexora 3D Mesh Dataset v1 Mini** is a curated collection of lightweight, high-quality 3D mesh assets designed for AI research, 3D machine learning, game development prototyping, and computer graphics experimentation.

This dataset is developed and maintained by **ArkDevelopmentLabs / ArkAiLab (ADL)** as part of the Nexora open dataset ecosystem.

---

## Dataset Summary

Nexora 3D Mesh Dataset v1 Mini contains a carefully selected set of **compact 3D meshes** provided in **GLB (binary glTF)** format.  
All assets are small in size, portable, and suitable for modern 3D workflows, making this dataset easy to download, inspect, and integrate into research pipelines.

This mini release serves as an initial, stable foundation before larger 3D dataset expansions.

---

## Key Features

- High-quality 3D meshes in **GLB format**
- Lightweight assets (optimized for size and portability)
- Single-file meshes with embedded textures
- Compatible with Blender, Unity, Unreal Engine, and web viewers
- Suitable for AI, ML, and graphics research
- Clean structure and clear licensing
- Designed for scalability (Mini → Medium → Large)

---

## Use Cases

This dataset is suitable for:

- 3D machine learning research
- Geometry and shape learning
- Text-to-3D and image-to-3D experimentation
- Game asset prototyping
- Simulation and visualization
- Dataset pipeline testing
- Educational and academic use

---

## Supported Tasks

| Task | Description |
|-----|-------------|
| 3D Vision | Shape and geometry learning |
| Computer Graphics | Rendering and asset workflows |
| Machine Learning | 3D representation learning |
| Simulation | Scene and asset testing |
| Dataset Research | Benchmarking and evaluation |

---

## Dataset Structure

```
nexora-3d-mesh-dataset-v1-mini/
├─ models/
│ ├─ mesh_0001.glb
│ ├─ mesh_0002.glb
│ └─ ...
├─ previews/
│ ├─ mesh_0001.png
│ └─ ...
├─ ATTRIBUTION.txt
├─ LICENSE
└─ README.md
```


---

## File Format

- **Primary format:** `.glb` (binary glTF)
- Single-file meshes with embedded textures
- Optimized for interoperability and compact storage

---

## Licensing

### Dataset Structure & Metadata
Licensed under the **MIT License**.

### 3D Mesh Assets
All 3D meshes included in this dataset are sourced from creators and platforms that allow redistribution under **Creative Commons (CC0 or CC-BY)** or equivalent open licenses.

- CC0 assets are in the public domain.
- CC-BY assets retain attribution to their original creators.

Full attribution details are provided in `ATTRIBUTION.txt`.

---

## Attribution

If you use this dataset in research, training, or publications, attribution is appreciated:

**JackMa — ArkDevelopmentLab / ArkAiLab (ADL)**

---

## How to Load (Hugging Face)

```python
from datasets import load_dataset

dataset = load_dataset("ArkAiLab-Adl/nexora-3d-mesh-dataset-v1-mini")
print(dataset)
```

## Download

**Hugging Face**
https://huggingface.co/datasets/ArkAiLab-Adl/Nexora-3d-mesh-dataset-v1-mini

**GitHub**
https://github.com/ArkDevelopmentLabs/Nexora-3d-mesh-dataset-v1-mini

## Credits

Developed by ArkDevelopmentLabs (ADL)
Dataset creators: JackMa (ArkDevelopmentLab / ArkAiLab)
