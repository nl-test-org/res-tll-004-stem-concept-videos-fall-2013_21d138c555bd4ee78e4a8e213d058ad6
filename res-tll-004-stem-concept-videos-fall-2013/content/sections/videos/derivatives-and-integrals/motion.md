---
about_this_resource_text: <h2 class="subhead">Summary</h2><p>This video uses robotics
  as a context for describing rigid body motion and equations of constraint. Illustrative
  video clips are drawn from the robotics competition in MIT&rsquo;s 2.007 &quot;Design
  and Manufacturing&quot; course. The video describes both linear and angular motion.</p><h2
  class="subhead">Learning Objectives</h2><p>After watching this video students will
  be able to:</p><ul><li>Explain what is meant by the phrase &quot;rigid body.&quot;</li><li>Describe
  restrictions on the motion of a object by using equations of constraint.</li><li>Use
  derivatives and integrals to connect different measurements of motion.</li></ul><p>Funding
  provided by the Singapore University of Technology and Design (SUTD)</p><p>Developed
  by the Teaching and Learning Laboratory (TLL) at MIT for SUTD</p><p>MIT &copy; 2012</p>
course_id: res-tll-004-stem-concept-videos-fall-2013
embedded_media:
- id: MITRES_TLL-004F13_Motn_IG.pdf
  parent_uid: 5e13ca2a4e20879bec4a7236d196e37a
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/derivatives-and-integrals/motion/MITRES_TLL-004F13_Motn_IG.pdf
  title: Motion Instructor Guide
  type: null
  uid: f750ea958f32507f35591d16317e2f9d
- id: Video-YouTube-Stream
  media_location: zRslv221V9c
  parent_uid: 5e13ca2a4e20879bec4a7236d196e37a
  title: Video-YouTube-Stream
  type: Video
  uid: edba33fcb54521dccfcb81b37dae4b89
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/zRslv221V9c/default.jpg
  parent_uid: 5e13ca2a4e20879bec4a7236d196e37a
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 9264dae89ef2211f84f6d78983c659a8
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id765926614
  parent_uid: 5e13ca2a4e20879bec4a7236d196e37a
  title: Video-iTunes U-MP4
  type: Video
  uid: e57296c92f57cca619f070381ed755e4
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MITRES.TLL-004F13/MITRES_TLL-004F13_motion_300k.mp4
  parent_uid: 5e13ca2a4e20879bec4a7236d196e37a
  title: Video-Internet Archive-MP4
  type: Video
  uid: ff2e5688fb1dc024ca19b990c6789b12
- id: 3Play-3PlayYouTubeid-MP4
  media_location: zRslv221V9c
  parent_uid: 5e13ca2a4e20879bec4a7236d196e37a
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: fa5d2723cb239a8a4108c8446e1d244c
- id: zRslv221V9c.srt
  parent_uid: 5e13ca2a4e20879bec4a7236d196e37a
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/derivatives-and-integrals/motion/zRslv221V9c.srt
  title: 3play caption file
  type: null
  uid: ad51ee41efb5b9b8120b1513e26a7b10
- id: zRslv221V9c.pdf
  parent_uid: 5e13ca2a4e20879bec4a7236d196e37a
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/derivatives-and-integrals/motion/zRslv221V9c.pdf
  title: 3play pdf file
  type: null
  uid: 76560b01f099801c07c1d64a98c25483
- id: Caption-3Play YouTube id-SRT
  parent_uid: 5e13ca2a4e20879bec4a7236d196e37a
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 9f10542b34ef4588a6fbfbdf348305ee
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 5e13ca2a4e20879bec4a7236d196e37a
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: bacbcc93be665c1fa4f4dd0090727a2b
inline_embed_id: 35239596motion58934414
layout: video
order_index: null
parent_uid: ee1c17b93698e35b3fca8ea85cec751a
related_resources_text: <p>Instructor Guide</p> <p><img alt="This resource may not
  render correctly in a screen reader." src="/images/inacessible.gif" /><a href="./resolveuid/f750ea958f32507f35591d16317e2f9d"
  target="_blank">Motion Instructor Guide (PDF)</a></p>
short_url: motion
technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/derivatives-and-integrals/motion
template_type: Tabbed
title: Motion
transcript: "<p><span m='3959'> How did MIT undergraduates design a robot to lift\
  \ a small model police car and place</span> <span m='9040'>it on top of a model\
  \ of MIT's great dome? Calculus! In this video, we'll use calculus</span> <span\
  \ m='15309'>to describe the motion of rigid bodies and see how these concepts are\
  \ used in the field</span> <span m='20179'>of robotics.</span> <span m='22839'>This\
  \ video is part of the Derivatives and Integrals video series. Derivatives and integrals</span>\
  \ <span m='27550'>are used to analyze the properties of a system. Derivatives describe\
  \ local properties of systems,</span> <span m='33329'>and integrals quantify their\
  \ cumulative properties.</span> <span m='36429'>Hello. My name is Dan Frey. I am\
  \ a professor in the Mechanical Engineering department at</span> <span m='41870'>MIT,\
  \ and today I'll be talking with you about the motion of rigid bodies--both translation</span>\
  \ <span m='48309'>and rotation.</span> <span m='50190'>In order to understand this\
  \ video you should be very comfortable with linear motion, including</span> <span\
  \ m='56170'>position, velocity, and acceleration. You will want to know how to turn\
  \ measurements</span> <span m='62039'>in polar coordinates into measurements in\
  \ Cartesian coordinates. You should also know</span> <span m='67180'>enough introductory\
  \ calculus to apply the chain rule.</span> <span m='71479'>After watching this video\
  \ you should be able to explain what is meant by the phrase \"rigid</span> <span\
  \ m='76890'>body.\" You should be able to describe restrictions on the motion of\
  \ an object by using constraint</span> <span m='83180'>equations. Finally, you should\
  \ be able to use derivatives and integrals to connect different</span> <span m='88619'>mathematical\
  \ descriptions of rigid body motion.</span> <span m='93100'>Our primary examples\
  \ today will be robots. Let's look at how basic ideas of motion are</span> <span\
  \ m='99640'>used in the field of robotics. Here you can see some footage from a\
  \ robotics competition</span> <span m='105350'>at MIT. The competition is part of\
  \ a Mechanical Engineering course, number 2.007.</span> <span m='113000'>One typical\
  \ task that robots perform is to grab something, pick it up, and move it. This</span>\
  \ <span m='119590'>robot uses a gripper, at the end of the arm, to pick up objects.</span>\
  \ <span m='125210'>One of the difficulties in programming a robot arm is that we\
  \ typically have no direct measurement</span> <span m='131030'>of where that gripper\
  \ is. There's usually no convenient sort of \"position meter\" that</span> <span\
  \ m='136610'>could tell its location. Instead we might determine the location for\
  \ the base of the</span> <span m='141910'>arm, and we can measure the angles for\
  \ different parts of the arm. We need to use the measurements</span> <span m='148410'>that\
  \ we can make in order to determine the location of the gripper.</span> <span m='169350'>This\
  \ is made easier by the concept of a \"rigid body.\" Rigid bodies can translate\
  \ and rotate,</span> <span m='176820'>but they do not bend, stretch, or twist. In\
  \ mathematical terms, the distance between any</span> <span m='183900'>two points\
  \ in the object does not change.</span> <span m='189010'>Rigid bodies are idealizations\
  \ -- to simplify our work, we imagine that we are working with</span> <span m='194730'>objects\
  \ that do not deform. This idealization works best when the object only experiences</span>\
  \ <span m='201260'>low amounts of force. Higher amounts of force can lead to objects\
  \ deforming or breaking,</span> <span m='207060'>depending on the object. The robot\
  \ we saw earlier is a good example</span> <span m='211620'>of a rigid body. You\
  \ can see in this video that as our robot moves, its pieces do not</span> <span\
  \ m='218340'>bend or distort noticeably, so we can treat each piece as a rigid body.\
  \ We could use the</span> <span m='225220'>definition of a rigid body to help us\
  \ determine the location of points on that robot.</span> <span m='231440'>This robot,\
  \ on the other hand, has a less sturdy frame. You can see the arm flex as</span>\
  \ <span m='237050'>the robot moves. We might not want to treat this arm as a rigid\
  \ body. Let's try to solve</span> <span m='245540'>a problem involving a rigid body.\
  \ Here is a very simple robot arm. It has a \"joint\"</span> <span m='250900'>on\
  \ the left that can tilt up and down, and a piston that can extend its arm. In addition,</span>\
  \ <span m='257139'>this part of the piston can be considered a rigid body, so its\
  \ length will be a constant.</span> <span m='263590'>Here is a task for you: describe\
  \ the acceleration of the gripper at the end of the arm.</span> <span m='270430'>First,\
  \ set the origin for your coordinate system. Then, write an expression for the</span>\
  \ <span m='277349'>x and y position of the gripper in terms of the quantities shown\
  \ here.</span> <span m='282490'>Once you have that position, use derivatives to\
  \ find the velocity and the acceleration</span> <span m='287610'>of the gripper.</span>\
  \ <span m='290050'>Pause the video here to carry out your calculations. Let's take\
  \ a look at the answer. First, we</span> <span m='301159'>need to choose an origin.\
  \ Let's choose an arbitrary location as the origin of our coordinate</span> <span\
  \ m='306360'>system. Our robot's joint may be moving, so we will use a pair of functions\
  \ x sub j of</span> <span m='312740'>time and y sub j of time to describe its location.\
  \ X sub j will be the horizontal distance from</span> <span m='320080'>our origin\
  \ to the joint, and y sub j will be the vertical distance.</span> <span m='325110'>We\
  \ can use derivatives of these functions to describe any relative movement that\
  \ the</span> <span m='329800'>joint has when compared with our coordinate system,\
  \ such as velocity or acceleration.</span> <span m='335620'>This slide shows just\
  \ the X components of the answer, with the value x sub j indicating</span> <span\
  \ m='341889'>the location of the joint. You can see that the expressions can easily\
  \ become complicated</span> <span m='347139'>if both s and theta change at the same\
  \ time. One reason that we want to know the acceleration</span> <span m='354740'>is\
  \ because some objects respond poorly to a high acceleration. Here you can see a\
  \ different</span> <span m='360080'>sort of robot arm lifting a car. Instead of\
  \ a gripper, these two robots use a forklift</span> <span m='365849'>design. Their\
  \ arms must move very gently, especially as they slow down, or the car will</span>\
  \ <span m='370969'>fall off. The arms are capable of moving more quickly, but the\
  \ robot's designers have programmed</span> <span m='378090'>it to use a lower acceleration.</span>\
  \ <span m='381310'>This leads us to a discussion of constraints. This section will\
  \ have a few examples, as</span> <span m='387080'>well as several opportunities\
  \ for you to practice. Be ready to pause the video.</span> <span m='393949'>Constraints\
  \ are any sort of restriction on a situation. When they can be expressed mathematically,</span>\
  \ <span m='399349'>we refer to Equations of Constraint. These describe the physical\
  \ connection between two</span> <span m='405490'>or more rigid bodies.</span> <span\
  \ m='407779'>Constraint equations are useful because they link one variable to another\
  \ in a way that</span> <span m='412259'>reduces the total number of variables in\
  \ a problem. This helps to make otherwise impossible</span> <span m='417779'>problems\
  \ solvable. Constraint equations are used throughout physics and mechanical engineering.</span>\
  \ <span m='424069'>Some fields refer to a similar idea called \"degree of freedom\
  \ analysis.\"</span> <span m='430240'>Here is a classic example of a situation with\
  \ a constraint. The car on this roller coaster</span> <span m='435939'>cannot leave\
  \ the tracks. If the track is circular, we can use the equation for a circle to\
  \ constrain</span> <span m='442559'>our movement. We can use this to reduce the\
  \ number of variables in our equations for the</span> <span m='447610'>position\
  \ of the roller coaster. Rather than an equation in x and y, we could have equations</span>\
  \ <span m='453808'>in just x, or just y. We could also use constraints that involve\
  \ the distance along the track</span> <span m='461009'>or another sensible measurement\
  \ for the situation we are investigating.</span> <span m='466029'>It's important\
  \ to note that constraints mean giving up some freedom in our variables. In</span>\
  \ <span m='471620'>our example, we can only specify x or y, not both. Once we choose\
  \ a value for x, there</span> <span m='479689'>are only two y values that will work.</span>\
  \ <span m='483669'>Here's a situation where you can find the equation of constraint.\
  \ A cart is being pulled</span> <span m='489279'>across a flat surface, and the\
  \ wheels turn without slipping\u2014effectively, the wheel</span> <span m='494889'>is\
  \ constrained to move only by rolling and not in any other way: no lifting up, no\
  \ sliding,</span> <span m='501800'>no peeling out. Can you find an equation that\
  \ connects x, the distance the cart has moved,</span> <span m='508309'>to theta,\
  \ the amount that the wheels have turned?</span> <span m='512010'>Pause the video\
  \ here to discuss this in class. Here is an arm that is fairly complex -- it</span>\
  \ <span m='523600'>has many joints. Pause the video and write down the variables\
  \ and constants you would</span> <span m='529820'>use for this robot.</span> <span\
  \ m='537730'>There are three separate angles that must be recorded, as well as the\
  \ extension of the</span> <span m='542780'>arm. There are also three pieces of constant\
  \ length.</span> <span m='549310'>Now we have an opportunity to describe a constraint\
  \ in a complex situation. We could choose, for</span> <span m='556120'>example,\
  \ to constrain the motion of the arm to just the horizontal direction. Because</span>\
  \ <span m='562200'>there are many variables in this situation, there are many possible\
  \ ways to satisfy the</span> <span m='567540'>constraint.</span> <span m='568820'>Write\
  \ an expression for just the vertical position of the gripper in terms of the quantities</span>\
  \ <span m='572890'>shown. Once you have done that, answer this question: how might\
  \ we move the gripper in</span> <span m='579550'>just the horizontal direction?</span>\
  \ <span m='582310'>You should come up with at least two ways that we could do this,\
  \ and describe them mathematically.</span> <span m='588870'>Your teacher will then\
  \ lead the class in a discussion of your answers. Pause the video</span> <span m='593470'>here\
  \ to do this. Here is a simulation of a \"hydrabot\" doing</span> <span m='602060'>exactly\
  \ what you just calculated: moving one end horizontally. You can see that it matches</span>\
  \ <span m='608190'>up quite well with our hypothetical robot. Examine its motion\
  \ closely--is this one of</span> <span m='616280'>the motions you described? Are\
  \ there extra constraints present here? What freedom of</span> <span m='621410'>motion\
  \ did we give up by making our choice?</span> <span m='627030'>Let's review.</span>\
  \ <span m='628630'>Today you used derivatives to find the velocity and acceleration\
  \ of an object based on its</span> <span m='633520'>position.</span> <span m='634200'>You\
  \ also learned the definition of a rigid body: that it does not bend or stretch\
  \ when</span> <span m='639300'>force is applied.</span> <span m='640600'>Finally,\
  \ you saw that constraint equations can reduce the total number of equations in</span>\
  \ <span m='645170'>a system, thus making problems easier to solve. I hope you enjoyed\
  \ seeing some applications</span> <span m='651640'>of basic motion concepts. Good\
  \ luck in your further investigation of physics and engineering!</span> </p>"
type: course
uid: 5e13ca2a4e20879bec4a7236d196e37a

---
None