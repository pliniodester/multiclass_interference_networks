# multiclass_interference_networks

Calculates the success probability and throughput of the uplink in a multi-class network (e.g. LoRa), where transmitters are homogeneously distributed in concentric rings and the receiver is in the center, given the following information:

- alpha = path-loss exponent
- tau   = vector of packet transmission times for each class
- theta = matrix of interference among classes in dB
- ri    = vector of internal radius of each ring
- ro    = vector of external radius of each ring
