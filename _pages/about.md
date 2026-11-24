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

# <!-- 👋 --> About Me
Hi! I'm a Ph.D. student at Xiamen University, working under the guidance of <a href='https://mac.xmu.edu.cn/rrji/'>Rongrong Ji</a> and <a href='https://mac.xmu.edu.cn/ljcao/'>Liujuan Cao</a>. I also collaborate closely with Prof. <a href='https://informatics.xmu.edu.cn/info/1395/25099.htm'>Yiyi Zhou</a> and Prof. <a href='https://yongjiandeng.github.io/'>Yongjian Deng</a> (Nankai university). 

My research interest includes multimodal and efficient training. If you’re interested in my work or have ideas for collaboration, feel free to reach out via email.


<section class="news-section" aria-labelledby="news-heading">
<h2 id="news-heading" class="news-heading">News</h2>
<ol id="news-list" class="news-timeline">
  <li class="news-item">
    <time datetime="2026-07">JUL 2026</time>
    <p>Paper "<span class="news-paper-title">Video Frame Interpolation via Asymmetric Refinement with the Event-based Reference.</span>" accepted by TCSVT 2026!</p>
  </li>
  <li class="news-item">
    <time datetime="2026-02">FEB 2026</time>
    <p>Paper "<span class="news-paper-title">One-Shot Flow, Any-Time Frame: A Bidirectional Warping Framework for Event-Based Video Frame Interpolation.</span>" accepted by CVPR 2026!</p>
  </li>
  <li class="news-item">
    <time datetime="2025-12">DEC 2025</time>
    <p>Paper "<span class="news-paper-title">EvSAM: Segment Anything Model with Event-based Assistance.</span>" accepted by ACM TOMM 2026!</p>
  </li>
  <li class="news-item">
    <time datetime="2025-09">SEP 2025</time>
    <p>Paper "<span class="news-paper-title">Event-based Video Interpolation via Complementary Motion Information</span>" accepted by EAAI 2025!</p>
  </li>
  <li class="news-item">
    <time datetime="2025-09">SEP 2025</time>
    <p>Paper "<span class="news-paper-title">EPA: Boosting Event-based Video Frame Interpolation with Perceptually Aligned Learning</span>" accepted by NIPS 2025!</p>
  </li>
  <li class="news-item" hidden>
    <time datetime="2025-03">MAR 2025</time>
    <p>Paper "<span class="news-paper-title">Neuromorphic event-based recognition boosted by motion-aware learning</span>" accepted by Neurocomputing 2025!</p>
  </li>
  <li class="news-item" hidden>
    <time datetime="2024-06">JUN 2024</time>
    <p>Paper "<span class="news-paper-title">Video Frame Interpolation via Direct Synthesis with the Event-based Reference</span>" accepted by CVPR 2024!</p>
  </li>
  <li class="news-item" hidden>
    <time datetime="2024-04">APR 2024</time>
    <p>Paper "<span class="news-paper-title">SAM-Event-Adapter: Adapting Segment Anything Model for Event-RGB Semantic Segmentation</span>" accepted by ICRA 2024!</p>
  </li>
</ol>
<button class="news-toggle" type="button" aria-expanded="false" aria-controls="news-list">Show more</button>
</section>

# <!-- 📝 --> Publications

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:eQOLeE2rZwMC'><div class='paper-box-image'><div><div class="badge">TCSVT 2026</div><img src='images/TCSVT2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Video Frame Interpolation via Asymmetric Refinement with the Event-based Reference](https://ieeexplore.ieee.org/document/11614017)

**Yuhan Liu**, Yongjian Deng, Linghui Fu, et al.

[**Project**](https://github.com/yuhan0802/DSER-pp) 
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<p style="color:#7f8c8d;font-style:italic">We propose DSER++, a purely synthesis-based framework for event-based video frame interpolation that avoids explicit motion estimation. It constructs an event-derived motion reference, aligns keyframes through bidirectional event-guided aggregation, and introduces a Bidirectional Asymmetric Selective Refinement module to recover occluded and non-rigid regions with reliable keyframe support.</p>
</div>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:W7OEmFMy1HYC'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/cvpr2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[One-Shot Flow, Any-Time Frame: A Bidirectional Warping Framework for Event-Based Video Frame Interpolation](https://github.com/Sudadaaaa/OF-AF)

**Linghui Fu\***, **Yuhan Liu\***, Hao Chen, et al.
<strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:W7OEmFMy1HYC'></span></strong>
<p style="color:#7f8c8d;font-style:italic">We present a novel event-based video frame interpolation framework to address the efficiency-quality trade-off of flow-based warping. Leveraging the high temporal resolution of events, it obtains holistic motion trajectories via a bidirectional flow estimation block in a single pass. A flow query module retrieves bidirectional optical flow for arbitrary timestamps with no redundant computation, and a bidirectional warping mechanism fuses dual warping strengths to suppress artifacts and produce high-fidelity frames.</p>
</div>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:Y0pCki6q_DkC'><div class='paper-box-image'><div><div class="badge">ACM TOMM 2026</div><img src='images/TOMM2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EvSAM: Segment Anything Model with Event-based Assistance](https://dl.acm.org/doi/10.1145/3786794/)

Yi Ding, Bowen Yao, **Yuhan Liu**, et al.

<p style="color:#7f8c8d;font-style:italic">We propose EvSAM, an RGB-event multi-modal framework that enhances SAM for challenging visual scenarios by integrating dynamic event cues with RGB semantics. Through the proposed MS2PAB and EFInj modules, EvSAM achieves effective spatiotemporal alignment and adaptive cross-modal fusion, improving event-based semantic segmentation and showing strong scalability to depth estimation.</p>
</div>
</div>


<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:IjCSPb-OGe4C'><div class='paper-box-image'><div><div class="badge">EAAI 2025</div><img src='images/EAAI2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Event-based Video Interpolation via Complementary Motion Information](https://yuhan0802.github.io/)

**Yuhan Liu**, Linghui Fu, Hao Chen, et al.
<strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:IjCSPb-OGe4C'></span></strong>
<p style="color:#7f8c8d;font-style:italic">We propose a novel end-to-end learning framework to explicitly leverage the complementary characteristics of event signals and frames for event-based video interpolation. Our method synergistically fuses dense contextual information from frames with sparse but precise edge motion from events via a proposed Edge Guided Attention (EGA) module and introduces an event-based visibility map to adaptively mitigate occlusions during the warping process.</p>
</div>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:Tyk-4Ss8FVUC'><div class='paper-box-image'><div><div class="badge">NIPS 2025</div><img src='images/nips2025.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EPA: Boosting Event-based Video Frame Interpolation with Perceptually Aligned Learning](https://github.com/yuhan0802/EPA)

**Yuhan Liu**, Linghui Fu, Zhen Yang, et al.

[**Project**](https://github.com/yuhan0802/EPA) <strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:Tyk-4Ss8FVUC'></span></strong>
<p style="color:#7f8c8d;font-style:italic">We propose a novel framework, EPA, which transfers the learning paradigm from an unstable pixel space to a semantically aware feature space insensitive to degradation, in order to overcome the problem of reduced model generalization ability caused by image degradation in training data.</p>
</div>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:qjMakFHDy7sC'><div class='paper-box-image'><div><div class="badge">Neurocomputing 2025</div><img src='images/neurocomputing2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neuromorphic event-based recognition boosted by motion-aware learning](https://www.sciencedirect.com/science/article/pii/S0925231225003509)

**Yuhan Liu**, Yongjian Deng, Bochen Xie, et al.

 <strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:qjMakFHDy7sC'></span></strong>
<p style="color:#7f8c8d;font-style:italic">We propose a motion-aware learning framework that addresses the inability of traditional 2D CNNs to effectively encode motion for event-based recognition. Our method introduces an auxiliary Motion-Aware Branch (MAB) to learn dynamic spatio-temporal correlations, providing complementary motion-centric knowledge that is then fused with the rich spatial semantics from the primary CNN branch for a more robust and comprehensive representation.</p>
</div>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:u-x6o8ySG0sC'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/cvpr2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Video Frame Interpolation via Direct Synthesis with the Event-based Reference](https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_Video_Frame_Interpolation_via_Direct_Synthesis_with_the_Event-based_Reference_CVPR_2024_paper.pdf)

**Yuhan Liu**, Yongjian Deng, Hao Chen, et al.

 <strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:u-x6o8ySG0sC'></span></strong>
<p style="color:#7f8c8d;font-style:italic">This paper introduces a novel E-VFI framework that obviates the need for explicit motion estimation by directly synthesizing the target frame. We achieve this by first reconstructing a structural reference of the intermediate scene solely from event data, and then propose a deformable alignment module (E-PCD) to align keyframes to this reference, which significantly enhances the model's ability to handle severe occlusions where traditional motion-based methods typically fail.</p>
</div>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:d1gkVwhDpl0C'><div class='paper-box-image'><div><div class="badge">ICRA 2024</div><img src='images/icra2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SAM-Event-Adapter: Adapting Segment Anything Model for Event-RGB Semantic Segmentation](https://ieeexplore.ieee.org/document/10611127/)

Bowen Yao, Yongjian Deng, **Yuhan Liu**, et al.

 <strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:d1gkVwhDpl0C'></span></strong>
<p style="color:#7f8c8d;font-style:italic">This paper introduces SAM-Event-Adapter, a novel and parameter-efficient method to adapt the Segment Anything Model (SAM) for multi-modal Event-RGB semantic segmentation. By freezing the powerful SAM backbone and inserting lightweight adapter modules, we effectively fuse motion cues from event cameras with texture information from RGB images, significantly improving segmentation performance in adverse conditions while avoiding the prohibitive costs and generalization loss associated with full model retraining.</p>
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# <!-- 🎖 --> Honors and Awards
- *2026.09* Selected for Young Elite Scientists Sponsorship Program by CAST, Ph.D.
- *2025.06* Received the title of Outstanding Graduate of Beijing University of Technology. 
- *2024.09* Received National Scholarship. 
<!-- - *2022.10* National Prize in the Chinese College Students Computer Competition.
- *2022.05* Provincial Prize in the Chinese College Students Computer Software Design Competition. -->

# <!-- 📖 --> Educations
- *NOW*, pursuing a Ph.D. at Xiamen University (MAC Lab). 
- *2022.09 - 2025.06*, Master's Degree, Beijing University of Technology (DMS Lab). 
- *2018.09 - 2022.06*, Bachelor's Degress, Huaqiao Univsersity.

# <!-- 🤝 --> Collaborators
- [Yongjian Deng](https://yongjiandeng.github.io/) - Nankai University.
- [Yurun Chen](https://yurunchen.github.io/) - Zhejiang University.

# <!-- 💻 --> Services
*Conference Reviewer*
- IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
- ACM International Conference on Multimedia (ACM MM)
- The Conference on Neural Information Processing Systems (NeurIPS)

*Journal Reviewer*
- IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
- IEEE Transactions on Multimedia (TMM)
- Transactions on Image Processing (TIP)