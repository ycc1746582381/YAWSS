# YAWSS

**Yet Another Web Security Scanner** - A Web Application Security Scanner Written in
Python.

## Objectives
Making automated security scans and web application tests easy to handle by just
writing yaml configs.

## Features

- Perform scan by modules created by the user.
- Crawl the website and save all necessery data.
- CLI and Web User Interface option.
- Scan configs can be written with YAML.
- Basic Secuirty information will be enough to use and test any web application.
- Support testing raw request as an input.

### Version

0.1.0 **BETA**

[(public releases).(beta versions).(bugfixes patches)]

## Installation


For installing the required libraries
```
$ pip install -r requirements
```

And it's ready.

## Usage

```bash
➜ python3 YAWSS.py -s [SCAN_CONFIG_PATH]
➜ python3 YAWSS.py -s [SCAN_CONFIG_PATH] -m  [MODULE1_NAME],[MODULE2_NAME]
➜ python3 YAWSS.py -ui web
```

For start a scan you have first to create a scan config file check the template
in 'scans' folder.

Modules have to be in modules folder for creating a new module please check the
template in 'modules' folder.

## Screenshots

![ss00](https://github.com/0xihsn/YAWSS/blob/master/screenshots/screenshot00.png) ![ss00](https://github.com/0xihsn/YAWSS/blob/master/screenshots/screenshot01.png)

## Development

Want to contribute? Great!

* Fork it!
* Create your feature branch: git checkout -b my-new-branch
* Commit your changes: git commit -m 'Add some feature'
* Push to the branch: git push origin my-new-branch
* Submit a pull request.

> **Note:** Any pull request will require to change the project main design will not
> approved until the next version.

## Todo's

 - Implement the check attack type
 - Use multi-threading in the analyze engine.
 - Develop a report generator to generate a professional report.
 - Use database for saving the projects details to optimize the RAM usage.
 - Add login page.
 - Write many new modules.

License
----

All project files are licensed under GPL v3 - please check the LICENSE file for more information.

**Bootstrap** and **Chartjs** javascript and css files are licensed under MIT license please check their official websites for more information.

&nbsp;

&nbsp;

&nbsp;

---

> **Bootstrap copyright**

    Copyright (c) 2011-2018 Twitter, Inc.

    Copyright (c) 2011-2018 The Bootstrap Authors.

> **Chartsjs copyright**

    Copyright (c) 2018 Chart.js Contributors.