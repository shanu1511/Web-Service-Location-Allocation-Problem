# WSLAP Benchmark Instances

This repository provides the benchmark instances used in the research paper:

**Web Service Location‑Allocation using Discrete NSGA‑II with Matrix-Based Genetic Operations and a Repair Mechanism**  
**Authors**: Shanu Verma, Millie Pant, Vaclav Snasel  
**Journal**: *Journal of Ambient Intelligence and Humanized Computing*, 2023  
 [DOI: 10.1007/s12652-023-04625-6](https://doi.org/10.1007/s12652-023-04625-6)

## Model Details

- **Model-I (`model1/`)**  
  Bi-objective model minimizing:  
  1️ Total deployment cost  
  2️ Total **response time** based on **latency**

- **Model-II (`model2/`)**  
  Bi-objective model minimizing:  
  1️ Total deployment cost  
  2️ Total **negative quality factor** = Latency / Throughput  

## Data Sources

- **Latency and Throughput Data**: Sourced from the publicly available **WS-DREAM dataset**:
  - Website: [https://wsdream.github.io/](https://wsdream.github.io/)
- **Deployment Cost and Invocation Frequency**: These files are generated as part of this study and provided here.


##Citations

If you use these instances in your research, please cite:

bibtex
@article{verma2023wslap,
  title     = {Web service location-allocation using discrete NSGA-II with matrix-based genetic operations and a repair mechanism},
  author    = {Verma, Shanu and Pant, Millie and Snasel, Vaclav},
  journal   = {Journal of Ambient Intelligence and Humanized Computing},
  year      = {2023},
  doi       = {10.1007/s12652-023-04625-6},
  publisher = {Springer}
}

For any queries, feedback, or collaborations, feel free to contact:
Shanu Verma – sverma@as.iitr.ac.in
