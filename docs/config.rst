Configuration
=============

In the pre-generated ``config.yaml`` all the values are required. You can add
as many values to that file and they will be available in the templates'
context.

.. option:: author

    Blog author

.. option:: site_name

    Site name

.. option:: posts_per_page

    Number of posts displayed per page. Used for pagination.

.. option:: url

    Your site's URL.

.. option:: date_format

    Python strftime formatted date format

.. option:: text_processor

    Which X to html processor to use; 'markdown', 'textile', 'rst', 'html'

.. option:: templates

    'django' or 'jinja2'

.. option:: append_slash

    Whether a slash should be appended to post urls.