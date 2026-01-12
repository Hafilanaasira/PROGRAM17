# PROGRAM17
items = input("Input comma separated sequence of words: ")
words = [word.strip() for word in items.split(",")]
print(",".join(sorted(set(words))))

output:
Input comma separated sequence of words: apple,orange,apple,grapes,orange
apple,grapes,orange
