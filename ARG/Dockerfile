ARG version
FROM almalinux:${version:-9}
ENV course="devops" \
    duration="120hrs"
ARG student="jana"
ENV student=$student
RUN echo "Hi, Course is: ${course}, duration is: ${duration}, student is: ${student}, version: ${version}"
CMD ["sleep", "1000"]

