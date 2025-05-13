ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="sivakumar reddy" \
    duration="120HRS"
ARG USERNAME=SIVASAIKUMAR
ENV USERNAME=${USERNAME}
RUN echo "Hello this is : ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]