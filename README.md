# IR-ExploreSL
Web UI
------

Serve this index.html on localhost:5500

Tasks -
when search button clicked, HTTP reqest will be made to ElasticSearh to xecute the query.
returned results are iterated one by one getting fields such as title, URL, description
Then description is splitted using period (.)and filtered first sentence containin the query term.
When results are displayed, above filtered sentence is used as the description with uery term highlighted in the text.
So far, qery term highlight only works for simple queries and not for complex queries.
