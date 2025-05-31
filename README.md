AstroHive is an AI-powered, distributed assistant system designed to manage and support autonomous space missions. It uses modular OPEA-compliant microservices to create intelligent agents that operate at three mission layers: rovers, satellites, and Earth-based control stations.

Each AI agent can:

Answer mission-specific questions (Q&A)

Summarize recent activity logs

Detect and alert on anomalies (like temperature spikes or signal loss)

These services work independently using FastAPI-based microservices with OpenAPI documentation, and are capable of running offline on edge devices—critical for space environments with limited connectivity.

The system features a unified dashboard interface (built with Streamlit or React) to monitor, interact with, and visualize mission data from all layers. Simulated telemetry data is used to replicate a real-world mission scenario, allowing you to demonstrate smart decision-making and real-time assistant collaboration—just like JARVIS, but for space.

