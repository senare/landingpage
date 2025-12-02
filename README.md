# landingpage


docker run -it --rm \
-p 0.0.0.0:8080:8080 \
-v $(pwd)/landing/cfg:/cfg:ro \
landing:latest

