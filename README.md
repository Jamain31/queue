# queue
I utilized the queue function by creating a Java program that uses the add(), element(), offer(), peek(), and poll() methods for the queue function.

import java.util.Queue;
import java.util.LinkedList;
public class queueExample {

	public static void main(String[] args) {
		
		Queue<String> myLine = new LinkedList<String>();
		
		myLine.add("Bobby");
		myLine.add("Malcome");
	    myLine.add("Cindy");
	    myLine.add(" Mindy");
	    
	    System.out.println(myLine);
	    
	    myLine.poll();
	    
	    System.out.println(myLine);
	    
	    myLine.poll();
	    
	    System.out.println(myLine.peek());
	    
	    
	    System.out.println(myLine.offer("Max"));
	    
	    System.out.println(myLine.element());
	    
	    System.out.println(myLine);
	    
	    
		
				

	}

}
![queueexample](https://user-images.githubusercontent.com/108758588/196001588-96516135-9f44-4304-a5a1-9c2244b267b9.png)
