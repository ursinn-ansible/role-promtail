# Ansible Role - Promtail

[![GitHub last commit](https://img.shields.io/github/last-commit/ursinn-ansible/role-promtail?logo=github&style=for-the-badge)](https://github.com/ursinn-ansible/role-promtail/commits)
[![License](https://img.shields.io/github/license/ursinn-ansible/role-promtail?style=for-the-badge)](https://github.com/ursinn-ansible/role-promtail/blob/main/LICENSE)

Docker Image: https://hub.docker.com/r/grafana/promtail

## Options

| Option | Default Value |
| ---- | ---- |
| system_promtail_docker_volume | promtail_config |
| system_promtail_docker_image | docker.io/grafana/promtail |
| system_promtail_docker_container | promtail |
| system_promtail_docker_network | app-network |
| system_promtail_tmp_dir | /tmp/ansible-role-promtail |
| system_promtail_nginx_docker_image | docker.io/beevelop/nginx-basic-auth |
| system_promtail_nginx_htpasswd | |
| system_promtail_loki_url| |
| system_promtail_loki_username| |
| system_promtail_loki_password | |

## License

This project is under the MIT License. See the [LICENSE](https://github.com/ursinn-ansible/role-promtail/blob/main/LICENSE) file for the full license text.
