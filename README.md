# Design-and-Implementation-of-Adaptive-CoCoA++
## Course Code - CO365
An attempt to design and implement Adaptive CoCoA++

## Overview 
CoAP is a wide application layer protocol used on top of UDP to ensure reliability in IoT network. It used exponential backoff. CoCoA and CoCoA+ used the information from the network i.e. RTT to calculate RTO and accordingly backoff. CoCoA++ is another modification that uses the concepts of CDG to do the backoff.

## Approach
- Studied CoAP,CoCoA,CoCoA+,CDG.
- Documented understanding.
- Took the implementation of CoCoA++ from mentor.
- Understood it and ran various experiments on it & recorded the results.
- Proposed a mechanism to make the backoff adaptive.
- Implemented the algorithm and used fixed point arithmetic to do so.
- Tested the algorithm and obtained the results.

