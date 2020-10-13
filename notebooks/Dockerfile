FROM jupyter/base-notebook #imagen base de docker.hub

USER jovyan

# Install Tensorflow
RUN conda install --quiet --yes \    
    'pandas' \
    'pandas-gbq' --channel conda-forge
    