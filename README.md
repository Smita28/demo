# demo
package com.lara;

import static org.junit.Assert.assertEquals;

import java.util.HashMap;

import org.junit.Test;

public class TestJunit
{
	static String s = "Hello World";
	

@Test
public static void testprintMap(HashMap<String,String> hm)
{
	/*SortOnKey sok=new SortOnKey(s);*/

	HashMap<String,String> t=new HashMap<String,String>();
	t.put("1", "one");
	assertEquals("l",SortOnKey.printMap(t));
	
	 System.out.println(s);
     
	
}

}
