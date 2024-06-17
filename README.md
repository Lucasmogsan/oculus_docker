# Template for running ROS 2 projects in docker containers

Clone the repo with submodules:
```bash
git clone --recursive git@github.com:Lucasmogsan/ROS2_docker_template.git
```

Alternatively clone the repo and then get the submodules afterwards:

```bash
git clone git@github.com:Lucasmogsan/ROS2_docker_template.git
```

```bash
git submodule update --init --recursive
```


The main repo has references to the submodules. If these submodules are modified, then the main repo may need to update these references in order to pull the latest data.
```bash
git submodule update --remote
```

This modifies the references in the main repo, and these changes needs to be comitted and pushed.