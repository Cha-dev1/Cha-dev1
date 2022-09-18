


//In Ascending

let looparr=[1,5,87,45,8,8]


for(i=0; i<=looparr.length; i++){
  
  for(j=i+1; j<looparr.length;j++){
    
    if(looparr[i]>looparr[j])
      {
        
        let temp=looparr[i];
        looparr[i]=looparr[j];
        looparr[j]=temp;
        
      }
    }
  }
console.log(looparr);
///Descending Form

let looparr1=[1,5,87,45,8,8]


for(i=0; i<=looparr1.length; i++){
  
  for(j=i+1; j<looparr1.length;j++){
    
    if(looparr1[i]<looparr1[j])
      {
        
        let temp=looparr1[i];
        looparr1[i]=looparr1[j];
        looparr1[j]=temp;
        
      }
    }
  }
console.log(looparr1);
