### What is this repo about?
It checks what exactly the [RISE](https://github.com/eclique/RISE) notebooks do.

### How to launch the notebooks?
1. Create the `conda` environment with the given `.yml` file.  
2. The environment will download the GPU versions of tensorflow and pytorch, which is around 4GB total, so it will take some time.  
3. If you want to run the Saliency notebook, you need to download the 
[Image Net 2012 validation](https://academictorrents.com/details/5d6d0df7ed81efd49ca99ea4737e0ae5e3a5f2e5) dataset. And put the pictures
into `whatever_folder/whatever_class/actual_pictures` so the image loader from the notebook works as intended.  
4. Now you can run `jupyter notebook` and open the notebooks in it.

### What is different?
Compared to the [original](https://github.com/eclique/RISE) repository,  
In Easy_start, `keras` became `tensorflow.keras` because it has become a part of the tensorflow package.  
In Saliency, the image folder and gpu batch size were changed.
