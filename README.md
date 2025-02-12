# AICTC-Internship

### Project: AICTE Internship on AI: Transformative Learning with TechSaksham – A joint CSR initiative of Microsoft & SAP

### Objective
To explore and implement an image generation system using Stable Diffusion and ComfyUI, enabling the creation of high-quality and diverse images from textual prompts or noise initialization, while providing an interactive and user-friendly interface for creative AI applications.

### Key Activities

-**Literature Review:** Studied diffusion models, U-Net architecture, and generative AI techniques.

-**Environment Setup:** Configured hardware and installed required software, libraries, and tools for Stable Diffusion and ComfyUI.

-**Model Integration:** Loaded and fine-tuned the Stable Diffusion model using the Diffusers library. Integrated the model with ComfyUI for interactive visualization.

-**Workflow Development:** Designed and implemented a pipeline for generating images using text prompts and noise initialization.

-**Parameter Tuning:** Experimented with resolution, guidance scales, and inference steps for optimal image quality.

-**Image Generation and Analysis:** Generated diverse images, capturing various creative and realistic elements. Evaluated image quality and performance metrics.

-**Snapshot Documentation:** Captured and analyzed generated image snapshots for report documentation.

### Understanding Connection

**1. Load Checkpoint** Loads the pre-trained Stable Diffusion model weights (.ckpt files). Provides essential parameters for image generation and allows model version switching.

**2. CLIP Text Encoder** Converts the user’s text prompt into a high-dimensional vector representation. Guides the diffusion model to generate images aligned with the prompt.

**3. KSampler Handles** the iterative denoising process, transforming random noise into meaningful images. Key components: Noise Schedule: Gradual noise removal. Sampling Method: Techniques like Euler or DDIM for quality control. Guidance Scale: Defines how strictly the output follows the prompt.

**4. VAE Decode** (Variational Autoencoder Decode) Converts the compressed latent data back into a viewable image. Ensures that fine image details are reconstructed accurately.

### Snap Shots of Result:
*Snapshot 1:*
![WhatsApp Image 2025-02-12 at 10 14 16_5481b4de](https://github.com/user-attachments/assets/a55fb7af-eec4-432e-83f4-2305e8056289)

![WhatsApp Image 2025-02-12 at 10 14 59_152aa023](https://github.com/user-attachments/assets/7643cd4b-c0c3-41d5-952d-c32495470014)

*Snapshot 2:*
![WhatsApp Image 2025-02-12 at 10 01 05_b7548474](https://github.com/user-attachments/assets/0aad906a-6c05-40ec-851e-249e90786a53)

![WhatsApp Image 2025-02-12 at 10 01 35_4d9114a6](https://github.com/user-attachments/assets/ea01f9ae-ebb9-4fb2-b896-9309ddd8fcd3)

*Snapshot 3:*
![WhatsApp Image 2025-02-12 at 10 02 39_3464967e](https://github.com/user-attachments/assets/632a0cae-7bc8-4081-bb0f-bdd8522d7db3)

![WhatsApp Image 2025-02-12 at 10 02 24_8e258a3b](https://github.com/user-attachments/assets/7c368e2c-9508-4add-a2a9-6969e22375dc)

*Snapshot 4:*
![WhatsApp Image 2025-02-12 at 12 08 30_f7541964](https://github.com/user-attachments/assets/0677ee7c-031b-41ca-8441-b6cded7d0cd4)

![WhatsApp Image 2025-02-12 at 12 08 45_5e7cf752](https://github.com/user-attachments/assets/b6880e8d-149e-470b-8efe-906461210767)

*Snapshot 5:*
![WhatsApp Image 2025-02-12 at 12 16 56_5f6680ef](https://github.com/user-attachments/assets/a026f372-3a04-4cb3-865f-d169b3846c16)

![WhatsApp Image 2025-02-12 at 12 17 35_7469ae3d](https://github.com/user-attachments/assets/7fcd81fa-b569-4f81-83c1-5cdaf6112e92)





