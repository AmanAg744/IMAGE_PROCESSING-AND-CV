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
