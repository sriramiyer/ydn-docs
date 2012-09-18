==============
YQL Quickstart
==============

1. Open YQL console
-------------------

	http://developer.yahoo.com/yql/console/

2. Choose Example Query
-----------------------

Under "Example Queries" click the "find sushi restaurants in san francisco" query.

.. code-block:: javascript

	select * from local.search where query="sushi" and location="san francisco, ca"

3. Run the Example Query
------------------------

Select the desired output format (XML or JSON) and click the "Test" button. This returns all fields of the *local.search* table. The filters in the WHERE clause restrict the output prouced by the table. Observe the output of the query, and note the various fields returned in the response.

4. Tweak the example Query
--------------------------

Here are some things you can do to get a feel of YQL and the *local.search* table:

	#. Replace the "sushi" in the original query with "pizza" and see how the output changes.
	#. Replace the \* in the original query with ``Title, Address, City`` and see how the output changes.
	#. Add ``limit 5`` to the original query and see how the number of results returned is restricted to 5.
	#. Add ``| sort (field="Rating.AverageRating")`` to the original query and see how the results with lowest ratings are shown on top.
	#. Copy the "REST QUERY" at the bottom of the page and paste it into a new browser window - this is the way that almost all applications invoke YQL directly.

5. Explore
----------

Feel free to try out other tables within the YQL console by clicking on them in the *DATA TABLES* section. You can look at what keys are available for each table by clicking the small *desc* link that pops up adjacent to the table name when you hover over it.

Explore even more tables within the YQL console by clicking on the *Show Community Tables" link in the *DATA TABLES* section. This lets you try out the approximately 1200 tables developed by the vibrant YQL community outside of Yahoo!

6. Dive into YQL
----------------

Visit the YQL guide at http://developer.yahoo.com/yql/guide and get started on understanding how to better use YQL in your own application.
