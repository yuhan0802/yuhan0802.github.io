---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👋 About Me
Hi! I'm a Ph.D. student at Xiamen University, working under the guidance of <a href='https://mac.xmu.edu.cn/ljcao/'>Liujuan Cao</a> and <a href='https://mac.xmu.edu.cn/rrji/'>Rongrong Ji</a>. I also collaborate closely with Prof. <a href='https://informatics.xmu.edu.cn/info/1395/25099.htm'>Yiyi Zhou</a> and Prof. <a href='https://yongjiandeng.github.io/'>Yongjian Deng</a> (Beijing university of technology). 

My research interest includes multimodal and efficient training. If you’re interested in my work or have ideas for collaboration, feel free to reach out via email.


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 Paper "<strong style="color:#6DA0BC;"><em>Event-based Video Interpolation via Complementary Motion Information</em></strong>" accepted by EAAI 2025!
- *2025.09*: &nbsp;🎉🎉 Paper "<strong style="color:#6DA0BC;"><em>EPA: Boosting Event-based Video Frame Interpolation with Perceptually Aligned Learning</em></strong>" accepted by NIPS 2025!
- *2025.03*: &nbsp;🎉🎉 Paper "<strong style="color:#6DA0BC;"><em>Neuromorphic event-based recognition boosted by motion-aware learning</em></strong>" accepted by Neurocomputing 2025!
- *2024.06*: &nbsp;🎉🎉 Paper "<strong style="color:#6DA0BC;"><em>Video Frame Interpolation via Direct Synthesis with the Event-based Reference</em></strong>" accepted by CVPR 2024!
- *2024.04*: &nbsp;🎉🎉 Paper "<strong style="color:#6DA0BC;"><em>SAM-Event-Adapter: Adapting Segment Anything Model for Event-RGB Semantic Segmentation</em></strong>" accepted by ICRA 2024!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EAAI 2025</div><img src='images/EAAI2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Event-based Video Interpolation via Complementary Motion Information](https://yuhan0802.github.io/)

**Yuhan Liu**, Linghui Fu, Hao Chen, Zhen Yang, Youfu Li, Yongjian Deng

<p style="color:#7f8c8d;font-style:italic">We propose a novel end-to-end learning framework to explicitly leverage the complementary characteristics of event signals and frames for event-based video interpolation. Our method synergistically fuses dense contextual information from frames with sparse but precise edge motion from events via a proposed Edge Guided Attention (EGA) module and introduces an event-based visibility map to adaptively mitigate occlusions during the warping process.</p>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NIPS 2025</div><img src='images/nips2025.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EPA: Boosting Event-based Video Frame Interpolation with Perceptually Aligned Learning](https://github.com/yuhan0802/EPA)

**Yuhan Liu**, Linghui Fu, Zhen Yang, Hao Chen, Youfu Li, Yongjian Deng

[**Project**](https://github.com/yuhan0802/EPA) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
<p style="color:#7f8c8d;font-style:italic">We propose a novel framework, EPA, which transfers the learning paradigm from an unstable pixel space to a semantically aware feature space insensitive to degradation, in order to overcome the problem of reduced model generalization ability caused by image degradation in training data.</p>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurocomputing 2025</div><img src='images/neurocomputing2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neuromorphic event-based recognition boosted by motion-aware learning](https://www.sciencedirect.com/science/article/pii/S0925231225003509)

**Yuhan Liu**, Yongjian Deng, Bochen Xie, Hai Liu, Zhen Yang, Youfu Li

 <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
<p style="color:#7f8c8d;font-style:italic">We propose a motion-aware learning framework that addresses the inability of traditional 2D CNNs to effectively encode motion for event-based recognition. Our method introduces an auxiliary Motion-Aware Branch (MAB) to learn dynamic spatio-temporal correlations, providing complementary motion-centric knowledge that is then fused with the rich spatial semantics from the primary CNN branch for a more robust and comprehensive representation.</p>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/cvpr2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Video Frame Interpolation via Direct Synthesis with the Event-based Reference](https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_Video_Frame_Interpolation_via_Direct_Synthesis_with_the_Event-based_Reference_CVPR_2024_paper.pdf)

**Yuhan Liu**, Yongjian Deng, Hao Chen, Zhen Yang

 <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
<p style="color:#7f8c8d;font-style:italic">This paper introduces a novel E-VFI framework that obviates the need for explicit motion estimation by directly synthesizing the target frame. We achieve this by first reconstructing a structural reference of the intermediate scene solely from event data, and then propose a deformable alignment module (E-PCD) to align keyframes to this reference, which significantly enhances the model's ability to handle severe occlusions where traditional motion-based methods typically fail.</p>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2024</div><img src='images/icra2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SAM-Event-Adapter: Adapting Segment Anything Model for Event-RGB Semantic Segmentation](https://ieeexplore.ieee.org/document/10611127/)

Bowen Yao, Yongjian Deng, **Yuhan Liu**, Hao Chen, Youfu Li, Zhen Yang

 <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
<p style="color:#7f8c8d;font-style:italic">This paper introduces SAM-Event-Adapter, a novel and parameter-efficient method to adapt the Segment Anything Model (SAM) for multi-modal Event-RGB semantic segmentation. By freezing the powerful SAM backbone and inserting lightweight adapter modules, we effectively fuse motion cues from event cameras with texture information from RGB images, significantly improving segmentation performance in adverse conditions while avoiding the prohibitive costs and generalization loss associated with full model retraining.</p>
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2025.06* Received the title of Outstanding Graduate of Beijing University of Technology. 
- *2024.09* Received National Scholarship. 
- *2022.10* National Second Prize in the Chinese College Students Computer Competition.
- *2022.05* Provincial Second Prize in the Chinese College Students Computer Software Design Competition.

# 📖 Educations
- *NOW*, pursuing a Ph.D. at Xiamen University (MAC Lab). 
- *2022.09 - 2025.06*, Master's Degree, Beijing University of Technology (DMS Lab). 
- *2018.09 - 2022.06*, Bachelor's Degress, Huaqiao Univsersity.

# 🤝 Collaborators
- [Yongjian Deng](https://yongjiandeng.github.io/) - Beijing University of Technology.
- [Yurun Chen](https://yurunchen.github.io/) - Zhejiang University.

# 💻 Services
*Conference Reviewer*
- IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
*Journal Reviewer*
- IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)