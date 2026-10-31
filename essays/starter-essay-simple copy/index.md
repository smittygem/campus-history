---
# Change these five lines as soon as you copy this starter.
title: The Pit
author: Gemma Gabriella Smith
category: Athletics                 # change to a category from the student guide
header-image: the-pit.png   # the filename of your own image
header-caption: Exterior photograph of The Pit at UNM

# Fill these in later, once your research is under way.
card-description: The history of The Pit and its importance to the University of New Mexico.
start:        1966                           # the year your story begins, shown on the map

# Leave this line as it is.
layout: essay
---

This first paragraph should give readers a quick way into your topic. Start with a scene, a question, a surprising fact, or a problem your essay will explain. You do not need to summarize everything here. Help the reader understand why this campus place, person, organization, object, or event deserves attention.

Keep the above lead paragraph first. Do not put an image, a heading, or any other component above it.

## Historical Background and Construction

The University of New Mexico's iconic basketball arena, commonly known as The Pit, stands as a testament to the university's rich athletic history, architectural innovation, and enduring commitment to community engagement. Since its opening in 1966, The Pit has played a pivotal role in shaping the identity of UNM and fostering a strong sense of pride among students, athletes, and Albuquerque residents. Its evolution from a newly constructed basketball facility into a nationally recognized sporting venue reflects broader developments in collegiate athletics and the cultural significance of university infrastructure.

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

## Historical Background and Construction

The origins of The Pit can be traced to the early 1960s, a transformative period for the University of New Mexico's basketball program. Under the leadership of head coach Bob King, who arrived in 1962, the Lobos experienced a remarkable resurgence. Following several unsuccessful seasons, the team achieved greater competitive success, including a Western Athletic Conference championship in 1964. This success generated increased enthusiasm for basketball and highlighted the limitations of Johnson Gym, the university's previous basketball venue.

In response to growing demand, UNM constructed University Arena, which officially opened on December 1, 1966. The facility initially accommodated approximately 14,831 spectators and reportedly cost $1.4 million to construct. These developments represented a significant milestone in UNM's efforts to establish a more prominent presence within collegiate athletics.

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

## Architectural Innovation and Cultural Significance

One of The Pit's most remarkable characteristics is its distinctive underground architectural design. Designed by architect Joe Boehning, the basketball court was situated approximately 37 feet below ground level, creating an unconventional yet highly functional athletic environment.

This innovative approach allowed the university to accommodate thousands of spectators while maintaining a relatively economical construction process. The arena's steep seating configuration also contributed to an exceptionally energetic atmosphere, enabling fans to participate actively in the basketball experience.

Beyond its practical advantages, The Pit's architectural design symbolizes the university's willingness to embrace innovation and challenge conventional approaches to campus development. Consequently, the building represents both a functional athletic facility and a broader expression of institutional ambition.


<!-- Portrait documents are the exception to the full-width rule. A tall scan at 100%
     is over 1200px tall and swallows the screen, so center it and leave it near 55%.
     Keep it centered, not floated. -->

{% include images/figure.html
  class="img-center"
  width="55%"
  caption="Replace this caption. Tell readers what to notice in the document and why it changes how they should understand your topic. Cite the collection, box, and folder."
  image-path="sample-primary-source.jpg"
%}

Explain what the document says, what it does not say, and how it fits the story. A source you actually read and explain is worth more than three you only mention.

## National Recognition and Athletic Achievement

Throughout the following decades, The Pit continued to evolve into a nationally recognized venue. A major expansion in 1975 increased its seating capacity, demonstrating the continued popularity of basketball within the university community.

Perhaps one of the most historically significant moments occurred in 1983, when The Pit hosted the NCAA Men's Basketball Final Four. The championship game featured North Carolina State's dramatic victory over the University of Houston, culminating in Lorenzo Charles's memorable last-second basket.

This nationally televised event reinforced The Pit's reputation as a premier collegiate basketball destination. Furthermore, it highlighted Albuquerque's growing visibility within the national sporting landscape and strengthened the relationship between the university and the surrounding community.
%}

## Modernization and Lasting Legacy

As collegiate athletics evolved, The Pit underwent substantial renovations to accommodate modern expectations. A major renovation completed in 2010 introduced upgraded seating, luxury suites, improved facilities, and technological enhancements while preserving the arena's distinctive underground character.

These improvements demonstrate the university's continued commitment to maintaining The Pit as a competitive athletic venue while respecting its historical significance.

Ultimately, The Pit represents far more than a basketball arena. Its history illustrates the intersection of athletic achievement, architectural innovation, institutional growth, and community identity. From its construction in 1966 to its continued prominence in contemporary collegiate athletics, The Pit remains an enduring symbol of the University of New Mexico's traditions and aspirations. Its lasting legacy serves as a powerful reminder of how physical spaces can shape collective experiences and contribute to the cultural identity of an educational institution.


## Sources for Verification
- [University of New Mexico Athletics](https://golobos.com/)
- [University of New Mexico Newsroom](https://news.unm.edu/)
- [The Guide to New Mexico Architecture](https://nmarchitectureguide.org/)
- [NCAA](https://www.ncaa.com/)
%}