# Docker image build using Jenkins CI/CD pipeline

Watch this tutorial https://www.youtube.com/watch?v=z32yzy4TrKM

Install plugin: docker pipeline

watch this video to intstall docker on ubuntu: https://www.youtube.com/watch?v=QKHqyRZV6Vk

If there is any error:
Got permission denied while trying to connect to the Docker daemon socket at unix:///var/run/docker.sock: Post http://%2Fvar%2Frun%2Fdocker.sock/v1.40/auth: dial unix /var/run/docker.sock: connect: permission denied

try this command on the terminal:
sudo chmod 666 /var/run/docker.sock

or else you can check:https://www.digitalocean.com/community/questions/how-to-fix-docker-got-permission-denied-while-trying-to-connect-to-the-docker-daemon-socket
