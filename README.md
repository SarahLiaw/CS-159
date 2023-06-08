# Improving the Quantification of Predictive Uncertainty using Scalable Uncertainty-aware Models with Lower Dimensional Representations
Caltech CS 159 - Uncertainty Quantification <br />
Michelle Li & Sarah Liaw

Our project proposes an approach to improve the accuracy of predictive uncertainty in imaging analysis by combining the use of various dimension-reduction methods with Gaussian Processes (GP). In 2021, Wu et al proposed the use of Deep Kernel Learning (DKL), an approach that combines a neural network with a GP. The goal was that the intermediate feature space provided by the neural network would capture the main semantic information about the images. This allows the GP to focus on capturing the classification differences and provide uncertainty estimates as GPs work especially well with low dimensional input spaces. To demonstrate and expand on this fact, this project will propose approaches with Stochastic Variational DKL and PCA to draw a comparison between Wu et al.'s DKL. Both methods of which are either well known or intriguing methods used for dimensionality reduction. We will show accuracy of this approach using a medical bone-age dataset as provided in the RSNA Pediatric Bone Age Challenge.

Dataset for preprocessed images: https://drive.google.com/file/d/1bJnyfFUGcBSrnvxiNxmIT73x4oyKTF9O/view?usp=sharing

README Citations: <br />
 - RSNA Pediatric Bone Age Challenge can be found here: https://www.rsna.org/education/ai-resources-and-training/ai-image-challenge/rsna-pediatric-bone-age-challenge-2017 <br />
 - Wu, Z., Yang, Y., Gu, J., \ \&  Tresp, V. (2021). Quantifying predictive uncertainty in medical image analysis with deep kernel learning. arXiv preprint arXiv:2106.00638.
