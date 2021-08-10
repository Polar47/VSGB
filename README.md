# VSGB

Sentiment Image Generation： Learning Continuous Emotional Distribution with Brightness Modulation

The introduciton and code of our work will be uploaded later.

## Dataset

The model is trained with a brand new emotional image dataset SBDI (Sentiment of Bright-Dark Images), consist of 500 pairs of images with valance and arousal labels.

Two pictures in any group have the same image content, but there are obvious differences in exposure, which also makes the two pictures have a significant difference in emotional characteristics. We have adjusted the exposure of some of the collected pictures to ensure that these pictures will not interfere with the content matching of the image group due to underexposure or overexposure.

Since these 1000 pictures have independent emotional distributions, we invited 5 experts in the field of psychology to label the groud truth of valance and arousal scores. We adopt the Self-Assessment Manikin (SAM) 9-point scale, which is also used in most sentiment image database annotation work. For the valence scores,1,5,and 9 mean very negative, neutral, and very positive emotions respectively. For the arousal scores, 1 (9) means the emotion has low (high) stimulating effect.

The SBDI dataset can be download from [SBDI](https://1drv.ms/u/s!Ar8Vb16CK2gdhx_scFFMnH8LJOAQ?e=AfMTG8)
