### Expressjs Demo

You can build and run the Docker image:

```sh
$ docker build --file ./Dockerfile -t my-nodejs-app .

$ docker run -d -p 3000:3000 my-nodejs-app
```

Then, load http://localhost:3000/ in a browser to see the output.

