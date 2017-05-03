Problem statement: Conceal your own identity in a live webcam stream. Facial regions corresponding to any other person should remain unaltered.
Description:
Can train the classifier one for detecting faces. Next, they can train another classifier to recognise their own face. During testing, a live video can be captured using webcam where the student and other people will be captured. The task is to identify the student and blur their facial region to conceal their identity.

Face detection and recognition have a lot of documentation available online. Such as this
http://docs.opencv.org/2.4/modules/contrib/doc/facerec/facerec_tutorial.html

Note: Requires external librarires : org.bytedeco.javacpp
