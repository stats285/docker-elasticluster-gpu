# stats285/elasticluster_gpu

This is a Docker image ( Dockerfile on [GitHub](https://github.com/stats285/docker-elasticluster-gpu) ) for elasticluster that has GPU functionalities. i.e., to build SLURM clusters with GPU accelarators on the cloud and requesting them using `--gres`.

written for **STATS 285** course at Stanford.
You can pull already built docker image by:

  `docker pull stats285/elasticluster_gpu`

You can create a container from this image by:

  `docker run -v ~/.ssh:/root/.ssh -P -it stats285/elasticluster_gpu`

Author: Hatef Monajemi (monajemi AT stanford DOT edu)

Date  : 20 NOV 2017

