# Base64Tool

Base64Tool is a plugin For Unreal Engine. It can convert Base64 image string to Texture2D. Judge Base64 Image format is or not PNG or JPEG.

## Feature1: Convert Base64 image string to Texture2D

1: Create an UserInterface with a image

![img1](https://gitee.com/hwreal/mdimages/raw/master/2023/s1.png)

![img2](https://gitee.com/hwreal/mdimages/raw/master/2023/s2.png)

2: Open the "Graph" tab in the UserInterface, Call "Base 64String to Texture2D" function after the "Event construct" node
![img3](https://gitee.com/hwreal/mdimages/raw/master/2023/s3.png)


3: Input a Base64String of a image, For example:
```
iVBORw0KGgoAAAANSUhEUgAAACQAAAAoCAYAAACWwljjAAAD30lEQVRYhcWYXYiWRRTHf65mTetGawRZXSQUfVMUUohfRF9SF3VTQUZJgdJVUVA4MdHQIELSVZFZSHRT6d2uYh9EZSyJJEWRhEEGpRepRYs7RtsH5+08y+Oz8zzPPLrr/uGFd2bOOfNjZt6Zc95ZdJSzcSFwF7AMuAq4BOjXKMeAA8B3wGfAdh/Mj11myAJyNord3cDTCtJFAvYSMOyD+feUgZyN1wGvATd3BKnqC2CtD+brJqO+FpgngD1TAIPG2KMxa5VcIWfjbF2Vx6YAJKU3dLX+ro5NAtLz8iaweppgCm0BHq2eq9SWrTsNMOgc66qdJ6yQs3ExsKvtbE2h/gGW+mBGJgE5G+cAe4FrTxNMoW+AG3ww41RWYtUMwKBzrioaZaBnZwCm0DPFlx6Qs/Em4PIZBLpCGZijHfeeRBA5kJ8DnwAHte9CYAWw5CR+GMKwuwBa0dF5E+B9MAdTg85GAXPAmg4xewwF0DWZTmPAfT6Y7U1GCrrW2TgEvAecnRG7xzDL2XgBcCjDQa75O30wH2XC9+RsvBXYCczOMF8g+zwvM/b6rjD8v1risz7TfJ5s2dwMw6OpoM5GSc6eB5Zr16fACz6YAxVT8X0cmN8yz1xZodEMoG0+mLEKzNV6sz8CLNSPfN+rYxNS320Z84z26fmZlAZUtDPR9wowmOgf1LGcGGUJw6E+fUP2txj/VG44GwdL25TScrWpjZHQfmEpLq+RFuNjlXZ/jV2TTTVGVT2GAmi4xXhBpS3bfLjB/nDiKqnGqGq4DLQDONJgvKjc0NRzQ4P9hkR6uqjGFp17xwSQD+ZPYHODwz2Jvo1AAMZLfePatzEzRqHNynBCgnaeHu7UL0e0zAezq9rpbJStWKzNER/MpFvf2bhU67OUfgMu88EcIZHCrtFqI6V9suw+mLbDWYXp11LqyhoTqT42FY1qivA6MFTjKAG3OhtzHsoCRmy3NsAM6ZwTSpVB52ieU5fOfgk85IPZ1wIjEG8DN9aYSC69xAfzRyOQBjsf+LghLflL04p35P3ywYyq34BemA9ImgKcUeP/LXCLD+bX6kBtbe9sPBd4F7i9zqak4j0cyLD9ALjfB/N7arA2zVSHlcBTmpg1aSADZkxjrayDocPfMRcDzwEPA2fl+JR0HHgLeNEH83Obcac/rJyN8zWvEbgzM0DkknzVB3M0d45sIGfjHcCTwG0dKgqpTD4EXvbBvD8lQFpBbMk83E2Sw7y6rlLJAnI2Xqp110WnCFPoFyl3fDA/dAZyNsrh/WoaKtrvget9MMdTg01n4cFpKq8lpsROqglIXujpUjo28B88qBlSeN8odQAAAABJRU5ErkJggg==
```

4: call "Set Brush Resource Object" function and add this UserInterface to viewport
![img6](https://gitee.com/hwreal/mdimages/raw/master/2023/s6.png)

5: Run. The image  will show
![img7](https://gitee.com/hwreal/mdimages/raw/master/2023/s7.png)

## Feature2: Judge Base64 Image format is or not PNG or JPEG

1: call "Base64 Image Is Png" or "Base64 Image Is Jpeg" function, then print the resut

![img9](https://gitee.com/hwreal/mdimages/raw/master/2023/s9.png)
![img10](https://gitee.com/hwreal/mdimages/raw/master/2023/s10.png)

2: Run, will print the result
![img11](https://gitee.com/hwreal/mdimages/raw/master/2023/s11.png)


