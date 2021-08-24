
## Class_09

### Authorization/Authentication


#### Q1: What header(s) are used in authentication and authorization
=> The HTTP Authorization request header contains the credentials to authenticate a user agent with a server, usually, but not necessarily, after the server has responded with a 401 Unauthorized status and the WWW-Authenticate header.

=> The HTTP WWW-Authenticate response header defines the authentication method that should be used to gain access to a resource.


#### Q2: What is safe to put into a JWT

=> It's safe to put very strong **SECRET-Key** ,So nobody can change user info from JWT used 
=> And put **encoding password** , So nobody can know it from JWT used 
By this way we can get more Safe and Secure


#### Q3: How are JWTs validated

- The Application server, instead of just taking the username from the header, will first validate the JWT:

=> if the signature is correct, then the user is correctly authenticated and the request goes through.
=> if not, the application server can simply reject the request.

----------------------

## Terms ::

- **RBAC** : It is the idea of assigning system access to users based on their role in an organization. It’s important to remember that not every employee needs a starring role.

- **User Roles** : A permission is the right to access one or more system objects. A role is a group of permissions. Roles can be assigned to any user or user group, and a user or user group can have more than one role. Unlike hierarchical users, a role does not contain another role.

- **JWT Token** : JSON Web Token (JWT) is a JSON encoded representation of a claim(s) that can be transferred between two parties. The claim is digitally signed by the issuer of the token, and the party receiving this token can later use this digital signature to prove the ownership on the claim.