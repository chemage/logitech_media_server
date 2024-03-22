# logitech_media_server
Logitech Media Server Docker Compose for Synology NAS

## Setup

1. Add `lms CNAME nas1` in bind on RPi3.
1. Upload `docker-compose.yml` to Container Manager > Projects (create a new project).
1. Set Web Station as follows:
	1. Hostname: lms.coloc.lan
	1. Port: 80 / 443
