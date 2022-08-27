# instance-level-object-det

A system that detects an instance of a given reference object in the input image

An example with intermediate results displayed:
1. Find keypoints and matches

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/1.png?raw=true)

2. Given points in the input image, find the bounding box parameters

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/2.png?raw=true)

3. Hough Voting

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/3.png?raw=true)

4. Use selected keypoints to fit homography with RANSAC

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/4.png?raw=true)

Some results:

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/book_ref.png?raw=true)

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/book1.png?raw=true)

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/book2.png?raw=true)

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/book3.png?raw=true)

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/book4.png?raw=true)

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/sign_ref.png?raw=true)

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/sign1.png?raw=true)

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/sign2.png?raw=true)

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/sign3.png?raw=true)

![alt text](https://github.com/yuhuahu310/instance-level-object-det/blob/main/results/sign4.png?raw=true)

