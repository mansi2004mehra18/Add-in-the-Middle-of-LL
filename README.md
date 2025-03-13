# Add-in-the-Middle-of-LL

in linklist copy step are not there.
they are in arrays and arraylist.

for linkage process/step it takes only constant time.
but here for finding index takes n time . therefore its time compixity is O(n).

but in array and arraylist we know index , but due to copy step it takes n time, i.e time compixity O(n)

addFirst is used for changing the head.

add(index, data)   [O(n)]

Node temp = head
i=0
while(i< idx-1) {
    temp ---->(points to ) next
    i++
}

temp(prev) 
1: newNode.next = temp.next
2: temp.next = newNode