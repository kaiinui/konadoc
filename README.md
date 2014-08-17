Konadoc
=======

Konadoc generates well-designed documents for Java codes.

![](https://dl.dropboxusercontent.com/u/7817937/_github/_kcc_topseal.jpg)

It will generates documents from Javadoc compatible documentation syntax.

```java
/**
 * Removes the object at the top of this stack and returns that object. 
 * @return  The object at the top of this stack.
 * @exception  NoSuchElementException  if this stack is empty.
 */
public Object pop() throws NoSuchElementException{
    int length = this.elements.size();
	  if (length == 0) throw new NoSuchElementException();
	  return this.elements.remove(length - 1);
}
```
