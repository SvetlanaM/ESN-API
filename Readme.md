# ESN API

ESN API documentation for [Erasmus in Czech republic mobile application project](https://www.esncz.org/cz-erasmus-app). 
This project is divided to many phases. This version of the API is for version 01.


# Allowed HTTPs requests:
<pre>
POST     : To create resource
PUT    : Update resource
GET     : Get a resource or list of resources
DELETE  : To delete resource
</pre>

# Description Of Usual Server Responses:
- 200 `OK` - the request was successful (some API calls may return 201 instead).
- 201 `Created` - the request was successful and a resource was created.
- 204 `No Content` - the request was successful but there is no representation to return (i.e. the response is empty).
- 400 `Bad Request` - the request could not be understood or was missing required parameters.
- 401 `Unauthorized` - authentication failed or user doesn't have permissions for requested operation.
- 403 `Forbidden` - access denied.
- 404 `Not Found` - resource was not found.
- 405 `Method Not Allowed` - requested method is not supported for resource.
- 500 `Internal Server Error` - server error

# Authentication
<table>
    <tr>
        <td> Token </td>
        <td> Token/API key </td>
    </tr>
</table>
