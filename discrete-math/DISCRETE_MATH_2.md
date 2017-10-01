## Finding Examples, Computer Search, Optimality

### How to find an example
  - We have stated that one example is enough to prove an existential statement, but of course we need to find this example
  - Sometimes it's difficult to find the example
  - Following are some examples and trick that can be used
  - Magic Squares
    - Table with numbers, sum is the same for all four columns, rows, and the two diagonals
    - Combinatronics, permutations of nine 9 digits 9 x 8 x ... x 1 = 362,880
  - Multiplicative Magic Squares
    - Cannot use sequential
    - Product to be used
    - Seven appears in some products, exponentiation, additive square to multiplicative
  - More puzzles
    - Simple but shows different side
    - Six-digit number starting by 100 and divisible by 9127
  - Ex. Find an integer n such that n^2 = 31415
    - Finite decimal fraction is enough
    - (10x)^2 = 100x^2
    - square root (31415) = 177.242771
    - 177.242771^2 = 31414.9998
    - shift decimal on left over three position, six position on right
      - 177.243^2 = 31415.081049 (six positions)
  - Integer Linear Combination
    - Ex. Image a country with 7/13 florin coins. Two people each have many coins of each type. Can one pay florin to the other?
      - 6 = 13 -7 
      - How about one florin?
        - 2(7) - 13 = 1
      - Bottom up approach or 7 - 6 =1  ~ capitalize what you already know
      - 7x + 13y = c has integer solutions
