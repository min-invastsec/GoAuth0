# Auth0 - Go Web App

This sample demonstrates how to add authentication to a Go web app using Auth0.

## Requirements
* [Docker](https://docs.docker.com/)

### Docker Images
* [golang:1.9-alpine3.7](https://hub.docker.com/_/golang/)

### Go Packages
* [gorilla/mux - URL router and dispatcher](https://github.com/gorilla/mux)
* [gorilla/sessions - cookie and filesystem sessions](https://github.com/gorilla/sessions)
* [codegangsta/negroni - HTTP middleware](https://github.com/codegangsta/negroni)
* [joho/godotenv - Go port of Ruby's dotenv library](https://github.com/joho/godotenv)]
* [oauths - OAuth2 support](https://golang.org/x/oauth2)]

## Run
* Replace .env.example with .env with valid client ID and client secret
* `./exec.sh` for Linux
* `Powershell.exe ./exec.ps1` for Windows
* access http://localhost:3000

## License
This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
