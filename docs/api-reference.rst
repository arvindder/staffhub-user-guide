API Reference
=============

This section provides information about the StaffHub API for developers.

Authentication
--------------

All API requests require authentication using an API key:

.. code-block:: python

   import requests
   
   headers = {
       'Authorization': 'Bearer YOUR_API_KEY',
       'Content-Type': 'application/json'
   }

Endpoints
---------

Users Endpoint
~~~~~~~~~~~~~~

Get all users:

.. code-block:: http

   GET /api/v1/users
   Authorization: Bearer YOUR_API_KEY

Response:

.. code-block:: json

   {
     "users": [
       {
         "id": 1,
         "name": "John Doe",
         "email": "john@example.com",
         "role": "Staff"
       }
     ]
   }

Schedules Endpoint
~~~~~~~~~~~~~~~~~~

Get schedules for a date range:

.. code-block:: http

   GET /api/v1/schedules?start_date=2024-01-01&end_date=2024-01-31
   Authorization: Bearer YOUR_API_KEY

Rate Limiting
-------------

API requests are rate-limited to 1000 requests per hour per API key.

For more information, see the full API documentation at https://api.staffhub.example.com/docs

