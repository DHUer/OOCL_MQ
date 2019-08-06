# OOCL_MQ

This repository is designed to offer a quick and simple solution for my company (OOCL) in a specific domain oriented scene.  

## Problem Description

There is only one Central Scanner Router(CSR) in my company used for capturing the RFID(radio-frequency identification) information details on many antenna boards sequentially. And at the same time, there are about dozens of clients needed to communicate with the CSR to gain information about the RFID. The performance downside happens when there are multiple clients sending the request to the CSR simultaneously, then other clients will be blocked for seconds. Besides, the CSR will traverse all the antenna boards to gain the refreshed RFID information, which is trivial and time-consuming.
 
Below here is a flow chart of the processing procedure:

```mermaid
graph TD;
  antenna_board_#1 --> CSR;
  antenna_board_#2 --> CSR;
  antenna_board_#n --> CSR;
  CSR --> client_#1;
  CSR --> client_#2;
  CSR --> client_#n;
```

### The 

## Redis

Redis的优点：
* 数据In-Memory
* 
