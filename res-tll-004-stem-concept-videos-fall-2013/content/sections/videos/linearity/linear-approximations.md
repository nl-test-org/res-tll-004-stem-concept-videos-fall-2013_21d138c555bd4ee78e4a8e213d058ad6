---
about_this_resource_text: <h2 class="subhead">Summary</h2><p>Prof. Ben Brubaker defines
  and explores the properties of the linear approximation of a function at a point.
  The linear approximation is then applied to solve a simple differential equation
  encountered in chemical kinetics.</p><h2 class="subhead">Learning Objectives</h2><p>After
  watching this video students will be able to:</p><ul><li>Recognize the linear approximation
  of a function as the tangent line to the function.</li><li>Apply linear approximations
  to solve a simple differential equation.</li><li>Explain the limitations of linear
  approximations mathematically and graphically.</li></ul><p>Funding provided by the
  Singapore University of Technology and Design (SUTD)</p><p>Developed by the Teaching
  and Learning Laboratory (TLL) at MIT for SUTD</p><p>MIT &copy; 2012</p>
course_id: res-tll-004-stem-concept-videos-fall-2013
embedded_media:
- id: MITRES_TLL-004F13_LinAp_IG.pdf
  parent_uid: 0a16b9640face725a18989a8593cf0a0
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/linearity/linear-approximations/MITRES_TLL-004F13_LinAp_IG.pdf
  title: Linear Approximations Instructor Guide
  type: null
  uid: d686550cd1aa0e732f43f20039a9fdc5
- id: Video-YouTube-Stream
  media_location: nwZ9FbZtOv0
  parent_uid: 0a16b9640face725a18989a8593cf0a0
  title: Video-YouTube-Stream
  type: Video
  uid: e335928815d5cb36356a24a1bf10b152
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/nwZ9FbZtOv0/default.jpg
  parent_uid: 0a16b9640face725a18989a8593cf0a0
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: f24685724aa900595ad28cb0aa93bd01
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id765926614
  parent_uid: 0a16b9640face725a18989a8593cf0a0
  title: Video-iTunes U-MP4
  type: Video
  uid: 8b83ba60030764fbcbd42f2cc080f6a7
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MITRES.TLL-004F13/MITRES_TLL-004F13_linear_approximations_300k.mp4
  parent_uid: 0a16b9640face725a18989a8593cf0a0
  title: Video-Internet Archive-MP4
  type: Video
  uid: 02876565d254fc1187811fe699ff03fa
- id: 3Play-3PlayYouTubeid-MP4
  media_location: nwZ9FbZtOv0
  parent_uid: 0a16b9640face725a18989a8593cf0a0
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 550379ed02adeb954168b8ae5b26e5ee
- id: nwZ9FbZtOv0.srt
  parent_uid: 0a16b9640face725a18989a8593cf0a0
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/linearity/linear-approximations/nwZ9FbZtOv0.srt
  title: 3play caption file
  type: null
  uid: 18affb65882dad125e2a0772f029efa8
- id: nwZ9FbZtOv0.pdf
  parent_uid: 0a16b9640face725a18989a8593cf0a0
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/linearity/linear-approximations/nwZ9FbZtOv0.pdf
  title: 3play pdf file
  type: null
  uid: 21b4dd321d090c6fdeb71cb73dbbb99c
- id: Caption-3Play YouTube id-SRT
  parent_uid: 0a16b9640face725a18989a8593cf0a0
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: e50d06aa7cbe31ec3ff862f994c77a33
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 0a16b9640face725a18989a8593cf0a0
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 3836f7cb1a92d902183afc8053303e34
inline_embed_id: 15601562linearapproximations4864933
layout: video
order_index: null
parent_uid: 408da4444ea5a84d94dbf30ef2be5696
related_resources_text: <p>Instructor Guide</p><p><a target="_blank" href="./resolveuid/d686550cd1aa0e732f43f20039a9fdc5">Linear
  Approximations Instructor Guide (PDF)</a></p>
short_url: linear-approximations
technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/linearity/linear-approximations
template_type: Tabbed
title: Linear Approximations
transcript: "<p><span m='3350'> N2O5 is a reagent that was used synthesize explosives\
  \ like TNT. Unfortunately, N2O5 decomposes</span> <span m='9860'>relatively quickly\
  \ at or above room temperature, so if you accidentally leave a bottle of it</span>\
  \ <span m='14330'>out on the counter, you could be in trouble! In this video, we'll\
  \ approximate a solution</span> <span m='18430'>to the decomposition rate equation\
  \ to figure out whether a batch of N2O5 that you left</span> <span m='22870'>at\
  \ room temperature can still be used. We'll also determine under what conditions\
  \ our approximation</span> <span m='28400'>is valid.</span> <span m='30260'>This\
  \ video is part of the Linearity video series.</span> <span m='33530'>Many complex\
  \ systems are modeled or approximated linearly because of the mathematical advantages.</span>\
  \ <span m='38640'>Hi, my name is Ben Brubaker, and I'm a professor in the Department\
  \ of Mathematics at MIT.</span> <span m='44769'>Today we'll be talking about linear\
  \ approximations. In mathematical terms, this is just another</span> <span m='49889'>name\
  \ for the tangent line to a function. But the name suggests more. Linear approximations</span>\
  \ <span m='55210'>can be used to simplify mathematical models that are not analytically\
  \ solvable. The approximated</span> <span m='61260'>model will have a solution that\
  \ is only acceptable under suitable conditions. However, it can</span> <span m='66500'>still\
  \ illuminate the behavior of the system within a certain acceptable range.</span>\
  \ <span m='72439'>Before watching this video, you should know the definition of\
  \ the derivative, and how</span> <span m='76280'>to write the equation of a line\
  \ with a given slope that passes through a given point.</span> <span m='81780'>After\
  \ watching this video, you should be able to recognize the linear approximation\
  \ of a</span> <span m='85719'>function as the tangent line to the function, apply\
  \ linear approximations to solve simple</span> <span m='91280'>differential equations,\
  \ and explain the limitations of linear approximations both mathematically</span>\
  \ <span m='96710'>and graphically.</span> <span m='99380'>Let's begin by defining\
  \ the linear approximation. Recall that if a function is differentiable</span> <span\
  \ m='106009'>at a point c, then when we zoom in on the point c, the function begins\
  \ to look more</span> <span m='110700'>and more like a line. This only works when\
  \ the function is \"smooth\"\u2014it doesn't have</span> <span m='115259'>any kinks,\
  \ corners, or discontinuities. Given a function f(x), which is differentiable at</span>\
  \ <span m='122100'>the point c, we define the linear approximation to be the tangent\
  \ line to the function at</span> <span m='127060'>c. This is a line whose slope\
  \ equals f'(c).</span> <span m='134620'>As an example, let's look at the following\
  \ cubic equation: f(x) = one thirtieth x times</span> <span m='141300'>x minus 2\
  \ times x plus 5. This function is differentiable everywhere, and in particular</span>\
  \ <span m='147800'>is differentiable at the point x=3. Find the equation of the\
  \ tangent line to this cubic</span> <span m='154520'>equation at x=3 for yourself.</span>\
  \ <span m='163430'>We've also found the equation for the tangent line. To do this,\
  \ we found the value of the</span> <span m='167700'>function at 3, which we found\
  \ to be 4/5. And then we computed the derivative and evaluated</span> <span m='173290'>it\
  \ at x=3, which we found to be 7/6. We'll write the tangent line as T sub 3 of (x)\
  \ to</span> <span m='180540'>remind us that we are finding the tangent to our function\
  \ at the point 3. Then the equation</span> <span m='186220'>for this line can be\
  \ written as T sub 3 of x equals 4/5 + 7/6 times (x-3).</span> <span m='196010'>Let's\
  \ take a look at the graphs of f(x) and T sub 3 of x. The function f(x) is graphed</span>\
  \ <span m='201170'>in red. The further we zoom into the graph at x=3, the more it\
  \ begins to resemble a straight</span> <span m='207090'>line. The slope of the line\
  \ approaches the value of the slope of the tangent line at</span> <span m='211500'>3,\
  \ which is drawn in blue.</span> <span m='215570'>The tangent line certainly seems\
  \ to be a good approximation to our function when we are</span> <span m='219390'>close\
  \ to x=3. But what about when we zoom out? Is it still a good approximation? Let's</span>\
  \ <span m='225650'>give a mathematical justification that the tangent line is a\
  \ good approximation. Our</span> <span m='231420'>function is differentiable at\
  \ a point, say x=3. This is equivalent to the statement that</span> <span m='236820'>when\
  \ x is near 3, the slope of the secant line is approximately equal to the slope\
  \ of</span> <span m='242280'>the tangent line. That is, for x near 3 f(x)-f(3) over\
  \ x-3, is approximately equal to the value</span> <span m='252200'>of the derivative\
  \ at 3.</span> <span m='254980'>In order to see why these statements are equivalent,\
  \ we need explain what we mean by \"approximately</span> <span m='260339'>equal\
  \ to\". This means that we can make the difference between these two sides as small</span>\
  \ <span m='265310'>as any error bound we choose, provided that we choose x close\
  \ enough to 3.</span> <span m='273370'>And this is exactly the definition of differentiability\
  \ at the point 3.</span> <span m='279940'>To relate this to linear approximations,\
  \ we use a bit of algebra. First we multiply both</span> <span m='286810'>sides\
  \ by (x-3), and we get f(x) -- f(3) approximately equal to f'(3)(x-3). Adding f(3)\
  \ to both sides,</span> <span m='299040'>we get that f(x) is approximately equal\
  \ to f(3)+f'(3)(x-3). And this right hand side</span> <span m='308210'>is the equation\
  \ for the tangent line at 3. So indeed the tangent line closely approximates</span>\
  \ <span m='314460'>the function as long as x is close to 3.</span> <span m='319760'>Here\
  \ we see the tangent line drawn in blue, the function drawn in red. The graphs demonstrate</span>\
  \ <span m='325010'>our mathematical proof that the tangent line is a good approximation\
  \ near x=3, but the</span> <span m='331330'>further we get from x=3 the worse the\
  \ approximation seems.</span> <span m='335670'>Now you might see that the function\
  \ and tangent line intersect at x=-9. Is the tangent line</span> <span m='342590'>a\
  \ good approximation for the function near x=-9?</span> <span m='347990'>No, it\
  \ isn't. If we move a small distance along the tangent line away from x=-9, this</span>\
  \ <span m='357020'>does not model the behavior of the function near x=-9. This property\
  \ is extremely important</span> <span m='363620'>in applications\u2014no measurement\
  \ or observed quantity is ever given exactly.</span> <span m='369010'>A1 The linearization\
  \ of a function that is differentiable at x=c is just another name</span> <span\
  \ m='374550'>for the tangent line through c.</span> <span m='377590'>The A2 key\
  \ properties of this tangent line are that it shares the same value as the function</span>\
  \ <span m='382220'>and the same first derivative of the function at x=c. And A3\
  \ we've seen through both graphical</span> <span m='387639'>intuition and the definition\
  \ of the derivative that this linearization closely approximates</span> <span m='393060'>the\
  \ function for points x sufficiently close to c.</span> <span m='397520'>Let's see\
  \ how we can apply a linear approximation to simplify a problem. Let's suppose that</span>\
  \ <span m='404210'>you are participating in undergraduate research in a chemistry\
  \ lab. You have been using a</span> <span m='409060'>.01 molar solution of N2O5.\
  \ You bring it out of the refrigerator at 9:00 Monday morning,</span> <span m='416270'>and\
  \ promptly forget about it, leaving it on the counter in the lab, which is 25 degrees</span>\
  \ <span m='422020'>Celsius. When you realize you left the solution out, 1 hour has\
  \ passed. You panic.</span> <span m='429169'>The problem is that N205 decomposes\
  \ into NO2 and O2 at room temperature. If the molarity</span> <span m='436510'>of\
  \ the solution has changed significantly, it might ruin your experiments. Experiments</span>\
  \ <span m='442419'>have shown that the rate of decomposition follows first order\
  \ kinetics. This means that</span> <span m='447940'>the instantaneous rate of change\
  \ in concentration of N205 is proportional to the concentration</span> <span m='454190'>of\
  \ N205. The constant of proportionality, k, has been found experimentally to be\
  \ 1.72</span> <span m='463010'>times ten to the negative 5 inverse seconds.</span>\
  \ <span m='468540'>Because you are panicking, you are having a hard time solving\
  \ this differential equation.</span> <span m='472990'>Instead, find the _approximate_\
  \ decomposition in the N205 solution after 1 hour using a</span> <span m='480340'>linear\
  \ approximation at time t=0. Note that because the reaction constant has units of</span>\
  \ <span m='487150'>inverse seconds, the variable t must have units of seconds.</span>\
  \ <span m='496110'>In order to produce a linear approximation at t=0, we need two\
  \ ingredients: the concentration</span> <span m='502770'>at time 0, and the value\
  \ of the derivative at time 0.</span> <span m='508760'>The initial concentration\
  \ was .01 molar. To find the value of the derivative, we use our</span> <span m='514870'>differential\
  \ equation, and we find that the value of the derivative at time t=0 is just</span>\
  \ <span m='520719'>minus k times the initial concentration at t=0, or negative k\
  \ times .01 molar. Remember</span> <span m='530540'>that k has units of inverse\
  \ seconds.</span> <span m='536019'>Putting this together into the formula for the\
  \ tangent line at zero, we see that the</span> <span m='540470'>linear approximation,\
  \ is given by T0(t)= (.01 molar) times 1 minus $kt$.</span> <span m='552420'>Now\
  \ we are interested in approximating the value at 1 hour, or 3600 seconds. Plugging</span>\
  \ <span m='559649'>in the value for k, we find that to two significant figures T0(3600)=.0094\
  \ Molar. So the molarity</span> <span m='570730'>is not so different. Phew!!</span>\
  \ <span m='573860'>Now you are feeling relieved, so when you look back at the reaction\
  \ rate, you realize</span> <span m='578220'>that in fact, a first order reaction\
  \ rate is telling you that the concentration is some</span> <span m='583170'>function\
  \ of time whose derivative is proportional to itself.</span> <span m='589529'>The\
  \ function with this property is the exponential function! So the concentration\
  \ function is</span> <span m='594860'>equal to some constant times e to the negative\
  \ kt.</span> <span m='599670'>The constant must be the initial concentration, which\
  \ is .01 Molar, so [N2O5]=(.01)e^{-kt}.</span> <span m='614079'>Evaluating this\
  \ expression at time t=3600, we find that the exact concentration is also</span>\
  \ <span m='620889'>.0094 Molar to two significant figures. To be more precise, we\
  \ can look at the error,</span> <span m='628920'>which is the absolute value of\
  \ the exact solution minus the approximate solution all divided</span> <span m='634790'>by\
  \ the exact solution.</span> <span m='637899'>The error at time t=3600 seconds is\
  \ .002 or .2%.</span> <span m='646329'>This is really quite good. Generally speaking,\
  \ we might consider an error of less than 5%</span> <span m='651829'>to be acceptable.</span>\
  \ <span m='655110'>So our linear approximation was definitely within the acceptable\
  \ range 1 hour later.</span> <span m='662199'>But now it's Tuesday. Today you leave\
  \ the .01 Molar N2O5 on the counter for a full 10</span> <span m='668100'>hours.\
  \ Oops. We know that the exact solution is an exponential</span> <span m='674550'>decay.</span>\
  \ <span m='677139'>So do you think that the linear approximation will be an over\
  \ estimate, an under estimate,</span> <span m='682199'>or equal to the exact solution\
  \ after 10 hours? [pause]</span> <span m='691670'>The linear approximation of the\
  \ concentration after 10 hours at room temperature is T0(36000)=</span> <span m='699889'>.0038\
  \ Molar. The exact solution of the concentration after</span> <span m='707709'>10\
  \ hours is .0054 Molar. Comparing these two solutions, we see that linear approximation</span>\
  \ <span m='716160'>is an under estimate as we would expect, with error is .29 or\
  \ 29%. So a linear approximation</span> <span m='726529'>is definitely not acceptable\
  \ for this time range.</span> <span m='732379'>But now you begin to wonder, for\
  \ what times is the linear approximation at t=0 within</span> <span m='738290'>5%\
  \ error of the exact solution? [pause] Because we are only interested in positive\
  \ time values,</span> <span m='750529'>you should have found that the approximation\
  \ is acceptable for times 0 less than t less</span> <span m='756509'>than 16, 700\
  \ seconds, which is about 4.5 hours. Now that you've carefully examined this problem</span>\
  \ <span m='763209'>using linear approximation, it is probably time to tell your\
  \ graduate student adviser</span> <span m='768149'>that you need to order a new\
  \ batch of N_2 O_5 solution.</span> <span m='775920'>Let's review. A1 The linear\
  \ approximation to a function at a point c is the tangent</span> <span m='780910'>line\
  \ of a function at c. A2 This linear approximation only accurately models the function\
  \ for points</span> <span m='787040'>sufficiently close to c. A3 It is easy to read\
  \ off the derivative at a point from a</span> <span m='793100'>differential equation,\
  \ and thus give a linear approximation to the solution. In our example</span> <span\
  \ m='799449'>with the concentration of N205, we could also solve the differential\
  \ equation exactly and</span> <span m='805449'>demonstrate that the approximation\
  \ was acceptable near the point of approximation t=0, but not</span> <span m='812239'>so\
  \ for larger time intervals.</span> <span m='814879'>Notice that we used this simple\
  \ example to illustrate linear approximation because we</span> <span m='819389'>could\
  \ also solve it exactly and use the exact solution to determine the error. This\
  \ is somewhat</span> <span m='825959'>misleading, since we often want to use linear\
  \ approximation precisely when the differential</span> <span m='831049'>equation\
  \ that describes our physical situation does not have an analytic solution.</span>\
  \ <span m='837399'>So you may wonder, is there a way to estimate the error in a\
  \ linear approximation without</span> <span m='842170'>knowing the exact solution.\
  \ The answer is yes! However, it involves Taylor's Remainder</span> <span m='848089'>theorem,\
  \ which finds an acceptable range in terms of higher order derivatives, and is</span>\
  \ <span m='853309'>beyond the scope this video.</span> </p>"
type: course
uid: 0a16b9640face725a18989a8593cf0a0

---
None