# "Trio"
"Three" member group
Clarence Cheng and Kevin Lin
# To Do
- Add addFirst(Card e)
- Add removeFirst()
- Add peekFirst()
- Add addLast(Card e)
- Add removeLast()
- Add peekLast()
# Explanations
We chose to implement the adding, removing, and peeking methods for both ends of
the array because those methods are similar to the methods we have created for
other types of queues.
We are choosing to use a node-based architecture because the only parts of the
list we need access to are the front and the end. There will be no need to copy
over the list every time its size limit is reached, because there is no size
limit. Dequeuing is also faster, since elements do not have to be shifted over,
like they do in an array or ArrayList.
