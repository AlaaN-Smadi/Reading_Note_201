
## Class_08

### Access Control (ACL)



#### Q1: When is Basic Authorization used vs. Bearer Authorization?

=> We used **Basic Authorization** when the cleint sign in correctly in basic case to give him the **JWT** and used it to stay sign in 

=> We used **Bearer Authorization** in any internal rout after the cleint sign in ,  to avoid ask him about userName and Password every time when he use our app, by using JWT that generated when he sign in correctly


#### Q2: What does the JSON Web Token package do?

=> Generate a Token that we used to create auto Authorization without need to enter userName and password every time when the cleint create a request 

#### Q3: What considerations should we make when creating and storing a SECRET?

- Make it complex as much as we can 
- Don't share it 
- Use .env and never push or store it on Git repo 

---------------------------

## Document the following Vocabulary Terms

- **encryption** => it is a way of scrambling data so that only authorized parties can understand the information. In technical terms, it is the process of converting human-readable plaintext to incomprehensible text, also known as ciphertext.

- **token** => it an encoded json, that we use in beare authorization to ensure if the user is authorized or not.

- **bearer** => it is an authorization process, that use the header, and create and compare the token for the users, to allow them to reach a certain endpionts or not.

- **secret** => it is a signiture for the developper that make his token secure and no one can access his data when his secret is exists.

- **JSON Web Token** => it is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed.

