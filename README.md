# Fake Customer Database & Credit Card Transactions Generator
Intended to be used to simulate data ingestion scenarios in a bank & build usecases from there

Instructions:
1. Use python3/pip3
2. Install packages from requirements.txt

Note:
1. 01-generate-customerdata.sh will generate fake customer profiles
2. 02-generate-transactions.sh will generate transactions for the customers we have previous generated & based on the customer profiles under fake-cctxn-gen/profiles
3. If required, you can pick the output from the 02-generate-transactions.sh toolkit under /data into a locally installed RabbitMQ instance using 03-stream-to-mq.sh
