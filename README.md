# role-ansible-semaphore
Role for Ansible semaphore


``
docker-compose logs --follow
``



# Manual Upgrade
- wget https://github.com/semaphoreui/semaphore/releases/download/v2.10.22/semaphore_2.10.22_linux_386.deb
- systemctl stop semaphore ; systemctl status semaphore
- dpkg -i
- systemctl start semaphore ; systemctl status semaphore

v
