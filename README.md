## Welcome!

My name is Alex Garber and I've caught the coding bug!

I'm currently attending a coding boot camp and CNM. This boot camp has been extremely annoying, difficult, mind-bending and so frustrating at points I have wanted to curl up under a blanket and hide.
With all that being said, I am absolutely loving it! Now that may sound strange to some but I'm enjoying it so much because of this overwhelming sense of fulfillment I get when I finally understand a new concept or figure out that problem that's been haunting my thoughts all day.

I have not always understood people who enjoyed a challenge. When I was a kid, I didn't get good grades I didn't enjoy challenging myself self in fact I hardly cared for much other than watching tv.
It wasn't until I dropped out of high school and got a job at Dairy queen to help my family pay the bills that something finally clicked.
I finally realized good things don't come easily. Good things come from hard work and dedication and ultimately challenging yourself every single day. This is where my journey really began or at least where it got interesting. I honestly believe that every upset in my life, every win every and every unexpected turn that has led me here has prepared me for a career in Program development. Coding can be complex, challenging, and overwhelming challenging but that's why I love it.

Some of my skills include (so far) Object-oriented programming Java, SQL, Junit testing, Intellij Idea, Markdown, Git Bash, Json, Building servers with Spring boot and androidx room, Android, Groovey, creating Entity-relationship Diagrams,  Designing wireframes for applications, leadership skills, problem-solving, customer service skills, with much more to come.

##  Areas of interest in software development

* Application Development
* Mobile Development
* API Development
* Software Tools Development
* Cloud Computing
* Security Software Development

## Current projects 

* [Smart Cheff](https://alex-garber.github.io/smart-cheff/)
	is an app that allows the user to input any amount of ingredients manually or with the camera if the ingredient has a barcode. After the user has inputted the ingredients of their choice and selected the search button, recipes are presented that include the ingredients inputted. 
* [Picme Gallery](https://picme-gallery.github.io/)
	 is an app that allows users who are out at an event, or who are traveling together to get access to a secure, cloud-based photo gallery via a shared password.
## Links
[LinkedIn](https://www.linkedin.com/in/alex-garber-a009281b4/)

## Recently updated repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{ repo.name }}]({{ repo.html_url}})
{% endfor %}
