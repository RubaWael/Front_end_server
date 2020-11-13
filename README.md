# Front_end_server
This is the first version of front end server .
the main functionality of this server is to sent REST requests to catalog and arder servers.
for lookup and search methods, front end server have to sent a request to catalog server and show the list of books returned.
for buy method, front end server have to sent a request to order server, then order server sent another request to catalog serve. After that, order server take the responce and forword it to front end server to show if buy process are done or fail.
