# IoTPulse
Portfolio Project for ALX Software Engineering Program.

<img alt="IoTPulse Project" src="https://github.com/elaifamouez/IoTPulse/blob/18f6587151857dc0a2b20e1e513618191380a1d3/IoTPulse.jpg" width="550" height="350">

 ## What is this app for ?
IoTPulse is a home automation controller written in C#, empowers users to seamlessly create and manage smart devices over the internet. It offers a user-friendly and efficient solution for automating your smart home through node-based visual programming, while also providing support for a wide array of devices and protocols.

**IoTPulse Features**

- <h4>Multiplatform : IoTPulse works on Windows or Linux. You can also run it on the Raspberry Pi. Automatic recognition of devices. As soon as you power on your hardware, it appears in the program, and you can control it.</h4>

<p align="center"><img alt="IoTPulse Multiplatform" src="https://github.com/elaifamouez/IoTPulse/blob/7d1a83e6e410314dcbff22ab56fa63d9db84b6da/IoTPulse%20multiplatform.png" width="300" height="100"></p>

- <h4>Dashboard : Create the control panels of your devices from UI elements such as buttons, sliders, input fields, etc. You will always have access to your control panels from the Internet using any device which has a browser.</h4>
<p align="center"><img alt="IoTPulse Dashboard" src="https://github.com/elaifamouez/IoTPulse/blob/71f044bcff05d76e47a41ef048a839c9551604a0/IoTPulse%20dashboard.jpg" width="700" height="500"></p>

- <h4>Node Editor : Configure your system in the visual Node Editor. Add various functional elements (nodes) in the scene and connect them together with "wires" as if you work with real devices.</h4>
<p align="center"><img alt="IoTPulse Node Editor" src="https://github.com/elaifamouez/IoTPulse/blob/e9f9dc702748e9d09d1df89315f978808fdf35e3/IoTPulse%20Visual%20Editor.jpg" width="700" height="500"></p>

- <h4>Scheduling : You can add a timer to the control panel that will control your device to do something on a schedule.</h4>

## How it works ?
**Network**
All devices (nodes) communicate wirelessly with computer through the gateway.

<p align="center"><img alt="IoTPulse Network" src="https://github.com/elaifamouez/IoTPulse/blob/372a09ac07dee1d4f96eabf23661c4e59bfa0cb0/IoTPulse%20network.png" width="300" height="300"></p>

The device does not have to be within range of the gateway, it can relay messages through other devices. Thus it allows communication over a long distance. The nodes can communicate with each other and interact.

IoTPulse works using MySensors protocol.

**Nodes**
<p align="center"><img alt="Node with temperature and humidity HT11/DHT22 sensor" src="https://github.com/elaifamouez/IoTPulse/blob/cdb9610d9f379806614317997efa67bd362224d6/node-IoTPulse%20sensor.png" width="300" height="300"></p>

All devices in the network are called Nodes. Nodes connect to the gateway wirelessly. You can connect to node some sensor or any device you would like to control. To build a node, you need an Arduino board and NRF24L01+ module. The node can run on batteries.

**Installation IoTPulse**

Windows
Make sure that you have installed .NET Framework.

Download or clone this repository

     git clone https://github.com/elaifamouez/IoTPulse.git
     cd IoTPulse
     ./localhost
     
To start the Web Controller, run the web.cmd file in the program folder.

Open the web interface in the browser (http://localhost:1312) and complete the First Run wizard.

### Authors

- [Kusare Chuwa Kusare](https://github.com/count58) 
- [elaifamouez](https://github.com/elaifamouez) 
