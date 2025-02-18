# experiment 4

https://leetcode.com/problems/rotate-string/submissions/1546989391
## Rotate a string 

class Solution {
public:
    bool rotateString(string s, string goal) {
        if (s.length() != goal.length()) return false;
        return (s + s).find(goal) != string::npos;
    }
};



https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/submissions/1546978768
# Find the Index of the First Occurrence in a String
class Solution {
public:
int strStr(string haystack, string needle) {
return haystack.find(needle);
}
};
