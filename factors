#!/usr/bin/python3
import sys
file = open(sys.argv[1], "r")
for Num in file:
    if Num == "\n":
        break
    Number = int(Num)
    for factor_1 in range(2, int(Number / 2) if Number > 10 else int(Number - Number / 4)):
        factor_2 = Number / factor_1
        if factor_2 - int(factor_2) == 0:
            print("{:d}={:d}*{:d}".format(Number, int(factor_2), factor_1))
            break
