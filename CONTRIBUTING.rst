============
Contributing
============

**Important**: We are using git-flow workflow here, so please submit your pull requests against develop branch (and not master).

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

You can contribute in many ways:

Types of Contributions
----------------------

Report Bugs
~~~~~~~~~~~

Report bugs at https://github.com/agateblue/django-dynamic-preferences/issues.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.
* Include whole stacktraces and error reports when necessary, directly in your issue body. Do not use external services such as pastebin.

Contributing
------------

Fix Bugs
~~~~~~~~

Look through the GitHub issues for bugs. Anything tagged with "bug"
is open to whoever wants to implement it.

Implement Features
~~~~~~~~~~~~~~~~~~

Look through the GitHub issues for features. Anything tagged with "feature"
is open to whoever wants to implement it.

Write Documentation
~~~~~~~~~~~~~~~~~~~

django-dynamic-preferences could always use more documentation, whether as part of the
official django-dynamic-preferences docs, in docstrings, or even on the web in blog posts,
articles, and such.

Submit Feedback
~~~~~~~~~~~~~~~

The best way to send feedback is to file an issue at https://github.com/agateblue/django-dynamic-preferences/issues.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* Remember that this is a volunteer-driven project, and that contributions
  are welcome :)

Get Started!
------------

Ready to contribute? Here's how to set up `django-dynamic-preferences` for local development.

1. Fork the `django-dynamic-preferences` repo on GitHub.
2. Clone your fork locally::

    $ git clone git@github.com:your_name_here/django-dynamic-preferences.git

3. Install your local copy into a virtualenv. Assuming you have virtualenvwrapper installed, this is how you set up your fork for local development::

    $ mkvirtualenv django-dynamic-preferences
    $ cd django-dynamic-preferences/
    $ python setup.py develop

4. Create a branch for local development::

    $ git checkout -b name-of-your-bugfix-or-feature

Now you can make your changes locally.

5. When you're done making changes, check that your changes pass flake8 and the
tests, including testing other Python versions with tox::

    $ flake8 dynamic_preferences tests
    $ python setup.py test
    $ tox

To get flake8 and tox, just pip install them into your virtualenv.

6. Commit your changes and push your branch to GitHub::

    $ git add .
    $ git commit -m "Your detailed description of your changes."
    $ git push origin name-of-your-bugfix-or-feature

7. Submit a pull request through the GitHub website.

Pull Request Guidelines
-----------------------

Before you submit a pull request, check that it meets these guidelines:

1. The pull request should include tests.
2. If the pull request adds functionality, the docs should be updated. Put
   your new functionality into a function with a docstring, and add the
   feature to the list in README.rst.
3. The pull request should work for Python, 2.7, and 3.4. Check
   https://travis-ci.org/agateblue/django-dynamic-preferences/pull_requests
   and make sure that the tests pass for all supported Python versions.
4. The pull request must target the `develop` branch, since the project relies on `git-flow branching model`_

.. _git-flow branching model: http://nvie.com/posts/a-successful-git-branching-model/


Tips
----

To run a subset of tests::

    $ python -m unittest tests.test_dynamic_preferences
