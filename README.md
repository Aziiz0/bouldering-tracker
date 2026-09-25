# Chalk & Beta — Indoor Bouldering Tracker App

**Chalk & Beta** is an interactive web-based application designed for indoor climbers and boulderers. It enables you to photograph climbing walls, visually map out routes and sequences, record gym vs. perceived difficulty grades, tag hold types and movement techniques, and analyze performance trends through an analytics dashboard.

---

## 🌟 Key Features

### 1. Photo Capture & Interactive Route Mapping ("Beta Mapper")
- **Live Camera / File Upload**: Snap a photo directly of any bouldering wall or upload an existing picture.
- **Sample Wall Generator**: Includes a built-in virtual boulder wall to try out route mapping immediately.
- **Hold Categorization**:
  - **Start** (Green `S`): Identifies starting hold(s).
  - **Hand Holds** (Blue `1`, `2`, `3`...): Sequenced hand placements.
  - **Foot Holds** (Orange `F`): Dedicated foot chips and jibs.
  - **Crux Hold** (Red `X`): Highlighting the hardest movement or stopper hold.
  - **Top / Finish** (Gold `T`): Match finish hold.
- **Directional Path & Flow Arrows**: Connects holds in sequence with dashed lines and directional arrowheads to illustrate the route's direction.
- **Freehand Beta Pen**: Draw custom body trajectories, hip motion lines, or dynamic dyno arcs.
- **Undo & Clear Controls**: Easily adjust markers or reset your canvas.

---

### 2. Difficulty & Grade Tracking
- **Gym Grade (Posted)**: Hueco V-Scale (`VB` through `V12+`) or Fontainebleau scale.
- **Felt Grade**: What the boulder problem actually felt like to you.
- **Grade Accuracy Feel**: Tag climbs as **Soft**, **Benchmark** (accurate), **Stiff**, or **Sandbagged**.
- **Effort Rating (RPE 1-10)**: Rate of Perceived Exertion to quantify physical intensity.
- **Attempts Counter**: Track whether a climb was flashed (1st try), sent in a session, or is an ongoing project.

---

### 3. Movement Techniques & Grip Profiles
- **Technique Tags**: Dyno, Heel Hook, Toe Hook, Drop Knee, Knee Bar, Mantle, Smear, Flagging, Bicycle, Campus, Gaston, Undercling, Compression, Rose Move, Deadpoint, Coordination.
- **Hold Types**: Crimps, Slopers, Pinches, Pockets, Jugs, Volumes, Edges, Jam/Crack.
- **Wall Profile**: Slab (<90°), Vertical (90°), Slight Overhang (10°-30°), Steep Overhang (30°-50°), Roof/Cave (>50°).

---

### 4. Performance Analytics Dashboard
- **Grade Pyramid**: Bar breakdown showing volume of sends across grades.
- **Difficulty Feel Index**: Visual distribution of Soft vs. Benchmark vs. Sandbagged sets.
- **Top Movement Techniques**: Highlights which techniques you rely on most and which areas need training.
- **Wall Angle Distribution**: Balance between slab, vertical, and steep cave climbing.

---

### 5. Local Storage & Portability
- **100% Client-Side Privacy**: All climb entries, images, and beta maps are saved in browser LocalStorage.
- **JSON Backup & Restore**: Export your entire logbook as a single JSON file and restore it on any device.

---

## 🚀 How to Run the App
1. Extract the `.zip` archive.
2. Double-click `index.html` to open it in Google Chrome, Safari, Firefox, or Edge on desktop or mobile.
3. No build tools, servers, or installations required!
