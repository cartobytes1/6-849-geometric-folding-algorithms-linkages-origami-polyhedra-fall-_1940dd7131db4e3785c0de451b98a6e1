---
about_this_resource_text: <p><strong>Description:</strong> This lecture introduces
  universal hinge patterns with the cube and maze gadget. NP-hardness problems involving
  partition and satisfiability are presented with examples of simple folds, global
  flat foldability, and disk packing.</p><p><strong>Speaker:</strong> Erik Demaine</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: VQcvVx-niG4
  parent_uid: 74a2c93d8d355de8de36b13e46848214
  title: Video-YouTube-Stream
  type: Video
  uid: 36d382be8ba4840343b92af0db7d741b
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/VQcvVx-niG4/default.jpg
  parent_uid: 74a2c93d8d355de8de36b13e46848214
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 1309ab1d88567629e3f57c12d239704b
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: 74a2c93d8d355de8de36b13e46848214
  title: Video-iTunes U-MP4
  type: Video
  uid: a145877ddf5ab780d3a6d8734eef3032
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_lec07_300k.mp4
  parent_uid: 74a2c93d8d355de8de36b13e46848214
  title: Video-Internet Archive-MP4
  type: Video
  uid: c44f66c2cf7514f150085cc663c5b749
- id: 3Play-3PlayYouTubeid-MP4
  media_location: VQcvVx-niG4
  parent_uid: 74a2c93d8d355de8de36b13e46848214
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 155eaf87879937124281ce4d0bbb4139
- id: VQcvVx-niG4.srt
  parent_uid: 74a2c93d8d355de8de36b13e46848214
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-7-origami-is-hard/VQcvVx-niG4.srt
  title: 3play caption file
  type: null
  uid: f36012b06b0863a16591cf715d7ce727
- id: VQcvVx-niG4.pdf
  parent_uid: 74a2c93d8d355de8de36b13e46848214
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-7-origami-is-hard/VQcvVx-niG4.pdf
  title: 3play pdf file
  type: null
  uid: 0550738bfefc6da5258cd42f452cc2e0
- id: Caption-3Play YouTube id-SRT
  parent_uid: 74a2c93d8d355de8de36b13e46848214
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 1df004d4a9d838e090a26f7377d8a8ad
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 74a2c93d8d355de8de36b13e46848214
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: c25fe6d8715cfb0d14cac854ff879b4b
inline_embed_id: 57864590lecture7:origamiishard20201032
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: lecture-7-origami-is-hard
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-7-origami-is-hard
template_type: Tabbed
title: 'Lecture 7: Origami is Hard'
transcript: '<p><span m=''3420''>PROFESSOR: Continue</span> <span m=''3760''>today.</span>
  <span m=''4230''>We''re</span> <span m=''5060''>still</span> <span m=''5390''>in</span>
  <span m=''5490''>the</span> <span m=''5680''>spirit</span> <span m=''6040''>of</span>
  <span m=''6280''>origami.</span> <span m=''6930''>And</span> <span m=''7430''>we''re</span>
  <span m=''7550''>going</span> <span m=''7670''>to</span> <span m=''7760''>do</span>
  <span m=''7890''>some</span> <span m=''8060''>origami</span> <span m=''8450''>design</span>
  <span m=''9000''>and</span> <span m=''9200''>foldability</span> <span m=''9930''>again.</span>
  <span m=''12830''>There</span> <span m=''13070''>are</span> <span m=''13200''>two</span>
  <span m=''13570''>main</span> <span m=''13910''>topics</span> <span m=''14370''>here</span>
  <span m=''14600''>on</span> <span m=''14700''>the</span> <span m=''14850''>design</span>
  <span m=''15360''>side</span> <span m=''15710''>we''re</span> <span m=''15870''>going</span>
  <span m=''16030''>to</span> <span m=''16940''>talk</span> <span m=''17180''>about--</span>
  <span m=''17680''>universal</span> <span m=''18200''>hinge</span> <span m=''18460''>patterns,</span>
  <span m=''19610''>which</span> <span m=''19930''>are</span> <span m=''20880''>the</span>
  <span m=''21000''>things</span> <span m=''21410''>that</span> <span m=''21610''>make</span>
  <span m=''22720''>underlying</span> <span m=''23280''>this</span> <span m=''23560''>robot,</span>
  <span m=''23940''>which</span> <span m=''24110''>I</span> <span m=''24140''>showed</span>
  <span m=''24400''>in</span> <span m=''24490''>lecture</span> <span m=''24820''>one.</span>
  <span m=''25050''>You</span> <span m=''25150''>may</span> <span m=''25300''>recall.</span>
  <span m=''26150''>So</span> <span m=''26280''>it''s</span> <span m=''26470''>called</span>
  <span m=''26710''>a</span> <span m=''26950''>box</span> <span m=''27310''>pleat</span>
  <span m=''27460''>pattern.</span> <span m=''29030''>It''s</span> <span m=''29080''>a</span>
  <span m=''29810''>square</span> <span m=''30190''>grid</span> <span m=''30530''>with</span>
  <span m=''30710''>alternating</span> <span m=''31170''>diagonal</span> <span m=''31590''>creases.</span>
  <span m=''32650''>And</span> <span m=''32780''>the</span> <span m=''32870''>idea</span>
  <span m=''33140''>with</span> <span m=''33240''>the</span> <span m=''33340''>robot</span>
  <span m=''33720''>is</span> <span m=''33810''>you''re</span> <span m=''33960''>constrained</span>
  <span m=''34760''>to</span> <span m=''35000''>only--</span> <span m=''36090''>you</span>
  <span m=''36210''>have</span> <span m=''36350''>to</span> <span m=''36450''>build</span>
  <span m=''36710''>the</span> <span m=''36800''>creases</span> <span m=''37340''>ahead</span>
  <span m=''37560''>of</span> <span m=''37640''>time.</span> <span m=''37950''>You
  can''t</span> <span m=''38370''>say,</span> <span m=''39150''>you</span> <span m=''39680''>can''t</span>
  <span m=''39850''>build</span> <span m=''40020''>one</span> <span m=''40220''>sheet</span>
  <span m=''40440''>that</span> <span m=''40530''>can fold</span> <span m=''40880''>anywhere</span>
  <span m=''41330''>at</span> <span m=''41380''>anytime.</span> <span m=''42450''>You</span>
  <span m=''42560''>want</span> <span m=''42700''>to</span> <span m=''42760''>build</span>
  <span m=''42970''>a</span> <span m=''43000''>sheet</span> <span m=''43320''>that
  can</span> <span m=''43500''>fold</span> <span m=''44510''>at</span> <span m=''44650''>any</span>
  <span m=''44870''>of</span> <span m=''44920''>the</span> <span m=''45000''>crease</span>
  <span m=''45290''>lines,</span> <span m=''45850''>at</span> <span m=''47020''>the</span>
  <span m=''47100''>built</span> <span m=''47450''>crease</span> <span m=''47790''>lines</span>
  <span m=''48290''>whenever</span> <span m=''48620''>you</span> <span m=''48760''>want.</span>
  </p><p><span m=''49870''>And</span> <span m=''50120''>so</span> <span m=''51640''>whereas
  with</span> <span m=''52030''>something</span> <span m=''52360''>like</span> <span
  m=''52810''>Origamizer,</span> <span m=''53860''>every</span> <span m=''54270''>design</span>
  <span m=''54900''>has</span> <span m=''55160''>a</span> <span m=''55210''>completely</span>
  <span m=''55730''>different</span> <span m=''56020''>crease</span> <span m=''56220''>pattern</span>
  <span m=''57230''>and</span> <span m=''57540''>it''s</span> <span m=''57740''>difficult</span>
  <span m=''58180''>to</span> <span m=''58280''>control</span> <span m=''58670''>that,</span>
  <span m=''59370''>here</span> <span m=''59570''>we</span> <span m=''59680''>wanted</span>
  <span m=''59980''>to</span> <span m=''60070''>make</span> <span m=''60240''>one.</span>
  <span m=''61660''>It''s</span> <span m=''61770''>not</span> <span m=''61940''>exactly</span>
  <span m=''62300''>a crease</span> <span m=''62530''>pattern,</span> <span m=''62770''>because</span>
  <span m=''62910''>you''re</span> <span m=''63010''>not</span> <span m=''63180''>using</span>
  <span m=''63480''>all</span> <span m=''63600''>the</span> <span m=''63690''>creases.</span>
  <span m=''63990''>It''s</span> <span m=''64290''>what</span> <span m=''64430''>we</span>
  <span m=''64530''>call</span> <span m=''64700''>a</span> <span m=''64720''>hinge</span>
  <span m=''65120''>pattern,</span> <span m=''65590''>all</span> <span m=''65780''>the</span>
  <span m=''65860''>possible</span> <span m=''66410''>places</span> <span m=''66800''>you</span>
  <span m=''66940''>could</span> <span m=''67170''>fold</span> <span m=''67440''>that</span>
  <span m=''67660''>thing</span> <span m=''68710''>and</span> <span m=''69080''>make</span>
  <span m=''69300''>lots</span> <span m=''69640''>of</span> <span m=''69720''>different</span>
  <span m=''69990''>shapes</span> <span m=''70520''>from</span> <span m=''70750''>that</span>
  <span m=''70950''>one</span> <span m=''71640''>hinge</span> <span m=''71870''>pattern.</span>
  <span m=''73300''>So</span> <span m=''75670''>that''s</span> <span m=''75930''>the</span>
  <span m=''76040''>first</span> <span m=''76450''>part</span> <span m=''76640''>of
  the lecture.</span> </p><p><span m=''77110''>And the</span> <span m=''77180''>second</span>
  <span m=''77480''>part</span> <span m=''77640''>of the</span> <span m=''77700''>lecture</span>
  <span m=''78020''>will</span> <span m=''78100''>be</span> <span m=''78220''>about</span>
  <span m=''78440''>hardness.</span> <span m=''79130''>And</span> <span m=''79290''>we''ll</span>
  <span m=''79420''>see,</span> <span m=''80060''>I</span> <span m=''80110''>think,</span>
  <span m=''80340''>four</span> <span m=''80750''>different</span> <span m=''81120''>kinds</span>
  <span m=''81550''>of</span> <span m=''81780''>origami</span> <span m=''82290''>problems</span>
  <span m=''82770''>which</span> <span m=''82950''>are</span> <span m=''83040''>all</span>
  <span m=''83510''>NP-hard.</span> <span m=''84460''>And</span> <span m=''84650''>I''ll</span>
  <span m=''84790''>tell</span> <span m=''84950''>you</span> <span m=''85080''>what</span>
  <span m=''85180''>NP-hard</span> <span m=''85620''>means.</span> <span m=''86360''>And</span>
  <span m=''86970''>we''ll</span> <span m=''87830''>prove</span> <span m=''88070''>all</span>
  <span m=''88200''>that.</span> <span m=''88450''>So</span> <span m=''88560''>there
  are</span> <span m=''88660''>lots</span> <span m=''88870''>of</span> <span m=''88910''>problems</span>
  <span m=''89230''>that</span> <span m=''89340''>are</span> <span m=''89430''>computationally</span>
  <span m=''89990''>intractable.</span> <span m=''91430''>And</span> <span m=''91690''>we''re</span>
  <span m=''91800''>going</span> <span m=''91910''>to</span> <span m=''92230''>cluster</span>
  <span m=''92560''>them</span> <span m=''92690''>all</span> <span m=''92910''>together</span>
  <span m=''93330''>into</span> <span m=''93530''>one</span> <span m=''95000''>lecture.</span>
  <span m=''95750''>Because</span> <span m=''95940''>it''s</span> <span m=''96060''>kind</span>
  <span m=''96210''>of</span> <span m=''96290''>fun</span> <span m=''96500''>to see</span>
  <span m=''96670''>them</span> <span m=''96800''>together.</span> <span m=''98540''>Mostly</span>
  <span m=''98930''>we''ve been</span> <span m=''99050''>talking</span> <span m=''99330''>about</span>
  <span m=''99740''>positive</span> <span m=''100160''>results</span> <span m=''101280''>so</span>
  <span m=''101480''>far.</span> </p><p><span m=''102780''>All</span> <span m=''102860''>right,</span>
  <span m=''103090''>so</span> <span m=''103200''>let''s</span> <span m=''103520''>do</span>
  <span m=''103840''>universal</span> <span m=''104330''>hinge</span> <span m=''104590''>patterns.</span>
  <span m=''115860''>This</span> <span m=''116020''>is</span> <span m=''116110''>pretty</span>
  <span m=''116370''>recent</span> <span m=''116670''>work.</span> <span m=''116890''>It</span>
  <span m=''117000''>just</span> <span m=''117220''>appeared</span> <span m=''117580''>at</span>
  <span m=''117760''>the</span> <span m=''118060''>big</span> <span m=''118290''>origami</span>
  <span m=''118690''>math</span> <span m=''118980''>conference</span> <span m=''119400''>this</span>
  <span m=''119530''>summer.</span> <span m=''120640''>And</span> <span m=''120960''>its</span>
  <span m=''121540''>work</span> <span m=''122000''>by</span> <span m=''122380''>Nadia,</span>
  <span m=''123460''>and</span> <span m=''123480''>me,</span> <span m=''124150''>and</span>
  <span m=''124230''>Marty,</span> <span m=''124650''>and</span> <span m=''124900''>Aviv</span>
  <span m=''124960''>Ovadya,</span> <span m=''126370''>who</span> <span m=''127780''>I</span>
  <span m=''127870''>think</span> <span m=''128150''>actually</span> <span m=''128460''>came</span>
  <span m=''128690''>out</span> <span m=''128789''>of</span> <span m=''128870''>this</span>
  <span m=''129060''>class</span> <span m=''129380''>three</span> <span m=''129550''>years</span>
  <span m=''129770''>ago,</span> <span m=''130039''>if</span> <span m=''130150''>I</span>
  <span m=''130229''>recall.</span> <span m=''130720''>It</span> <span m=''131160''>just</span>
  <span m=''131360''>took</span> <span m=''131510''>us</span> <span m=''131640''>awhile</span>
  <span m=''131960''>to</span> <span m=''132110''>write</span> <span m=''132310''>it</span>
  <span m=''132390''>all</span> <span m=''132850''>up.</span> <span m=''135530''>And</span>
  <span m=''135710''>it''s</span> <span m=''135850''>why</span> <span m=''136420''>the</span>
  <span m=''136630''>robot</span> <span m=''137050''>has</span> <span m=''137300''>a</span>
  <span m=''137360''>box</span> <span m=''137690''>pleat</span> <span m=''137820''>pattern.</span>
  <span m=''142140''>So</span> <span m=''142360''>the</span> <span m=''142490''>idea</span>
  <span m=''142740''>is</span> <span m=''143070''>to</span> <span m=''143260''>require</span>
  <span m=''144490''>that</span> <span m=''144770''>the</span> <span m=''145140''>crease</span>
  <span m=''145400''>pattern</span> <span m=''147090''>of</span> <span m=''147390''>whatever</span>
  <span m=''147650''>you</span> <span m=''147750''>want</span> <span m=''147870''>to</span>
  <span m=''147930''>fold</span> <span m=''150150''>must</span> <span m=''150540''>be</span>
  <span m=''151710''>a</span> <span m=''151800''>subset</span> <span m=''155380''>of</span>
  <span m=''155710''>some</span> <span m=''156260''>fixed</span> <span m=''156710''>hinge</span>
  <span m=''157020''>pattern.</span> </p><p><span m=''161520''>And</span> <span m=''161650''>the</span>
  <span m=''161730''>goal</span> <span m=''162010''>is</span> <span m=''162110''>to</span>
  <span m=''162210''>make</span> <span m=''162410''>one</span> <span m=''162650''>hinge</span>
  <span m=''162910''>pattern</span> <span m=''163790''>to</span> <span m=''163990''>rule</span>
  <span m=''164160''>them</span> <span m=''164310''>all,</span> <span m=''164590''>one</span>
  <span m=''164950''>hinge</span> <span m=''165210''>pattern</span> <span m=''165560''>that
  you</span> <span m=''165770''>can</span> <span m=''165900''>make</span> <span m=''166120''>anything.</span>
  <span m=''167190''>I</span> <span m=''167270''>mean</span> <span m=''167390''>you</span>
  <span m=''167490''>can''t</span> <span m=''167710''>make</span> <span m=''167900''>literally</span>
  <span m=''168300''>anything,</span> <span m=''168780''>I</span> <span m=''169080''>don''t</span>
  <span m=''169340''>think.</span> <span m=''170460''>I</span> <span m=''170570''>was</span>
  <span m=''170680''>wondering</span> <span m=''170930''>about</span> <span m=''171110''>this</span>
  <span m=''171260''>yesterday.</span> <span m=''171720''>But</span> <span m=''173740''>we''re</span>
  <span m=''173960''>not</span> <span m=''174100''>going</span> <span m=''174190''>to</span>
  <span m=''174250''>try</span> <span m=''174520''>to</span> <span m=''174600''>make</span>
  <span m=''174810''>everything</span> <span m=''175750''>out</span> <span m=''175840''>of</span>
  <span m=''175930''>one</span> <span m=''176510''>hinge</span> <span m=''176740''>pattern.</span>
  <span m=''177500''>But</span> <span m=''177670''>we</span> <span m=''177740''>want</span>
  <span m=''177900''>to</span> <span m=''177950''>make</span> <span m=''178160''>lots</span>
  <span m=''178480''>of</span> <span m=''178570''>different</span> <span m=''178880''>things</span>
  <span m=''179410''>somehow</span> <span m=''179760''>from</span> <span m=''180000''>one</span>
  <span m=''180500''>hinge</span> <span m=''180690''>pattern.</span> <span m=''181590''>And</span>
  <span m=''183150''>here''s</span> <span m=''183640''>the</span> <span m=''183790''>theorem</span>
  <span m=''184380''>that</span> <span m=''184720''>formalizes</span> <span m=''185360''>this</span>
  <span m=''185650''>idea</span> <span m=''185990''>of</span> <span m=''186100''>lots</span>
  <span m=''186370''>of</span> <span m=''186440''>things.</span> </p><p><span m=''189650''>We''re</span>
  <span m=''189860''>going</span> <span m=''189980''>to</span> <span m=''190070''>take</span>
  <span m=''190370''>the</span> <span m=''190460''>box</span> <span m=''190760''>pleat</span>
  <span m=''190960''>pattern</span> <span m=''191370''>from</span> <span m=''191790''>an</span>
  <span m=''191880''>n</span> <span m=''192050''>by</span> <span m=''192200''>n.</span>
  <span m=''192360''>Grid</span> <span m=''193810''>so</span> <span m=''194030''>that''s</span>
  <span m=''196120''>you</span> <span m=''196620''>take</span> <span m=''198160''>a</span>
  <span m=''198220''>square</span> <span m=''198550''>grid,</span> <span m=''200780''>n</span>
  <span m=''201020''>by</span> <span m=''201170''>n.</span> <span m=''202220''>And</span>
  <span m=''202400''>then</span> <span m=''202540''>you</span> <span m=''202650''>fill</span>
  <span m=''202940''>in</span> <span m=''203080''>alternating</span> <span m=''203640''>diagonals.</span>
  <span m=''216500''>Then</span> <span m=''217080''>that</span> <span m=''217440''>thing</span>
  <span m=''218840''>that</span> <span m=''219040''>hinge</span> <span m=''219320''>pattern</span>
  <span m=''220350''>can</span> <span m=''220520''>make</span> <span m=''220980''>by</span>
  <span m=''221140''>using</span> <span m=''221470''>a</span> <span m=''221520''>subset</span>
  <span m=''221930''>of</span> <span m=''222040''>those</span> <span m=''222270''>creases,</span>
  <span m=''223350''>you</span> <span m=''223530''>can</span> <span m=''223700''>make</span>
  <span m=''223970''>any</span> <span m=''226220''>polycube</span> <span m=''230790''>of</span>
  <span m=''231000''>n</span> <span m=''231210''>cubes.</span> <span m=''236760''>I''m</span>
  <span m=''236930''>sorry,</span> <span m=''237250''>order</span> <span m=''237510''>n</span>
  <span m=''237720''>cubes.</span> <span m=''243050''>And</span> <span m=''243960''>what</span>
  <span m=''244170''>else?</span> <span m=''245716''>You</span> <span m=''246210''>can</span>
  <span m=''246360''>even</span> <span m=''246590''>do</span> <span m=''246710''>it</span>
  <span m=''246840''>seamless.</span> </p><p><span m=''252420''>So a</span> <span
  m=''252510''>polycube</span> <span m=''253800''>made of</span> <span m=''254200''>n</span>
  <span m=''254400''>cubes</span> <span m=''254850''>is just you</span> <span m=''255020''>take</span>
  <span m=''255380''>n</span> <span m=''255685''>cubes.</span> <span m=''255990''>And</span>
  <span m=''256149''>you</span> <span m=''256260''>start</span> <span m=''256529''>gluing</span>
  <span m=''256800''>them</span> <span m=''256920''>together</span> <span m=''257240''>face</span>
  <span m=''257480''>to</span> <span m=''257570''>face</span> <span m=''257839''>until</span>
  <span m=''258070''>you</span> <span m=''258149''>have</span> <span m=''258320''>one</span>
  <span m=''258519''>connected</span> <span m=''259670''>monster.</span> <span m=''261230''>And</span>
  <span m=''262000''>that''s</span> <span m=''262990''>a</span> <span m=''263070''>polycube.</span>
  <span m=''264160''>So</span> <span m=''264410''>you</span> <span m=''264600''>can</span>
  <span m=''264750''>make,</span> <span m=''265050''>for</span> <span m=''265190''>example,</span>
  <span m=''266530''>I</span> <span m=''266780''>don''t</span> <span m=''267140''>know,
  all the</span> <span m=''267240''>Tetris</span> <span m=''267630''>pieces.</span>
  <span m=''269240''>Tetris</span> <span m=''269610''>pieces</span> <span m=''269970''>would</span>
  <span m=''270160''>be</span> <span m=''270440''>four</span> <span m=''270690''>cubes.</span>
  <span m=''271580''>Normally</span> <span m=''271840''>they''re</span> <span m=''271980''>squares,</span>
  <span m=''273400''>but</span> <span m=''273810''>you</span> <span m=''274220''>can</span>
  <span m=''274630''>3-dimensionalize</span> <span m=''275540''>them.</span> <span
  m=''277890''>That''s</span> <span m=''278120''>a</span> <span m=''278170''>four</span>
  <span m=''278460''>cube</span> <span m=''278580''>polycube.</span> <span m=''279140''>And</span>
  <span m=''279270''>you</span> <span m=''279350''>get</span> <span m=''279950''>the</span>
  <span m=''280060''>general</span> <span m=''280350''>idea.</span> </p><p><span m=''281180''>So</span>
  <span m=''281650''>this</span> <span m=''281970''>is</span> <span m=''282330''>cool</span>
  <span m=''282600''>because</span> <span m=''282910''>there are</span> <span m=''283060''>exponentially</span>
  <span m=''283740''>many</span> <span m=''284330''>polycubes</span> <span m=''284590''>with</span>
  <span m=''285070''>n</span> <span m=''285440''>cubes.</span> <span m=''286250''>And</span>
  <span m=''286510''>here is</span> <span m=''286790''>one</span> <span m=''287110''>pattern</span>
  <span m=''287490''>that</span> <span m=''287570''>can</span> <span m=''287720''>make</span>
  <span m=''287890''>all</span> <span m=''288140''>of</span> <span m=''288250''>them.</span>
  <span m=''289050''>And</span> <span m=''289250''>if</span> <span m=''289360''>you</span>
  <span m=''289480''>imagine</span> <span m=''289840''>some</span> <span m=''290090''>crazy</span>
  <span m=''290470''>3D</span> <span m=''290760''>shape,</span> <span m=''291130''>you</span>
  <span m=''291250''>can,</span> <span m=''291380''>of</span> <span m=''291500''>course,</span>
  <span m=''291860''>approximate</span> <span m=''292255''>it</span> <span m=''292650''>by</span>
  <span m=''293240''>cubes,</span> <span m=''294270''>sort</span> <span m=''294500''>of</span>
  <span m=''294570''>voxelization is</span> <span m=''295000''>the</span> <span m=''295850''>usual</span>
  <span m=''296140''>term,</span> <span m=''296880''>the</span> <span m=''296980''>same</span>
  <span m=''297170''>way</span> <span m=''297310''>that we</span> <span m=''297450''>pixelize</span>
  <span m=''297930''>images.</span> <span m=''298960''>And</span> <span m=''299810''>then</span>
  <span m=''299970''>you</span> <span m=''300100''>can</span> <span m=''300210''>make</span>
  <span m=''300490''>basically</span> <span m=''300860''>anything</span> <span m=''301180''>you</span>
  <span m=''301310''>want</span> <span m=''301600''>up</span> <span m=''301820''>to</span>
  <span m=''302100''>the</span> <span m=''302280''>resolution</span> <span m=''302890''>provided</span>
  <span m=''303400''>by</span> <span m=''304000''>your</span> <span m=''304140''>sheet.</span>
  <span m=''304670''>So</span> <span m=''304840''>that''s</span> <span m=''305100''>the</span>
  <span m=''305190''>sense</span> <span m=''305460''>in</span> <span m=''305520''>which</span>
  <span m=''305690''>this</span> <span m=''305870''>is</span> <span m=''305980''>universal.</span>
  </p><p><span m=''312650''>So</span> <span m=''314010''>let''s</span> <span m=''314200''>prove</span>
  <span m=''314400''>that.</span> <span m=''315500''>It''s</span> <span m=''315660''>actually</span>
  <span m=''316920''>not</span> <span m=''317190''>too</span> <span m=''317360''>hard</span>
  <span m=''317700''>to</span> <span m=''317810''>do</span> <span m=''318100''>in</span>
  <span m=''318190''>at</span> <span m=''318270''>least</span> <span m=''318950''>one</span>
  <span m=''319200''>way.</span> <span m=''320890''>The</span> <span m=''321070''>first</span>
  <span m=''321500''>idea</span> <span m=''321870''>is</span> <span m=''322200''>to</span>
  <span m=''322610''>build</span> <span m=''322830''>something</span> <span m=''323190''>called</span>
  <span m=''324642''>a</span> <span m=''325140''>cube</span> <span m=''325440''>gadget.</span>
  <span m=''328790''>We''re</span> <span m=''328800''>going</span> <span m=''328900''>to</span>
  <span m=''328940''>use</span> <span m=''329120''>the</span> <span m=''329230''>idea</span>
  <span m=''329460''>of</span> <span m=''329500''>a</span> <span m=''329580''>gadget</span>
  <span m=''329970''>a</span> <span m=''330030''>lot,</span> <span m=''330530''>especially</span>
  <span m=''330940''>in</span> <span m=''331000''>this</span> <span m=''331180''>lecture.</span>
  <span m=''331700''>But</span> <span m=''331830''>in</span> <span m=''331920''>general,</span>
  <span m=''332220''>it''s</span> <span m=''332360''>a</span> <span m=''332420''>useful</span>
  <span m=''332750''>algorithmic</span> <span m=''333180''>tool.</span> <span m=''333510''>A</span>
  <span m=''333830''>gadget</span> <span m=''334190''>is</span> <span m=''334300''>just</span>
  <span m=''334470''>something</span> <span m=''334800''>that</span> <span m=''335230''>you</span>
  <span m=''335470''>reuse</span> <span m=''336020''>many</span> <span m=''336270''>times.</span>
  <span m=''337270''>It''s</span> <span m=''337450''>like</span> <span m=''337640''>a</span>
  <span m=''337700''>tool.</span> <span m=''338720''>And</span> <span m=''340750''>in</span>
  <span m=''340810''>this</span> <span m=''340970''>case,</span> <span m=''341280''>we''re</span>
  <span m=''341380''>going</span> <span m=''341480''>to</span> <span m=''341580''>use</span>
  <span m=''341670''>this</span> <span m=''342560''>folding</span> <span m=''343480''>many</span>
  <span m=''343760''>times.</span> <span m=''345420''>At</span> <span m=''345580''>a</span>
  <span m=''345600''>high</span> <span m=''345770''>level,</span> <span m=''346140''>it''s</span>
  <span m=''346250''>just</span> <span m=''346420''>a</span> <span m=''346480''>way</span>
  <span m=''346630''>to</span> <span m=''346770''>fold</span> <span m=''347110''>a</span>
  <span m=''347210''>single</span> <span m=''347610''>cube.</span> <span m=''348840''>But</span>
  <span m=''349130''>it</span> <span m=''349220''>has</span> <span m=''349400''>lots</span>
  <span m=''349650''>of</span> <span m=''349730''>nice</span> <span m=''349940''>properties.</span>
  </p><p><span m=''350430''>So</span> <span m=''350660''>this</span> <span m=''350880''>is
  a</span> <span m=''351000''>crease</span> <span m=''351260''>pattern.</span> <span
  m=''352230''>Red</span> <span m=''352420''>lines</span> <span m=''352690''>are</span>
  <span m=''352730''>mountains.</span> <span m=''353210''>Blue</span> <span m=''353540''>dashed</span>
  <span m=''353870''>lines</span> <span m=''354150''>are</span> <span m=''354710''>valleys.</span>
  <span m=''355650''>It</span> <span m=''355870''>folds</span> <span m=''356150''>into</span>
  <span m=''356330''>this</span> <span m=''356550''>thing,</span> <span m=''357040''>which
  you can</span> <span m=''357130''>see</span> <span m=''357290''>is</span> <span
  m=''357400''>a</span> <span m=''357470''>cube.</span> <span m=''359050''>Here it''s</span>
  <span m=''359190''>some</span> <span m=''359410''>semi-transparent</span> <span
  m=''360170''>material.</span> <span m=''361130''>And</span> <span m=''361630''>there''s</span>
  <span m=''361870''>some</span> <span m=''362100''>pleats</span> <span m=''362550''>coming</span>
  <span m=''362890''>out</span> <span m=''363800''>in</span> <span m=''363890''>the</span>
  <span m=''363960''>four</span> <span m=''364170''>directions.</span> <span m=''365150''>But</span>
  <span m=''365240''>it''s</span> <span m=''365320''>basically</span> <span m=''365660''>a</span>
  <span m=''365710''>cube</span> <span m=''366620''>on</span> <span m=''366830''>a</span>
  <span m=''366920''>plane.</span> <span m=''368530''>So</span> <span m=''368670''>we</span>
  <span m=''368760''>started</span> <span m=''369090''>with</span> <span m=''369270''>a</span>
  <span m=''369330''>plane,</span> <span m=''369710''>a</span> <span m=''369770''>rectangle.</span>
  <span m=''371050''>We</span> <span m=''371260''>fold</span> <span m=''371820''>that</span>
  <span m=''372170''>pattern.</span> <span m=''372920''>And</span> <span m=''373100''>you</span>
  <span m=''373190''>get</span> <span m=''373420''>a</span> <span m=''373520''>rectangle</span>
  <span m=''374370''>plus</span> <span m=''374720''>a</span> <span m=''374800''>cube</span>
  <span m=''375110''>sticking</span> <span m=''375550''>out.</span> <span m=''377130''>OK,</span>
  <span m=''377550''>so</span> <span m=''377940''>in</span> <span m=''378090''>particular,</span>
  <span m=''378385''>I</span> <span m=''378680''>can</span> <span m=''378780''>make</span>
  <span m=''378950''>a</span> <span m=''379030''>one</span> <span m=''379240''>cube</span>
  <span m=''379420''>polycube</span> <span m=''379930''>out</span> <span m=''380030''>of</span>
  <span m=''380110''>this</span> <span m=''380570''>if I</span> <span m=''380700''>just</span>
  <span m=''381290''>made</span> <span m=''381500''>this,</span> <span m=''382060''>got</span>
  <span m=''382230''>rid</span> <span m=''382370''>of</span> <span m=''382510''>the</span>
  <span m=''382590''>rectangular</span> <span m=''383290''>part.</span> <span m=''384140''>But</span>
  <span m=''384570''>by</span> <span m=''384810''>using</span> <span m=''385200''>this</span>
  <span m=''385510''>gadget</span> <span m=''386600''>n</span> <span m=''386860''>times,</span>
  <span m=''387930''>I</span> <span m=''388090''>claim</span> <span m=''388420''>I</span>
  <span m=''388490''>can</span> <span m=''388640''>make</span> <span m=''388800''>an</span>
  <span m=''388920''>n</span> <span m=''389130''>cube</span> <span m=''389320''>polycube.</span>
  </p><p><span m=''390740''>And</span> <span m=''390990''>this</span> <span m=''391270''>kind</span>
  <span m=''391430''>of</span> <span m=''391520''>a</span> <span m=''391570''>crazy</span>
  <span m=''391970''>idea</span> <span m=''392280''>that,</span> <span m=''392890''>so</span>
  <span m=''393080''>for</span> <span m=''393230''>example,</span> <span m=''393580''>suppose</span>
  <span m=''394220''>the</span> <span m=''394420''>starting</span> <span m=''394930''>sheet</span>
  <span m=''395280''>was</span> <span m=''395440''>not</span> <span m=''397540''>just</span>
  <span m=''397720''>a</span> <span m=''397770''>rectangle.</span> <span m=''398720''>But</span>
  <span m=''398850''>suppose</span> <span m=''399150''>it</span> <span m=''399210''>was</span>
  <span m=''399350''>a</span> <span m=''399410''>rectangle</span> <span m=''399910''>with
  a</span> <span m=''400010''>cube</span> <span m=''400280''>sticking</span> <span
  m=''400740''>out</span> <span m=''400960''>right</span> <span m=''401170''>here.</span>
  <span m=''402530''>I</span> <span m=''402640''>could</span> <span m=''402850''>still</span>
  <span m=''403220''>do</span> <span m=''403340''>this</span> <span m=''403550''>folding.</span>
  <span m=''403980''>Because</span> <span m=''404200''>this</span> <span m=''404340''>folding</span>
  <span m=''404620''>didn''t</span> <span m=''404900''>touch</span> <span m=''405220''>The</span>
  <span m=''405410''>gray</span> <span m=''405670''>lines</span> <span m=''405950''>are</span>
  <span m=''406010''>not</span> <span m=''406410''>creases.</span> <span m=''406860''>They''re</span>
  <span m=''406930''>just</span> <span m=''407130''>hinges.</span> <span m=''408270''>If</span>
  <span m=''408380''>I</span> <span m=''408450''>had</span> <span m=''408650''>a</span>
  <span m=''408730''>cube</span> <span m=''408990''>sticking</span> <span m=''409390''>out</span>
  <span m=''409510''>here.</span> <span m=''409920''>and I</span> <span m=''410150''>folded</span>
  <span m=''410500''>this</span> <span m=''410680''>thing,</span> <span m=''411480''>it</span>
  <span m=''411640''>would</span> <span m=''411770''>now</span> <span m=''411980''>be</span>
  <span m=''412250''>a</span> <span m=''412330''>rectangle</span> <span m=''412820''>with</span>
  <span m=''412930''>a</span> <span m=''413010''>cube</span> <span m=''413260''>in</span>
  <span m=''413320''>the</span> <span m=''413410''>center</span> <span m=''413920''>and</span>
  <span m=''414240''>a cube</span> <span m=''414580''>sticking</span> <span m=''414930''>out</span>
  <span m=''415040''>of</span> <span m=''415120''>this</span> <span m=''415300''>corner.</span>
  <span m=''415640''>Because</span> <span m=''415950''>that</span> <span m=''416210''>corner</span>
  <span m=''416470''>just</span> <span m=''416670''>folds</span> <span m=''416970''>to</span>
  <span m=''417120''>right</span> <span m=''417340''>there.</span> <span m=''418840''>In</span>
  <span m=''418900''>fact,</span> <span m=''419300''>I</span> <span m=''419400''>could</span>
  <span m=''419470''>have</span> <span m=''419720''>a</span> <span m=''419790''>cube</span>
  <span m=''420260''>sticking</span> <span m=''420680''>out</span> <span m=''420770''>right</span>
  <span m=''420940''>here</span> <span m=''421720''>also.</span> <span m=''422260''>And</span>
  <span m=''422430''>then</span> <span m=''422550''>there''d</span> <span m=''422680''>be</span>
  <span m=''422810''>a</span> <span m=''422860''>cube</span> <span m=''423110''>sticking</span>
  <span m=''423450''>out</span> <span m=''423550''>here</span> <span m=''423750''>in</span>
  <span m=''423820''>the</span> <span m=''423890''>finished</span> <span m=''424200''>product.</span>
  </p><p><span m=''425180''>And</span> <span m=''425660''>the</span> <span m=''425860''>idea</span>
  <span m=''426170''>is</span> <span m=''426430''>to</span> <span m=''426690''>just</span>
  <span m=''426900''>keep</span> <span m=''427260''>using</span> <span m=''427680''>this</span>
  <span m=''427870''>gadget.</span> <span m=''428680''>And</span> <span m=''428880''>make</span>
  <span m=''429080''>your</span> <span m=''429190''>sheet</span> <span m=''429450''>bumpier</span>
  <span m=''429890''>and</span> <span m=''430070''>bumpier</span> <span m=''430850''>with</span>
  <span m=''431020''>more</span> <span m=''431260''>and</span> <span m=''431360''>more</span>
  <span m=''431480''>cubes</span> <span m=''431880''>sticking</span> <span m=''432110''>out.</span>
  <span m=''433312''>And</span> <span m=''433800''>this</span> <span m=''434050''>is</span>
  <span m=''434200''>the</span> <span m=''434290''>sort</span> <span m=''434550''>of</span>
  <span m=''434670''>thing</span> <span m=''434940''>if</span> <span m=''435080''>you</span>
  <span m=''435190''>wanted</span> <span m=''435490''>to</span> <span m=''435590''>make--</span>
  <span m=''436100''>so</span> <span m=''436230''>there</span> <span m=''436410''>I</span>
  <span m=''436450''>had</span> <span m=''436660''>cubes</span> <span m=''437040''>that</span>
  <span m=''437110''>were</span> <span m=''437260''>separated</span> <span m=''437830''>from</span>
  <span m=''438010''>each</span> <span m=''438160''>other.</span> <span m=''439440''>If</span>
  <span m=''439570''>you</span> <span m=''439700''>want</span> <span m=''439830''>to</span>
  <span m=''439870''>have</span> <span m=''440020''>cubes that</span> <span m=''440300''>are</span>
  <span m=''440430''>attached</span> <span m=''440850''>to</span> <span m=''440910''>each</span>
  <span m=''441080''>other,</span> <span m=''441680''>you</span> <span m=''441830''>can</span>
  <span m=''441970''>do</span> <span m=''442110''>that</span> <span m=''442370''>too.</span>
  <span m=''443720''>Because</span> <span m=''445190''>all right,</span> <span m=''445620''>say</span>
  <span m=''445840''>here,</span> <span m=''446610''>if</span> <span m=''447010''>you</span>
  <span m=''447170''>apply</span> <span m=''447920''>the</span> <span m=''448100''>cube</span>
  <span m=''448320''>gadget</span> <span m=''448970''>at</span> <span m=''449140''>this</span>
  <span m=''449410''>center</span> <span m=''449710''>square,</span> <span m=''450480''>so</span>
  <span m=''450600''>you</span> <span m=''450680''>want</span> <span m=''450800''>to</span>
  <span m=''450860''>pull</span> <span m=''451150''>a</span> <span m=''451190''>cube</span>
  <span m=''451530''>out</span> <span m=''451830''>from</span> <span m=''451990''>there.</span>
  <span m=''453730''>Maybe</span> <span m=''453880''>I</span> <span m=''453910''>should</span>
  <span m=''454080''>show</span> <span m=''454280''>you</span> <span m=''454450''>in</span>
  <span m=''455020''>the</span> <span m=''455150''>previous</span> <span m=''456080''>diagram.</span>
  </p><p><span m=''457100''>So</span> <span m=''457170''>you</span> <span m=''457310''>have</span>
  <span m=''459600''>these</span> <span m=''460080''>four</span> <span m=''460710''>squares</span>
  <span m=''461490''>around</span> <span m=''461910''>the</span> <span m=''461980''>center</span>
  <span m=''462320''>square</span> <span m=''462910''>make</span> <span m=''463240''>up</span>
  <span m=''463430''>the</span> <span m=''463530''>four</span> <span m=''463820''>sides</span>
  <span m=''464170''>of</span> <span m=''464260''>the</span> <span m=''464350''>cube,</span>
  <span m=''465360''>other</span> <span m=''465640''>than</span> <span m=''465780''>the</span>
  <span m=''465880''>top</span> <span m=''466160''>side.</span> <span m=''467570''>And</span>
  <span m=''467650''>so</span> <span m=''467800''>if</span> <span m=''467890''>you</span>
  <span m=''468080''>already</span> <span m=''468500''>had</span> <span m=''468850''>a</span>
  <span m=''468900''>cube</span> <span m=''469330''>on</span> <span m=''469460''>that</span>
  <span m=''469710''>side</span> <span m=''470000''>face,</span> <span m=''471110''>when</span>
  <span m=''471260''>you</span> <span m=''471370''>fold</span> <span m=''471680''>this</span>
  <span m=''471870''>thing,</span> <span m=''472130''>you</span> <span m=''472320''>end</span>
  <span m=''472520''>up</span> <span m=''472650''>with</span> <span m=''472750''>a</span>
  <span m=''472850''>cube</span> <span m=''473580''>that</span> <span m=''473710''>has</span>
  <span m=''473900''>a</span> <span m=''473960''>cube</span> <span m=''474210''>attached</span>
  <span m=''474630''>on</span> <span m=''474760''>its</span> <span m=''474890''>right.</span>
  <span m=''477130''>So</span> <span m=''477380''>if</span> <span m=''477500''>I</span>
  <span m=''477580''>wave</span> <span m=''477830''>my</span> <span m=''477960''>hands</span>
  <span m=''478310''>enough,</span> <span m=''478890''>I</span> <span m=''479020''>believe</span>
  <span m=''479520''>that</span> <span m=''479640''>it''s</span> <span m=''479960''>possible
  to</span> <span m=''480330''>make</span> <span m=''480540''>anything</span> <span
  m=''480910''>in</span> <span m=''480980''>this</span> <span m=''481160''>way.</span>
  </p><p><span m=''481920''>Let</span> <span m=''482120''>me</span> <span m=''483270''>convince</span>
  <span m=''483710''>you</span> <span m=''484060''>a</span> <span m=''484100''>little</span>
  <span m=''484430''>more</span> <span m=''484660''>formally.</span> <span m=''485900''>Let''s</span>
  <span m=''486110''>see.</span> <span m=''486710''>Here''s</span> <span m=''486920''>a</span>
  <span m=''486990''>real</span> <span m=''487210''>example.</span> <span m=''488450''>It</span>
  <span m=''488550''>gives</span> <span m=''488660''>you</span> <span m=''488760''>an</span>
  <span m=''488840''>idea</span> <span m=''489140''>of</span> <span m=''489190''>how</span>
  <span m=''489360''>you</span> <span m=''489530''>can</span> <span m=''489680''>make</span>
  <span m=''490290''>even</span> <span m=''490560''>overhanging</span> <span m=''491200''>cubes.</span>
  <span m=''492100''>All</span> <span m=''492440''>I</span> <span m=''492510''>did</span>
  <span m=''492940''>was</span> <span m=''494350''>initially</span> <span m=''494890''>I</span>
  <span m=''494980''>made</span> <span m=''495280''>this</span> <span m=''495470''>first</span>
  <span m=''495780''>cube.</span> <span m=''496880''>Then</span> <span m=''497910''>I</span>
  <span m=''498040''>made</span> <span m=''498350''>this</span> <span m=''498570''>cube</span>
  <span m=''499300''>with</span> <span m=''499430''>this</span> <span m=''499590''>one</span>
  <span m=''499720''>attached</span> <span m=''500090''>to</span> <span m=''500160''>the</span>
  <span m=''500260''>side,</span> <span m=''500610''>just</span> <span m=''500810''>like</span>
  <span m=''500960''>the</span> <span m=''501050''>previous</span> <span m=''501440''>picture.</span>
  <span m=''502570''>And</span> <span m=''502750''>then</span> <span m=''502920''>I</span>
  <span m=''503000''>just</span> <span m=''503230''>made</span> <span m=''503920''>another</span>
  <span m=''504260''>cube</span> <span m=''504660''>right</span> <span m=''505000''>underneath</span>
  <span m=''505500''>that</span> <span m=''505720''>one,</span> <span m=''506030''>so</span>
  <span m=''506200''>this</span> <span m=''506410''>cube</span> <span m=''506580''>was</span>
  <span m=''506710''>already</span> <span m=''506960''>attached</span> <span m=''507360''>to</span>
  <span m=''507430''>the</span> <span m=''507550''>center</span> <span m=''507900''>square.</span>
  <span m=''509170''>And</span> <span m=''509540''>it</span> <span m=''509640''>just</span>
  <span m=''510080''>got</span> <span m=''510310''>raised</span> <span m=''510580''>up</span>
  <span m=''511170''>by</span> <span m=''511310''>another</span> <span m=''511540''>cube.</span>
  <span m=''511820''>So</span> <span m=''512000''>now</span> <span m=''512140''>you''ve</span>
  <span m=''512280''>got</span> <span m=''512450''>this</span> <span m=''513080''>L</span>
  <span m=''513409''>overhang.</span> <span m=''513990''>And</span> <span m=''514059''>this</span>
  <span m=''514200''>is</span> <span m=''514309''>not</span> <span m=''514559''>quite</span>
  <span m=''514850''>the</span> <span m=''514940''>crease</span> <span m=''515159''>pattern.</span>
  <span m=''515470''>This</span> <span m=''515659''>is</span> <span m=''516360''>there''s</span>
  <span m=''516520''>some</span> <span m=''516720''>lines</span> <span m=''517000''>that
  are</span> <span m=''517110''>not</span> <span m=''517299''>drawn</span> <span m=''517539''>here.</span>
  <span m=''517840''>But</span> <span m=''517980''>it''s</span> <span m=''518169''>a</span>
  <span m=''518220''>rough</span> <span m=''518890''>sketch</span> <span m=''519230''>of</span>
  <span m=''519280''>the</span> <span m=''519360''>crease</span> <span m=''519610''>pattern.</span>
  </p><p><span m=''521650''>Let''s</span> <span m=''521950''>see.</span> <span m=''524320''>I''ll</span>
  <span m=''524770''>worry</span> <span m=''524900''>about</span> <span m=''525130''>the</span>
  <span m=''525200''>rest</span> <span m=''525620''>next.</span> <span m=''525860''>Let</span>
  <span m=''525990''>me</span> <span m=''526740''>give</span> <span m=''526890''>you</span>
  <span m=''527050''>a</span> <span m=''527070''>little</span> <span m=''527250''>bit</span>
  <span m=''527390''>of</span> <span m=''527450''>an</span> <span m=''527510''>argument</span>
  <span m=''527870''>why</span> <span m=''528030''>this</span> <span m=''528260''>works.</span>
  <span m=''533040''>So</span> <span m=''533240''>a</span> <span m=''533320''>cube</span>
  <span m=''533550''>gadget</span> <span m=''535390''>let''s</span> <span m=''535700''>say</span>
  <span m=''537040''>transforms</span> <span m=''538710''>a</span> <span m=''538820''>constant</span>
  <span m=''539310''>number</span> <span m=''540310''>of</span> <span m=''540510''>rows</span>
  <span m=''540770''>and</span> <span m=''540890''>columns</span> <span m=''541670''>of</span>
  <span m=''541830''>the</span> <span m=''541920''>grid</span> <span m=''547640''>into</span>
  <span m=''547810''>a</span> <span m=''548110''>cube</span> <span m=''551460''>that''s</span>
  <span m=''551750''>sticking</span> <span m=''552120''>out</span> <span m=''552310''>of</span>
  <span m=''552590''>your</span> <span m=''552730''>sheet.</span> <span m=''561040''>And</span>
  <span m=''561280''>the</span> <span m=''561370''>key</span> <span m=''561650''>property</span>
  <span m=''562150''>is</span> <span m=''562270''>it</span> <span m=''562370''>works</span>
  <span m=''563150''>even</span> <span m=''563500''>if</span> <span m=''563840''>there</span>
  <span m=''564250''>are</span> <span m=''564290''>bumps</span> <span m=''565060''>on</span>
  <span m=''565280''>your</span> <span m=''565420''>sheet</span> <span m=''573980''>elsewhere.</span>
  <span m=''575150''>So</span> <span m=''575200''>when</span> <span m=''575300''>I</span>
  <span m=''575360''>say</span> <span m=''575590''>elsewhere,</span> <span m=''576950''>let</span>
  <span m=''577070''>me</span> <span m=''577450''>show</span> <span m=''577660''>you</span>
  <span m=''577820''>the</span> <span m=''577930''>cube</span> <span m=''578160''>gadget</span>
  <span m=''578500''>again.</span> <span m=''582420''>There''s</span> <span m=''583850''>actually</span>
  <span m=''584190''>two</span> <span m=''584590''>columns</span> <span m=''585170''>sort</span>
  <span m=''585330''>of</span> <span m=''585430''>getting</span> <span m=''585680''>used</span>
  <span m=''586040''>up</span> <span m=''586830''>here.</span> <span m=''587500''>And</span>
  <span m=''587700''>there''s</span> <span m=''587830''>one</span> <span m=''588140''>row</span>
  <span m=''588470''>getting</span> <span m=''588680''>used</span> <span m=''588960''>up</span>
  <span m=''589110''>there.</span> <span m=''590210''>Sorry,</span> <span m=''590660''>actually</span>
  <span m=''590910''>one</span> <span m=''591130''>row</span> <span m=''591320''>here.</span>
  <span m=''592400''>So</span> <span m=''592560''>there''s</span> <span m=''592670''>one</span>
  <span m=''592900''>row and</span> <span m=''593240''>two</span> <span m=''593390''>columns</span>
  <span m=''593780''>in</span> <span m=''593840''>this</span> <span m=''594010''>corner.</span>
  <span m=''594430''>And</span> <span m=''594500''>there''s</span> <span m=''594720''>actually</span>
  <span m=''595680''>one</span> <span m=''595880''>row and</span> <span m=''596140''>two</span>
  <span m=''596290''>columns</span> <span m=''596680''>used</span> <span m=''596890''>up</span>
  <span m=''597240''>in</span> <span m=''597420''>each</span> <span m=''597640''>corner.</span>
  <span m=''597950''>And</span> <span m=''598030''>that</span> <span m=''598360''>material</span>
  <span m=''598990''>disappears</span> <span m=''599820''>in</span> <span m=''599890''>some</span>
  <span m=''600110''>sense</span> <span m=''600470''>from</span> <span m=''600630''>the</span>
  <span m=''600710''>folding</span> <span m=''601130''>up</span> <span m=''601320''>here.</span>
  </p><p><span m=''602300''>But</span> <span m=''602400''>all</span> <span m=''602580''>the</span>
  <span m=''602720''>other</span> <span m=''602920''>stuff,</span> <span m=''603730''>this</span>
  <span m=''603960''>column,</span> <span m=''605020''>everything</span> <span m=''605520''>out</span>
  <span m=''605760''>in</span> <span m=''605900''>this</span> <span m=''606090''>corner,</span>
  <span m=''607170''>and</span> <span m=''607250''>those</span> <span m=''607480''>four</span>
  <span m=''607700''>squares</span> <span m=''608130''>around</span> <span m=''608340''>the</span>
  <span m=''608410''>center</span> <span m=''608720''>and</span> <span m=''608950''>the</span>
  <span m=''609020''>center</span> <span m=''609310''>square</span> <span m=''609510''>itself,</span>
  <span m=''610360''>those</span> <span m=''610620''>can</span> <span m=''610730''>all</span>
  <span m=''610880''>have</span> <span m=''611080''>bumps.</span> <span m=''611630''>You</span>
  <span m=''611740''>better</span> <span m=''612000''>not</span> <span m=''612170''>have</span>
  <span m=''612370''>bumps</span> <span m=''612640''>here</span> <span m=''612890''>where</span>
  <span m=''613050''>I</span> <span m=''613090''>need</span> <span m=''613280''>to</span>
  <span m=''613340''>fold.</span> <span m=''613770''>But</span> <span m=''614200''>everywhere</span>
  <span m=''614590''>else</span> <span m=''614770''>can</span> <span m=''614880''>have</span>
  <span m=''615050''>bumps.</span> <span m=''615590''>And</span> <span m=''615950''>it''s</span>
  <span m=''616150''>OK--</span> <span m=''617310''>so</span> <span m=''617440''>I</span>
  <span m=''617510''>just</span> <span m=''617730''>need</span> <span m=''617900''>to</span>
  <span m=''617970''>set</span> <span m=''618210''>up</span> <span m=''618320''>my</span>
  <span m=''618470''>bump</span> <span m=''619130''>pattern</span> <span m=''619750''>so</span>
  <span m=''619920''>that</span> <span m=''620240''>when</span> <span m=''620500''>I</span>
  <span m=''620610''>finish</span> <span m=''621070''>making</span> <span m=''621390''>that</span>
  <span m=''621590''>cube,</span> <span m=''622330''>I</span> <span m=''622470''>have</span>
  <span m=''622650''>the</span> <span m=''622730''>bumps</span> <span m=''623000''>in</span>
  <span m=''623050''>the</span> <span m=''623130''>right</span> <span m=''623320''>place.</span>
  <span m=''625540''>So</span> <span m=''625730''>it''s</span> <span m=''625880''>sort</span>
  <span m=''626090''>of</span> <span m=''626240''>a</span> <span m=''626340''>working</span>
  <span m=''626690''>backwards</span> <span m=''627100''>process.</span> <span m=''628520''>And</span>
  <span m=''628640''>the</span> <span m=''628740''>idea</span> <span m=''629100''>is</span>
  <span m=''629480''>to</span> <span m=''629630''>make</span> <span m=''632910''>a</span>
  <span m=''633010''>tree</span> <span m=''633490''>of</span> <span m=''633690''>cubes.</span>
  <span m=''635790''>So</span> <span m=''635970''>if</span> <span m=''636080''>you</span>
  <span m=''636190''>want</span> <span m=''636350''>to</span> <span m=''636390''>make</span>
  <span m=''636600''>something</span> <span m=''637100''>that</span> <span m=''637240''>has</span>
  <span m=''638150''>cycles</span> <span m=''638700''>in</span> <span m=''638840''>it,</span>
  <span m=''639010''>like</span> <span m=''639640''>a</span> <span m=''639750''>big</span>
  <span m=''640140''>n</span> <span m=''640330''>by</span> <span m=''640520''>n</span>
  <span m=''640710''>by</span> <span m=''640850''>n</span> <span m=''641330''>cube</span>
  <span m=''641970''>array,</span> <span m=''642690''>you</span> <span m=''642890''>can</span>
  <span m=''643030''>just</span> <span m=''643710''>cut</span> <span m=''643970''>it</span>
  <span m=''644070''>up,</span> <span m=''644270''>subdivide</span> <span m=''644860''>it,</span>
  <span m=''645060''>so</span> <span m=''645250''>that it''s</span> <span m=''645790''>just</span>
  <span m=''646080''>a</span> <span m=''646190''>tree</span> <span m=''646630''>of</span>
  <span m=''647380''>objects.</span> </p><p><span m=''648230''>So</span> <span m=''650420''>for</span>
  <span m=''650560''>example,</span> <span m=''650880''>suppose</span> <span m=''651270''>I</span>
  <span m=''651340''>wanted</span> <span m=''651640''>to</span> <span m=''651740''>build</span>
  <span m=''653220''>this</span> <span m=''653690''>shape,</span> <span m=''656200''>which</span>
  <span m=''656390''>is</span> <span m=''656470''>not</span> <span m=''656650''>really</span>
  <span m=''656860''>a</span> <span m=''656910''>tree.</span> <span m=''657860''>I</span>
  <span m=''658010''>can</span> <span m=''658940''>just</span> <span m=''659170''>pretend</span>
  <span m=''660240''>that</span> <span m=''660370''>there''s</span> <span m=''660550''>a</span>
  <span m=''660610''>slice</span> <span m=''664340''>here.</span> <span m=''668860''>So</span>
  <span m=''668900''>these</span> <span m=''669120''>guys</span> <span m=''669330''>are</span>
  <span m=''669380''>connected</span> <span m=''669770''>in a</span> <span m=''669900''>path.</span>
  <span m=''670940''>But</span> <span m=''671070''>they''re</span> <span m=''671180''>not</span>
  <span m=''671410''>connected</span> <span m=''671800''>here.</span> <span m=''672800''>In</span>
  <span m=''672950''>general,</span> <span m=''673230''>you</span> <span m=''673370''>can</span>
  <span m=''673480''>just</span> <span m=''674440''>keep</span> <span m=''674690''>slicing</span>
  <span m=''675270''>until</span> <span m=''675500''>your</span> <span m=''675620''>thing</span>
  <span m=''675850''>is</span> <span m=''676680''>connected</span> <span m=''677060''>like</span>
  <span m=''677230''>a</span> <span m=''677270''>tree.</span> <span m=''679530''>Then</span>
  <span m=''680150''>once</span> <span m=''680380''>you</span> <span m=''680470''>have</span>
  <span m=''680630''>a</span> <span m=''680690''>tree,</span> <span m=''681550''>you</span>
  <span m=''681690''>may</span> <span m=''681830''>know</span> <span m=''682020''>this</span>
  <span m=''682230''>fact,</span> <span m=''682520''>every</span> <span m=''682850''>tree</span>
  <span m=''683120''>has</span> <span m=''683290''>at</span> <span m=''683360''>least</span>
  <span m=''683610''>two</span> <span m=''683830''>leaves</span> <span m=''685210''>except</span>
  <span m=''685580''>in</span> <span m=''686140''>winter.</span> <span m=''686940''>But</span>
  <span m=''689100''>in</span> <span m=''689260''>this</span> <span m=''689450''>context,</span>
  <span m=''689930''>we''re</span> <span m=''690030''>thinking</span> <span m=''690380''>of</span>
  <span m=''690470''>a</span> <span m=''690540''>tree.</span> <span m=''691390''>Here</span>
  <span m=''691600''>the</span> <span m=''691740''>tree</span> <span m=''692010''>is</span>
  <span m=''692270''>just</span> <span m=''692540''>this</span> <span m=''692660''>path.</span>
  <span m=''693880''>And</span> <span m=''694060''>a</span> <span m=''694130''>leaf</span>
  <span m=''694540''>is</span> <span m=''694680''>a</span> <span m=''694730''>vertex</span>
  <span m=''695130''>that</span> <span m=''695190''>has</span> <span m=''695810''>degree</span>
  <span m=''696060''>one.</span> <span m=''696690''>And</span> <span m=''696870''>every</span>
  <span m=''697090''>leaf</span> <span m=''697280''>has</span> <span m=''697480''>at</span>
  <span m=''697530''>least,</span> <span m=''698110''>every</span> <span m=''698360''>tree</span>
  <span m=''698600''>has</span> <span m=''698780''>at</span> <span m=''698830''>least</span>
  <span m=''699040''>two</span> <span m=''699190''>leaves</span> <span m=''699820''>is</span>
  <span m=''699970''>a</span> <span m=''700480''>fun</span> <span m=''700780''>fact</span>
  <span m=''701620''>about</span> <span m=''701900''>trees.</span> </p><p><span m=''702950''>And</span>
  <span m=''703190''>so</span> <span m=''704020''>what</span> <span m=''704300''>we</span>
  <span m=''704420''>do</span> <span m=''705240''>to</span> <span m=''705360''>make</span>
  <span m=''705580''>this</span> <span m=''705770''>thing</span> <span m=''707080''>is</span>
  <span m=''707370''>make</span> <span m=''707590''>a</span> <span m=''707650''>leaf.</span>
  <span m=''709350''>So</span> <span m=''709510''>what</span> <span m=''709610''>I</span>
  <span m=''709660''>mean</span> <span m=''709830''>is</span> <span m=''709930''>we</span>
  <span m=''710030''>start</span> <span m=''710270''>with</span> <span m=''710400''>a</span>
  <span m=''710440''>blank</span> <span m=''710760''>sheet.</span> <span m=''711970''>And</span>
  <span m=''712440''>we''ll</span> <span m=''712550''>say</span> <span m=''712750''>OK,</span>
  <span m=''713280''>here''s</span> <span m=''713530''>a</span> <span m=''713600''>leaf.</span>
  <span m=''713990''>I''m</span> <span m=''714120''>going</span> <span m=''714210''>to</span>
  <span m=''714270''>build</span> <span m=''714490''>that</span> <span m=''714710''>cube</span>
  <span m=''714910''>first.</span> <span m=''715840''>So</span> <span m=''716020''>you</span>
  <span m=''716450''>apply</span> <span m=''716770''>cube</span> <span m=''716970''>gadget.</span>
  <span m=''717510''>You</span> <span m=''717610''>build</span> <span m=''717810''>a</span>
  <span m=''717880''>cube.</span> <span m=''719250''>Then</span> <span m=''719480''>you</span>
  <span m=''720040''>effectively</span> <span m=''721450''>remove</span> <span m=''721840''>that</span>
  <span m=''722050''>leaf.</span> <span m=''722570''>Just</span> <span m=''722780''>pretend</span>
  <span m=''723360''>it</span> <span m=''723470''>was</span> <span m=''723630''>never</span>
  <span m=''723850''>there.</span> <span m=''724780''>This</span> <span m=''724930''>is</span>
  <span m=''725030''>sort</span> <span m=''725200''>of</span> <span m=''725270''>a</span>
  <span m=''725340''>conceptual</span> <span m=''725920''>thing.</span> <span m=''726140''>You''re</span>
  <span m=''726260''>not</span> <span m=''726440''>really</span> <span m=''726710''>removing</span>
  <span m=''727160''>it,</span> <span m=''727350''>but</span> <span m=''730150''>and</span>
  <span m=''730270''>then</span> <span m=''730390''>you</span> <span m=''730500''>repeat.</span>
  <span m=''734100''>It''s</span> <span m=''734290''>actually</span> <span m=''734670''>a</span>
  <span m=''734740''>super</span> <span m=''735100''>simple</span> <span m=''735390''>algorithm.</span>
  <span m=''735800''>The</span> <span m=''735880''>details</span> <span m=''736420''>are</span>
  <span m=''736790''>a</span> <span m=''736840''>little</span> <span m=''737040''>bit</span>
  <span m=''737670''>tricky,</span> <span m=''738150''>because</span> <span m=''738480''>we</span>
  <span m=''738590''>have to</span> <span m=''738750''>make</span> <span m=''738900''>sure</span>
  <span m=''739040''>that</span> <span m=''739200''>this</span> <span m=''739380''>works.</span>
  <span m=''740230''>But</span> <span m=''740680''>once</span> <span m=''740950''>I</span>
  <span m=''741020''>remove</span> <span m=''742210''>that</span> <span m=''742420''>cube,</span>
  <span m=''743620''>now</span> <span m=''743790''>my</span> <span m=''744510''>graph</span>
  <span m=''744810''>is</span> <span m=''744930''>like</span> <span m=''745110''>this.</span>
  <span m=''745970''>So</span> <span m=''746020''>I have a</span> <span m=''746110''>choice.</span>
  <span m=''746540''>I</span> <span m=''746560''>could</span> <span m=''746810''>either</span>
  <span m=''747070''>fold</span> <span m=''748080''>this</span> <span m=''748330''>leaf</span>
  <span m=''748570''>next,</span> <span m=''749330''>or I could</span> <span m=''749650''>fold</span>
  <span m=''749810''>this</span> <span m=''750020''>one.</span> <span m=''750940''>I</span>
  <span m=''751040''>just</span> <span m=''751220''>keep</span> <span m=''751380''>going.</span>
  </p><p><span m=''751830''>In</span> <span m=''751940''>this</span> <span m=''752110''>case,</span>
  <span m=''752440''>I</span> <span m=''752540''>could</span> <span m=''752550''>just</span>
  <span m=''752790''>go</span> <span m=''753040''>linearly</span> <span m=''753480''>along</span>
  <span m=''753740''>the</span> <span m=''753820''>path,</span> <span m=''754240''>like</span>
  <span m=''754440''>I</span> <span m=''754460''>did</span> <span m=''754680''>for</span>
  <span m=''755140''>making the</span> <span m=''755490''>overhanging</span> <span
  m=''756060''>L.</span> <span m=''757330''>And</span> <span m=''757580''>you</span>
  <span m=''757740''>will</span> <span m=''757870''>make</span> <span m=''758280''>all</span>
  <span m=''758520''>the</span> <span m=''758600''>cubes.</span> <span m=''759660''>And</span>
  <span m=''759840''>the</span> <span m=''759960''>property</span> <span m=''760380''>you''ll</span>
  <span m=''760540''>have</span> <span m=''760840''>is</span> <span m=''760950''>that</span>
  <span m=''761060''>whenever</span> <span m=''761440''>I</span> <span m=''761470''>build</span>
  <span m=''761840''>a</span> <span m=''761890''>cube,</span> <span m=''762570''>all</span>
  <span m=''762780''>the</span> <span m=''762840''>things</span> <span m=''763070''>that</span>
  <span m=''763160''>were</span> <span m=''763280''>hanging</span> <span m=''763680''>off</span>
  <span m=''763850''>of</span> <span m=''763960''>it</span> <span m=''764110''>have</span>
  <span m=''764350''>already</span> <span m=''764650''>been</span> <span m=''764830''>built.</span>
  <span m=''765910''>Because</span> <span m=''766120''>I''m</span> <span m=''766260''>always</span>
  <span m=''766480''>working</span> <span m=''766750''>from</span> <span m=''766900''>the</span>
  <span m=''766990''>leaves</span> <span m=''767460''>up</span> <span m=''768400''>the</span>
  <span m=''768490''>tree.</span> <span m=''769510''>This</span> <span m=''769710''>is,</span>
  <span m=''770350''>for</span> <span m=''770520''>those</span> <span m=''770790''>who</span>
  <span m=''770900''>know</span> <span m=''772690''>trees,</span> <span m=''773420''>this</span>
  <span m=''773590''>is</span> <span m=''773720''>called</span> <span m=''774040''>a</span>
  <span m=''774140''>post-order</span> <span m=''774630''>traversal.</span> <span
  m=''779900''>It</span> <span m=''780430''>just</span> <span m=''780630''>means</span>
  <span m=''780830''>whenever</span> <span m=''781210''>I</span> <span m=''781710''>touch</span>
  <span m=''782070''>a</span> <span m=''782120''>node,</span> <span m=''782410''>whenever</span>
  <span m=''782680''>I</span> <span m=''782880''>create</span> <span m=''783230''>a</span>
  <span m=''783280''>node,</span> <span m=''784080''>all</span> <span m=''784310''>of</span>
  <span m=''784420''>its</span> <span m=''784790''>descendants,</span> <span m=''785350''>all</span>
  <span m=''785570''>of the</span> <span m=''785650''>leaves</span> <span m=''785900''>below</span>
  <span m=''786210''>it,</span> <span m=''786350''>have</span> <span m=''786530''>already</span>
  <span m=''786780''>been</span> <span m=''786950''>built.</span> </p><p><span m=''788060''>And</span>
  <span m=''788150''>that''s</span> <span m=''788340''>exactly</span> <span m=''788770''>how</span>
  <span m=''789000''>this</span> <span m=''789200''>thing</span> <span m=''789350''>needs</span>
  <span m=''789580''>to</span> <span m=''789690''>work.</span> <span m=''790640''>Because</span>
  <span m=''791090''>you</span> <span m=''791270''>can</span> <span m=''791370''>have</span>
  <span m=''791650''>existing</span> <span m=''792080''>bumps</span> <span m=''792380''>which</span>
  <span m=''792580''>are</span> <span m=''792630''>the</span> <span m=''792750''>things</span>
  <span m=''793000''>that</span> <span m=''793100''>were</span> <span m=''793260''>attached</span>
  <span m=''793740''>to</span> <span m=''793830''>that</span> <span m=''794060''>cube
  and</span> <span m=''794480''>sort</span> <span m=''794660''>of</span> <span m=''794840''>are</span>
  <span m=''794950''>deeper</span> <span m=''795360''>in</span> <span m=''795440''>the</span>
  <span m=''795540''>tree.</span> <span m=''797030''>Those</span> <span m=''797310''>are</span>
  <span m=''797380''>harder.</span> <span m=''797680''>You</span> <span m=''797780''>can''t</span>
  <span m=''797970''>make</span> <span m=''798120''>those</span> <span m=''798280''>later.</span>
  <span m=''798810''>As</span> <span m=''798920''>long</span> <span m=''799100''>as</span>
  <span m=''799180''>they''re</span> <span m=''799340''>already</span> <span m=''799690''>built,</span>
  <span m=''800470''>you</span> <span m=''800630''>just</span> <span m=''800790''>sort</span>
  <span m=''801020''>of</span> <span m=''801110''>keep</span> <span m=''801350''>working</span>
  <span m=''801710''>up</span> <span m=''801870''>the</span> <span m=''801960''>tree.</span>
  <span m=''802250''>And</span> <span m=''802540''>the</span> <span m=''802780''>stuff</span>
  <span m=''803100''>you''ve</span> <span m=''803230''>already</span> <span m=''803400''>built</span>
  <span m=''803630''>hangs</span> <span m=''803890''>off.</span> <span m=''804500''>In</span>
  <span m=''804570''>the</span> <span m=''804680''>end,</span> <span m=''804880''>you''ll</span>
  <span m=''805010''>have</span> <span m=''805190''>your</span> <span m=''805300''>entire</span>
  <span m=''805610''>tree.</span> <span m=''806310''>And</span> <span m=''806380''>you''ll</span>
  <span m=''806480''>have</span> <span m=''806650''>your</span> <span m=''806760''>polycube.</span>
  <span m=''809090''>That''s it.</span> <span m=''810080''>So</span> <span m=''810300''>there
  are</span> <span m=''810500''>obviously</span> <span m=''810820''>details</span>
  <span m=''811850''>here</span> <span m=''812120''>that</span> <span m=''812280''>I''m</span>
  <span m=''812390''>skipping.</span> <span m=''813720''>But</span> <span m=''813910''>I</span>
  <span m=''814000''>think</span> <span m=''814470''>this</span> <span m=''814670''>is</span>
  <span m=''814810''>a</span> <span m=''814870''>fun</span> <span m=''815890''>essence</span>
  <span m=''816310''>of</span> <span m=''816460''>it.</span> </p><p><span m=''818330''>Another</span>
  <span m=''819220''>fact,</span> <span m=''819520''>this</span> <span m=''819680''>is</span>
  <span m=''819790''>essentially</span> <span m=''820290''>optimal.</span> <span m=''820790''>So</span>
  <span m=''822610''>I''m</span> <span m=''822770''>using</span> <span m=''823100''>an</span>
  <span m=''823180''>n</span> <span m=''823330''>by</span> <span m=''823470''>n</span>
  <span m=''823660''>grid</span> <span m=''823870''>to</span> <span m=''823940''>make</span>
  <span m=''824310''>around</span> <span m=''824710''>n</span> <span m=''824950''>cubes.</span>
  <span m=''825520''>You</span> <span m=''825640''>might</span> <span m=''825900''>hope</span>
  <span m=''826300''>in</span> <span m=''826370''>some</span> <span m=''826610''>cases</span>
  <span m=''826980''>you</span> <span m=''827110''>can</span> <span m=''827230''>do</span>
  <span m=''827340''>better.</span> <span m=''828170''>In</span> <span m=''828210''>some</span>
  <span m=''828380''>cases,</span> <span m=''828820''>you</span> <span m=''828990''>can</span>
  <span m=''829130''>make</span> <span m=''829360''>n</span> <span m=''829540''>squared</span>
  <span m=''829890''>cubes</span> <span m=''830360''>out</span> <span m=''830530''>of</span>
  <span m=''830610''>an</span> <span m=''830700''>n</span> <span m=''830840''>by</span>
  <span m=''830980''>n</span> <span m=''831130''>grid.</span> <span m=''831380''>That''s</span>
  <span m=''832055''>the</span> <span m=''832410''>best</span> <span m=''832700''>case.</span>
  <span m=''833510''>The</span> <span m=''833620''>worst</span> <span m=''833860''>case</span>
  <span m=''834080''>really</span> <span m=''834370''>is</span> <span m=''834760''>n</span>
  <span m=''835140''>cubes.</span> <span m=''835670''>Because</span> <span m=''836730''>if</span>
  <span m=''836860''>you</span> <span m=''836990''>want</span> <span m=''837170''>to</span>
  <span m=''837220''>make</span> <span m=''838040''>a</span> <span m=''838160''>super</span>
  <span m=''838560''>long</span> <span m=''839850''>polycube,</span> <span m=''842154''>a</span>
  <span m=''842580''>one</span> <span m=''842850''>by</span> <span m=''843000''>one</span>
  <span m=''843220''>by</span> <span m=''843380''>n</span> <span m=''845670''>grid,</span>
  <span m=''848190''>then</span> <span m=''848370''>the</span> <span m=''848480''>diameter</span>
  <span m=''849120''>of</span> <span m=''849200''>this</span> <span m=''849400''>thing</span>
  <span m=''849640''>is</span> <span m=''849760''>about</span> <span m=''850020''>n.</span>
  <span m=''851090''>And</span> <span m=''851250''>the</span> <span m=''851330''>diameter</span>
  <span m=''851820''>of my</span> <span m=''852180''>square</span> <span m=''852510''>paper
  is</span> <span m=''853270''>like</span> <span m=''853660''>maybe</span> <span m=''853920''>root</span>
  <span m=''854120''>2</span> <span m=''854270''>times</span> <span m=''854580''>n.</span>
  <span m=''855180''>So</span> <span m=''855310''>maybe</span> <span m=''855670''>I</span>
  <span m=''855720''>could</span> <span m=''855870''>save a</span> <span m=''856270''>root
  2</span> <span m=''856420''>factor.</span> <span m=''856850''>But</span> <span m=''857390''>just</span>
  <span m=''857610''>to</span> <span m=''857680''>get</span> <span m=''857860''>this</span>
  <span m=''858010''>diameter</span> <span m=''858850''>n,</span> <span m=''859250''>I''m</span>
  <span m=''859340''>going</span> <span m=''859460''>to</span> <span m=''859520''>need</span>
  <span m=''859730''>about</span> <span m=''859980''>an</span> <span m=''860040''>n</span>
  <span m=''860190''>by</span> <span m=''860350''>n</span> <span m=''860490''>sheet.</span>
  <span m=''861550''>So</span> <span m=''861790''>in the</span> <span m=''861880''>worst</span>
  <span m=''862120''>case,</span> <span m=''862830''>this</span> <span m=''863000''>is</span>
  <span m=''863150''>the</span> <span m=''863230''>best</span> <span m=''863480''>you</span>
  <span m=''863580''>can</span> <span m=''863690''>hope</span> <span m=''863890''>for</span>
  <span m=''864270''>from</span> <span m=''864650''>our</span> <span m=''864740''>usual</span>
  <span m=''865160''>diameter</span> <span m=''865540''>argument</span> <span m=''865870''>like</span>
  <span m=''865960''>last</span> <span m=''866260''>class.</span> </p><p><span m=''868350''>But</span>
  <span m=''868480''>sometimes</span> <span m=''868830''>you</span> <span m=''868940''>can</span>
  <span m=''869050''>do</span> <span m=''869150''>better.</span> <span m=''869580''>So</span>
  <span m=''869770''>for</span> <span m=''869930''>example,</span> <span m=''871460''>here</span>
  <span m=''871770''>is</span> <span m=''871900''>an</span> <span m=''872270''>MIT</span>
  <span m=''873650''>made</span> <span m=''874830''>by</span> <span m=''874980''>Aviv</span>
  <span m=''875330''>Ovadya.</span> <span m=''876620''>And</span> <span m=''876810''>this</span>
  <span m=''877400''>is</span> <span m=''877790''>much</span> <span m=''878010''>more</span>
  <span m=''878150''>efficient,</span> <span m=''879100''>in</span> <span m=''879550''>some
  sense</span> <span m=''880090''>because</span> <span m=''881070''>everything</span>
  <span m=''881460''>here</span> <span m=''881730''>is</span> <span m=''881990''>height</span>
  <span m=''882270''>one.</span> <span m=''884290''>You</span> <span m=''884570''>can</span>
  <span m=''885940''>share</span> <span m=''886380''>a</span> <span m=''886430''>lot</span>
  <span m=''886630''>of</span> <span m=''886710''>those</span> <span m=''886900''>pleats.</span>
  <span m=''888030''>You</span> <span m=''888120''>don''t</span> <span m=''888300''>have</span>
  <span m=''888460''>to</span> <span m=''888580''>waste</span> <span m=''889210''>rows</span>
  <span m=''889940''>for</span> <span m=''890080''>every</span> <span m=''890330''>single</span>
  <span m=''890650''>gadget.</span> <span m=''891440''>You</span> <span m=''891530''>just,</span>
  <span m=''892050''>you</span> <span m=''892330''>can</span> <span m=''892600''>share</span>
  <span m=''893010''>those</span> <span m=''893240''>wasted</span> <span m=''893600''>rows</span>
  <span m=''893920''>along</span> <span m=''894710''>all</span> <span m=''894980''>the</span>
  <span m=''895080''>guys</span> <span m=''895380''>who</span> <span m=''895470''>are</span>
  <span m=''895570''>aligned.</span> <span m=''897430''>And</span> <span m=''898110''>general</span>
  <span m=''898490''>picture,</span> <span m=''898840''>this</span> <span m=''899050''>is</span>
  <span m=''899190''>actually</span> <span m=''899655''>Aviv''s</span> <span m=''900500''>master''s</span>
  <span m=''901220''>thesis.</span> <span m=''904880''>The</span> <span m=''904990''>way</span>
  <span m=''905180''>I</span> <span m=''905200''>described</span> <span m=''905690''>it,
  if</span> <span m=''905810''>you</span> <span m=''905930''>wanted</span> <span m=''906140''>to</span>
  <span m=''906230''>make</span> <span m=''906420''>two</span> <span m=''906620''>cubes</span>
  <span m=''906900''>right</span> <span m=''907070''>next</span> <span m=''907300''>to</span>
  <span m=''907360''>each</span> <span m=''907520''>other,</span> <span m=''908540''>you</span>
  <span m=''908750''>fold</span> <span m=''909300''>two</span> <span m=''909910''>separate</span>
  <span m=''910290''>cube</span> <span m=''910440''>gadgets</span> <span m=''910810''>that</span>
  <span m=''910910''>each</span> <span m=''911260''>use</span> <span m=''911500''>up</span>
  <span m=''911640''>their</span> <span m=''911770''>rows</span> <span m=''912000''>and</span>
  <span m=''912100''>columns.</span> </p><p><span m=''913640''>You</span> <span m=''913820''>can</span>
  <span m=''913970''>be</span> <span m=''914150''>a</span> <span m=''914210''>little</span>
  <span m=''914470''>bit</span> <span m=''914950''>more</span> <span m=''915160''>clever</span>
  <span m=''915660''>like</span> <span m=''915900''>I was</span> <span m=''916020''>saying</span>
  <span m=''916400''>and</span> <span m=''916800''>share</span> <span m=''917410''>those</span>
  <span m=''919350''>used</span> <span m=''919600''>up</span> <span m=''919740''>rows</span>
  <span m=''920140''>between</span> <span m=''920460''>the</span> <span m=''920550''>two</span>
  <span m=''920700''>guys.</span> <span m=''920980''>Because</span> <span m=''921160''>they
  are</span> <span m=''921570''>horizontally</span> <span m=''922040''>aligned.</span>
  <span m=''922890''>And it''s</span> <span m=''923050''>a</span> <span m=''923090''>little</span>
  <span m=''923290''>more</span> <span m=''923460''>efficient.</span> <span m=''924810''>And</span>
  <span m=''925000''>that''s</span> <span m=''925360''>essentially</span> <span m=''925710''>what''s</span>
  <span m=''925990''>done</span> <span m=''926170''>in</span> <span m=''926250''>that</span>
  <span m=''926400''>example.</span> <span m=''929030''>But</span> <span m=''929230''>there''s</span>
  <span m=''929380''>still</span> <span m=''929580''>some</span> <span m=''929970''>sort</span>
  <span m=''930250''>of</span> <span m=''930320''>wastage</span> <span m=''930780''>here.</span>
  <span m=''930950''>You</span> <span m=''931020''>don''t</span> <span m=''931160''>really</span>
  <span m=''931490''>need</span> <span m=''931670''>to</span> <span m=''931750''>do</span>
  <span m=''931870''>that.</span> <span m=''932090''>You</span> <span m=''932200''>really</span>
  <span m=''932450''>want</span> <span m=''932630''>to</span> <span m=''932680''>build</span>
  <span m=''933390''>the</span> <span m=''933510''>two</span> <span m=''933680''>by</span>
  <span m=''933830''>one</span> <span m=''935250''>thing.</span> <span m=''935750''>And</span>
  <span m=''936140''>with</span> <span m=''936290''>some</span> <span m=''936490''>fancier</span>
  <span m=''936920''>version</span> <span m=''937180''>of</span> <span m=''937240''>the</span>
  <span m=''937350''>algorithm,</span> <span m=''937730''>you</span> <span m=''937840''>can</span>
  <span m=''937980''>do</span> <span m=''938090''>that.</span> <span m=''938530''>If</span>
  <span m=''938650''>you</span> <span m=''938740''>want</span> <span m=''938840''>to</span>
  <span m=''938900''>check</span> <span m=''939110''>it</span> <span m=''939190''>out,</span>
  <span m=''939760''>you</span> <span m=''939850''>can</span> <span m=''939970''>see</span>
  <span m=''940160''>Aviv''s</span> <span m=''941040''>[INAUDIBLE]</span> <span m=''941260''>thesis,</span>
  <span m=''943580''>which</span> <span m=''943720''>was</span> <span m=''943820''>just</span>
  <span m=''944050''>completed</span> <span m=''944690''>last</span> <span m=''944990''>month.</span>
  <span m=''947100''>And</span> <span m=''949090''>yeah,</span> <span m=''950050''>we</span>
  <span m=''950160''>don''t</span> <span m=''950300''>have</span> <span m=''950480''>a</span>
  <span m=''950550''>formal</span> <span m=''950880''>sense</span> <span m=''951160''>in</span>
  <span m=''951210''>which</span> <span m=''951485''>in</span> <span m=''951760''>how</span>
  <span m=''952120''>much</span> <span m=''952370''>better</span> <span m=''952610''>this</span>
  <span m=''952810''>is.</span> <span m=''953210''>But</span> <span m=''953440''>it''s</span>
  <span m=''954330''>sort</span> <span m=''954470''>of</span> <span m=''954570''>opportunistic,</span>
  <span m=''955230''>tries</span> <span m=''955470''>to</span> <span m=''955550''>be</span>
  <span m=''955760''>as</span> <span m=''955950''>good</span> <span m=''956110''>as</span>
  <span m=''956200''>possible.</span> <span m=''960440''>And</span> <span m=''962050''>that</span>
  <span m=''962350''>is</span> <span m=''963690''>one</span> <span m=''963900''>version</span>
  <span m=''964170''>of</span> <span m=''964250''>box</span> <span m=''964570''>pleating.</span>
  </p><p><span m=''966040''>But</span> <span m=''966280''>in</span> <span m=''966410''>the</span>
  <span m=''966480''>same</span> <span m=''966730''>spirit,</span> <span m=''967990''>I</span>
  <span m=''968050''>want</span> <span m=''968200''>to</span> <span m=''968250''>talk</span>
  <span m=''968450''>about</span> <span m=''968620''>another</span> <span m=''968910''>situation</span>
  <span m=''969600''>where</span> <span m=''970330''>we</span> <span m=''970490''>can</span>
  <span m=''970690''>do</span> <span m=''972030''>very</span> <span m=''972370''>well.</span>
  <span m=''973040''>And</span> <span m=''973170''>here</span> <span m=''973330''>we</span>
  <span m=''973440''>can</span> <span m=''973570''>prove</span> <span m=''973960''>that</span>
  <span m=''974080''>we</span> <span m=''974200''>can</span> <span m=''974310''>do</span>
  <span m=''974450''>very</span> <span m=''974670''>well.</span> <span m=''977030''>So</span>
  <span m=''977170''>again,</span> <span m=''977510''>trying</span> <span m=''977860''>to</span>
  <span m=''978450''>be</span> <span m=''978580''>more</span> <span m=''978780''>efficient</span>
  <span m=''979990''>and</span> <span m=''980720''>this</span> <span m=''980880''>sort</span>
  <span m=''981090''>of</span> <span m=''981490''>square</span> <span m=''981910''>wasted.</span>
  <span m=''982750''>We</span> <span m=''982860''>have</span> <span m=''982980''>n</span>
  <span m=''983140''>squared</span> <span m=''983420''>of</span> <span m=''983480''>material.</span>
  <span m=''984350''>We</span> <span m=''984460''>only</span> <span m=''984610''>make</span>
  <span m=''984820''>n</span> <span m=''985060''>things.</span> <span m=''985910''>Be</span>
  <span m=''986040''>really</span> <span m=''986270''>nice</span> <span m=''986560''>if</span>
  <span m=''986690''>we</span> <span m=''986820''>could</span> <span m=''987620''>make</span>
  <span m=''987940''>n</span> <span m=''988150''>squared</span> <span m=''988450''>things</span>
  <span m=''988730''>out</span> <span m=''988880''>of</span> <span m=''988980''>an</span>
  <span m=''989080''>n</span> <span m=''989220''>by</span> <span m=''989370''>n</span>
  <span m=''990390''>grid.</span> <span m=''992290''>And</span> <span m=''992770''>oh,</span>
  <span m=''992960''>here''s</span> <span m=''993180''>another</span> <span m=''993500''>fun</span>
  <span m=''993700''>example</span> <span m=''994290''>which</span> <span m=''994595''>uses</span>
  <span m=''995270''>all</span> <span m=''995380''>those</span> <span m=''995530''>optimizations</span>
  <span m=''996210''>building</span> <span m=''996500''>a</span> <span m=''996570''>car.</span>
  <span m=''997220''>This</span> <span m=''997390''>one</span> <span m=''997540''>there''s</span>
  <span m=''997700''>a</span> <span m=''997770''>real</span> <span m=''998190''>version</span>
  <span m=''998490''>of,</span> <span m=''998610''>but</span> <span m=''998770''>I</span>
  <span m=''998790''>don''t</span> <span m=''998940''>have</span> <span m=''999130''>it</span>
  <span m=''999510''>here.</span> </p><p><span m=''1001930''>And</span> <span m=''1003240''>where</span>
  <span m=''1003450''>we</span> <span m=''1003580''>can</span> <span m=''1003730''>be</span>
  <span m=''1004160''>particularly</span> <span m=''1004740''>efficient</span> <span
  m=''1005130''>is</span> <span m=''1005300''>maze</span> <span m=''1005620''>folding.</span>
  <span m=''1007000''>So</span> <span m=''1007200''>suppose</span> <span m=''1007620''>you</span>
  <span m=''1007740''>take</span> <span m=''1008480''>a</span> <span m=''1008590''>graph</span>
  <span m=''1009140''>on</span> <span m=''1010190''>an</span> <span m=''1010270''>n</span>
  <span m=''1010420''>by</span> <span m=''1010570''>n</span> <span m=''1010740''>grid.</span>
  <span m=''1011600''>Here</span> <span m=''1011790''>it</span> <span m=''1011870''>happens</span>
  <span m=''1012190''>not</span> <span m=''1012370''>to</span> <span m=''1012430''>be</span>
  <span m=''1012550''>square.</span> <span m=''1014170''>And</span> <span m=''1014350''>then</span>
  <span m=''1014470''>you</span> <span m=''1014600''>just</span> <span m=''1014810''>sort</span>
  <span m=''1015030''>of</span> <span m=''1015220''>extrude</span> <span m=''1015860''>that</span>
  <span m=''1016070''>graph</span> <span m=''1016400''>out</span> <span m=''1016730''>from</span>
  <span m=''1016920''>the</span> <span m=''1017000''>sheet.</span> <span m=''1017960''>That</span>
  <span m=''1018150''>would</span> <span m=''1018260''>give</span> <span m=''1018440''>you</span>
  <span m=''1018640''>a</span> <span m=''1018680''>bunch</span> <span m=''1018930''>of</span>
  <span m=''1019020''>walls</span> <span m=''1019750''>in</span> <span m=''1019900''>an</span>
  <span m=''1020010''>orthogonal,</span> <span m=''1021420''>3D</span> <span m=''1022040''>pattern.</span>
  <span m=''1023500''>Let''s</span> <span m=''1023660''>say I</span> <span m=''1023830''>extrude</span>
  <span m=''1024210''>by</span> <span m=''1024339''>one</span> <span m=''1024630''>unit,</span>
  <span m=''1026329''>one</span> <span m=''1026859''>unit</span> <span m=''1027099''>of</span>
  <span m=''1027220''>this</span> <span m=''1027550''>square.</span> <span m=''1028329''>And</span>
  <span m=''1028589''>I</span> <span m=''1028730''>claim</span> <span m=''1029079''>I</span>
  <span m=''1029170''>can</span> <span m=''1029339''>fold</span> <span m=''1029869''>this</span>
  <span m=''1030140''>3D</span> <span m=''1030530''>shape</span> <span m=''1031540''>from
  a</span> <span m=''1031780''>square</span> <span m=''1032079''>of</span> <span m=''1032160''>paper</span>
  <span m=''1033550''>that</span> <span m=''1033710''>is</span> <span m=''1033859''>just</span>
  <span m=''1035349''>3n</span> <span m=''1035740''>by</span> <span m=''1035869''>3n.</span>
  <span m=''1037490''>So</span> <span m=''1037680''>it''s</span> <span m=''1037780''>just</span>
  <span m=''1037940''>a</span> <span m=''1038010''>constant</span> <span m=''1038480''>factor</span>
  <span m=''1039210''>shrinkage.</span> <span m=''1040200''>And</span> <span m=''1040339''>this</span>
  <span m=''1040530''>is</span> <span m=''1040770''>essentially</span> <span m=''1041210''>the</span>
  <span m=''1041300''>best</span> <span m=''1041530''>you</span> <span m=''1041609''>could</span>
  <span m=''1041770''>hope</span> <span m=''1041880''>for.</span> <span m=''1044022''>Yeah,</span>
  <span m=''1044900''>should</span> <span m=''1045170''>I</span> <span m=''1045220''>try</span>
  <span m=''1045400''>to</span> <span m=''1045470''>argue</span> <span m=''1045810''>it.</span>
  </p><p><span m=''1046160''>So</span> <span m=''1046369''>if</span> <span m=''1046440''>you</span>
  <span m=''1046560''>look</span> <span m=''1046780''>at</span> <span m=''1047410''>where</span>
  <span m=''1047730''>did</span> <span m=''1047970''>this</span> <span m=''1048160''>material</span>
  <span m=''1048590''>come</span> <span m=''1048810''>from,</span> <span m=''1049730''>well</span>
  <span m=''1050060''>you''ve</span> <span m=''1050240''>got</span> <span m=''1050370''>to</span>
  <span m=''1050420''>go</span> <span m=''1050560''>up</span> <span m=''1050750''>this</span>
  <span m=''1050920''>wall,</span> <span m=''1051260''>down</span> <span m=''1051510''>this</span>
  <span m=''1051680''>wall,</span> <span m=''1052610''>over</span> <span m=''1052850''>the</span>
  <span m=''1052980''>side,</span> <span m=''1053410''>up</span> <span m=''1053560''>the</span>
  <span m=''1053650''>wall,</span> <span m=''1053850''>down</span> <span m=''1054090''>the</span>
  <span m=''1054170''>wall,</span> <span m=''1054560''>over,</span> <span m=''1054976''>over,</span>
  <span m=''1055392''>over, over,</span> <span m=''1055810''>up,</span> <span m=''1056090''>down.</span>
  <span m=''1057130''>And</span> <span m=''1057370''>in</span> <span m=''1057440''>general,</span>
  <span m=''1057750''>you</span> <span m=''1057810''>have</span> <span m=''1057900''>to</span>
  <span m=''1057980''>go</span> <span m=''1058120''>up</span> <span m=''1058320''>and</span>
  <span m=''1058420''>down</span> <span m=''1058710''>and</span> <span m=''1059390''>along</span>
  <span m=''1059740''>the</span> <span m=''1059820''>floor.</span> <span m=''1060340''>So</span>
  <span m=''1060490''>that''s</span> <span m=''1060690''>three</span> <span m=''1061440''>for</span>
  <span m=''1061620''>every</span> <span m=''1062220''>square</span> <span m=''1062510''>that
  you</span> <span m=''1062800''>have</span> <span m=''1063300''>here.</span> <span
  m=''1065550''>So</span> <span m=''1065800''>that''s</span> <span m=''1066050''>maze</span>
  <span m=''1066300''>folding.</span> <span m=''1066670''>And</span> <span m=''1066750''>this</span>
  <span m=''1066930''>is</span> <span m=''1067040''>work</span> <span m=''1067280''>with</span>
  <span m=''1067730''>Jason</span> <span m=''1068060''>Ku</span> <span m=''1068370''>and</span>
  <span m=''1068600''>Marty,</span> <span m=''1070150''>also</span> <span m=''1070650''>from</span>
  <span m=''1071540''>the</span> <span m=''1071950''>big</span> <span m=''1072170''>origami</span>
  <span m=''1072590''>conference</span> <span m=''1074430''>this</span> <span m=''1074600''>summer.</span>
  </p><p><span m=''1087690''>So</span> <span m=''1088010''>you</span> <span m=''1088230''>could</span>
  <span m=''1088350''>call</span> <span m=''1088570''>it</span> <span m=''1088630''>a</span>
  <span m=''1089065''>maze.</span> <span m=''1089500''>You could call it a</span>
  <span m=''1089810''>graph.</span> <span m=''1091610''>But</span> <span m=''1092040''>it''s</span>
  <span m=''1092200''>orthogonal.</span> <span m=''1092740''>It''s</span> <span m=''1092870''>on</span>
  <span m=''1092970''>the</span> <span m=''1093050''>grid.</span> <span m=''1094380''>And</span>
  <span m=''1095320''>it''s</span> <span m=''1096000''>extruded</span> <span m=''1096500''>from</span>
  <span m=''1096850''>an</span> <span m=''1096930''>n</span> <span m=''1097130''>by</span>
  <span m=''1097290''>n</span> <span m=''1097500''>square</span> <span m=''1098160''>let''s</span>
  <span m=''1098380''>say.</span> <span m=''1101358''>And</span> <span m=''1102280''>that</span>
  <span m=''1102600''>thing</span> <span m=''1102890''>can</span> <span m=''1103000''>be</span>
  <span m=''1103130''>folded</span> <span m=''1109690''>from</span> <span m=''1110070''>an</span>
  <span m=''1110160''>order</span> <span m=''1110420''>n</span> <span m=''1111820''>by</span>
  <span m=''1112010''>order</span> <span m=''1112300''>n</span> <span m=''1114080''>square
  of</span> <span m=''1114500''>paper.</span> <span m=''1118920''>And</span> <span
  m=''1119210''>if</span> <span m=''1119320''>you''re</span> <span m=''1119440''>extruding</span>
  <span m=''1119820''>by</span> <span m=''1119950''>one</span> <span m=''1120200''>unit,</span>
  <span m=''1120540''>this</span> <span m=''1121550''>big O</span> <span m=''1121900''>at</span>
  <span m=''1122030''>that</span> <span m=''1122390''>three.</span> <span m=''1124270''>And</span>
  <span m=''1124540''>to</span> <span m=''1124630''>me</span> <span m=''1124740''>this</span>
  <span m=''1124910''>is</span> <span m=''1125010''>really</span> <span m=''1125210''>exciting.</span>
  <span m=''1125580''>Because</span> <span m=''1126370''>one</span> <span m=''1126800''>of</span>
  <span m=''1126890''>the</span> <span m=''1126970''>big</span> <span m=''1127930''>mysteries</span>
  <span m=''1128470''>to</span> <span m=''1128590''>me</span> <span m=''1128800''>in</span>
  <span m=''1128920''>origami</span> <span m=''1129560''>design</span> <span m=''1129950''>is</span>
  <span m=''1130080''>in</span> <span m=''1130130''>practical</span> <span m=''1130580''>origami,</span>
  <span m=''1131050''>you usually</span> <span m=''1131430''>start</span> <span m=''1131680''>with</span>
  <span m=''1131780''>a</span> <span m=''1131830''>sheet.</span> <span m=''1132440''>And</span>
  <span m=''1132700''>you</span> <span m=''1132790''>make</span> <span m=''1132980''>something</span>
  <span m=''1133360''>that''s</span> <span m=''1133600''>like</span> <span m=''1133780''>two</span>
  <span m=''1133930''>or</span> <span m=''1134020''>three</span> <span m=''1134220''>times</span>
  <span m=''1134470''>smaller</span> <span m=''1135410''>and</span> <span m=''1135600''>never</span>
  <span m=''1136260''>much</span> <span m=''1136530''>more.</span> <span m=''1137740''>And</span>
  <span m=''1138060''>it would</span> <span m=''1138150''>be</span> <span m=''1138280''>really</span>
  <span m=''1138510''>nice</span> <span m=''1138700''>to</span> <span m=''1138780''>capture</span>
  <span m=''1139140''>theoretically</span> <span m=''1139660''>what</span> <span m=''1139990''>things</span>
  <span m=''1140230''>can</span> <span m=''1140360''>you</span> <span m=''1140470''>make</span>
  <span m=''1140810''>by</span> <span m=''1140940''>only</span> <span m=''1141220''>shrinking</span>
  <span m=''1141600''>by a</span> <span m=''1141760''>constant</span> <span m=''1142140''>factor.</span>
  </p><p><span m=''1143130''>Like</span> <span m=''1143330''>checkerboards,</span>
  <span m=''1143890''>we</span> <span m=''1144030''>know,</span> <span m=''1144540''>or</span>
  <span m=''1144690''>we</span> <span m=''1145140''>think,</span> <span m=''1145870''>you</span>
  <span m=''1145970''>have</span> <span m=''1146080''>to</span> <span m=''1146160''>shrink</span>
  <span m=''1146380''>a</span> <span m=''1146420''>lot.</span> <span m=''1147750''>For</span>
  <span m=''1147930''>an</span> <span m=''1148000''>n</span> <span m=''1148160''>by</span>
  <span m=''1148300''>n</span> <span m=''1148410''>checkerboard,</span> <span m=''1148860''>you
  have</span> <span m=''1148970''>to shrink by</span> <span m=''1149390''>like</span>
  <span m=''1149590''>factor</span> <span m=''1149960''>of</span> <span m=''1150060''>n</span>
  <span m=''1150450''>over</span> <span m=''1150660''>2,</span> <span m=''1151730''>n</span>
  <span m=''1151940''>over</span> <span m=''1152080''>4,</span> <span m=''1152580''>whatever</span>
  <span m=''1153260''>the</span> <span m=''1153340''>best</span> <span m=''1153620''>bound</span>
  <span m=''1153750''>is.</span> <span m=''1154090''>But</span> <span m=''1154750''>it</span>
  <span m=''1154870''>seems</span> <span m=''1155110''>the</span> <span m=''1155240''>more</span>
  <span m=''1155540''>complicated</span> <span m=''1156110''>you</span> <span m=''1156210''>want,</span>
  <span m=''1156590''>the</span> <span m=''1156660''>more</span> <span m=''1156870''>you</span>
  <span m=''1156910''>have</span> <span m=''1157020''>to</span> <span m=''1157110''>fold.</span>
  <span m=''1157370''>Here,</span> <span m=''1158070''>I</span> <span m=''1158190''>can</span>
  <span m=''1158320''>make</span> <span m=''1158470''>a</span> <span m=''1158530''>super</span>
  <span m=''1159000''>complicated</span> <span m=''1159550''>maze.</span> <span m=''1159850''>It</span>
  <span m=''1159930''>could</span> <span m=''1160060''>be</span> <span m=''1160680''>a</span>
  <span m=''1160760''>million</span> <span m=''1161090''>by</span> <span m=''1161260''>million.</span>
  <span m=''1161780''>And</span> <span m=''1161950''>I''m</span> <span m=''1162010''>still</span>
  <span m=''1162310''>only</span> <span m=''1162390''>shrinking</span> <span m=''1162740''>the</span>
  <span m=''1162810''>sheet</span> <span m=''1163110''>by</span> <span m=''1163510''>a</span>
  <span m=''1163860''>factor</span> <span m=''1164100''>of</span> <span m=''1164200''>three.</span>
  <span m=''1165520''>So</span> <span m=''1165910''>this</span> <span m=''1166110''>is</span>
  <span m=''1166380''>one</span> <span m=''1166560''>of</span> <span m=''1166610''>the</span>
  <span m=''1166680''>few</span> <span m=''1166880''>results</span> <span m=''1167330''>we</span>
  <span m=''1167430''>know</span> <span m=''1167610''>where</span> <span m=''1167900''>you</span>
  <span m=''1168030''>can</span> <span m=''1168170''>get</span> <span m=''1168710''>a</span>
  <span m=''1168810''>large</span> <span m=''1169160''>class,</span> <span m=''1169550''>and</span>
  <span m=''1169630''>yet you''re</span> <span m=''1169910''>only</span> <span m=''1170080''>shrinking</span>
  <span m=''1170430''>by</span> <span m=''1170600''>small</span> <span m=''1170870''>factor.</span>
  </p><p><span m=''1173800''>The</span> <span m=''1173920''>proof</span> <span m=''1174120''>of</span>
  <span m=''1174200''>this</span> <span m=''1174360''>is</span> <span m=''1174450''>also</span>
  <span m=''1174960''>pretty</span> <span m=''1175200''>easy,</span> <span m=''1176000''>in</span>
  <span m=''1176430''>fact</span> <span m=''1176630''>even</span> <span m=''1176850''>easier</span>
  <span m=''1177340''>than</span> <span m=''1177450''>the</span> <span m=''1177520''>previous</span>
  <span m=''1177880''>one.</span> <span m=''1179600''>Again,</span> <span m=''1179900''>we''re</span>
  <span m=''1180040''>going</span> <span m=''1180130''>to</span> <span m=''1180170''>use</span>
  <span m=''1180350''>gadgets.</span> <span m=''1180930''>And</span> <span m=''1181000''>we''re</span>
  <span m=''1181140''>going</span> <span m=''1181230''>to</span> <span m=''1181290''>combine</span>
  <span m=''1181730''>them</span> <span m=''1182770''>in</span> <span m=''1182850''>different</span>
  <span m=''1183110''>ways.</span> <span m=''1184580''>But</span> <span m=''1184720''>the</span>
  <span m=''1184830''>idea</span> <span m=''1185230''>is</span> <span m=''1185920''>we</span>
  <span m=''1186060''>just</span> <span m=''1186260''>make</span> <span m=''1187320''>a</span>
  <span m=''1187410''>gadget</span> <span m=''1188840''>for</span> <span m=''1189060''>each</span>
  <span m=''1190420''>possible</span> <span m=''1191900''>vertex</span> <span m=''1192400''>in</span>
  <span m=''1192490''>this</span> <span m=''1192650''>graph.</span> <span m=''1195570''>So</span>
  <span m=''1195690''>a</span> <span m=''1195750''>vertex</span> <span m=''1196250''>in</span>
  <span m=''1196400''>the</span> <span m=''1196480''>graph</span> <span m=''1197360''>could</span>
  <span m=''1197600''>have</span> <span m=''1198430''>no</span> <span m=''1198640''>edges</span>
  <span m=''1199200''>incident</span> <span m=''1199590''>to</span> <span m=''1199710''>it.</span>
  <span m=''1200340''>So</span> <span m=''1200450''>we</span> <span m=''1200540''>call</span>
  <span m=''1200760''>this</span> <span m=''1201530''>degree</span> <span m=''1201890''>0.</span>
  <span m=''1204960''>Or</span> <span m=''1205300''>it</span> <span m=''1205390''>could</span>
  <span m=''1205570''>have</span> <span m=''1205820''>one</span> <span m=''1206050''>incident</span>
  <span m=''1206370''>edge</span> <span m=''1207580''>and</span> <span m=''1207800''>the</span>
  <span m=''1207890''>rest</span> <span m=''1208280''>are</span> <span m=''1208500''>absent.</span>
  <span m=''1209740''>That''s</span> <span m=''1209960''>degree</span> <span m=''1210190''>1.</span>
  </p><p><span m=''1211280''>Or</span> <span m=''1211570''>it</span> <span m=''1211650''>could</span>
  <span m=''1211790''>have</span> <span m=''1211950''>two</span> <span m=''1212170''>incident</span>
  <span m=''1212490''>edges.</span> <span m=''1212850''>And</span> <span m=''1212940''>there''s</span>
  <span m=''1213100''>two</span> <span m=''1213330''>ways</span> <span m=''1213620''>it</span>
  <span m=''1213690''>could</span> <span m=''1213830''>be</span> <span m=''1213940''>like</span>
  <span m=''1214120''>that.</span> <span m=''1214320''>It</span> <span m=''1214390''>could</span>
  <span m=''1214510''>be</span> <span m=''1214630''>a</span> <span m=''1214690''>turn</span>
  <span m=''1215710''>or</span> <span m=''1216090''>it</span> <span m=''1216240''>could</span>
  <span m=''1216420''>be</span> <span m=''1216710''>straight.</span> <span m=''1221220''>You</span>
  <span m=''1221390''>could</span> <span m=''1221490''>have</span> <span m=''1221600''>three</span>
  <span m=''1221820''>incident</span> <span m=''1222120''>edges.</span> <span m=''1225410''>Or</span>
  <span m=''1225640''>you</span> <span m=''1225760''>could</span> <span m=''1225850''>have</span>
  <span m=''1225990''>four</span> <span m=''1226250''>incident</span> <span m=''1226550''>edges.</span>
  <span m=''1229720''>So</span> <span m=''1229830''>that''s</span> <span m=''1230060''>all</span>
  <span m=''1230360''>the</span> <span m=''1230450''>possible</span> <span m=''1230870''>vertices</span>
  <span m=''1231330''>in our</span> <span m=''1231410''>orthogonal</span> <span m=''1231960''>graph.</span>
  </p><p><span m=''1232770''>And</span> <span m=''1233000''>we''re</span> <span m=''1233090''>just</span>
  <span m=''1233250''>going</span> <span m=''1233360''>to</span> <span m=''1233420''>make</span>
  <span m=''1233750''>a</span> <span m=''1233870''>crease</span> <span m=''1234140''>pattern,</span>
  <span m=''1234530''>a</span> <span m=''1234620''>folding</span> <span m=''1235470''>for</span>
  <span m=''1235670''>each</span> <span m=''1235840''>one</span> <span m=''1236060''>of</span>
  <span m=''1236150''>these</span> <span m=''1237530''>and</span> <span m=''1237670''>then</span>
  <span m=''1237780''>just</span> <span m=''1237950''>combine</span> <span m=''1238290''>them</span>
  <span m=''1238420''>together.</span> <span m=''1239200''>Now</span> <span m=''1240090''>it</span>
  <span m=''1240230''>takes</span> <span m=''1240440''>a</span> <span m=''1240500''>lot</span>
  <span m=''1240660''>of</span> <span m=''1240750''>care</span> <span m=''1241090''>in</span>
  <span m=''1241150''>designing</span> <span m=''1241590''>those</span> <span m=''1242290''>patterns</span>
  <span m=''1243360''>that</span> <span m=''1243490''>they</span> <span m=''1243570''>actually</span>
  <span m=''1243880''>fit</span> <span m=''1244100''>together.</span> <span m=''1245380''>But</span>
  <span m=''1246100''>all</span> <span m=''1246310''>you</span> <span m=''1246400''>need</span>
  <span m=''1246560''>to</span> <span m=''1246660''>know</span> <span m=''1246820''>is</span>
  <span m=''1246960''>that it</span> <span m=''1247120''>can</span> <span m=''1247250''>be</span>
  <span m=''1247360''>done.</span> <span m=''1248970''>And</span> <span m=''1250540''>they''re</span>
  <span m=''1250670''>not</span> <span m=''1251520''>trivial.</span> <span m=''1252450''>But</span>
  <span m=''1252560''>once</span> <span m=''1252760''>you</span> <span m=''1252830''>have</span>
  <span m=''1253070''>them,</span> <span m=''1253220''>it''s</span> <span m=''1253330''>easy.</span>
  <span m=''1254580''>So</span> <span m=''1254720''>you''ve</span> <span m=''1254790''>got</span>
  <span m=''1254940''>degree</span> <span m=''1255080''>0</span> <span m=''1255360''>on</span>
  <span m=''1255480''>the</span> <span m=''1255570''>top,</span> <span m=''1256550''>degree</span>
  <span m=''1256820''>2</span> <span m=''1257320''>straight,</span> <span m=''1258360''>degree</span>
  <span m=''1258600''>4,</span> <span m=''1259190''>degree</span> <span m=''1259460''>3,</span>
  <span m=''1260070''>degree</span> <span m=''1260290''>1,</span> <span m=''1260720''>degree</span>
  <span m=''1260980''>2</span> <span m=''1261250''>turned.</span> <span m=''1262630''>And</span>
  <span m=''1263010''>they''re at,  I</span> <span m=''1263440''>guess,</span> <span
  m=''1263700''>an</span> <span m=''1263810''>increasing</span> <span m=''1264250''>order</span>
  <span m=''1264430''>of</span> <span m=''1264490''>difficulty.</span> </p><p><span
  m=''1266210''>And</span> <span m=''1267110''>we</span> <span m=''1267250''>need</span>
  <span m=''1267400''>to</span> <span m=''1267670''>know</span> <span m=''1267950''>that</span>
  <span m=''1268090''>these</span> <span m=''1268300''>things</span> <span m=''1268550''>exist.</span>
  <span m=''1269240''>One</span> <span m=''1269450''>way</span> <span m=''1269640''>is</span>
  <span m=''1269800''>to</span> <span m=''1270240''>in some</span> <span m=''1270430''>sense</span>
  <span m=''1270780''>just</span> <span m=''1270950''>to</span> <span m=''1271030''>draw</span>
  <span m=''1271260''>the</span> <span m=''1271370''>picture</span> <span m=''1271760''>of</span>
  <span m=''1271860''>the</span> <span m=''1271940''>folded</span> <span m=''1272280''>state.</span>
  <span m=''1272880''>But</span> <span m=''1273210''>there''s</span> <span m=''1273360''>so</span>
  <span m=''1273520''>many</span> <span m=''1273710''>layers</span> <span m=''1274070''>here</span>
  <span m=''1274180''>it''s</span> <span m=''1274290''>a</span> <span m=''1274330''>little</span>
  <span m=''1274520''>hard</span> <span m=''1274720''>to</span> <span m=''1274800''>see,</span>
  <span m=''1275530''>and</span> <span m=''1275810''>so</span> <span m=''1276000''>in</span>
  <span m=''1276060''>order</span> <span m=''1276240''>to</span> <span m=''1276640''>really</span>
  <span m=''1276970''>prove</span> <span m=''1277440''>that</span> <span m=''1277730''>these</span>
  <span m=''1277930''>things</span> <span m=''1278120''>exist,</span> <span m=''1278950''>Jason</span>
  <span m=''1279240''>drew</span> <span m=''1279430''>diagrams</span> <span m=''1280010''>of</span>
  <span m=''1280080''>how</span> <span m=''1280430''>these</span> <span m=''1280610''>things</span>
  <span m=''1280920''>could</span> <span m=''1281090''>actually</span> <span m=''1281360''>be</span>
  <span m=''1281490''>folded</span> <span m=''1282130''>in</span> <span m=''1282290''>isolation.</span>
  <span m=''1283870''>In some</span> <span m=''1283970''>sense,</span> <span m=''1284170''>we</span>
  <span m=''1284290''>only</span> <span m=''1284520''>care</span> <span m=''1284710''>about</span>
  <span m=''1284880''>this</span> <span m=''1285050''>final</span> <span m=''1285350''>3D</span>
  <span m=''1285590''>picture in</span> <span m=''1285910''>knowing</span> <span m=''1286220''>that</span>
  <span m=''1286330''>it</span> <span m=''1286430''>works</span> <span m=''1286750''>and</span>
  <span m=''1286860''>is</span> <span m=''1287050''>non</span> <span m=''1287240''>self-intersecting</span>
  <span m=''1287980''>and</span> <span m=''1288060''>all</span> <span m=''1288180''>that.</span>
  <span m=''1288500''>But</span> <span m=''1289240''>to</span> <span m=''1289610''>show</span>
  <span m=''1289900''>that</span> <span m=''1290100''>these</span> <span m=''1290310''>exist,</span>
  <span m=''1291220''>one</span> <span m=''1291510''>way</span> <span m=''1291710''>is</span>
  <span m=''1291910''>to</span> <span m=''1292240''>actually</span> <span m=''1293150''>build</span>
  <span m=''1293340''>them</span> <span m=''1294780''>or</span> <span m=''1294880''>show</span>
  <span m=''1295080''>the</span> <span m=''1295600''>sequence</span> <span m=''1296120''>that</span>
  <span m=''1296200''>got</span> <span m=''1296440''>there.</span> </p><p><span m=''1297680''>But</span>
  <span m=''1297810''>in</span> <span m=''1297880''>reality,</span> <span m=''1298380''>you
  wouldn''t</span> <span m=''1298610''>fold</span> <span m=''1298830''>it</span> <span
  m=''1298900''>this</span> <span m=''1299100''>way.</span> <span m=''1299720''>Because</span>
  <span m=''1300020''>what</span> <span m=''1300150''>you</span> <span m=''1300280''>do</span>
  <span m=''1300490''>is</span> <span m=''1300610''>you</span> <span m=''1300780''>take</span>
  <span m=''1301040''>these</span> <span m=''1301230''>crease</span> <span m=''1301470''>patterns</span>
  <span m=''1301820''>on</span> <span m=''1301880''>the</span> <span m=''1301960''>left</span>
  <span m=''1303130''>and</span> <span m=''1303310''>just</span> <span m=''1303460''>start</span>
  <span m=''1304120''>pasting</span> <span m=''1304540''>them</span> <span m=''1304670''>together.</span>
  <span m=''1305230''>It''s</span> <span m=''1305340''>like</span> <span m=''1305490''>a</span>
  <span m=''1305540''>big</span> <span m=''1305740''>cut</span> <span m=''1305980''>and</span>
  <span m=''1306060''>paste</span> <span m=''1306760''>job.</span> <span m=''1307200''>So</span>
  <span m=''1307500''>you</span> <span m=''1307600''>say,</span> <span m=''1307850''>oh</span>
  <span m=''1308350''>well</span> <span m=''1308670''>maybe</span> <span m=''1309770''>like</span>
  <span m=''1309950''>if</span> <span m=''1310060''>I</span> <span m=''1310100''>made</span>
  <span m=''1310330''>the</span> <span m=''1310390''>square</span> <span m=''1310920''>of</span>
  <span m=''1311020''>turns,</span> <span m=''1311810''>I</span> <span m=''1312010''>would</span>
  <span m=''1312110''>just</span> <span m=''1312280''>take</span> <span m=''1312770''>one</span>
  <span m=''1312950''>of</span> <span m=''1313030''>these,</span> <span m=''1313850''>copy,</span>
  <span m=''1314280''>rotate,</span> <span m=''1314920''>put</span> <span m=''1315070''>it</span>
  <span m=''1315140''>here,</span> <span m=''1315680''>copy,</span> <span m=''1316000''>rotate,</span>
  <span m=''1316340''>put</span> <span m=''1316470''>it</span> <span m=''1316530''>here,</span>
  <span m=''1316760''>copy, rotate,</span> <span m=''1317340''>put</span> <span m=''1317470''>it</span>
  <span m=''1317550''>here.</span> <span m=''1318150''>And</span> <span m=''1318250''>that
  would</span> <span m=''1318460''>make</span> <span m=''1318680''>a</span> <span
  m=''1318740''>square</span> <span m=''1319230''>root</span> <span m=''1319330''>of</span>
  <span m=''1319380''>turns.</span> </p><p><span m=''1320770''>And</span> <span m=''1321220''>what</span>
  <span m=''1321400''>you</span> <span m=''1321510''>need</span> <span m=''1321700''>for</span>
  <span m=''1321800''>that</span> <span m=''1322000''>to</span> <span m=''1322110''>work</span>
  <span m=''1322370''>is</span> <span m=''1322510''>that</span> <span m=''1322680''>the</span>
  <span m=''1322880''>interfaces</span> <span m=''1323570''>here</span> <span m=''1324240''>are</span>
  <span m=''1324390''>compatible.</span> <span m=''1325790''>You</span> <span m=''1325910''>can</span>
  <span m=''1326050''>think</span> <span m=''1326210''>of</span> <span m=''1326300''>it</span>
  <span m=''1326360''>in</span> <span m=''1326450''>the</span> <span m=''1326540''>crease</span>
  <span m=''1326790''>pattern,</span> <span m=''1327130''>or</span> <span m=''1327260''>you</span>
  <span m=''1327340''>can</span> <span m=''1327510''>think</span> <span m=''1327670''>of</span>
  <span m=''1327780''>it</span> <span m=''1327870''>in</span> <span m=''1328110''>the
  3D</span> <span m=''1328450''>state.</span> <span m=''1329160''>The</span> <span
  m=''1329300''>interface</span> <span m=''1329960''>in</span> <span m=''1330120''>all</span>
  <span m=''1330450''>of</span> <span m=''1330540''>these</span> <span m=''1330730''>pictures</span>
  <span m=''1331890''>is</span> <span m=''1332100''>that</span> <span m=''1332250''>when</span>
  <span m=''1332460''>you</span> <span m=''1332580''>have</span> <span m=''1333010''>an</span>
  <span m=''1333150''>actual</span> <span m=''1333600''>edge</span> <span m=''1334080''>that''s</span>
  <span m=''1334320''>raised,</span> <span m=''1335640''>it''s</span> <span m=''1335830''>very</span>
  <span m=''1335970''>simple.</span> <span m=''1336310''>It just</span> <span m=''1336500''>goes</span>
  <span m=''1336710''>over,</span> <span m=''1337160''>up,</span> <span m=''1337490''>down,</span>
  <span m=''1337910''>over.</span> <span m=''1339300''>And</span> <span m=''1339590''>when</span>
  <span m=''1339800''>you</span> <span m=''1339890''>have</span> <span m=''1340280''>an</span>
  <span m=''1340410''>edge</span> <span m=''1340650''>that doesn''t</span> <span m=''1340990''>exist,</span>
  <span m=''1341770''>you</span> <span m=''1341860''>go</span> <span m=''1342050''>over</span>
  <span m=''1342470''>and</span> <span m=''1342640''>then</span> <span m=''1342740''>you</span>
  <span m=''1342820''>have</span> <span m=''1342950''>a</span> <span m=''1343020''>pleat</span>
  <span m=''1343360''>underneath.</span> <span m=''1344790''>And</span> <span m=''1344960''>then</span>
  <span m=''1345140''>you</span> <span m=''1345280''>go</span> <span m=''1345530''>over.</span>
  <span m=''1346980''>And</span> <span m=''1347220''>it''s</span> <span m=''1347600''>important</span>
  <span m=''1348000''>that</span> <span m=''1348120''>those</span> <span m=''1348350''>are</span>
  <span m=''1348430''>the</span> <span m=''1348550''>same</span> <span m=''1348820''>total</span>
  <span m=''1349150''>length.</span> <span m=''1349630''>Because</span> <span m=''1349960''>you</span>
  <span m=''1350090''>need</span> <span m=''1351570''>to</span> <span m=''1351660''>be</span>
  <span m=''1351740''>able</span> <span m=''1351880''>to</span> <span m=''1351960''>choose</span>
  <span m=''1352340''>whether</span> <span m=''1352680''>it''s</span> <span m=''1352800''>a</span>
  <span m=''1352850''>raised</span> <span m=''1353150''>edge</span> <span m=''1353370''>or
  a</span> <span m=''1353510''>non-raised</span> <span m=''1354040''>edge.</span>
  </p><p><span m=''1355380''>And</span> <span m=''1355520''>because</span> <span m=''1356020''>all</span>
  <span m=''1356320''>of</span> <span m=''1356390''>those</span> <span m=''1356590''>interfaces</span>
  <span m=''1357150''>are</span> <span m=''1357240''>the</span> <span m=''1357350''>same,</span>
  <span m=''1357810''>all of</span> <span m=''1358120''>the</span> <span m=''1358220''>down</span>
  <span m=''1358480''>edges</span> <span m=''1358870''>are</span> <span m=''1359100''>this</span>
  <span m=''1359340''>kind</span> <span m=''1359490''>of</span> <span m=''1359570''>double</span>
  <span m=''1359840''>pleat.</span> <span m=''1360310''>And</span> <span m=''1360670''>all
  of</span> <span m=''1360910''>the</span> <span m=''1361050''>up</span> <span m=''1361240''>edges</span>
  <span m=''1361620''>are</span> <span m=''1361700''>just</span> <span m=''1362010''>the</span>
  <span m=''1362250''>ridge.</span> <span m=''1363400''>These</span> <span m=''1363640''>things</span>
  <span m=''1363880''>fit</span> <span m=''1364120''>together.</span> <span m=''1364820''>And</span>
  <span m=''1364920''>you</span> <span m=''1365020''>can</span> <span m=''1365130''>see</span>
  <span m=''1365300''>that</span> <span m=''1365480''>in</span> <span m=''1365550''>the</span>
  <span m=''1365640''>crease</span> <span m=''1365890''>pattern</span> <span m=''1366210''>also.</span>
  <span m=''1367170''>Here''s</span> <span m=''1367440''>what</span> <span m=''1367590''>the</span>
  <span m=''1367680''>pleat</span> <span m=''1367890''>looks</span> <span m=''1368120''>like.</span>
  <span m=''1368405''>And it</span> <span m=''1368690''>can</span> <span m=''1368860''>match</span>
  <span m=''1369110''>with</span> <span m=''1369220''>this</span> <span m=''1369390''>pleat</span>
  <span m=''1369720''>or</span> <span m=''1369800''>this</span> <span m=''1370030''>one.</span>
  <span m=''1370820''>You</span> <span m=''1370910''>can</span> <span m=''1371040''>rotate.</span>
  <span m=''1372190''>Here</span> <span m=''1372540''>is</span> <span m=''1372700''>the</span>
  <span m=''1373770''>ridge.</span> <span m=''1374110''>It</span> <span m=''1374450''>just</span>
  <span m=''1374640''>goes</span> <span m=''1374960''>up</span> <span m=''1375750''>and</span>
  <span m=''1376020''>back</span> <span m=''1376220''>down.</span> <span m=''1378920''>And</span>
  <span m=''1379900''>you</span> <span m=''1380020''>just</span> <span m=''1380440''>paste
  those</span> <span m=''1380860''>together.</span> <span m=''1381280''>And</span>
  <span m=''1381630''>you</span> <span m=''1381730''>get</span> <span m=''1381960''>your</span>
  <span m=''1383330''>desired</span> <span m=''1383720''>crease</span> <span m=''1383980''>pattern.</span>
  <span m=''1384360''>So</span> <span m=''1384480''>here''s</span> <span m=''1384700''>a</span>
  <span m=''1384740''>simple</span> <span m=''1385090''>example.</span> <span m=''1386020''>The</span>
  <span m=''1386090''>graph</span> <span m=''1386340''>has</span> <span m=''1386570''>almost</span>
  <span m=''1386930''>all</span> <span m=''1387110''>the</span> <span m=''1387150''>vertices,</span>
  <span m=''1387820''>everything</span> <span m=''1388220''>except</span> <span m=''1388410''>0</span>
  <span m=''1388810''>I</span> <span m=''1388890''>think,</span> <span m=''1390820''>and</span>
  <span m=''1391060''>straights.</span> <span m=''1391800''>All right,</span> <span
  m=''1392320''>not</span> <span m=''1392450''>quite</span> <span m=''1392630''>all</span>
  <span m=''1392850''>of them.</span> </p><p><span m=''1393990''>But</span> <span
  m=''1394210''>I''ve</span> <span m=''1394890''>color</span> <span m=''1395210''>coded</span>
  <span m=''1395590''>here.</span> <span m=''1395920''>So</span> <span m=''1396370''>like</span>
  <span m=''1396560''>you</span> <span m=''1396650''>take</span> <span m=''1396860''>the</span>
  <span m=''1396940''>graph.</span> <span m=''1397280''>You</span> <span m=''1397350''>just</span>
  <span m=''1397520''>embed it</span> <span m=''1397960''>on</span> <span m=''1398080''>a</span>
  <span m=''1398130''>slightly</span> <span m=''1398450''>larger</span> <span m=''1398810''>grid.</span>
  <span m=''1399280''>And</span> <span m=''1399570''>you</span> <span m=''1399750''>replace</span>
  <span m=''1400240''>each</span> <span m=''1400400''>of</span> <span m=''1400460''>those</span>
  <span m=''1400650''>vertices</span> <span m=''1401680''>with</span> <span m=''1402320''>the</span>
  <span m=''1402420''>crease</span> <span m=''1402650''>pattern that</span> <span
  m=''1403000''>makes</span> <span m=''1403230''>that</span> <span m=''1403460''>thing.</span>
  <span m=''1403650''>You</span> <span m=''1403730''>just</span> <span m=''1403920''>have</span>
  <span m=''1404020''>to</span> <span m=''1404130''>rotate</span> <span m=''1404510''>it</span>
  <span m=''1405010''>for</span> <span m=''1405170''>it</span> <span m=''1405270''>to</span>
  <span m=''1405280''>work</span> <span m=''1405500''>out.</span> <span m=''1406140''>And</span>
  <span m=''1406390''>then you</span> <span m=''1406480''>see</span> <span m=''1406800''>that
  all of</span> <span m=''1407140''>these</span> <span m=''1408120''>creases</span>
  <span m=''1408580''>just</span> <span m=''1408790''>meet</span> <span m=''1409040''>up</span>
  <span m=''1409930''>correctly.</span> <span m=''1410500''>And</span> <span m=''1410990''>then</span>
  <span m=''1411160''>that''s</span> <span m=''1411370''>your</span> <span m=''1411470''>crease</span>
  <span m=''1411700''>pattern,</span> <span m=''1412080''>which</span> <span m=''1412130''>will</span>
  <span m=''1412210''>fold</span> <span m=''1412440''>this.</span> <span m=''1414530''>So</span>
  <span m=''1414740''>that</span> <span m=''1414890''>once</span> <span m=''1415170''>you</span>
  <span m=''1415250''>have</span> <span m=''1415370''>the</span> <span m=''1415450''>gadgets,</span>
  <span m=''1415870''>the</span> <span m=''1415950''>algorithm is</span> <span m=''1416340''>super</span>
  <span m=''1416630''>simple,</span> <span m=''1416970''>just</span> <span m=''1418030''>a</span>
  <span m=''1418110''>bunch</span> <span m=''1418330''>of</span> <span m=''1418410''>cutting</span>
  <span m=''1418760''>and</span> <span m=''1418890''>pasting.</span> <span m=''1421290''>And</span>
  <span m=''1421390''>you</span> <span m=''1421510''>can</span> <span m=''1421640''>do</span>
  <span m=''1421780''>more</span> <span m=''1421930''>complicated</span> <span m=''1422500''>examples.</span>
  <span m=''1423010''>Here''s</span> <span m=''1423180''>an</span> <span m=''1423260''>actual</span>
  <span m=''1424250''>maze.</span> <span m=''1427640''>Get</span> <span m=''1427820''>some</span>
  <span m=''1427970''>pretty</span> <span m=''1428210''>complicated</span> <span m=''1428680''>crease</span>
  <span m=''1428910''>patterns.</span> <span m=''1430450''>Not</span> <span m=''1430680''>so</span>
  <span m=''1430830''>easy</span> <span m=''1431050''>to</span> <span m=''1431130''>fold.</span>
  <span m=''1432560''>But</span> <span m=''1433560''>it</span> <span m=''1433680''>can</span>
  <span m=''1433830''>be</span> <span m=''1433930''>done.</span> <span m=''1435310''>I</span>
  <span m=''1435400''>didn''t</span> <span m=''1435600''>bring</span> <span m=''1435780''>the</span>
  <span m=''1435870''>physical</span> <span m=''1436290''>model</span> <span m=''1436620''>of
  this,</span> <span m=''1436800''>because it</span> <span m=''1436970''>actually</span>
  <span m=''1437250''>looks</span> <span m=''1437440''>better</span> <span m=''1437690''>in</span>
  <span m=''1437780''>photograph.</span> <span m=''1441240''>It''s a</span> <span
  m=''1441330''>challenge.</span> <span m=''1441970''>This was</span> <span m=''1441990''>folded</span>
  <span m=''1442290''>by</span> <span m=''1442540''>an</span> <span m=''1442790''>undergrad</span>
  <span m=''1443190''>here,</span> <span m=''1443600''>Chris</span> <span m=''1443950''>Chin.</span>
  </p><p><span m=''1445440''>And</span> <span m=''1445790''>in fact,</span> <span
  m=''1446600''>it''s</span> <span m=''1446760''>such</span> <span m=''1446990''>an</span>
  <span m=''1447050''>easy</span> <span m=''1447340''>an</span> <span m=''1447580''>algorithm,</span>
  <span m=''1448390''>I</span> <span m=''1448520''>implemented</span> <span m=''1449070''>it</span>
  <span m=''1449600''>as</span> <span m=''1449810''>a</span> <span m=''1449910''>web</span>
  <span m=''1450160''>application.</span> <span m=''1450445''>It</span> <span m=''1450730''>runs</span>
  <span m=''1450920''>in</span> <span m=''1450980''>JavaScript.</span> <span m=''1452230''>And</span>
  <span m=''1452460''>you</span> <span m=''1452570''>can</span> <span m=''1452700''>go</span>
  <span m=''1452850''>play</span> <span m=''1453050''>with</span> <span m=''1453210''>it.</span>
  <span m=''1454500''>It''s</span> <span m=''1455580''>[INAUDIBLE].</span> <span m=''1457870''>And</span>
  <span m=''1458220''>you</span> <span m=''1458330''>can</span> <span m=''1458460''>say,</span>
  <span m=''1458600''>OK</span> <span m=''1458830''>give</span> <span m=''1458980''>me</span>
  <span m=''1459150''>a random</span> <span m=''1459350''>maze.</span> <span m=''1460040''>And</span>
  <span m=''1460390''>you</span> <span m=''1460490''>get</span> <span m=''1460630''>a</span>
  <span m=''1460810''>3D</span> <span m=''1461130''>representation.</span> <span m=''1462320''>And</span>
  <span m=''1462570''>you</span> <span m=''1462660''>get</span> <span m=''1462790''>your</span>
  <span m=''1462900''>crease</span> <span m=''1463140''>pattern.</span> <span m=''1463500''>You</span>
  <span m=''1463590''>hit</span> <span m=''1463770''>print.</span> <span m=''1464200''>It</span>
  <span m=''1464310''>will</span> <span m=''1464520''>print</span> <span m=''1464740''>out</span>
  <span m=''1464880''>this</span> <span m=''1465050''>part</span> <span m=''1465280''>in</span>
  <span m=''1465420''>vector</span> <span m=''1465730''>forms,</span> <span m=''1466270''>nice</span>
  <span m=''1466540''>high</span> <span m=''1466720''>resolution,</span> <span m=''1467360''>and</span>
  <span m=''1467770''>all</span> <span m=''1467930''>that.</span> <span m=''1469030''>You</span>
  <span m=''1469250''>can</span> <span m=''1469500''>make</span> <span m=''1469710''>more</span>
  <span m=''1469870''>mazes.</span> <span m=''1470420''>If</span> <span m=''1470520''>you</span>
  <span m=''1470660''>really</span> <span m=''1470900''>want</span> <span m=''1471080''>to</span>
  <span m=''1471140''>make</span> <span m=''1471320''>a</span> <span m=''1471370''>particular</span>
  <span m=''1471840''>maze,</span> <span m=''1472300''>you</span> <span m=''1472460''>can</span>
  <span m=''1472600''>fool</span> <span m=''1472810''>around</span> <span m=''1473040''>with</span>
  <span m=''1473140''>that.</span> </p><p><span m=''1475090''>And</span> <span m=''1475730''>you</span>
  <span m=''1475830''>can</span> <span m=''1475990''>also</span> <span m=''1476400''>write</span>
  <span m=''1476910''>important</span> <span m=''1477320''>messages</span> <span m=''1478000''>like</span>
  <span m=''1483750''>something</span> <span m=''1484140''>like</span> <span m=''1484320''>that.</span>
  <span m=''1486190''>And</span> <span m=''1487120''>then</span> <span m=''1487360''>you</span>
  <span m=''1487460''>get</span> <span m=''1487650''>this</span> <span m=''1487920''>3D</span>
  <span m=''1489300''>representation,</span> <span m=''1490520''>which you can</span>
  <span m=''1490700''>fold</span> <span m=''1491330''>by</span> <span m=''1491460''>this</span>
  <span m=''1491670''>simple</span> <span m=''1491960''>crease</span> <span m=''1492180''>pattern.</span>
  <span m=''1494070''>If</span> <span m=''1494560''>you</span> <span m=''1494650''>make</span>
  <span m=''1494820''>that,</span> <span m=''1495020''>one</span> <span m=''1495260''>please</span>
  <span m=''1495510''>send</span> <span m=''1495710''>it</span> <span m=''1495810''>to</span>
  <span m=''1495910''>me.</span> <span m=''1496180''>But</span> <span m=''1496430''>that</span>
  <span m=''1496570''>may</span> <span m=''1496690''>take</span> <span m=''1496930''>several</span>
  <span m=''1497860''>hours</span> <span m=''1500040''>and</span> <span m=''1500260''>use</span>
  <span m=''1500450''>a</span> <span m=''1500490''>big</span> <span m=''1500890''>sheet</span>
  <span m=''1501090''>of</span> <span m=''1501160''>paper.</span> <span m=''1503160''>I</span>
  <span m=''1503240''>mean,</span> <span m=''1503400''>you''re</span> <span m=''1503530''>only</span>
  <span m=''1503680''>shrinking</span> <span m=''1504000''>by a</span> <span m=''1504130''>constant</span>
  <span m=''1504480''>factor.</span> <span m=''1504780''>How</span> <span m=''1504930''>hard</span>
  <span m=''1505120''>could</span> <span m=''1505250''>it</span> <span m=''1505350''>be?</span>
  <span m=''1506490''>The</span> <span m=''1506620''>answer</span> <span m=''1506810''>is</span>
  <span m=''1506930''>quite</span> <span m=''1507200''>hard,</span> <span m=''1507480''>because</span>
  <span m=''1507760''>the</span> <span m=''1507850''>gadgets</span> <span m=''1508190''>interact.</span>
  <span m=''1508920''>It''s</span> <span m=''1509630''>tricky.</span> </p><p><span
  m=''1511600''>All</span> <span m=''1511680''>right,</span> <span m=''1512120''>that''s</span>
  <span m=''1512370''>maze</span> <span m=''1512610''>folding.</span> <span m=''1513730''>Any</span>
  <span m=''1513970''>questions</span> <span m=''1514370''>about</span> <span m=''1514600''>maze</span>
  <span m=''1515140''>folding</span> <span m=''1515540''>or</span> <span m=''1516530''>this</span>
  <span m=''1516700''>stuff?</span> <span m=''1516990''>I</span> <span m=''1517070''>think</span>
  <span m=''1517230''>that''s</span> <span m=''1517450''>the</span> <span m=''1517590''>end</span>
  <span m=''1517910''>of</span> <span m=''1518340''>positive</span> <span m=''1518920''>results</span>
  <span m=''1519260''>for</span> <span m=''1519380''>today.</span> <span m=''1519820''>And
  we</span> <span m=''1520220''>move</span> <span m=''1520590''>into</span> <span
  m=''1520910''>NP-hardness.</span> <span m=''1523936''>Good?</span> <span m=''1527430''>All</span>
  <span m=''1527540''>right,</span> <span m=''1527820''>well</span> <span m=''1531300''>every</span>
  <span m=''1531600''>origamist</span> <span m=''1532200''>knows,</span> <span m=''1532980''>and</span>
  <span m=''1533200''>if</span> <span m=''1533320''>you''ve</span> <span m=''1533700''>been</span>
  <span m=''1533820''>working</span> <span m=''1534120''>on a</span> <span m=''1534230''>problem</span>
  <span m=''1534570''>set,</span> <span m=''1535060''>you</span> <span m=''1535170''>should</span>
  <span m=''1535360''>know</span> <span m=''1536040''>by</span> <span m=''1536170''>now</span>
  <span m=''1536810''>origami</span> <span m=''1537310''>is</span> <span m=''1537430''>hard.</span>
  <span m=''1538980''>And</span> <span m=''1539550''>we''d</span> <span m=''1539780''>like</span>
  <span m=''1540020''>to</span> <span m=''1540300''>prove</span> <span m=''1540580''>that</span>
  <span m=''1540930''>formally.</span> <span m=''1542430''>And</span> <span m=''1543160''>because</span>
  <span m=''1543920''>we''re</span> <span m=''1544110''>computer</span> <span m=''1544450''>scientists,</span>
  <span m=''1546010''>we</span> <span m=''1546230''>like</span> <span m=''1546480''>to</span>
  <span m=''1549470''>know</span> <span m=''1549730''>what</span> <span m=''1549890''>we</span>
  <span m=''1550020''>can''t know</span> <span m=''1550290''>essentially.</span> <span
  m=''1555880''>There</span> <span m=''1556050''>are</span> <span m=''1556070''>a</span>
  <span m=''1556110''>lot</span> <span m=''1556260''>of</span> <span m=''1556330''>problems</span>
  <span m=''1556720''>where</span> <span m=''1556920''>there''s</span> <span m=''1557110''>no</span>
  <span m=''1557260''>efficient</span> <span m=''1557560''>algorithm.</span> <span
  m=''1558840''>And</span> <span m=''1559350''>instead</span> <span m=''1559650''>of</span>
  <span m=''1559710''>just</span> <span m=''1559880''>giving</span> <span m=''1560180''>up,</span>
  <span m=''1560750''>we</span> <span m=''1561010''>like</span> <span m=''1561240''>to</span>
  <span m=''1561340''>prove</span> <span m=''1561770''>that</span> <span m=''1562710''>no</span>
  <span m=''1562920''>one</span> <span m=''1563150''>can</span> <span m=''1563300''>find</span>
  <span m=''1563570''>an</span> <span m=''1563670''>efficient</span> <span m=''1564000''>algorithm.</span>
  <span m=''1564520''>Because</span> <span m=''1565040''>then</span> <span m=''1565200''>we</span>
  <span m=''1565300''>know</span> <span m=''1565490''>we''re</span> <span m=''1565600''>kind</span>
  <span m=''1565790''>of</span> <span m=''1565850''>done.</span> <span m=''1567080''>That''s</span>
  <span m=''1567360''>comforting.</span> </p><p><span m=''1569640''>And</span> <span
  m=''1571200''>NP-hardness,</span> <span m=''1571980''>let</span> <span m=''1572440''>me</span>
  <span m=''1574760''>change</span> <span m=''1575150''>this,</span> <span m=''1575540''>I</span>
  <span m=''1575640''>don''t</span> <span m=''1575680''>want</span> <span m=''1575790''>to</span>
  <span m=''1575840''>formally</span> <span m=''1576320''>define</span> <span m=''1576710''>it.</span>
  <span m=''1576790''>Because</span> <span m=''1576970''>it''s</span> <span m=''1577110''>a</span>
  <span m=''1577160''>little</span> <span m=''1577340''>bit</span> <span m=''1577500''>technical.</span>
  <span m=''1578910''>But</span> <span m=''1579240''>a</span> <span m=''1579310''>working</span>
  <span m=''1579660''>definition,</span> <span m=''1581110''>there</span> <span m=''1581260''>are</span>
  <span m=''1581280''>lots</span> <span m=''1581510''>of</span> <span m=''1581590''>working</span>
  <span m=''1581830''>definitions</span> <span m=''1582320''>that</span> <span m=''1582450''>are</span>
  <span m=''1582530''>super</span> <span m=''1582820''>easy</span> <span m=''1584040''>to</span>
  <span m=''1584130''>tell</span> <span m=''1584360''>you.</span> <span m=''1588830''>So</span>
  <span m=''1589040''>the</span> <span m=''1589200''>informal</span> <span m=''1589690''>version</span>
  <span m=''1590820''>is</span> <span m=''1591030''>that</span> <span m=''1591060''>NP-hard</span>
  <span m=''1591890''>problems</span> <span m=''1592490''>are</span> <span m=''1592650''>computationally</span>
  <span m=''1593250''>intractable</span> <span m=''1593830''>problems,</span> <span
  m=''1596700''>meaning</span> <span m=''1597620''>there''s</span> <span m=''1597830''>no</span>
  <span m=''1598310''>tractable</span> <span m=''1598780''>way,</span> <span m=''1598960''>no</span>
  <span m=''1599110''>efficient</span> <span m=''1599480''>way,</span> <span m=''1599670''>to</span>
  <span m=''1599760''>solve</span> <span m=''1600040''>it</span> <span m=''1600100''>on</span>
  <span m=''1600220''>a</span> <span m=''1600280''>computer.</span> <span m=''1601580''>But</span>
  <span m=''1601800''>what</span> <span m=''1601980''>it</span> <span m=''1602060''>really</span>
  <span m=''1602330''>means,</span> <span m=''1604250''>or</span> <span m=''1604460''>what</span>
  <span m=''1604610''>it</span> <span m=''1604670''>really</span> <span m=''1604860''>implies,</span>
  <span m=''1608130''>is</span> <span m=''1608390''>if</span> <span m=''1608520''>a</span>
  <span m=''1608640''>problem</span> <span m=''1609160''>is</span> <span m=''1609410''>NP-hard,</span>
  <span m=''1613900''>then</span> <span m=''1618500''>there''s</span> <span m=''1618670''>no</span>
  <span m=''1618830''>efficient</span> <span m=''1619150''>algorithm.</span> <span
  m=''1621240''>I</span> <span m=''1621280''>wish</span> <span m=''1621510''>we</span>
  <span m=''1621640''>could</span> <span m=''1621780''>just</span> <span m=''1621930''>say</span>
  <span m=''1622100''>that.</span> <span m=''1623316''>But</span> <span m=''1623760''>there''s</span>
  <span m=''1623970''>a</span> <span m=''1624020''>slight</span> <span m=''1624420''>catch,</span>
  <span m=''1631040''>unless</span> <span m=''1632900''>P=NP.</span> </p><p><span
  m=''1634240''>How</span> <span m=''1634400''>many</span> <span m=''1634590''>people</span>
  <span m=''1636070''>know</span> <span m=''1636240''>about</span> <span m=''1636440''>NP-hardness?</span>
  <span m=''1638700''>Well,</span> <span m=''1638860''>how</span> <span m=''1639070''>many</span>
  <span m=''1639230''>people</span> <span m=''1639410''>don''t?</span> <span m=''1641060''>Just</span>
  <span m=''1641230''>a few.</span> <span m=''1641540''>All</span> <span m=''1641640''>right,</span>
  <span m=''1641850''>I''m</span> <span m=''1641940''>going</span> <span m=''1642060''>to</span>
  <span m=''1642120''>go</span> <span m=''1642470''>relatively</span> <span m=''1642930''>quickly</span>
  <span m=''1643250''>then.</span> </p><p><span m=''1644790''>Those</span> <span m=''1645020''>who</span>
  <span m=''1645170''>haven''t</span> <span m=''1645620''>heard</span> <span m=''1645970''>NP-hardness</span>
  <span m=''1647280''>and</span> <span m=''1647650''>haven''t</span> <span m=''1647890''>heard</span>
  <span m=''1648040''>of</span> <span m=''1648140''>P=NP?</span> <span m=''1650460''>Good.</span>
  <span m=''1650890''>So</span> <span m=''1651120''>you''ve</span> <span m=''1651240''>all</span>
  <span m=''1651370''>heard</span> <span m=''1651560''>about</span> <span m=''1651900''>this</span>
  <span m=''1652090''>famous</span> <span m=''1652380''>problem.</span> <span m=''1653060''>It''s</span>
  <span m=''1653260''>almost</span> <span m=''1653650''>certainly</span> <span m=''1655430''>the</span>
  <span m=''1655610''>case</span> <span m=''1655930''>that P</span> <span m=''1656180''>does</span>
  <span m=''1656300''>not</span> <span m=''1656490''>equal</span> <span m=''1656740''>NP.</span>
  <span m=''1659380''>Pretty</span> <span m=''1659700''>much</span> <span m=''1659900''>everyone</span>
  <span m=''1660220''>believes</span> <span m=''1660520''>that,</span> <span m=''1661420''>unless</span>
  <span m=''1661570''>you</span> <span m=''1661670''>watch</span> <span m=''1661890''>my</span>
  <span m=''1662090''>April Foo;s</span> <span m=''1662510''>video</span> <span m=''1663660''>and</span>
  <span m=''1666190''>search</span> <span m=''1666440''>for</span> <span m=''1666570''>P</span>
  <span m=''1666690''>equals</span> <span m=''1666940''>NP</span> <span m=''1667880''>in</span>
  <span m=''1668160''>YouTube.</span> <span m=''1670170''>And</span> <span m=''1672310''>what</span>
  <span m=''1672550''>this</span> <span m=''1672720''>means</span> <span m=''1673120''>intuitively</span>
  <span m=''1673850''>is</span> <span m=''1674070''>that</span> <span m=''1674220''>there''s</span>
  <span m=''1674440''>no</span> <span m=''1675750''>cheating.</span> <span m=''1676440''>There''s</span>
  <span m=''1676640''>no</span> <span m=''1676830''>trick</span> <span m=''1677580''>to</span>
  <span m=''1677930''>make</span> <span m=''1678150''>lucky</span> <span m=''1678480''>guesses</span>
  <span m=''1679170''>in</span> <span m=''1679320''>life.</span> </p><p><span m=''1680400''>If</span>
  <span m=''1680480''>you''ve</span> <span m=''1680600''>got</span> <span m=''1680810''>two</span>
  <span m=''1680940''>choices</span> <span m=''1681890''>and</span> <span m=''1681960''>you</span>
  <span m=''1682030''>don''t</span> <span m=''1682180''>know</span> <span m=''1682280''>which</span>
  <span m=''1682450''>is</span> <span m=''1682530''>the</span> <span m=''1682620''>right</span>
  <span m=''1682810''>choice,</span> <span m=''1684090''>and</span> <span m=''1684230''>you''re</span>
  <span m=''1684430''>computer,</span> <span m=''1687030''>you</span> <span m=''1687170''>can''t--</span>
  <span m=''1687650''>computers</span> <span m=''1688110''>aren''t</span> <span m=''1688290''>lucky.</span>
  <span m=''1689740''>The</span> <span m=''1689830''>best</span> <span m=''1690080''>they</span>
  <span m=''1690180''>can</span> <span m=''1690330''>do</span> <span m=''1690440''>is</span>
  <span m=''1690520''>try</span> <span m=''1690710''>both</span> <span m=''1690950''>options.</span>
  <span m=''1692420''>That''s</span> <span m=''1692830''>what</span> <span m=''1693020''>P
  does not</span> <span m=''1693260''>equal</span> <span m=''1693670''>NP</span> <span
  m=''1694200''>means</span> <span m=''1694560''>basically.</span> <span m=''1694960''>There</span>
  <span m=''1695090''>are</span> <span m=''1695120''>no</span> <span m=''1695320''>lucky,</span>
  <span m=''1696030''>there''s</span> <span m=''1696200''>no</span> <span m=''1696340''>way</span>
  <span m=''1696440''>to</span> <span m=''1696510''>simulate</span> <span m=''1697050''>luckiness.</span>
  <span m=''1698090''>That''s</span> <span m=''1698310''>the</span> <span m=''1698390''>technical</span>
  <span m=''1699740''>version.</span> <span m=''1702710''>Those</span> <span m=''1702940''>who</span>
  <span m=''1702990''>know</span> <span m=''1703440''>NP</span> <span m=''1704010''>should</span>
  <span m=''1704300''>agree</span> <span m=''1704520''>with</span> <span m=''1704670''>me.</span>
  <span m=''1704810''>That</span> <span m=''1705000''>is real.</span> <span m=''1710073''>It''s</span>
  <span m=''1710530''>not how</span> <span m=''1710820''>most</span> <span m=''1711090''>people</span>
  <span m=''1711560''>explain</span> <span m=''1712010''>it.</span> <span m=''1712210''>But</span>
  <span m=''1712700''>it''s</span> <span m=''1712830''>how</span> <span m=''1712940''>I</span>
  <span m=''1713030''>like</span> <span m=''1713230''>to</span> <span m=''1713270''>think</span>
  <span m=''1713490''>about</span> <span m=''1713760''>it.</span> <span m=''1715690''>And</span>
  <span m=''1715890''>from</span> <span m=''1716020''>that</span> <span m=''1716210''>perspective,</span>
  <span m=''1716590''>it''s</span> <span m=''1716740''>kind</span> <span m=''1717030''>of</span>
  <span m=''1717120''>obvious.</span> <span m=''1718530''>But</span> <span m=''1718760''>it''s</span>
  <span m=''1718970''>very</span> <span m=''1719290''>annoying.</span> <span m=''1720380''>It''s</span>
  <span m=''1720480''>unlikely</span> <span m=''1720940''>anyone</span> <span m=''1721220''>will</span>
  <span m=''1721330''>prove</span> <span m=''1721550''>this</span> <span m=''1721980''>in</span>
  <span m=''1722160''>the</span> <span m=''1722230''>near</span> <span m=''1722410''>future,</span>
  <span m=''1725100''>says</span> <span m=''1725880''>Scott</span> <span m=''1726170''>Aaronson,</span>
  <span m=''1726540''>who</span> <span m=''1726650''>bet</span> <span m=''1726930''>$200,000</span>
  <span m=''1727900''>that</span> <span m=''1727980''>that</span> <span m=''1728130''>was</span>
  <span m=''1728260''>the</span> <span m=''1728350''>case.</span> <span m=''1731320''>Right.</span>
  </p><p><span m=''1735320''>So</span> <span m=''1735390''>you don''t</span> <span
  m=''1735640''>need</span> <span m=''1735820''>to</span> <span m=''1735930''>know</span>
  <span m=''1736130''>the</span> <span m=''1736250''>definition</span> <span m=''1736840''>of</span>
  <span m=''1736970''>NP-hardness</span> <span m=''1737430''>except</span> <span m=''1737750''>that</span>
  <span m=''1737860''>it</span> <span m=''1737980''>probably</span> <span m=''1738340''>means</span>
  <span m=''1738610''>there''s</span> <span m=''1738750''>no</span> <span m=''1738850''>efficient</span>
  <span m=''1739170''>algorithm.</span> <span m=''1741130''>For</span> <span m=''1741440''>what</span>
  <span m=''1741650''>we</span> <span m=''1741750''>need</span> <span m=''1741950''>here</span>
  <span m=''1742480''>is</span> <span m=''1742690''>this</span> <span m=''1742880''>idea</span>
  <span m=''1743170''>of</span> <span m=''1743250''>reduction,</span> <span m=''1744390''>that</span>
  <span m=''1744530''>we</span> <span m=''1744660''>can</span> <span m=''1744810''>take</span>
  <span m=''1745220''>some</span> <span m=''1746270''>hard</span> <span m=''1746590''>problem,</span>
  <span m=''1748620''>known</span> <span m=''1749160''>NP-hard</span> <span m=''1749460''>problems.</span>
  <span m=''1750150''>Why</span> <span m=''1750420''>did I</span> <span m=''1750690''>write</span>
  <span m=''1751030''>ness</span> <span m=''1751410''>there?</span> <span m=''1752690''>NP-hard</span>
  <span m=''1753270''>problems</span> <span m=''1755930''>show</span> <span m=''1756300''>that</span>
  <span m=''1756670''>a</span> <span m=''1756750''>problem</span> <span m=''1757090''>that</span>
  <span m=''1757200''>we</span> <span m=''1757320''>care</span> <span m=''1757610''>about,</span>
  <span m=''1757860''>like</span> <span m=''1758220''>origami</span> <span m=''1758440''>design,</span>
  <span m=''1759590''>is</span> <span m=''1760390''>even</span> <span m=''1760640''>harder</span>
  <span m=''1761020''>than</span> <span m=''1761170''>those</span> <span m=''1761370''>problems.</span>
  <span m=''1762360''>Therefore,</span> <span m=''1762680''>it''s</span> <span m=''1762760''>also</span>
  <span m=''1763140''>NP-hard.</span> <span m=''1764120''>That''s</span> <span m=''1764340''>the</span>
  <span m=''1764420''>usual</span> <span m=''1764700''>way</span> <span m=''1764880''>for</span>
  <span m=''1765050''>NP-hardness.</span> <span m=''1766150''>It''s</span> <span m=''1766440''>always</span>
  <span m=''1766690''>showing that</span> <span m=''1766730''>your</span> <span m=''1766920''>problem</span>
  <span m=''1767220''>is</span> <span m=''1767300''>harder</span> <span m=''1767530''>than</span>
  <span m=''1767660''>another.</span> <span m=''1768430''>Or</span> <span m=''1768660''>showing</span>
  <span m=''1768920''>that one</span> <span m=''1769150''>of</span> <span m=''1769200''>these</span>
  <span m=''1769380''>problems</span> <span m=''1769680''>is</span> <span m=''1769840''>easier</span>
  <span m=''1770220''>than</span> <span m=''1770350''>your</span> <span m=''1770520''>problem.</span>
  <span m=''1770950''>And therefore,</span> <span m=''1771330''>yours</span> <span
  m=''1771580''>is</span> <span m=''1771670''>harder.</span> </p><p><span m=''1772730''>So</span>
  <span m=''1773670''>I''m</span> <span m=''1773830''>going</span> <span m=''1773920''>to</span>
  <span m=''1774000''>need</span> <span m=''1774240''>three</span> <span m=''1774470''>problems</span>
  <span m=''1774810''>today.</span> <span m=''1775150''>I''ll</span> <span m=''1775290''>start</span>
  <span m=''1775630''>just</span> <span m=''1775800''>by</span> <span m=''1775910''>defining</span>
  <span m=''1776320''>two</span> <span m=''1776510''>of</span> <span m=''1776560''>them,</span>
  <span m=''1777153''>which</span> <span m=''1777546''>you''ve</span> <span m=''1777940''>probably</span>
  <span m=''1778320''>seen</span> <span m=''1778550''>before.</span> <span m=''1779590''>One</span>
  <span m=''1779880''>is</span> <span m=''1780750''>called</span> <span m=''1780990''>partition.</span>
  <span m=''1785100''>And</span> <span m=''1785370''>I</span> <span m=''1785430''>give</span>
  <span m=''1785670''>you</span> <span m=''1785860''>n</span> <span m=''1786130''>numbers.</span>
  <span m=''1789050''>I</span> <span m=''1789210''>want</span> <span m=''1789460''>to</span>
  <span m=''1789500''>know,</span> <span m=''1790500''>can</span> <span m=''1790740''>I</span>
  <span m=''1790820''>split</span> <span m=''1791190''>them</span> <span m=''1792370''>into</span>
  <span m=''1792950''>equal</span> <span m=''1793330''>halves?</span> <span m=''1807210''>Be
  a</span> <span m=''1807610''>little</span> <span m=''1807760''>more</span> <span
  m=''1807910''>precise.</span> <span m=''1812308''>Two</span> <span m=''1812780''>halves</span>
  <span m=''1813440''>of</span> <span m=''1813600''>equal</span> <span m=''1813950''>sum.</span>
  <span m=''1818100''>So</span> <span m=''1818310''>suppose</span> <span m=''1818730''>you''re</span>
  <span m=''1818850''>playing</span> <span m=''1819440''>video</span> <span m=''1819690''>game</span>
  <span m=''1820240''><i>Team</i></span> <span m=''1820520''><i>Deathmatch.</i></span>
  <span m=''1821340''>You''ve</span> <span m=''1821440''>got</span> <span m=''1821620''>two</span>
  <span m=''1821770''>teams.</span> <span m=''1822730''>You''ve</span> <span m=''1822830''>got</span>
  <span m=''1822980''>a</span> <span m=''1823040''>ranking</span> <span m=''1823380''>for</span>
  <span m=''1823500''>every</span> <span m=''1823670''>player.</span> <span m=''1824370''>You''d</span>
  <span m=''1824480''>like</span> <span m=''1824610''>to</span> <span m=''1824700''>divide</span>
  <span m=''1825010''>your</span> <span m=''1825120''>players</span> <span m=''1826180''>so</span>
  <span m=''1826400''>that</span> <span m=''1826680''>the</span> <span m=''1827340''>sum</span>
  <span m=''1827630''>of</span> <span m=''1827670''>the</span> <span m=''1827750''>rankings</span>
  <span m=''1828170''>on</span> <span m=''1828850''>the</span> <span m=''1828930''>red</span>
  <span m=''1829110''>side</span> <span m=''1829370''>is the</span> <span m=''1829450''>same</span>
  <span m=''1829700''>as</span> <span m=''1829800''>the</span> <span m=''1829890''>sum</span>
  <span m=''1830080''>of</span> <span m=''1830130''>the</span> <span m=''1830200''>rankings</span>
  <span m=''1830540''>on</span> <span m=''1830600''>the</span> <span m=''1830670''>blue</span>
  <span m=''1830850''>side,</span> <span m=''1831160''>so</span> <span m=''1831260''>it''s</span>
  <span m=''1831380''>an</span> <span m=''1831470''>even</span> <span m=''1832250''>game,</span>
  <span m=''1832600''>more</span> <span m=''1832760''>fun,</span> <span m=''1833090''>whatever.</span>
  <span m=''1834090''>This</span> <span m=''1834250''>problem,</span> <span m=''1834730''>sadly,</span>
  <span m=''1835120''>is</span> <span m=''1835210''>NP-hard.</span> <span m=''1835740''>There''s</span>
  <span m=''1835980''>no</span> <span m=''1836150''>way</span> <span m=''1836280''>to</span>
  <span m=''1836740''>do</span> <span m=''1836880''>that,</span> <span m=''1837400''>even</span>
  <span m=''1837610''>approximately.</span> <span m=''1840570''>The</span> <span m=''1840800''>only</span>
  <span m=''1841010''>catch</span> <span m=''1841310''>is</span> <span m=''1842020''>this</span>
  <span m=''1842160''>problem</span> <span m=''1842460''>is</span> <span m=''1842550''>hard</span>
  <span m=''1842890''>only</span> <span m=''1843140''>when</span> <span m=''1843260''>these</span>
  <span m=''1843430''>integers</span> <span m=''1843820''>are</span> <span m=''1843930''>super</span>
  <span m=''1845450''>big,</span> <span m=''1846310''>like</span> <span m=''1846530''>exponentially</span>
  <span m=''1847160''>large</span> <span m=''1847460''>in</span> <span m=''1847550''>n.</span>
  <span m=''1848330''>This</span> <span m=''1848510''>problem is</span> <span m=''1848900''>called</span>
  <span m=''1849130''>weakly</span> <span m=''1849570''>NP-hard.</span> <span m=''1852330''>So</span>
  <span m=''1852530''>as</span> <span m=''1852620''>long</span> <span m=''1852800''>as</span>
  <span m=''1852850''>your</span> <span m=''1852960''>player</span> <span m=''1853230''>rankings</span>
  <span m=''1853640''>are</span> <span m=''1853710''>nice</span> <span m=''1853970''>and</span>
  <span m=''1854080''>small,</span> <span m=''1854430''>there</span> <span m=''1854480''>actually</span>
  <span m=''1854760''>is</span> <span m=''1854880''>an</span> <span m=''1854970''>efficient</span>
  <span m=''1855340''>way</span> <span m=''1855500''>to</span> <span m=''1856290''>solve</span>
  <span m=''1856560''>that.</span> <span m=''1856730''>Problem</span> <span m=''1857560''>but</span>
  <span m=''1857770''>when</span> <span m=''1857910''>the</span> <span m=''1858000''>integers</span>
  <span m=''1858370''>are</span> <span m=''1858440''>big,</span> <span m=''1859260''>this</span>
  <span m=''1859440''>is</span> <span m=''1859690''>NP-hard.</span> </p><p><span m=''1863772''>An</span>
  <span m=''1864220''>even</span> <span m=''1864440''>nastier</span> <span m=''1864900''>problem</span>
  <span m=''1865650''>is</span> <span m=''1866030''>satisfiability,</span> <span m=''1866960''>or</span>
  <span m=''1867050''>SAT.</span> <span m=''1870880''>Here</span> <span m=''1871160''>you''re</span>
  <span m=''1871270''>given</span> <span m=''1871600''>some</span> <span m=''1871850''>Boolean</span>
  <span m=''1872200''>formula.</span> <span m=''1877310''>So</span> <span m=''1877710''>it</span>
  <span m=''1877800''>has</span> <span m=''1878100''>a</span> <span m=''1878150''>bunch</span>
  <span m=''1878410''>variables,</span> <span m=''1879140''>like</span> <span m=''1879350''>x</span>
  <span m=''1879750''>and</span> <span m=''1880150''>y.</span> <span m=''1883750''>You</span>
  <span m=''1883940''>can</span> <span m=''1884120''>do</span> <span m=''1884310''>and.</span>
  <span m=''1884910''>You</span> <span m=''1885040''>can</span> <span m=''1885200''>do</span>
  <span m=''1885420''>not.</span> <span m=''1887660''>And</span> <span m=''1887970''>you</span>
  <span m=''1888100''>can</span> <span m=''1888240''>do</span> <span m=''1888450''>or,</span>
  <span m=''1889830''>let''s</span> <span m=''1890310''>say.</span> <span m=''1890840''>That''s
  all</span> <span m=''1891060''>you</span> <span m=''1891160''>need,</span> <span
  m=''1892280''>x</span> <span m=''1892530''>and</span> <span m=''1892760''>not</span>
  <span m=''1892970''>y</span> <span m=''1893370''>or</span> <span m=''1893490''>z.</span>
  <span m=''1894500''>And</span> <span m=''1894630''>you</span> <span m=''1894720''>want</span>
  <span m=''1894870''>to</span> <span m=''1894930''>know,</span> <span m=''1895410''>can</span>
  <span m=''1895650''>I</span> <span m=''1895730''>make</span> <span m=''1896040''>that</span>
  <span m=''1896300''>formula</span> <span m=''1896720''>true?</span> <span m=''1898320''>Is</span>
  <span m=''1898640''>there</span> <span m=''1899210''>some</span> <span m=''1899400''>setting</span>
  <span m=''1900100''>to</span> <span m=''1900210''>the</span> <span m=''1900260''>variables</span>
  <span m=''1907258''>x,</span> <span m=''1907740''>y,</span> <span m=''1908130''>and</span>
  <span m=''1908250''>z,</span> <span m=''1908810''>or</span> <span m=''1908970''>in</span>
  <span m=''1909030''>general</span> <span m=''1909280''>there''s</span> <span m=''1909480''>n</span>
  <span m=''1909660''>variables,</span> <span m=''1913680''>so</span> <span m=''1913940''>that</span>
  <span m=''1914090''>the</span> <span m=''1914170''>formula is</span> <span m=''1914660''>true?</span>
  </p><p><span m=''1920300''>So</span> <span m=''1920480''>we''d</span> <span m=''1920610''>say</span>
  <span m=''1920730''>the</span> <span m=''1920830''>formula''s</span> <span m=''1921190''>satisfied.</span>
  <span m=''1923750''>And</span> <span m=''1923830''>that''s</span> <span m=''1924030''>NP-hard.</span>
  <span m=''1924740''>And</span> <span m=''1924860''>here</span> <span m=''1925000''>there''s</span>
  <span m=''1925160''>not</span> <span m=''1925320''>even</span> <span m=''1925550''>any</span>
  <span m=''1925710''>numbers</span> <span m=''1926120''>to</span> <span m=''1926220''>make</span>
  <span m=''1926400''>it</span> <span m=''1926490''>hard.</span> <span m=''1927440''>So</span>
  <span m=''1927660''>we</span> <span m=''1927760''>call</span> <span m=''1927920''>this</span>
  <span m=''1928060''>problem</span> <span m=''1928290''>strongly</span> <span m=''1928810''>NP-hard.</span>
  <span m=''1935450''>And</span> <span m=''1935860''>this</span> <span m=''1936070''>is</span>
  <span m=''1936220''>really</span> <span m=''1936400''>the</span> <span m=''1936500''>prototypical</span>
  <span m=''1937850''>hard</span> <span m=''1938170''>problem,</span> <span m=''1938620''>NP-hard</span>
  <span m=''1939040''>problem,</span> <span m=''1939450''>is</span> <span m=''1939620''>the</span>
  <span m=''1939690''>very</span> <span m=''1939920''>first</span> <span m=''1940270''>one</span>
  <span m=''1941000''>is</span> <span m=''1941120''>proved</span> <span m=''1941510''>NP-hard.</span>
  <span m=''1942780''>It''s</span> <span m=''1942950''>the</span> <span m=''1943080''>only</span>
  <span m=''1943330''>one</span> <span m=''1943610''>really</span> <span m=''1943850''>that</span>
  <span m=''1943980''>we</span> <span m=''1944280''>usually</span> <span m=''1944650''>prove</span>
  <span m=''1944950''>without</span> <span m=''1946176''>a</span> <span m=''1946550''>reduction,</span>
  <span m=''1946895''>you</span> <span m=''1947240''>could</span> <span m=''1947650''>say.</span>
  </p><p><span m=''1951730''>So</span> <span m=''1951940''>what</span> <span m=''1952080''>we''re</span>
  <span m=''1952230''>going</span> <span m=''1952330''>to</span> <span m=''1952420''>do</span>
  <span m=''1952870''>it</span> <span m=''1953980''>for</span> <span m=''1954400''>four</span>
  <span m=''1954720''>different</span> <span m=''1954990''>origami</span> <span m=''1955440''>problems</span>
  <span m=''1956610''>is</span> <span m=''1956890''>show</span> <span m=''1959520''>those</span>
  <span m=''1959740''>problems</span> <span m=''1960070''>are</span> <span m=''1960200''>easier</span>
  <span m=''1960610''>than</span> <span m=''1960760''>our</span> <span m=''1960900''>problems.</span>
  <span m=''1966220''>Therefore,</span> <span m=''1967020''>our</span> <span m=''1967150''>problems</span>
  <span m=''1967480''>are</span> <span m=''1967640''>NP-hard</span> <span m=''1967920''>also.</span>
  <span m=''1975470''>How</span> <span m=''1975700''>do</span> <span m=''1975800''>we</span>
  <span m=''1975910''>show</span> <span m=''1976380''>that,</span> <span m=''1976770''>say
  a</span> <span m=''1977230''>partition</span> <span m=''1978420''>is</span> <span
  m=''1978660''>easier</span> <span m=''1979750''>than</span> <span m=''1979900''>some</span>
  <span m=''1980090''>problem?</span> <span m=''1980970''>Well,</span> <span m=''1982170''>we</span>
  <span m=''1982350''>just</span> <span m=''1982580''>take</span> <span m=''1982790''>a</span>
  <span m=''1982870''>parti--</span> <span m=''1983340''>we</span> <span m=''1983470''>show</span>
  <span m=''1983660''>that</span> <span m=''1983810''>partition</span> <span m=''1984270''>is</span>
  <span m=''1984370''>a</span> <span m=''1984420''>special</span> <span m=''1984820''>case</span>
  <span m=''1985080''>of</span> <span m=''1985180''>our</span> <span m=''1985290''>problem.</span>
  <span m=''1986270''>It''s</span> <span m=''1986350''>a</span> <span m=''1986400''>special</span>
  <span m=''1986730''>case.</span> <span m=''1986930''>Clearly</span> <span m=''1987210''>it''s</span>
  <span m=''1987340''>easier.</span> <span m=''1988430''>So</span> <span m=''1988740''>to</span>
  <span m=''1988860''>show</span> <span m=''1989040''>that,</span> <span m=''1989250''>we</span>
  <span m=''1989420''>take</span> <span m=''1990210''>one</span> <span m=''1990430''>of</span>
  <span m=''1990470''>these</span> <span m=''1990610''>partition</span> <span m=''1991020''>problems,</span>
  <span m=''1991640''>like</span> <span m=''1991850''>n</span> <span m=''1992060''>integers.</span>
  <span m=''1992990''>We</span> <span m=''1993080''>want</span> <span m=''1993280''>to</span>
  <span m=''1993330''>know</span> <span m=''1993660''>whether</span> <span m=''1993850''>you</span>
  <span m=''1993950''>can</span> <span m=''1994100''>split</span> <span m=''1994270''>them</span>
  <span m=''1994400''>in</span> <span m=''1994530''>equal</span> <span m=''1994750''>halves.</span>
  <span m=''1995850''>I''m</span> <span m=''1995960''>going</span> <span m=''1996040''>to</span>
  <span m=''1996100''>convert</span> <span m=''1996480''>that</span> <span m=''1996640''>into</span>
  <span m=''1996820''>my</span> <span m=''1996990''>problem,</span> <span m=''1998360''>so</span>
  <span m=''1998550''>that</span> <span m=''1998700''>that</span> <span m=''1998890''>problem</span>
  <span m=''1999170''>has</span> <span m=''1999460''>a</span> <span m=''1999610''>yes</span>
  <span m=''1999940''>answer</span> <span m=''2000300''>if</span> <span m=''2000440''>and</span>
  <span m=''2000530''>only</span> <span m=''2000790''>if</span> <span m=''2001050''>the</span>
  <span m=''2001250''>partition</span> <span m=''2001660''>problem</span> <span m=''2001920''>has
  a</span> <span m=''2002180''>yes</span> <span m=''2002330''>answer.</span> <span
  m=''2002620''>Therefore,</span> <span m=''2003080''>really</span> <span m=''2003360''>this</span>
  <span m=''2003970''>problem</span> <span m=''2004220''>becomes</span> <span m=''2004580''>a</span>
  <span m=''2004660''>special</span> <span m=''2005040''>case</span> <span m=''2005920''>of</span>
  <span m=''2006030''>the</span> <span m=''2006110''>one</span> <span m=''2006260''>I</span>
  <span m=''2006310''>care</span> <span m=''2006530''>about.</span> <span m=''2006750''>Therefore,</span>
  <span m=''2007020''>that</span> <span m=''2007220''>problem</span> <span m=''2007970''>is</span>
  <span m=''2008400''>harder,</span> <span m=''2009650''>and</span> <span m=''2009860''>therefore</span>
  <span m=''2010220''>also</span> <span m=''2010540''>NP-hard.</span> </p><p><span
  m=''2013560''>So</span> <span m=''2016920''>I''m</span> <span m=''2017090''>going</span>
  <span m=''2017220''>to</span> <span m=''2017300''>start</span> <span m=''2017590''>out</span>
  <span m=''2017760''>with</span> <span m=''2017980''>a</span> <span m=''2018060''>super</span>
  <span m=''2018460''>simple</span> <span m=''2018730''>example</span> <span m=''2019590''>which</span>
  <span m=''2019810''>we</span> <span m=''2019970''>did</span> <span m=''2020730''>in</span>
  <span m=''2020870''>the</span> <span m=''2020950''>problem</span> <span m=''2021230''>session</span>
  <span m=''2021550''>on</span> <span m=''2021660''>Monday.</span> <span m=''2023730''>Someone</span>
  <span m=''2024140''>pose</span> <span m=''2024550''>this</span> <span m=''2024780''>to</span>
  <span m=''2024890''>me</span> <span m=''2025870''>after</span> <span m=''2026280''>class</span>
  <span m=''2027450''>last</span> <span m=''2027840''>week,</span> <span m=''2028100''>I</span>
  <span m=''2028170''>think.</span> <span m=''2031360''>I</span> <span m=''2031440''>think</span>
  <span m=''2031630''>two</span> <span m=''2031750''>lectures</span> <span m=''2032140''>ago.</span>
  <span m=''2034820''>So</span> <span m=''2035730''>here''s</span> <span m=''2035990''>a</span>
  <span m=''2036060''>problem.</span> <span m=''2038100''>I</span> <span m=''2038200''>give</span>
  <span m=''2038470''>you</span> <span m=''2038780''>a</span> <span m=''2039070''>single</span>
  <span m=''2039450''>vertex</span> <span m=''2040560''>hinge</span> <span m=''2040890''>pattern.</span>
  <span m=''2046670''>Someone</span> <span m=''2047090''>built</span> <span m=''2047490''>some</span>
  <span m=''2047740''>crazy</span> <span m=''2048230''>robot</span> <span m=''2048650''>with</span>
  <span m=''2048770''>some</span> <span m=''2048940''>crazy</span> <span m=''2049320''>pattern</span>
  <span m=''2049630''>of</span> <span m=''2049730''>hinges</span> <span m=''2050040''>all</span>
  <span m=''2050210''>around</span> <span m=''2050440''>a</span> <span m=''2050489''>single</span>
  <span m=''2050750''>vertex.</span> <span m=''2051810''>You</span> <span m=''2051949''>want</span>
  <span m=''2052100''>to</span> <span m=''2052150''>know,</span> <span m=''2052389''>can</span>
  <span m=''2052560''>I</span> <span m=''2052620''>make</span> <span m=''2053010''>anything</span>
  <span m=''2053560''>out</span> <span m=''2053699''>of</span> <span m=''2053810''>it?</span>
  <span m=''2056380''>Does</span> <span m=''2056650''>some</span> <span m=''2057090''>subset</span>
  <span m=''2057630''>of</span> <span m=''2057710''>those</span> <span m=''2057949''>hinges,</span>
  <span m=''2059150''>if</span> <span m=''2059219''>I</span> <span m=''2059280''>take</span>
  <span m=''2059500''>that</span> <span m=''2059650''>as</span> <span m=''2059739''>a</span>
  <span m=''2059810''>crease</span> <span m=''2060080''>pattern,</span> <span m=''2061690''>fold</span>
  <span m=''2062030''>flat?</span> <span m=''2066850''>Who</span> <span m=''2067010''>posed
  this</span> <span m=''2067389''>problem?</span> <span m=''2069310''>Anybody</span>
  <span m=''2069469''>remember?</span> <span m=''2071449''>All right.</span> <span
  m=''2071600''>Maybe he''s</span> <span m=''2071730''>not</span> <span m=''2071870''>here.</span>
  <span m=''2072980''>I</span> <span m=''2073100''>forgot,</span> <span m=''2073480''>unfortunately.</span>
  </p><p><span m=''2074900''>He</span> <span m=''2075070''>asked</span> <span m=''2075570''>me,</span>
  <span m=''2076199''>so</span> <span m=''2076440''>what</span> <span m=''2076600''>about</span>
  <span m=''2076790''>this</span> <span m=''2076940''>problem?</span> <span m=''2077929''>I
  said,</span> <span m=''2078394''>yeah it''s</span> <span m=''2078860''>obviously</span>
  <span m=''2079190''>NP-hard.</span> <span m=''2080060''>And</span> <span m=''2080190''>we</span>
  <span m=''2080300''>thought</span> <span m=''2080489''>about</span> <span m=''2080750''>it</span>
  <span m=''2080940''>for</span> <span m=''2081639''>five</span> <span m=''2081900''>minutes.</span>
  <span m=''2082520''>And</span> <span m=''2082630''>then</span> <span m=''2082860''>after</span>
  <span m=''2083120''>five</span> <span m=''2083300''>minutes,</span> <span m=''2083540''>it''s</span>
  <span m=''2083670''>obviously</span> <span m=''2084050''>NP-hard.</span> <span m=''2085446''>So</span>
  <span m=''2087780''>let</span> <span m=''2088060''>me</span> <span m=''2088500''>show</span>
  <span m=''2088760''>you</span> <span m=''2089670''>the</span> <span m=''2089830''>obvious</span>
  <span m=''2090199''>proof</span> <span m=''2090760''>once</span> <span m=''2090969''>we</span>
  <span m=''2091040''>have</span> <span m=''2091280''>it.</span> <span m=''2091420''>We''re</span>
  <span m=''2091590''>going</span> <span m=''2091840''>to</span> <span m=''2092480''>show</span>
  <span m=''2092730''>that</span> <span m=''2092860''>this</span> <span m=''2093010''>problem</span>
  <span m=''2093330''>is</span> <span m=''2093429''>harder</span> <span m=''2093719''>than</span>
  <span m=''2093889''>partition.</span> <span m=''2095070''>So</span> <span m=''2095230''>we</span>
  <span m=''2095320''>take</span> <span m=''2095530''>n</span> <span m=''2095679''>integers,</span>
  <span m=''2096710''>want</span> <span m=''2096820''>to</span> <span m=''2096860''>know</span>
  <span m=''2096980''>how</span> <span m=''2097139''>to</span> <span m=''2097270''>divide</span>
  <span m=''2097600''>them.</span> <span m=''2098430''>And</span> <span m=''2098550''>it''s</span>
  <span m=''2098680''>really</span> <span m=''2098880''>simple.</span> <span m=''2101470''>So</span>
  <span m=''2101930''>suppose</span> <span m=''2102260''>someone</span> <span m=''2102520''>gives</span>
  <span m=''2102700''>us</span> <span m=''2102820''>n</span> <span m=''2102960''>integers.</span>
  <span m=''2106820''>For</span> <span m=''2106980''>integers,</span> <span m=''2107550''>we''re</span>
  <span m=''2107730''>going</span> <span m=''2107920''>to</span> <span m=''2107990''>scale</span>
  <span m=''2108380''>them</span> <span m=''2109450''>all</span> <span m=''2109780''>by</span>
  <span m=''2109930''>the</span> <span m=''2110040''>same</span> <span m=''2110380''>scale</span>
  <span m=''2110660''>factor,</span> <span m=''2112370''>so</span> <span m=''2112700''>that</span>
  <span m=''2114280''>their</span> <span m=''2114580''>sum</span> <span m=''2115430''>equals</span>
  <span m=''2115960''>360</span> <span m=''2116690''>degrees.</span> </p><p><span
  m=''2119220''>And</span> <span m=''2119270''>now,</span> <span m=''2119670''>lo</span>
  <span m=''2119830''>and</span> <span m=''2119910''>behold,</span> <span m=''2120080''>those</span>
  <span m=''2120240''>integers</span> <span m=''2120590''>are</span> <span m=''2120760''>angles</span>
  <span m=''2121360''>in</span> <span m=''2121470''>a crease</span> <span m=''2121740''>pattern,</span>
  <span m=''2122320''>in</span> <span m=''2122450''>a</span> <span m=''2122490''>hinge</span>
  <span m=''2122740''>pattern.</span> <span m=''2123870''>So</span> <span m=''2123990''>you</span>
  <span m=''2124050''>just</span> <span m=''2124240''>take</span> <span m=''2124460''>those</span>
  <span m=''2124690''>numbers.</span> <span m=''2125690''>You</span> <span m=''2125800''>turn</span>
  <span m=''2126080''>them.</span> <span m=''2126510''>You</span> <span m=''2126640''>put</span>
  <span m=''2126840''>them</span> <span m=''2126990''>on</span> <span m=''2127200''>a</span>
  <span m=''2127260''>wheel.</span> <span m=''2131790''>OK.</span> <span m=''2132170''>Now</span>
  <span m=''2132530''>presumably,</span> <span m=''2133160''>it''s</span> <span m=''2133320''>not</span>
  <span m=''2133500''>a</span> <span m=''2133550''>flat,</span> <span m=''2133830''>foldable,</span>
  <span m=''2134640''>single</span> <span m=''2134980''>vertex</span> <span m=''2135370''>crease</span>
  <span m=''2135570''>pattern.</span> <span m=''2135840''>Otherwise,</span> <span
  m=''2136220''>the answer</span> <span m=''2136560''>would</span> <span m=''2136660''>be</span>
  <span m=''2136760''>yes.</span> <span m=''2137550''>We</span> <span m=''2137670''>want</span>
  <span m=''2137860''>to</span> <span m=''2137910''>know,</span> <span m=''2138080''>can</span>
  <span m=''2138270''>I</span> <span m=''2138340''>remove</span> <span m=''2138680''>some</span>
  <span m=''2138890''>the</span> <span m=''2138990''>creases</span> <span m=''2139380''>to</span>
  <span m=''2139480''>make</span> <span m=''2139660''>it</span> <span m=''2139750''>flat</span>
  <span m=''2139970''>foldable?</span> <span m=''2141236''>Now</span> <span m=''2141640''>if</span>
  <span m=''2141810''>you</span> <span m=''2141920''>think</span> <span m=''2142150''>about</span>
  <span m=''2143070''>Kawasaki''s</span> <span m=''2143640''>theorem,</span> <span
  m=''2144410''>the</span> <span m=''2144670''>sum,</span> <span m=''2145070''>the</span>
  <span m=''2145190''>alternating</span> <span m=''2145550''>sum</span> <span m=''2145740''>of</span>
  <span m=''2145830''>angles</span> <span m=''2146140''>equals</span> <span m=''2146410''>0.</span>
  <span m=''2147580''>Remember</span> <span m=''2147830''>how</span> <span m=''2147990''>that</span>
  <span m=''2148190''>proof worked?</span> <span m=''2148660''>We</span> <span m=''2148860''>said,</span>
  <span m=''2149160''>OK</span> <span m=''2149420''>you</span> <span m=''2149560''>follow</span>
  <span m=''2149940''>one</span> <span m=''2150110''>angle</span> <span m=''2150360''>for</span>
  <span m=''2150480''>a</span> <span m=''2150540''>while.</span> <span m=''2151260''>Then</span>
  <span m=''2151400''>you</span> <span m=''2151480''>turn.</span> <span m=''2151870''>Then</span>
  <span m=''2151990''>you</span> <span m=''2152070''>go</span> <span m=''2152190''>back.</span>
  <span m=''2152550''>And</span> <span m=''2152790''>somehow,</span> <span m=''2154160''>you</span>
  <span m=''2154260''>have</span> <span m=''2154530''>to</span> <span m=''2154640''>end</span>
  <span m=''2154890''>up</span> <span m=''2155690''>back</span> <span m=''2155900''>where
  you started.</span> <span m=''2156460''>That''s</span> <span m=''2156700''>the</span>
  <span m=''2156820''>equals</span> <span m=''2157080''>zero</span> <span m=''2157360''>part.</span>
  <span m=''2157850''>And it''s the</span> <span m=''2157940''>alternating</span>
  <span m=''2158400''>sum</span> <span m=''2158670''>part.</span> </p><p><span m=''2160280''>Now</span>
  <span m=''2160390''>in</span> <span m=''2160450''>this</span> <span m=''2160620''>case,</span>
  <span m=''2160960''>we</span> <span m=''2161090''>have</span> <span m=''2161220''>a</span>
  <span m=''2161280''>choice</span> <span m=''2161690''>at</span> <span m=''2161760''>every</span>
  <span m=''2161980''>crease.</span> <span m=''2162320''>We</span> <span m=''2162440''>could</span>
  <span m=''2162560''>include</span> <span m=''2162920''>it</span> <span m=''2163080''>or</span>
  <span m=''2163210''>not.</span> <span m=''2164540''>If</span> <span m=''2164700''>we</span>
  <span m=''2164780''>include</span> <span m=''2165100''>the</span> <span m=''2165180''>crease,</span>
  <span m=''2165480''>we</span> <span m=''2165600''>turn</span> <span m=''2165700''>around.</span>
  <span m=''2166500''>If</span> <span m=''2166700''>we</span> <span m=''2167220''>remove</span>
  <span m=''2167630''>the</span> <span m=''2167730''>crease,</span> <span m=''2168310''>we</span>
  <span m=''2168430''>keep</span> <span m=''2168610''>going</span> <span m=''2168820''>straight.</span>
  <span m=''2170310''>So</span> <span m=''2170470''>now</span> <span m=''2170650''>the</span>
  <span m=''2170750''>problem</span> <span m=''2171090''>is</span> <span m=''2171810''>I</span>
  <span m=''2171890''>give</span> <span m=''2172070''>you</span> <span m=''2172190''>all</span>
  <span m=''2172280''>these</span> <span m=''2172420''>integers.</span> <span m=''2173220''>And</span>
  <span m=''2173710''>I</span> <span m=''2173860''>can</span> <span m=''2174060''>go</span>
  <span m=''2174560''>right.</span> <span m=''2174950''>And</span> <span m=''2175060''>now</span>
  <span m=''2175180''>I</span> <span m=''2175220''>have</span> <span m=''2175330''>a</span>
  <span m=''2175380''>choice.</span> <span m=''2175820''>Do</span> <span m=''2175920''>I</span>
  <span m=''2176020''>go</span> <span m=''2176140''>right</span> <span m=''2176440''>or</span>
  <span m=''2176570''>left</span> <span m=''2177450''>by</span> <span m=''2177620''>the</span>
  <span m=''2177730''>next</span> <span m=''2178100''>integer,</span> <span m=''2178660''>theta</span>
  <span m=''2178990''>2.</span> <span m=''2179480''>There''s</span> <span m=''2179680''>theta</span>
  <span m=''2180010''>1,</span> <span m=''2180885''>theta</span> <span m=''2181290''>2.</span>
  <span m=''2182140''>Each</span> <span m=''2182360''>one,</span> <span m=''2182530''>I</span>
  <span m=''2182570''>have</span> <span m=''2182720''>a</span> <span m=''2182770''>choice.</span>
  <span m=''2183210''>Do</span> <span m=''2183230''>I</span> <span m=''2183310''>go</span>
  <span m=''2183490''>right</span> <span m=''2183700''>or</span> <span m=''2183790''>left?</span>
  <span m=''2188190''>In</span> <span m=''2188310''>the</span> <span m=''2188440''>end,</span>
  <span m=''2188710''>the</span> <span m=''2188790''>sum</span> <span m=''2189040''>must</span>
  <span m=''2189260''>equal</span> <span m=''2189460''>zero.</span> <span m=''2190610''>So</span>
  <span m=''2190780''>this</span> <span m=''2191570''>problem</span> <span m=''2192620''>is</span>
  <span m=''2192860''>the</span> <span m=''2192940''>same</span> <span m=''2193440''>problem</span>
  <span m=''2193900''>really</span> <span m=''2194630''>as</span> <span m=''2195050''>given</span>
  <span m=''2195370''>a</span> <span m=''2195420''>bunch</span> <span m=''2195710''>of</span>
  <span m=''2195800''>numbers,</span> <span m=''2197190''>can</span> <span m=''2197460''>I</span>
  <span m=''2197780''>assign</span> <span m=''2198130''>signs</span> <span m=''2198660''>of</span>
  <span m=''2198760''>plus</span> <span m=''2199210''>or</span> <span m=''2199330''>minus</span>
  <span m=''2200350''>so</span> <span m=''2200500''>that</span> <span m=''2200630''>they</span>
  <span m=''2200710''>add</span> <span m=''2200900''>up</span> <span m=''2201000''>to</span>
  <span m=''2201100''>0?</span> </p><p><span m=''2202800''>But</span> <span m=''2203410''>assigning</span>
  <span m=''2203850''>signs</span> <span m=''2204470''>of</span> <span m=''2204600''>plus</span>
  <span m=''2204880''>or</span> <span m=''2204930''>minus</span> <span m=''2205280''>so</span>
  <span m=''2205370''>they</span> <span m=''2205500''>add</span> <span m=''2205660''>up</span>
  <span m=''2205760''>to</span> <span m=''2205840''>is</span> <span m=''2206230''>the</span>
  <span m=''2206290''>same</span> <span m=''2206550''>as</span> <span m=''2206630''>saying</span>
  <span m=''2206840''>all</span> <span m=''2206940''>the</span> <span m=''2207020''>plus</span>
  <span m=''2207330''>guys</span> <span m=''2208170''>equal</span> <span m=''2208660''>all
  the</span> <span m=''2209100''>minus</span> <span m=''2209480''>guys.</span> <span
  m=''2211100''>So</span> <span m=''2212390''>really,</span> <span m=''2212650''>this</span>
  <span m=''2212910''>problem</span> <span m=''2214390''>becomes</span> <span m=''2219020''>assigning</span>
  <span m=''2222380''>pluses</span> <span m=''2223660''>and</span> <span m=''2223900''>minuses,</span>
  <span m=''2226670''>so</span> <span m=''2226910''>that</span> <span m=''2228650''>the</span>
  <span m=''2228930''>sum</span> <span m=''2229460''>with</span> <span m=''2229600''>the</span>
  <span m=''2229700''>appropriate</span> <span m=''2230150''>pluses</span> <span m=''2230520''>or</span>
  <span m=''2230580''>minuses</span> <span m=''2231160''>of</span> <span m=''2231340''>theta</span>
  <span m=''2231620''>i</span> <span m=''2231840''>is</span> <span m=''2231980''>equal</span>
  <span m=''2232220''>0.</span> <span m=''2232550''>That''s</span> <span m=''2232760''>the</span>
  <span m=''2232840''>Kawasaki</span> <span m=''2233390''>version.</span> <span m=''2235000''>But</span>
  <span m=''2235120''>that''s</span> <span m=''2235290''>the</span> <span m=''2235360''>same</span>
  <span m=''2235630''>thing</span> <span m=''2236000''>as</span> <span m=''2236100''>saying</span>
  <span m=''2236400''>the</span> <span m=''2236480''>sum</span> <span m=''2236940''>of</span>
  <span m=''2237200''>the</span> <span m=''2237300''>pluses</span> <span m=''2238550''>equals</span>
  <span m=''2239600''>the</span> <span m=''2239700''>sum</span> <span m=''2239990''>of</span>
  <span m=''2240090''>the</span> <span m=''2240170''>minuses.</span> </p><p><span
  m=''2242690''>And</span> <span m=''2243270''>if</span> <span m=''2243430''>that''s</span>
  <span m=''2243780''>the</span> <span m=''2243860''>case,</span> <span m=''2244720''>then</span>
  <span m=''2244800''>really you''ve</span> <span m=''2245000''>partitioned</span>
  <span m=''2245620''>your</span> <span m=''2245750''>numbers</span> <span m=''2246810''>into</span>
  <span m=''2247040''>two halves</span> <span m=''2247460''>of equal</span> <span
  m=''2247790''>sum.</span> <span m=''2249140''>So</span> <span m=''2249190''>this</span>
  <span m=''2249370''>is</span> <span m=''2249460''>going</span> <span m=''2249590''>to</span>
  <span m=''2249640''>be</span> <span m=''2249750''>possible</span> <span m=''2250830''>exactly</span>
  <span m=''2251410''>when</span> <span m=''2252160''>there''s</span> <span m=''2252320''>a</span>
  <span m=''2252380''>partition.</span> <span m=''2253500''>And</span> <span m=''2253710''>so</span>
  <span m=''2253850''>you''ve</span> <span m=''2254130''>converted</span> <span m=''2254630''>partition</span>
  <span m=''2255180''>into</span> <span m=''2255270''>this</span> <span m=''2255490''>problem,</span>
  <span m=''2256600''>which</span> <span m=''2256690''>means</span> <span m=''2256890''>this</span>
  <span m=''2257020''>problem</span> <span m=''2257390''>is</span> <span m=''2257500''>harder.</span>
  <span m=''2257980''>Because</span> <span m=''2258290''>it</span> <span m=''2258470''>has</span>
  <span m=''2258670''>other</span> <span m=''2258900''>situations</span> <span m=''2259510''>maybe.</span>
  <span m=''2260530''>But</span> <span m=''2260660''>you</span> <span m=''2260730''>take</span>
  <span m=''2260920''>any</span> <span m=''2261100''>partition,</span> <span m=''2261700''>and
  are</span> <span m=''2261870''>actually</span> <span m=''2262370''>pretty</span>
  <span m=''2262570''>much</span> <span m=''2262780''>identical.</span> <span m=''2263500''>But</span>
  <span m=''2265350''>partition</span> <span m=''2265770''>becomes</span> <span m=''2266040''>a</span>
  <span m=''2266090''>special</span> <span m=''2266430''>case</span> <span m=''2266660''>with</span>
  <span m=''2266720''>this</span> <span m=''2266860''>problem.</span> <span m=''2267190''>Therefore,</span>
  <span m=''2267960''>this</span> <span m=''2268110''>problem</span> <span m=''2268360''>is</span>
  <span m=''2268450''>harder,</span> <span m=''2269440''>and</span> <span m=''2269590''>therefore</span>
  <span m=''2269900''>NP-hard.</span> <span m=''2270570''>It''s</span> <span m=''2270910''>only</span>
  <span m=''2271150''>weakly</span> <span m=''2271490''>NP-hard.</span> <span m=''2272780''>But</span>
  <span m=''2273370''>that''s</span> <span m=''2273610''>a</span> <span m=''2273650''>minor</span>
  <span m=''2274850''>detail.</span> <span m=''2276260''>Clear?</span> <span m=''2278220''>All</span>
  <span m=''2278330''>right.</span> </p><p><span m=''2278830''>Now</span> <span m=''2279030''>we</span>
  <span m=''2279120''>move</span> <span m=''2279360''>on</span> <span m=''2279510''>to</span>
  <span m=''2279660''>the</span> <span m=''2281610''>more,</span> <span m=''2281945''>I</span>
  <span m=''2282280''>don''t</span> <span m=''2282710''>know,</span> <span m=''2284000''>that''s</span>
  <span m=''2284200''>a</span> <span m=''2284250''>brand</span> <span m=''2284510''>new</span>
  <span m=''2284650''>result,</span> <span m=''2285730''>and</span> <span m=''2285850''>a</span>
  <span m=''2285880''>very</span> <span m=''2286040''>simple</span> <span m=''2286340''>one.</span>
  <span m=''2289660''>Now</span> <span m=''2289820''>we</span> <span m=''2289910''>move</span>
  <span m=''2290110''>on</span> <span m=''2290230''>to</span> <span m=''2290340''>the</span>
  <span m=''2290450''>sort</span> <span m=''2290640''>of</span> <span m=''2290720''>more</span>
  <span m=''2291140''>established,</span> <span m=''2293110''>well-studied</span>
  <span m=''2293660''>problems.</span> <span m=''2296700''>The</span> <span m=''2296850''>NP-hardness</span>
  <span m=''2297110''>proofs</span> <span m=''2297530''>are</span> <span m=''2297610''>quite</span>
  <span m=''2297810''>a</span> <span m=''2297850''>bit</span> <span m=''2297970''>more</span>
  <span m=''2298130''>complicated.</span> <span m=''2298810''>But</span> <span m=''2298980''>they''re</span>
  <span m=''2299100''>still,</span> <span m=''2300160''>they all</span> <span m=''2300400''>follow</span>
  <span m=''2300690''>the</span> <span m=''2300800''>same</span> <span m=''2301130''>spirit.</span>
  <span m=''2302660''>And</span> <span m=''2302860''>they''re</span> <span m=''2303010''>a</span>
  <span m=''2303040''>lot</span> <span m=''2303180''>of</span> <span m=''2303270''>fun,</span>
  <span m=''2303470''>because</span> <span m=''2303660''>they</span> <span m=''2303750''>involve</span>
  <span m=''2304080''>gadgets.</span> <span m=''2304970''>Here</span> <span m=''2305140''>there
  aren''t</span> <span m=''2305430''>really</span> <span m=''2305650''>any</span>
  <span m=''2305810''>gadgets.</span> <span m=''2307080''>We</span> <span m=''2307220''>represented</span>
  <span m=''2307740''>an</span> <span m=''2307850''>integer</span> <span m=''2308610''>by</span>
  <span m=''2308760''>an</span> <span m=''2308870''>angle.</span> <span m=''2310080''>It''s</span>
  <span m=''2310220''>pretty</span> <span m=''2310430''>direct.</span> <span m=''2310910''>But</span>
  <span m=''2311050''>in</span> <span m=''2311140''>some</span> <span m=''2311420''>sense,</span>
  <span m=''2311630''>that''s</span> <span m=''2311860''>the</span> <span m=''2311950''>gadget.</span>
  <span m=''2312300''>And</span> <span m=''2312400''>we</span> <span m=''2312480''>just</span>
  <span m=''2312660''>used</span> <span m=''2312800''>n</span> <span m=''2312960''>of</span>
  <span m=''2313060''>them.</span> <span m=''2313890''>All</span> <span m=''2314130''>of</span>
  <span m=''2314200''>the</span> <span m=''2314340''>other</span> <span m=''2314900''>proofs</span>
  <span m=''2315250''>are</span> <span m=''2315340''>going</span> <span m=''2315460''>to</span>
  <span m=''2315510''>use</span> <span m=''2315770''>tons</span> <span m=''2316070''>of</span>
  <span m=''2316150''>gadgets.</span> <span m=''2316740''>And</span> <span m=''2316890''>they''re</span>
  <span m=''2317270''>kind</span> <span m=''2317460''>of</span> <span m=''2317540''>fun.</span>
  <span m=''2319070''>I</span> <span m=''2319180''>love</span> <span m=''2319460''>NP-hard</span>
  <span m=''2320020''>proofs.</span> <span m=''2320285''>They''re</span> <span m=''2320550''>one</span>
  <span m=''2320560''>of</span> <span m=''2320610''>my</span> <span m=''2320740''>favorite</span>
  <span m=''2321110''>things.</span> </p><p><span m=''2326630''>All right,</span>
  <span m=''2326810''>one</span> <span m=''2326990''>of</span> <span m=''2327080''>the</span>
  <span m=''2327180''>first</span> <span m=''2327520''>things</span> <span m=''2327710''>we</span>
  <span m=''2327820''>talked</span> <span m=''2328120''>about</span> <span m=''2329030''>in</span>
  <span m=''2329180''>this</span> <span m=''2329350''>class</span> <span m=''2329700''>was</span>
  <span m=''2329780''>simple</span> <span m=''2330200''>folds.</span> <span m=''2331170''>And</span>
  <span m=''2331380''>we</span> <span m=''2331620''>showed</span> <span m=''2332050''>that
  in</span> <span m=''2332250''>one</span> <span m=''2332490''>dimension,</span> <span
  m=''2332960''>if</span> <span m=''2333050''>you had</span> <span m=''2333160''>a</span>
  <span m=''2333250''>one</span> <span m=''2333390''>dimensional</span> <span m=''2333740''>piece</span>
  <span m=''2333910''>of</span> <span m=''2333980''>paper,</span> <span m=''2334650''>simple</span>
  <span m=''2334940''>folds</span> <span m=''2335180''>were</span> <span m=''2335280''>universal.</span>
  <span m=''2335880''>You</span> <span m=''2336020''>could</span> <span m=''2336180''>make</span>
  <span m=''2336760''>any</span> <span m=''2337060''>flat,</span> <span m=''2337300''>foldable</span>
  <span m=''2337700''>crease</span> <span m=''2337940''>pattern.</span> <span m=''2339060''>And</span>
  <span m=''2339510''>if</span> <span m=''2339720''>you</span> <span m=''2339890''>remember,</span>
  <span m=''2340100''>at</span> <span m=''2340200''>the</span> <span m=''2340270''>very</span>
  <span m=''2340630''>end,</span> <span m=''2341610''>we</span> <span m=''2341800''>talked</span>
  <span m=''2342190''>about</span> <span m=''2343390''>map</span> <span m=''2343680''>folding,</span>
  <span m=''2344750''>which</span> <span m=''2344950''>is</span> <span m=''2345000''>where</span>
  <span m=''2345140''>you</span> <span m=''2345190''>have</span> <span m=''2345360''>a</span>
  <span m=''2345420''>bunch</span> <span m=''2345650''>of</span> <span m=''2345740''>orthogonal</span>
  <span m=''2346340''>creases</span> <span m=''2347810''>in</span> <span m=''2349270''>a</span>
  <span m=''2349320''>rectangular</span> <span m=''2349870''>paper,</span> <span m=''2351770''>and</span>
  <span m=''2352340''>maybe</span> <span m=''2352650''>also</span> <span m=''2352870''>with</span>
  <span m=''2352960''>mountain</span> <span m=''2353230''>valley</span> <span m=''2353510''>assignment.</span>
  <span m=''2354870''>And</span> <span m=''2355060''>we</span> <span m=''2355130''>showed</span>
  <span m=''2355320''>that</span> <span m=''2355510''>this</span> <span m=''2355700''>problem</span>
  <span m=''2356180''>really</span> <span m=''2356570''>is</span> <span m=''2357970''>a</span>
  <span m=''2358060''>bunch</span> <span m=''2358390''>of</span> <span m=''2358480''>one</span>
  <span m=''2358640''>dimensional</span> <span m=''2359040''>problems.</span> <span
  m=''2359750''>And</span> <span m=''2359980''>so</span> <span m=''2360110''>if</span>
  <span m=''2360530''>we</span> <span m=''2360630''>wanted</span> <span m=''2360930''>to</span>
  <span m=''2361010''>solve</span> <span m=''2361320''>it</span> <span m=''2361390''>was</span>
  <span m=''2361510''>simple</span> <span m=''2361830''>folds,</span> <span m=''2362220''>where</span>
  <span m=''2362360''>you</span> <span m=''2362460''>only</span> <span m=''2362660''>fold</span>
  <span m=''2362980''>along a</span> <span m=''2363160''>single</span> <span m=''2363480''>line</span>
  <span m=''2363700''>at</span> <span m=''2363770''>a</span> <span m=''2363880''>time</span>
  <span m=''2364470''>by</span> <span m=''2364610''>180</span> <span m=''2365040''>degrees,</span>
  <span m=''2367000''>then</span> <span m=''2367400''>really</span> <span m=''2367660''>this</span>
  <span m=''2367850''>turned</span> <span m=''2368130''>into</span> <span m=''2368700''>a</span>
  <span m=''2368800''>one</span> <span m=''2368980''>dimensional</span> <span m=''2369360''>problem</span>
  <span m=''2369950''>in</span> <span m=''2370450''>one</span> <span m=''2370710''>dimension,</span>
  <span m=''2371200''>then</span> <span m=''2371390''>a</span> <span m=''2371440''>one</span>
  <span m=''2371570''>dimensional</span> <span m=''2371870''>problem</span> <span
  m=''2372200''>in the</span> <span m=''2372220''>other</span> <span m=''2372340''>dimension.</span>
  <span m=''2372720''>You just</span> <span m=''2372930''>kept</span> <span m=''2373140''>doing</span>
  <span m=''2373370''>that</span> <span m=''2374000''>until</span> <span m=''2374280''>either</span>
  <span m=''2374470''>you</span> <span m=''2374590''>got</span> <span m=''2374800''>stuck,</span>
  <span m=''2375190''>in</span> <span m=''2375280''>which</span> <span m=''2375460''>case</span>
  <span m=''2375710''>the</span> <span m=''2375790''>thing</span> <span m=''2376080''>was</span>
  <span m=''2376170''>not flat</span> <span m=''2376430''>foldable,</span> <span m=''2377300''>or</span>
  <span m=''2377740''>you</span> <span m=''2377850''>flat folded</span> <span m=''2378330''>it.</span>
  <span m=''2378600''>So</span> <span m=''2378760''>this</span> <span m=''2379010''>is</span>
  <span m=''2379130''>an</span> <span m=''2379180''>example</span> <span m=''2379540''>where</span>
  <span m=''2379680''>simple</span> <span m=''2380020''>folding</span> <span m=''2380900''>is</span>
  <span m=''2381140''>easy.</span> </p><p><span m=''2382290''>But</span> <span m=''2382430''>in</span>
  <span m=''2382540''>general,</span> <span m=''2383460''>deciding</span> <span m=''2383930''>whether</span>
  <span m=''2384090''>you</span> <span m=''2384200''>can</span> <span m=''2384350''>fold</span>
  <span m=''2384560''>a crease</span> <span m=''2384830''>pattern</span> <span m=''2385110''>flat</span>
  <span m=''2385420''>by</span> <span m=''2385520''>simple</span> <span m=''2385820''>folds</span>
  <span m=''2386300''>is</span> <span m=''2386550''>NP-hard.</span> <span m=''2388040''>So</span>
  <span m=''2388290''>for</span> <span m=''2388740''>this</span> <span m=''2388840''>special</span>
  <span m=''2389200''>case,</span> <span m=''2390040''>it''s</span> <span m=''2390170''>easy.</span>
  <span m=''2391100''>For</span> <span m=''2391800''>another</span> <span m=''2392110''>situation,</span>
  <span m=''2395370''>which</span> <span m=''2395530''>is</span> <span m=''2395820''>when</span>
  <span m=''2395960''>the</span> <span m=''2396050''>polygons</span> <span m=''2396550''>are</span>
  <span m=''2396610''>not</span> <span m=''2397300''>just</span> <span m=''2397490''>rectangles,</span>
  <span m=''2398170''>but</span> <span m=''2398290''>are a</span> <span m=''2398400''>little</span>
  <span m=''2398580''>more</span> <span m=''2398750''>general,</span> <span m=''2400050''>then</span>
  <span m=''2400230''>it</span> <span m=''2400310''>becomes</span> <span m=''2400620''>NP-hard.</span>
  <span m=''2404570''>So</span> <span m=''2404700''>in</span> <span m=''2404750''>general,</span>
  <span m=''2405050''>the</span> <span m=''2405140''>problem</span> <span m=''2405490''>is</span>
  <span m=''2405980''>given</span> <span m=''2406180''>a crease</span> <span m=''2406510''>pattern,</span>
  <span m=''2407690''>possibly</span> <span m=''2408150''>with</span> <span m=''2408250''>mountain</span>
  <span m=''2408500''>valley</span> <span m=''2408770''>assignments,</span> <span
  m=''2409260''>doesn''t</span> <span m=''2409490''>really</span> <span m=''2409650''>matter,</span>
  <span m=''2410770''>can it</span> <span m=''2411040''>be</span> <span m=''2411310''>folded</span>
  <span m=''2411650''>flat</span> <span m=''2413620''>by</span> <span m=''2413830''>simple</span>
  <span m=''2414210''>folds,</span> <span m=''2418290''>by</span> <span m=''2418430''>a</span>
  <span m=''2418490''>sequence</span> <span m=''2418870''>of</span> <span m=''2418940''>simple</span>
  <span m=''2419230''>folds?</span> <span m=''2420020''>Initially</span> <span m=''2420340''>we</span>
  <span m=''2420500''>thought</span> <span m=''2420760''>maybe</span> <span m=''2421030''>this</span>
  <span m=''2421210''>problem</span> <span m=''2421560''>was</span> <span m=''2421710''>polynomially</span>
  <span m=''2422270''>solvable,</span> <span m=''2422760''>because</span> <span m=''2422870''>simple</span>
  <span m=''2423160''>folds</span> <span m=''2423460''>are</span> <span m=''2423600''>so</span>
  <span m=''2423810''>damn</span> <span m=''2424020''>simple.</span> <span m=''2425610''>We</span>
  <span m=''2425740''>were</span> <span m=''2427210''>wishful,</span> <span m=''2427800''>but</span>
  <span m=''2430410''>it''s</span> <span m=''2430530''>not</span> <span m=''2430750''>true.</span>
  <span m=''2433270''>This</span> <span m=''2434030''>turns</span> <span m=''2434350''>out</span>
  <span m=''2434530''>to</span> <span m=''2434630''>be</span> <span m=''2434860''>NP-hard.</span>
  </p><p><span m=''2439870''>If</span> <span m=''2442320''>we</span> <span m=''2442400''>take</span>
  <span m=''2442630''>this</span> <span m=''2442800''>situation,</span> <span m=''2443790''>the</span>
  <span m=''2444000''>map</span> <span m=''2444470''>situation,</span> <span m=''2445820''>and</span>
  <span m=''2445970''>we</span> <span m=''2446160''>add</span> <span m=''2447470''>45</span>
  <span m=''2447970''>degree</span> <span m=''2449060''>folds,</span> <span m=''2449760''>creases,</span>
  <span m=''2452550''>so</span> <span m=''2452650''>I</span> <span m=''2452700''>just</span>
  <span m=''2452890''>add</span> <span m=''2453080''>some</span> <span m=''2453200''>things</span>
  <span m=''2454730''>like</span> <span m=''2454890''>that.</span> <span m=''2455590''>It
  looks</span> <span m=''2456160''>kind</span> <span m=''2456320''>of</span> <span
  m=''2456380''>crazy.</span> <span m=''2457275''>Got</span> <span m=''2457700''>to</span>
  <span m=''2457760''>do</span> <span m=''2457860''>some</span> <span m=''2458020''>sub</span>
  <span m=''2458400''>division.</span> <span m=''2459390''>I</span> <span m=''2459440''>just</span>
  <span m=''2459630''>add</span> <span m=''2459810''>45</span> <span m=''2460230''>degree</span>
  <span m=''2460450''>folds.</span> <span m=''2460730''>Then</span> <span m=''2460890''>this</span>
  <span m=''2461040''>problem</span> <span m=''2461270''>becomes</span> <span m=''2461590''>NP-hard.</span>
  <span m=''2462350''>So</span> <span m=''2462500''>with</span> <span m=''2462600''>orthogonal</span>
  <span m=''2463320''>creases</span> <span m=''2463750''>in</span> <span m=''2463850''>a</span>
  <span m=''2463880''>rectangle,</span> <span m=''2464700''>it''s</span> <span m=''2464820''>easy.</span>
  <span m=''2465670''>But</span> <span m=''2465910''>you</span> <span m=''2466010''>had</span>
  <span m=''2466160''>one</span> <span m=''2466300''>more</span> <span m=''2466490''>direction,</span>
  <span m=''2466900''>it''s</span> <span m=''2467030''>hard.</span> <span m=''2468500''>Another</span>
  <span m=''2468790''>version</span> <span m=''2469060''>that''s</span> <span m=''2469220''>hard.</span>
  <span m=''2469580''>If</span> <span m=''2469810''>I</span> <span m=''2469870''>keep</span>
  <span m=''2470170''>all</span> <span m=''2470320''>the</span> <span m=''2470410''>creases</span>
  <span m=''2470790''>horizontal</span> <span m=''2471230''>and</span> <span m=''2471410''>vertical</span>
  <span m=''2472710''>but</span> <span m=''2472900''>I</span> <span m=''2472990''>make</span>
  <span m=''2473510''>an</span> <span m=''2473630''>orthogonal</span> <span m=''2474220''>polygon</span>
  <span m=''2476920''>instead</span> <span m=''2477260''>of</span> <span m=''2477330''>just</span>
  <span m=''2477520''>a</span> <span m=''2477560''>rectangle,</span> <span m=''2479586''>then</span>
  <span m=''2479990''>it''s</span> <span m=''2480180''>also</span> <span m=''2480460''>NP-hard.</span>
  </p><p><span m=''2481450''>I''m</span> <span m=''2481580''>going</span> <span m=''2481660''>to</span>
  <span m=''2481710''>show</span> <span m=''2481890''>this</span> <span m=''2482080''>one</span>
  <span m=''2482200''>because</span> <span m=''2482400''>it''s</span> <span m=''2482540''>easier.</span>
  <span m=''2483540''>But</span> <span m=''2484560''>this</span> <span m=''2484810''>actually</span>
  <span m=''2485160''>just</span> <span m=''2485330''>converts.</span> <span m=''2486280''>You</span>
  <span m=''2486670''>can</span> <span m=''2486810''>set</span> <span m=''2487030''>up</span>
  <span m=''2487150''>45</span> <span m=''2487570''>degree</span> <span m=''2487810''>folds</span>
  <span m=''2488050''>so</span> <span m=''2488180''>that</span> <span m=''2488300''>you</span>
  <span m=''2488450''>are</span> <span m=''2488550''>forced</span> <span m=''2489080''>to</span>
  <span m=''2489170''>make</span> <span m=''2489400''>a</span> <span m=''2489460''>particular</span>
  <span m=''2489920''>orthogonal</span> <span m=''2490290''>polygon</span> <span m=''2490740''>to</span>
  <span m=''2490790''>get</span> <span m=''2490940''>started.</span> <span m=''2491890''>And</span>
  <span m=''2491970''>then</span> <span m=''2492140''>it''s</span> <span m=''2492300''>the</span>
  <span m=''2492350''>same</span> <span m=''2492580''>proof.</span> <span m=''2493770''>So</span>
  <span m=''2494170''>I</span> <span m=''2494340''>think</span> <span m=''2494570''>I</span>
  <span m=''2494610''>have the</span> <span m=''2494990''>proof</span> <span m=''2495270''>here.</span>
  <span m=''2499070''>So</span> <span m=''2499280''>again,</span> <span m=''2499950''>we''re</span>
  <span m=''2500040''>going</span> <span m=''2500290''>to</span> <span m=''2500580''>reduce</span>
  <span m=''2500950''>from</span> <span m=''2501130''>partition.</span> <span m=''2502860''>So</span>
  <span m=''2503050''>we''re</span> <span m=''2503200''>given</span> <span m=''2503470''>n</span>
  <span m=''2503690''>integers.</span> <span m=''2504730''>We</span> <span m=''2504830''>want</span>
  <span m=''2504940''>to</span> <span m=''2504980''>know</span> <span m=''2505150''>whether</span>
  <span m=''2505340''>we</span> <span m=''2505460''>can</span> <span m=''2505590''>divide</span>
  <span m=''2505910''>them</span> <span m=''2506500''>into</span> <span m=''2506860''>equal</span>
  <span m=''2507230''>summing</span> <span m=''2507570''>halves.</span> <span m=''2508680''>And</span>
  <span m=''2508850''>we''re</span> <span m=''2508960''>going</span> <span m=''2509040''>to</span>
  <span m=''2509120''>represent</span> <span m=''2509610''>those</span> <span m=''2509770''>integers</span>
  <span m=''2510360''>by</span> <span m=''2511340''>these</span> <span m=''2511650''>lengths.</span>
  </p><p><span m=''2513240''>So</span> <span m=''2513410''>here''s</span> <span m=''2514330''>an,</span>
  <span m=''2515490''>then</span> <span m=''2516350''>a3,</span> <span m=''2517106''>and</span>
  <span m=''2517472''>a2,</span> <span m=''2517840''>and a1.</span> <span m=''2518380''>So</span>
  <span m=''2518560''>the</span> <span m=''2519080''>lengths</span> <span m=''2519930''>in</span>
  <span m=''2520020''>the</span> <span m=''2520110''>top</span> <span m=''2520400''>part</span>
  <span m=''2520580''>of</span> <span m=''2520660''>the</span> <span m=''2520730''>staircase</span>
  <span m=''2522020''>are</span> <span m=''2522770''>integers.</span> <span m=''2524580''>We</span>
  <span m=''2524630''>want</span> <span m=''2524790''>to</span> <span m=''2524840''>somehow</span>
  <span m=''2525120''>divide</span> <span m=''2525390''>those into</span> <span m=''2525640''>equal</span>
  <span m=''2525900''>halves.</span> <span m=''2526410''>And</span> <span m=''2526950''>when</span>
  <span m=''2527140''>they</span> <span m=''2527220''>have</span> <span m=''2528610''>two
  halves,</span> <span m=''2529450''>and</span> <span m=''2529620''>I</span> <span
  m=''2529650''>suppose</span> <span m=''2530060''>at</span> <span m=''2530140''>their</span>
  <span m=''2530260''>sum</span> <span m=''2531050''>is</span> <span m=''2531290''>L,</span>
  <span m=''2531790''>capital</span> <span m=''2532260''>L.</span> <span m=''2533030''>I</span>
  <span m=''2533130''>can</span> <span m=''2533260''>just</span> <span m=''2533420''>add</span>
  <span m=''2533600''>them</span> <span m=''2533730''>all</span> <span m=''2533880''>up.</span>
  <span m=''2534120''>I should</span> <span m=''2534290''>get</span> <span m=''2534500''>2L.</span>
  <span m=''2535020''>I</span> <span m=''2535260''>divide</span> <span m=''2535520''>by</span>
  <span m=''2535630''>2,</span> <span m=''2535860''>I</span> <span m=''2536100''>could
  get</span> <span m=''2536290''>what</span> <span m=''2536430''>the</span> <span
  m=''2536520''>target</span> <span m=''2536900''>sum is.</span> <span m=''2537350''>So
  I</span> <span m=''2537460''>know</span> <span m=''2538100''>ahead</span> <span
  m=''2538280''>of</span> <span m=''2538350''>time</span> <span m=''2538530''>without</span>
  <span m=''2538860''>solving</span> <span m=''2539160''>the</span> <span m=''2539250''>partition</span>
  <span m=''2539650''>problem</span> <span m=''2540240''>what</span> <span m=''2540510''>L</span>
  <span m=''2540710''>ought</span> <span m=''2540940''>to</span> <span m=''2541040''>be,</span>
  <span m=''2541590''>and</span> <span m=''2541740''>what</span> <span m=''2541940''>twice</span>
  <span m=''2542210''>L</span> <span m=''2542470''>ought</span> <span m=''2542730''>to</span>
  <span m=''2542870''>be.</span> </p><p><span m=''2544000''>And</span> <span m=''2544150''>then</span>
  <span m=''2544280''>I</span> <span m=''2544340''>build</span> <span m=''2544570''>this</span>
  <span m=''2544730''>frame</span> <span m=''2545150''>over</span> <span m=''2545370''>on</span>
  <span m=''2545450''>the</span> <span m=''2545550''>right</span> <span m=''2546230''>whose</span>
  <span m=''2546410''>height</span> <span m=''2546710''>is</span> <span m=''2546860''>exactly</span>
  <span m=''2547500''>twice</span> <span m=''2547950''>L.</span> <span m=''2549990''>And</span>
  <span m=''2551390''>so</span> <span m=''2551620''>there''s</span> <span m=''2551880''>these</span>
  <span m=''2552160''>creases</span> <span m=''2552660''>in</span> <span m=''2553360''>the</span>
  <span m=''2553970''>horizontal</span> <span m=''2554470''>creases</span> <span m=''2554960''>down</span>
  <span m=''2555170''>the</span> <span m=''2555240''>staircase.</span> <span m=''2557100''>All</span>
  <span m=''2557280''>these</span> <span m=''2557440''>creases</span> <span m=''2557720''>have</span>
  <span m=''2557880''>to</span> <span m=''2557960''>get</span> <span m=''2558100''>folded</span>
  <span m=''2558400''>eventually,</span> <span m=''2558850''>and by</span> <span m=''2559020''>simple</span>
  <span m=''2559370''>folds.</span> <span m=''2560870''>And</span> <span m=''2560950''>then</span>
  <span m=''2561070''>there''s</span> <span m=''2561230''>also</span> <span m=''2561680''>these</span>
  <span m=''2561890''>two</span> <span m=''2562120''>vertical</span> <span m=''2562590''>creases</span>
  <span m=''2564540''>bounding the</span> <span m=''2565040''>frame.</span> <span
  m=''2566750''>So</span> <span m=''2566880''>the</span> <span m=''2567010''>idea</span>
  <span m=''2567250''>is,</span> <span m=''2567420''>well</span> <span m=''2567540''>you</span>
  <span m=''2567670''>make</span> <span m=''2567900''>some</span> <span m=''2568220''>of</span>
  <span m=''2568330''>the</span> <span m=''2568420''>horizontal</span> <span m=''2568880''>creases.</span>
  <span m=''2570240''>Then</span> <span m=''2570510''>you</span> <span m=''2570650''>fold</span>
  <span m=''2571260''>one</span> <span m=''2571550''>of</span> <span m=''2571670''>those</span>
  <span m=''2571950''>horizontal</span> <span m=''2572420''>creases.</span> <span
  m=''2572990''>And</span> <span m=''2573120''>then</span> <span m=''2573250''>eventually</span>
  <span m=''2573670''>you have to</span> <span m=''2573740''>fold--</span> <span m=''2574100''>I''m
  sorry,</span> <span m=''2574540''>one</span> <span m=''2574590''>of</span> <span
  m=''2574640''>those</span> <span m=''2574810''>vertical</span> <span m=''2575200''>creases.</span>
  <span m=''2575600''>I</span> <span m=''2575690''>always</span> <span m=''2575850''>get</span>
  <span m=''2575980''>horizontal</span> <span m=''2576410''>and</span> <span m=''2576490''>vertical</span>
  <span m=''2576890''>confused,</span> <span m=''2577380''>which</span> <span m=''2577560''>causes</span>
  <span m=''2577840''>me</span> <span m=''2577960''>great</span> <span m=''2578160''>difficulty</span>
  <span m=''2578610''>when</span> <span m=''2578700''>trying</span> <span m=''2578990''>to</span>
  <span m=''2579060''>sleep.</span> </p><p><span m=''2580100''>But</span> <span m=''2583000''>so</span>
  <span m=''2584250''>when</span> <span m=''2584410''>I</span> <span m=''2584490''>fold</span>
  <span m=''2584680''>the</span> <span m=''2584790''>first</span> <span m=''2585390''>vertical</span>
  <span m=''2585790''>crease,</span> <span m=''2586430''>whatever''s</span> <span
  m=''2586860''>over</span> <span m=''2587050''>here</span> <span m=''2587330''>comes</span>
  <span m=''2587670''>over</span> <span m=''2587890''>here.</span> <span m=''2588550''>If</span>
  <span m=''2588730''>it</span> <span m=''2588840''>hits</span> <span m=''2589090''>the</span>
  <span m=''2589190''>frame,</span> <span m=''2590000''>I''m</span> <span m=''2590220''>in</span>
  <span m=''2590310''>big</span> <span m=''2590520''>trouble.</span> <span m=''2591580''>Because</span>
  <span m=''2591900''>then</span> <span m=''2592000''>how</span> <span m=''2592290''>am
  I</span> <span m=''2592510''>going</span> <span m=''2592610''>to</span> <span m=''2592650''>fold</span>
  <span m=''2593220''>the</span> <span m=''2593390''>other</span> <span m=''2593650''>horizontal,</span>
  <span m=''2594550''>other</span> <span m=''2594710''>vertical</span> <span m=''2595160''>crease</span>
  <span m=''2596070''>without</span> <span m=''2598750''>colliding</span> <span m=''2599700''>with</span>
  <span m=''2599880''>the</span> <span m=''2599950''>frame?</span> <span m=''2600890''>If</span>
  <span m=''2601000''>I</span> <span m=''2601050''>want</span> <span m=''2601230''>to</span>
  <span m=''2601280''>avoid</span> <span m=''2601550''>collision</span> <span m=''2601840''>with</span>
  <span m=''2601940''>the</span> <span m=''2602020''>frame</span> <span m=''2602510''>by</span>
  <span m=''2602660''>simple</span> <span m=''2603050''>folds,</span> <span m=''2603630''>and</span>
  <span m=''2603710''>I fold</span> <span m=''2603950''>the</span> <span m=''2604010''>vertical</span>
  <span m=''2604350''>crease,</span> <span m=''2604630''>I</span> <span m=''2604710''>really</span>
  <span m=''2605010''>should</span> <span m=''2605220''>not</span> <span m=''2605440''>be</span>
  <span m=''2605550''>touching</span> <span m=''2605900''>the</span> <span m=''2605970''>frame.</span>
  <span m=''2607102''>So</span> <span m=''2607460''>you</span> <span m=''2607540''>try</span>
  <span m=''2607720''>to</span> <span m=''2607800''>fold</span> <span m=''2608020''>through</span>
  <span m=''2608290''>it.</span> <span m=''2608370''>They''re</span> <span m=''2608450''>both</span>
  <span m=''2608680''>valleys</span> <span m=''2610400''>in</span> <span m=''2610440''>this</span>
  <span m=''2610620''>case.</span> <span m=''2611060''>It</span> <span m=''2611160''>doesn''t</span>
  <span m=''2611390''>matter</span> <span m=''2611730''>too</span> <span m=''2611870''>much.</span>
  </p><p><span m=''2613590''>So</span> <span m=''2613780''>what</span> <span m=''2613900''>I</span>
  <span m=''2613960''>really</span> <span m=''2614260''>need</span> <span m=''2614420''>to</span>
  <span m=''2614510''>do</span> <span m=''2614710''>is</span> <span m=''2614890''>fold</span>
  <span m=''2615170''>this</span> <span m=''2615340''>thing</span> <span m=''2615510''>compactly</span>
  <span m=''2617130''>like</span> <span m=''2617350''>this,</span> <span m=''2618390''>so</span>
  <span m=''2618570''>that</span> <span m=''2618690''>it</span> <span m=''2618830''>just</span>
  <span m=''2619170''>fits</span> <span m=''2619380''>inside</span> <span m=''2619770''>the</span>
  <span m=''2619830''>frame.</span> <span m=''2621630''>And</span> <span m=''2621790''>the</span>
  <span m=''2621970''>only</span> <span m=''2622290''>way</span> <span m=''2622470''>to</span>
  <span m=''2622570''>do</span> <span m=''2622750''>that</span> <span m=''2623070''>is</span>
  <span m=''2623240''>for</span> <span m=''2623360''>each</span> <span m=''2623610''>of</span>
  <span m=''2623700''>those</span> <span m=''2624560''>vertical</span> <span m=''2625000''>segments</span>
  <span m=''2625390''>of</span> <span m=''2625460''>the</span> <span m=''2625550''>staircase</span>
  <span m=''2626050''>to</span> <span m=''2626130''>decide</span> <span m=''2626610''>should</span>
  <span m=''2626810''>it</span> <span m=''2626880''>go</span> <span m=''2627030''>up,</span>
  <span m=''2627280''>or</span> <span m=''2627380''>should</span> <span m=''2627550''>it</span>
  <span m=''2627620''>go</span> <span m=''2627730''>down?</span> <span m=''2628810''>And</span>
  <span m=''2629020''>you</span> <span m=''2629160''>do</span> <span m=''2629300''>that</span>
  <span m=''2629520''>in</span> <span m=''2629750''>actually</span> <span m=''2630080''>pretty</span>
  <span m=''2630310''>much</span> <span m=''2630530''>the</span> <span m=''2630610''>same</span>
  <span m=''2630910''>way</span> <span m=''2631100''>this</span> <span m=''2631370''>proof</span>
  <span m=''2631700''>works.</span> <span m=''2633290''>For</span> <span m=''2633580''>each</span>
  <span m=''2633820''>of</span> <span m=''2633900''>these</span> <span m=''2634080''>segments</span>
  <span m=''2634510''>here,</span> <span m=''2634690''>we were</span> <span m=''2634840''>deciding</span>
  <span m=''2635280''>should</span> <span m=''2635490''>I</span> <span m=''2635550''>keep</span>
  <span m=''2635780''>going</span> <span m=''2636020''>straight</span> <span m=''2636480''>and</span>
  <span m=''2636670''>go,</span> <span m=''2637950''>or</span> <span m=''2638180''>should</span>
  <span m=''2638340''>I</span> <span m=''2638400''>turn</span> <span m=''2638620''>around?</span>
  </p><p><span m=''2639790''>Over</span> <span m=''2640000''>here,</span> <span m=''2640260''>it''s</span>
  <span m=''2640390''>the</span> <span m=''2640450''>same</span> <span m=''2640700''>deal.</span>
  <span m=''2641190''>I</span> <span m=''2641520''>either</span> <span m=''2641860''>keep</span>
  <span m=''2642050''>going</span> <span m=''2643030''>straight,</span> <span m=''2643610''>whichever</span>
  <span m=''2644060''>direction</span> <span m=''2644460''>I was</span> <span m=''2644550''>going,</span>
  <span m=''2644840''>up</span> <span m=''2644970''>or</span> <span m=''2645050''>down,</span>
  <span m=''2645350''>or I</span> <span m=''2645570''>turn</span> <span m=''2645800''>around.</span>
  <span m=''2646090''>But I</span> <span m=''2646290''>always</span> <span m=''2646470''>have</span>
  <span m=''2646610''>a</span> <span m=''2646670''>choice</span> <span m=''2647000''>at</span>
  <span m=''2647080''>every</span> <span m=''2647350''>crease.</span> <span m=''2647820''>I''ll</span>
  <span m=''2648190''>just</span> <span m=''2648330''>fold</span> <span m=''2648570''>it</span>
  <span m=''2648630''>or</span> <span m=''2648710''>not</span> <span m=''2649020''>to</span>
  <span m=''2649120''>make</span> <span m=''2649290''>it</span> <span m=''2649360''>go</span>
  <span m=''2649480''>up</span> <span m=''2649620''>or</span> <span m=''2649680''>down</span>
  <span m=''2649870''>how</span> <span m=''2650080''>I</span> <span m=''2650150''>want.</span>
  <span m=''2650690''>The</span> <span m=''2650850''>up</span> <span m=''2651070''>guys</span>
  <span m=''2651390''>are</span> <span m=''2651450''>going</span> <span m=''2651570''>to</span>
  <span m=''2651620''>be</span> <span m=''2651740''>one</span> <span m=''2652000''>of</span>
  <span m=''2652110''>the</span> <span m=''2652180''>halves.</span> <span m=''2652700''>And</span>
  <span m=''2652790''>the</span> <span m=''2652880''>down</span> <span m=''2653140''>guys</span>
  <span m=''2653390''>are</span> <span m=''2653440''>going</span> <span m=''2653560''>to</span>
  <span m=''2653610''>be</span> <span m=''2653710''>the</span> <span m=''2653840''>other</span>
  <span m=''2654030''>halves.</span> <span m=''2654480''>Here,</span> <span m=''2655130''>it''s</span>
  <span m=''2655310''>the</span> <span m=''2655430''>other</span> <span m=''2655600''>side</span>
  <span m=''2655860''>of</span> <span m=''2655920''>the</span> <span m=''2656010''>paper,</span>
  <span m=''2656380''>the</span> <span m=''2656520''>dark</span> <span m=''2656810''>blue</span>
  <span m=''2657000''>versus</span> <span m=''2657280''>the</span> <span m=''2657380''>light</span>
  <span m=''2657860''>blue.</span> <span m=''2658920''>As</span> <span m=''2659050''>long</span>
  <span m=''2659410''>as</span> <span m=''2659510''>those</span> <span m=''2659770''>numbers</span>
  <span m=''2660210''>add</span> <span m=''2660440''>up</span> <span m=''2660590''>to</span>
  <span m=''2660720''>exactly</span> <span m=''2661770''>L,</span> <span m=''2664400''>I''ve</span>
  <span m=''2664550''>got</span> <span m=''2664750''>this</span> <span m=''2664970''>twice.</span>
  <span m=''2665610''>Then</span> <span m=''2667590''>I</span> <span m=''2667720''>start</span>
  <span m=''2669260''>here</span> <span m=''2671210''>at</span> <span m=''2671390''>the</span>
  <span m=''2671460''>middle</span> <span m=''2672090''>of</span> <span m=''2672310''>the</span>
  <span m=''2672380''>frame.</span> <span m=''2673480''>If</span> <span m=''2673670''>I</span>
  <span m=''2673860''>can</span> <span m=''2674060''>get</span> <span m=''2674230''>them</span>
  <span m=''2674350''>to</span> <span m=''2674430''>balance</span> <span m=''2674830''>out,</span>
  <span m=''2675290''>I</span> <span m=''2675420''>will</span> <span m=''2675610''>end</span>
  <span m=''2677020''>over</span> <span m=''2677260''>here,</span> <span m=''2678410''>also</span>
  <span m=''2678740''>at</span> <span m=''2678860''>the</span> <span m=''2678940''>middle.</span>
  <span m=''2680700''>And</span> <span m=''2680860''>then</span> <span m=''2680990''>I</span>
  <span m=''2681040''>go</span> <span m=''2681220''>up</span> <span m=''2681410''>by</span>
  <span m=''2681540''>L.</span> <span m=''2681930''>And then I</span> <span m=''2682010''>go</span>
  <span m=''2682120''>down</span> <span m=''2682390''>by</span> <span m=''2682500''>2L.</span>
  <span m=''2683830''>And</span> <span m=''2683930''>that</span> <span m=''2684070''>will</span>
  <span m=''2684190''>just</span> <span m=''2684640''>fit</span> <span m=''2684770''>inside</span>
  <span m=''2685120''>the</span> <span m=''2685190''>frame.</span> <span m=''2686840''>But</span>
  <span m=''2687040''>only</span> <span m=''2687350''>if</span> <span m=''2687470''>I</span>
  <span m=''2687550''>stay</span> <span m=''2687890''>in</span> <span m=''2688020''>the</span>
  <span m=''2688090''>middle</span> <span m=''2688950''>will</span> <span m=''2689230''>that</span>
  <span m=''2689480''>2L</span> <span m=''2689680''>fit</span> <span m=''2690100''>inside</span>
  <span m=''2690390''>the</span> <span m=''2690460''>frame.</span> <span m=''2691456''>And</span>
  <span m=''2691800''>so</span> <span m=''2691960''>the</span> <span m=''2692190''>only</span>
  <span m=''2692500''>way</span> <span m=''2692750''>for</span> <span m=''2692970''>these</span>
  <span m=''2693260''>two</span> <span m=''2693410''>creases</span> <span m=''2693810''>to</span>
  <span m=''2693930''>be</span> <span m=''2694090''>foldable</span> <span m=''2695150''>and</span>
  <span m=''2695320''>not</span> <span m=''2695600''>collide</span> <span m=''2695920''>with</span>
  <span m=''2696040''>the</span> <span m=''2696110''>frame</span> <span m=''2696550''>is</span>
  <span m=''2696890''>if</span> <span m=''2697030''>I</span> <span m=''2697110''>can</span>
  <span m=''2697480''>solve the</span> <span m=''2697560''>partition</span> <span
  m=''2697990''>problem.</span> </p><p><span m=''2699560''>Therefore,</span> <span
  m=''2700500''>so</span> <span m=''2701040''>finding</span> <span m=''2701500''>simple</span>
  <span m=''2701800''>fold</span> <span m=''2702010''>sequences</span> <span m=''2702320''>is</span>
  <span m=''2702480''>actually</span> <span m=''2702740''>way</span> <span m=''2702960''>harder</span>
  <span m=''2703470''>than</span> <span m=''2703720''>partition</span> <span m=''2704250''>in</span>
  <span m=''2704370''>some</span> <span m=''2704540''>sense.</span> <span m=''2705390''>Because</span>
  <span m=''2705540''>this</span> <span m=''2705690''>is</span> <span m=''2705800''>just</span>
  <span m=''2705970''>a</span> <span m=''2706010''>very</span> <span m=''2706460''>specific</span>
  <span m=''2707100''>kind</span> <span m=''2707330''>of</span> <span m=''2707410''>map,</span>
  <span m=''2708130''>specific</span> <span m=''2708660''>kind</span> <span m=''2708810''>of</span>
  <span m=''2708890''>crease</span> <span m=''2709100''>pattern</span> <span m=''2709300''>you</span>
  <span m=''2709350''>might</span> <span m=''2709660''>want</span> <span m=''2709800''>to</span>
  <span m=''2709850''>fold.</span> <span m=''2710290''>And</span> <span m=''2710790''>folding</span>
  <span m=''2711150''>that</span> <span m=''2712270''>is</span> <span m=''2712480''>exactly</span>
  <span m=''2713490''>partition.</span> <span m=''2714120''>So</span> <span m=''2714310''>the</span>
  <span m=''2714430''>general</span> <span m=''2715470''>simple</span> <span m=''2715750''>foldability</span>
  <span m=''2716260''>problem</span> <span m=''2716570''>is</span> <span m=''2716690''>going</span>
  <span m=''2716820''>to</span> <span m=''2716910''>be</span> <span m=''2717200''>NP-hard,</span>
  <span m=''2717710''>because</span> <span m=''2717890''>it</span> <span m=''2717970''>includes</span>
  <span m=''2719010''>partition</span> <span m=''2719420''>as</span> <span m=''2719540''>a</span>
  <span m=''2719590''>special</span> <span m=''2719920''>case.</span> <span m=''2721810''>Clear?</span>
  <span m=''2725460''>Good.</span> <span m=''2728300''>That''s</span> <span m=''2728510''>our</span>
  <span m=''2728670''>easiest</span> <span m=''2730190''>proof</span> <span m=''2730610''>among</span>
  <span m=''2731130''>the</span> <span m=''2731230''>next</span> <span m=''2731620''>three.</span>
  <span m=''2733130''>Going</span> <span m=''2733260''>to</span> <span m=''2733310''>get</span>
  <span m=''2733950''>increasingly</span> <span m=''2734510''>difficult,</span> <span
  m=''2734950''>I</span> <span m=''2735000''>guess.</span> <span m=''2735850''>But</span>
  <span m=''2736210''>I''ll</span> <span m=''2736410''>just</span> <span m=''2736560''>getting</span>
  <span m=''2736750''>increasingly</span> <span m=''2737180''>sketchy,</span> <span
  m=''2738130''>so it will</span> <span m=''2738280''>be</span> <span m=''2738820''>easy</span>
  <span m=''2739840''>for</span> <span m=''2740040''>me.</span> <span m=''2744310''>I
  mean,</span> <span m=''2744430''>the</span> <span m=''2744530''>more</span> <span
  m=''2744900''>complicated</span> <span m=''2745190''>a</span> <span m=''2745480''>proof</span>
  <span m=''2745690''>gets,</span> <span m=''2745960''>somehow</span> <span m=''2748470''>I</span>
  <span m=''2748650''>feel</span> <span m=''2748810''>like</span> <span m=''2748930''>the</span>
  <span m=''2749020''>number</span> <span m=''2749310''>of</span> <span m=''2749380''>interesting</span>
  <span m=''2749790''>details</span> <span m=''2750160''>in</span> <span m=''2750230''>a</span>
  <span m=''2750280''>proof</span> <span m=''2750550''>remains</span> <span m=''2750850''>constant.</span>
  <span m=''2751536''>If</span> <span m=''2751880''>the</span> <span m=''2752000''>proof</span>
  <span m=''2752210''>gets</span> <span m=''2752390''>more</span> <span m=''2752550''>complicated,</span>
  <span m=''2752905''>then</span> <span m=''2753260''>I</span> <span m=''2753830''>throw</span>
  <span m=''2754110''>away</span> <span m=''2754280''>more</span> <span m=''2754610''>of</span>
  <span m=''2754740''>the</span> <span m=''2755490''>messy</span> <span m=''2755780''>details.</span>
  </p><p><span m=''2781030''>All</span> <span m=''2781570''>right,</span> <span m=''2784862''>the</span>
  <span m=''2785300''>next</span> <span m=''2785660''>theorem</span> <span m=''2789920''>is</span>
  <span m=''2790030''>also</span> <span m=''2790360''>about</span> <span m=''2790650''>flat</span>
  <span m=''2791100''>foldability.</span> <span m=''2793990''>But</span> <span m=''2794250''>now</span>
  <span m=''2794590''>I</span> <span m=''2794740''>don''t</span> <span m=''2794950''>just</span>
  <span m=''2795140''>care</span> <span m=''2795340''>about</span> <span m=''2795590''>simple</span>
  <span m=''2795870''>folds,</span> <span m=''2800260''>I</span> <span m=''2800500''>want</span>
  <span m=''2800720''>to</span> <span m=''2800780''>look</span> <span m=''2801010''>at</span>
  <span m=''2802320''>regular</span> <span m=''2803050''>origami</span> <span m=''2803510''>folds,</span>
  <span m=''2803960''>which</span> <span m=''2804170''>are</span> <span m=''2804310''>folded</span>
  <span m=''2804730''>states.</span> <span m=''2806350''>So</span> <span m=''2807240''>we</span>
  <span m=''2807820''>talked</span> <span m=''2808440''>a</span> <span m=''2808800''>couple</span>
  <span m=''2809050''>lectures</span> <span m=''2809590''>ago</span> <span m=''2809900''>about</span>
  <span m=''2810160''>local</span> <span m=''2810480''>foldability,</span> <span m=''2811160''>which</span>
  <span m=''2811320''>was</span> <span m=''2812110''>can</span> <span m=''2812370''>we</span>
  <span m=''2812630''>assign</span> <span m=''2813070''>mountains</span> <span m=''2813350''>and</span>
  <span m=''2813450''>valleys</span> <span m=''2813900''>to</span> <span m=''2814010''>some</span>
  <span m=''2814200''>crease</span> <span m=''2814440''>pattern</span> <span m=''2815070''>so</span>
  <span m=''2815230''>that</span> <span m=''2815770''>each</span> <span m=''2815990''>vertex,</span>
  <span m=''2816450''>if</span> <span m=''2816570''>you</span> <span m=''2816710''>cut</span>
  <span m=''2816970''>it</span> <span m=''2817070''>out</span> <span m=''2817310''>into
  a</span> <span m=''2817540''>little</span> <span m=''2817780''>disk,</span> <span
  m=''2818500''>would</span> <span m=''2818730''>by</span> <span m=''2818890''>itself</span>
  <span m=''2819280''>fold</span> <span m=''2819480''>flat.</span> <span m=''2820350''>And</span>
  <span m=''2820500''>that</span> <span m=''2820670''>was</span> <span m=''2820940''>easy,</span>
  <span m=''2822040''>polynomially</span> <span m=''2822610''>solvable,</span> <span
  m=''2823560''>actually</span> <span m=''2823770''>linear</span> <span m=''2824050''>time.</span>
  <span m=''2825120''>And</span> <span m=''2825340''>that</span> <span m=''2825460''>was</span>
  <span m=''2825590''>a</span> <span m=''2825630''>result</span> <span m=''2826010''>by</span>
  <span m=''2826020''>Bern and</span> <span m=''2826340''>Hayes.</span> <span m=''2827060''>Another</span>
  <span m=''2827400''>result</span> <span m=''2827720''>in</span> <span m=''2827810''>the</span>
  <span m=''2827900''>same</span> <span m=''2828190''>paper</span> <span m=''2828530''>by</span>
  <span m=''2828670''>Bern and</span> <span m=''2828980''>Hayes,</span> <span m=''2829290''>which</span>
  <span m=''2829460''>is</span> <span m=''2829640''>actually</span> <span m=''2829980''>sort
  of</span> <span m=''2830250''>the</span> <span m=''2830340''>bigger</span> <span
  m=''2830760''>result</span> <span m=''2831350''>that</span> <span m=''2831450''>everyone</span>
  <span m=''2831770''>knows</span> <span m=''2831980''>about,</span> <span m=''2833010''>is</span>
  <span m=''2833250''>that</span> <span m=''2833390''>if</span> <span m=''2833520''>I</span>
  <span m=''2833570''>give</span> <span m=''2833830''>you</span> <span m=''2834050''>an</span>
  <span m=''2834130''>arbitrary</span> <span m=''2834540''>crease</span> <span m=''2834780''>pattern,</span>
  <span m=''2835130''>I</span> <span m=''2835160''>want</span> <span m=''2835380''>to</span>
  <span m=''2835420''>know</span> <span m=''2835570''>just</span> <span m=''2835840''>does</span>
  <span m=''2836040''>it</span> <span m=''2836180''>fold</span> <span m=''2836450''>flat,</span>
  <span m=''2837620''>that''s</span> <span m=''2837840''>NP-hard.</span> </p><p><span
  m=''2839720''>They</span> <span m=''2839830''>proved</span> <span m=''2840170''>actually</span>
  <span m=''2840940''>two</span> <span m=''2841280''>NP-hard</span> <span m=''2841520''>hardness</span>
  <span m=''2841850''>results.</span> <span m=''2850400''>So</span> <span m=''2850540''>this</span>
  <span m=''2850710''>is</span> <span m=''2850820''>way</span> <span m=''2850940''>back</span>
  <span m=''2851190''>in</span> <span m=''2851310''>''96.</span> <span m=''2851970''>This
  is</span> <span m=''2852210''>one</span> <span m=''2852350''>of</span> <span m=''2852420''>the</span>
  <span m=''2853170''>oldest</span> <span m=''2853550''>results</span> <span m=''2855390''>in</span>
  <span m=''2856910''>computational</span> <span m=''2857620''>origami.</span> <span
  m=''2862280''>So</span> <span m=''2862450''>I</span> <span m=''2862590''>give</span>
  <span m=''2862780''>you</span> <span m=''2862900''>a</span> <span m=''2862950''>crease</span>
  <span m=''2863200''>pattern.</span> <span m=''2864110''>I</span> <span m=''2864430''>just</span>
  <span m=''2864540''>want</span> <span m=''2864690''>to</span> <span m=''2864730''>know,</span>
  <span m=''2864880''>is</span> <span m=''2865070''>it</span> <span m=''2865180''>flat</span>
  <span m=''2865450''>foldable</span> <span m=''2865980''>in</span> <span m=''2866070''>the</span>
  <span m=''2866360''>global,</span> <span m=''2866800''>in</span> <span m=''2866900''>the</span>
  <span m=''2867000''>regular</span> <span m=''2867390''>sense?</span> <span m=''2871820''>This</span>
  <span m=''2872170''>is</span> <span m=''2873960''>strongly</span> <span m=''2874530''>NP-hard.</span>
  <span m=''2879440''>The proof</span> <span m=''2879510''>I</span> <span m=''2879570''>just</span>
  <span m=''2879780''>gave</span> <span m=''2879970''>is</span> <span m=''2880060''>actually</span>
  <span m=''2880360''>weakly</span> <span m=''2880640''>NP-hard.</span> <span m=''2881000''>It
  is</span> <span m=''2881120''>not</span> <span m=''2881320''>known</span> <span
  m=''2881600''>whether</span> <span m=''2881790''>that</span> <span m=''2881980''>problem</span>
  <span m=''2882310''>is</span> <span m=''2883290''>strongly</span> <span m=''2883750''>or</span>
  <span m=''2883840''>weakly</span> <span m=''2884120''>hard,</span> <span m=''2884385''>but</span>
  <span m=''2885512''>at</span> <span m=''2885920''>least</span> <span m=''2886130''>weekly.</span>
  <span m=''2902270''>The</span> <span m=''2902460''>other</span> <span m=''2902640''>thing</span>
  <span m=''2904070''>they</span> <span m=''2904210''>proved</span> <span m=''2906050''>is
  that</span> <span m=''2906260''>if</span> <span m=''2906370''>you''re</span> <span
  m=''2906560''>given</span> <span m=''2908610''>a</span> <span m=''2909110''>flat</span>
  <span m=''2909470''>foldable,</span> <span m=''2911500''>even</span> <span m=''2911720''>I</span>
  <span m=''2911790''>tell</span> <span m=''2912070''>you</span> <span m=''2912200''>it''s</span>
  <span m=''2912330''>flat</span> <span m=''2912550''>foldable,</span> <span m=''2914460''>and</span>
  <span m=''2914590''>I</span> <span m=''2914670''>even</span> <span m=''2914910''>give</span>
  <span m=''2915140''>you</span> <span m=''2915230''>the</span> <span m=''2915340''>mountains</span>
  <span m=''2915680''>and</span> <span m=''2915770''>valleys</span> <span m=''2916160''>that</span>
  <span m=''2916250''>make</span> <span m=''2916450''>it</span> <span m=''2916530''>work,</span>
  <span m=''2917660''>still</span> <span m=''2918600''>flat</span> <span m=''2918820''>folding</span>
  <span m=''2919180''>thing</span> <span m=''2920100''>is</span> <span m=''2920270''>NP-hard.</span>
  </p><p><span m=''2933840''>So</span> <span m=''2933970''>if</span> <span m=''2934080''>I</span>
  <span m=''2934130''>give</span> <span m=''2934390''>you</span> <span m=''2934490''>a</span>
  <span m=''2934530''>flat</span> <span m=''2934810''>foldable</span> <span m=''2935140''>mountain</span>
  <span m=''2935380''>valley</span> <span m=''2935640''>pattern,</span> <span m=''2935980''>all</span>
  <span m=''2936220''>that''s</span> <span m=''2936410''>left</span> <span m=''2936850''>is</span>
  <span m=''2937040''>to</span> <span m=''2937110''>decide</span> <span m=''2937770''>I
  can</span> <span m=''2938020''>fold</span> <span m=''2938250''>each</span> <span
  m=''2938410''>vertex.</span> <span m=''2939260''>And</span> <span m=''2939480''>then</span>
  <span m=''2939640''>there''s</span> <span m=''2939860''>this</span> <span m=''2940060''>issue</span>
  <span m=''2940360''>of</span> <span m=''2941090''>layering.</span> <span m=''2941700''>If</span>
  <span m=''2942170''>I</span> <span m=''2942280''>have</span> <span m=''2942460''>two</span>
  <span m=''2942600''>layers</span> <span m=''2942820''>of</span> <span m=''2942890''>paper</span>
  <span m=''2943150''>that are</span> <span m=''2943330''>overlapping,</span> <span
  m=''2943850''>they</span> <span m=''2943940''>could</span> <span m=''2944070''>be</span>
  <span m=''2944170''>like</span> <span m=''2944340''>this.</span> <span m=''2944570''>Or</span>
  <span m=''2944620''>they</span> <span m=''2944750''>could</span> <span m=''2944870''>be</span>
  <span m=''2944970''>like</span> <span m=''2945160''>this.</span> <span m=''2946300''>And</span>
  <span m=''2946900''>if</span> <span m=''2947100''>I</span> <span m=''2947190''>have,</span>
  <span m=''2947460''>for</span> <span m=''2947550''>example,</span> <span m=''2947890''>two</span>
  <span m=''2948050''>crimps,</span> <span m=''2948310''>I could</span> <span m=''2948660''>decide</span>
  <span m=''2949560''>how</span> <span m=''2949760''>the</span> <span m=''2949850''>layers</span>
  <span m=''2950170''>go.</span> <span m=''2951860''>Figuring</span> <span m=''2952440''>out</span>
  <span m=''2952630''>what</span> <span m=''2952780''>the</span> <span m=''2952880''>right</span>
  <span m=''2953060''>layer</span> <span m=''2953390''>ordering</span> <span m=''2953710''>is</span>
  <span m=''2953880''>is</span> <span m=''2953990''>really</span> <span m=''2954260''>the</span>
  <span m=''2954390''>heart</span> <span m=''2954670''>of</span> <span m=''2954740''>the</span>
  <span m=''2954830''>problem.</span> <span m=''2955610''>This</span> <span m=''2955780''>is</span>
  <span m=''2955890''>what</span> <span m=''2956050''>makes</span> <span m=''2956290''>it</span>
  <span m=''2956380''>NP-hard.</span> <span m=''2957470''>Because</span> <span m=''2957670''>we
  know</span> <span m=''2958260''>finding</span> <span m=''2958510''>a</span> <span
  m=''2958530''>mountain</span> <span m=''2958780''>valley</span> <span m=''2959040''>assignment--</span>
  <span m=''2959510''>locally</span> <span m=''2959850''>things</span> <span m=''2960050''>work--</span>
  <span m=''2960300''>is</span> <span m=''2960520''>easy.</span> <span m=''2961590''>But</span>
  <span m=''2961790''>getting</span> <span m=''2962060''>that</span> <span m=''2962870''>layering</span>
  <span m=''2963190''>to</span> <span m=''2963270''>work</span> <span m=''2963670''>is</span>
  <span m=''2963790''>hard.</span> <span m=''2964840''>That''s</span> <span m=''2965000''>what
  all</span> <span m=''2965210''>these</span> <span m=''2965420''>proofs</span> <span
  m=''2966550''>say.</span> </p><p><span m=''2976250''>So</span> <span m=''2976440''>I''m</span>
  <span m=''2976550''>going</span> <span m=''2976650''>to</span> <span m=''2976730''>talk</span>
  <span m=''2976940''>about</span> <span m=''2977140''>the</span> <span m=''2977220''>proof</span>
  <span m=''2977460''>of</span> <span m=''2977550''>the</span> <span m=''2977620''>first</span>
  <span m=''2977920''>result though,</span> <span m=''2978370''>because</span> <span
  m=''2978560''>the</span> <span m=''2978620''>second</span> <span m=''2978950''>one</span>
  <span m=''2979120''>is</span> <span m=''2979230''>pretty</span> <span m=''2979540''>complicated.</span>
  <span m=''2985320''>It''s</span> <span m=''2985610''>the</span> <span m=''2985740''>same</span>
  <span m=''2985950''>spirit,</span> <span m=''2986790''>just</span> <span m=''2987050''>a</span>
  <span m=''2987120''>lot</span> <span m=''2987320''>more</span> <span m=''2987450''>details.</span>
  <span m=''2993720''>Again,</span> <span m=''2994000''>we''re</span> <span m=''2994110''>going</span>
  <span m=''2994220''>to</span> <span m=''2994290''>do</span> <span m=''2994360''>a</span>
  <span m=''2994470''>reduction.</span> <span m=''2996080''>And</span> <span m=''2996310''>we</span>
  <span m=''2996410''>have</span> <span m=''2996610''>these</span> <span m=''2996800''>two</span>
  <span m=''2996920''>nice</span> <span m=''2997160''>problems,</span> <span m=''2997520''>partition</span>
  <span m=''2997960''>and</span> <span m=''2998110''>SAT.</span> <span m=''2999420''>I''m
  not</span> <span m=''2999460''>going to</span> <span m=''2999600''>use</span> <span
  m=''2999790''>either</span> <span m=''3000100''>of them,</span> <span m=''3000920''>though
  in</span> <span m=''3001210''>theory</span> <span m=''3001510''>you</span> <span
  m=''3001850''>could</span> <span m=''3002040''>use</span> <span m=''3002310''>SAT.</span>
  <span m=''3002840''>I''m</span> <span m=''3003010''>going</span> <span m=''3003120''>to</span>
  <span m=''3003290''>reduce</span> <span m=''3003720''>from</span> <span m=''3004570''>one</span>
  <span m=''3004760''>of</span> <span m=''3004800''>my</span> <span m=''3004920''>favorite</span>
  <span m=''3005330''>problems,</span> <span m=''3006380''>one</span> <span m=''3006440''>of</span>
  <span m=''3006490''>my</span> <span m=''3006590''>favorite</span> <span m=''3006900''>NP-hard</span>
  <span m=''3007340''>problems,</span> <span m=''3007710''>I</span> <span m=''3007750''>should</span>
  <span m=''3007930''>say.</span> <span m=''3009240''>Wait,</span> <span m=''3009480''>no.</span>
  <span m=''3010530''>That''s</span> <span m=''3010770''>the</span> <span m=''3010870''>next
  proof.</span> <span m=''3011230''>This</span> <span m=''3011730''>is</span> <span
  m=''3011930''>not</span> <span m=''3012090''>my</span> <span m=''3012200''>favorite.</span>
  <span m=''3012630''>It''s a</span> <span m=''3012760''>pretty</span> <span m=''3012930''>good</span>
  <span m=''3013080''>one,</span> <span m=''3013240''>though.</span> <span m=''3014020''>I</span>
  <span m=''3014040''>do</span> <span m=''3014190''>like</span> <span m=''3014420''>it.</span>
  <span m=''3016350''>Is</span> <span m=''3016530''>just</span> <span m=''3016840''>a</span>
  <span m=''3017310''>little</span> <span m=''3017510''>more</span> <span m=''3017700''>technical.</span>
  </p><p><span m=''3031230''>All</span> <span m=''3031690''>positive,</span> <span
  m=''3032440''>not</span> <span m=''3032820''>all</span> <span m=''3033060''>equal</span>
  <span m=''3033370''>3SAT,</span> <span m=''3033930''>has</span> <span m=''3034050''>anyone</span>
  <span m=''3034350''>heard</span> <span m=''3034510''>of</span> <span m=''3034560''>this</span>
  <span m=''3034690''>problem</span> <span m=''3034940''>before?</span> <span m=''3037560''>Nadia''s</span>
  <span m=''3037880''>heard</span> <span m=''3038040''>of</span> <span m=''3038150''>it,</span>
  <span m=''3038290''>because</span> <span m=''3039470''>she</span> <span m=''3039640''>TA''d</span>
  <span m=''3039860''>this</span> <span m=''3040040''>class</span> <span m=''3040460''>before.</span>
  <span m=''3041506''>It''s</span> <span m=''3041890''>no</span> <span m=''3042020''>surprise.</span>
  <span m=''3042305''>So</span> <span m=''3042590''>you''ve read</span> <span m=''3042980''>the</span>
  <span m=''3043040''>book.</span> <span m=''3044370''>This</span> <span m=''3044580''>is,</span>
  <span m=''3044930''>there</span> <span m=''3045170''>aren''t</span> <span m=''3045240''>a</span>
  <span m=''3045300''>lot</span> <span m=''3045460''>of</span> <span m=''3045530''>proofs
  that</span> <span m=''3045810''>use</span> <span m=''3045960''>this</span> <span
  m=''3046110''>one.</span> <span m=''3046320''>But</span> <span m=''3046510''>not</span>
  <span m=''3046770''>all</span> <span m=''3046920''>equal</span> <span m=''3047150''>3SAT</span>
  <span m=''3047620''>is</span> <span m=''3047740''>actually</span> <span m=''3048070''>fairly</span>
  <span m=''3048390''>common.</span> <span m=''3049660''>All</span> <span m=''3049830''>positive</span>
  <span m=''3050310''>is</span> <span m=''3050440''>just</span> <span m=''3051160''>makes</span>
  <span m=''3051440''>a</span> <span m=''3051520''>little</span> <span m=''3051710''>more</span>
  <span m=''3051880''>convenient.</span> <span m=''3052800''>I</span> <span m=''3052880''>think</span>
  <span m=''3053070''>actually</span> <span m=''3053310''>the</span> <span m=''3053420''>original</span>
  <span m=''3053710''>proof</span> <span m=''3053930''>didn''t</span> <span m=''3054130''>use</span>
  <span m=''3054300''>all</span> <span m=''3054430''>positive.</span> <span m=''3054860''>But</span>
  <span m=''3055000''>our</span> <span m=''3055100''>book</span> <span m=''3055340''>does.</span>
  <span m=''3056030''>Because</span> <span m=''3056200''>it</span> <span m=''3056300''>simplifies</span>
  <span m=''3056810''>things.</span> <span m=''3058180''>So</span> <span m=''3058370''>let</span>
  <span m=''3058490''>me</span> <span m=''3058590''>tell</span> <span m=''3058750''>you</span>
  <span m=''3058830''>what</span> <span m=''3058930''>this</span> <span m=''3059070''>problem</span>
  <span m=''3059350''>is.</span> <span m=''3062150''>Most</span> <span m=''3062320''>people</span>
  <span m=''3062530''>don''t</span> <span m=''3062710''>know</span> <span m=''3062860''>it.</span>
  <span m=''3062990''>So</span> <span m=''3063110''>don''t</span> <span m=''3063270''>worry.</span>
  </p><p><span m=''3068830''>You</span> <span m=''3068960''>could</span> <span m=''3069220''>technically,</span>
  <span m=''3069960''>it''s</span> <span m=''3070340''>a</span> <span m=''3070390''>version</span>
  <span m=''3070720''>of</span> <span m=''3070810''>SAT.</span> <span m=''3072100''>But</span>
  <span m=''3072290''>instead</span> <span m=''3072550''>of</span> <span m=''3072640''>giving</span>
  <span m=''3072910''>a</span> <span m=''3072960''>Boolean</span> <span m=''3073320''>formula,</span>
  <span m=''3073790''>I''m</span> <span m=''3073860''>going</span> <span m=''3073980''>to</span>
  <span m=''3074280''>think</span> <span m=''3074530''>of</span> <span m=''3074640''>that</span>
  <span m=''3074990''>it''s</span> <span m=''3075150''>really</span> <span m=''3075430''>a
  Boolean</span> <span m=''3075770''>formula.</span> <span m=''3076100''>But</span>
  <span m=''3076250''>I''m</span> <span m=''3076320''>going</span> <span m=''3076400''>to</span>
  <span m=''3076470''>think</span> <span m=''3076680''>of</span> <span m=''3076760''>it</span>
  <span m=''3076850''>in</span> <span m=''3076950''>a</span> <span m=''3077000''>simpler</span>
  <span m=''3077350''>way,</span> <span m=''3077935''>which</span> <span m=''3078220''>is</span>
  <span m=''3078320''>I</span> <span m=''3078360''>give</span> <span m=''3078560''>you</span>
  <span m=''3078660''>a</span> <span m=''3078680''>bunch</span> <span m=''3078910''>of</span>
  <span m=''3079010''>triples</span> <span m=''3079460''>if</span> <span m=''3079510''>variables,</span>
  <span m=''3081470''>so</span> <span m=''3081760''>like</span> <span m=''3082030''>xi,</span>
  <span m=''3082390''>xj</span> <span m=''3082770''>xk.</span> <span m=''3083850''>And</span>
  <span m=''3084190''>I</span> <span m=''3084240''>want</span> <span m=''3084450''>to</span>
  <span m=''3084510''>know</span> <span m=''3086830''>is</span> <span m=''3087120''>there</span>
  <span m=''3088460''>a</span> <span m=''3088500''>Boolean</span> <span m=''3088870''>assignment</span>
  <span m=''3089390''>to</span> <span m=''3089460''>those</span> <span m=''3089630''>variables?</span>
  <span m=''3090090''>I</span> <span m=''3090140''>want</span> <span m=''3090330''>to</span>
  <span m=''3090390''>set</span> <span m=''3090830''>each</span> <span m=''3091060''>of</span>
  <span m=''3091110''>them</span> <span m=''3091250''>to</span> <span m=''3091360''>true</span>
  <span m=''3091530''>or</span> <span m=''3091620''>false.</span> <span m=''3103730''>Say</span>
  <span m=''3103990''>there''s</span> <span m=''3104170''>n</span> <span m=''3104410''>variables.</span>
  <span m=''3107800''>So</span> <span m=''3108150''>that</span> <span m=''3109230''>no</span>
  <span m=''3109520''>triple</span> <span m=''3111440''>is</span> <span m=''3112510''>all</span>
  <span m=''3112810''>equal,</span> <span m=''3115990''>no</span> <span m=''3116170''>triple</span>
  <span m=''3117150''>is</span> <span m=''3117460''>all</span> <span m=''3117720''>true</span>
  <span m=''3120750''>or</span> <span m=''3121180''>all</span> <span m=''3121460''>false.</span>
  <span m=''3127450''>Maybe we</span> <span m=''3127710''>could</span> <span m=''3127810''>call</span>
  <span m=''3128030''>it the all</span> <span m=''3128180''>state</span> <span m=''3128720''>problem.</span>
  <span m=''3130570''>I''ve been</span> <span m=''3130820''>watching</span> <span
  m=''3130940''>too</span> <span m=''3131110''>many</span> <span m=''3131390''>ads.</span>
  </p><p><span m=''3132420''>All</span> <span m=''3132480''>right,</span> <span m=''3133450''>so</span>
  <span m=''3133870''>if</span> <span m=''3134030''>not</span> <span m=''3134230''>all</span>
  <span m=''3134380''>equal</span> <span m=''3134640''>3SAT,</span> <span m=''3135350''>that''s</span>
  <span m=''3136260''>this</span> <span m=''3136460''>version.</span> <span m=''3137400''>Actually,</span>
  <span m=''3137710''>it''s</span> <span m=''3137850''>also</span> <span m=''3138130''>all</span>
  <span m=''3138340''>positive,</span> <span m=''3138930''>meaning</span> <span m=''3139730''>I</span>
  <span m=''3139830''>don''t</span> <span m=''3140030''>have</span> <span m=''3140190''>any</span>
  <span m=''3140330''>nots</span> <span m=''3140790''>in</span> <span m=''3140870''>here.</span>
  <span m=''3141460''>So</span> <span m=''3141920''>ignore</span> <span m=''3142250''>that.</span>
  <span m=''3142880''>Ignore</span> <span m=''3143090''>the</span> <span m=''3143190''>technical</span>
  <span m=''3143680''>term.</span> <span m=''3144760''>This</span> <span m=''3144870''>is</span>
  <span m=''3145070''>the</span> <span m=''3145180''>right</span> <span m=''3145340''>definition.</span>
  <span m=''3146220''>So</span> <span m=''3146360''>I</span> <span m=''3146410''>have</span>
  <span m=''3146540''>a</span> <span m=''3146590''>bunch</span> <span m=''3146800''>of</span>
  <span m=''3146840''>triples</span> <span m=''3147970''>of</span> <span m=''3148040''>variables.</span>
  <span m=''3148590''>I</span> <span m=''3148660''>just</span> <span m=''3148890''>don''t</span>
  <span m=''3149090''>want</span> <span m=''3149280''>them</span> <span m=''3149420''>all</span>
  <span m=''3149570''>to</span> <span m=''3149630''>be</span> <span m=''3149750''>true</span>
  <span m=''3150000''>or</span> <span m=''3150130''>all to be</span> <span m=''3150190''>false.</span>
  <span m=''3150670''>So two of</span> <span m=''3150880''>them</span> <span m=''3151030''>could</span>
  <span m=''3151130''>be</span> <span m=''3151240''>true</span> <span m=''3151530''>and
  one</span> <span m=''3151720''>false,</span> <span m=''3152180''>or</span> <span
  m=''3152340''>two of</span> <span m=''3152490''>them</span> <span m=''3152630''>could
  be</span> <span m=''3152930''>false, and</span> <span m=''3153170''>one</span> <span
  m=''3153340''>true.</span> <span m=''3154830''>That''s</span> <span m=''3155040''>all.</span>
  <span m=''3155595''>It</span> <span m=''3155940''>turns</span> <span m=''3156210''>out</span>
  <span m=''3156360''>this</span> <span m=''3156500''>is</span> <span m=''3156610''>basically</span>
  <span m=''3157080''>equivalent</span> <span m=''3157470''>to</span> <span m=''3157550''>SAT.</span>
  <span m=''3158920''>But</span> <span m=''3159150''>the</span> <span m=''3159230''>proof</span>
  <span m=''3159440''>of</span> <span m=''3159520''>that</span> <span m=''3159670''>is</span>
  <span m=''3159790''>kind</span> <span m=''3159950''>of</span> <span m=''3160000''>messy.</span>
  <span m=''3160440''>So</span> <span m=''3160500''>I</span> <span m=''3160570''>don''t</span>
  <span m=''3160720''>want</span> <span m=''3160850''>to</span> <span m=''3162160''>do</span>
  <span m=''3162280''>it</span> <span m=''3162350''>here.</span> <span m=''3166040''>And</span>
  <span m=''3166350''>so</span> <span m=''3166510''>that</span> <span m=''3166720''>problem</span>
  <span m=''3167050''>is</span> <span m=''3167160''>NP-hard.</span> <span m=''3167910''>Just</span>
  <span m=''3168160''>take</span> <span m=''3168330''>that</span> <span m=''3168480''>on</span>
  <span m=''3168630''>faith.</span> </p><p><span m=''3171350''>And</span> <span m=''3171890''>now</span>
  <span m=''3172380''>I</span> <span m=''3172500''>want</span> <span m=''3172730''>to</span>
  <span m=''3172770''>show</span> <span m=''3174010''>that</span> <span m=''3174240''>global</span>
  <span m=''3174810''>flat</span> <span m=''3175160''>foldability</span> <span m=''3176140''>includes</span>
  <span m=''3177500''>all</span> <span m=''3177690''>positive</span> <span m=''3178070''>not</span>
  <span m=''3178670''>all</span> <span m=''3178820''>will</span> <span m=''3178940''>equal</span>
  <span m=''3179220''>3SAT</span> <span m=''3179810''>as</span> <span m=''3179960''>a</span>
  <span m=''3180010''>special</span> <span m=''3180340''>case.</span> <span m=''3181310''>And</span>
  <span m=''3181440''>therefore,</span> <span m=''3181870''>it''s</span> <span m=''3182080''>also</span>
  <span m=''3182910''>NP-hard.</span> <span m=''3192010''>So</span> <span m=''3195040''>I''ll</span>
  <span m=''3195380''>give</span> <span m=''3195550''>you</span> <span m=''3195630''>a</span>
  <span m=''3195680''>preview.</span> <span m=''3204490''>Start</span> <span m=''3204810''>with</span>
  <span m=''3205030''>a</span> <span m=''3205140''>high</span> <span m=''3205370''>level,</span>
  <span m=''3206110''>what</span> <span m=''3206270''>we</span> <span m=''3206390''>need</span>
  <span m=''3215440''>in</span> <span m=''3215510''>terms</span> <span m=''3215710''>of</span>
  <span m=''3215820''>gadgets.</span> <span m=''3225450''>And then</span> <span m=''3225610''>I''ll</span>
  <span m=''3225680''>show</span> <span m=''3225830''>you</span> <span m=''3225900''>the</span>
  <span m=''3226000''>gadgets,</span> <span m=''3226530''>and</span> <span m=''3226610''>then</span>
  <span m=''3226740''>show</span> <span m=''3226910''>you</span> <span m=''3227020''>how</span>
  <span m=''3227140''>they</span> <span m=''3227240''>fit</span> <span m=''3227440''>together.</span>
  <span m=''3229490''>So</span> <span m=''3230250''>this</span> <span m=''3230540''>is</span>
  <span m=''3230710''>a</span> <span m=''3230920''>general</span> <span m=''3231610''>picture,</span>
  <span m=''3232010''>in</span> <span m=''3232110''>fact,</span> <span m=''3232420''>of</span>
  <span m=''3232510''>what</span> <span m=''3232670''>a</span> <span m=''3232740''>SAT</span>
  <span m=''3233190''>kind</span> <span m=''3233460''>of</span> <span m=''3234200''>NP-hardness</span>
  <span m=''3234610''>proof</span> <span m=''3235050''>looks</span> <span m=''3235260''>like.</span>
  <span m=''3235460''>If you</span> <span m=''3235590''>haven''t</span> <span m=''3235720''>done</span>
  <span m=''3235950''>many</span> <span m=''3236200''>of</span> <span m=''3236280''>them,</span>
  <span m=''3238870''>now</span> <span m=''3239080''>you''ll</span> <span m=''3239240''>know.</span>
  <span m=''3239680''>If</span> <span m=''3239810''>you</span> <span m=''3239890''>have</span>
  <span m=''3240100''>done</span> <span m=''3240250''>many</span> <span m=''3240440''>of</span>
  <span m=''3240490''>them,</span> <span m=''3240660''>you</span> <span m=''3240930''>will</span>
  <span m=''3241050''>recognize</span> <span m=''3241355''>this</span> <span m=''3241660''>pattern,</span>
  <span m=''3242540''>which</span> <span m=''3242740''>is</span> <span m=''3243580''>to</span>
  <span m=''3243730''>represent</span> <span m=''3244350''>Boolean-ness,</span> <span
  m=''3245930''>we</span> <span m=''3246150''>need</span> <span m=''3246490''>something</span>
  <span m=''3246900''>that</span> <span m=''3246940''>represents</span> <span m=''3247340''>true</span>
  <span m=''3247520''>and</span> <span m=''3247630''>false.</span> <span m=''3248290''>And
  that''s usually</span> <span m=''3248600''>called</span> <span m=''3248780''>a</span>
  <span m=''3248860''>wire.</span> <span m=''3249500''>We</span> <span m=''3249630''>think</span>
  <span m=''3249870''>of</span> <span m=''3250130''>digital</span> <span m=''3251010''>signals</span>
  <span m=''3251940''>like</span> <span m=''3252120''>chips.</span> <span m=''3253830''>And</span>
  <span m=''3253920''>then</span> <span m=''3254090''>we''ve</span> <span m=''3254190''>got</span>
  <span m=''3254330''>to</span> <span m=''3254390''>be</span> <span m=''3254480''>able</span>
  <span m=''3254640''>to</span> <span m=''3254760''>connect</span> <span m=''3255030''>those</span>
  <span m=''3255170''>wires</span> <span m=''3255420''>together</span> <span m=''3255750''>to</span>
  <span m=''3255840''>do</span> <span m=''3255980''>interesting</span> <span m=''3256430''>things.</span>
  </p><p><span m=''3256920''>In</span> <span m=''3257040''>this</span> <span m=''3257230''>case,</span>
  <span m=''3257480''>the</span> <span m=''3257590''>interesting</span> <span m=''3257990''>thing</span>
  <span m=''3258180''>we</span> <span m=''3258260''>need</span> <span m=''3258420''>to</span>
  <span m=''3258530''>do</span> <span m=''3259200''>is</span> <span m=''3259420''>tell</span>
  <span m=''3260400''>if</span> <span m=''3260550''>I</span> <span m=''3260620''>have</span>
  <span m=''3260800''>a</span> <span m=''3260860''>triple</span> <span m=''3261160''>of</span>
  <span m=''3261260''>them,</span> <span m=''3261480''>are</span> <span m=''3261620''>they</span>
  <span m=''3261750''>all</span> <span m=''3261920''>true</span> <span m=''3262260''>or
  all</span> <span m=''3262500''>false,</span> <span m=''3263140''>and</span> <span
  m=''3263300''>somehow</span> <span m=''3263950''>force</span> <span m=''3264310''>them</span>
  <span m=''3264480''>to</span> <span m=''3264600''>not</span> <span m=''3264920''>be</span>
  <span m=''3265225''>all</span> <span m=''3265530''>true or</span> <span m=''3266010''>all</span>
  <span m=''3266150''>false.</span> <span m=''3266570''>And</span> <span m=''3266830''>in</span>
  <span m=''3266970''>this</span> <span m=''3267150''>case,</span> <span m=''3267500''>that</span>
  <span m=''3267570''>will</span> <span m=''3267680''>be</span> <span m=''3268220''>a</span>
  <span m=''3268300''>not</span> <span m=''3268510''>all</span> <span m=''3268660''>equal</span>
  <span m=''3268900''>clause.</span> <span m=''3269880''>It''ll</span> <span m=''3270060''>be</span>
  <span m=''3270170''>a</span> <span m=''3270210''>gadget</span> <span m=''3270730''>the</span>
  <span m=''3270830''>folds</span> <span m=''3271160''>flat,</span> <span m=''3272010''>exactly</span>
  <span m=''3272520''>when</span> <span m=''3272830''>those</span> <span m=''3273150''>wires</span>
  <span m=''3273670''>that</span> <span m=''3273760''>come</span> <span m=''3273970''>together,</span>
  <span m=''3274360''>three</span> <span m=''3274590''>wires</span> <span m=''3274920''>come</span>
  <span m=''3275080''>together.</span> <span m=''3275920''>And</span> <span m=''3276250''>if</span>
  <span m=''3276360''>they''re</span> <span m=''3276490''>all</span> <span m=''3276700''>truth,</span>
  <span m=''3277260''>they</span> <span m=''3277330''>won''t</span> <span m=''3277560''>fold</span>
  <span m=''3277740''>flat.</span> <span m=''3278080''>If they''re</span> <span m=''3278420''>all</span>
  <span m=''3278610''>false,</span> <span m=''3279000''>it</span> <span m=''3279060''>won''t</span>
  <span m=''3279230''>fold</span> <span m=''3279420''>flat.</span> <span m=''3279840''>In</span>
  <span m=''3280000''>all</span> <span m=''3280160''>of</span> <span m=''3280240''>the</span>
  <span m=''3280320''>cases,</span> <span m=''3280710''>it</span> <span m=''3280820''>will</span>
  <span m=''3281000''>fold</span> <span m=''3281220''>flat.</span> </p><p><span m=''3282260''>So</span>
  <span m=''3282520''>if</span> <span m=''3282620''>we</span> <span m=''3282710''>could</span>
  <span m=''3282830''>build</span> <span m=''3283030''>that,</span> <span m=''3283830''>that''ll</span>
  <span m=''3284180''>constrain</span> <span m=''3284740''>the</span> <span m=''3284810''>variables</span>
  <span m=''3285310''>that I</span> <span m=''3285440''>connect</span> <span m=''3285710''>together</span>
  <span m=''3286430''>with</span> <span m=''3286600''>a</span> <span m=''3286650''>not</span>
  <span m=''3286820''>all</span> <span m=''3286950''>equal</span> <span m=''3287160''>clause.</span>
  <span m=''3288410''>But</span> <span m=''3289010''>how</span> <span m=''3289210''>do</span>
  <span m=''3289330''>I</span> <span m=''3289410''>actually</span> <span m=''3290920''>move</span>
  <span m=''3291330''>the</span> <span m=''3291430''>wires</span> <span m=''3291780''>around</span>
  <span m=''3292480''>to</span> <span m=''3292650''>make</span> <span m=''3292880''>them</span>
  <span m=''3293040''>connect</span> <span m=''3293310''>together</span> <span m=''3293690''>at
  these</span> <span m=''3293910''>clauses?</span> <span m=''3294910''>Well,</span>
  <span m=''3295110''>I</span> <span m=''3295250''>need</span> <span m=''3295490''>something</span>
  <span m=''3295810''>called</span> <span m=''3296010''>a</span> <span m=''3296060''>turn</span>
  <span m=''3296370''>gadget.</span> <span m=''3296920''>If</span> <span m=''3297340''>I</span>
  <span m=''3297410''>have</span> <span m=''3297590''>a</span> <span m=''3297650''>wire</span>
  <span m=''3298050''>going</span> <span m=''3298290''>straight,</span> <span m=''3298700''>I''d</span>
  <span m=''3298780''>like</span> <span m=''3298920''>to be able to</span> <span m=''3299210''>turn</span>
  <span m=''3299500''>it to</span> <span m=''3299770''>some</span> <span m=''3300030''>other</span>
  <span m=''3300230''>angle.</span> <span m=''3300720''>I</span> <span m=''3300800''>could</span>
  <span m=''3300960''>just</span> <span m=''3301080''>sort</span> <span m=''3301210''>of</span>
  <span m=''3301260''>move them</span> <span m=''3301440''>around.</span> <span m=''3302400''>It''s</span>
  <span m=''3302760''>harder</span> <span m=''3303070''>than</span> <span m=''3303210''>it</span>
  <span m=''3303320''>sounds.</span> <span m=''3304170''>And</span> <span m=''3304990''>I''ll</span>
  <span m=''3305100''>also</span> <span m=''3305420''>need</span> <span m=''3305600''>a</span>
  <span m=''3305670''>split.</span> </p><p><span m=''3306560''>Because</span> <span
  m=''3307900''>in</span> <span m=''3308090''>this,</span> <span m=''3308390''>it''s</span>
  <span m=''3308550''>maybe</span> <span m=''3308770''>not</span> <span m=''3308910''>obvious</span>
  <span m=''3309240''>from</span> <span m=''3309360''>this</span> <span m=''3309500''>formulation,</span>
  <span m=''3310230''>but</span> <span m=''3310890''>I</span> <span m=''3310950''>have</span>
  <span m=''3311120''>these</span> <span m=''3311270''>n</span> <span m=''3311430''>variables.</span>
  <span m=''3311950''>I</span> <span m=''3312040''>might</span> <span m=''3312230''>have</span>
  <span m=''3312360''>many</span> <span m=''3312660''>more</span> <span m=''3312860''>than</span>
  <span m=''3313010''>n</span> <span m=''3313160''>clauses.</span> <span m=''3315060''>Each</span>
  <span m=''3315270''>variable,</span> <span m=''3315630''>like</span> <span m=''3315810''>x1,</span>
  <span m=''3316220''>might</span> <span m=''3316390''>appear</span> <span m=''3316740''>in</span>
  <span m=''3316820''>100</span> <span m=''3317240''>different</span> <span m=''3318610''>triples.</span>
  <span m=''3319990''>And</span> <span m=''3320160''>so</span> <span m=''3320260''>I</span>
  <span m=''3320370''>actually</span> <span m=''3320660''>need</span> <span m=''3320840''>100</span>
  <span m=''3321250''>copies</span> <span m=''3321650''>of</span> <span m=''3321760''>x1.</span>
  <span m=''3322680''>And</span> <span m=''3322820''>that''s</span> <span m=''3323020''>what</span>
  <span m=''3323150''>a</span> <span m=''3323210''>split</span> <span m=''3323510''>gadget</span>
  <span m=''3323830''>does.</span> <span m=''3324050''>And</span> <span m=''3324170''>we''re</span>
  <span m=''3324300''>going</span> <span m=''3324400''>to</span> <span m=''3324470''>build</span>
  <span m=''3324680''>one</span> <span m=''3324910''>gadget</span> <span m=''3325170''>called</span>
  <span m=''3325330''>a</span> <span m=''3325410''>reflector,</span> <span m=''3325930''>which</span>
  <span m=''3326100''>actually</span> <span m=''3326360''>does</span> <span m=''3326530''>both</span>
  <span m=''3326760''>of</span> <span m=''3326830''>those</span> <span m=''3327040''>in</span>
  <span m=''3327150''>one</span> <span m=''3327790''>fell</span> <span m=''3328030''>swoop.</span>
  </p><p><span m=''3329620''>And</span> <span m=''3329920''>the</span> <span m=''3330030''>last</span>
  <span m=''3330330''>thing</span> <span m=''3330470''>we</span> <span m=''3330550''>need</span>
  <span m=''3330700''>is</span> <span m=''3330830''>a</span> <span m=''3330910''>crossover.</span>
  <span m=''3331670''>Because</span> <span m=''3332780''>you</span> <span m=''3333000''>make</span>
  <span m=''3333240''>all</span> <span m=''3333350''>these</span> <span m=''3333510''>connections</span>
  <span m=''3333990''>between</span> <span m=''3334180''>variables</span> <span m=''3334780''>and</span>
  <span m=''3335890''>clauses</span> <span m=''3336390''>or</span> <span m=''3336460''>triples.</span>
  <span m=''3337450''>And</span> <span m=''3337640''>they</span> <span m=''3337740''>might</span>
  <span m=''3338480''>have</span> <span m=''3338650''>to</span> <span m=''3338750''>cross</span>
  <span m=''3339000''>each</span> <span m=''3339160''>other.</span> <span m=''3339620''>And</span>
  <span m=''3339830''>we</span> <span m=''3339900''>want</span> <span m=''3340090''>them</span>
  <span m=''3340180''>to</span> <span m=''3340250''>cross</span> <span m=''3340480''>each</span>
  <span m=''3340630''>other,</span> <span m=''3340770''>but</span> <span m=''3340900''>not</span>
  <span m=''3341070''>affect</span> <span m=''3341400''>each</span> <span m=''3341560''>other.</span>
  <span m=''3342510''>And</span> <span m=''3342590''>because</span> <span m=''3342770''>we''re</span>
  <span m=''3342920''>in</span> <span m=''3343560''>a</span> <span m=''3343610''>sheet</span>
  <span m=''3343920''>of</span> <span m=''3343990''>paper,</span> <span m=''3344620''>we''ve</span>
  <span m=''3344960''>got</span> <span m=''3345100''>to</span> <span m=''3345190''>deal</span>
  <span m=''3345400''>with</span> <span m=''3345530''>that.</span> <span m=''3346100''>It''s</span>
  <span m=''3346220''>going</span> <span m=''3346340''>to</span> <span m=''3346400''>be</span>
  <span m=''3346490''>these</span> <span m=''3346640''>wires</span> <span m=''3347000''>to</span>
  <span m=''3347100''>go</span> <span m=''3347240''>right</span> <span m=''3347430''>through</span>
  <span m=''3347590''>each</span> <span m=''3347750''>other.</span> <span m=''3348340''>We
  got</span> <span m=''3348480''>to</span> <span m=''3348530''>make</span> <span m=''3348680''>it</span>
  <span m=''3348790''>still</span> <span m=''3349030''>flat</span> <span m=''3349300''>foldable</span>
  <span m=''3349760''>without</span> <span m=''3350040''>affecting</span> <span m=''3350490''>either</span>
  <span m=''3350670''>wire.</span> <span m=''3352790''>That''s</span> <span m=''3353000''>all.</span>
  <span m=''3355400''>That''s</span> <span m=''3355620''>pretty</span> <span m=''3355820''>standard</span>
  <span m=''3356740''>for</span> <span m=''3356940''>this</span> <span m=''3357120''>kind</span>
  <span m=''3357270''>of</span> <span m=''3357340''>proof.</span> <span m=''3357960''>These</span>
  <span m=''3358150''>are</span> <span m=''3358210''>the</span> <span m=''3358340''>proofs
  that</span> <span m=''3358680''>I</span> <span m=''3358750''>like</span> <span m=''3358970''>the</span>
  <span m=''3359040''>most,</span> <span m=''3359350''>actually.</span> <span m=''3360610''>Pretty</span>
  <span m=''3360850''>fun.</span> </p><p><span m=''3361150''>So</span> <span m=''3361410''>in</span>
  <span m=''3361540''>our</span> <span m=''3361640''>case,</span> <span m=''3361940''>a</span>
  <span m=''3362040''>wire is</span> <span m=''3362490''>going</span> <span m=''3362600''>to</span>
  <span m=''3362660''>be</span> <span m=''3362770''>super</span> <span m=''3363120''>easy.</span>
  <span m=''3364110''>It''s</span> <span m=''3364150''>just</span> <span m=''3364605''>pleat,</span>
  <span m=''3365950''>so</span> <span m=''3366110''>two</span> <span m=''3366990''>very</span>
  <span m=''3367370''>nearby</span> <span m=''3368340''>parallel</span> <span m=''3368790''>creases.</span>
  <span m=''3370080''>And</span> <span m=''3370210''>because</span> <span m=''3370590''>they''re</span>
  <span m=''3370700''>nearby,</span> <span m=''3371350''>I</span> <span m=''3371660''>mean,</span>
  <span m=''3371790''>if</span> <span m=''3371890''>you</span> <span m=''3371990''>look</span>
  <span m=''3372370''>locally,</span> <span m=''3373150''>it''s</span> <span m=''3373280''>like</span>
  <span m=''3373420''>a</span> <span m=''3373480''>one</span> <span m=''3373630''>dimensional</span>
  <span m=''3374030''>problem.</span> <span m=''3374980''>They</span> <span m=''3375130''>can''t</span>
  <span m=''3375360''>both</span> <span m=''3375550''>be</span> <span m=''3375670''>valley</span>
  <span m=''3375990''>or</span> <span m=''3376050''>both</span> <span m=''3376250''>be</span>
  <span m=''3376330''>mountain.</span> <span m=''3376630''>Because</span> <span m=''3376830''>then</span>
  <span m=''3377970''>these</span> <span m=''3378220''>two</span> <span m=''3378390''>big</span>
  <span m=''3379260''>panels</span> <span m=''3379770''>would</span> <span m=''3380050''>intersect</span>
  <span m=''3380460''>each</span> <span m=''3380620''>other.</span> <span m=''3381960''>So</span>
  <span m=''3382260''>one</span> <span m=''3382450''>of</span> <span m=''3382500''>them
  is</span> <span m=''3382660''>valley,</span> <span m=''3382960''>one</span> <span
  m=''3383110''>of</span> <span m=''3383160''>them is</span> <span m=''3383320''>mountain.</span>
  <span m=''3383710''>There''s exactly</span> <span m=''3384100''>two</span> <span
  m=''3384250''>choices.</span> </p><p><span m=''3385200''>I''m</span> <span m=''3385330''>going</span>
  <span m=''3385440''>to</span> <span m=''3385510''>always</span> <span m=''3385730''>have</span>
  <span m=''3385870''>an</span> <span m=''3386010''>arrow</span> <span m=''3386320''>on</span>
  <span m=''3386440''>my</span> <span m=''3386570''>wire</span> <span m=''3386950''>so</span>
  <span m=''3387090''>I</span> <span m=''3387180''>have</span> <span m=''3387340''>a</span>
  <span m=''3387440''>sense</span> <span m=''3387680''>of</span> <span m=''3387770''>orientation,</span>
  <span m=''3388490''>which</span> <span m=''3388560''>way</span> <span m=''3388660''>the</span>
  <span m=''3388760''>signal is</span> <span m=''3389110''>going.</span> <span m=''3389770''>And</span>
  <span m=''3389950''>once</span> <span m=''3390170''>I</span> <span m=''3390220''>have</span>
  <span m=''3390380''>an</span> <span m=''3390450''>orientation,</span> <span m=''3391360''>the</span>
  <span m=''3391470''>left</span> <span m=''3391770''>side,</span> <span m=''3392230''>if</span>
  <span m=''3392340''>the</span> <span m=''3392430''>left</span> <span m=''3392660''>side</span>
  <span m=''3392850''>is</span> <span m=''3392960''>valley,</span> <span m=''3393640''>that''s</span>
  <span m=''3393880''>true.</span> <span m=''3394520''>If</span> <span m=''3394680''>the</span>
  <span m=''3394770''>left</span> <span m=''3395010''>side</span> <span m=''3395220''>is</span>
  <span m=''3395300''>mountain,</span> <span m=''3395880''>that''s</span> <span m=''3396060''>false.</span>
  <span m=''3397240''>That''s</span> <span m=''3397450''>just</span> <span m=''3397660''>I''m</span>
  <span m=''3397750''>going</span> <span m=''3397850''>to</span> <span m=''3397920''>decide</span>
  <span m=''3398180''>it</span> <span m=''3398440''>that</span> <span m=''3398640''>way.</span>
  <span m=''3399770''>It</span> <span m=''3399830''>doesn''t</span> <span m=''3400040''>actually</span>
  <span m=''3400290''>matter,</span> <span m=''3400620''>because</span> <span m=''3400880''>in</span>
  <span m=''3400950''>this</span> <span m=''3401090''>problem,</span> <span m=''3401370''>true</span>
  <span m=''3401530''>and</span> <span m=''3401630''>false</span> <span m=''3401870''>are</span>
  <span m=''3401950''>symmetric.</span> <span m=''3402800''>But I</span> <span m=''3402930''>just</span>
  <span m=''3403110''>need</span> <span m=''3403220''>to</span> <span m=''3403280''>be</span>
  <span m=''3403390''>consistent</span> <span m=''3403980''>about</span> <span m=''3404800''>which</span>
  <span m=''3405040''>is</span> <span m=''3405150''>which.</span> <span m=''3407380''>OK,</span>
  <span m=''3407530''>so</span> <span m=''3407650''>that</span> <span m=''3407780''>was</span>
  <span m=''3407870''>the</span> <span m=''3407960''>wire</span> <span m=''3408220''>gadget.</span>
  </p><p><span m=''3409080''>The</span> <span m=''3409170''>next</span> <span m=''3409440''>one</span>
  <span m=''3409580''>is</span> <span m=''3409730''>the</span> <span m=''3409780''>not</span>
  <span m=''3409980''>all</span> <span m=''3410120''>equal</span> <span m=''3410350''>gadget.</span>
  <span m=''3410770''>And</span> <span m=''3410860''>I''m</span> <span m=''3410940''>guessing</span>
  <span m=''3411360''>this</span> <span m=''3411530''>is</span> <span m=''3411650''>where</span>
  <span m=''3411880''>Bern and</span> <span m=''3412160''>Hayes</span> <span m=''3412340''>started.</span>
  <span m=''3414650''>Because</span> <span m=''3414880''>it''s</span> <span m=''3415640''>sort</span>
  <span m=''3415880''>of</span> <span m=''3415930''>the</span> <span m=''3416010''>heart</span>
  <span m=''3416230''>of</span> <span m=''3416300''>the</span> <span m=''3416380''>proof.</span>
  <span m=''3417520''>Then</span> <span m=''3417640''>there''s</span> <span m=''3417780''>all</span>
  <span m=''3417890''>these</span> <span m=''3418020''>details</span> <span m=''3418490''>to</span>
  <span m=''3418670''>connect</span> <span m=''3418970''>up</span> <span m=''3419080''>with</span>
  <span m=''3419190''>the</span> <span m=''3419260''>wires,</span> <span m=''3419670''>and</span>
  <span m=''3419760''>split</span> <span m=''3420000''>them,</span> <span m=''3420150''>and</span>
  <span m=''3420210''>whatnot.</span> <span m=''3420710''>But</span> <span m=''3422020''>this</span>
  <span m=''3422320''>is</span> <span m=''3422420''>something</span> <span m=''3422680''>called</span>
  <span m=''3422850''>a</span> <span m=''3422900''>triangular</span> <span m=''3423430''>twist.</span>
  <span m=''3425460''>You</span> <span m=''3425600''>may</span> <span m=''3425730''>have</span>
  <span m=''3425830''>folded</span> <span m=''3426100''>one</span> <span m=''3426260''>before.</span>
  <span m=''3426580''>It''s</span> <span m=''3426710''>kind</span> <span m=''3426870''>of</span>
  <span m=''3426930''>classic.</span> <span m=''3428140''>So</span> <span m=''3428310''>the</span>
  <span m=''3428410''>crease</span> <span m=''3428650''>pattern''s</span> <span m=''3429020''>in</span>
  <span m=''3429070''>the</span> <span m=''3429180''>top</span> <span m=''3429440''>left.</span>
  <span m=''3429770''>And</span> <span m=''3429830''>the</span> <span m=''3429910''>idea
  is</span> <span m=''3430230''>I</span> <span m=''3430270''>have</span> <span m=''3430470''>three</span>
  <span m=''3430700''>wires</span> <span m=''3431020''>coming</span> <span m=''3431270''>together.</span>
  <span m=''3431720''>I</span> <span m=''3431790''>want</span> <span m=''3432000''>this</span>
  <span m=''3432090''>thing</span> <span m=''3432280''>to</span> <span m=''3432360''>fold</span>
  <span m=''3432610''>flat</span> <span m=''3433060''>if,</span> <span m=''3433280''>and</span>
  <span m=''3433340''>only</span> <span m=''3433610''>if,</span> <span m=''3434200''>the</span>
  <span m=''3434310''>wires</span> <span m=''3435410''>are</span> <span m=''3435600''>not</span>
  <span m=''3435880''>all</span> <span m=''3436050''>the</span> <span m=''3436130''>same.</span>
  <span m=''3438080''>And</span> <span m=''3438360''>I''ve</span> <span m=''3438480''>drawn</span>
  <span m=''3438810''>here</span> <span m=''3439290''>sort of</span> <span m=''3439350''>three</span>
  <span m=''3439760''>of</span> <span m=''3439860''>the</span> <span m=''3439970''>possible</span>
  <span m=''3440950''>patterns</span> <span m=''3441270''>you</span> <span m=''3441380''>could</span>
  <span m=''3441500''>have.</span> </p><p><span m=''3441920''>Here</span> <span m=''3442180''>I</span>
  <span m=''3442220''>have</span> <span m=''3442390''>one</span> <span m=''3442630''>truth</span>
  <span m=''3442880''>and two</span> <span m=''3443120''>false.</span> <span m=''3443530''>That</span>
  <span m=''3443790''>folds</span> <span m=''3444050''>flat.</span> <span m=''3445150''>Here</span>
  <span m=''3445410''>I</span> <span m=''3445460''>have</span> <span m=''3446840''>three</span>
  <span m=''3447150''>false.</span> <span m=''3448140''>And</span> <span m=''3448340''>here</span>
  <span m=''3448510''>I</span> <span m=''3448560''>have</span> <span m=''3448990''>two</span>
  <span m=''3449150''>true</span> <span m=''3449730''>and</span> <span m=''3449890''>one</span>
  <span m=''3450060''>false.</span> <span m=''3450330''>This</span> <span m=''3450520''>also</span>
  <span m=''3450780''>folds</span> <span m=''3451070''>flat.</span> <span m=''3452240''>In</span>
  <span m=''3452400''>all</span> <span m=''3452700''>cases,</span> <span m=''3455110''>this</span>
  <span m=''3455410''>is</span> <span m=''3455520''>what</span> <span m=''3455680''>the</span>
  <span m=''3456040''>folded state</span> <span m=''3456390''>looks</span> <span m=''3456680''>like.</span>
  <span m=''3457620''>I</span> <span m=''3457890''>maybe</span> <span m=''3458100''>never</span>
  <span m=''3458340''>mentioned</span> <span m=''3458630''>this.</span> <span m=''3458810''>But</span>
  <span m=''3458900''>this</span> <span m=''3459050''>is</span> <span m=''3459180''>an</span>
  <span m=''3459260''>important</span> <span m=''3460060''>concept.</span> <span m=''3460570''>If</span>
  <span m=''3460700''>you</span> <span m=''3460820''>take</span> <span m=''3461530''>a</span>
  <span m=''3461630''>crease</span> <span m=''3461880''>pattern</span> <span m=''3463550''>and</span>
  <span m=''3463720''>you</span> <span m=''3463800''>say</span> <span m=''3464100''>I</span>
  <span m=''3464200''>want</span> <span m=''3464390''>to</span> <span m=''3464430''>fold</span>
  <span m=''3464660''>it</span> <span m=''3464740''>flat,</span> <span m=''3465290''>you</span>
  <span m=''3465460''>can</span> <span m=''3465660''>tell</span> <span m=''3466430''>where</span>
  <span m=''3466980''>all</span> <span m=''3467200''>the</span> <span m=''3467290''>stuff</span>
  <span m=''3467590''>is</span> <span m=''3467710''>going</span> <span m=''3467840''>to</span>
  <span m=''3467910''>go</span> <span m=''3468710''>in</span> <span m=''3468830''>terms</span>
  <span m=''3469050''>of</span> <span m=''3469140''>geometry.</span> <span m=''3469900''>What</span>
  <span m=''3470040''>you</span> <span m=''3470140''>can''t</span> <span m=''3470410''>tell</span>
  <span m=''3470610''>is</span> <span m=''3470700''>the</span> <span m=''3470780''>layer</span>
  <span m=''3471030''>ordering.</span> <span m=''3471730''>That</span> <span m=''3471890''>depends</span>
  <span m=''3472170''>on</span> <span m=''3472210''>the</span> <span m=''3472270''>mountain</span>
  <span m=''3472490''>valley</span> <span m=''3472750''>assignment.</span> <span m=''3473190''>That</span>
  <span m=''3473320''>depends</span> <span m=''3473660''>on</span> <span m=''3473830''>how</span>
  <span m=''3474010''>you</span> <span m=''3474140''>decide the</span> <span m=''3474480''>layers
  to</span> <span m=''3474740''>stack.</span> </p><p><span m=''3475670''>But</span>
  <span m=''3475780''>you</span> <span m=''3475920''>can</span> <span m=''3476070''>tell</span>
  <span m=''3476380''>already</span> <span m=''3476760''>where</span> <span m=''3476930''>everything</span>
  <span m=''3477340''>goes</span> <span m=''3477580''>in</span> <span m=''3477650''>the</span>
  <span m=''3477730''>plane.</span> <span m=''3478990''>Because</span> <span m=''3479510''>you</span>
  <span m=''3479660''>pick,</span> <span m=''3480150''>let''s see, did</span> <span
  m=''3480540''>anything</span> <span m=''3480940''>stay</span> <span m=''3481180''>fixed</span>
  <span m=''3481580''>here.</span> <span m=''3483070''>Yeah,</span> <span m=''3483280''>the</span>
  <span m=''3483390''>triangle</span> <span m=''3484290''>stayed</span> <span m=''3484530''>fix.</span>
  <span m=''3484850''>So you</span> <span m=''3485090''>pick</span> <span m=''3485440''>some</span>
  <span m=''3485700''>face to</span> <span m=''3486030''>stay</span> <span m=''3486260''>fixed,</span>
  <span m=''3486570''>like</span> <span m=''3486710''>that</span> <span m=''3486880''>center</span>
  <span m=''3487100''>triangle.</span> <span m=''3487840''>You</span> <span m=''3487920''>put</span>
  <span m=''3488070''>it</span> <span m=''3488160''>there.</span> <span m=''3488370''>And</span>
  <span m=''3488460''>then</span> <span m=''3488550''>you</span> <span m=''3488610''>say,</span>
  <span m=''3488960''>OK.</span> <span m=''3489900''>Well,</span> <span m=''3490130''>where</span>
  <span m=''3490280''>is</span> <span m=''3490390''>this</span> <span m=''3490570''>flap?</span>
  <span m=''3491070''>Where is</span> <span m=''3491220''>this</span> <span m=''3491770''>face</span>
  <span m=''3492220''>of</span> <span m=''3492360''>the</span> <span m=''3492430''>crease</span>
  <span m=''3492630''>pattern</span> <span m=''3492910''>going to</span> <span m=''3493000''>go?</span>
  <span m=''3493920''>Well,</span> <span m=''3494760''>it</span> <span m=''3494890''>gets</span>
  <span m=''3495070''>reflected</span> <span m=''3495690''>through</span> <span m=''3495850''>that</span>
  <span m=''3496010''>horizontal</span> <span m=''3496560''>line.</span> <span m=''3497620''>So</span>
  <span m=''3497770''>it</span> <span m=''3497890''>goes</span> <span m=''3498320''>here.</span>
  <span m=''3499740''>And</span> <span m=''3499780''>you</span> <span m=''3499890''>can</span>
  <span m=''3499990''>just</span> <span m=''3500170''>keep</span> <span m=''3500370''>playing</span>
  <span m=''3500620''>this</span> <span m=''3500750''>reflection</span> <span m=''3501270''>game.</span>
  <span m=''3501540''>Because</span> <span m=''3501740''>you know</span> <span m=''3502045''>every</span>
  <span m=''3502350''>crease</span> <span m=''3503040''>geometrically,</span> <span
  m=''3504140''>it''s</span> <span m=''3504360''>a</span> <span m=''3504410''>reflection.</span>
  <span m=''3504830''>It</span> <span m=''3504900''>could</span> <span m=''3505010''>be
  a</span> <span m=''3505120''>reflection</span> <span m=''3505460''>this</span> <span
  m=''3505620''>way or</span> <span m=''3505840''>this</span> <span m=''3506050''>way.</span>
  <span m=''3506840''>But</span> <span m=''3507010''>it</span> <span m=''3507110''>just,</span>
  <span m=''3507730''>as</span> <span m=''3507910''>soon</span> <span m=''3508150''>as</span>
  <span m=''3508220''>you</span> <span m=''3508320''>cross</span> <span m=''3508600''>a</span>
  <span m=''3508660''>crease,</span> <span m=''3508900''>you</span> <span m=''3509010''>end</span>
  <span m=''3509120''>up</span> <span m=''3509230''>reflecting</span> <span m=''3510240''>your</span>
  <span m=''3510370''>material.</span> </p><p><span m=''3511320''>And</span> <span
  m=''3511460''>so</span> <span m=''3511540''>you</span> <span m=''3511670''>can</span>
  <span m=''3511800''>draw</span> <span m=''3512020''>this</span> <span m=''3512200''>picture</span>
  <span m=''3512970''>without</span> <span m=''3513330''>knowing</span> <span m=''3513670''>anything</span>
  <span m=''3514020''>about</span> <span m=''3514380''>how</span> <span m=''3514570''>it''s</span>
  <span m=''3514720''>folded.</span> <span m=''3515495''>Just</span> <span m=''3515770''>if</span>
  <span m=''3515910''>there''s</span> <span m=''3516060''>a</span> <span m=''3516110''>flat</span>
  <span m=''3516360''>folding,</span> <span m=''3516580''>it''s</span> <span m=''3516700''>got</span>
  <span m=''3516840''>to</span> <span m=''3516890''>look</span> <span m=''3517080''>like</span>
  <span m=''3517230''>this.</span> <span m=''3517430''>And</span> <span m=''3517590''>the</span>
  <span m=''3517770''>annoying</span> <span m=''3518090''>thing</span> <span m=''3518360''>about</span>
  <span m=''3518680''>this</span> <span m=''3518880''>set</span> <span m=''3519080''>up,</span>
  <span m=''3519960''>because</span> <span m=''3520600''>that</span> <span m=''3520810''>angle</span>
  <span m=''3521090''>up</span> <span m=''3521170''>there</span> <span m=''3521350''>is</span>
  <span m=''3521610''>35</span> <span m=''3522080''>degrees,</span> <span m=''3523690''>these</span>
  <span m=''3523930''>guys</span> <span m=''3524190''>are</span> <span m=''3524260''>going</span>
  <span m=''3524410''>to</span> <span m=''3524790''>overlap</span> <span m=''3525510''>in</span>
  <span m=''3525680''>this</span> <span m=''3525920''>common</span> <span m=''3526580''>center.</span>
  <span m=''3527990''>And</span> <span m=''3528320''>in</span> <span m=''3528480''>this</span>
  <span m=''3528630''>situation</span> <span m=''3529170''>where</span> <span m=''3529280''>it''s</span>
  <span m=''3529390''>all</span> <span m=''3529600''>false</span> <span m=''3530020''>or</span>
  <span m=''3530170''>all</span> <span m=''3530340''>true,</span> <span m=''3531510''>you</span>
  <span m=''3531640''>get</span> <span m=''3531780''>an</span> <span m=''3531870''>intersection</span>
  <span m=''3532430''>there.</span> <span m=''3534210''>It''s</span> <span m=''3534330''>a</span>
  <span m=''3534380''>little</span> <span m=''3534620''>tricky</span> <span m=''3534890''>to</span>
  <span m=''3534970''>prove.</span> <span m=''3535330''>And you''ve</span> <span m=''3535420''>just</span>
  <span m=''3535610''>got</span> <span m=''3535730''>to</span> <span m=''3535800''>fiddle</span>
  <span m=''3536080''>with</span> <span m=''3536220''>one.</span> <span m=''3536470''>I</span>
  <span m=''3536520''>should</span> <span m=''3536680''>have</span> <span m=''3536770''>brought</span>
  <span m=''3536950''>one,</span> <span m=''3537250''>but</span> <span m=''3539410''>that</span>
  <span m=''3539750''>is</span> <span m=''3540830''>true.</span> <span m=''3541620''>And</span>
  <span m=''3541740''>so</span> <span m=''3541870''>in</span> <span m=''3541950''>the</span>
  <span m=''3542010''>all</span> <span m=''3542200''>false</span> <span m=''3542560''>and</span>
  <span m=''3542710''>symmetrically</span> <span m=''3542990''>the</span> <span m=''3543270''>all</span>
  <span m=''3543450''>true</span> <span m=''3543650''>case,</span> <span m=''3544170''>this</span>
  <span m=''3544320''>thing</span> <span m=''3544470''>does</span> <span m=''3544620''>not</span>
  <span m=''3544840''>fold</span> <span m=''3545000''>flat.</span> <span m=''3545520''>In</span>
  <span m=''3545750''>all</span> <span m=''3545920''>the</span> <span m=''3546020''>other</span>
  <span m=''3546170''>situations,</span> <span m=''3546730''>it</span> <span m=''3546890''>folds</span>
  <span m=''3547150''>fine.</span> <span m=''3547430''>Because</span> <span m=''3547590''>the</span>
  <span m=''3547680''>layers</span> <span m=''3547940''>get</span> <span m=''3548070''>out</span>
  <span m=''3548200''>of</span> <span m=''3548260''>the</span> <span m=''3548340''>way.</span>
  </p><p><span m=''3550640''>OK,</span> <span m=''3551220''>also</span> <span m=''3551700''>over</span>
  <span m=''3551860''>here,</span> <span m=''3552100''>and</span> <span m=''3552210''>there''s
  a</span> <span m=''3552390''>bunch</span> <span m=''3552710''>of</span> <span m=''3552780''>these</span>
  <span m=''3552950''>in</span> <span m=''3553040''>the</span> <span m=''3553130''>book,</span>
  <span m=''3553860''>are</span> <span m=''3554030''>little</span> <span m=''3554300''>analyses</span>
  <span m=''3554830''>of</span> <span m=''3554950''>which</span> <span m=''3555230''>of</span>
  <span m=''3555370''>the</span> <span m=''3555820''>creases</span> <span m=''3556210''>have</span>
  <span m=''3556380''>to</span> <span m=''3556470''>have</span> <span m=''3556580''>the</span>
  <span m=''3556670''>same</span> <span m=''3557760''>mountain</span> <span m=''3558000''>valley</span>
  <span m=''3558290''>assignment and</span> <span m=''3558640''>which</span> <span
  m=''3558850''>have</span> <span m=''3558990''>to</span> <span m=''3559070''>have</span>
  <span m=''3559230''>different.</span> <span m=''3560210''>That''s</span> <span m=''3560400''>actually</span>
  <span m=''3560650''>how</span> <span m=''3561020''>these</span> <span m=''3561210''>patterns</span>
  <span m=''3561580''>are</span> <span m=''3561650''>drawn.</span> <span m=''3562780''>This</span>
  <span m=''3562970''>is</span> <span m=''3563120''>from</span> <span m=''3563300''>our</span>
  <span m=''3563440''>old</span> <span m=''3564290''>local</span> <span m=''3564740''>analysis</span>
  <span m=''3565270''>of</span> <span m=''3565410''>a</span> <span m=''3565680''>single</span>
  <span m=''3565970''>vertex</span> <span m=''3566340''>crease</span> <span m=''3566520''>pattern,</span>
  <span m=''3567350''>right.</span> <span m=''3567520''>You''ve</span> <span m=''3567650''>got</span>
  <span m=''3567880''>these</span> <span m=''3568150''>four</span> <span m=''3568390''>creases.</span>
  <span m=''3569420''>Check</span> <span m=''3569630''>it</span> <span m=''3569700''>out.</span>
  <span m=''3569940''>The</span> <span m=''3570100''>only</span> <span m=''3570380''>one</span>
  <span m=''3570550''>that</span> <span m=''3570630''>could</span> <span m=''3570790''>be</span>
  <span m=''3570900''>crimped</span> <span m=''3571730''>is</span> <span m=''3571930''>this</span>
  <span m=''3572100''>one.</span> <span m=''3573210''>Because</span> <span m=''3573420''>it''s</span>
  <span m=''3573710''>globally</span> <span m=''3574180''>smallest.</span> <span m=''3574710''>All</span>
  <span m=''3574830''>the</span> <span m=''3574950''>other</span> <span m=''3575100''>guys</span>
  <span m=''3576112''>have</span> <span m=''3576460''>a</span> <span m=''3576510''>bigger</span>
  <span m=''3576770''>neighbor</span> <span m=''3578540''>or</span> <span m=''3579080''>are</span>
  <span m=''3579220''>in</span> <span m=''3579340''>trouble.</span> <span m=''3580090''>So</span>
  <span m=''3580360''>this</span> <span m=''3580580''>guy</span> <span m=''3580700''>has</span>
  <span m=''3580970''>to</span> <span m=''3581050''>be crimped.</span> <span m=''3581340''>So</span>
  <span m=''3581480''>these</span> <span m=''3581750''>two</span> <span m=''3582020''>are</span>
  <span m=''3582230''>not</span> <span m=''3582450''>equal.</span> <span m=''3583890''>And</span>
  <span m=''3584020''>therefore,</span> <span m=''3584290''>these</span> <span m=''3584520''>two</span>
  <span m=''3584660''>must</span> <span m=''3584860''>be</span> <span m=''3585030''>equal.</span>
  <span m=''3585490''>And</span> <span m=''3585680''>that''s</span> <span m=''3585820''>symmetrical</span>
  <span m=''3586195''>all the way</span> <span m=''3586570''>around.</span> </p><p><span
  m=''3587590''>So in</span> <span m=''3587680''>fact,</span> <span m=''3587940''>you</span>
  <span m=''3588000''>know</span> <span m=''3588120''>that</span> <span m=''3588300''>this</span>
  <span m=''3588550''>crease</span> <span m=''3588920''>is</span> <span m=''3589120''>different</span>
  <span m=''3589420''>from</span> <span m=''3589540''>this</span> <span m=''3589720''>one,</span>
  <span m=''3589930''>is</span> <span m=''3590070''>equal</span> <span m=''3590360''>to</span>
  <span m=''3590470''>this</span> <span m=''3590660''>one.</span> <span m=''3591530''>You</span>
  <span m=''3591640''>already</span> <span m=''3591840''>knew</span> <span m=''3591960''>that
  these</span> <span m=''3592240''>two</span> <span m=''3592360''>are</span> <span
  m=''3592430''>different.</span> <span m=''3592930''>So</span> <span m=''3593030''>that''s</span>
  <span m=''3593170''>OK.</span> <span m=''3595030''>So</span> <span m=''3595180''>you</span>
  <span m=''3595320''>can</span> <span m=''3595590''>figure</span> <span m=''3595990''>out</span>
  <span m=''3596270''>these</span> <span m=''3596470''>crease</span> <span m=''3596700''>patterns.</span>
  <span m=''3597760''>There''s</span> <span m=''3598200''>a</span> <span m=''3598270''>little</span>
  <span m=''3598490''>bit</span> <span m=''3598600''>of</span> <span m=''3598670''>flexi--</span>
  <span m=''3599260''>once</span> <span m=''3599450''>you</span> <span m=''3599530''>have</span>
  <span m=''3599950''>the</span> <span m=''3600940''>mountains</span> <span m=''3601240''>and</span>
  <span m=''3601330''>valleys</span> <span m=''3601690''>coming</span> <span m=''3601980''>in,</span>
  <span m=''3602450''>you know how</span> <span m=''3602880''>the</span> <span m=''3602960''>mountains</span>
  <span m=''3603240''>and</span> <span m=''3603320''>valleys</span> <span m=''3603560''>have</span>
  <span m=''3603830''>to</span> <span m=''3603910''>be</span> <span m=''3604020''>in</span>
  <span m=''3604100''>the</span> <span m=''3604170''>center.</span> <span m=''3604840''>Just</span>
  <span m=''3605180''>makes</span> <span m=''3605450''>life</span> <span m=''3605650''>easier.</span>
  <span m=''3606580''>There''s</span> <span m=''3606740''>only</span> <span m=''3606860''>one</span>
  <span m=''3607160''>mountain</span> <span m=''3607410''>valley</span> <span m=''3607690''>assignment</span>
  <span m=''3607890''>you</span> <span m=''3607940''>need</span> <span m=''3608190''>to</span>
  <span m=''3608260''>consider.</span> <span m=''3609150''>And</span> <span m=''3609290''>the</span>
  <span m=''3609360''>symmetric</span> <span m=''3609820''>one</span> <span m=''3610100''>turns</span>
  <span m=''3610330''>out</span> <span m=''3610450''>to</span> <span m=''3610520''>be</span>
  <span m=''3610630''>bad.</span> </p><p><span m=''3612720''>So</span> <span m=''3612950''>that''s</span>
  <span m=''3613410''>two</span> <span m=''3614210''>gadgets.</span> <span m=''3614580''>We</span>
  <span m=''3614640''>got</span> <span m=''3614790''>the</span> <span m=''3614890''>wire,</span>
  <span m=''3615820''>the not</span> <span m=''3615940''>all</span> <span m=''3616190''>equal</span>
  <span m=''3616380''>clause.</span> <span m=''3617520''>Of</span> <span m=''3617560''>course,</span>
  <span m=''3619330''>if</span> <span m=''3619490''>we''re</span> <span m=''3619580''>lucky,</span>
  <span m=''3619990''>all the wires</span> <span m=''3620420''>will</span> <span m=''3620540''>just</span>
  <span m=''3620910''>meet</span> <span m=''3621160''>at</span> <span m=''3621270''>the</span>
  <span m=''3621360''>right</span> <span m=''3621590''>points.</span> <span m=''3621870''>But</span>
  <span m=''3621980''>I''m</span> <span m=''3622090''>going</span> <span m=''3622180''>to</span>
  <span m=''3622220''>need</span> <span m=''3622380''>many</span> <span m=''3622570''>copies</span>
  <span m=''3622930''>of</span> <span m=''3623000''>them.</span> <span m=''3623210''>I''ve</span>
  <span m=''3623250''>got</span> <span m=''3623400''>to</span> <span m=''3623450''>move
  them</span> <span m=''3623630''>around</span> <span m=''3624430''>to</span> <span
  m=''3624710''>reach</span> <span m=''3624890''>all</span> <span m=''3625090''>the</span>
  <span m=''3625170''>different</span> <span m=''3626180''>clauses,</span> <span m=''3627200''>all</span>
  <span m=''3627380''>the</span> <span m=''3627460''>different</span> <span m=''3627720''>triples.</span>
  <span m=''3629050''>So</span> <span m=''3629270''>next</span> <span m=''3629540''>up</span>
  <span m=''3630270''>is</span> <span m=''3630450''>reflector.</span> <span m=''3637560''>This</span>
  <span m=''3637720''>is</span> <span m=''3637830''>actually</span> <span m=''3638290''>in
  some</span> <span m=''3638340''>sense</span> <span m=''3638970''>really</span> <span
  m=''3639200''>easy.</span> <span m=''3640320''>So</span> <span m=''3640780''>we</span>
  <span m=''3640910''>have,</span> <span m=''3642680''>here''s</span> <span m=''3642930''>our</span>
  <span m=''3643050''>input.</span> <span m=''3644700''>What</span> <span m=''3644890''>the</span>
  <span m=''3644960''>reflector</span> <span m=''3645420''>is</span> <span m=''3645500''>going</span>
  <span m=''3645610''>to</span> <span m=''3645690''>do</span> <span m=''3645800''>is
  it''s</span> <span m=''3646000''>going</span> <span m=''3646120''>to</span> <span
  m=''3646180''>make</span> <span m=''3646370''>two</span> <span m=''3646550''>copies,</span>
  <span m=''3647630''>one</span> <span m=''3647810''>down</span> <span m=''3648030''>here</span>
  <span m=''3648590''>which</span> <span m=''3648870''>is</span> <span m=''3649170''>negated,</span>
  <span m=''3650350''>and</span> <span m=''3650540''>one</span> <span m=''3650700''>up</span>
  <span m=''3650850''>here,</span> <span m=''3651200''>which</span> <span m=''3651330''>is</span>
  <span m=''3651470''>the</span> <span m=''3651580''>same</span> <span m=''3651860''>value.</span>
  <span m=''3654190''>And</span> <span m=''3654430''>it</span> <span m=''3654500''>also</span>
  <span m=''3654800''>effectively</span> <span m=''3655230''>turns</span> <span m=''3655520''>the</span>
  <span m=''3655600''>signal</span> <span m=''3655930''>two</span> <span m=''3656140''>different</span>
  <span m=''3656410''>directions.</span> </p><p><span m=''3658400''>So</span> <span
  m=''3658520''>to</span> <span m=''3658620''>see</span> <span m=''3658860''>why</span>
  <span m=''3659040''>it</span> <span m=''3659110''>works</span> <span m=''3661060''>is</span>
  <span m=''3661280''>actually</span> <span m=''3661540''>pretty</span> <span m=''3661730''>easy.</span>
  <span m=''3662100''>It''s</span> <span m=''3662120''>just</span> <span m=''3662280''>a</span>
  <span m=''3662360''>local</span> <span m=''3662700''>analysis</span> <span m=''3663170''>again.</span>
  <span m=''3664400''>You</span> <span m=''3664550''>look</span> <span m=''3664700''>at</span>
  <span m=''3664760''>this</span> <span m=''3664920''>vertex.</span> <span m=''3665710''>This</span>
  <span m=''3665920''>is</span> <span m=''3666040''>the</span> <span m=''3666190''>only</span>
  <span m=''3666960''>increase</span> <span m=''3667270''>they</span> <span m=''3667360''>could</span>
  <span m=''3667520''>be</span> <span m=''3667620''>crimped.</span> <span m=''3668270''>So</span>
  <span m=''3668440''>we</span> <span m=''3668530''>know</span> <span m=''3668680''>that</span>
  <span m=''3668820''>these</span> <span m=''3669090''>two</span> <span m=''3669390''>guys</span>
  <span m=''3669690''>have</span> <span m=''3669850''>opposite</span> <span m=''3670240''>assignment.</span>
  <span m=''3672120''>Therefore,</span> <span m=''3673160''>these</span> <span m=''3673410''>two</span>
  <span m=''3673570''>wires</span> <span m=''3674090''>will</span> <span m=''3674200''>have</span>
  <span m=''3674390''>opposite</span> <span m=''3674850''>value.</span> <span m=''3676290''>And</span>
  <span m=''3676440''>actually,</span> <span m=''3676860''>they</span> <span m=''3676950''>have</span>
  <span m=''3677100''>the</span> <span m=''3677180''>same</span> <span m=''3677430''>value</span>
  <span m=''3677730''>if</span> <span m=''3677810''>they''re</span> <span m=''3677930''>pointing</span>
  <span m=''3678230''>in</span> <span m=''3678310''>the</span> <span m=''3678380''>same</span>
  <span m=''3678560''>direction.</span> <span m=''3679390''>But</span> <span m=''3679600''>they''ll</span>
  <span m=''3679650''>have</span> <span m=''3679840''>opposite</span> <span m=''3680250''>value</span>
  <span m=''3680600''>because</span> <span m=''3681560''>I</span> <span m=''3681680''>decided</span>
  <span m=''3682170''>this</span> <span m=''3682310''>one''s</span> <span m=''3682490''>pointing</span>
  <span m=''3682790''>down.</span> <span m=''3684750''>So if</span> <span m=''3684950''>this</span>
  <span m=''3685120''>one''s</span> <span m=''3685300''>a</span> <span m=''3685340''>mountain,</span>
  <span m=''3685730''>this</span> <span m=''3685880''>one</span> <span m=''3685990''>has</span>
  <span m=''3686230''>to</span> <span m=''3686310''>be</span> <span m=''3686430''>a</span>
  <span m=''3686450''>valley.</span> <span m=''3687060''>And</span> <span m=''3687340''>so</span>
  <span m=''3687760''>if</span> <span m=''3688140''>this</span> <span m=''3688340''>is</span>
  <span m=''3688460''>true</span> <span m=''3688710''>because</span> <span m=''3688870''>it''s</span>
  <span m=''3688990''>valley</span> <span m=''3689240''>on</span> <span m=''3689310''>the</span>
  <span m=''3689380''>left,</span> <span m=''3689650''>this</span> <span m=''3689800''>one''s</span>
  <span m=''3689960''>false</span> <span m=''3690280''>because</span> <span m=''3690420''>it''s</span>
  <span m=''3690570''>mountain</span> <span m=''3690890''>on</span> <span m=''3690990''>the</span>
  <span m=''3691070''>left.</span> </p><p><span m=''3693286''>OK,</span> <span m=''3693720''>and</span>
  <span m=''3694110''>then</span> <span m=''3694240''>you</span> <span m=''3694350''>can</span>
  <span m=''3694480''>do</span> <span m=''3694560''>the</span> <span m=''3694650''>same</span>
  <span m=''3694870''>thing.</span> <span m=''3695030''>Then</span> <span m=''3695160''>you</span>
  <span m=''3695280''>also</span> <span m=''3695510''>know</span> <span m=''3695680''>these</span>
  <span m=''3695930''>two</span> <span m=''3696090''>guys</span> <span m=''3696360''>are</span>
  <span m=''3696470''>equal.</span> <span m=''3697520''>And</span> <span m=''3697950''>because</span>
  <span m=''3698450''>again,</span> <span m=''3698790''>this</span> <span m=''3698950''>is</span>
  <span m=''3699030''>the</span> <span m=''3699140''>only</span> <span m=''3699340''>crimpable</span>
  <span m=''3699780''>pair</span> <span m=''3700040''>here,</span> <span m=''3700650''>these</span>
  <span m=''3700940''>two</span> <span m=''3701100''>creases</span> <span m=''3701480''>are</span>
  <span m=''3701560''>not</span> <span m=''3701750''>equal.</span> <span m=''3702730''>And</span>
  <span m=''3703120''>so you know</span> <span m=''3703500''>these</span> <span m=''3703760''>two</span>
  <span m=''3703860''>guys</span> <span m=''3704120''>are</span> <span m=''3704190''>equal</span>
  <span m=''3704500''>and</span> <span m=''3704540''>these</span> <span m=''3704720''>two</span>
  <span m=''3704820''>guys</span> <span m=''3705040''>are</span> <span m=''3705090''>equal.</span>
  <span m=''3705690''>And</span> <span m=''3705910''>so</span> <span m=''3706010''>you</span>
  <span m=''3706140''>know</span> <span m=''3706350''>that</span> <span m=''3706920''>this</span>
  <span m=''3709800''>valley</span> <span m=''3710200''>is</span> <span m=''3710330''>propagated</span>
  <span m=''3710810''>up</span> <span m=''3710940''>there.</span> <span m=''3711130''>And</span>
  <span m=''3711210''>therefore,</span> <span m=''3711470''>these</span> <span m=''3711690''>two</span>
  <span m=''3712240''>wires</span> <span m=''3712530''>have</span> <span m=''3712640''>the</span>
  <span m=''3712710''>same</span> <span m=''3712910''>value.</span> <span m=''3713560''>So</span>
  <span m=''3713700''>you''ve</span> <span m=''3713810''>split</span> <span m=''3714180''>the</span>
  <span m=''3714270''>signal.</span> <span m=''3714610''>You''ve</span> <span m=''3714740''>made</span>
  <span m=''3714960''>a</span> <span m=''3715030''>positive</span> <span m=''3715480''>copy</span>
  <span m=''3715940''>and a</span> <span m=''3716150''>negated</span> <span m=''3716560''>copy.</span>
  <span m=''3717790''>And</span> <span m=''3717950''>if</span> <span m=''3718030''>you</span>
  <span m=''3718120''>just</span> <span m=''3718260''>do</span> <span m=''3718370''>this</span>
  <span m=''3718520''>again,</span> <span m=''3719530''>you''ll</span> <span m=''3719740''>get--</span>
  <span m=''3722620''>this</span> <span m=''3722810''>will</span> <span m=''3722930''>make</span>
  <span m=''3723800''>another</span> <span m=''3724140''>negated</span> <span m=''3724520''>copy</span>
  <span m=''3724990''>and</span> <span m=''3725740''>a</span> <span m=''3726000''>positive</span>
  <span m=''3726520''>copy.</span> </p><p><span m=''3727460''>So</span> <span m=''3727570''>I</span>
  <span m=''3727640''>get</span> <span m=''3727800''>two</span> <span m=''3727920''>positive</span>
  <span m=''3728290''>copies</span> <span m=''3728620''>and</span> <span m=''3728690''>a</span>
  <span m=''3728840''>negated</span> <span m=''3729090''>one.</span> <span m=''3729250''>You</span>
  <span m=''3729340''>can</span> <span m=''3729450''>just</span> <span m=''3729600''>keep</span>
  <span m=''3729780''>doing</span> <span m=''3730010''>this</span> <span m=''3730200''>and
  you''ll</span> <span m=''3730290''>get</span> <span m=''3730480''>tons</span> <span
  m=''3730710''>of</span> <span m=''3730790''>positive</span> <span m=''3731140''>copies,</span>
  <span m=''3731510''>tons of</span> <span m=''3731800''>negative</span> <span m=''3732100''>copies.</span>
  <span m=''3733230''>So</span> <span m=''3733420''>it</span> <span m=''3733480''>doesn''t</span>
  <span m=''3733680''>even</span> <span m=''3733810''>matter</span> <span m=''3734090''>if</span>
  <span m=''3734180''>it''s</span> <span m=''3734290''>all</span> <span m=''3734440''>positive.</span>
  <span m=''3734940''>But</span> <span m=''3735330''>if you</span> <span m=''3735430''>take</span>
  <span m=''3735620''>all</span> <span m=''3735770''>positive</span> <span m=''3736140''>ones.</span>
  <span m=''3736500''>Let</span> <span m=''3736530''>the</span> <span m=''3736640''>others</span>
  <span m=''3736960''>go</span> <span m=''3737060''>off</span> <span m=''3737210''>to</span>
  <span m=''3737300''>infinity.</span> <span m=''3738160''>And</span> <span m=''3738700''>now</span>
  <span m=''3738840''>you</span> <span m=''3738960''>want</span> <span m=''3739100''>to</span>
  <span m=''3739140''>move</span> <span m=''3739330''>around</span> <span m=''3740350''>so</span>
  <span m=''3740580''>that</span> <span m=''3740760''>they</span> <span m=''3741430''>hit</span>
  <span m=''3741710''>those</span> <span m=''3741920''>not</span> <span m=''3742090''>all</span>
  <span m=''3742250''>equal</span> <span m=''3742490''>clauses.</span> <span m=''3743470''>How</span>
  <span m=''3743640''>do</span> <span m=''3743710''>I</span> <span m=''3743780''>move</span>
  <span m=''3743960''>them</span> <span m=''3744070''>around?</span> <span m=''3744390''>I</span>
  <span m=''3744450''>just</span> <span m=''3744640''>use</span> <span m=''3744800''>more</span>
  <span m=''3745130''>reflectors.</span> <span m=''3746040''>If</span> <span m=''3746430''>I</span>
  <span m=''3746500''>come</span> <span m=''3746800''>in</span> <span m=''3746890''>at</span>
  <span m=''3747000''>some</span> <span m=''3747200''>angle,</span> <span m=''3747910''>I</span>
  <span m=''3748040''>can</span> <span m=''3748210''>now</span> <span m=''3748480''>turn</span>
  <span m=''3749030''>by</span> <span m=''3749230''>however</span> <span m=''3749570''>much</span>
  <span m=''3749840''>that</span> <span m=''3750050''>is.</span> <span m=''3750470''>Or
  I</span> <span m=''3750590''>can</span> <span m=''3750800''>turn</span> <span m=''3751040''>by</span>
  <span m=''3751160''>however</span> <span m=''3751400''>much</span> <span m=''3751600''>that</span>
  <span m=''3751850''>is.</span> <span m=''3752700''>I''m</span> <span m=''3752770''>not</span>
  <span m=''3752910''>going</span> <span m=''3753010''>to</span> <span m=''3753090''>try</span>
  <span m=''3753280''>to</span> <span m=''3753810''>figure</span> <span m=''3754040''>out</span>
  <span m=''3754130''>what</span> <span m=''3754240''>those</span> <span m=''3754410''>angles</span>
  <span m=''3754670''>are.</span> <span m=''3755030''>But</span> <span m=''3755300''>it</span>
  <span m=''3755390''>turns</span> <span m=''3755630''>out,</span> <span m=''3755780''>this</span>
  <span m=''3755950''>is</span> <span m=''3756060''>enough</span> <span m=''3757180''>to</span>
  <span m=''3757310''>make</span> <span m=''3757500''>everything</span> <span m=''3758150''>work.</span>
  </p><p><span m=''3760130''>The</span> <span m=''3760250''>last</span> <span m=''3760550''>thing</span>
  <span m=''3760660''>you</span> <span m=''3760740''>need</span> <span m=''3760920''>are</span>
  <span m=''3761000''>a</span> <span m=''3761040''>bunch</span> <span m=''3761300''>of</span>
  <span m=''3761400''>crossover</span> <span m=''3761860''>gadgets.</span> <span m=''3762290''>This</span>
  <span m=''3762470''>is</span> <span m=''3762570''>one</span> <span m=''3762770''>of</span>
  <span m=''3762840''>them.</span> <span m=''3763020''>There''s</span> <span m=''3763140''>a</span>
  <span m=''3763210''>second</span> <span m=''3763500''>one.</span> <span m=''3764660''>I''ll</span>
  <span m=''3764850''>just</span> <span m=''3765050''>wave</span> <span m=''3765230''>my</span>
  <span m=''3765350''>hands</span> <span m=''3765620''>and</span> <span m=''3765720''>say,</span>
  <span m=''3765920''>if</span> <span m=''3766010''>you</span> <span m=''3766100''>take</span>
  <span m=''3766310''>two</span> <span m=''3766450''>pleats</span> <span m=''3766900''>in</span>
  <span m=''3767000''>the</span> <span m=''3767120''>obvious</span> <span m=''3767480''>way,</span>
  <span m=''3768500''>they</span> <span m=''3768880''>really</span> <span m=''3769170''>don''t</span>
  <span m=''3769370''>care</span> <span m=''3769600''>about</span> <span m=''3769790''>each</span>
  <span m=''3770000''>other.</span> <span m=''3770590''>Because</span> <span m=''3771210''>the</span>
  <span m=''3771440''>way</span> <span m=''3771600''>to</span> <span m=''3771670''>fold</span>
  <span m=''3771960''>this</span> <span m=''3772120''>locally,</span> <span m=''3772505''>is</span>
  <span m=''3772890''>to</span> <span m=''3772970''>fold</span> <span m=''3773900''>this</span>
  <span m=''3774080''>diagonal</span> <span m=''3774470''>pleat</span> <span m=''3774780''>and</span>
  <span m=''3774920''>then</span> <span m=''3775060''>fold</span> <span m=''3775210''>the</span>
  <span m=''3775290''>vertical</span> <span m=''3775640''>pleat.</span> <span m=''3776310''>And</span>
  <span m=''3776570''>it will</span> <span m=''3776670''>work</span> <span m=''3777010''>whether</span>
  <span m=''3777730''>one</span> <span m=''3777980''>pleat</span> <span m=''3778190''>is</span>
  <span m=''3778500''>true</span> <span m=''3778800''>or</span> <span m=''3778870''>false.</span>
  <span m=''3779300''>It doesn''t</span> <span m=''3779470''>matter</span> <span m=''3779730''>which</span>
  <span m=''3780320''>side is</span> <span m=''3780540''>valley,</span> <span m=''3780820''>which</span>
  <span m=''3781040''>side is</span> <span m=''3781190''>mountain.</span> <span m=''3781500''>It</span>
  <span m=''3781720''>always</span> <span m=''3782000''>works.</span> <span m=''3782980''>So</span>
  <span m=''3783110''>crossovers</span> <span m=''3783680''>aren''t</span> <span m=''3784170''>actually</span>
  <span m=''3784510''>that</span> <span m=''3784750''>big</span> <span m=''3784900''>a</span>
  <span m=''3784940''>deal.</span> <span m=''3786570''>Once</span> <span m=''3786750''>you</span>
  <span m=''3786840''>have</span> <span m=''3787090''>that,</span> <span m=''3787490''>you</span>
  <span m=''3787810''>take</span> <span m=''3788020''>those</span> <span m=''3788190''>gadgets.</span>
  <span m=''3788630''>And</span> <span m=''3788720''>you</span> <span m=''3788830''>put</span>
  <span m=''3789020''>them</span> <span m=''3789140''>together</span> <span m=''3789540''>into</span>
  <span m=''3789690''>a</span> <span m=''3789730''>monstrosity</span> <span m=''3790560''>of</span>
  <span m=''3790660''>a crease</span> <span m=''3790990''>pattern,</span> <span m=''3791930''>which</span>
  <span m=''3792210''>looks</span> <span m=''3792490''>something</span> <span m=''3792830''>like</span>
  <span m=''3793030''>this.</span> <span m=''3794240''>And</span> <span m=''3794520''>this</span>
  <span m=''3794670''>took</span> <span m=''3794820''>forever</span> <span m=''3795210''>to</span>
  <span m=''3795310''>draw,</span> <span m=''3795790''>I</span> <span m=''3795910''>remember.</span>
  </p><p><span m=''3797530''>So</span> <span m=''3797770''>we</span> <span m=''3797900''>have</span>
  <span m=''3798270''>on</span> <span m=''3798460''>the</span> <span m=''3798550''>left</span>
  <span m=''3798860''>side</span> <span m=''3799180''>our</span> <span m=''3799290''>variables.</span>
  <span m=''3800660''>These</span> <span m=''3800880''>are</span> <span m=''3800970''>just</span>
  <span m=''3801170''>wires.</span> <span m=''3801680''>They''re</span> <span m=''3801800''>pleats.</span>
  <span m=''3802960''>And</span> <span m=''3803150''>each</span> <span m=''3803330''>one</span>
  <span m=''3803590''>could</span> <span m=''3803740''>be</span> <span m=''3803890''>folded</span>
  <span m=''3804290''>true</span> <span m=''3804460''>or</span> <span m=''3804540''>false,</span>
  <span m=''3806080''>left over</span> <span m=''3806460''>right or</span> <span m=''3806760''>right</span>
  <span m=''3806900''>over</span> <span m=''3807070''>left.</span> <span m=''3808620''>And</span>
  <span m=''3808740''>then</span> <span m=''3808850''>I</span> <span m=''3808940''>do</span>
  <span m=''3809320''>a</span> <span m=''3809400''>whole</span> <span m=''3809570''>bunch</span>
  <span m=''3809780''>of</span> <span m=''3809870''>reflectors,</span> <span m=''3810540''>just</span>
  <span m=''3810760''>reflect,</span> <span m=''3811200''>reflect,</span> <span m=''3811600''>reflect,</span>
  <span m=''3812010''>reflect,</span> <span m=''3812420''>reflect,</span> <span m=''3812810''>just</span>
  <span m=''3812970''>to</span> <span m=''3813040''>make</span> <span m=''3813200''>a</span>
  <span m=''3813250''>whole</span> <span m=''3813380''>bunch</span> <span m=''3813590''>of</span>
  <span m=''3813660''>copies.</span> <span m=''3815940''>And</span> <span m=''3817360''>then</span>
  <span m=''3817790''>at</span> <span m=''3817980''>the</span> <span m=''3818080''>top</span>
  <span m=''3818480''>there,</span> <span m=''3819960''>way</span> <span m=''3820160''>at</span>
  <span m=''3820290''>that</span> <span m=''3820460''>little</span> <span m=''3822750''>yellow</span>
  <span m=''3823080''>triangle,</span> <span m=''3824110''>is</span> <span m=''3824290''>a</span>
  <span m=''3824350''>not</span> <span m=''3824550''>all</span> <span m=''3824720''>equal</span>
  <span m=''3824940''>clause.</span> <span m=''3825740''>And</span> <span m=''3825990''>is</span>
  <span m=''3826240''>a</span> <span m=''3826300''>not</span> <span m=''3826510''>all</span>
  <span m=''3826650''>equal</span> <span m=''3826860''>clause</span> <span m=''3827250''>between</span>
  <span m=''3828810''>x3,</span> <span m=''3829870''>where</span> <span m=''3830070''>we</span>
  <span m=''3830200''>make</span> <span m=''3830390''>a</span> <span m=''3830460''>copy.</span>
  <span m=''3831570''>Wow,</span> <span m=''3832030''>this is</span> <span m=''3832270''>crazy.</span>
  <span m=''3833080''>I</span> <span m=''3833270''>end</span> <span m=''3833440''>up</span>
  <span m=''3833580''>making</span> <span m=''3833860''>a</span> <span m=''3833940''>copy,</span>
  <span m=''3834450''>negate it</span> <span m=''3834870''>downwards,</span> <span
  m=''3835310''>and</span> <span m=''3835400''>I</span> <span m=''3835460''>flip it</span>
  <span m=''3835740''>around.</span> <span m=''3836730''>And</span> <span m=''3837030''>it
  goes</span> <span m=''3837380''>up</span> <span m=''3837810''>straight.</span> <span
  m=''3838640''>And</span> <span m=''3838810''>then</span> <span m=''3838910''>I</span>
  <span m=''3839000''>turn</span> <span m=''3839350''>it</span> <span m=''3839590''>at</span>
  <span m=''3839740''>an</span> <span m=''3839840''>angle</span> <span m=''3840200''>to</span>
  <span m=''3840260''>hit</span> <span m=''3840450''>the</span> <span m=''3840530''>triangle</span>
  <span m=''3840990''>dead</span> <span m=''3841170''>on,</span> <span m=''3841400''>the</span>
  <span m=''3841480''>way</span> <span m=''3841590''>it''s</span> <span m=''3841700''>supposed</span>
  <span m=''3842030''>to.</span> <span m=''3843450''>Then</span> <span m=''3843500''>I</span>
  <span m=''3843610''>also</span> <span m=''3844000''>take</span> <span m=''3845030''>x1</span>
  <span m=''3845730''>up</span> <span m=''3845870''>the</span> <span m=''3845960''>top,</span>
  <span m=''3846410''>just</span> <span m=''3846750''>get</span> <span m=''3846890''>a</span>
  <span m=''3846940''>copy</span> <span m=''3847270''>straight</span> <span m=''3847540''>off</span>
  <span m=''3847670''>the</span> <span m=''3847750''>top</span> <span m=''3848010''>there.</span>
  <span m=''3848590''>And</span> <span m=''3848820''>x2,</span> <span m=''3849520''>I</span>
  <span m=''3849660''>take</span> <span m=''3849910''>a</span> <span m=''3849980''>copy</span>
  <span m=''3850780''>here.</span> <span m=''3851140''>For</span> <span m=''3851270''>some</span>
  <span m=''3851460''>reason</span> <span m=''3851770''>I</span> <span m=''3851850''>feel</span>
  <span m=''3852060''>like</span> <span m=''3852230''>negating</span> <span m=''3852630''>it,
  and</span> <span m=''3852770''>turning it</span> <span m=''3853090''>around,</span>
  <span m=''3853390''>and</span> <span m=''3853480''>spitting</span> <span m=''3854040''>it</span>
  <span m=''3854540''>up</span> <span m=''3854660''>there.</span> </p><p><span m=''3855390''>And</span>
  <span m=''3855620''>then</span> <span m=''3855760''>I</span> <span m=''3855850''>turn</span>
  <span m=''3856080''>it</span> <span m=''3856180''>back</span> <span m=''3856440''>down.</span>
  <span m=''3856700''>It hits the</span> <span m=''3856900''>yellow</span> <span m=''3857130''>triangle</span>
  <span m=''3857570''>at</span> <span m=''3857790''>just</span> <span m=''3858000''>the</span>
  <span m=''3858080''>right</span> <span m=''3858260''>angle.</span> <span m=''3858990''>And</span>
  <span m=''3859070''>therefore,</span> <span m=''3859450''>if</span> <span m=''3859510''>this</span>
  <span m=''3859700''>thing''s</span> <span m=''3859900''>going</span> <span m=''3860010''>to</span>
  <span m=''3860070''>fold</span> <span m=''3860330''>flat,</span> <span m=''3860630''>it</span>
  <span m=''3860720''>must</span> <span m=''3860940''>be</span> <span m=''3861050''>that</span>
  <span m=''3861150''>x1,</span> <span m=''3861560''>x2,</span> <span m=''3861860''>and</span>
  <span m=''3861940''>x3</span> <span m=''3862340''>are</span> <span m=''3862410''>not
  all</span> <span m=''3862730''>equal.</span> <span m=''3863500''>And</span> <span
  m=''3863660''>you</span> <span m=''3863740''>just</span> <span m=''3863930''>keep</span>
  <span m=''3864120''>doing</span> <span m=''3864400''>that,</span> <span m=''3864710''>one</span>
  <span m=''3864890''>for</span> <span m=''3865040''>every</span> <span m=''3865270''>triple.</span>
  <span m=''3866480''>Remember,</span> <span m=''3866680''>we''re</span> <span m=''3866830''>given</span>
  <span m=''3867170''>as</span> <span m=''3867290''>input</span> <span m=''3868880''>one</span>
  <span m=''3869040''>of</span> <span m=''3869130''>these</span> <span m=''3869390''>not</span>
  <span m=''3869570''>all</span> <span m=''3869730''>equal</span> <span m=''3870910''>SAT</span>
  <span m=''3871410''>problems.</span> <span m=''3871880''>I</span> <span m=''3871930''>give</span>
  <span m=''3872110''>you</span> <span m=''3872190''>a</span> <span m=''3872210''>bunch</span>
  <span m=''3872420''>of</span> <span m=''3872470''>triples.</span> <span m=''3873270''>I</span>
  <span m=''3873430''>just</span> <span m=''3875020''>put</span> <span m=''3875280''>the</span>
  <span m=''3875370''>wires</span> <span m=''3875700''>together</span> <span m=''3876290''>according</span>
  <span m=''3876720''>to</span> <span m=''3876810''>those</span> <span m=''3877000''>triples.</span>
  <span m=''3877540''>This</span> <span m=''3877750''>thing</span> <span m=''3877960''>we</span>
  <span m=''3878100''>flat</span> <span m=''3878370''>foldable</span> <span m=''3878830''>if</span>
  <span m=''3878990''>and</span> <span m=''3879070''>only</span> <span m=''3879320''>if</span>
  <span m=''3879950''>this</span> <span m=''3880270''>formula</span> <span m=''3880870''>is</span>
  <span m=''3881040''>satisfiable.</span> <span m=''3883290''>You</span> <span m=''3883400''>can</span>
  <span m=''3883550''>set</span> <span m=''3883760''>the</span> <span m=''3883840''>pleats</span>
  <span m=''3884660''>so</span> <span m=''3884850''>that</span> <span m=''3885070''>the</span>
  <span m=''3885280''>desired</span> <span m=''3885790''>triples</span> <span m=''3886190''>are</span>
  <span m=''3886240''>not</span> <span m=''3886540''>equal.</span> <span m=''3887510''>So</span>
  <span m=''3887660''>that''s</span> <span m=''3887800''>pretty</span> <span m=''3888140''>crazy.</span>
  <span m=''3889260''>This</span> <span m=''3889480''>is</span> <span m=''3890010''>in</span>
  <span m=''3890320''>some</span> <span m=''3890480''>sense</span> <span m=''3890700''>one</span>
  <span m=''3890850''>of</span> <span m=''3890900''>the</span> <span m=''3890980''>hardest</span>
  <span m=''3891510''>proofs</span> <span m=''3891860''>that</span> <span m=''3891970''>we</span>
  <span m=''3892360''>will</span> <span m=''3892960''>see.</span> <span m=''3894710''>But</span>
  <span m=''3894880''>in</span> <span m=''3894940''>the</span> <span m=''3895050''>end,</span>
  <span m=''3896230''>you</span> <span m=''3896370''>get</span> <span m=''3896500''>NP-hardness
  of</span> <span m=''3896930''>flat</span> <span m=''3897820''>foldability.</span>
  <span m=''3899740''>Questions?</span> </p><p><span m=''3902860''>OK,</span> <span
  m=''3903030''>I</span> <span m=''3903060''>want</span> <span m=''3903220''>to</span>
  <span m=''3903270''>do</span> <span m=''3903400''>one</span> <span m=''3903560''>more</span>
  <span m=''3903730''>proof</span> <span m=''3905580''>sketch.</span> <span m=''3940890''>This</span>
  <span m=''3941120''>is</span> <span m=''3941840''>yet</span> <span m=''3942070''>another</span>
  <span m=''3942410''>paper</span> <span m=''3942770''>that</span> <span m=''3942940''>was</span>
  <span m=''3943540''>at</span> <span m=''3943700''>this</span> <span m=''3943900''>year''s</span>
  <span m=''3944250''>Origami</span> <span m=''3944430''>in</span> <span m=''3944660''>Science</span>
  <span m=''3945000''>Math</span> <span m=''3945230''>and</span> <span m=''3945330''>Education</span>
  <span m=''3945800''>conference.</span> <span m=''3946880''>This</span> <span m=''3947180''>is,</span>
  <span m=''3948630''>it''s</span> <span m=''3948880''>fun</span> <span m=''3949130''>to</span>
  <span m=''3949200''>teach</span> <span m=''3949420''>this</span> <span m=''3949540''>class.</span>
  <span m=''3949810''>Because</span> <span m=''3950000''>it</span> <span m=''3950100''>changes</span>
  <span m=''3950440''>so</span> <span m=''3950670''>much</span> <span m=''3951490''>over</span>
  <span m=''3951710''>a</span> <span m=''3951770''>period</span> <span m=''3952010''>of</span>
  <span m=''3952110''>three</span> <span m=''3952290''>years.</span> <span m=''3953220''>Lots</span>
  <span m=''3953340''>of</span> <span m=''3953400''>new</span> <span m=''3953520''>results.</span>
  <span m=''3954080''>This</span> <span m=''3954180''>is</span> <span m=''3954310''>a</span>
  <span m=''3954350''>result</span> <span m=''3954690''>with</span> <span m=''3955110''>a</span>
  <span m=''3955130''>guy</span> <span m=''3955290''>named</span> <span m=''3955460''>Sandor</span>
  <span m=''3955810''>Fekete</span> <span m=''3956345''>from</span> <span m=''3956650''>Germany.</span>
  <span m=''3957380''>He</span> <span m=''3957670''>does</span> <span m=''3957820''>a</span>
  <span m=''3957860''>lot</span> <span m=''3958000''>of</span> <span m=''3958080''>optimization,</span>
  <span m=''3959520''>and</span> <span m=''3959950''>Robert</span> <span m=''3960310''>Lang,</span>
  <span m=''3961810''>and</span> <span m=''3961850''>myself.</span> <span m=''3964080''>So</span>
  <span m=''3965580''>disk</span> <span m=''3965860''>packing</span> <span m=''3966430''>is</span>
  <span m=''3966530''>something</span> <span m=''3966840''>we</span> <span m=''3966950''>talked</span>
  <span m=''3967270''>about</span> <span m=''3967630''>last</span> <span m=''3968170''>class</span>
  <span m=''3968730''>in</span> <span m=''3968860''>the</span> <span m=''3968950''>context</span>
  <span m=''3969470''>of</span> <span m=''3969660''>the</span> <span m=''3969750''>tree</span>
  <span m=''3969930''>method</span> <span m=''3970200''>of</span> <span m=''3970290''>origami</span>
  <span m=''3970690''>design.</span> <span m=''3971550''>We</span> <span m=''3971700''>said,</span>
  <span m=''3972600''>in</span> <span m=''3972700''>particular</span> <span m=''3973230''>we
  were</span> <span m=''3973280''>thinking</span> <span m=''3973580''>of</span> <span
  m=''3973650''>this</span> <span m=''3973750''>situation</span> <span m=''3974360''>where</span>
  <span m=''3974520''>we</span> <span m=''3974600''>wanted</span> <span m=''3974890''>to</span>
  <span m=''3974990''>make</span> <span m=''3975150''>them</span> <span m=''3975390''>a</span>
  <span m=''3975770''>Margulis</span> <span m=''3976310''>napkin</span> <span m=''3977010''>counter</span>
  <span m=''3977290''>example.</span> </p><p><span m=''3979190''>So</span> <span m=''3979340''>this</span>
  <span m=''3979600''>was</span> <span m=''3979730''>equivalent.</span> <span m=''3980390''>If</span>
  <span m=''3980510''>we</span> <span m=''3980570''>wanted</span> <span m=''3980840''>to</span>
  <span m=''3980900''>build</span> <span m=''3981340''>this</span> <span m=''3981640''>uniaxial</span>
  <span m=''3982340''>base</span> <span m=''3983560''>and</span> <span m=''3983800''>sides,</span>
  <span m=''3984650''>was</span> <span m=''3984790''>the</span> <span m=''3984870''>same</span>
  <span m=''3985160''>thing</span> <span m=''3985870''>as</span> <span m=''3986040''>packing</span>
  <span m=''3987040''>n</span> <span m=''3987450''>disks</span> <span m=''3988380''>into</span>
  <span m=''3989040''>a</span> <span m=''3989480''>square.</span> <span m=''3991210''>That''s</span>
  <span m=''3991460''>what</span> <span m=''3991610''>the tree</span> <span m=''3991870''>method</span>
  <span m=''3992660''>shows.</span> <span m=''3994830''>So</span> <span m=''3995670''>in</span>
  <span m=''3995790''>some</span> <span m=''3995990''>sense,</span> <span m=''3996230''>I''m</span>
  <span m=''3996320''>talking</span> <span m=''3996580''>about</span> <span m=''3996800''>this</span>
  <span m=''3996970''>problem.</span> <span m=''3997760''>But</span> <span m=''3997890''>equivalently,</span>
  <span m=''3998480''>I''m</span> <span m=''3998560''>talking</span> <span m=''3998830''>about</span>
  <span m=''3999010''>this</span> <span m=''3999160''>problem</span> <span m=''3999430''>of</span>
  <span m=''3999500''>packing</span> <span m=''3999870''>disks</span> <span m=''4000250''>into</span>
  <span m=''4000450''>a</span> <span m=''4000510''>square.</span> <span m=''4001440''>Now</span>
  <span m=''4001540''>if</span> <span m=''4001620''>I</span> <span m=''4001690''>give</span>
  <span m=''4001870''>you</span> <span m=''4002080''>n</span> <span m=''4002530''>unit</span>
  <span m=''4003010''>disks</span> <span m=''4003450''>all</span> <span m=''4003630''>the</span>
  <span m=''4003710''>same</span> <span m=''4003940''>size,</span> <span m=''4004250''>I</span>
  <span m=''4004290''>want</span> <span m=''4004420''>to</span> <span m=''4004460''>pack</span>
  <span m=''4004680''>them</span> <span m=''4004780''>in</span> <span m=''4004850''>a</span>
  <span m=''4004900''>square,</span> <span m=''4005570''>that</span> <span m=''4005760''>problem</span>
  <span m=''4007030''>cannot</span> <span m=''4007410''>be</span> <span m=''4007540''>NP-hard.</span>
  <span m=''4009710''>That''s</span> <span m=''4011070''>annoying.</span> <span m=''4011800''>But</span>
  <span m=''4011970''>the</span> <span m=''4012090''>input</span> <span m=''4012330''>is</span>
  <span m=''4012430''>only</span> <span m=''4012690''>n.</span> <span m=''4013520''>It''s</span>
  <span m=''4013640''>not</span> <span m=''4013770''>very</span> <span m=''4013950''>interesting.</span>
  </p><p><span m=''4014920''>So</span> <span m=''4015080''>to</span> <span m=''4015150''>make</span>
  <span m=''4015350''>it</span> <span m=''4016000''>harder,</span> <span m=''4017620''>be</span>
  <span m=''4017860''>able</span> <span m=''4018020''>to</span> <span m=''4018070''>show</span>
  <span m=''4018520''>that</span> <span m=''4019590''>this</span> <span m=''4019750''>problem</span>
  <span m=''4020050''>is</span> <span m=''4020300''>computationally</span> <span m=''4020830''>intractable,</span>
  <span m=''4021940''>I''m</span> <span m=''4022120''>going</span> <span m=''4022200''>to</span>
  <span m=''4022270''>consider</span> <span m=''4022620''>generalization,</span> <span
  m=''4024000''>which</span> <span m=''4024370''>is</span> <span m=''4025050''>I</span>
  <span m=''4025140''>still</span> <span m=''4025380''>have</span> <span m=''4025600''>this</span>
  <span m=''4025860''>kind</span> <span m=''4026010''>of</span> <span m=''4026080''>star</span>
  <span m=''4026560''>tree,</span> <span m=''4027180''>still</span> <span m=''4027420''>a</span>
  <span m=''4027450''>very</span> <span m=''4027690''>simple</span> <span m=''4028080''>kind</span>
  <span m=''4028250''>of</span> <span m=''4028340''>uniaxial</span> <span m=''4028900''>base</span>
  <span m=''4029200''>I</span> <span m=''4029280''>might</span> <span m=''4029480''>want</span>
  <span m=''4029630''>to</span> <span m=''4029680''>build.</span> <span m=''4030680''>But</span>
  <span m=''4030810''>now</span> <span m=''4031220''>all</span> <span m=''4031390''>the</span>
  <span m=''4031460''>limbs</span> <span m=''4031830''>are</span> <span m=''4031930''>different</span>
  <span m=''4032220''>lengths.</span> <span m=''4033610''>So</span> <span m=''4033780''>what</span>
  <span m=''4033890''>that</span> <span m=''4034070''>corresponds</span> <span m=''4034660''>to</span>
  <span m=''4035390''>is</span> <span m=''4035660''>I</span> <span m=''4035710''>have</span>
  <span m=''4036420''>disks</span> <span m=''4037450''>of</span> <span m=''4037690''>various</span>
  <span m=''4038090''>sizes.</span> <span m=''4042310''>It''s</span> <span m=''4042550''>kind</span>
  <span m=''4042700''>of</span> <span m=''4042810''>fun.</span> <span m=''4044002''>It''s</span>
  <span m=''4044400''>like</span> <span m=''4044570''>bubbles.</span> <span m=''4047520''>They</span>
  <span m=''4047690''>all</span> <span m=''4047810''>have</span> <span m=''4047980''>to</span>
  <span m=''4048080''>fit.</span> <span m=''4048320''>They</span> <span m=''4048410''>can''t</span>
  <span m=''4048640''>overlap</span> <span m=''4049030''>each</span> <span m=''4049200''>other.</span>
  <span m=''4049750''>All</span> <span m=''4049980''>of</span> <span m=''4050070''>the</span>
  <span m=''4050170''>centers</span> <span m=''4050640''>of</span> <span m=''4050750''>the</span>
  <span m=''4050820''>disks</span> <span m=''4051710''>are</span> <span m=''4051920''>inside</span>
  <span m=''4052310''>the</span> <span m=''4052390''>square.</span> <span m=''4055430''>And</span>
  <span m=''4055680''>I</span> <span m=''4055720''>want</span> <span m=''4055910''>to</span>
  <span m=''4055970''>know,</span> <span m=''4056190''>can</span> <span m=''4056490''>I--</span>
  <span m=''4057970''>how</span> <span m=''4058140''>big</span> <span m=''4058330''>a</span>
  <span m=''4058450''>square</span> <span m=''4058710''>do I</span> <span m=''4058780''>need</span>
  <span m=''4058960''>to</span> <span m=''4059030''>pack</span> <span m=''4059320''>them?</span>
  </p><p><span m=''4059985''>OK,</span> <span m=''4060460''>I''m</span> <span m=''4060600''>going</span>
  <span m=''4060690''>to</span> <span m=''4060760''>formulate</span> <span m=''4061230''>it</span>
  <span m=''4061380''>as</span> <span m=''4061580''>a</span> <span m=''4061730''>decision</span>
  <span m=''4062120''>question,</span> <span m=''4062910''>yes</span> <span m=''4063150''>or</span>
  <span m=''4063210''>no.</span> <span m=''4064500''>Can</span> <span m=''4064730''>you</span>
  <span m=''4064840''>place</span> <span m=''4067750''>n</span> <span m=''4068190''>given</span>
  <span m=''4068500''>disks,</span> <span m=''4069060''>I</span> <span m=''4069120''>give</span>
  <span m=''4069320''>you</span> <span m=''4069400''>the</span> <span m=''4069510''>sizes</span>
  <span m=''4069970''>of</span> <span m=''4070100''>them.</span> <span m=''4074610''>I</span>
  <span m=''4074680''>want</span> <span m=''4074910''>them</span> <span m=''4075030''>to</span>
  <span m=''4075090''>be</span> <span m=''4075200''>non-overlapping.</span> <span
  m=''4079100''>They</span> <span m=''4079200''>can</span> <span m=''4079380''>touch</span>
  <span m=''4080040''>on</span> <span m=''4080120''>the</span> <span m=''4080200''>boundary</span>
  <span m=''4080620''>but</span> <span m=''4080800''>the</span> <span m=''4081140''>interiors</span>
  <span m=''4081740''>can''t</span> <span m=''4082180''>overlap.</span> <span m=''4083600''>And</span>
  <span m=''4083830''>I</span> <span m=''4083900''>need</span> <span m=''4084110''>the</span>
  <span m=''4084190''>centers</span> <span m=''4085900''>to</span> <span m=''4086320''>lie</span>
  <span m=''4087900''>in</span> <span m=''4088100''>a</span> <span m=''4088140''>given</span>
  <span m=''4088450''>square.</span> <span m=''4090720''>So</span> <span m=''4090830''>I</span>
  <span m=''4090890''>want</span> <span m=''4091060''>to</span> <span m=''4091100''>know,</span>
  <span m=''4091270''>can</span> <span m=''4091510''>I</span> <span m=''4091560''>make</span>
  <span m=''4091790''>this</span> <span m=''4091930''>uniaxial</span> <span m=''4092440''>base</span>
  <span m=''4093010''>from</span> <span m=''4093260''>this</span> <span m=''4093520''>square</span>
  <span m=''4093870''>paper?</span> <span m=''4095280''>And</span> <span m=''4095780''>I</span>
  <span m=''4095940''>claim</span> <span m=''4096189''>that</span> <span m=''4096450''>as</span>
  <span m=''4096689''>NP-hard.</span> <span m=''4098560''>So</span> <span m=''4099040''>good</span>
  <span m=''4099250''>luck</span> <span m=''4099970''>solving</span> <span m=''4100399''>it</span>
  <span m=''4100520''>perfectly.</span> <span m=''4101580''>And</span> <span m=''4101750''>what</span>
  <span m=''4102020''>tree</span> <span m=''4102240''>maker</span> <span m=''4102500''>does</span>
  <span m=''4102779''>is</span> <span m=''4102920''>it</span> <span m=''4103040''>solves</span>
  <span m=''4103260''>it</span> <span m=''4103319''>approximately</span> <span m=''4105160''>with</span>
  <span m=''4105330''>a</span> <span m=''4105380''>heuristic.</span> </p><p><span
  m=''4112790''>For</span> <span m=''4112880''>those</span> <span m=''4113090''>who</span>
  <span m=''4113149''>know</span> <span m=''4113510''>approximation</span> <span m=''4114140''>algorithims,</span>
  <span m=''4114500''>this</span> <span m=''4114689''>is</span> <span m=''4114890''>a</span>
  <span m=''4114960''>problem</span> <span m=''4115270''>you</span> <span m=''4116109''>can</span>
  <span m=''4116220''>find</span> <span m=''4116399''>a</span> <span m=''4116450''>constant</span>
  <span m=''4116779''>factor</span> <span m=''4117050''>approximation.</span> <span
  m=''4118300''>There''s</span> <span m=''4118410''>one</span> <span m=''4118609''>in</span>
  <span m=''4118710''>the</span> <span m=''4118790''>same</span> <span m=''4119029''>paper.</span>
  <span m=''4119990''>But</span> <span m=''4120140''>it''s</span> <span m=''4120229''>still</span>
  <span m=''4120470''>not,</span> <span m=''4120830''>still</span> <span m=''4121109''>unresolved</span>
  <span m=''4121729''>how</span> <span m=''4123040''>close</span> <span m=''4123370''>to</span>
  <span m=''4123450''>optimal</span> <span m=''4123859''>you</span> <span m=''4124000''>can</span>
  <span m=''4124149''>get.</span> <span m=''4127600''>But</span> <span m=''4127700''>I</span>
  <span m=''4127779''>want</span> <span m=''4127930''>to</span> <span m=''4127979''>focus</span>
  <span m=''4128340''>here</span> <span m=''4128560''>on</span> <span m=''4128640''>the</span>
  <span m=''4128720''>NP-hardness.</span> <span m=''4134350''>So</span> <span m=''4134810''>I</span>
  <span m=''4134910''>should</span> <span m=''4135120''>say</span> <span m=''4135450''>this</span>
  <span m=''4135640''>problem</span> <span m=''4138140''>is</span> <span m=''4138330''>NP-hard.</span>
  <span m=''4143760''>So</span> <span m=''4144060''>we''re</span> <span m=''4144160''>going</span>
  <span m=''4144260''>to</span> <span m=''4144330''>prove</span> <span m=''4144569''>that.</span>
  <span m=''4148279''>And</span> <span m=''4148460''>now</span> <span m=''4148729''>I</span>
  <span m=''4148819''>get</span> <span m=''4148960''>to</span> <span m=''4149029''>reduce</span>
  <span m=''4149330''>for</span> <span m=''4149370''>my</span> <span m=''4149510''>favorite</span>
  <span m=''4149850''>problem,</span> <span m=''4153109''>favorite</span> <span m=''4153580''>NP-hard.</span>
  <span m=''4155390''>It''s</span> <span m=''4155520''>my</span> <span m=''4155649''>favorite</span>
  <span m=''4156310''>partly</span> <span m=''4156670''>because</span> <span m=''4157140''>not</span>
  <span m=''4157290''>many</span> <span m=''4157479''>people</span> <span m=''4157760''>know</span>
  <span m=''4157990''>it</span> <span m=''4159410''>unless</span> <span m=''4159640''>you''ve</span>
  <span m=''4159779''>done</span> <span m=''4159979''>NP-hardness</span> <span m=''4160500''>proofs
  with</span> <span m=''4160840''>me</span> <span m=''4160979''>before.</span> <span
  m=''4162279''>And</span> <span m=''4163810''>it''s</span> <span m=''4164120''>very</span>
  <span m=''4164340''>powerful.</span> </p><p><span m=''4165600''>Whenever</span>
  <span m=''4165920''>you</span> <span m=''4166040''>have</span> <span m=''4166229''>a</span>
  <span m=''4166300''>problem</span> <span m=''4166660''>that</span> <span m=''4166760''>involves</span>
  <span m=''4167109''>numbers,</span> <span m=''4167840''>and</span> <span m=''4167979''>this</span>
  <span m=''4168120''>problem</span> <span m=''4168370''>involves</span> <span m=''4168670''>numbers.</span>
  <span m=''4169029''>It''s</span> <span m=''4169180''>the</span> <span m=''4169319''>radii</span>
  <span m=''4169910''>of</span> <span m=''4170060''>the</span> <span m=''4170130''>disk''s.</span>
  <span m=''4171399''>Three</span> <span m=''4171620''>partition</span> <span m=''4171965''>is</span>
  <span m=''4172310''>the</span> <span m=''4172770''>problem</span> <span m=''4173069''>you</span>
  <span m=''4173180''>should</span> <span m=''4173390''>know.</span> <span m=''4174500''>Partition</span>
  <span m=''4174979''>is</span> <span m=''4175120''>all</span> <span m=''4175410''>right.</span>
  <span m=''4176180''>The</span> <span m=''4176290''>three</span> <span m=''4176500''>partition</span>
  <span m=''4176960''>is</span> <span m=''4177069''>like</span> <span m=''4177220''>50%</span>
  <span m=''4177800''>better.</span> <span m=''4181700''>Because</span> <span m=''4182149''>partition</span>
  <span m=''4182540''>is</span> <span m=''4182660''>like</span> <span m=''4182840''>you''ve</span>
  <span m=''4182979''>partitioned</span> <span m=''4183410''>it to</span> <span m=''4183660''>two</span>
  <span m=''4183859''>parts.</span> <span m=''4184920''>So</span> <span m=''4185260''>it''s</span>
  <span m=''4185439''>like</span> <span m=''4185620''>two</span> <span m=''4185760''>partition.</span>
  <span m=''4186580''>Three</span> <span m=''4186819''>partition,</span> <span m=''4187290''>you</span>
  <span m=''4187399''>partition</span> <span m=''4187850''>into?</span> <span m=''4191780''>Does</span>
  <span m=''4192263''>not</span> <span m=''4192750''>one</span> <span m=''4193109''>have</span>
  <span m=''4193229''>the</span> <span m=''4193319''>right</span> <span m=''4193510''>answer?</span>
  <span m=''4193850''>I hear</span> <span m=''4194069''>three</span> <span m=''4194260''>parts</span>
  <span m=''4194510''>and</span> <span m=''4194610''>five</span> <span m=''4194820''>parts.</span>
  <span m=''4195720''>Any</span> <span m=''4195900''>other</span> <span m=''4195960''>guesses?</span>
  </p><p><span m=''4196660''>AUDIENCE: Seven</span> </p><p><span m=''4197660''>PROFESSOR:
  Seven.</span> <span m=''4199830''>Keep</span> <span m=''4200030''>going.</span>
  <span m=''4202050''>n</span> <span m=''4202270''>over</span> <span m=''4202460''>three</span>
  <span m=''4202680''>parts</span> <span m=''4203370''>is</span> <span m=''4203540''>the</span>
  <span m=''4203710''>answer.</span> <span m=''4204630''>So</span> <span m=''4206000''>it''s</span>
  <span m=''4206090''>not</span> <span m=''4206280''>so</span> <span m=''4206410''>obvious.</span>
  <span m=''4208920''>Maybe</span> <span m=''4209150''>it</span> <span m=''4209220''>should</span>
  <span m=''4209330''>be</span> <span m=''4209420''>called</span> <span m=''4209640''>n</span>
  <span m=''4209760''>over</span> <span m=''4209950''>3</span> <span m=''4210130''>partition.</span>
  <span m=''4216900''>So</span> <span m=''4217070''>instead</span> <span m=''4217350''>of</span>
  <span m=''4217420''>the</span> <span m=''4217490''>number of</span> <span m=''4217790''>parts</span>
  <span m=''4218150''>being</span> <span m=''4218370''>three,</span> <span m=''4218800''>the</span>
  <span m=''4218900''>size</span> <span m=''4219310''>of</span> <span m=''4219420''>each</span>
  <span m=''4219610''>part</span> <span m=''4220040''>is</span> <span m=''4220170''>three.</span>
  <span m=''4221845''>So</span> <span m=''4222300''>n</span> <span m=''4222500''>should</span>
  <span m=''4222650''>be</span> <span m=''4222750''>divisible</span> <span m=''4223190''>by</span>
  <span m=''4223340''>3.</span> <span m=''4227070''>So</span> <span m=''4227270''>I''m</span>
  <span m=''4227450''>going</span> <span m=''4227620''>to</span> <span m=''4227680''>partition</span>
  <span m=''4228090''>it to</span> <span m=''4228250''>n</span> <span m=''4228430''>over</span>
  <span m=''4228580''>3</span> <span m=''4228820''>triples</span> <span m=''4229290''>of</span>
  <span m=''4229370''>numbers</span> <span m=''4230510''>of</span> <span m=''4230660''>equal</span>
  <span m=''4230970''>sum.</span> <span m=''4239500''>This</span> <span m=''4239710''>problem</span>
  <span m=''4240020''>is</span> <span m=''4240560''>cool</span> <span m=''4241660''>for</span>
  <span m=''4241910''>this</span> <span m=''4242170''>technical</span> <span m=''4243120''>reason</span>
  <span m=''4243980''>that</span> <span m=''4244110''>it</span> <span m=''4244220''>is</span>
  <span m=''4244350''>strongly</span> <span m=''4245410''>NP-hard.</span> <span m=''4248370''>So</span>
  <span m=''4248580''>even</span> <span m=''4248860''>when</span> <span m=''4248990''>the</span>
  <span m=''4249080''>numbers</span> <span m=''4249560''>are</span> <span m=''4249680''>really</span>
  <span m=''4249900''>small,</span> <span m=''4252100''>like</span> <span m=''4252300''>about</span>
  <span m=''4252580''>n,</span> <span m=''4254720''>this</span> <span m=''4254880''>problem</span>
  <span m=''4255160''>is</span> <span m=''4255270''>NP-hard.</span> </p><p><span m=''4256260''>With</span>
  <span m=''4256410''>partition,</span> <span m=''4257290''>the</span> <span m=''4257400''>numbers</span>
  <span m=''4257670''>had</span> <span m=''4257800''>to</span> <span m=''4257860''>be</span>
  <span m=''4258040''>exponential</span> <span m=''4258380''>and</span> <span m=''4258720''>n</span>
  <span m=''4259100''>for</span> <span m=''4259200''>the</span> <span m=''4259290''>problem</span>
  <span m=''4259570''>to</span> <span m=''4259640''>be</span> <span m=''4259760''>hard.</span>
  <span m=''4260420''>And</span> <span m=''4260590''>that''s</span> <span m=''4260760''>kind</span>
  <span m=''4261030''>of</span> <span m=''4261100''>artificial</span> <span m=''4261540''>here.</span>
  <span m=''4262190''>So</span> <span m=''4262370''>this</span> <span m=''4262580''>is</span>
  <span m=''4263240''>actually</span> <span m=''4263570''>strongly</span> <span m=''4264010''>NP-hard.</span>
  <span m=''4265390''>So</span> <span m=''4265620''>this</span> <span m=''4265790''>problem</span>
  <span m=''4266110''>is</span> <span m=''4266210''>hard</span> <span m=''4266590''>even</span>
  <span m=''4266870''>when</span> <span m=''4266990''>the</span> <span m=''4267100''>disk</span>
  <span m=''4267430''>sizes</span> <span m=''4268010''>are</span> <span m=''4268150''>not</span>
  <span m=''4268390''>that</span> <span m=''4268590''>different.</span> <span m=''4269470''>There''s</span>
  <span m=''4269510''>like</span> <span m=''4269720''>a</span> <span m=''4269790''>range</span>
  <span m=''4270040''>between</span> <span m=''4270270''>one</span> <span m=''4270470''>and
  n,</span> <span m=''4270820''>let''s</span> <span m=''4271020''>say.</span> <span
  m=''4272120''>If</span> <span m=''4272290''>I</span> <span m=''4272350''>reduce</span>
  <span m=''4272680''>from</span> <span m=''4272810''>partition,</span> <span m=''4273530''>I''d</span>
  <span m=''4273650''>need</span> <span m=''4273960''>some</span> <span m=''4274290''>disks</span>
  <span m=''4274690''>to be</span> <span m=''4275080''>microscopic</span> <span m=''4275980''>and</span>
  <span m=''4276140''>some to</span> <span m=''4276440''>be</span> <span m=''4276570''>ginormous,</span>
  <span m=''4277640''>exponential</span> <span m=''4279130''>difference.</span> <span
  m=''4280340''>I''m</span> <span m=''4280500''>going</span> <span m=''4280590''>to</span>
  <span m=''4280640''>reduce</span> <span m=''4280890''>from</span> <span m=''4281000''>three</span>
  <span m=''4281190''>partition</span> <span m=''4281620''>because</span> <span m=''4281890''>I</span>
  <span m=''4281940''>get</span> <span m=''4282110''>a</span> <span m=''4282160''>better</span>
  <span m=''4282440''>result.</span> <span m=''4283220''>I</span> <span m=''4283300''>get</span>
  <span m=''4283390''>a</span> <span m=''4283450''>stronger</span> <span m=''4283790''>result</span>
  <span m=''4284170''>the</span> <span m=''4284270''>says</span> <span m=''4284590''>even</span>
  <span m=''4284880''>when</span> <span m=''4285000''>the</span> <span m=''4285070''>disks
  are</span> <span m=''4285380''>not</span> <span m=''4285580''>so</span> <span m=''4285690''>different</span>
  <span m=''4286000''>in</span> <span m=''4286090''>size,</span> <span m=''4287010''>this</span>
  <span m=''4287170''>problem</span> <span m=''4287540''>is</span> <span m=''4287800''>NP-hard.</span>
  <span m=''4291860''>That''s</span> <span m=''4292110''>my</span> <span m=''4292220''>problem</span>
  <span m=''4301520''>that</span> <span m=''4301620''>I''ve</span> <span m=''4301720''>got</span>
  <span m=''4301820''>to</span> <span m=''4301920''>start</span> <span m=''4302050''>from.</span>
  </p><p><span m=''4302500''>So</span> <span m=''4302530''>I</span> <span m=''4302600''>give</span>
  <span m=''4302850''>you</span> <span m=''4303720''>n</span> <span m=''4303910''>integers.</span>
  <span m=''4305055''>I</span> <span m=''4305510''>want</span> <span m=''4305660''>to</span>
  <span m=''4305710''>somehow</span> <span m=''4306030''>triple</span> <span m=''4306390''>them</span>
  <span m=''4306540''>up</span> <span m=''4310160''>using</span> <span m=''4311410''>a</span>
  <span m=''4311490''>disk</span> <span m=''4311810''>packing.</span> <span m=''4313430''>So</span>
  <span m=''4313560''>somehow</span> <span m=''4313880''>solving</span> <span m=''4314330''>a</span>
  <span m=''4314380''>disk</span> <span m=''4314590''>packing</span> <span m=''4314960''>problem</span>
  <span m=''4315380''>is</span> <span m=''4315480''>going</span> <span m=''4315600''>to</span>
  <span m=''4315670''>solve</span> <span m=''4316200''>this</span> <span m=''4316300''>three</span>
  <span m=''4316560''>partition</span> <span m=''4317010''>problem.</span> <span m=''4318720''>And</span>
  <span m=''4319050''>it''s</span> <span m=''4319190''>kind</span> <span m=''4319380''>of</span>
  <span m=''4319440''>crazy.</span> <span m=''4323600''>I''ll</span> <span m=''4323700''>give</span>
  <span m=''4323870''>you</span> <span m=''4324170''>the</span> <span m=''4324270''>high</span>
  <span m=''4324450''>level</span> <span m=''4325070''>picture.</span> <span m=''4336027''>It''s</span>
  <span m=''4337040''>n</span> <span m=''4337340''>over</span> <span m=''4337560''>three</span>
  <span m=''4338820''>identical</span> <span m=''4340410''>pockets.</span> <span m=''4356250''>So</span>
  <span m=''4356550''>in</span> <span m=''4356790''>this</span> <span m=''4357020''>case,</span>
  <span m=''4357440''>there</span> <span m=''4357760''>is</span> <span m=''4359610''>kind</span>
  <span m=''4359820''>of</span> <span m=''4359880''>like</span> <span m=''4360090''>the</span>
  <span m=''4360240''>proof</span> <span m=''4360640''>where</span> <span m=''4361410''>we</span>
  <span m=''4361630''>had</span> <span m=''4361860''>the</span> <span m=''4362110''>simple</span>
  <span m=''4362360''>folds</span> <span m=''4362730''>and</span> <span m=''4362910''>we
  a</span> <span m=''4362980''>frame</span> <span m=''4363770''>and</span> <span m=''4364060''>some</span>
  <span m=''4364160''>stuff.</span> <span m=''4365720''>We''re</span> <span m=''4365890''>going</span>
  <span m=''4365980''>to</span> <span m=''4366020''>have</span> <span m=''4366190''>some</span>
  <span m=''4366510''>infrastructure,</span> <span m=''4367320''>which</span> <span
  m=''4367480''>in</span> <span m=''4367540''>that</span> <span m=''4367670''>case</span>
  <span m=''4367860''>was</span> <span m=''4367980''>the</span> <span m=''4368070''>frame.</span>
  <span m=''4368550''>That was</span> <span m=''4368720''>sort</span> <span m=''4368980''>of</span>
  <span m=''4369300''>a</span> <span m=''4369390''>basic</span> <span m=''4369740''>thing</span>
  <span m=''4369930''>that</span> <span m=''4369950''>always</span> <span m=''4370210''>exists.</span>
  </p><p><span m=''4371070''>In</span> <span m=''4371140''>this</span> <span m=''4371310''>case,</span>
  <span m=''4371550''>we''re</span> <span m=''4371650''>going</span> <span m=''4371740''>to</span>
  <span m=''4371780''>have</span> <span m=''4371910''>some</span> <span m=''4372080''>infrastructure</span>
  <span m=''4372570''>which</span> <span m=''4372700''>is</span> <span m=''4372780''>a</span>
  <span m=''4372830''>whole</span> <span m=''4373140''>bunch</span> <span m=''4373360''>of</span>
  <span m=''4373430''>disks</span> <span m=''4374410''>that</span> <span m=''4374500''>just</span>
  <span m=''4374680''>sort</span> <span m=''4374800''>of</span> <span m=''4374870''>set,</span>
  <span m=''4375710''>instead</span> <span m=''4376040''>of</span> <span m=''4376110''>having</span>
  <span m=''4376370''>this</span> <span m=''4377100''>very</span> <span m=''4377300''>open</span>
  <span m=''4377610''>problem,</span> <span m=''4378050''>open</span> <span m=''4378290''>playing</span>
  <span m=''4378570''>field with a</span> <span m=''4378900''>square,</span> <span
  m=''4379850''>and</span> <span m=''4380030''>like</span> <span m=''4380190''>you</span>
  <span m=''4380290''>could</span> <span m=''4380390''>put</span> <span m=''4380520''>disks</span>
  <span m=''4380740''>anywhere,</span> <span m=''4381850''>I</span> <span m=''4381980''>want</span>
  <span m=''4382160''>to</span> <span m=''4382500''>partition</span> <span m=''4383040''>my</span>
  <span m=''4383180''>square</span> <span m=''4383470''>into</span> <span m=''4383630''>lots</span>
  <span m=''4383890''>of</span> <span m=''4383940''>little</span> <span m=''4384140''>pockets,</span>
  <span m=''4384810''>all</span> <span m=''4385030''>the</span> <span m=''4385110''>same</span>
  <span m=''4385350''>size,</span> <span m=''4386110''>all</span> <span m=''4386310''>the</span>
  <span m=''4386390''>same</span> <span m=''4386610''>shape.</span> <span m=''4387900''>And</span>
  <span m=''4390280''>all</span> <span m=''4390560''>other</span> <span m=''4390760''>pockets</span>
  <span m=''4391230''>are</span> <span m=''4391300''>going</span> <span m=''4391420''>to</span>
  <span m=''4391480''>be</span> <span m=''4391610''>much</span> <span m=''4391800''>smaller.</span>
  <span m=''4393560''>So</span> <span m=''4393770''>it''s</span> <span m=''4393990''>a</span>
  <span m=''4394040''>little</span> <span m=''4394240''>hard</span> <span m=''4394430''>to</span>
  <span m=''4394500''>draw</span> <span m=''4394710''>this.</span> <span m=''4394910''>Because</span>
  <span m=''4395350''>while</span> <span m=''4395520''>I</span> <span m=''4395600''>said</span>
  <span m=''4395900''>that</span> <span m=''4395960''>the</span> <span m=''4396080''>disks</span>
  <span m=''4396470''>aren''t that</span> <span m=''4396840''>different</span> <span
  m=''4397230''>size,</span> <span m=''4397530''>they''re</span> <span m=''4397700''>only</span>
  <span m=''4398060''>a</span> <span m=''4398120''>factor</span> <span m=''4398550''>of</span>
  <span m=''4398630''>n</span> <span m=''4398890''>different</span> <span m=''4399180''>in
  size,</span> <span m=''4401150''>if</span> <span m=''4401380''>you</span> <span
  m=''4401460''>try</span> <span m=''4401620''>to</span> <span m=''4401730''>draw</span>
  <span m=''4401930''>these</span> <span m=''4402100''>pictures,</span> <span m=''4402530''>it</span>
  <span m=''4402640''>gets</span> <span m=''4402970''>tiny</span> <span m=''4403280''>very</span>
  <span m=''4403480''>quickly.</span> </p><p><span m=''4404400''>So</span> <span m=''4404520''>here''s</span>
  <span m=''4404750''>the</span> <span m=''4404820''>high</span> <span m=''4404980''>level</span>
  <span m=''4405720''>picture.</span> <span m=''4406460''>You have</span> <span m=''4406520''>a</span>
  <span m=''4406580''>square.</span> <span m=''4408660''>And</span> <span m=''4409470''>I''m</span>
  <span m=''4409620''>going</span> <span m=''4409720''>to</span> <span m=''4409780''>put</span>
  <span m=''4409960''>down</span> <span m=''4410210''>these</span> <span m=''4410690''>disks.</span>
  <span m=''4411860''>There''s</span> <span m=''4414920''>20</span> <span m=''4415660''>disks</span>
  <span m=''4416080''>here,</span> <span m=''4416380''>I</span> <span m=''4416430''>think,</span>
  <span m=''4417520''>4</span> <span m=''4417890''>times</span> <span m=''4418270''>4</span>
  <span m=''4418370''>is</span> <span m=''4418470''>16</span> <span m=''4419140''>plus</span>
  <span m=''4419840''>5.</span> <span m=''4420140''>I''m</span> <span m=''4420440''>sorry,</span>
  <span m=''4420620''>21.</span> <span m=''4421830''>So</span> <span m=''4421960''>these</span>
  <span m=''4422280''>21</span> <span m=''4422680''>disks,</span> <span m=''4423610''>they</span>
  <span m=''4423770''>have</span> <span m=''4423950''>a</span> <span m=''4424000''>unique</span>
  <span m=''4424410''>package,</span> <span m=''4425690''>this</span> <span m=''4425860''>one</span>
  <span m=''4426010''>right</span> <span m=''4426190''>here.</span> <span m=''4426350''>You</span>
  <span m=''4426470''>can</span> <span m=''4426590''>see</span> <span m=''4426780''>that</span>
  <span m=''4427000''>because</span> <span m=''4427630''>these</span> <span m=''4427870''>four</span>
  <span m=''4428060''>disks</span> <span m=''4428450''>have</span> <span m=''4428740''>to</span>
  <span m=''4428850''>be</span> <span m=''4428970''>in</span> <span m=''4429050''>the</span>
  <span m=''4429140''>corners,</span> <span m=''4430270''>can''t</span> <span m=''4430500''>fit</span>
  <span m=''4430640''>one</span> <span m=''4430810''>in</span> <span m=''4431180''>the</span>
  <span m=''4431330''>center</span> <span m=''4431660''>and</span> <span m=''4431800''>have</span>
  <span m=''4432050''>room</span> <span m=''4432170''>for</span> <span m=''4432280''>the</span>
  <span m=''4432400''>others.</span> <span m=''4433070''>Then</span> <span m=''4433220''>this</span>
  <span m=''4433410''>guy</span> <span m=''4433560''>has</span> <span m=''4433900''>to</span>
  <span m=''4434000''>go</span> <span m=''4434130''>right</span> <span m=''4434390''>there.</span>
  <span m=''4435190''>And</span> <span m=''4435350''>then</span> <span m=''4435460''>these</span>
  <span m=''4435650''>four</span> <span m=''4435840''>disks</span> <span m=''4436720''>are</span>
  <span m=''4437170''>unique</span> <span m=''4437600''>if</span> <span m=''4437700''>you</span>
  <span m=''4437790''>set</span> <span m=''4438000''>it</span> <span m=''4438080''>up</span>
  <span m=''4438240''>right.</span> <span m=''4438490''>It''s</span> <span m=''4438870''>a</span>
  <span m=''4438920''>little</span> <span m=''4439140''>bit,</span> <span m=''4439420''>it''s</span>
  <span m=''4439540''>hard</span> <span m=''4439710''>to</span> <span m=''4439760''>draw.</span>
  <span m=''4439980''>But</span> <span m=''4440140''>these</span> <span m=''4440300''>are</span>
  <span m=''4440440''>little</span> <span m=''4440630''>bit</span> <span m=''4440780''>wedged</span>
  <span m=''4441480''>over</span> <span m=''4441870''>to</span> <span m=''4442000''>the</span>
  <span m=''4442120''>right.</span> </p><p><span m=''4444690''>So</span> <span m=''4445010''>you</span>
  <span m=''4445200''>set</span> <span m=''4445410''>up</span> <span m=''4445500''>these
  disks.</span> <span m=''4445880''>That''s</span> <span m=''4446080''>infrastructure.</span>
  <span m=''4446900''>It''s</span> <span m=''4447190''>the</span> <span m=''4447310''>only</span>
  <span m=''4447570''>way</span> <span m=''4447810''>to</span> <span m=''4447940''>put</span>
  <span m=''4448140''>them.</span> <span m=''4448720''>And</span> <span m=''4448830''>then</span>
  <span m=''4448940''>there''s</span> <span m=''4449100''>these</span> <span m=''4449270''>little</span>
  <span m=''4449500''>pockets</span> <span m=''4450010''>here.</span> <span m=''4450940''>They''re</span>
  <span m=''4451500''>nice.</span> <span m=''4452080''>They''re</span> <span m=''4452310''>symmetric.</span>
  <span m=''4453400''>They''re</span> <span m=''4453560''>like</span> <span m=''4453750''>a</span>
  <span m=''4453880''>triangle,</span> <span m=''4454360''>an</span> <span m=''4454840''>equilateral</span>
  <span m=''4455340''>triangle</span> <span m=''4455800''>so</span> <span m=''4455820''>to</span>
  <span m=''4455910''>speak,</span> <span m=''4456150''>except</span> <span m=''4456460''>they
  have</span> <span m=''4456590''>curved</span> <span m=''4456910''>edges.</span>
  <span m=''4457840''>They''re</span> <span m=''4457960''>all</span> <span m=''4458100''>the</span>
  <span m=''4458180''>same</span> <span m=''4458420''>size.</span> <span m=''4459640''>That</span>
  <span m=''4459790''>gives</span> <span m=''4459940''>me</span> <span m=''4460100''>four</span>
  <span m=''4460400''>pockets.</span> <span m=''4461400''>But</span> <span m=''4461520''>I</span>
  <span m=''4461700''>want</span> <span m=''4462080''>n</span> <span m=''4462230''>over</span>
  <span m=''4462420''>3</span> <span m=''4462650''>pockets.</span> <span m=''4463260''>So
  I''m</span> <span m=''4463630''>going to  need</span> <span m=''4463750''>a</span>
  <span m=''4463800''>lot</span> <span m=''4464000''>more.</span> <span m=''4465310''>So</span>
  <span m=''4465550''>I</span> <span m=''4465670''>take</span> <span m=''4466020''>each</span>
  <span m=''4466260''>of</span> <span m=''4466340''>these</span> <span m=''4466540''>pockets.</span>
  <span m=''4467070''>That''s</span> <span m=''4467610''>these</span> <span m=''4468070''>three</span>
  <span m=''4469510''>disks.</span> <span m=''4470060''>And</span> <span m=''4470220''>this</span>
  <span m=''4470390''>is</span> <span m=''4470530''>the</span> <span m=''4470630''>triangular</span>
  <span m=''4471060''>pocket</span> <span m=''4471390''>in</span> <span m=''4471480''>the</span>
  <span m=''4471560''>center.</span> <span m=''4472560''>And</span> <span m=''4472770''>I</span>
  <span m=''4472820''>put</span> <span m=''4473160''>down</span> <span m=''4473500''>these</span>
  <span m=''4474870''>17</span> <span m=''4475650''>disks.</span> <span m=''4477000''>It''s</span>
  <span m=''4477380''>almost</span> <span m=''4477840''>the</span> <span m=''4477920''>same.</span>
  <span m=''4478510''>And</span> <span m=''4478750''>I</span> <span m=''4478800''>can</span>
  <span m=''4478990''>see</span> <span m=''4479230''>it''s</span> <span m=''4479390''>not</span>
  <span m=''4479550''>quite</span> <span m=''4479770''>drawn</span> <span m=''4479980''>perfectly.</span>
  <span m=''4480390''>This</span> <span m=''4480550''>is</span> <span m=''4480630''>supposed</span>
  <span m=''4480880''>to</span> <span m=''4480960''>touch</span> <span m=''4481240''>here.</span>
  </p><p><span m=''4482730''>This</span> <span m=''4482910''>guy</span> <span m=''4483060''>is</span>
  <span m=''4483220''>floating</span> <span m=''4483570''>a</span> <span m=''4483620''>little</span>
  <span m=''4483820''>bit.</span> <span m=''4485310''>And</span> <span m=''4486270''>what</span>
  <span m=''4486740''>we</span> <span m=''4487100''>end</span> <span m=''4487290''>up,</span>
  <span m=''4487420''>this</span> <span m=''4487650''>guy''s</span> <span m=''4487880''>uniquely</span>
  <span m=''4488280''>placed.</span> <span m=''4488670''>And</span> <span m=''4488760''>then</span>
  <span m=''4488870''>these</span> <span m=''4489060''>guys</span> <span m=''4489260''>have</span>
  <span m=''4489380''>got</span> <span m=''4489530''>to</span> <span m=''4489580''>go</span>
  <span m=''4489760''>in</span> <span m=''4489840''>the</span> <span m=''4489950''>three</span>
  <span m=''4490670''>remaining</span> <span m=''4491030''>pockets.</span> <span m=''4491520''>What</span>
  <span m=''4491670''>we</span> <span m=''4491780''>end</span> <span m=''4491920''>up</span>
  <span m=''4492020''>getting</span> <span m=''4492290''>is</span> <span m=''4492390''>another</span>
  <span m=''4492830''>equilateral</span> <span m=''4494130''>whole</span> <span m=''4495690''>pocket</span>
  <span m=''4496110''>right</span> <span m=''4496340''>there.</span> <span m=''4497110''>And</span>
  <span m=''4497270''>these</span> <span m=''4497500''>three</span> <span m=''4497730''>will</span>
  <span m=''4497840''>have</span> <span m=''4497990''>the</span> <span m=''4498080''>same</span>
  <span m=''4498350''>size</span> <span m=''4499370''>and</span> <span m=''4499740''>be</span>
  <span m=''4499910''>identical.</span> <span m=''4500900''>If I</span> <span m=''4501010''>do</span>
  <span m=''4501160''>that</span> <span m=''4501360''>in</span> <span m=''4501500''>all</span>
  <span m=''4501710''>four</span> <span m=''4502010''>of</span> <span m=''4502070''>these,</span>
  <span m=''4502830''>now I''ll</span> <span m=''4503170''>have</span> <span m=''4503520''>16</span>
  <span m=''4503970''>pockets.</span> <span m=''4505650''>And</span> <span m=''4505810''>each</span>
  <span m=''4505990''>time</span> <span m=''4506190''>I</span> <span m=''4506250''>do</span>
  <span m=''4506380''>this,</span> <span m=''4506580''>side</span> <span m=''4506920''>I</span>
  <span m=''4507590''>quadruple</span> <span m=''4507900''>the</span> <span m=''4508210''>number
  of</span> <span m=''4508480''>pockets.</span> <span m=''4509770''>So</span> <span
  m=''4509900''>after</span> <span m=''4510160''>I</span> <span m=''4510220''>do</span>
  <span m=''4510420''>it,</span> <span m=''4510610''>whatever</span> <span m=''4510960''>log</span>
  <span m=''4511270''>n</span> <span m=''4511590''>times,</span> <span m=''4512520''>or</span>
  <span m=''4512730''>I</span> <span m=''4512850''>apply</span> <span m=''4513090''>that</span>
  <span m=''4513280''>gadget</span> <span m=''4513610''>around</span> <span m=''4513910''>n</span>
  <span m=''4514050''>times,</span> <span m=''4514470''>I</span> <span m=''4514530''>get</span>
  <span m=''4514720''>around</span> <span m=''4515050''>n</span> <span m=''4515160''>over</span>
  <span m=''4515340''>3</span> <span m=''4516240''>pockets.</span> <span m=''4517020''>They''re</span>
  <span m=''4517110''>all</span> <span m=''4517200''>identical.</span> <span m=''4518330''>The</span>
  <span m=''4518420''>ones</span> <span m=''4518610''>I</span> <span m=''4518650''>don''t</span>
  <span m=''4518860''>want,</span> <span m=''4519030''>I''ll</span> <span m=''4519160''>just</span>
  <span m=''4519520''>throw</span> <span m=''4519740''>a</span> <span m=''4519790''>disk</span>
  <span m=''4520030''>in</span> <span m=''4520110''>there</span> <span m=''4520270''>to</span>
  <span m=''4520370''>destroy</span> <span m=''4520710''>it.</span> <span m=''4522270''>That''s</span>
  <span m=''4522480''>the</span> <span m=''4522570''>infrastructure.</span> </p><p><span
  m=''4524090''>Now</span> <span m=''4524230''>I''ve</span> <span m=''4524360''>got</span>
  <span m=''4524530''>n</span> <span m=''4524680''>over</span> <span m=''4524850''>three</span>
  <span m=''4525020''>identical</span> <span m=''4525410''>pockets.</span> <span m=''4525850''>There</span>
  <span m=''4525960''>are</span> <span m=''4525990''>these</span> <span m=''4526170''>other</span>
  <span m=''4526370''>pockets.</span> <span m=''4527200''>Just</span> <span m=''4527430''>throw
  in</span> <span m=''4527780''>disks</span> <span m=''4528170''>in</span> <span m=''4528350''>there.</span>
  <span m=''4528690''>I</span> <span m=''4528720''>mean,</span> <span m=''4528950''>I</span>
  <span m=''4529060''>can''t</span> <span m=''4529320''>force</span> <span m=''4529580''>them</span>
  <span m=''4529700''>to</span> <span m=''4529770''>go</span> <span m=''4529930''>there.</span>
  <span m=''4530160''>But</span> <span m=''4530320''>if</span> <span m=''4530450''>you</span>
  <span m=''4531080''>set</span> <span m=''4531370''>disks</span> <span m=''4531550''>to</span>
  <span m=''4531650''>the</span> <span m=''4531730''>right</span> <span m=''4531920''>size,</span>
  <span m=''4532200''>they</span> <span m=''4532290''>really</span> <span m=''4532510''>have</span>
  <span m=''4532810''>to</span> <span m=''4532900''>go</span> <span m=''4533050''>there.</span>
  <span m=''4534210''>And</span> <span m=''4534360''>so</span> <span m=''4534650''>all
  of</span> <span m=''4534830''>the</span> <span m=''4534920''>other</span> <span
  m=''4535060''>pockets</span> <span m=''4535460''>will</span> <span m=''4535550''>get</span>
  <span m=''4535950''>even</span> <span m=''4536190''>tinier.</span> <span m=''4536660''>It
  will</span> <span m=''4537450''>destroy</span> <span m=''4537830''>them.</span>
  <span m=''4539910''>That''s</span> <span m=''4540120''>the</span> <span m=''4540200''>infrastructure.</span>
  <span m=''4540850''>It''s</span> <span m=''4541100''>already</span> <span m=''4541450''>pretty</span>
  <span m=''4541680''>crazy.</span> <span m=''4542460''>But</span> <span m=''4542590''>then</span>
  <span m=''4542800''>the</span> <span m=''4542970''>last</span> <span m=''4543250''>part</span>
  <span m=''4543440''>is</span> <span m=''4543550''>actually</span> <span m=''4543830''>kind,</span>
  <span m=''4544120''>is</span> <span m=''4544380''>very</span> <span m=''4544570''>cool</span>
  <span m=''4546510''>and</span> <span m=''4546810''>elegant.</span> </p><p><span
  m=''4549210''>So</span> <span m=''4549370''>I''ve</span> <span m=''4549450''>got</span>
  <span m=''4549640''>these</span> <span m=''4549800''>n over 3</span> <span m=''4550240''>pockets.</span>
  <span m=''4554840''>And</span> <span m=''4554950''>this</span> <span m=''4555120''>was</span>
  <span m=''4555630''>the</span> <span m=''4555740''>central</span> <span m=''4556090''>idea</span>
  <span m=''4556380''>we</span> <span m=''4556470''>started</span> <span m=''4556850''>with.</span>
  <span m=''4557140''>It actually</span> <span m=''4557430''>took</span> <span m=''4557600''>us</span>
  <span m=''4557700''>awhile</span> <span m=''4558040''>to</span> <span m=''4558100''>find</span>
  <span m=''4558340''>this</span> <span m=''4558460''>way</span> <span m=''4558620''>to</span>
  <span m=''4558700''>force</span> <span m=''4559290''>a</span> <span m=''4559360''>bunch</span>
  <span m=''4559630''>of</span> <span m=''4559700''>identical</span> <span m=''4560100''>pockets.</span>
  <span m=''4560870''>It''s</span> <span m=''4561000''>easy</span> <span m=''4561260''>if</span>
  <span m=''4561340''>you</span> <span m=''4561420''>start</span> <span m=''4561670''>from</span>
  <span m=''4561790''>a</span> <span m=''4561850''>triangle of</span> <span m=''4562330''>paper</span>
  <span m=''4562780''>or a</span> <span m=''4562890''>rectangle</span> <span m=''4563145''>of</span>
  <span m=''4563400''>paper.</span> <span m=''4563870''>But we</span> <span m=''4564020''>really</span>
  <span m=''4564220''>wanted</span> <span m=''4564400''>to</span> <span m=''4564510''>start</span>
  <span m=''4564770''>from a</span> <span m=''4564930''>square.</span> <span m=''4566210''>So</span>
  <span m=''4566450''>that''s</span> <span m=''4566650''>the</span> <span m=''4566770''>case</span>
  <span m=''4567090''>we</span> <span m=''4567220''>care</span> <span m=''4567380''>about</span>
  <span m=''4567630''>in</span> <span m=''4567780''>origami.</span> <span m=''4568560''>And</span>
  <span m=''4568900''>so</span> <span m=''4569050''>we</span> <span m=''4569150''>came</span>
  <span m=''4569300''>up</span> <span m=''4569410''>with</span> <span m=''4569520''>that</span>
  <span m=''4569710''>proof.</span> <span m=''4571580''>This</span> <span m=''4571740''>is</span>
  <span m=''4573000''>hard</span> <span m=''4573260''>to</span> <span m=''4573340''>draw</span>
  <span m=''4574400''>perfectly.</span> <span m=''4575840''>Here''s</span> <span m=''4576110''>an</span>
  <span m=''4576220''>equilateral</span> <span m=''4576880''>triangle,</span> <span
  m=''4577430''>so</span> <span m=''4577480''>to</span> <span m=''4577560''>speak,</span>
  <span m=''4577950''>of</span> <span m=''4578010''>equal</span> <span m=''4578300''>radius</span>
  <span m=''4578690''>disks</span> <span m=''4579590''>pairwise</span> <span m=''4580140''>kissing.</span>
  <span m=''4581310''>A</span> <span m=''4581670''>little</span> <span m=''4582500''>slightly</span>
  <span m=''4582880''>wrong</span> <span m=''4583070''>aspect</span> <span m=''4583410''>ratio.</span>
  <span m=''4583860''>But</span> <span m=''4583910''>you</span> <span m=''4583950''>get</span>
  <span m=''4584080''>the</span> <span m=''4584170''>idea.</span> </p><p><span m=''4587800''>I''m</span>
  <span m=''4587900''>going</span> <span m=''4588000''>to</span> <span m=''4588100''>put</span>
  <span m=''4588110''>a</span> <span m=''4588190''>disk</span> <span m=''4588440''>here</span>
  <span m=''4589630''>that</span> <span m=''4590060''>has</span> <span m=''4590260''>a</span>
  <span m=''4590320''>little</span> <span m=''4590630''>bit</span> <span m=''4590760''>of</span>
  <span m=''4590830''>slack.</span> <span m=''4594240''>I''m</span> <span m=''4594350''>going</span>
  <span m=''4594430''>to</span> <span m=''4594490''>put</span> <span m=''4594660''>a</span>
  <span m=''4594760''>disk</span> <span m=''4595140''>here</span> <span m=''4597000''>that--</span>
  <span m=''4599500''>actually,</span> <span m=''4599950''>I''m</span> <span m=''4600040''>going</span>
  <span m=''4600130''>to</span> <span m=''4600200''>draw</span> <span m=''4600380''>them</span>
  <span m=''4600520''>without</span> <span m=''4600850''>slack</span> <span m=''4601190''>first.</span>
  <span m=''4601530''>And</span> <span m=''4601630''>then</span> <span m=''4601760''>I''m</span>
  <span m=''4601830''>going</span> <span m=''4601910''>to</span> <span m=''4601970''>say</span>
  <span m=''4602190''>how</span> <span m=''4602320''>the</span> <span m=''4602390''>slack</span>
  <span m=''4602720''>is.</span> <span m=''4603560''>Because</span> <span m=''4603680''>that''ll</span>
  <span m=''4603820''>be</span> <span m=''4603960''>clearer</span> <span m=''4604280''>what</span>
  <span m=''4604400''>I</span> <span m=''4604460''>mean.</span> <span m=''4605620''>So</span>
  <span m=''4605780''>suppose</span> <span m=''4606180''>this</span> <span m=''4606340''>guy</span>
  <span m=''4606510''>was</span> <span m=''4606670''>actually</span> <span m=''4607030''>kissing</span>
  <span m=''4607370''>all</span> <span m=''4607510''>three.</span> <span m=''4608310''>And</span>
  <span m=''4608500''>this</span> <span m=''4608680''>guy</span> <span m=''4608860''>was</span>
  <span m=''4609000''>kissing</span> <span m=''4609330''>three</span> <span m=''4610560''>and</span>
  <span m=''4611682''>it''s</span> <span m=''4612074''>like</span> <span m=''4612860''>a</span>
  <span m=''4612910''>bunch</span> <span m=''4613150''>of</span> <span m=''4613220''>threesomes</span>
  <span m=''4613720''>here.</span> <span m=''4614265''>All</span> <span m=''4614580''>right,</span>
  <span m=''4614920''>now</span> <span m=''4616940''>I</span> <span m=''4616970''>want</span>
  <span m=''4617190''>to</span> <span m=''4617240''>make</span> <span m=''4617520''>each</span>
  <span m=''4617770''>of</span> <span m=''4617890''>these</span> <span m=''4618180''>disks</span>
  <span m=''4618850''>a</span> <span m=''4618940''>little</span> <span m=''4619330''>bit</span>
  <span m=''4619550''>bigger,</span> <span m=''4620630''>which</span> <span m=''4620790''>will</span>
  <span m=''4620860''>make</span> <span m=''4621050''>this</span> <span m=''4621320''>impossible.</span>
  <span m=''4622670''>But</span> <span m=''4622790''>then</span> <span m=''4622940''>I''m</span>
  <span m=''4623000''>going</span> <span m=''4623090''>to</span> <span m=''4623140''>make</span>
  <span m=''4623320''>this</span> <span m=''4623530''>guy</span> <span m=''4623790''>a</span>
  <span m=''4623860''>little</span> <span m=''4624130''>bit</span> <span m=''4624310''>smaller.</span>
  <span m=''4626100''>So</span> <span m=''4626260''>I''m</span> <span m=''4626330''>going</span>
  <span m=''4626420''>to</span> <span m=''4626460''>make</span> <span m=''4626640''>this</span>
  <span m=''4626860''>one</span> <span m=''4627860''>ai</span> <span m=''4629170''>bigger.</span>
  <span m=''4631745''>I''m going</span> <span m=''4632200''>to</span> <span m=''4632340''>make</span>
  <span m=''4632540''>this</span> <span m=''4632710''>one</span> <span m=''4632910''>aj</span>
  <span m=''4633510''>bigger.</span> <span m=''4637150''>I''m going</span> <span m=''4637420''>to</span>
  <span m=''4637460''>make</span> <span m=''4637720''>this</span> <span m=''4637930''>one</span>
  <span m=''4638760''>ak</span> <span m=''4640207''>bigger.</span> </p><p><span m=''4643620''>And</span>
  <span m=''4643770''>this</span> <span m=''4643990''>one,</span> <span m=''4646120''>what
  did</span> <span m=''4646400''>I</span> <span m=''4646440''>call</span> <span m=''4646660''>it,</span>
  <span m=''4646770''>L,</span> <span m=''4648150''>smaller.</span> <span m=''4651090''>So</span>
  <span m=''4651300''>L</span> <span m=''4651850''>is</span> <span m=''4652130''>the</span>
  <span m=''4652400''>target</span> <span m=''4652830''>sum</span> <span m=''4653740''>for</span>
  <span m=''4654025''>a</span> <span m=''4654310''>triple,</span> <span m=''4660290''>meaning</span>
  <span m=''4661040''>I</span> <span m=''4661110''>take</span> <span m=''4661320''>all</span>
  <span m=''4661550''>the</span> <span m=''4661690''>integers</span> <span m=''4662100''>that</span>
  <span m=''4662200''>I''m</span> <span m=''4662280''>given.</span> <span m=''4663570''>And</span>
  <span m=''4663900''>I</span> <span m=''4666400''>add</span> <span m=''4666600''>them</span>
  <span m=''4666720''>all</span> <span m=''4666920''>up.</span> <span m=''4667790''>And</span>
  <span m=''4667860''>then</span> <span m=''4667960''>I</span> <span m=''4668010''>divide</span>
  <span m=''4668430''>by</span> <span m=''4668550''>n</span> <span m=''4668700''>over</span>
  <span m=''4668880''>3.</span> <span m=''4669580''>That''s</span> <span m=''4669810''>what</span>
  <span m=''4669940''>every</span> <span m=''4670160''>triple</span> <span m=''4670470''>should</span>
  <span m=''4670750''>sum</span> <span m=''4671010''>to.</span> <span m=''4671310''>Because</span>
  <span m=''4671530''>they''re</span> <span m=''4671650''>all</span> <span m=''4671720''>supposed</span>
  <span m=''4672010''>to</span> <span m=''4672050''>be</span> <span m=''4672150''>the</span>
  <span m=''4672230''>same.</span> <span m=''4673770''>So</span> <span m=''4673970''>I</span>
  <span m=''4674020''>call</span> <span m=''4674220''>that</span> <span m=''4674390''>L.</span>
  <span m=''4675030''>This</span> <span m=''4675230''>is</span> <span m=''4675860''>the</span>
  <span m=''4675930''>sum</span> <span m=''4676810''>divided</span> <span m=''4677230''>by</span>
  <span m=''4677400''>n</span> <span m=''4677550''>over</span> <span m=''4677710''>3.</span>
  <span m=''4680820''>So</span> <span m=''4680960''>I''m</span> <span m=''4681020''>going</span>
  <span m=''4681110''>to</span> <span m=''4681160''>make</span> <span m=''4681330''>this</span>
  <span m=''4681520''>one</span> <span m=''4681860''>that</span> <span m=''4682110''>much</span>
  <span m=''4682380''>smaller.</span> <span m=''4683880''>This</span> <span m=''4683940''>is</span>
  <span m=''4684090''>all</span> <span m=''4684240''>slightly</span> <span m=''4684540''>approximate.</span>
  <span m=''4685710''>Bear</span> <span m=''4685870''>with</span> <span m=''4686020''>me.</span>
  </p><p><span m=''4686750''>So</span> <span m=''4686900''>that</span> <span m=''4687070''>gives</span>
  <span m=''4687220''>it a</span> <span m=''4687300''>little</span> <span m=''4687610''>bit</span>
  <span m=''4687720''>of</span> <span m=''4687790''>slack,</span> <span m=''4688680''>which
  is</span> <span m=''4688880''>good</span> <span m=''4689090''>because</span> <span
  m=''4689370''>these</span> <span m=''4689550''>guys</span> <span m=''4689780''>are</span>
  <span m=''4689850''>little</span> <span m=''4690040''>bit</span> <span m=''4690180''>bigger.</span>
  <span m=''4691390''>And</span> <span m=''4691570''>if</span> <span m=''4691780''>they</span>
  <span m=''4691950''>are</span> <span m=''4692060''>bigger,</span> <span m=''4694220''>in</span>
  <span m=''4694440''>total</span> <span m=''4695270''>if</span> <span m=''4695560''>the</span>
  <span m=''4695720''>sum</span> <span m=''4696010''>of</span> <span m=''4696080''>these</span>
  <span m=''4696270''>two</span> <span m=''4696410''>values</span> <span m=''4696790''>is</span>
  <span m=''4696990''>L,</span> <span m=''4697710''>this</span> <span m=''4697880''>will</span>
  <span m=''4698040''>barely</span> <span m=''4698520''>fit.</span> <span m=''4699600''>If</span>
  <span m=''4699750''>it''s</span> <span m=''4699920''>bigger</span> <span m=''4700180''>than</span>
  <span m=''4700340''>L,</span> <span m=''4700600''>it</span> <span m=''4700750''>won''t</span>
  <span m=''4701020''>fit.</span> <span m=''4701610''>If</span> <span m=''4701780''>it''s</span>
  <span m=''4701920''>less</span> <span m=''4702190''>than</span> <span m=''4702290''>L,</span>
  <span m=''4703040''>it</span> <span m=''4703190''>will</span> <span m=''4703360''>fit.</span>
  <span m=''4704710''>But</span> <span m=''4705050''>because</span> <span m=''4705400''>L</span>
  <span m=''4705710''>has</span> <span m=''4706420''>to</span> <span m=''4706510''>be,</span>
  <span m=''4707260''>L</span> <span m=''4707510''>is</span> <span m=''4707630''>always</span>
  <span m=''4707970''>the</span> <span m=''4708220''>average</span> <span m=''4708840''>sum</span>
  <span m=''4709020''>of</span> <span m=''4709110''>the</span> <span m=''4709200''>triples,</span>
  <span m=''4710810''>if</span> <span m=''4711080''>they''re</span> <span m=''4711320''>all</span>
  <span m=''4711670''>going</span> <span m=''4711840''>to--</span> <span m=''4712000''>if</span>
  <span m=''4712190''>you</span> <span m=''4712260''>have</span> <span m=''4712540''>a</span>
  <span m=''4712610''>bunch</span> <span m=''4712890''>of</span> <span m=''4712940''>triples,</span>
  <span m=''4713760''>all</span> <span m=''4713980''>of</span> <span m=''4714080''>whose</span>
  <span m=''4714230''>sum</span> <span m=''4714470''>is</span> <span m=''4714600''>less</span>
  <span m=''4714960''>than</span> <span m=''4715090''>or</span> <span m=''4715190''>equal</span>
  <span m=''4715480''>to</span> <span m=''4715540''>L,</span> <span m=''4716300''>in</span>
  <span m=''4716680''>fact</span> <span m=''4716870''>they</span> <span m=''4716960''>all</span>
  <span m=''4717070''>have</span> <span m=''4717180''>to</span> <span m=''4717290''>be</span>
  <span m=''4717480''>exactly</span> <span m=''4717930''>equal</span> <span m=''4718190''>L.</span>
  <span m=''4719320''>Because</span> <span m=''4719530''>there''s</span> <span m=''4719680''>no</span>
  <span m=''4719840''>slack.</span> </p><p><span m=''4721430''>So</span> <span m=''4721570''>the</span>
  <span m=''4721750''>only</span> <span m=''4722040''>way</span> <span m=''4722190''>for</span>
  <span m=''4722310''>these</span> <span m=''4722490''>guys</span> <span m=''4722690''>to</span>
  <span m=''4722770''>pack,</span> <span m=''4723380''>now</span> <span m=''4723510''>I</span>
  <span m=''4723570''>said</span> <span m=''4723790''>this</span> <span m=''4723930''>is</span>
  <span m=''4724050''>ai,</span> <span m=''4724340''>aj,</span> <span m=''4724630''>ak,</span>
  <span m=''4725290''>in</span> <span m=''4725410''>fact</span> <span m=''4725650''>I''m</span>
  <span m=''4725740''>just</span> <span m=''4725880''>giving</span> <span m=''4726100''>you</span>
  <span m=''4726200''>a</span> <span m=''4726280''>heap,</span> <span m=''4726580''>a</span>
  <span m=''4726680''>bag</span> <span m=''4727030''>of</span> <span m=''4727170''>disks.</span>
  <span m=''4727880''>I</span> <span m=''4728020''>don''t</span> <span m=''4728100''>say</span>
  <span m=''4728260''>which</span> <span m=''4728440''>ones</span> <span m=''4728640''>go</span>
  <span m=''4728790''>where.</span> <span m=''4729600''>You</span> <span m=''4729840''>have</span>
  <span m=''4730060''>to</span> <span m=''4730180''>choose.</span> <span m=''4731220''>So</span>
  <span m=''4731230''>clearly,</span> <span m=''4731680''>these</span> <span m=''4731910''>are</span>
  <span m=''4731990''>all</span> <span m=''4732090''>the</span> <span m=''4732180''>same</span>
  <span m=''4732410''>size.</span> <span m=''4733120''>And</span> <span m=''4733280''>they''re</span>
  <span m=''4733420''>just</span> <span m=''4733560''>going</span> <span m=''4733660''>to</span>
  <span m=''4733710''>go</span> <span m=''4733820''>in</span> <span m=''4733900''>the</span>
  <span m=''4733970''>center.</span> <span m=''4734740''>And</span> <span m=''4734960''>they''ll</span>
  <span m=''4735060''>wiggle</span> <span m=''4735300''>around</span> <span m=''4735570''>a</span>
  <span m=''4735620''>little.</span> <span m=''4737280''>These</span> <span m=''4737560''>guys,</span>
  <span m=''4738870''>you</span> <span m=''4739030''>get</span> <span m=''4739190''>to</span>
  <span m=''4739270''>choose</span> <span m=''4740460''>how</span> <span m=''4740790''>I</span>
  <span m=''4740890''>triple</span> <span m=''4741200''>them</span> <span m=''4741340''>up</span>
  <span m=''4741520''>and</span> <span m=''4741600''>how</span> <span m=''4741770''>I</span>
  <span m=''4741870''>put</span> <span m=''4742070''>them</span> <span m=''4742210''>into</span>
  <span m=''4742390''>these</span> <span m=''4742600''>n</span> <span m=''4742720''>over</span>
  <span m=''4742890''>3</span> <span m=''4743070''>pockets.</span> <span m=''4743910''>So</span>
  <span m=''4744050''>that''s</span> <span m=''4744280''>your</span> <span m=''4744390''>flexibility</span>
  <span m=''4745010''>in</span> <span m=''4745100''>disk</span> <span m=''4745300''>packing.</span>
  <span m=''4745650''>It''s</span> <span m=''4745730''>your</span> <span m=''4745930''>only</span>
  <span m=''4746230''>flexibility</span> <span m=''4746535''>in</span> <span m=''4746840''>disk</span>
  <span m=''4747040''>packing,</span> <span m=''4747700''>is</span> <span m=''4747820''>how</span>
  <span m=''4747970''>you</span> <span m=''4748120''>triple</span> <span m=''4748410''>them</span>
  <span m=''4748560''>up.</span> <span m=''4749200''>And</span> <span m=''4749350''>the</span>
  <span m=''4749490''>only</span> <span m=''4749740''>way</span> <span m=''4749890''>for</span>
  <span m=''4750080''>it</span> <span m=''4750180''>to</span> <span m=''4750200''>work</span>
  <span m=''4750510''>is</span> <span m=''4750630''>if</span> <span m=''4750730''>you</span>
  <span m=''4750830''>can</span> <span m=''4750990''>triple</span> <span m=''4751240''>them</span>
  <span m=''4751380''>up</span> <span m=''4751560''>so</span> <span m=''4751870''>that
  their</span> <span m=''4752000''>sums,</span> <span m=''4752890''>the</span> <span
  m=''4753010''>sum</span> <span m=''4753590''>of</span> <span m=''4753830''>the</span>
  <span m=''4754000''>amount</span> <span m=''4754320''>by</span> <span m=''4754440''>which</span>
  <span m=''4754650''>they</span> <span m=''4754750''>are</span> <span m=''4754850''>bigger,</span>
  <span m=''4755520''>is</span> <span m=''4755620''>exactly</span> <span m=''4756080''>L.</span>
  <span m=''4756480''>Because</span> <span m=''4756630''>that''s</span> <span m=''4756790''>exactly</span>
  <span m=''4757220''>the</span> <span m=''4757330''>slack</span> <span m=''4757660''>of</span>
  <span m=''4757740''>this</span> <span m=''4758020''>disk.</span> <span m=''4758570''>And
  it will</span> <span m=''4758840''>just</span> <span m=''4759110''>fit.</span> <span
  m=''4760740''>Question?</span> </p><p><span m=''4761665''>AUDIENCE:</span> <span
  m=''4762150''>So the fact that</span> <span m=''4762635''>you</span> <span m=''4763120''>have
  an</span> <span m=''4763605''>increase in the</span> <span m=''4764090''>ai,</span>
  <span m=''4764575''>j,</span> <span m=''4765060''>k</span> <span m=''4765545''>[INAUDIBLE]</span>
  <span m=''4768455''>geometry</span> <span m=''4769425''>work out with</span> <span
  m=''4769910''>some tangents</span> <span m=''4770395''>and</span> <span m=''4770880''>stuff?</span>
  </p><p><span m=''4771370''>PROFESSOR: Yeah,</span> <span m=''4771800''>all</span>
  <span m=''4771870''>right.</span> <span m=''4772090''>So</span> <span m=''4772180''>you</span>
  <span m=''4772600''>raise</span> <span m=''4772720''>a</span> <span m=''4772770''>good</span>
  <span m=''4772920''>point,</span> <span m=''4773240''>which</span> <span m=''4773340''>is</span>
  <span m=''4773530''>I</span> <span m=''4773620''>said</span> <span m=''4773880''>this</span>
  <span m=''4774030''>is</span> <span m=''4774500''>ai</span> <span m=''4774790''>bigger.</span>
  <span m=''4775210''>I</span> <span m=''4775270''>didn''t</span> <span m=''4775480''>really</span>
  <span m=''4775660''>mean</span> <span m=''4775940''>that the</span> <span m=''4776070''>radius</span>
  <span m=''4776550''>is</span> <span m=''4776700''>ai</span> <span m=''4776940''>bigger,</span>
  <span m=''4777310''>although</span> <span m=''4777370''>it''s</span> <span m=''4777610''>actually</span>
  <span m=''4777990''>close</span> <span m=''4778320''>to</span> <span m=''4778400''>that.</span>
  <span m=''4780840''>ai</span> <span m=''4781110''>is</span> <span m=''4781200''>an</span>
  <span m=''4781310''>integer.</span> <span m=''4781750''>If</span> <span m=''4781890''>I</span>
  <span m=''4781940''>made</span> <span m=''4782140''>it</span> <span m=''4782600''>that</span>
  <span m=''4782750''>much</span> <span m=''4782930''>bigger,</span> <span m=''4783160''>it
  might</span> <span m=''4783330''>be</span> <span m=''4783710''>huge.</span> <span
  m=''4784320''>But</span> <span m=''4784910''>what</span> <span m=''4785050''>I</span>
  <span m=''4785090''>really</span> <span m=''4785360''>mean</span> <span m=''4785560''>is</span>
  <span m=''4785820''>I</span> <span m=''4785910''>take ai,</span> <span m=''4786140''>I</span>
  <span m=''4786630''>multiply</span> <span m=''4786885''>it</span> <span m=''4787140''>by</span>
  <span m=''4787410''>a</span> <span m=''4787440''>very</span> <span m=''4787820''>small</span>
  <span m=''4788170''>number</span> <span m=''4788770''>greater</span> <span m=''4789020''>than</span>
  <span m=''4789160''>zero</span> <span m=''4789580''>called</span> <span m=''4790210''>epsilon.</span>
  <span m=''4791220''>And</span> <span m=''4791320''>all of</span> <span m=''4791550''>these</span>
  <span m=''4791770''>are</span> <span m=''4791830''>actually</span> <span m=''4793200''>by</span>
  <span m=''4793410''>epsilon.</span> <span m=''4794020''>And</span> <span m=''4794210''>that</span>
  <span m=''4794400''>is</span> <span m=''4794570''>actually</span> <span m=''4795330''>how</span>
  <span m=''4795510''>much</span> <span m=''4795700''>you</span> <span m=''4795780''>change</span>
  <span m=''4796050''>the</span> <span m=''4796140''>radius.</span> <span m=''4797120''>Maybe</span>
  <span m=''4797460''>there''s</span> <span m=''4797600''>a</span> <span m=''4797640''>second</span>
  <span m=''4797920''>order</span> <span m=''4798100''>term.</span> <span m=''4798380''>But</span>
  <span m=''4798710''>to</span> <span m=''4798870''>the</span> <span m=''4798970''>first</span>
  <span m=''4799270''>order,</span> <span m=''4799990''>yeah</span> <span m=''4800650''>you</span>
  <span m=''4800750''>think,</span> <span m=''4801050''>oh,</span> <span m=''4801380''>there''s</span>
  <span m=''4801510''>this trig.</span> <span m=''4801890''>And I''ve</span> <span
  m=''4801940''>got</span> <span m=''4802110''>to do</span> <span m=''4802170''>tangents</span>
  <span m=''4802445''>and</span> <span m=''4802720''>all this</span> <span m=''4803010''>funny</span>
  <span m=''4803270''>stuff.</span> </p><p><span m=''4803990''>It</span> <span m=''4804150''>turns</span>
  <span m=''4804350''>out</span> <span m=''4804480''>to</span> <span m=''4804570''>the</span>
  <span m=''4804650''>first</span> <span m=''4804930''>order,</span> <span m=''4805250''>actually</span>
  <span m=''4805650''>things</span> <span m=''4805860''>work</span> <span m=''4806190''>really</span>
  <span m=''4806500''>simply.</span> <span m=''4807680''>If</span> <span m=''4808290''>I</span>
  <span m=''4808400''>shrink</span> <span m=''4808730''>this</span> <span m=''4808950''>disk</span>
  <span m=''4809920''>by</span> <span m=''4810300''>an</span> <span m=''4810450''>additive</span>
  <span m=''4810890''>amount,</span> <span m=''4813140''>or</span> <span m=''4813200''>sorry,</span>
  <span m=''4813320''>if</span> <span m=''4813440''>I</span> <span m=''4813500''>grow</span>
  <span m=''4813750''>these disks</span> <span m=''4814130''>by</span> <span m=''4814280''>and
  additive</span> <span m=''4814560''>amount,</span> <span m=''4815140''>I</span>
  <span m=''4815250''>shrink</span> <span m=''4815520''>this</span> <span m=''4815830''>by</span>
  <span m=''4816040''>the</span> <span m=''4816170''>same</span> <span m=''4816540''>amount,</span>
  <span m=''4817600''>this</span> <span m=''4817770''>will</span> <span m=''4818230''>still</span>
  <span m=''4818510''>work</span> <span m=''4819800''>up</span> <span m=''4820390''>to</span>
  <span m=''4820480''>the</span> <span m=''4820570''>first</span> <span m=''4820840''>order,</span>
  <span m=''4821710''>so</span> <span m=''4822080''>up</span> <span m=''4822190''>to</span>
  <span m=''4822310''>the</span> <span m=''4822440''>first</span> <span m=''4822690''>derivative.</span>
  <span m=''4823160''>So</span> <span m=''4823210''>you</span> <span m=''4823320''>might</span>
  <span m=''4823470''>have</span> <span m=''4823600''>to</span> <span m=''4823700''>do</span>
  <span m=''4823800''>a</span> <span m=''4823830''>little</span> <span m=''4824030''>bit</span>
  <span m=''4824150''>of</span> <span m=''4824220''>fudging.</span> <span m=''4825090''>I</span>
  <span m=''4825220''>can</span> <span m=''4825350''>just</span> <span m=''4826507''>subtract</span>
  <span m=''4827760''>off</span> <span m=''4827950''>an</span> <span m=''4828040''>epsilon</span>
  <span m=''4828430''>squared</span> <span m=''4828860''>or</span> <span m=''4828970''>something</span>
  <span m=''4829440''>to</span> <span m=''4829980''>give</span> <span m=''4830120''>me</span>
  <span m=''4830270''>just</span> <span m=''4830440''>a</span> <span m=''4830470''>little</span>
  <span m=''4830640''>bit</span> <span m=''4830740''>of</span> <span m=''4830810''>freedom.</span>
  <span m=''4831680''>And</span> <span m=''4831840''>then</span> <span m=''4831940''>this</span>
  <span m=''4832100''>is</span> <span m=''4832250''>actually</span> <span m=''4832600''>how</span>
  <span m=''4832760''>big</span> <span m=''4832970''>the</span> <span m=''4833040''>disks</span>
  <span m=''4833320''>are.</span> </p><p><span m=''4834140''>But</span> <span m=''4834470''>you</span>
  <span m=''4834650''>raise</span> <span m=''4834830''>a</span> <span m=''4834880''>good</span>
  <span m=''4835030''>point.</span> <span m=''4835270''>There''s</span> <span m=''4836140''>details</span>
  <span m=''4836600''>I''m</span> <span m=''4836690''>hiding</span> <span m=''4836990''>here.</span>
  <span m=''4837310''>It''s</span> <span m=''4837760''>actually</span> <span m=''4838830''>pretty</span>
  <span m=''4839010''>clean.</span> <span m=''4839240''>You</span> <span m=''4839330''>work</span>
  <span m=''4839500''>out</span> <span m=''4839590''>the</span> <span m=''4839690''>tangents
  and</span> <span m=''4840110''>things</span> <span m=''4840300''>just</span> <span
  m=''4840490''>are</span> <span m=''4840550''>pretty,</span> <span m=''4841550''>surprisingly.</span>
  <span m=''4842570''>We</span> <span m=''4842710''>thought</span> <span m=''4842900''>this</span>
  <span m=''4843050''>would</span> <span m=''4843130''>be</span> <span m=''4843240''>messy.</span>
  <span m=''4844150''>But</span> <span m=''4844310''>it</span> <span m=''4844530''>actually</span>
  <span m=''4844740''>works</span> <span m=''4844940''>pretty</span> <span m=''4845090''>well.</span>
  <span m=''4846290''>Other</span> <span m=''4846380''>the</span> <span m=''4846460''>questions?</span>
  <span m=''4849420''>All</span> <span m=''4849520''>right.</span> <span m=''4850200''>Now</span>
  <span m=''4850390''>you''re</span> <span m=''4851050''>experts</span> <span m=''4851460''>at</span>
  <span m=''4851680''>NP-hardness</span> <span m=''4852570''>of</span> <span m=''4852690''>origami.</span>
  </p><p><span m=''4857040''>So</span> <span m=''4857180''>here''s</span> <span m=''4857630''>the</span>
  <span m=''4859690''>no</span> <span m=''4860010''>equal</span> <span m=''4860470''>set</span>
  <span m=''4861370''>clause</span> <span m=''4862240''>gadget.</span> <span m=''4863450''>And</span>
  <span m=''4863920''>if</span> <span m=''4864100''>we</span> <span m=''4864240''>fold</span>
  <span m=''4864610''>it</span> <span m=''4864690''>here</span> <span m=''4864940''>with</span>
  <span m=''4865080''>all</span> <span m=''4865410''>of</span> <span m=''4865560''>the</span>
  <span m=''4866770''>incoming</span> <span m=''4867800''>signals</span> <span m=''4868105''>the</span>
  <span m=''4868410''>same</span> <span m=''4868970''>direction,</span> <span m=''4870860''>in</span>
  <span m=''4871290''>the</span> <span m=''4871370''>center</span> <span m=''4872400''>they</span>
  <span m=''4872500''>collide.</span> <span m=''4873520''>You</span> <span m=''4874120''>can''t</span>
  <span m=''4874470''>go</span> <span m=''4875020''>all</span> <span m=''4875200''>the</span>
  <span m=''4875260''>way to flat.</span> <span m=''4875600''>This</span> <span m=''4875940''>thing</span>
  <span m=''4876220''>is not yet</span> <span m=''4876580''>folded.</span> <span m=''4877840''>And</span>
  <span m=''4878095''>it''s</span> <span m=''4878850''>stuck</span> <span m=''4880256''>in
  the</span> <span m=''4880680''>center.</span> <span m=''4881475''>But</span> <span
  m=''4881810''>if</span> <span m=''4882070''>I</span> <span m=''4883490''>flip</span>
  <span m=''4883720''>one</span> <span m=''4883950''>of</span> <span m=''4884060''>them,</span>
  <span m=''4885690''>I''ll</span> <span m=''4885975''>flip</span> <span m=''4886260''>this</span>
  <span m=''4886460''>guy,</span> <span m=''4887570''>then</span> <span m=''4887990''>it</span>
  <span m=''4888350''>very</span> <span m=''4888570''>happily</span> <span m=''4889030''>folds
  flat.</span> <span m=''4889470''>Because</span> <span m=''4889910''>you</span> <span
  m=''4890050''>don''t</span> <span m=''4890240''>get</span> <span m=''4890370''>that</span>
  <span m=''4890540''>collision</span> <span m=''4890860''>because</span> <span m=''4891110''>the</span>
  <span m=''4891170''>center</span> <span m=''4891560''>ends</span> <span m=''4891690''>up</span>
  <span m=''4891880''>going</span> <span m=''4892380''>off</span> <span m=''4892610''>to
  the</span> <span m=''4892940''>side.</span> <span m=''4893880''>And</span> <span
  m=''4894340''>you</span> <span m=''4894490''>can</span> <span m=''4894620''>check</span>
  <span m=''4894920''>that</span> <span m=''4895080''>for</span> <span m=''4895230''>all</span>
  <span m=''4895420''>three,</span> <span m=''4895660''>it''s</span> <span m=''4895800''>actually</span>
  <span m=''4896050''>symmetric.</span> <span m=''4896680''>But</span> <span m=''4896790''>no</span>
  <span m=''4896860''>matter</span> <span m=''4897070''>how</span> <span m=''4897240''>these</span>
  <span m=''4897430''>guys</span> <span m=''4897660''>are</span> <span m=''4897730''>set,</span>
  <span m=''4898025''>if</span> <span m=''4898320''>they''re</span> <span m=''4898460''>all</span>
  <span m=''4898650''>equal,</span> <span m=''4899110''>you</span> <span m=''4899440''>get</span>
  <span m=''4899560''>collision in</span> <span m=''4899950''>the</span> <span m=''4900040''>center.</span>
  <span m=''4900900''>If they''re not</span> <span m=''4901040''>all equal,</span>
  <span m=''4901340''>it</span> <span m=''4901640''>folds</span> <span m=''4901940''>flat.</span>
  </p><p></p>'
type: course
uid: 74a2c93d8d355de8de36b13e46848214

---
None