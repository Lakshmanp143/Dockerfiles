# FROM almalinux:9
# ENV course="Devops with AWS" \
#     duration="120hrs" \
#     trainer="Siva"
# RUN echo "hello ${trainer}" > /tmp/Devops.txt
# CMD ["sleep", "100"]

ARG version
FROM almalinux:${version:-9}
ENV course="Devops with AWS" \
    duration="120hrs" \
    trainer="Siva"
ARG USERNAME=Lakshman
ENV USERNAME=$USERNAME
RUN echo "hello user: ${USERNAME}, image version: ${version}"  > /tmp/Devops.txt
CMD ["sleep", "100"]