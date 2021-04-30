---
about_this_resource_text: '<h2 class="subhead">Summary</h2> <p>In this video, Niaja
  Farve, doctoral student of Electrical Engineering and Computer Science, explains
  repetitive programming techniques, a very fundamental and essential programming
  skill. First, using a light-hearted example of eating cereal, Niaja explains how
  to break problems into simpler yet similar pieces. She then explains how to combine
  solutions of these simpler pieces to recursively or iteratively solve the whole
  problem. Next, students are presented with a classic string manipulation problem
  to apply their new skills. Finally, students are given a more complex programming
  task: solving the Towers of Hanoi problem.</p> <h2 class="subhead">Learning Objectives</h2>
  <p>After watching this video students will be able to:</p> <ul>     <li>Divide a
  programming problem into simpler, analogous pieces.</li>     <li>Solve the problem
  by combining solutions to simpler pieces.</li> </ul><p>Funding provided by the Singapore
  University of Technology and Design (SUTD)</p><p>Developed by the Teaching and Learning
  Laboratory (TLL) at MIT for SUTD</p><p>MIT &copy; 2012</p>'
course_id: res-tll-004-stem-concept-videos-fall-2013
embedded_media:
- id: Video-YouTube-Stream
  media_location: 0BDi0d1j7u0
  parent_uid: ce5f8650709155886f635ecb56351751
  title: Video-YouTube-Stream
  type: Video
  uid: 460417134a470b1f3c0de2ef53c59d27
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/0BDi0d1j7u0/default.jpg
  parent_uid: ce5f8650709155886f635ecb56351751
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 4e51074d82292adccfc547358312d081
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/podcast/basic-programming-techniques/id765926614?i=237394831&mt=2
  parent_uid: ce5f8650709155886f635ecb56351751
  title: Video-iTunes U-MP4
  type: Video
  uid: 8eaca379dcd4be60271b48437488d4c4
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MITRES.TLL-004F13/MITRES_TLL-004F13_basic_programming_300k.mp4
  parent_uid: ce5f8650709155886f635ecb56351751
  title: Video-Internet Archive-MP4
  type: Video
  uid: 30080625366aa97e3bdfb27aca39c8e3
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 0BDi0d1j7u0
  parent_uid: ce5f8650709155886f635ecb56351751
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 25fd6ddbf5732af98994f7d5c5482467
- id: 0BDi0d1j7u0.srt
  parent_uid: ce5f8650709155886f635ecb56351751
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/problem-solving/basic-programming-techniques/0BDi0d1j7u0.srt
  title: 3play caption file
  type: null
  uid: f3e23612e5cdd66500095142fc1cf18d
- id: 0BDi0d1j7u0.pdf
  parent_uid: ce5f8650709155886f635ecb56351751
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/problem-solving/basic-programming-techniques/0BDi0d1j7u0.pdf
  title: 3play pdf file
  type: null
  uid: f3aaeea5d583ec852dcfdbebd80e0e5c
- id: Caption-3Play YouTube id-SRT
  parent_uid: ce5f8650709155886f635ecb56351751
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 6cd03b2128c86cd3d0be3b803f6afc47
- id: Transcript-3Play YouTube id-PDF
  parent_uid: ce5f8650709155886f635ecb56351751
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 6c6d2eba6802d156012bc32ac37acfcd
inline_embed_id: 51444181basicprogrammingtechniques18372306
layout: video
order_index: null
parent_uid: 9b39fef08a7dea340e5530b48721109e
related_resources_text: <p>Instructor Guide</p> <p><a target="_blank" href="./resolveuid/945c2399edefafb5135ab9fd4d884422">Basic
  Programming Techniques Instructor Guide (PDF)</a></p>
short_url: basic-programming-techniques
technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/problem-solving/basic-programming-techniques
template_type: Tabbed
title: Basic Programming Techniques
transcript: '<p><span m=''4600''>There are many ways to complete a task---even a seemingly
  simple one like eating cereal.</span> </p><p><span m=''10150''>When programming
  a computer to complete a task or solve a problem, repetitive techniques</span> <span
  m=''14549''>like iteration and recursion are extremely useful. In this video, we
  will look at these</span> <span m=''19650''>problem-solving techniques.</span> </p><p><span
  m=''21870''>This video is part of the Problem Solving video series. Problem-solving
  skills, in combination</span> <span m=''27520''>with an understanding of the natural
  and human-made world, are critical to the design and optimization</span> <span m=''33280''>of
  systems and processes.</span> </p><p><span m=''34949''>Hi, my name is Niaja Farve.
  I am a doctoral student in Electrical Engineering and Computer</span> <span m=''41260''>Science
  at MIT.</span> </p><p><span m=''43679''>Before watching this video, you should be
  familiar with introductory programming and</span> <span m=''48019''>simple data
  structures.</span> </p><p><span m=''50469''>After watching this video, you will
  be able to: Divide a programming problem into simpler,</span> <span m=''55979''>analogous
  pieces. And, solve the problem by combining solutions to the simpler pieces.</span>
  </p><p><span m=''67440''>In computer science, we often want to solve complex problems.
  However, computers deal</span> <span m=''72850''>best with performing easy tasks
  over and over again. We utilize the computer''s ability by</span> <span m=''79380''>implementing
  repetitive techniques to incrementally solve our complex problems.</span> </p><p><span
  m=''84908''>Though eating a bowl of cereal is a fairly simple task that most of
  us can complete automatically,</span> <span m=''90600''>we need to think carefully
  about how to program a computer to do the same. Let''s take a closer</span> <span
  m=''95880''>look at the problem and identify the fundamental steps used to frame
  cereal eating for repetitive</span> <span m=''102100''>computation.</span> </p><p><span
  m=''103100''>In this example, let''s suppose the computer understands the basic
  operation of eating</span> <span m=''107658''>a single bite of cereal, but does
  not understand how to eat an entire bowl of cereal. So how</span> <span m=''113929''>do
  we "teach" the computer to eat a bowl of any size greater than one bite? Pause the</span>
  <span m=''119479''>video here and think about it.</span> </p><p><span m=''127770''>The
  first step when approaching a complex programming problem is to break the problem</span>
  <span m=''131930''>up into analogous, but simpler pieces that we can tell the computer
  how to directly solve.</span> </p><p><span m=''137750''>So what is a simpler version
  of eating a whole bowl of cereal?</span> </p><p><span m=''142350''>One possibility
  is eating a smaller amount of cereal.</span> </p><p><span m=''146480''>We already
  mentioned that a small, non-zero amount of cereal the computer can handle eating</span>
  <span m=''151300''>is a single bite.</span> </p><p><span m=''154220''>Going one
  step up, eating two bites-worth of cereal is equivalent to eating a single</span>
  <span m=''159430''>bite twice. The next step when approaching a complex problem
  is to deduce a pattern.</span> </p><p><span m=''166210''>That is, how does a generally
  larger problem look in comparison to the simpler version?</span> </p><p><span m=''171480''>Here,
  we notice that eating any amount of cereal is equivalent to the sum of eating</span>
  <span m=''176260''>multiple bites-worth of cereal.</span> </p><p><span m=''179230''>Now
  that we''ve broken up our problem and understand how the pieces will fit back together,
  we</span> <span m=''184740''>can put our solution into a generalized code framework:</span>
  <span m=''189180''>Start with telling the computer the procedure for solving the
  simplest problem. Then, repeat</span> <span m=''194120''>this procedure on subsequent
  pieces until the desired endpoint is reached:</span> <span m=''199130''>If the bowl
  contains cereal, take one bite of cereal. Repeat until there is no more cereal.</span>
  </p><p><span m=''211540''>You may recognize this type of solution as an iterative
  approach.</span> </p><p><span m=''216250''>Or we could also take the following alternative
  approach:</span> <span m=''219810''>Start with telling the computer how to solve
  the simplest problem. Then, break the problem</span> <span m=''224500''>into simpler
  and simpler pieces until we reach the version we''ve already told the computer</span>
  <span m=''229320''>how to solve. Does the bowl contain 1 bite of cereal? If</span>
  <span m=''234840''>so, take the bite. If not, divide it up into a bowl containing
  one bite and a bowl containing</span> <span m=''241030''>the remainder. Repeat this
  procedure on the resulting bowls.</span> </p><p><span m=''246090''>In this case,
  we end, up with a series of bowls containing one bite, which the computer</span>
  <span m=''251040''>knows how to eat.</span> </p><p><span m=''253200''>Breaking up
  a problem into progressively simpler, but analogous pieces in this way is known</span>
  <span m=''257880''>as a recursive approach. Because the solution to the most complex
  problem depends on solutions</span> <span m=''263350''>to the simpler pieces, recursion
  creates a queue of jobs waiting to be completed.</span> </p><p><span m=''268930''>In
  contrast, when using iteration, there is no such dependency from one instance of
  the</span> <span m=''275260''>problem to the next.</span> </p><p><span m=''277260''>So
  even though the computer ends up consuming n bites of cereal in both cases, the
  iterative</span> <span m=''283030''>and recursive approaches arrive at this answer
  in very different ways.</span> </p><p><span m=''288150''>There are many different
  ways to successfully eat a bowl of cereal or solve any given programming</span>
  <span m=''293690''>problem. The key is to 1. Break the problem into analogous pieces
  that the computer can</span> <span m=''300380''>solve, and 2. Combine the solutions
  to the pieces into a solution for the more complex</span> <span m=''305790''>problem.</span>
  </p><p><span m=''311620''>In our previous cereal-eating example, breaking down the
  problem into simpler pieces was fairly</span> <span m=''317470''>straightforward.
  Now, let''s look at a slightly more complex problem.</span> </p><p><span m=''321260''>We
  would like to write a function, downup, that takes an input string and prints out</span>
  <span m=''327250''>progressively smaller and larger sub-strings of the word as so.</span>
  </p><p><span m=''332260''>To help us work with strings, we have a helper function,
  substring, which extracts a portion</span> <span m=''338190''>of a string, beginning
  from the first character up though a specified end index.</span> </p><p><span m=''344440''>Following
  the framework we discussed earlier, what is a simpler version of downup that we</span>
  <span m=''348900''>can easily handle?</span> </p><p><span m=''350980''>How about
  downup of a single letter string. The desired output is achieved by simply printing</span>
  <span m=''356460''>the string.</span> </p><p><span m=''358500''>Moving one step
  up, we see that the desired output of a two-letter string can be accomplished</span>
  <span m=''363530''>by printing the string, printing the string shortened by one
  letter, and printing the</span> <span m=''368070''>full string a second time.</span>
  </p><p><span m=''371120''>And moving up one more step to a 3 letter string...</span>
  </p><p><span m=''376650''>Are you starting to notice any patterns? Pause the video
  to think of a possibility.</span> </p><p><span m=''387100''>Though there are many
  different patterns, here is one you may have come up with: With</span> <span m=''391370''>every
  string, we are sandwiching the _solution_ to a string one character shorter between</span>
  <span m=''396740''>two printings of the full string. With this mindset, we are poised
  for a recursive solution</span> <span m=''402490''>to this problem.</span> </p><p><span
  m=''404470''>Recall the general framework for a recursive solution: Tell the computer
  how to solve the</span> <span m=''409680''>simplest problem. Then break the problem
  into simpler pieces until we reach the simplest</span> <span m=''416199''>problem:
  If the string is a single letter, print it. Otherwise, print the string, solve</span>
  <span m=''422650''>for downup of the string one character shorter, and print the
  string again.</span> </p><p><span m=''429010''>Try now, if you haven''t already
  done so, to frame the problem in a more iterative manner.</span> </p><p><span m=''435180''>Pause
  the video to discuss.</span> </p><p><span m=''443770''>We can notice that we are
  repeatedly printing substrings of the full string, with each step</span> <span m=''449240''>moving
  the end index from the original length down to 1. This is followed by again printing</span>
  <span m=''455639''>substrings, but this time increasing the end index back up to
  the original length.</span> </p><p><span m=''461840''>We can program this solution
  using two iterative loops. Recall the general iterative code framework:</span> <span
  m=''468979''>Tell the computer the procedure for the simplest problem. Repeat the
  procedure on subsequent</span> <span m=''474110''>pieces until the endpoint is reached.</span>
  </p><p><span m=''477460''>In our first loop, we print the substring, decrease the
  index by one, and repeat the</span> <span m=''482490''>procedure until the index
  reaches one.</span> </p><p><span m=''486490''>In the second loop, we move in the
  opposite direction. Print the substring. Increase the</span> <span m=''492130''>index
  by one and repeat the procedure until the index is greater than the original length.</span>
  </p><p><span m=''498460''>Both approaches, while very different, are completely
  valid! There is no one correct</span> <span m=''504040''>way to solve a problem.
  Some solutions may even have both recursive and iterative elements.</span> </p><p><span
  m=''516059''>Now lets solve a third problem with an even more complex pattern.</span>
  </p><p><span m=''520698''>In the famous Towers of Hanoi problem, the goal is to
  transfer a stack of rings from</span> <span m=''525589''>pillar A to pillar C. We
  can only move a single ring at a time, and can use pillar B as "extra"</span> <span
  m=''534050''>workspace. We cannot place a larger ring on top of a smaller ring.</span>
  </p><p><span m=''539959''>Lets follow the framework and start by working out the
  simplest problem: transferring 1 ring.</span> </p><p><span m=''546369''>Here we
  can simply move the ring from A to C.</span> </p><p><span m=''549119''>Okay, now
  let''s try to transfer a stack of two rings. First we move the ring 1 to B,</span>
  <span m=''557550''>then ring 2 to C, then move ring 1 from B to C.</span> </p><p><span
  m=''562410''>Now, let''s try something a bit harder. Let''s try to transfer a stack
  of three rings. Ring</span> <span m=''570550''>1 moves to C, ring 2 goes to B, and
  ring 1 goes to B. Now ring 3, which was on the bottom,</span> <span m=''580889''>is
  free to move to C. Then, ring 1 goes to A, ring 2 goes to C, then ring 1 finally
  goes</span> <span m=''589470''>to C.</span> </p><p><span m=''590939''>Notice that
  after we moved the bottom ring to C, we essentially arrived at the same conformation</span>
  <span m=''597369''>as when trying to transfer 2 rings: We have two stacked rings
  and an extra empty pillar.</span> </p><p><span m=''603959''>And because the largest
  ring is in the desired, final position and does not impede the movements</span>
  <span m=''609449''>of any of the remaining smaller rings, we can treat the pillar
  as being empty.</span> </p><p><span m=''615459''>This observation is crucial to
  the recursive implementation of the towers of Hanoi solution.</span> </p><p><span
  m=''622249''>We transferred n-1 rings to the extra pillar, moved the largest ring
  to the final position,</span> <span m=''629059''>then transferred the n-1 rings
  to the final position.</span> </p><p><span m=''633399''>Can you frame a pseudocode
  solution to the problem? Pause the video here to work out</span> <span m=''638529''>a
  possible solution.</span> </p><p><span m=''646589''>Recall again the general recursive
  framework: Tell the computer how to solve the simplest</span> <span m=''652509''>problem:
  If we''re transferring a single ring, move it to the destination pillar.</span>
  </p><p><span m=''659259''>Then, break the problem up into progressively simpler
  pieces:</span> <span m=''665579''>Transfer n-1 rings from the source to the extra
  pillar, transfer ring n from the source</span> <span m=''671929''>to the destination,
  and transfer n-1 rings from the extra pillar to the destination.</span> </p><p><span
  m=''679279''>Note that the source, destination, and extra pillar designations change
  with each function</span> <span m=''684399''>call!</span> </p><p><span m=''685569''>It''s
  always a good idea to check your code with a test case. Pause the video here and</span>
  <span m=''691139''>check your code for the case of N equals 4. You may also wish
  to check our code and compare</span> <span m=''697990''>the two solution methods.</span>
  </p><p><span m=''706529''>Now lets check our code and traverse through the solution
  for transferring 4 rings.</span> </p><p><span m=''711420''>We''re not transferring
  a single ring, so lets transfer 3 rings from A to B.</span> </p><p><span m=''718189''>We''re
  still not transferring one ring, so lets transfer 2 rings from A to C.</span> </p><p><span
  m=''724379''>We''re still not transferring one ring, so lets transfer 1 ring from
  A to B. And we can</span> <span m=''730569''>finally move this single ring!</span>
  </p><p><span m=''734179''>Now we return to the previous call, and can move ring
  2 from A to C. Then we transfer</span> <span m=''741309''>our n-1 stack from B to
  C. This results in transferring 2 rings from A to C!</span> </p><p><span m=''752749''>Returning
  one more step back, we move ring 3 to B. Now we transfer 2 rings from C to</span>
  <span m=''760839''>A.</span> </p><p><span m=''768379''>Finally, we''ve returned
  back to our original function call, and we''ve completed transferring</span> <span
  m=''780220''>3 rings from A to B. So, we can move our largest ring number 4 from
  A to C.</span> </p><p><span m=''790420''>Now we need a whole other set of recursive
  function calls to transfer the 3 ring stack</span> <span m=''796600''>from B to
  C! Pause the video now to finish checking the second half of our solution.</span>
  </p><p><span m=''802480''>Notice how quickly the number of function calls grew!
  Good thing we have a computer</span> <span m=''810170''>that is very good at following
  repetitive instructions!</span> </p><p><span m=''814269''>To Review In this video,
  we showed you how recursion and iteration take advantage of</span> <span m=''819579''>a
  computer''s ability to repeat simple tasks.</span> </p><p><span m=''823550''>To
  approach a complicated programming problem, first solve some simpler versions and
  try</span> <span m=''828889''>to identify a pattern. Then, depending on the type
  of pattern you found, fill in a recursive</span> <span m=''834470''>or iterative
  code framework. And remember, iterative, recursive and even mixed solutions</span>
  <span m=''840679''>to a single problem may all be correct!</span> </p>'
type: course
uid: ce5f8650709155886f635ecb56351751

---
None