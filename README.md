# Android_tutoriel

# HTTPRequest
 
  free android library for making http request to invoque webservices 
  
  # basic
  
     -add the class HTTPRequest to your project 
     -you can use this to make requests
  
                HTTPRequest http = new HTTPRequest();
                JSONObject obj = http.MakeHttpRequest(HTTPRequest.GET_METHOD, "your_url",null);
                
    -send Post request with params
    
                HashMap<String,String>  param=new HashMap<>();
                  param.put("login",login);
                  param.put("password",pass);
                HTTPRequest http = new HTTPRequest();
                JSONObject obj = http.MakeHttpRequest(HTTPRequest.POST_METHOD, "your_url",param);
