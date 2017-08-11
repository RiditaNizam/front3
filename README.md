# front3
CodingBat Java Warmup-1 Question #12

Given a string, we'll say that the front is the first 3 chars of the string. If the string length is less than 3, the front is whatever is there. Return a new string which is 3 copies of the front.

public String front3(String str) {
  
  String answerString = "";
  
  for(int i = 0; i < 3; i++){

    if(str.length()>=3){
      answerString += str.substring(0,3);
    }

    else{
      answerString += str;
    }
    
  }
  
  return answerString;
  
}
