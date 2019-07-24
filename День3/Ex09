#include <stdio.h>

void sort_integer_table (int *tab, int size)
{
	int index = 0;
	int temp;
	while (index < size)
	{
		if (tab[index] == tab[size-1])
			break;					        
		if(tab[index] > tab[index+1])
		{
			temp = tab[index+1];
			tab[index+1] = tab[index];
			tab[index] = temp;
			index = 0;
		}
		else
			index++;
	}
}
int main()
{
	int array[4] = {3,2,1,0};
	printf("%d %d %d %d\n", array[0],array[1],array[2],array[3]);
	ft_sort_integer_table (&array, 4);
	printf("%d %d %d %d\n", array[0],array[1],array[2],array[3]);  
	return 0;
}
