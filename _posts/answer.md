hack 2

ArrayList<String> color = new ArrayList<>(); 
color.add("red apple");
color.add("green box");
color.add("blue water");
color.add("red panda");


for(int i = color.size() - 1; i >= 0; i--) 
{
        if(color.get(i).contains("red"))
        {
                color.remove(i);      
        }
        
}
System.out.println(color);

hack 3

ArrayList<Integer> num = new ArrayList<Integer>(); 

num.add(5);
num.add(1);
num.add(3);

int sum = 0;
for (int number: num) {
  sum += number; 
}
System.out.print(sum);
