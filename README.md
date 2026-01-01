


# IconClay Studio


**[Launch IconClay Studio](https://dovvnloading.github.io/Icon-Clay-Studio/)**


![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Status](https://img.shields.io/badge/Status-Proprietary_Utility-red?style=for-the-badge)

<img width="100%" alt="IconClay Studio Interface" src="https://github.com/user-attachments/assets/1b2aba03-7d76-4929-851b-1ea310a9868c" />

## Overview

IconClay Studio is a specialized vector-based design environment engineered for the creation of high-fidelity neumorphic and claymorphic digital assets. Unlike traditional vector tools that treat shadows as simple offsets, IconClay utilizes a custom rendering engine that decouples internal surface volume (lighting) from external atmospheric casting (shadows). This allows for the generation of assets with tangible depth, distinct bevels, and physically simulated materials.

This application is provided as a hosted utility tool for designers and developers requiring specific aesthetic outputs. It is not an open-source framework.

## Core Capabilities

### The Clay Engine
The rendering pipeline generates SVG filters dynamically based on physical parameters rather than CSS presets.
*   **Decoupled Shading:** Control internal convexity/concavity independent of global lighting sources.
*   **Material Simulation:** Adjust surface blur (softness), noise (texture grain), and specularity (gloss) to simulate materials ranging from matte plastic to ceramic.
*   **Dual-Pass Lighting:** Renders separate key lights and fill shadows to create volumetric objects.

### Vector Operations
*   **Non-Destructive Editing:** All shape properties, including corner radii and boolean states, remain editable post-creation.
*   **Boolean Unions:** Merge multiple primitives into single continuous clay surfaces.
*   **Masking:** Use shapes as clipping masks for complex compositions.
*   **Smart Guides:** Geometry-aware snapping for precision alignment.

### Production Pipeline
*   **Project Persistence:** Save and load full workspace states via custom `.clay` JSON schemas.
*   **Export formats:** 
    *   **PNG:** High-resolution raster export with transparency preservation.
    *   **ICO:** Native Windows icon format with embedded PNG compression.
    *   **SVG:** Clean vector output for web implementation.

## Usage

This application is intended to be used via the official deployment. It functions as a client-side Single Page Application (SPA) where all processing occurs within the user's browser memory. No data is transmitted to external servers during the design process.


## License & Proprietary Notice

**This repository contains proprietary software.**

While the source code is viewable for transparency and hosting purposes, it is **not** Open Source. It is not licensed under standard permissive licenses (such as MIT, Apache, or GPL). The developer retains all copyright and intellectual property rights to the interface designs, "Clay Engine" logic, and underlying architecture.

**Developer Requests and Usage Guidelines:**

*   **Intended Use:** This application is provided as a finished utility tool. Users are encouraged to utilize the hosted application to create design assets.
*   **Source Code:** Please refrain from forking, mirroring, modifying, or repackaging this codebase for distribution. The source code is provided "Source Available" rather than "Free and Open Source Software (FOSS)."
*   **Commercial Restrictions:** Redistribution or sale of this application, in whole or in part, is contrary to the developer's intent.

**Disclaimer:**
This software is provided "AS IS", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software.
