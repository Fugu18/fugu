# Condorcet's jury theorem using Numpy

https://en.wikipedia.org/wiki/Condorcet%27s_jury_theorem

(numpy.array([(p**i *(1-p)**(n-i))*(math.factorial(n)/(math.factorial(i)*math.factorial(n-i))) for i in range(n)[1:]])*([True if x>int(0.5*n) else False for x in range(n)[1:]])).sum()
