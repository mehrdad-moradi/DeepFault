# DeepFault: Fault Localization for Deep Neural Networks

This code is very much "research code": it is provided as a reference of exact details of the experiments and attacks.
If you encounter any problem do not hesitate to reach me.

Results are logged in "result.log" file by default. One should expect a lower score with _tarantula_, _ochiai_ or _dstar_ when compared to _random_.
_random_ should be run only after _tarantula_, _ochiai_ and _dstar_ suspicious neurons are determined -saved- as random suspicious neurons are selected from the rest of the neurons.

### Update
Scripts related to MNIST dataset are tested with the following versions:
Keras 2.3.1
Tensorflow 1.13.2

See the FASE'2019 paper [DeepFault: Fault Localization for Deep Neural Networks](https://arxiv.org/abs/1902.05974) for more details.

## Abstract
Deep Neural Networks (DNNs) are increasingly deployed in safety-critical applications including autonomous vehicles and medical diagnostics. To reduce the residual risk for unexpected DNN behaviour and provide evidence for their trustworthy operation, DNNs should be thoroughly tested. The DeepFault whitebox DNN testing approach presented in our paper addresses this challenge by employing suspiciousness measures inspired by fault localization to establish the hit spectrum of neurons and identify suspicious neurons whose weights have not been calibrated correctly and thus are considered responsible for inadequate DNN performance. DeepFault also uses a suspiciousness-guided algorithm to synthesize new inputs, from correctly classified inputs, that increase the activation values of suspicious neurons. Our empirical evaluation on several DNN instances trained on MNIST and CIFAR-10 datasets shows that DeepFault is effective in identifying suspicious neurons. Also, the inputs synthesized by DeepFault closely resemble the original inputs, exercise the identified suspicious neurons and are highly adversarial.


## Copyright Notice
DeepFault: Fault Localization for Deep Neural Networks Copyright (C) 2019 Bogazici University

DeepFault is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

DeepFault is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with DeepFault. If not, see https://www.gnu.org/licenses/.

mail: hfeniser@mpi-sws.org, simos.gerasimou@york.ac.uk
