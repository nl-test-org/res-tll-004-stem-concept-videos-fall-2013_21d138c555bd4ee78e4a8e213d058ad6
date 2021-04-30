---
about_this_resource_text: <h2 class="subhead">Summary</h2> <p>This video leads students
  through using linear algebra to model a gear train. This is achieved by modeling
  each rigid gear body as a system of 3 equations, the input and output gears as one
  linear equation each, and then modeling the connection between gears as another
  linear equation derived from Newton&rsquo;s second law. The resulting matrix is
  explored for consistency and design elements.</p> <h2 class="subhead">Learning Objectives</h2>
  <p>After watching this video students will be able to:</p>  <ul><li>Model the forces
  and torques in a gear train as a system of linear equations.</li><li>Combine these
  linear equations into a matrix equation.</li></ul> <p>Funding provided by the Singapore
  University of Technology and Design (SUTD)</p> <p>Developed by the Teaching and
  Learning Laboratory (TLL) at MIT for SUTD</p> <p>MIT &copy; 2012</p>
course_id: res-tll-004-stem-concept-videos-fall-2013
embedded_media:
- id: Video-YouTube-Stream
  media_location: DjMaDN3EtWc
  parent_uid: ae481c61de15266f24585c29a1b79749
  title: Video-YouTube-Stream
  type: Video
  uid: ff676f0854689f0d1e1a9d8cdb5c787e
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/DjMaDN3EtWc/default.jpg
  parent_uid: ae481c61de15266f24585c29a1b79749
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 2aa241bb176a02378112f6fe35e9b715
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/podcast/gear-trains/id765926614?i=237394828&mt=2
  parent_uid: ae481c61de15266f24585c29a1b79749
  title: Video-iTunes U-MP4
  type: Video
  uid: 33ccb748bc6b4d857d154592f5e2e922
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MITRES.TLL-004F13/MITRES_TLL-004F13_gear_trains_300k.mp4
  parent_uid: ae481c61de15266f24585c29a1b79749
  title: Video-Internet Archive-MP4
  type: Video
  uid: e1738aa7516b8b6c6220b7a2a4f18dda
- id: 3Play-3PlayYouTubeid-MP4
  media_location: DjMaDN3EtWc
  parent_uid: ae481c61de15266f24585c29a1b79749
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: b673895a16a04dd24263703f41398497
- id: DjMaDN3EtWc.srt
  parent_uid: ae481c61de15266f24585c29a1b79749
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/linearity/gear-trains/DjMaDN3EtWc.srt
  title: 3play caption file
  type: null
  uid: 01fbb8f254c107607ddaf11550ecdc3c
- id: DjMaDN3EtWc.pdf
  parent_uid: ae481c61de15266f24585c29a1b79749
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/linearity/gear-trains/DjMaDN3EtWc.pdf
  title: 3play pdf file
  type: null
  uid: 3ea45adbd42c2f9170a6dc9b79084309
- id: Caption-3Play YouTube id-SRT
  parent_uid: ae481c61de15266f24585c29a1b79749
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 30951055b65981c669b3cee19a3de72c
- id: Transcript-3Play YouTube id-PDF
  parent_uid: ae481c61de15266f24585c29a1b79749
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: a660e852c2ee352c533eb6129b524ec5
inline_embed_id: 45215739geartrains71453536
layout: video
order_index: null
parent_uid: 408da4444ea5a84d94dbf30ef2be5696
related_resources_text: <p>Instructor Guide</p> <p><img alt="This resource may not
  render correctly in a screen reader." src="/images/inacessible.gif" /><a target="_blank"
  href="./resolveuid/13590b5a99116c03c51019c1e094d284">Gear Trains Instructor Guide
  (PDF)</a></p>
short_url: gear-trains
technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/linearity/gear-trains
template_type: Tabbed
title: Gear Trains
transcript: '<p><span m=''4620''>Servomotors are widely used electro-mechanical components.
  For example, they are used in</span> <span m=''9950''>steering systems for scale
  model helicopters and other radio controlled cars, robots, and</span> <span m=''16740''>aircraft,
  including military "drones".</span> </p><p><span m=''19790''>A servomotor includes
  an electric motor, circuitry to control its speed and direction, and gearing</span>
  <span m=''25919''>to attain the high torques needed to apply moderately large forces
  over relatively short</span> <span m=''31759''>linear displacements. The gearing
  inside this servo is a compound gear train with four stages.</span> </p><p><span
  m=''39010''>In this video, we will understand how linear algebra can help us to
  predict the losses</span> <span m=''44499''>and understand the design trade-offs
  when converting high speeds and low torques into</span> <span m=''49929''>low speeds
  and high torques using a gear train.</span> </p><p><span m=''54670''>This video
  is part of the Linearity Video Series. Many complex systems are modeled or</span>
  <span m=''60129''>approximated linearly because of the mathematical advantages.</span>
  </p><p><span m=''64110''>Hi, my name is Dan Frey, and I am a professor of Mechanical
  Engineering and Engineering</span> <span m=''70590''>Systems at MIT.</span> </p><p><span
  m=''72710''>Before watching this video, you should be able to identify and describe
  the forces and</span> <span m=''77570''>torques that act on a system.</span> </p><p><span
  m=''80760''>After watching this video and some practice, you will be able to:</span>
  <span m=''85200''>Model the forces and torques in a gear train as a system of linear
  equations.</span> </p><p><span m=''91110''>Combine these linear equations into a
  matrix equation.</span> </p><p><span m=''96950''>First, let''s get a quick overview
  of the design. Here''s a servomotor with the case opened.</span> </p><p><span m=''106229''>Inside
  the case is a DC motor with a small pinion gear on it. The pinion has 10 teeth</span>
  <span m=''112960''>and is mated to a gear with 72 teeth. So the first pair provides
  a speed reduction of 7.2:1.</span> </p><p><span m=''121800''>This large, 72 tooth
  gear is part of a single molding with a 10 tooth gear.</span> </p><p><span m=''128769''>The
  10 tooth gear on top of the 72 tooth gear is mated to a plastic gear with 48 teeth
  as</span> <span m=''135120''>you see here. So that stage provides a speed reduction
  of 4.8:1. The 48 tooth gear is molded</span> <span m=''143760''>to another 10 tooth
  gear.</span> </p><p><span m=''145849''>The 11-tooth gear is mated to a black 36-tooth
  gear. This 36-tooth gear is molded to a 16-tooth</span> <span m=''153280''>gear.
  The 16-tooth gear is mated to this black 42 tooth gear, which is splined onto the
  output</span> <span m=''163269''>shaft.</span> </p><p><span m=''165090''>The overall
  sequence of gear pairs is: 10 teeth mated to 72 teeth, 10 mated to 48, 11</span>
  <span m=''173079''>mated to 36 and finally 16 mated to 42 teeth on the splined output
  shaft.</span> </p><p><span m=''180010''>The overall gear ratio is the product of
  all the gear ratios of the gear pairs in the train.</span> </p><p><span m=''186459''>Therefore
  about 326 to 1 as shown by this formula.</span> </p><p><span m=''191769''>Based
  on the motor''s output and some measurement and calculation, we would expect an
  output</span> <span m=''196879''>torque of 6.8 Newton meters in an idealized gear
  train.</span> </p><p><span m=''202099''>But there are frictional losses at every
  stage of the power transmission process, so we guess</span> <span m=''207180''>the
  output shaft will provide substantially less torque than that. So let''s start by
  measuring</span> <span m=''213049''>the maximum force at the output shaft, and convert
  that to an output torque.</span> </p><p><span m=''218150''>We attach weights to
  a servo horn that has been connected with the output shaft on the</span> <span m=''222659''>servomotor.
  An electrical power source (in this case, a battery) is connected through</span>
  <span m=''228168''>a radio controller.</span> </p><p><span m=''230340''>Here you
  see the servomotor lifting 1 kg. Here it is lifting about 2kg. And here it</span>
  <span m=''238150''>lifts even 3kg! This lightweight (100 gram) servomotor produces
  large amounts of torque,</span> <span m=''247730''>which can apparently lift more
  than 30 times its own weight.</span> </p><p><span m=''252069''>In this set-up, the
  servomotor will lift a 4.42kg weight starting from a 90 degree angle.</span> </p><p><span
  m=''258180''>As the motor lifts the weight, the readout on the scale should change.</span>
  </p><p><span m=''262979''>Here you see the initial weight, with slack in the string,
  is 9.75 lbs. This is about</span> <span m=''269949''>4.42kg. With the motor pulling
  at maximum capacity, the scale reads 3.70 lbs, which</span> <span m=''278530''>is
  1.68 kg.</span> </p><p><span m=''282190''>A calculation tells us that the maximum
  torque available at the output shaft according to</span> <span m=''287340''>our
  tests is 1.47 Newton meters.</span> </p><p><span m=''295979''>We can use linear
  algebra to work out a better estimate. The force transmission and frictional</span>
  <span m=''301310''>losses in each step of the train can be modeled by a set of linear
  equations, (summing forces</span> <span m=''308220''>and summing torques on the
  rigid body). For the three rigid bodies that are comprised</span> <span m=''313520''>of
  two gears molded together, we will need three equations (sums of separate x and
  y</span> <span m=''320169''>forces and sums of torques).</span> </p><p><span m=''323840''>The
  pinion gear and last gear in the train are simpler, because there is only one gear</span>
  <span m=''328860''>in the body, so we can combine each of those into a single equation.</span>
  </p><p><span m=''334080''>The equations modeling the entire train can be assembled
  by linking together the five</span> <span m=''339909''>sets of equations with four
  additional equations to link each mating pair, so the overall system</span> <span
  m=''347199''>will have 15 equations--- 3 sets of 3 each (9 total) plus 1 each for
  the input and output</span> <span m=''354389''>gears plus 4 equations that model
  the connections between the mating gears. The solution to</span> <span m=''361229''>that
  set of equations helps us to estimate performance of the machine and also gives</span>
  <span m=''366919''>us insight into its design.</span> </p><p><span m=''370720''>Let''s
  make the model of just one gear body now, say the 10 tooth and 48 tooth molded</span>
  <span m=''376349''>gear seen here. One way to model the system is to posit that
  there are three unknown forces</span> <span m=''383039''>acting on this single body
  of two gears molded together.</span> </p><p><span m=''388110''>We can name these
  forces F-TL2, F-TS2 , F-ShaftX2, and F-ShaftY2. The force F-TL2 is a force</span>
  <span m=''402210''>tangent to the gear pitch circle on the larger of the two gears.
  The T is for Tangent, the</span> <span m=''408949''>L is for Large, and the 2 indicates
  that this is the second compound gear in the train.</span> </p><p><span m=''417080''>The
  force F-TS2 is a force tangent to the gear pitch circle on the smaller of the two</span>
  <span m=''423969''>gears. Again the T means tangent, and the S here means small.</span>
  </p><p><span m=''429289''>Recall that these tangential forces really come from forces
  normal to the gear teeth.</span> </p><p><span m=''436270''>These gears are designed
  so that all of the gears in this servomotor have a pressure angle</span> <span m=''441000''>of
  20 degrees. So there is a X component to this force, the separation force between
  the</span> <span m=''448169''>mating gears, which has magnitude given by FTL2 and
  FTS2 times tan 0.35, where 0.35 is</span> <span m=''460849''>20 degrees expressed
  in radians.</span> </p><p><span m=''464990''>The forces F-ShaftX2 and F-ShaftY2
  are the X and Y components of the normal force to</span> <span m=''473060''>the
  shaft, which is applied to the gear it supports.</span> </p><p><span m=''478060''>There
  are also frictional forces associated with the normal force supporting the shaft,</span>
  <span m=''483539''>but they are not separate unknowns, they link the X and Y components
  normal forces by the</span> <span m=''498840''>friction coefficient, mu2.</span>
  </p><p><span m=''502340''>This completes the description of the unknown forces in
  our model. Those four forces appear</span> <span m=''507650''>in three different
  linear equations as represented by this matrix:</span> <span m=''512909''>Take a
  moment to verify that these equations balance the forces and torques.</span> </p><p><span
  m=''518260''>The first row in the matrix represents a sum of the forces on the gear
  in the X direction.</span> </p><p><span m=''532279''>The second row represents a
  sum of the forces on the gear in the Y direction. The third</span> <span m=''537760''>row
  represents a sum of the torques or moments on the gear in the direction parallel
  to the</span> <span m=''543610''>gear shaft.</span> </p><p><span m=''545339''>Now
  let''s work on the model of the next gear in the train -- the one with 16 teeth
  and</span> <span m=''550680''>36 teeth molded together. Again, we model the system
  by positing that there are four</span> <span m=''557800''>unknown forces acting
  on this single body having two gears molded together and we can</span> <span m=''564230''>name
  these forces FTL3, FTS3 , FShaftX3, and FShaftY3. And we obtain this matrix.</span>
  </p><p><span m=''578329''>How can we link these two matrices together to get a model
  of the second and third gears</span> <span m=''584120''>combined? We see that the
  smaller gear on body 2 is in contact with the larger gear</span> <span m=''590589''>on
  body 3. According to Newton''s third law, the reaction force on body 2 should be
  equal</span> <span m=''597350''>and opposite to that on body 3.</span> </p><p><span
  m=''600630''>In fact, the situation is more complex. As the gears enter mating they
  slide into engagement.</span> </p><p><span m=''610279''>As the gears depart contact,
  they slide back out. There are losses at the interface that</span> <span m=''615449''>are
  complex to model, and we will represent them simply using the efficiency in the
  average</span> <span m=''621290''>transmitted force.</span> </p><p><span m=''623430''>Now
  we can join the model of the second gear and the third gear into a single system
  of</span> <span m=''629040''>linear equations represented by this matrix:</span>
  <span m=''633800''>The row in the middle is like "glue" holding the two models together.
  The force on the</span> <span m=''638529''>large gear on body 3 is equal to the
  force on the large gear on body 2 except a penalty</span> <span m=''644820''>is
  applied for inefficiencies. The principal mechanism for loss of power and torque
  is</span> <span m=''651790''>sliding friction -- in this case, shearing the lubricant
  on the gear faces.</span> </p><p><span m=''658120''>Before going on to assemble
  more of the model, it is worth inspecting our work so far for</span> <span m=''663839''>patterns.
  Note that the top right and bottom left of our matrices are filled with 3x4 matrices</span>
  <span m=''671839''>of zeros. That is a clue that our matrix is shaping up to be
  banded in structure. Although</span> <span m=''678760''>every variable affects every
  other variable, the influences propagate locally (in some</span> <span m=''684690''>sense).
  For example, the frictional losses on shaft 2 do influence the frictional losses</span>
  <span m=''691149''>on shaft 3, but only indirectly through their effect on the force
  between the two bodies.</span> </p><p><span m=''699820''>Because we arranged the
  variables in our vectors in a way that respects this structure, our</span> <span
  m=''704730''>matrix has a band in the middle from the top left corner to the bottom
  right. We will try</span> <span m=''710300''>to keep this up as we continue building
  the model. It will clarify interpretation of the</span> <span m=''714980''>model
  and also aid in efficiency and stability of the computations needed to solve it.</span>
  </p><p><span m=''722699''>Now it''s your turn, take a moment to write a matrix that
  models the force and torque</span> <span m=''727779''>balance on the first rigid
  body gear in the gear train.</span> </p><p><span m=''740680''>This matrix is completely
  analogous to the matrices we obtained in for the 2nd and 3rd</span> <span m=''746740''>gear
  bodies.</span> </p><p><span m=''747320''>When we add the pinion gear and fourth
  gear into the model, we need to take additional</span> <span m=''752560''>care.
  These will have slightly different structure. The gear connected to the pinion on
  the motor</span> <span m=''758610''>has an applied torque due to the motor. The
  reaction at the output shaft is an externally</span> <span m=''765389''>applied
  torque, due entirely to the large fourth gear. It is possible to combine these</span>
  <span m=''772970''>into a single equation for each gear.</span> </p><p><span m=''775560''>Pause
  the video and try to write out the full system of linear equations for the overall</span>
  <span m=''780350''>4 gear train system.</span> </p><p><span m=''789420''>Placing
  these into the model as the first and last rows, the overall system of linear</span>
  <span m=''794170''>equations is:</span> <span m=''795990''>Note that the matrix
  has 15 rows and 15 columns. This should be expected as the system should</span>
  <span m=''802440''>be neither overdetermined nor underdetermined. Given a particular
  torque input at the motor,</span> <span m=''808940''>there should be a single value
  of output torque consistent with our gear train model and its</span> <span m=''814350''>deterministically
  defined parameters.</span> </p><p><span m=''817709''>By solving this system, we
  find unique values for all the unknowns. When we assembled the</span> <span m=''824880''>equations,
  we guessed the direction of each force in the free body diagram. So, it''s useful</span>
  <span m=''829920''>to inspect the solution for negative values. For the parameter
  values we chose, the reaction</span> <span m=''835800''>force at the shaft of the
  third body in the x direction turns out to be negative.</span> </p><p><span m=''843069''>We
  should ask ourselves, did we guess wrong about the direction of the force, or is
  there</span> <span m=''847350''>something wrong with our matrix? Looking at the
  forces computed it seems that the friction</span> <span m=''858940''>in the x direction
  due to support of the large y reaction on this gear was more dominant</span> <span
  m=''865569''>that we expected.</span> </p><p><span m=''867920''>It''s sensible to
  run some sanity checks in a case like this. If the friction on that</span> <span
  m=''872509''>gear were very low, would the sign be positive as expected? We ran
  that scenario, and the</span> <span m=''878410''>sign did become positive. So our
  guess about the direction of the reaction force was wrong.</span> </p><p><span m=''884360''>Our
  assumptions for the magnitude of the friction were too low. But it seems the model
  is behaving</span> <span m=''890519''>in reasonable ways.</span> </p><p><span m=''896569''>Now
  that we have a reasonable level of confidence in the model, we can begin to use
  it to explore</span> <span m=''901360''>the design decisions that the engineers
  made. If we put in reasonable values for the gear</span> <span m=''906420''>mating
  efficiency, such as 96%, and reasonable values for the friction coefficients at
  the</span> <span m=''912690''>bushings, such as 0.3, we find an overall efficiency
  of the gear train is about 52%.</span> </p><p><span m=''919569''>This is in reasonable
  agreement with our simple measurements. We found that the maximum torque</span>
  <span m=''924209''>available at the output shaft is 1.47 Newton meters, which would
  imply an efficiency closer</span> <span m=''930230''>to 25%.</span> </p><p><span
  m=''932110''>But our measurement used an overhanging load, which caused the shaft
  to bend. Our simple</span> <span m=''937930''>model makes a large and optimistic
  assumption of loading the servomotor with torques only.</span> </p><p><span m=''944019''>It''s
  not surprising that the answers differ substantially. It suggests installing the</span>
  <span m=''949149''>servo so that bending loads are supported elsewhere, not in the
  servo itself.</span> </p><p><span m=''955529''>The gears in automotive transmissions
  with similar ratios are much more efficient, perhaps</span> <span m=''961470''>90%
  to 95% efficient. But for a compact and inexpensive gear train, this design performs</span>
  <span m=''968060''>well, especially since the plastic the gears are molded from
  adds a great deal of rolling</span> <span m=''969810''>friction.</span> </p><p><span
  m=''969920''>To summarize, we built an engineering model of a servomotor gear train
  using systems of</span> <span m=''975360''>linear equations. The matrix representations
  helped us to explore the interactions among</span> <span m=''981110''>variables
  in the system like separation forces between gears and friction at the shafts.</span>
  </p><p><span m=''985690''>Since the 15 by 15 system of equations is so fast and
  easy to solve on a modern computer,</span> <span m=''990600''>we could run a large
  number of "what if" scenarios.</span> </p><p><span m=''994240''>We hope this video
  helped you see how linear algebra can be used to make and understand</span> <span
  m=''999040''>engineering design decisions.</span> </p>'
type: course
uid: ae481c61de15266f24585c29a1b79749

---
None