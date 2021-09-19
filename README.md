# Javascript---Day--1-Introduction-to-Browser-web

# Diff between HTTP1.1 and HTTP2

HTTP was a simple protocol.
It was used earlier to transfer documents from a web server to the local computer.
At that time the web elements and documents were simple as just texts and basic images so transfer was easy too.
But later on the web usage changed and people began to use web for various purposed ie for shopping and all.
So the transfer of documents , data and load increased.
The old HTML1.1 was unable to handle the data on this much scale.
The newly added HTML2 was able to download the various resources with a single connection.
It was developed by google with initial name SPDY , they used to call iy by synonym as SPEEDY.
In HTML1.1 case there was one way connection ie the request sent for each requirement.
But in HTML2 there is two way connection where the server is always listening
HTTP2 is binary, instead of textual
HTTP2 is fully multiplexed, instead of ordered and blocking
HTTP2 can, therefore, use one connection for parallelism
HTP2 uses header compression to reduce overhead
HTTP2 allows servers to “push” responses proactively into client caches


# Objects in JS
Objects contain a combination of primitive data-types as well as reference data-types.
Objects can have any data type for example key should be a string but value can be anything like string ,number ,array or another object.
An object is a reference data type. Variables that are assigned a reference value are given a reference or a pointer to that value. That reference or pointer points to the location in memory where the object is stored. The variables don’t actually store the value.
They are unordered collection of related data, of key: value pairs.
These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.
An object can be created with figure brackets {} with an optional list of properties. A property is a key: value pair, where a key is the property name value can be anything.
