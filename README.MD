# 🤖 ROSCon 2025 — Talks, Recordings & Resources

> **Singapore · October 27–29, 2025**
>
> A community-maintained index of ROSCon 2025 talks, recordings, and related repositories.
> Maintained by the ROS community — contributions welcome!

[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

---

## 📌 Quick Links

| Resource | Link |
|---|---|
| 🏠 Official ROSCon 2025 Website | [roscon.ros.org/2025](https://roscon.ros.org/2025/) |
| 🎥 Open Robotics Vimeo Showcase | [vimeo.com/openrobotics](https://vimeo.com/openrobotics/albums) |
| 📖 ROS 2 Documentation | [docs.ros.org](https://docs.ros.org) |
| 💬 Open Robotics Discourse | [discourse.openrobotics.org](https://discourse.openrobotics.org/t/roscon-2025-recordings-now-available/51241) |

> 🙏 Video archive made possible by **AMD**. All recordings are ad-free on Vimeo.

---

## 📋 Table of Contents

- [🎤 Main Talks — Day 2 & 3 (Oct 28–29)](#-main-talks--day-2--3-oct-28-29)
  - [Opening & Project Updates](#opening--project-updates)
  - [Middleware & Communications](#middleware--communications)
  - [Navigation & Planning](#navigation--planning)
  - [Simulation & Visualization](#simulation--visualization)
  - [Testing & Verification](#testing--verification)
  - [Hardware & Drivers](#hardware--drivers)
  - [Robot Learning & AI](#robot-learning--ai)
  - [Perception & Sensing](#perception--sensing)
  - [Data, Logging & Observability](#data-logging--observability)
  - [Field Deployments & Applications](#field-deployments--applications)
  - [Open-RMF Track](#open-rmf-track)
  - [Closing](#closing)
- [🛠️ Workshops — Day 1 (Oct 27)](#️-workshops--day-1-oct-27)
- [⚡ Lightning Talks](#-lightning-talks)
- [🤝 How to Contribute](#-how-to-contribute)

---

## 🎤 Main Talks — Day 2 & 3 (Oct 28–29)

### Opening & Project Updates

| Talk | Presenter(s) | 🎥 Recording | 📦 Repo / Resources |
|---|---|---|---|
| **Opening Remarks & Guest of Honor** | Geoff Biggs & Brian Gerkey | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **ROS Project Update** | Michael Carroll | [Watch](https://vimeo.com/openrobotics/albums) | [ros2/ros2](https://github.com/ros2/ros2) |
| **ros-controls Project Update** | Denis Stogl | [Watch](https://vimeo.com/openrobotics/albums) | [ros-controls/ros2_control](https://github.com/ros-controls/ros2_control) |
| **Gazebo Project Update** | Steve Peters | [Watch](https://vimeo.com/openrobotics/albums) | [gazebosim/gz-sim](https://github.com/gazebosim/gz-sim) |
| **Open-RMF Project Update** | Michael Grey | [Watch](https://vimeo.com/openrobotics/albums) | [open-rmf/rmf](https://github.com/open-rmf/rmf) |
| **Infrastructure Project Update** | Steven Ragnarök | [Watch](https://vimeo.com/openrobotics/albums) | [ros-infrastructure](https://github.com/ros-infrastructure) |

---

### Middleware & Communications

| Talk | Presenter(s) | 🎥 Recording | 📦 Repo / Resources |
|---|---|---|---|
| **rmw_what? Implementing the ROS 2 Middleware Interface** | Christophe Bédard | [Watch](https://vimeo.com/openrobotics/albums) | [ros2/rmw](https://github.com/ros2/rmw) |
| **Zenoh Strikes Back: From a New Hope to Tier-1** | Yadunund Vijay & Julien Enoch | [Watch](https://vimeo.com/openrobotics/albums) | [ros2/rmw_zenoh](https://github.com/ros2/rmw_zenoh) |
| **From DDS to Zenoh: Migrating the Dexory Autonomy ROS Stack** | Guillaume Doisy & Julien Enoch | [Watch](https://vimeo.com/openrobotics/albums) | [ZettaScaleLabs/zenoh](https://github.com/eclipse-zenoh/zenoh) |
| **Enhancing ROS 2 Communications: What's New in Fast DDS v3** | Raúl Sánchez-Mateos | [Watch](https://vimeo.com/openrobotics/albums) | [eProsima/Fast-DDS](https://github.com/eProsima/Fast-DDS) |
| **Agnocast: A ROS 2-Compatible Middleware Enabling True Zero-Copy IPC for Unsized Message Types** | Takahiro Ishikawa-Aso | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Toward Scalable Collaborative Robot Controllers: Internalizing ROS 2 with Zenoh** | Minsoo Song & Yuri Goncalves Rocha | [Watch](https://vimeo.com/openrobotics/albums) | — |

---

### Navigation & Planning

| Talk | Presenter(s) | 🎥 Recording | 📦 Repo / Resources |
|---|---|---|---|
| **On Use of Nav2 Route Server** | Steve Macenski | [Watch](https://vimeo.com/openrobotics/albums) | [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) |
| **SWAGGER: Sparse WAypoint Graph Generation for Efficient Routing** | Billy Okal | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Roadmap-Explorer: A Fast and Reliable Robot Exploration Module** | Suchetan Saravanan | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Mapping Together: Collaborative SLAM for Distributed Robot Fleets** | Achala Athukorala | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **PlanSys2, the ROS 2 Planning System: Past, Present and Future** | Francisco Martin Rico | [Watch](https://vimeo.com/openrobotics/albums) | [PlanSys2/ros2_planning_system](https://github.com/PlanSys2/ros2_planning_system) |

---

### Simulation & Visualization

| Talk | Presenter(s) | 🎥 Recording | 📦 Repo / Resources |
|---|---|---|---|
| **Realistic Terrain Simulation in Gazebo** | Ian Chen & Jenn Nguyen | [Watch](https://vimeo.com/openrobotics/albums) | [gazebosim/gz-sim](https://github.com/gazebosim/gz-sim) |
| **Ray-Tracing Everywhere: Vendor Agnostic Ray Tracing in Gazebo** | Arjo Chakravarty | [Watch](https://vimeo.com/openrobotics/albums) | [gazebosim/gz-rendering](https://github.com/gazebosim/gz-rendering) |
| **Introducing the New ROS Simulation Standard** | Adam Dabrowski & Ayush Ghosh | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Evaluation of ROS 2 Simulators 2025** | Ángel Soriano | [Watch](https://vimeo.com/openrobotics/albums) | — |

---

### Testing & Verification

| Talk | Presenter(s) | 🎥 Recording | 📦 Repo / Resources |
|---|---|---|---|
| **Replay Testing: Fast, Iterative Robotics Testing** | Troy Gibb | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Rtest - Reliable ROS 2 Unit Tests Framework** | Mariusz Szczepanik | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Formally Verifying Robot Behavior with Statistical Model Checking** | Christian Henkel | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Detecting Complex Events in ROS Data** | Benji Barash | [Watch](https://vimeo.com/openrobotics/albums) | [roboto-ai](https://github.com/roboto-ai) |
| **Traceability System for Autonomous Robots** | Laura Inyesto-Alonso & Claudia Álvarez-Aparicio | [Watch](https://vimeo.com/openrobotics/albums) | — |

---

### Hardware & Drivers

| Talk | Presenter(s) | 🎥 Recording | 📦 Repo / Resources |
|---|---|---|---|
| **From Sensors to Sensei: Mastering ROS Hardware with Analog Devices** | Sarvesh Pimpalkar | [Watch](https://vimeo.com/openrobotics/albums) | [analogdevicesinc/adi_ros2](https://github.com/analogdevicesinc/adi_ros2) |
| **Running ROS Natively on an Industrial Robot's Control Box** | Rune Søe-Knudsen & Felix Exner | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **ros2_control goes Industrial** | Dr. Denis Stogl | [Watch](https://vimeo.com/openrobotics/albums) | [ros-controls/ros2_control](https://github.com/ros-controls/ros2_control) |
| **Motions Made Easy: Simplifying Repetitive Robot Motions** | Sai Kishor Kothakota & Luca Marchionni | [Watch](https://vimeo.com/openrobotics/albums) | [ros-controls](https://github.com/ros-controls) |
| **Unlock FFmpeg in ROS 2: A Flexible Audio/Video Pipeline** | Yoshito Okada | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Seeing is Believing: Enhancing Robot Acceptance with Perception-Aware LED Feedback** | Matthias Schörghuber | [Watch](https://vimeo.com/openrobotics/albums) | — |

---

### Robot Learning & AI

| Talk | Presenter(s) | 🎥 Recording | 📦 Repo / Resources |
|---|---|---|---|
| **Advancing Robot Learning with ROS 2** | Tiffany Cappellari & Sebastian Castro | [Watch](https://vimeo.com/openrobotics/albums) | [ros-planning](https://github.com/ros-planning) |
| **Building Foundation Models for Generalist Robots: Insights and Challenges in Robot Learning** | You Liang Tan | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Easy ROS-based AI Robot Development with genesis/libtorch** | Masaya Kataoka | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **ROS 2: The Backbone for Physical AI** | Yadunund Vijay | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Real-Time Meets Cloud Native - ROS 2 on RTOS and Linux with Kubernetes** | Andrei Kholodnyi | [Watch](https://vimeo.com/openrobotics/albums) | — |

---

### Perception & Sensing

| Talk | Presenter(s) | 🎥 Recording | 📦 Repo / Resources |
|---|---|---|---|
| **Smarter Vision Pipelines for ROS 2: Compress, Transport, and Sync at Scale** | Guilherme Cardoso de Souza Rodrigues & Markus Hofstätter | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Cloudini: the Pointcloud Compression Library That You Missed in Your Life** | Davide Faconti | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **From Off-the-Shelf Drones to Research Platforms** | Andriy Sarabakha | [Watch](https://vimeo.com/openrobotics/albums) | — |

---

### Data, Logging & Observability

| Talk | Presenter(s) | 🎥 Recording | 📦 Repo / Resources |
|---|---|---|---|
| **Help Me with the Bags: Quick & Easy ROS 2 Data Handling** | Markus Hofstätter | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Open-source Robotics Observability at Scale!** | Guillaume Beuzeboc | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Simplifying Diagnostics: A Ready to Use Robot Webserver** | Hilary Luo | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **ROS 2 Logging Subsystem and Alternative Syslog Implementation** | Tomoya Fujita | [Watch](https://vimeo.com/openrobotics/albums) | [ros2/rcl_logging](https://github.com/ros2/rcl_logging) |

---

### Field Deployments & Applications

| Talk | Presenter(s) | 🎥 Recording | 📦 Repo / Resources |
|---|---|---|---|
| **From Simulation to Soil: Lessons from a ROS 2-Powered Tractor** | Tim Clephas & Ferry Schoenmakers | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Peer-2-Peer Agriculture Robotics Communication, Planning, Coverage and Task Allocation** | Trim Bresilla | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Transforming Robotics with Auto Bots from Outer Space** | Rob Woolley | [Watch](https://vimeo.com/openrobotics/albums) | — |

---

### Developer Experience & Tooling

| Talk | Presenter(s) | 🎥 Recording | 📦 Repo / Resources |
|---|---|---|---|
| **Our Ten Most Common ROS Questions Answered** | Katherine Scott | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Practical Guide for ROS 2 on Windows** | Kimberly McGuire | [Watch](https://vimeo.com/openrobotics/albums) | [ros2/ros2_documentation](https://github.com/ros2/ros2_documentation) |
| **Solving ROS Package Management with Pixi and RoboStack** | Ruben Arts | [Watch](https://vimeo.com/openrobotics/albums) | [RoboStack/robostack](https://github.com/RoboStack/robostack-staging) |
| **Escape Velocity: Smarter, Cleaner ROS 2 Launch Patterns** | Emerson Knapp | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Build, Iterate, Deploy - A Modular ROS 2 Workflow that Scales** | Cristian Paul Dragomir | [Watch](https://vimeo.com/openrobotics/albums) | — |
| **Introducing rclrs: the ROS 2 Client Library for Rust** | Esteve Fernández | [Watch](https://vimeo.com/openrobotics/albums) | [ros2/rclrs](https://github.com/ros2/rclrs) |

---

### Open-RMF Track

| Talk | Presenter(s) | 🎥 Recording | 📦 Repo / Resources |
|---|---|---|---|
| **Robots at Your Service: Deploying Open-RMF in Singapore's Hospitality Industry** | Vyshyamveetil Mohammed Ibrahim & Bey Hao Yun | [Watch](https://vimeo.com/openrobotics/albums) | [open-rmf/rmf](https://github.com/open-rmf/rmf) |
| **Optimizing Hospital Robotics Deployments with Open RMF: Implementing Emergency Handling and Dynamic Task Orchestration** | Mohammad Asraf Bin Abdul Hamid & Tey Leong Teck | [Watch](https://vimeo.com/openrobotics/albums) | [open-rmf/rmf](https://github.com/open-rmf/rmf) |
| **Orchestrating Interoperable Indoor Robots at Scale with Open-RMF: The Changi Airport Experience** | Alphonsus Tay & Tan Jin Yang | [Watch](https://vimeo.com/openrobotics/albums) | [open-rmf/rmf](https://github.com/open-rmf/rmf) |
| **Workflows for Multi-Agent Orchestration** | Michael Grey | [Watch](https://vimeo.com/openrobotics/albums) | [open-rmf/rmf](https://github.com/open-rmf/rmf) |

---

### Closing

| Talk | Presenter(s) | 🎥 Recording |
|---|---|---|
| **Panel: Ask us anything! With the OSRF Board of Directors + Closing Remarks** | Ryan Gariepy & Brian Gerkey | [Watch](https://vimeo.com/openrobotics/albums) |

---

## 🛠️ Workshops — Day 1 (Oct 27)

> Workshops were held on Day 1 (October 27) at the Suntec Singapore Convention & Exhibition Centre. Some required separate registration.

### Official Workshops

| Workshop | Presenter(s) | Organization | 📦 Repo / Resources |
|---|---|---|---|
| **ros2_control: Fun With Robot Drivers** | Denis Stogl, Bence Magyar | b»robotized / Locus Robotics | [ros-controls/ros2_control](https://github.com/ros-controls/ros2_control) |
| **Scalable Multi-Robot Scene Workflows Using ROS Simulation Interfaces in Isaac Sim** | Ayush Ghosh, Raffaello Bonghi | NVIDIA | [isaac-sim](https://developer.nvidia.com/isaac/sim) |
| **Hands-On Aerial Robotics Using PX4 and ROS 2** | Ramon Roche, Patrik Pordi, Beniamino Pozzan | Dronecode Foundation / ARK Electronics / PX4 | [Dronecode/roscon-25-workshop](https://github.com/Dronecode/roscon-25-workshop) |
| **ROS 2 Networking Redefined: Deep Dive into RMW Zenoh** | Julien Enoch, Alejandro Hernández Cordero, Yadunund Vijay | ZettaScale / Honu Robotics / Intrinsic | [ZettaScaleLabs/roscon2024_workshop](https://github.com/ZettaScaleLabs/roscon2024_workshop) |
| **ROS 2 & micro-ROS Dive In: Low-Cost Underwater Robotics** | Abu Bakr Azam, Mohammad Aasim Khan, Nguyen Trung Kien | Nanyang Technological University | — |
| **How to Implement a Full ROS 2 Application: a Tic-Tac-Toe Player Robot** | Ricardo Tellez, Cynthia Zeng | The Construct / AgileX | — |
| **Introducing AI PCs for Embodied AI** | Graham Schelle, Sonya Yang, Joshua Lu, Ken O'Brien, Chun-Yi Lee | AMD / National Taiwan University | [AMD Robotics](https://www.amd.com/en/solutions/industrial/robotics.html) |
| **Reinforcement Learning for Deliberation in ROS 2** | Christian Henkel, Sebastian Castro | Bosch Research / RAI Institute | [ros discourse wg-delib](https://discourse.ros.org/tag/wg-delib) |
| **Introduction to ROS and Building Robots with Open-Source Software** | Geoff Biggs, Katherine Scott | Open Robotics / Intrinsic | [kscottz/turtlebot4_docker](https://github.com/kscottz/turtlebot4_docker) |

### Sponsor Mini-Workshops (Free, No RSVP Required)

| Workshop | Presenter(s) | Organization | 📦 Resources |
|---|---|---|---|
| **Hands-On Workshop with ROS 2 and MoveIt Pro** | PickNik Robotics Team | PickNik Robotics | [picknik.ai/roscon](https://picknik.ai/roscon/workshop/2025/moveit/2025/10/06/Hands-On-Workshop-with-ROS-2-and-MoveIt-Pro-at-ROSCon-2025.html) |
| **Zenoh Drakes of a Flame** | Angelo Corsaro, Julien Enoch, Yu-Yuan Yuan | ZettaScale | [eclipse-zenoh/zenoh](https://github.com/eclipse-zenoh/zenoh) |
| **Automate Your ROS Bag Analysis: Getting Started with Roboto** | Yves Albers & Benji Barash | Roboto AI | [roboto-ai](https://roboto.ai) |
| **Demonstrating the Canonical Observability Stack for Devices** | Guillaume Beuzeboc | Canonical | [ubuntu/juju](https://github.com/juju/juju) |
| **Hands-on ROS 2 with Rubik Pi 3** | Qualcomm Team | Qualcomm Technologies | — |
| **Evolving ROS 2 for Real-Time Control of Learned Policy-Driven Robots** | Hemal Shah | NVIDIA | — |

---

## ⚡ Lightning Talks

Lightning talks are a beloved ROSCon tradition — rapid-fire 1–2 minute community presentations. ROSCon 2025 featured three lightning talk blocks.

### ⚡ In-Advance Lightning Talks

> 🎥 [Watch full block on Vimeo](https://vimeo.com/openrobotics/albums)

These were pre-submitted and scheduled ahead of the conference.

### ⚡ Lightning Talks — Day 1

| Talk | Presenter(s) | Organization | 📦 Repo / Resources |
|---|---|---|---|
| **Plugging ROS 2 into Legacy Robotics: Lessons from FANUC Integration** | Jayden Oyola Risco | GGI Robotic | — |
| **Let‘s forbid python launch files!** | Dr. Denis Stogl | b>>robotized | — |
| **ROS2 on Circuitpython** | Lucian Copeland | — | — |
| **RDK: A Powerful Hardware-Software Integration Platform for ROS 2 Applications** | Robbin Hu | D-Robotics | — |
| **A (quick) overview of ROS@Bosch​** | Christian Henkel | Bosch Research | — |
| **Bridging ROS 1 and 2 with Ubuntu 24.04 and Jazzy in Production** | Vatan Aksoy Tezer | KABAM Robotics | — |
| **Robotics for Everyone: Connecting Latin America Through ROS Community** | Catalina Caycedo | RAS Javeriana IEEE St. Ch. | — |
| **MoboBot (The Nigerian TurtleBot)** | Samuel Obiagba | Robocre8 | — |
| **Motion Planning For The People** | Sebastian Castro | — | — |
| **Does the World need a Horseshitbot** | Alexis Wiasmitinow | — | — |
| **Automatic Sensor Calibration for (Better Than) Pixel-Perfect Sensor Fusion** | William Sitch | Main Street Autonomy | — |
| **New ROS2 Broadcaster: Battery State Broadcaster** | Yara Shahin | b>>robotized | — |
| **Challenges for AMR & MM** | Brandon Koh | CHART | — |
| **ros2_fmt_logger** | Tim Clephas | Nobleo Autonomous Solutions | — |
| **YASMIN (Yet Another State MachINe)** | Miguel Á. González-Santamarta | Universidad de León | — |
| **ros-python-wheels: Pip-installable ROS packages** | Yifei Cheng | Remedy Robotics | — |
| **Dynamic Safety for ROS 2** | Pietro Pierpaoli | 3Laws Robotics | — |
| **Stamp out your twist problems!** | Josh Newans | — | — |
| **Simple cmake in interface packages** | Kotar YOSHIMOTO | TIER IV, Inc | — |
| **Enhancement to Open-RMF: Zone Feature with Sensor-Augmented Dynamic Goal** | Chee Keai Jiang | Changi General Hospital | — |
| **Running Autoware with Zenoh** | ChenYing Kuo | ZettaScale | — |
| **Design by contract for robust robotics software** | Zoltán Rési | ROBOSS PTE LTD | — |

> 🎥 [Watch full block on Vimeo](https://vimeo.com/openrobotics/albums)

### ⚡ Lightning Talks — Day 2

| Talk | Presenter(s) | Organization | 📦 Repo / Resources |
|---|---|---|---|
| **OSRF Infra 24.04 Migration in 2.04 minutes** | Cristóbal Arroyo | OSRF Infrastructure Committeer & Ekumen DevOps Engineer | — |
| **Beyond Boundaries: Redefining Access to Technical Education** | Irina Terebiznik | National Technological University | — |
| **Franka Robotics Open-source activities** | Baris Yazici | Franka Robotics - Robotics Software Engineer | — |
| **FOSDEM Robotics and simulation devroom** | Kimberly McGuire | Independent Contractor | — |
| **The Future of the Engineering Workforce is here** | Shaur Kumar | — | — |
| **ROS at the Airport** | Ruben Arts | Prefix.dev | — |
| **Monobranch ROS Packages** | Emerson Knapp | Polymath Robotics | — |
| **Stratospheric Gliders, Reusable Radiosondes and more!** | Junwoo Hwang | Independent Researcher | — |
| **Introducing Space Grade Linux** | Ramon Roche | Linux Foundation | — |
| **Isaac: Open Robotics Development Platform** | Raffaello Bonghi | Technical Marketing & Community Support | — |
| **Analog Devices ROS Drivers now available!** | Maggie Maralit | Analog Devices | — |
| **Low-Cost Underwater Robotics with ROS 2** | Abu Bakr Azam | Nanyang Technological University | — |
| **DWARL** | Ferry Schoenmakers | — | — |
| **Wind turbine repairs with robots** | Ivars Renge | Head of R&D, Aerones | — |
| **Autonomous and Remote Control System for Construction Machinery** | Ryodo Tanaka | CEO | — |
| **Accerating robot HW/product development** | Jakub Suchanek | Fabrica AI co-founder & CEO | — |
| **ROS 2 => Asterics Bridge** | Francisco J. Rodriguez Lera | Universidad de León (Spain) | — |
| **Chaos to Calm** | Akash Vibhute | Chief Shepherd | — |
| **Pixi and cppyy to use C++ stuff in Python quickly** | Sam Pfeiffer | Wayve | — |
| **PRISM FZF Rosbag Tool** | Sai Rohitth Chiluka | Peppermint Robotics | — |
| **Teaching Robots to Dive - Open-Source Underwater Robotics Course** | Daniel Duecker | TU Munich & TU Hamburg | — |
| **Post-ROSCon Hackathon this Friday!** | Arjo Chakravarty | Intrinsic | — |

> 🎥 [Watch full block on Vimeo](https://vimeo.com/openrobotics/albums)

---

## 🤝 How to Contribute

This repository is a **community effort** — your contributions make it better for everyone. Here's how you can help:

### What we need most

- ✅ **Direct Vimeo links** to individual talk recordings (replace the `Watch` placeholder links)
- ✅ **GitHub repo links** for talks that reference open-source projects
- ✅ **Slide deck links** (once OSRF publishes them)
- ✅ **Corrections** to presenter names, affiliations, or talk titles

### Step-by-step: How to open a Pull Request

1. **Fork** this repository by clicking the `Fork` button at the top right of the page.

2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/roscon2025-talks.git
   cd roscon2025-talks
   ```

3. **Create a new branch** for your change:
   ```bash
   git checkout -b add-vimeo-link-cloudini
   ```

4. **Edit `README.md`** with your contribution — for example, replacing a generic Vimeo link with a direct talk URL, or adding a missing repo.

5. **Commit** your changes with a clear message:
   ```bash
   git add README.md
   git commit -m "Add Vimeo link for Cloudini talk (Davide Faconti)"
   ```

6. **Push** to your fork:
   ```bash
   git push origin add-vimeo-link-cloudini
   ```

7. Open a **Pull Request** on GitHub. Fill in the PR title and description — explain what you added or fixed.

### Contribution Guidelines

- **One change per PR** is preferred (e.g., one talk's links) — it makes reviewing faster.
- Verify that links are working before submitting.
- Use the official Open Robotics Vimeo account for recording links.
- Do not add affiliate links or promotional content.
- Be respectful — this is a community resource for everyone.

### Adding a New Talk or Missing Entry

If you find a talk that's missing from this list, add it using this row format:

```markdown
| **Talk Title** | Presenter Name | [Watch](VIMEO_URL) | [repo-org/repo-name](GITHUB_URL) |
```

If there is no public repo for a talk, use `—` in the repo column.

---

## ⭐ Acknowledgements

- All recordings are generously provided **ad-free** by [Open Robotics](https://www.openrobotics.org/), made possible by **AMD**.
- This index is maintained by the ROS community and is not an official OSRF resource.
- ROSCon 2025 was held at **Suntec Singapore Convention & Exhibition Centre**, October 27–29, 2025.

---

*Missing something? Open an issue or PR — see [How to Contribute](#-how-to-contribute) above.*
