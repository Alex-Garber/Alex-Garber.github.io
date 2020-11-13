## Introduction

I am an egar determand student currently attending the Jave/Android boot camp at cnm.
 My plan after gradutaion is to look for employment or contract work in Android app development 
 
## Current projects 

* [Hello world: Java console appalication](https://github.com/Alex-Garber/deep-dive-hello-world)
* [Hello work: Android app](https://github.com/Alex-Garber/HelloWolrdpart2)

## Links
[LinkedIn](https://www.linkedin.com/in/alex-garber-a009281b4/)

## Recently updated repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{ repo.name }}]({{ repo.html_url}})
{% endfor %}
