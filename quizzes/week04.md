# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```async code runs after it gets a promise.
synchronous code runs as javascript is programed to read javascript.

```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
an event listener does what it says. it listens to an event.
heres an example. lets say in our appstate we say object = []
everytime we pass through an object through object the event listener will ping. when the event listener pings it will then run the function that is supplied after the comma. the comma is past the thing its listening too.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
open closed principle.

    we should be able to add new features or componets to the application without breaking existing code.
    and alternatively. we should not add code that will break other code.

    example. a class should be able to expand further without modifying the class or functions itself.




```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
callback is a convention in javascript.
callback is a function that doesnt immediately run as its read.
like maybe the code waits until a video is availible from a server then it will run.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
promise is a response from a server.
uhm...
pshhhh,..
lol..
okay.
in short i want to say console log it.
in my longform that is detailed for somebody else to understand its currently we use axios.
axios talks to an API.
in service we use the variable of res for response 
the response is from the API.
so console log the res from the API.
there is more steps like invoking a function to do that.
and to invoke that function it could be automatically done with a constructor in the controller..
or i could style out a fancy button that glows when you hover on it with a icon and make it take up the entire screen and let the res be drawn back to the screen.

you know what they say. there's many many ways to love a cat lol.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
request to the server, promise from server to client. promise is fulfilled or not
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
application programming interfaces
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
right now we are using a axios service folder that has our base url and params, in conjuction with another specific service folder with the base urls extension. both are working together to talk through axios(car goes) client -> server, and server -> client
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
security. organization.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
internal server error.
```