# Transformer Models in Autonomous Driving Applications

**Research Review · Technische Hochschule Ingolstadt · 2026**  
**Focus:** Transformers · Autonomous Driving · Perception · Motion Prediction · Real-Time Systems

This project is a literature review on the development and application of **Transformer architectures in autonomous driving**.

The review focuses on two major parts of the autonomous driving stack:

- **Perception** – understanding the surrounding environment
- **Prediction** – forecasting the future motion of road users

The work investigates how Transformer-based architectures improve global scene understanding and modeling of spatial and temporal relationships, while also examining their limitations regarding computational cost, latency and deployment on automotive hardware.

---

## Scope

The review covers the development of Transformer-based approaches for autonomous driving, including:

### Perception

- DETR
- PETR
- BEVFormer
- PETRv2
- BEVFormer v2
- StreamPETR
- BEVFusion

The analysis follows the architectural progression from 2D object detection towards camera-based 3D perception and BEV representations.
### Motion Prediction

- MultiPath
- MultiPath++
- Wayformer
- MTR / MTR++
- MotionLM

The review examines how Transformer-based architectures improve the modeling of temporal dependencies, multimodal trajectories and interactions between multiple road users.

---

## Key Findings

The review identifies a clear trend towards Transformer-based architectures in both perception and prediction.

Transformers provide strong capabilities for:

- global scene understanding
- spatial and temporal relationships
- multimodal information fusion
- complex multi-agent interactions

However, these advantages come with significant computational costs.

A central finding of the review is the **trade-off between model performance and computational efficiency**. Modern Transformer architectures can achieve strong benchmark results, but their computational requirements and inference latency remain major obstacles for real-time deployment in autonomous vehicles.

For example, the reviewed perception models show that increasing spatial and temporal modeling capabilities can come at the cost of inference speed and memory requirements. 

---

## Research Perspective

One of the main conclusions of the review is that Transformer architectures have established a strong foundation for future autonomous driving systems, but **real-world deployment remains challenging**.

Key open challenges include:

- real-time inference
- computational efficiency
- memory and hardware requirements
- interpretability
- limited and imbalanced training data
- rare and safety-critical scenarios

Further optimization of Transformer architectures and their underlying hardware is therefore essential for practical deployment.

---

## Technologies & Topics

**Transformers · Attention Mechanisms · Computer Vision · 3D Object Detection · BEV · Motion Prediction · Sensor Fusion · Autonomous Driving · Real-Time AI**

---

## Paper

**Transformer Models in Autonomous Driving Applications**  
*Linus Jürgens*

The complete review paper is available in this repository:

[`reviewpaper.pdf`](./reviewpaper.pdf)
