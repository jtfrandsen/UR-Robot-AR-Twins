# UR-Robot-AR-Twins

**Purpose:** To share ideas about using augmented reality to facilitate the integration of industrial robots.

**Summary:** A novel approach to integrating industrial robots in a production facility, using augmented reality digital twins. The AR digital twins depicted herein are intended to simplify the process of spatially planning a workstation, display real-time performance metrics for a robot in operation, as well as provide an intuitive user interface for creating basic robotic programs. This digital twin package is enabled by PTC's smart manufacturing software suite and was created specifically for Universal Robots' collaborative robot family.

### **Installation:**

You can try any of these AR experiences yourself by downloading the experience zip file (links are included below with the description of each AR experience) and using the "Import Project" option in Vuforia Studio to import the zip file. 

### **Table of Contents**

- [Project Background](#project-background)
- [Current Robot Integration Methods](#current-robot-integration-methods)
- [UR Robot Digital Twin Package](#ur-robot-digital-twin-package)
   - [Digital Twin for Visualizing](#digital-twin-for-visualizing)
   - [Digital Twin for Programming](#digital-twin-for-programming)
- [MSEC/NAMRC 2021 Conference Presentation](#MSEC/NAMRC-2021-conference-presentation)
- [PTC DX in Education Summit](#ptc-dx-ineducation-summit)

## Project Background

### Introduction

The incorporation of automation technology into a production facility is often an arduous and capital-intensive process that requires considerable specialized expertise. Many companies, especially small and medium-sized enterprises (SMEs), struggle to integrate robots and/or other automation systems into their facilities due to the overwhelming capital expenses and technical knowledge required during setup. Even after the automation systems have been assembled, robots still must be frequently re-programmed to accommodate the high-mix, low-volume production which is characteristic of most SMEs. Thus, the true cost of implementing robots becomes prohibitively high for these types of companies. A new and more intuitive approach to assist SMEs in their endeavor to automate their facilities is therefore necessary.

### What is a Digital Twin?

Industry 4.0 – often called the fourth industrial revolution – represents the marriage of physical production facilities with digital operational technologies. This new stage of industrial activity aims to provide digital solutions to address the problems the manufacturing sector faces. One of the most ubiquitous Industry 4.0 solutions is the digital twin.

Digital twins are defined as “a digital representation of an active, unique product or service or production system that is characterized by certain properties or conditions used in order to analyze, understand and improve the product, product service system, or production”. Digital twins come in many forms and can take any shape, from simple performance-monitoring dashboards, to data-rich simulation models, to immersive virtual-reality environments. The classification of digital twin used in any given situation should be determined based on the results and the level of immersion desired.

### Project Objective

This repository presents a comprehensive digital twin package, based in augmented-reality, that will facilitate SMEs in incorporating industrial robots into their production areas. The digital twins depicted hereafter can be used in existing factories with no extra costs and require little-to-no prior skill in robot programming. They will help SMEs confidently determine their needs with the robots before making the expensive purchase, as well as assist employees with creating robotic movement paths and monitoring real-time robot performance.

## UR Robot Digital Twin Package

The following digital twin classes are included in this package: (1) a dimensionally-accurate, moveable AR library of the UR robot family, (2) a data-rich, real-time 3D dashboard for the physical robot's operational data, and (3) a closed-loop, fully-connected programming interface that is capable of controlling the physical robot. These elements work together to enable inexperienced users to plan for, monitor, and interact with industrial robotics in a way that is much more intuitive than other, more traditional methods.


- [Digital Twin for Visualizing](#digital-twin-for-visualizing)
- [Digital Twin for Monitoring](#digital-twin-for-monitoring)
- [Digital Twin for Programming](#digital-twin-for-programming)

### Digital Twin for Visualizing

This digital twin allows the user to place a virtual robot into a physical space using augmented reality and serves to facilitate workstation planning. It includes a library of various robots and end effectors which render an accurate representation of the physical robot. ThingMarks are used for tracking becuase they provide a reference point to which the AR model is tethered. They also act as a size reference to ensure the AR models remain dimensionally precise, no matter where they are located. There are six sliders displayed on the user’s device, each of them corresponding to one of the AR robot’s six joints. These sliders give the user control over the AR cobot with 6 degrees of freedom and allow the user to move the AR robot into any pose. Additionally, a 3D rendering of the robot's entire working envelope has been included to give users a macro-level view of the robot's reach. Overall, this AR experience allows the user to easily visualize how a robot will fit into a workspace without having to purchase it first. It acts as a "try before you buy" experience for industrial robots.

The "Digital Twin for Visualizing" experience can be downloaded here.

### Digital Twin for Monitoring

