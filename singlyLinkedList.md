Singly Linked List definition
1. a data structure that contains a head, tail, and lenght property. 
2. linked list consist of nodes, and each node has a value and a pointer to another node or null.

-only one direction 
-ONEWAY 



+--+---------------------+----------------------------------+
|  |         List        |              Arrays              |
+--+---------------------+----------------------------------+
+--+---------------------+----------------------------------+
|  |        NO IDX       |                IDX               |
+--+---------------------+----------------------------------+
|  | connected via nodes |      insertion and deletion      |
|  |   w/ a next pointer |          can be expensive        |
+--+---------------------+----------------------------------+
|  |   NO random access  | quick access at the specific IDX |
+--+---------------------+----------------------------------+