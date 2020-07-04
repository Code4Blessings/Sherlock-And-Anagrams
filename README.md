# Sherlock-And-Anagrams
Two strings are anagrams of each other if the letters of one string can be rearranged to form the other string. Given a string, find the number of pairs of substrings of the string that are anagrams of each other.

For example s = mom, the list of all anagrammatic pairs is [m,m],[mo,mo] at positions [[0],[2]], [[0,1],[1,2]] respectively.

### Function Description

Complete the function sherlockAndAnagrams in the editor below. It must return an integer that represents the number of anagrammatic pairs of substrings in .

sherlockAndAnagrams has the following parameter(s):

- s: a string.

### Input Format

The first line contains an integer , the number of queries.
Each of the next  lines contains a string  to analyze.

1 <= q <= 10
2 <= |s| <= 100

String s contains only lowercase letters  ascii[a-z].

### Output Format

For each query, return the number of unordered anagrammatic pairs.

### Sample Input 0

```

2
abba
abcd

```

### Sample Output 0

``` 

4
0

```