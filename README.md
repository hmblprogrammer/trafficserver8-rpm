apache-traffic-server-rpm
=========================

Gitlab automation to build an [Apache Traffic Server](https://trafficserver.apache.org/) 8.x
RPM with prefix /opt/trafficserver for Amazon Linux 2 using
[p21jgitlin/ats-builder:latest](https://hub.docker.com/repository/docker/p21jgitlin/ats-builder)

## Setup

This repo is meant to be used within a GitLab CI pipeline. See `.gitlab-ci.yml`
for details

## TODOs

 * Add CircleCI pipelines to make more useful for users without a GitLab pipeline
 * Publish the built RPMs to GitHub and Artifactory

## License
MIT
