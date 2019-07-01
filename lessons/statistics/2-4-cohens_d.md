[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

>> REPLACE THIS TEXT WITH YOUR RESPONSE
Exercise 1:
First and other babies are born relatively near each other in terms of time frame. The most common week to be born in is the 39th week. The left tail is more gradual to grow, whereas the right tail has a steep drop.

Do first babies arrive late? It's kind of a strange question to answer, only in the sense that late is in reference to an accepted generality. Supposedly, babies are to be expected in 37 weeks. The reality according to the histogram that was introduced, is that babies are more often born in 39 weeks, that's for both first and succeeding babies. So, if your definition of arriving late relies on the 37 weeks being the expected time, then yes. And for that matter, most babies would be late. But if you gear your thinking to the average (39 weeks) then no. First babies arrive in general on time, just like their succeeding siblings.

Exercise 2:
See jupyter notebook

Exercise 3:
def mode(hist):
    """
    Given a hist dictionary, return the mode of the hist.
    """
    
    return max(hist, key=hist.get)
    
 Exercise 4:
 This question is asked in Exercise 2.
