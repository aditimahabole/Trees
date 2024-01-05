![WhatsApp Image 2023-12-28 at 11 39 24_e22b1d79](https://github.com/aditimahabole/Trees/assets/78752342/bd267df1-7ac0-43e9-87db-45fd1a4a83cb)

**8.Balanced Tree**

**Link** : https://www.geeksforgeeks.org/problems/check-for-balanced-tree/1

**Explain** : 
- Find left height and right height for each node
- then height should be <=1 then only its balanced 
- and it should be for each node so call 
- isBalanced(root->left) and similarly call isBalanced(root->right)
- all these are true then return 1 means yes it is balanced
