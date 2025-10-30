---
# Display name
title: 徐婧

# Name pronunciation (optional)
name_pronunciation: Jing Xu

# Full name (for SEO)
first_name: Jing
last_name: Xu

# Pronouns (optional)
pronouns: she/her

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Second-year M.S. student in Electrical and Computer Engineering at the University of Rochester. I am actively seeking PhD positions.

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Hajim School of Engineering & Applied Sciences
    url: https://www.hajim.rochester.edu/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:jxu101@ur.rochester.edu'
    label: E-mail Me
  - icon: brands/x
    url: https://x.com/lune_ang3?s=21
  - icon: brands/github
    url: https://github.com/ginforu
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/jing-xu-62287b390/
  # - icon: brands/instagram
  #   url: https://www.instagram.com/

education:
  - area: MS in Electrical and computer engineering
    institution: University of Rochester
    date_start: 2024-08-01
    date_end: 
    summary: |
      GPA: 3.95/4.0

      Courses included:
      - Intro to Computational Neuroscience,Advanced Computational Neuroscience
      - Advanced Topics in Cognitive Neuroscience
      - Natural Language Processing
    # button:
    #   text: 'Read Thesis'
    #   url: 'https://example.com'
  - area: BS in Software engineering 
    institution: Northeastern University(China）
    date_start: 2020-09-01
    date_end: 2024-07-31
    summary: |
      Courses included:
      - Artificial Intelligence Technology
      - Practice for Software Product Construction
      - Operating Systems
work:
  - position: Research Assistant (Supervised by Dr. Laurel Carney)
    company_name: Carney Lab
    company_url: https://www.urmc.rochester.edu/labs/carney
    company_logo: ''
    date_start: 2025-05-01
    date_end: 
    summary: |2-
      - Developed receptive-field encoding models to predict extracellular IC single-neuron responses with frequency
      and amplitude modulation tuning features (MATLAB).
      - Implemented MLP, CNN, and CKAN models to predict neural activity from single-trial data, enhancing model
      robustness over traditional trial-averaged approaches.
      - Analyzing acoustic stimuli signals with signal processing techniques including cochlear filterbanks etc.
  
  - position: Research Assistant (Supervised by Dr. Christopher Kanan)
    company_name: kLab 
    company_url: https://chriskanan.com/klab/
    company_logo: ''
    date_start: 2025-05-01
    date_end: 2025-09-01
    summary: |
      - Conducted multidimensional quantitative analysis of color representations in SOTA computer vision models and
      the fMRI responses of human visual cortex (Python).
      - Performed Representational Similarity Analysis (RSA) to assess the alignment of computer vision model
      representations with human perception, evaluating alignment using Pearson’s r and Spearman’s ρ and
      contextualizing the results with a leave-one-subject-out noise ceiling analysis.

  - position: Summer school research
    company_name: Neuromatch
    company_url: ''
    company_logo: ''
    date_start: 2024-08-01
    date_end: 2024-08-31
    summary: |
      - Analyzed large-scale calcium imaging data from
      10,000 neurons in the mouse visual cortex to characterize
      functionally coherent neuronal ensembles engaged during stimulus events.
      - Applied Non-negative Matrix Factorization to reduce high-dimensional neural activity into 10 low-dimensional“neural factors,” identifying functionally coordinated neuronal assemblies that are spatially clustered within the cortical architecture.
      - Built an XGBoost model using neural factor activity to predict pupil size dynamics, achieving 90.3% accuracy on
      test data.

  - position: Research Assistant(Supervised by Dr. Furao Sheng)
    company_name: State Key Laboratory for Novel Software Technology, Nanjing University
    company_url: ''
    company_logo: ''
    date_start: 2024-08-01
    date_end: 2024-08-31
    summary: |
      - Developed a framework to convert Artificial Neural Networks (ANNs) to Spiking Neural Networks (SNNs),
      translating continuous neural signals into sparse, spike-based computation for reduced energy consumption
      (Python).
      - Investigated brain-inspired mechanisms like Surrogate Gradient Learning and Temporal Encoding to enhance the efficiency and accuracy of converted SNNs for potential on-chip applications.
  
  - position: Software Engineer
    company_name: Shenzhen Kingdom Technology Co., Ltd– 
    company_url: ''
    company_logo: ''
    date_start: 2024-08-01
    date_end: 2024-08-31
    summary: |
      - Developed a framework to convert Artificial Neural Networks (ANNs) to Spiking Neural Networks (SNNs),
      translating continuous neural signals into sparse, spike-based computation for reduced energy consumption
      (Python).
      - Investigated brain-inspired mechanisms like Surrogate Gradient Learning and Temporal Encoding to enhance the efficiency and accuracy of converted SNNs for potential on-chip applications.

  - position: Research Assistant(Supervised by Dr. Furao Sheng)
    company_name: State Key Laboratory for Novel Software Technology, Nanjing University
    company_url: ''
    company_logo: ''
    date_start: 2024-08-01
    date_end: 2024-08-31
    summary: |
      - Developed a framework to convert Artificial Neural Networks (ANNs) to Spiking Neural Networks (SNNs),
      translating continuous neural signals into sparse, spike-based computation for reduced energy consumption
      (Python).
      - Investigated brain-inspired mechanisms like Surrogate Gradient Learning and Temporal Encoding to enhance the efficiency and accuracy of converted SNNs for potential on-chip applications.
  
  - position: Hierarchical Transformers for Multi-Document Summarization
    company_name:  course project for Natural Language Processing(A)
    company_url: ''
    company_logo: ''
    date_start: 2025-05-01
    date_end: 2025-05-31
    summary: |
      - Designed and evaluated a hierarchical Transformer model to address cross-document structure in
      multi-document summarization, overcoming the redundancy and lack of global coherence typical of
      flat-sequence processing.
      - Built a two-stage framework, replacing an LSTM ranker with a BERT-based encoder to jointly encode
      title-paragraph pairs and improve salient paragraph extraction.
      - Developed global Transformer layers with multi-head pooling and inter-paragraph attention to enable effective
      context fusion across documents.
      - Achieved a ROUGE-1 score of 11.11 using the BERT encoder, significantly outperforming the LSTM baseline and
      demonstrating improved content coverage and relevance.

  - position: Backpropagation vs. Prospective Configuration in Neural Networks 
    company_name: course project for Advanced ComputationalNeuroscience(A)
    company_url: ''
    company_logo: ''
    date_start: 2025-05-01
    date_end: 2025-05-31
    summary: |
      - Evaluated the performance of Backpropagation in CNNs versus Prospective Configuration in Predictive Coding
      Networks (PCNs) on CIFAR-10 image classification and target alignment tasks.
      - Developed and trained CNN and PCN models, achieving 64.96% accuracy with CNNs (BP) on CIFAR-10 and
      demonstrating lower test error for PCNs under specific conditions.

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: Python
        description: ''
        percent: 90
        icon: devicon/python
      - name: Matlab
        description: ''
        percent: 80
        icon: devicon/ Matlab
      - name: Java/JavaScript/SQL
        description: ''
        percent: 80
        icon: devicon/Java
      - name: C/C++
        description: ''
        percent: 90
        icon: devicon/C
      - name: Swift
        description: ''
        percent: 70
        icon: devicon/Swift
      - name: Amazon Web Services (AWS), Docker, Git, SVN
        description: ''
        percent: 70
        icon: devicon/Docker
  - name: Hobbies
    color: 'rgba(238, 172, 2, 1)'
    color_border: '#f0bf23'
    items:
      - name: Piano
        description: ''
        percent: 50
        icon: piano
      - name: Cats
        description: ''
        percent: 100
        icon: cat
      - name: Photography
        description: ''
        percent: 80
        icon: camera

languages:
  - name: English
    percent: 90
  - name: Chinese
    percent: 100

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
# awards:
#   - title: Neural Networks and Deep Learning
#     url: https://www.coursera.org/learn/neural-networks-deep-learning
#     date: '2023-11-25'
#     awarder: Coursera
#     icon: brands/coursera
#     summary: |
#       I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.
#   - title: Blockchain Fundamentals
#     url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#     date: '2023-07-01'
#     awarder: edX
#     icon: brands/edx
#     summary: |
#       Learned:
#       - Synthesize your own blockchain solutions
#       - Gain an in-depth understanding of the specific mechanics of Bitcoin
#       - Understand Bitcoin’s real-life applications and learn how to attack and destroy Bitcoin, Ethereum, smart contracts and Dapps, and alternatives to Bitcoin’s Proof-of-Work consensus algorithm
#   - title: 'Object-Oriented Programming in R'
#     url: https://www.datacamp.com/courses/object-oriented-programming-with-s3-and-r6-in-r
#     certificate_url: https://www.datacamp.com
#     date: '2023-01-21'
#     awarder: datacamp
#     icon: brands/datacamp
#     summary: |
#       Object-oriented programming (OOP) lets you specify relationships between functions and the objects that they can act on, helping you manage complexity in your code. This is an intermediate level course, providing an introduction to OOP, using the S3 and R6 systems. S3 is a great day-to-day R programming tool that simplifies some of the functions that you write. R6 is especially useful for industry-specific analyses, working with web APIs, and building GUIs.
---

University of Rochester ECE Master’s student seeking a research (PhD) position in computational neuroscience,
with a focused research interest in cognitive network neuroscience . With an interdisciplinary background
combining computer engineering and neuroscience research, my expertise lies in applying machine learning
models to diverse data modalities, including fMRI, electrophysiology, acoustic signals, and images. I am eager to
apply my experience in computational modeling to investigate how task-driven cognitive computations emerge
from underlying brain network mechanisms, and how these causal principles can inform the development of
more empirically-constrained and generalizable artificial intelligence.
