# mongodb-replica-set
MongoDb Replica Set with Docker Compose

# how to install
- Clone this repository
- Go to directory of docker-compose.yml file
- Run command from Terminal
``` 
docker-compose up
```


# how to connect

- from same network in Docker host
```
mongodb://mongo1,mongo2,mongo3
```
- from outside of Docker Host
- add ``` 127.0.0.1 mongo1 mongo2 mongo3 ``` to your etc/host file!
```
mongodb://localhost:27017,localhost:27018,localhost:27019
```


# LICENSE

MIT License

Copyright (c) 2021 Ali Güzel

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
