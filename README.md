# Ansible Role - Promtail

[![GitHub last commit](https://img.shields.io/github/last-commit/ursinn-ansible/role-promtail?logo=github&style=for-the-badge)](https://github.com/ursinn-ansible/role-promtail/commits)
[![License](https://img.shields.io/github/license/ursinn-ansible/role-promtail?style=for-the-badge)](https://github.com/ursinn-ansible/role-promtail/blob/main/LICENSE)

Docker Image: https://hub.docker.com/r/grafana/promtail

## Options

| Option | Default Value |
| ---- | ---- |
| role_promtail_docker_image | docker.io/grafana/promtail |
| role_promtail_docker_container | promtail |
| role_promtail_docker_volume | promtail |
| role_promtail_docker_network | app-network |
| role_promtail_tmp_dir | /tmp/ansible-role-promtail |
| role_promtail_loki_url| |
| role_promtail_loki_username| |
| role_promtail_loki_password | |

## License

This project is under the MIT License. See the [LICENSE](https://github.com/ursinn-ansible/role-promtail/blob/main/LICENSE) file for the full license text.
