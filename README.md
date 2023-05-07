Download Link: https://assignmentchef.com/product/solved-emth211-assignment-1
<br>
A1.1 The 100m sprint for women was first held in the 1928 Olympic Games. The event has been held in every Olympic Games since. The winning times are

<table width="351">

 <tbody>

  <tr>

   <td width="45">Year192819321936194819521956196019641968</td>

   <td width="201">Time12.2 11.9 11.5 11.9 11.5 11.5 11.0 11.411.0</td>

   <td width="70">Year197219761980198419881992199620002004</td>

   <td width="34">Time11.07 11.08 11.60 10.97 10.54 10.82 10.94 10.7510.93</td>

  </tr>

 </tbody>

</table>

Fit this data set with polynomials of degree 1, 2 and 3 using the QR decomposition of A. Check your results using MATLAB’S backslash operator. What is the error in each of these fits? In the case of the cubic fit, MATLAB issues a warning. Why does MATLAB do this? What can be done to avoid this (potential) problem? Use each of these fits to predict the winning time for the Beijing Olympic Games in 2008.

A1.2          A conic section (in the plane) is described implicitly by

Ax<sup>2</sup>+By<sup>2</sup>+Cxy+Dx+Ey+F=0.

In the file A1.mat on the EMTH211 Learn website, there is a matrix a 2×20 matrix X that has measurements of 20 points in the plane (first row is the x-coordinate and second row y-coordinate of each of these measurements). Using least squares, find the best conic section passing through these points.

A1.3 In the file A1.mat on the EMTH211 Learn website, is a matrix A which represents a 480×640 pixel, 256-level grayscale image. In order to view this image in MATLAB the colour map must be set to gray(256); that is

colormap(gray(256)) image(A)

<ul>

 <li>Compute the SVD for this matrix A. What is the largest and smallest singular value of A.</li>

 <li>Output the image based on only the 2, 6, 10, 15, 20, 30, 50 and 100 largest singular values are used (that is, all other singular values are set to zero).</li>

 <li>How much storage is require if only the k largest singular values are used (compute this as a percentage of the number of bytes taken to store the original image)?</li>

</ul>

In each of the cases of part (b), what is the storage required (as a percentage of the original file)?