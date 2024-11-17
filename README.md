# RSA using CryptoCell

This is an RSA example performed on Nordic devices that shows how to perform signature and verification using CryptoCell.

## The sample performs the following operations:

- Initialization of the Platform Security Architecture (PSA) API.
- Importing an RSA key pair into the PSA crypto store.
- RSA signing and verification:
  - Signing is performed using the RSA private key.
  - The signature is verified using the public key.
- Cleanup:  
  - The RSA key pair and public key are removed from the PSA crypto keystore.
  
## Testing

After programming the sample to your development kit, complete the following steps to test it:

1. Connect terminal.
2. Compile and program the application.
3. Observe the logs from the application using a terminal emulator.