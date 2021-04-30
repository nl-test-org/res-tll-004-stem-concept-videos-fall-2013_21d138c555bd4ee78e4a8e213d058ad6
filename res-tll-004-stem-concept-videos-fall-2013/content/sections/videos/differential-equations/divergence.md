---
about_this_resource_text: <h2 class="subhead">Summary</h2><p>This video describes
  how divergence is a fundamental component of a complex modeling problem involving
  detonation blasts. The divergence of a vector field is defined physically, and the
  physical description is connected to the mathematical formula. Students analyze
  a collection of vector fields to determine whether or not they have positive, negative,
  or zero divergence by analyzing the change in area or volume of a region of tracer
  particles.</p><h2 class="subhead">Learning Objectives</h2><p>After watching this
  video students will be able to determine points at which a vector field is divergent.</p><p>Funding
  provided by the Singapore University of Technology and Design (SUTD)</p><p>Developed
  by the Teaching and Learning Laboratory (TLL) at MIT for SUTD</p><p>MIT &copy; 2012</p>
course_id: res-tll-004-stem-concept-videos-fall-2013
embedded_media:
- id: Video-YouTube-MP4
  media_location: f0NgE--vOEI
  parent_uid: f7ba69c7d1fe502795b392e32b21858c
  title: Video-YouTube-MP4
  type: Video
  uid: b182eb582785c1484477cddd1d0b4de1
- id: MITRES_TLL-004F13_Div_IG.pdf
  parent_uid: f7ba69c7d1fe502795b392e32b21858c
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/differential-equations/divergence/MITRES_TLL-004F13_Div_IG.pdf
  title: Divergence Instructor Guide
  type: null
  uid: a70a54d5fecaa8b36a414ace76a9c257
- id: RES.TLL-004_F13_Divergence-th.jpg
  parent_uid: f7ba69c7d1fe502795b392e32b21858c
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/differential-equations/divergence/RES.TLL-004_F13_Divergence-th.jpg
  title: RES.TLL-004_F13_Divergence-th.jpg
  type: null
  uid: 2f66cd6d46626c5f26d9677644705073
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/f0NgE--vOEI/default.jpg
  parent_uid: f7ba69c7d1fe502795b392e32b21858c
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 67f08e580e2cfab72fd440405172cae3
inline_embed_id: 88175571divergence56215731
layout: video
order_index: null
parent_uid: 7e7fcfb2130297e43da2fb9fcaab47f4
related_resources_text: <p>Instructor Guide</p> <p><a href="./resolveuid/a70a54d5fecaa8b36a414ace76a9c257"
  target="_blank">Divergence Instructor Guide (PDF)</a></p>
short_url: divergence
technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/differential-equations/divergence
template_type: Tabbed
title: Divergence
transcript: '<ul>     <li><a href="./resolveuid/6dcaf2b25971f5026d8565d5af569b1f"
  target="_blank">Download this transcript - PDF (English - US)</a></li> </ul> <p>A
  soldier''s helmet can be designed to help protect against the shock waves from explosions.
  To achieve the best design, researchers need to understand how those shock waves
  cause damage. In this video you''ll see how they can model shock waves using three
  differential equations, all of which involve a concept called divergence.</p> <p>This
  video is part of the Differential Equations video series.   Laws that govern a system''s
  properties can be modeled using differential equations.</p> <p>Hi, my name is Raul
  Radovitzky, and I am a professor of Aeronautics and Astronautics at MIT.  Today,
  I want to talk to you about divergence.  Whenever you are modeling a system that
  involves a vector field quantity, knowing whether or not the vector field is divergent
  often provides valuable information.  This concept is applicable to a number of
  topics, including fluid dynamics and electromagnetism, and is fundamental to the
  mathematical description of exciting physical phenomena such as black holes, traffic
  flow, and explosive detonation.</p> <p>Before watching this video you should know
  the definition of divergence, and how to compute the divergence of a vector field.</p>
  <p>After watching this video, you should be able to determine whether or not a vector
  field has divergence.  You will do this by imagining the vector field to be a velocity
  field and considering what happens to the area of a differential volume element
  in the vector field.</p> <p>My expertise is in understanding how materials respond
  to extreme loads---such as in turbines, shuttles, and planes moving at hypersonic
  speed.  When I arrived at MIT one month after 9/11, I was motivated to use this
  expertise in order to help protect people.</p> <p>Explosions create a lot of damage.  In
  particular, the shock wave produced in the blast is presumed to be a cause of brain
  damage.</p> <p>One of the things we are interested in is developing helmets that
  protect people from such blasts.</p> <p>In order to do this, we need to understand
  how injury to the head occurs, and what material properties and helmet geometries
  can mitigate the blast damage.</p> <p>The approach has been to put together multidisciplinary
  teams--involving neurologists, cell biologists, biomechanical engineers, computational
  modelers, and material scientists to create complex mathematical models.</p> <p>We
  design experiments that investigate the effects of a shock wave as it damages an
  object. We use data from those experiments to validate our mathematical models.</p>
  <p>We of course need to model the blast wave.  This is a strong pressure or shock
  wave that results from the sudden release of chemical energy from the explosive
  material.</p> <p>And this shock wave is described by 3 equations: conservation of
  mass, conservation of momentum, and conservation of energy. All three differential
  equations involve divergence.  So the very start of our model involves modeling
  solutions to these 3 equations.  And this is the simple part.</p> <p>In the rest
  of this video, my graduate student Michelle Nyein will help you begin to understand
  how to use divergence to describe physical phenomena.  You will come back to the
  example of detonation at the end of the video to see if you can predict whether
  or not a blast wave has positive divergence, negative divergence, or zero divergence.</p>
  <p>My name is Michelle Nyein, and I am a graduate student in the department of aeronautics
  and astronautics, working with the Institute for Soldier Nanotechnologies.</p> <p>Divergence
  is a local property of vector fields.</p> <p>For two dimensional vector fields,
  the divergence is a measure of the net flux per area of a vector field through a
  differential area element.</p> <p>Or, in simple terms, divergence measures how much
  the flow expands or compresses at each point.</p> <p>In two dimensions, divergence
  is the net flux of the vector field over a very small area with side lengths 2 Delta
  x  and 2 Delta y.</p> <p>By making an approximation for the vector field on each
  side of this differential element, determine a formula for the divergence.   [pause]</p>
  <p>Because the component tangent to an edge does not affect the flux through the
  edge,  we need only considering the normal components of the vector field at each
  edge.</p> <p>We approximate the flux through a side to be the value of the vector
  in the middle times the length of the side, divided by  the area of the box.   So
  adding the fluxes through each side with appropriate signs, we obtain the following
  expression.</p> <p>We simplify the expression, and  take the limit as Delta x and
  Delta y approach zero.   We end up with an expression for the divergence in terms
  of partial derivatives of the components of the vector field.</p> <p>In 3 dimensions,
  we can take a differential volume element with side lengths  2 Delta x, 2 Delta
  y, and 2 Delta z in Cartesian coordinates.</p> <p>We look at our vector field at
  points on the interior of each face.  Because flux only depends on the components
  of a vector field perpendicular to the surface,  we can decompose each vector into
  its x, y, and z components.</p> <p>And we only need to consider the  component that
  is perpendicular to each face.</p> <p>We find an analogous formula for the net flux
  per unit volume through a differential volume element.</p> <p>Okay, so that is divergence.  But
  what does it mean?  And how are we supposed to use this to describe physical phenomena
  in the world around us?</p> <p>For the moment we will describe how to think of divergence
  for 2-dimensional vector fields because it is simpler to draw.  However, all of
  the ideas we will discuss are true in 3-dimensions as well  by replacing the word
  area with volume.</p> <p>One handy way to imagine divergence is to think of the
  vector field as being a velocity field. Suppose a small region is outlined by a
  number of tracer particles, each moving in the velocity field.</p> <p>If the divergence
  of the field is positive, then the net flux is out of the region, the particles
  move outwards according to the magnitude and direction of the velocity vector field.   Here
  the particles are moving with constant x-velocity,  but different y-velocities,
  increasing the area by expanding in the y-direction.</p> <p>If the divergence of
  the field is less than zero,  then the area outlined by the particles decreases
  as the particles flows according to the velocity field.   Here the particles are
  moving with zero y-velocity, but with x-velocities that decrease as the particles
  move to the right.</p> <p>And if the divergence is zero,  the area doesn''t change.  Let''s
  see if we can use this model to recognize positive, negative, and zero divergence.</p>
  <p>Let''s start by considering a vector field we encounter in the world.</p> <p>Fluid
  flow has a velocity vector field.  Here you see a clip of a classic MIT fluid flow
  video.  The region of flow is outlined.   Square regions of hydrogen bubbles have
  been added to the flow field.  These bubbles are analogous to tracer particles.</p>
  <p>Make a prediction as to whether or not this vector field is divergent. [pause]</p>
  <p>You may have noticed that the squares turn into parallelograms, because due to
  the flow geometry, the horizontal component of the velocity near the top wall is
  larger than the horizontal velocity component near the bottom wall.</p> <p>What
  you may not have noticed is that while the shape changes, the area of each element
  does not change.  Thus the velocity field of this fluid flow regime is divergence-free.</p>
  <p>In fluid dynamics,  when the velocity field of a fluid is divergence-free,  the
  fluid is said to be incompressible.  No divergence means that there is  zero net
  flux through any volume element.</p> <p>When the flow field of a fluid is divergence-free,
  it means that it is impossible to compress or expand the average separation between
  the molecules in the fluid.</p> <p>What do you think it means to be compressible?
  [pause]</p> <p>Gasses are a familiar substance that we understand to be compressible.  You
  are probably familiar with  the ideal gas law: PV=nRT.</p> <p>So you know that increasing
  pressure allows the average space between molecules to be compressed, which increases
  the average density.</p> <p>During compression, the divergence of the average velocity
  field is negative.</p> <p>Decreasing pressure allows the average space between molecules
  to expand, decreasing density.   During expansion, the divergence of the average
  velocity field is positive.</p> <p>Now let''s look at common 3-dimensional vector
  field,  an electric field generated by a positive  point charge.</p> <p>Since it
  is common to use spherical coordinates when considering electric fields,  we will
  consider differential volume elements that are in spherical coordinates for convenience.</p>
  <p>If we imagine this spherical volume element is made up of tracer particles, and
  the field is a velocity field,  the volume clearly increases.  So this electric
  field appears to have positive divergence.</p> <p>However, any differential volume
  element that does not contain the point charge actually will not change in volume.  So
  the divergence is only non-zero at the point charge generating the field.</p> <p>Consider  the
  electric field generated by a  negative point charge.   What is the divergence of
  the vector field at the point charge? [pause]</p> <p>That''s right,  the volume
  of a differential sphere surrounding the point charge would decrease, so the divergence
  is negative.</p> <p>The electric field generated by a positive charge is said to
  have  a source, while an electric field generated by a negative charge is said to
  have  a sink.</p> <p>The vector field at any source has positive divergence, while  the
  vector field at any sink has negative divergence.</p> <p>Let''s look at a rotational
  vector field in the plane:  V = y i-hat minus x j-hat.  The magnitudes of the vectors
  increase as they move radially outwards from the center.  Do you think this field
  has positive divergence, negative divergence, or zero divergence? [pause]</p> <p>A
  square of tracer particles placed about the origin  simply rotates.  This means
  that this field cannot have a source or a sink at the origin. If we add a square
  of tracer particles at any other point in the field, you see that  it revolves about
  the origin without changing area.  This happens because the particles further from
  the center move faster than particles near the origin. A quick computation confirms
  that this field has zero divergence everywhere.</p> <p>By looking at these common
  vector fields that you will encounter in your studies, we can see that divergence
  can tell us something important about the behavior of each field.</p> <p>Given what
  you just learned about divergence, what can you say about the divergence of a blast
  wave? [pause]</p> <p>Blast waves are NOT divergence-free.   At the simplest level
  of understanding, the blast wave is created by highly compressed air and chemicals,
  which do not experience any resistance to expansion.  So they expand very quickly,
  with positive divergence.</p> <p>To review:<br /> Detonations produce blast waves,
  which are described by solutions to a system of 3 partial differential equations,
  each containing divergence terms.</p> <p>The divergence is a local property of vector
  fields that describes the net flux per volume through an infinitesimal volume element.</p>
  <p>Understanding the divergence of a fluid flow tells us if the fluid is compressible
  or not.</p> <p>The divergence of a vector field is positive at a source, and negative
  at a sink.</p>'
type: course
uid: f7ba69c7d1fe502795b392e32b21858c

---
None