BranchAnalysis (2D/3D)
=======================

This plugin tags all pixel/voxels in a skeleton image and then counts all its junctions, triple and quadruple points and branches, and measures their average and maximum length. 
The tags are shown in a new window displaying every tag in a different color. 

It then finds the longest shortest path of the medial as also the branches from the medial. 
For each of the pixels/voxels in the branches and the spine, it computes the thickness - and then some metrics on those - such as the min, max, mean ...

You can find it under Morphometry>Branch Analysis (2D/3D).

For further details, please see the:
- documentation http://fiji.sc/AnalyzeSkeleton
- publication: http://www3.interscience.wiley.com/journal/123322233/abstract

