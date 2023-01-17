# RequestDispatchingApp

RequestDispatcherApp
1. In this App, we will create 2 servelts(FirstServlet, SecondServlet)
2. In this first servlet we will create a Request Dispacthing object using request object, with that object we will forward the request and response object of firstServlet.
4. Here request object of FirstServlet and SecondSerrvlet are same. The response object of FirstServlet will be flushed off. 
5. The response object of SecondServlet will be displayed to client.
6. RequestDispatcher will work only on single server where as RequestRedirection will work on different servers.
