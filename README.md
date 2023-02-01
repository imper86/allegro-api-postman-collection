# allegro-api-postman-collection
Postman collection for Allegro.pl REST API

## Usage
1. Import json files in Postman
1. Select proper environment and change your `client_id` and `client_secret`
1. You should authorize now, so look for **Oauth device start** request and send it
1. Follow the link under `verification_uri_complete` and confirm everything on allegro.pl
1. Open **Oauth device get token** request and send it
1. You're good to go
1. In case of expired access token, you can refresh it using **Oauth refresh token** request
