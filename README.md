# FinalProject - Neon Color Illusion:
The project implements the Neon Color Illusion effect by the following steps:

Model process: 

![Modle-schematic](https://github.com/user-attachments/assets/260148a3-2f67-49e1-b2a9-258847ce9074)

Orthogonal Completion Algorithem: 

![Orthogonal complement](https://github.com/user-attachments/assets/4bc3881d-c87f-4d9e-bf30-4dd5995bd9bf)

Diffusion Algorithem:
![DiffusionAlgorithem](https://github.com/user-attachments/assets/0412bd70-2dbb-4bec-8a1e-fea7c44b4626)
The desired solution achived by summing both solutions.

Setup:
This code has been tested with Python 3.10 (on google colab interface).

Clone the repository
git clone --depth=1 https://github.com/FinalProjectEEE/FinalProject && cd FinalProject

Setup python environment
conda create -n randlanet python=3.10
source activate randlanet
pip install -r helper_requirements.txt
sh compile_op.sh
