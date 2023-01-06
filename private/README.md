# Private repository

## How to push an image to Docker Hub as a private one

1. Create a private repository

   https://hub.docker.com/repository/create?namespace=matoruru

1. Build the image

   ```
   # "matoruru" here is my username.
   docker build -t matoruru/private-images:hello-world.latest .
   ```

1. Push the image

   ```
   docker push matoruru/private-images:hello-world.latest
   ```