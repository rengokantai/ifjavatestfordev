#### orjavatestfordev
#####dynamic testing tools
######junit
four params:  
```
@Test @Ignore
assertEquals("desc" , 1.4141D, sqrt(2))  //bad, and will fail
@Test
assertEquals("desc" , 1.4141D, sqrt(2),0.0001D)
```
Test exception
```
@Test(exceped=IndexOutOfBoundException.class)
public void testCheck(){
  new StringBuilder().insert(-1,"desc");
}
```
