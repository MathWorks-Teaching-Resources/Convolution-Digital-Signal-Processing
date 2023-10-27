
<a name="T_DEF03274"></a>
# <span style="color:rgb(213,80,0)">Convolution in Digital Signal Processing</span>
<a name="H_053613DF"></a>

[![View on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/97112-convolution-in-digital-signal-processing) or [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Convolution-Digital-Signal-Processing&project=Convolution.prj)

**Curriculum Module**

_Created with R2021a. Compatible with R2021a and later releases._

# Information

This curriculum module contains interactive [MATLAB® live scripts](https://www.mathworks.com/products/matlab/live-editor.html) and supporting data files centered around the fundamentals of convolution in digital signal processing. 

<a name="H_F00D98E4"></a>
## Background

You can use these live scripts as demonstrations in lectures, class activities, or interactive assignments outside class. This module covers the definition and computation of 1D and 2D convolution, as well as the concepts of linear time invariant systems and filtering. It also includes examples of audio and image manipulation using convolution.


The instructions inside the live scripts will guide you through the exercises and activities. Get started with each live script by running it one section at a time. To stop running the script or a section midway (for example, when an animation is in progress), use the <img src="Images/EndIcon.png" width="19" alt="EndIcon.png"> Stop button in the **RUN** section of the **Live Editor** tab in the MATLAB Toolstrip.

## Contact Us

Solutions are available upon instructor request. Contact the [MathWorks teaching resources team](mailto:onlineteaching@mathworks.com) if you would like to request solutions, provide feedback, or if you have a question.

<a name="H_30BC7141"></a>
## Prerequisites

This module assumes knowledge of MATLAB at the level of the [<u>MATLAB Onramp</u>](https://matlabacademy.mathworks.com/details/matlab-onramp/gettingstarted) – a free two-hour introductory tutorial that teaches the essentials of MATLAB.

<a name="H_330E72C3"></a>
## Getting Started
### Accessing the Module
### **On MATLAB Online:**

Use the [<img src="Images/OpenInMO.png" width="136" alt="OpenInMO.png">](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Convolution-Digital-Signal-Processing&project=Convolution.prj) link to download the module. You will be prompted to log in or create a MathWorks account. The project will be loaded, and you will see an app with several navigation options to get you started.

### **On Desktop:**

Download or clone this repository. Open MATLAB, navigate to the folder containing these scripts and double-click on [Convolution.prj](matlab: openProject("Convolution.prj")). It will add the appropriate files to your MATLAB path and open an app that asks you where you would like to start. 


Ensure you have all the required products ([listed below](#H_E850B4FF)) installed. If you need to include a product, add it using the Add-On Explorer. To install an add-on, go to the **Home** tab and select  <img src="Images/AddOnsIcon.png" width="16" alt="AddOnsIcon.png"> **Add-Ons** > **Get Add-Ons**. 

<a name="H_E850B4FF"></a>
## Products

MATLAB® and the Signal Processing Toolbox™ are used throughout. To run all of the examples in <samp>ConvolutionFilters.mlx</samp> requires the Image Processing Toolbox™ and the Deep Learning Toolbox™.

<a name="H_E8C62B23"></a>
# Scripts
## [**ConvolutionBasics.mlx**](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Convolution-Digital-Signal-Processing&project=Convolution.prj&file=ConvolutionBasics.mlx) 
|  | **In this script, students will...**  |
| :-- | :-- |
| <img src="Images/Conv1D.gif" width="171" alt="Conv1D.gif"> |<br>-  define and compute convolution of two 1-D signals <br>-  use FFT to compute convolution <br>-  define and compute circular convolution <br>-  achieve equivalence between circular and linear convolution  |

## [**ConvolutionLTI.mlx**](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Convolution-Digital-Signal-Processing&project=Convolution.prj&file=ConvolutionLTI.mlx) 
|  | **In this script, students will...** | **Application**  |
| :-- | :-- | :-- |
| <img src="Images/LTIPlot.png" width="171" alt="LTIPlot.png"> |<br>-  define a linear time invariant (LTI) system <br>-  identify the moving average operation as a simple LTI system <br>-  compute the output of an LTI system for an arbitrary input signal given its impulse response |<br>-  Transform a monophone signal to two channel stereo with reverberation  |

## [**ConvolutionFilters.mlx**](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Convolution-Digital-Signal-Processing&project=Convolution.prj&file=ConvolutionFilters.mlx) 
|  | **In this script, students will...** | **Applications**  |
| :-- | :-- | :-- |
| <img src="Images/EmbossedRose.png" width="171" alt="EmbossedRose.png"> |<br>-  explain the frequency domain implications of convolving two signals in the time domain <br>-  achieve equivalence between low pass filtering and convolution <br>-  define and compute convolution of two 2-D signals <br>-  perform spatial filtering of images to achieve effects such as blurring and embossing |<br>-  Blurring images <br>-  Sharpening images <br>-  Using convolution to identify parts of an image <br>-  Using pretrained convolutional neural network to identify images  |

## [**PracticeProblemSolns.mlx**](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Convolution-Digital-Signal-Processing&project=Convolution.prj&file=PracticeProblemSolns.mlx) 
# Related Courseware Modules
| **Courseware Module** | **Sample Content** | **Available on:**  |
| :-- | :-- | :-- |
| [**Binary Morphology in Image Processing**](https://www.mathworks.com/matlabcentral/fileexchange/94590-binary-morphology-in-image-processing) | <img src="Images/DilationAnimation.gif" width="171" alt="DilationAnimation.gif"> | [<img src="Images/OpenInFX.png" width="91" alt="OpenInFX.png">](https://www.mathworks.com/matlabcentral/fileexchange/94590-binary-morphology-in-image-processing)[<img src="Images/OpenInMO.png" width="136" alt="OpenInMO.png">](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Morphology-in-Image-Processing&project=Morphology.prj)[GitHub](https://github.com/MathWorks-Teaching-Resources/Morphology-in-Image-Processing)  |
| <br>[**Climate Data Visualization and Analysis**](https://www.mathworks.com/matlabcentral/fileexchange/110125-climate-data-visualization-and-analysis) | <img src="Images/image_9.png" width="171" alt="image_9.png"> | <br>[<img src="Images/OpenInFX.png" width="91" alt="OpenInFX.png">](https://www.mathworks.com/matlabcentral/fileexchange/110125-climate-data-visualization-and-analysis)<br>[<img src="Images/OpenInMO.png" width="136" alt="OpenInMO.png">](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Climate-Data-Visualization-and-Analysis&project=ClimateVis.prj)<br>[GitHub](https://github.com/MathWorks-Teaching-Resources/Climate-Data-Visualization-and-Analysis)  |


Or feel free to explore our other [modular courseware content](https://www.mathworks.com/matlabcentral/fileexchange/?q=tag%3A%22courseware+module%22&sort=downloads_desc_30d).

# Educator Resources
-  [Educator Page](https://www.mathworks.com/academia/educators.html) 
<a name="H_0FA5DA18"></a>
# Contribute 

Looking for more? Find an issue? Have a suggestion? Please contact the [MathWorks teaching resources team](mailto:%20onlineteaching@mathworks.com). If you want to contribute directly to this project, you can find information about how to do so in the [CONTRIBUTING.md](https://github.com/MathWorks-Teaching-Resources/Convolution-Digital-Signal-Processing/blob/release/CONTRIBUTING.md)  page on GitHub.


 *©* Copyright 2023 The MathWorks™, Inc


