# 16-QAM-Communication-System-Simulation
This project presents a MATLAB simulation of a 16-QAM (Quadrature Amplitude Modulation) digital communication system. The primary goal is to analyze the system's performance by calculating the Bit Error Rate (BER) when the signal is transmitted through a channel affected by noise and multipath fading.

📋 System OverviewThe simulation models a realistic communication pipeline to study how channel impairments affect data accuracy. The simulation process includes:
- Signal Generation: A random binary data stream of 20,000 bits is created.
- 16-QAM Modulation: The binary data is mapped to 16-QAM symbols, where each symbol represents 4 bits.
- Pulse Shaping: A Raised Cosine Filter is used to shape the signal pulses, which helps reduce inter-symbol interference (ISI) and limits the signal's bandwidth.
- Channel Simulation: The modulated signal is passed through a channel that introduces Additive White Gaussian Noise (AWGN) and multipath fading effects.
- Receiver: At the receiver end, a matched filter is used for signal demodulation to recover the original bits.

📊 Performance AnalysisSystem performance is evaluated using several methods:
- Bit Error Rate (BER): The core metric of the analysis, BER is calculated by comparing the transmitted bits with the received bits after accounting for processing delays.
- Spectrum Analysis: A spectrum analyzer is used to visualize the signal's frequency spectrum before and after it passes through the channel, showing the distortion caused by noise and fading.
- Constellation Diagram: The project also involves visualizing the constellation plot to observe how noise and other channel effects displace the received symbols from their ideal positions.
This model serves as a practical tool for understanding the fundamental challenges in digital communication systems.

🧑‍💻 Project Authors- Tej Prakash Jadhav
- Abhijit Kiran Kadam
- Omkar Shankar Kadam
- Vansh Vijay Katkar
Guided By: Suchitra Patil
