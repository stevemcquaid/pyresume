================
PyResume Builder
================


.. image:: https://img.shields.io/pypi/v/pyresume.svg
        :target: https://pypi.python.org/pypi/pyresume

.. image:: https://img.shields.io/travis/waynr/pyresume.svg
        :target: https://travis-ci.org/waynr/pyresume

.. image:: https://readthedocs.org/projects/pyresume/badge/?version=latest
        :target: https://pyresume.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status

.. image:: https://pyup.io/repos/github/waynr/pyresume/shield.svg
     :target: https://pyup.io/repos/github/waynr/pyresume/
     :alt: Updates


Do you like updating your resume? Are you satisfied with the layout and
formatting? Do you ever wish you could try different styles without going
through the trouble of manually reformatting each time? Well now you can!

PyResume Builder is a command line tool that populates a LaTeX template from
contents defined in a YAML file. By storing the contents of your resume in a
human-readable markup language and generating a LaTeX or PDF file from that you
are free to try alternative templates and generate resumes in different formats
without the tedium of manually reformatting.


* Documentation: https://pyresume.readthedocs.io.


Features
--------

Current
+++++++

* Store resume contents (skills, experience, contact info, etc) in a YAML file
  for ease of updating and version control convenience.
* Templated LaTeX approach allows for consistent look and feel between different
  combinations of information you might want to include in your resume.
* Default LaTeX template includes support for:

  * Contact info
  * Education
  * Experience
  * Skills (up to two levels of subcategories supported)
  * Activities
  * Education
  * References

Planned
+++++++

* Support externally-defined Jinja2 LaTeX templates.
* Support some kind of html output format.
* Create new resume templates using cookiecutter.


Similar Projects
----------------

http://www.resumebuilder.org
  This site let's you sign in, enter your resume data in a series of web forms,
  and generate a resume from predefined templates. Also seems to include all
  kinds of helpful advice about resume layouts and being more of a rock star
  potential employee.


Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
