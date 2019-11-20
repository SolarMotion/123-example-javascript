# Javascript examples
List of JS examples. <br/><br/>

## Check value is empty for string & number
```
function isEmpty(value){
  if(value){
    if(typeof(value) == 'number' && value > 0)
      return false;
    else if(typeof(value) == 'string' && value.trim())
      return false;
    else 
      return true;
  }
  return true;
}
```
