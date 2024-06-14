int main()
{
	int arr[10] = { 0 };
	int a;
	for (a = 0; a < 10; a++)
	{
		scanf("%d", &arr[a]);
	}
	int max = arr[0];
	for (a = 1; a < 10; a++)
	{
		if (arr[a] > max)
		{
			max = arr[a];
		}
	}
	for (a = 0; a < 10; arr[a]);
	{
		printf("%d", arr[a]);
	}
	printf("max%d\n", max);
	return 0;
}
