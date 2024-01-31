# Lab Report 2 - Servers and SSH Keys

## ChatServer

```
ChatServer code
```
![Image](https://github.com/DatGuy84/CSE-15L-Lab-2.0/blob/main/image_2024-01-30_123743936.png?raw=true)

```
First Message
```
![Image](https://github.com/DatGuy84/CSE-15L-Lab-2.0/blob/main/First%20message.png?raw=true) 

* In the `ChatServer` class, the methods `handleRequest` and `history` are called.
* In the `handleRequest` method, `url` of type `Uri` is taken in as an argument.  The String ArrayList called
  `HistoryList`, the three String variables (`user`, `message`, and `dialogue`), and the
   three String Arrays (`parameters`, `Mparameters`, and `Uparameters`) are given values inside
  `handleRequest`.  The `history` method has a String variable called `dialogues` and uses `HistoryList`
  to give `dialogues` its String values.
* When `/add-message` is apart of the url, the `handleRequest` method searches for the query, and
  `parameters` splits the query by the & symbol which separates the message and user.  `Mparameters` splits the
  message part and assigns it to the `message` variable, and `Uparameters` splits the user part and assigns it
  to the `user` variable.  The `dialogue` variable is then given a value in the format `user`: `message` and
  is added to `HistoryList` and returns the `history` method.  Since the `history` method is called, for every
  string in `HistoryList`, the variable `dialouges` is given the value of each string in `HistoryList` which is
  separated by `\n`.  `dialouges` is returned and prints out the string. 
```
Second Message
```
![Image](https://github.com/DatGuy84/CSE-15L-Lab-2.0/blob/main/second%20message.png?raw=true)
* In the `ChatServer` class, the methods `handleRequest` and `history` are called.
* In the `handleRequest` method, `url` of type `Uri` is taken in as an argument.  The String ArrayList called
  `HistoryList`, the three String variables (`user`, `message`, and `dialogue`), and the
   three String Arrays (`parameters`, `Mparameters`, and `Uparameters`) are given values inside
  `handleRequest`.  The `history` method has a String variable called `dialogues` and uses `HistoryList`
  to give `dialogues` its String values.
* When `/add-message` is apart of the url, the `handleRequest` method searches for the query, and
  `parameters` splits the query by the & symbol which separates the message and user.  `Mparameters` splits the
  message part and assigns it to the `message` variable, and `Uparameters` splits the user part and assigns it
  to the `user` variable.  The `dialogue` variable is then given a value in the format `user`: `message` and
  is added to `HistoryList` and returns the `history` method.  Since the `history` method is called, for every
  string in `HistoryList`, the variable `dialouges` is given the value of each string in `HistoryList` which is
  separated by `\n`.  `dialouges` is returned and prints out the string. 

## SSH key
```
Private key
```
![Image](https://github.com/DatGuy84/CSE-15L-Lab-2.0/blob/main/Password%20key.png?raw=true)
```
Public Key
```
![Image](https://github.com/DatGuy84/CSE-15L-Lab-2.0/blob/main/public%20key.png?raw=true)
```
No Password
```
![Image](https://github.com/DatGuy84/CSE-15L-Lab-2.0/blob/main/no%20password.png?raw=true)

## Summary
```
Throughout weeks 2 and 3, I have learned more about servers.  In week two, I learned how
to create a serve along with accessing the query and url info.  Additionally, in week
three, I learned how to create a pair of keys, public and private, that could be used
to sign in with my ieng6 account.
```

