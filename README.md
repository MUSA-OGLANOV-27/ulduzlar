# ulduzlar
Console.Write("Reqemi daxil edin: ");
int reqem = Convert.ToInt16(Console.ReadLine());

for(int i=1;i<=reqem;i++)
{
    for(int o=0;o<i;o++)
    {
        Console.Write("* ");
    }
    for(int k=reqem;k>i;k--)
    {
       
      
            Console.Write("  ");
        
        
    }
    for(int l=reqem;l>i;l--)
    {
        Console.Write("  ");
    }
    for(int n=0;n<i;n++)
    {
        Console.Write("* ");
    }

    Console.WriteLine();
}

for(int q=1;q<=reqem;q++)
{
    for(int w=reqem;w>=q;w--)
    {
        Console.Write("* ");
    }
    for(int a=1;a<q;a++)
    {
        Console.Write("  ");
    }
    for(int s=1;s<q;s++)
    {
        Console.Write("  ");
    }
    for(int d=reqem;d>=q;d--)
    {
        Console.Write("* ");
    }

    Console.WriteLine();
}
