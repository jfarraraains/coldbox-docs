# Ajax Integration

There are several techniques and ways you can integrate ColdBox with any Ajax library, either to return xml/json/wddx or html snippets (views). In our [ColdBox Bundle](http://www.coldbox.org/download) download we have over 20 different ColdBox sample applications and most of them use all kinds of Ajax integrations. There are no limitations on what JavaScript libraries you use, they all work as long as Ajax requests are made, we can even tell you via the [RequestContext](http://wiki.coldbox.org/wiki/RequestContext.cfm) if a request is a normal request or an Ajax request (event.isAjax()).

As the developer you will have to decide what technique best suites your problem at hand, whether to return any type of data back to the caller via rendering JSON/WDDX/XML/CUSTOM or actual HTML blocks. ColdBox can do all of these return types natively and you don't even need to know how to marshall (convert) the data; ColdBox will do it for you if so needed. This guide focuses on Ajax integrations but most of these topics are covered already in our Event Handlers and Layouts & Views guides.

> **Info** Most JavaSscript examples are based on JQuery