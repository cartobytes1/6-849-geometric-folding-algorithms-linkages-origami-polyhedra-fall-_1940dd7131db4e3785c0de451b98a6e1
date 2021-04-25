---
about_this_resource_text: <p><strong>Description:</strong> This class begins with
  defining handles and holes, and the Gauss-Bonnet Theorem applied to convex polyhedra.
  Algorithms for zipper unfolding, edge ununfoldable polyhedra, square-packing, band
  unfolding, and blooming of convex polyhedra are presented.</p> <p><strong>Speaker:</strong>
  Erik Demaine</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: tzXIDPNb93Y
  parent_uid: d9531943ae9e6a5bfbd385007b052267
  title: Video-YouTube-Stream
  type: Video
  uid: 8bd13a3d88f770bb284e4c7939c6687d
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/tzXIDPNb93Y/default.jpg
  parent_uid: d9531943ae9e6a5bfbd385007b052267
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: be9f2c7cea07aeb404488437fa883b14
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: d9531943ae9e6a5bfbd385007b052267
  title: Video-iTunes U-MP4
  type: Video
  uid: bc25ea1072e950bfdf3a86831e084885
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_class15_300k.mp4
  parent_uid: d9531943ae9e6a5bfbd385007b052267
  title: Video-Internet Archive-MP4
  type: Video
  uid: 6e663da135b8155b45766997561e8dda
- id: 3Play-3PlayYouTubeid-MP4
  media_location: tzXIDPNb93Y
  parent_uid: d9531943ae9e6a5bfbd385007b052267
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: a43009727ab281bf89869aa1c7386d41
- id: tzXIDPNb93Y.srt
  parent_uid: d9531943ae9e6a5bfbd385007b052267
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/class-15-general-edge-unfolding/tzXIDPNb93Y.srt
  title: 3play caption file
  type: null
  uid: 04779b9f3bda0340f2c7d69081a4d4a9
- id: tzXIDPNb93Y.pdf
  parent_uid: d9531943ae9e6a5bfbd385007b052267
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/class-15-general-edge-unfolding/tzXIDPNb93Y.pdf
  title: 3play pdf file
  type: null
  uid: c8438ff65debeb7896ef85478e62c653
- id: Caption-3Play YouTube id-SRT
  parent_uid: d9531943ae9e6a5bfbd385007b052267
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b836b30dabcedbbd581c049de312e87e
- id: Transcript-3Play YouTube id-PDF
  parent_uid: d9531943ae9e6a5bfbd385007b052267
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f37e56d91cf826fef7cdd250354d408f
inline_embed_id: 67479769class15:general&edgeunfolding32221968
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: class-15-general-edge-unfolding
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/class-15-general-edge-unfolding
template_type: Tabbed
title: 'Class 15: General & Edge Unfolding'
transcript: <p><span m='3255'>PROFESSOR:</span> <span m='3720'>We</span> <span m='3850'>have</span>
  <span m='3960'>a</span> <span m='4019'>lot</span> <span m='4190'>of</span> <span
  m='4280'>fun</span> <span m='4500'>material</span> <span m='4980'>to</span> <span
  m='5140'>cover</span> <span m='5420'>today,</span> <span m='5840'>so</span> <span
  m='5950'>let's</span> <span m='6230'>get</span> <span m='6380'>started.</span> <span
  m='7610'>We</span> <span m='7810'>start</span> <span m='8090'>with</span> <span
  m='8300'>a</span> <span m='8360'>few</span> <span m='8860'>basic</span> <span m='9200'>questions</span>
  <span m='9840'>about--</span> <span m='10920'>well,</span> <span m='11400'>first</span>
  <span m='11670'>is</span> <span m='11780'>a</span> <span m='11840'>topology</span>
  <span m='12330'>question.</span> <span m='13110'>What</span> <span m='13380'>is</span>
  <span m='13600'>a</span> <span m='13650'>handle?</span> <span m='15580'>In</span>
  <span m='15790'>general,</span> <span m='17190'>a</span> <span m='17250'>handle</span>
  <span m='17610'>is</span> <span m='17740'>really</span> <span m='17960'>a</span>
  <span m='18030'>transformation</span> <span m='18780'>on</span> <span m='18890'>a</span>
  <span m='18960'>surface.</span> <span m='19470'>I</span> <span m='19580'>thought</span>
  <span m='19790'>I</span> <span m='19870'>will</span> <span m='19980'>demonstrate</span>
  <span m='20520'>in</span> <span m='20690'>the</span> <span m='20780'>context</span>
  <span m='21160'>of</span> <span m='21230'>glass</span> <span m='21560'>blowing.</span>
  </p><p><span m='22190'>So</span> <span m='22520'>this</span> <span m='22760'>is</span>
  <span m='22890'>what</span> <span m='23050'>it</span> <span m='23110'>looks</span>
  <span m='23320'>like if</span> <span m='23570'>you're</span> <span m='23690'>making</span>
  <span m='24000'>a</span> <span m='24090'>cup.</span> <span m='24860'>You</span>
  <span m='24980'>take</span> <span m='25280'>some</span> <span m='25660'>hot</span>
  <span m='25940'>glass.</span> <span m='26800'>You</span> <span m='27060'>attach</span>
  <span m='27530'>it</span> <span m='27770'>to</span> <span m='28110'>your</span>
  <span m='28360'>surface.</span> <span m='29470'>You</span> <span m='30750'>cut</span>
  <span m='30960'>it</span> <span m='31080'>off</span> <span m='31340'>your hot</span>
  <span m='31800'>pipe.</span> <span m='32430'>And</span> <span m='32650'>then</span>
  <span m='32800'>you</span> <span m='33720'>bring</span> <span m='33930'>it</span>
  <span m='33990'>around</span> <span m='35360'>and</span> <span m='35830'>attach</span>
  <span m='36290'>it</span> <span m='36500'>to</span> <span m='37510'>another</span>
  <span m='37830'>point,</span> <span m='39100'>and</span> <span m='39270'>so</span>
  <span m='39800'>that's</span> <span m='39990'>a</span> <span m='40080'>handle.</span>
  </p><p><span m='41100'>You've</span> <span m='41320'>probably</span> <span m='41760'>used</span>
  <span m='41960'>handles</span> <span m='42330'>before</span> <span m='43720'>in</span>
  <span m='43860'>real</span> <span m='44060'>life.</span> <span m='45490'>In</span>
  <span m='45670'>general,</span> <span m='46790'>or</span> <span m='47200'>in</span>
  <span m='47730'>the</span> <span m='47830'>mathematical</span> <span m='48460'>setting,</span>
  <span m='48790'>it's</span> <span m='48930'>the</span> <span m='49010'>same</span>
  <span m='49240'>thing</span> <span m='49530'>but</span> <span m='50150'>on</span>
  <span m='50340'>a</span> <span m='50420'>2D</span> <span m='50740'>surface.</span>
  <span m='52120'>So</span> <span m='53690'>imagine</span> <span m='54020'>you</span>
  <span m='54110'>have</span> <span m='54370'>some</span> <span m='54580'>2D</span>
  <span m='54840'>surface.</span> <span m='55700'>You</span> <span m='55830'>take</span>
  <span m='56180'>two</span> <span m='56990'>disk-like</span> <span m='58840'>regions</span>
  <span m='59190'>on</span> <span m='59350'>the</span> <span m='59430'>surface</span>
  <span m='60420'>and</span> <span m='60610'>then</span> <span m='60730'>you</span>
  <span m='60860'>attach</span> <span m='61370'>on</span> <span m='62730'>a</span>
  <span m='62800'>handle--</span> <span m='66780'>something</span> <span m='67060'>like</span>
  <span m='67240'>that.</span> </p><p><span m='68660'>So</span> <span m='68900'>it's</span>
  <span m='69070'>an</span> <span m='69150'>operation</span> <span m='69770'>you</span>
  <span m='69900'>can</span> <span m='70030'>do</span> <span m='70240'>to</span> <span
  m='70480'>a</span> <span m='70550'>surface.</span> <span m='71470'>And</span> <span
  m='71840'>you</span> <span m='72020'>can</span> <span m='72190'>keep</span> <span
  m='72460'>adding</span> <span m='72710'>handles.</span> <span m='74330'>I</span>
  <span m='74460'>don't</span> <span m='74710'>think</span> <span m='74890'>there's</span>
  <span m='75060'>a</span> <span m='75200'>clear</span> <span m='75460'>way</span>
  <span m='75620'>to</span> <span m='75750'>say,</span> <span m='76100'>oh,</span>
  <span m='76250'>this</span> <span m='76530'>is</span> <span m='76640'>clearly a</span>
  <span m='77060'>handle,</span> <span m='77480'>except</span> <span m='77810'>to</span>
  <span m='77960'>have</span> <span m='78310'>added</span> <span m='78690'>it</span>
  <span m='78840'>as</span> <span m='79030'>a</span> <span m='79070'>handle.</span>
  </p><p><span m='80850'>In</span> <span m='81050'>general,</span> <span m='82090'>the</span>
  <span m='82200'>nice</span> <span m='82510'>theorem</span> <span m='83420'>for</span>
  <span m='83670'>two</span> <span m='83820'>dimensional</span> <span m='84240'>surfaces--</span>
  <span m='85230'>so</span> <span m='85370'>here's</span> <span m='85710'>a</span>
  <span m='86860'>coffee</span> <span m='87150'>cup</span> <span m='87440'>being</span>
  <span m='87650'>converted</span> <span m='88130'>into</span> <span m='88280'>a</span>
  <span m='88360'>torus,</span> <span m='88910'>because</span> <span m='89090'>it</span>
  <span m='89200'>has</span> <span m='89890'>genus</span> <span m='90200'>1,</span>
  <span m='90410'>meaning</span> <span m='90730'>it</span> <span m='90790'>has</span>
  <span m='91080'>essentially</span> <span m='91490'>one</span> <span m='91710'>handle</span>
  <span m='92080'>in</span> <span m='92170'>it.</span> <span m='93120'>In</span> <span
  m='93280'>general,</span> <span m='93710'>you</span> <span m='93850'>take</span>
  <span m='94060'>any</span> <span m='94400'>orientable</span> <span m='95030'>surface</span>
  <span m='95410'>without</span> <span m='95760'>boundary--</span> <span m='97080'>this
  is</span> <span m='97550'>locally</span> <span m='97920'>two</span> <span m='98070'>dimensional--</span>
  <span m='99030'>then</span> <span m='99260'>it</span> <span m='99370'>will</span>
  <span m='99870'>be a</span> <span m='100340'>sphere</span> <span m='101200'>plus</span>
  <span m='101880'>some</span> <span m='102990'>non-negative</span> <span m='103760'>number</span>
  <span m='104110'>of</span> <span m='104260'>handles.</span> <span m='105820'>And</span>
  <span m='105900'>that's</span> <span m='107500'>a</span> <span m='107840'>classification</span>
  <span m='108550'>theorem</span> <span m='108970'>for</span> <span m='109400'>orientable</span>
  <span m='109910'>surfaces.</span> </p><p><span m='110570'>It's</span> <span m='111130'>only</span>
  <span m='111340'>slightly</span> <span m='111720'>more</span> <span m='111890'>complicated</span>
  <span m='112390'>for</span> <span m='112510'>non-orientable</span> <span m='113150'>surfaces.</span>
  <span m='113700'>And</span> <span m='113820'>then</span> <span m='115470'>3D</span>
  <span m='116240'>surfaces</span> <span m='116680'>are</span> <span m='116800'>even</span>
  <span m='117000'>harder</span> <span m='118840'>and</span> <span m='119220'>was</span>
  <span m='119340'>only</span> <span m='119550'>recently</span> <span m='119880'>solved.</span>
  <span m='120410'>But</span> <span m='120690'>this</span> <span m='120880'>is</span>
  <span m='122970'>two</span> <span m='123110'>dimensional</span> <span m='123470'>surfaces,</span>
  <span m='123950'>which</span> <span m='124150'>is</span> <span m='124330'>easy</span>
  <span m='124700'>and</span> <span m='124890'>clean.</span> </p><p><span m='127730'>There</span>
  <span m='127900'>is</span> <span m='128009'>a</span> <span m='128070'>way</span>
  <span m='128199'>to</span> <span m='128340'>compute</span> <span m='128860'>genus</span>
  <span m='129280'>and</span> <span m='129370'>in</span> <span m='129449'>some</span>
  <span m='129650'>sense</span> <span m='129919'>learn</span> <span m='130100'>how</span>
  <span m='130340'>many</span> <span m='130580'>handles</span> <span m='131020'>are</span>
  <span m='131220'>there.</span> <span m='132130'>But</span> <span m='132610'>there</span>
  <span m='132800'>isn't</span> <span m='133000'>a</span> <span m='133060'>unique</span>
  <span m='133590'>thing</span> <span m='133980'>of,</span> <span m='134130'>oh,</span>
  <span m='134530'>this</span> <span m='134740'>part</span> <span m='135000'>is</span>
  <span m='135120'>clearly a</span> <span m='135460'>handle.</span> <span m='136360'>But
  when</span> <span m='136560'>you</span> <span m='136650'>draw</span> <span m='136930'>it</span>
  <span m='137020'>this</span> <span m='137190'>way,</span> <span m='137420'>it</span>
  <span m='138020'>kind</span> <span m='138240'>of</span> <span m='138320'>becomes</span>
  <span m='138670'>clear</span> <span m='138860'>this</span> <span m='139050'>is</span>
  <span m='139140'>a</span> <span m='139180'>handle.</span> <span m='139470'>This</span>
  <span m='139600'>is</span> <span m='139730'>a</span> <span m='139770'>handle.</span>
  <span m='140060'>But</span> <span m='140200'>there</span> <span m='140420'>isn't
  a</span> <span m='140540'>formal</span> <span m='140890'>sense</span> <span m='141220'>in</span>
  <span m='141310'>which--</span> <span m='142710'>I</span> <span m='142770'>don't</span>
  <span m='142920'>know--</span> <span m='144140'>this</span> <span m='144480'>thing</span>
  <span m='144810'>is</span> <span m='144950'>not</span> <span m='145170'>a</span>
  <span m='145190'>handle</span> <span m='145860'>or</span> <span m='146563'>some</span>
  <span m='146906'>weird</span> <span m='147250'>thing.</span> </p><p><span m='149170'>I</span>
  <span m='149240'>think</span> <span m='149480'>that's</span> <span m='149720'>all</span>
  <span m='149870'>about</span> <span m='150140'>handles.</span> <span m='152700'>Hopefully</span>
  <span m='152950'>that</span> <span m='153110'>answers</span> <span m='153480'>things.</span>
  <span m='153810'>Of</span> <span m='153900'>course,</span> <span m='154130'>things</span>
  <span m='154380'>get</span> <span m='154830'>more</span> <span m='155010'>complicated</span>
  <span m='155420'>when</span> <span m='155510'>you</span> <span m='155580'>have</span>
  <span m='155740'>a</span> <span m='155770'>boundary,</span> <span m='157110'>which</span>
  <span m='157230'>we</span> <span m='157340'>usually</span> <span m='157600'>call</span>
  <span m='157810'>holes.</span> <span m='158630'>But</span> <span m='158840'>the</span>
  <span m='158930'>next</span> <span m='159150'>question</span> <span m='159470'>is</span>
  <span m='159590'>about</span> <span m='160000'>holes</span> <span m='160510'>in</span>
  <span m='160810'>the</span> <span m='161060'>unfoldings.</span> </p><p><span m='163620'>So</span>
  <span m='163790'>I</span> <span m='163870'>claim</span> <span m='164270'>that</span>
  <span m='164440'>convex</span> <span m='165620'>polyhedron,</span> <span m='166170'>when</span>
  <span m='166250'>you</span> <span m='166380'>unfold them,</span> <span m='166870'>never</span>
  <span m='167210'>have</span> <span m='167450'>holes</span> <span m='168270'>in</span>
  <span m='168480'>the</span> <span m='168950'>unfolded</span> <span m='169760'>form.</span>
  <span m='170490'>And</span> <span m='170690'>this</span> <span m='170830'>is</span>
  <span m='170930'>to</span> <span m='171030'>contrast</span> <span m='171600'>this</span>
  <span m='171790'>example,</span> <span m='172250'>which</span> <span m='172410'>is</span>
  <span m='172520'>not</span> <span m='172740'>convex.</span> <span m='173760'>But</span>
  <span m='174010'>you</span> <span m='174170'>can</span> <span m='174330'>unfold</span>
  <span m='174810'>it</span> <span m='174910'>by</span> <span m='175020'>cutting</span>
  <span m='175430'>these</span> <span m='175650'>two</span> <span m='175820'>edges.</span>
  <span m='176770'>And</span> <span m='176950'>you've</span> <span m='177070'>got</span>
  <span m='177250'>a</span> <span m='177290'>little</span> <span m='177510'>hole.</span>
  </p><p><span m='177850'>So I</span> <span m='178040'>showed</span> <span m='178240'>this</span>
  <span m='178570'>in</span> <span m='178670'>lecture.</span> <span m='179620'>And</span>
  <span m='180000'>natural</span> <span m='180280'>question</span> <span m='180590'>is,</span>
  <span m='180680'>why</span> <span m='181120'>isn't</span> <span m='181390'>this</span>
  <span m='181560'>possible</span> <span m='183290'>for</span> <span m='183470'>convex</span>
  <span m='183890'>polyhedron?</span> <span m='185290'>So</span> <span m='185500'>I</span>
  <span m='185610'>thought</span> <span m='185830'>I</span> <span m='185930'>would</span>
  <span m='186110'>prove</span> <span m='186570'>that.</span> </p><p><span m='186900'>And</span>
  <span m='187220'>the</span> <span m='187330'>proof</span> <span m='187630'>uses</span>
  <span m='188530'>a</span> <span m='188620'>cool</span> <span m='188850'>theorem,</span>
  <span m='189350'>which we'll</span> <span m='189570'>probably</span> <span m='189870'>be</span>
  <span m='189990'>seeing</span> <span m='190320'>again,</span> <span m='191250'>called</span>
  <span m='191460'>the</span> <span m='191540'>Gauss-Bonnet</span> <span m='192160'>theorem.</span>
  <span m='195270'>And</span> <span m='196010'>it</span> <span m='196200'>says</span>
  <span m='196740'>that</span> <span m='196990'>if</span> <span m='197180'>you</span>
  <span m='197340'>have</span> <span m='198880'>some</span> <span m='199340'>surface,</span>
  <span m='201030'>which</span> <span m='201360'>is</span> <span m='201590'>homeomorphic</span>
  <span m='202220'>to</span> <span m='202360'>a</span> <span m='202600'>sphere--</span>
  <span m='204330'>so</span> <span m='204500'>I</span> <span m='204580'>don't</span>
  <span m='204770'>want</span> <span m='204950'>any</span> <span m='205100'>handles</span>
  <span m='205640'>for</span> <span m='205740'>this</span> <span m='206020'>theorem.</span>
  <span m='207430'>And</span> <span m='207570'>of</span> <span m='207650'>course,</span>
  <span m='207870'>convex</span> <span m='208240'>polyhedra</span> <span m='209290'>our</span>
  <span m='209600'>sphere-like.</span> <span m='210080'>They</span> <span m='210180'>don't</span>
  <span m='210370'>have</span> <span m='210540'>handles.</span> </p><p><span m='212310'>And</span>
  <span m='212480'>I</span> <span m='212570'>take</span> <span m='213230'>a--</span>
  <span m='214076'>let me</span> <span m='214462'>take a</span> <span m='214850'>better</span>
  <span m='215210'>color--</span> <span m='216770'>I</span> <span m='216870'>take</span>
  <span m='217180'>a</span> <span m='217380'>closed</span> <span m='218130'>curve</span>
  <span m='218710'>non-self-intersecting</span> <span m='219890'>closed</span> <span
  m='220310'>curve</span> <span m='221920'>on</span> <span m='222230'>that</span>
  <span m='222780'>surface--</span> <span m='224400'>that</span> <span m='224590'>defines</span>
  <span m='225130'>an</span> <span m='225320'>interior</span> <span m='226790'>and
  an</span> <span m='227120'>exterior.</span> <span m='229290'>Then</span> <span m='231530'>what</span>
  <span m='231730'>the</span> <span m='231790'>Gauss-Bonnet</span> <span m='232300'>theorem</span>
  <span m='232590'>says</span> <span m='233420'>is that</span> <span m='233750'>if</span>
  <span m='233950'>you</span> <span m='234120'>look</span> <span m='234350'>at</span>
  <span m='234550'>the</span> <span m='235210'>curvature</span> <span m='236600'>that's</span>
  <span m='236850'>enclosed</span> <span m='237480'>by</span> <span m='237640'>the</span>
  <span m='237770'>curve--</span> <span m='241090'>the</span> <span m='241210'>total</span>
  <span m='241540'>curvature</span> <span m='249300'>by</span> <span m='249420'>this</span>
  <span m='249600'>closed</span> <span m='249950'>curve</span> <span m='250250'>on</span>
  <span m='250370'>the</span> <span m='250460'>surface--</span> <span m='252150'>and</span>
  <span m='252390'>you</span> <span m='252630'>add</span> <span m='252960'>on</span>
  <span m='254120'>the</span> <span m='256430'>total</span> <span m='256839'>turn</span>
  <span m='257140'>angle</span> <span m='261329'>along</span> <span m='261750'>the</span>
  <span m='261890'>curve--</span> <span m='267620'>so</span> <span m='267820'>here,</span>
  <span m='268210'>the</span> <span m='268330'>curve is</span> <span m='268610'>turning</span>
  <span m='268950'>right.</span> <span m='269400'>Here,</span> <span m='269540'>it's</span>
  <span m='269690'>turning</span> <span m='270020'>left,</span> <span m='270560'>right,</span>
  <span m='271150'>left.</span> <span m='272150'>Left</span> <span m='272420'>is</span>
  <span m='272550'>positive.</span> <span m='273440'>Right</span> <span m='273670'>is</span>
  <span m='273800'>negative.</span> </p><p><span m='274930'>Then</span> <span m='275690'>these</span>
  <span m='276050'>always</span> <span m='276370'>add</span> <span m='276600'>up</span>
  <span m='276740'>to</span> <span m='276850'>360</span> <span m='277550'>degrees.</span>
  <span m='279290'>We're</span> <span m='279410'>not</span> <span m='279540'>going</span>
  <span m='279630'>to</span> <span m='279690'>prove</span> <span m='279950'>this</span>
  <span m='280150'>theorem,</span> <span m='280340'>but</span> <span m='280510'>we're</span>
  <span m='280680'>going</span> <span m='280820'>to</span> <span m='280870'>use</span>
  <span m='281160'>it.</span> <span m='282290'>So</span> <span m='282510'>this</span>
  <span m='282690'>is</span> <span m='282820'>a</span> <span m='282880'>nice</span>
  <span m='283420'>invariant</span> <span m='284040'>for</span> <span m='284360'>sphere-like</span>
  <span m='284880'>things.</span> </p><p><span m='285820'>When</span> <span m='285940'>you</span>
  <span m='286020'>have</span> <span m='286190'>handles,</span> <span m='286650'>this</span>
  <span m='286920'>number</span> <span m='287220'>changes.</span> <span m='287810'>I</span>
  <span m='287910'>think</span> <span m='287960'>it's</span> <span m='288100'>0</span>
  <span m='288430'>for</span> <span m='288610'>a</span> <span m='288670'>torus.</span>
  <span m='290566'>Well,</span> <span m='291000'>I</span> <span m='291100'>won't</span>
  <span m='291270'>try</span> <span m='291440'>to</span> <span m='291720'>guess</span>
  <span m='291960'>it,</span> <span m='292070'>because</span> <span m='292290'>it's</span>
  <span m='293070'>a</span> <span m='293130'>little</span> <span m='293310'>bit</span>
  <span m='293490'>subtle</span> <span m='293880'>to</span> <span m='294010'>get</span>
  <span m='294180'>right.</span> </p><p><span m='295150'>One</span> <span m='295560'>fun</span>
  <span m='296140'>consequence</span> <span m='296800'>of</span> <span m='296880'>this--</span>
  <span m='297110'>let's</span> <span m='297270'>just</span> <span m='297530'>get</span>
  <span m='298030'>warmed</span> <span m='298300'>up--</span> <span m='298420'>suppose</span>
  <span m='298820'>you</span> <span m='298940'>take</span> <span m='299240'>a</span>
  <span m='299360'>sphere</span> <span m='299650'>like</span> <span m='299870'>object</span>
  <span m='301640'>and</span> <span m='301960'>you</span> <span m='302100'>take</span>
  <span m='302570'>a</span> <span m='302680'>closed</span> <span m='303120'>curve--</span>
  <span m='304120'>this is</span> <span m='304250'>going</span> <span m='304440'>to</span>
  <span m='304480'>be</span> <span m='304620'>pretty</span> <span m='304850'>abstract--</span>
  <span m='306140'>in</span> <span m='306320'>this</span> <span m='306530'>direction,</span>
  <span m='307400'>then</span> <span m='307640'>it</span> <span m='307730'>says,</span>
  <span m='308210'>OK,</span> <span m='310300'>the</span> <span m='310890'>total</span>
  <span m='311150'>amount</span> <span m='311330'>of</span> <span m='311410'>curvature</span>
  <span m='311850'>in</span> <span m='312000'>here</span> <span m='312770'>plus</span>
  <span m='313200'>the</span> <span m='313380'>total</span> <span m='313680'>turn</span>
  <span m='313920'>angle</span> <span m='314680'>equals</span> <span m='315060'>360.</span>
  <span m='316840'>Now</span> <span m='316980'>suppose</span> <span m='317520'>that</span>
  <span m='317680'>I</span> <span m='318020'>turn</span> <span m='318260'>the</span>
  <span m='318350'>curve</span> <span m='318630'>around.</span> <span m='319710'>So</span>
  <span m='320170'>I</span> <span m='321670'>just</span> <span m='322150'>reverse</span>
  <span m='322610'>the</span> <span m='322710'>direction--</span> <span m='325795'>like</span>
  <span m='326770'>this.</span> </p><p><span m='328660'>And</span> <span m='328850'>so</span>
  <span m='328950'>now,</span> <span m='329150'>the</span> <span m='329290'>interior</span>
  <span m='329840'>is</span> <span m='330030'>this</span> <span m='330150'>stuff</span>
  <span m='330440'>out</span> <span m='330600'>here.</span> <span m='332190'>And</span>
  <span m='332650'>then</span> <span m='332810'>we</span> <span m='332910'>get</span>
  <span m='333100'>that</span> <span m='333240'>the</span> <span m='333360'>total</span>
  <span m='333860'>curvature</span> <span m='334500'>outside</span> <span m='335020'>the</span>
  <span m='335100'>curve,</span> <span m='335950'>plus</span> <span m='336700'>the</span>
  <span m='336900'>total</span> <span m='337180'>turn</span> <span m='337455'>angle
  of</span> <span m='337730'>the</span> <span m='337800'>blue</span> <span m='338020'>thing,</span>
  <span m='338450'>equals</span> <span m='338780'>360.</span> <span m='340120'>If</span>
  <span m='340190'>I</span> <span m='340290'>add</span> <span m='340530'>those</span>
  <span m='340720'>two</span> <span m='340850'>equations</span> <span m='341270'>together,</span>
  <span m='342410'>the</span> <span m='342600'>total</span> <span m='342890'>turn</span>
  <span m='343130'>angle</span> <span m='343390'>cancels.</span> <span m='343950'>Because</span>
  <span m='344300'>wherever</span> <span m='344850'>red</span> <span m='345090'>turns,</span>
  <span m='345340'>left</span> <span m='345690'>blue</span> <span m='345880'>turns</span>
  <span m='346190'>right.</span> <span m='346990'>And</span> <span m='347170'>so</span>
  <span m='347390'>this</span> <span m='347640'>term</span> <span m='348190'>disappears.</span>
  </p><p><span m='349280'>And</span> <span m='349450'>so</span> <span m='349660'>what
  we</span> <span m='349780'>get</span> <span m='349970'>is</span> <span m='350120'>that</span>
  <span m='350290'>the</span> <span m='350410'>total</span> <span m='350810'>curvature</span>
  <span m='351200'>inside</span> <span m='351620'>the</span> <span m='351700'>curve,</span>
  <span m='351970'>plus</span> <span m='352230'>the</span> <span m='352310'>total</span>
  <span m='352610'>curvature</span> <span m='353010'>outside</span> <span m='353370'>the</span>
  <span m='353460'>curve,</span> <span m='353700'>equals</span> <span m='354070'>720.</span>
  <span m='355260'>So</span> <span m='355320'>this</span> <span m='355460'>is</span>
  <span m='355600'>a</span> <span m='355650'>nice</span> <span m='356040'>topological</span>
  <span m='356680'>invariant</span> <span m='357170'>of</span> <span m='359990'>sphere-like</span>
  <span m='361170'>polyhedra.</span> <span m='361750'>You</span> <span m='361890'>add</span>
  <span m='362040'>up</span> <span m='362150'>the</span> <span m='362290'>total</span>
  <span m='362660'>curvature</span> <span m='363150'>everywhere--</span> <span m='364230'>it
  didn't</span> <span m='364430'>really</span> <span m='364620'>matter</span> <span
  m='364880'>what</span> <span m='365020'>the</span> <span m='365120'>curve</span>
  <span m='365380'>was--</span> <span m='366530'>you</span> <span m='366710'>always</span>
  <span m='366920'>get</span> <span m='367090'>720.</span> </p><p><span m='368150'>And
  so</span> <span m='368410'>this is</span> <span m='368620'>kind</span> <span m='368780'>of</span>
  <span m='368840'>neat.</span> <span m='369720'>For</span> <span m='369850'>convex</span>
  <span m='370230'>polyhedra,</span> <span m='370740'>this</span> <span m='370900'>means</span>
  <span m='371080'>you</span> <span m='371170'>have</span> <span m='371280'>to</span>
  <span m='371400'>somehow</span> <span m='371740'>divvy</span> <span m='372120'>up</span>
  <span m='372280'>this</span> <span m='372810'>curvature.</span> <span m='373240'>Because</span>
  <span m='373400'>all</span> <span m='373560'>curvatures</span> <span m='374000'>are</span>
  <span m='374080'>positive.</span> <span m='374560'>So</span> <span m='374810'>720</span>
  <span m='375155'>is,</span> <span m='375500'>somehow,</span> <span m='375810'>spread</span>
  <span m='376120'>around.</span> <span m='377400'>But</span> <span m='377530'>you</span>
  <span m='377620'>have</span> <span m='377810'>to</span> <span m='377900'>have</span>
  <span m='377990'>exactly</span> <span m='378410'>that</span> <span m='378580'>much.</span>
  </p><p><span m='379980'>For</span> <span m='380320'>non-convex</span> <span m='380920'>things,</span>
  <span m='381160'>you</span> <span m='381250'>could</span> <span m='381360'>have</span>
  <span m='381500'>some</span> <span m='381710'>negative</span> <span m='382040'>curvature</span>
  <span m='382430'>that</span> <span m='382550'>balances</span> <span m='383070'>out</span>
  <span m='383380'>a</span> <span m='383450'>lot</span> <span m='383630'>of</span>
  <span m='383700'>positive</span> <span m='384140'>curvature.</span> <span m='384570'>So</span>
  <span m='384650'>you</span> <span m='384710'>can</span> <span m='384790'>have</span>
  <span m='384890'>a</span> <span m='384910'>lot</span> <span m='385160'>of</span>
  <span m='385270'>both.</span> <span m='386180'>But</span> <span m='386310'>you</span>
  <span m='386390'>have</span> <span m='386620'>almost</span> <span m='387000'>the</span>
  <span m='387060'>same</span> <span m='387310'>amount</span> <span m='387580'>of</span>
  <span m='387660'>each.</span> <span m='388490'>Just you</span> <span m='388790'>have</span>
  <span m='388960'>exactly</span> <span m='389380'>720</span> <span m='390400'>excess.</span>
  </p><p><span m='391360'>that's</span> <span m='391470'>just</span> <span m='391640'>a</span>
  <span m='391690'>fun</span> <span m='391940'>fact.</span> <span m='392220'>We'll</span>
  <span m='392300'>be</span> <span m='392420'>using</span> <span m='392690'>that</span>
  <span m='392870'>in</span> <span m='392980'>the</span> <span m='393050'>future,</span>
  <span m='393410'>I</span> <span m='393470'>think.</span> <span m='398370'>OK,</span>
  <span m='398680'>that</span> <span m='399000'>was</span> <span m='400070'>Gauss-Bonnet.</span>
  </p><p><span m='400670'>Now</span> <span m='400840'>let's</span> <span m='401070'>use</span>
  <span m='401280'>it</span> <span m='401410'>to</span> <span m='401480'>prove</span>
  <span m='401930'>that</span> <span m='402160'>this</span> <span m='402380'>can't</span>
  <span m='402640'>happen</span> <span m='403460'>for</span> <span m='403720'>convex</span>
  <span m='404200'>polyhedron.</span> <span m='406610'>So</span> <span m='406880'>the</span>
  <span m='407020'>idea</span> <span m='407310'>is,</span> <span m='407500'>suppose</span>
  <span m='407890'>you</span> <span m='407990'>have</span> <span m='408200'>an</span>
  <span m='408280'>unfolding</span> <span m='410030'>with</span> <span m='410220'>a</span>
  <span m='410290'>hole</span> <span m='410580'>in</span> <span m='410660'>it.</span>
  <span m='412920'>So</span> <span m='413130'>this</span> <span m='413310'>is</span>
  <span m='413450'>the</span> <span m='413600'>surface</span> <span m='414150'>out</span>
  <span m='414300'>here.</span> <span m='418100'>Then</span> <span m='418330'>I'm</span>
  <span m='418440'>going</span> <span m='418650'>to</span> <span m='418770'>take</span>
  <span m='419260'>a</span> <span m='419540'>closed</span> <span m='419970'>curve</span>
  <span m='420380'>that</span> <span m='420580'>walks</span> <span m='420950'>around</span>
  <span m='421610'>the</span> <span m='421710'>hole</span> <span m='423390'>but</span>
  <span m='423580'>stays</span> <span m='423910'>inside</span> <span m='424410'>the</span>
  <span m='424590'>unfolding.</span> <span m='426290'>And</span> <span m='426440'>then,</span>
  <span m='426560'>of</span> <span m='426660'>course,</span> <span m='426880'>I'm</span>
  <span m='427010'>visualizing</span> <span m='427610'>that</span> <span m='427790'>really</span>
  <span m='428150'>on</span> <span m='428440'>the</span> <span m='428590'>polyhedron.</span>
  </p><p><span m='430420'>So</span> <span m='431710'>I</span> <span m='431780'>want</span>
  <span m='432020'>the</span> <span m='432160'>interior</span> <span m='432730'>of</span>
  <span m='432970'>the</span> <span m='433070'>curve</span> <span m='433440'>to</span>
  <span m='433610'>enclose</span> <span m='434090'>the</span> <span m='434190'>hole--</span>
  <span m='434720'>or</span> <span m='434840'>what</span> <span m='435040'>becomes</span>
  <span m='435440'>the</span> <span m='435530'>hole.</span> <span m='436850'>Now,</span>
  <span m='437050'>what</span> <span m='437220'>we</span> <span m='437370'>learned</span>
  <span m='437670'>from</span> <span m='437820'>Gauss-Bonnet</span> <span m='438790'>is</span>
  <span m='438970'>that</span> <span m='439070'>the</span> <span m='439180'>curvature</span>
  <span m='439670'>enclosed</span> <span m='440140'>by</span> <span m='440280'>this</span>
  <span m='440520'>thing,</span> <span m='441160'>plus</span> <span m='441460'>the</span>
  <span m='441570'>total</span> <span m='441860'>turn</span> <span m='442150'>angle</span>
  <span m='442370'>of</span> <span m='442500'>the</span> <span m='442600'>curve,</span>
  <span m='443440'>equals</span> <span m='443770'>360.</span> <span m='444630'>The</span>
  <span m='444770'>total</span> <span m='445040'>turn</span> <span m='445280'>angle
  of</span> <span m='445610'>the</span> <span m='445700'>curve</span> <span m='446910'>is</span>
  <span m='447180'>360.</span> <span m='448670'>It's</span> <span m='449150'>a</span>
  <span m='449500'>planar</span> <span m='450010'>walk</span> <span m='450400'>here.</span>
  <span m='451330'>So</span> <span m='453020'>turn</span> <span m='453250'>angle--</span>
  <span m='454980'>total</span> <span m='455220'>turn</span> <span m='455520'>here</span>
  <span m='455810'>is</span> <span m='455950'>360</span> <span m='456600'>degrees.</span>
  </p><p><span m='458150'>Now,</span> <span m='458380'>if</span> <span m='458610'>we</span>
  <span m='458740'>have</span> <span m='458930'>a</span> <span m='459030'>convex</span>
  <span m='459620'>polyhedron,</span> <span m='460380'>then</span> <span m='460780'>this</span>
  <span m='461030'>curvature</span> <span m='461530'>has</span> <span m='461780'>to</span>
  <span m='461880'>be</span> <span m='462070'>non-negative.</span> <span m='465280'>Well,</span>
  <span m='465710'>I</span> <span m='465790'>mean,</span> <span m='466000'>sorry.</span>
  <span m='466610'>In any</span> <span m='466790'>case</span> <span m='467030'>here,</span>
  <span m='467200'>this</span> <span m='467410'>curvature</span> <span m='467760'>better</span>
  <span m='468100'>equal</span> <span m='468490'>0.</span> </p><p><span m='469580'>For</span>
  <span m='469790'>convex</span> <span m='470190'>polyhedra,</span> <span m='470980'>this</span>
  <span m='471130'>is</span> <span m='471260'>a</span> <span m='471330'>sum</span>
  <span m='471720'>of</span> <span m='471920'>vertex</span> <span m='472340'>curvatures.</span>
  <span m='473320'>For</span> <span m='473430'>convex</span> <span m='473830'>polyhedra,</span>
  <span m='474810'>every</span> <span m='475110'>vertex</span> <span m='475550'>has</span>
  <span m='475890'>strictly</span> <span m='476400'>positive</span> <span m='476860'>curvature</span>
  <span m='477300'>actually.</span> <span m='478160'>I mean</span> <span m='478340'>the</span>
  <span m='478420'>zero</span> <span m='479780'>curvature</span> <span m='480150'>vertices</span>
  <span m='480600'>aren't</span> <span m='481290'>vertices.</span> <span m='481690'>They're
  just</span> <span m='482640'>points</span> <span m='482980'>on</span> <span m='483100'>the</span>
  <span m='483170'>surface.</span> </p><p><span m='484530'>So</span> <span m='485830'>for</span>
  <span m='486000'>convex</span> <span m='486390'>polyhedron,</span> <span m='487010'>if</span>
  <span m='487130'>you're</span> <span m='487230'>going</span> <span m='487320'>to</span>
  <span m='487360'>have</span> <span m='487530'>zero</span> <span m='487920'>total</span>
  <span m='488290'>curvature,</span> <span m='488690'>that</span> <span m='488900'>means</span>
  <span m='489160'>you</span> <span m='489280'>actually</span> <span m='489600'>have</span>
  <span m='490060'>no</span> <span m='490580'>curvature.</span> <span m='491160'>So</span>
  <span m='491280'>you</span> <span m='491420'>have</span> <span m='491670'>no</span>
  <span m='491920'>vertices</span> <span m='493080'>enclosed</span> <span m='493540'>in</span>
  <span m='493600'>here,</span> <span m='493920'>which</span> <span m='494000'>is</span>
  <span m='494110'>a</span> <span m='494180'>contradiction.</span> <span m='494880'>That</span>
  <span m='495020'>means</span> <span m='495200'>there</span> <span m='495290'>wasn't</span>
  <span m='495570'>a</span> <span m='495600'>hole</span> <span m='495840'>to</span>
  <span m='495960'>open</span> <span m='496230'>up.</span> </p><p><span m='497640'>Technically,</span>
  <span m='498340'>you</span> <span m='498470'>could</span> <span m='498690'>do</span>
  <span m='498820'>something</span> <span m='499240'>weird</span> <span m='500020'>like--</span>
  <span m='502360'>I don't know,</span> <span m='502730'>let's</span> <span m='503380'>take</span>
  <span m='503690'>a</span> <span m='503730'>cube.</span> <span m='505350'>You</span>
  <span m='505490'>could</span> <span m='505620'>say,</span> <span m='505870'>OK,</span>
  <span m='506830'>I'm</span> <span m='506950'>going</span> <span m='507060'>to</span>
  <span m='507110'>make</span> <span m='507370'>a</span> <span m='507880'>couple</span>
  <span m='508290'>cuts</span> <span m='508730'>here</span> <span m='509920'>that</span>
  <span m='510030'>do</span> <span m='510160'>nothing.</span> <span m='512140'>This</span>
  <span m='512350'>is</span> <span m='512750'>kind</span> <span m='512929'>of</span>
  <span m='513030'>a</span> <span m='513520'>weird</span> <span m='513750'>situation.</span>
  </p><p><span m='515333'>We're going to</span> <span m='515730'>add</span> <span
  m='515970'>those</span> <span m='516179'>cuts.</span> <span m='517049'>And</span>
  <span m='517220'>then,</span> <span m='517350'>of</span> <span m='517450'>course,</span>
  <span m='517650'>you</span> <span m='517760'>could</span> <span m='517970'>draw</span>
  <span m='518370'>this</span> <span m='518630'>curve</span> <span m='518929'>around
  it</span> <span m='519299'>and</span> <span m='519470'>say,</span> <span m='519620'>oh</span>
  <span m='519809'>yeah,</span> <span m='520059'>look.</span> <span m='520260'>I've</span>
  <span m='520370'>got</span> <span m='520539'>lots</span> <span m='520789'>of</span>
  <span m='520870'>zero</span> <span m='521210'>curvature</span> <span m='521650'>vertices</span>
  <span m='522110'>inside</span> <span m='522460'>here.</span> </p><p><span m='523080'>In</span>
  <span m='523200'>general,</span> <span m='523610'>whenever</span> <span m='523809'>you</span>
  <span m='523870'>have</span> <span m='524030'>zero</span> <span m='524270'>curvature</span>
  <span m='524640'>vertices,</span> <span m='525100'>you</span> <span m='525240'>could</span>
  <span m='525380'>always</span> <span m='525640'>just</span> <span m='525970'>suture</span>
  <span m='526300'>them</span> <span m='526460'>back</span> <span m='526730'>up--</span>
  <span m='526890'>uncut</span> <span m='527070'>them--</span> <span m='527780'>and</span>
  <span m='528070'>there'd</span> <span m='528260'>be</span> <span m='528360'>no</span>
  <span m='528500'>difference</span> <span m='528900'>in</span> <span m='528960'>the</span>
  <span m='529090'>unfolding.</span> <span m='530040'>So</span> <span m='530180'>you</span>
  <span m='530230'>have</span> <span m='530440'>to</span> <span m='530770'>assume</span>
  <span m='531080'>that</span> <span m='531180'>you've</span> <span m='531330'>already</span>
  <span m='532270'>removed</span> <span m='533670'>pointless</span> <span m='534640'>cuts.</span>
  <span m='535370'>Then</span> <span m='536100'>there'll</span> <span m='536230'>be</span>
  <span m='536360'>no</span> <span m='536500'>vertices</span> <span m='536940'>in</span>
  <span m='537040'>there.</span> <span m='537840'>And</span> <span m='537950'>so</span>
  <span m='538070'>then,</span> <span m='539450'>in</span> <span m='539520'>fact,</span>
  <span m='539780'>there</span> <span m='539870'>was</span> <span m='540030'>no</span>
  <span m='540180'>hole</span> <span m='541160'>for</span> <span m='541740'>convex</span>
  <span m='542170'>polyhedra.</span> </p><p><span m='542580'>For</span> <span m='542710'>non-convex</span>
  <span m='543260'>polyhedra,</span> <span m='544160'>you</span> <span m='544340'>can</span>
  <span m='544480'>have</span> <span m='545060'>a</span> <span m='545150'>negative</span>
  <span m='545540'>curvature</span> <span m='545960'>vertex</span> <span m='546780'>that</span>
  <span m='546900'>balances</span> <span m='547400'>out</span> <span m='547670'>some</span>
  <span m='547800'>positive</span> <span m='548200'>curvature</span> <span m='548580'>vertices.</span>
  <span m='549500'>And</span> <span m='549720'>so</span> <span m='549830'>the</span>
  <span m='549980'>total</span> <span m='550350'>curvature</span> <span m='550760'>here</span>
  <span m='550940'>equals</span> <span m='551360'>zero.</span> <span m='552320'>But</span>
  <span m='552480'>you</span> <span m='552560'>have</span> <span m='552760'>three</span>
  <span m='552910'>vertices.</span> <span m='553530'>And that just</span> <span m='553880'>can't</span>
  <span m='554050'>happen</span> <span m='554340'>for</span> <span m='554490'>convex.</span>
  </p><p><span m='559650'>Next</span> <span m='560140'>quick</span> <span m='560390'>question</span>
  <span m='561050'>is,</span> <span m='563450'>when</span> <span m='563530'>we're</span>
  <span m='563650'>talking</span> <span m='563920'>about</span> <span m='564090'>the</span>
  <span m='564180'>cut</span> <span m='564420'>locus</span> <span m='564840'>and</span>
  <span m='564930'>the</span> <span m='565040'>ridge</span> <span m='565300'>tree,</span>
  <span m='566980'>we</span> <span m='567170'>drew</span> <span m='567300'>some</span>
  <span m='567480'>pictures.</span> <span m='568770'>The</span> <span m='568870'>claim</span>
  <span m='569210'>is</span> <span m='569360'>that it</span> <span m='569550'>was</span>
  <span m='569690'>a</span> <span m='569750'>spanning</span> <span m='570130'>tree</span>
  <span m='570320'>of  the</span> <span m='570450'>polyhedron.</span> <span m='571020'>And
  in</span> <span m='571200'>particular,</span> <span m='571730'>the</span> <span
  m='571870'>leaves</span> <span m='572240'>of</span> <span m='572360'>the</span>
  <span m='572470'>tree--</span> <span m='572770'>the</span> <span m='572880'>degree</span>
  <span m='573210'>1</span> <span m='573430'>vertices--</span> <span m='574300'>are</span>
  <span m='574430'>exactly</span> <span m='575060'>the</span> <span m='575750'>vertices</span>
  <span m='576170'>of</span> <span m='576240'>the</span> <span m='576330'>polyhedron.</span>
  </p><p><span m='578260'>And</span> <span m='579280'>I hadn't</span> <span m='579590'>actually</span>
  <span m='579850'>realized</span> <span m='580250'>this,</span> <span m='580490'>but</span>
  <span m='581050'>in</span> <span m='581200'>fact,</span> <span m='584140'>it's</span>
  <span m='584340'>not</span> <span m='584550'>really</span> <span m='584980'>literally</span>
  <span m='585420'>true.</span> <span m='585690'>It's</span> <span m='585900'>kind</span>
  <span m='586140'>of</span> <span m='586290'>spiritually</span> <span m='586980'>true.</span>
  <span m='588380'>The vertices,</span> <span m='589060'>in</span> <span m='589290'>fact,</span>
  <span m='589660'>have</span> <span m='590040'>unique</span> <span m='590380'>shortest</span>
  <span m='590770'>paths</span> <span m='591560'>to</span> <span m='591690'>x.</span>
  </p><p><span m='591960'>So</span> <span m='592070'>remember,</span> <span m='592380'>we</span>
  <span m='592490'>have</span> <span m='592680'>some</span> <span m='592880'>point,</span>
  <span m='593150'>x,</span> <span m='593460'>on</span> <span m='593580'>the</span>
  <span m='593650'>surface.</span> <span m='595150'>And</span> <span m='595400'>we're</span>
  <span m='595510'>looking</span> <span m='595900'>at</span> <span m='596420'>points,</span>
  <span m='596830'>like</span> <span m='597010'>this</span> <span m='597210'>one,</span>
  <span m='597860'>they</span> <span m='597960'>have</span> <span m='598090'>non-unique</span>
  <span m='598690'>shortest</span> <span m='599030'>paths</span> <span m='599430'>to
  x.</span> <span m='599795'>This is,</span> <span m='600160'>if</span> <span m='600290'>you</span>
  <span m='600460'>grow</span> <span m='601480'>the</span> <span m='601570'>fire</span>
  <span m='601970'>around</span> <span m='602250'>x,</span> <span m='602580'>where</span>
  <span m='602810'>does</span> <span m='602980'>the</span> <span m='603040'>fire</span>
  <span m='603430'>meet</span> <span m='603630'>itself.</span> <span m='604060'>And</span>
  <span m='604160'>it</span> <span m='604230'>will</span> <span m='604380'>meet</span>
  <span m='604550'>itself</span> <span m='605410'>along</span> <span m='605790'>this</span>
  <span m='605990'>edge,</span> <span m='606350'>because</span> <span m='606540'>you</span>
  <span m='606670'>could</span> <span m='606820'>go</span> <span m='607040'>around</span>
  <span m='607300'>this</span> <span m='607480'>way</span> <span m='607750'>or</span>
  <span m='608030'>go</span> <span m='608200'>around</span> <span m='608410'>this</span>
  <span m='608590'>way</span> <span m='608790'>and</span> <span m='608900'>it's</span>
  <span m='609080'>equal</span> <span m='609390'>length</span> <span m='609660'>path.</span>
  </p><p><span m='611060'>But</span> <span m='611250'>at</span> <span m='611400'>the</span>
  <span m='611490'>vertex,</span> <span m='611980'>there's</span> <span m='612110'>actually</span>
  <span m='612590'>a</span> <span m='612690'>unique</span> <span m='613040'>way</span>
  <span m='613170'>to</span> <span m='613240'>go</span> <span m='613440'>there.</span>
  <span m='613600'>That's</span> <span m='613870'>the</span> <span m='613960'>black</span>
  <span m='614250'>line.</span> <span m='615490'>So</span> <span m='615660'>technically,</span>
  <span m='616260'>this</span> <span m='616470'>point</span> <span m='616820'>is</span>
  <span m='616970'>not</span> <span m='617180'>on</span> <span m='617300'>the</span>
  <span m='617400'>ridge tree.</span> <span m='618150'>But</span> <span m='618300'>all</span>
  <span m='618580'>of</span> <span m='618680'>these</span> <span m='618890'>points</span>
  <span m='619230'>are.</span> <span m='620040'>So</span> <span m='620230'>this</span>
  <span m='620410'>is</span> <span m='620490'>kind</span> <span m='620660'>of</span>
  <span m='620750'>like</span> <span m='620930'>a</span> <span m='621000'>limiting</span>
  <span m='621520'>point</span> <span m='621890'>of</span> <span m='623030'>the</span>
  <span m='623190'>ridge</span> <span m='623430'>tree</span> <span m='623920'>points.</span>
  </p><p><span m='625060'>So</span> <span m='625390'>we</span> <span m='625570'>think</span>
  <span m='625870'>of</span> <span m='625950'>it</span> <span m='626040'>as</span>
  <span m='626140'>being</span> <span m='626340'>on</span> <span m='626410'>the</span>
  <span m='626490'>ridge tree.</span> <span m='626880'>I</span> <span m='626910'>mean,</span>
  <span m='627050'>you</span> <span m='627150'>could</span> <span m='627320'>think</span>
  <span m='627510'>of</span> <span m='627600'>as</span> <span m='627790'>cut</span>
  <span m='628020'>are</span> <span m='628130'>not</span> <span m='628350'>cut.</span>
  <span m='628520'>It</span> <span m='628640'>doesn't</span> <span m='628960'>really</span>
  <span m='629190'>matter.</span> </p><p><span m='629710'>But</span> <span m='629900'>you</span>
  <span m='630020'>cut</span> <span m='630320'>right</span> <span m='630530'>next</span>
  <span m='630780'>to</span> <span m='630890'>it,</span> <span m='631130'>so</span>
  <span m='632220'>effectively</span> <span m='632660'>the</span> <span m='632750'>same</span>
  <span m='633010'>thing.</span> <span m='634190'>But</span> <span m='634320'>it is</span>
  <span m='634500'>a neat</span> <span m='634690'>point--</span> <span m='635180'>a</span>
  <span m='635290'>subtle</span> <span m='635550'>point--</span> <span m='635830'>that</span>
  <span m='638070'>these</span> <span m='638340'>guys</span> <span m='638520'>have</span>
  <span m='638780'>unique</span> <span m='639130'>shortest</span> <span m='639510'>paths.</span>
  <span m='639750'>Whereas,</span> <span m='639960'>these</span> <span m='640190'>do</span>
  <span m='640310'>not.</span> <span m='641030'>Still</span> <span m='641300'>we</span>
  <span m='641450'>cut</span> <span m='642000'>all</span> <span m='642180'>the</span>
  <span m='642250'>way</span> <span m='642370'>up</span> <span m='642530'>to</span>
  <span m='643330'>corner.</span> <span m='645420'>All</span> <span m='645500'>right,</span>
  <span m='645920'>that</span> <span m='646200'>is</span> <span m='646840'>that.</span>
  </p><p><span m='649290'>So</span> <span m='649560'>now</span> <span m='649810'>we</span>
  <span m='649900'>have</span> <span m='650060'>a</span> <span m='650120'>bunch</span>
  <span m='650370'>of</span> <span m='650660'>newer</span> <span m='651450'>and</span>
  <span m='651820'>more</span> <span m='652010'>exciting</span> <span m='652560'>things--</span>
  <span m='653450'>or</span> <span m='654810'>updates</span> <span m='655200'>that</span>
  <span m='655310'>you</span> <span m='656080'>haven't</span> <span m='656550'>heard</span>
  <span m='656780'>of.</span> <span m='658010'>One</span> <span m='658440'>question</span>
  <span m='658990'>that</span> <span m='659110'>we</span> <span m='659250'>mentioned</span>
  <span m='659620'>was</span> <span m='659900'>generalizing</span> <span m='660580'>the</span>
  <span m='660690'>star</span> <span m='661030'>and</span> <span m='661160'>source</span>
  <span m='661450'>unfoldings.</span> <span m='662130'>And</span> <span m='662330'>there's</span>
  <span m='662530'>a</span> <span m='662980'>new</span> <span m='663100'>paper</span>
  <span m='664570'>about</span> <span m='665000'>this.</span> <span m='665395'>This</span>
  <span m='665790'>is</span> <span m='667000'>with</span> <span m='667290'>my</span>
  <span m='668020'>PhD</span> <span m='668350'>advisor,</span> <span m='668740'>Anna</span>
  <span m='669010'>Lubiw,</span> <span m='670610'>and</span> <span m='671140'>this</span>
  <span m='671370'>is</span> <span m='671500'>just</span> <span m='671690'>a</span>
  <span m='671750'>warm</span> <span m='672080'>up</span> <span m='674320'>to</span>
  <span m='674730'>get</span> <span m='674890'>started.</span> </p><p><span m='675260'>So</span>
  <span m='675340'>here,</span> <span m='675540'>we</span> <span m='675630'>have</span>
  <span m='675770'>a</span> <span m='675820'>box,</span> <span m='676530'>if we</span>
  <span m='676970'>take</span> <span m='677170'>a</span> <span m='677250'>point</span>
  <span m='677590'>x.</span> <span m='678710'>And</span> <span m='678965'>let's</span>
  <span m='679220'>see,</span> <span m='679390'>here</span> <span m='679580'>we</span>
  <span m='679670'>have</span> <span m='679900'>the</span> <span m='680000'>source</span>
  <span m='680310'>unfolding</span> <span m='680780'>from</span> <span m='681060'>x.</span>
  <span m='681830'>And</span> <span m='681940'>here,</span> <span m='682100'>we</span>
  <span m='682190'>have</span> <span m='682340'>the</span> <span m='682420'>star</span>
  <span m='682760'>unfolding,</span> <span m='683970'>just</span> <span m='684210'>for</span>
  <span m='684720'>comparison.</span> <span m='685180'>It's</span> <span m='685280'>also</span>
  <span m='685530'>kind</span> <span m='685690'>of</span> <span m='685770'>fun</span>
  <span m='685960'>to</span> <span m='686040'>see</span> <span m='686200'>them</span>
  <span m='686340'>side</span> <span m='686590'>by</span> <span m='686710'>side.</span>
  </p><p><span m='687020'>They're</span> <span m='687170'>color</span> <span m='687470'>coded.</span>
  <span m='688290'>So</span> <span m='688650'>where</span> <span m='688830'>you</span>
  <span m='689000'>cut</span> <span m='689340'>is</span> <span m='689720'>the</span>
  <span m='689870'>ridge</span> <span m='690150'>tree,</span> <span m='690350'>in</span>
  <span m='690450'>this</span> <span m='690620'>case.</span> <span m='691870'>And</span>
  <span m='692170'>you</span> <span m='692380'>end</span> <span m='692550'>up</span>
  <span m='692780'>gluing</span> <span m='693400'>along</span> <span m='693690'>the</span>
  <span m='693790'>ridge</span> <span m='694290'>tree</span> <span m='694690'>in</span>
  <span m='694900'>the</span> <span m='695030'>star</span> <span m='695360'>unfolding.</span>
  </p><p><span m='698090'>Now,</span> <span m='698540'>we're</span> <span m='698800'>going</span>
  <span m='698930'>to</span> <span m='699060'>generalize</span> <span m='699520'>things</span>
  <span m='699710'>a</span> <span m='699770'>little</span> <span m='700020'>bit</span>
  <span m='700250'>in</span> <span m='700440'>that</span> <span m='701210'>we're</span>
  <span m='701350'>going</span> <span m='701430'>to</span> <span m='701500'>generalize</span>
  <span m='701970'>the</span> <span m='702050'>source</span> <span m='702390'>unfolding,</span>
  <span m='702930'>specifically.</span> <span m='704020'>So</span> <span m='704180'>source</span>
  <span m='704480'>unfolding,</span> <span m='705400'>you</span> <span m='705500'>have</span>
  <span m='705610'>a</span> <span m='705670'>point</span> <span m='705970'>x.</span>
  <span m='706560'>And</span> <span m='706920'>you</span> <span m='707320'>just</span>
  <span m='707490'>sort</span> <span m='707660'>of</span> <span m='707730'>shoot</span>
  <span m='708010'>shortest</span> <span m='708350'>paths</span> <span m='708850'>all</span>
  <span m='709120'>from</span> <span m='709350'>x,</span> <span m='709650'>and</span>
  <span m='709740'>that's</span> <span m='709910'>what</span> <span m='709990'>you</span>
  <span m='710140'>keep.</span> <span m='711390'>And</span> <span m='711530'>you</span>
  <span m='711630'>end</span> <span m='711730'>up</span> <span m='711850'>cutting</span>
  <span m='712130'>along</span> <span m='712360'>the</span> <span m='712450'>ridge</span>
  <span m='712780'>tree,</span> <span m='713070'>which is</span> <span m='713290'>the</span>
  <span m='713370'>void in</span> <span m='713590'>our diagram</span> <span m='714030'>at
  this</span> <span m='714260'>point.</span> </p><p><span m='715100'>So</span> <span
  m='716110'>I'm</span> <span m='716360'>going</span> <span m='716480'>to</span> <span
  m='716530'>generalize</span> <span m='716930'>that</span> <span m='717010'>a</span>
  <span m='717080'>little</span> <span m='717290'>bit</span> <span m='717420'>and</span>
  <span m='717520'>think</span> <span m='717710'>of</span> <span m='717790'>this</span>
  <span m='717970'>as</span> <span m='718100'>a</span> <span m='718210'>tiny</span>
  <span m='718620'>little</span> <span m='718850'>circle.</span> <span m='720370'>And</span>
  <span m='720990'>in</span> <span m='721140'>general,</span> <span m='721480'>what</span>
  <span m='721630'>I'm</span> <span m='721720'>going</span> <span m='721950'>to</span>
  <span m='722070'>do</span> <span m='722290'>is</span> <span m='722440'>the</span>
  <span m='722540'>source</span> <span m='722880'>unfolding</span> <span m='723470'>outside</span>
  <span m='724040'>the</span> <span m='724120'>circle.</span> <span m='724940'>And</span>
  <span m='725190'>so</span> <span m='725330'>when</span> <span m='725450'>the</span>
  <span m='725530'>circle is</span> <span m='725880'>really</span> <span m='726080'>tiny,</span>
  <span m='726410'>it is</span> <span m='726670'>just</span> <span m='726880'>the</span>
  <span m='726960'>source</span> <span m='727230'>unfolding.</span> </p><p><span m='728560'>But</span>
  <span m='728700'>in</span> <span m='728830'>general,</span> <span m='730060'>I'm</span>
  <span m='730180'>going</span> <span m='730320'>to</span> <span m='730390'>do</span>
  <span m='730490'>the</span> <span m='730610'>star</span> <span m='731020'>unfolding</span>
  <span m='731650'>inside</span> <span m='732260'>the</span> <span m='732340'>circle.</span>
  <span m='734240'>OK.</span> <span m='735180'>So</span> <span m='735440'>in</span>
  <span m='735560'>this</span> <span m='735810'>case,</span> <span m='736140'>nothing</span>
  <span m='736310'>changes.</span> <span m='737250'>But</span> <span m='738030'>next</span>
  <span m='738440'>example</span> <span m='738900'>is</span> <span m='738990'>going</span>
  <span m='739140'>to</span> <span m='739200'>be</span> <span m='739340'>more</span>
  <span m='739550'>general.</span> </p><p><span m='739860'>Instead</span> <span m='740140'>of</span>
  <span m='740230'>being</span> <span m='740390'>a</span> <span m='740440'>single</span>
  <span m='740760'>point</span> <span m='741030'>here,</span> <span m='741770'>I'm</span>
  <span m='741860'>going</span> <span m='741960'>to</span> <span m='742130'>take</span>
  <span m='742580'>a</span> <span m='742870'>geodesic</span> <span m='743460'>arc--</span>
  <span m='743780'>a straight</span> <span m='744170'>line</span> <span m='744540'>on</span>
  <span m='744760'>the</span> <span m='744840'>surface.</span> <span m='746030'>So</span>
  <span m='746150'>here's</span> <span m='746730'>an</span> <span m='747180'>example</span>
  <span m='747600'>of</span> <span m='747680'>that.</span> <span m='748310'>We</span>
  <span m='748440'>have</span> <span m='748710'>a</span> <span m='749650'>square-based</span>
  <span m='750250'>pyramid.</span> <span m='751350'>We</span> <span m='751540'>drew</span>
  <span m='751770'>a</span> <span m='752020'>straight</span> <span m='752550'>line</span>
  <span m='753470'>on</span> <span m='753720'>the</span> <span m='753800'>surface.</span>
  <span m='754470'>If</span> <span m='754490'>you</span> <span m='754610'>unfolded</span>
  <span m='754870'>it,</span> <span m='755130'>it</span> <span m='755320'>would</span>
  <span m='755460'>be</span> <span m='755590'>straight.</span> </p><p><span m='757210'>We're</span>
  <span m='757360'>thinking</span> <span m='757820'>of</span> <span m='757900'>having</span>
  <span m='758280'>a</span> <span m='758340'>little--</span> <span m='760296'>I</span>
  <span m='760660'>think it's</span> <span m='760900'>called</span> <span m='761080'>a</span>
  <span m='761160'>racetrack</span> <span m='761730'>curve</span> <span m='762080'>in</span>
  <span m='762170'>mathematics--</span> <span m='763630'>around</span> <span m='764320'>that</span>
  <span m='765070'>straight</span> <span m='765370'>line.</span> <span m='766440'>And</span>
  <span m='766640'>I'm</span> <span m='766710'>going</span> <span m='766840'>to</span>
  <span m='766920'>do</span> <span m='767050'>star</span> <span m='767420'>unfolding</span>
  <span m='767730'>on</span> <span m='767820'>the</span> <span m='767920'>inside.</span>
  <span m='768270'>In</span> <span m='768330'>this</span> <span m='768490'>case,</span>
  <span m='768670'>there's</span> <span m='768830'>no</span> <span m='768960'>vertices</span>
  <span m='769400'>on</span> <span m='769480'>the</span> <span m='769570'>inside,</span>
  <span m='769940'>so</span> <span m='770010'>nothing</span> <span m='770250'>happens.</span>
  <span m='771010'>And</span> <span m='771160'>then</span> <span m='771250'>we</span>
  <span m='771330'>do</span> <span m='771450'>source</span> <span m='771790'>unfolding</span>
  <span m='772230'>on</span> <span m='772330'>the</span> <span m='772440'>outside.</span>
  </p><p><span m='772960'>This</span> <span m='773150'>is</span> <span m='773230'>actually</span>
  <span m='773530'>previously</span> <span m='774110'>known</span> <span m='774320'>to</span>
  <span m='774390'>unfold</span> <span m='775460'>by</span> <span m='775860'>O'Rourke</span>
  <span m='776260'>and</span> <span m='776360'>others.</span> <span m='777290'>But</span>
  <span m='778470'>we</span> <span m='778650'>have</span> <span m='779090'>a</span>
  <span m='779200'>simpler</span> <span m='779820'>proof,</span> <span m='780160'>essentially.</span>
  <span m='780890'>And</span> <span m='781140'>we're</span> <span m='781260'>going</span>
  <span m='781370'>to</span> <span m='781440'>generalize</span> <span m='781920'>it</span>
  <span m='782030'>more.</span> </p><p><span m='783000'>But</span> <span m='783260'>what</span>
  <span m='783480'>we</span> <span m='783580'>do</span> <span m='783720'>is</span>
  <span m='783830'>the</span> <span m='783930'>source</span> <span m='784220'>unfolding</span>
  <span m='784660'>on</span> <span m='784750'>the</span> <span m='784900'>outside.</span>
  <span m='785490'>So</span> <span m='785660'>you</span> <span m='785800'>take</span>
  <span m='786010'>shortest</span> <span m='786450'>paths--</span> <span m='786880'>from</span>
  <span m='787050'>every</span> <span m='787300'>point,</span> <span m='787520'>you</span>
  <span m='787580'>take</span> <span m='787780'>its</span> <span m='787910'>shortest</span>
  <span m='788270'>path</span> <span m='788920'>to</span> <span m='790700'>this</span>
  <span m='790930'>geodesic.</span> <span m='792300'>That's,</span> <span m='792640'>some</span>
  <span m='792790'>of</span> <span m='792840'>these</span> <span m='793000'>blue</span>
  <span m='793240'>lines</span> <span m='793670'>show</span> <span m='794280'>various</span>
  <span m='794510'>shortest</span> <span m='794910'>paths.</span> <span m='795130'>That's</span>
  <span m='795330'>what</span> <span m='795430'>you</span> <span m='795590'>keep.</span>
  </p><p><span m='796810'>The</span> <span m='797040'>ridge</span> <span m='797400'>tree</span>
  <span m='797810'>is</span> <span m='798730'>if</span> <span m='798840'>you</span>
  <span m='798970'>light</span> <span m='799180'>fire</span> <span m='799440'>simultaneously</span>
  <span m='800240'>along</span> <span m='800470'>this</span> <span m='800620'>entire</span>
  <span m='800930'>segment,</span> <span m='801280'>where</span> <span m='801450'>does</span>
  <span m='801600'>it</span> <span m='801710'>burn</span> <span m='801850'>out?</span>
  <span m='802630'>And</span> <span m='802770'>that's</span> <span m='802960'>the</span>
  <span m='803060'>purple</span> <span m='803360'>stuff.</span> <span m='804520'>And</span>
  <span m='806180'>this</span> <span m='806410'>is</span> <span m='806500'>the</span>
  <span m='806610'>complementary</span> <span m='807250'>diagram,</span> <span m='807740'>where</span>
  <span m='807850'>you</span> <span m='807970'>do</span> <span m='810240'>the</span>
  <span m='810380'>reverse,</span> <span m='810880'>which</span> <span m='811050'>would</span>
  <span m='811140'>be</span> <span m='811250'>the</span> <span m='811360'>star</span>
  <span m='811720'>unfolding</span> <span m='812100'>on</span> <span m='812180'>the</span>
  <span m='812290'>outside,</span> <span m='812800'>source</span> <span m='813050'>unfolding</span>
  <span m='813500'>on</span> <span m='813570'>the</span> <span m='813690'>inside.</span>
  <span m='814230'>So</span> <span m='814350'>you</span> <span m='814450'>glue</span>
  <span m='814670'>along</span> <span m='814960'>the</span> <span m='815050'>purple</span>
  <span m='815390'>stuff</span> <span m='816400'>instead</span> <span m='816850'>of</span>
  <span m='818160'>cutting</span> <span m='818500'>along</span> <span m='818750'>the</span>
  <span m='818830'>purple</span> <span m='819120'>stuff.</span> <span m='819870'>And</span>
  <span m='820130'>this,</span> <span m='820370'>we</span> <span m='820580'>conjecture,</span>
  <span m='821110'>doesn't</span> <span m='821330'>overlap</span> <span m='821740'>but</span>
  <span m='821860'>we</span> <span m='821970'>don't</span> <span m='822150'>know.</span>
  </p><p><span m='824990'>All</span> <span m='825070'>right,</span> <span m='825450'>so</span>
  <span m='826180'>fine.</span> <span m='826750'>That</span> <span m='827000'>looks</span>
  <span m='827440'>easy.</span> <span m='827770'>And</span> <span m='827850'>you</span>
  <span m='827960'>can</span> <span m='828160'>prove</span> <span m='828400'>that</span>
  <span m='828520'>this</span> <span m='828690'>doesn't</span> <span m='828980'>overlap.</span>
  <span m='829460'>Before</span> <span m='829820'>you</span> <span m='829930'>proved</span>
  <span m='830190'>it,</span> <span m='830290'>because</span> <span m='831060'>you</span>
  <span m='831150'>just</span> <span m='831370'>had</span> <span m='831610'>shortest</span>
  <span m='831950'>paths</span> <span m='832260'>emanating</span> <span m='832720'>in</span>
  <span m='832800'>all</span> <span m='833030'>directions</span> <span m='833520'>around</span>
  <span m='833810'>x.</span> <span m='834630'>Now,</span> <span m='834840'>you</span>
  <span m='834970'>have</span> <span m='836200'>shortest</span> <span m='836580'>paths</span>
  <span m='836820'>emanating</span> <span m='838600'>in</span> <span m='838840'>180</span>
  <span m='839410'>degrees</span> <span m='839750'>of</span> <span m='839840'>directions</span>
  <span m='840790'>around</span> <span m='841090'>this</span> <span m='841260'>endpoint.</span>
  </p><p><span m='841950'>Then</span> <span m='842150'>they</span> <span m='842290'>are</span>
  <span m='842370'>all</span> <span m='842530'>just</span> <span m='842690'>straight.</span>
  <span m='843590'>And</span> <span m='843800'>then</span> <span m='843980'>they</span>
  <span m='844160'>rotate</span> <span m='844560'>around</span> <span m='844760'>180</span>
  <span m='845110'>degrees</span> <span m='845480'>here.</span> <span m='845660'>And</span>
  <span m='845740'>then</span> <span m='845860'>they're</span> <span m='846010'>all</span>
  <span m='846140'>just</span> <span m='846300'>straight.</span> <span m='847140'>And</span>
  <span m='847310'>so</span> <span m='847410'>there</span> <span m='847560'>can't</span>
  <span m='847830'>be</span> <span m='847920'>anything</span> <span m='848210'>overlapping,</span>
  <span m='848700'>because</span> <span m='848870'>you're</span> <span m='848970'>just</span>
  <span m='849160'>taking</span> <span m='849680'>a</span> <span m='849780'>continuum</span>
  <span m='850300'>of</span> <span m='850400'>these</span> <span m='850560'>segments</span>
  <span m='851010'>of</span> <span m='851120'>varying</span> <span m='851480'>lengths.</span>
  <span m='852470'>They</span> <span m='852650'>don't</span> <span m='852950'>overlap.</span>
  </p><p><span m='854130'>Here,</span> <span m='854320'>they're</span> <span m='854490'>all</span>
  <span m='854610'>parallel.</span> <span m='855540'>Here,</span> <span m='855780'>they</span>
  <span m='855950'>sweep</span> <span m='856280'>nicely.</span> <span m='856660'>In</span>
  <span m='856710'>general,</span> <span m='857050'>if</span> <span m='857160'>they</span>
  <span m='857310'>always</span> <span m='857510'>turn</span> <span m='858390'>clockwise</span>
  <span m='859110'>as</span> <span m='859300'>you</span> <span m='859440'>walk</span>
  <span m='859710'>along</span> <span m='859940'>the</span> <span m='860020'>curve,</span>
  <span m='860810'>you're</span> <span m='860970'>fine.</span> </p><p><span m='862471'>OK,</span>
  <span m='862870'>here's</span> <span m='863220'>a</span> <span m='863350'>more</span>
  <span m='863590'>general</span> <span m='863930'>one.</span> <span m='864200'>In</span>
  <span m='864340'>general,</span> <span m='864780'>what</span> <span m='864950'>we</span>
  <span m='865090'>can</span> <span m='865230'>prove</span> <span m='865530'>is</span>
  <span m='865720'>that</span> <span m='865810'>if</span> <span m='865930'>you</span>
  <span m='866030'>have</span> <span m='866230'>a</span> <span m='866310'>convex</span>
  <span m='867120'>curve</span> <span m='868340'>on</span> <span m='868680'>the</span>
  <span m='868770'>surface--</span> <span m='869820'>so</span> <span m='870020'>it</span>
  <span m='870110'>always</span> <span m='870530'>turns</span> <span m='871000'>to</span>
  <span m='871150'>the</span> <span m='871290'>left,</span> <span m='871840'>I</span>
  <span m='871890'>think</span> <span m='872200'>technically.</span> <span m='873210'>The</span>
  <span m='873320'>angle</span> <span m='873610'>on</span> <span m='873730'>the</span>
  <span m='873800'>left</span> <span m='874030'>hand</span> <span m='874210'>side</span>
  <span m='874470'>is</span> <span m='874600'>always</span> <span m='874880'>less</span>
  <span m='875150'>than</span> <span m='875310'>or</span> <span m='875420'>equal</span>
  <span m='875660'>to</span> <span m='875790'>180</span> <span m='876410'>degrees.</span>
  </p><p><span m='877530'>You have</span> <span m='877690'>to</span> <span m='877770'>be</span>
  <span m='877870'>a</span> <span m='877920'>little</span> <span m='878120'>careful</span>
  <span m='878440'>what</span> <span m='878570'>it</span> <span m='878630'>means to</span>
  <span m='878830'>turn</span> <span m='879070'>to the</span> <span m='879160'>left.</span>
  <span m='879370'>When</span> <span m='879450'>you</span> <span m='879530'>hit</span>
  <span m='879690'>a</span> <span m='879730'>vertex,</span> <span m='880220'>you've</span>
  <span m='880320'>got</span> <span m='880480'>less</span> <span m='880710'>than</span>
  <span m='880790'>360</span> <span m='881280'>total.</span> <span m='881660'>So</span>
  <span m='881800'>what</span> <span m='882140'>does</span> <span m='882560'>to the
  left</span> <span m='882900'>mean?</span> <span m='883120'>It</span> <span m='883520'>just</span>
  <span m='883710'>means</span> <span m='883870'>you've</span> <span m='884000'>got</span>
  <span m='884190'>less</span> <span m='884440'>than</span> <span m='884610'>180</span>
  <span m='885160'>degrees of</span> <span m='885460'>material</span> <span m='885890'>on</span>
  <span m='886010'>your</span> <span m='886130'>left</span> <span m='886330'>side.</span>
  </p><p><span m='887430'>So</span> <span m='887590'>this</span> <span m='887780'>is</span>
  <span m='887900'>an</span> <span m='887990'>example</span> <span m='888400'>of</span>
  <span m='888540'>a</span> <span m='888600'>convex</span> <span m='889000'>curve.</span>
  <span m='889320'>It's got</span> <span m='889480'>some</span> <span m='889590'>circular</span>
  <span m='890020'>arcs.</span> <span m='890840'>We're</span> <span m='890950'>no</span>
  <span m='891100'>longer</span> <span m='891470'>tracking</span> <span m='891960'>along</span>
  <span m='892390'>some--</span> <span m='893460'>we're</span> <span m='893640'>no</span>
  <span m='893780'>longer</span> <span m='894030'>just</span> <span m='894190'>doubling</span>
  <span m='894560'>along</span> <span m='894850'>some</span> <span m='895050'>curve.</span>
  </p><p><span m='895400'>Here,</span> <span m='895650'>we</span> <span m='895900'>enclose</span>
  <span m='896260'>a</span> <span m='896320'>vertex,</span> <span m='896800'>which</span>
  <span m='896950'>makes it</span> <span m='897170'>a</span> <span m='897220'>little</span>
  <span m='897380'>more</span> <span m='897540'>exciting,</span> <span m='898750'>because</span>
  <span m='899010'>now</span> <span m='899260'>what</span> <span m='899360'>we're</span>
  <span m='899380'>going</span> <span m='899610'>to</span> <span m='899720'>do</span>
  <span m='900230'>star</span> <span m='900560'>unfolding</span> <span m='900940'>on</span>
  <span m='901030'>the</span> <span m='901120'>inside,</span> <span m='901500'>which</span>
  <span m='901760'>remember</span> <span m='902150'>was</span> <span m='902420'>cutting</span>
  <span m='902790'>along</span> <span m='903110'>shortest</span> <span m='903500'>paths</span>
  <span m='904310'>from</span> <span m='904530'>every</span> <span m='904760'>vertex</span>
  <span m='905760'>to</span> <span m='906030'>your</span> <span m='906250'>thing.</span>
  <span m='906610'>In</span> <span m='906720'>this</span> <span m='906890'>case,</span>
  <span m='907220'>your</span> <span m='907370'>thing</span> <span m='907620'>is</span>
  <span m='907720'>no</span> <span m='907830'>longer</span> <span m='908060'>a</span>
  <span m='908120'>point,</span> <span m='908370'>x.</span> <span m='908730'>It is</span>
  <span m='908970'>now</span> <span m='909640'>this</span> <span m='909820'>convex</span>
  <span m='910290'>curve.</span> </p><p><span m='910690'>So</span> <span m='910760'>let's</span>
  <span m='910910'>say</span> <span m='911010'>this</span> <span m='911290'>is</span>
  <span m='911430'>the</span> <span m='911520'>shortest</span> <span m='911930'>path</span>
  <span m='912840'>here.</span> <span m='913895'>It</span> <span m='914260'>might</span>
  <span m='914350'>be</span> <span m='914480'>than</span> <span m='914600'>one</span>
  <span m='914730'>choice,</span> <span m='915230'>but</span> <span m='916540'>we're</span>
  <span m='916760'>going</span> <span m='917050'>to--</span> <span m='917840'>actually,</span>
  <span m='918120'>no.</span> <span m='918980'>This</span> <span m='919200'>is</span>
  <span m='919320'>the</span> <span m='919380'>shortest</span> <span m='919670'>path.</span>
  <span m='919860'>This</span> <span m='920050'>is</span> <span m='920150'>a</span>
  <span m='920260'>root</span> <span m='920440'>2</span> <span m='920580'>diagonal.</span>
  <span m='921050'>This</span> <span m='921230'>is</span> <span m='921370'>length</span>
  <span m='921610'>1.</span> </p><p><span m='923170'>So</span> <span m='923310'>we're</span>
  <span m='923390'>going</span> <span m='923480'>to</span> <span m='923550'>come</span>
  <span m='923720'>along</span> <span m='923990'>here</span> <span m='924270'>and</span>
  <span m='924440'>that's</span> <span m='924720'>this</span> <span m='925520'>dashed</span>
  <span m='925890'>line.</span> <span m='926190'>So</span> <span m='926380'>it</span>
  <span m='926460'>got</span> <span m='926720'>opened</span> <span m='927080'>up</span>
  <span m='927280'>here,</span> <span m='928860'>because</span> <span m='929040'>we</span>
  <span m='929140'>had</span> <span m='929300'>too</span> <span m='929460'>little</span>
  <span m='929650'>material</span> <span m='930120'>here.</span> <span m='930620'>We</span>
  <span m='930790'>open</span> <span m='931080'>it</span> <span m='931180'>up.</span>
  <span m='931910'>But</span> <span m='932080'>otherwise,</span> <span m='932570'>it</span>
  <span m='932670'>acts</span> <span m='933000'>the</span> <span m='933100'>same.</span>
  </p><p><span m='933410'>In</span> <span m='933500'>particular,</span> <span m='934090'>outside</span>
  <span m='934820'>this</span> <span m='935020'>red</span> <span m='935310'>curve,</span>
  <span m='936050'>it's</span> <span m='936290'>just</span> <span m='936470'>source</span>
  <span m='936830'>unfolding.</span> <span m='937290'>You've</span> <span m='937430'>got</span>
  <span m='937610'>all</span> <span m='937780'>these</span> <span m='937890'>shortest</span>
  <span m='938300'>paths.</span> <span m='939080'>And</span> <span m='939310'>again,</span>
  <span m='939640'>what</span> <span m='939860'>we</span> <span m='940050'>argue--</span>
  <span m='940480'>and</span> <span m='940560'>I'm</span> <span m='940640'>not</span>
  <span m='940810'>going</span> <span m='940900'>to</span> <span m='940970'>prove
  it</span> <span m='941260'>here--</span> <span m='941870'>is</span> <span m='942100'>that</span>
  <span m='942240'>all</span> <span m='942470'>of</span> <span m='942570'>these</span>
  <span m='942690'>shortest</span> <span m='943080'>paths</span> <span m='943520'>keep</span>
  <span m='943730'>turning</span> <span m='944060'>clockwise</span> <span m='944990'>and</span>
  <span m='945330'>do</span> <span m='945580'>so</span> <span m='945940'>exactly</span>
  <span m='946420'>360</span> <span m='946980'>degrees.</span> </p><p><span m='947800'>There's</span>
  <span m='947890'>some</span> <span m='948140'>jumps</span> <span m='948630'>when</span>
  <span m='948780'>you</span> <span m='948880'>hit</span> <span m='949120'>these</span>
  <span m='949370'>gaps.</span> <span m='949950'>And</span> <span m='950040'>you</span>
  <span m='950120'>have</span> <span m='950250'>to</span> <span m='950360'>kind</span>
  <span m='950520'>of</span> <span m='950630'>jump</span> <span m='950860'>over</span>
  <span m='951050'>them.</span> <span m='951770'>But</span> <span m='952720'>still,</span>
  <span m='953080'>you</span> <span m='953190'>have</span> <span m='953450'>no</span>
  <span m='954110'>collision.</span> </p><p><span m='955610'>And</span> <span m='955860'>drawn</span>
  <span m='956090'>over</span> <span m='956270'>here</span> <span m='956590'>is</span>
  <span m='956830'>the</span> <span m='957000'>reverse,</span> <span m='958240'>where</span>
  <span m='958620'>we</span> <span m='958880'>would</span> <span m='959190'>star</span>
  <span m='959810'>unfold</span> <span m='960840'>the</span> <span m='961450'>outside</span>
  <span m='962210'>of</span> <span m='962320'>a</span> <span m='962400'>convex</span>
  <span m='962880'>curve--</span> <span m='963720'>because</span> <span m='963890'>it's</span>
  <span m='964020'>a</span> <span m='964080'>convex</span> <span m='964500'>curve,</span>
  <span m='964700'>the</span> <span m='965020'>inside</span> <span m='965360'>and</span>
  <span m='965440'>outside</span> <span m='965740'>are</span> <span m='965810'>different--</span>
  <span m='966720'>and</span> <span m='966970'>source</span> <span m='967310'>unfold</span>
  <span m='967660'>on</span> <span m='967750'>the</span> <span m='967910'>inside.</span>
  <span m='968930'>And</span> <span m='969080'>this,</span> <span m='969250'>we</span>
  <span m='969420'>conjecture,</span> <span m='970040'>doesn't</span> <span m='970300'>overlap.</span>
  <span m='970790'>But</span> <span m='970960'>we</span> <span m='971110'>don't</span>
  <span m='971320'>know how</span> <span m='971600'>to prove</span> <span m='971960'>it.</span>
  </p><p><span m='973390'>This</span> <span m='973630'>thing</span> <span m='973980'>is</span>
  <span m='974110'>a</span> <span m='974180'>generalization</span> <span m='974780'>of</span>
  <span m='974850'>the</span> <span m='974930'>source</span> <span m='975230'>unfolding.</span>
  <span m='975900'>Because</span> <span m='976010'>when</span> <span m='976150'>this</span>
  <span m='976290'>curve</span> <span m='976510'>is</span> <span m='976600'>super</span>
  <span m='977040'>tiny,</span> <span m='977730'>it is</span> <span m='977990'>a</span>
  <span m='978050'>source</span> <span m='978300'>unfolding.</span> <span m='978710'>This</span>
  <span m='978890'>thing</span> <span m='979070'>would</span> <span m='979270'>be</span>
  <span m='979400'>a</span> <span m='979430'>generalization</span> <span m='980090'>of</span>
  <span m='980160'>the</span> <span m='980260'>star</span> <span m='980500'>unfolding,</span>
  <span m='980960'>but</span> <span m='981120'>we</span> <span m='981230'>don't</span>
  <span m='981430'>know</span> <span m='981600'>whether</span> <span m='981930'>works.</span>
  </p><p><span m='983641'>I think</span> <span m='984020'>one</span> <span m='984280'>more</span>
  <span m='984460'>example</span> <span m='984890'>here.</span> <span m='985840'>This</span>
  <span m='986060'>is</span> <span m='987640'>a</span> <span m='987730'>way</span>
  <span m='987920'>to</span> <span m='988050'>generate</span> <span m='988440'>convex</span>
  <span m='988870'>curves.</span> <span m='989070'>You</span> <span m='989150'>start</span>
  <span m='989400'>from</span> <span m='989520'>some</span> <span m='989720'>point,</span>
  <span m='989970'>x.</span> <span m='991320'>And</span> <span m='991500'>you</span>
  <span m='991670'>design</span> <span m='992150'>it--</span> <span m='992440'>you</span>
  <span m='992700'>choose</span> <span m='992980'>a</span> <span m='993340'>direction</span>
  <span m='993940'>so</span> <span m='994130'>that</span> <span m='994620'>if</span>
  <span m='994750'>you</span> <span m='994870'>go</span> <span m='995050'>straight--</span>
  <span m='995670'>so</span> <span m='995910'>this</span> <span m='996140'>curve</span>
  <span m='996380'>goes</span> <span m='996580'>straight</span> <span m='996980'>everywhere</span>
  <span m='997370'>except</span> <span m='997750'>x.</span> <span m='998230'>If</span>
  <span m='998320'>you</span> <span m='998530'>set</span> <span m='998780'>it</span>
  <span m='998870'>up</span> <span m='999040'>right,</span> <span m='999230'>you</span>
  <span m='999380'>come</span> <span m='999620'>back</span> <span m='999880'>to</span>
  <span m='999970'>x.</span> </p><p><span m='1000970'>So</span> <span m='1001120'>this,</span>
  <span m='1001360'>in</span> <span m='1001460'>particular,</span> <span m='1001870'>is</span>
  <span m='1001970'>a</span> <span m='1002020'>convex</span> <span m='1002430'>curve,</span>
  <span m='1002690'>because</span> <span m='1002810'>it's</span> <span m='1002880'>straight</span>
  <span m='1003220'>everywhere</span> <span m='1003600'>except</span> <span m='1003890'>x.</span>
  <span m='1004160'>And at</span> <span m='1004400'>x,</span> <span m='1004680'>it's</span>
  <span m='1004820'>convex.</span> </p><p><span m='1006290'>And</span> <span m='1006470'>so,</span>
  <span m='1007110'>in</span> <span m='1007240'>this</span> <span m='1007470'>case,</span>
  <span m='1007770'>we</span> <span m='1007940'>enclose</span> <span m='1008520'>a</span>
  <span m='1008600'>few</span> <span m='1009120'>vertices.</span> <span m='1009730'>On</span>
  <span m='1009840'>the</span> <span m='1009960'>inside,</span> <span m='1010410'>we've
  got</span> <span m='1010540'>V3,</span> <span m='1010810'>V7,</span> <span m='1011240'>V6.</span>
  <span m='1013440'>So</span> <span m='1013660'>each</span> <span m='1013920'>of</span>
  <span m='1014000'>those</span> <span m='1015310'>ends</span> <span m='1015510'>up</span>
  <span m='1015640'>getting</span> <span m='1016100'>cut</span> <span m='1016380'>here</span>
  <span m='1016750'>in</span> <span m='1016830'>these</span> <span m='1017150'>green</span>
  <span m='1017430'>lines.</span> </p><p><span m='1019950'>And</span> <span m='1020230'>so,</span>
  <span m='1020690'>like</span> <span m='1020860'>this</span> <span m='1021040'>one</span>
  <span m='1021230'>is</span> <span m='1021370'>a</span> <span m='1021420'>very</span>
  <span m='1021640'>tiny</span> <span m='1022000'>cut.</span> <span m='1022250'>We</span>
  <span m='1022330'>just</span> <span m='1022510'>cut</span> <span m='1022750'>there</span>
  <span m='1023570'>at</span> <span m='1023980'>V3.</span> <span m='1024160'>The</span>
  <span m='1024569'>other</span> <span m='1024730'>ones</span> <span m='1024940'>are</span>
  <span m='1025050'>little</span> <span m='1025240'>bigger.</span> <span m='1025960'>But</span>
  <span m='1026140'>they</span> <span m='1026319'>open</span> <span m='1026619'>up.</span>
  <span m='1027800'>And</span> <span m='1029579'>yeah, I</span> <span m='1029660'>guess,</span>
  <span m='1029869'>this</span> <span m='1030069'>is</span> <span m='1030240'>the--</span>
  <span m='1031900'>well,</span> <span m='1032359'>it's a few</span> <span m='1032450'>different</span>
  <span m='1033140'>versions</span> <span m='1033470'>of</span> <span m='1033560'>the</span>
  <span m='1033640'>picture</span> <span m='1033930'>here.</span> </p><p><span m='1035520'>But</span>
  <span m='1035660'>again,</span> <span m='1036010'>you</span> <span m='1036160'>look</span>
  <span m='1036339'>at</span> <span m='1036430'>the</span> <span m='1036550'>shortest</span>
  <span m='1036950'>paths.</span> <span m='1037790'>Here,</span> <span m='1037980'>they're</span>
  <span m='1038130'>all</span> <span m='1038280'>parallel.</span> <span m='1039099'>Here,</span>
  <span m='1039290'>they</span> <span m='1039440'>sweep.</span> <span m='1040300'>Here,</span>
  <span m='1040480'>they're</span> <span m='1040630'>all</span> <span m='1040760'>parallel.</span>
  <span m='1041670'>Here,</span> <span m='1041900'>we</span> <span m='1042119'>jump,</span>
  <span m='1042740'>but</span> <span m='1043369'>it's</span> <span m='1043640'>just</span>
  <span m='1043890'>the</span> <span m='1043970'>same as</span> <span m='1044250'>sweeping--</span>
  <span m='1044565'>it</span> <span m='1044880'>doesn't</span> <span m='1045119'>hurt</span>
  <span m='1045359'>you.</span> </p><p><span m='1046339'>Then</span> <span m='1047410'>they're</span>
  <span m='1047599'>all</span> <span m='1047660'>parallel.</span> <span m='1048300'>Then</span>
  <span m='1048359'>we</span> <span m='1048460'>jump.</span> <span m='1048890'>Then</span>
  <span m='1049000'>they're all</span> <span m='1049160'>parallel,</span> <span m='1049630'>in</span>
  <span m='1049720'>this</span> <span m='1049910'>particular</span> <span m='1050300'>example.</span>
  </p><p><span m='1050760'>But</span> <span m='1050890'>they</span> <span m='1050970'>will</span>
  <span m='1051190'>always</span> <span m='1051490'>proceed</span> <span m='1052530'>clockwise</span>
  <span m='1053030'>around</span> <span m='1053290'>the</span> <span m='1053380'>curve,</span>
  <span m='1054040'>which</span> <span m='1054420'>here is</span> <span m='1054810'>drawn</span>
  <span m='1055150'>red.</span> <span m='1057600'>Gets</span> <span m='1057780'>split</span>
  <span m='1058160'>up</span> <span m='1058310'>a</span> <span m='1058360'>little</span>
  <span m='1058590'>bit,</span> <span m='1058980'>but</span> <span m='1059260'>you</span>
  <span m='1059390'>can</span> <span m='1059500'>show</span> <span m='1059770'>because</span>
  <span m='1060110'>of</span> <span m='1060210'>that</span> <span m='1060440'>sweeping,</span>
  <span m='1061150'>they</span> <span m='1061260'>won't</span> <span m='1061490'>hit</span>
  <span m='1061670'>each</span> <span m='1061880'>other.</span> <span m='1062640'>And</span>
  <span m='1062740'>you</span> <span m='1062820'>have</span> <span m='1063660'>non-overlapping</span>
  <span m='1064390'>unfolding.</span> </p><p><span m='1066290'>So</span> <span m='1067520'>we</span>
  <span m='1067660'>call</span> <span m='1067900'>this</span> <span m='1068010'>sun</span>
  <span m='1068480'>unfolding,</span> <span m='1069600'>because</span> <span m='1070490'>of</span>
  <span m='1070600'>the</span> <span m='1070710'>rays</span> <span m='1071000'>that</span>
  <span m='1071130'>sweep</span> <span m='1071510'>around.</span> <span m='1072760'>And</span>
  <span m='1072980'>because</span> <span m='1073230'>we</span> <span m='1073300'>have</span>
  <span m='1073390'>a</span> <span m='1073450'>convex</span> <span m='1073870'>curve,</span>
  <span m='1074100'>it's</span> <span m='1074240'>kind</span> <span m='1074440'>of</span>
  <span m='1074490'>like</span> <span m='1074770'>the</span> <span m='1074940'>sun.</span>
  <span m='1076820'>So</span> <span m='1077880'>that's</span> <span m='1078440'>a</span>
  <span m='1078550'>new</span> <span m='1078750'>unfolding.</span> </p><p><span m='1080150'>The</span>
  <span m='1080560'>obvious</span> <span m='1080930'>open</span> <span m='1081170'>question</span>
  <span m='1081590'>is</span> <span m='1082450'>the</span> <span m='1082550'>reverse,</span>
  <span m='1082950'>when</span> <span m='1083110'>you</span> <span m='1083220'>glue</span>
  <span m='1083510'>around</span> <span m='1083730'>the</span> <span m='1083800'>purple</span>
  <span m='1084090'>sides</span> <span m='1084600'>instead</span> <span m='1084860'>of</span>
  <span m='1085120'>the--</span> <span m='1089600'>It's</span> <span m='1089840'>essentially,</span>
  <span m='1090710'>instead</span> <span m='1091030'>of</span> <span m='1091080'>having</span>
  <span m='1091290'>a</span> <span m='1091320'>convex</span> <span m='1091750'>curve,</span>
  <span m='1091960'>you</span> <span m='1092050'>have</span> <span m='1092250'>a</span>
  <span m='1092350'>reflex</span> <span m='1092770'>curve,</span> <span m='1093350'>exactly</span>
  <span m='1093830'>the</span> <span m='1093950'>opposite.</span> <span m='1094780'>What</span>
  <span m='1094940'>happens,</span> <span m='1095540'>we</span> <span m='1095660'>don't</span>
  <span m='1095800'>know.</span> </p><p><span m='1096300'>It's</span> <span m='1096430'>a</span>
  <span m='1096480'>lot</span> <span m='1096640'>harder</span> <span m='1096890'>to</span>
  <span m='1096980'>prove.</span> <span m='1097230'>Because</span> <span m='1097550'>in</span>
  <span m='1097640'>particular,</span> <span m='1097990'>it's</span> <span m='1098100'>a</span>
  <span m='1098140'>lot</span> <span m='1098270'>harder</span> <span m='1098490'>to</span>
  <span m='1098570'>prove</span> <span m='1098890'>that the</span> <span m='1098980'>star</span>
  <span m='1099290'>unfolding</span> <span m='1099660'>doesn't</span> <span m='1099910'>overlap.</span>
  <span m='1100350'>And you've</span> <span m='1100560'>got to</span> <span m='1100820'>include</span>
  <span m='1101160'>at</span> <span m='1101240'>least</span> <span m='1101540'>that</span>
  <span m='1101760'>proof</span> <span m='1102670'>in</span> <span m='1103070'>any</span>
  <span m='1103120'>generalization</span> <span m='1103870'>of</span> <span m='1103990'>it.</span>
  </p><p><span m='1106610'>Next</span> <span m='1107280'>topic</span> <span m='1107800'>of</span>
  <span m='1108000'>unfolding</span> <span m='1109300'>kind</span> <span m='1109510'>of</span>
  <span m='1109580'>related</span> <span m='1110070'>we</span> <span m='1110270'>call</span>
  <span m='1110570'>zipper</span> <span m='1111000'>unfolding.</span> <span m='1112130'>So</span>
  <span m='1113870'>these</span> <span m='1114040'>are</span> <span m='1114120'>some</span>
  <span m='1114320'>examples</span> <span m='1114780'>of</span> <span m='1114910'>real</span>
  <span m='1115260'>felt</span> <span m='1115600'>models</span> <span m='1116060'>with</span>
  <span m='1116230'>a</span> <span m='1116300'>zipper.</span> <span m='1116960'>The</span>
  <span m='1117080'>goal</span> <span m='1117370'>is,</span> <span m='1117530'>I</span>
  <span m='1118340'>want</span> <span m='1118950'>an</span> <span m='1119060'>unfolding</span>
  <span m='1120110'>that</span> <span m='1120200'>has</span> <span m='1120440'>a</span>
  <span m='1120500'>single</span> <span m='1120850'>zipper.</span> <span m='1121190'>And
  you</span> <span m='1121530'>just</span> <span m='1121790'>pull</span> <span m='1122060'>the</span>
  <span m='1122130'>zipper,</span> <span m='1122840'>and</span> <span m='1123020'>it</span>
  <span m='1123090'>makes</span> <span m='1123350'>your</span> <span m='1123500'>polyhedron.</span>
  </p><p><span m='1124410'>So this</span> <span m='1124710'>is</span> <span m='1124830'>an</span>
  <span m='1124910'>example</span> <span m='1125330'>of an</span> <span m='1125620'>octahedron.</span>
  <span m='1126340'>This</span> <span m='1126490'>one</span> <span m='1126630'>is</span>
  <span m='1126720'>actually</span> <span m='1127000'>not</span> <span m='1127170'>even</span>
  <span m='1127370'>a</span> <span m='1127430'>polyhedron.</span> <span m='1128730'>It</span>
  <span m='1128800'>has</span> <span m='1129080'>two</span> <span m='1129540'>pyramidal</span>
  <span m='1130360'>pockets</span> <span m='1131000'>in</span> <span m='1131190'>it.</span>
  <span m='1131650'>And</span> <span m='1131850'>it's</span> <span m='1132160'>actually</span>
  <span m='1132470'>closed</span> <span m='1132850'>off</span> <span m='1133070'>in</span>
  <span m='1133160'>the</span> <span m='1133230'>middle.</span> </p><p><span m='1134140'>I</span>
  <span m='1134430'>think</span> <span m='1134590'>we</span> <span m='1134670'>have</span>
  <span m='1134830'>a</span> <span m='1134870'>little</span> <span m='1135080'>video</span>
  <span m='1135480'>here</span> <span m='1136220'>of</span> <span m='1136560'>what</span>
  <span m='1136750'>it</span> <span m='1136850'>looks</span> <span m='1137080'>like</span>
  <span m='1137280'>to</span> <span m='1137550'>open</span> <span m='1137930'>that</span>
  <span m='1138120'>octahedron.</span> <span m='1140180'>So</span> <span m='1140710'>what</span>
  <span m='1140950'>does</span> <span m='1141090'>it</span> <span m='1141280'>take</span>
  <span m='1141710'>to</span> <span m='1141920'>have</span> <span m='1142190'>a</span>
  <span m='1142290'>single</span> <span m='1142830'>zipper</span> <span m='1143180'>line,</span>
  <span m='1146430'>that</span> <span m='1146910'>connects</span> <span m='1147300'>everything</span>
  <span m='1147690'>together?</span> <span m='1148800'>Well, if you</span> <span m='1149150'>think</span>
  <span m='1149300'>about</span> <span m='1149540'>it,</span> <span m='1149660'>that</span>
  <span m='1149820'>means</span> <span m='1150050'>that</span> <span m='1150290'>the</span>
  <span m='1150690'>cuts</span> <span m='1151060'>that</span> <span m='1151190'>you</span>
  <span m='1151300'>make</span> <span m='1151720'>must</span> <span m='1152010'>follow</span>
  <span m='1152470'>a</span> <span m='1152560'>single</span> <span m='1152950'>path.</span>
  </p><p><span m='1154160'>So</span> <span m='1155600'>in</span> <span m='1155790'>general,</span>
  <span m='1156170'>the</span> <span m='1156290'>cuts</span> <span m='1156590'>form
  a</span> <span m='1156900'>tree</span> <span m='1157180'>on a</span> <span m='1157460'>convex</span>
  <span m='1157840'>polyhedron.</span> <span m='1158380'>We</span> <span m='1158530'>want</span>
  <span m='1158770'>that</span> <span m='1158960'>tree</span> <span m='1159240'>to</span>
  <span m='1159360'>be</span> <span m='1159550'>just</span> <span m='1159820'>a</span>
  <span m='1159860'>path.</span> <span m='1161000'>So</span> <span m='1161140'>it's</span>
  <span m='1161240'>like</span> <span m='1161380'>a</span> <span m='1161430'>Hamiltonian</span>
  <span m='1162250'>path.</span> </p><p><span m='1163000'>It's</span> <span m='1163100'>got</span>
  <span m='1163220'>to</span> <span m='1163280'>visit</span> <span m='1163570'>all</span>
  <span m='1163710'>the</span> <span m='1163770'>vertices</span> <span m='1164885'>in</span>
  <span m='1165210'>some</span> <span m='1165460'>order.</span> <span m='1166430'>And</span>
  <span m='1166790'>you'd</span> <span m='1166940'>like</span> <span m='1167130'>it</span>
  <span m='1167230'>to</span> <span m='1167280'>unfold</span> <span m='1167710'>without</span>
  <span m='1167990'>overlap.</span> <span m='1169100'>So</span> <span m='1169290'>is</span>
  <span m='1169450'>this</span> <span m='1169570'>always</span> <span m='1169840'>possible?</span>
  </p><p><span m='1174280'>This</span> <span m='1174460'>is</span> <span m='1174620'>a</span>
  <span m='1175650'>father,</span> <span m='1176300'>son,</span> <span m='1177180'>mother,</span>
  <span m='1177760'>son,</span> <span m='1178080'>son</span> <span m='1178500'>paper.</span>
  <span m='1179780'>So</span> <span m='1179850'>this</span> <span m='1180040'>is</span>
  <span m='1180160'>my</span> <span m='1180320'>advisor</span> <span m='1180690'>again</span>
  <span m='1180940'>and</span> <span m='1181030'>her</span> <span m='1181220'>two</span>
  <span m='1181410'>sons.</span> <span m='1181790'>Although</span> <span m='1181990'>we</span>
  <span m='1182090'>like</span> <span m='1182250'>to</span> <span m='1182340'>say</span>
  <span m='1182470'>this</span> <span m='1182680'>a</span> <span m='1182770'>paper</span>
  <span m='1183050'>with</span> <span m='1183190'>her</span> <span m='1183310'>three</span>
  <span m='1183570'>sons,</span> <span m='1183910'>because</span> <span m='1184100'>I'm</span>
  <span m='1184240'>her</span> <span m='1184380'>academic</span> <span m='1184940'>son--</span>
  <span m='1187020'>or</span> <span m='1187180'>four,</span> <span m='1187520'>if</span>
  <span m='1187580'>you</span> <span m='1187680'>count</span> <span m='1187900'>Marty</span>
  <span m='1188250'>too.</span> <span m='1188560'>She</span> <span m='1188956'>was</span>
  <span m='1189750'>his</span> <span m='1189960'>advisor as</span> <span m='1190380'>well.</span>
  </p><p><span m='1191350'>So</span> <span m='1191510'>here are</span> <span m='1191770'>some</span>
  <span m='1192030'>examples</span> <span m='1192730'>of</span> <span m='1193050'>good</span>
  <span m='1193240'>unfolding.</span> <span m='1193800'>So</span> <span m='1193930'>we</span>
  <span m='1194010'>have</span> <span m='1194230'>the</span> <span m='1194330'>platonic</span>
  <span m='1194820'>solids.</span> <span m='1195200'>These</span> <span m='1195370'>are</span>
  <span m='1195440'>just</span> <span m='1195840'>typical</span> <span m='1196250'>unfoldings.</span>
  <span m='1197170'>These</span> <span m='1197420'>are</span> <span m='1197630'>all</span>
  <span m='1197940'>zipper</span> <span m='1198350'>unfoldings.</span> </p><p><span
  m='1199220'>So</span> <span m='1199410'>we're</span> <span m='1199560'>cutting</span>
  <span m='1199830'>along</span> <span m='1200100'>edges,</span> <span m='1200950'>along</span>
  <span m='1201490'>a</span> <span m='1201570'>Hamiltonian</span> <span m='1202090'>path</span>
  <span m='1202470'>that</span> <span m='1202570'>doesn't</span> <span m='1202830'>overlap.</span>
  <span m='1203300'>They</span> <span m='1203430'>all</span> <span m='1203530'>have</span>
  <span m='1203690'>this</span> <span m='1203850'>kind</span> <span m='1204020'>of</span>
  <span m='1204100'>nice</span> <span m='1204460'>snake</span> <span m='1204810'>like</span>
  <span m='1205460'>shape.</span> <span m='1206210'>And</span> <span m='1206340'>so</span>
  <span m='1206530'>all</span> <span m='1206720'>platonic</span> <span m='1207130'>solids</span>
  <span m='1207400'>can</span> <span m='1207520'>be</span> <span m='1207640'>made</span>
  <span m='1207880'>by</span> <span m='1207990'>zipper</span> <span m='1208430'>edge</span>
  <span m='1208660'>unfoldings.</span> </p><p><span m='1210210'>Next,</span> <span
  m='1210460'>we</span> <span m='1210520'>did</span> <span m='1210710'>Archimedean</span>
  <span m='1211260'>solids.</span> <span m='1211740'>This</span> <span m='1211940'>is</span>
  <span m='1212230'>a</span> <span m='1212580'>lot</span> <span m='1212790'>more</span>
  <span m='1213000'>work.</span> <span m='1213480'>But</span> <span m='1213830'>again,</span>
  <span m='1214150'>you</span> <span m='1214260'>get</span> <span m='1214440'>these</span>
  <span m='1214640'>nice</span> <span m='1215410'>S-like</span> <span m='1215880'>curves.</span>
  <span m='1217800'>And</span> <span m='1218650'>they're</span> <span m='1218810'>all</span>
  <span m='1218910'>zipper</span> <span m='1219200'>unfolding,</span> <span m='1219495'>because
  they're</span> <span m='1219790'>all</span> <span m='1220130'>possible</span> <span
  m='1220400'>and</span> <span m='1220670'>they'll</span> <span m='1220890'>have</span>
  <span m='1221790'>these</span> <span m='1221950'>Hamiltonian</span> <span m='1224040'>paths,</span>
  <span m='1225020'>cuts,</span> <span m='1225420'>and</span> <span m='1225580'>avoid</span>
  <span m='1225860'>overlap.</span> </p><p><span m='1227060'>But</span> <span m='1227270'>you</span>
  <span m='1227390'>may</span> <span m='1227510'>notice,</span> <span m='1227820'>there's</span>
  <span m='1227980'>one</span> <span m='1228270'>missing</span> <span m='1228700'>up</span>
  <span m='1228850'>there--</span> <span m='1228990'>the</span> <span m='1229120'>great</span>
  <span m='1229400'>Rhombi-Cosi-Dodecahedron,</span> <span m='1230890'>my</span> <span
  m='1231050'>favorite</span> <span m='1231315'>Archimedean</span> <span m='1231970'>solid.</span>
  <span m='1232870'>And</span> <span m='1233740'>it</span> <span m='1235100'>has</span>
  <span m='1235440'>a</span> <span m='1235570'>rather</span> <span m='1235870'>different</span>
  <span m='1236280'>looking</span> <span m='1236620'>unfolding.</span> <span m='1237000'>As</span>
  <span m='1237090'>far</span> <span m='1237220'>as</span> <span m='1237300'>we</span>
  <span m='1237400'>can</span> <span m='1237510'>tell,</span> <span m='1237680'>there's</span>
  <span m='1237900'>no</span> <span m='1238150'>S-shaped</span> <span m='1239060'>one--</span>
  <span m='1239430'>whatever</span> <span m='1239740'>that</span> <span m='1239920'>means.</span>
  <span m='1240350'>But</span> <span m='1240610'>you</span> <span m='1240760'>have</span>
  <span m='1240950'>to</span> <span m='1241050'>have</span> <span m='1241270'>a</span>
  <span m='1241350'>tree.</span> </p><p><span m='1242580'>These</span> <span m='1242850'>examples</span>
  <span m='1243420'>all</span> <span m='1243610'>had</span> <span m='1243890'>path-like--</span>
  <span m='1245310'>The</span> <span m='1245890'>dual</span> <span m='1246130'>graph</span>
  <span m='1246370'>was</span> <span m='1246510'>roughly</span> <span m='1247050'>a</span>
  <span m='1247120'>path.</span> <span m='1247470'>I</span> <span m='1247510'>guess</span>
  <span m='1247710'>it</span> <span m='1247830'>branches a</span> <span m='1248230'>little</span>
  <span m='1248450'>bit</span> <span m='1248600'>here.</span> <span m='1249970'>Here,</span>
  <span m='1250500'>it's</span> <span m='1250910'>very</span> <span m='1251280'>tree</span>
  <span m='1251540'>like,</span> <span m='1252150'>I guess.</span> </p><p><span m='1253810'>So</span>
  <span m='1254000'>all</span> <span m='1254300'>Archimedean</span> <span m='1254820'>solids</span>
  <span m='1255670'>can</span> <span m='1255840'>be</span> <span m='1255950'>done.</span>
  <span m='1257260'>One</span> <span m='1257520'>open</span> <span m='1257740'>question,</span>
  <span m='1258190'>next</span> <span m='1258980'>category</span> <span m='1259430'>up,</span>
  <span m='1259560'>is</span> <span m='1259720'>Johnson</span> <span m='1260160'>solids,</span>
  <span m='1260660'>which</span> <span m='1260880'>are</span> <span m='1260960'>all</span>
  <span m='1261190'>polyhedron</span> <span m='1261680'>made</span> <span m='1261890'>with</span>
  <span m='1262020'>regular</span> <span m='1262580'>polygon</span> <span m='1263160'>faces--</span>
  <span m='1263690'>convex</span> <span m='1264050'>polyhedron</span> <span m='1264310'>made</span>
  <span m='1264570'>by</span> <span m='1264770'>regular</span> <span m='1266050'>polygonal</span>
  <span m='1266380'>faces.</span> <span m='1266680'>Those</span> <span m='1266880'>we</span>
  <span m='1266990'>don't</span> <span m='1267150'>know,</span> <span m='1267490'>whether</span>
  <span m='1267720'>they</span> <span m='1267920'>always</span> <span m='1268150'>have</span>
  <span m='1268310'>zipper</span> <span m='1268710'>unfoldings.</span> </p><p><span
  m='1270040'>But</span> <span m='1270310'>we</span> <span m='1270420'>do</span> <span
  m='1270590'>know</span> <span m='1270850'>there</span> <span m='1271050'>are</span>
  <span m='1271100'>some</span> <span m='1271900'>convex</span> <span m='1272530'>polyhedra--</span>
  <span m='1273160'>like</span> <span m='1273440'>this</span> <span m='1273630'>rhombic</span>
  <span m='1274230'>dodecahedron--</span> <span m='1275990'>that</span> <span m='1276290'>do</span>
  <span m='1276440'>not</span> <span m='1277130'>have</span> <span m='1279640'>zipper</span>
  <span m='1279970'>unfoldings</span> <span m='1280490'>if</span> <span m='1280600'>you</span>
  <span m='1280720'>only</span> <span m='1280920'>cut</span> <span m='1281100'>along</span>
  <span m='1281570'>edges.</span> <span m='1281960'>Because</span> <span m='1282340'>this</span>
  <span m='1282560'>graph</span> <span m='1283030'>has</span> <span m='1283560'>no</span>
  <span m='1283760'>Hamiltonian</span> <span m='1284380'>path.</span> <span m='1284710'>So</span>
  <span m='1284860'>never</span> <span m='1285090'>mind</span> <span m='1286010'>avoiding</span>
  <span m='1286410'>overlap.</span> <span m='1286900'>There's</span> <span m='1287080'>some</span>
  <span m='1287230'>polyhedra</span> <span m='1287740'>that</span> <span m='1287840'>just</span>
  <span m='1288140'>aren't</span> <span m='1288230'>Hamiltonian.</span> </p><p><span
  m='1288840'>There's</span> <span m='1289070'>no</span> <span m='1289230'>path</span>
  <span m='1289530'>it</span> <span m='1289620'>visits</span> <span m='1290290'>every</span>
  <span m='1290510'>vertex</span> <span m='1290920'>exactly</span> <span m='1291330'>once</span>
  <span m='1291660'>and</span> <span m='1291770'>only</span> <span m='1292030'>follows</span>
  <span m='1292430'>edges.</span> <span m='1293890'>So</span> <span m='1295300'>there's</span>
  <span m='1295510'>nothing</span> <span m='1295780'>you</span> <span m='1295890'>could</span>
  <span m='1296030'>even</span> <span m='1296180'>hope</span> <span m='1296410'>to</span>
  <span m='1296490'>cut</span> <span m='1296650'>along</span> <span m='1296980'>and</span>
  <span m='1297260'>avoid</span> <span m='1297570'>overlap.</span> <span m='1299100'>So</span>
  <span m='1299300'>that's</span> <span m='1299500'>bad</span> <span m='1299700'>news</span>
  <span m='1299930'>for</span> <span m='1300590'>edge</span> <span m='1300890'>unfoldings.</span>
  </p><p><span m='1301590'>The</span> <span m='1301700'>big</span> <span m='1301950'>open</span>
  <span m='1302180'>question</span> <span m='1302510'>here</span> <span m='1302670'>is</span>
  <span m='1302770'>for</span> <span m='1302940'>general</span> <span m='1303360'>unfoldings</span>
  <span m='1303840'>if you're allowed</span> <span m='1304210'>to</span> <span m='1304290'>cut</span>
  <span m='1304510'>anywhere</span> <span m='1305020'>on a</span> <span m='1305090'>convex</span>
  <span m='1305530'>surface</span> <span m='1306420'>and</span> <span m='1306570'>do</span>
  <span m='1306680'>things</span> <span m='1306920'>like</span> <span m='1307090'>the</span>
  <span m='1307170'>sun</span> <span m='1307410'>unfolding.</span> <span m='1308030'>I</span>
  <span m='1308080'>mean,</span> <span m='1308540'>edge</span> <span m='1308760'>unfoldings,</span>
  <span m='1309500'>we</span> <span m='1309640'>don't</span> <span m='1309770'>know</span>
  <span m='1309880'>how</span> <span m='1310000'>to</span> <span m='1310100'>do</span>
  <span m='1310210'>them</span> <span m='1310360'>anyway.</span> <span m='1310800'>So</span>
  <span m='1312130'>if</span> <span m='1312280'>you</span> <span m='1312400'>allow</span>
  <span m='1312510'>general</span> <span m='1312910'>unfoldings,</span> <span m='1313280'>we've</span>
  <span m='1313370'>got</span> <span m='1313570'>star</span> <span m='1313850'>unfolding,</span>
  <span m='1314130'>source</span> <span m='1314400'>unfolding,</span> <span m='1314800'>sun</span>
  <span m='1315020'>unfolding,</span> <span m='1315450'>all</span> <span m='1315580'>sorts</span>
  <span m='1315810'>of</span> <span m='1315900'>things.</span> </p><p><span m='1317090'>But</span>
  <span m='1318090'>none</span> <span m='1318390'>of</span> <span m='1318500'>them</span>
  <span m='1318690'>are</span> <span m='1318800'>zipper</span> <span m='1319200'>unfoldings.</span>
  <span m='1319740'>They</span> <span m='1320120'>all</span> <span m='1320380'>cut</span>
  <span m='1320580'>along</span> <span m='1320950'>trees.</span> <span m='1321520'>Like</span>
  <span m='1321720'>star</span> <span m='1322010'>unfolding</span> <span m='1322780'>cuts</span>
  <span m='1322990'>along</span> <span m='1323280'>a</span> <span m='1323380'>star.</span>
  <span m='1324500'>The</span> <span m='1324670'>source</span> <span m='1324980'>unfolding</span>
  <span m='1325500'>cuts</span> <span m='1325720'>along</span> <span m='1325920'>the</span>
  <span m='1326010'>ridge</span> <span m='1326180'>tree,</span> <span m='1326460'>which</span>
  <span m='1326650'>is</span> <span m='1327210'>going</span> <span m='1327330'>to</span>
  <span m='1327380'>be</span> <span m='1327510'>very</span> <span m='1327740'>tree</span>
  <span m='1327960'>like</span> <span m='1328200'>thing.</span> </p><p><span m='1328910'>Can</span>
  <span m='1329180'>you</span> <span m='1329380'>always</span> <span m='1331030'>convert</span>
  <span m='1331450'>a</span> <span m='1331510'>tree</span> <span m='1331830'>cut</span>
  <span m='1332160'>into</span> <span m='1332360'>a</span> <span m='1332420'>path</span>
  <span m='1332860'>cut?</span> <span m='1333040'>We've</span> <span m='1333200'>tried.</span>
  <span m='1334520'>It seems</span> <span m='1334840'>quite</span> <span m='1335320'>challenging.</span>
  <span m='1337550'>So</span> <span m='1337840'>that's</span> <span m='1337980'>the</span>
  <span m='1338100'>open</span> <span m='1338300'>problem.</span> <span m='1338680'>Does</span>
  <span m='1338840'>every</span> <span m='1339200'>convex</span> <span m='1339660'>polyhedron</span>
  <span m='1340210'>have</span> <span m='1340480'>a</span> <span m='1341240'>general</span>
  <span m='1342270'>zipper</span> <span m='1342640'>unfolding,</span> <span m='1344860'>because
  edge</span> <span m='1345180'>unfolding</span> <span m='1345580'>is</span> <span
  m='1345630'>always</span> <span m='1346030'>too</span> <span m='1346170'>much</span>
  <span m='1346420'>to hope</span> <span m='1346610'>for.</span> </p><p><span m='1348010'>So</span>
  <span m='1348190'>those</span> <span m='1348410'>are</span> <span m='1349570'>some</span>
  <span m='1349830'>fun</span> <span m='1350040'>problems</span> <span m='1350440'>to</span>
  <span m='1350690'>think</span> <span m='1350940'>about.</span> <span m='1352735'>It's</span>
  <span m='1353220'>kind of like</span> <span m='1353440'>zipper</span> <span m='1353740'>unfolding.</span>
  </p><p><span m='1356760'>So</span> <span m='1357080'>the</span> <span m='1357150'>next</span>
  <span m='1357430'>topic--</span> <span m='1358110'>oh,</span> <span m='1358650'>right.</span>
  <span m='1358870'>One</span> <span m='1359090'>more</span> <span m='1359260'>thing</span>
  <span m='1359590'>to</span> <span m='1359690'>show,</span> <span m='1360250'>this</span>
  <span m='1360440'>is</span> <span m='1360570'>a</span> <span m='1360630'>very</span>
  <span m='1360830'>fun</span> <span m='1361090'>talk</span> <span m='1361430'>that</span>
  <span m='1361560'>we</span> <span m='1361700'>gave.</span> <span m='1363240'>All</span>
  <span m='1363450'>five</span> <span m='1363740'>of</span> <span m='1363860'>us</span>
  <span m='1364040'>gave</span> <span m='1364220'>this</span> <span m='1364410'>talk</span>
  <span m='1364810'>at</span> <span m='1365310'>Canadian</span> <span m='1366150'>Conference</span>
  <span m='1366530'>on</span> <span m='1366610'>Computational</span> <span m='1367130'>Geometry.</span>
  </p><p><span m='1368110'>And</span> <span m='1368300'>one</span> <span m='1368460'>of</span>
  <span m='1368530'>the</span> <span m='1368630'>props</span> <span m='1369100'>in</span>
  <span m='1369220'>the</span> <span m='1369470'>talk</span> <span m='1369780'>was</span>
  <span m='1369950'>this</span> <span m='1370480'>cardboard</span> <span m='1370900'>box.</span>
  <span m='1371270'>And</span> <span m='1371390'>in</span> <span m='1371510'>the</span>
  <span m='1371580'>middle</span> <span m='1371820'>of</span> <span m='1371880'>the</span>
  <span m='1371990'>talk,</span> <span m='1372270'>it</span> <span m='1372380'>starts</span>
  <span m='1372720'>jiggling.</span> <span m='1373920'>And</span> <span m='1374190'>actually,</span>
  <span m='1374460'>initially,</span> <span m='1374820'>only</span> <span m='1375020'>four
  of</span> <span m='1375320'>the</span> <span m='1375450'>co-authors</span> <span
  m='1376010'>were</span> <span m='1376810'>giving</span> <span m='1377090'>the</span>
  <span m='1377200'>talk,</span> <span m='1377880'>because</span> <span m='1378210'>the</span>
  <span m='1378300'>fifth</span> <span m='1378540'>one</span> <span m='1378750'>was</span>
  <span m='1378910'>hiding</span> <span m='1379230'>inside</span> <span m='1379600'>the</span>
  <span m='1379680'>box.</span> <span m='1381220'>And</span> <span m='1381410'>then</span>
  <span m='1381730'>in</span> <span m='1381890'>the</span> <span m='1381980'>middle</span>
  <span m='1382230'>of</span> <span m='1382310'>the</span> <span m='1382400'>talk,</span>
  <span m='1383170'>he</span> <span m='1383360'>just</span> <span m='1383970'>jumps</span>
  <span m='1384300'>out</span> <span m='1385040'>and</span> <span m='1385220'>then</span>
  <span m='1385450'>starts</span> <span m='1385750'>speaking,</span> <span m='1386340'>as</span>
  <span m='1386570'>if</span> <span m='1386750'>nothing</span> <span m='1387150'>happened.</span>
  </p><p><span m='1388180'>It was</span> <span m='1388370'>a</span> <span m='1388420'>lot</span>
  <span m='1388590'>of</span> <span m='1388680'>fun.</span> <span m='1389720'>At</span>
  <span m='1389930'>this</span> <span m='1390120'>point,</span> <span m='1391450'>our</span>
  <span m='1391620'>son,</span> <span m='1391730'>Jonah,</span> <span m='1392240'>is</span>
  <span m='1392430'>in</span> <span m='1392530'>the</span> <span m='1392610'>box.</span>
  <span m='1393200'>He was</span> <span m='1393470'>fairly</span> <span m='1393990'>small.</span>
  <span m='1394320'>He's</span> <span m='1394500'>grown</span> <span m='1394690'>up</span>
  <span m='1394810'>a</span> <span m='1394870'>lot</span> <span m='1395110'>since,</span>
  <span m='1395530'>but</span> <span m='1396610'>at</span> <span m='1396740'>the</span>
  <span m='1396840'>time</span> <span m='1397090'>he</span> <span m='1397190'>fit</span>
  <span m='1397380'>nicely</span> <span m='1397750'>into</span> <span m='1397960'>this</span>
  <span m='1398210'>cardboard</span> <span m='1398520'>box,</span> <span m='1398770'>which</span>
  <span m='1398930'>was</span> <span m='1399040'>maybe</span> <span m='1399970'>this</span>
  <span m='1400600'>big.</span> </p><p><span m='1401930'>I</span> <span m='1401970'>think</span>
  <span m='1402170'>we</span> <span m='1402280'>give</span> <span m='1402460'>him</span>
  <span m='1402620'>a</span> <span m='1402680'>book</span> <span m='1403050'>and</span>
  <span m='1403130'>a</span> <span m='1403180'>flashlight</span> <span m='1403870'>and</span>
  <span m='1403990'>stuff</span> <span m='1404220'>to</span> <span m='1404350'>do</span>
  <span m='1404660'>while</span> <span m='1404880'>he</span> <span m='1405020'>was</span>
  <span m='1405180'>sitting</span> <span m='1405380'>there,</span> <span m='1406170'>waiting</span>
  <span m='1406640'>for</span> <span m='1406820'>his</span> <span m='1407000'>slides,</span>
  <span m='1408200'>waiting</span> <span m='1408470'>for</span> <span m='1408580'>the</span>
  <span m='1408720'>queue</span> <span m='1408920'>to</span> <span m='1409010'>come</span>
  <span m='1409230'>out.</span> <span m='1410440'>There</span> <span m='1410610'>we
  go.</span> <span m='1416610'>So</span> <span m='1416800'>those</span> <span m='1417030'>are</span>
  <span m='1417150'>unfolding</span> <span m='1417550'>of</span> <span m='1417640'>the</span>
  <span m='1417720'>cube</span> <span m='1418070'>or</span> <span m='1418220'>a</span>
  <span m='1418260'>box</span> <span m='1418560'>in</span> <span m='1418640'>general.</span>
  </p><p><span m='1421910'>Next</span> <span m='1422170'>topic</span> <span m='1422560'>is</span>
  <span m='1423040'>going</span> <span m='1423250'>back</span> <span m='1423430'>to</span>
  <span m='1423560'>edge</span> <span m='1423800'>unfolding.</span> <span m='1425851'>I
  like</span> <span m='1426300'>this</span> <span m='1426500'>comment.</span> <span
  m='1427420'>I</span> <span m='1427580'>thought</span> <span m='1427860'>they</span>
  <span m='1427960'>were</span> <span m='1428100'>pretty</span> <span m='1428360'>obvious,</span>
  <span m='1429000'>but</span> <span m='1429180'>now</span> <span m='1429370'>you've</span>
  <span m='1429570'>convinced</span> <span m='1429980'>me</span> <span m='1430100'>otherwise.</span>
  <span m='1430820'>And</span> <span m='1431490'>some</span> <span m='1431750'>of</span>
  <span m='1431800'>the</span> <span m='1431920'>evidence</span> <span m='1432300'>for</span>
  <span m='1432520'>edge</span> <span m='1432670'>unfolding</span> <span m='1433060'>being</span>
  <span m='1433220'>difficult</span> <span m='1434450'>was</span> <span m='1434640'>this</span>
  <span m='1434860'>polyhedron,</span> <span m='1435490'>which</span> <span m='1435650'>we</span>
  <span m='1435790'>proved</span> <span m='1436270'>has</span> <span m='1436670'>no</span>
  <span m='1436980'>edge</span> <span m='1437200'>unfolding.</span> <span m='1437720'>I</span>
  <span m='1437760'>didn't</span> <span m='1438010'>say</span> <span m='1438180'>it</span>
  <span m='1438270'>in</span> <span m='1438380'>lecture,</span> <span m='1438670'>but</span>
  <span m='1438790'>we</span> <span m='1438910'>call</span> <span m='1439140'>it</span>
  <span m='1439550'>edge</span> <span m='1439980'>on</span> <span m='1440260'>unfoldable,</span>
  <span m='1441210'>because</span> <span m='1441370'>they</span> <span m='1441460'>cannot</span>
  <span m='1441880'>be</span> <span m='1442090'>unfolded.</span> </p><p><span m='1444350'>This</span>
  <span m='1444600'>is</span> <span m='1444720'>actually</span> <span m='1445120'>the</span>
  <span m='1445230'>first</span> <span m='1445520'>example</span> <span m='1445930'>we</span>
  <span m='1446050'>came</span> <span m='1446320'>up</span> <span m='1446460'>with.</span>
  <span m='1446700'>I</span> <span m='1446830'>mention</span> <span m='1447170'>it</span>
  <span m='1447300'>only</span> <span m='1447550'>because</span> <span m='1448570'>it</span>
  <span m='1448670'>has</span> <span m='1448860'>fewer</span> <span m='1449130'>faces.</span>
  <span m='1450480'>We</span> <span m='1450620'>usually</span> <span m='1450880'>show</span>
  <span m='1451060'>this</span> <span m='1451270'>one</span> <span m='1451410'>because</span>
  <span m='1451620'>it's</span> <span m='1451800'>triangulated</span> <span m='1452175'>and</span>
  <span m='1452550'>that's</span> <span m='1452750'>kind</span> <span m='1452890'>of</span>
  <span m='1453000'>cooler.</span> <span m='1453840'>This</span> <span m='1454010'>one</span>
  <span m='1454140'>has</span> <span m='1454320'>convex</span> <span m='1454760'>faces</span>
  <span m='1455120'>still,</span> <span m='1455820'>so</span> <span m='1455980'>still</span>
  <span m='1456240'>topologically</span> <span m='1456980'>convex.</span> </p><p><span
  m='1457790'>I mean,</span> <span m='1457920'>if</span> <span m='1458070'>I</span>
  <span m='1458120'>pushed</span> <span m='1458390'>these</span> <span m='1458570'>points</span>
  <span m='1458900'>in,</span> <span m='1460110'>the</span> <span m='1460260'>polyhedron</span>
  <span m='1460730'>would</span> <span m='1460840'>be</span> <span m='1460960'>convex</span>
  <span m='1461940'>but</span> <span m='1462050'>has</span> <span m='1462240'>fewer</span>
  <span m='1462500'>faces.</span> <span m='1462950'>It</span> <span m='1463040'>has</span>
  <span m='1464440'>I</span> <span m='1464530'>guess</span> <span m='1464750'>six</span>
  <span m='1466000'>faces</span> <span m='1466670'>per</span> <span m='1467000'>hat,</span>
  <span m='1468190'>times</span> <span m='1468640'>4</span> <span m='1469400'>hats,</span>
  <span m='1470190'>so</span> <span m='1470490'>24</span> <span m='1471690'>faces.</span>
  <span m='1474000'>This</span> <span m='1474430'>was</span> <span m='1474800'>done</span>
  <span m='1475030'>in</span> <span m='1475330'>'99.</span> </p><p><span m='1476440'>It</span>
  <span m='1476560'>turns</span> <span m='1476780'>out</span> <span m='1476910'>at</span>
  <span m='1477010'>exactly</span> <span m='1477550'>the</span> <span m='1477670'>same</span>
  <span m='1477940'>time,</span> <span m='1478740'>there</span> <span m='1478850'>was</span>
  <span m='1478980'>this</span> <span m='1479160'>paper</span> <span m='1479520'>by</span>
  <span m='1479650'>Tarasov</span> <span m='1480420'>called,</span> <span m='1480630'>"Polyhedron</span>
  <span m='1481140'>with</span> <span m='1481260'>No</span> <span m='1481400'>Natural</span>
  <span m='1481780'>Unfolding."</span> <span m='1482180'>The</span> <span m='1482280'>paper</span>
  <span m='1482550'>has</span> <span m='1482720'>no</span> <span m='1482890'>figures,</span>
  <span m='1483350'>so</span> <span m='1483650'>I</span> <span m='1483740'>had</span>
  <span m='1483900'>to</span> <span m='1483960'>draw</span> <span m='1484200'>one</span>
  <span m='1484855'>to</span> <span m='1485240'>show</span> <span m='1485410'>you</span>
  <span m='1485550'>what</span> <span m='1485650'>it</span> <span m='1485720'>looks</span>
  <span m='1485920'>like.</span> </p><p><span m='1486090'>It's</span> <span m='1486230'>just</span>
  <span m='1486430'>a</span> <span m='1486530'>cube.</span> <span m='1487580'>And</span>
  <span m='1487770'>then</span> <span m='1487970'>at</span> <span m='1488100'>each</span>
  <span m='1488370'>corner</span> <span m='1488700'>of</span> <span m='1488770'>the</span>
  <span m='1488860'>cube,</span> <span m='1489200'>you</span> <span m='1489320'>cut</span>
  <span m='1489510'>off</span> <span m='1489660'>the</span> <span m='1489750'>corner</span>
  <span m='1490100'>and</span> <span m='1490180'>then</span> <span m='1491110'>pull</span>
  <span m='1491520'>the</span> <span m='1491600'>point</span> <span m='1491910'>out.</span>
  <span m='1493450'>And</span> <span m='1493860'>they</span> <span m='1493970'>proved,</span>
  <span m='1494390'>by a</span> <span m='1494590'>pretty</span> <span m='1494870'>similar</span>
  <span m='1495290'>argument--</span> <span m='1496200'>I mean,</span> <span m='1496690'>essentially</span>
  <span m='1496990'>you</span> <span m='1497290'>treat</span> <span m='1497550'>each</span>
  <span m='1497710'>of</span> <span m='1497800'>these</span> <span m='1498050'>as</span>
  <span m='1498180'>a</span> <span m='1498230'>hat.</span> <span m='1498730'>It's</span>
  <span m='1499220'>kind</span> <span m='1499380'>of</span> <span m='1499460'>a</span>
  <span m='1499540'>very</span> <span m='1499740'>simple</span> <span m='1500060'>hat.</span>
  <span m='1500350'>They</span> <span m='1500440'>happen</span> <span m='1500720'>to</span>
  <span m='1500840'>overlap;</span> <span m='1501310'>they</span> <span m='1501410'>share</span>
  <span m='1501660'>edges.</span> </p><p><span m='1502730'>But</span> <span m='1502880'>again,</span>
  <span m='1503170'>because</span> <span m='1503500'>of</span> <span m='1503600'>these</span>
  <span m='1504060'>negative</span> <span m='1504410'>curvature</span> <span m='1504760'>vertices,</span>
  <span m='1505170'>you</span> <span m='1505250'>have</span> <span m='1505450'>to</span>
  <span m='1505560'>cut</span> <span m='1505820'>through</span> <span m='1506020'>the</span>
  <span m='1506100'>hat.</span> <span m='1506930'>And</span> <span m='1507350'>that</span>
  <span m='1507560'>cut</span> <span m='1507940'>has</span> <span m='1508130'>to</span>
  <span m='1508210'>keep</span> <span m='1508370'>going</span> <span m='1508580'>around.</span>
  <span m='1508860'>Eventually, it</span> <span m='1509240'>forms</span> <span m='1509510'>a</span>
  <span m='1509570'>cycle.</span> <span m='1510070'>So</span> <span m='1511670'>that's</span>
  <span m='1511850'>what</span> <span m='1511920'>Tarasov</span> <span m='1512190'>proved</span>
  <span m='1512610'>in</span> <span m='1512860'>the</span> <span m='1512940'>same</span>
  <span m='1513170'>year,</span> <span m='1513370'>'99.</span> </p><p><span m='1515480'>And</span>
  <span m='1515730'>then</span> <span m='1516370'>Grunbaum--</span> <span m='1517860'>he's
  a</span> <span m='1518050'>famous</span> <span m='1518510'>geometer</span> <span
  m='1519030'>in</span> <span m='1520030'>Seattle--</span> <span m='1522830'>came</span>
  <span m='1523070'>up</span> <span m='1523180'>with</span> <span m='1523290'>some</span>
  <span m='1523430'>more</span> <span m='1523640'>examples.</span> <span m='1524230'>So</span>
  <span m='1524290'>he</span> <span m='1525200'>initially</span> <span m='1525770'>wanted</span>
  <span m='1526110'>to</span> <span m='1526220'>make</span> <span m='1526380'>a</span>
  <span m='1526470'>star</span> <span m='1526880'>shaped</span> <span m='1527230'>example.</span>
  <span m='1527780'>Star</span> <span m='1528010'>shaped</span> <span m='1528270'>means</span>
  <span m='1528550'>that</span> <span m='1529370'>there's</span> <span m='1529700'>a</span>
  <span m='1529760'>single</span> <span m='1530120'>point,</span> <span m='1530410'>namely</span>
  <span m='1530680'>the</span> <span m='1530780'>center,</span> <span m='1531520'>where
  you</span> <span m='1531730'>can</span> <span m='1531840'>shine</span> <span m='1532130'>a</span>
  <span m='1532200'>light</span> <span m='1532440'>in</span> <span m='1532580'>all</span>
  <span m='1532690'>directions</span> <span m='1533250'>and</span> <span m='1533390'>the</span>
  <span m='1533460'>light</span> <span m='1533680'>reaches</span> <span m='1534010'>the</span>
  <span m='1534110'>entire</span> <span m='1534460'>interior</span> <span m='1535090'>of</span>
  <span m='1535270'>the</span> <span m='1535490'>polyhedron.</span> </p><p><span m='1536990'>He</span>
  <span m='1537120'>didn't</span> <span m='1537310'>know</span> <span m='1537440'>about</span>
  <span m='1537660'>our</span> <span m='1537790'>witch</span> <span m='1538010'>hat</span>
  <span m='1538190'>example.</span> <span m='1538740'>So</span> <span m='1539590'>he</span>
  <span m='1539800'>took</span> <span m='1540110'>the</span> <span m='1540550'>Tarasov</span>
  <span m='1541050'>example,</span> <span m='1541600'>made</span> <span m='1541690'>it
  a</span> <span m='1541840'>dodecahedron,</span> <span m='1542570'>and</span> <span
  m='1542730'>then</span> <span m='1543220'>it</span> <span m='1543370'>is</span>
  <span m='1543430'>star</span> <span m='1543740'>shaped.</span> <span m='1544500'>I
  think</span> <span m='1544690'>ours</span> <span m='1544890'>are</span> <span m='1545010'>already</span>
  <span m='1545470'>star</span> <span m='1545750'>shaped.</span> </p><p><span m='1547200'>So</span>
  <span m='1547400'>that's</span> <span m='1547630'>kind</span> <span m='1547790'>of</span>
  <span m='1547870'>fun.</span> <span m='1548130'>It looks</span> <span m='1548600'>like</span>
  <span m='1548850'>some</span> <span m='1549030'>scary</span> <span m='1549350'>underwater</span>
  <span m='1549770'>creature.</span> <span m='1551110'>And</span> <span m='1551340'>then</span>
  <span m='1551650'>he</span> <span m='1551970'>learned</span> <span m='1552180'>about</span>
  <span m='1552370'>our</span> <span m='1552530'>paper,</span> <span m='1553000'>and</span>
  <span m='1553120'>he</span> <span m='1553190'>said,</span> <span m='1553380'>all</span>
  <span m='1553590'>right,</span> <span m='1553700'>I</span> <span m='1553730'>want</span>
  <span m='1553900'>to</span> <span m='1553940'>get</span> <span m='1554070'>as</span>
  <span m='1554200'>few</span> <span m='1554450'>faces</span> <span m='1554900'>as</span>
  <span m='1555040'>possible.</span> <span m='1556000'>And so</span> <span m='1556170'>we</span>
  <span m='1556300'>had</span> <span m='1556570'>26,</span> <span m='1558180'>was</span>
  <span m='1558300'>it,</span> <span m='1558390'>24?</span> </p><p><span m='1559630'>This</span>
  <span m='1559910'>one</span> <span m='1560670'>has</span> <span m='1561290'>only</span>
  <span m='1561630'>13</span> <span m='1562340'>faces.</span> <span m='1563580'>And</span>
  <span m='1564270'>it</span> <span m='1564590'>has</span> <span m='1564780'>tetrahedral--</span>
  <span m='1565740'>well, that's</span> <span m='1565960'>not</span> <span m='1566260'>actually</span>
  <span m='1566540'>tetrahedrally</span> <span m='1567120'>asymmetric,</span> <span
  m='1567750'>because this</span> <span m='1568000'>bottom</span> <span m='1568490'>spike</span>
  <span m='1568880'>is</span> <span m='1569030'>different</span> <span m='1569370'>from</span>
  <span m='1569520'>the</span> <span m='1569670'>others.</span> <span m='1570880'>But</span>
  <span m='1570910'>it's</span> <span m='1571050'>kind</span> <span m='1571340'>of</span>
  <span m='1571420'>like</span> <span m='1572200'>Tarasov's</span> <span m='1572690'>example</span>
  <span m='1573250'>down</span> <span m='1573540'>to</span> <span m='1573650'>its</span>
  <span m='1573860'>very</span> <span m='1574120'>minimal</span> <span m='1575160'>amounts,</span>
  <span m='1575600'>also</span> <span m='1575900'>star</span> <span m='1576170'>shaped.</span>
  </p><p><span m='1577780'>And</span> <span m='1577920'>his</span> <span m='1578120'>conjecture</span>
  <span m='1578710'>is</span> <span m='1578910'>that,</span> <span m='1579030'>if</span>
  <span m='1579150'>you</span> <span m='1579220'>have</span> <span m='1579400'>12</span>
  <span m='1579810'>faces</span> <span m='1580270'>or</span> <span m='1580390'>fewer,</span>
  <span m='1581420'>there</span> <span m='1581600'>is</span> <span m='1581740'>no</span>
  <span m='1582650'>un-unfoldable</span> <span m='1583540'>polyhedron.</span> <span
  m='1584480'>So</span> <span m='1584640'>he</span> <span m='1584830'>says</span>
  <span m='1585100'>polyhedra</span> <span m='1585700'>with</span> <span m='1585990'>12</span>
  <span m='1586280'>faces</span> <span m='1587100'>are</span> <span m='1587350'>un-un-unfoldable.</span>
  <span m='1590130'>He</span> <span m='1590290'>wanted</span> <span m='1590480'>to</span>
  <span m='1591190'>one</span> <span m='1591410'>up</span> <span m='1591600'>us.</span>
  <span m='1593310'>Open</span> <span m='1593600'>problem</span> <span m='1593990'>is</span>
  <span m='1594120'>to</span> <span m='1594250'>define</span> <span m='1594780'>un-un-un-unfoldable.</span>
  <span m='1597960'>But we're</span> <span m='1598140'>up</span> <span m='1598240'>to</span>
  <span m='1598360'>three.</span> </p><p><span m='1602580'>So</span> <span m='1602810'>that's</span>
  <span m='1603090'>some</span> <span m='1603530'>un-unfoldable</span> <span m='1604150'>polyhedra</span>
  <span m='1605040'>and</span> <span m='1605210'>some</span> <span m='1606070'>conjectured</span>
  <span m='1606670'>un-un-unfoldable</span> <span m='1608370'>polyhedra.</span> <span
  m='1609330'>This</span> <span m='1609490'>is</span> <span m='1609620'>fun</span>
  <span m='1609800'>to</span> <span m='1609870'>say.</span> </p><p><span m='1610940'>The</span>
  <span m='1611270'>next</span> <span m='1611600'>result,</span> <span m='1611920'>which</span>
  <span m='1612070'>is</span> <span m='1612280'>very</span> <span m='1612530'>recent</span>
  <span m='1613010'>is</span> <span m='1613320'>that--</span> <span m='1614310'>this</span>
  <span m='1615430'>is</span> <span m='1615880'>with</span> <span m='1616170'>Zach</span>
  <span m='1616490'>Abel</span> <span m='1617110'>and</span> <span m='1617290'>myself--</span>
  <span m='1618250'>that</span> <span m='1618630'>it</span> <span m='1618750'>is</span>
  <span m='1618920'>NP-complete</span> <span m='1619670'>to</span> <span m='1619780'>decide,</span>
  <span m='1620350'>given</span> <span m='1620620'>a</span> <span m='1620690'>polyhedron,</span>
  <span m='1622330'>is</span> <span m='1622550'>it</span> <span m='1623080'>unfoldable</span>
  <span m='1623560'>or</span> <span m='1623890'>un-unfoldable--</span> <span m='1625020'>by</span>
  <span m='1625150'>cutting</span> <span m='1625460'>along</span> <span m='1625710'>edges.</span>
  <span m='1626250'>These</span> <span m='1626410'>are</span> <span m='1626510'>all</span>
  <span m='1626660'>cutting</span> <span m='1626890'>along</span> <span m='1627100'>edges.</span>
  <span m='1627850'>And</span> <span m='1628040'>we</span> <span m='1628140'>reduce</span>
  <span m='1628570'>from</span> <span m='1628760'>this</span> <span m='1628960'>problem,</span>
  <span m='1629840'>which</span> <span m='1630270'>comes</span> <span m='1630580'>from</span>
  <span m='1631340'>parallel</span> <span m='1631870'>computers</span> <span m='1632340'>actually--</span>
  <span m='1633620'>or</span> <span m='1634250'>geometry</span> <span m='1634730'>in</span>
  <span m='1634790'>general,</span> <span m='1635110'>you</span> <span m='1635210'>want</span>
  <span m='1635320'>to</span> <span m='1635380'>pack</span> <span m='1635700'>a</span>
  <span m='1635760'>bunch</span> <span m='1636010'>of</span> <span m='1636080'>squares</span>
  <span m='1636500'>into</span> <span m='1636770'>a</span> <span m='1636830'>square.</span>
  </p><p><span m='1637300'>So</span> <span m='1637450'>you</span> <span m='1637490'>have</span>
  <span m='1637850'>squares</span> <span m='1638310'>of</span> <span m='1638420'>different</span>
  <span m='1638740'>sizes.</span> <span m='1639930'>And</span> <span m='1640200'>you</span>
  <span m='1640320'>want</span> <span m='1640430'>to</span> <span m='1640480'>pack</span>
  <span m='1640770'>those</span> <span m='1640930'>squares</span> <span m='1641380'>into</span>
  <span m='1641890'>a</span> <span m='1641990'>given</span> <span m='1642350'>square.</span>
  <span m='1642910'>Is</span> <span m='1643090'>it</span> <span m='1643190'>possible?</span>
  <span m='1643640'>Yes</span> <span m='1643860'>or</span> <span m='1643940'>no?</span>
  <span m='1644490'>Sometimes</span> <span m='1644890'>it</span> <span m='1644960'>is,</span>
  <span m='1645120'>sometimes</span> <span m='1645510'>it</span> <span m='1645590'>isn't.</span>
  </p><p><span m='1647030'>This</span> <span m='1647330'>proof,</span> <span m='1647950'>by</span>
  <span m='1649520'>many</span> <span m='1649790'>people--</span> <span m='1650260'>Long,</span>
  <span m='1650520'>et</span> <span m='1650620'>al.--</span> <span m='1652390'>is</span>
  <span m='1652600'>from</span> <span m='1652810'>three</span> <span m='1653070'>partition,</span>
  <span m='1653690'>which</span> <span m='1653740'>is</span> <span m='1653830'>a</span>
  <span m='1653880'>problem</span> <span m='1654190'>we've</span> <span m='1654310'>seen.</span>
  <span m='1654550'>I</span> <span m='1654590'>won't</span> <span m='1654790'>go</span>
  <span m='1654920'>through</span> <span m='1655180'>it.</span> <span m='1655340'>But</span>
  <span m='1655500'>essentially,</span> <span m='1656550'>it's</span> <span m='1656710'>kind</span>
  <span m='1656940'>of</span> <span m='1657000'>like</span> <span m='1657190'>the</span>
  <span m='1657280'>disk</span> <span m='1657580'>packing</span> <span m='1657980'>proof,</span>
  <span m='1658240'>which</span> <span m='1658430'>I</span> <span m='1658480'>showed</span>
  <span m='1658770'>in</span> <span m='1658880'>lecture</span> <span m='1659280'>some</span>
  <span m='1659530'>time</span> <span m='1659800'>ago</span> <span m='1660090'>related</span>
  <span m='1660460'>to</span> <span m='1660760'>tree</span> <span m='1660980'>maker.</span>
  <span m='1662340'>But</span> <span m='1662830'>you</span> <span m='1662940'>set</span>
  <span m='1663160'>up</span> <span m='1663300'>this</span> <span m='1663550'>tiny</span>
  <span m='1663860'>space</span> <span m='1664280'>and</span> <span m='1664380'>you</span>
  <span m='1664500'>end</span> <span m='1664630'>up</span> <span m='1664740'>having</span>
  <span m='1665020'>to</span> <span m='1665680'>partition</span> <span m='1666840'>a</span>
  <span m='1666950'>bunch</span> <span m='1667200'>of</span> <span m='1667320'>your</span>
  <span m='1667730'>squares</span> <span m='1668200'>into</span> <span m='1669210'>groups,</span>
  <span m='1669660'>each</span> <span m='1669800'>with</span> <span m='1669960'>the</span>
  <span m='1670050'>same</span> <span m='1670320'>sum</span> <span m='1670740'>groups</span>
  <span m='1671120'>of</span> <span m='1671220'>size</span> <span m='1671530'>3.</span>
  </p><p><span m='1673950'>So</span> <span m='1674720'>starting</span> <span m='1675210'>from</span>
  <span m='1675910'>this</span> <span m='1676120'>problem</span> <span m='1676470'>of</span>
  <span m='1676550'>square</span> <span m='1676900'>packing,</span> <span m='1677290'>how</span>
  <span m='1677440'>do</span> <span m='1677520'>we</span> <span m='1677650'>convert
  it</span> <span m='1678050'>into</span> <span m='1678300'>an</span> <span m='1678460'>unfolding</span>
  <span m='1679150'>problem?</span> <span m='1681220'>This</span> <span m='1681460'>is</span>
  <span m='1681610'>a</span> <span m='1681720'>rough</span> <span m='1681990'>idea</span>
  <span m='1682460'>of</span> <span m='1682570'>the</span> <span m='1682710'>construction.</span>
  <span m='1683430'>So</span> <span m='1683780'>the</span> <span m='1683970'>big</span>
  <span m='1684180'>picture--</span> <span m='1684950'>this</span> <span m='1685180'>is</span>
  <span m='1685380'>initially</span> <span m='1685780'>a</span> <span m='1685850'>polyhedron</span>
  <span m='1686330'>with</span> <span m='1686480'>boundary.</span> <span m='1687000'>Later</span>
  <span m='1687240'>on,</span> <span m='1687390'>we'll</span> <span m='1687520'>remove</span>
  <span m='1687850'>the</span> <span m='1687940'>boundary.</span> </p><p><span m='1688680'>So</span>
  <span m='1688800'>just</span> <span m='1688990'>imagine</span> <span m='1689330'>a</span>
  <span m='1689390'>square,</span> <span m='1690360'>and</span> <span m='1690560'>in</span>
  <span m='1690650'>the</span> <span m='1690750'>square,</span> <span m='1691030'>there's</span>
  <span m='1691220'>a</span> <span m='1691320'>tower.</span> <span m='1692850'>Things</span>
  <span m='1693050'>are</span> <span m='1693110'>not</span> <span m='1693290'>drawn</span>
  <span m='1693460'>to</span> <span m='1693540'>scale</span> <span m='1693820'>here.</span>
  <span m='1693940'>The</span> <span m='1694070'>tower</span> <span m='1694480'>is</span>
  <span m='1694590'>super</span> <span m='1694970'>tall.</span> <span m='1697270'>This</span>
  <span m='1697650'>little</span> <span m='1697900'>pipe</span> <span m='1698250'>thing</span>
  <span m='1698590'>is</span> <span m='1698920'>very</span> <span m='1699500'>narrow</span>
  <span m='1699990'>and</span> <span m='1700130'>also</span> <span m='1700420'>very</span>
  <span m='1700930'>long.</span> <span m='1702010'>I</span> <span m='1702100'>think</span>
  <span m='1702740'>even</span> <span m='1703110'>way</span> <span m='1703400'>longer</span>
  <span m='1703780'>than</span> <span m='1703960'>anything</span> <span m='1704690'>in</span>
  <span m='1704780'>this</span> <span m='1704930'>picture.</span> </p><p><span m='1707130'>OK,</span>
  <span m='1707530'>so</span> <span m='1707760'>now</span> <span m='1708090'>along</span>
  <span m='1708770'>the</span> <span m='1709130'>side</span> <span m='1709620'>of</span>
  <span m='1709750'>the</span> <span m='1709880'>tower--</span> <span m='1710610'>so</span>
  <span m='1710970'>this</span> <span m='1711190'>is</span> <span m='1711420'>an</span>
  <span m='1711570'>unfolding.</span> <span m='1713010'>Like if</span> <span m='1713170'>you</span>
  <span m='1713290'>cut</span> <span m='1713750'>along</span> <span m='1714160'>these</span>
  <span m='1714410'>edges,</span> <span m='1714910'>you</span> <span m='1715080'>get</span>
  <span m='1715360'>a</span> <span m='1715440'>plus</span> <span m='1715800'>sign.</span>
  <span m='1716510'>This</span> <span m='1716680'>is</span> <span m='1716820'>the</span>
  <span m='1716930'>tower.</span> </p><p><span m='1718370'>Now,</span> <span m='1718900'>this</span>
  <span m='1719520'>grid</span> <span m='1719870'>stuff</span> <span m='1720260'>is</span>
  <span m='1720410'>something</span> <span m='1720770'>that</span> <span m='1720970'>I</span>
  <span m='1721080'>haven't</span> <span m='1721370'>shown</span> <span m='1721590'>you</span>
  <span m='1721720'>yet.</span> <span m='1722100'>But</span> <span m='1722630'>basically,</span>
  <span m='1723260'>think</span> <span m='1723490'>of</span> <span m='1723600'>it</span>
  <span m='1723690'>as</span> <span m='1724130'>water.</span> <span m='1724870'>It's</span>
  <span m='1724960'>very</span> <span m='1725400'>malleable.</span> <span m='1725960'>It</span>
  <span m='1726020'>can</span> <span m='1726780'>be cut</span> <span m='1727120'>open</span>
  <span m='1727430'>in</span> <span m='1727530'>many</span> <span m='1727740'>different</span>
  <span m='1728020'>ways.</span> <span m='1728780'>And</span> <span m='1729120'>essentially,</span>
  <span m='1730130'>you don't</span> <span m='1730430'>have</span> <span m='1730580'>to</span>
  <span m='1730670'>worry</span> <span m='1730810'>about it</span> <span m='1731100'>being</span>
  <span m='1731290'>there.</span> <span m='1731520'>It's</span> <span m='1731670'>like</span>
  <span m='1732290'>the</span> <span m='1732380'>glue</span> <span m='1732610'>that</span>
  <span m='1732710'>holds</span> <span m='1732920'>everything</span> <span m='1733260'>together.</span>
  </p><p><span m='1734010'>But</span> <span m='1734140'>then,</span> <span m='1734330'>there's</span>
  <span m='1734510'>these</span> <span m='1734740'>square</span> <span m='1735120'>faces,</span>
  <span m='1736705'>b1</span> <span m='1737260'>up</span> <span m='1737340'>to</span>
  <span m='1737470'>bn.</span> <span m='1738100'>These</span> <span m='1738350'>are</span>
  <span m='1738390'>the</span> <span m='1738510'>things</span> <span m='1738740'>you</span>
  <span m='1738810'>need</span> <span m='1738990'>to</span> <span m='1739060'>pack.</span>
  <span m='1739940'>So</span> <span m='1740070'>our</span> <span m='1740200'>goal</span>
  <span m='1740510'>is</span> <span m='1740600'>to</span> <span m='1740690'>set</span>
  <span m='1740920'>things</span> <span m='1741160'>up</span> <span m='1741370'>that</span>
  <span m='1741860'>so,</span> <span m='1742140'>when</span> <span m='1742340'>you</span>
  <span m='1742450'>take</span> <span m='1742640'>this</span> <span m='1742790'>tower</span>
  <span m='1743110'>out,</span> <span m='1743380'>you</span> <span m='1743480'>have</span>
  <span m='1743700'>a</span> <span m='1743790'>square</span> <span m='1744180'>hole.</span>
  <span m='1744550'>That</span> <span m='1744780'>is</span> <span m='1744890'>your</span>
  <span m='1745060'>target</span> <span m='1745940'>square</span> <span m='1746480'>shape.</span>
  </p><p><span m='1747240'>And</span> <span m='1747450'>then</span> <span m='1747650'>on</span>
  <span m='1747820'>the</span> <span m='1747900'>side</span> <span m='1748170'>of</span>
  <span m='1748240'>the</span> <span m='1748330'>tower,</span> <span m='1748590'>you've</span>
  <span m='1748750'>got</span> <span m='1748900'>all</span> <span m='1749030'>these</span>
  <span m='1749190'>squares.</span> <span m='1750090'>Basically</span> <span m='1750460'>those</span>
  <span m='1750700'>squares</span> <span m='1751030'>have</span> <span m='1751310'>to</span>
  <span m='1751410'>fit</span> <span m='1751600'>into</span> <span m='1751810'>that</span>
  <span m='1752000'>hole.</span> <span m='1752580'>So it is</span> <span m='1752870'>square</span>
  <span m='1753160'>packing.</span> <span m='1754230'>That</span> <span m='1754390'>is</span>
  <span m='1754510'>our</span> <span m='1754630'>goal.</span> </p><p><span m='1755200'>Now,</span>
  <span m='1755350'>the</span> <span m='1755460'>challenge</span> <span m='1755880'>for</span>
  <span m='1755980'>that</span> <span m='1756270'>is</span> <span m='1756440'>to</span>
  <span m='1756570'>make</span> <span m='1757200'>all</span> <span m='1757400'>of</span>
  <span m='1757530'>this</span> <span m='1757720'>stuff</span> <span m='1759560'>get</span>
  <span m='1759740'>out</span> <span m='1759910'>of</span> <span m='1760010'>the</span>
  <span m='1760110'>way</span> <span m='1760940'>and</span> <span m='1761100'>also</span>
  <span m='1761400'>for</span> <span m='1761580'>these</span> <span m='1761890'>squares--</span>
  <span m='1762240'>normally</span> <span m='1762570'>when</span> <span m='1762700'>you</span>
  <span m='1762810'>unfold,</span> <span m='1763190'>you're</span> <span m='1763290'>very</span>
  <span m='1763530'>constrained</span> <span m='1764070'>in</span> <span m='1764140'>how</span>
  <span m='1764320'>you</span> <span m='1764510'>lay</span> <span m='1764740'>out</span>
  <span m='1765010'>the</span> <span m='1765080'>faces.</span> <span m='1765540'>You</span>
  <span m='1765760'>can cut</span> <span m='1765930'>here or</span> <span m='1766210'>cut</span>
  <span m='1766400'>here,</span> <span m='1766640'>but</span> <span m='1766810'>there's</span>
  <span m='1767020'>a</span> <span m='1767170'>discrete</span> <span m='1767570'>set</span>
  <span m='1767730'>of</span> <span m='1767810'>choices.</span> <span m='1768680'>Our</span>
  <span m='1768850'>goal</span> <span m='1769040'>is</span> <span m='1769120'>to</span>
  <span m='1769240'>design</span> <span m='1769630'>this</span> <span m='1769870'>stuff</span>
  <span m='1770720'>so</span> <span m='1770800'>that these</span> <span m='1771030'>squares</span>
  <span m='1771360'>can</span> <span m='1771490'>just</span> <span m='1771670'>basically</span>
  <span m='1772010'>move</span> <span m='1772760'>willy-nilly</span> <span m='1773330'>without</span>
  <span m='1773700'>hitting</span> <span m='1773970'>each</span> <span m='1774140'>other.</span>
  <span m='1775230'>It's</span> <span m='1775360'>not</span> <span m='1775570'>easy</span>
  <span m='1775810'>to</span> <span m='1775930'>do,</span> <span m='1776290'>but</span>
  <span m='1776550'>that's</span> <span m='1776810'>the</span> <span m='1776900'>thing.</span>
  </p><p><span m='1777610'>This</span> <span m='1778000'>is</span> <span m='1778430'>one</span>
  <span m='1778640'>big</span> <span m='1778870'>face</span> <span m='1779230'>on</span>
  <span m='1779320'>the</span> <span m='1779460'>outside--</span> <span m='1780080'>this</span>
  <span m='1780240'>kind</span> <span m='1780400'>of L</span> <span m='1780530'>shape.</span>
  <span m='1781490'>We didn't</span> <span m='1781680'>want</span> <span m='1781830'>to</span>
  <span m='1781880'>go</span> <span m='1782020'>all the  way</span> <span m='1782290'>around</span>
  <span m='1782670'>for</span> <span m='1782780'>a</span> <span m='1782810'>couple</span>
  <span m='1783080'>reasons.</span> <span m='1783490'>One</span> <span m='1783560'>is</span>
  <span m='1783650'>we</span> <span m='1783760'>need</span> <span m='1784440'>a</span>
  <span m='1784530'>place</span> <span m='1784800'>for</span> <span m='1784880'>things</span>
  <span m='1785130'>to</span> <span m='1785200'>get</span> <span m='1785350'>out.</span>
  <span m='1785930'>But</span> <span m='1786150'>also,</span> <span m='1787890'>we</span>
  <span m='1788050'>wanted</span> <span m='1788310'>this</span> <span m='1788450'>to</span>
  <span m='1788540'>be</span> <span m='1788660'>topologically</span> <span m='1789320'>convex.</span>
  <span m='1789840'>So</span> <span m='1789950'>we</span> <span m='1790030'>didn't</span>
  <span m='1790200'>want</span> <span m='1790330'>to</span> <span m='1790370'>face</span>
  <span m='1790750'>that</span> <span m='1790880'>is</span> <span m='1791425'>a</span>
  <span m='1791730'>donut.</span> </p><p><span m='1793870'>OK,</span> <span m='1794260'>so</span>
  <span m='1794680'>what's</span> <span m='1794990'>the next</span> <span m='1795230'>part</span>
  <span m='1795370'>of</span> <span m='1795420'>the</span> <span m='1795510'>construction?</span>
  <span m='1796330'>Well,</span> <span m='1796800'>if</span> <span m='1796990'>we</span>
  <span m='1797130'>can</span> <span m='1797720'>arrange</span> <span m='1798440'>for</span>
  <span m='1798580'>these</span> <span m='1798870'>guys</span> <span m='1799280'>to</span>
  <span m='1800010'>move</span> <span m='1800310'>willy-nilly--</span> <span m='1800920'>that's</span>
  <span m='1801340'>these</span> <span m='1801780'>very</span> <span m='1802020'>thin</span>
  <span m='1802260'>lines--</span> <span m='1803150'>we</span> <span m='1803290'>can</span>
  <span m='1803390'>just</span> <span m='1803550'>imagine</span> <span m='1804100'>that</span>
  <span m='1804380'>if</span> <span m='1804530'>the</span> <span m='1804620'>squares</span>
  <span m='1805050'>are</span> <span m='1805130'>somehow</span> <span m='1805510'>packed,</span>
  <span m='1807430'>instead</span> <span m='1807810'>of</span> <span m='1807890'>having</span>
  <span m='1808350'>things</span> <span m='1808690'>overlapping</span> <span m='1809280'>like</span>
  <span m='1809480'>this,</span> <span m='1809780'>you</span> <span m='1809940'>can</span>
  <span m='1811210'>route</span> <span m='1811660'>all</span> <span m='1811860'>of</span>
  <span m='1811930'>those</span> <span m='1812140'>paths</span> <span m='1812620'>to</span>
  <span m='1812750'>avoid</span> <span m='1813050'>crossings.</span> <span m='1814700'>So</span>
  <span m='1814860'>as</span> <span m='1814950'>long</span> <span m='1815160'>as</span>
  <span m='1815270'>there's</span> <span m='1815450'>tiny</span> <span m='1815780'>gaps</span>
  <span m='1816140'>between</span> <span m='1816450'>all</span> <span m='1816540'>the</span>
  <span m='1816620'>squares,</span> <span m='1817160'>which</span> <span m='1817270'>doesn't</span>
  <span m='1817630'>turn</span> <span m='1817840'>out</span> <span m='1818020'>to</span>
  <span m='1818120'>change</span> <span m='1818700'>the</span> <span m='1819010'>square</span>
  <span m='1819250'>packing</span> <span m='1819580'>problem</span> <span m='1819840'>very</span>
  <span m='1820010'>much,</span> <span m='1820830'>you</span> <span m='1820980'>can</span>
  <span m='1822370'>do</span> <span m='1822510'>this.</span> </p><p><span m='1824080'>And</span>
  <span m='1824130'>then</span> <span m='1824300'>there's</span> <span m='1824500'>another</span>
  <span m='1824830'>issue,</span> <span m='1825210'>which</span> <span m='1825440'>is</span>
  <span m='1826800'>there's</span> <span m='1826960'>a</span> <span m='1827020'>lot</span>
  <span m='1827250'>of</span> <span m='1827310'>stuff</span> <span m='1827650'>here.</span>
  <span m='1827840'>You've</span> <span m='1827970'>got</span> <span m='1828110'>to</span>
  <span m='1828170'>put</span> <span m='1828380'>it</span> <span m='1828530'>somewhere,</span>
  <span m='1829340'>so</span> <span m='1829420'>you</span> <span m='1829520'>end</span>
  <span m='1829730'>up--</span> <span m='1830130'>it's</span> <span m='1830390'>very,</span>
  <span m='1830820'>very</span> <span m='1830950'>tiny--</span> <span m='1831760'>so</span>
  <span m='1831970'>in</span> <span m='1832060'>some</span> <span m='1832280'>cases,</span>
  <span m='1832620'>you</span> <span m='1832730'>have</span> <span m='1832950'>to</span>
  <span m='1833070'>do</span> <span m='1833170'>this</span> <span m='1833370'>kind</span>
  <span m='1833560'>of</span> <span m='1833660'>wiggling</span> <span m='1834490'>just</span>
  <span m='1834760'>to</span> <span m='1836040'>eat</span> <span m='1836200'>up</span>
  <span m='1836510'>length</span> <span m='1837830'>in</span> <span m='1837900'>certain</span>
  <span m='1838470'>settings.</span> <span m='1839510'>It</span> <span m='1839840'>gets</span>
  <span m='1840160'>complicated.</span> </p><p><span m='1841040'>So</span> <span m='1841120'>how</span>
  <span m='1841270'>do</span> <span m='1841370'>we</span> <span m='1841460'>do</span>
  <span m='1841570'>this</span> <span m='1841750'>wiggly</span> <span m='1842090'>stuff?</span>
  <span m='1843140'>Well,</span> <span m='1845340'>at the</span> <span m='1845570'>first</span>
  <span m='1845920'>level,</span> <span m='1847200'>there's</span> <span m='1847980'>a</span>
  <span m='1848100'>very</span> <span m='1848380'>fine</span> <span m='1848800'>grid</span>
  <span m='1849130'>with</span> <span m='1849270'>very</span> <span m='1849520'>small</span>
  <span m='1849920'>squares</span> <span m='1850370'>here.</span> <span m='1853370'>And</span>
  <span m='1853590'>we</span> <span m='1853700'>set</span> <span m='1853950'>it</span>
  <span m='1854060'>up</span> <span m='1854200'>so</span> <span m='1854360'>that</span>
  <span m='1854460'>we</span> <span m='1854600'>can</span> <span m='1854760'>follow</span>
  <span m='1855190'>everything</span> <span m='1855700'>along</span> <span m='1856190'>a</span>
  <span m='1856260'>single</span> <span m='1856660'>path.</span> <span m='1857150'>We</span>
  <span m='1857270'>can</span> <span m='1857410'>visit</span> <span m='1857760'>all
  of</span> <span m='1858040'>this</span> <span m='1858220'>great</span> <span m='1858490'>stuff</span>
  <span m='1858780'>along</span> <span m='1859030'>a</span> <span m='1859080'>single</span>
  <span m='1859350'>path.</span> <span m='1859960'>Occasionally,</span> <span m='1860460'>we</span>
  <span m='1860610'>will</span> <span m='1861350'>encounter</span> <span m='1861800'>squares,</span>
  <span m='1863120'>but</span> <span m='1863700'>the</span> <span m='1863880'>path</span>
  <span m='1864230'>length</span> <span m='1864490'>between</span> <span m='1864800'>any</span>
  <span m='1864970'>two</span> <span m='1865100'>squares</span> <span m='1865500'>is</span>
  <span m='1865610'>so</span> <span m='1865820'>big</span> <span m='1866280'>that</span>
  <span m='1866580'>these</span> <span m='1866850'>squares</span> <span m='1867320'>have</span>
  <span m='1867630'>room</span> <span m='1867830'>to</span> <span m='1867930'>kind</span>
  <span m='1868090'>of</span> <span m='1868160'>stretch</span> <span m='1868640'>out</span>
  <span m='1868930'>as</span> <span m='1869270'>far</span> <span m='1869710'>away</span>
  <span m='1870020'>from</span> <span m='1870200'>each</span> <span m='1870350'>other
  as</span> <span m='1870670'>they</span> <span m='1870760'>need</span> <span m='1870950'>to</span>
  <span m='1871040'>go.</span> </p><p><span m='1873010'>Now,</span> <span m='1873240'>these</span>
  <span m='1873420'>squares</span> <span m='1873790'>are</span> <span m='1873870'>not</span>
  <span m='1874080'>squares.</span> <span m='1874670'>They are</span> <span m='1874990'>actually</span>
  <span m='1875480'>this</span> <span m='1875800'>construction,</span> <span m='1876540'>which</span>
  <span m='1876740'>we</span> <span m='1876890'>call</span> <span m='1877160'>atoms.</span>
  <span m='1878440'>It looks</span> <span m='1878760'>like</span> <span m='1878960'>a</span>
  <span m='1879030'>weird</span> <span m='1879490'>set</span> <span m='1879770'>of</span>
  <span m='1880060'>pyramids,</span> <span m='1881830'>or</span> <span m='1882060'>outside</span>
  <span m='1882380'>of</span> <span m='1882470'>towers.</span> <span m='1883420'>But</span>
  <span m='1883560'>in</span> <span m='1883670'>fact,</span> <span m='1884870'>there's</span>
  <span m='1885110'>many</span> <span m='1885430'>different</span> <span m='1885690'>ways</span>
  <span m='1885910'>to</span> <span m='1885980'>unfold</span> <span m='1886450'>this.</span>
  </p><p><span m='1887280'>There's</span> <span m='1887560'>lots</span> <span m='1887820'>of</span>
  <span m='1887890'>different</span> <span m='1888110'>ways</span> <span m='1888270'>to</span>
  <span m='1888350'>cut</span> <span m='1888570'>it</span> <span m='1888660'>open.</span>
  <span m='1889400'>And</span> <span m='1889610'>some</span> <span m='1889860'>of</span>
  <span m='1889960'>them</span> <span m='1890120'>go</span> <span m='1890270'>straight.</span>
  <span m='1890660'>Some</span> <span m='1890840'>of</span> <span m='1890890'>them</span>
  <span m='1891040'>turn</span> <span m='1891230'>left.</span> <span m='1891540'>Some</span>
  <span m='1891760'>of</span> <span m='1891820'>them</span> <span m='1891970'>turn</span>
  <span m='1892190'>right.</span> <span m='1892910'>These</span> <span m='1893210'>are</span>
  <span m='1893280'>three</span> <span m='1893630'>of</span> <span m='1893700'>the</span>
  <span m='1893820'>unfoldings,</span> <span m='1894350'>I</span> <span m='1894460'>forget.</span>
  </p><p><span m='1894830'>There's</span> <span m='1895570'>a</span> <span m='1895700'>few</span>
  <span m='1895970'>dozen</span> <span m='1896320'>unfoldings</span> <span m='1896780'>that</span>
  <span m='1896960'>we</span> <span m='1897080'>need</span> <span m='1897810'>that</span>
  <span m='1897920'>all</span> <span m='1898090'>have</span> <span m='1898310'>the</span>
  <span m='1898430'>right</span> <span m='1898730'>parameters.</span> <span m='1899700'>This</span>
  <span m='1899860'>one's</span> <span m='1900010'>clearly</span> <span m='1900350'>turning</span>
  <span m='1900630'>left.</span> <span m='1901340'>This</span> <span m='1901460'>one's</span>
  <span m='1901570'>going</span> <span m='1901790'>straight</span> <span m='1902200'>in</span>
  <span m='1902330'>a</span> <span m='1902390'>certain</span> <span m='1902650'>sense.</span>
  <span m='1903850'>This</span> <span m='1904000'>is</span> <span m='1904080'>coming</span>
  <span m='1904420'>from</span> <span m='1904620'>a</span> <span m='1904670'>left</span>
  <span m='1904950'>turn</span> <span m='1905240'>and</span> <span m='1905310'>then</span>
  <span m='1905470'>going</span> <span m='1905730'>straight.</span> <span m='1906010'>So</span>
  <span m='1906290'>there's</span> <span m='1906450'>lots</span> <span m='1906670'>of</span>
  <span m='1906750'>combinations</span> <span m='1907410'>here,</span> <span m='1908060'>slightly</span>
  <span m='1908430'>different</span> <span m='1908700'>parities,</span> <span m='1909280'>and</span>
  <span m='1909390'>so</span> <span m='1909570'>on.</span> </p><p><span m='1910350'>But</span>
  <span m='1911070'>the</span> <span m='1911320'>end</span> <span m='1911440'>effect</span>
  <span m='1911860'>is</span> <span m='1912070'>that</span> <span m='1912240'>if</span>
  <span m='1912370'>you</span> <span m='1912470'>have</span> <span m='1912810'>a</span>
  <span m='1913160'>big</span> <span m='1913390'>grid</span> <span m='1913640'>of</span>
  <span m='1913750'>these</span> <span m='1914410'>and</span> <span m='1914550'>you're</span>
  <span m='1914640'>following</span> <span m='1915220'>them</span> <span m='1915410'>in</span>
  <span m='1915500'>a</span> <span m='1915550'>path,</span> <span m='1918690'>the</span>
  <span m='1919000'>path</span> <span m='1919340'>does</span> <span m='1919540'>some</span>
  <span m='1919820'>turns</span> <span m='1920170'>on</span> <span m='1920320'>the</span>
  <span m='1920410'>surface.</span> <span m='1921870'>But</span> <span m='1922160'>you</span>
  <span m='1922340'>can</span> <span m='1922510'>force</span> <span m='1922850'>it</span>
  <span m='1923010'>to</span> <span m='1923120'>do</span> <span m='1923310'>whatever</span>
  <span m='1923670'>turns</span> <span m='1923950'>you</span> <span m='1924070'>want</span>
  <span m='1924510'>in</span> <span m='1924640'>the</span> <span m='1924770'>unfolding.</span>
  <span m='1925320'>So</span> <span m='1925580'>you have</span> <span m='1925870'>complete</span>
  <span m='1926290'>freedom</span> <span m='1926670'>to</span> <span m='1926790'>move</span>
  <span m='1926990'>the</span> <span m='1927080'>squares</span> <span m='1927390'>around.</span>
  <span m='1928330'>As</span> <span m='1928470'>I</span> <span m='1928510'>showed</span>
  <span m='1928780'>you,</span> <span m='1929010'>you</span> <span m='1929130'>can</span>
  <span m='1929210'>avoid</span> <span m='1929400'>crossings,</span> <span m='1930450'>and</span>
  <span m='1930700'>it</span> <span m='1930770'>all</span> <span m='1931190'>works</span>
  <span m='1931470'>out.</span> </p><p><span m='1933160'>Maybe</span> <span m='1933370'>one</span>
  <span m='1933610'>detail,</span> <span m='1934070'>which</span> <span m='1934270'>I</span>
  <span m='1934320'>didn't</span> <span m='1935200'>mention,</span> <span m='1935640'>is</span>
  <span m='1936590'>there's</span> <span m='1937040'>going</span> <span m='1937170'>to</span>
  <span m='1937220'>be</span> <span m='1937340'>a</span> <span m='1937440'>ton</span>
  <span m='1937820'>of</span> <span m='1938030'>extra</span> <span m='1938410'>stuff.</span>
  <span m='1939370'>Where</span> <span m='1939570'>does</span> <span m='1939740'>it</span>
  <span m='1939920'>go?</span> <span m='1945630'>It's</span> <span m='1945820'>going</span>
  <span m='1945930'>to</span> <span m='1946000'>fill</span> <span m='1946310'>the</span>
  <span m='1946410'>pipe</span> <span m='1946710'>up.</span> <span m='1950240'>It's</span>
  <span m='1950420'>going</span> <span m='1950530'>to</span> <span m='1950590'>push</span>
  <span m='1950840'>these</span> <span m='1951130'>guys</span> <span m='1951580'>up</span>
  <span m='1951920'>somewhat.</span> </p><p><span m='1952860'>And</span> <span m='1953350'>this</span>
  <span m='1953560'>thing</span> <span m='1953720'>is so</span> <span m='1953810'>tall</span>
  <span m='1954520'>that</span> <span m='1954600'>there's</span> <span m='1954780'>room</span>
  <span m='1954990'>to</span> <span m='1955080'>put</span> <span m='1955260'>all</span>
  <span m='1955450'>the</span> <span m='1955590'>excess</span> <span m='1957540'>stuff</span>
  <span m='1958410'>in</span> <span m='1958580'>here.</span> <span m='1959790'>And</span>
  <span m='1959970'>it's</span> <span m='1960070'>also</span> <span m='1960350'>so</span>
  <span m='1960570'>tall</span> <span m='1960910'>that</span> <span m='1961020'>you</span>
  <span m='1961150'>can't</span> <span m='1961440'>just</span> <span m='1961710'>reach</span>
  <span m='1962150'>all</span> <span m='1962370'>the</span> <span m='1962440'>way</span>
  <span m='1962620'>out</span> <span m='1962900'>and</span> <span m='1963010'>put</span>
  <span m='1963160'>all</span> <span m='1963310'>the</span> <span m='1963370'>squares</span>
  <span m='1963690'>on</span> <span m='1963760'>the</span> <span m='1963880'>outside.</span>
  <span m='1964810'>OK, so</span> <span m='1965240'>if you</span> <span m='1965390'>make</span>
  <span m='1965570'>that</span> <span m='1965770'>super,</span> <span m='1966260'>super</span>
  <span m='1966430'>tall,</span> <span m='1968170'>none</span> <span m='1968350'>of</span>
  <span m='1968420'>the</span> <span m='1968500'>squares</span> <span m='1968850'>fit</span>
  <span m='1969090'>in</span> <span m='1969210'>here,</span> <span m='1969380'>because</span>
  <span m='1969550'>it's</span> <span m='1969710'>too</span> <span m='1969850'>narrow.</span>
  <span m='1970270'>And</span> <span m='1970420'>none of</span> <span m='1970580'>the</span>
  <span m='1970640'>squares can</span> <span m='1971060'>get</span> <span m='1971190'>up</span>
  <span m='1971320'>to</span> <span m='1971520'>the top,</span> <span m='1971760'>because</span>
  <span m='1971960'>it's</span> <span m='1972120'>too</span> <span m='1972375'>long.</span>
  <span m='1973160'>So</span> <span m='1973390'>that's</span> <span m='1973630'>how</span>
  <span m='1973740'>it</span> <span m='1973800'>works.</span> </p><p><span m='1975880'>Now,</span>
  <span m='1975920'>that</span> <span m='1976070'>was</span> <span m='1976170'>a</span>
  <span m='1976240'>polyhedron</span> <span m='1976740'>with</span> <span m='1976890'>boundary.</span>
  <span m='1978360'>Without</span> <span m='1978810'>boundary,</span> <span m='1979360'>the</span>
  <span m='1979590'>construction</span> <span m='1980070'>is</span> <span m='1980290'>almost</span>
  <span m='1980710'>the</span> <span m='1980760'>same.</span> <span m='1981690'>You</span>
  <span m='1981770'>just</span> <span m='1982050'>add</span> <span m='1982400'>some</span>
  <span m='1983280'>extra</span> <span m='1983830'>stuff</span> <span m='1984220'>on</span>
  <span m='1984310'>the</span> <span m='1984430'>outside</span> <span m='1984930'>to</span>
  <span m='1985040'>make</span> <span m='1985250'>it</span> <span m='1985585'>a</span>
  <span m='1985840'>regular</span> <span m='1986210'>polyhedron</span> <span m='1986710'>homeomorphic</span>
  <span m='1987300'>to a</span> <span m='1987440'>sphere.</span> <span m='1988180'>But</span>
  <span m='1988320'>in</span> <span m='1988440'>the</span> <span m='1988610'>end,</span>
  <span m='1988880'>you</span> <span m='1988990'>have</span> <span m='1989310'>basically</span>
  <span m='1989620'>the</span> <span m='1989700'>same</span> <span m='1989970'>construction</span>
  <span m='1990530'>of</span> <span m='1990630'>this</span> <span m='1990740'>nice</span>
  <span m='1991090'>square.</span> <span m='1991770'>The</span> <span m='1991870'>pipe</span>
  <span m='1992420'>and</span> <span m='1992670'>some</span> <span m='1992840'>other</span>
  <span m='1993050'>stuff,</span> <span m='1993340'>you</span> <span m='1993480'>prove</span>
  <span m='1994060'>basically</span> <span m='1994490'>doesn't</span> <span m='1994740'>matter.</span>
  </p><p><span m='1996490'>So</span> <span m='1996630'>that</span> <span m='1996820'>is</span>
  <span m='1997300'>NP-completeness</span> <span m='1999472'>of</span> <span m='1999920'>edge</span>
  <span m='2000160'>unfolding</span> <span m='2000940'>of</span> <span m='2002390'>topologically</span>
  <span m='2003070'>convex</span> <span m='2003470'>polyhedra,</span> <span m='2003730'>even</span>
  <span m='2004190'>orthogonal</span> <span m='2004770'>polyhedra,</span> <span m='2005310'>which</span>
  <span m='2005480'>is</span> <span m='2005590'>kind</span> <span m='2005770'>of</span>
  <span m='2005810'>nifty--</span> <span m='2008630'>from</span> <span m='2009100'>last</span>
  <span m='2009580'>year.</span> </p><p><span m='2012610'>If</span> <span m='2012750'>you</span>
  <span m='2012890'>actually</span> <span m='2013170'>want</span> <span m='2013340'>to</span>
  <span m='2013380'>unfold</span> <span m='2013840'>things--</span> <span m='2014080'>if</span>
  <span m='2014200'>you</span> <span m='2014320'>want</span> <span m='2014430'>to</span>
  <span m='2014490'>build</span> <span m='2014740'>things</span> <span m='2014960'>out</span>
  <span m='2015110'>of</span> <span m='2015170'>paper,</span> <span m='2016550'>the</span>
  <span m='2016890'>current</span> <span m='2017240'>best</span> <span m='2017580'>heuristic</span>
  <span m='2018010'>unfolder</span> <span m='2018120'>is</span> <span m='2018500'>called</span>
  <span m='2018760'>Pepakura.</span> <span m='2019430'>It's</span> <span m='2019700'>a</span>
  <span m='2019970'>free</span> <span m='2020340'>download</span> <span m='2020790'>online,</span>
  <span m='2021300'>probably</span> <span m='2021630'>Windows</span> <span m='2022030'>only.</span>
  <span m='2022800'>You</span> <span m='2022940'>can</span> <span m='2023080'>take</span>
  <span m='2023360'>some</span> <span m='2023600'>weird</span> <span m='2023770'>3D</span>
  <span m='2024110'>model.</span> <span m='2024840'>And</span> <span m='2025110'>it</span>
  <span m='2025220'>uses</span> <span m='2025520'>multiple</span> <span m='2025930'>pieces,</span>
  <span m='2026300'>in</span> <span m='2026410'>general,</span> <span m='2026810'>but</span>
  <span m='2027000'>you</span> <span m='2027400'>can</span> <span m='2027540'>add</span>
  <span m='2027740'>tabs</span> <span m='2028330'>and</span> <span m='2028490'>it's</span>
  <span m='2028910'>quite</span> <span m='2029200'>practical.</span> <span m='2030550'>And</span>
  <span m='2030720'>cut</span> <span m='2030910'>it</span> <span m='2031020'>out,</span>
  <span m='2031760'>either</span> <span m='2032050'>manually</span> <span m='2032630'>or</span>
  <span m='2032750'>with your</span> <span m='2033730'>computer</span> <span m='2034050'>controlled</span>
  <span m='2034370'>sign</span> <span m='2034630'>cutter or</span> <span m='2035020'>something</span>
  <span m='2035950'>and</span> <span m='2036100'>then</span> <span m='2036240'>fold</span>
  <span m='2036480'>up</span> <span m='2036650'>your</span> <span m='2037440'>pieces.</span>
  </p><p><span m='2040020'>When a</span> <span m='2040240'>one</span> <span m='2040410'>piece</span>
  <span m='2040710'>unfolding</span> <span m='2041130'>is</span> <span m='2041230'>possible,</span>
  <span m='2042270'>it</span> <span m='2042430'>will</span> <span m='2042650'>typically</span>
  <span m='2043110'>find</span> <span m='2043380'>it.</span> <span m='2043480'>But</span>
  <span m='2043620'>it's</span> <span m='2043770'>not</span> <span m='2043930'>guaranteed.</span>
  <span m='2045160'>I</span> <span m='2045290'>don't</span> <span m='2045460'>know</span>
  <span m='2045550'>exactly</span> <span m='2045960'>what</span> <span m='2046130'>algorithm</span>
  <span m='2046620'>it</span> <span m='2046920'>uses.</span> <span m='2047330'>But</span>
  <span m='2047530'>some</span> <span m='2047860'>combination</span> <span m='2048320'>of</span>
  <span m='2048380'>brute</span> <span m='2048590'>force</span> <span m='2048889'>and</span>
  <span m='2049719'>just</span> <span m='2050460'>cutting</span> <span m='2050770'>into</span>
  <span m='2050940'>multiple</span> <span m='2051270'>pieces</span> <span m='2051620'>when</span>
  <span m='2051770'>it</span> <span m='2051889'>fails.</span> </p><p><span m='2058620'>Next</span>
  <span m='2059050'>up,</span> <span m='2060219'>we</span> <span m='2060429'>have</span>
  <span m='2061020'>band</span> <span m='2061409'>unfolding.</span> <span m='2063320'>So</span>
  <span m='2063460'>I</span> <span m='2063510'>talked</span> <span m='2063860'>very</span>
  <span m='2064110'>briefly</span> <span m='2064449'>about</span> <span m='2064699'>band</span>
  <span m='2064909'>unfolding.</span> <span m='2065310'>I</span> <span m='2065350'>thought</span>
  <span m='2065530'>I'd</span> <span m='2065639'>show</span> <span m='2065770'>you</span>
  <span m='2065929'>some</span> <span m='2066719'>pictures</span> <span m='2067080'>about</span>
  <span m='2067429'>it.</span> </p><p><span m='2068550'>And</span> <span m='2068909'>so</span>
  <span m='2069030'>remember,</span> <span m='2069239'>we're</span> <span m='2069370'>talking</span>
  <span m='2069560'>about</span> <span m='2069750'>volcano</span> <span m='2070340'>unfoldings,</span>
  <span m='2070880'>which</span> <span m='2071080'>is</span> <span m='2071170'>when</span>
  <span m='2071280'>you</span> <span m='2071400'>cut</span> <span m='2071630'>along</span>
  <span m='2071960'>all</span> <span m='2072170'>the</span> <span m='2072330'>edges</span>
  <span m='2072830'>from</span> <span m='2073070'>a</span> <span m='2073170'>point</span>
  <span m='2073620'>or it's</span> <span m='2073879'>sort</span> <span m='2074139'>of</span>
  <span m='2074239'>in</span> <span m='2074370'>the</span> <span m='2074429'>vertical</span>
  <span m='2075300'>thing.</span> <span m='2075530'>Band</span> <span m='2075780'>unfolding</span>
  <span m='2076239'>was</span> <span m='2076400'>when</span> <span m='2077020'>you
  had</span> <span m='2077350'>some</span> <span m='2077480'>side</span> <span m='2077770'>faces,</span>
  <span m='2078150'>you</span> <span m='2078340'>kept</span> <span m='2078610'>those</span>
  <span m='2078830'>intact</span> <span m='2079400'>and</span> <span m='2079510'>cut</span>
  <span m='2080040'>everything</span> <span m='2080409'>else</span> <span m='2080620'>away.</span>
  <span m='2082250'>So</span> <span m='2082650'>what do I</span> <span m='2082770'>have
  to</span> <span m='2083219'>show</span> <span m='2083489'>here?</span> </p><p><span
  m='2084150'>This</span> <span m='2084250'>is</span> <span m='2084370'>an</span>
  <span m='2084440'>example</span> <span m='2084920'>of</span> <span m='2085150'>a</span>
  <span m='2085219'>band</span> <span m='2085510'>unfolding</span> <span m='2085980'>gone</span>
  <span m='2086270'>wrong--</span> <span m='2089420'>I</span> <span m='2089690'>guess.</span>
  <span m='2090489'>It's a</span> <span m='2090670'>little</span> <span m='2090909'>hard
  to</span> <span m='2090989'>see.</span> <span m='2092139'>This</span> <span m='2092380'>is,</span>
  <span m='2092600'>in</span> <span m='2092770'>general,</span> <span m='2093389'>a</span>
  <span m='2093489'>prismatoid.</span> <span m='2094170'>We</span> <span m='2094250'>had</span>
  <span m='2094420'>a</span> <span m='2094520'>top</span> <span m='2095320'>polygon,</span>
  <span m='2095909'>A,</span> <span m='2096210'>here,</span> <span m='2096510'>and</span>
  <span m='2096610'>then</span> <span m='2096770'>below</span> <span m='2097170'>it,</span>
  <span m='2097320'>this is</span> <span m='2097530'>polygon,</span> <span m='2098050'>B.</span>
  <span m='2098720'>We took</span> <span m='2098900'>the</span> <span m='2098980'>convex</span>
  <span m='2099440'>hull,</span> <span m='2099830'>which</span> <span m='2100060'>adds</span>
  <span m='2100350'>all</span> <span m='2100470'>these</span> <span m='2100650'>other</span>
  <span m='2100900'>edges.</span> <span m='2101910'>And</span> <span m='2102170'>this</span>
  <span m='2102320'>is</span> <span m='2102480'>an</span> <span m='2102620'>example</span>
  <span m='2103610'>of</span> <span m='2103810'>a</span> <span m='2103880'>bad</span>
  <span m='2104200'>unfolding</span> <span m='2104680'>of a</span> <span m='2104840'>primatoid.</span>
  </p><p><span m='2106630'>Here's</span> <span m='2106810'>an</span> <span m='2106850'>example</span>
  <span m='2107260'>of</span> <span m='2107370'>a</span> <span m='2107430'>bad--</span>
  <span m='2107990'>this</span> <span m='2108180'>is</span> <span m='2108290'>really</span>
  <span m='2108530'>a</span> <span m='2108580'>band</span> <span m='2108950'>unfolding</span>
  <span m='2109900'>that</span> <span m='2110270'>has</span> <span m='2110470'>gone</span>
  <span m='2110720'>wrong.</span> <span m='2111740'>So</span> <span m='2112580'>imagine</span>
  <span m='2113120'>here</span> <span m='2113300'>the</span> <span m='2113430'>top</span>
  <span m='2114000'>polygon</span> <span m='2114630'>is</span> <span m='2114800'>this</span>
  <span m='2114980'>triangle.</span> <span m='2115620'>Bottom</span> <span m='2115880'>polygon</span>
  <span m='2116390'>is</span> <span m='2116570'>this</span> <span m='2116760'>triangle.</span>
  <span m='2117270'>That</span> <span m='2117410'>nicely</span> <span m='2117750'>nest.</span>
  <span m='2118005'>It's a</span> <span m='2118260'>very</span> <span m='2118530'>easy</span>
  <span m='2118770'>example,</span> <span m='2119810'>seemingly.</span> </p><p><span
  m='2121180'>But</span> <span m='2121340'>for</span> <span m='2121460'>whatever</span>
  <span m='2121790'>reason,</span> <span m='2122050'>we</span> <span m='2122210'>also</span>
  <span m='2122520'>added</span> <span m='2122950'>this</span> <span m='2123160'>cut.</span>
  <span m='2123590'>And</span> <span m='2123810'>you</span> <span m='2123910'>can</span>
  <span m='2124050'>actually</span> <span m='2125050'>force</span> <span m='2125490'>that</span>
  <span m='2126030'>if</span> <span m='2126210'>I</span> <span m='2126530'>make</span>
  <span m='2126720'>this</span> <span m='2126920'>not</span> <span m='2127100'>quite--</span>
  <span m='2127680'>actually,</span> <span m='2127990'>maybe</span> <span m='2128350'>it's</span>
  <span m='2128640'>not</span> <span m='2128810'>quite</span> <span m='2129010'>a</span>
  <span m='2129070'>triangle.</span> <span m='2129490'>It's</span> <span m='2129620'>a</span>
  <span m='2129700'>quadrilateral.</span> <span m='2130470'>Yeah,</span> <span m='2130970'>and</span>
  <span m='2131100'>this</span> <span m='2131250'>is</span> <span m='2131350'>slightly</span>
  <span m='2131780'>a</span> <span m='2131870'>quadrilateral.</span> </p><p><span
  m='2132930'>So</span> <span m='2133110'>when</span> <span m='2133210'>you</span>
  <span m='2133300'>take</span> <span m='2133490'>a</span> <span m='2133550'>convex</span>
  <span m='2133910'>hull,</span> <span m='2134040'>you</span> <span m='2134160'>get</span>
  <span m='2134370'>that</span> <span m='2134550'>edge.</span> <span m='2135200'>If</span>
  <span m='2135400'>you</span> <span m='2135510'>cut</span> <span m='2135730'>along</span>
  <span m='2136020'>that</span> <span m='2136190'>edge</span> <span m='2136990'>and</span>
  <span m='2137130'>then</span> <span m='2137300'>cut</span> <span m='2137500'>along</span>
  <span m='2137760'>here and</span> <span m='2138040'>cut</span> <span m='2138200'>along</span>
  <span m='2138440'>here</span> <span m='2139590'>and</span> <span m='2139910'>do</span>
  <span m='2140170'>the</span> <span m='2140280'>band</span> <span m='2140540'>unfolding</span>
  <span m='2141010'>thing--</span> <span m='2141480'>we're</span> <span m='2141620'>not</span>
  <span m='2141760'>even</span> <span m='2141940'>drawing</span> <span m='2142270'>the</span>
  <span m='2142360'>bottom</span> <span m='2142630'>polygon</span> <span m='2143100'>here--</span>
  <span m='2143830'>just</span> <span m='2144080'>the</span> <span m='2144170'>band</span>
  <span m='2144520'>itself</span> <span m='2145570'>overlaps,</span> <span m='2148510'>which</span>
  <span m='2148690'>is</span> <span m='2148790'>annoying.</span> <span m='2149790'>Nonetheless--</span>
  <span m='2150630'>so</span> <span m='2150770'>this</span> <span m='2150920'>is</span>
  <span m='2151030'>an</span> <span m='2151110'>old</span> <span m='2151340'>example--</span>
  <span m='2153070'>but</span> <span m='2153400'>nonetheless,</span> <span m='2153910'>we</span>
  <span m='2154120'>proved</span> <span m='2154520'>that</span> <span m='2156810'>there's</span>
  <span m='2157080'>at</span> <span m='2157150'>least</span> <span m='2157400'>one</span>
  <span m='2157590'>place</span> <span m='2157890'>to</span> <span m='2157990'>cut</span>
  <span m='2158260'>the</span> <span m='2158340'>band--</span> <span m='2158630'>like</span>
  <span m='2158850'>here</span> <span m='2159020'>would</span> <span m='2159150'>work--</span>
  <span m='2159990'>that</span> <span m='2160110'>will</span> <span m='2160290'>avoid</span>
  <span m='2160630'>overlap.</span> </p><p><span m='2162920'>And</span> <span m='2163380'>this</span>
  <span m='2163610'>is</span> <span m='2163740'>some</span> <span m='2164880'>parts</span>
  <span m='2165200'>the</span> <span m='2165440'>proof.</span> <span m='2166310'>In</span>
  <span m='2166540'>general,</span> <span m='2167270'>here</span> <span m='2167470'>we're</span>
  <span m='2167550'>looking</span> <span m='2167840'>at</span> <span m='2167990'>the</span>
  <span m='2168170'>inner</span> <span m='2168440'>polygon.</span> <span m='2170370'>And</span>
  <span m='2170980'>we</span> <span m='2171160'>cut</span> <span m='2171420'>it</span>
  <span m='2171600'>somewhere.</span> <span m='2172770'>And</span> <span m='2172940'>then</span>
  <span m='2173050'>we</span> <span m='2173180'>argue</span> <span m='2173490'>about</span>
  <span m='2174440'>where</span> <span m='2174710'>that</span> <span m='2174950'>vertex</span>
  <span m='2175380'>goes</span> <span m='2175730'>if</span> <span m='2175940'>we</span>
  <span m='2176250'>open</span> <span m='2176560'>up</span> <span m='2176720'>all</span>
  <span m='2176870'>the</span> <span m='2177020'>angles,</span> <span m='2177430'>which</span>
  <span m='2177590'>is</span> <span m='2177680'>what</span> <span m='2177800'>happens</span>
  <span m='2178150'>when</span> <span m='2178250'>you</span> <span m='2178370'>squash</span>
  <span m='2178645'>it</span> <span m='2178920'>flat.</span> <span m='2180440'>And</span>
  <span m='2181290'>in</span> <span m='2181390'>particular,</span> <span m='2181770'>we</span>
  <span m='2181860'>argue</span> <span m='2182200'>this</span> <span m='2182410'>vertex</span>
  <span m='2183200'>must</span> <span m='2183460'>stay</span> <span m='2183720'>in</span>
  <span m='2184030'>the</span> <span m='2184110'>gray</span> <span m='2184380'>region,</span>
  <span m='2185700'>like</span> <span m='2186040'>in</span> <span m='2186150'>the</span>
  <span m='2186250'>picture</span> <span m='2186510'>on the</span> <span m='2186770'>right,</span>
  <span m='2187490'>so</span> <span m='2188260'>it</span> <span m='2188370'>can't</span>
  <span m='2188650'>go</span> <span m='2189220'>up</span> <span m='2189430'>here.</span>
  </p><p><span m='2190850'>And</span> <span m='2191040'>so</span> <span m='2191210'>in</span>
  <span m='2191300'>general,</span> <span m='2191600'>if</span> <span m='2191690'>you</span>
  <span m='2191820'>look</span> <span m='2192020'>at</span> <span m='2192380'>how</span>
  <span m='2192600'>these</span> <span m='2192760'>things</span> <span m='2192980'>unfold,</span>
  <span m='2193470'>if</span> <span m='2194000'>you're</span> <span m='2194120'>lucky,</span>
  <span m='2194790'>things</span> <span m='2194980'>will</span> <span m='2195050'>be</span>
  <span m='2195190'>convex</span> <span m='2195700'>when</span> <span m='2195790'>you</span>
  <span m='2195920'>open</span> <span m='2196170'>it.</span> <span m='2196280'>This</span>
  <span m='2196450'>is</span> <span m='2196600'>always</span> <span m='2196830'>going</span>
  <span m='2196950'>to</span> <span m='2197010'>be</span> <span m='2197130'>good.</span>
  <span m='2198130'>There's</span> <span m='2198470'>this</span> <span m='2198990'>weakly</span>
  <span m='2199480'>convex</span> <span m='2199950'>picture,</span> <span m='2200400'>where</span>
  <span m='2201010'>when</span> <span m='2201130'>you</span> <span m='2201250'>close</span>
  <span m='2202100'>the</span> <span m='2202270'>ends,</span> <span m='2202700'>it's</span>
  <span m='2202880'>not</span> <span m='2203070'>quite</span> <span m='2203240'>convex</span>
  <span m='2204620'>but</span> <span m='2204780'>only</span> <span m='2205070'>at</span>
  <span m='2205170'>one</span> <span m='2205370'>point.</span> <span m='2208840'>This</span>
  <span m='2209710'>is</span> <span m='2211000'>troublesome--</span> <span m='2212520'>sometimes</span>
  <span m='2213000'>this</span> <span m='2213150'>works,</span> <span m='2213420'>sometimes</span>
  <span m='2213800'>it</span> <span m='2213900'>doesn't.</span> <span m='2214510'>If</span>
  <span m='2214680'>you</span> <span m='2214800'>look</span> <span m='2214980'>at</span>
  <span m='2215060'>this</span> <span m='2215220'>example,</span> <span m='2216180'>I</span>
  <span m='2216290'>believe</span> <span m='2216550'>it</span> <span m='2216630'>is</span>
  <span m='2216750'>in</span> <span m='2216840'>the</span> <span m='2216940'>weakly</span>
  <span m='2217910'>convex</span> <span m='2218360'>category.</span> </p><p><span
  m='2218850'>I</span> <span m='2218920'>haven't</span> <span m='2219170'>told</span>
  <span m='2219350'>you</span> <span m='2219420'>the</span> <span m='2219590'>other</span>
  <span m='2219800'>one</span> <span m='2219990'>is</span> <span m='2220620'>a</span>
  <span m='2220690'>spiral.</span> <span m='2221790'>Here,</span> <span m='2222040'>if</span>
  <span m='2222220'>you</span> <span m='2222340'>draw</span> <span m='2222950'>a</span>
  <span m='2223460'>90</span> <span m='2223890'>degree</span> <span m='2224200'>angle</span>
  <span m='2224560'>from</span> <span m='2224900'>this</span> <span m='2225130'>last</span>
  <span m='2225480'>bar,</span> <span m='2226190'>then</span> <span m='2226590'>this</span>
  <span m='2226780'>guy is</span> <span m='2227000'>on</span> <span m='2227130'>wrong</span>
  <span m='2227530'>side</span> <span m='2227860'>of</span> <span m='2227970'>that</span>
  <span m='2228580'>90</span> <span m='2228810'>degree</span> <span m='2229100'>thing.</span>
  <span m='2231110'>This</span> <span m='2231980'>thing</span> <span m='2232170'>can't</span>
  <span m='2232490'>happen.</span> <span m='2233740'>So</span> <span m='2233790'>that's</span>
  <span m='2234740'>comforting.</span> <span m='2237190'>And</span> <span m='2237360'>it's</span>
  <span m='2237500'>related</span> <span m='2237880'>to</span> <span m='2237990'>this</span>
  <span m='2238560'>property.</span> </p><p><span m='2239460'>But</span> <span m='2239650'>these</span>
  <span m='2239860'>things</span> <span m='2240510'>can</span> <span m='2240760'>cause</span>
  <span m='2241000'>problems</span> <span m='2241390'>like</span> <span m='2241610'>in</span>
  <span m='2241700'>the</span> <span m='2241810'>previous</span> <span m='2242200'>picture.</span>
  <span m='2243220'>And</span> <span m='2243450'>so</span> <span m='2243600'>you</span>
  <span m='2243830'>have</span> <span m='2243960'>to</span> <span m='2244100'>argue</span>
  <span m='2244570'>that</span> <span m='2245050'>there</span> <span m='2245310'>is</span>
  <span m='2245410'>a</span> <span m='2245480'>place</span> <span m='2245760'>to</span>
  <span m='2245860'>cut</span> <span m='2246660'>where</span> <span m='2247690'>you</span>
  <span m='2247900'>don't</span> <span m='2248190'>get</span> <span m='2248370'>this</span>
  <span m='2248580'>or if</span> <span m='2249030'>when</span> <span m='2249180'>you</span>
  <span m='2249260'>get</span> <span m='2249470'>it,</span> <span m='2249600'>it's</span>
  <span m='2249750'>still</span> <span m='2250000'>OK.</span> <span m='2250590'>And</span>
  <span m='2251110'>that's</span> <span m='2251370'>a</span> <span m='2251420'>messy</span>
  <span m='2251730'>argument--</span> <span m='2252450'>a</span> <span m='2252530'>lot</span>
  <span m='2252680'>of</span> <span m='2252760'>case</span> <span m='2252990'>analysis</span>
  <span m='2253440'>I</span> <span m='2253490'>won't</span> <span m='2254110'>go</span>
  <span m='2254230'>through</span> <span m='2254440'>here.</span> <span m='2255160'>I</span>
  <span m='2255220'>think</span> <span m='2255430'>I</span> <span m='2255650'>have</span>
  <span m='2255830'>one</span> <span m='2256010'>picture</span> <span m='2256400'>of</span>
  <span m='2256600'>a</span> <span m='2257190'>nicely</span> <span m='2257630'>working</span>
  <span m='2257990'>example.</span> </p><p><span m='2259970'>This</span> <span m='2260460'>is,</span>
  <span m='2262110'>I</span> <span m='2262230'>guess,</span> <span m='2262410'>a</span>
  <span m='2262490'>general</span> <span m='2263690'>primatoid.</span> <span m='2265300'>But
  here,</span> <span m='2265520'>we</span> <span m='2265630'>have</span> <span m='2266110'>a</span>
  <span m='2266200'>nice</span> <span m='2267040'>cutting</span> <span m='2267360'>that</span>
  <span m='2267500'>works.</span> <span m='2268770'>The</span> <span m='2268930'>original</span>
  <span m='2269410'>question</span> <span m='2271550'>that</span> <span m='2271760'>someone</span>
  <span m='2272160'>here</span> <span m='2272480'>posed</span> <span m='2273290'>was,</span>
  <span m='2273510'>what</span> <span m='2273780'>about</span> <span m='2274320'>prismoids?</span>
  </p><p><span m='2274970'>So</span> <span m='2275710'>we</span> <span m='2275860'>know</span>
  <span m='2276000'>the</span> <span m='2276110'>band</span> <span m='2276530'>unfolds</span>
  <span m='2277040'>nicely.</span> <span m='2277730'>What</span> <span m='2277870'>we</span>
  <span m='2277980'>don't</span> <span m='2278220'>know</span> <span m='2278360'>is,</span>
  <span m='2278500'>can</span> <span m='2278700'>you</span> <span m='2278810'>attach</span>
  <span m='2279280'>the</span> <span m='2279400'>top</span> <span m='2279650'>polygon</span>
  <span m='2280170'>and</span> <span m='2280260'>the</span> <span m='2280320'>bottom</span>
  <span m='2280590'>polygons</span> <span m='2281060'>to</span> <span m='2281180'>the</span>
  <span m='2281280'>band</span> <span m='2281990'>and</span> <span m='2282160'>get</span>
  <span m='2282280'>an</span> <span m='2282380'>unfolding.</span> <span m='2283130'>We</span>
  <span m='2283260'>don't</span> <span m='2283440'>know,</span> <span m='2283590'>for</span>
  <span m='2283740'>example,</span> <span m='2284030'>whether</span> <span m='2284250'>all</span>
  <span m='2284400'>prismatoids</span> <span m='2285080'>have</span> <span m='2285400'>edge</span>
  <span m='2285570'>unfoldings,</span> <span m='2286860'>because</span> <span m='2287650'>we</span>
  <span m='2287740'>don't</span> <span m='2287890'>know</span> <span m='2287980'>how</span>
  <span m='2288110'>to</span> <span m='2288540'>place</span> <span m='2288780'>the</span>
  <span m='2288890'>top</span> <span m='2289140'>and bottom</span> <span m='2289500'>things.</span>
  <span m='2289780'>Probably</span> <span m='2290140'>possible</span> <span m='2290620'>but</span>
  <span m='2291260'>really</span> <span m='2291450'>hard</span> <span m='2291730'>to</span>
  <span m='2292570'>figure</span> <span m='2292840'>out</span> <span m='2292910'>where</span>
  <span m='2293010'>they</span> <span m='2293130'>would</span> <span m='2293280'>go.</span>
  </p><p><span m='2294820'>A</span> <span m='2294880'>simpler</span> <span m='2295230'>problem</span>
  <span m='2295600'>is</span> <span m='2295810'>prismoids--</span> <span m='2298335'>which</span>
  <span m='2298710'>this</span> <span m='2299480'>might</span> <span m='2299730'>actually</span>
  <span m='2300150'>be</span> <span m='2300280'>a</span> <span m='2300340'>prismoid.</span>
  <span m='2300880'>If</span> <span m='2301110'>you</span> <span m='2301250'>know</span>
  <span m='2301450'>that</span> <span m='2301570'>all</span> <span m='2301740'>of</span>
  <span m='2301810'>these</span> <span m='2301980'>edges</span> <span m='2302260'>are</span>
  <span m='2302370'>parallel</span> <span m='2303500'>initially--</span> <span m='2304670'>so</span>
  <span m='2304910'>it's a</span> <span m='2305180'>very</span> <span m='2305380'>nice</span>
  <span m='2305970'>situation--</span> <span m='2307990'>then</span> <span m='2309240'>that's
  a</span> <span m='2309640'>more</span> <span m='2309850'>special</span> <span m='2310170'>case</span>
  <span m='2310390'>from</span> <span m='2310500'>prismatoids--</span> <span m='2311170'>then</span>
  <span m='2311410'>maybe</span> <span m='2311650'>you</span> <span m='2311770'>could</span>
  <span m='2311920'>attach</span> <span m='2312320'>the</span> <span m='2312520'>interface</span>
  <span m='2312990'>and</span> <span m='2313100'>outerface.</span> <span m='2313590'>We</span>
  <span m='2313690'>don't</span> <span m='2314020'>know.</span> </p><p><span m='2315270'>We</span>
  <span m='2315420'>know</span> <span m='2315620'>volcano</span> <span m='2316080'>unfoldings</span>
  <span m='2316470'>work</span> <span m='2316620'>for</span> <span m='2316730'>prismoids.</span>
  <span m='2317770'>We</span> <span m='2317890'>don't</span> <span m='2318010'>know</span>
  <span m='2318130'>about</span> <span m='2318380'>band</span> <span m='2318650'>unfoldings.</span>
  <span m='2319270'>That</span> <span m='2319480'>could</span> <span m='2319630'>be</span>
  <span m='2319780'>an</span> <span m='2319850'>interesting</span> <span m='2320150'>open</span>
  <span m='2320380'>problem</span> <span m='2320620'>to</span> <span m='2320710'>work</span>
  <span m='2320890'>on.</span> <span m='2321960'>Maybe</span> <span m='2322280'>it's</span>
  <span m='2322690'>easy</span> <span m='2323150'>with</span> <span m='2323350'>prismoids.</span>
  <span m='2323890'>They</span> <span m='2324000'>seem</span> <span m='2324400'>pretty</span>
  <span m='2324740'>clean,</span> <span m='2325220'>but</span> <span m='2325910'>I</span>
  <span m='2325980'>don't</span> <span m='2326110'>know</span> <span m='2326210'>for</span>
  <span m='2326350'>sure.</span> </p><p><span m='2328330'>Oh,</span> <span m='2328500'>another</span>
  <span m='2328790'>fun</span> <span m='2329030'>thing,</span> <span m='2329490'>which</span>
  <span m='2329710'>relates</span> <span m='2330030'>to</span> <span m='2330130'>our</span>
  <span m='2330210'>next</span> <span m='2330500'>topic,</span> <span m='2330960'>is</span>
  <span m='2331170'>that</span> <span m='2332590'>if</span> <span m='2332770'>you</span>
  <span m='2332850'>just</span> <span m='2333070'>unfold</span> <span m='2333400'>the</span>
  <span m='2333460'>band</span> <span m='2333820'>part,</span> <span m='2335090'>you</span>
  <span m='2335290'>can</span> <span m='2335420'>do</span> <span m='2335590'>it</span>
  <span m='2335730'>by</span> <span m='2335890'>continuous</span> <span m='2336560'>blooming--</span>
  <span m='2338210'>meaning</span> <span m='2338560'>there's</span> <span m='2338720'>a</span>
  <span m='2338790'>continuous</span> <span m='2339330'>motion</span> <span m='2341000'>from</span>
  <span m='2341210'>the</span> <span m='2341290'>folded</span> <span m='2341630'>thing</span>
  <span m='2341900'>to</span> <span m='2341990'>the</span> <span m='2342180'>unfolded</span>
  <span m='2342560'>thing,</span> <span m='2342720'>or</span> <span m='2342790'>vice</span>
  <span m='2343070'>versa.</span> <span m='2344130'>And</span> <span m='2344390'>the</span>
  <span m='2344670'>easy</span> <span m='2344930'>way</span> <span m='2345090'>to</span>
  <span m='2345180'>see</span> <span m='2345390'>that--</span> <span m='2345670'>you</span>
  <span m='2345780'>kind</span> <span m='2345990'>of</span> <span m='2346070'>get</span>
  <span m='2346220'>a</span> <span m='2346450'>sense</span> <span m='2346750'>from</span>
  <span m='2346820'>this</span> <span m='2347020'>picture--</span> <span m='2348820'>in</span>
  <span m='2348950'>general,</span> <span m='2349330'>when you</span> <span m='2349450'>squash</span>
  <span m='2349820'>it</span> <span m='2349860'>all</span> <span m='2350020'>the</span>
  <span m='2350090'>way</span> <span m='2350230'>flat,</span> <span m='2350600'>it</span>
  <span m='2350770'>opens.</span> <span m='2352190'>Like</span> <span m='2352400'>this</span>
  <span m='2352560'>initial</span> <span m='2352910'>grey</span> <span m='2353160'>diagram</span>
  <span m='2353650'>is</span> <span m='2353770'>a</span> <span m='2353830'>projection</span>
  <span m='2355350'>of the</span> <span m='2355490'>original</span> <span m='2355840'>thing.</span>
  </p><p><span m='2356510'>If</span> <span m='2356710'>you--</span> <span m='2357290'>instead</span>
  <span m='2357610'>of</span> <span m='2357700'>opening it</span> <span m='2358060'>all</span>
  <span m='2358310'>the</span> <span m='2358390'>way--</span> <span m='2358670'>if</span>
  <span m='2358720'>you</span> <span m='2358980'>kind</span> <span m='2359180'>of</span>
  <span m='2359270'>squish</span> <span m='2359970'>it</span> <span m='2360110'>from</span>
  <span m='2360260'>the</span> <span m='2360380'>top</span> <span m='2360750'>and</span>
  <span m='2360840'>just</span> <span m='2360990'>keep</span> <span m='2361180'>lowering</span>
  <span m='2361690'>that</span> <span m='2361910'>top</span> <span m='2362160'>face,</span>
  <span m='2362480'>at</span> <span m='2362630'>the</span> <span m='2362840'>end,</span>
  <span m='2363310'>it's</span> <span m='2363520'>fully</span> <span m='2363840'>in</span>
  <span m='2363940'>the</span> <span m='2364030'>plane.</span> <span m='2365080'>But</span>
  <span m='2365220'>in</span> <span m='2365330'>the</span> <span m='2365410'>middle,</span>
  <span m='2365990'>you</span> <span m='2366130'>have a</span> <span m='2366340'>motion.</span>
  <span m='2367050'>And</span> <span m='2367830'>by</span> <span m='2368020'>the</span>
  <span m='2368120'>same</span> <span m='2368390'>argument,</span> <span m='2369220'>at</span>
  <span m='2369340'>all</span> <span m='2369520'>times,</span> <span m='2369800'>you
  are</span> <span m='2369980'>non-self</span> <span m='2370420'>intersecting.</span>
  <span m='2371030'>So</span> <span m='2371190'>that</span> <span m='2371310'>actually</span>
  <span m='2371560'>gives</span> <span m='2371750'>you</span> <span m='2371930'>a</span>
  <span m='2372000'>continuous</span> <span m='2372520'>blooming</span> <span m='2373350'>of</span>
  <span m='2373530'>the</span> <span m='2373600'>band</span> <span m='2374500'>of</span>
  <span m='2374660'>a</span> <span m='2374710'>prismatoid,</span> <span m='2376598'>which
  is kind of</span> <span m='2377000'>cool.</span> </p><p><span m='2379890'>So</span>
  <span m='2380390'>the</span> <span m='2380480'>next</span> <span m='2380730'>topic</span>
  <span m='2381100'>is</span> <span m='2381300'>blooming.</span> <span m='2382690'>This</span>
  <span m='2382840'>is</span> <span m='2382940'>the</span> <span m='2383030'>last</span>
  <span m='2383370'>topic</span> <span m='2383800'>also.</span> <span m='2384350'>A</span>
  <span m='2384800'>bunch</span> <span m='2385040'>of</span> <span m='2385140'>people</span>
  <span m='2385310'>asked</span> <span m='2385480'>about</span> <span m='2385690'>continuous</span>
  <span m='2386080'>booming</span> <span m='2386400'>and so</span> <span m='2386740'>the</span>
  <span m='2386890'>obvious</span> <span m='2387260'>one</span> <span m='2388220'>to</span>
  <span m='2388380'>learn</span> <span m='2388550'>more</span> <span m='2388730'>about.</span>
  <span m='2389080'>So</span> <span m='2389190'>I</span> <span m='2389270'>have</span>
  <span m='2389500'>some</span> <span m='2390430'>algorithms</span> <span m='2391210'>and</span>
  <span m='2392390'>examples</span> <span m='2393050'>for</span> <span m='2393260'>you.</span>
  </p><p><span m='2395530'>This</span> <span m='2395720'>is</span> <span m='2395810'>the</span>
  <span m='2395910'>paper--</span> <span m='2397160'>a bunch</span> <span m='2397380'>of</span>
  <span m='2397490'>authors,</span> <span m='2397840'>"Continuous</span> <span m='2398290'>Blooming</span>
  <span m='2398580'>of</span> <span m='2398680'>Convex</span> <span m='2399060'>Polyhedra."</span>
  <span m='2400030'>This problem was</span> <span m='2400450'>posed</span> <span m='2400940'>by</span>
  <span m='2401190'>Connolly,</span> <span m='2401880'>I</span> <span m='2401930'>believe,</span>
  <span m='2403142'>a</span> <span m='2403520'>bunch</span> <span m='2403820'>of</span>
  <span m='2404000'>years</span> <span m='2404380'>prior.</span> <span m='2410380'>It's
  still</span> <span m='2410650'>not</span> <span m='2410830'>known</span> <span m='2411100'>whether</span>
  <span m='2411660'>every</span> <span m='2412090'>unfolding</span> <span m='2412940'>continuously</span>
  <span m='2413580'>blooms.</span> <span m='2414700'>It</span> <span m='2414830'>could</span>
  <span m='2415030'>be</span> <span m='2415310'>that</span> <span m='2415610'>every</span>
  <span m='2416020'>unfolding--</span> <span m='2417940'>every</span> <span m='2418180'>non-overlapping</span>
  <span m='2418920'>unfolding</span> <span m='2419800'>of</span> <span m='2419920'>a</span>
  <span m='2420000'>convex</span> <span m='2420420'>polyhedron--</span> <span m='2421020'>continuously</span>
  <span m='2421630'>blooms.</span> </p><p><span m='2422160'>I</span> <span m='2422280'>would</span>
  <span m='2422430'>guess</span> <span m='2422610'>the</span> <span m='2422690'>answer</span>
  <span m='2422930'>is,</span> <span m='2423290'>it</span> <span m='2423430'>doesn't</span>
  <span m='2424590'>but</span> <span m='2424750'>it's</span> <span m='2424900'>plausible.</span>
  <span m='2425530'>That</span> <span m='2425630'>was</span> <span m='2425750'>the</span>
  <span m='2425840'>original</span> <span m='2426170'>question.</span> <span m='2427750'>What</span>
  <span m='2428020'>we</span> <span m='2428180'>found</span> <span m='2428550'>are</span>
  <span m='2428910'>two</span> <span m='2429090'>different</span> <span m='2429390'>ways</span>
  <span m='2430000'>to</span> <span m='2430360'>continuously</span> <span m='2431030'>bloom</span>
  <span m='2431320'>any</span> <span m='2431590'>convex</span> <span m='2432050'>polyhedron,</span>
  <span m='2433060'>but</span> <span m='2433200'>we</span> <span m='2433380'>choose</span>
  <span m='2433650'>the</span> <span m='2433770'>unfolding.</span> </p><p><span m='2434900'>So</span>
  <span m='2435040'>we</span> <span m='2435170'>have</span> <span m='2435260'>a</span>
  <span m='2435340'>couple</span> <span m='2435690'>different</span> <span m='2435990'>strategies</span>
  <span m='2436450'>for</span> <span m='2436560'>choosing</span> <span m='2436870'>unfoldings</span>
  <span m='2437205'>that</span> <span m='2437540'>do</span> <span m='2437700'>continuously</span>
  <span m='2438270'>bloom.</span> <span m='2438920'>Whether</span> <span m='2439230'>every</span>
  <span m='2439620'>unfolding</span> <span m='2440410'>continuously</span> <span m='2440900'>blooms,</span>
  <span m='2441150'>I don't</span> <span m='2441380'>know.</span> <span m='2442130'>There
  are</span> <span m='2442350'>definitely</span> <span m='2442640'>unfoldings</span>
  <span m='2443140'>of</span> <span m='2443240'>non-convex</span> <span m='2443940'>polyhedra</span>
  <span m='2444490'>that</span> <span m='2444730'>do</span> <span m='2444870'>not</span>
  <span m='2445370'>continuously</span> <span m='2445940'>bloom,</span> <span m='2447050'>based</span>
  <span m='2447390'>on</span> <span m='2447550'>knitting</span> <span m='2447810'>needles</span>
  <span m='2448130'>type</span> <span m='2448390'>examples,</span> <span m='2449190'>based</span>
  <span m='2449250'>on</span> <span m='2449420'>bad</span> <span m='2449660'>linkage</span>
  <span m='2449980'>stuff.</span> <span m='2450880'>But</span> <span m='2451150'>for</span>
  <span m='2451270'>convex</span> <span m='2451640'>polyhedra,</span> <span m='2453400'>I'm
  not sure.</span> </p><p><span m='2456930'>So</span> <span m='2457360'>what</span>
  <span m='2457520'>do</span> <span m='2457590'>we</span> <span m='2457690'>have</span>
  <span m='2457930'>first?</span> <span m='2458425'>First</span> <span m='2458920'>strategy</span>
  <span m='2460650'>actually</span> <span m='2460960'>starts</span> <span m='2461330'>from</span>
  <span m='2461550'>any</span> <span m='2461820'>unfolding</span> <span m='2462270'>you</span>
  <span m='2462380'>have.</span> <span m='2462800'>So</span> <span m='2463140'>we</span>
  <span m='2463290'>start</span> <span m='2463670'>here</span> <span m='2464030'>from</span>
  <span m='2464200'>the</span> <span m='2464320'>cross</span> <span m='2464640'>unfolding</span>
  <span m='2465050'>of</span> <span m='2465140'>the</span> <span m='2465230'>cube.</span>
  <span m='2466370'>And</span> <span m='2466570'>then</span> <span m='2466680'>it</span>
  <span m='2466780'>refines</span> <span m='2467450'>it.</span> <span m='2467920'>So
  a</span> <span m='2468300'>similar</span> <span m='2468670'>strategy</span> <span
  m='2469130'>to</span> <span m='2469260'>hinged</span> <span m='2469640'>dissection,</span>
  <span m='2469990'>although</span> <span m='2470280'>I</span> <span m='2470390'>think</span>
  <span m='2470590'>this</span> <span m='2470760'>was</span> <span m='2470900'>done</span>
  <span m='2471130'>before</span> <span m='2471610'>hinged</span> <span m='2471860'>dissection.</span>
  </p><p><span m='2474130'>Let's</span> <span m='2474370'>take</span> <span m='2474660'>some</span>
  <span m='2475240'>hinged</span> <span m='2475670'>structure,</span> <span m='2476670'>add</span>
  <span m='2476950'>extra</span> <span m='2477290'>cuts</span> <span m='2477590'>and</span>
  <span m='2477680'>extra</span> <span m='2478090'>hinges.</span> <span m='2479060'>In</span>
  <span m='2479120'>this</span> <span m='2479270'>case,</span> <span m='2479590'>I
  mean the</span> <span m='2479830'>hinges</span> <span m='2480170'>are</span> <span
  m='2480250'>going</span> <span m='2480360'>to</span> <span m='2480400'>be</span>
  <span m='2480510'>the</span> <span m='2480600'>same.</span> <span m='2481040'>It's</span>
  <span m='2481050'>just</span> <span m='2481240'>adding</span> <span m='2481540'>extra</span>
  <span m='2481820'>cuts.</span> <span m='2482770'>So</span> <span m='2482900'>we're</span>
  <span m='2483000'>going</span> <span m='2483090'>to</span> <span m='2483160'>cut</span>
  <span m='2483360'>along</span> <span m='2483670'>the</span> <span m='2483800'>red</span>
  <span m='2484110'>thing</span> <span m='2485660'>and</span> <span m='2485820'>also</span>
  <span m='2486030'>this</span> <span m='2486200'>red</span> <span m='2486410'>dashed</span>
  <span m='2486720'>line.</span> </p><p><span m='2487160'>The</span> <span m='2487260'>red</span>
  <span m='2487470'>thing</span> <span m='2487730'>is</span> <span m='2488040'>a</span>
  <span m='2488100'>spanning</span> <span m='2488630'>tree</span> <span m='2489940'>of</span>
  <span m='2490230'>the--</span> <span m='2491990'>or it's really</span> <span m='2492430'>the</span>
  <span m='2492550'>dual</span> <span m='2492790'>graph.</span> <span m='2493780'>So</span>
  <span m='2494040'>we</span> <span m='2494140'>have,</span> <span m='2494880'>the</span>
  <span m='2494990'>dual</span> <span m='2495180'>graph</span> <span m='2495450'>is</span>
  <span m='2495560'>you</span> <span m='2495640'>have</span> <span m='2495860'>a</span>
  <span m='2495960'>vertex</span> <span m='2496400'>for</span> <span m='2496520'>every</span>
  <span m='2496780'>face.</span> <span m='2497580'>You</span> <span m='2497670'>connect</span>
  <span m='2497920'>them</span> <span m='2498070'>together</span> <span m='2498470'>if
  they</span> <span m='2498560'>share</span> <span m='2498790'>an</span> <span m='2498870'>edge.</span>
  <span m='2499650'>In</span> <span m='2499710'>this</span> <span m='2499870'>case,</span>
  <span m='2501020'>when</span> <span m='2501170'>they</span> <span m='2501260'>share</span>
  <span m='2501460'>an</span> <span m='2501540'>edge,</span> <span m='2501710'>we're</span>
  <span m='2501840'>going</span> <span m='2501940'>to</span> <span m='2502030'>cut</span>
  <span m='2502390'>along</span> <span m='2502690'>there.</span> </p><p><span m='2503070'>So</span>
  <span m='2503110'>we</span> <span m='2503180'>cut</span> <span m='2503360'>along</span>
  <span m='2503660'>all</span> <span m='2503780'>this</span> <span m='2503940'>red</span>
  <span m='2504150'>stuff.</span> <span m='2504990'>And</span> <span m='2505160'>the</span>
  <span m='2505250'>cool</span> <span m='2505450'>thing</span> <span m='2505650'>is,</span>
  <span m='2505810'>if</span> <span m='2505920'>you</span> <span m='2506040'>walk</span>
  <span m='2506530'>around</span> <span m='2507060'>the</span> <span m='2507190'>red</span>
  <span m='2507690'>structure,</span> <span m='2508760'>you</span> <span m='2508930'>get</span>
  <span m='2509210'>a</span> <span m='2509300'>cycle--</span> <span m='2510290'>a</span>
  <span m='2510400'>Hamiltonian</span> <span m='2510970'>cycle</span> <span m='2511350'>that</span>
  <span m='2511420'>visits</span> <span m='2511800'>all</span> <span m='2511950'>the</span>
  <span m='2512010'>faces</span> <span m='2512400'>exactly</span> <span m='2512810'>once.</span>
  <span m='2513520'>We</span> <span m='2513650'>want</span> <span m='2513810'>to</span>
  <span m='2513870'>path,</span> <span m='2514230'>not</span> <span m='2514380'>a</span>
  <span m='2514430'>cycle,</span> <span m='2514790'>so</span> <span m='2514940'>we</span>
  <span m='2515080'>add</span> <span m='2515290'>one</span> <span m='2515460'>more</span>
  <span m='2515670'>cut.</span> </p><p><span m='2517100'>So</span> <span m='2517340'>then</span>
  <span m='2517540'>this</span> <span m='2517700'>blue</span> <span m='2518020'>dash</span>
  <span m='2518400'>thing</span> <span m='2518700'>is</span> <span m='2518850'>a</span>
  <span m='2518920'>path.</span> <span m='2520230'>And</span> <span m='2520380'>the</span>
  <span m='2520450'>claim</span> <span m='2520760'>is,</span> <span m='2521060'>any</span>
  <span m='2521940'>path</span> <span m='2522280'>shaped</span> <span m='2522720'>unfolding--</span>
  <span m='2523890'>where</span> <span m='2524010'>the</span> <span m='2524120'>faces</span>
  <span m='2524490'>are</span> <span m='2524590'>connected</span> <span m='2524850'>together</span>
  <span m='2525220'>in</span> <span m='2525290'>a</span> <span m='2525340'>path--</span>
  <span m='2525980'>can</span> <span m='2526250'>be</span> <span m='2526400'>continuously</span>
  <span m='2527000'>bloomed.</span> <span m='2527900'>How</span> <span m='2528070'>do</span>
  <span m='2528130'>you</span> <span m='2528240'>do</span> <span m='2528390'>it?</span>
  <span m='2529470'>Roll.</span> </p><p><span m='2533210'>So</span> <span m='2534000'>it's</span>
  <span m='2534220'>a</span> <span m='2534270'>little</span> <span m='2534520'>easier</span>
  <span m='2534890'>for</span> <span m='2535040'>me</span> <span m='2535260'>to</span>
  <span m='2535390'>think</span> <span m='2535570'>about</span> <span m='2535960'>unrolling</span>
  <span m='2536560'>rather</span> <span m='2536800'>than</span> <span m='2536980'>rolling,</span>
  <span m='2537420'>but</span> <span m='2537640'>they're</span> <span m='2537790'>the</span>
  <span m='2537910'>same</span> <span m='2538160'>thing.</span> <span m='2538410'>So</span>
  <span m='2538640'>imagine,</span> <span m='2538970'>you</span> <span m='2539090'>start</span>
  <span m='2539410'>with</span> <span m='2539500'>the</span> <span m='2539610'>cube.</span>
  <span m='2541580'>And</span> <span m='2541740'>then</span> <span m='2541850'>you</span>
  <span m='2541970'>just</span> <span m='2542230'>roll</span> <span m='2542670'>it--</span>
  <span m='2543020'>you</span> <span m='2543220'>unroll</span> <span m='2544020'>one</span>
  <span m='2544380'>face</span> <span m='2544680'>at</span> <span m='2544760'>a</span>
  <span m='2544860'>time.</span> </p><p><span m='2545580'>So</span> <span m='2545790'>initially,</span>
  <span m='2546280'>there</span> <span m='2546410'>was</span> <span m='2546560'>a</span>
  <span m='2546630'>90</span> <span m='2546920'>degree</span> <span m='2547190'>fold</span>
  <span m='2547490'>angle</span> <span m='2547750'>here.</span> <span m='2548490'>Just</span>
  <span m='2548740'>unroll</span> <span m='2549410'>it,</span> <span m='2549650'>so</span>
  <span m='2549850'>that</span> <span m='2550010'>now</span> <span m='2550210'>they're</span>
  <span m='2550540'>in</span> <span m='2550680'>the</span> <span m='2550770'>same</span>
  <span m='2551000'>plane.</span> <span m='2551960'>And</span> <span m='2552140'>there</span>
  <span m='2552250'>was</span> <span m='2552390'>initially a</span> <span m='2552760'>90</span>
  <span m='2553010'>degree</span> <span m='2553240'>angle</span> <span m='2553470'>here.</span>
  <span m='2553770'>Unroll</span> <span m='2554150'>that.</span> </p><p><span m='2555200'>After</span>
  <span m='2555740'>three</span> <span m='2556060'>steps,</span> <span m='2556750'>I</span>
  <span m='2556800'>think--</span> <span m='2557740'>this</span> <span m='2557940'>guy's</span>
  <span m='2558160'>been</span> <span m='2558310'>flattened,</span> <span m='2558850'>two,</span>
  <span m='2559710'>three--</span> <span m='2560660'>we</span> <span m='2560780'>have</span>
  <span m='2560940'>this</span> <span m='2561090'>picture.</span> <span m='2562850'>In</span>
  <span m='2563070'>general,</span> <span m='2563810'>I</span> <span m='2563910'>would</span>
  <span m='2563930'>normally</span> <span m='2564260'>draw it</span> <span m='2564690'>rotated,</span>
  <span m='2564960'>so</span> <span m='2565230'>that</span> <span m='2566510'>the</span>
  <span m='2566750'>unfolded</span> <span m='2567280'>part</span> <span m='2567930'>lives</span>
  <span m='2568200'>in</span> <span m='2568310'>the floor</span> <span m='2568710'>of</span>
  <span m='2568830'>xy-plane.</span> <span m='2570140'>And</span> <span m='2570310'>the</span>
  <span m='2570380'>polyhedron</span> <span m='2571110'>lives</span> <span m='2571390'>in</span>
  <span m='2571720'>z</span> <span m='2572000'>greater</span> <span m='2572240'>than
  or</span> <span m='2572280'>equal</span> <span m='2572510'>to</span> <span m='2572560'>zero,</span>
  <span m='2572930'>so</span> <span m='2573090'>lives</span> <span m='2573290'>above</span>
  <span m='2573580'>that</span> <span m='2573770'>plane.</span> </p><p><span m='2575340'>What</span>
  <span m='2575530'>you know</span> <span m='2575785'>at</span> <span m='2576040'>all</span>
  <span m='2576230'>times</span> <span m='2576740'>is</span> <span m='2576920'>that</span>
  <span m='2577090'>the</span> <span m='2577230'>unfolded</span> <span m='2577720'>part</span>
  <span m='2578800'>is</span> <span m='2579010'>a</span> <span m='2579080'>subset</span>
  <span m='2579600'>of</span> <span m='2579690'>the</span> <span m='2579810'>unfolding.</span>
  <span m='2580910'>It's</span> <span m='2581000'>a</span> <span m='2581050'>subset</span>
  <span m='2581450'>of</span> <span m='2581570'>this</span> <span m='2581750'>picture.</span>
  <span m='2583010'>So</span> <span m='2583260'>it</span> <span m='2583420'>doesn't</span>
  <span m='2583690'>overlap</span> <span m='2584120'>itself.</span> <span m='2584970'>If</span>
  <span m='2585120'>you</span> <span m='2585210'>start</span> <span m='2585470'>with</span>
  <span m='2585610'>a</span> <span m='2585680'>non-overlapping</span> <span m='2586360'>unfolding,</span>
  <span m='2586910'>you</span> <span m='2587410'>do</span> <span m='2587530'>this</span>
  <span m='2587730'>cutting.</span> <span m='2589330'>And</span> <span m='2589520'>then</span>
  <span m='2589650'>you</span> <span m='2589730'>just</span> <span m='2589930'>take</span>
  <span m='2590150'>some</span> <span m='2590440'>subset</span> <span m='2590870'>of</span>
  <span m='2590930'>the</span> <span m='2591000'>faces--</span> <span m='2591390'>a</span>
  <span m='2591480'>prefix</span> <span m='2592030'>of</span> <span m='2592140'>the</span>
  <span m='2592220'>path--</span> <span m='2593330'>then</span> <span m='2593460'>that</span>
  <span m='2593610'>will</span> <span m='2593710'>be</span> <span m='2593830'>a</span>
  <span m='2593880'>non-overlapping</span> <span m='2594580'>thing.</span> </p><p><span
  m='2595430'>On</span> <span m='2595530'>the</span> <span m='2595640'>other</span>
  <span m='2595770'>hand,</span> <span m='2596060'>the</span> <span m='2596160'>polyhedron</span>
  <span m='2596750'>that</span> <span m='2596870'>remains,</span> <span m='2597390'>we</span>
  <span m='2597530'>haven't</span> <span m='2597930'>touched.</span> <span m='2598350'>I
  mean,</span> <span m='2598490'>it's</span> <span m='2598660'>rotating.</span> <span
  m='2599940'>You</span> <span m='2600240'>have</span> <span m='2600370'>to</span>
  <span m='2600470'>make</span> <span m='2600640'>sure</span> <span m='2600810'>it</span>
  <span m='2600910'>stays</span> <span m='2601230'>above</span> <span m='2601520'>the</span>
  <span m='2601600'>plane</span> <span m='2601940'>here.</span> <span m='2602680'>But</span>
  <span m='2603630'>it</span> <span m='2603800'>is</span> <span m='2604030'>just</span>
  <span m='2604280'>a</span> <span m='2604340'>subset</span> <span m='2604830'>of
  the</span> <span m='2604960'>faces</span> <span m='2605370'>of</span> <span m='2605530'>the</span>
  <span m='2605620'>cube.</span> </p><p><span m='2606390'>The</span> <span m='2606400'>cube</span>
  <span m='2606670'>is</span> <span m='2606770'>also</span> <span m='2607030'>not</span>
  <span m='2607290'>self</span> <span m='2607490'>intersecting.</span> <span m='2608130'>So
  any</span> <span m='2608420'>subset</span> <span m='2608820'>is</span> <span m='2608940'>not</span>
  <span m='2609100'>self</span> <span m='2609280'>intersecting.</span> <span m='2609780'>So</span>
  <span m='2609960'>this</span> <span m='2610210'>thing</span> <span m='2610430'>doesn't</span>
  <span m='2610680'>self</span> <span m='2610870'>intersect.</span> <span m='2611710'>This</span>
  <span m='2611890'>thing</span> <span m='2612050'>doesn't</span> <span m='2612300'>self</span>
  <span m='2612510'>intersect.</span> </p><p><span m='2614930'>Potentially,</span>
  <span m='2616280'>this</span> <span m='2616560'>cube</span> <span m='2616970'>will</span>
  <span m='2617190'>be</span> <span m='2617410'>resting</span> <span m='2618130'>on</span>
  <span m='2618490'>like</span> <span m='2618710'>f1</span> <span m='2619210'>here.</span>
  <span m='2619700'>It's</span> <span m='2619900'>possible</span> <span m='2620430'>for</span>
  <span m='2620530'>this</span> <span m='2620700'>thing</span> <span m='2620850'>to</span>
  <span m='2620930'>unroll</span> <span m='2621810'>and</span> <span m='2621980'>just</span>
  <span m='2622300'>touch</span> <span m='2623470'>the</span> <span m='2623590'>plane--</span>
  <span m='2624610'>xy-plane.</span> <span m='2626910'>But</span> <span m='2626970'>it</span>
  <span m='2627050'>won't</span> <span m='2627280'>penetrate</span> <span m='2627540'>it,</span>
  <span m='2628510'>just</span> <span m='2628700'>because</span> <span m='2629010'>this</span>
  <span m='2629160'>thing's</span> <span m='2629370'>convex</span> <span m='2629790'>and</span>
  <span m='2630210'>this is a</span> <span m='2630550'>plane.</span> <span m='2631220'>So</span>
  <span m='2631330'>you</span> <span m='2631390'>can</span> <span m='2631490'>always</span>
  <span m='2631660'>keep</span> <span m='2631870'>this</span> <span m='2632030'>thing</span>
  <span m='2632200'>above--</span> <span m='2632930'>keep</span> <span m='2633150'>a
  convex</span> <span m='2633530'>shape</span> <span m='2634200'>above--</span> <span
  m='2635260'>or</span> <span m='2635390'>what</span> <span m='2635590'>was</span>
  <span m='2635840'>a</span> <span m='2635900'>convex</span> <span m='2636310'>shape--</span>
  <span m='2636650'>a</span> <span m='2636770'>partial</span> <span m='2637130'>version</span>
  <span m='2637410'>of</span> <span m='2637500'>a</span> <span m='2637540'>convex  shape--</span>
  <span m='2638040'>above</span> <span m='2638230'>a</span> <span m='2638400'>plane.</span>
  </p><p><span m='2640000'>But</span> <span m='2640450'>they</span> <span m='2640570'>can</span>
  <span m='2641000'>be</span> <span m='2641120'>potentially</span> <span m='2641610'>touching,</span>
  <span m='2642040'>even</span> <span m='2642260'>along</span> <span m='2643070'>two</span>
  <span m='2643280'>dimensional</span> <span m='2643740'>surfaces.</span> <span m='2644900'>So</span>
  <span m='2645160'>if</span> <span m='2645410'>you</span> <span m='2645590'>allow</span>
  <span m='2645790'>touching,</span> <span m='2646750'>this</span> <span m='2646960'>is</span>
  <span m='2647080'>the</span> <span m='2647220'>path</span> <span m='2647570'>unroll</span>
  <span m='2647930'>algorithm.</span> <span m='2648720'>It</span> <span m='2648870'>works</span>
  <span m='2649130'>fine.</span> <span m='2650030'>If</span> <span m='2650200'>you</span>
  <span m='2650290'>don't</span> <span m='2650550'>want</span> <span m='2650680'>to</span>
  <span m='2650720'>allow</span> <span m='2650980'>touching,</span> <span m='2651490'>you</span>
  <span m='2651580'>need</span> <span m='2651790'>a</span> <span m='2651900'>slightly</span>
  <span m='2652950'>better</span> <span m='2653980'>strategy,</span> <span m='2658655'>which
  I'll</span> <span m='2658950'>tell</span> <span m='2659160'>you.</span> </p><p><span
  m='2660970'>It's</span> <span m='2661470'>pretty</span> <span m='2661640'>simple.</span>
  <span m='2662550'>I</span> <span m='2662660'>won't</span> <span m='2662950'>argue</span>
  <span m='2663360'>that</span> <span m='2663550'>it</span> <span m='2664190'>works,</span>
  <span m='2664680'>but</span> <span m='2666040'>it's</span> <span m='2666300'>called</span>
  <span m='2666540'>the</span> <span m='2666820'>2-step</span> <span m='2667560'>unfolding.</span>
  <span m='2668170'>This is</span> <span m='2668520'>named</span> <span m='2668720'>after</span>
  <span m='2668960'>the</span> <span m='2669110'>2-step</span> <span m='2669650'>dance.</span>
  </p><p><span m='2670550'>So</span> <span m='2670930'>we</span> <span m='2671380'>alternate</span>
  <span m='2671890'>between</span> <span m='2672260'>two</span> <span m='2672400'>kinds</span>
  <span m='2672650'>of</span> <span m='2672730'>steps.</span> <span m='2673180'>One</span>
  <span m='2673350'>is</span> <span m='2674010'>unfold</span> <span m='2676090'>of</span>
  <span m='2677130'>edge,</span> <span m='2678740'>ei,</span> <span m='2679230'>to</span>
  <span m='2679510'>be</span> <span m='2681080'>almost</span> <span m='2684280'>coplanar--</span>
  <span m='2685080'>sorry,</span> <span m='2685430'>this</span> <span m='2685560'>should</span>
  <span m='2685710'>be</span> <span m='2685890'>a</span> <span m='2686580'>face--</span>
  <span m='2695774'>face,</span> <span m='2696257'>fi,</span> <span m='2697710'>to</span>
  <span m='2697910'>be</span> <span m='2698130'>almost</span> <span m='2698560'>coplanar</span>
  <span m='2701150'>with</span> <span m='2701580'>the</span> <span m='2701750'>previous</span>
  <span m='2702110'>one,</span> <span m='2702660'>fi</span> <span m='2703330'>minus</span>
  <span m='2703670'>1.</span> <span m='2704140'>So that</span> <span m='2704280'>does</span>
  <span m='2704480'>correspond</span> <span m='2704900'>to</span> <span m='2704950'>unfolding</span>
  <span m='2705410'>an</span> <span m='2705530'>edge,</span> <span m='2705870'>but</span>
  <span m='2706570'>I'm</span> <span m='2706610'>going</span> <span m='2706710'>to</span>
  <span m='2706760'>think</span> <span m='2706940'>about</span> <span m='2707160'>numbering</span>
  <span m='2707540'>the</span> <span m='2707620'>faces.</span> </p><p><span m='2708870'>Almost</span>
  <span m='2709370'>means</span> <span m='2709590'>we</span> <span m='2709840'>unfold</span>
  <span m='2710250'>it</span> <span m='2710340'>to</span> <span m='2710650'>epsilon</span>
  <span m='2711220'>within</span> <span m='2711690'>the</span> <span m='2712140'>angle
  of</span> <span m='2712470'>180</span> <span m='2712970'>degrees.</span> <span m='2714980'>Then</span>
  <span m='2716510'>we</span> <span m='2717840'>finish</span> <span m='2718340'>unfolding</span>
  <span m='2719020'>the</span> <span m='2719290'>previous</span> <span m='2720020'>step--</span>
  <span m='2723605'>fi</span> <span m='2724740'>minus</span> <span m='2725240'>1.</span>
  <span m='2726230'>And</span> <span m='2726380'>then</span> <span m='2726590'>we</span>
  <span m='2726730'>repeat.</span> </p><p><span m='2730170'>This is</span> <span m='2730360'>a</span>
  <span m='2730430'>little</span> <span m='2730660'>funny.</span> <span m='2733830'>So</span>
  <span m='2734060'>we're</span> <span m='2734210'>worried</span> <span m='2734580'>that</span>
  <span m='2734680'>if</span> <span m='2734800'>we</span> <span m='2734920'>unfold</span>
  <span m='2735290'>all</span> <span m='2735520'>the</span> <span m='2735600'>way</span>
  <span m='2735730'>flat,</span> <span m='2736110'>we'll</span> <span m='2736290'>actually</span>
  <span m='2736570'>live</span> <span m='2736830'>in</span> <span m='2736920'>the</span>
  <span m='2737020'>plane</span> <span m='2737500'>and</span> <span m='2737600'>then</span>
  <span m='2737730'>we'll</span> <span m='2737880'>touch</span> <span m='2738190'>things.</span>
  <span m='2738900'>We</span> <span m='2739020'>don't</span> <span m='2739170'>want</span>
  <span m='2739310'>to</span> <span m='2739390'>do</span> <span m='2739530'>that.</span>
  <span m='2740150'>So</span> <span m='2740170'>we're</span> <span m='2740270'>going</span>
  <span m='2740360'>to</span> <span m='2740400'>unfold</span> <span m='2740800'>it</span>
  <span m='2740910'>almost</span> <span m='2741290'>all</span> <span m='2741420'>the</span>
  <span m='2741500'>way.</span> <span m='2742000'>But</span> <span m='2742130'>when</span>
  <span m='2742300'>we're</span> <span m='2742420'>done,</span> <span m='2742950'>we</span>
  <span m='2743090'>do</span> <span m='2743390'>want</span> <span m='2743600'>to</span>
  <span m='2743660'>be</span> <span m='2743810'>flat.</span> </p><p><span m='2744460'>So</span>
  <span m='2745380'>I</span> <span m='2745490'>don't</span> <span m='2745670'>want</span>
  <span m='2745800'>to</span> <span m='2745880'>just</span> <span m='2746080'>unfold</span>
  <span m='2746550'>everything</span> <span m='2747140'>almost</span> <span m='2747590'>all</span>
  <span m='2747730'>the</span> <span m='2747800'>way.</span> <span m='2747960'>That</span>
  <span m='2748190'>might</span> <span m='2748430'>work,</span> <span m='2748730'>but</span>
  <span m='2748830'>it's</span> <span m='2748960'>a</span> <span m='2749000'>little</span>
  <span m='2749200'>tricky--</span> <span m='2749520'>the</span> <span m='2750000'>almost</span>
  <span m='2750460'>might</span> <span m='2750630'>interact.</span> <span m='2751840'>So</span>
  <span m='2752000'>what</span> <span m='2752140'>I'm</span> <span m='2752230'>going</span>
  <span m='2752420'>to</span> <span m='2752540'>do</span> <span m='2752710'>is</span>
  <span m='2752850'>just</span> <span m='2753050'>keep</span> <span m='2753290'>one</span>
  <span m='2753710'>guy</span> <span m='2754040'>almost</span> <span m='2754460'>unfolded.</span>
  <span m='2755400'>That</span> <span m='2755560'>will</span> <span m='2755640'>be</span>
  <span m='2755750'>the</span> <span m='2755850'>previous</span> <span m='2756230'>one.</span>
  </p><p><span m='2757150'>When</span> <span m='2757340'>I've</span> <span m='2757470'>almost</span>
  <span m='2757820'>unfolded</span> <span m='2758250'>the</span> <span m='2758350'>next</span>
  <span m='2758650'>guy,</span> <span m='2758990'>I</span> <span m='2759110'>will</span>
  <span m='2759280'>finish</span> <span m='2759710'>unfolding</span> <span m='2760470'>the</span>
  <span m='2760560'>previous</span> <span m='2760970'>guy.</span> <span m='2761560'>Then</span>
  <span m='2761700'>we will</span> <span m='2761840'>almost</span> <span m='2762210'>unfold</span>
  <span m='2762580'>the</span> <span m='2762660'>next,</span> <span m='2763140'>next
  guy</span> <span m='2763390'>and</span> <span m='2763590'>then</span> <span m='2763790'>finish</span>
  <span m='2764220'>unfolding</span> <span m='2764550'>the</span> <span m='2764880'>next</span>
  <span m='2765140'>guy, and</span> <span m='2765420'>so</span> <span m='2765710'>on.</span>
  <span m='2766390'>And</span> <span m='2766620'>this</span> <span m='2766810'>turns</span>
  <span m='2767070'>out</span> <span m='2767300'>to</span> <span m='2767430'>work.</span>
  </p><p><span m='2767870'>Essentially,</span> <span m='2769142'>you've</span> <span
  m='2769530'>got</span> <span m='2769720'>your</span> <span m='2769830'>fully</span>
  <span m='2770200'>planar</span> <span m='2770560'>part,</span> <span m='2770870'>which</span>
  <span m='2771030'>is</span> <span m='2771130'>everything</span> <span m='2771830'>before</span>
  <span m='2772690'>i</span> <span m='2772820'>minus</span> <span m='2773310'>2.</span>
  <span m='2774180'>That</span> <span m='2774340'>would</span> <span m='2774420'>be</span>
  <span m='2774530'>completely</span> <span m='2775050'>flat.</span> <span m='2775930'>Then</span>
  <span m='2776170'>the</span> <span m='2776270'>next</span> <span m='2776590'>angle</span>
  <span m='2776910'>will</span> <span m='2777050'>be</span> <span m='2777230'>almost</span>
  <span m='2777650'>flat.</span> <span m='2778050'>And</span> <span m='2778180'>then</span>
  <span m='2778320'>the</span> <span m='2778430'>rest</span> <span m='2778760'>will</span>
  <span m='2778870'>be</span> <span m='2778980'>in</span> <span m='2779050'>its</span>
  <span m='2779190'>original</span> <span m='2779580'>state.</span> </p><p><span m='2780260'>And</span>
  <span m='2780500'>you</span> <span m='2780610'>can</span> <span m='2780800'>argue</span>
  <span m='2781550'>the</span> <span m='2781630'>appropriate</span> <span m='2782130'>definitions</span>
  <span m='2782610'>of</span> <span m='2782740'>almost.</span> <span m='2783650'>There</span>
  <span m='2783760'>will</span> <span m='2783880'>be</span> <span m='2784040'>no--</span>
  <span m='2785320'>in</span> <span m='2785480'>this</span> <span m='2785660'>case,</span>
  <span m='2786050'>there</span> <span m='2786190'>will</span> <span m='2786300'>be</span>
  <span m='2786450'>no</span> <span m='2786750'>two</span> <span m='2787180'>dimensional</span>
  <span m='2787800'>overlap.</span> <span m='2788300'>You</span> <span m='2788430'>still</span>
  <span m='2788870'>can</span> <span m='2789190'>get</span> <span m='2789350'>an</span>
  <span m='2789590'>edge</span> <span m='2789940'>resting</span> <span m='2790420'>on</span>
  <span m='2790590'>another</span> <span m='2790940'>thing--</span> <span m='2791890'>still</span>
  <span m='2792270'>not</span> <span m='2792490'>quite</span> <span m='2792820'>perfect.</span>
  </p><p><span m='2793210'>To</span> <span m='2793310'>make</span> <span m='2793530'>it</span>
  <span m='2793670'>completely</span> <span m='2794230'>perfect,</span> <span m='2795060'>we</span>
  <span m='2795220'>need</span> <span m='2795940'>a</span> <span m='2796020'>waltz.</span>
  <span m='2798700'>So</span> <span m='2799070'>the</span> <span m='2799210'>waltz</span>
  <span m='2800560'>is</span> <span m='2800780'>a</span> <span m='2800860'>three</span>
  <span m='2801110'>step</span> <span m='2801400'>dance.</span> <span m='2805960'>So</span>
  <span m='2806880'>the</span> <span m='2806990'>waltz,</span> <span m='2807620'>we</span>
  <span m='2807750'>have--</span> <span m='2809776'>a little</span> <span m='2810250'>tricky--</span>
  <span m='2811560'>we</span> <span m='2811730'>unfold</span> <span m='2813470'>fi</span>
  <span m='2814190'>to</span> <span m='2814760'>almost</span> <span m='2816520'>coplanar--</span>
  <span m='2819200'>almost</span> <span m='2819510'>180</span> <span m='2819970'>degrees,</span>
  <span m='2820670'>with</span> <span m='2820930'>fi</span> <span m='2821230'>minus</span>
  <span m='2821560'>1.</span> <span m='2822480'>Then</span> <span m='2824060'>we</span>
  <span m='2824310'>unfold</span> <span m='2827100'>fi</span> <span m='2827750'>plus</span>
  <span m='2828220'>1</span> <span m='2828820'>slightly.</span> <span m='2832230'>And</span>
  <span m='2832930'>then</span> <span m='2833270'>we</span> <span m='2834810'>finish</span>
  <span m='2835160'>unfolding</span> <span m='2839560'>fi</span> <span m='2840350'>minus</span>
  <span m='2841560'>1.</span> </p><p><span m='2843690'>So</span> <span m='2844820'>there's</span>
  <span m='2845090'>essentially a</span> <span m='2845590'>potential</span> <span
  m='2846000'>interaction</span> <span m='2846440'>between</span> <span m='2846710'>fi</span>
  <span m='2847000'>plus</span> <span m='2847210'>1 and</span> <span m='2847510'>fi</span>
  <span m='2847780'>minus</span> <span m='2848180'>1.</span> <span m='2848850'>We</span>
  <span m='2849050'>do</span> <span m='2849300'>a</span> <span m='2849390'>little</span>
  <span m='2849850'>bit</span> <span m='2849980'>of</span> <span m='2850080'>unfolding</span>
  <span m='2850690'>to</span> <span m='2850800'>prevent</span> <span m='2851330'>that</span>
  <span m='2851610'>from</span> <span m='2851750'>being</span> <span m='2852010'>an</span>
  <span m='2852110'>issue</span> <span m='2853150'>here.</span> <span m='2854910'>And</span>
  <span m='2855260'>so</span> <span m='2855380'>you</span> <span m='2855600'>end</span>
  <span m='2855820'>up</span> <span m='2855970'>with</span> <span m='2856150'>this</span>
  <span m='2856430'>three</span> <span m='2856660'>step</span> <span m='2857930'>waltz</span>
  <span m='2858390'>thing.</span> <span m='2861790'>Stefan</span> <span m='2862190'>Langerman</span>
  <span m='2862370'>is</span> <span m='2862770'>a</span> <span m='2863260'>dancer,</span>
  <span m='2863630'>so</span> <span m='2864110'>he</span> <span m='2864310'>liked
  this</span> <span m='2864550'>terminology.</span> <span m='2865980'>I</span> <span
  m='2866180'>won't</span> <span m='2866460'>argue</span> <span m='2866800'>here</span>
  <span m='2867190'>that</span> <span m='2867480'>that</span> <span m='2867720'>works,</span>
  <span m='2868040'>but</span> <span m='2868230'>now</span> <span m='2868470'>actually,</span>
  <span m='2868750'>you</span> <span m='2868830'>avoid</span> <span m='2869020'>all</span>
  <span m='2869190'>touching.</span> </p><p><span m='2870510'>Last</span> <span m='2871170'>picture</span>
  <span m='2871520'>I</span> <span m='2871570'>wanted</span> <span m='2871830'>to</span>
  <span m='2871910'>show</span> <span m='2872100'>you</span> <span m='2872980'>is</span>
  <span m='2873840'>I</span> <span m='2874110'>said</span> <span m='2874450'>there</span>
  <span m='2874580'>were</span> <span m='2874670'>two</span> <span m='2874850'>ways</span>
  <span m='2875060'>to</span> <span m='2875120'>unfold.</span> <span m='2875590'>One</span>
  <span m='2875830'>was</span> <span m='2875990'>you</span> <span m='2876070'>take</span>
  <span m='2876260'>any</span> <span m='2876500'>unfolding,</span> <span m='2877380'>you</span>
  <span m='2877510'>make</span> <span m='2877680'>it</span> <span m='2877720'>Hamiltonian.</span>
  <span m='2878490'>And</span> <span m='2878590'>then</span> <span m='2878720'>you</span>
  <span m='2878880'>unroll</span> <span m='2879340'>it,</span> <span m='2879460'>using</span>
  <span m='2879780'>one</span> <span m='2879930'>of</span> <span m='2880010'>these</span>
  <span m='2880190'>three</span> <span m='2880430'>algorithms--</span> <span m='2880960'>just</span>
  <span m='2881140'>regular</span> <span m='2881520'>unroll,</span> <span m='2882160'>two</span>
  <span m='2882300'>step,</span> <span m='2882600'>or</span> <span m='2882760'>waltz.</span>
  </p><p><span m='2884390'>But</span> <span m='2885842'>another</span> <span m='2886330'>strategy</span>
  <span m='2886760'>we</span> <span m='2886880'>know</span> <span m='2887230'>works</span>
  <span m='2887570'>is</span> <span m='2887770'>the</span> <span m='2887870'>source</span>
  <span m='2888200'>unfolding.</span> <span m='2888660'>Here,</span> <span m='2889260'>no</span>
  <span m='2889450'>extra</span> <span m='2889730'>cuts</span> <span m='2889960'>required.</span>
  <span m='2890710'>Source</span> <span m='2890970'>unfolding</span> <span m='2891380'>is</span>
  <span m='2891470'>like</span> <span m='2891710'>the</span> <span m='2891870'>cleanest,</span>
  <span m='2892370'>coolest</span> <span m='2892780'>unfolding.</span> <span m='2893290'>It</span>
  <span m='2893330'>turns</span> <span m='2893630'>out</span> <span m='2893790'>it</span>
  <span m='2893990'>just</span> <span m='2894310'>unfolds.</span> <span m='2895490'>No</span>
  <span m='2895650'>problem.</span> </p><p><span m='2897080'>How</span> <span m='2897290'>do</span>
  <span m='2897390'>we</span> <span m='2897540'>unfold</span> <span m='2898020'>it?</span>
  <span m='2898200'>We</span> <span m='2898350'>follow</span> <span m='2898720'>a</span>
  <span m='2898850'>post</span> <span m='2899300'>order</span> <span m='2899520'>traversal</span>
  <span m='2900110'>of</span> <span m='2900350'>the</span> <span m='2900550'>tree</span>
  <span m='2900880'>of</span> <span m='2900960'>faces,</span> <span m='2902020'>meaning</span>
  <span m='2902380'>we</span> <span m='2902920'>completely</span> <span m='2903680'>do</span>
  <span m='2904010'>one</span> <span m='2904290'>subtree.</span> <span m='2905500'>And</span>
  <span m='2905790'>now,</span> <span m='2906170'>here,</span> <span m='2906390'>we're</span>
  <span m='2906550'>in</span> <span m='2906650'>the</span> <span m='2906720'>middle</span>
  <span m='2907100'>of</span> <span m='2907220'>doing</span> <span m='2907540'>this</span>
  <span m='2907760'>subtree.</span> </p><p><span m='2909060'>So</span> <span m='2909200'>here,</span>
  <span m='2909340'>we</span> <span m='2909630'>just</span> <span m='2909860'>have</span>
  <span m='2910010'>a</span> <span m='2910230'>cube</span> <span m='2910680'>with</span>
  <span m='2910980'>x</span> <span m='2911280'>being</span> <span m='2911500'>this</span>
  <span m='2911710'>point. And</span> <span m='2912130'>so</span> <span m='2912200'>the</span>
  <span m='2912340'>reds</span> <span m='2912600'>are</span> <span m='2912640'>the</span>
  <span m='2912770'>cuts.</span> <span m='2913190'>Pretty</span> <span m='2913380'>simple</span>
  <span m='2913680'>example.</span> <span m='2914170'>You</span> <span m='2914210'>just</span>
  <span m='2914410'>have</span> <span m='2914570'>a</span> <span m='2914630'>star
  of</span> <span m='2915030'>four</span> <span m='2915310'>prongs.</span> </p><p><span
  m='2916450'>But</span> <span m='2917090'>here,</span> <span m='2917320'>we've</span>
  <span m='2917490'>completely</span> <span m='2917910'>unfolded</span> <span m='2918290'>this</span>
  <span m='2918390'>subtree.</span> <span m='2918840'>We've</span> <span m='2918990'>done</span>
  <span m='2919170'>one</span> <span m='2919450'>step</span> <span m='2919750'>of</span>
  <span m='2919850'>this</span> <span m='2919960'>subtree.</span> <span m='2920820'>The
  next</span> <span m='2921110'>thing</span> <span m='2921240'>we</span> <span m='2921340'>would</span>
  <span m='2921480'>do</span> <span m='2921590'>is</span> <span m='2921690'>flip</span>
  <span m='2921970'>it</span> <span m='2922040'>open.</span> <span m='2922800'>Then</span>
  <span m='2922940'>we</span> <span m='2923020'>do</span> <span m='2923120'>the</span>
  <span m='2923220'>next</span> <span m='2923490'>one,</span> <span m='2923910'>then</span>
  <span m='2924020'>we</span> <span m='2924110'>do</span> <span m='2924220'>the</span>
  <span m='2924340'>next</span> <span m='2924620'>one.</span> </p><p><span m='2925460'>Essentially</span>
  <span m='2926280'>what</span> <span m='2926490'>we</span> <span m='2926670'>argue</span>
  <span m='2927030'>here,</span> <span m='2927660'>in</span> <span m='2927910'>one</span>
  <span m='2928100'>minute,</span> <span m='2928550'>is</span> <span m='2930310'>as</span>
  <span m='2930500'>you</span> <span m='2930690'>unfold</span> <span m='2931330'>you</span>
  <span m='2931460'>can</span> <span m='2931640'>think</span> <span m='2931980'>of--</span>
  <span m='2933040'>well,</span> <span m='2933270'>there's</span> <span m='2933440'>a</span>
  <span m='2933490'>couple</span> <span m='2933730'>things</span> <span m='2933940'>going</span>
  <span m='2934130'>on.</span> <span m='2934650'>One</span> <span m='2934770'>is</span>
  <span m='2935450'>just</span> <span m='2935800'>look</span> <span m='2936080'>at</span>
  <span m='2936370'>a</span> <span m='2936440'>shortest</span> <span m='2936920'>path.</span>
  <span m='2937970'>Right?</span> <span m='2938150'>This</span> <span m='2938350'>source</span>
  <span m='2938870'>unfolding</span> <span m='2939230'>is</span> <span m='2939330'>made</span>
  <span m='2939600'>by</span> <span m='2940140'>a</span> <span m='2940240'>star</span>
  <span m='2940500'>of</span> <span m='2940760'>shortest</span> <span m='2941120'>paths.</span>
  <span m='2941900'>So</span> <span m='2942110'>just</span> <span m='2942290'>think</span>
  <span m='2942470'>of</span> <span m='2942560'>each</span> <span m='2943380'>shortest</span>
  <span m='2943760'>path</span> <span m='2944170'>individually</span> <span m='2946500'>for</span>
  <span m='2946750'>now.</span> </p><p><span m='2947700'>Individually,</span> <span
  m='2948340'>if</span> <span m='2948440'>you</span> <span m='2948540'>look</span>
  <span m='2948720'>at</span> <span m='2948790'>a</span> <span m='2948850'>single</span>
  <span m='2950060'>shortest</span> <span m='2950420'>path,</span> <span m='2950800'>it</span>
  <span m='2950920'>hits</span> <span m='2951150'>some</span> <span m='2951300'>sequence</span>
  <span m='2951690'>of</span> <span m='2951790'>faces.</span> <span m='2952850'>Those</span>
  <span m='2953130'>faces</span> <span m='2953620'>form</span> <span m='2954710'>a</span>
  <span m='2955460'>path-like</span> <span m='2956110'>unfolding.</span> <span m='2957190'>So</span>
  <span m='2957420'>you</span> <span m='2957570'>just</span> <span m='2957800'>use</span>
  <span m='2958090'>path</span> <span m='2958410'>unroll.</span> <span m='2959360'>And</span>
  <span m='2959700'>that</span> <span m='2959860'>will</span> <span m='2959950'>work.</span>
  </p><p><span m='2961590'>The</span> <span m='2961730'>only</span> <span m='2961940'>issue
  is</span> <span m='2962260'>potential</span> <span m='2962740'>interactions</span>
  <span m='2963300'>between</span> <span m='2963590'>the</span> <span m='2963680'>paths.</span>
  <span m='2964090'>And</span> <span m='2964190'>that's</span> <span m='2964350'>where</span>
  <span m='2964460'>you</span> <span m='2964500'>have</span> <span m='2964610'>to</span>
  <span m='2964700'>get</span> <span m='2964860'>into</span> <span m='2965090'>the</span>
  <span m='2965160'>post</span> <span m='2965415'>order</span> <span m='2965670'>traversal.</span>
  </p><p><span m='2968360'>In</span> <span m='2968580'>general,</span> <span m='2968920'>you</span>
  <span m='2969040'>want</span> <span m='2969330'>this</span> <span m='2969720'>shortest</span>
  <span m='2970090'>path</span> <span m='2970420'>to</span> <span m='2970570'>stay</span>
  <span m='2970940'>shortest.</span> <span m='2972040'>What</span> <span m='2972260'>we're</span>
  <span m='2972380'>going</span> <span m='2972600'>to</span> <span m='2972720'>do</span>
  <span m='2972910'>is</span> <span m='2973020'>imagine</span> <span m='2973630'>the</span>
  <span m='2973760'>polyhedron</span> <span m='2974400'>in</span> <span m='2974480'>some</span>
  <span m='2974680'>sense</span> <span m='2974960'>as</span> <span m='2975140'>growing</span>
  <span m='2976750'>here.</span> <span m='2977220'>So</span> <span m='2979240'>as</span>
  <span m='2979490'>we</span> <span m='2979720'>unfold--</span> <span m='2980570'>like,</span>
  <span m='2980780'>as</span> <span m='2980930'>we</span> <span m='2981050'>start</span>
  <span m='2981340'>unfolding</span> <span m='2981880'>this--</span> <span m='2982570'>we</span>
  <span m='2982690'>can</span> <span m='2982820'>think</span> <span m='2983000'>of</span>
  <span m='2983100'>the</span> <span m='2983250'>interior</span> <span m='2983620'>of
  the</span> <span m='2983750'>polyhedron</span> <span m='2984055'>as</span> <span
  m='2984360'>just</span> <span m='2984640'>getting</span> <span m='2984890'>bigger.</span>
  </p><p><span m='2985890'>And</span> <span m='2986080'>in</span> <span m='2986240'>that</span>
  <span m='2986510'>convex</span> <span m='2986910'>polyhedron,</span> <span m='2987470'>it</span>
  <span m='2987570'>turns</span> <span m='2987870'>out</span> <span m='2988080'>still</span>
  <span m='2988990'>these</span> <span m='2989210'>paths</span> <span m='2989590'>remain</span>
  <span m='2989870'>shortest.</span> <span m='2990500'>And</span> <span m='2991010'>by</span>
  <span m='2991150'>that,</span> <span m='2991380'>all</span> <span m='2991530'>the</span>
  <span m='2991660'>variants</span> <span m='2992120'>to</span> <span m='2992250'>work</span>
  <span m='2992530'>out.</span> <span m='2993140'>And</span> <span m='2993360'>you</span>
  <span m='2993460'>could</span> <span m='2993580'>argue</span> <span m='2993800'>that</span>
  <span m='2994100'>the paths</span> <span m='2994380'>basically</span> <span m='2994830'>don't</span>
  <span m='2995050'>interact</span> <span m='2995440'>with</span> <span m='2995540'>each</span>
  <span m='2995710'>other,</span> <span m='2996210'>because</span> <span m='2996560'>of</span>
  <span m='2996630'>post</span> <span m='2996905'>order</span> <span m='2997180'>traversal.</span>
  </p><p><span m='2997620'>That was</span> <span m='2997860'>very</span> <span m='2998050'>hand</span>
  <span m='2998250'>wavy.</span> <span m='2998620'>The</span> <span m='2999010'>actual</span>
  <span m='2999300'>proof</span> <span m='3000040'>is</span> <span m='3000270'>a</span>
  <span m='3000320'>bit</span> <span m='3000510'>technical</span> <span m='3001370'>and</span>
  <span m='3001520'>more</span> <span m='3001690'>than</span> <span m='3001850'>I</span>
  <span m='3001900'>can</span> <span m='3002070'>do</span> <span m='3002720'>in</span>
  <span m='3003020'>zero</span> <span m='3003630'>minutes.</span> <span m='3005900'>That's</span>
  <span m='3006190'>a</span> <span m='3006450'>sketch</span> <span m='3006910'>of</span>
  <span m='3008410'>continuous</span> <span m='3008900'>blooming</span> <span m='3009320'>of</span>
  <span m='3009620'>source</span> <span m='3009920'>unfolding,</span> <span m='3011820'>which   is
  pretty cool.</span> </p><p><span m='3012170'>Star</span> <span m='3012540'>unfolding</span>
  <span m='3012920'>is</span> <span m='3013040'>open.</span> <span m='3014110'>Whether</span>
  <span m='3014420'>all</span> <span m='3014770'>unfoldings</span> <span m='3015320'>of</span>
  <span m='3016010'>convex</span> <span m='3016390'>polyhedra</span> <span m='3016860'>work</span>
  <span m='3017460'>is</span> <span m='3017580'>open.</span> <span m='3018800'>For</span>
  <span m='3019280'>non-convex</span> <span m='3020000'>polyhedra,</span> <span m='3020820'>there</span>
  <span m='3021020'>are</span> <span m='3021180'>bunch</span> <span m='3021410'>of</span>
  <span m='3021490'>non-convex</span> <span m='3021970'>polyhedra,</span> <span m='3022380'>which</span>
  <span m='3022530'>we'll</span> <span m='3022600'>be</span> <span m='3022820'>talking</span>
  <span m='3023090'>about</span> <span m='3023500'>in</span> <span m='3023830'>future</span>
  <span m='3024170'>lectures,</span> <span m='3025030'>that</span> <span m='3025150'>we</span>
  <span m='3025270'>know have</span> <span m='3025750'>unfoldings.</span> <span m='3027150'>Do</span>
  <span m='3027360'>they</span> <span m='3027470'>have</span> <span m='3027630'>continuous</span>
  <span m='3028150'>blooming?</span> <span m='3028600'>We</span> <span m='3028700'>have</span>
  <span m='3028800'>no</span> <span m='3028910'>idea.</span> </p><p><span m='3029430'>This</span>
  <span m='3029610'>is</span> <span m='3029740'>the</span> <span m='3029820'>state</span>
  <span m='3030020'>of</span> <span m='3030110'>the</span> <span m='3030210'>art</span>
  <span m='3030410'>for</span> <span m='3031140'>bloomings.</span> <span m='3032610'>Still</span>
  <span m='3032810'>a</span> <span m='3032830'>lot</span> <span m='3033040'>of</span>
  <span m='3033150'>interesting</span> <span m='3033425'>open</span> <span m='3033700'>questions.</span>
  <span m='3034930'>Any</span> <span m='3035260'>other</span> <span m='3036240'>questions</span>
  <span m='3036620'>from</span> <span m='3036730'>you?</span> <span m='3038952'>All</span>
  <span m='3039435'>right,</span> <span m='3039920'>that's</span> <span m='3040130'>it.</span>
  </p>
type: course
uid: d9531943ae9e6a5bfbd385007b052267

---
None