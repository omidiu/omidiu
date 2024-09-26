# Hi there 👋, I'm Omid Saghatchian!

## 🧑‍🔬 About Me
I am an ML Researcher and a passionate learner. Here are some highlights of my academic and professional journey:

- 🎓 **Current Pursuits**:  
  I am currently pursuing a master’s degree in Data Mining at Shahid Beheshti University with a GPA of **19.65**, holding the first rank in my major.

- 🧮 **Educational Background**:  
  I hold a bachelor’s degree in Mathematics and Applications from Amirkabir University of Technology.

- 💻 **Professional Experience**:  
  I have 2.5 years of experience as a software engineer. In my last year, I worked at [Yektanet](https://www.linkedin.com/company/yektanet/?originalSubdomain=ir), the largest and most advanced online advertising network in Iran.

- 🧑‍🏫 **Teaching Experience**:  
  I have served as a lead teaching assistant at Amirkabir University of Technology for several courses, including:
  - 📊 **Data Mining**, instructed by [Dr. Fatemeh Shakeri](https://scholar.google.com/citations?user=35zq7c4AAAAJ&hl=en)
  - 💻 **Computational Data Mining**, instructed by [Dr. Fatemeh Shakeri](https://scholar.google.com/citations?user=35zq7c4AAAAJ&hl=en)
  - 🤖 **Deep Learning**, instructed by [Dr. Fatemeh Shakeri](https://scholar.google.com/citations?user=35zq7c4AAAAJ&hl=en)
  - 📐 **Linear Algebra**, instructed by [Dr. Behzad Najafi](https://scholar.google.com/citations?user=DqRal7EAAAAJ&hl=en)
  - 🖥️ **User Interface Design**, instructed by [Dr. Sajad Shirali Shahreza](https://sajad.shirali.ir/)

- 🔬 **Research Involvement**:  
  I have been involved in various research projects, which are detailed below.

## 🚀 Projects

1. **Adaptive Token Merging Strategies**:  
   Investigating methods to optimize token merging processes for faster and more efficient model inference. Our research builds upon the existing method described in the paper [Token Merging for Fast Stable Diffusion](https://arxiv.org/abs/2303.17604).

2. **Driving Behavior Monitoring Framework**:  
   Creating a comprehensive framework for analyzing driving patterns using sensor time series data to improve driver safety and provide real-time insights. Our method is inspired by [wav2vec 2.0](https://arxiv.org/abs/2006.11477).

3. **Mini Torch Library**:  
   A friend and I created a framework demonstrating how PyTorch operates behind the scenes. I plan to create a tutorial for this as well. It’s a generalized version of the existing implementation from Andrew Karpathy’s project called [Micrograd](https://github.com/karpathy/micrograd), but there are significant differences:

   3.1 **Generalization Beyond Scalars**:  
   Our implementation is not limited to scalars; we have written it in a generalized form that supports scalars, vectors, matrices, and tensors. This is significant because it requires us to generalize the concept of derivatives. In this generalized context, the derivative is analogous to a linear transformation from an infinitesimal change in `dx` to an infinitesimal change in `dy`. For more detailed information, you can refer to this [MIT tutorial](https://ocw.mit.edu/courses/18-s096-matrix-calculus-for-machine-learning-and-beyond-january-iap-2023/video_galleries/lecture-videos/).

   3.2 **Module Class Implementation**:  
   We created a `Module` class similar to the [`torch.nn.Module`](https://pytorch.org/docs/stable/generated/torch.nn.Module.html) class in PyTorch, which all neural networks should inherit. This class automatically provides capabilities such as the `parameters()` method, so each class does not need to implement it individually.

   3.3 **Optimizer Abstraction**:  
   We introduced a separate `Optimizer` entity, similar to PyTorch, where each optimizer must implement two main methods: `zero_grad()` and `step()`.

   3.4 **Neural Network Components**:  
   We created a basic `nn` module to contain all the components a neural network could have. Currently, we have implemented only the `Linear` function.

## ✍️ Medium Articles

1. **[Decision Tree Implementation from Scratch & Visualization](https://medium.com/@omidsaghatchian/decision-tree-implementation-from-scratch-visualization-5eb0bbf427c2)**  
   In this article, I walk through a detailed implementation of the Decision Tree algorithm from scratch with visualization.


## 🌍 Connect with Me
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/omidiu)&nbsp;
[![Email](https://img.shields.io/badge/-Email-c14438?style=flat&logo=Gmail&logoColor=white)](mailto:omidsaghatchian@gmail.com)&nbsp;
