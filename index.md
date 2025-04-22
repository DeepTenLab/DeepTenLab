---
---

{% include section.html %}

{% capture col1 %}
## {% include icon.html icon="fa-solid fa-newspaper" %}Lab Latest News

  {% assign sorted_news = site.data.news | sort: "date" | reverse %}
    {% for post in sorted_news limit:3 %}
    
  <div class="news-card">
    <div class="news-header">
        <span class="news-title">{{ post.title }}</span>
        <span class="news-date">{% include icon.html icon="fa-regular fa-calendar" %} {{ post.date | date: "%B %d, %Y" }} </span>
    </div>
    <div class="news-description">
        {{ post.description }} 
            {% if post.url %}
            <a href="{{ post.url }}" target="_blank">More...</a>
            {% endif %}
    </div>
  </div>

    {% endfor %}  
  
{%
  include button.html
  link="news"
  text="Read all news"
  icon="fa-solid fa-arrow-right"
  flip=true
  align=left

%}

{% endcapture %}

{% include cols.html col1=col1 %}

# DeepTenLab

Welcome to DeepTenLab, the pioneering research laboratory of the Department of Computer Science at Tarbiat Modares University. Established in 2012, DeepTenLab has been at the forefront of cutting-edge research in advanced machine learning and deep learning, exploring the intersection of artificial intelligence (AI), mathematical modeling, and real-world applications. - 

{%
  include figure.html
  image="images/home/group-photo-team.jpg"
  width="100%"
%}

The lab's name reflects its core focus areas:
-  	Deep: Representing our dedication to advancing AI models such as Generative Adversarial Networks (GANs), Diffusion Models, Vision Transformers, and Graph Neural Networks (GNNs).
-  	Tensor: Emphasizing the lab's innovative use of matrix and tensor mathematics to design and analyze sophisticated AI systems.


{% include section.html %}

## Highlights

{% capture text %}

DeepTenLab focuses on advancing AI through the development of innovative mathematical methods, particularly in matrix and tensor analysis. The lab's research encompasses a wide range of applications, including feature extraction, classification, sparse coding, spectral clustering, and deep learning. It also explores cutting-edge generative models like GANs and diffusion models, along with image-to-image translation techniques such as style transfer and domain adaptation. Additionally, the lab investigates transformer-based architectures for computer vision (Vision Transformers) and applies Graph Neural Networks (GNNs) to analyze complex cognitive data, including fMRI and EEG, with the aim of advancing understanding in neuroscience and brain-computer interfaces.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="https://ars.els-cdn.com/content/image/1-s2.0-S0957417424021687-gr2.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

At DeepTenLab, our ongoing projects span a range of cutting-edge AI and machine learning domains. We are developing advanced matrix and tensor frameworks to enhance AI tasks such as feature extraction, clustering, and deep learning. Our work on generative models focuses on refining GANs and diffusion models for creative applications, while our image-to-image translation projects aim to improve style transfer and domain adaptation. Additionally, we are exploring the potential of Vision Transformers (ViT) for computer vision tasks and applying Graph Neural Networks (GNNs) to analyze cognitive data like fMRI and EEG, with a goal of advancing neuroscience and brain-computer interface technologies.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS47YStvAhpcyybQEOPX4TcsmaZvwuRQXwA0w&s"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

At DeepTenLab, our team is composed of a diverse group of talented researchers and studentys who are passionate about advancing the field of AI. With expertise spanning mathematics, computer science, neuroscience, and engineering, our interdisciplinary team brings a wealth of knowledge and creativity to every project. We foster a collaborative and inclusive environment where ideas can flourish, and each member is encouraged to explore new avenues of research. Together, we are dedicated to pushing the frontiers of AI, developing novel algorithms, and applying them to solve real-world challenges. Our team's commitment to excellence is reflected in the high-impact publications we produce and the innovative projects we pursue across various domains.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/home/highlight-team.jpg"
  link="team"
  title="Our Team"
  text=text
%}

{% include section.html %}

## Achievements and Contributions

DeepTenLab is recognized for its prolific contributions to the AI community:
- High-Impact Publications: The lab consistently publishes groundbreaking research in top-tier AI and machine learning journals and conferences.
- Innovative Projects: We actively pursue AI-driven projects with interdisciplinary applications


{% include section.html %}

## Mission and Vision

Our mission is to push the boundaries of AI research by integrating cutting-edge mathematical frameworks with practical AI challenges. DeepTenLab aspires to bridge theory and application, nurturing innovation that has a lasting impact on both academia and industry.

For over a decade, DeepTenLab has been a hub for fostering excellence, collaboration, and creativity in the field of AI. We invite you to explore our work and join us in shaping the future of artificial intelligence.

