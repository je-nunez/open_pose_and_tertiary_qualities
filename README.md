# Open-Pose and Tertiary qualities

# WIP

This project is a *work in progress*. The implementation is *incomplete* and subject to change. The documentation can be inaccurate.

# Brief

Open-Pose is a C++ library for real-time Multi-Person Keypoint Detection developed at the Carnegie Mellon University. As mentioned at its project repository [https://github.com/CMU-Perceptual-Computing-Lab/openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose):

    OpenPose represents the first real-time system to jointly detect human body, hand and facial keypoints (in total
    130 keypoints) on single images. In addition, the system computational performance on body keypoint estimation
    is invariant to the number of detected people in the image.

The article published by its authors is at:

       Realtime Multi-Person 2D Pose Estimation using Part Affinity Fields
          at https://arxiv.org/abs/1611.08050
          Authors: Zhe Cao, Tomas Simon, Shih-En Wei, Yaser Sheikh
          Date: Submitted on 24 Nov 2016 (v1), last revised 14 Apr 2017 (v2)

This project is using this library for tertiary artistic qualities, mainly simplification and remotion of qualities in the real-time videos as to get an abstract artistic form.

# Examples

The first example is from a scene of the movie ["Back Stage", starring Fatty Arbuckle and Buster Keaton (1919)](https://en.wikipedia.org/wiki/Back_Stage_(1919_film)), when the dancer Jack Coogan enters into the theater and Buster Keaton, Al St. John, and Roscoe Arbuckle meet him. The original scene is at [https://www.youtube.com/watch?v=tYL0VjaCAUY](https://www.youtube.com/watch?v=tYL0VjaCAUY). One result, by using Open-Pose to find Tertiary artistic qualities, is at [result_1919_Arbuckle_Buster_Keaton_Back_Stage.avi](result_1919_Arbuckle_Buster_Keaton_Back_Stage.avi), where it can be seen that the qualities of time and location in the original scene are translated.

[![result_1919_Arbuckle_Buster_Keaton_Back_Stage.avi](extras/result_combined_1919_Arbuckle_Buster_Keaton_Back_Stage_frame_000231.png)](result_1919_Arbuckle_Buster_Keaton_Back_Stage.avi)

(The background used in this translation to receive the scene is at [https://commons.wikimedia.org/wiki/File:Dance_Studio_First.jpg](https://commons.wikimedia.org/wiki/File:Dance_Studio_First.jpg), although any other adequate background could have been chosen -giving, probably, a very different translation of the scene. Furthermore, this scene has two other minor backgrounds -one were Buster Keaton and Al St. John talk and dance, and another where Roscoe Arbuckle dances: these two other backgrounds where to translate these subscenes need to be found.)

