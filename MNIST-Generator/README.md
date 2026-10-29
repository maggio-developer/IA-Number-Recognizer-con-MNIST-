ESTA RED FUE ENTRENADA CON MNIST 60000 training + 10000 testing BATCH.
PUEDE CREAR IMAGENES DEL 0 al 9 EN UNA CUADRICULA 28*28 de MNIST

Layers amount: 1

LayerType: VAE
Encoder amount: 3
Layer 1
LayerType: Dense
Input: 784
Output(Neurons): 128
Activation: ReLU
Regularizator: None
Optimizer: Adam
Batch Normalization: False
Layer 2
LayerType: Dense
Input: 128
Output(Neurons): 64
Activation: ReLU
Regularizator: None
Optimizer: Adam
Batch Normalization: False
Layer 3
LayerType: Dense
Input: 64
Output(Neurons): 32
Activation: Linear
Regularizator: None
Optimizer: Adam
Batch Normalization: False
Decoder amount: 3
Layer 1
LayerType: Dense
Input: 32
Output(Neurons): 64
Activation: ReLU
Regularizator: None
Optimizer: Adam
Batch Normalization: False
Layer 2
LayerType: Dense
Input: 64
Output(Neurons): 128
Activation: ReLU
Regularizator: None
Optimizer: Adam
Batch Normalization: False
Layer 3
LayerType: Dense
Input: 128
Output(Neurons): 784
Activation: Sigmoid
Regularizator: None
Optimizer: Adam
Batch Normalization: False
Amount of trainings: 3

Training error initial: 0.243033
Training accuracy initial: 0%

Amount of augmentations: 0

Epochs: 20
Batch: 70000
Minibatch: 64
Learning Rate: 0.001
Dropout: 0%
Shuffle: true

Training error final: 0.0321284
Training accuracy final: 0%

Time training: 100.346s
Time forward: 17.3941s
Time backward: 79.0506s


Training error initial: 0.0321058
Training accuracy initial: 0%

Amount of augmentations: 0

Epochs: 20
Batch: 70000
Minibatch: 128
Learning Rate: 0.001
Dropout: 0%
Shuffle: true

Training error final: 0.0312861
Training accuracy final: 0%

Time training: 66.416s
Time forward: 14.8258s
Time backward: 48.2114s


Training error initial: 0.0312787
Training accuracy initial: 0%

Amount of augmentations: 0

Epochs: 50
Batch: 70000
Minibatch: 128
Learning Rate: 0.001
Dropout: 0%
Shuffle: true

Training error final: 0.0303273
Training accuracy final: 0%

Time training: 167.135s
Time forward: 37.814s
Time backward: 122.17s