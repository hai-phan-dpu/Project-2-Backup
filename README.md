# Project-2-Backup

You are working for a company that expects to be hired to solve several problems related to queues where
each item in the queue is a string. The company expects to need an augmented type of a queue that
supports “cut” and “bail” operations in addition to the standard queue operations. Cut inserts a new entry
into the front of the queue, whereas bail removes and returns the entry at the rear of the queue. A cut and
bail queue is more properly called a deque.

Because the maximum size of the queue is unknown, you will be implementing the cut bail queue using a
pointer-based data structure.

Ten functions implemented in this project:
1. int CBQueue::getSize() const
2. bool CBQueue::isEmpty() const 
3. void CBQuue::enqueue(string s) 
4. void CBQueue::printF2B() const 
5. void CBQueue::printB2F() const 
6. string CBQueue::dequeue()
7. void CBQueue::cut(string s) 
8. string CBQueue::bail()
9. void CBQueue::B2F() 
10. bool CBQueue::equals(CBQueue otherQ) const
