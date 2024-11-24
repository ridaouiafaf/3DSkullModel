I created a 3D Skull model from a head CT Scan Dataset (DICOM standard), using 3d Slicer and Autodesk Meshmixer.

I did the segmentation on 3D Slicer using the tools: Threshold, Islands, Manual Segmentation tool, Eraser. 
After using the Threshold, I only corrected the missed parts or the artfacts detected as bone on half of the head since our body is symmetric (not 100% but still). To avoid wasting time since I had a very critical deadline to submit the project.

Then, I refined it on Meshmixer using the Symmetric function on the well segmented half of the head and after that I used the Inspector tool to correct any missed microscopic holes.

Dataset Link on Kaggle: https://www.kaggle.com/datasets/trainingdatapro/computed-tomography-ct-of-the-brain
