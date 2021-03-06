# Silverman's Sequence or Golomb Sequence

"In mathematics, the Golomb sequence, named after Solomon W. Golomb (but also called Silverman's sequence), is a non-decreasing integer sequence where an is the number of times that n occurs in the sequence, starting with a1 = 1, and with the property that for n > 1 each an is the unique integer which makes it possible to satisfy the condition. For example, a1 = 1 says that 1 only occurs once in the sequence, so a2 cannot be 1 too, but it can be, and therefore must be, 2. The first few values are

    1, 2, 2, 3, 3, 4, 4, 4, 5, 5, 5, 6, 6, 6, 6, 7, 7, 7, 7, 8, 8, 8, 8, 9, 9, 9, 9, 9, 10, 10, 10, 10, 10, 11, 11, 11, 11, 11, 12, 12, 12, 12, 12, 12 (sequence A001462 in OEIS).

a1 = 1
Therefore 1 occurs exactly one time in this sequence.
a2 > 1
a2 = 2
2 occurs exactly 2 times in this sequence.
a3 = 2
3 occurs exactly 2 times in this sequence.
a4 = a5 = 3
4 occurs exactly 3 times in this sequence.
5 occurs exactly 3 times in this sequence.
a6 = a7 = a8 = 4
a9 = a10 = a11 = 5
etc."

Let us see a python code to implement the same.
