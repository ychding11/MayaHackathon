# Overview
----------

We applied an open source toolkit called OpenFace on Github. It can track human face, do Head
Pose Estimation, track Eye Gaze and do Facial Action Unit Recognition in real-time by a single
RGB camera. 

But it lacks a portable message system to send the tracked infomation to third party software to
driver them do interesting things conveniently. OsPack is a simple open source implementation for
OSC(open sound control). I integrate this library into OpenFace source code to enable it talk with
other software supporting OSC.

When received these data, third party software, here we choose Processing which is a popular develop 
tool within the visual arts, does deeper computing and assemble those received data into new format 
to drive a 3D human head model in Autodesk Maya by MEL command.

# Reference
----------

OpenFace: an open source  behavior analysis toolkit[WIKI](https://github.com/TadasBaltrusaitis/OpenFace/wiki)**
We use the following features of OpenFace.

- **OpenFace: an open source facial behavior analysis toolkit**
Tadas Baltrušaitis, Peter Robinson, and Louis-Philippe Morency,in *IEEE Winter Conference on Applications of Computer Vision*, 2016  

- **Constrained Local Neural Fields for robust facial landmark detection in the wild** Tadas Baltrušaitis, Peter Robinson, and Louis-Philippe Morency. 
in IEEE Int. *Conference on Computer Vision Workshops, 300 Faces in-the-Wild Challenge*, 2013.  

- **Rendering of Eyes for Eye-Shape Registration and Gaze Estimation** Erroll Wood, Tadas Baltrušaitis, Xucong Zhang, Yusuke Sugano, Peter Robinson, and Andreas Bulling 
in *IEEE International. Conference on Computer Vision (ICCV)*,  2015 

- **Cross-dataset learning and person-specific normalisation for automatic Action Unit detection** Tadas Baltrušaitis, Marwa Mahmoud, and Peter Robinson 
in *Facial Expression Recognition and Analysis Challenge*, 
*IEEE International Conference on Automatic Face and Gesture Recognition*, 2015 




