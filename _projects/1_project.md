---
layout: page
title: freewill EXPERIMENT
description: Liberate us from the clutches of cloud dependence and place the power back into our own hands.
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

Transcends the realm of philosophical musings and ventures into the heart of technology. It stands as an embodiment of an innovative fusion of on-premises AI Research and Learning Lab, readymade hardware setups, and preconfigured software elements. This harmonious blend promises to liberate us from the clutches of cloud dependence and place the power back into our own hands.

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Have you ever imagined that an LLM AI agent based Lab brings "Research, learning and pre-configured hardware" in one compact package? If so, our innovative offering, the freewill.EXPERIMENT, delivers this vision by merging these essential components with Lab's powerful tools into one solution.
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    By combining an on-premises research environment with conversational LLM AI agent and a pre-configured hardware machine from ActiVating.AI, you can
Determine your aspirations
    This image can also have a caption. It's like magic.
</div>

Determine your aspirations

Ready to embark on a new research and learning goal, this all-in-one lab is here to help you begin an immersive journey focused on essential data science and LLM AI topics. Your journey commences by exploring the integration of various technologies and tools:

<li>Integrating these technologies: Linux, Docker Containers, Python, FastAPI, PyTorch, Transformers, to build a robust foundation.</li>
<li>Further integrating these tools: LLM AI and RAG, to enhance your capabilities.</li>
<li>Applying LLM AI within SETI's Hypotheses and Neutrino Dataset to investigate potential Extraterrestrial Intelligence.</li>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Set your own goal
    
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

In addition to the comprehensive set of tools for knowledge discovery and pre-installed software components, freewill.EXPERIMENT offers users the ability to set their own research and learning goals through a simple command "/goal is [insert one sentence describing your goal]." This feature allows users to tailor their journey according to their specific interests and objectives, making it an invaluable tool for individuals and organizations focusing on AI research and development.

By enabling users to define their goals, freewill.EXPERIMENT empowers them to explore topics that cater to their unique requirements, strive to create a more engaging and effective research and learning experience. This customization aspect sets freewill.EXPERIMENT apart from other similar platforms and reinforces its value as an innovative on-premises AI research and learning lab.

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}

<div class="caption">
Lab tools
</div>

List of tools for knowledge discovery
<li>Research Finding Generator. Seamlessly generate insightful research findings directly from your conversational data.</li>
<li>Knowledge Expansion Engine. Expand upon current concepts with potentially deeper, related insights derived from the same chat conversation.</li>
<li>Self Validation Statistic Report. Empowers the exploration of ideas and conversational directions through automated statistic generation on True/False hypotheses raised in response to recent discussions. (Accuracy relied upon personal assessment).</li>

<div class="caption">
Pre installed and configured software components
</div>

<li>Components installed and configured to set up this freewill.EXPERIMENT using Large Language Model (LLM), and various essential technologies.</li>

<li>
LLM Components

Instruct-model: This model is trained not only on vast text data but also on instructions, enabling it to generate responses that closely follow the input instructions. This makes the instruct-model better suited for applications requiring stricter adherence to commands or conditions.</li>

<li>
Operating System and GPU Environment Setup

Linux Ubuntu: Ubuntu is a popular and versatile Linux distribution designed for both desktop and server usage. Installing LLM and related packages on Ubuntu aims to provide compatibility and ease of use experience.</li>

<li>
NVIDIA GPU driver: To accelerate machine learning tasks using GPUs, NVIDIA's proprietary driver must be installed on the Ubuntu system. The GPU driver optimizes the interaction between the GPU and the operating system, allowing the efficient use of GPU resources for computationally intensive tasks.</li>

<div class="caption">
Python Libraries for AI/Machine Learning
</div>

<li>
CUDA Toolkits: CUDA Toolkits are collections of libraries and development tools for programming GPUs from NVIDIA. They enable the use of GPU-accelerated computation for machine learning and other demanding tasks, making the inference and deployment of advanced AI models much faster and more efficient.</li>

<li>
Machine Learning and Data Science Tools</li>

<li>
Torch: Torch is an open-source machine learning library inspired by Matlab and Lua. Torch provides a wide range of deep learning algorithms and neural network architectures, as well as tools for research and experimentation in machine learning and artificial intelligence.</li>

<li>
Numpy: Numpy is an open-source library for the Python programming language. It provides support for large, multidimensional arrays and matrices and includes functions for various linear algebra operations and other mathematical computations, making it an essential library for scientific computing and machine learning applications in Python.</li>

<li>
Pandas: Pandas is an open-source data analysis library for Python that provides data structures and tools for data manipulation and analysis. It offers various data structures such as DataFrames and Series, enabling efficient handling and manipulation of large datasets, making it an indispensable tool for data preprocessing and exploration in machine learning applications.</li>

<li>
FastAPI: FastAPI is a modern web framework for building APIs with Python, designed to make web development faster by providing a more intuitive and developer-friendly interface than traditional frameworks like Django or Flask. FastAPI supports asynchronous requests out of the box and integrates seamlessly with other popular Python libraries like Torch and Numpy. This makes it an ideal choice for creating efficient and scalable RESTful APIs for your LLM application.</li>

<div class="caption">
Hardware components
</div>

The following details outline the primay hardware specifications of our chat-based AI research and learning LAB, designed specifically for executing machine learning model inferences. This setup offers a perfect blend of cost-effectiveness and performance.


<li>Graphics Processing Unit (GPU)
NVIDIA RTX 4090: A high-end, consumer-grade graphics card featuring the latest NVIDIA Ampere architecture for superior performance and power efficiency. It comes with a generous 12GB GDDR6 memory to cater to the demands of complex machine learning models.</li>

<li>Central Processing Unit (CPU)
Intel 1xI7-13700BX CORE I7 13700BX LGA1700.</li>

<li>Memory
128GB DDR4: The system comes equipped with a large 128GB DDR4 memory capacity, aiming to provide sufficient memory to support the execution of large machine learning models and their associated data.</li>

<li>Storage
1x 1.92TB M.2 NVMe SSD: This high-performance storage drive offers quick data access and transfer rates to maximize productivity during model inferencing tasks. It can be used as the primary storage drive to host the operating system and other essential applications or data.</li>

<li>Networking
Onboard Networking: The system includes built-in networking capabilities.</li>

<li>Wireless Connectivity(Turned off by default)
Wi-Fi 6: The system includes a built-in Wi-Fi 6 adapter.</li>


<li>Monitor, keyboard and mouse not included</li>

<div>
Experience our product in action before making a purchase. Reach out to us to schedule a session where we'll demonstrate its features and answer questions you may have. Let us help you make an informed decision that our product meets your unique needs.</div>

<div>Estimated delivery date: 20 business days following purchase.</div>

