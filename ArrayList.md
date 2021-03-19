# ArrayList
---

```java
import java.util.ArrayList;
```

## Declare:
```java
ArrayList <String> cars = new ArrayList <String>();
```

## Add Element:
```java
cars.add("Volve");
cars.add("BMW");
```

## Access(and Return):
```java
cars.get(0);

contains(Object element);

indexOf(Object O);

lastindexOf(Ojbect O);

toArray();
```

## Change an item:
```java
cars.set(0, "Opel");

cars.add(int index, Object element);

//往 cars 里面加入 collection 的所有元素
cars.addAll(int index, Collection C);

//不使用index时，默认末尾
cars.addAll(Collection C);
```

## Length:
```java
cars.size();
```

## Loop:
```java
//regular loop
for(int i=0;i<cars.size();i++)
{
  System.out.print(cars.get(i));
}

//for-each
for(String i:cars)
{
  System.out.println(i);
}
```

## unusual ones:
```java
ensureCapacity(int minCapacity);

//trims the size to the number of elements
//ex: if (list.size()=4), but only has 2 items
trimToSize();

isEmpty();
```
