
# Energy-Efficient Ternary Approximate Multiplier with Error Compensation for Neural Networks

This repository contains the implementation and simulation framework for the paper:

> **Energy-Efficient Ternary Approximate Multiplier with Error Compensation for Neural Networks**  
> Accepted in IEEE ISVLSI 2026.

## Overview

This work proposes energy-efficient approximate ternary multiplier architectures with selective error compensation techniques for neural network applications.

Two error compensation circuits, **EC1** and **EC2**, are introduced to mitigate dominant truncation errors in approximate ternary multiplication while maintaining low hardware overhead.

The proposed architectures include:

- Approximate 3×3 ternary multipliers:
  - M1
  - M1+6
  - M1+24
  - M2
  - M2+60
  - M2+78

- Hierarchical 6×6 ternary multipliers:
  - S1 structures
  - S2 structures

## Key Results

- Up to **33% energy savings** for 3×3 multipliers
- Up to **40.73% energy reduction** for 6×6 multipliers
- Up to **93% MRED improvement**
- Only **1.18% PSNR degradation** in CNN-based image denoising

## Repository Structure

```text

HSPICE/            CNTFET simulation files
Figures/           Figures used in the paper
CNN_Application/   FFDNet integration
Results/           Simulation and evaluation results
Paper/             Published paper
