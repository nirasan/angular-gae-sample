# App Engine Angular sample

this application is sample of angular application to deploy to google app engine.

## Setup

install [App Engine SDK](https://cloud.google.com/appengine/downloads)

## Run Angular development server

`ng serve`

## Build

`npm run-script build:gae`

## Run App Engine development server

```
cd gae
goapp serve
```


## Deploy

```
cd gae
gcloud app deploy app.yaml --project [PROJECT_ID] -v [VERSION]
```

