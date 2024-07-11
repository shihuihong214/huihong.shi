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

Hello, welcome to my page!

My name is **<span style="color: #CC6600;">Huihong Shi</span>**, and I am currently a 5th-year Ph.D. student in the School of Electronic Science and Engineering at **<span style="color: #1976D2;">Nanjing University</span>**, under the supervision of **<span style="color: #CC6600;">Prof. Zhongfeng Wang</span>**. From April 2021 to December 2022, I was a visiting student at the EIC Lab at **<span style="color: #1976D2;">Rice University</span>**, supervised remotely by **<span style="color: #CC6600;">Prof. Yingyan Lin</span>**. I also visited the EIC Lab at **<span style="color: #1976D2;">the Georgia Institute of Technology</span>** in person from December 2023 to May 2024. 

My research interests include **<span style="color: #1976D2;">efficient and automated machine learning</span>**, as well as **<span style="color: #1976D2;">algorithm and hardware accelerator co-design</span>**.

My **<span style="color: #CC6600;">CV</span>** can be downloaded here!

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- <span class='anchor' id='/educations/'></span> -->
<!-- permalink: /terms/ -->
# 📖 Educations
- *2019.06 - now*, <span style="color: #1976D2;">Nanjing University</span>, School of Electronic Science and Engineering, <span style="color: #006400;">Ph.D. student</span> supervised by <span style="color: #CC6600;">Prof. Zhongfeng Wang</span>. 

- *2023.12 - 2024.05*, <span style="color: #1976D2;">Georgia Institute of Technology</span>, School of Computer Science, <span style="color: #006400;">visiting student</span> supervised by <span style="color: #CC6600;">Prof. Yingyan Lin</span>. 

- *2021.03 - 2022.12*, <span style="color: #1976D2;">Rice University (Remote)</span>, Schole of Electrical and Computer Engineering, <span style="color: #006400;">visiting student</span> supervised by <span style="color: #CC6600;">Prof. Yingyan Lin</span>. 

- *2016.09 - 2020.06*, <span style="color: #1976D2;">Jilin University</span>, School of Communication Engineering, <span style="color: #006400;">Bachelor</span>. 

# 📝 Publications 
<!-- *********Trio^ViT********* -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/trio-vit.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Trio-ViT: Post-Training Quantization and Acceleration for Softmax-Free Efficient Vision Transformer.](https://arxiv.org/abs/2405.03882)

**<span style="color: #006400;">Huihong Shi</span>**, Haikuo Shao, Wendong Mao, Zhongfeng Wang

<!-- [**Journal**] IEEE Transactions on Very Large Scale Integration Systems (TVLSI 2024) -->

[**Abstract**]
We propose Trio-ViT to marry the hardware efficiency of both quantization and efficient Vision Transformer (ViT) architectures, which (1) eliminate the troublesome Softmax and (2) integrate linear attention with low computational complexity.
</div>
</div>

<!-- *********NASH********* -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/nash.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NASH: Neural Architecture and Accelerator Search for Multiplication-Reduced Hybrid Models.]()

Yang Xu\*, **<span style="color: #006400;">Huihong Shi\*</span>**, Zhongfeng Wang (\*Co-first Authors)

<!-- [**Journal**] IEEE Transactions on Very Large Scale Integration Systems (TVLSI 2024) -->

[**Abstract**]
We propose a Neural **Architecture and Accelerator Co-Search** framework (NASH) for *multiplication-reduced hybrid models*. We introduce a tailored ***zero-shot metric*** for architecture search to pre-identify promising models, enhancing efficiency and reducing gradient conflicts. For accelerator search, we use a ***coarse-to-fine approach*** to streamline the process. By integrating both searches, NASH achieves optimal model and accelerator pairing.
</div>
</div>

<!-- *********P^ViT********* -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVLSI 2024</div><img src='images/p2-vit.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[P$^2$-ViT: Power-of-Two Post-Training Quantization and Acceleration for Fully Quantized Vision Transformer.](http://arxiv.org/abs/2405.19915)

**<span style="color: #006400;">Huihong Shi</span>**, Xin Cheng, Wendong Mao, Zhongfeng Wang

[**Journal**] IEEE Transactions on Very Large Scale Integration Systems (TVLSI 2024)

[**Abstract**]
We propose a Power-of-Two (PoT) post-training quantization and acceleration framework (P$^2$-ViT) for Vision Transformers (ViTs). We first propose a dedicated quantization scheme with ***PoT scaling factors*** to minimize re-quantization overhead and further develop a ***dedicated accelerator*** to enhance throughput.
</div>
</div>

<!-- *********ShiftAddViT********* -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/shiftaddvit.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ShiftAddViT: Mixture of Multiplication Primitives Towards Efficient Vision Transformer.](https://proceedings.neurips.cc/paper_files/paper/2023/file/69c49f75ca31620f1f0d38093d9f3d9b-Paper-Conference.pdf)

Haoran You\*, **<span style="color: #006400;">Huihong Shi\*</span>**, Yipin Guo\*, Zhongfeng Wang (\*Co-first Authors)

[**Conference**] Thirty-seventh Conference on Neural Information Processing Systems (NeurIPS 2023)

[**Abstract**]
We reparameterize pre-trained Vision Transformers (ViTs) with ***a mixture of multiplication primitives***, such as bitwise shifts and additions, to obtain ShiftAddViT. This approach aims to achieve end-to-end ***inference speedups on GPUs*** without requiring training from scratch.
</div>
</div>

<!-- *********Vitality********* -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">HPCA 2023</div><img src='images/vitality.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ViTALiTy: Unifying Low-rank and Sparse Approximation for Vision Transformer Acceleration with a Linear Taylor Attention.](https://ieeexplore.ieee.org/abstract/document/10071081)

Jyotikrishna Dass\*, Shang Wu\*, **<span style="color: #006400;">Huihong Shi\*</span>**, Chaojian Li, Zhifan Ye, Zhongfeng Wang, Yingyan Lin (\*Co-first Authors)

[**Conference**] International Symposium on High-Performance Computer Architecture (HPCA 2023)

[**Abstract**]
We propose VITALITY to boost the **inference efficiency of Vision Transformers (ViTs)** via algorithm-hardware co-design. We first approximate the vanilla softmax with first-order ***Taylor attention for linear complexity*** and unifies low-rank and sparse components to enhance accuracy. We further develop a ***dedicated accelerator*** that leverages the linearized workload to improve hardware efficiency.
</div>
</div>


<!-- *********NASA-F+********* -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCAS-I 2024</div><img src='images/nasa-f.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NASA-F: FPGA-Oriented Search and Acceleration for Multiplication-Reduced Hybrid Networks.](https://ieeexplore.ieee.org/abstract/document/10308526)

**<span style="color: #006400;">Huihong Shi</span>**, Yang Xu, Wendong Mao, Zhongfeng Wang 

[**Journal**] IEEE Transactions on Circuits and Systems I (TCAS-I 2024)

[**Abstract**]
We propose an **FPGA-oriented** search and acceleration framework called NASA-F for multiplication-reduced hybrid models. Specifically, we fully leverage the ***diverse hardware resources*** (DSPs and LUTs) available on FPGAs to accelerate ***heterogeneous layers*** in hybrid models, aiming to enhance both hardware utilization and throughput.

</div>
</div>


<!-- *********NASA+********* -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCAS-I 2023</div><img src='images/NASA2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NASA$+$: Neural Architecture Search and Acceleration for Multiplication-Reduced Hybrid Networks.](https://ieeexplore.ieee.org/abstract/document/10078392)

**<span style="color: #006400;">Huihong Shi</span>**, Haoran You, Zhongfeng Wang, Yingyan Lin

[**Journal**] IEEE Transactions on Circuits and Systems I (TCAS-I 2023)

[**Abstract**]
Inspired by the fact that multiplications can be mathematically decomposed into bit-wise shifts and additions, we design **reconfigurable PEs** to simultaneously support multiplication-based convolutions, shift, and adder layers, thus enhancing the flexibility of our accelerator.

</div>
</div>

<!-- *********NASA********* -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCAD 2022</div><img src='images/nasa.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NASA: Neural Architecture Search and Acceleration for Hardware Inspired Hybrid Networks.](https://dl.acm.org/doi/abs/10.1145/3508352.3549478)

**<span style="color: #006400;">Huihong Shi</span>**, Haoran You, Yang Zhao, Zhongfeng Wang, Yingyan Lin

[**Conference**] International Conference on Computer-Aided Design (ICCAD 2022)

[**Abstract**]
We propose a **Neural Architecture Search and Acceleration framework** (NASA) to enable automated search and acceleration of ***multiplication-reduced models***, aiming to marry the powerful performance of multiplication-based models and the hardware efficiency of multiplication-free models.
</div>
</div>

<!-- *********litnet********* -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCNN 2021</div><img src='images/litnet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LITNet: A Light-weight Image Transform Net for Image Style Transfer.](https://ieeexplore.ieee.org/abstract/document/9533679)

**<span style="color: #006400;">Huihong Shi</span>**, Wendong Mao, Zhongfeng Wang

[**Conference**] International Joint Conference on Neural Networks (IJCNN 2021)

[**Abstract**]
We propose a compression algorithm for one of the influential CNN-based **style transfer** networks, named Image Transform Net (ITNet), resulting in a lightweight model called Light-weight Image Transform Net (LITNet). Additionally, we introduce ***a novel distillation loss*** to convert unsupervised learning into supervised learning, aiming to enhance generation quality.
</div>
</div>


- [An FPGA-Based Reconfigurable Accelerator for Convolution-Transformer Hybrid EfficientViT](https://arxiv.org/abs/2403.20230), H. Shao, **<span style="color: #006400;">H. Shi</span>**, W. Mao, Z. Wang. IEEE International Symposium on Circuits and Systems 2024 **(ISCAS 2024)**

- [A Computationally Efficient Neural Video Compression Accelerator Based on a Sparse CNN-Transformer Hybrid](https://arxiv.org/html/2312.10716v1), S. Zhang, W. Mao, **<span style="color: #006400;">H. Shi</span>**, Z. Wang. Design, Automation and Test in Europe Conference **(DATE 2024)**

- [ViTCoD: Vision Transformer Acceleration via Dedicated Algorithm and Accelerator Co-Design](https://ieeexplore.ieee.org/abstract/document/10071027), H. You, Z. Sun, **<span style="color: #006400;">H. Shi</span>**, Z. Yu, Y. Zhao, Y. Zhang, C. Li, B. Li, Y. Lin. International Symposium on High-Performance Computer Architecture **(HPCA 2023)**

- [S$^2$R: Exploring a Double-Win Transformer-Based Framework for Ideal and Blind Super-Resolution](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=j7AChUYAAAAJ&citation_for_view=j7AChUYAAAAJ:Y0pCki6q_DkC), M. She, W. Mao, **<span style="color: #006400;">H. Shi</span>**, Z Wang. International Conference on Artificial Neural Networks **(ICANN 2023)**

- [ShiftAddNAS: Hardware-Inspired Search for More Accurate and Efficient Neural Networks](https://proceedings.mlr.press/v162/you22a.html), H. You, B. Li, **<span style="color: #006400;">H. Shi</span>**, Y. Lin. International Conference on Machine Learning **(ICML 2022)**

- [Intelligent Typography: Artistic Text Style Transfer for Complex Texture and Structure](https://ieeexplore.ieee.org/abstract/document/9906917), W. Mao, S. Yang, **<span style="color: #006400;">H. Shi</span>**, J. Liu, Z. Wang. IEEE Transactions on Multimedia **(TMM 2022)**

- [Unveiling and Harnessing Hidden Attention Sinks: Enhancing Large Language Models without Training through Attention Calibration](https://arxiv.org/abs/2406.15765), Z. Yu, Z. Wang, Y. Fu, **<span style="color: #006400;">H. Shi</span>**, K. Shaikh, Y. Lin. International Conference on Machine Learning **(ICML 2024)**

- [Max-Affine Spline Insights Into Deep Network Pruning](https://arxiv.org/abs/2406.15765), H. You, R. Balestriero, Z. Lu, Y. Kou, **<span style="color: #006400;">H. Shi</span>**, S. Zhang, S. Wu, Y. Lin. Transactions on Machine Learning Research **(TMLR 2024)**

- [Instant-3D: Instant Neural Radiance Field Training Towards On-Device AR/VR 3D Reconstruction](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=j7AChUYAAAAJ&citation_for_view=j7AChUYAAAAJ:zYLM7Y9cAGgC), S. Li, C. Li, W. Zhu, C. Wan, H. You, **<span style="color: #006400;">H. Shi</span>**, Y. Lin. International Symposium on Computer Architecture **(ISCA 2023)**

# 🎖 Honors and Awards
- *2023.09* The First-Class Academic Scholarship for Postgraduate Students at Nanjing University. 
- *2022.09* The First-Class Academic Scholarship for Postgraduate Students at Nanjing University. 
- *2021.09* The First-Class Academic Scholarship for Postgraduate Students at Nanjing University. 
- *2020.09* President's Special Scholarship for Doctoral Candidate of Nanjing University.  
- *2019.10* Post and Telecommunications Alumni Scholarship for Undergraduates of Jilin University.
- *2019.09* The First-Class Academic Scholarship for Undergraduates of Jilin University.
- *2018.09* The First-Class Academic Scholarship for Undergraduates of Jilin University.
- *2017.09* National Scholarship Award for Undergraduates Issued by Ministry of Education of China.


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->