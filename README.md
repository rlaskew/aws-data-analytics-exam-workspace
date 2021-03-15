# aws-data-analytics-exam-workspace

## TODO: fill in here

### Repo Purpose
+ The Udemy class listed below has a fairly long follow along lab project, so I'd like to be able to not leave all the AWS resources running. This repo is for the cloudformation that will recreate the incremental steps of the lab project, that are otherwise done in the UI by the instructor. The Udemy class in question is a great class and I'd encourace others to buy/take it when preping for this AWS exam

Udemy URL: https://www.udemy.com/course/aws-data-analytics/

### install former2 cli -- https://github.com/iann0036/former2
+ https://github.com/iann0036/former2/blob/master/cli/README.md
+ npm install -g former2
+ former2 generate --output-cloudformation sample-ec2.yml --services EC2 --region us-east-1 --search-filter cloud9
