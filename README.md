# Number-of-Integers-With-Popcount-Depth-Equal-to-K-II
Link: https://leetcode.com/contest/weekly-contest-459/problems/number-of-integers-with-popcount-depth-equal-to-k-ii/submissions/1715217572/

🧠 What’s “Popcount-Depth”?
For any number x, define:

p0 = x

p1 = popcount(p0) → number of 1s in binary

p2 = popcount(p1)

...repeat until you hit 1

🧨 Popcount-depth of x is how many steps it takes to reach 1.

Example: x = 7 → 111 → popcount = 3 → 11 → popcount = 2 → 10 → popcount = 1 Depth = 3

📥 Query Types
You're given:

nums: list of integers

queries: array of queries in two formats:

[1, l, r, k]: count how many nums[j] in [l,r] have depth = k

[2, idx, val]: update nums[idx] = val
