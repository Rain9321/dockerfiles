ARG version 
FROM almalinux:${version:-8}
# ARG variable before FROM will not work after FROM
# ARG version
# RUN echo "version passed by the user is: ${version}"
ARG COURSE
ARG TRAINER
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
RUN echo "Course is: ${COURSE}, trainer is: ${TRAINER} "
