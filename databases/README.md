# Databases

Lucy allows you to create and manage databases, providing a flexible and schema-less storage solution for diverse sets of data. These document-based containers enable you to store and query arbitrary information according to your unique needs.



{% hint style="info" %}
When we say 'database', it's more akin to a table or a collection, rather than how the word 'database' is used in a traditional database engine, where it refers to a single space that contains multiple tables + logic + security settings etc... We're trying to keep it simple here.
{% endhint %}



The 'document-based' aspect means that each item you add to the database is a document object that can contain one or more fields within it. Each field, in turn, can contain a value, a list of values, or another document.&#x20;

If you think of a 'Document' as a 'JSON Object', you're good to go.



The 'schema-less' aspect means there is no fixed structure for the document. When defining your database, you can specify what fields it expects but it's more of a guideline. It's not required that all fields are present in every document, and it's not necessary for every field in a document to be pre-defined.



You can create as many databases as you want. They are useful for storing data that you need for visualisations or analytics or for driving business logic and integrations.
