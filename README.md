# docker_installation
docker/docker-install
Home of the script that lives at get.docker.com and test.docker.com!

The purpose of the install script is for a convenience for quickly installing the latest Docker-CE releases on the supported linux distros. It is not recommended to depend on this script for deployment to production systems. For more thorough instructions for installing on the supported distros, see the install instructions.

This repository is solely maintained by Docker, Inc.

Usage:From https://get.docker.com:

curl -fsSL get.docker.com -o get-docker.sh

sh get-docker.sh
From https://test.docker.com:

curl -fsSL test.docker.com -o test-docker.sh

sh test-docker.sh
From the source repo (This will install latest from the test channel):

sh install.sh

Testing:
To verify that the install script works amongst the supported operating systems run:

make check

Legal
Brought to you courtesy of our legal counsel. For more context, please see the NOTICE document in this repo.
out in the future.

Licensing
docker/docker-install is licensed under the Apache License, Version 2.0. See LICENSE for the full license text.
