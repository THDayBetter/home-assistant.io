---
title: "DayBetter Services"
description: "Instructions on how to integrate DayBetter Services into Home Assistant."
ha_category:
  - Sensor
ha_release: "2025.1"
ha_iot_class: Cloud Polling
ha_codeowners:
  - "@THDayBetter"
ha_domain: daybetter_services
ha_integration_type: service
---

The DayBetter Services integration allows you to monitor temperature and humidity sensors from DayBetter devices in Home Assistant.

## Configuration

This integration is configured via the Home Assistant UI.

1. Go to **Settings** > **Devices & Services**.
2. Click **Add Integration**.
3. Search for **DayBetter Services**.
4. Enter your DayBetter user code (available on the **Me** page in the DayBetter app).
5. The integration will automatically discover and add your devices.

{% include integrations/config_flow.md %}

## Sensors

The integration provides the following sensors for each device:

- **Temperature**: Current temperature reading
- **Humidity**: Current humidity reading  
- **Battery**: Battery level reading  

## Reauthentication

If your authentication expires, you will be prompted to reauthenticate. Simply enter your DayBetter user code again when prompted.