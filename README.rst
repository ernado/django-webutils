=====
webutils
=====

Combined common toolkit for all our projects.

Quick start
-----------

pip install git+git://github.com/Ernado/django-webutils.git#egg=django-webutils

1. Add "webutils" to your INSTALLED_APPS setting like this::

      INSTALLED_APPS = (
          ...
          'webutils.captcha',
          'webutils.watermarks',
          'webutils',
      )

2. Configure in settings::

    FEEDBACK_MAIL = ['feedback@host', ...]
    MAIL_PASSWORD = 'password'
    MAIL_SERVER   = 'mail.server.com'
    YANDEX_API_KEY = 'yandex api key'
    
4. PROFIT

