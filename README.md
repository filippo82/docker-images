# docker-images
My collection of Docker images built and pushed with GitHub actions



### Google Cloud Artifact Registry

From a VM inside project $PROJECT_ID:

```bash
docker pull filippo82/fastapi_basic:latest
docker tag filippo82/fastapi_basic:latest $ARTIFACT_REGISTRY/$PROJECT_ID/docker-images/fastapi_basic:latest
docker push $ARTIFACT_REGISTRY/$PROJECT_ID/docker-images/fastapi_basic:latest
```
