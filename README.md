
<p align="center">

 <img width=150px height=100px src="https://vectorlogoseek.com/wp-content/uploads/2020/03/osisoft-vector-logo.png" alt="Project logo">
  <img width=150px height=100px src="https://mma.prnewswire.com/media/476379/kepware_technologies_logo.jpg?p=facebook" alt="Project logo">
   <img width=150px height=100px src="https://cdn.xingosoftware.com/elektor/images/fetch/dpr_1/https%3A%2F%2Fwww.elektormagazine.com%2Fassets%2Fupload%2Fimages%2F42%2F20200612144414_Node-Red-official-logo.png" alt="Project logo">
</p>


[![Status](https://img.shields.io/badge/status-active-success.svg)]() 

<h3 align="left">Intorducing projects :</h3>
<p align= "left">This project aim to tutorial manage your operation data platform  both OPC server and a database (SQL) to transmit data in PI System .In addition it has another choses to use <b style="color:red">node-red-contrib-osisoft-web-api. </b>it possible for you to create your own data-flow application with write data and query data an existing PI System in a few hours.  </p>


---


## 📝 Table of Contents

- [Data Source](#Data_Source)
- [Setup PI System](#PIsetup)
- [Setup Node-Red](#NodeRedsetup)
- [Started Project](#startproject)
- [Monitoring Dashboard](#Dashboard)
- [Building Tool](#built_Tool)
- [Authors](#authors)
- [Acknowledgements](#Acknowledgement)

## 🧐 Data Source <a name = "Data_Source"></a>
This project I assumed you had to set up Kepware and SQL express was organized in your company So I will focus at data preparation.

<p align="center">
 <img  width=300px height=350px src="https://raw.githubusercontent.com/watthanai/Node-Red-PIAPI/master/images/kepware/Architecture-Kepware.PNG?token=GHSAT0AAAAAABTUUZXDPOL7S52PMAFOQLY2YTKHMLQ"><br></p>


<ul>

<li><b style="color:rgb(46, 204, 113)">Kepware : </b> <br>This Paragraph describes how to configure a PLC with Ethernet module and other OPC on the Local Ethernet network.</li>
 <b><br>Configure kepserver</b>
  <a target="_blank" href="https://raw.githubusercontent.com/watthanai/Node-Red-PIAPI/master/images/kepware/Connect%20PLC%20Siemens%20to%20Kepware/Slide1.PNG">
  </a>
  <ul><li><a href="https://github.com/watthanai/Node-Red-PIAPI/blob/master/Data%20Source/PLC-Simen.md">PLC Siemens to Kepware </a> </li>
  <li><a href="https://github.com/watthanai/Node-Red-PIAPI/blob/master/Data%20Source/PLC-Mitsubishi.md">PLC Mitsubishi to Kepware</a></li>
  <li><a href="https://github.com/watthanai/Node-Red-PIAPI/blob/master/Data%20Source/OPC-Kepware.md">OPC to Kepware</a></li>
  </ul>
  <b><br>Data Logger</b>
  <p>After you have done configure kepserver. May be you want to have an application that logs data from an OPC server to any ODBC-compliant database </p> 

  <p align="center">
 <img  width=400px height=350px src="https://www.kepware.com/getmedia/9c8c0143-202f-4937-a2b0-bbda1590215c/datalogger"><br></p>
 <b><br>Configure Dataloger</b> 
   <ul><li><a href="https://github.com/watthanai/Node-Red-PIAPI/blob/master/Data%20Source/SQL/Port-SQL.md">Open port SQL Workstaion </a> </li>
  <li><a href="https://github.com/watthanai/Node-Red-PIAPI/blob/master/Data%20Source/SQL/DataLogger.md">OPC Data Logger</a></li>
  </ul><br>


## 🏁 SETUP PI SYSTEM <a name = "PIsetup"></a>

The PI system enables digital transformation through trusted, high-quality operations data. Collect, enhance, and deliver data in real time in  any location. [How the PI System works ? ](#PIsystem) 


<p align="center">
 <img  width=300px height=200px src="https://raw.githubusercontent.com/watthanai/Node-Red-PIAPI/master/images/PI_System/PI%20system%203%20layer.png"><br></p>
 <ul>
<li><b style="color:rgb(46, 204, 113)">Collect</b>
  <pre> o PI Interface Configuration Utility <img  width=30px height=25px src="https://raw.githubusercontent.com/watthanai/Node-Red-PIAPI/master/images/PI_System/pi%20interface.png"></pre>
Collect real-time data from hundreds of assets—including legacy, proprietary, remote, mobile, and IIoT devices. The PI System connects you to your data, no matter the location or format.</li>
<ul><li><a href="">Loading OPC & SQL Driver</a></li></ul><br>


</ul>


<ul>
<li><b style="color:rgb(46, 204, 113)">Manage Enhance </b>
<pre> o PI System Management Tools <img  width=30px height=25px src="https://raw.githubusercontent.com/watthanai/Node-Red-PIAPI/master/images/PI_System/pi%20system.png"> <br> o PI system Explorer         <img  width=30px height=25px src="https://raw.githubusercontent.com/watthanai/Node-Red-PIAPI/master/images/PI_System/pi%20explorer.png"></pre>Get immediate access to high-fidelity historical,real-time and predictive data to keep critical operations running and business insights coming </li>
</ul>

<ul>
<li><b style="color:rgb(46, 204, 113)">Visualize and act</b>
  <pre> o PI Vision  <img  width=30px height=25px src="https://raw.githubusercontent.com/watthanai/Node-Red-PIAPI/master/images/PI_System/pi%20vision.png"></pre>
Easily create your own custom reports and views, so you can monitor processes and troubleshoot on the spot. Quickly drill down from high-level summaries to see issues in an individual asset. Compare downtime events and batch datasets to identify patterns and replicate best practices.</li>
</ul><br>


## 🎈 Node-Red<a name="NodeRedsetup"></a>

Add notes about how to use the system.

## 🚀 Started Project<a name = "startproject"></a>

### Prerequisites 
Before we will start project you have to know & need Tools that appered paragrph <b> SET UP PI SYSTEM</b>
<ul>
<li>PI Interface Configuration Utility</li>
<li>PI System Management Tools</li>
<li>PI system Explorer</li>
<li>OSIsoft Web API server that is connected to your PI Server </li>
</ul>

### Implement PI system
PI System Managemnet Tool
<ul>

<li>
<a href="">OPC to PI Server</a></li></ul>
<img  width=500px height=200px src="https://raw.githubusercontent.com/watthanai/Node-Red-PIAPI/master/images/PI_System/OPC%20to%20PI.png">
<ul>
<li><a href="">SQL to PI Server</a></li></ul>
<br>
PI system Explorer<br>
<p align="center">
 <img  width=300px height=200px src="https://raw.githubusercontent.com/watthanai/Node-Red-PIAPI/master/images/PI_System/PI%20system%203%20layer.png"><br></p>
After you create PI tag in PI Server .it will generate PI web api .you can follow data depend on path element.




## ⛏️ Built Tool <a name = "built_Tool"></a>

- [MongoDB](https://www.mongodb.com/) - Database
- [Express](https://expressjs.com/) - Server Framework
- [VueJs](https://vuejs.org/) - Web Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ Authors <a name = "authors"></a>

- [@Watthani](https://github.com/watthanai) - Idea & Initial work


## 🎉 Acknowledgements <a name = "acknowledgement"></a>
- References
