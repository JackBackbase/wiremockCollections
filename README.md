# wiremockCollections

## Start wiremock-studio locally (Pay attention to the ports assigned to Mock APIs)

docker run -it \
  --name wiremock-studio \
  -p 9000:9000 \
  -p 8011-8019:8011-8019 \
  -v $PWD/wiremock:/home/wiremock \
  up9inc/wiremock-studio:2.32.0-18

## Access wiremock-studio
http://localhost:9000/

## References
https://wiremock.org/studio/docs/getting-started/docker/
