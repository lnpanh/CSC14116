# Enhancing Document Image

## Problem Statement

### Overview
Enhancing document image is a fundamental stage in image processing which support scan images, convert images to text, and re-align shooting angles,...

The problem is divided into two main steps:
- Step 1: Align the photo, remove the excess background around
- Step 2: Adjust the brightness and contrast of the photo

Common applications where this problem applies are:
- Scanning function of iPhone Notes 
- CamScanner app


 
### Input and Output Data description
* Input: a document image is not facing toward the screen.
* Output: the document image (cut the background) faces toward the screen.
* Example of input and output:

![](https://i.imgur.com/8cfHARR.png)

*cre*: [dropbox.Tech, Jongmin Baek, Aug 16, 2016, Fast document rectification and enhancement](https://dropbox.tech/machine-learning/fast-document-rectification-and-enhancement)

* **Steps of processing the image from Input to Output**
    * Detect edges
    * Get the document's contour based on the detected edges above.
    * Apply transform to get the top-down view of the image.
    * Adjust the contrast and light to make the document easier to read.

### Should we need to apply parallel to speed up the running time of this problem? Is it available to be paralleled?
First of all, we discuss the benefit of parallel can help: 
* Parallel computing saves time, allowing the execution of applications in a shorter wall-clock time.
* Solve Larger Problems in a short point of time.
* Compared to serial computing, parallel computing is much better suited for modeling, simulating and understanding complex, real-world phenomena.
* Throwing more resources at a task will shorten its time to completion, with potential cost savings. Parallel computers can be built from cheap, commodity components.
* Many problems are so large and/or complex that it is impractical or impossible to solve them on a single computer, especially given limited computer memory.
* You can do many things simultaneously by using multiple computing resources.
* Can using computer resources on the Wide Area Network(WAN) or even on the internet.
* It can help keep you organized. If you have Internet, then communication and social networking can be made easier.
* It has massive data storage and quick data computations.
Secondly, we discuss why Enhance Document Image need parallel programming to speed up and applications of its and it is available to be paralleled.
* As we declare above, we have 4 steps to do so as to enhance and scanner a image into a online doc from a picture. And in every steps, we have so many tasks to do complicated. This leads to takes us quite big amount of time to do this serially. => Time
* The second benefit when using parallel that we can do many things simultaneously by using multiple computing resources. Example: In real world, we not only do a function for an object at the particular. Imagine that we have 4 pictures or even more to scan at the same time, we cannot wasting time by letting system assign this for single core while we can do this for all gpu and cpu cores that we have. So that’s why we can use multiple computing resources effectively and efficiently.

### Weekly plan

<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky"></th>
    <th class="tg-rk9a">Main task</th>
    <th class="tg-rk9a">Sub-task</th>
    <th class="tg-rk9a">Assignee</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-9hil" rowspan="5">W05</td>
    <td class="tg-9wq8" rowspan="3">Write report about problem statement</td>
    <td class="tg-0pky">Describe problem</td>
    <td class="tg-kgv7"><span style="color:#000">Lư Ngọc Liên</span></td>
  </tr>
  <tr>
    <td class="tg-0pky">Describe data</td>
    <td class="tg-kgv7"><span style="color:#000">Lâm Ngọc Phương Anh</span></td>
  </tr>
  <tr>
    <td class="tg-0pky">The need of parallel</td>
    <td class="tg-kgv7"><span style="color:#000">Võ Minh Tú</span></td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="2">Refer the process of different solutions</td>
    <td class="tg-0pky">Read idea</td>
    <td class="tg-0pky">All Team</td>
  </tr>
  <tr>
    <td class="tg-0pky">Note the strong point of each idea</td>
    <td class="tg-0pky">All Team</td>
  </tr>
</tbody>
</table>
