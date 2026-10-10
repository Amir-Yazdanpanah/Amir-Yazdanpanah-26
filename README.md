# Amir-Yazdanpanah-26

I work on digital hardware design, computer architecture, and hardware security. This page brings together selected VHDL implementations of cryptographic primitives and a physically unclonable function (PUF).

## Cryptographic Hardware and PUF Projects

### AES-128 Architectures

These repositories contain different AES-128 hardware architectures, including encryption and decryption, with different datapath organizations and lookup-table structures.

| Repository | Implementation |
| --- | --- |
| [AES-128](https://github.com/Amir-Yazdanpanah/AES-128) | Encryption core with a 128-bit round datapath, key expansion, and round control. |
| [AES-128 Column-Based](https://github.com/Amir-Yazdanpanah/AES-128-Column-Based) | Encryption architecture that processes 32-bit columns and shares its substitution logic with key expansion. |
| [AES-128 Byte-Serial](https://github.com/Amir-Yazdanpanah/AES-128-Byte-Serial) | Encryption architecture with byte-serial substitution and key addition, using a shared 8-bit S-box. |
| [AES-128 BRAM](https://github.com/Amir-Yazdanpanah/AES-128-BRAM) | Encryption architecture using clocked lookup tables to implement SubBytes and MixColumns. |
| [AES-128 Decryption](https://github.com/Amir-Yazdanpanah/AES-128-Decryption) | Decryption core with inverse round transformations, reverse key expansion, and round control. |

### Keccak Permutation

| Repository | Implementation |
| --- | --- |
| [Keccak-f1600](https://github.com/Amir-Yazdanpanah/Keccak-f1600) | Hardware implementation of the 1600-bit Keccak permutation, with theta, rho/pi, chi/iota, and round-control modules. |

### Stream Ciphers

| Repository | Implementation |
| --- | --- |
| [Trivium](https://github.com/Amir-Yazdanpanah/Trivium) | Stream-cipher core with an 80-bit key, an 80-bit initialization vector, initialization control, and serial keystream output. |
| [A5/1 Stream Cipher](https://github.com/Amir-Yazdanpanah/A5-1-stream-cipher) | Stream-cipher datapath using three feedback shift registers, majority-controlled shifting, and serial keystream output. |

### Physically Unclonable Function

| Repository | Implementation |
| --- | --- |
| [Arbiter PUF](https://github.com/Amir-Yazdanpanah/Arbiter-PUF) | Configurable challenge-controlled switch chain with a NAND-latch arbiter and response-ready signal. |

