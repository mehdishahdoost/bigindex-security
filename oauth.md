### OAuth Roles

OAuth defines four roles:

* Resource Owner: The resource owner is the user who authorizes an application to access their account. 
The application’s access to the user’s account is limited to the scope of the authorization granted (e.g. read or write access)

* Client: The client is the application that wants to access the user’s account. Before it may do so,
it must be authorized by the user, and the authorization must be validated by the API.

* Resource Server: The resource server hosts the protected user accounts.

* Authorization Server: The authorization server verifies the identity of the user then issues access tokens to the application.
From an application developer’s point of view, a service’s API fulfills both the resource and authorization server roles. 
We will refer to both of these roles combined, as the Service or API role.
