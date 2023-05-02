# lab-antmedia
It is a streaming media broadcasting application aiming to bring some broadcasting protocols
such as RTMP, also being compatible with other streaming platforms like YouTube, Facebook,
Twitch, etc. And it is highly scalable regarding its simple API.

For more info visit [Ant Media GitHub page](https://github.com/ant-media/Ant-Media-Server)


# Running
The official docker hub page of the company has not the most updated version of the App.
For the community edition (CE) there is a highly contributed docker hub image called **nibrev**.

## Deploying using docker / docker compose
See the `docker-compose.yml` file and run `docker compose up`.

## Deploy using K8s
Follow [this](https://github.com/ant-media/Ant-Media-Server/wiki/Getting-Started-with-Ant-Media-Server-Kubernetes)
page of documentation. Instead of the image in the doc use the image of the docker compose file with
the instruction in the file such as `network_mode: host` and `command line` for running ssl.

# Front-end implementation
Use [this Swagger page](https://antmedia.io/rest/) for the streaming APIs.
