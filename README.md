# lesson43

Summarize the performance metrics for both noise levels

For 2% Gaussian Noise (initial run):
Mean PSNR: 31.5702
Mean SSIM: 0.9493
Mean LPIPS: 0.0972

For 10% Gaussian Noise (second run):
Mean PSNR: 27.5665
Mean SSIM: 0.8211
Mean LPIPS: 0.2949
As expected, with a higher noise level (10%), the PSNR and SSIM scores decreased, and the LPIPS score increased, indicating a reduction in overall image quality and perceptual similarity compared to the lower noise level. This demonstrates the impact of increased noise on the model's denoising capability.
