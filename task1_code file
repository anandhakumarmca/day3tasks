let obj1 = {name: "Person1", age: 5};
let obj2 = {age: 5 , name: "Person1" };

//create compare function
function compareObjects() {

  // Check if the number of keys is the same
  if (Object.keys(obj1).length !== Object.keys(obj1).length) {
    return false;
  }

  // Check if all keys in obj1 are present in obj2
  for (let key of Object.keys(obj1)) {
    if (!obj2.hasOwnProperty(key)) {
      return false;
    }
    //console.log( Object.keys(obj1));
    //console.log( Object.keys(obj2));
  }

  // Check if the values of the keys are the same
  for (let key of Object.keys(obj1)) {
    if (obj1[key] !== obj2[key]) {
      return false;
    }
    //console.log(obj1[key]); 
    //console.log(obj2[key]);
  }

  return true;
}

// call the comparing Funcion  
let areEqual = compareObjects();
console.log(areEqual);//display the result in console
