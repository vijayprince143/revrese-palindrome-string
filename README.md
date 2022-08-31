# revrese-palindrome-string
#palindrome strings
def ispal(n):
    for i in range(len(n)):
        if n[i]!=n[len(n)-i-1]:
            return False

    return True
n= input()
if ispal(n):
    print(n,"is palindrome")
else:
    print(n," is not palindrome")
