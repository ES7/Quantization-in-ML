# Quantization-in-ML
Large generative AI models like LLMs can be so huge that they are hard to run on consumer grade hardware. Quantization has emerged as a key tool for making this possible. How to decide whether we should use int8 or float16 to compress the model? AI models are getting bigger and bigger, so quantization has been recently exciting for the AI community because it enables us to shrink models to a small size, so that anyone can run it with their own computer with little to no performance degradation.

**1. `Data_Types_&_Sizes.ipynb`:** In this notebook I have explained the significance of different data types and how to convert parameters from one data type to another.

**2. `Loading_Models_in_different_dtypes.ipynb`:** In this notebook I have explained how we can load models in different data types to save memory and what are its effects on the model's performace.

**3. `Quantization_Theory.ipynb`:** In this notebook I have explained how to apply linear quantization to any model and the maths behind it.

**4. `Linear_Quantization.ipynb`:** In this notebook I have explained linear quantization in depth.

**5. `Scale_&_Zero_Point.ipynb`:** In this notebook I have explained how you can get the value of scale and zero point.

**6. `Symmetric_VS_Asymmetric.ipynb`:** In this notebook I have explained the two modes of linear quantization: symmetric and asymmetric.

**7. `Per_Channel_&_Per_Group_Quantization.ipynb`:** In this notebook I have explained how to perform per channel and per group quantization also how to quantize weights and activations.

**8. `Build_Custom_8-Bit_Quantizer.ipynb`:** In this notebook I have explained how to build our own quantizer that can quantize any model in 8-bit precision via per channel quantization.
