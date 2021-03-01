FROM alpine
RUN apk --no-cache add curl
RUN wget busybox-extras
RUN wget netcat-openbsd
RUN wget python py-pip bash
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null