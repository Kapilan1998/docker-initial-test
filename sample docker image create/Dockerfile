# base image as Alpine Linux (a lightweight Linux distribution).
FROM alpine:latest

# command to print "Hello, This is from docker"
CMD ["echo","Hello, This is from docker"]

# Remove a specific image
    # to remove sprecific image, first need to check whether that image is running inside container or not
    # if running inside container,need to stop container. Now this container removed that image and stopped using it.
    # then delete image. Now only able to delete image
            #   docker ps -a
            #   docker rm <CONTAINER_ID>
            #   docker rmi <IMAGE_ID>

# Force Remove the Image & Containers 
    # whether that image is running or not, i don't need to consider. directly delete that image
    # Even after deleting the image, any container that previously used it will still exist and continue running.
    # However, instead of displaying the image name, the container will now show the corresponding image ID.
             #   docker rmi -f <IMAGE_ID>
