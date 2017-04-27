# lab4
# ------------------------------partA--------------------------------
* 0000000000400555 T main
* 000000000040052d T _Z7averageif
* 00000000004004ed T _Z7averagePdRd

# ------------------------------partB--------------------------------
# Output:
* 1 8
* 4 8
* 4 8
* 8 8
# Reason:
* In 32 bits computer,to save a character we need only 1 byte.
* To save a integer we need 4 bytes.
* To save a float we need 4 bytes.
* To save a double we need 8 bytes.
* However, when we need to save a pointer,it takes space of 8 bytes,no matter what kind of data the pointer  points to.
