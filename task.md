# Lab: MongoDB lab

**Lab Duration: 90 minutes**

## Task

### MVP

We are going to store information about characters from the ever popular board game `Guess Who`.

Create a new file called `guess_who.js`.

Using a `guess_who` database and a `characters` collection perform the following actions:

- Add a few new characters with the following properties:
    - Name
    - Eye Colour
    - Hair Colour
    - Glasses (True/False)

- Get the list of characters back from the database

- Get one Character back by it's id.


### Extension

- Edit a characters property

- Delete a character.


### Notes

Comment out the `db.dropDatabase` and the `insertMany` once you have the characters in the database otherwise the id's will be regenerated every time you run the file.

Remember to use 

```sh
mongo < guess_who.js
```

to run the file.

