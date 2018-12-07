# Dockerfile with tensorflow support on python3, opencv3.3
FROM tensorflow/tensorflow:1.11.0-py3

RUN apt-get update

# Core linux dependencies. 
RUN apt-get install -y \
        build-essential \
        cmake \
        git \
        wget \
        unzip \
        yasm \
        pkg-config \
        libswscale-dev \
        libtbb2 \
        libtbb-dev \
        libjpeg-dev \
        libpng-dev \
        libtiff-dev \
        libjasper-dev \
        libavformat-dev \
        libhdf5-dev \
        libpq-dev

# Python dependencies
RUN pip3 --no-cache-dir install \
    numpy \
    hdf5storage \
    h5py \
    scipy \
    py3nvml \
    opencv-contrib-python-headless

