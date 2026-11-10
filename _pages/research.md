---
title: Research
layout: single
permalink: /research/
excerpt: "Diving into Sea Ice research"
classes: wide


header:
  overlay_image: ./assets/images/photo_research/for_research_header_compressed.gif
 # actions:
  #  - label: "McGill Sea Ice Group"
   #   url: "/"
  excerpt: "Diving into Sea Ice research"

ALL:
  - image_path: ./assets/images/placeholder_image.png
    alt: "Sea ice Dynamics"
    image_caption: "Image for dynamics, perhaps a sea ice picture from an I/B"
    title: "Sea Ice Dynamics"
    excerpt: "Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent per conubia nostra inceptos himenaeos. \n \n Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent per conubia nostra inceptos himenaeos."
    url: ./research/(thermo)dynamics/
    btn_label: "Read More"
    btn_class: "btn--inverse"

    
  - image_path: ./assets/images/placeholder_image.png
    image_caption: "Maybe a pan-Arctic Model output? or RGPS? "
    alt: ""
    title: "Sea Ice Rheology"
    excerpt: "Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu. "
    url: ./research/rheology/
    btn_label: "Read More"
    btn_class: "btn--inverse"
    
  - image_path: ./assets/images/placeholder_image.png
    title: 'Arctic Climate Change, Advocacy and Policy'
    image_caption: "Last Ice Area? Other stuff?"
    excerpt: "Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas."
    url: ./research/arctic_climate_change_and_policy/
    btn_label: "Read More"
    btn_class: "btn--inverse"

dynamics:
  - image_path: ./assets/images/placeholder_image.png
    alt: "Sea ice Dynamics"
    image_caption: "Image for dynamics, perhaps a sea ice picture from an I/B"
    title: "Sea Ice Dynamics"
  - excerpt: "Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent per conubia nostra inceptos himenaeos. \n \n Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent per conubia nostra inceptos himenaeos."
    url: ./(thermo)dynamics/
    btn_label: "Read More"
    btn_class: "btn--inverse"

rheology:
  - image_path: ./assets/images/placeholder_image.png
    image_caption: "Maybe a pan-Arctic Model output? or RGPS? "
    alt: ""
    title: "Sea Ice Rheology"
  - excerpt: "Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu. "
    url: ./rheology/
    btn_label: "Read More"
    btn_class: "btn--inverse"

ACC:  
  - title: 'Arctic Climate Change, Advocacy and Policy'
  - image_path: ./assets/images/placeholder_image.png
    image_caption: "Last Ice Area? Other stuff?"
  - excerpt: "Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas."
    url: ./arctic_climate_change_and_policy/
    btn_label: "Read More"
    btn_class: "btn--inverse"

ACC_gallery:
  - url: ./assets/images/placeholder_image.png # to click on the image and make it open big with its caption
    image_path:  ./assets/images/placeholder_image.png
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: ./assets/images/placeholder_image.png 
    image_path:  ./assets/images/placeholder_image.png
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - url: ./assets/images/placeholder_image.png 
    image_path:  ./assets/images/placeholder_image.png
    alt: "placeholder image 3"
    title: "Image 3 title caption"


sidebar:
  title: 'Research'
  nav: "research_nav"
---
This section will require most writing, since we all do different research. I made some preliminary pages, but we will need to rediscuss which to keep/create.


Some stylistic choices to make, we can put our three main research focus either
# TOGETHER

{% include feature_row id="ALL"%}{: .align-left}

# OR SEPERATED

# Sea Ice Dynamics

{% include figure popup=true image_path="./assets/images/placeholder_image.png" caption="Image for dynamics, perhaps a sea ice picture from an I/B" %}

Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent per conubia nostra inceptos himenaeos. \n \n Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent per conubia nostra inceptos himenaeos.
[Read More](./(thermo)dynamics/){: .btn .btn--primary }
# Sea Ice Rheology 

{% include figure popup=true image_path="./assets/images/placeholder_image.png" caption="Maybe a pan-Arctic Model output? or RGPS? "%}

J'adore les mots; bla bla bla.J'adore les mots; bla bla bla.J'adore les mots; bla bla bla.J'adore les mots; bla bla bla.J'adore les mots; bla bla bla.J'adore les mots; bla bla bla.J'adore les mots; bla bla bla.J'adore les mots; bla bla bla.J'adore les mots; bla bla bla. J'adore les mots; bla bla bla. J'adore les mots; bla bla bla. 
- une liste
- une liste 

Plus de bla bla ou des photos etc. 

Signature
{: .text-right}


<p align="right"> SIGNATURE (je joue avec le html)</p>
de retour centré?

[Read More]( ./rheology/){: .btn .btn--inverse }

# Arctic Climate Change, Policy, and Advocacy
{% include gallery id="ACC_gallery" popup="true" layout="third" caption="To show if we want to have many pictures next to each other it is **possible**" %}
Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent per conubia nostra inceptos himenaeos. \n \n Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu.
[Read More](./arctic_climate_change_and_policy/){: .btn .btn--light-outline}