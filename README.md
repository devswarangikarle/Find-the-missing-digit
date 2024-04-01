# Find-the-missing-digit
You are given a string S of length 9 which contains digits only (0 to 9). All digits appear exactly once in S. You need to find and print the digit which is missing. Input The input consists of a string. S  Constraints S is a string of length 9 consisting of digits. All characters in S are distinct. Output Print the only digit missing in S.

def find_missing_digit(S):
    for i in range(10):
        if str(i) not in S:
            return i

S = input().strip()

missing_digit = find_missing_digit(S)
print(missing_digit)
