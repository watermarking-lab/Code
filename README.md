This paper proposes a robust and reversible color image watermarking algorithm utilizing adaptive block selection and watermark embedding based on quantized DCT-DC components in the spatial domain.  With the increasing need for digital media copyright protection, we aim to develop a solution that balances invisibility, robustness, and efficiency.  By selectively embedding watermarks into smooth image blocks and quantizing their DCT-DC components, our method achieves high invisibility, as evidenced by an average PSNR exceeding 48 dB and SSIM close to 1.  The algorithm demonstrates strong robustness against various attacks, including JPEG compression, noise addition, and filtering, with normalized cross-correlation values consistently above 0.95.  Furthermore, our approach is fully reversible, enabling lossless recovery of the original host image.  The algorithm's efficiency is ensured through an adaptive block selection strategy, eliminating the need for complete DFT and IDFT computations.
The main function for execution can be found in "main_adaptive.m".
