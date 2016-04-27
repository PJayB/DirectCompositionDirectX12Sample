DirectComposite Sample (DirectX 12)
===================================

This sample demonstrates how to implement DirectComposition alongside DirectX 12. DirectComposition allows you to efficiently composite your rendered scene onto other windows using hardware acceleration.

For more information, see: 

- [MSDN page for DirectComposition](https://msdn.microsoft.com/en-us/library/windows/desktop/hh437371(v=vs.85).aspx)
- [Tutorial and comparison of DirectComposition vs. GDI-based techniques](http://blog.pjblewis.com/?p=95)

![DirectComposition allows efficient alpha-blending with other windows](http://i.imgur.com/PAMvWCG.png)

Acknowledgements & Disclaimer
=============================

This sample is based on Microsoft's [D3D12HelloTexture sample](https://github.com/Microsoft/DirectX-Graphics-Samples). 

This sample is not endorsed or recognized by Microsoft as an official Microsoft sample. This work is my own and is unaffiliated with Microsoft.

Requirements
============
DirectComposition minimum requirements:

- Windows 8 or above
- Visual Studio 2013 or above
- Direct3D 11, Direct2D or DirectX 12

However, this sample is written for:

- Windows 10
- Visual Studio 2015
- DirectX 12


Usage
=====
* Open DirectCompositionSample.sln
* Build & Run
* Click on the circle to drag the window around
* Press ESC to quit


