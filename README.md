# WITecAgent

Software for AI agents to control a WITec Raman microscope and carry out Raman experiments. The long-term goal is autonomous execution of a complete Raman measurement workflow.

This repository is the starting point for development. It currently contains project documentation only; microscope control and autonomous execution have not yet been implemented here.

## Maintainers

This repository is maintained by Professor Qiaoqiang Gan's research group at King Abdullah University of Science and Technology (KAUST).

The primary project leads are:

- Jiajun Li
- Carlos Hernandez Rodriguez
- Xiaokang Song

## Development direction

Use the existing control code as a reference and design interfaces that an AI agent can invoke programmatically. Instrument control, image recognition, and an optional monitoring UI should remain separable so they can run on different computers when needed.

## Reference repositories

- [WITecControlProject](https://github.com/JunLin615/WITecControlProject): the existing implementation, originally designed for human operation, with separate instrument-control, AI-recognition, and frontend components.
- [RegionSegProject](https://github.com/JunLin615/RegionSegProject): training and visualization scripts for segmentation of color-developed sample regions.
- [Raman_base](https://github.com/JunLin615/Raman_base): shared Raman-processing utilities.

## Contributions

Submit agent-control and experiment-orchestration code to this repository through pull requests. Submit reusable Raman-processing utilities to Raman_base. Include a description of the behavior, setup requirements, and validation performed. Contributions will be reviewed and merged periodically by the maintainer.
