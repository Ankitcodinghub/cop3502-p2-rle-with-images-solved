# cop3502-p2-rle-with-images-solved
**TO GET THIS SOLUTION VISIT:** [COP3502  P2: RLE with Images Solved](https://www.ankitcodinghub.com/product/cop3502-p2-rle-with-images-solution/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;30195&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;&nbsp;COP3502  &nbsp;P2: RLE with Images  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<h1>Overview</h1>
In this project students will develop routines to encode and decode data for images using run-length encoding (RLE). Students will implement encoding and decoding of raw data, conversion between data and strings, and display of information by creating procedures that can be called from within their programs and externally. This project will give students practice with loops, strings, arrays, methods, and type-casting.

<h2>Run-Length Encoding</h2>
RLE is a form of lossless compression used in many industry applications, including imaging. It is intended to take advantage of datasets where elements (such as bytes or characters) are repeated several times in a row in certain types of data (such as pixel art in games). Black pixels often appear in long “runs” in some animation frames; instead of representing each black pixel individually, the color is recorded once, following by the number of instances.

&nbsp;

<table width="160">
<tbody>
<tr>
<td width="24"><strong>0 0 </strong></td>
<td width="36"><strong>2 2 2 </strong></td>
<td width="72"><strong>0 0 0 0 0 0 </strong></td>
<td width="28"><strong>2 2 </strong></td>
</tr>
</tbody>
</table>
<table width="119">
<tbody>
<tr>
<td width="24"><strong>2 0 </strong></td>
<td width="24"><strong>3 2 </strong></td>
<td width="24"><strong>6 0 </strong></td>
<td width="24"><strong>2 2 </strong></td>
<td width="23"><strong>1 0</strong><strong>_</strong></td>
</tr>
</tbody>
</table>
For example, consider the first row of pixels from the pixel image of a gator (shown in <strong>Figure 1</strong>). The color back is “0”, and green is “2”:

<strong>&nbsp;</strong>

Flat (unencoded) data: <strong>0</strong><strong>_ </strong>

<strong>&nbsp;</strong>

Run-length encoded data: .

<strong>Figure 1 – Gator Pixel Image </strong>

The encoding for the entire image in RLE (in hexadecimal) – width, height, and pixels – is:

&nbsp;

<table width="531">
<tbody>
<tr>
<td width="24"><strong>2 0 </strong></td>
<td width="24"><strong>3 2 </strong></td>
<td width="24"><strong>6 0 </strong></td>
<td width="24"><strong>2 2 </strong></td>
<td width="24"><strong>2 0 </strong></td>
<td width="24"><strong>1 2 </strong></td>
<td width="26"><strong>1 F </strong></td>
<td width="24"><strong>1 0 </strong></td>
<td width="24"><strong>7 2 </strong></td>
<td width="28"><strong>1 A </strong></td>
<td width="26"><strong>F 2 </strong></td>
<td width="24"><strong>1 0 </strong></td>
<td width="24"><strong>9 2 </strong></td>
<td width="24"><strong>3 0 </strong></td>
<td width="24"><strong>1 2 </strong></td>
<td width="24"><strong>1 0 </strong></td>
<td width="24"><strong>3 2 </strong></td>
<td width="24"><strong>6 0 </strong></td>
<td width="24"><strong>3 2 </strong></td>
<td width="24"><strong>3 0 </strong></td>
<td width="24"><strong>8 2 </strong></td>
<td width="20"><strong>5 0 </strong></td>
</tr>
</tbody>
</table>
<strong>1 E |1 6 </strong>

\W/ \H/ \——————————————PIXELS———————————————–/

&nbsp;

In this project students will be encoding and decoding images (on the console) using this approach.

&nbsp;

<h2>Image Formatting</h2>
The images are stored in <strong>uncompressed / unencoded</strong> format natively. In addition, there are a few other rules to make the project more tractable:

&nbsp;

<ol>
<li>Images are stored as an array of bytes, with the first two bytes holding image width and height.</li>
<li>Pixels will be represented by a number between 0 and 15 (representing 16 unique colors).</li>
<li>No run may be longer than 15 pixels; if any pixel runs longer, it should be broken into a new run.</li>
</ol>
&nbsp;

For example, the chubby smiley image (<strong>Figure 2</strong>) would contain the data shown in <strong>Figure 3</strong>.

&nbsp;

<strong>Figure 2 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Figure 3 – Data for “Chubby Smiley” </strong>

<h1>Requirements</h1>
Student programs must present a menu when run in standalone mode and must also implement several methods, defined below, during this assignment.

&nbsp;

<h2>Standalone Mode (Menu)</h2>
When run as the program driver via the main() method, the program should:

&nbsp;

<ul>
<li>Display welcome message</li>
<li>Display color test (<strong><sub>testRainbow</sub></strong>)</li>
<li>Display the menu</li>
<li>Prompt for input</li>
</ul>
&nbsp;

<u>Note: for colors to properly display, it is highly recommended that student</u> <u>install the “CS1” theme on the project page.</u>

&nbsp;

&nbsp;

There are five ways that should be provided to load data into the program and four ways the program must be able to display data to the user.

&nbsp;

<u>Loading a File</u>

Accepts a filename from the user and invokes <strong><sub>ConsoleGfx.loadFile()</sub></strong>:

Select a Menu Option: <strong>1</strong>

Enter name of file to load: <strong>testfiles/uga.gfx</strong>

&nbsp;

<u>Loading the Test Image</u> Loads <strong><sub>ConsoleGfx.testImage</sub></strong>:

Select a Menu Option: <strong>2</strong>_

Test image data loaded._

&nbsp;

<u>Reading RLE String</u>

Reads RLE data from the user in decimal notation with delimiters (smiley example):

Select a Menu Option: <strong>3</strong>

Enter an RLE string to be decoded: <strong>28:10:6B:10:10B:10:2B:10:12B:10:2B:10:5B:20:11B:10:6B:10</strong>

&nbsp;

<u>Reading RLE Hex String</u>

Reads RLE data from the user in hexadecimal notation <strong>without</strong> delimiters (smiley example):

Select a Menu Option: <strong>4</strong>

Enter the hex string holding RLE data: <strong>28106B10AB102B10CB102B105B20BB106B10</strong>

&nbsp;

<u>Reading Flat Data Hex String</u>

Reads raw (flat) data from the user in hexadecimal notation (smiley example):

Select a Menu Option: <strong>5</strong>

Enter the hex string holding flat data:<strong> 880bbbbbb0bbbbbbbbbb0bb0bbbbbbbbbbbb0bb0bbbbb00bbbbbbbbbbb0bbbbbb0</strong>

&nbsp;

<u>Displaying the Image</u>

Displays the current image by invoking the <strong>ConsoleGfx.displayImage()</strong> method.

&nbsp;

<u>Displaying the RLE String</u>

Converts the current data into a human-readable RLE representation (with delimiters):

Select a Menu Option: <strong>7</strong>

RLE representation: 28:10:6b:10:10b:10:2b:10:12b:10:2b:10:5b:20:11b:10:6b:10

&nbsp;

<u>Displaying the RLE Hex Data</u>

Converts the current data into a RLE hexadecimal representation (<strong>without</strong> delimiters):

Select a Menu Option: <strong>8</strong>

RLE hex values: 28106b10ab102b10cb102b105b20bb106b10

&nbsp;

<u>Displaying the Flat Hex Data</u>

Displays the current raw (flat) data in hexadecimal representation (<strong>without</strong> delimiters):

Select a Menu Option: <strong>9</strong>

Flat hex values: 880bbbbbb0bbbbbbbbbb0bb0bbbbbbbbbbbb0bb0bbbbb00bbbbbbbbbbb0bbbbbb0

&nbsp;

<h2>Class Methods</h2>
Student classes are required to provide the following methods with the defined behaviors.

&nbsp;

<u>public static int countRuns(byte[] flatData)</u>

Returns the number of runs of data in an image data set. This can be used to prepare the RLE representation of a set of data in binary or string-based format.

&nbsp;

<u>public static int getDecodedLength(byte[] rleData)</u>

Returns the total size of a set of data in bytes once the given RLE data is decompressed. This can be used to decode RLE data into individual data points (such as pixels).

&nbsp;

<u>public static byte[] encodeRle(byte[] flatData)</u>

Returns an encoding (in RLE) of the raw data passed in. This is used to generate the RLE representation of a data set for later viewing or storage.

&nbsp;

<u>public static byte[] decodeRle(byte[] rleData)</u>

Returns the decoded data set from RLE encoded data. This is used to decompress RLE data for use.

&nbsp;

<u>public static String toRleString (byte[] rleData)</u>

Translates RLE data into a human-readable representation (with delimiters – see examples in standalone section.)

&nbsp;

<u>public static String toHexString (byte[] data)</u>

Translates data (RLE or raw) a hexadecimal string (without delimiters – see examples in standalone section.)

&nbsp;

<u>public static byte[] stringToRle(String rleString)</u>

Translates a string in human-readable RLE format (with delimiters) into RLE byte data.

&nbsp;

<u>public static byte[] stringToData(String dataString)</u>

Translates a string in hexadecimal format into byte data (can be raw or RLE).

<em>&nbsp;</em>

<h1>Submissions</h1>
<strong>NOTE</strong>: Your output must match the example output *exactly*. If it does not, <strong><em>you will not receive full credit for your submission</em></strong>!

&nbsp;

File: &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; RleProgram.java

Method: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Submit on ZyLabs

&nbsp;

<u>Do not submit any other files</u>!
