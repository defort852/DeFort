Dockerhub repo link: https://hub.docker.com/repository/docker/defort852/defort/general

1.Pull the image and create a container(Please use the platform with arm64 architecture)

2.Go to the /usr/src/app directory

3.Execute command: ./defort -e explore --meta path/to/meta/file --seed path/to/seed/file -o ./output
(eg. ./defort -e explore --meta ./samples/bgld/meta.json --seed ./samples/bgld/seed.json -o ./output)
