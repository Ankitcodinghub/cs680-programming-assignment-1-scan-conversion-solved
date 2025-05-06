# cs680-programming-assignment-1-scan-conversion-solved
**TO GET THIS SOLUTION VISIT:** [CS680 Programming Assignment 1-Scan Conversion Solved](https://www.ankitcodinghub.com/product/cs680-programming-assignment-1-scan-conversion-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91394&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS680 Programming Assignment 1-Scan Conversion Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Scan Conversion

## 1. Overview

This programming assignment is meant to acquaint you with scan conversion algorithms. You will implement two functions that perform rendering algorithms that draw lines and triangles.

### Basic Requirements

1. Write a line rendering function that uses Bresenham’s algorithm to draw lines, with support for smooth color interpolation, given vertex colors. For flat shading of the line, use the first vertex color. Implement your code at “TODO 1” in the drawLine() method in [Sketch.py](./Sketch.py).

2. Write a triangle rendering function. Your function should provide smooth bilinear interpolation of the vertex colors in smooth area fill mode. For flat shading of the triangle, use the first vertex color. Note: You cannot use the polygon scan fill algorithm given in the textbook or barycentric coordinates. Implement your code at “TODO 2” in the drawTriangle() method in [Sketch.py](./Sketch.py).

### Extra Credits

3. **(Required for CS680 Students)** Implement texture mapped area fill of triangles using bilinear interpolation. You should add a key interface callback “M” that toggles texture mapped area fill on/off. Implement your code at “TODO 3″ in the drawTriangle() function in [Sketch.py](./Sketch.py)

4. Implement anti-aliased rendering of lines and triangles. A control flag, which is toggled by “A” key on keyboard, will be fed to both drawLine() and drawTriangle() as an input argument. Implement your code in drawLine() and drawTriangle() methods conditioned by this control flag.

### Programming Style

5. For any modified or new added source file, you should include a brief explaination about what you did in this file at file heading and add your name to the author list. Your code should be readable with sufficient comments. You should use consistent variable naming and keep reasonable indentation. In python, we prefer to use reStructuredText format docstring, for more details about this format, please check [**here**](https://devguide.python.org/documenting/).

## 2. Resources

### 2.1 Start code

A Python Program skeleton, which includes basic classes, methods and main pipeline, are provided for you. You are expected to complete the sketch program by providing two missing functions using the code templates. There are comments in the skeleton code that will help guide you in writing your own subroutines.

### 2.2 Environment Setup

Installing the appropriate programming environment should be covered in a lab session. For more step by step instruction, please check [**this document**](./docs/build/html/InstallationInstructions.html).

### 2.3 User Interface

The user interface to the program is provided through mouse buttons and keyboard keys. Mouse and keyboard bindings have implemented for you. For toggles status, you can check control flags in Sketch class.

* **Left Mouse Button**: Places vertices for a line. For every two clicks, a line is drawn.

* **Right Mouse Button**: Places vertices for a triangle. For every three clicks, a triangle is drawn.

* **s** / **S**: Toggles smooth interpolation of color on/off for mouse drawn line/triangle. Status saved in doSmooth.

* **a** / **A**: Toggles anti-aliasing for mouse drawn line/triangle. Status saved in doAA.

* **m** / **M**: Toggles texture-mapping for mouse drawn line/triangle. Status saved in doTexture.

* **r** / **R**: Toggle random color assignment to new mouse drawn points. Status saved in random_color

* **c** / **C**: Clear the current screen.

* **t** / **T** / **DOWN** / **RIGHT**: Run the next test case.

* **UP** / **LEFT**: Run the last test case.

* **,** / **&lt;**: Decrease the number of steps for the line and triangle test cases.

* **.** / **&gt;**: Increase the number of steps for the line and triangle test cases.

### 2.4 Video Demo

We prepared a video demo for you, hope this can help you better understand your tasks and speed up your debugging process.

&lt;video width=”640″ height=”480″ controls&gt;

&lt;source src=”./docs/build/html/assets/PA1_demo.mp4″ type=”video/mp4″&gt;

&lt;/video&gt;

## 3. Submission (due by midnight, Tuesday, 9/21)

### 3.1 Source Code

Your program’s source files are to be submitted electronically on Gradescope. The code you submit should conform to the program assignment guidelines.

### 3.2 Demo

Part of your grade for this programming assignment will be based on your giving a short demo (5 minutes) during the CS480/680 scheduled labs following the assignment due date. You will be expected to talk about how your program works.

## 4. Grading

| Requirements | CS480 Credits | CS680 Credits |

| :—————————————————– | :———— | :———— |

| Line drawing with vertex color interpolation | 40 | 30 |

| Drawing triangles, including smooth fill and flat fill | 50 | 40 |

| Texture-mapped fill of triangles | 15(extra) | 20 |

| Anti-aliasing of lines and triangles | 10(extra) | 10(extra) |

| Programming Style | 10 | 10 |

## 5. Code Distribution Policy

You acknowledge this code is only for the course learning purpose. You should never distribute any part of this assignment, especially the completed version, to any public accessible website or open repository wihout our permission. Keep the code in your local computer or private repository is allowed. You should never share, sell, gift or copy the code in any format with any other person without our permission.

# Source Code Documentation

All methods you need to implement locates in Sketch.py and marked with TODO. If you need to find a help method or want to learn more about how the OpenGL work with our pipeline, please check detailed methods and classes documentation at

[**Programming Assignment 01 Documentation**](./docs/build/html/index.html)
