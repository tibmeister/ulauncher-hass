# Home Assistant - Ulauncher Extension

A [Ulauncher](https://ext.ulauncher.io/) extension to view and control devices in your [HomeAssistant](https://www.home-assistant.io/) instance.

This is heavily influenced by [qcasey/ulauncher-homeassistant](https://github.com/qcasey/ulauncher-homeassistant)

![Demo](https://github.com/tibmeister/ulauncher-hass/raw/main/demo.gif)

## Requirements

You'll need the Requests lib:

`pip install requests`

As well as the URL / API Key for your Home Assistant instance. You can generate a new long lived API Key by going to /profile (or clicking your name in the bottom left).

## Usage

Ideally all homeassistant services should be exposed, like media players and climate controls. The rough idea is

`<keyword> <service> <entity search>`

I don't use a lot of these so I cannot test them, however I welcome PRs. Speaking of...

## Contributing

I welcome all issues and contributions! Create a PR to contribute code.