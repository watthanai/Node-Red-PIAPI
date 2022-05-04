
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
- [Setup PI Interface](#PIsetup)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 Data Source <a name = "Data_Source"></a>
This project I assumed you had to set up Kepware and SQL express was organized in your company So I will focus at data preparation.

<p align="center">
 <img  width=300px height=350px src="https://raw.githubusercontent.com/watthanai/Node-Red-PIAPI/master/images/kepware/Architecture-Kepware.PNG?token=GHSAT0AAAAAABTUUZXDPOL7S52PMAFOQLY2YTKHMLQ"><br></p>


<ul>

<li><b style="color:rgb(46, 204, 113)">Kepware : </b> <br>This Paragraph describes how to configure a PLC with Ethernet module and other OPC on the Local Ethernet network.</li>
 <b><br>Configure kepserver</b>
  <a target="_blank" href="https://raw.githubusercontent.com/watthanai/Node-Red-PIAPI/master/images/kepware/Connect%20PLC%20Siemens%20to%20Kepware/Slide1.PNG">
  </a>
  <ul><li><a href="https://github.com/watthanai/Node-Red-PIAPI/blob/master/PLC-Simen.md">PLC Siemens to Kepware </a> </li>
  <li><a href="https://github.com/watthanai/Node-Red-PIAPI/blob/master/PLC-Mitsubishi.md">PLC Mitsubishi to Kepware</a></li>
  <li><a href="">OPC to Kepware</a></li>
  </ul>
  <b><br>Data Logger</b>
  <p>After you have done configure kepserver. May be you want to have an application that logs data from an OPC server to any ODBC-compliant database </p> 

  <p align="center">
 <img  width=400px height=350px src="https://www.kepware.com/getmedia/9c8c0143-202f-4937-a2b0-bbda1590215c/datalogger"><br></p>
 <b><br>Configure Dataloger</b> 
   <ul><li><a href="">Open port SQL Workstaion </a> </li>
  <li><a href="">Config Module logger</a></li>
  </ul><br>

<li><b style="color:rgb(46, 204, 113)">SQL : </b> <br>This Paragraph describes how to configure a PLC with Ethernet module and other OPC on the Local Ethernet network.</li>
</ul>

## 🏁 SETUP PI SYSTEM <a name = "PIsetup"></a>

The PI system enables digital transformation through trusted, high-quality operations data. Collect, enhance, and deliver data in real time in  any location. [How the PI System works ? ](#PIsystem) 

### How the PI System works ?
<p align="center">
 <img  width=300px height=350px src="https://raw.githubusercontent.com/watthanai/Node-Red-PIAPI/master/images/kepware/Architecture-Kepware.PNG?token=GHSAT0AAAAAABTUUZXDPOL7S52PMAFOQLY2YTKHMLQ"><br></p>
<li><b style="color:rgb(46, 204, 113)">Collect : </b> <br>Collect real-time data from hundreds of assets—including legacy, proprietary, remote, mobile, and IIoT devices. The PI System connects you to your data, no matter the location or format.</li>
</ul>
<!-- ```
Collect
``` -->

### Installing

A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo.

## 🔧 Running the tests <a name = "tests"></a>

Explain how to run the automated tests for this system.

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## 🎈 Usage <a name="usage"></a>

Add notes about how to use the system.

## 🚀 Deployment <a name = "deployment"></a>

Add additional notes about how to deploy this on a live system.

## ⛏️ Built Using <a name = "built_using"></a>

- [MongoDB](https://www.mongodb.com/) - Database
- [Express](https://expressjs.com/) - Server Framework
- [VueJs](https://vuejs.org/) - Web Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ Authors <a name = "authors"></a>

- [@kylelobo](https://github.com/kylelobo) - Idea & Initial work

See also the list of [contributors](https://github.com/kylelobo/The-Documentation-Compendium/contributors) who participated in this project.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Hat tip to anyone whose code was used
- Inspiration
- References
