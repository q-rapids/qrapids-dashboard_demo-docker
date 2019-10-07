# Q-Rapids Dashboard demo docker

Standalone version of the Q-Rapids Dashboard's demo docker.

## Pre-requisites

In order to run the dashboard demo docker, you need to have install Docker Engine and Docker-compose (https://docs.docker.com/).

## How to deploy dashboard demo docker

It's as simple as...
* **Step 1**. Unzip the zip file in the [release page](https://github.com/q-rapids/qrapids-dashboarddemo-docker/releases/tag/v1-standalone)
* **Step 2**. Open a command prompt on the unzipped root directory
* **Step 3**. Type "docker-compose up". This command can take some minutes the first time is executed.

## How to use Q-Rapids Dashboard

Access to the dashoard in your browser at: http://localhost:8888

The Q-Rapids Dashboard user's guideline is available at [Q-Rapids Strategic Dashboard User Guide](https://github.com/q-rapids/qrapids-dashboard/wiki/User-Guide).

## Dashboard Components' Ports

Q-Rapids Dashboard demo docker uses the following ports:
* Dashboard (WEB_PORT): 8888
* Postgreql (DB_PORT: 5433
* R Serve (RB_PORT): 6311
* Elastic (EL_PORT_REST): 9200
* Elastic (EL_PORT_NODE): 9300
* Kibana (KIBANA_PORT): 5601
* Kafka (KAFKA_PORT): 9092

You can configure them in the .env file in the unzipped root directory before runing the docker-compose statement.

