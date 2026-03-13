# VR Knee Surgery Simulation

A immersive VR surgical training application built with Unity and 
XR Interaction Toolkit 3.x, integrated into a hospital environment (HOPS).

## Features
- Interactive knee surgery with progressive incision system (91-stage mesh morphing)
- Grabbable surgical tools — scalpel, retractor, forceps
- Step-by-step surgery instruction system with VR UI canvas
- Patient model with draped surgical setup
- IK-based hand/arm tracking for realistic tool interaction
- Surgery state machine with event-driven progression
- Built for Meta Quest / OpenXR compatible headsets

## Tech Stack
- Unity 2022.x / 2023.x
- XR Interaction Toolkit 3.3.1
- Animation Rigging 1.4.1
- Universal Render Pipeline (URP)
- OpenXR / Meta XR

## Scene Structure
- EnvironmentScene — HOPS hospital environment with patient bed
- SurgeryManager — controls surgery flow and validation
- DrappedPatient + Leg_SkinIncision_Final — patient and knee model
- Surgical tools with XR grab interactions

## Status
🚧 In Development — Surgery integration in progress
