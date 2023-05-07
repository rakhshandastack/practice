class Laptop{
  String? name ;
  String? id;
  int? ram;
  display(){

  
  print("NAME:  $name");
  print("ID :  $id");
  print("RAM : $ram GB");
  }

}
  import 'Laptop.dart';
  
  void main(){

  var lp= Laptop();
  lp.name = "Macbook";
  lp.id= "Macbook pro 13";
  lp.ram=24 ;
  print(lp.display());


var lp1= Laptop();
  lp1.name = "Notebook";
  lp1.id= "Honor Magic 14";
  lp1.ram= 32 ;
  print(lp1.display());

var lp2= Laptop();
  lp2.name = "Chromebook";
  lp2.id= "ChromeOS";
  lp2.ram= 4 ;
  print(lp2.display());

  }



class Laptop{
  String? name ;
  String? id;
  int? ram;
  display(){

  
  print("NAME:  $name");
  print("ID :  $id");
  print("RAM : $ram GB");
  }

}


