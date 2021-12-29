# Applications

These are the applications I have written.

## Purely Infrastructure

Several of my applications are purely to provide infrastructure for other applications.

[db-backup-service](https://github.com/craigmiller160/db-backup-service) = Regularly backs up specific databases for my applications to a separate hard drive to avoid data loss.

[email-service](https://github.com/craigmiller160/email-service) = Simple micro-service for providing email-sending functionality to other apps.

## Authentication

I have a home-grown authentication system. While for professional projects I would defer to official providers like Okta, it was really fun building this myself. It follows the OAuth2 spec MOSTLY, and it is a highly secure JWT-minting authorization server.

[sso-oauth2-server](https://github.com/craigmiller160/sso-oauth2-server) = The OAuth2 server itself.

[auth-management-service](https://github.com/craigmiller160/auth-management-service) = The backend web service supporting the Admin UI for the OAuth2 server.

[auth-management-ui](https://github.com/craigmiller160/auth-management-ui) = The frontend for the Admin UI for the OAuth2 server.

## VideoManager

This application is used to stream personal content. It's basically a homemade Plex clone that I'm very fond of.

[VideoManagerServer](https://github.com/craigmiller160/VideoManagerServer) = The backend web service supporting this application.

[VideoManagerClient](https://github.com/craigmiller160/VideoManagerClient) = The frontend UI for this application.

## Covid19 Data

I wrote this app early in the pandemic to track COVID metrics. Some of the data sources are no longer running the same way and as time has gone on I haven't maintained it as much as I should.

[covid-19-config-mongo](https://github.com/craigmiller160/covid-19-config-mongo) = Some re-usable code in a library to share between the two micro-services.

[covid-19-api](https://github.com/craigmiller160/covid-19-api) = The backend REST API micro-service supporting the application.

[covid-19-downloader](https://github.com/craigmiller160/covid-19-downloader) = A micro-service that automatically downloads updated COVID 19 data at regular intervals.

[covid-19-client](https://github.com/craigmiller160/covid-19-client) = The frontend UI for this application.

## Funcoast H&I

An application that manages membership records for the Funcoast H&I Committee.

[funcoast-hi-server](https://github.com/craigmiller160/funcoast-hi-server) = The backend REST API for this application.

[funcoast-hi-client](https://github.com/craigmiller160/funcoast-hi-client) = The frontend UI for this application.
