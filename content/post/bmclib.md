+++
date = "2015-12-2T14:10:00+03:00"
draft = false
title = "bmclib"
weight = 2
+++

A vendor agnostic Baseboard Management Controller library that exposes methods to perform *inventory*, *management*, *configuration* actions.
 
##### **Devices supported**

- Dell M1000e
- Dell iDRAC8 (M630)
- Dell iDRAC9 (M640)
- Dell c7000   
- HPE iLO4 (Gen8, Gen8)
- HPE iLO5 (Gen10)
- Supermicro X10
- Supermicro X11
- Device not listed? get in touch, we'd be happy to help add support :)

##### **Devices Work In Progress**

- Intel S2600WF0
- Quanta QuantaGrid D52BM-2U
- Work is underway to add Redfish support using the Gofish library

##### **Check it out on Github**
[![Status](https://api.travis-ci.org/bmc-toolbox/bmclib.svg?branch=master)](https://travis-ci.org/bmc-toolbox/bmclib)
[![Go Report Card](https://goreportcard.com/badge/github.com/bmc-toolbox/bmclib)](https://goreportcard.com/report/github.com/bmc-toolbox/bmclib)
[![GoDoc](https://godoc.org/github.com/bmc-toolbox/bmclib?status.svg)](https://godoc.org/github.com/bmc-toolbox/bmclib)

  {{< figure src="/img/Octocat.png" height="50px" width="60px" link="https://github.com/bmc-toolbox/bmclib" >}} 
  <iframe src="https://ghbtns.com/github-btn.html?user=bmc-toolbox&repo=bmclib&type=star&count=true" frameborder="0" scrolling="0" width="160px" height="30px"></iframe>  

 
  
##### The figure describes various bmc-toolbox tools that currently use bmclib to interact with BMCs.  

{{< figure src="/img/bmc-toolbox-diag.png" >}}
