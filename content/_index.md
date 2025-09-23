+++
title = "Reasoning Representations for Robotics ICRA 2026 Workshop"
+++

# Abstract

A central challenge in robotics is distilling complex sensor data into actionable representations for
decision-making and motion planning. However, planners operating at different levels of abstraction
demand representations with distinct and contradictory properties. For instance, a high-level
decision-making planner requires a representation that encodes the high-level semantics and relationships
between scene elements. On the other hand, a low-level trajectory optimizer requires a
high-fidelity representation of occupancy to guarantee safe behavior. When robots operate in unknown
or dynamic environments, the representation must support real-time construction from a
stream of sensor data.

Recently, several communities have made significant progress on developing representations that
have subsets of these properties. These efforts include radiance field models from the 3D vision community,
rapid advances in vision-language models for semantic understanding, and continued developments
in model-based RL, scene graphs, and neuro-symbolic AI. Despite each field’s progress,
enabling robots to be safe and capable agents across diverse task specifications will require collaboration
across these academic disciplines.

Through invited and selected spotlight talks as well as a panel discussion, the Representations
for Robotic Reasoning workshop will address several key topics, including (1) designing representations
that enable intelligent, efficient, and safe motion planning, (2) evaluating trade-offs among
approaches such as learned world models, radiance fields, and scene graphs, (3) adapting representations
to dynamic and uncertain environments, and (4) fostering cross-disciplinary collaborations.
By bringing together these perspectives, the Representations for Robotic Reasoning workshop aims
to encourage discussion and collaboration on the development of perceptual representations that
support robust and safe robot behavior.

## Things

* enumerate
    * inner enumerate



{{ new_block() }}



# List of Speakers

{{ grid(
    text = [
        ["Felix Heide","Assistant Professor at Princeton University, Head of AI at Torc Robotics"], 
        ["Stefan Leutenegger","Associate Professor at ETH Zürich"],
        ["Michael Milford","Professor at Queensland University of Technology"],
        ["Yunzhu Li","Assistant Professor at Columbia University"],
        ["Alex Millane","Industry Researcher at Nvidia"],
    ],
    urls = [
        "https://www.cs.princeton.edu/~fheide/",
        "https://mavt.ethz.ch/de/personen/person-detail.MTEyOTE0.TGlzdC81NTksLTE3MDY5NzgwMTc=.html",
        "https://www.qut.edu.au/about/our-people/academic-profiles/michael.milford",
        "https://www.engineering.columbia.edu/faculty-staff/directory/yunzhu-li",
        "https://alexmillane.github.io/",
    ],
    images = [
        "heide.webp",
        "leutenegger.jpg",
        "milford.jpg",
        "li.jpg",
        "millane.png",
    ],
    narrow = true) }}



{{ new_block() }}



# List of Organizers

{{ grid(
    text = [
        ["Seth Isaacson","PhD Candidate at the University of Michigan"], 
        ["Ram Vasudevan","Associate Professor at the University of Michigan"],
        ["Georgia Chalvatzaki","Full Professor at the Technical University of Darmstadt"],
        ["Helen Olynikova","Senior Researcher at ETH Z¨urich"],
        ["Rudolf Lioutikov","TT Professor at Karlsruher Institute of Technology"],
        ["Shreyas Kousik","Assistant Professor at Georgia Institute of Technology"], 
        ["Katherine Skinner","Assistant Professor at the University of Michigan"],
        ["Dennis Anthony","PhD Student at Georgia Institute of Technology"],
        ["Paul Mattes","PhD Student at Karlsruher Institute of Technology"],
        ["Max Siebenborn","PhD Student at the Technical University of Darmstadt"],
    ],
    image_dir = "organizers") }}


{{ new_block() }}



# Schedule

| Time        | Event                    |
|-------------|---------------------------|
| 09:00–09:10 | Opening Remarks           |
| 09:10–09:35 | Stefan Leutenegger        |
| 09:35–10:00 | Michael Milford           |
| 10:00–10:25 | Angjoo Kanazawa (tentative) |
| 10:25–10:40 | Coffee Break              |
| 10:40–11:40 | Spotlight Presentations   |
| 11:40–12:30 | Poster Session            |
| Until 13:00 | Lunch Break               |
| 13:00–13:25 | Alex Millane              |
| 13:25–13:50 | Luca Carlone (tentative)  |
| 13:50–14:15 | Felix Heide               |
| 14:15–14:40 | David Hsu (tentative)     |
| 14:40–14:55 | Coffee Break              |
| 14:55–15:20 | Victor Reijgwart (tentative) |
| 15:20–15:45 | Yunzhu Li                 |
| 15:45–16:00 | Coffee Break              |
| 16:00–16:45 | Interactive Debate        |



{{ new_block() }}



# Accepted Papers

{{ table(
    data = "papers.csv", 
    columns = ["Title","Authors"],
    button_names = ["paper","poster"], 
    button_data_columns = [3,4], 
    button_output_columns = [1,1]) }}



{{ new_block() }}



# Upcoming Seminar

{{ highlights(section_name = "seminars") }}



{{ new_block() }}



# List of Seminars

{{ list(section_name = "seminars") }}

{{ button(name = "All Seminars", url = "seminars")}}