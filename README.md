<p align="center">
  <!---logo/logo.png -->
  <img src="logo/logo.png" alt="RavenOS Logo" width="160">
</p>

```text
#  _______  _______           _______  _        _______  _______ 
# (  ____ )(  ___  )|\     /|(  ____ \( (    /|(  ___  )(  ____ \
# | (    )|| (   ) || )   ( || (    \/|  \  ( || (   ) || (    \/
# | (____)|| (___) || |   | || (__    |   \ | || |   | || (_____ 
# |     __)|  ___  |( (   ) )|  __)   | (\ \) || |   | |(_____  )
# | (\ (   | (   ) | \ \_/ / | (      | | \   || |   | |      ) |
# | ) \ \__| )   ( |  \   /  | (____/\| )  \  || (___) |/\____) |
# |/   \__/|/     \|   \_/   (_______/|/    )_)(_______)\_______)
```

# RavenOS

**RavenOS**, or simply **ROS**, is an Arch-based live system made for cybersecurity labs, experiments, and temporary testing environments.

This project is still being built. I started working on it around 6–7 months ago, and it is not ready for public release yet.

The idea is simple: a live system that gives you a prepared environment without turning your main machine into a permanent testing box.

> **Status:** Work in progress  
> **Release:** Coming soon  
> **Installable:** No — RavenOS is planned as a live-only system for now.

---

## Preview ROS

```md
(screenshots-ros/01.png)
(screenshots-ros/02.png)
(screenshots-ros/03.png)
(screenshots-ros/04.png)
(screenshots-ros/05.png)
(screenshots-ros/06.png)
(screenshots-ros/07.png)
(screenshots-ros/08.png)
(screenshots-ros/09.png)
(screenshots-ros/10.png)
(screenshots-ros/11.png)
(screenshots-ros/12.png)
(screenshots-ros/13.png)
(screenshots-ros/14.png)
(screenshots-ros/15.png)
(screenshots-ros/16.png)
(screenshots-ros/17.png)
```

---

## What is RavenOS?

RavenOS is built using **archiso** and a set of custom scripts.

These scripts are used to build and customize the system from the ground up: packages, configs, desktop setup, tools, and the final ISO structure.

For now, the system is planned to run as a **live-only ISO**. That means it is not meant to be installed on a disk like a normal daily-use Linux distribution.

One of the main goals is to keep the environment temporary. After a reboot or shutdown, the system should not leave normal session traces behind on the machine. This makes it useful for short testing sessions, labs, and clean cybersecurity experiments.

---

## What RavenOS will include

RavenOS will focus on cybersecurity-related tools and workflows.

The first versions will mainly use official Arch Linux packages and official Arch tools. Later, I plan to add a wider set of tools from different sources, along with my own tools when they are ready.

The system is expected to be large because of the number and size of the included tools.

Current expected ISO size:

```text
RavenOS: around 7–10 GB
```

This may change later. I might also make a smaller version for people who only want to try the system first.

---

## Desktop

RavenOS will come with **GNOME** as the desktop environment, with some custom changes to make it fit the system better.

The goal is not to overcomplicate the desktop. I want it to feel clean, usable, and ready for work.

---

# ROS-PY

**ROS-PY** is the second project that came from RavenOS.

It uses the same general shape, structure, and behavior as RavenOS, but with a different focus.

Instead of shipping with a large cybersecurity toolkit, ROS-PY is more focused on Python scripting and Python-based experiments.

The plan is to include a very large set of official Arch Python packages, around **3,000 Python packages**, so the system can be used as a ready Python scripting environment.

Current expected ISO size:

```text
ROS-PY: around 9–10 GB
```

ROS-PY will also use **GNOME** with similar customizations.

## Preview ROS-PY
```md
(screenshots-ros-py/01.png)
(screenshots-ros-py/02.png)
(screenshots-ros-py/03.png)
(screenshots-ros-py/04.png)
(screenshots-ros-py/05.png)
(screenshots-ros-py/06.png)
(screenshots-ros-py/07.png)
```

---

## Project goals

- Build the systems using `archiso`
- Keep the systems live-only at the beginning
- Prepare a clean environment for cybersecurity experiments
- Avoid keeping normal session traces after reboot or shutdown
- Use official Arch packages as the base
- Add more tools and custom tools over time
- Keep the desktop simple and usable
- Provide two editions with different focuses:
  - **RavenOS / ROS** for cybersecurity tools and labs
  - **ROS-PY** for Python scripting and Python-heavy workflows

---

## Not ready yet

RavenOS and ROS-PY are not ready to be used as finished systems.

Right now, this repository is mainly here to show the idea, progress, screenshots, and general direction of the projects.

More files, scripts, screenshots, and release details will be added later.

---

## Disclaimer

RavenOS and ROS-PY are made for learning, research, labs, and authorized cybersecurity testing only.

Do not use these systems or any included tools against devices, networks, or services without permission.

---

## License

This project is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You are free to share and adapt the content, even for commercial purposes, as long as proper credit is given.

See the [LICENSE](LICENSE) file for more details.
