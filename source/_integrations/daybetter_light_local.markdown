---
title: DayBetter lights local
description: Instructions on how to integrate DayBetter lights with DayBetter local API
ha_category:
  - light
ha_release: 2025.9
ha_iot_class: Local Push
ha_codeowners:
  - '@THDayBetter'
ha_domain: daybetter_light_local
ha_config_flow: true
ha_platforms:
  - light
ha_integration_type: integration
---

Integrates [DayBetter](https://www.daybetter.com/) lights into Home Assistant using Local API control.


## Supported devices

P076

{% note %}
Some scenes may not be supported from all devices. If you find a scene that's not working with a specific model, please open an issue at the [underling library](https://github.com/THDayBetter/daybetter-local-api/issues)
{% endnote %}
