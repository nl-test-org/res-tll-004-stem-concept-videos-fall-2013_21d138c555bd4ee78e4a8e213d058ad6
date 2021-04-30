---
about_this_resource_text: <h2 class="subhead">Summary</h2> <p>This video leads students
  through the physical definition of the curl, and its connection to the mathematical
  description. A variety of classical fluid flow environments are analyzed for the
  existence of curl. Finally, the connection between curl and momentum transfer in
  fluid flow are explored in the context of biological locomotion.</p> <h2 class="subhead">Learning
  Objectives</h2> <p>After watching this video students will be able to:</p> <ul>     <li>Understand
  curl as a measurement of the magnitude and direction of maximum circulation per
  unit area.</li>     <li>Recognize curl in 2-dimensional fluid flows.</li>     <li>Describe
  the relationship between curl and vorticity.</li>     <li>Connect vorticity to momentum
  transfer for a collection of familiar physical phenomena.</li> </ul> <p>Funding
  provided by the Singapore University of Technology and Design (SUTD)</p> <p>Developed
  by the Teaching and Learning Laboratory (TLL) at MIT for SUTD</p> <p>MIT &copy;
  2012</p>
course_id: res-tll-004-stem-concept-videos-fall-2013
embedded_media:
- id: Video-YouTube-Stream
  media_location: 2pQW0UrkrQY
  parent_uid: 6200df4a290e4587c8bf27bb18171bee
  title: Video-YouTube-Stream
  type: Video
  uid: f7f5b95dba6db28aaa5d548643557df8
- id: MITRES_TLL-004F13_Curl_IG.pdf
  parent_uid: 6200df4a290e4587c8bf27bb18171bee
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/differential-equations/curl/MITRES_TLL-004F13_Curl_IG.pdf
  title: Curl Instructor Guide
  type: null
  uid: 94c6fc5f25af9e74e87a9a460657a76a
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/2pQW0UrkrQY/default.jpg
  parent_uid: 6200df4a290e4587c8bf27bb18171bee
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 44cb06c044f134d86e8917a165e0da00
inline_embed_id: 90981200curl79636411
layout: video
order_index: null
parent_uid: 7e7fcfb2130297e43da2fb9fcaab47f4
related_resources_text: <p>Instructor Guide</p> <p><a href="./resolveuid/94c6fc5f25af9e74e87a9a460657a76a"
  target="_blank">Curl Instructor Guide (PDF)</a></p>
short_url: curl
technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/differential-equations/curl
template_type: Tabbed
title: Curl
transcript: "<ul>     <li><a target=\"_blank\" href=\"./resolveuid/1167084d3d8718d0a9100d12b663a628\"\
  >Download this transcript - PDF (English - US)</a></li> </ul> <p>If you&rsquo;ve\
  \ ever tried to walk through waist-deep water, you know that you have to apply a\
  \ much stronger force to overcome drag than you do when walking through air. And\
  \ yet fish seem to glide through water almost effortlessly. Their bodies are adapted\
  \ to reduce drag, but they can&rsquo;t eliminate it; so they have to provide enough\
  \ propulsive force to overcome it. In this video we&rsquo;ll use the concept of\
  \ curl to explain how fish swim so efficiently through water.</p> <p>This video\
  \ is part of the Differential Equations video series.   Laws that govern a system&rsquo;s\
  \ properties can be modeled using differential equations.</p> <p>Hi, my name is\
  \ Brenden Epps, and I am a Postdoc at the MIT Sea Grant Design Lab.  Today, I want\
  \ to talk to you about curl.<br /> The existence of curl describes a variety of\
  \ physical phenomena such as fish swimming, [PAUSE]<br /> insects propelling themselves\
  \ along the water surface, [PAUSE]<br /> drag, [PAUSE] wing tip vortices, [PAUSE]\
  \ and hurricanes. [PAUSE]</p> <p>Before watching this video you should know the\
  \ definition of curl, and how to compute the curl of a vector field.</p> <p>After\
  \ watching this video, you should be able to understand curl as a measurement of\
  \ magnitude and direction of maximum circulation per area, recognize curl in 2-dimensional\
  \ fluid flows, describe the relationship between curl and vorticity, and connect\
  \ vorticity to momentum transfer for a collection of familiar physical phenomena.</p>\
  \ <p>Chapter 1:  Review of curl<br /> Some of my work as a graduate student investigated\
  \ how fish swim.  Identifying the mechanism for how fish propel themselves through\
  \ water relied on an understanding of the curl of the velocity field of fluid created\
  \ by the fish movements.</p> <p>Before we discuss this problem, let&rsquo;s review\
  \ the meaning of the curl first in 2-d, and then in 3-d.<br /> We often think of\
  \ the operations divergence, gradient, and curl together.  This is because they\
  \ are all operations that describe the behavior of multivariable scalar functions\
  \ or vector fields.  Work with a partner to refresh your memory about the physical\
  \ and mathematical descriptions of these operations. [PAUSE]<br /> The divergence\
  \ of a vector field is the scalar measurement of how much a flow field expands or\
  \ compresses near a point.</p> <p>The gradient of a scalar function is a vector\
  \ field. It points in the direction of maximum increase of the function, and the\
  \ magnitude measures the rate of increase.   The curl of a vector field is another\
  \ vector field quantity.  The magnitude measures how much the vector field rotates\
  \ about each point. The direction is normal to the plane of rotation and is determined\
  \ by the right hand rule.<br /> To be more precise about the meaning of curl let&rsquo;s\
  \ discuss the concept of circulation, since curl measures circulation per unit area.\
  \  The circulation of a vector field about a closed loop c is computed by the line\
  \ integral about c of the vector field dotted with the unit tangent to c.</p> <p>To\
  \ find the circulation at a point (x,y), let us consider the circulation around\
  \ a very small square path with side lengths Delta x and Delta y, centered about\
  \ the point.</p> <p>For a 2-dimensional vector field, the curl is defined as the\
  \ circulation per area, in the limit as Delta x and Delta y approach zero.<br />\
  \ Work with a partner to find the magnitude and direction of the curl vector at\
  \ (x,y).  [PAUSE]<br /> Hopefully you obtained the following expression.<br /> We\
  \ just found the limit of circulation per area as Delta x and Delta y approach zero\
  \ in the xy-plane.  But for a 3 dimensional vector field, you can compute this quantity\
  \ in any plane you choose.</p> <p>In particular, we can compute the circulation\
  \ per differential area in the xy-plane, the yz-plane, and the xz-plane.  This will\
  \ give us 3 orthogonal vectors describing the circulation about the z, x, and y\
  \ axes respectively.<br /> When we add these 3 vectors, we obtain an expression\
  \ for the curl in 3D.  The direction is normal to the plane of maximum circulation,\
  \ and the magnitude is the total circulation per area in the limit as the area approaches\
  \ zero.<br /> So now we understand curl.  Can you think of any physical quantities\
  \ that are described using curl?  [PAUSE]</p> <p>You are probably familiar with\
  \ the use of curl in electro-magnetism, which describes relationships between electric\
  \ fields and magnetic fields through Maxwell&rsquo;s equations.   These last two\
  \ equations involving curl are the differential forms of Faraday&rsquo;s Law and\
  \ Amp\xE8re&rsquo;s Law with Maxwell&rsquo;s correction term.</p> <p>Chapter 2:\
  \ Vorticity<br /> We often use curl to describe fluid flow, such as the flow of\
  \ water or air.   Vorticity is simply a term for the vector field defined as the\
  \ curl of the velocity field.  In this section, we are going to restrict our attention\
  \ to the vorticity in 2 dimensional fluid flows.  So here, vorticity measures how\
  \ much the fluid rotates about the z-axis at a given point. <br /> How might we\
  \ measure vorticity?  One way is to put a rigid body into a flow.  For our rigid\
  \ body, we use a paddle wheel with a vector arrow on top.  The paddle wheel is made\
  \ of two orthogonal components.  And there is an arrow on top to help designate\
  \ the orientation of the paddle wheel. <br /> By assuming that the paddle wheel\
  \ moves with the flow field, we can measure the existence of vorticity by placing\
  \ the paddle wheel into a velocity field. If the arrow rotates, there is vorticity.\
  \  Let&rsquo;s look at some examples.<br /> This cylinder has been rotating for\
  \ a long time, so the entire body of water rotates as if it is a solid body. <br\
  \ /> The paddle wheel moves with the flow.  You can see that the velocity field\
  \ has vorticity because the arrow is rotating clockwise.<br /> In this example,\
  \ the velocity field is zero at the center of the tank, and increases linearly from\
  \ the center towards the edge.</p> <p>Thus the velocity of the outside edge of the\
  \ paddle wheel is larger than the velocity of the inside edge.  So the paddle has\
  \ an angular velocity, which rotates the arrow clockwise. <br /> Let&rsquo;s look\
  \ at another example.  Here you see the flow created by injecting a small stream\
  \ of water tangentially at the edge of a circular tub.  The water flows in nearly\
  \ concentric circles and eventually drains out a small hole at the center. <br />\
  \ Let&rsquo;s see what happens when the paddle wheel is placed in the flow field.\
  \ You notice that even though the paddle wheel is circulating about the center of\
  \ the tub, the arrow always points in the same direction. So this region of flow\
  \ field is free of vorticity.</p> <p>Let&rsquo;s try to understand why this is true.\
  \  The velocity vectors of this flow field are tangent to nearly concentric circles.\
  \  The magnitude of the velocity is largest near the center, and decreases towards\
  \ the edge.</p> <p>Let&rsquo;s zoom in onto the effects of this velocity field on\
  \ the paddle wheel.  We draw one paddle yellow with an arrowhead, and the other\
  \ blue.  We draw the velocity vector at each paddle end point.</p> <p>How can you\
  \ explain the fact that after a short time, the paddle wheel circulates about the\
  \ center of the drain, but there is no rotation of the arrow at all?  [PAUSE]  \
  \ Considering only the normal component of the velocity field at the surface of\
  \ the blue paddle, we can see that the paddle would have a counterclockwise angular\
  \ velocity.  Considering the velocity field at the surface of the yellow paddle,\
  \ which has greater magnitude on the inside edge, we can see that the paddle would\
  \ have a clockwise angular velocity.  Because these two angular velocities are equal\
  \ and opposite, there is no net rotation.</p> <p>Of course, as the paddle wheel\
  \ approaches the center, things change.  The vorticity is very large in this region\
  \ of the flow field. We&rsquo;ve just looked at two examples of circulating flows,\
  \ with different velocity fields.  Let&rsquo;s consider something a bit different\
  \ now.  Consider a flow down a long straight channel?</p> <p>Do you expect the paddle\
  \ wheel to spin or not? [PAUSE]   Observe that the paddle wheel _does_ rotate as\
  \ it flows through the channel.  Let&rsquo;s see why.</p> <p>The fluid cannot slip\
  \ along the edges, so the velocity along the boundary of the channel is zero.  At\
  \ the center of the channel, the flow moves with some nonzero velocity.  Because\
  \ the velocity field is continuous, the velocity vectors decrease continuously as\
  \ you approach the wall.</p> <p>Pause the video and explain why the paddle wheel\
  \ rotates. [PAUSE] <br /> Chapter 3: Examples of vorticity In a fluid flow, vorticity\
  \ is a sign of momentum transfer. <br /> There are several instances of vorticity\
  \ being present in tandem with momentum transfer that you may be familiar with already:\
  \ such as drag forces and propulsion forces.</p> <p>A cylinder moving through a\
  \ fluid experiences a drag force opposing the motion.  The motion of the cylinder\
  \ creates vortices in its wake.</p> <p>These vortices cause the fluid in the wake\
  \ to follow the cylinder.  Thus momentum is imparted to the fluid, and the drag\
  \ force is the reaction to the rate of change of the fluid&rsquo;s momentum. <br\
  \ /> However, when a fish swims, it overcomes the drag force to propel itself through\
  \ the water.  How does this work?   The answer again is vorticity.</p> <p>In this\
  \ experiment, a laser sheet illuminates a plane of water in a fish tank.  The water\
  \ contains tracer particles, and a camera below the tank records the video.   Observe\
  \ the swirling motion of particles near the tail of the fish.  In order to understand\
  \ this flow, we use software to analyze this video.</p> <p>The program analyzes\
  \ the time and position of the tracer particles and determines the velocity field\
  \ of the fluid.</p> <p>The direction and magnitude of the curl of this velocity\
  \ field is shown by the colored regions&mdash;red denotes counterclockwise vorticity\
  \ and blue denotes clockwise vorticity.  The intensity of the color depicts the\
  \ relative magnitude of the curl at each point. As the fish swims, it experiences\
  \ a drag force on its body.  In order to swim at a constant speed, the fish must\
  \ negate this drag force with a propulsive force.  Observe that the fish sheds vortices,\
  \ but the direction of circulation of these vortices is opposite to the direction\
  \ of the vortices in the cylinder case.  [PAUSE]  Here the fish imparts momentum\
  \ to the water opposite to its direction of motion.   This provides the requisite\
  \ propulsive force. Using these ideas about curl, engineers at MIT developed a robotic\
  \ fish.  Here we see the wake of the robotic fish visualized using florescent dye.\
  \     By changing the motion of the robotic fish, engineers can analyze the vorticity\
  \ in the wake, allowing them to understand what movements create the most efficient\
  \ propulsion.   To Review:</p> <ul>     <li>The curl of a vector field is a vector\
  \ field that measures the circulation per unit area about each point.</li>     <li>The\
  \ direction of the curl is normal to the plane of maximum rotation.</li>     <li>Vorticity\
  \ is simply the curl of a velocity field.</li>     <li>You can recognize vorticity\
  \ in a 2-dimensional velocity field by observing the rotation of a paddle wheel\
  \ placed in the flow.</li>     <li>There are a variety of familiar physical phenomena\
  \ where the vorticity implies a momentum transfer, such as drag and propulsion.</li>\
  \ </ul>"
type: course
uid: 6200df4a290e4587c8bf27bb18171bee

---
None