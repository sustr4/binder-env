FROM quay.io/jupyter/base-notebook:latest

COPY environment.yml /tmp/environment.yml

RUN conda env update --name base --file /tmp/environment.yml && \
    conda clean --all --yes

