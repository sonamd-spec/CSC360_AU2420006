## CSC360 – Session 2 Reflection

## 1. Computer Graphics

Computer Graphics is the field of using computers to create, display and work with images. It is useful for creating different types of visual content and graphical applications. In this session, I understood that graphics are not just about drawing; images can also be stored and represented as data.

### Digital Image Processing

Digital Image Processing is related to working with digital images and changing or analysing the information present in them. A digital image can be represented using values, which makes it possible for a computer to process it.

### Digital Image

A digital image can be thought of as a **matrix of values**. Each position in the matrix contains some information about that part of the image. For a colour image, the values can represent RGB (Red, Green and Blue) information.

### Black and White Image

In a black-and-white image, a single value can be used to represent the intensity of a pixel. The value gives information about how light or dark that particular pixel is.

---

## 2. Graphics and Image Processing

Both graphics and image processing deal with images, but they can be used for different purposes. Graphics can be used to create visual objects, while image processing focuses more on working with existing digital image information. These concepts can be useful in areas such as **astronomy and biomedical research**.

### Gene Expression Study

Another example discussed was gene expression. The values related to gene expression can be represented and studied using digital images or data. A higher value can indicate a higher level of gene expression, while a lower value can indicate a lower level.

---

## 3. Image as Information

I learned that an image is also a form of information. A digital image consists of pixels arranged in a matrix, and each pixel contains some value related to that particular position. This helped me understand how a computer can store an image in a structured form.

---

# 4. Raster Graphics

Raster graphics are made up of **pixels**. These pixels are arranged in rows and columns to form an image. Each pixel can store information such as colour or intensity.

One important thing I learned is that increasing the resolution generally means having more pixels and more image information. However, if a raster image is enlarged too much, individual pixels may become visible and the image can lose its quality. A digital photograph is a common example of a raster image.

---

# 5. Vector Graphics

Vector graphics work differently from raster graphics. Instead of storing an image as individual pixels, they use **geometrical shapes and mathematical information**. Lines, curves, circles and polygons can be represented using this method.

The main advantage is that vector graphics can be resized without the same pixelation problem as raster images. They are useful for things such as logos, diagrams and drawings made from shapes.

### Raster vs Vector Graphics

| Feature         | Raster Graphics      | Vector Graphics                    |
| --------------- | -------------------- | ---------------------------------- |
| Basic unit      | Pixels               | Geometric shapes                   |
| Representation  | Pixel matrix         | Mathematical/geometric information |
| Enlarging       | May become pixelated | Can be resized more easily         |
| Best suited for | Photographs          | Logos, diagrams and shapes         |
| Example         | Digital photograph   | Logo or geometric drawing          |

This comparison helped me understand why different types of graphics are used for different purposes.

---

# 6. Multimedia Formats

The session also covered some common digital formats.

### Raster

Raster images store visual information using pixels arranged in rows and columns. Enlarging them too much can reduce their visual quality.

### MP3

MP3 is a commonly used format for storing **audio**.

### MP4

MP4 is commonly used for **video**. A video can be understood as a sequence of images or frames shown at a particular speed, which creates the appearance of movement.

---

# 7. Java 2D Graphics

Java provides a framework for creating **2D graphics**. It can be used to create and display different graphical objects. Java can also be used for both 2D and 3D graphics.

### JFrame

**JFrame** works as the main window of a Java GUI application.

### JPanel

**JPanel** is an area inside the frame where graphical content can be displayed.

### Graphics Context

The **Graphics Context** provides the methods and tools needed to draw objects.

The basic flow can be understood as:

**JFrame → JPanel → Graphics Context → Drawing**

---

# 8. Basic Geometric Objects

Geometric shapes are the basic elements used for creating graphics. Some of the examples discussed were:

* Circle
* Square
* Rectangle
* Line
* Polygon

Different simple shapes can be combined to create more complicated graphical objects.

---

# 9. Geometric Transformations

Transformations are used when we want to change something about a graphical object, such as its position, size or direction. Three important transformations discussed were **translation, scaling and rotation**.

### 9.1 Translation

Translation means **moving an object** from one location to another without changing its basic shape or size.

### 9.2 Scaling

Scaling means **changing the size** of an object.

* Scaling up → object becomes larger
* Scaling down → object becomes smaller

### 9.3 Rotation

Rotation means **turning an object around a fixed point** by a particular angle.

| Transformation | What it does     |
| -------------- | ---------------- |
| Translation    | Moves the object |
| Scaling        | Changes the size |
| Rotation       | Turns the object |

---

# 10. Git and SSH

The class also introduced **Git and SSH**.

### Git

Git is used to track and manage changes made to files and source code.

### SSH

SSH, or Secure Shell, provides secure communication and remote access between computers.

I found this topic useful because these tools are commonly connected with programming and software development work.

---

# 11. Practical Projects

The concepts were also connected with some practical project ideas.

### Project 1 – Moving a Triangle

The first project was about creating a triangle and allowing the user to move it using the mouse. This project uses:

* Geometric objects
* Mouse interaction
* Translation
* Interactive graphics

### Project 2 – Zooming

The second project involved creating a program where the user can zoom in and zoom out. This demonstrates the concept of **scaling**, because the size of the object or view is changed.

---

# 12. Interpolators

An interpolator is used to find values between two given values. It is useful when something needs to gradually change from one value to another.

For example, if an object's position has to change from one point to another, intermediate values can help in creating that change.

---

# 13. Lines and Intersection

The class also covered drawing lines and perpendicular lines. A perpendicular line can be constructed so that it forms the required angle with another line.

### Intersection Point

When two lines meet at a point, that point is called their **intersection point**. The intersection can be found using the equations of the lines or through graphical methods.

---

# 14. Linux Machine

Linux was also discussed as an operating system that can be used for programming and software development. Some advantages of Linux over Windows discussed in the session included:



Open source

Free to use

Good security

Customisation

Good performance

Development-friendly environment

---

# Overall Reflection

computers represent and manipulate graphics. I have learnt about the difference between raster and vector graphics and how to develop graphical objects using the Java programming language. I have also covered such interesting concepts as translation, scaling, and rotation, and learnt about their applicability in computer graphics. The practical session introduced me to such software tools as Git, SSH, interpolators, and Linux which are used in graphic design and software development. The examples used in the sessions, including moving a triangle and zooming were illustrative and helped in the comprehension of the theoretical aspects of computer graphics.
