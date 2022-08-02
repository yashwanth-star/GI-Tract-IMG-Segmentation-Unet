# GI-Tract-IMG-Segmentation-Unet
Gastrointestinal tract image segmentation using deep learning U-net architcture.

A Magnetic Resonance Imaging Guided Linear Accelerator (MRI-LINAC) is a radiotherapy method
used by oncologists to direct x-ray beams toward tumours to eradicate them. Cancerous tumours
are treated with radiotherapy by using MRI scans. This tumour is located between the stomach
and intestines on the gastrointestinal tract (GI-Tract) and changes position every few days.
The best feasible way to determine the position of a tumour is through MRI scans.
This allows oncologists to visualize the tumour's position and administer precise doses of
X-ray beams based on the tumour's presence. In order to deliver the dose to the tumour while
avoiding the organs, the X-ray beam must be angled to avoid the stomach and intestines.
The therapy is given for over 10 – 15 minutes after manually segmenting the tumour through
MRI scans for over a period of 1 – 6 weeks.
The oncologist must manually frame the position of the tumour and treat it since the tumour is
between the stomach and the intestine. So, this takes hours together which is a very painful task
for the patients to tolerate. By using deep learning, the segmented tumour treatment can be
accelerated, and treat a significantly higher number of patients.
Thus, patients can receive more effective treatment. By using the deep learning model, we can
automatically distinguish the stomach and intestine from tumours using MRI scans. Without
deep learning methods, this is a labour-intensive and time-consuming process that can easily
extend treatment time from 15 minutes to an hour. Using deep learning this process speed can
be increased and will help patients receive more effective treatment through the image
segmentation process.
The data used are the Xrays scans of the patients which are each 16-bit grayscale PNG format.
Models are constructed using convolutional neural networks, which consist of three layers:
convolutional layer, pooling layer, and fully connected layer. U-NET creates segmentation
masks from input images using deep learning convolutional networks. The oncologist or user
can then input the 16-bit x-ray grayscale images and get the segmented output after building
the deep learning model.
