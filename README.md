KaneAI & Test Manager: Configuration Management System Design
This repository contains the front-end design and interactive prototype for a Configuration Management System, intended for integration with KaneAI and Test Manager platforms. The system aims to streamline the process of defining, allocating, and maintaining diverse test environments and application versions, enhancing efficiency and consistency in software testing.

Table of Contents
Features

Design Overview

Technologies Used

Setup and Usage

Wireframes Included

Future Enhancements

Features
The design incorporates the following key features based on the Product Requirements Document (PRD):

Centralized Configuration Management: A unified interface to manage all testing configurations.

Diverse Configuration Types: Support for Desktop, Real Device, and Virtual Device configurations.

Detailed Parameters: Define specific parameters for each configuration type (OS, Browser, Device Name, OS Version, Resolution, Application).

Regular Expression Support: Advanced filtering and selection of Real Devices using regular expressions for Manufacturer, Device Name, and OS Version.

Configuration Allocation: Simulate the allocation of configurations to Test Cases and Test Runs.

Application Versioning: A dedicated section for uploading, managing, and linking different versions of applications (APKs, IPAs).

Responsive Design: Optimized for various screen sizes, from mobile to desktop.

Interactive Prototype: Basic JavaScript functionality to simulate UI navigation and dynamic field changes.

Design Overview
The prototype is built as a single-page application (SPA) simulation, where different "views" are toggled using JavaScript. This provides a smooth user experience without full page reloads.

Key views include:

Main Configurations List View: Displays all created configurations with filtering and sorting options.

Add/Edit Configuration Screen: A dynamic form that adapts based on the selected configuration type (Desktop, Real Device, Virtual Device), including conditional fields for regex input and application selection.

Test Run Allocation View: A simplified representation of how configurations would be selected and assigned within a Test Manager's test run creation flow.

Application Management List View: Lists all managed applications with their latest versions.

Upload Application Screen: A form for uploading new application files and defining their metadata.

Manage Application Versions Modal: A modal dialog to view and manage specific versions of an application.

Technologies Used
HTML5: For structuring the web content.

Tailwind CSS: A utility-first CSS framework for rapid and responsive styling.

JavaScript (Vanilla JS): For interactive elements, view switching, and dynamic form logic.

SVG Icons: Used for a clean and scalable icon set.

Setup and Usage
To view and interact with this prototype:

Clone the repository:

git clone <repository-url>
cd <repository-name>

Open index.html: Simply open the index.html file in your web browser. No local server is required as all assets are loaded via CDN or are self-contained.

Wireframes Included
The design directly implements the following wireframes:

Configuration Management Interface:

Main Configurations List View

Add/Edit Configuration Screen (demonstrated with Real Device example)

Allocation to Test Run (simplified view within Test Manager context)

Application Management Interface:

Main Application List View

Upload Application Screen

Manage Application Versions (Modal/Screen)

Future Enhancements
Full backend integration for data persistence.

Advanced search and filtering capabilities.

User authentication and authorization.

Integration with actual KaneAI and Test Manager APIs for real-time data.

More sophisticated error handling and user feedback mechanisms.

Comprehensive unit and end-to-end testing.
