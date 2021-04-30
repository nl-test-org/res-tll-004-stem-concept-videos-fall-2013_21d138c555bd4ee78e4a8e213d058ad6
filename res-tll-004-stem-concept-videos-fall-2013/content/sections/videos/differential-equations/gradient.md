---
about_this_resource_text: <h2 class="subhead">Summary</h2> <p>This video leads students
  through an understanding of how the gradient is used in Fick's first law to describe
  a relationship between the flux of particles and the concentration of particles.
  This relationship is explored by modeling the process of diffusion using random
  walkers. Finally, this law is applied to other real-world scenarios involving solid
  state diffusion and thermodynamics.</p> <h2 class="subhead">Learning Objectives</h2>
  <p>After watching this video students should be able to:</p> <ul>     <li>Recognize
  that the gradient vector points in the direction of maximum slope of a scalar function
  with magnitude equal to that slope.</li>     <li>Describe the physicality of Fick&rsquo;s
  first law as it applies to concentration gradients.</li> </ul> <p>&nbsp;</p> <p>Funding
  provided by the Singapore University of Technology and Design (SUTD)</p> <p>Developed
  by the Teaching and Learning Laboratory (TLL) at MIT for SUTD</p> <p>MIT &copy;
  2012</p>
course_id: res-tll-004-stem-concept-videos-fall-2013
embedded_media:
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/gradient/id765926614?i=194533716
  parent_uid: d100e428782cb1631e5867fd7984f6d7
  title: Video-iTunes U-MP4
  type: Video
  uid: 325437891308d9ccbfeafe8dc3fd0ff0
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MITRES.TLL-004F13/MITRES_TLL-004F13_gradient_intro_300k.mp4
  parent_uid: d100e428782cb1631e5867fd7984f6d7
  title: Video-Internet Archive-MP4
  type: Video
  uid: a81d079a1e4fbfc76dc0bf26b436ee61
- id: Video-YouTube-Stream
  media_location: mDvty90jENM
  parent_uid: d100e428782cb1631e5867fd7984f6d7
  title: Video-YouTube-Stream
  type: Video
  uid: 0dd944bcd03894bccddae1a1f401e6c7
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/mDvty90jENM/default.jpg
  parent_uid: d100e428782cb1631e5867fd7984f6d7
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e9451ff0ccb64726ae6a992aef6549ce
- id: 3Play-3PlayYouTubeid-MP4
  media_location: mDvty90jENM
  parent_uid: d100e428782cb1631e5867fd7984f6d7
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: e90d838dad0d75aa6c5cb127c8870664
- id: mDvty90jENM.srt
  parent_uid: d100e428782cb1631e5867fd7984f6d7
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/differential-equations/gradient/mDvty90jENM.srt
  title: 3play caption file
  type: null
  uid: db87f99becc1cb32865800a2cd5fc28d
- id: mDvty90jENM.pdf
  parent_uid: d100e428782cb1631e5867fd7984f6d7
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/differential-equations/gradient/mDvty90jENM.pdf
  title: 3play pdf file
  type: null
  uid: 577f3ea3df4ef5dbf3e0ada44285257f
- id: Caption-3Play YouTube id-SRT
  parent_uid: d100e428782cb1631e5867fd7984f6d7
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 363f36200ced6f61dca70d2c1e297eba
- id: Transcript-3Play YouTube id-PDF
  parent_uid: d100e428782cb1631e5867fd7984f6d7
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 4d0d67115599eba3eeb27d929282246b
inline_embed_id: 76361145gradient36114403
layout: video
order_index: null
parent_uid: 7e7fcfb2130297e43da2fb9fcaab47f4
related_resources_text: <p>Instructor Guide</p> <p><a target="_blank" href="./resolveuid/d213b6b2fda4b9d7e98539152c725e92">Gradient
  Instructor Guide (PDF)</a></p> <p>&nbsp;</p>
short_url: gradient
technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/differential-equations/gradient
template_type: Tabbed
title: Gradient
transcript: "<p><span m='3330'> How long after swallowing a pill does it takes for\
  \ a drug to enter your bloodstream? How</span> <span m='8250'>long does it take\
  \ for hot molten glass to cool? In this video, we'll see how the gradient</span>\
  \ <span m='13599'>helps us model molecular and thermal diffusion.</span> <span m='17110'>This\
  \ video is part of the Differential Equations video series. Laws that govern a system's</span>\
  \ <span m='21270'>properties can be modeled using differential equations.</span>\
  \ <span m='24570'>Hi, my name is Tom Peacock, and I'm a Professor of Mechanical\
  \ Engineering here at MIT. Today</span> <span m='31689'>I'd like to talk to you\
  \ a little bit about the gradient.</span> <span m='35479'>Partial differential equations\
  \ describe the world around us. And partial differential</span> <span m='40120'>equations\
  \ often contain grad, div, and/or curl terms. In order to use these operations</span>\
  \ <span m='47330'>to describe physical phenomena, the first step is to understand\
  \ what each mathematical</span> <span m='52400'>process means geometrically and\
  \ how it behaves in different examples.</span> <span m='57610'>The gradient is an\
  \ operation that takes in a scalar function and outputs a vector field.</span> <span\
  \ m='64250'>Many scalar quantities such as temperature and density have time derivatives\
  \ that exhibit</span> <span m='69850'>both a magnitude and a direction. Therefore\
  \ it makes sense that we would need an operation</span> <span m='75789'>that turns\
  \ scalar functions into vector fields.</span> <span m='79750'>Before watching this\
  \ video, you should be familiar with the definition of the gradient,</span> <span\
  \ m='84890'>and its connection to the directional derivative.</span> <span m='88030'>After\
  \ watching this video, you will be able to</span> <span m='90810'>Recognize that\
  \ the gradient vector points in the direction of the maximum slope of a</span> <span\
  \ m='95700'>scalar function and has magnitude equal to that slope.</span> <span\
  \ m='100310'>Describe the physicality of Fick's First Law as it applies to concentration\
  \ gradients.</span> <span m='106880'>[Pause]</span> <span m='109190'>Imagine what\
  \ happens when you swallow a pill. Usually the pill contains an active ingredient,</span>\
  \ <span m='115090'>or drug, and a mixture of other inactive ingredients, such as\
  \ binders, flavoring agents, etc. Some</span> <span m='123360'>pills are coated\
  \ to make the pill easier to swallow and to control the release of the</span> <span\
  \ m='127440'>drug. When you swallow the pill, it starts to dissolve.</span> <span\
  \ m='132380'>It is usually desired for there to be a constant and predictable delivery\
  \ rate of drug to the</span> <span m='137120'>body, that is that the diffusion of\
  \ drug reaches steady state. We need to understand what this</span> <span m='144540'>steady\
  \ state amount is to ensure that we are delivering the desired dose.</span> <span\
  \ m='150110'>The equation that describes diffusion is the partial derivative of\
  \ c with respect to time</span> <span m='156579'>is equal to D del squared c.</span>\
  \ <span m='160800'>where c is concentration, and D is the diffusion coefficient,\
  \ which we will assume is constant.</span> <span m='167790'>But where does this\
  \ come from? In order to understand this completely, we will need to</span> <span\
  \ m='172459'>combine the divergence and gradient to have a full description of the\
  \ del squared term.</span> <span m='179170'>In this video, our goal is to understand\
  \ how flux is related to the gradient of the concentration.</span> <span m='186170'>[Pause]</span>\
  \ <span m='187340'>Let's review the properties and meaning of the gradient. The\
  \ gradient is a local property</span> <span m='192610'>of a function. That is, it\
  \ depends only on points that are near a point of interest.</span> <span m='199630'>Given\
  \ a function f(x,y) of two variables, we can represent this function as a surface</span>\
  \ <span m='205730'>in 3-dimensions z=f(x,y)</span> <span m='211900'>Or as a collection\
  \ of level curves.</span> <span m='214930'>The gradient at a point (x,y) can be\
  \ determined by finding a vector in the tangent plane to</span> <span m='221959'>z=f(x,y)\
  \ at (x,y) that points in the direction of the steepest slope.</span> <span m='229579'>The\
  \ gradient vector is a vector in the x,y-plane. The direction is found by projecting\
  \ the vector</span> <span m='236190'>in the tangent plane down onto the xy-plane.</span>\
  \ <span m='241580'>The magnitude of the gradient is the slope of that vector in\
  \ the tangent plane.</span> <span m='247849'>This vector is always perpendicular\
  \ to the level curve because along the level curve,</span> <span m='253160'>the\
  \ function is constant.</span> <span m='259659'>What is the 1-dimensional analogue\
  \ of the gradient?</span> <span m='263559'>Take the tangent line to the graph of\
  \ the function. Point a vector up the hill, then</span> <span m='270300'>project\
  \ down. The direction is either positive or negative. The magnitude is the slope\
  \ of</span> <span m='277960'>the graph. But 1-dimensional vectors are scalars. So\
  \ the gradient is simply the derivative.</span> <span m='286469'>And we already\
  \ know that the derivative is a local property of a function: because it</span>\
  \ <span m='293139'>is a limit, it depends only on points in a small region near\
  \ the point at which we are</span> <span m='298659'>looking for the derivative.</span>\
  \ <span m='300699'>What happens in 3-dimensions? It is somewhat difficult to represent\
  \ a 3-dimensional function.</span> <span m='307619'>The best way to represent such\
  \ a function is through a collection of level surfaces.</span> <span m='314759'>The\
  \ gradient field can be computed at every point on the level surface. We know that\
  \ the</span> <span m='321029'>gradient vector is a 3-dimensional vector that is\
  \ normal to this surface. The magnitude</span> <span m='326520'>of the gradient\
  \ vector measures the steepest increase of a shape we can't imagine because</span>\
  \ <span m='332558'>it is 4-dimensional.</span> <span m='333099'>[Pause]</span> <span\
  \ m='333169'>Let's get back to our tablet diffusion example. We aren't going to\
  \ attack the entire problem</span> <span m='334240'>all at once. The first thing\
  \ that we want to try to understand is the movement of drug</span> <span m='335449'>molecules\
  \ through any given surface area per unit time, i.e. we want to understand the</span>\
  \ <span m='336449'>flux from the pill into its surroundings.</span> <span m='336930'>In\
  \ order to better understand this process, we begin with a demo. Here you see a\
  \ tank</span> <span m='341839'>of water and a drop of dye. Initially, the dye is\
  \ concentrated in a single droplet at</span> <span m='348180'>the center of the\
  \ tank. Over time, the dye particles move away from the center, until</span> <span\
  \ m='353169'>a point in time when the process reaches steady state.</span> <span\
  \ m='356990'>In order to model what is happening at the atomic level in this demo,\
  \ we are going to</span> <span m='361259'>start by making a 1-dimensional discrete\
  \ model. This one-dimensional model will be simpler,</span> <span m='369009'>and\
  \ allow us to describe the flux of particles more easily. Then we will extend the\
  \ model</span> <span m='375399'>to 2-dimensions, creating a discrete time step simulation\
  \ to determine the equation</span> <span m='380740'>for flux. Then we will look\
  \ at our 3 dimensional demo and discuss the equation for flux.</span> <span m='385789'>In\
  \ the 1-dimensional model, we are going to model the particles of dye as random\
  \ walkers</span> <span m='391389'>on a line. Each random walker has an equal probability\
  \ of moving one step of length Delta</span> <span m='398159'>x to the right or to\
  \ the left during a time step Delta t. The walkers move independently</span> <span\
  \ m='406529'>of each other.</span> <span m='408159'>We make an assumption that Delta\
  \ x and Delta t are both small.</span> <span m='414929'>In order to understand how\
  \ the particles are moving, we want to understand the flux through</span> <span\
  \ m='420110'>any given point.</span> <span m='421800'>Recall that flux is flow per\
  \ unit \"area\" per unit time. Our random walk model is one dimensional,</span>\
  \ <span m='431710'>so we will define the flow of particles through a single point\
  \ over a time step Delta t to</span> <span m='437809'>be flux.</span> <span m='439550'>While\
  \ we can look at the flux through any point, for mathematical convenience, let us</span>\
  \ <span m='444800'>determine the flux through the point x + Delta x over 2 at time\
  \ t. This point is half way</span> <span m='451909'>between the point x and x+delta\
  \ x. Because of the hypotheses of our random walk, any</span> <span m='458159'>particle\
  \ that is within a step length Delta x to the left or the right of x + Delta x</span>\
  \ <span m='464550'>over 2 has a \xBD probability of flowing through the point during\
  \ the next time step. So in</span> <span m='471039'>order to find the flux, the\
  \ first step is to determine many particles are within our</span> <span m='476800'>step\
  \ distance Delta x from the point x + Delta x over 2.</span> <span m='483050'>Let\
  \ the concentration of particles be denoted by the function c(x,t), which is the\
  \ number</span> <span m='490119'>of particles per unit length at a time t. To find\
  \ the number of particles to the left</span> <span m='496959'>of x + Delta x over\
  \ 2, we could integrate the concentration function over the interval</span> <span\
  \ m='503509'>of length Delta x centered about the point x. However, because we have\
  \ assumed that Delta</span> <span m='510709'>x is small, we can approximate the\
  \ concentration function by the value of the concentration</span> <span m='517830'>at\
  \ x for the whole interval. So the number of particles on the interval of length\
  \ centered</span> <span m='524810'>about the point x can be approximated by c(x,t)\
  \ times Delta x . The number of particles on</span> <span m='533820'>the interval\
  \ of length Delta x centered about the point x + Delta x is approximately c(x+Delta</span>\
  \ <span m='542150'>x, t) times Delta x particles.</span> <span m='548560'>We assume\
  \ that any particle has 1/2 probability of moving one step to the left or the right.</span>\
  \ <span m='555190'>Thus the flux through our point is given by one half times the\
  \ number of particles to</span> <span m='560880'>the left minus one half times the\
  \ number of particles to the right a time t. We divide</span> <span m='568320'>the\
  \ entire expression by the time step, which is the unit of time over which we are\
  \ looking</span> <span m='573990'>at the motion of particles.</span> <span m='576580'>To\
  \ dig a little deeper into this equation, we can take a Taylor expansion of our\
  \ concentration</span> <span m='582010'>function c(x + Delta x, t) about x, holding\
  \ t fixed. This gives us the following expression,</span> <span m='592950'>which\
  \ is a polynomial in Delta x with coefficients given by multiples of sequentially\
  \ higher</span> <span m='598930'>partial derivatives of the concentration function\
  \ c.</span> <span m='603160'>Our equation for flux becomes this seemingly more complicated\
  \ equation.</span> <span m='608290'>However, if we make an assumption that Delta\
  \ x grows proportionally to the square root</span> <span m='618500'>of Delta t,\
  \ in other words that Delta x squared is proportional to Delta t:</span> <span m='623130'>This\
  \ simplifies the expression for flux because only the first term has a significant\
  \ contribution,</span> <span m='632860'>and we are left with the following expression\
  \ for flux:</span> <span m='638870'>[pause]</span> <span m='639530'>You can do a\
  \ table top experiment by placing a small drop of dye in a narrow test tube</span>\
  \ <span m='644970'>and measuring the change in height of dye with respect to the\
  \ change in time in order</span> <span m='649910'>to verify that the assumption\
  \ we made is valid.</span> <span m='654250'>Rewriting the constant term in front\
  \ as some diffusion constant D, this equation is commonly</span> <span m='660990'>written\
  \ as flux is equal to negative D times the partial derivative of c with respect\
  \ to</span> <span m='667880'>x.</span> <span m='669100'>The negative sign in this\
  \ equation says that the direction of net flux goes from a region</span> <span m='675500'>of\
  \ high concentration to a region of low concentration, in the opposite direction\
  \ as the concentration</span> <span m='682580'>gradient. Why is this? If there are\
  \ more particles on one side of a point than the other, we</span> <span m='691590'>suspect\
  \ half of them flow through the point on either side, so the net flow through the</span>\
  \ <span m='698470'>point is away from the highest concentration.</span> <span m='700700'>This\
  \ behavior is consistent with what we saw with the dye in the fish tank.</span>\
  \ <span m='703010'>Now we want to extend this to 2-dimensions. Here we have modeled\
  \ a system of 2000 particles</span> <span m='711340'>walking randomly in the plane.\
  \ Each particle can move a unit distance away from its current</span> <span m='718560'>location\
  \ in any direction with equal probability. A profile of the concentration at each\
  \ time</span> <span m='726610'>step is displayed to the right.</span> <span m='728690'>We\
  \ change the view of the concentration to be contour lines, and add some more particles</span>\
  \ <span m='735650'>to increase the accuracy of our computation in order to add in\
  \ the flux vector. In 2D,</span> <span m='743430'>the flux is a flow per length\
  \ per unit time, and is a vector quantity. Observe that the</span> <span m='751380'>flux\
  \ is everywhere perpendicular to the level sets, or contours of the concentration\
  \ map,</span> <span m='758560'>and it points away from the highest concentration.\
  \ In other words, this simulation suggests that</span> <span m='765150'>the flux\
  \ points in the direction of the negative gradient of the concentration.</span>\
  \ <span m='774180'>The equation that describes this says that flux J is equal to\
  \ some constant, which we</span> <span m='782550'>will call D, times the negative\
  \ gradient of the concentration: Compare to the equation</span> <span m='788410'>we\
  \ had in the 1-dimensional example. Here the derivative is replaced by the gradient</span>\
  \ <span m='794770'>because the derivative is the 1-dimensional analogue of the gradient.</span>\
  \ <span m='798460'>Now let's look back to our 3-dimensional example. The flow profile\
  \ seems to follow the same</span> <span m='805380'>basic principles.</span> <span\
  \ m='806490'>Experiments and observations have shown that the flux of particles\
  \ per unit area is determined</span> <span m='819270'>by some constant times the\
  \ negative gradient of concentration, just as in our discrete</span> <span m='842580'>2-dimensional\
  \ model:</span> <span m='849040'>This equation is one form of Fick's first law.\
  \ It says that flux points along the negative</span> <span m='862330'>gradient of\
  \ the concentration.</span> <span m='863820'>It turns out that this equation describes\
  \ the flux of many familiar quantities. Let's</span> <span m='872279'>consider some\
  \ examples:</span> <span m='874260'>When students exit a classroom when class ends\
  \ shows the flux of people through the</span> <span m='884110'>doorway points away\
  \ from the highest concentration of students.</span> <span m='898290'>The second\
  \ law of thermodynamics says that heat flows from high to low temperatures.</span>\
  \ <span m='903390'>This says that the flux is proportional (perhaps non-uniformly)\
  \ to the negative temperature gradient.</span> <span m='981790'>Be aware that this\
  \ is just one form of Fick's first law. The most general form says that</span> <span\
  \ m='988520'>flux is proportional to the negative gradient of the chemical potential.</span>\
  \ <span m='994800'>You may see the equation in this form in later courses. In all\
  \ of the examples that we have</span> <span m='1003690'>considered in this video,\
  \ the gradient of the concentration and the gradient of the</span> <span m='1008880'>chemical\
  \ potential pointed in the same direction.</span> <span m='1013330'>To review:</span>\
  \ <span m='1015470'>The gradient is a vector quantity that points in the direction\
  \ of the maximum slope of a</span> <span m='1020950'>scalar function.</span> <span\
  \ m='1022850'>Fick's first law says that flux points along the negative gradient\
  \ of concentration.</span> <span m='1028609'>In order to understand Fick's First\
  \ Law, we first considered models in 1-d and 2-d, before</span> <span m='1035049'>trying\
  \ to understand the description in 3-d.</span> </p>"
type: course
uid: d100e428782cb1631e5867fd7984f6d7

---
None