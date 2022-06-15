# Enhancing Document Image

## Problem Statement

### Overview
@NL


 
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
@MT



### Weekly plan

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-9wq8{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-9hil{background-color:#FFE599;border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-rk9a{background-color:#B6D7A8;border-color:inherit;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-kgv7{border-color:inherit;color:#00E;text-align:left;vertical-align:top}
</style>
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
