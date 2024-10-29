# Information-Security-Basics-HW1

## Task:

The file simple aes.c (available on Moodle) contains a simple AES128 implementation
written in the C programming language. However, the four AES 2round transformations
are not provided in the source code and still need to be implemented. Then, these four
round transformations have to be applied to the plaintext block 0123456789abcdeffed-
cba9876543210 as shown in the function aes round trans, which corresponds to encryption
with a round-reduced version of AES128 consisting of just a single round. The round key
(in hex format) is 0f1571c947d9e8590cb7add6af7f6798, but the last four bytes af7f6798
need to be replaced by the last four bytes of your student-ID number (see comments at
the beginning of the function aes round trans for an example). In order to get the full
points for this question, the correct ciphertext (after applying the four round transforma-
tions as shown in aes round trans) as well as the source code of the implementation of
the four round transformations have to be submitted. Please copy the source code of the
four round transformations into the PDF file that contains the answers of this homework,
i.e. do not attach them as a separate file. There is no strict requirement to write the
implementation of the round transformations in C, i.e. using another language like Java
or Python is permitted. However, it is not allowed to use a library that provides the AES
round transformations.
