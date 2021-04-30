---
about_this_resource_text: <h2 class="subhead">Summary</h2><p>This video introduces
  students to the notion of stability of equilibria. A temperature example is explored
  using an energy argument, and then the typical linear stability analysis framework
  is introduced. This framework is applied in detail to analyze a pendulum.</p><h2
  class="subhead">Learning Objectives</h2><p>After watching this video students will
  be familiar with the framework of equilibrium and stability analysis.</p><p>Funding
  provided by the Singapore University of Technology and Design (SUTD)</p><p>Developed
  by the Teaching and Learning Laboratory (TLL) at MIT for SUTD</p><p>MIT &copy; 2012</p>
course_id: res-tll-004-stem-concept-videos-fall-2013
embedded_media:
- id: MITRES_TLL-004F13_StbAl_IG.pdf
  parent_uid: 96c4783295d3f194667058829419579a
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/linearity/stability-analysis/MITRES_TLL-004F13_StbAl_IG.pdf
  title: Stability Analysis Instructor Guide
  type: null
  uid: 0c82ede480e5f9c119a12002236df292
- id: Video-YouTube-Stream
  media_location: JrlZSfRM-IY
  parent_uid: 96c4783295d3f194667058829419579a
  title: Video-YouTube-Stream
  type: Video
  uid: af9c7ac95291f073bcfb9bf1431e24a9
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/JrlZSfRM-IY/default.jpg
  parent_uid: 96c4783295d3f194667058829419579a
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: f25e2dbc46c46d8b936c4052a6bfd0ac
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id765926614
  parent_uid: 96c4783295d3f194667058829419579a
  title: Video-iTunes U-MP4
  type: Video
  uid: 74b9f5cd6fa9a58c0876a5af29bbb903
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MITRES.TLL-004F13/MITRES_TLL-004F13_stability_analysis_300k.mp4
  parent_uid: 96c4783295d3f194667058829419579a
  title: Video-Internet Archive-MP4
  type: Video
  uid: df593389fb2cd50c940118cc7b072741
- id: 3Play-3PlayYouTubeid-MP4
  media_location: JrlZSfRM-IY
  parent_uid: 96c4783295d3f194667058829419579a
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 42c19834153f943292d2e11a716a85f8
- id: JrlZSfRM-IY.srt
  parent_uid: 96c4783295d3f194667058829419579a
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/linearity/stability-analysis/JrlZSfRM-IY.srt
  title: 3play caption file
  type: null
  uid: c6f9f9428f65613aaac7edc317b16436
- id: JrlZSfRM-IY.pdf
  parent_uid: 96c4783295d3f194667058829419579a
  technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/linearity/stability-analysis/JrlZSfRM-IY.pdf
  title: 3play pdf file
  type: null
  uid: 7b893a4a8d3e9c38506752a229e5bdb1
- id: Caption-3Play YouTube id-SRT
  parent_uid: 96c4783295d3f194667058829419579a
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: bf2adf56622707b512167a3361aed1fd
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 96c4783295d3f194667058829419579a
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: e2daf70165fa4eca9a5961343de6fc14
inline_embed_id: 36712086stabilityanalysis89535839
layout: video
order_index: null
parent_uid: 408da4444ea5a84d94dbf30ef2be5696
related_resources_text: "<p>Instructor Guide</p>\r\n<p><img src=\"/images/inacessible.gif\"\
  \ alt=\"This resource may not render correctly in a screen reader.\" /><a href=\"\
  ./resolveuid/0c82ede480e5f9c119a12002236df292\" target=\"_blank\">Stability Analysis\
  \ Instructor Guide (PDF)</a></p>"
short_url: stability-analysis
technical_location: https://ocw.mit.edu/resources/res-tll-004-stem-concept-videos-fall-2013/videos/linearity/stability-analysis
template_type: Tabbed
title: Stability Analysis
transcript: "<p><span m='3830'> When you put a cold drink on the kitchen counter the\
  \ counter surface temperature will decrease.</span> <span m='8990'>But, if the cold\
  \ drink is removed, the counter will eventually return to room temperature.</span>\
  \ <span m='16710'>If instead we place a cup of tea on the counter, the counter temperature\
  \ rises; but if we remove</span> <span m='22039'>the cup of tea, the counter top\
  \ eventually returns to room temperature. We say that the</span> <span m='29109'>counter\
  \ at room temperature is a stable equilibrium. In this video, we discuss the world\
  \ from the</span> <span m='36019'>perspective of equilibrium and stability, and\
  \ in particular linear stability.</span> <span m='42440'>This video is part of the\
  \ Linearity video series. Many complex systems are modeled or</span> <span m='48030'>approximated\
  \ as linear because of the mathematical advantages.</span> <span m='53540'>All the\
  \ world is an initial value problem, and the matter merely state variables. However,</span>\
  \ <span m='58570'>and less poetically, there are alternative interpretations of\
  \ physical, and indeed social,</span> <span m='64260'>systems that can prove very\
  \ enlightening.</span> <span m='67049'>The purpose of this video is to introduce\
  \ you to the framework of equilibrium and stability</span> <span m='72260'>analysis.\
  \ We hope this motivates you to study the topic in greater depth.</span> <span m='77360'>To\
  \ appreciate the material you should be familiar with elementary mechanics, ordinary\
  \ differential</span> <span m='82310'>equations, and eigenproblems.</span> <span\
  \ m='90890'>Let's look at the iced drink and hot teacup example from the perspective\
  \ of equilibrium</span> <span m='95800'>and stability.</span> <span m='98509'>In\
  \ this example, the governing partial differential equation is the heat equation\
  \ shown here.</span> <span m='103789'>At equilibrium, the solution of the governing\
  \ equations is time-independent, that is, the</span> <span m='109320'>partial time\
  \ derivative is zero.</span> <span m='112070'>This tells us that the del square\
  \ temperature term must also be zero, which is only possible,</span> <span m='117310'>given\
  \ the boundary conditions, if the entire counter is at room temperature.</span>\
  \ <span m='123690'>Stability refers to the behavior of the system when perturbed\
  \ from a particular equilibrium</span> <span m='128149'>near the uniform counter\
  \ temperature; a stable system returns to the equilibrium state; an</span> <span\
  \ m='133900'>unstable system departs from the equilibrium state.</span> <span m='139390'>We\
  \ say that this equilibrium is stable because if we perturb the temperature by increasing</span>\
  \ <span m='144340'>or decreasing the temperature slightly, it will return to room\
  \ temperature, the equilibrium</span> <span m='149430'>state, after enough time.</span>\
  \ <span m='151980'>Here we intuitively understand that the equilibrium is stable\
  \ from our own experiences. But for</span> <span m='157440'>other situations, we\
  \ need mathematical methods for determining whether or not equilibria</span> <span\
  \ m='162480'>are stable.</span> <span m='163950'>One way to determine if the equilibrium\
  \ of this partial differential equation is stable</span> <span m='168380'>is to\
  \ apply an energy argument.</span> <span m='171020'>Manipulation of this heat equation\
  \ permits us to derive a relationship that describes</span> <span m='175240'>how\
  \ the \"mean square departure\" of the counter temperature from room temperature\
  \ evolves</span> <span m='179810'>over time, as shown here.</span> <span m='182290'>Note\
  \ u(x) is the deviation of the temperature in the counter from room temperature,\
  \ \u03A9 is</span> <span m='187599'>the counter region, and \u0393 is the counter\
  \ surface; d1 and d2 are positive constants\u2014determined</span> <span m='194709'>by\
  \ the thermal properties of the counter.</span> <span m='197690'>Because the right--hand\
  \ side of this equation is negative, it drives the temperature fluctuations\u2014\
  the</span> <span m='202760'>integral of u(x) squared over the counter region\u2014\
  to zero.</span> <span m='208180'>This energy argument is the mathematical prediction\
  \ of the behavior we observe physically.</span> <span m='219120'>Linear stability\
  \ theory refers to the case in which we limit our attention to initially</span>\
  \ <span m='223739'>small perturbations. This allows us to model the evolution with\
  \ linear equation! Linearizing</span> <span m='230410'>the governing equations has\
  \ many mathematical advantages.</span> <span m='234819'>Let's consider the following\
  \ framework for linear stability analysis.</span> <span m='239700'>choose a physical\
  \ system of interest; develop a (typically nonlinear) mathematical</span> <span\
  \ m='245870'>model; identify equilibria;</span> <span m='250819'>linearize the governing\
  \ equations about these equilibria;</span> <span m='254540'>convert the initial\
  \ value problem to an eigenproblem; inspect the eigenvalues and associated eigenmodes</span>\
  \ <span m='261769'>(or eigenvectors)</span> <span m='263860'>Let's see how to use\
  \ this framework as we proceed through the example of the real, physical</span>\
  \ <span m='268080'>pendulum seen here.</span> <span m='270479'>You see a large bob,\
  \ the rod, and a flexural hinge, which is designed to reduce friction</span> <span\
  \ m='275558'>losses.</span> <span m='277939'>Let's develop the mathematical model.\
  \ We show here the simple pendulum consisting</span> <span m='282990'>of a bob connected\
  \ to a massless rod; we denote the (angular) position of the bob by theta(t),</span>\
  \ <span m='290360'>and the angular velocity of the bob by \u03C9(t); g is the acceleration\
  \ due to gravity; and</span> <span m='296259'>L is the effective rod length for\
  \ our simple pendulum.</span> <span m='300180'>The effective length L is chosen\
  \ such that the simple pendulum replicates the dynamics</span> <span m='304900'>of\
  \ the real, physical pendulum; L is calculated from the center of mass, the moment\
  \ of inertia,</span> <span m='310279'>and the mass of the compound pendulum.</span>\
  \ <span m='313789'>The dynamics may be expressed as a coupled system of ordinary\
  \ differential equations</span> <span m='318240'>that describe how the angular displacement\
  \ and angular velocity evolve over time.</span> <span m='323219'>These equations\
  \ are nonlinear due to the presence of sin(\u03B8) and the drag function fdrag(\u03C9\
  ).</span> <span m='330080'>The drag function is quite complicated.</span> <span\
  \ m='332409'>For large \u03C9\u2014it is equal to c|omega|omega, where c is a negative\
  \ constant.</span> <span m='339330'>But for very small angular velocities, near\
  \ points on the trajectory where the pendulum</span> <span m='343270'>isn't moving,\
  \ or at least not moving fast, drag is given by to b omega, where b is a</span>\
  \ <span m='348669'>negative constant.</span> <span m='350779'>Next, let's explore\
  \ the validity of this model. Here you see a comparison between a numerical</span>\
  \ <span m='357150'>simulation, and an experiment, courtesy of Drs. Yano and Penn,\
  \ respectively.</span> <span m='362779'>The numerical simulation is created by calibrating\
  \ the drag function to the experimental data.</span> <span m='368550'>The agreement\
  \ is quite good for both small and large initial displacement angles.</span> <span\
  \ m='373899'>However, because we are fitting the dissipation to the data, this comparison\
  \ does not truly</span> <span m='379689'>validate the mathematical model.</span>\
  \ <span m='382689'>To validate the mathematical model, we must focus on a system\
  \ property that is largely</span> <span m='387419'>independent of the here, small,\
  \ dissipation, such as the natural frequency, or period,</span> <span m='393499'>of\
  \ the pendulum motion.</span> <span m='395110'>And a comparison of the natural frequency\
  \ of the physical pendulum to that predicted</span> <span m='400020'>by the numerical\
  \ model shows that the natural frequencies agree quite well, for any initial</span>\
  \ <span m='406129'>displacement angle, even large.</span> <span m='409050'>We now\
  \ look for equilibrium states, solutions that are independent of time. To find these</span>\
  \ <span m='415058'>equilibria we set the left--hand side of the equations to zero\
  \ and solve for \u03B8 and \u03C9.</span> <span m='420779'>We can readily conclude\
  \ that there are two equilibria:</span> <span m='423689'>(\u03B8, \u03C9) = (0,\
  \ 0), which we denote the \"bottom\"equilibrium; and</span> <span m='428830'>(\u03B8\
  , \u03C9) = (\u03C0, 0), which we denote the \"top\"equilibrium.</span> <span m='433110'>The\
  \ mathematical model actually has infinitely many equilibria corresponding to theta\
  \ values</span> <span m='437960'>that are integral multiples of pi.</span> <span\
  \ m='440099'>But for our stability analysis, two will suffice.</span> <span m='444119'>Are\
  \ these equilibrium solutions stable or unstable for the physical pendulum? Pause</span>\
  \ <span m='449469'>the video here and discuss.</span> <span m='455439'>They are\
  \ stable if a small nudge will result in commensurately small bob motion; They are</span>\
  \ <span m='460679'>unstable, if a small nudge will result in incommensurately large\
  \ bob motion. So we can</span> <span m='466580'>predict that the bottom equilibrium\
  \ is stable; the top equilibrium, unstable. If our mathematical</span> <span m='472619'>model\
  \ is good, it should predict the same behavior as the physical system.</span> <span\
  \ m='477159'>But how do we mathematically analyze stability of our model? Let's\
  \ work through the linear</span> <span m='481869'>stability analysis framework for\
  \ the bottom equilibrium, \u03B8 = 0 and \u03C9 = 0. First, we</span> <span m='489459'>linearize\
  \ the equations about the equilibrium.</span> <span m='492449'>The linearized equations\
  \ are only valid near the equilibrium, theta = 0 and omega =0, i.e.</span> <span\
  \ m='498899'>for small displacements, theta prime, with small angular velocities,\
  \ omega prime.</span> <span m='505020'>The first equation of our system is already\
  \ linear.</span> <span m='508529'>So we only need to worry about linearizing the\
  \ sin(0+\u03B8') term and the dissipation term</span> <span m='514750'>of the second\
  \ equation for small theta prime and omega prime.</span> <span m='519549'>What is\
  \ the linear approximation of sin(theta') about theta=0. Hint: use a Taylor series.</span>\
  \ <span m='526800'>Pause the video and write down your answer.</span> <span m='533080'>If\
  \ we assume that theta prime is small, we can approximate sin(\u03B8') by theta'\
  \ \u2014 the</span> <span m='539060'>deviation of \u03B8 from 0\u2014 by ignoring\
  \ the higher order terms in the Taylor series expansion</span> <span m='545630'>of\
  \ sin theta' about 0.</span> <span m='549020'>Because we are linearizing near omega\
  \ prime sufficiently close to zero, the dissipation</span> <span m='553450'>term\
  \ is asymptotic to b omega prime, as mentioned previously. We then substitute these\
  \ expressions</span> <span m='560330'>into our dynamical equations to obtain the,\
  \ linear equations indicated.</span> <span m='565490'>We must supply initial conditions,\
  \ and the initial angle and angular velocity must be</span> <span m='569930'>small\
  \ in order for this linearized system of equations to be applicable. We now write</span>\
  \ <span m='575840'>the linear equations in matrix form, in order to prepare for\
  \ the next step \u2014 formulation</span> <span m='581080'>as an eigenproblem.</span>\
  \ <span m='583270'>To do this, we assume temporal behavior of the form e\u03BBt.\
  \ This yields an eigenvalue problem</span> <span m='589520'>for \u03BB.</span> <span\
  \ m='590840'>Note that our matrix is 2\xD72 and hence there will be two eigenvalues\
  \ and two associated</span> <span m='595630'>eigenvectors, or eigenmodes.</span>\
  \ <span m='598690'>Once we obtain the eigenvalues and eigenvectors we may reconstruct\
  \ the solution to the linearized</span> <span m='603900'>equations, as shown here;\
  \ the constants c1 and c2 are determined by the initial conditions.</span> <span\
  \ m='610690'>However, to determine stability, a simple inspection of the eigenvalues\
  \ suffices:</span> <span m='617050'>What happens to e to the lambda t when each\
  \ of the eigenvalues has negative real part?</span> <span m='623280'>Pause the video.</span>\
  \ <span m='629430'>We observe that e\u03BBt decays in this case, and the system\
  \ is stable.</span> <span m='636560'>What happens if any of the eigenvalues has\
  \ positive real part? Pause the video.</span> <span m='643250'>If an eigenvalue\
  \ has positive real part \u2014 in which case e\u03BBt corresponds to exponential</span>\
  \ <span m='652680'>growth away from the equilibrium</span> <span m='654200'>\u2014\
  \ the system is unstable; note that even one eigenvalue with a positive real part\
  \ is</span> <span m='659510'>sufficient to deem the system unstable, since sooner\
  \ or later, no matter how small initially,</span> <span m='665840'>the growing exponential\
  \ term will dominate.</span> <span m='668140'>Lastly, if the real part of the eigenvalue\
  \ with largest real part is zero \u2014 in which</span> <span m='673630'>case e\u03BB\
  t is of constant magnitude \u2014 the system is marginally stable and requires further</span>\
  \ <span m='679900'>analysis. We now proceed for our particular system.</span> <span\
  \ m='684180'>For this problem it is easy to find the eigenvalues analytically.</span>\
  \ <span m='688240'>We observe that both \u03BB1 and \u03BB2 have a small negative\
  \ real part - due to our negative damping</span> <span m='693810'>coefficient, b.</span>\
  \ <span m='694840'>Thus, the system is stable as we predicted based on the physical\
  \ pendulum.</span> <span m='700490'>For our experimental system, b L over g is much\
  \ less than 1.</span> <span m='706800'>And thus the damping does indeed have little\
  \ effect on the period of motion. If we recall</span> <span m='712720'>the connection\
  \ between the complex exponential and sine and cosine, we may conclude that</span>\
  \ <span m='718280'>the linearized system response is a very slowly decaying oscillation.\
  \ This linear approximation</span> <span m='725150'>to our governing equations can\
  \ predict not just the stability of the system, but also</span> <span m='729790'>because\
  \ the system is stable, the evolution of the system\u2014assuming of course small\
  \ initial</span> <span m='735500'>conditions</span> <span m='735950'>Indeed, comparing\
  \ our original non-linear numerical solution to the numerical solution</span> <span\
  \ m='742040'>obtained from the linear model, we find that the agreement between\
  \ the two is very good</span> <span m='746600'>for the low-amplitude case.</span>\
  \ <span m='749470'>As advertised, we obtain a solution to the linear model with\
  \ which we can predict the</span> <span m='753860'>motion resulting from small perturbations\
  \ away from equilibrium. But as you see here,</span> <span m='759680'>the accuracy\
  \ of the linear theory is indeed limited to small perturbations</span> <span m='763550'>\u2014\
  \ for even moderately larger angles, the linear model no longer adequately represents</span>\
  \ <span m='768380'>the behavior of the pendulum.</span> <span m='770870'>But this\
  \ is to be expected since the linear approximation of these governing equations</span>\
  \ <span m='775820'>is only valid when theta prime and omega prime are very close\
  \ to zero.</span> <span m='781750'>To Review We have thus linearized the governing\
  \ equations</span> <span m='787310'>for the pendulum near the equilibrium theta\
  \ = 0, omega = 0.</span> <span m='792370'>By solving an eigenvalue problem, we showed\
  \ that the equilibrium was stable at this point.</span> <span m='797600'>The linear\
  \ equations even predict the behavior of the pendulum near this stable equilibrium.</span>\
  \ <span m='804090'>This video has focused primarily on the modal approach to stability\
  \ analysis, which is the</span> <span m='808560'>simplest and arguably the most\
  \ relevant approach in many applications. However, there are other</span> <span\
  \ m='813940'>important approaches too, such as the \"energy\"approach, briefly mentioned\
  \ at the outset of the video.</span> <span m='821290'>We shall leave to you to analyze\
  \ the case of the \"top\"equilibrium, which we predicted</span> <span m='828560'>to\
  \ be unstable.</span> <span m='830480'>You'll find that there's an unstable mode\
  \ AND a stable mode. The unstable mode will</span> <span m='835840'>ultimately dominate,\
  \ but the stable mode is still surprising. Our intuition suggests than</span> <span\
  \ m='841070'>any perturbation should grow. The stable mode requires a precise specification\
  \ of both initial</span> <span m='847800'>angular displacement AND initial angular\
  \ velocity. This explains the apparent contradiction between</span> <span m='854320'>the\
  \ mathematics and our expectations.</span> </p>"
type: course
uid: 96c4783295d3f194667058829419579a

---
None