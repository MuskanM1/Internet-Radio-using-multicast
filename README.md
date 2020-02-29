# Internet-Radio-using-multicast
C application to implement Internet Radio over IP Multicast

# CPU Scheduler using MultiThreading

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Usage](#usage)
* [Summary](#Summary)
* [Results](#Results)
* [Report Link](#report-Link)


## General info
This project is C implementation of Internet Radio using Multicasting consisting of both server and client side interfaces.

## Technologies
Project is created with:
* Programming Language: C 


## Summary
The project is an application of Internet Radio which involves multicasting of data in the form of
multimedia over IP. Since, in a radio any number of users can be tuned in to a particular station
out of all the available stations at any time; to support the same scenario the model used in our
project is Any Source Multicast model (ASM). In this model, multicast group address will help to
identify the multicast messages and multiple senders can be part of the same group. Just like a
user can change and exit the stations in an actual radio, our client and server provides the
similar functionality. The connection of sockets is initially done using TCP which establishes
control channel and later the multimedia is sent using UDP socket since it is more efficient for
multicast type of transmission. Hence, in all it implements one-to-many multicast several times.

## Results

##### SERVER SIDE 
![Alt Text](https://github.com/MuskanM1/Internet-Radio-using-multicast/blob/master/docs/screenshots/server.JPG)

##### CLIENT SIDE
![Alt Text](https://github.com/MuskanM1/Internet-Radio-using-multicast/blob/master/docs/screenshots/client.JPG)

##### FINAL OUTPUT
DRR performs better than RR
![Alt Text](https://github.com/MuskanM1/Internet-Radio-using-multicast/blob/master/docs/screenshots/final.JPG)

##### GUI 
![Alt Text](https://github.com/MuskanM1/Internet-Radio-using-multicast/blob/master/docs/screenshots/GUI.JPG)

