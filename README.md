# March_Intake
# Day 1
```
//Data Types and Variables
void main(){
 int age =23;
 String name ='Ram';
 double salary=90000.78;
 bool isMarried = false;
 List<String> hobbies =['Coding','Swimming'];
 Map<String,String> familyMembers={
    'father':'RamLal',
    'mother':'HariKala'
  };
 print(age);
  print(name);
  print(salary);
  print(isMarried);
  print(hobbies);
  print(familyMembers);
}
```
```
//Data Types and Variables
void main(){
 int age =23;
 String name ='Shyam';
 double salary=90000.78;
 bool isMarried = false;
 List<String> hobbies =['Coding','Swimming'];
 Map<String,String> familyMembers={
    'father':'RamLal',
    'mother':'HariKala'
  };
print("Hello my name is $name I am $age years old. I make around $salary every month and my hobbies are $hobbies. And my maritial status is $isMarried and my family members are: $familyMembers");
}
```
```
void main(){
 List<String> myData =['Cat','Dog'];
 print(myData);
 print(myData[1]);
 myData.add('Cow');
  print(myData);
  myData.removeAt(1);
  print(myData);
print(myData.contains('Cat'));
print(myData.contains('Elephant'));
}
```
```
void main(){
List<Map<String,String>> families=[
  {
  'father':'RamLal',
  'mother':'Harikala'
    },
  {
    'father':'Rameshwor',
    'mother':'Nandini'
  }
];
  
  print(families.length);
  print(families[0]['father']);
  
}
```
