@RestResource(urlMapping='/Account/*')
global with sharing class MyRestResource {

    //request
  @HttpPost
    global static void handleNotification()
    {
        try
        {
            RestResource request=RestContext.request;
            RestResponse response=RestContext.response;
        }

        catch(Exception e)
        {
            System.debug('Exception happen:'+e.getMessage());
        }
    }


}
