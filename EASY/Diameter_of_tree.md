![WhatsApp Image 2023-12-27 at 19 25 46_cd16f2ab](https://github.com/aditimahabole/Trees/assets/78752342/32ae615b-c7f5-4a8c-b072-4b3ba3cadf31)

**7.Diameter of Tree**
->Number of nodes in the Longest path
->It is not necessary that longest path passes via root only
->It can pass through any node

**Link** : https://practice.geeksforgeeks.org/problems/diameter-of-binary-tree/1

**Explanation** : 
- we have to find the longest height of left tree and right tree from each node
- then do 1+lh+rh for each node and return maximum among them.
- In code ans is max of 1+lh+rh and the function is returning the maximum of left height , right height as we need maximum height from a node only
