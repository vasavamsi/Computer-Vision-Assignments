>>>> Assingment-4 (Computer Vision)

## Executing the code:
>> Run test_script.py.
>> Enter the image pair no. to execute the code on respective set.
>> The Fundamental matrix in between the pair of images will be displayed (both for inbuilt function
and using my RANSAC function)
>> Input the image patch size (choose in between 3 and 5) for reconstruction.
>> The code is designed to save the intermediate progress to monitor and the no. of reconstructed patches
is displayed at every 100 patches.
>> Final reconstructed image is saved in the same folder as of the image pair.

##Note:
>> The root directory is to be maintained as seen and naming of the images and their folders to be
followed in the same fashion.
>> The resize function is used to downscale the image before considering for the RANSAC Algorthim and for
reconstruction purpose due to time constraint. The same can uncommented for regular size reconstruction,
but will consume more time.(same is mentioned in the image_reconstruction.py)
>> The no. of inliers in the ransac.py script can be changed to get the better Fundamental matrix.
>> The no. of iterations for the RANSAC Algorithm can also be changed as per user requirement.
(Both the above are commented in the code itself)
>> To see the intermediate progress, uncomment the part mentioned in panaroma_stitching.py.
(the intermediate images will be saved in the same directory in BGR format)
>> The parameters for RANSAC Algorithm in inbuilt fundamental matrix function is set for the default
values.