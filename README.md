# docker ubuntu 1804 bionic ansible

## build
docker image build -t bentul/ubuntu18-ansible .

## run
docker container run bentul/ubuntu18-ansible ansible --version
