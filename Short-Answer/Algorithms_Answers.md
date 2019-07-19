Add your answers to the Algorithms exercises here.

#Exercise Ia

a = 0
a) while a < n^2
    a = a + n^2

    n = 0 O(1)
    n = 1 a = 1 0(1)
    n = 2 a = 4 0(1)

#Answer Exercise a: 0(1) time complexity, 0(1) space complexity

#Exercise Ib
n = 5

i = 0  next i = 2 next i = 4
j = 1  next j = 3 next j = 5
k = 2 next  k = 4 next k = 6
l

sum = 0
    for i in range(n): #0(n)
      i += 1
      for j in range(i + 1, n):#0(n)
        j += 1
        for k in range(j + 1, n):#0(n)
          k += 1
          for l in range(k + 1, 10 + k):#0(1)
            l += 1
            sum += 1

#Answer Exercise Ib: time complexity 0(n^3), 0(1) space complexity

#exercise Ic

bunnies = 50 
next = 49



c)  def bunnyEars(bunnies):
      if bunnies == 0:
        return 0

      return 2 + bunnyEars(bunnies-1)


#Answer Exercise Ic: time complexity 0(n), 0(n) space complexity

#exercise II

n stories
floor f >= egg breaks
height < f egg good
minimize number of dropped eggs


1) Well we could start at story 0  and DROP an egg. If it does not break move up one floor. This would at best be 0(1) but probably on average O(n) time complexity.
***Not the solution***


*** If there is a distinction between thrown and dropped. This is probably not the solution**

1a) WELL we could just never DROP an EGG. We could instead start at floor 0 and THROW!!! This shares the 0(n) time complexity and you actually DROP 0 eggs!  As long as the eggs dont break when you thrown them at lower floors than f.


*** We are minimizing the number of dropped eggs not broken eggs**
***SOLUTION is 2***

2) Start on the middle story: Throw an egg , if thrown egg breaks breaks move down a floor. If it does not break move up a floor. Dropped eggs == 0.

Time complexity O (1/2n). Best time complexity O(1)








