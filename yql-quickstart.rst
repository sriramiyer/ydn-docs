==============
YQL Quickstart
==============

#. Open YQL console
-------------------

	http://developer.yahoo.com/yql/console/

#. Choose Example Query
-----------------------

Under "Example Queries" click the "find sushi restaurants in san francisco" query.

.. code-block:: javascript

	select * from local.search where query="sushi" and location="san francisco, ca"

#. Run the Example Query
------------------------

Select the desired output format (XML or JSON) and click the "Test" button.

