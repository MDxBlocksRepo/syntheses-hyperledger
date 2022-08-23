Installation Steps
------------------

git clone https://github.com/mdxblock/hyperledger

cd hyperledger

sudo su

chmod +x *.sh

chmod +x artifacts/channel/*.sh


./prerequisites.sh

Start Duplication session

sudo su

Add the following paths to /root/.bashrc

export PATH=$PATH:/usr/local/go/bin

export PATH=$PATH:<PATH OF >/fabric-samples/bin

nvm install v16.17.0

>node --version
 
v16.17.0

 
>go version
 
go version go1.13.15 linux/amd64

 
 
#docker version
Client: Docker Engine - Community
 Version:           20.10.17

#docker-compose version
docker-compose version 1.17.1, build unknown


cd artifacts/channel
 
./create-artifacts.sh


cd ../..
./start.sh







