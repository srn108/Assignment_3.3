# Assignment_3.3
# To mplement a function longestWord() that takes a list of words and returns the longest one.

from functools import reduce

listofwords=[]

def longestWord(listofwords):
    return reduce((lambda a,b:b if len(b)>len(a) else a),listofwords)
    
#listofwords need to assigned before calling the function
longestWord(listofwords)
