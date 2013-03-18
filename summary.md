# Public Planning Models


## Summary
<!-- 250 chars -->
Public Planning Models will connect an urban population to the models that drive urban
planning.  The resulting two-way conversation between citizens and
government will increase transparency and improve planning outcomes.

## Details

Urban and Transportation planners have the unenviable task of modeling
the population's behavior, and using those models to evaluate
suggested policies.  This is a balance between science and art,
engineering and politics.  More often than not, the core need to
produce *something* leads to necessarily simplified models that are
only occasionally sensitive to the things that matter and are rarely
critically evaluated.

Public Planning Models extends the concept of open data to *open model* by allowing
*everyone* to:

* see the predictions made by urban professionals and used by
  decision makers,
  
* use the outputs of these models for their own purposes,

* evaluate the quality of these models on an ongoing basis,

* inject data directly into these models to improve their quality.


## Key products

* Adding *recent* urban forecasting data to the open data catalogue

* Opening current forecasting models for the public's use

* Establishing a set of conventions and tools that translate planning
  models into an open, web-based visualization framework

* Establishing methods to allow users to correct and augment the
  travel and activity data that underpin the local agency's planning models.

## The problem

The challenges and shortcomings of the planning process in the United
States are well known, and have been studied extensively since the
early 1970s.  The current leading edge of the state of the practice
has turned towards activity-based models and simulation.  Activty
models are based on one or two day travel and activity surveys, and
attempt to generate synthetic activity patterns for all households in
an area.  While this approach shows promise, the fundamental barrier
is that collecting the necessary input data is expensive and
difficult, and typically happens only once a decade.


## Our solution

Public Planning Models will open up a planning agency's planning
models to the public.  Whether these models are activity-based or of
the more traditional four-step planning process variety, these models
are typically difficult to set up and run, and are generally kept
hidden in back rooms and dark corners.  We feel that dragging these
models out into public view, while difficult and painful, is necessary
in order to improve the models, and to motivate the public to
contribute better information into the modeling process.  All politics
are local, and if a person hears about a new shopping mall or fast
food eatery being proposed for his or her neighborhood, the Public
Planning Models approach will allow individuals to both become
educated on the expected impacts of such projects, and also to weigh
in on how he or she might personally be impacted by the proposed
development.  Similarly, if a mayor wants to push for area-wide
vehicle tolling (following the London example), or a public bike-share
program, people can see how the projected impacts of such large
scale projects, and more importantly, evaluate the personal impacts of
such projects compared to the "do nothing" alternatives.

The process of opening up these models to greater public scrutiny and
to allow greater public input is not without challenges.  These
include:

* Models differ across regions, cities, and even localities.  Finding
  a common language and set of conventions for representing these
  model systems is central to Public Planning Models.

* How to bring new data from the public interation with the Public
  Planning Models systems into a planning model.  Again, different
  modeling approaches require different kinds of input data, and so a
  common set of abstractions will be necessary in order to have the
  widest possible impact.

* How to protect the privacy of individual persons and households
  reviewing and contributing planning data, while still giving users
  the belief that their particular contributions are being used.  For
  example, if a person clicks in their daily commute to work, the
  exact information should be hidden from every other user, and
  anonymized sufficiently prior to insertion into the planning model
  system, but the user should be able to see their contribution and
  feel like their voice has been heard.




## The Long term benefits

Public Planning Models is about connecting the public with urban
transportation policy making.  Right now the process is opaque to all
but a select few.  Even city council members and planning
commissioners probably have no idea how models are developed and how
tenuous the predictions really are.  Our vision is that truly
community-driven planning and development is impossible without
opening the models that drive that policy.  Furthermore, we feel that
opening up this process will give average citizens a motivation to
contribute their own unique experiences to the planning process.  If
one thing is true in transportation and planning, it is that every
person and every household has a unique set of motivations and
limitations.  These unique constraints can come together using the
Public Planning Models system and make for a better life for
everybody.  

## The team

Public Planning Models is proposed by Activimetrics, a two-person
consulting firm based in Orange County, California.  We are Craig
Rindt and James Marca, both of whom obtained their PhDs in
transportation engineering from the University of California, Irvine.
We have been working in the transportation and planning fields for the
past 20 years, and together have extensive experience working with
planning models that range from microsimulation models of freeway
interchanges, to mesoscopic models of traffic patterns in local
cities, to long term planning models that describe future year
scenarios for an entire metropolitan area.  We have solid working
relationships with staff at Caltrans and at the California Air
Resources Board, and will therefore focus our intial development on
California cities and counties.  Our intent is to develop a
system that can be deployed anywhere in the US, and so we will also contact
municipalities in other states to act as initial customers during the
development phase of our project.  

Compared to the "typical" transportation engineer, we have unique
skills in the areas of managing data and abstracting interfaces.  As
an example of this, Dr. Rindt recently completed a web-based interface
for Caltrans District 12 that allows them to review how the efforts of
the freeway traffic management center improved the response and
clearing times for specific incidents in any given day.  The system
required the development of database systems that could process
traffic loop data (one observation every 30 seconds from upwards of
2,000 detectors) on a rolling 12-month horizon, along with systems to
abstract key inputs from the California Highway Patrol's incident log,
and the traffic management center's activity log.

On a similar scale, but with different data, Dr. Marca has been
working with the California Air Resources Board to develop an
integrated database that merges freeway loop detector data, truck
weigh in motion data, and the federal highway performance monitoring
system data into a single view of roadway vehicle activity.  The
project has to deal with missing data in each of these sets, and has
developed data-centric  imputation algorithms to provide a best guess
for missing data.  The project also integrated OpenStreetMap data to
create GIS entries for arterial and highway links so that the data
quality and quantity can be visualized on a map.

Neither of these projects are yet open to public scrutiny, but the
source code and some preliminary results can be made available upon
request.


One area where our team lacks experience is in developing iOS and
Android apps.  We are well-versed in web-based application
development, but while web-based HTML5 interfaces can reach a broad
audience, we also recognize that smartphones and tablets are going to
be the dominant way people interact with Public Planning Models.  To
that end, we expect to hire at least two engineers to develop iOS and
Android apps for this project.  Ideally the apps would use an off-line
first strategy, syncing the projects and travel patterns of the
individual with the projects and planning models most likely to impact
that individual, so that feedback and input can be made with or
without a web connetion.

Finally, we place a high value on open source software and open data,
and will open up the entire Public Planning Models stack for use by
any agency.  While we have good ideas and can execute them, experience
has shown that the broader Internet will always come up with something
new and different.  The best way to leverage this is to share our code
and our data.



## What is the project (in 1 sentence)

The idea behind the Public Planning Models project is to develop a set
of tools and conventions that will allow government agencies of all
sizes to share their planning models on-line with the public, and in
turn accept feedback and input that can be folded back into the
planning model process.  
