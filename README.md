# Palindrome
def isPalindrome(s):
    if len(s) == 1 or len(s) == 0:
        return True
    elif s[0] == s[-1] and len(s) >= 2:
        s = s[1:-1]
        isPalindrome(s)
    else: return False
    
  
