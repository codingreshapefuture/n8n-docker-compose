# n8n-docker-compose

Link video: https://youtu.be/liW_lyBcD3w

## Hướng dẫn

N8n self-host docker và public domain:

dùng cá nhân/test:

VM/server/pc/laptop: dựng n8n (hoặc thuê VPS thì đã public luôn)

docker: ảo hóa và tạo n8n nhanh chóng

apt update
apt install docker.io docker-compose nano -y

Tham khảo cách quản lý ubuntu: https://youtu.be/xfT2gqwHyO0?si=E-pv6HtgLvDI9dOT

Build n8n:
https://github.com/codingreshapefuture/n8n-docker-compose

---

dùng public/production:

domain: nếu muốn public internet -> nếu không cần public thì ko cần cái này

cloudflare -> expose n8n ra Internet mà không cần mở port

Tham khảo cách quản lý cloudflare: https://youtu.be/_ry_MAvZXt4?si=dhhcr56DRg9_1pHZ

