# devops

# docker containers sort based on mem usage:
docker stats --no-stream | sort -k 7 -h

cd /var/lib/docker/volumes/img-regitery/_data/docke/registery/v2/repositories