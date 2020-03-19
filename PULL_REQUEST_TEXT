# My CI/CD Ready Repo

## Roles can be installed with:

  # Future this will be `install linuxfoundation.ci`
  #  which will contain all the other roles as dependencies
  #  and may be done as a post-run script for cookiecutter
  ansible-galaxy install -r requirements.yml --roles-path roles

## Individual roles can be tested with the following command:

  # In the future this will be molecule, or an ansible specific runner
  docker run --rm -it \
  -v $PWD:/app \
  -w /app \
  -e ANSIBLE_STDOUT_CALLBACK=unixy \
  -e WORKSPACE=/app \
  williamyeh/ansible:alpine3 \
  ansible-playbook -c local .playbooks/verify.yml





# Java Toolchain

## Environment

- MAVEN_RELEASE_REPO_URL
  URL of the release repository

- MAVEN_RELEASE_REPO_USER
  Username for the release repository

- MAVEN_RELEASE_REPO_PASS
  Password for the release repository

- MAVEN_RELEASE_REPO
  Nmae of the release repository

- MAVEN_SNAPSHOT_REPO_URL
  URL of the snapshot repository

- MAVEN_SNAPSHOT_REPO_USER
  Username for the snapshot repository

- MAVEN_SNAPSHOT_REPO_PASS
  Password for the snapshot repository

- MAVEN_SNAPSHOT_REPO
  Nmae of the snapshot repository





