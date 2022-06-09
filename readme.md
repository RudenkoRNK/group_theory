# Теория групп

[![GitHub Actions Status](https://github.com/rudenkornk/group_theory/actions/workflows/workflow.yml/badge.svg)](https://github.com/rudenkornk/group_theory/actions)

Конспект [курса МФТИ И. И. Богданова](https://www.youtube.com/playlist?list=PLyBWNG-pZKx6pWlAfPRo2X_kPWyzq1ebj)

## Build
### Option 1: Use docker container with all required packages installed:
```bash
make in_docker TARGET=main
```

### Option 2: Use docker container interactively:
```bash
make group_theory_container
docker attach group_theory_container
make main
```

### Option 3: config your system with provided scripts
Config your system [using provided scripts from docker repo](https://github.com/rudenkornk/docker_latex#3-use-scripts-from-this-repository-to-setup-your-own-system) and run:
```bash
make main
```

