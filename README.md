# android-sdk-build-image

## Build an Android project inside a docker container
Execute the following command in the android project directory
```
docker run -v $PWD:/application tomsabel/android-sdk-build-image:28.0.3 sh -c "./gradlew assemble"
```
