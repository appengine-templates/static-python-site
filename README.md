static-python-site
==================

A template that allows you to host a static site on Google App Engine using the Python WSGI.

How to
------

* Put your static files in the `static` directory and you're almost done.
* Also, you need to change the application name in the app.yaml to what you've entered in your App Engine dashboard.  
* Upload the site using the following command line:  
  
      appcfg.py update myapp/
  
  More information on uploading is available here: <https://developers.google.com/appengine/docs/python/tools/uploadinganapp>

Note that I did not set up any error handlers. So the defaults of Google App Engine will be used.