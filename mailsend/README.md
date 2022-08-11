# Instructions

## 1. Install Dependency
go get -u google.golang.org/api/gmail/v1
go get -u golang.org/x/oauth2/google


## 2. Download Credentials
Goto  https://console.cloud.google.com/apis/credentials and find appropriate oauth2.0 client and download the credential. store it as credentials.json


## 3. Get permission for your account
goto oauth 2.0 playground https://developers.google.com/oauthplayground

in the select api, select `https://www.googleapis.com/auth/gmail.send`
top right on settings icon, click and in oauth config, paste the client id and client secret.

Generate api token


## 4. Running 
`go run send.go` 
on the terminal it will prompt for access token, paste the token generated from above step
