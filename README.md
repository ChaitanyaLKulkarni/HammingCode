# HammingCode

---

Hamming code Genreation and Checker 

Steps:
  * [Step 1](https://github.com/ChaitanyaLKulkarni/HammingCode/blob/master/hammingCode.py#L80).Get input bits from user.
  * [Step 2](https://github.com/ChaitanyaLKulkarni/HammingCode/blob/master/hammingCode.py#L5).Calculate how many extra redundant bits needed.
  * [Step 3](https://github.com/ChaitanyaLKulkarni/HammingCode/blob/master/hammingCode.py#L12).Place 0s at the position of parity bits
  * [Step 4](https://github.com/ChaitanyaLKulkarni/HammingCode/blob/master/hammingCode.py#L35).Set Correct parity for those position.
    * [Step 4.1](https://github.com/ChaitanyaLKulkarni/HammingCode/blob/master/hammingCode.py#L40).Go through all bits, if its an parity bit then set it by **XOR** all the bits where its _position bits_ **bitwise and** _other bit position_ is equal to _its position bit_

---

## Detecting Error

* [Step 1](https://github.com/ChaitanyaLKulkarni/HammingCode/blob/master/hammingCode.py#L99).Set one random bit to flip.
* [Step 2](https://github.com/ChaitanyaLKulkarni/HammingCode/blob/master/hammingCode.py#L58).Detect Error:
    * [Step 2.1](https://github.com/ChaitanyaLKulkarni/HammingCode/blob/master/hammingCode.py#L63).Calculate parity bits for given bits
    * [Step 2.2](https://github.com/ChaitanyaLKulkarni/HammingCode/blob/master/hammingCode.py#L75).It will give position of _Incorrect Bit_
