# Drowsiness_Detection

## Dependencies to install before running the detector:
1. opencv - pip install opencv-python
2. scipy - pip install scipy
3. dlib - conda install -c conda-forge dlib
4. sounddevice - pip install sounddevice
5. soundfile - pip install soundfile
6. numpy 


Using the dlib library, we can find the facial landmarks such as eyes, nose, ears, mouth,etc as illustrated in the below figure.

![image](https://user-images.githubusercontent.com/83316095/215728024-ed33e3f2-9be7-4ba6-a436-657e3836b6c0.png)

Eye Aspect Ratio(EAR) is given by the following formula :

![image](https://user-images.githubusercontent.com/83316095/215727326-5ae04015-7804-4632-9845-73cd9c24a39d.png)

To run the program, simply type the following command :
python3 Drownsiness_Detection.py

or 

Run the cell on jupyter notebook to invoke the camera. 


Download Pre Trained Dlib Model - https://www.kaggle.com/datasets/sajikim/shape-predictor-68-face-landmarks
References: http://vision.fe.uni-lj.si/cvww2016/proceedings/papers/05.pdf
