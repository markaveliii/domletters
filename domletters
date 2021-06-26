#!/usr/bin/python3
import sys
from collections import Counter

def dlc(words):
    if not words:
        return 0
    sum = 0
    for word in words:
        sum += count_dl(word)

    return sum

def count_dl(word):
    if not word:
        return 0
    if not word.isalpha():
        return 0

    counted = Counter(word)
    return max(counted.values())



def main():
    words = sys.stdin.read()
    words = words.upper()
    words = words.split()

    print(dlc(words))

if __name__ == "__main__":
    main()
