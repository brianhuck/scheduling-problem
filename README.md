# scheduling-problem
I solve a scheduling problem as an integer program using google's ortools package in Python.

My goal for this script is to address an ops research problem that is a bit more abstract. The practice problem comese from the book 'Ops Research: Applications and Algorithms 3rd ed,' by Wayne L. Winston on page 74

Problem: A maintenance shop requires different number of maintainers on different
days.  The number required is:
    
    Mon  17
    Tue  13
    Wed  15
    Thu  19
    Fri  14
    Sat  16
    Sun  11

Policy states that each airman must work five consecutive days then get two
days off.  Minimize the total number of airmen per shop.
