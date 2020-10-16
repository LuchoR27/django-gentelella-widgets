Notifications app
^^^^^^^^^^^^^^^^^^^

How to install it ??

After add 'djgentelella' to INSTALLED_APPS variable in the settings file, you will be able to use this app.

Then to use notification you must use create_notification function.

.. code:: python

   from djgentelella.notification import create_notification

.. automodule:: djgentelella.notification.create_notification
   :members:
   :noindex:

You can also add a widget to handle notifications from navbar.

.. automodule:: djgentelella.notification.widgets
   :members:
   :noindex:
