ARG version
FROM almalinux:${version:-8}
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
# If we give any value, it will be ccess at buildtime only.If we want access in container, we have to create ENV
RUN echo "Course: ${COURSE}, Trainer: ${TRAINER}, Version: ${version}"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
CMD ["sleep","100"]