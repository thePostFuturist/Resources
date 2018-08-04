---
title: Resources by Subject
---

Intro
=====

Unity is an engine that is built around modularity. Some of it is built in, but
there are many other plugins that can be imported via its Unity Asset Store, a
repository of paid...wait for it...Assets. Assets are not limited to plugins but
include models, particle systems, audio effects, graphic icons, and other
things. If a capability is not native to Unity, there is a good chance someone
has rolled their own solution which can be found in the [Asset
Store](https://assetstore.unity.com/). Unity is always prioritized by vendors
when it comes to emerging tech en lieu of other game engines, which means we can
use more experimental devices.

I also have my own framework for development, which is a system that contains
all of the assets in separate scenes, or a collection of entities within Unity.
This mean each member can work independently and everyone's work will be
aggregated dynamically. The framework, however, will be described in another
document.

Everyone
========

[Unity
Interface](https://unity3d.com/learn/tutorials/topics/interface-essentials), in
section Using the Unity Interface, steps 1-6.

1.  [Interface
    Overview](https://unity3d.com/learn/tutorials/topics/interface-essentials/interface-overview?playlist=17090)

2.  [The Scene
    View](https://unity3d.com/learn/tutorials/topics/interface-essentials/scene-view?playlist=17090)

3.  [The Game
    View](https://unity3d.com/learn/tutorials/topics/interface-essentials/game-view?playlist=17090)

4.  [The Hierarchy
    Window](https://unity3d.com/learn/tutorials/topics/interface-essentials/hierarchy-window?playlist=17090)

5.  [The Project
    Window](https://unity3d.com/learn/tutorials/topics/interface-essentials/project-window?playlist=17090)

6.  [The Inspector
    Window](https://unity3d.com/learn/tutorials/topics/interface-essentials/inspector-window?playlist=17090)

Then Essential Unity Concepts 1.

1.  [Game Objects and
    Components](https://unity3d.com/learn/tutorials/topics/interface-essentials/game-objects-and-components?playlist=17090)

[Git](https://unity3d.com/learn/tutorials/topics/cloud-build/creating-your-first-source-control-repository),
a version control system that we will use for collaboration.

Lighting and Materials
======================

Shaders used for materials have had major changes in Physically Based Rendering.
Most of the properties Unity's Standard Shader will look familiar to those
coming from a 3D Kit, however the way things are rendered is different. This is
mostly due to the lack of Raytracing, a process that really makes things look
life-like is too resource intensive. The process usually involves baking and
progressive baking, light estimation, reflection probes.

[Graphics,](https://unity3d.com/learn/tutorials/s/graphics) overview the
[Intro,](https://unity3d.com/learn/tutorials/topics/graphics/introduction-lighting-and-rendering?playlist=17102)
skip to [Light
Types](https://unity3d.com/learn/tutorials/topics/graphics/light-types?playlist=17102).
Go through the playlists 1-6 in Rendering and Shading in the graphics manual.

-   [Lighting
    Overview](https://unity3d.com/learn/tutorials/topics/graphics/lighting-overview?playlist=17102)

-   [Lights](https://unity3d.com/learn/tutorials/topics/graphics/lights?playlist=17102)

-   [Materials](https://unity3d.com/learn/tutorials/topics/graphics/materials?playlist=17102)

-   [The Standard Shader](The%20Standard%20Shader)

-   [Using
    Skyboxes](https://unity3d.com/learn/tutorials/topics/graphics/using-skyboxes?playlist=17102)

Go through this [manual
page](https://docs.unity3d.com/Manual/LightingOverview.html). 

##### Precomputed Realtime GI (Realtime Global Illumination)

-   [Introduction to Precomputed Realtime
    GI](https://unity3d.com/learn/tutorials/topics/graphics/introduction-precomputed-realtime-gi?playlist=17102)

-   [Realtime
    Resolution](https://unity3d.com/learn/tutorials/topics/graphics/realtime-resolution?playlist=17102)

-   [Starting the precompute
    process](https://unity3d.com/learn/tutorials/topics/graphics/starting-precompute-process?playlist=17102)

-   [Probe
    lighting](https://unity3d.com/learn/tutorials/topics/graphics/probe-lighting?playlist=17102)

-   [Fine tuning with Lightmap
    Parameters](https://unity3d.com/learn/tutorials/topics/graphics/fine-tuning-lightmap-parameters?playlist=17102)

-   [Summary - Precomputed Realtime
    GI](https://unity3d.com/learn/tutorials/topics/graphics/summary-precomputed-realtime-gi?playlist=17102)

Texturing
=========

Shaders within Unity can support all types of textures used in film: normal,
reflective, detail, etc.

From the [Graphics](https://unity3d.com/learn/tutorials/s/graphics) page,
section *Rendering and Shading*:
[Materials](https://unity3d.com/learn/tutorials/topics/graphics/materials?playlist=17102),
[The Standard
Shader](https://unity3d.com/learn/tutorials/topics/graphics/standard-shader?playlist=17102),
and
[Textures](https://unity3d.com/learn/tutorials/topics/graphics/textures?playlist=17102).

Composition and Rendering
=========================

While a vital part of film, the only thing Unity has that resembles Compositing
is the [Post
Processing](https://docs.unity3d.com/Manual/PostProcessing-Stack.html) Stack ( I
advise checking out the [development
build](https://github.com/Unity-Technologies/PostProcessing/tree/v2) ). In the
author's opinion, the analogy in compositing within game engines is *Rendering*.

As of 2018.1 Release, Unity takes on a different approach with the
[High](https://blogs.unity3d.com/2018/03/16/the-high-definition-render-pipeline-focused-on-visual-quality/)
and
[Light](https://blogs.unity3d.com/2018/02/21/the-lightweight-render-pipeline-optimizing-real-time-performance/)
Definition
[Pipelines](https://blogs.unity3d.com/2018/02/21/the-lightweight-render-pipeline-optimizing-real-time-performance/),
giving you full control of builds cross-platform.

Graphic Design
==============

Designing directly in Unity instead of Illustrator or Photoshop allows
flexibility in creating graphic components, and prevents redundant labor of
development implementation. Unity easily allows implementation of responsive
design, skinning, and is well suited for 3D or 2D content.

Learn modules 1 - 8  in [UI
Components](https://unity3d.com/learn/tutorials/s/user-interface-ui).

I'm not sure why the lessons are so granular in segmentation, but each module is
simply a part of Unity's "Canvas", or a plane that defines the UI elements.

1.  [UI
    Canvas](https://unity3d.com/learn/tutorials/topics/user-interface-ui/ui-canvas?playlist=17111)

2.  [UI
    RectTransform](https://unity3d.com/learn/tutorials/modules/beginner/ui/rect-transform?playlist=17111)

3.  [UI
    Button](https://unity3d.com/learn/tutorials/topics/user-interface-ui/ui-button?playlist=17111)

4.  [UI
    Image](https://unity3d.com/learn/tutorials/topics/user-interface-ui/ui-image?playlist=17111)

5.  [UI
    Text](https://unity3d.com/learn/tutorials/topics/user-interface-ui/ui-text?playlist=17111)

6.  [UI Events and Event
    Triggers](https://unity3d.com/learn/tutorials/topics/user-interface-ui/ui-events-and-event-triggers?playlist=17111)

7.  [UI
    Slider](https://unity3d.com/learn/tutorials/topics/user-interface-ui/ui-slider?playlist=17111)

8.  [UI
    Transitions](https://unity3d.com/learn/tutorials/topics/user-interface-ui/ui-transitions?playlist=17111)

Learn the basics of mecanim for more advanced animations: [Animate Anything with
Mecanim](https://unity3d.com/learn/tutorials/topics/animation/animate-anything-mecanim?playlist=17099)

Image Targets: [Guidelines for Designing Image
Targets](https://library.vuforia.com/articles/Solution/Optimizing-Target-Detection-and-Tracking-Stability.html)
by Vuforia.

Animation
=========

Unity has a very robust animation system which comprises of two parts: Mecanim
and Timeline. Mecanim includes a key functionality of retargeting of humanoid
subjects, meaning that a walkcycle for one subject can be used for another mesh.
It is also a way to structure animations that may be invoked by trigger.
Timeline is a sequence editor which can animate any object in the scene.

##### Character Animation

1.  [Humanoid
    Avatars](https://unity3d.com/learn/tutorials/topics/animation/humanoid-avatars?playlist=17099)

2.  [Authoring Root
    Motion](https://unity3d.com/learn/tutorials/topics/animation/authoring-root-motion?playlist=17099)

##### Controlling Animation

1.  [The Animator
    Component](https://unity3d.com/learn/tutorials/topics/animation/animator-component?playlist=17099)

2.  [The Animator
    Controller](https://unity3d.com/learn/tutorials/topics/animation/animator-controller?playlist=17099)

[Animate Anything with
Mecanim](https://unity3d.com/learn/tutorials/topics/animation/animate-anything-mecanim?playlist=17099)

##### Timeline

1.  [Using Timeline:
    Overview](https://unity3d.com/learn/tutorials/topics/animation/using-timeline-overview?playlist=17099)

2.  [Using Timeline: Getting
    Started](https://unity3d.com/learn/tutorials/topics/animation/using-timeline-getting-started?playlist=17099)

3.  [Using Timeline: Understanding
    Tracks](https://unity3d.com/learn/tutorials/topics/animation/using-timeline-understanding-tracks?playlist=17099)

4.  [Using Timeline: Working with Animation
    Clips](https://unity3d.com/learn/tutorials/topics/animation/using-timeline-working-animation-clips?playlist=17099)

XR UX
-----

-   VR Book by Jason Jerald

    -   Deep insight on the history of VR, and UX through Philosophy,
        Psychology, and Neuroscience.

    -   <http://www.thevrbook.net/>

-   Meta

    -   Meta has had an interesting combination of one of the pioneers of AR (
        Steve Mann ), as well the designer behind Iron Man's helmet HUD.

    -   Spatial Design Guidelines

        -   <http://devcenter.metavision.com/design/spatial-interface-design-principles-introduction>

        -   <https://blog.metavision.com/a-primer-on-augmented-reality-design-with-general-assembly-and-meta>

-   Microsoft Hololens

    -   Microsoft has had a head start on everybody due to it's tracking
        algorithm (SLAM) first developed with the Kinect, providing a limited,
        but capable product that dominated the market

    -   <https://docs.microsoft.com/en-us/windows/mixed-reality/design>

-   Leap Motion

    -   <http://blog.leapmotion.com/ergonomics-vr-design/>

Coding
------

##### Books

[Learning C\# Programming with Unity 3D by Alex
Okita](https://www.amazon.com/Learning-C-Programming-Unity-3D/dp/1466586524)

A robust scope of programming within Unity

[Holistic Game Development by Penny De
Byl](http://www.pennydebyl.me/holistic3d/holistic-game-development/)

A little dated, but is a good scope on not just programming but also learning
Unity.

##### Blogs and Channels

[Catlike Tutorials](https://catlikecoding.com/unity/tutorials/)

[VirtualityRipple](https://www.youtube.com/watch?v=zCjSO8-Pb00&list=PLGKDmLYR31_hXEpCThVfH9pm1K2iB3ztX)

[Brackeys](https://www.youtube.com/channel/UCYbK_tjZ2OrIZFBvU6CCMiA)

[Infallible Code](https://www.youtube.com/channel/UCTjnCCcuIbrprhOiaDJxxHA)

3D Graphics
-----------

[Guerrilla CG](https://vimeo.com/user904568)
