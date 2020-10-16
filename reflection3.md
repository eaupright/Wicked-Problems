# Data Science Reflection #3: Oxford's New COVID-19 Test


Scientists that are a part of the Physics Department at Oxford University have developed a new 5-minute COVID test by utilizing machine learning. In using machine learning, they are able to detect COVID-19 virus particles and differentiate them from other seasonal flu viruses or coronaviruses. The test works directly on a throat swab taken from the patient, with no need to alter or prepare the sample. First, any virus particles that are found in the sample are tagged with a short fluorescent DNA strand. A microscope is then used to take pictures of the tagged particles in the test sample. From there, machine learning software uses the images to automatically identify the virus by detecting differences in how the fluorescent tag interacts with the surface makeup of the virus.


This test uses a 15-layer convolutional neural network (CNN) to classify different viral particles. The CNN was first trained on data sets of different combinations of four lab-grown virus strains and a virus-negative control. Then, the CNN was trained with clinical samples from patients who had tested negative for virus, positive for COVID-19, positive for influenza A, or positive for a seasonal coronavirus. Currently, the neural network has around 70% accuracy with clinical samples and will continue to improve as it’s testing increases and its exposure to different samples increases. The CNN also has a significantly lower sensitivity than conventional RT-PCR tests, although its sensitivity should also increase with continued testing and training.


This test is a breakthrough in virus detection in many ways. Primarily, because this test works directly on the sample taken from the patient, it does not need to be carried out in a laboratory setting. Therefore, it can be used in airports, offices, or schools, allowing for rapid mass testing that we are currently lacking in. This test also bypasses the issues current tests are having with supply issues.


##### References:
Andersson, M., Bickerton, E., Crook, D., Shiaelis, N., Tometzki, A., Peto, L.,McMahon, A., Hepp, C., Favard, C., Muriaux, D., Oakley, S., Vaughan, A., Matthews, P. C., Stoesser, N., Kapanidis, A. N., & Robb, N. C. (2020, October 13) *Virus detection and identification in minutes using single-particle imaging and deep learning*. MedRxiv.https://www.medrxiv.org/content/10.1101/2020.10.13.20212035v1.full.pdf+html
