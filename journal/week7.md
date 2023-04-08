# Week 7 — Solving CORS with a Load Balancer and Custom Domain

export AWS_ACCOUNT_ID="1234567890"
gp env AWS_ACCOUNT_ID="1234567890"

export HONEYCOMB_API_KEY="LOLHONEYCOMB"
gp env HONEYCOMB_API_KEY="LOLHONEYCOMB"

export OTEL_EXPORTER_OTLP_HEADERS="x-honeycomb-team=${HONEYCOMB_API_KEY}"
echo $OTEL_EXPORTER_OTLP_HEADERS

$PROD_CONNECTION_URL is not set

aws iam create-role --role-name CruddurServiceExecutionRole --assume-role-policy-document file://aws/policies/service-assume-role-execution-policy.json

aws iam put-role-policy --policy-name CruddurServiceExecutionPolicy --role-name CruddurServiceExecutionRole --policy-document file://aws/policies/service-execution-policy.json

https://github.com/omenking/aws-bootcamp-cruddur-2023/blob/week-6-fargate/aws/json/service-backend-flask.json