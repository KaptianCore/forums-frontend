FROM nginx:alpine
RUN apk add apt-get
RUN apk add --update nodejs
RUN apt-get install -y git
RUN mkdir /home/forums-frontend \      
           cd /home/forums-frontend \        
           git clone https://github.com/KaptianCore/forums-frontend.git
WORKDIR /home/forums-frontend
