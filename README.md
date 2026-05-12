# ll_insert-at-end_new_node
code for insert at end a new node in ll

class Node:
    def __init__(self, data):
        self.data = data
        self.next = None




n1=Node(3)
n2=Node(4)
n3=Node(5)

n1.next=n2
n2.next=n3

new_node=Node(6)

head=n1
curr=head
while curr is not  None:
    if curr.next is None:
        
        
        
       curr.next=new_node
       break
    curr=curr.next
curr=head
while curr is not None:
    print(curr.data,end=" ")
    if curr.next is not None:
        print("->",end=" ")
    curr=curr.next
    


    


