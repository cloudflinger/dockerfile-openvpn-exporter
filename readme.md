# Openvpn-exporter

This dockerfile has a prometheus exporter for openvpn installed. It reads a file output by openvpn

## Releasing a new version

* Make the code changes
* Bump `VERSION`
* run `./release.sh` on a machine authorized to push images to the dockerhub repository

## How are certs generated?

The tools are in the image but the process is outside of the scope of this repository. See the code for deploying this dockerfile in kubernetes.
