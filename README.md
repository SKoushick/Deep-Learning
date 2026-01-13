# Deep-Learning


32-bit Floating Point	torch.float32	Standard floating-point type used for most deep learning tasks. Provides a balance between precision and memory usage.
64-bit Floating Point	torch.float64	Double-precision floating point. Useful for high-precision numerical tasks but uses more memory.
16-bit Floating Point	torch.float16	Half-precision floating point. Commonly used in mixed-precision training to reduce memory and computational overhead on modern GPUs.
BFloat16	torch.bfloat16	Brain floating-point format with reduced precision compared to float16. Used in mixed-precision training, especially on TPUs.
8-bit Floating Point	torch.float8	Ultra-low-precision floating point. Used for experimental applications and extreme memory-constrained environments (less common).
8-bit Integer	torch.int8	8-bit signed integer. Used for quantized models to save memory and computation in inference.
16-bit Integer	torch.int16	16-bit signed integer. Useful for special numerical tasks requiring intermediate precision.
32-bit Integer	torch.int32	Standard signed integer type. Commonly used for indexing and general-purpose numerical tasks.
64-bit Integer	torch.int64	Long integer type. Often used for large indexing arrays or for tasks involving large numbers.
8-bit Unsigned Integer	torch.uint8	8-bit unsigned integer. Commonly used for image data (e.g., pixel values between 0 and 255).
Boolean	torch.bool	Boolean type, stores True or False values. Often used for masks in logical operations.
Complex 64	torch.complex64	Complex number type with 32-bit real and 32-bit imaginary parts. Used for scientific and signal processing tasks.
Complex 128	torch.complex128	Complex number type with 64-bit real and 64-bit imaginary parts. Offers higher precision but uses more memory.
Quantized Integer	torch.qint8	Quantized signed 8-bit integer. Used in quantized models for efficient inference.
Quantized Unsigned Integer	torch.quint8	Quantized unsigned 8-bit integer. Often used for quantized tensors in image-related tasks.
