# Awesome Neuromorphic [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome spiking or neuromorphic frameworks, libraries, resources, and other things (i.e. useful robotics simulators and frameworks).

## Contents

- [Spiking and Neuromorphic Frameworks](#spiking-and-neuromorphic-frameworks)
- [ANN2SNN Converters](#ann2snn-converters)
- [Robotic Toolkits](#robotic-toolkits)
- [Datasets and Dataset Tools](#datasets-and-dataset-tools)
- [Computational Neuroscience Software](#computational-neuroscience-software)
- [Institutes and Groups](#institutes-and-groups)
  - [Motiv NT](#motiv-nt).
  - [The Neuromorphic Vision and Natural Computation Team](#the-neuromorphic-vision-and-natural-computation-team).
  - [Brainchip](#brainchip).
  - [SynSense](#synsense).
  - [Open Neuromorphic](#open-neuromorphic).
- [Hardware](#hardware).


## Spiking and Neuromorphic Frameworks

- [BindsNET](https://github.com/BindsNET/bindsnet) - Python package used for simulating spiking neural networks (SNNs) on CPUs or GPUs using PyTorch Tensor functionality.
- [BrainCog](https://github.com/BrainCog-X/Brain-Cog) - BrainCog is an open source spiking neural network based brain-inspired cognitive intelligence engine for Brain-inspired Artificial Intelligence and brain simulation.
- [Brian 2](https://brian2.readthedocs.io) - Brian is a simulator for spiking neural networks. It is written in the Python programming language and is available on almost all platforms. We believe that a simulator should not only save the time of processors, but also the time of scientists. Brian is therefore designed to be easy to learn and use, highly flexible and easily extensible.
- [CARLSim](https://github.com/UCI-CARL/CARLsim6) - CARLsim is an efficient, easy-to-use, GPU-accelerated library for simulating large-scale spiking neural network (SNN) models with a high degree of biological detail.
- [GeNN](https://github.com/genn-team/genn) - GeNN is a GPU-enhanced Neuronal Network simulation environment based on code generation for Nvidia CUDA.
- [Intel LAVA](https://github.com/lava-nc) - Software Framework for Neuromorphic Computing from Intel.
- [Kaspersky Neuromorphic Platform](https://github.com/KasperskyLab/knp) - The Kaspersky Neuromorphic Platform or KNP is a software platform for developing, training and executing spiking neural networks on a variety of computers. Platform contains totally spiking package, that allows to build and run spiking networks on CPU or AltAI neuromorphic hardware and ANN2SNN package, that can train spiking networks using Tensorflow and then run AltAI. Core of the platform was written in C++. KNP has fully-functional C++ and Python frameworks.
- [Moose](https://moose.ncbs.res.in/) -  Multiscale Object-Oriented Simulation Environment. It is designed to simulate neural systems ranging from subcellular components and biochemical reactions to complex models of single neurons, circuits, and large networks.
- [Nengo](https://www.nengo.ai/) - Python package for building, testing, and deploying spiking neural networks.
- [Nest](https://www.nest-simulator.org/) - NEST is a simulator for spiking neural network models that focuses on the dynamics, size and structure of neural systems rather than on the exact morphology of individual neurons.
- [NetPyNE](http://www.netpyne.org/) - Python package to facilitate the development, simulation, parallelization, analysis, and optimization of biological neuronal networks using the NEURON simulator.
- [Neural Circuit Policies](https://github.com/mlech26l/ncps) - Neural Circuit Policies (NCPs) are designed sparse recurrent neural networks loosely inspired by the nervous system of the organism C. elegans. The goal of this package is to making working with NCPs in PyTorch and keras as easy as possible.
- [NEURON](https://www.neuron.yale.edu/neuron/) - The NEURON simulation environment is used in laboratories and classrooms around the world for building and using computational models of neurons and networks of neurons.
- [Norse](https://norse.github.io/norse/) - A deep learning library for spiking neural networks. Deep learning Python library used for simulating spiking neural networks that leverages PyTorch with bio-inspired neural networks. Norse is a community-driven project, encouraging community contributions and development.
- [PeleNet](https://github.com/sagacitysite/pelenet) - Reservoir computing framework for Loihi.
- [PyNN](https://neuralensemble.org/PyNN/) - Python package for simulator-independent specification of neuronal network models.
- [PySNN](https://github.com/BasBuller/PySNN) - Spiking neural network (SNN) framework written on top of PyTorch for efficient simulation of SNNs both on CPU and GPU.
- [Rockpool](https://rockpool.ai/) - Rockpool is designed to let you design, simulate, train and test dynamical neural networks, which include explicit temporal dynamics and simulation of time. Rockpool created by SynSense (see below) and supports SynSense neuromorphic hardware. Rockpool allows to build networks, simulate, train, test, and deploy them in simulation or event-driven neuromorphic compute hardware. Rockpool provides layers with many simulation backends, including Brian2, NEST, Torch, JAX, Numba, and raw NumPy. It is not designed for detailed simulation of biological networks.
- [Sinabs](https://www.synsense.ai/products/sinabs/) - Open source PyTorch based library, developed to design and implement Spiking Convolutional Neural Networks. Created by SynSense. The library implements several layers that are spiking equivalents of CNN layers. In addition it provides support to import CNN models implemented in Keras conveniently to test their spiking equivalent implementation.
- [SNN Torch](https://snntorch.readthedocs.io/en/latest/index.html) - snnTorch is designed to be intuitively used with PyTorch, as though each spiking neuron were simply another activation in a sequence of layers. It is therefore agnostic to fully-connected layers, convolutional layers, residual connections, etc.
- [SPAIC](https://github.com/ZhejianglabNCRC/SPAIC) - Spike-based artificial intelligence computing platform.
- [spikeflow](https://github.com/colinator/spikeflow) - Spiking neural networks in tensorflow.
- [SpikingJelly](https://github.com/fangwei123456/spikingjelly) - Open-source deep learning framework for Spiking Neural Network (SNN) based on PyTorch.
- [Spyx](https://spyx.readthedocs.io) - compact spiking neural network library built on top of DeepMind's Haiku package. Spyx promises the flexibility and extensibility offered by PyTorch-based SNN libraries while enabling extremely efficient training on high-performance hardware at speeds comparable to or faster than SNN frameworks that have custom CUDA implementataions.
- [The HBP Neuromorphic Computing Platform](https://electronicvisions.github.io/hbp-sp9-guidebook/) - Part of the EBRAINS research infrastructure. The EBRAINS infrastructure is created by the Human Brain Project (HBP).


## ANN2SNN Converters

- [snn_toolbox](https://github.com/NeuromorphicProcessorProject/snn_toolbox) - The SNN conversion toolbox (SNN-TB) is a framework to transform rate-based artificial neural networks into spiking neural networks, and to run them using various spike encodings.


## Robotic Toolkits

- [DART](https://dart.readthedocs.io/en/latest/) - Dynamic Animation and Robotics Toolkit.


## Datasets and Dataset Tools

- [Tonic](https://github.com/BrainCog-X/tonic_braincog) - Tonic is a tool created by SynSense, to facilitate the download, manipulation and loading of event-based/spike-based data. It's like PyTorch Vision but for neuromorphic data. Tonic provides publicly available event-based vision and audio datasets and event transformations. The package is fully compatible with PyTorch Vision/Audio, giving you the flexibility you need.


## Computational Neuroscience Software

- [BrainPy](https://github.com/brainpy/BrainPy) - Framework for computational neuroscience and brain-inspired computation based on the Just-In-Time (JIT) compilation (built on top of JAX, Numba, and other JIT compilers). It provides an integrative ecosystem for brain dynamics programming, including brain dynamics building, simulation, training, analysis, etc.


## Institutes and Groups

### Motiv NT

AltAI NPU developers.

- [motivnt.ru](https://motivnt.ru/) - Official site.


### The Neuromorphic Vision and Natural Computation Team

Team, based at the Institut de la Vision in Paris.

- [www.neuromorphic-vision.com](https://www.neuromorphic-vision.com/) - Official site.
- [GitHub repository](https://github.com/neuromorphic-paris) - Projects code.


### Brainchip

Akida NPU developers.

- [brainchip.com](https://brainchip.com/) - Official site.


### Open Neuromorphic

Neuromorphic Computing and Engineering Community provides:

- Educational content to get you started with the neuromorphic engineering.
- Events about neuromorphic research and software, with contributions from both academia and industry.
- A curated list of neuromorphc open source software and hardware to make it easier to find the tool you need.
- A platform for your code. If you wish to create a new repository or migrate your existing code to ONM, please get in touch with us.

- [open-neuromorphic.org](https://open-neuromorphic.org/) - Official site.
 

### SynSense

SynSense focuses on the commercialization of neuromorphic intelligence, based on 20+ years of world-leading experience of University of Zürich and ETH Zürich.

- [www.synsense.ai](https://www.synsense.ai/) - Official site.


## Hardware

- [Motiv AltAI](https://motivnt.ru/neurochip-altai/) - AltAI NPU description page.
- [Asprinity AML100](https://www.aspinity.com/aml100) - Analog machine learning chips for the lowest always-on system power.
- [End-to-End Implementation of Various Hybrid Neural Networks on a Cross-Paradigm Neuromorphic Chip](https://www.researchgate.net/publication/348962820) - Paper.
- [Brainchip Akida](https://brainchip.com/akida-neural-processor-soc/) - Akida NPU.
- [Intel Loihi 2](https://www.intel.com/content/www/us/en/research/neuromorphic-computing-loihi-2-technology-brief.html) - Intel Loihi 2 NPU.
- [Leaky Integrate and Fire (LIF) model implementation for FPGA](https://github.com/metr0jw/Spiking-Neural-Network-on-FPGA) - FPGA example.
- [Tianjic](https://ieeexplore.ieee.org/document/8998338) - A Unified and Scalable Chip Bridging Spike-Based and Continuous Neural Computation.
- [Xylo](https://www.synsense.ai/products/xylo/) - SynSense's programmable neuromorphic chip, excels in low-dimensional signal processing. Combines the analog front end that can efficiently provide pre-processing functionality to input analog signals. Xylo is highly re-configurable and scalable, which supports feed-forward, recurrent and reservoir and other complex neural network structure. Seamlessly integrate Xylo with MEMS microphones, thermal sensors, pressure sensors, vibration sensors, IMUs, gyros, PPG sensors, and more. 


## Footnotes

- [Awesome Neuroscience](https://github.com/realamirhe/awesome-computational-neuro-science) - Computational Neuro Science repository.
- [Event-based Vision Resources](https://github.com/uzh-rpg/event-based_vision_resources#neuromorphic-systems) - Big articles list.
