# django_eb_template
Django 1.11.2 template configured to work with AWS Elastic Beanstalk

This was built with the help of Real Python's [Guide](https://realpython.com/blog/python/deploying-a-django-app-to-aws-elastic-beanstalk).

## Notes:
1. Replace the Security Key. I've generated this one for the public repository:
```
SECRET_KEY = 'o^t+p*oo@_*=16u40oro1qo-p2dfohbdpst)f292l*@hvpi&9f'
```
You can generate a new one [here](http://www.miniwebtool.com/django-secret-key-generator/).

2. Checkout `.elasticbeanstalk/config.yml` and replace *application_name*, *default_ec2_keyname* (not necessary).
3. Replace all instances of `django_eb_template` with your applciation name. Use snakecase.
