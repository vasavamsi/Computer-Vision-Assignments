>>>> Assingment-3 (Computer Vision)

## Executing the code:
>> Run test_script.py.
>> Enter the image set no. to execute the code on respective set.
>> The Homography matrix in between the current pair of images will be displayed.
>> Final panaroma image will be saved in the same folder as of dataset.

##Note:
>> The root directory is to be maintained as seen and naming of the images and their folders to be
followed in the same fashion.
>> The Code is fixed for the set of 8 images, for different no. of images alter the range mentioned
in the panaroma_stitching.py (commented in the code)
>> The no. of inliers in the ransac.py script can be changed to get the better homography matrix.
>> The no. of iterations for the RANSAC Algorithm can also be changed as per user requirement.
(Both the above are commented in the code itself)
>> To see the intermediate progress, uncomment the part mentioned in panaroma_stitching.py.
(the intermediate images will be saved in the same directory in BGR format)