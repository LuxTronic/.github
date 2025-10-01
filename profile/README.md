# LuxTronic AI 🤖⚙️
Defect Detection for Aluminium Cans & Glass Bottles

We build high‑speed vision systems for mass‑pack manufacturing. Our specialty is detecting and tracking defects on aluminium cans and glass bottles, with real‑time integration to PLCs, SCADA, and MES.

## Core Competency
- Aluminium cans: body dents/dings, rim/neck deformation, flange damage, decoration/print/varnish defects, internal coating, ends & tabs (score integrity, rivet, curl)
- Glass bottles: finish/neck chips & cracks, base checks, sidewall cracks, inclusions (stones, blisters, cords), scuffs/scratches, contamination
- 360° inspection with area‑ or line‑scan cameras, strobed illumination, and deterministic rejection
- High throughput (hundreds–thousands per minute) with low false‑reject rates

## Defect Tracking & Analytics
- Per‑unit lineage by time, lane, turret/station, mold/cavity
- Heatmaps and SPC to localize sources and trends
- Image recall for root‑cause analysis and QA audits
- Events and quality states published to PLC/SCADA/MES

## Line Integration
- Triggers, encoders, photoeyes; sub‑ms timing and eject windows
- Air‑jet/actuator reject gates with deterministic delays
- Industrial I/O and PLC tags via OPC UA, MQTT, Modbus

## From Data to Deployment
1) Capture & Label: camera layout, lenses, strobes; cylindrical unwrap and 360° registration  
2) Train & Validate: classical CV + deep learning; class imbalance and rare‑defect handling  
3) Optimize: quantization and acceleration (TensorRT, OpenVINO, ONNX Runtime) to meet latency budgets  
4) Deploy & Integrate: containerized edge on Jetson/x86; I/O, reject gates, PLC/SCADA tags  
5) Monitor & Improve: drift detection, false‑reject budgets, golden‑sample validation, continuous learning

## Technology We Use
- Cameras: area‑scan and line‑scan; multi‑camera 360° rigs
- Computer Vision: OpenCV, YOLO family, segmentation/detection/pose
- ML/DL: PyTorch, TensorFlow, scikit‑learn; anomaly detection for rare events
- Edge & Acceleration: TensorRT, OpenVINO, ONNX Runtime, TensorFlow Lite
- Industrial Protocols: OPC UA, MQTT, Modbus for controls and telemetry

## Open Source Commitment
We sponsor and contribute to open source in packaging CV/ML. Learn about our
[Sponsorship Program](https://github.com/LuxTronic/.github#-open-source-sponsorship-program) for free AI coding agent compute and engineering support.

## Industries We Serve
Container manufacturing • Beverage • Food & Personal Care • Logistics

## Connect
🌐 https://www.luxtronic.ai  
💼 https://www.linkedin.com/company/luxtronicai/  
📧 contact@luxtronic.ai
