FROM gookboet/curator:1.1.1

COPY config/ /srv

COPY cronjobs /etc/crontabs/root

# Run curator 
CMD ["/curator/curator", "--config", "/srv/config.yml", "/srv/actionfile.yml"]