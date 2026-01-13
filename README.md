# 35.-comma-separated-sequence-
items = input("Input comma separated sequence of words")
words = [word for word in items.split(",")]
print(",".join(sorted(list(set(words)))))
OUTPUT:
Input comma separated sequence of wordsabcd
abcd
