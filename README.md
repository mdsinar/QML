# QML

Project descriptions:

## Prediction of Brain Tumor Occurance from Genetic Markers: 

BrainTumorClassification: Based on genetic markers, predicts tumor presence. This implementation uses Qiskit and its template feature maps for a QNN aproach.


## Tumor Recognition from CT Scans:

In this project, we use Pennylane. The quantum circuit is custom designed without use of templates. The idea is to embed data as rotations, produce a single qubit output through a close ring CNOT circuit with arbitrary rotations, than compare output states with a SWAP test.

TumorRecognition-2-An-4Q: Implements data embedding on a 4-qubit system. There is some data loss since I have to compress the image matrix into a 4x1 array. As a result classification suffers a bit with this approach.

TumorRecognition-2-Ancilla: Implements data embedding on a 8-qubit system. With more qubits used, there is less data loss and classification performance is better. Due to my old computer (:D), this code uses a reduced dataset.
