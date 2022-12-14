# Dequelicious
In this project, a deque or double-ended queue Java class is implemented using two different underlying implementations. The first is with a doubly linked list where the linked list structure is also implemented from scratch. The second implementation uses Java's built in arrays. Lastly, an interface is created allowing both to be used interchangably. 

## Deque API
The interface and both deque classes implemented the following methods:
<ul> <li><code class="language-plaintext highlighter-rouge">public void addFirst(T item)</code>: Adds an item of type <code class="language-plaintext highlighter-rouge">T</code> to the front of the deque.</li> <li><code class="language-plaintext highlighter-rouge">public void addLast(T item)</code>: Adds an item of type <code class="language-plaintext highlighter-rouge">T</code> to the back of the deque.</li> <li><code class="language-plaintext highlighter-rouge">public boolean isEmpty()</code>: Returns true if deque is empty, false otherwise. </li> <li><code class="language-plaintext highlighter-rouge">public int size()</code>: Returns the number of items in the deque.</li> <li><code class="language-plaintext highlighter-rouge">public void printDeque()</code>: Prints the items in the deque from first to last, separated by a space. Once all the items have been printed, print out a new line.</li> <li><code class="language-plaintext highlighter-rouge">public T removeFirst()</code>: Removes and returns the item at the front of the deque. If no such item exists, returns null.</li> <li><code class="language-plaintext highlighter-rouge">public T removeLast()</code>: Removes and returns the item at the back of the deque. If no such item exists, returns null.</li> <li><code class="language-plaintext highlighter-rouge">public T get(int index)</code>: Gets the item at the given index, where 0 is the front, 1 is the next item, and so forth. If no such item exists, returns null. </li> </ul>

### LinkedListDeque
In addition to the aforementioned methods, the linked list deque also implements:
<ul> <li><code class="language-plaintext highlighter-rouge">public LinkedListDeque()</code>: Creates an empty linked list deque.</li> <li><code class="language-plaintext highlighter-rouge">public T getRecursive(int index)</code>: Same as get, but uses recursion.</li> </ul>

### ArrayDeque
In addition to the aforementioned methods, the array deque also implements:
<ul> <li><code class="language-plaintext highlighter-rouge">public ArrayDeque()</code>: Creates an empty array deque.</li> </ul>
