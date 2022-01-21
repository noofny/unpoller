# Unpoller Config

Configuration needed to install and configure [Unpoller](https://unpoller.com/).

Vastly improved telemetry and observability for UniFi networks.

## Usage

- Install and configure Docker.
- Enable port TCP:8085 through firewall, eg `ufw allow 8086/tcp`
- Create a data mount/volume/folder (eg at `/root/unpoller`).
- Clone this repo and `cd` to the folder you cloned it to.
- Run `docker-compose up`
- Hopefully you see no errors and after a minute you should see something like...

```text
[INFO] UniFi Metrics Recorded. Sites: 1, Clients: 67, UAP: 6, USG/UDM: 1, USW: 5, IDS Events: 0, Points: 1837, Fields: 11307, Errs: 0, Elapsed: 599ms
```

## Links

- [UnPoller](https://unpoller.com)
- [UnPoller: Store UniFi Controller Metrics in Prometheus or InfluxDB ](https://community.ui.com/questions/UnPoller-Store-UniFi-Controller-Metrics-in-Prometheus-or-InfluxDB/58a0ea34-d2b3-41cd-93bb-d95d3896d1a1)
