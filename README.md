# 🎮 Cub3D  
> *My first RayCaster using MiniLibX — inspired by Wolfenstein 3D*

---

## 📌 Summary  
**Cub3D** is a graphical project inspired by the legendary game **Wolfenstein 3D**—the first-ever first-person shooter (FPS) developed in 1992 by id Software. This project introduces you to the fundamentals of **raycasting**, where you render a 3D-like world from a 2D map using C and the **MiniLibX** graphics library.

---

## 🎯 Objectives  
- Understand and implement the **raycasting** technique  
- Practice **algorithm design**, **memory management**, and **graphics programming** in C  
- Use **MiniLibX** to render a dynamic 3D environment  
- Enable **first-person navigation** inside a 2D maze

---

## ⚙️ Mandatory Features  
- ✅ **.cub** scene file parsing  
- ✅ Render walls with textures for each direction: `NO`, `SO`, `WE`, `EA`  
- ✅ Floor (`F`) and ceiling (`C`) colors defined in RGB  
- ✅ Player movement:
  - `W`, `A`, `S`, `D` to move
  - Left/Right arrows to rotate
  - `ESC` or red window cross to quit

### 🧩 Map Parsing & Validation  
- The map must:
  - Be fully enclosed by walls
  - Contain only: `0`, `1`, `N`, `S`, `E`, `W`

## 🧪 Compilation & Usage
Compile with: `make`

Run with: `./cub3D map.cub`

## ⭐ Bonus (Only if mandatory is perfect)
Minimap

Mouse controls
