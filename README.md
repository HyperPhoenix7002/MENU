#include<stdio.h>
main()
{
	int ch;
	printf("pick a choice:");
	scanf("%d",&ch);
	
	switch (ch)
	{
		case 1:
            printf("Food Item: FRENCH FRIES\n Price:99");
	    break;
	    
	    case 2:
	        printf("Food Item: BURGER\n Price: 129 ");
	        break;
	    
	    case 3: 
	        printf("Food Item: SANDWICH\n Price: 149");
	        break;
	    
	    case 4:
	        printf("Food Item: PASTA\n Price: 179");
	        break;
	        
	    case 5:
	    	printf("Food Item: PIZZA\n Price: 239");
	    	break;
	    	
	    deafult:
		    printf("invalid");	
	    	
	    
	}
	
	
}
	
