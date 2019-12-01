Here is some instruction about what has been made.
An API has been created which listens at the link https://anypoint.mulesoft.com/mocking/api/v1/links/8255f7dd-70c5-4733-9647-1b26226ef265

That API is connected with another API (http://code-school-workshop.ir-e1.cloudhub.io/api/)

In the MuleSoft online platform, a Raml script has been coded. It implements the followings:
1) /user : GET - returns a list of all the users of the database
2) /user : POST - sends a JSON object and returns the ID of the new object
3) /user/{id} : GET - returns a JSON object of user that has the id of the URI param
4) /user/{id} : PUT - sends a JSON object and returns an JSON object that indicates the number of the matched objects and the modified 
			and a nullable field (upsertId)
5) /user/{id} : DELETE - returns a response in case there is an object with the same id of the URI param id which has been deleted

At the anypoint platform the connection with the other API has been developed. Moreover the above functions has been parameterized in order
to have a successfull response.