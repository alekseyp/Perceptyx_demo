run `vagrant up` to deploy vagrant server with docker containers inside

if you want to run it on real server, you can add server ip / hostname to hosts file and run `ansible-playbook -i hosts playbook.yml`

if you already have docker installed you can simply run `docker-compose up -d`
