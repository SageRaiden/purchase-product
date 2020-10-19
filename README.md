#include<stdio.h>
int main(){
	int a, chx,pr,;
	printf("Name of products / Price: \n
		1. Milo / 7php \n
		2. Energine / 10php \n
		3. Nescafe 25g. / 24php \n
		4. coffee mate 25g/ 25 php\n\n");
	printf("Enter Purchase:");
	scanf("%d",&chx);

	switch(chx){
	case 1: printf("Enter Payment: ");
		scanf("%d", &a);
		if(a>=7){
		pr= a- 7;
		printf("Change: %d php", pr);
		} else printf("Invalid Input");
	break;
	case 2: printf("Enter Payment: ");
		scanf("%d", &a);
		if(a>=10){
		pr= a- 10;
		printf("Change: %d php", pr);
		} else printf("Invalid Input");
	break;
	case 3: printf("Enter Payment: ");
		scanf("%d", &a);
		if(a>=24){
		pr= a- 24;
		printf("Change: %d php", pr);
		} else printf("Invalid Input");
	break;
	case 4: printf("Enter Payment: ");
		scanf("%d", &a);
		if(a>=25){
		pr= a- 25;
		printf("Change: %d php", pr);
		} else printf("Invalid Input");
	break;
}


return 0;
}
