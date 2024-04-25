# HPC-Practicals  [![Views](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fprashantjagtap2909%2FHPC-Practical&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Views&edge_flat=false)](https://hits.seeyoufarm.com)




#### CUDA Installation
- 1. Install CUDA Toolkit:

  Download and install the appropriate CUDA Toolkit for your system from the NVIDIA website: https://developer.nvidia.com/cuda-toolkit
  Follow the installation instructions provided by NVIDIA.
- 2. Configure CUDA Paths:

  - After installation, you'll need to set the environment variables for CUDA include and library paths. These paths typically point to the directories containing cuda.h and other CUDA libraries.

  - The specific steps for setting environment variables depend on your operating system. Here are some general guidelines:

    ##### Windows:
  - Right-click on "This PC" or "My Computer" and select "Properties".
  - Go to "Advanced system settings" -> "Environment Variables".
  - Under "System variables", find the "Path" variable and edit it.
  - Add the paths to your CUDA include directory (e.g., C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.7\include) and the CUDA library directory (e.g., C:\Program Files\NVIDIA GPU       Computing Toolkit\CUDA\v11.7\libnvdiacompute). Separate each path with a semicolon (;).

- 3. Verify Installation:

  - Once you've installed and configured CUDA, try compiling a simple CUDA program to verify if it works. You can use the provided code snippets as a starting point.
