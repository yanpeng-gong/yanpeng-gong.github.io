---
layout: archive
permalink: /publications/
author_profile: false
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-K251SYLJ6Y"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-K251SYLJ6Y');
</script>

<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@400;600&display=swap" rel="stylesheet">

/_ CSS 部分 _/

<style>
body {
  font-family: 'IBM Plex Sans', sans-serif;
  font-size: 16px;
}
.publications-list {
    counter-reset: pub-counter 59; /* 设置初始值为总论文数+1 */
    list-style: none;
    padding-left: 0;
}
.publication-item {
    display: flex;
    margin-bottom: 30px;
    gap: 20px;
    align-items: flex-start;
    counter-increment: pub-counter -1; /* 每次递减1 */
}
.publication-item::before {
    content: counter(pub-counter) ".";
    font-weight: bold;
    margin-right: 8px;
    flex-shrink: 0;
}
.publication-content {
    flex: 1;
    min-width: 0;
}
.publication-image {
    flex-shrink: 0;
    width: 280px;
}
.publication-image img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}
/* 响应式设计：小屏幕时图片移到下方 */
@media (max-width: 768px) {
  .publication-item {
    flex-direction: column;
  }
  .publication-image {
    width: 100%;
  }
}
</style>

<!--
<h3>Cover Gallary</h3>
<table border=0>
  <tr><td width=145 ><img src="/images/publications/Cover_2016afm.png" width="145"></td><td width=145><img src="/images/publications/Cover_2016softmatter.png" width="145"></td><td width=145><img src="/images/publications/Cover_2018_PRL.jpg" width="145"></td><td width=145><img src="/images/publications/Cover_2019AM.jpg" width="145"></td><td width=145><img src="/images/publications/Cover_2019prl.png" width="145"></td><td width=145 ><img src="/images/publications/Cover_2022AMI.JPG" width="145"></td></tr>
</table>
<table border=0>
  <tr><td width=145><img src="/images/publications/Cover_2023NL.jpg" width="145"></td><td width=145><img src="/images/publications/Cover_2024_AIS.png" width="145"></td><td width=145><img src="/images/publications/Cover_2024NL.png" width="145"></td><td width=145><img src="/images/publications/Cover_2025_NL.png" width="145"></td></tr>
</table>
-->
<hr>
<p>Below is a chronological list of my publications in refereed journals. For recent highlights, please visit my profile at <a href="https://yanzhao.bjut.edu.cn/info/1516/17371.htm" style="color:black;"><i class="fa fa-university" aria-hidden="true"></i></a>. For citation statistics, see my <a href="https://scholar.google.com/citations?user=wmkLERIAAAAJ&hl=zh-CN" style="color:black;"><i class="fas fa-fw fa-graduation-cap" aria-hidden="true"></i></a> or <a href="https://www.researchgate.net/profile/Yanpeng-Gong" style="color:black;"><i class="fab fa-fw fa-researchgate"></i></a> profile.</p>
<hr>

<ol reversed >

<br>
<hr>
<h2 style="color: #008B8B; font-weight: bold; font-size: 28px; margin-bottom: 20px;">Forthcoming</h2>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>*, Y. He, Y. Mei*, X. Zhuang*, F. Qin, T. Rabczuk.
        <!-- Title of the paper -->
        <a href="https://arxiv.org/abs/2508.16999" style="text-decoration:none; color:#DE3163;">
            Physics-Informed Kolmogorov-Arnold Networks for multi-material elasticity problems in electronic packaging.
        </a>
        <!-- Journal information -->
        <b>arXiv</b> (2025)
        <a href="http://yanpeng-gong.github.io/files/papers/2025_PIKAN.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
        <!-- link of arXive -->
        <a href="https://arxiv.org/abs/2508.16999" style="text-decoration:none; color:#4A90E2;">
            [arXiv]
        </a>
    </div>
</li>

<!--
论文模版，包括有图片和无图片介绍的情况

Arxive预印版：有图片
<li class="publication-item">
    左侧：论文信息
    <div class="publication-content">
        Author names
        <u>Y. Gong</u>, Y. He, Y. Mei*, X. Zhuang*, F. Qin, T. Rabczuk.
        Title of the paper
        <a href="https://arxiv.org/abs/2508.16999" style="text-decoration:none; color:#DE3163;">
            Physics-Informed Kolmogorov-Arnold Networks for multi-material elasticity problems in electronic packaging.
        </a>
        Journal information
        <b>arXiv</b> (2025)
        <a href="http://yanpeng-gong.github.io/files/papers/2025_PIKAN.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
        link of open source code
        <a href="https://github.com/your-repo" style="text-decoration:none; color:#24292e;">
            <i class="fa fa-github" style="font-size:16px;"></i> [Code]
        </a>
    </div>
    右侧：图片展示
    <div class="publication-image">
        <img src="/images/papers/2025_PIKAN.jpg" alt="PIKAN scheme">
    </div>
</li>
-->

<!-- 发表论文：有图片
<li class="publication-item">
    左侧：论文信息
    <div class="publication-content">
        Author names
        <u>Y. Gong</u>*, S. Li, F. Qin, B. Xu*.
        Title of the paper
        <a href="https://link.springer.com/article/10.1007/s00366-025-02219-8" style="text-decoration:none; color:#DE3163;">
            Virtual element method for thermomechanical analysis of electronic packaging structures with multi-scale features.
        </a>
        Journal information
        <b>Engineering with Computers</b> 41 (2025) 4799–4824
        <a href="http://yanpeng-gong.github.io/files/papers/2025_EC.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
        link of arXive
        <a href="https://arxiv.org/abs/2508.11410" style="text-decoration:none; color:#4A90E2;">
            [arXiv]
        </a>
        link of open source code
        <a href="https://github.com/yanpeng-gong/VEM-electronic-packaging" style="text-decoration:none; color:#24292e;">
            <i class="fa fa-github" style="font-size:16px;"></i> [Code]
        </a>
    </div>
    右侧：图片展示
    <div class="publication-image">
        <img src="/images/papers/2025_VEM.jpg" alt="VEM mesh">
    </div>
</li>
-->

<!--
    发表论文：没有图片
<li class="publication-item">
    <div class="publication-content">
        Author names
        H. Liu, F. Wang*, S. Cheng, L. Qiu, <u>Y. Gong</u>.
        Title of the paper
        <a href="https://doi.org/10.1063/5.0191290" style="text-decoration:none; color:#DE3163;">
            Shape optimization of sound barriers using an isogeometric meshless method.
        </a>
        Journal information
        <b>Physics of Fluids</b> 36(2) (2024) 027116
        link of arXive
        <a href="https://arxiv.org/abs/2508.11410" style="text-decoration:none; color:#4A90E2;">
            [arXiv]
        </a>
    </div>
</li>
-->

<!-- 2026 -->
<br>
<hr>
<h3>2026</h3>

<!-- VEM FEM coupling method -->
<li class="publication-item">
    <!-- 左侧：论文信息 -->
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>, S. Li, Y. Mei*,B. Xu, F. Qin, X. Zhuang, T. Rabczuk. 
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.enganabound.2026.106640" style="text-decoration:none; color:#DE3163;">
        A coupled finite element-virtual element method for thermomechanical analysis of electronic packaging structures.
        </a> 
        <!-- Journal information -->
        <b>Engineering Analysis with Boundary Elements</b> 184 (2026) 106640.
        <a href="http://yanpeng-gong.github.io/files/papers/2026_VeFe.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
          <!-- link of arXive -->
        <a href="https://arxiv.org/abs/2511.09348" style="text-decoration:none; color:#4A90E2;">
          [arXiv]
        </a>
          <!-- link of open source code -->
        <a href="https://github.com/yanpeng-gong/VEM-electronic-packaging" style="text-decoration:none; color:#24292e;">
            <i class="fa fa-github" style="font-size:16px;"></i> [Code] 
        </a>
      </div>
       <!-- 右侧：图片展示 -->
      <div class="publication-image">
        <img src="/files/papers/2026_VeFe.jpg" alt="VE-FE Coupling mesh">
      </div>
</li>

<!-- 2025 -->
<br>
<hr>
<h3>2025</h3>

<li class="publication-item">
    <!-- 左侧：论文信息 -->
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>*, S. Li, F. Qin, B. Xu*. 
        <!-- Title of the paper -->
        <a href="https://link.springer.com/article/10.1007/s00366-025-02219-8" style="text-decoration:none; color:#DE3163;">
            Virtual element method for thermomechanical analysis of electronic packaging structures with multi-scale features.
        </a> 
        <!-- Journal information -->
        <b>Engineering with Computers</b> 41 (2025) 4799–4824
        <a href="http://yanpeng-gong.github.io/files/papers/2025_EC.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
        <!-- link of arXive -->
        <a href="https://arxiv.org/abs/2508.11410" style="text-decoration:none; color:#4A90E2;">
            [arXiv] 
        </a>
        <!-- link of open source code -->
        <a href="https://github.com/yanpeng-gong/VEM-electronic-packaging" style="text-decoration:none; color:#24292e;">
            <i class="fa fa-github" style="font-size:16px;"></i> [Code] 
        </a>
    </div>
    <!-- 右侧：图片展示 -->
    <div class="publication-image">
        <img src="/files/papers/2025_EC_VEM.jpg" alt="Mesh used in Virtual Element Method">
    </div>
</li>

<!-- Flexo -->
<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        X. Zhuang*, H. Hu**, S. S. Nanthakumar, Q.-T. Tran, <u>Y. Gong</u>, T. Rabczuk.
        <!-- Title of the paper -->
        <a href="https://dx.doi.org/10.1016/j.apm.2025.116327" style="text-decoration:none; color:#DE3163;">
            Variationally consistent Maxwell stress in flexoelectric structures under finite deformation and immersed in free space.
        </a>
        <!-- Journal information -->
        <b>Applied Mathematical Modelling</b> (2025) 116327
        <a href="http://yanpeng-gong.github.io/files/papers/2025_AMM.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>*, Y. Kou, Q. Yue*, X. Zhuang*, N. Valizadeh, F. Qin, Q. Wang, T. Rabczuk.
        <!-- Title of the paper -->
        <a href="https://dx.doi.org/10.1016/j.engfracmech.2025.111039" style="text-decoration:none; color:#DE3163;">
            A phase-field study on thermo-mechanical coupled damage evolution and failure mechanisms of sintered silver interconnections.
        </a>
        <!-- Journal information -->
        <b>Engineering Fracture Mechanics</b> (2025) 111039
        <a href="http://yanpeng-gong.github.io/files/papers/2025_EFM.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>*, Y. He, H. Hu, X. Zhuang*, F. Qin, H. Xu, T. Rabczuk.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.engstruct.2024.119500" style="text-decoration:none; color:#DE3163;">
            A coupled finite element–boundary element method for transient elastic dynamic analysis of electronic packaging structures.
        </a>
        <!-- Journal information -->
        <b>Engineering Structures</b> 326 (2025) 119500
        <a href="http://yanpeng-gong.github.io/files/papers/2025_ES.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        H. Liu, F. Wang*, S. Cheng, L. Qiu, <u>Y. Gong</u>.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1063/5.0191290" style="text-decoration:none; color:#DE3163;">
            Shape optimization of sound barriers using an isogeometric meshless method.
        </a>
        <!-- Journal information -->
        <b>Physics of Fluids</b> 36(2) (2024) 027116
        <a href="http://yanpeng-gong.github.io/files/papers/2024_POF.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        S. Li, <u>Y. Gong</u>*, F. Qin, P. Chen.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1109/ICEPT67137.2025.11156946" style="text-decoration:none; color:#DE3163;">
            Virtual Element Method for Thermomechanical Problems in Electronic Packaging.
        </a>
        <!-- Journal information -->
        <b>2025 26th International Conference on Electronic Packaging Technology (ICEPT)</b> (2025) 1-6
        <a href="http://yanpeng-gong.github.io/files/papers/2025_ICEPT_Li.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<!-- 2024 -->
<br>
<hr>
<h3>2024</h3>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>, Y. Kou, Q. Yue*, X. Zhuang*, F. Qin, Q. Wang, T. Rabczuk.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.icheatmasstransfer.2024.108033" style="text-decoration:none; color:#DE3163;">
            The application of thermomechanically coupled phase-field models in electronic packaging interconnect structures.
        </a>
        <!-- Journal information -->
        <b>International Communications in Heat and Mass Transfer</b> 159 (2024) 108033
        <a href="http://yanpeng-gong.github.io/files/papers/2024_ICHMT.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        Y. He, <u>Y. Gong</u>*, H. Xu, F. Qin.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1109/icept63120.2024.10668740" style="text-decoration:none; color:#DE3163;">
            A FEM-BEM Coupling Scheme for Elastic Dynamics Problems in Electronic Packaging.
        </a>
        <!-- Journal information -->
        <b>2024 25th International Conference on Electronic Packaging Technology (ICEPT)</b> (2024) 1-5
        <a href="http://yanpeng-gong.github.io/files/papers/2024_ICEPT2.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        S. Song, T. An*, F. Qin, <u>Y. Gong</u>, Y. Dai, P. Chen.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1109/ICEPT63120.2024.10668476" style="text-decoration:none; color:#DE3163;">
            Effect of Different Solder Layer Damage on Junction Temperature of IGBT Module.
        </a>
        <!-- Journal information -->
        <b>2024 25th International Conference on Electronic Packaging Technology (ICEPT)</b> (2024) 1-4
        <a href="http://yanpeng-gong.github.io/files/papers/2024_ICEPT.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<!-- 2023 -->
<br>
<hr>
<h3>2023</h3>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        F. Qin, Q. He, <u>Y. Gong</u>*, C. Hou, H. Cheng, T. An, Y. Dai, P. Chen.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1115/1.4055125" style="text-decoration:none; color:#DE3163;">
            An Automatic Finite Element Method-Boundary Element Method Coupling Method for Elastic–Plastic Problems of Multiscale Structures in Electronic Packaging.
        </a>
        <!-- Journal information -->
        <b>Journal of Electronic Packaging</b> 145(2) (2023)
        <a href="http://yanpeng-gong.github.io/files/papers/2023_JEP.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        H. Xu, <u>Y. Gong</u>*, Y. Kou, F. Qin.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1109/icept59018.2023.10492337" style="text-decoration:none; color:#DE3163;">
            An isogeometric boundary element scheme for transient heat transfer problems in electronic packaging.
        </a>
        <!-- Journal information -->
        <b>2023 24th International Conference on Electronic Packaging Technology (ICEPT)</b> (2023)
        <a href="http://yanpeng-gong.github.io/files/papers/2023_ICEPT.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        T. An, X. Chen, Q. Wang, J. Han*, F. Qin, Y. Dai, P. Chen, <u>Y. Gong</u>.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1080/08927022.2023.2225632" style="text-decoration:none; color:#DE3163;">
            Effect of Si segregation at grain boundaries on the mechanical behaviours of ageing Al metallization layer in insulated gate bipolar transistor module.
        </a>
        <!-- Journal information -->
        <b>Molecular Simulation</b> 49(13-14) (2023) 1281-1292
        <a href="http://yanpeng-gong.github.io/files/papers/2023_MS.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        Y. Dai*, S. Zhao, F. Qin*, T. An, <u>Y. Gong</u>, P. Chen.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.ijadhadh.2023.103422" style="text-decoration:none; color:#DE3163;">
            Shear fracture resistance enhancement through micropatterning on copper substrate for sintered nano silver joints.
        </a>
        <!-- Journal information -->
        <b>International Journal of Adhesion and Adhesives</b> 125 (2023) 103422
        <a href="http://yanpeng-gong.github.io/files/papers/2023_IJAA.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        M. Zhang, F. Qin*, S. Chen, Y. Dai*, Y. Jin, P. Chen, T. An, <u>Y. Gong</u>.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.mssp.2023.107353" style="text-decoration:none; color:#DE3163;">
            Holding time effect on mechanical properties and protrusion behaviors of through silicon via copper under various annealing processes.
        </a>
        <!-- Journal information -->
        <b>Materials Science in Semiconductor Processing</b> 158 (2023) 107353
        <a href="http://yanpeng-gong.github.io/files/papers/2023_MSSP.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        T. An*, R. Zhou, F. Qin*, Y. Dai, <u>Y. Gong</u>, P. Chen.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.3390/electronics12071650" style="text-decoration:none; color:#DE3163;">
            Comparative Study of the Parameter Acquisition Methods for the Cauer Thermal Network Model of an IGBT Module.
        </a>
        <!-- Journal information -->
        <b>Electronics</b> 12(7) (2023) 1650
        <a href="http://yanpeng-gong.github.io/files/papers/2023_Electronics.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        M. Zhang, F. Qin*, S. Chen, Y. Dai, Y. Jin, P. Chen, T. An, <u>Y. Gong</u>.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1109/TDMR.2022.3232128" style="text-decoration:none; color:#DE3163;">
            Effect of Capped Cu Layer on Protrusion Behaviors of Through Silicon via Copper (TSV-Cu) Under Double Annealing Conditions: Comparative Study.
        </a>
        <!-- Journal information -->
        <b>IEEE Transactions on Device and Materials Reliability</b> 23(1) (2023) 89-98
        <a href="http://yanpeng-gong.github.io/files/papers/2023_TDMR.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<!-- 2022 -->
<br>
<hr>
<h3>2022</h3>
<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        F. Wang*, Z. Chen, <u>Y. Gong</u>*.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1002/nme.7061" style="text-decoration:none; color:#DE3163;">
            Local knot method for solving inverse Cauchy problems of Helmholtz equations on complicated two‐ and three‐dimensional domains.
        </a>
        <!-- Journal information -->
        <b>International Journal for Numerical Methods in Engineering</b> 123(20) (2022) 4877-4892
        <a href="http://yanpeng-gong.github.io/files/papers/2022_IJNME.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        F. Qin, Q. He, <u>Y. Gong</u>*, T. An, P. Chen, Y. Dai.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.enganabound.2022.01.009" style="text-decoration:none; color:#DE3163;">
            The application of FEM-BEM coupling method for steady 2D heat transfer problems with multi-scale structure.
        </a>
        <!-- Journal information -->
        <b>Engineering Analysis with Boundary Elements</b> 137 (2022) 78-90
        <a href="http://yanpeng-gong.github.io/files/papers/2022_EABE.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>*, F. Qin, C. Dong, J. Trevelyan.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.apm.2022.03.047" style="text-decoration:none; color:#DE3163;">
            An isogeometric boundary element method for heat transfer problems of multiscale structures in electronic packaging with arbitrary heat sources.
        </a>
        <!-- Journal information -->
        <b>Applied Mathematical Modelling</b> 109 (2022) 161-185
        <a href="http://yanpeng-gong.github.io/files/papers/2022_AMM.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        B. Yu, G. Cao, S. Ren, <u>Y. Gong</u>, C. Dong*.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.applthermaleng.2022.118600" style="text-decoration:none; color:#DE3163;">
            An isogeometric boundary element method for transient heat transfer problems in inhomogeneous materials and the non-iterative inversion of loads.
        </a>
        <!-- Journal information -->
        <b>Applied Thermal Engineering</b> 212 (2022) 118600
        <a href="http://yanpeng-gong.github.io/files/papers/2022_ATE.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        F. Qin, S. Zhao, Y. Dai*, Y. Hu, T. An, <u>Y. Gong</u>.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1109/TCPMT.2022.3178226" style="text-decoration:none; color:#DE3163;">
            Mud-Cracking Effect of Sintered Silver Layer on Quantifying Heat Transfer Behavior of SiC Devices Under Power Cycling: Voronoi Tessellation Model.
        </a>
        <!-- Journal information -->
        <b>IEEE Transactions on Components, Packaging and Manufacturing Technology</b> 12(6) (2022) 964-972
        <a href="http://yanpeng-gong.github.io/files/papers/2022_TCPMT.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        S. Zhao, Y. Dai*, F. Qin, Y. Li, T. An, <u>Y. Gong</u>.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.engfracmech.2022.108355" style="text-decoration:none; color:#DE3163;">
            Effect of surface finish metallization layer on shearing fracture toughness of sintered silver bonded joints.
        </a>
        <!-- Journal information -->
        <b>Engineering Fracture Mechanics</b> 264 (2022) 108355
        <a href="http://yanpeng-gong.github.io/files/papers/2022_EFM.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        L. Chen, H. Lian, Z. Liu, <u>Y. Gong</u>, C. Zheng, S. Bordas*.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.enganabound.2021.11.005" style="text-decoration:none; color:#DE3163;">
            Bi-material topology optimization for fully coupled structural-acoustic systems with isogeometric FEM–BEM.
        </a>
        <!-- Journal information -->
        <b>Engineering Analysis with Boundary Elements</b> 135 (2022) 182-195
        <a href="http://yanpeng-gong.github.io/files/papers/2022_EABE2.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        T. An*, Z. Li, Y. Zhang, F. Qin, L. Wang, Z. Lin, X. Tang, Y. Dai, <u>Y. Gong</u>, P. Chen.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1109/TPEL.2021.3134175" style="text-decoration:none; color:#DE3163;">
            The Effect of the Surface Roughness Characteristics of the Contact Interface on the Thermal Contact Resistance of the PP-IGBT Module.
        </a>
        <!-- Journal information -->
        <b>IEEE Transactions on Power Electronics</b> 37(6) (2022) 7286-7298
        <a href="http://yanpeng-gong.github.io/files/papers/2022_TPE.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        C. Ma, F. Qin, <u>Y. Gong</u>*, C. Hou, H. Cheng, Q. He.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1109/ICEPT56209.2022.9873417" style="text-decoration:none; color:#DE3163;">
            A novel coupling simulation scheme for elastoplastic problems of multiscale structures in electronic packaging.
        </a>
        <!-- Journal information -->
        <b>2022 23rd International Conference on Electronic Packaging Technology (ICEPT)</b> (2022) 1-4
        <a href="http://yanpeng-gong.github.io/files/papers/2022_ICEPT.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        T. An*, Y. Tian, F. Qin, Y. Dai, <u>Y. Gong</u>, P. Chen.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1007/s43236-022-00449-3" style="text-decoration:none; color:#DE3163;">
            Comparison of junction temperature variations of IGBT modules under DC and PWM power cycling test conditions.
        </a>
        <!-- Journal information -->
        <b>Journal of Power Electronics</b> 22(9) (2022) 1561-1575
        <a href="http://yanpeng-gong.github.io/files/papers/2022_JPE.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        S. Zhao, S. Chen, F. Qin*, Y. Dai, <u>Y. Gong</u>.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1109/ICEPT56209.2022.9873205" style="text-decoration:none; color:#DE3163;">
            Thermal stress analysis of wafer-level multilayer stacking process for 3D-TSV packaging.
        </a>
        <!-- Journal information -->
        <b>2022 23rd International Conference on Electronic Packaging Technology (ICEPT)</b> (2022) 1-4
        <a href="http://yanpeng-gong.github.io/files/papers/2022_ICEPT2.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        R. Zhou, T. An*, F. Qin, <u>Y. Gong</u>, Y. Dai, P. Chen.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1109/ICEPT56209.2022.9873141" style="text-decoration:none; color:#DE3163;">
            Influence of chip layout on temperature distribution of multi-chip press pack IGBT devices.
        </a>
        <!-- Journal information -->
        <b>2022 23rd International Conference on Electronic Packaging Technology (ICEPT)</b> (2022) 1-4
        <a href="http://yanpeng-gong.github.io/files/papers/2022_ICEPT3.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        Y. Tian, T. An*, F. Qin, <u>Y. Gong</u>, Y. Dai, Y. Chen.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1109/ICEPT56209.2022.9873277" style="text-decoration:none; color:#DE3163;">
            Stress analysis of automotive IGBT module under vibration load.
        </a>
        <!-- Journal information -->
        <b>2022 23rd International Conference on Electronic Packaging Technology (ICEPT)</b> (2022) 1-4
        <a href="http://yanpeng-gong.github.io/files/papers/2022_ICEPT4.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<!-- 2021 -->
<br>
<hr>
<h3>2021</h3>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        H. Yu, Y. Guo, <u>Y. Gong</u>*, F. Qin.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.enganabound.2021.04.008" style="text-decoration:none; color:#DE3163;">
            Thermal analysis of electronic packaging structure using isogeometric boundary element method.
        </a>
        <!-- Journal information -->
        <b>Engineering Analysis with Boundary Elements</b> 128 (2021) 195-202
        <a href="http://yanpeng-gong.github.io/files/papers/2021_EABE.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        C. Wang, F. Wang*, <u>Y. Gong</u>*.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.3934/math.2021726" style="text-decoration:none; color:#DE3163;">
            Analysis of 2D heat conduction in nonlinear functionally graded materials using a local semi-analytical meshless method.
        </a>
        <!-- Journal information -->
        <b>AIMS Mathematics</b> 6(11) (2021) 12599-12618
        <a href="http://yanpeng-gong.github.io/files/papers/2021_AIMS.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        B. Yu*, G. Cao, Z. Meng, <u>Y. Gong</u>, C. Dong.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.cma.2021.113958" style="text-decoration:none; color:#DE3163;">
            Three-dimensional transient heat conduction problems in FGMs via IG-DRBEM.
        </a>
        <!-- Journal information -->
        <b>Computer Methods in Applied Mechanics and Engineering</b> 384 (2021) 113958
        <a href="http://yanpeng-gong.github.io/files/papers/2021_CMAME.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        B. Yu, G. Cao, <u>Y. Gong</u>*, S. Ren, C. Dong.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.enganabound.2021.04.014" style="text-decoration:none; color:#DE3163;">
            IG-DRBEM of three-dimensional transient heat conduction problems.
        </a>
        <!-- Journal information -->
        <b>Engineering Analysis with Boundary Elements</b> 128 (2021) 298-309
        <a href="http://yanpeng-gong.github.io/files/papers/2021_EABE2.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        F. Qin, L. Zhang, P. Chen*, T. An, Y. Dai, <u>Y. Gong</u>, Z. Yi, H. Wang.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.ymssp.2020.107550" style="text-decoration:none; color:#DE3163;">
            In situ wireless measurement of grinding force in silicon wafer self-rotating grinding process.
        </a>
        <!-- Journal information -->
        <b>Mechanical Systems and Signal Processing</b> 154 (2021) 107550
        <a href="http://yanpeng-gong.github.io/files/papers/2021_MSSP.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        F. Qin, S. Zhao, L. Liu, Y. Dai*, T. An, P. Chen, <u>Y. Gong</u>.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.microrel.2021.114290" style="text-decoration:none; color:#DE3163;">
            Thickness and metallization layer effect on interfacial and vertical cracking of sintered silver layer: A numerical investigation.
        </a>
        <!-- Journal information -->
        <b>Microelectronics Reliability</b> 124 (2021) 114290
        <a href="http://yanpeng-gong.github.io/files/papers/2021_MR.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        S. Zhao, Y. Dai*, F. Qin**, Y. Li, L. Liu, Z. Zan, T. An, P. Chen, <u>Y. Gong</u>, Y. Wang.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.msea.2021.141729" style="text-decoration:none; color:#DE3163;">
            On mode II fracture toughness of sintered silver based on end-notch flexure (ENF) test considering various sintering parameters.
        </a>
        <!-- Journal information -->
        <b>Materials Science and Engineering: A</b> 823 (2021) 141729
        <a href="http://yanpeng-gong.github.io/files/papers/2021_MSEA.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<!-- 2020 -->
<br>
<hr>
<h3>2020</h3>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>*, C. Dong, F. Qin, G. Hattori, J. Trevelyan.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.cma.2020.113099" style="text-decoration:none; color:#DE3163;">
            Hybrid nearly singular integration for three-dimensional isogeometric boundary element analysis of coatings and other thin structures.
        </a>
        <!-- Journal information -->
        <b>Computer Methods in Applied Mechanics and Engineering</b> 367 (2020) 113099
        <a href="http://yanpeng-gong.github.io/files/papers/2020_CMAME.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        F. Sun, <u>Y. Gong</u>, C. Dong*.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.cam.2020.112904" style="text-decoration:none; color:#DE3163;">
            A novel fast direct solver for 3D elastic inclusion problems with the isogeometric boundary element method.
        </a>
        <!-- Journal information -->
        <b>Journal of Computational and Applied Mathematics</b> 377 (2020) 112904
        <a href="http://yanpeng-gong.github.io/files/papers/2020_JCAM.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        Y. Guo, H. Yu, <u>Y. Gong</u>*, F. Qin.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1109/ICEPT50128.2020.9202534" style="text-decoration:none; color:#DE3163;">
            Thermal analysis of IGBT by isogeometric boundary element method.
        </a>
        <!-- Journal information -->
        <b>2020 21st International Conference on Electronic Packaging Technology (ICEPT)</b> (2020) 1-5
        <a href="http://yanpeng-gong.github.io/files/papers/2020_ICEPT.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        F. Qin, Y. Hu, Y. Dai*, T. An, P. Chen, <u>Y. Gong</u>, H. Yu.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1007/s11664-020-08325-1" style="text-decoration:none; color:#DE3163;">
            Crack Effect on the Equivalent Thermal Conductivity of Porously Sintered Silver.
        </a>
        <!-- Journal information -->
        <b>Journal of Electronic Materials</b> 49(10) (2020) 5994-6008
        <a href="http://yanpeng-gong.github.io/files/papers/2020_JEM.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<!-- 2019 -->
<br>
<hr>
<h3>2019</h3>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>, J. Trevelyan, G. Hattori, C. Dong*.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.cma.2018.12.019" style="text-decoration:none; color:#DE3163;">
            Hybrid nearly singular integration for isogeometric boundary element analysis of coatings and other thin 2D structures.
        </a>
        <!-- Journal information -->
        <b>Computer Methods in Applied Mechanics and Engineering</b> 346 (2019) 642-673
        <a href="http://yanpeng-gong.github.io/files/papers/2019_CMAME.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>, H. Yang, C. Dong*.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1007/s00466-018-1590-9" style="text-decoration:none; color:#DE3163;">
            A novel interface integral formulation for 3D steady state thermal conduction problem for a medium with non-homogenous inclusions.
        </a>
        <!-- Journal information -->
        <b>Computational Mechanics</b> 63(2) (2019) 181-199
        <a href="http://yanpeng-gong.github.io/files/papers/2019_CM.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        F. Sun, C. Dong*, Y. Wu, <u>Y. Gong</u>.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.amc.2019.04.030" style="text-decoration:none; color:#DE3163;">
            Fast direct isogeometric boundary element method for 3D potential problems based on HODLR matrix.
        </a>
        <!-- Journal information -->
        <b>Applied Mathematics and Computation</b> 359 (2019) 17-33
        <a href="http://yanpeng-gong.github.io/files/papers/2019_AMC.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<!-- 2018 -->
<br>
<hr>
<h3>2018</h3>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>, C. Dong*, X. Qu.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.advengsoft.2018.03.001" style="text-decoration:none; color:#DE3163;">
            An adaptive isogeometric boundary element method for predicting the effective thermal conductivity of steady state heterogeneity.
        </a>
        <!-- Journal information -->
        <b>Advances in Engineering Software</b> 119 (2018) 103-115
        <a href="http://yanpeng-gong.github.io/files/papers/2018_AES.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        X. Qu, C. Dong*, Y. Bai, <u>Y. Gong</u>.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.cam.2018.04.053" style="text-decoration:none; color:#DE3163;">
            Isogeometric boundary element method for calculating effective property of steady state thermal conduction in 2D heterogeneities with a homogeneous interphase.
        </a>
        <!-- Journal information -->
        <b>Journal of Computational and Applied Mathematics</b> 343 (2018) 124-138
        <a href="http://yanpeng-gong.github.io/files/papers/2018_JCAM.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<!-- 2017 -->
<br>
<hr>
<h3>2017</h3>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>, C. Dong*, X. Qin.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.cam.2016.10.003" style="text-decoration:none; color:#DE3163;">
            An isogeometric boundary element method for three dimensional potential problems.
        </a>
        <!-- Journal information -->
        <b>Journal of Computational and Applied Mathematics</b> 313 (2017) 454-468
        <a href="http://yanpeng-gong.github.io/files/papers/2017_JCAM.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>, C. Dong*, Y. Bai.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.enganabound.2016.11.005" style="text-decoration:none; color:#DE3163;">
            Evaluation of nearly singular integrals in isogeometric boundary element method.
        </a>
        <!-- Journal information -->
        <b>Engineering Analysis with Boundary Elements</b> 75 (2017) 21-35
        <a href="http://yanpeng-gong.github.io/files/papers/2017_EABE.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>, C. Dong*.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.cam.2016.12.038" style="text-decoration:none; color:#DE3163;">
            An isogeometric boundary element method using adaptive integral method for 3D potential problems.
        </a>
        <!-- Journal information -->
        <b>Journal of Computational and Applied Mathematics</b> 319 (2017) 141-158
        <a href="http://yanpeng-gong.github.io/files/papers/2017_JCAM2.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        X. Qin, C. Dong*, F. Wang, <u>Y. Gong</u>.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.tws.2017.03.019" style="text-decoration:none; color:#DE3163;">
            Free vibration analysis of isogeometric curvilinearly stiffened shells.
        </a>
        <!-- Journal information -->
        <b>Thin-Walled Structures</b> 116 (2017) 124-135
        <a href="http://yanpeng-gong.github.io/files/papers/2017_TWS.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<!-- 2015 -->
<br>
<hr>
<h3>2015</h3>
<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        Y. Zhang*, <u>Y. Gong</u>, X. Gao.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1016/j.enganabound.2014.12.006" style="text-decoration:none; color:#DE3163;">
            Calculation of 2D nearly singular integrals over high-order geometry elements using the sinh transformation.
        </a>
        <!-- Journal information -->
        <b>Engineering Analysis with Boundary Elements</b> 60 (2015) 144-153
        <a href="http://yanpeng-gong.github.io/files/papers/2015_EABE.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        X. Li, Y. Zhang*, <u>Y. Gong</u>, Y. Su, X. Gao.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1007/s00707-015-1361-z" style="text-decoration:none; color:#DE3163;">
            Use of the sinh transformation for evaluating 2D nearly singular integrals in 3D BEM.
        </a>
        <!-- Journal information -->
        <b>Acta Mechanica</b> 226(9) (2015) 2873-2885
        <a href="http://yanpeng-gong.github.io/files/papers/2015_AM.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        <u>Y. Gong</u>, Z. Jiang*, Y. Gao.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.1155/2015/418293" style="text-decoration:none; color:#DE3163;">
            On Jacobsthal and Jacobsthal-Lucas Circulant Type Matrices.
        </a>
        <!-- Journal information -->
        <b>Abstract and Applied Analysis</b> 2015 (2015) 418293
        <a href="http://yanpeng-gong.github.io/files/papers/2015_AAA.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<hr>
<h3>Other writings</h3>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        C. Ma, <u>Y. Gong</u>*, C. Hou, F. Qin.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.19457/j.cnki.11-1773/v.2022.05.015" style="text-decoration:none; color:#DE3163;">
            Analysis of FEM-BEM Coupling Method for Structures in Electronic Packaging (in Chinese).
        </a>
        <!-- Journal information -->
        <b>Structure & Environment Engineering</b> 49(5) (2022)
        <a href="http://yanpeng-gong.github.io/files/papers/2022_SEE.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        S. Zhao, <u>Y. Gong</u>*, C. Hou, F. Qin.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.19457/j.cnki.11-1773/v.2022.05.011" style="text-decoration:none; color:#DE3163;">
            Application of Direct Multilevel Finite Element Method in Multiscale Package Structures (in Chinese).
        </a>
        <!-- Journal information -->
        <b>Structure & Environment Engineering</b> 49(5) (2022)
        <a href="http://yanpeng-gong.github.io/files/papers/2022_SEE2.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        G. Sun, <u>Y. Gong</u>*, C. Hou, Y. Li, F. Qin.
        <!-- Title of the paper -->
        <a href="https://doi.org/10.19457/j.cnki.11-1773/v.2022.03.013" style="text-decoration:none; color:#DE3163;">
            Multiscale Package Structure Analysis Method Based on RVE-Submodel Method (in Chinese).
        </a>
        <!-- Journal information -->
        <b>Structure & Environment Engineering</b> 49(3) (2022)
        <a href="http://yanpeng-gong.github.io/files/papers/2022_SEE3.pdf" style="text-decoration:none;">
            <i class="fa fa-file-pdf-o" style="font-size:16px; color:black;"></i>
        </a>
    </div>
</li>

<h3>专著与书籍章节 Books & Book Chapters</h3>

<!-- 专著 -->
<li class="publication-item">
    <div class="publication-content">
        <!-- Author names -->
        C. Dong, <u>Y. Gong</u>, F. Sun.
        <!-- Title of the book -->
        Isogeometric Boundary Element Method (等几何边界元法).
        <!-- Publication information -->
        Science Press, Beijing, 1st Edition (May 2023) ISBN: 9787030742926
    </div>
</li>

 <!-- 书籍章节 -->
 <!--
 <li><u>Y. Gong</u>, F. Qin. Chapter 5: Computational Methods for Electronic Packaging. In: Advanced Electronic Packaging Technologies. Springer (2024) pp. 85-110</li>
-->
