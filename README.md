# JS2SHACL - JSON Schema to SHACL conversor

JS2Shacl is a document conversor, makes conversions from JSON Schema to SHACL Schema (Turtle format).

- https://js2shacl.onrender.com/

### Installation

JS2Schacl requires [Node.js](https://nodejs.org/) to run.

```
$ npm install
```

### Executation

```sh
# Convert the especified file in /inputSchemas
# example: $ node app.js CaseStudy-GlobalSchema.json
$ node app.js <filename in /inputSchemas>
```

or

```sh
# Convert all files in /inputSchemas
$ node app.js -a
```

or if you want the tool running on a website on your computer (localhost:8080)

```sh
# Start the server in localhost:8080
$ node app.js
```

### Output

All analyzed files will be saved in the /outputSchemas folder, and a conversion log in the /outputLog folder.
