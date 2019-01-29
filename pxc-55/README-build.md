Build image

  `docker build -t perconalab/percona-xtradb-cluster Dockerfile`

or

  `docker build --build-arg PXC_VERSION=5.5.41 -t perconalab/percona-xtradb-cluster Dockerfile`

Tag image
  
  `docker tag <NNNNN> perconalab/percona-xtradb-cluster:5.5`

Push to hub

  `docker push perconalab/percona-xtradb-cluster:5.5`
  
Usage
=====

