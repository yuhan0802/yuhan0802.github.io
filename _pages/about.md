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

# <!-- 👋 --> About Me
{: #about-me}
Hi! I'm a Ph.D. student at Xiamen University, working under the guidance of <a href='https://mac.xmu.edu.cn/rrji/'>Rongrong Ji</a> and <a href='https://mac.xmu.edu.cn/ljcao/'>Liujuan Cao</a>. I also collaborate closely with Prof. <a href='https://informatics.xmu.edu.cn/info/1395/25099.htm'>Yiyi Zhou</a> and Prof. <a href='https://yongjiandeng.github.io/'>Yongjian Deng</a> (Nankai University).

My current research focuses on embodied intelligence and multimodal large language models. Previously, I worked on event-based vision, with a focus on video frame interpolation and multimodal perception. I welcome opportunities for discussion and collaboration—feel free to reach out via email.


# News
{: #news}

<section class="news-section" aria-labelledby="news">
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
{: #publications}

<div class="publication-sort" role="group" aria-label="Sort publications">
  <span>Sort by:</span>
  <button type="button" data-publication-sort="citations" aria-pressed="true">Most cited</button>
  <button type="button" data-publication-sort="latest" aria-pressed="false">Latest</button>
  <span class="publication-sort-status" role="status" aria-live="polite">Loading citation counts…</span>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:eQOLeE2rZwMC' data-year='2026'><div class='paper-box-image'><div><div class="badge">TCSVT 2026</div><img src='images/TCSVT2026.png' alt="Overview of Video Frame Interpolation via Asymmetric Refinement with the Event-based Reference" loading="lazy" decoding="async" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Video Frame Interpolation via Asymmetric Refinement with the Event-based Reference](https://ieeexplore.ieee.org/document/11614017)

**Yuhan Liu**, Yongjian Deng, Linghui Fu, et al. <strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:eQOLeE2rZwMC'></span></strong>

<p class="paper-links"><a href="https://ieeexplore.ieee.org/document/11614017">Paper</a> &middot; <a href="https://github.com/yuhan0802/DSER-pp">Code</a></p>
<p class="paper-summary">DSER++ synthesizes intermediate frames from an event-derived motion reference without explicit motion estimation. Bidirectional event-guided aggregation and asymmetric selective refinement recover occluded and non-rigid regions.</p>
</div>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:W7OEmFMy1HYC' data-year='2026'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/cvpr2026.png' alt="Overview of One-Shot Flow, Any-Time Frame: A Bidirectional Warping Framework for Event-Based Video Frame Interpolation" loading="lazy" decoding="async" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[One-Shot Flow, Any-Time Frame: A Bidirectional Warping Framework for Event-Based Video Frame Interpolation](https://openaccess.thecvf.com/content/CVPR2026/html/Fu_One-Shot_Flow_Any-Time_Frame_A_Bidirectional_Warping_Framework_for_Event-Based_CVPR_2026_paper.html)

**Linghui Fu\***, **Yuhan Liu\***, Hao Chen, et al. <span class="paper-highlight">(Highlight)</span> <strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:W7OEmFMy1HYC'></span></strong>

<p class="paper-links"><a href="https://openaccess.thecvf.com/content/CVPR2026/html/Fu_One-Shot_Flow_Any-Time_Frame_A_Bidirectional_Warping_Framework_for_Event-Based_CVPR_2026_paper.html">Paper</a> &middot; <a href="https://github.com/Sudadaaaa/OF-AF">Code</a></p>
<p class="paper-summary">We estimate holistic motion trajectories from events in a single pass and query optical flow at arbitrary timestamps. Bidirectional warping combines complementary keyframe information for efficient, high-quality interpolation.</p>
</div>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:Y0pCki6q_DkC' data-year='2026'><div class='paper-box-image'><div><div class="badge">ACM TOMM 2026</div><img src='images/TOMM2026.png' alt="Overview of EvSAM: Segment Anything Model with Event-based Assistance" loading="lazy" decoding="async" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EvSAM: Segment Anything Model with Event-based Assistance](https://dl.acm.org/doi/10.1145/3786794/)

Yi Ding, Bowen Yao, **Yuhan Liu**, et al. <strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:Y0pCki6q_DkC'></span></strong>

<p class="paper-links"><a href="https://dl.acm.org/doi/10.1145/3786794/">Paper</a></p>
<p class="paper-summary">EvSAM adapts SAM to RGB-event segmentation by aligning spatial and temporal features and injecting event cues. It combines event dynamics with RGB semantics for challenging scenes.</p>
</div>
</div>


<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:IjCSPb-OGe4C' data-year='2025'><div class='paper-box-image'><div><div class="badge">EAAI 2025</div><img src='images/EAAI2025.png' alt="Overview of Event-based Video Interpolation via Complementary Motion Information" loading="lazy" decoding="async" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Event-based Video Interpolation via Complementary Motion Information](https://www.sciencedirect.com/science/article/pii/S0952197625026375)

**Yuhan Liu**, Linghui Fu, Hao Chen, et al. <strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:IjCSPb-OGe4C'></span></strong>

<p class="paper-links"><a href="https://www.sciencedirect.com/science/article/pii/S0952197625026375">Paper</a></p>
<p class="paper-summary">We combine dense frame context with sparse event motion cues through Edge Guided Attention. An event-based visibility map handles occlusions during frame warping.</p>
</div>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:Tyk-4Ss8FVUC' data-year='2025'><div class='paper-box-image'><div><div class="badge">NIPS 2025</div><img src='images/nips2025.jpg' alt="Overview of EPA: Boosting Event-based Video Frame Interpolation with Perceptually Aligned Learning" loading="lazy" decoding="async" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EPA: Boosting Event-based Video Frame Interpolation with Perceptually Aligned Learning](https://github.com/yuhan0802/EPA)

**Yuhan Liu**, Linghui Fu, Zhen Yang, et al. <strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:Tyk-4Ss8FVUC'></span></strong>

<p class="paper-links"><a href="https://github.com/yuhan0802/EPA">Paper</a> &middot; <a href="https://github.com/yuhan0802/EPA">Code</a></p>
<p class="paper-summary">EPA introduces perceptually aligned learning for event-based video frame interpolation. Training in a semantic feature space improves robustness to image degradation.</p>
</div>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:qjMakFHDy7sC' data-year='2025'><div class='paper-box-image'><div><div class="badge">Neurocomputing 2025</div><img src='images/neurocomputing2025.png' alt="Overview of Neuromorphic event-based recognition boosted by motion-aware learning" loading="lazy" decoding="async" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neuromorphic event-based recognition boosted by motion-aware learning](https://www.sciencedirect.com/science/article/pii/S0925231225003509)

**Yuhan Liu**, Yongjian Deng, Bochen Xie, et al. <strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:qjMakFHDy7sC'></span></strong>

<p class="paper-links"><a href="https://www.sciencedirect.com/science/article/pii/S0925231225003509">Paper</a></p>
<p class="paper-summary">A Motion-Aware Branch learns temporal relationships from events and complements the spatial features of a 2D CNN. This motion knowledge improves event-based recognition.</p>
</div>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:u-x6o8ySG0sC' data-year='2024'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/cvpr2024.png' alt="Overview of Video Frame Interpolation via Direct Synthesis with the Event-based Reference" loading="lazy" decoding="async" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Video Frame Interpolation via Direct Synthesis with the Event-based Reference](https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_Video_Frame_Interpolation_via_Direct_Synthesis_with_the_Event-based_Reference_CVPR_2024_paper.pdf)

**Yuhan Liu**, Yongjian Deng, Hao Chen, et al. <strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:u-x6o8ySG0sC'></span></strong>

<p class="paper-links"><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_Video_Frame_Interpolation_via_Direct_Synthesis_with_the_Event-based_Reference_CVPR_2024_paper.pdf">Paper</a> &middot; <a href="https://github.com/yuhan0802/DSER">Code</a></p>
<p class="paper-summary">We synthesize intermediate frames directly from an event-derived reference. Event-guided deformable alignment improves reconstruction under occlusion and complex motion.</p>
</div>
</div>

<div class='paper-box' data-scholar-id='Tzv0bjoAAAAJ:d1gkVwhDpl0C' data-year='2024'><div class='paper-box-image'><div><div class="badge">ICRA 2024</div><img src='images/icra2024.png' alt="Overview of SAM-Event-Adapter: Adapting Segment Anything Model for Event-RGB Semantic Segmentation" loading="lazy" decoding="async" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SAM-Event-Adapter: Adapting Segment Anything Model for Event-RGB Semantic Segmentation](https://ieeexplore.ieee.org/document/10611127/)

Bowen Yao, Yongjian Deng, **Yuhan Liu**, et al. <strong><span class='show_paper_citations' data='Tzv0bjoAAAAJ:d1gkVwhDpl0C'></span></strong>

<p class="paper-links"><a href="https://ieeexplore.ieee.org/document/10611127/">Paper</a></p>
<p class="paper-summary">SAM-Event-Adapter uses lightweight adapters to combine event and RGB features while keeping the SAM backbone frozen. This enables parameter-efficient semantic segmentation in challenging conditions.</p>
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# <!-- 🎖 --> Honors and Awards
{: #honors-and-awards}
- *2026.09* Selected for Young Elite Scientists Sponsorship Program by CAST, Ph.D.
- *2025.06* Received the title of Outstanding Graduate of Beijing University of Technology.
- *2024.09* Received National Scholarship.

# <!-- 📖 --> Education
{: #education}
- *NOW*, pursuing a Ph.D. at Xiamen University (MAC Lab).
- *2022.09 - 2025.06*, Master's Degree, Beijing University of Technology (DMS Lab).
- *2018.09 - 2022.06*, Bachelor's Degree, Huaqiao University.

# <!-- 🤝 --> Collaborators
{: #collaborators}
- [Yongjian Deng](https://yongjiandeng.github.io/) - Nankai University.
- [Yurun Chen](https://yurunchen.github.io/) - Zhejiang University.

# <!-- 💻 --> Services
{: #service}
*Conference Reviewer*
- IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
- ACM International Conference on Multimedia (ACM MM)
- The Conference on Neural Information Processing Systems (NeurIPS)

*Journal Reviewer*
- IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
- IEEE Transactions on Multimedia (TMM)
- Transactions on Image Processing (TIP)
