# Ansible Role: telegraf

Install telegraf, a useful agent to grab metrics.

## Requirements

Ubuntu 16.04

Should work on all supported by InfluxData distros.

## Tags

- **telegraf-repository**: Only add Telegraf (whole Influxdata stack) repository to `/etc/apt/sources.list.d/influxdb.list` (if no defaults were redefined, see options `telegraf.apt_keyserver`, `telegraf.apt_key_sig`, `telegraf.apt_repository`, `telegraf.apt_repository_filename`), install all needed python modules for ansible apt* modules.
