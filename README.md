# Microgripper-Force-Prediction
An AI-powered simulation of a microgripper, designed to safely handle fragile electronics like optical fibers without crushing them.

## What is this project?
This repository contains the design and machine learning code for a tiny, two-armed robotic gripper. This "microgripper" is designed to pick up and assemble microscopic, highly delicate parts—like fiber optic cables and smartphone camera lenses—without damaging them. 

## How does it work?
Traditionally, figuring out exactly how hard a robotic arm needs to squeeze a microscopic object requires slow and complex math simulations that can take up to 15 minutes. 

To solve this, we gave the gripper an "AI Brain." We trained a Machine Learning model (a Random Forest) on thousands of simulation examples. Now, instead of doing the slow math, the AI can instantly predict the exact right grip force in less than a millisecond. 

## Key Features
* **Lightning-Fast Reflexes:** Because the AI predicts the force in sub-milliseconds, the robotic arm can adjust its grip in real-time, just like human reflexes. 
* **Safe, Balanced Pinch:** The two-arm design provides a perfectly symmetrical squeeze. This stops the tiny objects from sliding out of the gripper, which is a big problem with older, one-armed designs.
* **Smart Engineering:** The AI helped us figure out that making the robotic arms slightly thicker and wider (rather than longer) is the most effective way to increase its grip strength.
* **Ready for the Real World:** The AI model is designed to handle "noise" (slight sensor errors that happen in the real world) so it can eventually be used in a real factory to build electronics faster and cheaper.
