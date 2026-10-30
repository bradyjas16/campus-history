---
# Change these five lines as soon as you copy this starter.
title: UNM Duck Pond 
author: Jason Brady
category: Landscape                  # change to a category from the student guide
header-image: unm duck pond.jpg   # the filename of your own image
header-caption: New Mexico Digital Archive

# Fill these in later, once your research is under way.
card-description: Replace this with two sentences that summarize the story your essay tells and why it matters.
start:                                   # the year your story begins, shown on the map

# Leave this line as it is.
layout: essay
---



On a busy day at the University of New Mexico, students hurry between classes, conversations echo across campus, and schedules rarely slow down. Yet in the middle of all this activity sits a peaceful oasis where ducks glide across the water, turtles bask in the sun, and people gather to relax. Why does the UNM Duck Pond attract so much attention from students, visitors, and locals alike? More than just a scenic spot, the Duck Pond serves as a place for community, reflection, and connection with nature, making it one of the most beloved landmarks on campus.



## Main Story

The history of the UNM Duck Pond begins in the mid-1970s, when the University of New Mexico started a landscaping project to create a central space where students and faculty could relax and enjoy the outdoors. The pond was designed by renowned landscape architect Garrett Eckbo and included features such as a waterfall, footbridge, and grassy areas for gathering.

Construction of the Duck Pond required major changes to the area. An existing parking lot and several nearby buildings were removed to make room for the new space. Although university planners believed the pond would improve campus life, many students, professors, and community members initially criticized the project, arguing that a large water feature did not fit New Mexico’s desert environment.

When the pond was completed in 1975 and filled with water in 1976, opinions began to change. Students started calling it the “Duck Pond,” a name that quickly replaced its original titles such as “University Pond.” Ducks, fish, and turtles soon made the pond their home, helping transform it into a lively and welcoming part of campus.

Over the decades, the Duck Pond grew into one of UNM’s most recognizable landmarks. Trees and vegetation matured around the water, creating a peaceful setting where students could study, meet friends, or take a break between classes. What was once controversial became one of the most beloved gathering places on campus.

In recent years, the university has invested in preserving the Duck Pond for future generations. A major revitalization project completed in 2025 updated aging infrastructure, improved water quality, and increased accessibility while maintaining the pond’s historic appearance. Nearly fifty years after its creation, the Duck Pond continues to be a central part of the UNM experience.

<!-- Full-width figure. This is the default for any landscape photo wider than about 700px.
     image-path is just the filename: upload your images into this essay's folder,
     next to index.md. -->

{% include images/figure.html
  class="img-center"
  width="100%"
  caption="Replace this caption. Say why the image matters, not just what it shows, then cite where you found it: [Center for Southwest Research](https://econtent.unm.edu/), collection and box number."
  image-path="sample-archive-photo.jpg"
%}

Every image needs a caption, including this one. A caption should explain what the reader should notice and where the image came from. Captions accept Markdown, so use `[source](https://example.com/)` to link to a digital collection whenever the image has an online home.

## What Changed

The UNM Duck Pond has changed dramatically since it was first proposed in the 1970s. Before the pond existed, the area was mostly used for parking and did not serve as a major gathering place for students. University leaders envisioned a landscaped space that would improve campus life and provide a central location where people could relax, study, and socialize. However, many students and community members questioned the project at the time, arguing that a large pond seemed out of place in New Mexico's dry climate.

As the years passed, opinions shifted. What was once a controversial construction project became one of the most popular and recognizable places on campus. Students began using the pond as a meeting spot, a study area, and a place to attend campus events. The ducks, turtles, fish, and surrounding vegetation helped create a unique environment that stood out from the rest of the university.

The evolution of the Duck Pond reflects a larger pattern in UNM's history. As enrollment grew and campus life became a greater focus of university planning, more attention was given to creating spaces that encouraged community and student engagement. The pond became more than a decorative feature; it became part of the university's identity and public memory. Generations of students have taken graduation photos there, met friends there, and associated the space with their time at UNM.

In recent years, university officials have worked to preserve and improve the Duck Pond through renovation and maintenance projects. These efforts show how the pond has shifted from a debated campus project to a valued landmark worth protecting. Its continued popularity demonstrates how spaces can gain new meaning over time and become important symbols of student life and campus culture.

<!-- Carousel: use when you have three or more images that belong together but do not
     each need their own paragraph. Images are split on commas, captions on the | character.
     Carousel captions are plain text: Markdown links will NOT work here, so write out
     the collection name and box number instead of linking. -->

{% assign images =
"sample-archive-photo.jpg,
sample-second-photo.jpg,
sample-primary-source.jpg" | split: ','
%}

{% assign headers =
"Replace with a short slide title,
Replace with a short slide title,
Replace with a short slide title" | split: ','
%}

{% assign captions =
"Replace this caption. Explain what this slide shows and why it matters. Center for Southwest Research, collection name, box number.|
Replace this caption. Every slide needs one. Center for Southwest Research, collection name, box number.|
Replace this caption. Plain text only in carousels, so spell out the source instead of linking. Center for Southwest Research, collection name, box number." | split: '|'
%}

{% include images/carousel.html
  images=images
  headers=headers
  captions=captions
%}

Delete the carousel if you do not have a set of images that works this way. Three related photographs, a series of floor plans, or a run of newspaper clippings are all good candidates. Two images that need to be compared directly are usually better as a pair than as a carousel.

## Evidence

unm-duck-pond-construction.jpg
<!-- Portrait documents are the exception to the full-width rule. A tall scan at 100%
     is over 1200px tall and swallows the screen, so center it and leave it near 55%.
     Keep it centered, not floated. -->

{% include images/figure.html
  class="img-center"
  width="55%"
  caption="Replace this caption. Tell readers what to notice in the document and why it changes how they should understand your topic. Cite the collection, box, and folder."
  image-path="sample-primary-source.jpg"
%}


## Why This History Matters

Today, most students see the UNM Duck Pond as a peaceful place to study, meet friends, or take a break between classes. Yet its history reveals that the pond is much more than a scenic campus landmark. It represents decades of planning, debate, and investment in student life, showing how physical spaces can shape the university experience.

The pond also serves as a reminder of how campus memories are created. Thousands of students have walked its paths, fed the ducks, taken graduation photographs, and shared stories connected to the space. These everyday experiences have transformed the Duck Pond from a once-controversial project into a symbol of UNM itself.

At the same time, gaps remain in the historical record. Official plans and university documents explain why administrators wanted to build the pond, but they do not always capture how students felt about it or how different generations have used the space. Those memories continue to change as new students add their own experiences to its history.

As UNM grows and evolves, the Duck Pond remains a living part of campus life rather than a relic of the past. Looking at the pond today, readers can see not only a body of water surrounded by trees and wildlife, but also a place where history, community, and memory continue to shape one another. 

{% capture bibliography %}
- Replace this with your first source. Include enough detail that someone else could find it: collection name, box, and folder for archival material.
- Replace this with your second source.
- Replace this with your third source.
{% endcapture %}

{% include typography/bibliography.html
  title="Bibliography"
  content=bibliography
%}
