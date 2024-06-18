# IMAGE_PROCESSING-AND-CV

My journery to learn computer vision and image processing first by using the Digital Sreeni playlist then to dive into good practical books for Healthcare imaging. Will also add projects using MONAI for healhcare imaging. 



Top 5 Computer Vision Textbooks
-------------------------------

Textbooks are those books written by experts, often academics, and are designed to be used as a reference for students and practitioners.

They focus mainly on general methods and theory (math), not on the practical concerns of problems and the application of methods (code).

I gathered a list of the top five textbooks based on their usage in university courses at top schools (e.g. MIT, etc.) and recommendations on discussion websites (e.g. Quora, etc.).

The top five textbooks on computer vision are as follows (in no particular order):

*   [Computer Vision: Algorithms and Applications](https://amzn.to/2LcIt4J), 2010.
    
*   [Computer Vision: Models, Learning, and Inference](https://amzn.to/2rxrdOF), 2012.
    
*   [Computer Vision: A Modern Approach](https://amzn.to/2rv7AqJ), 2002.
    
*   [Introductory Techniques for 3-D Computer Vision](https://amzn.to/2L9C2zF), 1998.
    
*   [Multiple View Geometry in Computer Vision](https://amzn.to/2LfHLE8), 2004.
    

Let’s take a closer look at each in turn, including the target audience and table of contents for each book.

### Computer Vision: Algorithms and Applications

This book was written by [Richard Szeliski](http://szeliski.org/RichardSzeliski.htm) and published in 2010.

Computer Vision: Algorithms and Applications

A draft version of the book in PDF format is available from the [book’s homepage](http://szeliski.org/Book/).

I like this book. It provides a strong foundation for beginners (undergraduates) in computer vision techniques for a wide range of standard computer vision problems. The book was developed by Richard based on his years of experience teaching the topic at the University of Washington.

> This book also reflects my 20 years’ experience doing computer vision research in corporate research labs \[…\] I have mostly focused on problems and solution techniques (algorithms) that have practical real-world applications and that work well in practice. Thus, this book has more emphasis on basic techniques that work under real-world conditions and less on more esoteric mathematics that has intrinsic elegance but less practical applicability.

— Page ix, [Computer Vision: Algorithms and Applications](https://amzn.to/2LcIt4J), 2010.

*   [Book Homepage](http://szeliski.org/Book/)
    
*   [Book on Amazon](https://amzn.to/2LcIt4J)
    

The table of contents for this book is as follows:

*   1\. Introduction
    
*   2\. Image formation
    
*   3\. Image processing
    
*   3\. Feature detection and matching
    
*   5\. Segmentation
    
*   6\. Feature-based alignment
    
*   7\. Structure from motion
    
*   8\. Dense motion estimation
    
*   9\. Image stitching
    
*   10\. Computational photography
    
*   11\. Stereo correspondence
    
*   12\. 3D reconstruction
    
*   13\. Image-based rendering
    
*   14\. Recognition
    

### Computer Vision: Models, Learning, and Inference

This book was written by [Simon Prince](http://www0.cs.ucl.ac.uk/external/s.prince/) and published in 2012.

Computer Vision: Models, Learning, and Inference

A draft version of the book is available on the [book’s website](http://www.computervisionmodels.com/) in PDF format.

This is a great introductory book (for students) and covers a wide range of computer vision techniques and problems. The book takes more time to introduce computer vision and spends useful time on foundational topics related to probabilistic modeling.

> This modern treatment of computer vision focuses on learning and inference in probabilistic models as a unifying theme. It shows how to use training data to learn the relationships between the observed image data and the aspects of the world that we wish to estimate, such as the 3D structure or the object class, and how to exploit these relationships to make inferences about the world from new image data.

— [Computer Vision: Models, Learning, and Inference](https://amzn.to/2rxrdOF), 2012.

*   [Book Homepage](http://www.computervisionmodels.com/)
    
*   [Book on Amazon](https://amzn.to/2rxrdOF)
    

The table of contents for this book is as follows:

*   1\. Introduction
    
*   2\. Introduction to probability
    
*   3\. Common probability distributions
    
*   4\. Fitting probability models
    
*   5\. The normal distribution
    
*   6\. Learning and inference in vision
    
*   7\. Modeling complex data densities
    
*   8\. Regression models
    
*   9\. Classification models
    
*   10\. Graphical models
    
*   11\. Models for chains and trees
    
*   12\. Models for grids
    
*   13\. Image preprocessing and feature extraction
    
*   14\. The pinhole camera
    
*   15\. Models for transformations
    
*   16\. Multiple cameras
    
*   17\. Models for shape
    
*   18\. Models for style and identity
    
*   19\. Temporal models
    
*   20\. Models for visual words
    

### Computer Vision: A Modern Approach

This book was written by [David Forsyth](http://luthuli.cs.uiuc.edu/~daf/) and [Jean Ponce](https://www.di.ens.fr/~ponce/) and published in 2011.

Computer Vision: A Modern Approach

This is an introductory textbook on computer vision and is perhaps more broad in the topics covered than many of the other textbooks. Although broad, it may be less loved (popular) than some of the other introductory text as it can be challenging to read: it dives right in.

> … vision relies on a solid understanding of cameras and of the physical process of image formation (Part I of this book) to obtain simple inferences from individual pixel values (Part II), combine the information available in multiple images into a coherent whole (Part III), impose some order on groups of pixels to separate them from each other or infer shape information (Part IV), and recognize objects using geometric information or probabilistic techniques (Part V).

— xvii, [Computer Vision: A Modern Approach](https://amzn.to/2rv7AqJ), 2002.

*   [Book’s Homepage](http://luthuli.cs.uiuc.edu/~daf/CV2E-site/cv2eindex.html)
    
*   [Book on Amazon](https://amzn.to/2rv7AqJ)
    

The table of contents for this book is as follows:

*   Part I. Image Formation
    
    *   1\. Radiometry – Measuring Light
        
    *   2\. Sources, Shadows and Shading
        
    *   3\. Colour
        
*   Part II. Image Models
    
    *   4\. Geometric Image Features
        
    *   5\. Analytical Image Features
        
    *   6\. An introduction to Probability
        
*   Part III. Early Vision: One Image
    
    *   7\. Linear Filters
        
    *   8\. Edge Detection
        
    *   9\. Filters and Features
        
    *   10\. Texture
        
*   Part IV. Early Vision: Multiple Images
    
    *   11\. The Geometry of Multiple Views
        
    *   12\. Stereopsis
        
    *   13\. Affine Structure from Motion
        
    *   14\. Projective Structure from Motion
        
*   Part V. Mid-Level Vision
    
    *   15\. Segmentation Using Clustering Methods
        
    *   16\. Fitting
        
    *   17\. Segmentation and Fitting Using Probabilistic Methods
        
    *   18\. Tracking
        
*   Part VI. High-Level Vision
    
    *   19\. Correspondence and Pose Consistency
        
    *   20\. Finding Templates Using Classifiers
        
    *   21\. Recognition by Relations Between Templates
        
    *   22\. Aspect Graphs
        
*   Part VII. Applications and Topics
    
    *   23\. Range Data
        
    *   24\. Applications: Finding in Digital Libraries
        
    *   25\. Application: Image-Based Rendering
        

### Introductory Techniques for 3-D Computer Vision

This book was written by [Emanuele Trucco](https://www.dundee.ac.uk/computing/people/profile/emanuele-trucco.php) and [Alessandro Verri](https://www.disi.unige.it/person/VerriA/) and was published in 1998.

Introductory Techniques for 3-D Computer Vision

This is an older book that focuses on computer vision in general with some focus on techniques related to 3D problems in vision. It’s a great starting point, intended for undergraduate rather than graduate-level readers.

> This book is meant to be: \[…\] an applied introduction to the problems and solutions of modern computer vision.

– xiii, [Introductory Techniques for 3-D Computer Vision](https://amzn.to/2L9C2zF), 1998.

*   [Book on Amazon](https://amzn.to/2L9C2zF)
    

The table of contents for this book is as follows:

*   1\. Introduction
    
*   2\. Digital snapshots
    
*   3\. Dealing with Image Noise
    
*   4\. Image Features
    
*   5\. More Image Features
    
*   6\. Camera Calibration
    
*   7\. Stereopsis
    
*   8\. Motion
    
*   9\. Shape from Single-image Cues
    
*   10\. Recognition
    
*   11\. Locating Objects in Space
    
*   A. Appendix
    

### Multiple View Geometry in Computer Vision

This book was written by [Richard Hartley](https://cecs.anu.edu.au/people/richard-hartley) and [Andrew Zisserman](https://www.robots.ox.ac.uk/~az/) and was published in 2004.

Multiple View Geometry in Computer Vision

Samples of some of the chapters are available in PDF format from the [book’s webpage](http://www.robots.ox.ac.uk/~vgg/hzbook/).

It is a reasonably advanced book (graduate level) on a specialized topic in computer vision, specifically on the problem and methods related to inferring geometry from multiple images.

> The book is divided into six parts and there are seven short appendices. Each part introduces a new geometric relation: the homography for background, the camera matrix for single view, the fundamental matrix for two views, the trifocal tensor for three views, and the quadrifocal tensor for four views.

— Page xiv, [Multiple View Geometry in Computer Vision](https://amzn.to/2LfHLE8), 2004.

*   [Book Homepage](http://www.robots.ox.ac.uk/~vgg/hzbook/)
    
*   [Book on Amazon](https://amzn.to/2LfHLE8)
    

The table of contents for this book is as follows:

*   1\. Introduction
    
*   PART 0. The Background: Projective Geometry, Transformations and Estimation
    
    *   2\. Projective Geometry and Transformations of 2D
        
    *   3\. Projective Geometry and Transformations of 3D
        
    *   4\. Estimation – 2D Projective Transformations
        
    *   5\. Algorithm Evaluation and Error Analysis
        
*   PART I. Camera Geometry and Single View Geometry
    
    *   6\. Camera Models
        
    *   7\. Computation of the Camera Matrix P
        
    *   8\. More Single View Geometry
        
*   PART II. Two-View Geometry
    
    *   9\. Epipolar Geometry and the Fundamental Matrix
        
    *   10\. 3D Reconstruction of Cameras and Structure
        
    *   11\. Computation of the Fundamental Matrix F
        
    *   12\. Structure Computation
        
    *   13\. Scene Planes and Homographies
        
    *   14\. Affine Epipolar Geometry
        
*   PART III. Three-View Geometry
    
    *   15\. The Trifocal Tensor
        
    *   16\. Computation of the Trifocal Tensor T
        
*   PART IV. N-View Geometry
    
    *   17\. N-Linearities and Multiple View Tensors
        
    *   18\. N-View Computational Methods
        
    *   19\. Auto-Calibration
        
    *   20\. Duality
        
    *   21\. Cheirality
        
    *   22\. Degenerate Configurations
        
*   PART V. Appendices

Top 3 Computer Vision Programmer Books
--------------------------------------

Programmer books are playbooks (e.g. O’Reilly books) written by experts, often developers and engineers, and are designed to be used as a reference by practitioners.

They focus mainly on techniques and the practical concerns of problem solving with a focus on example code and standard libraries. Techniques may be described briefly with relevant theory (math) but should probably not be used as a primary reference.

I’ve gathered a list of the top three playbooks based on their rank ordering in lists of top computer vision books and on recommendations on discussion websites.

The top three textbooks on computer vision are as follows (in no particular order):

*   [Learning OpenCV 3](https://amzn.to/2EqF0Pv), 2017.
    
*   [Programming Computer Vision with Python](https://amzn.to/2QKTaAL), 2012.
    
*   [Practical Computer Vision with SimpleCV](https://amzn.to/2QnFqMY), 2012.
    

Let’s take a closer look at each in turn, including the target audience and table of contents for each book.

### Learning OpenCV 3

This book was written by [Adrian Kaehler](https://www.linkedin.com/in/adriankaehler/) and [Gary Bradski](https://www.linkedin.com/in/garybradski/) and published in 2017. The subtitle of the book is “_Computer Vision in C++ with the OpenCV Library_.”

Learning OpenCV 3

The book focuses on teaching you how to use the OpenCV library, perhaps the premiere open source computer vision library. All code examples are in C++, suggesting that the target audience are professional developers looking to learn how to incorporate computer vision into their applications. Importantly, the authors are board members and founders of OpenCV.

It is a technical book and perhaps more an elaborated API documentation than a playbook.

> This book provides a working guide to the C++ Open Source Computer Vision Library (OpenCV) version 3.x and gives a general background on the field of computer vision sufficient to help readers use OpenCV effectively.

— [Learning OpenCV 3](https://amzn.to/2EqF0Pv), 2017.

This book may be considered an updated version of the older (2008) book Learning “[OpenCV: Computer Vision with the OpenCV Library](https://amzn.to/2QpYiuZ)” by the same authors.

*   [Book’s Homepage (source code)](https://github.com/oreillymedia/Learning-OpenCV-3_examples)
    
*   [Book on Amazon](https://amzn.to/2EqF0Pv)
    

The table of contents for this book is as follows:

*   1\. Overview
    
*   2\. Introduction to OpenCV
    
*   3\. Getting to Know OpenCV Data Types
    
*   4\. Images and Large Array Types
    
*   5\. Array Operations
    
*   6\. Drawing and Annotating
    
*   7\. Functions in OpenCV
    
*   8\. Image, Video and Data Files
    
*   9\. Cross-Platform and Native Windows
    
*   10\. Filters and Convolutions
    
*   11\. General Image Transforms
    
*   12\. Image Analysis
    
*   13\. Histograms and Templates
    
*   14\. Contours
    
*   15\. Background Subtraction
    
*   16\. Keypoints and Descriptors
    
*   17\. Tracking
    
*   18\. Camera Models and CAlibration
    
*   19\. Projection and Three-Dimensional Vision
    
*   20\. The Basics of Machine Learning in OpenCV
    
*   21\. StatModel: The Standard Model for Learning in OpenCV
    
*   22\. Object Detection
    
*   23\. Future of OpenCV
    

### Programming Computer Vision with Python

This book was written by [Jan Erik Solem](https://www.janeriksolem.net/) and published in 2012. The subtitle for the book is “Tools and algorithms for analyzing images.”

Programming Computer Vision with Python

A final draft version of the book is available from the [book’s website](http://programmingcomputervision.com/) in PDF format.

This is a hands-on book that focuses on teaching you how to perform basic computer vision tasks in Python, mostly with PIL, although with a basic introduction to OpenCV as well. I’m a fan of this book, although minor modifications are required to use updated libraries (e.g. [Pillow](https://github.com/python-pillow/Pillow)). An update to this book is due!

> The idea behind this book is to give an easily accessible entry point to hands-on computer vision with enough understanding of the underlying theory and algorithms to be a foundation for students, researchers, and enthusiasts.

— Page vii, [Programming Computer Vision with Python](https://amzn.to/2QKTaAL), 2012.

*   [Book Homepage](http://programmingcomputervision.com/)
    
*   [Book on Amazon](https://amzn.to/2QKTaAL)
    

The table of contents for this book is as follows:

*   1\. Basic Image Handling and Processing
    
*   2\. Local Image Descriptors
    
*   3\. Image to Image Mappings
    
*   4\. Camera Models and Augmented Reality
    
*   5\. Multiple View Geometry
    
*   6\. Clustering Images
    
*   7\. Searching Images
    
*   8\. Classifying Image Content
    
*   9\. Image Segmentation
    
*   10\. OpenCV
    

### Practical Computer Vision With SimpleCV

This book was written by [Kurt DeMaagd](https://www.linkedin.com/in/kurtdemaagd/), Anthony Oliver, [Nathan Oostendorp](http://oostendorp.net/), and [Katherine Scott](http://www.kscottz.com/), and was published in 2012. The subtitle of the book is “_The Simple Way to Make Technology See_.”

Practical Computer Vision with SimpleCV

This book teaches you how to perform basic computer vision operations using the SimpleCV library in Python. This provides a nice alternative to working with PIL (Pillow) or OpenCV, although I’m not convinced that SimpleCV has been broadly adopted (I’m happy to be proven wrong).

> Learn how to build your own computer vision (CV) applications quickly and easily with SimpleCV, an open source framework written in Python. Through examples of real-world applications, this hands-on guide introduces you to basic CV techniques for collecting, processing, and analyzing streaming digital images.

— [Practical Computer Vision with SimpleCV](https://amzn.to/2QnFqMY), 2012.

*   [Book Homepage](http://simplecv.org/book/)
    
*   [Book on Amazon](https://amzn.to/2QnFqMY)
    

The table of contents for this book is as follows:

*   1\. Introduction
    
*   2\. Getting to Know the SimpleCV Framework
    
*   3\. Image Sources
    
*   4\. Pixels and Images
    
*   5\. The Impact of Light
    
*   6\. Image Arithmetic
    
*   7\. Drawing on Images
    
*   8\. Basic Feature Detection
    
*   9\. FeatureSet Manipulation
    
*   10\. Advanced Features
