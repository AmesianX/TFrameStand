#TFrameStand component (FMX)
Easily use TFrame(s) in your FireMonkey (FMX) applications to gain visual consistency though the whole user experience and easily add modern looking elements like effects and transitions.

_All code and demos tested on Delphi XE8 and Delphi 10 Seattle._

##Installation
1. Compile “packages\FrameStandPackage.dproj”
2. Install “FrameStandPackage.bpl” package
3. Add “source\” library path for Delphi (repeat for each platform you need)

##Main functionalities
* Show any TFrame (manually or while doing a background task)
* Add a common visual layer between the TFrame and its parent (either a TForm or any TControl)
* Add animations and effects to provide a modern looking UI
* Share CommonActions through different UI combinations

##Get started
* Have a look at [my blog posts about TFrameStand](www.andreamagni.eu/wp)
* [My CodeRage X session (50 min video covering all the basic functionalities)](https://www.youtube.com/watch?v=Z6_ZvnCmFCw)

##Demo projects
* **wait**: a wait splashscreen with running animation and opacity. Can be show on the top of a whole form or a single FMX control. Runs a task on a background thread and keeps UI responsive.
* **lightbox**: achieves the popular lightbox effect to show different kind of content (pictures, text, data) using a consistent UI. Also provides an example of CommonActions use (the Close button) and provides fade-in animation of content
* **material_button**: a simple example to overlay a button on the form or any other control, with sliding animations.
* **ViewAndDialogs**: some Material Design-like transition to show a view (employee's details) and a dialog (rate a picture).
* **PictureWall**: show pictures in a TFlowLayout with a fading in transition
* **ButtonSet**: mimics Android's Camera toolbuttons laying over your content.
* **EditHelper**: adds easy to customize buttons or controls to any TEdit.
