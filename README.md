# ns3-simple-multicast-flooding

This repository conatins the ns-3 simulation code used to evaluate the impact of Duplicate Packet Detection. The code is based on the original simple-multicast-flooding.cc found in the examples directory in ns-3.

## Modifications

Modifications done to the code:
1. Added a Time-To-Live value
2. Duplicate packet detection on/off

## How to run

1. copy 'simple-multicast-flooding.cc' into your ns-3 'scratch/' directory
2. Build and run:
    ./ns3 run scratch/simple-multicast-flooding

The program then prints the amount of received data per node