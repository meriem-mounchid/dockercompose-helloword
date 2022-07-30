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
<img width="759" alt="Screen Shot 2022-07-30 at 7 12 34 PM" src="https://user-images.githubusercontent.com/43518207/181936283-6d0e2d02-bc18-472f-ad51-0a445af5812f.png">


Test: `docker ps -a`
<img width="1144" alt="Screen Shot 2022-07-30 at 4 04 45 PM" src="https://user-images.githubusercontent.com/43518207/181920442-9c0c0444-0472-4b11-9dac-4068728f43eb.png">

