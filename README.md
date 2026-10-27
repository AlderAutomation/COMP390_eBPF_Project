# COMP390 Project - eBPF Investigation and Comparisons 

## Introduction 

This project is a eBPF packet filtering project that I built for my Data Communications class in university. I wanted to prove and show that the eBPF was a much more performant way to filter packets with out relying on data from the internet.  

## Setup   

I have configured two Ubunter server VMs. Server A (labelled Sender) will send packet data to server B (lebelled Reciever). Reciever will run one the standard OS and firewal to test and log benchmarks. After gathering metrics for how the OS handles the data stream, we will run the eBPF packet filtering app to test and log those benchmarks. 

## Scope (Requirements)  

- Coding will be done in C language for best performance and for further C and OS programming practise. 
- Two identical Ubuntu VMs
- fake IP data
- filtering rules 
- iperf3, ping, traceroute, btm for gathering benchmarking information

## eBPF Information  

INFO about eBPF in General

## Baseline Data

INFO about OS filtering & performance

## eBPF Filtering App 

INFO about eBPF filtering and performance

## Sample Packet Data  

Possible sample packet data will be coming from:  
- (PCAP files)[https://wiki.wireshark.org/SampleCaptures]  
- My own network (Maybe)   

## Further Reading (References)  

link to ebpf
link 
