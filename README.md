# docker-gitlab
install gitlab with docker compose

# docker 실행후 패스워드 확인
docker exec -it gitlab grep 'Password:' /etc/gitlab/initial_root_password
