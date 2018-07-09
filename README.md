class GetSet 
{
	int regno;
	String city;
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
	}

	public static void main(String[] args) 
	{
		GetSet obj = new GetSet();
		obj.setRegno(4258);
		obj.setCity("bangalore");
		obj.display();
	}
}
