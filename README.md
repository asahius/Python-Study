# Python-Study
A Private Site To learn Python

# This file will add some Python Exercises to learn Python.

#code like Below

class SpecialString:
  def __init__(self,cont):
    self.cont=cont
  
  def __truediv__(self,other):
    line = "="* len(other.cont)
    return "\n".join([self.cont,line,other.cont])

spam = SpecialString("spam")
hello = SpecialString("Hello World")
print(spam/hello)
