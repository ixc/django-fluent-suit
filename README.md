# Fluent Suit

A collection of template overrides to get Fluent CMS (including Parler) to play
nice with Django Suit.

# Installation

Install directly from GitHub:

	$ pip install -e 'git+https://github.com/ixc/django-fluent-suit.git#egg=django-fluent-suit'

Add to `INSTALLED_APPS`:

	# Must come before Fluent CMS apps and Django Suit to override template
	# load order and static file collection.
	INSTALLED_APPS = ('fluent_suit', ) + INSTALLED_APPS

## Assumed Versions

django-suit>=0.26
https://github.com/darklow/django-suit

django-fluent-blogs>=1.0a1
https://github.com/edoburu/django-fluent-blogs

django-fluent-contents>=1.0a1
https://github.com/edoburu/django-fluent-contents

django-fluent-pages>=0.9a1
https://github.com/edoburu/django-fluent-pages
