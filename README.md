Caffe-Multi-Label

	The caffe version support Multi-Label.

	It can Automatically inferred label dimension.

Example:

	it support label like this：

	lfw_5590\Aaron_Eckhart_0001.jpg 10

	lfw_5590\Aaron_Eckhart_0012.jpg 84 161 92 169 122

	and
	
	lfw_5590\Aaron_Eckhart_0003.jpg 94.12 101.03 141.89 169.56 106.25 107.75 146.75 112.25

Useage:

	there two fils in the “/tools” folder: convert_imageset.cpp convert_imageset_labels.cpp

	convert_imageset.cpp is official version of caffe，convert_imageset_labels.cpp is my version which supported Multi-Label. They have same usage.

Attention:

	I convert labels to float in this version. A VERSION support template labels will come soon.
