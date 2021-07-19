# Mariia Shabanova
mariasha312@gmail.com
+79522063598
Saint-Petersburg, Russia


## Profile
My objective is to become a web development.

I am initiative, responsible, ready to learn new things, committed
to the full implementation of the targets, ready for teamjob.

I have experience in image processing using Wolfram Mathematica.


## Skills
* HTML basic skills
* CSS basic skills
* Wolfram Mathematica 
* C++ basic skills
* Matlab 
* Image Processing
* Altium Designer
* Git basic skills


## Code example
```img2 = Inpaint[img1, 
  Dilation[Binarize[ColorSeparate[img1][[1]], 0.19], 
   0.5]] 
img3 = DeleteSmallComponents[img2, 
  Method -> 
   "Cluster"]
img6 = ImageMultiply[img3, 
  SelectComponents[FillingTransform@Binarize[img3, 0.225], "Area", -3]]

GraphicsRow[{img3,img6}]
img4=ImageSubtract[img3,ColorNegate@FillingTransform@ColorNegate[\
img3]]
img5=EdgeDetect[img4, 5.5]
img7=Colorize[MorphologicalComponents[img4]];
img8=Colorize[MorphologicalComponents[img6]];

img9=SetAlphaChannel[img5,img6]
img10=SetAlphaChannel[img5,img5]
img11=ImageCompose [img2, img10]

img12=ImageCompose[MedianFilter[img6,4],img10]
img13=ColorSeparate[img9]
```


## Experience
Trainee NII Vektor

2021-2021 Saint-Petersburg, Russia

Developing component databases and processing technical
documentation


## Education
Bachelor Mobile Communication Systems

Saint-Petersburg Electrotechnical University
2017-2021

Diploma with Honors

Third-class degree Graduation Paper "Software System of
Tomographic Images Analysis"


## Languages
* English B2
* French B1