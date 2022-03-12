## cow-gen!

### details
---
this project uses a deep convolutional generative adversarial network to generate cow pictures.

unfortunately, i can't find a large dataset of cow faces + the quality isn't that great, so the results won't look that good.

i essentially repurposed the code from tensorflow's tutorial: https://www.tensorflow.org/tutorials/generative/dcgan

the code'll look really similar to this code ^^

if anyone has a better dataset + any ideas on how to make this better, please let me know by opening an issue/pr!

note that you'd probably want to scale up the image res, i didn't because i wanted to make sure the model worked quickly if people wanted to try it out.


### use
---
you uh, probably won't get the results you're expecting. the images are black and white, and the pictures are really bad quality due to low res and small dataset. you'll probably just see blobs of black & white...

but, if you still want to see it ~~to spite me~~, clone this github repo, and run the jupyter notebook, with however many epochs you want!

here's an example output with scaled up res:

![](demo.gif)

thanks for reading ≧(´▽｀)≦