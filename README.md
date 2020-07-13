# RedBot Docker
Basic image to run **Node-RED** + **RedBot**.
It basically installs the packages `node-red-contrib-chatbot` and `node-red-contrib-chatbot-mission-control`

To run the image

```
docker run -it --env -p 1880:1880 -p 1942:1942 -p 1943:1943 --rm --name redbot guidone/redbot
```

## Dockerize a RedBot project

TBC 