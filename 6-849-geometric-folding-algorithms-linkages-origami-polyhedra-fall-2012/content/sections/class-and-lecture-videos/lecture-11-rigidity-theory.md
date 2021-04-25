---
about_this_resource_text: <p><strong>Description:</strong> This lecture begins with
  a review of linkages and classifying graphs as generically rigid or flexible. Conditions
  for minimally generic rigid graphs are presented with degree-of-freedom analysis.
  Proofs of Henneberg and Laman characterizations are given.</p> <p><strong>Speaker:</strong>
  Erik Demaine</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: k2jKCJ8fhj0
  parent_uid: 34f3ccafb01dcd7b542efb76fe5fe07b
  title: Video-YouTube-Stream
  type: Video
  uid: 82239e8163f6da43d751051606d29826
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/k2jKCJ8fhj0/default.jpg
  parent_uid: 34f3ccafb01dcd7b542efb76fe5fe07b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 7c8587ef092e8a0d7b5f9874034bbed0
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: 34f3ccafb01dcd7b542efb76fe5fe07b
  title: Video-iTunes U-MP4
  type: Video
  uid: a808bfb537355e1b86ad00ae0d37b065
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_lec11_300k.mp4
  parent_uid: 34f3ccafb01dcd7b542efb76fe5fe07b
  title: Video-Internet Archive-MP4
  type: Video
  uid: e3e02d30cebe6ef20aed09851323affb
- id: 3Play-3PlayYouTubeid-MP4
  media_location: k2jKCJ8fhj0
  parent_uid: 34f3ccafb01dcd7b542efb76fe5fe07b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: c9c711318860f9da86ac9a981ec4487e
- id: k2jKCJ8fhj0.srt
  parent_uid: 34f3ccafb01dcd7b542efb76fe5fe07b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-11-rigidity-theory/k2jKCJ8fhj0.srt
  title: 3play caption file
  type: null
  uid: 45e338d86e6a7610669a05ec00f01c02
- id: k2jKCJ8fhj0.pdf
  parent_uid: 34f3ccafb01dcd7b542efb76fe5fe07b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-11-rigidity-theory/k2jKCJ8fhj0.pdf
  title: 3play pdf file
  type: null
  uid: a39bd2f7b1b3e9abedfdbb3814741106
- id: Caption-3Play YouTube id-SRT
  parent_uid: 34f3ccafb01dcd7b542efb76fe5fe07b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: faad4d250582474bf19ccc6947b7f155
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 34f3ccafb01dcd7b542efb76fe5fe07b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: ce2ccc7402760bde991e4b3edc5f9566
inline_embed_id: 16535125lecture11:rigiditytheory26951047
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: lecture-11-rigidity-theory
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-11-rigidity-theory
template_type: Tabbed
title: 'Lecture 11: Rigidity Theory'
transcript: '<p><span m=''72290''>PROFESSOR: All</span> <span m=''72380''>right.</span>
  <span m=''72610''>Let''s</span> <span m=''72800''>get</span> <span m=''72930''>started.</span>
  <span m=''75050''>So</span> <span m=''75370''>we''re</span> <span m=''75510''>continuing</span>
  <span m=''76100''>on</span> <span m=''76210''>the</span> <span m=''76310''>theme</span>
  <span m=''76670''>of</span> <span m=''76870''>linkages.</span> </p><p><span m=''77920''>And</span>
  <span m=''78230''>just a</span> <span m=''78670''>brief</span> <span m=''79370''>recollection</span>
  <span m=''80040''>from</span> <span m=''80200''>last</span> <span m=''80460''>time--</span>
  <span m=''80870''>and</span> <span m=''81000''>also</span> <span m=''81240''>changing</span>
  <span m=''81610''>definitions</span> <span m=''82110''>a</span> <span m=''82150''>little</span>
  <span m=''82320''>bit and</span> <span m=''82480''>throwing</span> <span m=''82780''>away</span>
  <span m=''82990''>some</span> <span m=''83150''>details</span> <span m=''83540''>we</span>
  <span m=''83630''>won''t</span> <span m=''83830''>need--</span> <span m=''84780''>we</span>
  <span m=''84860''>have</span> <span m=''85000''>the</span> <span m=''85110''>idea</span>
  <span m=''85300''>of</span> <span m=''85380''>a</span> <span m=''85450''>graph,</span>
  <span m=''86090''>which</span> <span m=''86130''>is just</span> <span m=''86200''>vertices</span>
  <span m=''86630''>and</span> <span m=''87080''>edges.</span> <span m=''88730''>And</span>
  <span m=''89060''>then</span> <span m=''89300''>if</span> <span m=''89890''>we</span>
  <span m=''90040''>added</span> <span m=''90490''>edge</span> <span m=''90750''>lengths,</span>
  <span m=''91540''>if we</span> <span m=''91710''>put</span> <span m=''91870''>a</span>
  <span m=''91930''>number</span> <span m=''92300''>on</span> <span m=''92430''>each</span>
  <span m=''92600''>of</span> <span m=''92660''>the</span> <span m=''92750''>edges,</span>
  <span m=''93590''>we''ve</span> <span m=''93710''>got</span> <span m=''93920''>what</span>
  <span m=''94010''>we</span> <span m=''94120''>call</span> <span m=''94310''>the</span>
  <span m=''94380''>linkage.</span> <span m=''95420''>And</span> <span m=''95560''>then</span>
  <span m=''95650''>if</span> <span m=''95790''>we</span> <span m=''95930''>actually</span>
  <span m=''96220''>embed</span> <span m=''96670''>that</span> <span m=''97410''>picture</span>
  <span m=''98270''>into</span> <span m=''98950''>the</span> <span m=''99070''>plane,</span>
  <span m=''99600''>or</span> <span m=''99700''>into</span> <span m=''99890''>3D,</span>
  <span m=''100530''>or</span> <span m=''100600''>whatever</span> <span m=''101090''>space
  we''re</span> <span m=''101430''>working</span> <span m=''101830''>in,</span> <span
  m=''102410''>into</span> <span m=''102710''>d-dimensional</span> <span m=''103350''>space,</span>
  <span m=''104910''>then</span> <span m=''105160''>we</span> <span m=''105280''>call</span>
  <span m=''105490''>that</span> <span m=''105620''>a</span> <span m=''105680''>configuration</span>
  <span m=''106460''>of</span> <span m=''106560''>the</span> <span m=''106650''>linkage.</span>
  </p><p><span m=''107270''>And</span> <span m=''107490''>in</span> <span m=''107550''>general,</span>
  <span m=''108490''>there</span> <span m=''108600''>might</span> <span m=''108760''>be</span>
  <span m=''108870''>many</span> <span m=''109100''>configurations</span> <span m=''109950''>of</span>
  <span m=''110070''>one</span> <span m=''110240''>linkage.</span> <span m=''111040''>If</span>
  <span m=''111090''>it''s</span> <span m=''111250''>going</span> <span m=''111380''>to</span>
  <span m=''111450''>fold</span> <span m=''111765''>or</span> <span m=''112080''>move</span>
  <span m=''112250''>around,</span> <span m=''113210''>there</span> <span m=''113440''>is</span>
  <span m=''114320''>infinitely</span> <span m=''114760''>many</span> <span m=''115020''>configurations</span>
  <span m=''115720''>of</span> <span m=''115820''>a</span> <span m=''115860''>linkage.</span>
  <span m=''117060''>And</span> <span m=''117340''>what</span> <span m=''117530''>today</span>
  <span m=''117780''>is</span> <span m=''117940''>about</span> <span m=''118390''>is</span>
  <span m=''118660''>basically</span> <span m=''119050''>when</span> <span m=''119580''>there''s</span>
  <span m=''119780''>only</span> <span m=''120040''>one</span> <span m=''120330''>configuration,</span>
  <span m=''121010''>versus</span> <span m=''121330''>when</span> <span m=''121520''>there''s</span>
  <span m=''121690''>many,</span> <span m=''122560''>at</span> <span m=''122660''>least</span>
  <span m=''122850''>locally.</span> </p><p><span m=''124610''>So</span> <span m=''125160''>this</span>
  <span m=''125340''>is</span> <span m=''125470''>the</span> <span m=''125580''>concept</span>
  <span m=''126030''>of</span> <span m=''126200''>rigidity.</span> <span m=''132220''>So</span>
  <span m=''134140''>if</span> <span m=''134290''>we</span> <span m=''134390''>have</span>
  <span m=''134600''>some</span> <span m=''136330''>linkage</span> <span m=''136720''>configuration--</span>
  <span m=''139170''>some</span> <span m=''139540''>configuration</span> <span m=''139950''>of</span>
  <span m=''140360''>some</span> <span m=''140580''>linkage--</span> <span m=''145600''>then</span>
  <span m=''146080''>we</span> <span m=''146270''>call</span> <span m=''146600''>it</span>
  <span m=''147420''>flexible</span> <span m=''149480''>if</span> <span m=''149710''>it</span>
  <span m=''149820''>can</span> <span m=''150010''>move</span> <span m=''150350''>from</span>
  <span m=''150540''>that</span> <span m=''150730''>configuration</span> <span m=''152420''>in</span>
  <span m=''152580''>a</span> <span m=''152660''>non-trivial</span> <span m=''153300''>way.</span>
  <span m=''159970''>So</span> <span m=''160140''>we</span> <span m=''160210''>want</span>
  <span m=''160480''>a</span> <span m=''160540''>non-trivial</span> <span m=''161300''>motion</span>
  <span m=''163520''>starting</span> <span m=''165080''>from</span> <span m=''165260''>that</span>
  <span m=''165470''>configuration.</span> </p><p><span m=''170710''>And</span> <span
  m=''171020''>you''ll</span> <span m=''171230''>notice</span> <span m=''171650''>that</span>
  <span m=''171810''>in</span> <span m=''172150''>my</span> <span m=''172320''>definition</span>
  <span m=''172780''>of</span> <span m=''172880''>linkage</span> <span m=''173410''>here,</span>
  <span m=''174380''>I</span> <span m=''174500''>did</span> <span m=''174710''>not</span>
  <span m=''175040''>specify</span> <span m=''175610''>that</span> <span m=''175750''>some</span>
  <span m=''175990''>of</span> <span m=''176060''>the</span> <span m=''176120''>vertices</span>
  <span m=''176550''>could</span> <span m=''176680''>be</span> <span m=''176810''>pinned</span>
  <span m=''177240''>to</span> <span m=''177400''>the</span> <span m=''177510''>plane</span>
  <span m=''177850''>or</span> <span m=''177950''>pinned</span> <span m=''178290''>to</span>
  <span m=''178400''>3D,</span> <span m=''179230''>because</span> <span m=''179820''>we</span>
  <span m=''179980''>needed</span> <span m=''180250''>that</span> <span m=''180420''>a</span>
  <span m=''180470''>lot</span> <span m=''180700''>last</span> <span m=''180980''>time.</span>
  <span m=''181240''>A</span> <span m=''181330''>bunch</span> <span m=''181590''>of</span>
  <span m=''181670''>our</span> <span m=''182120''>gadgets</span> <span m=''184600''>had</span>
  <span m=''184820''>fixed</span> <span m=''185600''>vertices--</span> <span m=''186420''>pinned</span>
  <span m=''186700''>vertices.</span> <span m=''187940''>I''m</span> <span m=''188070''>going</span>
  <span m=''188160''>to</span> <span m=''188610''>throw</span> <span m=''188810''>that</span>
  <span m=''188980''>away,</span> <span m=''189420''>and</span> <span m=''189580''>the</span>
  <span m=''189650''>price</span> <span m=''189990''>I</span> <span m=''190140''>pay
  is</span> <span m=''190520''>that</span> <span m=''190590''>whatever</span> <span
  m=''190940''>linkage</span> <span m=''191290''>I</span> <span m=''191330''>build</span>
  <span m=''191660''>can</span> <span m=''191830''>float</span> <span m=''192140''>around</span>
  <span m=''192980''>in</span> <span m=''193130''>my</span> <span m=''193260''>space.</span>
  </p><p><span m=''194280''>And</span> <span m=''194390''>so</span> <span m=''194510''>I</span>
  <span m=''194600''>need</span> <span m=''194810''>to</span> <span m=''195170''>add</span>
  <span m=''195450''>this</span> <span m=''195610''>non-trivial</span> <span m=''196240''>specification</span>
  <span m=''197750''>to</span> <span m=''198410''>say</span> <span m=''199130''>that</span>
  <span m=''199280''>it''s</span> <span m=''199460''>not</span> <span m=''200860''>just</span>
  <span m=''201420''>a</span> <span m=''201530''>rigid</span> <span m=''201840''>motion.</span>
  <span m=''204020''>It''s</span> <span m=''204210''>not</span> <span m=''204420''>just</span>
  <span m=''204650''>a</span> <span m=''204700''>translation</span> <span m=''205500''>and/or</span>
  <span m=''205900''>rotation.</span> <span m=''210240''>That''s</span> <span m=''210620''>rigid</span>
  <span m=''210910''>motion.</span> <span m=''212000''>So</span> <span m=''212200''>you</span>
  <span m=''212360''>ignore</span> <span m=''212690''>translations</span> <span m=''213270''>and</span>
  <span m=''213380''>rotations,</span> <span m=''214080''>for</span> <span m=''214270''>example,</span>
  <span m=''214630''>by</span> <span m=''214760''>pinning.</span> </p><p><span m=''215770''>But</span>
  <span m=''216020''>you</span> <span m=''216140''>can</span> <span m=''216260''>also</span>
  <span m=''216460''>just</span> <span m=''216610''>see--</span> <span m=''216780''>what</span>
  <span m=''216990''>are</span> <span m=''217100''>all</span> <span m=''217230''>the</span>
  <span m=''217600''>motions</span> <span m=''218140''>I</span> <span m=''218220''>can</span>
  <span m=''218370''>do</span> <span m=''218500''>from</span> <span m=''218690''>here?</span>
  <span m=''219310''>If</span> <span m=''219470''>it''s</span> <span m=''219660''>just</span>
  <span m=''220830''>in</span> <span m=''221180''>2D,</span> <span m=''221730''>if</span>
  <span m=''221880''>it''s</span> <span m=''222050''>just</span> <span m=''222400''>the</span>
  <span m=''223030''>three</span> <span m=''223320''>dimensions</span> <span m=''223640''>of</span>
  <span m=''224340''>I</span> <span m=''224480''>can</span> <span m=''224680''>translate</span>
  <span m=''225270''>in two</span> <span m=''225660''>ways,</span> <span m=''226020''>and</span>
  <span m=''226120''>I</span> <span m=''226170''>can</span> <span m=''226300''>rotate</span>
  <span m=''226650''>in</span> <span m=''226750''>one</span> <span m=''226930''>way,</span>
  <span m=''227810''>then</span> <span m=''228300''>we</span> <span m=''228640''>don''t</span>
  <span m=''228850''>call</span> <span m=''229050''>it</span> <span m=''229100''>flexible,</span>
  <span m=''229600''>we</span> <span m=''229710''>call</span> <span m=''229980''>it</span>
  <span m=''230110''>rigid.</span> </p><p><span m=''239950''>And</span> <span m=''240160''>today</span>
  <span m=''240420''>is</span> <span m=''240540''>all</span> <span m=''240720''>about</span>
  <span m=''240990''>distinguishing</span> <span m=''241610''>rigid</span> <span m=''242250''>scenarios</span>
  <span m=''242870''>from</span> <span m=''243030''>flexible</span> <span m=''243480''>scenarios.</span>
  <span m=''245240''>And</span> <span m=''245700''>yesterday--</span> <span m=''246590''>or</span>
  <span m=''246750''>last</span> <span m=''247010''>class--</span> <span m=''247340''>was</span>
  <span m=''247530''>all</span> <span m=''247790''>about</span> <span m=''248990''>making</span>
  <span m=''249310''>things</span> <span m=''249510''>flexible, and</span> <span m=''250000''>making</span>
  <span m=''250270''>things</span> <span m=''250450''>flexible</span> <span m=''250850''>in</span>
  <span m=''250920''>an</span> <span m=''251030''>interesting</span> <span m=''251470''>way</span>
  <span m=''251770''>so</span> <span m=''251820''>that</span> <span m=''251940''>we</span>
  <span m=''252050''>computed</span> <span m=''252400''>some</span> <span m=''252550''>polynomial.</span>
  <span m=''253480''>Today,</span> <span m=''254240''>we''re</span> <span m=''254470''>really</span>
  <span m=''254730''>interested</span> <span m=''255080''>in</span> <span m=''255120''>the</span>
  <span m=''255210''>case</span> <span m=''255450''>where</span> <span m=''255570''>we</span>
  <span m=''255780''>can</span> <span m=''256089''>make</span> <span m=''256290''>things</span>
  <span m=''256529''>rigid.</span> </p><p><span m=''256950''>There</span> <span m=''257130''>are</span>
  <span m=''257180''>some</span> <span m=''257410''>places,</span> <span m=''257930''>some</span>
  <span m=''258190''>situations,</span> <span m=''259709''>where</span> <span m=''259959''>you</span>
  <span m=''260089''>want</span> <span m=''260450''>things</span> <span m=''260820''>to</span>
  <span m=''260940''>not</span> <span m=''261190''>move,</span> <span m=''262079''>like</span>
  <span m=''262590''>you''re</span> <span m=''262790''>building</span> <span m=''263080''>a</span>
  <span m=''263120''>building.</span> <span m=''264070''>Unless</span> <span m=''264330''>you''re</span>
  <span m=''264540''>really</span> <span m=''264820''>cool</span> <span m=''265100''>and</span>
  <span m=''265170''>you''re</span> <span m=''265260''>making</span> <span m=''265520''>a</span>
  <span m=''265540''>reconfigurable</span> <span m=''266180''>building,</span> <span
  m=''266820''>you</span> <span m=''266960''>want it</span> <span m=''267320''>to</span>
  <span m=''268120''>not</span> <span m=''268380''>move.</span> <span m=''268730''>You</span>
  <span m=''268870''>want it</span> <span m=''268980''>to</span> <span m=''269160''>be</span>
  <span m=''269300''>rigid.</span> <span m=''270240''>And</span> <span m=''270760''>so</span>
  <span m=''270970''>some</span> <span m=''271350''>classic</span> <span m=''271810''>examples</span>
  <span m=''272770''>of</span> <span m=''272900''>this</span> <span m=''273160''>are</span>
  <span m=''273410''>the</span> <span m=''273570''>truss.</span> </p><p><span m=''274450''>This
  is</span> <span m=''274700''>a</span> <span m=''274810''>standard</span> <span m=''275200''>planar</span>
  <span m=''275550''>truss</span> <span m=''275920''>of some</span> <span m=''276920''>nearby</span>
  <span m=''277880''>bridge.</span> <span m=''278790''>I</span> <span m=''279170''>have</span>
  <span m=''280020''>another</span> <span m=''280550''>truss</span> <span m=''280820''>for
  the</span> <span m=''281090''>architects.</span> <span m=''281670''>It''s an</span>
  <span m=''283170''>octet</span> <span m=''283670''>truss--</span> <span m=''285480''>or</span>
  <span m=''285640''>at</span> <span m=''285720''>least</span> <span m=''286830''>various</span>
  <span m=''287150''>sections</span> <span m=''287510''>of</span> <span m=''287670''>it</span>
  <span m=''288420''>in</span> <span m=''288530''>the</span> <span m=''288610''>Brussels</span>
  <span m=''288970''>airport.</span> <span m=''289530''>You</span> <span m=''289630''>see</span>
  <span m=''289800''>these</span> <span m=''289900''>a</span> <span m=''289950''>lot</span>
  <span m=''290150''>in</span> <span m=''290240''>airports,</span> <span m=''290730''>especially</span>
  <span m=''291090''>in</span> <span m=''291170''>ceilings.</span> <span m=''291650''>And</span>
  <span m=''292240''>trusses</span> <span m=''292530''>all</span> <span m=''292730''>over</span>
  <span m=''292880''>the</span> <span m=''292990''>place,</span> <span m=''293200''>especially</span>
  <span m=''293550''>in</span> <span m=''293600''>bridges.</span> </p><p><span m=''294510''>And</span>
  <span m=''294920''>they</span> <span m=''295100''>are</span> <span m=''295620''>rigid</span>
  <span m=''296120''>linkages.</span> <span m=''297090''>You''ve</span> <span m=''297260''>got</span>
  <span m=''298010''>vertices,</span> <span m=''298620''>you''ve</span> <span m=''298750''>got</span>
  <span m=''298940''>edges.</span> <span m=''301440''>In</span> <span m=''301590''>principle,</span>
  <span m=''302070''>they</span> <span m=''302100''>could</span> <span m=''302250''>hinge</span>
  <span m=''302590''>there,</span> <span m=''303240''>though</span> <span m=''303340''>they''re</span>
  <span m=''303450''>not</span> <span m=''303620''>usually</span> <span m=''303820''>designed</span>
  <span m=''304220''>to</span> <span m=''304290''>allow</span> <span m=''304540''>hinging.</span>
  <span m=''304880''>But</span> <span m=''305180''>the</span> <span m=''305280''>point</span>
  <span m=''305480''>is</span> <span m=''305630''>even</span> <span m=''305880''>if</span>
  <span m=''306000''>they</span> <span m=''306150''>are</span> <span m=''306790''>allowed</span>
  <span m=''307060''>to</span> <span m=''307110''>hinge,</span> <span m=''307460''>it</span>
  <span m=''307540''>will</span> <span m=''307700''>be</span> <span m=''307860''>a</span>
  <span m=''307950''>rigid</span> <span m=''308590''>3D</span> <span m=''309420''>linkage</span>
  <span m=''309820''>configuration.</span> </p><p><span m=''311710''>And</span> <span
  m=''311970''>these</span> <span m=''312170''>are</span> <span m=''312260''>very</span>
  <span m=''312620''>simple</span> <span m=''312990''>examples</span> <span m=''313580''>we</span>
  <span m=''313770''>would</span> <span m=''313920''>like</span> <span m=''314170''>to</span>
  <span m=''314290''>generalize</span> <span m=''315050''>to</span> <span m=''317900''>understand</span>
  <span m=''318320''>the</span> <span m=''318690''>general</span> <span m=''319060''>picture.</span>
  <span m=''319950''>Turns</span> <span m=''320230''>out,</span> <span m=''320440''>the</span>
  <span m=''320500''>general</span> <span m=''320760''>picture in</span> <span m=''321030''>3D</span>
  <span m=''321450''>is</span> <span m=''321570''>not</span> <span m=''321740''>really</span>
  <span m=''321920''>well</span> <span m=''322090''>understood.</span> <span m=''322500''>It''s</span>
  <span m=''322630''>quite</span> <span m=''322800''>complicated.</span> <span m=''323990''>But</span>
  <span m=''324040''>in</span> <span m=''324160''>2D,</span> <span m=''324640''>which</span>
  <span m=''324850''>is</span> <span m=''324960''>what</span> <span m=''325120''>we''ll</span>
  <span m=''325250''>be</span> <span m=''325380''>working</span> <span m=''325700''>in</span>
  <span m=''326140''>today,</span> <span m=''327070''>there''s</span> <span m=''327220''>a</span>
  <span m=''327270''>very</span> <span m=''327510''>good</span> <span m=''327660''>answer,
  and</span> <span m=''328060''>it''s</span> <span m=''328240''>very</span> <span
  m=''328620''>clean,</span> <span m=''329010''>and</span> <span m=''329180''>you</span>
  <span m=''329290''>can</span> <span m=''329390''>characterize</span> <span m=''330350''>all</span>
  <span m=''330710''>the</span> <span m=''330800''>good</span> <span m=''331090''>rigid</span>
  <span m=''331590''>2D</span> <span m=''331880''>structures</span> <span m=''332870''>to</span>
  <span m=''333130''>some</span> <span m=''333430''>extent.</span> </p><p><span m=''338100''>Let</span>
  <span m=''338280''>me</span> <span m=''339220''>elaborate</span> <span m=''339870''>a</span>
  <span m=''339920''>little</span> <span m=''340170''>bit.</span> <span m=''341170''>One</span>
  <span m=''341480''>annoying</span> <span m=''341820''>thing</span> <span m=''342080''>about</span>
  <span m=''342950''>rigidity</span> <span m=''344250''>is</span> <span m=''344470''>that</span>
  <span m=''344590''>it</span> <span m=''344720''>depends</span> <span m=''345440''>on</span>
  <span m=''345630''>the</span> <span m=''345720''>configuration,</span> <span m=''354900''>not</span>
  <span m=''355000''>just</span> <span m=''355230''>the</span> <span m=''355320''>linkage</span>
  <span m=''356180''>or</span> <span m=''356300''>the</span> <span m=''356400''>graph.</span>
  <span m=''360940''>So</span> <span m=''361040''>let</span> <span m=''361200''>me</span>
  <span m=''361330''>draw</span> <span m=''361580''>you</span> <span m=''362360''>a</span>
  <span m=''362450''>picture.</span> </p><p><span m=''365650''>Suppose</span> <span
  m=''365960''>we</span> <span m=''366080''>have</span> <span m=''366560''>a</span>
  <span m=''366820''>rigified</span> <span m=''367320''>square. I''m</span> <span
  m=''367710''>going</span> <span m=''367810''>to</span> <span m=''367880''>work</span>
  <span m=''368110''>in</span> <span m=''368260''>two</span> <span m=''368390''>dimensions.</span>
  <span m=''370740''>Add</span> <span m=''370910''>some</span> <span m=''371040''>triangles.</span>
  <span m=''371600''>So</span> <span m=''371700''>this</span> <span m=''371880''>thing</span>
  <span m=''372040''>is</span> <span m=''372160''>rigid.</span> <span m=''372580''>A
  bunch of</span> <span m=''372820''>triangles</span> <span m=''373180''>in</span>
  <span m=''373230''>the</span> <span m=''373310''>plane.</span> <span m=''374850''>And</span>
  <span m=''375190''>let''s</span> <span m=''375470''>say</span> <span m=''377300''>I</span>
  <span m=''377390''>do</span> <span m=''377560''>that,</span> <span m=''379220''>verses--</span>
  <span m=''380630''>and</span> <span m=''380850''>I''m</span> <span m=''380920''>going</span>
  <span m=''381050''>to</span> <span m=''381260''>allow</span> <span m=''381810''>crossings</span>
  <span m=''382510''>here.</span> <span m=''384090''>It</span> <span m=''384170''>doesn''t</span>
  <span m=''384410''>really</span> <span m=''384610''>matter</span> <span m=''384870''>too</span>
  <span m=''385010''>much.</span> </p><p><span m=''397490''>If</span> <span m=''397740''>I</span>
  <span m=''398340''>draw</span> <span m=''398540''>this</span> <span m=''398750''>right--</span>
  <span m=''399080''>and I''ve</span> <span m=''399380''>done</span> <span m=''399630''>a
  little</span> <span m=''399900''>better.</span> <span m=''400430''>It''s</span>
  <span m=''400620''>easier</span> <span m=''400880''>when</span> <span m=''400990''>I</span>
  <span m=''401010''>have</span> <span m=''401130''>a</span> <span m=''401180''>grid--</span>
  <span m=''401900''>my</span> <span m=''402040''>graph</span> <span m=''402330''>paper.</span>
  <span m=''403950''>In</span> <span m=''404110''>this</span> <span m=''404290''>situation,</span>
  <span m=''404970''>the</span> <span m=''405080''>configuration</span> <span m=''405650''>should</span>
  <span m=''405840''>be</span> <span m=''406000''>rigid,</span> <span m=''406930''>because</span>
  <span m=''407210''>this</span> <span m=''407410''>part</span> <span m=''407640''>is</span>
  <span m=''407770''>rigid,</span> <span m=''408350''>and</span> <span m=''408620''>these</span>
  <span m=''408840''>three</span> <span m=''409050''>bars</span> <span m=''409690''>are</span>
  <span m=''409890''>held</span> <span m=''410220''>taut,</span> <span m=''412860''>because</span>
  <span m=''413110''>these</span> <span m=''413340''>vertices</span> <span m=''413780''>are</span>
  <span m=''413980''>effectively</span> <span m=''414520''>pinned</span> <span m=''414980''>to</span>
  <span m=''415130''>the</span> <span m=''415240''>rest</span> <span m=''415480''>of</span>
  <span m=''415580''>this</span> <span m=''415760''>framework.</span> <span m=''416600''>And</span>
  <span m=''416690''>this</span> <span m=''416850''>is</span> <span m=''417000''>at</span>
  <span m=''417370''>full</span> <span m=''417630''>length.</span> <span m=''418050''>You</span>
  <span m=''418170''>can''t</span> <span m=''418390''>really</span> <span m=''418600''>hinge</span>
  <span m=''418910''>here.</span> </p><p><span m=''420150''>Whereas</span> <span m=''420510''>if</span>
  <span m=''420740''>I</span> <span m=''420980''>flip</span> <span m=''421950''>this</span>
  <span m=''422220''>triangle</span> <span m=''423490''>through</span> <span m=''423790''>that</span>
  <span m=''424250''>vertical</span> <span m=''424690''>line,</span> <span m=''425780''>flip</span>
  <span m=''425950''>that</span> <span m=''426130''>over,</span> <span m=''426370''>I</span>
  <span m=''426470''>get</span> <span m=''426730''>this</span> <span m=''426970''>triangle.</span>
  <span m=''427860''>And</span> <span m=''428130''>I did</span> <span m=''428220''>the</span>
  <span m=''428290''>same</span> <span m=''428520''>thing</span> <span m=''428710''>for</span>
  <span m=''428780''>the</span> <span m=''428880''>other</span> <span m=''429030''>triangle.</span>
  <span m=''429350''>I</span> <span m=''429400''>didn''t</span> <span m=''429590''>have</span>
  <span m=''429840''>to.</span> <span m=''430440''>But</span> <span m=''430570''>now,</span>
  <span m=''430790''>suddenly--</span> <span m=''431720''>and</span> <span m=''431810''>you</span>
  <span m=''431900''>can''t</span> <span m=''432130''>do</span> <span m=''432230''>that</span>
  <span m=''432430''>by a</span> <span m=''432570''>motion.</span> <span m=''433090''>But</span>
  <span m=''433220''>if</span> <span m=''433350''>I</span> <span m=''433410''>consider</span>
  <span m=''433770''>this</span> <span m=''433960''>other</span> <span m=''434210''>configuration</span>
  <span m=''434910''>where</span> <span m=''435030''>that''s</span> <span m=''435410''>the</span>
  <span m=''435490''>case,</span> <span m=''436420''>then</span> <span m=''436540''>suddenly</span>
  <span m=''437480''>these</span> <span m=''437740''>guys,</span> <span m=''438010''>which</span>
  <span m=''438150''>have</span> <span m=''438270''>exactly</span> <span m=''438680''>the</span>
  <span m=''438750''>same</span> <span m=''438980''>lengths</span> <span m=''439310''>as</span>
  <span m=''439420''>they</span> <span m=''439520''>did</span> <span m=''439670''>before,</span>
  <span m=''440990''>have</span> <span m=''441170''>some</span> <span m=''441310''>slack,</span>
  <span m=''442150''>and</span> <span m=''442300''>now</span> <span m=''442570''>you</span>
  <span m=''442740''>can</span> <span m=''442870''>think</span> <span m=''443060''>of</span>
  <span m=''443160''>this</span> <span m=''443440''>as</span> <span m=''443690''>a</span>
  <span m=''443940''>quadrilateral</span> <span m=''444630''>which</span> <span m=''444840''>can</span>
  <span m=''445570''>flex</span> <span m=''445950''>separately.</span> </p><p><span
  m=''446880''>So</span> <span m=''446940''>this</span> <span m=''447160''>guy''s</span>
  <span m=''447340''>flexible,</span> <span m=''449240''>and</span> <span m=''449660''>this</span>
  <span m=''449850''>guy''s</span> <span m=''450050''>rigid.</span> <span m=''452940''>This</span>
  <span m=''453110''>is</span> <span m=''453210''>annoying,</span> <span m=''454990''>because</span>
  <span m=''456160''>we''d</span> <span m=''456390''>like</span> <span m=''456640''>to--</span>
  <span m=''458260''>think</span> <span m=''458440''>of</span> <span m=''458550''>a</span>
  <span m=''458620''>truss,</span> <span m=''459000''>or</span> <span m=''459060''>something</span>
  <span m=''459840''>like</span> <span m=''460390''>this.</span> <span m=''463140''>You</span>
  <span m=''463260''>don''t</span> <span m=''463410''>think</span> <span m=''463580''>about</span>
  <span m=''463780''>exactly</span> <span m=''464320''>how</span> <span m=''464550''>it''s
  drawn.</span> <span m=''464960''>You</span> <span m=''465030''>just</span> <span
  m=''465250''>think,</span> <span m=''465510''>oh,</span> <span m=''465720''>well,</span>
  <span m=''465860''>there''s</span> <span m=''466070''>this</span> <span m=''466130''>structure.</span>
  <span m=''466530''>It''s</span> <span m=''466660''>got</span> <span m=''466820''>vertices.</span>
  <span m=''467420''>It''s</span> <span m=''467620''>like</span> <span m=''467780''>squares</span>
  <span m=''468040''>with</span> <span m=''468300''>diagonals.</span> <span m=''469870''>Does</span>
  <span m=''470090''>it</span> <span m=''470190''>work</span> <span m=''470490''>if</span>
  <span m=''470770''>they''re</span> <span m=''471000''>skewed</span> <span m=''471380''>squares?</span>
  <span m=''475030''>This</span> <span m=''475140''>presumably</span> <span m=''475340''>works.</span>
  </p><p><span m=''477060''>We</span> <span m=''477240''>think,</span> <span m=''477540''>oh,</span>
  <span m=''477700''>triangles</span> <span m=''478160''>are</span> <span m=''478230''>rigid.</span>
  <span m=''478710''>It</span> <span m=''478930''>shouldn''t</span> <span m=''479180''>matter</span>
  <span m=''479430''>exactly</span> <span m=''479770''>how</span> <span m=''479910''>they''re</span>
  <span m=''480030''>drawn.</span> <span m=''480780''>And</span> <span m=''481040''>it</span>
  <span m=''481240''>turns</span> <span m=''481530''>out,</span> <span m=''481660''>most</span>
  <span m=''481900''>of</span> <span m=''482000''>the</span> <span m=''482100''>time,</span>
  <span m=''482220''>it</span> <span m=''482300''>doesn''t</span> <span m=''482600''>matter</span>
  <span m=''482860''>how</span> <span m=''483000''>they''re</span> <span m=''483140''>drawn.</span>
  <span m=''483560''>This</span> <span m=''483750''>is</span> <span m=''483880''>kind</span>
  <span m=''484070''>of</span> <span m=''484170''>a</span> <span m=''484230''>very</span>
  <span m=''484430''>special</span> <span m=''484830''>case,</span> <span m=''485710''>and</span>
  <span m=''486090''>I</span> <span m=''486130''>want</span> <span m=''486290''>to</span>
  <span m=''486350''>formalize</span> <span m=''487410''>that</span> <span m=''487580''>notion</span>
  <span m=''487850''>of</span> <span m=''487920''>"special</span> <span m=''488270''>case"</span>
  <span m=''488620''>and</span> <span m=''488930''>"most</span> <span m=''489210''>of</span>
  <span m=''489290''>the</span> <span m=''489390''>time."</span> </p><p><span m=''491240''>Because</span>
  <span m=''491820''>in</span> <span m=''491900''>particular,</span> <span m=''492830''>if</span>
  <span m=''492960''>I</span> <span m=''494310''>gave</span> <span m=''494670''>you</span>
  <span m=''496950''>a</span> <span m=''497050''>particular</span> <span m=''497600''>linkage</span>
  <span m=''497920''>configuration,</span> <span m=''499310''>and</span> <span m=''499520''>I</span>
  <span m=''499580''>ask</span> <span m=''499920''>you,</span> <span m=''500100''>is</span>
  <span m=''500260''>it</span> <span m=''500380''>rigid?</span> <span m=''511250''>As</span>
  <span m=''511520''>I</span> <span m=''511570''>mentioned</span> <span m=''512159''>in</span>
  <span m=''512440''>the</span> <span m=''512510''>last</span> <span m=''512780''>class,</span>
  <span m=''513980''>this</span> <span m=''514340''>is</span> <span m=''515200''>coNP-hard.</span>
  <span m=''518070''>So</span> <span m=''518210''>almost</span> <span m=''518600''>certainly</span>
  <span m=''519650''>there''s</span> <span m=''519840''>no</span> <span m=''520140''>good</span>
  <span m=''520330''>algorithm</span> <span m=''520655''>to</span> <span m=''520980''>tell</span>
  <span m=''521309''>you</span> <span m=''521440''>whether</span> <span m=''521929''>a</span>
  <span m=''522000''>given</span> <span m=''522340''>linkage</span> <span m=''522630''>configuration</span>
  <span m=''523909''>like</span> <span m=''524049''>this--</span> <span m=''524320''>versus</span>
  <span m=''524610''>this--</span> <span m=''524970''>is</span> <span m=''525120''>rigid.</span>
  <span m=''526590''>That''s</span> <span m=''527470''>disconcerting,</span> <span
  m=''528270''>because</span> <span m=''528770''>I</span> <span m=''528950''>want</span>
  <span m=''529180''>to</span> <span m=''529280''>have</span> <span m=''529610''>a</span>
  <span m=''529680''>good</span> <span m=''529840''>characterization</span> <span
  m=''530530''>of</span> <span m=''530640''>rigidity.</span> <span m=''530950''>And</span>
  <span m=''531020''>this</span> <span m=''531190''>is</span> <span m=''531260''>true,</span>
  <span m=''531420''>even</span> <span m=''531620''>in</span> <span m=''531710''>two</span>
  <span m=''531830''>dimensions.</span> </p><p><span m=''534770''>So</span> <span
  m=''535590''>we''re</span> <span m=''535760''>going</span> <span m=''535870''>to</span>
  <span m=''536240''>change</span> <span m=''536520''>the</span> <span m=''536610''>problem</span>
  <span m=''536870''>a</span> <span m=''536910''>little</span> <span m=''537220''>bit</span>
  <span m=''537810''>so</span> <span m=''537970''>suddenly it</span> <span m=''538430''>becomes</span>
  <span m=''539220''>easy.</span> <span m=''541170''>We''re</span> <span m=''541330''>going</span>
  <span m=''541430''>to</span> <span m=''541480''>be</span> <span m=''541590''>a</span>
  <span m=''541640''>little</span> <span m=''541860''>bit</span> <span m=''542010''>less</span>
  <span m=''542240''>precise.</span> <span m=''542650''>We''re</span> <span m=''542750''>not</span>
  <span m=''542930''>going</span> <span m=''543050''>be</span> <span m=''543120''>able</span>
  <span m=''543260''>to</span> <span m=''543340''>distinguish</span> <span m=''543780''>between</span>
  <span m=''544000''>this</span> <span m=''544190''>and</span> <span m=''544310''>this,</span>
  <span m=''545370''>but</span> <span m=''545510''>almost</span> <span m=''545930''>all</span>
  <span m=''546090''>the</span> <span m=''546180''>time--</span> <span m=''546800''>like
  if</span> <span m=''546850''>this</span> <span m=''547110''>thing</span> <span m=''547240''>just</span>
  <span m=''547440''>had</span> <span m=''547550''>a</span> <span m=''547610''>little</span>
  <span m=''547880''>bit</span> <span m=''548010''>of</span> <span m=''548080''>slack,</span>
  <span m=''548510''>it</span> <span m=''548640''>would</span> <span m=''548800''>be</span>
  <span m=''548920''>flexible.</span> <span m=''550160''>So</span> <span m=''550330''>we''re</span>
  <span m=''550440''>going to</span> <span m=''550650''>ignore</span> <span m=''550820''>the</span>
  <span m=''550930''>fact</span> <span m=''551230''>that</span> <span m=''551340''>occasionally</span>
  <span m=''551860''>this</span> <span m=''552080''>thing</span> <span m=''552420''>is</span>
  <span m=''552590''>taut,</span> <span m=''553560''>and</span> <span m=''553750''>most</span>
  <span m=''554000''>of</span> <span m=''554100''>the</span> <span m=''554120''>time,</span>
  <span m=''554710''>this</span> <span m=''555300''>picture</span> <span m=''555750''>would</span>
  <span m=''555910''>be</span> <span m=''556050''>flexible</span> <span m=''557370''>most</span>
  <span m=''557670''>of</span> <span m=''557720''>the</span> <span m=''557800''>ways</span>
  <span m=''558000''>you</span> <span m=''558100''>draw it.</span> </p><p><span m=''562810''>All</span>
  <span m=''562960''>right.</span> <span m=''564740''>This</span> <span m=''564930''>is</span>
  <span m=''565010''>the</span> <span m=''565160''>idea</span> <span m=''565570''>of</span>
  <span m=''565780''>generic</span> <span m=''566210''>rigidity.</span> <span m=''575900''>We''ve</span>
  <span m=''576060''>talked</span> <span m=''576350''>about</span> <span m=''576690''>generic</span>
  <span m=''577110''>situations</span> <span m=''577710''>before</span> <span m=''578140''>in</span>
  <span m=''578580''>a</span> <span m=''578630''>single</span> <span m=''578900''>vertex</span>
  <span m=''579260''>piece</span> <span m=''579450''>patterns.</span> <span m=''580430''>We
  said,</span> <span m=''580620''>well,</span> <span m=''580770''>generically,</span>
  <span m=''582070''>no</span> <span m=''582220''>two</span> <span m=''582410''>angles</span>
  <span m=''582730''>are</span> <span m=''582840''>ever</span> <span m=''583010''>going</span>
  <span m=''583140''>to</span> <span m=''583210''>be</span> <span m=''583340''>the</span>
  <span m=''583450''>same</span> <span m=''584125''>if we</span> <span m=''584440''>just</span>
  <span m=''584580''>sort</span> <span m=''584750''>of</span> <span m=''585020''>perturb</span>
  <span m=''585440''>everything</span> <span m=''585790''>a</span> <span m=''585840''>little</span>
  <span m=''586030''>bit.</span> <span m=''586600''>We''re</span> <span m=''586710''>going</span>
  <span m=''586810''>to</span> <span m=''586900''>take</span> <span m=''587100''>the</span>
  <span m=''587180''>same</span> <span m=''587420''>idea</span> <span m=''587720''>here.</span>
  <span m=''588570''>And</span> <span m=''588770''>so,</span> <span m=''588900''>for</span>
  <span m=''589100''>example,</span> <span m=''590060''>no</span> <span m=''590300''>two</span>
  <span m=''590930''>edge</span> <span m=''591160''>lengths</span> <span m=''591440''>are</span>
  <span m=''591520''>going</span> <span m=''591640''>to</span> <span m=''591700''>be</span>
  <span m=''591820''>the</span> <span m=''591910''>same,</span> <span m=''592740''>but</span>
  <span m=''592860''>we''re</span> <span m=''592960''>going</span> <span m=''593060''>to</span>
  <span m=''593100''>assume</span> <span m=''593360''>a</span> <span m=''593410''>lot</span>
  <span m=''593620''>more</span> <span m=''593830''>than</span> <span m=''593990''>that</span>
  <span m=''594330''>to</span> <span m=''594490''>make</span> <span m=''594780''>life</span>
  <span m=''595200''>easier.</span> </p><p><span m=''599040''>The</span> <span m=''599150''>general</span>
  <span m=''599520''>goal</span> <span m=''601580''>is</span> <span m=''601800''>to</span>
  <span m=''601930''>think</span> <span m=''602180''>about</span> <span m=''602570''>the</span>
  <span m=''602670''>graph--</span> <span m=''603580''>not</span> <span m=''603810''>the</span>
  <span m=''603890''>linkage,</span> <span m=''604750''>and</span> <span m=''604900''>not</span>
  <span m=''605270''>the</span> <span m=''606400''>configuration.</span> <span m=''610990''>I</span>
  <span m=''611120''>want</span> <span m=''611280''>to</span> <span m=''611340''>say</span>
  <span m=''611510''>that</span> <span m=''611630''>rigidity</span> <span m=''612220''>is</span>
  <span m=''612350''>usually</span> <span m=''614220''>a</span> <span m=''614290''>property</span>
  <span m=''614680''>of</span> <span m=''614760''>the</span> <span m=''614830''>graph.</span>
  <span m=''622730''>Most</span> <span m=''623100''>the</span> <span m=''623190''>time,</span>
  <span m=''623520''>it</span> <span m=''623570''>doesn''t</span> <span m=''623790''>matter</span>
  <span m=''624060''>what</span> <span m=''624190''>your</span> <span m=''624310''>edge</span>
  <span m=''624470''>lengths</span> <span m=''624730''>are,</span> <span m=''625310''>it</span>
  <span m=''625410''>doesn''t</span> <span m=''625640''>matter</span> <span m=''625880''>exactly</span>
  <span m=''626240''>how</span> <span m=''626310''>you</span> <span m=''626450''>draw
  it,</span> <span m=''626690''>it</span> <span m=''626890''>just</span> <span m=''627200''>matters</span>
  <span m=''627530''>how</span> <span m=''627790''>things</span> <span m=''628050''>are</span>
  <span m=''628130''>connected.</span> <span m=''628920''>Are</span> <span m=''629100''>they</span>
  <span m=''629220''>triangles?</span> <span m=''630670''>What</span> <span m=''630840''>is</span>
  <span m=''630970''>that</span> <span m=''631480''>combinatorial</span> <span m=''632100''>structure?</span>
  <span m=''634150''>The</span> <span m=''634250''>geometry</span> <span m=''634800''>falls</span>
  <span m=''635100''>out</span> <span m=''635240''>of</span> <span m=''635340''>it.</span>
  <span m=''635500''>I</span> <span m=''635580''>need</span> <span m=''635790''>one</span>
  <span m=''636020''>term</span> <span m=''636490''>so</span> <span m=''636660''>I</span>
  <span m=''636750''>can</span> <span m=''636970''>talk</span> <span m=''637220''>about</span>
  <span m=''637540''>graphs</span> <span m=''638680''>in</span> <span m=''638930''>a</span>
  <span m=''640730''>realization.</span> </p><p><span m=''648460''>This</span> <span
  m=''648730''>is</span> <span m=''648880''>just</span> <span m=''649260''>shorthand.</span>
  <span m=''650475''>It''ll</span> <span m=''650960''>make</span> <span m=''651190''>my</span>
  <span m=''651290''>life</span> <span m=''651540''>a</span> <span m=''651580''>lot</span>
  <span m=''651750''>easier.</span> <span m=''652130''>It''s</span> <span m=''652380''>a</span>
  <span m=''652450''>configuration</span> <span m=''653720''>of</span> <span m=''653930''>a</span>
  <span m=''653970''>linkage</span> <span m=''655440''>of</span> <span m=''655620''>the</span>
  <span m=''655710''>graph.</span> <span m=''660440''>We</span> <span m=''660710''>have</span>
  <span m=''660950''>three</span> <span m=''661130''>levels.</span> <span m=''662710''>The</span>
  <span m=''662720''>graph,</span> <span m=''663080''>which is</span> <span m=''663150''>just</span>
  <span m=''663390''>the</span> <span m=''663450''>combinatorial</span> <span m=''663670''>infrastructure,</span>
  <span m=''664250''>linkage,</span> <span m=''664580''>where</span> <span m=''664730''>you</span>
  <span m=''664810''>add</span> <span m=''664970''>the edge</span> <span m=''665230''>lengths,</span>
  <span m=''665480''>and</span> <span m=''665580''>then</span> <span m=''665680''>a</span>
  <span m=''665730''>configuration</span> <span m=''666020''>where you</span> <span
  m=''666310''>draw</span> <span m=''666760''>it.</span> <span m=''667410''>I''m</span>
  <span m=''667550''>going</span> <span m=''667640''>to</span> <span m=''667740''>jump</span>
  <span m=''668000''>all</span> <span m=''668200''>the</span> <span m=''668270''>way</span>
  <span m=''668400''>to</span> <span m=''668490''>the</span> <span m=''668660''>end</span>
  <span m=''669110''>and</span> <span m=''669590''>say,</span> <span m=''670190''>if</span>
  <span m=''670240''>I</span> <span m=''670300''>start</span> <span m=''670590''>with</span>
  <span m=''670710''>a</span> <span m=''670760''>graph,</span> <span m=''671080''>I</span>
  <span m=''671100''>want</span> <span m=''671260''>to</span> <span m=''671300''>go</span>
  <span m=''671420''>all</span> <span m=''671570''>the</span> <span m=''671640''>way</span>
  <span m=''671750''>to</span> <span m=''671810''>a</span> <span m=''671880''>configuration.</span>
  <span m=''672630''>That''s</span> <span m=''672870''>a</span> <span m=''672940''>realization.</span>
  </p><p><span m=''674300''>And</span> <span m=''674540''>so</span> <span m=''674950''>you</span>
  <span m=''675120''>can</span> <span m=''675250''>think</span> <span m=''675460''>of</span>
  <span m=''675620''>a</span> <span m=''675680''>realization</span> <span m=''677010''>as</span>
  <span m=''677270''>just</span> <span m=''677450''>some</span> <span m=''677620''>mapping.</span>
  <span m=''678600''>It</span> <span m=''678800''>looks</span> <span m=''679000''>exactly</span>
  <span m=''679360''>like</span> <span m=''679530''>a</span> <span m=''679600''>configuration.</span>
  <span m=''681770''>Just</span> <span m=''681980''>forget</span> <span m=''682220''>about</span>
  <span m=''682450''>the</span> <span m=''682560''>edge</span> <span m=''682730''>lengths.</span>
  <span m=''683550''>You</span> <span m=''683710''>can</span> <span m=''683850''>put</span>
  <span m=''683990''>the</span> <span m=''684060''>vertices</span> <span m=''684440''>wherever</span>
  <span m=''684720''>you</span> <span m=''684840''>want,</span> <span m=''685100''>because</span>
  <span m=''685330''>you</span> <span m=''685530''>haven''t</span> <span m=''685840''>said</span>
  <span m=''686000''>what</span> <span m=''686100''>the</span> <span m=''686190''>edge</span>
  <span m=''686320''>lengths</span> <span m=''686560''>are</span> <span m=''686610''>supposed</span>
  <span m=''686930''>to</span> <span m=''686990''>be.</span> </p><p><span m=''688590''>So</span>
  <span m=''688830''>by</span> <span m=''689010''>taking a</span> <span m=''689370''>graph</span>
  <span m=''689660''>and</span> <span m=''689800''>drawing</span> <span m=''690180''>it
  in</span> <span m=''690770''>the</span> <span m=''690870''>plane--</span> <span
  m=''691210''>this is</span> <span m=''691550''>going</span> <span m=''691650''>to</span>
  <span m=''691700''>be</span> <span m=''691850''>our</span> <span m=''691920''>situation--</span>
  <span m=''693070''>you</span> <span m=''693220''>can</span> <span m=''693360''>compute</span>
  <span m=''693670''>what</span> <span m=''693810''>the</span> <span m=''693910''>edge</span>
  <span m=''694050''>lengths</span> <span m=''694280''>become,</span> <span m=''694810''>and</span>
  <span m=''694960''>then</span> <span m=''695100''>see,</span> <span m=''695460''>does</span>
  <span m=''695690''>it</span> <span m=''695840''>flex</span> <span m=''696220''>given</span>
  <span m=''696450''>those</span> <span m=''696770''>edge lengths?</span> <span m=''697480''>So
  as</span> <span m=''697640''>soon</span> <span m=''697840''>as</span> <span m=''697920''>you</span>
  <span m=''698030''>draw in</span> <span m=''698280''>the</span> <span m=''698460''>plane,</span>
  <span m=''698820''>the edge</span> <span m=''699110''>lengths</span> <span m=''699310''>become</span>
  <span m=''699560''>fixed.</span> <span m=''700010''>But</span> <span m=''700140''>before</span>
  <span m=''700410''>that,</span> <span m=''700600''>they''re</span> <span m=''700730''>free</span>
  <span m=''701110''>to</span> <span m=''701230''>be</span> <span m=''701390''>whatever</span>
  <span m=''701650''>you</span> <span m=''701750''>want.</span> <span m=''702570''>You
  just</span> <span m=''702810''>embed</span> <span m=''703030''>every</span> <span
  m=''703220''>vertex</span> <span m=''703770''>into</span> <span m=''703980''>the</span>
  <span m=''704080''>plane,</span> <span m=''704460''>and</span> <span m=''704890''>you</span>
  <span m=''704990''>get</span> <span m=''705120''>a</span> <span m=''705180''>realization.</span>
  </p><p><span m=''707050''>And</span> <span m=''707210''>now</span> <span m=''707490''>I</span>
  <span m=''707620''>want</span> <span m=''707840''>to</span> <span m=''707880''>define</span>
  <span m=''708240''>the</span> <span m=''708320''>notion</span> <span m=''708620''>of</span>
  <span m=''708730''>a</span> <span m=''708800''>generic</span> <span m=''710320''>realization.</span>
  <span m=''712800''>And</span> <span m=''712920''>this</span> <span m=''713130''>is</span>
  <span m=''713280''>a</span> <span m=''713370''>subtle</span> <span m=''713680''>notion,</span>
  <span m=''714300''>and</span> <span m=''714490''>it''s</span> <span m=''714680''>a</span>
  <span m=''714720''>little</span> <span m=''715260''>tricky</span> <span m=''715610''>to</span>
  <span m=''715750''>define.</span> <span m=''718470''>So</span> <span m=''718670''>I''m</span>
  <span m=''718730''>going</span> <span m=''718820''>to</span> <span m=''718860''>give</span>
  <span m=''719000''>the</span> <span m=''719080''>intuition.</span> <span m=''720390''>And</span>
  <span m=''720500''>I</span> <span m=''720530''>will</span> <span m=''720720''>give</span>
  <span m=''720890''>a</span> <span m=''721030''>definition--</span> <span m=''721620''>we''ll</span>
  <span m=''721730''>see</span> <span m=''721870''>another</span> <span m=''722110''>definition</span>
  <span m=''722580''>next</span> <span m=''722810''>class,</span> <span m=''723180''>in</span>
  <span m=''723260''>fact.</span> <span m=''726090''>But</span> <span m=''726290''>it''s</span>
  <span m=''726420''>a</span> <span m=''726490''>pretty</span> <span m=''726720''>intuitive</span>
  <span m=''727870''>notion,</span> <span m=''730030''>especially</span> <span m=''732530''>the</span>
  <span m=''732650''>way</span> <span m=''732810''>I''ll</span> <span m=''732920''>be</span>
  <span m=''733040''>using</span> <span m=''733360''>it.</span> </p><p><span m=''734070''>I</span>
  <span m=''734240''>want</span> <span m=''734440''>to</span> <span m=''734510''>somehow</span>
  <span m=''734920''>avoid</span> <span m=''735770''>things</span> <span m=''736000''>that</span>
  <span m=''736120''>are</span> <span m=''736240''>rare--</span> <span m=''737050''>degenerate</span>
  <span m=''737530''>situations.</span> <span m=''738680''>And</span> <span m=''738940''>mathematically,</span>
  <span m=''739530''>that</span> <span m=''739690''>means</span> <span m=''739900''>lower</span>
  <span m=''740210''>dimensional</span> <span m=''740700''>situations.</span> <span
  m=''742120''>In</span> <span m=''742270''>general,</span> <span m=''743350''>a</span>
  <span m=''743430''>realization--</span> <span m=''745030''>remember,</span> <span
  m=''745430''>we</span> <span m=''745450''>can</span> <span m=''745610''>think</span>
  <span m=''745860''>of</span> <span m=''746050''>it</span> <span m=''746100''>as</span>
  <span m=''746290''>a</span> <span m=''746370''>point</span> <span m=''749770''>in</span>
  <span m=''752160''>d</span> <span m=''752540''>times</span> <span m=''753010''>n</span>
  <span m=''753240''>dimensional</span> <span m=''753750''>space.</span> <span m=''754720''>If
  n</span> <span m=''754980''>is</span> <span m=''755100''>a</span> <span m=''755150''>number</span>
  <span m=''755380''>vertices,</span> <span m=''756120''>d</span> <span m=''756240''>is</span>
  <span m=''756350''>the</span> <span m=''756440''>dimension</span> <span m=''757030''>of</span>
  <span m=''757670''>space</span> <span m=''758020''>that</span> <span m=''758150''>they</span>
  <span m=''758250''>live</span> <span m=''758520''>in.</span> <span m=''759420''>Then</span>
  <span m=''759630''>we</span> <span m=''759750''>could</span> <span m=''759870''>just</span>
  <span m=''760040''>write</span> <span m=''760220''>down</span> <span m=''760380''>the</span>
  <span m=''760450''>coordinates</span> <span m=''760870''>of</span> <span m=''760960''>every</span>
  <span m=''761160''>vertex</span> <span m=''761550''>separately.</span> <span m=''762340''>And</span>
  <span m=''763210''>the</span> <span m=''763440''>realization</span> <span m=''764020''>space</span>
  <span m=''764310''>is</span> <span m=''764400''>just</span> <span m=''764600''>that.</span>
  <span m=''764890''>You</span> <span m=''765000''>can</span> <span m=''765140''>do</span>
  <span m=''765310''>whatever</span> <span m=''765580''>you</span> <span m=''765690''>want.</span>
  </p><p><span m=''769190''>So</span> <span m=''770650''>we</span> <span m=''770870''>would</span>
  <span m=''771020''>like</span> <span m=''771230''>to</span> <span m=''771350''>throw</span>
  <span m=''771680''>away</span> <span m=''772430''>lower</span> <span m=''772710''>dimensional</span>
  <span m=''773140''>subspaces</span> <span m=''773740''>of</span> <span m=''773830''>that</span>
  <span m=''774080''>that</span> <span m=''774140''>just</span> <span m=''774330''>make</span>
  <span m=''774510''>our</span> <span m=''774610''>life</span> <span m=''774830''>easier.</span>
  <span m=''775680''>So</span> <span m=''775850''>for</span> <span m=''776020''>example,</span>
  <span m=''778600''>I''d</span> <span m=''778640''>like</span> <span m=''778790''>to</span>
  <span m=''778900''>say</span> <span m=''779290''>no</span> <span m=''779460''>three</span>
  <span m=''779740''>points</span> <span m=''780710''>are</span> <span m=''780810''>co-linear.</span>
  <span m=''785890''>So</span> <span m=''786040''>if</span> <span m=''786100''>I</span>
  <span m=''786180''>take</span> <span m=''786450''>three</span> <span m=''786700''>points</span>
  <span m=''787100''>in</span> <span m=''787170''>the</span> <span m=''787260''>plane,</span>
  <span m=''788060''>it''s</span> <span m=''788220''>pretty</span> <span m=''788440''>unlikely</span>
  <span m=''788850''>they</span> <span m=''789000''>lie</span> <span m=''789210''>on</span>
  <span m=''789300''>a</span> <span m=''789360''>common</span> <span m=''789660''>line.</span>
  <span m=''790930''>It</span> <span m=''791110''>happens</span> <span m=''792070''>with</span>
  <span m=''792230''>probability</span> <span m=''792750''>zero</span> <span m=''793150''>if</span>
  <span m=''793270''>I</span> <span m=''793320''>had</span> <span m=''793480''>random</span>
  <span m=''793780''>points.</span> <span m=''794200''>Even</span> <span m=''794430''>if</span>
  <span m=''794560''>I</span> <span m=''794610''>didn''t</span> <span m=''794790''>have</span>
  <span m=''794990''>random</span> <span m=''795200''>points,</span> <span m=''795490''>I</span>
  <span m=''795540''>just</span> <span m=''795720''>take</span> <span m=''795930''>arbitrary</span>
  <span m=''796350''>points and</span> <span m=''796530''>then perturb</span> <span
  m=''797020''>them</span> <span m=''797200''>a</span> <span m=''797300''>tiny</span>
  <span m=''797620''>bit</span> <span m=''797850''>in</span> <span m=''797940''>a</span>
  <span m=''798030''>random</span> <span m=''798700''>neighborhood--</span> <span
  m=''799270''>little</span> <span m=''799530''>epsilon</span> <span m=''801270''>disk--</span>
  <span m=''802090''>then</span> <span m=''802590''>with</span> <span m=''802760''>probability</span>
  <span m=''803270''>zero,</span> <span m=''803840''>they</span> <span m=''803970''>will</span>
  <span m=''804150''>be</span> <span m=''804300''>aligned.</span> </p><p><span m=''805230''>So</span>
  <span m=''805370''>I</span> <span m=''805400''>can</span> <span m=''805550''>say</span>
  <span m=''805650''>a</span> <span m=''805700''>whole</span> <span m=''805850''>bunch</span>
  <span m=''806080''>of</span> <span m=''806150''>things</span> <span m=''806370''>like</span>
  <span m=''806530''>this,</span> <span m=''807550''>maybe</span> <span m=''807870''>no</span>
  <span m=''808150''>four</span> <span m=''808550''>points</span> <span m=''810200''>con-cyclic,</span>
  <span m=''811180''>which</span> <span m=''811390''>means</span> <span m=''811790''>lies</span>
  <span m=''812110''>in</span> <span m=''812190''>a</span> <span m=''812290''>common</span>
  <span m=''812620''>circle.</span> <span m=''815000''>You know,</span> <span m=''815450''>Latin.</span>
  <span m=''819566''>In</span> <span m=''820360''>3D,</span> <span m=''820850''>you''d</span>
  <span m=''820950''>assume</span> <span m=''821225''>no four</span> <span m=''821500''>points</span>
  <span m=''821810''>are</span> <span m=''821880''>coplanar.</span> <span m=''823000''>All</span>
  <span m=''823150''>these</span> <span m=''823270''>sorts</span> <span m=''823490''>of</span>
  <span m=''823570''>things.</span> <span m=''824220''>In</span> <span m=''824340''>general,</span>
  <span m=''825560''>what</span> <span m=''825820''>we</span> <span m=''826830''>can</span>
  <span m=''827000''>throw</span> <span m=''827280''>away</span> <span m=''828560''>is</span>
  <span m=''828850''>any</span> <span m=''830430''>non-trivial</span> <span m=''833940''>rational</span>
  <span m=''836070''>algebraic--</span> <span m=''837445''>how many</span> <span m=''837910''>adjectives</span>
  <span m=''838410''>can</span> <span m=''838550''>I</span> <span m=''838620''>get</span>
  <span m=''838770''>in</span> <span m=''838880''>here?</span> <span m=''839565''>I</span>
  <span m=''839990''>think</span> <span m=''840160''>that''s</span> <span m=''840360''>all</span>
  <span m=''840530''>of</span> <span m=''840580''>them--</span> <span m=''841460''>equation.</span>
  </p><p><span m=''849230''>You</span> <span m=''849490''>can,</span> <span m=''849940''>for</span>
  <span m=''850010''>example,</span> <span m=''850560''>write</span> <span m=''850760''>the</span>
  <span m=''850830''>fact that</span> <span m=''851220''>three</span> <span m=''851450''>points</span>
  <span m=''851780''>lie in</span> <span m=''852050''>a</span> <span m=''852110''>common</span>
  <span m=''852400''>line</span> <span m=''852740''>as</span> <span m=''852960''>a</span>
  <span m=''853030''>polynomial</span> <span m=''854320''>with</span> <span m=''854610''>integer</span>
  <span m=''855040''>coefficients--</span> <span m=''855880''>or</span> <span m=''855980''>definitely</span>
  <span m=''856290''>rational</span> <span m=''856650''>coefficients.</span> <span
  m=''857780''>And</span> <span m=''857880''>generally, you</span> <span m=''858260''>take</span>
  <span m=''858450''>any</span> <span m=''858620''>polynomial</span> <span m=''859600''>you</span>
  <span m=''859720''>want, it</span> <span m=''860160''>explains</span> <span m=''860550''>some</span>
  <span m=''860820''>geometric</span> <span m=''861260''>property.</span> <span m=''862220''>If
  it</span> <span m=''862320''>has</span> <span m=''862500''>rational</span> <span
  m=''862870''>coefficients,</span> <span m=''864090''>and</span> <span m=''864250''>it''s</span>
  <span m=''864370''>nontrivial,</span> <span m=''865010''>meaning</span> <span m=''865290''>that
  it''s</span> <span m=''865490''>not</span> <span m=''865680''>always</span> <span
  m=''865980''>true--</span> <span m=''867330''>so</span> <span m=''867590''>sometimes</span>
  <span m=''868050''>it''s</span> <span m=''868130''>true,</span> <span m=''868300''>sometimes
  it''s</span> <span m=''868800''>false.</span> <span m=''869210''>That''s</span>
  <span m=''869400''>all</span> <span m=''869480''>I</span> <span m=''869560''>mean</span>
  <span m=''869740''>here--</span> <span m=''871680''>then</span> <span m=''871930''>you</span>
  <span m=''872050''>can</span> <span m=''872180''>just--</span> <span m=''873090''>suppose</span>
  <span m=''873560''>that</span> <span m=''873740''>doesn''t</span> <span m=''873980''>happen.</span>
  </p><p><span m=''875160''>Because</span> <span m=''875990''>if</span> <span m=''876040''>you</span>
  <span m=''876120''>have</span> <span m=''876280''>an</span> <span m=''876340''>equation,</span>
  <span m=''876880''>that</span> <span m=''877060''>describes</span> <span m=''877450''>a</span>
  <span m=''877520''>lower</span> <span m=''877800''>dimensional</span> <span m=''878250''>space.</span>
  <span m=''878630''>You</span> <span m=''878710''>start</span> <span m=''878960''>with</span>
  <span m=''879180''>d</span> <span m=''879370''>times</span> <span m=''879610''>n</span>
  <span m=''879730''>dimensions.</span> <span m=''880320''>If</span> <span m=''880360''>you</span>
  <span m=''880470''>add</span> <span m=''880700''>a</span> <span m=''881050''>constraint</span>
  <span m=''881520''>on</span> <span m=''881830''>the</span> <span m=''882540''>coordinates</span>
  <span m=''883420''>of</span> <span m=''883610''>some</span> <span m=''883870''>vertices--</span>
  <span m=''885080''>over</span> <span m=''885210''>here</span> <span m=''885420''>we</span>
  <span m=''885530''>have</span> <span m=''886970''>all</span> <span m=''887280''>the</span>
  <span m=''887360''>coordinates</span> <span m=''887770''>of</span> <span m=''887840''>all</span>
  <span m=''888000''>the</span> <span m=''888050''>vertices.</span> <span m=''888810''>That''s
  what</span> <span m=''888990''>we''re</span> <span m=''889100''>thinking of.</span>
  <span m=''889500''>You</span> <span m=''889590''>take</span> <span m=''889820''>any</span>
  <span m=''890060''>polynomial</span> <span m=''890560''>over</span> <span m=''890730''>those.</span>
  <span m=''891650''>If that</span> <span m=''891820''>holds,</span> <span m=''892260''>then</span>
  <span m=''892380''>that</span> <span m=''892530''>was</span> <span m=''892690''>degenerate,</span>
  <span m=''893370''>and</span> <span m=''893850''>you</span> <span m=''893980''>can</span>
  <span m=''894110''>throw</span> <span m=''894290''>that</span> <span m=''894450''>away.</span>
  </p><p><span m=''895730''>And it</span> <span m=''895840''>may</span> <span m=''896000''>sound</span>
  <span m=''896300''>weird,</span> <span m=''896500''>because</span> <span m=''896700''>there</span>
  <span m=''896800''>are</span> <span m=''896870''>infinitely</span> <span m=''897310''>many</span>
  <span m=''897560''>of</span> <span m=''897610''>these</span> <span m=''897760''>equations,</span>
  <span m=''899290''>but</span> <span m=''899490''>for</span> <span m=''899590''>the</span>
  <span m=''899640''>mathematicians,</span> <span m=''900190''>they''re</span> <span
  m=''900340''>only</span> <span m=''900580''>countably</span> <span m=''901130''>many.</span>
  <span m=''901960''>So</span> <span m=''902290''>if</span> <span m=''902480''>you</span>
  <span m=''902570''>take</span> <span m=''903370''>these</span> <span m=''903530''>spaces,</span>
  <span m=''904610''>you</span> <span m=''904680''>take</span> <span m=''904860''>a</span>
  <span m=''904890''>whole</span> <span m=''905060''>bunch</span> <span m=''905250''>of</span>
  <span m=''905320''>lower</span> <span m=''905510''>dimensional</span> <span m=''905840''>spaces</span>
  <span m=''906230''>times</span> <span m=''906670''>countable</span> <span m=''907150''>number,</span>
  <span m=''907570''>it''s</span> <span m=''907740''>still</span> <span m=''907960''>lower</span>
  <span m=''908170''>dimensional.</span> <span m=''908990''>And</span> <span m=''909200''>so</span>
  <span m=''909290''>you</span> <span m=''909390''>can</span> <span m=''909490''>afford</span>
  <span m=''909770''>to</span> <span m=''909840''>throw</span> <span m=''910160''>away</span>
  <span m=''910250''>all</span> <span m=''910460''>this</span> <span m=''910560''>stuff.</span>
  </p><p><span m=''910800''>If</span> <span m=''911040''>that</span> <span m=''911200''>doesn''t</span>
  <span m=''911400''>make</span> <span m=''911570''>sense,</span> <span m=''911820''>don''t</span>
  <span m=''911950''>worry</span> <span m=''912110''>about</span> <span m=''912350''>it.</span>
  <span m=''913270''>I</span> <span m=''913390''>will</span> <span m=''913870''>tell</span>
  <span m=''914150''>you</span> <span m=''914320''>various</span> <span m=''914660''>times</span>
  <span m=''914970''>when</span> <span m=''915060''>we''re</span> <span m=''915160''>just</span>
  <span m=''915360''>assuming</span> <span m=''915740''>that</span> <span m=''915860''>we''re</span>
  <span m=''916650''>generic.</span> <span m=''916960''>It''ll</span> <span m=''917270''>seem</span>
  <span m=''917470''>like</span> <span m=''917640''>magic,</span> <span m=''918140''>because</span>
  <span m=''918320''>whenever</span> <span m=''918620''>I</span> <span m=''918650''>get</span>
  <span m=''918770''>into</span> <span m=''918980''>a</span> <span m=''919040''>situation</span>
  <span m=''919480''>I</span> <span m=''919530''>don''t</span> <span m=''919730''>like,</span>
  <span m=''920050''>I''ll just</span> <span m=''920140''>say,</span> <span m=''920330''>oh,</span>
  <span m=''920490''>but</span> <span m=''920590''>that''s</span> <span m=''920790''>not</span>
  <span m=''920930''>generic.</span> <span m=''921330''>And</span> <span m=''921400''>we</span>
  <span m=''921500''>move</span> <span m=''921690''>on.</span> <span m=''922560''>But</span>
  <span m=''922730''>this</span> <span m=''922920''>is</span> <span m=''923040''>the</span>
  <span m=''923130''>formal</span> <span m=''923480''>version</span> <span m=''923870''>that</span>
  <span m=''924790''>makes</span> <span m=''925070''>that</span> <span m=''925270''>safe.</span>
  <span m=''925990''>We''ll</span> <span m=''926130''>see</span> <span m=''926250''>another</span>
  <span m=''926500''>version that''s a</span> <span m=''926900''>little</span> <span
  m=''927100''>more</span> <span m=''927260''>intuitive</span> <span m=''928710''>next</span>
  <span m=''928960''>time.</span> <span m=''929310''>But</span> <span m=''929390''>we</span>
  <span m=''929500''>need</span> <span m=''929690''>other</span> <span m=''929980''>concepts.</span>
  </p><p><span m=''932260''>So</span> <span m=''932330''>this</span> <span m=''932710''>it</span>
  <span m=''933010''>implies</span> <span m=''933730''>that</span> <span m=''934240''>degenerate</span>
  <span m=''934980''>situations</span> <span m=''935650''>are</span> <span m=''935740''>lower</span>
  <span m=''935960''>dimensional.</span> <span m=''940860''>And</span> <span m=''942870''>what</span>
  <span m=''943070''>other</span> <span m=''943320''>good</span> <span m=''943510''>facts</span>
  <span m=''944900''>do we</span> <span m=''945050''>have?</span> <span m=''945420''>So</span>
  <span m=''945640''>lower</span> <span m=''945820''>dimensional</span> <span m=''946230''>means</span>
  <span m=''946470''>this is</span> <span m=''946650''>going</span> <span m=''946770''>to</span>
  <span m=''946820''>happen</span> <span m=''947090''>with</span> <span m=''947170''>probability</span>
  <span m=''947740''>zero,</span> <span m=''948220''>if</span> <span m=''948320''>you</span>
  <span m=''948420''>perturb</span> <span m=''948750''>your</span> <span m=''948860''>vertices</span>
  <span m=''949250''>a</span> <span m=''949310''>little</span> <span m=''949490''>bit.</span>
  </p><p><span m=''954130''>So</span> <span m=''954290''>in</span> <span m=''954370''>particular,</span>
  <span m=''955140''>this</span> <span m=''955380''>scenario--</span> <span m=''956770''>this</span>
  <span m=''957070''>is</span> <span m=''957150''>sort</span> <span m=''957280''>of</span>
  <span m=''957340''>the</span> <span m=''957420''>generic</span> <span m=''957790''>picture,</span>
  <span m=''958410''>where</span> <span m=''958520''>there''s</span> <span m=''958680''>some</span>
  <span m=''958820''>slack</span> <span m=''959180''>here.</span> <span m=''960880''>This</span>
  <span m=''961070''>is</span> <span m=''961190''>extremely</span> <span m=''961680''>rare,</span>
  <span m=''961920''>because</span> <span m=''962110''>in</span> <span m=''962210''>particular,</span>
  <span m=''962570''>we</span> <span m=''962650''>have</span> <span m=''962780''>four</span>
  <span m=''962980''>points</span> <span m=''963280''>co-linear.</span> <span m=''964840''>And</span>
  <span m=''965240''>that''s</span> <span m=''965550''>not</span> <span m=''965680''>going</span>
  <span m=''965770''>to</span> <span m=''965810''>happen</span> <span m=''966100''>in
  a</span> <span m=''966340''>generic</span> <span m=''966700''>situation.</span>
  <span m=''967210''>So</span> <span m=''967340''>we</span> <span m=''967440''>would</span>
  <span m=''967560''>say</span> <span m=''967680''>that</span> <span m=''967830''>this</span>
  <span m=''967990''>graph--</span> <span m=''968690''>a</span> <span m=''969110''>bunch
  of</span> <span m=''969380''>triangles,</span> <span m=''969880''>plus</span> <span
  m=''970650''>these</span> <span m=''970830''>three</span> <span m=''970970''>bars</span>
  <span m=''971320''>connecting</span> <span m=''971690''>the</span> <span m=''971760''>endpoints--</span>
  <span m=''972590''>is</span> <span m=''973320''>generically</span> <span m=''974060''>flexible.</span>
  <span m=''974970''>Most</span> <span m=''975290''>of</span> <span m=''975330''>the</span>
  <span m=''975420''>time,</span> <span m=''976130''>it</span> <span m=''976240''>will</span>
  <span m=''976380''>be</span> <span m=''976500''>flexible.</span> </p><p><span m=''978040''>And</span>
  <span m=''978420''>fun</span> <span m=''978660''>fact</span> <span m=''979170''>is</span>
  <span m=''979400''>that</span> <span m=''980500''>for</span> <span m=''980700''>any</span>
  <span m=''980850''>graph--</span> <span m=''989732''>and</span> <span m=''990230''>this</span>
  <span m=''990420''>is</span> <span m=''990540''>not</span> <span m=''990720''>obvious,</span>
  <span m=''991570''>but</span> <span m=''991700''>it''s</span> <span m=''991840''>true--</span>
  <span m=''993830''>it''s</span> <span m=''993960''>either</span> <span m=''995330''>generically</span>
  <span m=''998460''>rigid</span> <span m=''1003120''>or</span> <span m=''1004080''>generically</span>
  <span m=''1004590''>flexible.</span> <span m=''1014580''>Generically</span> <span
  m=''1015040''>rigid</span> <span m=''1015440''>means</span> <span m=''1016400''>that</span>
  <span m=''1016680''>all</span> <span m=''1017140''>generic</span> <span m=''1018260''>realizations</span>
  <span m=''1018980''>are</span> <span m=''1019340''>rigid.</span> <span m=''1029480''>And</span>
  <span m=''1029730''>generically</span> <span m=''1030170''>flexible</span> <span
  m=''1030670''>means</span> <span m=''1033540''>all</span> <span m=''1033790''>generic</span>
  <span m=''1034579''>realizations</span> <span m=''1036149''>are</span> <span m=''1036609''>flexible.</span>
  <span m=''1037690''>I''m</span> <span m=''1037819''>going</span> <span m=''1037900''>to</span>
  <span m=''1037950''>start</span> <span m=''1038160''>abbreviating,</span> <span
  m=''1038690''>because</span> <span m=''1038890''>these</span> <span m=''1039579''>adjectives</span>
  <span m=''1040160''>get</span> <span m=''1040290''>really</span> <span m=''1040510''>long,</span>
  <span m=''1040950''>especially</span> <span m=''1041310''>with</span> <span m=''1042589''>the</span>
  <span m=''1042800''>adverb</span> <span m=''1043270''>form.</span> </p><p><span
  m=''1045880''>So</span> <span m=''1046900''>when</span> <span m=''1047230''>I</span>
  <span m=''1047339''>said</span> <span m=''1048930''>rigidity</span> <span m=''1049370''>is</span>
  <span m=''1049470''>usually</span> <span m=''1049980''>a</span> <span m=''1050050''>property</span>
  <span m=''1050430''>of</span> <span m=''1050510''>the</span> <span m=''1050590''>graph,</span>
  <span m=''1051420''>this</span> <span m=''1051590''>is</span> <span m=''1051690''>what</span>
  <span m=''1051820''>I</span> <span m=''1051870''>meant.</span> <span m=''1052660''>Either</span>
  <span m=''1053850''>you</span> <span m=''1053940''>take</span> <span m=''1054110''>all</span>
  <span m=''1054270''>the</span> <span m=''1054360''>generic</span> <span m=''1054690''>realizations</span>
  <span m=''1054970''>of</span> <span m=''1055250''>your</span> <span m=''1055420''>graph,</span>
  <span m=''1055730''>and</span> <span m=''1055800''>they''re</span> <span m=''1055920''>either</span>
  <span m=''1056160''>all</span> <span m=''1056360''>rigid</span> <span m=''1056680''>or</span>
  <span m=''1056800''>all</span> <span m=''1056930''>flexible.</span> <span m=''1057430''>There''s</span>
  <span m=''1057580''>going</span> <span m=''1057710''>to</span> <span m=''1057770''>be</span>
  <span m=''1057850''>the</span> <span m=''1057980''>lower</span> <span m=''1058190''>dimensional</span>
  <span m=''1058580''>subsets</span> <span m=''1059020''>where</span> <span m=''1059160''>maybe</span>
  <span m=''1059800''>it''s</span> <span m=''1060070''>the</span> <span m=''1060240''>other</span>
  <span m=''1060370''>way</span> <span m=''1060470''>around.</span> <span m=''1061560''>I''ll</span>
  <span m=''1061650''>give</span> <span m=''1061770''>you</span> <span m=''1061840''>some</span>
  <span m=''1062010''>examples</span> <span m=''1062470''>of</span> <span m=''1062540''>that.</span>
  </p><p><span m=''1066050''>So</span> <span m=''1068100''>here--</span> <span m=''1072962''>what
  the heck did</span> <span m=''1073430''>I</span> <span m=''1073520''>draw?</span>
  <span m=''1074680''>That''s</span> <span m=''1075050''>funny.</span> <span m=''1077180''>One
  of</span> <span m=''1077250''>the</span> <span m=''1077350''>edges</span> <span
  m=''1077660''>moved</span> <span m=''1078000''>on</span> <span m=''1078100''>me.</span>
  <span m=''1080780''>If I</span> <span m=''1080860''>take</span> <span m=''1081090''>a</span>
  <span m=''1081240''>picture</span> <span m=''1081530''>like</span> <span m=''1081700''>this--</span>
  <span m=''1085200''>OK, this</span> <span m=''1085700''>is</span> <span m=''1085810''>flexible,</span>
  <span m=''1086260''>because</span> <span m=''1086470''>I</span> <span m=''1086530''>have</span>
  <span m=''1086770''>a</span> <span m=''1087420''>quadrilateral</span> <span m=''1087980''>here</span>
  <span m=''1088100''>that</span> <span m=''1088210''>can flex</span> <span m=''1088660''>independent</span>
  <span m=''1088970''>of</span> <span m=''1089100''>the</span> <span m=''1089180''>triangles.</span>
  <span m=''1089680''>But</span> <span m=''1089810''>suppose</span> <span m=''1090160''>I</span>
  <span m=''1090260''>add</span> <span m=''1090810''>a</span> <span m=''1091150''>bar</span>
  <span m=''1092180''>between</span> <span m=''1092490''>this</span> <span m=''1092660''>vertex
  and</span> <span m=''1093020''>this</span> <span m=''1093280''>vertex</span> <span
  m=''1093830''>which</span> <span m=''1094050''>somehow</span> <span m=''1094340''>connects</span>
  <span m=''1095130''>the</span> <span m=''1095220''>two</span> <span m=''1095350''>sides</span>
  <span m=''1095670''>of</span> <span m=''1095760''>that</span> <span m=''1095970''>quadrilateral.</span>
  <span m=''1098210''>When</span> <span m=''1098410''>this</span> <span m=''1098680''>special</span>
  <span m=''1099080''>case,</span> <span m=''1100280''>the</span> <span m=''1100380''>way</span>
  <span m=''1100810''>I  drew,</span> <span m=''1101310''>where</span> <span m=''1101410''>these</span>
  <span m=''1101600''>triangles</span> <span m=''1101970''>are</span> <span m=''1102030''>identical</span>
  <span m=''1103070''>and</span> <span m=''1103150''>this</span> <span m=''1103290''>is</span>
  <span m=''1103440''>a</span> <span m=''1103490''>nice</span> <span m=''1103720''>rectangle,</span>
  <span m=''1104690''>this</span> <span m=''1104880''>thing</span> <span m=''1105070''>is</span>
  <span m=''1105180''>flexible.</span> </p><p><span m=''1108420''>You</span> <span
  m=''1108520''>take</span> <span m=''1109050''>this</span> <span m=''1109200''>triangle,</span>
  <span m=''1110450''>and</span> <span m=''1111140''>I</span> <span m=''1111270''>want</span>
  <span m=''1111440''>to</span> <span m=''1111480''>flex</span> <span m=''1111880''>the</span>
  <span m=''1113230''>quad,</span> <span m=''1114290''>so</span> <span m=''1114450''>if</span>
  <span m=''1114580''>I</span> <span m=''1114670''>rotate</span> <span m=''1116460''>the</span>
  <span m=''1116580''>whole</span> <span m=''1116800''>thing</span> <span m=''1117280''>like</span>
  <span m=''1117560''>this--</span> <span m=''1118665''>I</span> <span m=''1119090''>think</span>
  <span m=''1119310''>it</span> <span m=''1119430''>works.</span> <span m=''1123880''>It</span>
  <span m=''1124150''>twists</span> <span m=''1124470''>at</span> <span m=''1124570''>the</span>
  <span m=''1124660''>same</span> <span m=''1124910''>time.</span> <span m=''1126120''>Yeah,
  it''s</span> <span m=''1126360''>a</span> <span m=''1126420''>little</span> <span
  m=''1126600''>hard</span> <span m=''1126800''>to</span> <span m=''1126870''>see.</span>
  <span m=''1127450''>But</span> <span m=''1127610''>because</span> <span m=''1127910''>these</span>
  <span m=''1128100''>guys</span> <span m=''1128280''>are</span> <span m=''1128370''>all</span>
  <span m=''1128460''>parallel,</span> <span m=''1129500''>this</span> <span m=''1129720''>thing</span>
  <span m=''1129960''>can</span> <span m=''1130710''>keep</span> <span m=''1130940''>them</span>
  <span m=''1131100''>all</span> <span m=''1131250''>parallel,</span> <span m=''1132145''>I</span>
  <span m=''1132450''>think,</span> <span m=''1132840''>and</span> <span m=''1133050''>keep</span>
  <span m=''1133230''>all</span> <span m=''1133360''>the</span> <span m=''1133430''>distances</span>
  <span m=''1133860''>the</span> <span m=''1133920''>same.</span> </p><p><span m=''1134210''>AUDIENCE:
  All of them are</span> <span m=''1134651''>parallel</span> <span m=''1135092''>and</span>
  <span m=''1135533''>the same</span> <span m=''1135974''>length?</span> </p><p><span
  m=''1136860''>PROFESSOR: All</span> <span m=''1137040''>parallel</span> <span m=''1137410''>and</span>
  <span m=''1137560''>the</span> <span m=''1137630''>same</span> <span m=''1137850''>length.</span>
  <span m=''1138330''>It''s</span> <span m=''1138460''>necessary</span> <span m=''1138820''>for</span>
  <span m=''1138920''>this</span> <span m=''1139100''>to</span> <span m=''1139200''>work.</span>
  <span m=''1139700''>But you</span> <span m=''1139890''>take</span> <span m=''1140100''>a</span>
  <span m=''1140150''>generic</span> <span m=''1140620''>drawing-- if I</span> <span
  m=''1141050''>perturb</span> <span m=''1141370''>this at</span> <span m=''1141540''>all,</span>
  <span m=''1142360''>it</span> <span m=''1142480''>will</span> <span m=''1142610''>be</span>
  <span m=''1143370''>rigid.</span> <span m=''1144610''>so</span> <span m=''1144800''>this</span>
  <span m=''1145020''>is</span> <span m=''1145310''>rarely</span> <span m=''1145820''>flexible,</span>
  <span m=''1149880''>but</span> <span m=''1150180''>generically</span> <span m=''1151870''>it''s</span>
  <span m=''1152030''>rigid.</span> </p><p><span m=''1154380''>And I</span> <span
  m=''1154620''>have</span> <span m=''1154850''>an</span> <span m=''1154930''>example</span>
  <span m=''1155330''>of</span> <span m=''1155390''>the</span> <span m=''1155480''>reverse.</span>
  <span m=''1167290''>The</span> <span m=''1167510''>way</span> <span m=''1168680''>I''ve</span>
  <span m=''1168880''>drawn</span> <span m=''1169190''>this,</span> <span m=''1169390''>where</span>
  <span m=''1169600''>all</span> <span m=''1169870''>these</span> <span m=''1170100''>guys</span>
  <span m=''1170520''>in</span> <span m=''1170640''>extension</span> <span m=''1171460''>meet</span>
  <span m=''1171700''>up,</span> <span m=''1172600''>and</span> <span m=''1172820''>all</span>
  <span m=''1172970''>these</span> <span m=''1173170''>guys</span> <span m=''1173410''>are</span>
  <span m=''1173490''>parallel,</span> <span m=''1174210''>and</span> <span m=''1174330''>so</span>
  <span m=''1174480''>on,</span> <span m=''1175200''>you</span> <span m=''1175560''>can</span>
  <span m=''1175750''>check--</span> <span m=''1176080''>it''s</span> <span m=''1176240''>a</span>
  <span m=''1176290''>little</span> <span m=''1176490''>hard</span> <span m=''1176840''>to</span>
  <span m=''1176880''>see--</span> <span m=''1178370''>but</span> <span m=''1178570''>it''s</span>
  <span m=''1178730''>rarely</span> <span m=''1180030''>rigid.</span> <span m=''1180660''>In</span>
  <span m=''1180740''>this</span> <span m=''1180920''>case</span> <span m=''1181150''>it''s</span>
  <span m=''1181320''>rigid,</span> <span m=''1183610''>but</span> <span m=''1183740''>generically,</span>
  <span m=''1184270''>it''s</span> <span m=''1184490''>flexible.</span> </p><p><span
  m=''1189380''>I</span> <span m=''1189480''>wouldn''t</span> <span m=''1189700''>take</span>
  <span m=''1189860''>this</span> <span m=''1190030''>on</span> <span m=''1190170''>faith.</span>
  <span m=''1190930''>For</span> <span m=''1191250''>me</span> <span m=''1191400''>to</span>
  <span m=''1191490''>check</span> <span m=''1191770''>this,</span> <span m=''1192410''>I</span>
  <span m=''1192540''>had</span> <span m=''1192740''>to</span> <span m=''1192820''>constructed</span>
  <span m=''1193830''>in</span> <span m=''1194070''>Cinderella,</span> <span m=''1195190''>and</span>
  <span m=''1195340''>then</span> <span m=''1195490''>see</span> <span m=''1195700''>that</span>
  <span m=''1195830''>it</span> <span m=''1195920''>moves.</span> <span m=''1196680''>And</span>
  <span m=''1196930''>when</span> <span m=''1197050''>these</span> <span m=''1197230''>things</span>
  <span m=''1197390''>are</span> <span m=''1197480''>almost</span> <span m=''1197810''>parallel,</span>
  <span m=''1198190''>it</span> <span m=''1198370''>moves</span> <span m=''1198540''>just</span>
  <span m=''1198760''>a</span> <span m=''1198790''>little</span> <span m=''1199010''>bit.</span>
  <span m=''1199450''>And</span> <span m=''1199540''>you</span> <span m=''1199640''>can</span>
  <span m=''1199750''>see</span> <span m=''1199910''>that</span> <span m=''1200040''>in</span>
  <span m=''1200150''>the</span> <span m=''1200240''>limit,</span> <span m=''1200530''>when</span>
  <span m=''1200690''>all</span> <span m=''1200800''>these</span> <span m=''1200980''>things</span>
  <span m=''1201590''>line</span> <span m=''1201830''>up</span> <span m=''1202020''>nicely,</span>
  <span m=''1202610''>it</span> <span m=''1202840''>doesn''t</span> <span m=''1203100''>move</span>
  <span m=''1203290''>at</span> <span m=''1203350''>all.</span> <span m=''1205160''>The</span>
  <span m=''1205550''>point</span> <span m=''1205870''>is that</span> <span m=''1206080''>there
  are</span> <span m=''1206210''>these</span> <span m=''1206420''>exceptions.</span>
  <span m=''1207150''>That''s</span> <span m=''1207340''>all you</span> <span m=''1207560''>need</span>
  <span m=''1207650''>to</span> <span m=''1207760''>believe.</span> </p><p><span m=''1209080''>But</span>
  <span m=''1209520''>most</span> <span m=''1209790''>the</span> <span m=''1209900''>time,</span>
  <span m=''1210720''>we''re</span> <span m=''1210850''>going</span> <span m=''1210950''>to</span>
  <span m=''1211000''>get</span> <span m=''1211170''>the</span> <span m=''1211250''>right</span>
  <span m=''1211410''>answer.</span> <span m=''1212370''>And</span> <span m=''1212470''>so,</span>
  <span m=''1212500''>the</span> <span m=''1212590''>rest of</span> <span m=''1212840''>this</span>
  <span m=''1212960''>class is</span> <span m=''1213370''>about</span> <span m=''1213620''>characterizing</span>
  <span m=''1214160''>when</span> <span m=''1214310''>a</span> <span m=''1214360''>graph</span>
  <span m=''1214690''>is</span> <span m=''1214830''>generically</span> <span m=''1215260''>rigid</span>
  <span m=''1215660''>or</span> <span m=''1215870''>generically</span> <span m=''1216250''>flexible.</span>
  <span m=''1216620''>It''s</span> <span m=''1216730''>a</span> <span m=''1216770''>nice</span>
  <span m=''1217040''>problem,</span> <span m=''1217460''>because</span> <span m=''1217750''>it</span>
  <span m=''1217880''>just</span> <span m=''1218110''>depends</span> <span m=''1218450''>on</span>
  <span m=''1218500''>the</span> <span m=''1218600''>combinatorial</span> <span m=''1219150''>structure,</span>
  <span m=''1220120''>but</span> <span m=''1220320''>occasionally,</span> <span m=''1220600''>it</span>
  <span m=''1220880''>will</span> <span m=''1221060''>give</span> <span m=''1221190''>the</span>
  <span m=''1221280''>wrong</span> <span m=''1221500''>answer.</span> <span m=''1221790''>If</span>
  <span m=''1221880''>you''ve</span> <span m=''1222050''>set</span> <span m=''1222370''>things</span>
  <span m=''1222600''>up</span> <span m=''1222780''>with</span> <span m=''1222890''>very</span>
  <span m=''1223130''>special</span> <span m=''1223480''>geometry,</span> <span m=''1224590''>it</span>
  <span m=''1224730''>might</span> <span m=''1224920''>be the</span> <span m=''1225110''>other</span>
  <span m=''1225230''>way</span> <span m=''1225360''>around.</span> <span m=''1225990''>Question?</span>
  </p><p><span m=''1226440''>AUDIENCE: Is it</span> <span m=''1226938''>fair</span>
  <span m=''1227436''>to think</span> <span m=''1228432''>the</span> <span m=''1229428''>rigidity</span>
  <span m=''1229926''>is happening</span> <span m=''1230424''>right</span> <span m=''1230922''>before</span>
  <span m=''1231918''>it no longer</span> <span m=''1232416''>works?</span> </p><p><span
  m=''1233420''>PROFESSOR: Yeah.</span> <span m=''1234270''>Right.</span> <span m=''1235710''>The</span>
  <span m=''1235810''>rigidity is</span> <span m=''1236300''>kind</span> <span m=''1236460''>of</span>
  <span m=''1236530''>happening</span> <span m=''1236880''>right</span> <span m=''1237080''>before</span>
  <span m=''1237460''>it</span> <span m=''1237550''>breaks.</span> <span m=''1237920''>In</span>
  <span m=''1238000''>some</span> <span m=''1238190''>sense,</span> <span m=''1238890''>there</span>
  <span m=''1239090''>is</span> <span m=''1239200''>a</span> <span m=''1239260''>nontrivial</span>
  <span m=''1239750''>motion</span> <span m=''1240060''>there, it</span> <span m=''1240200''>just</span>
  <span m=''1240420''>happens</span> <span m=''1240700''>to</span> <span m=''1240780''>be</span>
  <span m=''1240890''>super</span> <span m=''1241190''>short.</span> <span m=''1242740''>It''s</span>
  <span m=''1243230''>hard</span> <span m=''1243470''>to</span> <span m=''1243560''>define</span>
  <span m=''1243920''>that</span> <span m=''1244120''>formally,</span> <span m=''1244560''>but</span>
  <span m=''1244720''>intuitively,</span> <span m=''1245190''>that''s</span> <span
  m=''1245400''>what''s</span> <span m=''1245530''>happening.</span> <span m=''1246580''>And</span>
  <span m=''1247310''>you</span> <span m=''1247510''>can</span> <span m=''1247640''>think</span>
  <span m=''1247840''>of</span> <span m=''1247940''>this</span> <span m=''1248260''>thing</span>
  <span m=''1248470''>as</span> <span m=''1248600''>being</span> <span m=''1249380''>a</span>
  <span m=''1249440''>little</span> <span m=''1249740''>bit</span> <span m=''1249920''>wobbly,</span>
  <span m=''1251710''>but</span> <span m=''1251960''>not</span> <span m=''1252240''>technically</span>
  <span m=''1252690''>flexible.</span> <span m=''1253910''>There''s</span> <span m=''1254140''>actually
  a</span> <span m=''1254410''>formal</span> <span m=''1254690''>notion of</span>
  <span m=''1254980''>wobbly</span> <span m=''1255720''>in</span> <span m=''1255850''>the</span>
  <span m=''1255930''>rigidity</span> <span m=''1256470''>literature,</span> <span
  m=''1259070''>which</span> <span m=''1259350''>we</span> <span m=''1259480''>probably</span>
  <span m=''1259760''>will</span> <span m=''1259870''>talk</span> <span m=''1260080''>about</span>
  <span m=''1260260''>next</span> <span m=''1260470''>class.</span> <span m=''1262540''>Would</span>
  <span m=''1262690''>this</span> <span m=''1262860''>be</span> <span m=''1262980''>wobbly?</span>
  <span m=''1264010''>Probably.</span> <span m=''1264630''>I''d</span> <span m=''1264830''>have</span>
  <span m=''1265070''>to</span> <span m=''1265170''>think</span> <span m=''1265320''>about</span>
  <span m=''1265590''>it.</span> <span m=''1267320''>Wobbly</span> <span m=''1267780''>is</span>
  <span m=''1267900''>a</span> <span m=''1267960''>computable</span> <span m=''1268420''>notion.</span>
  <span m=''1268910''>It''s</span> <span m=''1269220''>nice.</span> </p><p><span m=''1270510''>So</span>
  <span m=''1270680''>rigidity</span> <span m=''1271190''>theory</span> <span m=''1271320''>is</span>
  <span m=''1271410''>actually</span> <span m=''1271710''>pretty</span> <span m=''1271970''>old.</span>
  <span m=''1272900''>In</span> <span m=''1273100''>the</span> <span m=''1274150''>mechanical,</span>
  <span m=''1274960''>structural</span> <span m=''1275290''>engineering</span> <span
  m=''1275750''>worlds,</span> <span m=''1276150''>it</span> <span m=''1276230''>goes</span>
  <span m=''1276430''>back</span> <span m=''1276640''>to</span> <span m=''1278050''>Cremona</span>
  <span m=''1278650''>In</span> <span m=''1278740''>the</span> <span m=''1278890''>17th,</span>
  <span m=''1279650''>18th</span> <span m=''1279870''>century.</span> <span m=''1281910''>The</span>
  <span m=''1282060''>mathematics</span> <span m=''1282640''>even</span> <span m=''1282850''>is</span>
  <span m=''1282970''>pretty</span> <span m=''1283190''>old.</span> <span m=''1283390''>The</span>
  <span m=''1286400''>next</span> <span m=''1286620''>big</span> <span m=''1286760''>theorem</span>
  <span m=''1287020''>we''ll</span> <span m=''1287110''>talk</span> <span m=''1287320''>about</span>
  <span m=''1287450''>is</span> <span m=''1287530''>from</span> <span m=''1287650''>1911.</span>
  <span m=''1288520''>It''s</span> <span m=''1288650''>probably</span> <span m=''1288910''>one</span>
  <span m=''1289030''>of</span> <span m=''1289070''>the</span> <span m=''1289140''>earliest</span>
  <span m=''1289850''>formal</span> <span m=''1290210''>mathematical</span> <span
  m=''1291470''>treatments,</span> <span m=''1292990''>and it</span> <span m=''1293220''>started</span>
  <span m=''1293590''>to</span> <span m=''1293690''>address</span> <span m=''1294000''>exactly</span>
  <span m=''1294420''>this</span> <span m=''1294740''>issue.</span> <span m=''1295280''>In</span>
  <span m=''1295430''>two</span> <span m=''1295550''>dimensions,</span> <span m=''1296140''>which</span>
  <span m=''1296400''>graphs are</span> <span m=''1296680''>rigid,</span> <span m=''1297050''>which</span>
  <span m=''1297240''>are</span> <span m=''1297300''>flexible</span> <span m=''1297760''>in</span>
  <span m=''1297840''>the</span> <span m=''1297930''>generic</span> <span m=''1298270''>sense?</span>
  <span m=''1300420''>It''s</span> <span m=''1301090''>become</span> <span m=''1301480''>pretty</span>
  <span m=''1302330''>popular</span> <span m=''1302740''>and</span> <span m=''1302800''>interesting
  in the</span> <span m=''1303210''>last</span> <span m=''1304610''>10,</span> <span
  m=''1304970''>20</span> <span m=''1305210''>years,</span> <span m=''1306010''>and</span>
  <span m=''1308360''>a</span> <span m=''1309130''>lot</span> <span m=''1309270''>more</span>
  <span m=''1309450''>action--</span> <span m=''1309730''>a</span> <span m=''1309770''>lot</span>
  <span m=''1309910''>more</span> <span m=''1310060''>theorems</span> <span m=''1310400''>and</span>
  <span m=''1310940''>whatnot.</span> </p><p><span m=''1311400''>Today</span> <span
  m=''1311630''>we''re</span> <span m=''1311740''>going</span> <span m=''1311820''>to</span>
  <span m=''1311880''>talk</span> <span m=''1312100''>mostly</span> <span m=''1312380''>about</span>
  <span m=''1314510''>old</span> <span m=''1314710''>things.</span> <span m=''1315560''>Next</span>
  <span m=''1315760''>class</span> <span m=''1315980''>we''ll</span> <span m=''1316090''>do</span>
  <span m=''1316200''>some</span> <span m=''1316420''>newer</span> <span m=''1316650''>things</span>
  <span m=''1318040''>in</span> <span m=''1318200''>the</span> <span m=''1318290''>rigidity</span>
  <span m=''1318700''>world.</span> <span m=''1319630''>I</span> <span m=''1319790''>got</span>
  <span m=''1319980''>interested</span> <span m=''1320400''>in rigidity</span> <span
  m=''1320930''>because</span> <span m=''1321420''>it</span> <span m=''1321540''>turned</span>
  <span m=''1321750''>out</span> <span m=''1321870''>to</span> <span m=''1321970''>be</span>
  <span m=''1322060''>really</span> <span m=''1322240''>important</span> <span m=''1323280''>for</span>
  <span m=''1323560''>folding</span> <span m=''1323910''>linkages.</span> <span m=''1325790''>Not</span>
  <span m=''1326040''>just</span> <span m=''1326290''>telling</span> <span m=''1326550''>whether
  a</span> <span m=''1326780''>linkage is</span> <span m=''1327170''>rigid,</span>
  <span m=''1327560''>which</span> <span m=''1327760''>is</span> <span m=''1327880''>important</span>
  <span m=''1328360''>for</span> <span m=''1328510''>things</span> <span m=''1328870''>like</span>
  <span m=''1329060''>building</span> <span m=''1329380''>rigid</span> <span m=''1329620''>structures,</span>
  <span m=''1331170''>but</span> <span m=''1331410''>for</span> <span m=''1331760''>actually</span>
  <span m=''1332100''>folding</span> <span m=''1332530''>things</span> <span m=''1333100''>and</span>
  <span m=''1333270''>showing</span> <span m=''1333820''>that</span> <span m=''1334230''>you</span>
  <span m=''1334460''>can</span> <span m=''1334610''>fold</span> <span m=''1334920''>the</span>
  <span m=''1334980''>linkage</span> <span m=''1335310''>from</span> <span m=''1335610''>any</span>
  <span m=''1335790''>configuration</span> <span m=''1336370''>to</span> <span m=''1336450''>any</span>
  <span m=''1336710''>other.</span> </p><p><span m=''1337390''>Turns</span> <span
  m=''1337680''>out</span> <span m=''1338110''>rigidity</span> <span m=''1338370''>is</span>
  <span m=''1338630''>really</span> <span m=''1338830''>useful</span> <span m=''1339130''>for</span>
  <span m=''1339240''>that.</span> <span m=''1340410''>And</span> <span m=''1340540''>that''s</span>
  <span m=''1340740''>not at</span> <span m=''1340950''>all</span> <span m=''1341170''>obvious.</span>
  <span m=''1342730''>It''s</span> <span m=''1342860''>kind</span> <span m=''1343010''>of</span>
  <span m=''1343090''>a</span> <span m=''1343150''>surprise,</span> <span m=''1343680''>and
  a</span> <span m=''1343800''>fun</span> <span m=''1343990''>surprise.</span> <span
  m=''1346680''>We''ll</span> <span m=''1346860''>be</span> <span m=''1347030''>talking</span>
  <span m=''1347260''>about</span> <span m=''1347420''>that</span> <span m=''1347560''>next</span>
  <span m=''1347780''>class.</span> <span m=''1348360''>Today,</span> <span m=''1348650''>sort
  of</span> <span m=''1348970''>classic</span> <span m=''1349400''>stuff--</span>
  <span m=''1350160''>understanding</span> <span m=''1350860''>when</span> <span m=''1351920''>2D</span>
  <span m=''1352140''>graphs</span> <span m=''1352500''>are</span> <span m=''1352570''>rigid.</span>
  <span m=''1353820''>I''ll</span> <span m=''1353980''>give</span> <span m=''1354110''>you</span>
  <span m=''1354200''>an</span> <span m=''1354280''>idea</span> <span m=''1354530''>why</span>
  <span m=''1354670''>3D</span> <span m=''1354970''>is</span> <span m=''1355090''>much</span>
  <span m=''1355280''>harder.</span> </p><p><span m=''1358300''>OK,</span> <span m=''1358630''>we</span>
  <span m=''1358740''>need</span> <span m=''1358910''>one</span> <span m=''1359070''>more</span>
  <span m=''1359810''>notion.</span> <span m=''1362270''>This is a</span> <span m=''1362480''>real</span>
  <span m=''1362960''>long-winded</span> <span m=''1364070''>thing--</span> <span
  m=''1364960''>minimally</span> <span m=''1366160''>generically</span> <span m=''1369510''>rigid</span>
  <span m=''1371956''>graph.</span> <span m=''1375350''>So</span> <span m=''1375530''>the</span>
  <span m=''1375630''>new</span> <span m=''1375760''>addition</span> <span m=''1376060''>here
  is</span> <span m=''1376300''>minimally.</span> <span m=''1377230''>This</span>
  <span m=''1377410''>is</span> <span m=''1377550''>going</span> <span m=''1377690''>to</span>
  <span m=''1377780''>be</span> <span m=''1378180''>some</span> <span m=''1378610''>generically</span>
  <span m=''1379680''>rigid</span> <span m=''1380020''>graph,</span> <span m=''1384710''>and</span>
  <span m=''1385010''>it</span> <span m=''1385090''>also</span> <span m=''1385370''>has</span>
  <span m=''1385570''>the</span> <span m=''1385660''>property</span> <span m=''1386170''>that</span>
  <span m=''1386390''>removing</span> <span m=''1386880''>any</span> <span m=''1387090''>edge</span>
  <span m=''1391060''>makes</span> <span m=''1391440''>the</span> <span m=''1391560''>graph</span>
  <span m=''1392490''>generically</span> <span m=''1392930''>flexible.</span> <span
  m=''1399270''>So</span> <span m=''1399400''>it''s</span> <span m=''1399520''>minimal</span>
  <span m=''1400020''>in</span> <span m=''1400080''>the</span> <span m=''1400170''>sense
  that</span> <span m=''1400460''>I</span> <span m=''1400530''>can''t</span> <span
  m=''1400940''>get</span> <span m=''1401080''>rid</span> <span m=''1401220''>of</span>
  <span m=''1401310''>any</span> <span m=''1401490''>edges</span> <span m=''1401810''>and</span>
  <span m=''1401910''>still</span> <span m=''1402140''>be</span> <span m=''1402270''>generically</span>
  <span m=''1402760''>rigid.</span> </p><p><span m=''1404550''>So</span> <span m=''1404790''>the</span>
  <span m=''1404930''>idea</span> <span m=''1405260''>is,</span> <span m=''1405640''>let''s</span>
  <span m=''1405960''>characterize</span> <span m=''1406640''>minimally</span> <span
  m=''1407120''>generically</span> <span m=''1407580''>rigid</span> <span m=''1407810''>graphs.</span>
  <span m=''1408150''>If</span> <span m=''1408260''>I</span> <span m=''1408310''>can</span>
  <span m=''1408430''>characterize</span> <span m=''1408850''>those,</span> <span
  m=''1409850''>then</span> <span m=''1410010''>the</span> <span m=''1410090''>generically</span>
  <span m=''1410500''>rigid</span> <span m=''1410750''>ones</span> <span m=''1411020''>are</span>
  <span m=''1411090''>just</span> <span m=''1411550''>those</span> <span m=''1411870''>plus</span>
  <span m=''1412120''>some</span> <span m=''1412230''>more</span> <span m=''1412440''>edges.</span>
  <span m=''1412860''>You</span> <span m=''1412940''>could</span> <span m=''1413070''>throw</span>
  <span m=''1413240''>in</span> <span m=''1413320''>extra</span> <span m=''1413570''>edges--</span>
  <span m=''1414090''>it</span> <span m=''1414240''>only</span> <span m=''1414420''>makes</span>
  <span m=''1414630''>things</span> <span m=''1414810''>more</span> <span m=''1415040''>rigid.</span>
  <span m=''1415340''>It''s</span> <span m=''1415460''>more</span> <span m=''1415660''>constraints.</span>
  <span m=''1417030''>But</span> <span m=''1417410''>I''m</span> <span m=''1417530''>really</span>
  <span m=''1417770''>interested</span> <span m=''1418200''>in</span> <span m=''1418500''>the</span>
  <span m=''1419140''>boundary</span> <span m=''1419560''>between</span> <span m=''1420140''>generically</span>
  <span m=''1420540''>region and</span> <span m=''1420890''>generically</span> <span
  m=''1421310''>flexible,</span> <span m=''1422180''>and</span> <span m=''1422380''>this</span>
  <span m=''1422570''>is</span> <span m=''1422710''>exactly</span> <span m=''1423090''>the</span>
  <span m=''1423200''>boundary</span> <span m=''1423680''>on</span> <span m=''1423900''>the</span>
  <span m=''1424020''>rigid</span> <span m=''1424310''>side--</span> <span m=''1424740''>just</span>
  <span m=''1424970''>barely</span> <span m=''1425320''>rigid.</span> </p><p><span
  m=''1428980''>So</span> <span m=''1429350''>first</span> <span m=''1429670''>thing--</span>
  <span m=''1433290''>if</span> <span m=''1433450''>you''ve</span> <span m=''1433560''>done</span>
  <span m=''1433720''>structural</span> <span m=''1434200''>engineering,</span> <span
  m=''1435320''>this</span> <span m=''1435500''>will</span> <span m=''1435730''>start</span>
  <span m=''1435970''>to</span> <span m=''1436050''>look</span> <span m=''1436200''>familiar--</span>
  <span m=''1439810''>is</span> <span m=''1440000''>how</span> <span m=''1440260''>many</span>
  <span m=''1440540''>edges</span> <span m=''1441150''>should</span> <span m=''1441370''>a</span>
  <span m=''1441750''>minimally</span> <span m=''1442370''>generically</span> <span
  m=''1443290''>rigid</span> <span m=''1443950''>graph</span> <span m=''1444440''>have?</span>
  <span m=''1445300''>And</span> <span m=''1445410''>we</span> <span m=''1445490''>can</span>
  <span m=''1445630''>think</span> <span m=''1445830''>of</span> <span m=''1445920''>this</span>
  <span m=''1446120''>in</span> <span m=''1446220''>a</span> <span m=''1446270''>very</span>
  <span m=''1446520''>intuitive</span> <span m=''1446950''>way,</span> <span m=''1448610''>which</span>
  <span m=''1448980''>is--</span> <span m=''1451410''>let''s</span> <span m=''1451590''>see.</span>
  <span m=''1451870''>If</span> <span m=''1452060''>I</span> <span m=''1452130''>don''t</span>
  <span m=''1452300''>have</span> <span m=''1452420''>any</span> <span m=''1452700''>edges,</span>
  <span m=''1454340''>every</span> <span m=''1454630''>vertex</span> <span m=''1455120''>can</span>
  <span m=''1455250''>float</span> <span m=''1455500''>around</span> <span m=''1456350''>separately.</span>
  </p><p><span m=''1456940''>So</span> <span m=''1457130''>the</span> <span m=''1457190''>number</span>
  <span m=''1457480''>of</span> <span m=''1457530''>degrees</span> <span m=''1457850''>of</span>
  <span m=''1457940''>freedom--</span> <span m=''1458310''>the</span> <span m=''1458430''>dimensionality</span>
  <span m=''1459260''>of</span> <span m=''1459330''>my</span> <span m=''1460480''>realization</span>
  <span m=''1461270''>space,</span> <span m=''1461740''>in</span> <span m=''1461840''>fact--</span>
  <span m=''1462660''>is</span> <span m=''1463170''>in</span> <span m=''1463360''>two</span>
  <span m=''1463510''>dimensions</span> <span m=''1464450''>two</span> <span m=''1464630''>times</span>
  <span m=''1464980''>m.</span> <span m=''1465250''>I''m</span> <span m=''1465300''>going</span>
  <span m=''1465410''>to</span> <span m=''1465480''>do</span> <span m=''1465640''>to</span>
  <span m=''1465820''>2D</span> <span m=''1466740''>first.</span> <span m=''1468090''>Every</span>
  <span m=''1468330''>vertex</span> <span m=''1468730''>has</span> <span m=''1468890''>two</span>
  <span m=''1469040''>degrees</span> <span m=''1469320''>of</span> <span m=''1469420''>freedom.</span>
  <span m=''1471410''>Now</span> <span m=''1471470''>I</span> <span m=''1471600''>would</span>
  <span m=''1471750''>like</span> <span m=''1471960''>to</span> <span m=''1472110''>reduce</span>
  <span m=''1472520''>the</span> <span m=''1472600''>number</span> <span m=''1472830''>of</span>
  <span m=''1472890''>degrees</span> <span m=''1473200''>of</span> <span m=''1473280''>freedom</span>
  <span m=''1473690''>to</span> <span m=''1474770''>what</span> <span m=''1475010''>number?</span>
  </p><p><span m=''1478240''>AUDIENCE: Zero.</span> </p><p><span m=''1479190''>PROFESSOR:
  Zero.</span> <span m=''1479960''>It''s</span> <span m=''1480130''>often</span> <span
  m=''1480460''>a</span> <span m=''1480510''>good</span> <span m=''1480670''>answer,</span>
  <span m=''1481040''>but</span> <span m=''1481330''>sadly</span> <span m=''1481700''>not</span>
  <span m=''1482020''>the</span> <span m=''1482120''>right</span> <span m=''1482340''>one</span>
  <span m=''1482470''>here.</span> </p><p><span m=''1483173''>AUDIENCE: Two.</span>
  </p><p><span m=''1483880''>PROFESSOR: Two.</span> <span m=''1484470''>Close.</span>
  </p><p><span m=''1485940''>AUDIENCE: Three.</span> </p><p><span m=''1486720''>PROFESSOR:
  Three.</span> <span m=''1487560''>Right</span> <span m=''1487600''>guess.</span>
  <span m=''1488780''>We''ll</span> <span m=''1488880''>just</span> <span m=''1489030''>keep</span>
  <span m=''1489180''>trying</span> <span m=''1489500''>all</span> <span m=''1489650''>the</span>
  <span m=''1489740''>integers.</span> </p><p><span m=''1492860''>I</span> <span m=''1492990''>mentioned</span>
  <span m=''1493310''>this</span> <span m=''1493460''>at</span> <span m=''1493510''>the</span>
  <span m=''1493590''>very</span> <span m=''1493820''>beginning</span> <span m=''1494300''>that</span>
  <span m=''1494450''>if</span> <span m=''1495180''>the</span> <span m=''1495330''>best</span>
  <span m=''1495680''>we</span> <span m=''1495780''>could</span> <span m=''1495900''>hope</span>
  <span m=''1496130''>for</span> <span m=''1496380''>is</span> <span m=''1496480''>that</span>
  <span m=''1496580''>there</span> <span m=''1496700''>are</span> <span m=''1496740''>three</span>
  <span m=''1496990''>degrees</span> <span m=''1497290''>of</span> <span m=''1497370''>freedom,</span>
  <span m=''1497680''>we''ll</span> <span m=''1497820''>never</span> <span m=''1498130''>be</span>
  <span m=''1498240''>able</span> <span m=''1498390''>to</span> <span m=''1498440''>get</span>
  <span m=''1498590''>rid</span> <span m=''1498710''>of</span> <span m=''1498830''>the</span>
  <span m=''1498930''>two</span> <span m=''1499100''>translation</span> <span m=''1499700''>degrees</span>
  <span m=''1500490''>and</span> <span m=''1500660''>the</span> <span m=''1500740''>one</span>
  <span m=''1500920''>rotation</span> <span m=''1501380''>degree</span> <span m=''1501710''>in</span>
  <span m=''1501820''>two</span> <span m=''1501960''>dimensions.</span> <span m=''1503030''>In</span>
  <span m=''1503160''>general,</span> <span m=''1504180''>it</span> <span m=''1504340''>is</span>
  <span m=''1505590''>d</span> <span m=''1505810''>times</span> <span m=''1506120''>d</span>
  <span m=''1506260''>plus</span> <span m=''1506540''>1</span> <span m=''1506790''>over</span>
  <span m=''1506990''>2</span> <span m=''1507370''>is</span> <span m=''1507510''>the</span>
  <span m=''1507610''>number</span> <span m=''1507900''>of</span> <span m=''1507960''>dimensions</span>
  <span m=''1509150''>of</span> <span m=''1509480''>rigid</span> <span m=''1509780''>motions</span>
  <span m=''1510490''>in d</span> <span m=''1510780''>dimensions.</span> </p><p><span
  m=''1512130''>And</span> <span m=''1512390''>here</span> <span m=''1512570''>we</span>
  <span m=''1512760''>start</span> <span m=''1513030''>with</span> <span m=''1513140''>dn.</span>
  <span m=''1514750''>So</span> <span m=''1514870''>that''s</span> <span m=''1515020''>in
  d</span> <span m=''1515280''>dimensions.</span> <span m=''1517220''>This</span>
  <span m=''1517430''>is</span> <span m=''1517550''>really</span> <span m=''1517800''>how</span>
  <span m=''1517970''>many</span> <span m=''1518230''>edges</span> <span m=''1518510''>you</span>
  <span m=''1518640''>should</span> <span m=''1518910''>have,</span> <span m=''1519560''>because</span>
  <span m=''1520400''>if</span> <span m=''1520560''>I</span> <span m=''1520620''>have</span>
  <span m=''1520810''>exactly</span> <span m=''1521220''>2n</span> <span m=''1521470''>minus</span>
  <span m=''1521730''>3</span> <span m=''1521920''>edges,</span> <span m=''1523150''>I</span>
  <span m=''1523260''>will</span> <span m=''1523450''>have</span> <span m=''1523710''>started</span>
  <span m=''1524080''>with</span> <span m=''1524200''>2n</span> <span m=''1524500''>degrees</span>
  <span m=''1524800''>of</span> <span m=''1524880''>freedom.</span> <span m=''1525400''>Every</span>
  <span m=''1526320''>edge</span> <span m=''1526570''>that</span> <span m=''1526700''>I</span>
  <span m=''1526750''>add</span> <span m=''1527060''>is</span> <span m=''1527200''>one</span>
  <span m=''1527540''>equation,</span> <span m=''1528230''>so it</span> <span m=''1528360''>should</span>
  <span m=''1528600''>reduce</span> <span m=''1528870''>my</span> <span m=''1528980''>dimension</span>
  <span m=''1529390''>by</span> <span m=''1529520''>one</span> <span m=''1530660''>in</span>
  <span m=''1530800''>the</span> <span m=''1530900''>generic</span> <span m=''1531340''>sense--</span>
  <span m=''1532240''>it''s a</span> <span m=''1532350''>generic</span> <span m=''1532730''>case--</span>
  <span m=''1533580''>and</span> <span m=''1534320''>the</span> <span m=''1534450''>best</span>
  <span m=''1534740''>I</span> <span m=''1534780''>can</span> <span m=''1534910''>hope</span>
  <span m=''1535050''>for</span> <span m=''1535180''>is</span> <span m=''1535250''>to</span>
  <span m=''1535320''>get</span> <span m=''1535470''>down</span> <span m=''1535630''>to</span>
  <span m=''1535710''>three.</span> <span m=''1535920''>If</span> <span m=''1536010''>you</span>
  <span m=''1536110''>put</span> <span m=''1536270''>in</span> <span m=''1536360''>more</span>
  <span m=''1536570''>edges,</span> <span m=''1537020''>you</span> <span m=''1537140''>won''t</span>
  <span m=''1537280''>get</span> <span m=''1537410''>any</span> <span m=''1537540''>more</span>
  <span m=''1537750''>rigid.</span> <span m=''1538310''>I</span> <span m=''1538390''>mean,</span>
  <span m=''1538520''>you''ll</span> <span m=''1539550''>still</span> <span m=''1539710''>be</span>
  <span m=''1539830''>rigid,</span> <span m=''1540320''>but</span> <span m=''1540490''>if</span>
  <span m=''1540630''>I</span> <span m=''1540680''>want</span> <span m=''1540860''>the</span>
  <span m=''1540950''>minimal</span> <span m=''1541280''>case,</span> <span m=''1541580''>this</span>
  <span m=''1541760''>is</span> <span m=''1541900''>really</span> <span m=''1542080''>the</span>
  <span m=''1542180''>best</span> <span m=''1542910''>I should</span> <span m=''1543200''>hope</span>
  <span m=''1543370''>for.</span> </p><p><span m=''1544020''>And</span> <span m=''1544260''>this</span>
  <span m=''1544840''>is</span> <span m=''1544940''>just</span> <span m=''1545130''>a</span>
  <span m=''1545190''>rough</span> <span m=''1545360''>sketch.</span> <span m=''1545900''>This
  is</span> <span m=''1546360''>proved</span> <span m=''1546980''>more</span> <span
  m=''1547160''>formally</span> <span m=''1547510''>in</span> <span m=''1547570''>the</span>
  <span m=''1547650''>notes</span> <span m=''1547940''>here,</span> <span m=''1548530''>but</span>
  <span m=''1548700''>this</span> <span m=''1548860''>really</span> <span m=''1549070''>is</span>
  <span m=''1549190''>a</span> <span m=''1549260''>formal</span> <span m=''1549630''>thing.</span>
  </p><p><span m=''1551140''>Again,</span> <span m=''1551350''>if</span> <span m=''1551430''>you</span>
  <span m=''1551480''>take</span> <span m=''1551700''>some</span> <span m=''1551830''>polynomial</span>
  <span m=''1552320''>equation,</span> <span m=''1553800''>most</span> <span m=''1554140''>of</span>
  <span m=''1554200''>the</span> <span m=''1554300''>time</span> <span m=''1555990''>it''s</span>
  <span m=''1556240''>going</span> <span m=''1556480''>to</span> <span m=''1556610''>define</span>
  <span m=''1557160''>a</span> <span m=''1557670''>space</span> <span m=''1558120''>that</span>
  <span m=''1558230''>is</span> <span m=''1558330''>one</span> <span m=''1558560''>dimension</span>
  <span m=''1558960''>lower.</span> <span m=''1560370''>So</span> <span m=''1560580''>in</span>
  <span m=''1560640''>the</span> <span m=''1560740''>generic</span> <span m=''1561080''>situation,</span>
  <span m=''1562530''>every</span> <span m=''1562870''>equation</span> <span m=''1563220''>you</span>
  <span m=''1563340''>add</span> <span m=''1563610''>will</span> <span m=''1563800''>remove</span>
  <span m=''1564170''>exactly</span> <span m=''1564550''>one</span> <span m=''1564730''>degree
  of</span> <span m=''1565000''>freedom.</span> </p><p><span m=''1566140''>There</span>
  <span m=''1566290''>are</span> <span m=''1566500''>rare</span> <span m=''1566720''>scenarios</span>
  <span m=''1567260''>where</span> <span m=''1567380''>it</span> <span m=''1567430''>doesn''t</span>
  <span m=''1567680''>remove</span> <span m=''1567910''>any,</span> <span m=''1568270''>and</span>
  <span m=''1568580''>they''re</span> <span m=''1568770''>rare</span> <span m=''1568950''>scenarios</span>
  <span m=''1569380''>where</span> <span m=''1569540''>it</span> <span m=''1569820''>removes</span>
  <span m=''1570140''>more</span> <span m=''1570350''>than</span> <span m=''1570480''>one,</span>
  <span m=''1571490''>and</span> <span m=''1571770''>I have</span> <span m=''1572050''>some</span>
  <span m=''1572220''>pictures</span> <span m=''1572590''>of</span> <span m=''1572680''>them</span>
  <span m=''1572790''>here.</span> <span m=''1573050''>But</span> <span m=''1573670''>most
  of</span> <span m=''1573900''>the</span> <span m=''1573970''>time,</span> <span
  m=''1574400''>this</span> <span m=''1574540''>is</span> <span m=''1574640''>right.</span>
  <span m=''1576010''>And</span> <span m=''1576220''>we</span> <span m=''1576370''>are</span>
  <span m=''1576480''>in</span> <span m=''1576570''>the</span> <span m=''1576650''>generic</span>
  <span m=''1576970''>case,</span> <span m=''1577300''>so</span> <span m=''1577410''>most</span>
  <span m=''1577630''>the</span> <span m=''1577730''>time</span> <span m=''1577930''>is</span>
  <span m=''1578020''>all</span> <span m=''1578150''>we</span> <span m=''1578250''>need.</span>
  <span m=''1580450''>So</span> <span m=''1580540''>this</span> <span m=''1580750''>gives</span>
  <span m=''1580940''>us</span> <span m=''1581060''>an</span> <span m=''1581170''>idea.</span>
  </p><p><span m=''1582000''>And</span> <span m=''1583800''>about how</span> <span
  m=''1583910''>many</span> <span m=''1584050''>people have heard</span> <span m=''1584300''>of</span>
  <span m=''1584490''>2n</span> <span m=''1584800''>minus</span> <span m=''1585040''>3</span>
  <span m=''1585190''>before</span> <span m=''1585690''>in</span> <span m=''1585970''>this</span>
  <span m=''1586730''>structural</span> <span m=''1587140''>engineering</span> <span
  m=''1587570''>context?</span> <span m=''1588010''>A</span> <span m=''1588050''>few.</span>
  <span m=''1589900''>And</span> <span m=''1590060''>sometimes,</span> <span m=''1590880''>people</span>
  <span m=''1591130''>end</span> <span m=''1591230''>the</span> <span m=''1591290''>story</span>
  <span m=''1591550''>there.</span> <span m=''1591770''>But</span> <span m=''1591900''>this</span>
  <span m=''1592050''>is</span> <span m=''1592160''>not</span> <span m=''1592370''>enough</span>
  <span m=''1592710''>to</span> <span m=''1592840''>be</span> <span m=''1593480''>generically</span>
  <span m=''1593940''>rigid.</span> <span m=''1594720''>This</span> <span m=''1594880''>is</span>
  <span m=''1595020''>a</span> <span m=''1595080''>necessary</span> <span m=''1595570''>condition,</span>
  <span m=''1595990''>but</span> <span m=''1596120''>it''s</span> <span m=''1596250''>not</span>
  <span m=''1596440''>sufficient.</span> <span m=''1599200''>And</span> <span m=''1599360''>you</span>
  <span m=''1599500''>can</span> <span m=''1599670''>check</span> <span m=''1599920''>all</span>
  <span m=''1600030''>these</span> <span m=''1600200''>examples.</span> <span m=''1601682''>It</span>
  <span m=''1602070''>should</span> <span m=''1602310''>match</span> <span m=''1602580''>up.
  I</span> <span m=''1603040''>haven''t</span> <span m=''1603340''>checked them</span>
  <span m=''1603670''>myself.</span> </p><p><span m=''1617830''>All</span> <span m=''1618050''>right.</span>
  <span m=''1619640''>Let''s</span> <span m=''1619850''>start</span> <span m=''1620070''>characterizing</span>
  <span m=''1620710''>this</span> <span m=''1621430''>thing.</span> <span m=''1631640''>We''re</span>
  <span m=''1631700''>going</span> <span m=''1631800''>to</span> <span m=''1631870''>see</span>
  <span m=''1632090''>two</span> <span m=''1632330''>characterizations</span> <span
  m=''1633440''>of</span> <span m=''1634030''>minimally</span> <span m=''1634450''>generically</span>
  <span m=''1635010''>rigid</span> <span m=''1635290''>graphs.</span> <span m=''1637620''>First</span>
  <span m=''1637880''>one</span> <span m=''1638600''>is</span> <span m=''1638770''>very</span>
  <span m=''1639080''>intuitive,</span> <span m=''1639540''>nice</span> <span m=''1639750''>to</span>
  <span m=''1639840''>work</span> <span m=''1640040''>with</span> <span m=''1640210''>by</span>
  <span m=''1640340''>hand,</span> <span m=''1641190''>but</span> <span m=''1642040''>doesn''t--</span>
  <span m=''1642970''>at least as</span> <span m=''1643210''>far</span> <span m=''1643360''>as</span>
  <span m=''1643450''>I</span> <span m=''1643510''>can</span> <span m=''1643640''>tell,</span>
  <span m=''1643850''>it doesn''t</span> <span m=''1644060''>turn</span> <span m=''1644210''>into</span>
  <span m=''1644390''>an</span> <span m=''1644460''>algorithm.</span> <span m=''1644910''>I</span>
  <span m=''1644980''>think</span> <span m=''1645150''>we''ve</span> <span m=''1645280''>tried</span>
  <span m=''1645650''>in</span> <span m=''1646060''>past</span> <span m=''1646390''>years,</span>
  <span m=''1647300''>but</span> <span m=''1647660''>it</span> <span m=''1648150''>has</span>
  <span m=''1648390''>not.</span> <span m=''1650370''>And</span> <span m=''1650840''>the</span>
  <span m=''1650960''>other</span> <span m=''1651140''>one</span> <span m=''1651420''>is</span>
  <span m=''1652490''>more</span> <span m=''1652750''>algorithmic,</span> <span m=''1653660''>but</span>
  <span m=''1653880''>a</span> <span m=''1653930''>little</span> <span m=''1654130''>bit</span>
  <span m=''1654260''>hard</span> <span m=''1654510''>to</span> <span m=''1655430''>intuit.</span>
  </p><p><span m=''1673380''>So</span> <span m=''1673570''>this</span> <span m=''1673790''>is</span>
  <span m=''1673950''>what</span> <span m=''1674220''>both</span> <span m=''1674520''>theorems</span>
  <span m=''1674740''>look</span> <span m=''1674950''>like.</span> <span m=''1675120''>A</span>
  <span m=''1675180''>graph</span> <span m=''1675450''>is</span> <span m=''1675580''>minimally</span>
  <span m=''1675880''>generically</span> <span m=''1676290''>rigid</span> <span m=''1676570''>in
  2D</span> <span m=''1676800''>if</span> <span m=''1677020''>and</span> <span m=''1677230''>only</span>
  <span m=''1677460''>if--</span> <span m=''1680746''>for</span> <span m=''1681230''>Henneberg,</span>
  <span m=''1681900''>this</span> <span m=''1682070''>is</span> <span m=''1682170''>from</span>
  <span m=''1682370''>the</span> <span m=''1682450''>1911</span> <span m=''1683170''>result--</span>
  <span m=''1685120''>it</span> <span m=''1685360''>can</span> <span m=''1685780''>be</span>
  <span m=''1688270''>built.</span> </p><p><span m=''1705390''>Oh,</span> <span m=''1705500''>by</span>
  <span m=''1705640''>the</span> <span m=''1705760''>way.</span> <span m=''1705900''>Maybe</span>
  <span m=''1706230''>the</span> <span m=''1706600''>reason</span> <span m=''1706870''>people</span>
  <span m=''1707090''>haven''t</span> <span m=''1707280''>seen</span> <span m=''1707420''>2n</span>
  <span m=''1707660''>minus</span> <span m=''1707920''>three is</span> <span m=''1708150''>because</span>
  <span m=''1708340''>they''re used to the</span> <span m=''1708710''>3D</span> <span
  m=''1709010''>case.</span> <span m=''1709310''>There it''s</span> <span m=''1709610''>2n</span>
  <span m=''1709900''>minus</span> <span m=''1710150''>6.</span> <span m=''1710910''>How</span>
  <span m=''1710990''>many</span> <span m=''1711120''>people have</span> <span m=''1711360''>seen
  3n</span> <span m=''1711740''>minus 6?</span> <span m=''1713610''>Same</span> <span
  m=''1713860''>people.</span> <span m=''1714290''>All right.</span> <span m=''1715780''>Thought</span>
  <span m=''1715950''>I''d</span> <span m=''1716080''>try.</span> <span m=''1717390''>All
  right.</span> <span m=''1719810''>You guys</span> <span m=''1719860''>should</span>
  <span m=''1720060''>take</span> <span m=''1720250''>structural</span> <span m=''1720630''>engineering.</span>
  </p><p><span m=''1728370''>So</span> <span m=''1728560''>this</span> <span m=''1728780''>is</span>
  <span m=''1728880''>the</span> <span m=''1728990''>form</span> <span m=''1729320''>of</span>
  <span m=''1729460''>the</span> <span m=''1729570''>theorem.</span> <span m=''1730770''>The</span>
  <span m=''1730910''>idea is</span> <span m=''1731180''>we''re</span> <span m=''1731300''>starting</span>
  <span m=''1731780''>with</span> <span m=''1732330''>a</span> <span m=''1732450''>single</span>
  <span m=''1732800''>edge</span> <span m=''1733190''>connecting</span> <span m=''1733600''>two</span>
  <span m=''1733750''>vertices,</span> <span m=''1734530''>which</span> <span m=''1734770''>is</span>
  <span m=''1735070''>minimally</span> <span m=''1735410''>generically</span> <span
  m=''1735850''>rigid.</span> <span m=''1736610''>All it can</span> <span m=''1736910''>do</span>
  <span m=''1737070''>is</span> <span m=''1737170''>rotate</span> <span m=''1737570''>and</span>
  <span m=''1737670''>translate.</span> <span m=''1738960''>And</span> <span m=''1739300''>the</span>
  <span m=''1739390''>claim</span> <span m=''1739690''>is</span> <span m=''1739890''>whatever</span>
  <span m=''1740320''>you</span> <span m=''1740480''>want</span> <span m=''1740670''>to</span>
  <span m=''1740730''>build,</span> <span m=''1741340''>I</span> <span m=''1741500''>can</span>
  <span m=''1741730''>build</span> <span m=''1742040''>it</span> <span m=''1742590''>using</span>
  <span m=''1742890''>just</span> <span m=''1743190''>two</span> <span m=''1744190''>types</span>
  <span m=''1744640''>of</span> <span m=''1745490''>operations.</span> </p><p><span
  m=''1746990''>First</span> <span m=''1747320''>type</span> <span m=''1748750''>is</span>
  <span m=''1748940''>I</span> <span m=''1749010''>take</span> <span m=''1749240''>something</span>
  <span m=''1749560''>that</span> <span m=''1749690''>I''ve</span> <span m=''1749840''>already</span>
  <span m=''1750180''>built.</span> <span m=''1751730''>I</span> <span m=''1751820''>add</span>
  <span m=''1752110''>one</span> <span m=''1752370''>new</span> <span m=''1752510''>vertex,</span>
  <span m=''1753460''>and</span> <span m=''1753620''>I</span> <span m=''1753680''>attach</span>
  <span m=''1754130''>it</span> <span m=''1754840''>to</span> <span m=''1755520''>two</span>
  <span m=''1755690''>existing</span> <span m=''1756080''>vertices.</span> <span m=''1758530''>So</span>
  <span m=''1758890''>everything</span> <span m=''1759260''>in</span> <span m=''1759340''>the</span>
  <span m=''1759410''>circle</span> <span m=''1759730''>is</span> <span m=''1759840''>old,</span>
  <span m=''1760890''>and</span> <span m=''1761140''>the</span> <span m=''1761220''>new</span>
  <span m=''1761370''>thing</span> <span m=''1762620''>is</span> <span m=''1762700''>that</span>
  <span m=''1762890''>vertex</span> <span m=''1763350''>and</span> <span m=''1763470''>those</span>
  <span m=''1763660''>two</span> <span m=''1763790''>guys.</span> </p><p><span m=''1765214''>AUDIENCE:
  Everything is</span> <span m=''1765701''>old</span> <span m=''1766188''>and</span>
  <span m=''1766675''>rigid.</span> </p><p><span m=''1767650''>PROFESSOR: Yeah.</span>
  <span m=''1767950''>This</span> <span m=''1768150''>is</span> <span m=''1768260''>something
  that</span> <span m=''1768590''>you</span> <span m=''1768750''>could</span> <span
  m=''1768920''>already</span> <span m=''1769280''>build</span> <span m=''1769640''>from</span>
  <span m=''1769880''>this--</span> <span m=''1771250''>I</span> <span m=''1771310''>mean,</span>
  <span m=''1771600''>in</span> <span m=''1771730''>particular,</span> <span m=''1772190''>that</span>
  <span m=''1772330''>will</span> <span m=''1772440''>be</span> <span m=''1772540''>minimally</span>
  <span m=''1772850''>generically</span> <span m=''1773220''>rigid.</span> <span m=''1773530''>But</span>
  <span m=''1773700''>that''s</span> <span m=''1773900''>not</span> <span m=''1774390''>what</span>
  <span m=''1774530''>we''re</span> <span m=''1774630''>saying</span> <span m=''1774890''>right</span>
  <span m=''1775050''>now.</span> <span m=''1776000''>You</span> <span m=''1776110''>start</span>
  <span m=''1776390''>from</span> <span m=''1776500''>the</span> <span m=''1776620''>edge,</span>
  <span m=''1777190''>and</span> <span m=''1777360''>you</span> <span m=''1777480''>just</span>
  <span m=''1777680''>keep</span> <span m=''1777880''>doing</span> <span m=''1778120''>this.</span>
  <span m=''1778300''>So I can</span> <span m=''1778750''>turn it</span> <span m=''1778960''>into</span>
  <span m=''1779230''>a</span> <span m=''1779290''>triangle,</span> <span m=''1779710''>for</span>
  <span m=''1779830''>example.</span> <span m=''1781030''>Just</span> <span m=''1781220''>keep</span>
  <span m=''1781390''>taking</span> <span m=''1781700''>things</span> <span m=''1781920''>that
  I already</span> <span m=''1782400''>know</span> <span m=''1782610''>how</span>
  <span m=''1782740''>to</span> <span m=''1782830''>build,</span> <span m=''1783500''>add</span>
  <span m=''1783690''>one</span> <span m=''1783860''>vertex and</span> <span m=''1784360''>two</span>
  <span m=''1784540''>edges.</span> </p><p><span m=''1786730''>The</span> <span m=''1786820''>other</span>
  <span m=''1786970''>type</span> <span m=''1787190''>of</span> <span m=''1787320''>operation,</span>
  <span m=''1788300''>I</span> <span m=''1788440''>take</span> <span m=''1788600''>something</span>
  <span m=''1788940''>I''ve</span> <span m=''1789020''>already</span> <span m=''1789250''>built.</span>
  <span m=''1790660''>I</span> <span m=''1790770''>take</span> <span m=''1791020''>three</span>
  <span m=''1791320''>of</span> <span m=''1791390''>the</span> <span m=''1791470''>vertices</span>
  <span m=''1793610''>in</span> <span m=''1793790''>there,</span> <span m=''1795220''>and</span>
  <span m=''1797930''>there''s</span> <span m=''1798110''>already</span> <span m=''1798410''>an</span>
  <span m=''1798540''>edge</span> <span m=''1798810''>between</span> <span m=''1799170''>them--</span>
  <span m=''1800490''>at</span> <span m=''1800580''>least</span> <span m=''1800820''>one.</span>
  <span m=''1801010''>There</span> <span m=''1801090''>might</span> <span m=''1801280''>be</span>
  <span m=''1801400''>more.</span> <span m=''1803040''>And</span> <span m=''1803330''>I</span>
  <span m=''1803540''>add</span> <span m=''1804300''>three</span> <span m=''1804680''>edges</span>
  <span m=''1805760''>connecting</span> <span m=''1806120''>to</span> <span m=''1806250''>a</span>
  <span m=''1806290''>new</span> <span m=''1806450''>vertex,</span> <span m=''1808360''>and</span>
  <span m=''1808650''>I</span> <span m=''1808730''>delete</span> <span m=''1810480''>that</span>
  <span m=''1810780''>old</span> <span m=''1811090''>edge.</span> <span m=''1812800''>So</span>
  <span m=''1812940''>I</span> <span m=''1813010''>add</span> <span m=''1813330''>three,</span>
  <span m=''1813840''>I</span> <span m=''1813980''>remove</span> <span m=''1814960''>one.</span>
  </p><p><span m=''1817130''>Either I</span> <span m=''1817370''>add</span> <span
  m=''1817670''>two</span> <span m=''1817890''>and</span> <span m=''1817990''>remove</span>
  <span m=''1818200''>zero,</span> <span m=''1818960''>or</span> <span m=''1819130''>I</span>
  <span m=''1819200''>add</span> <span m=''1819440''>three</span> <span m=''1820120''>and</span>
  <span m=''1820310''>remove</span> <span m=''1820620''>one.</span> <span m=''1820900''>This</span>
  <span m=''1821400''>should</span> <span m=''1821620''>make</span> <span m=''1821790''>sense,</span>
  <span m=''1822110''>because</span> <span m=''1822320''>if</span> <span m=''1822450''>we''re</span>
  <span m=''1822550''>going</span> <span m=''1822700''>to</span> <span m=''1822760''>get</span>
  <span m=''1823450''>about</span> <span m=''1823990''>two</span> <span m=''1824290''>edges</span>
  <span m=''1824660''>per</span> <span m=''1824840''>vertex,</span> <span m=''1825850''>this</span>
  <span m=''1826050''>is</span> <span m=''1826160''>just</span> <span m=''1826380''>the</span>
  <span m=''1826480''>starting</span> <span m=''1826880''>case.</span> <span m=''1828070''>If</span>
  <span m=''1828210''>I</span> <span m=''1828270''>want</span> <span m=''1828480''>two</span>
  <span m=''1828600''>edges</span> <span m=''1828860''>per</span> <span m=''1828980''>vertex,</span>
  <span m=''1829900''>I</span> <span m=''1830040''>really</span> <span m=''1830320''>should</span>
  <span m=''1830570''>only</span> <span m=''1830770''>be</span> <span m=''1830940''>adding</span>
  <span m=''1831310''>two</span> <span m=''1831860''>edges</span> <span m=''1832260''>for</span>
  <span m=''1832430''>every</span> <span m=''1832620''>vertex</span> <span m=''1833050''>that
  I</span> <span m=''1833100''>add.</span> <span m=''1834570''>So</span> <span m=''1834610''>these</span>
  <span m=''1834810''>are</span> <span m=''1834890''>two</span> <span m=''1835090''>things</span>
  <span m=''1835320''>you</span> <span m=''1835440''>could</span> <span m=''1835620''>do.</span>
  </p><p><span m=''1835780''>And</span> <span m=''1835860''>you</span> <span m=''1835940''>could</span>
  <span m=''1836070''>imagine</span> <span m=''1836390''>a</span> <span m=''1836410''>more</span>
  <span m=''1836580''>complicated</span> <span m=''1837170''>ones</span> <span m=''1837370''>where
  I</span> <span m=''1837490''>add</span> <span m=''1837700''>four</span> <span m=''1837970''>edges,</span>
  <span m=''1838340''>remove</span> <span m=''1838690''>two.</span> <span m=''1839410''>You</span>
  <span m=''1839530''>don''t</span> <span m=''1839680''>have</span> <span m=''1839830''>to</span>
  <span m=''1839950''>worry</span> <span m=''1840130''>about</span> <span m=''1840390''>that.</span>
  <span m=''1841020''>You</span> <span m=''1841160''>only</span> <span m=''1841410''>have</span>
  <span m=''1841600''>to</span> <span m=''1841710''>worry</span> <span m=''1841870''>about</span>
  <span m=''1842720''>these</span> <span m=''1842900''>two</span> <span m=''1843030''>scenarios.</span>
  <span m=''1843750''>That''s</span> <span m=''1843960''>enough</span> <span m=''1844190''>to</span>
  <span m=''1844290''>build</span> <span m=''1844520''>everything.</span> </p><p><span
  m=''1848460''>Maybe</span> <span m=''1848710''>we</span> <span m=''1848830''>can</span>
  <span m=''1848930''>do</span> <span m=''1849020''>an</span> <span m=''1849090''>example</span>
  <span m=''1854300''>before</span> <span m=''1854570''>we</span> <span m=''1854690''>prove</span>
  <span m=''1855040''>this</span> <span m=''1855280''>theorem.</span> <span m=''1856270''>I''m</span>
  <span m=''1856400''>not</span> <span m=''1856580''>going</span> <span m=''1856690''>to</span>
  <span m=''1856760''>prove</span> <span m=''1857970''>all</span> <span m=''1858120''>the</span>
  <span m=''1858200''>parts.</span> <span m=''1858850''>I''m going to give</span>
  <span m=''1859140''>a</span> <span m=''1859340''>sketch.</span> <span m=''1863960''>In</span>
  <span m=''1864020''>particular,</span> <span m=''1864630''>to</span> <span m=''1864750''>prove</span>
  <span m=''1865080''>it,</span> <span m=''1865250''>I</span> <span m=''1865340''>need</span>
  <span m=''1866310''>technology</span> <span m=''1866850''>that</span> <span m=''1867020''>we''ll</span>
  <span m=''1867160''>develop</span> <span m=''1867540''>next</span> <span m=''1867790''>class.</span>
  <span m=''1868540''>So</span> <span m=''1869140''>it''s</span> <span m=''1869240''>a</span>
  <span m=''1869280''>little</span> <span m=''1869470''>hard</span> <span m=''1869680''>to</span>
  <span m=''1869780''>do</span> <span m=''1869910''>in</span> <span m=''1870000''>a</span>
  <span m=''1870050''>self-contained</span> <span m=''1870640''>way.</span> <span
  m=''1871250''>But</span> <span m=''1871400''>let''s</span> <span m=''1871610''>start</span>
  <span m=''1871830''>with</span> <span m=''1872430''>an easy</span> <span m=''1872560''>example.</span>
  </p><p><span m=''1878750''>You may</span> <span m=''1878990''>remember</span> <span
  m=''1879320''>this</span> <span m=''1879540''>one.</span> <span m=''1879720''>When</span>
  <span m=''1879850''>I</span> <span m=''1879930''>drew</span> <span m=''1880190''>everything</span>
  <span m=''1880620''>parallel</span> <span m=''1881800''>and</span> <span m=''1882090''>the</span>
  <span m=''1882170''>triangles</span> <span m=''1882590''>were</span> <span m=''1882660''>identical,</span>
  <span m=''1884260''>then</span> <span m=''1884540''>this</span> <span m=''1884690''>thing
  was</span> <span m=''1884920''>flexible.</span> <span m=''1885360''>But</span> <span
  m=''1885450''>most of</span> <span m=''1885690''>the</span> <span m=''1885790''>time,</span>
  <span m=''1886020''>generically,</span> <span m=''1886450''>this</span> <span m=''1886660''>is</span>
  <span m=''1886810''>rigid,</span> <span m=''1887940''>and</span> <span m=''1888090''>we</span>
  <span m=''1888180''>can</span> <span m=''1888290''>prove</span> <span m=''1888530''>that</span>
  <span m=''1889410''>by</span> <span m=''1890500''>doing</span> <span m=''1890750''>these</span>
  <span m=''1890930''>operations.</span> <span m=''1894680''>So</span> <span m=''1895370''>somehow</span>
  <span m=''1896350''>I</span> <span m=''1896420''>start</span> <span m=''1896690''>with</span>
  <span m=''1896820''>an</span> <span m=''1896900''>edge.</span> <span m=''1897900''>I</span>
  <span m=''1898000''>have</span> <span m=''1898030''>to</span> <span m=''1898150''>do</span>
  <span m=''1898320''>operations</span> <span m=''1898880''>to</span> <span m=''1898980''>end</span>
  <span m=''1899170''>up</span> <span m=''1899330''>here.</span> <span m=''1900410''>That''s</span>
  <span m=''1900600''>a</span> <span m=''1900640''>little</span> <span m=''1900860''>hard
  to--</span> <span m=''1901140''>yeah.</span> <span m=''1901420''>Question.</span>
  </p><p><span m=''1902702''>AUDIENCE: Does the</span> <span m=''1903140''>removed</span>
  <span m=''1904034''>edge have to</span> <span m=''1904468''>be</span> <span m=''1904902''>between</span>
  <span m=''1906204''>two of the</span> <span m=''1906640''>three</span> <span m=''1906790''>vertices?</span>
  </p><p><span m=''1907650''>PROFESSOR: The</span> <span m=''1907760''>removed</span>
  <span m=''1908110''>edge</span> <span m=''1908280''>has</span> <span m=''1908540''>to</span>
  <span m=''1908640''>be</span> <span m=''1908790''>among</span> <span m=''1909240''>those</span>
  <span m=''1909480''>three</span> <span m=''1909620''>vertices.</span> <span m=''1910600''>And</span>
  <span m=''1910790''>there</span> <span m=''1910870''>might</span> <span m=''1911030''>be</span>
  <span m=''1911140''>more</span> <span m=''1911300''>than</span> <span m=''1911430''>one.</span>
  <span m=''1911840''>You would</span> <span m=''1912020''>just</span> <span m=''1912260''>remove</span>
  <span m=''1912470''>one</span> <span m=''1912640''>of</span> <span m=''1912740''>them.</span>
  <span m=''1913190''>You</span> <span m=''1913310''>get</span> <span m=''1913440''>to</span>
  <span m=''1913520''>remove</span> <span m=''1913730''>whichever</span> <span m=''1914080''>one</span>
  <span m=''1914230''>you</span> <span m=''1914320''>want.</span> <span m=''1915390''>Good</span>
  <span m=''1915470''>question.</span> </p><p><span m=''1917780''>So</span> <span
  m=''1918440''>if</span> <span m=''1918650''>we</span> <span m=''1918860''>were</span>
  <span m=''1920670''>lucky</span> <span m=''1921340''>and</span> <span m=''1921480''>adventurous,</span>
  <span m=''1922540''>we</span> <span m=''1922680''>could</span> <span m=''1922830''>just</span>
  <span m=''1923020''>try</span> <span m=''1923270''>going</span> <span m=''1923590''>here</span>
  <span m=''1924010''>and</span> <span m=''1924590''>hope</span> <span m=''1924920''>that</span>
  <span m=''1925060''>we</span> <span m=''1925220''>end</span> <span m=''1925380''>up</span>
  <span m=''1925510''>there.</span> <span m=''1926210''>But</span> <span m=''1927730''>we</span>
  <span m=''1927820''>don''t</span> <span m=''1927950''>want</span> <span m=''1928060''>to</span>
  <span m=''1928140''>draw</span> <span m=''1928380''>all</span> <span m=''1928500''>the</span>
  <span m=''1928580''>possible</span> <span m=''1928920''>things</span> <span m=''1929110''>we</span>
  <span m=''1929190''>could</span> <span m=''1929290''>make,</span> <span m=''1929490''>because</span>
  <span m=''1929560''>that''s</span> <span m=''1929840''>all</span> <span m=''1930110''>minimally</span>
  <span m=''1930470''>generically</span> <span m=''1930880''>rigid</span> <span m=''1931100''>graphs.</span>
  <span m=''1931920''>It''s a</span> <span m=''1931970''>lot</span> <span m=''1932100''>easier</span>
  <span m=''1932640''>to</span> <span m=''1932850''>think</span> <span m=''1933160''>backwards,</span>
  <span m=''1934830''>as</span> <span m=''1935080''>often</span> <span m=''1935400''>the</span>
  <span m=''1935490''>case</span> <span m=''1935750''>in</span> <span m=''1935850''>puzzles.</span>
  </p><p><span m=''1937850''>If</span> <span m=''1938040''>I</span> <span m=''1938100''>want</span>
  <span m=''1938330''>to</span> <span m=''1938390''>make</span> <span m=''1938610''>this,</span>
  <span m=''1939030''>what</span> <span m=''1939240''>was</span> <span m=''1939400''>the</span>
  <span m=''1939500''>last</span> <span m=''1939860''>operation</span> <span m=''1940370''>that</span>
  <span m=''1940490''>I</span> <span m=''1940570''>did?</span> <span m=''1943000''>It</span>
  <span m=''1943140''>must</span> <span m=''1943380''>have</span> <span m=''1943460''>been</span>
  <span m=''1943650''>one</span> <span m=''1943810''>of</span> <span m=''1943870''>these</span>
  <span m=''1944100''>two.</span> <span m=''1945550''>And</span> <span m=''1945740''>every</span>
  <span m=''1945940''>vertex</span> <span m=''1946380''>here</span> <span m=''1946550''>has</span>
  <span m=''1946830''>degree</span> <span m=''1947150''>three,</span> <span m=''1947420''>has</span>
  <span m=''1947670''>three</span> <span m=''1947870''>incident</span> <span m=''1948210''>edges.</span>
  <span m=''1949210''>So</span> <span m=''1949810''>probably</span> <span m=''1950180''>it
  was</span> <span m=''1950350''>a</span> <span m=''1950420''>Type</span> <span m=''1950590''>II</span>
  <span m=''1950820''>operation.</span> <span m=''1952630''>So</span> <span m=''1952920''>there''s</span>
  <span m=''1953050''>going</span> <span m=''1953150''>to</span> <span m=''1953200''>be
  a</span> <span m=''1953340''>Type</span> <span m=''1953590''>II</span> <span m=''1953740''>operation</span>
  <span m=''1954390''>that</span> <span m=''1954530''>results</span> <span m=''1954930''>in</span>
  <span m=''1955010''>this</span> <span m=''1955210''>thing.</span> </p><p><span m=''1955940''>Let''s</span>
  <span m=''1956170''>say,</span> <span m=''1956500''>I</span> <span m=''1956530''>don''t</span>
  <span m=''1956650''>know,</span> <span m=''1956780''>this</span> <span m=''1956990''>vertex.</span>
  <span m=''1958320''>And</span> <span m=''1958450''>here</span> <span m=''1958620''>I</span>
  <span m=''1958700''>still</span> <span m=''1958930''>have</span> <span m=''1959060''>to</span>
  <span m=''1959150''>be</span> <span m=''1959260''>a</span> <span m=''1959310''>little</span>
  <span m=''1959480''>bit</span> <span m=''1959640''>lucky,</span> <span m=''1959990''>but</span>
  <span m=''1960230''>it''s</span> <span m=''1960400''>not</span> <span m=''1960560''>quite</span>
  <span m=''1960770''>as</span> <span m=''1960890''>lucky.</span> <span m=''1963020''>OK</span>
  <span m=''1963640''>so</span> <span m=''1966510''>I''m</span> <span m=''1966870''>going</span>
  <span m=''1966960''>to</span> <span m=''1967020''>try</span> <span m=''1967190''>not</span>
  <span m=''1967420''>to</span> <span m=''1967520''>cheat</span> <span m=''1967820''>here.</span>
  <span m=''1970590''>So</span> <span m=''1971310''>we</span> <span m=''1971480''>remove</span>
  <span m=''1971850''>that</span> <span m=''1972070''>vertex,</span> <span m=''1972870''>and</span>
  <span m=''1972990''>we</span> <span m=''1973110''>also</span> <span m=''1973350''>remove</span>
  <span m=''1973660''>some</span> <span m=''1973940''>edge</span> <span m=''1974230''>among</span>
  <span m=''1974490''>these</span> <span m=''1974750''>guys.</span> <span m=''1976500''>So</span>
  <span m=''1977840''>I''m</span> <span m=''1977960''>going</span> <span m=''1978050''>to</span>
  <span m=''1978110''>guess</span> <span m=''1978370''>that</span> <span m=''1978470''>I</span>
  <span m=''1978540''>removed</span> <span m=''1979700''>that</span> <span m=''1980000''>edge.</span>
  <span m=''1981531''>I</span> <span m=''1981910''>think that''ll</span> <span m=''1982050''>work.</span>
  <span m=''1984010''>I</span> <span m=''1984180''>have</span> <span m=''1984370''>to</span>
  <span m=''1984480''>be</span> <span m=''1984620''>careful.</span> <span m=''1984970''>I</span>
  <span m=''1985090''>could</span> <span m=''1985300''>have</span> <span m=''1985420''>removed</span>
  <span m=''1985690''>this</span> <span m=''1985910''>edge.</span> <span m=''1988220''>There</span>
  <span m=''1988400''>are</span> <span m=''1988450''>two</span> <span m=''1988600''>cases.</span>
  <span m=''1991690''>I''ll</span> <span m=''1992030''>explain</span> <span m=''1992340''>later</span>
  <span m=''1992720''>what</span> <span m=''1992810''>we</span> <span m=''1992930''>need</span>
  <span m=''1993080''>to</span> <span m=''1993170''>check</span> <span m=''1993430''>here.</span>
  </p><p><span m=''1994490''>Well,</span> <span m=''1994660''>now</span> <span m=''1994810''>I</span>
  <span m=''1994910''>see</span> <span m=''1995150''>a</span> <span m=''1995190''>nice</span>
  <span m=''1995530''>Type</span> <span m=''1996000''>I</span> <span m=''1996250''>operation.</span>
  <span m=''1996830''>I''ll</span> <span m=''1996920''>just</span> <span m=''1997100''>get</span>
  <span m=''1997250''>rid</span> <span m=''1997390''>of</span> <span m=''1997470''>that</span>
  <span m=''1997690''>vertex.</span> <span m=''2000500''>Good.</span> <span m=''2001540''>So</span>
  <span m=''2001710''>Type</span> <span m=''2001960''>I</span> <span m=''2002120''>operation.</span>
  <span m=''2003120''>I''m</span> <span m=''2003330''>left</span> <span m=''2003670''>with</span>
  <span m=''2005550''>this,</span> <span m=''2007400''>and</span> <span m=''2007550''>I</span>
  <span m=''2007620''>see</span> <span m=''2007870''>two</span> <span m=''2008030''>more</span>
  <span m=''2008250''>Type</span> <span m=''2008470''>I</span> <span m=''2008610''>operations.</span>
  <span m=''2009430''>I''ll do</span> <span m=''2009850''>them</span> <span m=''2009990''>one</span>
  <span m=''2010140''>at</span> <span m=''2010240''>a</span> <span m=''2010310''>time.</span>
  <span m=''2018840''>Ta</span> <span m=''2019190''>da.</span> <span m=''2021550''>I</span>
  <span m=''2021570''>think</span> <span m=''2021710''>that''s</span> <span m=''2021900''>right.</span>
  </p><p><span m=''2022020''>We</span> <span m=''2022130''>can</span> <span m=''2022250''>play
  it</span> <span m=''2022430''>forwards</span> <span m=''2022780''>just</span> <span
  m=''2022930''>to</span> <span m=''2023000''>double</span> <span m=''2023260''>check,</span>
  <span m=''2023580''>but</span> <span m=''2023700''>I</span> <span m=''2023760''>started</span>
  <span m=''2024010''>with</span> <span m=''2024140''>an</span> <span m=''2024240''>edge.</span>
  <span m=''2024590''>I</span> <span m=''2024910''>added</span> <span m=''2025260''>one</span>
  <span m=''2025500''>vertex</span> <span m=''2026000''>connected</span> <span m=''2026360''>to</span>
  <span m=''2026510''>the</span> <span m=''2026550''>existing</span> <span m=''2027020''>two.
  I</span> <span m=''2027240''>added</span> <span m=''2027420''>another</span> <span
  m=''2027720''>vertex</span> <span m=''2028130''>connecting</span> <span m=''2028540''>to
  two</span> <span m=''2028830''>existing.</span> <span m=''2030080''>I added</span>
  <span m=''2030310''>another</span> <span m=''2030640''>vertex</span> <span m=''2031050''>connected
  to</span> <span m=''2031500''>two</span> <span m=''2031630''>existing.</span> <span
  m=''2032470''>And</span> <span m=''2032670''>then</span> <span m=''2032940''>the</span>
  <span m=''2033030''>tricky</span> <span m=''2033340''>one--</span> <span m=''2033630''>I</span>
  <span m=''2033720''>added</span> <span m=''2034020''>this</span> <span m=''2034210''>vertex</span>
  <span m=''2035070''>here,</span> <span m=''2035650''>I</span> <span m=''2035740''>connected
  it</span> <span m=''2036170''>to</span> <span m=''2036280''>these</span> <span m=''2036590''>three,</span>
  <span m=''2037690''>and</span> <span m=''2037830''>I</span> <span m=''2037880''>removed</span>
  <span m=''2038280''>this</span> <span m=''2038460''>edge.</span> <span m=''2039830''>So</span>
  <span m=''2040740''>because</span> <span m=''2041050''>this</span> <span m=''2041190''>works</span>
  <span m=''2041410''>forwards,</span> <span m=''2042210''>this</span> <span m=''2042380''>theorem</span>
  <span m=''2042610''>tells</span> <span m=''2042910''>us</span> <span m=''2043210''>that</span>
  <span m=''2043430''>graph</span> <span m=''2043670''>is</span> <span m=''2043780''>minimally</span>
  <span m=''2044100''>generically</span> <span m=''2044500''>rigid.</span> <span m=''2044880''>Now</span>
  <span m=''2045040''>we</span> <span m=''2045130''>have</span> <span m=''2045570''>a</span>
  <span m=''2045640''>way</span> <span m=''2045790''>to</span> <span m=''2045890''>test.</span>
  </p><p><span m=''2046920''>Now,</span> <span m=''2047140''>the</span> <span m=''2047300''>algorithm</span>
  <span m=''2047710''>is</span> <span m=''2047810''>a</span> <span m=''2047850''>little</span>
  <span m=''2048030''>tricky,</span> <span m=''2048400''>because</span> <span m=''2048870''>I</span>
  <span m=''2048960''>had</span> <span m=''2049130''>a</span> <span m=''2049179''>choice</span>
  <span m=''2049500''>here.</span> <span m=''2050639''>In</span> <span m=''2050790''>this</span>
  <span m=''2050949''>case,</span> <span m=''2051170''>it</span> <span m=''2051239''>didn''t</span>
  <span m=''2051429''>matter.</span> <span m=''2051880''>In</span> <span m=''2052100''>the</span>
  <span m=''2052190''>notes,</span> <span m=''2052449''>there''s</span> <span m=''2052580''>an</span>
  <span m=''2052630''>example</span> <span m=''2053020''>where</span> <span m=''2053210''>if</span>
  <span m=''2053310''>you</span> <span m=''2053420''>do</span> <span m=''2053560''>the</span>
  <span m=''2053690''>wrong</span> <span m=''2054050''>choice--</span> <span m=''2055170''>you</span>
  <span m=''2055690''>go</span> <span m=''2055830''>backwards</span> <span m=''2056360''>and</span>
  <span m=''2056429''>you</span> <span m=''2056570''>add</span> <span m=''2056739''>in</span>
  <span m=''2056840''>the</span> <span m=''2056940''>wrong</span> <span m=''2057210''>edge--</span>
  <span m=''2058090''>it</span> <span m=''2058130''>doesn''t</span> <span m=''2058420''>work.</span>
  <span m=''2059699''>You</span> <span m=''2059830''>don''t</span> <span m=''2060030''>become</span>
  <span m=''2060310''>minimally</span> <span m=''2060620''>generically</span> <span
  m=''2061020''>rigid,</span> <span m=''2061280''>essentially</span> <span m=''2061719''>because</span>
  <span m=''2062550''>one</span> <span m=''2062750''>part</span> <span m=''2063040''>gets</span>
  <span m=''2063280''>too</span> <span m=''2063449''>many</span> <span m=''2063670''>edges,</span>
  <span m=''2064070''>and</span> <span m=''2064230''>another</span> <span m=''2064449''>part</span>
  <span m=''2064650''>has</span> <span m=''2064810''>too</span> <span m=''2064969''>few.</span>
  <span m=''2065770''>Here,</span> <span m=''2066080''>I</span> <span m=''2066130''>got</span>
  <span m=''2066340''>it</span> <span m=''2066389''>balanced,</span> <span m=''2066870''>and</span>
  <span m=''2066940''>it</span> <span m=''2066989''>worked</span> <span m=''2067239''>out.</span>
  </p><p><span m=''2067800''>And</span> <span m=''2068210''>when</span> <span m=''2068330''>you''re</span>
  <span m=''2068449''>good</span> <span m=''2068610''>at</span> <span m=''2068699''>visualizing
  these,</span> <span m=''2069179''>this</span> <span m=''2069530''>is</span> <span
  m=''2069699''>an</span> <span m=''2069830''>easy</span> <span m=''2070159''>way--</span>
  <span m=''2070320''>like</span> <span m=''2070530''>on</span> <span m=''2070630''>your</span>
  <span m=''2070739''>problem</span> <span m=''2071030''>set</span> <span m=''2071280''>two--</span>
  <span m=''2072170''>this</span> <span m=''2072360''>is</span> <span m=''2072420''>an</span>
  <span m=''2072489''>easy</span> <span m=''2072699''>way</span> <span m=''2072830''>to</span>
  <span m=''2072920''>check,</span> <span m=''2073360''>to</span> <span m=''2073510''>prove</span>
  <span m=''2073889''>to</span> <span m=''2074090''>me</span> <span m=''2074320''>that</span>
  <span m=''2074460''>things</span> <span m=''2074760''>are</span> <span m=''2074870''>minimally</span>
  <span m=''2075210''>generically</span> <span m=''2075620''>rigid.</span> <span m=''2076620''>Just
  have</span> <span m=''2076840''>to</span> <span m=''2076949''>be</span> <span m=''2077020''>a</span>
  <span m=''2077070''>little</span> <span m=''2077219''>careful.</span> <span m=''2078469''>If</span>
  <span m=''2078610''>you</span> <span m=''2078730''>fail,</span> <span m=''2080370''>and</span>
  <span m=''2080659''>you</span> <span m=''2080780''>fail</span> <span m=''2081130''>to</span>
  <span m=''2081199''>get</span> <span m=''2081370''>back</span> <span m=''2081590''>to</span>
  <span m=''2081679''>start</span> <span m=''2082190''>in</span> <span m=''2082370''>this</span>
  <span m=''2082540''>way,</span> <span m=''2083190''>that</span> <span m=''2083310''>doesn''t</span>
  <span m=''2083650''>tell</span> <span m=''2083840''>you</span> <span m=''2083980''>much.</span>
  <span m=''2084340''>You</span> <span m=''2084480''>just</span> <span m=''2084710''>may</span>
  <span m=''2084870''>have</span> <span m=''2084960''>messed</span> <span m=''2085250''>up.</span>
  <span m=''2085830''>You</span> <span m=''2085949''>may</span> <span m=''2086130''>have</span>
  <span m=''2087070''>made</span> <span m=''2087340''>the</span> <span m=''2087420''>wrong</span>
  <span m=''2087639''>choice</span> <span m=''2087940''>along</span> <span m=''2088179''>the</span>
  <span m=''2088260''>way.</span> <span m=''2089020''>But</span> <span m=''2089139''>when</span>
  <span m=''2089260''>it</span> <span m=''2089320''>works,</span> <span m=''2089739''>you</span>
  <span m=''2089840''>know</span> <span m=''2090000''>that</span> <span m=''2090120''>it</span>
  <span m=''2090190''>works,</span> <span m=''2090480''>because</span> <span m=''2090630''>you</span>
  <span m=''2090730''>can play it</span> <span m=''2091020''>forwards.</span> </p><p><span
  m=''2092814''>AUDIENCE:</span> <span m=''2093306''>[INAUDIBLE]</span> </p><p><span
  m=''2099710''>PROFESSOR: Yeah.</span> <span m=''2099910''>By</span> <span m=''2100040''>forward,</span>
  <span m=''2100540''>I</span> <span m=''2100590''>mean</span> <span m=''2101200''>starting</span>
  <span m=''2101560''>from</span> <span m=''2101690''>the</span> <span m=''2101750''>single</span>
  <span m=''2102060''>edge</span> <span m=''2102280''>and</span> <span m=''2102450''>following</span>
  <span m=''2102880''>the</span> <span m=''2102970''>arrows</span> <span m=''2103290''>in</span>
  <span m=''2103390''>the</span> <span m=''2103470''>way</span> <span m=''2103580''>that</span>
  <span m=''2103710''>they''re</span> <span m=''2103870''>pointing.</span> <span m=''2105260''>So</span>
  <span m=''2105950''>going</span> <span m=''2106180''>backwards</span> <span m=''2106560''>is</span>
  <span m=''2106650''>a</span> <span m=''2106710''>little</span> <span m=''2106930''>bit</span>
  <span m=''2107080''>of</span> <span m=''2107660''>a</span> <span m=''2107720''>lucky</span>
  <span m=''2108040''>black</span> <span m=''2108320''>art,</span> <span m=''2108500''>whatever.</span>
  <span m=''2109480''>But</span> <span m=''2109990''>once</span> <span m=''2110220''>you</span>
  <span m=''2110460''>succeed,</span> <span m=''2111000''>you</span> <span m=''2111130''>can</span>
  <span m=''2111270''>play</span> <span m=''2111450''>it</span> <span m=''2111510''>forwards</span>
  <span m=''2111880''>and</span> <span m=''2111970''>say,</span> <span m=''2112110''>oh</span>
  <span m=''2112280''>yeah,</span> <span m=''2112550''>that</span> <span m=''2112780''>clearly</span>
  <span m=''2113070''>works.</span> <span m=''2113835''>Another</span> <span m=''2114110''>question.</span>
  </p><p><span m=''2115910''>AUDIENCE: Do you</span> <span m=''2116380''>know if it</span>
  <span m=''2116850''>matters</span> <span m=''2117320''>whether you do</span> <span
  m=''2117790''>Type</span> <span m=''2117946''>I</span> <span m=''2118103''>or</span>
  <span m=''2118260''>Type II</span> <span m=''2118730''>operations first,</span>
  <span m=''2119200''>if you have</span> <span m=''2119670''>choices?</span> </p><p><span
  m=''2120610''>PROFESSOR: Does</span> <span m=''2120830''>it</span> <span m=''2120890''>matter</span>
  <span m=''2121240''>Type</span> <span m=''2121470''>I</span> <span m=''2121610''>versus</span>
  <span m=''2121870''>Type</span> <span m=''2122090''>II?</span> <span m=''2122540''>I</span>
  <span m=''2122690''>don''t</span> <span m=''2122840''>think</span> <span m=''2122970''>it</span>
  <span m=''2123270''>matters</span> <span m=''2123980''>in</span> <span m=''2124080''>general,</span>
  <span m=''2124800''>just</span> <span m=''2125080''>with</span> <span m=''2125220''>Type</span>
  <span m=''2125420''>II,</span> <span m=''2125530''>you</span> <span m=''2125630''>have</span>
  <span m=''2125730''>to</span> <span m=''2125810''>be</span> <span m=''2125920''>careful.</span>
  <span m=''2126730''>Type</span> <span m=''2126960''>one,</span> <span m=''2127110''>I</span>
  <span m=''2127150''>like</span> <span m=''2127350''>to</span> <span m=''2127440''>do</span>
  <span m=''2127570''>immediately,</span> <span m=''2128040''>because</span> <span
  m=''2129240''>there''s</span> <span m=''2129410''>no</span> <span m=''2129530''>choice.</span>
  <span m=''2129860''>You</span> <span m=''2130190''>just</span> <span m=''2130350''>do</span>
  <span m=''2130450''>them.</span> <span m=''2131420''>Type</span> <span m=''2131710''>Is</span>
  <span m=''2131910''>are</span> <span m=''2131990''>always</span> <span m=''2132170''>safe.</span>
  <span m=''2132430''>Type</span> <span m=''2132660''>II,</span> <span m=''2132880''>it</span>
  <span m=''2132970''>depends</span> <span m=''2134090''>which</span> <span m=''2134320''>edge.</span>
  <span m=''2134780''>And</span> <span m=''2135190''>I</span> <span m=''2135310''>should</span>
  <span m=''2135500''>call</span> <span m=''2135640''>these</span> <span m=''2135830''>anti-type</span>
  <span m=''2136360''>II</span> <span m=''2136520''>operations</span> <span m=''2137010''>when</span>
  <span m=''2137120''>you</span> <span m=''2137200''>go</span> <span m=''2137300''>backwards.</span>
  <span m=''2138840''>Anti-Type</span> <span m=''2139350''>II, it</span> <span m=''2139490''>depends</span>
  <span m=''2139830''>which</span> <span m=''2140030''>edge</span> <span m=''2140180''>you</span>
  <span m=''2140370''>add.</span> <span m=''2142050''>So</span> <span m=''2142440''>I</span>
  <span m=''2142540''>like</span> <span m=''2142720''>to</span> <span m=''2142810''>do</span>
  <span m=''2142940''>Type</span> <span m=''2143200''>Is</span> <span m=''2143420''>whenever</span>
  <span m=''2143730''>I</span> <span m=''2143760''>have</span> <span m=''2143900''>the</span>
  <span m=''2144020''>chance.</span> </p><p><span m=''2147530''>All</span> <span m=''2147650''>right.</span>
  <span m=''2149460''>Let</span> <span m=''2149620''>me</span> <span m=''2150010''>sketch</span>
  <span m=''2150410''>a</span> <span m=''2150480''>proof</span> <span m=''2150860''>of</span>
  <span m=''2151180''>this</span> <span m=''2152230''>theorem.</span> <span m=''2168790''>There</span>
  <span m=''2168950''>are</span> <span m=''2169000''>two</span> <span m=''2169140''>directions</span>
  <span m=''2169590''>we</span> <span m=''2169690''>need</span> <span m=''2169860''>to</span>
  <span m=''2169940''>prove.</span> <span m=''2171500''>We</span> <span m=''2171660''>need</span>
  <span m=''2171860''>to</span> <span m=''2171950''>prove</span> <span m=''2172460''>that</span>
  <span m=''2173720''>if</span> <span m=''2173930''>we</span> <span m=''2174020''>build</span>
  <span m=''2174270''>such</span> <span m=''2174500''>a</span> <span m=''2174560''>thing,</span>
  <span m=''2175240''>it</span> <span m=''2175380''>is</span> <span m=''2175520''>minimally</span>
  <span m=''2175860''>generically</span> <span m=''2176310''>rigid.</span> <span m=''2176690''>I''m</span>
  <span m=''2176790''>going</span> <span m=''2176880''>to</span> <span m=''2176940''>start</span>
  <span m=''2177170''>with</span> <span m=''2177260''>that.</span> <span m=''2177680''>And</span>
  <span m=''2177780''>the</span> <span m=''2177880''>other</span> <span m=''2177910''>one</span>
  <span m=''2178470''>we need to</span> <span m=''2178700''>show is</span> <span m=''2179110''>that</span>
  <span m=''2179220''>everything</span> <span m=''2179700''>can</span> <span m=''2179850''>be</span>
  <span m=''2179940''>built</span> <span m=''2180230''>in</span> <span m=''2180300''>this</span>
  <span m=''2180470''>way.</span> <span m=''2182180''>The</span> <span m=''2182250''>first</span>
  <span m=''2182460''>direction</span> <span m=''2182850''>is</span> <span m=''2183000''>not</span>
  <span m=''2183520''>too</span> <span m=''2183720''>hard,</span> <span m=''2183990''>although</span>
  <span m=''2184070''>it''s</span> <span m=''2184360''>still</span> <span m=''2185240''>not
  trivial.</span> <span m=''2187330''>And</span> <span m=''2187780''>this</span> <span
  m=''2187960''>direction</span> <span m=''2190140''>works</span> <span m=''2190340''>in</span>
  <span m=''2190440''>any</span> <span m=''2190620''>dimension,</span> <span m=''2190910''>in</span>
  <span m=''2191200''>fact. It</span> <span m=''2191610''>doesn''t</span> <span m=''2191850''>need</span>
  <span m=''2192000''>to</span> <span m=''2192060''>be</span> <span m=''2192180''>two</span>
  <span m=''2192310''>dimensional.</span> <span m=''2192760''>It''s the</span> <span
  m=''2192940''>other</span> <span m=''2193100''>direction</span> <span m=''2195080''>that''s</span>
  <span m=''2195520''>harder.</span> </p><p><span m=''2204680''>So</span> <span m=''2204820''>let''s</span>
  <span m=''2204990''>suppose</span> <span m=''2205330''>I</span> <span m=''2205380''>have</span>
  <span m=''2205590''>a</span> <span m=''2205640''>generically</span> <span m=''2206100''>rigid</span>
  <span m=''2206340''>graph,</span> <span m=''2210150''>and</span> <span m=''2210590''>I</span>
  <span m=''2210660''>do</span> <span m=''2210860''>a</span> <span m=''2210940''>Type</span>
  <span m=''2211300''>I</span> <span m=''2211540''>operation.</span> <span m=''2215120''>And</span>
  <span m=''2215400''>I</span> <span m=''2215470''>get</span> <span m=''2215660''>a</span>
  <span m=''2215710''>graph</span> <span m=''2215975''>call</span> <span m=''2216240''>G</span>
  <span m=''2216430''>prime.</span> <span m=''2224200''>I</span> <span m=''2224340''>claim</span>
  <span m=''2225050''>that</span> <span m=''2225440''>the</span> <span m=''2225510''>resulting</span>
  <span m=''2225940''>graph</span> <span m=''2226230''>will</span> <span m=''2226330''>also</span>
  <span m=''2226600''>be</span> <span m=''2226740''>generically</span> <span m=''2227160''>rigid</span>
  <span m=''2227480''>and</span> <span m=''2227650''>vice</span> <span m=''2227910''>versa.</span>
  <span m=''2230490''>So</span> <span m=''2231100''>doing</span> <span m=''2231360''>a</span>
  <span m=''2231420''>Type I</span> <span m=''2231670''>operation</span> <span m=''2232230''>does</span>
  <span m=''2232370''>not</span> <span m=''2232570''>affect</span> <span m=''2233000''>generic</span>
  <span m=''2233450''>rigidity.</span> <span m=''2234910''>This</span> <span m=''2235190''>may
  be</span> <span m=''2235520''>obvious,</span> <span m=''2236720''>but</span> <span
  m=''2236880''>let</span> <span m=''2237030''>me</span> <span m=''2238520''>explain</span>
  <span m=''2238930''>it</span> <span m=''2239080''>to</span> <span m=''2239190''>you.</span>
  </p><p><span m=''2241380''>There''s</span> <span m=''2241880''>again</span> <span
  m=''2242160''>two</span> <span m=''2242300''>directions</span> <span m=''2242770''>you</span>
  <span m=''2242850''>need</span> <span m=''2243020''>to</span> <span m=''2243080''>prove.</span>
  <span m=''2244470''>And</span> <span m=''2244980''>let''s</span> <span m=''2245200''>start</span>
  <span m=''2245470''>with--</span> <span m=''2246525''>which one do</span> <span
  m=''2246840''>I</span> <span m=''2246880''>start</span> <span m=''2247160''>with?--</span>
  <span m=''2247990''>this</span> <span m=''2248220''>way.</span> <span m=''2252690''>So</span>
  <span m=''2253460''>I</span> <span m=''2253580''>want</span> <span m=''2253780''>to</span>
  <span m=''2253830''>show</span> <span m=''2254030''>that</span> <span m=''2254220''>if</span>
  <span m=''2254430''>the</span> <span m=''2254540''>new</span> <span m=''2254790''>graph</span>
  <span m=''2255100''>is</span> <span m=''2255240''>rigid,</span> <span m=''2256230''>than</span>
  <span m=''2256410''>the</span> <span m=''2256560''>old</span> <span m=''2256820''>graph</span>
  <span m=''2257460''>is</span> <span m=''2257700''>rigid.</span> <span m=''2258510''>An</span>
  <span m=''2258690''>easier</span> <span m=''2259040''>way</span> <span m=''2259170''>to</span>
  <span m=''2259260''>think</span> <span m=''2259460''>about</span> <span m=''2259710''>that</span>
  <span m=''2260010''>is</span> <span m=''2260680''>if</span> <span m=''2260940''>the</span>
  <span m=''2261210''>old</span> <span m=''2261470''>graph</span> <span m=''2261760''>is</span>
  <span m=''2261920''>flexible,</span> <span m=''2263140''>then</span> <span m=''2263370''>the</span>
  <span m=''2263460''>new</span> <span m=''2263620''>graph</span> <span m=''2263930''>should</span>
  <span m=''2264100''>be</span> <span m=''2264230''>flexible.</span> <span m=''2265600''>Hm.</span>
  <span m=''2266005''>That sounds</span> <span m=''2266410''>all right.</span> </p><p><span
  m=''2267410''>So</span> <span m=''2267550''>I have</span> <span m=''2269070''>G</span>
  <span m=''2269250''>flexible</span> <span m=''2271400''>generically.</span> <span
  m=''2273260''>I</span> <span m=''2273370''>want</span> <span m=''2273550''>to</span>
  <span m=''2273590''>show</span> <span m=''2274760''>that</span> <span m=''2275070''>G</span>
  <span m=''2275240''>prime</span> <span m=''2276130''>is</span> <span m=''2276420''>flexible.</span>
  <span m=''2277560''>So</span> <span m=''2277700''>here''s</span> <span m=''2278040''>G--</span>
  <span m=''2279490''>what</span> <span m=''2279630''>I</span> <span m=''2279670''>called</span>
  <span m=''2279930''>old</span> <span m=''2280230''>before--</span> <span m=''2281570''>and</span>
  <span m=''2281740''>it</span> <span m=''2281940''>flexes</span> <span m=''2282340''>somehow.</span>
  <span m=''2283890''>And</span> <span m=''2284040''>now</span> <span m=''2284260''>I</span>
  <span m=''2284370''>have</span> <span m=''2284640''>this</span> <span m=''2284850''>guy</span>
  <span m=''2286360''>that</span> <span m=''2286510''>I</span> <span m=''2286590''>add</span>
  <span m=''2286820''>on.</span> <span m=''2287730''>These</span> <span m=''2288020''>bars</span>
  <span m=''2288300''>are</span> <span m=''2288410''>rigid,</span> <span m=''2290010''>but</span>
  <span m=''2290480''>it</span> <span m=''2290590''>can</span> <span m=''2290950''>come</span>
  <span m=''2291160''>along</span> <span m=''2291410''>for</span> <span m=''2291510''>the</span>
  <span m=''2291620''>ride.</span> <span m=''2291900''>If</span> <span m=''2292320''>I</span>
  <span m=''2292390''>move</span> <span m=''2292680''>these</span> <span m=''2292860''>two</span>
  <span m=''2293000''>points</span> <span m=''2293950''>somewhat,</span> <span m=''2295240''>I''ll</span>
  <span m=''2295370''>still</span> <span m=''2295590''>be</span> <span m=''2295740''>able</span>
  <span m=''2295910''>to</span> <span m=''2295980''>draw</span> <span m=''2296240''>this</span>
  <span m=''2296450''>guy.</span> </p><p><span m=''2297120''>It is</span> <span m=''2298200''>defined</span>
  <span m=''2298610''>by</span> <span m=''2298750''>the</span> <span m=''2298860''>intersection</span>
  <span m=''2299350''>of</span> <span m=''2299440''>two</span> <span m=''2299620''>circles,</span>
  <span m=''2300240''>one</span> <span m=''2300420''>circle</span> <span m=''2300730''>centered</span>
  <span m=''2301030''>here,</span> <span m=''2301860''>another</span> <span m=''2302190''>circle</span>
  <span m=''2303520''>centered</span> <span m=''2304100''>here.</span> <span m=''2305890''>Those</span>
  <span m=''2306050''>two</span> <span m=''2306150''>circles</span> <span m=''2306470''>actually</span>
  <span m=''2306700''>intersect</span> <span m=''2307070''>in</span> <span m=''2307150''>two</span>
  <span m=''2307320''>points.</span> <span m=''2307780''>But</span> <span m=''2308230''>if</span>
  <span m=''2308410''>I</span> <span m=''2308480''>move</span> <span m=''2309170''>these</span>
  <span m=''2309440''>guys</span> <span m=''2309660''>continuously,</span> <span m=''2310760''>this</span>
  <span m=''2310940''>guy</span> <span m=''2311060''>can</span> <span m=''2311400''>track</span>
  <span m=''2311950''>continuously</span> <span m=''2313160''>along</span> <span m=''2313440''>the</span>
  <span m=''2313520''>intersection</span> <span m=''2314120''>of</span> <span m=''2314240''>those</span>
  <span m=''2314420''>two</span> <span m=''2314510''>circles,</span> <span m=''2315960''>except</span>
  <span m=''2317980''>in</span> <span m=''2318130''>one</span> <span m=''2318310''>special</span>
  <span m=''2318650''>case,</span> <span m=''2319180''>which</span> <span m=''2319660''>is</span>
  <span m=''2319740''>when</span> <span m=''2319890''>the</span> <span m=''2319970''>three</span>
  <span m=''2320150''>points</span> <span m=''2320400''>are</span> <span m=''2320470''>collinear.</span>
  <span m=''2322360''>So</span> <span m=''2322500''>if</span> <span m=''2322580''>this</span>
  <span m=''2322790''>is</span> <span m=''2322940''>the</span> <span m=''2323100''>old,</span>
  <span m=''2324170''>and</span> <span m=''2324580''>here''s</span> <span m=''2324780''>my</span>
  <span m=''2324900''>new</span> <span m=''2325080''>guy,</span> <span m=''2325410''>and</span>
  <span m=''2325530''>this</span> <span m=''2325690''>is</span> <span m=''2325830''>taut,</span>
  <span m=''2326840''>and</span> <span m=''2326980''>these</span> <span m=''2327170''>guys</span>
  <span m=''2327400''>move</span> <span m=''2327630''>away</span> <span m=''2327930''>from</span>
  <span m=''2328130''>each</span> <span m=''2328300''>other,</span> <span m=''2329110''>then</span>
  <span m=''2329310''>this</span> <span m=''2329490''>guy</span> <span m=''2329620''>fails</span>
  <span m=''2329970''>to</span> <span m=''2330080''>exist.</span> <span m=''2331070''>Boom.</span>
  </p><p><span m=''2331890''>But</span> <span m=''2331950''>that''s</span> <span m=''2332190''>not</span>
  <span m=''2332390''>generic.</span> <span m=''2333950''>So</span> <span m=''2334180''>here''s</span>
  <span m=''2334440''>where</span> <span m=''2334570''>I</span> <span m=''2334620''>get</span>
  <span m=''2334770''>these</span> <span m=''2335040''>genericity.</span> <span m=''2336600''>This</span>
  <span m=''2336850''>in</span> <span m=''2336960''>particular</span> <span m=''2337380''>would</span>
  <span m=''2337480''>have</span> <span m=''2337630''>three</span> <span m=''2337790''>points</span>
  <span m=''2338020''>collinear.</span> <span m=''2338880''>So</span> <span m=''2339040''>that''s</span>
  <span m=''2339280''>forbidden.</span> <span m=''2339960''>So</span> <span m=''2340120''>in</span>
  <span m=''2340210''>a</span> <span m=''2340260''>generic</span> <span m=''2340610''>situation--</span>
  <span m=''2341480''>and I</span> <span m=''2341630''>should</span> <span m=''2342300''>be</span>
  <span m=''2342410''>putting</span> <span m=''2342700''>generically</span> <span
  m=''2344310''>here--</span> <span m=''2346030''>if</span> <span m=''2346220''>I</span>
  <span m=''2346300''>can</span> <span m=''2346470''>generically</span> <span m=''2346820''>flex</span>
  <span m=''2347290''>the</span> <span m=''2347410''>original</span> <span m=''2347700''>graph,</span>
  <span m=''2348390''>I''ll</span> <span m=''2348490''>still</span> <span m=''2348740''>be</span>
  <span m=''2348860''>able</span> <span m=''2349020''>to</span> <span m=''2349070''>generically</span>
  <span m=''2349480''>flex</span> <span m=''2349740''>after I</span> <span m=''2350050''>add</span>
  <span m=''2350260''>the</span> <span m=''2350330''>vertex.</span> <span m=''2351680''>Cool.</span>
  <span m=''2353240''>That''s</span> <span m=''2353410''>pretty</span> <span m=''2353690''>easy.</span>
  <span m=''2356760''>The</span> <span m=''2356850''>other</span> <span m=''2356980''>direction--</span>
  <span m=''2357450''>I</span> <span m=''2357530''>mean,</span> <span m=''2357640''>it''s</span>
  <span m=''2357780''>almost</span> <span m=''2358060''>the</span> <span m=''2358120''>same.</span>
  </p><p><span m=''2358480''>So</span> <span m=''2358650''>now</span> <span m=''2358850''>if</span>
  <span m=''2358980''>I</span> <span m=''2359050''>have</span> <span m=''2359260''>G</span>
  <span m=''2359460''>rigid,</span> <span m=''2361830''>I</span> <span m=''2361960''>claim</span>
  <span m=''2362610''>that</span> <span m=''2362910''>G</span> <span m=''2363100''>prime</span>
  <span m=''2364400''>is</span> <span m=''2364680''>generically</span> <span m=''2365170''>rigid--</span>
  <span m=''2366610''>I</span> <span m=''2366760''>should</span> <span m=''2366910''>be</span>
  <span m=''2367010''>putting</span> <span m=''2367250''>generic</span> <span m=''2367750''>everywhere</span>
  <span m=''2368170''>here--</span> <span m=''2370790''>for</span> <span m=''2371170''>essentially</span>
  <span m=''2371530''>the</span> <span m=''2371610''>same</span> <span m=''2371820''>reason.</span>
  <span m=''2372060''>If</span> <span m=''2372180''>I</span> <span m=''2372240''>can''t</span>
  <span m=''2372670''>move</span> <span m=''2372870''>these</span> <span m=''2373060''>vertices--</span>
  <span m=''2374470''>this</span> <span m=''2374650''>vertex</span> <span m=''2375010''>is</span>
  <span m=''2375060''>again</span> <span m=''2375440''>defined</span> <span m=''2375810''>by</span>
  <span m=''2375900''>the</span> <span m=''2375990''>intersection</span> <span m=''2376400''>of</span>
  <span m=''2376450''>two</span> <span m=''2376570''>circles.</span> <span m=''2376930''>It</span>
  <span m=''2377020''>could</span> <span m=''2377160''>be</span> <span m=''2377280''>here</span>
  <span m=''2377520''>or</span> <span m=''2377570''>here,</span> <span m=''2378270''>but</span>
  <span m=''2378390''>we''re</span> <span m=''2378530''>only</span> <span m=''2378700''>thinking</span>
  <span m=''2378970''>about</span> <span m=''2379180''>continuous</span> <span m=''2379630''>motions.</span>
  </p><p><span m=''2380650''>Motion</span> <span m=''2381000''>means</span> <span
  m=''2381230''>continuous.</span> <span m=''2382070''>I</span> <span m=''2382190''>can''t</span>
  <span m=''2382550''>instantaneously</span> <span m=''2383270''>jump</span> <span
  m=''2383520''>over</span> <span m=''2383700''>here.</span> <span m=''2384260''>I</span>
  <span m=''2384360''>have</span> <span m=''2384550''>to</span> <span m=''2384650''>stay</span>
  <span m=''2384910''>right</span> <span m=''2385170''>there.</span> <span m=''2385940''>These</span>
  <span m=''2386130''>guys</span> <span m=''2386300''>don''t</span> <span m=''2386460''>move--</span>
  <span m=''2387580''>and</span> <span m=''2387660''>I</span> <span m=''2387710''>mean</span>
  <span m=''2387930''>that</span> <span m=''2388070''>in</span> <span m=''2388180''>a</span>
  <span m=''2388250''>relative</span> <span m=''2388640''>sense.</span> <span m=''2388900''>Of</span>
  <span m=''2388990''>course,</span> <span m=''2389210''>they</span> <span m=''2389280''>can</span>
  <span m=''2389420''>translate</span> <span m=''2389850''>and</span> <span m=''2389920''>rotate--</span>
  <span m=''2390890''>but</span> <span m=''2392540''>if</span> <span m=''2392740''>they
  don''t</span> <span m=''2392930''>move</span> <span m=''2393110''>away</span> <span
  m=''2393350''>from</span> <span m=''2393510''>each</span> <span m=''2393650''>other,</span>
  <span m=''2394290''>this</span> <span m=''2394380''>guy</span> <span m=''2394560''>can''t</span>
  <span m=''2394890''>do</span> <span m=''2394990''>anything</span> <span m=''2395300''>interesting.</span>
  <span m=''2397970''>So</span> <span m=''2398310''>if</span> <span m=''2398450''>the</span>
  <span m=''2398540''>original</span> <span m=''2398820''>thing</span> <span m=''2398970''>is</span>
  <span m=''2399070''>rigid,</span> <span m=''2399450''>the</span> <span m=''2399540''>new</span>
  <span m=''2399660''>thing</span> <span m=''2399860''>is</span> <span m=''2399980''>rigid.</span>
  <span m=''2400920''>I''ll</span> <span m=''2401140''>start</span> <span m=''2401230''>going</span>
  <span m=''2401420''>a</span> <span m=''2401470''>little</span> <span m=''2401610''>faster,</span>
  <span m=''2402040''>but</span> <span m=''2402180''>that''s</span> <span m=''2403450''>the</span>
  <span m=''2403620''>idea.</span> <span m=''2406190''>This</span> <span m=''2406370''>is</span>
  <span m=''2406430''>a</span> <span m=''2406520''>start,</span> <span m=''2407620''>but</span>
  <span m=''2407750''>what</span> <span m=''2407880''>we</span> <span m=''2408000''>really</span>
  <span m=''2408240''>care</span> <span m=''2408440''>about</span> <span m=''2408620''>is</span>
  <span m=''2408700''>minimal</span> <span m=''2409060''>generic</span> <span m=''2409520''>rigidity.</span>
  </p><p><span m=''2429650''>And</span> <span m=''2431430''>this is</span> <span m=''2431670''>also</span>
  <span m=''2432030''>if and</span> <span m=''2432080''>only</span> <span m=''2432340''>if.</span>
  <span m=''2433930''>If</span> <span m=''2433965''>your</span> <span m=''2434000''>original</span>
  <span m=''2434350''>graph</span> <span m=''2434570''>is</span> <span m=''2434700''>minimally</span>
  <span m=''2435100''>generically</span> <span m=''2435550''>rigid,</span> <span m=''2436650''>then</span>
  <span m=''2437230''>your</span> <span m=''2437430''>new</span> <span m=''2437580''>graph</span>
  <span m=''2438750''>from</span> <span m=''2438980''>a</span> <span m=''2439030''>Type</span>
  <span m=''2439250''>I</span> <span m=''2439380''>operation</span> <span m=''2439740''>will</span>
  <span m=''2439830''>also</span> <span m=''2440110''>be</span> <span m=''2440240''>minimally</span>
  <span m=''2440610''>generically</span> <span m=''2441010''>rigid,</span> <span m=''2441320''>and</span>
  <span m=''2441450''>vice</span> <span m=''2441700''>versa.</span> <span m=''2442330''>So</span>
  <span m=''2442390''>minimality</span> <span m=''2442590''>is</span> <span m=''2443030''>also</span>
  <span m=''2443280''>preserved.</span> <span m=''2444200''>So</span> <span m=''2444290''>this</span>
  <span m=''2444500''>is</span> <span m=''2444890''>a</span> <span m=''2445130''>super</span>
  <span m=''2445490''>safe</span> <span m=''2445750''>operation.</span> <span m=''2448410''>I</span>
  <span m=''2448560''>won''t</span> <span m=''2448830''>prove</span> <span m=''2449030''>this.</span>
  </p><p><span m=''2449250''>But</span> <span m=''2449370''>it''s</span> <span m=''2449530''>almost</span>
  <span m=''2449860''>the</span> <span m=''2449930''>same</span> <span m=''2450160''>proof,</span>
  <span m=''2450850''>except</span> <span m=''2451220''>instead</span> <span m=''2451490''>of</span>
  <span m=''2451580''>thinking</span> <span m=''2451840''>about</span> <span m=''2452060''>G,</span>
  <span m=''2452650''>you</span> <span m=''2452790''>think</span> <span m=''2452960''>about</span>
  <span m=''2453210''>G</span> <span m=''2453430''>minus</span> <span m=''2453760''>1</span>
  <span m=''2453960''>edge,</span> <span m=''2454950''>because</span> <span m=''2455120''>that''s</span>
  <span m=''2455560''>what</span> <span m=''2455680''>you</span> <span m=''2455780''>worry</span>
  <span m=''2455950''>about</span> <span m=''2456160''>in</span> <span m=''2456250''>the</span>
  <span m=''2456330''>minimal</span> <span m=''2456640''>situation.</span> <span m=''2457200''>We''ve</span>
  <span m=''2457340''>already</span> <span m=''2457550''>shown</span> <span m=''2457810''>that</span>
  <span m=''2457870''>the</span> <span m=''2458010''>generic</span> <span m=''2458370''>rigidity</span>
  <span m=''2458800''>part</span> <span m=''2459020''>is</span> <span m=''2459140''>preserved</span>
  <span m=''2460250''>in</span> <span m=''2460370''>either</span> <span m=''2460620''>direction,</span>
  <span m=''2461710''>doing</span> <span m=''2462050''>Type</span> <span m=''2462280''>I</span>
  <span m=''2462470''>or</span> <span m=''2462600''>anti-Type</span> <span m=''2463090''>I.</span>
  <span m=''2464530''>But</span> <span m=''2464610''>for</span> <span m=''2464810''>minimality</span>
  <span m=''2466720''>right</span> <span m=''2466840''>here,</span> <span m=''2468310''>we</span>
  <span m=''2468460''>want</span> <span m=''2468630''>to</span> <span m=''2468680''>think</span>
  <span m=''2468860''>about</span> <span m=''2469130''>removing</span> <span m=''2469530''>any</span>
  <span m=''2469750''>edge,</span> <span m=''2470180''>and</span> <span m=''2470260''>whether</span>
  <span m=''2470460''>that</span> <span m=''2470650''>gives</span> <span m=''2470830''>generic</span>
  <span m=''2471150''>flexibility.</span> </p><p><span m=''2471880''>So</span> <span
  m=''2472080''>we</span> <span m=''2472160''>just</span> <span m=''2472320''>do</span>
  <span m=''2472400''>the</span> <span m=''2472500''>same</span> <span m=''2472740''>thing,</span>
  <span m=''2472970''>but</span> <span m=''2473090''>with</span> <span m=''2473230''>G</span>
  <span m=''2473370''>minus</span> <span m=''2473710''>e,</span> <span m=''2474550''>and</span>
  <span m=''2475250''>G</span> <span m=''2475440''>prime</span> <span m=''2475730''>minus</span>
  <span m=''2476040''>e,</span> <span m=''2476640''>where</span> <span m=''2476790''>e
  is</span> <span m=''2477040''>somewhere</span> <span m=''2477350''>in</span> <span
  m=''2477410''>the</span> <span m=''2477470''>old</span> <span m=''2477690''>part.</span>
  <span m=''2478630''>And</span> <span m=''2478840''>it''s the</span> <span m=''2479160''>same</span>
  <span m=''2479500''>argument.</span> <span m=''2484110''>And</span> <span m=''2484840''>so
  you''d</span> <span m=''2485290''>write</span> <span m=''2485640''>substitute</span>
  <span m=''2486300''>all instances</span> <span m=''2486860''>of</span> <span m=''2486970''>G</span>
  <span m=''2487370''>with</span> <span m=''2487660''>G minus</span> <span m=''2488140''>e.</span>
  <span m=''2491010''>That''s</span> <span m=''2492210''>pretty</span> <span m=''2492460''>old</span>
  <span m=''2492620''>and</span> <span m=''2492720''>geeky.</span> <span m=''2493060''>Probably</span>
  <span m=''2493350''>no</span> <span m=''2493470''>one</span> <span m=''2493560''>knows</span>
  <span m=''2493740''>what</span> <span m=''2493830''>that</span> <span m=''2493980''>means,</span>
  <span m=''2494350''>but</span> <span m=''2495410''>you get</span> <span m=''2495820''>the</span>
  <span m=''2495930''>idea.</span> <span m=''2498595''>All</span> <span m=''2499020''>right.</span>
  </p><p><span m=''2500500''>Now,</span> <span m=''2501290''>we</span> <span m=''2501420''>get</span>
  <span m=''2501620''>to</span> <span m=''2501720''>Type</span> <span m=''2501960''>II</span>
  <span m=''2502130''>operations.</span> <span m=''2503980''>It''s</span> <span m=''2504180''>a</span>
  <span m=''2504240''>little</span> <span m=''2504430''>more</span> <span m=''2504580''>subtle.</span>
  <span m=''2505400''>if</span> <span m=''2505600''>I</span> <span m=''2505670''>said</span>
  <span m=''2505930''>this</span> <span m=''2506110''>with</span> <span m=''2506200''>Type</span>
  <span m=''2506440''>II, it would</span> <span m=''2506860''>be false.</span> <span
  m=''2508220''>So</span> <span m=''2508790''>life</span> <span m=''2508940''>it''s</span>
  <span m=''2509030''>harder.</span> <span m=''2510110''>And</span> <span m=''2510290''>this</span>
  <span m=''2510450''>is</span> <span m=''2510580''>all</span> <span m=''2510720''>about</span>
  <span m=''2511210''>the</span> <span m=''2511280''>fact that</span> <span m=''2511550''>anti-Type</span>
  <span m=''2512130''>II</span> <span m=''2512260''>operations</span> <span m=''2512750''>are</span>
  <span m=''2512800''>not</span> <span m=''2513030''>unique,</span> <span m=''2513580''>and</span>
  <span m=''2513720''>you''ve</span> <span m=''2513830''>got</span> <span m=''2513950''>to</span>
  <span m=''2514000''>be</span> <span m=''2514120''>careful in</span> <span m=''2514480''>how</span>
  <span m=''2514610''>you</span> <span m=''2514730''>do</span> <span m=''2514900''>it.</span>
  <span m=''2516810''>It</span> <span m=''2516940''>does</span> <span m=''2517110''>work</span>
  <span m=''2517300''>in</span> <span m=''2517400''>one</span> <span m=''2517550''>direction.</span>
  <span m=''2523160''>If</span> <span m=''2523460''>the</span> <span m=''2523590''>input</span>
  <span m=''2523990''>is</span> <span m=''2524290''>minimally</span> <span m=''2524600''>generically</span>
  <span m=''2525000''>rigid,</span> <span m=''2525480''>then</span> <span m=''2525760''>the</span>
  <span m=''2525880''>new</span> <span m=''2526060''>one</span> <span m=''2526260''>will</span>
  <span m=''2526460''>be.</span> </p><p><span m=''2540070''>But</span> <span m=''2540170''>it</span>
  <span m=''2540260''>doesn''t</span> <span m=''2540490''>work</span> <span m=''2540670''>in</span>
  <span m=''2540750''>the</span> <span m=''2540890''>other</span> <span m=''2541050''>direction.</span>
  <span m=''2542200''>Now</span> <span m=''2542330''>at</span> <span m=''2542420''>this</span>
  <span m=''2542620''>point,</span> <span m=''2543170''>I''m</span> <span m=''2543540''>not</span>
  <span m=''2543690''>going</span> <span m=''2543780''>to</span> <span m=''2543850''>prove
  this.</span> <span m=''2544060''>This</span> <span m=''2544230''>is</span> <span
  m=''2544420''>actually</span> <span m=''2544970''>a</span> <span m=''2545060''>lot</span>
  <span m=''2545200''>harder</span> <span m=''2545510''>to</span> <span m=''2545580''>prove.</span>
  <span m=''2546490''>At least,</span> <span m=''2546680''>I</span> <span m=''2546750''>don''t</span>
  <span m=''2546910''>know</span> <span m=''2547170''>of</span> <span m=''2547280''>a</span>
  <span m=''2547460''>simple,</span> <span m=''2548150''>straightforward</span> <span
  m=''2548750''>proof</span> <span m=''2548970''>like</span> <span m=''2549110''>this</span>
  <span m=''2549270''>one,</span> <span m=''2549390''>where you</span> <span m=''2549560''>just</span>
  <span m=''2549740''>construct</span> <span m=''2550065''>it.</span> <span m=''2551090''>The
  easy</span> <span m=''2551390''>way</span> <span m=''2552110''>I</span> <span m=''2552200''>know</span>
  <span m=''2552340''>how</span> <span m=''2552430''>to</span> <span m=''2552520''>prove
  it</span> <span m=''2552860''>uses</span> <span m=''2554450''>next</span> <span
  m=''2554650''>class.</span> <span m=''2555610''>So</span> <span m=''2555700''>we''re</span>
  <span m=''2555830''>not</span> <span m=''2556000''>going</span> <span m=''2556110''>to</span>
  <span m=''2556420''>bother</span> <span m=''2556660''>proving</span> <span m=''2556980''>it.</span>
  <span m=''2558190''>It</span> <span m=''2558310''>should</span> <span m=''2558490''>be</span>
  <span m=''2558590''>intuitive</span> <span m=''2558960''>enough.</span> <span m=''2559620''>Certainly</span>
  <span m=''2560000''>in</span> <span m=''2560610''>thinking</span> <span m=''2560930''>about</span>
  <span m=''2561120''>degrees</span> <span m=''2561360''>of</span> <span m=''2561440''>freedom</span>
  <span m=''2561720''>it''s</span> <span m=''2561940''>correct,</span> <span m=''2562690''>but</span>
  <span m=''2563080''>you''ve</span> <span m=''2563510''>got</span> <span m=''2563640''>to</span>
  <span m=''2563700''>be</span> <span m=''2563800''>more</span> <span m=''2563980''>careful</span>
  <span m=''2564340''>than that.</span> </p><p><span m=''2567460''>I</span> <span
  m=''2567570''>want</span> <span m=''2567690''>to</span> <span m=''2567750''>talk</span>
  <span m=''2567940''>more</span> <span m=''2568130''>about</span> <span m=''2568370''>the</span>
  <span m=''2568520''>reverse</span> <span m=''2568820''>direction.</span> <span m=''2573100''>At</span>
  <span m=''2573430''>this</span> <span m=''2573610''>point,</span> <span m=''2573810''>by</span>
  <span m=''2573920''>the</span> <span m=''2574020''>way,</span> <span m=''2574120''>we</span>
  <span m=''2574290''>have</span> <span m=''2574470''>proved</span> <span m=''2576150''>one</span>
  <span m=''2576360''>direction</span> <span m=''2576740''>of</span> <span m=''2576870''>our</span>
  <span m=''2576970''>big</span> <span m=''2577170''>theorem.</span> <span m=''2579030''>We''ve</span>
  <span m=''2579250''>proved</span> <span m=''2579560''>that</span> <span m=''2579670''>if</span>
  <span m=''2579810''>you</span> <span m=''2579940''>can</span> <span m=''2580070''>build</span>
  <span m=''2580310''>something</span> <span m=''2580670''>with</span> <span m=''2580780''>these</span>
  <span m=''2580940''>two</span> <span m=''2581060''>operations,</span> <span m=''2582070''>it</span>
  <span m=''2582250''>is</span> <span m=''2582390''>minimally</span> <span m=''2582750''>generically</span>
  <span m=''2583190''>rigid,</span> <span m=''2584070''>because</span> <span m=''2585020''>when</span>
  <span m=''2585220''>we</span> <span m=''2585310''>start</span> <span m=''2585570''>out</span>
  <span m=''2586770''>with</span> <span m=''2587050''>an</span> <span m=''2587130''>edge,
  this</span> <span m=''2587360''>is</span> <span m=''2587620''>the</span> <span m=''2587700''>base</span>
  <span m=''2587980''>case</span> <span m=''2588240''>of</span> <span m=''2588350''>our</span>
  <span m=''2588460''>induction.</span> <span m=''2589470''>This</span> <span m=''2589700''>guy</span>
  <span m=''2590040''>is</span> <span m=''2590270''>minimally</span> <span m=''2590620''>generically</span>
  <span m=''2591030''>rigid.</span> </p><p><span m=''2591900''>And</span> <span m=''2592110''>then</span>
  <span m=''2592260''>every</span> <span m=''2592570''>operation</span> <span m=''2593050''>I</span>
  <span m=''2593120''>do,</span> <span m=''2593590''>I</span> <span m=''2593730''>know</span>
  <span m=''2593880''>I''m</span> <span m=''2593980''>safe,</span> <span m=''2594560''>because</span>
  <span m=''2594850''>I</span> <span m=''2594910''>start</span> <span m=''2595270''>with</span>
  <span m=''2596030''>G being</span> <span m=''2596420''>minimally</span> <span m=''2596710''>generically</span>
  <span m=''2597060''>rigid.</span> <span m=''2597310''>If</span> <span m=''2597430''>I</span>
  <span m=''2597490''>do</span> <span m=''2597620''>a</span> <span m=''2597690''>Type
  I</span> <span m=''2597940''>operation,</span> <span m=''2598550''>it</span> <span
  m=''2598730''>will</span> <span m=''2599130''>still</span> <span m=''2599420''>be</span>
  <span m=''2599580''>minimally</span> <span m=''2599920''>generically</span> <span
  m=''2600320''>rigid,</span> <span m=''2601170''>and</span> <span m=''2601480''>same</span>
  <span m=''2601690''>thing</span> <span m=''2601920''>for</span> <span m=''2602070''>Type</span>
  <span m=''2602280''>II</span> <span m=''2602420''>operations.</span> <span m=''2603030''>So
  in</span> <span m=''2603130''>that</span> <span m=''2603290''>direction,</span>
  <span m=''2604200''>we''re</span> <span m=''2604340''>golden.</span> </p><p><span
  m=''2605940''>But</span> <span m=''2606060''>I''d</span> <span m=''2606170''>really</span>
  <span m=''2606370''>like</span> <span m=''2606600''>to</span> <span m=''2606710''>know,</span>
  <span m=''2606920''>is</span> <span m=''2607060''>there</span> <span m=''2609910''>some</span>
  <span m=''2610200''>converse</span> <span m=''2610660''>of</span> <span m=''2610840''>three,</span>
  <span m=''2612100''>this</span> <span m=''2612240''>third</span> <span m=''2612450''>property?</span>
  <span m=''2613620''>And</span> <span m=''2613910''>I</span> <span m=''2613960''>will</span>
  <span m=''2614110''>tell</span> <span m=''2614300''>you</span> <span m=''2614670''>a</span>
  <span m=''2614770''>converse</span> <span m=''2615240''>of the</span> <span m=''2615380''>third</span>
  <span m=''2615620''>property.</span> <span m=''2617450''>Suppose</span> <span m=''2618690''>I</span>
  <span m=''2618830''>have</span> <span m=''2620780''>a</span> <span m=''2620950''>minimally</span>
  <span m=''2622510''>generically</span> <span m=''2624020''>rigid</span> <span m=''2624380''>graph</span>
  <span m=''2625410''>G</span> <span m=''2625640''>prime.</span> <span m=''2626990''>And</span>
  <span m=''2627140''>I''m</span> <span m=''2627210''>not</span> <span m=''2627390''>assuming</span>
  <span m=''2627750''>that it''s</span> <span m=''2627950''>made</span> <span m=''2628150''>from</span>
  <span m=''2628310''>a</span> <span m=''2628370''>Type II</span> <span m=''2628630''>operation</span>
  <span m=''2629150''>yet.</span> <span m=''2631460''>But</span> <span m=''2631620''>suppose</span>
  <span m=''2632780''>it</span> <span m=''2632910''>has</span> <span m=''2633250''>a</span>
  <span m=''2633310''>degree-3</span> <span m=''2633890''>vertex--</span> <span m=''2635550''>vertex</span>
  <span m=''2635875''>with</span> <span m=''2636200''>three</span> <span m=''2636490''>incident</span>
  <span m=''2636880''>edges.</span> <span m=''2642290''>Then</span> <span m=''2645690''>G</span>
  <span m=''2645880''>prime</span> <span m=''2648490''>is</span> <span m=''2648860''>the
  result</span> <span m=''2652080''>of a</span> <span m=''2652200''>Type</span> <span
  m=''2652460''>II</span> <span m=''2652620''>operation</span> <span m=''2658330''>of</span>
  <span m=''2659810''>some</span> <span m=''2662560''>minimally</span> <span m=''2664220''>generically</span>
  <span m=''2666000''>rigid</span> <span m=''2668030''>graph</span> <span m=''2668540''>G.</span>
  <span m=''2673450''>So</span> <span m=''2673600''>this</span> <span m=''2673820''>is</span>
  <span m=''2673920''>saying</span> <span m=''2675470''>that</span> <span m=''2676840''>there</span>
  <span m=''2677040''>is</span> <span m=''2677160''>hope</span> <span m=''2677660''>in</span>
  <span m=''2677820''>working</span> <span m=''2678130''>backwards.</span> </p><p><span
  m=''2679450''>Here</span> <span m=''2679760''>I</span> <span m=''2679810''>had</span>
  <span m=''2680000''>two</span> <span m=''2680160''>choices</span> <span m=''2680590''>of</span>
  <span m=''2680690''>Type II</span> <span m=''2680930''>operations.</span> <span
  m=''2681580''>I</span> <span m=''2681660''>think</span> <span m=''2681850''>in</span>
  <span m=''2681940''>this</span> <span m=''2682090''>case, it</span> <span m=''2682340''>didn''t</span>
  <span m=''2682540''>actually</span> <span m=''2682800''>matter,</span> <span m=''2683140''>but</span>
  <span m=''2683260''>in</span> <span m=''2683360''>general,</span> <span m=''2683680''>it</span>
  <span m=''2683740''>matters</span> <span m=''2684060''>which</span> <span m=''2684210''>one</span>
  <span m=''2684370''>you</span> <span m=''2684480''>choose.</span> <span m=''2686330''>And</span>
  <span m=''2689610''>this</span> <span m=''2689790''>is</span> <span m=''2689890''>saying</span>
  <span m=''2690290''>there</span> <span m=''2690440''>is</span> <span m=''2690720''>a</span>
  <span m=''2690790''>choice,</span> <span m=''2691330''>there</span> <span m=''2691490''>is</span>
  <span m=''2691680''>an</span> <span m=''2691780''>anti-Type</span> <span m=''2692590''>II</span>
  <span m=''2692780''>operation,</span> <span m=''2693130''>a</span> <span m=''2693480''>backwards</span>
  <span m=''2693980''>II</span> <span m=''2694140''>operation,</span> <span m=''2695730''>that</span>
  <span m=''2695930''>results</span> <span m=''2696550''>in</span> <span m=''2696670''>something</span>
  <span m=''2696990''>that</span> <span m=''2697110''>is</span> <span m=''2697190''>minimally</span>
  <span m=''2697550''>generically</span> <span m=''2697980''>rigid.</span> <span m=''2698680''>And</span>
  <span m=''2698840''>if</span> <span m=''2698930''>it''s</span> <span m=''2699050''>minimally</span>
  <span m=''2699350''>generically</span> <span m=''2699770''>rigid,</span> <span m=''2700310''>by</span>
  <span m=''2700440''>induction,</span> <span m=''2701190''>I</span> <span m=''2701300''>can</span>
  <span m=''2701460''>keep</span> <span m=''2701640''>going</span> <span m=''2701950''>on.</span>
  <span m=''2702560''>And</span> <span m=''2702650''>so</span> <span m=''2702740''>eventually</span>
  <span m=''2703140''>I</span> <span m=''2703200''>will</span> <span m=''2703400''>get</span>
  <span m=''2703540''>back</span> <span m=''2703760''>to</span> <span m=''2703820''>start.</span>
  <span m=''2705010''>And</span> <span m=''2705100''>this</span> <span m=''2705260''>is</span>
  <span m=''2705360''>what</span> <span m=''2705590''>we</span> <span m=''2705750''>need</span>
  <span m=''2706060''>to</span> <span m=''2706310''>show</span> <span m=''2707360''>in</span>
  <span m=''2707610''>order</span> <span m=''2707780''>to</span> <span m=''2707900''>believe</span>
  <span m=''2708440''>one</span> <span m=''2708690''>half</span> <span m=''2708930''>of</span>
  <span m=''2709020''>this</span> <span m=''2709200''>theorem</span> <span m=''2709560''>that</span>
  <span m=''2710500''>if</span> <span m=''2710700''>your</span> <span m=''2710840''>thing</span>
  <span m=''2711030''>is</span> <span m=''2711110''>minimally</span> <span m=''2711420''>generically</span>
  <span m=''2711790''>rigid,</span> <span m=''2712050''>there</span> <span m=''2712230''>is</span>
  <span m=''2712320''>a</span> <span m=''2712390''>way</span> <span m=''2712520''>to</span>
  <span m=''2712600''>build</span> <span m=''2712900''>it</span> <span m=''2713250''>like</span>
  <span m=''2713480''>this.</span> </p><p><span m=''2716030''>And</span> <span m=''2716250''>the</span>
  <span m=''2716330''>way</span> <span m=''2716440''>you</span> <span m=''2716530''>build</span>
  <span m=''2716810''>it</span> <span m=''2716900''>is</span> <span m=''2717040''>if</span>
  <span m=''2717150''>there''s</span> <span m=''2717280''>a</span> <span m=''2717340''>Type</span>
  <span m=''2717560''>I</span> <span m=''2717700''>operation--</span> <span m=''2718940''>anti-Type</span>
  <span m=''2719430''>I</span> <span m=''2719580''>operation</span> <span m=''2719980''>do</span>
  <span m=''2720100''>that.</span> <span m=''2720480''>If</span> <span m=''2720720''>there''s</span>
  <span m=''2720890''>an</span> <span m=''2720940''>anti-Type</span> <span m=''2721350''>II</span>
  <span m=''2721490''>operation,</span> <span m=''2723610''>do</span> <span m=''2723770''>the</span>
  <span m=''2723930''>right</span> <span m=''2724160''>one.</span> <span m=''2725320''>Let</span>
  <span m=''2725550''>the</span> <span m=''2725640''>right</span> <span m=''2725820''>one</span>
  <span m=''2726010''>in.</span> <span m=''2726550''>Do</span> <span m=''2726710''>the</span>
  <span m=''2727120''>right</span> <span m=''2727700''>instance</span> <span m=''2728450''>of</span>
  <span m=''2728600''>an</span> <span m=''2728690''>anti-Type</span> <span m=''2729150''>II</span>
  <span m=''2729330''>operation</span> <span m=''2730640''>that</span> <span m=''2730900''>gives</span>
  <span m=''2731070''>you</span> <span m=''2731190''>something</span> <span m=''2731570''>that''s</span>
  <span m=''2731680''>minimally</span> <span m=''2732010''>generically</span> <span
  m=''2732420''>rigid.</span> <span m=''2732720''>If</span> <span m=''2732860''>you</span>
  <span m=''2733050''>preserve</span> <span m=''2733470''>minimal</span> <span m=''2733790''>generic</span>
  <span m=''2734140''>rigidity,</span> <span m=''2734560''>you know you</span> <span
  m=''2734950''>can</span> <span m=''2735100''>keep</span> <span m=''2735290''>going,</span>
  <span m=''2736160''>because</span> <span m=''2736280''>you</span> <span m=''2736350''>have</span>
  <span m=''2736440''>a</span> <span m=''2736490''>smaller</span> <span m=''2736850''>graph</span>
  <span m=''2737800''>And</span> <span m=''2738170''>so</span> <span m=''2738310''>by</span>
  <span m=''2738470''>induction</span> <span m=''2738860''>you</span> <span m=''2738990''>can</span>
  <span m=''2739110''>keep</span> <span m=''2739270''>going.</span> </p><p><span m=''2743000''>I''m</span>
  <span m=''2743110''>not</span> <span m=''2743260''>going</span> <span m=''2743360''>to</span>
  <span m=''2743420''>prove</span> <span m=''2743620''>four</span> <span m=''2743920''>either,</span>
  <span m=''2744850''>because</span> <span m=''2745040''>it</span> <span m=''2746820''>again</span>
  <span m=''2747120''>uses</span> <span m=''2747510''>technology</span> <span m=''2748070''>we</span>
  <span m=''2748230''>haven''t</span> <span m=''2748510''>yet</span> <span m=''2748700''>developed.</span>
  <span m=''2751610''>But</span> <span m=''2751750''>there''s</span> <span m=''2751910''>one</span>
  <span m=''2752240''>more</span> <span m=''2752910''>part</span> <span m=''2753240''>of</span>
  <span m=''2753360''>this</span> <span m=''2753540''>theorem</span> <span m=''2753820''>that</span>
  <span m=''2753930''>we</span> <span m=''2754010''>haven''t</span> <span m=''2754150''>proved.</span>
  <span m=''2756820''>This</span> <span m=''2756950''>sounds</span> <span m=''2757260''>great.</span>
  <span m=''2757860''>We</span> <span m=''2758050''>do</span> <span m=''2758340''>anti-type</span>
  <span m=''2758930''>I</span> <span m=''2759090''>operations.</span> <span m=''2761460''>When
  can</span> <span m=''2761770''>we</span> <span m=''2761900''>do</span> <span m=''2762020''>those?</span>
  <span m=''2762590''>We</span> <span m=''2762720''>can</span> <span m=''2762840''>do</span>
  <span m=''2762970''>those</span> <span m=''2763320''>when</span> <span m=''2764530''>we</span>
  <span m=''2764650''>have</span> <span m=''2764830''>a</span> <span m=''2764860''>vertex</span>
  <span m=''2765270''>of</span> <span m=''2765350''>degree-2.</span> <span m=''2766200''>Then</span>
  <span m=''2766410''>we</span> <span m=''2766540''>can</span> <span m=''2766970''>get</span>
  <span m=''2767120''>rid</span> <span m=''2767270''>of</span> <span m=''2767390''>it.</span>
  <span m=''2768530''>And</span> <span m=''2768770''>what</span> <span m=''2769430''>property</span>
  <span m=''2769920''>four</span> <span m=''2770190''>over</span> <span m=''2770330''>there</span>
  <span m=''2770590''>says</span> <span m=''2771080''>that</span> <span m=''2771320''>if</span>
  <span m=''2771480''>I</span> <span m=''2771540''>have</span> <span m=''2771810''>a</span>
  <span m=''2771850''>vertex</span> <span m=''2772270''>of</span> <span m=''2772380''>degree-3,</span>
  <span m=''2773420''>I</span> <span m=''2773520''>can</span> <span m=''2773670''>get</span>
  <span m=''2773800''>rid</span> <span m=''2773940''>of</span> <span m=''2774040''>it,</span>
  <span m=''2774250''>and</span> <span m=''2774380''>add</span> <span m=''2774550''>some</span>
  <span m=''2774780''>edge to</span> <span m=''2775100''>compensate.</span> <span
  m=''2776930''>But</span> <span m=''2777050''>what</span> <span m=''2777190''>if</span>
  <span m=''2777310''>I</span> <span m=''2777360''>don''t</span> <span m=''2777510''>have</span>
  <span m=''2777730''>any</span> <span m=''2777870''>vertices</span> <span m=''2778320''>of</span>
  <span m=''2778410''>degree-2</span> <span m=''2778890''>or</span> <span m=''2779010''>3?</span>
  <span m=''2780620''>That</span> <span m=''2780800''>would</span> <span m=''2781220''>suck.</span>
  </p><p><span m=''2793150''>So</span> <span m=''2793560''>this</span> <span m=''2793780''>is</span>
  <span m=''2793930''>now</span> <span m=''2794350''>the</span> <span m=''2795470''>other</span>
  <span m=''2795770''>half</span> <span m=''2797000''>of</span> <span m=''2797130''>this</span>
  <span m=''2797340''>theorem.</span> <span m=''2802310''>All</span> <span m=''2802430''>right.</span>
  <span m=''2802920''>Well,</span> <span m=''2803820''>we</span> <span m=''2804000''>know</span>
  <span m=''2804390''>by</span> <span m=''2804550''>the</span> <span m=''2804630''>thing</span>
  <span m=''2804850''>I</span> <span m=''2804880''>just</span> <span m=''2805110''>erased</span>
  <span m=''2806120''>that</span> <span m=''2806470''>the</span> <span m=''2806570''>number</span>
  <span m=''2806850''>of</span> <span m=''2806920''>edges</span> <span m=''2809790''>is</span>
  <span m=''2809900''>2n</span> <span m=''2810150''>minus</span> <span m=''2810430''>3.</span>
  <span m=''2810580''>So</span> <span m=''2810750''>just</span> <span m=''2811000''>to</span>
  <span m=''2811030''>recall,</span> <span m=''2811620''>we''re</span> <span m=''2811800''>assuming</span>
  <span m=''2812150''>now</span> <span m=''2812360''>we</span> <span m=''2812450''>have</span>
  <span m=''2812670''>something</span> <span m=''2812980''>that''s</span> <span m=''2813120''>minimally</span>
  <span m=''2813460''>generically</span> <span m=''2813910''>rigid.</span> <span m=''2814970''>We</span>
  <span m=''2815140''>already</span> <span m=''2815340''>did</span> <span m=''2815520''>a</span>
  <span m=''2816130''>degree</span> <span m=''2816420''>of</span> <span m=''2816500''>freedom</span>
  <span m=''2816790''>analysis</span> <span m=''2817220''>to</span> <span m=''2817310''>show</span>
  <span m=''2817760''>the</span> <span m=''2818000''>number</span> <span m=''2818260''>edges</span>
  <span m=''2818480''>must</span> <span m=''2818730''>be</span> <span m=''2818860''>2n</span>
  <span m=''2819140''>minus</span> <span m=''2819460''>3.</span> </p><p><span m=''2820690''>Now,</span>
  <span m=''2820970''>we</span> <span m=''2821080''>need</span> <span m=''2821300''>to</span>
  <span m=''2821400''>somehow</span> <span m=''2821740''>find</span> <span m=''2822140''>either</span>
  <span m=''2822340''>an</span> <span m=''2822400''>anti-Type</span> <span m=''2822860''>I</span>
  <span m=''2823040''>operation</span> <span m=''2823550''>or an anti-Type</span>
  <span m=''2824130''>II</span> <span m=''2824280''>operation</span> <span m=''2824780''>so
  that</span> <span m=''2824990''>we</span> <span m=''2825090''>can</span> <span m=''2825630''>go</span>
  <span m=''2825780''>all</span> <span m=''2825930''>the</span> <span m=''2826020''>way</span>
  <span m=''2826200''>to</span> <span m=''2826470''>a</span> <span m=''2826530''>single</span>
  <span m=''2826850''>edge</span> <span m=''2827560''>and</span> <span m=''2827780''>find</span>
  <span m=''2828100''>a</span> <span m=''2828230''>Henneberg</span> <span m=''2828540''>construction.</span>
  <span m=''2835870''>Any</span> <span m=''2836020''>suggestions?</span> <span m=''2839150''>People</span>
  <span m=''2839240''>know</span> <span m=''2839380''>graph</span> <span m=''2839600''>theory?</span>
  <span m=''2846378''>All right.</span> <span m=''2846880''>On</span> <span m=''2847120''>the</span>
  <span m=''2847200''>one</span> <span m=''2847360''>hand,</span> <span m=''2847730''>we</span>
  <span m=''2847830''>have</span> <span m=''2847980''>the</span> <span m=''2848040''>number</span>
  <span m=''2848290''>of</span> <span m=''2848360''>edges,</span> <span m=''2849890''>and</span>
  <span m=''2850020''>the</span> <span m=''2850130''>other</span> <span m=''2850290''>hand,</span>
  <span m=''2850840''>we</span> <span m=''2850900''>care</span> <span m=''2851180''>about</span>
  <span m=''2851480''>the</span> <span m=''2851560''>degrees</span> <span m=''2851960''>of</span>
  <span m=''2852030''>vertices.</span> <span m=''2853470''>Anyone</span> <span m=''2853670''>know</span>
  <span m=''2853790''>a</span> <span m=''2853950''>relation</span> <span m=''2854370''>between</span>
  <span m=''2854670''>those</span> <span m=''2854850''>two</span> <span m=''2854960''>things?</span>
  <span m=''2858830''>Yeah.</span> </p><p><span m=''2859839''>AUDIENCE: Two.</span>
  <span m=''2861246''>Every</span> <span m=''2861715''>edge contributes</span> <span
  m=''2862653''>two</span> <span m=''2863122''>to the total</span> <span m=''2863591''>Henneberg</span>
  <span m=''2864529''>[INAUDIBLE].</span> </p><p><span m=''2865940''>PROFESSOR: If</span>
  <span m=''2866020''>I</span> <span m=''2866100''>take</span> <span m=''2866430''>the</span>
  <span m=''2866510''>sum</span> <span m=''2867530''>of</span> <span m=''2867680''>the</span>
  <span m=''2867780''>degrees</span> <span m=''2869070''>of</span> <span m=''2869460''>the</span>
  <span m=''2869540''>vertices--</span> <span m=''2871590''>sum</span> <span m=''2871860''>over
  all</span> <span m=''2872230''>vertices--</span> <span m=''2874520''>this</span>
  <span m=''2874710''>is</span> <span m=''2874760''>really</span> <span m=''2874980''>intuitive.</span>
  <span m=''2876260''>I</span> <span m=''2876360''>add</span> <span m=''2876670''>up</span>
  <span m=''2877240''>how</span> <span m=''2877440''>many</span> <span m=''2877610''>edges
  are</span> <span m=''2878100''>incident to</span> <span m=''2878290''>this</span>
  <span m=''2878460''>vertex,</span> <span m=''2878900''>then</span> <span m=''2879030''>I</span>
  <span m=''2879100''>add</span> <span m=''2879340''>up</span> <span m=''2879470''>how</span>
  <span m=''2879670''>many</span> <span m=''2879900''>edges</span> <span m=''2880180''>are</span>
  <span m=''2880270''>incident</span> <span m=''2880620''>to</span> <span m=''2880670''>this</span>
  <span m=''2880860''>vertex,</span> <span m=''2881810''>then I</span> <span m=''2881970''>add</span>
  <span m=''2882140''>up</span> <span m=''2882300''>how</span> <span m=''2882450''>many</span>
  <span m=''2882690''>edges</span> <span m=''2882950''>are</span> <span m=''2883050''>incident</span>
  <span m=''2883380''>to</span> <span m=''2883460''>this</span> <span m=''2883670''>vertex.</span>
  <span m=''2884610''>I</span> <span m=''2884740''>count</span> <span m=''2885020''>every</span>
  <span m=''2885270''>edge</span> <span m=''2885440''>twice,</span> <span m=''2885860''>because</span>
  <span m=''2886030''>it has</span> <span m=''2886220''>two</span> <span m=''2886390''>ends.</span>
  <span m=''2887560''>So</span> <span m=''2887840''>some</span> <span m=''2888080''>of</span>
  <span m=''2888150''>the</span> <span m=''2888220''>degrees</span> <span m=''2889080''>is</span>
  <span m=''2889300''>twice</span> <span m=''2889930''>the</span> <span m=''2890000''>number</span>
  <span m=''2890290''>of</span> <span m=''2890360''>edges.</span> <span m=''2890720''>I''ll
  write</span> <span m=''2891220''>that</span> <span m=''2891300''>this</span> <span
  m=''2891480''>way.</span> <span m=''2892430''>E is</span> <span m=''2892780''>the</span>
  <span m=''2892980''>set</span> <span m=''2893220''>of</span> <span m=''2893320''>edges</span>
  <span m=''2893735''>that''s</span> <span m=''2894020''>the</span> <span m=''2894120''>size</span>
  <span m=''2894470''>of</span> <span m=''2894530''>that.</span> </p><p><span m=''2895940''>This</span>
  <span m=''2896170''>is</span> <span m=''2896290''>called</span> <span m=''2896570''>the</span>
  <span m=''2896630''>handshaking</span> <span m=''2897200''>lemma.</span> <span m=''2897610''>It</span>
  <span m=''2897870''>says</span> <span m=''2898200''>if</span> <span m=''2898300''>everyone</span>
  <span m=''2898820''>in</span> <span m=''2898910''>this</span> <span m=''2899070''>room</span>
  <span m=''2899400''>shakes</span> <span m=''2899790''>hands</span> <span m=''2900080''>with</span>
  <span m=''2900200''>everyone</span> <span m=''2900540''>else--</span> <span m=''2901310''>if</span>
  <span m=''2901520''>I</span> <span m=''2901600''>go</span> <span m=''2901780''>around
  and</span> <span m=''2901990''>shake</span> <span m=''2902190''>hands with</span>
  <span m=''2902430''>everybody--</span> <span m=''2903280''>the</span> <span m=''2903390''>total</span>
  <span m=''2903650''>number</span> <span m=''2903860''>of</span> <span m=''2903900''>handshakes</span>
  <span m=''2904380''>will</span> <span m=''2904490''>be</span> <span m=''2908990''>twice</span>
  <span m=''2909340''>the</span> <span m=''2909440''>number</span> <span m=''2909820''>of</span>
  <span m=''2909880''>pairs</span> <span m=''2910160''>of</span> <span m=''2910240''>people</span>
  <span m=''2910580''>that</span> <span m=''2910750''>shook</span> <span m=''2910890''>hands.</span>
  <span m=''2911500''>No.</span> <span m=''2912860''>If</span> <span m=''2913030''>we</span>
  <span m=''2913160''>do</span> <span m=''2913350''>some</span> <span m=''2913710''>set</span>
  <span m=''2913980''>of</span> <span m=''2914750''>handshakes--</span> <span m=''2916110''>so</span>
  <span m=''2916330''>that''s</span> <span m=''2916590''>the</span> <span m=''2916680''>graph</span>
  <span m=''2916970''>scenario.</span> <span m=''2917540''>So</span> <span m=''2917650''>some
  of us</span> <span m=''2918040''>shake</span> <span m=''2918280''>hands,</span>
  <span m=''2920440''>and</span> <span m=''2920620''>I</span> <span m=''2920850''>count</span>
  <span m=''2921220''>how</span> <span m=''2921330''>many</span> <span m=''2921510''>handshakes</span>
  <span m=''2921890''>I</span> <span m=''2922020''>did,</span> <span m=''2922480''>and</span>
  <span m=''2923020''>everybody</span> <span m=''2923440''>counts</span> <span m=''2923680''>how</span>
  <span m=''2923770''>many</span> <span m=''2923930''>handshakes</span> <span m=''2924490''>they</span>
  <span m=''2924620''>did,</span> <span m=''2924870''>we</span> <span m=''2925000''>add</span>
  <span m=''2925200''>them</span> <span m=''2925330''>all</span> <span m=''2925500''>up,</span>
  <span m=''2926210''>it</span> <span m=''2926310''>will</span> <span m=''2926320''>be</span>
  <span m=''2926470''>exactly</span> <span m=''2926880''>twice</span> <span m=''2927300''>the</span>
  <span m=''2927390''>number</span> <span m=''2927610''>of</span> <span m=''2927680''>actual</span>
  <span m=''2927950''>handshakes</span> <span m=''2928380''>that</span> <span m=''2928490''>took</span>
  <span m=''2928660''>place.</span> <span m=''2929600''>That''s this</span> <span
  m=''2929860''>statement.</span> <span m=''2931220''>That''s</span> <span m=''2931370''>why</span>
  <span m=''2931470''>it''s</span> <span m=''2931570''>called</span> <span m=''2931720''>the</span>
  <span m=''2931770''>handshaking</span> <span m=''2932260''>lemma.</span> </p><p><span
  m=''2934920''>This</span> <span m=''2935130''>is</span> <span m=''2935250''>good</span>
  <span m=''2935420''>news,</span> <span m=''2935820''>because</span> <span m=''2936190''>we</span>
  <span m=''2936330''>know</span> <span m=''2936560''>this</span> <span m=''2936960''>number</span>
  <span m=''2937330''>is</span> <span m=''2937800''>4n</span> <span m=''2938160''>minus</span>
  <span m=''2938470''>6</span> <span m=''2940160''>here.</span> <span m=''2942800''>So</span>
  <span m=''2943680''>what</span> <span m=''2943920''>could</span> <span m=''2944070''>these</span>
  <span m=''2944260''>degrees</span> <span m=''2944630''>look</span> <span m=''2944850''>like?</span>
  <span m=''2945410''>There''s</span> <span m=''2945600''>n</span> <span m=''2945830''>of</span>
  <span m=''2945960''>them.</span> <span m=''2947320''>Number</span> <span m=''2947600''>of</span>
  <span m=''2948000''>vertices</span> <span m=''2948730''>is n.</span> <span m=''2949040''>That''s</span>
  <span m=''2949430''>the</span> <span m=''2949510''>neat</span> <span m=''2949840''>definition</span>
  <span m=''2950300''>of</span> <span m=''2950390''>n.</span> <span m=''2951930''>So</span>
  <span m=''2952130''>on</span> <span m=''2952280''>average</span> <span m=''2954320''>what</span>
  <span m=''2954500''>could</span> <span m=''2954600''>these</span> <span m=''2954760''>degrees</span>
  <span m=''2955070''>be?</span> <span m=''2955230''>They</span> <span m=''2955350''>have</span>
  <span m=''2955560''>to</span> <span m=''2955670''>be</span> <span m=''2955780''>less</span>
  <span m=''2956040''>than</span> <span m=''2956160''>four.</span> </p><p><span m=''2957396''>The</span>
  <span m=''2957760''>average</span> <span m=''2958220''>degree</span> <span m=''2961940''>has</span>
  <span m=''2962150''>to</span> <span m=''2962250''>be</span> <span m=''2962360''>at</span>
  <span m=''2962410''>least</span> <span m=''2962630''>a</span> <span m=''2962690''>little</span>
  <span m=''2963080''>bit</span> <span m=''2963240''>less</span> <span m=''2963480''>than</span>
  <span m=''2963610''>four,</span> <span m=''2964340''>because</span> <span m=''2964610''>in</span>
  <span m=''2964790''>summation,</span> <span m=''2965400''>you</span> <span m=''2965500''>get</span>
  <span m=''2965670''>4n</span> <span m=''2966420''>minus</span> <span m=''2966720''>a</span>
  <span m=''2966790''>little</span> <span m=''2967040''>bit.</span> <span m=''2968550''>So</span>
  <span m=''2968610''>the</span> <span m=''2968760''>average</span> <span m=''2969210''>degree</span>
  <span m=''2969460''>in</span> <span m=''2969550''>the</span> <span m=''2969690''>summation</span>
  <span m=''2970120''>must</span> <span m=''2970330''>be</span> <span m=''2970430''>a</span>
  <span m=''2970490''>little</span> <span m=''2970680''>bit</span> <span m=''2970830''>less
  than</span> <span m=''2971030''>four.</span> <span m=''2971460''>Now,</span> <span
  m=''2971570''>some</span> <span m=''2971810''>of</span> <span m=''2971860''>them</span>
  <span m=''2972000''>are</span> <span m=''2972070''>bigger,</span> <span m=''2972480''>some</span>
  <span m=''2972560''>of</span> <span m=''2972600''>them</span> <span m=''2972760''>are</span>
  <span m=''2972840''>smaller.</span> <span m=''2973860''>But</span> <span m=''2973970''>if</span>
  <span m=''2974040''>the</span> <span m=''2974160''>average is</span> <span m=''2974510''>less
  than</span> <span m=''2974820''>four,</span> <span m=''2975040''>then</span> <span
  m=''2975180''>in</span> <span m=''2975280''>particular,</span> <span m=''2975640''>there</span>
  <span m=''2975750''>must</span> <span m=''2975940''>be</span> <span m=''2976050''>one</span>
  <span m=''2976340''>guy</span> <span m=''2976540''>less than</span> <span m=''2976910''>four.</span>
  </p><p><span m=''2979570''>Some</span> <span m=''2979910''>vertex</span> <span m=''2983380''>has</span>
  <span m=''2984010''>degree</span> <span m=''2986460''>less</span> <span m=''2986710''>than</span>
  <span m=''2986890''>four.</span> <span m=''2987660''>So</span> <span m=''2987830''>it</span>
  <span m=''2987890''>could</span> <span m=''2988070''>either</span> <span m=''2988330''>be</span>
  <span m=''2989020''>zero,</span> <span m=''2989460''>one,</span> <span m=''2989930''>two,</span>
  <span m=''2990310''>or</span> <span m=''2990410''>three.</span> <span m=''2991350''>Two</span>
  <span m=''2991630''>and</span> <span m=''2991790''>three,</span> <span m=''2992490''>we''re</span>
  <span m=''2992680''>OK.</span> <span m=''2993640''>One</span> <span m=''2995290''>can''t</span>
  <span m=''2995520''>happen,</span> <span m=''2996060''>because</span> <span m=''2996420''>we</span>
  <span m=''2996570''>are</span> <span m=''2996690''>supposed</span> <span m=''2997060''>to</span>
  <span m=''2997100''>be</span> <span m=''2997210''>minimally</span> <span m=''2997580''>generically</span>
  <span m=''2997990''>rigid.</span> <span m=''2998700''>If</span> <span m=''2998860''>I</span>
  <span m=''2998920''>have</span> <span m=''2999070''>a</span> <span m=''2999110''>degree1</span>
  <span m=''2999590''>vertex</span> <span m=''3000820''>and</span> <span m=''3000930''>some</span>
  <span m=''3001050''>stuff,</span> <span m=''3001820''>this</span> <span m=''3002000''>guy</span>
  <span m=''3002120''>can</span> <span m=''3002330''>spin</span> <span m=''3002560''>around.</span>
  <span m=''3003040''>It''s</span> <span m=''3003180''>not</span> <span m=''3003360''>minimally</span>
  <span m=''3003690''>generically</span> <span m=''3004060''>rigid.</span> <span m=''3004600''>If
  I have a</span> <span m=''3004800''>degree-0</span> <span m=''3005310''>vertex,</span>
  <span m=''3005860''>it</span> <span m=''3005990''>can</span> <span m=''3006170''>float</span>
  <span m=''3006410''>around.</span> <span m=''3007040''>It''s not</span> <span m=''3007270''>minimally</span>
  <span m=''3007630''>generically</span> <span m=''3008060''>rigid,</span> <span m=''3008960''>assuming</span>
  <span m=''3009210''>you</span> <span m=''3009280''>have</span> <span m=''3009380''>more</span>
  <span m=''3009540''>than</span> <span m=''3009650''>one</span> <span m=''3009820''>vertex.</span>
  </p><p><span m=''3011160''>So</span> <span m=''3012310''>I</span> <span m=''3012340''>guess</span>
  <span m=''3012560''>this</span> <span m=''3012740''>is</span> <span m=''3012950''>the</span>
  <span m=''3013060''>situation</span> <span m=''3013620''>where</span> <span m=''3014240''>you</span>
  <span m=''3014350''>have</span> <span m=''3014460''>more</span> <span m=''3014660''>than</span>
  <span m=''3014790''>one</span> <span m=''3014960''>vertex,</span> <span m=''3016070''>otherwise</span>
  <span m=''3016370''>you</span> <span m=''3016470''>can''t</span> <span m=''3016720''>build</span>
  <span m=''3016920''>it</span> <span m=''3017040''>from</span> <span m=''3017190''>a</span>
  <span m=''3017240''>single</span> <span m=''3017510''>edge.</span> <span m=''3018740''>Assuming</span>
  <span m=''3019030''>you</span> <span m=''3019120''>have--</span> <span m=''3020470''>so</span>
  <span m=''3020590''>I should</span> <span m=''3020760''>put</span> <span m=''3020980''>n</span>
  <span m=''3021280''>greater</span> <span m=''3021550''>than</span> <span m=''3021740''>one</span>
  <span m=''3022020''>here.</span> <span m=''3025590''>So</span> <span m=''3025920''>then</span>
  <span m=''3026120''>you</span> <span m=''3026220''>get</span> <span m=''3026360''>a</span>
  <span m=''3026420''>degree2</span> <span m=''3026840''>vertex</span> <span m=''3027230''>or
  a</span> <span m=''3027320''>degree-3</span> <span m=''3027740''>vertex.</span>
  <span m=''3028660''>You</span> <span m=''3028850''>use</span> <span m=''3029140''>either</span>
  <span m=''3029420''>property</span> <span m=''3030640''>two</span> <span m=''3031250''>or</span>
  <span m=''3031380''>property</span> <span m=''3031800''>four</span> <span m=''3034450''>to</span>
  <span m=''3034750''>make</span> <span m=''3035550''>an</span> <span m=''3035700''>anti-Type</span>
  <span m=''3036270''>I</span> <span m=''3036520''>or anti-Type</span> <span m=''3037130''>II</span>
  <span m=''3037290''>operation.</span> <span m=''3038550''>You''ll</span> <span m=''3038690''>still</span>
  <span m=''3038980''>have</span> <span m=''3039140''>a</span> <span m=''3039200''>minimally</span>
  <span m=''3039550''>generically</span> <span m=''3039970''>rigid</span> <span m=''3040200''>graph.</span>
  <span m=''3040830''>You</span> <span m=''3040930''>keep</span> <span m=''3041140''>going.</span>
  <span m=''3041810''>By</span> <span m=''3041960''>the</span> <span m=''3042120''>end,</span>
  <span m=''3042820''>you''ll</span> <span m=''3043170''>have</span> <span m=''3043440''>a</span>
  <span m=''3043500''>single</span> <span m=''3043780''>edge.</span> </p><p><span
  m=''3044750''>That''s</span> <span m=''3044920''>the</span> <span m=''3045040''>only</span>
  <span m=''3045230''>case</span> <span m=''3045530''>when</span> <span m=''3045680''>you</span>
  <span m=''3045790''>get</span> <span m=''3045970''>stuck,</span> <span m=''3046750''>because</span>
  <span m=''3046930''>actually--</span> <span m=''3047560''>see, I</span> <span m=''3047920''>lied.</span>
  <span m=''3048620''>Here,</span> <span m=''3048900''>I</span> <span m=''3048960''>have</span>
  <span m=''3049140''>two</span> <span m=''3049810''>degree-1</span> <span m=''3050230''>vertices.</span>
  <span m=''3050810''>That''s</span> <span m=''3051010''>the</span> <span m=''3051370''>only</span>
  <span m=''3051650''>situation</span> <span m=''3052290''>where</span> <span m=''3052410''>you</span>
  <span m=''3052540''>can</span> <span m=''3052680''>have</span> <span m=''3053600''>degree-1</span>
  <span m=''3054030''>vertices.</span> <span m=''3055400''>And</span> <span m=''3057410''>that''s</span>
  <span m=''3057620''>when</span> <span m=''3057720''>you</span> <span m=''3057800''>get</span>
  <span m=''3057970''>stuck.</span> <span m=''3058950''>You have two</span> <span
  m=''3059140''>degree-1</span> <span m=''3059580''>vertices,</span> <span m=''3059950''>but</span>
  <span m=''3060080''>then</span> <span m=''3060250''>I</span> <span m=''3060320''>have</span>
  <span m=''3060500''>an</span> <span m=''3060590''>edge.</span> <span m=''3060910''>I''m</span>
  <span m=''3061230''>done.</span> <span m=''3065180''>Questions?</span> <span m=''3067630''>Obviously,</span>
  <span m=''3068040''>I</span> <span m=''3068340''>elided</span> <span m=''3068990''>a</span>
  <span m=''3069060''>couple</span> <span m=''3069330''>of</span> <span m=''3069430''>key</span>
  <span m=''3069620''>details</span> <span m=''3070060''>here,</span> <span m=''3071060''>but</span>
  <span m=''3071200''>other</span> <span m=''3071380''>than</span> <span m=''3071490''>that,</span>
  <span m=''3072530''>it''s</span> <span m=''3072670''>pretty</span> <span m=''3072830''>straightforward.</span>
  <span m=''3073840''>Yeah.</span> </p><p><span m=''3074300''>AUDIENCE: What if</span>
  <span m=''3074760''>you</span> <span m=''3075220''>have</span> <span m=''3075680''>more
  edges</span> <span m=''3076140''>than you</span> <span m=''3076600''>need?</span>
  </p><p><span m=''3078450''>PROFESSOR: If</span> <span m=''3078500''>I</span> <span
  m=''3078570''>have</span> <span m=''3078780''>more</span> <span m=''3079200''>edges</span>
  <span m=''3079520''>than</span> <span m=''3079730''>you</span> <span m=''3079830''>need,</span>
  <span m=''3080230''>then</span> <span m=''3081980''>this</span> <span m=''3082360''>does</span>
  <span m=''3082470''>not</span> <span m=''3082700''>capture</span> <span m=''3083250''>such</span>
  <span m=''3083500''>structures.</span> <span m=''3084070''>This is</span> <span
  m=''3084340''>just</span> <span m=''3084560''>about</span> <span m=''3085240''>minimal</span>
  <span m=''3085970''>generic</span> <span m=''3086770''>rigidity.</span> <span m=''3088160''>But</span>
  <span m=''3089190''>if</span> <span m=''3089410''>I</span> <span m=''3089470''>have</span>
  <span m=''3089710''>some</span> <span m=''3089960''>graph</span> <span m=''3090215''>that</span>
  <span m=''3090470''>is</span> <span m=''3090880''>generically</span> <span m=''3091340''>rigid,</span>
  <span m=''3092110''>it</span> <span m=''3092160''>will</span> <span m=''3092350''>be</span>
  <span m=''3092630''>a</span> <span m=''3092710''>graph</span> <span m=''3093010''>I</span>
  <span m=''3093060''>can</span> <span m=''3093220''>build</span> <span m=''3093440''>this</span>
  <span m=''3093580''>way,</span> <span m=''3094080''>plus</span> <span m=''3094380''>more</span>
  <span m=''3094610''>edges.</span> <span m=''3095830''>Now,</span> <span m=''3096010''>how</span>
  <span m=''3096270''>to</span> <span m=''3096340''>identify</span> <span m=''3097010''>what</span>
  <span m=''3097250''>edges</span> <span m=''3097530''>I</span> <span m=''3097590''>should</span>
  <span m=''3097810''>remove</span> <span m=''3098250''>so</span> <span m=''3098400''>that</span>
  <span m=''3098500''>I</span> <span m=''3098570''>could</span> <span m=''3098760''>do</span>
  <span m=''3099490''>this</span> <span m=''3099620''>Henneberg</span> <span m=''3099950''>construction</span>
  <span m=''3101780''>is</span> <span m=''3101990''>unclear</span> <span m=''3102420''>at</span>
  <span m=''3102500''>this</span> <span m=''3102660''>point,</span> <span m=''3103050''>and</span>
  <span m=''3103100''>that''s</span> <span m=''3103320''>the</span> <span m=''3103400''>purpose</span>
  <span m=''3103740''>of</span> <span m=''3103790''>the</span> <span m=''3103870''>next</span>
  <span m=''3104130''>theorem.</span> <span m=''3106460''>So</span> <span m=''3106890''>good</span>
  <span m=''3107070''>question.</span> </p><p><span m=''3121550''>It</span> <span
  m=''3121860''>turns</span> <span m=''3122120''>out</span> <span m=''3122270''>there''s</span>
  <span m=''3122450''>an</span> <span m=''3122540''>algorithm,</span> <span m=''3123650''>which</span>
  <span m=''3123900''>given</span> <span m=''3124420''>a</span> <span m=''3124810''>generically</span>
  <span m=''3125220''>rigid</span> <span m=''3125520''>graph,</span> <span m=''3126000''>will</span>
  <span m=''3126130''>tell</span> <span m=''3126330''>you</span> <span m=''3126490''>which</span>
  <span m=''3126720''>edges</span> <span m=''3127480''>you</span> <span m=''3127590''>can</span>
  <span m=''3127720''>throw</span> <span m=''3127970''>away,</span> <span m=''3128810''>so</span>
  <span m=''3129010''>that</span> <span m=''3129140''>you</span> <span m=''3129260''>get</span>
  <span m=''3129510''>a</span> <span m=''3129560''>minimally</span> <span m=''3129930''>generically</span>
  <span m=''3130380''>rigid</span> <span m=''3130660''>graph.</span> <span m=''3131790''>And</span>
  <span m=''3133470''>that</span> <span m=''3133680''>algorithm</span> <span m=''3134100''>uses</span>
  <span m=''3135200''>the</span> <span m=''3135590''>following</span> <span m=''3135890''>theorem.</span>
  <span m=''3136190''>This</span> <span m=''3136520''>one</span> <span m=''3136720''>is</span>
  <span m=''3136850''>from</span> <span m=''3137120''>the</span> <span m=''3137190''>''70s</span>
  <span m=''3146130''>by a</span> <span m=''3146310''>guy</span> <span m=''3146560''>named</span>
  <span m=''3146790''>Laman.</span> <span m=''3149090''>It starts</span> <span m=''3149440''>the</span>
  <span m=''3149520''>same</span> <span m=''3151030''>as</span> <span m=''3151290''>Henneberg</span>
  <span m=''3152130''>above.</span> <span m=''3153970''>Graph</span> <span m=''3154390''>is</span>
  <span m=''3155410''>minimally</span> <span m=''3156530''>generically</span> <span
  m=''3158040''>rigid</span> <span m=''3160730''>in</span> <span m=''3160920''>2D</span>
  <span m=''3163950''>if</span> <span m=''3164170''>and</span> <span m=''3164280''>only</span>
  <span m=''3164530''>if</span> <span m=''3169180''>it</span> <span m=''3169350''>has</span>
  <span m=''3169920''>2n</span> <span m=''3170850''>minus</span> <span m=''3171290''>3</span>
  <span m=''3171630''>edges.</span> <span m=''3173890''>And</span> <span m=''3174210''>again,</span>
  <span m=''3174550''>I''m</span> <span m=''3174650''>assuming</span> <span m=''3174900''>the</span>
  <span m=''3174960''>number of</span> <span m=''3175200''>vertices</span> <span m=''3175760''>is</span>
  <span m=''3175920''>bigger</span> <span m=''3176120''>than</span> <span m=''3176250''>one.</span>
  </p><p><span m=''3180230''>So</span> <span m=''3180400''>far,</span> <span m=''3180730''>this</span>
  <span m=''3180900''>is</span> <span m=''3181020''>just</span> <span m=''3181230''>our</span>
  <span m=''3181310''>regular</span> <span m=''3181590''>degree</span> <span m=''3181830''>or</span>
  <span m=''3181890''>freedom</span> <span m=''3182170''>analysis.</span> <span m=''3182620''>But
  I</span> <span m=''3182740''>said</span> <span m=''3182900''>this</span> <span m=''3183060''>wasn''t</span>
  <span m=''3183320''>enough.</span> <span m=''3184090''>You</span> <span m=''3184300''>something</span>
  <span m=''3184660''>else.</span> <span m=''3185390''>Here''s</span> <span m=''3185650''>the</span>
  <span m=''3185730''>something</span> <span m=''3186090''>else.</span> <span m=''3190296''>If</span>
  <span m=''3190760''>I</span> <span m=''3190860''>take</span> <span m=''3191050''>a</span>
  <span m=''3191120''>subset</span> <span m=''3191640''>of</span> <span m=''3191700''>vertices--</span>
  <span m=''3192460''>and</span> <span m=''3192640''>let''s</span> <span m=''3192840''>say</span>
  <span m=''3192960''>there''s</span> <span m=''3193170''>k</span> <span m=''3193450''>of</span>
  <span m=''3193560''>them--</span> <span m=''3202150''>then</span> <span m=''3202390''>that</span>
  <span m=''3202610''>induces</span> <span m=''3203360''>at</span> <span m=''3203500''>most</span>
  <span m=''3203850''>2k</span> <span m=''3204210''>minus</span> <span m=''3204580''>3</span>
  <span m=''3205360''>edges.</span> <span m=''3209230''>So</span> <span m=''3209290''>this--</span>
  <span m=''3209430''>again,</span> <span m=''3209740''>minimal</span> <span m=''3210160''>generic</span>
  <span m=''3210500''>rigidity.</span> <span m=''3210820''>I''m</span> <span m=''3210930''>still</span>
  <span m=''3211170''>not</span> <span m=''3211610''>directly</span> <span m=''3212020''>talking</span>
  <span m=''3212340''>about</span> <span m=''3212670''>the</span> <span m=''3212750''>bigger</span>
  <span m=''3213010''>case.</span> <span m=''3213265''>We''ll</span> <span m=''3213520''>worry</span>
  <span m=''3213770''>about</span> <span m=''3213980''>that</span> <span m=''3214130''>later.</span>
  <span m=''3215250''>So</span> <span m=''3215400''>there''s</span> <span m=''3215650''>the</span>
  <span m=''3215730''>fewest</span> <span m=''3216110''>possible</span> <span m=''3216500''>edges.</span>
  <span m=''3216710''>That</span> <span m=''3216840''>means</span> <span m=''3217080''>2n</span>
  <span m=''3217360''>minus</span> <span m=''3217670''>3.</span> </p><p><span m=''3219220''>But</span>
  <span m=''3219370''>now,</span> <span m=''3220000''>essentially</span> <span m=''3220410''>what</span>
  <span m=''3220560''>I</span> <span m=''3220600''>want</span> <span m=''3220760''>to</span>
  <span m=''3220830''>say</span> <span m=''3221090''>is</span> <span m=''3221270''>that</span>
  <span m=''3221760''>there</span> <span m=''3221980''>aren''t</span> <span m=''3222110''>too</span>
  <span m=''3222340''>many</span> <span m=''3222570''>edges</span> <span m=''3222860''>in</span>
  <span m=''3222950''>any</span> <span m=''3223110''>one</span> <span m=''3223360''>place,</span>
  <span m=''3224220''>and</span> <span m=''3224280''>therefore</span> <span m=''3224570''>the</span>
  <span m=''3224680''>edges</span> <span m=''3224990''>are</span> <span m=''3225090''>well</span>
  <span m=''3225410''>distributed.</span> <span m=''3226830''>So</span> <span m=''3226960''>if</span>
  <span m=''3227050''>I</span> <span m=''3227120''>take</span> <span m=''3227370''>some</span>
  <span m=''3227550''>subset</span> <span m=''3227980''>of</span> <span m=''3228040''>the</span>
  <span m=''3228100''>vertices--</span> <span m=''3228740''>so</span> <span m=''3228880''>here''s</span>
  <span m=''3229320''>my</span> <span m=''3230000''>graph,</span> <span m=''3230840''>and
  I</span> <span m=''3231060''>take</span> <span m=''3231230''>some</span> <span m=''3231660''>crazy</span>
  <span m=''3232060''>subset--</span> <span m=''3232720''>any</span> <span m=''3233620''>blob</span>
  <span m=''3233920''>the</span> <span m=''3233980''>vertices</span> <span m=''3234420''>I</span>
  <span m=''3234480''>want,</span> <span m=''3235330''>I</span> <span m=''3235440''>look</span>
  <span m=''3235660''>at</span> <span m=''3235750''>what</span> <span m=''3235960''>are</span>
  <span m=''3236080''>all</span> <span m=''3236230''>the</span> <span m=''3236400''>edges</span>
  <span m=''3236870''>inside</span> <span m=''3237830''>between</span> <span m=''3238350''>vertices</span>
  <span m=''3238850''>in</span> <span m=''3238980''>that</span> <span m=''3239210''>set?</span>
  <span m=''3241270''>I</span> <span m=''3241390''>don''t</span> <span m=''3241570''>want</span>
  <span m=''3241660''>to</span> <span m=''3241710''>have</span> <span m=''3241890''>too</span>
  <span m=''3242070''>many.</span> <span m=''3243300''>I</span> <span m=''3243400''>don''t</span>
  <span m=''3243540''>want</span> <span m=''3243660''>to</span> <span m=''3243710''>have</span>
  <span m=''3243890''>more</span> <span m=''3244140''>than</span> <span m=''3244290''>what</span>
  <span m=''3244420''>I</span> <span m=''3244470''>should--</span> <span m=''3244950''>2k</span>
  <span m=''3245110''>minus</span> <span m=''3245440''>3</span> <span m=''3245730''>if
  there''s</span> <span m=''3245880''>k</span> <span m=''3246040''>vertices</span>
  <span m=''3246520''>in</span> <span m=''3246590''>here.</span> </p><p><span m=''3247610''>If</span>
  <span m=''3247770''>I</span> <span m=''3247850''>had</span> <span m=''3248060''>more--</span>
  <span m=''3249400''>for</span> <span m=''3249530''>example,</span> <span m=''3251810''>that''s</span>
  <span m=''3252060''>minimally</span> <span m=''3252400''>generically</span> <span
  m=''3252770''>rigid.</span> <span m=''3253080''>If</span> <span m=''3253220''>I</span>
  <span m=''3253280''>did</span> <span m=''3253480''>that</span> <span m=''3254300''>anywhere</span>
  <span m=''3254720''>in</span> <span m=''3254790''>the</span> <span m=''3254870''>graph--</span>
  <span m=''3256810''>this</span> <span m=''3257010''>has</span> <span m=''3257450''>2n</span>
  <span m=''3258490''>minus</span> <span m=''3258780''>2</span> <span m=''3258990''>edges.
  It''s</span> <span m=''3259490''>too</span> <span m=''3259640''>many.</span> <span
  m=''3260870''>Or</span> <span m=''3260990''>2k</span> <span m=''3261360''>minus</span>
  <span m=''3261710''>2</span> <span m=''3261880''>edges.</span> <span m=''3262470''>K
  is</span> <span m=''3262800''>four</span> <span m=''3263100''>here.</span> <span
  m=''3263870''>If</span> <span m=''3264030''>I</span> <span m=''3264100''>put</span>
  <span m=''3264310''>that</span> <span m=''3264460''>in</span> <span m=''3264550''>some</span>
  <span m=''3264760''>bigger</span> <span m=''3265010''>graph</span> <span m=''3265440''>and</span>
  <span m=''3265560''>the</span> <span m=''3265620''>bigger</span> <span m=''3265950''>graph</span>
  <span m=''3266220''>has</span> <span m=''3266400''>2n</span> <span m=''3266640''>minus</span>
  <span m=''3266950''>3,</span> <span m=''3267400''>and I</span> <span m=''3267620''>wasted</span>
  <span m=''3268060''>an</span> <span m=''3268130''>edge</span> <span m=''3268340''>here,</span>
  <span m=''3268800''>that</span> <span m=''3268970''>means</span> <span m=''3269150''>somewhere</span>
  <span m=''3269510''>else,</span> <span m=''3269690''>it</span> <span m=''3269760''>will</span>
  <span m=''3269880''>be</span> <span m=''3270000''>flexible.</span> <span m=''3271430''>So</span>
  <span m=''3271530''>it''s</span> <span m=''3271650''>a</span> <span m=''3271690''>bit</span>
  <span m=''3271850''>of</span> <span m=''3271970''>a</span> <span m=''3272050''>weird</span>
  <span m=''3272410''>condition.</span> </p><p><span m=''3273520''>You</span> <span
  m=''3273650''>might</span> <span m=''3273880''>think</span> <span m=''3274050''>this</span>
  <span m=''3274110''>should</span> <span m=''3274300''>say</span> <span m=''3274430''>greater</span>
  <span m=''3274720''>than</span> <span m=''3274860''>or</span> <span m=''3274890''>equal</span>
  <span m=''3275090''>to</span> <span m=''3275240''>be.</span> <span m=''3275380''>It''d
  be more</span> <span m=''3275570''>intuitive.</span> <span m=''3275980''>That</span>
  <span m=''3276130''>would</span> <span m=''3276260''>be</span> <span m=''3276390''>wrong.</span>
  <span m=''3277345''>The</span> <span m=''3277830''>theorem</span> <span m=''3278110''>isn''t</span>
  <span m=''3278340''>true</span> <span m=''3278550''>when</span> <span m=''3278660''>you</span>
  <span m=''3278740''>put</span> <span m=''3278900''>greater than</span> <span m=''3279140''>or</span>
  <span m=''3279230''>equal</span> <span m=''3279440''>to,</span> <span m=''3281030''>because</span>
  <span m=''3281220''>you</span> <span m=''3281350''>could</span> <span m=''3281480''>choose</span>
  <span m=''3281660''>vertices that</span> <span m=''3282020''>have</span> <span m=''3282190''>no</span>
  <span m=''3282400''>edges</span> <span m=''3282700''>between</span> <span m=''3283020''>them.</span>
  <span m=''3283500''>There''s</span> <span m=''3283790''>going</span> <span m=''3283930''>to</span>
  <span m=''3283980''>be</span> <span m=''3284060''>a</span> <span m=''3284120''>lot</span>
  <span m=''3284320''>of</span> <span m=''3284380''>them.</span> <span m=''3285590''>But</span>
  <span m=''3286100''>if</span> <span m=''3286320''>you</span> <span m=''3286560''>make</span>
  <span m=''3286770''>sure</span> <span m=''3286890''>there</span> <span m=''3287020''>aren''t</span>
  <span m=''3287170''>too</span> <span m=''3287390''>many</span> <span m=''3287660''>anywhere,</span>
  <span m=''3288100''>then</span> <span m=''3288300''>it</span> <span m=''3288480''>turns</span>
  <span m=''3288730''>out</span> <span m=''3288950''>it</span> <span m=''3289010''>will</span>
  <span m=''3289160''>be</span> <span m=''3289380''>just</span> <span m=''3289650''>right</span>
  <span m=''3289910''>everywhere.</span> <span m=''3291436''>It''s</span> <span m=''3291920''>like</span>
  <span m=''3292160''>three</span> <span m=''3292330''>little</span> <span m=''3292510''>bears</span>
  <span m=''3292890''>or</span> <span m=''3292960''>something.</span> <span m=''3295040''>So</span>
  <span m=''3296540''>some</span> <span m=''3296750''>generalized</span> <span m=''3297310''>version
  of</span> <span m=''3297710''>three</span> <span m=''3297890''>little</span> <span
  m=''3298070''>bears.</span> <span m=''3298370''>K little</span> <span m=''3298820''>bears.</span>
  </p><p><span m=''3299794''>[LAUGHTER]</span> </p><p><span m=''3302460''>All</span>
  <span m=''3302560''>right.</span> <span m=''3302920''>So</span> <span m=''3303080''>this</span>
  <span m=''3303230''>is a</span> <span m=''3303340''>very</span> <span m=''3303530''>cool</span>
  <span m=''3303780''>theorem.</span> <span m=''3304630''>It''s</span> <span m=''3304800''>not</span>
  <span m=''3305050''>obviously</span> <span m=''3305610''>algorithmic,</span> <span
  m=''3306350''>because</span> <span m=''3306840''>it</span> <span m=''3306920''>says,</span>
  <span m=''3307210''>oh,</span> <span m=''3307430''>you</span> <span m=''3307540''>just</span>
  <span m=''3307830''>check</span> <span m=''3308150''>every</span> <span m=''3308490''>subset</span>
  <span m=''3309600''>of</span> <span m=''3309700''>k</span> <span m=''3309850''>vertices</span>
  <span m=''3310230''>for</span> <span m=''3310360''>all</span> <span m=''3310530''>values</span>
  <span m=''3310790''>of</span> <span m=''3310890''>k.</span> <span m=''3311080''>There''s</span>
  <span m=''3311240''>exponentially</span> <span m=''3311910''>many</span> <span m=''3312140''>subsets.</span>
  <span m=''3312590''>It''s</span> <span m=''3312740''>not</span> <span m=''3312980''>a</span>
  <span m=''3313030''>good</span> <span m=''3313200''>algorithm</span> <span m=''3313560''>by</span>
  <span m=''3313690''>itself,</span> <span m=''3314540''>but</span> <span m=''3314750''>it</span>
  <span m=''3314880''>turns</span> <span m=''3315120''>out</span> <span m=''3315240''>you</span>
  <span m=''3315350''>can</span> <span m=''3315450''>make</span> <span m=''3315650''>it</span>
  <span m=''3315720''>into</span> <span m=''3315910''>an</span> <span m=''3315980''>algorithm.</span>
  <span m=''3317220''>I''ll</span> <span m=''3317330''>talk</span> <span m=''3317500''>about</span>
  <span m=''3317710''>that</span> <span m=''3317860''>in</span> <span m=''3317960''>a</span>
  <span m=''3318000''>moment.</span> </p><p><span m=''3318970''>First,</span> <span
  m=''3319230''>we''re</span> <span m=''3319310''>going</span> <span m=''3319450''>to</span>
  <span m=''3319550''>prove</span> <span m=''3319820''>the</span> <span m=''3319910''>theorem.</span>
  <span m=''3323769''>OK, I have</span> <span m=''3324270''>to</span> <span m=''3324370''>speed</span>
  <span m=''3324640''>up</span> <span m=''3324760''>a</span> <span m=''3324810''>little.</span>
  <span m=''3327470''>All</span> <span m=''3327610''>right.</span> <span m=''3328770''>Let</span>
  <span m=''3328950''>me</span> <span m=''3329250''>sketch</span> <span m=''3329620''>this</span>
  <span m=''3329780''>proof.</span> <span m=''3329980''>It''s</span> <span m=''3330100''>really</span>
  <span m=''3330350''>easy,</span> <span m=''3331080''>because</span> <span m=''3331640''>we</span>
  <span m=''3331770''>already</span> <span m=''3331970''>have</span> <span m=''3332190''>this</span>
  <span m=''3332350''>great</span> <span m=''3332530''>characterization</span> <span
  m=''3333810''>of</span> <span m=''3333900''>minimally</span> <span m=''3334250''>generically</span>
  <span m=''3334650''>rigid</span> <span m=''3334860''>graphs.</span> <span m=''3335760''>It''s</span>
  <span m=''3335880''>just</span> <span m=''3336050''>things</span> <span m=''3336240''>you</span>
  <span m=''3336350''>can</span> <span m=''3336480''>build</span> <span m=''3336790''>by</span>
  <span m=''3336910''>Type</span> <span m=''3337160''>I</span> <span m=''3337360''>and</span>
  <span m=''3337490''>Type</span> <span m=''3337680''>II</span> <span m=''3337830''>operations.</span>
  </p><p><span m=''3339740''>So</span> <span m=''3340020''>if</span> <span m=''3340170''>I</span>
  <span m=''3341210''>want</span> <span m=''3341660''>to</span> <span m=''3342160''>show</span>
  <span m=''3343310''>the</span> <span m=''3343400''>forward</span> <span m=''3343710''>direction,
  that</span> <span m=''3344150''>if</span> <span m=''3344350''>I</span> <span m=''3344410''>have</span>
  <span m=''3344630''>a</span> <span m=''3344680''>minimally</span> <span m=''3344990''>generic</span>
  <span m=''3345310''>thing--</span> <span m=''3345620''>i.e.</span> <span m=''3346360''>It</span>
  <span m=''3346500''>can</span> <span m=''3346630''>be</span> <span m=''3346740''>built</span>
  <span m=''3347040''>this</span> <span m=''3347200''>way--</span> <span m=''3348150''>then</span>
  <span m=''3348830''>it</span> <span m=''3349030''>has</span> <span m=''3350350''>2n</span>
  <span m=''3350660''>minus</span> <span m=''3350870''>3</span> <span m=''3351010''>edges.</span>
  <span m=''3351250''>Well,</span> <span m=''3351350''>that</span> <span m=''3351500''>we
  already</span> <span m=''3351860''>know.</span> <span m=''3353430''>And</span> <span
  m=''3353690''>then</span> <span m=''3353970''>the</span> <span m=''3354170''>other</span>
  <span m=''3354350''>thing</span> <span m=''3354710''>is</span> <span m=''3354880''>that</span>
  <span m=''3355010''>every</span> <span m=''3355220''>subset</span> <span m=''3355610''>of</span>
  <span m=''3355700''>k</span> <span m=''3355850''>vertices</span> <span m=''3356420''>has</span>
  <span m=''3357110''>at</span> <span m=''3357260''>most</span> <span m=''3357530''>2k</span>
  <span m=''3357820''>minus</span> <span m=''3358080''>3</span> <span m=''3358240''>edges</span>
  <span m=''3358470''>among</span> <span m=''3358760''>them.</span> </p><p><span m=''3360960''>So</span>
  <span m=''3362710''>think</span> <span m=''3362870''>about</span> <span m=''3363130''>it</span>
  <span m=''3363200''>here.</span> <span m=''3364770''>So</span> <span m=''3364910''>maybe</span>
  <span m=''3365160''>this</span> <span m=''3365360''>is</span> <span m=''3365450''>my</span>
  <span m=''3365620''>graph.</span> <span m=''3367010''>It''s</span> <span m=''3367150''>produced</span>
  <span m=''3367540''>by a</span> <span m=''3367700''>Type</span> <span m=''3367970''>I</span>
  <span m=''3368140''>operation</span> <span m=''3368570''>at</span> <span m=''3368720''>the</span>
  <span m=''3368850''>end.</span> <span m=''3371210''>Well,</span> <span m=''3373240''>it</span>
  <span m=''3373350''>takes</span> <span m=''3373540''>some</span> <span m=''3373680''>subset</span>
  <span m=''3374020''>of</span> <span m=''3374090''>the</span> <span m=''3374150''>vertices.</span>
  <span m=''3374580''>Either</span> <span m=''3374780''>the</span> <span m=''3374880''>subset</span>
  <span m=''3375270''>contains</span> <span m=''3375630''>this</span> <span m=''3375750''>vertex,</span>
  <span m=''3376150''>or it</span> <span m=''3376270''>doesn''t.</span> <span m=''3377720''>If</span>
  <span m=''3377880''>it</span> <span m=''3378650''>doesn''t</span> <span m=''3379010''>contain</span>
  <span m=''3379360''>this</span> <span m=''3379510''>vertex,</span> <span m=''3380080''>then</span>
  <span m=''3380210''>it''s</span> <span m=''3380350''>a</span> <span m=''3380410''>subset</span>
  <span m=''3381040''>just</span> <span m=''3381270''>in</span> <span m=''3381340''>the</span>
  <span m=''3381440''>old</span> <span m=''3381670''>graph.</span> <span m=''3382210''>And</span>
  <span m=''3382580''>by</span> <span m=''3382740''>induction,</span> <span m=''3383540''>my</span>
  <span m=''3383670''>theorem will hold,</span> <span m=''3384470''>because</span>
  <span m=''3384640''>that''s</span> <span m=''3384810''>a</span> <span m=''3384860''>smaller</span>
  <span m=''3385180''>graph.</span> </p><p><span m=''3385920''>If</span> <span m=''3386190''>it''s</span>
  <span m=''3386330''>a</span> <span m=''3386390''>subset</span> <span m=''3386860''>that</span>
  <span m=''3386970''>includes</span> <span m=''3387440''>this</span> <span m=''3387660''>guy,</span>
  <span m=''3389580''>then</span> <span m=''3390480''>it''s</span> <span m=''3390700''>whatever</span>
  <span m=''3391410''>the</span> <span m=''3391610''>subset</span> <span m=''3392120''>contains</span>
  <span m=''3392530''>over</span> <span m=''3392700''>here,</span> <span m=''3393330''>plus</span>
  <span m=''3393650''>2</span> <span m=''3393850''>edges</span> <span m=''3394600''>minus</span>
  <span m=''3394920''>1</span> <span m=''3395090''>vertex.</span> <span m=''3396610''>And</span>
  <span m=''3396800''>that</span> <span m=''3396940''>just</span> <span m=''3397110''>works</span>
  <span m=''3397340''>out.</span> <span m=''3397780''>Over</span> <span m=''3398000''>here,</span>
  <span m=''3398140''>there''s</span> <span m=''3398280''>going</span> <span m=''3398390''>to</span>
  <span m=''3398440''>be</span> <span m=''3398550''>k</span> <span m=''3398740''>minus</span>
  <span m=''3399040''>1</span> <span m=''3399250''>vertices,</span> <span m=''3400300''>so
  it''ll</span> <span m=''3400440''>be two</span> <span m=''3400650''>times</span>
  <span m=''3400920''>k</span> <span m=''3401050''>minus</span> <span m=''3401330''>1</span>
  <span m=''3401630''>minus</span> <span m=''3401970''>3</span> <span m=''3402330''>at</span>
  <span m=''3402490''>most.</span> <span m=''3403430''>We</span> <span m=''3403580''>add</span>
  <span m=''3403840''>two</span> <span m=''3404040''>edges,</span> <span m=''3404590''>we</span>
  <span m=''3404800''>add</span> <span m=''3405010''>one</span> <span m=''3405190''>vertex.</span>
  <span m=''3405640''>That''s</span> <span m=''3405830''>exactly</span> <span m=''3406190''>what</span>
  <span m=''3406360''>this</span> <span m=''3406720''>predicts.</span> <span m=''3407150''>You</span>
  <span m=''3407220''>should</span> <span m=''3407410''>add</span> <span m=''3407630''>two</span>
  <span m=''3407950''>edges</span> <span m=''3408220''>for</span> <span m=''3408320''>every</span>
  <span m=''3408510''>vertex.</span> <span m=''3409820''>So</span> <span m=''3409840''>that''s</span>
  <span m=''3410070''>fine.</span> </p><p><span m=''3410830''>The</span> <span m=''3410940''>Type</span>
  <span m=''3411200''>II,</span> <span m=''3411510''>same</span> <span m=''3411800''>deal.</span>
  <span m=''3413890''>But</span> <span m=''3415270''>in</span> <span m=''3415340''>general,</span>
  <span m=''3415660''>I''m adding</span> <span m=''3415930''>three</span> <span m=''3416190''>edges,</span>
  <span m=''3416480''>removing</span> <span m=''3416860''>one,</span> <span m=''3418040''>and</span>
  <span m=''3418230''>adding</span> <span m=''3418440''>one</span> <span m=''3418600''>vertex.</span>
  <span m=''3419350''>And</span> <span m=''3419520''>that''s</span> <span m=''3419710''>again</span>
  <span m=''3419960''>true</span> <span m=''3420190''>in</span> <span m=''3420380''>the</span>
  <span m=''3420460''>subsets,</span> <span m=''3421130''>not</span> <span m=''3421830''>just</span>
  <span m=''3422100''>overall.</span> </p><p><span m=''3423370''>I take</span> <span
  m=''3423500''>a</span> <span m=''3423550''>subset</span> <span m=''3423920''>containing</span>
  <span m=''3424290''>this</span> <span m=''3424450''>guy</span> <span m=''3424700''>or</span>
  <span m=''3424810''>not.</span> <span m=''3426560''>You</span> <span m=''3426770''>have</span>
  <span m=''3426950''>to</span> <span m=''3427050''>check</span> <span m=''3427280''>all</span>
  <span m=''3427380''>the</span> <span m=''3427470''>cases,</span> <span m=''3427950''>depending
  on</span> <span m=''3428230''>whether it</span> <span m=''3428450''>contains</span>
  <span m=''3428720''>this</span> <span m=''3428900''>guy</span> <span m=''3429030''>or</span>
  <span m=''3429160''>this</span> <span m=''3429360''>guy or</span> <span m=''3429600''>this</span>
  <span m=''3429820''>guy,</span> <span m=''3430010''>or</span> <span m=''3430090''>not.</span>
  <span m=''3430530''>But</span> <span m=''3431220''>in</span> <span m=''3431500''>all</span>
  <span m=''3431690''>cases,</span> <span m=''3432780''>this</span> <span m=''3432980''>inequality</span>
  <span m=''3433490''>still</span> <span m=''3433840''>holds.</span> <span m=''3435640''>How''s</span>
  <span m=''3435730''>that?</span> <span m=''3441230''>It''s</span> <span m=''3441480''>a</span>
  <span m=''3441510''>bunch</span> <span m=''3441730''>of</span> <span m=''3441790''>case</span>
  <span m=''3442070''>work,</span> <span m=''3442850''>but</span> <span m=''3443020''>all</span>
  <span m=''3443230''>really</span> <span m=''3443430''>straightforward,</span> <span
  m=''3445840''>so</span> <span m=''3446030''>believe</span> <span m=''3446340''>me.</span>
  </p><p><span m=''3447530''>The</span> <span m=''3447630''>hard</span> <span m=''3447860''>part</span>
  <span m=''3448080''>is</span> <span m=''3448180''>the</span> <span m=''3448280''>other</span>
  <span m=''3448400''>direction.</span> <span m=''3450340''>If</span> <span m=''3450560''>I''m</span>
  <span m=''3450730''>told</span> <span m=''3451050''>that</span> <span m=''3451170''>this</span>
  <span m=''3451360''>is</span> <span m=''3451480''>true--</span> <span m=''3452420''>all</span>
  <span m=''3453060''>the</span> <span m=''3453160''>subsets</span> <span m=''3454410''>don''t</span>
  <span m=''3454600''>have</span> <span m=''3454740''>too</span> <span m=''3454860''>many</span>
  <span m=''3455080''>edges--</span> <span m=''3455810''>then</span> <span m=''3455990''>I</span>
  <span m=''3456060''>claim</span> <span m=''3456510''>I</span> <span m=''3456610''>can</span>
  <span m=''3456750''>actually</span> <span m=''3457040''>build</span> <span m=''3457290''>it</span>
  <span m=''3457380''>this</span> <span m=''3457550''>way,</span> <span m=''3458250''>or</span>
  <span m=''3458500''>I</span> <span m=''3458530''>claim</span> <span m=''3458820''>that</span>
  <span m=''3458940''>somehow</span> <span m=''3459270''>it''s</span> <span m=''3459400''>minimally</span>
  <span m=''3459730''>generically</span> <span m=''3460150''>rigid.</span> <span m=''3461860''>And</span>
  <span m=''3462130''>we</span> <span m=''3462290''>are,</span> <span m=''3462500''>in</span>
  <span m=''3462600''>fact,</span> <span m=''3462970''>going</span> <span m=''3463070''>to</span>
  <span m=''3463170''>build</span> <span m=''3463480''>it</span> <span m=''3464580''>using</span>
  <span m=''3464990''>Henneberg</span> <span m=''3465360''>constructions,</span> <span
  m=''3466070''>using</span> <span m=''3466410''>these</span> <span m=''3466570''>properties</span>
  <span m=''3466825''>that</span> <span m=''3467080''>we</span> <span m=''3467230''>proved--
  one,</span> <span m=''3467700''>two,</span> <span m=''3467840''>three,</span> <span
  m=''3468030''>four.</span> </p><p><span m=''3470720''>All</span> <span m=''3470790''>right.</span>
  <span m=''3471170''>So</span> <span m=''3471370''>what</span> <span m=''3471500''>do</span>
  <span m=''3471570''>we</span> <span m=''3471690''>know?</span> <span m=''3472840''>We</span>
  <span m=''3472890''>know</span> <span m=''3473100''>that</span> <span m=''3473240''>there</span>
  <span m=''3473380''>are</span> <span m=''3473450''>2n</span> <span m=''3473740''>minus</span>
  <span m=''3474030''>3</span> <span m=''3474220''>edges.</span> <span m=''3475250''>Hey,</span>
  <span m=''3476130''>I already</span> <span m=''3476380''>have</span> <span m=''3476560''>a</span>
  <span m=''3476610''>great</span> <span m=''3476840''>argument</span> <span m=''3477250''>for</span>
  <span m=''3477380''>when</span> <span m=''3477500''>the</span> <span m=''3477570''>number</span>
  <span m=''3477800''>of</span> <span m=''3477880''>edges</span> <span m=''3478130''>is</span>
  <span m=''3478220''>2n</span> <span m=''3478460''>minus</span> <span m=''3478770''>3.</span>
  <span m=''3479550''>I do</span> <span m=''3479660''>the</span> <span m=''3479740''>handshaking</span>
  <span m=''3480150''>lemma, and</span> <span m=''3480340''>I know that</span> <span
  m=''3480700''>the</span> <span m=''3480940''>sum</span> <span m=''3481130''>of</span>
  <span m=''3481250''>degrees</span> <span m=''3481540''>is</span> <span m=''3481670''>4n</span>
  <span m=''3481860''>minus</span> <span m=''3482110''>6.</span> <span m=''3482340''>Therefore,</span>
  <span m=''3482680''>I know</span> <span m=''3482730''>the</span> <span m=''3482860''>average</span>
  <span m=''3483140''>degree is</span> <span m=''3483450''>less than</span> <span
  m=''3483750''>four.</span> <span m=''3484790''>Great.</span> <span m=''3486750''>Problem</span>
  <span m=''3487020''>solved.</span> <span m=''3487300''>Therefore,</span> <span m=''3487410''>I</span>
  <span m=''3487630''>know</span> <span m=''3488430''>there''s</span> <span m=''3488610''>a</span>
  <span m=''3488660''>vertex</span> <span m=''3494380''>of</span> <span m=''3494880''>degree</span>
  <span m=''3496750''>less</span> <span m=''3497040''>than</span> <span m=''3497170''>four.</span>
  </p><p><span m=''3497630''>It</span> <span m=''3497770''>could</span> <span m=''3497900''>be</span>
  <span m=''3498050''>zero,</span> <span m=''3498470''>one</span> <span m=''3498830''>two,</span>
  <span m=''3499150''>or</span> <span m=''3499240''>three.</span> <span m=''3500520''>Can
  it</span> <span m=''3500750''>be</span> <span m=''3500830''>zero?</span> <span m=''3505010''>Hope</span>
  <span m=''3505450''>not.</span> <span m=''3507045''>How</span> <span m=''3507430''>do
  I</span> <span m=''3507540''>prove</span> <span m=''3507780''>it''s</span> <span
  m=''3507910''>not</span> <span m=''3508110''>zero?</span> <span m=''3508710''>I</span>
  <span m=''3508850''>know how</span> <span m=''3509050''>to</span> <span m=''3509150''>prove</span>
  <span m=''3509470''>it''s</span> <span m=''3509660''>not</span> <span m=''3510880''>one,</span>
  <span m=''3511940''>think.</span> <span m=''3517570''>I have to</span> <span m=''3518060''>cheat</span>
  <span m=''3518420''>here.</span> <span m=''3519820''>Aha.</span> <span m=''3520320''>Right,
  right.</span> <span m=''3521010''>OK,</span> <span m=''3521470''>good.</span> <span
  m=''3522214''>Duh.</span> <span m=''3524150''>All</span> <span m=''3524230''>right.</span>
  <span m=''3524470''>Number</span> <span m=''3524720''>of</span> <span m=''3524800''>edges</span>
  <span m=''3525120''>is</span> <span m=''3525280''>2n</span> <span m=''3525370''>minus</span>
  <span m=''3525670''>3.</span> </p><p><span m=''3526510''>Suppose</span> <span m=''3527420''>my</span>
  <span m=''3527570''>graph</span> <span m=''3528600''>looked</span> <span m=''3528770''>like</span>
  <span m=''3528930''>this,</span> <span m=''3529200''>where</span> <span m=''3529290''>there''s</span>
  <span m=''3529440''>no</span> <span m=''3529630''>edges</span> <span m=''3529930''>incident</span>
  <span m=''3530270''>to</span> <span m=''3530340''>this</span> <span m=''3530530''>guy.</span>
  <span m=''3531020''>Well,</span> <span m=''3531230''>how</span> <span m=''3531390''>many</span>
  <span m=''3531740''>edges</span> <span m=''3532100''>does</span> <span m=''3532180''>this</span>
  <span m=''3532370''>have?</span> <span m=''3533810''>2n</span> <span m=''3533920''>minus</span>
  <span m=''3534200''>3</span> <span m=''3534410''>still.</span> <span m=''3534730''>I
  didn''t</span> <span m=''3534950''>remove</span> <span m=''3535260''>any.</span>
  <span m=''3536480''>So</span> <span m=''3536610''>I''ve</span> <span m=''3536740''>got</span>
  <span m=''3536930''>n</span> <span m=''3537080''>minus</span> <span m=''3537360''>1</span>
  <span m=''3537540''>vertices,</span> <span m=''3537990''>yet</span> <span m=''3538150''>I</span>
  <span m=''3538190''>have</span> <span m=''3538380''>2n</span> <span m=''3538660''>minus</span>
  <span m=''3538960''>3</span> <span m=''3539240''>edges?</span> <span m=''3539590''>That</span>
  <span m=''3539810''>ain''t</span> <span m=''3540000''>right.</span> <span m=''3541170''>So</span>
  <span m=''3541290''>that</span> <span m=''3541470''>can''t</span> <span m=''3541650''>happen.</span>
  </p><p><span m=''3542440''>Similarly</span> <span m=''3542940''>here,</span> <span
  m=''3544310''>if</span> <span m=''3544560''>I</span> <span m=''3544630''>have</span>
  <span m=''3545850''>one</span> <span m=''3546100''>edge</span> <span m=''3546340''>here,</span>
  <span m=''3547630''>then</span> <span m=''3548040''>the</span> <span m=''3548130''>number</span>
  <span m=''3548370''>of</span> <span m=''3548430''>edges</span> <span m=''3548750''>inside</span>
  <span m=''3549270''>this</span> <span m=''3549550''>blob--</span> <span m=''3550750''>everything</span>
  <span m=''3551140''>except</span> <span m=''3551480''>that</span> <span m=''3551630''>one</span>
  <span m=''3551800''>vertex--</span> <span m=''3552200''>would</span> <span m=''3552370''>be</span>
  <span m=''3552560''>2n</span> <span m=''3552940''>minus</span> <span m=''3553710''>2,</span>
  <span m=''3553970''>I</span> <span m=''3554230''>guess.</span> <span m=''3556010''>But</span>
  <span m=''3556160''>it</span> <span m=''3556240''>should</span> <span m=''3556420''>really</span>
  <span m=''3556680''>have</span> <span m=''3556980''>at</span> <span m=''3557060''>most</span>
  <span m=''3557380''>2</span> <span m=''3557600''>times</span> <span m=''3558080''>n</span>
  <span m=''3558240''>minus</span> <span m=''3558590''>1</span> <span m=''3559460''>minus</span>
  <span m=''3559980''>3,</span> <span m=''3562040''>which</span> <span m=''3562450''>is</span>
  <span m=''3563970''>2n</span> <span m=''3564690''>minus</span> <span m=''3565750''>4.</span>
  </p><p><span m=''3566610''>Sorry,</span> <span m=''3566790''>I</span> <span m=''3566900''>did</span>
  <span m=''3567060''>this</span> <span m=''3567200''>wrong.</span> <span m=''3569460''>2n</span>
  <span m=''3569700''>minus</span> <span m=''3570130''>3.</span> <span m=''3571120''>This</span>
  <span m=''3571260''>should</span> <span m=''3571420''>be</span> <span m=''3571580''>4.</span>
  <span m=''3572010''>This</span> <span m=''3572210''>should</span> <span m=''3572380''>be</span>
  <span m=''3572530''>5.</span> <span m=''3573846''>I''ll get it</span> <span m=''3574190''>right</span>
  <span m=''3574350''>eventually.</span> <span m=''3576450''>So</span> <span m=''3576490''>if</span>
  <span m=''3576580''>I</span> <span m=''3576630''>remove</span> <span m=''3576920''>one</span>
  <span m=''3577150''>edge from</span> <span m=''3577520''>2n</span> <span m=''3577720''>minus</span>
  <span m=''3577940''>3,</span> <span m=''3578090''>I</span> <span m=''3578160''>get</span>
  <span m=''3578360''>2n</span> <span m=''3578570''>minus</span> <span m=''3578860''>4.</span>
  <span m=''3579220''>I had the</span> <span m=''3579590''>sign</span> <span m=''3579900''>error.</span>
  <span m=''3581590''>But</span> <span m=''3581770''>I''m</span> <span m=''3581850''>supposed</span>
  <span m=''3582320''>to</span> <span m=''3582390''>have</span> <span m=''3582590''>2</span>
  <span m=''3582780''>times</span> <span m=''3583060''>n</span> <span m=''3583220''>minus</span>
  <span m=''3583510''>1--</span> <span m=''3583750''>that''s the</span> <span m=''3583970''>number</span>
  <span m=''3584220''>vertices</span> <span m=''3584650''>over</span> <span m=''3584860''>here--</span>
  <span m=''3586170''>minus</span> <span m=''3586560''>3,</span> <span m=''3586770''>which</span>
  <span m=''3586940''>is</span> <span m=''3587020''>2n</span> <span m=''3587240''>minus</span>
  <span m=''3587520''>5.</span> <span m=''3587890''>So</span> <span m=''3588080''>I</span>
  <span m=''3588200''>have</span> <span m=''3588570''>the</span> <span m=''3588680''>wrong</span>
  <span m=''3588890''>number</span> <span m=''3589110''>of</span> <span m=''3589170''>edges.</span>
  <span m=''3589740''>In fact, it</span> <span m=''3590130''>should</span> <span m=''3590410''>equal.</span>
  <span m=''3592010''>Whatever.</span> <span m=''3592370''>At</span> <span m=''3592510''>most,</span>
  <span m=''3592900''>at</span> <span m=''3593080''>most.</span> </p><p><span m=''3594930''>We</span>
  <span m=''3595050''>know</span> <span m=''3595180''>in</span> <span m=''3595270''>every</span>
  <span m=''3595510''>subset--</span> <span m=''3596040''>here, I''m</span> <span
  m=''3596280''>taking</span> <span m=''3596530''>a</span> <span m=''3596590''>subset</span>
  <span m=''3596930''>of</span> <span m=''3597010''>n</span> <span m=''3597120''>minus</span>
  <span m=''3597400''>1</span> <span m=''3597550''>vertices.</span> <span m=''3598020''>I</span>
  <span m=''3598060''>have</span> <span m=''3598210''>at</span> <span m=''3598270''>most</span>
  <span m=''3598510''>2k</span> <span m=''3598770''>minus</span> <span m=''3599100''>3.</span>
  <span m=''3599650''>Here</span> <span m=''3599860''>k</span> <span m=''3600080''>is</span>
  <span m=''3600220''>n</span> <span m=''3600320''>minus</span> <span m=''3600580''>1.</span>
  <span m=''3601410''>So</span> <span m=''3601530''>I</span> <span m=''3601560''>can''t</span>
  <span m=''3601810''>have</span> <span m=''3601950''>degree-1,</span> <span m=''3602510''>I</span>
  <span m=''3602550''>can''t</span> <span m=''3602770''>have</span> <span m=''3602920''>degree-0.</span>
  <span m=''3603380''>Therefore,</span> <span m=''3605000''>in</span> <span m=''3605070''>fact,</span>
  <span m=''3605390''>it''s</span> <span m=''3605810''>either</span> <span m=''3606950''>degree2</span>
  <span m=''3607490''>or</span> <span m=''3607590''>3.</span> <span m=''3611490''>If</span>
  <span m=''3611620''>it''s</span> <span m=''3611760''>degree-2,</span> <span m=''3614580''>I''m</span>
  <span m=''3614730''>done.</span> <span m=''3616130''>I''m</span> <span m=''3616280''>happy.</span>
  <span m=''3617390''>If it''s</span> <span m=''3617810''>degree--2,</span> <span
  m=''3621640''>then</span> <span m=''3622050''>I</span> <span m=''3622180''>do</span>
  <span m=''3622530''>an</span> <span m=''3622660''>anti-Type</span> <span m=''3623320''>I</span>
  <span m=''3623490''>operation.</span> </p><p><span m=''3629680''>So</span> <span
  m=''3629760''>that''s</span> <span m=''3631420''>this</span> <span m=''3631520''>scenario.</span>
  <span m=''3632500''>If I</span> <span m=''3632560''>have</span> <span m=''3633070''>any</span>
  <span m=''3633290''>degree-2</span> <span m=''3633790''>Vertex,</span> <span m=''3634220''>I</span>
  <span m=''3634340''>remove</span> <span m=''3634750''>it.</span> <span m=''3638350''>And</span>
  <span m=''3638790''>I</span> <span m=''3638830''>want</span> <span m=''3639000''>to</span>
  <span m=''3639060''>induct</span> <span m=''3639480''>on</span> <span m=''3639600''>the</span>
  <span m=''3639680''>rest.</span> <span m=''3640100''>Now,</span> <span m=''3640270''>what</span>
  <span m=''3640380''>do</span> <span m=''3640450''>I</span> <span m=''3640810''>need
  to induct?</span> <span m=''3641170''>I</span> <span m=''3641530''>need</span> <span
  m=''3641760''>to</span> <span m=''3641870''>know</span> <span m=''3642680''>that</span>
  <span m=''3643530''>this</span> <span m=''3643730''>property</span> <span m=''3644800''>still</span>
  <span m=''3645200''>holds</span> <span m=''3646280''>on</span> <span m=''3646510''>my</span>
  <span m=''3646630''>smaller</span> <span m=''3647040''>graph.</span> </p><p><span
  m=''3647570''>When</span> <span m=''3647750''>I</span> <span m=''3647790''>remove</span>
  <span m=''3648120''>this</span> <span m=''3648290''>vertex,</span> <span m=''3649560''>I</span>
  <span m=''3649650''>want</span> <span m=''3649840''>the</span> <span m=''3649910''>remaining</span>
  <span m=''3650250''>graph</span> <span m=''3650510''>to</span> <span m=''3650630''>still</span>
  <span m=''3650850''>have</span> <span m=''3651040''>this</span> <span m=''3651210''>property.</span>
  <span m=''3652970''>Does it</span> <span m=''3653260''>have</span> <span m=''3653400''>2n</span>
  <span m=''3653660''>minus</span> <span m=''3653930''>3</span> <span m=''3654100''>edges,</span>
  <span m=''3654500''>for</span> <span m=''3654640''>the</span> <span m=''3654750''>new</span>
  <span m=''3654890''>value</span> <span m=''3655260''>of n,</span> <span m=''3655560''>n</span>
  <span m=''3655790''>being</span> <span m=''3656380''>n</span> <span m=''3656550''>minus</span>
  <span m=''3656830''>1</span> <span m=''3657080''>now?</span> <span m=''3657920''>Yeah,</span>
  <span m=''3658160''>because</span> <span m=''3658340''>I</span> <span m=''3658490''>removed</span>
  <span m=''3658810''>two</span> <span m=''3658980''>edges.</span> <span m=''3659260''>I
  removed</span> <span m=''3659540''>one</span> <span m=''3659700''>vertex.</span>
  <span m=''3660180''>So it</span> <span m=''3660310''>still</span> <span m=''3660500''>has</span>
  <span m=''3660640''>the</span> <span m=''3660720''>right</span> <span m=''3660870''>number</span>
  <span m=''3661070''>of</span> <span m=''3661140''>edges.</span> <span m=''3662260''>We''ve
  already</span> <span m=''3662470''>checked</span> <span m=''3662730''>that.</span>
  </p><p><span m=''3663930''>And</span> <span m=''3664120''>I</span> <span m=''3664170''>need</span>
  <span m=''3664320''>to</span> <span m=''3664410''>check</span> <span m=''3664610''>that</span>
  <span m=''3664720''>every</span> <span m=''3664940''>subset</span> <span m=''3665370''>of</span>
  <span m=''3665420''>the</span> <span m=''3665490''>vertices</span> <span m=''3666530''>over</span>
  <span m=''3666750''>here</span> <span m=''3667380''>has</span> <span m=''3667710''>at</span>
  <span m=''3667780''>most</span> <span m=''3668020''>2k</span> <span m=''3668310''>minus</span>
  <span m=''3668610''>3</span> <span m=''3668800''>edges.</span> <span m=''3669950''>That''s</span>
  <span m=''3670150''>still</span> <span m=''3670390''>true,</span> <span m=''3671130''>because</span>
  <span m=''3671340''>before</span> <span m=''3671670''>I</span> <span m=''3671720''>had</span>
  <span m=''3671840''>to</span> <span m=''3671910''>consider</span> <span m=''3672260''>all</span>
  <span m=''3672440''>subsets</span> <span m=''3672920''>containing</span> <span m=''3673260''>this</span>
  <span m=''3673400''>one</span> <span m=''3673550''>or</span> <span m=''3673660''>not.</span>
  <span m=''3674350''>Now</span> <span m=''3674520''>I''m</span> <span m=''3674590''>just</span>
  <span m=''3674770''>looking</span> <span m=''3674940''>at</span> <span m=''3675090''>subsets</span>
  <span m=''3675350''>that</span> <span m=''3675830''>don''t</span> <span m=''3676060''>contain</span>
  <span m=''3676400''>it.</span> <span m=''3677150''>So</span> <span m=''3680180''>I</span>
  <span m=''3680280''>still</span> <span m=''3680490''>have</span> <span m=''3680610''>the
  Laman</span> <span m=''3681020''>conditions</span> <span m=''3681460''>holding</span>
  <span m=''3682320''>for</span> <span m=''3682440''>the</span> <span m=''3682560''>smaller</span>
  <span m=''3682990''>graph</span> <span m=''3684280''>in</span> <span m=''3684350''>here.</span>
  </p><p><span m=''3685930''>Therefore, I can</span> <span m=''3686280''>induct,</span>
  <span m=''3690536''>and we''re</span> <span m=''3691000''>done.</span> <span m=''3693100''>And</span>
  <span m=''3693250''>we''re</span> <span m=''3693370''>done</span> <span m=''3693710''>because</span>
  <span m=''3694360''>then</span> <span m=''3694520''>we</span> <span m=''3694650''>conclude</span>
  <span m=''3695050''>that</span> <span m=''3695160''>the</span> <span m=''3695260''>smaller</span>
  <span m=''3695610''>graph</span> <span m=''3695830''>is</span> <span m=''3695920''>minimally</span>
  <span m=''3696240''>generically</span> <span m=''3696640''>rigid.</span> <span m=''3696980''>And</span>
  <span m=''3697080''>then</span> <span m=''3697250''>property</span> <span m=''3698130''>two</span>
  <span m=''3699330''>tells</span> <span m=''3699710''>us</span> <span m=''3700030''>that</span>
  <span m=''3700800''>this</span> <span m=''3701000''>thing''s</span> <span m=''3701220''>minimally</span>
  <span m=''3701540''>generically</span> <span m=''3701900''>rigid,</span> <span m=''3702190''>and</span>
  <span m=''3702250''>then I</span> <span m=''3702360''>add</span> <span m=''3702560''>this</span>
  <span m=''3702680''>vertex,</span> <span m=''3703020''>two</span> <span m=''3703160''>edges,</span>
  <span m=''3703400''>it''ll</span> <span m=''3703550''>still</span> <span m=''3703760''>be</span>
  <span m=''3703880''>minimally</span> <span m=''3704210''>generically</span> <span
  m=''3704600''>rigid.</span> <span m=''3705370''>And</span> <span m=''3705470''>that''s</span>
  <span m=''3705670''>what</span> <span m=''3705800''>I</span> <span m=''3705850''>wanted</span>
  <span m=''3706150''>to</span> <span m=''3706240''>conclude</span> <span m=''3707500''>in
  the</span> <span m=''3708440''>left</span> <span m=''3709240''>implication</span>
  <span m=''3709770''>direction.</span> </p><p><span m=''3710890''>The</span> <span
  m=''3710970''>hard</span> <span m=''3711170''>case</span> <span m=''3712030''>is</span>
  <span m=''3712210''>degree</span> <span m=''3712440''>three.</span> <span m=''3715810''>Again,</span>
  <span m=''3716050''>there''s</span> <span m=''3716190''>more</span> <span m=''3716350''>than</span>
  <span m=''3716450''>one</span> <span m=''3716580''>Type</span> <span m=''3716770''>II</span>
  <span m=''3716910''>operation.</span> <span m=''3718610''>I</span> <span m=''3719050''>already</span>
  <span m=''3719290''>wave</span> <span m=''3719550''>my</span> <span m=''3719700''>hands,</span>
  <span m=''3720390''>claiming</span> <span m=''3720960''>that</span> <span m=''3721480''>there</span>
  <span m=''3721720''>is</span> <span m=''3722680''>an</span> <span m=''3722760''>operation</span>
  <span m=''3723270''>you</span> <span m=''3723430''>can</span> <span m=''3723550''>do</span>
  <span m=''3725040''>so that</span> <span m=''3725230''>the</span> <span m=''3725430''>result</span>
  <span m=''3725940''>is</span> <span m=''3726130''>minimally</span> <span m=''3726480''>generically</span>
  <span m=''3726920''>rigid.</span> <span m=''3732580''>But</span> <span m=''3732710''>is</span>
  <span m=''3732860''>that</span> <span m=''3733060''>enough?</span> <span m=''3733640''>I</span>
  <span m=''3734090''>have to</span> <span m=''3734230''>think</span> <span m=''3734380''>about</span>
  <span m=''3734580''>it</span> <span m=''3734660''>for a</span> <span m=''3734780''>second.</span>
  <span m=''3736400''>It''s</span> <span m=''3736570''>minimally</span> <span m=''3737100''>generically</span>
  <span m=''3737750''>rigid.</span> </p><p><span m=''3743880''>Ah,</span> <span m=''3744220''>it''s
  not enough.</span> <span m=''3744835''>It''s</span> <span m=''3745110''>annoying.</span>
  <span m=''3747040''>That''s</span> <span m=''3747240''>what</span> <span m=''3747360''>I</span>
  <span m=''3747420''>thought.</span> <span m=''3748970''>I''m</span> <span m=''3749070''>not</span>
  <span m=''3749210''>surprised,</span> <span m=''3749790''>but</span> <span m=''3749840''>I''m</span>
  <span m=''3749960''>re-surprised.</span> <span m=''3750660''>Whatever.</span> <span
  m=''3753780''>For</span> <span m=''3753930''>this</span> <span m=''3754260''>theory</span>
  <span m=''3754590''>property</span> <span m=''3754980''>to</span> <span m=''3755040''>hold,</span>
  <span m=''3755690''>I</span> <span m=''3755810''>need</span> <span m=''3756350''>that</span>
  <span m=''3756570''>the</span> <span m=''3756780''>graph</span> <span m=''3757090''>I</span>
  <span m=''3757150''>have</span> <span m=''3757440''>is</span> <span m=''3757580''>minimally</span>
  <span m=''3757920''>generically</span> <span m=''3758360''>rigid.</span> <span m=''3759050''>That''s</span>
  <span m=''3759260''>what</span> <span m=''3759390''>I</span> <span m=''3759440''>want</span>
  <span m=''3759640''>to</span> <span m=''3759710''>prove.</span> <span m=''3760670''>I</span>
  <span m=''3760790''>don''t</span> <span m=''3760930''>know</span> <span m=''3761050''>that</span>
  <span m=''3761180''>that''s</span> <span m=''3761400''>true.</span> <span m=''3762890''>So</span>
  <span m=''3762900''>I</span> <span m=''3762940''>can''t</span> <span m=''3763200''>use</span>
  <span m=''3763380''>property</span> <span m=''3763750''>four.</span> <span m=''3764790''>Sucks</span>
  <span m=''3765070''>to</span> <span m=''3765160''>be</span> <span m=''3765280''>me.</span>
  </p><p><span m=''3768890''>I''m</span> <span m=''3769050''>trying</span> <span m=''3769280''>to</span>
  <span m=''3769340''>prove</span> <span m=''3769590''>the</span> <span m=''3769670''>graph</span>
  <span m=''3769920''>is</span> <span m=''3770030''>minimally</span> <span m=''3770330''>generically</span>
  <span m=''3770710''>rigid.</span> <span m=''3770960''>All</span> <span m=''3771150''>I</span>
  <span m=''3771250''>have</span> <span m=''3771440''>is</span> <span m=''3771560''>degree-3</span>
  <span m=''3772020''>vertex,</span> <span m=''3772440''>and</span> <span m=''3772520''>I</span>
  <span m=''3772570''>have</span> <span m=''3772770''>Laman''s</span> <span m=''3773160''>condition.</span>
  <span m=''3774110''>I</span> <span m=''3774210''>don''t</span> <span m=''3774240''>know</span>
  <span m=''3774400''>whether</span> <span m=''3774590''>property</span> <span m=''3774970''>four</span>
  <span m=''3776740''>applies</span> <span m=''3777300''>to</span> <span m=''3777400''>my</span>
  <span m=''3777520''>scenario.</span> <span m=''3778640''>So</span> <span m=''3778790''>we''ve</span>
  <span m=''3778870''>got</span> <span m=''3779010''>to</span> <span m=''3779080''>do</span>
  <span m=''3779210''>work.</span> <span m=''3782030''>And</span> <span m=''3783790''>wow.</span>
  <span m=''3791480''>See</span> <span m=''3791760''>what</span> <span m=''3791900''>I</span>
  <span m=''3791980''>can</span> <span m=''3792570''>do to</span> <span m=''3792820''>this</span>
  <span m=''3793030''>proof.</span> </p><p><span m=''3815050''>In</span> <span m=''3815180''>the</span>
  <span m=''3815280''>degree-3</span> <span m=''3815790''>case,</span> <span m=''3816440''>I</span>
  <span m=''3816560''>want</span> <span m=''3816820''>to</span> <span m=''3816880''>find</span>
  <span m=''3817200''>an</span> <span m=''3817300''>anti-Type</span> <span m=''3817810''>II</span>
  <span m=''3817990''>operation.</span> <span m=''3821170''>Presumably</span> <span
  m=''3821640''>they''re</span> <span m=''3821840''>out</span> <span m=''3822040''>there,</span>
  <span m=''3822270''>but</span> <span m=''3822970''>I</span> <span m=''3823060''>need</span>
  <span m=''3823450''>a</span> <span m=''3823550''>good</span> <span m=''3823770''>one.</span>
  <span m=''3824390''>For</span> <span m=''3824600''>me,</span> <span m=''3824800''>good</span>
  <span m=''3825160''>means</span> <span m=''3825900''>it</span> <span m=''3826030''>should</span>
  <span m=''3826210''>preserve</span> <span m=''3826690''>the Laman</span> <span m=''3827130''>condition.</span>
  <span m=''3828050''>So</span> <span m=''3828180''>after</span> <span m=''3828560''>I</span>
  <span m=''3828630''>do</span> <span m=''3828770''>the</span> <span m=''3828890''>anti-Type</span>
  <span m=''3829360''>II,</span> <span m=''3829530''>after</span> <span m=''3829910''>I  delete</span>
  <span m=''3830370''>those</span> <span m=''3830550''>three</span> <span m=''3830760''>edges,</span>
  <span m=''3831150''>delete</span> <span m=''3831390''>the</span> <span m=''3831460''>vertex,</span>
  <span m=''3831880''>add</span> <span m=''3832140''>one</span> <span m=''3832360''>edge</span>
  <span m=''3832620''>back,</span> <span m=''3834690''>I</span> <span m=''3834810''>want</span>
  <span m=''3835160''>this</span> <span m=''3835390''>to</span> <span m=''3835500''>still</span>
  <span m=''3835790''>hold.</span> </p><p><span m=''3839420''>Now,</span> <span m=''3839620''>there''s</span>
  <span m=''3839920''>essentially</span> <span m=''3840310''>two</span> <span m=''3840490''>things</span>
  <span m=''3840750''>that</span> <span m=''3840830''>could</span> <span m=''3840960''>go</span>
  <span m=''3841130''>wrong</span> <span m=''3841990''>for</span> <span m=''3842140''>this</span>
  <span m=''3842330''>to</span> <span m=''3842420''>still</span> <span m=''3842650''>hold.</span>
  <span m=''3843470''>One</span> <span m=''3843720''>is</span> <span m=''3843940''>you</span>
  <span m=''3844070''>go</span> <span m=''3844220''>to</span> <span m=''3844350''>add
  an</span> <span m=''3844640''>edge,</span> <span m=''3845340''>and</span> <span
  m=''3845500''>it''s</span> <span m=''3845630''>already</span> <span m=''3845940''>there.</span>
  <span m=''3847240''>If it''s</span> <span m=''3847280''>already</span> <span m=''3847600''>there,</span>
  <span m=''3848940''>you</span> <span m=''3849020''>can''t</span> <span m=''3849210''>really</span>
  <span m=''3849410''>add</span> <span m=''3849560''>it</span> <span m=''3849640''>again,</span>
  <span m=''3850650''>and</span> <span m=''3850830''>then</span> <span m=''3851090''>the</span>
  <span m=''3851160''>number</span> <span m=''3851410''>of</span> <span m=''3851470''>edges</span>
  <span m=''3851820''>will</span> <span m=''3851950''>be</span> <span m=''3852100''>wrong.</span>
  <span m=''3852680''>You</span> <span m=''3852870''>always</span> <span m=''3852990''>want
  to</span> <span m=''3853170''>have</span> <span m=''3853340''>2n</span> <span m=''3853600''>minus</span>
  <span m=''3853880''>3</span> <span m=''3854090''>as</span> <span m=''3854200''>you</span>
  <span m=''3854310''>go</span> <span m=''3854450''>down.</span> <span m=''3855480''>If</span>
  <span m=''3855640''>I</span> <span m=''3855750''>try</span> <span m=''3855980''>to</span>
  <span m=''3856080''>add</span> <span m=''3856270''>an</span> <span m=''3856370''>edge</span>
  <span m=''3856640''>and</span> <span m=''3856700''>it</span> <span m=''3856780''>doesn''t</span>
  <span m=''3857100''>work</span> <span m=''3857320''>out--</span> <span m=''3857560''>because</span>
  <span m=''3857750''>the</span> <span m=''3857830''>whole</span> <span m=''3857970''>point</span>
  <span m=''3858150''>is</span> <span m=''3858270''>I''m</span> <span m=''3858350''>supposed</span>
  <span m=''3858610''>to</span> <span m=''3858690''>remove</span> <span m=''3858990''>three,</span>
  <span m=''3859230''>add</span> <span m=''3859440''>one.</span> <span m=''3860260''>If
  I</span> <span m=''3860340''>don''t</span> <span m=''3860540''>actually</span> <span
  m=''3860780''>succeed</span> <span m=''3861160''>in</span> <span m=''3861250''>adding</span>
  <span m=''3861490''>one,</span> <span m=''3861680''>it''ll</span> <span m=''3861800''>be</span>
  <span m=''3861920''>the</span> <span m=''3862050''>wrong</span> <span m=''3862280''>number.</span>
  </p><p><span m=''3863700''>So</span> <span m=''3863890''>first</span> <span m=''3864160''>thing</span>
  <span m=''3864300''>you</span> <span m=''3864390''>need</span> <span m=''3864550''>to</span>
  <span m=''3864640''>check</span> <span m=''3865480''>is</span> <span m=''3865700''>that--</span>
  <span m=''3866870''>so</span> <span m=''3866980''>I</span> <span m=''3867030''>take</span>
  <span m=''3867270''>this</span> <span m=''3867430''>degree-3</span> <span m=''3867900''>vertex.</span>
  <span m=''3868990''>Here</span> <span m=''3869240''>it</span> <span m=''3869290''>is.</span>
  <span m=''3871040''>Now</span> <span m=''3871330''>it''s</span> <span m=''3871440''>all</span>
  <span m=''3871770''>about</span> <span m=''3872380''>its</span> <span m=''3872530''>neighbors,</span>
  <span m=''3872990''>these</span> <span m=''3873180''>three</span> <span m=''3873360''>guys.</span>
  <span m=''3874410''>If</span> <span m=''3874900''>all</span> <span m=''3875220''>three</span>
  <span m=''3875530''>of</span> <span m=''3875590''>those</span> <span m=''3875810''>exist,</span>
  <span m=''3876740''>I</span> <span m=''3876900''>would</span> <span m=''3877070''>be</span>
  <span m=''3877180''>in</span> <span m=''3877300''>trouble.</span> </p><p><span m=''3878510''>Fortunately,</span>
  <span m=''3879600''>that</span> <span m=''3879770''>can''t</span> <span m=''3879970''>happen.</span>
  <span m=''3880600''>This</span> <span m=''3880790''>is</span> <span m=''3880900''>the</span>
  <span m=''3881000''>picture</span> <span m=''3881330''>I</span> <span m=''3881350''>drew</span>
  <span m=''3881640''>that</span> <span m=''3881760''>cannot</span> <span m=''3882070''>happen.</span>
  <span m=''3882460''>This</span> <span m=''3882610''>is</span> <span m=''3882700''>over-braced.</span>
  <span m=''3883320''>There''s</span> <span m=''3883460''>too</span> <span m=''3883600''>many</span>
  <span m=''3883790''>edges</span> <span m=''3884080''>here.</span> <span m=''3884510''>This</span>
  <span m=''3884670''>is</span> <span m=''3884800''>a</span> <span m=''3884870''>subset</span>
  <span m=''3885270''>of</span> <span m=''3885380''>four</span> <span m=''3885560''>vertices.</span>
  <span m=''3886360''>It has</span> <span m=''3886550''>more</span> <span m=''3886860''>than</span>
  <span m=''3887000''>2k</span> <span m=''3887770''>minus</span> <span m=''3888100''>3</span>
  <span m=''3888270''>edges.</span> <span m=''3889130''>So</span> <span m=''3889140''>by</span>
  <span m=''3889270''>Laman''s</span> <span m=''3889650''>condition,</span> <span
  m=''3889950''>this</span> <span m=''3890100''>can''t</span> <span m=''3890290''>hold.</span>
  <span m=''3890870''>Some</span> <span m=''3891270''>edge</span> <span m=''3891570''>must</span>
  <span m=''3891850''>be</span> <span m=''3891960''>missing.</span> <span m=''3893490''>That''s</span>
  <span m=''3893670''>the one</span> <span m=''3893910''>we''ll</span> <span m=''3894040''>target.</span>
  <span m=''3895510''>So</span> <span m=''3895640''>at</span> <span m=''3895690''>least</span>
  <span m=''3895920''>there''s</span> <span m=''3896080''>an</span> <span m=''3896190''>edge</span>
  <span m=''3896580''>that''s</span> <span m=''3896770''>missing.</span> <span m=''3897565''>That''s</span>
  <span m=''3897960''>property</span> <span m=''3898310''>one.</span> </p><p><span
  m=''3900060''>There''s</span> <span m=''3900240''>another</span> <span m=''3900530''>thing</span>
  <span m=''3900710''>that</span> <span m=''3900840''>could go</span> <span m=''3901100''>wrong,</span>
  <span m=''3901420''>though,</span> <span m=''3902840''>which</span> <span m=''3903040''>is</span>
  <span m=''3903180''>I</span> <span m=''3903250''>go</span> <span m=''3903490''>to</span>
  <span m=''3903610''>add in</span> <span m=''3903980''>this</span> <span m=''3904170''>edge,</span>
  <span m=''3905550''>and</span> <span m=''3905760''>somehow</span> <span m=''3906240''>the</span>
  <span m=''3906420''>other</span> <span m=''3906630''>part</span> <span m=''3906880''>of</span>
  <span m=''3906940''>the</span> <span m=''3907040''>condition--</span> <span m=''3907990''>the</span>
  <span m=''3908100''>subset</span> <span m=''3908570''>property--</span> <span m=''3909460''>doesn''t</span>
  <span m=''3909720''>hold.</span> <span m=''3911210''>Now,</span> <span m=''3911390''>what</span>
  <span m=''3911610''>could</span> <span m=''3911740''>that</span> <span m=''3911930''>possibly</span>
  <span m=''3912450''>look</span> <span m=''3912650''>like?</span> <span m=''3913760''>It</span>
  <span m=''3913890''>would</span> <span m=''3913980''>have</span> <span m=''3914190''>to</span>
  <span m=''3914300''>be</span> <span m=''3914490''>a</span> <span m=''3914540''>subset</span>
  <span m=''3914980''>of</span> <span m=''3915020''>vertices.</span> </p><p><span
  m=''3920120''>It</span> <span m=''3920240''>should</span> <span m=''3920450''>at</span>
  <span m=''3920530''>least</span> <span m=''3920900''>contain</span> <span m=''3921350''>these</span>
  <span m=''3921570''>two</span> <span m=''3921710''>vertices.</span> <span m=''3923690''>Actually,
  it</span> <span m=''3924090''>probably</span> <span m=''3924400''>shouldn''t</span>
  <span m=''3924720''>contain</span> <span m=''3925070''>this</span> <span m=''3925250''>one.</span>
  <span m=''3928030''>This</span> <span m=''3928330''>requires</span> <span m=''3928670''>some</span>
  <span m=''3928850''>thinking.</span> <span m=''3931490''>I</span> <span m=''3931580''>mean,</span>
  <span m=''3931780''>if</span> <span m=''3931930''>it</span> <span m=''3932030''>contained</span>
  <span m=''3932340''>this</span> <span m=''3932490''>one,</span> <span m=''3932650''>it''s</span>
  <span m=''3932780''>no</span> <span m=''3932890''>big</span> <span m=''3933070''>deal.</span>
  <span m=''3933310''>I</span> <span m=''3933360''>mean,</span> <span m=''3933550''>it''s</span>
  <span m=''3933710''>got</span> <span m=''3935140''>do</span> <span m=''3935230''>one</span>
  <span m=''3935370''>more</span> <span m=''3935520''>vertex,</span> <span m=''3935910''>two</span>
  <span m=''3936040''>more</span> <span m=''3936220''>edges.</span> <span m=''3936660''>Who</span>
  <span m=''3936780''>cares.</span> </p><p><span m=''3940250''>But</span> <span m=''3940580''>if</span>
  <span m=''3941700''>you</span> <span m=''3941810''>just</span> <span m=''3942030''>look</span>
  <span m=''3942160''>at</span> <span m=''3942240''>one</span> <span m=''3942370''>of</span>
  <span m=''3942450''>these</span> <span m=''3942640''>subsets,</span> <span m=''3943840''>then</span>
  <span m=''3944490''>in</span> <span m=''3944610''>this</span> <span m=''3944780''>subset,</span>
  <span m=''3945100''>you''re</span> <span m=''3945250''>adding</span> <span m=''3945580''>an</span>
  <span m=''3945650''>edge.</span> <span m=''3946140''>That''s</span> <span m=''3946450''>in</span>
  <span m=''3946540''>general</span> <span m=''3946890''>a</span> <span m=''3946950''>bad</span>
  <span m=''3947250''>idea,</span> <span m=''3948050''>because</span> <span m=''3948200''>if</span>
  <span m=''3948320''>it</span> <span m=''3948440''>had</span> <span m=''3948620''>exactly</span>
  <span m=''3949070''>2k</span> <span m=''3949400''>minus</span> <span m=''3949700''>3</span>
  <span m=''3949880''>before</span> <span m=''3950360''>and</span> <span m=''3950450''>now</span>
  <span m=''3950580''>I</span> <span m=''3950650''>add</span> <span m=''3950900''>an</span>
  <span m=''3950990''>edge,</span> <span m=''3951900''>it''ll</span> <span m=''3952090''>have</span>
  <span m=''3952260''>too</span> <span m=''3952410''>many</span> <span m=''3952670''>edges.</span>
  <span m=''3953660''>That would</span> <span m=''3953880''>be</span> <span m=''3954000''>bad.</span>
  </p><p><span m=''3954330''>So</span> <span m=''3954460''>somehow</span> <span m=''3955340''>I</span>
  <span m=''3955410''>want</span> <span m=''3955500''>to</span> <span m=''3955600''>say</span>
  <span m=''3955710''>there''s</span> <span m=''3955860''>some</span> <span m=''3956070''>place</span>
  <span m=''3956340''>I</span> <span m=''3956400''>can</span> <span m=''3956560''>add</span>
  <span m=''3956770''>an</span> <span m=''3956880''>edge</span> <span m=''3957740''>where</span>
  <span m=''3959300''>there</span> <span m=''3959520''>was</span> <span m=''3959680''>slack,</span>
  <span m=''3960740''>where</span> <span m=''3960850''>there</span> <span m=''3960940''>were</span>
  <span m=''3961050''>less</span> <span m=''3961460''>than</span> <span m=''3961630''>2k</span>
  <span m=''3962560''>minus</span> <span m=''3962890''>3</span> <span m=''3963070''>edges.</span>
  <span m=''3963950''>And</span> <span m=''3964080''>so</span> <span m=''3964210''>when</span>
  <span m=''3964360''>I</span> <span m=''3964430''>add</span> <span m=''3964670''>this</span>
  <span m=''3964850''>in,</span> <span m=''3965420''>I''m</span> <span m=''3965560''>OK.</span>
  <span m=''3968370''>It''s</span> <span m=''3968490''>a</span> <span m=''3968530''>little</span>
  <span m=''3968710''>tricky</span> <span m=''3968970''>to</span> <span m=''3969040''>argue.</span>
  <span m=''3970140''>What</span> <span m=''3970340''>we</span> <span m=''3970470''>do</span>
  <span m=''3971720''>is</span> <span m=''3971860''>suppose--</span> <span m=''3973560''>we''re
  going to</span> <span m=''3973770''>argue</span> <span m=''3974060''>by</span> <span
  m=''3974200''>contradiction.</span> <span m=''3975700''>If</span> <span m=''3975900''>this</span>
  <span m=''3976090''>is</span> <span m=''3976210''>impossible--</span> <span m=''3977210''>so</span>
  <span m=''3977320''>I''m</span> <span m=''3977380''>going</span> <span m=''3977460''>to</span>
  <span m=''3977520''>try</span> <span m=''3977810''>for</span> <span m=''3977930''>these</span>
  <span m=''3978120''>two</span> <span m=''3978220''>vertices,</span> <span m=''3978670''>then</span>
  <span m=''3978790''>I''ll</span> <span m=''3978870''>try</span> <span m=''3979060''>it
  for</span> <span m=''3979170''>these</span> <span m=''3979350''>two</span> <span
  m=''3979460''>vertices,</span> <span m=''3979880''>then I''ll</span> <span m=''3980000''>try
  for</span> <span m=''3980280''>these</span> <span m=''3980560''>two--</span> <span
  m=''3981400''>three</span> <span m=''3981650''>choices.</span> <span m=''3982890''>If</span>
  <span m=''3983050''>they</span> <span m=''3983230''>all</span> <span m=''3983520''>fail,</span>
  <span m=''3984580''>I</span> <span m=''3984690''>claim</span> <span m=''3985050''>there''s</span>
  <span m=''3985200''>a</span> <span m=''3985260''>contradiction.</span> <span m=''3987310''>And</span>
  <span m=''3987820''>I</span> <span m=''3987920''>will</span> <span m=''3988270''>try</span>
  <span m=''3988490''>to</span> <span m=''3988560''>sketch</span> <span m=''3988870''>this</span>
  <span m=''3989040''>for</span> <span m=''3989230''>you.</span> </p><p><span m=''3989890''>So</span>
  <span m=''3990070''>let''s</span> <span m=''3990300''>say</span> <span m=''3991110''>there</span>
  <span m=''3991300''>are</span> <span m=''3991680''>Si--</span> <span m=''3992720''>I</span>
  <span m=''3992980''>have</span> <span m=''3993130''>some</span> <span m=''3993300''>subset</span>
  <span m=''3993710''>of</span> <span m=''3993760''>vertices</span> <span m=''3994170''>Si--</span>
  <span m=''3995710''>and</span> <span m=''3996910''>i is</span> <span m=''3997230''>one,</span>
  <span m=''3997530''>two,</span> <span m=''3997740''>or</span> <span m=''3997820''>three.</span>
  <span m=''3999880''>And</span> <span m=''4001140''>this will</span> <span m=''4001330''>turn</span>
  <span m=''4001600''>out</span> <span m=''4001740''>to</span> <span m=''4001820''>be</span>
  <span m=''4001940''>the</span> <span m=''4002030''>bad</span> <span m=''4002340''>case.</span>
  <span m=''4004540''>Suppose</span> <span m=''4004950''>that</span> <span m=''4005120''>it</span>
  <span m=''4005280''>contains--</span> <span m=''4007660''>I didn''t</span> <span
  m=''4007980''>give</span> <span m=''4008110''>these</span> <span m=''4008280''>labels.</span>
  <span m=''4008900''>This</span> <span m=''4009010''>is</span> <span m=''4009150''>V,</span>
  <span m=''4010440''>V1,</span> <span m=''4011730''>V2,</span> <span m=''4013000''>V3.</span>
  <span m=''4014510''>So</span> <span m=''4014640''>it''s</span> <span m=''4014760''>going</span>
  <span m=''4014870''>to</span> <span m=''4014940''>contain</span> <span m=''4015570''>Vi
  plus</span> <span m=''4015830''>1</span> <span m=''4017640''>and</span> <span m=''4017920''>Vi</span>
  <span m=''4018190''>plus</span> <span m=''4018530''>2--</span> <span m=''4019130''>those</span>
  <span m=''4019320''>are</span> <span m=''4019390''>the</span> <span m=''4019540''>other</span>
  <span m=''4019760''>two</span> <span m=''4019940''>vertices</span> <span m=''4021560''>from</span>
  <span m=''4021850''>i--</span> <span m=''4025030''>but</span> <span m=''4025180''>not</span>
  <span m=''4025480''>V.</span> <span m=''4027216''>Not</span> <span m=''4027660''>the</span>
  <span m=''4027740''>vertex</span> <span m=''4028150''>that I</span> <span m=''4028240''>added,</span>
  <span m=''4028740''>because</span> <span m=''4029180''>that</span> <span m=''4029540''>turns</span>
  <span m=''4029850''>out</span> <span m=''4029940''>not</span> <span m=''4030110''>to</span>
  <span m=''4030190''>matter.</span> </p><p><span m=''4031130''>And</span> <span m=''4031280''>suppose</span>
  <span m=''4032610''>that</span> <span m=''4032950''>it</span> <span m=''4033100''>induces</span>
  <span m=''4034920''>exactly</span> <span m=''4035700''>2k--</span> <span m=''4037560''>what''s</span>
  <span m=''4037740''>k</span> <span m=''4037960''>here?</span> <span m=''4038170''>Size</span>
  <span m=''4038480''>of</span> <span m=''4038590''>Si--</span> <span m=''4041220''>minus</span>
  <span m=''4041570''>3</span> <span m=''4045030''>edges.</span> <span m=''4047885''>It</span>
  <span m=''4048360''>has</span> <span m=''4048610''>Si</span> <span m=''4049100''>edges.</span>
  <span m=''4049630''>If it</span> <span m=''4049720''>has</span> <span m=''4049960''>exactly</span>
  <span m=''4050470''>2Si</span> <span m=''4051020''>minus</span> <span m=''4051330''>3</span>
  <span m=''4051520''>edges,</span> <span m=''4051810''>I</span> <span m=''4051880''>can''t</span>
  <span m=''4052180''>add</span> <span m=''4052330''>another</span> <span m=''4052610''>one.</span>
  <span m=''4053480''>And if</span> <span m=''4053700''>this</span> <span m=''4053910''>is</span>
  <span m=''4054030''>true</span> <span m=''4054980''>for</span> <span m=''4055150''>this</span>
  <span m=''4055360''>pair</span> <span m=''4055680''>and</span> <span m=''4055860''>for</span>
  <span m=''4055950''>this</span> <span m=''4056130''>pair</span> <span m=''4056360''>and</span>
  <span m=''4056490''>for</span> <span m=''4056570''>this</span> <span m=''4056740''>pair,</span>
  <span m=''4057590''>then</span> <span m=''4057780''>I''m</span> <span m=''4057860''>screwed.</span>
  <span m=''4058600''>So</span> <span m=''4059060''>suppose</span> <span m=''4059490''>that</span>
  <span m=''4059570''>it''s</span> <span m=''4059660''>true</span> <span m=''4059880''>for</span>
  <span m=''4060040''>all</span> <span m=''4060170''>three</span> <span m=''4060340''>pairs</span>
  <span m=''4061190''>of these</span> <span m=''4061400''>Sis.</span> </p><p><span
  m=''4065660''>Fun</span> <span m=''4065980''>fact.</span> <span m=''4066520''>Let''s</span>
  <span m=''4066590''>look</span> <span m=''4066830''>at</span> <span m=''4067340''>all</span>
  <span m=''4067710''>of</span> <span m=''4067820''>the</span> <span m=''4067990''>edges</span>
  <span m=''4068490''>among</span> <span m=''4070900''>S1</span> <span m=''4071350''>and</span>
  <span m=''4071490''>S2.</span> <span m=''4072020''>Let''s</span> <span m=''4072200''>start</span>
  <span m=''4072310''>combining</span> <span m=''4072760''>these</span> <span m=''4072910''>sets</span>
  <span m=''4073170''>in</span> <span m=''4073270''>different</span> <span m=''4073510''>ways.</span>
  <span m=''4080350''>Speed</span> <span m=''4080470''>through</span> <span m=''4080640''>this
  a</span> <span m=''4080870''>little.</span> <span m=''4085380''>Something</span>
  <span m=''4085710''>called</span> <span m=''4086050''>inclusion-exclusion</span>
  <span m=''4086910''>principle,</span> <span m=''4088330''>which</span> <span m=''4088480''>is</span>
  <span m=''4088690''>I</span> <span m=''4088810''>have</span> <span m=''4088970''>these</span>
  <span m=''4089130''>two</span> <span m=''4089260''>sets</span> <span m=''4089560''>S1</span>
  <span m=''4090300''>and</span> <span m=''4090800''>S2.</span> <span m=''4091760''>They</span>
  <span m=''4091850''>might</span> <span m=''4092060''>overlap,</span> <span m=''4092630''>who</span>
  <span m=''4092750''>knows.</span> <span m=''4094200''>But</span> <span m=''4094330''>if</span>
  <span m=''4094440''>I</span> <span m=''4094490''>count</span> <span m=''4094710''>all</span>
  <span m=''4094900''>the</span> <span m=''4095030''>edges</span> <span m=''4095330''>in</span>
  <span m=''4095650''>both</span> <span m=''4095910''>of</span> <span m=''4096010''>them</span>
  <span m=''4096250''>together,</span> <span m=''4098979''>that''s</span> <span m=''4099149''>kind</span>
  <span m=''4099410''>of</span> <span m=''4099460''>like</span> <span m=''4099670''>counting</span>
  <span m=''4099960''>all</span> <span m=''4100040''>the</span> <span m=''4100140''>edges</span>
  <span m=''4100720''>in</span> <span m=''4101100''>here--</span> <span m=''4102140''>all</span>
  <span m=''4102340''>of</span> <span m=''4102439''>Si--</span> <span m=''4103029''>and</span>
  <span m=''4103189''>counting</span> <span m=''4103439''>all</span> <span m=''4103569''>the</span>
  <span m=''4103680''>edges</span> <span m=''4103920''>in S2--</span> <span m=''4104760''>and</span>
  <span m=''4104920''>then</span> <span m=''4105040''>removing</span> <span m=''4105479''>the</span>
  <span m=''4105560''>intersection</span> <span m=''4106170''>because</span> <span
  m=''4106370''>I</span> <span m=''4106420''>double-counted</span> <span m=''4107050''>there.</span>
  </p><p><span m=''4107674''>AUDIENCE: It''s</span> <span m=''4108108''>like</span>
  <span m=''4108542''>probability.</span> </p><p><span m=''4109410''>PROFESSOR: It''s</span>
  <span m=''4109620''>like</span> <span m=''4109760''>probability.</span> <span m=''4110300''>This</span>
  <span m=''4110470''>is</span> <span m=''4110580''>inclusion-exclusion.</span> <span
  m=''4111270''>It</span> <span m=''4111550''>exists</span> <span m=''4112100''>all</span>
  <span m=''4112260''>over</span> <span m=''4112359''>the</span> <span m=''4112460''>place.</span>
  <span m=''4113010''>Usually</span> <span m=''4113270''>it''s</span> <span m=''4113500''>combinatorics.</span>
  <span m=''4116660''>But</span> <span m=''4118410''>it''s</span> <span m=''4118529''>not</span>
  <span m=''4118670''>quite</span> <span m=''4119130''>accurate</span> <span m=''4119560''>here,</span>
  <span m=''4119779''>and</span> <span m=''4119850''>that''s</span> <span m=''4120029''>why</span>
  <span m=''4120149''>there''s</span> <span m=''4120290''>a</span> <span m=''4120340''>greater</span>
  <span m=''4120630''>than</span> <span m=''4120779''>or</span> <span m=''4120810''>equal</span>
  <span m=''4121029''>to.</span> <span m=''4121600''>Because</span> <span m=''4121770''>we''re</span>
  <span m=''4121850''>counting</span> <span m=''4122160''>edges</span> <span m=''4122430''>not</span>
  <span m=''4122590''>vertices,</span> <span m=''4122849''>it''s a</span> <span m=''4123109''>little</span>
  <span m=''4123319''>messier,</span> <span m=''4123870''>because</span> <span m=''4124370''>there''s</span>
  <span m=''4124520''>some</span> <span m=''4124720''>edges</span> <span m=''4124950''>you</span>
  <span m=''4125080''>miss,</span> <span m=''4125450''>like</span> <span m=''4126020''>an</span>
  <span m=''4126140''>edge</span> <span m=''4126390''>from</span> <span m=''4126569''>this</span>
  <span m=''4126750''>vertex</span> <span m=''4127250''>over</span> <span m=''4127490''>to</span>
  <span m=''4127580''>this</span> <span m=''4127790''>vertex.</span> <span m=''4129149''>You''ll</span>
  <span m=''4129279''>still</span> <span m=''4129470''>count</span> <span m=''4129770''>twice.</span>
  <span m=''4131380''>But</span> <span m=''4131520''>hey,</span> <span m=''4131890''>it''s</span>
  <span m=''4131990''>close</span> <span m=''4132200''>enough.</span> <span m=''4132850''>Greater</span>
  <span m=''4133069''>than</span> <span m=''4133220''>or</span> <span m=''4133250''>equal</span>
  <span m=''4133470''>to.</span> <span m=''4134710''>OK?</span> </p><p><span m=''4135540''>Now,</span>
  <span m=''4136090''>I</span> <span m=''4136270''>claim</span> <span m=''4137470''>this</span>
  <span m=''4137729''>thing</span> <span m=''4139060''>should</span> <span m=''4139399''>only</span>
  <span m=''4139740''>have</span> <span m=''4140100''>one</span> <span m=''4140399''>vertex</span>
  <span m=''4140870''>in it.</span> <span m=''4142754''>How the heck</span> <span
  m=''4143240''>could</span> <span m=''4143450''>I</span> <span m=''4143490''>claim</span>
  <span m=''4143750''>that?</span> <span m=''4144210''>Well,</span> <span m=''4144330''>let''s</span>
  <span m=''4144500''>suppose</span> <span m=''4144819''>that it</span> <span m=''4144930''>has</span>
  <span m=''4145109''>at</span> <span m=''4145160''>least</span> <span m=''4145399''>two</span>
  <span m=''4145540''>vertices.</span> <span m=''4148950''>And</span> <span m=''4149120''>then</span>
  <span m=''4149250''>I''m</span> <span m=''4149319''>going</span> <span m=''4149439''>to</span>
  <span m=''4149500''>get</span> <span m=''4149640''>a</span> <span m=''4149660''>contradiction.</span>
  <span m=''4150930''>So</span> <span m=''4153240''>I</span> <span m=''4153500''>guess</span>
  <span m=''4153740''>I</span> <span m=''4153790''>really</span> <span m=''4154029''>mean</span>
  <span m=''4155100''>this--</span> <span m=''4155405''>that</span> <span m=''4156470''>Si</span>
  <span m=''4156899''>intersects</span> <span m=''4157330''>S2.</span> </p><p><span
  m=''4158000''>I</span> <span m=''4158130''>claim</span> <span m=''4158399''>these</span>
  <span m=''4158550''>intersections</span> <span m=''4159029''>have</span> <span m=''4159160''>to</span>
  <span m=''4159240''>be</span> <span m=''4159359''>pretty</span> <span m=''4159609''>tiny.</span>
  <span m=''4160390''>The</span> <span m=''4160479''>reason</span> <span m=''4160810''>is,</span>
  <span m=''4161050''>if</span> <span m=''4161189''>it</span> <span m=''4161300''>weren''t,</span>
  <span m=''4162740''>what do</span> <span m=''4162960''>I</span> <span m=''4163090''>know</span>
  <span m=''4163319''>about</span> <span m=''4163990''>the</span> <span m=''4164100''>edges</span>
  <span m=''4164450''>induced</span> <span m=''4164790''>by</span> <span m=''4164910''>S1?</span>
  <span m=''4165399''>Well, it''s</span> <span m=''4165640''>a</span> <span m=''4165720''>subset,</span>
  <span m=''4166290''>so</span> <span m=''4166430''>it</span> <span m=''4166500''>satisfies</span>
  <span m=''4167189''>the</span> <span m=''4167370''>2K</span> <span m=''4167689''>minus</span>
  <span m=''4167979''>3</span> <span m=''4168130''>property.</span> </p><p><span m=''4169550''>So</span>
  <span m=''4169750''>it''s</span> <span m=''4169920''>going</span> <span m=''4170040''>to</span>
  <span m=''4170120''>be</span> <span m=''4171260''>greater than or equal</span> <span
  m=''4171729''>to,</span> <span m=''4172040''>right?</span> <span m=''4174899''>Actually,</span>
  <span m=''4175800''>I''d already</span> <span m=''4175970''>assumed</span> <span
  m=''4177649''>the</span> <span m=''4177740''>number</span> <span m=''4177930''>of</span>
  <span m=''4178010''>edges</span> <span m=''4178260''>induced</span> <span m=''4178600''>here
  is</span> <span m=''4178790''>exactly</span> <span m=''4179330''>twice</span> <span
  m=''4179700''>the</span> <span m=''4179779''>Sis</span> <span m=''4180140''>minus</span>
  <span m=''4180460''>3.</span> <span m=''4181170''>So</span> <span m=''4181240''>this</span>
  <span m=''4181359''>will</span> <span m=''4181439''>be</span> <span m=''4181620''>exactly</span>
  <span m=''4182170''>equal</span> <span m=''4182439''>to</span> <span m=''4183540''>2</span>
  <span m=''4183810''>times</span> <span m=''4184399''>S1</span> <span m=''4184920''>minus</span>
  <span m=''4185350''>3.</span> <span m=''4186660''>It''s</span> <span m=''4186770''>2</span>
  <span m=''4187090''>times</span> <span m=''4187689''>S2</span> <span m=''4188250''>minus</span>
  <span m=''4188659''>3,</span> <span m=''4190130''>and</span> <span m=''4190340''>then</span>
  <span m=''4190890''>the</span> <span m=''4190979''>same</span> <span m=''4191210''>thing</span>
  <span m=''4191390''>there.</span> <span m=''4192700''>OK?</span> </p><p><span m=''4192960''>But</span>
  <span m=''4193590''>this</span> <span m=''4195160''>is</span> <span m=''4195310''>some</span>
  <span m=''4195580''>subset.</span> <span m=''4196660''>As</span> <span m=''4196810''>long</span>
  <span m=''4197010''>as</span> <span m=''4197090''>it</span> <span m=''4197190''>has</span>
  <span m=''4197390''>at</span> <span m=''4197470''>least</span> <span m=''4197690''>two</span>
  <span m=''4197840''>vertices--</span> <span m=''4199460''>yeah,</span> <span m=''4199870''>this</span>
  <span m=''4200170''>should</span> <span m=''4200340''>be</span> <span m=''4200500''>k</span>
  <span m=''4200710''>greater</span> <span m=''4200940''>than</span> <span m=''4201080''>or</span>
  <span m=''4201160''>one.</span> <span m=''4202370''>Things</span> <span m=''4202600''>don''t
  quite</span> <span m=''4202940''>work</span> <span m=''4203200''>with</span> <span
  m=''4203300''>one</span> <span m=''4203460''>vertex,</span> <span m=''4203930''>because</span>
  <span m=''4204010''>then</span> <span m=''4204170''>it</span> <span m=''4204250''>says</span>
  <span m=''4204610''>2</span> <span m=''4204760''>times</span> <span m=''4204990''>1</span>
  <span m=''4205140''>minus</span> <span m=''4205400''>3.</span> <span m=''4205580''>It</span>
  <span m=''4205600''>should</span> <span m=''4205840''>have</span> <span m=''4206030''>negative</span>
  <span m=''4206400''>1</span> <span m=''4206570''>edges.</span> <span m=''4207550''>Ain''t</span>
  <span m=''4207730''>so.</span> <span m=''4208210''>It''s</span> <span m=''4208320''>got</span>
  <span m=''4208460''>zero</span> <span m=''4208730''>edges.</span> <span m=''4210180''>So</span>
  <span m=''4210240''>you</span> <span m=''4210290''>need</span> <span m=''4210490''>more</span>
  <span m=''4210630''>than</span> <span m=''4210750''>one</span> <span m=''4210930''>vertex</span>
  <span m=''4211340''>for</span> <span m=''4211430''>this</span> <span m=''4211700''>to</span>
  <span m=''4211820''>apply.</span> </p><p><span m=''4213630''>But</span> <span m=''4213750''>now</span>
  <span m=''4213930''>I</span> <span m=''4214020''>have</span> <span m=''4214200''>some</span>
  <span m=''4214370''>subset.</span> <span m=''4214840''>It</span> <span m=''4214950''>has</span>
  <span m=''4215180''>at</span> <span m=''4215250''>least</span> <span m=''4215480''>two</span>
  <span m=''4215590''>vertices,</span> <span m=''4216380''>let''s</span> <span m=''4216490''>say.</span>
  <span m=''4217260''>So</span> <span m=''4217710''>it</span> <span m=''4217850''>has</span>
  <span m=''4218190''>at</span> <span m=''4218290''>most</span> <span m=''4218550''>2k</span>
  <span m=''4218820''>minus</span> <span m=''4219140''>3</span> <span m=''4219320''>edges.</span>
  <span m=''4220240''>So</span> <span m=''4220280''>this</span> <span m=''4220480''>is</span>
  <span m=''4220600''>going</span> <span m=''4220740''>to</span> <span m=''4220830''>be</span>
  <span m=''4224080''>at</span> <span m=''4224380''>most--</span> <span m=''4226000''>it''s</span>
  <span m=''4226310''>confusing</span> <span m=''4226730''>because</span> <span m=''4226840''>everything''s</span>
  <span m=''4227210''>backwards.</span> <span m=''4230740''>Well, it''s</span> <span
  m=''4231010''>going</span> <span m=''4231120''>to</span> <span m=''4231190''>be</span>
  <span m=''4231330''>another</span> <span m=''4231860''>two</span> <span m=''4232090''>times</span>
  <span m=''4233020''>the</span> <span m=''4233060''>size</span> <span m=''4233310''>of</span>
  <span m=''4233400''>this</span> <span m=''4233570''>thing</span> <span m=''4233760''>minus</span>
  <span m=''4234100''>3.</span> <span m=''4234460''>So</span> <span m=''4234620''>I''m</span>
  <span m=''4234740''>just</span> <span m=''4234890''>going</span> <span m=''4234990''>to</span>
  <span m=''4235200''>collect</span> <span m=''4235560''>them</span> <span m=''4235710''>all</span>
  <span m=''4235820''>together.</span> <span m=''4236230''>We have</span> <span m=''4236680''>S1,</span>
  <span m=''4237750''>we</span> <span m=''4237850''>have</span> <span m=''4238050''>S2,</span>
  <span m=''4239540''>and the</span> <span m=''4239710''>one that</span> <span m=''4239830''>we</span>
  <span m=''4240020''>just</span> <span m=''4240180''>added</span> <span m=''4241050''>was</span>
  <span m=''4241460''>S1</span> <span m=''4241840''>intersect</span> <span m=''4242250''>S2</span>
  <span m=''4244870''>minus</span> <span m=''4246160''>9.</span> <span m=''4246780''>It''s</span>
  <span m=''4247110''>three</span> <span m=''4247390''>3s.</span> </p><p><span m=''4252178''>But</span>
  <span m=''4252660''>this</span> <span m=''4252940''>thing--</span> <span m=''4255430''>and</span>
  <span m=''4255570''>I</span> <span m=''4255630''>got</span> <span m=''4255850''>it</span>
  <span m=''4255930''>wrong.</span> <span m=''4256200''>There''s</span> <span m=''4256350''>a</span>
  <span m=''4256410''>sign error.</span> <span m=''4257485''>I</span> <span m=''4257960''>got</span>
  <span m=''4258260''>two</span> <span m=''4258390''>sign</span> <span m=''4258660''>errors.</span>
  <span m=''4259160''>There''s</span> <span m=''4259340''>a</span> <span m=''4259390''>minus</span>
  <span m=''4259840''>here.</span> <span m=''4261020''>There''s</span> <span m=''4262440''>2k</span>
  <span m=''4262720''>minus</span> <span m=''4263020''>3.</span> <span m=''4263280''>And</span>
  <span m=''4263420''>so</span> <span m=''4263540''>this</span> <span m=''4263760''>is</span>
  <span m=''4264400''>going</span> <span m=''4264520''>to</span> <span m=''4264570''>be</span>
  <span m=''4265230''>two</span> <span m=''4265410''>negative</span> <span m=''4265770''>3s,</span>
  <span m=''4266340''>then</span> <span m=''4266590''>there''s</span> <span m=''4266820''>going</span>
  <span m=''4266920''>to</span> <span m=''4266960''>be</span> <span m=''4267060''>a</span>
  <span m=''4267100''>negative</span> <span m=''4267410''>negative</span> <span m=''4267770''>3.</span>
  <span m=''4268890''>2</span> <span m=''4269050''>wrongs</span> <span m=''4269290''>make</span>
  <span m=''4269470''>a</span> <span m=''4269550''>right.</span> <span m=''4270330''>It
  should</span> <span m=''4270510''>be</span> <span m=''4270670''>3</span> <span m=''4270930''>in</span>
  <span m=''4271020''>the</span> <span m=''4271130''>end.</span> <span m=''4274710''>OK.</span>
  </p><p><span m=''4275650''>Now,</span> <span m=''4276530''>this</span> <span m=''4276800''>thing.</span>
  <span m=''4278130''>What''s</span> <span m=''4278380''>that?</span> </p><p><span
  m=''4281928''>AUDIENCE: The union.</span> </p><p><span m=''4282890''>PROFESSOR:
  It''s the</span> <span m=''4283010''>size</span> <span m=''4283310''>of</span> <span
  m=''4283370''>the</span> <span m=''4283460''>union.</span> <span m=''4284650''>Here</span>
  <span m=''4284900''>it''s</span> <span m=''4285020''>exact,</span> <span m=''4285490''>because</span>
  <span m=''4285590''>we''re</span> <span m=''4285660''>counting</span> <span m=''4285930''>vertices</span>
  <span m=''4286390''>instead</span> <span m=''4286630''>of</span> <span m=''4286720''>edges.</span>
  <span m=''4289650''>It''s</span> <span m=''4290070''>this</span> <span m=''4290400''>plus</span>
  <span m=''4290660''>this</span> <span m=''4290920''>minus</span> <span m=''4291230''>the</span>
  <span m=''4291310''>intersection</span> <span m=''4291810''>from</span> <span m=''4291990''>double</span>
  <span m=''4292240''>counting.</span> <span m=''4293612''>Huh.</span> <span m=''4294090''>So</span>
  <span m=''4294250''>two</span> <span m=''4294570''>times</span> <span m=''4294920''>that</span>
  <span m=''4295170''>size</span> <span m=''4296240''>minus</span> <span m=''4296630''>3.</span>
  <span m=''4298082''>Hmm.</span> <span m=''4299930''>So</span> <span m=''4300040''>I</span>
  <span m=''4300070''>looked</span> <span m=''4300290''>at</span> <span m=''4300360''>the</span>
  <span m=''4300490''>edges</span> <span m=''4301400''>induced</span> <span m=''4301710''>by</span>
  <span m=''4301830''>the</span> <span m=''4301970''>union.</span> <span m=''4303060''>I</span>
  <span m=''4303200''>got</span> <span m=''4303370''>those</span> <span m=''4303560''>at</span>
  <span m=''4303640''>least</span> <span m=''4304000''>to</span> <span m=''4305050''>k</span>
  <span m=''4305320''>minus</span> <span m=''4305700''>3.</span> <span m=''4305940''>So</span>
  <span m=''4306180''>what--?</span> <span m=''4309450''>Right.</span> </p><p><span
  m=''4311150''>It doesn''t</span> <span m=''4311320''>sound</span> <span m=''4311500''>like</span>
  <span m=''4311630''>a</span> <span m=''4311680''>contradiction</span> <span m=''4312210''>yet.</span>
  <span m=''4313740''>We</span> <span m=''4313860''>want it</span> <span m=''4314020''>to</span>
  <span m=''4314130''>be</span> <span m=''4314220''>at</span> <span m=''4314280''>most</span>
  <span m=''4314590''>2k</span> <span m=''4314830''>minus</span> <span m=''4315140''>3</span>
  <span m=''4316018''>but</span> <span m=''4317930''>I</span> <span m=''4317980''>think</span>
  <span m=''4318170''>there''s a</span> <span m=''4318310''>property</span> <span
  m=''4318690''>I didn''t</span> <span m=''4319070''>prove</span> <span m=''4319510''>yet.</span>
  <span m=''4321670''>Great.</span> <span m=''4322632''>All right.</span> <span m=''4322990''>So</span>
  <span m=''4323335''>what.</span> <span m=''4324920''>Let''s</span> <span m=''4325090''>look</span>
  <span m=''4325230''>back</span> <span m=''4325450''>at</span> <span m=''4325530''>this</span>
  <span m=''4325700''>picture.</span> </p><p><span m=''4335480''>So</span> <span m=''4336130''>if</span>
  <span m=''4336360''>I</span> <span m=''4336420''>take</span> <span m=''4336660''>S1</span>
  <span m=''4336980''>union</span> <span m=''4337080''>S2,</span> <span m=''4338290''>S1</span>
  <span m=''4338840''>hits</span> <span m=''4339150''>these</span> <span m=''4339360''>two</span>
  <span m=''4339490''>guys--</span> <span m=''4341130''>2</span> <span m=''4341290''>and</span>
  <span m=''4341400''>3--</span> <span m=''4341806''>S2</span> <span m=''4342920''>hits</span>
  <span m=''4343930''>these</span> <span m=''4344160''>two</span> <span m=''4344290''>guys--</span>
  <span m=''4344590''>1</span> <span m=''4344770''>and</span> <span m=''4344890''>3.</span>
  <span m=''4345650''>In</span> <span m=''4345780''>their</span> <span m=''4345900''>union,</span>
  <span m=''4346210''>they''re</span> <span m=''4346330''>going</span> <span m=''4346430''>to</span>
  <span m=''4346470''>hit</span> <span m=''4346580''>all</span> <span m=''4346770''>three.</span>
  <span m=''4348290''>So</span> <span m=''4348670''>the</span> <span m=''4348840''>set</span>
  <span m=''4349100''>is</span> <span m=''4349260''>going</span> <span m=''4349380''>to</span>
  <span m=''4349460''>look</span> <span m=''4349660''>like</span> <span m=''4350560''>this.</span>
  <span m=''4351150''>It''s</span> <span m=''4351260''>going</span> <span m=''4351360''>to</span>
  <span m=''4351420''>contain</span> <span m=''4351810''>V1,</span> <span m=''4352510''>V2,</span>
  <span m=''4352680''>V3,</span> <span m=''4352950''>but</span> <span m=''4353210''>not</span>
  <span m=''4353450''>V.</span> <span m=''4356780''>Interesting.</span> </p><p><span
  m=''4359780''>I</span> <span m=''4359880''>know</span> <span m=''4360140''>that</span>
  <span m=''4360280''>if</span> <span m=''4360420''>I</span> <span m=''4360530''>put</span>
  <span m=''4360840''>V</span> <span m=''4361040''>in,</span> <span m=''4362220''>I</span>
  <span m=''4362310''>still</span> <span m=''4362580''>have</span> <span m=''4362760''>at</span>
  <span m=''4362840''>most</span> <span m=''4363100''>2k</span> <span m=''4363380''>minus</span>
  <span m=''4363700''>3</span> <span m=''4363900''>edges.</span> <span m=''4364720''>If</span>
  <span m=''4364910''>I</span> <span m=''4365000''>remove</span> <span m=''4365430''>V,</span>
  <span m=''4365730''>I remove</span> <span m=''4366330''>one</span> <span m=''4366710''>vertex</span>
  <span m=''4367380''>and</span> <span m=''4367660''>three</span> <span m=''4368040''>edges.</span>
  <span m=''4368690''>Three</span> <span m=''4369000''>edges</span> <span m=''4369320''>for</span>
  <span m=''4369400''>the</span> <span m=''4369520''>price</span> <span m=''4369770''>of</span>
  <span m=''4369870''>one.</span> <span m=''4370550''>Or</span> <span m=''4370680''>for</span>
  <span m=''4370840''>the</span> <span m=''4370950''>price</span> <span m=''4371200''>of</span>
  <span m=''4371320''>two,</span> <span m=''4371640''>I</span> <span m=''4371760''>guess.</span>
  <span m=''4372610''>Normally if</span> <span m=''4372970''>I</span> <span m=''4372990''>remove</span>
  <span m=''4373320''>a</span> <span m=''4373370''>vertex,</span> <span m=''4373780''>I</span>
  <span m=''4373830''>should</span> <span m=''4373990''>remove</span> <span m=''4374250''>only</span>
  <span m=''4374440''>two</span> <span m=''4374650''>edges.</span> <span m=''4375410''>If</span>
  <span m=''4375590''>I</span> <span m=''4375690''>cut</span> <span m=''4375960''>out</span>
  <span m=''4376200''>V,</span> <span m=''4376350''>I</span> <span m=''4376510''>remove</span>
  <span m=''4376840''>three</span> <span m=''4377120''>edges.</span> </p><p><span
  m=''4378180''>Therefore,</span> <span m=''4378840''>this</span> <span m=''4379130''>set</span>
  <span m=''4379830''>that</span> <span m=''4379950''>includes</span> <span m=''4380260''>V1,</span>
  <span m=''4380560''>V2,</span> <span m=''4380890''>V3</span> <span m=''4382170''>has</span>
  <span m=''4382510''>to</span> <span m=''4382580''>have</span> <span m=''4382790''>slack.</span>
  <span m=''4383570''>It</span> <span m=''4383730''>can''t</span> <span m=''4383990''>have</span>
  <span m=''4384320''>2k</span> <span m=''4384660''>minus</span> <span m=''4384960''>3</span>
  <span m=''4385150''>edges,</span> <span m=''4386310''>because--</span> <span m=''4386600''>this</span>
  <span m=''4387500''>should</span> <span m=''4388250''>be</span> <span m=''4388400''>OK.</span>
  <span m=''4388780''>The</span> <span m=''4389090''>bigger</span> <span m=''4389440''>set</span>
  <span m=''4389700''>should</span> <span m=''4389850''>be</span> <span m=''4390030''>at</span>
  <span m=''4390110''>most</span> <span m=''4390360''>2k</span> <span m=''4391260''>minus</span>
  <span m=''4391620''>3.</span> <span m=''4391850''>When</span> <span m=''4392000''>I</span>
  <span m=''4392060''>remove</span> <span m=''4392310''>a</span> <span m=''4392370''>vertex</span>
  <span m=''4392820''>and</span> <span m=''4393110''>remove</span> <span m=''4393470''>three</span>
  <span m=''4393720''>edges,</span> <span m=''4394580''>there''s</span> <span m=''4394760''>going</span>
  <span m=''4394900''>to</span> <span m=''4394990''>be</span> <span m=''4395430''>too</span>
  <span m=''4395620''>few</span> <span m=''4395940''>edges</span> <span m=''4396240''>over</span>
  <span m=''4396430''>here.</span> <span m=''4396660''>Two</span> <span m=''4396800''>few</span>
  <span m=''4396980''>edges</span> <span m=''4397120''>is</span> <span m=''4397260''>OK.</span>
  <span m=''4398390''>It</span> <span m=''4398490''>would</span> <span m=''4398620''>be</span>
  <span m=''4398810''>strictly</span> <span m=''4399260''>less</span> <span m=''4399550''>than</span>
  <span m=''4399670''>2k</span> <span m=''4399990''>minus</span> <span m=''4400330''>3,</span>
  <span m=''4400510''>and</span> <span m=''4400610''>here</span> <span m=''4400950''>I''m</span>
  <span m=''4401050''>claiming</span> <span m=''4401560''>it''s</span> <span m=''4401740''>at</span>
  <span m=''4401820''>least</span> <span m=''4402130''>2k</span> <span m=''4402400''>minus</span>
  <span m=''4402720''>3.</span> <span m=''4403340''>That''s</span> <span m=''4403570''>a</span>
  <span m=''4403630''>contradiction.</span> </p><p><span m=''4410670''>Now,</span>
  <span m=''4410840''>it</span> <span m=''4410950''>turns</span> <span m=''4411190''>out,</span>
  <span m=''4411410''>I''m</span> <span m=''4411490''>not</span> <span m=''4411690''>done,</span>
  <span m=''4411980''>because</span> <span m=''4412360''>I</span> <span m=''4412460''>was</span>
  <span m=''4412640''>in</span> <span m=''4412760''>two</span> <span m=''4412920''>levels</span>
  <span m=''4413310''>of</span> <span m=''4413410''>contradiction.</span> <span m=''4414820''>So</span>
  <span m=''4415010''>what</span> <span m=''4415550''>this</span> <span m=''4415700''>contradicts</span>
  <span m=''4416280''>is</span> <span m=''4416430''>this</span> <span m=''4416620''>assumption</span>
  <span m=''4417610''>that</span> <span m=''4417740''>there are</span> <span m=''4417900''>at</span>
  <span m=''4417950''>least</span> <span m=''4418200''>two</span> <span m=''4418340''>vertices</span>
  <span m=''4418790''>in</span> <span m=''4418870''>the</span> <span m=''4418980''>intersection.</span>
  <span m=''4419960''>Now,</span> <span m=''4420170''>I</span> <span m=''4420250''>know</span>
  <span m=''4420500''>there</span> <span m=''4420640''>can''t</span> <span m=''4420890''>be</span>
  <span m=''4421020''>two</span> <span m=''4421220''>vertices in the</span> <span
  m=''4421670''>intersection.</span> <span m=''4422015''>It''s</span> <span m=''4422360''>got</span>
  <span m=''4422520''>to</span> <span m=''4422580''>be</span> <span m=''4422720''>fewer.</span>
  <span m=''4423570''>Could</span> <span m=''4423740''>be</span> <span m=''4423850''>zero,</span>
  <span m=''4425780''>but</span> <span m=''4426160''>it</span> <span m=''4426210''>can''t</span>
  <span m=''4426420''>really</span> <span m=''4426580''>be</span> <span m=''4426700''>zero,</span>
  <span m=''4427210''>because</span> <span m=''4428940''>S2</span> <span m=''4429320''>and</span>
  <span m=''4429430''>S2</span> <span m=''4430030''>both</span> <span m=''4430380''>contain</span>
  <span m=''4430920''>V3.</span> <span m=''4432760''>So</span> <span m=''4432880''>it''s</span>
  <span m=''4432980''>got</span> <span m=''4433110''>to</span> <span m=''4433170''>be</span>
  <span m=''4433280''>exactly</span> <span m=''4433730''>one.</span> </p><p><span
  m=''4434760''>In</span> <span m=''4434910''>fact--</span> <span m=''4435910''>it''s
  the</span> <span m=''4436090''>crazy</span> <span m=''4436490''>proof.</span> <span
  m=''4438120''>When I</span> <span m=''4438250''>read</span> <span m=''4438460''>this,</span>
  <span m=''4438710''>I was like,</span> <span m=''4439040''>really?</span> <span
  m=''4440826''>It</span> <span m=''4441230''>works,</span> <span m=''4441650''>though.</span>
  <span m=''4442890''>You</span> <span m=''4443030''>can</span> <span m=''4443140''>do</span>
  <span m=''4443290''>all</span> <span m=''4443500''>of</span> <span m=''4443630''>them.</span>
  <span m=''4444240''>This is</span> <span m=''4444530''>going</span> <span m=''4444680''>to</span>
  <span m=''4444890''>equal</span> <span m=''4446080''>exactly</span> <span m=''4446620''>V1</span>
  <span m=''4447500''>and</span> <span m=''4447970''>S1</span> <span m=''4448450''>intersect</span>
  <span m=''4448890''>S3.</span> <span m=''4450150''>You</span> <span m=''4450230''>can</span>
  <span m=''4450330''>do</span> <span m=''4450400''>this</span> <span m=''4450530''>for</span>
  <span m=''4450670''>any</span> <span m=''4450830''>pair.</span> <span m=''4451180''>So</span>
  <span m=''4451630''>this</span> <span m=''4451790''>is</span> <span m=''4451890''>going</span>
  <span m=''4452010''>to</span> <span m=''4452080''>be</span> <span m=''4452220''>V2.</span>
  <span m=''4453930''>So</span> <span m=''4454060''>all</span> <span m=''4454140''>these</span>
  <span m=''4454250''>intersections</span> <span m=''4454780''>have</span> <span m=''4454910''>size</span>
  <span m=''4455150''>one,</span> <span m=''4456040''>and</span> <span m=''4456120''>we</span>
  <span m=''4456220''>know</span> <span m=''4456440''>what</span> <span m=''4456560''>it</span>
  <span m=''4456660''>is.</span> <span m=''4457780''>So</span> <span m=''4458130''>what?</span>
  </p><p><span m=''4466640''>Well,</span> <span m=''4466790''>now</span> <span m=''4473630''>if</span>
  <span m=''4473740''>I</span> <span m=''4473790''>take</span> <span m=''4474030''>the</span>
  <span m=''4474160''>union</span> <span m=''4474480''>of</span> <span m=''4474560''>all</span>
  <span m=''4474770''>of</span> <span m=''4474850''>them--</span> <span m=''4478230''>there''s</span>
  <span m=''4478670''>only</span> <span m=''4478890''>this</span> <span m=''4479020''>sharing.</span>
  <span m=''4479580''>There''s</span> <span m=''4479660''>only</span> <span m=''4479870''>three</span>
  <span m=''4480060''>shared</span> <span m=''4480410''>guys.</span> <span m=''4481440''>So</span>
  <span m=''4481600''>I</span> <span m=''4481670''>get</span> <span m=''4481890''>twice</span>
  <span m=''4484250''>the</span> <span m=''4484360''>size</span> <span m=''4484670''>of</span>
  <span m=''4484720''>all</span> <span m=''4484980''>them,</span> <span m=''4485190''>which</span>
  <span m=''4485360''>is</span> <span m=''4485530''>S1</span> <span m=''4486250''>plus</span>
  <span m=''4486640''>S2</span> <span m=''4487915''>plus</span> <span m=''4488290''>S3</span>
  <span m=''4492300''>minus</span> <span m=''4493050''>3.</span> <span m=''4496360''>Not</span>
  <span m=''4496540''>twice.</span> <span m=''4497450''>Sorry,</span> <span m=''4497950''>just</span>
  <span m=''4498160''>that.</span> <span m=''4500520''>Who</span> <span m=''4500620''>cares.</span>
  <span m=''4502950''>Take</span> <span m=''4503120''>all</span> <span m=''4503200''>the</span>
  <span m=''4503330''>edges</span> <span m=''4503650''>induced</span> <span m=''4503960''>by</span>
  <span m=''4504060''>those</span> <span m=''4504300''>guys.</span> <span m=''4509290''>At</span>
  <span m=''4509480''>the</span> <span m=''4509560''>very</span> <span m=''4509820''>least,</span>
  <span m=''4510710''>that''s</span> <span m=''4510920''>going</span> <span m=''4511040''>to</span>
  <span m=''4511120''>be--</span> <span m=''4515240''>good.</span> <span m=''4516390''>Now
  I see.</span> <span m=''4521140''>I</span> <span m=''4521220''>think that''d</span>
  <span m=''4521400''>actually</span> <span m=''4521830''>be</span> <span m=''4522180''>equal.</span>
  </p><p><span m=''4523150''>But</span> <span m=''4523300''>the</span> <span m=''4523380''>point</span>
  <span m=''4523550''>is</span> <span m=''4523700''>they</span> <span m=''4523830''>don''t</span>
  <span m=''4524080''>share</span> <span m=''4524410''>any</span> <span m=''4524570''>edges.</span>
  <span m=''4525310''>Because</span> <span m=''4525480''>they only</span> <span m=''4525660''>share</span>
  <span m=''4525860''>a</span> <span m=''4525920''>single</span> <span m=''4526170''>vertex,</span>
  <span m=''4526540''>there''s</span> <span m=''4526660''>no</span> <span m=''4526800''>room</span>
  <span m=''4526980''>to</span> <span m=''4527040''>share</span> <span m=''4527320''>any</span>
  <span m=''4527490''>edges.</span> <span m=''4528940''>So</span> <span m=''4529330''>these</span>
  <span m=''4529510''>guys</span> <span m=''4529670''>should</span> <span m=''4529850''>be</span>
  <span m=''4530310''>probably</span> <span m=''4530620''>equal</span> <span m=''4530870''>to</span>
  <span m=''4530970''>each</span> <span m=''4531130''>other.</span> <span m=''4532530''>Edges</span>
  <span m=''4532830''>induced</span> <span m=''4533140''>by</span> <span m=''4533270''>all
  of them</span> <span m=''4533690''>versus</span> <span m=''4534000''>edges</span>
  <span m=''4534330''>induced</span> <span m=''4534590''>by</span> <span m=''4534720''>each</span>
  <span m=''4534870''>of</span> <span m=''4534930''>them</span> <span m=''4535040''>individually.</span>
  <span m=''4536160''>Here</span> <span m=''4536320''>the</span> <span m=''4536410''>whole</span>
  <span m=''4536710''>is</span> <span m=''4536820''>equal</span> <span m=''4537060''>to</span>
  <span m=''4537150''>the</span> <span m=''4537230''>sum</span> <span m=''4537420''>of</span>
  <span m=''4537470''>the</span> <span m=''4537560''>parts.</span> </p><p><span m=''4540050''>And</span>
  <span m=''4540500''>this is</span> <span m=''4540730''>going to</span> <span m=''4540940''>be</span>
  <span m=''4541350''>2</span> <span m=''4541890''>times</span> <span m=''4543180''>number
  of</span> <span m=''4543510''>S1s</span> <span m=''4544440''>plus</span> <span m=''4544750''>number
  of</span> <span m=''4545230''>S2s</span> <span m=''4545940''>plus</span> <span m=''4546240''>number
  of</span> <span m=''4546710''>S3s</span> <span m=''4548400''>minus</span> <span
  m=''4548930''>9.</span> <span m=''4553760''>This</span> <span m=''4553920''>should</span>
  <span m=''4554120''>be</span> <span m=''4554540''>equal.</span> <span m=''4555130''>We</span>
  <span m=''4555270''>assumed</span> <span m=''4555550''>that</span> <span m=''4555690''>they</span>
  <span m=''4555870''>were</span> <span m=''4555990''>exactly</span> <span m=''4557840''>the</span>
  <span m=''4557900''>right</span> <span m=''4558110''>number</span> <span m=''4558350''>of</span>
  <span m=''4558430''>edges.</span> </p><p><span m=''4561530''>So</span> <span m=''4561780''>this</span>
  <span m=''4562060''>is</span> <span m=''4563240''>the</span> <span m=''4563350''>usual</span>
  <span m=''4563670''>problem.</span> <span m=''4567570''>This</span> <span m=''4567730''>can''t</span>
  <span m=''4567890''>happen</span> <span m=''4568320''>by</span> <span m=''4568440''>the</span>
  <span m=''4568510''>same</span> <span m=''4568970''>argument</span> <span m=''4569620''>we</span>
  <span m=''4569720''>did</span> <span m=''4569770''>here.</span> <span m=''4570940''>If</span>
  <span m=''4571050''>we</span> <span m=''4571120''>include</span> <span m=''4571480''>V1,</span>
  <span m=''4571840''>V2,</span> <span m=''4572200''>V3</span> <span m=''4572750''>and</span>
  <span m=''4572840''>we</span> <span m=''4572930''>don''t</span> <span m=''4573140''>include</span>
  <span m=''4573480''>V,</span> <span m=''4574170''>we''ve</span> <span m=''4574300''>got</span>
  <span m=''4574480''>to</span> <span m=''4574520''>have</span> <span m=''4574730''>too</span>
  <span m=''4574900''>few</span> <span m=''4575150''>edges.</span> <span m=''4575950''>And</span>
  <span m=''4576040''>here</span> <span m=''4576230''>we''re</span> <span m=''4576330''>saying</span>
  <span m=''4576640''>we</span> <span m=''4576720''>have</span> <span m=''4576870''>exactly</span>
  <span m=''4577250''>the</span> <span m=''4577360''>right</span> <span m=''4577530''>number.</span>
  <span m=''4578910''>Can''t</span> <span m=''4579090''>happen.</span> </p><p><span
  m=''4581705''>AUDIENCE:</span> <span m=''4582168''>[INAUDIBLE]</span> </p><p><span
  m=''4584950''>PROFESSOR: It''s</span> <span m=''4585100''>a</span> <span m=''4585350''>slight</span>
  <span m=''4585690''>discrepancy</span> <span m=''4586190''>between</span> <span
  m=''4586460''>the</span> <span m=''4586540''>9</span> <span m=''4586820''>and the</span>
  <span m=''4587000''>3.</span> <span m=''4588200''>Sorry,</span> <span m=''4588490''>question?</span>
  </p><p><span m=''4588880''>AUDIENCE:</span> <span m=''4589351''>[INAUDIBLE].</span>
  </p><p><span m=''4591710''>PROFESSOR: There''s</span> <span m=''4591900''>no</span>
  <span m=''4592040''>2</span> <span m=''4592240''>here.</span> <span m=''4592960''>Here</span>
  <span m=''4593180''>I''m</span> <span m=''4593260''>counting</span> <span m=''4593530''>vertices,</span>
  <span m=''4594460''>here I''m</span> <span m=''4594740''>counting</span> <span m=''4595030''>edges.</span>
  <span m=''4595900''>So</span> <span m=''4595950''>I</span> <span m=''4596020''>get</span>
  <span m=''4596170''>a</span> <span m=''4596270''>2</span> <span m=''4597220''>here.</span>
  <span m=''4599210''>This</span> <span m=''4599690''>thing</span> <span m=''4601590''>is</span>
  <span m=''4602180''>equal</span> <span m=''4602560''>to</span> <span m=''4604770''>this</span>
  <span m=''4605090''>thing</span> <span m=''4606370''>plus</span> <span m=''4606710''>3.</span>
  <span m=''4613400''>Ah,</span> <span m=''4613800''>algebra.</span> <span m=''4615000''>I</span>
  <span m=''4615090''>multiply</span> <span m=''4615450''>the</span> <span m=''4615560''>2</span>
  <span m=''4615720''>by</span> <span m=''4615900''>the</span> <span m=''4615990''>3.</span>
  <span m=''4616240''>I</span> <span m=''4616280''>get</span> <span m=''4616510''>6.</span>
  <span m=''4616810''>It</span> <span m=''4616880''>cancels</span> <span m=''4617430''>with</span>
  <span m=''4617660''>the</span> <span m=''4617730''>9.</span> <span m=''4618030''>I
  get</span> <span m=''4618330''>minus</span> <span m=''4618740''>3.</span> <span
  m=''4619510''>So</span> <span m=''4619650''>this</span> <span m=''4619870''>says</span>
  <span m=''4620010''>I</span> <span m=''4620050''>should</span> <span m=''4620200''>have</span>
  <span m=''4620320''>exactly</span> <span m=''4620730''>the</span> <span m=''4620800''>right</span>
  <span m=''4620930''>number--</span> <span m=''4621450''>twice</span> <span m=''4621780''>the</span>
  <span m=''4621850''>size</span> <span m=''4622130''>of</span> <span m=''4622190''>the</span>
  <span m=''4622270''>set</span> <span m=''4622580''>minus</span> <span m=''4622940''>3.</span>
  </p><p><span m=''4623760''>That</span> <span m=''4623950''>can''t</span> <span m=''4624110''>happen.</span>
  <span m=''4624410''>I</span> <span m=''4624470''>have</span> <span m=''4624650''>to</span>
  <span m=''4624730''>have</span> <span m=''4624910''>at</span> <span m=''4624980''>least</span>
  <span m=''4625260''>one</span> <span m=''4625480''>fewer.</span> <span m=''4625910''>That''s
  what</span> <span m=''4626300''>we</span> <span m=''4626430''>argued.</span> <span
  m=''4627780''>It''s</span> <span m=''4627920''>messy.</span> <span m=''4628300''>You</span>
  <span m=''4628390''>should</span> <span m=''4628560''>read</span> <span m=''4628690''>the</span>
  <span m=''4628760''>notes.</span> <span m=''4629460''>But</span> <span m=''4629590''>that</span>
  <span m=''4629850''>proves</span> <span m=''4631100''>Laman''s</span> <span m=''4631510''>theorem.</span>
  </p><p><span m=''4632900''>Now,</span> <span m=''4633160''>in</span> <span m=''4633280''>the</span>
  <span m=''4633360''>remaining</span> <span m=''4633930''>four</span> <span m=''4634160''>minutes,</span>
  <span m=''4635185''>I want</span> <span m=''4635610''>to</span> <span m=''4635680''>tell</span>
  <span m=''4635830''>you</span> <span m=''4635920''>two</span> <span m=''4636170''>more</span>
  <span m=''4636370''>cool</span> <span m=''4636590''>things.</span> <span m=''4638630''>Three</span>
  <span m=''4638820''>more</span> <span m=''4639000''>cool</span> <span m=''4639210''>things.</span>
  <span m=''4639580''>Great.</span> <span m=''4641960''>All</span> <span m=''4642030''>right.</span>
  </p><p><span m=''4642770''>First</span> <span m=''4643080''>thing</span> <span m=''4644020''>is</span>
  <span m=''4644150''>you</span> <span m=''4644250''>can</span> <span m=''4644370''>turn</span>
  <span m=''4644530''>this</span> <span m=''4644680''>into</span> <span m=''4644840''>an</span>
  <span m=''4644930''>algorithm.</span> <span m=''4647360''>How</span> <span m=''4647670''>do</span>
  <span m=''4647740''>you</span> <span m=''4647850''>turn it</span> <span m=''4648060''>into</span>
  <span m=''4648360''>an</span> <span m=''4648440''>algorithm?</span> <span m=''4649355''>It''s
  a</span> <span m=''4649640''>crazy</span> <span m=''4650020''>idea.</span> <span
  m=''4650880''>Roughly</span> <span m=''4651190''>speaking,</span> <span m=''4652620''>in</span>
  <span m=''4652750''>every</span> <span m=''4652960''>vertex,</span> <span m=''4653390''>you</span>
  <span m=''4653480''>imagine</span> <span m=''4653820''>there''s</span> <span m=''4653980''>two</span>
  <span m=''4654220''>little</span> <span m=''4654520''>pebbles</span> <span m=''4655440''>sitting</span>
  <span m=''4655810''>on</span> <span m=''4655910''>the</span> <span m=''4655980''>vertex.</span>
  <span m=''4657230''>And</span> <span m=''4657580''>then</span> <span m=''4658040''>there''s</span>
  <span m=''4658200''>a</span> <span m=''4658250''>bunch</span> <span m=''4658490''>of</span>
  <span m=''4658560''>edges</span> <span m=''4658930''>incident</span> <span m=''4659360''>to</span>
  <span m=''4659440''>that</span> <span m=''4659620''>vertex.</span> <span m=''4660670''>You</span>
  <span m=''4660830''>can</span> <span m=''4660950''>assign</span> <span m=''4661480''>each</span>
  <span m=''4661660''>of</span> <span m=''4661710''>these</span> <span m=''4661870''>pebbles</span>
  <span m=''4662360''>to</span> <span m=''4662570''>one</span> <span m=''4662820''>of</span>
  <span m=''4662910''>those</span> <span m=''4663130''>edges.</span> <span m=''4664760''>Something</span>
  <span m=''4665030''>like</span> <span m=''4665240''>that.</span> <span m=''4666830''>You</span>
  <span m=''4666950''>get</span> <span m=''4667080''>to</span> <span m=''4667150''>choose</span>
  <span m=''4667850''>each,</span> <span m=''4668300''>but</span> <span m=''4668440''>I</span>
  <span m=''4668490''>only</span> <span m=''4668700''>have</span> <span m=''4668830''>two</span>
  <span m=''4669020''>of</span> <span m=''4669090''>them.</span> <span m=''4670050''>I</span>
  <span m=''4670160''>do</span> <span m=''4670280''>that</span> <span m=''4670460''>for</span>
  <span m=''4670610''>every</span> <span m=''4671610''>vertex.</span> <span m=''4673910''>So</span>
  <span m=''4674920''>something</span> <span m=''4675180''>like</span> <span m=''4675360''>that.</span>
  </p><p><span m=''4677190''>If</span> <span m=''4677360''>I</span> <span m=''4677430''>can</span>
  <span m=''4677590''>cover</span> <span m=''4677940''>all</span> <span m=''4678060''>the</span>
  <span m=''4678190''>edges--</span> <span m=''4678810''>there''s a</span> <span m=''4679940''>slight</span>
  <span m=''4680240''>extra</span> <span m=''4680530''>condition--</span> <span m=''4680970''>but</span>
  <span m=''4681120''>if</span> <span m=''4681250''>I</span> <span m=''4681300''>can</span>
  <span m=''4681460''>cover</span> <span m=''4681770''>all</span> <span m=''4681860''>the</span>
  <span m=''4681970''>edge</span> <span m=''4682140''>in</span> <span m=''4682230''>this</span>
  <span m=''4682410''>way,</span> <span m=''4683470''>I</span> <span m=''4683560''>claim</span>
  <span m=''4683840''>I''m</span> <span m=''4683910''>rigid.</span> <span m=''4686740''>Well,</span>
  <span m=''4686970''>not</span> <span m=''4687020''>cover</span> <span m=''4687330''>all</span>
  <span m=''4687440''>the</span> <span m=''4687550''>edges.</span> <span m=''4688670''>If</span>
  <span m=''4689300''>I</span> <span m=''4689370''>can</span> <span m=''4689570''>get</span>
  <span m=''4689750''>all</span> <span m=''4689880''>the</span> <span m=''4689980''>pebbles</span>
  <span m=''4690420''>off</span> <span m=''4690730''>the</span> <span m=''4690810''>vertices</span>
  <span m=''4691290''>without</span> <span m=''4691730''>them</span> <span m=''4691860''>hitting</span>
  <span m=''4692170''>each</span> <span m=''4692370''>other,</span> <span m=''4693630''>then</span>
  <span m=''4694100''>I''m</span> <span m=''4694270''>rigid.</span> <span m=''4696030''>I</span>
  <span m=''4696130''>might</span> <span m=''4696310''>have</span> <span m=''4696460''>more</span>
  <span m=''4696790''>extra</span> <span m=''4697090''>edges</span> <span m=''4697390''>that</span>
  <span m=''4697500''>aren''t</span> <span m=''4697650''>covered.</span> <span m=''4698220''>Those</span>
  <span m=''4698510''>are</span> <span m=''4698600''>the</span> <span m=''4698720''>extra</span>
  <span m=''4699050''>edges.</span> <span m=''4699360''>You</span> <span m=''4699460''>should</span>
  <span m=''4699640''>throw</span> <span m=''4699840''>them</span> <span m=''4700000''>away.</span>
  <span m=''4700530''>That''s</span> <span m=''4700730''>over-bracing.</span> <span
  m=''4701510''>It''s</span> <span m=''4701980''>too</span> <span m=''4702230''>much</span>
  <span m=''4702460''>to</span> <span m=''4702550''>be</span> <span m=''4702680''>rigid.</span>
  </p><p><span m=''4703255''>But</span> <span m=''4703510''>if</span> <span m=''4703650''>I</span>
  <span m=''4703740''>can</span> <span m=''4703860''>get</span> <span m=''4703980''>all</span>
  <span m=''4704080''>these</span> <span m=''4704220''>pebbles</span> <span m=''4704550''>off</span>
  <span m=''4705150''>somehow,</span> <span m=''4706770''>then</span> <span m=''4707300''>I</span>
  <span m=''4707450''>have</span> <span m=''4707890''>roughly</span> <span m=''4708220''>the</span>
  <span m=''4708330''>right</span> <span m=''4708520''>number</span> <span m=''4708770''>of</span>
  <span m=''4708840''>edges</span> <span m=''4709140''>for</span> <span m=''4709370''>vertices.</span>
  <span m=''4710340''>And</span> <span m=''4710590''>while it''s</span> <span m=''4710830''>not</span>
  <span m=''4710980''>obvious,</span> <span m=''4711330''>it</span> <span m=''4711680''>turns</span>
  <span m=''4711970''>out</span> <span m=''4712110''>you</span> <span m=''4712240''>will</span>
  <span m=''4712340''>satisfy</span> <span m=''4712790''>Laman''s</span> <span m=''4713180''>condition
  in</span> <span m=''4713590''>that</span> <span m=''4713760''>situation.</span>
  <span m=''4715050''>And</span> <span m=''4715470''>so</span> <span m=''4715870''>it</span>
  <span m=''4716020''>turns</span> <span m=''4716250''>out</span> <span m=''4716360''>to
  just</span> <span m=''4716440''>be</span> <span m=''4716610''>a</span> <span m=''4716730''>graph</span>
  <span m=''4716970''>searching</span> <span m=''4717320''>problem.</span> </p><p><span
  m=''4717600''>You</span> <span m=''4717680''>have</span> <span m=''4717780''>to</span>
  <span m=''4717870''>push</span> <span m=''4718090''>the</span> <span m=''4718220''>pebbles</span>
  <span m=''4718610''>around</span> <span m=''4719370''>in</span> <span m=''4719540''>order</span>
  <span m=''4719730''>to</span> <span m=''4720240''>get</span> <span m=''4720410''>them</span>
  <span m=''4720540''>off</span> <span m=''4720710''>the</span> <span m=''4720790''>vertices.</span>
  <span m=''4722350''>You</span> <span m=''4722570''>don''t</span> <span m=''4722770''>have</span>
  <span m=''4722940''>a</span> <span m=''4722980''>lot</span> <span m=''4723150''>of</span>
  <span m=''4723190''>choices</span> <span m=''4723550''>where</span> <span m=''4723660''>the
  pebbles</span> <span m=''4724040''>can</span> <span m=''4724160''>go.</span> <span
  m=''4725400''>And it</span> <span m=''4725530''>turns</span> <span m=''4725770''>out</span>
  <span m=''4725900''>to</span> <span m=''4725990''>be</span> <span m=''4726410''>basically</span>
  <span m=''4729050''>m</span> <span m=''4729410''>calls</span> <span m=''4730010''>to</span>
  <span m=''4732820''>path</span> <span m=''4733080''>connectivity</span> <span m=''4734600''>operations.</span>
  </p><p><span m=''4736090''>So</span> <span m=''4736340''>I''ve</span> <span m=''4736530''>just</span>
  <span m=''4736720''>given</span> <span m=''4736980''>two</span> <span m=''4737140''>graphs.</span>
  <span m=''4737740''>So</span> <span m=''4738050''>I''m</span> <span m=''4738220''>given</span>
  <span m=''4738420''>a</span> <span m=''4738480''>connected</span> <span m=''4738820''>graph,</span>
  <span m=''4739990''>which</span> <span m=''4740140''>is</span> <span m=''4740370''>the</span>
  <span m=''4740480''>ways</span> <span m=''4740830''>that</span> <span m=''4740960''>I</span>
  <span m=''4741030''>can</span> <span m=''4741160''>move</span> <span m=''4741350''>the</span>
  <span m=''4741440''>pebbles</span> <span m=''4741780''>around.</span> <span m=''4742560''>I</span>
  <span m=''4742660''>just</span> <span m=''4742800''>want</span> <span m=''4742920''>to</span>
  <span m=''4742970''>know,</span> <span m=''4744240''>can</span> <span m=''4744390''>I</span>
  <span m=''4744460''>do</span> <span m=''4744590''>a</span> <span m=''4744670''>chain</span>
  <span m=''4744950''>reaction</span> <span m=''4745330''>of</span> <span m=''4745390''>pebble</span>
  <span m=''4745930''>twitches</span> <span m=''4746360''>till</span> <span m=''4746560''>I</span>
  <span m=''4746610''>get</span> <span m=''4746790''>this</span> <span m=''4746950''>one</span>
  <span m=''4747650''>moved</span> <span m=''4747950''>away?</span> <span m=''4750240''>So</span>
  <span m=''4750430''>it''s</span> <span m=''4750530''>just</span> <span m=''4750720''>a</span>
  <span m=''4750970''>depth</span> <span m=''4751190''>first</span> <span m=''4751390''>search.</span>
  <span m=''4751920''>Whatever.</span> </p><p><span m=''4752510''>So</span> <span
  m=''4752690''>this</span> <span m=''4752890''>cost</span> <span m=''4753190''>linear</span>
  <span m=''4753460''>time.</span> <span m=''4755860''>I</span> <span m=''4755920''>think</span>
  <span m=''4756140''>we could</span> <span m=''4756240''>probably</span> <span m=''4756490''>get</span>
  <span m=''4756600''>away with</span> <span m=''4756870''>n</span> <span m=''4757300''>operations</span>
  <span m=''4758320''>each</span> <span m=''4759250''>linear</span> <span m=''4759590''>time</span>
  <span m=''4760280''>in</span> <span m=''4760650''>number</span> <span m=''4761000''>of</span>
  <span m=''4761110''>edges.</span> <span m=''4763090''>So</span> <span m=''4763170''>the</span>
  <span m=''4763290''>total</span> <span m=''4763550''>amount</span> <span m=''4763770''>of</span>
  <span m=''4763840''>time</span> <span m=''4764190''>is</span> <span m=''4764410''>number
  of</span> <span m=''4764680''>vertices</span> <span m=''4765230''>times</span> <span
  m=''4765500''>number</span> <span m=''4765690''>of</span> <span m=''4765760''>edges.</span>
  <span m=''4766550''>M</span> <span m=''4766850''>is</span> <span m=''4767030''>the</span>
  <span m=''4767070''>number</span> <span m=''4767280''>of</span> <span m=''4767360''>edges.</span>
  <span m=''4769550''>Polynomial</span> <span m=''4770030''>time.</span> <span m=''4770750''>Life</span>
  <span m=''4770930''>is</span> <span m=''4771070''>good.</span> <span m=''4771740''>Open</span>
  <span m=''4772000''>problem.</span> <span m=''4772400''>Can</span> <span m=''4772560''>you</span>
  <span m=''4772640''>do</span> <span m=''4772770''>better?</span> <span m=''4773455''>But</span>
  <span m=''4773710''>that''s</span> <span m=''4773960''>been</span> <span m=''4774060''>around</span>
  <span m=''4774280''>for</span> <span m=''4774390''>a</span> <span m=''4774430''>long</span>
  <span m=''4774630''>time.</span> <span m=''4774960''>We''ve</span> <span m=''4775250''>tried</span>
  <span m=''4775500''>it</span> <span m=''4775570''>before.</span> <span m=''4776400''>Seems</span>
  <span m=''4776640''>quite</span> <span m=''4776840''>challenging.</span> </p><p><span
  m=''4778760''>Bigger</span> <span m=''4779040''>open</span> <span m=''4779240''>problem.</span>
  <span m=''4780190''>What</span> <span m=''4780300''>about</span> <span m=''4780550''>3D?</span>
  <span m=''4782240''>In 3D,</span> <span m=''4782940''>there</span> <span m=''4783080''>these</span>
  <span m=''4783260''>annoying</span> <span m=''4783550''>situations,</span> <span
  m=''4786000''>like</span> <span m=''4786800''>this</span> <span m=''4787020''>one.</span>
  <span m=''4792460''>Two</span> <span m=''4792630''>tetrahedra</span> <span m=''4793180''>glued</span>
  <span m=''4793410''>along</span> <span m=''4793670''>a</span> <span m=''4793710''>face.</span>
  <span m=''4802510''>Take</span> <span m=''4802780''>two--</span> <span m=''4803200''>we
  call this</span> <span m=''4803490''>a</span> <span m=''4803530''>banana--</span>
  <span m=''4804420''>take</span> <span m=''4804650''>two</span> <span m=''4804830''>bananas.</span>
  <span m=''4805920''>Joined</span> <span m=''4806210''>them</span> <span m=''4806370''>at</span>
  <span m=''4806510''>vertices,</span> <span m=''4807610''>the</span> <span m=''4807990''>opposing</span>
  <span m=''4808410''>vertices.</span> </p><p><span m=''4809300''>This</span> <span
  m=''4809560''>thing</span> <span m=''4810650''>is</span> <span m=''4810890''>flexible,</span>
  <span m=''4811600''>right?</span> <span m=''4811900''>You</span> <span m=''4812010''>just</span>
  <span m=''4812260''>rotate</span> <span m=''4813430''>through</span> <span m=''4813640''>here.</span>
  <span m=''4813900''>It''s</span> <span m=''4814160''>generically</span> <span m=''4814670''>flexible.</span>
  <span m=''4815110''>It doesn''t</span> <span m=''4815310''>matter</span> <span m=''4815540''>how
  I draw it.</span> <span m=''4816030''>You</span> <span m=''4816130''>can</span>
  <span m=''4816290''>rotate</span> <span m=''4816650''>through</span> <span m=''4816780''>that</span>
  <span m=''4816940''>axis.</span> <span m=''4817870''>But</span> <span m=''4818280''>it</span>
  <span m=''4818410''>has</span> <span m=''4818950''>2n</span> <span m=''4819260''>minus</span>
  <span m=''4819500''>6</span> <span m=''4819690''>edges,</span> <span m=''4820390''>and</span>
  <span m=''4820540''>every</span> <span m=''4820730''>subset</span> <span m=''4821080''>has</span>
  <span m=''4821250''>at</span> <span m=''4821310''>most</span> <span m=''4821510''>3n</span>
  <span m=''4821750''>minus</span> <span m=''4821980''>6</span> <span m=''4822180''>edges.</span>
  <span m=''4822980''>So Laman</span> <span m=''4823910''>doesn''t</span> <span m=''4824180''>hold.</span>
  </p><p><span m=''4825020''>Does</span> <span m=''4825270''>the</span> <span m=''4825380''>generalized</span>
  <span m=''4825820''>version</span> <span m=''4826130''>of</span> <span m=''4826210''>Henneberg''s</span>
  <span m=''4826710''>theorem</span> <span m=''4826950''>hold?</span> <span m=''4827740''>We</span>
  <span m=''4827880''>don''t</span> <span m=''4828020''>know.</span> <span m=''4829240''>I</span>
  <span m=''4829340''>think</span> <span m=''4829590''>maybe</span> <span m=''4829840''>yes.</span>
  <span m=''4831030''>If you</span> <span m=''4831130''>want</span> <span m=''4831280''>to</span>
  <span m=''4831340''>work</span> <span m=''4831550''>on</span> <span m=''4831680''>3D</span>
  <span m=''4831950''>rigidity--</span> <span m=''4832390''>which</span> <span m=''4832600''>is</span>
  <span m=''4832960''>a</span> <span m=''4832990''>little</span> <span m=''4833120''>scary,</span>
  <span m=''4833440''>because</span> <span m=''4833610''>a</span> <span m=''4833660''>lot</span>
  <span m=''4833800''>of</span> <span m=''4833870''>people</span> <span m=''4834130''>worked</span>
  <span m=''4834360''>on</span> <span m=''4834510''>it--</span> <span m=''4836080''>I</span>
  <span m=''4836220''>think</span> <span m=''4836410''>Henneberg</span> <span m=''4836880''>might</span>
  <span m=''4837130''>be</span> <span m=''4837350''>a</span> <span m=''4837430''>good</span>
  <span m=''4837590''>way</span> <span m=''4837720''>to</span> <span m=''4837810''>go.</span>
  <span m=''4838040''>It</span> <span m=''4838100''>might</span> <span m=''4838260''>not
  lead</span> <span m=''4838550''>to</span> <span m=''4838670''>an</span> <span m=''4838740''>algorithm,</span>
  <span m=''4839210''>but</span> <span m=''4839330''>at</span> <span m=''4839400''>least</span>
  <span m=''4839570''>you</span> <span m=''4839660''>might</span> <span m=''4839830''>get</span>
  <span m=''4839950''>a</span> <span m=''4840010''>nice</span> <span m=''4840240''>characterization.</span>
  <span m=''4844650''>It''d be</span> <span m=''4844770''>fun.</span> <span m=''4845080''>I</span>
  <span m=''4845180''>think</span> <span m=''4845510''>Henneberg</span> <span m=''4845850''>would</span>
  <span m=''4845940''>make</span> <span m=''4846150''>a</span> <span m=''4846200''>great</span>
  <span m=''4846440''>puzzle.</span> <span m=''4847510''>By</span> <span m=''4847630''>working</span>
  <span m=''4847950''>forward</span> <span m=''4848400''>not</span> <span m=''4848560''>backward,</span>
  <span m=''4848940''>it''s</span> <span m=''4849060''>quite</span> <span m=''4849290''>challenging.</span>
  </p><p><span m=''4851120''>Other</span> <span m=''4851570''>fun</span> <span m=''4851960''>things.</span>
  <span m=''4855160''>Let</span> <span m=''4855340''>me</span> <span m=''4855450''>tell</span>
  <span m=''4855680''>you</span> <span m=''4856180''>briefly</span> <span m=''4856710''>about</span>
  <span m=''4857130''>polyhedra.</span> <span m=''4858840''>Polyhedra</span> <span
  m=''4859240''>are</span> <span m=''4859390''>fun,</span> <span m=''4860330''>and</span>
  <span m=''4860660''>they</span> <span m=''4860750''>exist</span> <span m=''4861060''>in</span>
  <span m=''4861120''>three</span> <span m=''4861290''>dimensions.</span> <span m=''4863400''>Here''s</span>
  <span m=''4863650''>a</span> <span m=''4863720''>polyhedron.</span> <span m=''4864940''>It''s</span>
  <span m=''4865110''>a</span> <span m=''4865160''>convex</span> <span m=''4865640''>polygon--</span>
  <span m=''4866340''>it''s</span> <span m=''4866550''>Buckminster</span> <span m=''4867020''>Fuller</span>
  <span m=''4868970''>Geodesic</span> <span m=''4869430''>Dome</span> <span m=''4870770''>in</span>
  <span m=''4870910''>Montreal--</span> <span m=''4872720''>and</span> <span m=''4874490''>it''s</span>
  <span m=''4874690''>convex.</span> <span m=''4876940''>It''s</span> <span m=''4877210''>made</span>
  <span m=''4877420''>of</span> <span m=''4877490''>triangles.</span> </p><p><span
  m=''4878780''>Is</span> <span m=''4878930''>that</span> <span m=''4879150''>rigid?</span>
  <span m=''4879800''>It</span> <span m=''4879900''>looks</span> <span m=''4880020''>like</span>
  <span m=''4880230''>it.</span> <span m=''4881070''>Hasn''t</span> <span m=''4881370''>fallen</span>
  <span m=''4881620''>down</span> <span m=''4881860''>yet--</span> <span m=''4882090''>it''s</span>
  <span m=''4882240''>been</span> <span m=''4882390''>there</span> <span m=''4882530''>for</span>
  <span m=''4883410''>40</span> <span m=''4883550''>years</span> <span m=''4883820''>now.</span>
  <span m=''4886290''>Indeed,</span> <span m=''4886790''>you</span> <span m=''4886900''>can</span>
  <span m=''4887030''>prove</span> <span m=''4887260''>that</span> <span m=''4887460''>thing</span>
  <span m=''4887610''>is</span> <span m=''4887720''>rigid,</span> <span m=''4888290''>and</span>
  <span m=''4888470''>this</span> <span m=''4888640''>is</span> <span m=''4888810''>the</span>
  <span m=''4888970''>basis</span> <span m=''4889400''>for</span> <span m=''4890370''>geodesic</span>
  <span m=''4890830''>domes.</span> <span m=''4892210''>Turns</span> <span m=''4892540''>out,</span>
  <span m=''4892960''>if</span> <span m=''4893140''>you</span> <span m=''4893220''>have</span>
  <span m=''4893500''>a</span> <span m=''4893570''>convex</span> <span m=''4894120''>polyhedron--</span>
  <span m=''4895110''>so</span> <span m=''4895620''>3D</span> <span m=''4895970''>I</span>
  <span m=''4896030''>said</span> <span m=''4896260''>is</span> <span m=''4896360''>really</span>
  <span m=''4896560''>hard.</span> <span m=''4897030''>But</span> <span m=''4897170''>this</span>
  <span m=''4897370''>does</span> <span m=''4897470''>not</span> <span m=''4897690''>look</span>
  <span m=''4897820''>like</span> <span m=''4897980''>a</span> <span m=''4898010''>convex</span>
  <span m=''4898380''>polyhedron.</span> </p><p><span m=''4898940''>So</span> <span
  m=''4899110''>what</span> <span m=''4899230''>if</span> <span m=''4899320''>you</span>
  <span m=''4899410''>had</span> <span m=''4899570''>a</span> <span m=''4899620''>3D</span>
  <span m=''4900580''>linkage</span> <span m=''4901950''>that</span> <span m=''4902380''>is</span>
  <span m=''4902810''>the</span> <span m=''4902970''>surface</span> <span m=''4903560''>of</span>
  <span m=''4903800''>a</span> <span m=''4903870''>convex</span> <span m=''4904470''>polyhedron</span>
  <span m=''4905300''>and</span> <span m=''4905810''>every</span> <span m=''4906110''>face</span>
  <span m=''4906430''>is</span> <span m=''4906540''>a</span> <span m=''4906610''>triangle?</span>
  <span m=''4909860''>I</span> <span m=''4909900''>mean,</span> <span m=''4910080''>ignoring</span>
  <span m=''4910390''>the</span> <span m=''4910460''>floor</span> <span m=''4911130''>for</span>
  <span m=''4911320''>a</span> <span m=''4911340''>little</span> <span m=''4911520''>bit,</span>
  <span m=''4911820''>but</span> <span m=''4911830''>you</span> <span m=''4911930''>can</span>
  <span m=''4912040''>deal</span> <span m=''4912180''>with</span> <span m=''4912270''>that</span>
  <span m=''4912470''>too.</span> <span m=''4913040''>Every</span> <span m=''4913940''>face</span>
  <span m=''4914270''>here</span> <span m=''4914540''>is</span> <span m=''4914640''>a</span>
  <span m=''4914690''>triangle.</span> <span m=''4915530''>It</span> <span m=''4915810''>may
  be</span> <span m=''4916030''>easier to</span> <span m=''4916400''>see</span> <span
  m=''4917020''>in</span> <span m=''4917130''>this</span> <span m=''4917300''>diagram.</span>
  </p><p><span m=''4919460''>So</span> <span m=''4919580''>it''s</span> <span m=''4919700''>a</span>
  <span m=''4919750''>linkage.</span> <span m=''4920290''>It''s a</span> <span m=''4920555''>bunch
  of</span> <span m=''4920820''>triangles.</span> <span m=''4922660''>That thing</span>
  <span m=''4923130''>willl</span> <span m=''4923300''>be</span> <span m=''4923470''>generically</span>
  <span m=''4924130''>rigid.</span> <span m=''4925110''>And</span> <span m=''4925290''>even</span>
  <span m=''4925890''>rigid--</span> <span m=''4926360''>never mind</span> <span m=''4926770''>generically.</span>
  <span m=''4928100''>You</span> <span m=''4928240''>can</span> <span m=''4928350''>prove</span>
  <span m=''4928820''>this</span> <span m=''4928970''>thing</span> <span m=''4929110''>is</span>
  <span m=''4929220''>rigid,</span> <span m=''4931000''>and</span> <span m=''4932300''>it</span>
  <span m=''4932430''>was</span> <span m=''4932610''>proved,</span> <span m=''4933060''>roughly</span>
  <span m=''4933630''>speaking,</span> <span m=''4934190''>by</span> <span m=''4935030''>Alexandrov,</span>
  <span m=''4936890''>let''s</span> <span m=''4937090''>say,</span> <span m=''4937250''>or</span>
  <span m=''4937360''>Den--</span> <span m=''4938960''>the</span> <span m=''4939120''>early</span>
  <span m=''4939490''>to</span> <span m=''4939580''>mid</span> <span m=''4939760''>1900s.</span>
  <span m=''4944310''>That''s</span> <span m=''4944550''>cool.</span> </p><p><span
  m=''4946220''>And</span> <span m=''4948950''>that</span> <span m=''4949090''>doesn''t</span>
  <span m=''4949320''>mean</span> <span m=''4949460''>that</span> <span m=''4949570''>there</span>
  <span m=''4949720''>aren''t</span> <span m=''4949820''>other</span> <span m=''4950050''>configurations.</span>
  <span m=''4950770''>So</span> <span m=''4950890''>here''s</span> <span m=''4951130''>a</span>
  <span m=''4951200''>convex</span> <span m=''4951610''>polyhedron,</span> <span m=''4952700''>and</span>
  <span m=''4952900''>you</span> <span m=''4953000''>could</span> <span m=''4953120''>triangulate</span>
  <span m=''4953580''>the</span> <span m=''4953660''>sides</span> <span m=''4954040''>also.</span>
  <span m=''4955080''>And</span> <span m=''4955920''>there''s</span> <span m=''4956110''>a</span>
  <span m=''4956160''>non-convex</span> <span m=''4956890''>realization</span> <span
  m=''4957450''>of</span> <span m=''4957520''>that.</span> <span m=''4958880''>But</span>
  <span m=''4959040''>as</span> <span m=''4959140''>long</span> <span m=''4959350''>as</span>
  <span m=''4959420''>you</span> <span m=''4959630''>stay</span> <span m=''4959900''>convex,</span>
  <span m=''4960490''>and</span> <span m=''4960750''>if</span> <span m=''4960920''>you</span>
  <span m=''4961120''>move--</span> <span m=''4961980''>this</span> <span m=''4962160''>requires</span>
  <span m=''4962490''>a</span> <span m=''4962540''>big</span> <span m=''4962790''>jump.</span>
  <span m=''4963220''>And</span> <span m=''4963400''>you</span> <span m=''4963500''>can</span>
  <span m=''4963620''>show</span> <span m=''4963890''>that</span> <span m=''4964030''>if</span>
  <span m=''4964130''>you</span> <span m=''4964190''>have</span> <span m=''4964280''>a</span>
  <span m=''4964330''>convex</span> <span m=''4964710''>polyhedron,</span> <span m=''4965700''>in</span>
  <span m=''4965820''>order</span> <span m=''4965930''>for</span> <span m=''4966120''>it</span>
  <span m=''4966220''>to</span> <span m=''4966320''>flex</span> <span m=''4966510''>continuously,</span>
  <span m=''4967870''>well, it</span> <span m=''4968040''>can''t.</span> <span m=''4969400''>In</span>
  <span m=''4969590''>order</span> <span m=''4969740''>to</span> <span m=''4970010''>flex</span>
  <span m=''4970310''>at</span> <span m=''4970390''>all,</span> <span m=''4970960''>it</span>
  <span m=''4971220''>has</span> <span m=''4971500''>to</span> <span m=''4971600''>jump</span>
  <span m=''4971850''>into</span> <span m=''4972040''>a</span> <span m=''4972100''>non-convex</span>
  <span m=''4972690''>state.</span> </p><p><span m=''4973370''>But</span> <span m=''4973550''>there''s</span>
  <span m=''4973700''>a</span> <span m=''4973790''>fun</span> <span m=''4973850''>thing</span>
  <span m=''4974290''>that</span> <span m=''4974400''>happens</span> <span m=''4975360''>when</span>
  <span m=''4975530''>you</span> <span m=''4975840''>look</span> <span m=''4976040''>at</span>
  <span m=''4976140''>non-convex</span> <span m=''4976780''>polyhedra.</span> <span
  m=''4977310''>And</span> <span m=''4977440''>it''s</span> <span m=''4977570''>really</span>
  <span m=''4977760''>hard</span> <span m=''4978000''>to</span> <span m=''4978090''>see</span>
  <span m=''4978400''>this</span> <span m=''4978600''>polyhedron,</span> <span m=''4979090''>this</span>
  <span m=''4979230''>dent</span> <span m=''4979530''>on</span> <span m=''4979640''>the</span>
  <span m=''4979710''>backside,</span> <span m=''4981490''>but</span> <span m=''4981600''>you</span>
  <span m=''4981700''>can</span> <span m=''4981830''>cut</span> <span m=''4982020''>this</span>
  <span m=''4982190''>out and</span> <span m=''4982350''>make</span> <span m=''4982590''>one.</span>
  <span m=''4983590''>And</span> <span m=''4985280''>it''s</span> <span m=''4985530''>a</span>
  <span m=''4985590''>non-convex</span> <span m=''4986280''>polyhedron,</span> <span
  m=''4986840''>and</span> <span m=''4987050''>it</span> <span m=''4987260''>does</span>
  <span m=''4987570''>have</span> <span m=''4987850''>a</span> <span m=''4987900''>continuous</span>
  <span m=''4988450''>flex.</span> <span m=''4988820''>It''s</span> <span m=''4988950''>a</span>
  <span m=''4989000''>flexible</span> <span m=''4990840''>linkage.</span> <span m=''4991940''>It''s</span>
  <span m=''4992010''>triangulated,</span> <span m=''4993480''>but</span> <span m=''4993600''>it''s</span>
  <span m=''4993720''>not</span> <span m=''4993930''>convex,</span> <span m=''4994930''>and</span>
  <span m=''4995180''>so</span> <span m=''4995460''>Alexandrov''s</span> <span m=''4995970''>theorem</span>
  <span m=''4996210''>doesn''t</span> <span m=''4996440''>apply.</span> <span m=''4997290''>And</span>
  <span m=''4997930''>you</span> <span m=''5000180''>can</span> <span m=''5000450''>move</span>
  <span m=''5000730''>it</span> <span m=''5000900''>continuously.</span> <span m=''5001660''>It''s
  a</span> <span m=''5001830''>flexible</span> <span m=''5002310''>linkage.</span>
  </p><p><span m=''5003550''>Fun</span> <span m=''5003900''>fact--</span> <span m=''5004520''>when</span>
  <span m=''5004830''>it</span> <span m=''5004940''>moves,</span> <span m=''5005640''>the</span>
  <span m=''5005730''>volume</span> <span m=''5006220''>stays</span> <span m=''5006560''>constant.</span>
  <span m=''5008100''>It''s</span> <span m=''5008240''>called</span> <span m=''5008420''>the</span>
  <span m=''5008480''>bellow''s</span> <span m=''5008920''>theorem--</span> <span
  m=''5009016''>it</span> <span m=''5009113''>was</span> <span m=''5009210''>open</span>
  <span m=''5009470''>for</span> <span m=''5009630''>many</span> <span m=''5009880''>years--</span>
  <span m=''5011440''>by</span> <span m=''5011590''>Connelly</span> <span m=''5012050''>and</span>
  <span m=''5012190''>others.</span> <span m=''5013230''>And</span> <span m=''5013460''>so</span>
  <span m=''5014850''>in</span> <span m=''5014940''>fact,</span> <span m=''5015250''>you</span>
  <span m=''5015330''>take</span> <span m=''5015570''>any--</span> <span m=''5016430''>not</span>
  <span m=''5016590''>just</span> <span m=''5016760''>this</span> <span m=''5016960''>polyhedron--</span>
  <span m=''5017800''>you take</span> <span m=''5018020''>any</span> <span m=''5018260''>polyhedron</span>
  <span m=''5018530''>that</span> <span m=''5018800''>can</span> <span m=''5018870''>flex--</span>
  <span m=''5019915''>it</span> <span m=''5020190''>has</span> <span m=''5020390''>to</span>
  <span m=''5020450''>be</span> <span m=''5020550''>non-convex--</span> <span m=''5021580''>its</span>
  <span m=''5021740''>volume</span> <span m=''5022090''>will</span> <span m=''5022200''>stay</span>
  <span m=''5022370''>constant</span> <span m=''5023050''>throughout</span> <span
  m=''5023340''>the</span> <span m=''5023410''>whole</span> <span m=''5023570''>motion.</span>
  <span m=''5024790''>So</span> <span m=''5024860''>if</span> <span m=''5024920''>you''ve</span>
  <span m=''5025040''>ever</span> <span m=''5025240''>played</span> <span m=''5025450''>with</span>
  <span m=''5025530''>the</span> <span m=''5025610''>bellows,</span> <span m=''5027470''>you</span>
  <span m=''5028030''>may</span> <span m=''5028570''>think</span> <span m=''5028890''>this</span>
  <span m=''5029070''>is</span> <span m=''5029170''>not</span> <span m=''5029400''>true,</span>
  <span m=''5029780''>because</span> <span m=''5030130''>bellows</span> <span m=''5030810''>pump</span>
  <span m=''5031130''>air</span> <span m=''5031390''>in</span> <span m=''5031540''>and</span>
  <span m=''5031650''>out</span> <span m=''5032400''>somehow.</span> </p><p><span
  m=''5033750''>And</span> <span m=''5034090''>the</span> <span m=''5034170''>theorem</span>
  <span m=''5034470''>is</span> <span m=''5035130''>well,</span> <span m=''5035250''>you</span>
  <span m=''5035360''>can''t</span> <span m=''5035690''>build</span> <span m=''5035890''>a</span>
  <span m=''5035920''>bellows</span> <span m=''5036360''>out</span> <span m=''5036470''>of</span>
  <span m=''5036540''>linkages.</span> <span m=''5039400''>You could</span> <span
  m=''5039710''>maybe</span> <span m=''5039980''>build</span> <span m=''5040470''>bellows</span>
  <span m=''5040790''>out</span> <span m=''5040870''>a</span> <span m=''5040930''>paper,</span>
  <span m=''5042492''>or</span> <span m=''5042970''>a</span> <span m=''5043040''>flexible</span>
  <span m=''5043500''>material,</span> <span m=''5044630''>but</span> <span m=''5044680''>if</span>
  <span m=''5044810''>you</span> <span m=''5045010''>cannot</span> <span m=''5045840''>triangulate</span>
  <span m=''5046390''>that</span> <span m=''5046560''>surface,</span> <span m=''5046820''>you</span>
  <span m=''5046930''>cannot</span> <span m=''5047230''>make</span> <span m=''5047390''>it</span>
  <span m=''5047620''>a</span> <span m=''5047710''>metal</span> <span m=''5048180''>bellows.</span>
  <span m=''5049150''>Never</span> <span m=''5049350''>mind</span> <span m=''5049560''>if</span>
  <span m=''5049650''>they</span> <span m=''5049730''>exist</span> <span m=''5050050''>in</span>
  <span m=''5050090''>reality.</span> <span m=''5051270''>They are</span> <span m=''5051450''>theoretically</span>
  <span m=''5052090''>impossible</span> <span m=''5053130''>to</span> <span m=''5053280''>build.</span>
  <span m=''5055550''>I don''t</span> <span m=''5055650''>know-- are there</span>
  <span m=''5056020''>metal</span> <span m=''5056260''>bellows?</span> </p><p><span
  m=''5058260''>That''s</span> <span m=''5058460''>it.</span> <span m=''5058960''>And</span>
  <span m=''5059440''>next</span> <span m=''5059750''>time,</span> <span m=''5060060''>we</span>
  <span m=''5060200''>will</span> <span m=''5060380''>talk</span> <span m=''5060610''>about</span>
  <span m=''5060940''>more</span> <span m=''5061210''>rigidity</span> <span m=''5062300''>and</span>
  <span m=''5062680''>things</span> <span m=''5062890''>called</span> <span m=''5063090''>tensegrities,</span>
  <span m=''5063740''>which</span> <span m=''5064160''>even</span> <span m=''5064360''>more</span>
  <span m=''5064530''>exciting.</span> <span m=''5065010''>And</span> <span m=''5065280''>we''ll</span>
  <span m=''5065430''>see</span> <span m=''5065600''>how</span> <span m=''5065730''>this</span>
  <span m=''5065920''>ties</span> <span m=''5066170''>into</span> <span m=''5066350''>actually</span>
  <span m=''5066650''>getting</span> <span m=''5066870''>things</span> <span m=''5067050''>to</span>
  <span m=''5067140''>fold</span> <span m=''5067500''>from</span> <span m=''5067660''>point</span>
  <span m=''5067910''>A</span> <span m=''5067970''>to</span> <span m=''5068050''>point</span>
  <span m=''5068310''>B,</span> <span m=''5068880''>not</span> <span m=''5069090''>just</span>
  <span m=''5069370''>do</span> <span m=''5069470''>they</span> <span m=''5069620''>fold</span>
  <span m=''5069900''>at</span> <span m=''5069960''>all.</span> <span m=''5070910''>It''s</span>
  <span m=''5071070''>all</span> <span m=''5071240''>related.</span> </p>'
type: course
uid: 34f3ccafb01dcd7b542efb76fe5fe07b

---
None