FROM alpine
RUN apk --no-cache add curl
RUN apk add -u busybox
RUN apk add -u netcat-openbsd
RUN apk add -u python py-pip bash
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null