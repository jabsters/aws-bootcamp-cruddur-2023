# Week 4 — Postgres and RDS

* watched Ashish's video on RDS security considerations and finished the quiz related to it
* watched the two-hour Saturday live stream and completed the same activites with Andrew with all the postgres scripts
* watched the video where Andrew installed PostGres drivers in the backend application
* connected Gitpod to the RDS instance
  * I followed the steps exactly regarding the VPC and security groups (wow, that was rough)
  * the script that automatically updates the IP address is cool!
* watched the video where Andrew created Cognito triggers to insert the user into the database
* watched the video where POSTing to activites saved it to the db

=============

Scratch pad of notes, so I don't forget

Environment variables
> export CONNECTION_URL="postgresql://postgres:password@127.0.0.1:5432/cruddur"
> 
> gp env CONNECTION_URL="postgresql://postgres:password@127.0.0.1:5432/cruddur"

> export PROD_CONNECTION_URL="postgresql://root:IFORGOTLOL@RDS-URL.amazonaws.com:5432/cruddur"
>
> gp env PROD_CONNECTION_URL="postgresql://root:IFORGOTLOL@RDS-URL.amazonaws.com:5432/cruddur"

> export DB_SG_ID="sg-abc"
> 
> gp env DB_SG_ID="sg-abc"
> 
> export DB_SG_RULE_ID="sgr-def"
> 
> gp env DB_SG_RULE_ID="sgr-def"

Lambda layer for US-west-2 `arn:aws:lambda:us-west-2:898466741470:layer:psycopg2-py38:1`
