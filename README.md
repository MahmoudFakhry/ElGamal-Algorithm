# ElGamal Encryption and Diﬃe–Hellman Key Exchange

## Summary

This repository contains an implementation of the ElGamal encryption algorithm with documentation alongside background on the Diﬃe–Hellman Key Exchange (DHKE) algorithm. For rigorous mathematical detail including a descriptive proof of correctness, refer to the paper: [ElGamal Encryption and Diffie–Hellman Key Exchange Paper](ElGamal%20Encryption%20and%20Diffie–Hellman%20Key%20Exchange.pdf).

- To illustrate the ElGamal cryptographic algorithm, two parties “Alice” (Receiver) and “Bob” (Sender) have both a secret and private key. After combining their private and secret keys, they swap their key combinations in order to ﬁnd the message sent by the sender to the receiver, decrypted by the receiver.

## Code Implementation

A demonstration of the ElGamal executing key generation followed by encrypting and decrypting a message sent from one party to another over a public channel is provided in [ElGamal.nb](ElGamal.nb).  
