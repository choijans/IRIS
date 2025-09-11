
# IRIS – Integrated Remote Infrastructure System

## Overview

**IRIS (Integrated Remote Infrastructure System)** is a comprehensive campus IT infrastructure and lab management platform developed as a Capstone Project. The system is designed to enhance visibility, control, and operational efficiency for IT administrators and teaching staff managing laboratory resources and classroom computing environments.

## Table of Contents

- [Project Overview](#project-overview)
- [Group Members](#group-members)
- [Core Modules & Functionality](#core-modules--functionality)
  - [1. Hardware and Network Monitoring](#1-hardware-and-network-monitoring)
  - [2. Laboratory Monitoring and Management](#2-laboratory-monitoring-and-management)
  - [3. Software Management](#3-software-management)
  - [4. Policy Enforcement](#4-policy-enforcement)
  - [5. Role-Based Access Control](#5-role-based-access-control)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

---

## Project Overview

IRIS is developed to address the increasing demand for centralized, real-time, and intelligent monitoring of computing environments within academic institutions. It combines device health monitoring, network traffic analysis, user behavior tracking, software inventory management, and role-based access into a single intuitive interface.

---

## Group Members

- Josh Edward Lui  
- Jansen Kai Xuan Choi  
- Jeskha Samantha Derama  
- Jose Rafael Achilles Delgado  
- Marie Louise Ty  
- Keanu Riel Ensomo

---

## Core Modules & Functionality

### 1. Hardware and Network Monitoring

Provides real-time insights into system performance and network activity.

| Code | Name                    | Description |
|------|-------------------------|-------------|
| 1.1  | System Resource Monitoring | Tracks CPU, GPU, RAM, disk usage, and temperature of lab PCs. |
| 1.2  | Bandwidth Usage Tracker   | Monitors bandwidth per device to detect congestion or heavy use. |
| 1.3  | Network Behavior Alerts   | Alerts for abnormal activity like CPU spikes or link losses. |
| 1.4  | Device Status Dashboard   | Displays real-time operational status of all machines. |

---

### 2. Laboratory Monitoring and Management

Enables classroom supervision and remote administrative actions.

| Code | Name                    | Description |
|------|-------------------------|-------------|
| 2.1  | Live Screen View         | Real-time screen viewing of student PCs in a tiled interface. |
| 2.2  | Remote Control Actions   | Lock, restart, or shut down lab PCs remotely (manual only). |
| 2.3  | Input and Activity Logging | Logs idle time, app switching, and input patterns. |
| 2.4  | Room-Based Interface     | Lab-specific dashboards for segmented monitoring and actions. |

---

### 3. Software Management

Centralizes software deployment, removal, and compliance tracking.

| Code | Name                    | Description |
|------|-------------------------|-------------|
| 3.1  | Remote Software Installation | Deploy new applications across selected machines. |
| 3.2  | App Uninstallation       | Remove outdated or unauthorized software. |
| 3.3  | Software Inventory Viewer | View and audit installed apps per device. |

---

### 4. Policy Enforcement

Automates enforcement of IT policies and system restrictions.

| Code | Name                    | Description |
|------|-------------------------|-------------|
| 4.1  | Policy Enforcement Scripts | Apply rules like restricted access or auto-shutdowns. |
| 4.2  | UI/Usage Restrictions    | Prevent UI changes like wallpapers or system settings. |
| 4.3  | Scheduled Actions        | Automate session resets and shutdowns via scheduler. |

---

### 5. Role-Based Access Control

Ensures appropriate access based on user roles.

| Code | Name                    | Description |
|------|-------------------------|-------------|
| 5.1  | User Role Definitions    | Define and assign roles such as Administrator, IT Staff, and Faculty to restrict access by need. |

---

## Technologies Used

- Programming Languages: *(e.g., Python, JavaScript)*
- Frontend: *(e.g., React, Vue, HTML/CSS)*
- Backend: *(e.g., Node.js, Flask, Django)*
- Database: *(e.g., MySQL, PostgreSQL, MongoDB)*
- Real-Time Communication: *(e.g., WebSockets, MQTT)*
- Others: *(e.g., Docker, Git, REST APIs)*

> **Note**: Specific stack details can be added based on your actual implementation.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/IRIS.git
   cd IRIS

   ```
2. Install dependencies:

   ```bash
   npm install     # or pip install -r requirements.txt for Python-based projects
   ```

3. Configure environment variables and database connections.

4. Run the system:

   ```bash
   npm start       # or python app.py / flask run
   ```

---

## Usage

* Access the dashboard via browser at `http://localhost:PORT`
* Login using appropriate credentials (e.g., Admin, IT, Faculty)
* Navigate to modules to monitor and manage labs

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
