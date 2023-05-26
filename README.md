# This repository for helps learning RedHAT Ansible Playbooks development and teaching mid and advanced level examples

## Prerequisite and requirements for running these examples

[Please goto this link and to complete your environment setup](https://github.com/baasandorj/playbooks/blob/master/module_utils/README.md)

## Examples table

|Playbook Name|Usage|To learn knowledge|
|---|---|---|
|[parse-test-1](https://github.com/baasandorj/playbooks/blob/master/parse-test-1.yaml)|Example of searching exact word text from an ascii text table result|You will be learn how to use block, if then else, loop, error control, and string commands.|
|[parse-test-2](https://github.com/baasandorj/playbooks/blob/master/parse-test-2.yaml)|Parsing "ip addr show" command result by using Ansible special text parsing modules|You will be learn how to use cli_parse, netcommon.native modules, processing json and template file.|
|[parse-test-3](https://github.com/baasandorj/playbooks/blob/master/parse-test-3.yaml)|Parsing DIG command result by jc community developed ansible module|You will be learn how to use jc community developed ansible module for parsing linux command result and converting it into nice json format.|
|[parse-test-4](https://github.com/baasandorj/playbooks/blob/master/parse-test-4.yaml)|Parsing PS command result by using cli_parse custom developed template file|You will be learn how to use for parsing ps command result by cli_parse with custom developed template file and saving its result into json file|
|[parse-test-5](https://github.com/baasandorj/playbooks/blob/master/parse-test-5.yaml)|Parsing remote host command result and convert it into tuples result|You will be learn how to parsing remote command result by string methods and save it into tuples|
|[parse-test-6](https://github.com/baasandorj/playbooks/blob/master/parse-test-6.yaml)|Parsing remote host command result and convert it into dictionary result|You will be learn how to parsing remote command result by string methods and save it into dictionary|
|[parse-test-7](https://github.com/baasandorj/playbooks/blob/master/parse-test-7.yaml)|Parsing remote host command result by jinja template code and convert it into tuples result|You will be learn how to parsing remote command result by jinja template methods and save it into tuples|
