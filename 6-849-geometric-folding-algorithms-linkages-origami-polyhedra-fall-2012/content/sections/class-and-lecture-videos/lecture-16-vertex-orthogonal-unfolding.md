---
about_this_resource_text: <p><strong>Description:</strong> This lecture continues
  with open problems involving general unfoldings of polyhedra and proof of vertex
  unfolding using construction of facet-paths. Approaches for unfolding orthogonal
  polyhedra, grid unfolding, and folding convex polyhedra are presented.</p> <p><strong>Speaker:</strong>
  Erik Demaine</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: 2ylK_QUpJcQ
  parent_uid: e705388dec0ac7567a512648dce64949
  title: Video-YouTube-Stream
  type: Video
  uid: 30b2fbaa8fec9f51576684c33dddffbe
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/2ylK_QUpJcQ/default.jpg
  parent_uid: e705388dec0ac7567a512648dce64949
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 9405b073561401c893d6c357e0178e41
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: e705388dec0ac7567a512648dce64949
  title: Video-iTunes U-MP4
  type: Video
  uid: 42231dc7bf3b1e3dd1010d9859b7d5a7
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_lec16_300k.mp4
  parent_uid: e705388dec0ac7567a512648dce64949
  title: Video-Internet Archive-MP4
  type: Video
  uid: c18761b7e2f5e8f1e07eb6716ea8af14
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 2ylK_QUpJcQ
  parent_uid: e705388dec0ac7567a512648dce64949
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: c41e9797233c7356faa3d431a6fe0761
- id: 2ylK_QUpJcQ.srt
  parent_uid: e705388dec0ac7567a512648dce64949
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-16-vertex-orthogonal-unfolding/2ylK_QUpJcQ.srt
  title: 3play caption file
  type: null
  uid: d8910a3b731b085ddaa4e4fcbc4393cc
- id: 2ylK_QUpJcQ.pdf
  parent_uid: e705388dec0ac7567a512648dce64949
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-16-vertex-orthogonal-unfolding/2ylK_QUpJcQ.pdf
  title: 3play pdf file
  type: null
  uid: 72513cd4d3cfc640063267fbe87f1ff7
- id: Caption-3Play YouTube id-SRT
  parent_uid: e705388dec0ac7567a512648dce64949
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 353d67af65b9eed47948e1be8ffb6770
- id: Transcript-3Play YouTube id-PDF
  parent_uid: e705388dec0ac7567a512648dce64949
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 00d5677f0d76666db9b1b6800cb98558
inline_embed_id: 14197617lecture16:vertex&orthogonalunfolding55175705
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: lecture-16-vertex-orthogonal-unfolding
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-16-vertex-orthogonal-unfolding
template_type: Tabbed
title: 'Lecture 16: Vertex & Orthogonal Unfolding'
transcript: '<p><span m=''51000''>PROFESSOR: All</span> <span m=''51090''>right.</span>
  <span m=''51440''>Let''s</span> <span m=''51720''>get</span> <span m=''51830''>started.</span>
  <span m=''53170''>So</span> <span m=''53670''>we</span> <span m=''53880''>are</span>
  <span m=''54000''>continuing</span> <span m=''54460''>the</span> <span m=''54570''>theme</span>
  <span m=''54900''>of</span> <span m=''55150''>unfolding</span> <span m=''55850''>polyhedra,</span>
  <span m=''57130''>and</span> <span m=''57520''>the</span> <span m=''58350''>general</span>
  <span m=''58860''>picture</span> <span m=''59320''>we</span> <span m=''59400''>are</span>
  <span m=''59460''>thinking</span> <span m=''59740''>about</span> <span m=''60650''>in</span>
  <span m=''60690''>terms</span> <span m=''60890''>of</span> <span m=''61050''>edge</span>
  <span m=''61290''>unfolding</span> <span m=''62080''>versus</span> <span m=''62420''>general</span>
  <span m=''62790''>unfolding</span> <span m=''63420''>which</span> <span m=''63670''>are</span>
  <span m=''64080''>these</span> <span m=''64290''>two</span> <span m=''64430''>pictures.</span>
  <span m=''65440''>Top</span> <span m=''65720''>is</span> <span m=''65850''>an</span>
  <span m=''65940''>edge</span> <span m=''66110''>unfolding</span> <span m=''66540''>of</span>
  <span m=''66610''>the</span> <span m=''66710''>cube.</span> <span m=''67030''>Bottom</span>
  <span m=''67400''>is a</span> <span m=''67600''>general</span> <span m=''67880''>unfolding</span>
  <span m=''68260''>of</span> <span m=''68330''>the</span> <span m=''68440''>cube.</span>
  </p><p><span m=''70680''>If</span> <span m=''70940''>you</span> <span m=''71050''>have</span>
  <span m=''71180''>a</span> <span m=''71240''>complex</span> <span m=''71660''>polyhedron,</span>
  <span m=''72640''>we</span> <span m=''73150''>found</span> <span m=''73920''>general</span>
  <span m=''74240''>unfoldings.</span> <span m=''74930''>There are</span> <span m=''75160''>like</span>
  <span m=''75370''>four</span> <span m=''75640''>of</span> <span m=''75700''>them.</span>
  <span m=''76290''>They</span> <span m=''76390''>work.</span> <span m=''76740''>We</span>
  <span m=''76920''>proved</span> <span m=''77270''>one</span> <span m=''77430''>of</span>
  <span m=''77520''>them.</span> </p><p><span m=''78970''>If</span> <span m=''79080''>you</span>
  <span m=''79170''>want an</span> <span m=''79380''>edge</span> <span m=''79560''>unfolding,</span>
  <span m=''80020''>that''s</span> <span m=''80340''>the</span> <span m=''80720''>centuries-old</span>
  <span m=''81290''>open</span> <span m=''81740''>problem.</span> <span m=''82760''>For</span>
  <span m=''82930''>non-convex</span> <span m=''83510''>polyhedra,</span> <span m=''84110''>we</span>
  <span m=''84220''>know</span> <span m=''84370''>this</span> <span m=''84530''>is</span>
  <span m=''84640''>too</span> <span m=''84770''>much</span> <span m=''84980''>to</span>
  <span m=''85060''>hope</span> <span m=''85250''>for.</span> <span m=''85560''>Even</span>
  <span m=''86090''>if</span> <span m=''86210''>it''s</span> <span m=''86340''>topologically</span>
  <span m=''86970''>convex,</span> <span m=''88010''>there''s</span> <span m=''88150''>not</span>
  <span m=''88340''>always</span> <span m=''88550''>an</span> <span m=''88630''>edge</span>
  <span m=''88900''>unfolding.</span> <span m=''89420''>That</span> <span m=''89890''>was</span>
  <span m=''90090''>the</span> <span m=''90770''>tetrahedral</span> <span m=''91770''>Witch''s</span>
  <span m=''92050''>Hat.</span> <span m=''93410''>But</span> <span m=''93750''>for</span>
  <span m=''93860''>general</span> <span m=''94190''>unfolding,</span> <span m=''94660''>we</span>
  <span m=''94770''>don''t</span> <span m=''94920''>know.</span> </p><p><span m=''97470''>So</span>
  <span m=''97900''>today''s</span> <span m=''98500''>lecture</span> <span m=''98910''>is</span>
  <span m=''99090''>actually</span> <span m=''99350''>mostly</span> <span m=''99760''>about</span>
  <span m=''99990''>these</span> <span m=''100160''>two</span> <span m=''100320''>open</span>
  <span m=''100560''>problems</span> <span m=''103490''>and</span> <span m=''103790''>different</span>
  <span m=''104740''>variations</span> <span m=''105610''>of</span> <span m=''105770''>it</span>
  <span m=''105910''>that</span> <span m=''106040''>we</span> <span m=''106210''>know</span>
  <span m=''106410''>how</span> <span m=''106550''>to</span> <span m=''106640''>solve,</span>
  <span m=''108020''>special</span> <span m=''108400''>cases,</span> <span m=''109070''>and</span>
  <span m=''110200''>changes</span> <span m=''110600''>in</span> <span m=''110680''>the</span>
  <span m=''110750''>model.</span> <span m=''114280''>At</span> <span m=''114460''>the</span>
  <span m=''114600''>end,</span> <span m=''114800''>there''ll also</span> <span m=''115110''>be</span>
  <span m=''115240''>some</span> <span m=''115750''>stuff</span> <span m=''116280''>about</span>
  <span m=''116470''>the</span> <span m=''116550''>reverse</span> <span m=''116830''>direction</span>
  <span m=''117230''>folding,</span> <span m=''118270''>but</span> <span m=''118910''>mostly,
  it</span> <span m=''119310''>will</span> <span m=''119450''>be</span> <span m=''119600''>about</span>
  <span m=''120570''>unfolding.</span> <span m=''122190''>So</span> <span m=''122400''>there''s</span>
  <span m=''122570''>a</span> <span m=''122640''>third</span> <span m=''122940''>kind</span>
  <span m=''123160''>of</span> <span m=''123250''>unfolding</span> <span m=''125300''>which</span>
  <span m=''125600''>we</span> <span m=''125760''>call</span> <span m=''127100''>vertex</span>
  <span m=''127590''>unfolding,</span> <span m=''129669''>and</span> <span m=''130070''>it''s</span>
  <span m=''130330''>kind</span> <span m=''130710''>of</span> <span m=''130800''>like</span>
  <span m=''131670''>a</span> <span m=''131690''>hinged</span> <span m=''132130''>dissection.</span>
  <span m=''133900''>So</span> <span m=''134190''>instead</span> <span m=''134630''>of</span>
  <span m=''134840''>normally</span> <span m=''135270''>in</span> <span m=''135360''>unfolding,</span>
  <span m=''136120''>something</span> <span m=''136430''>like</span> <span m=''137045''>a</span>
  <span m=''137440''>cross,</span> <span m=''139900''>it''s</span> <span m=''140480''>a</span>
  <span m=''140520''>nice,</span> <span m=''140970''>connected</span> <span m=''141560''>polygon.</span>
  <span m=''143450''>The</span> <span m=''143550''>faces</span> <span m=''144310''>are</span>
  <span m=''144460''>joined along</span> <span m=''144940''>edges.</span> </p><p><span
  m=''146430''>But</span> <span m=''146540''>what</span> <span m=''146710''>if</span>
  <span m=''146870''>I</span> <span m=''146990''>allowed</span> <span m=''148960''>disconnecting</span>
  <span m=''149870''>along</span> <span m=''150220''>edges,</span> <span m=''150770''>but</span>
  <span m=''150980''>I</span> <span m=''151840''>just</span> <span m=''152100''>wanted</span>
  <span m=''152370''>things</span> <span m=''152590''>to</span> <span m=''152690''>stay</span>
  <span m=''152880''>connected</span> <span m=''153330''>along</span> <span m=''154230''>vertices,</span>
  <span m=''157240''>like</span> <span m=''157320''>at</span> <span m=''157510''>a</span>
  <span m=''157560''>hinge.</span> <span m=''158610''>So it</span> <span m=''158770''>still</span>
  <span m=''159000''>should</span> <span m=''159170''>be</span> <span m=''159310''>one</span>
  <span m=''159670''>piece</span> <span m=''160850''>in</span> <span m=''160990''>the</span>
  <span m=''161070''>sense</span> <span m=''161390''>that</span> <span m=''161810''>this</span>
  <span m=''161990''>is</span> <span m=''162060''>still</span> <span m=''162300''>connected,</span>
  <span m=''164200''>and</span> <span m=''165030''>in</span> <span m=''165200''>this</span>
  <span m=''165410''>case,</span> <span m=''165840''>I</span> <span m=''165940''>still</span>
  <span m=''166210''>want</span> <span m=''166410''>an</span> <span m=''166500''>edge</span>
  <span m=''166740''>unfolding.</span> <span m=''168710''>You''re</span> <span m=''169010''>only</span>
  <span m=''169280''>allowed</span> <span m=''169540''>to</span> <span m=''169610''>cut</span>
  <span m=''169820''>on</span> <span m=''169970''>edges.</span> <span m=''173480''>And</span>
  <span m=''173600''>in</span> <span m=''173670''>fact,</span> <span m=''173920''>we</span>
  <span m=''174040''>will</span> <span m=''174200''>cut</span> <span m=''174460''>on</span>
  <span m=''174680''>all</span> <span m=''175010''>the</span> <span m=''175150''>edges</span>
  <span m=''175500''>because</span> <span m=''175660''>that''ll</span> <span m=''175900''>be</span>
  <span m=''176020''>the</span> <span m=''176120''>most</span> <span m=''176370''>flexible.</span>
  <span m=''177190''>Every</span> <span m=''177510''>edge</span> <span m=''177710''>gets</span>
  <span m=''177910''>cut,</span> <span m=''178430''>but</span> <span m=''179240''>you''re</span>
  <span m=''179390''>going</span> <span m=''179510''>to</span> <span m=''179580''>leave</span>
  <span m=''179790''>intact</span> <span m=''180190''>certain</span> <span m=''180480''>vertices</span>
  <span m=''187540''>to</span> <span m=''187660''>make</span> <span m=''187950''>one,</span>
  <span m=''189450''>quote,</span> <span m=''189830''>"piece"</span> <span m=''190875''>at</span>
  <span m=''194490''>vertices.</span> <span m=''198635''>So</span> <span m=''199090''>we</span>
  <span m=''199220''>still</span> <span m=''199440''>want</span> <span m=''199670''>one</span>
  <span m=''199960''>piece.</span> </p><p><span m=''203310''>So</span> <span m=''203370''>this</span>
  <span m=''203580''>is</span> <span m=''203680''>vertex</span> <span m=''204100''>unfolding,</span>
  <span m=''205070''>and</span> <span m=''205600''>it''s</span> <span m=''206630''>always</span>
  <span m=''206880''>possible.</span> <span m=''208950''>We''ve even</span> <span
  m=''209420''>implemented</span> <span m=''209890''>this</span> <span m=''210040''>algorithm</span>
  <span m=''210450''>here.</span> <span m=''210660''>A</span> <span m=''210700''>bunch</span>
  <span m=''210970''>of</span> <span m=''211590''>random</span> <span m=''211890''>points</span>
  <span m=''212130''>on</span> <span m=''212230''>a</span> <span m=''212290''>sphere.</span>
  <span m=''212560''>Take</span> <span m=''212760''>the</span> <span m=''212850''>convex</span>
  <span m=''213270''>hull,</span> <span m=''213580''>and</span> <span m=''213720''>then,</span>
  <span m=''213900''>take</span> <span m=''214130''>a</span> <span m=''215610''>vertex</span>
  <span m=''216050''>unfolding.</span> <span m=''217030''>So</span> <span m=''217240''>you</span>
  <span m=''217330''>get</span> <span m=''217470''>this</span> <span m=''217620''>nice</span>
  <span m=''218070''>chain</span> <span m=''218520''>of</span> <span m=''218870''>triangles,</span>
  <span m=''220330''>don''t</span> <span m=''220510''>intersect</span> <span m=''220950''>each</span>
  <span m=''221090''>other,</span> <span m=''221600''>and</span> <span m=''221740''>this</span>
  <span m=''221900''>will</span> <span m=''222010''>fold</span> <span m=''222290''>up</span>
  <span m=''222450''>into</span> <span m=''222680''>that</span> <span m=''223360''>3D</span>
  <span m=''223790''>polyhedron</span> <span m=''224370''>on</span> <span m=''224520''>the</span>
  <span m=''224600''>left.</span> <span m=''225000''>Here''s</span> <span m=''225190''>some</span>
  <span m=''225940''>bigger</span> <span m=''226190''>examples,</span> <span m=''226730''>hundreds</span>
  <span m=''227120''>of</span> <span m=''227190''>vertices.</span> <span m=''227810''>Amazing.</span>
  </p><p><span m=''233010''>All</span> <span m=''233080''>right.</span> <span m=''233380''>So</span>
  <span m=''233870''>how</span> <span m=''234070''>do</span> <span m=''234150''>we</span>
  <span m=''234260''>do</span> <span m=''234400''>this?</span> <span m=''237215''>All
  right.</span> <span m=''237678''>Let me</span> <span m=''239070''>state a</span>
  <span m=''239430''>theorem.</span> <span m=''241330''>Every</span> <span m=''244250''>connected</span>
  <span m=''247670''>triangulated</span> <span m=''249770''>manifold--</span> <span
  m=''254050''>this is</span> <span m=''254310''>a</span> <span m=''254360''>very</span>
  <span m=''254590''>general</span> <span m=''254920''>result.</span> <span m=''255300''>It</span>
  <span m=''255370''>actually</span> <span m=''255620''>holds</span> <span m=''255860''>in</span>
  <span m=''255960''>any</span> <span m=''256200''>dimension.</span> <span m=''257620''>We''re</span>
  <span m=''257769''>going</span> <span m=''257850''>to</span> <span m=''257920''>think</span>
  <span m=''258089''>about</span> <span m=''258329''>two</span> <span m=''258440''>dimensional</span>
  <span m=''258800''>sources</span> <span m=''259329''>in</span> <span m=''259470''>3D,</span>
  <span m=''259910''>but</span> <span m=''260089''>it</span> <span m=''260190''>could</span>
  <span m=''260339''>be</span> <span m=''260560''>D</span> <span m=''260670''>dimensional</span>
  <span m=''261070''>surfaces</span> <span m=''261360''>in</span> <span m=''261500''>D</span>
  <span m=''261690''>plus</span> <span m=''261899''>1</span> <span m=''262060''>dimensions.</span>
  <span m=''263963''>--has</span> <span m=''265920''>a</span> <span m=''265960''>vertex</span>
  <span m=''266450''>unfolding.</span> </p><p><span m=''274640''>So</span> <span m=''274840''>this</span>
  <span m=''275030''>works</span> <span m=''275250''>both</span> <span m=''275440''>for</span>
  <span m=''275560''>convex</span> <span m=''276020''>and</span> <span m=''276160''>for</span>
  <span m=''276260''>non-convex.</span> <span m=''278420''>The</span> <span m=''278580''>only</span>
  <span m=''278830''>catch</span> <span m=''279200''>is</span> <span m=''279340''>that</span>
  <span m=''279500''>every</span> <span m=''279740''>face</span> <span m=''280030''>has</span>
  <span m=''280210''>to</span> <span m=''280310''>be</span> <span m=''280420''>a</span>
  <span m=''280480''>triangle.</span> <span m=''282740''>It''s an</span> <span m=''283040''>open</span>
  <span m=''283320''>problem</span> <span m=''284010''>for</span> <span m=''284240''>something</span>
  <span m=''284660''>like</span> <span m=''285080''>a</span> <span m=''285200''>cube</span>
  <span m=''285630''>where</span> <span m=''285770''>you</span> <span m=''285870''>actually</span>
  <span m=''286160''>have</span> <span m=''288010''>quadrilateral</span> <span m=''288630''>faces.</span>
  </p><p><span m=''295260''>So</span> <span m=''295550''>the</span> <span m=''295660''>way</span>
  <span m=''295770''>we</span> <span m=''295930''>prove</span> <span m=''296190''>this</span>
  <span m=''298080''>is</span> <span m=''298590''>to</span> <span m=''298920''>construct</span>
  <span m=''300720''>what</span> <span m=''301060''>we</span> <span m=''301210''>call</span>
  <span m=''302496''>a</span> <span m=''302850''>facet-path.</span> <span m=''308640''>This</span>
  <span m=''308870''>is</span> <span m=''308990''>a</span> <span m=''309070''>path</span>
  <span m=''309550''>that</span> <span m=''310610''>alternates</span> <span m=''312780''>between</span>
  <span m=''313340''>visiting</span> <span m=''314330''>faces,</span> <span m=''316680''>triangles,</span>
  <span m=''322120''>and</span> <span m=''322570''>vertices.</span> <span m=''328490''>So</span>
  <span m=''328690''>the</span> <span m=''328810''>idea</span> <span m=''329040''>is</span>
  <span m=''329830''>you</span> <span m=''330030''>have</span> <span m=''330290''>some--</span>
  <span m=''331820''>say</span> <span m=''331960''>we''re</span> <span m=''332080''>doing</span>
  <span m=''332400''>a</span> <span m=''333280''>tetrahedron</span> <span m=''333810''>or</span>
  <span m=''333900''>something.</span> </p><p><span m=''334690''>You</span> <span
  m=''334770''>start at</span> <span m=''335170''>a</span> <span m=''335210''>facet.</span>
  <span m=''336090''>Then,</span> <span m=''336230''>you</span> <span m=''336340''>go</span>
  <span m=''336520''>to</span> <span m=''336640''>one</span> <span m=''336780''>of</span>
  <span m=''336880''>its</span> <span m=''337000''>vertices.</span> <span m=''337520''>Then,</span>
  <span m=''337670''>you</span> <span m=''337810''>go</span> <span m=''338070''>to</span>
  <span m=''338310''>one</span> <span m=''338460''>of</span> <span m=''338520''>the</span>
  <span m=''338600''>facets</span> <span m=''339720''>that</span> <span m=''339960''>shares</span>
  <span m=''340260''>that</span> <span m=''340450''>vertex.</span> <span m=''341440''>Then,</span>
  <span m=''341650''>you</span> <span m=''341750''>go</span> <span m=''341900''>to</span>
  <span m=''342000''>one</span> <span m=''342140''>of</span> <span m=''342200''>the</span>
  <span m=''342270''>vertices.</span> </p><p><span m=''342840''>Then,</span> <span
  m=''343010''>you</span> <span m=''343130''>go</span> <span m=''343280''>to a</span>
  <span m=''343430''>facet.</span> <span m=''344290''>Then,</span> <span m=''344420''>you</span>
  <span m=''344510''>go</span> <span m=''344620''>to a</span> <span m=''344750''>vertex.</span>
  <span m=''345300''>Then,</span> <span m=''345440''>you</span> <span m=''345530''>go</span>
  <span m=''345650''>to</span> <span m=''345710''>a</span> <span m=''345780''>facet.</span>
  <span m=''346490''>This</span> <span m=''346700''>is</span> <span m=''346800''>a</span>
  <span m=''346860''>facet-path.</span> <span m=''348380''>It</span> <span m=''348540''>should</span>
  <span m=''348800''>visit</span> <span m=''350130''>every</span> <span m=''352280''>facet,</span>
  <span m=''352870''>every</span> <span m=''353340''>triangle,</span> <span m=''354780''>exactly</span>
  <span m=''355320''>once.</span> </p><p><span m=''359730''>Vertices</span> <span
  m=''360300''>you</span> <span m=''360440''>can</span> <span m=''360610''>visit</span>
  <span m=''360920''>multiple</span> <span m=''361410''>times,</span> <span m=''361900''>although</span>
  <span m=''362070''>I</span> <span m=''362150''>think</span> <span m=''362340''>it''s</span>
  <span m=''362480''>a</span> <span m=''362740''>bad</span> <span m=''363070''>idea</span>
  <span m=''363390''>to</span> <span m=''363480''>visit</span> <span m=''363770''>the</span>
  <span m=''363850''>same</span> <span m=''364110''>vertex</span> <span m=''364480''>twice</span>
  <span m=''364790''>in</span> <span m=''364870''>a</span> <span m=''364960''>row.</span>
  <span m=''366460''>Other</span> <span m=''366590''>than</span> <span m=''366720''>that,</span>
  <span m=''367090''>you</span> <span m=''367250''>can</span> <span m=''367700''>visit</span>
  <span m=''367940''>a</span> <span m=''367990''>vertex</span> <span m=''368340''>more</span>
  <span m=''368470''>than</span> <span m=''368580''>once.</span> <span m=''368810''>Maybe</span>
  <span m=''369090''>I</span> <span m=''369180''>would</span> <span m=''369350''>visit</span>
  <span m=''369650''>it</span> <span m=''369760''>again</span> <span m=''370090''>coming</span>
  <span m=''370390''>up</span> <span m=''370530''>here.</span> <span m=''371150''>If</span>
  <span m=''371420''>there was</span> <span m=''371610''>another</span> <span m=''371860''>triangle</span>
  <span m=''372210''>like</span> <span m=''372380''>this,</span> <span m=''372630''>I</span>
  <span m=''372740''>could</span> <span m=''372970''>go</span> <span m=''373230''>up</span>
  <span m=''373460''>to</span> <span m=''373560''>this</span> <span m=''373740''>vertex</span>
  <span m=''374130''>again</span> <span m=''374940''>and</span> <span m=''375250''>over</span>
  <span m=''375420''>to</span> <span m=''375520''>the</span> <span m=''375610''>triangle.</span>
  </p><p><span m=''378050''>So</span> <span m=''378260''>the</span> <span m=''378360''>claim</span>
  <span m=''378640''>is</span> <span m=''378820''>facet-paths</span> <span m=''379620''>always</span>
  <span m=''379850''>exist</span> <span m=''380270''>for</span> <span m=''380420''>any</span>
  <span m=''380760''>triangulated,</span> <span m=''381510''>connected</span> <span
  m=''382870''>surface.</span> <span m=''385390''>Once</span> <span m=''385730''>you</span>
  <span m=''385830''>have</span> <span m=''386160''>this</span> <span m=''386450''>facet-path,</span>
  <span m=''388440''>you''re</span> <span m=''388690''>basically</span> <span m=''389110''>golden</span>
  <span m=''389620''>because</span> <span m=''390210''>you</span> <span m=''390480''>can</span>
  <span m=''393250''>lay</span> <span m=''393450''>it</span> <span m=''393540''>out</span>
  <span m=''395320''>without</span> <span m=''395740''>overlap.</span> <span m=''396810''>And</span>
  <span m=''397020''>that''s</span> <span m=''397490''>the</span> <span m=''397560''>next</span>
  <span m=''398440''>picture.</span> </p><p><span m=''400970''>So</span> <span m=''401450''>if</span>
  <span m=''401600''>you</span> <span m=''401730''>have</span> <span m=''402170''>a</span>
  <span m=''402250''>triangle</span> <span m=''404410''>and</span> <span m=''404720''>you</span>
  <span m=''404830''>have</span> <span m=''405020''>some</span> <span m=''406200''>corners</span>
  <span m=''406690''>of</span> <span m=''406840''>it</span> <span m=''406980''>that</span>
  <span m=''407100''>are</span> <span m=''407170''>hinged</span> <span m=''407490''>to</span>
  <span m=''407700''>adjacent</span> <span m=''408110''>triangles,</span> <span m=''409120''>you</span>
  <span m=''409320''>can</span> <span m=''409530''>rotate</span> <span m=''409930''>that</span>
  <span m=''410120''>triangle</span> <span m=''410580''>''til</span> <span m=''410930''>it
  fits</span> <span m=''411140''>in</span> <span m=''411270''>a</span> <span m=''411330''>vertical</span>
  <span m=''411740''>slab.</span> <span m=''412910''>And</span> <span m=''413270''>the</span>
  <span m=''413510''>hinges</span> <span m=''413970''>are</span> <span m=''414080''>on</span>
  <span m=''414770''>the</span> <span m=''414890''>ends</span> <span m=''415120''>of</span>
  <span m=''415180''>the</span> <span m=''415290''>slab.</span> <span m=''415650''>And</span>
  <span m=''415760''>so</span> <span m=''416360''>each</span> <span m=''416650''>triangle</span>
  <span m=''417060''>lives</span> <span m=''417180''>in</span> <span m=''417320''>its
  own</span> <span m=''417530''>slab.</span> <span m=''418150''>Slabs</span> <span
  m=''418460''>don''t</span> <span m=''418620''>intersect.</span> <span m=''419760''>No</span>
  <span m=''419890''>intersection.</span> </p><p><span m=''433980''>The</span> <span
  m=''434090''>hard</span> <span m=''434330''>part</span> <span m=''434530''>is</span>
  <span m=''434650''>really</span> <span m=''434860''>getting</span> <span m=''435130''>this</span>
  <span m=''435300''>path.</span> <span m=''435720''>Once</span> <span m=''435960''>you</span>
  <span m=''436050''>have</span> <span m=''436260''>that,</span> <span m=''436520''>you</span>
  <span m=''436650''>can</span> <span m=''436770''>just</span> <span m=''437050''>lay</span>
  <span m=''437250''>it</span> <span m=''437360''>out.</span> <span m=''438190''>It''s</span>
  <span m=''438270''>a</span> <span m=''438320''>little</span> <span m=''438530''>bit</span>
  <span m=''438670''>nontrivial</span> <span m=''439160''>with</span> <span m=''439300''>obtuse</span>
  <span m=''439560''>triangles.</span> <span m=''440540''>They</span> <span m=''440650''>don''t</span>
  <span m=''441220''>necessarily</span> <span m=''441660''>just</span> <span m=''441830''>lie</span>
  <span m=''442040''>along</span> <span m=''442330''>the</span> <span m=''442380''>horizontal</span>
  <span m=''442820''>line.</span> <span m=''443680''>You have</span> <span m=''443840''>to
  set</span> <span m=''444080''>things up</span> <span m=''444350''>so that</span>
  <span m=''444780''>those</span> <span m=''445030''>guys</span> <span m=''445460''>are</span>
  <span m=''445940''>on</span> <span m=''446090''>the</span> <span m=''446190''>boundary,</span>
  <span m=''447660''>but</span> <span m=''447970''>you</span> <span m=''448110''>can</span>
  <span m=''448250''>always</span> <span m=''448420''>rotate</span> <span m=''448750''>it</span>
  <span m=''448850''>so that</span> <span m=''449070''>that''s</span> <span m=''449700''>possible.</span>
  </p><p><span m=''454260''>So</span> <span m=''461680''>the</span> <span m=''461830''>real</span>
  <span m=''462050''>question</span> <span m=''462420''>is,</span> <span m=''462850''>how</span>
  <span m=''463060''>do</span> <span m=''463180''>we</span> <span m=''463990''>construct</span>
  <span m=''464480''>a</span> <span m=''464520''>facet-path?</span> <span m=''473820''>All
  right.</span> <span m=''474800''>So</span> <span m=''474940''>I</span> <span m=''475020''>have</span>
  <span m=''475150''>a</span> <span m=''475220''>bunch</span> <span m=''475420''>of</span>
  <span m=''475470''>triangles.</span> <span m=''476740''>In</span> <span m=''476870''>general,</span>
  <span m=''477210''>they</span> <span m=''477310''>make</span> <span m=''477710''>some</span>
  <span m=''477920''>surface.</span> <span m=''479360''>And</span> <span m=''479820''>maybe</span>
  <span m=''480120''>I</span> <span m=''480170''>should</span> <span m=''480900''>draw</span>
  <span m=''481210''>a</span> <span m=''481290''>running</span> <span m=''481580''>example</span>
  <span m=''482820''>over</span> <span m=''482990''>here.</span> </p><p><span m=''484340''>Let''s</span>
  <span m=''484590''>think</span> <span m=''484800''>about</span> <span m=''485972''>a</span>
  <span m=''486340''>triangulated</span> <span m=''487010''>cube,</span> <span m=''488050''>something</span>
  <span m=''488470''>simple.</span> <span m=''493220''>Imagine</span> <span m=''493520''>there''s</span>
  <span m=''493670''>more</span> <span m=''493830''>triangles</span> <span m=''494500''>in</span>
  <span m=''494570''>the</span> <span m=''494640''>back.</span> <span m=''495690''>It''s</span>
  <span m=''495890''>a</span> <span m=''495940''>little</span> <span m=''496170''>hard</span>
  <span m=''496350''>to</span> <span m=''496420''>think</span> <span m=''496600''>about</span>
  <span m=''496800''>the</span> <span m=''496880''>3D</span> <span m=''497160''>picture.</span>
  <span m=''497540''>I</span> <span m=''497650''>would</span> <span m=''497800''>really</span>
  <span m=''498050''>like</span> <span m=''498280''>to</span> <span m=''498750''>two</span>
  <span m=''498920''>dimensionalify</span> <span m=''499680''>it,</span> <span m=''500600''>and</span>
  <span m=''501080''>because</span> <span m=''501600''>this</span> <span m=''501800''>theorem</span>
  <span m=''502080''>works,</span> <span m=''502310''>not</span> <span m=''502490''>only</span>
  <span m=''502740''>for</span> <span m=''503000''>a</span> <span m=''503060''>polyhedron--</span>
  <span m=''505220''>it</span> <span m=''505380''>works</span> <span m=''505590''>for</span>
  <span m=''505750''>any</span> <span m=''506230''>manifold,</span> <span m=''507040''>any</span>
  <span m=''507380''>sort</span> <span m=''507620''>of</span> <span m=''507700''>locally,</span>
  <span m=''508050''>two</span> <span m=''508170''>dimensional</span> <span m=''508620''>thing--</span>
  <span m=''510390''>it would</span> <span m=''510540''>be</span> <span m=''510630''>nice</span>
  <span m=''510880''>if</span> <span m=''511020''>I</span> <span m=''511090''>could</span>
  <span m=''511280''>just</span> <span m=''511480''>sort of</span> <span m=''511750''>cut</span>
  <span m=''511970''>this</span> <span m=''512150''>open</span> <span m=''512919''>and</span>
  <span m=''513100''>think</span> <span m=''513299''>about</span> <span m=''513539''>a</span>
  <span m=''513600''>disc</span> <span m=''513960''>instead</span> <span m=''514250''>of</span>
  <span m=''514340''>a</span> <span m=''514390''>sphere,</span> <span m=''515230''>topologically.</span>
  </p><p><span m=''516730''>And</span> <span m=''516900''>I</span> <span m=''517380''>can.
  I mean</span> <span m=''517549''>this</span> <span m=''517730''>theorem''s</span>
  <span m=''517919''>supposed</span> <span m=''518169''>to</span> <span m=''518240''>work</span>
  <span m=''518390''>for</span> <span m=''518490''>discs</span> <span m=''518919''>just</span>
  <span m=''519169''>as</span> <span m=''519250''>well.</span> <span m=''519470''>It
  should</span> <span m=''519620''>work</span> <span m=''519809''>for</span> <span
  m=''519890''>anything</span> <span m=''520169''>that''s</span> <span m=''520320''>connected.</span>
  <span m=''521110''>So</span> <span m=''521210''>ideally,</span> <span m=''521539''>I</span>
  <span m=''521590''>cut</span> <span m=''521830''>it all</span> <span m=''522100''>apart</span>
  <span m=''522429''>into</span> <span m=''522630''>lots of</span> <span m=''522840''>little</span>
  <span m=''523020''>triangles,</span> <span m=''523530''>but</span> <span m=''523659''>it</span>
  <span m=''523700''>has</span> <span m=''523850''>to</span> <span m=''523929''>stay</span>
  <span m=''524100''>connected.</span> </p><p><span m=''526100''>So</span> <span m=''527370''>I''ll</span>
  <span m=''527720''>unfold</span> <span m=''528180''>it.</span> <span m=''529240''>Why
  not?</span> <span m=''529920''>So</span> <span m=''531070''>I</span> <span m=''531210''>can</span>
  <span m=''531480''>add</span> <span m=''531740''>some</span> <span m=''531880''>cuts</span>
  <span m=''532300''>until</span> <span m=''532700''>I</span> <span m=''532760''>get</span>
  <span m=''533030''>down</span> <span m=''533420''>to</span> <span m=''534140''>a</span>
  <span m=''534230''>spanning</span> <span m=''534680''>tree</span> <span m=''535690''>of</span>
  <span m=''540440''>the</span> <span m=''540510''>faces,</span> <span m=''541240''>a</span>
  <span m=''541570''>spanning</span> <span m=''541970''>tree</span> <span m=''542160''>of</span>
  <span m=''542260''>the</span> <span m=''542410''>dual</span> <span m=''542680''>graph.</span>
  <span m=''544016''>OK.</span> <span m=''544420''>For</span> <span m=''544570''>whatever</span>
  <span m=''544910''>reason,</span> <span m=''547740''>this is</span> <span m=''547900''>the</span>
  <span m=''548010''>triangulation</span> <span m=''548425''>I</span> <span m=''548840''>chose,</span>
  <span m=''549280''>and</span> <span m=''549410''>this is the</span> <span m=''549550''>unfolding</span>
  <span m=''550000''>I</span> <span m=''550070''>chose.</span> <span m=''550500''>But</span>
  <span m=''550740''>just</span> <span m=''550910''>keep</span> <span m=''551080''>cutting</span>
  <span m=''551400''>edges</span> <span m=''551740''>until</span> <span m=''552550''>cutting
  an</span> <span m=''552940''>edge</span> <span m=''553230''>would</span> <span m=''553400''>cause</span>
  <span m=''553640''>it</span> <span m=''553740''>to</span> <span m=''553820''>disconnect.</span>
  </p><p><span m=''554990''>So</span> <span m=''555120''>the</span> <span m=''555190''>maximal</span>
  <span m=''555730''>set</span> <span m=''555920''>of</span> <span m=''556010''>cuts,</span>
  <span m=''556490''>there</span> <span m=''556920''>are</span> <span m=''557000''>many</span>
  <span m=''557200''>ways</span> <span m=''557400''>to</span> <span m=''557490''>do</span>
  <span m=''557640''>it.</span> <span m=''557740''>When</span> <span m=''557880''>I</span>
  <span m=''557940''>unfold,</span> <span m=''558450''>it</span> <span m=''558530''>might</span>
  <span m=''558700''>overlap</span> <span m=''559450''>because</span> <span m=''559610''>we</span>
  <span m=''559700''>don''t</span> <span m=''559810''>know</span> <span m=''560020''>whether</span>
  <span m=''560280''>edge</span> <span m=''560380''>unfoldings</span> <span m=''560750''>exist,</span>
  <span m=''561220''>but</span> <span m=''561840''>that''s</span> <span m=''562020''>fine.</span>
  <span m=''562590''>You</span> <span m=''563060''>can</span> <span m=''563330''>think</span>
  <span m=''563540''>of</span> <span m=''563650''>it</span> <span m=''563740''>as</span>
  <span m=''563860''>a</span> <span m=''563920''>two</span> <span m=''564040''>dimensional</span>
  <span m=''564450''>picture,</span> <span m=''564810''>but</span> <span m=''564960''>it</span>
  <span m=''565060''>might</span> <span m=''566170''>need</span> <span m=''566350''>a</span>
  <span m=''566390''>few</span> <span m=''566620''>layers.</span> <span m=''567240''>We''re</span>
  <span m=''567320''>not</span> <span m=''567460''>going</span> <span m=''567550''>to</span>
  <span m=''567590''>actually</span> <span m=''567950''>fold</span> <span m=''568280''>this</span>
  <span m=''568450''>thing,</span> <span m=''568710''>but</span> <span m=''569160''>we''re</span>
  <span m=''569190''>going</span> <span m=''569290''>to</span> <span m=''569360''>cut</span>
  <span m=''569560''>this</span> <span m=''569730''>up</span> <span m=''569960''>into</span>
  <span m=''570330''>a</span> <span m=''570380''>facet-path.</span> </p><p><span m=''571500''>This</span>
  <span m=''571740''>could</span> <span m=''571960''>actually</span> <span m=''572270''>be</span>
  <span m=''572420''>our</span> <span m=''572530''>input.</span> <span m=''572910''>Instead</span>
  <span m=''573220''>of</span> <span m=''573290''>being</span> <span m=''573450''>given</span>
  <span m=''573985''>a</span> <span m=''574250''>polyhedron,</span> <span m=''574780''>we''re</span>
  <span m=''574880''>given</span> <span m=''575190''>a</span> <span m=''575260''>disc</span>
  <span m=''575530''>like</span> <span m=''575700''>this, a</span> <span m=''575960''>triangulated</span>
  <span m=''576470''>disc,</span> <span m=''577270''>and</span> <span m=''577490''>we</span>
  <span m=''577600''>have</span> <span m=''577810''>to</span> <span m=''578280''>deal</span>
  <span m=''578490''>with</span> <span m=''578640''>it.</span> <span m=''579020''>Somehow</span>
  <span m=''579390''>we''ve</span> <span m=''579510''>got</span> <span m=''579620''>to</span>
  <span m=''579680''>construct</span> <span m=''580040''>a</span> <span m=''580070''>facet-path</span>
  <span m=''580410''>here,</span> <span m=''580770''>visit</span> <span m=''581040''>every</span>
  <span m=''581250''>triangle</span> <span m=''581590''>exactly</span> <span m=''581970''>once,</span>
  <span m=''583020''>and</span> <span m=''584190''>passing</span> <span m=''584510''>through</span>
  <span m=''584640''>vertices.</span> </p><p><span m=''585320''>AUDIENCE: So if you</span>
  <span m=''585760''>have overlap,</span> <span m=''586200''>it</span> <span m=''586640''>doesn''t
  really</span> <span m=''587080''>matter.</span> </p><p><span m=''588400''>PROFESSOR:
  Yeah,</span> <span m=''588510''>overlap</span> <span m=''588910''>doesn''t</span>
  <span m=''589130''>really</span> <span m=''589320''>matter.</span> <span m=''589640''>We''re</span>
  <span m=''589760''>going</span> <span m=''589870''>to</span> <span m=''589980''>cut</span>
  <span m=''590200''>it</span> <span m=''590310''>up,</span> <span m=''590610''>and</span>
  <span m=''590760''>then,</span> <span m=''590870''>we''re</span> <span m=''590980''>going</span>
  <span m=''591100''>to</span> <span m=''591410''>splay</span> <span m=''591680''>out</span>
  <span m=''591960''>the</span> <span m=''592060''>triangles.</span> </p><p><span
  m=''592413''>AUDIENCE: Distances</span> <span m=''592766''>don''t</span> <span m=''593120''>matter.</span>
  <span m=''593526''>Right?</span> </p><p><span m=''595150''>PROFESSOR: No,</span>
  <span m=''595400''>uh.</span> </p><p><span m=''596708''>AUDIENCE: If you''re trying</span>
  <span m=''597144''>to</span> <span m=''597790''>just</span> <span m=''598205''>find
  a path--</span> </p><p><span m=''598620''>PROFESSOR: Right. From</span> <span m=''598760''>the</span>
  <span m=''598860''>perspective</span> <span m=''599360''>of</span> <span m=''599500''>facet-path,</span>
  <span m=''600410''>distances</span> <span m=''600910''>don''t</span> <span m=''601050''>matter.</span>
  <span m=''601440''>It''s just</span> <span m=''601610''>topology.</span> <span m=''602360''>Yeah.</span>
  <span m=''602630''>You</span> <span m=''602750''>could</span> <span m=''602920''>think</span>
  <span m=''603130''>of</span> <span m=''603240''>it</span> <span m=''603830''>as</span>
  <span m=''604140''>a</span> <span m=''604200''>circle</span> <span m=''605300''>with</span>
  <span m=''607590''>some</span> <span m=''607800''>decomposition</span> <span m=''608430''>into</span>
  <span m=''608610''>triangles,</span> <span m=''609280''>if</span> <span m=''609450''>you</span>
  <span m=''609610''>like,</span> <span m=''610700''>but</span> <span m=''611260''>that''s</span>
  <span m=''611500''>maybe</span> <span m=''611760''>harder</span> <span m=''612000''>to</span>
  <span m=''612080''>think</span> <span m=''612270''>about.</span> <span m=''613850''>I
  got to</span> <span m=''614110''>think</span> <span m=''614270''>about</span> <span
  m=''614490''>it</span> <span m=''614550''>this</span> <span m=''614710''>way.</span>
  <span m=''615630''>It''s</span> <span m=''616060''>useful</span> <span m=''616420''>because</span>
  <span m=''616650''>then,</span> <span m=''616760''>we''ll</span> <span m=''616890''>get</span>
  <span m=''617060''>to</span> <span m=''617170''>Mickey</span> <span m=''617400''>Mouses,</span>
  <span m=''617970''>as</span> <span m=''618100''>we''ll</span> <span m=''618210''>see.</span>
  </p><p><span m=''621000''>So</span> <span m=''622770''>cut</span> <span m=''623080''>edges</span>
  <span m=''625950''>until</span> <span m=''626760''>you</span> <span m=''626880''>can''t</span>
  <span m=''629530''>anymore,</span> <span m=''630310''>so</span> <span m=''630510''>until</span>
  <span m=''630810''>cutting</span> <span m=''631300''>would</span> <span m=''631470''>disconnect.</span>
  <span m=''638520''>So</span> <span m=''638740''>this</span> <span m=''638980''>means</span>
  <span m=''640040''>what</span> <span m=''640170''>you''re</span> <span m=''640290''>left</span>
  <span m=''640550''>with</span> <span m=''640730''>will</span> <span m=''640810''>be</span>
  <span m=''641130''>sort</span> <span m=''641290''>of</span> <span m=''641340''>a
  tree</span> <span m=''641770''>of</span> <span m=''641860''>faces.</span> <span
  m=''643640''>There''ll</span> <span m=''643740''>be</span> <span m=''643850''>no</span>
  <span m=''644000''>cycles</span> <span m=''644570''>because</span> <span m=''644800''>if
  there was</span> <span m=''645040''>a</span> <span m=''645100''>cycle,</span> <span
  m=''645480''>you</span> <span m=''645600''>could</span> <span m=''645760''>cut</span>
  <span m=''646190''>one</span> <span m=''646320''>of</span> <span m=''646380''>the</span>
  <span m=''646480''>edges,</span> <span m=''646790''>and</span> <span m=''646860''>it</span>
  <span m=''646920''>wouldn''t</span> <span m=''647140''>fall</span> <span m=''647300''>apart.</span>
  <span m=''649770''>So obviously,</span> <span m=''649950''>there''s</span> <span
  m=''650780''>a</span> <span m=''650950''>tree</span> <span m=''651270''>here.</span>
  </p><p><span m=''652570''>Now,</span> <span m=''652700''>trees</span> <span m=''653490''>have</span>
  <span m=''653720''>leaves.</span> <span m=''654980''>That''s</span> <span m=''655130''>our</span>
  <span m=''655230''>favorite</span> <span m=''656400''>lemma</span> <span m=''656750''>lately.</span>
  <span m=''657260''>They</span> <span m=''657670''>have</span> <span m=''657950''>at</span>
  <span m=''658000''>least</span> <span m=''658230''>two</span> <span m=''658400''>leaves.</span>
  </p><p><span m=''659480''>In</span> <span m=''659620''>the</span> <span m=''659710''>case</span>
  <span m=''659990''>of</span> <span m=''660080''>a</span> <span m=''660140''>triangulated</span>
  <span m=''660650''>polygon,</span> <span m=''661140''>we</span> <span m=''661250''>usually</span>
  <span m=''661480''>call</span> <span m=''661660''>them</span> <span m=''661830''>ears.</span>
  <span m=''662330''>So</span> <span m=''662630''>here''s</span> <span m=''662890''>a</span>
  <span m=''662960''>fun</span> <span m=''663240''>term.</span> <span m=''666700''>So</span>
  <span m=''666970''>let''s</span> <span m=''667160''>say</span> <span m=''667300''>color</span>
  <span m=''668650''>the</span> <span m=''668870''>ears.</span> <span m=''671740''>These</span>
  <span m=''672020''>are</span> <span m=''672280''>leaves</span> <span m=''674840''>and</span>
  <span m=''675390''>in</span> <span m=''675600''>that</span> <span m=''675820''>tree</span>
  <span m=''677200''>which</span> <span m=''677330''>call</span> <span m=''677540''>the</span>
  <span m=''678500''>dual</span> <span m=''678820''>tree.</span> </p><p><span m=''682190''>So</span>
  <span m=''682410''>in</span> <span m=''682590''>reality,</span> <span m=''683050''>we''re</span>
  <span m=''683170''>thinking</span> <span m=''683490''>about</span> <span m=''684290''>a</span>
  <span m=''684720''>dual</span> <span m=''684970''>graph</span> <span m=''685370''>which</span>
  <span m=''685540''>looks</span> <span m=''685670''>something</span> <span m=''685930''>like</span>
  <span m=''686120''>this,</span> <span m=''686990''>where</span> <span m=''687040''>there''s</span>
  <span m=''687190''>a</span> <span m=''687230''>vertex</span> <span m=''687600''>for</span>
  <span m=''687670''>every</span> <span m=''687860''>triangle</span> <span m=''688850''>and</span>
  <span m=''689110''>edges</span> <span m=''689580''>for</span> <span m=''689840''>every</span>
  <span m=''690460''>edge</span> <span m=''690820''>connecting</span> <span m=''691160''>triangles,</span>
  <span m=''691800''>and</span> <span m=''692200''>there''s</span> <span m=''692470''>leaves</span>
  <span m=''692740''>of</span> <span m=''692820''>that</span> <span m=''693050''>tree.</span>
  <span m=''693590''>But</span> <span m=''694380''>in</span> <span m=''694780''>the</span>
  <span m=''695360''>original</span> <span m=''695700''>thing,</span> <span m=''695900''>we</span>
  <span m=''695980''>think</span> <span m=''696180''>of</span> <span m=''696270''>this</span>
  <span m=''696450''>triangle</span> <span m=''696820''>as</span> <span m=''696920''>being</span>
  <span m=''697120''>an</span> <span m=''697190''>ear,</span> <span m=''698820''>and</span>
  <span m=''699050''>this</span> <span m=''699190''>triangle</span> <span m=''699730''>is</span>
  <span m=''699920''>an</span> <span m=''700000''>ear.</span> <span m=''701180''>And</span>
  <span m=''701590''>this</span> <span m=''701750''>triangle</span> <span m=''702180''>is</span>
  <span m=''702270''>an</span> <span m=''702360''>ear,</span> <span m=''703480''>and</span>
  <span m=''703850''>this</span> <span m=''704000''>triangle is an</span> <span m=''704450''>ear.</span>
  <span m=''706850''>I</span> <span m=''706960''>like</span> <span m=''707160''>ears</span>
  <span m=''707430''>because</span> <span m=''707620''>they''re</span> <span m=''707720''>kind</span>
  <span m=''707910''>of</span> <span m=''708180''>on</span> <span m=''708400''>the</span>
  <span m=''708550''>boundary,</span> <span m=''709150''>on</span> <span m=''709260''>the</span>
  <span m=''709330''>surface,</span> <span m=''710020''>so</span> <span m=''710780''>they''re</span>
  <span m=''710900''>just</span> <span m=''711050''>triangles</span> <span m=''711450''>that
  are</span> <span m=''711660''>adjacent to</span> <span m=''711930''>only</span>
  <span m=''712160''>one</span> <span m=''712330''>other</span> <span m=''712520''>triangle.</span>
  </p><p><span m=''714650''>Now,</span> <span m=''715720''>the</span> <span m=''716220''>next</span>
  <span m=''716400''>step</span> <span m=''716680''>is</span> <span m=''716850''>to</span>
  <span m=''716970''>color</span> <span m=''717590''>what</span> <span m=''717770''>are</span>
  <span m=''717900''>called</span> <span m=''718370''>the</span> <span m=''718510''>second-level</span>
  <span m=''719170''>ears.</span> <span m=''720340''>I''ll</span> <span m=''720520''>call</span>
  <span m=''720680''>them</span> <span m=''720880''>the</span> <span m=''721020''>remaining</span>
  <span m=''721430''>ears,</span> <span m=''722020''>if</span> <span m=''722210''>you</span>
  <span m=''722350''>remove</span> <span m=''722770''>those</span> <span m=''723040''>ears,</span>
  <span m=''723690''>what</span> <span m=''723970''>would,</span> <span m=''724120''>then,</span>
  <span m=''724300''>become</span> <span m=''724620''>an</span> <span m=''724700''>ear.</span>
  <span m=''729390''>All</span> <span m=''729470''>right.</span> <span m=''729800''>Now,</span>
  <span m=''730050''>I</span> <span m=''730170''>wish</span> <span m=''730410''>I</span>
  <span m=''730430''>had</span> <span m=''730620''>another</span> <span m=''730870''>color.</span>
  <span m=''732531''>Yeah,</span> <span m=''732960''>that''s</span> <span m=''733230''>kind</span>
  <span m=''733410''>of</span> <span m=''733450''>yellowish.</span> </p><p><span m=''734260''>So</span>
  <span m=''734550''>this</span> <span m=''734760''>would</span> <span m=''734860''>become</span>
  <span m=''735230''>an</span> <span m=''735310''>ear.</span> <span m=''736060''>This</span>
  <span m=''736240''>would</span> <span m=''736330''>become</span> <span m=''736650''>an</span>
  <span m=''736690''>ear.</span> <span m=''737170''>This</span> <span m=''737630''>would</span>
  <span m=''737880''>become</span> <span m=''738070''>an</span> <span m=''738140''>ear,</span>
  <span m=''738410''>and</span> <span m=''738620''>this</span> <span m=''738770''>would</span>
  <span m=''738870''>become</span> <span m=''739170''>an</span> <span m=''739310''>ear.</span>
  <span m=''742340''>And I''m</span> <span m=''742690''>going</span> <span m=''742790''>to</span>
  <span m=''742850''>stop</span> <span m=''743150''>there,</span> <span m=''743450''>just</span>
  <span m=''743640''>two</span> <span m=''743750''>levels.</span> </p><p><span m=''746280''>What</span>
  <span m=''746610''>could</span> <span m=''746770''>I</span> <span m=''746840''>get</span>
  <span m=''747750''>in</span> <span m=''747910''>this</span> <span m=''748070''>process?</span>
  <span m=''749860''>I</span> <span m=''749890''>mean</span> <span m=''750040''>what</span>
  <span m=''750170''>it</span> <span m=''750280''>looks</span> <span m=''750540''>like</span>
  <span m=''750830''>I''m</span> <span m=''750930''>getting</span> <span m=''751150''>is</span>
  <span m=''751270''>I</span> <span m=''751320''>get</span> <span m=''751490''>an</span>
  <span m=''751580''>ear</span> <span m=''752270''>and</span> <span m=''752360''>then,</span>
  <span m=''752430''>a</span> <span m=''752490''>second-level</span> <span m=''753020''>ear.</span>
  <span m=''753370''>It</span> <span m=''753740''>could</span> <span m=''753900''>be</span>
  <span m=''754010''>a</span> <span m=''754060''>little</span> <span m=''754260''>more</span>
  <span m=''754420''>general</span> <span m=''754740''>than</span> <span m=''754880''>that.</span>
  </p><p><span m=''755540''>Maybe,</span> <span m=''755890''>for</span> <span m=''756030''>example,</span>
  <span m=''756600''>if</span> <span m=''756650''>I</span> <span m=''756710''>had</span>
  <span m=''756850''>a</span> <span m=''756910''>triangle</span> <span m=''757260''>like</span>
  <span m=''757420''>this,</span> <span m=''758490''>both</span> <span m=''758630''>of</span>
  <span m=''758720''>these</span> <span m=''758970''>would</span> <span m=''759000''>be</span>
  <span m=''759140''>first-level</span> <span m=''759640''>ears,</span> <span m=''760190''>and</span>
  <span m=''760340''>then,</span> <span m=''760450''>this</span> <span m=''760630''>would</span>
  <span m=''760710''>become</span> <span m=''760990''>a</span> <span m=''761050''>second-level</span>
  <span m=''761600''>ear.</span> <span m=''762600''>Turns</span> <span m=''762890''>out</span>
  <span m=''763050''>that''s</span> <span m=''763260''>all</span> <span m=''763430''>that</span>
  <span m=''763510''>can</span> <span m=''763670''>happen.</span> <span m=''765080''>Because</span>
  <span m=''765360''>these</span> <span m=''765500''>are</span> <span m=''765570''>triangles,</span>
  <span m=''767080''>second-level</span> <span m=''767710''>ear,</span> <span m=''769260''>at</span>
  <span m=''769360''>this</span> <span m=''769540''>point,</span> <span m=''769740''>it''s</span>
  <span m=''769840''>only</span> <span m=''770040''>adjacent</span> <span m=''770360''>to</span>
  <span m=''770460''>one</span> <span m=''770600''>other</span> <span m=''770760''>thing.</span>
  </p><p><span m=''771060''>So</span> <span m=''771190''>what</span> <span m=''771320''>was</span>
  <span m=''771460''>it</span> <span m=''771550''>adjacent</span> <span m=''771930''>to</span>
  <span m=''772030''>before?</span> <span m=''772760''>Well,</span> <span m=''772930''>maybe,</span>
  <span m=''773220''>one</span> <span m=''773430''>ear,</span> <span m=''773960''>certainly</span>
  <span m=''774300''>not</span> <span m=''774580''>zero</span> <span m=''774860''>because</span>
  <span m=''775130''>it</span> <span m=''775200''>wasn''t</span> <span m=''775450''>a</span>
  <span m=''775500''>first-level</span> <span m=''775960''>ear.</span> <span m=''777000''>So</span>
  <span m=''777370''>at</span> <span m=''777450''>least</span> <span m=''777640''>one</span>
  <span m=''777880''>ear,</span> <span m=''778310''>maybe</span> <span m=''778550''>two</span>
  <span m=''778760''>ears.</span> <span m=''779270''>That''s</span> <span m=''779480''>it.</span>
  </p><p><span m=''780157''>AUDIENCE: Unless</span> <span m=''780654''>there''s only</span>
  <span m=''781151''>four pieces left.</span> <span m=''781648''>Right?</span> </p><p><span
  m=''783640''>PROFESSOR: Sorry,</span> <span m=''783910''>what do</span> <span m=''783990''>you</span>
  <span m=''784070''>mean?</span> </p><p><span m=''784520''>AUDIENCE: You could have
  three ears.</span> </p><p><span m=''786660''>PROFESSOR: You</span> <span m=''786770''>could</span>
  <span m=''786890''>have</span> <span m=''787080''>three</span> <span m=''787340''>years.</span>
  <span m=''788060''>Yeah,</span> <span m=''788310''>so</span> <span m=''788390''>here</span>
  <span m=''788610''>I have</span> <span m=''788800''>two.</span> <span m=''789180''>I</span>
  <span m=''789240''>mean</span> <span m=''789390''>the</span> <span m=''789480''>first-level</span>
  <span m=''789930''>ear</span> <span m=''790050''>and</span> <span m=''790100''>a</span>
  <span m=''790160''>second-level,</span> <span m=''790760''>or</span> <span m=''790940''>it</span>
  <span m=''791040''>could</span> <span m=''791100''>be</span> <span m=''791210''>a</span>
  <span m=''791260''>first-level--</span> <span m=''792380''>Oh,</span> <span m=''792530''>you''re</span>
  <span m=''792640''>saying</span> <span m=''792850''>at</span> <span m=''792980''>the</span>
  <span m=''793130''>end.</span> <span m=''794020''>Right.</span> <span m=''794740''>It</span>
  <span m=''794910''>could</span> <span m=''795060''>be</span> <span m=''795190''>like</span>
  <span m=''795400''>this.</span> <span m=''795970''>That</span> <span m=''796110''>would</span>
  <span m=''796180''>only</span> <span m=''796400''>happen</span> <span m=''796680''>at</span>
  <span m=''796760''>the</span> <span m=''796840''>very</span> <span m=''797110''>end.</span>
  <span m=''798220''>But</span> <span m=''798250''>yeah,</span> <span m=''798570''>this</span>
  <span m=''798760''>could</span> <span m=''798900''>be</span> <span m=''799080''>first-level</span>
  <span m=''800020''>ears,</span> <span m=''800230''>and</span> <span m=''800310''>this</span>
  <span m=''800520''>is</span> <span m=''800630''>the</span> <span m=''800710''>second-level</span>
  <span m=''800990''>ear.</span> <span m=''801275''>Good</span> <span m=''801560''>point.</span>
  </p><p><span m=''802810''>Most</span> <span m=''803080''>of</span> <span m=''803130''>the</span>
  <span m=''803230''>time,</span> <span m=''808310''>we</span> <span m=''808460''>will</span>
  <span m=''808600''>either</span> <span m=''808950''>get</span> <span m=''813450''>something</span>
  <span m=''814040''>like</span> <span m=''814600''>this,</span> <span m=''815940''>the</span>
  <span m=''816080''>rest</span> <span m=''816360''>of</span> <span m=''816440''>the</span>
  <span m=''816520''>polygons</span> <span m=''817010''>over</span> <span m=''817200''>here--</span>
  <span m=''817470''>so</span> <span m=''817610''>this</span> <span m=''817790''>is</span>
  <span m=''817920''>a</span> <span m=''817980''>first-level</span> <span m=''818500''>ear.</span>
  <span m=''818780''>This</span> <span m=''818970''>is</span> <span m=''819090''>a</span>
  <span m=''819150''>second-level</span> <span m=''819700''>ear.</span> <span m=''821020''>--or</span>
  <span m=''824550''>I</span> <span m=''824720''>get--</span> <span m=''829710''>this</span>
  <span m=''829890''>is</span> <span m=''830050''>the</span> <span m=''830150''>Mickey</span>
  <span m=''830430''>Mouse</span> <span m=''830850''>picture.</span> <span m=''833110''>Probably</span>
  <span m=''833400''>not</span> <span m=''833550''>allowed</span> <span m=''833800''>to</span>
  <span m=''833860''>say</span> <span m=''834070''>Mickey</span> <span m=''834360''>Mouse.</span>
  <span m=''835435''>It''s under</span> <span m=''835810''>copyright,</span> <span
  m=''836610''>but</span> <span m=''837580''>there</span> <span m=''837820''>you</span>
  <span m=''837870''>go.</span> </p><p><span m=''840650''>So</span> <span m=''840830''>two</span>
  <span m=''841020''>first-level</span> <span m=''841450''>ears,</span> <span m=''841680''>second-level</span>
  <span m=''842020''>ear.</span> <span m=''842820''>Boom.</span> <span m=''844220''>This</span>
  <span m=''844400''>is,</span> <span m=''844490''>most</span> <span m=''844720''>of</span>
  <span m=''844820''>the</span> <span m=''844920''>time,</span> <span m=''845020''>what</span>
  <span m=''845140''>you''ll</span> <span m=''845260''>get</span> <span m=''845670''>in</span>
  <span m=''845860''>the</span> <span m=''846190''>base</span> <span m=''846470''>case</span>
  <span m=''846810''>of</span> <span m=''846960''>this</span> <span m=''847160''>induction.</span>
  <span m=''847670''>I''m</span> <span m=''847780''>going</span> <span m=''847910''>to</span>
  <span m=''848200''>pluck</span> <span m=''848520''>off</span> <span m=''848670''>these</span>
  <span m=''848860''>ears</span> <span m=''849120''>and</span> <span m=''849220''>keep</span>
  <span m=''849370''>making</span> <span m=''849720''>the thing</span> <span m=''849900''>smaller.</span>
  <span m=''850470''>At</span> <span m=''850690''>the</span> <span m=''850840''>end,</span>
  <span m=''851300''>there</span> <span m=''851500''>are a</span> <span m=''851530''>few</span>
  <span m=''851900''>cases to</span> <span m=''852360''>think</span> <span m=''852580''>about.</span>
  <span m=''853630''>I have them</span> <span m=''853990''>drawn</span> <span m=''854300''>here</span>
  <span m=''854590''>somewhere,</span> <span m=''856560''>base</span> <span m=''856850''>cases.</span>
  <span m=''860190''>Nothing.</span> <span m=''861230''>Yeah,</span> <span m=''861590''>well.</span>
  </p><p><span m=''870500''>This</span> <span m=''870680''>won''t</span> <span m=''870850''>work</span>
  <span m=''871100''>out</span> <span m=''871360''>if</span> <span m=''871480''>you</span>
  <span m=''871570''>have</span> <span m=''871730''>one</span> <span m=''871930''>triangle,</span>
  <span m=''872830''>if</span> <span m=''872990''>you</span> <span m=''873090''>have</span>
  <span m=''874200''>zero</span> <span m=''874520''>triangles,</span> <span m=''875430''>which</span>
  <span m=''875530''>is</span> <span m=''875630''>this</span> <span m=''875750''>empty</span>
  <span m=''876020''>picture,</span> <span m=''877670''>or</span> <span m=''877860''>if</span>
  <span m=''877940''>you</span> <span m=''878010''>just</span> <span m=''878200''>have</span>
  <span m=''878370''>two</span> <span m=''878850''>maybe.</span> <span m=''879875''>Well,</span>
  <span m=''880310''>I</span> <span m=''880430''>guess--</span> <span m=''881260''>Yeah,</span>
  <span m=''881420''>because</span> <span m=''881610''>then,</span> <span m=''881700''>these</span>
  <span m=''881850''>are</span> <span m=''881900''>both</span> <span m=''882090''>first-level</span>
  <span m=''882560''>ears.</span> <span m=''882770''>It</span> <span m=''882840''>doesn''t</span>
  <span m=''883160''>look</span> <span m=''883330''>quite</span> <span m=''883580''>the</span>
  <span m=''883670''>same.</span> <span m=''884780''>Or</span> <span m=''886680''>maybe</span>
  <span m=''886990''>just</span> <span m=''887310''>a</span> <span m=''887360''>Mickey</span>
  <span m=''887820''>Mouse</span> <span m=''888850''>because those are</span> <span
  m=''889190''>all--</span> <span m=''890096''>Well, it</span> <span m=''890450''>probably</span>
  <span m=''890700''>works.</span> <span m=''891590''>Anyway,</span> <span m=''893570''>these
  are the</span> <span m=''893720''>sort</span> <span m=''893920''>of</span> <span
  m=''894000''>cases</span> <span m=''894370''>you</span> <span m=''894730''>worry</span>
  <span m=''894960''>about.</span> </p><p><span m=''897090''>But</span> <span m=''897360''>for</span>
  <span m=''897460''>these</span> <span m=''897680''>cases,</span> <span m=''898010''>I</span>
  <span m=''898080''>just</span> <span m=''898290''>need</span> <span m=''898400''>to</span>
  <span m=''898490''>check</span> <span m=''898790''>that</span> <span m=''898910''>I</span>
  <span m=''898970''>can</span> <span m=''899150''>find</span> <span m=''899360''>a</span>
  <span m=''899400''>facet-path.</span> <span m=''900140''>So</span> <span m=''900250''>for</span>
  <span m=''900380''>example,</span> <span m=''900680''>this</span> <span m=''900860''>one,</span>
  <span m=''901470''>I</span> <span m=''901580''>just</span> <span m=''901760''>visit</span>
  <span m=''901980''>the</span> <span m=''902060''>triangle.</span> <span m=''902930''>This</span>
  <span m=''903140''>one--</span> <span m=''904130''>I don''t know--</span> <span
  m=''904260''>I</span> <span m=''906230''>do</span> <span m=''906320''>it</span>
  <span m=''906400''>like</span> <span m=''906570''>that.</span> <span m=''906820''>In</span>
  <span m=''907020''>fact,</span> <span m=''907340''>I</span> <span m=''907440''>can</span>
  <span m=''907560''>make</span> <span m=''907730''>it</span> <span m=''907810''>a</span>
  <span m=''907860''>cycle</span> <span m=''908805''>if</span> <span m=''909250''>I</span>
  <span m=''909370''>want</span> <span m=''909540''>to</span> <span m=''909580''>go</span>
  <span m=''909710''>crazy.</span> <span m=''911660''>This</span> <span m=''911900''>one--</span>
  <span m=''912090''>I don''t</span> <span m=''912470''>know--</span> <span m=''912850''>something</span>
  <span m=''913310''>like</span> <span m=''913550''>this.</span> <span m=''915166''>That''d
  be</span> <span m=''915550''>one</span> <span m=''915680''>way</span> <span m=''915780''>to</span>
  <span m=''915880''>do</span> <span m=''916050''>it.</span> </p><p><span m=''917650''>(SINGING)
  Doo, doo,</span> <span m=''918030''>doo.</span> <span m=''921400''>Hm.</span> <span
  m=''924350''>Got</span> <span m=''924480''>to</span> <span m=''924520''>be</span>
  <span m=''924610''>a</span> <span m=''924660''>little</span> <span m=''924840''>careful.</span>
  <span m=''926620''>[INAUDIBLE].</span> <span m=''930980''>Something</span> <span
  m=''931260''>like</span> <span m=''931430''>that.</span> </p><p><span m=''932350''>All</span>
  <span m=''932840''>right.</span> <span m=''933100''>But</span> <span m=''933240''>really,</span>
  <span m=''933510''>I</span> <span m=''933580''>care</span> <span m=''933830''>about</span>
  <span m=''934360''>these</span> <span m=''934580''>two</span> <span m=''934700''>cases.</span>
  <span m=''937340''>So</span> <span m=''937640''>what</span> <span m=''937790''>I''m</span>
  <span m=''937870''>going</span> <span m=''937980''>to</span> <span m=''938070''>do</span>
  <span m=''938230''>for</span> <span m=''938360''>each</span> <span m=''938590''>of</span>
  <span m=''938680''>those--</span> <span m=''939856''>I</span> <span m=''940230''>guess</span>
  <span m=''940510''>this is</span> <span m=''940790''>still</span> <span m=''941100''>step</span>
  <span m=''941400''>four--</span> <span m=''948430''>is</span> <span m=''950380''>I</span>
  <span m=''950530''>actually</span> <span m=''950760''>want</span> <span m=''950920''>to</span>
  <span m=''950970''>make</span> <span m=''951140''>cycles</span> <span m=''952080''>for</span>
  <span m=''952210''>these</span> <span m=''952450''>guys.</span> <span m=''953706''>I</span>
  <span m=''954130''>care</span> <span m=''954400''>about</span> <span m=''954710''>that.</span>
  <span m=''963440''>Am</span> <span m=''963835''>I</span> <span m=''964230''>doing</span>
  <span m=''964450''>something</span> <span m=''964780''>wrong?</span> <span m=''965250''>Oh,
  no.</span> <span m=''965720''>Over</span> <span m=''966190''>there.</span> <span
  m=''966660''>Good.</span> </p><p><span m=''969950''>So in</span> <span m=''970190''>both</span>
  <span m=''970410''>of</span> <span m=''970480''>these</span> <span m=''970660''>cases,</span>
  <span m=''971020''>I can make</span> <span m=''971420''>cycles.</span> <span m=''971780''>In</span>
  <span m=''971890''>this</span> <span m=''972070''>one,</span> <span m=''972430''>in</span>
  <span m=''972560''>the</span> <span m=''972630''>base</span> <span m=''972850''>cases,</span>
  <span m=''973140''>not</span> <span m=''973340''>always.</span> <span m=''973720''>Like</span>
  <span m=''973890''>this</span> <span m=''974070''>guy,</span> <span m=''974990''>hard</span>
  <span m=''975190''>to</span> <span m=''975260''>make</span> <span m=''975440''>a</span>
  <span m=''975500''>cycle.</span> <span m=''977770''>But</span> <span m=''978130''>for</span>
  <span m=''978250''>the</span> <span m=''978380''>two</span> <span m=''978550''>general</span>
  <span m=''978880''>cases,</span> <span m=''979335''>if</span> <span m=''979790''>I</span>
  <span m=''979870''>find</span> <span m=''980130''>two</span> <span m=''980280''>ears</span>
  <span m=''980580''>or</span> <span m=''980620''>three</span> <span m=''980820''>ears,</span>
  <span m=''981300''>I</span> <span m=''981400''>can</span> <span m=''981540''>just</span>
  <span m=''981940''>draw</span> <span m=''982080''>that</span> <span m=''982230''>in.</span>
  <span m=''982370''>So</span> <span m=''982570''>I''ll</span> <span m=''982680''>do</span>
  <span m=''982770''>that</span> <span m=''983010''>for</span> <span m=''983100''>this</span>
  <span m=''983300''>example,</span> <span m=''983810''>though,</span> <span m=''984510''>by
  now, it''s</span> <span m=''984880''>gotten</span> <span m=''985010''>a</span> <span
  m=''985070''>little</span> <span m=''985220''>messy,</span> <span m=''985660''>so</span>
  <span m=''985720''>let</span> <span m=''985820''>me</span> <span m=''985950''>redraw</span>
  <span m=''986280''>it.</span> </p><p><span m=''990930''>So</span> <span m=''991430''>we</span>
  <span m=''991540''>have--</span> <span m=''1003133''>All right.</span> <span m=''1003630''>So</span>
  <span m=''1003850''>I''m</span> <span m=''1003980''>going</span> <span m=''1004140''>to</span>
  <span m=''1004430''>connect</span> <span m=''1005130''>these</span> <span m=''1005420''>guys</span>
  <span m=''1007170''>and</span> <span m=''1007700''>connect</span> <span m=''1008030''>these</span>
  <span m=''1008360''>guys.</span> <span m=''1009390''>This</span> <span m=''1009550''>case,</span>
  <span m=''1009880''>I</span> <span m=''1009980''>only</span> <span m=''1010160''>get</span>
  <span m=''1010300''>the</span> <span m=''1010590''>two-ear</span> <span m=''1010750''>case,</span>
  <span m=''1011080''>but</span> <span m=''1011170''>I</span> <span m=''1011200''>think</span>
  <span m=''1011380''>we''ll</span> <span m=''1011500''>get</span> <span m=''1011650''>another</span>
  <span m=''1011920''>case</span> <span m=''1012950''>shortly.</span> <span m=''1021370''>OK?</span>
  <span m=''1022180''>So</span> <span m=''1022440''>obviously,</span> <span m=''1022540''>I</span>
  <span m=''1022660''>haven''t</span> <span m=''1023010''>finished</span> <span m=''1023420''>it,</span>
  <span m=''1024310''>and</span> <span m=''1024490''>these</span> <span m=''1024640''>are</span>
  <span m=''1024700''>disconnected.</span> <span m=''1025400''>There''s</span> <span
  m=''1025710''>lots</span> <span m=''1025920''>of</span> <span m=''1026030''>things</span>
  <span m=''1026250''>left</span> <span m=''1026460''>to</span> <span m=''1026550''>do.</span>
  </p><p><span m=''1027750''>But</span> <span m=''1029670''>then,</span> <span m=''1029920''>the</span>
  <span m=''1030060''>idea</span> <span m=''1030410''>is</span> <span m=''1030760''>repeat.</span>
  <span m=''1033690''>So</span> <span m=''1033839''>imagine</span> <span m=''1034260''>those</span>
  <span m=''1034460''>guys</span> <span m=''1034670''>as</span> <span m=''1034760''>being</span>
  <span m=''1034990''>done.</span> <span m=''1035880''>I''m</span> <span m=''1036089''>left</span>
  <span m=''1036420''>with</span> <span m=''1036770''>these</span> <span m=''1037619''>four</span>
  <span m=''1037839''>triangles,</span> <span m=''1039349''>actually,</span> <span
  m=''1039890''>a</span> <span m=''1040369''>little</span> <span m=''1041300''>boring</span>
  <span m=''1042560''>because I</span> <span m=''1042640''>don''t</span> <span m=''1042790''>get</span>
  <span m=''1042900''>the</span> <span m=''1042980''>Mickey</span> <span m=''1043210''>Mouse</span>
  <span m=''1043450''>case.</span> <span m=''1045089''>But</span> <span m=''1045619''>then,</span>
  <span m=''1045780''>this</span> <span m=''1045940''>will</span> <span m=''1046010''>be</span>
  <span m=''1046150''>an</span> <span m=''1046440''>ear.</span> <span m=''1046720''>This</span>
  <span m=''1046869''>will</span> <span m=''1046970''>be</span> <span m=''1047040''>a</span>
  <span m=''1047099''>second-level</span> <span m=''1047630''>ear.</span> <span m=''1048410''>And</span>
  <span m=''1048560''>so</span> <span m=''1048760''>I''ll</span> <span m=''1048850''>end</span>
  <span m=''1048980''>up</span> <span m=''1049150''>doing</span> <span m=''1050500''>this.</span>
  <span m=''1052380''>And</span> <span m=''1052820''>this</span> <span m=''1053020''>will</span>
  <span m=''1053140''>be</span> <span m=''1053270''>an</span> <span m=''1053370''>ear,</span>
  <span m=''1054150''>and</span> <span m=''1054370''>this</span> <span m=''1054540''>will</span>
  <span m=''1054620''>be an</span> <span m=''1054780''>ear,</span> <span m=''1056180''>second-level</span>
  <span m=''1056660''>here.</span> <span m=''1057030''>I</span> <span m=''1057090''>mean</span>
  <span m=''1057230''>this</span> <span m=''1057390''>is</span> <span m=''1057520''>actually</span>
  <span m=''1057760''>the</span> <span m=''1057840''>base</span> <span m=''1058090''>case,</span>
  <span m=''1058500''>if you</span> <span m=''1058590''>will.</span> </p><p><span
  m=''1060670''>So</span> <span m=''1060760''>in</span> <span m=''1060830''>general,</span>
  <span m=''1061090''>I</span> <span m=''1061170''>just</span> <span m=''1061350''>pluck</span>
  <span m=''1061580''>off</span> <span m=''1061770''>two</span> <span m=''1061900''>or</span>
  <span m=''1061980''>three</span> <span m=''1062150''>triangles,</span> <span m=''1062660''>repeat</span>
  <span m=''1063000''>until</span> <span m=''1063230''>I</span> <span m=''1063280''>get</span>
  <span m=''1063430''>one</span> <span m=''1063540''>of</span> <span m=''1063590''>the</span>
  <span m=''1063660''>base</span> <span m=''1063920''>cases.</span> <span m=''1065040''>Now,</span>
  <span m=''1065210''>what</span> <span m=''1065340''>I</span> <span m=''1065410''>have</span>
  <span m=''1065820''>is</span> <span m=''1065960''>not</span> <span m=''1066290''>connected,</span>
  <span m=''1068110''>but</span> <span m=''1068510''>it''s</span> <span m=''1068750''>a</span>
  <span m=''1068800''>bunch</span> <span m=''1069070''>of</span> <span m=''1069170''>cycles.</span>
  <span m=''1070310''>But</span> <span m=''1070480''>there''s</span> <span m=''1070670''>one</span>
  <span m=''1070870''>cycle</span> <span m=''1071160''>here,</span> <span m=''1071520''>one</span>
  <span m=''1071670''>cycle</span> <span m=''1072000''>there,</span> <span m=''1072410''>one</span>
  <span m=''1072550''>cycle</span> <span m=''1072840''>there.</span> </p><p><span
  m=''1074950''>You</span> <span m=''1075130''>could</span> <span m=''1075320''>actually</span>
  <span m=''1075590''>connect</span> <span m=''1075840''>some</span> <span m=''1076000''>of</span>
  <span m=''1076040''>them</span> <span m=''1076170''>together,</span> <span m=''1076500''>like</span>
  <span m=''1076670''>these</span> <span m=''1076870''>two.</span> <span m=''1077070''>You</span>
  <span m=''1077260''>could</span> <span m=''1077540''>go</span> <span m=''1077640''>around</span>
  <span m=''1078200''>like</span> <span m=''1078400''>this</span> <span m=''1078630''>and</span>
  <span m=''1078750''>then,</span> <span m=''1078940''>go</span> <span m=''1079260''>like</span>
  <span m=''1079450''>that,</span> <span m=''1079820''>so</span> <span m=''1079990''>that</span>
  <span m=''1080170''>could</span> <span m=''1080300''>be</span> <span m=''1080440''>a</span>
  <span m=''1080500''>bigger</span> <span m=''1080800''>cycle.</span> <span m=''1081780''>But</span>
  <span m=''1082090''>these</span> <span m=''1082390''>cycles</span> <span m=''1082920''>are</span>
  <span m=''1083080''>not</span> <span m=''1083300''>even</span> <span m=''1083480''>attached</span>
  <span m=''1083910''>to</span> <span m=''1083970''>these</span> <span m=''1084150''>cycles,</span>
  <span m=''1084670''>so</span> <span m=''1084760''>it''s</span> <span m=''1084990''>kind</span>
  <span m=''1085140''>of</span> <span m=''1085220''>a</span> <span m=''1085290''>problem.</span>
  </p><p><span m=''1086310''>That''s</span> <span m=''1086540''>step</span> <span
  m=''1086770''>five</span> <span m=''1087140''>is we''re</span> <span m=''1087280''>going</span>
  <span m=''1087410''>to</span> <span m=''1087480''>fix</span> <span m=''1087890''>all
  the</span> <span m=''1087970''>problems.</span> <span m=''1091020''>That''d be a</span>
  <span m=''1091480''>great</span> <span m=''1091740''>title.</span> <span m=''1093080''>Connect</span>
  <span m=''1095120''>cycles</span> <span m=''1096870''>together.</span> <span m=''1100800''>We''re</span>
  <span m=''1100920''>going</span> <span m=''1101000''>to</span> <span m=''1101070''>do</span>
  <span m=''1101170''>that</span> <span m=''1101400''>by</span> <span m=''1101530''>local</span>
  <span m=''1101870''>switches,</span> <span m=''1102800''>so</span> <span m=''1103120''>here''s</span>
  <span m=''1103750''>the</span> <span m=''1104240''>general</span> <span m=''1104510''>picture.</span>
  </p><p><span m=''1104870''>Suppose</span> <span m=''1105170''>you</span> <span m=''1105250''>have</span>
  <span m=''1105360''>two</span> <span m=''1105560''>adjacent</span> <span m=''1105930''>triangles</span>
  <span m=''1107180''>and</span> <span m=''1107760''>two</span> <span m=''1108020''>completely</span>
  <span m=''1108660''>separate</span> <span m=''1109060''>paths.</span> <span m=''1111940''>So</span>
  <span m=''1112160''>it''s</span> <span m=''1113040''>a</span> <span m=''1113110''>cycle,</span>
  <span m=''1114240''>so</span> <span m=''1114400''>some</span> <span m=''1114690''>cycle</span>
  <span m=''1115010''>over</span> <span m=''1115190''>here.</span> <span m=''1116180''>And</span>
  <span m=''1116840''>if</span> <span m=''1116940''>this</span> <span m=''1117120''>guy</span>
  <span m=''1117230''>shared</span> <span m=''1117520''>a</span> <span m=''1117560''>vertex,</span>
  <span m=''1118010''>then</span> <span m=''1118120''>I</span> <span m=''1118170''>could</span>
  <span m=''1118320''>actually</span> <span m=''1118560''>connect</span> <span m=''1118820''>them</span>
  <span m=''1118940''>together.</span> <span m=''1119320''>So</span> <span m=''1119460''>suppose</span>
  <span m=''1119820''>it</span> <span m=''1119880''>doesn''t</span> <span m=''1120140''>share
  a</span> <span m=''1120350''>vertex.</span> <span m=''1120700''>That</span> <span
  m=''1120830''>means</span> <span m=''1120980''>it</span> <span m=''1121040''>has</span>
  <span m=''1121280''>to</span> <span m=''1121360''>use</span> <span m=''1121500''>these</span>
  <span m=''1121730''>two,</span> <span m=''1122640''>and</span> <span m=''1122820''>then,</span>
  <span m=''1123050''>it--</span> <span m=''1124670''>something</span> <span m=''1124990''>like</span>
  <span m=''1125160''>that.</span> </p><p><span m=''1126510''>What</span> <span m=''1126660''>I</span>
  <span m=''1126710''>want</span> <span m=''1126900''>to</span> <span m=''1126960''>do</span>
  <span m=''1127640''>is</span> <span m=''1127890''>remove</span> <span m=''1128310''>this</span>
  <span m=''1128520''>edge</span> <span m=''1129350''>and</span> <span m=''1129650''>remove</span>
  <span m=''1130010''>this</span> <span m=''1130220''>edge</span> <span m=''1130940''>and,</span>
  <span m=''1131140''>instead,</span> <span m=''1131580''>add</span> <span m=''1132010''>this</span>
  <span m=''1132240''>edge</span> <span m=''1133150''>and</span> <span m=''1133390''>that</span>
  <span m=''1133610''>edge.</span> <span m=''1135060''>So</span> <span m=''1135560''>that''s</span>
  <span m=''1135760''>a</span> <span m=''1135830''>local</span> <span m=''1136120''>change,</span>
  <span m=''1136510''>and</span> <span m=''1136550''>now,</span> <span m=''1136800''>it
  will</span> <span m=''1136950''>be</span> <span m=''1137100''>one</span> <span m=''1137310''>big</span>
  <span m=''1137470''>cycle.</span> <span m=''1138620''>We''ve</span> <span m=''1138770''>probably</span>
  <span m=''1139060''>seen</span> <span m=''1139250''>this</span> <span m=''1139390''>trick</span>
  <span m=''1140150''>once</span> <span m=''1140340''>or</span> <span m=''1140390''>twice</span>
  <span m=''1140640''>before,</span> <span m=''1142860''>I</span> <span m=''1142920''>think</span>
  <span m=''1143200''>in</span> <span m=''1143310''>the</span> <span m=''1144030''>Mountain</span>
  <span m=''1144310''>Valley</span> <span m=''1144570''>assignment</span> <span m=''1145170''>stuff.</span>
  </p><p><span m=''1145840''>So</span> <span m=''1145960''>here</span> <span m=''1146720''>I</span>
  <span m=''1146890''>have,</span> <span m=''1147040''>for</span> <span m=''1147140''>example,</span>
  <span m=''1147620''>these</span> <span m=''1147840''>two</span> <span m=''1147970''>triangles,</span>
  <span m=''1149940''>which</span> <span m=''1150080''>are</span> <span m=''1150150''>adjacent,</span>
  <span m=''1150710''>but</span> <span m=''1150950''>the</span> <span m=''1151450''>paths</span>
  <span m=''1151830''>don''t</span> <span m=''1152030''>meet.</span> <span m=''1152760''>So
  I''m</span> <span m=''1152900''>just</span> <span m=''1153060''>going</span> <span
  m=''1153160''>to</span> <span m=''1153200''>erase</span> <span m=''1153560''>this</span>
  <span m=''1153740''>edge,</span> <span m=''1154160''>put</span> <span m=''1154320''>in</span>
  <span m=''1154430''>that</span> <span m=''1154630''>one,</span> <span m=''1155390''>erase</span>
  <span m=''1155700''>this</span> <span m=''1155910''>edge,</span> <span m=''1156240''>put</span>
  <span m=''1156390''>in</span> <span m=''1156480''>that</span> <span m=''1156660''>one.</span>
  <span m=''1157295''>Lo</span> <span m=''1157640''>and</span> <span m=''1157830''>behold,</span>
  <span m=''1158340''>I</span> <span m=''1158400''>have</span> <span m=''1158770''>a</span>
  <span m=''1158930''>bigger</span> <span m=''1159510''>cycle</span> <span m=''1159880''>now,</span>
  <span m=''1161320''>like</span> <span m=''1162240''>that.</span> </p><p><span m=''1164010''>Still</span>
  <span m=''1164260''>not</span> <span m=''1164480''>everything,</span> <span m=''1164960''>so</span>
  <span m=''1165140''>like</span> <span m=''1165320''>these</span> <span m=''1165470''>two</span>
  <span m=''1165590''>triangles</span> <span m=''1166410''>don''t</span> <span m=''1166650''>touch.</span>
  <span m=''1167510''>So</span> <span m=''1167690''>erase</span> <span m=''1167980''>that</span>
  <span m=''1168160''>edge.</span> <span m=''1168400''>Erase</span> <span m=''1168650''>that</span>
  <span m=''1168860''>edge.</span> <span m=''1169490''>Put</span> <span m=''1169650''>in</span>
  <span m=''1169740''>that</span> <span m=''1169920''>one.</span> <span m=''1170110''>Put</span>
  <span m=''1170270''>in</span> <span m=''1170370''>that</span> <span m=''1170560''>one.</span>
  </p><p><span m=''1171620''>I''m</span> <span m=''1171740''>preserving,</span> <span
  m=''1172190''>at</span> <span m=''1172250''>all</span> <span m=''1172400''>times,</span>
  <span m=''1172660''>that</span> <span m=''1172750''>I''m</span> <span m=''1172860''>a</span>
  <span m=''1172900''>facet</span> <span m=''1173270''>path,</span> <span m=''1174140''>and</span>
  <span m=''1174420''>I''m</span> <span m=''1174440''>merging</span> <span m=''1174940''>components.</span>
  <span m=''1176270''>So</span> <span m=''1176370''>by</span> <span m=''1176530''>the</span>
  <span m=''1176660''>end,</span> <span m=''1177750''>I''ll</span> <span m=''1177850''>have</span>
  <span m=''1178000''>one</span> <span m=''1178240''>big</span> <span m=''1178450''>component.</span>
  <span m=''1180780''>Now,</span> <span m=''1180910''>I</span> <span m=''1180950''>haven''t</span>
  <span m=''1181110''>necessarily</span> <span m=''1181540''>described</span> <span
  m=''1181930''>this</span> <span m=''1182090''>as</span> <span m=''1182200''>a</span>
  <span m=''1182250''>big</span> <span m=''1182400''>cycle,</span> <span m=''1182740''>but</span>
  <span m=''1182850''>as</span> <span m=''1183020''>I''ve</span> <span m=''1183160''>kind</span>
  <span m=''1183370''>of</span> <span m=''1183450''>been</span> <span m=''1183570''>hinting,</span>
  <span m=''1184280''>what</span> <span m=''1184470''>I</span> <span m=''1184540''>do</span>
  <span m=''1184680''>now</span> <span m=''1184910''>is</span> <span m=''1184990''>take</span>
  <span m=''1185180''>an</span> <span m=''1185260''>Euler</span> <span m=''1185550''>tour</span>
  <span m=''1185760''>around</span> <span m=''1186110''>this</span> <span m=''1186290''>thing.</span>
  <span m=''1186920''>We''ve</span> <span m=''1186990''>seen</span> <span m=''1187220''>Euler</span>
  <span m=''1187490''>tours.</span> </p><p><span m=''1188870''>All</span> <span m=''1189110''>the</span>
  <span m=''1189180''>vertices</span> <span m=''1189670''>in</span> <span m=''1189750''>this</span>
  <span m=''1189900''>graph</span> <span m=''1190150''>will</span> <span m=''1190250''>have</span>
  <span m=''1190410''>even</span> <span m=''1190700''>degree.</span> <span m=''1192350''>And</span>
  <span m=''1192700''>so</span> <span m=''1192900''>I</span> <span m=''1193000''>can</span>
  <span m=''1193150''>take</span> <span m=''1193310''>an</span> <span m=''1193380''>Euler</span>
  <span m=''1193660''>tour,</span> <span m=''1195380''>and</span> <span m=''1195590''>really,</span>
  <span m=''1195920''>I</span> <span m=''1195960''>should</span> <span m=''1196170''>take</span>
  <span m=''1196440''>what''s</span> <span m=''1196680''>called</span> <span m=''1196950''>a</span>
  <span m=''1196970''>non-crossing</span> <span m=''1198580''>Euler</span> <span m=''1198840''>tour.</span>
  <span m=''1201920''>Point</span> <span m=''1202040''>is</span> <span m=''1202180''>you''ve</span>
  <span m=''1202340''>got</span> <span m=''1202530''>a</span> <span m=''1202570''>bunch</span>
  <span m=''1202800''>of</span> <span m=''1202860''>cycles</span> <span m=''1203280''>that</span>
  <span m=''1203440''>touch.</span> </p><p><span m=''1203920''>You</span> <span m=''1204240''>just</span>
  <span m=''1204430''>walk</span> <span m=''1204795''>around</span> <span m=''1205160''>the</span>
  <span m=''1205290''>outside.</span> <span m=''1206540''>That</span> <span m=''1206770''>will</span>
  <span m=''1206950''>visit</span> <span m=''1207380''>all</span> <span m=''1207590''>the</span>
  <span m=''1207670''>cycles.</span> <span m=''1208750''>It''ll</span> <span m=''1208850''>visit</span>
  <span m=''1208950''>all</span> <span m=''1209130''>these</span> <span m=''1209290''>edges</span>
  <span m=''1209540''>exactly</span> <span m=''1209930''>once,</span> <span m=''1210190''>and</span>
  <span m=''1210280''>that</span> <span m=''1210440''>will</span> <span m=''1210580''>actually</span>
  <span m=''1210840''>be</span> <span m=''1211410''>a</span> <span m=''1211470''>facet-path.</span>
  <span m=''1218340''>And</span> <span m=''1218430''>we''re</span> <span m=''1218530''>done.</span>
  </p><p><span m=''1220778''>Now,</span> <span m=''1221220''>I</span> <span m=''1221390''>have</span>
  <span m=''1221570''>a</span> <span m=''1221610''>facet-path</span> <span m=''1222000''>for
  a</span> <span m=''1222460''>triangulated</span> <span m=''1222980''>cube.</span>
  <span m=''1224210''>So</span> <span m=''1224420''>I</span> <span m=''1224500''>can</span>
  <span m=''1224630''>splay</span> <span m=''1225060''>out</span> <span m=''1225210''>those</span>
  <span m=''1225380''>triangles,</span> <span m=''1226110''>get</span> <span m=''1226310''>a</span>
  <span m=''1226380''>non-overlapping</span> <span m=''1227090''>chain</span> <span
  m=''1227410''>like</span> <span m=''1227610''>this.</span> <span m=''1228940''>Actually,</span>
  <span m=''1229220''>it''s</span> <span m=''1229330''>probably</span> <span m=''1229830''>the</span>
  <span m=''1230020''>top</span> <span m=''1230340''>one,</span> <span m=''1232110''>something</span>
  <span m=''1232460''>like</span> <span m=''1232650''>that,</span> <span m=''1233910''>might</span>
  <span m=''1234120''>be.</span> <span m=''1234390''>I</span> <span m=''1234570''>may
  not</span> <span m=''1234860''>have</span> <span m=''1235010''>matched</span> <span
  m=''1235380''>exactly</span> <span m=''1235760''>what''s</span> <span m=''1235970''>in</span>
  <span m=''1236030''>the</span> <span m=''1236110''>textbook.</span> <span m=''1240360''>Cool.</span>
  </p><p><span m=''1241500''>One</span> <span m=''1241840''>slight</span> <span m=''1242120''>detail</span>
  <span m=''1242600''>is</span> <span m=''1243240''>I was</span> <span m=''1243410''>sort</span>
  <span m=''1243620''>of</span> <span m=''1243830''>waving</span> <span m=''1244150''>my</span>
  <span m=''1244250''>hands,</span> <span m=''1244480''>assuming</span> <span m=''1244870''>there</span>
  <span m=''1245030''>was</span> <span m=''1245130''>actually</span> <span m=''1245420''>a</span>
  <span m=''1245480''>cycle</span> <span m=''1245890''>here.</span> <span m=''1247430''>I</span>
  <span m=''1247550''>really</span> <span m=''1247830''>only</span> <span m=''1247990''>need</span>
  <span m=''1248110''>a</span> <span m=''1248180''>path.</span> <span m=''1248900''>In</span>
  <span m=''1248970''>fact,</span> <span m=''1249180''>there</span> <span m=''1249270''>won''t</span>
  <span m=''1249500''>always</span> <span m=''1249740''>be</span> <span m=''1249840''>a</span>
  <span m=''1249890''>cycle</span> <span m=''1250230''>because</span> <span m=''1250540''>at</span>
  <span m=''1250760''>the</span> <span m=''1250850''>very</span> <span m=''1251150''>end,</span>
  <span m=''1252270''>you''re</span> <span m=''1252380''>not</span> <span m=''1252630''>able</span>
  <span m=''1252880''>to</span> <span m=''1252960''>construct</span> <span m=''1253360''>a</span>
  <span m=''1253410''>cycle.</span> </p><p><span m=''1253930''>So</span> <span m=''1254100''>that</span>
  <span m=''1254280''>will</span> <span m=''1254420''>actually</span> <span m=''1254700''>cause</span>
  <span m=''1255060''>you</span> <span m=''1255260''>to</span> <span m=''1255420''>make--</span>
  <span m=''1256135''>if</span> <span m=''1256430''>I</span> <span m=''1256500''>do</span>
  <span m=''1256640''>something</span> <span m=''1257070''>like</span> <span m=''1258040''>this,</span>
  <span m=''1258650''>so</span> <span m=''1259290''>at least it</span> <span m=''1259690''>can</span>
  <span m=''1260040''>connect to</span> <span m=''1260380''>other</span> <span m=''1260580''>things.</span>
  <span m=''1262510''>That</span> <span m=''1262680''>will</span> <span m=''1262800''>cause</span>
  <span m=''1263020''>you</span> <span m=''1263180''>make</span> <span m=''1263400''>two</span>
  <span m=''1263700''>vertices</span> <span m=''1264190''>of</span> <span m=''1264380''>odd</span>
  <span m=''1264590''>degree.</span> <span m=''1265732''>But</span> <span m=''1266100''>that''s</span>
  <span m=''1266350''>OK</span> <span m=''1266730''>because there''s</span> <span
  m=''1266910''>still</span> <span m=''1267160''>an</span> <span m=''1267260''>Euler</span>
  <span m=''1267560''>path</span> <span m=''1268650''>that</span> <span m=''1268820''>starts</span>
  <span m=''1269250''>at</span> <span m=''1269360''>one</span> <span m=''1269500''>of</span>
  <span m=''1269540''>the</span> <span m=''1269600''>vertices</span> <span m=''1269970''>of
  odd</span> <span m=''1270140''>degree,</span> <span m=''1270850''>visits</span>
  <span m=''1271480''>all</span> <span m=''1271660''>the</span> <span m=''1271780''>other</span>
  <span m=''1271990''>edges,</span> <span m=''1272380''>and</span> <span m=''1272470''>then,</span>
  <span m=''1272600''>comes</span> <span m=''1273720''>to</span> <span m=''1273840''>the</span>
  <span m=''1273980''>other</span> <span m=''1274260''>vertex</span> <span m=''1274680''>of
  odd</span> <span m=''1274930''>degree.</span> <span m=''1275460''>And</span> <span
  m=''1275670''>I</span> <span m=''1275750''>just</span> <span m=''1275980''>need</span>
  <span m=''1276090''>a</span> <span m=''1276140''>path.</span> </p><p><span m=''1277310''>You</span>
  <span m=''1277420''>can</span> <span m=''1277520''>actually</span> <span m=''1277750''>characterize</span>
  <span m=''1278240''>when</span> <span m=''1278370''>you</span> <span m=''1278450''>get</span>
  <span m=''1278550''>a</span> <span m=''1278620''>cycle.</span> <span m=''1279050''>It''s</span>
  <span m=''1279670''>when</span> <span m=''1280650''>the</span> <span m=''1280780''>original</span>
  <span m=''1281150''>thing</span> <span m=''1281390''>is</span> <span m=''1281570''>not</span>
  <span m=''1281880''>too</span> <span m=''1282080''>colorable,</span> <span m=''1282610''>I</span>
  <span m=''1283110''>think.</span> <span m=''1284860''>Anyway,</span> <span m=''1287730''>that''s</span>
  <span m=''1287960''>vertex</span> <span m=''1288340''>unfolding.</span> <span m=''1288980''>It''s</span>
  <span m=''1289090''>kind</span> <span m=''1289260''>of</span> <span m=''1289300''>easy.</span>
  </p><p><span m=''1292470''>I</span> <span m=''1292560''>think</span> <span m=''1293560''>we
  solved</span> <span m=''1293720''>most</span> <span m=''1293985''>of</span> <span
  m=''1294250''>it</span> <span m=''1294450''>in like an</span> <span m=''1294550''>afternoon.</span>
  <span m=''1294910''>We</span> <span m=''1294980''>had</span> <span m=''1295110''>this</span>
  <span m=''1295270''>idea.</span> <span m=''1295545''>It was</span> <span m=''1295820''>cool,</span>
  <span m=''1296710''>and</span> <span m=''1296930''>then,</span> <span m=''1297960''>we</span>
  <span m=''1298170''>solved</span> <span m=''1298410''>it</span> <span m=''1298780''>kind</span>
  <span m=''1298970''>of</span> <span m=''1299060''>quickly.</span> <span m=''1299785''>That''s</span>
  <span m=''1300150''>how</span> <span m=''1300290''>it</span> <span m=''1300560''>often</span>
  <span m=''1300820''>goes.</span> <span m=''1301090''>Once</span> <span m=''1301230''>you</span>
  <span m=''1301310''>have</span> <span m=''1301570''>a</span> <span m=''1301620''>cool</span>
  <span m=''1301820''>problem,</span> <span m=''1303360''>it</span> <span m=''1303840''>falls</span>
  <span m=''1304210''>quickly.</span> </p><p><span m=''1305010''>There''s</span> <span
  m=''1305190''>lots</span> <span m=''1305380''>of</span> <span m=''1305460''>interesting</span>
  <span m=''1305900''>open</span> <span m=''1306170''>problems</span> <span m=''1306470''>remaining</span>
  <span m=''1306820''>about</span> <span m=''1307040''>vertex</span> <span m=''1307400''>unfolding,</span>
  <span m=''1307810''>and</span> <span m=''1307880''>they</span> <span m=''1308000''>seem</span>
  <span m=''1308260''>a</span> <span m=''1308310''>lot</span> <span m=''1308540''>harder.</span>
  <span m=''1309900''>So</span> <span m=''1310320''>for</span> <span m=''1310470''>example,</span>
  <span m=''1311160''>what</span> <span m=''1311240''>if</span> <span m=''1311360''>I</span>
  <span m=''1311420''>have</span> <span m=''1311630''>non-triangulated</span> <span
  m=''1312620''>polyhedra?</span> <span m=''1313920''>And</span> <span m=''1314140''>natural</span>
  <span m=''1314530''>version</span> <span m=''1314850''>is</span> <span m=''1314980''>to</span>
  <span m=''1315080''>think</span> <span m=''1315290''>about</span> <span m=''1315995''>what
  we were</span> <span m=''1316280''>originally</span> <span m=''1316710''>trying</span>
  <span m=''1316940''>to</span> <span m=''1317010''>attack,</span> <span m=''1317300''>convex</span>
  <span m=''1318020''>polyhedra.</span> <span m=''1318520''>This</span> <span m=''1318680''>turned</span>
  <span m=''1318900''>out</span> <span m=''1319010''>to</span> <span m=''1319090''>not</span>
  <span m=''1319270''>require</span> <span m=''1319610''>convexity.</span> </p><p><span
  m=''1320090''>But</span> <span m=''1320190''>what</span> <span m=''1320310''>about</span>
  <span m=''1320570''>convex</span> <span m=''1321030''>polyhedra,</span> <span m=''1321650''>not</span>
  <span m=''1321960''>triangulated?</span> <span m=''1323290''>Is</span> <span m=''1323460''>there</span>
  <span m=''1323750''>always</span> <span m=''1323860''>a</span> <span m=''1323910''>vertex</span>
  <span m=''1324490''>unfolding?</span> <span m=''1325330''>We</span> <span m=''1325450''>don''t</span>
  <span m=''1325570''>know</span> <span m=''1325650''>about</span> <span m=''1325850''>edge</span>
  <span m=''1326040''>unfoldings.</span> <span m=''1327490''>And</span> <span m=''1328710''>the</span>
  <span m=''1328810''>answer</span> <span m=''1329100''>is</span> <span m=''1329320''>no.</span>
  <span m=''1331620''>Well,</span> <span m=''1331900''>no</span> <span m=''1332260''>that''s</span>
  <span m=''1332430''>not</span> <span m=''1332580''>right.</span> <span m=''1333710''>Sorry.</span>
  <span m=''1335050''>The</span> <span m=''1335140''>answer</span> <span m=''1335330''>is</span>
  <span m=''1335410''>we</span> <span m=''1335520''>don''t</span> <span m=''1335670''>know.</span>
  </p><p><span m=''1337030''>What''s</span> <span m=''1337870''>annoying</span> <span
  m=''1338180''>about</span> <span m=''1338420''>this</span> <span m=''1338580''>example</span>
  <span m=''1338970''>is</span> <span m=''1339070''>that</span> <span m=''1339170''>there''s</span>
  <span m=''1339350''>no</span> <span m=''1339500''>facet-path.</span> <span m=''1340610''>So</span>
  <span m=''1340730''>there</span> <span m=''1340850''>are</span> <span m=''1340890''>two</span>
  <span m=''1341060''>things</span> <span m=''1341340''>that</span> <span m=''1341420''>could</span>
  <span m=''1341580''>go</span> <span m=''1341740''>wrong.</span> <span m=''1342620''>One</span>
  <span m=''1342850''>is</span> <span m=''1343000''>that</span> <span m=''1343100''>the</span>
  <span m=''1343180''>facet-path</span> <span m=''1343750''>doesn''t</span> <span
  m=''1343970''>exist,</span> <span m=''1344350''>and</span> <span m=''1344450''>that</span>
  <span m=''1344680''>can</span> <span m=''1344800''>happen</span> <span m=''1345150''>in</span>
  <span m=''1345290''>this</span> <span m=''1345530''>more</span> <span m=''1345710''>general</span>
  <span m=''1345980''>scenario.</span> <span m=''1346690''>And</span> <span m=''1346910''>the</span>
  <span m=''1347040''>other is</span> <span m=''1347370''>that</span> <span m=''1347480''>when</span>
  <span m=''1347590''>you</span> <span m=''1347700''>lay</span> <span m=''1347890''>it</span>
  <span m=''1347970''>out,</span> <span m=''1348240''>it</span> <span m=''1348320''>overlaps.</span>
  <span m=''1349400''>Both</span> <span m=''1349660''>of</span> <span m=''1349770''>these</span>
  <span m=''1350000''>things</span> <span m=''1350270''>could</span> <span m=''1350870''>go</span>
  <span m=''1351090''>wrong</span> <span m=''1351770''>in</span> <span m=''1351960''>the</span>
  <span m=''1352040''>general</span> <span m=''1352740''>convex</span> <span m=''1353200''>case.</span>
  </p><p><span m=''1353990''>So</span> <span m=''1354120''>in</span> <span m=''1354180''>this</span>
  <span m=''1354330''>example,</span> <span m=''1354990''>this is</span> <span m=''1355170''>a</span>
  <span m=''1355420''>truncated</span> <span m=''1355900''>cube.</span> <span m=''1356640''>There''s</span>
  <span m=''1356920''>eight</span> <span m=''1357650''>triangles</span> <span m=''1358380''>and</span>
  <span m=''1358520''>only</span> <span m=''1358730''>six</span> <span m=''1359790''>octagons.</span>
  <span m=''1361360''>And</span> <span m=''1361600''>if</span> <span m=''1361700''>you</span>
  <span m=''1361820''>look,</span> <span m=''1363270''>once</span> <span m=''1363500''>you''re</span>
  <span m=''1363630''>at</span> <span m=''1363690''>a</span> <span m=''1363750''>triangle,</span>
  <span m=''1364150''>you</span> <span m=''1364240''>have</span> <span m=''1364440''>to</span>
  <span m=''1364520''>go</span> <span m=''1364660''>to</span> <span m=''1364740''>an</span>
  <span m=''1364810''>octagon</span> <span m=''1365300''>because</span> <span m=''1365520''>there''s</span>
  <span m=''1365680''>no</span> <span m=''1365850''>adjacent</span> <span m=''1366230''>triangles.</span>
  </p><p><span m=''1367380''>So</span> <span m=''1367700''>at</span> <span m=''1367940''>best,</span>
  <span m=''1368300''>you</span> <span m=''1368400''>could</span> <span m=''1368540''>alternate</span>
  <span m=''1368980''>triangle-octagon-triangle-octagon</span> <span m=''1370400''>if</span>
  <span m=''1370490''>you</span> <span m=''1370580''>want</span> <span m=''1370690''>to</span>
  <span m=''1370750''>pack</span> <span m=''1371060''>all</span> <span m=''1371160''>those</span>
  <span m=''1371310''>triangles</span> <span m=''1371730''>in,</span> <span m=''1372280''>but</span>
  <span m=''1372410''>you</span> <span m=''1372560''>run</span> <span m=''1372780''>out</span>
  <span m=''1372870''>of</span> <span m=''1372970''>octagons</span> <span m=''1373680''>to</span>
  <span m=''1373790''>get</span> <span m=''1374020''>there.</span> <span m=''1374310''>So</span>
  <span m=''1374340''>there''s</span> <span m=''1374510''>no</span> <span m=''1374640''>facet-path,</span>
  <span m=''1378270''>but</span> <span m=''1378430''>maybe,</span> <span m=''1378670''>you</span>
  <span m=''1378730''>don''t</span> <span m=''1378900''>need</span> <span m=''1379310''>facet-path.</span>
  <span m=''1379630''>You</span> <span m=''1379750''>could</span> <span m=''1379880''>make</span>
  <span m=''1380030''>a</span> <span m=''1380090''>tree,</span> <span m=''1381930''>just</span>
  <span m=''1382210''>a</span> <span m=''1382280''>little</span> <span m=''1382490''>trickier.</span>
  </p><p><span m=''1383960''>Obviously,</span> <span m=''1384250''>if</span> <span
  m=''1384340''>you</span> <span m=''1384420''>triangulate</span> <span m=''1384980''>that</span>
  <span m=''1385160''>surface,</span> <span m=''1385910''>you''re</span> <span m=''1386030''>done.</span>
  <span m=''1386450''>So</span> <span m=''1386500''>the</span> <span m=''1386660''>analog</span>
  <span m=''1387210''>of</span> <span m=''1387970''>general</span> <span m=''1388380''>unfolding</span>
  <span m=''1389800''>with</span> <span m=''1390050''>vertex</span> <span m=''1390500''>unfolding</span>
  <span m=''1391030''>is</span> <span m=''1391290''>trivial.</span> <span m=''1391830''>You</span>
  <span m=''1391920''>just</span> <span m=''1392100''>triangulate,</span> <span m=''1392660''>and</span>
  <span m=''1392770''>then,</span> <span m=''1392900''>you use</span> <span m=''1393310''>the</span>
  <span m=''1393420''>edge</span> <span m=''1393770''>case.</span> <span m=''1395130''>But</span>
  <span m=''1395330''>if</span> <span m=''1395480''>you</span> <span m=''1395600''>really</span>
  <span m=''1395820''>only</span> <span m=''1395980''>want</span> <span m=''1396120''>to</span>
  <span m=''1396170''>cut</span> <span m=''1396320''>along</span> <span m=''1396590''>edges,</span>
  <span m=''1397110''>this</span> <span m=''1397380''>example</span> <span m=''1397750''>can</span>
  <span m=''1397970''>be</span> <span m=''1398080''>done.</span> <span m=''1398510''>I</span>
  <span m=''1398610''>mean it</span> <span m=''1398730''>has</span> <span m=''1398910''>an</span>
  <span m=''1399000''>edge</span> <span m=''1399170''>unfolding,</span> <span m=''1399730''>so</span>
  <span m=''1400300''>if</span> <span m=''1400530''>it</span> <span m=''1400640''>has</span>
  <span m=''1400820''>an</span> <span m=''1400900''>edge</span> <span m=''1401150''>unfolding,</span>
  <span m=''1401450''>it definitely</span> <span m=''1401820''>has a</span> <span
  m=''1401880''>vertex</span> <span m=''1402260''>unfolding,</span> <span m=''1403150''>but</span>
  <span m=''1403290''>we</span> <span m=''1403390''>don''t</span> <span m=''1403530''>know</span>
  <span m=''1403600''>how</span> <span m=''1403780''>to</span> <span m=''1403860''>prove</span>
  <span m=''1404110''>it.</span> </p><p><span m=''1405010''>The</span> <span m=''1405030''>other</span>
  <span m=''1405180''>thing</span> <span m=''1405300''>that</span> <span m=''1405400''>could</span>
  <span m=''1405550''>go</span> <span m=''1405680''>wrong</span> <span m=''1405910''>is</span>
  <span m=''1406210''>once</span> <span m=''1406400''>you</span> <span m=''1406480''>have</span>
  <span m=''1406600''>octagons,</span> <span m=''1409640''>even</span> <span m=''1409890''>if</span>
  <span m=''1410000''>you</span> <span m=''1410130''>could</span> <span m=''1410510''>find</span>
  <span m=''1410770''>a</span> <span m=''1410820''>way</span> <span m=''1411970''>to</span>
  <span m=''1412350''>lay</span> <span m=''1412580''>them</span> <span m=''1412740''>out--</span>
  <span m=''1413690''>that''s not</span> <span m=''1413950''>a very good</span> <span
  m=''1414230''>octagon--</span> <span m=''1416420''>you</span> <span m=''1416590''>can''t--</span>
  <span m=''1417080''>let''s</span> <span m=''1417280''>say</span> <span m=''1417630''>if</span>
  <span m=''1417810''>your</span> <span m=''1418010''>two</span> <span m=''1418210''>hinges</span>
  <span m=''1418640''>were</span> <span m=''1418780''>here</span> <span m=''1419110''>and</span>
  <span m=''1419190''>here,</span> <span m=''1419650''>if that''s</span> <span m=''1419840''>where</span>
  <span m=''1419960''>you</span> <span m=''1420070''>attach</span> <span m=''1420500''>two</span>
  <span m=''1420590''>adjacent</span> <span m=''1420970''>pieces,</span> <span m=''1422110''>you</span>
  <span m=''1422270''>can''t</span> <span m=''1422520''>fit</span> <span m=''1422770''>that</span>
  <span m=''1422970''>in</span> <span m=''1423100''>a</span> <span m=''1423140''>vertical</span>
  <span m=''1423500''>strip.</span> <span m=''1424250''>There''s</span> <span m=''1424440''>no</span>
  <span m=''1424580''>way</span> <span m=''1424690''>to</span> <span m=''1424840''>turn</span>
  <span m=''1425100''>it</span> <span m=''1425250''>so</span> <span m=''1425360''>it</span>
  <span m=''1425470''>fits</span> <span m=''1425620''>in</span> <span m=''1425700''>a</span>
  <span m=''1425730''>vertical</span> <span m=''1426070''>strip.</span> <span m=''1426450''>So</span>
  <span m=''1426610''>also</span> <span m=''1426890''>this</span> <span m=''1427050''>layout</span>
  <span m=''1427370''>problem</span> <span m=''1428870''>doesn''t</span> <span m=''1429180''>work</span>
  <span m=''1429510''>if</span> <span m=''1430190''>you</span> <span m=''1430250''>have</span>
  <span m=''1430330''>something</span> <span m=''1430640''>more</span> <span m=''1430840''>than</span>
  <span m=''1430980''>triangles.</span> <span m=''1432330''>So</span> <span m=''1432490''>some</span>
  <span m=''1432650''>pretty</span> <span m=''1432860''>fascinating</span> <span m=''1433310''>questions.</span>
  </p><p><span m=''1433585''>It''s</span> <span m=''1433860''>even</span> <span m=''1434170''>open</span>
  <span m=''1436130''>for</span> <span m=''1436370''>non-convex.</span> <span m=''1437210''>If</span>
  <span m=''1437330''>I</span> <span m=''1437380''>take</span> <span m=''1437590''>non-convex</span>
  <span m=''1438250''>polyhedra,</span> <span m=''1440070''>and</span> <span m=''1441450''>I</span>
  <span m=''1441550''>want</span> <span m=''1441720''>a</span> <span m=''1441760''>vertex</span>
  <span m=''1442220''>unfolding--</span> <span m=''1443460''>let''s</span> <span m=''1443620''>say</span>
  <span m=''1443800''>all the</span> <span m=''1443880''>faces</span> <span m=''1444260''>are</span>
  <span m=''1445110''>convex.</span> <span m=''1446400''>At</span> <span m=''1446540''>the</span>
  <span m=''1446620''>very</span> <span m=''1446860''>least,</span> <span m=''1447140''>you</span>
  <span m=''1447210''>need</span> <span m=''1447380''>to</span> <span m=''1447460''>forbid</span>
  <span m=''1448890''>faces</span> <span m=''1449210''>having</span> <span m=''1449450''>holes.</span>
  <span m=''1450635''>If you</span> <span m=''1451030''>remember</span> <span m=''1452190''>this</span>
  <span m=''1452380''>example,</span> <span m=''1456030''>the</span> <span m=''1456100''>box</span>
  <span m=''1456440''>on</span> <span m=''1456550''>a</span> <span m=''1456590''>box,</span>
  <span m=''1457480''>this</span> <span m=''1457660''>also</span> <span m=''1457900''>doesn''t</span>
  <span m=''1458150''>have</span> <span m=''1458320''>a</span> <span m=''1458360''>vertex</span>
  <span m=''1458800''>unfolding</span> <span m=''1459720''>because</span> <span m=''1460220''>still,</span>
  <span m=''1460560''>this</span> <span m=''1460770''>guy</span> <span m=''1460920''>has</span>
  <span m=''1461120''>to</span> <span m=''1461260''>fit</span> <span m=''1461430''>in</span>
  <span m=''1461600''>that</span> <span m=''1461810''>little</span> <span m=''1462610''>square</span>
  <span m=''1462920''>hole.</span> </p><p><span m=''1465840''>But</span> <span m=''1466360''>as</span>
  <span m=''1466580''>long</span> <span m=''1466790''>as</span> <span m=''1466880''>the</span>
  <span m=''1466960''>faces</span> <span m=''1467280''>don''t</span> <span m=''1467460''>have</span>
  <span m=''1467640''>holes--</span> <span m=''1467930''>let''s</span> <span m=''1468000''>say
  the</span> <span m=''1468220''>faces</span> <span m=''1468550''>are</span> <span
  m=''1468630''>convex--</span> <span m=''1468925''>would</span> <span m=''1469220''>be</span>
  <span m=''1469330''>a</span> <span m=''1469370''>nice</span> <span m=''1469720''>version,</span>
  <span m=''1471310''>like</span> <span m=''1471660''>the</span> <span m=''1474030''>Witch''s</span>
  <span m=''1474310''>Hat,</span> <span m=''1474550''>the</span> <span m=''1474640''>spiked</span>
  <span m=''1474900''>tetrahedron.</span> <span m=''1476550''>That</span> <span m=''1476770''>probably</span>
  <span m=''1477110''>has</span> <span m=''1477320''>a</span> <span m=''1477380''>vertex</span>
  <span m=''1477770''>unfolding.</span> </p><p><span m=''1478280''>AUDIENCE: If you</span>
  <span m=''1478761''>triangulate that,</span> <span m=''1479242''>[INAUDIBLE].</span>
  </p><p><span m=''1481166''>PROFESSOR: If</span> <span m=''1481650''>you</span> <span
  m=''1481730''>triangulate</span> <span m=''1482150''>this,</span> <span m=''1482360''>it''ll</span>
  <span m=''1482590''>definitely</span> <span m=''1482830''>have</span> <span m=''1483110''>a--</span>
  <span m=''1483460''>if you</span> <span m=''1483690''>triangulate</span> <span m=''1484030''>anything,</span>
  <span m=''1484490''>it''ll</span> <span m=''1484670''>have</span> <span m=''1484790''>a</span>
  <span m=''1484840''>vertex</span> <span m=''1485200''>unfolding.</span> <span m=''1485495''>Yeah.</span>
  <span m=''1487462''>All right.</span> <span m=''1487880''>That''s</span> <span m=''1488230''>all</span>
  <span m=''1488390''>I</span> <span m=''1488440''>want</span> <span m=''1488570''>to</span>
  <span m=''1488630''>say</span> <span m=''1488740''>about</span> <span m=''1488960''>vertex</span>
  <span m=''1489320''>unfolding,</span> <span m=''1490110''>and</span> <span m=''1490300''>that''s</span>
  <span m=''1490460''>sort</span> <span m=''1490680''>of</span> <span m=''1490760''>addressing</span>
  <span m=''1492030''>edge</span> <span m=''1492220''>unfolding</span> <span m=''1492600''>of</span>
  <span m=''1492680''>convex</span> <span m=''1493060''>polyhedra,</span> <span m=''1493530''>or</span>
  <span m=''1493700''>actually,</span> <span m=''1494030''>both</span> <span m=''1494240''>of</span>
  <span m=''1494330''>these.</span> </p><p><span m=''1497060''>Now,</span> <span m=''1497230''>I''d</span>
  <span m=''1497360''>like</span> <span m=''1497490''>to</span> <span m=''1497580''>go</span>
  <span m=''1497720''>to</span> <span m=''1497800''>sort</span> <span m=''1498290''>of</span>
  <span m=''1498500''>the</span> <span m=''1498630''>real</span> <span m=''1498910''>problem.</span>
  <span m=''1499650''>This</span> <span m=''1499830''>is</span> <span m=''1499960''>one</span>
  <span m=''1500100''>of</span> <span m=''1500160''>my</span> <span m=''1500290''>favorite</span>
  <span m=''1500580''>problems,</span> <span m=''1500940''>I</span> <span m=''1501000''>think.</span>
  <span m=''1501360''>A</span> <span m=''1501790''>bunch</span> <span m=''1502190''>of</span>
  <span m=''1502240''>us</span> <span m=''1502380''>posed</span> <span m=''1502645''>it</span>
  <span m=''1502910''>in</span> <span m=''1503040''>''98,</span> <span m=''1503680''>which
  was</span> <span m=''1503990''>right</span> <span m=''1504120''>when</span> <span
  m=''1504250''>I was--</span> <span m=''1504520''>or</span> <span m=''1504790''>''99,</span>
  <span m=''1506090''>right when</span> <span m=''1506170''>I was</span> <span m=''1506260''>starting</span>
  <span m=''1506590''>out.</span> </p><p><span m=''1508220''>See,</span> <span m=''1508520''>it''s</span>
  <span m=''1509090''>tantalizing,</span> <span m=''1509870''>in</span> <span m=''1509920''>some</span>
  <span m=''1510170''>ways</span> <span m=''1510360''>more</span> <span m=''1510550''>natural,</span>
  <span m=''1511020''>because</span> <span m=''1511700''>it''s</span> <span m=''1511840''>nice</span>
  <span m=''1512090''>to</span> <span m=''1512300''>allow</span> <span m=''1512600''>cuts</span>
  <span m=''1512830''>anywhere.</span> <span m=''1513600''>And</span> <span m=''1513940''>it</span>
  <span m=''1514030''>could</span> <span m=''1514290''>potentially</span> <span m=''1514690''>work</span>
  <span m=''1514850''>for</span> <span m=''1514990''>everything.</span> <span m=''1515440''>I</span>
  <span m=''1515740''>conjecture</span> <span m=''1516640''>every</span> <span m=''1517300''>non-convex</span>
  <span m=''1518110''>polyhedron</span> <span m=''1518650''>without</span> <span m=''1518960''>boundary</span>
  <span m=''1519850''>can</span> <span m=''1520120''>be</span> <span m=''1520320''>generally</span>
  <span m=''1520730''>unfolded,</span> <span m=''1521900''>and</span> <span m=''1522090''>there''s</span>
  <span m=''1522220''>some</span> <span m=''1522430''>really</span> <span m=''1522670''>good</span>
  <span m=''1522810''>evidence</span> <span m=''1523180''>for</span> <span m=''1523270''>this</span>
  <span m=''1523600''>as</span> <span m=''1523840''>of</span> <span m=''1524270''>a</span>
  <span m=''1524560''>couple</span> <span m=''1524810''>years</span> <span m=''1525060''>ago.</span>
  </p><p><span m=''1526220''>That''s</span> <span m=''1526440''>what</span> <span
  m=''1526550''>I</span> <span m=''1526580''>want</span> <span m=''1526810''>to</span>
  <span m=''1527000''>talk</span> <span m=''1527280''>about,</span> <span m=''1550720''>which</span>
  <span m=''1550850''>is</span> <span m=''1551190''>orthogonal</span> <span m=''1551720''>polyhedra.</span>
  <span m=''1558810''>This</span> <span m=''1559020''>is</span> <span m=''1559120''>one</span>
  <span m=''1559280''>of</span> <span m=''1559340''>my</span> <span m=''1559470''>favorite</span>
  <span m=''1560210''>unfolding</span> <span m=''1560640''>results.</span> <span m=''1562120''>It''s</span>
  <span m=''1562390''>by</span> <span m=''1563900''>Mirela</span> <span m=''1564220''>Damian,</span>
  <span m=''1564670''>Robin</span> <span m=''1565000''>Flatland,</span> <span m=''1565540''>and</span>
  <span m=''1565730''>Joe</span> <span m=''1565970''>O''Rourke.</span> <span m=''1568830''>They''ve</span>
  <span m=''1568990''>done</span> <span m=''1569140''>a</span> <span m=''1569190''>lot</span>
  <span m=''1569470''>of</span> <span m=''1569530''>work</span> <span m=''1569720''>in</span>
  <span m=''1569820''>this</span> <span m=''1570050''>unfolding</span> <span m=''1570840''>area.</span>
  </p><p><span m=''1571530''>An</span> <span m=''1571820''>orthogonal</span> <span
  m=''1572440''>polyhedron</span> <span m=''1572950''>is</span> <span m=''1573020''>one</span>
  <span m=''1573200''>where</span> <span m=''1573350''>all</span> <span m=''1573510''>the</span>
  <span m=''1573580''>faces</span> <span m=''1574090''>are</span> <span m=''1574880''>perpendicular</span>
  <span m=''1575540''>to</span> <span m=''1575660''>one</span> <span m=''1575830''>of</span>
  <span m=''1575890''>the</span> <span m=''1575990''>three</span> <span m=''1576180''>coordinate</span>
  <span m=''1576520''>axes.</span> <span m=''1577640''>So</span> <span m=''1577760''>for</span>
  <span m=''1577960''>example,</span> <span m=''1578920''>here</span> <span m=''1579230''>is</span>
  <span m=''1579410''>a</span> <span m=''1580090''>orthogonal</span> <span m=''1580640''>polyhedron</span>
  <span m=''1581160''>I</span> <span m=''1581220''>drew</span> <span m=''1581410''>this</span>
  <span m=''1581590''>morning.</span> <span m=''1582726''>If</span> <span m=''1583110''>you</span>
  <span m=''1583150''>want to</span> <span m=''1583250''>draw</span> <span m=''1583390''>orthogonal</span>
  <span m=''1583900''>polyhedra,</span> <span m=''1584470''>Google</span> <span m=''1584750''>SketchUp</span>
  <span m=''1585960''>makes</span> <span m=''1586160''>it</span> <span m=''1586230''>really</span>
  <span m=''1586490''>easy,</span> <span m=''1586880''>and you can</span> <span m=''1586940''>add</span>
  <span m=''1587160''>shadows</span> <span m=''1587920''>and</span> <span m=''1588100''>texture.</span>
  </p><p><span m=''1590900''>So</span> <span m=''1591620''>there</span> <span m=''1591730''>are</span>
  <span m=''1591780''>three</span> <span m=''1592040''>kinds</span> <span m=''1592330''>of</span>
  <span m=''1592430''>faces.</span> <span m=''1592970''>There''s</span> <span m=''1593170''>the</span>
  <span m=''1593270''>ones</span> <span m=''1593570''>perpendicular</span> <span m=''1594150''>to</span>
  <span m=''1594240''>x,</span> <span m=''1595850''>like</span> <span m=''1596040''>these</span>
  <span m=''1596270''>guys.</span> <span m=''1597230''>There''s</span> <span m=''1597430''>the</span>
  <span m=''1597540''>ones</span> <span m=''1597840''>perpendicular</span> <span m=''1598620''>to</span>
  <span m=''1598990''>y.</span> <span m=''1600470''>That''s</span> <span m=''1600780''>all</span>
  <span m=''1600980''>the</span> <span m=''1601080''>yellow</span> <span m=''1601420''>faces.</span>
  <span m=''1602720''>And</span> <span m=''1602840''>there''s</span> <span m=''1602970''>the</span>
  <span m=''1603050''>ones</span> <span m=''1603280''>perpendicular</span> <span m=''1603800''>to</span>
  <span m=''1603860''>z.</span> <span m=''1604160''>That''s</span> <span m=''1604440''>these</span>
  <span m=''1604660''>top</span> <span m=''1605620''>guys.</span> <span m=''1605870''>So</span>
  <span m=''1606010''>we</span> <span m=''1606090''>call</span> <span m=''1606250''>them</span>
  <span m=''1606390''>x-faces,</span> <span m=''1606990''>y-faces,</span> <span m=''1607580''>z-faces.</span>
  </p><p><span m=''1611480''>What</span> <span m=''1611740''>we''re</span> <span m=''1611880''>going</span>
  <span m=''1612010''>to</span> <span m=''1612330''>do--</span> <span m=''1613030''>so</span>
  <span m=''1613170''>the</span> <span m=''1613290''>theorem</span> <span m=''1613590''>is</span>
  <span m=''1613780''>these</span> <span m=''1614060''>have</span> <span m=''1614280''>general</span>
  <span m=''1614580''>unfoldings.</span> <span m=''1616540''>That''s</span> <span
  m=''1616750''>pretty</span> <span m=''1616970''>awesome</span> <span m=''1618100''>because</span>
  <span m=''1618880''>every</span> <span m=''1619200''>polyhedron</span> <span m=''1619520''>is</span>
  <span m=''1619640''>approximately</span> <span m=''1620330''>orthogonal</span> <span
  m=''1621020''>if</span> <span m=''1621950''>you</span> <span m=''1622130''>can</span>
  <span m=''1622540''>voxelize</span> <span m=''1623170''>it.</span> <span m=''1623780''>So</span>
  <span m=''1623990''>this</span> <span m=''1624130''>is</span> <span m=''1624270''>really</span>
  <span m=''1624550''>a</span> <span m=''1624620''>lot</span> <span m=''1624880''>of</span>
  <span m=''1624990''>stuff.</span> <span m=''1625640''>I</span> <span m=''1625720''>would</span>
  <span m=''1625870''>love</span> <span m=''1626110''>to</span> <span m=''1626200''>generalize</span>
  <span m=''1626590''>this</span> <span m=''1626740''>approach</span> <span m=''1627060''>arbitrary</span>
  <span m=''1627510''>polyhedra,</span> <span m=''1628010''>but</span> <span m=''1628090''>that''s</span>
  <span m=''1629000''>the</span> <span m=''1629070''>big</span> <span m=''1629260''>open</span>
  <span m=''1629480''>question.</span> </p><p><span m=''1631900''>So</span> <span
  m=''1632790''>what</span> <span m=''1632990''>do</span> <span m=''1633060''>we</span>
  <span m=''1633180''>do?</span> <span m=''1633380''>Well, we''re</span> <span m=''1633650''>going</span>
  <span m=''1633780''>to</span> <span m=''1633860''>single</span> <span m=''1634270''>out,</span>
  <span m=''1634880''>from</span> <span m=''1635170''>this</span> <span m=''1635330''>color</span>
  <span m=''1635560''>coding,</span> <span m=''1636270''>the</span> <span m=''1636770''>y-faces.</span>
  <span m=''1638430''>Just color</span> <span m=''1638790''>them</span> <span m=''1638930''>yellow.</span>
  <span m=''1640290''>Then,</span> <span m=''1640500''>there''s</span> <span m=''1640980''>all</span>
  <span m=''1641170''>the</span> <span m=''1641290''>other</span> <span m=''1641430''>faces.</span>
  <span m=''1641740''>Well,</span> <span m=''1642050''>they</span> <span m=''1642420''>form</span>
  <span m=''1643410''>bands.</span> <span m=''1645090''>They''re</span> <span m=''1645230''>cycles.</span>
  <span m=''1646470''>They</span> <span m=''1646620''>go</span> <span m=''1646900''>around</span>
  <span m=''1647460''>in</span> <span m=''1647550''>a</span> <span m=''1647956''>loop.</span>
  <span m=''1649174''>A</span> <span m=''1649580''>lot</span> <span m=''1649800''>of</span>
  <span m=''1649860''>them</span> <span m=''1650220''>here,</span> <span m=''1650610''>I''ve</span>
  <span m=''1650720''>just</span> <span m=''1650900''>drawn</span> <span m=''1651110''>as</span>
  <span m=''1651760''>rectangular</span> <span m=''1652300''>loops,</span> <span m=''1652820''>but</span>
  <span m=''1652940''>in</span> <span m=''1653030''>general,</span> <span m=''1653380''>all</span>
  <span m=''1653550''>those</span> <span m=''1653810''>wooden</span> <span m=''1654270''>faces,</span>
  <span m=''1655290''>the</span> <span m=''1655400''>x</span> <span m=''1655630''>and</span>
  <span m=''1655770''>z-faces,</span> <span m=''1656280''>will</span> <span m=''1656420''>form</span>
  <span m=''1656750''>a</span> <span m=''1657080''>bunch</span> <span m=''1657350''>of</span>
  <span m=''1657430''>loops.</span> <span m=''1659290''>And</span> <span m=''1659410''>then,</span>
  <span m=''1659530''>there''s</span> <span m=''1660290''>the</span> <span m=''1660380''>y-faces</span>
  <span m=''1660950''>which</span> <span m=''1661120''>we''re</span> <span m=''1661190''>going</span>
  <span m=''1661280''>to have to</span> <span m=''1661450''>deal</span> <span m=''1661650''>with,</span>
  <span m=''1661840''>but</span> <span m=''1662030''>sort</span> <span m=''1662170''>of</span>
  <span m=''1662260''>ignore</span> <span m=''1662490''>them</span> <span m=''1662650''>for</span>
  <span m=''1662770''>a</span> <span m=''1662870''>while.</span> <span m=''1664386''>I</span>
  <span m=''1664880''>should</span> <span m=''1665040''>have</span> <span m=''1665110''>drawn</span>
  <span m=''1665330''>it</span> <span m=''1665390''>with</span> <span m=''1665530''>them</span>
  <span m=''1665650''>erased.</span> <span m=''1666040''>It would look</span> <span
  m=''1666270''>cool.</span> </p><p><span m=''1667230''>But</span> <span m=''1667470''>if</span>
  <span m=''1667900''>you</span> <span m=''1668020''>think</span> <span m=''1668220''>about</span>
  <span m=''1668530''>just</span> <span m=''1668810''>those</span> <span m=''1669090''>bands,</span>
  <span m=''1670250''>this</span> <span m=''1670440''>is</span> <span m=''1670540''>sort</span>
  <span m=''1670730''>of</span> <span m=''1670810''>how</span> <span m=''1670980''>they''re</span>
  <span m=''1671110''>connected</span> <span m=''1671520''>together,</span> <span
  m=''1672320''>this</span> <span m=''1672500''>tree.</span> <span m=''1673270''>There''s</span>
  <span m=''1673430''>a</span> <span m=''1673490''>big</span> <span m=''1673710''>one</span>
  <span m=''1673890''>out</span> <span m=''1674020''>here,</span> <span m=''1675950''>and</span>
  <span m=''1676160''>then,</span> <span m=''1676300''>it</span> <span m=''1676350''>has</span>
  <span m=''1676630''>two</span> <span m=''1676800''>children.</span> <span m=''1677270''>There''s</span>
  <span m=''1677430''>this</span> <span m=''1677630''>one</span> <span m=''1678290''>and</span>
  <span m=''1678520''>this</span> <span m=''1678700''>one.</span> <span m=''1679405''>And</span>
  <span m=''1679810''>then,</span> <span m=''1680010''>this</span> <span m=''1680160''>child</span>
  <span m=''1680460''>has</span> <span m=''1680630''>one</span> <span m=''1680890''>child</span>
  <span m=''1681220''>hanging</span> <span m=''1681520''>off</span> <span m=''1681670''>of</span>
  <span m=''1681770''>it,</span> <span m=''1682450''>and</span> <span m=''1682720''>this</span>
  <span m=''1682880''>one</span> <span m=''1683030''>has</span> <span m=''1683350''>two</span>
  <span m=''1683510''>children</span> <span m=''1684310''>hanging</span> <span m=''1684690''>off</span>
  <span m=''1684810''>of</span> <span m=''1684920''>it.</span> <span m=''1685120''>So</span>
  <span m=''1685300''>that''s</span> <span m=''1686040''>these</span> <span m=''1686280''>two</span>
  <span m=''1687270''>guys.</span> </p><p><span m=''1688810''>In</span> <span m=''1688990''>general,</span>
  <span m=''1690130''>this</span> <span m=''1690430''>guy</span> <span m=''1690530''>might</span>
  <span m=''1690740''>have</span> <span m=''1690940''>some</span> <span m=''1691310''>children</span>
  <span m=''1691640''>hanging</span> <span m=''1691940''>off</span> <span m=''1692080''>the</span>
  <span m=''1692150''>back</span> <span m=''1692410''>side</span> <span m=''1692620''>as</span>
  <span m=''1692720''>well.</span> <span m=''1692930''>I''m</span> <span m=''1693050''>not</span>
  <span m=''1693300''>going</span> <span m=''1693420''>to</span> <span m=''1693500''>try</span>
  <span m=''1693660''>to</span> <span m=''1693750''>represent</span> <span m=''1694200''>that</span>
  <span m=''1694360''>in</span> <span m=''1694430''>this</span> <span m=''1694580''>picture.</span>
  <span m=''1694880''>There''s</span> <span m=''1695070''>just</span> <span m=''1695320''>a</span>
  <span m=''1695730''>bunch</span> <span m=''1695950''>of</span> <span m=''1696020''>children.</span>
  <span m=''1696350''>There will</span> <span m=''1696480''>be</span> <span m=''1696600''>some</span>
  <span m=''1696810''>front</span> <span m=''1697050''>children and</span> <span m=''1697450''>some</span>
  <span m=''1697610''>back</span> <span m=''1697840''>children.</span> <span m=''1699150''>You</span>
  <span m=''1699320''>pick</span> <span m=''1699510''>some</span> <span m=''1699710''>root</span>
  <span m=''1699950''>arbitrarily,</span> <span m=''1700570''>and</span> <span m=''1700670''>then,</span>
  <span m=''1700760''>you</span> <span m=''1700850''>have</span> <span m=''1701060''>children</span>
  <span m=''1701520''>going</span> <span m=''1701750''>off</span> <span m=''1701890''>of</span>
  <span m=''1701970''>there.</span> </p><p><span m=''1702370''>Now,</span> <span m=''1703610''>if</span>
  <span m=''1703720''>you''re</span> <span m=''1703820''>orthogonal</span> <span m=''1704250''>polyhedron</span>
  <span m=''1704740''>has</span> <span m=''1705030''>genus</span> <span m=''1705370''>0--</span>
  <span m=''1706040''>it''s</span> <span m=''1706290''>topologically</span> <span
  m=''1706580''>a</span> <span m=''1707010''>sphere--</span> <span m=''1707840''>this</span>
  <span m=''1708030''>will</span> <span m=''1708150''>be</span> <span m=''1708290''>a</span>
  <span m=''1708340''>tree.</span> <span m=''1709100''>If</span> <span m=''1709330''>it''s</span>
  <span m=''1709590''>like</span> <span m=''1709760''>a</span> <span m=''1709810''>doughnut,</span>
  <span m=''1710500''>it</span> <span m=''1710650''>will</span> <span m=''1711000''>have</span>
  <span m=''1711180''>a</span> <span m=''1711240''>cycle.</span> <span m=''1712730''>So</span>
  <span m=''1712920''>this</span> <span m=''1713150''>theorem</span> <span m=''1713410''>only</span>
  <span m=''1713660''>applies</span> <span m=''1714100''>for</span> <span m=''1714440''>our</span>
  <span m=''1714700''>genius</span> <span m=''1715020''>zero.</span> <span m=''1719380''>So</span>
  <span m=''1719760''>we''re</span> <span m=''1719880''>going</span> <span m=''1720000''>to</span>
  <span m=''1720040''>exploit</span> <span m=''1721015''>that</span> <span m=''1721420''>that</span>
  <span m=''1723000''>dual</span> <span m=''1723460''>drawing,</span> <span m=''1724150''>how</span>
  <span m=''1724370''>the</span> <span m=''1724670''>bands</span> <span m=''1725080''>are</span>
  <span m=''1725160''>connected</span> <span m=''1725560''>together,</span> <span
  m=''1726000''>is</span> <span m=''1726130''>like</span> <span m=''1726310''>a</span>
  <span m=''1726360''>tree.</span> <span m=''1727540''>So</span> <span m=''1727740''>why
  don''t</span> <span m=''1727910''>I</span> <span m=''1728990''>write</span> <span
  m=''1729250''>down,</span> <span m=''1731070''>a</span> <span m=''1731130''>band</span>
  <span m=''1732960''>is</span> <span m=''1733830''>a</span> <span m=''1733900''>cycle</span>
  <span m=''1736170''>of</span> <span m=''1737030''>x</span> <span m=''1737720''>and</span>
  <span m=''1739390''>z-faces,</span> <span m=''1743990''>and</span> <span m=''1744480''>they</span>
  <span m=''1744780''>are</span> <span m=''1745640''>connected</span> <span m=''1746080''>together</span>
  <span m=''1749640''>in</span> <span m=''1749960''>a</span> <span m=''1750030''>tree.</span>
  </p><p><span m=''1752610''>Now,</span> <span m=''1752750''>the</span> <span m=''1752880''>rough</span>
  <span m=''1753140''>idea</span> <span m=''1754120''>is</span> <span m=''1754360''>we''re</span>
  <span m=''1754440''>going</span> <span m=''1754550''>to</span> <span m=''1754630''>take</span>
  <span m=''1754850''>a</span> <span m=''1754930''>depth-first</span> <span m=''1755700''>traversal</span>
  <span m=''1756280''>of</span> <span m=''1756410''>this</span> <span m=''1756620''>tree.</span>
  <span m=''1757180''>We''re going</span> <span m=''1757290''>to</span> <span m=''1757360''>start</span>
  <span m=''1757700''>at</span> <span m=''1757810''>the</span> <span m=''1757920''>root,</span>
  <span m=''1758790''>work</span> <span m=''1759110''>our</span> <span m=''1759220''>way</span>
  <span m=''1759430''>down</span> <span m=''1759920''>and</span> <span m=''1759990''>come</span>
  <span m=''1760170''>back,</span> <span m=''1760760''>work</span> <span m=''1760960''>our</span>
  <span m=''1761030''>way</span> <span m=''1761210''>down,</span> <span m=''1761720''>and</span>
  <span m=''1761940''>something</span> <span m=''1762260''>like</span> <span m=''1762430''>that.</span>
  <span m=''1763710''>It''s</span> <span m=''1763830''>not</span> <span m=''1764010''>going</span>
  <span m=''1764120''>to</span> <span m=''1764200''>be</span> <span m=''1764370''>quite</span>
  <span m=''1764690''>so</span> <span m=''1764880''>simple.</span> </p><p><span m=''1768710''>The</span>
  <span m=''1768860''>challenge,</span> <span m=''1769690''>I</span> <span m=''1769740''>guess</span>
  <span m=''1769970''>you</span> <span m=''1770090''>could</span> <span m=''1770250''>say,</span>
  <span m=''1770500''>is</span> <span m=''1771010''>avoiding</span> <span m=''1771340''>overlap.</span>
  <span m=''1772210''>OK?</span> <span m=''1772410''>If</span> <span m=''1772530''>you</span>
  <span m=''1772660''>wanted to</span> <span m=''1772950''>unfold a</span> <span m=''1773370''>band,</span>
  <span m=''1773710''>obviously,</span> <span m=''1773860''>a</span> <span m=''1774090''>band</span>
  <span m=''1774370''>can</span> <span m=''1775120''>just</span> <span m=''1775280''>unfold</span>
  <span m=''1775610''>straight.</span> <span m=''1776010''>It''s</span> <span m=''1776180''>like</span>
  <span m=''1776360''>a</span> <span m=''1776470''>nice,</span> <span m=''1776850''>long</span>
  <span m=''1777070''>strip.</span> <span m=''1778630''>So</span> <span m=''1778850''>each</span>
  <span m=''1779020''>band,</span> <span m=''1779240''>individually,</span> <span
  m=''1779710''>is</span> <span m=''1779850''>fine.</span> <span m=''1780220''>It''s</span>
  <span m=''1780320''>how</span> <span m=''1780490''>do</span> <span m=''1780560''>you</span>
  <span m=''1780670''>piece</span> <span m=''1781100''>those bands</span> <span m=''1781330''>together</span>
  <span m=''1781790''>and</span> <span m=''1781850''>then,</span> <span m=''1782050''>have</span>
  <span m=''1782280''>room</span> <span m=''1782650''>for</span> <span m=''1782850''>the</span>
  <span m=''1783350''>yellow</span> <span m=''1783640''>faces</span> <span m=''1784650''>to</span>
  <span m=''1784780''>attach</span> <span m=''1785100''>on</span> <span m=''1785200''>the</span>
  <span m=''1785270''>sides,</span> <span m=''1787060''>no</span> <span m=''1787240''>overlap?</span>
  </p><p><span m=''1789366''>But</span> <span m=''1789820''>it</span> <span m=''1790020''>can</span>
  <span m=''1790160''>be</span> <span m=''1790250''>done</span> <span m=''1791620''>with</span>
  <span m=''1791770''>the</span> <span m=''1792100''>awesome,</span> <span m=''1792530''>crazy</span>
  <span m=''1792910''>idea</span> <span m=''1793690''>that we''ll</span> <span m=''1794250''>get</span>
  <span m=''1794420''>to</span> <span m=''1794550''>shortly.</span> <span m=''1797620''>It''s</span>
  <span m=''1797730''>going</span> <span m=''1797830''>to</span> <span m=''1797900''>start</span>
  <span m=''1798170''>out</span> <span m=''1798360''>kind</span> <span m=''1798550''>of</span>
  <span m=''1798670''>innocent,</span> <span m=''1799160''>but</span> <span m=''1803110''>the</span>
  <span m=''1803220''>general</span> <span m=''1803610''>approach</span> <span m=''1809440''>is</span>
  <span m=''1810100''>always</span> <span m=''1811450''>proceed</span> <span m=''1812060''>rightward</span>
  <span m=''1818130''>in</span> <span m=''1818250''>the</span> <span m=''1818370''>unfolding.</span>
  <span m=''1821870''>So</span> <span m=''1824340''>the</span> <span m=''1824510''>unfolding</span>
  <span m=''1824890''>will</span> <span m=''1825420''>look</span> <span m=''1825610''>something</span>
  <span m=''1825990''>like</span> <span m=''1827200''>this.</span> <span m=''1836910''>OK,</span>
  <span m=''1837390''>whatever.</span> <span m=''1838720''>Always</span> <span m=''1839100''>going</span>
  <span m=''1839350''>to</span> <span m=''1839450''>the</span> <span m=''1839530''>right.</span>
  <span m=''1839670''>We</span> <span m=''1839750''>start</span> <span m=''1840010''>here,</span>
  <span m=''1840880''>and</span> <span m=''1841390''>we</span> <span m=''1841480''>might</span>
  <span m=''1841670''>go</span> <span m=''1841790''>up</span> <span m=''1841930''>and</span>
  <span m=''1842040''>down,</span> <span m=''1842540''>but</span> <span m=''1842670''>we</span>
  <span m=''1842760''>never</span> <span m=''1843010''>go</span> <span m=''1843130''>left.</span>
  </p><p><span m=''1846080''>And</span> <span m=''1846260''>then,</span> <span m=''1846810''>that''s</span>
  <span m=''1847070''>going</span> <span m=''1847190''>to</span> <span m=''1847260''>be</span>
  <span m=''1847490''>all</span> <span m=''1847660''>the</span> <span m=''1847730''>band</span>
  <span m=''1848080''>faces.</span> <span m=''1849100''>All</span> <span m=''1849300''>the</span>
  <span m=''1849380''>band</span> <span m=''1849660''>stuff</span> <span m=''1850330''>will</span>
  <span m=''1850490''>be</span> <span m=''1850620''>connected</span> <span m=''1850970''>like</span>
  <span m=''1851130''>that,</span> <span m=''1851620''>and</span> <span m=''1851760''>then,</span>
  <span m=''1851890''>there''s</span> <span m=''1851990''>going</span> <span m=''1852100''>to</span>
  <span m=''1852160''>be</span> <span m=''1852320''>yellow</span> <span m=''1852470''>faces</span>
  <span m=''1852960''>that</span> <span m=''1853060''>can</span> <span m=''1853230''>just</span>
  <span m=''1853410''>hang</span> <span m=''1853570''>off</span> <span m=''1853700''>the</span>
  <span m=''1853790''>sides.</span> <span m=''1856820''>So</span> <span m=''1857010''>these</span>
  <span m=''1857300''>are</span> <span m=''1857400''>the</span> <span m=''1857670''>y-faces.</span>
  <span m=''1861140''>As</span> <span m=''1861210''>long</span> <span m=''1861420''>as</span>
  <span m=''1861530''>I</span> <span m=''1861580''>get</span> <span m=''1861820''>the</span>
  <span m=''1861900''>band</span> <span m=''1862160''>to</span> <span m=''1862250''>do</span>
  <span m=''1862370''>this,</span> <span m=''1863130''>y-faces</span> <span m=''1863750''>can</span>
  <span m=''1863900''>hang</span> <span m=''1864140''>up</span> <span m=''1864270''>and</span>
  <span m=''1864360''>down.</span> <span m=''1865260''>It''s</span> <span m=''1865300''>not</span>
  <span m=''1865440''>going</span> <span m=''1865530''>to</span> <span m=''1865570''>intersect</span>
  <span m=''1865960''>anybody.</span> <span m=''1867600''>Pretty</span> <span m=''1867720''>clear?</span>
  <span m=''1868580''>So</span> <span m=''1868770''>it''s</span> <span m=''1868960''>clear</span>
  <span m=''1869250''>if</span> <span m=''1869360''>we</span> <span m=''1869480''>could</span>
  <span m=''1869610''>do</span> <span m=''1869730''>this,</span> <span m=''1870060''>we</span>
  <span m=''1870220''>can</span> <span m=''1870320''>get</span> <span m=''1870470''>non-selfintersection.</span>
  </p><p><span m=''1872060''>The</span> <span m=''1872160''>amazing</span> <span m=''1872530''>thing</span>
  <span m=''1872690''>is</span> <span m=''1872810''>that</span> <span m=''1872910''>this</span>
  <span m=''1873080''>is</span> <span m=''1873180''>possible.</span> <span m=''1875050''>What</span>
  <span m=''1875300''>this</span> <span m=''1875470''>is</span> <span m=''1875540''>essentially</span>
  <span m=''1876030''>a</span> <span m=''1876080''>limitation</span> <span m=''1876690''>on</span>
  <span m=''1876900''>is</span> <span m=''1877110''>how</span> <span m=''1877560''>far</span>
  <span m=''1878050''>you</span> <span m=''1878220''>could</span> <span m=''1878480''>turn</span>
  <span m=''1879230''>your</span> <span m=''1879390''>bearing.</span> <span m=''1879900''>So
  you</span> <span m=''1880080''>start</span> <span m=''1880330''>going</span> <span
  m=''1880600''>right.</span> <span m=''1881650''>You</span> <span m=''1881780''>can</span>
  <span m=''1881930''>turn</span> <span m=''1882140''>right,</span> <span m=''1882400''>but</span>
  <span m=''1882520''>I</span> <span m=''1882570''>could</span> <span m=''1882760''>not</span>
  <span m=''1882990''>turn</span> <span m=''1883150''>right</span> <span m=''1883330''>again.</span>
  <span m=''1883710''>I</span> <span m=''1883820''>have</span> <span m=''1884070''>to</span>
  <span m=''1884180''>turn</span> <span m=''1884390''>left</span> <span m=''1884660''>next.</span>
  <span m=''1885510''>I</span> <span m=''1885570''>can</span> <span m=''1885690''>actually</span>
  <span m=''1885960''>do</span> <span m=''1886090''>two</span> <span m=''1886290''>left</span>
  <span m=''1886490''>turns</span> <span m=''1886710''>in</span> <span m=''1886800''>a</span>
  <span m=''1886870''>row,</span> <span m=''1887120''>as</span> <span m=''1887210''>long</span>
  <span m=''1887400''>as</span> <span m=''1887480''>I was</span> <span m=''1887710''>initially</span>
  <span m=''1888040''>going</span> <span m=''1888290''>down.</span> </p><p><span m=''1889145''>I
  can</span> <span m=''1889400''>turn</span> <span m=''1889580''>left</span> <span
  m=''1889800''>twice,</span> <span m=''1890240''>then,</span> <span m=''1890480''>I</span>
  <span m=''1890590''>could</span> <span m=''1890820''>alternate</span> <span m=''1891270''>left-right.</span>
  <span m=''1891770''>That''s</span> <span m=''1892000''>always</span> <span m=''1892250''>good.</span>
  <span m=''1892650''>Or I</span> <span m=''1893100''>could</span> <span m=''1893340''>turn</span>
  <span m=''1893500''>right</span> <span m=''1893720''>twice,</span> <span m=''1895110''>but</span>
  <span m=''1895230''>only</span> <span m=''1895450''>if</span> <span m=''1895580''>I''m</span>
  <span m=''1895710''>initially</span> <span m=''1896030''>going</span> <span m=''1896290''>up.</span>
  <span m=''1897940''>That''s</span> <span m=''1898140''>the</span> <span m=''1898220''>rules.</span>
  <span m=''1898780''>As</span> <span m=''1898890''>long</span> <span m=''1899050''>as</span>
  <span m=''1899160''>I</span> <span m=''1899290''>adhere</span> <span m=''1899600''>to</span>
  <span m=''1899650''>those</span> <span m=''1899830''>rules,</span> <span m=''1900110''>I''m</span>
  <span m=''1900270''>fine.</span> </p><p><span m=''1901500''>Now,</span> <span m=''1901780''>we''re</span>
  <span m=''1901970''>going</span> <span m=''1902210''>to</span> <span m=''1902420''>heavily</span>
  <span m=''1902910''>exploit</span> <span m=''1903950''>that</span> <span m=''1904140''>we</span>
  <span m=''1904320''>can</span> <span m=''1904490''>do</span> <span m=''1904690''>general</span>
  <span m=''1905140''>unfolding,</span> <span m=''1905760''>that</span> <span m=''1905900''>we</span>
  <span m=''1906060''>can</span> <span m=''1906430''>subdivide</span> <span m=''1907770''>those</span>
  <span m=''1907950''>strips</span> <span m=''1908260''>into</span> <span m=''1908450''>lots</span>
  <span m=''1908690''>of</span> <span m=''1908740''>little</span> <span m=''1908950''>pieces.</span>
  <span m=''1910210''>We''re</span> <span m=''1910370''>going</span> <span m=''1910460''>to</span>
  <span m=''1910520''>subdivide</span> <span m=''1910940''>into</span> <span m=''1911190''>a</span>
  <span m=''1911300''>lot</span> <span m=''1911990''>of</span> <span m=''1912030''>little</span>
  <span m=''1912190''>pieces,</span> <span m=''1912600''>an</span> <span m=''1912760''>exponential</span>
  <span m=''1914320''>number</span> <span m=''1914570''>of</span> <span m=''1914650''>pieces,</span>
  <span m=''1915980''>so</span> <span m=''1916140''>this is</span> <span m=''1916410''>kind</span>
  <span m=''1916590''>of</span> <span m=''1917350''>hard</span> <span m=''1917650''>core.</span>
  <span m=''1920100''>So</span> <span m=''1920280''>here</span> <span m=''1920620''>is</span>
  <span m=''1920770''>one</span> <span m=''1921820''>example.</span> </p><p><span
  m=''1925430''>This</span> <span m=''1925750''>is</span> <span m=''1926010''>a</span>
  <span m=''1926110''>leaf.</span> <span m=''1927190''>So</span> <span m=''1927640''>trees</span>
  <span m=''1927900''>have</span> <span m=''1928060''>leaves,</span> <span m=''1928680''>and</span>
  <span m=''1928840''>at</span> <span m=''1929020''>the</span> <span m=''1929170''>end,</span>
  <span m=''1929460''>we''re</span> <span m=''1929590''>going</span> <span m=''1929690''>to</span>
  <span m=''1929740''>have</span> <span m=''1929910''>to</span> <span m=''1930010''>visit</span>
  <span m=''1930330''>a</span> <span m=''1930430''>leaf.</span> <span m=''1930860''>So</span>
  <span m=''1931330''>this</span> <span m=''1931430''>is</span> <span m=''1931550''>one</span>
  <span m=''1931860''>box.</span> <span m=''1933140''>There''s</span> <span m=''1934190''>this</span>
  <span m=''1934320''>funny</span> <span m=''1934590''>view,</span> <span m=''1934830''>so</span>
  <span m=''1934980''>you</span> <span m=''1935120''>can</span> <span m=''1935250''>see</span>
  <span m=''1936290''>like</span> <span m=''1936520''>a</span> <span m=''1936590''>mirror</span>
  <span m=''1937180''>on</span> <span m=''1937310''>the</span> <span m=''1937390''>bottom</span>
  <span m=''1938290''>and</span> <span m=''1938660''>a</span> <span m=''1938700''>mirror</span>
  <span m=''1938990''>on</span> <span m=''1939140''>the</span> <span m=''1939230''>right</span>
  <span m=''1939490''>and</span> <span m=''1939620''>on</span> <span m=''1939780''>the</span>
  <span m=''1939870''>side.</span> <span m=''1941780''>So</span> <span m=''1942070''>this</span>
  <span m=''1942240''>is</span> <span m=''1942320''>if</span> <span m=''1942880''>you</span>
  <span m=''1943000''>had</span> <span m=''1943160''>one</span> <span m=''1943390''>box,</span>
  <span m=''1944280''>here''s</span> <span m=''1944470''>what</span> <span m=''1945050''>you</span>
  <span m=''1945190''>would</span> <span m=''1945330''>do.</span> </p><p><span m=''1947850''>And</span>
  <span m=''1948460''>we''re</span> <span m=''1948640''>actually</span> <span m=''1948920''>assuming--</span>
  <span m=''1949540''>notice</span> <span m=''1949800''>this</span> <span m=''1950070''>side</span>
  <span m=''1950350''>does</span> <span m=''1950470''>not</span> <span m=''1950750''>get</span>
  <span m=''1954200''>covered.</span> <span m=''1954970''>The</span> <span m=''1955080''>idea
  is</span> <span m=''1955340''>that</span> <span m=''1955520''>site</span> <span
  m=''1955680''>doesn''t</span> <span m=''1955890''>exist.</span> <span m=''1956210''>That''s</span>
  <span m=''1956410''>attached</span> <span m=''1956810''>to</span> <span m=''1956880''>the</span>
  <span m=''1956980''>rest</span> <span m=''1957230''>of the</span> <span m=''1957320''>polyhedron,</span>
  <span m=''1957920''>so</span> <span m=''1958080''>that''s</span> <span m=''1958300''>where</span>
  <span m=''1958430''>our</span> <span m=''1958490''>parent</span> <span m=''1958780''>lives.</span>
  <span m=''1959410''>And</span> <span m=''1959580''>our</span> <span m=''1959670''>parent</span>
  <span m=''1960030''>tells</span> <span m=''1960320''>us</span> <span m=''1960750''>you</span>
  <span m=''1960940''>have</span> <span m=''1961090''>to</span> <span m=''1961200''>start</span>
  <span m=''1961530''>at</span> <span m=''1961640''>s,</span> <span m=''1962600''>and
  it</span> <span m=''1962820''>says</span> <span m=''1963020''>you</span> <span m=''1963180''>better</span>
  <span m=''1963430''>finish</span> <span m=''1963840''>at</span> <span m=''1964030''>t.</span>
  <span m=''1965280''>And</span> <span m=''1965460''>I</span> <span m=''1965540''>want</span>
  <span m=''1965760''>the</span> <span m=''1965850''>property</span> <span m=''1966280''>that</span>
  <span m=''1966410''>if</span> <span m=''1966540''>initially,</span> <span m=''1969180''>I</span>
  <span m=''1969920''>think,</span> <span m=''1970080''>initially,</span> <span m=''1970470''>you''re</span>
  <span m=''1970520''>going</span> <span m=''1970770''>right.</span> <span m=''1971720''>No,</span>
  <span m=''1972115''>it</span> <span m=''1972420''>looks</span> <span m=''1972630''>like</span>
  <span m=''1972760''>initially,</span> <span m=''1973130''>you''re going</span> <span
  m=''1973380''>up.</span> <span m=''1975900''>It</span> <span m=''1976130''>matters.</span>
  </p><p><span m=''1977680''>You</span> <span m=''1977910''>can</span> <span m=''1978060''>do</span>
  <span m=''1978200''>stuff,</span> <span m=''1979220''>and</span> <span m=''1979350''>then,</span>
  <span m=''1979490''>at</span> <span m=''1979560''>the</span> <span m=''1979700''>end,</span>
  <span m=''1979910''>you</span> <span m=''1980020''>should</span> <span m=''1980300''>still</span>
  <span m=''1980540''>be</span> <span m=''1980680''>facing</span> <span m=''1981070''>up.</span>
  <span m=''1982060''>So</span> <span m=''1982210''>you</span> <span m=''1982290''>have</span>
  <span m=''1982480''>to</span> <span m=''1982570''>visit</span> <span m=''1982880''>all</span>
  <span m=''1982990''>these</span> <span m=''1983170''>faces,</span> <span m=''1983580''>but</span>
  <span m=''1984040''>not</span> <span m=''1984360''>turn</span> <span m=''1985030''>in</span>
  <span m=''1985210''>total.</span> <span m=''1986550''>And</span> <span m=''1986760''>normally,</span>
  <span m=''1987140''>that</span> <span m=''1987300''>would</span> <span m=''1987410''>be</span>
  <span m=''1987520''>hard</span> <span m=''1987770''>to</span> <span m=''1987840''>do.</span>
  <span m=''1988020''>If</span> <span m=''1988120''>you</span> <span m=''1988190''>just</span>
  <span m=''1988360''>tried</span> <span m=''1988480''>to</span> <span m=''1988590''>visit</span>
  <span m=''1988820''>one</span> <span m=''1989000''>face</span> <span m=''1989240''>at</span>
  <span m=''1989290''>a</span> <span m=''1989360''>time,</span> <span m=''1989640''>you</span>
  <span m=''1989730''>can''t</span> <span m=''1989990''>do</span> <span m=''1990100''>that,</span>
  <span m=''1990940''>but</span> <span m=''1991900''>if</span> <span m=''1992050''>you</span>
  <span m=''1992270''>visit</span> <span m=''1992640''>faces</span> <span m=''1992930''>multiple</span>
  <span m=''1993330''>times</span> <span m=''1993660''>and</span> <span m=''1993770''>kind</span>
  <span m=''1993970''>of</span> <span m=''1994060''>weave</span> <span m=''1994290''>around</span>
  <span m=''1994650''>in</span> <span m=''1994740''>a</span> <span m=''1994800''>clever</span>
  <span m=''1995100''>way,</span> <span m=''1995660''>you</span> <span m=''1995820''>can</span>
  <span m=''1995950''>do</span> <span m=''1996100''>it.</span> </p><p><span m=''1996880''>So</span>
  <span m=''1999380''>maybe</span> <span m=''2000175''>I''ll</span> <span m=''2000590''>point</span>
  <span m=''2001450''>with</span> <span m=''2001580''>this</span> <span m=''2002350''>thing.</span>
  <span m=''2004115''>Yeah.</span> <span m=''2004560''>So</span> <span m=''2004750''>I</span>
  <span m=''2004830''>start at</span> <span m=''2005210''>s.</span> <span m=''2005910''>I</span>
  <span m=''2006260''>go</span> <span m=''2006630''>up.</span> <span m=''2007060''>I</span>
  <span m=''2007490''>turn</span> <span m=''2007760''>right.</span> <span m=''2008670''>Now,</span>
  <span m=''2008780''>I</span> <span m=''2008850''>better</span> <span m=''2009100''>turn</span>
  <span m=''2009320''>left.</span> <span m=''2009700''>I</span> <span m=''2009760''>go</span>
  <span m=''2009970''>down</span> <span m=''2010400''>over</span> <span m=''2010670''>here,</span>
  <span m=''2011510''>up</span> <span m=''2011710''>there.</span> <span m=''2012840''>I</span>
  <span m=''2012990''>turn</span> <span m=''2013240''>left.</span> <span m=''2014140''>Then,</span>
  <span m=''2014280''>I</span> <span m=''2014370''>turn</span> <span m=''2014600''>right.</span>
  </p><p><span m=''2016560''>So</span> <span m=''2016730''>if</span> <span m=''2017010''>you</span>
  <span m=''2017120''>follow</span> <span m=''2017460''>along</span> <span m=''2017720''>here,</span>
  <span m=''2018510''>I</span> <span m=''2018670''>just</span> <span m=''2018870''>turn</span>
  <span m=''2019030''>right</span> <span m=''2019280''>here.</span> <span m=''2020420''>So</span>
  <span m=''2020630''>now,</span> <span m=''2020890''>I</span> <span m=''2021060''>go</span>
  <span m=''2021200''>down</span> <span m=''2021420''>here.</span> <span m=''2021890''>And</span>
  <span m=''2022090''>that</span> <span m=''2022340''>is</span> <span m=''2023720''>a</span>
  <span m=''2023840''>left</span> <span m=''2024200''>turn</span> <span m=''2024440''>because</span>
  <span m=''2024640''>it''s</span> <span m=''2024780''>on</span> <span m=''2024870''>the</span>
  <span m=''2024950''>bottom,</span> <span m=''2025390''>a little</span> <span m=''2025790''>hard</span>
  <span m=''2025990''>to</span> <span m=''2026060''>think</span> <span m=''2026240''>about.</span>
  <span m=''2026990''>So</span> <span m=''2027400''>I</span> <span m=''2027490''>turn</span>
  <span m=''2027730''>left</span> <span m=''2028050''>here,</span> <span m=''2029180''>and</span>
  <span m=''2029400''>then, I</span> <span m=''2029520''>go,</span> <span m=''2031020''>turn</span>
  <span m=''2031230''>right.</span> <span m=''2032330''>And</span> <span m=''2032750''>then,</span>
  <span m=''2032970''>I go</span> <span m=''2033120''>down,</span> <span m=''2034380''>turn</span>
  <span m=''2035610''>left</span> <span m=''2037100''>and</span> <span m=''2037310''>then,</span>
  <span m=''2037540''>right.</span> <span m=''2038900''>This is</span> <span m=''2039030''>confusing</span>
  <span m=''2039280''>that</span> <span m=''2039360''>I''m</span> <span m=''2039580''>upside</span>
  <span m=''2039810''>down.</span> <span m=''2040560''>And</span> <span m=''2040770''>I</span>
  <span m=''2040820''>come</span> <span m=''2041040''>to</span> <span m=''2041120''>t,</span>
  <span m=''2041930''>and</span> <span m=''2042090''>lo</span> <span m=''2042240''>and</span>
  <span m=''2042310''>behold,</span> <span m=''2043250''>I''m</span> <span m=''2043530''>facing</span>
  <span m=''2043920''>up</span> <span m=''2044050''>again.</span> <span m=''2046310''>In</span>
  <span m=''2046450''>fact, I</span> <span m=''2046700''>basically</span> <span m=''2047160''>just</span>
  <span m=''2047240''>zigzagged.</span> </p><p><span m=''2048520''>This</span> <span
  m=''2048989''>would</span> <span m=''2049120''>also</span> <span m=''2049460''>work</span>
  <span m=''2049699''>if</span> <span m=''2049820''>it</span> <span m=''2049880''>was</span>
  <span m=''2050030''>rotated</span> <span m=''2050480''>90</span> <span m=''2050699''>degrees.</span>
  <span m=''2051389''>I''d</span> <span m=''2051520''>initially</span> <span m=''2051810''>be</span>
  <span m=''2051909''>going</span> <span m=''2052120''>right</span> <span m=''2052360''>and,</span>
  <span m=''2052469''>then,</span> <span m=''2052610''>down</span> <span m=''2053179''>and</span>
  <span m=''2053340''>right and</span> <span m=''2053620''>down</span> <span m=''2053840''>and</span>
  <span m=''2053889''>right and</span> <span m=''2054380''>down.</span> <span m=''2054659''>So</span>
  <span m=''2054770''>this</span> <span m=''2054920''>can</span> <span m=''2055030''>kind</span>
  <span m=''2055270''>of</span> <span m=''2055350''>go</span> <span m=''2055610''>in</span>
  <span m=''2055710''>a</span> <span m=''2055800''>couple</span> <span m=''2056090''>of</span>
  <span m=''2056179''>different</span> <span m=''2056500''>orientations.</span> <span
  m=''2057790''>It''s</span> <span m=''2057949''>really</span> <span m=''2058100''>powerful.</span>
  </p><p><span m=''2058600''>It</span> <span m=''2058699''>also</span> <span m=''2058800''>works</span>
  <span m=''2059040''>if</span> <span m=''2059130''>t</span> <span m=''2059280''>is</span>
  <span m=''2059370''>on</span> <span m=''2059469''>the</span> <span m=''2059570''>other</span>
  <span m=''2059750''>side</span> <span m=''2059969''>of</span> <span m=''2060070''>s.</span>
  <span m=''2060384''>You could</span> <span m=''2060699''>do</span> <span m=''2060790''>sort</span>
  <span m=''2060940''>of</span> <span m=''2061030''>the</span> <span m=''2061080''>mirror</span>
  <span m=''2061360''>image</span> <span m=''2062199''>traversal.</span> <span m=''2062560''>Now,</span>
  <span m=''2062679''>obviously,</span> <span m=''2063000''>I</span> <span m=''2063030''>didn''t</span>
  <span m=''2063280''>cover</span> <span m=''2063560''>the</span> <span m=''2063670''>entire</span>
  <span m=''2064030''>surface.</span> <span m=''2064949''>I''m</span> <span m=''2065060''>leaving</span>
  <span m=''2065340''>room</span> <span m=''2065540''>for</span> <span m=''2065690''>later,</span>
  <span m=''2067179''>but</span> <span m=''2067630''>if</span> <span m=''2067780''>this</span>
  <span m=''2067940''>was</span> <span m=''2068060''>all</span> <span m=''2068380''>I
  was</span> <span m=''2068480''>going</span> <span m=''2068600''>to</span> <span
  m=''2068690''>do,</span> <span m=''2070719''>I</span> <span m=''2070830''>would</span>
  <span m=''2071000''>actually</span> <span m=''2071290''>sort</span> <span m=''2071469''>of</span>
  <span m=''2071560''>fill</span> <span m=''2072020''>out</span> <span m=''2072710''>all</span>
  <span m=''2072900''>those</span> <span m=''2073090''>strips,</span> <span m=''2073440''>just</span>
  <span m=''2073600''>kind</span> <span m=''2073739''>of</span> <span m=''2074520''>extend</span>
  <span m=''2074889''>them.</span> <span m=''2075360''>It</span> <span m=''2075489''>just</span>
  <span m=''2075690''>makes</span> <span m=''2075909''>this</span> <span m=''2076060''>kind</span>
  <span m=''2076219''>of</span> <span m=''2076300''>fatter.</span> <span m=''2077469''>So</span>
  <span m=''2077620''>this</span> <span m=''2078330''>got</span> <span m=''2078469''>a</span>
  <span m=''2078530''>little</span> <span m=''2078730''>bigger.</span> <span m=''2079070''>I''ve</span>
  <span m=''2079290''>got the</span> <span m=''2079380''>first</span> <span m=''2080150''>half</span>
  <span m=''2080730''>and</span> <span m=''2080980''>then, the</span> <span m=''2081060''>second</span>
  <span m=''2081370''>half.</span> <span m=''2082290''>This</span> <span m=''2082480''>is</span>
  <span m=''2082580''>really</span> <span m=''2082820''>glued</span> <span m=''2083130''>up</span>
  <span m=''2083270''>there.</span> </p><p><span m=''2084929''>But</span> <span m=''2085179''>you</span>
  <span m=''2085330''>can</span> <span m=''2085449''>imagine</span> <span m=''2086120''>once</span>
  <span m=''2086310''>you</span> <span m=''2086389''>have</span> <span m=''2086590''>these</span>
  <span m=''2086730''>sort</span> <span m=''2086889''>of</span> <span m=''2086989''>paths</span>
  <span m=''2087400''>that</span> <span m=''2087489''>visit</span> <span m=''2087810''>everything,</span>
  <span m=''2088800''>you</span> <span m=''2088929''>just</span> <span m=''2089120''>fatten</span>
  <span m=''2089469''>out,</span> <span m=''2089889''>and</span> <span m=''2090130''>it''s</span>
  <span m=''2090330''>no</span> <span m=''2090409''>big</span> <span m=''2090560''>deal.</span>
  <span m=''2091889''>And</span> <span m=''2092250''>also,</span> <span m=''2092620''>in</span>
  <span m=''2093040''>this</span> <span m=''2093210''>case</span> <span m=''2093480''>here,</span>
  <span m=''2093630''>we''re</span> <span m=''2093770''>imagining--</span> <span m=''2095126''>oh,</span>
  <span m=''2095480''>this</span> <span m=''2095690''>is</span> <span m=''2095790''>actually</span>
  <span m=''2096050''>two</span> <span m=''2096260''>of</span> <span m=''2096340''>them.</span>
  <span m=''2096870''>Fun.</span> <span m=''2098040''>Two of</span> <span m=''2098460''>these</span>
  <span m=''2098630''>strips</span> <span m=''2098930''>joined</span> <span m=''2099170''>together.</span>
  </p><p><span m=''2100770''>And</span> <span m=''2101050''>so</span> <span m=''2101200''>there''s</span>
  <span m=''2101580''>a</span> <span m=''2101640''>few</span> <span m=''2101830''>side</span>
  <span m=''2102120''>faces.</span> <span m=''2102670''>They</span> <span m=''2102780''>just</span>
  <span m=''2103130''>attach</span> <span m=''2103680''>up</span> <span m=''2103880''>and</span>
  <span m=''2103980''>down.</span> <span m=''2104590''>They''re</span> <span m=''2104690''>not
  going to</span> <span m=''2104860''>intersect</span> <span m=''2105360''>anything</span>
  <span m=''2106040''>because</span> <span m=''2106260''>this</span> <span m=''2106400''>is</span>
  <span m=''2106560''>not</span> <span m=''2106800''>actually</span> <span m=''2107050''>below</span>
  <span m=''2107330''>this.</span> <span m=''2107770''>This is</span> <span m=''2107870''>way</span>
  <span m=''2108070''>over</span> <span m=''2108260''>here.</span> <span m=''2112330''>So</span>
  <span m=''2112570''>that''s</span> <span m=''2113140''>the</span> <span m=''2113340''>leaves,</span>
  <span m=''2115950''>and</span> <span m=''2116130''>I</span> <span m=''2116520''>still</span>
  <span m=''2116700''>haven''t</span> <span m=''2116870''>gotten</span> <span m=''2117100''>to</span>
  <span m=''2117220''>the</span> <span m=''2117390''>exciting</span> <span m=''2117840''>part.</span>
  </p><p><span m=''2120940''>So</span> <span m=''2121280''>imagine</span> <span m=''2121730''>you</span>
  <span m=''2121840''>have</span> <span m=''2122070''>a</span> <span m=''2122130''>band.</span>
  <span m=''2123010''>Just</span> <span m=''2123130''>going</span> <span m=''2123240''>to</span>
  <span m=''2123310''>represent</span> <span m=''2123780''>that</span> <span m=''2123980''>by</span>
  <span m=''2124100''>this</span> <span m=''2124420''>big</span> <span m=''2124650''>rectangle,</span>
  <span m=''2126010''>and it has a</span> <span m=''2126430''>bunch</span> <span m=''2126650''>of</span>
  <span m=''2126730''>children.</span> <span m=''2127180''>Remember, it</span> <span
  m=''2127500''>can</span> <span m=''2127640''>have</span> <span m=''2127880''>front</span>
  <span m=''2128090''>children.</span> <span m=''2129030''>This</span> <span m=''2129210''>is</span>
  <span m=''2129530''>down</span> <span m=''2129940''>in</span> <span m=''2130060''>the</span>
  <span m=''2130290''>y-coordinate.</span> <span m=''2131370''>And</span> <span m=''2132220''>it</span>
  <span m=''2132360''>could</span> <span m=''2132470''>have</span> <span m=''2133620''>back</span>
  <span m=''2133910''>children</span> <span m=''2135590''>up</span> <span m=''2135770''>in</span>
  <span m=''2135860''>the</span> <span m=''2135960''>y-coordinate.</span> </p><p><span
  m=''2137640''>And</span> <span m=''2137970''>suppose</span> <span m=''2138600''>I''m</span>
  <span m=''2138780''>actually</span> <span m=''2139050''>attached</span> <span m=''2139440''>to</span>
  <span m=''2139510''>some</span> <span m=''2139730''>parent,</span> <span m=''2141070''>let''s</span>
  <span m=''2141270''>say,</span> <span m=''2141390''>as</span> <span m=''2141540''>a</span>
  <span m=''2141590''>down</span> <span m=''2141830''>neighbor,</span> <span m=''2143590''>and</span>
  <span m=''2144080''>I</span> <span m=''2144180''>start</span> <span m=''2144470''>at</span>
  <span m=''2144590''>some</span> <span m=''2144720''>s.</span> <span m=''2145220''>Let''s</span>
  <span m=''2145450''>say</span> <span m=''2145550''>I''m</span> <span m=''2145600''>told</span>
  <span m=''2145920''>you</span> <span m=''2146070''>have</span> <span m=''2146180''>to</span>
  <span m=''2146240''>start</span> <span m=''2146480''>here.</span> <span m=''2146760''>You</span>
  <span m=''2146860''>have</span> <span m=''2146960''>to</span> <span m=''2147060''>finish</span>
  <span m=''2147210''>here,</span> <span m=''2147780''>and</span> <span m=''2147950''>you
  should</span> <span m=''2148210''>preserve</span> <span m=''2148700''>orientation</span>
  <span m=''2149340''>because</span> <span m=''2149620''>I</span> <span m=''2149680''>don''t</span>
  <span m=''2149810''>want</span> <span m=''2149930''>to</span> <span m=''2149970''>have</span>
  <span m=''2150110''>to</span> <span m=''2150180''>think</span> <span m=''2150390''>about</span>
  <span m=''2150750''>whether it</span> <span m=''2151070''>turned,</span> <span m=''2152630''>don''t
  want to</span> <span m=''2152860''>have</span> <span m=''2153020''>to</span> <span
  m=''2153100''>depend</span> <span m=''2153430''>on</span> <span m=''2153560''>that.</span>
  </p><p><span m=''2154060''>So</span> <span m=''2154630''>you</span> <span m=''2154800''>can</span>
  <span m=''2154950''>do</span> <span m=''2155110''>it.</span> <span m=''2156190''>Initially,</span>
  <span m=''2156600''>you</span> <span m=''2156680''>must</span> <span m=''2156850''>be</span>
  <span m=''2156960''>facing</span> <span m=''2157350''>up</span> <span m=''2157680''>because</span>
  <span m=''2157960''>immediately</span> <span m=''2158380''>I''m</span> <span m=''2158460''>going</span>
  <span m=''2158570''>to</span> <span m=''2158610''>make</span> <span m=''2158770''>two</span>
  <span m=''2158960''>right</span> <span m=''2159170''>turns.</span> <span m=''2160150''>And</span>
  <span m=''2160320''>I</span> <span m=''2160370''>could</span> <span m=''2160510''>handle</span>
  <span m=''2160770''>two</span> <span m=''2160910''>right</span> <span m=''2161090''>turns,</span>
  <span m=''2161350''>as</span> <span m=''2161460''>long</span> <span m=''2161650''>as</span>
  <span m=''2161750''>the</span> <span m=''2161820''>next</span> <span m=''2162060''>thing</span>
  <span m=''2162200''>I</span> <span m=''2162310''>did</span> <span m=''2162390''>was</span>
  <span m=''2162530''>a</span> <span m=''2162590''>left.</span> </p><p><span m=''2162890''>So</span>
  <span m=''2163430''>I</span> <span m=''2163550''>come</span> <span m=''2163830''>into</span>
  <span m=''2163980''>this</span> <span m=''2164160''>thing</span> <span m=''2164350''>saying,</span>
  <span m=''2165210''>look,</span> <span m=''2165460''>you''re</span> <span m=''2165690''>facing--</span>
  <span m=''2167060''>this</span> <span m=''2167200''>is</span> <span m=''2167320''>facing</span>
  <span m=''2167660''>up.</span> <span m=''2167940''>Now,</span> <span m=''2168110''>you''re</span>
  <span m=''2168250''>facing</span> <span m=''2168600''>down.</span> <span m=''2169430''>You</span>
  <span m=''2169600''>better</span> <span m=''2169880''>turn</span> <span m=''2170080''>left</span>
  <span m=''2170380''>next,</span> <span m=''2171030''>and</span> <span m=''2171370''>by</span>
  <span m=''2171500''>the</span> <span m=''2171640''>end,</span> <span m=''2171870''>I</span>
  <span m=''2171920''>still</span> <span m=''2172150''>want</span> <span m=''2172280''>to</span>
  <span m=''2172330''>be</span> <span m=''2172440''>facing</span> <span m=''2172790''>down.</span>
  <span m=''2173940''>OK.</span> </p><p><span m=''2174090''>Now,</span> <span m=''2174280''>I</span>
  <span m=''2174350''>make</span> <span m=''2174580''>two</span> <span m=''2174750''>left</span>
  <span m=''2174970''>turns.</span> <span m=''2175460''>Now,</span> <span m=''2175650''>I''m
  facing</span> <span m=''2175990''>up</span> <span m=''2176120''>again.</span> <span
  m=''2176450''>I</span> <span m=''2176530''>tell</span> <span m=''2176720''>this</span>
  <span m=''2176910''>guy,</span> <span m=''2177160''>you</span> <span m=''2177290''>better</span>
  <span m=''2177500''>turn</span> <span m=''2177710''>right</span> <span m=''2177930''>next,</span>
  <span m=''2178850''>and</span> <span m=''2179340''>preserve.</span> <span m=''2180230''>At</span>
  <span m=''2180360''>the</span> <span m=''2180470''>end,</span> <span m=''2180610''>you</span>
  <span m=''2180680''>should</span> <span m=''2180830''>be</span> <span m=''2180940''>facing</span>
  <span m=''2181300''>up</span> <span m=''2181440''>again.</span> <span m=''2182170''>Now,</span>
  <span m=''2182350''>I</span> <span m=''2182420''>make</span> <span m=''2182580''>two</span>
  <span m=''2182790''>right</span> <span m=''2182980''>turns.</span> <span m=''2183250''>Now,
  I''m</span> <span m=''2183400''>facing</span> <span m=''2183680''>down,</span> <span
  m=''2183970''>and</span> <span m=''2184090''>so</span> <span m=''2184250''>on</span>
  <span m=''2184440''>and</span> <span m=''2184520''>so</span> <span m=''2184660''>on.</span>
  <span m=''2185160''>And</span> <span m=''2185350''>here,</span> <span m=''2185680''>I''m</span>
  <span m=''2185830''>wrapping</span> <span m=''2186220''>around</span> <span m=''2187370''>to</span>
  <span m=''2187520''>here</span> <span m=''2188380''>because</span> <span m=''2188580''>this</span>
  <span m=''2188720''>is</span> <span m=''2188820''>actually</span> <span m=''2189100''>a</span>
  <span m=''2189360''>band that</span> <span m=''2189620''>cycles</span> <span m=''2190000''>around.</span>
  </p><p><span m=''2190850''>Then,</span> <span m=''2190990''>I</span> <span m=''2191060''>go</span>
  <span m=''2191250''>in</span> <span m=''2191330''>here.</span> <span m=''2191620''>It''s</span>
  <span m=''2191770''>the</span> <span m=''2191860''>same</span> <span m=''2192140''>thing.</span>
  <span m=''2192520''>It''s</span> <span m=''2192540''>just</span> <span m=''2192750''>a</span>
  <span m=''2192780''>little</span> <span m=''2192990''>hard</span> <span m=''2193200''>to</span>
  <span m=''2193260''>see</span> <span m=''2194390''>because</span> <span m=''2194670''>I''m</span>
  <span m=''2194820''>drawing</span> <span m=''2195160''>it</span> <span m=''2195960''>on</span>
  <span m=''2196210''>a</span> <span m=''2196940''>flat</span> <span m=''2197280''>surface.</span>
  <span m=''2197970''>But</span> <span m=''2198030''>if</span> <span m=''2198170''>it</span>
  <span m=''2198230''>was</span> <span m=''2198410''>on</span> <span m=''2198570''>a</span>
  <span m=''2198640''>ring,</span> <span m=''2198920''>it would</span> <span m=''2199080''>be</span>
  <span m=''2199200''>much</span> <span m=''2199410''>clearer.</span> <span m=''2200170''>Just</span>
  <span m=''2200340''>going</span> <span m=''2200580''>left</span> <span m=''2200960''>and</span>
  <span m=''2201060''>right</span> <span m=''2201450''>and</span> <span m=''2201540''>left</span>
  <span m=''2201890''>and right,</span> <span m=''2202190''>alternating</span> <span
  m=''2202650''>direction,</span> <span m=''2203450''>so</span> <span m=''2203710''>that
  I</span> <span m=''2203870''>preserve</span> <span m=''2205240''>my</span> <span
  m=''2205520''>orientation.</span> </p><p><span m=''2206570''>At</span> <span m=''2206750''>some</span>
  <span m=''2206970''>point,</span> <span m=''2207370''>I</span> <span m=''2207470''>get</span>
  <span m=''2207780''>to</span> <span m=''2208940''>here.</span> <span m=''2210160''>I</span>
  <span m=''2210320''>loop</span> <span m=''2210530''>around.</span> <span m=''2211090''>I</span>
  <span m=''2211520''>make</span> <span m=''2211690''>a</span> <span m=''2211750''>little</span>
  <span m=''2211940''>wiggle</span> <span m=''2212230''>at</span> <span m=''2212310''>some</span>
  <span m=''2212470''>point,</span> <span m=''2213530''>and</span> <span m=''2213760''>then,</span>
  <span m=''2213910''>I</span> <span m=''2213990''>can</span> <span m=''2214150''>visit</span>
  <span m=''2214390''>all</span> <span m=''2214530''>the</span> <span m=''2214630''>top</span>
  <span m=''2214910''>neighbors.</span> <span m=''2215840''>You</span> <span m=''2215920''>just</span>
  <span m=''2216100''>have</span> <span m=''2216210''>to</span> <span m=''2216320''>slightly</span>
  <span m=''2216660''>switch</span> <span m=''2216940''>your</span> <span m=''2217050''>orientation,</span>
  <span m=''2217600''>but</span> <span m=''2217720''>again,</span> <span m=''2217970''>preserve</span>
  <span m=''2218350''>that</span> <span m=''2218450''>you''re</span> <span m=''2218550''>doing</span>
  <span m=''2219080''>left-left-right-right,</span> <span m=''2220310''>left-left-right-right,</span>
  <span m=''2221480''>left-left-right-right.</span> <span m=''2222890''>Then,</span>
  <span m=''2223080''>you</span> <span m=''2223250''>will</span> <span m=''2223500''>preserve</span>
  <span m=''2223880''>your</span> <span m=''2224000''>orientation.</span> <span m=''2225030''>You</span>
  <span m=''2225210''>tell</span> <span m=''2225460''>each</span> <span m=''2225600''>of</span>
  <span m=''2225650''>the</span> <span m=''2225740''>children</span> <span m=''2226100''>which</span>
  <span m=''2226260''>way</span> <span m=''2226430''>you''re</span> <span m=''2226540''>initially</span>
  <span m=''2226910''>going,</span> <span m=''2227980''>and</span> <span m=''2228510''>they</span>
  <span m=''2228640''>can</span> <span m=''2228770''>deal</span> <span m=''2228950''>with</span>
  <span m=''2229120''>it.</span> <span m=''2230070''>It''s</span> <span m=''2230200''>basically</span>
  <span m=''2230550''>telling</span> <span m=''2230800''>you</span> <span m=''2230900''>whether</span>
  <span m=''2231100''>s</span> <span m=''2231700''>and</span> <span m=''2231970''>t</span>
  <span m=''2232070''>is</span> <span m=''2232160''>like</span> <span m=''2232340''>this</span>
  <span m=''2232590''>or</span> <span m=''2232700''>the</span> <span m=''2232840''>other</span>
  <span m=''2232980''>way</span> <span m=''2233060''>around.</span> </p><p><span m=''2236380''>OK?</span>
  <span m=''2237350''>So</span> <span m=''2237510''>now,</span> <span m=''2238220''>we</span>
  <span m=''2238460''>end</span> <span m=''2238610''>up</span> <span m=''2238750''>way</span>
  <span m=''2238980''>up</span> <span m=''2239110''>there</span> <span m=''2239360''>where</span>
  <span m=''2240000''>the</span> <span m=''2240220''>lavender</span> <span m=''2240850''>edge</span>
  <span m=''2241240''>is</span> <span m=''2241630''>at</span> <span m=''2241860''>t10.</span>
  <span m=''2244100''>Now</span> <span m=''2244400''>what?</span> <span m=''2245620''>We</span>
  <span m=''2245790''>want</span> <span m=''2245960''>to</span> <span m=''2246030''>come</span>
  <span m=''2246260''>back</span> <span m=''2246520''>here,</span> <span m=''2248590''>and</span>
  <span m=''2248780''>I''m</span> <span m=''2248860''>not</span> <span m=''2249040''>allowed</span>
  <span m=''2249340''>to</span> <span m=''2249440''>sort</span> <span m=''2249620''>of</span>
  <span m=''2249720''>intersect</span> <span m=''2250250''>myself.</span> <span m=''2250660''>That</span>
  <span m=''2250810''>would</span> <span m=''2250930''>be</span> <span m=''2251030''>the</span>
  <span m=''2251120''>paper</span> <span m=''2251480''>going</span> <span m=''2251710''>into</span>
  <span m=''2251890''>two</span> <span m=''2252050''>parts</span> <span m=''2252420''>of</span>
  <span m=''2252520''>this</span> <span m=''2252710''>unfolding,</span> <span m=''2253300''>so</span>
  <span m=''2253450''>that''s</span> <span m=''2253710''>not</span> <span m=''2253940''>good.</span>
  <span m=''2254620''>But</span> <span m=''2254770''>I</span> <span m=''2254840''>have</span>
  <span m=''2255060''>all</span> <span m=''2255190''>this</span> <span m=''2255390''>space,</span>
  <span m=''2256400''>so</span> <span m=''2257160''>natural</span> <span m=''2257500''>thing</span>
  <span m=''2257700''>is</span> <span m=''2257810''>to</span> <span m=''2258140''>just</span>
  <span m=''2258380''>wander</span> <span m=''2258890''>from</span> <span m=''2259100''>there</span>
  <span m=''2259760''>back</span> <span m=''2259990''>down</span> <span m=''2260180''>to
  here,</span> <span m=''2260670''>using</span> <span m=''2261020''>up</span> <span
  m=''2261140''>the</span> <span m=''2261220''>space.</span> </p><p><span m=''2262450''>So</span>
  <span m=''2262670''>it''s</span> <span m=''2262890''>going</span> <span m=''2262990''>to</span>
  <span m=''2263070''>look</span> <span m=''2263250''>like</span> <span m=''2263430''>this.</span>
  <span m=''2265650''>Everything</span> <span m=''2265925''>that</span> <span m=''2266200''>you</span>
  <span m=''2266440''>did,</span> <span m=''2266720''>you</span> <span m=''2266860''>just</span>
  <span m=''2267140''>undo.</span> <span m=''2269090''>Now,</span> <span m=''2269250''>where</span>
  <span m=''2269370''>this</span> <span m=''2269540''>is</span> <span m=''2269660''>painful</span>
  <span m=''2270670''>is</span> <span m=''2270850''>not</span> <span m=''2271110''>only</span>
  <span m=''2271310''>do I</span> <span m=''2271400''>have</span> <span m=''2271530''>to</span>
  <span m=''2271610''>undo</span> <span m=''2271900''>it</span> <span m=''2272050''>in</span>
  <span m=''2272230''>this</span> <span m=''2272600''>diagram,</span> <span m=''2273030''>but</span>
  <span m=''2273140''>I</span> <span m=''2273190''>have</span> <span m=''2273370''>to</span>
  <span m=''2273480''>recursively</span> <span m=''2274150''>undo</span> <span m=''2274470''>everything</span>
  <span m=''2274950''>I</span> <span m=''2275000''>did</span> <span m=''2275170''>in</span>
  <span m=''2275270''>here,</span> <span m=''2275910''>everything</span> <span m=''2276410''>I</span>
  <span m=''2276450''>didn''t</span> <span m=''2276730''>in here, and</span> <span
  m=''2276910''>everything</span> <span m=''2277340''>I</span> <span m=''2277390''>did</span>
  <span m=''2277570''>in</span> <span m=''2277640''>here.</span> </p><p><span m=''2278400''>So</span>
  <span m=''2279340''>this</span> <span m=''2279570''>recursive</span> <span m=''2280040''>thing</span>
  <span m=''2280750''>from</span> <span m=''2281090''>this</span> <span m=''2281410''>structure</span>
  <span m=''2281930''>ends</span> <span m=''2282140''>up</span> <span m=''2282260''>getting</span>
  <span m=''2282520''>doubled.</span> <span m=''2283360''>At</span> <span m=''2283530''>the</span>
  <span m=''2283610''>parent</span> <span m=''2283920''>structure,</span> <span m=''2284400''>it</span>
  <span m=''2284500''>will</span> <span m=''2284600''>also</span> <span m=''2284800''>get</span>
  <span m=''2284960''>doubled.</span> <span m=''2285700''>At</span> <span m=''2285870''>every</span>
  <span m=''2286220''>level</span> <span m=''2286650''>of</span> <span m=''2286850''>the</span>
  <span m=''2286940''>tree,</span> <span m=''2287420''>you''re</span> <span m=''2287620''>going</span>
  <span m=''2287760''>to</span> <span m=''2287830''>double</span> <span m=''2288780''>what</span>
  <span m=''2288980''>was</span> <span m=''2289180''>below</span> <span m=''2289480''>you,</span>
  <span m=''2290430''>so</span> <span m=''2290600''>that''s</span> <span m=''2290790''>why</span>
  <span m=''2290910''>you</span> <span m=''2290990''>get</span> <span m=''2291110''>exponential,</span>
  <span m=''2291660''>in</span> <span m=''2291730''>general.</span> </p><p><span m=''2292060''>If</span>
  <span m=''2292230''>your</span> <span m=''2292380''>tree</span> <span m=''2293200''>is</span>
  <span m=''2294850''>ugly</span> <span m=''2296310''>like</span> <span m=''2298480''>something</span>
  <span m=''2298850''>like</span> <span m=''2298990''>this,</span> <span m=''2302320''>you''ll</span>
  <span m=''2302450''>start</span> <span m=''2302720''>with</span> <span m=''2302800''>something</span>
  <span m=''2303100''>nice</span> <span m=''2303330''>and</span> <span m=''2303420''>small</span>
  <span m=''2303690''>down</span> <span m=''2303890''>here,</span> <span m=''2304360''>maybe</span>
  <span m=''2304820''>constant</span> <span m=''2305080''>number</span> <span m=''2305300''>of</span>
  <span m=''2305370''>terms.</span> <span m=''2306100''>Then,</span> <span m=''2306240''>you''ll</span>
  <span m=''2306380''>double.</span> <span m=''2306970''>Then,</span> <span m=''2307120''>you''ll</span>
  <span m=''2307220''>double</span> <span m=''2307440''>again.</span> <span m=''2307730''>Then,</span>
  <span m=''2307880''>you''ll</span> <span m=''2307960''>double</span> <span m=''2308180''>again.</span>
  <span m=''2308490''>Then, you''ll</span> <span m=''2308730''>double</span> <span
  m=''2308950''>again,</span> <span m=''2309290''>and it will</span> <span m=''2309370''>be</span>
  <span m=''2309500''>exponential.</span> <span m=''2310910''>So</span> <span m=''2311050''>if
  this</span> <span m=''2311250''>is</span> <span m=''2311380''>n,</span> <span m=''2313260''>the</span>
  <span m=''2313340''>number</span> <span m=''2313550''>of</span> <span m=''2313610''>things</span>
  <span m=''2313770''>you''re</span> <span m=''2313870''>doing</span> <span m=''2314070''>here</span>
  <span m=''2314230''>is</span> <span m=''2314515''>2</span> <span m=''2314800''>theta</span>
  <span m=''2314980''>n.</span> </p><p><span m=''2317190''>On</span> <span m=''2317320''>the</span>
  <span m=''2317420''>other</span> <span m=''2317600''>hand,</span> <span m=''2317900''>if</span>
  <span m=''2317930''>your</span> <span m=''2318050''>tree</span> <span m=''2318260''>happens</span>
  <span m=''2318680''>to</span> <span m=''2318780''>be</span> <span m=''2318910''>nice</span>
  <span m=''2319450''>and</span> <span m=''2319620''>balanced,</span> <span m=''2321450''>doubling</span>
  <span m=''2321780''>is</span> <span m=''2321890''>not</span> <span m=''2322100''>so</span>
  <span m=''2322270''>bad</span> <span m=''2323930''>because</span> <span m=''2324140''>here</span>
  <span m=''2324450''>you''ll</span> <span m=''2324530''>have</span> <span m=''2324780''>constant.</span>
  <span m=''2326270''>This</span> <span m=''2326450''>will</span> <span m=''2326580''>double</span>
  <span m=''2326880''>everything</span> <span m=''2327230''>below.</span> <span m=''2328710''>This</span>
  <span m=''2328890''>a</span> <span m=''2328950''>double</span> <span m=''2329190''>everything</span>
  <span m=''2329470''>below,</span> <span m=''2329730''>but</span> <span m=''2329850''>there''s</span>
  <span m=''2330030''>only</span> <span m=''2330340''>log n</span> <span m=''2330780''>levels.</span>
  <span m=''2334610''>So</span> <span m=''2334860''>is</span> <span m=''2335000''>that</span>
  <span m=''2335090''>linear?</span> <span m=''2337486''>It</span> <span m=''2337940''>should</span>
  <span m=''2338130''>be</span> <span m=''2338250''>about</span> <span m=''2338690''>linear.</span>
  <span m=''2339610''>It''s</span> <span m=''2339740''>certainly</span> <span m=''2340070''>2</span>
  <span m=''2340430''>to the</span> <span m=''2340530''>theta</span> <span m=''2341570''>log</span>
  <span m=''2341865''>n,</span> <span m=''2343140''>and it</span> <span m=''2343340''>matters</span>
  <span m=''2343660''>what</span> <span m=''2343800''>this</span> <span m=''2343950''>constant</span>
  <span m=''2344375''>is.</span> <span m=''2344800''>I</span> <span m=''2345100''>think</span>
  <span m=''2345270''>it''s</span> <span m=''2345650''>n</span> <span m=''2346050''>or</span>
  <span m=''2346120''>maybe</span> <span m=''2346420''>n</span> <span m=''2346550''>squared,</span>
  <span m=''2347810''>but</span> <span m=''2347930''>not</span> <span m=''2348100''>too</span>
  <span m=''2348200''>bad.</span> </p><p><span m=''2349790''>So</span> <span m=''2349920''>if</span>
  <span m=''2350000''>you''re</span> <span m=''2350120''>lucky</span> <span m=''2350440''>and</span>
  <span m=''2350550''>the</span> <span m=''2351030''>just</span> <span m=''2351270''>the</span>
  <span m=''2351350''>structure</span> <span m=''2351750''>of</span> <span m=''2351810''>your</span>
  <span m=''2351920''>bands</span> <span m=''2352330''>is</span> <span m=''2352440''>balanced,</span>
  <span m=''2353410''>it''s</span> <span m=''2353580''>good.</span> <span m=''2354220''>In</span>
  <span m=''2354350''>general,</span> <span m=''2354670''>though,</span> <span m=''2354820''>it''s</span>
  <span m=''2354940''>going</span> <span m=''2355040''>to</span> <span m=''2355100''>be</span>
  <span m=''2355190''>exponential.</span> <span m=''2356600''>Open</span> <span m=''2356900''>problem.</span>
  <span m=''2358420''>Can</span> <span m=''2358600''>you</span> <span m=''2358700''>deal</span>
  <span m=''2358970''>with</span> <span m=''2359100''>these</span> <span m=''2359250''>situations</span>
  <span m=''2360120''>and</span> <span m=''2360320''>sort</span> <span m=''2360490''>of</span>
  <span m=''2360590''>balance</span> <span m=''2361100''>them</span> <span m=''2361270''>and</span>
  <span m=''2361350''>make</span> <span m=''2361550''>them</span> <span m=''2362420''>only</span>
  <span m=''2362670''>make</span> <span m=''2362860''>a</span> <span m=''2362910''>polynomial</span>
  <span m=''2363460''>number</span> <span m=''2363670''>of</span> <span m=''2363760''>cuts.</span>
  <span m=''2364670''>Certainly</span> <span m=''2364930''>be</span> <span m=''2365040''>nice.</span>
  <span m=''2366320''>Exponential</span> <span m=''2366670''>number</span> <span m=''2366920''>cuts</span>
  <span m=''2367170''>is</span> <span m=''2367310''>a</span> <span m=''2367380''>lot,</span>
  <span m=''2369700''>but</span> <span m=''2370210''>it</span> <span m=''2370370''>works.</span>
  </p><p><span m=''2371960''>You</span> <span m=''2372100''>can</span> <span m=''2372220''>unfold</span>
  <span m=''2372570''>every</span> <span m=''2373060''>orthogonal</span> <span m=''2373560''>polyhedron</span>
  <span m=''2374040''>this</span> <span m=''2374200''>way.</span> <span m=''2374380''>I</span>
  <span m=''2374460''>would</span> <span m=''2374590''>love</span> <span m=''2374810''>to</span>
  <span m=''2374920''>see</span> <span m=''2375060''>an</span> <span m=''2375120''>implementation</span>
  <span m=''2375470''>of</span> <span m=''2375820''>this</span> <span m=''2375880''>algorithm.</span>
  <span m=''2377610''>You</span> <span m=''2377760''>could</span> <span m=''2377880''>only</span>
  <span m=''2378110''>do</span> <span m=''2378240''>it</span> <span m=''2378350''>in</span>
  <span m=''2378730''>a</span> <span m=''2378820''>computer</span> <span m=''2379430''>because</span>
  <span m=''2379580''>you''d</span> <span m=''2379720''>be</span> <span m=''2380060''>splicing</span>
  <span m=''2380400''>into</span> <span m=''2380530''>all</span> <span m=''2380750''>these</span>
  <span m=''2380860''>little</span> <span m=''2381050''>things,</span> <span m=''2381360''>and</span>
  <span m=''2381420''>it</span> <span m=''2381640''>would</span> <span m=''2382400''>fall</span>
  <span m=''2382590''>apart.</span> <span m=''2382960''>Jason?</span> </p><p><span
  m=''2384400''>AUDIENCE: You''ve</span> <span m=''2384880''>been</span> <span m=''2385360''>making</span>
  <span m=''2385840''>these,</span> <span m=''2386320''>I guess,</span> <span m=''2387476''>gadgets</span>
  <span m=''2387972''>[INAUDIBLE]</span> <span m=''2391940''>voxel</span> <span m=''2392690''>would</span>
  <span m=''2393530''>attach</span> <span m=''2393860''>just</span> <span m=''2394160''>by</span>
  <span m=''2394400''>a side.</span> <span m=''2395305''>You</span> <span m=''2395730''>could</span>
  <span m=''2395910''>imagine</span> <span m=''2396358''>it</span> <span m=''2396806''>attaching</span>
  <span m=''2397254''>at</span> <span m=''2397702''>a</span> <span m=''2398150''>corner</span>
  <span m=''2398600''>attaching</span> <span m=''2399091''>to</span> <span m=''2399582''>multiple</span>
  <span m=''2400073''>sides.</span> </p><p><span m=''2401550''>PROFESSOR: So</span>
  <span m=''2401840''>you''re</span> <span m=''2402570''>worried</span> <span m=''2402850''>about--</span>
  <span m=''2403885''>not quite</span> <span m=''2404370''>sure.</span> <span m=''2407210''>What</span>
  <span m=''2407440''>we</span> <span m=''2407620''>think</span> <span m=''2407880''>about</span>
  <span m=''2408760''>is</span> <span m=''2409000''>one</span> <span m=''2409330''>band,</span>
  <span m=''2410000''>which</span> <span m=''2410430''>looks</span> <span m=''2410580''>something</span>
  <span m=''2410840''>like</span> <span m=''2411040''>this,</span> <span m=''2413630''>attaching</span>
  <span m=''2414190''>to</span> <span m=''2414310''>another</span> <span m=''2414590''>band.</span>
  <span m=''2415090''>That</span> <span m=''2415260''>will</span> <span m=''2415440''>always</span>
  <span m=''2415670''>happen</span> <span m=''2416720''>on</span> <span m=''2416910''>a</span>
  <span m=''2416950''>face.</span> <span m=''2420750''>I''m</span> <span m=''2420840''>not</span>
  <span m=''2421030''>quite</span> <span m=''2421390''>sure</span> <span m=''2421620''>what</span>
  <span m=''2421750''>you''re</span> <span m=''2421890''>imagining.</span> <span m=''2422290''>Maybe</span>
  <span m=''2424760''>something</span> <span m=''2425230''>like</span> <span m=''2425490''>that</span>
  <span m=''2426040''>where</span> <span m=''2426260''>they</span> <span m=''2427160''>share
  a</span> <span m=''2427470''>partial</span> <span m=''2427880''>face</span> <span
  m=''2428540''>here?</span> </p><p><span m=''2429260''>AUDIENCE: Yeah,</span> <span
  m=''2429490''>but it</span> <span m=''2429960''>could</span> <span m=''2430430''>also
  be</span> <span m=''2430900''>inset</span> <span m=''2431370''>into the</span> <span
  m=''2431840''>[INAUDIBLE].</span> </p><p><span m=''2431980''>PROFESSOR: If it''s</span>
  <span m=''2432160''>inset,</span> <span m=''2433460''>I''m</span> <span m=''2433630''>cutting</span>
  <span m=''2434040''>with</span> <span m=''2434200''>every--</span> <span m=''2434890''>I</span>
  <span m=''2435000''>maybe</span> <span m=''2435320''>didn''t</span> <span m=''2435520''>mention</span>
  <span m=''2435800''>that--</span> <span m=''2436710''>through</span> <span m=''2437030''>every</span>
  <span m=''2437340''>vertex,</span> <span m=''2437940''>I''m</span> <span m=''2438060''>going</span>
  <span m=''2438160''>to</span> <span m=''2438230''>slice</span> <span m=''2438580''>with</span>
  <span m=''2438700''>a</span> <span m=''2438750''>y-plane.</span> <span m=''2440230''>So</span>
  <span m=''2440370''>that</span> <span m=''2440520''>will</span> <span m=''2440630''>cut</span>
  <span m=''2440840''>into</span> <span m=''2441060''>lots</span> <span m=''2441340''>of</span>
  <span m=''2441430''>little</span> <span m=''2441620''>strips,</span> <span m=''2442450''>and</span>
  <span m=''2442610''>then,</span> <span m=''2442760''>there''s</span> <span m=''2442940''>no</span>
  <span m=''2443110''>sort</span> <span m=''2443280''>of</span> <span m=''2443370''>overlap</span>
  <span m=''2443820''>with</span> <span m=''2443900''>the</span> <span m=''2443980''>strips.</span>
  <span m=''2444460''>I''m</span> <span m=''2444610''>subdividing</span> <span m=''2445770''>into</span>
  <span m=''2446010''>little</span> <span m=''2446190''>substrips.</span> <span m=''2447600''>So</span>
  <span m=''2447700''>that sort</span> <span m=''2447960''>of</span> <span m=''2448070''>deals</span>
  <span m=''2448360''>with</span> <span m=''2448470''>that</span> <span m=''2448630''>issue</span>
  <span m=''2448840''>if</span> <span m=''2449350''>this</span> <span m=''2449510''>was</span>
  <span m=''2449680''>moved</span> <span m=''2450060''>that</span> <span m=''2450260''>way.</span>
  <span m=''2451760''>Then,</span> <span m=''2451910''>there will be</span> <span
  m=''2452020''>three</span> <span m=''2452360''>strips,</span> <span m=''2453710''>one</span>
  <span m=''2454000''>over</span> <span m=''2454170''>here,</span> <span m=''2454410''>one</span>
  <span m=''2454550''>where</span> <span m=''2454650''>they''re</span> <span m=''2454780''>overlapping,</span>
  <span m=''2455300''>and</span> <span m=''2455370''>one</span> <span m=''2455660''>on
  the right.</span> <span m=''2457310''>Yeah.</span> <span m=''2457520''>Good</span>
  <span m=''2457660''>question.</span> <span m=''2457970''>I</span> <span m=''2458010''>forgot</span>
  <span m=''2458280''>to</span> <span m=''2458350''>mention</span> <span m=''2458610''>the</span>
  <span m=''2458680''>subdivision</span> <span m=''2459210''>at</span> <span m=''2459310''>the</span>
  <span m=''2459380''>beginning.</span> </p><p><span m=''2462190''>Speaking</span>
  <span m=''2462630''>of</span> <span m=''2462710''>subdivision</span> <span m=''2463230''>at</span>
  <span m=''2463320''>the</span> <span m=''2463400''>beginning,</span> <span m=''2465520''>this</span>
  <span m=''2465750''>leads</span> <span m=''2465990''>to</span> <span m=''2466110''>another</span>
  <span m=''2466390''>notion</span> <span m=''2467620''>which</span> <span m=''2468050''>we</span>
  <span m=''2468140''>call</span> <span m=''2468670''>grid</span> <span m=''2468930''>unfolding.</span>
  <span m=''2497010''>So</span> <span m=''2498430''>the</span> <span m=''2498530''>grid</span>
  <span m=''2499270''>of</span> <span m=''2499440''>an</span> <span m=''2499510''>orthogonal</span>
  <span m=''2500060''>polyhedron</span> <span m=''2501610''>is</span> <span m=''2501780''>what</span>
  <span m=''2501950''>you</span> <span m=''2502080''>get</span> <span m=''2502320''>when</span>
  <span m=''2502430''>you</span> <span m=''2502540''>subdivide</span> <span m=''2505850''>by</span>
  <span m=''2506690''>extending</span> <span m=''2507320''>every</span> <span m=''2507630''>face</span>
  <span m=''2508030''>into</span> <span m=''2508260''>a</span> <span m=''2508350''>plane</span>
  <span m=''2521730''>and</span> <span m=''2521900''>cutting</span> <span m=''2522210''>with</span>
  <span m=''2522320''>that</span> <span m=''2522530''>plane.</span> <span m=''2523700''>So</span>
  <span m=''2523890''>that''s</span> <span m=''2524110''>sort</span> <span m=''2524260''>of</span>
  <span m=''2524330''>what</span> <span m=''2524450''>I was</span> <span m=''2524610''>doing</span>
  <span m=''2524820''>here</span> <span m=''2525080''>when</span> <span m=''2525180''>they''re</span>
  <span m=''2525330''>overlapping.</span> <span m=''2525870''>Even</span> <span m=''2526130''>in</span>
  <span m=''2526200''>this</span> <span m=''2526400''>picture,</span> <span m=''2528310''>there''s</span>
  <span m=''2528540''>like</span> <span m=''2528700''>a</span> <span m=''2528750''>face</span>
  <span m=''2529070''>here,</span> <span m=''2530480''>this</span> <span m=''2530650''>vertical</span>
  <span m=''2531020''>face,</span> <span m=''2531400''>and</span> <span m=''2531510''>so</span>
  <span m=''2531600''>I''d</span> <span m=''2531730''>end</span> <span m=''2531870''>up</span>
  <span m=''2531980''>slicing</span> <span m=''2533250''>through</span> <span m=''2533400''>this</span>
  <span m=''2533610''>thing</span> <span m=''2533950''>with</span> <span m=''2534110''>a</span>
  <span m=''2534190''>band</span> <span m=''2534640''>in</span> <span m=''2535250''>that</span>
  <span m=''2535500''>direction.</span> </p><p><span m=''2539590''>And</span> <span
  m=''2540160''>I</span> <span m=''2540180''>don''t</span> <span m=''2540300''>know,</span>
  <span m=''2540430''>this</span> <span m=''2540660''>vertex</span> <span m=''2541870''>you''ll
  end</span> <span m=''2542090''>up</span> <span m=''2542170''>slicing</span> <span
  m=''2542680''>through</span> <span m=''2542820''>this</span> <span m=''2543050''>guy.</span>
  <span m=''2546690''>So</span> <span m=''2546800''>hopefully,</span> <span m=''2547070''>you</span>
  <span m=''2547150''>can</span> <span m=''2547260''>imagine</span> <span m=''2547620''>that.</span>
  <span m=''2548800''>With</span> <span m=''2548920''>every</span> <span m=''2549100''>vertex,</span>
  <span m=''2549520''>slice</span> <span m=''2549780''>x, y,</span> <span m=''2550120''>and</span>
  <span m=''2550230''>z.</span> <span m=''2551400''>That''s</span> <span m=''2551510''>another</span>
  <span m=''2551590''>way</span> <span m=''2551680''>to</span> <span m=''2551770''>do</span>
  <span m=''2551910''>it.</span> <span m=''2552620''>And</span> <span m=''2553330''>that</span>
  <span m=''2553640''>subdivides</span> <span m=''2554180''>in</span> <span m=''2554510''>sort</span>
  <span m=''2554710''>of</span> <span m=''2555120''>a</span> <span m=''2555240''>nice</span>
  <span m=''2555530''>grid</span> <span m=''2555840''>where</span> <span m=''2556000''>every</span>
  <span m=''2556310''>face</span> <span m=''2556620''>will</span> <span m=''2556730''>now</span>
  <span m=''2556890''>be</span> <span m=''2557070''>a</span> <span m=''2557260''>rectangle,</span>
  <span m=''2558370''>and</span> <span m=''2558550''>rectangles</span> <span m=''2559360''>always</span>
  <span m=''2559650''>meet</span> <span m=''2559880''>whole</span> <span m=''2560150''>edge</span>
  <span m=''2560350''>to</span> <span m=''2560420''>whole</span> <span m=''2560650''>edge.</span>
  <span m=''2561730''>So</span> <span m=''2561840''>it''s</span> <span m=''2561940''>a</span>
  <span m=''2561980''>nice</span> <span m=''2562170''>simplification.</span> </p><p><span
  m=''2563400''>What</span> <span m=''2563550''>I''m</span> <span m=''2563610''>proposing</span>
  <span m=''2564130''>is</span> <span m=''2564290''>add</span> <span m=''2564610''>those</span>
  <span m=''2564840''>edges</span> <span m=''2565180''>to</span> <span m=''2565300''>your</span>
  <span m=''2565410''>polyhedron.</span> <span m=''2566870''>It''s</span> <span m=''2566990''>kind</span>
  <span m=''2567260''>of</span> <span m=''2567330''>like</span> <span m=''2567520''>assuming</span>
  <span m=''2567920''>that you</span> <span m=''2568030''>started</span> <span m=''2568450''>with</span>
  <span m=''2568630''>unit</span> <span m=''2568920''>cubes</span> <span m=''2569670''>and</span>
  <span m=''2569880''>build</span> <span m=''2570080''>something</span> <span m=''2570390''>but</span>
  <span m=''2570570''>kept</span> <span m=''2570870''>all</span> <span m=''2571110''>the</span>
  <span m=''2571260''>edges</span> <span m=''2571600''>of</span> <span m=''2571710''>all</span>
  <span m=''2571860''>the</span> <span m=''2571950''>cubes.</span> <span m=''2574710''>I</span>
  <span m=''2574870''>want</span> <span m=''2575110''>an</span> <span m=''2575200''>edge</span>
  <span m=''2575390''>unfolding</span> <span m=''2575810''>of</span> <span m=''2575920''>that.</span>
  <span m=''2577700''>Do</span> <span m=''2577780''>those</span> <span m=''2578090''>exist?</span>
  <span m=''2578720''>These</span> <span m=''2578950''>are</span> <span m=''2579020''>what</span>
  <span m=''2579170''>we</span> <span m=''2579270''>call</span> <span m=''2580040''>grid</span>
  <span m=''2580280''>unfoldings.</span> </p><p><span m=''2587270''>So</span> <span
  m=''2587420''>grid</span> <span m=''2587660''>unfolding</span> <span m=''2588860''>is</span>
  <span m=''2589050''>an</span> <span m=''2589170''>edge</span> <span m=''2589400''>unfolding</span>
  <span m=''2589960''>of</span> <span m=''2590110''>the</span> <span m=''2590190''>grid.</span>
  <span m=''2592080''>This</span> <span m=''2592300''>only</span> <span m=''2592510''>makes</span>
  <span m=''2592720''>sense</span> <span m=''2592910''>for</span> <span m=''2593000''>orthogonal</span>
  <span m=''2593460''>polyhedra.</span> <span m=''2600460''>Open</span> <span m=''2600760''>question.</span>
  <span m=''2601730''>Do grid</span> <span m=''2602030''>unfoldings</span> <span m=''2602450''>always</span>
  <span m=''2602730''>exist?</span> <span m=''2604300''>It''s</span> <span m=''2604700''>essentially</span>
  <span m=''2605350''>the</span> <span m=''2605800''>orthogonal</span> <span m=''2606520''>analog</span>
  <span m=''2608170''>of</span> <span m=''2609610''>this</span> <span m=''2609830''>question,</span>
  <span m=''2611580''>edge</span> <span m=''2611780''>unfolding</span> <span m=''2612160''>a</span>
  <span m=''2612240''>convex</span> <span m=''2612630''>polyhedra.</span> <span m=''2613740''>If</span>
  <span m=''2613790''>you</span> <span m=''2613880''>want</span> <span m=''2614020''>to</span>
  <span m=''2614060''>go</span> <span m=''2614180''>to</span> <span m=''2614230''>orthogonal,</span>
  <span m=''2615040''>which is</span> <span m=''2615300''>like</span> <span m=''2615470''>in</span>
  <span m=''2615570''>between</span> <span m=''2616900''>convex</span> <span m=''2617340''>and</span>
  <span m=''2617420''>general</span> <span m=''2617710''>non-convex,</span> <span
  m=''2618970''>maybe</span> <span m=''2619360''>you</span> <span m=''2619470''>could</span>
  <span m=''2619580''>hope</span> <span m=''2619740''>for</span> <span m=''2619840''>grid</span>
  <span m=''2620030''>unfoldings.</span> </p><p><span m=''2620540''>Edge</span> <span
  m=''2620730''>unfoldings</span> <span m=''2621170''>obviously</span> <span m=''2621520''>don''t</span>
  <span m=''2621730''>work.</span> <span m=''2622030''>We</span> <span m=''2622150''>had</span>
  <span m=''2622370''>lots</span> <span m=''2622620''>of</span> <span m=''2622690''>examples</span>
  <span m=''2623890''>where</span> <span m=''2624110''>those</span> <span m=''2624960''>fail,</span>
  <span m=''2625600''>like</span> <span m=''2625850''>the</span> <span m=''2626070''>cube</span>
  <span m=''2626450''>with</span> <span m=''2626650''>little</span> <span m=''2626840''>bites</span>
  <span m=''2627150''>taken</span> <span m=''2627410''>out</span> <span m=''2627520''>of</span>
  <span m=''2627580''>the</span> <span m=''2627690''>edges.</span> <span m=''2629990''>But</span>
  <span m=''2630180''>grid</span> <span m=''2630380''>unfolding,</span> <span m=''2630950''>you</span>
  <span m=''2631020''>get</span> <span m=''2631150''>lots</span> <span m=''2631500''>of</span>
  <span m=''2631600''>subdivision.</span> <span m=''2632220''>It</span> <span m=''2632600''>might</span>
  <span m=''2632750''>be</span> <span m=''2632880''>easy.</span> <span m=''2633590''>Well,</span>
  <span m=''2633910''>it''s</span> <span m=''2634030''>not</span> <span m=''2634160''>easy.</span>
  </p><p><span m=''2635660''>I</span> <span m=''2635800''>would</span> <span m=''2635950''>guess,</span>
  <span m=''2636140''>actually,</span> <span m=''2636350''>it''s</span> <span m=''2636450''>not</span>
  <span m=''2636610''>possible.</span> <span m=''2638760''>The</span> <span m=''2639210''>next</span>
  <span m=''2639560''>best</span> <span m=''2639770''>thing</span> <span m=''2639890''>you</span>
  <span m=''2639980''>could</span> <span m=''2640100''>hope</span> <span m=''2640310''>for</span>
  <span m=''2641170''>is</span> <span m=''2641350''>to</span> <span m=''2641520''>refine.</span>
  <span m=''2648490''>So</span> <span m=''2648660''>you</span> <span m=''2649250''>take</span>
  <span m=''2649610''>each</span> <span m=''2649880''>of</span> <span m=''2649980''>the</span>
  <span m=''2650080''>grid</span> <span m=''2650270''>rectangles</span> <span m=''2654880''>and</span>
  <span m=''2655280''>divide</span> <span m=''2655700''>it</span> <span m=''2656330''>into</span>
  <span m=''2657650''>k</span> <span m=''2658110''>by</span> <span m=''2658520''>k,</span>
  <span m=''2659700''>so</span> <span m=''2659850''>subgrid.</span> <span m=''2666460''>So</span>
  <span m=''2666600''>ideally,</span> <span m=''2667040''>k</span> <span m=''2667240''>is</span>
  <span m=''2667530''>one,</span> <span m=''2668050''>and</span> <span m=''2668150''>you''re</span>
  <span m=''2668270''>not</span> <span m=''2668470''>subdividing</span> <span m=''2668960''>at</span>
  <span m=''2669020''>all.</span> <span m=''2669780''>But</span> <span m=''2670610''>maybe,</span>
  <span m=''2671490''>you</span> <span m=''2671570''>take</span> <span m=''2671770''>every</span>
  <span m=''2671940''>rectangle,</span> <span m=''2672700''>divide it</span> <span
  m=''2673020''>in</span> <span m=''2673130''>half.</span> <span m=''2673420''>Maybe</span>
  <span m=''2673630''>that''s</span> <span m=''2673870''>enough</span> <span m=''2674440''>to</span>
  <span m=''2674790''>then</span> <span m=''2675030''>be</span> <span m=''2675180''>edge</span>
  <span m=''2675370''>unfoldable.</span> <span m=''2676640''>That</span> <span m=''2676810''>would</span>
  <span m=''2676910''>be</span> <span m=''2677160''>sort</span> <span m=''2677390''>of</span>
  <span m=''2677530''>a</span> <span m=''2677660''>refined</span> <span m=''2678380''>level</span>
  <span m=''2678680''>two</span> <span m=''2679740''>grid-like</span> <span m=''2679970''>unfolding.</span>
  </p><p><span m=''2682220''>There</span> <span m=''2682380''>are</span> <span m=''2682400''>a</span>
  <span m=''2682490''>ton</span> <span m=''2682780''>of</span> <span m=''2682850''>results</span>
  <span m=''2683460''>about</span> <span m=''2684050''>this.</span> <span m=''2685590''>They''re</span>
  <span m=''2685750''>all</span> <span m=''2685900''>partial.</span> <span m=''2687670''>Obviously,</span>
  <span m=''2688230''>in</span> <span m=''2688420''>the</span> <span m=''2688540''>general</span>
  <span m=''2688900''>situation--</span> <span m=''2689610''>I</span> <span m=''2689650''>mean</span>
  <span m=''2689850''>this</span> <span m=''2690100''>algorithm</span> <span m=''2690550''>we</span>
  <span m=''2690650''>just</span> <span m=''2690730''>covered--</span> <span m=''2691480''>you</span>
  <span m=''2691650''>can</span> <span m=''2691770''>achieve</span> <span m=''2692060''>a</span>
  <span m=''2692100''>refinement</span> <span m=''2692650''>of</span> <span m=''2692950''>only</span>
  <span m=''2693450''>2</span> <span m=''2693720''>to the</span> <span m=''2693890''>theta</span>
  <span m=''2694130''>n</span> <span m=''2695590''>exponential.</span> </p><p><span
  m=''2697170''>When</span> <span m=''2697540''>can</span> <span m=''2697700''>you</span>
  <span m=''2697810''>do</span> <span m=''2697950''>better?</span> <span m=''2699030''>Ideally,</span>
  <span m=''2699380''>you</span> <span m=''2699500''>get</span> <span m=''2699630''>1</span>
  <span m=''2699820''>by</span> <span m=''2699940''>1,</span> <span m=''2700830''>but</span>
  <span m=''2701940''>maybe,</span> <span m=''2702200''>you</span> <span m=''2702340''>can</span>
  <span m=''2702450''>do</span> <span m=''2702550''>something.</span> <span m=''2711030''>What?</span>
  <span m=''2714870''>OK.</span> <span m=''2715820''>Interesting.</span> <span m=''2722420''>One</span>
  <span m=''2722820''>thing</span> <span m=''2723060''>you</span> <span m=''2723190''>could</span>
  <span m=''2723570''>do,</span> <span m=''2725230''>with</span> <span m=''2725540''>merely</span>
  <span m=''2726110''>5</span> <span m=''2726710''>by</span> <span m=''2726900''>4</span>
  <span m=''2727370''>refinement,</span> <span m=''2728620''>is</span> <span m=''2728780''>something</span>
  <span m=''2729040''>called</span> <span m=''2729240''>Manhattan</span> <span m=''2729710''>Towers.</span>
  </p><p><span m=''2730690''>Let me</span> <span m=''2730740''>show</span> <span m=''2730910''>you</span>
  <span m=''2731060''>a</span> <span m=''2731080''>picture</span> <span m=''2731520''>of</span>
  <span m=''2731990''>Manhattan</span> <span m=''2732430''>Tower.</span> <span m=''2734440''>No</span>
  <span m=''2734600''>that''s</span> <span m=''2734800''>not</span> <span m=''2734990''>a</span>
  <span m=''2735040''>picture</span> <span m=''2735350''>of Manhattan</span> <span
  m=''2735740''>Tower.</span> <span m=''2736120''>This</span> <span m=''2736250''>is</span>
  <span m=''2736390''>more</span> <span m=''2737250''>crazy</span> <span m=''2737640''>examples</span>
  <span m=''2738220''>of</span> <span m=''2738380''>what</span> <span m=''2738510''>it''s</span>
  <span m=''2738650''>like</span> <span m=''2738830''>to</span> <span m=''2738940''>visit.</span>
  <span m=''2739410''>This</span> <span m=''2739570''>is</span> <span m=''2739690''>not--</span>
  <span m=''2740740''>this</span> <span m=''2740950''>probably</span> <span m=''2741240''>is</span>
  <span m=''2741380''>complete,</span> <span m=''2742260''>but</span> <span m=''2742370''>here,</span>
  <span m=''2742520''>there</span> <span m=''2742660''>isn''t</span> <span m=''2742840''>too</span>
  <span m=''2742950''>much</span> <span m=''2743150''>doubling</span> <span m=''2743590''>because</span>
  <span m=''2743970''>there''s</span> <span m=''2745090''>only</span> <span m=''2745250''>a</span>
  <span m=''2745300''>single</span> <span m=''2745590''>child,</span> <span m=''2746130''>more
  or</span> <span m=''2746425''>less,</span> <span m=''2746720''>everywhere.</span>
  <span m=''2747920''>But</span> <span m=''2748220''>the</span> <span m=''2748475''>unfolding</span>
  <span m=''2748730''>looks</span> <span m=''2748910''>something</span> <span m=''2749170''>like</span>
  <span m=''2749350''>that.</span> </p><p><span m=''2751350''>Here</span> <span m=''2751670''>is</span>
  <span m=''2752200''>Manhattan</span> <span m=''2752660''>Tower.</span> <span m=''2753160''>So</span>
  <span m=''2753390''>it</span> <span m=''2753460''>has</span> <span m=''2753690''>a</span>
  <span m=''2753860''>connected</span> <span m=''2754370''>base</span> <span m=''2755405''>on</span>
  <span m=''2755790''>the</span> <span m=''2757020''>x-y plane.</span> <span m=''2759070''>And</span>
  <span m=''2760700''>I</span> <span m=''2760870''>want</span> <span m=''2761030''>to</span>
  <span m=''2761090''>consider</span> <span m=''2761550''>z-slices</span> <span m=''2762400''>as</span>
  <span m=''2762580''>I</span> <span m=''2762650''>go</span> <span m=''2762960''>up</span>
  <span m=''2763940''>in</span> <span m=''2764100''>z-coordinate,</span> <span m=''2764780''>and</span>
  <span m=''2765130''>I</span> <span m=''2765310''>want</span> <span m=''2765590''>those</span>
  <span m=''2765720''>z-slices</span> <span m=''2766300''>to</span> <span m=''2766400''>get</span>
  <span m=''2766600''>smaller</span> <span m=''2767060''>and</span> <span m=''2767150''>smaller,</span>
  <span m=''2767560''>always</span> <span m=''2767810''>contained</span> <span m=''2768380''>in</span>
  <span m=''2768470''>what</span> <span m=''2768610''>I</span> <span m=''2768660''>had</span>
  <span m=''2768850''>before.</span> <span m=''2769930''>So</span> <span m=''2770030''>I</span>
  <span m=''2770130''>never</span> <span m=''2770180''>have</span> <span m=''2770350''>overhang.</span>
  <span m=''2771260''>That''s</span> <span m=''2771460''>a</span> <span m=''2771510''>Manhattan</span>
  <span m=''2771850''>Tower.</span> </p><p><span m=''2773550''>And</span> <span m=''2773890''>in</span>
  <span m=''2773970''>that</span> <span m=''2774150''>case,</span> <span m=''2774600''>5</span>
  <span m=''2774990''>by</span> <span m=''2775140''>4</span> <span m=''2775430''>refinement</span>
  <span m=''2776240''>is</span> <span m=''2776410''>enough</span> <span m=''2777390''>to</span>
  <span m=''2777560''>unfold</span> <span m=''2778560''>these</span> <span m=''2778760''>things.</span>
  <span m=''2779080''>So</span> <span m=''2779220''>that''s</span> <span m=''2779390''>pretty</span>
  <span m=''2779600''>good,</span> <span m=''2780460''>still</span> <span m=''2780660''>not</span>
  <span m=''2780780''>perfect,</span> <span m=''2781270''>but</span> <span m=''2781560''>pretty</span>
  <span m=''2781760''>good.</span> <span m=''2782020''>And this is</span> <span m=''2782280''>by</span>
  <span m=''2782440''>the</span> <span m=''2782550''>same</span> <span m=''2782800''>authors,</span>
  <span m=''2784210''>like</span> <span m=''2784360''>a year</span> <span m=''2784620''>before</span>
  <span m=''2785080''>the</span> <span m=''2785190''>general</span> <span m=''2785490''>result.</span>
  </p><p><span m=''2787974''>Let''s</span> <span m=''2788470''>see.</span> <span m=''2789650''>I</span>
  <span m=''2789730''>think</span> <span m=''2790060''>maybe</span> <span m=''2790270''>I</span>
  <span m=''2790310''>have</span> <span m=''2790510''>a</span> <span m=''2790950''>movie.</span>
  <span m=''2791350''>Yeah.</span> <span m=''2791995''>So</span> <span m=''2792340''>this</span>
  <span m=''2792780''>algorithm</span> <span m=''2793200''>has</span> <span m=''2793370''>been</span>
  <span m=''2793490''>implemented,</span> <span m=''2793850''>at</span> <span m=''2793910''>least</span>
  <span m=''2794170''>in</span> <span m=''2794260''>some</span> <span m=''2794470''>simple</span>
  <span m=''2795460''>examples.</span> <span m=''2796780''>And it</span> <span m=''2797000''>kind</span>
  <span m=''2797190''>of</span> <span m=''2797240''>nicely</span> <span m=''2797600''>unrolls.</span>
  <span m=''2797990''>You</span> <span m=''2798110''>can</span> <span m=''2798240''>see</span>
  <span m=''2798470''>a</span> <span m=''2798630''>5</span> <span m=''2798710''>by</span>
  <span m=''2798860''>4</span> <span m=''2799080''>refinement</span> <span m=''2799540''>in</span>
  <span m=''2799630''>that</span> <span m=''2799790''>little</span> <span m=''2799950''>staircase.</span>
  <span m=''2801320''>It''s,</span> <span m=''2801500''>again,</span> <span m=''2801820''>to</span>
  <span m=''2801950''>make</span> <span m=''2802200''>everything</span> <span m=''2802810''>keep</span>
  <span m=''2803040''>going</span> <span m=''2803360''>to</span> <span m=''2803470''>the</span>
  <span m=''2803600''>right,</span> <span m=''2804750''>but</span> <span m=''2804860''>here,</span>
  <span m=''2805050''>they</span> <span m=''2805170''>find</span> <span m=''2805440''>a</span>
  <span m=''2805490''>clever</span> <span m=''2805820''>way</span> <span m=''2806050''>to</span>
  <span m=''2806270''>visit</span> <span m=''2806980''>all</span> <span m=''2807230''>the</span>
  <span m=''2807280''>faces</span> <span m=''2807630''>without</span> <span m=''2807900''>having</span>
  <span m=''2808160''>to</span> <span m=''2808270''>revisit,</span> <span m=''2809700''>basically,</span>
  <span m=''2809965''>at</span> <span m=''2810230''>all,</span> <span m=''2811580''>just</span>
  <span m=''2811770''>visiting</span> <span m=''2812100''>each</span> <span m=''2812260''>face</span>
  <span m=''2812450''>a</span> <span m=''2812520''>constant</span> <span m=''2812850''>number</span>
  <span m=''2813030''>of</span> <span m=''2813090''>times.</span> </p><p><span m=''2819990''>And
  then,</span> <span m=''2820340''>we</span> <span m=''2820460''>can</span> <span
  m=''2820640''>zoom</span> <span m=''2820940''>out,</span> <span m=''2822172''>and</span>
  <span m=''2822630''>you</span> <span m=''2822730''>get</span> <span m=''2822910''>the</span>
  <span m=''2823020''>unfolding.</span> <span m=''2823530''>So it</span> <span m=''2823720''>looks</span>
  <span m=''2823950''>very</span> <span m=''2824110''>similar</span> <span m=''2824460''>in</span>
  <span m=''2824530''>spirit.</span> <span m=''2825360''>Of</span> <span m=''2825400''>course,</span>
  <span m=''2825580''>the</span> <span m=''2825660''>details</span> <span m=''2826050''>is</span>
  <span m=''2826170''>how</span> <span m=''2826360''>do</span> <span m=''2826430''>you</span>
  <span m=''2826890''>do all</span> <span m=''2827080''>that</span> <span m=''2827270''>visiting.</span>
  <span m=''2827770''>I''m</span> <span m=''2827860''>not</span> <span m=''2828020''>going</span>
  <span m=''2828130''>to</span> <span m=''2828900''>cover</span> <span m=''2829100''>that</span>
  <span m=''2829270''>here,</span> <span m=''2830970''>but</span> <span m=''2831280''>you</span>
  <span m=''2831350''>get</span> <span m=''2831580''>substantially</span> <span m=''2832290''>less</span>
  <span m=''2832530''>refinement</span> <span m=''2833050''>for</span> <span m=''2833200''>that</span>
  <span m=''2833380''>special</span> <span m=''2833690''>case.</span> </p><p><span
  m=''2838150''>Yeah.</span> <span m=''2838810''>Another</span> <span m=''2839010''>case</span>
  <span m=''2839970''>looks</span> <span m=''2840160''>like</span> <span m=''2840300''>this.</span>
  <span m=''2840710''>Boom!</span> </p><p><span m=''2841380''>AUDIENCE: Woah.</span>
  </p><p><span m=''2842920''>PROFESSOR: Isn''t that</span> <span m=''2843400''>cool?</span>
  <span m=''2843680''>I''ll play it</span> <span m=''2843770''>again.</span> <span
  m=''2844780''>This</span> <span m=''2845060''>is</span> <span m=''2845760''>just</span>
  <span m=''2845950''>slightly</span> <span m=''2846420''>more</span> <span m=''2846630''>special.</span>
  <span m=''2847190''>So</span> <span m=''2847350''>again--</span> <span m=''2849120''>I</span>
  <span m=''2849550''>have</span> <span m=''2849890''>three</span> <span m=''2850160''>of</span>
  <span m=''2850250''>them.</span> <span m=''2850930''>They''re so</span> <span m=''2851110''>much</span>
  <span m=''2851330''>fun.</span> <span m=''2851740''>It''s</span> <span m=''2852230''>like</span>
  <span m=''2852380''>exploding</span> <span m=''2852850''>a</span> <span m=''2853155''>city.</span>
  <span m=''2853760''>Boom!</span> </p><p><span m=''2857220''>So</span> <span m=''2857560''>here,</span>
  <span m=''2858060''>the</span> <span m=''2858330''>floor</span> <span m=''2859240''>is</span>
  <span m=''2859410''>a</span> <span m=''2859520''>rectangle.</span> <span m=''2860300''>That''s</span>
  <span m=''2860490''>the</span> <span m=''2860630''>only</span> <span m=''2860970''>additional</span>
  <span m=''2861420''>requirement,</span> <span m=''2862590''>and</span> <span m=''2862740''>again,</span>
  <span m=''2863850''>as</span> <span m=''2864030''>you</span> <span m=''2864250''>slice</span>
  <span m=''2864710''>upwards,</span> <span m=''2865230''>things</span> <span m=''2865470''>only</span>
  <span m=''2865660''>get</span> <span m=''2865860''>smaller.</span> <span m=''2867270''>Here''s</span>
  <span m=''2867460''>a</span> <span m=''2867510''>bigger</span> <span m=''2867770''>one.</span>
  <span m=''2870760''>Boom!</span> <span m=''2872850''>So</span> <span m=''2873060''>exciting.</span>
  <span m=''2874680''>I could</span> <span m=''2874770''>do</span> <span m=''2874880''>this</span>
  <span m=''2875060''>all</span> <span m=''2875200''>day.</span> </p><p><span m=''2878860''>So</span>
  <span m=''2879890''>I''m</span> <span m=''2880130''>not</span> <span m=''2880290''>going</span>
  <span m=''2880400''>to</span> <span m=''2881750''>describe</span> <span m=''2882160''>how</span>
  <span m=''2882440''>this</span> <span m=''2882610''>works,</span> <span m=''2882970''>but</span>
  <span m=''2883150''>you</span> <span m=''2883380''>could</span> <span m=''2883520''>almost</span>
  <span m=''2883860''>reconstruct</span> <span m=''2884175''>it</span> <span m=''2884490''>from</span>
  <span m=''2884650''>these</span> <span m=''2884810''>diagrams.</span> <span m=''2886040''>This</span>
  <span m=''2886220''>is what</span> <span m=''2886700''>we</span> <span m=''2886850''>call</span>
  <span m=''2887080''>an</span> <span m=''2887160''>orthogonal</span> <span m=''2887660''>terrain.</span>
  <span m=''2890060''>This</span> <span m=''2890250''>result</span> <span m=''2890640''>by</span>
  <span m=''2890780''>Joe</span> <span m=''2891140''>O''Rourke.</span> <span m=''2893840''>Here,</span>
  <span m=''2894200''>you</span> <span m=''2894320''>don''t</span> <span m=''2894490''>need</span>
  <span m=''2894620''>any</span> <span m=''2894800''>refinement,</span> <span m=''2896050''>grid</span>
  <span m=''2896290''>unfolding,</span> <span m=''2897010''>one</span> <span m=''2897190''>by</span>
  <span m=''2897320''>one.</span> <span m=''2898200''>That''s</span> <span m=''2898400''>pretty</span>
  <span m=''2898610''>sweet.</span> </p><p><span m=''2901702''>All right.</span> <span
  m=''2902170''>Next</span> <span m=''2902440''>one</span> <span m=''2902950''>is</span>
  <span m=''2903380''>what</span> <span m=''2903470''>we</span> <span m=''2903570''>call</span>
  <span m=''2903880''>orthostacks.</span> <span m=''2906400''>These</span> <span m=''2906570''>are</span>
  <span m=''2906640''>like</span> <span m=''2906960''>a</span> <span m=''2907010''>stack</span>
  <span m=''2907500''>of</span> <span m=''2907630''>a</span> <span m=''2907690''>bunch</span>
  <span m=''2908010''>of</span> <span m=''2908150''>orthogonal</span> <span m=''2909730''>polygons,</span>
  <span m=''2910460''>a</span> <span m=''2910510''>bunch</span> <span m=''2910730''>of</span>
  <span m=''2910790''>bands,</span> <span m=''2911200''>basically.</span> <span m=''2911770''>This</span>
  <span m=''2911930''>is</span> <span m=''2911970''>where</span> <span m=''2912100''>the</span>
  <span m=''2912210''>idea of</span> <span m=''2912460''>bands</span> <span m=''2912770''>came</span>
  <span m=''2913020''>from.</span> <span m=''2913420''>This</span> <span m=''2913630''>is</span>
  <span m=''2913760''>from</span> <span m=''2913920''>an</span> <span m=''2913980''>old</span>
  <span m=''2914150''>paper in</span> <span m=''2914480''>1998,</span> <span m=''2915635''>from</span>
  <span m=''2915990''>the</span> <span m=''2916130''>beginning.</span> </p><p><span
  m=''2917600''>So</span> <span m=''2917680''>it''s</span> <span m=''2917780''>just</span>
  <span m=''2918170''>I</span> <span m=''2918270''>have</span> <span m=''2918480''>a</span>
  <span m=''2918540''>band,</span> <span m=''2918950''>and</span> <span m=''2919030''>then,</span>
  <span m=''2919140''>I</span> <span m=''2919170''>stack</span> <span m=''2919430''>another</span>
  <span m=''2919660''>band</span> <span m=''2919870''>on</span> <span m=''2919970''>top.</span>
  <span m=''2920350''>So</span> <span m=''2920610''>each</span> <span m=''2921430''>z</span>
  <span m=''2921795''>cross-section</span> <span m=''2923250''>is</span> <span m=''2923420''>connected.</span>
  <span m=''2924680''>So</span> <span m=''2924820''>that''s</span> <span m=''2924940''>a</span>
  <span m=''2924980''>little</span> <span m=''2925180''>different.</span> <span m=''2925580''>With</span>
  <span m=''2925790''>towers,</span> <span m=''2926260''>I</span> <span m=''2926320''>could</span>
  <span m=''2926460''>have</span> <span m=''2926620''>multiple</span> <span m=''2927450''>towers</span>
  <span m=''2927820''>here.</span> <span m=''2928090''>I really</span> <span m=''2928300''>only</span>
  <span m=''2928480''>want</span> <span m=''2928660''>one</span> <span m=''2929060''>tower</span>
  <span m=''2929930''>built</span> <span m=''2930160''>slab</span> <span m=''2930460''>by</span>
  <span m=''2930590''>slab.</span> </p><p><span m=''2931590''>These</span> <span m=''2931830''>things</span>
  <span m=''2932150''>we</span> <span m=''2932270''>don''t</span> <span m=''2932420''>know</span>
  <span m=''2932490''>how</span> <span m=''2932630''>to</span> <span m=''2932730''>grid</span>
  <span m=''2932920''>unfold.</span> <span m=''2933320''>That''s</span> <span m=''2933500''>an</span>
  <span m=''2933590''>open</span> <span m=''2933840''>problem,</span> <span m=''2934730''>but</span>
  <span m=''2934860''>if</span> <span m=''2934980''>you</span> <span m=''2935150''>refine</span>
  <span m=''2935800''>just</span> <span m=''2936330''>in</span> <span m=''2936540''>z</span>
  <span m=''2937410''>by a</span> <span m=''2937570''>factor</span> <span m=''2937910''>of</span>
  <span m=''2938000''>2,</span> <span m=''2938940''>that''s</span> <span m=''2939190''>enough</span>
  <span m=''2939400''>to</span> <span m=''2939480''>unfold.</span> <span m=''2941360''>So</span>
  <span m=''2941600''>1</span> <span m=''2941810''>by</span> <span m=''2941960''>2</span>
  <span m=''2942190''>refinement</span> <span m=''2942740''>is</span> <span m=''2942910''>enough</span>
  <span m=''2943270''>for</span> <span m=''2943520''>orthostacks.</span> </p><p><span
  m=''2952840''>Now,</span> <span m=''2953100''>you</span> <span m=''2953290''>could</span>
  <span m=''2953730''>go</span> <span m=''2953860''>a</span> <span m=''2953880''>little</span>
  <span m=''2954070''>crazier</span> <span m=''2955420''>and</span> <span m=''2955570''>allow</span>
  <span m=''2955960''>vertex</span> <span m=''2956460''>unfolding</span> <span m=''2958380''>of</span>
  <span m=''2958560''>orthostacks</span> <span m=''2959500''>with</span> <span m=''2959650''>some</span>
  <span m=''2959840''>grid</span> <span m=''2960030''>refinement,</span> <span m=''2960540''>and</span>
  <span m=''2960820''>in</span> <span m=''2961020''>that</span> <span m=''2961280''>case,</span>
  <span m=''2961600''>you</span> <span m=''2961730''>don''t</span> <span m=''2961890''>need</span>
  <span m=''2962050''>any</span> <span m=''2962260''>refinement.</span> <span m=''2964420''>So</span>
  <span m=''2964600''>grid</span> <span m=''2965320''>vertex</span> <span m=''2965730''>unfolding</span>
  <span m=''2966230''>orthostacks</span> <span m=''2967190''>was</span> <span m=''2967390''>the</span>
  <span m=''2967480''>title</span> <span m=''2968330''>of</span> <span m=''2968730''>paper.</span>
  <span m=''2970510''>These</span> <span m=''2970730''>guys,</span> <span m=''2971940''>John</span>
  <span m=''2972280''>Iacono</span> <span m=''2972490''>and</span> <span m=''2972570''>Stefan</span>
  <span m=''2972890''>Langerman.</span> </p><p><span m=''2973570''>And</span> <span
  m=''2974810''>it</span> <span m=''2974900''>looks</span> <span m=''2975080''>something</span>
  <span m=''2975340''>like</span> <span m=''2975490''>this.</span> <span m=''2976050''>He</span>
  <span m=''2976420''>uses</span> <span m=''2976650''>vertex</span> <span m=''2977090''>unfolding</span>
  <span m=''2977550''>to</span> <span m=''2978090''>fix</span> <span m=''2978430''>the</span>
  <span m=''2978510''>direction.</span> <span m=''2978920''>Here</span> <span m=''2979090''>you
  were</span> <span m=''2979290''>going</span> <span m=''2979610''>up,</span> <span
  m=''2979750''>but</span> <span m=''2979840''>you</span> <span m=''2979950''>really</span>
  <span m=''2980160''>wanted</span> <span m=''2980400''>to</span> <span m=''2980470''>go</span>
  <span m=''2980650''>right.</span> <span m=''2981730''>So</span> <span m=''2982080''>it</span>
  <span m=''2982290''>makes</span> <span m=''2982510''>things</span> <span m=''2982730''>easier.</span>
  </p><p><span m=''2983180''>And in</span> <span m=''2983220''>fact,</span> <span
  m=''2984750''>the</span> <span m=''2984770''>other</span> <span m=''2984900''>guys,</span>
  <span m=''2985190''>Damian,</span> <span m=''2986580''>Flatland,</span> <span m=''2986830''>and</span>
  <span m=''2987370''>O''Rourke--</span> <span m=''2988140''>It''s</span> <span m=''2988380''>got</span>
  <span m=''2988550''>to</span> <span m=''2989040''>be</span> <span m=''2989190''>awesome</span>
  <span m=''2989470''>doing</span> <span m=''2989650''>geometry</span> <span m=''2990130''>and</span>
  <span m=''2990170''>your</span> <span m=''2990280''>last</span> <span m=''2990500''>name
  is</span> <span m=''2990720''>Flatland,</span> <span m=''2994770''>unless she</span>
  <span m=''2995030''>does</span> <span m=''2995190''>a</span> <span m=''2995220''>lot</span>
  <span m=''2995360''>of</span> <span m=''2995430''>three</span> <span m=''2995610''>dimensional</span>
  <span m=''2996080''>stuff.</span> <span m=''2997490''>Irony.</span> </p><p><span
  m=''2999110''>You</span> <span m=''2999380''>can</span> <span m=''2999520''>do</span>
  <span m=''2999710''>vertex</span> <span m=''3001720''>grid</span> <span m=''3001960''>unfolding</span>
  <span m=''3002440''>of</span> <span m=''3002600''>any</span> <span m=''3002870''>orthogonal</span>
  <span m=''3003340''>polyhedron</span> <span m=''3004310''>is</span> <span m=''3004410''>what</span>
  <span m=''3004530''>I</span> <span m=''3004570''>have</span> <span m=''3004780''>written</span>
  <span m=''3004950''>here.</span> <span m=''3005400''>I</span> <span m=''3005500''>haven''t</span>
  <span m=''3005770''>actually</span> <span m=''3006030''>read</span> <span m=''3006120''>that.</span>
  <span m=''3006490''>I should</span> <span m=''3006670''>read that</span> <span m=''3006970''>paper.</span>
  <span m=''3008400''>What</span> <span m=''3008650''>else do</span> <span m=''3008760''>I</span>
  <span m=''3008820''>have?</span> </p><p><span m=''3009650''>Orthotubes.</span> <span
  m=''3011770''>Orthotubes,</span> <span m=''3012380''>this</span> <span m=''3012540''>is</span>
  <span m=''3012640''>again</span> <span m=''3012900''>in</span> <span m=''3013000''>the</span>
  <span m=''3013250''>old</span> <span m=''3013480''>paper.</span> <span m=''3015420''>Orthotube</span>
  <span m=''3015930''>is</span> <span m=''3016050''>just</span> <span m=''3016780''>sort</span>
  <span m=''3017010''>of</span> <span m=''3017280''>thickness</span> <span m=''3017720''>one</span>
  <span m=''3018400''>orthogonal</span> <span m=''3019410''>tube.</span> <span m=''3020590''>It</span>
  <span m=''3020680''>could</span> <span m=''3020800''>even</span> <span m=''3021060''>be</span>
  <span m=''3021320''>closed,</span> <span m=''3021850''>I</span> <span m=''3021910''>think,</span>
  <span m=''3022130''>in</span> <span m=''3022220''>a</span> <span m=''3022270''>loop,</span>
  <span m=''3023095''>but</span> <span m=''3023510''>here</span> <span m=''3023740''>I''ve</span>
  <span m=''3024180''>shown it</span> <span m=''3024540''>open.</span> </p><p><span
  m=''3025320''>And</span> <span m=''3025510''>here,</span> <span m=''3025800''>grid</span>
  <span m=''3026040''>unfolding</span> <span m=''3026550''>is</span> <span m=''3026660''>enough.</span>
  <span m=''3027200''>You</span> <span m=''3027320''>just</span> <span m=''3027570''>do</span>
  <span m=''3027730''>all</span> <span m=''3027880''>the</span> <span m=''3027960''>grid</span>
  <span m=''3028140''>refinement.</span> <span m=''3029090''>You</span> <span m=''3029200''>could</span>
  <span m=''3029300''>even</span> <span m=''3029490''>just</span> <span m=''3029640''>do</span>
  <span m=''3029760''>it</span> <span m=''3029810''>locally.</span> <span m=''3032030''>Technically,</span>
  <span m=''3034740''>there''s</span> <span m=''3034920''>a</span> <span m=''3034980''>slice</span>
  <span m=''3035370''>here</span> <span m=''3035620''>that</span> <span m=''3035760''>might</span>
  <span m=''3035950''>slice</span> <span m=''3036250''>over</span> <span m=''3036420''>here,</span>
  <span m=''3036750''>but you</span> <span m=''3036870''>don''t have</span> <span
  m=''3037070''>to</span> <span m=''3037170''>worry</span> <span m=''3037310''>about</span>
  <span m=''3037530''>that.</span> <span m=''3038160''>You</span> <span m=''3038540''>just</span>
  <span m=''3038690''>subdivide</span> <span m=''3039130''>into</span> <span m=''3039310''>a</span>
  <span m=''3039350''>bunch</span> <span m=''3039570''>of</span> <span m=''3039650''>boxes,</span>
  <span m=''3040330''>and</span> <span m=''3040510''>this</span> <span m=''3040680''>can</span>
  <span m=''3040850''>be</span> <span m=''3041110''>unfolded</span> <span m=''3041690''>in
  a</span> <span m=''3041890''>sort</span> <span m=''3042180''>of</span> <span m=''3042260''>zigzag</span>
  <span m=''3043130''>fashion.</span> <span m=''3045250''>So</span> <span m=''3045470''>1</span>
  <span m=''3045640''>by</span> <span m=''3045760''>1.</span> </p><p><span m=''3046850''>You</span>
  <span m=''3046980''>can</span> <span m=''3047090''>generalize</span> <span m=''3047450''>this</span>
  <span m=''3047580''>to</span> <span m=''3047700''>trees</span> <span m=''3048130''>also,</span>
  <span m=''3048620''>though, it''s</span> <span m=''3048750''>not</span> <span m=''3049070''>totally</span>
  <span m=''3049400''>known.</span> <span m=''3050110''>As</span> <span m=''3050150''>long</span>
  <span m=''3050330''>as</span> <span m=''3050400''>you</span> <span m=''3050530''>have</span>
  <span m=''3051390''>a</span> <span m=''3051480''>tree</span> <span m=''3051790''>of</span>
  <span m=''3051910''>cubes</span> <span m=''3052750''>with</span> <span m=''3053020''>fairly</span>
  <span m=''3053390''>long</span> <span m=''3053810''>connectors</span> <span m=''3054350''>in</span>
  <span m=''3054460''>between</span> <span m=''3055750''>the</span> <span m=''3055830''>branch</span>
  <span m=''3056130''>points--</span> <span m=''3056870''>those are</span> <span m=''3056970''>called</span>
  <span m=''3057170''>well-separated</span> <span m=''3057980''>orthotrees--</span>
  <span m=''3059990''>that</span> <span m=''3060180''>works</span> <span m=''3060720''>grid</span>
  <span m=''3060900''>unfolding.</span> <span m=''3062090''>If</span> <span m=''3062170''>you</span>
  <span m=''3062250''>don''t</span> <span m=''3062480''>have</span> <span m=''3062640''>that</span>
  <span m=''3062780''>condition,</span> <span m=''3063540''>so</span> <span m=''3063680''>just</span>
  <span m=''3063900''>have</span> <span m=''3064030''>cubes</span> <span m=''3064370''>connect</span>
  <span m=''3064640''>in</span> <span m=''3064740''>some</span> <span m=''3064980''>treelike</span>
  <span m=''3065340''>fashion,</span> <span m=''3065830''>it''s</span> <span m=''3066290''>open</span>
  <span m=''3066640''>whether</span> <span m=''3066780''>you can</span> <span m=''3067000''>do
  a grid</span> <span m=''3067360''>unfolding.</span> <span m=''3067730''>We''ve</span>
  <span m=''3067820''>worked</span> <span m=''3068070''>on</span> <span m=''3068150''>that</span>
  <span m=''3068300''>in</span> <span m=''3068340''>the</span> <span m=''3068420''>past.</span>
  </p><p><span m=''3068800''>My</span> <span m=''3069170''>conjecture''s,</span> <span
  m=''3071670''>in</span> <span m=''3071780''>general,</span> <span m=''3072750''>you</span>
  <span m=''3072940''>need</span> <span m=''3073380''>to</span> <span m=''3074130''>omega</span>
  <span m=''3074550''>n</span> <span m=''3075480''>refinement.</span> <span m=''3084830''>My</span>
  <span m=''3085200''>belief</span> <span m=''3086430''>is</span> <span m=''3086670''>that</span>
  <span m=''3086980''>this</span> <span m=''3087190''>kind</span> <span m=''3087450''>of</span>
  <span m=''3087640''>exponential</span> <span m=''3088220''>blow</span> <span m=''3088460''>up</span>
  <span m=''3088650''>is</span> <span m=''3088810''>necessary,</span> <span m=''3090310''>but</span>
  <span m=''3090680''>that</span> <span m=''3090840''>you</span> <span m=''3091000''>can</span>
  <span m=''3091150''>do</span> <span m=''3091320''>it</span> <span m=''3091450''>only</span>
  <span m=''3091710''>a</span> <span m=''3091770''>balance</span> <span m=''3092200''>tree.</span>
  <span m=''3092720''>So</span> <span m=''3092870''>this</span> <span m=''3093090''>would</span>
  <span m=''3093190''>give</span> <span m=''3094070''>like</span> <span m=''3094240''>linear</span>
  <span m=''3094550''>refinement.</span> <span m=''3095340''>I</span> <span m=''3095480''>think</span>
  <span m=''3095700''>that''s</span> <span m=''3095880''>necessary,</span> <span m=''3096190''>but</span>
  <span m=''3096330''>we</span> <span m=''3096450''>can''t</span> <span m=''3096660''>even</span>
  <span m=''3096880''>prove that</span> <span m=''3097180''>you</span> <span m=''3097360''>need</span>
  <span m=''3097990''>2</span> <span m=''3098170''>buy</span> <span m=''3098330''>1</span>
  <span m=''3098570''>refinement</span> <span m=''3099100''>in</span> <span m=''3099220''>any</span>
  <span m=''3099480''>example.</span> <span m=''3100670''>We don''t have</span> <span
  m=''3100940''>anything</span> <span m=''3102010''>where</span> <span m=''3102430''>grid</span>
  <span m=''3102610''>unfolding</span> <span m=''3103280''>is</span> <span m=''3103790''>definitely</span>
  <span m=''3104210''>impossible.</span> <span m=''3106190''>It''s</span> <span m=''3106330''>quite</span>
  <span m=''3107780''>sad</span> <span m=''3108650''>state,</span> <span m=''3109080''>I</span>
  <span m=''3109160''>guess.</span> </p><p><span m=''3113190''>It''s</span> <span
  m=''3113400''>very</span> <span m=''3113610''>hard</span> <span m=''3113820''>to</span>
  <span m=''3113900''>prove</span> <span m=''3114170''>that</span> <span m=''3114290''>there</span>
  <span m=''3114410''>aren''t</span> <span m=''3114650''>unfoldings,</span> <span
  m=''3115150''>accept</span> <span m=''3115440''>by</span> <span m=''3115600''>exhaustive</span>
  <span m=''3116050''>enumeration,</span> <span m=''3117630''>and</span> <span m=''3119180''>that''s</span>
  <span m=''3119380''>hard</span> <span m=''3119540''>to</span> <span m=''3119600''>do</span>
  <span m=''3119920''>because</span> <span m=''3120040''>it''s</span> <span m=''3120200''>slow.</span>
  <span m=''3130070''>We''ve come up with</span> <span m=''3130190''>lots</span> <span
  m=''3130500''>of</span> <span m=''3130610''>candidate</span> <span m=''3130940''>examples,</span>
  <span m=''3131520''>but</span> <span m=''3132040''>eventually,</span> <span m=''3132430''>we</span>
  <span m=''3132680''>unfold</span> <span m=''3133030''>them</span> <span m=''3133080''>all.</span>
  <span m=''3136690''>I</span> <span m=''3136990''>have</span> <span m=''3137310''>a</span>
  <span m=''3137330''>bunch</span> <span m=''3137570''>of</span> <span m=''3137690''>other</span>
  <span m=''3138450''>open</span> <span m=''3138700''>problems.</span> </p><p><span
  m=''3141430''>This</span> <span m=''3141640''>was</span> <span m=''3141790''>genus</span>
  <span m=''3142130''>0.</span> <span m=''3143080''>Interesting</span> <span m=''3143500''>question</span>
  <span m=''3143830''>is</span> <span m=''3143940''>can</span> <span m=''3144160''>you</span>
  <span m=''3144290''>do</span> <span m=''3144570''>genus</span> <span m=''3145790''>higher</span>
  <span m=''3146100''>than</span> <span m=''3146390''>0?</span> <span m=''3147620''>Orthogonal</span>
  <span m=''3148160''>polyhedra.</span> <span m=''3150670''>I</span> <span m=''3150800''>would</span>
  <span m=''3150940''>guess</span> <span m=''3151140''>so,</span> <span m=''3151460''>but
  I''m</span> <span m=''3151590''>not</span> <span m=''3151730''>sure.</span> <span
  m=''3152530''>I</span> <span m=''3152620''>think</span> <span m=''3152750''>the</span>
  <span m=''3152830''>biggest</span> <span m=''3153160''>question</span> <span m=''3153420''>is,</span>
  <span m=''3153600''>can</span> <span m=''3153660''>you</span> <span m=''3153760''>make</span>
  <span m=''3153940''>this</span> <span m=''3154080''>non-orthogonal?</span> <span
  m=''3155440''>But</span> <span m=''3155560''>then,</span> <span m=''3155710''>the</span>
  <span m=''3155800''>bands</span> <span m=''3156130''>get</span> <span m=''3156280''>messy.</span>
  <span m=''3157850''>Haven''t</span> <span m=''3158060''>been</span> <span m=''3158160''>able</span>
  <span m=''3158360''>to</span> <span m=''3158460''>do</span> <span m=''3158570''>that.</span>
  </p><p><span m=''3159760''>All right.</span> <span m=''3160160''>I</span> <span
  m=''3160400''>think</span> <span m=''3160580''>those were</span> <span m=''3160750''>the</span>
  <span m=''3160820''>main</span> <span m=''3161020''>problems.</span> <span m=''3162300''>Any</span>
  <span m=''3162410''>questions?</span> <span m=''3165960''>I''m</span> <span m=''3166130''>going</span>
  <span m=''3166270''>to</span> <span m=''3166610''>take</span> <span m=''3166760''>a</span>
  <span m=''3166800''>break</span> <span m=''3167050''>from</span> <span m=''3167210''>unfolding</span>
  <span m=''3168030''>now</span> <span m=''3168250''>and</span> <span m=''3168430''>switch</span>
  <span m=''3168770''>the</span> <span m=''3168930''>other</span> <span m=''3169090''>direction</span>
  <span m=''3169630''>of</span> <span m=''3170010''>folding.</span> </p><p><span m=''3173100''>So</span>
  <span m=''3173710''>with</span> <span m=''3173870''>folding,</span> <span m=''3185330''>we''re</span>
  <span m=''3185460''>imagining</span> <span m=''3185900''>we''re</span> <span m=''3186720''>given</span>
  <span m=''3186990''>some</span> <span m=''3187230''>polygon,</span> <span m=''3189850''>and</span>
  <span m=''3190000''>we''d</span> <span m=''3190140''>like</span> <span m=''3190350''>to</span>
  <span m=''3190470''>make</span> <span m=''3190610''>a</span> <span m=''3190670''>polyhedron</span>
  <span m=''3191220''>out</span> <span m=''3191360''>of</span> <span m=''3191470''>it.</span>
  <span m=''3191570''>It''s</span> <span m=''3191660''>exactly</span> <span m=''3192140''>the</span>
  <span m=''3192250''>reverse</span> <span m=''3193570''>of</span> <span m=''3193780''>what</span>
  <span m=''3193940''>we''ve</span> <span m=''3194100''>been</span> <span m=''3194230''>thinking</span>
  <span m=''3194490''>about.</span> <span m=''3197730''>When</span> <span m=''3197930''>is</span>
  <span m=''3198040''>this</span> <span m=''3198190''>possible?</span> </p><p><span
  m=''3199510''>Now,</span> <span m=''3199530''>the</span> <span m=''3199640''>rules</span>
  <span m=''3199890''>of</span> <span m=''3199950''>the</span> <span m=''3200030''>game</span>
  <span m=''3200260''>here</span> <span m=''3200410''>are</span> <span m=''3200510''>different</span>
  <span m=''3200970''>from</span> <span m=''3201290''>origami.</span> <span m=''3201660''>With</span>
  <span m=''3202030''>origami,</span> <span m=''3202570''>we</span> <span m=''3202670''>showed</span>
  <span m=''3203520''>from</span> <span m=''3203740''>any</span> <span m=''3203870''>shape,</span>
  <span m=''3204250''>you</span> <span m=''3204370''>can</span> <span m=''3204490''>make</span>
  <span m=''3204680''>anything</span> <span m=''3205490''>if</span> <span m=''3205540''>you</span>
  <span m=''3205650''>scale</span> <span m=''3205940''>it</span> <span m=''3206000''>down.</span>
  <span m=''3207350''>But</span> <span m=''3207570''>here,</span> <span m=''3208020''>I</span>
  <span m=''3208130''>really</span> <span m=''3208430''>want</span> <span m=''3208670''>exact</span>
  <span m=''3209120''>coverage.</span> <span m=''3209840''>Every</span> <span m=''3210500''>point</span>
  <span m=''3210840''>here,</span> <span m=''3212236''>or</span> <span m=''3212690''>let''s</span>
  <span m=''3212870''>say</span> <span m=''3213000''>every</span> <span m=''3213210''>little</span>
  <span m=''3213390''>patch</span> <span m=''3213830''>here,</span> <span m=''3214360''>should</span>
  <span m=''3214520''>be</span> <span m=''3214630''>covered</span> <span m=''3214950''>by</span>
  <span m=''3215140''>exactly</span> <span m=''3215670''>one</span> <span m=''3216390''>layer</span>
  <span m=''3216800''>over</span> <span m=''3216980''>here,</span> <span m=''3217800''>not</span>
  <span m=''3218030''>allowing</span> <span m=''3218340''>multiple</span> <span m=''3218660''>layers.</span>
  <span m=''3219330''>So</span> <span m=''3219410''>this</span> <span m=''3219590''>means</span>
  <span m=''3219910''>not</span> <span m=''3220060''>everything</span> <span m=''3220340''>is</span>
  <span m=''3220460''>possible.</span> <span m=''3221590''>I also</span> <span m=''3221840''>care</span>
  <span m=''3221990''>about</span> <span m=''3222180''>scale</span> <span m=''3222420''>factor,</span>
  <span m=''3222870''>but--</span> </p><p><span m=''3223950''>This</span> <span m=''3224170''>one,</span>
  <span m=''3224330''>of</span> <span m=''3224420''>course,</span> <span m=''3224850''>you</span>
  <span m=''3224900''>can</span> <span m=''3225000''>crease</span> <span m=''3225330''>like</span>
  <span m=''3225520''>this,</span> <span m=''3226190''>and</span> <span m=''3226370''>more</span>
  <span m=''3227070''>importantly,</span> <span m=''3227640''>you</span> <span m=''3227780''>glue</span>
  <span m=''3228190''>these</span> <span m=''3228480''>edges</span> <span m=''3228790''>together.</span>
  <span m=''3229600''>You</span> <span m=''3229720''>glue</span> <span m=''3230030''>these</span>
  <span m=''3230270''>edges</span> <span m=''3230770''>together.</span> <span m=''3231240''>The</span>
  <span m=''3231340''>opposite</span> <span m=''3231840''>of</span> <span m=''3232040''>cutting</span>
  <span m=''3232410''>is</span> <span m=''3232540''>gluing.</span> <span m=''3234820''>We''ll</span>
  <span m=''3235000''>be</span> <span m=''3235150''>more</span> <span m=''3235340''>formal</span>
  <span m=''3235650''>about</span> <span m=''3235880''>defining</span> <span m=''3236200''>gluing,</span>
  <span m=''3236520''>I</span> <span m=''3236560''>think,</span> <span m=''3236730''>next</span>
  <span m=''3237650''>lecture.</span> <span m=''3238520''>This is</span> <span m=''3238610''>just</span>
  <span m=''3238860''>a</span> <span m=''3239140''>sort of</span> <span m=''3239220''>prelude.</span>
  </p><p><span m=''3240810''>But</span> <span m=''3241130''>you</span> <span m=''3241270''>end</span>
  <span m=''3241440''>up</span> <span m=''3241620''>gluing--</span> <span m=''3242230''>I</span>
  <span m=''3242330''>want</span> <span m=''3242540''>to</span> <span m=''3242580''>make</span>
  <span m=''3242760''>something,</span> <span m=''3243440''>let''s</span> <span m=''3243640''>say--</span>
  <span m=''3244720''>in fact,</span> <span m=''3245010''>we''re</span> <span m=''3245160''>always</span>
  <span m=''3245280''>going</span> <span m=''3245380''>to</span> <span m=''3245470''>talk</span>
  <span m=''3245710''>about</span> <span m=''3245930''>folding</span> <span m=''3246310''>convex</span>
  <span m=''3246930''>polyhedra.</span> <span m=''3248820''>There''s</span> <span
  m=''3249090''>very</span> <span m=''3249320''>little</span> <span m=''3249680''>work</span>
  <span m=''3250020''>on</span> <span m=''3250310''>the</span> <span m=''3250820''>non-convex</span>
  <span m=''3251460''>case,</span> <span m=''3254700''>though,</span> <span m=''3254820''>there</span>
  <span m=''3254920''>was</span> <span m=''3255110''>actually a</span> <span m=''3255360''>recent</span>
  <span m=''3255620''>result.</span> <span m=''3256250''>I''ll</span> <span m=''3256320''>mention</span>
  <span m=''3256660''>that</span> <span m=''3257440''>next</span> <span m=''3257610''>lecture.</span>
  </p><p><span m=''3259690''>If</span> <span m=''3259810''>you</span> <span m=''3259930''>want</span>
  <span m=''3260030''>to</span> <span m=''3260070''>make</span> <span m=''3260210''>something</span>
  <span m=''3260460''>convex,</span> <span m=''3260960''>and</span> <span m=''3261030''>therefore,</span>
  <span m=''3261470''>sphere-like,</span> <span m=''3262060''>you</span> <span m=''3262280''>have</span>
  <span m=''3262510''>to</span> <span m=''3262690''>get</span> <span m=''3262860''>rid</span>
  <span m=''3262990''>of</span> <span m=''3263090''>all</span> <span m=''3263230''>the</span>
  <span m=''3263290''>boundary,</span> <span m=''3264510''>so</span> <span m=''3264650''>you''ve</span>
  <span m=''3264740''>got</span> <span m=''3264900''>a</span> <span m=''3264960''>glue</span>
  <span m=''3265400''>every</span> <span m=''3265890''>edge.</span> <span m=''3266370''>You</span>
  <span m=''3266460''>don''t</span> <span m=''3266610''>have</span> <span m=''3266720''>to</span>
  <span m=''3266800''>glue</span> <span m=''3267250''>whole</span> <span m=''3267505''>edges
  to whole</span> <span m=''3267760''>edges.</span> <span m=''3268010''>Maybe</span>
  <span m=''3268280''>you just</span> <span m=''3268470''>glue</span> <span m=''3268590''>part</span>
  <span m=''3268810''>of</span> <span m=''3268890''>an</span> <span m=''3268980''>edge</span>
  <span m=''3269180''>to</span> <span m=''3269320''>another</span> <span m=''3269580''>part</span>
  <span m=''3269770''>of</span> <span m=''3269850''>an</span> <span m=''3269940''>edge,</span>
  <span m=''3270170''>but</span> <span m=''3270300''>somehow,</span> <span m=''3271120''>boundary</span>
  <span m=''3271390''>has</span> <span m=''3271580''>to</span> <span m=''3271660''>get</span>
  <span m=''3271790''>glued</span> <span m=''3272030''>up.</span> <span m=''3272650''>And</span>
  <span m=''3272790''>if</span> <span m=''3272870''>you</span> <span m=''3272980''>want</span>
  <span m=''3273120''>something</span> <span m=''3273360''>sphere-like,</span> <span
  m=''3273850''>in</span> <span m=''3273940''>fact,</span> <span m=''3274140''>those</span>
  <span m=''3274310''>gluings</span> <span m=''3274610''>have</span> <span m=''3274750''>to</span>
  <span m=''3274840''>be</span> <span m=''3274940''>non-crossing.</span> <span m=''3275650''>I
  have</span> <span m=''3275830''>to</span> <span m=''3275890''>be</span> <span m=''3275980''>able</span>
  <span m=''3276100''>to</span> <span m=''3276160''>draw</span> <span m=''3276540''>a</span>
  <span m=''3276950''>picture</span> <span m=''3277210''>like</span> <span m=''3277380''>this.</span>
  </p><p><span m=''3278130''>Question</span> <span m=''3278460''>is</span> <span m=''3278600''>when</span>
  <span m=''3278790''>do</span> <span m=''3278870''>these</span> <span m=''3279070''>gluings</span>
  <span m=''3279940''>make</span> <span m=''3280170''>a</span> <span m=''3280230''>polyhedron?</span>
  <span m=''3281840''>That</span> <span m=''3282020''>is</span> <span m=''3282190''>the</span>
  <span m=''3282370''>question</span> <span m=''3282730''>we will</span> <span m=''3282880''>be</span>
  <span m=''3283010''>answering</span> <span m=''3283300''>next</span> <span m=''3283530''>class.</span>
  <span m=''3284870''>But</span> <span m=''3285330''>first</span> <span m=''3285630''>question</span>
  <span m=''3285950''>is</span> <span m=''3286070''>suppose</span> <span m=''3286460''>I</span>
  <span m=''3286520''>gave</span> <span m=''3286860''>you</span> <span m=''3287020''>one</span>
  <span m=''3287160''>of</span> <span m=''3287210''>these</span> <span m=''3287380''>pictures.</span>
  <span m=''3287930''>I</span> <span m=''3288000''>give</span> <span m=''3288220''>you</span>
  <span m=''3288300''>a</span> <span m=''3288340''>polygon,</span> <span m=''3289240''>and</span>
  <span m=''3289400''>I</span> <span m=''3289450''>give</span> <span m=''3289630''>you
  a</span> <span m=''3289770''>gluing.</span> <span m=''3290200''>What</span> <span
  m=''3290380''>this</span> <span m=''3290560''>tells</span> <span m=''3290840''>you</span>
  <span m=''3291020''>is</span> <span m=''3291110''>sort</span> <span m=''3291270''>of</span>
  <span m=''3291340''>how</span> <span m=''3291530''>to</span> <span m=''3291580''>locally</span>
  <span m=''3291970''>walk</span> <span m=''3292335''>around.</span> </p><p><span
  m=''3294030''>So</span> <span m=''3294250''>if</span> <span m=''3294340''>I''m</span>
  <span m=''3294450''>here,</span> <span m=''3295240''>I</span> <span m=''3295300''>could</span>
  <span m=''3295490''>walk</span> <span m=''3295910''>over</span> <span m=''3296270''>here.</span>
  <span m=''3297060''>I could</span> <span m=''3297160''>walk</span> <span m=''3297470''>over</span>
  <span m=''3297770''>here,</span> <span m=''3298560''>teleport</span> <span m=''3299130''>over</span>
  <span m=''3299320''>there,</span> <span m=''3300240''>walk</span> <span m=''3300570''>over</span>
  <span m=''3300820''>here,</span> <span m=''3301080''>teleport</span> <span m=''3301540''>over</span>
  <span m=''3301780''>here.</span> <span m=''3302520''>Whatever.</span> <span m=''3303470''>OK?</span>
  <span m=''3303910''>The gluing</span> <span m=''3304290''>tells</span> <span m=''3304510''>you</span>
  <span m=''3305170''>locally</span> <span m=''3305580''>what</span> <span m=''3305730''>the</span>
  <span m=''3305830''>surface</span> <span m=''3306210''>looks</span> <span m=''3306410''>like,</span>
  <span m=''3306720''>even</span> <span m=''3306940''>though</span> <span m=''3307040''>you</span>
  <span m=''3307170''>don''t</span> <span m=''3307350''>know</span> <span m=''3307500''>what</span>
  <span m=''3307600''>it</span> <span m=''3307650''>looks</span> <span m=''3307860''>like</span>
  <span m=''3308040''>yet</span> <span m=''3308150''>in</span> <span m=''3308260''>3D.</span>
  </p><p><span m=''3309400''>In</span> <span m=''3309540''>particular,</span> <span
  m=''3310180''>you</span> <span m=''3310240''>can</span> <span m=''3310370''>compute</span>
  <span m=''3310690''>shortest</span> <span m=''3311060''>paths</span> <span m=''3311400''>here.</span>
  <span m=''3313320''>I</span> <span m=''3313430''>could</span> <span m=''3313630''>compute</span>
  <span m=''3313970''>the</span> <span m=''3314230''>shortest</span> <span m=''3314490''>path</span>
  <span m=''3315160''>from</span> <span m=''3315340''>this</span> <span m=''3315550''>point</span>
  <span m=''3315920''>to</span> <span m=''3316010''>this</span> <span m=''3316220''>point</span>
  <span m=''3316430''>you</span> <span m=''3316500''>might</span> <span m=''3316730''>think</span>
  <span m=''3316950''>is</span> <span m=''3317410''>a</span> <span m=''3317440''>straight</span>
  <span m=''3317820''>line.</span> <span m=''3318790''>But</span> <span m=''3318970''>no,</span>
  <span m=''3320490''>it''s</span> <span m=''3320680''>not.</span> <span m=''3324375''>I</span>
  <span m=''3324800''>don''t</span> <span m=''3324980''>think.</span> <span m=''3325160''>Or</span>
  <span m=''3325250''>maybe</span> <span m=''3325500''>it</span> <span m=''3325580''>is.</span>
  <span m=''3326410''>Let''s</span> <span m=''3326680''>see.</span> <span m=''3327812''>A</span>
  <span m=''3328300''>little</span> <span m=''3328500''>tricky.</span> </p><p><span
  m=''3331310''>AUDIENCE: Should</span> <span m=''3331774''>be</span> <span m=''3332238''>diagonal</span>
  <span m=''3332702''>with the</span> <span m=''3333166''>bottom</span> <span m=''3333630''>square.</span>
  </p><p><span m=''3334558''>PROFESSOR: Diagonal</span> <span m=''3335030''>with the</span>
  <span m=''3335070''>bottom</span> <span m=''3335620''>square</span> <span m=''3335890''>because</span>
  <span m=''3336060''>these</span> <span m=''3336220''>guys</span> <span m=''3336400''>are</span>
  <span m=''3336470''>both</span> <span m=''3336730''>in</span> <span m=''3336790''>the</span>
  <span m=''3336870''>bottom.</span> <span m=''3337310''>Very</span> <span m=''3337530''>good.</span>
  <span m=''3338230''>So</span> <span m=''3338310''>this</span> <span m=''3338500''>point</span>
  <span m=''3338800''>is</span> <span m=''3338980''>the</span> <span m=''3339100''>same</span>
  <span m=''3339650''>as</span> <span m=''3340840''>this</span> <span m=''3341030''>point,</span>
  <span m=''3342010''>or no,</span> <span m=''3342320''>this</span> <span m=''3342530''>point.</span>
  <span m=''3343820''>Because</span> <span m=''3344270''>these</span> <span m=''3344480''>get
  zipped</span> <span m=''3344960''>together.</span> <span m=''3346190''>This</span>
  <span m=''3346420''>point</span> <span m=''3346790''>is</span> <span m=''3346910''>the</span>
  <span m=''3346980''>same</span> <span m=''3347280''>as</span> <span m=''3347470''>this</span>
  <span m=''3347690''>point,</span> <span m=''3348840''>so</span> <span m=''3348990''>in</span>
  <span m=''3349060''>fact,</span> <span m=''3350050''>that</span> <span m=''3350270''>diagonal</span>
  <span m=''3350780''>is</span> <span m=''3350960''>the</span> <span m=''3351010''>shortest</span>
  <span m=''3351350''>path</span> <span m=''3351820''>between</span> <span m=''3352190''>those</span>
  <span m=''3352360''>two</span> <span m=''3352490''>points.</span> <span m=''3353360''>So</span>
  <span m=''3353510''>you</span> <span m=''3353900''>have</span> <span m=''3354010''>to</span>
  <span m=''3354120''>think</span> <span m=''3354300''>about</span> <span m=''3354510''>it</span>
  <span m=''3354600''>for</span> <span m=''3354680''>a</span> <span m=''3354720''>while,</span>
  <span m=''3355060''>but</span> <span m=''3355480''>it</span> <span m=''3355520''>turns</span>
  <span m=''3355760''>out,</span> <span m=''3355890''>in</span> <span m=''3355950''>polynomial</span>
  <span m=''3356450''>time,</span> <span m=''3356690''>you</span> <span m=''3356810''>can</span>
  <span m=''3356950''>do</span> <span m=''3357060''>that.</span> <span m=''3359890''>That''s</span>
  <span m=''3359940''>cool.</span> </p><p><span m=''3362070''>What</span> <span m=''3362260''>I</span>
  <span m=''3362320''>want</span> <span m=''3362480''>to</span> <span m=''3362530''>show</span>
  <span m=''3362720''>now</span> <span m=''3365430''>is</span> <span m=''3365660''>that</span>
  <span m=''3368260''>suppose</span> <span m=''3368670''>you</span> <span m=''3368800''>could</span>
  <span m=''3369030''>make</span> <span m=''3369220''>a</span> <span m=''3369300''>convex</span>
  <span m=''3369700''>polyhedron</span> <span m=''3370180''>in</span> <span m=''3370270''>this</span>
  <span m=''3370440''>way.</span> <span m=''3370860''>I</span> <span m=''3371010''>claim</span>
  <span m=''3371620''>you</span> <span m=''3371760''>can</span> <span m=''3371930''>only</span>
  <span m=''3372210''>make</span> <span m=''3372440''>one,</span> <span m=''3373420''>never</span>
  <span m=''3373730''>more</span> <span m=''3373970''>than</span> <span m=''3374110''>one</span>
  <span m=''3374370''>from</span> <span m=''3374560''>the</span> <span m=''3374660''>same</span>
  <span m=''3374950''>gluing.</span> <span m=''3376440''>So</span> <span m=''3376800''>I''ve</span>
  <span m=''3376980''>defined</span> <span m=''3377350''>locally</span> <span m=''3377780''>what</span>
  <span m=''3377940''>this</span> <span m=''3378100''>thing</span> <span m=''3378280''>is.</span>
  <span m=''3378410''>It''s</span> <span m=''3378570''>like</span> <span m=''3378720''>a</span>
  <span m=''3378780''>piece</span> <span m=''3379030''>of</span> <span m=''3379110''>paper.</span>
  <span m=''3379500''>I</span> <span m=''3379520''>can</span> <span m=''3379940''>mangle</span>
  <span m=''3380130''>it around.</span> <span m=''3380710''>If</span> <span m=''3380880''>I</span>
  <span m=''3380940''>want</span> <span m=''3381180''>to</span> <span m=''3381230''>make</span>
  <span m=''3381410''>something</span> <span m=''3381700''>convex,</span> <span m=''3382760''>there''s</span>
  <span m=''3382890''>only</span> <span m=''3383130''>one</span> <span m=''3383440''>thing</span>
  <span m=''3383650''>it</span> <span m=''3383720''>could</span> <span m=''3383850''>possibly</span>
  <span m=''3384360''>make.</span> </p><p><span m=''3391290''>Finding</span> <span
  m=''3391740''>out</span> <span m=''3391980''>what that</span> <span m=''3392150''>one</span>
  <span m=''3392320''>thing</span> <span m=''3392510''>is</span> <span m=''3392850''>quite</span>
  <span m=''3393040''>a</span> <span m=''3393090''>challenge,</span> <span m=''3394390''>but</span>
  <span m=''3394580''>at</span> <span m=''3394965''>least,</span> <span m=''3395350''>we</span>
  <span m=''3395500''>can</span> <span m=''3395640''>prove</span> <span m=''3395880''>that</span>
  <span m=''3395980''>it''s</span> <span m=''3396140''>unique.</span> <span m=''3397826''>Sorry</span>
  <span m=''3398310''>about the</span> <span m=''3398600''>screeching.</span> <span
  m=''3401830''>This</span> <span m=''3402040''>is</span> <span m=''3402480''>Cauchy''s</span>
  <span m=''3402730''>rigidity</span> <span m=''3403200''>theorem.</span> <span m=''3405190''>I</span>
  <span m=''3405260''>think</span> <span m=''3405410''>we</span> <span m=''3405520''>mentioned
  it</span> <span m=''3405880''>in</span> <span m=''3406270''>a</span> <span m=''3406330''>previous</span>
  <span m=''3409490''>lecture</span> <span m=''3409750''>when we</span> <span m=''3410010''>were</span>
  <span m=''3410190''>talking</span> <span m=''3410430''>about</span> <span m=''3410590''>rigidity</span>
  <span m=''3411310''>and</span> <span m=''3411680''>three</span> <span m=''3411860''>dimensions</span>
  <span m=''3412266''>and</span> <span m=''3413870''>like</span> <span m=''3414040''>why</span>
  <span m=''3414260''>domes</span> <span m=''3414600''>stand</span> <span m=''3415020''>up.</span>
  <span m=''3416380''>But</span> <span m=''3416520''>now,</span> <span m=''3416710''>we''re</span>
  <span m=''3416800''>going</span> <span m=''3416910''>to</span> <span m=''3416950''>use</span>
  <span m=''3417240''>it.</span> <span m=''3417460''>We''re</span> <span m=''3417570''>actually</span>
  <span m=''3417790''>going</span> <span m=''3417870''>to</span> <span m=''3417930''>prove</span>
  <span m=''3418150''>this</span> <span m=''3418320''>theorem,</span> <span m=''3418750''>and</span>
  <span m=''3418970''>we''re</span> <span m=''3419110''>going</span> <span m=''3419340''>to</span>
  <span m=''3419380''>use</span> <span m=''3419640''>it</span> <span m=''3419790''>to</span>
  <span m=''3420030''>study</span> <span m=''3420380''>these</span> <span m=''3420590''>kinds</span>
  <span m=''3420790''>of</span> <span m=''3420860''>gluings</span> <span m=''3421140''>and</span>
  <span m=''3421270''>say</span> <span m=''3421910''>there''s,</span> <span m=''3422030''>at</span>
  <span m=''3422140''>most,</span> <span m=''3422470''>one</span> <span m=''3422710''>way</span>
  <span m=''3422920''>to</span> <span m=''3423060''>do</span> <span m=''3423200''>this.</span>
  </p><p><span m=''3424960''>There''s</span> <span m=''3425080''>a</span> <span m=''3425130''>lot</span>
  <span m=''3425280''>of</span> <span m=''3425340''>ways</span> <span m=''3425530''>to</span>
  <span m=''3425600''>state</span> <span m=''3425850''>this</span> <span m=''3426010''>theorem,</span>
  <span m=''3426300''>but</span> <span m=''3426550''>one</span> <span m=''3426780''>way</span>
  <span m=''3426990''>is</span> <span m=''3427110''>to</span> <span m=''3427150''>say,</span>
  <span m=''3427590''>suppose</span> <span m=''3428080''>you</span> <span m=''3428170''>have</span>
  <span m=''3428400''>two</span> <span m=''3428610''>convex</span> <span m=''3429060''>polyhedra,</span>
  <span m=''3431400''>and</span> <span m=''3431590''>suppose</span> <span m=''3431990''>they</span>
  <span m=''3432110''>came</span> <span m=''3432550''>from</span> <span m=''3432770''>the</span>
  <span m=''3432900''>same</span> <span m=''3433610''>sort</span> <span m=''3433810''>of</span>
  <span m=''3433890''>intrinsic</span> <span m=''3436420''>geometry.</span> <span
  m=''3437580''>So</span> <span m=''3437750''>there''s</span> <span m=''3438530''>the</span>
  <span m=''3438630''>geometry</span> <span m=''3439080''>of the</span> <span m=''3439170''>faces,</span>
  <span m=''3440450''>and</span> <span m=''3440840''>there''s</span> <span m=''3441020''>how</span>
  <span m=''3441240''>they''re</span> <span m=''3441360''>connected</span> <span m=''3441750''>together.</span>
  <span m=''3443060''>So</span> <span m=''3443070''>here,</span> <span m=''3443770''>initially,</span>
  <span m=''3444200''>I</span> <span m=''3444250''>drew</span> <span m=''3444440''>a</span>
  <span m=''3444490''>tree</span> <span m=''3444920''>of</span> <span m=''3445010''>how</span>
  <span m=''3445160''>the</span> <span m=''3445250''>faces</span> <span m=''3445510''>were</span>
  <span m=''3445620''>connected</span> <span m=''3446000''>together,</span> <span
  m=''3446980''>and</span> <span m=''3447200''>then,</span> <span m=''3447500''>I</span>
  <span m=''3448560''>drew</span> <span m=''3448690''>some</span> <span m=''3448880''>other</span>
  <span m=''3449100''>connections</span> <span m=''3450190''>like</span> <span m=''3450320''>this.</span>
  <span m=''3450820''>So</span> <span m=''3450890''>the</span> <span m=''3451000''>dual</span>
  <span m=''3451230''>here</span> <span m=''3451400''>is,</span> <span m=''3451500''>of</span>
  <span m=''3451620''>course,</span> <span m=''3451830''>an</span> <span m=''3451920''>octahedron.</span>
  </p><p><span m=''3453630''>But</span> <span m=''3453810''>if</span> <span m=''3453920''>you</span>
  <span m=''3454010''>have</span> <span m=''3454180''>two</span> <span m=''3454650''>convex</span>
  <span m=''3455000''>polyhedra</span> <span m=''3456960''>and</span> <span m=''3457170''>they</span>
  <span m=''3457370''>are</span> <span m=''3457580''>combinatorally</span> <span m=''3458330''>equivalent,</span>
  <span m=''3459260''>they</span> <span m=''3459360''>have</span> <span m=''3459560''>the</span>
  <span m=''3459650''>same</span> <span m=''3460510''>way</span> <span m=''3460790''>that</span>
  <span m=''3460930''>things</span> <span m=''3461140''>are</span> <span m=''3461210''>connected</span>
  <span m=''3461570''>together,</span> <span m=''3462030''>the</span> <span m=''3462090''>same</span>
  <span m=''3462300''>graph,</span> <span m=''3468420''>and</span> <span m=''3469640''>they</span>
  <span m=''3469760''>have</span> <span m=''3469940''>congruent</span> <span m=''3470430''>faces,</span>
  <span m=''3471710''>so</span> <span m=''3471860''>the</span> <span m=''3471960''>geometries</span>
  <span m=''3472500''>match</span> <span m=''3472810''>also,</span> <span m=''3476170''>then,</span>
  <span m=''3476880''>they</span> <span m=''3477060''>are</span> <span m=''3477200''>actually</span>
  <span m=''3477470''>the</span> <span m=''3477590''>same</span> <span m=''3477820''>thing,</span>
  <span m=''3484980''>the</span> <span m=''3485040''>same</span> <span m=''3485380''>polyhedron.</span>
  </p><p><span m=''3486954''>AUDIENCE: Is</span> <span m=''3487411''>that</span> <span
  m=''3487868''>something</span> <span m=''3488325''>that--</span> </p><p><span m=''3491070''>PROFESSOR:
  Up</span> <span m=''3491230''>to</span> <span m=''3491540''>rotation</span> <span
  m=''3492840''>and</span> <span m=''3493000''>translation.</span> </p><p><span m=''3494137''>AUDIENCE:
  Is it the</span> <span m=''3494624''>same set</span> <span m=''3495111''>of</span>
  <span m=''3495598''>congruent</span> <span m=''3496085''>faces?</span> </p><p><span
  m=''3497550''>PROFESSOR: Oh,</span> <span m=''3497720''>yeah.</span> <span m=''3498050''>So</span>
  <span m=''3498250''>when</span> <span m=''3498380''>I</span> <span m=''3498460''>say</span>
  <span m=''3498610''>congruent</span> <span m=''3498980''>faces,</span> <span m=''3499330''>I</span>
  <span m=''3499370''>mean</span> <span m=''3499520''>according</span> <span m=''3499910''>to</span>
  <span m=''3499990''>this</span> <span m=''3500160''>equivalence.</span> <span m=''3501150''>If
  you</span> <span m=''3501250''>take</span> <span m=''3501450''>a</span> <span m=''3501510''>face</span>
  <span m=''3501810''>on</span> <span m=''3501890''>one</span> <span m=''3502150''>that</span>
  <span m=''3502380''>has</span> <span m=''3502600''>a</span> <span m=''3502650''>corresponding</span>
  <span m=''3503170''>face</span> <span m=''3503410''>on</span> <span m=''3503480''>the</span>
  <span m=''3503590''>other,</span> <span m=''3504250''>those</span> <span m=''3504470''>two
  faces</span> <span m=''3504880''>should</span> <span m=''3505050''>be</span> <span
  m=''3505190''>congruent,</span> <span m=''3505580''>not</span> <span m=''3505760''>just</span>
  <span m=''3505940''>any</span> <span m=''3506110''>pair,</span> <span m=''3507100''>and</span>
  <span m=''3507250''>they''re</span> <span m=''3507330''>not</span> <span m=''3507500''>all</span>
  <span m=''3507690''>the</span> <span m=''3507780''>same.</span> <span m=''3508860''>Different</span>
  <span m=''3509330''>faces</span> <span m=''3509680''>can</span> <span m=''3509800''>be</span>
  <span m=''3509900''>different,</span> <span m=''3510380''>but</span> <span m=''3510570''>they''re</span>
  <span m=''3511010''>identical</span> <span m=''3511460''>in</span> <span m=''3511540''>pairs.</span>
  </p><p><span m=''3513450''>So</span> <span m=''3513470''>I''m</span> <span m=''3513570''>just</span>
  <span m=''3513700''>saying</span> <span m=''3515860''>basically,</span> <span m=''3516180''>if</span>
  <span m=''3516220''>you</span> <span m=''3516310''>have</span> <span m=''3516470''>this</span>
  <span m=''3516620''>picture,</span> <span m=''3516930''>there''s</span> <span m=''3517120''>only</span>
  <span m=''3517320''>one</span> <span m=''3517510''>realization.</span> <span m=''3518330''>So</span>
  <span m=''3518480''>this</span> <span m=''3518660''>picture</span> <span m=''3518960''>defines</span>
  <span m=''3519850''>what</span> <span m=''3520040''>are</span> <span m=''3520070''>the</span>
  <span m=''3520200''>geometry</span> <span m=''3520650''>of the</span> <span m=''3520740''>faces,</span>
  <span m=''3521450''>how</span> <span m=''3521670''>are</span> <span m=''3521740''>they</span>
  <span m=''3521860''>connected</span> <span m=''3522230''>together.</span> <span
  m=''3523810''>And</span> <span m=''3524140''>so</span> <span m=''3524310''>if</span>
  <span m=''3524410''>you</span> <span m=''3524490''>had</span> <span m=''3524770''>two</span>
  <span m=''3524990''>convex</span> <span m=''3525380''>polyhedra</span> <span m=''3525800''>with</span>
  <span m=''3525920''>that</span> <span m=''3526110''>same</span> <span m=''3526510''>underlying</span>
  <span m=''3526940''>diagram,</span> <span m=''3527880''>they</span> <span m=''3528000''>have</span>
  <span m=''3528290''>to</span> <span m=''3528390''>be</span> <span m=''3528480''>the</span>
  <span m=''3528590''>same</span> <span m=''3528890''>polyhedron.</span> <span m=''3529890''>That''s</span>
  <span m=''3530110''>what</span> <span m=''3530420''>we''re</span> <span m=''3531000''>claiming.</span>
  <span m=''3533470''>That''s</span> <span m=''3533755''>what we''re going to</span>
  <span m=''3534040''>prove.</span> </p><p><span m=''3544591''>Is this one any</span>
  <span m=''3545090''>better?</span> <span m=''3545750''>Yeah,</span> <span m=''3545950''>it''s
  better.</span> <span m=''3556420''>This</span> <span m=''3556630''>is</span> <span
  m=''3556730''>an</span> <span m=''3556800''>old</span> <span m=''3557020''>theorem.</span>
  <span m=''3558370''>You</span> <span m=''3558820''>may</span> <span m=''3558920''>have</span>
  <span m=''3559010''>heard</span> <span m=''3559150''>of</span> <span m=''3559240''>Cauchy,</span>
  <span m=''3559690''>famous</span> <span m=''3560160''>French</span> <span m=''3560460''>mathematician.</span>
  <span m=''3561820''>Cauchy-Schwarz</span> <span m=''3562430''>inequality,</span>
  <span m=''3563550''>all those</span> <span m=''3563810''>good</span> <span m=''3563960''>things.</span>
  <span m=''3564890''>You don''t</span> <span m=''3564950''>need</span> <span m=''3565110''>to</span>
  <span m=''3565200''>know</span> <span m=''3565330''>those.</span> <span m=''3565470''>He
  proved</span> <span m=''3565830''>a</span> <span m=''3565890''>lot</span> <span
  m=''3566080''>of</span> <span m=''3566140''>things.</span> </p><p><span m=''3567240''>This</span>
  <span m=''3567690''>theorem</span> <span m=''3567930''>he</span> <span m=''3568030''>didn''t</span>
  <span m=''3568220''>actually</span> <span m=''3568500''>prove.</span> <span m=''3569480''>He</span>
  <span m=''3569760''>wrote</span> <span m=''3569810''>a</span> <span m=''3569860''>paper</span>
  <span m=''3570270''>about</span> <span m=''3570540''>it</span> <span m=''3570630''>or,</span>
  <span m=''3570830''>I</span> <span m=''3570900''>think,</span> <span m=''3571270''>partly</span>
  <span m=''3571580''>a</span> <span m=''3571630''>letter,</span> <span m=''3571880''>partly</span>
  <span m=''3572060''>a</span> <span m=''3572220''>paper</span> <span m=''3572560''>in</span>
  <span m=''3572660''>1813.</span> <span m=''3574890''>Proof</span> <span m=''3575120''>was</span>
  <span m=''3575240''>wrong,</span> <span m=''3576160''>and</span> <span m=''3576390''>it</span>
  <span m=''3576450''>was</span> <span m=''3576630''>fixed</span> <span m=''3577590''>in</span>
  <span m=''3577740''>1934,</span> <span m=''3578730''>over</span> <span m=''3578900''>100</span>
  <span m=''3579190''>years</span> <span m=''3579420''>later,</span> <span m=''3580170''>by</span>
  <span m=''3580320''>Steinitz.</span> <span m=''3581010''>So</span> <span m=''3581190''>sometimes</span>
  <span m=''3581640''>it''s</span> <span m=''3581780''>called</span> <span m=''3582120''>Cauchy-Steinitz</span>
  <span m=''3584400''>rigidity</span> <span m=''3584880''>theorem,</span> <span m=''3585280''>although,
  usually,</span> <span m=''3585560''>Cauchy.</span> <span m=''3587250''>There''s</span>
  <span m=''3587410''>a</span> <span m=''3587490''>lemma</span> <span m=''3587680''>in</span>
  <span m=''3587940''>here</span> <span m=''3588180''>that''s</span> <span m=''3588960''>often</span>
  <span m=''3589200''>attributed</span> <span m=''3589620''>to</span> <span m=''3589730''>both</span>
  <span m=''3589980''>of</span> <span m=''3590050''>them.</span> </p><p><span m=''3595190''>So</span>
  <span m=''3599148''>it''s</span> <span m=''3599590''>sort of a</span> <span m=''3599920''>proof</span>
  <span m=''3600140''>by</span> <span m=''3600260''>contradiction.</span> <span m=''3600550''>We</span>
  <span m=''3600840''>want</span> <span m=''3600970''>to</span> <span m=''3601020''>prove</span>
  <span m=''3601230''>uniqueness.</span> <span m=''3602490''>So</span> <span m=''3602700''>we''re</span>
  <span m=''3602830''>supposing,</span> <span m=''3603910''>well,</span> <span m=''3603960''>maybe,</span>
  <span m=''3604240''>there''s</span> <span m=''3604420''>two</span> <span m=''3604600''>polyhedra,</span>
  <span m=''3605940''>p</span> <span m=''3606740''>and</span> <span m=''3606930''>p</span>
  <span m=''3607100''>prime,</span> <span m=''3609180''>and</span> <span m=''3609270''>they''re</span>
  <span m=''3609510''>combinatory</span> <span m=''3610000''>equivalent</span> <span
  m=''3610470''>and</span> <span m=''3610550''>have</span> <span m=''3610910''>matching</span>
  <span m=''3611340''>faces</span> <span m=''3611710''>congruent.</span> <span m=''3615370''>What</span>
  <span m=''3615540''>I</span> <span m=''3615600''>want</span> <span m=''3615790''>to</span>
  <span m=''3615870''>do</span> <span m=''3620930''>is</span> <span m=''3621150''>look</span>
  <span m=''3621390''>at</span> <span m=''3621520''>corresponding</span> <span m=''3622130''>vertices,</span>
  <span m=''3624890''>let''s</span> <span m=''3625030''>say a</span> <span m=''3625170''>vertex</span>
  <span m=''3625640''>v</span> <span m=''3626110''>and</span> <span m=''3626360''>p</span>
  <span m=''3627360''>and</span> <span m=''3627560''>a</span> <span m=''3627610''>vertex</span>
  <span m=''3628080''>v</span> <span m=''3628300''>prime</span> <span m=''3628900''>and</span>
  <span m=''3629090''>p</span> <span m=''3629270''>prime.</span> <span m=''3630760''>So</span>
  <span m=''3630920''>there</span> <span m=''3631280''>corresponding</span> <span
  m=''3632020''>in</span> <span m=''3632160''>the</span> <span m=''3632300''>combinatorial</span>
  <span m=''3632870''>equivalence.</span> </p><p><span m=''3635170''>And</span> <span
  m=''3635360''>then,</span> <span m=''3635710''>I</span> <span m=''3635870''>want</span>
  <span m=''3636210''>to</span> <span m=''3636860''>slice</span> <span m=''3639260''>the</span>
  <span m=''3639370''>polyhedra,</span> <span m=''3640930''>p and</span> <span m=''3641220''>p</span>
  <span m=''3641510''>prime,</span> <span m=''3644600''>with</span> <span m=''3646170''>an</span>
  <span m=''3646400''>epsilon</span> <span m=''3647180''>sphere,</span> <span m=''3649820''>epsilon</span>
  <span m=''3650190''>radius</span> <span m=''3650560''>sphere</span> <span m=''3651300''>centered</span>
  <span m=''3654260''>at</span> <span m=''3654600''>v</span> <span m=''3654920''>and</span>
  <span m=''3655010''>v</span> <span m=''3655180''>prime.</span> <span m=''3662460''>Quick</span>
  <span m=''3662680''>mention,</span> <span m=''3663270''>this</span> <span m=''3663460''>is</span>
  <span m=''3663550''>not</span> <span m=''3663790''>true</span> <span m=''3664490''>if</span>
  <span m=''3664630''>you</span> <span m=''3664750''>allow</span> <span m=''3664880''>non-convex</span>
  <span m=''3665510''>realizations.</span> <span m=''3666500''>You</span> <span m=''3666770''>may
  have</span> <span m=''3667100''>seen</span> <span m=''3667190''>that</span> <span
  m=''3667330''>example</span> <span m=''3667720''>before.</span> <span m=''3668770''>These</span>
  <span m=''3669270''>have</span> <span m=''3669380''>exactly</span> <span m=''3669830''>the</span>
  <span m=''3669900''>same</span> <span m=''3670110''>combinatorial</span> <span m=''3670630''>structure,</span>
  <span m=''3671910''>same</span> <span m=''3672160''>geometry</span> <span m=''3672940''>on</span>
  <span m=''3673100''>each</span> <span m=''3673260''>face,</span> <span m=''3674140''>but</span>
  <span m=''3674320''>one''s</span> <span m=''3674530''>non-convex,</span> <span m=''3675180''>and</span>
  <span m=''3675270''>they''re</span> <span m=''3675360''>different.</span> <span
  m=''3675740''>But</span> <span m=''3676240''>as</span> <span m=''3676350''>long</span>
  <span m=''3676520''>as</span> <span m=''3676600''>they''re</span> <span m=''3676720''>convex,</span>
  <span m=''3677180''>they''re</span> <span m=''3677280''>going</span> <span m=''3677400''>to</span>
  <span m=''3677470''>be</span> <span m=''3677560''>the</span> <span m=''3677660''>same.</span>
  </p><p><span m=''3678450''>In a</span> <span m=''3678560''>convex</span> <span m=''3678970''>situation,</span>
  <span m=''3679790''>here''s</span> <span m=''3680110''>what</span> <span m=''3680250''>the</span>
  <span m=''3680340''>slice</span> <span m=''3680670''>looks</span> <span m=''3680860''>like.</span>
  <span m=''3681170''>So</span> <span m=''3682250''>here''s</span> <span m=''3682820''>little</span>
  <span m=''3683080''>vertex,</span> <span m=''3684250''>degree</span> <span m=''3684650''>like</span>
  <span m=''3684870''>5,</span> <span m=''3687610''>and</span> <span m=''3687740''>I</span>
  <span m=''3687820''>slice</span> <span m=''3688370''>the</span> <span m=''3688460''>polyhedron</span>
  <span m=''3688980''>with</span> <span m=''3689100''>this</span> <span m=''3689240''>tiny</span>
  <span m=''3689590''>sphere</span> <span m=''3689980''>centered</span> <span m=''3690360''>at</span>
  <span m=''3690470''>v,</span> <span m=''3693110''>not</span> <span m=''3693410''>the</span>
  <span m=''3693550''>interior,</span> <span m=''3694010''>just</span> <span m=''3694180''>the</span>
  <span m=''3694250''>boundary</span> <span m=''3694590''>of</span> <span m=''3694630''>the</span>
  <span m=''3694720''>sphere.</span> <span m=''3695630''>What</span> <span m=''3695790''>I</span>
  <span m=''3695850''>get</span> <span m=''3696090''>are</span> <span m=''3696210''>these</span>
  <span m=''3696650''>arcs.</span> <span m=''3697100''>They''ll</span> <span m=''3697240''>be</span>
  <span m=''3697450''>great</span> <span m=''3697740''>circular</span> <span m=''3698180''>arcs.</span>
  </p><p><span m=''3700130''>Here</span> <span m=''3700370''>we</span> <span m=''3700470''>can
  see all</span> <span m=''3700870''>five</span> <span m=''3701110''>of them.</span>
  <span m=''3702250''>They''re</span> <span m=''3702630''>great</span> <span m=''3702870''>circular</span>
  <span m=''3703260''>arcs.</span> <span m=''3703610''>There</span> <span m=''3703770''>on</span>
  <span m=''3703980''>the</span> <span m=''3704050''>sphere.</span> <span m=''3704990''>I</span>
  <span m=''3705090''>get</span> <span m=''3705220''>a</span> <span m=''3705290''>polygon.</span>
  <span m=''3706680''>I</span> <span m=''3706770''>get</span> <span m=''3706910''>a</span>
  <span m=''3706990''>convex</span> <span m=''3707660''>polygon</span> <span m=''3708270''>on</span>
  <span m=''3708460''>the</span> <span m=''3708550''>sphere.</span> </p><p><span m=''3715030''>Convex</span>
  <span m=''3716770''>spherical</span> <span m=''3717510''>polygons,</span> <span
  m=''3718060''>convex</span> <span m=''3718530''>because</span> <span m=''3718690''>the
  polyhedra</span> <span m=''3719080''>are</span> <span m=''3719240''>convex.</span>
  <span m=''3719840''>I</span> <span m=''3720180''>actually</span> <span m=''3720510''>get</span>
  <span m=''3720660''>two</span> <span m=''3720870''>of</span> <span m=''3720930''>them.</span>
  <span m=''3721130''>Right?</span> <span m=''3721330''>One</span> <span m=''3721490''>for</span>
  <span m=''3721790''>p,</span> <span m=''3722260''>one</span> <span m=''3722550''>for</span>
  <span m=''3722910''>p</span> <span m=''3723080''>prime.</span> <span m=''3724850''>Polygons.</span>
  <span m=''3727960''>What</span> <span m=''3728110''>do</span> <span m=''3728170''>I</span>
  <span m=''3728260''>know</span> <span m=''3728390''>about</span> <span m=''3728600''>those</span>
  <span m=''3728780''>polygons?</span> <span m=''3729500''>I</span> <span m=''3729610''>know</span>
  <span m=''3729800''>they''re</span> <span m=''3729980''>edge</span> <span m=''3730210''>lengths</span>
  <span m=''3731570''>because</span> <span m=''3731830''>the</span> <span m=''3732040''>length</span>
  <span m=''3732490''>of</span> <span m=''3732600''>an</span> <span m=''3732700''>edge</span>
  <span m=''3733050''>here</span> <span m=''3734050''>is</span> <span m=''3734300''>equal</span>
  <span m=''3734660''>to--</span> <span m=''3735100''>if</span> <span m=''3735220''>this</span>
  <span m=''3735380''>is</span> <span m=''3735490''>a</span> <span m=''3735550''>unit</span>
  <span m=''3735970''>sphere,</span> <span m=''3736300''>if I</span> <span m=''3736440''>rescale</span>
  <span m=''3737040''>the</span> <span m=''3737130''>epsilon</span> <span m=''3737560''>to</span>
  <span m=''3737620''>be</span> <span m=''3737760''>1,</span> <span m=''3738800''>that</span>
  <span m=''3739060''>edge</span> <span m=''3739280''>length</span> <span m=''3739850''>is</span>
  <span m=''3740000''>actually</span> <span m=''3740260''>this</span> <span m=''3740500''>angle.</span>
  <span m=''3741660''>That</span> <span m=''3741900''>angle</span> <span m=''3742340''>is</span>
  <span m=''3742500''>an</span> <span m=''3742700''>angle</span> <span m=''3743070''>of</span>
  <span m=''3743210''>the</span> <span m=''3743430''>face</span> <span m=''3744020''>at</span>
  <span m=''3744180''>the</span> <span m=''3744250''>vertex.</span> </p><p><span m=''3745440''>So</span>
  <span m=''3745620''>I</span> <span m=''3745750''>know</span> <span m=''3746090''>all</span>
  <span m=''3746210''>the</span> <span m=''3746340''>angles.</span> <span m=''3746710''>I</span>
  <span m=''3746780''>know</span> <span m=''3746960''>all</span> <span m=''3747080''>the</span>
  <span m=''3747170''>geometries</span> <span m=''3747700''>of</span> <span m=''3747760''>the</span>
  <span m=''3747840''>faces.</span> <span m=''3748310''>I know they''re</span> <span
  m=''3748640''>congruent.</span> <span m=''3749820''>So</span> <span m=''3751390''>I</span>
  <span m=''3751560''>know</span> <span m=''3751800''>what</span> <span m=''3751960''>these
  edge</span> <span m=''3752300''>lengths</span> <span m=''3752560''>are</span> <span
  m=''3752700''>in</span> <span m=''3752770''>the</span> <span m=''3752840''>sphere.</span>
  </p><p><span m=''3754130''>What</span> <span m=''3754270''>I</span> <span m=''3754350''>don''t</span>
  <span m=''3754640''>know</span> <span m=''3754780''>are</span> <span m=''3754900''>these</span>
  <span m=''3755110''>angles</span> <span m=''3756380''>of</span> <span m=''3756520''>the</span>
  <span m=''3756600''>polygon.</span> <span m=''3757080''>I</span> <span m=''3757160''>know</span>
  <span m=''3757290''>the</span> <span m=''3757590''>lengths</span> <span m=''3757900''>of</span>
  <span m=''3757950''>the</span> <span m=''3758010''>polygon,</span> <span m=''3759190''>but</span>
  <span m=''3759300''>I</span> <span m=''3759370''>don''t</span> <span m=''3759530''>know</span>
  <span m=''3759620''>the</span> <span m=''3759760''>angles</span> <span m=''3760040''>of
  the</span> <span m=''3760140''>polygon</span> <span m=''3760600''>because</span>
  <span m=''3761560''>that''s</span> <span m=''3761920''>essentially</span> <span
  m=''3762310''>the</span> <span m=''3762470''>dihedral</span> <span m=''3763020''>angle</span>
  <span m=''3763290''>of</span> <span m=''3763680''>that</span> <span m=''3763920''>edge.</span>
  <span m=''3766010''>And</span> <span m=''3766500''>the</span> <span m=''3766610''>worry</span>
  <span m=''3766930''>is,</span> <span m=''3767320''>well,</span> <span m=''3767430''>maybe</span>
  <span m=''3767740''>all</span> <span m=''3767850''>the</span> <span m=''3767930''>edge</span>
  <span m=''3768090''>lengths</span> <span m=''3768260''>match.</span> <span m=''3768610''>We</span>
  <span m=''3768710''>could do</span> <span m=''3769090''>this at</span> <span m=''3769170''>every</span>
  <span m=''3769350''>vertex,</span> <span m=''3770110''>but</span> <span m=''3770350''>maybe</span>
  <span m=''3770940''>the</span> <span m=''3771040''>dihedral</span> <span m=''3771190''>angles</span>
  <span m=''3771610''>are</span> <span m=''3771660''>different.</span> <span m=''3772070''>Maybe</span>
  <span m=''3772460''>the</span> <span m=''3772570''>convex</span> <span m=''3772960''>polyhedron</span>
  <span m=''3773390''>could</span> <span m=''3773540''>flex.</span> <span m=''3774000''>That''s</span>
  <span m=''3774190''>why</span> <span m=''3774300''>this</span> <span m=''3774460''>is</span>
  <span m=''3774540''>about</span> <span m=''3774770''>rigidity.</span> </p><p><span
  m=''3775720''>Maybe</span> <span m=''3775920''>it''s</span> <span m=''3776050''>flexible,</span>
  <span m=''3776980''>and</span> <span m=''3777200''>then,</span> <span m=''3777370''>maybe</span>
  <span m=''3777620''>there</span> <span m=''3777750''>are</span> <span m=''3777850''>two</span>
  <span m=''3778210''>different</span> <span m=''3778670''>states.</span> <span m=''3780070''>All</span>
  <span m=''3780250''>the</span> <span m=''3780300''>faces</span> <span m=''3780640''>are</span>
  <span m=''3780720''>the</span> <span m=''3780800''>same,</span> <span m=''3781280''>and</span>
  <span m=''3781380''>therefore,</span> <span m=''3781710''>all</span> <span m=''3781830''>those</span>
  <span m=''3782070''>edge</span> <span m=''3782290''>lengths</span> <span m=''3782490''>are</span>
  <span m=''3782570''>the</span> <span m=''3782660''>same,</span> <span m=''3783230''>but</span>
  <span m=''3783370''>the</span> <span m=''3783460''>angles</span> <span m=''3783800''>might</span>
  <span m=''3783990''>differ.</span> <span m=''3785740''>If</span> <span m=''3785980''>p</span>
  <span m=''3786170''>and</span> <span m=''3786250''>p</span> <span m=''3786400''>prime</span>
  <span m=''3786660''>are</span> <span m=''3786730''>supposed</span> <span m=''3786990''>to</span>
  <span m=''3787040''>be</span> <span m=''3787150''>different,</span> <span m=''3787560''>then</span>
  <span m=''3787820''>there</span> <span m=''3787920''>must</span> <span m=''3788270''>be</span>
  <span m=''3788420''>two</span> <span m=''3788700''>angles</span> <span m=''3789110''>that</span>
  <span m=''3789270''>differ.</span> <span m=''3790440''>So</span> <span m=''3790570''>I</span>
  <span m=''3790590''>want</span> <span m=''3790730''>to</span> <span m=''3790790''>look</span>
  <span m=''3791000''>at</span> <span m=''3791110''>those</span> <span m=''3791370''>angles,</span>
  <span m=''3793330''>and</span> <span m=''3793880''>I</span> <span m=''3793920''>want</span>
  <span m=''3794180''>to</span> <span m=''3795720''>label</span> <span m=''3806690''>vertex</span>
  <span m=''3808370''>of</span> <span m=''3808610''>a</span> <span m=''3808680''>spherical</span>
  <span m=''3809360''>polygon.</span> </p><p><span m=''3811270''>So</span> <span m=''3811400''>I</span>
  <span m=''3811460''>have</span> <span m=''3812310''>n</span> <span m=''3812540''>of</span>
  <span m=''3812630''>these</span> <span m=''3812790''>spherical</span> <span m=''3813160''>polygons</span>
  <span m=''3815510''>for</span> <span m=''3815730''>p</span> <span m=''3816030''>n</span>
  <span m=''3816330''>of</span> <span m=''3816430''>them</span> <span m=''3816630''>and</span>
  <span m=''3816870''>p</span> <span m=''3817050''>prime.</span> <span m=''3817900''>Let''s</span>
  <span m=''3818060''>look</span> <span m=''3818190''>at</span> <span m=''3818250''>them</span>
  <span m=''3818380''>in</span> <span m=''3818480''>p.</span> <span m=''3819890''>I''m
  going</span> <span m=''3819980''>to</span> <span m=''3820050''>label</span> <span
  m=''3820440''>it</span> <span m=''3820640''>plus</span> <span m=''3822140''>if</span>
  <span m=''3822420''>the</span> <span m=''3822770''>angle</span> <span m=''3823140''>there</span>
  <span m=''3825050''>in</span> <span m=''3825350''>p</span> <span m=''3827180''>is</span>
  <span m=''3827450''>bigger</span> <span m=''3827780''>than</span> <span m=''3828120''>the</span>
  <span m=''3828250''>angle</span> <span m=''3828650''>in</span> <span m=''3829370''>p</span>
  <span m=''3829540''>prime.</span> <span m=''3830910''>Remember</span> <span m=''3831070''>I
  have a</span> <span m=''3831280''>correspondence</span> <span m=''3831970''>between</span>
  <span m=''3832470''>everything</span> <span m=''3833010''>in</span> <span m=''3833100''>p</span>
  <span m=''3833350''>and</span> <span m=''3833570''>everything</span> <span m=''3833910''>and</span>
  <span m=''3834010''>p</span> <span m=''3834150''>prime.</span> <span m=''3834770''>Minus,</span>
  <span m=''3835400''>if</span> <span m=''3835620''>the</span> <span m=''3835730''>angle
  is</span> <span m=''3836110''>less,</span> <span m=''3837290''>and</span> <span
  m=''3837610''>0,</span> <span m=''3838810''>if</span> <span m=''3838950''>the</span>
  <span m=''3839030''>angles</span> <span m=''3839330''>are</span> <span m=''3839400''>equal.</span>
  </p><p><span m=''3841100''>So</span> <span m=''3841140''>what</span> <span m=''3841290''>I</span>
  <span m=''3841330''>want</span> <span m=''3841580''>to</span> <span m=''3841640''>show</span>
  <span m=''3841910''>is</span> <span m=''3842030''>actually</span> <span m=''3842380''>all</span>
  <span m=''3842590''>the</span> <span m=''3842720''>angles</span> <span m=''3843010''>are</span>
  <span m=''3843090''>equal.</span> <span m=''3843370''>Therefore,</span> <span m=''3843610''>the</span>
  <span m=''3843730''>polyhedra</span> <span m=''3844270''>will</span> <span m=''3844420''>be</span>
  <span m=''3844560''>identical.</span> <span m=''3845810''>If</span> <span m=''3845990''>all</span>
  <span m=''3846120''>the</span> <span m=''3846180''>faces</span> <span m=''3846540''>are</span>
  <span m=''3846600''>the</span> <span m=''3846700''>same</span> <span m=''3847590''>and</span>
  <span m=''3847850''>all</span> <span m=''3848000''>the</span> <span m=''3848430''>angles</span>
  <span m=''3848850''>at</span> <span m=''3848910''>which</span> <span m=''3849080''>you</span>
  <span m=''3849160''>join</span> <span m=''3849410''>them</span> <span m=''3849530''>are</span>
  <span m=''3849600''>the</span> <span m=''3849720''>same</span> <span m=''3850190''>and</span>
  <span m=''3850390''>they''re</span> <span m=''3850480''>connected</span> <span m=''3850770''>in</span>
  <span m=''3850840''>the</span> <span m=''3850910''>same</span> <span m=''3851140''>way,</span>
  <span m=''3851340''>they are</span> <span m=''3851540''>the</span> <span m=''3851660''>same</span>
  <span m=''3851890''>polyhedron.</span> <span m=''3852440''>There''s</span> <span
  m=''3852620''>no</span> <span m=''3853130''>flexibility</span> <span m=''3853680''>there,</span>
  <span m=''3855440''>but</span> <span m=''3855640''>it</span> <span m=''3855710''>could</span>
  <span m=''3855880''>be</span> <span m=''3856000''>there are</span> <span m=''3856170''>pluses</span>
  <span m=''3856540''>and</span> <span m=''3856640''>minuses.</span> </p><p><span
  m=''3857460''>But</span> <span m=''3857880''>if</span> <span m=''3858100''>there''s</span>
  <span m=''3858310''>going</span> <span m=''3858430''>to</span> <span m=''3858500''>be</span>
  <span m=''3858600''>a</span> <span m=''3858660''>problem</span> <span m=''3858920''>with</span>
  <span m=''3859010''>this</span> <span m=''3859160''>theorem,</span> <span m=''3859690''>there</span>
  <span m=''3859790''>have</span> <span m=''3860010''>to</span> <span m=''3860100''>be</span>
  <span m=''3860220''>pluses</span> <span m=''3860570''>and</span> <span m=''3860640''>minuses.</span>
  <span m=''3861060''>That''s</span> <span m=''3861280''>the</span> <span m=''3861400''>proof</span>
  <span m=''3861650''>by</span> <span m=''3861750''>contradiction.</span> <span m=''3863170''>So</span>
  <span m=''3863350''>let''s</span> <span m=''3863530''>look</span> <span m=''3863690''>at</span>
  <span m=''3863900''>one</span> <span m=''3864070''>of</span> <span m=''3864160''>them.</span>
  <span m=''3865150''>Let''s</span> <span m=''3865210''>look</span> <span m=''3865320''>at</span>
  <span m=''3865390''>a</span> <span m=''3865440''>vertex</span> <span m=''3865870''>that</span>
  <span m=''3865940''>has</span> <span m=''3866150''>some</span> <span m=''3866290''>pluses</span>
  <span m=''3866650''>or</span> <span m=''3866720''>minuses.</span> </p><p><span m=''3884470''>So</span>
  <span m=''3885030''>we</span> <span m=''3885160''>have--</span> <span m=''3885990''>it''s</span>
  <span m=''3886170''>a</span> <span m=''3886220''>spherical</span> <span m=''3886650''>polygon.</span>
  <span m=''3887260''>I''m</span> <span m=''3887430''>going</span> <span m=''3887530''>to</span>
  <span m=''3887630''>draw</span> <span m=''3887905''>it</span> <span m=''3888450''>more</span>
  <span m=''3888600''>like</span> <span m=''3888750''>a</span> <span m=''3888800''>polygon,</span>
  <span m=''3891920''>maybe</span> <span m=''3892740''>some</span> <span m=''3892920''>pluses,</span>
  <span m=''3893520''>some</span> <span m=''3893700''>zeroes,</span> <span m=''3894360''>some</span>
  <span m=''3894530''>minuses,</span> <span m=''3895710''>whatever.</span> <span m=''3897160''>First</span>
  <span m=''3897400''>question</span> <span m=''3897770''>is</span> <span m=''3898430''>could</span>
  <span m=''3898680''>it</span> <span m=''3898760''>be</span> <span m=''3898960''>all</span>
  <span m=''3899210''>pluses</span> <span m=''3900740''>and</span> <span m=''3900900''>zeroes?</span>
  <span m=''3902510''>Is</span> <span m=''3902590''>that</span> <span m=''3902760''>possible?</span>
  <span m=''3909630''>No.</span> <span m=''3912400''>It doesn''t</span> <span m=''3912540''>look</span>
  <span m=''3912830''>good.</span> </p><p><span m=''3913220''>What</span> <span m=''3913350''>does</span>
  <span m=''3913480''>that</span> <span m=''3913650''>mean?</span> <span m=''3914530''>It</span>
  <span m=''3914600''>would</span> <span m=''3914790''>mean</span> <span m=''3915150''>this</span>
  <span m=''3915360''>is</span> <span m=''3915450''>like</span> <span m=''3915640''>a</span>
  <span m=''3915700''>linkage.</span> <span m=''3916270''>We''re</span> <span m=''3916360''>used</span>
  <span m=''3916600''>to</span> <span m=''3916680''>linkages.</span> <span m=''3917710''>It</span>
  <span m=''3917980''>just</span> <span m=''3918250''>happens</span> <span m=''3918530''>to</span>
  <span m=''3918590''>be</span> <span m=''3918720''>on a</span> <span m=''3918930''>sphere.</span>
  <span m=''3919190''>Forget</span> <span m=''3919600''>this</span> <span m=''3919840''>on</span>
  <span m=''3919960''>a</span> <span m=''3920020''>sphere.</span> <span m=''3920260''>Think</span>
  <span m=''3920480''>of</span> <span m=''3920580''>it</span> <span m=''3920660''>is</span>
  <span m=''3920900''>as almost</span> <span m=''3921190''>flat.</span> </p><p><span
  m=''3923120''>What</span> <span m=''3923270''>that</span> <span m=''3923380''>would</span>
  <span m=''3923500''>mean</span> <span m=''3923710''>is</span> <span m=''3923920''>there''s</span>
  <span m=''3924090''>some</span> <span m=''3924580''>other</span> <span m=''3924870''>way</span>
  <span m=''3924990''>to</span> <span m=''3925100''>draw</span> <span m=''3925360''>this</span>
  <span m=''3925620''>thing.</span> <span m=''3926180''>Basically,</span> <span m=''3926290''>there''s</span>
  <span m=''3926470''>a</span> <span m=''3926530''>way</span> <span m=''3926620''>to</span>
  <span m=''3926690''>flex</span> <span m=''3927080''>this</span> <span m=''3927250''>linkage</span>
  <span m=''3928020''>so</span> <span m=''3928190''>that</span> <span m=''3928340''>all</span>
  <span m=''3928610''>of</span> <span m=''3928690''>these</span> <span m=''3928890''>angles</span>
  <span m=''3929380''>increase</span> <span m=''3929950''>and</span> <span m=''3930040''>this</span>
  <span m=''3930200''>one</span> <span m=''3930320''>stays</span> <span m=''3930620''>the</span>
  <span m=''3930700''>same.</span> <span m=''3932070''>How</span> <span m=''3932320''>could</span>
  <span m=''3932500''>I</span> <span m=''3932540''>get</span> <span m=''3932780''>a</span>
  <span m=''3932850''>polygon</span> <span m=''3933310''>where</span> <span m=''3933720''>all</span>
  <span m=''3933960''>the</span> <span m=''3934080''>angles</span> <span m=''3934360''>increase</span>
  <span m=''3935380''>and</span> <span m=''3935510''>still</span> <span m=''3935680''>be</span>
  <span m=''3935790''>convex?</span> <span m=''3937610''>Ain''t</span> <span m=''3938110''>possible.</span>
  </p><p><span m=''3938860''>Why is</span> <span m=''3939230''>it not</span> <span
  m=''3939480''>possible?</span> <span m=''3940360''>I think</span> <span m=''3940600''>we''ve</span>
  <span m=''3940760''>used</span> <span m=''3940960''>this</span> <span m=''3941130''>fact</span>
  <span m=''3942270''>a</span> <span m=''3942630''>couple</span> <span m=''3942870''>lectures</span>
  <span m=''3943190''>ago.</span> <span m=''3945650''>It''s</span> <span m=''3945800''>not</span>
  <span m=''3945950''>possible</span> <span m=''3946310''>by</span> <span m=''3946690''>something</span>
  <span m=''3946940''>called</span> <span m=''3947070''>the</span> <span m=''3947160''>Cauchy</span>
  <span m=''3947480''>Arm</span> <span m=''3947670''>Lemma.</span> <span m=''3951107''>This</span>
  <span m=''3951600''>is</span> <span m=''3951680''>the</span> <span m=''3951770''>part</span>
  <span m=''3951980''>that</span> <span m=''3952070''>Cauchy</span> <span m=''3952360''>got</span>
  <span m=''3952520''>wrong,</span> <span m=''3952800''>so</span> <span m=''3952920''>it''s</span>
  <span m=''3953040''>also</span> <span m=''3953280''>called</span> <span m=''3953460''>the</span>
  <span m=''3953550''>Cauchy-Steinitz</span> <span m=''3954360''>Arm</span> <span
  m=''3954600''>Lemma.</span> </p><p><span m=''3955880''>And</span> <span m=''3956840''>here''s</span>
  <span m=''3957260''>the</span> <span m=''3957380''>thing.</span> <span m=''3957870''>If</span>
  <span m=''3957960''>you</span> <span m=''3958070''>have</span> <span m=''3959670''>a</span>
  <span m=''3959810''>convex</span> <span m=''3960420''>chain</span> <span m=''3963080''>but</span>
  <span m=''3963900''>open</span> <span m=''3964100''>chain</span> <span m=''3964360''>here.</span>
  <span m=''3964530''>There''s</span> <span m=''3964770''>a</span> <span m=''3965090''>missing</span>
  <span m=''3965450''>bar.</span> <span m=''3966580''>So</span> <span m=''3966850''>suppose</span>
  <span m=''3967260''>that</span> <span m=''3967330''>even</span> <span m=''3967650''>when</span>
  <span m=''3967760''>you</span> <span m=''3967850''>add</span> <span m=''3968060''>the</span>
  <span m=''3968130''>bar,</span> <span m=''3968370''>it''s</span> <span m=''3968500''>a</span>
  <span m=''3968550''>convex</span> <span m=''3968970''>polygon.</span> <span m=''3969470''>But</span>
  <span m=''3969600''>then,</span> <span m=''3970050''>I</span> <span m=''3970150''>take</span>
  <span m=''3970340''>a</span> <span m=''3970390''>convex</span> <span m=''3970730''>polygon,</span>
  <span m=''3971080''>remove</span> <span m=''3971370''>an</span> <span m=''3971450''>edge.</span>
  <span m=''3971740''>This</span> <span m=''3971920''>is</span> <span m=''3972080''>what</span>
  <span m=''3972200''>we</span> <span m=''3972290''>call</span> <span m=''3972920''>convex</span>
  <span m=''3973390''>chain.</span> </p><p><span m=''3974940''>And</span> <span m=''3975170''>if</span>
  <span m=''3975380''>you</span> <span m=''3975710''>open</span> <span m=''3976780''>all</span>
  <span m=''3977130''>the</span> <span m=''3977250''>angles,</span> <span m=''3978540''>increasing</span>
  <span m=''3979050''>all</span> <span m=''3979170''>the</span> <span m=''3979280''>angles,</span>
  <span m=''3981280''>in</span> <span m=''3981450''>a</span> <span m=''3981520''>convex</span>
  <span m=''3981940''>chain,</span> <span m=''3987280''>then</span> <span m=''3991510''>this</span>
  <span m=''3991730''>distance</span> <span m=''3993760''>increases.</span> <span
  m=''4002120''>It''s</span> <span m=''4002260''>pretty</span> <span m=''4002490''>intuitive.</span>
  <span m=''4002960''>I</span> <span m=''4003270''>open</span> <span m=''4003610''>all</span>
  <span m=''4003750''>these</span> <span m=''4003930''>angles.</span> <span m=''4005660''>So</span>
  <span m=''4005800''>I put</span> <span m=''4006020''>plus.</span> </p><p><span m=''4006670''>Some
  of them</span> <span m=''4007050''>could</span> <span m=''4007190''>stay</span>
  <span m=''4007350''>the</span> <span m=''4007460''>same,</span> <span m=''4008940''>but</span>
  <span m=''4009120''>then,</span> <span m=''4009460''>this</span> <span m=''4009930''>distance</span>
  <span m=''4010340''>will</span> <span m=''4010520''>increase,</span> <span m=''4011600''>as</span>
  <span m=''4011660''>long</span> <span m=''4011850''>as</span> <span m=''4011920''>you</span>
  <span m=''4012020''>stay</span> <span m=''4012240''>convex.</span> <span m=''4015270''>I
  should</span> <span m=''4015740''>mention</span> <span m=''4016070''>that.</span>
  <span m=''4016590''>But</span> <span m=''4016930''>in</span> <span m=''4017010''>this</span>
  <span m=''4017150''>situation,</span> <span m=''4017660''>we</span> <span m=''4017750''>know</span>
  <span m=''4017940''>that</span> <span m=''4018070''>both</span> <span m=''4018470''>the</span>
  <span m=''4018820''>initial</span> <span m=''4019260''>position</span> <span m=''4019650''>in</span>
  <span m=''4019750''>p</span> <span m=''4020070''>and</span> <span m=''4020140''>its</span>
  <span m=''4020370''>target</span> <span m=''4020740''>position</span> <span m=''4021070''>in</span>
  <span m=''4021140''>p prime</span> <span m=''4021380''>are</span> <span m=''4021590''>both</span>
  <span m=''4021790''>convex.</span> </p><p><span m=''4028420''>OK.</span> <span m=''4029010''>Let''s</span>
  <span m=''4029200''>just</span> <span m=''4029560''>take</span> <span m=''4029780''>that</span>
  <span m=''4029940''>lemma</span> <span m=''4030190''>as</span> <span m=''4030300''>given.</span>
  <span m=''4031500''>This</span> <span m=''4031720''>is the</span> <span m=''4032000''>one
  I</span> <span m=''4032120''>don''t</span> <span m=''4032360''>like.</span> <span
  m=''4045250''>Then,</span> <span m=''4045390''>I</span> <span m=''4045470''>know,</span>
  <span m=''4045690''>in</span> <span m=''4045810''>particular,</span> <span m=''4046390''>I</span>
  <span m=''4046440''>can''t</span> <span m=''4046730''>have</span> <span m=''4046900''>all</span>
  <span m=''4047030''>pluses</span> <span m=''4047660''>because</span> <span m=''4048120''>then,</span>
  <span m=''4048780''>if</span> <span m=''4048960''>I</span> <span m=''4049020''>just</span>
  <span m=''4049270''>pretend</span> <span m=''4049610''>one</span> <span m=''4049740''>of</span>
  <span m=''4049790''>these</span> <span m=''4049940''>edges</span> <span m=''4050220''>wasn''t</span>
  <span m=''4050510''>here,</span> <span m=''4052530''>I</span> <span m=''4052670''>know</span>
  <span m=''4052840''>that</span> <span m=''4053610''>that</span> <span m=''4053900''>distance</span>
  <span m=''4054260''>must</span> <span m=''4054510''>increase.</span> <span m=''4056820''>But
  it</span> <span m=''4056940''>can''t</span> <span m=''4057170''>increase.</span>
  <span m=''4057530''>It''s</span> <span m=''4057640''>supposed</span> <span m=''4057830''>to</span>
  <span m=''4057900''>stay</span> <span m=''4058070''>the</span> <span m=''4058170''>same.</span>
  <span m=''4058520''>The edge</span> <span m=''4058780''>lengths</span> <span m=''4059010''>are</span>
  <span m=''4059070''>fixed.</span> </p><p><span m=''4060370''>So</span> <span m=''4060410''>if</span>
  <span m=''4060470''>they''re</span> <span m=''4060610''>all</span> <span m=''4060780''>pluses</span>
  <span m=''4061140''>and</span> <span m=''4061240''>zeroes,</span> <span m=''4061780''>or</span>
  <span m=''4062190''>all</span> <span m=''4062320''>minuses</span> <span m=''4062800''>and</span>
  <span m=''4062900''>zeroes,</span> <span m=''4063310''>the</span> <span m=''4063390''>same</span>
  <span m=''4063890''>is</span> <span m=''4064010''>true</span> <span m=''4064190''>just</span>
  <span m=''4064520''>viewing</span> <span m=''4064780''>p</span> <span m=''4065010''>prime</span>
  <span m=''4065370''>as</span> <span m=''4065500''>p</span> <span m=''4065800''>and</span>
  <span m=''4065940''>p</span> <span m=''4066335''>as p</span> <span m=''4066730''>prime.</span>
  <span m=''4069060''>They</span> <span m=''4069170''>can''t</span> <span m=''4069450''>be</span>
  <span m=''4069570''>all</span> <span m=''4069680''>pluses.</span> <span m=''4070050''>They</span>
  <span m=''4070120''>can''t</span> <span m=''4070360''>be all</span> <span m=''4070480''>minuses.</span>
  <span m=''4072040''>So</span> <span m=''4072170''>if</span> <span m=''4072230''>there''s</span>
  <span m=''4072370''>anything</span> <span m=''4072800''>in</span> <span m=''4072870''>there</span>
  <span m=''4073040''>other</span> <span m=''4073190''>than</span> <span m=''4073350''>zeroes,</span>
  <span m=''4074180''>there has</span> <span m=''4074360''>to</span> <span m=''4074450''>be</span>
  <span m=''4074870''>at</span> <span m=''4074930''>least</span> <span m=''4075130''>one</span>
  <span m=''4075260''>plus,</span> <span m=''4075570''>at</span> <span m=''4075660''>least</span>
  <span m=''4075870''>one</span> <span m=''4075970''>minus.</span> </p><p><span m=''4077540''>In</span>
  <span m=''4077660''>particular,</span> <span m=''4078630''>there</span> <span m=''4078730''>have</span>
  <span m=''4078930''>to</span> <span m=''4079040''>be</span> <span m=''4079310''>at</span>
  <span m=''4079410''>least</span> <span m=''4079860''>two</span> <span m=''4080670''>alternations.</span>
  <span m=''4083620''>Alternation</span> <span m=''4084440''>is</span> <span m=''4084690''>either</span>
  <span m=''4084990''>going</span> <span m=''4085250''>from</span> <span m=''4085410''>plus
  to</span> <span m=''4085740''>minus</span> <span m=''4086110''>or</span> <span m=''4086930''>from</span>
  <span m=''4087040''>minus</span> <span m=''4087390''>to</span> <span m=''4087480''>plus.</span>
  <span m=''4088800''>So</span> <span m=''4088990''>it</span> <span m=''4089040''>could</span>
  <span m=''4089200''>be</span> <span m=''4089310''>something</span> <span m=''4089620''>like</span>
  <span m=''4089980''>plus,</span> <span m=''4090353''>plus,</span> <span m=''4090726''>plus,</span>
  <span m=''4091100''>minus,</span> <span m=''4091790''>minus,</span> <span m=''4092120''>minus,</span>
  <span m=''4093430''>minus,</span> <span m=''4093990''>plus,</span> <span m=''4094340''>plus.</span>
  <span m=''4094950''>Whatever.</span> <span m=''4096350''>OK?</span> <span m=''4096550''>Maybe</span>
  <span m=''4096870''>that''s</span> <span m=''4097149''>your</span> <span m=''4097279''>polygon,</span>
  <span m=''4098529''>and</span> <span m=''4098680''>that''s</span> <span m=''4098830''>your</span>
  <span m=''4098950''>labeling.</span> </p><p><span m=''4106410''>Is</span> <span
  m=''4106600''>that</span> <span m=''4106790''>possible?</span> <span m=''4111560''>So</span>
  <span m=''4111670''>once</span> <span m=''4111840''>you</span> <span m=''4111910''>have</span>
  <span m=''4112040''>at</span> <span m=''4112080''>least</span> <span m=''4112279''>one</span>
  <span m=''4112410''>plus and</span> <span m=''4112660''>one</span> <span m=''4112850''>minus,</span>
  <span m=''4113130''>you</span> <span m=''4113220''>have</span> <span m=''4113390''>to</span>
  <span m=''4113470''>have</span> <span m=''4113600''>these</span> <span m=''4113840''>two</span>
  <span m=''4115069''>switches</span> <span m=''4116399''>at least.</span> <span m=''4118380''>Could</span>
  <span m=''4118550''>this</span> <span m=''4118710''>happen?</span> </p><p><span
  m=''4119693''>AUDIENCE: No.</span> </p><p><span m=''4120660''>PROFESSOR: No.</span>
  <span m=''4122370''>Right.</span> <span m=''4123950''>Because</span> <span m=''4125620''>you</span>
  <span m=''4125770''>pick</span> <span m=''4125970''>some</span> <span m=''4126310''>chord.</span>
  <span m=''4128590''>What</span> <span m=''4129000''>do I</span> <span m=''4129410''>do</span>
  <span m=''4129630''>here?</span> <span m=''4132002''>Just</span> <span m=''4132500''>subdivide.</span>
  <span m=''4133180''>All right.</span> <span m=''4133500''>Whatever.</span> <span
  m=''4134890''>Pick</span> <span m=''4135200''>some</span> <span m=''4135399''>chord</span>
  <span m=''4135740''>like</span> <span m=''4137580''>this</span> <span m=''4137880''>one.</span>
  <span m=''4138939''>I''m not</span> <span m=''4139010''>sure</span> <span m=''4139160''>it</span>
  <span m=''4139210''>matters.</span> <span m=''4139505''>Maybe</span> <span m=''4139800''>here?</span>
  <span m=''4140609''>Whatever.</span> </p><p><span m=''4143020''>These</span> <span
  m=''4143830''>angles</span> <span m=''4144090''>down</span> <span m=''4144279''>here</span>
  <span m=''4144620''>are</span> <span m=''4144790''>decreasing.</span> <span m=''4145550''>Therefore,</span>
  <span m=''4145899''>this</span> <span m=''4146109''>distance</span> <span m=''4146630''>decreases.</span>
  <span m=''4148229''>The</span> <span m=''4148340''>angles</span> <span m=''4148720''>up</span>
  <span m=''4148870''>here</span> <span m=''4149859''>are</span> <span m=''4149990''>all</span>
  <span m=''4150130''>increasing.</span> <span m=''4150870''>Therefore,</span> <span
  m=''4151220''>this</span> <span m=''4151420''>distance</span> <span m=''4151880''>increases.</span>
  <span m=''4153200''>Can''t</span> <span m=''4153399''>have</span> <span m=''4153560''>both.</span>
  <span m=''4155310''>So</span> <span m=''4155390''>this</span> <span m=''4155580''>is</span>
  <span m=''4155649''>also</span> <span m=''4156140''>not</span> <span m=''4156410''>possible.</span>
  </p><p><span m=''4158109''>So</span> <span m=''4158170''>in</span> <span m=''4158240''>fact,</span>
  <span m=''4158470''>you</span> <span m=''4158550''>have</span> <span m=''4158710''>to</span>
  <span m=''4158810''>have</span> <span m=''4159160''>at</span> <span m=''4159279''>least</span>
  <span m=''4159939''>four</span> <span m=''4160260''>alternations.</span> <span m=''4160770''>It''s
  always</span> <span m=''4161180''>even.</span> <span m=''4167020''>And</span> <span
  m=''4167290''>so</span> <span m=''4167410''>it</span> <span m=''4167479''>has</span>
  <span m=''4167700''>to</span> <span m=''4167810''>be</span> <span m=''4168689''>at</span>
  <span m=''4169160''>least</span> <span m=''4169510''>a</span> <span m=''4169550''>bunch</span>
  <span m=''4169779''>of</span> <span m=''4169830''>pluses,</span> <span m=''4170310''>then</span>
  <span m=''4170479''>a</span> <span m=''4170529''>bunch</span> <span m=''4170760''>of</span>
  <span m=''4170819''>minuses,</span> <span m=''4171359''>then</span> <span m=''4171529''>a</span>
  <span m=''4171569''>bunch</span> <span m=''4171800''>of</span> <span m=''4171870''>pluses,</span>
  <span m=''4172770''>then</span> <span m=''4172910''>a</span> <span m=''4172960''>bunch</span>
  <span m=''4173180''>of</span> <span m=''4173260''>minuses.</span> <span m=''4174560''>And</span>
  <span m=''4174729''>so</span> <span m=''4174880''>we''re</span> <span m=''4175010''>counting</span>
  <span m=''4175330''>these</span> <span m=''4175490''>transitions</span> <span m=''4176100''>from</span>
  <span m=''4176220''>plus</span> <span m=''4176460''>to</span> <span m=''4176550''>minus.</span>
  </p><p><span m=''4177910''>This</span> <span m=''4178109''>is</span> <span m=''4178270''>a</span>
  <span m=''4178370''>lemma</span> <span m=''4178750''>that</span> <span m=''4178870''>we</span>
  <span m=''4179050''>used</span> <span m=''4180109''>when we were</span> <span m=''4180390''>locking</span>
  <span m=''4180770''>trees,</span> <span m=''4181380''>I</span> <span m=''4181439''>think.</span>
  <span m=''4182040''>We had</span> <span m=''4182160''>a</span> <span m=''4182210''>convex</span>
  <span m=''4182569''>polygon.</span> <span m=''4183000''>I</span> <span m=''4183090''>said</span>
  <span m=''4183279''>at</span> <span m=''4183340''>least</span> <span m=''4183600''>two</span>
  <span m=''4183760''>of the</span> <span m=''4183859''>angles</span> <span m=''4184120''>have</span>
  <span m=''4184260''>to</span> <span m=''4184359''>decrease,</span> <span m=''4185859''>or</span>
  <span m=''4186060''>at least</span> <span m=''4186210''>two</span> <span m=''4186350''>of
  them</span> <span m=''4186510''>have</span> <span m=''4186600''>to</span> <span
  m=''4186680''>increase,</span> <span m=''4187240''>one</span> <span m=''4187420''>way</span>
  <span m=''4187520''>or</span> <span m=''4187550''>the</span> <span m=''4187700''>other.</span>
  <span m=''4188279''>That''s because</span> <span m=''4188470''>there</span> <span
  m=''4188560''>have</span> <span m=''4188760''>to</span> <span m=''4188870''>be</span>
  <span m=''4189180''>at</span> <span m=''4189250''>least</span> <span m=''4190060''>two</span>
  <span m=''4190439''>groups</span> <span m=''4190819''>of</span> <span m=''4190930''>pluses,</span>
  <span m=''4191460''>not</span> <span m=''4191620''>only</span> <span m=''4192069''>at</span>
  <span m=''4192229''>least</span> <span m=''4192380''>two</span> <span m=''4192520''>pluses</span>
  <span m=''4193290''>and</span> <span m=''4193520''>at least</span> <span m=''4193660''>two</span>
  <span m=''4193810''>minuses.</span> </p><p><span m=''4195900''>You</span> <span
  m=''4195970''>might</span> <span m=''4196140''>think,</span> <span m=''4196310''>well,</span>
  <span m=''4196410''>what</span> <span m=''4196550''>happens</span> <span m=''4196840''>if</span>
  <span m=''4196930''>there''s</span> <span m=''4197080''>only</span> <span m=''4197310''>three</span>
  <span m=''4198280''>vertices.</span> <span m=''4199900''>Then,</span> <span m=''4200050''>you</span>
  <span m=''4200120''>can''t</span> <span m=''4200320''>have</span> <span m=''4200500''>these</span>
  <span m=''4200650''>four</span> <span m=''4200910''>alternations.</span> <span m=''4201340''>Well,</span>
  <span m=''4201470''>yeah,</span> <span m=''4201690''>you</span> <span m=''4201770''>can''t</span>
  <span m=''4201980''>have</span> <span m=''4202120''>those</span> <span m=''4202290''>four</span>
  <span m=''4202490''>alternation</span> <span m=''4203450''>because</span> <span
  m=''4203650''>if</span> <span m=''4203740''>you</span> <span m=''4203840''>have</span>
  <span m=''4204020''>a</span> <span m=''4204230''>triangle,</span> <span m=''4204800''>even</span>
  <span m=''4205020''>on</span> <span m=''4205120''>the</span> <span m=''4205190''>sphere,</span>
  <span m=''4205830''>triangles</span> <span m=''4206250''>are</span> <span m=''4206320''>rigid.</span>
  <span m=''4207240''>So</span> <span m=''4207620''>you</span> <span m=''4208050''>would</span>
  <span m=''4208280''>know</span> <span m=''4209160''>if</span> <span m=''4209330''>I</span>
  <span m=''4209390''>had</span> <span m=''4209590''>a</span> <span m=''4209650''>degree</span>
  <span m=''4209930''>3</span> <span m=''4210100''>vertex,</span> <span m=''4211590''>locally</span>
  <span m=''4212030''>that</span> <span m=''4212200''>thing</span> <span m=''4212350''>is</span>
  <span m=''4212450''>rigid.</span> <span m=''4212750''>It can''t</span> <span m=''4213020''>flex</span>
  <span m=''4213425''>at all.</span> <span m=''4213830''>We''re</span> <span m=''4213930''>only</span>
  <span m=''4214200''>interested</span> <span m=''4214630''>in</span> <span m=''4215220''>cases</span>
  <span m=''4215560''>where</span> <span m=''4215770''>it</span> <span m=''4215940''>might</span>
  <span m=''4216380''>flex</span> <span m=''4216720''>locally</span> <span m=''4217090''>at</span>
  <span m=''4217190''>a</span> <span m=''4217220''>vertex</span> <span m=''4217680''>like</span>
  <span m=''4217910''>the</span> <span m=''4218360''>pentagon,</span> <span m=''4219630''>like</span>
  <span m=''4219810''>a</span> <span m=''4219880''>quadrilateral.</span> </p><p><span
  m=''4222760''>All</span> <span m=''4222870''>right.</span> <span m=''4223550''>So</span>
  <span m=''4224180''>what?</span> <span m=''4225480''>This</span> <span m=''4225700''>was</span>
  <span m=''4225830''>true</span> <span m=''4226080''>at</span> <span m=''4226350''>every</span>
  <span m=''4226720''>vertex</span> <span m=''4227640''>that</span> <span m=''4227740''>was</span>
  <span m=''4227880''>not</span> <span m=''4228080''>entirely</span> <span m=''4228520''>zero.</span>
  <span m=''4230610''>So</span> <span m=''4230830''>if</span> <span m=''4231090''>we</span>
  <span m=''4231240''>look</span> <span m=''4231530''>at--</span> <span m=''4233540''>let
  me write this</span> <span m=''4233760''>down.</span> <span m=''4235890''>I</span>
  <span m=''4235980''>really</span> <span m=''4236210''>just</span> <span m=''4236400''>care</span>
  <span m=''4236560''>about</span> <span m=''4236750''>the</span> <span m=''4236840''>non-zero</span>
  <span m=''4237310''>edges,</span> <span m=''4237640''>the</span> <span m=''4237730''>ones</span>
  <span m=''4237930''>that</span> <span m=''4238020''>are</span> <span m=''4238100''>plus</span>
  <span m=''4238420''>or</span> <span m=''4238480''>minus.</span> <span m=''4242510''>So</span>
  <span m=''4242960''>I''ll</span> <span m=''4243130''>call</span> <span m=''4243390''>the</span>
  <span m=''4243710''>subgraph</span> <span m=''4249006''>of</span> <span m=''4249450''>plus</span>
  <span m=''4250090''>and</span> <span m=''4250580''>minus</span> <span m=''4251030''>edges.</span>
  <span m=''4254480''>The</span> <span m=''4254580''>number</span> <span m=''4254900''>of</span>
  <span m=''4254950''>alternations</span> <span m=''4257320''>is</span> <span m=''4260390''>at</span>
  <span m=''4260470''>least</span> <span m=''4261220''>4</span> <span m=''4262000''>times</span>
  <span m=''4262520''>the</span> <span m=''4262590''>number of</span> <span m=''4262860''>vertices.</span>
  <span m=''4263440''>I''m</span> <span m=''4263560''>going</span> <span m=''4263650''>to</span>
  <span m=''4263740''>denote</span> <span m=''4263830''>the</span> <span m=''4264070''>number
  of</span> <span m=''4264310''>vertices</span> <span m=''4264740''>by a</span> <span
  m=''4265090''>capital</span> <span m=''4265520''>V.</span> <span m=''4267748''>OK?</span>
  <span m=''4270083''>That''s</span> <span m=''4270550''>page</span> <span m=''4270780''>one.</span>
  </p><p><span m=''4273670''>We''re</span> <span m=''4273830''>going</span> <span
  m=''4273930''>to</span> <span m=''4273970''>use</span> <span m=''4274170''>a</span>
  <span m=''4274230''>trick.</span> <span m=''4276620''>It</span> <span m=''4276790''>has</span>
  <span m=''4277220''>many</span> <span m=''4277410''>names,</span> <span m=''4277720''>I</span>
  <span m=''4277760''>suppose.</span> <span m=''4278120''>I</span> <span m=''4278210''>usually</span>
  <span m=''4278460''>call</span> <span m=''4278610''>it</span> <span m=''4278750''>double</span>
  <span m=''4279020''>counting</span> <span m=''4279570''>in</span> <span m=''4280020''>combinatorics,</span>
  <span m=''4281060''>where you</span> <span m=''4281330''>have</span> <span m=''4281510''>one</span>
  <span m=''4281800''>quantity,</span> <span m=''4282300''>namely,</span> <span m=''4282500''>the</span>
  <span m=''4282590''>number</span> <span m=''4282920''>of</span> <span m=''4282990''>alterations.</span>
  <span m=''4283550''>We''re</span> <span m=''4283650''>going</span> <span m=''4283760''>to</span>
  <span m=''4283830''>count</span> <span m=''4284100''>it in</span> <span m=''4284190''>two</span>
  <span m=''4284370''>different</span> <span m=''4284650''>ways.</span> <span m=''4285830''>We''ll</span>
  <span m=''4285970''>get</span> <span m=''4286140''>two</span> <span m=''4286260''>different</span>
  <span m=''4286530''>answers,</span> <span m=''4286890''>but</span> <span m=''4287000''>we</span>
  <span m=''4287110''>know</span> <span m=''4287230''>they</span> <span m=''4287320''>must</span>
  <span m=''4287660''>end</span> <span m=''4287820''>up</span> <span m=''4287920''>being</span>
  <span m=''4288080''>the</span> <span m=''4288190''>same.</span> <span m=''4289150''>And</span>
  <span m=''4289360''>then,</span> <span m=''4289490''>we''ll</span> <span m=''4289610''>get</span>
  <span m=''4289730''>a</span> <span m=''4289780''>contradiction.</span> </p><p><span
  m=''4293410''>So</span> <span m=''4294100''>what''s</span> <span m=''4294360''>the</span>
  <span m=''4294440''>second</span> <span m=''4294870''>way</span> <span m=''4295040''>of</span>
  <span m=''4295150''>counting.</span> <span m=''4295760''>Well,</span> <span m=''4296620''>we</span>
  <span m=''4296790''>counted</span> <span m=''4297310''>local</span> <span m=''4297760''>to</span>
  <span m=''4297930''>a</span> <span m=''4297970''>vertex.</span> <span m=''4299390''>The</span>
  <span m=''4299570''>other</span> <span m=''4299830''>natural</span> <span m=''4300190''>way</span>
  <span m=''4300330''>to</span> <span m=''4300430''>count</span> <span m=''4301320''>angles</span>
  <span m=''4302420''>is</span> <span m=''4302640''>by</span> <span m=''4302750''>looking</span>
  <span m=''4303040''>at</span> <span m=''4303130''>the</span> <span m=''4303200''>faces.</span>
  <span m=''4304020''>There are</span> <span m=''4304170''>also</span> <span m=''4304380''>faces.</span>
  <span m=''4304810''>It''s</span> <span m=''4304830''>sort</span> <span m=''4305060''>of</span>
  <span m=''4305120''>the</span> <span m=''4305210''>dual</span> <span m=''4305510''>perspective.</span>
  <span m=''4306110''>Every</span> <span m=''4306380''>phase</span> <span m=''4306850''>has</span>
  <span m=''4307160''>a</span> <span m=''4307210''>bunch</span> <span m=''4307450''>of</span>
  <span m=''4307510''>angles</span> <span m=''4307820''>that</span> <span m=''4307900''>have</span>
  <span m=''4308040''>some</span> <span m=''4308190''>degree</span> <span m=''4308610''>or</span>
  <span m=''4308630''>whatever.</span> </p><p><span m=''4311060''>They''re</span>
  <span m=''4311160''>really</span> <span m=''4311580''>kind of</span> <span m=''4311860''>the</span>
  <span m=''4311940''>same</span> <span m=''4312150''>thing.</span> <span m=''4312350''>Oh,</span>
  <span m=''4312470''>here</span> <span m=''4312630''>was</span> <span m=''4312800''>Cauchy''s</span>
  <span m=''4313130''>Arm Lemma.</span> <span m=''4313250''>Beautiful.</span> <span
  m=''4316230''>If</span> <span m=''4316390''>you</span> <span m=''4316540''>look</span>
  <span m=''4316740''>at</span> <span m=''4316820''>the</span> <span m=''4316940''>alternations</span>
  <span m=''4317540''>as</span> <span m=''4317700''>you</span> <span m=''4317830''>walk</span>
  <span m=''4318090''>around</span> <span m=''4318310''>a</span> <span m=''4318350''>vertex</span>
  <span m=''4319620''>versus</span> <span m=''4320290''>as</span> <span m=''4320470''>you</span>
  <span m=''4320600''>walk</span> <span m=''4320880''>around</span> <span m=''4321110''>a</span>
  <span m=''4321190''>face,</span> <span m=''4322420''>you''ll</span> <span m=''4322560''>end</span>
  <span m=''4322720''>up</span> <span m=''4322830''>counting</span> <span m=''4323170''>them</span>
  <span m=''4323630''>the</span> <span m=''4323730''>same</span> <span m=''4323990''>number.</span>
  <span m=''4325170''>Right?</span> <span m=''4325310''>Here</span> <span m=''4325520''>was</span>
  <span m=''4325660''>an</span> <span m=''4325750''>alternation</span> <span m=''4326810''>from</span>
  <span m=''4327140''>plus</span> <span m=''4327410''>to</span> <span m=''4327500''>minus.</span>
  </p><p><span m=''4329290''>What''s</span> <span m=''4330010''>interesting</span>
  <span m=''4330390''>here--</span> <span m=''4330550''>before</span> <span m=''4330880''>we</span>
  <span m=''4330940''>were</span> <span m=''4331050''>thinking</span> <span m=''4331300''>of</span>
  <span m=''4331370''>labeling</span> <span m=''4331750''>the</span> <span m=''4331840''>vertices</span>
  <span m=''4332440''>of</span> <span m=''4332550''>the</span> <span m=''4332640''>spherical</span>
  <span m=''4333010''>polygon,</span> <span m=''4333480''>but</span> <span m=''4333580''>in</span>
  <span m=''4333670''>fact,</span> <span m=''4334370''>whatever</span> <span m=''4334660''>this</span>
  <span m=''4334830''>edge</span> <span m=''4335060''>does,</span> <span m=''4335380''>it</span>
  <span m=''4335460''>does</span> <span m=''4335640''>the</span> <span m=''4335720''>same</span>
  <span m=''4336030''>thing</span> <span m=''4336380''>local</span> <span m=''4336710''>to</span>
  <span m=''4336790''>that</span> <span m=''4337030''>vertex</span> <span m=''4337520''>as</span>
  <span m=''4337760''>the</span> <span m=''4337850''>thing</span> <span m=''4338020''>local</span>
  <span m=''4338300''>to</span> <span m=''4338390''>that</span> <span m=''4338590''>vertex.</span>
  <span m=''4339020''>So really</span> <span m=''4339320''>the</span> <span m=''4339420''>labels</span>
  <span m=''4339760''>are on</span> <span m=''4339890''>the</span> <span m=''4340030''>edges</span>
  <span m=''4340380''>of</span> <span m=''4340450''>the</span> <span m=''4340530''>graph.</span>
  <span m=''4341640''>They</span> <span m=''4341760''>could</span> <span m=''4341890''>be</span>
  <span m=''4341980''>zero,</span> <span m=''4342300''>plus,</span> <span m=''4342580''>or</span>
  <span m=''4342640''>minus.</span> </p><p><span m=''4344030''>And</span> <span m=''4344210''>if</span>
  <span m=''4344320''>I</span> <span m=''4344400''>have</span> <span m=''4344600''>an</span>
  <span m=''4344680''>alternation</span> <span m=''4345200''>from</span> <span m=''4345350''>plus</span>
  <span m=''4345600''>to</span> <span m=''4345690''>minus,</span> <span m=''4346660''>view</span>
  <span m=''4346830''>from</span> <span m=''4346960''>the</span> <span m=''4347040''>vertex,</span>
  <span m=''4347570''>it''s</span> <span m=''4347760''>also</span> <span m=''4348120''>an</span>
  <span m=''4348190''>alternation</span> <span m=''4348710''>as</span> <span m=''4348880''>I</span>
  <span m=''4348930''>walk</span> <span m=''4349200''>around</span> <span m=''4349420''>the</span>
  <span m=''4349480''>face.</span> <span m=''4350650''>So</span> <span m=''4350790''>instead</span>
  <span m=''4351210''>of</span> <span m=''4351320''>counting</span> <span m=''4351760''>by</span>
  <span m=''4351880''>walking</span> <span m=''4352490''>around</span> <span m=''4352710''>all</span>
  <span m=''4352800''>the</span> <span m=''4352860''>vertices--</span> <span m=''4353280''>which</span>
  <span m=''4353430''>are</span> <span m=''4353490''>just</span> <span m=''4353730''>did,
  and</span> <span m=''4354150''>I</span> <span m=''4354250''>got</span> <span m=''4354280''>at</span>
  <span m=''4354350''>least</span> <span m=''4354550''>four</span> <span m=''4354880''>at
  every</span> <span m=''4355070''>vertex--</span> <span m=''4356160''>let''s</span>
  <span m=''4356320''>do</span> <span m=''4356460''>it</span> <span m=''4356840''>from</span>
  <span m=''4357080''>the</span> <span m=''4357160''>perspective</span> <span m=''4357650''>of</span>
  <span m=''4357750''>the</span> <span m=''4357820''>faces.</span> <span m=''4361310''>And</span>
  <span m=''4361690''>we''re</span> <span m=''4361850''>in</span> <span m=''4362100''>this</span>
  <span m=''4362280''>weird</span> <span m=''4362490''>subgraph of</span> <span m=''4362970''>plus
  and</span> <span m=''4363220''>minus</span> <span m=''4363540''>edges,</span> <span
  m=''4363590''>so</span> <span m=''4363850''>assume</span> <span m=''4364170''>there</span>
  <span m=''4364260''>are</span> <span m=''4364290''>no</span> <span m=''4364560''>zeroes.</span>
  </p><p><span m=''4369437''>All right.</span> <span m=''4369910''>If</span> <span
  m=''4370150''>I</span> <span m=''4370230''>have</span> <span m=''4370500''>a</span>
  <span m=''4370560''>face</span> <span m=''4373485''>of</span> <span m=''4373950''>2</span>
  <span m=''4374190''>k</span> <span m=''4375990''>or</span> <span m=''4376210''>2</span>
  <span m=''4376500''>k</span> <span m=''4377060''>plus</span> <span m=''4377510''>1</span>
  <span m=''4377960''>edges,</span> <span m=''4382110''>then</span> <span m=''4383710''>it</span>
  <span m=''4383850''>will</span> <span m=''4383990''>have,</span> <span m=''4386450''>at</span>
  <span m=''4386640''>most,</span> <span m=''4387630''>2</span> <span m=''4387830''>k</span>
  <span m=''4388200''>alternations.</span> <span m=''4393710''>So</span> <span m=''4393830''>I</span>
  <span m=''4393910''>already</span> <span m=''4394100''>have</span> <span m=''4395050''>a</span>
  <span m=''4395140''>lower</span> <span m=''4395450''>bound</span> <span m=''4395730''>number</span>
  <span m=''4395980''>of</span> <span m=''4396020''>alternations.</span> <span m=''4396600''>I''m</span>
  <span m=''4396660''>going</span> <span m=''4396750''>to</span> <span m=''4396820''>try
  and prove</span> <span m=''4397260''>an</span> <span m=''4397360''>upper</span>
  <span m=''4397610''>bound,</span> <span m=''4398360''>sandwich</span> <span m=''4398760''>it</span>
  <span m=''4398840''>between,</span> <span m=''4399240''>and show</span> <span m=''4399510''>that,</span>
  <span m=''4399630''>actually,</span> <span m=''4399930''>the upper</span> <span
  m=''4400150''>bound</span> <span m=''4400420''>is</span> <span m=''4400530''>smaller</span>
  <span m=''4401030''>than</span> <span m=''4401160''>the</span> <span m=''4401260''>lower</span>
  <span m=''4401490''>bound,</span> <span m=''4401710''>and</span> <span m=''4401790''>that''s</span>
  <span m=''4401960''>a</span> <span m=''4402010''>contradiction.</span> </p><p><span
  m=''4403850''>So</span> <span m=''4404960''>this</span> <span m=''4405160''>is</span>
  <span m=''4405460''>kind</span> <span m=''4405680''>of</span> <span m=''4405750''>obvious.</span>
  <span m=''4406200''>Right?</span> <span m=''4406260''>If you</span> <span m=''4406540''>have</span>
  <span m=''4406900''>2 k</span> <span m=''4407320''>vertices,</span> <span m=''4407730''>no</span>
  <span m=''4407840''>more</span> <span m=''4408000''>than</span> <span m=''4408150''>2</span>
  <span m=''4408320''>k</span> <span m=''4408840''>alternations,</span> <span m=''4409350''>slight,</span>
  <span m=''4409940''>the</span> <span m=''4410110''>place</span> <span m=''4410440''>where
  we''re</span> <span m=''4410670''>making</span> <span m=''4410940''>a</span> <span
  m=''4410990''>little</span> <span m=''4411240''>improvement</span> <span m=''4411770''>is</span>
  <span m=''4411870''>for</span> <span m=''4412010''>the</span> <span m=''4412130''>odd</span>
  <span m=''4412410''>case.</span> <span m=''4413380''>We</span> <span m=''4413510''>know</span>
  <span m=''4413660''>because</span> <span m=''4413850''>a</span> <span m=''4413900''>number</span>
  <span m=''4414080''>of</span> <span m=''4414160''>alterations</span> <span m=''4414600''>has</span>
  <span m=''4414780''>to</span> <span m=''4414840''>be</span> <span m=''4414960''>even</span>
  <span m=''4415290''>you</span> <span m=''4415400''>can''t</span> <span m=''4415700''>get</span>
  <span m=''4415890''>up</span> <span m=''4416090''>to</span> <span m=''4416220''>2</span>
  <span m=''4416410''>k</span> <span m=''4416580''>plus</span> <span m=''4416850''>1</span>
  <span m=''4417600''>alternations.</span> <span m=''4418990''>Has</span> <span m=''4419180''>to</span>
  <span m=''4419260''>be</span> <span m=''4419400''>even</span> <span m=''4419620''>because</span>
  <span m=''4419840''>for</span> <span m=''4419940''>every</span> <span m=''4420670''>plus</span>
  <span m=''4420920''>to</span> <span m=''4421000''>minus,</span> <span m=''4421360''>there
  has</span> <span m=''4421530''>to</span> <span m=''4421600''>be</span> <span m=''4421700''>a</span>
  <span m=''4421740''>matching</span> <span m=''4422050''>minus</span> <span m=''4422300''>to</span>
  <span m=''4422390''>plus</span> <span m=''4422680''>because</span> <span m=''4422820''>it''s</span>
  <span m=''4422970''>cyclic.</span> <span m=''4424220''>So</span> <span m=''4424380''>even</span>
  <span m=''4424640''>here,</span> <span m=''4425020''>you</span> <span m=''4425310''>can</span>
  <span m=''4425420''>only</span> <span m=''4425620''>get</span> <span m=''4425780''>2</span>
  <span m=''4425920''>k</span> <span m=''4426180''>alternations.</span> </p><p><span
  m=''4426460''>That</span> <span m=''4426650''>helps</span> <span m=''4426870''>us</span>
  <span m=''4426950''>a</span> <span m=''4427020''>little</span> <span m=''4427290''>bit</span>
  <span m=''4429300''>because</span> <span m=''4429980''>now,</span> <span m=''4430490''>we</span>
  <span m=''4430670''>can</span> <span m=''4430810''>talk</span> <span m=''4431060''>about</span>
  <span m=''4433950''>number</span> <span m=''4434150''>of</span> <span m=''4434220''>alternation</span>
  <span m=''4439430''>is</span> <span m=''4439580''>at</span> <span m=''4439670''>most</span>
  <span m=''4441440''>two</span> <span m=''4441810''>times</span> <span m=''4442340''>the</span>
  <span m=''4442430''>number</span> <span m=''4442740''>of</span> <span m=''4442800''>triangles,</span>
  <span m=''4443730''>f</span> <span m=''4443930''>sub</span> <span m=''4444130''>3</span>
  <span m=''4444570''>is</span> <span m=''4444690''>going</span> <span m=''4444810''>to</span>
  <span m=''4444880''>be</span> <span m=''4444980''>the</span> <span m=''4445070''>number
  of</span> <span m=''4445310''>faces</span> <span m=''4445690''>of</span> <span m=''4445790''>degree</span>
  <span m=''4446090''>3,</span> <span m=''4448320''>plus</span> <span m=''4451080''>4</span>
  <span m=''4451550''>times</span> <span m=''4452120''>the</span> <span m=''4452240''>number</span>
  <span m=''4452580''>of</span> <span m=''4452650''>quadrilaterals</span> <span m=''4454010''>plus</span>
  <span m=''4454840''>4</span> <span m=''4455170''>times</span> <span m=''4455580''>the</span>
  <span m=''4455660''>number</span> <span m=''4455920''>of</span> <span m=''4455990''>pentagons</span>
  <span m=''4457490''>plus</span> <span m=''4457930''>6</span> <span m=''4458170''>times</span>
  <span m=''4458590''>the</span> <span m=''4458680''>number</span> <span m=''4459000''>of</span>
  <span m=''4459060''>hexagons</span> <span m=''4460340''>plus--</span> <span m=''4462030''>why''d
  I</span> <span m=''4462100''>write</span> <span m=''4462310''>seven?</span> <span
  m=''4462770''>I</span> <span m=''4462890''>wrote</span> <span m=''4462940''>seven.</span>
  <span m=''4463850''>I''m</span> <span m=''4463940''>being</span> <span m=''4464110''>sloppy.</span>
  </p><p><span m=''4466150''>At</span> <span m=''4466270''>that</span> <span m=''4466450''>point,</span>
  <span m=''4466630''>I</span> <span m=''4466690''>don''t</span> <span m=''4466890''>care.</span>
  <span m=''4467860''>7</span> <span m=''4468230''>f</span> <span m=''4468370''>7,</span>
  <span m=''4468655''>8</span> <span m=''4468940''>f</span> <span m=''4469160''>8,</span>
  <span m=''4469650''>9 f</span> <span m=''4470060''>9--</span> <span m=''4470700''>I''m</span>
  <span m=''4470790''>not</span> <span m=''4470960''>going</span> <span m=''4471050''>to</span>
  <span m=''4471180''>try</span> <span m=''4471350''>to</span> <span m=''4471430''>be</span>
  <span m=''4472710''>clever</span> <span m=''4473760''>from</span> <span m=''4474390''>6</span>
  <span m=''4474760''>on,</span> <span m=''4475280''>but</span> <span m=''4475470''>I''m</span>
  <span m=''4475580''>going</span> <span m=''4475740''>to</span> <span m=''4475800''>be</span>
  <span m=''4475890''>clever</span> <span m=''4476240''>at</span> <span m=''4476370''>5</span>
  <span m=''4477450''>and</span> <span m=''4477840''>3.</span> <span m=''4478270''>Why</span>
  <span m=''4478700''>5</span> <span m=''4478970''>and</span> <span m=''4479080''>3?</span>
  </p><p><span m=''4479750''>As</span> <span m=''4480010''>you</span> <span m=''4480070''>may</span>
  <span m=''4480230''>remember</span> <span m=''4480780''>from</span> <span m=''4480980''>way</span>
  <span m=''4481090''>back</span> <span m=''4481330''>when,</span> <span m=''4481440''>you</span>
  <span m=''4481490''>have</span> <span m=''4481650''>a</span> <span m=''4481720''>planar</span>
  <span m=''4481990''>graph--</span> <span m=''4483050''>because</span> <span m=''4483870''>polyhedra</span>
  <span m=''4484160''>are</span> <span m=''4484290''>planar</span> <span m=''4484610''>graphs.</span>
  <span m=''4485190''>They''re</span> <span m=''4485300''>convex.</span> <span m=''4487020''>The</span>
  <span m=''4487150''>average</span> <span m=''4487530''>degree</span> <span m=''4487970''>is</span>
  <span m=''4491580''>5?</span> <span m=''4493700''>Slightly</span> <span m=''4494000''>under</span>
  <span m=''4494440''>6,</span> <span m=''4494903''>4,</span> <span m=''4495366''>3,</span>
  <span m=''4495829''>2,</span> <span m=''4496292''>1?</span> <span m=''4497680''>One</span>
  <span m=''4497850''>of</span> <span m=''4497900''>those</span> <span m=''4498080''>numbers.</span>
  <span m=''4499940''>Let''s</span> <span m=''4500120''>see.</span> <span m=''4501080''>Should</span>
  <span m=''4501290''>be</span> <span m=''4501470''>like</span> <span m=''4501810''>3</span>
  <span m=''4502230''>n</span> <span m=''4502370''>minus</span> <span m=''4502740''>6</span>
  <span m=''4503080''>edges,</span> <span m=''4504560''>so</span> <span m=''4504660''>that</span>
  <span m=''4504860''>should</span> <span m=''4505040''>be</span> <span m=''4505780''>3.</span>
  <span m=''4509025''>Yeah,</span> <span m=''4509370''>three.</span> <span m=''4510600''>So</span>
  <span m=''4510890''>most</span> <span m=''4511950''>of</span> <span m=''4512070''>the</span>
  <span m=''4512540''>faces</span> <span m=''4512970''>are</span> <span m=''4513030''>going</span>
  <span m=''4513120''>to</span> <span m=''4513160''>have</span> <span m=''4513330''>low</span>
  <span m=''4513490''>degree.</span> <span m=''4514160''>That''s the</span> <span
  m=''4514250''>points.</span> <span m=''4514580''>So</span> <span m=''4514690''>3</span>
  <span m=''4515010''>and</span> <span m=''4515110''>5</span> <span m=''4515390''>really</span>
  <span m=''4515600''>matter,</span> <span m=''4516470''>but</span> <span m=''4516730''>out
  here,</span> <span m=''4517040''>it</span> <span m=''4517100''>doesn''t</span> <span
  m=''4517290''>matter</span> <span m=''4517530''>so</span> <span m=''4517650''>much.</span>
  </p><p><span m=''4536750''>This is</span> <span m=''4537030''>kind</span> <span
  m=''4537210''>of</span> <span m=''4537280''>a</span> <span m=''4537340''>magical</span>
  <span m=''4537790''>proof.</span> <span m=''4539160''>It</span> <span m=''4539490''>shouldn''t</span>
  <span m=''4539790''>be</span> <span m=''4539880''>intuitive</span> <span m=''4540290''>where</span>
  <span m=''4540470''>it</span> <span m=''4540550''>came</span> <span m=''4540760''>from,</span>
  <span m=''4543130''>but</span> <span m=''4543280''>it''s</span> <span m=''4543400''>really</span>
  <span m=''4543600''>beautiful.</span> <span m=''4544440''>You''ll</span> <span m=''4544540''>see</span>
  <span m=''4545350''>as it</span> <span m=''4545470''>all</span> <span m=''4545640''>comes</span>
  <span m=''4545850''>together.</span> <span m=''4547390''>Fun.</span> <span m=''4548670''>What
  do I</span> <span m=''4549010''>do next?</span> <span m=''4551680''>Right.</span>
  </p><p><span m=''4552400''>I</span> <span m=''4552560''>want</span> <span m=''4552750''>to</span>
  <span m=''4552830''>relate--</span> <span m=''4554570''>I</span> <span m=''4554690''>have</span>
  <span m=''4554910''>a</span> <span m=''4554960''>vertex</span> <span m=''4555490''>count</span>
  <span m=''4555720''>here.</span> <span m=''4556000''>I</span> <span m=''4556050''>have</span>
  <span m=''4556170''>a</span> <span m=''4556220''>face</span> <span m=''4556580''>count</span>
  <span m=''4556850''>here,</span> <span m=''4558070''>and</span> <span m=''4558340''>I</span>
  <span m=''4558420''>know</span> <span m=''4559030''>Euler''s</span> <span m=''4559390''>formula.</span>
  <span m=''4560330''>Hopefully,</span> <span m=''4560710''>we</span> <span m=''4561090''>know
  it.</span> <span m=''4562070''>It''s a cool</span> <span m=''4562380''>formula.</span>
  <span m=''4566340''>V</span> <span m=''4566400''>minus</span> <span m=''4566690''>E</span>
  <span m=''4566900''>plus</span> <span m=''4567170''>F</span> <span m=''4567520''>is
  2.</span> <span m=''4567870''>This is the</span> <span m=''4568120''>number of</span>
  <span m=''4568320''>vertices,</span> <span m=''4568770''>number</span> <span m=''4568950''>of</span>
  <span m=''4569030''>edges,</span> <span m=''4569350''>number</span> <span m=''4569590''>faces</span>
  <span m=''4570410''>is</span> <span m=''4570570''>two.</span> <span m=''4571630''>[?
  For ?]</span> <span m=''4572660''>connected,</span> <span m=''4573720''>planar</span>
  <span m=''4574560''>graphs.</span> </p><p><span m=''4576810''>There</span> <span
  m=''4577010''>are</span> <span m=''4577030''>other</span> <span m=''4577180''>versions</span>
  <span m=''4577620''>when</span> <span m=''4577740''>you</span> <span m=''4577810''>have</span>
  <span m=''4577950''>multiple</span> <span m=''4578280''>components</span> <span
  m=''4578910''>or</span> <span m=''4579000''>when</span> <span m=''4579130''>you</span>
  <span m=''4579210''>have</span> <span m=''4580950''>tori,</span> <span m=''4581550''>genus,</span>
  <span m=''4582030''>whatever,</span> <span m=''4582420''>but</span> <span m=''4582620''>for</span>
  <span m=''4582850''>convex</span> <span m=''4583250''>polyhedra,</span> <span m=''4583710''>this</span>
  <span m=''4583900''>is</span> <span m=''4584020''>true.</span> <span m=''4584930''>So</span>
  <span m=''4584990''>this</span> <span m=''4585200''>conveniently</span> <span m=''4585650''>relates</span>
  <span m=''4585950''>vertices</span> <span m=''4586360''>to</span> <span m=''4586440''>faces,</span>
  <span m=''4588430''>but</span> <span m=''4588880''>it</span> <span m=''4589060''>involves</span>
  <span m=''4589470''>edges.</span> <span m=''4590790''>So</span> <span m=''4590880''>somehow,</span>
  <span m=''4591080''>I</span> <span m=''4591230''>have</span> <span m=''4591340''>to</span>
  <span m=''4591430''>bring</span> <span m=''4591620''>edges</span> <span m=''4591900''>into</span>
  <span m=''4592070''>the</span> <span m=''4592170''>mix.</span> <span m=''4593616''>All</span>
  <span m=''4594090''>right.</span> <span m=''4594370''>Well,</span> <span m=''4596270''>edges.</span>
  </p><p><span m=''4598930''>I</span> <span m=''4599080''>want</span> <span m=''4599230''>to</span>
  <span m=''4599280''>count</span> <span m=''4599550''>the</span> <span m=''4599620''>number</span>
  <span m=''4599840''>of</span> <span m=''4599940''>edges</span> <span m=''4601190''>in</span>
  <span m=''4601360''>terms</span> <span m=''4601760''>of</span> <span m=''4602810''>the</span>
  <span m=''4602910''>number</span> <span m=''4603130''>of</span> <span m=''4603190''>faces.</span>
  <span m=''4603720''>I</span> <span m=''4603790''>could</span> <span m=''4603940''>do
  it</span> <span m=''4604040''>in</span> <span m=''4604110''>terms</span> <span m=''4604300''>of</span>
  <span m=''4604370''>vertices</span> <span m=''4604990''>or</span> <span m=''4605080''>faces.</span>
  <span m=''4605500''>The number</span> <span m=''4605690''>of</span> <span m=''4605760''>edges</span>
  <span m=''4606100''>is</span> <span m=''4606230''>half</span> <span m=''4607360''>the</span>
  <span m=''4607470''>sum</span> <span m=''4607710''>of</span> <span m=''4607770''>the</span>
  <span m=''4607840''>degrees</span> <span m=''4608160''>of</span> <span m=''4608220''>the</span>
  <span m=''4608290''>vertices.</span> <span m=''4609310''>Remember,</span> <span
  m=''4609520''>that''s</span> <span m=''4609770''>handshaking</span> <span m=''4610320''>lemma</span>
  <span m=''4610760''>from</span> <span m=''4611130''>way</span> <span m=''4611250''>back</span>
  <span m=''4611490''>when.</span> </p><p><span m=''4612240''>It''s</span> <span m=''4612430''>also</span>
  <span m=''4613660''>half</span> <span m=''4614260''>the</span> <span m=''4614380''>sum</span>
  <span m=''4614690''>of</span> <span m=''4614800''>the</span> <span m=''4614900''>degrees</span>
  <span m=''4615280''>of</span> <span m=''4615360''>the</span> <span m=''4615440''>faces.</span>
  <span m=''4617200''>If</span> <span m=''4617300''>I</span> <span m=''4617400''>look</span>
  <span m=''4617630''>at</span> <span m=''4617690''>every</span> <span m=''4617920''>face</span>
  <span m=''4618520''>and</span> <span m=''4618710''>I</span> <span m=''4618780''>count</span>
  <span m=''4619040''>the</span> <span m=''4619120''>number</span> <span m=''4619350''>of</span>
  <span m=''4619420''>edges,</span> <span m=''4620170''>I</span> <span m=''4620320''>will</span>
  <span m=''4620540''>end</span> <span m=''4620640''>up</span> <span m=''4621190''>counting</span>
  <span m=''4621490''>every</span> <span m=''4621700''>edge</span> <span m=''4621870''>twice,</span>
  <span m=''4622300''>once</span> <span m=''4622560''>from</span> <span m=''4622690''>each</span>
  <span m=''4622820''>side,</span> <span m=''4624180''>so</span> <span m=''4624370''>this</span>
  <span m=''4624630''>is</span> <span m=''4625250''>half</span> <span m=''4626030''>the</span>
  <span m=''4626120''>number</span> <span m=''4626370''>of</span> <span m=''4626440''>faces.</span>
  <span m=''4627515''>Well,</span> <span m=''4627810''>number</span> <span m=''4628070''>faces</span>
  <span m=''4628560''>I</span> <span m=''4628640''>want</span> <span m=''4628810''>to</span>
  <span m=''4628890''>write</span> <span m=''4629050''>in</span> <span m=''4629130''>this</span>
  <span m=''4629360''>form.</span> <span m=''4630240''>So</span> <span m=''4630370''>this</span>
  <span m=''4630540''>is</span> <span m=''4630640''>half</span> <span m=''4632260''>2--</span>
  <span m=''4632820''>No,</span> <span m=''4633060''>sorry.</span> </p><p><span m=''4635570''>Not
  the</span> <span m=''4635790''>number</span> <span m=''4636060''>faces.</span> <span
  m=''4636320''>What</span> <span m=''4636580''>am</span> <span m=''4636810''>I doing?</span>
  <span m=''4638460''>Half</span> <span m=''4638840''>the</span> <span m=''4638950''>sum</span>
  <span m=''4639470''>of</span> <span m=''4639630''>the</span> <span m=''4639730''>degrees</span>
  <span m=''4640210''>of</span> <span m=''4640290''>the</span> <span m=''4640370''>faces.</span>
  <span m=''4643810''>So</span> <span m=''4644110''>this</span> <span m=''4644320''>is</span>
  <span m=''4644460''>half--</span> <span m=''4645470''>what is</span> <span m=''4645720''>the</span>
  <span m=''4645800''>degree</span> <span m=''4646280''>of</span> <span m=''4647490''>degree</span>
  <span m=''4647740''>3</span> <span m=''4647950''>faces?</span> <span m=''4648690''>3.</span>
  <span m=''4650340''>What</span> <span m=''4650530''>is</span> <span m=''4650620''>the</span>
  <span m=''4650710''>degree</span> <span m=''4651050''>of</span> <span m=''4651120''>degree</span>
  <span m=''4651380''>4</span> <span m=''4651580''>faces?</span> <span m=''4652110''>4.</span>
  <span m=''4653110''>And so on.</span> <span m=''4661880''>Exactly.</span> </p><p><span
  m=''4665660''>So</span> <span m=''4665800''>now,</span> <span m=''4666060''>things</span>
  <span m=''4666310''>are</span> <span m=''4666380''>starting</span> <span m=''4666650''>to</span>
  <span m=''4666730''>look</span> <span m=''4666930''>similar,</span> <span m=''4667400''>and</span>
  <span m=''4667520''>I</span> <span m=''4667550''>want</span> <span m=''4667730''>to</span>
  <span m=''4667770''>get</span> <span m=''4667910''>some</span> <span m=''4668040''>cancellation</span>
  <span m=''4668650''>going</span> <span m=''4669120''>on.</span> <span m=''4671300''>Use</span>
  <span m=''4671510''>my</span> <span m=''4671620''>cheat</span> <span m=''4671870''>sheet</span>
  <span m=''4672150''>here.</span> <span m=''4673530''>I''m</span> <span m=''4673920''>going</span>
  <span m=''4674040''>to</span> <span m=''4674140''>rewrite</span> <span m=''4674570''>this</span>
  <span m=''4674790''>formula</span> <span m=''4676120''>as V</span> <span m=''4676490''>equals</span>
  <span m=''4678100''>2</span> <span m=''4678930''>plus</span> <span m=''4679490''>E</span>
  <span m=''4680280''>minus</span> <span m=''4680810''>F.</span> <span m=''4681910''>Hopefully,</span>
  <span m=''4682130''>that''s</span> <span m=''4682340''>the</span> <span m=''4682420''>same.</span>
  <span m=''4682830''>I put E</span> <span m=''4683320''>over</span> <span m=''4683500''>here.</span>
  <span m=''4684270''>I put</span> <span m=''4684460''>F</span> <span m=''4684650''>over</span>
  <span m=''4684820''>there.</span> <span m=''4685495''>We''ll</span> <span m=''4685780''>get</span>
  <span m=''4685920''>this.</span> </p><p><span m=''4687650''>OK.</span> <span m=''4688260''>So</span>
  <span m=''4688430''>now,</span> <span m=''4688550''>I</span> <span m=''4688620''>have</span>
  <span m=''4688830''>E</span> <span m=''4689000''>minus</span> <span m=''4689340''>F.</span>
  <span m=''4689765''>E</span> <span m=''4690190''>is</span> <span m=''4690330''>this.</span>
  <span m=''4692790''>F--</span> <span m=''4695670''>I</span> <span m=''4695700''>have</span>
  <span m=''4695950''>F.</span> <span m=''4705492''>Am</span> <span m=''4705990''>I</span>
  <span m=''4706140''>missing</span> <span m=''4706410''>something</span> <span m=''4706740''>here?</span>
  <span m=''4709390''>I''ll</span> <span m=''4709480''>write</span> <span m=''4709620''>the</span>
  <span m=''4709700''>next</span> <span m=''4709940''>one,</span> <span m=''4710810''>and</span>
  <span m=''4711075''>I''ll</span> <span m=''4711670''>figure</span> <span m=''4711980''>out</span>
  <span m=''4712060''>where</span> <span m=''4712180''>it</span> <span m=''4712240''>came</span>
  <span m=''4712430''>from.</span> </p><p><span m=''4732800''>Oh,</span> <span m=''4733774''>duh,</span>
  <span m=''4734261''>I</span> <span m=''4734750''>just</span> <span m=''4734860''>skipped</span>
  <span m=''4735090''>a</span> <span m=''4735140''>step.</span> <span m=''4735690''>F</span>
  <span m=''4736490''>is</span> <span m=''4736680''>the</span> <span m=''4736770''>sum</span>
  <span m=''4737170''>of</span> <span m=''4737310''>f3</span> <span m=''4737710''>plus</span>
  <span m=''4738040''>f4</span> <span m=''4738290''>plus</span> <span m=''4738520''>f5</span>
  <span m=''4738850''>plus</span> <span m=''4738970''>f6.</span> <span m=''4739620''>OK?</span>
  <span m=''4740215''>All</span> <span m=''4740540''>I</span> <span m=''4740760''>did</span>
  <span m=''4740940''>here</span> <span m=''4741180''>was</span> <span m=''4741400''>decrease</span>
  <span m=''4741970''>by--</span> <span m=''4742750''>well,</span> <span m=''4743020''>because</span>
  <span m=''4743240''>there''s</span> <span m=''4743370''>a</span> <span m=''4743420''>half</span>
  <span m=''4743760''>out</span> <span m=''4743850''>here,</span> <span m=''4744030''>I</span>
  <span m=''4744180''>decrease</span> <span m=''4744530''>each</span> <span m=''4745000''>coefficient</span>
  <span m=''4745540''>by</span> <span m=''4745660''>2,</span> <span m=''4747270''>nothing</span>
  <span m=''4747710''>surprising.</span> <span m=''4749204''>Whew!</span> <span m=''4751470''>So</span>
  <span m=''4751720''>I</span> <span m=''4751840''>took</span> <span m=''4751920''>E,</span>
  <span m=''4752360''>I</span> <span m=''4752440''>subtracted</span> <span m=''4752940''>F,</span>
  <span m=''4754200''>just</span> <span m=''4754490''>took</span> <span m=''4754690''>away</span>
  <span m=''4755310''>one</span> <span m=''4755510''>of</span> <span m=''4755590''>each.</span>
  <span m=''4756610''>Now,</span> <span m=''4756700''>I</span> <span m=''4756800''>have</span>
  <span m=''4756930''>this</span> <span m=''4757090''>formula.</span> <span m=''4757670''>That''s</span>
  <span m=''4757950''>V.</span> </p><p><span m=''4758690''>Now,</span> <span m=''4759190''>I</span>
  <span m=''4759460''>also</span> <span m=''4759870''>know</span> <span m=''4761700''>that</span>
  <span m=''4762010''>4V</span> <span m=''4763062''>is</span> <span m=''4763420''>at</span>
  <span m=''4763520''>most,</span> <span m=''4763850''>the</span> <span m=''4763920''>number
  of</span> <span m=''4764210''>alternations.</span> <span m=''4766538''>Hm.</span>
  <span m=''4767430''>So</span> <span m=''4767850''>I</span> <span m=''4767890''>could</span>
  <span m=''4768040''>get</span> <span m=''4768140''>a</span> <span m=''4768180''>formula</span>
  <span m=''4768480''>for</span> <span m=''4768610''>4V</span> <span m=''4769070''>here.</span>
  <span m=''4769400''>Right?</span> <span m=''4769790''>4V</span> <span m=''4770140''>is</span>
  <span m=''4771140''>going</span> <span m=''4771300''>to</span> <span m=''4771380''>be</span>
  <span m=''4771640''>8</span> <span m=''4772500''>plus</span> <span m=''4773340''>this</span>
  <span m=''4773700''>is</span> <span m=''4773840''>going</span> <span m=''4773970''>to</span>
  <span m=''4774030''>be</span> <span m=''4774190''>like</span> <span m=''4774470''>2.</span>
  <span m=''4776230''>So</span> <span m=''4776500''>I</span> <span m=''4776590''>get</span>
  <span m=''4776830''>2</span> <span m=''4777330''>f3</span> <span m=''4778870''>plus--</span>
  <span m=''4779245''>oh boy,</span> <span m=''4779620''>1</span> <span m=''4780720''>times--</span>
  <span m=''4780940''>4</span> <span m=''4781350''>times</span> <span m=''4781720''>f4</span>
  <span m=''4783670''>plus--</span> <span m=''4785910''>just</span> <span m=''4786130''>double</span>
  <span m=''4786370''>these</span> <span m=''4786580''>numbers--</span> <span m=''4787260''>6</span>
  <span m=''4787670''>times</span> <span m=''4787890''>f5</span> <span m=''4788780''>plus--</span>
  <span m=''4790285''>what''s</span> <span m=''4790570''>the</span> <span m=''4790650''>next</span>
  <span m=''4790880''>one?</span> <span m=''4790990''>4--</span> <span m=''4791836''>8</span>
  <span m=''4792260''>times</span> <span m=''4792540''>f6,</span> <span m=''4794000''>and</span>
  <span m=''4794210''>so</span> <span m=''4794760''>on.</span> <span m=''4804470''>Yes.</span>
  <span m=''4806240''>OK.</span> </p><p><span m=''4806790''>Now,</span> <span m=''4810730''>these</span>
  <span m=''4810980''>guys</span> <span m=''4812710''>look</span> <span m=''4812920''>very</span>
  <span m=''4813320''>similar</span> <span m=''4814710''>to</span> <span m=''4814880''>these</span>
  <span m=''4815140''>guys.</span> <span m=''4818560''>Now,</span> <span m=''4818710''>here
  it</span> <span m=''4819000''>gets</span> <span m=''4819220''>bigger.</span> <span
  m=''4820330''>8.</span> <span m=''4820600''>It''s</span> <span m=''4820870''>going</span>
  <span m=''4820980''>to go</span> <span m=''4821170''>10,</span> <span m=''4821710''>instead
  of</span> <span m=''4821940''>6</span> <span m=''4822290''>and</span> <span m=''4822390''>7.</span>
  <span m=''4823670''>We</span> <span m=''4823810''>also</span> <span m=''4824020''>have</span>
  <span m=''4824120''>a</span> <span m=''4824180''>plus</span> <span m=''4824460''>8.</span>
  <span m=''4825080''>We</span> <span m=''4825200''>don''t</span> <span m=''4825320''>know</span>
  <span m=''4825470''>whether</span> <span m=''4825660''>there</span> <span m=''4825820''>any</span>
  <span m=''4825980''>faces</span> <span m=''4826350''>of</span> <span m=''4826440''>degree</span>
  <span m=''4826680''>6</span> <span m=''4826990''>or</span> <span m=''4827050''>more,</span>
  <span m=''4827660''>so</span> <span m=''4827940''>we</span> <span m=''4828040''>can''t</span>
  <span m=''4828250''>rely</span> <span m=''4828510''>on</span> <span m=''4828590''>that,</span>
  <span m=''4828750''>but</span> <span m=''4828840''>we</span> <span m=''4828920''>have</span>
  <span m=''4829020''>plus</span> <span m=''4829310''>8.</span> </p><p><span m=''4829790''>So</span>
  <span m=''4829880''>somehow,</span> <span m=''4831270''>4V,</span> <span m=''4831630''>which</span>
  <span m=''4832740''>is,</span> <span m=''4832830''>at</span> <span m=''4832950''>most,</span>
  <span m=''4833410''>the</span> <span m=''4833500''>number of</span> <span m=''4833740''>alternations--</span>
  <span m=''4834420''>that''s</span> <span m=''4834860''>the</span> <span m=''4834980''>reverse</span>
  <span m=''4835320''>of what</span> <span m=''4835480''>we</span> <span m=''4835550''>said</span>
  <span m=''4835730''>before--</span> <span m=''4836760''>4V</span> <span m=''4837070''>is,</span>
  <span m=''4837400''>at</span> <span m=''4837500''>most,</span> <span m=''4837830''>this</span>
  <span m=''4838010''>number,</span> <span m=''4838600''>and</span> <span m=''4838760''>yet,
  it''s</span> <span m=''4838970''>also</span> <span m=''4839350''>equal</span> <span
  m=''4839700''>to</span> <span m=''4839810''>this</span> <span m=''4840030''>number.</span>
  <span m=''4840670''>It</span> <span m=''4840820''>can''t</span> <span m=''4841060''>be</span>
  <span m=''4841200''>both.</span> <span m=''4841620''>This</span> <span m=''4841820''>number''s</span>
  <span m=''4842140''>at</span> <span m=''4842210''>least</span> <span m=''4842540''>8</span>
  <span m=''4842680''>larger</span> <span m=''4843020''>than</span> <span m=''4843150''>this</span>
  <span m=''4843310''>number.</span> <span m=''4843680''>It</span> <span m=''4844070''>could</span>
  <span m=''4844220''>be</span> <span m=''4844310''>even</span> <span m=''4844750''>more</span>
  <span m=''4844980''>larger,</span> <span m=''4845520''>but</span> <span m=''4846110''>at</span>
  <span m=''4846210''>least</span> <span m=''4846380''>that</span> <span m=''4847070''>contradiction</span>
  <span m=''4847850''>done.</span> </p><p><span m=''4849320''>This</span> <span m=''4849510''>works</span>
  <span m=''4849800''>as</span> <span m=''4849900''>long</span> <span m=''4850120''>as</span>
  <span m=''4850210''>there''s</span> <span m=''4850370''>at</span> <span m=''4850440''>least</span>
  <span m=''4850740''>one</span> <span m=''4850920''>face,</span> <span m=''4851750''>meaning</span>
  <span m=''4852090''>there''s</span> <span m=''4852260''>at</span> <span m=''4852320''>least</span>
  <span m=''4852610''>1</span> <span m=''4853010''>plus</span> <span m=''4853250''>or</span>
  <span m=''4853290''>minus</span> <span m=''4854310''>because</span> <span m=''4854420''>we''re</span>
  <span m=''4854570''>only</span> <span m=''4854720''>looking</span> <span m=''4854930''>at</span>
  <span m=''4855010''>the</span> <span m=''4855090''>subgraph</span> <span m=''4855710''>plus</span>
  <span m=''4856200''>and</span> <span m=''4856350''>minus</span> <span m=''4856700''>edges.</span>
  <span m=''4857530''>And</span> <span m=''4857700''>that</span> <span m=''4857860''>is</span>
  <span m=''4857960''>Cauchy''s</span> <span m=''4858280''>rigidity</span> <span m=''4858750''>theorem.</span>
  </p><p><span m=''4859320''>Let</span> <span m=''4859450''>me</span> <span m=''4859540''>quickly</span>
  <span m=''4859900''>tell</span> <span m=''4860140''>you</span> <span m=''4862050''>in</span>
  <span m=''4862260''>our</span> <span m=''4862430''>situation,</span> <span m=''4865010''>here,</span>
  <span m=''4865470''>we</span> <span m=''4865600''>don''t</span> <span m=''4865770''>actually</span>
  <span m=''4866070''>necessarily</span> <span m=''4866470''>know</span> <span m=''4866610''>where</span>
  <span m=''4866690''>the</span> <span m=''4866790''>creases</span> <span m=''4867190''>are.</span>
  <span m=''4867410''>We</span> <span m=''4867530''>just</span> <span m=''4867780''>know</span>
  <span m=''4867910''>how</span> <span m=''4868100''>things</span> <span m=''4868330''>are</span>
  <span m=''4868410''>glued</span> <span m=''4868630''>together.</span> <span m=''4870430''>Even</span>
  <span m=''4870690''>in</span> <span m=''4870780''>that</span> <span m=''4870990''>situation,</span>
  <span m=''4871490''>you</span> <span m=''4871630''>could</span> <span m=''4871760''>sort</span>
  <span m=''4871940''>of</span> <span m=''4872010''>figure</span> <span m=''4872290''>out</span>
  <span m=''4872430''>where the</span> <span m=''4872560''>creases</span> <span m=''4872940''>must</span>
  <span m=''4873350''>be</span> <span m=''4874110''>because</span> <span m=''4874420''>as</span>
  <span m=''4874580''>I</span> <span m=''4874640''>said,</span> <span m=''4874890''>you</span>
  <span m=''4875010''>can</span> <span m=''4875150''>compute</span> <span m=''4875490''>shortest</span>
  <span m=''4875830''>paths</span> <span m=''4876170''>once</span> <span m=''4876350''>you</span>
  <span m=''4876440''>have</span> <span m=''4876610''>the</span> <span m=''4876720''>gluing.</span>
  <span m=''4877360''>So</span> <span m=''4877480''>you</span> <span m=''4877530''>compute</span>
  <span m=''4877830''>the</span> <span m=''4877910''>shortest</span> <span m=''4878220''>paths</span>
  <span m=''4878440''>between</span> <span m=''4878730''>all</span> <span m=''4878940''>pairs</span>
  <span m=''4879210''>of</span> <span m=''4879270''>vertices,</span> <span m=''4879770''>something</span>
  <span m=''4880100''>like</span> <span m=''4880260''>this</span> <span m=''4880420''>picture,</span>
  <span m=''4880710''>except</span> <span m=''4881000''>you</span> <span m=''4881080''>don''t</span>
  <span m=''4881260''>know</span> <span m=''4881360''>what</span> <span m=''4881450''>it</span>
  <span m=''4881510''>looks</span> <span m=''4881710''>like</span> <span m=''4881860''>in</span>
  <span m=''4881950''>3D.</span> </p><p><span m=''4883040''>You can</span> <span m=''4883240''>still</span>
  <span m=''4883370''>compute</span> <span m=''4883660''>the</span> <span m=''4884020''>shortest
  paths.</span> <span m=''4884180''>You know every</span> <span m=''4884650''>edge</span>
  <span m=''4885020''>must</span> <span m=''4885320''>be a</span> <span m=''4885450''>shortest</span>
  <span m=''4885830''>path.</span> <span m=''4887030''>So</span> <span m=''4887070''>the</span>
  <span m=''4887210''>edges</span> <span m=''4887530''>are</span> <span m=''4887630''>some</span>
  <span m=''4887900''>subset</span> <span m=''4888320''>of</span> <span m=''4888380''>these</span>
  <span m=''4888570''>guys.</span> <span m=''4889660''>And</span> <span m=''4889860''>so</span>
  <span m=''4889950''>you''ve</span> <span m=''4890100''>got</span> <span m=''4890270''>lots</span>
  <span m=''4890510''>of</span> <span m=''4890600''>little</span> <span m=''4890970''>convex</span>
  <span m=''4891370''>polygons</span> <span m=''4891920''>here.</span> <span m=''4893500''>We</span>
  <span m=''4893670''>know</span> <span m=''4893940''>it</span> <span m=''4894040''>must</span>
  <span m=''4894320''>make</span> <span m=''4894470''>a</span> <span m=''4894520''>convex</span>
  <span m=''4894870''>polyhedron.</span> <span m=''4895360''>If</span> <span m=''4895460''>it</span>
  <span m=''4895610''>made</span> <span m=''4895860''>two,</span> <span m=''4897660''>Cauchy''s</span>
  <span m=''4897980''>rigidity</span> <span m=''4898420''>theorem</span> <span m=''4898710''>would
  tell</span> <span m=''4898860''>you</span> <span m=''4898950''>that they''re the</span>
  <span m=''4899330''>same.</span> </p><p><span m=''4900330''>So</span> <span m=''4901050''>even</span>
  <span m=''4901330''>once</span> <span m=''4901530''>you</span> <span m=''4901620''>fix</span>
  <span m=''4901850''>the</span> <span m=''4901930''>gluing, you know that</span>
  <span m=''4902250''>there''s</span> <span m=''4902690''>a</span> <span m=''4902730''>unique</span>
  <span m=''4903370''>convex</span> <span m=''4904320''>realization,</span> <span
  m=''4906590''>and</span> <span m=''4906730''>there</span> <span m=''4906810''>will</span>
  <span m=''4906930''>be</span> <span m=''4907150''>a</span> <span m=''4907180''>unique</span>
  <span m=''4907640''>set</span> <span m=''4907860''>of</span> <span m=''4908050''>edges</span>
  <span m=''4909050''>from</span> <span m=''4909280''>the</span> <span m=''4909390''>shortest</span>
  <span m=''4909710''>paths that</span> <span m=''4910030''>actually</span> <span
  m=''4910360''>realize</span> <span m=''4910780''>it.</span> <span m=''4911340''>The</span>
  <span m=''4911470''>next</span> <span m=''4911700''>class</span> <span m=''4912020''>will</span>
  <span m=''4912170''>be</span> <span m=''4912420''>all</span> <span m=''4912570''>about</span>
  <span m=''4913420''>how</span> <span m=''4913610''>to</span> <span m=''4913660''>actually</span>
  <span m=''4913890''>find</span> <span m=''4914220''>those</span> <span m=''4914370''>gluings</span>
  <span m=''4914690''>and</span> <span m=''4914810''>know</span> <span m=''4915070''>that</span>
  <span m=''4915220''>they</span> <span m=''4915300''>actually</span> <span m=''4915600''>will</span>
  <span m=''4915860''>fold</span> <span m=''4916160''>into</span> <span m=''4916360''>some</span>
  <span m=''4916600''>convex</span> <span m=''4916905''>shape</span> <span m=''4917210''>and</span>
  <span m=''4917280''>how</span> <span m=''4917400''>to</span> <span m=''4917470''>find</span>
  <span m=''4917700''>that</span> <span m=''4917830''>convex</span> <span m=''4918290''>shape,</span>
  <span m=''4919451''>but</span> <span m=''4919840''>that''s</span> <span m=''4920010''>it</span>
  <span m=''4920190''>for</span> <span m=''4920330''>today.</span> </p>'
type: course
uid: e705388dec0ac7567a512648dce64949

---
None