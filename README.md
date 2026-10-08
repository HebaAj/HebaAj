# Heba Ajjour

Cybersecurity engineer focused on applied cryptography, security protocol analysis, and post-quantum TLS. B.Sc. in Cybersecurity Engineering, University College of Applied Sciences (UCAS), Gaza.

## Security research

### Verifpal: protocol analysis tool

I contribute to [Verifpal](https://github.com/symbolicsoft/verifpal), the security protocol verifier maintained by Dr. Nadim Kobeissi. Through source review and testing, I identified four flaws in its analysis engine, each fixed with credit to my findings in the repository:

- [Unlinkability: attacker-observable values assembled from transmitted components](https://github.com/symbolicsoft/verifpal/commit/d9d5d7542b54fed86e4ee4772a7768f4a95de0e3)
- [Missed attack from disclosure bookkeeping around a failed check](https://github.com/symbolicsoft/verifpal/commit/b2b4ef2f88481cf3e29b4c1ea490e6ffb89077c4)
- [Scenario analysis: peer incorrectly classified as corrupt](https://github.com/symbolicsoft/verifpal/commit/5962ede0d8df686223c461725119cfcf7f6d0227)
- [Guarded downstream forwarding: missed duplicate acceptance](https://github.com/symbolicsoft/verifpal/commit/d0969fd3a79f8c7967f79084ef73842020511acb)

### AdaptiveQKE: graduation project

I initiated and led the research and implementation of [AdaptiveQKE](https://github.com/HebaAj/AdaptiveQKE), a client-side policy that chooses the hybrid ML-KEM/ECDH key-exchange group for each TLS 1.3 connection, based on measured RTT and device resource limits. The choice is made before the handshake, and the TLS 1.3 handshake itself is not modified.

Across **1,800 controlled handshakes** (3 device × 3 network profiles), it had lower median latency than the strongest fixed group in 8 of 9 conditions (12.8% lower on average, up to 36.1%) and used 26.2% fewer handshake bytes on average.

[Thesis](https://github.com/HebaAj/AdaptiveQKE/blob/main/docs/AdaptiveQKE-thesis.pdf) · [Code and dataset](https://github.com/HebaAj/AdaptiveQKE) · [DOI](https://doi.org/10.5281/zenodo.23244638)

## Learning notes

- [Applied Cryptanalysis](https://github.com/HebaAj/Applied-Cryptanalysis): number theory and attacks on AES, RSA, Diffie–Hellman, and elliptic curves.
- [Smart Contract Security](https://github.com/HebaAj/Smart-Contract-Security): Solidity vulnerability patterns, built through Ethernaut.

## Tools and languages

Python · Java · Solidity · Bash · Linux · Git · OpenSSL · Verifpal · Wireshark · Burp Suite · Snort

## Other open-source work

[bajjour/stripe](https://packagist.org/packages/bajjour/stripe): a Laravel package for Stripe API integration.

**Contact:** [hajjour27@gmail.com](mailto:hajjour27@gmail.com)