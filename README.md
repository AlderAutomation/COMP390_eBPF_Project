# COMP390 Project - eBPF Investigation and Comparisons 

## Introduction 

This repo contains two different apps, both do packet filter, but one works in user space and the other works in Kernel space using eBPF. These programs are meant to do the same filtering on same VM with same sample packet traffic to compare the difference of processing performance of user space and kernel space. 

## Setup  

I have configured two Ubunter server VMs. One will send packet data to the the second VM. The Second VM will run one packet filtering app and log benchmarks and then it will run the other packet filtering app using eBPF and log those benchmarks. Coding will be done in C language for best performance and for further C and OS programming practise. 

## Userland Filtering App 

This will be using the pcap libary to capture packet information.  

## Kernel Filtering App 

This will be using eBPF to capture packet information.  

## Benchmarking Tools 

To capture the benchmarks required for my report, I will be using network tools such as:  
- iperf3  
- ping  
- traceroute  

## Sample Packet Data  

Possible sample packet data will be coming from:  
- (PCAP files)[https://wiki.wireshark.org/SampleCaptures]  
- My own network (Maybe)   

## Further Reading 

There will be additional READMEs for each program in the subfolders. 
