# agenst
docker ps -a -q | ForEach-Object { docker stop $_ ; docker rm $_ }
docker run -d -v /var/run/docker.sock:/var/run/docker.sock -e DEVICE_NAME="join to us https://t.me/Io_net_warriors" -e DEVICE_ID=dbb974ce-6544-4762-b871-339c2a7bb16d -e USER_ID=5b4c11dc-eaf2-40d7-9916-a6ca2be23132 -e OPERATING_SYSTEM="Windows" -e USEGPUS=true --pull always ionetcontainers/io-launch:v0.1
