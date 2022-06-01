# django-http-benchmarks

A Django project for investigating HTTP performance in various scenarios.

These are _HTTP benchmarks_ because we're checking the full app performance,
in contrast to the micro benchmarks you'll find in the `djangobench` project.

See also:

* [`djangobench`](https://github.com/django/djangobench): Harness and benchmarks for evaluating Django's performance over time.
* [`django-asv`](https://github.com/smithdc1/django-asv): Runner for benchmarks under ASV. Part of GSoC 2022.


The goal here is to be able to look at the effect of changes such as different
protocol server, worker numbers and so on, as well as verify the high-level
effect of proposed changes related the async project and ASGI in Django.
