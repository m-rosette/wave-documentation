---
title: WAVE - An open-source underWater Arm-Vehicle Emulator
description: An open-source underWater Arm-Vehicle Emulator
---

{{% blocks/cover title="WAVE" image_anchor="top" height="full" %}}
{{% param description %}}
{.display-6}

<!-- <a class="btn btn-lg btn-primary me-3" href="about/">Learn More</a>
<a class="btn btn-lg btn-secondary" href="docs/get-started/">Get started</a> -->
<!-- {.p-initial .my-5} -->

{{% blocks/link-down color="info" %}}
{{% /blocks/cover %}}

{{% blocks/lead color="primary" %}}
Wave is a novel physical testbed developed for underwater manipulation studies.

Read about: the <a href="docs/">Testbed Overview</a>, <a href="docs/">Hardware</a>, and <a href="docs/">Software</a>.

See the <a href="docs/">bill of materials</a> and <a href="docs/">3D models</a> to build your own.

{{% /blocks/lead %}}

{{% blocks/section type="section" color="dark" type="row" %}}

### Key functionality:

* Replicated ROV motion: surge-heave-sway-yaw within an approximately 2m x 2m x 1m square workspace
* Ground truth localization: feedback from joint encoders at each axis can be used to accurately reconstruct
the forward kinematics of the testbed and provide  accurate state estimation
* Two operating modes: rigid and passively compliant. In the passive-mode, the ROV body can pitch similar to
how an underactuated vehicle without pitch control would rotate during manipulatormotion due to dynamic coupling.
* Modularity: the testbed can be disassembled and re-assembled within two hours

{{% /blocks/section %}}
