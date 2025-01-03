"# springboot-docker-demo" 

echo "# springboot-docker-demo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/fusumwan/ordertableweb.git
git push -u origin main

===============================================
git remote add origin https://github.com/fusumwan/ordertableweb.git
git branch -M main
git push -u origin main

=================================================


docker build -t springboot-docker-demo .

provide tag name to image


docker build -t springboot-docker-demo:0.1.RELEASE .



docker run -p 8080:8080 -d springboot-docker-demo

docker images

docker logs -f 77a01728645d008438ed652195c459e9aedb591dc0c668c723ca3fae1b562bcc

docker ps


Clean Up Docker Context: Remove unused Docker images and containers to avoid conflicts:

docker system prune -af

========================================
git pull
git add .
git commit -m "Updating"
git branch -M main
git push -u origin main




=========================================
below is container image url
docker.io/timothyfudocker/springboot-docker-demo:v1.00
