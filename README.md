# [siaimes/pytorch](https://github.com/siaimes/pytorch): Build ready-to-use pytorch docker images.

## released images

[https://hub.docker.com/repository/docker/siaimes/pytorch/tags](https://hub.docker.com/repository/docker/siaimes/pytorch/tags)

## Customization

1. Fork this project to your own GitHub account.
2. Add the following secrets: `REGISTRY_REPONAME`, `REGISTRY_USERNAME`, `REGISTRY_PASSWORD`.
3. Add the packages you need to `apt-get install`, `conda install` or `pip install` commands in the branch that corresponds to the PyTorch version. Afterwards, navigate to `Actions` tab to review the log;
4. If there are no errors when executing the actions, proceed to release a version based on this branch. Then, visit the `Actions` tab to access the log and DockerHub to examine the associated tags.
