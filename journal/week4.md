# Week 4 — Postgres and RDS

Environment variables
export CONNECTION_URL="postgresql://postgres:password@127.0.0.1:5432/cruddur"
gp env CONNECTION_URL="postgresql://postgres:password@127.0.0.1:5432/cruddur"

export PROD_CONNECTION_URL="postgresql://root:IFORGOTLOL@RDS-URL.amazonaws.com:5432/cruddur"
gp env PROD_CONNECTION_URL="postgresql://root:IFORGOTLOL@RDS-URL.amazonaws.com:5432/cruddur"

export DB_SG_ID="sg-abc"
gp env DB_SG_ID="sg-abc"
export DB_SG_RULE_ID="sgr-def"
gp env DB_SG_RULE_ID="sgr-def"