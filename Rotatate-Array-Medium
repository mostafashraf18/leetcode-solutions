# Intuition
first i thought i can do it be making two array and coping to them, iwill just copy the reversed number in an array and i will copy the res number in another array and then compine them to each othe but it 
didn't go as planned, it was a headache and too expensive in memory and also complex as f***.

# Approach
my approch here is to use itrations module to decrease the number of iterations i had to do to reverse the number.

and then reverse the whole array first and then reverse the begining numbers with last number + k(k%n)
and then reverse the beginnig + k with the end();

# Complexity
- Time complexity:
 $$O(n)$$ 

- Space complexity:
$$O(1)$$

# Code
```cpp []
class Solution {
public:
    void rotate(vector<int>& nums, int k) {
        int n = nums.size();
        k %=n;
        reverse(nums.begin(), nums.end());
        reverse(nums.begin(), nums.begin()+ k);
        reverse(nums.begin()+k, nums.end());
    }
};
```
