# RabbitMQ Web STOMP Examples

## This was migrated to https://github.com/rabbitmq/rabbitmq-server

This repository has been moved to the main unified RabbitMQ "monorepo", including all open issues. You can find the source under [/deps/rabbitmq_web_stomp_examples](https://github.com/rabbitmq/rabbitmq-server/tree/master/deps/rabbitmq_web_stomp_examples).
All issues have been transferred.

## Introduction

This project contains few basic examples of [RabbitMQ Web STOMP plugin](https://github.com/rabbitmq/rabbitmq-web-stomp)
usage.

Once installed the server will bind to port 15670 and serve few static
HTML files on port 15670 (e.g. [http://127.0.0.1:15670](http://127.0.0.1:15670/)).

## Installation

This plugin ships with RabbitMQ. Enabled it using [CLI tools](https://www.rabbitmq.com/cli.html):

    rabbitmq-plugins enable rabbitmq_web_stomp_examples
