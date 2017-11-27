

```python
# Program for finding longest common prefix 

def longestCommonPrefix(s1, s2):
    i = 0
    while i < len(s1) and i < len(s2) and s1[i] == s2[i]:
        i += 1
    return s1[:i]
longestCommonPrefix('ACCGGACTT', 'ACCATTTG')
```




    'ACC'




```python
def reverseComplement(s):
    complement = {'A': 'T', 'C': 'G', 'G': 'C', 'T': 'A'}
    t = ''
    for base in s:
        t = complement[base] + t
    return t
reverseComplement('CCTAAGA')
```




    'TCTTAGG'




```python
def reverseNewComp(a):
    complement = {'A' : 'T', 'C' : 'G', 'T': 'A', 'G' : 'C'}
    c = ''
    for dna in a:
        c = complement[dna]+ c
    return c
reverseNewComp('CCGTAAA')
```




    'TTTACGG'




```python

```
