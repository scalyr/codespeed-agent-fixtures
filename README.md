# Scalyr Agent CodeSpeed Fixture Files

This repository contains various log fixture files which are used to benchmark
the scalyr-agent-2 project.

## Directory Structure

* ``fixtures/logs/`` - Contains various raw log file fixtures.
* ``fixtures/protobuf/`` - Contains various fixtures for serialized Protobuf messages. Those
  fixture files are usually generated from raw log file fixture in logs/ directory.

## Log File Sources

All the log files in this directory are either auto generated or available from
free and public sources:

* ``fixtures/logs/access_log_*_mb.log`` -> http://www.almhuette-raith.at/apache-log/access.log
