# Data_Structure

# Assignment 1
# 
# I created My own LinkedNode Class just like LinkedList class. 
# And, I created bubble sort and shell sort. 
#
# Assignment 2
# I created Huffman Algorithm.
#
# Assignment 3
#
# I found the more effective way of hashing for String than Java's API.
# Initially, I set my hashcode as 7 and multiply with 23. Those numbers are prime 
# numbers; therefore, I was able to avoid some  collisions as I use them. 
# Then, I added the result with multiplication of integer value of ASCII character 
# and order of alphabet, then mod by table size, which is also prime number as shown below. 
# I ended up with 1365 primary collisions. Since java's API has O(log(n)) runtime, log(25027) = 14.
# It means collision happens every 14 words are placed.
# But, my function gives that collision happens every 18 words are placed (25027 / 1365 = 18).
# It proves that my function performed better than O(log(n)). For handling the secondary 
# collisions, I used the way of quadratic probing.
# So, I ended up 1598 total collisions for 25027 words.
