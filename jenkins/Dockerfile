from jenkins/jenkins:lts
USER root
RUN  curl -fsSLO https://get.docker.com/builds/Linux/x86_64/docker-17.04.0-ce.tgz \
  && tar xzvf docker-17.04.0-ce.tgz \
  && mv docker/docker /usr/local/bin \
  && rm -r docker docker-17.04.0-ce.tgz

RUN jenkins-plugin-cli --plugins  docker:1.2.9 \
                            ssh-agent:295.v9ca_a_1c7cc3a_a_ \
                            prometheus:2.0.11 \
                            cloudbees-disk-usage-simple:0.10
