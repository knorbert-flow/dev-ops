# Python 2 - Final Practice

### **SETUP**
- Using the Star Wars API ***( SWAPI )*** download all characters which appeared in the first film ***( films/1 , "A New Hope" )***  .

---

### **PART 1**
- Save the characters into an array, with only the following properties:
	- Name
	- Gender
	- Birth year
	- Eye color
	- Hair color
	- List of movies they appeared in ( only the name of the movie )
- Save this list into the following file formats:
	- JSON
	- CSV
	With the name: starwars_people.json/csv
- Compress all these files into people_compressed.zip
- Send me the compressed archive in a private message

---

### **PART 2**
- In a separate python file read all people from starwars_people.json
- Upload people who were at least in 3 films to the /main_characters endpoint on crudcrud
- Change Darh Vader's name to Anakin Skywalker on the /main_characters endpoint
- Upload all males to /male and everyone else to /female
- Remove from /female every character with the gender "n/a"
- Send me your crudcrud id
