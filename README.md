I created a 3D Skull model from a head CT Scan Dataset (DICOM standard), using 3d Slicer and Autodesk Meshmixer.

I did the segmentation on 3D Slicer using the tools: Threshold, Islands, Manual Segmentation tool, and Eraser. 
After using the Threshold, I only corrected the missed parts or the artifacts detected as bone on half of the head since our body is symmetric (not 100% but still). I wanted to avoid wasting time since I had a very critical project submission deadline.
![Capture d’écran 2024-11-18 211851](https://github.com/user-attachments/assets/6ebd81cc-5f90-4bc0-9c8b-59e10979436f)
![Capture d’écran 2024-11-18 211916](https://github.com/user-attachments/assets/b85fed1a-d206-49b7-b0fe-2db1f16a4076)
![Capture d’écran 2024-11-18 211928](https://github.com/user-attachments/assets/71684078-1d59-462c-9461-88e7bf7938c4)


Then, I refined it on Meshmixer using the Symmetric function on the well-segmented half of the head and after that, I used the Inspector tool to correct any missed microscopic holes.
![Capture d’écran 2024-11-18 212406](https://github.com/user-attachments/assets/c29cba30-731c-4815-a05f-d981e7b15e77)
![Capture d’écran 2024-11-18 212427](https://github.com/user-attachments/assets/a74d2b89-a02c-4606-bcf6-2f43f3eaca05)
![Capture d’écran 2024-11-18 212450](https://github.com/user-attachments/assets/0d532506-be18-4106-a0fd-955b9a1b9f2c)
![Capture d’écran 2024-11-18 212503](https://github.com/user-attachments/assets/e80488d0-48f6-4a9f-b893-bdb3d2fcb96d)

Dataset Link on Kaggle: https://www.kaggle.com/datasets/trainingdatapro/computed-tomography-ct-of-the-brain
