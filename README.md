# Wirebench (WIP)

This project has the intention of comparing several protocol for data streaming. 

## First phase
The first phase will consist of the comparisson between three streaming protocols:
- WebSocket
- WebRTC
- HTTP/3

## Comparisson
For comparisson we're gonna check the data throughtput between client - server showing how many of them reached the client and how many got lost. This metric is not final, and I'm gonna more in the future.

## Dataset
The dataset used will be an auto-generated one using some already made library. I thought on building my own 3D shape, but I think that'd be an overengieering for this

## Future work
- Would be nice if I can replace some protocols with an own version
- Use my own database engine (Go, LSM-tree and WAL) to store dataset and retrive to simulate real-life scenarios
