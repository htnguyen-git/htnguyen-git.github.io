---
layout: post
title:  "Toeic vocabulary"
date:   2023-12-22 15:23:16 +0700
categories: toeic vocabulary
---

## People and Occupations List
{% assign record = site.data.eng.vocabulary | where: "group", "People and Occupations List" %}
{% for member in record %}
{{ member.word }} - {{ member.ipa }} - {{ member.meaning }}

|{{ member.describe }}|
{% endfor %}


## Business and Finance list
{% assign record = site.data.eng.vocabulary | where: "group", "Business and Finance list" %}
{% for member in record %}
{{ member.word }} - {{ member.ipa }} - {{ member.meaning }}

|{{ member.describe }}|
{% endfor %}


## Communications
{% assign record = site.data.eng.vocabulary | where: "group", "Communications" %}
{% for member in record %}
{{ member.word }} - {{ member.ipa }} - {{ member.meaning }}

|{{ member.describe }}|
{% endfor %}


## Technology
{% assign record = site.data.eng.vocabulary | where: "group", "Technology" %}
{% for member in record %}
{{ member.word }} - {{ member.ipa }} - {{ member.meaning }}

|{{ member.describe }}|
{% endfor %}


## Travel and transportation
{% assign record = site.data.eng.vocabulary | where: "group", "Travel and transportation" %}
{% for member in record %}
{{ member.word }} - {{ member.ipa }} - {{ member.meaning }}

|{{ member.describe }}|
{% endfor %}


## Time
{% assign record = site.data.eng.vocabulary | where: "group", "Time" %}
{% for member in record %}
{{ member.word }} - {{ member.ipa }} - {{ member.meaning }}

|{{ member.describe }}|
{% endfor %}


## The workplace
{% assign record = site.data.eng.vocabulary | where: "group", "The workplace" %}
{% for member in record %}
{{ member.word }} - {{ member.ipa }} - {{ member.meaning }}

|{{ member.describe }}|
{% endfor %}


## Marketing and Advertising
{% assign record = site.data.eng.vocabulary | where: "group", "Marketing and Advertising" %}
{% for member in record %}
{{ member.word }} - {{ member.ipa }} - {{ member.meaning }}

|{{ member.describe }}|
{% endfor %}


## Economics and Trade
{% assign record = site.data.eng.vocabulary | where: "group", "Economics and Trade" %}
{% for member in record %}
{{ member.word }} - {{ member.ipa }} - {{ member.meaning }}

|{{ member.describe }}|
{% endfor %}


## The Environment
{% assign record = site.data.eng.vocabulary | where: "group", "The Environment" %}
{% for member in record %}
{{ member.word }} - {{ member.ipa }} - {{ member.meaning }}

|{{ member.describe }}|
{% endfor %}


