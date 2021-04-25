---
about_this_resource_text: <p><strong>Description:</strong> This lecture explores the
  local behavior of a crease pattern and characterizing flat-foldability of single-vertex
  crease patterns. Kawasaki's theorem and Maekawa's theorem are presented as well
  as the tree method with Robert Lang's TreeMaker.</p> <p><strong>Speaker:</strong>
  Erik Demaine</p><p>&nbsp;</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_lec03_300k.mp4
  parent_uid: 1603733c609c79033c2088b144d09d73
  title: Video-Internet Archive-MP4
  type: Video
  uid: ec60cdc35db2f6901e570246cc5801a4
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: 1603733c609c79033c2088b144d09d73
  title: Video-iTunes U-MP4
  type: Video
  uid: 840af98b602a79ea2c3e0607f4f03891
- id: Video-YouTube-Stream
  media_location: 5lO7gBJEzH4
  parent_uid: 1603733c609c79033c2088b144d09d73
  title: Video-YouTube-Stream
  type: Video
  uid: 8f9509b1cc1142a5910abda362cf67bb
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/5lO7gBJEzH4/default.jpg
  parent_uid: 1603733c609c79033c2088b144d09d73
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e5147958afdd99ac7cb92f8aa75ef8e9
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 5lO7gBJEzH4
  parent_uid: 1603733c609c79033c2088b144d09d73
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 030d0bc7a5f796124b3acb75a21db44e
- id: 5lO7gBJEzH4.srt
  parent_uid: 1603733c609c79033c2088b144d09d73
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-3-single-vertex-crease-patterns/5lO7gBJEzH4.srt
  title: 3play caption file
  type: null
  uid: beb6327cf66eab4c1e7c191a2994c8cf
- id: 5lO7gBJEzH4.pdf
  parent_uid: 1603733c609c79033c2088b144d09d73
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-3-single-vertex-crease-patterns/5lO7gBJEzH4.pdf
  title: 3play pdf file
  type: null
  uid: dde4ebb0041ae0e5171af4cdcbab2f66
- id: Caption-3Play YouTube id-SRT
  parent_uid: 1603733c609c79033c2088b144d09d73
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 02632db7654b3a3765f264304cdccac3
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 1603733c609c79033c2088b144d09d73
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 7c81a1a2064adc22ef7316489f069ed3
inline_embed_id: 71327937lecture3:single-vertexcreasepatterns98032908
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: lecture-3-single-vertex-crease-patterns
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-3-single-vertex-crease-patterns
template_type: Tabbed
title: 'Lecture 3: Single-Vertex Crease Patterns'
transcript: <p><span m='2850'>PROFESSOR:</span> <span m='3330'>Today,</span> <span
  m='3600'>we are</span> <span m='3770'>talking</span> <span m='4190'>about</span>
  <span m='4590'>the</span> <span m='5100'>local</span> <span m='5670'>behavior</span>
  <span m='6850'>of</span> <span m='6990'>a</span> <span m='7040'>crease</span> <span
  m='7300'>pattern.</span> <span m='8970'>So</span> <span m='9120'>you</span> <span
  m='9290'>take</span> <span m='9580'>some</span> <span m='10150'>crease</span> <span
  m='10400'>pattern</span> <span m='10760'>for</span> <span m='11090'>some</span>
  <span m='12510'>flat</span> <span m='12830'>folding--</span> <span m='13240'>we're</span>
  <span m='13340'>thinking</span> <span m='13580'>about</span> <span m='13830'>flat  foldability.</span>
  <span m='15550'>This is a</span> <span m='15790'>foldability</span> <span m='16390'>question.</span>
  <span m='16710'>I</span> <span m='16750'>give</span> <span m='16890'>you</span>
  <span m='16990'>a crease</span> <span m='17210'>pattern</span> <span m='17500'>like</span>
  <span m='17680'>this.</span> <span m='17900'>I</span> <span m='17960'>want</span>
  <span m='18200'>to</span> <span m='18240'>know,</span> <span m='18370'>does</span>
  <span m='18590'>it</span> <span m='18710'>fold</span> <span m='18910'>flat,</span>
  <span m='19290'>like</span> <span m='19430'>this</span> <span m='19610'>one</span>
  <span m='19750'>does.</span> </p><p><span m='22350'>And</span> <span m='22690'>we're</span>
  <span m='23090'>studying</span> <span m='24210'>what</span> <span m='24450'>happens</span>
  <span m='25130'>locally</span> <span m='25660'>right</span> <span m='25910'>around</span>
  <span m='26290'>a</span> <span m='26350'>single</span> <span m='26720'>vertex.</span>
  <span m='28220'>So</span> <span m='28670'>I</span> <span m='28820'>didn't</span>
  <span m='29010'>mention</span> <span m='29960'>graph</span> <span m='30300'>terminology.</span>
  <span m='30870'>It's</span> <span m='31030'>probably</span> <span m='31310'>useful</span>
  <span m='31610'>to</span> <span m='31670'>mention</span> <span m='31970'>that.</span>
  <span m='32509'>These</span> <span m='32910'>corners--</span> <span m='33360'>where</span>
  <span m='33650'>all</span> <span m='33810'>the</span> <span m='34130'>edges</span>
  <span m='34420'>come</span> <span m='34590'>together--</span> <span m='35440'>those</span>
  <span m='35580'>are</span> <span m='35620'>vertices.</span> <span m='36270'>These</span>
  <span m='36570'>triangles--</span> <span m='37570'>or</span> <span m='37680'>in</span>
  <span m='37760'>general,</span> <span m='38270'>some</span> <span m='38530'>regions</span>
  <span m='39040'>divided</span> <span m='39540'>by</span> <span m='39710'>the</span>
  <span m='39820'>creases--</span> <span m='40650'>we</span> <span m='40760'>call</span>
  <span m='40910'>faces.</span> </p><p><span m='44060'>If</span> <span m='44240'>we</span>
  <span m='44550'>just</span> <span m='44810'>sort</span> <span m='44980'>of</span>
  <span m='45310'>imagine</span> <span m='45790'>cutting</span> <span m='46390'>a</span>
  <span m='46480'>little</span> <span m='47540'>disk</span> <span m='48100'>around</span>
  <span m='48580'>that</span> <span m='48810'>vertex</span> <span m='49310'>and</span>
  <span m='49410'>seeing</span> <span m='49610'>how</span> <span m='49820'>it</span>
  <span m='49910'>behaves,</span> <span m='50770'>we</span> <span m='50920'>get</span>
  <span m='51140'>a</span> <span m='51230'>nice</span> <span m='51620'>circular</span>
  <span m='52040'>piece</span> <span m='52250'>of</span> <span m='52320'>paper</span>
  <span m='53130'>with</span> <span m='53240'>some</span> <span m='53780'>crease</span>
  <span m='54070'>pattern.</span> <span m='54900'>And</span> <span m='55260'>we</span>
  <span m='55380'>want</span> <span m='55560'>to</span> <span m='55600'>understand</span>
  <span m='56070'>when</span> <span m='56260'>those</span> <span m='56490'>things</span>
  <span m='56720'>fold</span> <span m='56940'>flat</span> <span m='57740'>and</span>
  <span m='57960'>when</span> <span m='58080'>they</span> <span m='58190'>don't.</span>
  <span m='58500'>Sometimes</span> <span m='58900'>they</span> <span m='58990'>do,</span>
  <span m='59260'>sometimes</span> <span m='59570'>they</span> <span m='59650'>don't.</span>
  <span m='60710'>This</span> <span m='61010'>is</span> <span m='61540'>kind</span>
  <span m='61980'>of</span> <span m='62070'>like</span> <span m='62900'>a</span> <span
  m='63000'>one</span> <span m='63210'>dimensional</span> <span m='64849'>folding</span>
  <span m='65260'>problem.</span> <span m='65700'>So</span> <span m='65950'>let</span>
  <span m='66090'>me</span> <span m='67030'>write</span> <span m='67280'>some</span>
  <span m='67430'>stuff</span> <span m='68790'>about</span> <span m='69010'>that.</span>
  </p><p><span m='76130'>So</span> <span m='76370'>we</span> <span m='76480'>get</span>
  <span m='77330'>what</span> <span m='77710'>we</span> <span m='77870'>call</span>
  <span m='78260'>single</span> <span m='78690'>vertex</span> <span m='79190'>crease</span>
  <span m='79420'>patterns.</span> <span m='90860'>So</span> <span m='92470'>something</span>
  <span m='92890'>like--</span> <span m='93890'>this</span> <span m='94090'>is</span>
  <span m='94220'>the</span> <span m='94310'>example</span> <span m='94700'>I</span>
  <span m='94780'>have</span> <span m='96530'>made--</span> <span m='96810'>just</span>
  <span m='97090'>something like</span> <span m='97460'>that.</span> <span m='97660'>That</span>
  <span m='97770'>should</span> <span m='97960'>be</span> <span m='98100'>flat</span>
  <span m='98495'>foldable.</span> </p><p><span m='101590'>So</span> <span m='103230'>we</span>
  <span m='103410'>think</span> <span m='103670'>of</span> <span m='104200'>having</span>
  <span m='104830'>a</span> <span m='105260'>disk</span> <span m='105530'>of</span>
  <span m='105610'>paper.</span> <span m='108270'>It</span> <span m='108680'>doesn't</span>
  <span m='108970'>really</span> <span m='109190'>matter,</span> <span m='109660'>but</span>
  <span m='109860'>it's</span> <span m='110750'>going</span> <span m='110870'>to</span>
  <span m='110920'>be</span> <span m='111040'>easier</span> <span m='111360'>to</span>
  <span m='111440'>reason</span> <span m='111670'>about</span> <span m='111960'>and</span>
  <span m='112080'>think</span> <span m='112250'>about</span> <span m='112540'>a</span>
  <span m='112600'>disk</span> <span m='112830'>of</span> <span m='112890'>paper.</span>
  <span m='113790'>Really,</span> <span m='114030'>we</span> <span m='114140'>just</span>
  <span m='114330'>mean</span> <span m='114450'>some</span> <span m='114840'>small</span>
  <span m='115290'>region</span> <span m='115620'>around</span> <span m='115920'>that</span>
  <span m='116110'>vertex.</span> <span m='116940'>There's</span> <span m='117020'>obviously</span>
  <span m='117350'>one</span> <span m='117570'>vertex</span> <span m='118000'>in the</span>
  <span m='118200'>crease</span> <span m='118350'>pattern.</span> <span m='119800'>Let's</span>
  <span m='120000'>say</span> <span m='120100'>we</span> <span m='120230'>have</span>
  <span m='120500'>n</span> <span m='120770'>creases</span> <span m='123840'>emanating</span>
  <span m='124420'>from</span> <span m='124830'>one</span> <span m='125010'>vertex.</span>
  </p><p><span m='136510'>This</span> <span m='136720'>pattern</span> <span m='137300'>is</span>
  <span m='137470'>going</span> <span m='137680'>to</span> <span m='137830'>be</span>
  <span m='138010'>defined</span> <span m='138610'>by</span> <span m='139850'>some</span>
  <span m='140360'>sequence</span> <span m='140950'>of</span> <span m='141230'>angles.</span>
  <span m='158560'>In</span> <span m='158660'>general,</span> <span m='159140'>theta</span>
  <span m='159440'>1</span> <span m='160770'>up</span> <span m='160920'>to</span>
  <span m='161240'>theta</span> <span m='161650'>n.</span> <span m='161890'>If</span>
  <span m='162010'>there are</span> <span m='162190'>n</span> <span m='162490'>creases,</span>
  <span m='162790'>there</span> <span m='162910'>will</span> <span m='163030'>be</span>
  <span m='163190'>n</span> <span m='163400'>angles</span> <span m='163910'>between</span>
  <span m='164240'>them,</span> <span m='166060'>say in</span> <span m='166430'>clockwise</span>
  <span m='166910'>order.</span> <span m='168790'>And</span> <span m='170270'>let's</span>
  <span m='170430'>see.</span> </p><p><span m='173000'>When</span> <span m='173200'>we</span>
  <span m='173340'>fold</span> <span m='173640'>this</span> <span m='173830'>thing</span>
  <span m='174030'>flat--</span> <span m='178040'>like</span> <span m='178230'>in</span>
  <span m='178320'>this</span> <span m='178500'>picture--</span> <span m='180330'>we</span>
  <span m='180580'>take</span> <span m='181190'>this</span> <span m='181450'>disk.</span>
  <span m='182760'>We</span> <span m='182920'>fold</span> <span m='183220'>it</span>
  <span m='183840'>along</span> <span m='184150'>all</span> <span m='184360'>of</span>
  <span m='184430'>those</span> <span m='184630'>creases.</span> <span m='186330'>What</span>
  <span m='186530'>I'd</span> <span m='186630'>like</span> <span m='186820'>to</span>
  <span m='186930'>focus</span> <span m='187380'>on</span> <span m='187550'>is</span>
  <span m='187660'>what</span> <span m='187860'>happens</span> <span m='188380'>to</span>
  <span m='188750'>the</span> <span m='188880'>boundary</span> <span m='189720'>of</span>
  <span m='189860'>the</span> <span m='189940'>paper.</span> </p><p><span m='190590'>So</span>
  <span m='190740'>there's</span> <span m='190900'>this</span> <span m='191070'>outer</span>
  <span m='191420'>circle.</span> <span m='191870'>The boundary is</span> <span m='192240'>a</span>
  <span m='192300'>circle.</span> <span m='193720'>And</span> <span m='194100'>locally,</span>
  <span m='194540'>if</span> <span m='194640'>you</span> <span m='194740'>look</span>
  <span m='194910'>at</span> <span m='194980'>one</span> <span m='195110'>of</span>
  <span m='195160'>these</span> <span m='195330'>creases,</span> <span m='195840'>it's</span>
  <span m='196020'>like</span> <span m='196200'>folding</span> <span m='196590'>the</span>
  <span m='196670'>circle</span> <span m='197030'>in</span> <span m='197100'>half</span>
  <span m='198250'>onto</span> <span m='198530'>itself.</span> <span m='199950'>And</span>
  <span m='200170'>when</span> <span m='200280'>you</span> <span m='200390'>make</span>
  <span m='200570'>all  of</span> <span m='200860'>these</span> <span m='201050'>creases,</span>
  <span m='201450'>if</span> <span m='201560'>you're</span> <span m='201730'>successful,</span>
  <span m='202900'>you</span> <span m='203080'>end</span> <span m='203250'>up</span>
  <span m='203380'>folding</span> <span m='203880'>the</span> <span m='203970'>circle</span>
  <span m='205010'>onto</span> <span m='205840'>a</span> <span m='205940'>portion</span>
  <span m='206370'>of</span> <span m='206470'>the</span> <span m='206540'>circle.</span>
  </p><p><span m='207800'>So</span> <span m='208000'>if</span> <span m='208120'>you</span>
  <span m='208370'>look</span> <span m='208550'>at</span> <span m='208630'>this</span>
  <span m='208810'>boundary--</span> <span m='209300'>which</span> <span m='209340'>is
  a</span> <span m='209410'>little</span> <span m='209580'>hard</span> <span m='209800'>to</span>
  <span m='209870'>see.</span> <span m='211680'>Why</span> <span m='211940'>don't
  I</span> <span m='212020'>trace</span> <span m='212370'>it?</span> <span m='212960'>It's</span>
  <span m='213120'>going</span> <span m='213240'>to</span> <span m='213310'>do</span>
  <span m='213450'>something</span> <span m='213850'>like</span> <span m='215680'>this.</span>
  <span m='223400'>So</span> <span m='223480'>this</span> <span m='223730'>is</span>
  <span m='223940'>what</span> <span m='224290'>the</span> <span m='224430'>3D</span>
  <span m='225000'>thing</span> <span m='225240'>looks</span> <span m='225470'>like</span>
  <span m='227330'>blown</span> <span m='227580'>up</span> <span m='227720'>a</span>
  <span m='227760'>little</span> <span m='227970'>bit--</span> <span m='228660'>and</span>
  <span m='229580'>I</span> <span m='229770'>changed</span> <span m='230000'>the</span>
  <span m='230080'>angles a</span> <span m='230380'>little</span> <span m='230580'>bit.</span>
  </p><p><span m='231310'>But</span> <span m='231400'>this</span> <span m='231570'>is</span>
  <span m='231670'>what</span> <span m='231800'>a</span> <span m='231840'>flat</span>
  <span m='232100'>folding</span> <span m='232370'>would</span> <span m='232500'>look</span>
  <span m='232640'>like.</span> <span m='232850'>And</span> <span m='232970'>I'm</span>
  <span m='233070'>really</span> <span m='233310'>just</span> <span m='233520'>focusing</span>
  <span m='233970'>on</span> <span m='234550'>how</span> <span m='234830'>the</span>
  <span m='234950'>circle</span> <span m='235820'>maps</span> <span m='236400'>around</span>
  <span m='237450'>this</span> <span m='237570'>circle.</span> <span m='240270'>So</span>
  <span m='241350'>a</span> <span m='241720'>flat</span> <span m='242220'>folding</span>
  <span m='243190'>of</span> <span m='243380'>a</span> <span m='243460'>disk</span>
  <span m='244690'>also</span> <span m='245870'>folds</span> <span m='246490'>a</span>
  <span m='246570'>circle</span> <span m='247220'>onto</span> <span m='247460'>a</span>
  <span m='247540'>circle.</span> <span m='248826'>So</span> <span m='252490'>we</span>
  <span m='252510'>have</span> <span m='252710'>a</span> <span m='252770'>flat</span>
  <span m='253080'>folding</span> <span m='253450'>on</span> <span m='253480'>one</span>
  <span m='253630'>of</span> <span m='253670'>these</span> <span m='253770'>single</span>
  <span m='254050'>vertex</span> <span m='254460'>crease</span> <span m='254630'>patterns,</span>
  <span m='255980'>we</span> <span m='256269'>get</span> <span m='257420'>a</span>
  <span m='257500'>folding</span> <span m='261550'>of a</span> <span m='261640'>circle</span>
  <span m='266880'>onto</span> <span m='267000'>a</span> <span m='267060'>circle.</span>
  </p><p><span m='268250'>This</span> <span m='268450'>is</span> <span m='268580'>nice,</span>
  <span m='269480'>because</span> <span m='270080'>circles</span> <span m='270640'>are</span>
  <span m='270790'>one</span> <span m='271000'>dimensional.</span> <span m='272090'>And</span>
  <span m='272250'>last</span> <span m='272520'>class,</span> <span m='272770'>we</span>
  <span m='272860'>talked</span> <span m='273110'>about</span> <span m='273520'>folding</span>
  <span m='273880'>one</span> <span m='274040'>dimensional</span> <span m='274480'>line</span>
  <span m='274710'>segments.</span> <span m='274975'>A</span> <span m='275240'>circle</span>
  <span m='275630'>is</span> <span m='275680'>just</span> <span m='275920'>a</span>
  <span m='275970'>little</span> <span m='276280'>bit</span> <span m='276420'>more</span>
  <span m='276590'>complicated.</span> <span m='277650'>It's</span> <span m='277960'>different</span>
  <span m='278230'>topology.</span> <span m='279740'>But we</span> <span m='280010'>can</span>
  <span m='280140'>use</span> <span m='280340'>a</span> <span m='280410'>lot</span>
  <span m='280600'>of</span> <span m='280690'>the</span> <span m='280770'>same</span>
  <span m='281540'>mindset,</span> <span m='282060'>at</span> <span m='282110'>least,</span>
  <span m='282510'>as</span> <span m='282820'>we</span> <span m='282960'>did</span>
  <span m='283190'>for</span> <span m='283350'>folding</span> <span m='284290'>line</span>
  <span m='284530'>segments</span> <span m='285030'>onto</span> <span m='285670'>the</span>
  <span m='285760'>line.</span> </p><p><span m='286180'>In</span> <span m='286290'>particular,</span>
  <span m='288380'>you</span> <span m='288430'>can</span> <span m='288560'>see,</span>
  <span m='288830'>yeah,</span> <span m='289190'>this</span> <span m='289380'>is</span>
  <span m='289500'>kind</span> <span m='289740'>of</span> <span m='289820'>circular.</span>
  <span m='290940'>But</span> <span m='291060'>you</span> <span m='291170'>could</span>
  <span m='291310'>also</span> <span m='291600'>imagine</span> <span m='292450'>unrolling</span>
  <span m='292940'>it</span> <span m='293020'>a</span> <span m='293070'>little</span>
  <span m='293270'>bit</span> <span m='293860'>and</span> <span m='294010'>making</span>
  <span m='294360'>it</span> <span m='294470'>straight.</span> <span m='295640'>Something</span>
  <span m='296000'>like</span> <span m='297160'>this.</span> <span m='298090'>So</span>
  <span m='298270'>that</span> <span m='298470'>it lies</span> <span m='299350'>on</span>
  <span m='299510'>a</span> <span m='299560'>straight</span> <span m='299850'>line,</span>
  <span m='300310'>if</span> <span m='300380'>you</span> <span m='300460'>just</span>
  <span m='300690'>unroll</span> <span m='301050'>that</span> <span m='301250'>circle.</span>
  <span m='303160'>So</span> <span m='303340'>you</span> <span m='303480'>also</span>
  <span m='303810'>get</span> <span m='303960'>a</span> <span m='304020'>folding</span>
  <span m='304440'>of</span> <span m='304530'>a</span> <span m='304580'>circle</span>
  <span m='304930'>in</span> <span m='305010'>some</span> <span m='305280'>sense</span>
  <span m='306870'>onto</span> <span m='307190'>a</span> <span m='307240'>line</span>
  <span m='311020'>by</span> <span m='311280'>unrolling.</span> </p><p><span m='314720'>Now,</span>
  <span m='314990'>at</span> <span m='315100'>this</span> <span m='315270'>point,</span>
  <span m='315450'>I</span> <span m='315500'>want</span> <span m='315660'>to</span>
  <span m='315720'>mention</span> <span m='316100'>a</span> <span m='316170'>slight</span>
  <span m='317560'>issue</span> <span m='318100'>here.</span> <span m='320960'>I</span>
  <span m='321090'>mean</span> <span m='322670'>for</span> <span m='322760'>this</span>
  <span m='323310'>unrolling</span> <span m='323790'>to</span> <span m='323910'>work--</span>
  <span m='325590'>if</span> <span m='325810'>you're</span> <span m='325930'>taking</span>
  <span m='327520'>a</span> <span m='327560'>circle</span> <span m='327840'>like</span>
  <span m='328010'>this--</span> <span m='328870'>in</span> <span m='329000'>particular,</span>
  <span m='329500'>you</span> <span m='329550'>must</span> <span m='329800'>make</span>
  <span m='329960'>at</span> <span m='330040'>least</span> <span m='330380'>one</span>
  <span m='330640'>fold</span> <span m='330990'>for</span> <span m='331080'>this</span>
  <span m='331280'>to</span> <span m='331370'>be</span> <span m='331500'>possible.</span>
  <span m='332350'>Because</span> <span m='332530'>right</span> <span m='332740'>now,</span>
  <span m='333615'>if</span> <span m='334030'>I</span> <span m='334090'>haven't</span>
  <span m='334290'>folded</span> <span m='334560'>anything,</span> <span m='335080'>I</span>
  <span m='335210'>just</span> <span m='335390'>have</span> <span m='335510'>a</span>
  <span m='335560'>big</span> <span m='335720'>circle,</span> <span m='336050'>I</span>
  <span m='336100'>can't</span> <span m='336380'>unroll</span> <span m='336760'>circle</span>
  <span m='337070'>onto</span> <span m='337290'>a</span> <span m='337330'>line.</span>
  <span m='338000'>I</span> <span m='338120'>haven't</span> <span m='339030'>collapsed</span>
  <span m='339530'>it.</span> </p><p><span m='339650'>Yet</span> <span m='339830'>here,</span>
  <span m='340580'>I've</span> <span m='340750'>made</span> <span m='340970'>it</span>
  <span m='341110'>small</span> <span m='341450'>enough</span> <span m='341970'>that</span>
  <span m='342230'>it</span> <span m='342440'>only</span> <span m='342720'>occupies</span>
  <span m='343130'>a</span> <span m='343190'>portion</span> <span m='343640'>of</span>
  <span m='343740'>the</span> <span m='343840'>entire</span> <span m='344160'>circle.</span>
  <span m='344510'>And so</span> <span m='344620'>I</span> <span m='344780'>can</span>
  <span m='344880'>unroll</span> <span m='345260'>it.</span> <span m='345960'>So</span>
  <span m='346110'>this</span> <span m='346300'>is</span> <span m='346420'>true,</span>
  <span m='347260'>as</span> <span m='347440'>long</span> <span m='347760'>as</span>
  <span m='347890'>I</span> <span m='347960'>make</span> <span m='348230'>at</span>
  <span m='348290'>least</span> <span m='348540'>one</span> <span m='348730'>fold.</span>
  </p><p><span m='352560'>OK.</span> <span m='353410'>Technically,</span> <span m='354170'>I</span>
  <span m='354320'>need</span> <span m='354510'>to</span> <span m='354590'>assume</span>
  <span m='354910'>another</span> <span m='355200'>thing,</span> <span m='355630'>which</span>
  <span m='355840'>is</span> <span m='355970'>that</span> <span m='356570'>this</span>
  <span m='356790'>thing</span> <span m='356970'>came</span> <span m='357310'>from</span>
  <span m='357560'>a</span> <span m='357650'>flat</span> <span m='357960'>piece</span>
  <span m='358170'>of</span> <span m='358250'>paper.</span> <span m='359920'>I</span>
  <span m='360090'>said</span> <span m='360350'>there</span> <span m='360460'>were</span>
  <span m='360490'>these</span> <span m='360680'>angles.</span> <span m='361640'>And</span>
  <span m='361870'>what</span> <span m='362030'>I</span> <span m='362160'>intended</span>
  <span m='362750'>to</span> <span m='362890'>mean</span> <span m='363680'>is</span>
  <span m='363920'>that</span> <span m='364470'>the</span> <span m='364560'>sum</span>
  <span m='364800'>of</span> <span m='364880'>those</span> <span m='365100'>angles</span>
  <span m='366790'>is</span> <span m='367140'>360</span> <span m='367850'>degrees,</span>
  <span m='369230'>as</span> <span m='369450'>it</span> <span m='369540'>is</span>
  <span m='369800'>in</span> <span m='369900'>a</span> <span m='369950'>flat</span>
  <span m='370250'>piece</span> <span m='370440'>of</span> <span m='370510'>paper.</span>
  </p><p><span m='373190'>But</span> <span m='373440'>I'm</span> <span m='373590'>not</span>
  <span m='373850'>always</span> <span m='374160'>going</span> <span m='374390'>to</span>
  <span m='374500'>require</span> <span m='374940'>this</span> <span m='375180'>assumption.</span>
  <span m='376340'>It's</span> <span m='376520'>what</span> <span m='376670'>we</span>
  <span m='376780'>care</span> <span m='377070'>about</span> <span m='377480'>for</span>
  <span m='377620'>thinking</span> <span m='377940'>about</span> <span m='378240'>a</span>
  <span m='378310'>crease</span> <span m='378540'>pattern</span> <span m='378880'>of</span>
  <span m='379050'>a</span> <span m='379400'>flat</span> <span m='379630'>piece</span>
  <span m='379820'>of</span> <span m='379900'>paper</span> <span m='380770'>and</span>
  <span m='380850'>we</span> <span m='380920'>look</span> <span m='381110'>at</span>
  <span m='381150'>each</span> <span m='381290'>vertex.</span> <span m='381680'>This</span>
  <span m='381860'>will</span> <span m='381980'>be</span> <span m='382110'>true.</span>
  <span m='383960'>But</span> <span m='384240'>when</span> <span m='384530'>we</span>
  <span m='385010'>reason</span> <span m='385390'>about</span> <span m='385890'>these</span>
  <span m='386560'>single</span> <span m='386860'>vertex</span> <span m='387230'>crease</span>
  <span m='387430'>patterns,</span> <span m='387790'>it's</span> <span m='387910'>really</span>
  <span m='388180'>useful</span> <span m='388960'>to</span> <span m='389130'>think</span>
  <span m='389380'>about,</span> <span m='390560'>sort</span> <span m='390790'>of</span>
  <span m='390870'>in</span> <span m='391020'>the</span> <span m='391100'>middle,</span>
  <span m='391890'>this</span> <span m='392060'>could</span> <span m='392210'>get</span>
  <span m='392380'>smaller.</span> </p><p><span m='393130'>So</span> <span m='393170'>for</span>
  <span m='393330'>example,</span> <span m='394330'>you</span> <span m='394440'>have</span>
  <span m='394660'>a</span> <span m='394870'>pattern</span> <span m='395140'>like</span>
  <span m='395330'>this.</span> <span m='395660'>Let's</span> <span m='395910'>say</span>
  <span m='396070'>I</span> <span m='396160'>just</span> <span m='396550'>take</span>
  <span m='397190'>these</span> <span m='397380'>two</span> <span m='397530'>creases</span>
  <span m='397940'>on</span> <span m='398020'>the</span> <span m='398100'>bottom</span>
  <span m='398880'>and</span> <span m='399000'>I</span> <span m='399070'>fold</span>
  <span m='399330'>a</span> <span m='399380'>crimp.</span> <span m='400450'>Because</span>
  <span m='400610'>I</span> <span m='400670'>know</span> <span m='400990'>a</span>
  <span m='401080'>cramp</span> <span m='401350'>is</span> <span m='401570'>kind</span>
  <span m='402110'>of</span> <span m='402190'>a</span> <span m='402260'>good</span>
  <span m='402470'>thing</span> <span m='402640'>to</span> <span m='402740'>do.</span>
  <span m='403580'>So</span> <span m='403610'>now</span> <span m='403800'>I</span>
  <span m='403900'>have</span> <span m='404300'>what's</span> <span m='404640'>called</span>
  <span m='404840'>a</span> <span m='404900'>cone</span> <span m='405190'>of</span>
  <span m='405280'>paper.</span> </p><p><span m='406540'>The</span> <span m='406640'>sum</span>
  <span m='406930'>of</span> <span m='407010'>the</span> <span m='407160'>angles--</span>
  <span m='407720'>there's</span> <span m='407940'>two</span> <span m='408150'>angles</span>
  <span m='408490'>here,</span> <span m='409110'>this</span> <span m='409310'>one</span>
  <span m='409550'>and</span> <span m='409640'>this</span> <span m='409810'>one.</span>
  <span m='409970'>Each</span> <span m='410170'>one</span> <span m='410950'>looks</span>
  <span m='411120'>like</span> <span m='411250'>270--</span> <span m='412186'>no,
  not</span> <span m='412654'>270,</span> <span m='413122'>135?</span> <span m='415920'>In</span>
  <span m='416100'>total,</span> <span m='416430'>it's</span> <span m='416540'>270.</span>
  <span m='417530'>So</span> <span m='417550'>the</span> <span m='417670'>total</span>
  <span m='418050'>angle</span> <span m='418280'>there is</span> <span m='418560'>now</span>
  <span m='418730'>less</span> <span m='418980'>than</span> <span m='419060'>360.</span>
  <span m='419620'>This</span> <span m='419800'>is</span> <span m='419910'>what</span>
  <span m='420060'>we</span> <span m='420170'>call</span> <span m='420370'>a</span>
  <span m='420440'>convex</span> <span m='420980'>cone.</span> </p><p><span m='423660'>So</span>
  <span m='424280'>if</span> <span m='424470'>you</span> <span m='424780'>relax</span>
  <span m='425280'>this</span> <span m='425470'>constraint</span> <span m='427500'>to</span>
  <span m='428140'>allow</span> <span m='429290'>less</span> <span m='429560'>than</span>
  <span m='429640'>or</span> <span m='429680'>equal</span> <span m='429870'>to</span>
  <span m='429950'>360,</span> <span m='431580'>then</span> <span m='431810'>we</span>
  <span m='431920'>get</span> <span m='432735'>a</span> <span m='433030'>convex</span>
  <span m='433520'>cone.</span> <span m='436730'>And</span> <span m='437050'>today,</span>
  <span m='437500'>I</span> <span m='437520'>only</span> <span m='437790'>want</span>
  <span m='437960'>to</span> <span m='438020'>talk</span> <span m='438250'>about</span>
  <span m='438500'>flat</span> <span m='438730'>paper</span> <span m='439040'>and</span>
  <span m='439110'>convex</span> <span m='439550'>cones.</span> <span m='439840'>We</span>
  <span m='439960'>need</span> <span m='440180'>this</span> <span m='440650'>for</span>
  <span m='440840'>the</span> <span m='440950'>induction,</span> <span m='441440'>essentially--</span>
  <span m='441990'>for</span> <span m='442140'>proving</span> <span m='442490'>things</span>
  <span m='442710'>about</span> <span m='443020'>the</span> <span m='443100'>flat</span>
  <span m='443370'>case.</span> </p><p><span m='444590'>In</span> <span m='444850'>the</span>
  <span m='444980'>textbook--</span> <span m='445780'>if</span> <span m='445820'>you</span>
  <span m='445940'>look</span> <span m='446130'>at</span> <span m='446220'>this</span>
  <span m='446390'>chapter</span> <span m='446740'>on</span> <span m='446830'>single</span>
  <span m='447070'>vertex</span> <span m='447740'>crease</span> <span m='448000'>patterns--</span>
  <span m='448830'>we</span> <span m='448950'>also</span> <span m='449180'>prove</span>
  <span m='450160'>or</span> <span m='450250'>study</span> <span m='450500'>the</span>
  <span m='450610'>case</span> <span m='450930'>where</span> <span m='451300'>the</span>
  <span m='451400'>sum</span> <span m='451580'>of</span> <span m='451630'>the</span>
  <span m='451720'>angles</span> <span m='451970'>is</span> <span m='452060'>greater</span>
  <span m='452400'>than</span> <span m='452560'>360,</span> <span m='453170'>which</span>
  <span m='453340'>you</span> <span m='453430'>could</span> <span m='453570'>never</span>
  <span m='453820'>make</span> <span m='454050'>from</span> <span m='454180'>flat</span>
  <span m='454450'>paper.</span> <span m='455300'>But</span> <span m='455450'>hey,</span>
  <span m='455680'>it's</span> <span m='455880'>fun</span> <span m='456030'>to</span>
  <span m='456080'>think</span> <span m='456260'>about.</span> <span m='456680'>It's</span>
  <span m='457100'>a</span> <span m='457250'>natural</span> <span m='457550'>generalization.</span>
  <span m='458740'>And</span> <span m='459740'>all</span> <span m='459980'>the</span>
  <span m='460060'>things  that</span> <span m='460310'>we</span> <span m='460500'>do</span>
  <span m='460680'>here,</span> <span m='461000'>you</span> <span m='461160'>can</span>
  <span m='461290'>generalize</span> <span m='461545'>to</span> <span m='461800'>that</span>
  <span m='461980'>situation.</span> <span m='462950'>It's</span> <span m='463080'>just</span>
  <span m='463270'>a</span> <span m='463300'>little</span> <span m='463460'>bit</span>
  <span m='463590'>harder.</span> </p><p><span m='471780'>So</span> <span m='474610'>what</span>
  <span m='474790'>does</span> <span m='474910'>it</span> <span m='475030'>take</span>
  <span m='475250'>to</span> <span m='475340'>fold</span> <span m='475600'>a</span>
  <span m='475670'>circle</span> <span m='476530'>onto</span> <span m='476880'>a</span>
  <span m='476940'>line?</span> <span m='477420'>In</span> <span m='477560'>this</span>
  <span m='477720'>situation</span> <span m='478320'>of</span> <span m='478410'>a</span>
  <span m='478480'>convex</span> <span m='478940'>cone,</span> <span m='479390'>where</span>
  <span m='479710'>we</span> <span m='479910'>make</span> <span m='480110'>at</span>
  <span m='480180'>least</span> <span m='480440'>one</span> <span m='480640'>fold,</span>
  <span m='482170'>our</span> <span m='482300'>folding</span> <span m='482680'>is</span>
  <span m='482780'>going</span> <span m='482910'>to</span> <span m='482970'>lie</span>
  <span m='483150'>along a</span> <span m='483470'>portion</span> <span m='483780'>of</span>
  <span m='483850'>the</span> <span m='483920'>circle.</span> <span m='484370'>We</span>
  <span m='484500'>can</span> <span m='484920'>unroll</span> <span m='485370'>it</span>
  <span m='485430'>a</span> <span m='485480'>little</span> <span m='485680'>bit,</span>
  <span m='486250'>get</span> <span m='486390'>something</span> <span m='487310'>lying</span>
  <span m='487630'>on</span> <span m='487700'>a</span> <span m='487750'>straight</span>
  <span m='488010'>line.</span> </p><p><span m='490930'>It's</span> <span m='491090'>kind</span>
  <span m='491440'>of</span> <span m='491540'>like</span> <span m='494030'>folding</span>
  <span m='494700'>a</span> <span m='494780'>line</span> <span m='495030'>segment</span>
  <span m='495650'>onto</span> <span m='495870'>a</span> <span m='495930'>straight</span>
  <span m='496180'>line,</span> <span m='496480'>if</span> <span m='496895'>it</span>
  <span m='497310'>was</span> <span m='497440'>flat</span> <span m='497700'>folding</span>
  <span m='498550'>of</span> <span m='499690'>one</span> <span m='499940'>dimensional</span>
  <span m='500370'>pieces</span> <span m='500660'>of</span> <span m='500750'>paper.</span>
  <span m='508220'>But</span> <span m='508310'>there's</span> <span m='508500'>a</span>
  <span m='508570'>lot</span> <span m='508760'>of</span> <span m='508840'>differences.</span>
  <span m='510600'>I mean,</span> <span m='510730'>they</span> <span m='510870'>are</span>
  <span m='510990'>similar.</span> <span m='512990'>But</span> <span m='513110'>a</span>
  <span m='513150'>lot</span> <span m='513340'>of</span> <span m='513390'>the</span>
  <span m='513460'>things</span> <span m='513659'>we</span> <span m='513780'>proved</span>
  <span m='513990'>last</span> <span m='514270'>time</span> <span m='514470'>do</span>
  <span m='514600'>not</span> <span m='514830'>hold</span> <span m='515150'>in</span>
  <span m='515220'>the</span> <span m='515309'>case</span> <span m='515580'>of</span>
  <span m='515650'>circular</span> <span m='516020'>paper.</span> <span m='516500'>So</span>
  <span m='516980'>I</span> <span m='517080'>have</span> <span m='517260'>a</span>
  <span m='517330'>bunch</span> <span m='517590'>of</span> <span m='517650'>them</span>
  <span m='517789'>here.</span> </p><p><span m='520400'>So</span> <span m='520580'>one</span>
  <span m='520740'>problem--</span> <span m='521549'>you</span> <span m='521890'>may</span>
  <span m='522039'>recall</span> <span m='522350'>before,</span> <span m='523070'>if</span>
  <span m='523220'>we</span> <span m='523330'>had</span> <span m='523600'>a</span>
  <span m='523650'>line</span> <span m='523860'>segment</span> <span m='524270'>and</span>
  <span m='524560'>we</span> <span m='524690'>put</span> <span m='524840'>an</span>
  <span m='524930'>arbitrary</span> <span m='525400'>crease</span> <span m='525650'>pattern,</span>
  <span m='527150'>then</span> <span m='527580'>we</span> <span m='527810'>could</span>
  <span m='528000'>just</span> <span m='528210'>assign</span> <span m='528540'>a</span>
  <span m='528580'>mountain</span> <span m='528800'>valley</span> <span m='529100'>assignment,</span>
  <span m='529410'>alternating</span> <span m='529920'>mountain</span> <span m='530220'>valley.</span>
  <span m='531090'>And</span> <span m='531270'>that</span> <span m='531470'>would</span>
  <span m='531800'>always</span> <span m='532140'>fold</span> <span m='532380'>flat,</span>
  <span m='532690'>no</span> <span m='532890'>collisions.</span> <span m='534550'>OK.</span>
  </p><p><span m='534850'>In</span> <span m='535160'>this</span> <span m='535370'>world</span>
  <span m='535870'>of</span> <span m='536110'>having</span> <span m='536430'>a</span>
  <span m='536480'>circular</span> <span m='537060'>piece</span> <span m='537250'>of</span>
  <span m='537320'>paper,</span> <span m='538480'>that's</span> <span m='538840'>no</span>
  <span m='538970'>longer</span> <span m='539280'>true.</span> <span m='540670'>For</span>
  <span m='540820'>example,</span> <span m='543060'>if</span> <span m='543070'>you</span>
  <span m='543170'>have</span> <span m='543500'>this</span> <span m='543700'>kind</span>
  <span m='543890'>of</span> <span m='543980'>crease</span> <span m='544210'>pattern</span>
  <span m='544570'>on</span> <span m='544770'>a</span> <span m='544840'>circle</span>
  <span m='545750'>or</span> <span m='546050'>in</span> <span m='546260'>the</span>
  <span m='546350'>disk,</span> <span m='546830'>it</span> <span m='546920'>would</span>
  <span m='547070'>look</span> <span m='547240'>like</span> <span m='547890'>this,</span>
  <span m='548200'>those</span> <span m='548400'>two</span> <span m='548550'>creases.</span>
  <span m='549880'>You</span> <span m='550060'>can't</span> <span m='550320'>fold</span>
  <span m='550500'>that</span> <span m='550700'>thing</span> <span m='550870'>flat.</span>
  <span m='551440'>It's</span> <span m='551570'>not</span> <span m='551740'>going</span>
  <span m='551830'>to</span> <span m='551890'>work.</span> <span m='553240'>We'll</span>
  <span m='553380'>see</span> <span m='554650'>exactly</span> <span m='555050'>what</span>
  <span m='555640'>you</span> <span m='555720'>need to</span> <span m='555920'>forbid</span>
  <span m='556300'>for</span> <span m='556410'>that</span> <span m='556680'>to</span>
  <span m='556780'>make</span> <span m='556970'>sense.</span> </p><p><span m='558890'>Another</span>
  <span m='559370'>example</span> <span m='562580'>is</span> <span m='564190'>something</span>
  <span m='564650'>like</span> <span m='565170'>this.</span> <span m='571720'>I mean,</span>
  <span m='572010'>if</span> <span m='572130'>I</span> <span m='572200'>tried</span>
  <span m='572350'>to</span> <span m='572460'>draw</span> <span m='572660'>this</span>
  <span m='572890'>in</span> <span m='573515'>the</span> <span m='573890'>line,</span>
  <span m='574220'>what's</span> <span m='574400'>happening</span> <span m='575320'>is</span>
  <span m='575430'>I</span> <span m='575470'>have</span> <span m='575950'>a</span>
  <span m='576040'>short</span> <span m='576330'>segment</span> <span m='577080'>and</span>
  <span m='577170'>then</span> <span m='577270'>I</span> <span m='577300'>have</span>
  <span m='577450'>a</span> <span m='577490'>long</span> <span m='577790'>segment.</span>
  <span m='578550'>So</span> <span m='578610'>the</span> <span m='578690'>problem</span>
  <span m='578980'>is</span> <span m='579100'>those</span> <span m='579370'>ends</span>
  <span m='579650'>don't</span> <span m='579900'>meet.</span> </p><p><span m='580800'>But</span>
  <span m='580930'>even</span> <span m='581230'>when</span> <span m='581360'>the</span>
  <span m='581440'>ends</span> <span m='581710'>meet--</span> <span m='582410'>like</span>
  <span m='582670'>in</span> <span m='582750'>this</span> <span m='582910'>picture,</span>
  <span m='583220'>imagine</span> <span m='583590'>these</span> <span m='583780'>are</span>
  <span m='583890'>vertically</span> <span m='584290'>aligned--</span> <span m='585660'>if</span>
  <span m='585830'>I</span> <span m='585910'>do</span> <span m='586060'>this</span>
  <span m='586240'>alternating</span> <span m='586740'>mountain</span> <span m='587010'>valley</span>
  <span m='587360'>pattern--</span> <span m='588560'>mountain</span> <span m='588820'>valley</span>
  <span m='589060'>assignment--</span> <span m='590570'>I</span> <span m='590670'>can't</span>
  <span m='591120'>join</span> <span m='591480'>these</span> <span m='591680'>ends</span>
  <span m='592010'>and</span> <span m='592110'>make</span> <span m='592280'>a</span>
  <span m='592330'>circle,</span> <span m='593300'>because</span> <span m='593730'>that</span>
  <span m='593870'>would</span> <span m='593980'>collide</span> <span m='594390'>with</span>
  <span m='594520'>everything.</span> <span m='595550'>So</span> <span m='595730'>this</span>
  <span m='595920'>thing</span> <span m='596090'>actually</span> <span m='596370'>does</span>
  <span m='596630'>have</span> <span m='597240'>a</span> <span m='597300'>flat</span>
  <span m='597960'>folding</span> <span m='599220'>starting</span> <span m='599580'>from</span>
  <span m='599730'>a</span> <span m='599780'>circle.</span> <span m='600680'>And</span>
  <span m='600890'>I'm</span> <span m='600960'>not</span> <span m='601100'>going</span>
  <span m='601180'>to</span> <span m='601250'>try</span> <span m='601390'>to</span>
  <span m='601640'>un-map</span> <span m='602180'>it</span> <span m='602300'>to</span>
  <span m='602390'>a</span> <span m='602450'>circle.</span> <span m='603410'>It</span>
  <span m='603520'>does</span> <span m='603720'>fold,</span> <span m='604100'>but</span>
  <span m='604280'>not</span> <span m='604540'>like</span> <span m='604750'>that.</span>
  <span m='608170'>Not</span> <span m='608320'>with</span> <span m='608460'>that</span>
  <span m='608630'>alternating</span> <span m='609060'>mountain</span> <span m='609310'>valley</span>
  <span m='610000'>pattern.</span> </p><p><span m='611620'>There</span> <span m='611900'>are</span>
  <span m='611940'>other</span> <span m='612150'>annoying</span> <span m='612450'>things.</span>
  <span m='613440'>Let</span> <span m='613570'>me</span> <span m='613690'>tell</span>
  <span m='613880'>you</span> <span m='616680'>one</span> <span m='616890'>more</span>
  <span m='617120'>on</span> <span m='617190'>the</span> <span m='617270'>proof</span>
  <span m='617510'>side.</span> <span m='619660'>Last</span> <span m='619990'>time,</span>
  <span m='621230'>we</span> <span m='621420'>had</span> <span m='624920'>a lemma</span>
  <span m='625420'>that</span> <span m='625600'>said,</span> <span m='626150'>if</span>
  <span m='626430'>your</span> <span m='626770'>crease</span> <span m='627010'>pattern</span>
  <span m='627290'>is</span> <span m='627400'>mingling--</span> <span m='627840'>which</span>
  <span m='628050'>still</span> <span m='628380'>is</span> <span m='628490'>a</span>
  <span m='628530'>meaningful</span> <span m='629160'>notion</span> <span m='629520'>here--</span>
  <span m='630360'>then</span> <span m='630950'>you</span> <span m='631060'>have</span>
  <span m='631240'>a</span> <span m='631290'>crimp,</span> <span m='633030'>or</span>
  <span m='633260'>an</span> <span m='633320'>end</span> <span m='633500'>fold</span>
  <span m='633930'>in</span> <span m='633970'>that</span> <span m='634130'>case.</span>
  <span m='634340'>Here,</span> <span m='634480'>of</span> <span m='634560'>course,</span>
  <span m='634760'>we</span> <span m='634850'>don't</span> <span m='634970'>have</span>
  <span m='635110'>any</span> <span m='635250'>end</span> <span m='635595'>folds.</span>
  </p><p><span m='636210'>Here,</span> <span m='636390'>we</span> <span m='636530'>also</span>
  <span m='636820'>do</span> <span m='636960'>not</span> <span m='637250'>get</span>
  <span m='637410'>this</span> <span m='637560'>implication.</span> <span m='638720'>Mingling</span>
  <span m='639000'>does</span> <span m='639130'>not</span> <span m='639290'>imply</span>
  <span m='639530'>the</span> <span m='639590'>existence</span> <span m='640000'>of</span>
  <span m='640100'>a</span> <span m='640160'>crimp.</span> <span m='640450'>And</span>
  <span m='640660'>where</span> <span m='641060'>the</span> <span m='641170'>proof</span>
  <span m='641460'>breaks</span> <span m='641750'>down</span> <span m='642560'>is</span>
  <span m='642860'>if</span> <span m='643040'>you</span> <span m='643210'>have--</span>
  <span m='644590'>so</span> <span m='645020'>if</span> <span m='645160'>you</span>
  <span m='645300'>remember,</span> <span m='645900'>our</span> <span m='645990'>parentheses</span>
  <span m='647100'>from</span> <span m='647270'>last</span> <span m='647530'>time--</span>
  <span m='648720'>we</span> <span m='648730'>had</span> <span m='648900'>this</span>
  <span m='649060'>kind</span> <span m='649230'>of</span> <span m='649310'>pattern.</span>
  <span m='650270'>And</span> <span m='650410'>we</span> <span m='650500'>said,</span>
  <span m='650720'>well,</span> <span m='654250'>you</span> <span m='654440'>keep</span>
  <span m='654640'>going</span> <span m='655850'>and</span> <span m='656090'>either</span>
  <span m='656420'>on</span> <span m='656520'>the</span> <span m='656590'>left</span>
  <span m='656810'>side,</span> <span m='657200'>you</span> <span m='657300'>have</span>
  <span m='657450'>a</span> <span m='657680'>beginning</span> <span m='658080'>open</span>
  <span m='658340'>paren</span> <span m='658630'>or</span> <span m='658750'>on</span>
  <span m='658850'>the</span> <span m='659070'>right</span> <span m='659320'>side</span>
  <span m='659520'>you</span> <span m='659600'>have</span> <span m='659800'>a</span>
  <span m='659870'>closing</span> <span m='661230'>round</span> <span m='661610'>parenthesis.</span>
  <span m='662490'>In</span> <span m='662700'>either</span> <span m='662760'>case,</span>
  <span m='662960'>you've</span> <span m='663060'>got</span> <span m='663200'>an</span>
  <span m='663270'>end</span> <span m='663460'>fold.</span> </p><p><span m='664030'>Now,</span>
  <span m='664270'>this</span> <span m='664430'>can</span> <span m='664560'>actually</span>
  <span m='664800'>happen</span> <span m='665110'>in</span> <span m='665210'>a</span>
  <span m='665270'>circle.</span> <span m='666090'>And</span> <span m='666210'>so</span>
  <span m='666310'>you</span> <span m='666410'>have</span> <span m='666580'>nothing</span>
  <span m='666910'>you</span> <span m='667040'>can</span> <span m='667200'>do.</span>
  <span m='668190'>So</span> <span m='668330'>you</span> <span m='668390'>could</span>
  <span m='668480'>have</span> <span m='668650'>this</span> <span m='668780'>pattern.</span>
  <span m='669240'>There</span> <span m='669560'>would</span> <span m='669710'>be</span>
  <span m='669850'>no</span> <span m='670020'>crimp.</span> <span m='671720'>And</span>
  <span m='671870'>probably,</span> <span m='672230'>in</span> <span m='672290'>that</span>
  <span m='672430'>case,</span> <span m='672680'>you</span> <span m='672780'>would</span>
  <span m='672950'>not</span> <span m='673140'>be</span> <span m='673270'>flat</span>
  <span m='673610'>foldable,</span> <span m='674700'>but</span> <span m='674820'>in</span>
  <span m='674910'>particular,</span> <span m='675320'>this</span> <span m='675550'>implication</span>
  <span m='676260'>fails.</span> </p><p><span m='677580'>So</span> <span m='677990'>we</span>
  <span m='678120'>have</span> <span m='678270'>to</span> <span m='678390'>do</span>
  <span m='678560'>more</span> <span m='678760'>work.</span> <span m='679710'>But</span>
  <span m='679810'>we're</span> <span m='679950'>going</span> <span m='680060'>to</span>
  <span m='680100'>get</span> <span m='680260'>the</span> <span m='680340'>same</span>
  <span m='680550'>kind</span> <span m='680730'>of</span> <span m='680800'>result</span>
  <span m='681280'>that, in</span> <span m='681470'>linear</span> <span m='681770'>time,</span>
  <span m='682640'>we</span> <span m='682810'>can</span> <span m='682970'>tell</span>
  <span m='683360'>whether</span> <span m='683610'>one</span> <span m='683750'>of</span>
  <span m='683850'>these</span> <span m='684070'>things</span> <span m='684390'>folds</span>
  <span m='684660'>flat.</span> <span m='688219'>So</span> <span m='689590'>that's</span>
  <span m='689810'>good</span> <span m='690000'>news.</span> </p><p><span m='692490'>So</span>
  <span m='694470'>last</span> <span m='694720'>time,</span> <span m='696300'>telling</span>
  <span m='696600'>whether a</span> <span m='696840'>crease</span> <span m='697110'>pattern</span>
  <span m='697360'>folded</span> <span m='697630'>flat</span> <span m='697890'>was</span>
  <span m='698030'>trivial.</span> <span m='698460'>The answer</span> <span m='698710'>was</span>
  <span m='698830'>always</span> <span m='699040'>yes.</span> <span m='700110'>And</span>
  <span m='700200'>now,</span> <span m='700520'>it's</span> <span m='700690'>not</span>
  <span m='700830'>so</span> <span m='700920'>trivial.</span> <span m='701610'>So</span>
  <span m='701780'>let's</span> <span m='701950'>start</span> <span m='702210'>with</span>
  <span m='702450'>characterizing</span> <span m='702910'>crease</span> <span m='703270'>patterns</span>
  <span m='703600'>that</span> <span m='703690'>fold</span> <span m='703940'>flat.</span>
  <span m='704600'>Then</span> <span m='704780'>we</span> <span m='704860'>will</span>
  <span m='705020'>go</span> <span m='705220'>to</span> <span m='705770'>mountain</span>
  <span m='706060'>valley</span> <span m='706350'>patterns</span> <span m='706780'>that</span>
  <span m='706890'>fold</span> <span m='707140'>flat.</span> </p><p><span m='737020'>It'd
  be</span> <span m='737130'>great</span> <span m='737370'>if</span> <span m='737550'>I</span>
  <span m='737620'>could</span> <span m='737780'>just</span> <span m='737950'>say</span>
  <span m='738110'>that,</span> <span m='738390'>but</span> <span m='738530'>I</span>
  <span m='738700'>mean</span> <span m='738900'>here,</span> <span m='739090'>of</span>
  <span m='739210'>course,</span> <span m='739540'>single</span> <span m='739770'>vertex.</span>
  <span m='746040'>So</span> <span m='746180'>I</span> <span m='746280'>give</span>
  <span m='746490'>you</span> <span m='746960'>one</span> <span m='747150'>of</span>
  <span m='747190'>these</span> <span m='747280'>sequence</span> <span m='747680'>of</span>
  <span m='747790'>angles.</span> <span m='749180'>Let's</span> <span m='749270'>say</span>
  <span m='749370'>it</span> <span m='749570'>sums</span> <span m='749890'>to</span>
  <span m='749980'>360</span> <span m='750630'>or</span> <span m='750700'>less.</span>
  <span m='752050'>When</span> <span m='752400'>is</span> <span m='752550'>it</span>
  <span m='752670'>going</span> <span m='752940'>to</span> <span m='753500'>be</span>
  <span m='753640'>flat</span> <span m='753920'>foldable?</span> <span m='755660'>And</span>
  <span m='755820'>the</span> <span m='755900'>answer</span> <span m='756170'>is</span>
  <span m='756260'>very</span> <span m='756420'>simple.</span> <span m='759620'>Let</span>
  <span m='759690'>me</span> <span m='759840'>write</span> <span m='760040'>it</span>
  <span m='760160'>down.</span> </p><p><span m='773970'>This</span> <span m='774120'>thing</span>
  <span m='774290'>is</span> <span m='774390'>going</span> <span m='774520'>to</span>
  <span m='774570'>be</span> <span m='774700'>flat</span> <span m='774950'>foldable</span>
  <span m='776590'>if</span> <span m='776790'>and</span> <span m='776880'>only</span>
  <span m='777140'>if</span> <span m='779560'>the</span> <span m='779860'>sum</span>
  <span m='780350'>of</span> <span m='780790'>the</span> <span m='781130'>odd</span>
  <span m='781460'>angles</span> <span m='787130'>is</span> <span m='787570'>equal</span>
  <span m='787890'>to</span> <span m='788140'>the</span> <span m='788260'>sum</span>
  <span m='788490'>of</span> <span m='788590'>the</span> <span m='788740'>even</span>
  <span m='788950'>angles.</span> <span m='796130'>And,</span> <span m='798230'>yeah,</span>
  <span m='798420'>I'm</span> <span m='798550'>implicitly</span> <span m='799190'>assuming</span>
  <span m='799830'>and</span> <span m='799980'>requiring</span> <span m='800560'>here</span>
  <span m='800890'>that</span> <span m='801270'>n</span> <span m='801480'>is</span>
  <span m='801610'>even.</span> <span m='802290'>That's</span> <span m='802480'>something</span>
  <span m='802930'>we'll</span> <span m='803210'>prove.</span> <span m='803940'>So</span>
  <span m='804230'>n</span> <span m='804470'>is</span> <span m='804640'>actually</span>
  <span m='805090'>even</span> <span m='805360'>and</span> <span m='805470'>minus</span>
  <span m='805770'>1</span> <span m='805990'>is</span> <span m='806110'>going</span>
  <span m='806290'>be</span> <span m='806575'>odd.</span> </p><p><span m='807760'>And</span>
  <span m='808410'>if</span> <span m='808640'>you</span> <span m='808790'>happen</span>
  <span m='809110'>to</span> <span m='809190'>have</span> <span m='809250'>started</span>
  <span m='809530'>with</span> <span m='809680'>a</span> <span m='809720'>flat</span>
  <span m='810070'>piece</span> <span m='810250'>of</span> <span m='810340'>paper--</span>
  <span m='812250'>for</span> <span m='812440'>the</span> <span m='812630'>sum</span>
  <span m='812980'>of</span> <span m='813090'>all</span> <span m='813350'>these</span>
  <span m='813530'>things</span> <span m='813720'>is</span> <span m='813820'>360--</span>
  <span m='814410'>then</span> <span m='814560'>of</span> <span m='814660'>course,</span>
  <span m='815160'>if</span> <span m='815190'>you</span> <span m='815280'>have</span>
  <span m='815480'>them</span> <span m='815630'>evenly</span> <span m='815980'>divided,</span>
  <span m='816920'>this</span> <span m='817050'>sum</span> <span m='817400'>will</span>
  <span m='817600'>be</span> <span m='817810'>180</span> <span m='818350'>degrees.</span>
  <span m='820950'>But</span> <span m='820990'>if</span> <span m='821090'>you</span>
  <span m='821180'>started</span> <span m='821440'>with</span> <span m='821570'>the</span>
  <span m='821660'>convex</span> <span m='822070'>cone,</span> <span m='823970'>it'll</span>
  <span m='824210'>be</span> <span m='824320'>smaller.</span> <span m='828370'>For</span>
  <span m='828460'>this</span> <span m='828680'>reason,</span> <span m='829110'>a</span>
  <span m='829160'>lot</span> <span m='829320'>of</span> <span m='829390'>people--</span>
  <span m='830200'>or</span> <span m='830280'>some</span> <span m='830450'>people</span>
  <span m='830710'>call</span> <span m='830910'>this the</span> <span m='831120'>180</span>
  <span m='831630'>degree</span> <span m='831910'>property,</span> <span m='832640'>or</span>
  <span m='832920'>the</span> <span m='833050'>pie</span> <span m='833310'>property--</span>
  <span m='833850'>if</span> <span m='833990'>you</span> <span m='834150'>like</span>
  <span m='834330'>to</span> <span m='834390'>think</span> <span m='834580'>in</span>
  <span m='834670'>radians</span> <span m='835210'>instead of</span> <span m='835330'>degrees.</span>
  </p><p><span m='837740'>And</span> <span m='838200'>we</span> <span m='838300'>can</span>
  <span m='838430'>do</span> <span m='838570'>a</span> <span m='838590'>little</span>
  <span m='838790'>example</span> <span m='839510'>here.</span> <span m='840780'>This</span>
  <span m='841020'>guy--</span> <span m='842370'>this</span> <span m='842560'>crease</span>
  <span m='842800'>pattern--</span> <span m='845110'>has</span> <span m='846280'>a</span>
  <span m='846350'>90</span> <span m='846600'>degree</span> <span m='846860'>angle</span>
  <span m='847320'>here.</span> <span m='848480'>And</span> <span m='848720'>it</span>
  <span m='848760'>has</span> <span m='848960'>a</span> <span m='849000'>90</span>
  <span m='849220'>degree</span> <span m='849470'>angle</span> <span m='849740'>down</span>
  <span m='849950'>here.</span> <span m='850870'>So the</span> <span m='851060'>sum</span>
  <span m='851310'>of</span> <span m='851360'>those</span> <span m='851590'>two</span>
  <span m='851900'>is</span> <span m='851980'>180.</span> <span m='852790'>Those</span>
  <span m='852970'>are</span> <span m='853180'>alternating</span> <span m='853710'>angles,</span>
  <span m='854830'>different</span> <span m='855000'>parity</span> <span m='855300'>classes.</span>
  </p><p><span m='856210'>This</span> <span m='856420'>is</span> <span m='856540'>45.</span>
  <span m='857940'>This</span> <span m='858170'>is</span> <span m='858350'>the</span>
  <span m='858420'>complement,</span> <span m='859400'>135.</span> <span m='861740'>And</span>
  <span m='862610'>those</span> <span m='862720'>also</span> <span m='863480'>sum</span>
  <span m='863650'>to</span> <span m='863790'>180,</span> <span m='864140'>of</span>
  <span m='864240'>course.</span> <span m='864620'>One</span> <span m='864800'>does</span>
  <span m='865060'>only</span> <span m='865420'>if</span> <span m='865540'>the</span>
  <span m='865640'>other</span> <span m='865780'>does.</span> <span m='866080'>So</span>
  <span m='866230'>it's</span> <span m='866360'>flat</span> <span m='866550'>foldable.</span>
  <span m='867760'>We're</span> <span m='867890'>golden.</span> </p><p><span m='868460'>Something</span>
  <span m='868790'>like</span> <span m='868990'>this</span> <span m='869710'>is</span>
  <span m='869850'>bad,</span> <span m='870620'>because</span> <span m='873100'>I</span>
  <span m='873140'>mean</span> <span m='873400'>it's</span> <span m='873590'>an</span>
  <span m='873700'>even</span> <span m='873930'>number.</span> <span m='874280'>But</span>
  <span m='875540'>the</span> <span m='875930'>odd</span> <span m='876160'>angles</span>
  <span m='876570'>do</span> <span m='876670'>not</span> <span m='876840'>equal</span>
  <span m='877150'>the</span> <span m='877230'>sum</span> <span m='877420'>of</span>
  <span m='877510'>the</span> <span m='877620'>even</span> <span m='877810'>angles.</span>
  <span m='879240'>One's</span> <span m='879540'>clearly</span> <span m='879850'>bigger.</span>
  </p><p><span m='881290'>And</span> <span m='881580'>this</span> <span m='881740'>is</span>
  <span m='881790'>a</span> <span m='881850'>general</span> <span m='882140'>property.</span>
  <span m='882570'>This</span> <span m='882780'>is</span> <span m='882950'>also</span>
  <span m='883370'>called</span> <span m='883910'>Kawasaki's</span> <span m='884500'>theorem</span>
  <span m='885000'>or</span> <span m='885470'>Kawasaki-Justin's</span> <span m='886990'>theorem.</span>
  <span m='888220'>They</span> <span m='888350'>proved</span> <span m='888780'>it</span>
  <span m='888990'>in</span> <span m='889250'>1989.</span> <span m='890920'>This</span>
  <span m='891100'>is</span> <span m='891480'>pretty</span> <span m='891670'>much</span>
  <span m='891910'>the</span> <span m='892000'>beginning</span> <span m='892600'>of</span>
  <span m='893230'>origami</span> <span m='893630'>mathematics.</span> <span m='896050'>So</span>
  <span m='896260'>let's</span> <span m='896420'>prove</span> <span m='896650'>it.</span>
  </p><p><span m='898550'>There's</span> <span m='898660'>two</span> <span m='898800'>things</span>
  <span m='899190'>to prove.</span> <span m='899390'>One</span> <span m='899590'>is</span>
  <span m='899720'>that</span> <span m='900910'>any</span> <span m='901310'>flat</span>
  <span m='901540'>foldable</span> <span m='901950'>crease</span> <span m='902140'>pattern</span>
  <span m='902390'>has</span> <span m='902630'>this</span> <span m='902770'>property,</span>
  <span m='903330'>which</span> <span m='903410'>is</span> <span m='903500'>pretty</span>
  <span m='903700'>easy.</span> <span m='904510'>And</span> <span m='904700'>the</span>
  <span m='904820'>other,</span> <span m='905050'>which is</span> <span m='905190'>a</span>
  <span m='905230'>little</span> <span m='905460'>bit</span> <span m='905570'>harder,</span>
  <span m='906320'>is</span> <span m='906430'>that</span> <span m='906510'>if</span>
  <span m='906610'>you</span> <span m='906710'>have</span> <span m='906860'>this</span>
  <span m='907010'>property,</span> <span m='907380'>you</span> <span m='907490'>really</span>
  <span m='907770'>are</span> <span m='907920'>flat</span> <span m='908190'>foldable.</span>
  <span m='908760'>That's</span> <span m='909020'>the</span> <span m='909090'>full</span>
  <span m='909320'>characterization.</span> </p><p><span m='914090'>So</span> <span
  m='914360'>let's</span> <span m='914600'>start</span> <span m='914980'>with</span>
  <span m='915910'>the</span> <span m='916240'>easy</span> <span m='916470'>direction.</span>
  <span m='917240'>If you're</span> <span m='917400'>flat</span> <span m='917640'>foldable,</span>
  <span m='918010'>you</span> <span m='918160'>must</span> <span m='919090'>have</span>
  <span m='919430'>that</span> <span m='919690'>sum.</span> <span m='922870'>OK.</span>
  <span m='925100'>So</span> <span m='925260'>it's</span> <span m='925360'>all</span>
  <span m='925550'>about</span> <span m='926100'>thinking</span> <span m='927310'>what</span>
  <span m='927590'>happens</span> <span m='928200'>at</span> <span m='928390'>a</span>
  <span m='928470'>crease.</span> </p><p><span m='929570'>So</span> <span m='929630'>we're</span>
  <span m='929840'>thinking</span> <span m='930110'>about</span> <span m='930390'>the</span>
  <span m='930490'>boundary</span> <span m='930920'>of</span> <span m='930970'>this</span>
  <span m='931110'>piece</span> <span m='931300'>of</span> <span m='931380'>paper.</span>
  <span m='931720'>We're thinking</span> <span m='931920'>about</span> <span m='932130'>the</span>
  <span m='932210'>circle.</span> <span m='933590'>And</span> <span m='935480'>what's</span>
  <span m='935670'>happening</span> <span m='936090'>on</span> <span m='936200'>the</span>
  <span m='936260'>circle</span> <span m='937250'>as</span> <span m='937360'>you</span>
  <span m='937500'>travel,</span> <span m='940260'>say</span> <span m='940900'>counterclockwise</span>
  <span m='942000'>for</span> <span m='942150'>some</span> <span m='942560'>amount</span>
  <span m='942870'>of</span> <span m='942970'>time,</span> <span m='943290'>that</span>
  <span m='943520'>would</span> <span m='943620'>be</span> <span m='944210'>first</span>
  <span m='944540'>angle.</span> <span m='945450'>Then</span> <span m='945640'>you</span>
  <span m='946010'>make</span> <span m='946220'>a</span> <span m='946270'>fold.</span>
  <span m='946580'>It's</span> <span m='946710'>either a</span> <span m='946950'>mountain</span>
  <span m='947210'>or</span> <span m='947270'>valley.</span> </p><p><span m='947620'>At</span>
  <span m='947710'>this</span> <span m='947860'>point,</span> <span m='948030'>we</span>
  <span m='948120'>don't</span> <span m='948290'>care.</span> <span m='949140'>Either</span>
  <span m='949400'>way,</span> <span m='949590'>you</span> <span m='949730'>turn</span>
  <span m='949830'>around--</span> <span m='951110'>maybe</span> <span m='951420'>you
  turn around</span> <span m='951890'>this</span> <span m='952060'>way,</span> <span
  m='952250'>or</span> <span m='952370'>you</span> <span m='952440'>turn</span> <span
  m='952610'>around</span> <span m='952820'>this</span> <span m='952980'>way.</span>
  <span m='953910'>But</span> <span m='954370'>in</span> <span m='954460'>terms</span>
  <span m='954710'>as</span> <span m='954820'>your</span> <span m='954980'>travel</span>
  <span m='955570'>along</span> <span m='955730'>a</span> <span m='955810'>circle--</span>
  <span m='957140'>so</span> <span m='957200'>we</span> <span m='957280'>went</span>
  <span m='957740'>theta</span> <span m='958000'>1</span> <span m='958280'>counterclockwise.</span>
  <span m='959170'>Now</span> <span m='959360'>we're</span> <span m='959450'>going</span>
  <span m='959560'>to</span> <span m='959640'>go</span> <span m='959850'>theta</span>
  <span m='960140'>2</span> <span m='960930'>clockwise;</span> <span m='962110'>then</span>
  <span m='962350'>we're</span> <span m='962480'>going</span> <span m='962600'>to</span>
  <span m='962670'>go</span> <span m='962940'>theta</span> <span m='963250'>3</span>
  <span m='964390'>counterclockwise,</span> <span m='965040'>and</span> <span m='965140'>so</span>
  <span m='965300'>on.</span> <span m='965460'>We</span> <span m='965570'>keep</span>
  <span m='965840'>alternating</span> <span m='966500'>back</span> <span m='966750'>and</span>
  <span m='966860'>forth.</span> </p><p><span m='967930'>It's</span> <span m='968190'>much</span>
  <span m='968410'>easier</span> <span m='968680'>to think</span> <span m='969030'>drawn</span>
  <span m='969330'>a</span> <span m='969380'>line.</span> <span m='970290'>So</span>
  <span m='970480'>we</span> <span m='970590'>go</span> <span m='971090'>to</span>
  <span m='971190'>the</span> <span m='971310'>right,</span> <span m='971750'>theta</span>
  <span m='971970'>1.</span> <span m='972760'>Then</span> <span m='972950'>we</span>
  <span m='973070'>go</span> <span m='974030'>to</span> <span m='974110'>the</span>
  <span m='974190'>left,</span> <span m='974760'>theta</span> <span m='975050'>2.</span>
  <span m='976130'>Then</span> <span m='976280'>we</span> <span m='976420'>go</span>
  <span m='976720'>to</span> <span m='976860'>the</span> <span m='976960'>right,</span>
  <span m='978380'>theta</span> <span m='978600'>3.</span> </p><p><span m='981040'>And</span>
  <span m='981190'>I</span> <span m='981220'>don't</span> <span m='981360'>know</span>
  <span m='981470'>about</span> <span m='981680'>the</span> <span m='981770'>layering</span>
  <span m='982210'>here.</span> <span m='983000'>I'm</span> <span m='983110'>just</span>
  <span m='983300'>drawing</span> <span m='983670'>it</span> <span m='983880'>in</span>
  <span m='983990'>terms</span> <span m='984270'>of</span> <span m='984560'>horizontal</span>
  <span m='985130'>travel.</span> <span m='985480'>The</span> <span m='985570'>y-coordinate</span>
  <span m='986160'>means</span> <span m='986400'>nothing.</span> </p><p><span m='990270'>In</span>
  <span m='990470'>order</span> <span m='990690'>for</span> <span m='990830'>this</span>
  <span m='991070'>thing</span> <span m='991320'>to</span> <span m='991460'>be</span>
  <span m='991840'>a</span> <span m='991940'>flat</span> <span m='992270'>folding--</span>
  <span m='994050'>to</span> <span m='994180'>be</span> <span m='994330'>a</span>
  <span m='994370'>valid</span> <span m='994770'>folding</span> <span m='995200'>of</span>
  <span m='995350'>a</span> <span m='995410'>circle</span> <span m='995850'>of</span>
  <span m='995940'>paper--</span> <span m='997310'>these</span> <span m='997580'>guys</span>
  <span m='998330'>have</span> <span m='998620'>to</span> <span m='998720'>have</span>
  <span m='999010'>the</span> <span m='999070'>same</span> <span m='999360'>x-coordinate.</span>
  <span m='1001410'>So</span> <span m='1001440'>I</span> <span m='1001510'>don't</span>
  <span m='1001640'>know--</span> <span m='1002070'>I</span> <span m='1002180'>mean,</span>
  <span m='1002260'>the</span> <span m='1002350'>y-coordinates,</span> <span m='1003000'>they</span>
  <span m='1003170'>also</span> <span m='1003400'>have</span> <span m='1003590'>to</span>
  <span m='1003690'>work</span> <span m='1003920'>out.</span> <span m='1004280'>But</span>
  <span m='1004400'>we're</span> <span m='1004520'>not</span> <span m='1004690'>thinking</span>
  <span m='1004890'>about</span> <span m='1005050'>the</span> <span m='1005130'>y-coordinates.</span>
  <span m='1005590'>We're</span> <span m='1005680'>just</span> <span m='1005970'>thinking</span>
  <span m='1006000'>about</span> <span m='1006250'>x</span> <span m='1006480'>travel.</span>
  <span m='1008570'>We've</span> <span m='1008700'>got</span> <span m='1008860'>to</span>
  <span m='1008910'>get</span> <span m='1009060'>back</span> <span m='1009240'>to</span>
  <span m='1009340'>where</span> <span m='1009470'>we</span> <span m='1009560'>started</span>
  <span m='1009970'>if</span> <span m='1010030'>we're</span> <span m='1010160'>folding</span>
  <span m='1010490'>a</span> <span m='1010550'>circle.</span> <span m='1011770'>That's</span>
  <span m='1012010'>it.</span> </p><p><span m='1013170'>So</span> <span m='1014840'>how</span>
  <span m='1014990'>much</span> <span m='1015190'>total</span> <span m='1015460'>travel</span>
  <span m='1015800'>do</span> <span m='1015910'>we</span> <span m='1016030'>do,</span>
  <span m='1016430'>in</span> <span m='1016540'>a sign</span> <span m='1016900'>sense?</span>
  <span m='1017170'>How</span> <span m='1017260'>much</span> <span m='1017450'>do</span>
  <span m='1017540'>we</span> <span m='1017630'>go</span> <span m='1017810'>right?</span>
  <span m='1018490'>Well, we</span> <span m='1018620'>go</span> <span m='1018750'>theta</span>
  <span m='1019050'>1</span> <span m='1019250'>to</span> <span m='1019340'>the</span>
  <span m='1019440'>right.</span> <span m='1020280'>Then</span> <span m='1020480'>we</span>
  <span m='1020600'>go</span> <span m='1020750'>theta</span> <span m='1021190'>2 to</span>
  <span m='1021340'>the</span> <span m='1021490'>left,</span> <span m='1021990'>which</span>
  <span m='1022010'>is</span> <span m='1022120'>like</span> <span m='1022290'>going</span>
  <span m='1022520'>negative</span> <span m='1023040'>theta</span> <span m='1023350'>2</span>
  <span m='1023645'>to</span> <span m='1023940'>the</span> <span m='1024069'>right.</span>
  </p><p><span m='1025030'>And</span> <span m='1025270'>then</span> <span m='1025450'>we</span>
  <span m='1025579'>go</span> <span m='1025930'>through</span> <span m='1026130'>theta</span>
  <span m='1026240'>3</span> <span m='1026530'>to</span> <span m='1026640'>the</span>
  <span m='1026760'>right.</span> <span m='1027599'>Then</span> <span m='1027720'>we</span>
  <span m='1027839'>go</span> <span m='1027960'>negative</span> <span m='1028589'>theta</span>
  <span m='1028839'>4</span> <span m='1029140'>to</span> <span m='1029250'>the</span>
  <span m='1029359'>right.</span> <span m='1030470'>And</span> <span m='1030740'>you</span>
  <span m='1030859'>add</span> <span m='1031040'>up</span> <span m='1031300'>this</span>
  <span m='1031530'>alternating</span> <span m='1032069'>summation</span> <span m='1033599'>that</span>
  <span m='1033780'>must</span> <span m='1034089'>equal</span> <span m='1034730'>0.</span>
  </p><p><span m='1037960'>The</span> <span m='1038119'>other</span> <span m='1038310'>thing</span>
  <span m='1039260'>that</span> <span m='1039490'>I</span> <span m='1039569'>should</span>
  <span m='1039910'>say</span> <span m='1040140'>is</span> <span m='1040290'>that</span>
  <span m='1040420'>n</span> <span m='1040560'>has</span> <span m='1040790'>to</span>
  <span m='1040890'>be</span> <span m='1041130'>even.</span> <span m='1043619'>This</span>
  <span m='1043910'>is</span> <span m='1045569'>maybe</span> <span m='1045829'>obvious</span>
  <span m='1046310'>at</span> <span m='1046430'>this</span> <span m='1046599'>point.</span>
  <span m='1046950'>But</span> <span m='1047420'>we're</span> <span m='1047540'>supposed</span>
  <span m='1047950'>to</span> <span m='1048010'>alternate.</span> <span m='1048840'>Every</span>
  <span m='1049120'>time</span> <span m='1049360'>we</span> <span m='1049440'>hit</span>
  <span m='1049570'>a</span> <span m='1049640'>crease,</span> <span m='1049930'>we</span>
  <span m='1050060'>have</span> <span m='1050340'>to</span> <span m='1050430'>change</span>
  <span m='1050750'>direction.</span> </p><p><span m='1052340'>And</span> <span m='1052460'>so</span>
  <span m='1052630'>in</span> <span m='1052700'>the</span> <span m='1052850'>end,</span>
  <span m='1054440'>it's</span> <span m='1054600'>important</span> <span m='1055060'>that</span>
  <span m='1055310'>after</span> <span m='1055680'>theta</span> <span m='1055970'>4,</span>
  <span m='1056390'>we</span> <span m='1056530'>change</span> <span m='1056950'>direction</span>
  <span m='1057470'>to</span> <span m='1057600'>visit</span> <span m='1057950'>theta</span>
  <span m='1058170'>1.</span> <span m='1059230'>If</span> <span m='1059350'>they</span>
  <span m='1059490'>were</span> <span m='1059650'>aligned--</span> <span m='1060360'>like</span>
  <span m='1061650'>if</span> <span m='1061810'>theta</span> <span m='1062030'>4</span>
  <span m='1062310'>went</span> <span m='1062480'>over</span> <span m='1062690'>here</span>
  <span m='1063490'>and</span> <span m='1063710'>then</span> <span m='1063860'>theta</span>
  <span m='1064110'>5</span> <span m='1064750'>went</span> <span m='1064970'>like</span>
  <span m='1065180'>that,</span> <span m='1067890'>and</span> <span m='1068030'>there</span>
  <span m='1068120'>was</span> <span m='1068230'>an</span> <span m='1068330'>odd</span>
  <span m='1068530'>number</span> <span m='1068760'>of</span> <span m='1068830'>creases,</span>
  <span m='1069600'>this</span> <span m='1069780'>would</span> <span m='1069900'>be</span>
  <span m='1070020'>bad.</span> </p><p><span m='1070400'>Even</span> <span m='1070610'>though</span>
  <span m='1070870'>they're</span> <span m='1070940'>lined</span> <span m='1071270'>up,</span>
  <span m='1071480'>there's</span> <span m='1071640'>no</span> <span m='1071790'>crease</span>
  <span m='1072090'>here.</span> <span m='1072440'>You</span> <span m='1072550'>just</span>
  <span m='1072770'>went</span> <span m='1072970'>straight</span> <span m='1073480'>from</span>
  <span m='1073750'>theta</span> <span m='1074010'>5</span> <span m='1074830'>theta</span>
  <span m='1075090'>1.</span> <span m='1075710'>You're</span> <span m='1075820'>supposed</span>
  <span m='1076070'>to</span> <span m='1076140'>change</span> <span m='1076380'>direction</span>
  <span m='1076710'>every</span> <span m='1076970'>crease.</span> <span m='1077460'>So</span>
  <span m='1077960'>also,</span> <span m='1078890'>n</span> <span m='1079090'>is</span>
  <span m='1079270'>even</span> <span m='1081300'>to</span> <span m='1081740'>alternate</span>
  <span m='1082200'>directions.</span> <span m='1089650'>Question?</span> </p><p><span
  m='1090494'>AUDIENCE:</span> <span m='1090958'>Oh, no.</span> <span m='1091422'>You
  already--</span> </p><p><span m='1091886'>PROFESSOR:</span> <span m='1092350'>All
  right, good.</span> <span m='1094670'>Clear?</span> <span m='1095570'>This is</span>
  <span m='1095800'>pretty</span> <span m='1095990'>easy,</span> <span m='1097060'>once</span>
  <span m='1097260'>you</span> <span m='1097600'>realize</span> <span m='1098000'>the</span>
  <span m='1098080'>angles</span> <span m='1098440'>correspond</span> <span m='1098730'>to</span>
  <span m='1099020'>x-coordinates</span> <span m='1099700'>in</span> <span m='1099810'>this</span>
  <span m='1100010'>linear</span> <span m='1100320'>space.</span> </p><p><span m='1106470'>So</span>
  <span m='1107020'>why</span> <span m='1107320'>is</span> <span m='1107570'>this</span>
  <span m='1107760'>enough?</span> <span m='1108850'>In order</span> <span m='1109090'>to</span>
  <span m='1109160'>show</span> <span m='1109420'>that</span> <span m='1109960'>this</span>
  <span m='1110240'>property</span> <span m='1110590'>is</span> <span m='1110680'>enough</span>
  <span m='1110990'>for</span> <span m='1111110'>flat</span> <span m='1111570'>foldability,</span>
  <span m='1113120'>we</span> <span m='1113390'>need</span> <span m='1113610'>to</span>
  <span m='1113720'>actually</span> <span m='1114050'>worry</span> <span m='1114390'>about</span>
  <span m='1114930'>the</span> <span m='1115010'>stacking</span> <span m='1115430'>order</span>
  <span m='1115720'>of</span> <span m='1115800'>these</span> <span m='1116220'>edges.</span>
  <span m='1116590'>We</span> <span m='1116700'>need</span> <span m='1116810'>to</span>
  <span m='1116880'>worry</span> <span m='1117070'>about</span> <span m='1117290'>the</span>
  <span m='1117390'>y-coordinates.</span> <span m='1118130'>We</span> <span m='1118240'>need</span>
  <span m='1118380'>to</span> <span m='1118440'>make</span> <span m='1118600'>sure</span>
  <span m='1118790'>that</span> <span m='1118970'>they</span> <span m='1119080'>can</span>
  <span m='1119280'>avoid</span> <span m='1119590'>collision</span> <span m='1120330'>with</span>
  <span m='1120530'>some</span> <span m='1120860'>mountain</span> <span m='1121100'>valley</span>
  <span m='1121380'>assignment.</span> </p><p><span m='1121850'>The</span> <span m='1121940'>good</span>
  <span m='1122090'>news</span> <span m='1122270'>is</span> <span m='1122380'>we're</span>
  <span m='1122500'>free</span> <span m='1122760'>to</span> <span m='1122810'>use</span>
  <span m='1123050'>whatever</span> <span m='1123400'>mountains and</span> <span m='1123830'>valleys</span>
  <span m='1124040'>we</span> <span m='1124140'>want.</span> <span m='1124530'>We
  can</span> <span m='1124800'>stack</span> <span m='1125110'>things</span> <span
  m='1125300'>however</span> <span m='1125500'>we</span> <span m='1125670'>want.</span>
  <span m='1125930'>We</span> <span m='1126020'>just</span> <span m='1126190'>need</span>
  <span m='1126280'>to</span> <span m='1126330'>find</span> <span m='1126610'>some</span>
  <span m='1126940'>valid</span> <span m='1127300'>state.</span> </p><p><span m='1128470'>And</span>
  <span m='1128710'>our</span> <span m='1128840'>intuition,</span> <span m='1129440'>from</span>
  <span m='1129660'>the</span> <span m='1129760'>one</span> <span m='1129940'>dimensional</span>
  <span m='1130350'>case,</span> <span m='1130670'>was</span> <span m='1131670'>we</span>
  <span m='1131790'>should</span> <span m='1131980'>try</span> <span m='1132300'>alternating</span>
  <span m='1132790'>mountains</span> <span m='1133080'>and</span> <span m='1133160'>valleys.</span>
  <span m='1133900'>That</span> <span m='1134150'>seemed</span> <span m='1134310'>like</span>
  <span m='1134510'>a</span> <span m='1134560'>good</span> <span m='1134780'>thing.</span>
  <span m='1135040'>It</span> <span m='1135160'>avoided</span> <span m='1135720'>collisions</span>
  <span m='1137330'>for</span> <span m='1137570'>an</span> <span m='1137650'>open</span>
  <span m='1137960'>piece</span> <span m='1138170'>of</span> <span m='1138250'>paper--</span>
  <span m='1138570'>for</span> <span m='1139170'>a</span> <span m='1139260'>line</span>
  <span m='1139500'>segment.</span> </p><p><span m='1140220'>Of</span> <span m='1140260'>course,</span>
  <span m='1140570'>we</span> <span m='1140600'>know</span> <span m='1140820'>that's</span>
  <span m='1141050'>not</span> <span m='1141210'>enough.</span> <span m='1142130'>Here--</span>
  <span m='1142830'>somewhere--</span> <span m='1144100'>I</span> <span m='1144270'>drew</span>
  <span m='1145340'>this</span> <span m='1145500'>example.</span> <span m='1146700'>So</span>
  <span m='1146850'>it's</span> <span m='1146980'>alternating</span> <span m='1147580'>in</span>
  <span m='1147660'>the</span> <span m='1147740'>middle,</span> <span m='1149440'>and</span>
  <span m='1149660'>then</span> <span m='1149820'>that</span> <span m='1150010'>last</span>
  <span m='1150490'>crease</span> <span m='1151070'>is</span> <span m='1151200'>a</span>
  <span m='1151260'>problem.</span> <span m='1152420'>But</span> <span m='1152520'>that's</span>
  <span m='1152700'>all</span> <span m='1152870'>we</span> <span m='1152960'>need</span>
  <span m='1153130'>to</span> <span m='1153200'>fix.</span> <span m='1153560'>It</span>
  <span m='1153920'>turns</span> <span m='1154190'>out</span> <span m='1154390'>it's</span>
  <span m='1154560'>not</span> <span m='1154710'>so</span> <span m='1154850'>hard.</span>
  </p><p><span m='1157220'>So</span> <span m='1157380'>we</span> <span m='1157490'>have</span>
  <span m='1157700'>a</span> <span m='1157760'>nice</span> <span m='1157980'>circle.</span>
  <span m='1160460'>What</span> <span m='1160690'>I'd</span> <span m='1160800'>like</span>
  <span m='1160980'>to</span> <span m='1161100'>do</span> <span m='1161760'>is</span>
  <span m='1161960'>cut</span> <span m='1162270'>that</span> <span m='1162520'>circle.</span>
  <span m='1163680'>So</span> <span m='1163690'>here,</span> <span m='1163910'>I</span>
  <span m='1163960'>sort</span> <span m='1164170'>of</span> <span m='1164290'>cut</span>
  <span m='1164550'>it</span> <span m='1164680'>and</span> <span m='1164800'>thought</span>
  <span m='1165020'>about</span> <span m='1165240'>it as</span> <span m='1165360'>a</span>
  <span m='1165410'>line</span> <span m='1165660'>segment</span> <span m='1165990'>and</span>
  <span m='1166100'>then</span> <span m='1166230'>I</span> <span m='1166280'>wanted</span>
  <span m='1166590'>to</span> <span m='1166710'>rejoin.</span> <span m='1168040'>OK.</span>
  <span m='1168240'>I'm</span> <span m='1168460'>going</span> <span m='1168560'>to</span>
  <span m='1168930'>be</span> <span m='1169110'>careful</span> <span m='1169490'>about</span>
  <span m='1169760'>where</span> <span m='1169900'>I</span> <span m='1169950'>cut</span>
  <span m='1170200'>it.</span> </p><p><span m='1189284'>OK,</span> <span m='1189790'>I</span>
  <span m='1189830'>want</span> <span m='1190020'>to</span> <span m='1190090'>cut</span>
  <span m='1190360'>at</span> <span m='1190500'>an</span> <span m='1190620'>extreme</span>
  <span m='1191160'>left</span> <span m='1191550'>or</span> <span m='1191780'>extreme</span>
  <span m='1192120'>right.</span> <span m='1192390'>It doesn't</span> <span m='1192600'>matter.</span>
  <span m='1192950'>We</span> <span m='1193260'>can</span> <span m='1193410'>see</span>
  <span m='1193560'>here</span> <span m='1193740'>the</span> <span m='1193860'>cut</span>
  <span m='1194130'>ended</span> <span m='1194390'>up</span> <span m='1194510'>being</span>
  <span m='1194730'>in</span> <span m='1194810'>the</span> <span m='1194880'>middle.</span>
  <span m='1195800'>That's</span> <span m='1196000'>bad.</span> <span m='1197320'>So</span>
  <span m='1197500'>how</span> <span m='1197620'>do</span> <span m='1197690'>I</span>
  <span m='1197780'>fix</span> <span m='1198050'>it?</span> </p><p><span m='1201530'>What</span>
  <span m='1201690'>does</span> <span m='1201800'>extreme</span> <span m='1202160'>mean?</span>
  <span m='1202900'>How do I</span> <span m='1203100'>tell--</span> <span m='1203650'>given</span>
  <span m='1203890'>a</span> <span m='1203940'>circle,</span> <span m='1204300'>it's</span>
  <span m='1204400'>a</span> <span m='1204450'>little</span> <span m='1204600'>hard</span>
  <span m='1204790'>to</span> <span m='1204860'>say</span> <span m='1205030'>what</span>
  <span m='1205160'>extreme</span> <span m='1205490'>means,</span> <span m='1205730'>because</span>
  <span m='1205900'>it's</span> <span m='1206400'>circular.</span> <span m='1207760'>But</span>
  <span m='1207900'>if</span> <span m='1208030'>I</span> <span m='1208090'>take</span>
  <span m='1208330'>a</span> <span m='1208390'>picture</span> <span m='1208670'>like</span>
  <span m='1208860'>this,</span> <span m='1209180'>I've</span> <span m='1209330'>already</span>
  <span m='1209550'>drawn</span> <span m='1209860'>it</span> <span m='1209950'>with</span>
  <span m='1210210'>nice</span> <span m='1210460'>x-coordinates--</span> <span m='1211130'>I</span>
  <span m='1211180'>don't</span> <span m='1211320'>know</span> <span m='1211430'>about</span>
  <span m='1211650'>the</span> <span m='1211740'>y-coordinates</span> <span m='1212320'>yet--</span>
  <span m='1213180'>I say,</span> <span m='1213330'>oh</span> <span m='1213470'>that's</span>
  <span m='1213710'>bad.</span> <span m='1213970'>My</span> <span m='1214080'>cut</span>
  <span m='1214380'>point</span> <span m='1214620'>ended</span> <span m='1214850'>up</span>
  <span m='1214960'>being</span> <span m='1215130'>non-extreme.</span> </p><p><span
  m='1216900'>Well,</span> <span m='1217170'>this</span> <span m='1217390'>is</span>
  <span m='1217530'>extreme.</span> <span m='1218440'>So</span> <span m='1219150'>cut</span>
  <span m='1219370'>here</span> <span m='1219610'>instead.</span> <span m='1221840'>So</span>
  <span m='1222660'>what</span> <span m='1222810'>that</span> <span m='1222970'>means</span>
  <span m='1223190'>is</span> <span m='1223320'>redraw</span> <span m='1223840'>this</span>
  <span m='1224020'>picture</span> <span m='1224810'>with</span> <span m='1225040'>this</span>
  <span m='1225340'>being</span> <span m='1225570'>the</span> <span m='1225660'>cut</span>
  <span m='1225920'>point.</span> </p><p><span m='1226820'>So</span> <span m='1226990'>maybe,</span>
  <span m='1227410'>this</span> <span m='1227630'>is</span> <span m='1227760'>the</span>
  <span m='1227850'>beginning.</span> <span m='1229490'>So</span> <span m='1229600'>we</span>
  <span m='1229720'>go</span> <span m='1229900'>like</span> <span m='1230110'>that</span>
  <span m='1230660'>again</span> <span m='1231590'>and</span> <span m='1231620'>now</span>
  <span m='1231900'>we</span> <span m='1232130'>wrap</span> <span m='1232380'>around.</span>
  <span m='1233470'>So</span> <span m='1233630'>now</span> <span m='1233800'>we</span>
  <span m='1233880'>have</span> <span m='1234030'>this</span> <span m='1234180'>segment.</span>
  <span m='1235630'>And</span> <span m='1236110'>now</span> <span m='1236290'>we</span>
  <span m='1236390'>have</span> <span m='1236660'>this</span> <span m='1236750'>segment.</span>
  <span m='1238370'>And</span> <span m='1238510'>lo</span> <span m='1238650'>and</span>
  <span m='1238730'>behold,</span> <span m='1239150'>it</span> <span m='1239260'>remained</span>
  <span m='1239660'>extreme.</span> </p><p><span m='1240430'>And</span> <span m='1240550'>this</span>
  <span m='1240710'>is</span> <span m='1240840'>always</span> <span m='1241110'>true.</span>
  <span m='1241460'>You</span> <span m='1241510'>can</span> <span m='1241670'>do</span>
  <span m='1241770'>this</span> <span m='1241950'>sort</span> <span m='1242100'>of</span>
  <span m='1242670'>cut</span> <span m='1243090'>and</span> <span m='1243310'>rejoin</span>
  <span m='1244060'>the</span> <span m='1244390'>ends</span> <span m='1244760'>that</span>
  <span m='1244890'>were</span> <span m='1245460'>messed</span> <span m='1245710'>up</span>
  <span m='1245820'>before.</span> <span m='1246930'>And</span> <span m='1247060'>you'll</span>
  <span m='1247200'>preserve</span> <span m='1247590'>the</span> <span m='1247680'>x-coordinates.</span>
  <span m='1247975'>The</span> <span m='1248270'>x-coordinates</span> <span m='1248850'>aren't</span>
  <span m='1249020'>changing</span> <span m='1249500'>when</span> <span m='1249610'>you</span>
  <span m='1249690'>do</span> <span m='1249810'>this</span> <span m='1249960'>kind</span>
  <span m='1250120'>of</span> <span m='1250170'>transformation.</span> </p><p><span
  m='1251340'>So</span> <span m='1251400'>there's</span> <span m='1251610'>a</span>
  <span m='1251680'>clear</span> <span m='1252060'>leftmost</span> <span m='1252650'>and</span>
  <span m='1252710'>there's</span> <span m='1252850'>a</span> <span m='1252900'>clear</span>
  <span m='1253190'>rightmost.</span> <span m='1254030'>You</span> <span m='1254140'>pick</span>
  <span m='1254330'>either</span> <span m='1254610'>one,</span> <span m='1254810'>you</span>
  <span m='1254910'>cut</span> <span m='1255160'>there</span> <span m='1255350'>instead.</span>
  <span m='1256130'>And</span> <span m='1256320'>now</span> <span m='1256650'>we</span>
  <span m='1256750'>have</span> <span m='1256910'>this</span> <span m='1257070'>nice</span>
  <span m='1257280'>property</span> <span m='1258210'>that</span> <span m='1258350'>it's</span>
  <span m='1258520'>easy</span> <span m='1258850'>to</span> <span m='1258970'>join</span>
  <span m='1259230'>the</span> <span m='1259360'>ends,</span> <span m='1259920'>because</span>
  <span m='1261170'>it's</span> <span m='1261330'>as</span> <span m='1261510'>far</span>
  <span m='1261730'>left</span> <span m='1261960'>as</span> <span m='1262030'>you</span>
  <span m='1262160'>can</span> <span m='1262280'>go.</span> <span m='1262470'>There</span>
  <span m='1262600'>can't</span> <span m='1262860'>be</span> <span m='1262980'>anything</span>
  <span m='1263340'>that</span> <span m='1263430'>penetrates,</span> <span m='1264140'>because</span>
  <span m='1264270'>that</span> <span m='1264420'>would</span> <span m='1264540'>be</span>
  <span m='1265150'>farther</span> <span m='1265430'>left.</span> </p><p><span m='1268820'>Let</span>
  <span m='1268950'>me</span> <span m='1269190'>write</span> <span m='1269380'>down</span>
  <span m='1269560'>some</span> <span m='1269760'>words</span> <span m='1270250'>corresponding</span>
  <span m='1270890'>to</span> <span m='1270990'>that.</span> <span m='1272470'>So</span>
  <span m='1273120'>once</span> <span m='1273460'>we</span> <span m='1273630'>cut</span>
  <span m='1273870'>at</span> <span m='1273990'>this</span> <span m='1274170'>extreme</span>
  <span m='1274590'>crease,</span> <span m='1275770'>you</span> <span m='1275940'>can</span>
  <span m='1276345'>fold</span> <span m='1278630'>this</span> <span m='1278830'>1D</span>
  <span m='1280370'>segment</span> <span m='1282070'>just</span> <span m='1282310'>like</span>
  <span m='1282540'>we</span> <span m='1282680'>used</span> <span m='1282870'>to</span>
  <span m='1282940'>be</span> <span m='1283100'>able</span> <span m='1283310'>to.</span>
  <span m='1287080'>So we</span> <span m='1287230'>can</span> <span m='1287370'>fold</span>
  <span m='1287630'>it</span> <span m='1287740'>flat</span> <span m='1290100'>using</span>
  <span m='1290480'>the</span> <span m='1290760'>accordion</span> <span m='1291220'>fold,</span>
  <span m='1291550'>alternating</span> <span m='1292000'>mountain</span> <span m='1292270'>and</span>
  <span m='1292370'>valley.</span> <span m='1295050'>We</span> <span m='1295260'>know</span>
  <span m='1295430'>that</span> <span m='1295630'>works.</span> </p><p><span m='1296730'>And</span>
  <span m='1296830'>then</span> <span m='1297760'>all</span> <span m='1297940'>we</span>
  <span m='1298040'>need</span> <span m='1298200'>to</span> <span m='1298300'>show</span>
  <span m='1298630'>is</span> <span m='1298890'>that the</span> <span m='1299020'>two</span>
  <span m='1299270'>ends</span> <span m='1300700'>can</span> <span m='1300980'>join.</span>
  <span m='1304510'>Those</span> <span m='1304770'>ends</span> <span m='1305270'>are</span>
  <span m='1305460'>the</span> <span m='1305570'>two</span> <span m='1305760'>copies</span>
  <span m='1306830'>of</span> <span m='1307870'>the</span> <span m='1308410'>cut</span>
  <span m='1308800'>crease</span> <span m='1314860'>that</span> <span m='1314960'>we</span>
  <span m='1314970'>did</span> <span m='1315190'>in</span> <span m='1315340'>this</span>
  <span m='1315550'>first</span> <span m='1315770'>step.</span> </p><p><span m='1320190'>We</span>
  <span m='1320370'>need</span> <span m='1320570'>two</span> <span m='1320730'>things.</span>
  <span m='1322250'>One</span> <span m='1322350'>is</span> <span m='1322470'>that</span>
  <span m='1322550'>they</span> <span m='1322690'>are</span> <span m='1322810'>aligned</span>
  <span m='1324830'>and</span> <span m='1325190'>that's</span> <span m='1325670'>where</span>
  <span m='1325880'>we</span> <span m='1326010'>need</span> <span m='1326310'>this</span>
  <span m='1326760'>condition--</span> <span m='1327940'>that</span> <span m='1328200'>the</span>
  <span m='1328660'>sum</span> <span m='1329090'>of</span> <span m='1329180'>the</span>
  <span m='1329830'>odd</span> <span m='1330020'>angles</span> <span m='1330310'>equals</span>
  <span m='1330550'>the</span> <span m='1330620'>sum</span> <span m='1330830'>of</span>
  <span m='1330890'>even</span> <span m='1331160'>angles,</span> <span m='1332130'>which</span>
  <span m='1332230'>is</span> <span m='1332340'>the</span> <span m='1332400'>same</span>
  <span m='1332690'>as</span> <span m='1332780'>saying</span> <span m='1332980'>the</span>
  <span m='1333090'>alternating</span> <span m='1333570'>sum</span> <span m='1334430'>is</span>
  <span m='1334550'>equal</span> <span m='1334790'>to</span> <span m='1334840'>zero.</span>
  <span m='1335350'>That</span> <span m='1335580'>tells</span> <span m='1335930'>us</span>
  <span m='1336370'>that</span> <span m='1336570'>whatever</span> <span m='1336920'>we</span>
  <span m='1337060'>do,</span> <span m='1337270'>the</span> <span m='1337360'>x-coordinates</span>
  <span m='1337960'>are</span> <span m='1338030'>lined</span> <span m='1338300'>up</span>
  <span m='1338460'>at</span> <span m='1338550'>the</span> <span m='1338670'>end.</span>
  <span m='1340650'>So</span> <span m='1340740'>they are</span> <span m='1340940'>aligned</span>
  <span m='1341320'>by</span> <span m='1342770'>the</span> <span m='1342860'>assumption</span>
  <span m='1343330'>that</span> <span m='1343460'>we</span> <span m='1343570'>made</span>
  <span m='1343770'>here.</span> <span m='1344710'>And</span> <span m='1347890'>you</span>
  <span m='1348060'>can</span> <span m='1348210'>join</span> <span m='1350400'>without</span>
  <span m='1350730'>crossing.</span> </p><p><span m='1354730'>So</span> <span m='1354880'>this</span>
  <span m='1355090'>is</span> <span m='1355210'>a</span> <span m='1355280'>statement</span>
  <span m='1355630'>about</span> <span m='1355870'>y-coordinates.</span> <span m='1357240'>And</span>
  <span m='1357400'>we</span> <span m='1357510'>know</span> <span m='1357700'>it's</span>
  <span m='1357850'>OK,</span> <span m='1358270'>because</span> <span m='1358750'>it's</span>
  <span m='1358920'>at</span> <span m='1359150'>the</span> <span m='1359250'>left</span>
  <span m='1359520'>extreme.</span> <span m='1360530'>So by</span> <span m='1360750'>this</span>
  <span m='1360930'>choice</span> <span m='1361280'>of</span> <span m='1361380'>the</span>
  <span m='1361490'>proper</span> <span m='1361860'>cut,</span> <span m='1363440'>there</span>
  <span m='1363570'>could</span> <span m='1363810'>be</span> <span m='1363990'>other</span>
  <span m='1364160'>things</span> <span m='1364390'>that</span> <span m='1364490'>come</span>
  <span m='1364810'>right</span> <span m='1365150'>to</span> <span m='1365240'>the</span>
  <span m='1365330'>boundary</span> <span m='1365750'>here,</span> <span m='1366370'>but</span>
  <span m='1366500'>that's</span> <span m='1366740'>considered</span> <span m='1367210'>OK.</span>
  <span m='1367570'>That's</span> <span m='1367790'>not</span> <span m='1367960'>crossing,</span>
  <span m='1368500'>that</span> <span m='1368710'>just</span> <span m='1368910'>touching.</span>
  <span m='1370400'>Nothing</span> <span m='1370750'>can</span> <span m='1370910'>go</span>
  <span m='1371080'>farther</span> <span m='1371410'>left</span> <span m='1372210'>because</span>
  <span m='1372860'>it</span> <span m='1372930'>was the</span> <span m='1373100'>left</span>
  <span m='1373360'>extreme.</span> </p><p><span m='1376740'>That's</span> <span m='1376950'>the</span>
  <span m='1377030'>end</span> <span m='1377170'>of</span> <span m='1377220'>the</span>
  <span m='1377320'>proof.</span> <span m='1377670'>Any</span> <span m='1377840'>questions</span>
  <span m='1378240'>about</span> <span m='1378450'>that?</span> <span m='1381020'>That's</span>
  <span m='1381180'>Kawasaki's</span> <span m='1381640'>theorem--</span> <span m='1384430'>Kawasaki-Justin.</span>
  </p><p><span m='1385060'>I would</span> <span m='1385480'>mention</span> <span m='1385900'>just</span>
  <span m='1386060'>for</span> <span m='1386150'>fun--</span> <span m='1387060'>this
  is</span> <span m='1387230'>sort</span> <span m='1387380'>of</span> <span m='1387470'>classic--</span>
  <span m='1389850'>if</span> <span m='1390120'>you</span> <span m='1390520'>allow</span>
  <span m='1392210'>one</span> <span m='1392460'>of</span> <span m='1392580'>these--</span>
  <span m='1393660'>a</span> <span m='1393800'>non-convex</span> <span m='1394520'>cone,</span>
  <span m='1395410'>where you</span> <span m='1395600'>have</span> <span m='1395750'>more</span>
  <span m='1395990'>than</span> <span m='1396130'>360</span> <span m='1396700'>degrees</span>
  <span m='1397340'>of</span> <span m='1397410'>material--</span> <span m='1398250'>this</span>
  <span m='1398360'>statement</span> <span m='1398660'>is</span> <span m='1398760'>not</span>
  <span m='1399040'>true.</span> <span m='1400550'>And</span> <span m='1402020'>there's</span>
  <span m='1402210'>one</span> <span m='1402460'>other</span> <span m='1402650'>situation</span>
  <span m='1403160'>which</span> <span m='1403340'>can</span> <span m='1403450'>happen,</span>
  <span m='1404240'>which</span> <span m='1404320'>is</span> <span m='1404470'>that
  the</span> <span m='1404700'>alternating</span> <span m='1405170'>sum</span> <span
  m='1405390'>of</span> <span m='1405500'>angles</span> <span m='1405820'>is</span>
  <span m='1405910'>not</span> <span m='1406140'>zero,</span> <span m='1406530'>but</span>
  <span m='1406740'>it's</span> <span m='1407280'>plus</span> <span m='1407530'>or</span>
  <span m='1407590'>minus</span> <span m='1407900'>360</span> <span m='1408940'>degrees,</span>
  <span m='1410100'>which</span> <span m='1410110'>is</span> <span m='1410210'>fun.</span>
  <span m='1410430'>And</span> <span m='1411030'>you</span> <span m='1411170'>can</span>
  <span m='1411290'>see</span> <span m='1411420'>examples</span> <span m='1411810'>of</span>
  <span m='1411870'>that</span> <span m='1412020'>in</span> <span m='1412090'>the</span>
  <span m='1412160'>book.</span> </p><p><span m='1416930'>All</span> <span m='1417000'>right.</span>
  <span m='1417670'>So</span> <span m='1418070'>obviously,</span> <span m='1418480'>if</span>
  <span m='1418600'>you</span> <span m='1418730'>want</span> <span m='1418880'>to</span>
  <span m='1418960'>tell</span> <span m='1419260'>whether a</span> <span m='1419540'>crease</span>
  <span m='1419790'>pattern--</span> <span m='1420370'>or</span> <span m='1420640'>a</span>
  <span m='1420930'>single</span> <span m='1421220'>vertex</span> <span m='1421710'>is</span>
  <span m='1421860'>flat</span> <span m='1422080'>foldable,</span> <span m='1422860'>you
  just</span> <span m='1423080'>compute</span> <span m='1423380'>this</span> <span
  m='1423550'>thing</span> <span m='1423730'>in</span> <span m='1423780'>linear</span>
  <span m='1424060'>time</span> <span m='1424410'>and</span> <span m='1424500'>you</span>
  <span m='1424600'>know</span> <span m='1425500'>yes</span> <span m='1425710'>or</span>
  <span m='1425770'>no.</span> <span m='1428220'>So</span> <span m='1428430'>crease</span>
  <span m='1428640'>patterns</span> <span m='1428980'>are</span> <span m='1429270'>pretty</span>
  <span m='1429700'>easy--</span> <span m='1431190'>just have</span> <span m='1431390'>one</span>
  <span m='1431650'>extra</span> <span m='1432016'>condition.</span> </p><p><span
  m='1433840'>What</span> <span m='1434010'>about</span> <span m='1434250'>mountain</span>
  <span m='1434510'>valley</span> <span m='1434820'>assignments?</span> <span m='1435580'>Last</span>
  <span m='1435950'>time,</span> <span m='1436940'>we</span> <span m='1437060'>looked</span>
  <span m='1437250'>at</span> <span m='1437300'>mountain</span> <span m='1437530'>valley</span>
  <span m='1437880'>assignments</span> <span m='1438100'>and</span> <span m='1438230'>we</span>
  <span m='1438380'>showed</span> <span m='1438820'>that</span> <span m='1439020'>crimps</span>
  <span m='1439690'>and</span> <span m='1440100'>end folds</span> <span m='1440960'>were</span>
  <span m='1441110'>always</span> <span m='1441380'>enough</span> <span m='1441730'>to</span>
  <span m='1441830'>fold</span> <span m='1442090'>any</span> <span m='1442290'>mountain</span>
  <span m='1442570'>valley</span> <span m='1442820'>assignment</span> <span m='1443220'>that's</span>
  <span m='1443380'>out</span> <span m='1443580'>there.</span> <span m='1445760'>That</span>
  <span m='1446050'>will</span> <span m='1446410'>continue</span> <span m='1446990'>to</span>
  <span m='1447120'>be</span> <span m='1447270'>true</span> <span m='1447530'>here,</span>
  <span m='1448410'>except</span> <span m='1448500'>now</span> <span m='1448650'>we</span>
  <span m='1448720'>don't</span> <span m='1448840'>have</span> <span m='1448990'>end</span>
  <span m='1449130'>folds.</span> <span m='1449460'>Now,</span> <span m='1449800'>it's</span>
  <span m='1450130'>crimps</span> <span m='1450450'>all</span> <span m='1450600'>the</span>
  <span m='1450670'>way.</span> <span m='1453220'>What</span> <span m='1453450'>does</span>
  <span m='1453580'>it</span> <span m='1453660'>mean?</span> </p><p><span m='1456750'>So</span>
  <span m='1462860'>that</span> <span m='1463530'>is</span> <span m='1463770'>the</span>
  <span m='1463900'>flat</span> <span m='1464270'>foldable</span> <span m='1464810'>mountain</span>
  <span m='1465070'>valley</span> <span m='1465360'>patterns.</span> <span m='1474750'>We're</span>
  <span m='1474910'>going</span> <span m='1475020'>to</span> <span m='1475090'>prove</span>
  <span m='1475300'>that</span> <span m='1475400'>crimps</span> <span m='1475590'>are</span>
  <span m='1475780'>enough,</span> <span m='1476100'>but</span> <span m='1476300'>before</span>
  <span m='1476600'>we</span> <span m='1476710'>get</span> <span m='1476920'>there,</span>
  <span m='1477190'>I</span> <span m='1477290'>need</span> <span m='1477320'>a</span>
  <span m='1477370'>bunch</span> <span m='1477630'>of</span> <span m='1477730'>sort</span>
  <span m='1477950'>of</span> <span m='1478020'>warm</span> <span m='1478310'>up</span>
  <span m='1478920'>facts</span> <span m='1479540'>about</span> <span m='1480070'>valid</span>
  <span m='1480990'>mountain</span> <span m='1481250'>valley</span> <span m='1481500'>patterns.</span>
  </p><p><span m='1483570'>The</span> <span m='1483660'>first</span> <span m='1483950'>thing</span>
  <span m='1485520'>is</span> <span m='1485660'>just</span> <span m='1485860'>counting</span>
  <span m='1486280'>mountains</span> <span m='1486610'>and</span> <span m='1486710'>valleys.</span>
  <span m='1489530'>So</span> <span m='1489630'>even</span> <span m='1489850'>if</span>
  <span m='1489960'>you</span> <span m='1490060'>play</span> <span m='1490280'>with</span>
  <span m='1490450'>a</span> <span m='1490500'>simple</span> <span m='1490800'>example</span>
  <span m='1491200'>like</span> <span m='1491370'>this</span> <span m='1491550'>one,</span>
  <span m='1492650'>you</span> <span m='1492750'>see</span> <span m='1493520'>it</span>
  <span m='1493730'>as</span> <span m='1494170'>three</span> <span m='1494570'>mountains</span>
  <span m='1495460'>and</span> <span m='1495750'>one</span> <span m='1495970'>valley</span>
  <span m='1496420'>or</span> <span m='1496910'>three</span> <span m='1497380'>valleys</span>
  <span m='1497880'>and</span> <span m='1498170'>one</span> <span m='1498350'>mountain.</span>
  <span m='1498790'>In</span> <span m='1498940'>fact,</span> <span m='1499980'>if</span>
  <span m='1501270'>you</span> <span m='1501360'>have</span> <span m='1501590'>a</span>
  <span m='1501740'>degree</span> <span m='1502060'>4</span> <span m='1502270'>vertex,</span>
  <span m='1502525'>with</span> <span m='1502780'>four</span> <span m='1503060'>creases</span>
  <span m='1503430'>emanating</span> <span m='1503790'>from</span> <span m='1503930'>that</span>
  <span m='1504100'>point,</span> <span m='1504780'>those</span> <span m='1504970'>are</span>
  <span m='1505000'>your</span> <span m='1505140'>only</span> <span m='1505340'>choices.</span>
  </p><p><span m='1506830'>You</span> <span m='1506960'>could</span> <span m='1507120'>try,</span>
  <span m='1507450'>for</span> <span m='1507590'>example,</span> <span m='1507980'>making
  it</span> <span m='1508360'>all</span> <span m='1508610'>valleys,</span> <span m='1509770'>and</span>
  <span m='1509950'>it--</span> <span m='1511360'>I</span> <span m='1511460'>mean,</span>
  <span m='1511760'>you</span> <span m='1511880'>can't</span> <span m='1512330'>do</span>
  <span m='1512480'>it.</span> <span m='1514350'>It's</span> <span m='1514500'>hard</span>
  <span m='1514690'>to</span> <span m='1514770'>demonstrate.</span> <span m='1516110'>You</span>
  <span m='1516290'>could</span> <span m='1516450'>try</span> <span m='1517020'>making</span>
  <span m='1517600'>it</span> <span m='1517770'>two</span> <span m='1518000'>mountains</span>
  <span m='1518360'>and two</span> <span m='1518660'>valleys.</span> <span m='1519200'>Maybe</span>
  <span m='1519420'>I</span> <span m='1519460'>try</span> <span m='1519630'>to</span>
  <span m='1519740'>do</span> <span m='1519870'>mountain</span> <span m='1520180'>mountain</span>
  <span m='1520450'>here</span> <span m='1521330'>and</span> <span m='1521500'>then</span>
  <span m='1521620'>somehow</span> <span m='1522320'>this is</span> <span m='1522400'>going
  to be</span> <span m='1522590'>valley</span> <span m='1522990'>valley</span> <span
  m='1523690'>there.</span> <span m='1523940'>It's</span> <span m='1524480'>no</span>
  <span m='1524640'>good.</span> </p><p><span m='1526740'>But</span> <span m='1527040'>what's</span>
  <span m='1527830'>happening</span> <span m='1528300'>here</span> <span m='1528610'>is</span>
  <span m='1528920'>that</span> <span m='1529160'>the</span> <span m='1529870'>number</span>
  <span m='1530170'>of</span> <span m='1530210'>mountains</span> <span m='1533620'>and</span>
  <span m='1533780'>the</span> <span m='1533840'>number</span> <span m='1534110'>valleys</span>
  <span m='1534720'>must</span> <span m='1535040'>differ</span> <span m='1536510'>by</span>
  <span m='1537170'>exactly</span> <span m='1537660'>two.</span> <span m='1539455'>It</span>
  <span m='1539930'>doesn't</span> <span m='1540470'>matter</span> <span m='1540790'>who's</span>
  <span m='1541000'>bigger.</span> <span m='1541920'>So</span> <span m='1542070'>the</span>
  <span m='1542160'>difference</span> <span m='1542470'>could</span> <span m='1542580'>be</span>
  <span m='1542700'>plus</span> <span m='1542960'>2</span> <span m='1543140'>or</span>
  <span m='1543230'>minus</span> <span m='1543600'>2,</span> <span m='1544140'>because</span>
  <span m='1544320'>you</span> <span m='1544440'>can</span> <span m='1544550'>always</span>
  <span m='1544710'>flip</span> <span m='1544950'>over</span> <span m='1545280'>and</span>
  <span m='1545330'>negate</span> <span m='1546420'>that</span> <span m='1546620'>difference,</span>
  <span m='1547500'>swapping</span> <span m='1547880'>mountains</span> <span m='1548200'>for</span>
  <span m='1548260'>valleys.</span> <span m='1549900'>But</span> <span m='1550280'>they</span>
  <span m='1550440'>always</span> <span m='1550650'>have</span> <span m='1550780'>to</span>
  <span m='1550870'>differ</span> <span m='1551130'>by</span> <span m='1551250'>exactly</span>
  <span m='1551700'>two.</span> <span m='1554590'>Why is</span> <span m='1554870'>that?</span>
  </p><p><span m='1556510'>Well,</span> <span m='1558530'>this</span> <span m='1558870'>is--</span>
  <span m='1560620'>yeah,</span> <span m='1561130'>we're</span> <span m='1561260'>again</span>
  <span m='1561580'>going</span> <span m='1561740'>to</span> <span m='1562180'>think</span>
  <span m='1562360'>of</span> <span m='1562460'>a</span> <span m='1562530'>picture</span>
  <span m='1562900'>like</span> <span m='1563150'>this.</span> <span m='1563990'>We</span>
  <span m='1564120'>have</span> <span m='1564230'>horizontal</span> <span m='1565320'>travel</span>
  <span m='1565680'>according</span> <span m='1566020'>to</span> <span m='1566120'>the</span>
  <span m='1566230'>theta</span> <span m='1566510'>i's.</span> <span m='1567140'>We're</span>
  <span m='1567300'>also</span> <span m='1567590'>going</span> <span m='1567700'>to</span>
  <span m='1567770'>think</span> <span m='1567970'>about</span> <span m='1568310'>the</span>
  <span m='1568370'>vertical</span> <span m='1568730'>picture.</span> <span m='1570290'>If</span>
  <span m='1570540'>this</span> <span m='1570730'>thing</span> <span m='1570910'>is</span>
  <span m='1571010'>flat</span> <span m='1571290'>foldable--</span> <span m='1571810'>so</span>
  <span m='1571970'>I'm</span> <span m='1572090'>assuming,</span> <span m='1572900'>it's
  flat</span> <span m='1573180'>foldable--</span> <span m='1573980'>then</span> <span
  m='1574180'>this</span> <span m='1574380'>must</span> <span m='1574640'>happen.</span>
  </p><p><span m='1576950'>This</span> <span m='1577090'>is</span> <span m='1577190'>called</span>
  <span m='1577380'>Maekawa's</span> <span m='1577960'>theorem,</span> <span m='1578260'>by</span>
  <span m='1578490'>the</span> <span m='1578590'>way.</span> <span m='1579850'>It
  was proved</span> <span m='1580020'>by</span> <span m='1581030'>Jun</span> <span
  m='1581250'>Maekawa</span> <span m='1581950'>in</span> <span m='1584660'>1986--</span>
  <span m='1587275'>a</span> <span m='1587750'>little</span> <span m='1587990'>earlier.</span>
  <span m='1589740'>Also</span> <span m='1590060'>proved</span> <span m='1590350'>by</span>
  <span m='1590700'>Jacques</span> <span m='1591160'>Justin</span> <span m='1591850'>around</span>
  <span m='1592120'>the</span> <span m='1592180'>same</span> <span m='1592390'>time--</span>
  <span m='1594560'>back</span> <span m='1594770'>before</span> <span m='1595130'>we</span>
  <span m='1595200'>were</span> <span m='1595340'>good</span> <span m='1595580'>at</span>
  <span m='1596220'>internet</span> <span m='1596680'>and</span> <span m='1596820'>communication</span>
  <span m='1597480'>and whatnot.</span> <span m='1599410'>And</span> <span m='1599650'>there</span>
  <span m='1599750'>were</span> <span m='1599840'>little</span> <span m='1600100'>pockets</span>
  <span m='1600980'>of</span> <span m='1601370'>mathematical</span> <span m='1601930'>origamists</span>
  <span m='1602650'>and</span> <span m='1603150'>they</span> <span m='1603250'>found</span>
  <span m='1603530'>each</span> <span m='1603690'>other</span> <span m='1604970'>basically
  in</span> <span m='1605350'>'89,</span> <span m='1606720'>when</span> <span m='1606890'>there</span>
  <span m='1607080'>was</span> <span m='1607250'>the--</span> <span m='1609270'>'89</span>
  <span m='1610060'>was</span> <span m='1610210'>the</span> <span m='1610320'>first</span>
  <span m='1610870'>origami</span> <span m='1611370'>science</span> <span m='1611730'>math</span>
  <span m='1611940'>and</span> <span m='1612020'>education</span> <span m='1612470'>conference--</span>
  <span m='1613410'>started</span> <span m='1613715'>bringing these</span> <span m='1614020'>people</span>
  <span m='1614250'>together.</span> <span m='1616010'>The</span> <span m='1616130'>last</span>
  <span m='1616400'>one</span> <span m='1616520'>was</span> <span m='1616690'>this</span>
  <span m='1616800'>summer.</span> </p><p><span m='1619830'>Right.</span> <span m='1620200'>So</span>
  <span m='1620390'>why</span> <span m='1620560'>is</span> <span m='1620670'>this</span>
  <span m='1620810'>true?</span> <span m='1627090'>I don't know.</span> <span m='1627360'>A</span>
  <span m='1627510'>flat</span> <span m='1627760'>folding</span> <span m='1628100'>looks</span>
  <span m='1628280'>like</span> <span m='1628450'>something.</span> </p><p><span m='1629730'>It</span>
  <span m='1629840'>has</span> <span m='1630020'>no</span> <span m='1630150'>crossings.</span>
  <span m='1631980'>It</span> <span m='1632130'>has--</span> <span m='1633020'>the</span>
  <span m='1633080'>horizontal</span> <span m='1633480'>travel,</span> <span m='1633800'>we</span>
  <span m='1633920'>understand.</span> <span m='1636020'>It</span> <span m='1636170'>ends</span>
  <span m='1636450'>up</span> <span m='1636720'>back where it</span> <span m='1637120'>started.</span>
  <span m='1637810'>There's</span> <span m='1638090'>also</span> <span m='1638430'>some</span>
  <span m='1638640'>notion</span> <span m='1638940'>of</span> <span m='1639030'>layers</span>
  <span m='1639520'>and</span> <span m='1639670'>vertical</span> <span m='1640660'>travel,</span>
  <span m='1641600'>which</span> <span m='1641710'>is</span> <span m='1641780'>a</span>
  <span m='1641820'>little</span> <span m='1642080'>tricky</span> <span m='1642400'>to</span>
  <span m='1642500'>think</span> <span m='1642690'>about.</span> </p><p><span m='1643850'>But</span>
  <span m='1643980'>the</span> <span m='1644070'>one</span> <span m='1644260'>thing</span>
  <span m='1644440'>that's</span> <span m='1644560'>easy</span> <span m='1644840'>to</span>
  <span m='1644930'>think</span> <span m='1645140'>about--</span> <span m='1645430'>I</span>
  <span m='1645450'>mean,</span> <span m='1645610'>this</span> <span m='1645770'>forms</span>
  <span m='1646210'>essentially a</span> <span m='1646670'>polygon.</span> <span m='1647240'>It's</span>
  <span m='1647480'>like</span> <span m='1647650'>a</span> <span m='1647710'>really</span>
  <span m='1647900'>squashed</span> <span m='1648340'>polygon.</span> <span m='1649080'>And</span>
  <span m='1649140'>these</span> <span m='1649290'>vertical</span> <span m='1650060'>segments</span>
  <span m='1650520'>are</span> <span m='1650670'>actually</span> <span m='1650970'>really</span>
  <span m='1651170'>just</span> <span m='1651720'>points.</span> <span m='1652940'>OK,</span>
  <span m='1653230'>imagine.</span> <span m='1655190'>That's</span> <span m='1655410'>just</span>
  <span m='1655590'>where</span> <span m='1655680'>you</span> <span m='1655770'>turn</span>
  <span m='1655970'>around.</span> </p><p><span m='1657250'>So</span> <span m='1657450'>it's
  like</span> <span m='1657680'>a</span> <span m='1657730'>polygon,</span> <span m='1658430'>just</span>
  <span m='1659410'>stretched</span> <span m='1660520'>or</span> <span m='1661020'>squashed</span>
  <span m='1661420'>down</span> <span m='1661890'>onto</span> <span m='1662200'>a</span>
  <span m='1662250'>line.</span> <span m='1663040'>And we</span> <span m='1663220'>know</span>
  <span m='1663340'>some</span> <span m='1663520'>things</span> <span m='1663730'>about</span>
  <span m='1663960'>polygons.</span> <span m='1666470'>OK,</span> <span m='1666620'>as
  an</span> <span m='1666730'>end</span> <span m='1666920'>vertex</span> <span m='1667280'>polygon--</span>
  <span m='1667860'>you know</span> <span m='1668120'>that</span> <span m='1668470'>the</span>
  <span m='1668540'>sum</span> <span m='1668790'>of</span> <span m='1668840'>the</span>
  <span m='1668910'>interior</span> <span m='1669360'>angles</span> <span m='1670070'>is--</span>
  <span m='1670880'>whatever</span> <span m='1671200'>it</span> <span m='1671250'>is.</span>
  <span m='1671740'>I</span> <span m='1671860'>always</span> <span m='1672040'>get</span>
  <span m='1672170'>confused</span> <span m='1672530'>with</span> <span m='1672590'>that</span>
  <span m='1672790'>formula.</span> <span m='1673330'>So</span> <span m='1673380'>I</span>
  <span m='1673410'>don't</span> <span m='1673580'>like</span> <span m='1673740'>to</span>
  <span m='1673840'>think</span> <span m='1674020'>about</span> <span m='1674260'>it.</span>
  </p><p><span m='1674570'>But</span> <span m='1674880'>one</span> <span m='1675120'>thing</span>
  <span m='1675510'>we--</span> <span m='1676070'>an</span> <span m='1676170'>easier</span>
  <span m='1676440'>way</span> <span m='1676540'>to</span> <span m='1676610'>think</span>
  <span m='1676770'>about</span> <span m='1676990'>that</span> <span m='1677200'>same</span>
  <span m='1677500'>statement</span> <span m='1678720'>is</span> <span m='1678900'>just</span>
  <span m='1679080'>think</span> <span m='1679240'>about</span> <span m='1679440'>how</span>
  <span m='1679570'>much</span> <span m='1679810'>turning</span> <span m='1680200'>the</span>
  <span m='1680280'>polygon</span> <span m='1680760'>does.</span> <span m='1681550'>So
  you</span> <span m='1681730'>start</span> <span m='1681980'>here,</span> <span m='1683010'>you</span>
  <span m='1683090'>turn</span> <span m='1683380'>right</span> <span m='1683670'>180</span>
  <span m='1684150'>degrees,</span> <span m='1684480'>you</span> <span m='1684690'>turn</span>
  <span m='1685000'>left</span> <span m='1685340'>180</span> <span m='1685730'>degrees,</span>
  <span m='1686300'>you</span> <span m='1686450'>turn</span> <span m='1686720'>left</span>
  <span m='1687020'>180,</span> <span m='1687880'>right</span> <span m='1688130'>180,</span>
  <span m='1688720'>right</span> <span m='1688950'>180,</span> <span m='1689760'>right</span>
  <span m='1689980'>180.</span> <span m='1690630'>How</span> <span m='1690800'>much</span>
  <span m='1691030'>is</span> <span m='1691160'>it</span> <span m='1691250'>in</span>
  <span m='1691370'>total?</span> <span m='1692420'>Oh gosh,</span> <span m='1693100'>do
  I</span> <span m='1693270'>have</span> <span m='1693400'>to</span> <span m='1693510'>add?</span>
  <span m='1694570'>No.</span> </p><p><span m='1695550'>It's</span> <span m='1695750'>so</span>
  <span m='1695870'>simple.</span> <span m='1696250'>It's</span> <span m='1696400'>360.</span>
  <span m='1697400'>Right?</span> <span m='1697580'>Just,</span> <span m='1697800'>if</span>
  <span m='1697960'>you</span> <span m='1698050'>think</span> <span m='1698270'>about</span>
  <span m='1698630'>if</span> <span m='1698990'>you're</span> <span m='1699120'>going</span>
  <span m='1699340'>around</span> <span m='1699590'>in</span> <span m='1699680'>a</span>
  <span m='1699730'>circle,</span> <span m='1700930'>any</span> <span m='1701210'>polygon--</span>
  <span m='1701710'>not</span> <span m='1701870'>just</span> <span m='1702050'>flat--</span>
  <span m='1702380'>but</span> <span m='1702520'>anything</span> <span m='1702910'>in</span>
  <span m='1703630'>two</span> <span m='1703780'>dimensions,</span> <span m='1705270'>the</span>
  <span m='1705460'>total</span> <span m='1705740'>amount</span> <span m='1705970'>of</span>
  <span m='1706070'>turning</span> <span m='1706470'>you</span> <span m='1706590'>do</span>
  <span m='1706760'>is</span> <span m='1706870'>360.</span> <span m='1707450'>Or</span>
  <span m='1707580'>if</span> <span m='1707640'>you</span> <span m='1707750'>count</span>
  <span m='1708000'>backwards,</span> <span m='1708520'>it's</span> <span m='1708820'>negative</span>
  <span m='1709160'>360.</span> </p><p><span m='1710960'>So</span> <span m='1711290'>this</span>
  <span m='1711510'>is</span> <span m='1711660'>the</span> <span m='1711750'>key--</span>
  <span m='1712570'>something</span> <span m='1712850'>you</span> <span m='1712930'>should</span>
  <span m='1713100'>all</span> <span m='1713320'>know</span> <span m='1714050'>about</span>
  <span m='1714540'>polygons.</span> <span m='1715120'>If</span> <span m='1715230'>you</span>
  <span m='1715520'>look</span> <span m='1715700'>at</span> <span m='1715770'>sum</span>
  <span m='1716160'>of</span> <span m='1716240'>the</span> <span m='1716330'>turn</span>
  <span m='1716580'>angles--</span> <span m='1716990'>how</span> <span m='1717140'>much</span>
  <span m='1717340'>turning</span> <span m='1717630'>you</span> <span m='1717740'>do</span>
  <span m='1717890'>at</span> <span m='1717950'>each</span> <span m='1718110'>vertex--</span>
  <span m='1719080'>that</span> <span m='1719250'>will</span> <span m='1719380'>always</span>
  <span m='1719720'>be</span> <span m='1720280'>plus</span> <span m='1720530'>or</span>
  <span m='1720580'>minus</span> <span m='1720890'>360</span> <span m='1722250'>in</span>
  <span m='1722410'>any</span> <span m='1722600'>polygon.</span> <span m='1727390'>This</span>
  <span m='1727570'>is</span> <span m='1727670'>equivalent</span> <span m='1728160'>to</span>
  <span m='1728250'>the</span> <span m='1728380'>sum</span> <span m='1728600'>of</span>
  <span m='1728650'>the</span> <span m='1728730'>interior</span> <span m='1729100'>angles</span>
  <span m='1729490'>being,</span> <span m='1729880'>whatever,</span> <span m='1730230'>pi</span>
  <span m='1730450'>times</span> <span m='1730710'>n</span> <span m='1730800'>minus</span>
  <span m='1731090'>2,</span> <span m='1731740'>which</span> <span m='1731860'>I</span>
  <span m='1731920'>don't</span> <span m='1732080'>remember.</span> <span m='1732820'>But</span>
  <span m='1733790'>this</span> <span m='1733970'>is</span> <span m='1734080'>much</span>
  <span m='1734310'>easier</span> <span m='1734600'>to</span> <span m='1734690'>remember.</span>
  </p><p><span m='1736660'>And</span> <span m='1737560'>it's</span> <span m='1737790'>useful,</span>
  <span m='1738150'>because</span> <span m='1738770'>we</span> <span m='1738980'>can</span>
  <span m='1739180'>map</span> <span m='1739710'>mountains</span> <span m='1740050'>and</span>
  <span m='1740150'>valleys</span> <span m='1740980'>to</span> <span m='1741220'>left</span>
  <span m='1741470'>and</span> <span m='1741540'>right</span> <span m='1741730'>turns.</span>
  <span m='1742040'>As</span> <span m='1742190'>I</span> <span m='1742250'>said,</span>
  <span m='1742520'>every</span> <span m='1742770'>time</span> <span m='1742990'>this</span>
  <span m='1743150'>is</span> <span m='1743280'>a</span> <span m='1743320'>valley,</span>
  <span m='1744510'>it</span> <span m='1744640'>was</span> <span m='1744890'>a</span>
  <span m='1747040'>left</span> <span m='1747480'>turn</span> <span m='1747700'>by</span>
  <span m='1747840'>180.</span> <span m='1748750'>Every</span> <span m='1748970'>time</span>
  <span m='1749150'>it</span> <span m='1749170'>was</span> <span m='1749310'>a</span>
  <span m='1749350'>mountain,</span> <span m='1749730'>it</span> <span m='1749810'>was</span>
  <span m='1749930'>a</span> <span m='1750010'>right</span> <span m='1750220'>turn</span>
  <span m='1750420'>by</span> <span m='1750540'>180.</span> <span m='1751905'>So</span>
  <span m='1752360'>valleys,</span> <span m='1762980'>mountains,</span> <span m='1771580'>right</span>
  <span m='1771880'>turns--</span> <span m='1772790'>so</span> <span m='1773030'>I'm
  going to</span> <span m='1773060'>think</span> <span m='1773260'>of</span> <span
  m='1773350'>that as</span> <span m='1773550'>negative</span> <span m='1773900'>180.</span>
  </p><p><span m='1775290'>Now,</span> <span m='1775570'>of</span> <span m='1775700'>course</span>
  <span m='1775910'>technically,</span> <span m='1776370'>it could</span> <span m='1776520'>be</span>
  <span m='1776720'>the</span> <span m='1776850'>other</span> <span m='1776990'>way</span>
  <span m='1777090'>around.</span> <span m='1777410'>It could</span> <span m='1777550'>be</span>
  <span m='1777650'>this</span> <span m='1777840'>is</span> <span m='1777940'>negative,</span>
  <span m='1778290'>this</span> <span m='1778460'>is</span> <span m='1778550'>positive.</span>
  <span m='1779120'>But</span> <span m='1780270'>I</span> <span m='1780420'>already</span>
  <span m='1780600'>have</span> <span m='1780750'>a</span> <span m='1780820'>plus</span>
  <span m='1781070'>and</span> <span m='1781160'>minus</span> <span m='1781520'>here.</span>
  <span m='1781740'>So</span> <span m='1781930'>it's</span> <span m='1782080'>symmetric.</span>
  </p><p><span m='1784340'>So</span> <span m='1784820'>if</span> <span m='1784980'>we</span>
  <span m='1785080'>sum</span> <span m='1785360'>up</span> <span m='1785490'>the</span>
  <span m='1785600'>turn</span> <span m='1785850'>angles--</span> <span m='1786240'>which</span>
  <span m='1786380'>we</span> <span m='1786510'>know</span> <span m='1786700'>is</span>
  <span m='1786790'>supposed</span> <span m='1787160'>to</span> <span m='1787220'>be</span>
  <span m='1787360'>plus</span> <span m='1787630'>or</span> <span m='1787680'>minus</span>
  <span m='1787960'>360--</span> <span m='1789080'>the</span> <span m='1789440'>sum</span>
  <span m='1789770'>of</span> <span m='1789820'>the</span> <span m='1789920'>turn</span>
  <span m='1790160'>angles</span> <span m='1795580'>is</span> <span m='1795810'>going</span>
  <span m='1795960'>to</span> <span m='1796060'>be--</span> <span m='1797210'>we're</span>
  <span m='1797360'>going</span> <span m='1797500'>to</span> <span m='1797550'>have</span>
  <span m='1798340'>180</span> <span m='1800130'>for</span> <span m='1800390'>each</span>
  <span m='1801530'>valley,</span> <span m='1802290'>so</span> <span m='1802660'>180</span>
  <span m='1803090'>times the</span> <span m='1803380'>number of</span> <span m='1803620'>valleys.</span>
  <span m='1806050'>And</span> <span m='1806170'>we're</span> <span m='1806270'>going</span>
  <span m='1806350'>to</span> <span m='1806390'>have</span> <span m='1806600'>negative</span>
  <span m='1806940'>180</span> <span m='1808670'>for</span> <span m='1808840'>each</span>
  <span m='1809070'>mountain.</span> <span m='1815860'>And</span> <span m='1816220'>so</span>
  <span m='1816610'>the</span> <span m='1816690'>180's</span> <span m='1817180'>factor</span>
  <span m='1817490'>out.</span> <span m='1830740'>And</span> <span m='1830890'>this</span>
  <span m='1831080'>thing</span> <span m='1831240'>is</span> <span m='1831310'>supposed</span>
  <span m='1831660'>to</span> <span m='1831700'>equal</span> <span m='1831960'>360--</span>
  <span m='1834350'>plus</span> <span m='1834590'>or</span> <span m='1834640'>minus</span>
  <span m='1834960'>360.</span> </p><p><span m='1836080'>How</span> <span m='1836300'>could</span>
  <span m='1836420'>that</span> <span m='1836610'>be?</span> <span m='1837540'>Well,</span>
  <span m='1837720'>the number of</span> <span m='1837970'>valleys</span> <span m='1838320'>minus</span>
  <span m='1838610'>number of</span> <span m='1838790'>mountains</span> <span m='1839090'>should</span>
  <span m='1839270'>be</span> <span m='1839750'>either</span> <span m='1840000'>2--</span>
  <span m='1840290'>for</span> <span m='1840440'>plus</span> <span m='1840740'>360--</span>
  <span m='1841170'>or</span> <span m='1841240'>negative</span> <span m='1841570'>2--</span>
  <span m='1841810'>for</span> <span m='1841950'>minus</span> <span m='1842240'>360.</span>
  <span m='1844040'>So</span> <span m='1844230'>that</span> <span m='1844430'>proves
  the</span> <span m='1844740'>theorem.</span> </p><p><span m='1849250'>And</span>
  <span m='1849380'>that's</span> <span m='1849570'>why,</span> <span m='1849820'>in</span>
  <span m='1849890'>a</span> <span m='1849950'>degree</span> <span m='1850240'>4</span>
  <span m='1850480'>vertex,</span> <span m='1851320'>one</span> <span m='1851580'>of
  them</span> <span m='1851670'>has</span> <span m='1851850'>to</span> <span m='1851910'>be</span>
  <span m='1852040'>3,</span> <span m='1852300'>the</span> <span m='1852420'>other</span>
  <span m='1852550'>one</span> <span m='1852650'>has</span> <span m='1852830'>to</span>
  <span m='1852900'>be</span> <span m='1853040'>1.</span> <span m='1854860'>There's</span>
  <span m='1855010'>no</span> <span m='1855150'>other</span> <span m='1855350'>option,</span>
  <span m='1856280'>because</span> <span m='1856460'>the</span> <span m='1856670'>total</span>
  <span m='1856920'>number is</span> <span m='1857320'>4.</span> <span m='1858400'>It's
  the</span> <span m='1858500'>only</span> <span m='1858690'>way</span> <span m='1858820'>to</span>
  <span m='1858890'>get</span> <span m='1859040'>the</span> <span m='1859120'>difference</span>
  <span m='1859530'>to be</span> <span m='1859660'>plus</span> <span m='1859930'>or</span>
  <span m='1859970'>minus</span> <span m='1860260'>2.</span> <span m='1862260'>So</span>
  <span m='1862470'>that's</span> <span m='1862910'>kind</span> <span m='1863260'>of</span>
  <span m='1863390'>nice.</span> </p><p><span m='1864890'>But</span> <span m='1865030'>it's</span>
  <span m='1865140'>not</span> <span m='1865340'>enough,</span> <span m='1865670'>unfortunately.</span>
  <span m='1866530'>If</span> <span m='1866700'>I</span> <span m='1866760'>gave</span>
  <span m='1867020'>you</span> <span m='1867210'>a</span> <span m='1867250'>mountain</span>
  <span m='1867510'>valley</span> <span m='1867800'>pattern</span> <span m='1868140'>that</span>
  <span m='1868280'>satisfies</span> <span m='1868890'>this</span> <span m='1869070'>condition,</span>
  <span m='1870150'>it</span> <span m='1870270'>still</span> <span m='1870590'>might</span>
  <span m='1870790'>not</span> <span m='1870970'>be</span> <span m='1871100'>flat</span>
  <span m='1871520'>foldable.</span> <span m='1874120'>That's</span> <span m='1874290'>maybe</span>
  <span m='1874540'>no</span> <span m='1874670'>surprise.</span> <span m='1875380'>It's</span>
  <span m='1875430'>not</span> <span m='1875600'>like</span> <span m='1875790'>we</span>
  <span m='1875900'>had</span> <span m='1876680'>such</span> <span m='1876960'>a</span>
  <span m='1877010'>simple</span> <span m='1877380'>test</span> <span m='1877830'>for</span>
  <span m='1878160'>the</span> <span m='1878440'>one</span> <span m='1878610'>dimensional</span>
  <span m='1879020'>case, which</span> <span m='1879500'>should</span> <span m='1879690'>be</span>
  <span m='1879850'>easier.</span> </p><p><span m='1880670'>We</span> <span m='1880810'>had</span>
  <span m='1880970'>to</span> <span m='1881020'>give</span> <span m='1881150'>an</span>
  <span m='1881250'>algorithm.</span> <span m='1881940'>We</span> <span m='1882040'>said</span>
  <span m='1882190'>repeatedly</span> <span m='1882760'>crimp and</span> <span m='1883130'>end
  fold.</span> <span m='1883920'>If</span> <span m='1883960'>you</span> <span m='1884050'>get</span>
  <span m='1884240'>stuck,</span> <span m='1885100'>the</span> <span m='1885210'>answer
  is</span> <span m='1885530'>no.</span> <span m='1885910'>If</span> <span m='1886010'>you</span>
  <span m='1886090'>don't</span> <span m='1886250'>get</span> <span m='1886360'>stuck,</span>
  <span m='1886990'>you</span> <span m='1887090'>folded</span> <span m='1887430'>it</span>
  <span m='1887570'>great.</span> </p><p><span m='1903280'>I love</span> <span m='1903340'>this</span>
  <span m='1903530'>eraser--</span> <span m='1904610'>increases</span> <span m='1905110'>entropy.</span>
  <span m='1911110'>Let</span> <span m='1911250'>me</span> <span m='1911350'>tell</span>
  <span m='1911500'>you</span> <span m='1911640'>one</span> <span m='1911830'>case</span>
  <span m='1912120'>that</span> <span m='1912250'>is</span> <span m='1912450'>easy</span>
  <span m='1913930'>to</span> <span m='1914030'>think</span> <span m='1914230'>about.</span>
  <span m='1915040'>Because</span> <span m='1915540'>it's</span> <span m='1915950'>nice.</span>
  <span m='1916340'>It</span> <span m='1916530'>reduces</span> <span m='1917000'>directly</span>
  <span m='1917380'>to</span> <span m='1917490'>the</span> <span m='1917590'>one</span>
  <span m='1917740'>dimensional</span> <span m='1918120'>case.</span> <span m='1919140'>And</span>
  <span m='1919220'>that's</span> <span m='1919380'>what</span> <span m='1919490'>I</span>
  <span m='1919540'>call</span> <span m='1919960'>the</span> <span m='1920090'>generic</span>
  <span m='1920590'>case.</span> </p><p><span m='1926380'>Generic</span> <span m='1926900'>is</span>
  <span m='1927010'>this</span> <span m='1927170'>very</span> <span m='1927380'>convenient</span>
  <span m='1927920'>term</span> <span m='1928170'>we use in</span> <span m='1928440'>mathematics.</span>
  <span m='1929010'>It's</span> <span m='1929140'>actually</span> <span m='1929410'>really</span>
  <span m='1929620'>tricky</span> <span m='1929990'>to</span> <span m='1930110'>define.</span>
  <span m='1932450'>So</span> <span m='1932630'>I'd</span> <span m='1932740'>like</span>
  <span m='1932890'>to</span> <span m='1933160'>not</span> <span m='1933390'>define</span>
  <span m='1933710'>it,</span> <span m='1934090'>if</span> <span m='1934270'>I</span>
  <span m='1934340'>can.</span> <span m='1935260'>But</span> <span m='1935760'>maybe</span>
  <span m='1936080'>I</span> <span m='1936140'>should.</span> </p><p><span m='1942320'>The</span>
  <span m='1942460'>simple</span> <span m='1942760'>version,</span> <span m='1943460'>which</span>
  <span m='1943600'>is</span> <span m='1943690'>not</span> <span m='1943870'>quite</span>
  <span m='1944060'>enough,</span> <span m='1944410'>is</span> <span m='1944570'>to</span>
  <span m='1944660'>say</span> <span m='1944870'>that</span> <span m='1945070'>all</span>
  <span m='1945420'>of</span> <span m='1945600'>the</span> <span m='1945780'>angles</span>
  <span m='1946210'>in</span> <span m='1946270'>the</span> <span m='1946360'>crease</span>
  <span m='1946580'>pattern</span> <span m='1946920'>are</span> <span m='1947000'>different.</span>
  <span m='1949150'>OK,</span> <span m='1949310'>here,</span> <span m='1949620'>for</span>
  <span m='1949760'>example,</span> <span m='1950190'>two</span> <span m='1950340'>of</span>
  <span m='1950390'>them</span> <span m='1950550'>are</span> <span m='1950590'>the</span>
  <span m='1950670'>same.</span> <span m='1950990'>There's</span> <span m='1951090'>two
  90</span> <span m='1951450'>degree</span> <span m='1951670'>angles.</span> <span
  m='1951920'>This</span> <span m='1952060'>is</span> <span m='1952140'>not</span>
  <span m='1952310'>generic.</span> <span m='1952990'>It's</span> <span m='1953080'>just</span>
  <span m='1953270'>easier</span> <span m='1953590'>to</span> <span m='1953670'>draw.</span>
  </p><p><span m='1955030'>But</span> <span m='1955180'>in</span> <span m='1955280'>general,</span>
  <span m='1955990'>I</span> <span m='1956090'>mean,</span> <span m='1956260'>you</span>
  <span m='1956350'>imagine,</span> <span m='1956770'>you</span> <span m='1956860'>just</span>
  <span m='1957010'>draw</span> <span m='1957210'>some</span> <span m='1957440'>random</span>
  <span m='1957750'>thing.</span> <span m='1959110'>None</span> <span m='1959330'>of</span>
  <span m='1959410'>those</span> <span m='1959630'>lengths</span> <span m='1959890'>are</span>
  <span m='1959950'>going</span> <span m='1960070'>to</span> <span m='1960130'>be</span>
  <span m='1960330'>the same.</span> <span m='1961080'>Yeah,</span> <span m='1961460'>the</span>
  <span m='1961610'>alternating</span> <span m='1962070'>sum</span> <span m='1962400'>is</span>
  <span m='1962510'>zero.</span> <span m='1962920'>But</span> <span m='1963870'>that's</span>
  <span m='1964100'>it.</span> </p><p><span m='1965330'>And</span> <span m='1965500'>that's</span>
  <span m='1965670'>what</span> <span m='1965810'>I--</span> <span m='1966100'>the</span>
  <span m='1966190'>generic</span> <span m='1966550'>case is</span> <span m='1967030'>that</span>
  <span m='1967200'>is</span> <span m='1967330'>the</span> <span m='1967510'>only</span>
  <span m='1967980'>thing</span> <span m='1968900'>that</span> <span m='1969010'>holds</span>
  <span m='1969260'>true</span> <span m='1969530'>about</span> <span m='1969830'>these</span>
  <span m='1970500'>angles.</span> <span m='1970870'>You</span> <span m='1971030'>can</span>
  <span m='1971170'>take</span> <span m='1971340'>the</span> <span m='1971440'>alternating</span>
  <span m='1971870'>sum.</span> <span m='1972670'>That</span> <span m='1972850'>equals</span>
  <span m='1973110'>zero.</span> <span m='1973990'>If</span> <span m='1974190'>you</span>
  <span m='1974420'>take</span> <span m='1974680'>some</span> <span m='1974850'>alternating</span>
  <span m='1975230'>sum</span> <span m='1975525'>of some</span> <span m='1975820'>subset</span>
  <span m='1976200'>of</span> <span m='1976260'>the</span> <span m='1976330'>angles,</span>
  <span m='1976680'>that</span> <span m='1976840'>will</span> <span m='1976980'>not</span>
  <span m='1977180'>equal</span> <span m='1977440'>zero.</span> <span m='1978190'>If</span>
  <span m='1978300'>you</span> <span m='1978360'>take</span> <span m='1978580'>a</span>
  <span m='1978690'>random</span> <span m='1979040'>example,</span> <span m='1979490'>this</span>
  <span m='1979660'>is</span> <span m='1979750'>going</span> <span m='1979880'>to</span>
  <span m='1979940'>be</span> <span m='1980060'>true.</span> </p><p><span m='1980760'>OK,</span>
  <span m='1981180'>just</span> <span m='1981870'>bear</span> <span m='1982060'>with</span>
  <span m='1982220'>me.</span> <span m='1982700'>Suppose</span> <span m='1983550'>never</span>
  <span m='1983990'>any</span> <span m='1984150'>two</span> <span m='1984310'>angles</span>
  <span m='1984660'>are</span> <span m='1984740'>the</span> <span m='1984860'>same.</span>
  <span m='1986760'>Then</span> <span m='1988190'>look</span> <span m='1988500'>at</span>
  <span m='1988680'>the</span> <span m='1989090'>globally</span> <span m='1989680'>smallest</span>
  <span m='1990270'>crease,</span> <span m='1991230'>so</span> <span m='1991670'>globally</span>
  <span m='1992010'>smallest</span> <span m='1992800'>theta.</span> <span m='1998380'>Say</span>
  <span m='1998530'>it's</span> <span m='1998710'>theta</span> <span m='1998970'>i.</span>
  <span m='2000000'>So the</span> <span m='2000090'>picture</span> <span m='2000460'>is</span>
  <span m='2002250'>theta</span> <span m='2002580'>i,</span> <span m='2003700'>theta</span>
  <span m='2004220'>i</span> <span m='2004280'>minus</span> <span m='2004610'>1,</span>
  <span m='2005930'>theta</span> <span m='2006230'>i</span> <span m='2006320'>plus</span>
  <span m='2006610'>1.</span> </p><p><span m='2008100'>And</span> <span m='2008240'>what</span>
  <span m='2008360'>do</span> <span m='2008430'>we</span> <span m='2008540'>know</span>
  <span m='2008820'>if</span> <span m='2008940'>it's</span> <span m='2009080'>globally</span>
  <span m='2009460'>smallest</span> <span m='2009950'>and</span> <span m='2010020'>none</span>
  <span m='2010160'>of</span> <span m='2010240'>the</span> <span m='2010310'>values</span>
  <span m='2010720'>are</span> <span m='2010850'>equal?</span> <span m='2012080'>Then</span>
  <span m='2012170'>we</span> <span m='2012280'>know</span> <span m='2013100'>that</span>
  <span m='2014660'>these</span> <span m='2014870'>two</span> <span m='2015130'>are</span>
  <span m='2015240'>bigger.</span> <span m='2018035'>No</span> <span m='2018500'>big</span>
  <span m='2018630'>surprise.</span> </p><p><span m='2020250'>Think</span> <span m='2020490'>about</span>
  <span m='2020770'>what</span> <span m='2020920'>happens</span> <span m='2022220'>if</span>
  <span m='2022380'>this</span> <span m='2022600'>is</span> <span m='2022710'>small,</span>
  <span m='2023670'>these</span> <span m='2023810'>are</span> <span m='2023880'>bigger,</span>
  <span m='2024780'>and</span> <span m='2024950'>you</span> <span m='2025030'>try</span>
  <span m='2025240'>to</span> <span m='2025330'>make</span> <span m='2025520'>these</span>
  <span m='2025700'>both</span> <span m='2025980'>valleys</span> <span m='2027580'>or</span>
  <span m='2027720'>both</span> <span m='2027940'>mountains,</span> <span m='2028890'>that's,</span>
  <span m='2029060'>of</span> <span m='2029170'>course,</span> <span m='2029850'>bad.</span>
  <span m='2030200'>This</span> <span m='2030390'>is</span> <span m='2030540'>one</span>
  <span m='2030710'>of</span> <span m='2030830'>the</span> <span m='2033990'>situations</span>
  <span m='2034590'>we</span> <span m='2034680'>had</span> <span m='2034860'>in</span>
  <span m='2034950'>the</span> <span m='2035030'>one</span> <span m='2035180'>dimensional</span>
  <span m='2035580'>case.</span> <span m='2036380'>I</span> <span m='2036470'>mean,</span>
  <span m='2036660'>really,</span> <span m='2036880'>this</span> <span m='2037050'>is</span>
  <span m='2037150'>a</span> <span m='2037210'>circle,</span> <span m='2037930'>but</span>
  <span m='2037970'>I</span> <span m='2038020'>can</span> <span m='2038180'>think</span>
  <span m='2038360'>just</span> <span m='2038530'>locally</span> <span m='2038880'>about</span>
  <span m='2039070'>what's</span> <span m='2039240'>happening</span> <span m='2039570'>here.</span>
  </p><p><span m='2040640'>So</span> <span m='2040750'>in</span> <span m='2040930'>this</span>
  <span m='2041100'>situation,</span> <span m='2042340'>one</span> <span m='2042580'>of</span>
  <span m='2042640'>these</span> <span m='2042810'>must</span> <span m='2043120'>be</span>
  <span m='2043250'>a</span> <span m='2043290'>mountain</span> <span m='2043990'>and</span>
  <span m='2044170'>the</span> <span m='2044280'>other</span> <span m='2044420'>must</span>
  <span m='2044640'>be a</span> <span m='2044750'>valley.</span> <span m='2045890'>I</span>
  <span m='2046000'>don't</span> <span m='2046130'>know</span> <span m='2046250'>which</span>
  <span m='2046470'>order</span> <span m='2046690'>they</span> <span m='2046870'>are,</span>
  <span m='2048360'>but</span> <span m='2048480'>I</span> <span m='2048540'>know</span>
  <span m='2048679'>they're</span> <span m='2048790'>different.</span> <span m='2050040'>And</span>
  <span m='2050219'>then</span> <span m='2050389'>I</span> <span m='2050460'>know</span>
  <span m='2051139'>I</span> <span m='2051280'>can</span> <span m='2051429'>apply</span>
  <span m='2052480'>one</span> <span m='2052630'>of</span> <span m='2052699'>these</span>
  <span m='2052889'>crimps.</span> </p><p><span m='2055670'>Incidentally,</span> <span
  m='2057420'>the</span> <span m='2057520'>word</span> <span m='2057710'>crimp,</span>
  <span m='2058080'>Jason</span> <span m='2058409'>Koo</span> <span m='2058610'>was</span>
  <span m='2058739'>asking</span> <span m='2059100'>about,</span> <span m='2059330'>like,</span>
  <span m='2059489'>why</span> <span m='2059650'>do</span> <span m='2059690'>you</span>
  <span m='2059790'>call</span> <span m='2060020'>it</span> <span m='2060110'>crimp</span>
  <span m='2060510'>and</span> <span m='2060650'>not</span> <span m='2060889'>pleat?</span>
  <span m='2062120'>Probably,</span> <span m='2062510'>I</span> <span m='2062580'>should</span>
  <span m='2062739'>call</span> <span m='2062920'>it</span> <span m='2063030'>pleat.</span>
  <span m='2063639'>But</span> <span m='2064739'>it's</span> <span m='2065090'>crimp</span>
  <span m='2065380'>in</span> <span m='2065469'>my</span> <span m='2065590'>mind.</span>
  <span m='2065940'>It's</span> <span m='2066060'>been</span> <span m='2066210'>crimp</span>
  <span m='2066440'>in</span> <span m='2066530'>my</span> <span m='2066659'>mind</span>
  <span m='2066969'>since</span> <span m='2067210'>1998</span> <span m='2067980'>when</span>
  <span m='2068150'>we</span> <span m='2068270'>wrote</span> <span m='2068840'>the</span>
  <span m='2068949'>1D</span> <span m='2069230'>paper.</span> <span m='2069750'>It
  was</span> <span m='2070179'>before</span> <span m='2070510'>I</span> <span m='2070550'>knew</span>
  <span m='2070690'>the</span> <span m='2070800'>word</span> <span m='2071000'>pleat,</span>
  <span m='2071780'>so</span> <span m='2072050'>that's</span> <span m='2072260'>my</span>
  <span m='2072429'>excuse.</span> </p><p><span m='2073480'>So</span> <span m='2073850'>pleat</span>
  <span m='2074130'>or crimp,</span> <span m='2074550'>take</span> <span m='2074719'>your</span>
  <span m='2074820'>pick.</span> <span m='2075710'>Crimp</span> <span m='2075929'>is</span>
  <span m='2076030'>usually</span> <span m='2076389'>many</span> <span m='2076630'>pleats</span>
  <span m='2076889'>together.</span> <span m='2077620'>That's</span> <span m='2077909'>crimping.</span>
  <span m='2081190'>Cool.</span> </p><p><span m='2081870'>So</span> <span m='2082239'>crimps,</span>
  <span m='2082600'>we</span> <span m='2082909'>kind</span> <span m='2083040'>of</span>
  <span m='2083170'>like.</span> <span m='2084090'>Why</span> <span m='2084320'>do</span>
  <span m='2084460'>we</span> <span m='2084580'>like</span> <span m='2085070'>crimps?</span>
  <span m='2088820'>We</span> <span m='2089020'>proved,</span> <span m='2089610'>in</span>
  <span m='2089900'>the</span> <span m='2090000'>one</span> <span m='2090219'>dimensional</span>
  <span m='2090610'>case</span> <span m='2090889'>last</span> <span m='2091179'>time,</span>
  <span m='2091550'>that</span> <span m='2092360'>if</span> <span m='2092540'>you</span>
  <span m='2092670'>make</span> <span m='2092900'>a</span> <span m='2092960'>crimp</span>
  <span m='2093600'>and</span> <span m='2093710'>your</span> <span m='2093820'>original</span>
  <span m='2094159'>thing</span> <span m='2094320'>was</span> <span m='2094429'>flat</span>
  <span m='2094670'>foldable,</span> <span m='2095270'>the</span> <span m='2095370'>new</span>
  <span m='2095520'>thing</span> <span m='2095760'>will</span> <span m='2095880'>be</span>
  <span m='2096010'>flat</span> <span m='2096260'>foldable.</span> <span m='2097690'>Good</span>
  <span m='2097870'>news</span> <span m='2098080'>is,</span> <span m='2098360'>that</span>
  <span m='2098560'>is</span> <span m='2098650'>still</span> <span m='2098910'>true.</span>
  </p><p><span m='2100030'>I</span> <span m='2100130'>told</span> <span m='2100340'>you,</span>
  <span m='2100420'>all</span> <span m='2100560'>these</span> <span m='2100700'>things</span>
  <span m='2100890'>were</span> <span m='2100960'>no</span> <span m='2101140'>longer</span>
  <span m='2101470'>true</span> <span m='2101650'>in</span> <span m='2101720'>the</span>
  <span m='2101790'>circular</span> <span m='2102190'>case.</span> <span m='2102840'>It's</span>
  <span m='2103020'>still</span> <span m='2103220'>true</span> <span m='2103430'>in</span>
  <span m='2103500'>the</span> <span m='2103590'>circular</span> <span m='2103970'>case.</span>
  <span m='2106500'>Should I</span> <span m='2106780'>tell</span> <span m='2107000'>you--</span>
  </p><p><span m='2107500'>Let</span> <span m='2107720'>me</span> <span m='2107810'>just</span>
  <span m='2108000'>remind</span> <span m='2108270'>you--</span> <span m='2108440'>the</span>
  <span m='2108510'>same</span> <span m='2108730'>proof</span> <span m='2108960'>works--</span>
  <span m='2109760'>remind</span> <span m='2110080'>you</span> <span m='2110180'>what</span>
  <span m='2110290'>the</span> <span m='2110370'>proof</span> <span m='2110610'>looked</span>
  <span m='2110780'>like.</span> <span m='2111620'>We</span> <span m='2111730'>had</span>
  <span m='2111890'>a</span> <span m='2111960'>crimp,</span> <span m='2114740'>and</span>
  <span m='2114910'>we're</span> <span m='2115020'>hoping</span> <span m='2115380'>to</span>
  <span m='2115440'>fold</span> <span m='2115690'>that</span> <span m='2115960'>first.</span>
  <span m='2116900'>We</span> <span m='2117000'>know</span> <span m='2117200'>at</span>
  <span m='2117300'>some</span> <span m='2117470'>point,</span> <span m='2117660'>these</span>
  <span m='2117820'>creases</span> <span m='2118140'>get</span> <span m='2118290'>folded.</span>
  <span m='2119160'>But</span> <span m='2119330'>there</span> <span m='2119430'>may</span>
  <span m='2119580'>be</span> <span m='2119760'>other</span> <span m='2119990'>junk</span>
  <span m='2120350'>in</span> <span m='2120440'>here,</span> <span m='2120990'>or</span>
  <span m='2121290'>maybe</span> <span m='2121630'>other</span> <span m='2121780'>junk</span>
  <span m='2122060'>in</span> <span m='2122150'>here.</span> <span m='2123110'>We'd</span>
  <span m='2123360'>like</span> <span m='2123530'>to</span> <span m='2123610'>get</span>
  <span m='2123780'>rid</span> <span m='2123930'>of</span> <span m='2124020'>that</span>
  <span m='2124220'>junk.</span> </p><p><span m='2124950'>And</span> <span m='2125100'>so
  what</span> <span m='2125280'>we</span> <span m='2125430'>did</span> <span m='2125610'>is</span>
  <span m='2125720'>move</span> <span m='2125920'>this</span> <span m='2126150'>junk</span>
  <span m='2126840'>up</span> <span m='2127010'>to</span> <span m='2127130'>here,</span>
  <span m='2127480'>which</span> <span m='2127650'>was</span> <span m='2127810'>always</span>
  <span m='2128020'>safe.</span> <span m='2128360'>We</span> <span m='2128450'>moved</span>
  <span m='2128650'>this</span> <span m='2128850'>junk</span> <span m='2129180'>down
  to</span> <span m='2129450'>here.</span> <span m='2130400'>And</span> <span m='2130960'>that</span>
  <span m='2131570'>was</span> <span m='2131730'>still</span> <span m='2132000'>a</span>
  <span m='2132040'>folded</span> <span m='2132400'>state--</span> <span m='2132880'>a
  flat</span> <span m='2133140'>folded</span> <span m='2133410'>state.</span> <span
  m='2135598'>OK,</span> <span m='2136000'>remember</span> <span m='2136430'>all</span>
  <span m='2136540'>this</span> <span m='2136950'>stuff.</span> </p><p><span m='2138980'>Therefore,</span>
  <span m='2139320'>we</span> <span m='2139450'>could</span> <span m='2139660'>have
  folded</span> <span m='2140030'>the</span> <span m='2140110'>crimp</span> <span
  m='2140320'>first.</span> <span m='2141190'>And</span> <span m='2141340'>then</span>
  <span m='2141480'>we</span> <span m='2141560'>have</span> <span m='2141680'>a</span>
  <span m='2141730'>flat</span> <span m='2142020'>folding</span> <span m='2142950'>in</span>
  <span m='2143120'>this</span> <span m='2143280'>situation,</span> <span m='2143880'>where</span>
  <span m='2144010'>this</span> <span m='2144570'>paper is</span> <span m='2145000'>effectively</span>
  <span m='2145590'>glued</span> <span m='2145830'>together,</span> <span m='2147570'>which</span>
  <span m='2147830'>means,</span> <span m='2148220'>it</span> <span m='2148340'>was</span>
  <span m='2148480'>safe</span> <span m='2148820'>to</span> <span m='2148930'>fold</span>
  <span m='2149170'>this</span> <span m='2149340'>crimp</span> <span m='2149800'>and</span>
  <span m='2150140'>glue</span> <span m='2150290'>these</span> <span m='2150480'>together</span>
  <span m='2150890'>and</span> <span m='2150980'>never</span> <span m='2151230'>touch</span>
  <span m='2151490'>them</span> <span m='2151600'>again.</span> <span m='2152980'>So</span>
  <span m='2153050'>that is</span> <span m='2153310'>still</span> <span m='2153500'>true</span>
  <span m='2153750'>in</span> <span m='2153880'>the</span> <span m='2153960'>circular</span>
  <span m='2154400'>case.</span> <span m='2154620'>That</span> <span m='2154770'>proof</span>
  <span m='2155000'>didn't</span> <span m='2155280'>really</span> <span m='2155470'>assume</span>
  <span m='2155920'>anything</span> <span m='2156300'>about</span> <span m='2156520'>the</span>
  <span m='2156600'>paper.</span> <span m='2157740'>Would</span> <span m='2157870'>even</span>
  <span m='2158060'>work</span> <span m='2158260'>for</span> <span m='2158440'>like</span>
  <span m='2158660'>tree</span> <span m='2158880'>shaped</span> <span m='2159290'>paper
  or</span> <span m='2159740'>something</span> <span m='2160030'>weird.</span> </p><p><span
  m='2162670'>So</span> <span m='2162910'>if</span> <span m='2163000'>we</span> <span
  m='2163110'>can</span> <span m='2163240'>find</span> <span m='2163500'>a</span>
  <span m='2163530'>crimp,</span> <span m='2164390'>which</span> <span m='2164610'>we</span>
  <span m='2164760'>can</span> <span m='2165040'>in</span> <span m='2165120'>the</span>
  <span m='2165210'>generic</span> <span m='2165570'>case,</span> <span m='2166610'>then</span>
  <span m='2166820'>you</span> <span m='2166910'>just</span> <span m='2167160'>make
  a</span> <span m='2167270'>crimp,</span> <span m='2167620'>make</span> <span m='2167810'>a</span>
  <span m='2167870'>crimp,</span> <span m='2168120'>repeat.</span> <span m='2168690'>If</span>
  <span m='2168840'>you</span> <span m='2168940'>ever</span> <span m='2169120'>get</span>
  <span m='2169280'>stuck,</span> <span m='2169610'>you</span> <span m='2169690'>know</span>
  <span m='2169890'>that</span> <span m='2170060'>the</span> <span m='2170140'>original</span>
  <span m='2170500'>thing</span> <span m='2170650'>was</span> <span m='2170830'>not</span>
  <span m='2171050'>flat</span> <span m='2171480'>foldable,</span> <span m='2171640'>because</span>
  <span m='2171810'>the</span> <span m='2171900'>thing</span> <span m='2172040'>you</span>
  <span m='2172130'>have</span> <span m='2172370'>is</span> <span m='2172460'>not</span>
  <span m='2172660'>flat</span> <span m='2172840'>foldable.</span> <span m='2175810'>Why?</span>
  <span m='2176380'>If</span> <span m='2176560'>there's</span> <span m='2176730'>no</span>
  <span m='2176920'>cramp</span> <span m='2177240'>in</span> <span m='2177330'>the</span>
  <span m='2177420'>generic</span> <span m='2177820'>case,</span> <span m='2178620'>that</span>
  <span m='2178750'>means</span> <span m='2178910'>you</span> <span m='2179000'>have</span>
  <span m='2179110'>two</span> <span m='2179280'>valleys</span> <span m='2179990'>around</span>
  <span m='2180310'>the</span> <span m='2180370'>smallest</span> <span m='2180790'>angle,</span>
  <span m='2181740'>and</span> <span m='2181980'>that's</span> <span m='2182180'>clearly</span>
  <span m='2182610'>bad.</span> </p><p><span m='2186020'>So--</span> <span m='2187270'>I'm</span>
  <span m='2187370'>not</span> <span m='2187520'>writing</span> <span m='2187710'>a</span>
  <span m='2187760'>lot</span> <span m='2187900'>of</span> <span m='2187950'>details</span>
  <span m='2188360'>here.</span> <span m='2188610'>Is</span> <span m='2188660'>that</span>
  <span m='2188820'>clear?</span> <span m='2191040'>If</span> <span m='2191250'>I</span>
  <span m='2191340'>have</span> <span m='2191880'>an</span> <span m='2192020'>angle</span>
  <span m='2192380'>that's</span> <span m='2192630'>surrounded</span> <span m='2192950'>by</span>
  <span m='2193070'>strictly</span> <span m='2193510'>larger</span> <span m='2193880'>angles,</span>
  <span m='2194170'>I</span> <span m='2194290'>know</span> <span m='2195130'>there</span>
  <span m='2195220'>must</span> <span m='2195460'>be</span> <span m='2195670'>one</span>
  <span m='2195900'>mountain and</span> <span m='2196160'>one</span> <span m='2196330'>valley.</span>
  <span m='2196660'>Then</span> <span m='2196820'>I</span> <span m='2196890'>can</span>
  <span m='2197040'>safely</span> <span m='2197370'>make</span> <span m='2197570'>a</span>
  <span m='2197630'>crimp</span> <span m='2198040'>and</span> <span m='2198130'>repeat.</span>
  </p><p><span m='2199600'>The</span> <span m='2199720'>trouble</span> <span m='2200140'>comes</span>
  <span m='2200450'>in</span> <span m='2200700'>when</span> <span m='2200870'>these</span>
  <span m='2201180'>angles</span> <span m='2201710'>are</span> <span m='2201890'>equal.</span>
  <span m='2203500'>We</span> <span m='2203650'>never</span> <span m='2203910'>had</span>
  <span m='2204060'>to</span> <span m='2204160'>think</span> <span m='2204560'>about</span>
  <span m='2205040'>angles</span> <span m='2205360'>being</span> <span m='2205530'>equal</span>
  <span m='2205780'>in</span> <span m='2205910'>the</span> <span m='2206000'>one</span>
  <span m='2206150'>dimensional</span> <span m='2206550'>case.</span> <span m='2206830'>It</span>
  <span m='2206900'>didn't</span> <span m='2207180'>matter</span> <span m='2207460'>much.</span>
  <span m='2209090'>We</span> <span m='2209270'>just</span> <span m='2209450'>said,</span>
  <span m='2210075'>oh,</span> <span m='2210370'>you</span> <span m='2210510'>know,</span>
  <span m='2210850'>it's</span> <span m='2211030'>safe</span> <span m='2211240'>to</span>
  <span m='2211340'>make</span> <span m='2211520'>a</span> <span m='2211590'>crimp,</span>
  <span m='2212400'>as</span> <span m='2212590'>long</span> <span m='2212850'>as</span>
  <span m='2213330'>this</span> <span m='2213600'>was</span> <span m='2213780'>greater</span>
  <span m='2214100'>than</span> <span m='2214280'>or</span> <span m='2214410'>equal</span>
  <span m='2214660'>to</span> <span m='2214830'>this</span> <span m='2215490'>and</span>
  <span m='2215770'>this</span> <span m='2215940'>was</span> <span m='2216060'>greater</span>
  <span m='2216310'>than</span> <span m='2216390'>or</span> <span m='2216440'>equal</span>
  <span m='2216660'>to</span> <span m='2216770'>this.</span> <span m='2217740'>That</span>
  <span m='2217930'>is</span> <span m='2218010'>still</span> <span m='2218210'>true;</span>
  <span m='2218380'>it's</span> <span m='2218550'>safe</span> <span m='2218770'>to</span>
  <span m='2218880'>make</span> <span m='2219070'>a</span> <span m='2219130'>crimp.</span>
  </p><p><span m='2220030'>But</span> <span m='2220190'>how</span> <span m='2220460'>do</span>
  <span m='2220550'>we</span> <span m='2220690'>know</span> <span m='2220880'>that</span>
  <span m='2221040'>there</span> <span m='2221230'>is</span> <span m='2221330'>a</span>
  <span m='2221400'>crimp?</span> <span m='2221700'>How</span> <span m='2221860'>do</span>
  <span m='2221940'>we</span> <span m='2222050'>know  that</span> <span m='2222190'>there's</span>
  <span m='2222450'>a</span> <span m='2222510'>mountain</span> <span m='2222800'>followed</span>
  <span m='2223110'>by</span> <span m='2223270'>valley?</span> <span m='2225720'>We</span>
  <span m='2226070'>don't.</span> <span m='2226420'>I</span> <span m='2226500'>mean,</span>
  <span m='2226640'>if</span> <span m='2226750'>they're</span> <span m='2226840'>equal,</span>
  <span m='2227860'>this</span> <span m='2228390'>would</span> <span m='2228530'>be</span>
  <span m='2228690'>all</span> <span m='2228780'>right.</span> <span m='2231400'>That's</span>
  <span m='2231800'>two</span> <span m='2232200'>valleys</span> <span m='2232670'>is</span>
  <span m='2232790'>valid</span> <span m='2233220'>if</span> <span m='2233400'>these</span>
  <span m='2233590'>three</span> <span m='2233820'>angles</span> <span m='2234140'>are</span>
  <span m='2234220'>equal.</span> </p><p><span m='2234580'>But</span> <span m='2234890'>I</span>
  <span m='2235030'>claim</span> <span m='2235400'>still</span> <span m='2235680'>somewhere</span>
  <span m='2236160'>there's</span> <span m='2236330'>got</span> <span m='2236490'>to</span>
  <span m='2236560'>be</span> <span m='2236690'>a</span> <span m='2236760'>crimp.</span>
  <span m='2237430'>There's</span> <span m='2237590'>no</span> <span m='2237740'>longer</span>
  <span m='2238110'>a</span> <span m='2238150'>notion</span> <span m='2238420'>of</span>
  <span m='2238470'>the</span> <span m='2238540'>globally</span> <span m='2238880'>smallest</span>
  <span m='2239270'>angle,</span> <span m='2239560'>because</span> <span m='2239780'>some</span>
  <span m='2239960'>of</span> <span m='2240020'>them</span> <span m='2240170'>are</span>
  <span m='2240220'>equal.</span> <span m='2241380'>We've</span> <span m='2241470'>got</span>
  <span m='2241590'>to</span> <span m='2241640'>find</span> <span m='2241950'>that</span>
  <span m='2242150'>crimp,</span> <span m='2242480'>but</span> <span m='2242670'>it's</span>
  <span m='2242830'>out</span> <span m='2243020'>there.</span> <span m='2244770'>So</span>
  <span m='2245200'>we</span> <span m='2245280'>just</span> <span m='2245500'>need</span>
  <span m='2245640'>to</span> <span m='2245920'>prove</span> <span m='2246250'>that</span>
  <span m='2246580'>it</span> <span m='2246800'>exists.</span> </p><p><span m='2277960'>So</span>
  <span m='2278100'>to</span> <span m='2278240'>do</span> <span m='2278480'>that,</span>
  <span m='2279220'>we're</span> <span m='2279480'>going</span> <span m='2279740'>to</span>
  <span m='2279890'>generalize</span> <span m='2280620'>this</span> <span m='2281360'>theorem--</span>
  <span m='2282670'>Meakawa-Justin--</span> <span m='2284220'>that</span> <span m='2284530'>number</span>
  <span m='2284780'>of mountains</span> <span m='2285080'>minus</span> <span m='2285350'>number
  of</span> <span m='2285530'>valleys is</span> <span m='2285990'>plus</span> <span
  m='2286240'>or</span> <span m='2286290'>minus</span> <span m='2286550'>2.</span>
  <span m='2286730'>That's</span> <span m='2286980'>true,</span> <span m='2288200'>and</span>
  <span m='2288470'>it's a</span> <span m='2288530'>statement</span> <span m='2288930'>about</span>
  <span m='2289180'>the sum</span> <span m='2289580'>of</span> <span m='2291260'>all</span>
  <span m='2291610'>the</span> <span m='2291750'>angles--</span> <span m='2292390'>all
  of</span> <span m='2292660'>the</span> <span m='2292760'>creases.</span> <span m='2293710'>What</span>
  <span m='2293860'>I'd</span> <span m='2293970'>like is</span> <span m='2294220'>something</span>
  <span m='2294630'>a</span> <span m='2294660'>little</span> <span m='2294910'>bit</span>
  <span m='2295080'>more</span> <span m='2295350'>localized.</span> <span m='2296820'>And</span>
  <span m='2297010'>in</span> <span m='2297070'>particular,</span> <span m='2297680'>we're</span>
  <span m='2297780'>going</span> <span m='2297880'>to</span> <span m='2297980'>think</span>
  <span m='2298080'>about</span> <span m='2298770'>when</span> <span m='2298930'>I</span>
  <span m='2298970'>have</span> <span m='2299240'>a</span> <span m='2299270'>whole</span>
  <span m='2299600'>bunch</span> <span m='2299920'>of</span> <span m='2300540'>angles</span>
  <span m='2300970'>that</span> <span m='2301090'>are</span> <span m='2301240'>equal,</span>
  <span m='2302530'>how</span> <span m='2302650'>many</span> <span m='2302870'>mountains</span>
  <span m='2303210'>and</span> <span m='2303300'>valleys</span> <span m='2303640'>can</span>
  <span m='2303810'>there</span> <span m='2303920'>be</span> <span m='2304110'>in</span>
  <span m='2304230'>there.</span> <span m='2307480'>So</span> <span m='2308772'>it's</span>
  <span m='2309140'>what I</span> <span m='2309260'>call</span> <span m='2309750'>local</span>
  <span m='2310120'>counts.</span> </p><p><span m='2315170'>So</span> <span m='2315350'>while</span>
  <span m='2315600'>everything</span> <span m='2315950'>I</span> <span m='2316010'>said</span>
  <span m='2316240'>so</span> <span m='2316370'>far</span> <span m='2316590'>is</span>
  <span m='2316700'>pretty</span> <span m='2316890'>classic,</span> <span m='2317770'>this</span>
  <span m='2317960'>result</span> <span m='2319050'>was proved</span> <span m='2319320'>in</span>
  <span m='2319750'>2001</span> <span m='2320760'>by</span> <span m='2320900'>Tom</span>
  <span m='2321160'>Hall,</span> <span m='2321560'>so</span> <span m='2321860'>much</span>
  <span m='2322070'>more</span> <span m='2322250'>recent,</span> <span m='2324930'>over</span>
  <span m='2325110'>a</span> <span m='2325150'>decade</span> <span m='2325520'>later.</span>
  <span m='2328580'>So</span> <span m='2328790'>let's</span> <span m='2329020'>think</span>
  <span m='2329240'>about</span> <span m='2330580'>k</span> <span m='2331460'>equal</span>
  <span m='2331860'>angles.</span> <span m='2338640'>And</span> <span m='2338900'>I</span>
  <span m='2338930'>want</span> <span m='2339180'>that</span> <span m='2339370'>to</span>
  <span m='2339450'>be</span> <span m='2339580'>a</span> <span m='2339630'>maximal</span>
  <span m='2340260'>sequence</span> <span m='2340790'>of</span> <span m='2340950'>equal
  angles,</span> <span m='2341400'>so</span> <span m='2341640'>the</span> <span m='2341760'>ones</span>
  <span m='2342130'>right</span> <span m='2342410'>after</span> <span m='2342830'>and</span>
  <span m='2342900'>right</span> <span m='2343110'>before</span> <span m='2344010'>are</span>
  <span m='2344210'>different.</span> <span m='2345560'>And</span> <span m='2345830'>furthermore,</span>
  <span m='2347030'>I'm</span> <span m='2347200'>going</span> <span m='2347320'>to</span>
  <span m='2347390'>assume that</span> <span m='2347710'>they're</span> <span m='2347840'>bigger--</span>
  <span m='2356090'>strictly</span> <span m='2358010'>larger</span> <span m='2360210'>angles.</span>
  </p><p><span m='2363320'>OK,</span> <span m='2363560'>so</span> <span m='2367680'>something</span>
  <span m='2367960'>like</span> <span m='2368140'>that.</span> <span m='2368710'>A</span>
  <span m='2369050'>bunch</span> <span m='2369270'>of</span> <span m='2369350'>equal</span>
  <span m='2369650'>angles--</span> <span m='2370060'>k</span> <span m='2370300'>of</span>
  <span m='2370400'>them--</span> <span m='2371230'>bigger</span> <span m='2371520'>angles</span>
  <span m='2371850'>on</span> <span m='2371980'>either</span> <span m='2372200'>side.</span>
  <span m='2373960'>This</span> <span m='2374240'>almost</span> <span m='2374620'>always</span>
  <span m='2375160'>exists.</span> <span m='2376660'>I</span> <span m='2376730'>should</span>
  <span m='2376950'>mention--</span> <span m='2378010'>so</span> <span m='2378110'>I'm</span>
  <span m='2378220'>going</span> <span m='2378340'>to</span> <span m='2378390'>say</span>
  <span m='2378600'>something</span> <span m='2378890'>about</span> <span m='2379170'>this</span>
  <span m='2379280'>situation.</span> </p><p><span m='2379930'>But</span> <span m='2380060'>this</span>
  <span m='2380160'>situation</span> <span m='2380690'>should</span> <span m='2380870'>exist,</span>
  <span m='2381270'>because</span> <span m='2381960'>I</span> <span m='2382050'>take</span>
  <span m='2382270'>the</span> <span m='2382350'>smallest</span> <span m='2382820'>angle</span>
  <span m='2383130'>out</span> <span m='2383300'>there</span> <span m='2384090'>and</span>
  <span m='2384280'>then</span> <span m='2384440'>I</span> <span m='2384620'>see</span>
  <span m='2384940'>how</span> <span m='2385100'>many</span> <span m='2385320'>friends</span>
  <span m='2385630'>it has</span> <span m='2385700'>that</span> <span m='2386010'>are</span>
  <span m='2386160'>all</span> <span m='2386300'>equal.</span> <span m='2387270'>If</span>
  <span m='2387420'>it's</span> <span m='2387550'>the</span> <span m='2387610'>smallest</span>
  <span m='2388070'>angle--</span> <span m='2389100'>or</span> <span m='2389210'>it's</span>
  <span m='2389310'>one</span> <span m='2389520'>of</span> <span m='2389590'>the</span>
  <span m='2389670'>smallest</span> <span m='2390070'>angles--</span> <span m='2390910'>then</span>
  <span m='2391250'>the</span> <span m='2391410'>ones</span> <span m='2392330'>surrounding</span>
  <span m='2392900'>it</span> <span m='2393100'>are</span> <span m='2393200'>going</span>
  <span m='2393330'>to</span> <span m='2393380'>be</span> <span m='2393500'>bigger--</span>
  <span m='2394660'>unless</span> <span m='2396980'>all</span> <span m='2397280'>the</span>
  <span m='2397400'>angles</span> <span m='2397700'>are</span> <span m='2397790'>equal.</span>
  <span m='2398530'>So</span> <span m='2398730'>there's</span> <span m='2398910'>one</span>
  <span m='2399140'>case,</span> <span m='2399530'>which</span> <span m='2399630'>we'll</span>
  <span m='2399870'>worry</span> <span m='2400060'>about</span> <span m='2400280'>later.</span>
  <span m='2400590'>It's</span> <span m='2400770'>very</span> <span m='2401000'>easy.</span>
  <span m='2401690'>All</span> <span m='2401890'>the</span> <span m='2401990'>angles</span>
  <span m='2402240'>are</span> <span m='2402330'>equal.</span> </p><p><span m='2404410'>In</span>
  <span m='2404460'>fact,</span> <span m='2404700'>I</span> <span m='2404750'>could</span>
  <span m='2404890'>tell</span> <span m='2405020'>you</span> <span m='2405210'>how</span>
  <span m='2405380'>to</span> <span m='2405460'>worry</span> <span m='2405620'>about</span>
  <span m='2405860'>that.</span> <span m='2406280'>If</span> <span m='2406450'>all</span>
  <span m='2406720'>the</span> <span m='2406830'>angles</span> <span m='2407140'>are</span>
  <span m='2407230'>equal,</span> <span m='2409450'>then</span> <span m='2410530'>everything</span>
  <span m='2411350'>is</span> <span m='2411510'>crimpable</span> <span m='2411950'>as</span>
  <span m='2412020'>long</span> <span m='2412240'>as</span> <span m='2412330'>we</span>
  <span m='2412440'>can</span> <span m='2412580'>find</span> <span m='2412880'>a</span>
  <span m='2412930'>switch</span> <span m='2413240'>between</span> <span m='2413550'>mountain</span>
  <span m='2413820'>and</span> <span m='2413930'>valley--</span> <span m='2414760'>somewhere.</span>
  <span m='2416420'>And</span> <span m='2416650'>because</span> <span m='2417020'>the</span>
  <span m='2417060'>number</span> <span m='2417300'>of</span> <span m='2417340'>mountains</span>
  <span m='2417650'>and</span> <span m='2417740'>valleys</span> <span m='2418100'>is</span>
  <span m='2418210'>plus</span> <span m='2418440'>or</span> <span m='2418490'>minus</span>
  <span m='2418770'>2,</span> <span m='2419540'>there's</span> <span m='2419720'>got</span>
  <span m='2419940'>to</span> <span m='2420000'>be--</span> <span m='2420600'>so</span>
  <span m='2420790'>they're</span> <span m='2420990'>almost</span> <span m='2421660'>in</span>
  <span m='2421820'>equal</span> <span m='2422380'>balance--</span> <span m='2423100'>there's</span>
  <span m='2423290'>got</span> <span m='2423500'>to</span> <span m='2423570'>be</span>
  <span m='2425440'>a</span> <span m='2425540'>valley.</span> <span m='2425960'>It</span>
  <span m='2426070'>can't</span> <span m='2426280'>be</span> <span m='2426400'>all</span>
  <span m='2426550'>valleys,</span> <span m='2427390'>can't</span> <span m='2427590'>be</span>
  <span m='2427720'>all</span> <span m='2427860'>mountains.</span> </p><p><span m='2428220'>So</span>
  <span m='2428380'>somewhere,</span> <span m='2428730'>there's</span> <span m='2428900'>a</span>
  <span m='2428950'>transition</span> <span m='2429400'>between</span> <span m='2429720'>mountain</span>
  <span m='2429990'>and</span> <span m='2430090'>valley.</span> <span m='2431180'>So</span>
  <span m='2431350'>you</span> <span m='2431480'>get</span> <span m='2431650'>a</span>
  <span m='2431720'>crimp</span> <span m='2432210'>out</span> <span m='2432330'>of</span>
  <span m='2432390'>that.</span> <span m='2434490'>But</span> <span m='2434700'>otherwise,</span>
  <span m='2435055'>if</span> <span m='2435410'>they're</span> <span m='2435560'>not</span>
  <span m='2435830'>all</span> <span m='2436130'>equal--</span> <span m='2436940'>let's</span>
  <span m='2437110'>think</span> <span m='2437270'>about</span> <span m='2437500'>k</span>
  <span m='2439150'>equal</span> <span m='2439460'>angles</span> <span m='2439830'>surrounded</span>
  <span m='2440090'>by</span> <span m='2440430'>two</span> <span m='2440620'>larger</span>
  <span m='2440910'>guys.</span> <span m='2443230'>Forgot</span> <span m='2443330'>how</span>
  <span m='2443490'>technical</span> <span m='2443870'>this</span> <span m='2444060'>is.</span>
  </p><p><span m='2445370'>All</span> <span m='2445460'>right.</span> <span m='2445820'>Then</span>
  <span m='2450870'>I</span> <span m='2450990'>want</span> <span m='2451220'>to</span>
  <span m='2451300'>look</span> <span m='2451560'>at</span> <span m='2451790'>the</span>
  <span m='2451870'>number</span> <span m='2452240'>of</span> <span m='2452290'>mountains</span>
  <span m='2452770'>and</span> <span m='2452840'>the</span> <span m='2452900'>number</span>
  <span m='2453170'>valleys</span> <span m='2454570'>among</span> <span m='2455050'>these</span>
  <span m='2455980'>k</span> <span m='2456230'>plus</span> <span m='2456530'>one</span>
  <span m='2456720'>creases,</span> <span m='2458020'>so</span> <span m='2458490'>within</span>
  <span m='2458910'>that</span> <span m='2459120'>range.</span> <span m='2464130'>It's</span>
  <span m='2464380'>going</span> <span m='2464500'>to</span> <span m='2464550'>be</span>
  <span m='2464650'>0,</span> <span m='2466300'>if</span> <span m='2466760'>k</span>
  <span m='2466970'>is</span> <span m='2467120'>odd.</span> <span m='2470160'>And
  it's</span> <span m='2470330'>going</span> <span m='2470430'>to</span> <span m='2470480'>be</span>
  <span m='2470600'>plus</span> <span m='2470880'>or</span> <span m='2470930'>minus</span>
  <span m='2471250'>1,</span> <span m='2472250'>if k</span> <span m='2472640'>is</span>
  <span m='2472900'>even.</span> </p><p><span m='2477140'>It's not</span> <span m='2477350'>plus</span>
  <span m='2477720'>or</span> <span m='2477770'>minus</span> <span m='2478060'>2.</span>
  <span m='2478730'>Intuitively,</span> <span m='2479560'>plus</span> <span m='2479820'>or</span>
  <span m='2479860'>minus</span> <span m='2480130'>2</span> <span m='2480360'>is</span>
  <span m='2480480'>when</span> <span m='2480610'>you</span> <span m='2480700'>go</span>
  <span m='2480840'>all</span> <span m='2481010'>the</span> <span m='2481070'>way</span>
  <span m='2481170'>around.</span> <span m='2482130'>Here,</span> <span m='2482410'>we're</span>
  <span m='2482510'>just</span> <span m='2482710'>looking</span> <span m='2483020'>at</span>
  <span m='2484280'>a segment--</span> <span m='2484580'>a</span> <span m='2484880'>portion</span>
  <span m='2485310'>of</span> <span m='2485430'>the</span> <span m='2485500'>entire</span>
  <span m='2485850'>circle.</span> <span m='2487260'>Remember,</span> <span m='2487560'>this</span>
  <span m='2487750'>is</span> <span m='2487890'>actually</span> <span m='2488170'>a</span>
  <span m='2488220'>circle</span> <span m='2488690'>somewhere.</span> </p><p><span
  m='2490730'>And</span> <span m='2492600'>this</span> <span m='2492970'>corresponds</span>
  <span m='2493540'>to,</span> <span m='2494270'>in</span> <span m='2494400'>the</span>
  <span m='2494490'>odd</span> <span m='2494740'>case,</span> <span m='2495190'>you're</span>
  <span m='2495230'>going</span> <span m='2495380'>to</span> <span m='2495480'>be</span>
  <span m='2495670'>going</span> <span m='2496130'>in</span> <span m='2496340'>the</span>
  <span m='2496460'>same</span> <span m='2496740'>direction</span> <span m='2497190'>afterwards.</span>
  <span m='2498280'>In</span> <span m='2498500'>the</span> <span m='2498640'>even</span>
  <span m='2498970'>case,</span> <span m='2499280'>you're</span> <span m='2499410'>going</span>
  <span m='2499520'>to</span> <span m='2499580'>have</span> <span m='2499900'>turned</span>
  <span m='2500375'>around</span> <span m='2500850'>but</span> <span m='2501000'>not</span>
  <span m='2501170'>a</span> <span m='2501210'>full</span> <span m='2501390'>circle.</span>
  <span m='2501870'>So</span> <span m='2501900'>it's</span> <span m='2502040'>going</span>
  <span m='2502140'>to</span> <span m='2502190'>be</span> <span m='2502300'>plus</span>
  <span m='2502570'>or</span> <span m='2502620'>minus</span> <span m='2502890'>1.</span>
  </p><p><span m='2503890'>There's</span> <span m='2504070'>a</span> <span m='2504140'>lot</span>
  <span m='2504320'>of</span> <span m='2504370'>ways</span> <span m='2504580'>to</span>
  <span m='2504680'>prove</span> <span m='2504940'>this.</span> <span m='2506740'>One</span>
  <span m='2506900'>way</span> <span m='2507100'>is</span> <span m='2507220'>to</span>
  <span m='2507320'>think</span> <span m='2507510'>about</span> <span m='2507760'>convex</span>
  <span m='2508190'>cones.</span> <span m='2510770'>So</span> <span m='2515068'>if
  k</span> <span m='2515520'>is</span> <span m='2515910'>even,</span> <span m='2517930'>and
  you</span> <span m='2518070'>fold</span> <span m='2518350'>this</span> <span m='2518540'>thing--</span>
  <span m='2520210'>let's see,</span> <span m='2520570'>one,</span> <span m='2520950'>two,</span>
  <span m='2521050'>three,</span> <span m='2521250'>four,</span> <span m='2521740'>five,</span>
  <span m='2522540'>six--</span> <span m='2525560'>equal</span> <span m='2525920'>angles.</span>
  <span m='2526480'>And</span> <span m='2526650'>then</span> <span m='2526920'>there's</span>
  <span m='2527130'>the</span> <span m='2527220'>two</span> <span m='2527380'>longer</span>
  <span m='2527670'>guys.</span> <span m='2527950'>They</span> <span m='2528030'>may</span>
  <span m='2528140'>not</span> <span m='2528300'>be</span> <span m='2528380'>the</span>
  <span m='2528480'>same</span> <span m='2528730'>length,</span> <span m='2529750'>but
  that's</span> <span m='2529960'>what</span> <span m='2530030'>you</span> <span m='2530170'>get</span>
  <span m='2530320'>in the</span> <span m='2530550'>even</span> <span m='2530830'>case.</span>
  </p><p><span m='2533660'>So</span> <span m='2533910'>what</span> <span m='2534050'>I'd</span>
  <span m='2534130'>like</span> <span m='2534300'>to</span> <span m='2534400'>do</span>
  <span m='2535130'>is</span> <span m='2535970'>just,</span> <span m='2537740'>in</span>
  <span m='2537930'>order</span> <span m='2538120'>to</span> <span m='2538260'>just</span>
  <span m='2538450'>reduce</span> <span m='2538800'>to</span> <span m='2538870'>things</span>
  <span m='2539130'>that</span> <span m='2539220'>we've</span> <span m='2539360'>already</span>
  <span m='2539590'>thought</span> <span m='2539810'>about--</span> <span m='2540100'>I</span>
  <span m='2540130'>mean,</span> <span m='2540280'>you</span> <span m='2540380'>could</span>
  <span m='2540520'>talk</span> <span m='2540730'>about</span> <span m='2540940'>turn</span>
  <span m='2541120'>angles</span> <span m='2541390'>again,</span> <span m='2542020'>or</span>
  <span m='2542190'>you</span> <span m='2542250'>could</span> <span m='2542340'>just</span>
  <span m='2542470'>say,</span> <span m='2542650'>hey,</span> <span m='2543250'>I</span>
  <span m='2543420'>know</span> <span m='2543880'>Maekawa's</span> <span m='2544175'>theorem.</span>
  <span m='2545040'>So</span> <span m='2545250'>as</span> <span m='2545340'>long</span>
  <span m='2545540'>as</span> <span m='2545670'>I</span> <span m='2545730'>could</span>
  <span m='2545910'>make</span> <span m='2546090'>this</span> <span m='2546250'>into</span>
  <span m='2546480'>a</span> <span m='2546540'>circle,</span> <span m='2548080'>which</span>
  <span m='2548100'>I</span> <span m='2548180'>can</span> <span m='2548340'>do</span>
  <span m='2548580'>by</span> <span m='2549790'>adding</span> <span m='2550090'>that</span>
  <span m='2550310'>stuff,</span> <span m='2551710'>now</span> <span m='2551860'>I</span>
  <span m='2551940'>have</span> <span m='2552140'>a</span> <span m='2552190'>nice</span>
  <span m='2552580'>circular--</span> <span m='2553690'>it's</span> <span m='2553870'>a</span>
  <span m='2553920'>flat</span> <span m='2554170'>folded</span> <span m='2554340'>state.</span>
  </p><p><span m='2554620'>There's</span> <span m='2554760'>no</span> <span m='2554890'>crossings</span>
  <span m='2555330'>here,</span> <span m='2557330'>presumably</span> <span m='2557980'>because</span>
  <span m='2558310'>this</span> <span m='2558590'>did</span> <span m='2558770'>something.</span>
  <span m='2559210'>I</span> <span m='2559230'>don't</span> <span m='2559390'>actually</span>
  <span m='2559640'>know</span> <span m='2559780'>that</span> <span m='2559900'>it's</span>
  <span m='2560080'>zigzagging.</span> <span m='2560540'>It</span> <span m='2560650'>might</span>
  <span m='2560840'>do</span> <span m='2561000'>other</span> <span m='2561230'>stuff.</span>
  <span m='2562140'>But</span> <span m='2562360'>it's</span> <span m='2562540'>not</span>
  <span m='2562690'>going</span> <span m='2562780'>to</span> <span m='2562840'>cross</span>
  <span m='2563180'>what</span> <span m='2563320'>I</span> <span m='2563390'>just</span>
  <span m='2563590'>added.</span> </p><p><span m='2565410'>So</span> <span m='2565490'>the</span>
  <span m='2565590'>number</span> <span m='2565920'>of</span> <span m='2566150'>mountains</span>
  <span m='2566490'>minus</span> <span m='2566750'>number of</span> <span m='2566930'>valleys,</span>
  <span m='2567320'>in</span> <span m='2567440'>total</span> <span m='2567740'>here,</span>
  <span m='2568480'>must</span> <span m='2568780'>be</span> <span m='2568960'>plus</span>
  <span m='2569210'>or</span> <span m='2569250'>minus</span> <span m='2569560'>2.</span>
  <span m='2571280'>I only</span> <span m='2571590'>added</span> <span m='2572020'>one</span>
  <span m='2572240'>crease--</span> <span m='2573050'>this</span> <span m='2573230'>one.</span>
  <span m='2575160'>So</span> <span m='2575800'>that's</span> <span m='2576030'>going</span>
  <span m='2576130'>to</span> <span m='2576190'>make</span> <span m='2576350'>it</span>
  <span m='2576460'>either</span> <span m='2576750'>plus</span> <span m='2576970'>or</span>
  <span m='2577010'>minus</span> <span m='2577270'>1</span> <span m='2577730'>or</span>
  <span m='2577950'>plus</span> <span m='2578190'>or</span> <span m='2578230'>minus</span>
  <span m='2578570'>3.</span> <span m='2579750'>If</span> <span m='2579790'>you</span>
  <span m='2579870'>think</span> <span m='2580070'>about it</span> <span m='2580330'>a</span>
  <span m='2580410'>little</span> <span m='2580600'>bit,</span> <span m='2580760'>it</span>
  <span m='2580840'>has</span> <span m='2581060'>to</span> <span m='2581160'>be</span>
  <span m='2581320'>plus</span> <span m='2581570'>or</span> <span m='2581620'>minus</span>
  <span m='2581970'>1.</span> <span m='2582250'>And</span> <span m='2582310'>hopefully,</span>
  <span m='2582705'>that's what I wrote</span> <span m='2583100'>here,</span> <span
  m='2583310'>yes.</span> </p><p><span m='2586760'>Because</span> <span m='2589060'>I</span>
  <span m='2589110'>mean,</span> <span m='2589300'>really,</span> <span m='2589580'>we're</span>
  <span m='2589700'>thinking</span> <span m='2589920'>about</span> <span m='2590120'>turn</span>
  <span m='2590290'>angles</span> <span m='2590550'>again,</span> <span m='2590810'>I'm</span>
  <span m='2590920'>afraid.</span> <span m='2591580'>Can't</span> <span m='2591820'>totally</span>
  <span m='2592110'>reduce</span> <span m='2592450'>it.</span> <span m='2593330'>We</span>
  <span m='2593520'>just</span> <span m='2593740'>turned</span> <span m='2593970'>around</span>
  <span m='2594390'>here.</span> <span m='2595820'>And</span> <span m='2595990'>we</span>
  <span m='2596070'>were</span> <span m='2596120'>about</span> <span m='2596400'>to</span>
  <span m='2596500'>finish</span> <span m='2596820'>the</span> <span m='2596940'>circle,</span>
  <span m='2597560'>which</span> <span m='2597640'>would</span> <span m='2597720'>make  it</span>
  <span m='2597860'>plus</span> <span m='2598140'>or</span> <span m='2598180'>minus</span>
  <span m='2598440'>2.</span> <span m='2598960'>Before</span> <span m='2599300'>we</span>
  <span m='2599420'>finish</span> <span m='2599660'>the</span> <span m='2599740'>circle,</span>
  <span m='2600180'>it's</span> <span m='2600320'>plus</span> <span m='2600530'>or</span>
  <span m='2600570'>minus</span> <span m='2600830'>1.</span> </p><p><span m='2603510'>k</span>
  <span m='2603700'>is</span> <span m='2603830'>odd.</span> <span m='2608600'>Again,</span>
  <span m='2608920'>this</span> <span m='2609090'>might</span> <span m='2609260'>go</span>
  <span m='2609420'>like</span> <span m='2609590'>that,</span> <span m='2609990'>whatever.</span>
  <span m='2611080'>But,</span> <span m='2611390'>because</span> <span m='2611580'>it's</span>
  <span m='2611720'>an</span> <span m='2611800'>odd</span> <span m='2612000'>number,</span>
  <span m='2612420'>these</span> <span m='2612630'>guys</span> <span m='2613220'>are</span>
  <span m='2613360'>going</span> <span m='2613710'>in</span> <span m='2613920'>the</span>
  <span m='2614000'>same</span> <span m='2614210'>direction.</span> <span m='2616030'>And</span>
  <span m='2616320'>so</span> <span m='2616480'>the</span> <span m='2616900'>total</span>
  <span m='2617180'>turn</span> <span m='2617400'>angle</span> <span m='2617630'>here</span>
  <span m='2617880'>must</span> <span m='2618210'>be</span> <span m='2618710'>0.</span>
  </p><p><span m='2619120'>And</span> <span m='2619240'>one</span> <span m='2619460'>way</span>
  <span m='2619610'>to</span> <span m='2619690'>see</span> <span m='2619880'>that</span>
  <span m='2620490'>is</span> <span m='2620710'>to</span> <span m='2620840'>extend</span>
  <span m='2621320'>it</span> <span m='2622030'>into</span> <span m='2622530'>a</span>
  <span m='2622590'>full</span> <span m='2622910'>polygon.</span> <span m='2624240'>You</span>
  <span m='2624360'>know</span> <span m='2624540'>that</span> <span m='2624670'>it's</span>
  <span m='2624820'>plus</span> <span m='2625070'>or</span> <span m='2625120'>minus</span>
  <span m='2625830'>2</span> <span m='2627220'>for</span> <span m='2627420'>this</span>
  <span m='2627590'>whole</span> <span m='2627810'>thing.</span> <span m='2628250'>And</span>
  <span m='2628360'>I</span> <span m='2628410'>added</span> <span m='2628920'>two</span>
  <span m='2629880'>guys</span> <span m='2630400'>in</span> <span m='2630560'>the</span>
  <span m='2630630'>same</span> <span m='2630850'>direction.</span> <span m='2632100'>If</span>
  <span m='2632180'>I</span> <span m='2632250'>remove</span> <span m='2632610'>them,</span>
  <span m='2632990'>it's</span> <span m='2633170'>going</span> <span m='2633280'>to</span>
  <span m='2633350'>go</span> <span m='2633470'>down</span> <span m='2633630'>to</span>
  <span m='2633700'>plus</span> <span m='2633960'>or</span> <span m='2634000'>minus</span>
  <span m='2634450'>0.</span> </p><p><span m='2639960'>That</span> <span m='2640120'>was</span>
  <span m='2640240'>a</span> <span m='2640290'>bit</span> <span m='2640450'>hand</span>
  <span m='2640650'>wavy.</span> <span m='2640970'>But</span> <span m='2641160'>do
  you</span> <span m='2641660'>buy</span> <span m='2641820'>that?</span> </p><p><span
  m='2645823'>AUDIENCE:</span> <span m='2646302'>[INAUDIBLE]</span> <span m='2646781'>plus</span>
  <span m='2647260'>or minus</span> <span m='2647739'>0?</span> </p><p><span m='2648697'>PROFESSOR:</span>
  <span m='2649180'>Plus</span> <span m='2649430'>or</span> <span m='2649470'>minus</span>
  <span m='2649710'>0</span> <span m='2649960'>is 0,</span> <span m='2650590'>yeah.</span>
  <span m='2651630'>You</span> <span m='2651740'>went</span> <span m='2651920'>from</span>
  <span m='2652060'>2</span> <span m='2652350'>down</span> <span m='2652530'>to</span>
  <span m='2652580'>zero,</span> <span m='2652940'>because</span> <span m='2653120'>you</span>
  <span m='2653200'>remove</span> <span m='2653480'>two</span> <span m='2653870'>identical</span>
  <span m='2654340'>guys.</span> <span m='2658730'>So</span> <span m='2660760'>let</span>
  <span m='2661260'>me</span> <span m='2661470'>tie</span> <span m='2661710'>this</span>
  <span m='2661890'>all</span> <span m='2662020'>together,</span> <span m='2662450'>because</span>
  <span m='2662660'>there's</span> <span m='2662790'>so</span> <span m='2662940'>many</span>
  <span m='2663530'>little</span> <span m='2663920'>cases.</span> </p><p><span m='2674630'>So</span>
  <span m='2674750'>I</span> <span m='2674830'>want</span> <span m='2675060'>to</span>
  <span m='2675140'>know</span> <span m='2676520'>what</span> <span m='2676800'>mountain</span>
  <span m='2677020'>valley</span> <span m='2677300'>patterns</span> <span m='2677660'>are</span>
  <span m='2677780'>flat</span> <span m='2678060'>foldable,</span> <span m='2681430'>single</span>
  <span m='2681730'>vertex,</span> <span m='2687920'>m/v</span> <span m='2688740'>patterns.</span>
  <span m='2696630'>I</span> <span m='2696730'>claim</span> <span m='2701860'>there</span>
  <span m='2702050'>is</span> <span m='2702150'>a</span> <span m='2702220'>crimp.</span>
  <span m='2704710'>If it's</span> <span m='2704880'>flat</span> <span m='2705080'>foldable,</span>
  <span m='2706020'>there</span> <span m='2706120'>has</span> <span m='2706380'>to</span>
  <span m='2706460'>be</span> <span m='2706630'>a crimp</span> <span m='2706890'>that</span>
  <span m='2707000'>you</span> <span m='2707140'>can</span> <span m='2707270'>find</span>
  <span m='2707600'>to</span> <span m='2707690'>do.</span> </p><p><span m='2708400'>Remember,</span>
  <span m='2708760'>a crimp</span> <span m='2709150'>was</span> <span m='2710140'>where</span>
  <span m='2712230'>this</span> <span m='2712460'>length</span> <span m='2714330'>was</span>
  <span m='2715270'>less</span> <span m='2715880'>than</span> <span m='2716090'>or</span>
  <span m='2716240'>equal</span> <span m='2716590'>to</span> <span m='2716860'>this</span>
  <span m='2717070'>length</span> <span m='2717530'>and</span> <span m='2717750'>less</span>
  <span m='2718060'>than</span> <span m='2718240'>or</span> <span m='2718340'>equal</span>
  <span m='2718660'>to</span> <span m='2719440'>this</span> <span m='2719650'>length.</span>
  <span m='2720250'>And</span> <span m='2720410'>one</span> <span m='2720570'>of</span>
  <span m='2720620'>these</span> <span m='2720790'>was</span> <span m='2720920'>m.</span>
  <span m='2721370'>One of</span> <span m='2721440'>them</span> <span m='2721590'>was</span>
  <span m='2721750'>v.</span> <span m='2722300'>That was</span> <span m='2722390'>the</span>
  <span m='2722460'>definition</span> <span m='2722900'>of</span> <span m='2722990'>a</span>
  <span m='2723040'>crimp.</span> </p><p><span m='2723800'>I claim</span> <span m='2724080'>such</span>
  <span m='2724310'>a</span> <span m='2724360'>thing</span> <span m='2724570'>always</span>
  <span m='2724790'>exists.</span> <span m='2726090'>The</span> <span m='2726190'>proof</span>
  <span m='2726530'>is</span> <span m='2728910'>two</span> <span m='2729210'>parts.</span>
  <span m='2730230'>If</span> <span m='2730500'>all</span> <span m='2730780'>the</span>
  <span m='2730890'>angles</span> <span m='2731200'>are</span> <span m='2731300'>equal,</span>
  <span m='2738250'>we</span> <span m='2738260'>know</span> <span m='2738450'>that</span>
  <span m='2738630'>these</span> <span m='2738850'>conditions</span> <span m='2739310'>are</span>
  <span m='2739470'>always</span> <span m='2739780'>satisfied,</span> <span m='2740300'>because</span>
  <span m='2740500'>everything</span> <span m='2740980'>is</span> <span m='2741070'>equal.</span>
  </p><p><span m='2743080'>So</span> <span m='2743330'>we</span> <span m='2743440'>just</span>
  <span m='2743630'>need</span> <span m='2743750'>to</span> <span m='2743810'>find</span>
  <span m='2744140'>an m</span> <span m='2744240'>followed</span> <span m='2744720'>by</span>
  <span m='2744860'>v</span> <span m='2745180'>or a v</span> <span m='2745340'>followed</span>
  <span m='2745800'>by an</span> <span m='2746030'>m.</span> <span m='2747010'>And</span>
  <span m='2747520'>by</span> <span m='2748780'>Maekawa's</span> <span m='2749410'>theorem,</span>
  <span m='2750440'>we</span> <span m='2750630'>know</span> <span m='2751330'>it's</span>
  <span m='2751540'>not</span> <span m='2751730'>all</span> <span m='2752030'>m's</span>
  <span m='2752400'>or</span> <span m='2752510'>all</span> <span m='2752770'>v's.</span>
  <span m='2753230'>So</span> <span m='2753390'>somewhere,</span> <span m='2753760'>there</span>
  <span m='2753900'>has</span> <span m='2754120'>to</span> <span m='2754210'>be</span>
  <span m='2754380'>a</span> <span m='2754430'>transition</span> <span m='2754960'>from</span>
  <span m='2755150'>m</span> <span m='2755555'>to</span> <span m='2755960'>v's.</span>
  <span m='2764150'>So</span> <span m='2764300'>just</span> <span m='2764600'>use</span>
  <span m='2764800'>that</span> <span m='2765020'>lemma</span> <span m='2765530'>theorem</span>
  <span m='2765970'>or</span> <span m='2766306'>the</span> <span m='2766980'>count</span>
  <span m='2768380'>property.</span> </p><p><span m='2769580'>Otherwise,</span> <span
  m='2770650'>if</span> <span m='2771120'>they're</span> <span m='2771230'>not  all</span>
  <span m='2771600'>equal,</span> <span m='2772890'>then</span> <span m='2773400'>I</span>
  <span m='2773560'>can</span> <span m='2773690'>apply</span> <span m='2773990'>this</span>
  <span m='2774180'>local</span> <span m='2774540'>counts</span> <span m='2774870'>result,</span>
  <span m='2776250'>take</span> <span m='2776630'>the</span> <span m='2777210'>smallest</span>
  <span m='2778450'>angle--</span> <span m='2778900'>take</span> <span m='2779090'>one</span>
  <span m='2779350'>instance</span> <span m='2779790'>of</span> <span m='2779860'>the</span>
  <span m='2779940'>smallest</span> <span m='2780320'>angle.</span> <span m='2780560'>There</span>
  <span m='2780670'>could</span> <span m='2780810'>be</span> <span m='2780910'>many</span>
  <span m='2781190'>of</span> <span m='2781250'>them.</span> <span m='2781770'>Find</span>
  <span m='2782270'>all</span> <span m='2782590'>of</span> <span m='2782750'>its</span>
  <span m='2783030'>neighboring</span> <span m='2783600'>friends</span> <span m='2784040'>that</span>
  <span m='2784140'>are</span> <span m='2784260'>equal.</span> </p><p><span m='2785540'>Then</span>
  <span m='2785570'>I</span> <span m='2785630'>know</span> <span m='2785820'>that</span>
  <span m='2786030'>the</span> <span m='2786140'>next</span> <span m='2786480'>angles</span>
  <span m='2786870'>before</span> <span m='2787240'>and</span> <span m='2787300'>after</span>
  <span m='2787620'>have</span> <span m='2787800'>to</span> <span m='2787890'>be</span>
  <span m='2787990'>strictly</span> <span m='2788410'>bigger.</span> <span m='2789770'>Then</span>
  <span m='2789940'>I</span> <span m='2790030'>know</span> <span m='2790280'>that</span>
  <span m='2790440'>the</span> <span m='2790520'>number of</span> <span m='2790810'>mountains</span>
  <span m='2791160'>and</span> <span m='2791240'>valleys</span> <span m='2791620'>in</span>
  <span m='2791710'>here--</span> <span m='2793770'>if I</span> <span m='2793810'>look</span>
  <span m='2794000'>at</span> <span m='2794040'>the</span> <span m='2794140'>difference</span>
  <span m='2794970'>and</span> <span m='2795230'>it's</span> <span m='2795330'>0,</span>
  <span m='2796750'>that</span> <span m='2797010'>means</span> <span m='2797450'>the</span>
  <span m='2797500'>number of</span> <span m='2797720'>mountains</span> <span m='2798050'>equals
  the</span> <span m='2798400'>number of</span> <span m='2798630'>valleys.</span>
  <span m='2798970'>Therefore,</span> <span m='2799280'>there's</span> <span m='2799450'>at</span>
  <span m='2799520'>least</span> <span m='2799750'>one</span> <span m='2799920'>of</span>
  <span m='2800010'>each.</span> <span m='2801400'>And</span> <span m='2801460'>therefore,</span>
  <span m='2801700'>there's</span> <span m='2801870'>a</span> <span m='2801920'>transition</span>
  <span m='2802450'>from</span> <span m='2802570'>mountain to</span> <span m='2802850'>valley</span>
  <span m='2803180'>in</span> <span m='2803290'>there.</span> </p><p><span m='2804250'>Because</span>
  <span m='2804370'>the</span> <span m='2804440'>transition</span> <span m='2804970'>from</span>
  <span m='2805090'>mountain</span> <span m='2805320'>to</span> <span m='2805370'>valley--</span>
  <span m='2806390'>like</span> <span m='2806600'>right</span> <span m='2806840'>here,</span>
  <span m='2808130'>that's</span> <span m='2808350'>a</span> <span m='2808390'>valid</span>
  <span m='2808710'>crimp.</span> <span m='2809020'>This</span> <span m='2809190'>guy's</span>
  <span m='2809350'>bigger;</span> <span m='2809960'>this</span> <span m='2810130'>guy's</span>
  <span m='2810290'>equal.</span> <span m='2812160'>This</span> <span m='2812720'>would</span>
  <span m='2812850'>also</span> <span m='2813140'>be</span> <span m='2813280'>a</span>
  <span m='2813330'>fine</span> <span m='2813580'>transition,</span> <span m='2814030'>because</span>
  <span m='2814210'>everybody's</span> <span m='2814620'>equal.</span> <span m='2815400'>This
  would</span> <span m='2815520'>also</span> <span m='2815730'>be a fine</span> <span
  m='2816080'>transition.</span> <span m='2816560'>Any</span> <span m='2817150'>transition</span>
  <span m='2817620'>from</span> <span m='2817710'>mountain to</span> <span m='2817980'>valley</span>
  <span m='2818230'>in</span> <span m='2818300'>here,</span> <span m='2818890'>I've</span>
  <span m='2819000'>got</span> <span m='2819150'>a</span> <span m='2819210'>crimp.</span>
  </p><p><span m='2820660'>The</span> <span m='2821350'>even</span> <span m='2821670'>case</span>
  <span m='2822020'>is</span> <span m='2822140'>a</span> <span m='2822190'>little--</span>
  <span m='2822900'>I got to</span> <span m='2823120'>think</span> <span m='2823340'>a</span>
  <span m='2823390'>little</span> <span m='2823590'>bit</span> <span m='2823750'>more.</span>
  <span m='2824480'>k is</span> <span m='2824840'>even.</span> <span m='2827610'>k</span>
  <span m='2827850'>plus</span> <span m='2828160'>1,</span> <span m='2828480'>which</span>
  <span m='2828630'>is</span> <span m='2828730'>the</span> <span m='2828820'>number</span>
  <span m='2829050'>of</span> <span m='2829120'>creases</span> <span m='2829520'>here,</span>
  <span m='2830350'>is</span> <span m='2830710'>odd.</span> <span m='2832140'>And</span>
  <span m='2832690'>the</span> <span m='2832810'>difference</span> <span m='2833170'>between</span>
  <span m='2833610'>mountains</span> <span m='2833890'>and</span> <span m='2833970'>valleys</span>
  <span m='2834310'>among</span> <span m='2834530'>those</span> <span m='2834710'>k</span>
  <span m='2834860'>plus</span> <span m='2835130'>one</span> <span m='2835250'>creases</span>
  <span m='2835650'>is</span> <span m='2835740'>plus</span> <span m='2836000'>or</span>
  <span m='2836060'>minus</span> <span m='2836350'>1.</span> </p><p><span m='2837010'>Think</span>
  <span m='2837190'>about</span> <span m='2837410'>it</span> <span m='2837480'>for</span>
  <span m='2837600'>second.</span> <span m='2837990'>That</span> <span m='2838000'>means</span>
  <span m='2838190'>there's,</span> <span m='2838420'>again,</span> <span m='2838730'>at</span>
  <span m='2838800'>least</span> <span m='2839060'>one</span> <span m='2839210'>mountain</span>
  <span m='2839480'>and at</span> <span m='2839650'>least</span> <span m='2839880'>one</span>
  <span m='2840040'>valley.</span> <span m='2842940'>Because</span> <span m='2843070'>k,</span>
  <span m='2843500'>to</span> <span m='2843660'>be</span> <span m='2843950'>even,</span>
  <span m='2844190'>has</span> <span m='2844380'>to</span> <span m='2844470'>be</span>
  <span m='2844610'>at</span> <span m='2844660'>least</span> <span m='2845130'>2.</span>
  <span m='2846090'>We've got</span> <span m='2846570'>to have</span> <span m='2846690'>at</span>
  <span m='2846750'>least</span> <span m='2846980'>three</span> <span m='2847210'>things.</span>
  <span m='2848050'>So there's</span> <span m='2848210'>going</span> <span m='2848330'>to</span>
  <span m='2848370'>be</span> <span m='2848450'>at</span> <span m='2848500'>least</span>
  <span m='2849020'>one of</span> <span m='2849385'>one</span> <span m='2849750'>and</span>
  <span m='2849860'>two</span> <span m='2849990'>of</span> <span m='2850040'>the</span>
  <span m='2850170'>other,</span> <span m='2850890'>in fact.</span> </p><p><span m='2852010'>And
  I</span> <span m='2852130'>just</span> <span m='2852310'>need</span> <span m='2852430'>one</span>
  <span m='2852640'>mountain and</span> <span m='2852990'>one</span> <span m='2853140'>valley</span>
  <span m='2853390'>somewhere</span> <span m='2853760'>in</span> <span m='2853840'>there.</span>
  <span m='2854110'>And</span> <span m='2854200'>then</span> <span m='2854320'>I</span>
  <span m='2854380'>know</span> <span m='2854540'>there</span> <span m='2854660'>has</span>
  <span m='2854920'>to</span> <span m='2854990'>be a</span> <span m='2855100'>transition</span>
  <span m='2855590'>from</span> <span m='2855740'>mountain to</span> <span m='2856040'>valley.</span>
  <span m='2859190'>Otherwise,</span> <span m='2861160'>use</span> <span m='2861350'>local</span>
  <span m='2861690'>counts.</span> </p><p><span m='2865890'>And</span> <span m='2866270'>in</span>
  <span m='2866390'>either</span> <span m='2866690'>case,</span> <span m='2872910'>we</span>
  <span m='2873060'>get</span> <span m='2875610'>either</span> <span m='2875710'>a</span>
  <span m='2875880'>mountain</span> <span m='2876200'>to</span> <span m='2876310'>valley</span>
  <span m='2876630'>transition</span> <span m='2877860'>or</span> <span m='2879210'>a</span>
  <span m='2879310'>valley</span> <span m='2879960'>to</span> <span m='2880170'>mountain</span>
  <span m='2881850'>transition.</span> <span m='2883460'>And</span> <span m='2884190'>I</span>
  <span m='2884310'>get</span> <span m='2884640'>it</span> <span m='2884740'>in</span>
  <span m='2884850'>such a</span> <span m='2885170'>way that</span> <span m='2885490'>these</span>
  <span m='2886680'>inequalities</span> <span m='2887360'>on</span> <span m='2887430'>the</span>
  <span m='2887500'>lengths</span> <span m='2887810'>hold.</span> <span m='2889190'>So</span>
  <span m='2889480'>in</span> <span m='2889620'>other</span> <span m='2889750'>words,</span>
  <span m='2889990'>that it's</span> <span m='2890140'>a</span> <span m='2890200'>crimp.</span>
  </p><p><span m='2895590'>Therefore,</span> <span m='2895950'>any</span> <span m='2896430'>flat</span>
  <span m='2896880'>foldable,</span> <span m='2897210'>single</span> <span m='2897550'>vertex,</span>
  <span m='2897990'>mountain</span> <span m='2898240'>valley</span> <span m='2898520'>pattern</span>
  <span m='2899130'>has</span> <span m='2899390'>a</span> <span m='2899480'>crimp.</span>
  <span m='2900320'>Make</span> <span m='2900620'>it.</span> <span m='2901590'>And</span>
  <span m='2901820'>as</span> <span m='2901970'>I</span> <span m='2902040'>was</span>
  <span m='2902160'>arguing</span> <span m='2902640'>here,</span> <span m='2903530'>just</span>
  <span m='2903790'>like</span> <span m='2903950'>last</span> <span m='2904250'>time,</span>
  <span m='2905300'>that</span> <span m='2905510'>crimp</span> <span m='2905850'>will</span>
  <span m='2906260'>still--</span> <span m='2907080'>after</span> <span m='2907190'>you</span>
  <span m='2907330'>do</span> <span m='2907430'>the</span> <span m='2907510'>crimp,</span>
  <span m='2907750'>you'll</span> <span m='2907850'>still</span> <span m='2908060'>be</span>
  <span m='2908180'>flat</span> <span m='2908420'>foldable,</span> <span m='2909120'>so</span>
  <span m='2909280'>repeat.</span> <span m='2910120'>Cook</span> <span m='2910330'>until</span>
  <span m='2910640'>done</span> <span m='2911120'>is</span> <span m='2912370'>how
  I</span> <span m='2912520'>like</span> <span m='2912720'>to</span> <span m='2912810'>put</span>
  <span m='2912970'>it.</span> <span m='2914160'>Question.</span> </p><p><span m='2914600'>AUDIENCE:</span>
  <span m='2915061'>What about</span> <span m='2915522'>the trivial case</span> <span
  m='2915983'>of just</span> <span m='2916444'>folding a circle</span> <span m='2916905'>in
  half?</span> </p><p><span m='2917827'>PROFESSOR:</span> <span m='2918290'>The trivial</span>
  <span m='2918740'>case</span> <span m='2919000'>of</span> <span m='2919080'>folding</span>
  <span m='2919340'>a</span> <span m='2919460'>circle</span> <span m='2919540'>in</span>
  <span m='2919760'>half.</span> <span m='2919930'>All right.</span> <span m='2920170'>That's</span>
  <span m='2920360'>a</span> <span m='2920410'>good</span> <span m='2920540'>question.</span>
  <span m='2921450'>It's</span> <span m='2921570'>kind</span> <span m='2921820'>of</span>
  <span m='2921930'>a</span> <span m='2922000'>technicality.</span> </p><p><span m='2925650'>One</span>
  <span m='2925950'>version</span> <span m='2926340'>would</span> <span m='2926580'>be
  to</span> <span m='2926650'>say,</span> <span m='2927140'>that's</span> <span m='2927440'>zero</span>
  <span m='2927720'>vertices.</span> <span m='2928390'>That</span> <span m='2928550'>doesn't</span>
  <span m='2928800'>count.</span> <span m='2929100'>And we're</span> <span m='2929220'>thinking</span>
  <span m='2929460'>about</span> <span m='2929650'>one</span> <span m='2929820'>vertex.</span>
  </p><p><span m='2930760'>And</span> <span m='2930890'>as</span> <span m='2930980'>soon</span>
  <span m='2931160'>as</span> <span m='2931220'>you</span> <span m='2931320'>think</span>
  <span m='2931510'>about</span> <span m='2931740'>it</span> <span m='2931820'>as</span>
  <span m='2931940'>one</span> <span m='2932150'>vertex,</span> <span m='2932670'>which</span>
  <span m='2932900'>is</span> <span m='2933070'>fine,</span> <span m='2934110'>then</span>
  <span m='2934330'>you</span> <span m='2934480'>actually</span> <span m='2934730'>have</span>
  <span m='2935030'>two</span> <span m='2937170'>creases</span> <span m='2937590'>there.</span>
  <span m='2938510'>So</span> <span m='2938630'>it's</span> <span m='2938770'>two</span>
  <span m='2938890'>creases.</span> <span m='2939570'>And</span> <span m='2939740'>hopefully,</span>
  <span m='2940070'>this</span> <span m='2940240'>works.</span> </p><p><span m='2942550'>Oh,</span>
  <span m='2942610'>I</span> <span m='2942700'>see what</span> <span m='2942940'>you're</span>
  <span m='2943030'>saying.</span> <span m='2943260'>It's</span> <span m='2943380'>not</span>
  <span m='2943550'>a</span> <span m='2943620'>crimp.</span> <span m='2944890'>That's</span>
  <span m='2945080'>a</span> <span m='2945140'>good</span> <span m='2945370'>point.</span>
  </p><p><span m='2945740'>AUDIENCE:</span> <span m='2946204'>But then it's</span>
  <span m='2946668'>flat</span> <span m='2947132'>foldable.</span> </p><p><span m='2948524'>PROFESSOR:</span>
  <span m='2948990'>It</span> <span m='2949120'>is</span> <span m='2949310'>flat</span>
  <span m='2949600'>foldable, and</span> <span m='2949890'>yet,</span> <span m='2950060'>there's</span>
  <span m='2950210'>no</span> <span m='2950370'>crimp.</span> <span m='2950850'>Damn
  it.</span> <span m='2953170'>All right.</span> <span m='2953560'>Sorry?</span> </p><p><span
  m='2953870'>AUDIENCE:</span> <span m='2954328'>But it follows</span> <span m='2955702'>Maekawa's,</span>
  <span m='2956618'>right?</span> </p><p><span m='2957080'>PROFESSOR:</span> <span
  m='2957345'>Yeah.</span> <span m='2958260'>So</span> <span m='2959280'>I</span>
  <span m='2959370'>made</span> <span m='2959590'>a</span> <span m='2959650'>slight</span>
  <span m='2960100'>mistake</span> <span m='2960510'>here.</span> <span m='2961370'>I</span>
  <span m='2961450'>said</span> <span m='2961620'>if</span> <span m='2961730'>all</span>
  <span m='2961870'>the</span> <span m='2961960'>angles</span> <span m='2962250'>are</span>
  <span m='2962320'>equal,</span> <span m='2962720'>then</span> <span m='2962740'>Maekawa</span>
  <span m='2962910'>says</span> <span m='2963205'>there's</span> <span m='2963620'>at</span>
  <span m='2963690'>least</span> <span m='2963930'>one</span> <span m='2964100'>of</span>
  <span m='2964180'>each.</span> <span m='2964760'>That's</span> <span m='2964990'>not</span>
  <span m='2965240'>true</span> <span m='2965540'>when</span> <span m='2965670'>n</span>
  <span m='2965790'>equals</span> <span m='2966090'>2.</span> <span m='2967230'>Then</span>
  <span m='2967460'>there's</span> <span m='2967900'>two</span> <span m='2968180'>of</span>
  <span m='2968280'>one</span> <span m='2968550'>and</span> <span m='2968650'>zero</span>
  <span m='2968990'>of the</span> <span m='2969180'>other.</span> </p><p><span m='2970450'>As</span>
  <span m='2970780'>long</span> <span m='2970980'>as</span> <span m='2971050'>you</span>
  <span m='2971120'>have</span> <span m='2971220'>more</span> <span m='2971470'>than</span>
  <span m='2971650'>two</span> <span m='2972110'>creases,</span> <span m='2974120'>then</span>
  <span m='2974320'>this</span> <span m='2974520'>is</span> <span m='2974750'>true.</span>
  <span m='2976060'>That's</span> <span m='2976250'>enough.</span> <span m='2977030'>So</span>
  <span m='2977090'>you</span> <span m='2977160'>have</span> <span m='2977270'>to</span>
  <span m='2977370'>handle</span> <span m='2977590'>this</span> <span m='2977760'>as</span>
  <span m='2977870'>a</span> <span m='2977930'>special</span> <span m='2978260'>case.</span>
  </p><p><span m='2978740'>AUDIENCE:</span> <span m='2979125'>At the end of</span>
  <span m='2979510'>your algorithm,</span> <span m='2979895'>you're</span> <span m='2980280'>always</span>
  <span m='2980700'>left</span> <span m='2981053'>with</span> <span m='2981406'>two</span>
  <span m='2981760'>of the same--</span> </p><p><span m='2983396'>PROFESSOR:</span>
  <span m='2983830'>That's</span> <span m='2984060'>true.</span> <span m='2985232'>This</span>
  <span m='2985590'>is</span> <span m='2985700'>an</span> <span m='2985790'>important</span>
  <span m='2986180'>special</span> <span m='2986490'>case</span> <span m='2986770'>to</span>
  <span m='2986930'>remember,</span> <span m='2987390'>because</span> <span m='2988140'>this</span>
  <span m='2988290'>will</span> <span m='2988620'>be</span> <span m='2988810'>the</span>
  <span m='2988900'>final</span> <span m='2989440'>picture.</span> <span m='2990210'>After</span>
  <span m='2990530'>you</span> <span m='2990620'>do a</span> <span m='2990790'>sequence</span>
  <span m='2991160'>of</span> <span m='2991260'>crimps,</span> <span m='2992290'>this</span>
  <span m='2992720'>is</span> <span m='2992930'>the</span> <span m='2993030'>good</span>
  <span m='2993220'>case.</span> <span m='2995240'>If</span> <span m='2995370'>your</span>
  <span m='2995480'>thing</span> <span m='2995640'>is</span> <span m='2995730'>flat</span>
  <span m='2995920'>foldable,</span> <span m='2996270'>you will</span> <span m='2996410'>always</span>
  <span m='2996800'>end</span> <span m='2996940'>up</span> <span m='2997070'>with</span>
  <span m='2997170'>that.</span> </p><p><span m='2997435'>AUDIENCE:</span> <span m='2997700'>That's
  a</span> <span m='2998200'>case where</span> <span m='2998700'>everything</span>
  <span m='2999200'>is</span> <span m='3001200'>the</span> <span m='3001700'>same,</span>
  <span m='3002200'>smallest.</span> </p><p><span m='3002905'>PROFESSOR:</span> <span
  m='3003290'>It's</span> <span m='3003880'>another</span> <span m='3004190'>example</span>
  <span m='3004650'>where</span> <span m='3004830'>all</span> <span m='3004930'>the</span>
  <span m='3005030'>angles</span> <span m='3005310'>are</span> <span m='3005410'>equal.</span>
  <span m='3006530'>So</span> <span m='3006710'>that's</span> <span m='3006920'>why</span>
  <span m='3007110'>this</span> <span m='3007360'>is</span> <span m='3007530'>the</span>
  <span m='3007610'>situation.</span> <span m='3009130'>It's</span> <span m='3009530'>either</span>
  <span m='3009830'>Maekawa</span> <span m='3010130'>and</span> <span m='3010460'>you</span>
  <span m='3010560'>get</span> <span m='3010700'>a</span> <span m='3010760'>cramp</span>
  <span m='3013800'>here,</span> <span m='3014070'>because</span> <span m='3014750'>n</span>
  <span m='3014930'>is</span> <span m='3015050'>greater</span> <span m='3015290'>than</span>
  <span m='3015480'>2.</span> </p><p><span m='3016500'>And</span> <span m='3016650'>here,</span>
  <span m='3016870'>I</span> <span m='3016900'>should</span> <span m='3017110'>say,</span>
  <span m='3017500'>if</span> <span m='3018370'>n</span> <span m='3018570'>is</span>
  <span m='3018690'>greater</span> <span m='3018920'>than</span> <span m='3019110'>2,</span>
  <span m='3020590'>then</span> <span m='3020780'>this</span> <span m='3020940'>is</span>
  <span m='3021050'>true.</span> <span m='3021740'>Of</span> <span m='3021880'>course</span>
  <span m='3022120'>the n</span> <span m='3022340'>equals</span> <span m='3022740'>2</span>
  <span m='3022960'>case,</span> <span m='3024380'>it</span> <span m='3024580'>looks</span>
  <span m='3024730'>like</span> <span m='3024860'>that.</span> <span m='3025070'>And
  it had</span> <span m='3025160'>better</span> <span m='3025360'>be</span> <span
  m='3025480'>both</span> <span m='3025710'>valleys</span> <span m='3026040'>or</span>
  <span m='3026100'>both</span> <span m='3026300'>mountains.</span> <span m='3026650'>Otherwise,</span>
  <span m='3026730'>it's</span> <span m='3026810'>not</span> <span m='3027080'>going
  to be</span> <span m='3027230'>flat</span> <span m='3027700'>foldable.</span> </p><p><span
  m='3028120'>I</span> <span m='3028210'>forgot</span> <span m='3028520'>about</span>
  <span m='3028740'>that.</span> <span m='3028970'>I</span> <span m='3029360'>should</span>
  <span m='3029570'>add it</span> <span m='3029710'>in</span> <span m='3029870'>the</span>
  <span m='3029950'>notes.</span> <span m='3030200'>But</span> <span m='3030310'>it's</span>
  <span m='3030430'>in</span> <span m='3030510'>the</span> <span m='3030600'>textbook,</span>
  <span m='3031040'>right.</span> </p><p><span m='3031315'>AUDIENCE:</span> <span
  m='3031590'>At the</span> <span m='3032048'>end</span> <span m='3032506'>of the
  algorithm,</span> <span m='3032964'>it's not</span> <span m='3033422'>going to be
  a</span> <span m='3033880'>circle.</span> <span m='3034338'>It's going to be a</span>
  <span m='3034796'>cone.</span> </p><p><span m='3035254'>PROFESSOR:</span> <span
  m='3035720'>That's</span> <span m='3035950'>true.</span> <span m='3036300'>It</span>
  <span m='3036410'>won't</span> <span m='3036650'>actually</span> <span m='3037080'>look</span>
  <span m='3037260'>like</span> <span m='3037410'>this.</span> <span m='3038650'>At</span>
  <span m='3038850'>the</span> <span m='3038950'>end</span> <span m='3039090'>of</span>
  <span m='3039130'>the</span> <span m='3039240'>algorithm,</span> <span m='3039660'>it's</span>
  <span m='3039780'>going</span> <span m='3039890'>to</span> <span m='3039940'>be</span>
  <span m='3040070'>a</span> <span m='3040170'>cone.</span> <span m='3041330'>The</span>
  <span m='3041450'>two</span> <span m='3041640'>angles</span> <span m='3041890'>will</span>
  <span m='3042030'>be</span> <span m='3042210'>equal,</span> <span m='3042580'>because</span>
  <span m='3042970'>of</span> <span m='3043210'>Kawasaki's</span> <span m='3044020'>theorem.</span>
  <span m='3045590'>And</span> <span m='3045810'>they</span> <span m='3045890'>should</span>
  <span m='3046070'>still</span> <span m='3046320'>be</span> <span m='3046990'>both</span>
  <span m='3047190'>mountains</span> <span m='3047470'>or</span> <span m='3047520'>both</span>
  <span m='3047700'>valleys.</span> </p><p><span m='3048700'>But it's</span> <span
  m='3048890'>going</span> <span m='3049040'>to</span> <span m='3049110'>be--</span>
  <span m='3049990'>we</span> <span m='3050220'>can</span> <span m='3050350'>see it</span>
  <span m='3050530'>right</span> <span m='3050710'>here.</span> <span m='3051170'>So</span>
  <span m='3051220'>I</span> <span m='3051310'>apply</span> <span m='3051800'>my</span>
  <span m='3051910'>crimp,</span> <span m='3053270'>and</span> <span m='3053440'>now
  I</span> <span m='3053530'>have</span> <span m='3053670'>a</span> <span m='3053730'>cone,</span>
  <span m='3054550'>and</span> <span m='3054680'>there's</span> <span m='3054890'>two</span>
  <span m='3055090'>angles.</span> <span m='3055480'>There's</span> <span m='3055620'>one</span>
  <span m='3056360'>here,</span> <span m='3057300'>which</span> <span m='3057490'>has</span>
  <span m='3057580'>been</span> <span m='3057730'>fused</span> <span m='3058060'>together.</span>
  <span m='3058850'>And there's</span> <span m='3059020'>one</span> <span m='3059220'>here,</span>
  <span m='3060280'>which</span> <span m='3060530'>is the</span> <span m='3060630'>original.</span>
  </p><p><span m='3061670'>They're</span> <span m='3061890'>equal.</span> <span m='3062950'>And</span>
  <span m='3063250'>it's</span> <span m='3063400'>two</span> <span m='3063610'>mountains</span>
  <span m='3064840'>or</span> <span m='3065010'>two</span> <span m='3065160'>valleys,</span>
  <span m='3065530'>if</span> <span m='3065630'>I</span> <span m='3065710'>turned</span>
  <span m='3065910'>it</span> <span m='3065980'>upside</span> <span m='3066240'>down.</span>
  <span m='3067290'>And</span> <span m='3067440'>then</span> <span m='3067560'>it</span>
  <span m='3067930'>finishes.</span> <span m='3068880'>So</span> <span m='3069000'>that's</span>
  <span m='3069330'>the</span> <span m='3069580'>algorithm</span> <span m='3069900'>in</span>
  <span m='3069980'>action--</span> <span m='3070390'>two</span> <span m='3070560'>steps.</span>
  </p><p><span m='3071550'>First</span> <span m='3071820'>you</span> <span m='3071930'>find</span>
  <span m='3072210'>this</span> <span m='3072390'>crimp</span> <span m='3073150'>here.</span>
  <span m='3073410'>This</span> <span m='3073600'>is</span> <span m='3073680'>actually</span>
  <span m='3073910'>the</span> <span m='3074000'>globally</span> <span m='3074370'>smallest</span>
  <span m='3074770'>angle.</span> <span m='3075020'>It's</span> <span m='3075090'>surrounded</span>
  <span m='3075410'>by</span> <span m='3075490'>bigger</span> <span m='3075760'>angles.</span>
  <span m='3076000'>So</span> <span m='3076120'>it's</span> <span m='3076240'>really</span>
  <span m='3076440'>easy.</span> </p><p><span m='3077680'>Then</span> <span m='3077900'>I</span>
  <span m='3077980'>have</span> <span m='3078850'>a</span> <span m='3078960'>cone</span>
  <span m='3079870'>with</span> <span m='3080040'>two</span> <span m='3080190'>equal</span>
  <span m='3080480'>angles,</span> <span m='3081220'>which</span> <span m='3081360'>is</span>
  <span m='3081420'>what</span> <span m='3081570'>has</span> <span m='3081770'>to</span>
  <span m='3081850'>happen</span> <span m='3082180'>at</span> <span m='3082270'>the</span>
  <span m='3082400'>end.</span> <span m='3083130'>And</span> <span m='3083510'>then</span>
  <span m='3084270'>I'm</span> <span m='3084480'>done.</span> <span m='3087340'>Good?</span>
  </p><p><span m='3087740'>AUDIENCE:</span> <span m='3088720'>Is that</span> <span
  m='3089210'>the only way</span> <span m='3089700'>to do it?</span> </p><p><span
  m='3091170'>PROFESSOR:</span> <span m='3091660'>This</span> <span m='3092090'>is</span>
  <span m='3092280'>what</span> <span m='3092490'>always</span> <span m='3092830'>happens.</span>
  <span m='3094430'>Oh,</span> <span m='3094800'>is</span> <span m='3095110'>this</span>
  <span m='3095230'>the</span> <span m='3095400'>only</span> <span m='3095720'>way</span>
  <span m='3095920'>to</span> <span m='3096010'>flat</span> <span m='3096380'>fold</span>
  <span m='3096530'>these</span> <span m='3096750'>things?</span> <span m='3097830'>No.</span>
  <span m='3098550'>There</span> <span m='3098750'>are</span> <span m='3099030'>other--</span>
  <span m='3100870'>yes,</span> <span m='3101640'>one</span> <span m='3101810'>of</span>
  <span m='3101880'>the</span> <span m='3101970'>two.</span> </p><p><span m='3113060'>I</span>
  <span m='3113160'>think</span> <span m='3114580'>it</span> <span m='3114720'>depends</span>
  <span m='3115020'>what</span> <span m='3115130'>you're</span> <span m='3115250'>counting.</span>
  <span m='3116620'>If</span> <span m='3116770'>you're</span> <span m='3116860'>counting</span>
  <span m='3117190'>mountain</span> <span m='3117440'>valley</span> <span m='3117750'>assignments--</span>
  <span m='3119190'>I</span> <span m='3119260'>mean,</span> <span m='3119430'>if</span>
  <span m='3119550'>you</span> <span m='3119630'>just</span> <span m='3119820'>want</span>
  <span m='3119980'>to</span> <span m='3120020'>know,</span> <span m='3120860'>can</span>
  <span m='3121010'>every</span> <span m='3121600'>mountain</span> <span m='3121840'>valley</span>
  <span m='3122100'>assignment</span> <span m='3122490'>be</span> <span m='3123130'>folded</span>
  <span m='3123450'>by</span> <span m='3123570'>crimping.</span> <span m='3123990'>Then
  the</span> <span m='3124160'>answer is</span> <span m='3124460'>yes.</span> <span
  m='3124770'>That's</span> <span m='3124860'>what</span> <span m='3124980'>we</span>
  <span m='3125100'>proved.</span> </p><p><span m='3125890'>But</span> <span m='3126000'>if</span>
  <span m='3126100'>you</span> <span m='3126210'>want</span> <span m='3126530'>to</span>
  <span m='3126620'>get</span> <span m='3126840'>every</span> <span m='3127190'>possible</span>
  <span m='3127630'>folded</span> <span m='3127990'>state,</span> <span m='3128990'>crimps
  are</span> <span m='3129370'>not</span> <span m='3129530'>going</span> <span m='3129630'>to</span>
  <span m='3129670'>be</span> <span m='3129780'>enough.</span> <span m='3130110'>The</span>
  <span m='3130220'>reason</span> <span m='3130490'>they're</span> <span m='3130610'>not</span>
  <span m='3130810'>enough</span> <span m='3131050'>is</span> <span m='3131420'>because</span>
  <span m='3131630'>we're</span> <span m='3131780'>using</span> <span m='3132040'>this</span>
  <span m='3132260'>thing.</span> <span m='3133130'>So,</span> <span m='3133280'>hey,</span>
  <span m='3133640'>here's</span> <span m='3133790'>some</span> <span m='3134010'>hypothetical</span>
  <span m='3134580'>folded</span> <span m='3134870'>state.</span> <span m='3135570'>We</span>
  <span m='3135720'>can</span> <span m='3135870'>rip</span> <span m='3136080'>it</span>
  <span m='3136170'>out</span> <span m='3136410'>and</span> <span m='3136510'>make</span>
  <span m='3136810'>the</span> <span m='3136920'>crimp</span> <span m='3137200'>has</span>
  <span m='3137440'>been</span> <span m='3137610'>done.</span> <span m='3137890'>But</span>
  <span m='3138040'>then</span> <span m='3138680'>there's</span> <span m='3138870'>a</span>
  <span m='3138920'>folded</span> <span m='3139180'>state</span> <span m='3139360'>you're</span>
  <span m='3139480'>not</span> <span m='3139700'>able</span> <span m='3139920'>to</span>
  <span m='3140040'>reach</span> <span m='3140700'>by</span> <span m='3140790'>crimping.</span>
  </p><p><span m='3141970'>We</span> <span m='3142140'>need</span> <span m='3142310'>to</span>
  <span m='3142390'>work</span> <span m='3142550'>that</span> <span m='3142690'>into</span>
  <span m='3142870'>an</span> <span m='3142960'>actual</span> <span m='3143210'>example,</span>
  <span m='3144510'>where</span> <span m='3144670'>crimping</span> <span m='3145020'>forbids</span>
  <span m='3145440'>you</span> <span m='3145600'>from</span> <span m='3145780'>reaching</span>
  <span m='3146080'>some</span> <span m='3146250'>folded</span> <span m='3146520'>state.</span>
  <span m='3146760'>But</span> <span m='3147010'>I'm</span> <span m='3147120'>pretty</span>
  <span m='3147340'>sure</span> <span m='3147540'>one</span> <span m='3147680'>exists</span>
  <span m='3148080'>because</span> <span m='3148400'>of</span> <span m='3148500'>this.</span>
  </p><p><span m='3148890'>AUDIENCE:</span> <span m='3149322'>Could that be more like</span>
  <span m='3149754'>spirals?</span> </p><p><span m='3150618'>PROFESSOR:</span> <span
  m='3151050'>Yeah,</span> <span m='3151240'>maybe</span> <span m='3151550'>some</span>
  <span m='3151730'>kind</span> <span m='3151860'>of</span> <span m='3151930'>spiraling</span>
  <span m='3152460'>thing.</span> </p><p><span m='3152890'>AUDIENCE:</span> <span
  m='3153341'>Well, layering</span> <span m='3154243'>takes into account--</span>
  </p><p><span m='3155145'>PROFESSOR:</span> <span m='3155600'>Right.</span> <span
  m='3155810'>What</span> <span m='3155930'>we're</span> <span m='3156040'>missing</span>
  <span m='3156350'>here</span> <span m='3156550'>is</span> <span m='3156760'>getting</span>
  <span m='3157040'>all</span> <span m='3157260'>the</span> <span m='3157640'>possible</span>
  <span m='3158110'>layer</span> <span m='3158490'>stacking</span> <span m='3159120'>orders.</span>
  <span m='3160020'>So</span> <span m='3160830'>we're</span> <span m='3160970'>just</span>
  <span m='3161110'>trying</span> <span m='3161310'>to</span> <span m='3161370'>match
  a</span> <span m='3161660'>mountain</span> <span m='3161920'>valley</span> <span
  m='3162200'>assignment.</span> <span m='3163290'>We're</span> <span m='3163410'>not</span>
  <span m='3163600'>going</span> <span m='3163700'>to</span> <span m='3163750'>match
  a</span> <span m='3164120'>target</span> <span m='3164740'>layer</span> <span m='3165030'>ordering,</span>
  <span m='3165360'>because</span> <span m='3166710'>we</span> <span m='3166920'>simplified</span>
  <span m='3167180'>the</span> <span m='3167440'>layer</span> <span m='3167780'>orders</span>
  <span m='3168140'>in</span> <span m='3168220'>order</span> <span m='3168360'>to</span>
  <span m='3168460'>make</span> <span m='3169000'>crimps</span> <span m='3169300'>possible.</span>
  <span m='3170790'>So</span> <span m='3170900'>crimps</span> <span m='3171180'>won't</span>
  <span m='3171410'>get</span> <span m='3171580'>you</span> <span m='3172520'>some</span>
  <span m='3172900'>of</span> <span m='3172970'>the folded</span> <span m='3173310'>states.</span>
  </p><p><span m='3175980'>But</span> <span m='3176220'>one</span> <span m='3176540'>thing</span>
  <span m='3177130'>you</span> <span m='3177360'>can</span> <span m='3177780'>play</span>
  <span m='3178070'>with</span> <span m='3182366'>over</span> <span m='3182838'>here--</span>
  <span m='3184730'>that</span> <span m='3184800'>has</span> <span m='3185080'>been</span>
  <span m='3185280'>played</span> <span m='3185520'>with</span> <span m='3185930'>by</span>
  <span m='3186120'>Tom</span> <span m='3186370'>Hall--</span> <span m='3188400'>is</span>
  <span m='3191340'>if</span> <span m='3191500'>I</span> <span m='3191570'>give</span>
  <span m='3191830'>you</span> <span m='3192320'>a</span> <span m='3192440'>crease</span>
  <span m='3192720'>pattern,</span> <span m='3195440'>how</span> <span m='3195700'>many</span>
  <span m='3196140'>flat</span> <span m='3196450'>foldable</span> <span m='3197990'>mountain</span>
  <span m='3198260'>valley</span> <span m='3198840'>assignments</span> <span m='3199320'>does</span>
  <span m='3199470'>it</span> <span m='3199550'>have?</span> <span m='3200630'>OK,</span>
  <span m='3200780'>we</span> <span m='3200850'>have</span> <span m='3201020'>this</span>
  <span m='3201180'>nice</span> <span m='3201580'>linear</span> <span m='3201830'>time</span>
  <span m='3202050'>algorithm  to</span> <span m='3202440'>tell</span> <span m='3202600'>you</span>
  <span m='3202730'>whether</span> <span m='3202850'>a</span> <span m='3202970'>particular</span>
  <span m='3203410'>one</span> <span m='3203550'>is</span> <span m='3203670'>doable.</span>
  <span m='3204450'>How</span> <span m='3204640'>many</span> <span m='3204880'>are</span>
  <span m='3205030'>there?</span> </p><p><span m='3206250'>And</span> <span m='3207490'>there</span>
  <span m='3207680'>is--</span> <span m='3208710'>if</span> <span m='3208840'>you</span>
  <span m='3208950'>work</span> <span m='3209160'>through</span> <span m='3210170'>all</span>
  <span m='3210460'>of</span> <span m='3210580'>the</span> <span m='3210670'>things</span>
  <span m='3210930'>I've</span> <span m='3211060'>shown</span> <span m='3211300'>you</span>
  <span m='3211460'>in</span> <span m='3211540'>a</span> <span m='3211600'>little</span>
  <span m='3211810'>bit</span> <span m='3211960'>more</span> <span m='3212110'>detail,</span>
  <span m='3213140'>you</span> <span m='3213340'>can</span> <span m='3213570'>recover--</span>
  <span m='3214280'>this</span> <span m='3214450'>was</span> <span m='3214590'>finding</span>
  <span m='3214980'>a</span> <span m='3215190'>crimp.</span> <span m='3216430'>But
  you</span> <span m='3216560'>can</span> <span m='3216680'>actually</span> <span
  m='3216940'>look</span> <span m='3217160'>at</span> <span m='3217240'>what</span>
  <span m='3217430'>are</span> <span m='3217530'>all</span> <span m='3217700'>the</span>
  <span m='3217790'>crimps that are</span> <span m='3218240'>possible</span> <span
  m='3219580'>and</span> <span m='3220270'>actually</span> <span m='3220620'>count</span>
  <span m='3221090'>how</span> <span m='3221430'>many</span> <span m='3221750'>different</span>
  <span m='3222130'>ways</span> <span m='3223340'>there</span> <span m='3223530'>are</span>
  <span m='3223750'>to</span> <span m='3224085'>fold.</span> <span m='3224420'>How</span>
  <span m='3224610'>many</span> <span m='3224860'>crimps</span> <span m='3225160'>you</span>
  <span m='3225290'>can</span> <span m='3225420'>do.</span> <span m='3225640'>And</span>
  <span m='3225730'>then</span> <span m='3226040'>given</span> <span m='3226320'>those</span>
  <span m='3226510'>crimps,</span> <span m='3226760'>how</span> <span m='3226860'>many</span>
  <span m='3226990'>crimps</span> <span m='3227230'>you</span> <span m='3227340'>can</span>
  <span m='3227460'>go</span> <span m='3227580'>after</span> <span m='3227750'>that.</span>
  </p><p><span m='3228340'>And in</span> <span m='3228660'>the same</span> <span m='3229120'>linear</span>
  <span m='3229390'>time</span> <span m='3229980'>kind</span> <span m='3230160'>of</span>
  <span m='3230230'>algorithm,</span> <span m='3231050'>you</span> <span m='3231140'>can</span>
  <span m='3231270'>figure</span> <span m='3231530'>out</span> <span m='3231650'>how</span>
  <span m='3231960'>many</span> <span m='3232760'>different</span> <span m='3233010'>mountain</span>
  <span m='3233230'>valley</span> <span m='3233470'>patterns</span> <span m='3233870'>are</span>
  <span m='3234040'>flat</span> <span m='3234310'>foldable.</span> <span m='3235410'>That</span>
  <span m='3235540'>takes</span> <span m='3235710'>a</span> <span m='3235760'>little</span>
  <span m='3235940'>bit</span> <span m='3236090'>more</span> <span m='3236250'>care.</span>
  <span m='3237120'>I</span> <span m='3237250'>will</span> <span m='3237390'>tell</span>
  <span m='3237590'>you</span> <span m='3237820'>the</span> <span m='3238390'>extremes.</span>
  </p><p><span m='3242860'>How</span> <span m='3243070'>small</span> <span m='3244820'>could</span>
  <span m='3245040'>the</span> <span m='3245930'>number</span> <span m='3246390'>of</span>
  <span m='3246490'>flat</span> <span m='3246850'>foldable</span> <span m='3247700'>mountain</span>
  <span m='3248010'>valley</span> <span m='3248300'>assignments</span> <span m='3248950'>be</span>
  <span m='3249070'>for a given</span> <span m='3249530'>crease</span> <span m='3249880'>pattern?</span>
  <span m='3252560'>Well,</span> <span m='3252620'>do you</span> <span m='3252680'>have</span>
  <span m='3252840'>any</span> <span m='3252960'>guesses</span> <span m='3253400'>when?</span>
  <span m='3254226'>When</span> <span m='3254640'>do</span> <span m='3254720'>I</span>
  <span m='3254790'>have</span> <span m='3254970'>the</span> <span m='3255090'>least</span>
  <span m='3255500'>choice</span> <span m='3256130'>of</span> <span m='3256290'>where</span>
  <span m='3256460'>to</span> <span m='3256530'>make</span> <span m='3256720'>crimps?</span>
  <span m='3264140'>Yeah.</span> </p><p><span m='3264680'>AUDIENCE:</span> <span m='3265176'>We  have
  three</span> <span m='3265672'>angles.</span> </p><p><span m='3266664'>PROFESSOR:</span>
  <span m='3267160'>For</span> <span m='3267370'>general</span> <span m='3267740'>n.</span>
  <span m='3268590'>Sorry.</span> <span m='3269680'>But,</span> <span m='3269850'>yeah,</span>
  <span m='3270420'>three</span> <span m='3270630'>angles</span> <span m='3270930'>or,
  I</span> <span m='3271030'>guess,</span> <span m='3271240'>two</span> <span m='3271400'>angles.</span>
  <span m='3272135'>We</span> <span m='3272430'>really</span> <span m='3272730'>can't</span>
  <span m='3272960'>do</span> <span m='3273100'>any--</span> <span m='3273530'>I don't</span>
  <span m='3273560'>have</span> <span m='3273670'>any</span> <span m='3273830'>choice.</span>
  </p><p><span m='3274980'>But</span> <span m='3275380'>for</span> <span m='3275920'>general</span>
  <span m='3276350'>n,</span> <span m='3276980'>how</span> <span m='3277280'>should</span>
  <span m='3277550'>I</span> <span m='3277640'>disperse</span> <span m='3278350'>the</span>
  <span m='3278440'>theta</span> <span m='3278760'>i's</span> <span m='3279650'>in</span>
  <span m='3279860'>order</span> <span m='3280020'>to</span> <span m='3280150'>make</span>
  <span m='3280480'>there</span> <span m='3280630'>be</span> <span m='3280800'>very</span>
  <span m='3281100'>few</span> <span m='3281400'>possible</span> <span m='3281890'>crimps?</span>
  </p><p><span m='3282870'>AUDIENCE:</span> <span m='3283350'>When there are only</span>
  <span m='3283830'>two</span> <span m='3284310'>transitions.</span> </p><p><span
  m='3284790'>PROFESSOR:</span> <span m='3285270'>When there</span> <span m='3285400'>are</span>
  <span m='3285430'>only</span> <span m='3285640'>two</span> <span m='3285950'>transitions</span>
  <span m='3286610'>between</span> <span m='3286780'>mountains</span> <span m='3287070'>and</span>
  <span m='3287160'>valleys.</span> <span m='3288090'>All</span> <span m='3288270'>the</span>
  <span m='3288330'>mountains</span> <span m='3288670'>are</span> <span m='3288760'>together.</span>
  <span m='3289190'>All</span> <span m='3289300'>the</span> <span m='3289370'>valleys</span>
  <span m='3289730'>are</span> <span m='3289800'>together.</span> <span m='3291690'>That's</span>
  <span m='3291910'>right,</span> <span m='3292150'>if</span> <span m='3292260'>I</span>
  <span m='3292320'>was</span> <span m='3292440'>asking</span> <span m='3292680'>a</span>
  <span m='3292730'>question</span> <span m='3292980'>about</span> <span m='3293160'>mountains</span>
  <span m='3293460'>and</span> <span m='3293550'>valleys.</span> <span m='3293990'>But</span>
  <span m='3294250'>I was asking a</span> <span m='3294510'>question</span> <span
  m='3294790'>about</span> <span m='3295040'>theta</span> <span m='3295280'>i's.</span>
  </p><p><span m='3296140'>So</span> <span m='3297170'>I</span> <span m='3297270'>want</span>
  <span m='3297430'>to</span> <span m='3297500'>count</span> <span m='3297790'>how</span>
  <span m='3298120'>many</span> <span m='3298400'>mountain</span> <span m='3298670'>valley</span>
  <span m='3298970'>patterns</span> <span m='3299360'>there</span> <span m='3299510'>are--</span>
  <span m='3301060'>mountain</span> <span m='3301300'>valley</span> <span m='3301580'>assignments</span>
  <span m='3302870'>that</span> <span m='3302990'>are</span> <span m='3303050'>flat</span>
  <span m='3303380'>foldable</span> <span m='3307550'>for</span> <span m='3307820'>a</span>
  <span m='3308090'>given</span> <span m='3308300'>crease</span> <span m='3308640'>pattern.</span>
  </p><p><span m='3310453'>AUDIENCE:</span> <span m='3310944'>So if you have a</span>
  <span m='3311435'>bunch of</span> <span m='3311926'>angles,</span> <span m='3312417'>consecutive</span>
  <span m='3312908'>theta</span> <span m='3313399'>i's</span> <span m='3313890'>are</span>
  <span m='3314381'>increasing?</span> </p><p><span m='3314872'>PROFESSOR:</span>
  <span m='3315370'>All</span> <span m='3315680'>the</span> <span m='3315780'>angles</span>
  <span m='3316160'>are</span> <span m='3316240'>consecutive</span> <span m='3316730'>increasing.</span>
  <span m='3317300'>Yeah,</span> <span m='3317530'>that</span> <span m='3317730'>pretty</span>
  <span m='3317950'>much</span> <span m='3318150'>works.</span> <span m='3318770'>In</span>
  <span m='3318840'>fact,</span> <span m='3319080'>what</span> <span m='3319210'>I</span>
  <span m='3319260'>need</span> <span m='3319470'>is</span> <span m='3319630'>the</span>
  <span m='3319790'>generic</span> <span m='3320180'>case,</span> <span m='3321410'>where</span>
  <span m='3321590'>all</span> <span m='3321760'>angles</span> <span m='3322060'>are</span>
  <span m='3322100'>different</span> <span m='3323210'>and</span> <span m='3324480'>they</span>
  <span m='3324650'>never</span> <span m='3324950'>become</span> <span m='3325450'>equal</span>
  <span m='3325800'>by</span> <span m='3325930'>folding,</span> <span m='3327300'>which
  is what</span> <span m='3327410'>generic</span> <span m='3327820'>means.</span>
  </p><p><span m='3328840'>So</span> <span m='3329010'>then</span> <span m='3329190'>there</span>
  <span m='3329280'>was</span> <span m='3329400'>only</span> <span m='3329770'>really</span>
  <span m='3330020'>one</span> <span m='3330290'>crimp</span> <span m='3330560'>I</span>
  <span m='3330620'>could</span> <span m='3330880'>do,</span> <span m='3331130'>which
  is</span> <span m='3331630'>the</span> <span m='3331710'>globally</span> <span m='3332140'>smallest</span>
  <span m='3333190'>angle.</span> <span m='3334970'>So</span> <span m='3335140'>actually,</span>
  <span m='3335660'>I still</span> <span m='3335700'>have</span> <span m='3335870'>two</span>
  <span m='3336060'>choices.</span> <span m='3336590'>I</span> <span m='3336700'>could</span>
  <span m='3336880'>do</span> <span m='3337010'>mountain then</span> <span m='3337440'>valley</span>
  <span m='3337840'>or</span> <span m='3337930'>valley</span> <span m='3338210'>then</span>
  <span m='3338330'>mountain.</span> <span m='3339510'>But</span> <span m='3339670'>I</span>
  <span m='3339740'>only</span> <span m='3339950'>have</span> <span m='3340070'>two</span>
  <span m='3340230'>choices</span> <span m='3340670'>for</span> <span m='3340820'>that</span>
  <span m='3341520'>crimp.</span> <span m='3342350'>Then</span> <span m='3342530'>I
  will</span> <span m='3342670'>have</span> <span m='3342870'>two</span> <span m='3343020'>choices</span>
  <span m='3343380'>for</span> <span m='3343450'>the</span> <span m='3343520'>next</span>
  <span m='3343760'>crimp,</span> <span m='3344100'>two</span> <span m='3344470'>choices
  for</span> <span m='3344930'>the</span> <span m='3345070'>next</span> <span m='3345350'>crimp.</span>
  <span m='3345560'>In</span> <span m='3345690'>general,</span> <span m='3346570'>I</span>
  <span m='3346700'>get</span> <span m='3346890'>2 to</span> <span m='3347060'>the</span>
  <span m='3347310'>n</span> <span m='3350720'>possible</span> <span m='3351380'>mountain</span>
  <span m='3351650'>valley</span> <span m='3351920'>assignments</span> <span m='3352520'>for</span>
  <span m='3352940'>the</span> <span m='3353040'>generic</span> <span m='3353460'>case.</span>
  </p><p><span m='3359500'>OK,</span> <span m='3359720'>what</span> <span m='3359890'>about,</span>
  <span m='3361510'>what's</span> <span m='3361850'>the</span> <span m='3361980'>opposite,</span>
  <span m='3362570'>where</span> <span m='3362730'>I</span> <span m='3362790'>get</span>
  <span m='3363010'>as</span> <span m='3363160'>much</span> <span m='3363570'>choice</span>
  <span m='3363860'>as</span> <span m='3363970'>possible?</span> </p><p><span m='3364470'>AUDIENCE:</span>
  <span m='3364930'>Isn't</span> <span m='3365390'>2 to the n</span> <span m='3365850'>every</span>
  <span m='3368150'>mountain valley</span> <span m='3368610'>assignment?</span> </p><p><span
  m='3369070'>PROFESSOR:</span> <span m='3369530'>Yes,</span> <span m='3369970'>2
  to</span> <span m='3370230'>the</span> <span m='3370400'>n--</span> <span m='3370670'>no--</span>
  <span m='3373560'>2 to</span> <span m='3373860'>the</span> <span m='3374000'>n</span>
  <span m='3374110'>over</span> <span m='3374270'>2.</span> <span m='3374500'>Thank</span>
  <span m='3374750'>you.</span> <span m='3374900'>Right.</span> </p><p><span m='3375290'>There</span>
  <span m='3375450'>are</span> <span m='3375520'>2 to</span> <span m='3375840'>the</span>
  <span m='3376040'>n</span> <span m='3376380'>conceivable</span> <span m='3377020'>mountain
  valley</span> <span m='3377490'>assignments.</span> <span m='3377960'>It can't</span>
  <span m='3378120'>be</span> <span m='3378210'>that</span> <span m='3378430'>big.</span>
  <span m='3379440'>Every</span> <span m='3379690'>time</span> <span m='3379880'>I</span>
  <span m='3379930'>do</span> <span m='3380040'>a</span> <span m='3380100'>crimp,</span>
  <span m='3380350'>I</span> <span m='3380440'>eat</span> <span m='3380640'>two</span>
  <span m='3380810'>creases,</span> <span m='3381210'>not</span> <span m='3381390'>one.</span>
  <span m='3381660'>That's</span> <span m='3381890'>what I</span> <span m='3382000'>forgot.</span>
  <span m='3383450'>Good.</span> </p><p><span m='3385090'>It's still</span> <span
  m='3385340'>pretty</span> <span m='3385540'>big</span> <span m='3385780'>though.</span>
  <span m='3386560'>It's</span> <span m='3387330'>like</span> <span m='3387510'>square</span>
  <span m='3387860'>root</span> <span m='3387960'>of all</span> <span m='3388060'>the</span>
  <span m='3388270'>possible</span> <span m='3388750'>things</span> <span m='3388940'>you</span>
  <span m='3389040'>could</span> <span m='3389170'>imagine</span> <span m='3389650'>are</span>
  <span m='3389950'>indeed</span> <span m='3390270'>feasible.</span> <span m='3392220'>What,
  from</span> <span m='3392410'>2 to</span> <span m='3392590'>the</span> <span m='3392700'>n</span>
  <span m='3392910'>to</span> <span m='3393070'>2 to the</span> <span m='3393170'>n</span>
  <span m='3393270'>over</span> <span m='3393400'>2.</span> <span m='3394580'>When
  would</span> <span m='3394720'>I</span> <span m='3394790'>get</span> <span m='3395030'>the</span>
  <span m='3395110'>most</span> <span m='3395490'>choice</span> <span m='3395880'>in</span>
  <span m='3396170'>crimping?</span> </p><p><span m='3397578'>AUDIENCE:</span> <span
  m='3398062'>All angles</span> <span m='3398546'>are equal.</span> </p><p><span m='3399030'>PROFESSOR:</span>
  <span m='3399300'>All angles</span> <span m='3399540'>are</span> <span m='3399620'>equal.</span>
  <span m='3400310'>That's</span> <span m='3400480'>the</span> <span m='3400820'>opposite</span>
  <span m='3401080'>extreme.</span> <span m='3402070'>And in</span> <span m='3402400'>this</span>
  <span m='3402580'>case--</span> <span m='3403840'>a little messier.</span> </p><p><span
  m='3425300'>When</span> <span m='3425450'>all</span> <span m='3425580'>the</span>
  <span m='3425670'>angles</span> <span m='3425980'>are</span> <span m='3426090'>equal,</span>
  <span m='3427250'>the</span> <span m='3427410'>only</span> <span m='3427740'>property</span>
  <span m='3428140'>you</span> <span m='3428260'>need--</span> <span m='3428570'>and</span>
  <span m='3428770'>you</span> <span m='3428880'>can</span> <span m='3429020'>see</span>
  <span m='3429150'>that</span> <span m='3429350'>from the</span> <span m='3429480'>proof--</span>
  <span m='3430300'>the</span> <span m='3430400'>only</span> <span m='3430600'>property</span>
  <span m='3430960'>you</span> <span m='3431030'>need</span> <span m='3431230'>is</span>
  <span m='3431430'>that the</span> <span m='3431520'>number</span> <span m='3431780'>mountains</span>
  <span m='3432110'>minus the</span> <span m='3432390'>number</span> <span m='3432600'>valleys</span>
  <span m='3432970'>is</span> <span m='3433120'>plus</span> <span m='3433330'>or</span>
  <span m='3433380'>minus</span> <span m='3433690'>2,</span> <span m='3435310'>and</span>
  <span m='3435930'>n</span> <span m='3436200'>is</span> <span m='3436320'>even.</span>
  <span m='3437430'>As</span> <span m='3437480'>long</span> <span m='3437630'>as</span>
  <span m='3437700'>you</span> <span m='3437790'>have</span> <span m='3437990'>that,</span>
  <span m='3440050'>we</span> <span m='3440490'>showed</span> <span m='3440790'>here,</span>
  <span m='3441280'>you're</span> <span m='3441480'>going</span> <span m='3441600'>to</span>
  <span m='3441660'>have--</span> <span m='3442300'>on</span> <span m='3442480'>alternation</span>
  <span m='3442970'>from</span> <span m='3443090'>mountain</span> <span m='3443340'>valley--</span>
  <span m='3443700'>that's</span> <span m='3443940'>a</span> <span m='3443970'>valid</span>
  <span m='3444270'>crimp,</span> <span m='3444480'>because</span> <span m='3444680'>all</span>
  <span m='3444780'>the</span> <span m='3444870'>angles</span> <span m='3445130'>are</span>
  <span m='3445170'>equal.</span> <span m='3446050'>And you</span> <span m='3446220'>keep</span>
  <span m='3446490'>going.</span> </p><p><span m='3447340'>So</span> <span m='3447430'>it's</span>
  <span m='3447550'>just,</span> <span m='3447740'>how</span> <span m='3447990'>do</span>
  <span m='3448060'>you</span> <span m='3448210'>disperse</span> <span m='3450030'>that</span>
  <span m='3450420'>many--</span> <span m='3451740'>how</span> <span m='3451890'>do</span>
  <span m='3451960'>I</span> <span m='3452050'>disperse</span> <span m='3453670'>n</span>
  <span m='3453860'>over</span> <span m='3454040'>2</span> <span m='3454240'>minus</span>
  <span m='3454630'>1</span> <span m='3455430'>mountains</span> <span m='3456960'>among</span>
  <span m='3457790'>n</span> <span m='3458170'>different</span> <span m='3458480'>positions.</span>
  <span m='3459440'>That's</span> <span m='3459650'>what</span> <span m='3459760'>this</span>
  <span m='3459940'>represents.</span> <span m='3460740'>And</span> <span m='3461130'>positions,</span>
  <span m='3461660'>how</span> <span m='3461830'>do</span> <span m='3461900'>I</span>
  <span m='3461990'>pick</span> <span m='3462320'>n</span> <span m='3462470'>over</span>
  <span m='3462630'>2</span> <span m='3462780'>minus</span> <span m='3463050'>1</span>
  <span m='3463210'>of</span> <span m='3463270'>them</span> <span m='3463420'>to</span>
  <span m='3463520'>be</span> <span m='3463640'>mountains.</span> <span m='3464540'>Or
  it</span> <span m='3464950'>could</span> <span m='3465140'>be</span> <span m='3465300'>n</span>
  <span m='3465510'>over</span> <span m='3465760'>2</span> <span m='3466000'>minus</span>
  <span m='3466250'>1</span> <span m='3466380'>of</span> <span m='3466430'>them</span>
  <span m='3466550'>are</span> <span m='3466650'>valleys.</span> <span m='3467890'>And</span>
  <span m='3468000'>that's</span> <span m='3468180'>this</span> <span m='3468300'>factor</span>
  <span m='3468580'>of</span> <span m='3468680'>2.</span> </p><p><span m='3469510'>So
  it</span> <span m='3469640'>could</span> <span m='3469800'>have</span> <span m='3469890'>more</span>
  <span m='3470050'>mountains</span> <span m='3470380'>or</span> <span m='3470430'>more</span>
  <span m='3470600'>valleys.</span> <span m='3471430'>And</span> <span m='3471620'>then</span>
  <span m='3471790'>you</span> <span m='3471880'>somehow</span> <span m='3472220'>place</span>
  <span m='3472590'>those</span> <span m='3473280'>among</span> <span m='3473540'>those.</span>
  <span m='3474020'>And</span> <span m='3474500'>if</span> <span m='3474630'>you</span>
  <span m='3474730'>don't</span> <span m='3474880'>know</span> <span m='3475000'>this</span>
  <span m='3475160'>notation,</span> <span m='3476430'>that's</span> <span m='3476780'>just</span>
  <span m='3477000'>what</span> <span m='3477110'>it</span> <span m='3477190'>means.</span>
  </p><p><span m='3478320'>If</span> <span m='3478450'>you</span> <span m='3478580'>want</span>
  <span m='3478770'>to</span> <span m='3478830'>know</span> <span m='3479990'>using</span>
  <span m='3480340'>other</span> <span m='3480570'>notation,</span> <span m='3482170'>it's</span>
  <span m='3482430'>like</span> <span m='3482680'>this,</span> <span m='3483270'>n</span>
  <span m='3483710'>over</span> <span m='3483930'>2</span> <span m='3484210'>minus</span>
  <span m='3484620'>1</span> <span m='3484890'>factorial,</span> <span m='3486460'>over</span>
  <span m='3486610'>2</span> <span m='3486900'>plus</span> <span m='3487300'>1</span>
  <span m='3487580'>factorial.</span> <span m='3488750'>If</span> <span m='3488810'>you</span>
  <span m='3488890'>don't</span> <span m='3489060'>know</span> <span m='3489190'>factorials,</span>
  <span m='3490810'>I'll</span> <span m='3490910'>tell</span> <span m='3491100'>you</span>
  <span m='3491170'>about</span> <span m='3491410'>them</span> <span m='3491530'>later.</span>
  <span m='3494160'>Cool.</span> </p><p><span m='3495910'>So</span> <span m='3496140'>that's</span>
  <span m='3496350'>kind</span> <span m='3496510'>of</span> <span m='3496580'>the</span>
  <span m='3496700'>end</span> <span m='3496850'>of</span> <span m='3496920'>the</span>
  <span m='3497000'>single</span> <span m='3497730'>vertex</span> <span m='3498120'>situation.</span>
  <span m='3502020'>Yeah,</span> <span m='3502490'>I</span> <span m='3502630'>think</span>
  <span m='3503060'>I'll</span> <span m='3503320'>mention</span> <span m='3503650'>one</span>
  <span m='3503780'>interesting</span> <span m='3504160'>open</span> <span m='3504400'>question</span>
  <span m='3504710'>here,</span> <span m='3505030'>which</span> <span m='3505120'>I</span>
  <span m='3505150'>would</span> <span m='3505280'>love</span> <span m='3505440'>to</span>
  <span m='3505540'>explore</span> <span m='3505950'>maybe</span> <span m='3506240'>in</span>
  <span m='3506370'>our</span> <span m='3506490'>problem</span> <span m='3506840'>session--</span>
  <span m='3509140'>which</span> <span m='3509330'>looks</span> <span m='3509510'>like</span>
  <span m='3509650'>it'll</span> <span m='3509770'>be</span> <span m='3509900'>Mondays</span>
  <span m='3510450'>at</span> <span m='3510770'>5:00,</span> <span m='3511570'>I</span>
  <span m='3511600'>think.</span> <span m='3514898'>This </span> <span m='3515300'>is</span>
  <span m='3515420'>one</span> <span m='3515670'>vertex,</span> <span m='3516450'>and</span>
  <span m='3516630'>we</span> <span m='3516720'>went</span> <span m='3516860'>through</span>
  <span m='3516960'>all</span> <span m='3517100'>this</span> <span m='3517210'>work</span>
  <span m='3517440'>to</span> <span m='3517540'>solve a</span> <span m='3517810'>single</span>
  <span m='3518120'>vertex</span> <span m='3518470'>situation.</span> <span m='3519000'>And</span>
  <span m='3519130'>it's</span> <span m='3519270'>interesting,</span> <span m='3520410'>as</span>
  <span m='3520630'>we'll</span> <span m='3520710'>see,</span> <span m='3521430'>to</span>
  <span m='3521690'>think</span> <span m='3521890'>about</span> <span m='3522160'>locally</span>
  <span m='3522730'>how</span> <span m='3522940'>each</span> <span m='3523040'>vertex</span>
  <span m='3523500'>behaves.</span> </p><p><span m='3525460'>But</span> <span m='3526360'>you</span>
  <span m='3526490'>would</span> <span m='3526620'>think,</span> <span m='3526830'>if</span>
  <span m='3526950'>you</span> <span m='3527040'>have</span> <span m='3527160'>a crease</span>
  <span m='3527460'>pattern</span> <span m='3527820'>with</span> <span m='3528040'>two</span>
  <span m='3528270'>vertices,</span> <span m='3529335'>it</span> <span m='3529650'>shouldn't</span>
  <span m='3529920'>be</span> <span m='3530020'>that</span> <span m='3530210'>much</span>
  <span m='3530380'>harder.</span> <span m='3531280'>So</span> <span m='3531380'>here</span>
  <span m='3531450'>we</span> <span m='3531540'>have</span> <span m='3531660'>linear</span>
  <span m='3531970'>time.</span> <span m='3532780'>How</span> <span m='3533060'>quickly</span>
  <span m='3533510'>can</span> <span m='3533740'>you</span> <span m='3533860'>tell</span>
  <span m='3534230'>whether</span> <span m='3534560'>a</span> <span m='3534770'>two
  vertex</span> <span m='3535190'>crease</span> <span m='3535370'>pattern</span> <span
  m='3536020'>is</span> <span m='3536160'>flat</span> <span m='3536390'>foldable?</span>
  </p><p><span m='3536920'>As</span> <span m='3536990'>far</span> <span m='3537170'>as</span>
  <span m='3537260'>I</span> <span m='3537320'>know,</span> <span m='3537560'>no</span>
  <span m='3537690'>one</span> <span m='3537800'>has</span> <span m='3537940'>looked</span>
  <span m='3538130'>at</span> <span m='3538200'>that</span> <span m='3538380'>problem.</span>
  <span m='3539760'>Surely,</span> <span m='3540450'>we</span> <span m='3540610'>can</span>
  <span m='3540740'>do</span> <span m='3540890'>it</span> <span m='3541000'>in</span>
  <span m='3541290'>quadratic</span> <span m='3541860'>time</span> <span m='3542390'>but</span>
  <span m='3542540'>maybe</span> <span m='3542810'>even</span> <span m='3543010'>linear</span>
  <span m='3543290'>time,</span> <span m='3543960'>I think.</span> <span m='3544560'>It
  can't</span> <span m='3544740'>be</span> <span m='3544820'>that</span> <span m='3545000'>hard,</span>
  <span m='3546240'>I</span> <span m='3546300'>think.</span> </p><p><span m='3548300'>In</span>
  <span m='3548430'>general,</span> <span m='3548840'>if</span> <span m='3548960'>I</span>
  <span m='3549030'>have</span> <span m='3549290'>a</span> <span m='3549350'>small</span>
  <span m='3549760'>number</span> <span m='3550100'>of</span> <span m='3550510'>vertices--</span>
  <span m='3551030'>say</span> <span m='3551310'>k</span> <span m='3551610'>vertices--</span>
  <span m='3552790'>much</span> <span m='3553050'>smaller</span> <span m='3553330'>than</span>
  <span m='3553490'>n</span> <span m='3554310'>creases,</span> <span m='3556420'>is</span>
  <span m='3556710'>there--</span> <span m='3557850'>for the</span> <span m='3557950'>algorithms</span>
  <span m='3558380'>people--</span> <span m='3558730'>is there</span> <span m='3558800'>fixed</span>
  <span m='3559030'>parameter</span> <span m='3559330'>tractable</span> <span m='3559890'>algorithm</span>
  <span m='3560310'>in</span> <span m='3560420'>k?</span> <span m='3561360'>Or</span>
  <span m='3561520'>can</span> <span m='3561680'>I</span> <span m='3561740'>get</span>
  <span m='3561930'>something--</span> <span m='3562450'>even</span> <span m='3562740'>getting</span>
  <span m='3563100'>something</span> <span m='3563440'>like</span> <span m='3563640'>n</span>
  <span m='3563850'>to</span> <span m='3564860'>some</span> <span m='3565110'>function</span>
  <span m='3565430'>of</span> <span m='3565510'>k,</span> <span m='3566700'>would</span>
  <span m='3566860'>be</span> <span m='3567050'>progress.</span> <span m='3567590'>I</span>
  <span m='3567650'>think</span> <span m='3567820'>this</span> <span m='3567930'>should</span>
  <span m='3568080'>be</span> <span m='3568180'>doable.</span> <span m='3569190'>But</span>
  <span m='3569360'>ideally,</span> <span m='3569860'>we</span> <span m='3569990'>get</span>
  <span m='3570630'>a</span> <span m='3570680'>running</span> <span m='3570920'>time</span>
  <span m='3571200'>that's</span> <span m='3572540'>exponential</span> <span m='3573300'>in</span>
  <span m='3573430'>k</span> <span m='3574290'>and</span> <span m='3574720'>linear</span>
  <span m='3575010'>in</span> <span m='3575100'>n.</span> <span m='3575800'>That</span>
  <span m='3576210'>would</span> <span m='3576310'>be</span> <span m='3576880'>my</span>
  <span m='3576970'>hope.</span> </p><p><span m='3578220'>Why</span> <span m='3578440'>do</span>
  <span m='3578540'>I</span> <span m='3578640'>say</span> <span m='3578940'>it</span>
  <span m='3579000'>has</span> <span m='3579190'>to</span> <span m='3579280'>be</span>
  <span m='3579410'>exponential?</span> <span m='3579960'>Because</span> <span m='3580330'>in</span>
  <span m='3580410'>general,</span> <span m='3580710'>if</span> <span m='3580810'>I</span>
  <span m='3580870'>give</span> <span m='3581070'>you</span> <span m='3581460'>a crease</span>
  <span m='3581600'>pattern</span> <span m='3581870'>with</span> <span m='3582050'>n</span>
  <span m='3582260'>vertices--</span> <span m='3582810'>lots</span> <span m='3583030'>of</span>
  <span m='3583090'>vertices--</span> <span m='3583960'>this</span> <span m='3584110'>problem</span>
  <span m='3584400'>is</span> <span m='3584510'>NP-complete,</span> <span m='3585570'>which</span>
  <span m='3585780'>is--</span> <span m='3586740'>there's</span> <span m='3587090'>not</span>
  <span m='3587330'>going</span> <span m='3587440'>to</span> <span m='3587490'>be</span>
  <span m='3587630'>a</span> <span m='3587680'>polynomial</span> <span m='3588200'>time</span>
  <span m='3588410'>algorithm</span> <span m='3588750'>for</span> <span m='3589040'>it.</span>
  <span m='3589460'>Nothing</span> <span m='3589760'>good.</span> </p><p><span m='3590910'>We</span>
  <span m='3591100'>will</span> <span m='3591210'>prove</span> <span m='3591420'>that</span>
  <span m='3591970'>next</span> <span m='3592570'>Wednesday.</span> <span m='3593610'>So</span>
  <span m='3593860'>I'll</span> <span m='3594230'>hold</span> <span m='3594470'>off</span>
  <span m='3594640'>on</span> <span m='3594700'>that</span> <span m='3594830'>a</span>
  <span m='3594880'>little</span> <span m='3595080'>bit.</span> <span m='3596640'>But</span>
  <span m='3596920'>for</span> <span m='3597050'>two</span> <span m='3597680'>vertices,</span>
  <span m='3598130'>how</span> <span m='3598300'>hard</span> <span m='3598490'>could</span>
  <span m='3598680'>it be?</span> <span m='3601540'>All</span> <span m='3601630'>right.</span>
  </p><p><span m='3623860'>I</span> <span m='3624010'>want</span> <span m='3624180'>to</span>
  <span m='3624250'>talk</span> <span m='3624440'>about</span> <span m='3624640'>one</span>
  <span m='3624810'>related</span> <span m='3625240'>topic.</span> <span m='3625610'>And</span>
  <span m='3625710'>then</span> <span m='3625850'>we</span> <span m='3625950'>will</span>
  <span m='3626100'>go</span> <span m='3626260'>to</span> <span m='3626450'>origami</span>
  <span m='3626850'>design</span> <span m='3628060'>and</span> <span m='3628290'>do</span>
  <span m='3628390'>a</span> <span m='3628430'>little</span> <span m='3628710'>bit</span>
  <span m='3628910'>on</span> <span m='3629050'>the</span> <span m='3629170'>tree</span>
  <span m='3629340'>method.</span> <span m='3630960'>But</span> <span m='3631250'>before</span>
  <span m='3631530'>we</span> <span m='3631640'>get</span> <span m='3631830'>there,</span>
  <span m='3633130'>I</span> <span m='3633180'>want</span> <span m='3633360'>to</span>
  <span m='3633430'>talk</span> <span m='3633640'>about</span> <span m='3633880'>local</span>
  <span m='3634210'>foldability,</span> <span m='3640830'>which is</span> <span m='3640980'>a</span>
  <span m='3641070'>cool</span> <span m='3641300'>topic.</span> <span m='3641800'>People</span>
  <span m='3641990'>tend</span> <span m='3642180'>to</span> <span m='3642240'>forget</span>
  <span m='3642520'>about</span> <span m='3642810'>it.</span> </p><p><span m='3643520'>I</span>
  <span m='3643650'>really</span> <span m='3643840'>like</span> <span m='3644050'>it.</span>
  <span m='3644230'>I</span> <span m='3644330'>think</span> <span m='3644380'>it would</span>
  <span m='3644510'>make</span> <span m='3644710'>a</span> <span m='3644770'>cool</span>
  <span m='3644950'>project</span> <span m='3645400'>also.</span> <span m='3646690'>It's</span>
  <span m='3646880'>a</span> <span m='3646930'>nice</span> <span m='3647140'>algorithm.</span>
  <span m='3647510'>It</span> <span m='3647550'>goes</span> <span m='3647740'>back</span>
  <span m='3647960'>to</span> <span m='3648960'>Bern</span> <span m='3649180'>and</span>
  <span m='3649250'>Hayes,</span> <span m='3649570'>1996.</span> <span m='3650750'>So</span>
  <span m='3650880'>it's</span> <span m='3651010'>also</span> <span m='3651870'>right
  at</span> <span m='3652050'>the</span> <span m='3652170'>beginning</span> <span
  m='3652680'>of</span> <span m='3653190'>origami</span> <span m='3653570'>mathematics.</span>
  </p><p><span m='3655860'>And</span> <span m='3656030'>it's</span> <span m='3656150'>this</span>
  <span m='3656310'>idea,</span> <span m='3657190'>all right,</span> <span m='3657530'>I</span>
  <span m='3657610'>give</span> <span m='3657760'>you</span> <span m='3657850'>a</span>
  <span m='3657900'>crease</span> <span m='3658200'>pattern</span> <span m='3658770'>now</span>
  <span m='3659230'>arbitrarily</span> <span m='3659780'>many</span> <span m='3659980'>vertices.</span>
  <span m='3661410'>And</span> <span m='3662460'>if</span> <span m='3662620'>I</span>
  <span m='3662700'>ask</span> <span m='3662940'>you,</span> <span m='3663060'>does</span>
  <span m='3663250'>it</span> <span m='3663380'>fold</span> <span m='3663620'>flat?</span>
  <span m='3663910'>That's</span> <span m='3664130'>NP-complete--</span> <span m='3664770'>intractable--</span>
  <span m='3665820'>same</span> <span m='3666080'>paper.</span> <span m='3667410'>But</span>
  <span m='3667620'>what</span> <span m='3667760'>if</span> <span m='3667870'>I</span>
  <span m='3667950'>ask</span> <span m='3668230'>you</span> <span m='3668340'>just</span>
  <span m='3668550'>to</span> <span m='3668630'>give</span> <span m='3668880'>me</span>
  <span m='3669100'>a</span> <span m='3669140'>mountain</span> <span m='3669410'>valley</span>
  <span m='3669730'>assignment</span> <span m='3670890'>that</span> <span m='3671010'>might</span>
  <span m='3671360'>fold</span> <span m='3671610'>flat?</span> <span m='3673440'>Well,</span>
  <span m='3674490'>that's</span> <span m='3674820'>also</span> <span m='3675120'>NP-complete.</span>
  </p><p><span m='3675710'>But</span> <span m='3676350'>if</span> <span m='3677070'>you</span>
  <span m='3677280'>actually</span> <span m='3677730'>want</span> <span m='3678040'>it
  to fold</span> <span m='3678360'>flat,</span> <span m='3678650'>this is</span> <span
  m='3678760'>really</span> <span m='3678960'>the</span> <span m='3679040'>same</span>
  <span m='3679290'>problem.</span> <span m='3680110'>But</span> <span m='3680750'>if</span>
  <span m='3680930'>I</span> <span m='3681060'>ask</span> <span m='3681350'>you,</span>
  <span m='3681640'>give me</span> <span m='3681970'>a</span> <span m='3682000'>mountain</span>
  <span m='3682260'>valley</span> <span m='3682560'>assignment,</span> <span m='3683480'>so</span>
  <span m='3683620'>that if</span> <span m='3683850'>I</span> <span m='3683950'>checked</span>
  <span m='3684340'>every</span> <span m='3684550'>vertex</span> <span m='3685070'>according</span>
  <span m='3685400'>to</span> <span m='3685480'>this</span> <span m='3685660'>algorithm,</span>
  <span m='3686570'>at</span> <span m='3686640'>least</span> <span m='3687010'>every</span>
  <span m='3687220'>vertex</span> <span m='3687700'>folds</span> <span m='3687950'>flat.</span>
  <span m='3689082'>That</span> <span m='3689490'>would</span> <span m='3689720'>seem</span>
  <span m='3690000'>nice.</span> </p><p><span m='3692650'>Definitely,</span> <span
  m='3693110'>I have</span> <span m='3693320'>to</span> <span m='3693410'>find</span>
  <span m='3693600'>a</span> <span m='3693650'>mountain</span> <span m='3693860'>valley</span>
  <span m='3694100'>assignment</span> <span m='3694400'>that</span> <span m='3694500'>satisfies</span>
  <span m='3695430'>these</span> <span m='3695640'>conditions,</span> <span m='3696240'>that</span>
  <span m='3696430'>as</span> <span m='3696630'>I</span> <span m='3696690'>do</span>
  <span m='3696830'>successive</span> <span m='3697330'>crimps,</span> <span m='3698440'>every</span>
  <span m='3698690'>vertex--</span> <span m='3699130'>if</span> <span m='3699270'>I</span>
  <span m='3699330'>cut</span> <span m='3699650'>out</span> <span m='3699840'>the</span>
  <span m='3699910'>vertex</span> <span m='3700310'>separately,</span> <span m='3700790'>it</span>
  <span m='3700910'>would</span> <span m='3701070'>fold</span> <span m='3701280'>flat.</span>
  <span m='3701570'>This</span> <span m='3701800'>is</span> <span m='3701940'>the</span>
  <span m='3702020'>notion</span> <span m='3702280'>of</span> <span m='3702410'>local</span>
  <span m='3702730'>foldability.</span> <span m='3703860'>And</span> <span m='3704030'>there's</span>
  <span m='3704260'>a</span> <span m='3704320'>linear</span> <span m='3704620'>time</span>
  <span m='3704840'>algorithm</span> <span m='3706370'>to</span> <span m='3706490'>give</span>
  <span m='3706750'>you</span> <span m='3707100'>a</span> <span m='3707170'>mountain</span>
  <span m='3707460'>valley</span> <span m='3707720'>assignment</span> <span m='3708700'>that</span>
  <span m='3709010'>ought</span> <span m='3709280'>to</span> <span m='3709420'>work,</span>
  <span m='3709810'>in</span> <span m='3709960'>that</span> <span m='3710150'>at</span>
  <span m='3710320'>each</span> <span m='3710520'>vertex</span> <span m='3710920'>it</span>
  <span m='3711010'>works.</span> <span m='3711310'>It</span> <span m='3711410'>still</span>
  <span m='3711650'>may</span> <span m='3711760'>not</span> <span m='3711930'>work</span>
  <span m='3712200'>globally</span> <span m='3712555'>for</span> <span m='3712910'>some</span>
  <span m='3713150'>other</span> <span m='3713320'>reason.</span> <span m='3716360'>But</span>
  <span m='3716845'>it's</span> <span m='3717330'>pretty</span> <span m='3717560'>good.</span>
  </p><p><span m='3719290'>I</span> <span m='3719450'>think</span> <span m='3719600'>this</span>
  <span m='3719760'>would</span> <span m='3719890'>be,</span> <span m='3720110'>actually,</span>
  <span m='3720420'>pretty</span> <span m='3720650'>practical.</span> <span m='3721360'>I</span>
  <span m='3721490'>think</span> <span m='3721680'>in</span> <span m='3721770'>a</span>
  <span m='3721830'>lot</span> <span m='3722140'>of</span> <span m='3724030'>real</span>
  <span m='3724280'>world</span> <span m='3724580'>origami</span> <span m='3725020'>settings--</span>
  <span m='3725440'>when</span> <span m='3725550'>you're</span> <span m='3725670'>doing</span>
  <span m='3726480'>flat</span> <span m='3726740'>folding</span> <span m='3727100'>anyway--</span>
  <span m='3729660'>locally</span> <span m='3730310'>foldable</span> <span m='3730780'>is</span>
  <span m='3730880'>going</span> <span m='3730980'>to</span> <span m='3731030'>be</span>
  <span m='3731140'>enough</span> <span m='3731490'>to</span> <span m='3731630'>be</span>
  <span m='3731780'>globally</span> <span m='3732170'>foldable.</span> <span m='3733430'>That's</span>
  <span m='3733620'>a</span> <span m='3733670'>guess.</span> <span m='3735010'>I</span>
  <span m='3735090'>don't</span> <span m='3735220'>know</span> <span m='3735320'>if</span>
  <span m='3735420'>it's</span> <span m='3735550'>true.</span> <span m='3742520'>Consistent</span>
  <span m='3744320'>mountain</span> <span m='3744600'>valley</span> <span m='3744910'>assignment,</span>
  <span m='3748290'>if</span> <span m='3748530'>there</span> <span m='3748710'>is</span>
  <span m='3748840'>one,</span> <span m='3756880'>so that</span> <span m='3757310'>each</span>
  <span m='3758520'>vertex</span> <span m='3763360'>locally</span> <span m='3763930'>folds</span>
  <span m='3764230'>flat.</span> </p><p><span m='3785470'>Let</span> <span m='3785740'>me</span>
  <span m='3789130'>try</span> <span m='3789280'>to</span> <span m='3789380'>concoct</span>
  <span m='3789840'>a</span> <span m='3789880'>small</span> <span m='3790210'>example</span>
  <span m='3790710'>that's</span> <span m='3790860'>relevant</span> <span m='3791230'>here--</span>
  <span m='3800620'>got to</span> <span m='3801115'>think.</span> <span m='3812010'>Yes,
  I</span> <span m='3812140'>think</span> <span m='3812330'>that</span> <span m='3812490'>works.</span>
  <span m='3812890'>All right,</span> <span m='3813100'>here</span> <span m='3813410'>we
  go.</span> <span m='3815610'>I think</span> <span m='3815770'>this</span> <span
  m='3815910'>is</span> <span m='3816030'>in</span> <span m='3816120'>the</span> <span
  m='3816220'>textbook.</span> <span m='3816690'>I</span> <span m='3816740'>remember</span>
  <span m='3817030'>drawing</span> <span m='3817400'>it</span> <span m='3817520'>in</span>
  <span m='3817610'>the</span> <span m='3817700'>past</span> <span m='3820670'>three</span>
  <span m='3820890'>years</span> <span m='3821140'>ago or</span> <span m='3821460'>whatever.</span>
  </p><p><span m='3823590'>So</span> <span m='3823700'>here's</span> <span m='3823930'>a</span>
  <span m='3823980'>crease</span> <span m='3824220'>pattern</span> <span m='3825895'>on
  a</span> <span m='3826330'>square</span> <span m='3826610'>or</span> <span m='3826890'>whatever.</span>
  </p><p><span m='3827180'>AUDIENCE:</span> <span m='3827470'>The top one</span> <span
  m='3827943'>should have--</span> </p><p><span m='3828416'>PROFESSOR:</span> <span
  m='3828890'>Yes,</span> <span m='3829640'>it should</span> <span m='3829800'>have</span>
  <span m='3830140'>this.</span> <span m='3831440'>Thank</span> <span m='3831570'>you.</span>
  <span m='3833720'>So</span> <span m='3833870'>this</span> <span m='3834120'>satisfies</span>
  <span m='3835050'>Kawasaki's</span> <span m='3835650'>theorem--</span> <span m='3835870'>that</span>
  <span m='3836000'>was</span> <span m='3836140'>the</span> <span m='3836210'>hard</span>
  <span m='3836450'>part--</span> <span m='3837130'>because</span> <span m='3837250'>these</span>
  <span m='3837460'>angles</span> <span m='3837830'>sum</span> <span m='3838030'>to</span>
  <span m='3838110'>180.</span> <span m='3839350'>And it's</span> <span m='3839590'>symmetric</span>
  <span m='3840495'>all</span> <span m='3840760'>around.</span> </p><p><span m='3841500'>OK,</span>
  <span m='3843321'>these</span> <span m='3843750'>angles</span> <span m='3844170'>are</span>
  <span m='3844370'>the</span> <span m='3844450'>smallest.</span> <span m='3845080'>They
  are</span> <span m='3845500'>60</span> <span m='3845860'>degrees.</span> <span m='3847460'>This
  is</span> <span m='3847540'>an</span> <span m='3847630'>equilateral</span> <span
  m='3848060'>triangle.</span> <span m='3849590'>So</span> <span m='3849710'>we</span>
  <span m='3849820'>have</span> <span m='3849970'>this--</span> <span m='3850590'>not</span>
  <span m='3850740'>quite</span> <span m='3850910'>the</span> <span m='3850990'>generic</span>
  <span m='3851320'>case, but</span> <span m='3851520'>we</span> <span m='3851750'>have</span>
  <span m='3851950'>the</span> <span m='3852430'>smallest</span> <span m='3852860'>angle
  is</span> <span m='3853180'>surrounded</span> <span m='3854360'>by</span> <span
  m='3854860'>two</span> <span m='3855390'>larger</span> <span m='3855740'>angles.</span>
  <span m='3856290'>Therefore,</span> <span m='3856630'>one</span> <span m='3856790'>of</span>
  <span m='3856850'>these</span> <span m='3857030'>is</span> <span m='3857120'>a</span>
  <span m='3857160'>mountain;</span> <span m='3857840'>the other</span> <span m='3857980'>is</span>
  <span m='3858190'>a</span> <span m='3858230'>valley.</span> </p><p><span m='3859480'>That</span>
  <span m='3859670'>means</span> <span m='3860640'>that</span> <span m='3860850'>these</span>
  <span m='3861140'>two</span> <span m='3861370'>creases</span> <span m='3862300'>have</span>
  <span m='3862530'>to</span> <span m='3862620'>have</span> <span m='3862930'>different</span>
  <span m='3863370'>assignments--</span> <span m='3863960'>I'm</span> <span m='3864080'>going</span>
  <span m='3864200'>to</span> <span m='3864270'>write</span> <span m='3864440'>a</span>
  <span m='3864500'>not</span> <span m='3864750'>equal</span> <span m='3865020'>sign.</span>
  <span m='3866380'>One of</span> <span m='3866630'>these</span> <span m='3866820'>is
  a mountain, and</span> <span m='3867060'>the</span> <span m='3867160'>other is a</span>
  <span m='3867350'>valley.</span> <span m='3867610'>They</span> <span m='3867700'>can't</span>
  <span m='3867920'>be</span> <span m='3868030'>the</span> <span m='3868110'>same.</span>
  <span m='3868800'>Also,</span> <span m='3869630'>these</span> <span m='3869860'>two</span>
  <span m='3870450'>cannot</span> <span m='3870690'>be</span> <span m='3870780'>the</span>
  <span m='3870860'>same.</span> <span m='3871170'>Also,</span> <span m='3871450'>these</span>
  <span m='3871720'>two</span> <span m='3872010'>cannot</span> <span m='3872330'>be</span>
  <span m='3872660'>the</span> <span m='3872740'>same.</span> </p><p><span m='3873410'>That's</span>
  <span m='3873680'>not</span> <span m='3873880'>possible.</span> <span m='3875340'>Because</span>
  <span m='3875710'>I've</span> <span m='3875800'>got</span> <span m='3876040'>three,</span>
  <span m='3876710'>it has</span> <span m='3876950'>to</span> <span m='3877050'>alternate.</span>
  <span m='3877640'>You</span> <span m='3877760'>can</span> <span m='3877990'>alternate</span>
  <span m='3878420'>three</span> <span m='3878610'>times.</span> <span m='3879570'>You
  can</span> <span m='3879690'>only</span> <span m='3879900'>alternative</span> <span
  m='3880400'>at even</span> <span m='3880610'>number</span> <span m='3880860'>of</span>
  <span m='3880930'>times.</span> </p><p><span m='3882540'>Two</span> <span m='3882890'>of</span>
  <span m='3883240'>these are</span> <span m='3883480'>mountains.</span> <span m='3883960'>One
  is</span> <span m='3884190'>valley.</span> <span m='3884690'>And</span> <span m='3884780'>then</span>
  <span m='3885350'>you've</span> <span m='3885620'>got</span> <span m='3885750'>a</span>
  <span m='3885800'>problem.</span> <span m='3886450'>OK,</span> <span m='3886680'>so</span>
  <span m='3886770'>this</span> <span m='3886960'>thing</span> <span m='3887130'>is</span>
  <span m='3887220'>not</span> <span m='3887440'>flat</span> <span m='3887640'>foldable.</span>
  </p><p><span m='3888640'>And</span> <span m='3888840'>this</span> <span m='3889030'>algorithm</span>
  <span m='3889550'>will</span> <span m='3889690'>tell</span> <span m='3889940'>you</span>
  <span m='3890080'>that.</span> <span m='3890570'>Because it will</span> <span m='3890760'>say,</span>
  <span m='3890980'>hey,</span> <span m='3891250'>I</span> <span m='3891350'>can't</span>
  <span m='3891570'>even</span> <span m='3891750'>find</span> <span m='3892070'>a</span>
  <span m='3892100'>mountain</span> <span m='3892370'>valley</span> <span m='3892680'>assignment</span>
  <span m='3893400'>that</span> <span m='3893540'>could</span> <span m='3893700'>possibly</span>
  <span m='3894340'>fold</span> <span m='3894640'>each</span> <span m='3894800'>vertex</span>
  <span m='3895190'>flat.</span> <span m='3897420'>So</span> <span m='3900150'>this
  is</span> <span m='3900330'>a</span> <span m='3900380'>nice</span> <span m='3900600'>algorithm.</span>
  <span m='3902100'>At least,</span> <span m='3902220'>it</span> <span m='3902340'>will</span>
  <span m='3902600'>detect</span> <span m='3903000'>annoying</span> <span m='3903340'>situations</span>
  <span m='3903920'>like</span> <span m='3904100'>that.</span> </p><p><span m='3906700'>So</span>
  <span m='3908750'>in</span> <span m='3908940'>order</span> <span m='3909130'>to</span>
  <span m='3909260'>solve</span> <span m='3909590'>this,</span> <span m='3909780'>we're</span>
  <span m='3909920'>going</span> <span m='3910210'>to</span> <span m='3910360'>use--</span>
  <span m='3911320'>and</span> <span m='3911750'>I'm</span> <span m='3911850'>just</span>
  <span m='3912010'>going</span> <span m='3912100'>to</span> <span m='3912170'>sketch</span>
  <span m='3912510'>how</span> <span m='3912640'>this</span> <span m='3912800'>algorithm</span>
  <span m='3913150'>works--</span> <span m='3913810'>we're</span> <span m='3913950'>going</span>
  <span m='3914050'>to</span> <span m='3914090'>use</span> <span m='3914370'>this</span>
  <span m='3914530'>characterization</span> <span m='3915830'>and</span> <span m='3915980'>this</span>
  <span m='3916150'>idea</span> <span m='3916490'>that</span> <span m='3916620'>we</span>
  <span m='3916750'>can</span> <span m='3916890'>really</span> <span m='3917140'>find</span>
  <span m='3917560'>all</span> <span m='3917950'>possible</span> <span m='3918500'>mountain</span>
  <span m='3918770'>valley</span> <span m='3919040'>assignments</span> <span m='3919910'>just</span>
  <span m='3920090'>by</span> <span m='3920190'>trying</span> <span m='3920620'>all</span>
  <span m='3920930'>the</span> <span m='3921020'>possible</span> <span m='3921550'>crimp</span>
  <span m='3921750'>sequences.</span> <span m='3922930'>Now,</span> <span m='3922990'>there
  are</span> <span m='3923160'>exponentially</span> <span m='3923720'>many.</span>
  <span m='3924050'>So</span> <span m='3924270'>it's</span> <span m='3924390'>not</span>
  <span m='3924510'>like</span> <span m='3924680'>I'm</span> <span m='3924800'>actually</span>
  <span m='3925070'>going</span> <span m='3925170'>to</span> <span m='3925230'>try</span>
  <span m='3925430'>them</span> <span m='3925590'>all.</span> <span m='3926270'>But</span>
  <span m='3926440'>I</span> <span m='3926520'>need</span> <span m='3926720'>to</span>
  <span m='3927010'>explore</span> <span m='3927420'>that</span> <span m='3927630'>space</span>
  <span m='3927970'>of</span> <span m='3928400'>candidate</span> <span m='3928930'>crimps</span>
  <span m='3930220'>and</span> <span m='3930400'>see</span> <span m='3930530'>what</span>
  <span m='3930640'>happens.</span> </p><p><span m='3936850'>So</span> <span m='3939020'>the</span>
  <span m='3939180'>idea</span> <span m='3939900'>is</span> <span m='3940850'>kind</span>
  <span m='3941200'>of</span> <span m='3941300'>crazy.</span> <span m='3943300'>The</span>
  <span m='3943400'>beginning</span> <span m='3943680'>of the</span> <span m='3943960'>algorithm</span>
  <span m='3944370'>is</span> <span m='3945290'>fold</span> <span m='3945700'>each</span>
  <span m='3945860'>vertex</span> <span m='3946260'>flat--</span> <span m='3947070'>somehow.</span>
  <span m='3948570'>I</span> <span m='3948640'>don't</span> <span m='3948800'>care</span>
  <span m='3949010'>how.</span> <span m='3950150'>Just</span> <span m='3950540'>pick</span>
  <span m='3950810'>a crimp,</span> <span m='3951190'>do</span> <span m='3951340'>it.</span>
  <span m='3951520'>Pick</span> <span m='3951700'>a</span> <span m='3951770'>crimp,</span>
  <span m='3952070'>do</span> <span m='3952210'>it--</span> <span m='3953170'>separately</span>
  <span m='3953710'>for</span> <span m='3953840'>each</span> <span m='3953980'>vertex.</span>
  <span m='3954400'>They're</span> <span m='3954500'>not</span> <span m='3954680'>going</span>
  <span m='3954770'>to</span> <span m='3954830'>be</span> <span m='3954980'>compatible.</span>
  </p><p><span m='3956440'>And</span> <span m='3956630'>don't</span> <span m='3956790'>look</span>
  <span m='3956970'>at</span> <span m='3957060'>the</span> <span m='3957150'>mountain</span>
  <span m='3957440'>valley</span> <span m='3957810'>assignment</span> <span m='3958450'>you</span>
  <span m='3958920'>get.</span> <span m='3959270'>But</span> <span m='3959410'>look</span>
  <span m='3959700'>at</span> <span m='3959990'>the</span> <span m='3960280'>crimping</span>
  <span m='3960730'>sequence</span> <span m='3961140'>you</span> <span m='3961220'>get.</span>
  <span m='3962460'>So</span> <span m='3962810'>here,</span> <span m='3963220'>let's</span>
  <span m='3963570'>do</span> <span m='3963750'>a</span> <span m='3963780'>little</span>
  <span m='3964020'>example--</span> <span m='3966880'>a</span> <span m='3967340'>non-trivial</span>
  <span m='3968090'>example.</span> </p><p><span m='3968650'>So</span> <span m='3969000'>here,</span>
  <span m='3969160'>we</span> <span m='3969240'>have the</span> <span m='3969600'>peace</span>
  <span m='3969850'>sign,</span> <span m='3970540'>and</span> <span m='3971080'>these</span>
  <span m='3971290'>two</span> <span m='3971440'>angles</span> <span m='3971740'>are</span>
  <span m='3971830'>equal.</span> <span m='3972260'>They're</span> <span m='3972380'>smallest.</span>
  <span m='3973190'>I</span> <span m='3973290'>could</span> <span m='3973590'>crimp</span>
  <span m='3973870'>this</span> <span m='3974090'>angle</span> <span m='3974360'>first,</span>
  <span m='3975150'>or</span> <span m='3975410'>I</span> <span m='3975470'>could</span>
  <span m='3975630'>crimp</span> <span m='3975890'>this</span> <span m='3976090'>angle</span>
  <span m='3976320'>first.</span> <span m='3976650'>I</span> <span m='3976690'>have</span>
  <span m='3976800'>a</span> <span m='3976860'>choice.</span> <span m='3977980'>So</span>
  <span m='3978250'>I'll</span> <span m='3978340'>draw</span> <span m='3978480'>both</span>
  <span m='3978760'>of</span> <span m='3978810'>them.</span> </p><p><span m='3983080'>If</span>
  <span m='3983310'>I</span> <span m='3983400'>crimp</span> <span m='3984260'>this</span>
  <span m='3984560'>angle</span> <span m='3984800'>first,</span> <span m='3985910'>I</span>
  <span m='3986030'>know</span> <span m='3986860'>these</span> <span m='3987090'>guys</span>
  <span m='3987340'>are</span> <span m='3987440'>paired</span> <span m='3987710'>up</span>
  <span m='3987990'>in</span> <span m='3988140'>the</span> <span m='3988220'>sense</span>
  <span m='3988550'>that</span> <span m='3988650'>they</span> <span m='3988780'>must</span>
  <span m='3989090'>be</span> <span m='3989240'>not</span> <span m='3989490'>equal--</span>
  <span m='3989810'>one's</span> <span m='3990030'>mountain and</span> <span m='3990390'>one's</span>
  <span m='3990620'>valley.</span> <span m='3991730'>After</span> <span m='3992060'>I</span>
  <span m='3992110'>do</span> <span m='3992250'>that</span> <span m='3992460'>crimp--</span>
  <span m='3992820'>just</span> <span m='3993070'>like</span> <span m='3993280'>in</span>
  <span m='3993420'>the</span> <span m='3994070'>real</span> <span m='3994280'>example</span>
  <span m='3994660'>I</span> <span m='3994750'>had--</span> <span m='3996550'>this</span>
  <span m='3996910'>angle will</span> <span m='3997190'>equal</span> <span m='3997360'>that</span>
  <span m='3997530'>angle.</span> <span m='3998120'>And</span> <span m='3998300'>these</span>
  <span m='3998530'>two</span> <span m='3998660'>guys</span> <span m='3999520'>must</span>
  <span m='3999840'>have</span> <span m='4000240'>equal</span> <span m='4001640'>assignments.</span>
  <span m='4002160'>They</span> <span m='4002220'>must</span> <span m='4002430'>be</span>
  <span m='4002530'>both</span> <span m='4002790'>mountain</span> <span m='4003050'>or</span>
  <span m='4003150'>both</span> <span m='4003370'>valley.</span> </p><p><span m='4004480'>In</span>
  <span m='4004630'>this</span> <span m='4004780'>situation,</span> <span m='4006130'>these</span>
  <span m='4006360'>two</span> <span m='4006500'>guys</span> <span m='4007410'>are</span>
  <span m='4007560'>not</span> <span m='4007760'>equal,</span> <span m='4008850'>if
  I</span> <span m='4009130'>crimp</span> <span m='4009400'>this</span> <span m='4009730'>pair</span>
  <span m='4010130'>first.</span> <span m='4011100'>And</span> <span m='4011290'>these</span>
  <span m='4011450'>two</span> <span m='4011550'>guys</span> <span m='4011770'>must</span>
  <span m='4011970'>be</span> <span m='4012160'>equal--</span> <span m='4012550'>equal</span>
  <span m='4012910'>now in</span> <span m='4013160'>the</span> <span m='4013220'>sense</span>
  <span m='4013470'>of</span> <span m='4013800'>being</span> <span m='4013960'>mountain</span>
  <span m='4014280'>or</span> <span m='4014340'>valley.</span> <span m='4016500'>OK,</span>
  <span m='4016990'>so</span> <span m='4018430'>there are</span> <span m='4018670'>still</span>
  <span m='4019330'>exponentially</span> <span m='4019940'>many</span> <span m='4020170'>possibilities</span>
  <span m='4020840'>in</span> <span m='4020920'>how</span> <span m='4021090'>to</span>
  <span m='4021190'>do</span> <span m='4021310'>this.</span> </p><p><span m='4021640'>But</span>
  <span m='4022080'>just</span> <span m='4022300'>pick</span> <span m='4022500'>one--</span>
  <span m='4022940'>pick</span> <span m='4023210'>one</span> <span m='4023570'>of</span>
  <span m='4023660'>these</span> <span m='4023850'>ways</span> <span m='4024150'>of</span>
  <span m='4024230'>pairing</span> <span m='4024820'>up.</span> <span m='4025000'>You're</span>
  <span m='4025080'>going</span> <span m='4025180'>to</span> <span m='4025250'>pair</span>
  <span m='4025560'>up</span> <span m='4026280'>each</span> <span m='4026510'>of</span>
  <span m='4026780'>the</span> <span m='4026990'>n creases</span> <span m='4027540'>into</span>
  <span m='4027710'>n</span> <span m='4027900'>over</span> <span m='4028080'>2</span>
  <span m='4028240'>pairs.</span> <span m='4029830'>And</span> <span m='4030790'>they're</span>
  <span m='4031000'>going</span> <span m='4031100'>to</span> <span m='4031140'>have</span>
  <span m='4031300'>some</span> <span m='4031450'>not</span> <span m='4031640'>equal</span>
  <span m='4031990'>and</span> <span m='4032110'>equal</span> <span m='4032340'>signs.</span>
  </p><p><span m='4034550'>So</span> <span m='4034740'>now,</span> <span m='4035140'>if</span>
  <span m='4035280'>you</span> <span m='4035380'>imagine</span> <span m='4036070'>the</span>
  <span m='4036170'>general</span> <span m='4036520'>picture,</span> <span m='4036850'>like</span>
  <span m='4037040'>here,</span> <span m='4038260'>for</span> <span m='4038450'>example,</span>
  <span m='4039100'>I</span> <span m='4039200'>might</span> <span m='4039340'>get--</span>
  <span m='4039750'>in</span> <span m='4040060'>this</span> <span m='4040280'>pattern,</span>
  <span m='4040630'>I</span> <span m='4040730'>would</span> <span m='4040900'>be</span>
  <span m='4041040'>forced</span> <span m='4041400'>to</span> <span m='4041480'>get</span>
  <span m='4041680'>not</span> <span m='4041860'>equals</span> <span m='4042710'>and</span>
  <span m='4043050'>these</span> <span m='4043290'>guys</span> <span m='4043520'>paired</span>
  <span m='4043790'>up.</span> <span m='4045160'>And</span> <span m='4045290'>in</span>
  <span m='4045370'>general,</span> <span m='4045830'>I</span> <span m='4045870'>want</span>
  <span m='4046020'>to</span> <span m='4046070'>look</span> <span m='4046410'>at</span>
  <span m='4047430'>these</span> <span m='4047810'>kinds</span> <span m='4048130'>of</span>
  <span m='4048210'>cycles.</span> <span m='4051450'>If</span> <span m='4053020'>I</span>
  <span m='4053110'>come</span> <span m='4053360'>into</span> <span m='4053550'>a</span>
  <span m='4053600'>vertex--</span> <span m='4055620'>here's</span> <span m='4056300'>a</span>
  <span m='4056350'>vertex--</span> <span m='4057150'>it's</span> <span m='4057310'>paired</span>
  <span m='4057550'>up</span> <span m='4057660'>with</span> <span m='4057760'>somebody.</span>
  </p><p><span m='4058970'>So</span> <span m='4059040'>if I</span> <span m='4059120'>come</span>
  <span m='4059340'>in</span> <span m='4059410'>here,</span> <span m='4059810'>I</span>
  <span m='4059930'>can</span> <span m='4060150'>go</span> <span m='4060320'>out</span>
  <span m='4060970'>somewhere.</span> <span m='4061900'>And</span> <span m='4062650'>I</span>
  <span m='4062720'>come</span> <span m='4062930'>to</span> <span m='4063010'>this</span>
  <span m='4063200'>vertex,</span> <span m='4063620'>it's</span> <span m='4063820'>paired</span>
  <span m='4064070'>with</span> <span m='4064180'>somebody.</span> <span m='4065260'>So</span>
  <span m='4065590'>I'm</span> <span m='4065750'>going</span> <span m='4065870'>to</span>
  <span m='4065930'>just--</span> <span m='4066380'>I</span> <span m='4066510'>can</span>
  <span m='4066660'>keep</span> <span m='4066860'>wandering</span> <span m='4067300'>around.</span>
  <span m='4068380'>And</span> <span m='4068530'>in</span> <span m='4068610'>general,</span>
  <span m='4068970'>there will</span> <span m='4069220'>be</span> <span m='4069650'>a</span>
  <span m='4069730'>bunch</span> <span m='4070090'>of</span> <span m='4070200'>these</span>
  <span m='4071530'>paths</span> <span m='4071815'>that</span> <span m='4072100'>you</span>
  <span m='4072200'>can</span> <span m='4072370'>follow.</span> </p><p><span m='4073690'>What
  could</span> <span m='4073900'>the</span> <span m='4074000'>paths</span> <span m='4074380'>do?</span>
  <span m='4074650'>They</span> <span m='4075080'>either</span> <span m='4076050'>close</span>
  <span m='4076330'>up</span> <span m='4076490'>on</span> <span m='4076610'>themselves--</span>
  <span m='4077800'>maybe</span> <span m='4078090'>things</span> <span m='4078350'>are</span>
  <span m='4078440'>paired</span> <span m='4078760'>up</span> <span m='4079630'>in</span>
  <span m='4079770'>such</span> <span m='4080040'>a</span> <span m='4080100'>way</span>
  <span m='4080320'>that</span> <span m='4080520'>you</span> <span m='4081580'>make</span>
  <span m='4081830'>a</span> <span m='4081870'>return</span> <span m='4082480'>trip.</span>
  <span m='4083660'>Or</span> <span m='4084040'>it</span> <span m='4084170'>could</span>
  <span m='4084370'>be</span> <span m='4084820'>some</span> <span m='4085110'>other</span>
  <span m='4085350'>path.</span> </p><p><span m='4085880'>Let</span> <span m='4086350'>me</span>
  <span m='4086470'>draw</span> <span m='4086820'>a</span> <span m='4086880'>dotted</span>
  <span m='4087280'>path.</span> <span m='4088305'>It</span> <span m='4088770'>could</span>
  <span m='4088980'>come</span> <span m='4089200'>in</span> <span m='4089280'>here,</span>
  <span m='4089780'>and</span> <span m='4089880'>maybe</span> <span m='4090140'>it
  gets</span> <span m='4090350'>paired</span> <span m='4090550'>up</span> <span m='4090680'>with</span>
  <span m='4090800'>this</span> <span m='4091010'>guy.</span> <span m='4092180'>Maybe</span>
  <span m='4092560'>it</span> <span m='4092640'>goes</span> <span m='4092860'>off</span>
  <span m='4093020'>to</span> <span m='4093110'>infinity.</span> <span m='4093610'>It
  reaches</span> <span m='4093900'>the</span> <span m='4093980'>boundary</span> <span
  m='4094320'>of the</span> <span m='4094420'>paper.</span> <span m='4095450'>Those</span>
  <span m='4095630'>are</span> <span m='4095730'>the</span> <span m='4095750'>two</span>
  <span m='4095900'>possibilities.</span> </p><p><span m='4096600'>You</span> <span
  m='4096740'>get</span> <span m='4096960'>paths,</span> <span m='4097929'>which</span>
  <span m='4098189'>go</span> <span m='4098340'>off</span> <span m='4098520'>to</span>
  <span m='4098640'>the</span> <span m='4098819'>edge--</span> <span m='4099250'>off</span>
  <span m='4099390'>to</span> <span m='4099479'>infinity</span> <span m='4099880'>on</span>
  <span m='4100000'>either</span> <span m='4100250'>end.</span> <span m='4100870'>Or</span>
  <span m='4101050'>you</span> <span m='4101140'>could</span> <span m='4101300'>get</span>
  <span m='4101470'>cycles.</span> <span m='4102990'>The</span> <span m='4103100'>cycles</span>
  <span m='4103600'>are</span> <span m='4103670'>the</span> <span m='4103750'>problem.</span>
  <span m='4105000'>Because</span> <span m='4105189'>whenever</span> <span m='4105550'>I</span>
  <span m='4105590'>have</span> <span m='4105770'>a</span> <span m='4105840'>cycle,</span>
  <span m='4107330'>I</span> <span m='4107470'>have</span> <span m='4107640'>a</span>
  <span m='4107700'>parity</span> <span m='4108069'>constraint.</span> </p><p><span
  m='4109479'>For</span> <span m='4109649'>example,</span> <span m='4110510'>when</span>
  <span m='4110660'>they're</span> <span m='4110800'>all</span> <span m='4111040'>not</span>
  <span m='4111229'>equals,</span> <span m='4112979'>the</span> <span m='4113569'>length</span>
  <span m='4113840'>of</span> <span m='4113890'>the</span> <span m='4113950'>cycle</span>
  <span m='4114260'>must</span> <span m='4114460'>be</span> <span m='4114609'>even.</span>
  <span m='4116010'>If</span> <span m='4116170'>there</span> <span m='4116330'>were--</span>
  <span m='4119680'>what's</span> <span m='4119890'>the</span> <span m='4119950'>general</span>
  <span m='4120250'>statement?</span> <span m='4120700'>It's</span> <span m='4120800'>like</span>
  <span m='4121580'>the</span> <span m='4121830'>parity</span> <span m='4122550'>of</span>
  <span m='4122670'>the</span> <span m='4122760'>cycle,</span> <span m='4123310'>which</span>
  <span m='4123370'>is</span> <span m='4123439'>whether</span> <span m='4123609'>it's</span>
  <span m='4123710'>even</span> <span m='4123920'>or</span> <span m='4123990'>odd,</span>
  <span m='4124260'>should</span> <span m='4124660'>be</span> <span m='4124850'>equal</span>
  <span m='4125180'>to</span> <span m='4125859'>the</span> <span m='4125960'>parity</span>
  <span m='4126430'>of</span> <span m='4126630'>the</span> <span m='4126729'>number</span>
  <span m='4127130'>of</span> <span m='4127720'>not</span> <span m='4128160'>equal</span>
  <span m='4128439'>signs.</span> <span m='4132340'>Something</span> <span m='4132590'>like</span>
  <span m='4132750'>that.</span> <span m='4134939'>I've got a sheet</span> <span m='4135189'>here.</span>
  </p><p><span m='4143244'>Great,</span> <span m='4143740'>I</span> <span m='4143810'>just</span>
  <span m='4144000'>said</span> <span m='4144420'>"parity</span> <span m='4144790'>problems."</span>
  <span m='4145810'>It's</span> <span m='4145950'>something</span> <span m='4146220'>like</span>
  <span m='4146430'>that.</span> <span m='4146870'>It's</span> <span m='4147020'>either</span>
  <span m='4147330'>the</span> <span m='4147470'>parity</span> <span m='4147930'>of</span>
  <span m='4148060'>the</span> <span m='4148510'>cycle</span> <span m='4148970'>should</span>
  <span m='4149149'>equal</span> <span m='4149380'>the</span> <span m='4149460'>parity</span>
  <span m='4149770'>of</span> <span m='4149859'>the</span> <span m='4149950'>number
  of</span> <span m='4150210'>equals</span> <span m='4150990'>or</span> <span m='4151170'>the</span>
  <span m='4151279'>parity</span> <span m='4151500'>of</span> <span m='4151590'>the</span>
  <span m='4151660'>number</span> <span m='4151910'>of not</span> <span m='4152090'>equals.</span>
  <span m='4153090'>I</span> <span m='4153149'>think,</span> <span m='4153439'>number</span>
  <span m='4153890'>of</span> <span m='4154310'>equals.</span> <span m='4155350'>Anyway,</span>
  <span m='4156140'>one</span> <span m='4156290'>of</span> <span m='4156350'>the</span>
  <span m='4156439'>two.</span> </p><p><span m='4158260'>And</span> <span m='4158430'>you</span>
  <span m='4158500'>can</span> <span m='4158630'>just</span> <span m='4158830'>check.</span>
  <span m='4159319'>I</span> <span m='4159470'>mean,</span> <span m='4159630'>you're</span>
  <span m='4159729'>forced.</span> <span m='4160090'>If</span> <span m='4160229'>I</span>
  <span m='4160310'>say,</span> <span m='4160550'>OK,</span> <span m='4160840'>let's</span>
  <span m='4161029'>make</span> <span m='4161200'>this</span> <span m='4161340'>mountain,</span>
  <span m='4162250'>then</span> <span m='4162439'>this</span> <span m='4162670'>is</span>
  <span m='4162950'>either</span> <span m='4163200'>equals</span> <span m='4163529'>or</span>
  <span m='4163600'>not</span> <span m='4163760'>equals.</span> <span m='4164069'>It'll</span>
  <span m='4164220'>tell</span> <span m='4164390'>me</span> <span m='4164520'>whether</span>
  <span m='4164729'>this</span> <span m='4164920'>is</span> <span m='4165000'>mountain</span>
  <span m='4165229'>or</span> <span m='4165260'>valley.</span> </p><p><span m='4165640'>Just</span>
  <span m='4165810'>walk</span> <span m='4166060'>around</span> <span m='4166279'>the</span>
  <span m='4166340'>cycle.</span> <span m='4166770'>Either</span> <span m='4166979'>you</span>
  <span m='4167090'>get</span> <span m='4167200'>a</span> <span m='4167260'>contradiction</span>
  <span m='4167819'>or</span> <span m='4167910'>you</span> <span m='4168010'>don't.</span>
  <span m='4168899'>If you</span> <span m='4168990'>get</span> <span m='4169130'>a</span>
  <span m='4169189'>contradiction,</span> <span m='4169720'>we</span> <span m='4169790'>have</span>
  <span m='4170000'>a</span> <span m='4170069'>problem.</span> <span m='4172520'>How</span>
  <span m='4172689'>could</span> <span m='4172830'>we</span> <span m='4172939'>possibly</span>
  <span m='4173460'>fix</span> <span m='4173720'>the</span> <span m='4173790'>problem?</span>
  </p><p><span m='4175080'>Well,</span> <span m='4178740'>when</span> <span m='4179000'>we</span>
  <span m='4179140'>made--</span> <span m='4180020'>you</span> <span m='4180200'>look</span>
  <span m='4180399'>at</span> <span m='4180460'>each</span> <span m='4180640'>of</span>
  <span m='4180710'>these</span> <span m='4180920'>cramps.</span> <span m='4181750'>I
  mean,</span> <span m='4181880'>in</span> <span m='4181990'>fact,</span> <span m='4182220'>you</span>
  <span m='4182310'>could</span> <span m='4182420'>look</span> <span m='4182609'>at</span>
  <span m='4182740'>each</span> <span m='4182960'>of</span> <span m='4183210'>these</span>
  <span m='4183399'>vertices</span> <span m='4183770'>separately.</span> <span m='4184260'>But</span>
  <span m='4184910'>you</span> <span m='4185000'>think</span> <span m='4185189'>about</span>
  <span m='4185510'>one</span> <span m='4185620'>of these</span> <span m='4185760'>crimps</span>
  <span m='4185899'>and</span> <span m='4186040'>say,</span> <span m='4186189'>well,</span>
  <span m='4186410'>could</span> <span m='4186620'>I</span> <span m='4186700'>have</span>
  <span m='4186819'>done</span> <span m='4187010'>it</span> <span m='4187109'>another</span>
  <span m='4187420'>way?</span> </p><p><span m='4188069'>Sometimes,</span> <span m='4188770'>there
  are</span> <span m='4188970'>crimps</span> <span m='4189620'>that</span> <span m='4189710'>have</span>
  <span m='4189970'>other</span> <span m='4190340'>equal</span> <span m='4190600'>choices.</span>
  <span m='4191920'>Maybe,</span> <span m='4192120'>there are a</span> <span m='4192279'>bunch</span>
  <span m='4192560'>of</span> <span m='4192670'>equal</span> <span m='4192990'>angles.</span>
  <span m='4193620'>And</span> <span m='4193880'>I</span> <span m='4194000'>could</span>
  <span m='4194180'>have</span> <span m='4194300'>done</span> <span m='4194490'>a</span>
  <span m='4194550'>different</span> <span m='4194860'>pairing.</span> </p><p><span
  m='4196760'>What</span> <span m='4196950'>happens</span> <span m='4197320'>when</span>
  <span m='4197450'>I</span> <span m='4197520'>try a</span> <span m='4197770'>different</span>
  <span m='4198080'>pairing?</span> <span m='4199070'>Well,</span> <span m='4199530'>instead</span>
  <span m='4200060'>of</span> <span m='4201530'>this</span> <span m='4201980'>being</span>
  <span m='4202190'>in</span> <span m='4202270'>one</span> <span m='4202470'>cycle</span>
  <span m='4203290'>and,</span> <span m='4203540'>let's</span> <span m='4203750'>say,</span>
  <span m='4204430'>this</span> <span m='4204790'>being</span> <span m='4205290'>in</span>
  <span m='4205390'>another</span> <span m='4205730'>cycle,</span> <span m='4207230'>if</span>
  <span m='4207370'>I</span> <span m='4207440'>pair</span> <span m='4207720'>these</span>
  <span m='4208020'>guys</span> <span m='4208270'>up</span> <span m='4208440'>instead,</span>
  <span m='4209360'>I'll</span> <span m='4209510'>end</span> <span m='4209640'>up</span>
  <span m='4209750'>merging</span> <span m='4210190'>those</span> <span m='4210370'>two</span>
  <span m='4210490'>cycles</span> <span m='4210880'>into</span> <span m='4211120'>one</span>
  <span m='4211380'>bigger</span> <span m='4211680'>thing.</span> <span m='4213150'>It
  could</span> <span m='4213330'>be</span> <span m='4213450'>a</span> <span m='4213520'>path</span>
  <span m='4213830'>or</span> <span m='4213900'>a</span> <span m='4213960'>cycle.</span>
  </p><p><span m='4215620'>And</span> <span m='4215950'>the</span> <span m='4216070'>algorithm</span>
  <span m='4216460'>says,</span> <span m='4216860'>just</span> <span m='4217160'>keep</span>
  <span m='4217540'>doing</span> <span m='4217850'>those</span> <span m='4218070'>cycle</span>
  <span m='4218480'>merges.</span> <span m='4219850'>And</span> <span m='4220240'>if</span>
  <span m='4220410'>you</span> <span m='4220930'>get</span> <span m='4221150'>stuck,</span>
  <span m='4222040'>your</span> <span m='4222180'>thing</span> <span m='4222550'>is</span>
  <span m='4222680'>not</span> <span m='4222880'>locally</span> <span m='4223210'>foldable.</span>
  <span m='4223820'>That's</span> <span m='4224060'>the</span> <span m='4224150'>hard</span>
  <span m='4224360'>part to</span> <span m='4224630'>prove.</span> <span m='4225830'>Otherwise,</span>
  <span m='4226310'>you</span> <span m='4226450'>will</span> <span m='4226560'>find</span>
  <span m='4227982'>one</span> <span m='4228460'>of</span> <span m='4228550'>these</span>
  <span m='4228720'>patterns</span> <span m='4229340'>that</span> <span m='4229460'>you</span>
  <span m='4229580'>can</span> <span m='4229710'>actually</span> <span m='4230200'>resolve</span>
  <span m='4230770'>mountains</span> <span m='4231070'>and</span> <span m='4231140'>valleys</span>
  <span m='4231460'>all</span> <span m='4231570'>the</span> <span m='4231640'>way</span>
  <span m='4231760'>through.</span> </p><p><span m='4233140'>So</span> <span m='4235020'>let's</span>
  <span m='4235280'>say,</span> <span m='4239860'>so</span> <span m='4240030'>start</span>
  <span m='4240480'>with</span> <span m='4240690'>some</span> <span m='4246340'>folding--</span>
  <span m='4247940'>say</span> <span m='4248150'>local</span> <span m='4248640'>folding,</span>
  <span m='4251330'>whatever.</span> <span m='4252380'>I'm</span> <span m='4252500'>going</span>
  <span m='4252580'>to</span> <span m='4252640'>say</span> <span m='4252810'>with</span>
  <span m='4252950'>some</span> <span m='4253200'>pairing</span> <span m='4256895'>of</span>
  <span m='4257350'>creases</span> <span m='4258160'>at</span> <span m='4258490'>vertices.</span>
  <span m='4266460'>And</span> <span m='4274860'>merge</span> <span m='4279400'>two</span>
  <span m='4279710'>paths</span> <span m='4280110'>or</span> <span m='4280190'>cycles</span>
  <span m='4288730'>whenever</span> <span m='4289130'>possible.</span> </p><p><span
  m='4293000'>And when</span> <span m='4293200'>I</span> <span m='4293270'>say</span>
  <span m='4293470'>merge,</span> <span m='4294990'>I</span> <span m='4295100'>mean</span>
  <span m='4297350'>whenever</span> <span m='4297760'>you</span> <span m='4297920'>have--</span>
  <span m='4299080'>what</span> <span m='4299230'>are</span> <span m='4299260'>the</span>
  <span m='4299390'>possible</span> <span m='4300130'>things</span> <span m='4300420'>you</span>
  <span m='4300560'>could</span> <span m='4300690'>possibly</span> <span m='4301110'>merge--</span>
  <span m='4301770'>when</span> <span m='4301880'>you</span> <span m='4301950'>have</span>
  <span m='4302320'>at</span> <span m='4302530'>some</span> <span m='4302780'>point</span>
  <span m='4303030'>during</span> <span m='4303220'>the</span> <span m='4303310'>algorithm</span>
  <span m='4303720'>a</span> <span m='4303800'>bunch</span> <span m='4304100'>of</span>
  <span m='4304160'>equal</span> <span m='4304510'>angles,</span> <span m='4305230'>you</span>
  <span m='4305670'>have</span> <span m='4305790'>a</span> <span m='4305840'>choice</span>
  <span m='4306220'>which</span> <span m='4306400'>of</span> <span m='4306480'>these</span>
  <span m='4306640'>you</span> <span m='4306770'>crimp.</span> <span m='4307180'>Obviously,</span>
  <span m='4308940'>the</span> <span m='4309020'>mountain</span> <span m='4309290'>valley</span>
  <span m='4309360'>assignment</span> <span m='4309770'>is</span> <span m='4309860'>not</span>
  <span m='4310050'>fixed.</span> <span m='4310320'>You</span> <span m='4310410'>can</span>
  <span m='4310640'>crimp</span> <span m='4310740'>any</span> <span m='4310950'>of</span>
  <span m='4311030'>them.</span> </p><p><span m='4313450'>You</span> <span m='4313620'>picked</span>
  <span m='4313830'>one</span> <span m='4314040'>of</span> <span m='4314130'>them,</span>
  <span m='4315040'>and</span> <span m='4315510'>it's</span> <span m='4315750'>sort</span>
  <span m='4315920'>of</span> <span m='4315990'>merging</span> <span m='4316840'>whatever</span>
  <span m='4317130'>this</span> <span m='4317330'>thing</span> <span m='4317480'>is</span>
  <span m='4317580'>attached</span> <span m='4318000'>to, to</span> <span m='4318420'>whatever</span>
  <span m='4318690'>this</span> <span m='4318870'>thing</span> <span m='4319000'>is</span>
  <span m='4319110'>attached</span> <span m='4319540'>to.</span> <span m='4321380'>If</span>
  <span m='4321540'>there's</span> <span m='4321710'>something</span> <span m='4322100'>else</span>
  <span m='4322540'>that's</span> <span m='4323490'>disconnected</span> <span m='4324400'>from</span>
  <span m='4324620'>that</span> <span m='4324880'>thing,</span> <span m='4325660'>I</span>
  <span m='4325770'>want</span> <span m='4326080'>you</span> <span m='4326240'>to</span>
  <span m='4326380'>instead</span> <span m='4327330'>merge</span> <span m='4328140'>two</span>
  <span m='4328330'>of</span> <span m='4328480'>them</span> <span m='4328960'>that</span>
  <span m='4329090'>combines</span> <span m='4329700'>two</span> <span m='4329890'>different</span>
  <span m='4330280'>connected</span> <span m='4330630'>components--</span> <span m='4331150'>two</span>
  <span m='4331360'>paths</span> <span m='4331750'>or</span> <span m='4331830'>cycles.</span>
  <span m='4332880'>Merging</span> <span m='4333280'>means</span> <span m='4333560'>I</span>
  <span m='4333640'>decrease</span> <span m='4334210'>the</span> <span m='4334310'>total</span>
  <span m='4334630'>number</span> <span m='4334950'>of</span> <span m='4335010'>paths</span>
  <span m='4335270'>or</span> <span m='4335350'>cycles.</span> <span m='4335780'>I</span>
  <span m='4335830'>combine</span> <span m='4336250'>two</span> <span m='4336440'>into</span>
  <span m='4336640'>one.</span> </p><p><span m='4337220'>Whenever</span> <span m='4337530'>that's</span>
  <span m='4337740'>possible,</span> <span m='4338470'>do</span> <span m='4338700'>it.</span>
  <span m='4339310'>You</span> <span m='4339460'>can</span> <span m='4339590'>prove</span>
  <span m='4339990'>that</span> <span m='4340100'>if</span> <span m='4340200'>you</span>
  <span m='4340290'>have</span> <span m='4341220'>parity</span> <span m='4341580'>problem</span>
  <span m='4342230'>in</span> <span m='4342410'>the</span> <span m='4342480'>merge</span>
  <span m='4342870'>thing,</span> <span m='4343670'>you</span> <span m='4343760'>had</span>
  <span m='4343990'>to</span> <span m='4344030'>have</span> <span m='4344120'>had</span>
  <span m='4344290'>a</span> <span m='4344350'>parity</span> <span m='4344620'>problem</span>
  <span m='4344920'>originally.</span> <span m='4345450'>And</span> <span m='4345590'>merging</span>
  <span m='4345930'>can</span> <span m='4346150'>only</span> <span m='4346500'>fix</span>
  <span m='4347560'>parity</span> <span m='4347900'>problems.</span> <span m='4349260'>That's</span>
  <span m='4349470'>the</span> <span m='4349540'>claim,</span> <span m='4349990'>and</span>
  <span m='4350070'>that's</span> <span m='4350240'>what</span> <span m='4350350'>I</span>
  <span m='4350400'>will</span> <span m='4350520'>not</span> <span m='4350740'>prove.</span>
  </p><p><span m='4351940'>Once</span> <span m='4352170'>you</span> <span m='4352260'>know</span>
  <span m='4352410'>that--</span> <span m='4352620'>and it</span> <span m='4352810'>doesn't</span>
  <span m='4353080'>matter in</span> <span m='4353480'>what</span> <span m='4353700'>order</span>
  <span m='4354470'>or</span> <span m='4354610'>how</span> <span m='4354790'>you</span>
  <span m='4354940'>choose</span> <span m='4355180'>to</span> <span m='4355280'>merge--</span>
  <span m='4355590'>you</span> <span m='4355660'>just</span> <span m='4355840'>merge</span>
  <span m='4356080'>as</span> <span m='4356130'>much</span> <span m='4356440'>as</span>
  <span m='4356540'>possible.</span> <span m='4357860'>And</span> <span m='4358280'>either</span>
  <span m='4358730'>the</span> <span m='4359160'>resulting</span> <span m='4359540'>thing</span>
  <span m='4359920'>is</span> <span m='4360890'>OK</span> <span m='4361550'>or</span>
  <span m='4361660'>not.</span> <span m='4362600'>And</span> <span m='4362750'>accordingly,</span>
  <span m='4363240'>you</span> <span m='4363360'>will</span> <span m='4363500'>tell</span>
  <span m='4363740'>whether</span> <span m='4363930'>this</span> <span m='4364140'>thing</span>
  <span m='4364270'>is</span> <span m='4364380'>locally</span> <span m='4364690'>foldable.</span>
  </p><p><span m='4366650'>Sorry,</span> <span m='4366780'>I</span> <span m='4366940'>want</span>
  <span m='4367120'>to</span> <span m='4367170'>move</span> <span m='4367350'>on</span>
  <span m='4367480'>to</span> <span m='4367550'>other</span> <span m='4367730'>things.</span>
  <span m='4368700'>But</span> <span m='4369450'>I</span> <span m='4369560'>think</span>
  <span m='4369700'>this</span> <span m='4369790'>would</span> <span m='4369890'>be</span>
  <span m='4370000'>a</span> <span m='4370060'>fun</span> <span m='4370340'>thing</span>
  <span m='4370570'>to</span> <span m='4370670'>actually</span> <span m='4370950'>implement.</span>
  <span m='4371340'>It's</span> <span m='4371570'>an</span> <span m='4371770'>easy</span>
  <span m='4371880'>algorithm.</span> <span m='4373310'>And</span> <span m='4375240'>it's,</span>
  <span m='4377870'>I</span> <span m='4377970'>think,</span> <span m='4378250'>a</span>
  <span m='4378350'>pretty</span> <span m='4378540'>good</span> <span m='4378750'>test</span>
  <span m='4379110'>it</span> <span m='4379400'>for</span> <span m='4380100'>problems</span>
  <span m='4380640'>like</span> <span m='4380820'>this</span> <span m='4381000'>that</span>
  <span m='4381090'>prevent</span> <span m='4381450'>flat</span> <span m='4381850'>foldability.</span>
  </p><p><span m='4393510'>So</span> <span m='4394180'>let's</span> <span m='4394410'>move</span>
  <span m='4394610'>on</span> <span m='4395030'>from</span> <span m='4395320'>foldability</span>
  <span m='4396560'>to</span> <span m='4396790'>origami</span> <span m='4397120'>design.</span>
  <span m='4401690'>So</span> <span m='4402340'>a bit</span> <span m='4402540'>of
  a</span> <span m='4403130'>big</span> <span m='4403260'>transition.</span> <span
  m='4403595'>And</span> <span m='4403930'>we're</span> <span m='4404100'>going</span>
  <span m='4404220'>to</span> <span m='4404800'>talk</span> <span m='4405160'>about</span>
  <span m='4406290'>origami</span> <span m='4406600'>design</span> <span m='4406880'>a</span>
  <span m='4406940'>lot</span> <span m='4407120'>more</span> <span m='4407550'>next</span>
  <span m='4408420'>class</span> <span m='4408750'>also</span> <span m='4411130'>but</span>
  <span m='4412820'>just</span> <span m='4413530'>start</span> <span m='4413870'>it</span>
  <span m='4413950'>off</span> <span m='4414150'>today.</span> </p><p><span m='4414920'>And</span>
  <span m='4415210'>the</span> <span m='4415450'>particular</span> <span m='4417210'>algorithm</span>
  <span m='4417600'>for</span> <span m='4417890'>origami</span> <span m='4418070'>design</span>
  <span m='4418460'>I</span> <span m='4418500'>want</span> <span m='4418640'>to</span>
  <span m='4418690'>talk</span> <span m='4418900'>about</span> <span m='4419260'>is</span>
  <span m='4419620'>called the tree</span> <span m='4420090'>method.</span> <span
  m='4421850'>This is</span> <span m='4422050'>probably</span> <span m='4422340'>the</span>
  <span m='4422530'>oldest</span> <span m='4424150'>algorithm</span> <span m='4424600'>for</span>
  <span m='4424790'>origami</span> <span m='4425230'>design,</span> <span m='4426370'>in</span>
  <span m='4426520'>that</span> <span m='4427630'>people</span> <span m='4427940'>have</span>
  <span m='4428040'>been</span> <span m='4428100'>thinking</span> <span m='4428450'>about</span>
  <span m='4428690'>it and</span> <span m='4428830'>developing</span> <span m='4429360'>it</span>
  <span m='4429710'>for</span> <span m='4429870'>many</span> <span m='4430140'>years</span>
  <span m='4431700'>through</span> <span m='4432190'>this</span> <span m='4432380'>period</span>
  <span m='4432700'>called</span> <span m='4432940'>the</span> <span m='4433010'>Bug</span>
  <span m='4433310'>Wars,</span> <span m='4433720'>when</span> <span m='4433840'>people</span>
  <span m='4434090'>were</span> <span m='4434140'>trying</span> <span m='4434380'>to</span>
  <span m='4434440'>design</span> <span m='4435090'>more</span> <span m='4435450'>and</span>
  <span m='4435510'>more</span> <span m='4435670'>complicated</span> <span m='4436220'>insects.</span>
  </p><p><span m='4436880'>It's</span> <span m='4437170'>like,</span> <span m='4437330'>well,</span>
  <span m='4437670'>I</span> <span m='4437790'>can</span> <span m='4437940'>make</span>
  <span m='4438100'>an</span> <span m='4438160'>insect</span> <span m='4439210'>with</span>
  <span m='4439420'>six</span> <span m='4439740'>legs.</span> <span m='4440140'>Oh
  yeah,</span> <span m='4440380'>well I</span> <span m='4440800'>can</span> <span
  m='4440960'>make</span> <span m='4442500'>a spider</span> <span m='4442910'>with</span>
  <span m='4443060'>eight</span> <span m='4443260'>legs.</span> <span m='4443610'>Oh</span>
  <span m='4443730'>yeah,</span> <span m='4444170'>well I</span> <span m='4444290'>can</span>
  <span m='4444500'>make</span> <span m='4445130'>an</span> <span m='4445320'>insect--</span>
  <span m='4446600'>a</span> <span m='4446810'>beetle</span> <span m='4447380'>that</span>
  <span m='4447660'>has</span> <span m='4447860'>wings</span> <span m='4448360'>and</span>
  <span m='4448430'>horns</span> <span m='4449020'>and</span> <span m='4449120'>there's</span>
  <span m='4449340'>thorns</span> <span m='4449770'>on</span> <span m='4449870'>the</span>
  <span m='4449950'>horns--</span> <span m='4450410'>you know,</span> <span m='4450600'>all</span>
  <span m='4450770'>these</span> <span m='4450950'>crazy</span> <span m='4451230'>things.</span>
  </p><p><span m='4452780'>During</span> <span m='4453080'>that</span> <span m='4453320'>time,</span>
  <span m='4453840'>there were a</span> <span m='4454030'>lot</span> <span m='4454280'>of</span>
  <span m='4454340'>people</span> <span m='4454600'>thinking</span> <span m='4454840'>about</span>
  <span m='4455020'>how</span> <span m='4455180'>do</span> <span m='4455280'>I</span>
  <span m='4455360'>make</span> <span m='4455640'>more</span> <span m='4455850'>and</span>
  <span m='4455910'>more</span> <span m='4456080'>complicated--</span> <span m='4456850'>especially,</span>
  <span m='4459690'>more</span> <span m='4459950'>limbs</span> <span m='4460580'>in</span>
  <span m='4460690'>my</span> <span m='4460810'>creatures</span> <span m='4462300'>and</span>
  <span m='4462530'>very</span> <span m='4462840'>precise</span> <span m='4463990'>arrangements</span>
  <span m='4464490'>of</span> <span m='4464580'>those</span> <span m='4464760'>limbs,</span>
  <span m='4465280'>let's</span> <span m='4465450'>say.</span> <span m='4465950'>And</span>
  <span m='4466100'>that</span> <span m='4466290'>is</span> <span m='4466390'>what</span>
  <span m='4466500'>the</span> <span m='4466590'>tree</span> <span m='4466810'>method</span>
  <span m='4467460'>deals</span> <span m='4467710'>with</span> <span m='4468270'>and
  was</span> <span m='4468470'>really</span> <span m='4468690'>formalized</span> <span
  m='4469430'>by</span> <span m='4469740'>Robert</span> <span m='4470050'>Lang,</span>
  <span m='4470930'>who</span> <span m='4471990'>published</span> <span m='4472490'>a</span>
  <span m='4472870'>paper</span> <span m='4473240'>in</span> <span m='4474230'>'96,</span>
  <span m='4475420'>describing</span> <span m='4476150'>it</span> <span m='4476250'>as</span>
  <span m='4476390'>a</span> <span m='4477030'>sort</span> <span m='4477470'>of</span>
  <span m='4477580'>complete</span> <span m='4477890'>algorithm.</span> </p><p><span
  m='4479810'>And</span> <span m='4481380'>it's</span> <span m='4481620'>still</span>
  <span m='4481980'>not</span> <span m='4482250'>known</span> <span m='4482480'>for</span>
  <span m='4482620'>sure</span> <span m='4482940'>that that</span> <span m='4483210'>algorithm</span>
  <span m='4483550'>always</span> <span m='4483810'>works.</span> <span m='4484480'>But</span>
  <span m='4485040'>that's</span> <span m='4485280'>what</span> <span m='4485370'>we've</span>
  <span m='4486520'>been</span> <span m='4486660'>working</span> <span m='4486930'>on--</span>
  <span m='4487030'>me</span> <span m='4487340'>and</span> <span m='4488090'>Marty</span>
  <span m='4488490'>and</span> <span m='4488940'>Rob</span> <span m='4489300'>Lang--</span>
  <span m='4490430'>for</span> <span m='4490610'>the</span> <span m='4490710'>last</span>
  <span m='4491340'>four</span> <span m='4491620'>years</span> <span m='4491880'>or</span>
  <span m='4491980'>so.</span> <span m='4492260'>And</span> <span m='4492490'>soon,</span>
  <span m='4492840'>we</span> <span m='4492960'>will</span> <span m='4493420'>publish</span>
  <span m='4493790'>that</span> <span m='4494010'>thing</span> <span m='4494600'>and</span>
  <span m='4494860'>prove</span> <span m='4495150'>that</span> <span m='4495270'>this</span>
  <span m='4495430'>thing</span> <span m='4495740'>always</span> <span m='4495970'>works.</span>
  </p><p><span m='4496870'>But</span> <span m='4497040'>I'm</span> <span m='4497170'>going</span>
  <span m='4497270'>to</span> <span m='4497310'>describe</span> <span m='4497660'>the</span>
  <span m='4497820'>algorithm</span> <span m='4498250'>without</span> <span m='4498590'>the</span>
  <span m='4498680'>proof</span> <span m='4499020'>that it</span> <span m='4499150'>works.</span>
  <span m='4500170'>And</span> <span m='4500240'>what</span> <span m='4500380'>it</span>
  <span m='4500480'>does--</span> <span m='4501746'>I'll</span> <span m='4502100'>tell</span>
  <span m='4502280'>you</span> <span m='4502440'>its</span> <span m='4502610'>goal</span>
  <span m='4505920'>from</span> <span m='4506080'>a</span> <span m='4506170'>mathematical</span>
  <span m='4506810'>perspective.</span> <span m='4518260'>So</span> <span m='4518570'>it's</span>
  <span m='4519100'>interested</span> <span m='4519470'>in</span> <span m='4519590'>practical</span>
  <span m='4520040'>origami</span> <span m='4520440'>design.</span> <span m='4520800'>So</span>
  <span m='4520910'>we're</span> <span m='4521000'>going</span> <span m='4521090'>to</span>
  <span m='4521150'>start</span> <span m='4521410'>from</span> <span m='4521530'>a</span>
  <span m='4521580'>square</span> <span m='4521830'>piece</span> <span m='4522020'>of</span>
  <span m='4522080'>paper.</span> </p><p><span m='4522780'>It</span> <span m='4522900'>would</span>
  <span m='4523040'>also</span> <span m='4523390'>work</span> <span m='4523650'>for</span>
  <span m='4523790'>triangular</span> <span m='4524290'>pieces</span> <span m='4524620'>of</span>
  <span m='4524720'>paper</span> <span m='4525200'>or</span> <span m='4525300'>anything</span>
  <span m='4525750'>convex.</span> <span m='4527700'>But</span> <span m='4527960'>squares</span>
  <span m='4528390'>are</span> <span m='4528470'>what</span> <span m='4528650'>people</span>
  <span m='4529550'>usually</span> <span m='4529900'>care about.</span> <span m='4531130'>Sometimes
  it's</span> <span m='4531590'>used</span> <span m='4531760'>for</span> <span m='4531850'>rectangles</span>
  <span m='4532370'>also.</span> </p><p><span m='4566510'>The</span> <span m='4566630'>idea</span>
  <span m='4566920'>is</span> <span m='4568020'>I</span> <span m='4568150'>give</span>
  <span m='4568500'>to you</span> <span m='4569530'>a</span> <span m='4569600'>stick</span>
  <span m='4569860'>figure.</span> <span m='4573110'>So</span> <span m='4573360'>that's</span>
  <span m='4573720'>formally,</span> <span m='4574070'>it's</span> <span m='4574210'>a</span>
  <span m='4574260'>tree--</span> <span m='4574750'>a</span> <span m='4574920'>graph</span>
  <span m='4575210'>without</span> <span m='4575470'>any</span> <span m='4575590'>cycles.</span>
  <span m='4577090'>It's</span> <span m='4577300'>a</span> <span m='4577370'>metric</span>
  <span m='4577920'>tree,</span> <span m='4578820'>meaning</span> <span m='4579140'>that</span>
  <span m='4579300'>I</span> <span m='4579390'>put</span> <span m='4579950'>lengths</span>
  <span m='4580420'>on</span> <span m='4580530'>the</span> <span m='4580650'>edges.</span>
  <span m='4581410'>I</span> <span m='4581540'>know</span> <span m='4581810'>this</span>
  <span m='4582270'>length--</span> <span m='4582700'>this</span> <span m='4582900'>edge</span>
  <span m='4583120'>length--</span> <span m='4583350'>is</span> <span m='4583440'>maybe</span>
  <span m='4583680'>twice</span> <span m='4583960'>as</span> <span m='4584030'>long</span>
  <span m='4584230'>as</span> <span m='4584320'>this</span> <span m='4584490'>one.</span>
  <span m='4584920'>So</span> <span m='4585010'>I</span> <span m='4585050'>really</span>
  <span m='4585290'>draw</span> <span m='4585590'>it</span> <span m='4586270'>with</span>
  <span m='4586490'>edge</span> <span m='4586690'>lengths</span> <span m='4586960'>in</span>
  <span m='4587040'>mind.</span> </p><p><span m='4588380'>Then</span> <span m='4588640'>what</span>
  <span m='4588820'>I</span> <span m='4588870'>want</span> <span m='4589140'>you</span>
  <span m='4589260'>to</span> <span m='4589360'>do</span> <span m='4590140'>is</span>
  <span m='4590310'>find</span> <span m='4592600'>some</span> <span m='4593380'>folding</span>
  <span m='4593660'>of</span> <span m='4593940'>a</span> <span m='4594110'>piece</span>
  <span m='4594350'>of</span> <span m='4594420'>paper--</span> <span m='4598820'>I</span>
  <span m='4598900'>should</span> <span m='4599100'>really</span> <span m='4599280'>be</span>
  <span m='4599410'>looking</span> <span m='4599750'>at</span> <span m='4599840'>what</span>
  <span m='4599960'>I'm</span> <span m='4600040'>trying</span> <span m='4600240'>to</span>
  <span m='4600290'>match.</span> <span m='4601950'>So</span> <span m='4602460'>here,</span>
  <span m='4604080'>here,</span> <span m='4610824'>this</span> <span m='4611260'>goes</span>
  <span m='4611710'>down,</span> <span m='4625670'>such</span> <span m='4626140'>that</span>
  <span m='4626410'>I</span> <span m='4626450'>want</span> <span m='4626590'>to</span>
  <span m='4626640'>find</span> <span m='4627250'>some</span> <span m='4627540'>folding</span>
  <span m='4627860'>of</span> <span m='4627990'>a</span> <span m='4628050'>square</span>
  <span m='4628490'>paper--</span> <span m='4628900'>in</span> <span m='4629010'>fact,</span>
  <span m='4629290'>the</span> <span m='4629390'>smallest</span> <span m='4629870'>square</span>
  <span m='4630100'>possible,</span> <span m='4631830'>so</span> <span m='4632130'>that</span>
  <span m='4632690'>when</span> <span m='4632920'>I</span> <span m='4633470'>project--</span>
  <span m='4635130'>like</span> <span m='4635490'>this--</span> <span m='4636810'>vertically,</span>
  <span m='4639100'>the</span> <span m='4639210'>projection</span> <span m='4639970'>of</span>
  <span m='4640190'>that</span> <span m='4642250'>folding</span> <span m='4643490'>is</span>
  <span m='4643720'>exactly</span> <span m='4644140'>that</span> <span m='4644450'>metric</span>
  <span m='4644790'>tree.</span> <span m='4646270'>And</span> <span m='4646730'>this</span>
  <span m='4646920'>is</span> <span m='4647050'>called</span> <span m='4647480'>a</span>
  <span m='4647580'>uniaxial--</span> <span m='4648430'>this</span> <span m='4648640'>thing</span>
  <span m='4648830'>is</span> <span m='4648940'>called</span> <span m='4649160'>a</span>
  <span m='4649200'>uniaxial</span> <span m='4649870'>base.</span> </p><p><span m='4650880'>Let
  me</span> <span m='4650970'>tell</span> <span m='4651120'>you</span> <span m='4651250'>a</span>
  <span m='4651280'>little</span> <span m='4651470'>bit</span> <span m='4651610'>why</span>
  <span m='4651830'>it's</span> <span m='4651970'>called</span> <span m='4652790'>a</span>
  <span m='4653000'>uniaxial</span> <span m='4653300'>base.</span> <span m='4657280'>We're</span>
  <span m='4657390'>thinking</span> <span m='4657780'>about</span> <span m='4658290'>what</span>
  <span m='4658440'>are</span> <span m='4658520'>called</span> <span m='4658730'>origami</span>
  <span m='4659430'>bases.</span> <span m='4660220'>These</span> <span m='4660440'>there</span>
  <span m='4660850'>like</span> <span m='4661070'>the</span> <span m='4661160'>beginning</span>
  <span m='4661960'>of</span> <span m='4662250'>origami</span> <span m='4662720'>models.</span>
  <span m='4663570'>And</span> <span m='4664020'>most</span> <span m='4664980'>classic</span>
  <span m='4665480'>origami</span> <span m='4665880'>models--</span> <span m='4666290'>like</span>
  <span m='4666670'>more</span> <span m='4667040'>than</span> <span m='4668180'>60</span>
  <span m='4668610'>years</span> <span m='4668950'>ago--</span> <span m='4669960'>start</span>
  <span m='4670330'>from</span> <span m='4670500'>one</span> <span m='4670680'>of</span>
  <span m='4670750'>these</span> <span m='4670930'>bases.</span> </p><p><span m='4671980'>You've
  got</span> <span m='4673810'>waterbomb</span> <span m='4674080'>base</span> <span
  m='4674540'>on</span> <span m='4674690'>the</span> <span m='4674820'>top</span>
  <span m='4675120'>left,</span> <span m='4676420'>preliminary</span> <span m='4677050'>base,</span>
  <span m='4678780'>fish</span> <span m='4679070'>base,</span> <span m='4680380'>bird</span>
  <span m='4680620'>base</span> <span m='4681850'>windmill</span> <span m='4682330'>base,</span>
  <span m='4683510'>and</span> <span m='4684350'>frog</span> <span m='4684580'>base.</span>
  <span m='4685830'>I can't</span> <span m='4686190'>remember</span> <span m='4686320'>them</span>
  <span m='4686470'>all.</span> <span m='4686640'>I</span> <span m='4686720'>have</span>
  <span m='4687210'>a</span> <span m='4687500'>little</span> <span m='4687690'>example</span>
  <span m='4688070'>here.</span> </p><p><span m='4688250'>This</span> <span m='4688500'>is</span>
  <span m='4688690'>the</span> <span m='4689170'>waterbomb</span> <span m='4689630'>base.</span>
  <span m='4690750'>So</span> <span m='4691090'>it's</span> <span m='4691400'>just</span>
  <span m='4691770'>very</span> <span m='4691950'>simple</span> <span m='4693810'>crease</span>
  <span m='4694040'>pattern.</span> <span m='4694810'>And</span> <span m='4696210'>why</span>
  <span m='4696470'>this</span> <span m='4696670'>is</span> <span m='4696770'>useful</span>
  <span m='4697240'>is,</span> <span m='4697340'>it</span> <span m='4697430'>gives</span>
  <span m='4697590'>you</span> <span m='4697700'>sort</span> <span m='4697890'>of</span>
  <span m='4697990'>four</span> <span m='4698450'>flaps</span> <span m='4698950'>of</span>
  <span m='4699040'>paper</span> <span m='4699740'>to</span> <span m='4699850'>work</span>
  <span m='4700070'>with.</span> <span m='4700370'>Maybe</span> <span m='4700780'>you</span>
  <span m='4700870'>make</span> <span m='4701090'>one</span> <span m='4701270'>of</span>
  <span m='4701370'>them</span> <span m='4702630'>the</span> <span m='4702820'>head</span>
  <span m='4703640'>and</span> <span m='4704020'>the</span> <span m='4704120'>other</span>
  <span m='4704270'>two</span> <span m='4704730'>wings</span> <span m='4705220'>and</span>
  <span m='4705500'>the</span> <span m='4705800'>back</span> <span m='4706040'>one</span>
  <span m='4706180'>a</span> <span m='4706260'>tail,</span> <span m='4706590'>if</span>
  <span m='4706920'>you're</span> <span m='4707030'>making</span> <span m='4707300'>a</span>
  <span m='4707380'>crane.</span> <span m='4707930'>If doesn't</span> <span m='4708150'>actually</span>
  <span m='4708410'>start</span> <span m='4709060'>not</span> <span m='4709250'>from</span>
  <span m='4709350'>this</span> <span m='4709490'>space</span> <span m='4709880'>but</span>
  <span m='4710050'>from</span> <span m='4711210'>the</span> <span m='4711330'>other</span>
  <span m='4711540'>one.</span> </p><p><span m='4712610'>But the</span> <span m='4712680'>same</span>
  <span m='4712780'>idea.</span> <span m='4713990'>If you're</span> <span m='4714120'>folding</span>
  <span m='4714410'>a</span> <span m='4714480'>crane,</span> <span m='4715200'>one</span>
  <span m='4715370'>of</span> <span m='4715730'>these</span> <span m='4715990'>would
  be</span> <span m='4716380'>the head,</span> <span m='4717600'>the</span> <span
  m='4717640'>other</span> <span m='4717760'>tail,</span> <span m='4718130'>and</span>
  <span m='4718270'>two</span> <span m='4718440'>wings.</span> <span m='4718860'>This</span>
  <span m='4718910'>is</span> <span m='4718990'>great</span> <span m='4719240'>if
  you're</span> <span m='4719350'>making</span> <span m='4719660'>a</span> <span m='4719710'>four</span>
  <span m='4720080'>flap</span> <span m='4720650'>animal.</span> </p><p><span m='4721870'>And</span>
  <span m='4722120'>if</span> <span m='4722220'>you</span> <span m='4722310'>think</span>
  <span m='4722520'>about</span> <span m='4723390'>its</span> <span m='4723670'>projection--</span>
  <span m='4724020'>and</span> <span m='4724370'>it's</span> <span m='4724860'>easier</span>
  <span m='4725090'>to</span> <span m='4725140'>think</span> <span m='4725340'>about</span>
  <span m='4725620'>in this</span> <span m='4726040'>other</span> <span m='4726794'>picture--</span>
  <span m='4729520'>the</span> <span m='4729620'>projection</span> <span m='4730090'>of</span>
  <span m='4730170'>this</span> <span m='4730360'>thing</span> <span m='4730650'>is</span>
  <span m='4730950'>a</span> <span m='4731220'>four</span> <span m='4731760'>limbed</span>
  <span m='4732670'>star.</span> <span m='4734710'>You</span> <span m='4734860'>can</span>
  <span m='4735000'>see</span> <span m='4735090'>it's</span> <span m='4735230'>a</span>
  <span m='4735290'>plus</span> <span m='4735540'>sign.</span> <span m='4736490'>All</span>
  <span m='4736690'>of</span> <span m='4736770'>them</span> <span m='4736930'>are</span>
  <span m='4736990'>the</span> <span m='4737100'>same</span> <span m='4737350'>length.</span>
  </p><p><span m='4738400'>And</span> <span m='4738660'>so</span> <span m='4738750'>this</span>
  <span m='4738980'>is</span> <span m='4739100'>actually</span> <span m='4739350'>something</span>
  <span m='4739670'>you</span> <span m='4739810'>can</span> <span m='4739950'>get</span>
  <span m='4740240'>out</span> <span m='4740440'>of</span> <span m='4740550'>the</span>
  <span m='4740630'>tree</span> <span m='4740800'>method.</span> <span m='4741610'>You</span>
  <span m='4741690'>just</span> <span m='4741970'>give</span> <span m='4743150'>that</span>
  <span m='4743540'>as</span> <span m='4743670'>your</span> <span m='4743820'>input.</span>
  <span m='4744420'>You</span> <span m='4744560'>will</span> <span m='4744720'>get</span>
  <span m='4744980'>this</span> <span m='4745400'>3D</span> <span m='4745790'>thing</span>
  <span m='4746400'>and</span> <span m='4746600'>this</span> <span m='4746780'>crease</span>
  <span m='4747010'>pattern</span> <span m='4747870'>as</span> <span m='4748170'>your</span>
  <span m='4752520'>origami--</span> <span m='4753380'>as</span> <span m='4753560'>the</span>
  <span m='4753680'>output.</span> </p><p><span m='4754060'>Let</span> <span m='4754160'>me</span>
  <span m='4754260'>show</span> <span m='4754320'>you</span> <span m='4754900'>the</span>
  <span m='4755000'>program</span> <span m='4755400'>in</span> <span m='4755480'>action.</span>
  <span m='4757150'>So</span> <span m='4757310'>Robert</span> <span m='4757710'>Lang</span>
  <span m='4758020'>implemented</span> <span m='4758460'>this</span> <span m='4758640'>thing.</span>
  <span m='4758850'>It's</span> <span m='4758960'>called</span> <span m='4759170'>tree</span>
  <span m='4759380'>maker.</span> <span m='4760110'>It's</span> <span m='4760230'>freely</span>
  <span m='4760510'>available,</span> <span m='4761010'>open</span> <span m='4761260'>source,</span>
  <span m='4762260'>all</span> <span m='4762450'>that</span> <span m='4762610'>good</span>
  <span m='4762760'>stuff.</span> </p><p><span m='4768540'>And I'm</span> <span m='4768750'>not</span>
  <span m='4768930'>an</span> <span m='4768990'>expert at</span> <span m='4769340'>using</span>
  <span m='4769640'>it,</span> <span m='4769830'>so</span> <span m='4770510'>bear</span>
  <span m='4770720'>with</span> <span m='4770890'>me.</span> <span m='4771970'>But</span>
  <span m='4772180'>if</span> <span m='4772380'>we</span> <span m='4772490'>wanted</span>
  <span m='4772780'>to</span> <span m='4772890'>say,</span> <span m='4773750'>I</span>
  <span m='4773950'>would</span> <span m='4774130'>like</span> <span m='4774480'>that</span>
  <span m='4778620'>star.</span> <span m='4779970'>OK,</span> <span m='4780130'>now,</span>
  <span m='4780690'>I</span> <span m='4780820'>drew</span> <span m='4781150'>it</span>
  <span m='4781620'>obviously</span> <span m='4781950'>not</span> <span m='4782170'>with</span>
  <span m='4782290'>all</span> <span m='4782440'>the</span> <span m='4782500'>lengths</span>
  <span m='4782780'>equal,</span> <span m='4783300'>but</span> <span m='4783430'>it's</span>
  <span m='4783690'>ignoring</span> <span m='4784100'>the</span> <span m='4784190'>lengths</span>
  <span m='4784430'>that</span> <span m='4784530'>I</span> <span m='4784610'>drew.</span>
  <span m='4785380'>And they're</span> <span m='4785480'>actually</span> <span m='4785750'>specified</span>
  <span m='4786200'>here.</span> <span m='4786590'>So</span> <span m='4786650'>all</span>
  <span m='4786810'>the</span> <span m='4786880'>lengths</span> <span m='4787190'>here
  are</span> <span m='4787330'>supposed</span> <span m='4787600'>to</span> <span m='4787660'>be</span>
  <span m='4787780'>1.</span> </p><p><span m='4788560'>And</span> <span m='4788770'>then</span>
  <span m='4788870'>I</span> <span m='4788940'>say,</span> <span m='4789240'>OK,</span>
  <span m='4790020'>optimize.</span> <span m='4791500'>And</span> <span m='4791800'>then</span>
  <span m='4792360'>make</span> <span m='4792590'>a crease</span> <span m='4792910'>pattern.</span>
  <span m='4793660'>And</span> <span m='4793900'>then</span> <span m='4794260'>show</span>
  <span m='4794480'>me</span> <span m='4794590'>the</span> <span m='4794690'>crease</span>
  <span m='4794910'>pattern.</span> <span m='4795635'>And</span> <span m='4795940'>there</span>
  <span m='4796170'>it</span> <span m='4796220'>is,</span> <span m='4796710'>exactly</span>
  <span m='4797460'>the</span> <span m='4797560'>crease</span> <span m='4797760'>pattern</span>
  <span m='4798060'>I made,</span> <span m='4798350'>although</span> <span m='4798640'>actually</span>
  <span m='4799850'>I can</span> <span m='4799960'>see</span> <span m='4800130'>from</span>
  <span m='4800290'>the</span> <span m='4800360'>mountain valley</span> <span m='4800810'>assignment--</span>
  <span m='4801310'>because</span> <span m='4801660'>this</span> <span m='4801840'>is</span>
  <span m='4801950'>not</span> <span m='4802130'>really--</span> <span m='4802410'>this</span>
  <span m='4802590'>is</span> <span m='4802680'>not</span> <span m='4802890'>flat</span>
  <span m='4803120'>origami.</span> </p><p><span m='4804450'>It</span> <span m='4805270'>made</span>
  <span m='4805460'>it</span> <span m='4805580'>this</span> <span m='4805760'>way.</span>
  <span m='4806240'>So</span> <span m='4806390'>it's</span> <span m='4806530'>flat.</span>
  <span m='4806840'>Of</span> <span m='4806930'>course,</span> <span m='4807190'>the</span>
  <span m='4807350'>projection</span> <span m='4807645'>is</span> <span m='4807940'>the</span>
  <span m='4808000'>same--</span> <span m='4808300'>still</span> <span m='4808520'>four</span>
  <span m='4809150'>limbs.</span> <span m='4812560'>And</span> <span m='4812980'>so</span>
  <span m='4813330'>it's</span> <span m='4813420'>dashes</span> <span m='4813950'>for</span>
  <span m='4814670'>valleys</span> <span m='4815080'>and</span> <span m='4815220'>solid</span>
  <span m='4815550'>lines</span> <span m='4815780'>for</span> <span m='4815870'>mountains.</span>
  </p><p><span m='4817330'>But</span> <span m='4817530'>you</span> <span m='4817690'>can</span>
  <span m='4817830'>make</span> <span m='4818020'>anything</span> <span m='4818320'>you</span>
  <span m='4818440'>want.</span> <span m='4819540'>So</span> <span m='4820190'>let's</span>
  <span m='4820430'>say</span> <span m='4821400'>we</span> <span m='4821660'>want</span>
  <span m='4821920'>to</span> <span m='4821960'>make--</span> <span m='4824350'>I
  don't</span> <span m='4824560'>know--</span> <span m='4824750'>a lizard</span> <span
  m='4825130'>or</span> <span m='4825220'>something.</span> <span m='4826350'>So</span>
  <span m='4827880'>the</span> <span m='4827960'>blue</span> <span m='4828280'>lines</span>
  <span m='4828650'>are</span> <span m='4828740'>the</span> <span m='4828950'>tree.</span>
  <span m='4837820'>So here's--</span> <span m='4838460'>can I do</span> <span m='4838880'>this?</span>
  <span m='4839170'>Yes,</span> <span m='4839440'>there we go.</span> </p><p><span
  m='4840970'>So</span> <span m='4841150'>here,</span> <span m='4841550'>I</span>
  <span m='4841640'>have</span> <span m='4842300'>a</span> <span m='4842660'>forearm,</span>
  <span m='4843115'>a</span> <span m='4843570'>head,</span> <span m='4844250'>a</span>
  <span m='4844640'>foreleg,</span> <span m='4846380'>another</span> <span m='4846750'>forearm,</span>
  <span m='4847390'>a</span> <span m='4847470'>body</span> <span m='4847870'>segment,</span>
  <span m='4849180'>tail,</span> <span m='4850220'>and</span> <span m='4850580'>two</span>
  <span m='4850750'>hind</span> <span m='4851010'>legs.</span> <span m='4851490'>Maybe</span>
  <span m='4851830'>I</span> <span m='4851860'>want</span> <span m='4852030'>to</span>
  <span m='4852070'>make</span> <span m='4852250'>that.</span> <span m='4853820'>So</span>
  <span m='4854390'>I</span> <span m='4854710'>say</span> <span m='4855090'>optimize</span>
  <span m='4856020'>and</span> <span m='4856250'>then</span> <span m='4856580'>make</span>
  <span m='4856780'>a crease</span> <span m='4857090'>pattern,</span> <span m='4858100'>and</span>
  <span m='4858350'>then</span> <span m='4858630'>boom.</span> <span m='4859340'>You</span>
  <span m='4859440'>fold</span> <span m='4859680'>that,</span> <span m='4860010'>and
  it will</span> <span m='4860100'>have</span> <span m='4860230'>exactly</span> <span
  m='4860570'>that</span> <span m='4860720'>projection.</span> </p><p><span m='4862000'>And</span>
  <span m='4862300'>assuming</span> <span m='4862850'>it</span> <span m='4863010'>did</span>
  <span m='4863170'>a</span> <span m='4863210'>reasonable</span> <span m='4863840'>job</span>
  <span m='4864080'>at</span> <span m='4864150'>computation,</span> <span m='4864750'>this
  will</span> <span m='4864990'>be</span> <span m='4865870'>the</span> <span m='4866000'>best</span>
  <span m='4866320'>way</span> <span m='4866450'>to</span> <span m='4866540'>fold</span>
  <span m='4866740'>this</span> <span m='4866900'>thing.</span> <span m='4867120'>And</span>
  <span m='4867190'>it's</span> <span m='4867450'>the</span> <span m='4867500'>smallest</span>
  <span m='4867880'>square</span> <span m='4868210'>that</span> <span m='4868410'>matches</span>
  <span m='4868810'>exactly</span> <span m='4869910'>that</span> <span m='4870190'>shape.</span>
  <span m='4870670'>You</span> <span m='4870810'>get</span> <span m='4870950'>the</span>
  <span m='4871020'>best</span> <span m='4872010'>scale</span> <span m='4872420'>factor</span>
  <span m='4874520'>between</span> <span m='4874940'>the</span> <span m='4875040'>size</span>
  <span m='4875300'>of</span> <span m='4875400'>your</span> <span m='4875440'>piece</span>
  <span m='4875630'>of</span> <span m='4875670'>paper</span> <span m='4876060'>and</span>
  <span m='4876190'>the</span> <span m='4876270'>target</span> <span m='4876570'>shape.</span>
  </p><p><span m='4877570'>But</span> <span m='4877810'>actually,</span> <span m='4878750'>doing</span>
  <span m='4879050'>that</span> <span m='4879120'>optimization--</span> <span m='4879790'>the</span>
  <span m='4879870'>first</span> <span m='4880120'>step</span> <span m='4880330'>I</span>
  <span m='4880400'>did--</span> <span m='4881010'>is</span> <span m='4881230'>NP-complete.</span>
  <span m='4882020'>So</span> <span m='4882180'>it's</span> <span m='4882280'>not</span>
  <span m='4882440'>going</span> <span m='4882540'>to</span> <span m='4882580'>do</span>
  <span m='4882670'>it</span> <span m='4882720'>perfectly,</span> <span m='4882985'>and</span>
  <span m='4883250'>we'll</span> <span m='4883400'>prove</span> <span m='4883580'>that</span>
  <span m='4884430'>Wednesday.</span> <span m='4885720'>But</span> <span m='4886340'>the</span>
  <span m='4886490'>heuristics</span> <span m='4886940'>are</span> <span m='4887050'>pretty</span>
  <span m='4887250'>good.</span> </p><p><span m='4887520'>AUDIENCE:</span> <span m='4887932'>It  finds</span>
  <span m='4888344'>a local.</span> </p><p><span m='4888756'>PROFESSOR:</span> <span
  m='4889170'>It</span> <span m='4889300'>finds</span> <span m='4889520'>a</span>
  <span m='4889590'>local</span> <span m='4889880'>minimum,</span> <span m='4890690'>and</span>
  <span m='4891170'>often</span> <span m='4891460'>it</span> <span m='4891540'>finds</span>
  <span m='4891800'>a</span> <span m='4891900'>pretty</span> <span m='4892200'>good</span>
  <span m='4892390'>one.</span> <span m='4892710'>And</span> <span m='4892970'>sometimes</span>
  <span m='4893310'>you</span> <span m='4893590'>can</span> <span m='4893770'>coax</span>
  <span m='4894060'>it to</span> <span m='4894210'>find</span> <span m='4894440'>better</span>
  <span m='4894650'>ones,</span> <span m='4894960'>but,</span> <span m='4895090'>yeah.</span>
  <span m='4896000'>It's</span> <span m='4896150'>not</span> <span m='4896330'>perfect,</span>
  <span m='4897170'>but</span> <span m='4897190'>hey,</span> <span m='4897350'>it's
  NP-complete.</span> <span m='4898020'>So</span> <span m='4898190'>you</span> <span
  m='4898300'>can't</span> <span m='4898670'>do</span> <span m='4898830'>it.</span>
  </p><p><span m='4899580'>This</span> <span m='4899860'>actually</span> <span m='4900130'>shows</span>
  <span m='4900490'>you</span> <span m='4900730'>what</span> <span m='4900900'>it</span>
  <span m='4901000'>would</span> <span m='4901120'>look</span> <span m='4901320'>like</span>
  <span m='4902210'>in</span> <span m='4902580'>x-ray</span> <span m='4903000'>view.</span>
  <span m='4906640'>And</span> <span m='4906870'>then</span> <span m='4907010'>you</span>
  <span m='4907100'>can</span> <span m='4907220'>say,</span> <span m='4907430'>oh,</span>
  <span m='4907850'>that</span> <span m='4908040'>was</span> <span m='4908350'>nice,</span>
  <span m='4910100'>but</span> <span m='4910280'>let's--</span> <span m='4911570'>where
  is</span> <span m='4911980'>my--</span> <span m='4913268'>yeah,</span> <span m='4914570'>that</span>
  <span m='4914790'>was</span> <span m='4914960'>good.</span> <span m='4915980'>But</span>
  <span m='4916160'>maybe</span> <span m='4916650'>I</span> <span m='4916790'>really</span>
  <span m='4917140'>wanted</span> <span m='4917460'>the</span> <span m='4917530'>head</span>
  <span m='4918570'>segment</span> <span m='4918850'>to</span> <span m='4919130'>be</span>
  <span m='4920240'>shorter</span> <span m='4921910'>length of</span> <span m='4922210'>0.5.</span>
  <span m='4923660'>And</span> <span m='4924010'>then</span> <span m='4924170'>I</span>
  <span m='4924270'>wanted</span> <span m='4924670'>the</span> <span m='4924900'>tail</span>
  <span m='4925750'>to</span> <span m='4925940'>be</span> <span m='4926250'>really</span>
  <span m='4926520'>long.</span> </p><p><span m='4927910'>And</span> <span m='4928240'>then</span>
  <span m='4928570'>you</span> <span m='4928730'>can</span> <span m='4929220'>optimize</span>
  <span m='4929610'>that</span> <span m='4930470'>and</span> <span m='4930750'>find</span>
  <span m='4931000'>a</span> <span m='4931050'>crease</span> <span m='4931860'>pattern.</span>
  <span m='4932240'>And it'll</span> <span m='4932550'>complain.</span> <span m='4933170'>Because</span>
  <span m='4933430'>it's</span> <span m='4933690'>having</span> <span m='4933950'>trouble.</span>
  <span m='4934810'>Oh,</span> <span m='4935030'>dear.</span> </p><p><span m='4938150'>Demo</span>
  <span m='4938490'>effect.</span> <span m='4938860'>I should</span> <span m='4938950'>have</span>
  <span m='4939140'>tried</span> <span m='4939330'>this</span> <span m='4939510'>example</span>
  <span m='4940040'>before.</span> <span m='4941540'>It's</span> <span m='4941680'>not--</span>
  <span m='4942240'>oh,</span> <span m='4942950'>gosh.</span> <span m='4943935'>It's</span>
  <span m='4944400'>one of these</span> <span m='4944760'>annoying</span> <span m='4945080'>ones.</span>
  <span m='4945520'>I</span> <span m='4945700'>should</span> <span m='4945950'>say--</span>
  <span m='4951910'>I</span> <span m='4952080'>should</span> <span m='4952300'>add</span>
  <span m='4952560'>some</span> <span m='4952760'>feature</span> <span m='4954000'>like</span>
  <span m='4960040'>maybe</span> <span m='4961420'>a strain</span> <span m='4962710'>split</span>
  <span m='4963440'>something,</span> <span m='4964750'>add a</span> <span m='4964830'>little</span>
  <span m='4965050'>bit,</span> <span m='4966700'>maybe</span> <span m='4967290'>do</span>
  <span m='4967540'>that</span> <span m='4968180'>and--</span> <span m='4972040'>there</span>
  <span m='4972230'>we</span> <span m='4972330'>go.</span> </p><p><span m='4974150'>I</span>
  <span m='4974310'>cheated,</span> <span m='4974850'>and</span> <span m='4975190'>I'll</span>
  <span m='4975350'>explain</span> <span m='4975750'>how</span> <span m='4976090'>I</span>
  <span m='4976260'>cheated</span> <span m='4976560'>last</span> <span m='4976800'>time.</span>
  <span m='4977050'>But</span> <span m='4978200'>if</span> <span m='4978360'>sometimes</span>
  <span m='4979320'>the</span> <span m='4979420'>particular</span> <span m='4979900'>method</span>
  <span m='4980380'>fails</span> <span m='4981060'>but</span> <span m='4981260'>you</span>
  <span m='4981440'>can</span> <span m='4981590'>fix</span> <span m='4981900'>it</span>
  <span m='4982070'>by</span> <span m='4982360'>adding</span> <span m='4982730'>in</span>
  <span m='4982880'>another</span> <span m='4984280'>tiny</span> <span m='4984650'>limb</span>
  <span m='4985090'>off</span> <span m='4985280'>the</span> <span m='4985430'>edge</span>
  <span m='4986040'>somewhere--</span> <span m='4986850'>and</span> <span m='4987560'>of</span>
  <span m='4987620'>course,</span> <span m='4987840'>you</span> <span m='4987950'>can</span>
  <span m='4988090'>then</span> <span m='4988240'>get</span> <span m='4988360'>rid</span>
  <span m='4988490'>of</span> <span m='4988560'>that</span> <span m='4988710'>at</span>
  <span m='4988800'>the</span> <span m='4988930'>end</span> <span m='4989170'>when</span>
  <span m='4989270'>you're</span> <span m='4989370'>folding,</span> <span m='4990510'>it</span>
  <span m='4990700'>only</span> <span m='4990860'>makes the</span> <span m='4991100'>problem</span>
  <span m='4991380'>slightly</span> <span m='4991740'>harder.</span> <span m='4992300'>And</span>
  <span m='4992480'>it'll</span> <span m='4992620'>still</span> <span m='4992810'>find</span>
  <span m='4993530'>a</span> <span m='4993590'>folding.</span> <span m='4994050'>But</span>
  <span m='4994180'>we'll</span> <span m='4994300'>talk</span> <span m='4994500'>about</span>
  <span m='4994740'>that</span> <span m='4995270'>next</span> <span m='4995450'>time.</span>
  <span m='4995750'>And I'm</span> <span m='4996430'>way</span> <span m='4996650'>out</span>
  <span m='4996750'>of</span> <span m='4996860'>time,</span> <span m='4998300'>so</span>
  <span m='4998930'>we</span> <span m='4999100'>will</span> <span m='4999510'>stop</span>
  <span m='4999770'>there.</span> </p>
type: course
uid: 1603733c609c79033c2088b144d09d73

---
None