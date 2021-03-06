# neuralnet-mcg

Convolutional neural networks (CNNs), and their possible uses in
electrocardiography and magnetocardiography are explored. A CNN that
diagnoses myocardial infarction in electrocardiograms (ECGs) taken from
the Physikalisch Technische Bundesanstalt (PTB) diagnostic database is
described. This CNN has a diagnosis
accuracy of 99.8% in unseen patients, on par with state of the art
machine learning methods. CNNs that diagnose
magnetocardiograms (MCGs) generated by a magnetocardiograph developed by
Mooney et al are described. With a best diagnostic accuracy
of $(88 \pm 3)\%$, these CNNs outperform results obtained by
Kangwanariyakul et al, Fenici et al, Tantimongcolwat et al, and Wilson. 
Through a moving window
method, the diagnostic powers of different segments of ECG and MCG are
found. Due to the platform agnosticity afforded by CNN’s automated
feature extraction, the methods described here can be easily adapted to
a wide range of vital signs, such as magnetoencephalography,
electroencephalography, and ballistocardiography. The 3D CNN developed
is highly portable; two MCG devices with different sensor arrangements
can interpolate to an identically shaped output. Therefore, the CNN can
be trained on one MCG device, and deployed on another dissimilar one.

Please see the full report for a more in depth explanation of the algorithm.
