# Torsdagsopgave2
cph-mb743@cphbusiness.dk
Mikkel Dam Binau


//TASK 1: Functions
/*
void setup(){
  mikkel();
  mikkelstring("bøh"); 
  mikkelSetup("Mikkel", 29);  
}

void mikkel(){
  
  println("Hello from the method");
  
}
//parameter
void mikkelstring(String mikkel){
  
  println(mikkel);
 
}

void mikkelSetup(String name, int age){

println("My name is " + name + " I am " + age + " years old.");


}

////////////////////////////////////////////////////////////////////////////////////////////////////

//TASK 2: Functions' return types
/*
boolean happy = true;

 void setup() {
   if (iAmHappy())
   {
     println("I clap my hands");
   }
   else
   {
     println("I don't clap my hands"); 
   }
}

boolean iAmHappy(){
  // fill out what is missing here: 
  return happy;
}


///////////////////////////////////////////////////////////

void setup(){
  int sum = mikkelGrades(10,5); 
   println("The sum of grades is = " + sum); 
}
//parameter
int mikkelGrades(int grade1, int grade2){
return grade1 + grade2;
}

/////////////////////////////////////////////////////////////


void setup(){
  String mikkel = "mikkel"; 
  println(mikkel.toUpperCase()); 
}


/////////////////////////////////////////////////////////////
String mikkel = "mikkel";
void setup(){
}
void draw(){

  if (true) { 
    println(mikkel.toUpperCase()); 
  if (false)
    println("mikkel");
  }
}
/////////////////////////////////////////////////////////////
*/


//TASK 3 - STUDENT

class Student{
//Variabler
String name;
String isFemale;
String datamatikerTeam;
int age;

//Student constructor
Student(String tmpName, String tmpIsFemale, String tmpDatamatikerTeam, int tmpAge){

name = tmpName;
isFemale = tmpIsFemale;
datamatikerTeam = tmpDatamatikerTeam;
age = tmpAge;


}
}

