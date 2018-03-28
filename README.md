#Darknet4j_2#
This java project is migrated from [darknet](https://github.com/pjreddie/darknet), and only implemented the part of detector train and detector test by now.
 Originally, we want it as a bridge to NN/Deap-Learning for a java programmer.

The file darknet_jni_wrapper.dll is for win7 x64, compiled by vc++2015, functions of read/write png of stbi(an image lib in stb_image.h and stb_image_write.h).

The program enter is java class cn.darknet.(By convention, Java type names usually start with an uppercase letter. But here we not.)
 The data for detector train is [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html), in the directory data/CelebA/.

IDE is eclipse with a maven plugin supported.

By convention, darknet/src/*.c will be src/main/java/cn/*.java, helpers will be in src/main/java/cn/wrapper/*_wrapper.java.
 Some stable functions will be put in src/main/java/cn/drknt/lib/ .