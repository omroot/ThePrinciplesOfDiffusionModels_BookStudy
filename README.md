# The Principles of Diffusion Models - Book Study

Author: Oualid Missaoui

## Overview

This repository contains notes, code implementations, and experiments from studying the monograph **"The Principles of Diffusion Models"** by Chieh-Hsin Lai, Yang Song, Dongjun Kim, Yuki Mitsufuji, and Stefano Ermon.

**Paper:** https://arxiv.org/abs/2510.21890

## About the Monograph

This 470-page monograph presents a unified theoretical framework for diffusion models, demonstrating how diverse formulations arise from shared mathematical principles. The work explores three complementary perspectives:

1. **Variational View**: Learning to remove noise step by step (e.g., DDPM)
2. **Score-Based View**: Learning the gradient of the evolving data distribution (e.g., Score SDE)
3. **Flow-Based View**: Following a smooth path from noise to data (e.g., Flow Matching)

The key insight is that these historically distinct approaches are mathematically equivalent, all converging on learning a time-dependent vector field to reverse a fixed forward corruption process.

## Repository Structure

The `docs/` directory contains study notes and chapter summaries as I work through the monograph.

## Environment Setup

Setup instructions for running code implementations will be added as the study progresses.
