# 3d-mesh-tutorial


This is the code produced by following the tutorial located here:

https://matplotlib.org/3.1.0/gallery/mplot3d/surface3d.html

This is run in Python3. As it stands, the resolution is still extremely choppy. I attempted to increase the resolution by decreasing the step size in the X and Y value range, though that did not appear to have the desired effect. 

I was able to prove that going the other direction is radically noticeable - dropping the step size to 0.5 produced a mesh plot that was completely angular. The inverse is unfortunately not apparent. The plot is definitely smoother than that of 0.5, but at 0.0005 the surfaces are still notieceably planar.

Further tinkering to come.

