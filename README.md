
# RiceRLE Codex App

**Propuse of the client**
They want to create a portotype for encoding and decoding a series of uncompressed audio files (WAV files), encode them and save it in your drive with the same name, but adding a _enc at the end to know what file was encoded. 

## Overview

RiceRLE Codex is an advanced encoding and decoding prototype that utilizes Rice encoding, characterized by its adjustable parameter `k`. Designed to optimize data compression without loss of information, RiceRLE Codex ensures accuracy and efficiency in processing messages.

## Key Features

- **Rice Encoding and Decoding**
- **Data Conversion**
- **File Comparison**
- **Parameter Impact**

## Encoding and Decoding Process

The application processes input files byte by byte, encoding each byte using Rice encoding. The encoded messages are then combined, converted back to bytes, and saved to an output file. The decoding process reverses these steps to accurately retrieve and store decoded messages.

## Impact of `k` Parameter

The `k` parameter is pivotal in determining the efficiency of encoding, affecting how input data is divided into unary and binary parts within code words. Experimentation with `k` values is essential to optimize encoding efficiency for specific datasets.

<img width="675" alt="Screenshot 2024-03-26 141445" src="https://github.com/joseortega9988/Rice-Run-Length-Encoding-App/assets/77720475/0b236e44-2546-4e8b-9ff6-02b8fca0f8ce">


## Further Development

Exploring the combination of Rice coding with Run-Length Encoding (RLE) to enhance compression efficiency, especially for datasets characterized by extended sequences of zeros and ones. Segmenting data files and tailoring `k` values to specific segments could further optimize compression.

<img width="338" alt="Screenshot 2024-03-26 141643" src="https://github.com/joseortega9988/Rice-Run-Length-Encoding-App/assets/77720475/ed25551b-99dd-47e8-9c27-20492c84f3ec">
## Conclusion

RiceRLE Codex offers a sophisticated solution for data compression, providing tools for effective encoding and decoding with potential for further optimization through combined encoding strategies and parameter adjustments.

**To see more details, please check the documentation and the comments on the code**



