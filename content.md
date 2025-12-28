WIREFRAME DESIGN REPORT
Product: Car Infotainment System UI (Software-Defined Vehicle)
1. Introduction
In the UX/UI design process, a wireframe serves as a structural blueprint that defines the layout, information hierarchy, and interaction flow of a digital product before visual styling is applied.
For in-vehicle infotainment systems, wireframing plays a particularly critical role because the interface is used in a safety-critical environment, where users must interact with the system while maintaining full attention on driving. As a result, the wireframe must prioritize clarity, simplicity, minimal cognitive load, and at-a-glance readability.
This wireframe is designed for a car infotainment system acting as a central control center, enabling users to:
Monitor vehicle status


Control in-car devices


Receive driving guidance


Manage automated features


Connect and interact with mobile devices


The wireframe establishes a foundation for safe interaction across different driving contexts and user roles, including drivers, passengers, and maintenance technicians
2. Objectives of the Wireframe
The objectives of this wireframe are to:
Define the overall screen structure of the infotainment system


Establish a clear and consistent information architecture for all major system functions


Support safe, efficient, and distraction-minimized interaction during driving


Provide a solid foundation for:


Usability testing


Expert evaluation based on ISO 9241 usability principles


Technical feasibility assessment by developers
3. Design Principles Applied
The wireframe is developed based on the following key UX principles:
Safety First:
 Visual and cognitive distractions are minimized to support safe driving behavior.


At-a-Glance Readability:
 Key information must be understandable within 1–2 seconds of visual attention.


Consistency:
 Similar layouts, interaction patterns, and iconography are used across all screens.


Large Touch Targets:
 Interactive elements are sized appropriately for in-car touch interaction under vibration and motion.


Context Awareness:
 The interface adapts to different vehicle states such as Driving, Parked, and Automated modes.
4. Overall Wireframe Layout
The infotainment system is designed for a wide landscape in-car display and is divided into four persistent regions to ensure clarity and predictability.
4.1 Status Bar
Displays system time, connectivity status, and vehicle alerts


Indicates the current driving state (Driving / Parked / Automated Mode)


4.2 Global Navigation
A persistent navigation menu providing access to the five main system modules:
Monitoring


Device Controls


Driving Guidance


Automated Features


Mobile Connect


This structure enables users to quickly switch between major functions without navigating deep menu hierarchies.
4.3 Main Content Area
The central area of the screen where contextual content is displayed based on the currently selected module.
4.4 Quick Action Controls
Provides fast access to frequently used actions:
Home


Voice control


Volume adjustment


Back navigation


These controls are always accessible to reduce interaction time and distraction.
5. Information Architecture
5.1 Sitemap
Home / Overview
Monitoring


Device Controls


Driving Guidance


Automated Features


Mobile Connect


Settings (Secondary)


The Home / Overview screen functions as the central dashboard, allowing users to quickly understand the current system state and access core functions.
6. Context-Based Interaction States
To ensure safety and usability, the wireframe supports different interaction behaviors depending on vehicle state:
Driving Mode


Only high-level information is shown


Deep configuration settings (language, profiles, OTA updates) are restricted


Voice commands and physical controls are prioritized over touch


Parked Mode


Full access to all system settings and configuration features


Device pairing, personalization, and system setup are enabled


Automated Mode


Monitoring and system transparency are emphasized


Emergency override actions remain accessible at all times
7. Wireframe Screens Description

7.1 Home / Overview Screen
Purpose
 To provide an at-a-glance overview of vehicle status and quick access to all major functions.
Main Components
Vehicle status summary (fuel level, driving range, outside temperature, tire pressure)


Active alerts and notifications


Quick device control shortcuts (air conditioning, lights)


Navigation preview


Mobile connection status


UX Rationale
 This dashboard-style layout allows drivers to understand system status quickly without navigating into deeper menus.

7.2 Monitoring Screen
Purpose
 To allow users to monitor real-time vehicle information clearly and efficiently.
Main Components
Tire pressure indicators for each wheel


Fuel consumption and remaining range


Outside temperature


Vehicle health alerts


Interaction
Tapping a summary card opens a detailed view


Critical warnings are visually highlighted

7.3 Device Controls Screen
Purpose
 To enable direct control of in-car devices with minimal interaction effort.
Subsections
Climate Control: temperature, fan speed, defrost


Lights: headlights and ambient lighting


Seats: heating, ventilation, seat position presets


UX Rationale
 Controls are grouped by function and presented with large, clearly labeled elements to support safe use while driving.

7.4 Driving Guidance Screen
Purpose
 To assist users during driving through navigation and real-time guidance.
Main Components
Navigation map (primary focus)


Turn-by-turn directions


Lane assist indicators


Speed limit and hazard warnings

UX Rationale
 Visual cues are prioritized over text to reduce cognitive load and support fast decision-making.
7.5 Automated Features Screen
Purpose
 To manage automated driving features while maintaining transparency and user control.
Main Components
Automated parking


Collision avoidance status


Self-driving mode indicators


Emergency override controls
Automated Parking Flow
Select parking mode


System scans for available spaces


User confirms selected space


Parking execution with progress feedback


Emergency stop available at all times

UX Rationale
 The UI focuses on monitoring and user override, ensuring users can intervene quickly when needed.
7.6 Mobile Connect Screen
Purpose
 To allow users to connect mobile devices and manage communication and media safely.
Main Components
Connection status (Bluetooth / cable)


Device pairing flow


Media playback controls


Notification previews


Android Auto / Apple CarPlay access

UX Rationale
 The interface is simplified to limit interaction complexity and supports full-screen integration for mirrored systems.
7.7 Settings & Service Mode (Secondary)
Purpose
 To manage system preferences and maintenance-related functions.
Subsections
Display and sound settings


Connectivity preferences


Service Mode (Restricted):


Diagnostic logs


ECU and sensor status


OTA update progress


Access limited to authorized technicians


Certain settings are restricted while the vehicle is in motion to maintain safety.

8. User Task Flow Support
The wireframe supports common user tasks, including:
Adjusting air conditioning


Checking tire pressure


Starting navigation


Using automated parking


Connecting a mobile phone


Detailed task flows and HTA descriptions are defined in the User Task Analysis document and will be used in later usability testing and evaluation phases.

