# SI671 - HW3 Peer-assessed Exam Question

+ **Question (Multiple Choices)**:

  Note that in *Levenshtein Edit Distance*, we define a single-character edit with 3 different operations: insertions, deletions and substitutions. Sometimes a substitution can be replaced with a deletion and insertion. So we now define a new Edit Distance with only two operations: insertions, deletions. Can you find out which of the following has the shortest distance with our newly defined Edit Distance to the target word "change"?

  + A: challenge
  + B: challenging
  + C: challenger
  + D: changing

+ **Answer**: A

+ **Explanation**:

  For A, it requires 3 deletions.

  For B, it requires 6 deletions and 1 insertion.

  For C, it requires 4 deletions.

  For D, it requires 3 deletions and 1 insertion.

  So A "challenge" has the shortest distance to target word "change" in our newly defined Edit Distance.