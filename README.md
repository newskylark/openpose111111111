Human pose estimation from monocular images： A comprehensive survey

Human pose estimation
Pose estimation is a general problem in computer vision where we detect the position and orientation of an object.it means detecting key point locations that describe the object.
 In this essay, we will focus on human pose estimation, where is required to detect and localize. besides the head.
human has divide to movement, action, activity. by Turaga.
Several types image can be captured:
 RGB or gray scale images, infrared images ,depth images,.

Human estimation problem specific characteristics.
1.human body has high degrees of freedom, leading to a high-dimensional solution space
2.the complex structure and flexibility of human body parts causes partially occluded human poses which are extremely hard to recognize;
3.depth loss resulting from 3d pose projections to 2d image planes makes the estimation of 3d poses extremely difficult.

Methodologies

According to the previous works. There are two main ways of categorizing human pose estimation algorithms.
Based on whether human pose estimation is modeled as a geometric projection or is treated as a speciﬁc image processing problem, related works can be classiﬁed into two main groups: generative methods or discriminative methods

