# GitHub Profile & Portfolio Checklist

Action items to finalize [github.com/diogoccprado](https://github.com/diogoccprado) for robotics labs, research internships, and engineering recruiters.

---

## 1. Repository renames

| Current name | Recommended name | Local folder | Status |
|--------------|------------------|--------------|--------|
| `Robocup-Work-2024` | `robocup-work-robot-software-2024` | `~/Robocup-Work-2024` | TODO |
| `hovercraft_prj` | `hovercraft-robot-control` | `~/hovercraft_prj` | TODO |
| `LiDAR---Camera-Calibration---Annotations-and-Fixes-` | `lidar-camera-calibration-ros2` | `~/LiDAR---Camera-Calibration---Annotations-and-Fixes-` | TODO |
| `genesis-go2-sim` | `genesis-go2-ros2-bridge` (optional) | `~/genesis-go2-sim` | TODO (optional) |

After each rename, update local remote:

```bash
git remote set-url origin git@github.com:diogoccprado/<NEW_NAME>.git
```

Rename commands are in each repo's `GITHUB_METADATA.md`.

---

## 2. About descriptions (paste in GitHub Settings → General)

| Repo | About description |
|------|-----------------|
| `robocup-work-robot-software-2024` | Robot software stack for RoboCup@Work experiments with C++/Python ROS packages, launch files, Docker setup, and simulation assets. |
| `hovercraft-robot-control` | Control and software stack for a real hovercraft robot, including embedded firmware, host-side tools, trajectory/control logic, logging, and visualization. |
| `lidar-camera-calibration-ros2` | ROS 2 workflow for LiDAR-camera extrinsic calibration using Livox Mid-360, RealSense D435, rosbag2, SAM masks, and CalibAnything. |
| `genesis-go2-sim` | Physics-based Unitree Go2 Genesis simulation with joint-level ROS 2 interface for MPC, WBC, and RL control development. |
| `diogoccprado` | Undergraduate robotics researcher — ROS 2, SLAM, semantic mapping, perception, control, and robot learning. |
| `diogoccprado.github.io` | Personal robotics portfolio site. |

---

## 3. Topic lists

### robocup-work-robot-software-2024
`robocup`, `robocup-at-work`, `robotics`, `ros`, `mobile-manipulation`, `navigation`, `cplusplus`, `python`, `cmake`, `docker`

### hovercraft-robot-control
`robotics`, `hovercraft`, `embedded-systems`, `control`, `trajectory-tracking`, `esp32`, `mqtt`, `python`, `cplusplus`, `real-robot`

### lidar-camera-calibration-ros2
`ros2`, `lidar`, `camera-calibration`, `extrinsic-calibration`, `livox`, `realsense`, `calibanything`, `segment-anything`, `computer-vision`, `robotics`

### genesis-go2-sim
`robotics`, `ros2`, `simulation`, `legged-robotics`, `unitree-go2`, `genesis`, `mpc`, `python`

---

## 4. Pinned repositories (recommended order)

Pin up to 6 repos on your GitHub profile:

1. `diogoccprado.github.io` — portfolio site (pin once deployed)
2. `genesis-go2-sim` (or `genesis-go2-ros2-bridge` after rename)
3. `lidar-camera-calibration-ros2`
4. `hovercraft-robot-control`
5. `robocup-work-robot-software-2024`
6. _Later:_ `semantic-mapping-nav` or `adaptive-odom-filter-ros2` when public and cleaned

**Do not pin yet:** `adaptive_odom_filter` (active development, upstream fork), `diogoccprado` profile README (not a project).

---

## 5. New repos to create and push

| Repo | Local folder | Purpose |
|------|--------------|---------|
| `diogoccprado` | `~/diogoccprado` | GitHub profile README |
| `diogoccprado.github.io` | `~/diogoccprado.github.io` | Portfolio website |

---

## 6. Media to add later

| Repo / site | Media |
|-------------|-------|
| Hovercraft | Physical platform photo, autonomous trajectory video, EKF plot |
| RoboCup | Competition arena photo/video, RViz screenshot, AprilTag manipulation demo |
| LiDAR calibration | RViz alignment screenshot, projection validation image |
| Genesis Go2 | Sim screenshot or short locomotion clip |
| ARGUS / semantic mapping | System diagram, mapping demo (when repo is public) |
| Portfolio site | Project thumbnails in `index.html` card sections |
| Profile README | Optional: no images needed; keep text-focused |

---

## 7. LinkedIn Featured section

Link these (once repos are renamed and media is added):

1. **Portfolio site** — `https://diogoccprado.github.io`
2. **Genesis Go2 ROS 2 Bridge** — legged robot simulation + control interface
3. **LiDAR-Camera Calibration** — perception infrastructure for semantic mapping
4. **Real Hovercraft Control System** — embedded + host-side real robot project
5. **RoboCup@Work Robot Software** — competition robotics systems
6. _Later:_ ARGUS / semantic mapping paper or repo

Write each Featured item as: **title + 1-sentence technical hook + link**.

---

## 8. GitHub.io site links

Ensure `index.html` links to:

- All public project repos (update URLs after renames)
- GitHub profile
- LinkedIn (TODO)
- CV PDF (TODO)
- Email (TODO)

Cross-link: profile README → `diogoccprado.github.io`, site footer → GitHub.

---

## 9. Profile README TODOs

In `~/diogoccprado/README.md`:

- [ ] Add LinkedIn URL
- [ ] Add CV PDF link
- [ ] Add ARGUS / semantic mapping repo when public
- [ ] Update repo links after renames
- [ ] Add adaptive odom filter link when fork is cleaned and public

---

## 10. Repos to handle later

| Repo | Action | Reason |
|------|--------|--------|
| `adaptive_odom_filter` | Light review only; fork/clean later | Active development on `ros2-dev`; upstream is `gilmarpcjunior/adaptive_odom_filter` |
| ARGUS / semantic mapping | Add when paper/repo is ready | In progress |
| Robot Learning exercises | Add to coursework when cleaned | Not portfolio-ready |
| Generative AI assignment | Add to coursework when repo is public | Pending |

---

## 11. Remaining TODOs before sharing with recruiters/labs

### Documentation
- [ ] Commit and push hovercraft positioning fix (real hardware, not simulation)
- [ ] Commit and push RoboCup / LiDAR polish
- [ ] Create and push `diogoccprado` profile README repo
- [ ] Create and push `diogoccprado.github.io` site

### GitHub settings
- [ ] Rename repos (see section 1)
- [ ] Set About descriptions (section 2)
- [ ] Add topics (section 3)
- [ ] Pin repos (section 4)
- [ ] Set profile bio: _"Undergraduate robotics researcher · ROS 2 · SLAM · perception · control"_
- [ ] Add portfolio URL to GitHub profile website field

### Content
- [ ] Add project media (section 6)
- [ ] Fill LinkedIn Featured (section 7)
- [ ] Add CV PDF to site and profile
- [ ] Write 2–3 sentence contribution summaries for each pinned repo

### Optional polish
- [ ] Rename `genesis-go2-sim` → `genesis-go2-ros2-bridge`
- [ ] Add `requirements.txt` to hovercraft repo
- [ ] Add Open Graph meta tags to portfolio site for link previews

---

## 12. Commit & push commands (run manually)

### Hovercraft (positioning fix)
```bash
cd ~/hovercraft_prj
git add README.md PORTFOLIO_CARD.md GITHUB_METADATA.md
git commit -m "Reposition as real physical hovercraft robotics project"
git push origin main
```

### RoboCup (polish)
```bash
cd ~/Robocup-Work-2024
git add README.md PORTFOLIO_CARD.md
git commit -m "Polish RoboCup team systems positioning for portfolio"
git push origin main
```

### LiDAR calibration (polish)
```bash
cd ~/LiDAR---Camera-Calibration---Annotations-and-Fixes-
git add README.md PORTFOLIO_CARD.md
git commit -m "Strengthen perception infrastructure positioning"
git push origin main
```

### Profile README (new repo)
```bash
cd ~/diogoccprado
git init && git add README.md SETUP.md
git commit -m "Add GitHub profile README"
git branch -M main
git remote add origin git@github.com:diogoccprado/diogoccprado.git
git push -u origin main
```

### Portfolio site (new repo)
```bash
cd ~/diogoccprado.github.io
git init && git add .
git commit -m "Initial robotics portfolio site scaffold"
git branch -M main
git remote add origin git@github.com:diogoccprado/diogoccprado.github.io.git
git push -u origin main
```

> Create the `diogoccprado` and `diogoccprado.github.io` repos on GitHub first (empty, no README) before pushing.

---

_Last updated: 2026-07-08_
