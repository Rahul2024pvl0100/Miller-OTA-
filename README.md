Design and Implementation of Ultra-Low Power Miller OTA (Virtuoso, GPDK 90 nm)

Jul 2025 – Aug 2025

This project focuses on designing a highly energy-efficient Miller Operational Transconductance Amplifier (OTA) suitable for low-voltage and low-power analog systems. 
The goal was to create an amplifier that could operate reliably at a very small supply voltage of 500 mV, while still offering good gain, stability, and linearity. 
This makes the design suitable for biomedical and portable applications where power availability is very limited.

To achieve operation at such low voltage levels, the OTA uses a bulk-driven differential input pair, which improves the input dynamic range even when the supply voltage is small. 
Additional DC level shifters were included to maintain proper biasing and enhance linear performance across the full rail-to-rail input and output range.
The design was implemented and tested in Cadence Virtuoso using the GPDK 90 nm CMOS technology, ensuring compatibility with modern integrated circuit fabrication processes.

During simulation, the OTA demonstrated strong electrical performance. It achieved a closed-loop gain of 40 dB, which is suitable for many low-frequency sensing and amplification tasks. 
The unity-gain frequency of 127.4 kHz indicates that the circuit can handle moderate signal bandwidths while maintaining stability. 
A phase margin of 70.47° confirms that the amplifier operates without oscillations even under feedback.

The output also showed a linear signal swing from 0.04 V to 0.486 V, allowing the OTA to utilize most of the available supply voltage, which is important in low-power circuits.
Despite these performance levels, the OTA consumes only 2.31 µW of static power, proving its suitability for long-term, battery-powered, or energy-harvested systems.

Overall, this project demonstrates a practical and efficient approach to designing ultra-low power analog circuits for next-generation low-voltage applications.
