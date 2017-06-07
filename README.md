# js-framework

Http

Example

    http = new Http(url);
    http.setMethod(http.Method.POST);
    http.setDataType("json");
    http.setHeaders({
        "Accept":"application/json",
        "Content-Type":"application/json"
    });
    http.setBody(body);
    http.Request(callback);
