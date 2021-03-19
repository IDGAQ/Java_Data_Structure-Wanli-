# ArrayDeque
---

## Declare:
ArrayDeque <String> animals = new ArrayDeque<>();

## Change element:
```java
//add at the end
add(Object o)

//add at the beginning
addFirst(Object o)

//add at the end
addLast(Object o)

//offer() works the same as add()
//only difference is:
//if ArrayDeque is full, add()throws an exception, offer return false
offer()
offerFirst()
offerLast()
```

## Access:
```java
_________________________
getFirst()
getLast()

//同上,peek = get
peek()
peekFirst()
peekLast()
_________________________
//remove() = removeFirst()
//remove 1st element
remove()
removeFirst()
remove(element)
removeLast()

//remove all
clear()
_________________________
//return 1st element then remove
poll()
pollFirst()
//return last element then remove
pollLast()
_________________________
```
## Iterate:
```java
Iterator <Object> iterate = animals.iterator();
while(iterate.hasNext())
{
print(iterate.next());
}
```


