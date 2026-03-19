bash <(curl -L https://raw.githubusercontent.com/linlin8866/warpx/main/warp.sh)



bash <(curl -L https://raw.githubusercontent.com/linlin8866/warpx/main/warp.sh) <<< "1"



curl --socks5 127.0.0.1:40000 https://ipinfo.io

一键命令回滚ipv6
systemctl stop wireproxy && \
sed -i "s|Endpoint =.*|Endpoint = engage.cloudflareclient.com:2408|" /etc/wireguard/proxy.conf && \
systemctl restart wireproxy && \
sleep 3 && \
curl --socks5 127.0.0.1:40000 https://ipinfo.io -m 10




systemctl stop wireproxy && \
sed -i "s|Endpoint =.*|Endpoint = engage.cloudflareclient.com:2408|" /etc/wireguard/proxy.conf && \
systemctl restart wireproxy && \
sleep 3 && \
curl --socks5 127.0.0.1:40000 https://ipinfo.io -m 10




systemctl stop wireproxy && \
sed -i "s|Endpoint =.*|Endpoint = engage.cloudflareclient.com:2408|" /etc/wireguard/proxy.conf && \
systemctl restart wireproxy && \
sleep 3 && \
curl --socks5 127.0.0.1:40000 https://ipinfo.io -m 10


一键替换IP

systemctl stop wireproxy && \
sed -i "s|Endpoint =.*|Endpoint = 104.16.180.124:443|" /etc/wireguard/proxy.conf && \
systemctl restart wireproxy && \
sleep 3 && \
curl --socks5 127.0.0.1:40000 https://ipinfo.io -m 10


一键查找命令

systemctl cat wireproxy | grep -E "ExecStart|--config"


打开
nano /etc/wireguard/proxy.conf

重启

systemctl restart wireproxy


验证


systemctl status wireproxy

