# Guía de instalación del environment

### En el anaconda prompt escrubir secuencialmente los siguientes comandos

conda create --name tpn1

conda activate tpn1

conda config  --env --add channels conda-forge

conda config --env --set channel_priority strict

conda install --file requirements.txt

python -m ipykernel install --name tpn1
