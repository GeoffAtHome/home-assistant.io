---
title: Rheem EcoNET Water Products
description: Instructions on how to integrate Rheem EcoNet water heaters into Home Assistant.
ha_category:
  - Water Heater
ha_release: 0.61
ha_iot_class: Cloud Push
ha_domain: econet
ha_codeowners:
  - '@w1ll1am23'
  - '@vangorra'
ha_config_flow: true
---

The `econet` water heater platform is consuming the information provided by a [EcoNet enabled Rheem water heater](https://www.rheem.com/EcoNet/Home). This platform allows you to set the temperature, the operation mode, and away mode. It also provides access to several device sensors depending on your model of water heater.

## Configuration

1. From the Home Assistant front-end, navigate to 'Configuration' then 'Integrations'. Under 'Set up a new integration' locate 'Rheem EcoNet Products' and click 'Configure'.
2. Enter the information requested, email and password, and click 'Submit'.
