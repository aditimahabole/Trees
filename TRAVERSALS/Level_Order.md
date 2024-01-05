![WhatsApp Image 2023-12-27 at 15 12 45_9ffb0432](https://github.com/aditimahabole/Trees/assets/78752342/b0fdb71b-53af-4d31-afd1-d7b55da58178)

**Level order Traversal**

**Link** : https://leetcode.com/problems/binary-tree-level-order-traversal/

**Explain** :
- use Queue
- add root node and then add NULL denoting level 1 
- NULL represents end of a level 
- if front element is NULL then and the temp array to ans array denoting levels 
- if front element is not NULL then add its left and right if present 
- if front ele is NULL then also check that if q is not empty then add NULL to it denoting end of that level .
