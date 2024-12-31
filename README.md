Key Explanations:
Initialization (__init__):

The input string is stored as an instance variable so the object can access it later.
An empty string self.encoded_string is used to store the encoded result.
Encoding Logic:

Uses a loop to process the input string character by character.
Counts consecutive occurrences of characters and formats them as char+count (e.g., a3).
Helper Method (get_encoded):

Checks if the encoding is already done (self.encoded_string).
If not, it triggers the encode() method.
User Interaction:

The input() function is used to let the user provide the string.
An object is created with this string, and encoding is performed using the class method.
