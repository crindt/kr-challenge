# Public Planning Models


## Summary
<!-- 250 chars --> 

Public Planning Models will connect an urban population to the models
that drive urban planning.  The resulting two-way conversation between
citizens and government will increase transparency and improve planning
outcomes.

## Details

Urban and Transportation planners have the unenviable task of modeling
the population's behavior, and using those models to evaluate
suggested policies.  This is a balance between science and art,
engineering and politics.  The core need to produce *something* leads
to simplified models that can be insensitive to important inputs, and
the size and complexity of the models means they are rarely critically
evaluated.

Public Planning Models extends the concept of open data to *open
model* by allowing *everyone* to:

* see the predictions made by urban professionals and used by
  decision makers,
  
* use the outputs of these models for their own purposes,

* evaluate the quality of these models on an ongoing basis, and

* inject data into these models to improve their quality.


## Key products

* Adding *recent* urban forecasting data to the open data catalog

* Opening current forecasting models for the public's inspection and use

* Establishing a set of conventions and tools that translate planning
  models into an open, web-based visualization framework

* Establishing methods to allow users to correct and augment the
  travel and activity data that underpin the local agency's planning models.

## The problem

The challenges and shortcomings of the planning process in the United
States are well known, and have been studied extensively since the
early 1970s.  The current leading edge of the state of the practice
has turned towards activity-based models and simulation.  Activity
models are based on one or two day travel and activity surveys, and
attempt to generate synthetic activity patterns for all households in
an area.  While this approach shows promise, the fundamental barrier
is that collecting the necessary input data is expensive and
difficult, and typically happens only once a decade.

The more common state of the practice is to use the Four-Step
planning process.  This approach has the distinction of being both
thoroughly discredited, and widely used!  One of the reasons that the
four-step process is still used is that even though it can be shown to
be broken, it produces future year forecasts based on a modest set of
input data.  Alternative methods require more data and more rigorous
modeling step, and in the end cannot be proven to be much better.

The *problem* as we see it, is that no matter what modeling approach
is used, the process and results are shrouded in mystery, and can only
be fully understood by a handful of people who live and breathe the
local agency's planning model data.

## Our solution

Public Planning Models will open up a planning agency's planning
models to the public.  Whether these models are activity-based
([pdf](http://orfe.princeton.edu/~alaink/NJ_aTaxiOrf467F12/Papers/lit%20review/TSHANDBK.pdf))
or of the more traditional four-step planning process ([pdf](http://www.its.uci.edu/its/publications/papers/CASA/UCI-ITS-AS-WP-07-2.pdf))
variety, these models are typically difficult to set up and run, and
are generally kept hidden in back rooms and dark corners.  We feel
that dragging these models out into public view is
necessary in order to improve the models, and to motivate the public
to contribute better information into the modeling process.

All politics are local.  People only really care about issues if they
are directly affected, but caring doesn't translate into being able to
understand and contribute to the conversation.  For example, presently
if a person hears about a new shopping mall or fast food eatery being
proposed for his or her neighborhood, the individual can try to be
present at the open planning committee meeting at which the new
development will be evaluated.  If the individual is worried about
traffic impacts, he or she must be able to understand complicated
models that are documented in sometimes hundreds of pages of reports.

Instead, imagine a population engaged in the planning process because
they have with direct information about how policy options will impact
their daily lives.  This is the central vision of our project.  Public
Planning Models will localize and personalize the output of planning
models so that empowers citizens to create the communities they want.

In the above example, the key metric might be link travel times on roads
surrounding the project for the various alternatives.  This can be
translated into total trip times quite easily, and trip times are
something everybody can understand.  Using our tool, a concerned citizen
would be able to enter an origin, a destination, and a time of day, and
would then see immediately how long that specific trip will take under
the various alternatives considered, as well as the current time that
trip takes (according to the planning models).  This will allow
individuals to understand different alternatives, and better contribute
to the debate by being able to articulate how he or she might personally
be impacted.

Taking it one step further, users will be able to use our mobile
application to automatically link their travel patterns into the system.
These patterns can be used to notify those users when proposed plans
might impact their current behavior based on model-generated metrics
chosen by the user.  

The benefits are not limited to individuals.  A developer would have
access to the same set of tools, and would be able to more easily
model the traffic impacts a proposed project might have using a
standard baseline model.  Similarly, if a political leaders or
environmental activists want to push for area-wide vehicle tolling
(following the London example), a public bike-share program, or
expanded mass transit, the Public Planning Models tools will allow
them to start with the community's current baseline planning model,
develop their ideal scenario, and then insert those outcomes directly
into the public dialog.  Average citizens can see the projected
impacts of such large scale projects and how they might be affected
both positively and negatively.

Finally, the open, anonymized data collected through Public Planning
Models becomes a new source of high fidelity information that can be
incorporated back into the planning models themselves.  This direct
feedback offers the potential for improving the fit between model
predictions and what the population is actually doing.


The process of opening up these models to greater public scrutiny and
to allow greater public input is not without challenges.  These
include:

* Models differ across regions, cities, and even localities.  Finding
  a common language and set of conventions for representing these
  model systems is hard, and is a central component of Public Planning
  Models.

* How to bring new data from the public interaction with the Public
  Planning Models systems into a planning model.  Again, different
  modeling approaches require different kinds of input data, and so a
  common set of abstractions will be necessary in order to have the
  widest possible impact.

* How to protect the privacy of individual persons and households
  reviewing and contributing planning data, while still giving users
  the belief that their particular contributions are being used.  For
  example, if a person takes the time to enter their daily travel
  patterns, the exact information should be hidden from every other
  user and anonymized sufficiently prior to insertion into the
  planning model system.  But the user should be able to see their
  contribution and feel like their voice has been heard.


## The tool

The fundamental elements of the proposed system are as follows:

### A tool to translate the output of planning models into a common data set   

This element will be the most challenging to develop, but is crucial to
the success of the project.  We expect that it will consist of a
combination of computer programs and established conventions to apply
depending upon which modeling package is being used. While all
planning model systems are unique, they all tend to have certain
features in common, such as the use of traffic analysis zones,
origin-destination matrices, and traffic network data.  Any planning
model output can be converted back into future year traffic analysis
zones with modified land uses, updated origin-destination matrices for
future planning years, and loaded traffic networks. 

### A web-based portal to publicize the Public Planning Models data.  

The public face of the Public Planning Models project will be a
website that everybody can access.  The website would have at least
four different areas.  An Inputs area would allow interested
individuals to enter their own travel and activity data, and indicate
spatially and temporally what projects they personally would be
interested in.  A Model Review section would allow people to examine
baseline and future year models, enter their own travel plans (or use
ones already entered via the Inputs section) and see if the planning
models as they currently stand pass muster.  This part of the website
would also allow for user feedback, enabling a crowd-sourced
model-calibration step.  

A Current Projects section of the website would present any projects
that are currently under consideration by the local or regional
governments.  Similar to the model review section, users could see how
their travel and activity patterns are affected by each proposed
development.  Complementing the current projects section, a Project
Submission section would also exist to allow interested parties to
submit new projects for consideration.  While we haven't thought much
about how this aspect might work, one idea would allow users to edit a
custom copy of the planning zones and traffic networks, allowing them
to create custom scenarios.

While it might be the case that some municipalities will want to run
their own public website, our current thinking is that municipalities
would be more than happy to offload such work onto us.  While we
haven't yet considered revenue streams to establish a continued
maintenance of this data, there are several models that might fit,
including establishing a public, non-profit entity.  Given the nature
of the project, a for-profit enterprise might not be the best approach.

### Smart phone Apps

While our initial focus will be on developing a solid, HTML5 website as
the public face of the project, we are well aware that everybody
expects iOS or Android apps.  Our current team does not have an app
developer on board, and this is a shortcoming of the project.  We
intend to use modern web design tools to produce sites that can work
on all kinds of devices.  Furthermore, our data and methods will be
open, so other developers can take our data and create their own apps.
But most likely we will hire a app developer immediately if this
project is funded.  It would be really cool if an app in your phone
could alert you not only when current traffic conditions might hinder
today's trip home, but also let you know whenever a development plan
is proposed that might impact some aspect of your future life.

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
consulting firm based in Orange County, California.  We are Craig Rindt
and James Marca, both of whom obtained their PhDs in transportation
engineering from the University of California, Irvine.  We have been
working in the transportation and planning fields for the past 20 years,
and together have extensive experience working with planning models that
range from microsimulation models of freeway interchanges, to mesoscopic
models of traffic patterns in local cities, to long term planning models
that describe future year scenarios for an entire metropolitan area.  We
have solid working relationships with staff at Caltrans and at the
California Air Resources Board, and will therefore focus our initial
development on California cities and counties.  Our intent is to develop
a system that can be deployed anywhere in the US, and so we will also
contact municipalities in other states to act as initial customers
during the development phase of our project.

Compared to the "typical" transportation engineer or planner, we have
unique skills in the areas of managing data and abstracting interfaces.
As an example of this, Dr. Rindt recently completed a web-based
interface for Caltrans District 12 that allows them to review how the
efforts of the freeway traffic management center improved the response
and clearing times for specific incidents in any given day.  The system
required the development of database systems that could process traffic
loop data (one observation every 30 seconds from upwards of 2,000
detectors) on a rolling 12-month horizon, along with systems to abstract
key inputs from the California Highway Patrol's incident log, and the
traffic management center's activity log.

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
audience, we also recognize that smart phones and tablets are going to
be the dominant way people interact with Public Planning Models.  To
that end, we expect to hire at least two engineers to develop iOS and
Android apps for this project.  Ideally the apps would use an off-line
first strategy, syncing the projects and travel patterns of the
individual with the projects and planning models most likely to impact
that individual, so that feedback and input can be made with or
without a web connection.

Finally, we place a high value on open source software and open data,
and will open up the entire Public Planning Models stack for use by any
agency or organization.  While we have good ideas and can execute them,
experience has shown that the broader global community will always come
up with something new and different.  The best way to leverage this is
to share our code and our data.



## What is the project (in 1 sentence)

The Public Planning Models project will allow government agencies to
share their planning models on-line with the public, and in turn
accept feedback and input that can be folded back into the planning
model process.
