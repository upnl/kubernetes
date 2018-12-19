```sh
sudo git clone https://github.com/upnl/swarm.git /srv/swarm

sudo docker swarm init
sudo docker stack deploy -c /srv/swarm/gitlab.yml gitlab
```
