# Information-Security-Basics-HW1

## Assignment Goals

The main tasks for this assignment include:

- Developing the four AES round transformations: **Add Round Key**, **Byte Substitution**, **Shift Rows**, and **Mix Columns**.
- Sequentially applying these transformations to perform one round of AES-128 encryption on a given plaintext block.

This implementation represents a reduced version of AES-128, performing only a single encryption round rather than the full ten rounds specified by the AES standard.

## Implementation

The key AES transformations are as follows:

1. **add_round_key**: This step combines the current state with the round key using the XOR operation, which blends the key into the encryption.
2. **sub_bytes**: Each byte in the state matrix is substituted with a new value from the AES S-box, adding complexity to the transformation.
3. **shift_rows**: The rows of the state matrix are moved by different amounts to improve the mixing of information between columns.
4. **mix_columns**: The data in each column is mixed together using Galois Field multiplication to ensure better spreading of information.

## Requirements for Submission

- Include the correct ciphertext produced after applying the transformations.
- Provide the source code of the four round transformations in the PDF file containing your homework answers; do not submit this code as a separate file.
