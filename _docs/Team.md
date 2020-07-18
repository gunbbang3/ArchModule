---
title: Team members section
subtitle:SubTitle 자리 입니다.
tags: [features]
author: andy
---

To add the following to a page:
{% raw %}
```yaml
{% include team.html authors="wootaik, andy" title="We are here to help" subtitle="Our team is just an email away ready to answer your questions" %}
```
{% endraw %}

Specifying authors is optional, if not defined all authors will be displayed form `_config.yml` file.
