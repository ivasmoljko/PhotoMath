# PhotoMath

Here is my version of PhotoMath. In this file I will explain only the basics, detailed version is in Colab Notebook.

*DATA*:
I used dataset I found on Kaggle. I load it directly from there. That set contains all handwritten digits, plus, minus, multiplication and division operator. The division operator is not as expected "/" but "%". However, the set does not contain bracket symbols "(" and ")" so my model does not recognize them. 

The dataset I used for expressions are manually made by me. Some of them (you can recognize them by heavier font) were merged from multiple images (from dataset above, folder "eval"), and some of them were written in Paint. Beneath the subtitle "Testing on expression" you can see that we create file "test_data". You can download from "test_data" folder I put on Git (folder that contains all images I tested on) and then upload the images in "test_data" folder on Colab. 

