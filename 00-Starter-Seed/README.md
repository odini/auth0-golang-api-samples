# Auth0 + Go Web API Sample

## Running the App

To run the sample, make sure you have **go** and **goget** installed.

Rename the `.env.example` file to `.env` and provide your Auth0 credentials.

```bash
# .env

AUTH0_CLIENT_ID={CLIENT_ID}
AUTH0_DOMAIN={DOMAN}
AUTH0_CLIENT_SECRET={CLIENT_SECRET}
AUTH0_CALLBACK_URL=http://localhost:3000/callback
```

Once you've set your Auth0 credentials in the `.env` file, run `go get .` to install the Go dependencies.

Run `go run main.go server.go` to start the app and navigate to [http://localhost:3000/](http://localhost:3000/ping)