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
        "Organizer A",
        "Organizer B",
    ],
    image_dir = "organizers") }}


{{ new_block() }}



# Schedule

| Time             | Event            |
| ---------------- | ---------------- |
| 12:00pm - 1:00pm | Introduction and Opening Remarks: Speaker Name A     |
| 1:00pm - 2:00pm  | Speaker A        |
| 2:00pm - 3:00pm  | Speaker B        |
| 3:00pm - 4:00pm  | Discussion Panel |



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