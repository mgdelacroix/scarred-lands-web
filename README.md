# Scarred Lands web

## Run the server

To run the server, the first step is to generate the docker image. Just run:

```sh
./scarred-lands build
```

After the image is generated, each time you want to run the interactive server, just run:

```sh
./scarred-lands server
```

You can access the server at [http://localhost:1313](http://localhost:1313)

## Generate the static site

To be able to generate the site, the docker image needs to be built. To generate the site, just run:

```sh
./scarred-lands generate
```

## Publish the static site

Once you've modified any post, if you want to publish the site, you can use

```sh
./scarred-lands publish
```

to generate the static files, commit them to the repository and upload them to the remote
