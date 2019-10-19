# minecraft-dns Docker Image

## What is this for
- Redirecting request to your private servers IP address

## Pre-requisites
- IP address of your Minecraft Bedrock server running on the default port

## How to

```
docker run -d -p 53:53 \
	-e SERVER_IP=123.123.123.123
```