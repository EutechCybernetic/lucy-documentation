# Databases

Lucy lets you define databases and use them to store and query any arbitrary data you want.

Databases are document-based schema-less storage containers for any kind of data you want.

{% hint style="info" %}
When we say 'database', it's more akin to a table or a collection, rather than how the word 'database' is used in a traditional database engine, where it refers to a single space that contains multiple tables + logic + security settings etc... We're trying to keep it simple here.
{% endhint %}



The 'document-based' part means that each item you add to the database is a document object that can contain one or more fields within it. Each field can in-turn contain a value, a list of values, or another document.&#x20;

If you think of 'Document' as 'JSON Object' you're good to go.



The 'schema-less' part means there is no fixed structure for the document. When you define your database, you can specify what fields it expects but that's more of a guideline. Its not required that all fields are present in every document and its not required that every field in a document is pre-defined.



You can create as many databases as you want. They are useful for storing data that you need for visualizations or analytics or for driving bussiness logic and integrations
