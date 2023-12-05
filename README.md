# vishrutha.github.io
Program 1(easy)
1. Given a string s consisting of words and spaces, return the length of the last word in the string.
A word is a maximal 
substring consisting of non-space characters only.

Constraints:
1 <= s.length <= 104
s consists of only English letters and spaces ' '.
There will be at least one word in s.


CODE:
def length_of_last_word(s): 
                       
    words = s.split()  # Split the string into words
    # Check if there are any words
    if not words:
        return 0
    # Return the length of the last word
    return len(words[-1])

s = input()     #Give the input string
result = length_of_last_word(s)   #call the function to find length of last word
print(result)    
