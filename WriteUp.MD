The challenges our group faced are as follow:
(a) We first tried to make our project using backsub1.cpp from imagelab to extract the background that was used in the video of Kermit. However, the program produces a black and while images, and we find it hard to bring back the background into its original colors.
(b) By using OpenCV, we are able to extract the background image used in the video. However, there are still traces of Kermit as he only stays in the middle althroughout the video.
(c) We find it hard at first to get the range of color green in the HSV color space, and what morphological operation to be used.
(d) There is some discrepancy to the size of our inputs (Kermit video and our own video).
(e) We used Virtual Dub at first in creating the video but we found out that the output file size is too large.

The solutions we made for the problems we encountered as mentioned above are as follow:
(a) We tried a different approach by using OpenCV.
(b) We consulted Sir O'neil about this and the possible explanation is Kermit just stays in the middle althroughout the video.
(c) We tried and tested several ranges of green until we come up with a range that will fit our video.
(d) We converted the size of both of our videos for them to fit each other.
(e) We instead used OpenCV in creating our video and find it much easier than using Virtual Dub.
