# FCCEverythingBeTrue
For freecodecamp


function truthCheck(collection, pre) {
  return collection.every(elem => elem.hasOwnProperty(pre) && Boolean(elem[pre]));
}

truthCheck([{"user": "Tinky-Winky", "sex": "male"}, {"user": "Dipsy", "sex": "male"}, {"user": "Laa-Laa", "sex": "female"}, {"user": "Po", "sex": "female"}], "sex");
