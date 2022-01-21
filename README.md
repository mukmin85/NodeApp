# How to use : Step - Step

git clone https://github.com/mukmin85/NodeApp.git

docker build . -t mukmin85/nodeapp

docker run -d -p 9090:9090 --name node-app mukmin85/nodeapp

Access URL http://localhost:9090
