ARG ARCH
FROM ${ARCH}alpine:3.17.1
ARG TARGETPLATFORM
ARG BUILDPLATFORM
ENV TARGETPATH=${TARGETPLATFORM:-"."}
COPY bin/$TARGETPATH/webhook-receiver /webhook-receiver
CMD ["/webhook-receiver"]
