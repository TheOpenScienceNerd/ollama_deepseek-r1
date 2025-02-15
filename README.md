[![ORCID: Monks](https://img.shields.io/badge/Tom_Monks_ORCID-0000--0003--2631--4481-brightgreen)](https://orcid.org/0000-0003-2631-4481)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# DeepSeek-R1: research setup for working with Ollama, Python DeepSeek locally.

The materials in this repo provide a example Python code to prompt a local installatio of DeepSeek-R1 using the python package `ollama`

## License

The materials have been made available under an [MIT license](LICENCE).  The materials are as-is with no liability for the author. Please provide credit if you reuse the code in your own work.

## Citation

Please feel free to use or adapt the code for your own work. But if so then a citation would be very much appreciated! 

```bibtex
@software{ollama_deepseekr1,
author = {Monks, Thomas },
license = {MIT},
title = {{@TheOpenScienceNerd: Interacting with DeepSeek-R1 via Python}},
url = {https://github.com/TheOpenScienceNerd/ollama_deepseek-r1}
}
```

## Installation instructions

### Installing dependencies

All dependencies can be found in [`binder/environment.yml`]() and are pulled from conda-forge.  To run the code locally, we recommend installing [miniforge](https://github.com/conda-forge/miniforge);

> miniforge is Free and Open Source Software (FOSS) alternative to Anaconda and miniconda that uses conda-forge as the default channel for packages. It installs both conda and mamba (a drop in replacement for conda) package managers.  We recommend mamba for faster resolving of dependencies and installation of packages. 

navigating your terminal (or cmd prompt) to the directory containing the repo and issuing the following command:

```bash
mamba env create -f environment.yml
```

Activate the mamba environment using the following command:

```bash
mamba activate ollama
```

Run Jupyter-lab

```bash
jupyter-lab
```

## Repo overview

```
.
├── binder
│   └── 
├── callcentresim
│   ├── __init__.py
│   ├── model.py
│   └── output_analysis.py
├── CHANGELOG.md
├── CITATION.cff
├── environment.yml
├── LICENSE
├── prompt_deepseek.ipynb
└── README.md
```

* `environment.yml` - contains the conda environment if you wish to work locally algorithm
* `prompt_deepseek` - main notebook file containing the tutorial code for the interacting with a local deepseek-r1 via python.
* `CHANGES.md` - changelog with record of notable changes to project between versions.
* `CITATION.cff` - citation information for the package.
* `LICENSE` - details of the MIT permissive license of this work.

