## What does it do?    
1. Loads MNIST dataset    
2. Builds two neural networks:    
    - Generator: Transforms random noise into fake digit images    
    - Discriminator: Distinguishes between real and fake images    
3. Trains adversarially - Generator tries to fool discriminator, discriminator tries to detect fakes    
4. Generates synthetic digits - Creates new handwritten digit images    
5. Visualizes progress - Saves images at each epoch and creates animated GIF    
