# cis_benchmarks
CIS Benchmarks as I get around to making them.

## These are meant to be pulled into Ansible Tower or AWX

## Current Benchmark Tests

| Benchmark Name | Yaml to call role| Status | Notes |
| ---------------- | ---------------| --------- | ------------------------------ |
| CIS_apache2.4 | CIS_apache2.4_site.yml | Complete | Run against running apache host |
| CIS_Ubuntu_18.04 | CIS_Ubuntu_18.04_site.yml | In progress | Run against Ubuntu18.04 server |

## Optional Extra Variables to give in your AWX Template

| Variable Name | Description |
| ---------------------- | -------------------------------------- |
| discord_webhook_url | Will cause file to be written out to your Discord server |