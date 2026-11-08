# Chengdong Zhu · 朱铖栋

**Robotics · Visual localization · AI engineering**  
PhD researcher in Electronic Engineering at the **University of York**, UK.

I work on robot sensing and control software, visual SLAM evaluation, and AI applications for engineering workflows. My projects combine platform integration, stereo calibration, experimental datasets and software verification.

[Website](https://zhuchengdong.com) · [Email](mailto:chengdong.zhu@york.ac.uk) · [ORCID](https://orcid.org/0000-0001-5877-2650)

**Industry interests:** Robotics R&D, autonomous-driving perception and localization, robot manipulation, and AI engineering. I am seeking short-term internships or R&D work within **April–August 2027**, and industry R&D roles after my PhD. Flexible on location.

## Selected projects

### York-Tank — stereo perception and visual SLAM evaluation

- Integrated the acquisition platform, calibrated stereo cameras and organized controlled underwater experiments.
- Released **16 sequences with 18,948 synchronized stereo pairs**, organized by visual degradation and difficulty.
- Evaluated **ORB-SLAM3 and SVO Pro**, including controlled comparisons of contrast enhancement and dynamic-region feature rejection within ORB-SLAM3.

**Published:** Dataset and first-author paper in *Sensors*, 26(20), 6567 (2026).

[Dataset & documentation](https://github.com/zhu-chengdong/York-Tank) · [Paper](https://doi.org/10.3390/s26206567) · [Download data](https://doi.org/10.5281/zenodo.23347574) · [Calibration & processing code](https://github.com/zhu-chengdong/rov-v1-hardwarex/tree/main/software/offline) · [Experiment setup](https://zhuchengdong.com/york-tank.html)

Earlier C++/ROS integration: my [ORB-SLAM2 adaptation](https://github.com/zhu-chengdong/slam2_18/blob/master/Examples/ROS/ORB_SLAM2/src/ros_stereo.cc) adds idle-timeout shutdown before the upstream trajectory-export calls.

### SolidWorks AI — AI-assisted CAD software

- Built a **Python** workbench for schema-validated model planning, **MCP** tool calls and serialized native **COM** execution in **SOLIDWORKS 2024**.
- Integrated part, assembly and drawing workflows with geometry/mate checks, save/reopen verification, preview review and versioned CAD/STEP/BOM delivery.

**Released:** Windows x64 **v0.18.1**, with public source, tests and a release acceptance report. Native validation currently covers the SOLIDWORKS 2024 development machine.

The application builds on MIT-licensed automation components, with upstream provenance retained.

[Source](https://github.com/zhu-chengdong/solidworks-ai) · [Tests](https://github.com/zhu-chengdong/solidworks-ai/tree/main/tests) · [Windows release & acceptance report](https://github.com/zhu-chengdong/solidworks-ai/releases/tag/v0.18.1) · [Workflow & output examples](https://zhuchengdong.com/solidworks-ai.html)

### ATArm — robot control and software integration

- Extending an existing agricultural-arm control framework with local Jacobian-based **3D position control**, **ROS 2** pose/goal interfaces and a four-channel A1 actuator adapter.
- Added pose freshness/frame checks, bounded commands, stop/fault handling and offline verification.

**Validation:** Simulation and fake-serial tests; published records cover **18 ROS/A1 pseudo-terminal scenarios**. Physical commissioning is pending. The application target is vision-guided, automatic multi-view imaging of real plants.

[Public repository](https://github.com/zhu-chengdong/atarm-control) · [Validation records](https://github.com/zhu-chengdong/atarm-control/blob/main/docs/VALIDATION.md) · [Code provenance & permissions](https://github.com/zhu-chengdong/atarm-control/blob/main/docs/CODE_PROVENANCE.md) · [Control overview](https://zhuchengdong.com/atarm-control.html)

### ROV V1 — robot platform and engineering resources

Designed and integrated a shallow-water stereo research platform. Public **v0.1.1** materials include editable CAD, wiring/BOM documentation, onboard camera software, offline processing tools and recorded thermal data.

[Engineering resources](https://github.com/zhu-chengdong/rov-v1-hardwarex) · [Platform overview & photographs](https://zhuchengdong.com/rov-v1.html)

## Education

- **University of York** — PhD research in Electronic Engineering, October 2023–present.
- **China University of Mining and Technology** — Master's degree in Mechanical Engineering, September 2020–July 2023.
- **China University of Mining and Technology** — Bachelor's degree in Mechanical Engineering, September 2016–July 2020.
