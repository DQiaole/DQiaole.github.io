---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.intro-card {
    background: #ffffff;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin: 20px 0;
    padding: 20px;
    transition: transform 0.2s ease-in-out;
}

@media (max-width: 768px) {
    .intro-card {
        margin: 12px 0;
        padding: 16px;
    }
    
    .intro-text {
        font-size: 1.1em;
        line-height: 1.6;
        margin: 1em 0;
    }
}

.intro-text {
    color: var(--global-text-color);
    font-size: 1.1em;
    line-height: 1.8;
    margin: 1.5em 0;
    font-weight: 400;
    text-align: left;
    hyphens: auto;
    -webkit-hyphens: auto;
    -ms-hyphens: auto;
}

.intro-text a {
    color: var(--global-theme-color);
    text-decoration: underline;
    font-weight: 500;
    transition: color 0.2s ease;
}

.intro-text a:hover {
    color: var(--global-hover-color);
    text-decoration: underline;
}
</style>

<p class="intro-text">
I am currently a fourth-year Ph.D. student under the supervision of Prof. <a href="https://yanweifu.github.io/">Yanwei Fu</a>. 
My research interests focus on the perception and anticipation of motion, especially optical flow estimation and future prediction. Besides, I am also interested in image generation, e.g., image inpainting/editing. Currently, I am also working on multimodal large language models.
</p>

<style>
.education-card {
    display: flex;
    align-items: flex-start;
    background: #ffffff;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin: 8px 0;
    padding: 12px;
    transition: transform 0.2s ease-in-out;
}

@media (max-width: 768px) {
    .education-card {
        padding: 10px;
        margin: 6px 0;
    }
    
    .education-icon {
        flex: 0 0 24px;
        margin-right: 8px;
    }
    
    .education-icon img {
        width: 24px;
        height: 24px;
    }
    
    .education-school {
        font-size: 0.95em;
    }
    
    .education-degree {
        font-size: 0.9em;
    }
    
    .education-date {
        font-size: 0.8em;
    }
}

.education-icon {
    flex: 0 0 32px;
    margin-right: 12px;
    text-align: center;
    padding-top: 8px;
}

.education-icon img {
    width: 32px;
    height: 32px;
    object-fit: contain;
}

.education-content {
    flex: 1;
}

.education-school {
    color: #34495e;
    font-weight: 500;
    margin-bottom: 8px;
}

.education-degree {
    color: #2c3e50;
    margin-bottom: 4px;
    font-size: 0.95em;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.education-date {
    color: #7f8c8d;
    font-size: 0.85em;
    margin-left: 12px;
}

.education-degree:last-child {
    margin-bottom: 0;
}

.section-title {
    font-size: 1.5em;
    font-weight: 600;
    color: var(--global-text-color);
    margin: 1.2em 0 0.3em 0;
    padding-bottom: 0em;
    border-bottom: 1px solid var(--global-theme-color);
    display: flex;
    align-items: center;
}

.sub-section-title {
    font-size: 1em;
    font-weight: 600;
    color: var(--global-text-color);
    margin: 1.2em 0 0.3em 0;
    padding-bottom: 0em;
    border-bottom: 1px solid var(--global-theme-color);
    display: flex;
    align-items: center;
}

.section-title::before {
    content: '';
    display: inline-block;
    width: 3px;
    height: 1em;
    background-color: var(--global-theme-color);
    margin-right: 0.4em;
    border-radius: 1.5px;
}
</style>

<div class="section-title">Education</div>

<div class="experience-card">
    <div class="experience-item">
        <div class="experience-company">
            <img src="../images/fudan-university-logo-1024px.png" alt="Fudan University" class="company-logo" loading="lazy"/>
            <div class="experience-content">
                <div>
                    <span class="company-name">Ph.D in Statistics (Machine Learning track)</span>
                    <span class="team-name">Fudan University</span>
                </div>
            </div>
        </div>
        <span class="experience-date">2022.9-2026.6</span>
    </div>
    <div class="experience-item">
        <div class="experience-company">
            <img src="../images/fudan-university-logo-1024px.png" alt="Fudan University" class="company-logo" loading="lazy"/>
            <div class="experience-content">
                <div>
                    <span class="company-name">B.Sc. in Data Science</span>
                    <span class="team-name">Fudan University</span>
                </div>
            </div>
        </div>
        <span class="experience-date">2018.9-2022.6</span>
    </div>
</div>

<style>
.experience-card {
    background: #ffffff;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin: 8px 0;
    padding: 12px;
    transition: transform 0.2s ease-in-out;
}

@media (max-width: 768px) {
    .experience-card {
        padding: 10px;
        margin: 6px 0;
    }
    
    .experience-item {
        font-size: 0.9em;
        gap: 4px;
    }
    
    .company-logo {
        width: 16px;
        height: 16px;
    }
    
    .company-name {
        min-width: 100px;
        font-size: 0.95em;
    }
    
    .team-name {
        font-size: 0.9em;
    }
    
    .experience-date {
        font-size: 0.8em;
    }
}

.experience-item {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 8px;
    color: #2c3e50;
    font-size: 0.95em;
    flex-wrap: wrap;
    gap: 8px;
}

.experience-item:last-child {
    margin-bottom: 0;
}

.experience-company {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 8px;
    flex: 1;
    min-width: 200px;
}

.company-logo {
    width: 20px;
    height: 20px;
    margin-right: 8px;
    object-fit: contain;
    flex-shrink: 0;
}

.experience-content {
    display: flex;
    flex-direction: column;
    flex: 1;
    min-width: 150px;
}

.company-name {
    font-weight: 400;
    margin-right: 4px;
    display: inline-block;
    min-width: 120px;
    line-height: 1.4;
    padding-top: 2px;
}

.team-name {
    color: #7f8c8d;
    display: inline-block;
    line-height: 1.4;
}

.experience-date {
    color: #7f8c8d;
    font-size: 0.85em;
    margin-left: 12px;
    white-space: nowrap;
    flex-shrink: 0;
}

.awards-card {
    background: #ffffff;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin: 8px 0;
    padding: 12px;
    transition: transform 0.2s ease-in-out;
}

@media (max-width: 768px) {
    .awards-card {
        padding: 10px;
        margin: 6px 0;
    }
    
    .award-item {
        font-size: 0.9em;
        margin-bottom: 6px;
    }
    
    .award-icon {
        font-size: 1.1em;
    }
    
    .award-date {
        font-size: 0.8em;
    }
}

.award-item {
    display: flex;
    align-items: center;
    margin-bottom: 8px;
    color: #2c3e50;
    font-size: 0.95em;
}

.award-item:last-child {
    margin-bottom: 0;
}

.award-icon {
    margin-right: 8px;
    color: #3498db;
    font-size: 1.2em;
    line-height: 1;
}

.award-date {
    color: #7f8c8d;
    font-size: 0.85em;
    margin-left: auto;
    padding-left: 12px;
}
</style>


<div class="section-title">Services</div>

<div class="awards-card">
    <div class="award-item">
        <span class="award-icon">•</span>
        <span>Reviewer of CVPR, ICCV, ECCV, AAAI, ACCV, IJCV, IEEE TPAMI, IEEE TCSVT, IEEE TIP, IEEE TMM</span>
    </div>
</div>

<div class="section-title">Publications</div>

<style>
.category-links {
    margin: 1em 0;
}

.category-item {
    margin: 0.5em 0;
    line-height: 1.6;
}

.category-item a {
    color: #2c3e50;
    text-decoration: none;
    transition: color 0.2s ease;
}

.category-item a:hover {
    color: #3498db;
}

.category-a, .category-b, .category-c {
    font-weight: 600;
    margin-right: 0.5em;
}
</style>

<style>
.venue-ribbon {
    position: absolute;
    top: 0;
    left: 0;
    background: #2c3e50;
    color: white;
    padding: 4px 12px;
    font-size: 0.85em;
    font-weight: 500;
    border-radius: 8px;
    z-index: 1;
}

.venue-ribbon::after {
    display: none;
}

.publication-card {
    position: relative;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    background: #ffffff;
    border-radius: 4px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.08);
    margin: 24px 0;
    padding: 24px;
    transition: all 0.3s ease;
    border: 1px solid rgba(0, 0, 0, 0.05);
    opacity: 1;
    transform: translateY(0);
}

.publication-image {
    flex: 0 0 280px;
    text-align: center;
    margin-right: 24px;
    margin-bottom: 0;
    display: flex;
    align-items: center;
    justify-content: center;
}

.publication-image img {
    width: 100%;
    max-width: 280px;
    height: auto;
    object-fit: contain;
    border-radius: 8px;
}

.publication-content {
    flex: 1;
    min-width: 300px;
    margin-left: 0;
    display: flex;
    flex-direction: column;
    gap: 12px;
}

.publication-title {
    color: #2c3e50;
    font-size: 1.1em;
    font-weight: 600;
    line-height: 1.4;
    margin: 0;
}

.publication-authors {
    color: #34495e;
    font-size: 1em;
    line-height: 1.6;
    margin: 0;
}

.publication-bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 4px;
    flex-wrap: wrap;
    gap: 8px;
}

.publication-links {
    display: flex;
    gap: 16px;
    flex-wrap: wrap;
}

.publication-number {
    font-size: 0.9em;
    font-weight: 600;
    color: #666;
    display: flex;
    align-items: center;
    margin-left: 16px;
    white-space: nowrap;
}

.publication-tags {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
    margin-top: 12px;
}

.publication-tag {
    display: inline-block;
    padding: 4px 8px;
    background: rgba(52, 152, 219, 0.08);
    color: #3498db;
    border-radius: 4px;
    font-size: 0.85em;
    font-weight: 500;
    transition: all 0.2s ease;
}

.publication-tag:hover {
    background: rgba(52, 152, 219, 0.15);
}

.tag-filter-container {
    display: flex;
    gap: 12px;
    flex-wrap: wrap;
    margin: 20px 0;
    padding: 16px;
    background: #f8f9fa;
    border-radius: 8px;
}

.tag-filter {
    display: inline-block;
    padding: 6px 12px;
    background: #ffffff;
    color: #3498db;
    border: 1px solid #3498db;
    border-radius: 6px;
    font-size: 0.9em;
    font-weight: 500;
    cursor: pointer;
    transition: all 0.2s ease;
}

.tag-filter:hover {
    background: rgba(52, 152, 219, 0.1);
}

.tag-filter.active {
    background: #3498db;
    color: #ffffff;
}

.publication-card.hidden {
    display: none;
    opacity: 0;
    transform: translateY(20px);
}

.category-tag {
    display: inline-block;
    padding: 2px 6px;
    border-radius: 4px;
    font-size: 0.8em;
    font-weight: 500;
    margin-left: 8px;
}

.category-a {
    background: rgba(52, 152, 219, 0.1);
    color: #3498db;
}

.category-b {
    background: rgba(46, 204, 113, 0.1);
    color: #2ecc71;
}

.category-c {
    background: rgba(230, 126, 34, 0.1);
    color: #e67e22;
}

@media (max-width: 768px) {
    .publication-card {
        padding: 12px;
        margin: 12px 0;
    }
    
    .publication-image {
        flex: 0 0 100%;
        margin-right: 0;
        margin-bottom: 12px;
    }
    
    .publication-image img {
        max-width: 100%;
    }
    
    .publication-content {
        gap: 8px;
    }
    
    .publication-title {
        font-size: 1.1em;
        line-height: 1.3;
    }
    
    .publication-authors {
        font-size: 0.9em;
        line-height: 1.4;
    }
    
    .publication-bottom {
        flex-direction: row;
        align-items: center;
        gap: 8px;
    }
    
    .publication-links {
        gap: 8px;
    }
    
    .publication-number {
        margin-left: 0;
        font-size: 0.85em;
    }
}

@media (max-width: 480px) {
    .publication-bottom {
        flex-direction: row;
        align-items: center;
        gap: 4px;
    }
    
    .publication-links a {
        padding: 4px 8px;
        font-size: 0.85em;
    }
    
    .publication-number {
        font-size: 0.8em;
    }
}

/* 添加触摸设备优化 */
@media (hover: none) {
    .intro-card:hover,
    .education-card:hover,
    .experience-card:hover,
    .awards-card:hover,
    .publication-card:hover {
        transform: none;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    
    .publication-links a:active {
        background: rgba(52, 152, 219, 0.2);
    }
    
    .publication-tag:active {
        background: rgba(52, 152, 219, 0.15);
    }
}

/* 优化字体大小和间距 */
@media (max-width: 480px) {
    .section-title {
        font-size: 1.3em;
        margin: 1em 0 0.2em 0;
    }
    
    .intro-text {
        font-size: 1em;
    }
    
    .education-school {
        font-size: 0.9em;
    }
    
    .education-degree {
        font-size: 0.85em;
    }
    
    .company-name {
        font-size: 0.9em;
    }
    
    .team-name {
        font-size: 0.85em;
    }
    
    .award-item {
        font-size: 0.85em;
    }
    
    .publication-title {
        font-size: 1em;
    }
    
    .publication-authors {
        font-size: 0.85em;
    }
}
</style>

<p class="publication-authors">* indicates equal contributions.</p>


<div class="sub-section-title">Multimodal Large Lanuage Models:</div>

<div class="publication-card">
    <div class="publication-image">
        <img src="../images/publications/Reinforcement_zhang_2025.png" alt="Arxiv 2025" loading="lazy"/>
    </div>
    <div class="publication-content">
        <h3 class="publication-title">Reinforcement Fine-Tuning Enables MLLMs Learning Novel Tasks Stably</h3>
        <p class="publication-authors">Zhihao Zhang*, <b>Qiaole Dong*</b>, Qi Zhang, ..., Xuanjing Huang</p>
        <div class="publication-bottom">
            <div class="publication-links">
                <a href="https://arxiv.org/abs/2506.23508">Paper</a>
            </div>
            <div class="publication-number">
                <span class="num1">Arxiv 2025</span>
            </div>
        </div>
    </div>
</div>

<div class="publication-card">
    <div class="publication-image">
        <img src="../images/publications/reasoning_memorization.png" alt="Arxiv 2025" loading="lazy"/>
    </div>
    <div class="publication-content">
        <h3 class="publication-title">Reasoning or Memorization? Unreliable Results of Reinforcement Learning Due to Data Contamination</h3>
        <p class="publication-authors">Mingqi Wu*, Zhihao Zhang*, <b>Qiaole Dong*</b>, Qi Zhang, et al.</p>
        <div class="publication-bottom">
            <div class="publication-links">
                <a href="https://arxiv.org/abs/2507.10532">Paper</a>
            </div>
            <div class="publication-number">
                <span class="num1">Arxiv 2025</span>
            </div>
        </div>
    </div>
</div>


<div class="sub-section-title">Visual Perception:</div>

<div class="publication-card">
    <div class="publication-image">
        <img src="../images/publications/SPOT_2025.png" alt="ICCV 2025" loading="lazy"/>
    </div>
    <div class="publication-content">
        <h3 class="publication-title">Online Dense Point Tracking with Streaming Memory</h3>
        <p class="publication-authors"><b>Qiaole Dong</b>, Yanwei Fu</p>
        <div class="publication-bottom">
            <div class="publication-links">
                <a href="https://arxiv.org/abs/2503.06471">Paper</a><a href="https://github.com/DQiaole/SPOT">Code</a><a href="https://dqiaole.github.io/SPOT/">Project</a>
            </div>
            <div class="publication-number">
                <span class="num1">ICCV 2025</span>
            </div>
        </div>
    </div>
</div>

<div class="publication-card">
    <div class="publication-image">
        <img src="../images/publications/memflow_2024.png" alt="CVPR 2024" loading="lazy"/>
    </div>
    <div class="publication-content">
        <h3 class="publication-title">MemFlow: Optical Flow Estimation and Prediction with Memory</h3>
        <p class="publication-authors"><b>Qiaole Dong</b>, Yanwei Fu</p>
        <div class="publication-bottom">
            <div class="publication-links">
                <a href="https://arxiv.org/abs/2404.04808">Paper</a><a href="https://github.com/DQiaole/MemFlow">Code</a><a href="https://dqiaole.github.io/MemFlow/">Project</a>
            </div>
            <div class="publication-number">
                <span class="num1">CVPR 2024</span>
            </div>
        </div>
    </div>
</div>

<div class="publication-card">
    <div class="publication-image">
        <img src="../images/publications/matchflow.png" alt="CVPR 2023" loading="lazy"/>
    </div>
    <div class="publication-content">
        <h3 class="publication-title">Rethinking Optical Flow from Geometric Matching Consistent Perspective</h3>
        <p class="publication-authors"><b>Qiaole Dong*</b>, Chenjie Cao*, Yanwei Fu</p>
        <div class="publication-bottom">
            <div class="publication-links">
                <a href="https://arxiv.org/abs/2303.08384">Paper</a>
                <a href="https://github.com/DQiaole/MatchFlow">Code</a><a href="https://dqiaole.github.io/MatchFlow/">Project</a>
            </div>
            <div class="publication-number">
                <span class="num1">CVPR 2023</span>
            </div>
        </div>
    </div>
</div>

<div class="publication-card">
    <div class="publication-image">
        <img src="../images/publications/flowdiffusion.png" alt="Arxiv" loading="lazy"/>
    </div>
    <div class="publication-content">
        <h3 class="publication-title">Open-DDVM: A Reproduction and Extension of Diffusion Model for Optical Flow Estimation</h3>
        <p class="publication-authors"><b>Qiaole Dong</b>, Bo Zhao, Yanwei Fu</p>
        <div class="publication-bottom">
            <div class="publication-links">
                <a href="https://arxiv.org/abs/2312.01746">Paper</a>
                <a href="https://github.com/DQiaole/FlowDiffusion_pytorch">Code</a>
            </div>
            <div class="publication-number">
                <span class="num1">Arxiv 2023</span>
            </div>
        </div>
    </div>
</div>


<div class="sub-section-title">Visual Generation:</div>

<div class="publication-card">
    <div class="publication-image">
        <img src="../images/publications/zits++.jpg" alt="TPAMI 2023" loading="lazy"/>
    </div>
    <div class="publication-content">
        <h3 class="publication-title">ZITS++: Image Inpainting by Improving the Incremental Transformer on Structural Priors</h3>
        <p class="publication-authors">Chenjie Cao*, <b>Qiaole Dong*</b>, Yanwei Fu</p>
        <div class="publication-bottom">
            <div class="publication-links">
                <a href="https://arxiv.org/abs/2210.05950">Paper</a>
                <a href="https://github.com/ewrfcas/ZITS-PlusPlus">Code</a><a href="https://ewrfcas.github.io/ZITS-PlusPlus/">Project</a>
            </div>
            <div class="publication-number">
                <span class="num1">IEEE TPAMI 2023</span>
            </div>
        </div>
    </div>
</div>

<div class="publication-card">
    <div class="publication-image">
        <img src="../images/publications/ECCV2022_FAR.png" alt="ECCV 2022" loading="lazy"/>
    </div>
    <div class="publication-content">
        <h3 class="publication-title">Learning Prior Feature and Attention Enhanced Image Inpainting</h3>
        <p class="publication-authors">Chenjie Cao*, <b>Qiaole Dong*</b>, Yanwei Fu</p>
        <div class="publication-bottom">
            <div class="publication-links">
                <a href="https://arxiv.org/abs/2208.01837.pdf">Paper</a>
                <a href="https://github.com/ewrfcas/MAE-FAR">Code</a><a href="https://ewrfcas.github.io/MAE-FAR/">Project</a>
            </div>
            <div class="publication-number">
                <span class="num1">ECCV 2022</span>
            </div>
        </div>
    </div>
</div>

<div class="publication-card">
    <div class="publication-image">
        <img src="../images/publications/CVPR2022_ZITS.png" alt="CVPR 2022" loading="lazy"/>
    </div>
    <div class="publication-content">
        <h3 class="publication-title">Incremental Transformer Structure Enhanced Image Inpainting with Masking Positional Encoding</h3>
        <p class="publication-authors"><b>Qiaole Dong*</b>, Chenjie Cao*, Yanwei Fu</p>
        <div class="publication-bottom">
            <div class="publication-links">
                <a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Dong_Incremental_Transformer_Structure_Enhanced_Image_Inpainting_With_Masking_Positional_Encoding_CVPR_2022_paper.pdf">Paper</a>
                <a href="https://github.com/DQiaole/ZITS_inpainting">Code</a><a href="https://dqiaole.github.io/ZITS_inpainting/">Project</a>
            </div>
            <div class="publication-number">
                <span class="num1">CVPR 2022</span>
            </div>
        </div>
    </div>
</div>

<div class="publication-card">
    <div class="publication-image">
        <img src="../images/publications/ARCI_teaser.jpg" alt="CVPR 2024" loading="lazy"/>
    </div>
    <div class="publication-content">
        <h3 class="publication-title">LeftRefill: Filling Right Canvas based on Left Reference through Generalized Text-to-Image Diffusion Model</h3>
        <p class="publication-authors">Chenjie Cao, Yunuo Cai, <b>Qiaole Dong</b>, Yikai Wang, Yanwei Fu</p>
        <div class="publication-bottom">
            <div class="publication-links">
                <a href="https://arxiv.org/abs/2305.11577">Paper</a>
                <a href="https://github.com/ewrfcas/LeftRefill">Code</a><a href="https://ewrfcas.github.io/LeftRefill/">Project</a>
            </div>
            <div class="publication-number">
                <span class="num1">CVPR 2024</span>
            </div>
        </div>
    </div>
</div>

<div class="publication-card">
    <div class="publication-image">
        <img src="../images/publications/seele.jpg" alt="TMLR 2024" loading="lazy"/>
    </div>
    <div class="publication-content">
        <h3 class="publication-title">Repositioning the Subject
within Image</h3>
        <p class="publication-authors">Yikai Wang, Chenjie Cao, Ke Fan, <b>Qiaole Dong</b>, Yifan Li, Xiangyang Xue, Yanwei Fu</p>
        <div class="publication-bottom">
            <div class="publication-links">
                <a href="https://openreview.net/pdf?id=orHH4fCtR8">Paper</a><a href="https://yikai-wang.github.io/seele/">Project</a>
            </div>
            <div class="publication-number">
                <span class="num1">TMLR 2024</span>
            </div>
        </div>
    </div>
</div>


<div class="sub-section-title">Others:</div>

<div class="publication-card">
    <div class="publication-image">
        <img src="../images/publications/cvpr23_CAWIM.png" alt="CVPR 2023" loading="lazy"/>
    </div>
    <div class="publication-content">
        <h3 class="publication-title">Causally-Aware Intraoperative Imputation for Overall Survival Time Prediction</h3>
        <p class="publication-authors">Xiang Li*, Xuelin Qian*, Litian Liang*, Lingjie Kong, <b>Qiaole Dong</b>, ..., Yanwei Fu</p>
        <div class="publication-bottom">
            <div class="publication-links">
                <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Causally-Aware_Intraoperative_Imputation_for_Overall_Survival_Time_Prediction_CVPR_2023_paper.pdf">Paper</a><a href="https://github.com/ChrisXLi/CaDAG">Code</a>
            </div>
            <div class="publication-number">
                <span class="num1">CVPR 2023</span>
            </div>
        </div>
    </div>
</div>