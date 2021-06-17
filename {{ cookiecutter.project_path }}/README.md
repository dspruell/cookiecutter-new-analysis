```
## Analysis:   {{ cookiecutter.project_name }}
## Created by: {{ cookiecutter.username }}
## Date:       {% now 'local', '%Y-%m-%d %H:%M:%S %Z' %}

```

## Summary


## Observations

{%+ if cookiecutter.analysis_type == 'malicious_traffic_distribution' %}
Malicious traffic distribution details:

```
request:
  method:
  uri_patterns:
    - 
response:
  status:
  content_samples:
  cookies:
    - 
  payload:
    - 
  tokens:
    - 
traffic:
  tds: (hosting TDS if known (e.g. Keitaro, Sutra, BossTDS))
  upstream:
    - type of traffic
  downstream:
    - type of threats
infrastructure:
  hosting:
    - AS#### | CC | AS-NAME AS Decription
  ns:
    - =domain   # if NS in same domain
    - example.com
  registrar:
    - Example LTD
  registrant:
    - Privacy usage
    - Domain shadowing: XXX
    - Dynamic DNS: XXX
    - Name Email
```
{% endif %}

## Analysis notes

