# Image_Stitching
EECS4422 A3

part 1 uses openCV SIFT detector and kornia match_snn to find closest matches of keypoints by their direction descriptors.
And then use RANSAC to find and solve for the best affine transformation matrix to align `parliament-left` with `parliament-right`

part 2 uses similar strategy to find and solve for the best homography transformation matrix to align 3 images to the "middle" one.

May need more tuning on the homography match finder.