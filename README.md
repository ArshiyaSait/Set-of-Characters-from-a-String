# Set-of-Characters-from-a-String
def strip_chars(string, chars):
    return "".join(c for c in string if c not in chars)
original_string = "The quick brown fox jumps over the lazy dog."
print("\nOriginal String:")
print(original_string)
chars_to_strip = "aeiou"
print("\nAfter stripping a, e, i, o, u:")
print(strip_chars(original_string, chars_to_strip))
OUTPUT:
Original String:
The quick brown fox jumps over the lazy dog.

After stripping a, e, i, o, u:
Th qck brwn fx jmps vr th lzy dg.

