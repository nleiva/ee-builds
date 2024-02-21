# Build Execution Environments with `ansible-builder`

OLD ACCOUNT: [![Cloud EE](https://github.com/nleiva/ee-builds/actions/workflows/ee-cloud-image.yml/badge.svg)](https://github.com/nleiva/ee-builds/actions/workflows/ee-cloud-image.yml) [![Controller EE](https://github.com/nleiva/ee-builds/actions/workflows/ee-controller-image.yml/badge.svg)](https://github.com/nleiva/ee-builds/actions/workflows/ee-controller-image.yml) [![General EE](https://github.com/nleiva/ee-builds/actions/workflows/ee-general-image.yml/badge.svg)](https://github.com/nleiva/ee-builds/actions/workflows/ee-general-image.yml) [![Network EE](https://github.com/nleiva/ee-builds/actions/workflows/ee-network-image.yml/badge.svg)](https://github.com/nleiva/ee-builds/actions/workflows/ee-network-image.yml) [![Network Community EE build](https://github.com/nleiva/ee-builds/actions/workflows/ee-network-community.yml/badge.svg)](https://github.com/nleiva/ee-builds/actions/workflows/ee-network-community.yml) [![Security EE build](https://github.com/nleiva/ee-builds/actions/workflows/ee-security-image.yml/badge.svg)](https://github.com/nleiva/ee-builds/actions/workflows/ee-security-image.yml) [![Web EE](https://github.com/nleiva/ee-builds/actions/workflows/ee-web-image.yml/badge.svg)](https://github.com/nleiva/ee-builds/actions/workflows/ee-web-image.yml)

NEW ACCOUNT: [![Docker Repository on Quay](https://quay.io/repository/nleiva2/ee-general-community/status "Docker Repository on Quay")](https://quay.io/repository/nleiva2/ee-general-community)

## Inspect an Image

```bash
podman run -it quay.io/nleiva/ee-general-image /bin/bash
```

## Documentation
- [Ansible Links](https://github.com/nleiva/ansible-links)
- [Automating execution environment image builds with GitHub Actions](https://www.ansible.com/blog/automating-execution-environment-image-builds-with-github-actions)

### Ansible projects
- [ansible-navigator](https://github.com/ansible/ansible-navigator)
- [ansible-builder](https://github.com/ansible/ansible-builder)

### GitHub Actions
- [GitHub Actions quickstart](https://docs.github.com/en/actions/quickstart)
- [GitHub Environments](https://docs.github.com/en/actions/deployment/using-environments-for-deployment)
- [redhat-actions/podman-login](https://github.com/redhat-actions/podman-login)
- [redhat-actions/push-to-registry](https://github.com/redhat-actions/push-to-registry)
