# noir-security

### Cryptography

#### Elliptic Curves

- [BigCurve](https://github.com/noir-lang/noir_bigcurve) - operations over elliptic curves instantiated with an arbitrary prime field
- [Pairing over BLS12-381](https://github.com/ewynx/noir_bls12_381_pairing) - Pairing over BLS12-381

#### Hashes

- [Keccak256](https://github.com/noir-lang/keccak256) - Keccak256 hashes
- [MiMC](https://github.com/noir-lang/mimc) - MiMC hashes
- [Poseidon](https://github.com/noir-lang/poseidon) - Poseidon and Poseidon2 hashes
- [RIPEMD160](https://github.com/distributed-lab/noir-ripemd160) - RIPEMD160 hashes
- [SHA256](https://github.com/noir-lang/sha256) - SHA256 hashes
- [SHA512](https://github.com/noir-lang/sha512) - SHA512 and SHA384 hashes

#### Encryption

- [AES](https://github.com/TaceoLabs/noir-aes) - a (naive) implementation of AES encryption and decryption
- [ChaCha20 Implementation](https://github.com/SleepingShell/noir-chacha20) - a Noir implementation of ChaCha20 as defined by [RFC7539](https://www.rfc-editor.org/rfc/rfc7539)
- [ElGamal Encryption](https://github.com/jat9292/noir-elgamal/) - Exponential ElGamal Encryption on the Baby Jubjub curve
- [Hydra for BN254](https://github.com/TaceoLabs/noir-hydra) - symmetric encryption and decryption
- [ECIES](https://github.com/informalsystems/noir-ecies) - simple implementation of ECIES on the Baby Jubjub curve
- [ECDH](https://github.com/privacy-scaling-explorations/zk-kit.noir/tree/main/packages/ecdh) - simple implementation of ECDH on the Baby Jubjub curve

#### Signatures

- [BLS12_381 Elliptic Curve Pairing and Signature Verification Library](https://github.com/onurinanc/noir-bls-signature)
- [EdDSA](https://github.com/noir-lang/eddsa) - EdDSA signature verification
- [ECDSA](https://github.com/zkpassport/noir-ecdsa) - ECDSA (NIST and Brainpool curves) signature verification
- [JWT](https://github.com/saleel/noir-jwt) - Verification of JSON Web Tokens (JWTs) and prove claims
- [PLUME](https://github.com/signorecello/zk-nullifier-sig/) - ECDSA-based nullifiers
- [RSA](https://github.com/zkpassport/noir_rsa) - RSA signature verification
- [Schnorr](https://github.com/noir-lang/schnorr) - Schnorr signature verification
- [WebAuthn/Passkeys](https://github.com/olehmisar/noir_webauthn) - Verification of WebAuthn/Passkeys signatures; verifies signatures produced by `credentials.get`

#### Merkle Trees

- [ZK-Kit: Merkle Trees](https://github.com/privacy-scaling-explorations/zk-kit.noir/tree/main/packages/merkle-trees) - verification of (non-)membership proofs and add/update/delete leaves
- [Indexed Merkle Tree](https://github.com/numtel/indexed-merkle-noir) - Generate and verify proofs of inclusion, exclusion, or insert transition, includes complementary NPM package
- [Merkle Tree](https://github.com/noir-lang/merkle) - Merkle Tree implementations forked from Aztec Packages

#### Message Authentication Code

- [Noir HMAC](https://github.com/zkpersona/noir-hmac) - hash-based message authentication code

#### Randomness

- [Cryptographically Secure Pseudo-Random Number Generator](https://github.com/doctoruber/CSPRNG) - pseudo-random number generation


### Security

- [rocq-of-noir](https://github.com/formal-land/rocq-of-noir) - formal verification of Noir programs with Rocq
- [lampe](https://github.com/reilabs/lampe) - formal verification of Noir programs with Lean
- [hunter](https://github.com/nfurfaro/hunter) - mutation-testing of Noir programs
- [zk-mutant](https://github.com/mutorium/zk-mutant) - mutation testing for Noir programs (source-level), running `nargo test` against small mutations to assess test-suite effectiveness
- [Circuzz fuzzer](https://github.com/Rigorous-Software-Engineering/circuzz) - fuzzer for finding soundness and completeness issues in the Noir infrastructure (by Consensys Diligence and TU Vienna)
- [noir-metrics](https://github.com/mutorium/noir-metrics) - source code metrics for Noir programs, with JSON output designed for audits, tooling, and mutation testing

#### Security

- [Workshop] [Circuit Safety and an Introduction to Noir](https://www.youtube.com/watch?v=rLvu61DA-hk) - common ZK vulnerabilities and an introduction to Noir
- [Workshop] [Noir Xmas Camp: Circuit Security & Production Readiness with Noir](https://youtu.be/pNI_56b7Bdo?si=LU1wQ-2Igd4Z7oNA)
- [Workshop] [NoirCon 2: Lampe](https://www.youtube.com/watch?v=CPel4WyBNuk) - formal verification of Noir programs in Lean

