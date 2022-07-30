# Docker-Compose Hello World

Create a new directory: `mkdir hello–world`

Move into the previously created directory: `cd hello–world`

Create a YAML configuration file: `touch docker-compose.yaml`

Add the following content to the YAML file:
```
version: '3.3'
services:
   hello-world:
      image:
         hello-world:latest
```
Launch the command: `docker-compose up`

<img width="802" alt="Screen Shot 2022-07-30 at 3 51 14 PM" src="https://user-images.githubusercontent.com/43518207/181920397-909ca338-37be-4283-99d7-9ad253615be5.png">

Test: `docker ps -a`
<img width="1144" alt="Screen Shot 2022-07-30 at 4 04 45 PM" src="https://user-images.githubusercontent.com/43518207/181920442-9c0c0444-0472-4b11-9dac-4068728f43eb.png">

