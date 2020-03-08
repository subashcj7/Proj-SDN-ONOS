# Proj-SDN-ONOS
This project domain based on the IOt and network.with the growth of iot network this project based on the dynamic traffic priortization in iot networks based on ONOS using SDN

#descripion
  In a campus network there are multiple users each running several Internet applications concurrently, competing for the available bandwidth. Even though the access link is rarely fully utilized, prioritizing traffic during contention is important. Our solution consists of an SDN application, which makes traffic prioritization decisions, client agents running in the end host devices which send periodic contextual reports to the controller application and a router which applies the traffic prioritization rules to the active flows. However, our solution changes the bandwidth allocations in these links according to detected active traffic. The client agents periodically inform the controller about currently active flows,the applications those flows belong to, applications the user is  directly interacting with, the visible percentages of the active windows, applications playing sound and so on. For example, consider a campus network with motion sensor, camera and computers generating user traffic as shown in the topology. For a particular floor in the building, if the motion sensor detect any movement, the cameras should be given higher priority to stream HD video and web trffic should given lower priority. Similarly when there is no motion, the cameras should only stream SD video and we should not let the camera's UDP traffic take over the link bandwidth.  the number of push-and-forget devices are increasing in traditional networks. These IoT devices are used for some application at the edge server or the cloud. The goal of the project is to effectively prioritize traffic in a network which is mixture of IoT and traditional network. We leverage the application level knowledge of the IoT network to analyse the importance of the data. Using SDN, this application layer knowledge can be translated into traffic priorities. 
For example, consider a campus network with motion sensor, camera and computers generating user traffic as shown in the topology. For a particular floor in the building, if the motion sensor detect any movement, the cameras should be given higher priority to stream HD video and web trffic should given lower priority.  


#specification
 Software Specifications 
 
1. Ubuntu[18.04] 
2. MININET emulator 
3. ONOS[Open Network Operating System] 
 
2. Hardware Specifications 
 1. Motion Sensor                                   
 2. CCTV Camera                                   
 3. Router                                   
 4.SDN Controller 
