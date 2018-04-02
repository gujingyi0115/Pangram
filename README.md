

import string

def ispangram(str1, alphabet=string.ascii_lowercase):
    str1=str1.lower()
    for i,c in enumerate(alphabet):
        if c not in set(str1):
            return False
            break
    else:
        return True
