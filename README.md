#include<stdio.h>
#include<conio.h>
void main()
{

	int ch;
	
	printf("1.Pizza \n 2.Burger \n 3.Pasta \n 4.French fries \n 5.Sandwich ");
	printf("\n Enter your choice");
	scanf("%d",&ch);
	switch(ch)
	{
	   case 1:printf("food item: Pizza \n Price: 239");
	          break;
	   case 2:printf("food item: Burger \n Price: 129");
	          break;
	   case 3:printf("food item: Pasta \n Price: 179");
	          break;
	   case 4:printf("food item: French fries \n Price: 99");
	          break;
	   case 5:printf("food item: Sandwich \n Price: 149");
	          break;      
	   default:printf("invalid choice");
	   		   break;
	}
			  
}
