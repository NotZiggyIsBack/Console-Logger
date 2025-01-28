# Console-Logger
Log stuff in new console window :)

# CODE
```js
const { exec } = require("child_process");

function logg(message) {
  const command = `start cmd /k "echo ${message} & echo. & echo Press any key to exit... & pause >nul & exit"`;
  exec(command);
}

//Example usage
logg("Hello there :)")
```
