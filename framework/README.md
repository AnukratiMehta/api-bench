# @idrinth/api-bench

[![Coverage Status](https://coveralls.io/repos/github/Idrinth/api-bench/badge.svg?branch=master)](https://coveralls.io/github/Idrinth/api-bench?branch=master) [![Codacy Badge](https://app.codacy.com/project/badge/Grade/3171affc728048da8df4fe36b6d4771e)](https://app.codacy.com/gh/Idrinth/api-bench/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)

## Contents

- [Contents](#contents)
- [What does this Project do?](#what-does-this-project-do)
  - [Why a Benchmark Runner](#why-use-a-benchmark-runner)
  - [Regarding existing libraries](#regarding-existing-libraries)
- [Usage & Examples](#usage--examples)
- [License](#license)
- [Support](#support)

## What does this project do?

This project provides a framework for testing restful APIs and websites for changes in response times. This helps to detect performance changes in code in a quick and simple manner.

### Why use a Benchmark Runner

Given, that the amount of APIs increase by moving to microservices, we need a way to determine if changes to a service's response times are related to code changes. For this purpose a defined load with repeatable request seems the most useful.

### Regarding existing libraries

Other tools like [matteofigus/api-benchmark](https://github.com/matteofigus/api-benchmark), [bvanderlaan/api-bench-runner](https://github.com/bvanderlaan/api-bench-runner) or [jeffbski/bench-rest](https://github.com/jeffbski/bench-rest) are all untouched for quite a while and don't provide type definitions for typescript. This makes them less desirable when working with bigger projects where the better static codecheck is a huge boost in development speed.
Additionally, this tool separates the validation thread from the thread processing the actual requests to further minimise the effect of complicated validations or huge response bodies on the data gathering.

## Usage & Examples

Please have a look at the [website](https://idrinth-api-ben.ch) for more information.

## License

As usual with my projects this is MIT-licensed.

## Support

Additionally, to support requests via issue, you can reach me via discord at [Idrinth's Discord](https://discord.gg/xHSF8CGPTh). Commercial support and training is provided via [Björn Büttner](https://bjoern-buettner.me).
