Project 0 Getting Started
====================

**University of Pennsylvania, CIS 565: GPU Programming and Architecture, Project 0**

* Author: Chhavi Sharma
  * [LinkedIn](https://www.linkedin.com/in/chhavi275/), [personal website](https://www.grasp.upenn.edu/people/chhavi-sharma), [twitter](), etc.
* Tested on: Windows 10, Intel Xeon CPU E5-2687W v3 @ 3.10GHz 22GB, NVIDIA TITAN V 12GB (SIGLab-VR1)


### README

Summary: In this project, we setup GPU development tools and verify that we can build, run, and do performance analysis.

Part 1: Fork & Clone

Part 2: Set up development environment

Part 2.0: Integrated Development Environment
	SYSTEM : Windows 10, Intel Xeon CPU E5-2687W v3 @ 3.10GHz 22GB, NVIDIA TITAN V 12GB (SIGLab-VR1)
	CMAKE  : CMAKE 3.14.6
	GPU    : NVIDIA TITAN V	 (compute capability = 7.0)


Part 2.1: CUDA
    CUDA   : CUDA 10.0


Part 2.2: WebGL

    Google Chrome WebGL support
    If step 2 doesn't show WebGL compatibility, then try the following:
        
        Enabling WebGL
            
            chrome://settings 
            System section: Use hardware acceleration 
            ![Chrome settings](/images/Chrome1.png)

            chrome://flags
            ![Chrome flags](/images/Chrome2.png)

        
        Checking WebGL status
            chrome://gpu
            [WebGL status](/images/Chrome3.png)


Part 2.3: DXR
Skipped due to unsupported GPU.

Part 3: Build & Run

    cuda-getting-started/src/ - source code.
    cuda-getting-started/external/ - Windows binaries and headers for GLEW and GLFW.

    cmake-build to generate cis565_getting_started.sln
    open sln in VS2017
    Build.
    Run. 

Part 4: Modify
	![Visual Studio Run](/images/output.png)


Part 5: Analyze
	![Nsight Performance Analysis](/images/performance.png)

Part 6: Nsight Debugging
    index == 1278
	![Nsight debugger](/images/warpinfo.png)
			