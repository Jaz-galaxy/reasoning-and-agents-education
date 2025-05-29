# Demo Notebooks

## Important Setup Requirements

⚠️ **The demo notebooks in this folder require a separate virtual environment from the main repository.**

### Why a separate environment?

The demo notebooks use **vLLM** which:
- Must be run with **NVIDIA GPU** support
- Has different dependency requirements that may conflict with the main repository's environment

### Setup Instructions

1. **Copy this demo folder to a separate location** on your system (outside of this repository)
2. Create a new virtual environment specifically for these demos in the copied location
3. Use the provided `.toml` file in the demo folder to set up the environment with the correct dependencies
4. Ensure you have access to an NVIDIA GPU before running the notebooks

### Running the Demos

Make sure to activate the demo-specific virtual environment before launching Jupyter and running either of the two demo notebooks in this folder.

> **Note**: Ensure that your NVIDIA drivers and CUDA toolkit are properly installed and configured in your virtual environment to leverage GPU acceleration.
