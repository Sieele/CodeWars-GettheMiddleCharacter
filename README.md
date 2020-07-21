# CodeWars-GettheMiddleCharacter
Second attempt at CodeWars

function getMiddle(str){
    const length = str.length
        if (length === 1){
          return str;         
        }
  return length % 2 === 1 ? str.split ('')[Math.ceil((length / 2)- 1)]
                          : str.split ('')[(length / 2) - 1] + str.split ('')[(length / 2)];
  
  }
