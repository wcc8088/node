# node

1. Install node
- $> sudo apt install node

2. Download source
- $> git clone https://github.com/wcc8088/node.git

3. Create container
- $> cd node
- $> sudo podman build -t nodejs .

4. Run container
- $> sudo podman run -dt -p 8080:8080/tcp nodejs
