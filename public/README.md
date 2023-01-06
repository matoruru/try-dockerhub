# Public repository

## How to push to Docker Hub

1. Build the image

   ```
   # "matoruru" here is my username.
   docker build -t matoruru/hello-world .
   ```

1. Push the image

   ```
   docker push matoruru/hello-world:latest
   ```