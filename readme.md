# Теория групп

[![GitHub Actions Status](https://github.com/rudenkornk/group_theory/actions/workflows/workflow.yml/badge.svg)](https://github.com/rudenkornk/group_theory/actions)

Конспект [курса МФТИ И. И. Богданова](https://www.youtube.com/playlist?list=PLyBWNG-pZKx6pWlAfPRo2X_kPWyzq1ebj)

## Build
Install drawio using steps from github workflow and run
```shell
python3 compile_images.py
```

Install texlive or use docker image (also from github workflow)
```shell
latexmk
```

docker command for local build:

```shell
sudo docker run  -it --volume <project_source>:<mount_point> ghcr.io/xu-cheng/texlive-full:latest  bash
```

