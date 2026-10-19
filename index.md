---
title: Observability Labs
lang: en
slug: index
section: index
order: 0
status: needs-review
upstream: index.md
---
Welcome to the observability labs.

These are hands-on resources to help you learn monitoring, logging and tracing.

## Pre-reqs

 - [Set up Docker and a Git client](setup/README.md) 
 - Download your repo
    - Open a terminal (PowerShell on Windows; any shell on Linux/macOS) 
    - Run: `git clone https://github.com/courselabs/observability.git`
    - Open the folder: `cd observability`
- _Optional_
    -   Install [Visual Studio Code](https://code.visualstudio.com) (free - Windows, macOS and Linux) to browse the repo and documentation

<!-- labs:start -->

## Metrics

Collecting, querying and visualizing metrics.

| Lab | Time | Needs |
|---|---|---|
| [Exporting Metrics](labs/metrics/README.md) | 45 min | docker |
| [Prometheus](labs/prometheus/README.md) | 45 min | docker |
| [Querying Metrics with PromQL](labs/promql/README.md) | 45 min | docker |
| [Grafana](labs/grafana/README.md) | 40 min | docker |
| [Building Grafana Dashboards](labs/grafana-dashboard/README.md) | 45 min | docker |

## Logs

Writing, shipping, storing and searching application logs.

| Lab | Time | Needs |
|---|---|---|
| [Writing Logs](labs/logging/README.md) | 40 min | docker |
| [Running Elasticsearch](labs/elasticsearch/README.md) | 45 min | docker |
| [Collecting Logs with Logstash](labs/logstash/README.md) | 45 min | docker |
| [Kibana](labs/kibana/README.md) | 45 min | docker |
| [Searching with the Query DSL](labs/query-dsl/README.md) | 45 min | docker |
| [Kibana Dashboards](labs/kibana-dashboard/README.md) | 40 min | docker |

## Distributed Tracing

Following a request across services.

| Lab | Time | Needs |
|---|---|---|
| [Application Traces](labs/tracing/README.md) | 45 min | docker |
| [Running Jaeger](labs/jaeger/README.md) | 35 min | docker |
| [Custom Spans](labs/custom-spans/README.md) | 45 min | docker |

## Real World

Using all three signals together to find a problem.

| Lab | Time | Needs |
|---|---|---|
| [Troubleshooting Observability](labs/troubleshooting/README.md) | 50 min | docker |

<!-- labs:end -->

### Credits

Created by [@EltonStoneman](https://twitter.com/EltonStoneman) ([sixeyed](https://github.com/sixeyed)): Freelance Consultant and Trainer. Author of [Learn Docker in a Month of Lunches](https://www.manning.com/books/learn-docker-in-a-month-of-lunches), [Learn Kubernetes in a Month of Lunches](https://www.manning.com/books/learn-kubernetes-in-a-month-of-lunches) and [many Pluralsight courses](https://pluralsight.pxf.io/c/1197078/424552/7490?u=https%3A%2F%2Fwww.pluralsight.com%2Fauthors%2Felton-stoneman).

Photo by <a href="https://unsplash.com/@pawel_czerwinski?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Pawel Czerwinski</a> on <a href="https://unsplash.com/s/photos/surveillance?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

