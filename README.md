

---------

        It’s likely that, within the next two to three years, the AI industry will converge around one open-source cross-compilation supported by all front-end and back-end environments. Other industry developments in recent weeks call attention to the opening of the AI cross-compilation ecosystem.

        These include:

        - Microsoft’s open-sourcing of a GitHub repo to foster cross-framework benchmarking of GPU-optimized deep learning models.
        - ARM’s partnership with Nvidia to integrate the open-source Nvidia Deep Learning Accelerator architecture into its just-announced Project Trillium platform, designed to enable cross-framework deep learning model compilation for optimized execution in mobile, “internet of things” and other mass-market edge devices.
        - IBM’s launch of the new open-source Fabric for Deep Learning framework, which supports optimized deployment of deep-learning microservices built in TensorFlow, PyTorch, Caffe2 and other frameworks to diverse compute nodes on heterogeneous clusters of GPUs and CPUs via stateless RESTful interfaces over Kubernetes.
        - Linux Foundation’s launch of the Acumos AI Project, which defines APIs, an open-source framework, and an AI model catalog for framework-agnostic AI app development, chaining and deployment over Kubernetes.


 More details on [DL compilers](https://github.com/gopala-kr/a-week-in-wild-ai/tree/master/12-ai-hardware-compilers)


      The aim of this project is to do the fundamental research and experimentation on
         - Existing/emerging ML/DL compiler optimization technologies 
         - Different hardwares/computing platforms which can accelerate ML/DL model training and inference(active research area)
         - Research on each computing platform and code optimization/synthesis from high level to low level machine code(active research area)
         - To find out how the existing platforms differ from each other and their offerings
         - To bring out the best in all frameworks, which helps in creating single open platform/standard.
         - To initiate a single cross-compilation open platform which simplifies integration of future frontend and backend environments.
         - To publish a papers on this research
         
------------------


- [Review Papers](https://github.com/gopala-kr/DL-on-Silicon/blob/master/review_papers.md)

        

##### References

- [AI-accelerators(CPU, GPU, FPGA, ASIC, SoC, HPC), Neuromorphic and Quantum Compute for AI](https://github.com/gopala-kr/a-week-in-wild-ai/tree/master/01-ai-accelerators)
- [case study: ml/dl frameworks/libraries(an architectural overview)](https://github.com/gopala-kr/10-weeks/tree/master/Projects-Blogs/06-ml-dl-frameworks)
- [deep learning compiler Optimization for different hardwares](https://github.com/gopala-kr/a-week-in-wild-ai/tree/master/12-ai-hardware-compilers)
- [Demystifying Deep Learning Frameworks and Libraries(end to end low+high level)](https://github.com/gopala-kr/a-week-in-wild-ai/tree/master/14-demystifying-dl-frameworks-and-libraries)
- [Neural Networks on Silicon](https://github.com/fengbintu/Neural-Networks-on-Silicon)
- [Embedded-Neural-Network](https://github.com/ZhishengWang/Embedded-Neural-Network)
- [MyCaffe: A Complete C# Re-Write of Caffe with Reinforcement Learning](https://arxiv.org/ftp/arxiv/papers/1810/1810.02272.pdf)
- [Tensor Comprehensions: Framework-Agnostic High-Performance Machine Learning Abstractions](https://arxiv.org/abs/1802.04730)
- [TVM: An Automated End-to-End Optimizing Compiler for Deep Learning](https://arxiv.org/abs/1802.04799)
- [Toolflows for Mapping Convolutional Neural Networks on FPGAs:
A Survey and Future Directions](https://arxiv.org/pdf/1803.05900v1.pdf)
- [The implementation of a Deep Recurrent Neural
Network Language Model on a Xilinx FPGA](https://arxiv.org/ftp/arxiv/papers/1710/1710.10296.pdf)
- [Automatic Full Compilation of Julia Programs and ML Models to Cloud TPUs](https://arxiv.org/pdf/1810.09868v1.pdf)
- [Facebook: Hardware & Software Systems research](https://research.fb.com/announcing-the-winners-of-the-facebook-hardware-software-systems-research-awards/)
- [Intel AI: high-throughput-object-detection-on-edge-platforms-with-fpga](https://ai.intel.com/high-throughput-object-detection-on-edge-platforms-with-fpga/)
- [Intel AI: adaptable-deep-learning-solutions-with-ngraph-compiler-and-onnx](https://ai.intel.com/adaptable-deep-learning-solutions-with-ngraph-compiler-and-onnx/)
- [Intel AI: intel-fpgas-powering-real-time-ai-inferencing](https://ai.intel.com/intel-fpgas-powering-real-time-ai-inferencing/)
- [Intel AI: heterogenous-computing-ai-hardware-designed-for-specific-tasks ](https://ai.intel.com/heterogenous-computing-ai-hardware-designed-for-specific-tasks/)
- [Intel AI Academy: Framework Optimization Training](https://software.intel.com/en-us/ai-academy/frameworks)
- [Intel® Optimization for TensorFlow*](https://software.intel.com/en-us/videos/introduction-to-intel-optimization-for-tensorflow)
- [Intel AI Docs](https://ai.intel.com/docs/) 
- [CUDA](https://github.com/Erkaman/Awesome-CUDA) - useful libraries and resources for CUDA development
- [IBM AI: Hardware and the Physics of AI](https://www.research.ibm.com/artificial-intelligence/physics-of-ai/)
- [DyNet: The Dynamic Neural Network Toolkit](https://arxiv.org/pdf/1701.03980.pdf)
- [Deep Learning with Dynamic Computation Graphs](https://arxiv.org/pdf/1702.02181.pdf)
- [Mesh-TensorFlow: Deep Learning for Supercomputers](https://arxiv.org/pdf/1811.02084v1.pdf)
- [AI Benchmark: Running Deep Neural Networks
on Android Smartphones](https://arxiv.org/pdf/1810.01109v1.pdf)
- [Apple: Democratizing Production-Scale Distributed Deep Learning](https://arxiv.org/pdf/1811.00143v1.pdf)
- [Communication Primitives in Deep Learning Frameworks](https://medium.com/south-park-commons/communication-primitives-in-deep-learning-frameworks-7faefb2f3f63)
- [Comparing Deep Learning Frameworks: A Rosetta Stone Approach](https://blogs.technet.microsoft.com/machinelearning/2018/03/14/comparing-deep-learning-frameworks-a-rosetta-stone-approach/)
- [CodeX: Bit-Flexible Encoding for Streaming-based FPGA Acceleration of DNNs](https://arxiv.org/abs/1901.05582v1)
- [EcoRNN: Efficient Computing of LSTM RNN Training on GPUs](https://arxiv.org/abs/1805.08899v4)
- [Training for 'Unstable' CNN Accelerator:A Case Study on FPGA](https://arxiv.org/abs/1812.01689v1)
- [Optimized Compilation of Aggregated Instructions for Realistic Quantum Computers](https://arxiv.org/abs/1902.01474v1)
- [Software-Defined FPGA Accelerator Design for Mobile Deep Learning Applications](https://arxiv.org/abs/1902.03192v1)
- [Systimator: A Design Space Exploration Methodology for Systolic Array based CNNs Acceleration on the FPGA-based Edge Nodes](https://arxiv.org/abs/1901.04986v2)
- [TensorSCONE: A Secure TensorFlow Framework using Intel SGX](https://arxiv.org/abs/1902.04413v1)
- [Quantum Entanglement in Deep Learning Architectures](https://arxiv.org/abs/1803.09780v3)
- [Lingvo: a Modular and Scalable Framework for Sequence-to-Sequence Modeling](https://arxiv.org/abs/1902.08295v1)
- [Hyperdrive: A Multi-Chip Systolically Scalable Binary-Weight CNN Inference Engine](https://arxiv.org/abs/1804.00623v3)
- [High-Throughput CNN Inference on Embedded ARM big.LITTLE Multi-Core Processors](https://arxiv.org/abs/1903.05898v1)
- [Improving Transparency of Deep Neural Inference Process](https://arxiv.org/abs/1903.05501v1)
- [Neuromorphic Hardware learns to learn](https://arxiv.org/abs/1903.06493v1)
- [FixyNN: Efficient Hardware for Mobile Computer Vision via Transfer Learning](https://arxiv.org/abs/1902.11128v1)
- [Extracting Success from IBM's 20-Qubit Machines Using Error-Aware Compilation](https://arxiv.org/abs/1903.10963v1)
- [Multi-Level Intermediate Representation" Compiler Infrastructure](https://github.com/tensorflow/mlir)
- [TensorFlow Lite Now Faster with Mobile GPUs (Developer Preview)](https://medium.com/tensorflow/tensorflow-lite-now-faster-with-mobile-gpus-developer-preview-e15797e6dee7)
- [Open-sourcing PyTorch-BigGraph for faster embeddings of extremely large graphs](https://ai.facebook.com/blog/open-sourcing-pytorch-biggraph-for-faster-embeddings-of-extremely-large-graphs/)
- [Accelerated Neural Networks on OpenCL Devices Using SYCL-DNN](https://arxiv.org/abs/1904.04174v1)
- [DARPA, NSF Seek Real-Time ML Processor](https://www.hpcwire.com/2019/03/18/darpa-nsf-seek-real-time-ml-processor/)
- [unlocking-dl-performance-with-ngraph](https://www.intel.ai/unlocking-dl-performance-with-ngraph/#gs.72u424)
- [Deep Learning in Mobile and Wireless Networking: A Survey](https://arxiv.org/pdf/1803.04311v3.pdf)
- [Meta Filter Pruning to Accelerate Deep Convolutional Neural Networks](https://arxiv.org/abs/1904.03961v1)
- [alibaba/ai-matrix](https://github.com/alibaba/ai-matrix) - To make it easy to benchmark AI accelerators
- [facebookresearch/deepfloat](https://github.com/facebookresearch/deepfloat) - An exploration of log domain "alternative floating point" for hardware ML/AI accelerators.
- [Stanford: Hardware Accelerators for Machine Learning (CS 217)](https://cs217.stanford.edu/)
- [https://github.com/pytorch/glow](https://github.com/pytorch/glow) - Compiler for Neural Network hardware accelerators
- [MorphIC: A 65-nm 738k-Synapse/mm2 Quad-Core Binary-Weight Digital Neuromorphic Processor with Stochastic Spike-Driven Online Learning](https://arxiv.org/abs/1904.08513v1)
- [NeuroPod: a real-time neuromorphic spiking CPG applied to robotics](https://arxiv.org/abs/1904.11243v1)
- [NengoDL: Combining deep learning and neuromorphic modelling methods](https://arxiv.org/abs/1805.11144v3)
- [Dynamic Power Management for Neuromorphic Many-Core Systems](https://arxiv.org/abs/1903.08941v1)
- [Programming multi-level quantum gates in disordered computing reservoirs via machine learning](https://arxiv.org/abs/1905.05264v2)
- [Bayesian Deep Learning on a Quantum Computer](https://arxiv.org/abs/1806.11463v3)
- [Defining Quantum Neural Networks via Quantum Time Evolution](https://arxiv.org/abs/1905.10912v1)
- [Full-stack Optimization for Accelerating CNNs with FPGA Validation](https://arxiv.org/abs/1905.00462v1)
- [OpenCL-based FPGA accelerator for disparity map generation with stereoscopic event cameras](https://arxiv.org/abs/1903.03509v1)
- [Energy-Efficient Inference Accelerator for Memory-Augmented Neural Networks on an FPGA](https://arxiv.org/abs/1805.07978v2)

------------


_**Maintainer**_

Gopala KR /@gopala-kr

------------
