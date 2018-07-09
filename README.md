class GetSet 
{
	int regno;
	String city;
	int marks;
	public void setRegno(int x)
	{
		regno = x;
	}
	public void setCity(String y)
	{
		city =  y;
	}
	public int getRegno()
	{
		return regno;
	}
	public String getCity()
	{
		return city;
	}
	public void display()
	{
		System.out.println(regno);
		System.out.println(city);
		System.out.println(marks);
	}

	public static void main(String[] args) 
	{
		GetSet obj = new GetSet();
		obj.setRegno(4258);
		obj.setCity("bangalore");
		obj.setMarks(925);
		obj.display();
	}
}
