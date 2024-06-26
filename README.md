# Higuchi Fractal Dimension with a multidimensional approach for color images
Multidimensional and Multiscale Higuchi dimension for the analysis of histological images

Paper: https://ieeexplore.ieee.org/abstract/document/9313575

Implementation of the paper above. It allows the computation of the higuchi fractal dimension for color images.

Related publications: 
1. https://ieeexplore.ieee.org/document/9854418
2. https://www.mdpi.com/2076-3417/14/3/1084

## Requirements
Verify that version 9.6 (R2019a) of the MATLAB Runtime is installed.   

If not, you can download it in https://www.mathworks.com/products/compiler/matlab-runtime.html


## Examples

You can compute the multidimensional and multiscale higuchi dimension for one single color image as shown in ```example.m``` or as:

``` matlab
Hm = Hm_RBG_image(image, Lmax, kmax); 
```

Or you can calculate the multidimensional and multiscale Higuchi Dimension for a dataset, as shown in ```example2.m```

# Higuchi Dimension
The Higuchi Dimension for grey scale images is available in:

Jesús Monge-Álvarez (2022). Higuchi and Katz fractal dimension measures (https://www.mathworks.com/matlabcentral/fileexchange/50290-higuchi-and-katz-fractal-dimension-measures), MATLAB Central File Exchange. Retrieved April 28, 2022.

It can be use by:

```matlab
HFD = Higuchi_FD(serie, Kmax) 
```
