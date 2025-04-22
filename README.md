# Welcome to eclipse-autowrx

This GitHub organization contains artifacts developed by the **Eclipse AutoWRX Project**.

## Introduction to Eclipse AutoWRX

Eclipse AutoWRX is the open source implementation of [digital.auto](https://www.digital.auto), an industry-wide initiative enabling the automotive industry to establish a new, digital-first approach for the creation of next-generation customer experiences and data-driven mobility services.

Designed as an open ecosystem with a use-case-centric approach, digital.auto brings together automotive OEMs, suppliers, and partners to drive the transformation of the industry. The initiative builds on two key pillars of automotive technology development: the software-defined vehicle (SDV) and standardized vehicle APIs.

Eclipse AutoWRX aims to combine existing standards with appropriate methods and best practices to translate technology into business value. Co-initiators include Robert Bosch GmbH, Dassault Systèmes, and LeanIX. The initiative is hosted by the Ferdinand-Steinbeis-Institut (FSTI), a neutral, non-profit facilitator, and was launched in November 2022.

The ultimate goal of Eclipse AutoWRX is to support digital value creation for OEMs in close alignment with the development of the physical elements of the vehicle.

---

## Repository Overview and Functionality

### Core Repositories

| Repository       | Description |
|------------------|-------------|
| **[autowrx](https://github.com/eclipse-autowrx/autowrx)** | A TypeScript-based frontend application for visualizing vehicle data, simulation states, and interacting with SDV components. It serves as the main user interface for AutoWRX. |
| **[backend-core](https://github.com/eclipse-autowrx/backend-core)** | JavaScript/Node.js backend providing REST and WebSocket APIs. It acts as a middleware between the frontend and data providers (e.g., CAN, GPS, simulation). |
| **[sdv-runtime](https://github.com/eclipse-autowrx/sdv-runtime)** | A Python-based runtime environment designed to manage SDV logic, orchestrate services, and simulate vehicle signal flows using VSS (Vehicle Signal Specification). |
| **[dreamKIT](https://github.com/eclipse-autowrx/dreamKIT)** | C++ modules for embedded simulation, sensor emulation, and low-level integration with automotive ECUs or virtual ECUs. |

---

### Visualization and UI Components

| Repository       | Description |
|------------------|-------------|
| **[widget-3d-car-unity](https://github.com/eclipse-autowrx/widget-3d-car-unity)** | A Unity-based 3D car visualization widget using ShaderLab. It renders real-time vehicle state and sensor data in a 3D environment. |
| **[instance-overlay](https://github.com/eclipse-autowrx/instance-overlay)** | CSS and HTML-based UI overlay components for displaying contextual information (e.g., alerts, diagnostics) on top of the main visualization. |

---

### Learning and Documentation

| Repository       | Description |
|------------------|-------------|
| **[learning-journey](https://github.com/eclipse-autowrx/learning-journey)** | Educational resources, tutorials, and onboarding guides for developers and integrators using AutoWRX. |
| **[docs](https://github.com/eclipse-autowrx/docs)** | HTML-based documentation site for AutoWRX architecture, APIs, integration guides, and developer references. |

---

### Integration and Services

| Repository       | Description |
|------------------|-------------|
| **[epam-service-connector](https://github.com/eclipse-autowrx/epam-service-connector)** | A connector module for integrating third-party services and tools (e.g., EPAM platforms) with the AutoWRX backend. |
| **[analytics](https://github.com/eclipse-autowrx/analytics)** | Modules for collecting, processing, and visualizing telemetry and usage data from AutoWRX components. |

---

### Infrastructure and Configuration

| Repository       | Description |
|------------------|-------------|
| **[.github](https://github.com/eclipse-autowrx/.github)** | GitHub metadata, issue templates, contribution guidelines, and organization-wide configuration. |
| **[.eclipsefdn](https://github.com/eclipse-autowrx/.eclipsefdn)** | Repository for Eclipse Foundation-related configuration, project metadata, and compliance files. |

---

## License
 
This organization supports open collaboration and transparency. Licensing terms are defined individually per repository to best reflect the nature and intended use of each component.
 
Please refer to the `LICENSE` or `NOTICE` file in each repository for specific licensing information.