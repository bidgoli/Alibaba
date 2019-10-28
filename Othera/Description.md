# Book Build for Othera
---------
It's a short assessment I did for othera. Here is the description:

### Bookbuild Task

Given a list of LOANS, and a list of INVESTORS, the task is produce an output showing which INVESTORS can be assigned to which LOANS, to fill all loans.
We can assume that there is sufficient money in the INVESTORS to pay for all LOANS.

eg. If LOANS = [2000, 7000, 8000, 6000, 4000],
and INVESTORS = [3000, 2000, 9000, 5000, 6000, 8000, 3000, 5000]
One possible distribution of LOAN_INVESTORS: [[0], [0, 1, 2], [2, 3], [3, 4], [4, 5]]

Here, LOAN_INVESTORS is a list (same length as LOANS) showing which investors are filling it (starting from a 0-index on the INVESTORS list)
That is, the first loan ($2000) is filled by the first investor (0), the second by the first three investors (0,1,2), the third loan by the third and fourth investor (2,3),
and so on.

Feel free to provide an answer in any way that suits, but there's no need to overthink
this task.

You can also assume that LOANS and INVESTORS are provided in a form that suits.
