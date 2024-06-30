# hw05-module4

### 1. Take the standard nginx image and push it to private registry
![alt text](<screenshots/1/Знімок екрана з 2024-06-30 13-31-52.png>)
![alt text](<screenshots/1/Знімок екрана з 2024-06-30 13-32-20.png>)
![alt text](<screenshots/1/Знімок екрана з 2024-06-30 13-32-27.png>)
![alt text](<screenshots/1/Знімок екрана з 2024-06-30 13-36-59.png>)
![alt text](<screenshots/1/Знімок екрана з 2024-06-30 13-39-51.png>)
![alt text](<screenshots/1/Знімок екрана з 2024-06-30 13-40-33.png>)


### 2. Create a secret for accessing private registry with needed creds
![alt text](<screenshots/2/Знімок екрана з 2024-06-30 14-05-45.png>)
![alt text](<screenshots/2/Знімок екрана з 2024-06-30 14-08-51.png>)
![alt text](<screenshots/2/Знімок екрана з 2024-06-30 14-14-52.png>)


### 3. Create a configmap with nginx config file listening on port 8080 instead of 80
![alt text](<screenshots/3/Знімок екрана з 2024-06-30 14-30-53.png>)
![alt text](<screenshots/3/Знімок екрана з 2024-06-30 14-33-16.png>)


### 4. Create a deployment with this private nginx image, registry secret attached and attached config from the configmap
![alt text](<screenshots/4/Знімок екрана з 2024-06-30 14-42-18.png>)
![alt text](<screenshots/4/Знімок екрана з 2024-06-30 14-42-32.png>)
![alt text](<screenshots/4/Знімок екрана з 2024-06-30 14-53-23.png>)
![alt text](<screenshots/4/Знімок екрана з 2024-06-30 14-54-45.png>)
![alt text](<screenshots/4/Знімок екрана з 2024-06-30 14-55-05.png>)
![alt text](<screenshots/4/Знімок екрана з 2024-06-30 14-55-18.png>)