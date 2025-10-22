ROS 2 Examples 🚀

This repository represents more than just code — it’s my personal deep dive into the Robot Operating System 2 (ROS 2), exploring its core subsystems, tools, and philosophies that power the next generation of intelligent robots.

I’m using this collection to understand, experiment, and build — from simple publishers and subscribers to image processing, navigation, and advanced ROS 2 design patterns.

🧭 Why This Project Matters to Me

Robotics is where code meets motion — where logic turns into life.
Through ROS 2, I’m learning how distributed systems, real-time control, and autonomous behavior come together to make robots think and move.

Each example here is more than a tutorial — it’s a small step toward my dream of building intelligent systems that can see, decide, and act in the real world.

⚙️ Requirements

Git – for version control and collaboration

ROS 2 Jazzy Jalisco – the backbone of all examples

GCC / C++17 compiler or any modern toolchain

Python 3 – for scripting and node development

CMake – to build projects cleanly

VS Code (recommended) – my preferred IDE setup

Docker (optional) – for isolated, reproducible builds

Clone the repository:

git clone  https://github.com/Keerthivarman-S-D/IOT_ROS2.git


To update later:

git checkout jazzy
git pull

🐳 Docker Containers

I’m fascinated by how ROS 2 integrates with Docker — this repo supports containers like:

x86-dev

x86-cudev

armv8-dev

These help me build and test code across architectures without installing ROS 2 directly. It’s an elegant approach to scalable robotics development.

🧩 Code Organization

The repository is organized with clarity and purpose:

src/
 ├── cpp/           → C++ examples  
 │   ├── advanced/  → multithreading, plugins, namespaces  
 ├── python/        → Python examples  
 │   ├── advanced/  → deeper-level ROS 2 internals  
 └── ros2_examples_interfaces/  → shared message definitions


Every file is well-commented — //! in C++ and #! in Python explain the why behind the code, not just the what.

💡 Key Example Packages
🧩 Core

ros2_examples_interfaces – interface-only package

ros2_examples_bringup – conventions and launch file design

⚙️ C++ Examples

topic_pubsub_cpp – publishers & subscribers

custom_topic_cpp – custom message types and QoS

simple_service_cpp – client/server basics

parameters_example_cpp – handling node parameters

actions_example_cpp – computing Fibonacci with actions

plugins_demo – implementing and using pluginlib in ROS 2

🔬 Advanced

namespaces_examples – remapping and namespaces

smp_example – multithreaded ROS 2 applications

complete_actions_cpp – realistic action handling with executors

🎥 Image Processing

ros2_usb_camera – image publishing via image_transport

aruco_detector – detect and process ArUco markers

rqt_image_view – GUI visualization for image topics

🐍 Python

Equivalent publisher/subscriber and service examples for those who love simplicity and flexibility.

📘 Additional Resources

This repo is a goldmine for learning references:

interfaces.md – best practices for interface packages

launch_files.md – clean and modular launch configurations

ros2_cli_cheat_sheet.pdf – all the CLI tools at your fingertips

vscode_cheat_sheet_linux.pdf – productivity shortcuts

🔗 Useful References

These guides inspired me to go beyond just running code:

ROS 2 naming conventions and design patterns

Plugin tutorials for modular software design

Parameter event handlers & lifecycle nodes

Efficient intra-process communication

ROS bags for data recording and playback

image_transport and message_filters for high-performance vision

🤝 Feedback & Contributions

If you have feedback, ideas, or improvements — open an issue or PR!
Collaboration is at the heart of robotics, and every contribution pushes the boundaries of what we can learn and build together.

🧡 My Vision

This isn’t just a collection of exercises — it’s a reflection of my journey in robotics.
Every launch file, every node, every simulation is a lesson in patience, precision, and problem-solving.

I believe the future belongs to those who can teach machines to perceive and move — and this repository is one of my first steps toward that vision.

🪪 License

Licensed under the Apache 2.0 License.
© 2024 Intelligent Systems Lab, University of Rome Tor Vergata.
Personal exploration and modifications by Keerthivarman.
