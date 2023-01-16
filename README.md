# Candy-Castle




import java.util.Scanner;

import java.util.*;

class Chocolates
{
	String Shop_Name = "CandyCastle";
	private String Owner_Name = "Mr._.Rayyan";
	private long Owner_Mob_No = 8169505463l;
	String Shop_Address ="Khadakpada,Godrejhill O6pp to Dmart,kalyan(West)";
	long Shop_Mob_No = 7400074441l;
	String Shop_Mail_Id = "raycastle@gmail.com";
	String Greetings = "Thankuhh for supporting my small business.";
	
	public long getOwner_Mob_No() {
		return Owner_Mob_No;
	}
		
	public String getOwner_Name() {
		return Owner_Name;
	}
}

class  MilkChocolates extends Chocolates {
	public void MilkChocolates1(){
		//System.out.println("1)Hersheys Milkchoc 2)Classic Milkchoc 3)Almond Milkchoc 4)Swiss Milkchoc");
		System.out.println("1)Hersheys Milkchoc ");
		System.out.println("2)Classic Milkchoc ");
		System.out.println("3)Almond Milkchoc ");
		System.out.println("4)Swiss Milkchoc");
		Scanner s = new Scanner(System.in);	
		int choice = s.nextInt();
		switch(choice)
		     {
		        case 1: HersheysMilkchoc t = new HersheysMilkchoc();
		        System.out.println("Selected choice : Hersheys Milkchoc");
		        t.HersheysMilkchoc1();
		        break;
		        
		        case 2: ClassicMilkchoc t1 =new ClassicMilkchoc();
		        System.out.println("Selected choice : Classic Milkchoc");
		        t1.ClassicMilkchoc1();
		        break;
		     
		        case 3: AlmondMilkchoc t3 =new AlmondMilkchoc();
		        System.out.println("Selected choice : Almond Milkchoc");
		        t3.AlmondMilkchoc1();
		        break;
		        
		        case 4: SwissMilkchoc t4 =new SwissMilkchoc();
		        System.out.println("Selected choice : Swiss Milkchoc");
		        t4.SwissMilkchoc1();
		        break;
		        
		       default:System.out.println("Invalid Choice");
		     }
		  } 
	}

class HersheysMilkchoc extends MilkChocolates {
	String name= "Hersheys Milkchoc";
	double price = 285;
	public  void  HersheysMilkchoc1(){
		  System.out.println("Please enter quantity in pieces");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolate:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolate:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolate:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolate:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolate:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolate:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}
}

class ClassicMilkchoc extends MilkChocolates {
	String name= "Classic Milkchoc";
	double price = 250;
	public  void ClassicMilkchoc1() {
			System.out.println("Please enter quantity in pcs");
			  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
			  Scanner a=new Scanner(System.in);
			  double choice = a.nextDouble();
			  if ( choice == 1){   
				  double b = choice*price;
				  System.out.println("Selected Chocolates:"+name);
				  System.out.println("Ordered Quantity:"+choice +"pc");
				  System.out.println("Price:"+ b +"/-");
		     }
			  else if (choice==2){
				  double b = choice*price;
				  System.out.println("Selected Chocolates:"+name);
				  System.out.println("Ordered Quantity:"+choice +"pcs");
				  System.out.println("Price:"+ b +"/-");				
		      }
			  else if (choice==3){
				  double b = choice*price;
				  System.out.println("Selected Chocolates:"+name);
				  System.out.println("Ordered Quantity:"+choice +"pcs");
				  System.out.println("Price:"+ b +"/-");
		      }
		     else if (choice==4) {
		    	  double b = choice*price;
		    	  System.out.println("Selected Chocolates:"+name);
		    	  System.out.println("Ordered Quantity:"+choice +"pcs");
		    	  System.out.println("Price:"+ b +"/-");
		      }
		      else if (choice==5){
		    	  double b = choice*price;
		    	  System.out.println("Selected Chocolates:"+name);
		    	  System.out.println("Ordered Quantity:"+choice +"pcs");
		    	  System.out.println("Price:"+ b +"/-");
		      }
		      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
		    	  double b = choice*price;
		    	  System.out.println("Selected Chocolates:"+name);
		    	  System.out.println("Ordered Quantity:"+choice +"pcs");
		    	  System.out.println("Price:"+ b +"/-");
		      }
		      else{
		    	  System.out.println("Invalid Input");
		      }
			  	  System.out.println("***************************************************");
			      CustomerDetails ref22 = new CustomerDetails();
				  ref22.detials1();
		}
}


class AlmondMilkchoc extends MilkChocolates {
	String name= "Almond Milkchoc";
	double price = 300;
	public  void AlmondMilkchoc1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}
}

class SwissMilkchoc extends MilkChocolates{
	String name= "Swiss Milkchoc";
	double price = 350;
	public  void SwissMilkchoc1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}
}


class  Darkchocolates extends Chocolates {
public  void Darkchocolates1(){
		
		//System.out.println("1)Hersheys Dark 2)Amul Dark 3)Bournville Dark 4)Toblerone Dark");
		System.out.println("1)Hersheys Dark");
		System.out.println("2)Amul Dark ");
		System.out.println("3)Bournville Dark");
		System.out.println("4)Toblerone Dark");
		
		Scanner s = new Scanner(System.in);
		
		   int choice = s.nextInt();
		     switch(choice)
		     {
		        case 1: HersheysDark t = new HersheysDark();
		        System.out.println("Selected choice : Hersheys Dark ");
		        t.HersheysDark1();
		        break;
		        case 2: AmulDark t1 =new AmulDark();
		        System.out.println("Selected choice : Amul Dark");
		        t1.AmulDark1();
		        break;
		        case 3: BournvilleDark t2 =new BournvilleDark();
		        System.out.println("Selected choice : Bournville Dark");
		        t2.BournvilleDark1();
		        break;
		        case 4: TobleroneDark t3 =new TobleroneDark();
		        System.out.println("Selected choice :Toblerone Dark");
		        t3.TobleroneDark1();
		        break;
		       
		       default:System.out.println("Invalid Choice");
		     }
		  } 
}

class HersheysDark extends Darkchocolates {
	String name= "Hersheys Dark" ;
	double price = 300;
	public  void HersheysDark1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}
}

class AmulDark extends Darkchocolates {
	String name= "Amul Dark";
	double price = 200;
	public  void AmulDark1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}
}

class BournvilleDark extends Darkchocolates {
	String name= "Bournville Dark";
	double price = 300;
	public  void BournvilleDark1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	
	}
}

class TobleroneDark extends Darkchocolates {
	String name= "Toblerone Dark";
	double price = 350;
	public  void TobleroneDark1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}	
}


class  Semisweet  extends Chocolates {
	public void Semisweet1(){
		
	//	System.out.println("1)Guittard Semisweet 2) Nestle Semisweet 3)Ghirardelli Semisweet 4)Hersheys Semisweet");
		System.out.println("1)Guittard Semisweet ");
		System.out.println("2)Nestle Semisweet ");
		System.out.println("3)Ghirardelli Semisweet");
		System.out.println("4)Hersheys Semisweet");

		Scanner s = new Scanner(System.in);	
		int choice = s.nextInt();
		switch(choice)
		     {
		        case 1: GuittardSemisweet t = new GuittardSemisweet();
		        System.out.println("Selected choice : Guittard Semisweet");
		        t.GuittardSemisweet1();
		        break;
		        
		        case 2: NestleSemisweet  t1 =new  NestleSemisweet ();
		        System.out.println("Selected choice :  Nestle Semisweet ");
		        t1. NestleSemisweet1 ();
		        break;
		        
		        case 3: GhirardelliSemisweet t2 =new GhirardelliSemisweet();
		        System.out.println("Selected choice : Ghirardelli Semisweet");
		        t2.GhirardelliSemisweet1();
		        break;
		        
		        case 4: HersheysSemisweet t3 =new HersheysSemisweet();
		        System.out.println("Selected choice : Hersheys Semisweet");
		        t3.HersheysSemisweet1();
		        break;
		        
	
		       default:System.out.println("Invalid Choice");
		     }
		  }
}
class GuittardSemisweet extends Semisweet {
	String name= "Guittard Semisweet";
	double price =200 ;
	public  void GuittardSemisweet1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}
}

class NestleSemisweet extends Semisweet{
	String name= "NestleSemisweet";
	double price = 300;
	public  void NestleSemisweet1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();	
	}
}

class GhirardelliSemisweet extends Semisweet {
	String name= "Ghirardelli Semisweet";
	double price = 200;
	public  void GhirardelliSemisweet1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}
}

class HersheysSemisweet extends Semisweet {
	String name= "Hersheys Semisweet";
	double price = 300;
	public  void HersheysSemisweet1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}
}


class  Bittersweet extends Chocolates {
	public void Bittersweet1(){		
		//System.out.println("1)Callebaut 2)Ghirardelli  3)Hersheys Bitter 4)Bournville Bitter ");
		System.out.println("1)Callebaut ");
		System.out.println("2)Ghirardelli");
		System.out.println("3)Hersheys Bitter");
		System.out.println("4)Bournville Bitter");

		
		
		Scanner s = new Scanner(System.in);	
		int choice = s.nextInt();
		switch(choice)
		     {
		        case 1: Callebaut t = new Callebaut();
		        System.out.println("Selected choice : Callebaut");
		        t.Callebaut1();
		        break;
		        
		        case 2: Ghirardelli t1 =new Ghirardelli();
		        System.out.println("Selected choice : Ghirardelli");
		        t1.Ghirardelli1();
		        break;
		        
		        case 3: HersheysBitter t2 =new HersheysBitter();
		        System.out.println("Selected choice : Hersheys Bitter");
		        t2.HersheysBitter1();
		        break;
		        
		        case 4: BournvilleBitter t3 =new BournvilleBitter();
		        System.out.println("Selected choice : Bournville Bitter");
		        t3.BournvilleBitter1();
		        break;
		        
		   
		        
		       default:System.out.println("Invalid Choice");
		     }
		  }	
}

class  Callebaut extends Bittersweet {
	String name= "Callebaut";
	double price = 400;
	public  void Callebaut1() {                             
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();		
	}	
}

class  Ghirardelli extends Bittersweet {
	String name= "Ghirardelli";
	double price = 450;
	public  void Ghirardelli1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}	
}

class  HersheysBitter extends Bittersweet {
	String name= "HersheysBitter";
	double price = 300;
	public  void HersheysBitter1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}	
}

class  BournvilleBitter extends Bittersweet {
	String name= "Bournville Bitter";
	double price = 300;
	public  void BournvilleBitter1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}	
}



class  Couverture extends Chocolates {
	public void Couverture1(){		
		//System.out.println("1)Couverture Premium 2)Denali 3)Couverture Chocochips 4)Vizyon ");
		System.out.println("1)Couverture Premium");
		System.out.println("2)Denali");
		System.out.println("3)Couverture Chocochips ");
		System.out.println("4)Vizyon");
		
		Scanner s = new Scanner(System.in);	
		int choice = s.nextInt();
		switch(choice)
		     {
		        case 1: CouverturePremium t = new CouverturePremium();
		        System.out.println("Selected choice : Couverture Premium");
		        t.CouverturePremium1();
		        break;
		        
		        case 2: Denali t1 =new Denali();
		        System.out.println("Selected choice : Denali");
		        t1.Denali1();
		        break;
		        
		        case 3: CouvertureChocochips t2 =new CouvertureChocochips();
		        System.out.println("Selected choice : Couverture Chocochips");
		        t2.CouvertureChocochips1();
		        break;
		        
		        case 4: Vizyon t3 =new Vizyon();
		        System.out.println("Selected choice : Vizyon");
		        t3.Vizyon1();
		        break;
		        
		  
		        
		       default:System.out.println("Invalid Choice");
		     }
		  }	
}

class  CouverturePremium extends Couverture {
	String name= "Couverture Premium";
	double price = 550 ;
	public  void CouverturePremium1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();		
	}	
}

class  Denali extends Couverture {
	String name= "Denali";
	double price = 600;
	public  void Denali1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}	
}

class  CouvertureChocochips extends Couverture {
	String name= "Couverture Chocochips";
	double price =450 ;
	public  void CouvertureChocochips1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}	
}

class  Vizyon extends Couverture {
	String name= "Vizyon";
	double price = 600;
	public  void Vizyon1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}	
}


class  RubyChocolates extends Chocolates {
	public void RubyChocolates1(){		
		//System.out.println("1)Ruby Kitkat 2)Magnum Ruby 3)Fabelle Ruby 4)Ruby Ganache ");
		System.out.println("1)Ruby Kitkat");
		System.out.println("2)Magnum Ruby");
		System.out.println("3)Fabelle Ruby ");
		System.out.println("4)Ruby Ganache ");

		Scanner s = new Scanner(System.in);	
		int choice = s.nextInt();
		switch(choice)
		     {
		        case 1: RubyKitkat t = new RubyKitkat();
		        System.out.println("Selected choice : Ruby Kitkat");
		        t.RubyKitkat1();
		        break;
		        
		        case 2: MagnumRuby t1 =new MagnumRuby();
		        System.out.println("Selected choice : Magnum Ruby");
		        t1.MagnumRuby1();
		        break;
		        
		        case 3: FabelleRuby t2 =new FabelleRuby();
		        System.out.println("Selected choice : Fabelle Ruby");
		        t2.FabelleRuby1();
		        break;
		        
		        case 4: RubyGanache t3 =new RubyGanache ();
		        System.out.println("Selected choice : Ruby Ganache ");
		        t3.RubyGanache1();
		        break;
		        
		        
		       default:System.out.println("Invalid Choice");
		     }
		  }	
}

class  RubyKitkat extends RubyChocolates {
	String name= "Ruby Kitkat";
	double price = 250;
	public  void RubyKitkat1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}		
	
}

class  MagnumRuby extends RubyChocolates {
	String name= "Magnum Ruby";
	double price = 550;
	public  void MagnumRuby1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();		
	}		
	
}

class  FabelleRuby extends RubyChocolates {
	String name= "Fabelle Ruby";
	double price = 450;
	public  void FabelleRuby1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}		
	
}

class  RubyGanache extends RubyChocolates {
	String name= "Ruby Ganache";
	double price = 650;
	public  void RubyGanache1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}		 	
}


class WhiteCompoundChocolates extends Chocolates{
	public void WhiteCompoundChocolates1(){		
		//System.out.println("1)Morde Compound 2)Amul Compound 3)Hersheys Compound 4)Marco Compound ");
		System.out.println("1)Morde Compound");
		System.out.println("2)Amul Compound");
		System.out.println("3)Hersheys Compound");
		System.out.println("4)Marco Compound ");

		Scanner s = new Scanner(System.in);	
		int choice = s.nextInt();
		switch(choice)
		     {
		        case 1: MordeCompound t = new MordeCompound();
		        System.out.println("Selected choice : Morde Compound");
		        t.MordeCompound1();
		        break;
		        
		        case 2: AmulCompound t1 =new AmulCompound();
		        System.out.println("Selected choice : Amul Compound");
		        t1.AmulCompound1();
		        break;
		        
		        case 3: HersheysCompound t2 =new HersheysCompound();
		        System.out.println("Selected choice : Hersheys Compound");
		        t2.HersheysCompound1();
		        break;
		        
		        case 4: MarcoCompound t3 =new MarcoCompound();
		        System.out.println("Selected choice : Marco Compound");
		        t3.MarcoCompound1();
		        break;
		        
		     		        
		       default:System.out.println("Invalid Choice");
		     }
		  }	
}

class MordeCompound extends WhiteCompoundChocolates{
	String name= "Morde Compound";
	double price = 150;
	public  void MordeCompound1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();

	}		
}

class AmulCompound extends WhiteCompoundChocolates{
	String name= "Amul Compound";
	double price = 300;
	public  void AmulCompound1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();

	}		
}

class HersheysCompound extends WhiteCompoundChocolates{
	String name= "Hersheys Compound";
	double price = 350;
	public  void HersheysCompound1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();

	}		
}

class MarcoCompound extends WhiteCompoundChocolates{
	String name= "Marco Compound";
	double price = 250;
	public  void MarcoCompound1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();

	}		
}

class DarkCompoundChocolates extends Chocolates{
	public void DarkCompoundChocolates1(){		
		//System.out.println("1)Morde DrkCompound 2)Amul DrkCompound 3)Hersheys DrkCompound 4)Marco DrkCompound ");
		System.out.println("1)Morde DrkCompound");
		System.out.println("2)Amul DrkCompound");
		System.out.println("3)Hersheys DrkCompound");
		System.out.println("4)Marco DrkCompound ");

		Scanner s = new Scanner(System.in);	
		int choice = s.nextInt();
		switch(choice)
		     {
		        case 1: MordeDrkCompound t = new MordeDrkCompound();
		        System.out.println("Selected choice : Morde DrkCompound");
		        t.MordeDrkCompound1();
		        break;
		        
		        case 2: AmulDrkCompound t1 =new AmulDrkCompound();
		        System.out.println("Selected choice : Amul DrkCompound");
		        t1.AmulDrkCompound1();
		        break;
		        
		        case 3: HersheysDrkCompound  t2 =new HersheysDrkCompound();
		        System.out.println("Selected choice : Hersheys DrkCompound");
		        t2.HersheysDrkCompound1 ();
		        break;
		        
		        case 4: MarcoDrkCompound t3 =new MarcoDrkCompound();
		        System.out.println("Selected choice : Marco DrkCompound");
		        t3.MarcoDrkCompound1();
		        break;
		        
		     		        
		       default:System.out.println("Invalid Choice");
		     }
		  }	
}

class MordeDrkCompound extends DarkCompoundChocolates{
	String name= "Morde DrkCompound";
	double price = 150;
	public  void MordeDrkCompound1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();

	}		
}

class AmulDrkCompound extends DarkCompoundChocolates{
	String name= "Amul DrkCompound";
	double price = 300;
	public  void AmulDrkCompound1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();

	}		
}

class HersheysDrkCompound extends DarkCompoundChocolates{
	String name= "Hersheys DrkCompound";
	double price = 350;
	public  void HersheysDrkCompound1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();
	}		
}

class MarcoDrkCompound extends DarkCompoundChocolates{
	String name= "Marco DrkCompound";
	double price = 250;
	public  void MarcoDrkCompound1() {
		System.out.println("Please enter quantity in pcs");
		  System.out.println("1) 1 pc 2) 2 pcs 3) 3 pcs 4) 4 pcs 5) 5 pcs 6)Other");
		  Scanner a=new Scanner(System.in);
		  double choice = a.nextDouble();
		  if ( choice == 1){   
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pc");
			  System.out.println("Price:"+ b +"/-");
	     }
		  else if (choice==2){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");				
	      }
		  else if (choice==3){
			  double b = choice*price;
			  System.out.println("Selected Chocolates:"+name);
			  System.out.println("Ordered Quantity:"+choice +"pcs");
			  System.out.println("Price:"+ b +"/-");
	      }
	     else if (choice==4) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice==5){
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else if (choice != 1 || choice != 2 ||choice != 3 ||choice != 4 ||choice != 5 ) {
	    	  double b = choice*price;
	    	  System.out.println("Selected Chocolates:"+name);
	    	  System.out.println("Ordered Quantity:"+choice +"pcs");
	    	  System.out.println("Price:"+ b +"/-");
	      }
	      else{
	    	  System.out.println("Invalid Input");
	      }
		  	  System.out.println("***************************************************");
		      CustomerDetails ref22 = new CustomerDetails();
			  ref22.detials1();

	}		
}

class CustomerDetails
{
	private String name;
	private String Address;
	private long MobNo ;
	private String EmailId;


	public String getName(){
			return name;
	}

	public void setName(String name) {
			this.name = name;
	}

	public String getAddress() {
			return Address;
	}

	public void setAddress(String address) {
			Address = address;
	}

	public long getMobNo() {
			return MobNo;
	}

	public void setMobNo(long mobNo) {
			MobNo = mobNo;
	}

	public String getEmailId() {
			return EmailId;
	}

	public void setEmailId(String emailId) {
			EmailId = emailId;
	}
									

									 

public  void detials1(){

			Scanner s = new Scanner(System.in);
       		System.out.println("Please Enter Below Details: ");
       		System.out.println("Enter Your Name : ");
       		String name = s.nextLine();

       		System.out.println("Enter Your Address : ");
       		String Address = s.nextLine();

       		System.out.println("Enter Your Mobile No : ");
       		long MobNo = s.nextLong();

       		System.out.println("Enter Your Email ID : ");
       		String EmailId = s.next();
      		
			System.out.println("***************************************************");
	        
	        CustomerDetails ref =new CustomerDetails();
	        
	        ref.setName(name);
	        System.out.println("Name :"+ref.getName());
	        
	        ref.setAddress(Address);
	        System.out.println("Address :"+ref.getAddress());
	        
	        ref.setMobNo(MobNo);
	        System.out.println("Mobile No :"+ref.getMobNo());
	        
	        ref.setEmailId(EmailId);
	        System.out.println("Email ID :"+ref.getEmailId());
	        	        
	        System.out.println("You have ordered Successfully");	        
	        System.out.println("");
			System.out.println("***************************************************");

			Chocolates C1 = new Chocolates();
			System.out.println("Shop Name:"+ C1.Shop_Name);
			//System.out.println("Owner Name:"+ C1.Owner_Name);
			//System.out.println("Owner Mobile No:"+ M1.Owner_Mob_No);
			System.out.println("Shop Address:"+ C1.Shop_Address);
			System.out.println("Contact details :"+ C1.Shop_Mob_No);
			System.out.println("Mail ID:"+ C1.Shop_Mail_Id);
			System.out.println( C1.Greetings);
			
			System.out.println("***************************************************");

	}
}

public class CandyCastle {

	public static void main(String[] args) 
	{
		System.out.println("Welcome To Candy Castle (^_^)");
		System.out.println("Mingle Sweetness of Chocolates with Your Love..");
		System.out.println("Please Place Your Order Here  ");
		
		 	Scanner s=new Scanner(System.in);
		//System.out.println//("1) Milk Chocolates 2)Darkchocolates 3)Semisweet 4)Bitter Sweet 5)Couverture 6)RubyChocolates 7)WhiteCompoundChocolates"
				//+ "8)DarkCompoundChocolates" );	
		System.out.println("1)Milk Chocolates");
		System.out.println("2)Dark Chocolates");
		System.out.println("3)Semi Sweet");
		System.out.println("4)Bitter Sweet");
		System.out.println("5)Couverture");
		System.out.println("6)Ruby Chocolates");
		System.out.println("7)WhiteCompound Chocolates");
		System.out.println("8)DarkCompound Chocolates");
		
		
		
		
		int choice = s.nextInt();
		 if ( choice == 1) {
			 MilkChocolates ref = new MilkChocolates();
		     System.out.println("Selected choice : Milk Chocolates");
		     ref.MilkChocolates1();			    
		 }
		 else if (choice == 2) {
			 Darkchocolates ref2 = new Darkchocolates();
		     System.out.println("Selected choice : Dark Chocolates");
			 ref2.Darkchocolates1();	
		}
		 else if(choice == 3) {
			 Semisweet ref3 = new Semisweet();
			 System.out.println("Selected choice : Semi Sweet");
			 ref3.Semisweet1();
		 }
		 else if(choice == 4) {
			 Bittersweet ref4 = new Bittersweet();
			 System.out.println("Selected choice : Bitter Sweet");
			 ref4.Bittersweet1();
		 }
		 else if(choice == 5) {
			 Couverture ref5 = new Couverture();
			 System.out.println("Selected choice : Couverture");
	         ref5.Couverture1();
		 }
		else if(choice == 6) {
			RubyChocolates ref6 = new RubyChocolates();
			 System.out.println("Selected choice : Ruby Chocolates");
	         ref6.RubyChocolates1();
		 }
		 else if(choice == 7) {
			 WhiteCompoundChocolates ref7 = new WhiteCompoundChocolates();
			 System.out.println("Selected choice : WhiteCompound Chocolates");
	         ref7.WhiteCompoundChocolates1();
		 }
		  else if(choice == 8) {
			  DarkCompoundChocolates ref8 = new DarkCompoundChocolates();
			 System.out.println("Selected choice : DarkCompound Chocolates");
	         ref8.DarkCompoundChocolates1();
		 }
		
		  
		  else {
			 System.out.println("Invalid Input");
			 }
		 

	}
}









