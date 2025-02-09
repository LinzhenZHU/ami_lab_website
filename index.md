---
---

# Ambient Intelligence Lab's Website

**The AmI (Ambient Intelligence) Lab led by [Ke Sun](https://samsonsjarkal.github.io/KeSun/)** is established in CSE of the EECS Department at the University of Michigan, Ann Arbor in Jan 2025.

## AmI Lab Vision

We envision a future where our environments intuitively adapt in real-time to augment human abilities through **Ambient Intelligence (AmI)**. In this future, devices, sensors, and processors are seamlessly embedded into everyday objects and spaces, creating intelligent systems that proactively adjust to individual needs. This vision guides AmI Lab @ UMich CSE on developing **intelligent, cost-effective, deployable, human-centric, and trustworthy Mobile, Wearable, and IoT (MWIoT) systems**.

Our specific aims include harnessing innovative sensing modalities—ranging from traditional human sensory sensors like microphones and cameras to extended sensory sensors such as ultrasound, radio/frequency signals, electromagnetic waves, biopotentials, motion sensors, etc. 

Our goals are to: i). **Enable novel applications** through advanced sensing technologies; ii). **Advance computational sensing techniques** to enhance the capabilities and performance of MWIoT systems; iii).**Address system bottlenecks** in MWIoT ecosystems, ensuring efficiency and reliability.

---

## AmI Lab Mission

Specifically, we co-design end-to-end mobile, wearable, and IoT systems to achieve the following requirements from different layers. 

- Applications Layers: Enable critical or novel applications using MWIoT systems, including i). Human-Computer Interaction (HCI); ii). Mobile, Household, and Industrial Robotics; iii). Mobile Health iv): Environmental Sensing; v). Autonomous Driving and UVA; vi). Multimedia for new scenarios, like 6G, Metaverse, etc.
- Data Processing Layers: Design the sensor computational models for MWIoT systems to make them i). accurate; ii). intelligent; iii). robust; iv) personalized;
- Systems Layers: Design the MWIoT systems to achieve (i) energy efficiency; (ii) computational efficiency; (iii) communication efficiency; (iv) trustworthiness; and (v) privacy preservation.
- Sensing Layers: Innovate low-cost solutions with minimal or no hardware modifications to maximize the potential of ubiquitous sensors on existing MWIoT systems. Except for traditional sensors like audio and vision, we specifically focus on ubiquitous MWIoT sensors, like radio frequency, ultrasound, electromagnetic, capacitive sensors, biopotential signals, and olfactory sensors, etc.

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
