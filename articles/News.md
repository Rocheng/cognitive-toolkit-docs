---
title:   News
author:    chrisbasoglu
date:    04/06/2017
ms.author:   cbasoglu
ms.date:   04/06/2017
ms.custom:   cognitive-toolkit
ms.topic:   conceptual
ms.service:  Cognitive-services
ms.devlang:   NA
---

# News

## April 2017
***2017-03-31.* V 2.0 RC 1 **  
With Release Candidate 1 the Microsoft Cognitive Toolkit enters the final set of enhancements before release of the production version of CNTK v.2.0. We expect no breaking changes before the release of the production version, but we are eager to hear your feedback!

Highlights:
* The release candidate contains [all changes and improvements introduced in CNTK 2.0 during beta phase](./CNTK-2.0-Beta-Highlights.md).
* Enables Caffe-converted pretrained models on image classification including AlexNet, ResNet, VGG and BN-Inception. 
* Slice now supports multiple-axis slicing.
* Improves performance and memory footprint
* Improvements in the [device selection API](./ReleaseNotes/CNTK_2_0_RC_1_Release_Notes.md).
* New Python [model debugging functions](https://www.cntk.ai/pythondocs/cntk.debugging.html#module-cntk.debugging.debug).
* Improvements in Python and C# API. See the [release notes](./ReleaseNotes/CNTK_2_0_RC_1_Release_Notes.md) for detailed description.
* New file names for [CNTK libraries and dlls](./CNTK-Shared-Libraries-Naming-Format.md).
* Various bug fixes.

The [release notes](./ReleaseNotes/CNTK_2_0_RC_1_Release_Notes.md) contain an overview. 
Get the release from the [CNTK Releases Page](https://github.com/Microsoft/CNTK/releases).

## March 2017
***2017-03-24.* Important Note breaking changes**
There are breaking changes in master compared to beta15, click [here](./Breaking-changes-in-Master-compared-to-beta15.md) for more information.

***2017-03-16.* V 2.0 Beta 15 Release available at Docker Hub**  
CNTK V 2.0 Beta 15 Runtime packages are now available as [Public Images at Docker Hub](https://hub.docker.com/r/microsoft/cntk/).  
See more on CNTK as Docker Images in this [Wiki article](./CNTK-Docker-Containers.md).

***2017-03-15.* V 2.0 Beta 15 Release**  
Highlights of this Release:
*  In addition to pre-existing python support, added support for TensorBoard output in BrainScript. [Read more here](./Using-TensorBoard-for-Visualization.md).
* Learners can now be implemented in pure Python by means of `UserLearners`. [Read more here](https://www.cntk.ai/pythondocs/extend.html#user-learners).
* New debugging helpers: `dump_function()`, `dump_signature()`.
* Tensors can be indexed using advanced indexing. E.g. `x[[0,2,3]]` would return a tensor that contains the first, third and fourth element of the first axis.
* Significant updates in the [Layers Library](https://www.cntk.ai/pythondocs/layerref.html) of Python API. See [Release Notes](./ReleaseNotes/CNTK_2_0_beta_15_Release_Notes.md) for detailed description.
* Updates and [new examples](./CNTK-Eval-Examples#examples-for-evaluating-multiple-requests-in-parallel) in C# API.
* Various bug fixes.

See more in the [Release Notes](./ReleaseNotes/CNTK_2_0_beta_15_Release_Notes.md).  
Get the Release from the [CNTK Releases page](https://github.com/Microsoft/CNTK/releases).

## February 2017
***2017-02-28.* V 2.0 Beta 12 Release available at Docker Hub**  
CNTK V 2.0 Beta 12 Runtime packages are now available as [Public Images at Docker Hub](https://hub.docker.com/r/microsoft/cntk/).  
See more on CNTK as Docker Images in this [Wiki article](./CNTK-Docker-Containers.md).

***2017-02-23.* V 2.0 Beta 12 Release**  
Highlights of this Release:
* New and updated features: new activation functions, support of `Argmax` and `Argmin`, improved performance of `numpy` interop, new functionality of existing operators, and more.
* [CNTK for CPU on Windows can now be installed via `pip install` on Anaconda 3](./Setup-CNTK-on-your-machine.md). Other configurations will be enabled soon.
* HTK deserializers are now exposed in Python. All deserializers are exposed in C++.
* The memory pool implementation of CNTK has been updated with a new global optimization algorithm. Hyper memory compression has been removed.
* New features in C++ API.
* [New Eval examples for RNN models](https://github.com/Microsoft/CNTK/blob/master/Examples/Evaluation/CNTKLibraryCSEvalCPUOnlyExamples/CNTKLibraryCSEvalExamples.cs).
* New [CNTK NuGet Packages](./NuGet-Package.md) with CNTK V2 C++ Library.

See more in the [Release Notes](./CNTK_2_0_beta_12_Release_Notes.md).  
Get the Release from the [CNTK Releases page](https://github.com/Microsoft/CNTK/releases).

***2017-02-13.* V 2.0 Beta 11 Release available at Docker Hub**  
CNTK V 2.0 Beta 11 Runtime packages are now available as [Public Images at Docker Hub](https://hub.docker.com/r/microsoft/cntk/).  
See more on CNTK as Docker Images in this [Wiki article](./CNTK-Docker-Containers.md).

***2017-02-10.* V 2.0 Beta 11 Release**  
Highlights of this Release:
* New and updated features: reduce_prod, reductions across all axes, denominator sharing, memory improvement, & more...
* New Tutorials and Examples:
  * [Transfer learning example to train custom image classifiers](https://github.com/Microsoft/CNTK/tree/v2.0.beta11.0/Examples/Image/TransferLearning).
* New [CNTK NuGet Packages](./NuGet-Package.md).
  * Note a *breaking change* due to Assembly Strong Name enabling. See [Release Notes](./ReleaseNotes/CNTK_2_0_beta_11_Release_Notes.md).

See more in the [Release Notes](./ReleaseNotes/CNTK_2_0_beta_11_Release_Notes.md).  
Get the Release from the [CNTK Releases page](https://github.com/Microsoft/CNTK/releases).

***2017-02-08.* V 2.0 Beta 10 Release available at Docker Hub**  
CNTK V 2.0 Beta 10 Runtime packages are now available as [Public Images at Docker Hub](https://hub.docker.com/r/microsoft/cntk/).  
See more on CNTK as Docker Images in this [Wiki article](./CNTK-Docker-Containers.md).

***2017-02-01.* V 2.0 Beta 10 Release**  
Highlights of this Release:
* New and updated core and Python API features ([Operators with UserFunctions](https://www.cntk.ai/pythondocs/extend.html), [Tensorboard support](./Using-TensorBoard-for-Visualization.md), [Python API Fast R CNN](./Object-Detection-using-Fast-R-CNN.md)).
* Improved speed of CrossEntropyWithSoftmax and ClassificationError for sparse labels.
* New Tutorials and Examples:
  * A Python version of the deconvolution layer and image auto encoder example was added ([Example **07_Deconvolution** in *Image - Getting Started*](https://github.com/Microsoft/CNTK/tree/v2.0.beta10.0/Examples/Image/GettingStarted)).
  * A Python distributed training example for image classification using AlexNet was added, cf. [here](https://github.com/Microsoft/CNTK/tree/v2.0.beta10.0/Examples/Image/Classification/AlexNet/Python)
  * [Basic implementation of Generative Adversarial Networks (GAN) networks](https://github.com/Microsoft/CNTK/blob/v2.0.beta10.0/Tutorials/CNTK_206_Basic_GAN.ipynb)
  * [Training with Sampled Softmax](https://github.com/Microsoft/CNTK/blob/v2.0.beta10.0/Tutorials/CNTK_207_Training_with_Sampled_Softmax.ipynb)
* New [CNTK NuGet Packages](./NuGet-Package.md).

See more in the [Release Notes](./ReleaseNotes/CNTK_2_0_beta_10_Release_Notes.md).
Get the Release from the [CNTK Releases page](https://github.com/Microsoft/CNTK/releases).

## January 2017
***2017-01-25.* V 2.0 Beta 9 Release available at Docker Hub**  
CNTK V 2.0 Beta 9 Runtime packages are now available as [Public Images at Docker Hub](https://hub.docker.com/r/microsoft/cntk/).  
See more on CNTK as Docker Images in this [Wiki article](./CNTK-Docker-Containers.md).

***2017-01-25.* 1bit-SGD Code is relocated to GitHub. Submodule configuration update is required for affected users**  
This news is related to users who are working with CNTK code base. If you use Binary or Docker Runtime Images installation you may ignore it.

Effective January 25, 2017 CNTK [1-bit Stochastic Gradient Descent (1bit-SGD)](./Enabling-1bit-SGD.md) and [BlockMomentumSGD](./Multiple-GPUs-and-machines#22-block-momentum-sgd) code is moved to a new Repository in GitHub.

If you cloned CNTK Repository with [1bit-SGD enabled](./Enabling-1bit-SGD.md) *prior to January 25, 2017* you need to update git submodule configuration as described in [this Wiki article](./Update-1bit-SGD-Submodule-Location.md).

***2017-01-20.* V 2.0 Beta 9 Release**  
Highlights of this Release:
* Default Python version is now 3.5 (relates to default parameters in client installations as well as [Runtime Images at Docker Hub](./CNTK-Docker-Containers.md)).
* New and updated core and Python API features.
* New Tutorials and Examples:
  * Deconvolution layer and image auto encoder example using deconvolution and unpooling ([Example **07_Deconvolution** in *Image - Getting Started*](https://github.com/Microsoft/CNTK/tree/v2.0.beta9.0/Examples/Image/GettingStarted)).
  * [Basic autoencoder with MNIST data](https://github.com/Microsoft/CNTK/blob/v2.0.beta9.0/Tutorials/CNTK_105_Basic_Autoencoder_for_Dimensionality_Reduction.ipynb).
  * [LSTM Timeseries with Simulated Data (Part A)](https://github.com/Microsoft/CNTK/blob/v2.0.beta9.0/Tutorials/CNTK_106A_LSTM_Timeseries_with_Simulated_Data.ipynb). (More will come in the next Releases)
* New [CNTK NuGet Packages](./NuGet-Package.md).

See more in the [Release Notes](./ReleaseNotes//CNTK_2_0_beta_9_Release_Notes.md).  
Get the Release from the [CNTK Releases page](https://github.com/Microsoft/CNTK/releases).

***2017-01-19.* V 2.0 Beta 8 Release available at Docker Hub**  
CNTK V 2.0 Beta 8 Runtime packages are now available as [Public Images at Docker Hub](https://hub.docker.com/r/microsoft/cntk/).  
See more on CNTK as Docker Images in this [Wiki article](./CNTK-Docker-Containers.md).

***2017-01-16.* V 2.0 Beta 8 Release**  
Highlights of this Release:
* Support of Python v. 2.7, 3.4, and 3.5. See [binary and source setup](./Setup-CNTK-on-your-machine.md) instructions to find out about how to select Python version.
* New Python API features.
* New Python example [Feature extraction using a trained model in Python API](https://github.com/Microsoft/CNTK/tree/v2.0.beta8.0/Examples/Image/FeatureExtraction).
* Support of [Visual Studio 2015](./Setup-Migrate-VS13-to-VS15.md) for Windows version.
* Introduction of [C# API in CNTK Evaluation Library](./CNTK-Library-Evaluation-on-Windows#using-the-cntk-library-managed-api) and a new set of [CNTK NuGet Packages](./NuGet-Package.md).
* CNTK Runtime packages are now available as [Public Images at Docker Hub](./CNTK-Docker-Containers.md). (**Beta 7** is currently available; Beta 8 Images availability will be announced separately in a few days)
* Version 3 of [CNTK Custom MKL Library](https://cntk.ai/mkl/) is available.

See more in the [Release Notes](./CNTK_2_0_beta_8_Release_Notes.md).  
Get the Release from the [CNTK Releases page](https://github.com/Microsoft/CNTK/releases).

***2017-01-10.* CNTK for Windows supports Visual 2015**

If you pull or merge the master branch, CNTK will now require Visual Studio 2015 to build on Windows. There are two ways to move your development environment to Visual Studio 2015:

* [Migrate VS2013 to VS2015](./Setup-Migrate-VS13-to-VS15.md): This gives you a fine grained control over where components are installed 
* [Script driven setup](./Setup-CNTK-with-script-on-Windows.md): This gives you an mostly automated migration to Visual Studio 2015

## Earlier News

* [News of 2016](./News-2016.md)