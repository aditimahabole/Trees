![WhatsApp Image 2023-12-27 at 14 03 46_ad8ee4b5](https://github.com/aditimahabole/Trees/assets/78752342/aa55bf85-b7b6-452b-a2a1-258a007c2c8e)

**1.Height of Binary tree Level Order**

-> Using Level order Traversal
-> Queue Data Structure

**Process:**

Take a queue of Node* type
push the root node in it and along with it push a NULL
a NULL represents that level has ended
Make a max_height variable initialize to 0

loop will run until q is not empty
store the front element in a variable(mine name is front_ele) and pop the front element of queue.

if front element is not empty like if its 1 or 2 or something but not NULL then check if it has left ele , if yes then push to q ,
do the same with right , if present then push

if front_ele is NULL means level ended so increment max_height

also check if queue is not empty then add NULL to it at last.

