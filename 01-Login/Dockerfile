FROM golang:1.9-alpine3.7

# install git
RUN apk --update add \
	git openssl \
	&& rm /var/cache/apk/*

# Set apps working directory
WORKDIR /go/src

ADD . /go/src

# get go dependency
RUN echo "Installing Go dependencies ..."
RUN go get -d github.com/gorilla/mux
RUN go get -d github.com/gorilla/sessions
RUN go get -d github.com/joho/godotenv
RUN go get -d github.com/codegangsta/negroni
RUN go get -d golang.org/x/oauth2

CMD ["go", "run", "main.go", "server.go"]

EXPOSE 3000
