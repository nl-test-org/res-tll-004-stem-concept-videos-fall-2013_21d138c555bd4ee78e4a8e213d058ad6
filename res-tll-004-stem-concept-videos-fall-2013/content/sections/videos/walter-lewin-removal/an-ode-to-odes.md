---
about_this_resource_text: <h2 class="subhead">Summary</h2> <p>This video leads students
  through modeling the regular, non-linear pendulum with a differential equation.
  We explore why solutions to a differential equation are an infinite family of functions.
  We show that to determine a specific solution to this second order differential
  equation, two initial conditions must be specified. Proof of the need for two initial
  conditions is shown via use of the Taylor Series.</p> <h2 class="subhead">Learning
  Objectives</h2> <p>After watching this video students will be able to:</p> <ul>     <li>Understand
  that the physical laws governing a system&rsquo;s properties can be modeled using
  differential equations.</li>     <li>Explain that the solution to a differential
  equation is a family of functions.</li>     <li>Recognize that specifying initial
  conditions determines a particular solution function to a differential equation.</li>
  </ul> <p>Funding provided by the Singapore University of Technology and Design (SUTD)</p>
  <p>Developed by the Teaching and Learning Laboratory (TLL) at MIT for SUTD</p> <p>MIT
  &copy; 2012</p>
course_id: res-tll-004-stem-concept-videos-fall-2013
embedded_media:
- id: Video-YouTube-Stream
  media_location: 8VlloeKvV8E
  parent_uid: 1ffd49a2c8d1324c2b0f9dd62846e47b
  title: Video-YouTube-Stream
  type: Video
  uid: c0440ea2dcf07c76945cc78d02a8fecb
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/8VlloeKvV8E/default.jpg
  parent_uid: 1ffd49a2c8d1324c2b0f9dd62846e47b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 7a004b3783b56685f84af726fb67ee8c
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/podcast/an-ode-to-odes/id765926614?i=237394842&mt=2
  parent_uid: 1ffd49a2c8d1324c2b0f9dd62846e47b
  title: Video-iTunes U-MP4
  type: Video
  uid: 25b3d4da34c90c0578a2e67bcb0c56d3
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MITRES.TLL-004F13/MITRES_TLL-004F13_an_ode_to_odes_300k.mp4
  parent_uid: 1ffd49a2c8d1324c2b0f9dd62846e47b
  title: Video-Internet Archive-MP4
  type: Video
  uid: 2a8f307a8b13e56b6877d73bb708dc84
- id: an_ode_to_odes.srt
  parent_uid: 1ffd49a2c8d1324c2b0f9dd62846e47b
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/walter-lewin-removal/an-ode-to-odes/an_ode_to_odes.srt
  title: an_ode_to_odes.srt
  type: null
  uid: ce061be4ba0366a62ac02d034fe30152
- id: Caption-OCW-SRT
  parent_uid: 1ffd49a2c8d1324c2b0f9dd62846e47b
  title: Caption-OCW-SRT-English - US
  type: Caption
  uid: 71cf8326a92cd0b81621c0c1458b8dff
- id: Transcript-OCW-PDF
  parent_uid: 1ffd49a2c8d1324c2b0f9dd62846e47b
  title: Transcript-OCW-PDF-English - US
  type: Transcript
  uid: 29e094dbd1e05bb0900962035f466f94
inline_embed_id: 71293024anodetoodes71275910
layout: video
order_index: null
parent_uid: 4e02974d63754176cb96f536107d96bf
related_resources_text: <p>Instructor Guide</p> <p><a href="./resolveuid/139c2030b23f62b37b20276b75f1b28e"
  target="_blank">An Ode to ODEs Instructor Guide (PDF)</a></p>
short_url: an-ode-to-odes
technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/walter-lewin-removal/an-ode-to-odes
template_type: Tabbed
title: An Ode to ODEs
transcript: '<p>Here you see MIT''s Walter Lewin, about to swing on a pendulum. We
  can write a function for how the angle theta 1 depends on time, which completely
  describes his motion.</p> <p>But what if Walter were to start swinging from here,
  instead of there? We''d need a different function, theta 2 of t.</p> <p>And what
  if one of his students were to give him a little push? That''s right&mdash;we''d
  need a third function, theta 3 of t.</p> <p>It would be great if we could write
  a single rule, based on physical principles, that governs the behavior of the pendulum.
  And every function that describes pendulum motion would have to satisfy this rule.</p>
  <p>This video will show you how to write rules like these using the language of
  differential equations.</p> <p>This video is part of the Differential Equations
  video series. Laws that govern a system''s properties can be modeled using differential
  equations.</p> <p>Hi, my name is Peter Dourmashkin. And I am a senior physics lecturer
  at MIT.</p> <p>Differential equations are very important in modeling physical phenomena.
  They describe rules that constrain the behavior of many complex physical and social
  systems.</p> <p>Before watching this video, you should be familiar with drawing
  free body force diagrams and applying Newton''s second law in polar coordinates.
  You should remember how to write a Taylor series expansion of a function about a
  point, and understand what it means.</p> <p>After watching this video, you should
  be able to do the following 3 things:</p> <p>Understand that the physical laws governing
  a system''s properties can be modeled using differential equations,</p> <p>Explain
  that the solution to a differential equation is a family of functions,</p> <p>And
  recognize that specifying initial conditions determines a particular solution function
  to a differential equation.</p> <p>Let''s see how differential equations arise as
  a natural language to model the pendulum. To develop this model, we will use our
  knowledge of physics.</p> <p>First, what is a pendulum? A pendulum is typically
  an object, called a bob, which hangs from one end of a string. The other end is
  fixed to a pivot point.</p> <p>Let''s pause the video. Try to describe what you
  think are the important properties of pendulum motion. You might have said that
  the behavior is periodic, that the same motion repeats over and over. We say that
  the pendulum exhibits oscillations, or harmonic motion. Maybe you also noted that
  the motion is rotational, moving in a circular path about the pivot point.</p> <p>Finally,
  you may know that the motion eventually stops, that is, the oscillations experience
  a damping force. Overall we describe the motion as &quot;damped harmonic motion.&quot;</p>
  <p>Now, let''s develop a model for the pendulum. A good first step is to choose
  a coordinate system.  Because the pendulum rotates about a fixed pivot point, it
  makes sense to use polar coordinates. Theta is the angle the bob makes with the
  vertical, and r is the distance of the bob from the pivot point.</p> <p>Remember
  that when using vector in polar coordinates, r-hat is the unit vector that points
  radially outward from the pivot point, and theta-hat is the unit vector that points
  perpendicular to r-hat, tangential to the motion of the pendulum.</p> <p>Whenever
  you model a system, it''s important to recognize that you are making some simplifying
  assumptions.  We are going to start by making three:</p> <ol>     <li>The string
  has no mass.</li>     <li>The mass, m, of the bob is uniformly distributed.</li>     <li>The
  string has length L and does not stretch or shrink.</li> </ol> <p>This means that
  all motion happens in the tangential direction; none in the radial direction.</p>
  <p>Now let''s figure out what we need to know to describe the motion of the pendulum.</p>
  <p>At the speeds we are dealing with, we can ignore relativistic effects; there
  are no electromagnetic forces, and the scale is large enough that quantum mechanics
  isn''t necessary. So we''ll use Newton''s second law to describe the motion of the
  pendulum.</p> <p>What forces do you think we need to consider in this problem? Pause
  the video here.</p> <p>Let''s draw a free body diagram for an instant where the
  bob is to the right of vertical, and moving downwards.</p> <p>There is the gravitational
  force acting on the bob, due to the interaction between the Earth and the bob, which
  points straight down with magnitude mg. We treat this force as acting on the center
  of mass of the bob.</p> <p>The string exerts a force on the bob, which you know
  as tension. We don''t know what the magnitude of this force is, so we''ll just write
  it as T, pointing inwards towards the pivot point.</p> <p>Finally, the motion will
  eventually stop, so there must be damping forces acting on the system. The damping
  forces are complicated. For example, there is friction at the pivot point, and air
  resistance on the bob. Let''s make an assumption that the damping force due to friction
  at the pivot point is negligible because the string is small and lubricated. Then
  the damping force is almost entirely from the drag due to air resistance.</p> <p>The
  bob doesn''t experience any drag when it is stationary, and experiences larger amounts
  of drag the faster it is moving. Because the speeds of the pendulum are relatively
  slow, that is we do not expect there to be turbulence, we can model the drag force
  as being linearly proportional to velocity, and opposing the direction of motion.
  Because we assume that all motion occurs in tangential direction, we can draw the
  damping force like so.</p> <p>Recall that Newton''s second law is a vector equation.
  Because force and acceleration are both vector quantities, we need to decompose
  them into r-hat and theta-hat components. Remember, acceleration can be decomposed
  into two component vectors, one pointing radially inward called centripetal acceleration,
  and a tangential component vector called angular acceleration.  We also need to
  decompose our force vectors.  Notice that the tension force is already pointing
  radially inward, in the negative r-hat direction. And the damping force is pointing
  in the theta-hat direction, opposite the direction of the angular velocity vector.</p>
  <p>So all we have to do is decompose the gravitational force. We project that vector
  onto the r-hat and theta-hat component vectors. In the r-hat direction the magnitude
  is mg cos(theta) and points outwards. In the theta-hat direction, the magnitude
  is mg sin(theta) and points in the negative theta-hat direction.</p> <p>Newton''s
  second law can now be written as two component equations. One in the radial direction,  mg
  cosine theta minus tension is equal to m times centripetal acceleration.</p> <p>And
  the other in the tangential direction, negative mg sine theta minus k times angular
  velocity is equal to m times the angular acceleration.</p> <p>This system of two
  equations has two unknowns: the angle theta and the tension. Remember that we are
  trying to find an expression for how the angle theta depends on time. This second
  equation is more useful to us, because we can express both the angular velocity
  and the angular acceleration in terms of theta. Let''s see how.</p> <p>The circular
  motion of the pendulum is a 1-dimensional motion, parameterized by time t. The displacement
  of the pendulum away from center is the arc length, which is L times theta of t.
  Because the angular velocity is tangent to the circle of motion, it can be found
  simply by differentiating the displacement with respect to the parameter t, which
  gives us that the angular velocity is L times the time derivative of theta. The
  angular acceleration is just the time derivative of the angular velocity, and is
  given by L times the second time derivative of theta.</p> <p>Observe that this works
  because we are only looking for the angular velocity and angular acceleration which
  point tangent to our 1-dimensional motion. In fact, we see that the velocity is
  everywhere tangent to the motion, if we think of the velocity as the limit of the
  displacement vector with respect to a small change in time.</p> <p>However, the
  acceleration has two components. It has an angular component that we computed, but
  it also has a radial component, the centripetal acceleration. The tangential component
  comes from how the velocity vector changes in magnitude, and the radial component
  comes from how the velocity vector changes in direction.</p> <p>So now we''ve found
  expressions for the magnitudes of the angular velocity and angular acceleration:</p>
  <p>We can substitute these equations into Newton''s Second Law in the theta-hat
  direction; we obtain the following equation.</p> <p>This is a second order ordinary
  differential equation or 2nd order ODE. It is ordinary because there is only one
  independent variable, time, that the angle theta depends on. It is second order
  because the highest degree derivative that appears in the equation is a second derivative.</p>
  <p>Any function describing the pendulum motion must satisfy this differential equation.   Keep
  in mind that there are other forces we ignored, such as friction at the pivot point.
  This is a very simple but nontrivial model for the non-linear pendulum.</p> <p>Notice
  that the first derivative term is our velocity dependent drag force. If we decide
  that this term is negligible, we would get this equation. It is still complicated,
  but you might notice that it looks somewhat familiar.</p> <p>If we assume that the
  displacement of the angle is very small, we can approximate sin theta as the angle
  theta, which gives us this equation. This is the equation of the simple harmonic
  oscillator.  So you see that this piece connecting the term sin theta and the second
  derivative of theta produces the oscillatory behavior, and the first derivative
  term is responsible for the damping of the motion.</p> <p>We''ve seen that we can
  apply our knowledge of physical laws to model a non-linear pendulum with a differential
  equation.  How does this differential equation describe the motion of a pendulum?</p>
  <p>A differential equation is an equation where the unknown element is a function,
  rather than a number or a single value. The differential equation is a rule that
  describes how the system evolves from any time t to a time t plus Delta t. In particular,
  it describes the relationship between the angle theta and its first and second derivatives
  as the system evolves over time.</p> <p>Remember that to describe the motion of
  the pendulum, we need an expression for the angle theta as a function of time. Do
  you think there is a unique solution to this differential equation? Pause the video
  here and discuss.</p> <p>You probably have some sense that the motion of the pendulum
  depends on how and where you release it&mdash;conditions we refer to as initial
  conditions.</p> <p>For example, if we barely move the pendulum away from center,
  and release it from rest, the oscillation will be small. Larger displacements will
  give larger oscillations, even though eventually they all damp down to zero. All
  of these pendulum motions satisfy the same differential equation!</p> <p>Since every
  starting position will give a different dependence of theta on time, the solution
  is not unique. We say that the solution to a differential equation is an infinite
  family of functions.</p> <p>But what if we were are interested in finding one solution
  in particular?</p> <p>In the examples you just saw, we specified the initial angle
  from which the pendulum was released. Is this the only piece of information we need
  to pick out a specific solution from the infinite family?</p> <p>Let''s test that.
  Here you see two identical pendulums, each starting from the same initial angle.
  Are we guaranteed that the motion will be the same?</p> <p>Pause the video here
  to make a prediction.</p> <p>Clearly not. What was the difference between the initial
  conditions for these two pendulums? Pause the video here.</p> <p>The initial angles
  of both pendulums were the same. However, one was released from rest, and the other
  had an initial push. In other words, the initial angular velocities were different.
  Remember, our differential equation only holds after the pendulum is released because
  it doesn''t include the action of the pushing force.</p> <p>Now we see the importance
  of specifying two initial conditions&mdash;the initial angle and the initial angular
  velocity.  Remember, the differential equation is the rule for how the system evolves
  over time. In order to solve this differential equation, we are going to use the
  Taylor series expansion for the function theta about t=0.</p> <p>Recall that this
  is a polynomial series, whose coefficients are determined by all of the derivatives
  of the function theta at time t=0.  So how can we find all of these derivatives
  of theta?</p> <p>Let''s use the differential equation to find the second derivative
  at time t=0. Notice that it depends on both of our initial conditions: initial angle
  and initial angular velocity.  This is why we need these initial conditions.</p>
  <p>We can differentiate the second derivative to find the third derivative at time
  t=0. Notice again that the third derivative depends on the initial angle, the initial
  angular velocity, and the second derivative at time t=0.</p> <p>We can continue
  this process and find recursive formulas for the all of the higher order derivatives
  of theta at time t=0! That''s how the two initial conditions allow us to pick out
  a solution, by specifying all of the coefficients for the Taylor series at t=0.
  Our Taylor series solution completely describes the function theta. But it only
  works on the interval of convergence. If the series converges everywhere, we''re
  done! But if it doesn''t converge everywhere, it must converge on some interval.</p>
  <p>So you see, a differential equation can determine a specific function if you
  have enough pieces of initial data to determine all the Taylor coefficients for
  the function. In our case, with a second order ordinary differential equation, we
  just needed two initial conditions.</p> <p>Pause the video. If you had a third order
  differential equation, how many initial conditions would you need to specify one
  solution? [Pause] That''s right, three!</p> <p>We wanted to describe the motion
  of a pendulum.  We did this by making a model, where we made some simplifying assumptions
  and applied Newton''s Second Law.</p> <p>This gave us the differential equation,
  which is the rule that any function of pendulum motion and its derivatives must
  satisfy.</p> <p>We saw there is an infinite family of solution functions for a differential
  equation.</p> <p>Because our differential equation was second order, we needed 2
  initial conditions to specify one solution.</p> <p>The initial conditions allowed
  us to determine the coefficients of the Taylor series for the angle theta as a function
  of time, which solved the differential equation.</p>'
type: course
uid: 1ffd49a2c8d1324c2b0f9dd62846e47b

---
None