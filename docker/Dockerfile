FROM rust
LABEL Name=microservicetutorial Version=0.0.1

WORKDIR /var/www/microservice
COPY . .

RUN rustc --version
RUN cargo install --path .

# CMD [ "microservice" ]
CMD [ "MicroService_Tutorial" ]