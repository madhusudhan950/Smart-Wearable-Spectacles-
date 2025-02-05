README.md documentation based on mini project:


AI-Powered Smart Spectacles

Overview

This project focuses on developing AI-powered smart spectacles equipped with a camera, microphone, open-ear speakers, and Bluetooth connectivity. The spectacles can capture images, transmit audio and video data to a smartphone, and provide real-time AI-powered assistance.

Features

✅ Camera Integration: Captures HD images and transmits them via Bluetooth.
✅ AI-Powered Assistance: Recognizes objects, reads text aloud, and provides real-time translations.
✅ Open-Ear Audio: Bone conduction speakers for hands-free interaction.
✅ Bluetooth Connectivity: Connects to a smartphone for seamless data transfer.
✅ Smart Notifications: Displays minimal text alerts and caller ID inside the lens.
✅ Voice Commands: Users can control functions via voice input.

Hardware Components

MCU: STM32H7B3I (480MHz Cortex-M7, hardware JPEG encoder)

Bluetooth SoC: Nordic nRF5340 (Bluetooth 5.2, LE Audio)

Camera Module: Sony IMX219 (8MP, MIPI-CSI)

Microphone: Knowles SPH0645LM4H (Digital MEMS)

Speakers: Bone conduction transducers

Battery: Li-Po 3.7V, 500mAh

Battery Management System: TI BQ24230 (PMIC for wearables)

Storage: Winbond W25Q128 (128MB NOR Flash)

Power Regulator: TI TPS62743 (Efficient low-power voltage regulation)

Antenna: Integrated PCB antenna


Software & Tools Used

Embedded C for firmware development

Keil4 & Visual Studio Code for coding

Proteus & KiCad for circuit design & simulation

GitHub for version control


How It Works

1. The user presses a button to capture an image and send audio.


2. The camera module captures an HD image, which is encoded (JPEG) before sending.


3. The Bluetooth module transmits the data to a smartphone.


4. The microphone captures real-time audio for AI-powered voice assistance.


5. The spectacles provide text-to-speech notifications and object recognition via AI.



Future Improvements

AI-based personal assistant for real-time responses.

Gesture-based controls for seamless interaction.

Improved battery efficiency for extended usage.

