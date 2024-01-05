![WhatsApp Image 2023-12-27 at 14 43 17_42d11b39](https://github.com/aditimahabole/Trees/assets/78752342/3d2a39a1-4945-4ce1-973f-f0c3be54a7c3)

**2.Minimum Depth of Tree (S&P Globals)**

**Link** : https://leetcode.com/problems/minimum-depth-of-binary-tree

Explain :
-> Using DFS and Recurrsion

if node is NULL means no tree means no depth 😂 obvio
if node ka left is NULL and also node ka right is also NULL
means that is a leaf node so we are returning 1 as this could be our answer . returning 1 means returning the height , so after returning 1 it will do 1+1 and
then this is returned to the prev call this is how recurssion is working .

if we have node ka right but not left so simply move to right part
and dont forget to add 1 , we are increasing the depth at every step
If node ka right does not exist but left does exist then simply mode to left part and add +1 

Now if the node has both left and right node present 
so we have to return the minimum depth of both the subtrees right?!
so find the depth of left subtree by moving left 
similarly find depth of right subtree 
return the minimum of both the trees .
