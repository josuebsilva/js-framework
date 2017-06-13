# js-framework

Http

Example

    var http = new Http(url);
    http.setMethod(http.Method.POST);
    http.setDataType("json");
    http.setHeaders({
        "Accept":"application/json",
        "Content-Type":"application/json"
    });
    http.setBody(body);
    http.Request(callback);
    
Alert

    var alert = new Alert();
    alert.setMessage("Hi! :)");
    alert.setType(AlertType.SUCCESS);
    alert.setContainer("#my-div");
    alert.show();
    
    // if you need clear alert, call clear(), look. 
    alert.clear();
