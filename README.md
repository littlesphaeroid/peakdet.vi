peakdet.vi is a LabVIEW port of Ali Billaeur's peakdet MATLAB script (https://billauer.co.il/blog/2009/01/peakdet-matlab-octave/).

From Eli's original description:

When trying to find the local maxima and minima in some noisy signal, in many cases, we don’t really care about maxima and minima in the mathematical sense. We can see the peaks and valleys, and we want the computer to find them. This is what “peakdet” does. The trick here is to realize, that a peak is the highest point between “valleys”. What makes a peak is the fact that there are lower points around it. This strategy is adopted by “peakdet”: Look for the highest point, around which there are points lower by X on both sides.

Peakdet.vi returns peaks and valleys in formats useful for plotting in LabVIEW.

Check out the demo for a few examples.