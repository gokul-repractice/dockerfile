FROM almalinux:8
RUN adduser gokul
# To run this command, we should have root access
USER gokul
# If we use USER, before CMD, atlease, we will not have root access
CMD ["sleep", "100"]
# If we run this in the container, it will sleep for 100 seconds  and will exit