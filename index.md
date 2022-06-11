---
layout: centered-column
title: USPS Hold Mail Service
prose: true
body-style: bg-base-lightest
layout-style: tablet:width-tablet bg-white margin-top-6 padding-5 radius-lg shadow-3
save-data: true
---

# USPS Hold Mail Service

Headed out of town? We can hold your mail safely at your local Post Office™ until you return.
{: .font-body-lg}

We can hold your mail from 3 to 30 days in a row. For hold times greater than 30 days, please sign up for a [USPS forward mail service](https://www.usps.com/manage/forward.htm?_gl=1*1lbyg57*_ga*NTk4Mjc4NTczLjE2NTMzNTg2MjY.*_ga_3NXP3C8S9V*MTY1MzUxNTY0MS41LjEuMTY1MzUxNjM2OC4w).

{% include components/text-input.html label="When do you want us to start holding mail?" type="date" %}

{% include components/text-input.html label="When do you want us to stop?" type="date" %}
{: .padding-bottom-4}

{% include components/radio-buttons.html legend="How do you want to get your held mail?" labels="I want it delivered,I'll pick it up" %}
{: .padding-bottom-4}

{% include components/checkbox.html legend="Acknowledgement" labels="I acknowledge that I am the person, executor, guardian, authorized officer, or agent of the person for whom mail would be redelivered under this order. I understand that anyone submitting false or inaccurate information on this form is subject to punishment by fine or imprisonment or both under Sections 2, 1001, 1702 and 1708 of Title 18, United States Code." %}
{: .padding-bottom-4}

{% include components/button.html label="Schedule Mail Hold" link="confirmation.html" style="usa-button--big" %}
{: .padding-bottom-4}

<!-- ACTIONS -->
{% include actions/get-data.html get-this="usps-hold-mail-service-when-do-you-want-us-to-start-holding-mail" put-it-here="when-do-you-want-us-to-start-holding-mail" %}

{% include actions/get-data.html get-this="usps-hold-mail-service-when-do-you-want-us-to-stop" put-it-here="when-do-you-want-us-to-stop" %}

{% include actions/get-data.html get-this="usps-hold-mail-service-how-do-you-want-to-get-your-held-mail-index"  put-it-here="how-do-you-want-to-get-your-held-mail" %}