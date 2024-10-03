# Biocopilot

**Biocopilot** is a GenAI application with an intuitive interface designed to support biomedical research. This project leverages advanced AI technologies and high-performance computing to streamline bioinformatics workflows and enhance data analysis capabilities.

## Features

### LLM Integration
- Enhanced query handling for improved user interactions.
- Streamlined processing of user requests.

### LlamaIndex Vector Database
- Implemented agentic functionality for Retrieval-Augmented Generation (RAG).
- Enables efficient searches across web and local databases.

### High-Performance Computing Interface
- Seamless integration with high-performance computing clusters.
- Efficient analysis of gigabyte-scale bioinformatic datasets.

### Python Automation and Data Visualization
- Automated research processes.
- Custom tools for generating gene reports.
- Advanced plotting capabilities for enhanced data visualization.

## Technical Details

Biocopilot is built using Python and incorporates several key libraries and technologies:

- **PyQt5**: For creating the graphical user interface.
- **rpy2**: Enables integration with R for statistical computing and graphics.
- **paramiko**: Facilitates SSH connections for remote server interactions.
- **pandas**: For data manipulation and analysis.
- **numpy**: Supports numerical computing operations.
- **matplotlib**: Likely used for creating plots and visualizations.

The application also integrates with various R packages, including:
- Seurat
- dplyr
- ggplot2
- EnhancedVolcano
- clusterProfiler
- org.Hs.eg.db

## Getting Started

To run Biocopilot, ensure you have Python 3.11 or 3.12 installed, along with the required dependencies. You can set up the environment using Conda:

```python
conda create -n biocopilot python=3.11
conda activate biocopilot
pip install PyQt5 rpy2 numpy pandas jupyter pexpect Pillow reportlab
```


For R integration, ensure R is installed on your system and install the required R packages within the R environment.

## Usage

The main application class LLMApp initializes the user interface and sets up the core functionality. Key features include:
- File browsing and management
- Server login and file transfer capabilities
- Integrated terminal for command execution
- Chat interface for interacting with the AI assistant
- Result display area for code output and progress reports
- Image visualization for plots and graphs


## Paper Reference

This project is based on research presented in the following preprint:
[Biocopilot: A GenAI Application to Support Biomedical Research](https://www.biorxiv.org/content/10.1101/2024.08.15.607673v1)