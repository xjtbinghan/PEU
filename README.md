# Pose Estimation and Neural Implicit Reconstruction Towards Non-cooperative Spacecraft Without Prior Information
This is an implementation of our work

# Abstract
Non-cooperative spacecraft pose estimation plays a crucial role in on-orbit servicing. However, existing pose estimation methods often assume CAD models of target objects as prior information, used for offline training or online template matching. This limits the generalization and universality of pose estimation methods. To explore a generic solution, this work proposes a pose estimation method for unknown spacecraft. Our method is not only independent of prior models or image priors of the target but also synchronously outputs pose parameters and aligned target texture models. Specifically, we employ three modules in parallel: pose tracking, neural object reconstruction, and target reference frame (TRF) estimation. Firstly, leveraging the knowledge of temporal data, we optimize the pose graph to provide stable tracking performance. Then, we use neural implicit representation to reconstruct the target texture model, with pose parameters jointly optimized during the reconstruction process. Finally, we propose TRFE-Net for online estimation of the TRF. The obtained TRF is used to correct the sensor reference frame (SRF), transforming the pose tracking and reconstruction problem from scene-centric to spaceraft-centric. Additionally, the PEU dataset was constructed specifically for pose estimation of unknown spacecraft. Comprehensive experiments show that although the proposed method reduces the need for prior information, it still achieves good performance across multiple objects and effectively handles large-scale motions, specular highlights, thin structures, and symmetric structures.

# PEU Dataset
The PEU dataset is coming soon

# Result on PEU-Track

# Result on PEU-cloud

# Bibtex
