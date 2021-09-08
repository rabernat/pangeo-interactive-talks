FROM pangeo/pangeo-notebook:2021.07.17
RUN echo $(which mamba)
RUN mamba install -n notebook -c conda-forge rise ipytree nbgitpuller==1.0.2
RUN mamba env list
RUN ${NB_PYTHON_PREFIX}/bin/python -m pip install gcm-filters
