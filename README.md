<div align="center"><h1 style="font-family: courier;" align="center">619-J_Stepper</h1></div>
<div align="center"><img src="image/closed loop.26.jpg" width="70%"></div>
<div align="center"><b>An open source closed loop stepper driver.</b></div>

# 619-J_Stepper
**619-J_Stepper** is an open source micro-controller board used to drive a stepper motor in closed loop mode. The board is generally used on 3D printer steppers or CNC steppers to prevent losing steps. The project is inspired by [**Tropical labs: Mechaduino board**](https://tropical-labs.com/mechaduino/).

Here the **features** of the **619-J_Stepper**:

* **STM32F103C8T6 ARM 32-bit Cortex™-M3** is the CPU of the board. Higher frequency, higher speed and cost-effictive.  

* **Magnetic encoder to Allegro's A1333LLETR-T** Contactless 0° to 360° angle sensor IC ,12bit

* **USB programming** and **serial communication** (serial version)

* High speed printing without losing steps.

* Ported the compilation platform from arduino to PlatformIO —— Convenient for STM32 MCU compilation

* This project support build and upload by platformio, you can use Atom or Code editor (need install platformio) build it or upload firmware.

* Cosed loop motor feedback.

Here are the schematic and the board:

<div align="center"><img src="image/sch.JPG" width="70%"></div>


# Getting started



# License

The hardware is under the Creative Commons Attribution Share-Alike 4.0 License as much of the work is based on Mechaduino project by J. Church.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />Ce(tte) œuvre est mise à disposition selon les termes de la <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Licence Creative Commons Attribution - Pas d’Utilisation Commerciale - Partage dans les Mêmes Conditions 4.0 International</a>.

# Disclaimer

This hardware/software is provided "as is", and you use the hardware/software at your own risk. Under no circumstances shall any author be liable for direct, indirect, special, incidental, or consequential damages resulting from the use, misuse, or inability to use this hardware/software, even if the authors have been advised of the possibility of such damages.
