---
widget: blank
headless: true
weight: 30
# title: Explore talks
# subtitle:
# content:
#   filters:
#     folders:
#       - course
#     kinds:
#       - section
#     exclude_tags:
#       - preface

  # filter_default: 0

  # filter_button:
  #   - name: All Talks
  #     tag: '*'
  #   - name: Previous
  #     tag: previous
  #   - name: Current
  #     tag: current
# design:
  # columns: '1'
#   view: masonry
#   flip_alt_rows: false
---
---
<section id="courses" class="some-section">
    <div class="row">
        <div class="col-12">
            <div class="listing" style="clear:both;">
                <div class="left" style="margin-bottom: 10px;">
                    <h3 style="text-align:center; font-style: italic;"> Upcoming Talks, Winter 2024</h3>
                    <!-- Add a new talk -->
                    <h4 style="margin-top: 20px;">Jan 23, 2024</h4>
                    <ul style="padding-left: 0;">
                        <li style="list-style-type: none;">
                            <b>
                                <a style="color: #2c3e50;"> Title: When randomized algorithms meet tensor decompositions </a> 
                            </b>
                            <br> Presenter: Beheshteh Toloui Rakhshan  
                            <br>
                            <!-- <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkBio" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Speaker Bio
                            </a> -->
                            <!-- <div class="collapse" id="newTalkBio">
                                <div class="card card-body" style="margin-top: 10px;">
                                    Guillaume Rabusseau is an assistant professor at Univeristé de Montréal since 2018 and holds a Canada CIFAR AI chair at the Mila research institute since 2019. Prior to joining Mila, he was an IVADO postdoctoral research fellow in the Reasoning and Learning Lab at McGill University, where he worked with Prakash Panangaden, Joelle Pineau and Doina Precup. He obtained his PhD in computer science in 2016 at Aix-Marseille University under the supervision of François Denis and Hachem Kadri. His research interests lie at the intersection of theoretical computer science and machine learning, and his work revolves around exploring inter-connections between tensors and machine learning to develop efficient learning methods for structured data relying on linear and multilinear algebra, and on the tensor network formalism.
                                </div>
                            </div> -->
                            <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkAbstract" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Abstract
                            </a>
                            <div class="collapse" id="newTalkAbstract">
                                <div class="card card-body" style="margin-top: 10px;">    
                                Tensor decomposition methods have recently found numerous applications in machine learning. Their ability to perform operations efficiently on very high-dimensional tensor data makes them ubiquitous in data science and machine learning. Due to the curse of dimensionality of tensors, designing efficient algorithms for very high dimensional tensor data is challenging. On the other hand, finding a decomposition of high-dimensional tensors is crucial. Many tensor decompositions correspond to either difficult non-convex optimization problems or the running time is exponential in the order of a tensor. To address these issues, several recent works have developed randomized-based algorithms. These issues have led to the search for alternatives based on randomization and sampling techniques. In this talk, we will be giving a tutorial on randomized algorithms and their application in tensor network methods.
                                </div>
                            <!-- </div>
                            <a href="notes/TNRG.pdf" download="TNRG.pdf" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Notes</a>
                            <a href="https://www.youtube.com/channel/UCajE0Tzf0r3qORFsQIemglA" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Recording Link</a> -->
                        </li>
                    </ul>
                    <!-- Add more talks here if needed -->
                    <h4 style="margin-top: 20px;">Jan 30, 2024</h4>
                    <ul style="padding-left: 0;">
                        <li style="list-style-type: none;">
                            <b>
                                <a style="color: #2c3e50;"> Title: Sampling-Based Decomposition Algorithms for Arbitrary Tensor Networks </a> 
                            </b>
                            <br> Presenter: Osman Malik  
                            <br>
                            <!-- <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkBio" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Speaker Bio
                            </a> -->
                            <!-- <div class="collapse" id="newTalkBio">
                                <div class="card card-body" style="margin-top: 10px;">
                                    Guillaume Rabusseau is an assistant professor at Univeristé de Montréal since 2018 and holds a Canada CIFAR AI chair at the Mila research institute since 2019. Prior to joining Mila, he was an IVADO postdoctoral research fellow in the Reasoning and Learning Lab at McGill University, where he worked with Prakash Panangaden, Joelle Pineau and Doina Precup. He obtained his PhD in computer science in 2016 at Aix-Marseille University under the supervision of François Denis and Hachem Kadri. His research interests lie at the intersection of theoretical computer science and machine learning, and his work revolves around exploring inter-connections between tensors and machine learning to develop efficient learning methods for structured data relying on linear and multilinear algebra, and on the tensor network formalism.
                                </div>
                            </div> -->
                            <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkAbstract_012024" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Abstract
                            </a>
                            <div class="collapse" id="newTalkAbstract_012024">
                                <div class="card card-body" style="margin-top: 10px;">    
                               We show how to develop sampling-based alternating least squares (ALS) algorithms for
                                decomposition of tensors into any tensor network (TN) format. Provided the TN format
                                satisfies certain mild assumptions, resulting algorithms will have input sublinear per-iteration
                                cost. Unlike most previous works on sampling-based ALS methods for tensor decomposition,
                                the sampling in our framework is done according to the exact leverage score distribution of the
                                design matrices in the ALS subproblems. We implement and test two tensor decomposition
                                algorithms that use our sampling framework in a feature extraction experiment where we
                                compare them against a number of other decomposition algorithms.
                                </div>
                            <!-- </div>
                            <a href="notes/TNRG.pdf" download="TNRG.pdf" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Notes</a>
                            <a href="https://www.youtube.com/channel/UCajE0Tzf0r3qORFsQIemglA" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Recording Link</a> -->
                        </li>
                    </ul>
                     <!-- Add more talks here if needed -->
                    <h4 style="margin-top: 20px;">Feb 6, 2024</h4>
                    <ul style="padding-left: 0;">
                        <li style="list-style-type: none;">
                            <b>
                                <a style="color: #2c3e50;"> Title: Fast Exact Leverage Score Sampling from Khatri-Rao Products with Applications to Tensor Decomposition </a> 
                            </b>
                            <br> Presenter: Vivek Bharadwaj  
                            <br>
                            <!-- <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkBio" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Speaker Bio
                            </a> -->
                            <!-- <div class="collapse" id="newTalkBio">
                                <div class="card card-body" style="margin-top: 10px;">
                                    Guillaume Rabusseau is an assistant professor at Univeristé de Montréal since 2018 and holds a Canada CIFAR AI chair at the Mila research institute since 2019. Prior to joining Mila, he was an IVADO postdoctoral research fellow in the Reasoning and Learning Lab at McGill University, where he worked with Prakash Panangaden, Joelle Pineau and Doina Precup. He obtained his PhD in computer science in 2016 at Aix-Marseille University under the supervision of François Denis and Hachem Kadri. His research interests lie at the intersection of theoretical computer science and machine learning, and his work revolves around exploring inter-connections between tensors and machine learning to develop efficient learning methods for structured data relying on linear and multilinear algebra, and on the tensor network formalism.
                                </div>
                            </div> -->
                            <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkAbstract_022024" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Abstract
                            </a>
                            <div class="collapse" id="newTalkAbstract_022024">
                                <div class="card card-body" style="margin-top: 10px;">    
                              We present a data structure to randomly sample rows from the Khatri-Rao product
                                of several matrices according to the exact distribution of its leverage scores. Our
                                proposed sampler draws each row in time logarithmic in the height of the KhatriRao product and quadratic in its column count, with persistent space overhead
                                at most the size of the input matrices. As a result, it tractably draws samples
                                even when the matrices forming the Khatri-Rao product have tens of millions
                                of rows each. When used to sketch the linear least squares problems arising in
                                CANDECOMP / PARAFAC tensor decomposition, our method achieves lower
                                asymptotic complexity per solve than recent state-of-the-art methods. Experiments
                                on billion-scale sparse tensors validate our claims, with our algorithm achieving
                                higher accuracy than competing methods as the decomposition rank grows.
                                </div>
                            <!-- </div>
                            <a href="notes/TNRG.pdf" download="TNRG.pdf" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Notes</a>
                            <a href="https://www.youtube.com/channel/UCajE0Tzf0r3qORFsQIemglA" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Recording Link</a> -->
                        </li>
                    </ul>
                                         <!-- Add more talks here if needed -->
                    <h4 style="margin-top: 20px;">Feb 20, 2024</h4>
                    <ul style="padding-left: 0;">
                        <li style="list-style-type: none;">
                            <b>
                                <a style="color: #2c3e50;"> Title: Cost-efficient Gaussian tensor network embeddings for tensor-structured inputs </a> 
                            </b>
                            <br> Presenter: Linjian Ma  
                            <br>
                            <!-- <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkBio" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Speaker Bio
                            </a> -->
                            <!-- <div class="collapse" id="newTalkBio">
                                <div class="card card-body" style="margin-top: 10px;">
                                    Guillaume Rabusseau is an assistant professor at Univeristé de Montréal since 2018 and holds a Canada CIFAR AI chair at the Mila research institute since 2019. Prior to joining Mila, he was an IVADO postdoctoral research fellow in the Reasoning and Learning Lab at McGill University, where he worked with Prakash Panangaden, Joelle Pineau and Doina Precup. He obtained his PhD in computer science in 2016 at Aix-Marseille University under the supervision of François Denis and Hachem Kadri. His research interests lie at the intersection of theoretical computer science and machine learning, and his work revolves around exploring inter-connections between tensors and machine learning to develop efficient learning methods for structured data relying on linear and multilinear algebra, and on the tensor network formalism.
                                </div>
                            </div> -->
                            <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkAbstract_032024" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Abstract
                            </a>
                            <div class="collapse" id="newTalkAbstract_032024">
                                <div class="card card-body" style="margin-top: 10px;">    
                              This work discusses tensor network embeddings, which are random matrices (S)
                                with tensor network structure. These embeddings have been used to perform dimensionality reduction of tensor network structured inputs x and accelerate applications such as tensor decomposition and kernel regression. Existing works have
                                designed embeddings for inputs x with specific structures, such as the Kronecker
                                product or Khatri-Rao product, such that the computational cost for calculating Sx
                                is efficient. We provide a systematic way to design tensor network embeddings
                                consisting of Gaussian random tensors, such that for inputs with more general
                                tensor network structures, both the sketch size (row size of S) and the sketching
                                computational cost are low.
                                </div>
                            <!-- </div>
                            <a href="notes/TNRG.pdf" download="TNRG.pdf" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Notes</a>
                            <a href="https://www.youtube.com/channel/UCajE0Tzf0r3qORFsQIemglA" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Recording Link</a> -->
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</section>

---

<section id="courses" class="some-section">
    <div class="row">
        <div class="col-12">
            <div class="listing" style="clear:both;">
                <div class="left" style="margin-bottom: 10px;">
                    <h3 style="text-align:center; font-style: italic;"> Past Talks, Fall 2023</h3>
                    <!-- Add a new talk -->
                    <h4 style="margin-top: 20px;">Oct 17, 2023</h4>
                    <ul style="padding-left: 0;">
                        <li style="list-style-type: none;">
                            <b>
                                <a style="color: #2c3e50;"> Title: Introduction to Tensor Networks </a> 
                            </b>
                            <br> Presenter: Guillaume Rabusseau  
                            <br>
                            <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkBio" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Speaker Bio
                            </a>
                            <div class="collapse" id="newTalkBio">
                                <div class="card card-body" style="margin-top: 10px;">
                                    Guillaume Rabusseau is an assistant professor at Univeristé de Montréal since 2018 and holds a Canada CIFAR AI chair at the Mila research institute since 2019. Prior to joining Mila, he was an IVADO postdoctoral research fellow in the Reasoning and Learning Lab at McGill University, where he worked with Prakash Panangaden, Joelle Pineau and Doina Precup. He obtained his PhD in computer science in 2016 at Aix-Marseille University under the supervision of François Denis and Hachem Kadri. His research interests lie at the intersection of theoretical computer science and machine learning, and his work revolves around exploring inter-connections between tensors and machine learning to develop efficient learning methods for structured data relying on linear and multilinear algebra, and on the tensor network formalism.
                                </div>
                            </div>
                            <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkAbstract" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Abstract
                            </a>
                            <div class="collapse" id="newTalkAbstract">
                                <div class="card card-body" style="margin-top: 10px;">
                                    In this talk, I will give a tutorial on tensor networks and briefly present some of their applications in Machine Learning.
                                    Tensors are high order generalization of vectors and matrices. Similar to matrix factorization techniques, one of the goal of tensor decomposition techniques is to express a tensor as a product of small factors, thus reducing the number of parameters and potentially regularizing machine learning models. While linear algebra is ubiquitous and taught in most undergrad curriculum, tensor and multilinear algebra can be daunting. In this talk, I will try to give an easy and accessible introduction to tensor methods using the tensor network formalism. Tensor networks are an intuitive diagrammatic notation allowing one to easily reason about complex operations on high-order tensors.
                                </div>
                            </div>
                            <a href="notes/TNRG.pdf" download="TNRG.pdf" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Notes</a>
                            <a href="https://www.youtube.com/channel/UCajE0Tzf0r3qORFsQIemglA" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Recording Link</a>
                        </li>
                    </ul>
                    <!-- Add more talks here if needed -->
                </div>
            </div>
        </div>
    </div>
                    <!-- Add a new talk -->
                    <h4 style="margin-top: 20px;">Oct 24, 2023</h4>
                    <ul style="padding-left: 0;">
                        <li style="list-style-type: none;">
                            <b>
                                <a style="color: #2c3e50;"> Title: Tensor network structure search (TN-SS) </a> 
                            </b>
                            <br> Presenter: Chao Li  
                            <br>
                            <!-- <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkBio" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Speaker Bio
                            </a>
                            <div class="collapse" id="newTalkBio">
                                <div class="card card-body" style="margin-top: 10px;">
                                </div>
                            </div> -->
                             <a href="https://arxiv.org/abs/2304.12875" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Reading
                             </a>
                            <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkAbstract_0" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                               Abstract
                            </a>
                            <div class="collapse" id="newTalkAbstract_0">
                                <div class="card card-body" style="margin-top: 10px;">
                                 Tensor networks (TN) represent a formidable framework within machine learning. However, the selection of an effective TN model—a process known as Tensor Network Structure Search (TN-SS)—remains a computationally challenging endeavor. In my presentation, I will offer a succinct overview of our approach to this issue. I will concentrate on problem formulation and solution strategies from the standpoint of discrete optimization. Specifically, I will discuss three algorithms and the associated theoretical findings, which have been the subject of my research and were published in ICML conferences in 2020, 2022, and 2023.
                                </div>
                            </div>
                            <a href="notes/TNSSMILA.pdf" download="TNSSMILA.pdf" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Notes</a>
                            <a href="https://www.youtube.com/channel/UCajE0Tzf0r3qORFsQIemglA" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Recording Link</a>
                        </li>
                    </ul>
                    <!-- Add more talks here if needed -->
                    <h4 style="margin-top: 20px;">Oct 31, 2023</h4>
                    <ul style="padding-left: 0;">
                        <li style="list-style-type: none;">
                            <b>
                                <a style="color: #2c3e50;"> Title: TNS and non-equilibrium dynamics </a> 
                            </b>
                            <br> Presenter: Mari Carmen Bañuls 
                            <br>
                            <!-- <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkBio" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Speaker Bio
                            </a>
                            <div class="collapse" id="newTalkBio">
                                <div class="card card-body" style="margin-top: 10px;">
                                </div>
                            </div> -->
                            <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkAbstract_3" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Abstract
                            </a>
                            <div class="collapse" id="newTalkAbstract_3">
                                <div class="card card-body" style="margin-top: 10px;">
                                Tensor Network States (TNS) are ansatzes that can efficiently represent certain states of quantum many-body systems. In one spatial dimension, the paradigmatic example is the family of Matrix Product States (MPS), extremely powerful to study ground states, low energy excitations, and thermal equilibrium states. Quantum information theory provides tools to understand why TNS are good ansatzes for physically relevant states, and some of the limitations connected to the simulation algorithms. Most significantly, while to some extent TNS can be used to study real time evolution, a full description of the most general out-of-equilibrium setup is often out of reach.  
In this talk I will present the basic ideas behind TNS algorithms, as well as the limitations and some alternative approaches that try to push their application for dynamical problems.
                                </div>
                            </div>
                            <a href="notes/TNSandQMBDynamics_TNRG_Oct23.pdf" download="TNSandQMBDynamics_TNRG_Oct23.pdf" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Notes</a>
                            <a href="https://arxiv.org/abs/2209.11788" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Reading</a>
                            <a href="https://www.youtube.com/watch?v=mrPAZ-ZqdGg" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Recording Link</a>
                        </li>
                    </ul>
                     <!-- Add more talks here if needed -->
                    <h4 style="margin-top: 20px;">Nov 7th, 2023</h4>
                    <ul style="padding-left: 0;">
                        <li style="list-style-type: none;">
                            <b>
                                <a style="color: #2c3e50;"> Title: MultiHU-TD: Multi-feature Hyperspectral Unmixing Based on Tensor Decomposition </a> 
                            </b>
                            <br> Presenter: Mohamad Jouni 
                            <br>
                            <!-- <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkBio" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Speaker Bio
                            </a>
                            <div class="collapse" id="newTalkBio">
                                <div class="card card-body" style="margin-top: 10px;">
                                </div>
                            </div> -->
                            <!-- <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkAbstract" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Abstract
                            </a>
                            <div class="collapse" id="newTalkAbstract">
                                <div class="card card-body" style="margin-top: 10px;">
                                </div>
                            </div> -->
                            <a href="notes/MultiHUTD_slides.pdf" download="MultiHUTD_slides.pdf" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Notes</a>
                            <a href="https://arxiv.org/abs/2310.03860" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Reading</a>
                            <a href="https://youtu.be/OUimbKVZtvs?si=2KGShraYZD6PFxN7" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Recording Link</a>
                        </li>
                    </ul>
                    <h4 style="margin-top: 20px;">Nov 14, 2023</h4>
                    <ul style="padding-left: 0;">
                        <li style="list-style-type: none;">
                            <b>
                                <a style="color: #2c3e50;"> Title: What Makes Data Suitable for a Locally Connected Neural Network? A Necessary and Sufficient Condition Based on Quantum Entanglement </a> 
                            </b>
                            <br> Presenter: Yotam Alexander 
                            <br>
                            <!-- <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkBio" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Speaker Bio
                            </a>
                            <div class="collapse" id="newTalkBio">
                                <div class="card card-body" style="margin-top: 10px;">
                                </div>
                            </div> -->
                            <!-- <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkAbstract" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Abstract
                            </a>
                            <div class="collapse" id="newTalkAbstract">
                                <div class="card card-body" style="margin-top: 10px;">
                                </div>
                            </div> -->
                            <a href="notes/talk_slides_latest.pptx" download="talk_slides_latest.pptx" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Notes</a>
                            <a href="https://youtu.be/T7uY9cNu5Kw" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Recording Link</a>
                            <a href="https://arxiv.org/abs/2303.11249" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Reading</a>
                        </li>
                    </ul>
                    <h4 style="margin-top: 20px;">Nov 21, 2023</h4>
                    <ul style="padding-left: 0;">
                        <li style="list-style-type: none;">
                            <b>
                                <a style="color: #2c3e50;"> Title: High-dimensional density estimation with tensorizing flow </a> 
                            </b>
                            <br> Presenter: Yinuo Ren 
                            <br>
                            <!-- <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkBio" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Speaker Bio
                            </a>
                            <div class="collapse" id="newTalkBio">
                                <div class="card card-body" style="margin-top: 10px;">
                                </div>
                            </div> -->
                            <!-- <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkAbstract" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Abstract
                            </a>
                            <div class="collapse" id="newTalkAbstract">
                                <div class="card card-body" style="margin-top: 10px;">
                                </div>
                            </div> -->
                            <a href="notes/slides.pdf" download="slides.pdf" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Notes</a>
                            <a href="https://youtu.be/qVW1_DnQXKI" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Recording Link</a>
                            <a href="https://arxiv.org/abs/2212.00759" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Reading</a>
                        </li>
                    </ul>
                    <h4 style="margin-top: 20px;">Nov 28, 2023</h4>
                    <ul style="padding-left: 0;">
                        <li style="list-style-type: none;">
                            <b>
                                <a style="color: #2c3e50;"> Title: AI and TN -  a love affair </a> 
                            </b>
                            <br> Presenters: Bram Vanhecke 
                            <br>
                            <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkBio" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Speaker Bio
                            </a>
                            <div class="collapse" id="newTalkBio">
                                <div class="card card-body" style="margin-top: 10px;">
                                I studied at KU Leuven where I made one publication on supergravity with A. Van Proeyen. Then did a PhD in the group of Frank Verstraete working on tensor networks, specifically PEPS methods, criticality and
                                frustrated systems. Now I'm doing a post-doc UniWien in the group of Norbert Schuch. Current work continues in tensor networks, but branching out into some machine learning applications with Samuel Wauthier and
                                continuous tensor networks (unpublished).
                                </div>
                            </div> 
                            <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkAbstract" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Abstract
                            </a>
                            <div class="collapse" id="newTalkAbstract">
                                <div class="card card-body" style="margin-top: 10px;">
                                Machine learning and tensor networks have grown closer these past few years as they both learn and borrow from one another. We will discuss one project where tensor networks are used to construct a generative
                                model for active inference planning (a theory in neuroscience that models human learning and cognition), hence using tensor networks to do human-inspired machine learning. And also another project where a technique developed for deep learning, automatic differentiation, is applied to a standard tensor network problem: PEPS optimization. The latter focusses on three major issues in applying AD in this new context, and presents efficient solutions.  One of these has also implications for AD users who aren't using it for PEPS.
                                </div>
                            </div> 
                            <a href="notes/presentation_Vienna.pdf" download="presentation_Vienna.pdf" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Notes</a>
                            <a href="https://youtu.be/EaqdAWCO5p8" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Recording Link</a>
                            <a href="https://arxiv.org/abs/2208.08713" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Reading 1</a>
                            <a href="https://arxiv.org/abs/2311.11894" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Reading 2</a>
                        </li>
                    </ul>
                    <h4 style="margin-top: 20px;">Dec 4, 2023</h4>
                    <ul style="padding-left: 0;">
                        <li style="list-style-type: none;">
                            <b>
                                <a style="color: #2c3e50;"> Title: Enhancing Generative Models via Quantum Correlations </a> 
                            </b>
                            <br> Presenter: Eric R. Anschuetz 
                            <br>
                            <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkBio_dec4" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Speaker Bio
                            </a>
                            <div class="collapse" id="newTalkBio_dec4">
                                <div class="card card-body" style="margin-top: 10px;">
Eric is a Sherman Fairchild postdoctoral fellow at Caltech, having recently finished his PhD under Aram Harrow at MIT. His research focuses on studying the performance of quantum machine learning algorithms: when they are useful, when they are feasible, and when they break. Previously, Eric has shown how techniques from random matrix theory and Morse theory can be used to study the loss landscapes of quantum machine learning models. Most recently, he has shown how nonuniversal quantum resources can lead to expressivity advantages over classical generative models using techniques from quantum foundations research.
                                </div>
                            </div> 
                            <a class="btn btn-primary btn-xs" data-toggle="collapse" href="#newTalkAbstract_dec4" role="button" aria-expanded="false" aria-controls="collapseExample" style="margin-top: 10px;">
                                Abstract
                            </a>
                            <div class="collapse" id="newTalkAbstract_dec4">
                                <div class="card card-body" style="margin-top: 10px;">
                                Quantum mechanical systems can produce probability distributions that exhibit quantum correlations which are difficult to capture using classical models. We show theoretically that such quantum correlations provide a powerful resource for generative modeling. In particular, we provide an unconditional proof of separation in expressive power between a class of widely used generative models—known as Bayesian networks—and its minimal quantum extension, which can be expressed as a class of matrix product states. We show that this expressivity enhancement is associated with quantum nonlocality and quantum contextuality. The possibility of quantum enhancement demonstrated in this work not only sheds light on the design of useful quantum machine-learning protocols but also provides inspiration to draw on ideas from quantum foundations to improve purely classical algorithms. We also briefly discuss more recent results demonstrating a similar separation between classical sequence models (including encoder-decoder models such as Transformers) and a class of quantized recurrent neural networks.
                                </div>
                            </div>
                             <a href="notes/Mila_Presentation_20231205.pdf" download="Mila_Presentation_20231205.pdf" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Notes</a>
                             <a href="https://youtu.be/rUbjqU98jJY?\si=qrin1jewP3au3P2C" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Recording Link</a>
                            <a href="https://arxiv.org/abs/2101.08354" class="btn btn-primary btn-xs" style="margin-top: 10px;"> Reading</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</section>

---

