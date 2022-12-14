# Blockchain-Project-82787

## Build an Image ##

```docker build -t nci/project82787 .```


## Run an image ##

```docker run --name project82787 -p 8090:8080 project82787```

## To build from existing image created ##

```docker pull abhishekmedhane04/project82787:latest```

## Run an image ##

```docker-compose up -d```

## Check running containers ##

```docker ps```

## Start the containers ##

```docker start container_id```

## Stop the containers ##

```docker stop container_id```

## Run the curl command ##

This transfers ETH:

```curl --header "Content-Type: application/json" --request POST --data '{"address":"0xBaA61D706bE990699beAa36E4373f744A9324968", "amount":"0.05"}' http://localhost:8090/eth```

This transfers token:

```curl --header "Content-Type: application/json" --request POST --data '{"address":"0xBaA61D706bE990699beAa36E4373f744A9324968"}' http://localhost:8090/token```

