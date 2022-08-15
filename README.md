# DCGAN_celebA

This is a Deep Learning model using dcgan to create a fake image generator Generative Adversarial Network (GAN) and Deep Convolutional for classification
I worked on the celeb A dataset imported from kaggle and applied the model on google colab



Omar Elsamahy 							18102063
Generator Architecture
dense (Dense)               multiple                  3660800   
                                                                 
 batch_normalization (BatchN  multiple                 146432    
 ormalization)                                                   
                                                                 
 leaky_re_lu (LeakyReLU)     multiple                  0         
                                                                 
 reshape (Reshape)           multiple                  0         
                                                                 
 upsample (Upsample)         multiple                  1639680   
                                                                 
 upsample_1 (Upsample)       multiple                  819840    
                                                                 
 upsample_2 (Upsample)       multiple                  205120    
                                                                 
 conv2d_transpose_3 (Conv2DT  multiple                 4803


Discriminator arch
input_1 (InputLayer)        [(None, 104, 88, 3)]      0         
                                                                 
 cnn_block (CNNBlock)        multiple                  2432      
                                                                 
 cnn_block_1 (CNNBlock)      multiple                  51264     
                                                                 
 cnn_block_2 (CNNBlock)      multiple                  204928    
                                                                 
 cnn_block_3 (CNNBlock)      multiple                  819456    
                                                                 
 flatten (Flatten)           multiple                  0         
                                                                 
 dense_1 (Dense)             multiple                  585729


10 Images
