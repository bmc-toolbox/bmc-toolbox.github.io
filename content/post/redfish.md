+++
date = "2019-09-08T11:10:00+03:00"
draft = false
title = "Redfish"
weight = 9
+++

### What about Redfish?


 
  Redfish is a standard defined by the *DMTF*, hardware vendors are then expected to implement these standards,  
  on thier BMCs, however the problems we faced when dealing with a large fleet were,

  - Vendors are quite slow at implementing and keeping up with the released standards
  - Some of the implementations are just incorrect or not functional (we try to report these when we find them)  
  - Not all of the methods exposed by bmclib are currently exposed through Redfish.


  Redfish support is currently being added to bmclib through the Gofish library.  
  The tools in the bmc-toolbox leverage bmclib which helps get around these limitations. 
   

```
Redfish support as of 09 Sept 2019

BMC type                       BMC firmware      Redfish version
========                       ============      ===============
idrac8 (M630)                   v2.60.60.60        Unsupported
idrac9 (M640)                   v3.34.34.34        v1.4.0
ilo4   (Gen8, Gen9)             v2.70              v1.0.0
ilo5   (Gen10)                  v1.6.0             v1.6.0
Supermicro (X10DRFF-CTG)         -                 v1.0.1
QuantaGrid (D42A-2U)             -                 v1.1.0
Intel      (S2600WF0)            -                 v1.1.0
```
