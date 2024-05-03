ARG USE_VERSION=3.19
FROM alpine:${USE_VERSION}
RUN apk update && apk add python3 py3-pip
WORKDIR /web_app
COPY . .
RUN pip3 install -r requirements.txt --break-system-packages
ENTRYPOINT [ "python3" ]
CMD [ "app.py" ]