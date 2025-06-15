# Conjecture:
For any integer n that has 5 as the last digit, n^2 will have 25 as the last two digits.

## Proof attempt 1:
Let n be an integer with 5 as the last digit.

Then n = k + 5, for some integer k that is an integer multiple of 10.

n^2 = (k + 5)(k + 5) = k^2 + 10k + 25 = k(k + 10) + 25

Because k is some multiple of 10, we know that the number ends with 25.


## Proof attempt 2:
Let n be an integer with 5 as the last digit.

Then n = 5 + 10j for some integer j.

Then n^2 = (5 + 10j)^2 = 25(1 + 2j)^2

2j + 1 is the definition of an odd number. The square of an odd number is always odd.

case 1: j is 0, then n^2 is 25
case 2: j is 1 or greater, then you have 25 times some integer >= 9.

Because the number either 0 or odd and greater or equal to 9, n^2 must end in 25.

## Proof attempt 3:
Let n be an integer with 5 as the last digit.

Then n = 10j + 5 for some integer j

Therefore:

n^2 = (10j + 5)(10j + 5) = 100j^2 + 100j + 25
                         = 100j(j + 1) + 25

let l = j(j + 1)
then we have n^2 = 100l + 25

which is to say that n^2 ≡ 25 (mod 100)

Since congruence mod 100 preserves the last two decimal digits, n^2 ends in 25.
