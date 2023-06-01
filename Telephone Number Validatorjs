function telephoneCheck(str) {
  let regularExp = /^1?[\s-]?(?:\(\d{3}\)|\d{3})[\s-]?\d{3}[\s-]?\d{4}$/;

 
 if  (regularExp.test(str) === true && typeof str === 'string') {
  return true;
  }else{
    return false;
  }
 }



console.log(telephoneCheck("5555555555")); 


"Examples:"
"555-555-5555"
"1 555-555-5555"
"5555555555"
"555-555-5555"
"(555)555-5555"
"1(555)555-5555"
"1 555 555 5555"
"1 456 789 4444"
