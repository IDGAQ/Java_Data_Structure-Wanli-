# Queue
---

## Declare:
```java
Queue<MyObject> queue = new LinkedList<MyObject>();
Queue<Integer> q = new ArrayDeque<Integer>();
```

## Access:
```java
//add = offer
//但是，if false，add throws exception, offer doesn't. 但是，abstractQ 和 PQ的 add 又是不一样。哎。
add(Object)
offer(Object)

//remove = poll，但是。。。
// remove top
remove()
poll()

//element = peek，但是。。。
//但是。。。
element()
peek()

//remove all
clear()

//return size
size()

contains(Object)
```

## Iterate
```java
Iterator<String> iterator = queue.iterator();

//access via Iterator
while(iterator.hasNext()
{
  String element = iterator.next();
}

//for-each
for(String element : queue) {
    //do something with each element
}
```
---


# Priority Queue
#### (also called as PQ, heap, 优先队列，or 完全二叉树）
#### 完全二叉树的条件：
#### 1.除了最后一层，其他层都排满了
#### 2.最后一层的所有非空节点都排在左边
![Optional Text](https://raw.githubusercontent.com/IDGAQ/Super_Cool_Notes/main/Screen%20Shot%202021-03-22%20at%202.41.04%20AM.png)
![Optional Text](https://raw.githubusercontent.com/IDGAQ/Super_Cool_Notes/main/Screen%20Shot%202021-03-22%20at%202.41.42%20AM.png)
![Optional Text](https://raw.githubusercontent.com/IDGAQ/Super_Cool_Notes/main/Screen%20Shot%202021-03-22%20at%202.42.15%20AM.png)


## Declare:
```java
PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();
```
---



# Heap
![Optional Text](https://raw.githubusercontent.com/IDGAQ/Super_Cool_Notes/main/Screen%20Shot%202021-03-22%20at%202.33.33%20AM.png)



# Keep updating ⬇️

## siftup()
## siftdown()
## graph of PQ tree
## IC questions such as Top-K
## Everything else the same