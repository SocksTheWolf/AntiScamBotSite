---
title: Report a Scam
subtitle: Send a report directly to ScamGuard and TAG
layout: page
hero_darken: true
hero_height: is-fullwidth
description: Report a Discord scammer to ScamGuard
---

Use the handy form below to submit scamming reports to {{ site.bot_name }}.

{% if site.use_zapier_report == true %}
{% include report_zapier.html %}
{% else %}
{% include report_form.html %}
{% endif %}
