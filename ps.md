# GROKKING NOTES

I liked the way Grokking the coding interview organized problems into learnable patterns. However, the course is expensive and the majority of the time the problems are copy-pasted from leetcode. As the explanations on leetcode are usually just as good, the course really boils down to being a glorified curated list of leetcode problems.

So below I made a list of leetcode problems that are as close to grokking problems as possible.

## Pattern: Sliding Window

* https://leetcode.com/problems/maximum-subarray/ 
* https://leetcode.com/problems/minimum-size-subarray-sum/
* https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/
* https://leetcode.com/problems/fruit-into-baskets/
* https://leetcode.com/problems/longest-substring-without-repeating-characters/
* https://leetcode.com/problems/longest-repeating-character-replacement/
* https://leetcode.com/problems/max-consecutive-ones-iii/
* https://leetcode.com/problems/permutation-in-string/
* https://leetcode.com/problems/find-all-anagrams-in-a-string/
* https://leetcode.com/problems/minimum-window-substring/
* https://leetcode.com/problems/substring-with-concatenation-of-all-words/

## Pattern: Two Pointers

* https://leetcode.com/problems/two-sum/
* https://leetcode.com/problems/remove-duplicates-from-sorted-array/
* https://leetcode.com/problems/squares-of-a-sorted-array/
* https://leetcode.com/problems/3sum/
* https://leetcode.com/problems/3sum-closest/
* https://leetcode.com/problems/3sum-smaller/
* https://leetcode.com/problems/subarray-product-less-than-k/
* https://leetcode.com/problems/sort-colors/
* https://leetcode.com/problems/4sum/
* https://leetcode.com/problems/backspace-string-compare/
* https://leetcode.com/problems/shortest-unsorted-continuous-subarray/

## Pattern: Fast & Slow pointers
* https://leetcode.com/problems/linked-list-cycle/
* https://leetcode.com/problems/linked-list-cycle-ii/
* https://leetcode.com/problems/happy-number/
* https://leetcode.com/problems/middle-of-the-linked-list/
* https://leetcode.com/problems/palindrome-linked-list/
* https://leetcode.com/problems/reorder-list/
* https://leetcode.com/problems/circular-array-loop/

## Pattern: Merge Intervals
* https://leetcode.com/problems/merge-intervals/
* https://leetcode.com/problems/insert-interval/
* https://leetcode.com/problems/interval-list-intersections/
* https://leetcode.com/problems/meeting-rooms-ii/
* Could not find equivalent. Given a list of intervals with values, find the peak sum (i.e. if intervals are overlapping, sum their values)
* https://leetcode.com/problems/employee-free-time/

## Pattern: Cyclic Sort

* Couldn't find equivalent for the first question. The second question below encompasses the first one though. See https://leetcode.com/problems/missing-number/discuss/859510/C%2B%2B-O(N)-O(1)-using-Cyclic-Sort for how grokking the coding interview approached these problems. It uses the fact that we can sort the array in O(n) without comparison operators
* https://leetcode.com/problems/missing-number/
* https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/
* https://leetcode.com/problems/find-all-duplicates-in-an-array/
* combine https://leetcode.com/problems/find-the-duplicate-number/ and https://leetcode.com/problems/missing-number/
* https://leetcode.com/problems/first-missing-positive/
* https://leetcode.com/problems/kth-missing-positive-number/

## Pattern: In-place Reversal of a LinkedList
* https://leetcode.com/problems/reverse-linked-list/
* https://leetcode.com/problems/reverse-linked-list-ii/
* https://leetcode.com/problems/reverse-nodes-in-k-group/
* Next question is the same, but alternate each subgroup
* https://leetcode.com/problems/rotate-list/

## Pattern: Tree Breadth First Search
* https://leetcode.com/problems/binary-tree-level-order-traversal/
* https://leetcode.com/problems/binary-tree-level-order-traversal-ii/
* https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/
* https://leetcode.com/problems/minimum-depth-of-binary-tree/
* https://leetcode.com/problems/inorder-successor-in-bst/  # Close, not exact
* https://leetcode.com/problems/populating-next-right-pointers-in-each-node/  # Close, grokk assumes non-perfect tree
* Next question is the same, but connect end nodes to the next level instead of null
* https://leetcode.com/problems/binary-tree-right-side-view/

## Pattern: Tree Depth First Search
* https://leetcode.com/problems/path-sum/
* https://leetcode.com/problems/path-sum-ii/
* https://leetcode.com/problems/sum-root-to-leaf-numbers/
* https://leetcode.com/problems/check-if-a-string-is-a-valid-sequence-from-root-to-leaves-path-in-a-binary-tree/description/
* https://leetcode.com/problems/path-sum-iii/
* https://leetcode.com/problems/diameter-of-binary-tree/
* https://leetcode.com/problems/binary-tree-maximum-path-sum/

## Pattern: Two Heaps
* https://leetcode.com/problems/find-median-from-data-stream/
* https://leetcode.com/problems/sliding-window-median/
* https://leetcode.com/problems/ipo/
* https://leetcode.com/problems/find-right-interval/

## Pattern: Subsets
* https://leetcode.com/problems/subsets/
* https://leetcode.com/problems/subsets-ii/
* https://leetcode.com/problems/permutations/
* https://leetcode.com/problems/letter-case-permutation/
* https://leetcode.com/problems/generate-parentheses/
* https://leetcode.com/problems/generalized-abbreviation/
* https://leetcode.com/problems/different-ways-to-add-parentheses/
* https://leetcode.com/problems/unique-binary-search-trees-ii/
* https://leetcode.com/problems/unique-binary-search-trees/

## Pattern: Modified Binary Search
* https://leetcode.com/problems/binary-search/  # Close enough. The grokking problem allows sorted input arrays as ascending or descending, which only introduces a simple check
* Did not find. Problem is find index of smallest element greater or equal to input value
* https://leetcode.com/problems/find-smallest-letter-greater-than-target/
* https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/
* https://leetcode.com/problems/search-in-a-sorted-array-of-unknown-size/
* https://leetcode.com/problems/find-k-closest-elements/ (with K == 1)
* https://leetcode.com/problems/peak-index-in-a-mountain-array/
* https://leetcode.com/problems/find-in-mountain-array/
* https://leetcode.com/problems/search-in-rotated-sorted-array/
* Similar to previous, but find the number of rotations of the array.

## Pattern: Bitwise XOR
* https://leetcode.com/problems/single-number/
* https://leetcode.com/problems/single-number-iii/
* https://leetcode.com/problems/complement-of-base-10-integer/
* https://leetcode.com/problems/flipping-an-image/

## Pattern: Top 'K' elements
* Same as second question, but the first Grokking question wants the top K instead of the bottom K
* https://leetcode.com/problems/kth-largest-element-in-an-array
* https://leetcode.com/problems/k-closest-points-to-origin/
* https://leetcode.com/problems/minimum-cost-to-connect-sticks/
* https://leetcode.com/problems/top-k-frequent-elements/
* https://leetcode.com/problems/sort-characters-by-frequency/
* https://leetcode.com/problems/kth-largest-element-in-a-stream/
* https://leetcode.com/problems/find-k-closest-elements/
* https://leetcode.com/problems/least-number-of-unique-integers-after-k-removals/ closest leetcode or https://www.geeksforgeeks.org/maximum-distinct-elements-removing-k-elements/ for exact
* https://www.geeksforgeeks.org/sum-elements-k1th-k2th-smallest-elements/ no leetcode equivalent found
* https://leetcode.com/problems/reorganize-string/
* https://leetcode.com/problems/rearrange-string-k-distance-apart/
* https://leetcode.com/problems/task-scheduler/
* https://leetcode.com/problems/maximum-frequency-stack/

## Pattern: K-way merge
* https://leetcode.com/problems/merge-k-sorted-lists/
* Same as previous, but return the Kth smallest number
* https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/
* https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/
* https://leetcode.com/problems/find-k-pairs-with-smallest-sums/ small difference, grokking has different sort order and wants the largest

## Pattern: 0/1 Knapsack
* https://www.educative.io/courses/grokking-dynamic-programming-patterns-for-coding-interviews/RM1BDv71V60
* https://www.educative.io/courses/grokking-dynamic-programming-patterns-for-coding-interviews/3jEPRo5PDvx or https://leetcode.com/problems/partition-equal-subset-sum/
* https://www.educative.io/courses/grokking-dynamic-programming-patterns-for-coding-interviews/3j64vRY6JnR
* https://leetcode.com/problems/last-stone-weight-ii/ similar concept, but problem description is more abstract.
* https://leetcode.com/problems/combination-sum-ii/ similar, but return the number of combinations instead of the combinations
* https://leetcode.com/problems/target-sum/
* BONUS : Not in grokking, but I still found this very useful https://leetcode.com/problems/ones-and-zeroes/

## Pattern: Topological Sort
* First problem is identical to the following three
* https://leetcode.com/problems/course-schedule/
* https://leetcode.com/problems/course-schedule-ii/ 
* Same as above, but return all instead of any
* https://leetcode.com/problems/alien-dictionary/
* https://leetcode.com/problems/sequence-reconstruction/description/
* https://leetcode.com/problems/minimum-height-trees/

## Misc
* https://leetcode.com/problems/kth-largest-element-in-an-array/


----------------------------------------




ول اكتر ٩ techniques حليت بيهم مسأل علي leetcode و دول مسأل لكل technique


لو حد حابب يعرف كل technique اللينك دا كويس 
https://lnkd.in/dFTwNfbH

1- two pointers 
 https://lnkd.in/dnC-a3qU
 
https://lnkd.in/dbi7D-y4

 https://lnkd.in/dtWxM67G

 https://lnkd.in/dT7G-CHM

2- sliding windows

 https://lnkd.in/dyXvvGGp

 https://lnkd.in/d_JZreVa

 https://lnkd.in/drNGF5F2

 https://lnkd.in/dAEGFAEk

 https://lnkd.in/dVcESTcM

3-0/1 knapsack (Dynamic Programming)

 https://lnkd.in/dsVpFYUb

 https://lnkd.in/d6YsD_Ti

4- Fast and slow pointers 

 https://lnkd.in/dsUPf8aN

 https://lnkd.in/dC3uxKTe

 https://lnkd.in/d3ycsGcH

5- merge intervals 

 https://lnkd.in/dDJgQFJv

 https://lnkd.in/dKy36fjx

6- in- place reversal of linkedlist

 https://lnkd.in/d9btzCDt

 

7- breadth-first search

 https://lnkd.in/d7Bv4HVk

 https://lnkd.in/dB89d5YW

8-Depth first search 

 https://lnkd.in/dNDJ9vuh

 https://lnkd.in/dceYPpU3

9-Bottom-Up (Dynamic Programming) 

 https://lnkd.in/dney-xxX

 https://lnkd.in/dqKkn_vN



ودول مقابلونيش كتير في الحل بس مهمين تعرفهم لل interviews 

1- k-way merge 

 https://lnkd.in/dWJiyx7p

2- two heaps 

 https://lnkd.in/dSaa4kSH

3- cyclic sort

 https://lnkd.in/diaccEPg


this is my account on leetcode :
https://lnkd.in/dsQnizTJ






ال sliding window من ال concepts اللي قابلتني كتير وانا بحل علي Leetcode و بيجي كتير في الانترفيوهات فا حبيت اقولكوا علي اكتر patterns لل sliding window

و دايما بيكون ليها keywords في المسأل بتقدر تساعدك انك تعرف ان المسألة دي sliding window
زي
"(Longest/Shortest/Number of) (Substrings/Subarrays) with (At most/Exactly) K elements .

وفي الاغلب دايما بيكون time complexity O(N)

و دا من اهم الاسباب ان احنا بنستخدم الtechnique دا هو ان الحل بيكون linear و مش بتحتاج تعمل nested loop

ودا فيديو بشرح فيه ازاي ال sliding window قدرت تخليه من O(N*K) ل 0(N)


لينك الفيديو :
https://lnkd.in/epKq97r7

طيب الsliding window ساعات بتكون fixed sized window و variable sized window

طيب ايه الفرق
1- ال fixed sized window : هو بيكون معرفك مقاس ال window في المسألة و انت بتحل علي اساسه

ودي فيديو بشرح فيه ال fixed size window
https://lnkd.in/epKq97r7

و دي مسأل عن ال fixed sized window :

1-https://lnkd.in/dAEGFAEk

2-https://lnkd.in/d-hdK5ji

3-https://lnkd.in/egeSZYmW

4-https://lnkd.in/djSiZUYT

5-https://lnkd.in/em32-SR4

6-https://lnkd.in/eFjZvZKX

7-https://lnkd.in/eVQid6AP


2- ال variable sized window : هو مش بيعرفك مقاس ال window بيديلك condition وانت اللي بتحدد مقاس الwindow بال 2 pointers

دا فيديو بشرح فيه الconcept

لينك الفيديو:
https://lnkd.in/dXupAvN2

و دي مسال لل variable sized window:

1-https://lnkd.in/d_JZreVa

2-https://lnkd.in/euBFC7Ap

3-https://lnkd.in/drNGF5F2

4-https://lnkd.in/eSsQ7kAm

5-https://lnkd.in/e2JFjAqu

6-https://lnkd.in/e6XxEmEv

7-https://lnkd.in/e3PKCjjc


و دي مسأل تبان انها sliding window بس هي مش بتتحل بنفس ال pattern

1- https://lnkd.in/ehurv7Df. (Dynamic programming)

2-https://lnkd.in/ehVynbiY (prefix sum)



ودي لينك القناة بينزل عليها حلول المسأل اللي في الشيت دا
لينك القناة :
https://lnkd.in/dV3mQqhe

ودا لينك الشيت :
https://lnkd.in/dy8Ck52D


و شكرا لكل الناس اللي عملت contribute ونزلت حلول بلغات مختلفة

ودا لينك ويب سايت لو في مسأل premium علي leetcode تقدر تلاقيها عليه اغلب المسأل كنت بلاقيها
https://www.lintcode.com/

ودا لينك جروب بنساعد في الناس في problem solving

https://lnkd.in/eR_6STFf