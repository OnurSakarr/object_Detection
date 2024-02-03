Yolov6-v7-v8 were trained with 90 epochs and Detectron with 10000 iterations. Yolov6 recognizes some of the close objects as one and some not at all. In the Empty ones, in some images, it does not take all the empty parts of the shelf, but only a small part. It does not recognize AlmostEmptys.

Yolov7 recognizes some regions as objects that it should recognize as AlmostEmptleri. If the angle of the image is good, it seems to recognize 3 classes very well, but if the angle is bad, it does not recognize some of the objects and does not seem to recognize the empties at all. 

Yolov8 gives wrong results in object detection in some images and the results are wrong in images with bad angle.

Detectron2 seems to be good at identifying objects and AlmostEmptys, but in one image the empty shelf was too high and it was not recognized.

Figure35-figure39-figure43 and figure47 is a picture I found on the internet and if we look at the results, we see that yolov7 and detectron give the best results. Other algorithms do not seem to be very good at finding products and gaps in this band of images. The fact that yolov7 sees the almostEmpty object in figure32 as object makes detectron2 look like a slightly better algorithm.
![Uploading WhatsApp Image 2023-12-18 at 13.50.34.jpeg…]()




**Detection Sample Outputs:**

<a name="_toc130565737"></a>*Şekil 1**

<a name="_toc130565738"></a>*Şekil 2**

<a name="_toc130565739"></a>*Şekil 3**

<a name="_toc130565740"></a>*Şekil 4**


**Yolov8 Sample Outputs:**

<a name="_toc130565741"></a>*Şekil 5**

<a name="_toc130565742"></a>*Şekil 6**

**Yolov7 Sample Outputs:**

<a name="_toc130565743"></a>*Şekil 7**

<a name="_toc130565744"></a>*Şekil 8**

<a name="_toc130565745"></a>*Şekil 9**

<a name="_toc130565746"></a>*Şekil 10**

**Yolov6 Sample Outputs:** 

<a name="_toc130565747"></a>*Şekil 11**

<a name="_toc130565748"></a>*Şekil 12**

<a name="_toc130565749"></a>*Şekil 13**

<a name="_toc130565750"></a>*Şekil 14**

<a name="_toc130565751"></a>*Şekil 15**

**Graphics**

**Yolov6:**

<a name="_toc130565752"></a>*Şekil 16**

<a name="_toc130565753"></a>*Şekil 17**

**Yolov7:** 

<a name="_toc130565754"></a>*Şekil 18**










**F1\_curve:**                                                                           

<a name="_toc130565755"></a>*Şekil 19**

**P\_curve:**

<a name="_toc130565756"></a>*Şekil 20**







**PR\_curve:**

<a name="_toc130565757"></a>*Şekil 21**

**R\_curve:**

<a name="_toc130565758"></a>*Şekil 22**


**Yolov8:** 

<a name="_toc130565759"></a>*Şekil 23**


<a name="_toc130565760"></a>*Şekil 24**

<a name="_toc130565761"></a>*Şekil 25**

<a name="_toc130565762"></a>*Şekil 26**

<a name="_toc130565763"></a>*Şekil 27**

**Details**

**Yolov8**

<a name="_toc130565764"></a>*Şekil 28**

**Yolov7**

<a name="_toc130565765"></a>*Şekil 29**

**Yolov6**

<a name="_toc130565766"></a>*Şekil 30**

**Detectron2**

<a name="_toc130565767"></a>*Şekil 31**


**Comparison**

**Yolov7:** 

<a name="_toc130565768"></a>*Şekil 32**

<a name="_toc130565769"></a>*Şekil 33**

<a name="_toc130565770"></a>*Şekil 34**

<a name="_toc130565771"></a>*Şekil 35**

**Yolov6:**

<a name="_toc130565772"></a>*Şekil 36**

<a name="_toc130565773"></a>*Şekil 37**

<a name="_toc130565774"></a>*Şekil 38**

<a name="_toc130565775"></a>*Şekil 39**

**Yolov8:** 

<a name="_toc130565776"></a>*Şekil 40**

<a name="_toc130565777"></a>*Şekil 41**

<a name="_toc130565778"></a>*Şekil 42**


<a name="_toc130565779"></a>*Şekil 43**

**Detectron2:** 

<a name="_toc130565780"></a>*Şekil 44**

<a name="_toc130565781"></a>*Şekil 45**

<a name="_toc130565782"></a>*Şekil 46**

<a name="_toc130565783"></a>*Şekil 47**


