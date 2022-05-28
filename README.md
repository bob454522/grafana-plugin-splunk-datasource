# Splunk Data Source Plugin for Grafana

![Splunk Data Source for Grafana](https://github.com/efcasado/grafana-plugin-splunk-datasource/actions/workflows/ci.yml/badge.svg?branch=main)
[!["Buy Me A Coffee"](https://img.shields.io/badge/-buy_me_a%C2%A0coffee-gray?logo=buy-me-a-coffee)](https://www.buymeacoffee.com/efcasado)


## What is Splunk Data Source Plugin for Grafana?

Splunk Data Source Plugin for Grafana is a Grafana (data source) plugin that
allows you to pull Splunk data into your Grafana dashboards. Or, in other words,
it is a Grafana plugin that allows you to query Splunk directly from Grafana.


## Installation

1. Download the latest version of the plugin

    ```bash
    wget https://github.com/efcasado/grafana-plugin-splunk-datasource/releases/download/v0.1.0/efcasado-splunk-datasource-0.1.0.zip
    ```

2. Unzip it in your Grafana's installation plugin directory (eg. `/var/lib/grafana/plugins`)

    ```bash
    unzip efcasado-splunk-datasource-0.1.0.zip -d YOUR_PLUGIN_DIR/efcasado-splunk-datasource
    ```


## Configuration

TBD


## Getting started

1. Build the project

   ```bash
   make build
   ```

2. Spin up the test environment

   ```bash
   make up
   ```

3. Point your browser to [localhost:3000](http://localhost:3000)


### License

> The MIT License (MIT)
>
> Copyright (c) 2022, Enrique Fernandez
>
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in
> all copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
> THE SOFTWARE.
