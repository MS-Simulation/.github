# MS-Simulation

Home of **TimSim 2.0**, a simulator for LC-IMS-MS proteomics raw data, and the pieces around it.

### Engine (Rust)
- [timsim](https://github.com/MS-Simulation/timsim): engine libraries (acquisition schemes, Parquet schema, chemistry and digest, streaming simulation)
- [mscore](https://github.com/MS-Simulation/mscore): foundation crates (`ms-chem`, `mscore`)
- [timsim-cli](https://github.com/MS-Simulation/timsim-cli): protocol and render command-line tools

### Prediction
- [timsim-predict](https://github.com/MS-Simulation/timsim-predict): CCS, RT and MS2 intensity prediction jobs
- [pepdl](https://github.com/MS-Simulation/pepdl): peptide deep-learning predictors (inference)
- [pepdl-train](https://github.com/MS-Simulation/pepdl-train): training for the pepdl models

### Orchestration and UI
- [timsim-necro](https://github.com/MS-Simulation/timsim-necro): the simulator as a [necroflow](https://github.com/MatteoLacki/necroflow) DAG
- [timsim-gui](https://github.com/MS-Simulation/timsim-gui): Sample & Experiment Designer web GUI
- [timsim-eval](https://github.com/MS-Simulation/timsim-eval): evaluation against ground truth (DIA-NN, Sage, FragPipe)
- [timsim-bench](https://github.com/MS-Simulation/timsim-bench): post-processing of search results on simulated data

### Vendor formats
- [sciexwiff](https://github.com/MS-Simulation/sciexwiff), [sciex-io](https://github.com/MS-Simulation/sciex-io): SCIEX .wiff
- [thermorawfile](https://github.com/MS-Simulation/thermorawfile): Thermo .raw
- [mobilionmbi](https://github.com/MS-Simulation/mobilionmbi): MOBILion .mbi

### Benchmarks
- [PlasmaBENCH](https://github.com/MS-Simulation/PlasmaBENCH): mixed-proteome plasma benchmark
- [SAGEBench](https://github.com/MS-Simulation/SAGEBench): simulated timsTOF fixtures for the Sage search engine
