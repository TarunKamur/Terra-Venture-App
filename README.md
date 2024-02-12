## Terra-Venture-App
## First created one aws-ec2-instnace for running as server #

![image](https://github.com/TarunKamur/Terra-Venture-App/assets/152691126/bc44802a-5c39-473a-91a7-a11d27905615)
## Then install git for git opperations & docker for containerization ##

## Writting Dockerfile for building image ##

![root@ip-172-31-39-124_~ 12-02-2024 10 30 00 AM](https://github.com/TarunKamur/Terra-Venture-App/assets/152691126/5b612c47-6ca0-4689-a73e-6a3ad397a911)

## Building image From Dockerfile & creating container from that building image ##

![image](https://github.com/TarunKamur/Terra-Venture-App/assets/152691126/de548b81-fac1-4a0b-bcf1-9a12f3398e8f)


## Building image from Dockerfile command ##
```
 docker build -t img-name:tag . 
```
## Creating container from building img command ##

``` 
docker run -itd --name <cont-name> <img-name:tag>
```
## Deploying application in giving port access ##

![image](https://github.com/TarunKamur/Terra-Venture-App/assets/152691126/3649745d-8652-4fb8-af7d-93b1ece47ce1)

## finally getting the application in web browser ##

![image](https://github.com/TarunKamur/Terra-Venture-App/assets/152691126/c8037499-f68e-426a-990d-73a31b642055)



![image](https://github.com/TarunKamur/Terra-Venture-App/assets/152691126/b98abf47-55fd-44b6-83ff-be2f9f996a22)
