---
about_this_resource_text: <p><strong>Description:</strong> This lecture begins with
  describing polyhedron unfolding for convex and nonconvex polygons. Algorithms for
  shortest path solutions and unfoldings are presented along with how to determine
  whether an edge unfolding exists.</p><p><strong>Speaker:</strong> Erik Demaine</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: usWjdV0-Jg0
  parent_uid: b850f671a0e779b2c326bdc52ba0e18d
  title: Video-YouTube-Stream
  type: Video
  uid: cb5fb8731596ff758b4b9a13c2ffc043
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/usWjdV0-Jg0/default.jpg
  parent_uid: b850f671a0e779b2c326bdc52ba0e18d
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: c84d08726224ad1ad64087bd930f9108
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: b850f671a0e779b2c326bdc52ba0e18d
  title: Video-iTunes U-MP4
  type: Video
  uid: cab78b3a4de5dbf4b9eadcedc52201c2
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_lec15_300k.mp4
  parent_uid: b850f671a0e779b2c326bdc52ba0e18d
  title: Video-Internet Archive-MP4
  type: Video
  uid: 737c3f9e9d96eb14a59016d7f615b289
- id: 3Play-3PlayYouTubeid-MP4
  media_location: usWjdV0-Jg0
  parent_uid: b850f671a0e779b2c326bdc52ba0e18d
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 3ecd6b2d1a62d096ec1e462dd3172ab9
- id: usWjdV0-Jg0.srt
  parent_uid: b850f671a0e779b2c326bdc52ba0e18d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-15-general-edge-unfolding/usWjdV0-Jg0.srt
  title: 3play caption file
  type: null
  uid: 56c7d1664928693d40fad5b4a84f5da1
- id: usWjdV0-Jg0.pdf
  parent_uid: b850f671a0e779b2c326bdc52ba0e18d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-15-general-edge-unfolding/usWjdV0-Jg0.pdf
  title: 3play pdf file
  type: null
  uid: 2582d5f97cc3f3dd1fbca37b935f7e33
- id: Caption-3Play YouTube id-SRT
  parent_uid: b850f671a0e779b2c326bdc52ba0e18d
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 603c154e9bf41c5c28985c63be4283a6
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b850f671a0e779b2c326bdc52ba0e18d
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: a01abb10be4b51ca9a945cc60b0d0637
inline_embed_id: 49548451lecture15:general&edgeunfolding62036357
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: lecture-15-general-edge-unfolding
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-15-general-edge-unfolding
template_type: Tabbed
title: 'Lecture 15: General & Edge Unfolding'
transcript: '<p><span m=''4900''>PROFESSOR: Today</span> <span m=''5310''>we</span>
  <span m=''5530''>begin</span> <span m=''6360''>the</span> <span m=''6510''>third</span>
  <span m=''7150''>major</span> <span m=''7540''>part</span> <span m=''7790''>of</span>
  <span m=''7880''>the</span> <span m=''7970''>class.</span> <span m=''8370''>We''ve</span>
  <span m=''8540''>done</span> <span m=''9190''>paper</span> <span m=''9440''>folding,</span>
  <span m=''10170''>linkage</span> <span m=''10540''>folding,</span> <span m=''11130''>and</span>
  <span m=''11290''>now</span> <span m=''11500''>we''re</span> <span m=''11610''>going</span>
  <span m=''11720''>to</span> <span m=''11800''>do</span> <span m=''12540''>polyhedron</span>
  <span m=''13030''>folding.</span> <span m=''25860''>The</span> <span m=''25950''>very</span>
  <span m=''26310''>last</span> <span m=''26660''>topic</span> <span m=''26950''>we</span>
  <span m=''27060''>did</span> <span m=''27260''>was</span> <span m=''27460''>hinged</span>
  <span m=''27740''>dissection,</span> <span m=''28220''>which</span> <span m=''28410''>is</span>
  <span m=''28510''>somewhere</span> <span m=''28850''>in</span> <span m=''28910''>the</span>
  <span m=''29000''>middle</span> <span m=''29270''>of</span> <span m=''29360''>all</span>
  <span m=''29590''>these</span> <span m=''29800''>things.</span> <span m=''31320''>But</span>
  <span m=''31460''>with</span> <span m=''31660''>polyhedron</span> <span m=''32150''>folding,</span>
  <span m=''32479''>we''re</span> <span m=''32600''>thinking</span> <span m=''32980''>about</span>
  <span m=''33390''>a</span> <span m=''33550''>two</span> <span m=''33690''>dimensional</span>
  <span m=''34130''>surface</span> <span m=''34650''>in</span> <span m=''34890''>3D,</span>
  <span m=''36570''>something</span> <span m=''36980''>like a</span> <span m=''37390''>cube,</span>
  <span m=''40210''>and</span> <span m=''40620''>we''re</span> <span m=''40760''>interested</span>
  <span m=''41400''>in</span> <span m=''41680''>cutting</span> <span m=''42070''>along</span>
  <span m=''43500''>the</span> <span m=''43670''>edges</span> <span m=''44920''>of</span>
  <span m=''45140''>that</span> <span m=''46560''>shape</span> <span m=''51290''>or</span>
  <span m=''51400''>somehow</span> <span m=''51740''>cutting</span> <span m=''52000''>along</span>
  <span m=''52260''>the</span> <span m=''52330''>surface--</span> <span m=''55220''>that''s</span>
  <span m=''55470''>a</span> <span m=''55810''>good</span> <span m=''56060''>cutting--</span>
  <span m=''57610''>and</span> <span m=''57920''>then</span> <span m=''58250''>unfolding</span>
  <span m=''61300''>into</span> <span m=''62390''>some</span> <span m=''62740''>flat</span>
  <span m=''63050''>shape.</span> <span m=''70770''>So</span> <span m=''70960''>this</span>
  <span m=''71140''>is</span> <span m=''71220''>a</span> <span m=''71300''>standard</span>
  <span m=''71680''>cross</span> <span m=''72070''>unfolding</span> <span m=''72980''>of</span>
  <span m=''73150''>the</span> <span m=''73250''>cube.</span> </p><p><span m=''73920''>This</span>
  <span m=''74160''>is</span> <span m=''74290''>the</span> <span m=''74460''>unfolding</span>
  <span m=''74970''>process,</span> <span m=''76650''>and</span> <span m=''76740''>of</span>
  <span m=''76820''>course</span> <span m=''77080''>the</span> <span m=''77200''>reverse</span>
  <span m=''78310''>is</span> <span m=''78580''>the</span> <span m=''78650''>folding</span>
  <span m=''78990''>process,</span> <span m=''83330''>and</span> <span m=''83730''>both</span>
  <span m=''83970''>of</span> <span m=''84040''>them</span> <span m=''84170''>are</span>
  <span m=''84290''>interesting.</span> <span m=''85090''>We''re</span> <span m=''85250''>going</span>
  <span m=''85350''>to</span> <span m=''85420''>start</span> <span m=''85970''>thinking</span>
  <span m=''86300''>about</span> <span m=''86530''>unfolding.</span> <span m=''87350''>That''s</span>
  <span m=''87850''>one</span> <span m=''88060''>of</span> <span m=''88160''>the</span>
  <span m=''88240''>most</span> <span m=''88670''>practical</span> <span m=''89180''>problems</span>
  <span m=''89650''>here.</span> <span m=''90190''>You</span> <span m=''90540''>really</span>
  <span m=''90840''>want</span> <span m=''91050''>to</span> <span m=''91110''>build</span>
  <span m=''91470''>some</span> <span m=''93160''>3D</span> <span m=''93460''>shape</span>
  <span m=''94240''>out</span> <span m=''94480''>of</span> <span m=''94770''>sheet</span>
  <span m=''95040''>material.</span> <span m=''95860''>What</span> <span m=''96150''>shape
  do</span> <span m=''96480''>you</span> <span m=''96640''>cut</span> <span m=''96870''>out</span>
  <span m=''97450''>in</span> <span m=''97700''>order</span> <span m=''97930''>to</span>
  <span m=''98310''>bend</span> <span m=''98570''>it</span> <span m=''98660''>into</span>
  <span m=''98940''>that</span> <span m=''99750''>surface?</span> </p><p><span m=''101430''>So</span>
  <span m=''101530''>you</span> <span m=''101640''>start</span> <span m=''101910''>with</span>
  <span m=''102000''>the</span> <span m=''102080''>surface.</span> <span m=''102550''>You</span>
  <span m=''102620''>need</span> <span m=''102770''>to</span> <span m=''102820''>figure</span>
  <span m=''103080''>out</span> <span m=''103160''>where</span> <span m=''103340''>to</span>
  <span m=''103430''>cut</span> <span m=''104000''>so</span> <span m=''104170''>that</span>
  <span m=''104290''>when</span> <span m=''104490''>you</span> <span m=''104880''>unfold,</span>
  <span m=''106110''>you</span> <span m=''106240''>get</span> <span m=''106440''>something</span>
  <span m=''106800''>that</span> <span m=''107520''>has</span> <span m=''107850''>no</span>
  <span m=''108000''>overlap.</span> <span m=''108660''>If</span> <span m=''108710''>you</span>
  <span m=''108830''>want</span> <span m=''108940''>to</span> <span m=''108990''>make</span>
  <span m=''109170''>it</span> <span m=''109250''>from</span> <span m=''109390''>one</span>
  <span m=''109560''>sheet,</span> <span m=''109870''>it shouldn''t</span> <span m=''110140''>have</span>
  <span m=''110310''>any</span> <span m=''110480''>overlap,</span> <span m=''111390''>and</span>
  <span m=''112110''>ideally</span> <span m=''112520''>just</span> <span m=''112740''>one</span>
  <span m=''112940''>piece</span> <span m=''113410''>because</span> <span m=''113620''>then</span>
  <span m=''113770''>you</span> <span m=''113860''>have</span> <span m=''114020''>to</span>
  <span m=''114130''>do</span> <span m=''114280''>less</span> <span m=''114590''>welding</span>
  <span m=''115870''>or</span> <span m=''116240''>edge</span> <span m=''116520''>joining</span>
  <span m=''116970''>to</span> <span m=''117260''>make</span> <span m=''118080''>that</span>
  <span m=''118850''>surface.</span> <span m=''121230''>So</span> <span m=''121410''>today</span>
  <span m=''121770''>and</span> <span m=''121920''>the</span> <span m=''122060''>next</span>
  <span m=''122460''>couple</span> <span m=''122700''>lectures</span> <span m=''123060''>will</span>
  <span m=''123180''>be</span> <span m=''123370''>all</span> <span m=''123490''>about</span>
  <span m=''123760''>unfolding,</span> <span m=''124350''>and</span> <span m=''124430''>then</span>
  <span m=''124590''>eventually</span> <span m=''124990''>we</span> <span m=''125120''>will</span>
  <span m=''125310''>turn</span> <span m=''125490''>to</span> <span m=''125620''>the</span>
  <span m=''125710''>reverse</span> <span m=''126050''>problem,</span> <span m=''127800''>folding</span>
  <span m=''128180''>problem.</span> </p><p><span m=''129380''>And</span> <span m=''129620''>there</span>
  <span m=''129780''>are</span> <span m=''130050''>two</span> <span m=''130300''>kinds</span>
  <span m=''130810''>of</span> <span m=''131460''>unfolding.</span> <span m=''132440''>The</span>
  <span m=''132570''>one</span> <span m=''132800''>that</span> <span m=''132920''>I</span>
  <span m=''133010''>just</span> <span m=''133280''>drew</span> <span m=''134160''>is</span>
  <span m=''134940''>an</span> <span m=''135160''>edge</span> <span m=''135480''>unfolding</span>
  <span m=''136000''>because</span> <span m=''136170''>it</span> <span m=''136270''>only</span>
  <span m=''136570''>cuts</span> <span m=''136840''>along</span> <span m=''137160''>edges.</span>
  <span m=''140010''>Edge</span> <span m=''140290''>unfolding</span> <span m=''149010''>only</span>
  <span m=''149310''>cut</span> <span m=''149530''>along</span> <span m=''150140''>edges</span>
  <span m=''150730''>of</span> <span m=''151070''>the</span> <span m=''151170''>surface.</span>
  <span m=''153970''>This</span> <span m=''154120''>property</span> <span m=''154490''>is</span>
  <span m=''154610''>nice.</span> <span m=''155010''>If</span> <span m=''155910''>you''re</span>
  <span m=''156070''>building</span> <span m=''156460''>something,</span> <span m=''156980''>you</span>
  <span m=''157080''>don''t</span> <span m=''157280''>want</span> <span m=''157430''>to</span>
  <span m=''157470''>have</span> <span m=''157680''>visible</span> <span m=''158070''>seems.</span>
  <span m=''160090''>You</span> <span m=''160330''>have</span> <span m=''160590''>to</span>
  <span m=''160700''>be</span> <span m=''160830''>bent</span> <span m=''161150''>at</span>
  <span m=''161230''>the</span> <span m=''161370''>edges,</span> <span m=''161850''>so</span>
  <span m=''162050''>it''s</span> <span m=''162170''>not</span> <span m=''162450''>such</span>
  <span m=''162720''>a</span> <span m=''162780''>big</span> <span m=''162950''>deal</span>
  <span m=''163220''>if</span> <span m=''163330''>you''re</span> <span m=''163480''>also</span>
  <span m=''165070''>fusing</span> <span m=''165550''>along</span> <span m=''165840''>an</span>
  <span m=''165910''>edge.</span> </p><p><span m=''167070''>But</span> <span m=''167200''>in</span>
  <span m=''167300''>general,</span> <span m=''167760''>you</span> <span m=''167800''>could</span>
  <span m=''167920''>imagine</span> <span m=''168270''>cutting</span> <span m=''168630''>anywhere</span>
  <span m=''169050''>on</span> <span m=''169140''>the</span> <span m=''169210''>surface,</span>
  <span m=''169810''>and</span> <span m=''169930''>this</span> <span m=''170090''>is</span>
  <span m=''170200''>an</span> <span m=''170280''>example</span> <span m=''171340''>where</span>
  <span m=''171450''>the</span> <span m=''171670''>solid</span> <span m=''172130''>red</span>
  <span m=''172330''>lines</span> <span m=''172650''>are</span> <span m=''172740''>cutting</span>
  <span m=''173060''>on</span> <span m=''173230''>what</span> <span m=''173370''>you</span>
  <span m=''173510''>see</span> <span m=''173830''>and</span> <span m=''173930''>the</span>
  <span m=''174040''>dotted</span> <span m=''174490''>red</span> <span m=''174640''>lines</span>
  <span m=''174900''>were</span> <span m=''175000''>cutting</span> <span m=''176170''>on</span>
  <span m=''176270''>the</span> <span m=''176360''>backside.</span> <span m=''177510''>And</span>
  <span m=''177730''>when</span> <span m=''177860''>you</span> <span m=''178000''>unfold</span>
  <span m=''178400''>that</span> <span m=''178620''>thing,</span> <span m=''178850''>you</span>
  <span m=''178990''>get</span> <span m=''179230''>this</span> <span m=''179620''>stoplight</span>
  <span m=''180690''>polygon,</span> <span m=''182150''>and</span> <span m=''182810''>this</span>
  <span m=''183200''>is</span> <span m=''183380''>what</span> <span m=''183580''>we</span>
  <span m=''183730''>call</span> <span m=''184070''>a</span> <span m=''184130''>general</span>
  <span m=''184560''>unfolding,</span> <span m=''185240''>or</span> <span m=''185400''>just</span>
  <span m=''185620''>unfolding.</span> <span m=''188290''>There</span> <span m=''188520''>you</span>
  <span m=''188660''>can</span> <span m=''188780''>cut</span> <span m=''189030''>anywhere.</span>
  <span m=''190010''>In</span> <span m=''190170''>both</span> <span m=''190420''>cases,</span>
  <span m=''191700''>we</span> <span m=''191810''>want</span> <span m=''192070''>one</span>
  <span m=''192310''>piece,</span> <span m=''192780''>no</span> <span m=''192960''>overlap,</span>
  <span m=''196810''>but</span> <span m=''197070''>you</span> <span m=''197190''>can</span>
  <span m=''197370''>change</span> <span m=''198600''>where</span> <span m=''198870''>you''re</span>
  <span m=''199030''>allowed</span> <span m=''199290''>to</span> <span m=''199380''>cut.</span>
  <span m=''220230''>So</span> <span m=''220470''>those</span> <span m=''220590''>are</span>
  <span m=''220680''>the</span> <span m=''221010''>rules</span> <span m=''221320''>of</span>
  <span m=''221400''>the</span> <span m=''221480''>game,</span> <span m=''222120''>or</span>
  <span m=''222260''>two</span> <span m=''222430''>possible</span> <span m=''223670''>rules</span>
  <span m=''223970''>of</span> <span m=''224040''>the</span> <span m=''224130''>game.</span>
  </p><p><span m=''225580''>And</span> <span m=''225930''>let</span> <span m=''226050''>me</span>
  <span m=''226170''>tell</span> <span m=''226390''>you</span> <span m=''226590''>what''s</span>
  <span m=''226850''>known</span> <span m=''227080''>about</span> <span m=''229880''>these</span>
  <span m=''230070''>kinds</span> <span m=''230350''>of</span> <span m=''230420''>unfoldings.</span>
  <span m=''231930''>I''ve</span> <span m=''232420''>mentioned</span> <span m=''232820''>it
  way</span> <span m=''232940''>back</span> <span m=''233200''>in</span> <span m=''233270''>lecture</span>
  <span m=''233580''>one.</span> <span m=''267010''>so</span> <span m=''267230''>we</span>
  <span m=''267340''>can</span> <span m=''267420''>think</span> <span m=''267560''>about</span>
  <span m=''267750''>edge</span> <span m=''267940''>unfolding,</span> <span m=''268370''>we</span>
  <span m=''268470''>can</span> <span m=''268600''>think</span> <span m=''268760''>about</span>
  <span m=''268970''>general</span> <span m=''269290''>unfolding,</span> <span m=''269800''>and</span>
  <span m=''269880''>we</span> <span m=''270000''>can</span> <span m=''270150''>think</span>
  <span m=''270340''>about</span> <span m=''270600''>them</span> <span m=''270740''>for</span>
  <span m=''270920''>convex</span> <span m=''271400''>polyhedra--</span> <span m=''272340''>simple</span>
  <span m=''272660''>things</span> <span m=''272990''>like</span> <span m=''273210''>the</span>
  <span m=''273260''>cube</span> <span m=''274130''>have</span> <span m=''274320''>no</span>
  <span m=''274450''>dents--</span> <span m=''275580''>or</span> <span m=''275920''>general</span>
  <span m=''276720''>polyhedra,</span> <span m=''277350''>non-convex</span> <span
  m=''277850''>polyhedra.</span> <span m=''280350''>And</span> <span m=''281510''>status</span>
  <span m=''281860''>is</span> <span m=''284230''>these</span> <span m=''284540''>two</span>
  <span m=''284710''>corners</span> <span m=''285170''>are</span> <span m=''285300''>open.</span>
  <span m=''289860''>This</span> <span m=''290110''>one</span> <span m=''291885''>is</span>
  <span m=''292270''>solved.</span> <span m=''292655''>It</span> <span m=''293040''>can</span>
  <span m=''293230''>always</span> <span m=''293600''>be</span> <span m=''293720''>done.</span>
  <span m=''293960''>You</span> <span m=''294060''>can</span> <span m=''294230''>always</span>
  <span m=''294560''>generally</span> <span m=''295110''>unfold</span> <span m=''295610''>a</span>
  <span m=''295680''>convex</span> <span m=''296180''>polyhedron,</span> <span m=''297300''>but</span>
  <span m=''297420''>we</span> <span m=''297530''>don''t</span> <span m=''297730''>know</span>
  <span m=''297990''>about</span> <span m=''298400''>general</span> <span m=''298740''>polyhedra.</span>
  </p><p><span m=''301080''>Edge</span> <span m=''301350''>unfolding</span> <span
  m=''301820''>of</span> <span m=''301880''>convex</span> <span m=''302270''>polyhedra,</span>
  <span m=''302810''>we</span> <span m=''302940''>don''t</span> <span m=''303180''>know</span>
  <span m=''303740''>whether</span> <span m=''304020''>it''s</span> <span m=''304150''>possible,</span>
  <span m=''305340''>but</span> <span m=''305580''>for</span> <span m=''305690''>non-convex</span>
  <span m=''305890''>polyhedra,</span> <span m=''306640''>we</span> <span m=''306730''>know</span>
  <span m=''306860''>that''s</span> <span m=''307090''>too</span> <span m=''307210''>much</span>
  <span m=''307440''>to</span> <span m=''307650''>hope</span> <span m=''307990''>for.</span>
  <span m=''311170''>Not</span> <span m=''311410''>always</span> <span m=''311620''>possible.</span>
  <span m=''314390''>Both</span> <span m=''314680''>of</span> <span m=''314770''>these</span>
  <span m=''314910''>questions</span> <span m=''315340''>could</span> <span m=''315540''>go</span>
  <span m=''315710''>either</span> <span m=''316000''>way,</span> <span m=''318400''>but</span>
  <span m=''318550''>we</span> <span m=''318670''>know</span> <span m=''318990''>in</span>
  <span m=''319990''>various</span> <span m=''320330''>generalizations,</span> <span
  m=''321620''>easy</span> <span m=''321930''>case</span> <span m=''322320''>of</span>
  <span m=''322470''>convex</span> <span m=''322840''>polyhedra</span> <span m=''323260''>general</span>
  <span m=''323550''>unfolding,</span> <span m=''323910''>we</span> <span m=''324010''>can</span>
  <span m=''324160''>do</span> <span m=''324340''>it.</span> <span m=''326450''>The</span>
  <span m=''326540''>most</span> <span m=''326780''>restrictive,</span> <span m=''327680''>hardest</span>
  <span m=''327980''>situation</span> <span m=''328260''>is</span> <span m=''328540''>edge</span>
  <span m=''328750''>unfolding</span> <span m=''329560''>non-convex</span> <span m=''329740''>polyhedra.</span>
  <span m=''330470''>That''s</span> <span m=''330750''>too</span> <span m=''330910''>much.</span>
  <span m=''331680''>But</span> <span m=''331810''>each</span> <span m=''332020''>of</span>
  <span m=''332100''>these</span> <span m=''332300''>things,</span> <span m=''332990''>we</span>
  <span m=''333100''>don''t</span> <span m=''333270''>know.</span> </p><p><span m=''334120''>And</span>
  <span m=''334320''>these</span> <span m=''334490''>are</span> <span m=''334570''>some</span>
  <span m=''334780''>of</span> <span m=''334850''>the</span> <span m=''334930''>biggest</span>
  <span m=''335320''>open</span> <span m=''335530''>questions</span> <span m=''335980''>remaining</span>
  <span m=''336480''>in</span> <span m=''336750''>geometric</span> <span m=''338040''>folding</span>
  <span m=''338540''>algorithms,</span> <span m=''339250''>this</span> <span m=''339460''>field.</span>
  <span m=''341330''>I''m</span> <span m=''341550''>going</span> <span m=''341640''>to</span>
  <span m=''341720''>talk</span> <span m=''343130''>mostly</span> <span m=''343660''>about</span>
  <span m=''346350''>these</span> <span m=''346830''>three</span> <span m=''347110''>things</span>
  <span m=''347470''>today,</span> <span m=''348580''>so</span> <span m=''349080''>this</span>
  <span m=''349340''>open</span> <span m=''349600''>problem</span> <span m=''350400''>and</span>
  <span m=''350530''>these</span> <span m=''350760''>two</span> <span m=''351790''>results.</span>
  <span m=''352580''>And</span> <span m=''352780''>then</span> <span m=''353270''>this</span>
  <span m=''353780''>topic</span> <span m=''354230''>will</span> <span m=''354440''>essentially</span>
  <span m=''354840''>be</span> <span m=''354980''>next</span> <span m=''355370''>lecture.</span>
  <span m=''356920''>Obviously</span> <span m=''357440''>it''s</span> <span m=''357750''>not</span>
  <span m=''357970''>solved,</span> <span m=''358540''>but</span> <span m=''358890''>we</span>
  <span m=''359040''>still</span> <span m=''359260''>have</span> <span m=''359370''>a</span>
  <span m=''359410''>lot</span> <span m=''359620''>to</span> <span m=''359700''>say.</span>
  <span m=''360410''>There</span> <span m=''360520''>are</span> <span m=''360540''>various</span>
  <span m=''360810''>partial</span> <span m=''361120''>results</span> <span m=''361540''>toward</span>
  <span m=''361890''>solving</span> <span m=''363020''>both</span> <span m=''363230''>of</span>
  <span m=''363320''>those</span> <span m=''364940''>problems,</span> <span m=''365640''>I</span>
  <span m=''365740''>would</span> <span m=''365870''>say</span> <span m=''365980''>more</span>
  <span m=''366310''>on</span> <span m=''366400''>this</span> <span m=''366580''>one.</span>
  <span m=''368590''>This</span> <span m=''368770''>one</span> <span m=''368940''>is</span>
  <span m=''369070''>five</span> <span m=''369415''>centuries</span> <span m=''369760''>old.</span>
  <span m=''370780''>This</span> <span m=''370980''>one</span> <span m=''371210''>is</span>
  <span m=''372800''>one</span> <span m=''373080''>decade</span> <span m=''373450''>old</span>
  <span m=''373960''>or</span> <span m=''374260''>so.</span> </p><p><span m=''386230''>So</span>
  <span m=''386460''>I</span> <span m=''386550''>need</span> <span m=''386710''>to</span>
  <span m=''386800''>set</span> <span m=''386980''>the</span> <span m=''387070''>stage</span>
  <span m=''387340''>a</span> <span m=''387390''>little</span> <span m=''387580''>bit</span>
  <span m=''387740''>before</span> <span m=''388030''>I</span> <span m=''388050''>can</span>
  <span m=''388220''>talk</span> <span m=''388450''>about</span> <span m=''388730''>any</span>
  <span m=''388960''>of</span> <span m=''389030''>these</span> <span m=''389250''>things,</span>
  <span m=''390400''>so</span> <span m=''391240''>let</span> <span m=''391450''>me</span>
  <span m=''391590''>start</span> <span m=''392050''>with</span> <span m=''392680''>a</span>
  <span m=''392760''>little</span> <span m=''393040''>bit</span> <span m=''393180''>of</span>
  <span m=''393260''>terminology.</span> <span m=''400220''>We''ve</span> <span m=''401060''>in</span>
  <span m=''401160''>some</span> <span m=''401350''>sense</span> <span m=''401550''>talked</span>
  <span m=''401810''>about</span> <span m=''402070''>curvature</span> <span m=''402580''>before.</span>
  <span m=''403080''>I</span> <span m=''403130''>don''t</span> <span m=''403360''>think</span>
  <span m=''403550''>I</span> <span m=''403600''>gave</span> <span m=''403820''>it</span>
  <span m=''403930''>this</span> <span m=''404140''>name,</span> <span m=''404400''>though,</span>
  <span m=''404810''>in</span> <span m=''405010''>the</span> <span m=''405100''>context
  of</span> <span m=''405510''>origami.</span> <span m=''410860''>And</span> <span
  m=''411120''>I</span> <span m=''411200''>use</span> <span m=''411480''>it</span>
  <span m=''411810''>almost</span> <span m=''412210''>subconsciously</span> <span
  m=''412990''>so</span> <span m=''413230''>it''s</span> <span m=''413390''>good</span>
  <span m=''413540''>for</span> <span m=''413710''>me</span> <span m=''413860''>to</span>
  <span m=''414010''>define</span> <span m=''414420''>it.</span> </p><p><span m=''420810''>If</span>
  <span m=''420940''>you</span> <span m=''421010''>have</span> <span m=''421170''>some</span>
  <span m=''421390''>vertex</span> <span m=''422720''>on</span> <span m=''422890''>your</span>
  <span m=''423090''>polyhedron.</span> <span m=''423740''>Let''s</span> <span m=''423980''>say</span>
  <span m=''424990''>we''re</span> <span m=''425120''>looking</span> <span m=''425420''>at</span>
  <span m=''425540''>a</span> <span m=''425610''>corner</span> <span m=''425890''>of</span>
  <span m=''425950''>a</span> <span m=''426000''>cube,</span> <span m=''427070''>so</span>
  <span m=''427250''>this</span> <span m=''427490''>has</span> <span m=''427730''>three</span>
  <span m=''428542''>90</span> <span m=''428950''>degree</span> <span m=''429220''>angles</span>
  <span m=''430150''>coming</span> <span m=''430430''>together.</span> <span m=''432660''>You</span>
  <span m=''432800''>sum</span> <span m=''433120''>those</span> <span m=''433330''>angles,</span>
  <span m=''434070''>we</span> <span m=''434220''>get</span> <span m=''434800''>270,</span>
  <span m=''437200''>and</span> <span m=''437440''>then</span> <span m=''437600''>you</span>
  <span m=''437700''>take</span> <span m=''437920''>360</span> <span m=''438550''>minus</span>
  <span m=''439050''>that</span> <span m=''439300''>sum,</span> <span m=''440110''>and</span>
  <span m=''440390''>that</span> <span m=''440680''>is</span> <span m=''440820''>your</span>
  <span m=''441060''>curvature.</span> <span m=''442875''>This</span> <span m=''443290''>is</span>
  <span m=''443450''>going</span> <span m=''443580''>to</span> <span m=''443650''>be</span>
  <span m=''443820''>90.</span> </p><p><span m=''446180''>And</span> <span m=''446450''>what</span>
  <span m=''446580''>I</span> <span m=''446630''>really</span> <span m=''446890''>care</span>
  <span m=''447120''>about</span> <span m=''447470''>is</span> <span m=''447800''>whether</span>
  <span m=''448020''>the</span> <span m=''448130''>curvature</span> <span m=''448550''>is</span>
  <span m=''448690''>positive,</span> <span m=''449460''>0,</span> <span m=''449800''>or</span>
  <span m=''451250''>negative.</span> <span m=''459520''>Positive</span> <span m=''459950''>curvature,</span>
  <span m=''460400''>which</span> <span m=''460570''>is</span> <span m=''460660''>what</span>
  <span m=''460780''>we</span> <span m=''460900''>got</span> <span m=''461080''>here--</span>
  <span m=''461250''>this</span> <span m=''461410''>is</span> <span m=''461500''>plus</span>
  <span m=''461840''>90--</span> <span m=''463200''>is</span> <span m=''463560''>like</span>
  <span m=''463790''>a</span> <span m=''463880''>convex</span> <span m=''464400''>cone.</span>
  <span m=''471970''>So</span> <span m=''472260''>if</span> <span m=''472410''>you''re</span>
  <span m=''472610''>thinking</span> <span m=''472880''>about</span> <span m=''473100''>convex</span>
  <span m=''473540''>polyhedra,</span> <span m=''474130''>which</span> <span m=''474360''>is</span>
  <span m=''474940''>one</span> <span m=''475160''>of</span> <span m=''475200''>the</span>
  <span m=''475270''>situations</span> <span m=''475790''>we</span> <span m=''475890''>care</span>
  <span m=''476090''>about,</span> <span m=''476370''>you''ll</span> <span m=''476550''>always</span>
  <span m=''476930''>get</span> <span m=''477510''>positive</span> <span m=''478920''>or</span>
  <span m=''479140''>0,</span> <span m=''479700''>maybe,</span> <span m=''481310''>curvature</span>
  <span m=''481700''>vertices,</span> <span m=''482180''>depending</span> <span m=''482570''>on</span>
  <span m=''483010''>what</span> <span m=''483160''>you''re</span> <span m=''483260''>thinking</span>
  <span m=''483590''>about.</span> </p><p><span m=''484120''>Zero,</span> <span m=''484510''>this</span>
  <span m=''484710''>is</span> <span m=''484810''>like</span> <span m=''484990''>a</span>
  <span m=''485060''>piece</span> <span m=''485260''>of</span> <span m=''485330''>paper,</span>
  <span m=''486250''>so</span> <span m=''486320''>this</span> <span m=''486490''>is</span>
  <span m=''486620''>what</span> <span m=''486780''>you</span> <span m=''486870''>might</span>
  <span m=''487040''>call</span> <span m=''487250''>flat,</span> <span m=''489220''>but</span>
  <span m=''489560''>it''s</span> <span m=''489980''>locally</span> <span m=''490370''>flat.</span>
  <span m=''490680''>It</span> <span m=''490770''>could</span> <span m=''491000''>be</span>
  <span m=''491730''>drawn</span> <span m=''492120''>flat</span> <span m=''492770''>or</span>
  <span m=''493900''>we</span> <span m=''493990''>know</span> <span m=''494200''>how</span>
  <span m=''494340''>to</span> <span m=''494420''>fold</span> <span m=''494780''>pieces</span>
  <span m=''495080''>of</span> <span m=''495160''>paper.</span> <span m=''496790''>You</span>
  <span m=''496900''>never</span> <span m=''497120''>change</span> <span m=''497460''>the</span>
  <span m=''497550''>curvature.</span> <span m=''498380''>The</span> <span m=''498460''>sum
  of the</span> <span m=''498780''>instant face</span> <span m=''498980''>angles</span>
  <span m=''499200''>will</span> <span m=''499270''>always</span> <span m=''499540''>stay</span>
  <span m=''499690''>the</span> <span m=''499800''>same,</span> <span m=''500100''>no</span>
  <span m=''500180''>matter</span> <span m=''500400''>how</span> <span m=''500530''>you</span>
  <span m=''500660''>fold</span> <span m=''500900''>this</span> <span m=''501080''>thing.</span>
  <span m=''501730''>Curvature</span> <span m=''501990''>is</span> <span m=''502250''>an</span>
  <span m=''502350''>invariant.</span> <span m=''505780''>If</span> <span m=''505900''>you</span>
  <span m=''505980''>just</span> <span m=''506190''>think</span> <span m=''506360''>locally</span>
  <span m=''506810''>and</span> <span m=''506910''>forget</span> <span m=''507160''>about</span>
  <span m=''507570''>the</span> <span m=''507640''>actual</span> <span m=''508280''>folding</span>
  <span m=''509020''>of</span> <span m=''509120''>the</span> <span m=''509240''>thing,</span>
  <span m=''509540''>it''s</span> <span m=''509840''>kind</span> <span m=''510050''>of</span>
  <span m=''510120''>flat.</span> <span m=''512169''>So</span> <span m=''512320''>you</span>
  <span m=''512400''>can</span> <span m=''512520''>think</span> <span m=''512659''>of</span>
  <span m=''512730''>this</span> <span m=''512950''>as</span> <span m=''513179''>a</span>
  <span m=''513210''>piece</span> <span m=''513429''>of</span> <span m=''513500''>paper.</span>
  </p><p><span m=''514360''>We</span> <span m=''514490''>talked</span> <span m=''514760''>about</span>
  <span m=''514929''>these</span> <span m=''515100''>two</span> <span m=''515230''>situations</span>
  <span m=''515960''>in</span> <span m=''516070''>the</span> <span m=''516179''>context</span>
  <span m=''516630''>of</span> <span m=''516720''>Kawasaki''s</span> <span m=''517390''>theorem</span>
  <span m=''518120''>way</span> <span m=''518270''>back</span> <span m=''518539''>when.</span>
  <span m=''518720''>Kawasaki''s</span> <span m=''519280''>theorem</span> <span m=''519470''>applied</span>
  <span m=''519830''>for</span> <span m=''519940''>both</span> <span m=''520169''>of</span>
  <span m=''520250''>these</span> <span m=''520490''>for</span> <span m=''520600''>the</span>
  <span m=''520710''>negative</span> <span m=''521080''>curvature</span> <span m=''521470''>case,</span>
  <span m=''522260''>which</span> <span m=''522530''>is</span> <span m=''522590''>when</span>
  <span m=''522730''>you</span> <span m=''522799''>have</span> <span m=''522970''>lots</span>
  <span m=''523429''>of</span> <span m=''523520''>material</span> <span m=''524400''>all</span>
  <span m=''524900''>joined</span> <span m=''525220''>at</span> <span m=''525290''>a</span>
  <span m=''525410''>single</span> <span m=''525710''>point,</span> <span m=''527420''>something</span>
  <span m=''527840''>like</span> <span m=''528070''>this.</span> <span m=''533300''>Then</span>
  <span m=''537310''>Kawasaki''s</span> <span m=''537600''>theorem</span> <span m=''537900''>changed</span>
  <span m=''538190''>a</span> <span m=''538230''>little</span> <span m=''538420''>bit.</span>
  <span m=''538700''>There</span> <span m=''538810''>were</span> <span m=''538900''>some</span>
  <span m=''539070''>other</span> <span m=''539510''>cases</span> <span m=''539910''>that</span>
  <span m=''540030''>could</span> <span m=''540140''>happen.</span> <span m=''541510''>So</span>
  <span m=''541730''>when</span> <span m=''541840''>you</span> <span m=''541900''>have</span>
  <span m=''542010''>tons</span> <span m=''542250''>of</span> <span m=''542310''>material,</span>
  <span m=''542810''>this</span> <span m=''542980''>can</span> <span m=''543110''>only</span>
  <span m=''543370''>happen</span> <span m=''543820''>in</span> <span m=''543980''>a</span>
  <span m=''544050''>non-convex</span> <span m=''544870''>polyhedron.</span> <span
  m=''546000''>That''s</span> <span m=''546210''>sort</span> <span m=''546380''>of</span>
  <span m=''546420''>the</span> <span m=''546510''>point.</span> <span m=''546810''>If</span>
  <span m=''546950''>you''re</span> <span m=''547100''>a</span> <span m=''547130''>convex</span>
  <span m=''547510''>polyhedron,</span> <span m=''547970''>you</span> <span m=''548395''>know
  you</span> <span m=''548820''>have</span> <span m=''548960''>to</span> <span m=''549030''>have</span>
  <span m=''549580''>only</span> <span m=''549790''>these</span> <span m=''549980''>two</span>
  <span m=''550100''>situations.</span> </p><p><span m=''551370''>Where</span> <span
  m=''551550''>do</span> <span m=''551620''>you</span> <span m=''551710''>get</span>
  <span m=''551920''>flat</span> <span m=''552210''>vertices?</span> <span m=''552760''>Well,</span>
  <span m=''553030''>if</span> <span m=''553190''>you</span> <span m=''553290''>think</span>
  <span m=''553520''>of</span> <span m=''553630''>this</span> <span m=''553910''>point</span>
  <span m=''554270''>as</span> <span m=''554450''>a</span> <span m=''554500''>vertex</span>
  <span m=''555490''>and</span> <span m=''555650''>you</span> <span m=''555770''>add</span>
  <span m=''556010''>up</span> <span m=''556150''>all</span> <span m=''556350''>the</span>
  <span m=''556470''>angles</span> <span m=''556780''>around</span> <span m=''557090''>it,</span>
  <span m=''557280''>well,</span> <span m=''557620''>that''s</span> <span m=''558040''>360.</span>
  <span m=''558880''>360</span> <span m=''559200''>minus</span> <span m=''559470''>360</span>
  <span m=''559920''>is</span> <span m=''560040''>0.</span> <span m=''561220''>So</span>
  <span m=''561500''>you</span> <span m=''561610''>have</span> <span m=''561920''>zero</span>
  <span m=''562250''>curvature</span> <span m=''562630''>on</span> <span m=''562710''>all</span>
  <span m=''562830''>the</span> <span m=''562910''>faces</span> <span m=''563460''>and</span>
  <span m=''563730''>on</span> <span m=''563880''>the</span> <span m=''564050''>edges.</span>
  <span m=''564600''>Also,</span> <span m=''564840''>if</span> <span m=''564940''>you</span>
  <span m=''565090''>look</span> <span m=''565640''>here,</span> <span m=''565900''>you</span>
  <span m=''565980''>have</span> <span m=''566140''>180</span> <span m=''567380''>and</span>
  <span m=''567650''>other</span> <span m=''567830''>180.</span> <span m=''568330''>That</span>
  <span m=''568550''>adds to</span> <span m=''568760''>360.</span> <span m=''570540''>And</span>
  <span m=''570690''>then</span> <span m=''570810''>at</span> <span m=''570910''>the</span>
  <span m=''571000''>actual</span> <span m=''571560''>vertices,</span> <span m=''572290''>that''s</span>
  <span m=''572530''>where</span> <span m=''572680''>you</span> <span m=''572830''>have</span>
  <span m=''573420''>positive</span> <span m=''573850''>curvature</span> <span m=''574420''>for</span>
  <span m=''575550''>a</span> <span m=''575830''>convex</span> <span m=''576340''>polyhedron.</span>
  <span m=''577820''>So</span> <span m=''577980''>just</span> <span m=''578170''>some</span>
  <span m=''578310''>terminology.</span> <span m=''579340''>Get</span> <span m=''579630''>used</span>
  <span m=''579850''>to</span> <span m=''579930''>the</span> <span m=''580070''>idea</span>
  <span m=''580280''>of</span> <span m=''580350''>positive</span> <span m=''580740''>curvature,</span>
  <span m=''581120''>zero</span> <span m=''581390''>curvature,</span> <span m=''581840''>and
  negative</span> <span m=''582220''>curvature.</span> </p><p><span m=''586230''>Then</span>
  <span m=''586890''>we</span> <span m=''587090''>have</span> <span m=''587300''>the</span>
  <span m=''587400''>idea</span> <span m=''587630''>of</span> <span m=''587690''>a</span>
  <span m=''587750''>cutting.</span> <span m=''590680''>So</span> <span m=''590870''>cutting</span>
  <span m=''591440''>is</span> <span m=''591590''>just,</span> <span m=''592240''>what</span>
  <span m=''592490''>edges</span> <span m=''592840''>do</span> <span m=''592920''>you</span>
  <span m=''593110''>cut?</span> <span m=''593400''>It''s</span> <span m=''593620''>the</span>
  <span m=''593820''>red</span> <span m=''594060''>stuff</span> <span m=''594520''>in</span>
  <span m=''594690''>this</span> <span m=''594920''>picture.</span> <span m=''595740''>What</span>
  <span m=''595920''>edges</span> <span m=''596060''>do</span> <span m=''596220''>you</span>
  <span m=''596420''>cut</span> <span m=''596710''>in</span> <span m=''596870''>order</span>
  <span m=''597040''>to</span> <span m=''597140''>unfold?</span> <span m=''597860''>So</span>
  <span m=''598050''>this</span> <span m=''598220''>is</span> <span m=''598330''>an</span>
  <span m=''598570''>unfolding,</span> <span m=''600140''>the</span> <span m=''600250''>mapping</span>
  <span m=''600690''>here,</span> <span m=''601480''>but</span> <span m=''601640''>the</span>
  <span m=''601770''>red</span> <span m=''602020''>part,</span> <span m=''602730''>I''ll</span>
  <span m=''602970''>call</span> <span m=''603170''>it</span> <span m=''603240''>cutting.</span>
  <span m=''604030''>Sometimes it''s</span> <span m=''604480''>also</span> <span m=''604730''>called</span>
  <span m=''604960''>an</span> <span m=''605030''>unfolding,</span> <span m=''605435''>but</span>
  <span m=''605840''>that</span> <span m=''605990''>can</span> <span m=''606160''>be</span>
  <span m=''606310''>a</span> <span m=''606350''>little</span> <span m=''606620''>confusing.</span>
  </p><p><span m=''617940''>The</span> <span m=''618180''>main</span> <span m=''618390''>point</span>
  <span m=''618610''>here</span> <span m=''618780''>is</span> <span m=''618880''>I</span>
  <span m=''618930''>want</span> <span m=''619140''>to</span> <span m=''619210''>talk</span>
  <span m=''619470''>about</span> <span m=''619820''>what</span> <span m=''620400''>constraints</span>
  <span m=''621130''>cutting</span> <span m=''621400''>must</span> <span m=''621590''>satisfy</span>
  <span m=''622220''>in</span> <span m=''622320''>order</span> <span m=''622490''>to</span>
  <span m=''622610''>be</span> <span m=''622730''>valid</span> <span m=''623580''>so</span>
  <span m=''623790''>we</span> <span m=''623880''>can</span> <span m=''623970''>just</span>
  <span m=''624150''>get</span> <span m=''624280''>a</span> <span m=''624340''>sense</span>
  <span m=''624760''>of</span> <span m=''625050''>what</span> <span m=''626180''>is</span>
  <span m=''626250''>happening</span> <span m=''626640''>here.</span> <span m=''627880''>If</span>
  <span m=''627940''>you</span> <span m=''628040''>look</span> <span m=''628180''>at</span>
  <span m=''628220''>these</span> <span m=''628400''>pictures,</span> <span m=''632240''>you</span>
  <span m=''632320''>can</span> <span m=''632460''>see</span> <span m=''632640''>two</span>
  <span m=''633150''>properties.</span> <span m=''634930''>One</span> <span m=''635110''>is</span>
  <span m=''635280''>that</span> <span m=''635970''>the</span> <span m=''636090''>cuttings</span>
  <span m=''636790''>visit</span> <span m=''637350''>all</span> <span m=''637610''>the</span>
  <span m=''637680''>vertices</span> <span m=''638320''>of</span> <span m=''638420''>the</span>
  <span m=''638520''>polyhedron.</span> <span m=''640890''>So</span> <span m=''641110''>there''s</span>
  <span m=''641330''>this</span> <span m=''641470''>red</span> <span m=''641720''>stuff.</span>
  <span m=''642610''>The</span> <span m=''642720''>red</span> <span m=''642970''>stuff</span>
  <span m=''643060''>is</span> <span m=''643350''>connected.</span> <span m=''645740''>It''s</span>
  <span m=''646050''>acyclic,</span> <span m=''647310''>so</span> <span m=''647460''>it''s</span>
  <span m=''647590''>actually</span> <span m=''647900''>a</span> <span m=''647950''>tree</span>
  <span m=''648490''>in</span> <span m=''648640''>these</span> <span m=''648800''>pictures,</span>
  <span m=''649350''>and</span> <span m=''649660''>it''s</span> <span m=''649940''>visiting</span>
  <span m=''650330''>all</span> <span m=''650480''>the</span> <span m=''650560''>corners.</span>
  <span m=''651880''>Even</span> <span m=''652190''>back</span> <span m=''652460''>here,</span>
  <span m=''652890''>it''s</span> <span m=''653030''>visited</span> <span m=''653340''>on</span>
  <span m=''653540''>the</span> <span m=''653620''>back.</span> </p><p><span m=''655330''>Is</span>
  <span m=''655400''>that</span> <span m=''655600''>always</span> <span m=''655870''>true?</span>
  <span m=''656550''>Most</span> <span m=''656890''>of</span> <span m=''656950''>those</span>
  <span m=''657110''>properties</span> <span m=''657620''>are</span> <span m=''657920''>mostly</span>
  <span m=''658350''>true,</span> <span m=''659660''>but</span> <span m=''659940''>it</span>
  <span m=''660090''>depends</span> <span m=''660500''>a</span> <span m=''660560''>little</span>
  <span m=''660780''>bit.</span> <span m=''662150''>One</span> <span m=''662420''>thing</span>
  <span m=''662610''>that</span> <span m=''662750''>is</span> <span m=''662920''>sure</span>
  <span m=''664450''>is</span> <span m=''664660''>the</span> <span m=''664780''>cutting</span>
  <span m=''665580''>must</span> <span m=''666090''>span</span> <span m=''668450''>all</span>
  <span m=''670220''>non-zero</span> <span m=''671090''>curvature</span> <span m=''671600''>vertices.</span>
  <span m=''675630''>But</span> <span m=''675790''>I</span> <span m=''675850''>do</span>
  <span m=''675990''>have</span> <span m=''676140''>to</span> <span m=''676250''>say</span>
  <span m=''676440''>"non-zero</span> <span m=''676960''>curvature."</span> <span
  m=''681450''>"Spans"</span> <span m=''682060''>just</span> <span m=''682270''>means</span>
  <span m=''682560''>visits.</span> <span m=''684060''>You</span> <span m=''684210''>have</span>
  <span m=''684480''>to</span> <span m=''684570''>hit</span> <span m=''684820''>all</span>
  <span m=''685080''>the</span> <span m=''685170''>vertices</span> <span m=''685730''>of</span>
  <span m=''685820''>non-zero</span> <span m=''686260''>curvature</span> <span m=''687330''>because</span>
  <span m=''688230''>anything</span> <span m=''688690''>of</span> <span m=''688740''>non-zero</span>
  <span m=''689130''>curvature</span> <span m=''689550''>can''t</span> <span m=''689840''>be</span>
  <span m=''689980''>flattened</span> <span m=''690660''>by</span> <span m=''690810''>itself.</span>
  <span m=''691360''>It</span> <span m=''691390''>needs</span> <span m=''691660''>to</span>
  <span m=''691750''>be</span> <span m=''691950''>cut.</span> <span m=''695590''>At</span>
  <span m=''695750''>that</span> <span m=''695990''>point,</span> <span m=''696420''>the</span>
  <span m=''696960''>cutting</span> <span m=''697370''>has</span> <span m=''697560''>to</span>
  <span m=''697640''>have</span> <span m=''697750''>degree</span> <span m=''697980''>at</span>
  <span m=''698040''>least</span> <span m=''698280''>one.</span> </p><p><span m=''701790''>With</span>
  <span m=''702010''>zero</span> <span m=''702340''>curvature</span> <span m=''702750''>vertices,</span>
  <span m=''703210''>even</span> <span m=''703520''>if</span> <span m=''703650''>they''re</span>
  <span m=''703790''>not</span> <span m=''704090''>flat</span> <span m=''704390''>in</span>
  <span m=''704530''>three</span> <span m=''704740''>dimensions,</span> <span m=''705900''>you</span>
  <span m=''706060''>could</span> <span m=''706320''>flatten</span> <span m=''706710''>them</span>
  <span m=''707510''>because</span> <span m=''707730''>we know</span> <span m=''707840''>locally,</span>
  <span m=''708670''>it</span> <span m=''708730''>really</span> <span m=''708950''>is</span>
  <span m=''709060''>a</span> <span m=''709120''>flat</span> <span m=''709420''>thing.</span>
  <span m=''709620''>So</span> <span m=''709780''>there</span> <span m=''709910''>may</span>
  <span m=''710050''>not</span> <span m=''710220''>be</span> <span m=''710360''>any</span>
  <span m=''710590''>cuts</span> <span m=''710900''>at</span> <span m=''710980''>zero</span>
  <span m=''711770''>curvature</span> <span m=''712100''>vertices.</span> <span m=''712460''>Most</span>
  <span m=''712660''>of the</span> <span m=''712760''>time,</span> <span m=''712970''>we</span>
  <span m=''713070''>won''t</span> <span m=''713230''>have</span> <span m=''713350''>to</span>
  <span m=''713450''>worry</span> <span m=''713610''>about</span> <span m=''713850''>them,</span>
  <span m=''714150''>but</span> <span m=''714840''>something</span> <span m=''715210''>to</span>
  <span m=''715290''>think</span> <span m=''715490''>about.</span> <span m=''716700''>Everybody</span>
  <span m=''717160''>else</span> <span m=''717560''>you</span> <span m=''717660''>have</span>
  <span m=''717920''>to</span> <span m=''718030''>span.</span> </p><p><span m=''723970''>You</span>
  <span m=''724110''>can</span> <span m=''724230''>say</span> <span m=''724380''>even</span>
  <span m=''724570''>more.</span> <span m=''726020''>If</span> <span m=''726260''>you</span>
  <span m=''726380''>have</span> <span m=''726800''>very</span> <span m=''727300''>negative</span>
  <span m=''727750''>curvature,</span> <span m=''729680''>if</span> <span m=''729850''>the</span>
  <span m=''729940''>curvature</span> <span m=''730205''>of a</span> <span m=''730470''>vertex</span>
  <span m=''730890''>is</span> <span m=''731030''>less</span> <span m=''731270''>than</span>
  <span m=''731450''>some</span> <span m=''731850''>integer,</span> <span m=''732260''>k</span>
  <span m=''732670''>times</span> <span m=''733010''>360</span> <span m=''734476''>with
  a</span> <span m=''734850''>minus</span> <span m=''735120''>sign</span> <span m=''735310''>in</span>
  <span m=''735390''>front,</span> <span m=''736750''>then</span> <span m=''739080''>cutting</span>
  <span m=''744020''>must</span> <span m=''744490''>have</span> <span m=''746790''>degree</span>
  <span m=''748580''>strictly</span> <span m=''749050''>more</span> <span m=''749300''>than</span>
  <span m=''749480''>k</span> <span m=''749670''>plus</span> <span m=''749980''>1.</span>
  <span m=''752760''>So</span> <span m=''753510''>if</span> <span m=''753670''>you</span>
  <span m=''753780''>have</span> <span m=''753960''>negative</span> <span m=''754300''>curvature,</span>
  <span m=''754680''>you</span> <span m=''755060''>know</span> <span m=''755370''>you</span>
  <span m=''755770''>have</span> <span m=''755920''>to</span> <span m=''756010''>have</span>
  <span m=''758340''>at</span> <span m=''758390''>least</span> <span m=''758820''>two</span>
  <span m=''759000''>cuts</span> <span m=''759470''>for a</span> <span m=''759660''>negative</span>
  <span m=''759980''>curvature</span> <span m=''760330''>vertex</span> <span m=''760820''>because</span>
  <span m=''760990''>if</span> <span m=''761100''>you</span> <span m=''761180''>had</span>
  <span m=''761490''>negative</span> <span m=''761810''>curvature--</span> <span m=''762860''>one</span>
  <span m=''763020''>of</span> <span m=''763070''>these</span> <span m=''763290''>things--</span>
  <span m=''764270''>you</span> <span m=''764400''>made</span> <span m=''764570''>a</span>
  <span m=''764620''>single</span> <span m=''765050''>cut.</span> <span m=''765380''>Then</span>
  <span m=''765710''>all</span> <span m=''765880''>that</span> <span m=''766030''>material
  is</span> <span m=''766440''>still</span> <span m=''766700''>there.</span> <span
  m=''767070''>If</span> <span m=''767170''>you</span> <span m=''767180''>then</span>
  <span m=''767380''>flattened</span> <span m=''767840''>it,</span> <span m=''768280''>it''s</span>
  <span m=''768490''>going</span> <span m=''768630''>to</span> <span m=''768740''>overlap</span>
  <span m=''769170''>itself</span> <span m=''769490''>because</span> <span m=''769660''>you''re</span>
  <span m=''769790''>trying</span> <span m=''769970''>to</span> <span m=''770030''>flatten
  it</span> <span m=''770290''>into</span> <span m=''770560''>360.</span> <span m=''771120''>There''s</span>
  <span m=''771280''>more</span> <span m=''771450''>than</span> <span m=''771590''>360</span>
  <span m=''772090''>material</span> <span m=''772560''>there.</span> </p><p><span
  m=''774080''>So</span> <span m=''774510''>negative</span> <span m=''774840''>curvature</span>
  <span m=''775220''>already,</span> <span m=''775520''>you</span> <span m=''775610''>need</span>
  <span m=''775800''>two</span> <span m=''776640''>vertices.</span> <span m=''777590''>That''s</span>
  <span m=''777950''>the</span> <span m=''778220''>plus</span> <span m=''778950''>1</span>
  <span m=''779170''>here.</span> <span m=''780130''>And</span> <span m=''780440''>as</span>
  <span m=''780550''>soon</span> <span m=''780760''>as</span> <span m=''780870''>you</span>
  <span m=''781020''>get</span> <span m=''781950''>to</span> <span m=''784890''>smaller</span>
  <span m=''785260''>than</span> <span m=''785390''>negative</span> <span m=''785680''>360,</span>
  <span m=''786610''>then</span> <span m=''786760''>you</span> <span m=''786820''>have</span>
  <span m=''786950''>to</span> <span m=''787020''>have at</span> <span m=''787190''>least</span>
  <span m=''787380''>three</span> <span m=''787570''>cuts</span> <span m=''787990''>and</span>
  <span m=''788110''>so</span> <span m=''788250''>on,</span> <span m=''789100''>just</span>
  <span m=''789360''>to</span> <span m=''789740''>partition</span> <span m=''790250''>up</span>
  <span m=''790510''>into</span> <span m=''790820''>at</span> <span m=''790910''>most</span>
  <span m=''791160''>360</span> <span m=''791660''>groups.</span> <span m=''794700''>This</span>
  <span m=''795020''>is</span> <span m=''795340''>useful.</span> <span m=''796040''>Negative</span>
  <span m=''796380''>curvature is</span> <span m=''796840''>basically</span> <span
  m=''797180''>really</span> <span m=''797410''>tough</span> <span m=''797650''>to</span>
  <span m=''797730''>unfold</span> <span m=''798170''>and</span> <span m=''798230''>we''ll</span>
  <span m=''798380''>use</span> <span m=''798610''>that</span> <span m=''798830''>to</span>
  <span m=''798930''>make</span> <span m=''799080''>counter</span> <span m=''799370''>examples</span>
  <span m=''799870''>here.</span> <span m=''802320''>What</span> <span m=''802410''>else?</span>
  </p><p><span m=''815940''>your</span> <span m=''816060''>polyhedron</span> <span
  m=''817930''>has</span> <span m=''818450''>no</span> <span m=''818890''>handles,</span>
  <span m=''822350''>then</span> <span m=''826080''>cutting</span> <span m=''827310''>has</span>
  <span m=''827610''>no</span> <span m=''827750''>cycles.</span> <span m=''836620''>A</span>
  <span m=''836680''>handle</span> <span m=''837140''>is</span> <span m=''838500''>something</span>
  <span m=''839060''>of</span> <span m=''839560''>higher</span> <span m=''839890''>genus.</span>
  <span m=''840400''>If</span> <span m=''840510''>this</span> <span m=''840670''>is</span>
  <span m=''840760''>your</span> <span m=''840920''>polyhedron,</span> <span m=''842430''>we</span>
  <span m=''842520''>call</span> <span m=''842760''>this</span> <span m=''843000''>a</span>
  <span m=''843040''>handle.</span> <span m=''844210''>You</span> <span m=''844230''>have</span>
  <span m=''844540''>sort of a</span> <span m=''844810''>blob</span> <span m=''845110''>down</span>
  <span m=''845320''>here</span> <span m=''845490''>and you have</span> <span m=''845630''>a</span>
  <span m=''845720''>connection</span> <span m=''846330''>from</span> <span m=''846810''>one</span>
  <span m=''846960''>place</span> <span m=''847210''>to</span> <span m=''847330''>the</span>
  <span m=''847500''>other.</span> <span m=''848730''>If</span> <span m=''848890''>you</span>
  <span m=''849000''>have</span> <span m=''849140''>a</span> <span m=''849190''>handle,</span>
  <span m=''850170''>you</span> <span m=''850280''>can</span> <span m=''850400''>have</span>
  <span m=''850600''>a</span> <span m=''850670''>cycle</span> <span m=''851000''>of</span>
  <span m=''851120''>cuts</span> <span m=''851570''>like</span> <span m=''851910''>this</span>
  <span m=''852800''>that</span> <span m=''852950''>does</span> <span m=''853090''>not</span>
  <span m=''853320''>disconnect</span> <span m=''853780''>the</span> <span m=''853870''>surface,</span>
  <span m=''855320''>but</span> <span m=''855500''>we</span> <span m=''855630''>basically</span>
  <span m=''856070''>never</span> <span m=''856350''>think</span> <span m=''856550''>about</span>
  <span m=''856810''>that</span> <span m=''857610''>situation.</span> </p><p><span
  m=''858720''>Whenever</span> <span m=''859030''>we''re</span> <span m=''859110''>thinking</span>
  <span m=''859370''>of</span> <span m=''859430''>something</span> <span m=''859720''>of
  genus</span> <span m=''860000''>zero,</span> <span m=''860480''>like</span> <span
  m=''860550''>a</span> <span m=''860870''>convex</span> <span m=''861150''>polyhedron</span>
  <span m=''861560''>or</span> <span m=''861940''>a</span> <span m=''862300''>regular,</span>
  <span m=''862780''>non-convex</span> <span m=''863360''>polyhedron,</span> <span
  m=''866150''>you</span> <span m=''866320''>really</span> <span m=''866500''>shouldn''t</span>
  <span m=''866760''>have</span> <span m=''866920''>a</span> <span m=''866980''>cycle</span>
  <span m=''867330''>in</span> <span m=''867400''>your</span> <span m=''867500''>cutting</span>
  <span m=''867780''>because</span> <span m=''867960''>if</span> <span m=''868070''>you</span>
  <span m=''868170''>had</span> <span m=''868360''>a</span> <span m=''868410''>cycle,</span>
  <span m=''869120''>you''d</span> <span m=''869250''>disconnect</span> <span m=''869810''>your</span>
  <span m=''869940''>surface</span> <span m=''870290''>into</span> <span m=''870480''>two</span>
  <span m=''870620''>parts</span> <span m=''871920''>normally,</span> <span m=''872810''>if</span>
  <span m=''872970''>you''re</span> <span m=''873120''>like</span> <span m=''873320''>a</span>
  <span m=''873380''>sphere</span> <span m=''873850''>or</span> <span m=''873870''>like</span>
  <span m=''874070''>a</span> <span m=''874130''>disk.</span> <span m=''877230''>That''s</span>
  <span m=''877450''>the</span> <span m=''877570''>acyclic</span> <span m=''878040''>condition</span>
  <span m=''879370''>and</span> <span m=''879610''>when</span> <span m=''879750''>it</span>
  <span m=''879790''>holds.</span> <span m=''880910''>Some</span> <span m=''881390''>other</span>
  <span m=''881600''>good</span> <span m=''881800''>things.</span> </p><p><span m=''897230''>If</span>
  <span m=''897490''>a</span> <span m=''897560''>polyhedron</span> <span m=''898130''>has</span>
  <span m=''898440''>no</span> <span m=''900180''>boundary</span> <span m=''902670''>and</span>
  <span m=''902920''>no</span> <span m=''903120''>handles,</span> <span m=''908560''>and</span>
  <span m=''911820''>the</span> <span m=''911990''>unfolding</span> <span m=''913560''>has</span>
  <span m=''913990''>no</span> <span m=''914260''>holes,</span> <span m=''919120''>then</span>
  <span m=''924660''>cutting</span> <span m=''925280''>is</span> <span m=''925820''>a</span>
  <span m=''927900''>spanning</span> <span m=''928390''>tree.</span> <span m=''931230''>Spanning</span>
  <span m=''931660''>tree,</span> <span m=''932340''>it''s</span> <span m=''933040''>a</span>
  <span m=''933150''>concept</span> <span m=''933560''>we''ve</span> <span m=''933680''>used</span>
  <span m=''933900''>a</span> <span m=''933940''>few</span> <span m=''934100''>times.</span>
  <span m=''934530''>It''s</span> <span m=''934630''>just</span> <span m=''934830''>a</span>
  <span m=''934900''>tree.</span> <span m=''935380''>In</span> <span m=''935470''>this</span>
  <span m=''935650''>case,</span> <span m=''936360''>it''s</span> <span m=''936460''>got</span>
  <span m=''936570''>to</span> <span m=''936620''>visit</span> <span m=''936910''>all</span>
  <span m=''937090''>the</span> <span m=''937140''>vertices</span> <span m=''937600''>of</span>
  <span m=''937660''>non-zero</span> <span m=''938120''>curvature</span> <span m=''939440''>and</span>
  <span m=''939600''>it''s</span> <span m=''939720''>a</span> <span m=''939770''>tree,</span>
  <span m=''940140''>so</span> <span m=''940270''>it''s</span> <span m=''940400''>connected</span>
  <span m=''941130''>and</span> <span m=''941360''>it''s</span> <span m=''941480''>acyclic.</span>
  <span m=''943450''>The</span> <span m=''943610''>main</span> <span m=''943850''>new</span>
  <span m=''944000''>thing</span> <span m=''944200''>here</span> <span m=''944400''>is</span>
  <span m=''944490''>that</span> <span m=''944610''>it''s</span> <span m=''944830''>connected.</span>
  <span m=''945410''>We''ve</span> <span m=''945590''>already</span> <span m=''945780''>said</span>
  <span m=''946000''>that it</span> <span m=''946110''>should</span> <span m=''946270''>be</span>
  <span m=''946430''>acyclic</span> <span m=''947030''>with</span> <span m=''947230''>no</span>
  <span m=''947340''>handles,</span> <span m=''947920''>we''ve</span> <span m=''948230''>already</span>
  <span m=''948370''>said</span> <span m=''948580''>that it</span> <span m=''948690''>should</span>
  <span m=''948840''>span</span> <span m=''949140''>everybody,</span> <span m=''951030''>so</span>
  <span m=''951570''>it''s</span> <span m=''951830''>sort</span> <span m=''952120''>of</span>
  <span m=''952210''>a</span> <span m=''952270''>summary</span> <span m=''953010''>theorem,</span>
  <span m=''953330''>but</span> <span m=''953450''>we</span> <span m=''953560''>have</span>
  <span m=''953790''>a</span> <span m=''953840''>whole</span> <span m=''954080''>bunch</span>
  <span m=''954330''>of</span> <span m=''954420''>conditions</span> <span m=''954970''>here.</span>
  </p><p><span m=''955520''>In</span> <span m=''955670''>particular,</span> <span
  m=''956850''>this</span> <span m=''957050''>will</span> <span m=''957210''>hold</span>
  <span m=''960530''>if</span> <span m=''960990''>your</span> <span m=''961170''>polyhedron</span>
  <span m=''961680''>is</span> <span m=''961790''>convex.</span> <span m=''966770''>So</span>
  <span m=''966990''>for</span> <span m=''967140''>convex</span> <span m=''967560''>polyhedra,</span>
  <span m=''969520''>you have</span> <span m=''969710''>a</span> <span m=''969770''>spanning</span>
  <span m=''970150''>tree,</span> <span m=''970450''>and</span> <span m=''970590''>that''s</span>
  <span m=''970790''>what''s</span> <span m=''970960''>going</span> <span m=''971240''>on</span>
  <span m=''971410''>in</span> <span m=''971490''>this</span> <span m=''971660''>picture</span>
  <span m=''972550''>even</span> <span m=''972820''>for</span> <span m=''972950''>general</span>
  <span m=''973280''>unfoldings.</span> <span m=''973740''>That''s the</span> <span
  m=''974130''>interesting</span> <span m=''974530''>case.</span> <span m=''974940''>Here,</span>
  <span m=''975190''>it''s</span> <span m=''975310''>maybe</span> <span m=''975600''>more</span>
  <span m=''975800''>obvious,</span> <span m=''976250''>here</span> <span m=''976480''>it''s</span>
  <span m=''976690''>a</span> <span m=''977490''>little</span> <span m=''977650''>less</span>
  <span m=''977860''>obvious.</span> </p><p><span m=''980160''>And</span> <span m=''980380''>to</span>
  <span m=''980480''>sort</span> <span m=''980720''>of</span> <span m=''980800''>see</span>
  <span m=''981640''>what</span> <span m=''981870''>could</span> <span m=''982000''>go</span>
  <span m=''982110''>wrong</span> <span m=''982440''>here,</span> <span m=''982740''>I</span>
  <span m=''982800''>have</span> <span m=''983020''>an</span> <span m=''983100''>example.</span>
  <span m=''985550''>This</span> <span m=''985630''>is</span> <span m=''985770''>a</span>
  <span m=''985930''>non-convex</span> <span m=''986570''>polyhedron.</span> <span
  m=''987210''>There''s</span> <span m=''987480''>a</span> <span m=''987550''>whole</span>
  <span m=''987770''>bunch</span> <span m=''988010''>of</span> <span m=''988120''>views</span>
  <span m=''988590''>of</span> <span m=''988810''>it</span> <span m=''989270''>up</span>
  <span m=''989440''>here,</span> <span m=''990770''>and</span> <span m=''990990''>in</span>
  <span m=''991080''>particular</span> <span m=''992090''>this</span> <span m=''992260''>top</span>
  <span m=''992560''>view.</span> <span m=''993330''>What</span> <span m=''993520''>we''re</span>
  <span m=''993640''>doing</span> <span m=''994010''>is</span> <span m=''994470''>slicing</span>
  <span m=''995450''>along</span> <span m=''995860''>just</span> <span m=''996220''>those</span>
  <span m=''996480''>two</span> <span m=''996710''>edges</span> <span m=''997210''>and</span>
  <span m=''997380''>some</span> <span m=''997580''>other</span> <span m=''997760''>stuff</span>
  <span m=''998040''>around</span> <span m=''998230''>the</span> <span m=''998340''>outside,</span>
  <span m=''999220''>but</span> <span m=''999320''>in</span> <span m=''999410''>particular,</span>
  <span m=''999800''>we</span> <span m=''999900''>cut</span> <span m=''1000120''>those</span>
  <span m=''1000330''>two</span> <span m=''1000490''>edges</span> <span m=''1000890''>and</span>
  <span m=''1001040''>there</span> <span m=''1001170''>aren''t</span> <span m=''1001670''>any</span>
  <span m=''1002040''>other</span> <span m=''1002270''>cuts</span> <span m=''1003590''>around</span>
  <span m=''1004080''>there.</span> <span m=''1006060''>A</span> <span m=''1006090''>polyhedron</span>
  <span m=''1006385''>is</span> <span m=''1006680''>set</span> <span m=''1006900''>up</span>
  <span m=''1007010''>so that</span> <span m=''1007210''>when</span> <span m=''1007330''>you</span>
  <span m=''1007450''>open</span> <span m=''1007700''>it</span> <span m=''1007790''>up,</span>
  <span m=''1008610''>this</span> <span m=''1009490''>works</span> <span m=''1009820''>out.</span>
  <span m=''1010100''>It''s</span> <span m=''1010270''>nice</span> <span m=''1010490''>and</span>
  <span m=''1010600''>flat.</span> <span m=''1011170''>This</span> <span m=''1011330''>is</span>
  <span m=''1011440''>extremely</span> <span m=''1011960''>rare.</span> <span m=''1012280''>If</span>
  <span m=''1012360''>you</span> <span m=''1012450''>perturbed</span> <span m=''1012800''>this</span>
  <span m=''1012940''>example,</span> <span m=''1013470''>it</span> <span m=''1013520''>wouldn''t</span>
  <span m=''1013750''>hold.</span> </p><p><span m=''1014750''>But</span> <span m=''1014900''>you</span>
  <span m=''1015020''>can</span> <span m=''1015150''>set</span> <span m=''1015370''>things</span>
  <span m=''1015610''>up</span> <span m=''1016020''>so</span> <span m=''1016330''>that,</span>
  <span m=''1016790''>in</span> <span m=''1016890''>fact,</span> <span m=''1017230''>what''s</span>
  <span m=''1017280''>happening</span> <span m=''1017680''>is</span> <span m=''1017800''>that</span>
  <span m=''1017900''>the</span> <span m=''1018030''>total</span> <span m=''1018430''>curvature--</span>
  <span m=''1019330''>this</span> <span m=''1019810''>vertex</span> <span m=''1020180''>has</span>
  <span m=''1020320''>positive</span> <span m=''1020700''>curvature,</span> <span
  m=''1021050''>this</span> <span m=''1021280''>has</span> <span m=''1021420''>negative,</span>
  <span m=''1022280''>this</span> <span m=''1022470''>has</span> <span m=''1022610''>positive,</span>
  <span m=''1023150''>and</span> <span m=''1023180''>the</span> <span m=''1023270''>sum</span>
  <span m=''1023600''>of</span> <span m=''1023710''>those</span> <span m=''1023890''>three</span>
  <span m=''1024069''>curvatures</span> <span m=''1024940''>is</span> <span m=''1025140''>zero,</span>
  <span m=''1026300''>and</span> <span m=''1026530''>that''s</span> <span m=''1026750''>what</span>
  <span m=''1026869''>allows</span> <span m=''1027260''>this</span> <span m=''1027440''>to</span>
  <span m=''1027560''>be</span> <span m=''1027730''>flat</span> <span m=''1028680''>because</span>
  <span m=''1028790''>the</span> <span m=''1028859''>total</span> <span m=''1029200''>curvature</span>
  <span m=''1029640''>in</span> <span m=''1029720''>that</span> <span m=''1029890''>little</span>
  <span m=''1030089''>region</span> <span m=''1030510''>is</span> <span m=''1030670''>zero,</span>
  <span m=''1031550''>and</span> <span m=''1031630''>that''s</span> <span m=''1031819''>when</span>
  <span m=''1031950''>things</span> <span m=''1032200''>are</span> <span m=''1032270''>allowed</span>
  <span m=''1032510''>to</span> <span m=''1032569''>be</span> <span m=''1032690''>flat.</span>
  <span m=''1033750''>So</span> <span m=''1033930''>you</span> <span m=''1034109''>can</span>
  <span m=''1034290''>cut</span> <span m=''1034569''>here</span> <span m=''1035369''>and</span>
  <span m=''1035540''>make</span> <span m=''1035740''>a</span> <span m=''1035819''>separate</span>
  <span m=''1036310''>collection</span> <span m=''1036720''>of cuts</span> <span m=''1036990''>on</span>
  <span m=''1037069''>the</span> <span m=''1037200''>outside,</span> <span m=''1037609''>but
  it''s</span> <span m=''1037859''>disconnected,</span> <span m=''1038880''>so</span>
  <span m=''1039069''>this</span> <span m=''1039220''>is</span> <span m=''1039329''>kind</span>
  <span m=''1039530''>of</span> <span m=''1039599''>weird.</span> <span m=''1040780''>Most</span>
  <span m=''1041079''>of the</span> <span m=''1041190''>time,</span> <span m=''1041589''>things</span>
  <span m=''1041900''>will</span> <span m=''1042020''>be</span> <span m=''1042160''>connected,</span>
  <span m=''1045020''>and</span> <span m=''1045319''>as</span> <span m=''1045440''>long</span>
  <span m=''1045740''>as</span> <span m=''1046930''>your</span> <span m=''1047119''>unfolding</span>
  <span m=''1047530''>has</span> <span m=''1047730''>no</span> <span m=''1047880''>holes--</span>
  <span m=''1048750''>and</span> <span m=''1048970''>for</span> <span m=''1049100''>an</span>
  <span m=''1049160''>unfolding</span> <span m=''1049570''>to</span> <span m=''1049630''>have</span>
  <span m=''1049820''>holes,</span> <span m=''1050060''>you''d</span> <span m=''1050150''>have</span>
  <span m=''1050340''>to</span> <span m=''1050410''>have</span> <span m=''1050530''>this</span>
  <span m=''1050670''>weird</span> <span m=''1050910''>property</span> <span m=''1051290''>that</span>
  <span m=''1051450''>a</span> <span m=''1051500''>bunch</span> <span m=''1051740''>of</span>
  <span m=''1051820''>curvatures</span> <span m=''1052230''>sum</span> <span m=''1052420''>to</span>
  <span m=''1052520''>zero</span> <span m=''1053020''>like</span> <span m=''1053480''>in</span>
  <span m=''1053660''>that</span> <span m=''1053820''>picture--</span> <span m=''1054270''>as</span>
  <span m=''1054710''>long as</span> <span m=''1054820''>you</span> <span m=''1054910''>don''t</span>
  <span m=''1055040''>have</span> <span m=''1055220''>that,</span> <span m=''1056410''>you''re</span>
  <span m=''1056710''>OK.</span> </p><p><span m=''1062460''>Let''s</span> <span m=''1062680''>get</span>
  <span m=''1062890''>to</span> <span m=''1063010''>these</span> <span m=''1063270''>theorems.</span>
  <span m=''1066820''>Actually,</span> <span m=''1067080''>one</span> <span m=''1067370''>thing</span>
  <span m=''1067650''>related</span> <span m=''1068320''>to</span> <span m=''1069630''>this</span>
  <span m=''1069940''>problem,</span> <span m=''1072310''>general</span> <span m=''1072650''>unfolding</span>
  <span m=''1073370''>of</span> <span m=''1073760''>arbitrary</span> <span m=''1074330''>polyhedra,</span>
  <span m=''1075420''>is</span> <span m=''1075560''>you</span> <span m=''1075680''>can''t</span>
  <span m=''1075920''>be</span> <span m=''1076080''>too</span> <span m=''1076390''>general</span>
  <span m=''1077870''>what</span> <span m=''1078040''>you</span> <span m=''1078120''>mean</span>
  <span m=''1078290''>by</span> <span m=''1078390''>non-convex</span> <span m=''1078940''>polyhedra.</span>
  <span m=''1079500''>So</span> <span m=''1079710''>we</span> <span m=''1079800''>have</span>
  <span m=''1079980''>this</span> <span m=''1080170''>example.</span> <span m=''1081670''>It''s</span>
  <span m=''1082120''>the</span> <span m=''1082230''>simplest</span> <span m=''1083450''>nasty</span>
  <span m=''1083880''>polyhedron</span> <span m=''1084460''>there</span> <span m=''1084620''>is</span>
  <span m=''1084860''>this.</span> <span m=''1085330''>It</span> <span m=''1085790''>has</span>
  <span m=''1086010''>one</span> <span m=''1086510''>vertex</span> <span m=''1087020''>at</span>
  <span m=''1087140''>the</span> <span m=''1087270''>top</span> <span m=''1087570''>there</span>
  <span m=''1087770''>with</span> <span m=''1087940''>a</span> <span m=''1087990''>big</span>
  <span m=''1088290''>dot</span> <span m=''1088705''>that</span> <span m=''1089120''>has</span>
  <span m=''1089350''>negative</span> <span m=''1089760''>curvature.</span> <span
  m=''1090660''>There''s</span> <span m=''1090840''>more</span> <span m=''1091200''>than</span>
  <span m=''1091350''>360</span> <span m=''1091950''>degrees</span> <span m=''1092310''>of</span>
  <span m=''1092390''>material</span> <span m=''1092990''>from</span> <span m=''1093190''>all</span>
  <span m=''1093320''>these</span> <span m=''1093470''>triangles.</span> <span m=''1095200''>And</span>
  <span m=''1095360''>that''s</span> <span m=''1095480''>sort</span> <span m=''1095660''>of</span>
  <span m=''1095830''>all</span> <span m=''1096100''>that it</span> <span m=''1096230''>has.</span>
  <span m=''1096640''>This</span> <span m=''1096830''>is</span> <span m=''1096990''>the</span>
  <span m=''1097080''>polyhedron.</span> <span m=''1097930''>This</span> <span m=''1098450''>is</span>
  <span m=''1098510''>what</span> <span m=''1098650''>we</span> <span m=''1098760''>call</span>
  <span m=''1099030''>boundary</span> <span m=''1099870''>of</span> <span m=''1100140''>the</span>
  <span m=''1100310''>polyhedron.</span> <span m=''1100860''>So</span> <span m=''1101010''>far,</span>
  <span m=''1101160''>all</span> <span m=''1101280''>the</span> <span m=''1101350''>polyhedra</span>
  <span m=''1101605''>I''ve</span> <span m=''1101860''>done</span> <span m=''1102050''>haven''t</span>
  <span m=''1102290''>had</span> <span m=''1102520''>that,</span> <span m=''1103360''>and</span>
  <span m=''1103710''>you</span> <span m=''1104030''>may</span> <span m=''1104250''>have</span>
  <span m=''1104340''>seen</span> <span m=''1104550''>that</span> <span m=''1104700''>I</span>
  <span m=''1105160''>assumed</span> <span m=''1105430''>that</span> <span m=''1105560''>it</span>
  <span m=''1105620''>wasn''t</span> <span m=''1105910''>there</span> <span m=''1107070''>for</span>
  <span m=''1107260''>that</span> <span m=''1107450''>last</span> <span m=''1107890''>lemma.</span>
  </p><p><span m=''1109608''>This</span> <span m=''1111010''>polyhedron</span> <span
  m=''1111510''>can''t</span> <span m=''1111750''>be</span> <span m=''1111860''>unfolded</span>
  <span m=''1113040''>at</span> <span m=''1113220''>all</span> <span m=''1114660''>in</span>
  <span m=''1114840''>one</span> <span m=''1115020''>piece,</span> <span m=''1115970''>no</span>
  <span m=''1116500''>overlap.</span> <span m=''1117740''>Why?</span> <span m=''1118940''>Because</span>
  <span m=''1119440''>it</span> <span m=''1119510''>has</span> <span m=''1119670''>one</span>
  <span m=''1119980''>vertex.</span> <span m=''1120590''>You</span> <span m=''1120720''>could</span>
  <span m=''1120850''>think</span> <span m=''1121000''>of</span> <span m=''1121070''>these</span>
  <span m=''1121260''>as</span> <span m=''1121380''>vertices,</span> <span m=''1121850''>but</span>
  <span m=''1122010''>they''re</span> <span m=''1122150''>kind</span> <span m=''1122360''>of</span>
  <span m=''1122470''>flat.</span> <span m=''1122990''>Everything''s</span> <span
  m=''1123450''>flat</span> <span m=''1123720''>except</span> <span m=''1124020''>that</span>
  <span m=''1124170''>one</span> <span m=''1124340''>point.</span> <span m=''1124650''>It</span>
  <span m=''1125050''>has</span> <span m=''1125350''>negative</span> <span m=''1125680''>curvature.</span>
  <span m=''1127000''>Negative</span> <span m=''1127330''>curvature,</span> <span
  m=''1127720''>we</span> <span m=''1127820''>said</span> <span m=''1128600''>you</span>
  <span m=''1128730''>have</span> <span m=''1128900''>to</span> <span m=''1128980''>have</span>
  <span m=''1129090''>at</span> <span m=''1129170''>least</span> <span m=''1129630''>two</span>
  <span m=''1129880''>cuts</span> <span m=''1130340''>coming</span> <span m=''1130620''>in</span>
  <span m=''1130720''>there.</span> <span m=''1130900''>If</span> <span m=''1130980''>you</span>
  <span m=''1131070''>just</span> <span m=''1131280''>made</span> <span m=''1131450''>one</span>
  <span m=''1131740''>cut,</span> <span m=''1132740''>then</span> <span m=''1133160''>when</span>
  <span m=''1133360''>you</span> <span m=''1133510''>flatten</span> <span m=''1133990''>this</span>
  <span m=''1134190''>thing,</span> <span m=''1134380''>it''ll</span> <span m=''1134450''>overlap</span>
  <span m=''1134950''>itself</span> <span m=''1135260''>locally.</span> </p><p><span
  m=''1136450''>So</span> <span m=''1136630''>there''s</span> <span m=''1136730''>got</span>
  <span m=''1136850''>to</span> <span m=''1136900''>be</span> <span m=''1136990''>at</span>
  <span m=''1137060''>least</span> <span m=''1137400''>two</span> <span m=''1137550''>cuts</span>
  <span m=''1137870''>coming</span> <span m=''1138150''>in</span> <span m=''1138250''>there.</span>
  <span m=''1139940''>I</span> <span m=''1140050''>don''t</span> <span m=''1140190''>think</span>
  <span m=''1140560''>that</span> <span m=''1140740''>even</span> <span m=''1140950''>matters</span>
  <span m=''1141310''>much.</span> <span m=''1142910''>I</span> <span m=''1142940''>mean,</span>
  <span m=''1143130''>there''s</span> <span m=''1143360''>at</span> <span m=''1143420''>least</span>
  <span m=''1143640''>one,</span> <span m=''1144070''>certainly.</span> <span m=''1144850''>Where</span>
  <span m=''1145030''>could</span> <span m=''1145180''>those</span> <span m=''1145400''>guys</span>
  <span m=''1145650''>go,</span> <span m=''1146420''>those</span> <span m=''1146580''>cuts?</span>
  <span m=''1146890''>They</span> <span m=''1146980''>have</span> <span m=''1147180''>to</span>
  <span m=''1147400''>wander</span> <span m=''1147890''>around</span> <span m=''1148100''>the</span>
  <span m=''1148170''>surface.</span> <span m=''1148810''>If</span> <span m=''1148850''>they</span>
  <span m=''1148960''>just</span> <span m=''1149140''>stop</span> <span m=''1149650''>in</span>
  <span m=''1149810''>the</span> <span m=''1149890''>middle</span> <span m=''1150130''>of</span>
  <span m=''1150230''>nowhere,</span> <span m=''1151220''>then</span> <span m=''1151350''>you''re</span>
  <span m=''1151450''>sort</span> <span m=''1151620''>of</span> <span m=''1151710''>doing</span>
  <span m=''1151940''>nothing</span> <span m=''1152420''>because</span> <span m=''1154100''>a</span>
  <span m=''1154190''>cut</span> <span m=''1154430''>that</span> <span m=''1154510''>just</span>
  <span m=''1154690''>stops</span> <span m=''1155000''>in</span> <span m=''1155060''>the</span>
  <span m=''1155120''>middle</span> <span m=''1155350''>of a</span> <span m=''1155500''>flat</span>
  <span m=''1155570''>vertex,</span> <span m=''1155970''>well,</span> <span m=''1156140''>you
  might</span> <span m=''1156350''>as</span> <span m=''1156470''>well</span> <span
  m=''1156840''>not</span> <span m=''1157080''>have</span> <span m=''1157210''>done</span>
  <span m=''1157380''>that</span> <span m=''1157590''>cut,</span> <span m=''1158020''>so</span>
  <span m=''1158170''>you</span> <span m=''1158250''>could</span> <span m=''1158390''>erase</span>
  <span m=''1158720''>it.</span> </p><p><span m=''1159420''>So</span> <span m=''1159570''>it''s</span>
  <span m=''1159690''>got</span> <span m=''1159880''>to</span> <span m=''1159930''>go</span>
  <span m=''1160050''>somewhere.</span> <span m=''1160400''>They</span> <span m=''1160550''>could</span>
  <span m=''1160820''>go</span> <span m=''1161030''>to</span> <span m=''1161350''>each</span>
  <span m=''1161670''>other,</span> <span m=''1162510''>in</span> <span m=''1162890''>which</span>
  <span m=''1163120''>case</span> <span m=''1163300''>you''ve</span> <span m=''1163420''>made</span>
  <span m=''1163600''>a</span> <span m=''1163640''>cycle</span> <span m=''1164100''>and
  then you''ve</span> <span m=''1164350''>disconnected</span> <span m=''1164880''>your</span>
  <span m=''1165000''>surface</span> <span m=''1165660''>because</span> <span m=''1165920''>this</span>
  <span m=''1166150''>is</span> <span m=''1166290''>like</span> <span m=''1166470''>a</span>
  <span m=''1166520''>disk,</span> <span m=''1167600''>or</span> <span m=''1167830''>they</span>
  <span m=''1167940''>could</span> <span m=''1168090''>go</span> <span m=''1168210''>to</span>
  <span m=''1168280''>the</span> <span m=''1168390''>boundary.</span> <span m=''1169070''>And</span>
  <span m=''1169380''>if</span> <span m=''1169650''>they</span> <span m=''1169790''>both</span>
  <span m=''1170060''>go</span> <span m=''1170210''>to the</span> <span m=''1170300''>boundary,</span>
  <span m=''1170650''>again,</span> <span m=''1170920''>you</span> <span m=''1171050''>disconnect</span>
  <span m=''1171230''>your</span> <span m=''1171580''>surface,</span> <span m=''1172350''>two</span>
  <span m=''1172500''>pieces.</span> <span m=''1173640''>So</span> <span m=''1173770''>this
  is</span> <span m=''1173920''>kind</span> <span m=''1174110''>of</span> <span m=''1174200''>pathetic,</span>
  <span m=''1174840''>but</span> <span m=''1175200''>you</span> <span m=''1175940''>can''t</span>
  <span m=''1176460''>unfold</span> <span m=''1176860''>this</span> <span m=''1177120''>with</span>
  <span m=''1177270''>one</span> <span m=''1178090''>piece,</span> <span m=''1178450''>no</span>
  <span m=''1178660''>overlap.</span> </p><p><span m=''1180240''>So</span> <span m=''1180450''>when</span>
  <span m=''1180610''>I</span> <span m=''1180730''>say,</span> <span m=''1181100''>in</span>
  <span m=''1181210''>this</span> <span m=''1181380''>picture,</span> <span m=''1181870''>and</span>
  <span m=''1182050''>I</span> <span m=''1182120''>say</span> <span m=''1182370''>that
  it''s</span> <span m=''1182560''>open</span> <span m=''1182920''>whether</span>
  <span m=''1183130''>non-convex</span> <span m=''1183700''>polyhedra</span> <span
  m=''1184640''>can</span> <span m=''1184800''>be</span> <span m=''1184880''>generally</span>
  <span m=''1185230''>unfolded,</span> <span m=''1185790''>I</span> <span m=''1185900''>mean</span>
  <span m=''1187040''>non-convex</span> <span m=''1187570''>polyhedra</span> <span
  m=''1188020''>without</span> <span m=''1188340''>boundary.</span> <span m=''1189770''>I''ll</span>
  <span m=''1189990''>even</span> <span m=''1190250''>give</span> <span m=''1190420''>you</span>
  <span m=''1190530''>handles</span> <span m=''1191030''>if</span> <span m=''1191160''>you</span>
  <span m=''1191290''>want.</span> <span m=''1191955''>I''m</span> <span m=''1192350''>not</span>
  <span m=''1192500''>sure</span> <span m=''1192650''>that</span> <span m=''1192810''>it</span>
  <span m=''1192890''>matters</span> <span m=''1193230''>too</span> <span m=''1193370''>much,</span>
  <span m=''1194780''>but</span> <span m=''1194960''>boundary</span> <span m=''1195320''>seems</span>
  <span m=''1195580''>to</span> <span m=''1195670''>make</span> <span m=''1195850''>a</span>
  <span m=''1195900''>big</span> <span m=''1196090''>difference.</span> <span m=''1196870''>So</span>
  <span m=''1197090''>what''s</span> <span m=''1198350''>wrong</span> <span m=''1198670''>is</span>
  <span m=''1198960''>this</span> <span m=''1199040''>polyhedron</span> <span m=''1199340''>is</span>
  <span m=''1199460''>kind</span> <span m=''1199650''>of</span> <span m=''1199780''>incomplete,</span>
  <span m=''1200680''>and</span> <span m=''1200880''>as</span> <span m=''1200980''>long</span>
  <span m=''1201210''>as</span> <span m=''1201280''>you</span> <span m=''1201430''>close</span>
  <span m=''1201750''>it</span> <span m=''1201820''>up</span> <span m=''1202040''>somehow</span>
  <span m=''1202870''>and</span> <span m=''1203110''>don''t</span> <span m=''1203140''>have</span>
  <span m=''1203380''>these</span> <span m=''1204080''>boundary</span> <span m=''1204380''>effects,</span>
  <span m=''1204870''>then</span> <span m=''1205750''>maybe</span> <span m=''1206710''>you</span>
  <span m=''1206930''>can</span> <span m=''1207070''>generally</span> <span m=''1207440''>unfold</span>
  <span m=''1207810''>everything.</span> <span m=''1208560''>That''s</span> <span
  m=''1209930''>this</span> <span m=''1210140''>question.</span> </p><p><span m=''1219410''>That</span>
  <span m=''1219850''>was</span> <span m=''1220450''>a</span> <span m=''1220550''>little</span>
  <span m=''1220780''>bit</span> <span m=''1220910''>on</span> <span m=''1221050''>this.</span>
  <span m=''1221250''>We''ll</span> <span m=''1221360''>come</span> <span m=''1221520''>back</span>
  <span m=''1221700''>to it</span> <span m=''1221840''>more</span> <span m=''1222060''>next</span>
  <span m=''1222310''>lecture.</span> <span m=''1223940''>Next,</span> <span m=''1224280''>I</span>
  <span m=''1224410''>want</span> <span m=''1224720''>to</span> <span m=''1224840''>do</span>
  <span m=''1226460''>this</span> <span m=''1226650''>one,</span> <span m=''1227580''>general</span>
  <span m=''1227940''>unfolding</span> <span m=''1228520''>of</span> <span m=''1228940''>convex</span>
  <span m=''1229360''>polyhedra.</span> <span m=''1229870''>This</span> <span m=''1230040''>is</span>
  <span m=''1230170''>really</span> <span m=''1231080''>the</span> <span m=''1231180''>most</span>
  <span m=''1231460''>positive</span> <span m=''1231890''>news</span> <span m=''1232430''>I</span>
  <span m=''1232540''>could</span> <span m=''1232770''>give</span> <span m=''1232930''>you.</span>
  <span m=''1236200''>All</span> <span m=''1236330''>this</span> <span m=''1236490''>unfolding</span>
  <span m=''1236660''>stuff,</span> <span m=''1237190''>it''s</span> <span m=''1237490''>the</span>
  <span m=''1237590''>one</span> <span m=''1238000''>good</span> <span m=''1238200''>result.</span>
  <span m=''1239540''>We</span> <span m=''1239660''>know</span> <span m=''1239790''>several</span>
  <span m=''1240070''>good</span> <span m=''1240210''>results,</span> <span m=''1240690''>but</span>
  <span m=''1241070''>in</span> <span m=''1241360''>terms</span> <span m=''1241590''>of</span>
  <span m=''1241670''>that</span> <span m=''1241900''>table,</span> <span m=''1242370''>it''s</span>
  <span m=''1242510''>our</span> <span m=''1242600''>only</span> <span m=''1242810''>good</span>
  <span m=''1242980''>result.</span> <span m=''1246020''>And</span> <span m=''1246760''>to</span>
  <span m=''1247370''>do</span> <span m=''1247520''>that,</span> <span m=''1249090''>there''s</span>
  <span m=''1249240''>a</span> <span m=''1249290''>bunch</span> <span m=''1249540''>of</span>
  <span m=''1249610''>solutions</span> <span m=''1250030''>to</span> <span m=''1250090''>this</span>
  <span m=''1250210''>problem.</span> <span m=''1250530''>They</span> <span m=''1250690''>all</span>
  <span m=''1250920''>use</span> <span m=''1251220''>the</span> <span m=''1251350''>idea</span>
  <span m=''1251740''>of</span> <span m=''1251850''>shortest</span> <span m=''1252230''>paths.</span>
  </p><p><span m=''1271540''>The</span> <span m=''1272410''>shortest</span> <span
  m=''1272750''>path</span> <span m=''1273170''>is</span> <span m=''1273390''>a</span>
  <span m=''1273490''>path</span> <span m=''1274050''>that''s</span> <span m=''1274210''>shortest.</span>
  <span m=''1275210''>So</span> <span m=''1276010''>you</span> <span m=''1276160''>have</span>
  <span m=''1276480''>some</span> <span m=''1276740''>surface,</span> <span m=''1277790''>you</span>
  <span m=''1277910''>have</span> <span m=''1278150''>some</span> <span m=''1278390''>points.</span>
  <span m=''1279380''>You</span> <span m=''1279490''>do</span> <span m=''1279700''>this</span>
  <span m=''1279840''>all</span> <span m=''1279960''>the</span> <span m=''1280020''>time</span>
  <span m=''1280260''>when</span> <span m=''1280350''>you''re</span> <span m=''1280640''>flying</span>
  <span m=''1281060''>between</span> <span m=''1281360''>two</span> <span m=''1281490''>cities.</span>
  <span m=''1282240''>You</span> <span m=''1282350''>follow a</span> <span m=''1282720''>shortest</span>
  <span m=''1283110''>path</span> <span m=''1283600''>on</span> <span m=''1283940''>a</span>
  <span m=''1284000''>sphere.</span> <span m=''1285870''>It''s</span> <span m=''1286170''>not</span>
  <span m=''1286410''>straight</span> <span m=''1286720''>in</span> <span m=''1286810''>three</span>
  <span m=''1286980''>dimensions.</span> <span m=''1287620''>It''s</span> <span m=''1287760''>the</span>
  <span m=''1287830''>shortest</span> <span m=''1288190''>thing</span> <span m=''1288450''>subject</span>
  <span m=''1288960''>to</span> <span m=''1289110''>lying</span> <span m=''1289510''>on</span>
  <span m=''1289650''>that</span> <span m=''1289830''>surface,</span> <span m=''1290670''>what</span>
  <span m=''1290890''>is</span> <span m=''1290990''>the</span> <span m=''1291050''>shortest</span>
  <span m=''1291380''>path</span> <span m=''1291630''>you</span> <span m=''1291740''>can</span>
  <span m=''1292230''>do?</span> </p><p><span m=''1292310''>So you''re</span> <span
  m=''1292520''>used to</span> <span m=''1292610''>it</span> <span m=''1292790''>on</span>
  <span m=''1292920''>a</span> <span m=''1292970''>sphere.</span> <span m=''1293870''>It''s</span>
  <span m=''1293960''>a</span> <span m=''1294010''>little</span> <span m=''1294240''>weirder</span>
  <span m=''1294440''>on</span> <span m=''1294620''>a</span> <span m=''1294670''>polyhedron,</span>
  <span m=''1295300''>but</span> <span m=''1295450''>it''s</span> <span m=''1295700''>just</span>
  <span m=''1295890''>the</span> <span m=''1295950''>same</span> <span m=''1296180''>idea.</span>
  <span m=''1297520''>Take</span> <span m=''1297770''>all</span> <span m=''1297940''>the</span>
  <span m=''1298020''>possible</span> <span m=''1298440''>paths</span> <span m=''1298670''>you</span>
  <span m=''1298790''>could,</span> <span m=''1299520''>find</span> <span m=''1299710''>the</span>
  <span m=''1299770''>shortest</span> <span m=''1300160''>one.</span> <span m=''1300570''>You</span>
  <span m=''1300700''>fix</span> <span m=''1301160''>the</span> <span m=''1301300''>two</span>
  <span m=''1301460''>endpoints,</span> <span m=''1301860''>x</span> <span m=''1302060''>and</span>
  <span m=''1302140''>y,</span> <span m=''1303000''>and</span> <span m=''1303120''>you</span>
  <span m=''1303190''>get</span> <span m=''1303320''>to</span> <span m=''1303400''>optimize</span>
  <span m=''1303940''>this.</span> <span m=''1304260''>Whatever is</span> <span m=''1304690''>shortest</span>
  <span m=''1305570''>is</span> <span m=''1305760''>the</span> <span m=''1305850''>right</span>
  <span m=''1306060''>thing.</span> </p><p><span m=''1306860''>I</span> <span m=''1306960''>have</span>
  <span m=''1307060''>some</span> <span m=''1307210''>pictures</span> <span m=''1307630''>of</span>
  <span m=''1307700''>what</span> <span m=''1307850''>they</span> <span m=''1307930''>look</span>
  <span m=''1308140''>like</span> <span m=''1311060''>here.</span> <span m=''1312660''>So</span>
  <span m=''1312840''>these</span> <span m=''1313130''>are</span> <span m=''1313220''>some</span>
  <span m=''1313420''>convex</span> <span m=''1313820''>polyhedra.</span> <span m=''1316240''>They''re</span>
  <span m=''1318740''>probably</span> <span m=''1319050''>random</span> <span m=''1319370''>points</span>
  <span m=''1319640''>on</span> <span m=''1319730''>a</span> <span m=''1319770''>sphere,</span>
  <span m=''1320050''>take</span> <span m=''1320260''>the</span> <span m=''1320340''>convex</span>
  <span m=''1320750''>hull.</span> <span m=''1321650''>And</span> <span m=''1321830''>then</span>
  <span m=''1321970''>we</span> <span m=''1322070''>pick</span> <span m=''1322270''>some</span>
  <span m=''1322550''>vertex,</span> <span m=''1323280''>or</span> <span m=''1323360''>some</span>
  <span m=''1323560''>point</span> <span m=''1323840''>x</span> <span m=''1324360''>in</span>
  <span m=''1324470''>the</span> <span m=''1324560''>corner</span> <span m=''1324810''>there,</span>
  <span m=''1325160''>and</span> <span m=''1325420''>this</span> <span m=''1325570''>is</span>
  <span m=''1325680''>computing</span> <span m=''1326080''>the</span> <span m=''1326140''>shortest</span>
  <span m=''1326500''>paths</span> <span m=''1326810''>from</span> <span m=''1327020''>x</span>
  <span m=''1327580''>to</span> <span m=''1327720''>every</span> <span m=''1328030''>other</span>
  <span m=''1328210''>vertex</span> <span m=''1328720''>on</span> <span m=''1328860''>the</span>
  <span m=''1328950''>polyhedron.</span> </p><p><span m=''1330360''>So</span> <span
  m=''1330500''>they</span> <span m=''1330620''>look</span> <span m=''1330890''>very</span>
  <span m=''1331240''>straight</span> <span m=''1332280''>in</span> <span m=''1332350''>this</span>
  <span m=''1332500''>case</span> <span m=''1332700''>because</span> <span m=''1332890''>the</span>
  <span m=''1333000''>polyhedron</span> <span m=''1333310''>is</span> <span m=''1333570''>almost</span>
  <span m=''1333910''>a</span> <span m=''1333960''>sphere.</span> <span m=''1334430''>They</span>
  <span m=''1334570''>look</span> <span m=''1334760''>kind</span> <span m=''1335000''>of</span>
  <span m=''1335090''>like</span> <span m=''1335750''>great</span> <span m=''1335960''>circular</span>
  <span m=''1336420''>arcs</span> <span m=''1336520''>on</span> <span m=''1336610''>a</span>
  <span m=''1336670''>sphere,</span> <span m=''1337020''>but</span> <span m=''1337120''>they''re</span>
  <span m=''1337220''>not</span> <span m=''1337410''>quite.</span> <span m=''1338130''>You</span>
  <span m=''1338250''>can</span> <span m=''1338390''>look</span> <span m=''1338710''>carefully</span>
  <span m=''1340110''>at</span> <span m=''1340260''>an</span> <span m=''1340420''>edge</span>
  <span m=''1340840''>here,</span> <span m=''1341210''>this</span> <span m=''1341490''>does</span>
  <span m=''1341760''>bend</span> <span m=''1342100''>a</span> <span m=''1342150''>little</span>
  <span m=''1342370''>bit.</span> <span m=''1343470''>It''s a</span> <span m=''1343560''>bit</span>
  <span m=''1343750''>subtle.</span> <span m=''1345190''>It</span> <span m=''1345330''>bends</span>
  <span m=''1345570''>only</span> <span m=''1345780''>a</span> <span m=''1345850''>little</span>
  <span m=''1346100''>bit</span> <span m=''1346310''>because</span> <span m=''1346770''>the</span>
  <span m=''1346970''>property</span> <span m=''1347460''>you</span> <span m=''1347580''>want</span>
  <span m=''1348030''>is</span> <span m=''1348360''>if</span> <span m=''1348500''>you</span>
  <span m=''1348640''>look</span> <span m=''1348810''>at</span> <span m=''1348900''>this</span>
  <span m=''1349090''>triangle</span> <span m=''1349730''>and</span> <span m=''1350010''>this</span>
  <span m=''1350190''>triangle</span> <span m=''1351130''>and</span> <span m=''1351270''>you</span>
  <span m=''1351440''>unfold</span> <span m=''1351710''>them--</span> <span m=''1352550''>so</span>
  <span m=''1352720''>right</span> <span m=''1352910''>now,</span> <span m=''1353060''>they</span>
  <span m=''1353160''>have</span> <span m=''1353360''>some</span> <span m=''1354520''>dihedral</span>
  <span m=''1354800''>angle</span> <span m=''1355030''>between</span> <span m=''1355360''>them,</span>
  <span m=''1356110''>and</span> <span m=''1356290''>if</span> <span m=''1356430''>you</span>
  <span m=''1356840''>open</span> <span m=''1357140''>it</span> <span m=''1357240''>out</span>
  <span m=''1357500''>so</span> <span m=''1357630''>that</span> <span m=''1357810''>they''re</span>
  <span m=''1358170''>flat,</span> <span m=''1359180''>then</span> <span m=''1359470''>this</span>
  <span m=''1359640''>line</span> <span m=''1359860''>should</span> <span m=''1360050''>be</span>
  <span m=''1360170''>straight.</span> </p><p><span m=''1361150''>Still</span> <span
  m=''1361380''>the</span> <span m=''1361470''>case</span> <span m=''1361760''>that</span>
  <span m=''1362180''>shortest</span> <span m=''1362630''>paths</span> <span m=''1362910''>are</span>
  <span m=''1363000''>straight</span> <span m=''1363230''>lines,</span> <span m=''1364260''>but</span>
  <span m=''1364420''>only</span> <span m=''1364670''>when</span> <span m=''1364770''>you</span>
  <span m=''1364890''>unfold.</span> <span m=''1365410''>That''s</span> <span m=''1365730''>the</span>
  <span m=''1366050''>idea.</span> <span m=''1366315''>So</span> <span m=''1366580''>if</span>
  <span m=''1366690''>you</span> <span m=''1366800''>look</span> <span m=''1366960''>at</span>
  <span m=''1367010''>all</span> <span m=''1367260''>the</span> <span m=''1367350''>triangles</span>
  <span m=''1367830''>are</span> <span m=''1367890''>visited</span> <span m=''1368220''>by
  a</span> <span m=''1368380''>path,</span> <span m=''1368800''>and</span> <span m=''1369120''>you</span>
  <span m=''1369260''>unfold</span> <span m=''1369720''>them</span> <span m=''1369990''>to</span>
  <span m=''1370120''>be</span> <span m=''1370370''>a</span> <span m=''1370420''>straight</span>
  <span m=''1370770''>thing--</span> <span m=''1371130''>this is called</span> <span
  m=''1371360''>developing,</span> <span m=''1372435''>you</span> <span m=''1372900''>flatten</span>
  <span m=''1373250''>it</span> <span m=''1373350''>out--</span> <span m=''1373860''>then</span>
  <span m=''1374290''>actually,</span> <span m=''1374700''>the</span> <span m=''1375040''>shortest</span>
  <span m=''1375350''>path</span> <span m=''1375540''>will</span> <span m=''1375680''>be</span>
  <span m=''1375760''>a</span> <span m=''1375820''>straight</span> <span m=''1376070''>line,</span>
  <span m=''1376420''>so</span> <span m=''1376590''>that</span> <span m=''1376680''>makes</span>
  <span m=''1376880''>it</span> <span m=''1376970''>really</span> <span m=''1377210''>easy</span>
  <span m=''1377410''>to</span> <span m=''1377490''>draw</span> <span m=''1377680''>these</span>
  <span m=''1377870''>things.</span> <span m=''1378690''>There</span> <span m=''1378820''>still</span>
  <span m=''1379240''>might</span> <span m=''1379470''>be</span> <span m=''1379620''>multiple</span>
  <span m=''1380110''>candidates,</span> <span m=''1380630''>like</span> <span m=''1380770''>to</span>
  <span m=''1380850''>get</span> <span m=''1381010''>here,</span> <span m=''1381250''>should</span>
  <span m=''1381410''>I</span> <span m=''1381460''>go</span> <span m=''1381600''>this</span>
  <span m=''1381800''>way</span> <span m=''1381940''>or</span> <span m=''1382050''>the</span>
  <span m=''1382170''>other</span> <span m=''1382320''>way</span> <span m=''1382400''>around,</span>
  <span m=''1383610''>but</span> <span m=''1384900''>each</span> <span m=''1385060''>of</span>
  <span m=''1385130''>those</span> <span m=''1385320''>will</span> <span m=''1385490''>be</span>
  <span m=''1386270''>locally</span> <span m=''1386660''>straight,</span> <span m=''1387590''>and</span>
  <span m=''1387760''>this</span> <span m=''1387890''>is</span> <span m=''1388030''>a</span>
  <span m=''1388100''>property</span> <span m=''1388480''>called</span> <span m=''1388740''>geodesic.</span>
  </p><p><span m=''1393630''>Shortest</span> <span m=''1394110''>paths</span> <span
  m=''1394840''>always</span> <span m=''1395810''>unfold</span> <span m=''1396230''>straight.</span>
  <span m=''1397360''>And in</span> <span m=''1397590''>general,</span> <span m=''1397860''>anything</span>
  <span m=''1398300''>that</span> <span m=''1398450''>unfolds</span> <span m=''1398820''>straight,</span>
  <span m=''1399300''>it</span> <span m=''1399430''>might</span> <span m=''1399630''>not</span>
  <span m=''1399770''>even</span> <span m=''1399950''>be</span> <span m=''1400050''>shortest,</span>
  <span m=''1401100''>is</span> <span m=''1401260''>a</span> <span m=''1401310''>geodesic.</span>
  <span m=''1406110''>These</span> <span m=''1406300''>are</span> <span m=''1406350''>like</span>
  <span m=''1406560''>locally</span> <span m=''1407020''>shortest.</span> <span m=''1407590''>Locally,</span>
  <span m=''1407980''>you</span> <span m=''1408070''>can''t</span> <span m=''1408260''>make</span>
  <span m=''1408400''>them</span> <span m=''1408510''>any</span> <span m=''1408640''>shorter,</span>
  <span m=''1408910''>but</span> <span m=''1409030''>they</span> <span m=''1409110''>might</span>
  <span m=''1409310''>have</span> <span m=''1409400''>made</span> <span m=''1409560''>the</span>
  <span m=''1409650''>wrong</span> <span m=''1409900''>choice.</span> <span m=''1410270''>They
  might</span> <span m=''1410450''>have</span> <span m=''1410540''>gone</span> <span
  m=''1410730''>around</span> <span m=''1411160''>the</span> <span m=''1411260''>wrong</span>
  <span m=''1411490''>way.</span> <span m=''1415400''>Geodesic</span> <span m=''1415970''>means</span>
  <span m=''1416410''>going</span> <span m=''1416630''>straight</span> <span m=''1417020''>for</span>
  <span m=''1417180''>a</span> <span m=''1417230''>long</span> <span m=''1417440''>time.</span>
  <span m=''1417700''>You</span> <span m=''1417800''>could</span> <span m=''1417930''>actually</span>
  <span m=''1418150''>spiral</span> <span m=''1418580''>around</span> <span m=''1418930''>and</span>
  <span m=''1419030''>do</span> <span m=''1419150''>all</span> <span m=''1419250''>sorts</span>
  <span m=''1419470''>of</span> <span m=''1419550''>crazy</span> <span m=''1419860''>things.</span>
  </p><p><span m=''1420610''>But</span> <span m=''1420750''>shortest</span> <span
  m=''1421090''>paths</span> <span m=''1422810''>never</span> <span m=''1423140''>cross</span>
  <span m=''1423460''>themselves</span> <span m=''1430440''>because</span> <span m=''1430580''>if</span>
  <span m=''1430690''>you</span> <span m=''1430790''>had</span> <span m=''1430970''>the</span>
  <span m=''1431030''>shortest</span> <span m=''1431390''>path</span> <span m=''1432220''>that</span>
  <span m=''1432340''>crossed</span> <span m=''1432690''>itself,</span> <span m=''1433070''>that</span>
  <span m=''1433150''>wasn''t</span> <span m=''1433430''>shortest.</span> <span m=''1433840''>You</span>
  <span m=''1433920''>should</span> <span m=''1434120''>have</span> <span m=''1434900''>just</span>
  <span m=''1435570''>gotten</span> <span m=''1435790''>rid</span> <span m=''1435950''>of</span>
  <span m=''1436040''>this</span> <span m=''1436220''>part</span> <span m=''1436980''>and</span>
  <span m=''1437170''>gone</span> <span m=''1437320''>straight</span> <span m=''1437730''>through</span>
  <span m=''1438050''>the</span> <span m=''1438200''>crossing.</span> <span m=''1439830''>That''s</span>
  <span m=''1440130''>sort of</span> <span m=''1440470''>trivial.</span> </p><p><span
  m=''1441560''>And</span> <span m=''1441850''>there''s</span> <span m=''1441990''>another</span>
  <span m=''1442200''>good,</span> <span m=''1442620''>fun</span> <span m=''1442860''>property</span>
  <span m=''1443875''>that</span> <span m=''1444480''>you</span> <span m=''1444600''>may</span>
  <span m=''1444740''>not</span> <span m=''1444900''>have</span> <span m=''1445010''>noticed</span>
  <span m=''1445360''>in</span> <span m=''1445460''>those</span> <span m=''1445710''>figures,</span>
  <span m=''1447330''>but</span> <span m=''1447850''>they</span> <span m=''1449740''>never</span>
  <span m=''1450170''>pass</span> <span m=''1450660''>through</span> <span m=''1453520''>positive</span>
  <span m=''1454120''>curvature</span> <span m=''1454500''>vertex.</span> <span m=''1465360''>So</span>
  <span m=''1465470''>if</span> <span m=''1465560''>you</span> <span m=''1465670''>look</span>
  <span m=''1465850''>at</span> <span m=''1465890''>these</span> <span m=''1466040''>pictures,</span>
  <span m=''1468060''>they</span> <span m=''1468240''>might</span> <span m=''1468590''>end</span>
  <span m=''1469300''>at</span> <span m=''1469420''>a</span> <span m=''1469480''>positive</span>
  <span m=''1469890''>curvature</span> <span m=''1470260''>vertex</span> <span m=''1470630''>because</span>
  <span m=''1470770''>that''s</span> <span m=''1470950''>where</span> <span m=''1471040''>we</span>
  <span m=''1471170''>told</span> <span m=''1471390''>the</span> <span m=''1471450''>shortest</span>
  <span m=''1471740''>path</span> <span m=''1471970''>to</span> <span m=''1472090''>go,</span>
  <span m=''1472960''>but</span> <span m=''1473090''>in</span> <span m=''1473230''>the</span>
  <span m=''1473310''>middle,</span> <span m=''1473690''>they''re</span> <span m=''1473850''>always</span>
  <span m=''1474140''>crossing</span> <span m=''1474560''>edges.</span> <span m=''1475050''>This</span>
  <span m=''1475200''>is</span> <span m=''1475250''>a</span> <span m=''1475320''>convex</span>
  <span m=''1475720''>polyhedron</span> <span m=''1476690''>so</span> <span m=''1476810''>everything''s</span>
  <span m=''1477190''>positive</span> <span m=''1477540''>curvature</span> <span m=''1477920''>or</span>
  <span m=''1478010''>zero.</span> <span m=''1478810''>In</span> <span m=''1479260''>that</span>
  <span m=''1479450''>case,</span> <span m=''1479760''>the</span> <span m=''1480100''>paths</span>
  <span m=''1480830''>can</span> <span m=''1480960''>really</span> <span m=''1481200''>only</span>
  <span m=''1481390''>go</span> <span m=''1481520''>through</span> <span m=''1481930''>zero</span>
  <span m=''1482390''>curvature</span> <span m=''1482800''>points.</span> <span m=''1483800''>They</span>
  <span m=''1484260''>might</span> <span m=''1484420''>start and</span> <span m=''1484840''>end</span>
  <span m=''1485060''>wherever,</span> <span m=''1486010''>but</span> <span m=''1486160''>in</span>
  <span m=''1486300''>between,</span> <span m=''1488040''>they</span> <span m=''1488160''>never</span>
  <span m=''1488410''>hit</span> <span m=''1488570''>a</span> <span m=''1488630''>corner.</span>
  </p><p><span m=''1489010''>Why?</span> <span m=''1489980''>Because</span> <span
  m=''1490550''>if</span> <span m=''1490660''>you</span> <span m=''1490760''>have</span>
  <span m=''1491590''>a</span> <span m=''1491880''>positive</span> <span m=''1492260''>curvature</span>
  <span m=''1492640''>vertex--</span> <span m=''1494200''>I''m</span> <span m=''1494260''>just</span>
  <span m=''1494430''>going</span> <span m=''1494530''>to</span> <span m=''1494610''>sketch</span>
  <span m=''1494980''>this</span> <span m=''1495190''>idea--</span> <span m=''1496240''>if</span>
  <span m=''1496410''>you</span> <span m=''1496590''>went</span> <span m=''1497090''>up</span>
  <span m=''1497270''>here</span> <span m=''1497700''>in</span> <span m=''1497910''>order</span>
  <span m=''1498040''>to</span> <span m=''1498160''>go</span> <span m=''1498310''>back</span>
  <span m=''1498600''>down</span> <span m=''1498940''>somewhere</span> <span m=''1499540''>like</span>
  <span m=''1499720''>there,</span> <span m=''1500550''>it''s</span> <span m=''1500800''>always</span>
  <span m=''1501170''>better</span> <span m=''1501720''>to</span> <span m=''1502300''>shortcut</span>
  <span m=''1502740''>a</span> <span m=''1502800''>little</span> <span m=''1503000''>bit</span>
  <span m=''1503680''>and</span> <span m=''1504100''>not</span> <span m=''1504530''>go</span>
  <span m=''1504950''>through</span> <span m=''1505160''>the</span> <span m=''1505250''>vertex.</span>
  <span m=''1505730''>It''s</span> <span m=''1505840''>better</span> <span m=''1506060''>to</span>
  <span m=''1506130''>go</span> <span m=''1506250''>around</span> <span m=''1506660''>one</span>
  <span m=''1506830''>way</span> <span m=''1506930''>or</span> <span m=''1507030''>the</span>
  <span m=''1507180''>other.</span> <span m=''1508276''>I''m</span> <span m=''1508670''>just</span>
  <span m=''1508840''>going</span> <span m=''1508920''>to</span> <span m=''1508980''>wave</span>
  <span m=''1509140''>my</span> <span m=''1509280''>hands</span> <span m=''1509560''>at</span>
  <span m=''1509630''>that,</span> <span m=''1510300''>but</span> <span m=''1510440''>it''s</span>
  <span m=''1510630''>true.</span> <span m=''1513550''>So</span> <span m=''1513940''>what?</span>
  </p><p><span m=''1514690''>Shortest</span> <span m=''1515080''>paths</span> <span
  m=''1515390''>are</span> <span m=''1515440''>going</span> <span m=''1515570''>to</span>
  <span m=''1515630''>be a</span> <span m=''1515790''>really</span> <span m=''1516020''>powerful</span>
  <span m=''1516410''>tool</span> <span m=''1516690''>for</span> <span m=''1516880''>finding</span>
  <span m=''1517270''>unfoldings.</span> <span m=''1525530''>In</span> <span m=''1525700''>particular,</span>
  <span m=''1527890''>I</span> <span m=''1528040''>want</span> <span m=''1528260''>to</span>
  <span m=''1528330''>define</span> <span m=''1528720''>the</span> <span m=''1528810''>star,</span>
  <span m=''1530800''>that</span> <span m=''1531070''>picture,</span> <span m=''1532640''>of</span>
  <span m=''1532790''>all</span> <span m=''1532990''>shortest</span> <span m=''1533350''>paths</span>
  <span m=''1534650''>from</span> <span m=''1534890''>one</span> <span m=''1535090''>point.</span>
  <span m=''1550630''>And</span> <span m=''1551140''>do I</span> <span m=''1551170''>want</span>
  <span m=''1551570''>points</span> <span m=''1552000''>here?</span> <span m=''1552770''>I</span>
  <span m=''1552790''>think</span> <span m=''1553090''>I</span> <span m=''1553160''>want</span>
  <span m=''1553600''>vertices.</span> <span m=''1558000''>That''s</span> <span m=''1558220''>the</span>
  <span m=''1558310''>picture</span> <span m=''1558610''>that</span> <span m=''1558790''>we</span>
  <span m=''1558880''>drew.</span> </p><p><span m=''1564330''>The</span> <span m=''1564510''>interesting</span>
  <span m=''1564950''>thing</span> <span m=''1565140''>about</span> <span m=''1565350''>all</span>
  <span m=''1565470''>the</span> <span m=''1565570''>shortest</span> <span m=''1565930''>paths,</span>
  <span m=''1566240''>they all</span> <span m=''1566430''>start from</span> <span
  m=''1566790''>the</span> <span m=''1566880''>same</span> <span m=''1567090''>point,</span>
  <span m=''1568800''>they</span> <span m=''1569000''>never</span> <span m=''1569300''>hit</span>
  <span m=''1569490''>each</span> <span m=''1569690''>other.</span> <span m=''1570560''>So</span>
  <span m=''1570690''>not</span> <span m=''1570870''>only</span> <span m=''1571010''>does</span>
  <span m=''1571170''>a</span> <span m=''1571220''>shortest</span> <span m=''1571510''>path</span>
  <span m=''1571710''>not hit</span> <span m=''1571970''>itself,</span> <span m=''1572650''>but</span>
  <span m=''1572770''>if</span> <span m=''1572860''>you</span> <span m=''1572930''>take</span>
  <span m=''1573130''>many</span> <span m=''1573380''>shortest</span> <span m=''1573730''>paths,</span>
  <span m=''1574750''>or</span> <span m=''1575120''>even</span> <span m=''1575380''>two</span>
  <span m=''1575530''>shortest</span> <span m=''1575860''>paths</span> <span m=''1576150''>from</span>
  <span m=''1576330''>a</span> <span m=''1576650''>common</span> <span m=''1577090''>starting</span>
  <span m=''1577560''>point,</span> <span m=''1578950''>they</span> <span m=''1579070''>can''t</span>
  <span m=''1579390''>hit</span> <span m=''1579590''>each</span> <span m=''1579790''>other.</span>
  <span m=''1581800''>It</span> <span m=''1582050''>could</span> <span m=''1582400''>be</span>
  <span m=''1582890''>one</span> <span m=''1583240''>is</span> <span m=''1583490''>a</span>
  <span m=''1583550''>subset</span> <span m=''1584140''>of</span> <span m=''1584240''>another.</span>
  <span m=''1584790''>For</span> <span m=''1584970''>example,</span> <span m=''1585400''>if</span>
  <span m=''1585500''>I</span> <span m=''1585600''>took</span> <span m=''1585660''>the</span>
  <span m=''1585740''>shortest</span> <span m=''1586100''>path</span> <span m=''1587050''>to</span>
  <span m=''1587190''>here</span> <span m=''1588000''>and</span> <span m=''1588220''>then</span>
  <span m=''1588350''>I</span> <span m=''1588440''>also</span> <span m=''1588670''>took</span>
  <span m=''1588830''>the</span> <span m=''1588890''>shortest</span> <span m=''1589160''>path</span>
  <span m=''1589450''>to a</span> <span m=''1589610''>point</span> <span m=''1589900''>just</span>
  <span m=''1590270''>beyond</span> <span m=''1590710''>it,</span> <span m=''1591520''>well,</span>
  <span m=''1591740''>one''s</span> <span m=''1591970''>going</span> <span m=''1592080''>to</span>
  <span m=''1592150''>be</span> <span m=''1592260''>a</span> <span m=''1592320''>prefix</span>
  <span m=''1592760''>of</span> <span m=''1592850''>the</span> <span m=''1592990''>other.</span>
  <span m=''1593380''>Other</span> <span m=''1593770''>than</span> <span m=''1593900''>that,</span>
  <span m=''1594680''>they</span> <span m=''1594830''>will</span> <span m=''1595050''>never</span>
  <span m=''1595320''>cross</span> <span m=''1595660''>each</span> <span m=''1595830''>other.</span>
  <span m=''1596860''>I''m</span> <span m=''1596980''>going</span> <span m=''1597090''>to</span>
  <span m=''1597270''>just</span> <span m=''1597500''>assert</span> <span m=''1597820''>that,</span>
  <span m=''1598130''>not</span> <span m=''1598385''>prove</span> <span m=''1598640''>it</span>
  <span m=''1598940''>here.</span> </p><p><span m=''1599930''>So</span> <span m=''1600120''>really,</span>
  <span m=''1600530''>it does</span> <span m=''1600750''>look</span> <span m=''1601030''>like</span>
  <span m=''1601230''>a</span> <span m=''1601290''>star.</span> <span m=''1601650''>In</span>
  <span m=''1601710''>fact,</span> <span m=''1601970''>you</span> <span m=''1602070''>could</span>
  <span m=''1602210''>fill</span> <span m=''1602530''>in</span> <span m=''1603160''>more</span>
  <span m=''1603390''>shortest</span> <span m=''1603760''>paths.</span> <span m=''1603960''>You</span>
  <span m=''1604060''>could</span> <span m=''1604180''>take</span> <span m=''1604310''>the</span>
  <span m=''1604380''>shortest</span> <span m=''1604700''>path to</span> <span m=''1605000''>here,</span>
  <span m=''1605830''>for</span> <span m=''1605970''>example,</span> <span m=''1606430''>and</span>
  <span m=''1606530''>it''ll</span> <span m=''1606750''>fit</span> <span m=''1606990''>in</span>
  <span m=''1607170''>nicely,</span> <span m=''1608260''>kind</span> <span m=''1608400''>of</span>
  <span m=''1608470''>bisect that</span> <span m=''1608960''>angle</span> <span m=''1609420''>in</span>
  <span m=''1609510''>there.</span> <span m=''1611210''>It''s a</span> <span m=''1611710''>very</span>
  <span m=''1611960''>simple</span> <span m=''1612450''>kind</span> <span m=''1612630''>of</span>
  <span m=''1612690''>structure.</span> <span m=''1613150''>It''s just</span> <span
  m=''1613350''>from a</span> <span m=''1613620''>point,</span> <span m=''1613920''>you
  have</span> <span m=''1614320''>all</span> <span m=''1614600''>this</span> <span
  m=''1614730''>stuff</span> <span m=''1614970''>going</span> <span m=''1615320''>out.</span>
  <span m=''1616120''>They</span> <span m=''1616260''>never</span> <span m=''1616410''>hit</span>
  <span m=''1616720''>each</span> <span m=''1616920''>other</span> <span m=''1624640''>except</span>
  <span m=''1625090''>at</span> <span m=''1625270''>something</span> <span m=''1625650''>called</span>
  <span m=''1626740''>the</span> <span m=''1627100''>cut</span> <span m=''1627370''>locus,</span>
  <span m=''1630880''>also</span> <span m=''1631270''>called</span> <span m=''1631640''>the</span>
  <span m=''1631740''>ridge</span> <span m=''1632076''>tree.</span> <span m=''1638090''>And</span>
  <span m=''1638490''>these</span> <span m=''1638750''>are</span> <span m=''1638870''>points</span>
  <span m=''1643760''>with</span> <span m=''1644200''>non-unique</span> <span m=''1645110''>shortest</span>
  <span m=''1645520''>paths</span> <span m=''1647080''>to</span> <span m=''1647390''>x.</span>
  <span m=''1657960''>So</span> <span m=''1658340''>we''re</span> <span m=''1658830''>fixing</span>
  <span m=''1659180''>some</span> <span m=''1659390''>point,</span> <span m=''1659620''>x.</span>
  </p><p><span m=''1665810''>So</span> <span m=''1665980''>here''s</span> <span m=''1666230''>a</span>
  <span m=''1666290''>simpler</span> <span m=''1666630''>polyhedron.</span> <span
  m=''1667160''>It''s</span> <span m=''1667270''>just</span> <span m=''1667520''>a</span>
  <span m=''1668630''>square-based</span> <span m=''1669410''>pyramid.</span> <span
  m=''1671110''>We''re</span> <span m=''1671300''>picking</span> <span m=''1671820''>x</span>
  <span m=''1672080''>to</span> <span m=''1672170''>be</span> <span m=''1672300''>in</span>
  <span m=''1672390''>the</span> <span m=''1672460''>middle</span> <span m=''1672760''>of</span>
  <span m=''1672870''>this</span> <span m=''1672990''>face,</span> <span m=''1674060''>and</span>
  <span m=''1674450''>drawn in</span> <span m=''1674840''>these</span> <span m=''1675030''>black</span>
  <span m=''1675360''>lines</span> <span m=''1675740''>are</span> <span m=''1675830''>the</span>
  <span m=''1675930''>shortest</span> <span m=''1676290''>paths</span> <span m=''1677110''>from</span>
  <span m=''1677340''>x</span> <span m=''1677600''>to</span> <span m=''1677860''>all</span>
  <span m=''1678130''>the</span> <span m=''1678200''>vertices.</span> <span m=''1680180''>Here,</span>
  <span m=''1680465''>that''s</span> <span m=''1680750''>a</span> <span m=''1681260''>straight</span>
  <span m=''1681660''>line.</span> <span m=''1682440''>This</span> <span m=''1682640''>one,</span>
  <span m=''1682890''>if</span> <span m=''1683000''>you</span> <span m=''1683120''>unfolded</span>
  <span m=''1683610''>it,</span> <span m=''1683740''>it would</span> <span m=''1683900''>be</span>
  <span m=''1684030''>straight,</span> <span m=''1685620''>and</span> <span m=''1685770''>there''s
  some</span> <span m=''1685850''>similar</span> <span m=''1686190''>ones</span> <span
  m=''1686410''>on</span> <span m=''1686490''>the</span> <span m=''1686570''>back.</span>
  <span m=''1687750''>And</span> <span m=''1688030''>I</span> <span m=''1688080''>think</span>
  <span m=''1688300''>this</span> <span m=''1688520''>is</span> <span m=''1688690''>the</span>
  <span m=''1688760''>back</span> <span m=''1689220''>in case</span> <span m=''1689430''>you</span>
  <span m=''1689530''>want</span> <span m=''1689660''>to</span> <span m=''1689710''>see.</span>
  <span m=''1692730''>There''s</span> <span m=''1692910''>one</span> <span m=''1693430''>back</span>
  <span m=''1693650''>face</span> <span m=''1693930''>that</span> <span m=''1694000''>you</span>
  <span m=''1694100''>can''t</span> <span m=''1694320''>see</span> <span m=''1694430''>at</span>
  <span m=''1694520''>all,</span> <span m=''1695330''>C,</span> <span m=''1696050''>behind</span>
  <span m=''1696630''>B</span> <span m=''1696870''>here,</span> <span m=''1698420''>and</span>
  <span m=''1700340''>that''s</span> <span m=''1700550''>what</span> <span m=''1700650''>it</span>
  <span m=''1700710''>looks</span> <span m=''1700950''>like.</span> <span m=''1701120''>There''s</span>
  <span m=''1701280''>no</span> <span m=''1701370''>shortest</span> <span m=''1701750''>paths</span>
  <span m=''1702020''>there.</span> </p><p><span m=''1702310''>Now,</span> <span m=''1702460''>there''s</span>
  <span m=''1702630''>these</span> <span m=''1702820''>dashed</span> <span m=''1703150''>lines.</span>
  <span m=''1703810''>That''s</span> <span m=''1704100''>the</span> <span m=''1704230''>ridge</span>
  <span m=''1704545''>tree.</span> <span m=''1705640''>That''s</span> <span m=''1705950''>the</span>
  <span m=''1706090''>cut</span> <span m=''1706310''>locus.</span> <span m=''1708000''>And</span>
  <span m=''1708220''>these</span> <span m=''1708420''>are</span> <span m=''1708510''>points</span>
  <span m=''1709200''>on</span> <span m=''1709460''>the</span> <span m=''1709550''>backside</span>
  <span m=''1710270''>with</span> <span m=''1710480''>respect</span> <span m=''1710870''>to</span>
  <span m=''1710940''>x.</span> <span m=''1713330''>If</span> <span m=''1713540''>you''re</span>
  <span m=''1713690''>going</span> <span m=''1713930''>from</span> <span m=''1714150''>x,</span>
  <span m=''1714500''>you</span> <span m=''1714610''>go</span> <span m=''1714770''>around</span>
  <span m=''1715780''>behind</span> <span m=''1716350''>to</span> <span m=''1716460''>C,</span>
  <span m=''1717260''>or</span> <span m=''1717490''>you</span> <span m=''1717600''>could</span>
  <span m=''1717740''>go</span> <span m=''1718000''>from</span> <span m=''1718260''>x</span>
  <span m=''1718610''>around</span> <span m=''1718970''>behind</span> <span m=''1719510''>to</span>
  <span m=''1719620''>D</span> <span m=''1720040''>and</span> <span m=''1720460''>then</span>
  <span m=''1720610''>to</span> <span m=''1720720''>C.</span> <span m=''1722330''>At</span>
  <span m=''1722520''>some</span> <span m=''1722710''>point,</span> <span m=''1723800''>those</span>
  <span m=''1724150''>things</span> <span m=''1724430''>meet</span> <span m=''1724760''>and</span>
  <span m=''1724970''>are</span> <span m=''1725160''>still</span> <span m=''1725420''>of</span>
  <span m=''1725530''>equal</span> <span m=''1725900''>length.</span> <span m=''1727040''>So</span>
  <span m=''1727220''>here,</span> <span m=''1728540''>if</span> <span m=''1728890''>you''re</span>
  <span m=''1729150''>trying</span> <span m=''1729330''>to</span> <span m=''1729420''>go</span>
  <span m=''1729540''>to</span> <span m=''1729630''>x,</span> <span m=''1729970''>you</span>
  <span m=''1730140''>could</span> <span m=''1730490''>go</span> <span m=''1730680''>around</span>
  <span m=''1730940''>this</span> <span m=''1731100''>way</span> <span m=''1731640''>or</span>
  <span m=''1731840''>you</span> <span m=''1731970''>could</span> <span m=''1732160''>go</span>
  <span m=''1732270''>around</span> <span m=''1732520''>this</span> <span m=''1732670''>way.</span>
  <span m=''1732800''>They</span> <span m=''1732910''>will</span> <span m=''1733060''>be</span>
  <span m=''1733190''>the</span> <span m=''1733300''>same</span> <span m=''1733620''>length,</span>
  <span m=''1734980''>and</span> <span m=''1735470''>all</span> <span m=''1735810''>the</span>
  <span m=''1735910''>points</span> <span m=''1736230''>with</span> <span m=''1736300''>that</span>
  <span m=''1736480''>property</span> <span m=''1736900''>are</span> <span m=''1736990''>the</span>
  <span m=''1737070''>dashed</span> <span m=''1737880''>lines.</span> </p><p><span
  m=''1738735''>Now,</span> <span m=''1739040''>if</span> <span m=''1739200''>you''re</span>
  <span m=''1739300''>familiar</span> <span m=''1739730''>with</span> <span m=''1739850''>[?
  Vornar ?]</span> <span m=''1740250''>diagrams,</span> <span m=''1740810''>this</span>
  <span m=''1741080''>is</span> <span m=''1741340''>the</span> <span m=''1741430''>[?
  Vornar ?]</span> <span m=''1741780''>diagram</span> <span m=''1742280''>of</span>
  <span m=''1742450''>one</span> <span m=''1742760''>point,</span> <span m=''1743600''>x.</span>
  <span m=''1745700''>Imagine</span> <span m=''1746670''>you</span> <span m=''1746800''>plant</span>
  <span m=''1747310''>grass</span> <span m=''1747990''>over</span> <span m=''1748490''>your</span>
  <span m=''1748720''>polyhedron,</span> <span m=''1749780''>you</span> <span m=''1749940''>light</span>
  <span m=''1750160''>a</span> <span m=''1750210''>fire</span> <span m=''1750630''>here,</span>
  <span m=''1751740''>it</span> <span m=''1751940''>burns</span> <span m=''1752240''>at</span>
  <span m=''1752730''>uniform</span> <span m=''1753290''>speed</span> <span m=''1753580''>in</span>
  <span m=''1753670''>all</span> <span m=''1753810''>directions.</span> <span m=''1755250''>Where</span>
  <span m=''1755480''>the</span> <span m=''1755590''>fire</span> <span m=''1755950''>meets</span>
  <span m=''1756260''>itself</span> <span m=''1756740''>on</span> <span m=''1756840''>the</span>
  <span m=''1756910''>backside,</span> <span m=''1757710''>that</span> <span m=''1757970''>is</span>
  <span m=''1759020''>the</span> <span m=''1759130''>ridge</span> <span m=''1759370''>tree.</span>
  <span m=''1759540''>That</span> <span m=''1759730''>is</span> <span m=''1759880''>the</span>
  <span m=''1759970''>[? Vornar ?]</span> <span m=''1760270''>diagram.</span> </p><p><span
  m=''1762030''>So</span> <span m=''1762280''>it''s</span> <span m=''1762530''>kind</span>
  <span m=''1762680''>of</span> <span m=''1762760''>intuitive</span> <span m=''1763190''>that
  it''s</span> <span m=''1763400''>there.</span> <span m=''1764410''>Maybe</span>
  <span m=''1764690''>less</span> <span m=''1764910''>obvious</span> <span m=''1765240''>is</span>
  <span m=''1765370''>that</span> <span m=''1765480''>it''s</span> <span m=''1765630''>a</span>
  <span m=''1765680''>tree</span> <span m=''1766580''>and</span> <span m=''1766900''>it''s</span>
  <span m=''1767040''>a</span> <span m=''1767080''>spanning</span> <span m=''1767440''>tree.</span>
  <span m=''1767650''>It</span> <span m=''1767760''>hits</span> <span m=''1767960''>all</span>
  <span m=''1768140''>the</span> <span m=''1768210''>vertices.</span> <span m=''1772240''>So</span>
  <span m=''1773230''>it''s</span> <span m=''1773370''>a</span> <span m=''1773420''>natural</span>
  <span m=''1773810''>cutting.</span> <span m=''1775390''>That''s</span> <span m=''1775580''>why</span>
  <span m=''1775680''>it''s</span> <span m=''1775780''>called</span> <span m=''1776080''>the</span>
  <span m=''1776180''>cut</span> <span m=''1776400''>locus,</span> <span m=''1778330''>and</span>
  <span m=''1778640''>it</span> <span m=''1778700''>works</span> <span m=''1779000''>really</span>
  <span m=''1779240''>well.</span> <span m=''1798470''>And</span> <span m=''1798850''>it''s</span>
  <span m=''1798960''>called</span> <span m=''1799190''>the</span> <span m=''1799270''>source</span>
  <span m=''1799630''>unfolding.</span> </p><p><span m=''1811690''>Source</span> <span
  m=''1811850''>unfolding</span> <span m=''1812220''>goes</span> <span m=''1812380''>back</span>
  <span m=''1812550''>to</span> <span m=''1812640''>the</span> <span m=''1812750''>mid</span>
  <span m=''1813040''>''80s.</span> <span m=''1813730''>A</span> <span m=''1814230''>bunch</span>
  <span m=''1814480''>of</span> <span m=''1814580''>people</span> <span m=''1814770''>discovered</span>
  <span m=''1815190''>it</span> <span m=''1815380''>for</span> <span m=''1815530''>various</span>
  <span m=''1816510''>computational</span> <span m=''1817060''>geometry</span> <span
  m=''1817460''>applications.</span> <span m=''1818010''>They</span> <span m=''1818120''>didn''t</span>
  <span m=''1818280''>care</span> <span m=''1818440''>about</span> <span m=''1818710''>unfolding</span>
  <span m=''1819200''>at</span> <span m=''1819310''>the</span> <span m=''1819380''>time.</span>
  <span m=''1820630''>And</span> <span m=''1820810''>it''s</span> <span m=''1820910''>kind</span>
  <span m=''1821110''>of</span> <span m=''1821200''>obvious</span> <span m=''1823760''>after</span>
  <span m=''1823880''>you</span> <span m=''1824010''>think</span> <span m=''1824180''>about</span>
  <span m=''1824420''>it</span> <span m=''1824510''>for</span> <span m=''1824630''>a</span>
  <span m=''1824680''>while,</span> <span m=''1825640''>trying</span> <span m=''1825900''>to</span>
  <span m=''1825990''>solve</span> <span m=''1826250''>this</span> <span m=''1826420''>general</span>
  <span m=''1826710''>unfolding</span> <span m=''1827110''>problem.</span> <span m=''1828280''>Once</span>
  <span m=''1828400''>you</span> <span m=''1828510''>have</span> <span m=''1828650''>this</span>
  <span m=''1828740''>structure,</span> <span m=''1833250''>cut</span> <span m=''1833350''>along</span>
  <span m=''1833570''>the</span> <span m=''1833650''>cut</span> <span m=''1833860''>locus,</span>
  <span m=''1836970''>unfold</span> <span m=''1837690''>the</span> <span m=''1837770''>star</span>
  <span m=''1838746''>of</span> <span m=''1839560''>shortest</span> <span m=''1839920''>paths</span>
  <span m=''1842450''>from</span> <span m=''1842780''>x.</span> </p><p><span m=''1846770''>So</span>
  <span m=''1847060''>let''s</span> <span m=''1847270''>do</span> <span m=''1847400''>it</span>
  <span m=''1847500''>for</span> <span m=''1847580''>this</span> <span m=''1847750''>example.</span>
  <span m=''1849200''>It''s</span> <span m=''1849260''>the</span> <span m=''1849370''>same</span>
  <span m=''1849600''>example</span> <span m=''1849940''>on</span> <span m=''1850020''>the</span>
  <span m=''1850090''>left.</span> <span m=''1850860''>This</span> <span m=''1851080''>is</span>
  <span m=''1851220''>the</span> <span m=''1851290''>star</span> <span m=''1851590''>unfolding.</span>
  <span m=''1852150''>I''ve</span> <span m=''1852340''>just</span> <span m=''1852780''>splayed</span>
  <span m=''1853340''>out</span> <span m=''1853660''>everything,</span> <span m=''1855930''>so</span>
  <span m=''1856220''>at</span> <span m=''1856400''>the</span> <span m=''1856490''>boundary,</span>
  <span m=''1856890''>I''m</span> <span m=''1857000''>cutting</span> <span m=''1857410''>at</span>
  <span m=''1857570''>the</span> <span m=''1857850''>dashed</span> <span m=''1858180''>part.</span>
  <span m=''1858570''>That''s</span> <span m=''1858880''>the</span> <span m=''1859290''>cut</span>
  <span m=''1859480''>locus.</span> <span m=''1860820''>Ignore</span> <span m=''1861160''>these</span>
  <span m=''1861450''>little</span> <span m=''1861770''>dashed</span> <span m=''1862080''>lines.</span>
  <span m=''1862320''>Those</span> <span m=''1862500''>are</span> <span m=''1862580''>just</span>
  <span m=''1862810''>edges,</span> <span m=''1864470''>unfolded.</span> </p><p><span
  m=''1866280''>And</span> <span m=''1866860''>what''s</span> <span m=''1867140''>happening</span>
  <span m=''1867560''>is</span> <span m=''1867680''>that</span> <span m=''1867770''>all</span>
  <span m=''1867920''>the</span> <span m=''1868010''>shortest</span> <span m=''1868340''>paths</span>
  <span m=''1868650''>are</span> <span m=''1870370''>all</span> <span m=''1870490''>here.</span>
  <span m=''1872200''>If</span> <span m=''1872370''>I</span> <span m=''1872430''>look</span>
  <span m=''1872670''>at</span> <span m=''1872740''>any</span> <span m=''1872930''>shortest</span>
  <span m=''1873280''>path</span> <span m=''1873520''>from</span> <span m=''1873700''>x</span>
  <span m=''1874000''>on</span> <span m=''1874070''>the</span> <span m=''1874170''>left</span>
  <span m=''1874520''>diagram,</span> <span m=''1875490''>I</span> <span m=''1875600''>can</span>
  <span m=''1875780''>map</span> <span m=''1876100''>it</span> <span m=''1876730''>to</span>
  <span m=''1877120''>a</span> <span m=''1877510''>line</span> <span m=''1877970''>segment</span>
  <span m=''1878540''>starting</span> <span m=''1878980''>from</span> <span m=''1879200''>x.</span>
  <span m=''1880830''>x</span> <span m=''1881080''>was</span> <span m=''1881250''>a</span>
  <span m=''1881320''>flat</span> <span m=''1881630''>vertex.</span> <span m=''1882100''>It</span>
  <span m=''1882200''>has</span> <span m=''1882400''>360</span> <span m=''1882680''>degrees</span>
  <span m=''1882980''>of</span> <span m=''1883280''>material</span> <span m=''1883770''>around</span>
  <span m=''1884070''>it.</span> <span m=''1884450''>I</span> <span m=''1884530''>just</span>
  <span m=''1884700''>chose</span> <span m=''1884920''>it</span> <span m=''1885020''>to</span>
  <span m=''1885090''>be</span> <span m=''1885200''>somewhere</span> <span m=''1885480''>in</span>
  <span m=''1885540''>the</span> <span m=''1885610''>middle</span> <span m=''1885850''>somewhere.</span>
  <span m=''1886900''>Doesn''t</span> <span m=''1887160''>matter</span> <span m=''1887450''>other</span>
  <span m=''1887650''>than</span> <span m=''1887970''>that.</span> </p><p><span m=''1888590''>And</span>
  <span m=''1889180''>now</span> <span m=''1889820''>there''s</span> <span m=''1890050''>360</span>
  <span m=''1890590''>degrees of</span> <span m=''1890850''>material</span> <span
  m=''1891260''>on</span> <span m=''1891350''>the</span> <span m=''1891440''>flat</span>
  <span m=''1891680''>unfolding.</span> <span m=''1892100''>That''s</span> <span m=''1892310''>great.</span>
  <span m=''1893120''>And</span> <span m=''1893360''>you</span> <span m=''1893450''>pick</span>
  <span m=''1893660''>any</span> <span m=''1893850''>direction</span> <span m=''1894320''>here,</span>
  <span m=''1895130''>you</span> <span m=''1895340''>can</span> <span m=''1895520''>map</span>
  <span m=''1895860''>it</span> <span m=''1896030''>to</span> <span m=''1896140''>a</span>
  <span m=''1896200''>corresponding</span> <span m=''1896690''>direction</span> <span
  m=''1897120''>over</span> <span m=''1897290''>there</span> <span m=''1897620''>on</span>
  <span m=''1897710''>the</span> <span m=''1897800''>surface,</span> <span m=''1898970''>see</span>
  <span m=''1899410''>where</span> <span m=''1899720''>that</span> <span m=''1899950''>shortest</span>
  <span m=''1900310''>path</span> <span m=''1900560''>would</span> <span m=''1900780''>go</span>
  <span m=''1901080''>if</span> <span m=''1901190''>you</span> <span m=''1901280''>kept</span>
  <span m=''1901520''>going</span> <span m=''1901810''>until</span> <span m=''1902040''>you</span>
  <span m=''1902170''>were</span> <span m=''1902230''>no</span> <span m=''1902380''>longer</span>
  <span m=''1902630''>shortest.</span> <span m=''1903850''>When</span> <span m=''1903990''>you</span>
  <span m=''1904070''>stop being</span> <span m=''1904510''>shortest,</span> <span
  m=''1905510''>the</span> <span m=''1905960''>edge</span> <span m=''1906250''>of</span>
  <span m=''1906320''>that</span> <span m=''1906890''>place</span> <span m=''1907700''>is</span>
  <span m=''1908020''>the</span> <span m=''1908350''>ridge</span> <span m=''1908590''>tree,</span>
  <span m=''1909180''>and</span> <span m=''1909860''>that''s</span> <span m=''1910070''>where</span>
  <span m=''1910170''>you</span> <span m=''1910270''>cut.</span> <span m=''1912630''>You</span>
  <span m=''1912750''>stop</span> <span m=''1913080''>your</span> <span m=''1913200''>segment</span>
  <span m=''1913580''>there.</span> </p><p><span m=''1914720''>So</span> <span m=''1914850''>it''s</span>
  <span m=''1914940''>actually</span> <span m=''1915230''>pretty</span> <span m=''1915520''>obvious</span>
  <span m=''1915940''>this</span> <span m=''1916080''>thing</span> <span m=''1916230''>doesn''t</span>
  <span m=''1916500''>overlap</span> <span m=''1917000''>because</span> <span m=''1917620''>all</span>
  <span m=''1917850''>of</span> <span m=''1917930''>these</span> <span m=''1918020''>shortest</span>
  <span m=''1918330''>paths</span> <span m=''1918620''>are</span> <span m=''1918700''>going</span>
  <span m=''1918960''>in</span> <span m=''1919060''>different</span> <span m=''1919330''>directions</span>
  <span m=''1920310''>from</span> <span m=''1920500''>x.</span> <span m=''1921940''>What</span>
  <span m=''1922170''>you</span> <span m=''1922260''>have</span> <span m=''1922510''>is</span>
  <span m=''1922630''>what</span> <span m=''1922710''>we</span> <span m=''1922810''>call</span>
  <span m=''1923040''>a</span> <span m=''1923110''>star</span> <span m=''1923470''>shaped</span>
  <span m=''1923850''>polygon</span> <span m=''1924330''>around</span> <span m=''1924630''>x.</span>
  <span m=''1925450''>Every</span> <span m=''1925860''>point</span> <span m=''1926180''>on</span>
  <span m=''1926300''>the</span> <span m=''1926370''>surface</span> <span m=''1926740''>is</span>
  <span m=''1926870''>visible</span> <span m=''1927230''>from</span> <span m=''1927410''>x</span>
  <span m=''1928060''>because</span> <span m=''1928240''>we</span> <span m=''1928350''>just</span>
  <span m=''1928470''>sort</span> <span m=''1928620''>of</span> <span m=''1928720''>unrolled</span>
  <span m=''1929150''>it</span> <span m=''1929270''>to</span> <span m=''1929360''>be</span>
  <span m=''1929610''>right</span> <span m=''1929860''>there.</span> <span m=''1932090''>That''s</span>
  <span m=''1932180''>the</span> <span m=''1932260''>source</span> <span m=''1932540''>unfolding.</span>
  <span m=''1934550''>It''s</span> <span m=''1934650''>a</span> <span m=''1934700''>little</span>
  <span m=''1934860''>hard</span> <span m=''1935030''>to</span> <span m=''1935090''>see</span>
  <span m=''1935290''>the</span> <span m=''1935400''>3D</span> <span m=''1935760''>diagrams,</span>
  <span m=''1936350''>but</span> <span m=''1936720''>it''s</span> <span m=''1936890''>actually</span>
  <span m=''1937220''>really</span> <span m=''1939110''>easy</span> <span m=''1939500''>once</span>
  <span m=''1939700''>you</span> <span m=''1939790''>draw</span> <span m=''1940080''>those</span>
  <span m=''1940480''>shortest</span> <span m=''1940830''>paths.</span> </p><p><span
  m=''1946680''>So</span> <span m=''1946840''>the</span> <span m=''1946940''>source</span>
  <span m=''1947280''>unfolding</span> <span m=''1948350''>is</span> <span m=''1948550''>star</span>
  <span m=''1948880''>shaped.</span> <span m=''1950060''>We</span> <span m=''1950250''>have</span>
  <span m=''1950420''>another</span> <span m=''1950750''>unfolding</span> <span m=''1951170''>called</span>
  <span m=''1951340''>the</span> <span m=''1951410''>star</span> <span m=''1951740''>unfolding,</span>
  <span m=''1952150''>which</span> <span m=''1952310''>is</span> <span m=''1952430''>not</span>
  <span m=''1952730''>star</span> <span m=''1952960''>shaped.</span> <span m=''1953820''>Very</span>
  <span m=''1953980''>confusing.</span> <span m=''1957230''>I</span> <span m=''1957320''>mean,</span>
  <span m=''1957760''>what</span> <span m=''1957900''>you</span> <span m=''1957990''>call</span>
  <span m=''1958320''>one</span> <span m=''1959380''>doesn''t</span> <span m=''1959560''>matter</span>
  <span m=''1959790''>too</span> <span m=''1959960''>much.</span> <span m=''1960710''>This</span>
  <span m=''1960940''>unfolding</span> <span m=''1961340''>was</span> <span m=''1961470''>mentioned</span>
  <span m=''1962000''>in</span> <span m=''1962100''>1948</span> <span m=''1964120''>by</span>
  <span m=''1964260''>Alexandrov,</span> <span m=''1964930''>who</span> <span m=''1965180''>we''ll</span>
  <span m=''1965330''>be</span> <span m=''1965450''>hearing</span> <span m=''1965740''>about</span>
  <span m=''1965970''>more</span> <span m=''1966280''>in</span> <span m=''1966360''>the</span>
  <span m=''1966410''>future,</span> <span m=''1967400''>but</span> <span m=''1969100''>wasn''t</span>
  <span m=''1969270''>improved</span> <span m=''1969690''>to</span> <span m=''1970050''>non-overlap</span>
  <span m=''1970710''>until</span> <span m=''1971360''>''92.</span> <span m=''1972770''>So</span>
  <span m=''1972950''>this</span> <span m=''1973140''>one</span> <span m=''1973290''>is</span>
  <span m=''1973480''>much</span> <span m=''1973760''>less</span> <span m=''1974010''>obvious</span>
  <span m=''1974380''>that</span> <span m=''1974500''>it</span> <span m=''1974950''>doesn''t</span>
  <span m=''1975180''>overlap,</span> <span m=''1975570''>and</span> <span m=''1975650''>I''m</span>
  <span m=''1975730''>not</span> <span m=''1975890''>going</span> <span m=''1975980''>to</span>
  <span m=''1976040''>prove</span> <span m=''1976240''>it</span> <span m=''1976300''>here.</span>
  </p><p><span m=''1977560''>But</span> <span m=''1977690''>it</span> <span m=''1977760''>goes</span>
  <span m=''1977930''>back</span> <span m=''1978130''>to</span> <span m=''1978230''>this</span>
  <span m=''1978390''>idea</span> <span m=''1978690''>of</span> <span m=''1978760''>star.</span>
  <span m=''1980470''>Say,</span> <span m=''1980660''>OK,</span> <span m=''1981050''>this
  cut</span> <span m=''1981220''>locus</span> <span m=''1981530''>is</span> <span
  m=''1981630''>nice,</span> <span m=''1982000''>but</span> <span m=''1982660''>let''s</span>
  <span m=''1982950''>focus</span> <span m=''1983330''>on</span> <span m=''1983430''>the</span>
  <span m=''1983510''>star of</span> <span m=''1983880''>shortest</span> <span m=''1984230''>paths</span>
  <span m=''1985050''>from</span> <span m=''1985250''>one</span> <span m=''1985410''>point</span>
  <span m=''1985720''>to</span> <span m=''1985790''>all</span> <span m=''1985980''>the</span>
  <span m=''1986080''>other</span> <span m=''1986240''>vertices.</span> <span m=''1988750''>Instead</span>
  <span m=''1989100''>of</span> <span m=''1989290''>keeping</span> <span m=''1989750''>those</span>
  <span m=''1990040''>paths</span> <span m=''1990690''>as</span> <span m=''1992770''>the</span>
  <span m=''1992870''>things</span> <span m=''1993140''>that</span> <span m=''1993210''>you</span>
  <span m=''1993380''>unroll,</span> <span m=''1994600''>what</span> <span m=''1994770''>if</span>
  <span m=''1994900''>we</span> <span m=''1995010''>cut</span> <span m=''1995230''>along</span>
  <span m=''1995530''>them?</span> <span m=''1997700''>It''s</span> <span m=''1997830''>another</span>
  <span m=''1998360''>natural</span> <span m=''1998720''>thing</span> <span m=''1998910''>to</span>
  <span m=''1998990''>try</span> <span m=''1999360''>and</span> <span m=''1999470''>it</span>
  <span m=''1999570''>turns</span> <span m=''1999800''>out</span> <span m=''1999920''>to</span>
  <span m=''2000010''>work.</span> </p><p><span m=''2003380''>So</span> <span m=''2003520''>here,</span>
  <span m=''2003710''>we</span> <span m=''2003810''>cut</span> <span m=''2004000''>along</span>
  <span m=''2005820''>the</span> <span m=''2005910''>star.</span> <span m=''2007650''>We''ve</span>
  <span m=''2007820''>already</span> <span m=''2008220''>proved</span> <span m=''2009570''>this</span>
  <span m=''2009760''>result,</span> <span m=''2010930''>every</span> <span m=''2011200''>convex</span>
  <span m=''2011560''>polyhedron</span> <span m=''2012080''>is</span> <span m=''2012190''>generally</span>
  <span m=''2012520''>unfoldable.</span> <span m=''2013040''>Just</span> <span m=''2013230''>with</span>
  <span m=''2013310''>that</span> <span m=''2013880''>picture,</span> <span m=''2014350''>it''s</span>
  <span m=''2014600''>very</span> <span m=''2014820''>easy.</span> <span m=''2015590''>But</span>
  <span m=''2015770''>hey,</span> <span m=''2015950''>it''s</span> <span m=''2016110''>fun</span>
  <span m=''2016280''>to</span> <span m=''2016330''>have</span> <span m=''2016510''>more.</span>
  <span m=''2017990''>And</span> <span m=''2018270''>this</span> <span m=''2018450''>is</span>
  <span m=''2018590''>what</span> <span m=''2018840''>the</span> <span m=''2018930''>star</span>
  <span m=''2019190''>unfolding</span> <span m=''2019570''>looks</span> <span m=''2019770''>like</span>
  <span m=''2019940''>for</span> <span m=''2020060''>the</span> <span m=''2020190''>same</span>
  <span m=''2020480''>example.</span> </p><p><span m=''2021990''>This</span> <span
  m=''2022200''>is</span> <span m=''2022340''>a</span> <span m=''2022410''>little</span>
  <span m=''2022700''>less</span> <span m=''2022990''>obvious,</span> <span m=''2027080''>but</span>
  <span m=''2027920''>if</span> <span m=''2028040''>you</span> <span m=''2028130''>think</span>
  <span m=''2028310''>about</span> <span m=''2028580''>it,</span> <span m=''2029290''>the</span>
  <span m=''2029420''>star,</span> <span m=''2029850''>the</span> <span m=''2029930''>set</span>
  <span m=''2030100''>of</span> <span m=''2030170''>all</span> <span m=''2030280''>shortest</span>
  <span m=''2030450''>paths to</span> <span m=''2030850''>all</span> <span m=''2030970''>the</span>
  <span m=''2031030''>vertices,</span> <span m=''2032130''>is</span> <span m=''2032360''>a</span>
  <span m=''2032430''>spanning</span> <span m=''2032850''>tree.</span> <span m=''2033500''>It</span>
  <span m=''2033570''>hits</span> <span m=''2033780''>all</span> <span m=''2033890''>the</span>
  <span m=''2033950''>vertices</span> <span m=''2034440''>because</span> <span m=''2034740''>we</span>
  <span m=''2034950''>told</span> <span m=''2035330''>it</span> <span m=''2035430''>to,</span>
  <span m=''2036280''>and</span> <span m=''2037970''>it''s</span> <span m=''2038450''>a</span>
  <span m=''2038530''>tree</span> <span m=''2039190''>because</span> <span m=''2039450''>it''s</span>
  <span m=''2039670''>just</span> <span m=''2040060''>all</span> <span m=''2040440''>these</span>
  <span m=''2040650''>edges</span> <span m=''2040960''>coming</span> <span m=''2041220''>together</span>
  <span m=''2041550''>at</span> <span m=''2041620''>a</span> <span m=''2041670''>point.</span>
  <span m=''2042960''>So</span> <span m=''2043060''>it''s</span> <span m=''2043180''>a</span>
  <span m=''2043230''>natural</span> <span m=''2043560''>cutting</span> <span m=''2043850''>also.</span>
  <span m=''2045320''>And</span> <span m=''2045720''>magically</span> <span m=''2046260''>it</span>
  <span m=''2046350''>works.</span> <span m=''2046850''>How</span> <span m=''2047160''>it</span>
  <span m=''2047250''>works</span> <span m=''2047540''>is</span> <span m=''2047720''>a</span>
  <span m=''2047790''>little</span> <span m=''2048120''>less</span> <span m=''2048360''>obvious.</span>
  </p><p><span m=''2050260''>You</span> <span m=''2050370''>see</span> <span m=''2050679''>here</span>
  <span m=''2050830''>the</span> <span m=''2050969''>ridge</span> <span m=''2051324''>tree</span>
  <span m=''2052020''>drawn</span> <span m=''2052440''>on</span> <span m=''2052580''>the</span>
  <span m=''2052699''>unfolding,</span> <span m=''2054650''>and</span> <span m=''2054730''>you</span>
  <span m=''2054830''>can</span> <span m=''2054960''>see</span> <span m=''2055170''>all</span>
  <span m=''2055290''>the</span> <span m=''2055380''>parts</span> <span m=''2055810''>and</span>
  <span m=''2055870''>map</span> <span m=''2056400''>the</span> <span m=''2056570''>letter</span>
  <span m=''2057110''>E,</span> <span m=''2057310''>this</span> <span m=''2057480''>is</span>
  <span m=''2057590''>the</span> <span m=''2057690''>bottom</span> <span m=''2058070''>square,</span>
  <span m=''2059340''>and</span> <span m=''2059489''>stays</span> <span m=''2059790''>connected.</span>
  <span m=''2060409''>It''s</span> <span m=''2060540''>just</span> <span m=''2060730''>like</span>
  <span m=''2060889''>you</span> <span m=''2061020''>reattach</span> <span m=''2061520''>everything</span>
  <span m=''2062510''>around</span> <span m=''2063110''>the</span> <span m=''2063219''>ridge</span>
  <span m=''2063539''>tree</span> <span m=''2065290''>and</span> <span m=''2065710''>it</span>
  <span m=''2065880''>doesn''t</span> <span m=''2066150''>overlap.</span> <span m=''2070710''>It''s</span>
  <span m=''2071090''>quite</span> <span m=''2071520''>difficult,</span> <span m=''2072010''>I</span>
  <span m=''2072110''>think,</span> <span m=''2072170''>to</span> <span m=''2072270''>give</span>
  <span m=''2072460''>intuition</span> <span m=''2072980''>why</span> <span m=''2073170''>this</span>
  <span m=''2073639''>doesn''t</span> <span m=''2073889''>overlap,</span> <span m=''2075292''>but</span>
  <span m=''2076214''>it</span> <span m=''2076679''>doesn''t.</span> <span m=''2083350''>I''ll</span>
  <span m=''2083610''>wave</span> <span m=''2083750''>my</span> <span m=''2083920''>hands</span>
  <span m=''2084120''>at</span> <span m=''2084210''>some</span> <span m=''2084409''>point</span>
  <span m=''2084600''>when</span> <span m=''2084719''>we</span> <span m=''2084810''>have</span>
  <span m=''2084980''>the</span> <span m=''2085060''>necessary</span> <span m=''2086150''>tools</span>
  <span m=''2086600''>to</span> <span m=''2086710''>prove</span> <span m=''2086980''>it,</span>
  <span m=''2087690''>I</span> <span m=''2087810''>can</span> <span m=''2087969''>mention</span>
  <span m=''2088270''>how</span> <span m=''2088480''>it''s</span> <span m=''2088620''>done.</span>
  <span m=''2089600''>But</span> <span m=''2089730''>we</span> <span m=''2089810''>don''t</span>
  <span m=''2089969''>have</span> <span m=''2090130''>them</span> <span m=''2090250''>yet.</span>
  <span m=''2090699''>We''ll</span> <span m=''2090730''>get</span> <span m=''2090909''>them</span>
  <span m=''2091090''>in</span> <span m=''2091260''>a</span> <span m=''2091389''>couple</span>
  <span m=''2091670''>of</span> <span m=''2091750''>lectures,</span> <span m=''2092210''>I</span>
  <span m=''2092270''>think.</span> </p><p><span m=''2096150''>These</span> <span
  m=''2096489''>results</span> <span m=''2096860''>can</span> <span m=''2097000''>be</span>
  <span m=''2097090''>extended</span> <span m=''2097590''>also</span> <span m=''2100700''>in</span>
  <span m=''2101130''>various</span> <span m=''2101460''>directions.</span> <span
  m=''2102260''>Let</span> <span m=''2102370''>me</span> <span m=''2102520''>tell</span>
  <span m=''2102710''>you</span> <span m=''2102810''>briefly</span> <span m=''2103220''>about</span>
  <span m=''2104350''>some</span> <span m=''2104570''>extensions.</span> <span m=''2110850''>For</span>
  <span m=''2111020''>a</span> <span m=''2111070''>long</span> <span m=''2111410''>time,</span>
  <span m=''2112180''>these</span> <span m=''2112430''>were</span> <span m=''2112590''>the</span>
  <span m=''2112740''>two</span> <span m=''2113050''>ways</span> <span m=''2113370''>to</span>
  <span m=''2113470''>solve</span> <span m=''2113720''>that</span> <span m=''2113890''>problem</span>
  <span m=''2114310''>and</span> <span m=''2114370''>that</span> <span m=''2114520''>was</span>
  <span m=''2114630''>sort</span> <span m=''2114800''>of</span> <span m=''2114890''>it.</span>
  <span m=''2117910''>It</span> <span m=''2118070''>would</span> <span m=''2118130''>be</span>
  <span m=''2118250''>nice,</span> <span m=''2118510''>for</span> <span m=''2118590''>example,</span>
  <span m=''2118890''>to</span> <span m=''2118950''>have</span> <span m=''2119100''>some</span>
  <span m=''2119300''>general</span> <span m=''2119650''>family</span> <span m=''2119980''>of</span>
  <span m=''2120050''>unfoldings</span> <span m=''2120480''>that</span> <span m=''2120620''>includes</span>
  <span m=''2121050''>the</span> <span m=''2121140''>star</span> <span m=''2121360''>unfolding</span>
  <span m=''2121700''>and</span> <span m=''2121910''>the</span> <span m=''2121990''>source</span>
  <span m=''2122250''>unfolding</span> <span m=''2122710''>and there''s</span> <span
  m=''2122810''>something</span> <span m=''2123330''>in</span> <span m=''2123410''>the</span>
  <span m=''2123480''>middle,</span> <span m=''2124530''>but</span> <span m=''2124690''>we</span>
  <span m=''2124780''>don''t</span> <span m=''2125180''>necessarily</span> <span m=''2125650''>know</span>
  <span m=''2125770''>what</span> <span m=''2125870''>that</span> <span m=''2126010''>is.</span>
  <span m=''2126280''>Do you have a</span> <span m=''2126370''>question?</span> </p><p><span
  m=''2127732''>AUDIENCE: [INAUDIBLE]?</span> </p><p><span m=''2133450''>PROFESSOR:
  How</span> <span m=''2133680''>do</span> <span m=''2133740''>you</span> <span m=''2133870''>find</span>
  <span m=''2134110''>the</span> <span m=''2134190''>creases</span> <span m=''2134880''>is</span>
  <span m=''2134950''>your</span> <span m=''2135160''>question?</span> <span m=''2140140''>You</span>
  <span m=''2140230''>find</span> <span m=''2140450''>the</span> <span m=''2140520''>creases</span>
  <span m=''2140900''>because you know</span> <span m=''2141180''>for</span> <span
  m=''2141680''>every</span> <span m=''2141950''>point</span> <span m=''2142210''>here</span>
  <span m=''2142800''>where</span> <span m=''2143030''>it</span> <span m=''2143080''>was</span>
  <span m=''2143290''>on</span> <span m=''2143370''>the</span> <span m=''2143440''>surface,</span>
  <span m=''2144370''>and</span> <span m=''2144490''>if</span> <span m=''2144570''>it</span>
  <span m=''2144640''>was</span> <span m=''2144810''>on</span> <span m=''2144980''>an</span>
  <span m=''2145090''>edge,</span> <span m=''2145450''>then</span> <span m=''2145620''>it''s</span>
  <span m=''2145770''>a</span> <span m=''2145810''>crease</span> <span m=''2146040''>point.</span>
  <span m=''2147700''>That''s</span> <span m=''2147950''>the</span> <span m=''2148280''>easy</span>
  <span m=''2148480''>way</span> <span m=''2148610''>to</span> <span m=''2148710''>do</span>
  <span m=''2148830''>it.</span> <span m=''2151500''>I don''t</span> <span m=''2151620''>know
  if that''s a</span> <span m=''2151720''>satisfactory</span> <span m=''2152400''>answer,</span>
  <span m=''2152720''>but</span> <span m=''2153620''>it</span> <span m=''2154090''>can</span>
  <span m=''2154220''>be</span> <span m=''2154320''>done.</span> </p><p><span m=''2155061''>AUDIENCE:
  Does it</span> <span m=''2155512''>matter</span> <span m=''2155963''>where you</span>
  <span m=''2156414''>choose x</span> <span m=''2156865''>to be?</span> </p><p><span
  m=''2157770''>PROFESSOR: Does it</span> <span m=''2158050''>matter</span> <span
  m=''2158930''>where</span> <span m=''2159180''>you</span> <span m=''2159330''>choose</span>
  <span m=''2159600''>x</span> <span m=''2159830''>to</span> <span m=''2159930''>be?</span>
  <span m=''2160660''>It</span> <span m=''2160870''>will</span> <span m=''2161020''>change</span>
  <span m=''2161360''>the</span> <span m=''2161480''>unfolding.</span> <span m=''2162560''>It</span>
  <span m=''2162670''>will</span> <span m=''2162800''>never</span> <span m=''2163110''>overlap,</span>
  <span m=''2164290''>but</span> <span m=''2165390''>in</span> <span m=''2165480''>that</span>
  <span m=''2165640''>sense</span> <span m=''2166840''>there''s</span> <span m=''2166960''>a</span>
  <span m=''2167000''>whole</span> <span m=''2167130''>family</span> <span m=''2167480''>of</span>
  <span m=''2167540''>star</span> <span m=''2167730''>unfoldings,</span> <span m=''2168160''>depending
  on</span> <span m=''2168570''>where</span> <span m=''2168700''>you</span> <span
  m=''2168830''>move</span> <span m=''2168970''>x.</span> <span m=''2169270''>There''s</span>
  <span m=''2169400''>a</span> <span m=''2169440''>whole</span> <span m=''2169600''>family</span>
  <span m=''2170070''>of</span> <span m=''2170140''>source</span> <span m=''2170420''>unfoldings</span>
  <span m=''2170800''>depending on</span> <span m=''2171170''>where you move</span>
  <span m=''2171530''>x.</span> </p><p><span m=''2171920''>AUDIENCE: Does</span> <span
  m=''2172397''>it make</span> <span m=''2172874''>it more</span> <span m=''2173351''>efficient,</span>
  <span m=''2173828''>any</span> <span m=''2174305''>choice?</span> </p><p><span m=''2175740''>PROFESSOR:
  I</span> <span m=''2175850''>mean,</span> <span m=''2176070''>some</span> <span
  m=''2176360''>of</span> <span m=''2176460''>the</span> <span m=''2176860''>unfoldings</span>
  <span m=''2178340''>might</span> <span m=''2178570''>have</span> <span m=''2178860''>more</span>
  <span m=''2179220''>cuts,</span> <span m=''2179960''>some</span> <span m=''2180240''>might</span>
  <span m=''2180430''>have</span> <span m=''2180610''>less</span> <span m=''2180870''>cuts.</span>
  <span m=''2181330''>You''re</span> <span m=''2181480''>going</span> <span m=''2181590''>to</span>
  <span m=''2181650''>get</span> <span m=''2181800''>more</span> <span m=''2182050''>cuts</span>
  <span m=''2182410''>when</span> <span m=''2182550''>you</span> <span m=''2182660''>have--</span>
  <span m=''2183610''>depends</span> <span m=''2183900''>how</span> <span m=''2183950''>you</span>
  <span m=''2184100''>count.</span> <span m=''2184760''>In</span> <span m=''2184990''>some</span>
  <span m=''2185150''>sense,</span> <span m=''2185390''>there''s</span> <span m=''2185560''>only</span>
  <span m=''2185840''>n</span> <span m=''2186080''>cuts,</span> <span m=''2187930''>n</span>
  <span m=''2188150''>shortest</span> <span m=''2188520''>paths.</span> <span m=''2189760''>But</span>
  <span m=''2190350''>a</span> <span m=''2190470''>shortest</span> <span m=''2190820''>path</span>
  <span m=''2191860''>might</span> <span m=''2192370''>cut</span> <span m=''2192650''>over</span>
  <span m=''2193030''>many</span> <span m=''2193460''>faces</span> <span m=''2193960''>or</span>
  <span m=''2194070''>it</span> <span m=''2194130''>might</span> <span m=''2194300''>just</span>
  <span m=''2194500''>cut</span> <span m=''2194650''>over</span> <span m=''2194880''>one</span>
  <span m=''2195070''>face.</span> <span m=''2197140''>Depends</span> <span m=''2197370''>where</span>
  <span m=''2197510''>x</span> <span m=''2197825''>is.</span> <span m=''2198140''>If</span>
  <span m=''2198260''>you</span> <span m=''2198350''>choose</span> <span m=''2198580''>x</span>
  <span m=''2198770''>to</span> <span m=''2198860''>be</span> <span m=''2198950''>in</span>
  <span m=''2199040''>a</span> <span m=''2199080''>nice</span> <span m=''2199300''>place,</span>
  <span m=''2199530''>maybe</span> <span m=''2199840''>you</span> <span m=''2199950''>could</span>
  <span m=''2200070''>get</span> <span m=''2200180''>away</span> <span m=''2200320''>with</span>
  <span m=''2200460''>fewer</span> <span m=''2200670''>cuts</span> <span m=''2201450''>and</span>
  <span m=''2201680''>have</span> <span m=''2201900''>to</span> <span m=''2202010''>do</span>
  <span m=''2202160''>less</span> <span m=''2203060''>welding,</span> <span m=''2203900''>but</span>
  <span m=''2205210''>there''s</span> <span m=''2205410''>no</span> <span m=''2205540''>theory</span>
  <span m=''2205810''>about</span> <span m=''2206040''>that.</span> <span m=''2206540''>More</span>
  <span m=''2206670''>questions.</span> </p><p><span m=''2208222''>AUDIENCE: So</span>
  <span m=''2208688''>it doesn''t</span> <span m=''2209154''>matter</span> <span m=''2209620''>where</span>
  <span m=''2210086''>you put</span> <span m=''2210552''>x.</span> <span m=''2211020''>If
  it</span> <span m=''2211310''>works</span> <span m=''2211767''>at one</span> <span
  m=''2212224''>spot,</span> <span m=''2212681''>it basically</span> <span m=''2213138''>works</span>
  <span m=''2213595''>at every</span> <span m=''2214052''>spot.</span> <span m=''2214966''>[INAUDIBLE]?</span>
  </p><p><span m=''2216340''>PROFESSOR: For</span> <span m=''2216500''>convex</span>
  <span m=''2216970''>polyhedra,</span> <span m=''2217430''>it works</span> <span
  m=''2217730''>no</span> <span m=''2217820''>matter</span> <span m=''2218190''>where</span>
  <span m=''2218360''>you</span> <span m=''2218480''>put</span> <span m=''2218670''>x.</span>
  <span m=''2219150''>For</span> <span m=''2219270''>non-convex</span> <span m=''2219840''>polyhedra,</span>
  <span m=''2221000''>some</span> <span m=''2221260''>x''s</span> <span m=''2221520''>might</span>
  <span m=''2221700''>work,</span> <span m=''2221910''>some</span> <span m=''2222180''>might</span>
  <span m=''2222430''>not.</span> <span m=''2226330''>Here,</span> <span m=''2226830''>let</span>
  <span m=''2226960''>me</span> <span m=''2227060''>show</span> <span m=''2227260''>you.</span>
  <span m=''2228970''>Here''s</span> <span m=''2229170''>more</span> <span m=''2229380''>star</span>
  <span m=''2229630''>unfoldings.</span> <span m=''2230040''>Cool.</span> <span m=''2231030''>They''re</span>
  <span m=''2231270''>really</span> <span m=''2231600''>crazy</span> <span m=''2232050''>looking</span>
  <span m=''2232770''>and</span> <span m=''2233020''>not</span> <span m=''2233330''>really</span>
  <span m=''2233570''>star</span> <span m=''2233820''>shaped.</span> <span m=''2235320''>There</span>
  <span m=''2235600''>isn''t</span> <span m=''2236100''>one</span> <span m=''2236520''>point</span>
  <span m=''2236880''>that</span> <span m=''2236970''>can</span> <span m=''2237130''>see</span>
  <span m=''2237370''>everything.</span> <span m=''2238410''>They</span> <span m=''2238520''>look</span>
  <span m=''2238710''>kind</span> <span m=''2238890''>of</span> <span m=''2238970''>spiky</span>
  <span m=''2239420''>like</span> <span m=''2239600''>a</span> <span m=''2239660''>star,</span>
  <span m=''2240030''>but</span> <span m=''2241010''>it''s</span> <span m=''2241100''>quite</span>
  <span m=''2241270''>different.</span> <span m=''2241620''>These</span> <span m=''2241670''>are</span>
  <span m=''2241770''>random</span> <span m=''2243010''>points</span> <span m=''2243270''>on</span>
  <span m=''2243340''>a</span> <span m=''2243400''>sphere,</span> <span m=''2243790''>like</span>
  <span m=''2243970''>take</span> <span m=''2244440''>42</span> <span m=''2244890''>random</span>
  <span m=''2245110''>points</span> <span m=''2245350''>on a</span> <span m=''2245480''>sphere,</span>
  <span m=''2245760''>take</span> <span m=''2245930''>the</span> <span m=''2246000''>convex</span>
  <span m=''2246380''>hull,</span> <span m=''2246820''>then</span> <span m=''2246970''>take</span>
  <span m=''2247140''>a</span> <span m=''2247200''>star</span> <span m=''2247390''>unfolding.</span>
  </p><p><span m=''2250620''>Here''s</span> <span m=''2250880''>an</span> <span m=''2250920''>example</span>
  <span m=''2251280''>with</span> <span m=''2252480''>a</span> <span m=''2252540''>non-convex</span>
  <span m=''2253060''>polyhedron.</span> <span m=''2255060''>So</span> <span m=''2255270''>one</span>
  <span m=''2255470''>thing</span> <span m=''2255640''>we</span> <span m=''2255890''>hoped</span>
  <span m=''2256350''>for</span> <span m=''2256650''>for a</span> <span m=''2256950''>little</span>
  <span m=''2257230''>while</span> <span m=''2258040''>briefly</span> <span m=''2259170''>was</span>
  <span m=''2259440''>that if</span> <span m=''2259540''>you</span> <span m=''2259700''>only</span>
  <span m=''2259920''>had</span> <span m=''2260220''>one</span> <span m=''2260510''>vertex</span>
  <span m=''2260910''>of</span> <span m=''2261030''>negative</span> <span m=''2261370''>curvature,</span>
  <span m=''2261940''>which</span> <span m=''2262130''>is</span> <span m=''2262230''>this</span>
  <span m=''2262430''>one,</span> <span m=''2264060''>maybe</span> <span m=''2264480''>if</span>
  <span m=''2264590''>you</span> <span m=''2264740''>choose</span> <span m=''2265060''>x</span>
  <span m=''2265310''>to</span> <span m=''2265420''>be</span> <span m=''2265620''>right</span>
  <span m=''2265930''>there</span> <span m=''2266780''>and</span> <span m=''2266920''>did</span>
  <span m=''2267060''>the</span> <span m=''2267130''>star</span> <span m=''2267450''>unfolding,</span>
  <span m=''2267860''>because</span> <span m=''2268010''>that</span> <span m=''2268240''>cuts</span>
  <span m=''2268710''>x</span> <span m=''2268970''>into</span> <span m=''2269180''>lots</span>
  <span m=''2269520''>of</span> <span m=''2269740''>little</span> <span m=''2270110''>tiny</span>
  <span m=''2270400''>pieces,</span> <span m=''2271610''>then</span> <span m=''2271860''>maybe
  it</span> <span m=''2272140''>would</span> <span m=''2272290''>unfold</span> <span
  m=''2272690''>about</span> <span m=''2272920''>overlap,</span> <span m=''2273620''>but</span>
  <span m=''2274210''>it</span> <span m=''2274250''>doesn''t</span> <span m=''2274460''>work.</span>
  <span m=''2275710''>We</span> <span m=''2275810''>were</span> <span m=''2276450''>destroyed.</span>
  </p><p><span m=''2279890''>In</span> <span m=''2279940''>fact,</span> <span m=''2280210''>you</span>
  <span m=''2280300''>can</span> <span m=''2280440''>show</span> <span m=''2280610''>neither</span>
  <span m=''2280960''>of</span> <span m=''2281010''>them</span> <span m=''2281190''>will</span>
  <span m=''2281340''>work</span> <span m=''2281670''>in</span> <span m=''2281850''>general</span>
  <span m=''2282330''>for</span> <span m=''2282560''>a</span> <span m=''2282590''>non-convex</span>
  <span m=''2283160''>polyhedra,</span> <span m=''2283700''>so</span> <span m=''2283850''>there''s</span>
  <span m=''2284030''>no</span> <span m=''2284180''>hope</span> <span m=''2284380''>of</span>
  <span m=''2284460''>solving</span> <span m=''2284840''>this</span> <span m=''2285040''>problem</span>
  <span m=''2286020''>with</span> <span m=''2286150''>these</span> <span m=''2286330''>techniques,</span>
  <span m=''2288730''>at</span> <span m=''2289160''>least</span> <span m=''2289340''>with</span>
  <span m=''2289440''>these</span> <span m=''2289720''>exact</span> <span m=''2290090''>algorithms.</span>
  <span m=''2298550''>You</span> <span m=''2298700''>might</span> <span m=''2298890''>get</span>
  <span m=''2299040''>lucky,</span> <span m=''2299580''>but</span> <span m=''2299700''>most
  of</span> <span m=''2299950''>the</span> <span m=''2300060''>time,</span> <span
  m=''2300500''>I</span> <span m=''2300970''>think</span> <span m=''2301150''>they</span>
  <span m=''2301240''>won''t</span> <span m=''2301390''>work.</span> </p><p><span
  m=''2310690''>Currently,</span> <span m=''2311020''>x</span> <span m=''2311210''>is</span>
  <span m=''2311310''>a</span> <span m=''2311390''>point.</span> <span m=''2312410''>You</span>
  <span m=''2312550''>can</span> <span m=''2312670''>actually</span> <span m=''2313020''>let</span>
  <span m=''2313200''>x</span> <span m=''2313490''>be--</span> <span m=''2316340''>I</span>
  <span m=''2316530''>guess</span> <span m=''2316770''>I''m</span> <span m=''2316860''>not</span>
  <span m=''2317020''>going</span> <span m=''2317110''>to</span> <span m=''2317230''>be
  safe--</span> <span m=''2317620''>I''m</span> <span m=''2317780''>going</span> <span
  m=''2317870''>to</span> <span m=''2317940''>call it</span> <span m=''2318410''>a</span>
  <span m=''2318500''>geodesic</span> <span m=''2318940''>path.</span> <span m=''2319750''>There''s</span>
  <span m=''2319930''>some</span> <span m=''2320100''>restrictions</span> <span m=''2321960''>on</span>
  <span m=''2322290''>when</span> <span m=''2322450''>this</span> <span m=''2322620''>is</span>
  <span m=''2322720''>allowed,</span> <span m=''2323370''>but</span> <span m=''2323550''>the</span>
  <span m=''2323660''>idea</span> <span m=''2323900''>is</span> <span m=''2323980''>you</span>
  <span m=''2324330''>have</span> <span m=''2324580''>your</span> <span m=''2324710''>surface,</span>
  <span m=''2325930''>you</span> <span m=''2326080''>take</span> <span m=''2326320''>some</span>
  <span m=''2327360''>straight</span> <span m=''2327720''>path</span> <span m=''2328410''>on</span>
  <span m=''2328610''>the</span> <span m=''2328700''>surface,</span> <span m=''2329250''>and</span>
  <span m=''2329400''>then</span> <span m=''2329490''>you</span> <span m=''2329580''>take</span>
  <span m=''2329760''>shortest</span> <span m=''2329920''>paths</span> <span m=''2330330''>from</span>
  <span m=''2330470''>there.</span> <span m=''2334080''>And</span> <span m=''2334180''>if</span>
  <span m=''2334250''>you</span> <span m=''2334290''>just</span> <span m=''2334440''>think</span>
  <span m=''2334580''>about</span> <span m=''2334770''>the</span> <span m=''2337320''>source</span>
  <span m=''2337670''>unfolding</span> <span m=''2338550''>where</span> <span m=''2338700''>you</span>
  <span m=''2338820''>keep</span> <span m=''2339070''>x</span> <span m=''2339350''>intact</span>
  <span m=''2340750''>and</span> <span m=''2341310''>unfold</span> <span m=''2341770''>from</span>
  <span m=''2341930''>there,</span> <span m=''2342740''>the</span> <span m=''2342850''>picture</span>
  <span m=''2343120''>is</span> <span m=''2343210''>going</span> <span m=''2343330''>to</span>
  <span m=''2343410''>look</span> <span m=''2343540''>like,</span> <span m=''2343720''>well,</span>
  <span m=''2343850''>you</span> <span m=''2343930''>have</span> <span m=''2344160''>this</span>
  <span m=''2344240''>straight</span> <span m=''2344560''>line</span> <span m=''2344840''>when</span>
  <span m=''2344940''>you</span> <span m=''2345050''>unfold</span> <span m=''2345410''>that</span>
  <span m=''2345610''>thing,</span> <span m=''2346350''>and</span> <span m=''2346460''>then</span>
  <span m=''2346580''>you</span> <span m=''2346660''>have</span> <span m=''2346860''>this</span>
  <span m=''2347310''>nice</span> <span m=''2347590''>star of</span> <span m=''2347980''>stuff</span>
  <span m=''2348290''>around</span> <span m=''2348610''>it.</span> <span m=''2350560''>And</span>
  <span m=''2350810''>under</span> <span m=''2351010''>some</span> <span m=''2351180''>simple</span>
  <span m=''2351500''>conditions,</span> <span m=''2354050''>that</span> <span m=''2354270''>will</span>
  <span m=''2354450''>work</span> <span m=''2354710''>without</span> <span m=''2354960''>overlap.</span>
  </p><p><span m=''2356430''>What''s</span> <span m=''2356700''>more</span> <span
  m=''2356920''>impressive</span> <span m=''2357360''>is that</span> <span m=''2357710''>the</span>
  <span m=''2357810''>star</span> <span m=''2358120''>unfolding</span> <span m=''2358530''>works</span>
  <span m=''2359480''>from</span> <span m=''2359980''>a</span> <span m=''2360070''>source</span>
  <span m=''2360480''>like</span> <span m=''2360680''>that.</span> <span m=''2361310''>Again,</span>
  <span m=''2361520''>there</span> <span m=''2361620''>are</span> <span m=''2361670''>some</span>
  <span m=''2361850''>restrictions</span> <span m=''2362400''>on</span> <span m=''2362560''>x</span>
  <span m=''2362850''>that</span> <span m=''2362980''>I''m</span> <span m=''2363050''>not</span>
  <span m=''2363230''>going</span> <span m=''2363340''>to</span> <span m=''2363430''>define</span>
  <span m=''2363780''>here,</span> <span m=''2364520''>but</span> <span m=''2364570''>it</span>
  <span m=''2364640''>can</span> <span m=''2364780''>be</span> <span m=''2364880''>done.</span>
  <span m=''2365040''>These</span> <span m=''2365190''>are</span> <span m=''2365260''>two</span>
  <span m=''2365420''>very</span> <span m=''2365640''>recent</span> <span m=''2365920''>papers</span>
  <span m=''2366340''>by</span> <span m=''2367600''>O''Rourke</span> <span m=''2368330''>and</span>
  <span m=''2368770''>Itoh</span> <span m=''2369120''>and</span> <span m=''2369280''>Vilku</span>
  <span m=''2371450''>from the</span> <span m=''2371710''>last</span> <span m=''2371950''>two</span>
  <span m=''2372060''>years.</span> <span m=''2373280''>So</span> <span m=''2373450''>that''s</span>
  <span m=''2373580''>exciting.</span> <span m=''2374000''>We</span> <span m=''2374110''>now</span>
  <span m=''2374250''>have</span> <span m=''2374420''>four</span> <span m=''2375310''>general</span>
  <span m=''2375690''>methods</span> <span m=''2376100''>for</span> <span m=''2376270''>unfolding</span>
  <span m=''2376990''>convex</span> <span m=''2377250''>polyhedra.</span> <span m=''2378130''>Again,</span>
  <span m=''2378240''>these</span> <span m=''2378390''>are</span> <span m=''2378450''>big</span>
  <span m=''2378630''>families.</span> <span m=''2379060''>You</span> <span m=''2379170''>can</span>
  <span m=''2379340''>choose</span> <span m=''2379550''>any</span> <span m=''2379740''>geodesic</span>
  <span m=''2380200''>path.</span> <span m=''2380450''>Maybe</span> <span m=''2380680''>some
  are</span> <span m=''2380960''>nicer</span> <span m=''2381280''>than</span> <span
  m=''2381450''>others.</span> </p><p><span m=''2385390''>You</span> <span m=''2385580''>can</span>
  <span m=''2385790''>do</span> <span m=''2386240''>higher</span> <span m=''2386470''>dimensions.</span>
  <span m=''2395275''>Star</span> <span m=''2395560''>unfolding</span> <span m=''2396240''>doesn''t</span>
  <span m=''2396660''>really</span> <span m=''2396830''>make</span> <span m=''2397030''>sense</span>
  <span m=''2397420''>in</span> <span m=''2397510''>higher</span> <span m=''2397740''>dimensions.</span>
  <span m=''2398280''>I</span> <span m=''2398760''>don''t</span> <span m=''2398910''>think</span>
  <span m=''2399080''>I''ve</span> <span m=''2399160''>thought</span> <span m=''2399340''>about</span>
  <span m=''2399560''>it</span> <span m=''2399620''>much,</span> <span m=''2399970''>but</span>
  <span m=''2400070''>source</span> <span m=''2400340''>unfolding</span> <span m=''2400710''>makes</span>
  <span m=''2400910''>sense.</span> <span m=''2402300''>So</span> <span m=''2402450''>you</span>
  <span m=''2402520''>have</span> <span m=''2402670''>some</span> <span m=''2402840''>four</span>
  <span m=''2403400''>polytopes,</span> <span m=''2403830''>a</span> <span m=''2404070''>little</span>
  <span m=''2404230''>hard</span> <span m=''2404410''>to</span> <span m=''2404450''>imagine.</span>
  <span m=''2405420''>You</span> <span m=''2405550''>take</span> <span m=''2405780''>some</span>
  <span m=''2406040''>point</span> <span m=''2406340''>and</span> <span m=''2406650''>just</span>
  <span m=''2407790''>radiate</span> <span m=''2408290''>out</span> <span m=''2408480''>from</span>
  <span m=''2408630''>there,</span> <span m=''2409150''>unfold</span> <span m=''2409530''>like</span>
  <span m=''2409690''>that</span> <span m=''2409910''>until</span> <span m=''2410200''>you</span>
  <span m=''2410340''>hit</span> <span m=''2410480''>yourself,</span> <span m=''2411000''>and</span>
  <span m=''2411120''>then</span> <span m=''2411250''>you</span> <span m=''2411330''>stop,</span>
  <span m=''2412440''>and</span> <span m=''2412630''>that</span> <span m=''2412790''>works</span>
  <span m=''2413020''>in</span> <span m=''2413090''>any</span> <span m=''2413260''>dimension.</span>
  <span m=''2414510''>Source</span> <span m=''2414710''>unfolding</span> <span m=''2415680''>works</span>
  <span m=''2416170''>in</span> <span m=''2416300''>any</span> <span m=''2416480''>dimension.</span>
  <span m=''2417240''>That''s</span> <span m=''2417510''>fairly</span> <span m=''2418850''>recent,</span>
  <span m=''2419110''>2003,</span> <span m=''2419760''>Miller</span> <span m=''2420150''>and</span>
  <span m=''2420405''>Pak.</span> </p><p><span m=''2422870''>Another</span> <span
  m=''2423250''>thing</span> <span m=''2423410''>you</span> <span m=''2423550''>can</span>
  <span m=''2423680''>do</span> <span m=''2424810''>is</span> <span m=''2425310''>continuous</span>
  <span m=''2427460''>blooming.</span> <span m=''2432110''>This</span> <span m=''2432210''>is</span>
  <span m=''2432290''>an</span> <span m=''2432380''>idea</span> <span m=''2432680''>posed</span>
  <span m=''2432940''>by</span> <span m=''2433050''>Connolly</span> <span m=''2434240''>several</span>
  <span m=''2434560''>years</span> <span m=''2434810''>back</span> <span m=''2435700''>and</span>
  <span m=''2435850''>then</span> <span m=''2436000''>solved</span> <span m=''2437640''>last</span>
  <span m=''2437970''>year,</span> <span m=''2438280''>I</span> <span m=''2438330''>guess.</span>
  <span m=''2439220''>It was</span> <span m=''2439340''>presented</span> <span m=''2439740''>in</span>
  <span m=''2439820''>Japan.</span> <span m=''2442660''>This</span> <span m=''2442910''>is</span>
  <span m=''2443050''>about</span> <span m=''2444310''>folded</span> <span m=''2444650''>states</span>
  <span m=''2445090''>versus</span> <span m=''2445410''>folding</span> <span m=''2445680''>motions,</span>
  <span m=''2446400''>an</span> <span m=''2446520''>issue</span> <span m=''2446780''>we</span>
  <span m=''2446880''>have</span> <span m=''2446980''>thought</span> <span m=''2447170''>about</span>
  <span m=''2447390''>many</span> <span m=''2447610''>times</span> <span m=''2448080''>in</span>
  <span m=''2448180''>origami.</span> <span m=''2448450''>It</span> <span m=''2448720''>was</span>
  <span m=''2448940''>easy</span> <span m=''2449630''>for</span> <span m=''2449790''>any</span>
  <span m=''2450060''>polygonal</span> <span m=''2450440''>piece</span> <span m=''2450670''>of</span>
  <span m=''2450770''>paper.</span> <span m=''2451050''>We</span> <span m=''2451200''>could</span>
  <span m=''2451340''>go</span> <span m=''2452680''>from</span> <span m=''2452880''>unfolded
  to</span> <span m=''2453360''>folded</span> <span m=''2453660''>state</span> <span
  m=''2454120''>by a</span> <span m=''2454320''>continuous</span> <span m=''2454760''>motion</span>
  <span m=''2455060''>without</span> <span m=''2455320''>self</span> <span m=''2455500''>intersection.</span>
  <span m=''2456450''>For</span> <span m=''2456580''>linkages,</span> <span m=''2457090''>it</span>
  <span m=''2457190''>was</span> <span m=''2457420''>the</span> <span m=''2457550''>big</span>
  <span m=''2457810''>deal.</span> <span m=''2458400''>It was</span> <span m=''2458530''>all</span>
  <span m=''2458680''>about,</span> <span m=''2458990''>can</span> <span m=''2459160''>we</span>
  <span m=''2459250''>get</span> <span m=''2459430''>from</span> <span m=''2459540''>a</span>
  <span m=''2459690''>to</span> <span m=''2459760''>b?</span> </p><p><span m=''2462030''>For</span>
  <span m=''2462210''>convex</span> <span m=''2462740''>polyhedra,</span> <span m=''2464070''>you</span>
  <span m=''2464250''>can</span> <span m=''2464400''>do</span> <span m=''2464580''>it,</span>
  <span m=''2465700''>continuous</span> <span m=''2466160''>blooming.</span> <span
  m=''2466590''>This</span> <span m=''2466780''>is</span> <span m=''2467480''>in</span>
  <span m=''2467630''>the</span> <span m=''2467720''>middle</span> <span m=''2468260''>of</span>
  <span m=''2468490''>an</span> <span m=''2468580''>algorithm</span> <span m=''2469660''>of</span>
  <span m=''2470030''>continuously</span> <span m=''2470670''>blooming</span> <span
  m=''2471050''>the</span> <span m=''2471150''>source</span> <span m=''2471550''>unfolding.</span>
  <span m=''2472970''>So</span> <span m=''2473240''>here''s</span> <span m=''2473490''>our</span>
  <span m=''2473570''>point</span> <span m=''2473820''>x.</span> <span m=''2474380''>This</span>
  <span m=''2474570''>is</span> <span m=''2474710''>the</span> <span m=''2474840''>cube,</span>
  <span m=''2475660''>and</span> <span m=''2475910''>the</span> <span m=''2476080''>source</span>
  <span m=''2476430''>unfolding</span> <span m=''2476930''>of</span> <span m=''2477100''>a</span>
  <span m=''2477690''>cube</span> <span m=''2478570''>for</span> <span m=''2478730''>this</span>
  <span m=''2478940''>point</span> <span m=''2479190''>x</span> <span m=''2479440''>in</span>
  <span m=''2479500''>the</span> <span m=''2479580''>center</span> <span m=''2479990''>of
  a</span> <span m=''2480080''>face,</span> <span m=''2481050''>these</span> <span
  m=''2481290''>four</span> <span m=''2481650''>vertical</span> <span m=''2482040''>lines</span>
  <span m=''2482460''>and</span> <span m=''2482570''>then</span> <span m=''2482740''>a</span>
  <span m=''2482850''>little</span> <span m=''2483120''>x</span> <span m=''2483530''>on</span>
  <span m=''2483690''>the</span> <span m=''2483790''>top</span> <span m=''2484380''>side.</span>
  <span m=''2486370''>The</span> <span m=''2486520''>algorithm</span> <span m=''2487300''>unfolds</span>
  <span m=''2487710''>one</span> <span m=''2487910''>edge</span> <span m=''2488080''>at</span>
  <span m=''2488120''>a</span> <span m=''2488210''>time</span> <span m=''2488500''>but</span>
  <span m=''2488620''>in</span> <span m=''2488770''>a</span> <span m=''2488810''>very</span>
  <span m=''2489000''>specific</span> <span m=''2489510''>order.</span> <span m=''2490040''>So</span>
  <span m=''2490130''>it</span> <span m=''2490200''>ends</span> <span m=''2490420''>up</span>
  <span m=''2490570''>unfolding</span> <span m=''2491000''>this</span> <span m=''2491180''>entire</span>
  <span m=''2492420''>house</span> <span m=''2492910''>shape</span> <span m=''2493580''>first,</span>
  <span m=''2494170''>and</span> <span m=''2494320''>then</span> <span m=''2494460''>it''s</span>
  <span m=''2494630''>done</span> <span m=''2494830''>one</span> <span m=''2495090''>edge</span>
  <span m=''2495350''>of</span> <span m=''2495430''>this</span> <span m=''2495610''>one,</span>
  <span m=''2495790''>and</span> <span m=''2495860''>then</span> <span m=''2495970''>it''s</span>
  <span m=''2496100''>going</span> <span m=''2496200''>to</span> <span m=''2496270''>fold</span>
  <span m=''2496510''>the</span> <span m=''2496610''>other</span> <span m=''2496790''>one</span>
  <span m=''2496960''>down</span> <span m=''2497650''>and</span> <span m=''2497780''>then</span>
  <span m=''2497960''>unfold</span> <span m=''2498410''>one,</span> <span m=''2498950''>two</span>
  <span m=''2499450''>for</span> <span m=''2499620''>the</span> <span m=''2500070''>backside,</span>
  <span m=''2500730''>and</span> <span m=''2500800''>then</span> <span m=''2500940''>one,</span>
  <span m=''2501180''>two</span> <span m=''2501440''>for</span> <span m=''2501580''>the</span>
  <span m=''2501700''>left</span> <span m=''2501910''>side.</span> <span m=''2502670''>And</span>
  <span m=''2502830''>you</span> <span m=''2502940''>can</span> <span m=''2503040''>show</span>
  <span m=''2503260''>that</span> <span m=''2503420''>will</span> <span m=''2503640''>not</span>
  <span m=''2503920''>self</span> <span m=''2504130''>intersect</span> <span m=''2504670''>as</span>
  <span m=''2504760''>long</span> <span m=''2504940''>as</span> <span m=''2504990''>you</span>
  <span m=''2505070''>had</span> <span m=''2505170''>a</span> <span m=''2505220''>convex</span>
  <span m=''2505640''>polyhedron.</span> <span m=''2507060''>It''s</span> <span m=''2507180''>not</span>
  <span m=''2507320''>obvious</span> <span m=''2508320''>but</span> <span m=''2508560''>it''s</span>
  <span m=''2508680''>true.</span> </p><p><span m=''2510830''>There</span> <span m=''2511140''>are</span>
  <span m=''2511190''>some</span> <span m=''2511370''>other</span> <span m=''2511520''>results</span>
  <span m=''2511920''>that</span> <span m=''2512030''>if</span> <span m=''2512140''>you</span>
  <span m=''2512230''>have</span> <span m=''2513070''>any</span> <span m=''2513870''>unfolding</span>
  <span m=''2514630''>that</span> <span m=''2514740''>doesn''t</span> <span m=''2515090''>self</span>
  <span m=''2515270''>intersect</span> <span m=''2515640''>at</span> <span m=''2515800''>the</span>
  <span m=''2515950''>end,</span> <span m=''2517280''>you</span> <span m=''2517480''>can</span>
  <span m=''2517630''>add</span> <span m=''2517830''>some</span> <span m=''2517990''>cuts</span>
  <span m=''2518470''>and</span> <span m=''2518630''>make</span> <span m=''2518820''>it</span>
  <span m=''2518890''>actually</span> <span m=''2520350''>continuously</span> <span
  m=''2520980''>bloom.</span> <span m=''2521805''>It''s</span> <span m=''2522300''>kind</span>
  <span m=''2522490''>of</span> <span m=''2522550''>like</span> <span m=''2522690''>hinged</span>
  <span m=''2522870''>dissections.</span> <span m=''2523365''>It</span> <span m=''2523640''>may</span>
  <span m=''2523780''>not work</span> <span m=''2524280''>by</span> <span m=''2524430''>itself,</span>
  <span m=''2524840''>but</span> <span m=''2524950''>you''d</span> <span m=''2525220''>cut</span>
  <span m=''2525460''>the</span> <span m=''2525570''>pieces</span> <span m=''2525850''>into</span>
  <span m=''2526070''>smaller</span> <span m=''2526400''>pieces</span> <span m=''2526920''>and</span>
  <span m=''2527250''>then it</span> <span m=''2527480''>will</span> <span m=''2527580''>work.</span>
  <span m=''2529450''>That''s</span> <span m=''2529990''>pretty</span> <span m=''2530170''>good</span>
  <span m=''2530340''>news,</span> <span m=''2530850''>and</span> <span m=''2531030''>source</span>
  <span m=''2531240''>unfolding</span> <span m=''2531580''>just</span> <span m=''2531750''>works</span>
  <span m=''2532010''>as</span> <span m=''2532220''>is.</span> <span m=''2536070''>I</span>
  <span m=''2536350''>might</span> <span m=''2536890''>talk</span> <span m=''2537110''>about
  that</span> <span m=''2537430''>some</span> <span m=''2537680''>future</span> <span
  m=''2537970''>lecture.</span> </p><p><span m=''2543610''>Not</span> <span m=''2543850''>known,</span>
  <span m=''2544170''>for</span> <span m=''2544300''>example,</span> <span m=''2544720''>whether</span>
  <span m=''2544810''>the</span> <span m=''2544940''>star</span> <span m=''2545320''>unfolding</span>
  <span m=''2545760''>continuously</span> <span m=''2546370''>blooms.</span> <span
  m=''2547305''>That</span> <span m=''2547560''>sounds</span> <span m=''2547840''>a</span>
  <span m=''2547870''>little</span> <span m=''2548070''>scary</span> <span m=''2548460''>to</span>
  <span m=''2548530''>me.</span> <span m=''2550750''>We</span> <span m=''2550860''>don''t</span>
  <span m=''2551090''>actually</span> <span m=''2551520''>have</span> <span m=''2551910''>an</span>
  <span m=''2552000''>unfolding</span> <span m=''2552900''>of</span> <span m=''2553040''>a</span>
  <span m=''2553110''>convex</span> <span m=''2553490''>polyhedron</span> <span m=''2554040''>that</span>
  <span m=''2554230''>does</span> <span m=''2554420''>not</span> <span m=''2554820''>continuously</span>
  <span m=''2555195''>bloom.</span> <span m=''2556940''>I</span> <span m=''2557010''>think</span>
  <span m=''2557240''>there</span> <span m=''2557340''>should</span> <span m=''2557540''>be</span>
  <span m=''2557670''>one,</span> <span m=''2558370''>but</span> <span m=''2558490''>that''s</span>
  <span m=''2558670''>an</span> <span m=''2558840''>open</span> <span m=''2559080''>problem.</span>
  <span m=''2560460''>Is this</span> <span m=''2560590''>always</span> <span m=''2560900''>possible,</span>
  <span m=''2561950''>or</span> <span m=''2562120''>is</span> <span m=''2562230''>there</span>
  <span m=''2562400''>some</span> <span m=''2562700''>crazy</span> <span m=''2563210''>collection</span>
  <span m=''2563560''>of</span> <span m=''2563650''>cuts</span> <span m=''2564000''>that</span>
  <span m=''2564750''>you</span> <span m=''2564960''>cannot</span> <span m=''2565370''>escape?</span>
  <span m=''2569470''>That''s</span> <span m=''2571464''>that,</span> <span m=''2572340''>general</span>
  <span m=''2572630''>unfolding</span> <span m=''2573020''>of</span> <span m=''2573080''>convex</span>
  <span m=''2573460''>polyhedra.</span> </p><p><span m=''2574050''>Let''s</span> <span
  m=''2574330''>turn</span> <span m=''2574650''>to</span> <span m=''2575730''>the--</span>
  <span m=''2577430''>it''s</span> <span m=''2577750''>not</span> <span m=''2577880''>the</span>
  <span m=''2577940''>last</span> <span m=''2578190''>topic.</span> <span m=''2578900''>We</span>
  <span m=''2579020''>still</span> <span m=''2579250''>want</span> <span m=''2579380''>to</span>
  <span m=''2579440''>cover</span> <span m=''2579680''>both</span> <span m=''2579900''>of</span>
  <span m=''2579980''>these.</span> <span m=''2580710''>Next</span> <span m=''2580930''>topic</span>
  <span m=''2581320''>is</span> <span m=''2581780''>edge</span> <span m=''2582010''>unfolding</span>
  <span m=''2582650''>of</span> <span m=''2583000''>convex</span> <span m=''2583410''>polyhedra.</span>
  <span m=''2585320''>Now,</span> <span m=''2585570''>this</span> <span m=''2586100''>problem,</span>
  <span m=''2586590''>as</span> <span m=''2586780''>I</span> <span m=''2586820''>said,</span>
  <span m=''2587050''>goes</span> <span m=''2587260''>back</span> <span m=''2587600''>to</span>
  <span m=''2588100''>1525,</span> <span m=''2590200''>implicitly</span> <span m=''2591170''>at</span>
  <span m=''2591220''>least,</span> <span m=''2593090''>by</span> <span m=''2593330''>this</span>
  <span m=''2593560''>guy,</span> <span m=''2593820''>Albrecht</span> <span m=''2594290''>Durer,</span>
  <span m=''2595430''>who</span> <span m=''2596160''>was</span> <span m=''2597440''>a</span>
  <span m=''2597940''>cool</span> <span m=''2598170''>guy.</span> <span m=''2600445''>This</span>
  <span m=''2600850''>is</span> <span m=''2601140''>Renaissance</span> <span m=''2601610''>time.</span>
  <span m=''2602240''>He</span> <span m=''2602380''>did</span> <span m=''2602550''>many</span>
  <span m=''2602760''>different</span> <span m=''2603220''>things.</span> <span m=''2603730''>I</span>
  <span m=''2603890''>guess</span> <span m=''2604230''>painter</span> <span m=''2604515''>is</span>
  <span m=''2604800''>maybe</span> <span m=''2605160''>his</span> <span m=''2605530''>primary</span>
  <span m=''2605900''>profession,</span> <span m=''2606400''>but</span> <span m=''2606520''>he</span>
  <span m=''2606630''>did</span> <span m=''2606820''>a</span> <span m=''2606890''>lot</span>
  <span m=''2607110''>of</span> <span m=''2607180''>different</span> <span m=''2607440''>things.</span>
  <span m=''2607700''>He</span> <span m=''2607790''>studied</span> <span m=''2609160''>early</span>
  <span m=''2609520''>perspective,</span> <span m=''2610720''>all</span> <span m=''2610890''>that</span>
  <span m=''2611040''>good</span> <span m=''2611180''>stuff.</span> </p><p><span m=''2612300''>This</span>
  <span m=''2612480''>is</span> <span m=''2612590''>one</span> <span m=''2612750''>of</span>
  <span m=''2612840''>his</span> <span m=''2613000''>famous</span> <span m=''2613350''>prints.</span>
  <span m=''2613700''>It</span> <span m=''2614120''>was</span> <span m=''2614290''>actually</span>
  <span m=''2614580''>on</span> <span m=''2614700''>display</span> <span m=''2615070''>at</span>
  <span m=''2615180''>the</span> <span m=''2615640''>MFA</span> <span m=''2616140''>last</span>
  <span m=''2616450''>year,</span> <span m=''2616860''>I</span> <span m=''2617270''>got
  to</span> <span m=''2617390''>see</span> <span m=''2617550''>it,</span> <span m=''2618170''>and</span>
  <span m=''2618440''>it</span> <span m=''2618640''>has</span> <span m=''2618820''>a</span>
  <span m=''2618870''>little</span> <span m=''2619030''>polyhedron</span> <span m=''2619580''>thrown</span>
  <span m=''2619810''>in</span> <span m=''2619920''>there.</span> <span m=''2622260''>It''s</span>
  <span m=''2622320''>a</span> <span m=''2622360''>nice</span> <span m=''2622570''>polyhedron.</span>
  <span m=''2623700''>How</span> <span m=''2623900''>did</span> <span m=''2624030''>he</span>
  <span m=''2624120''>draw</span> <span m=''2624370''>them?</span> <span m=''2624600''>Well,</span>
  <span m=''2624790''>he</span> <span m=''2624870''>probably</span> <span m=''2625190''>built</span>
  <span m=''2625660''>models</span> <span m=''2626150''>out</span> <span m=''2626290''>of</span>
  <span m=''2626360''>some</span> <span m=''2626870''>material.</span> <span m=''2628320''>And</span>
  <span m=''2628580''>he was</span> <span m=''2628720''>just</span> <span m=''2628970''>generally</span>
  <span m=''2629300''>interested</span> <span m=''2629650''>in</span> <span m=''2629720''>the</span>
  <span m=''2629800''>third</span> <span m=''2629990''>dimension</span> <span m=''2630600''>and</span>
  <span m=''2631240''>understanding</span> <span m=''2631720''>how</span> <span m=''2631990''>all</span>
  <span m=''2632290''>these</span> <span m=''2632480''>things</span> <span m=''2632680''>worked,</span>
  <span m=''2633290''>and</span> <span m=''2633560''>so</span> <span m=''2633660''>he</span>
  <span m=''2634180''>made</span> <span m=''2634550''>a</span> <span m=''2634600''>lot</span>
  <span m=''2634790''>of</span> <span m=''2634880''>unfoldings</span> <span m=''2635640''>in</span>
  <span m=''2635810''>this</span> <span m=''2636050''>book.</span> </p><p><span m=''2637080''>This</span>
  <span m=''2637270''>is</span> <span m=''2637380''>the</span> <span m=''2637690''>original</span>
  <span m=''2638590''>title.</span> <span m=''2639290''>Here''s</span> <span m=''2639600''>a</span>
  <span m=''2639660''>translation.</span> <span m=''2640900''>Titles</span> <span
  m=''2641210''>were</span> <span m=''2641310''>a</span> <span m=''2641360''>lot</span>
  <span m=''2641560''>longer</span> <span m=''2641850''>in</span> <span m=''2641920''>those</span>
  <span m=''2642070''>days.</span> <span m=''2643140''>The</span> <span m=''2643260''>Painter''s</span>
  <span m=''2643760''>Manual</span> <span m=''2644090''>is</span> <span m=''2644420''>what</span>
  <span m=''2644520''>I</span> <span m=''2644670''>usually</span> <span m=''2644970''>call</span>
  <span m=''2645170''>it,</span> <span m=''2645550''>"A</span> <span m=''2645600''>Manual
  of</span> <span m=''2645920''>Measurement of</span> <span m=''2646320''>Lines,</span>
  <span m=''2646700''>Areas,</span> <span m=''2647050''>and</span> <span m=''2647120''>Solids</span>
  <span m=''2647450''>by</span> <span m=''2647570''>Means</span> <span m=''2647760''>of</span>
  <span m=''2647810''>Compass</span> <span m=''2648140''>and</span> <span m=''2648230''>Ruler</span>
  <span m=''2648520''>Assembled</span> <span m=''2648870''>by</span> <span m=''2649000''>Albrecht</span>
  <span m=''2649140''>Durer</span> <span m=''2649670''>for</span> <span m=''2649830''>the</span>
  <span m=''2650110''>Use</span> <span m=''2650320''>of</span> <span m=''2650430''>all</span>
  <span m=''2650720''>Lovers</span> <span m=''2650990''>of</span> <span m=''2651100''>Art</span>
  <span m=''2651280''>with</span> <span m=''2651400''>Appropriate</span> <span m=''2651780''>Illustrations</span>
  <span m=''2652035''>Arranged</span> <span m=''2652290''>to</span> <span m=''2652550''>be</span>
  <span m=''2652660''>Printed</span> <span m=''2652990''>in the</span> <span m=''2653280''>Year</span>
  <span m=''2653780''>MDXXV."</span> <span m=''2656320''>And</span> <span m=''2656530''>I</span>
  <span m=''2656590''>don''t</span> <span m=''2656770''>even</span> <span m=''2656940''>know</span>
  <span m=''2657040''>what</span> <span m=''2657130''>the</span> <span m=''2657590''>subtitle</span>
  <span m=''2657860''>is,</span> <span m=''2658610''>but</span> <span m=''2659680''>there</span>
  <span m=''2659930''>you go.</span> <span m=''2660360''>If</span> <span m=''2660630''>you</span>
  <span m=''2661010''>read</span> <span m=''2661200''>German,</span> <span m=''2661580''>I''m</span>
  <span m=''2661800''>told</span> <span m=''2662040''>this</span> <span m=''2662210''>is</span>
  <span m=''2662310''>a</span> <span m=''2662380''>challenge</span> <span m=''2662760''>because</span>
  <span m=''2663140''>of the</span> <span m=''2663240''>old</span> <span m=''2663480''>script.</span>
  </p><p><span m=''2666240''>So</span> <span m=''2666900''>unfoldings</span> <span
  m=''2668460''>like</span> <span m=''2668700''>this.</span> <span m=''2669620''>He</span>
  <span m=''2669790''>did</span> <span m=''2670040''>mostly</span> <span m=''2670560''>Archimedian</span>
  <span m=''2671100''>solids</span> <span m=''2671490''>in</span> <span m=''2671650''>this</span>
  <span m=''2671870''>book.</span> <span m=''2672410''>This</span> <span m=''2672570''>book</span>
  <span m=''2672780''>is</span> <span m=''2673090''>several</span> <span m=''2673250''>hundred</span>
  <span m=''2673530''>pages</span> <span m=''2674070''>long.</span> <span m=''2674840''>I
  have</span> <span m=''2674950''>a</span> <span m=''2675000''>copy.</span> <span
  m=''2676790''>This</span> <span m=''2676990''>is</span> <span m=''2677130''>a</span>
  <span m=''2677210''>cuboctahedron</span> <span m=''2678470''>unfolded.</span> <span
  m=''2681380''>He</span> <span m=''2681850''>is</span> <span m=''2682410''>only</span>
  <span m=''2682670''>cutting</span> <span m=''2682950''>along</span> <span m=''2683230''>edges,</span>
  <span m=''2683860''>and he</span> <span m=''2684130''>liked</span> <span m=''2684350''>this,</span>
  <span m=''2684700''>I</span> <span m=''2684830''>presume,</span> <span m=''2685290''>for</span>
  <span m=''2685590''>building</span> <span m=''2685920''>models.</span> <span m=''2687290''>Here''s</span>
  <span m=''2687590''>a</span> <span m=''2687720''>fancy</span> <span m=''2688170''>one,</span>
  <span m=''2688500''>the</span> <span m=''2688720''>snub cube.</span> <span m=''2689180''>This</span>
  <span m=''2689360''>one,</span> <span m=''2689520''>I</span> <span m=''2689590''>think,</span>
  <span m=''2689810''>might</span> <span m=''2689990''>have</span> <span m=''2690150''>an</span>
  <span m=''2690230''>error.</span> <span m=''2690520''>A</span> <span m=''2690570''>couple</span>
  <span m=''2690840''>of</span> <span m=''2690910''>them</span> <span m=''2691040''>have</span>
  <span m=''2691170''>very</span> <span m=''2691370''>small</span> <span m=''2691680''>errors,</span>
  <span m=''2693570''>but</span> <span m=''2694385''>for</span> <span m=''2694710''>the</span>
  <span m=''2694940''>most</span> <span m=''2695170''>part,</span> <span m=''2695380''>he</span>
  <span m=''2695530''>was</span> <span m=''2695730''>the</span> <span m=''2695920''>inventor</span>
  <span m=''2696410''>of</span> <span m=''2696620''>edge</span> <span m=''2696780''>unfolding.</span>
  </p><p><span m=''2698030''>Now,</span> <span m=''2698180''>he</span> <span m=''2698270''>didn''t</span>
  <span m=''2698640''>ask,</span> <span m=''2699480''>is</span> <span m=''2699690''>this</span>
  <span m=''2699820''>always</span> <span m=''2700150''>possible,</span> <span m=''2701170''>but</span>
  <span m=''2702010''>we</span> <span m=''2702160''>did.</span> <span m=''2703230''>Mathematicians</span>
  <span m=''2703890''>did</span> <span m=''2704220''>in</span> <span m=''2707290''>1976,</span>
  <span m=''2709040''>I</span> <span m=''2709100''>believe,</span> <span m=''2710290''>or</span>
  <span m=''2710550''>''85.</span> <span m=''2715370''>''75,</span> <span m=''2719850''>G.</span>
  <span m=''2720060''>C.</span> <span m=''2720370''>Shephard,</span> <span m=''2720920''>geometer.</span>
  <span m=''2722230''>He</span> <span m=''2722720''>was</span> <span m=''2722920''>the</span>
  <span m=''2722990''>first</span> <span m=''2723230''>one</span> <span m=''2723340''>to</span>
  <span m=''2723590''>write</span> <span m=''2723800''>it</span> <span m=''2723900''>in</span>
  <span m=''2724010''>a</span> <span m=''2724060''>paper,</span> <span m=''2724830''>does</span>
  <span m=''2725030''>every</span> <span m=''2725460''>convex</span> <span m=''2725820''>polyhedron</span>
  <span m=''2726460''>have</span> <span m=''2726840''>an</span> <span m=''2726940''>edge</span>
  <span m=''2727130''>unfolding?</span> </p><p><span m=''2731910''>So</span> <span
  m=''2733080''>what</span> <span m=''2733250''>can I</span> <span m=''2733450''>tell</span>
  <span m=''2733650''>you</span> <span m=''2733730''>about</span> <span m=''2733940''>this</span>
  <span m=''2734100''>problem?</span> <span m=''2736000''>It''s</span> <span m=''2736160''>hard.</span>
  <span m=''2737460''>Many</span> <span m=''2737670''>people</span> <span m=''2737950''>have</span>
  <span m=''2738050''>thought</span> <span m=''2738260''>about</span> <span m=''2738530''>it.</span>
  <span m=''2741180''>I''m</span> <span m=''2741340''>not</span> <span m=''2741500''>really</span>
  <span m=''2741710''>sure</span> <span m=''2741910''>that</span> <span m=''2742050''>it''s</span>
  <span m=''2742180''>possible.</span> <span m=''2748420''>A</span> <span m=''2748900''>lot</span>
  <span m=''2749090''>of</span> <span m=''2749150''>people</span> <span m=''2749420''>do,</span>
  <span m=''2749610''>though.</span> <span m=''2765240''>It''s</span> <span m=''2765400''>possible</span>
  <span m=''2765860''>for</span> <span m=''2766040''>a</span> <span m=''2766100''>lot</span>
  <span m=''2766420''>of</span> <span m=''2767180''>polyhedra.</span> <span m=''2768780''>In</span>
  <span m=''2768900''>fact,</span> <span m=''2769180''>every</span> <span m=''2769460''>polyhedron</span>
  <span m=''2769950''>we''ve</span> <span m=''2770100''>tried</span> <span m=''2770430''>to</span>
  <span m=''2770480''>unfold</span> <span m=''2770930''>we</span> <span m=''2771020''>have</span>
  <span m=''2771210''>eventually</span> <span m=''2771670''>unfolded--</span> <span
  m=''2772440''>convex</span> <span m=''2772850''>polyhedron.</span> </p><p><span
  m=''2774100''>Simple</span> <span m=''2774470''>set</span> <span m=''2774650''>of</span>
  <span m=''2774720''>examples</span> <span m=''2775220''>are</span> <span m=''2775560''>the
  Archimedian</span> <span m=''2775970''>solids.</span> <span m=''2777680''>Doesn''t</span>
  <span m=''2777960''>take</span> <span m=''2778390''>that</span> <span m=''2778720''>much</span>
  <span m=''2778910''>effort</span> <span m=''2779340''>to</span> <span m=''2779860''>find</span>
  <span m=''2780220''>unfoldings</span> <span m=''2780645''>of</span> <span m=''2780970''>all
  of</span> <span m=''2781340''>them.</span> <span m=''2781440''>You</span> <span
  m=''2781580''>can do this</span> <span m=''2781930''>with</span> <span m=''2782060''>exhaustive</span>
  <span m=''2782480''>search</span> <span m=''2782890''>or</span> <span m=''2783370''>just</span>
  <span m=''2784150''>playing</span> <span m=''2784400''>around.</span> <span m=''2785310''>A</span>
  <span m=''2785770''>lot</span> <span m=''2785960''>of</span> <span m=''2786020''>people
  have</span> <span m=''2786290''>done</span> <span m=''2786450''>this</span> <span
  m=''2786600''>over</span> <span m=''2786750''>the</span> <span m=''2786850''>years.</span>
  <span m=''2788020''>This</span> <span m=''2788170''>is</span> <span m=''2788250''>all</span>
  <span m=''2788430''>the</span> <span m=''2788510''>unfoldings</span> <span m=''2788930''>of</span>
  <span m=''2789060''>those</span> <span m=''2789300''>guys.</span> </p><p><span m=''2790550''>There''s</span>
  <span m=''2790800''>a</span> <span m=''2790880''>lot</span> <span m=''2791200''>of</span>
  <span m=''2791360''>heuristic</span> <span m=''2792030''>software</span> <span m=''2793370''>for</span>
  <span m=''2794080''>actually</span> <span m=''2794450''>doing</span> <span m=''2794690''>this.</span>
  <span m=''2795680''>I</span> <span m=''2795750''>think</span> <span m=''2795920''>the</span>
  <span m=''2796010''>coolest</span> <span m=''2796400''>one</span> <span m=''2796510''>right</span>
  <span m=''2796680''>now</span> <span m=''2796950''>is</span> <span m=''2797420''>Pepakura.</span>
  <span m=''2799290''>If</span> <span m=''2799410''>you</span> <span m=''2799510''>want</span>
  <span m=''2799670''>to</span> <span m=''2799720''>build</span> <span m=''2799910''>a</span>
  <span m=''2799950''>paper</span> <span m=''2800200''>model of</span> <span m=''2800560''>something,</span>
  <span m=''2801020''>you</span> <span m=''2801140''>have</span> <span m=''2801350''>a</span>
  <span m=''2801400''>3D</span> <span m=''2801690''>model</span> <span m=''2802520''>thrown</span>
  <span m=''2802810''>into</span> <span m=''2802980''>Pepakura</span> <span m=''2803540''>and</span>
  <span m=''2803670''>it''ll</span> <span m=''2803810''>probably</span> <span m=''2804160''>give</span>
  <span m=''2804310''>you a</span> <span m=''2804460''>one</span> <span m=''2804680''>piece</span>
  <span m=''2804910''>unfolding,</span> <span m=''2805330''>even</span> <span m=''2805610''>for</span>
  <span m=''2805760''>non-convex</span> <span m=''2806350''>shapes.</span> <span m=''2806690''>Even
  though</span> <span m=''2806890''>it''s</span> <span m=''2807090''>not</span> <span
  m=''2807270''>always</span> <span m=''2807470''>possible,</span> <span m=''2808740''>it''ll</span>
  <span m=''2809340''>do</span> <span m=''2809520''>edge</span> <span m=''2809720''>cuttings,</span>
  <span m=''2810140''>it''ll</span> <span m=''2810280''>try</span> <span m=''2810480''>to</span>
  <span m=''2810590''>do</span> <span m=''2810690''>some</span> <span m=''2810900''>exhaustive</span>
  <span m=''2811310''>search,</span> <span m=''2812270''>and</span> <span m=''2812630''>usually</span>
  <span m=''2812980''>does</span> <span m=''2813160''>pretty</span> <span m=''2813360''>well.</span>
  <span m=''2813540''>Sometimes</span> <span m=''2813940''>it''ll</span> <span m=''2814070''>use</span>
  <span m=''2814230''>multiple</span> <span m=''2814580''>pieces.</span> <span m=''2815310''>That''s
  the</span> <span m=''2815600''>catch.</span> <span m=''2818350''>There''s</span>
  <span m=''2818430''>a</span> <span m=''2818480''>link</span> <span m=''2818720''>in</span>
  <span m=''2818840''>the</span> <span m=''2818960''>lecture</span> <span m=''2819230''>notes.</span>
  </p><p><span m=''2820670''>The</span> <span m=''2820820''>most</span> <span m=''2821240''>thorough</span>
  <span m=''2821790''>mathematical</span> <span m=''2822420''>search</span> <span
  m=''2823710''>is</span> <span m=''2823870''>by</span> <span m=''2824030''>this</span>
  <span m=''2824210''>guy,</span> <span m=''2825050''>Wolfram</span> <span m=''2825230''>Schlickenrieder,</span>
  <span m=''2829310''>who</span> <span m=''2830360''>wrote</span> <span m=''2831480''>the</span>
  <span m=''2831610''>equivalent</span> <span m=''2831960''>of</span> <span m=''2832040''>a</span>
  <span m=''2832090''>master''s</span> <span m=''2832510''>thesis</span> <span m=''2833040''>in</span>
  <span m=''2833670''>Berlin</span> <span m=''2836550''>13</span> <span m=''2836990''>years</span>
  <span m=''2837220''>ago.</span> <span m=''2839560''>I</span> <span m=''2839630''>just</span>
  <span m=''2839800''>wrote</span> <span m=''2840060''>to him about</span> <span m=''2840360''>it</span>
  <span m=''2840620''>yesterday.</span> <span m=''2841180''>I</span> <span m=''2841663''>was
  like,</span> <span m=''2842146''>hey,</span> <span m=''2842630''>this is</span>
  <span m=''2843120''>cool</span> <span m=''2843290''>stuff.</span> <span m=''2843590''>Can
  I show it in</span> <span m=''2844090''>my</span> <span m=''2844200''>lecture?</span>
  <span m=''2844600''>He was like,</span> <span m=''2844760''>yeah,</span> <span m=''2845200''>it</span>
  <span m=''2845350''>lives</span> <span m=''2845580''>on.</span> </p><p><span m=''2849600''>He</span>
  <span m=''2849790''>had</span> <span m=''2850040''>a</span> <span m=''2850110''>class</span>
  <span m=''2850540''>of</span> <span m=''2851660''>10</span> <span m=''2851960''>different</span>
  <span m=''2852240''>algorithms,</span> <span m=''2853170''>around</span> <span m=''2853980''>that</span>
  <span m=''2854150''>many,</span> <span m=''2855880''>possible</span> <span m=''2856380''>algorithms</span>
  <span m=''2856750''>for</span> <span m=''2856860''>unfolding</span> <span m=''2857270''>all</span>
  <span m=''2857440''>convex</span> <span m=''2857820''>polyhedra,</span> <span m=''2858640''>and</span>
  <span m=''2858880''>then</span> <span m=''2859000''>he</span> <span m=''2859090''>came</span>
  <span m=''2859290''>up</span> <span m=''2859420''>with</span> <span m=''2859530''>a</span>
  <span m=''2859770''>dozen</span> <span m=''2860120''>different</span> <span m=''2860560''>families</span>
  <span m=''2861110''>of</span> <span m=''2861200''>polyhedra.</span> <span m=''2861750''>I</span>
  <span m=''2861770''>don''t</span> <span m=''2861900''>have</span> <span m=''2862020''>the</span>
  <span m=''2862110''>polyhedra</span> <span m=''2862395''>drawn</span> <span m=''2862830''>here,</span>
  <span m=''2863020''>just</span> <span m=''2863230''>the</span> <span m=''2863350''>unfoldings.</span>
  <span m=''2867420''>They''re</span> <span m=''2867790''>generators</span> <span
  m=''2868450''>of</span> <span m=''2869230''>big</span> <span m=''2869670''>classes</span>
  <span m=''2870000''>of</span> <span m=''2870080''>polyhedra.</span> <span m=''2871160''>He</span>
  <span m=''2871270''>applied</span> <span m=''2871490''>every</span> <span m=''2871710''>algorithm</span>
  <span m=''2872060''>to</span> <span m=''2872140''>every</span> <span m=''2872330''>class.</span>
  </p><p><span m=''2874440''>Ideally,</span> <span m=''2874890''>you</span> <span
  m=''2874990''>get</span> <span m=''2875140''>an</span> <span m=''2875230''>algorithm
  that</span> <span m=''2875630''>works</span> <span m=''2875830''>for</span> <span
  m=''2875940''>all</span> <span m=''2876180''>classes</span> <span m=''2876900''>or</span>
  <span m=''2877310''>you</span> <span m=''2877430''>find</span> <span m=''2877830''>a</span>
  <span m=''2878040''>class</span> <span m=''2878550''>that</span> <span m=''2878730''>foils</span>
  <span m=''2879170''>all</span> <span m=''2879370''>algorithms.</span> <span m=''2880620''>Sadly,</span>
  <span m=''2881260''>he</span> <span m=''2881450''>found</span> <span m=''2881730''>neither.</span>
  <span m=''2883080''>Every</span> <span m=''2883410''>algorithm</span> <span m=''2884660''>was</span>
  <span m=''2885040''>foiled</span> <span m=''2885590''>by</span> <span m=''2885720''>some</span>
  <span m=''2885990''>example,</span> <span m=''2887190''>yet</span> <span m=''2887500''>every</span>
  <span m=''2887870''>example</span> <span m=''2888460''>was</span> <span m=''2888690''>foiled</span>
  <span m=''2889210''>by</span> <span m=''2889380''>some</span> <span m=''2889670''>algorithm.</span>
  <span m=''2893060''>It''s</span> <span m=''2893210''>really</span> <span m=''2893430''>annoying,</span>
  <span m=''2894920''>but</span> <span m=''2895060''>here''s</span> <span m=''2895250''>some</span>
  <span m=''2895420''>examples</span> <span m=''2895880''>where</span> <span m=''2896260''>they</span>
  <span m=''2896440''>fail.</span> <span m=''2896960''>They</span> <span m=''2897120''>just</span>
  <span m=''2897400''>barely</span> <span m=''2897860''>fail,</span> <span m=''2898290''>just
  a</span> <span m=''2898680''>couple</span> <span m=''2899020''>triangles</span>
  <span m=''2899480''>are</span> <span m=''2899540''>messed</span> <span m=''2899870''>up.</span>
  <span m=''2900710''>Little</span> <span m=''2901200''>squares</span> <span m=''2901495''>are</span>
  <span m=''2901840''>messed</span> <span m=''2902070''>up.</span> <span m=''2902280''>I
  think</span> <span m=''2902700''>these</span> <span m=''2902840''>are</span> <span
  m=''2902920''>called</span> <span m=''2903090''>the</span> <span m=''2903200''>turtle</span>
  <span m=''2903700''>polyhedra.</span> <span m=''2904320''>It''s</span> <span m=''2904780''>like</span>
  <span m=''2904900''>a</span> <span m=''2904950''>big,</span> <span m=''2905170''>flat</span>
  <span m=''2905490''>thing</span> <span m=''2905700''>and</span> <span m=''2905800''>then</span>
  <span m=''2905920''>a</span> <span m=''2906020''>dome</span> <span m=''2906350''>on</span>
  <span m=''2906490''>top.</span> </p><p><span m=''2909080''>So</span> <span m=''2910250''>inconclusive,</span>
  <span m=''2911120''>I</span> <span m=''2911240''>guess,</span> <span m=''2911500''>is</span>
  <span m=''2911600''>the</span> <span m=''2911670''>answer.</span> <span m=''2911960''>There</span>
  <span m=''2912100''>was</span> <span m=''2912270''>one</span> <span m=''2912640''>algorithm</span>
  <span m=''2913940''>that</span> <span m=''2914070''>had</span> <span m=''2914260''>a</span>
  <span m=''2914310''>degree</span> <span m=''2914590''>of</span> <span m=''2914670''>freedom.</span>
  <span m=''2914970''>You had</span> <span m=''2915140''>to</span> <span m=''2915420''>choose
  a</span> <span m=''2915490''>direction,</span> <span m=''2916720''>then</span> <span
  m=''2916830''>you</span> <span m=''2916930''>cut</span> <span m=''2917110''>along</span>
  <span m=''2917320''>all</span> <span m=''2917440''>the</span> <span m=''2917550''>edges</span>
  <span m=''2917830''>that</span> <span m=''2917920''>are</span> <span m=''2917990''>most</span>
  <span m=''2918300''>in</span> <span m=''2918360''>that</span> <span m=''2918510''>direction.</span>
  <span m=''2919600''>And</span> <span m=''2919840''>there</span> <span m=''2919920''>was</span>
  <span m=''2920100''>a</span> <span m=''2920180''>conjecture</span> <span m=''2920640''>on</span>
  <span m=''2920750''>the</span> <span m=''2920830''>table</span> <span m=''2921130''>from</span>
  <span m=''2921340''>this</span> <span m=''2921530''>thesis</span> <span m=''2921980''>that</span>
  <span m=''2922120''>maybe</span> <span m=''2923370''>for</span> <span m=''2923600''>every</span>
  <span m=''2923810''>polyhedron,</span> <span m=''2924340''>there</span> <span m=''2924570''>is</span>
  <span m=''2924760''>a</span> <span m=''2924830''>direction</span> <span m=''2925250''>that</span>
  <span m=''2925350''>works,</span> <span m=''2926250''>but</span> <span m=''2926380''>then</span>
  <span m=''2926520''>that</span> <span m=''2926740''>was</span> <span m=''2926940''>destroyed</span>
  <span m=''2928400''>four</span> <span m=''2928810''>years</span> <span m=''2929080''>ago.</span>
  <span m=''2929950''>Brendan</span> <span m=''2930280''>Lucier</span> <span m=''2931410''>from</span>
  <span m=''2931640''>Waterloo</span> <span m=''2932450''>proved</span> <span m=''2932670''>that</span>
  <span m=''2932980''>that''s</span> <span m=''2933450''>not</span> <span m=''2933620''>true.</span>
  <span m=''2933840''>He found</span> <span m=''2934060''>a</span> <span m=''2934110''>polyhedron</span>
  <span m=''2934640''>that</span> <span m=''2934720''>doesn''t</span> <span m=''2934930''>work</span>
  <span m=''2935090''>from</span> <span m=''2935220''>any</span> <span m=''2935350''>direction.</span>
  </p><p><span m=''2936810''>So</span> <span m=''2936960''>at</span> <span m=''2937050''>the</span>
  <span m=''2937120''>moment,</span> <span m=''2937360''>we</span> <span m=''2937470''>have</span>
  <span m=''2937570''>no</span> <span m=''2937730''>candidate</span> <span m=''2938110''>algorithms,</span>
  <span m=''2938860''>which</span> <span m=''2938980''>makes</span> <span m=''2939200''>me</span>
  <span m=''2939340''>worry</span> <span m=''2939950''>whether</span> <span m=''2940170''>this</span>
  <span m=''2940340''>could</span> <span m=''2940460''>possibly</span> <span m=''2940890''>be</span>
  <span m=''2941040''>true.</span> <span m=''2944200''>We</span> <span m=''2944250''>have</span>
  <span m=''2944410''>some</span> <span m=''2945620''>more</span> <span m=''2945900''>bad</span>
  <span m=''2946150''>examples.</span> <span m=''2946750''>Here are</span> <span m=''2946930''>some</span>
  <span m=''2948230''>annoying</span> <span m=''2948600''>things,</span> <span m=''2949730''>like</span>
  <span m=''2949970''>a</span> <span m=''2950050''>cube</span> <span m=''2950570''>with</span>
  <span m=''2950750''>a</span> <span m=''2950820''>corner</span> <span m=''2951130''>cut</span>
  <span m=''2951330''>off.</span> <span m=''2954370''>It''s a</span> <span m=''2954580''>very</span>
  <span m=''2954810''>local</span> <span m=''2955140''>thing,</span> <span m=''2955450''>but</span>
  <span m=''2955560''>you</span> <span m=''2955680''>can</span> <span m=''2955830''>mess</span>
  <span m=''2956080''>up</span> <span m=''2956350''>really</span> <span m=''2956570''>easily.</span>
  <span m=''2957030''>It''s</span> <span m=''2957410''>actually</span> <span m=''2957630''>quite</span>
  <span m=''2957820''>common</span> <span m=''2958140''>to</span> <span m=''2958190''>mess</span>
  <span m=''2958430''>up,</span> <span m=''2958830''>I would</span> <span m=''2958990''>say,</span>
  <span m=''2959760''>even</span> <span m=''2959970''>though</span> <span m=''2960320''>for</span>
  <span m=''2960760''>things</span> <span m=''2961040''>like</span> <span m=''2961180''>Archimedian,</span>
  <span m=''2961340''>it''s</span> <span m=''2961840''>much</span> <span m=''2962020''>harder</span>
  <span m=''2962430''>to</span> <span m=''2962550''>mess</span> <span m=''2962930''>up.</span>
  </p><p><span m=''2963470''>Simplest</span> <span m=''2963880''>polyhedron</span>
  <span m=''2964620''>that</span> <span m=''2964870''>messes</span> <span m=''2965180''>up</span>
  <span m=''2965350''>is</span> <span m=''2965570''>this</span> <span m=''2966620''>sliver</span>
  <span m=''2967090''>tetrahedron.</span> <span m=''2968340''>So</span> <span m=''2968430''>the</span>
  <span m=''2968520''>polyhedron</span> <span m=''2968990''>is</span> <span m=''2969090''>drawn</span>
  <span m=''2969310''>at</span> <span m=''2969400''>the</span> <span m=''2969550''>top.</span>
  <span m=''2970800''>It''s</span> <span m=''2970890''>a</span> <span m=''2970930''>little</span>
  <span m=''2971100''>hard</span> <span m=''2971320''>to</span> <span m=''2971390''>see,</span>
  <span m=''2972940''>but</span> <span m=''2978390''>on</span> <span m=''2978550''>the</span>
  <span m=''2978620''>backside,</span> <span m=''2979650''>there''s</span> <span m=''2981580''>an</span>
  <span m=''2981710''>edge</span> <span m=''2981890''>like</span> <span m=''2982060''>that,</span>
  <span m=''2984020''>if</span> <span m=''2984420''>you</span> <span m=''2984550''>can</span>
  <span m=''2984670''>imagine.</span> <span m=''2987250''>So</span> <span m=''2987310''>it''s</span>
  <span m=''2987560''>almost</span> <span m=''2988020''>flat,</span> <span m=''2989350''>so</span>
  <span m=''2989520''>that''s</span> <span m=''2989860''>why</span> <span m=''2990050''>it''s</span>
  <span m=''2990190''>drawn</span> <span m=''2990600''>flat,</span> <span m=''2991980''>and</span>
  <span m=''2992480''>the</span> <span m=''2992590''>four</span> <span m=''2992830''>corners,</span>
  <span m=''2993330''>like a</span> <span m=''2993550''>tetrahedron</span> <span m=''2994050''>should</span>
  <span m=''2994210''>have,</span> <span m=''2995030''>four</span> <span m=''2995260''>faces,</span>
  <span m=''2995820''>the</span> <span m=''2995900''>front</span> <span m=''2996170''>two</span>
  <span m=''2996280''>triangles</span> <span m=''2996740''>and the</span> <span m=''2996870''>back</span>
  <span m=''2997120''>two</span> <span m=''2997240''>triangles</span> <span m=''2997535''>with</span>
  <span m=''2997830''>the</span> <span m=''2997920''>line</span> <span m=''2998260''>that
  I</span> <span m=''2998350''>drew.</span> <span m=''2999580''>And</span> <span m=''2999710''>if</span>
  <span m=''2999790''>you</span> <span m=''3000230''>unfold</span> <span m=''3000710''>it</span>
  <span m=''3000990''>in</span> <span m=''3001090''>a</span> <span m=''3001150''>simple</span>
  <span m=''3001480''>way,</span> <span m=''3001930''>you</span> <span m=''3002000''>just</span>
  <span m=''3002180''>cut</span> <span m=''3002380''>from</span> <span m=''3002550''>a</span>
  <span m=''3002700''>to</span> <span m=''3002760''>b,</span> <span m=''3003085''>it</span>
  <span m=''3003530''>unfolds</span> <span m=''3003840''>like</span> <span m=''3003990''>this,</span>
  <span m=''3004220''>no</span> <span m=''3004350''>problem.</span> <span m=''3005240''>But</span>
  <span m=''3005280''>if</span> <span m=''3005390''>you</span> <span m=''3005510''>unfold</span>
  <span m=''3005800''>the</span> <span m=''3005880''>wrong</span> <span m=''3006150''>way,</span>
  <span m=''3007110''>which</span> <span m=''3007340''>is</span> <span m=''3007450''>to</span>
  <span m=''3007550''>cut</span> <span m=''3007950''>both</span> <span m=''3008150''>of</span>
  <span m=''3008230''>the</span> <span m=''3008330''>diagonal</span> <span m=''3008840''>lines,</span>
  <span m=''3009820''>then</span> <span m=''3010000''>you</span> <span m=''3010270''>end</span>
  <span m=''3010480''>up</span> <span m=''3010630''>with</span> <span m=''3010750''>the</span>
  <span m=''3010880''>spears</span> <span m=''3011300''>that cross</span> <span m=''3011680''>each</span>
  <span m=''3011820''>other,</span> <span m=''3012990''>so</span> <span m=''3013210''>you</span>
  <span m=''3013390''>really</span> <span m=''3013560''>have</span> <span m=''3013700''>to</span>
  <span m=''3013800''>be</span> <span m=''3013900''>careful.</span> </p><p><span m=''3015590''>In</span>
  <span m=''3015720''>fact,</span> <span m=''3019120''>if</span> <span m=''3019170''>you</span>
  <span m=''3019250''>take</span> <span m=''3019460''>a</span> <span m=''3019610''>random</span>
  <span m=''3020150''>polyhedron--</span> <span m=''3021660''>I</span> <span m=''3021780''>choose</span>
  <span m=''3022100''>80</span> <span m=''3023020''>points</span> <span m=''3023360''>on</span>
  <span m=''3023470''>a</span> <span m=''3023520''>sphere,</span> <span m=''3024030''>I</span>
  <span m=''3024380''>take</span> <span m=''3024580''>the</span> <span m=''3024660''>convex</span>
  <span m=''3025040''>hull.</span> <span m=''3025370''>It''s a</span> <span m=''3025650''>very</span>
  <span m=''3025860''>nice,</span> <span m=''3026180''>round</span> <span m=''3027120''>sphere-like</span>
  <span m=''3027590''>polyhedron.</span> <span m=''3028600''>And</span> <span m=''3028880''>I</span>
  <span m=''3028900''>look</span> <span m=''3029140''>at</span> <span m=''3029360''>all</span>
  <span m=''3029760''>the</span> <span m=''3029910''>unfoldings--</span> <span m=''3031300''>this</span>
  <span m=''3031520''>is</span> <span m=''3031730''>probably not</span> <span m=''3031840''>all</span>
  <span m=''3032080''>the</span> <span m=''3032170''>unfoldings,</span> <span m=''3032620''>but</span>
  <span m=''3033240''>I</span> <span m=''3033520''>randomly</span> <span m=''3033960''>generate</span>
  <span m=''3034380''>unfoldings,</span> <span m=''3035360''>and</span> <span m=''3036520''>I</span>
  <span m=''3037200''>evaluate,</span> <span m=''3037750''>what</span> <span m=''3037910''>is</span>
  <span m=''3038020''>the</span> <span m=''3039160''>observed</span> <span m=''3039480''>probability</span>
  <span m=''3040650''>that</span> <span m=''3041250''>I</span> <span m=''3041380''>get</span>
  <span m=''3041550''>overlap?</span> <span m=''3042870''>And</span> <span m=''3043060''>it''s</span>
  <span m=''3043230''>very</span> <span m=''3043470''>close</span> <span m=''3043800''>to</span>
  <span m=''3044260''>100%.</span> </p><p><span m=''3046700''>The</span> <span m=''3046820''>conjecture</span>
  <span m=''3047370''>is</span> <span m=''3047460''>that</span> <span m=''3047580''>as</span>
  <span m=''3047700''>n</span> <span m=''3047840''>goes</span> <span m=''3048030''>to</span>
  <span m=''3048090''>infinity,</span> <span m=''3048650''>the</span> <span m=''3048660''>probability</span>
  <span m=''3049120''>of</span> <span m=''3049200''>overlap</span> <span m=''3049620''>goes</span>
  <span m=''3049900''>to</span> <span m=''3050140''>1.</span> <span m=''3051820''>We</span>
  <span m=''3051930''>don''t</span> <span m=''3052090''>have</span> <span m=''3052190''>a</span>
  <span m=''3052230''>proof</span> <span m=''3052470''>of</span> <span m=''3052550''>that.</span>
  <span m=''3052810''>That would</span> <span m=''3052920''>be</span> <span m=''3053080''>nice</span>
  <span m=''3053340''>to</span> <span m=''3053800''>prove.</span> <span m=''3055500''>There''s</span>
  <span m=''3055830''>good</span> <span m=''3056010''>reason</span> <span m=''3056250''>to</span>
  <span m=''3056310''>believe</span> <span m=''3056770''>that''s</span> <span m=''3056980''>easy</span>
  <span m=''3057240''>to</span> <span m=''3057320''>prove</span> <span m=''3057580''>or</span>
  <span m=''3058410''>that</span> <span m=''3058550''>it''s</span> <span m=''3058680''>true,</span>
  <span m=''3058990''>let''s</span> <span m=''3059210''>say,</span> <span m=''3059460''>that</span>
  <span m=''3059830''>there</span> <span m=''3060020''>is</span> <span m=''3060100''>a</span>
  <span m=''3060180''>proof.</span> <span m=''3060500''>I</span> <span m=''3060560''>don''t</span>
  <span m=''3060750''>know</span> <span m=''3060830''>how</span> <span m=''3060960''>to</span>
  <span m=''3061090''>actually</span> <span m=''3061370''>formalize</span> <span m=''3061880''>it.</span>
  <span m=''3065310''>This</span> <span m=''3065470''>is</span> <span m=''3065580''>some</span>
  <span m=''3065950''>work</span> <span m=''3066160''>from</span> <span m=''3066350''>the</span>
  <span m=''3066750''>late</span> <span m=''3066970''>''80s.</span> </p><p><span m=''3077570''>Just</span>
  <span m=''3077780''>because</span> <span m=''3078060''>most</span> <span m=''3078420''>unfoldings</span>
  <span m=''3078830''>fail</span> <span m=''3079380''>doesn''t</span> <span m=''3079630''>mean</span>
  <span m=''3079770''>there</span> <span m=''3079910''>isn''t</span> <span m=''3080160''>one</span>
  <span m=''3080370''>unfolding</span> <span m=''3080890''>that</span> <span m=''3081050''>works.</span>
  <span m=''3082280''>If</span> <span m=''3082470''>I</span> <span m=''3082620''>were</span>
  <span m=''3082770''>to</span> <span m=''3083140''>try</span> <span m=''3083340''>to</span>
  <span m=''3083440''>prove</span> <span m=''3083820''>that</span> <span m=''3084350''>there</span>
  <span m=''3084600''>is</span> <span m=''3084700''>an</span> <span m=''3084780''>unfolding</span>
  <span m=''3085160''>that</span> <span m=''3085280''>works,</span> <span m=''3086080''>here''s</span>
  <span m=''3086390''>my</span> <span m=''3086640''>best</span> <span m=''3086970''>hope,</span>
  <span m=''3087300''>and</span> <span m=''3087470''>it</span> <span m=''3087620''>ties</span>
  <span m=''3087940''>into</span> <span m=''3088110''>some</span> <span m=''3088300''>things</span>
  <span m=''3088520''>that</span> <span m=''3088630''>we''ve</span> <span m=''3088770''>seen</span>
  <span m=''3089010''>with</span> <span m=''3089110''>tensegrities.</span> <span m=''3091420''>If</span>
  <span m=''3091530''>you</span> <span m=''3091590''>take</span> <span m=''3091800''>a</span>
  <span m=''3091920''>really</span> <span m=''3092440''>big</span> <span m=''3092800''>polyhedron,</span>
  <span m=''3094480''>which</span> <span m=''3094910''>is</span> <span m=''3095360''>the</span>
  <span m=''3095540''>case</span> <span m=''3095840''>you</span> <span m=''3096180''>worry</span>
  <span m=''3096410''>about,</span> <span m=''3097190''>and</span> <span m=''3097440''>you</span>
  <span m=''3097560''>look</span> <span m=''3097750''>at</span> <span m=''3097830''>a</span>
  <span m=''3097890''>small</span> <span m=''3098380''>portion</span> <span m=''3098740''>of</span>
  <span m=''3098870''>it,</span> <span m=''3100150''>that</span> <span m=''3100460''>portion</span>
  <span m=''3100850''>will</span> <span m=''3101000''>be</span> <span m=''3101300''>almost</span>
  <span m=''3101720''>completely</span> <span m=''3102100''>flat.</span> <span m=''3103810''>Locally,</span>
  <span m=''3104270''>this</span> <span m=''3104450''>thing</span> <span m=''3104610''>is</span>
  <span m=''3106450''>mostly</span> <span m=''3106820''>flat.</span> </p><p><span
  m=''3108450''>Instead</span> <span m=''3108800''>of</span> <span m=''3108880''>thinking</span>
  <span m=''3109130''>about</span> <span m=''3109300''>the</span> <span m=''3109380''>big</span>
  <span m=''3109560''>polyhedron,</span> <span m=''3110350''>if</span> <span m=''3110665''>we</span>
  <span m=''3110980''>at least</span> <span m=''3111340''>wanted</span> <span m=''3111630''>to</span>
  <span m=''3111720''>get</span> <span m=''3112940''>it</span> <span m=''3113040''>to</span>
  <span m=''3113130''>work</span> <span m=''3113300''>in</span> <span m=''3113380''>any</span>
  <span m=''3113540''>patch,</span> <span m=''3114350''>think</span> <span m=''3114630''>about</span>
  <span m=''3114970''>the</span> <span m=''3115060''>case</span> <span m=''3116210''>of</span>
  <span m=''3116380''>an</span> <span m=''3116630''>almost</span> <span m=''3117370''>flat</span>
  <span m=''3119150''>polyhedron.</span> <span m=''3119820''>So</span> <span m=''3119960''>it''s</span>
  <span m=''3120090''>like</span> <span m=''3120220''>a</span> <span m=''3120280''>little</span>
  <span m=''3120590''>dome.</span> <span m=''3121050''>It</span> <span m=''3121440''>has</span>
  <span m=''3121690''>boundary</span> <span m=''3122180''>now.</span> <span m=''3123000''>Makes</span>
  <span m=''3123190''>life</span> <span m=''3123360''>a</span> <span m=''3123390''>little</span>
  <span m=''3123540''>harder,</span> <span m=''3123890''>but</span> <span m=''3123930''>let''s</span>
  <span m=''3124090''>say</span> <span m=''3124170''>it''s</span> <span m=''3124300''>a</span>
  <span m=''3124360''>nice,</span> <span m=''3124600''>convex</span> <span m=''3125070''>boundary.</span>
  <span m=''3125430''>This</span> <span m=''3125620''>is</span> <span m=''3125740''>a</span>
  <span m=''3125810''>convex</span> <span m=''3126340''>dome.</span> <span m=''3127310''>It''s</span>
  <span m=''3127640''>actually</span> <span m=''3127890''>polyhedral.</span> </p><p><span
  m=''3132560''>Well,</span> <span m=''3132670''>let''s</span> <span m=''3132810''>make</span>
  <span m=''3133020''>it</span> <span m=''3133200''>super,</span> <span m=''3133690''>super</span>
  <span m=''3133860''>flat.</span> <span m=''3135170''>So</span> <span m=''3135470''>we</span>
  <span m=''3135590''>have</span> <span m=''3135780''>this</span> <span m=''3136500''>z-coordinate.</span>
  <span m=''3137480''>Scale</span> <span m=''3138010''>z</span> <span m=''3138570''>to</span>
  <span m=''3139110''>squash</span> <span m=''3139700''>it</span> <span m=''3139790''>down</span>
  <span m=''3140060''>into</span> <span m=''3140240''>the</span> <span m=''3140350''>plane.</span>
  <span m=''3140980''>What''s</span> <span m=''3141180''>nice</span> <span m=''3141440''>about</span>
  <span m=''3141670''>this</span> <span m=''3141830''>is</span> <span m=''3141940''>then</span>
  <span m=''3142140''>you</span> <span m=''3142280''>can</span> <span m=''3142410''>think</span>
  <span m=''3142600''>of</span> <span m=''3142680''>your</span> <span m=''3142800''>convex</span>
  <span m=''3143180''>polyhedron</span> <span m=''3144240''>just</span> <span m=''3144540''>as</span>
  <span m=''3145770''>some</span> <span m=''3146190''>drawing</span> <span m=''3147280''>in</span>
  <span m=''3147360''>the</span> <span m=''3147450''>plane.</span> <span m=''3148830''>So</span>
  <span m=''3148960''>here</span> <span m=''3149240''>maybe</span> <span m=''3149560''>is</span>
  <span m=''3149690''>my</span> <span m=''3150260''>convex</span> <span m=''3150660''>polyhedron.</span>
  </p><p><span m=''3151220''>Now,</span> <span m=''3151370''>in</span> <span m=''3151440''>fact,</span>
  <span m=''3151860''>each</span> <span m=''3152050''>of</span> <span m=''3152120''>these</span>
  <span m=''3152310''>vertices</span> <span m=''3152740''>is</span> <span m=''3152870''>lifted</span>
  <span m=''3153230''>a</span> <span m=''3153310''>tiny</span> <span m=''3153690''>amount,</span>
  <span m=''3154120''>some</span> <span m=''3154310''>infinitesimal</span> <span m=''3154930''>amount,</span>
  <span m=''3155180''>but</span> <span m=''3155280''>you</span> <span m=''3155370''>can</span>
  <span m=''3155510''>think</span> <span m=''3155690''>of</span> <span m=''3155800''>it</span>
  <span m=''3156320''>in</span> <span m=''3156470''>the</span> <span m=''3156560''>plane.</span>
  <span m=''3158570''>These</span> <span m=''3158820''>are</span> <span m=''3158980''>convex</span>
  <span m=''3159820''>faces.</span> <span m=''3160220''>We</span> <span m=''3160370''>know</span>
  <span m=''3160580''>this</span> <span m=''3160820''>thing</span> <span m=''3160970''>can</span>
  <span m=''3161110''>be</span> <span m=''3161210''>lifted</span> <span m=''3161520''>to</span>
  <span m=''3161610''>a</span> <span m=''3161650''>convex</span> <span m=''3162010''>polyhedron.</span>
  <span m=''3162490''>That</span> <span m=''3162700''>lifting</span> <span m=''3163940''>is</span>
  <span m=''3164250''>a</span> <span m=''3164730''>positive</span> <span m=''3165320''>stress</span>
  <span m=''3165840''>on</span> <span m=''3165980''>all</span> <span m=''3166160''>the</span>
  <span m=''3166330''>edges</span> <span m=''3166710''>except</span> <span m=''3167020''>the</span>
  <span m=''3167090''>boundary</span> <span m=''3167420''>edges.</span> <span m=''3168380''>Maybe</span>
  <span m=''3168790''>that</span> <span m=''3169030''>stress</span> <span m=''3169600''>gives</span>
  <span m=''3169750''>you</span> <span m=''3169920''>some</span> <span m=''3170380''>useful</span>
  <span m=''3170700''>structure.</span> <span m=''3171650''>If</span> <span m=''3171740''>there''s</span>
  <span m=''3171910''>any</span> <span m=''3172110''>hope</span> <span m=''3172330''>of</span>
  <span m=''3172400''>this</span> <span m=''3172540''>working,</span> <span m=''3173430''>that</span>
  <span m=''3173650''>structure</span> <span m=''3173970''>better</span> <span m=''3174210''>be</span>
  <span m=''3174320''>useful,</span> <span m=''3174730''>but</span> <span m=''3174880''>I
  don''t</span> <span m=''3174960''>know</span> <span m=''3175180''>how</span> <span
  m=''3175280''>to</span> <span m=''3175350''>use</span> <span m=''3175570''>it.</span>
  </p><p><span m=''3176680''>But</span> <span m=''3176820''>in</span> <span m=''3176900''>particular,</span>
  <span m=''3177440''>open</span> <span m=''3177680''>question.</span> <span m=''3178640''>If
  I</span> <span m=''3178750''>give</span> <span m=''3178980''>you</span> <span m=''3179270''>a</span>
  <span m=''3180140''>super</span> <span m=''3180490''>shallow,</span> <span m=''3180790''>arbitrarily</span>
  <span m=''3181430''>shallow,</span> <span m=''3182220''>convex</span> <span m=''3182640''>polyhedral</span>
  <span m=''3183110''>dome,</span> <span m=''3184040''>can</span> <span m=''3184240''>it</span>
  <span m=''3184370''>be</span> <span m=''3184480''>unfolded?</span> <span m=''3186540''>I</span>
  <span m=''3186860''>don''t</span> <span m=''3187030''>know.</span> <span m=''3191290''>Maybe</span>
  <span m=''3191410''>we''ll</span> <span m=''3191660''>work</span> <span m=''3191850''>on</span>
  <span m=''3192000''>it</span> <span m=''3192720''>in</span> <span m=''3192890''>the</span>
  <span m=''3193150''>problem</span> <span m=''3193410''>session.</span> <span m=''3196700''>Haven''t</span>
  <span m=''3196870''>thought</span> <span m=''3197050''>about</span> <span m=''3197230''>it</span>
  <span m=''3197320''>for</span> <span m=''3197430''>awhile.</span> </p><p><span m=''3200890''>That''s</span>
  <span m=''3201070''>if</span> <span m=''3201160''>you</span> <span m=''3201280''>want</span>
  <span m=''3201430''>to</span> <span m=''3201480''>solve</span> <span m=''3201760''>everything.</span>
  <span m=''3203840''>What</span> <span m=''3203980''>if</span> <span m=''3204080''>you</span>
  <span m=''3204190''>just</span> <span m=''3204390''>want</span> <span m=''3204520''>to</span>
  <span m=''3204580''>solve</span> <span m=''3204860''>some</span> <span m=''3205010''>special</span>
  <span m=''3205380''>cases?</span> <span m=''3207580''>That</span> <span m=''3207740''>is</span>
  <span m=''3207880''>a</span> <span m=''3207940''>special</span> <span m=''3208290''>case</span>
  <span m=''3208560''>motivated</span> <span m=''3209110''>by</span> <span m=''3209430''>the</span>
  <span m=''3209530''>general</span> <span m=''3209850''>case.</span> <span m=''3211900''>Well,</span>
  <span m=''3212900''>you</span> <span m=''3213190''>can</span> <span m=''3213320''>solve</span>
  <span m=''3213640''>the</span> <span m=''3213720''>case</span> <span m=''3214080''>of</span>
  <span m=''3214370''>a</span> <span m=''3214460''>polyhedron</span> <span m=''3214920''>with</span>
  <span m=''3215040''>at</span> <span m=''3215120''>most</span> <span m=''3215340''>six</span>
  <span m=''3215640''>vertices.</span> <span m=''3216130''>That''s</span> <span m=''3216370''>as</span>
  <span m=''3216480''>far</span> <span m=''3216700''>as</span> <span m=''3216830''>we''ve</span>
  <span m=''3216990''>gotten.</span> </p><p><span m=''3218950''>You</span> <span m=''3219270''>can</span>
  <span m=''3219420''>solve</span> <span m=''3219810''>some</span> <span m=''3220050''>simple</span>
  <span m=''3220350''>examples</span> <span m=''3220910''>like</span> <span m=''3221250''>pyramids</span>
  <span m=''3222210''>if</span> <span m=''3222440''>you</span> <span m=''3222540''>take</span>
  <span m=''3223410''>any</span> <span m=''3223630''>convex</span> <span m=''3224110''>polygon,</span>
  <span m=''3226210''>doesn''t</span> <span m=''3226380''>have</span> <span m=''3226530''>to</span>
  <span m=''3226620''>be</span> <span m=''3226780''>irregular or</span> <span m=''3227200''>anything,</span>
  <span m=''3228000''>and</span> <span m=''3228080''>then</span> <span m=''3228170''>you</span>
  <span m=''3228240''>take</span> <span m=''3228420''>a</span> <span m=''3228480''>point</span>
  <span m=''3228910''>and</span> <span m=''3229050''>you</span> <span m=''3229130''>take</span>
  <span m=''3229340''>the</span> <span m=''3229420''>convex</span> <span m=''3229830''>hull.</span>
  <span m=''3232780''>So that''s</span> <span m=''3233040''>a</span> <span m=''3233160''>polyhedron</span>
  <span m=''3234160''>and</span> <span m=''3234320''>it</span> <span m=''3234410''>unfolds.</span>
  <span m=''3235360''>How</span> <span m=''3235600''>does</span> <span m=''3235740''>it</span>
  <span m=''3235820''>unfold?</span> <span m=''3236580''>Any</span> <span m=''3236810''>suggestions</span>
  <span m=''3237340''>where</span> <span m=''3237460''>to</span> <span m=''3237540''>cut?</span>
  <span m=''3243670''>How?</span> </p><p><span m=''3245954''>AUDIENCE: From</span>
  <span m=''3246445''>the</span> <span m=''3246936''>top?</span> </p><p><span m=''3247430''>PROFESSOR:
  From</span> <span m=''3247710''>the</span> <span m=''3247820''>top.</span> <span
  m=''3248870''>Yeah,</span> <span m=''3249340''>just</span> <span m=''3249650''>cut</span>
  <span m=''3249850''>here.</span> <span m=''3250500''>Here,</span> <span m=''3250610''>we''re</span>
  <span m=''3250700''>only</span> <span m=''3250880''>allowed</span> <span m=''3251080''>to</span>
  <span m=''3251140''>cut</span> <span m=''3251260''>along</span> <span m=''3251510''>edges.</span>
  <span m=''3252680''>This</span> <span m=''3252870''>is</span> <span m=''3253000''>called</span>
  <span m=''3253370''>the</span> <span m=''3253580''>volcano</span> <span m=''3254420''>unfolding.</span>
  <span m=''3257021''>What do</span> <span m=''3257490''>we</span> <span m=''3257670''>have?</span>
  <span m=''3258010''>Like</span> <span m=''3258180''>that,</span> <span m=''3259550''>and</span>
  <span m=''3259730''>then</span> <span m=''3260870''>there''s</span> <span m=''3261020''>just</span>
  <span m=''3261190''>a</span> <span m=''3261230''>bunch</span> <span m=''3261440''>of</span>
  <span m=''3261490''>triangles.</span> <span m=''3263310''>What''s</span> <span m=''3263570''>nice</span>
  <span m=''3263860''>about</span> <span m=''3264160''>the</span> <span m=''3264240''>volcano</span>
  <span m=''3264760''>unfolding</span> <span m=''3265340''>is</span> <span m=''3268080''>if</span>
  <span m=''3268250''>you</span> <span m=''3268370''>look</span> <span m=''3268550''>at</span>
  <span m=''3268650''>these</span> <span m=''3269170''>perpendicular</span> <span
  m=''3269770''>strips</span> <span m=''3270420''>here,</span> <span m=''3271370''>those</span>
  <span m=''3271570''>triangles</span> <span m=''3271980''>will</span> <span m=''3272070''>fit</span>
  <span m=''3272290''>inside</span> <span m=''3272700''>those</span> <span m=''3272870''>perpendicular</span>
  <span m=''3273430''>strips,</span> <span m=''3274600''>and</span> <span m=''3276410''>therefore</span>
  <span m=''3276660''>they</span> <span m=''3276760''>won''t</span> <span m=''3276960''>intersect</span>
  <span m=''3277350''>each</span> <span m=''3277490''>other</span> <span m=''3277630''>because</span>
  <span m=''3277810''>these</span> <span m=''3277900''>strips</span> <span m=''3278220''>don''t</span>
  <span m=''3278370''>intersect</span> <span m=''3278830''>each</span> <span m=''3278980''>other.</span>
  <span m=''3279370''>You could</span> <span m=''3279470''>probably</span> <span m=''3279820''>even</span>
  <span m=''3280110''>continuously</span> <span m=''3280620''>bloom</span> <span m=''3280880''>this,</span>
  <span m=''3281080''>no</span> <span m=''3281190''>problem.</span> <span m=''3281940''>So
  a</span> <span m=''3282080''>very</span> <span m=''3282450''>simple</span> <span
  m=''3282740''>example,</span> <span m=''3283630''>easy</span> <span m=''3283970''>to</span>
  <span m=''3284090''>do</span> <span m=''3284330''>with</span> <span m=''3284520''>volcanoes.</span>
  <span m=''3286050''>That''s</span> <span m=''3286320''>the</span> <span m=''3286480''>so-called</span>
  <span m=''3286920''>pyramid.</span> </p><p><span m=''3291030''>Prism,</span> <span
  m=''3292536''>a</span> <span m=''3292990''>little</span> <span m=''3293350''>bit</span>
  <span m=''3293510''>more</span> <span m=''3293690''>interesting,</span> <span m=''3294250''>but</span>
  <span m=''3294745''>not</span> <span m=''3295240''>by</span> <span m=''3295330''>much.</span>
  <span m=''3296240''>You</span> <span m=''3296400''>take</span> <span m=''3297490''>some</span>
  <span m=''3297810''>polygon.</span> <span m=''3299791''>Again,</span> <span m=''3300350''>doesn''t</span>
  <span m=''3300550''>have</span> <span m=''3300690''>to</span> <span m=''3300770''>be</span>
  <span m=''3300900''>regular,</span> <span m=''3302010''>but</span> <span m=''3302210''>you</span>
  <span m=''3302280''>take</span> <span m=''3302470''>two</span> <span m=''3302600''>copies</span>
  <span m=''3303010''>of</span> <span m=''3303180''>it</span> <span m=''3303600''>vertically</span>
  <span m=''3304060''>offset,</span> <span m=''3305130''>take</span> <span m=''3305310''>the</span>
  <span m=''3305380''>convex</span> <span m=''3305760''>hull.</span> <span m=''3308600''>This</span>
  <span m=''3308870''>one</span> <span m=''3309020''>you</span> <span m=''3309160''>can</span>
  <span m=''3309570''>cut</span> <span m=''3312990''>in</span> <span m=''3313210''>two</span>
  <span m=''3313390''>ways.</span> <span m=''3314510''>You</span> <span m=''3314670''>could</span>
  <span m=''3314800''>do</span> <span m=''3314940''>a</span> <span m=''3314960''>volcano-like</span>
  <span m=''3315690''>thing</span> <span m=''3315920''>where</span> <span m=''3316050''>you</span>
  <span m=''3316170''>cut</span> <span m=''3316400''>all</span> <span m=''3316670''>the</span>
  <span m=''3317380''>vertical</span> <span m=''3317720''>edges</span> <span m=''3320350''>and</span>
  <span m=''3320580''>then</span> <span m=''3320740''>you</span> <span m=''3320910''>cut</span>
  <span m=''3321270''>all</span> <span m=''3321690''>but</span> <span m=''3321890''>one</span>
  <span m=''3322460''>of</span> <span m=''3322660''>the</span> <span m=''3322960''>bottom</span>
  <span m=''3323280''>edges.</span> <span m=''3324860''>Then</span> <span m=''3325030''>you''ll</span>
  <span m=''3325280''>have</span> <span m=''3325590''>basically</span> <span m=''3325980''>a</span>
  <span m=''3326030''>volcano</span> <span m=''3328800''>with</span> <span m=''3329150''>little</span>
  <span m=''3329530''>rectangles</span> <span m=''3330280''>hanging</span> <span m=''3330580''>off</span>
  <span m=''3330760''>all</span> <span m=''3330930''>the</span> <span m=''3331000''>sides.</span>
  <span m=''3333420''>And</span> <span m=''3333660''>then</span> <span m=''3334700''>there''s</span>
  <span m=''3334920''>another</span> <span m=''3335210''>copy,</span> <span m=''3335550''>the</span>
  <span m=''3335650''>bottom</span> <span m=''3336470''>copy</span> <span m=''3336770''>of</span>
  <span m=''3336850''>this</span> <span m=''3337050''>face,</span> <span m=''3337840''>and</span>
  <span m=''3338070''>it</span> <span m=''3338150''>just</span> <span m=''3338350''>hangs</span>
  <span m=''3338570''>out</span> <span m=''3338670''>over</span> <span m=''3338840''>here,</span>
  <span m=''3339160''>and</span> <span m=''3339230''>you</span> <span m=''3339320''>could</span>
  <span m=''3339460''>prove</span> <span m=''3339650''>that that</span> <span m=''3340020''>won''t</span>
  <span m=''3340230''>hit</span> <span m=''3340410''>anybody</span> <span m=''3341090''>in</span>
  <span m=''3341230''>this</span> <span m=''3341390''>very</span> <span m=''3341560''>simple</span>
  <span m=''3342300''>situation.</span> </p><p><span m=''3343250''>There''s</span>
  <span m=''3343420''>another</span> <span m=''3343730''>unfolding,</span> <span m=''3344160''>though,</span>
  <span m=''3345292''>that</span> <span m=''3345730''>I</span> <span m=''3345840''>mention</span>
  <span m=''3346260''>because</span> <span m=''3346570''>it''s</span> <span m=''3346840''>useful</span>
  <span m=''3347110''>for</span> <span m=''3347270''>other</span> <span m=''3347430''>things,</span>
  <span m=''3350080''>and it''s</span> <span m=''3350200''>so-called</span> <span
  m=''3350620''>band</span> <span m=''3350940''>unfolding.</span> <span m=''3351905''>Band</span>
  <span m=''3352630''>unfolding,</span> <span m=''3356860''>I</span> <span m=''3356940''>want</span>
  <span m=''3357080''>to</span> <span m=''3357150''>keep</span> <span m=''3357530''>intact</span>
  <span m=''3358220''>the</span> <span m=''3358890''>radial</span> <span m=''3359220''>band</span>
  <span m=''3359530''>around</span> <span m=''3359810''>the</span> <span m=''3359890''>thing,</span>
  <span m=''3361970''>maybe</span> <span m=''3362360''>like</span> <span m=''3362670''>this.</span>
  <span m=''3364266''>What</span> <span m=''3364764''>do I</span> <span m=''3365262''>want
  to</span> <span m=''3365760''>do to</span> <span m=''3366310''>keep</span> <span
  m=''3366530''>that</span> <span m=''3366730''>edge?</span> <span m=''3367600''>Cut,</span>
  <span m=''3368720''>cut.</span> <span m=''3369450''>So</span> <span m=''3369810''>I</span>
  <span m=''3369930''>cut</span> <span m=''3370100''>on</span> <span m=''3370210''>all</span>
  <span m=''3370410''>the</span> <span m=''3370500''>top</span> <span m=''3370750''>edges</span>
  <span m=''3371000''>except</span> <span m=''3371320''>one,</span> <span m=''3371600''>I</span>
  <span m=''3371650''>cut</span> <span m=''3371850''>on</span> <span m=''3371960''>all</span>
  <span m=''3372080''>the</span> <span m=''3372150''>bottom</span> <span m=''3372490''>edges</span>
  <span m=''3372780''>except</span> <span m=''3373100''>the</span> <span m=''3373170''>same</span>
  <span m=''3373430''>one,</span> <span m=''3373700''>and</span> <span m=''3373780''>then</span>
  <span m=''3373910''>I</span> <span m=''3373990''>also</span> <span m=''3374230''>cut</span>
  <span m=''3374450''>this</span> <span m=''3375110''>vertical</span> <span m=''3375470''>edge.</span>
  <span m=''3377110''>So</span> <span m=''3377350''>what</span> <span m=''3377490''>I</span>
  <span m=''3377560''>should</span> <span m=''3377810''>get</span> <span m=''3378930''>is</span>
  <span m=''3379680''>I</span> <span m=''3379750''>get</span> <span m=''3379950''>my</span>
  <span m=''3380090''>top</span> <span m=''3380420''>face,</span> <span m=''3381560''>then</span>
  <span m=''3381690''>I</span> <span m=''3381740''>get</span> <span m=''3381880''>a</span>
  <span m=''3381930''>rectangle,</span> <span m=''3382420''>then</span> <span m=''3383740''>I</span>
  <span m=''3383810''>get</span> <span m=''3384020''>the</span> <span m=''3384290''>band</span>
  <span m=''3385210''>that</span> <span m=''3385320''>goes</span> <span m=''3385530''>around</span>
  <span m=''3385830''>the</span> <span m=''3385930''>outside,</span> <span m=''3387020''>and</span>
  <span m=''3387140''>then</span> <span m=''3387270''>I</span> <span m=''3387320''>get</span>
  <span m=''3387480''>another</span> <span m=''3387820''>copy</span> <span m=''3389050''>of</span>
  <span m=''3389270''>my</span> <span m=''3390590''>shape,</span> <span m=''3390950''>the</span>
  <span m=''3391070''>bottom</span> <span m=''3391370''>side.</span> <span m=''3392760''>This</span>
  <span m=''3392830''>is</span> <span m=''3392940''>what</span> <span m=''3393060''>we</span>
  <span m=''3393170''>call</span> <span m=''3393460''>band</span> <span m=''3393710''>unfolding.</span>
  </p><p><span m=''3396890''>There''s</span> <span m=''3397100''>some</span> <span
  m=''3397140''>nice</span> <span m=''3397360''>theorems</span> <span m=''3397640''>about</span>
  <span m=''3397890''>band</span> <span m=''3398110''>unfoldings</span> <span m=''3399260''>working</span>
  <span m=''3399680''>out.</span> <span m=''3404440''>Let</span> <span m=''3404770''>me</span>
  <span m=''3404900''>get</span> <span m=''3405110''>to</span> <span m=''3405770''>more</span>
  <span m=''3406020''>interesting</span> <span m=''3406410''>polyhedra.</span> <span
  m=''3409780''>These</span> <span m=''3409930''>are</span> <span m=''3410010''>some</span>
  <span m=''3410180''>pretty</span> <span m=''3410540''>simple</span> <span m=''3411160''>cases,</span>
  <span m=''3411650''>but</span> <span m=''3412950''>we</span> <span m=''3413050''>don''t</span>
  <span m=''3413210''>know</span> <span m=''3413350''>very</span> <span m=''3413540''>much</span>
  <span m=''3414190''>on</span> <span m=''3414310''>the</span> <span m=''3414390''>positive</span>
  <span m=''3414780''>side.</span> </p><p><span m=''3425400''>Prismoid.</span> <span
  m=''3433000''>Suppose</span> <span m=''3433400''>you</span> <span m=''3433510''>take</span>
  <span m=''3434240''>a</span> <span m=''3434330''>polygon,</span> <span m=''3437310''>and</span>
  <span m=''3437500''>you</span> <span m=''3437610''>basically</span> <span m=''3438590''>inset</span>
  <span m=''3439060''>it.</span> <span m=''3440480''>So</span> <span m=''3440640''>I</span>
  <span m=''3440700''>want</span> <span m=''3440940''>to</span> <span m=''3441000''>make</span>
  <span m=''3441730''>a</span> <span m=''3441850''>new</span> <span m=''3442050''>version</span>
  <span m=''3442380''>of</span> <span m=''3442440''>the</span> <span m=''3442520''>polygon</span>
  <span m=''3444400''>where</span> <span m=''3444750''>all</span> <span m=''3444980''>of</span>
  <span m=''3445080''>the</span> <span m=''3445230''>angles</span> <span m=''3445960''>match,</span>
  <span m=''3450840''>so</span> <span m=''3451040''>these</span> <span m=''3451210''>edges</span>
  <span m=''3451490''>are</span> <span m=''3451600''>parallel</span> <span m=''3452100''>to</span>
  <span m=''3452220''>each</span> <span m=''3452370''>other.</span> <span m=''3452760''>I</span>
  <span m=''3452860''>think,</span> <span m=''3452930''>actually,</span> <span m=''3453200''>the</span>
  <span m=''3453330''>lengths</span> <span m=''3453580''>can</span> <span m=''3453720''>change.</span>
  <span m=''3456170''>And</span> <span m=''3456640''>then</span> <span m=''3456770''>you</span>
  <span m=''3456840''>take</span> <span m=''3457000''>the</span> <span m=''3457080''>convex</span>
  <span m=''3457460''>hull.</span> </p><p><span m=''3460790''>These</span> <span m=''3461030''>unfold</span>
  <span m=''3462060''>with</span> <span m=''3462360''>the</span> <span m=''3462420''>volcano</span>
  <span m=''3462900''>unfolding.</span> <span m=''3466190''>It''s</span> <span m=''3466300''>a</span>
  <span m=''3466340''>little</span> <span m=''3466520''>more</span> <span m=''3466700''>subtle</span>
  <span m=''3467000''>to</span> <span m=''3467070''>prove</span> <span m=''3467440''>but</span>
  <span m=''3467690''>it''s</span> <span m=''3467870''>proved</span> <span m=''3469490''>in</span>
  <span m=''3469620''>the</span> <span m=''3469700''>textbook.</span> <span m=''3474720''>Edges</span>
  <span m=''3475080''>have</span> <span m=''3475190''>to</span> <span m=''3475300''>stay</span>
  <span m=''3475500''>parallel.</span> <span m=''3477070''>I</span> <span m=''3477110''>think</span>
  <span m=''3478200''>that</span> <span m=''3478370''>might</span> <span m=''3478680''>force</span>
  <span m=''3479300''>something.</span> <span m=''3479870''>I''m</span> <span m=''3479980''>not</span>
  <span m=''3480150''>quite</span> <span m=''3480330''>sure,</span> <span m=''3480590''>but</span>
  <span m=''3480710''>the</span> <span m=''3480800''>constraints</span> <span m=''3481200''>are</span>
  <span m=''3481250''>that the</span> <span m=''3481440''>edges</span> <span m=''3481610''>have</span>
  <span m=''3481720''>to</span> <span m=''3481800''>be</span> <span m=''3481910''>parallel</span>
  <span m=''3482300''>and the</span> <span m=''3482390''>angles</span> <span m=''3482670''>have</span>
  <span m=''3482800''>to</span> <span m=''3482890''>be</span> <span m=''3483020''>equal.</span>
  </p><p><span m=''3488370''>Dome.</span> <span m=''3489660''>Dome</span> <span m=''3489960''>is</span>
  <span m=''3490100''>actually</span> <span m=''3490470''>in</span> <span m=''3490560''>some</span>
  <span m=''3490850''>ways</span> <span m=''3491070''>simpler.</span> <span m=''3493160''>You</span>
  <span m=''3496700''>take</span> <span m=''3496930''>some</span> <span m=''3497200''>base,</span>
  <span m=''3499170''>and</span> <span m=''3499360''>then</span> <span m=''3499500''>I</span>
  <span m=''3499540''>want</span> <span m=''3499730''>a</span> <span m=''3499770''>whole</span>
  <span m=''3499980''>bunch</span> <span m=''3500190''>of</span> <span m=''3500280''>faces</span>
  <span m=''3500720''>that</span> <span m=''3500850''>all</span> <span m=''3501080''>touch</span>
  <span m=''3501370''>the</span> <span m=''3501450''>base.</span> <span m=''3502500''>So</span>
  <span m=''3502720''>in</span> <span m=''3502830''>general,</span> <span m=''3503180''>it''s</span>
  <span m=''3503320''>going</span> <span m=''3503430''>to</span> <span m=''3503500''>be</span>
  <span m=''3503650''>like</span> <span m=''3503820''>a</span> <span m=''3503900''>tree</span>
  <span m=''3504480''>of</span> <span m=''3505820''>faces,</span> <span m=''3506290''>something</span>
  <span m=''3506610''>like</span> <span m=''3506810''>this.</span> <span m=''3508710''>Every</span>
  <span m=''3509030''>face</span> <span m=''3509350''>has</span> <span m=''3509520''>to</span>
  <span m=''3509610''>touch</span> <span m=''3509830''>an</span> <span m=''3509910''>edge</span>
  <span m=''3510120''>of</span> <span m=''3510180''>the</span> <span m=''3510270''>base.</span>
  <span m=''3511840''>These</span> <span m=''3512050''>also</span> <span m=''3512380''>unfold,</span>
  <span m=''3513050''>and</span> <span m=''3513440''>also</span> <span m=''3514000''>with</span>
  <span m=''3514080''>a</span> <span m=''3514120''>volcano.</span> <span m=''3517060''>This</span>
  <span m=''3517170''>is</span> <span m=''3517240''>proved</span> <span m=''3517670''>also</span>
  <span m=''3518140''>in</span> <span m=''3518320''>the</span> <span m=''3518410''>textbook.</span>
  <span m=''3520490''>Both</span> <span m=''3520740''>results</span> <span m=''3521080''>are</span>
  <span m=''3521150''>by</span> <span m=''3521540''>Joe</span> <span m=''3522000''>O''Rourke.</span>
  </p><p><span m=''3525650''>Prismatoid.</span> <span m=''3527380''>This</span> <span
  m=''3527610''>is</span> <span m=''3527740''>the</span> <span m=''3527850''>coolest</span>
  <span m=''3529020''>special</span> <span m=''3529380''>case</span> <span m=''3529790''>I''m</span>
  <span m=''3529870''>going</span> <span m=''3529950''>to</span> <span m=''3530010''>talk</span>
  <span m=''3530260''>about,</span> <span m=''3531710''>the</span> <span m=''3531770''>most</span>
  <span m=''3532070''>interesting.</span> <span m=''3533380''>I</span> <span m=''3533510''>take</span>
  <span m=''3534050''>some</span> <span m=''3534400''>convex</span> <span m=''3534830''>polygon,</span>
  <span m=''3536820''>and</span> <span m=''3537000''>then</span> <span m=''3537800''>in</span>
  <span m=''3537950''>a parallel</span> <span m=''3538300''>offset,</span> <span m=''3539340''>I</span>
  <span m=''3539430''>take</span> <span m=''3539660''>some</span> <span m=''3539850''>other</span>
  <span m=''3540060''>convex</span> <span m=''3540690''>polygon--</span> <span m=''3546520''>no</span>
  <span m=''3546780''>relation</span> <span m=''3547180''>to</span> <span m=''3547290''>each</span>
  <span m=''3547450''>other</span> <span m=''3547660''>except</span> <span m=''3548080''>that
  they''re in</span> <span m=''3548280''>parallel</span> <span m=''3548650''>planes--</span>
  <span m=''3549460''>and</span> <span m=''3549600''>then</span> <span m=''3549710''>I</span>
  <span m=''3549770''>take</span> <span m=''3549950''>the</span> <span m=''3550030''>convex</span>
  <span m=''3550390''>hull,</span> <span m=''3554870''>something</span> <span m=''3555210''>like</span>
  <span m=''3555370''>that.</span> <span m=''3562160''>This</span> <span m=''3562370''>one,</span>
  <span m=''3562600''>sadly,</span> <span m=''3562990''>is</span> <span m=''3563110''>open.</span>
  </p><p><span m=''3567250''>Now,</span> <span m=''3567410''>what</span> <span m=''3567560''>we</span>
  <span m=''3567680''>do</span> <span m=''3567870''>know,</span> <span m=''3568280''>and
  this</span> <span m=''3568560''>is</span> <span m=''3568730''>related</span> <span
  m=''3569110''>to</span> <span m=''3569210''>the</span> <span m=''3569320''>band</span>
  <span m=''3569640''>unfolding,</span> <span m=''3571980''>if</span> <span m=''3572260''>you</span>
  <span m=''3572440''>look</span> <span m=''3572660''>at</span> <span m=''3572810''>the</span>
  <span m=''3572920''>band</span> <span m=''3574220''>around</span> <span m=''3576620''>the</span>
  <span m=''3576710''>sides</span> <span m=''3577320''>of</span> <span m=''3577440''>this</span>
  <span m=''3577600''>prismatoid</span> <span m=''3578650''>and</span> <span m=''3578790''>just</span>
  <span m=''3579080''>unfold</span> <span m=''3579410''>that</span> <span m=''3579680''>by</span>
  <span m=''3579810''>itself,</span> <span m=''3581140''>that</span> <span m=''3581460''>will</span>
  <span m=''3581680''>not</span> <span m=''3581940''>self</span> <span m=''3582180''>intersect,</span>
  <span m=''3583930''>and</span> <span m=''3584050''>that''s</span> <span m=''3584310''>quite</span>
  <span m=''3584620''>nontrivial,</span> <span m=''3585160''>the</span> <span m=''3585230''>proof.</span>
  <span m=''3585820''>But</span> <span m=''3585960''>if</span> <span m=''3586050''>you</span>
  <span m=''3586130''>just</span> <span m=''3586550''>unroll</span> <span m=''3587310''>the</span>
  <span m=''3587390''>side</span> <span m=''3587720''>faces,</span> <span m=''3589040''>they</span>
  <span m=''3589290''>will</span> <span m=''3589790''>wander</span> <span m=''3590130''>around</span>
  <span m=''3590460''>but</span> <span m=''3590610''>they</span> <span m=''3590730''>won''t</span>
  <span m=''3591240''>hit</span> <span m=''3591440''>themselves.</span> <span m=''3593170''>The</span>
  <span m=''3593280''>only</span> <span m=''3593530''>remaining</span> <span m=''3593830''>problem</span>
  <span m=''3594140''>is,</span> <span m=''3594300''>where</span> <span m=''3594540''>does</span>
  <span m=''3594690''>the</span> <span m=''3594780''>top</span> <span m=''3595070''>and</span>
  <span m=''3595130''>the</span> <span m=''3595200''>bottom</span> <span m=''3595490''>face</span>
  <span m=''3595790''>go?</span> <span m=''3597960''>I</span> <span m=''3598000''>think</span>
  <span m=''3598240''>I</span> <span m=''3598270''>have</span> <span m=''3598470''>an</span>
  <span m=''3598520''>example</span> <span m=''3598990''>where</span> <span m=''3599150''>that''s</span>
  <span m=''3600110''>a</span> <span m=''3600240''>little</span> <span m=''3600570''>dicey.</span>
  </p><p><span m=''3601920''>Prism.</span> <span m=''3604060''>Prismoid.</span> <span
  m=''3604860''>That</span> <span m=''3604920''>gives</span> <span m=''3605110''>you</span>
  <span m=''3605350''>an</span> <span m=''3605460''>answer</span> <span m=''3605700''>to</span>
  <span m=''3605830''>your</span> <span m=''3606610''>offset.</span> <span m=''3607120''>So</span>
  <span m=''3607270''>they</span> <span m=''3607400''>can</span> <span m=''3607620''>be</span>
  <span m=''3608760''>sheared</span> <span m=''3609140''>away</span> <span m=''3609470''>from</span>
  <span m=''3609680''>each</span> <span m=''3609840''>other,</span> <span m=''3610070''>but</span>
  <span m=''3611280''>this</span> <span m=''3611500''>is</span> <span m=''3611630''>a</span>
  <span m=''3611750''>prismoid.</span> <span m=''3612840''>All</span> <span m=''3613030''>of</span>
  <span m=''3613200''>the</span> <span m=''3613510''>sides</span> <span m=''3613780''>are</span>
  <span m=''3613840''>parallel</span> <span m=''3614100''>and</span> <span m=''3614360''>the</span>
  <span m=''3614470''>angles</span> <span m=''3614780''>match,</span> <span m=''3615055''>a</span>
  <span m=''3615330''>and</span> <span m=''3615650''>b.</span> <span m=''3617420''>Here</span>
  <span m=''3617830''>is</span> <span m=''3618260''>the</span> <span m=''3618560''>volcano</span>
  <span m=''3619110''>unfolding</span> <span m=''3620270''>of</span> <span m=''3620750''>the</span>
  <span m=''3620970''>prismoid,</span> <span m=''3622900''>and</span> <span m=''3624050''>here''s</span>
  <span m=''3624320''>showing</span> <span m=''3624660''>that</span> <span m=''3624780''>it''s</span>
  <span m=''3624920''>not</span> <span m=''3625260''>so</span> <span m=''3625540''>obvious</span>
  <span m=''3626240''>that</span> <span m=''3626360''>it</span> <span m=''3626480''>always</span>
  <span m=''3626730''>works.</span> <span m=''3627080''>If</span> <span m=''3627180''>you''re</span>
  <span m=''3627280''>not</span> <span m=''3627460''>careful</span> <span m=''3627930''>where</span>
  <span m=''3628210''>you</span> <span m=''3628350''>put</span> <span m=''3628590''>the</span>
  <span m=''3628700''>top</span> <span m=''3629150''>face--</span> <span m=''3630040''>so</span>
  <span m=''3630170''>this</span> <span m=''3630330''>is a</span> <span m=''3630480''>on</span>
  <span m=''3630880''>top</span> <span m=''3631110''>of b</span> <span m=''3631240''>in</span>
  <span m=''3632144''>plan--</span> <span m=''3633900''>you</span> <span m=''3634060''>could</span>
  <span m=''3634230''>attach</span> <span m=''3634550''>a</span> <span m=''3634740''>to</span>
  <span m=''3635060''>any</span> <span m=''3635110''>of</span> <span m=''3635730''>these</span>
  <span m=''3636000''>faces.</span> <span m=''3636860''>You</span> <span m=''3636980''>have</span>
  <span m=''3637220''>to</span> <span m=''3637340''>choose</span> <span m=''3637710''>one</span>
  <span m=''3637870''>that''s</span> <span m=''3638030''>not</span> <span m=''3638250''>so</span>
  <span m=''3639070''>inside</span> <span m=''3639415''>because</span> <span m=''3639760''>it''s</span>
  <span m=''3640010''>overlapping</span> <span m=''3640520''>here.</span> <span m=''3641540''>But</span>
  <span m=''3641650''>if</span> <span m=''3641700''>you</span> <span m=''3641770''>choose</span>
  <span m=''3642130''>the</span> <span m=''3642280''>outermost</span> <span m=''3642750''>one,</span>
  <span m=''3642920''>it</span> <span m=''3643000''>works</span> <span m=''3643430''>and
  you</span> <span m=''3643890''>can prove</span> <span m=''3644030''>that.</span>
  </p><p><span m=''3645890''>This</span> <span m=''3646130''>is</span> <span m=''3646340''>the</span>
  <span m=''3648580''>dome.</span> <span m=''3651490''>You</span> <span m=''3651630''>can</span>
  <span m=''3651810''>even</span> <span m=''3651970''>have</span> <span m=''3652190''>overhang</span>
  <span m=''3653640''>and</span> <span m=''3653770''>they</span> <span m=''3653900''>will</span>
  <span m=''3654140''>unfold,</span> <span m=''3655480''>volcano</span> <span m=''3656010''>style.</span>
  <span m=''3657190''>You</span> <span m=''3657370''>no</span> <span m=''3657540''>longer</span>
  <span m=''3657840''>have</span> <span m=''3658060''>those</span> <span m=''3658260''>nice</span>
  <span m=''3659070''>perpendicular</span> <span m=''3659790''>wedges</span> <span
  m=''3660260''>to</span> <span m=''3660370''>say</span> <span m=''3660540''>everything</span>
  <span m=''3660870''>is</span> <span m=''3660970''>disjoined.</span> <span m=''3661650''>But</span>
  <span m=''3661700''>it</span> <span m=''3661790''>still</span> <span m=''3662010''>turns</span>
  <span m=''3662270''>out.</span> <span m=''3662860''>Nothing</span> <span m=''3663170''>intersects.</span>
  <span m=''3666380''>Here''s</span> <span m=''3666920''>the</span> <span m=''3667240''>prismatoid</span>
  <span m=''3668010''>I</span> <span m=''3668070''>wanted</span> <span m=''3668330''>to</span>
  <span m=''3668400''>show</span> <span m=''3668620''>you.</span> <span m=''3669290''>This</span>
  <span m=''3669460''>one''s</span> <span m=''3669680''>actually</span> <span m=''3670010''>almost</span>
  <span m=''3670320''>flat.</span> <span m=''3671820''>So</span> <span m=''3671980''>a</span>
  <span m=''3672620''>is</span> <span m=''3672800''>this</span> <span m=''3672910''>triangle</span>
  <span m=''3673540''>right</span> <span m=''3673720''>on</span> <span m=''3673830''>top</span>
  <span m=''3674060''>of</span> <span m=''3674160''>b,</span> <span m=''3675340''>the</span>
  <span m=''3675480''>triangle</span> <span m=''3675810''>beneath.</span> <span m=''3676290''>You</span>
  <span m=''3676350''>take</span> <span m=''3676530''>the</span> <span m=''3676590''>convex</span>
  <span m=''3676990''>hull</span> <span m=''3677280''>and</span> <span m=''3677340''>you</span>
  <span m=''3677450''>get</span> <span m=''3677790''>all</span> <span m=''3677980''>those</span>
  <span m=''3678220''>edges</span> <span m=''3678690''>on</span> <span m=''3678800''>the</span>
  <span m=''3678910''>outside.</span> <span m=''3680970''>And</span> <span m=''3681120''>if</span>
  <span m=''3681240''>you''re</span> <span m=''3681410''>not</span> <span m=''3681680''>careful--</span>
  <span m=''3682430''>this</span> <span m=''3682640''>is</span> <span m=''3682950''>more</span>
  <span m=''3683220''>volcano</span> <span m=''3683710''>style</span> <span m=''3684030''>unfolding--</span>
  <span m=''3685060''>but</span> <span m=''3685230''>you</span> <span m=''3686110''>can</span>
  <span m=''3686310''>get</span> <span m=''3686440''>overlap.</span> </p><p><span
  m=''3692020''>One</span> <span m=''3692370''>thing</span> <span m=''3692650''>we</span>
  <span m=''3692760''>do</span> <span m=''3692940''>know,</span> <span m=''3693180''>this</span>
  <span m=''3693330''>is</span> <span m=''3693430''>kind</span> <span m=''3693600''>of</span>
  <span m=''3694310''>weird.</span> <span m=''3696910''>If</span> <span m=''3697070''>you</span>
  <span m=''3697150''>try</span> <span m=''3697350''>to</span> <span m=''3697450''>go</span>
  <span m=''3697750''>more</span> <span m=''3698020''>general,</span> <span m=''3699390''>and</span>
  <span m=''3699540''>instead</span> <span m=''3699810''>of</span> <span m=''3699900''>taking</span>
  <span m=''3700410''>a</span> <span m=''3700910''>convex</span> <span m=''3701380''>polygon</span>
  <span m=''3701890''>on</span> <span m=''3701960''>the</span> <span m=''3702050''>top</span>
  <span m=''3702300''>and</span> <span m=''3702370''>a</span> <span m=''3702410''>convex</span>
  <span m=''3702800''>polygon</span> <span m=''3703065''>on</span> <span m=''3703330''>the</span>
  <span m=''3703390''>bottom,</span> <span m=''3703970''>instead</span> <span m=''3704300''>you</span>
  <span m=''3704400''>take</span> <span m=''3704620''>a</span> <span m=''3704690''>smooth</span>
  <span m=''3705340''>convex</span> <span m=''3705920''>curve</span> <span m=''3706290''>on</span>
  <span m=''3706380''>the</span> <span m=''3706490''>top</span> <span m=''3706790''>and</span>
  <span m=''3706890''>a</span> <span m=''3706940''>smooth</span> <span m=''3707240''>convex</span>
  <span m=''3707640''>curve</span> <span m=''3707890''>on</span> <span m=''3707960''>the</span>
  <span m=''3708050''>bottom,</span> <span m=''3708845''>which</span> <span m=''3709220''>is</span>
  <span m=''3709350''>getting</span> <span m=''3709660''>weird</span> <span m=''3710070''>because</span>
  <span m=''3710360''>now</span> <span m=''3710510''>there''s</span> <span m=''3710690''>infinitely</span>
  <span m=''3711120''>many</span> <span m=''3711340''>vertices</span> <span m=''3711820''>and</span>
  <span m=''3711900''>going</span> <span m=''3712010''>to</span> <span m=''3712050''>be</span>
  <span m=''3712250''>infinitely</span> <span m=''3712730''>many</span> <span m=''3712970''>cuts.</span>
  <span m=''3714200''>But</span> <span m=''3714380''>there</span> <span m=''3714540''>is</span>
  <span m=''3714760''>a</span> <span m=''3714830''>natural</span> <span m=''3716310''>notion</span>
  <span m=''3716840''>of</span> <span m=''3716980''>unfolding</span> <span m=''3718440''>which</span>
  <span m=''3718770''>sort</span> <span m=''3719020''>of</span> <span m=''3719110''>takes</span>
  <span m=''3719370''>the</span> <span m=''3719460''>continuum.</span> <span m=''3719990''>You</span>
  <span m=''3720070''>take</span> <span m=''3720260''>all</span> <span m=''3720570''>those</span>
  <span m=''3721260''>lines</span> <span m=''3721900''>that</span> <span m=''3722030''>go</span>
  <span m=''3722300''>from</span> <span m=''3722490''>one</span> <span m=''3722660''>side
  to</span> <span m=''3722970''>the</span> <span m=''3723120''>other,</span> <span
  m=''3724140''>the</span> <span m=''3724380''>rule</span> <span m=''3724660''>lines</span>
  <span m=''3725050''>of</span> <span m=''3725220''>the</span> <span m=''3725510''>convex</span>
  <span m=''3725940''>shape,</span> <span m=''3727630''>and</span> <span m=''3727890''>you</span>
  <span m=''3727970''>just</span> <span m=''3729000''>unfold</span> <span m=''3729320''>them.</span>
  </p><p><span m=''3729740''>You</span> <span m=''3729860''>don''t</span> <span m=''3730000''>actually</span>
  <span m=''3730260''>preserve</span> <span m=''3730720''>area</span> <span m=''3731100''>when</span>
  <span m=''3731210''>you</span> <span m=''3731310''>do</span> <span m=''3731440''>this.</span>
  <span m=''3731730''>It''s</span> <span m=''3731890''>not</span> <span m=''3732100''>a</span>
  <span m=''3732750''>valid</span> <span m=''3733210''>unfolding</span> <span m=''3733660''>in</span>
  <span m=''3733730''>the</span> <span m=''3733820''>usual</span> <span m=''3734160''>sense,</span>
  <span m=''3734580''>but</span> <span m=''3734860''>it''s</span> <span m=''3735240''>a</span>
  <span m=''3735320''>natural</span> <span m=''3735740''>generalization</span> <span
  m=''3736430''>of</span> <span m=''3736590''>unfolding</span> <span m=''3737010''>to</span>
  <span m=''3737250''>smooth</span> <span m=''3738140''>shapes.</span> <span m=''3739200''>You</span>
  <span m=''3739330''>can</span> <span m=''3739480''>prove,</span> <span m=''3739760''>well,</span>
  <span m=''3739840''>that</span> <span m=''3740070''>part''s</span> <span m=''3740310''>going</span>
  <span m=''3740440''>to</span> <span m=''3740500''>work</span> <span m=''3740710''>just</span>
  <span m=''3740930''>fine</span> <span m=''3741180''>if</span> <span m=''3741280''>you</span>
  <span m=''3741380''>just</span> <span m=''3741630''>volcano</span> <span m=''3742240''>it,</span>
  <span m=''3742450''>and</span> <span m=''3742690''>then</span> <span m=''3742830''>you</span>
  <span m=''3742940''>can</span> <span m=''3743130''>actually</span> <span m=''3743410''>find</span>
  <span m=''3743750''>a</span> <span m=''3744170''>place</span> <span m=''3744480''>for</span>
  <span m=''3745550''>the</span> <span m=''3745660''>top</span> <span m=''3745920''>face.</span>
  </p><p><span m=''3753940''>Those</span> <span m=''3754130''>are</span> <span m=''3754220''>the</span>
  <span m=''3754310''>special</span> <span m=''3754630''>cases</span> <span m=''3755080''>we</span>
  <span m=''3755100''>know,</span> <span m=''3755420''>and</span> <span m=''3755540''>even</span>
  <span m=''3755830''>some</span> <span m=''3756100''>pretty</span> <span m=''3756380''>simple</span>
  <span m=''3756780''>cases</span> <span m=''3757160''>that</span> <span m=''3757240''>we</span>
  <span m=''3757340''>don''t</span> <span m=''3757550''>know,</span> <span m=''3757780''>although
  it''s</span> <span m=''3758160''>almost</span> <span m=''3760170''>there.</span>
  <span m=''3775440''>One</span> <span m=''3775620''>more</span> <span m=''3775810''>open</span>
  <span m=''3776020''>problem.</span> <span m=''3801760''>Just</span> <span m=''3801950''>mention</span>
  <span m=''3802230''>this</span> <span m=''3802460''>because</span> <span m=''3802650''>it''s</span>
  <span m=''3802810''>a</span> <span m=''3802870''>fun</span> <span m=''3803100''>problem.</span>
  <span m=''3806430''>So</span> <span m=''3806580''>again,</span> <span m=''3806840''>I</span>
  <span m=''3806890''>want</span> <span m=''3807060''>to</span> <span m=''3807160''>edge</span>
  <span m=''3807440''>unfold</span> <span m=''3809330''>all</span> <span m=''3809610''>convex</span>
  <span m=''3810030''>polyhedra,</span> <span m=''3818380''>but</span> <span m=''3818560''>I</span>
  <span m=''3818650''>allow</span> <span m=''3819160''>multiple</span> <span m=''3819770''>pieces</span>
  <span m=''3821640''>to</span> <span m=''3821800''>make</span> <span m=''3822000''>the</span>
  <span m=''3822080''>problem</span> <span m=''3822340''>a</span> <span m=''3822380''>little</span>
  <span m=''3822620''>easier.</span> </p><p><span m=''3826140''>So</span> <span m=''3826240''>let''s</span>
  <span m=''3826450''>say</span> <span m=''3826830''>I</span> <span m=''3826930''>have</span>
  <span m=''3828350''>a</span> <span m=''3828370''>polyhedron</span> <span m=''3830650''>with</span>
  <span m=''3830900''>f</span> <span m=''3831370''>faces.</span> <span m=''3833690''>I</span>
  <span m=''3834000''>want</span> <span m=''3834200''>to</span> <span m=''3834240''>know</span>
  <span m=''3834380''>how</span> <span m=''3834730''>few</span> <span m=''3835000''>pieces</span>
  <span m=''3835370''>could</span> <span m=''3835520''>I</span> <span m=''3835560''>get</span>
  <span m=''3835730''>away</span> <span m=''3835930''>with?</span> <span m=''3836740''>The</span>
  <span m=''3836880''>big open</span> <span m=''3837290''>problem</span> <span m=''3837570''>is,</span>
  <span m=''3837680''>can</span> <span m=''3837830''>I</span> <span m=''3837870''>get</span>
  <span m=''3838020''>away</span> <span m=''3838150''>with</span> <span m=''3838350''>one</span>
  <span m=''3838630''>piece?</span> <span m=''3840050''>What</span> <span m=''3840180''>if</span>
  <span m=''3840270''>you</span> <span m=''3840370''>make</span> <span m=''3840540''>it</span>
  <span m=''3840610''>easier?</span> <span m=''3840960''>What</span> <span m=''3841100''>if</span>
  <span m=''3841220''>I</span> <span m=''3841300''>just</span> <span m=''3841590''>want,</span>
  <span m=''3841910''>say,</span> <span m=''3842560''>little o</span> <span m=''3843360''>of</span>
  <span m=''3843590''>f</span> <span m=''3843920''>pieces?</span> <span m=''3845760''>Smaller</span>
  <span m=''3846320''>than</span> <span m=''3846470''>any</span> <span m=''3846650''>constant</span>
  <span m=''3847070''>times</span> <span m=''3847310''>f.</span> <span m=''3848410''>This</span>
  <span m=''3848640''>is</span> <span m=''3848870''>open.</span> </p><p><span m=''3853210''>What</span>
  <span m=''3853400''>we</span> <span m=''3853520''>do</span> <span m=''3853710''>know</span>
  <span m=''3854100''>is</span> <span m=''3854350''>some</span> <span m=''3854600''>constant</span>
  <span m=''3855100''>times</span> <span m=''3855390''>f</span> <span m=''3855690''>where</span>
  <span m=''3855790''>the</span> <span m=''3855960''>constant</span> <span m=''3856500''>is</span>
  <span m=''3857100''>less</span> <span m=''3857360''>than</span> <span m=''3857500''>1.</span>
  <span m=''3859710''>Best</span> <span m=''3859910''>constant</span> <span m=''3860170''>I</span>
  <span m=''3860240''>have</span> <span m=''3860470''>written</span> <span m=''3860670''>here</span>
  <span m=''3860950''>is</span> <span m=''3861250''>1/2.</span> <span m=''3863230''>There</span>
  <span m=''3863580''>is</span> <span m=''3863680''>a</span> <span m=''3863730''>better</span>
  <span m=''3863980''>bound,</span> <span m=''3864370''>but</span> <span m=''3864620''>I</span>
  <span m=''3864700''>think</span> <span m=''3864900''>it''s</span> <span m=''3865040''>not</span>
  <span m=''3865270''>so</span> <span m=''3865420''>easy</span> <span m=''3865670''>to</span>
  <span m=''3865770''>summarize</span> <span m=''3866290''>in</span> <span m=''3866380''>this</span>
  <span m=''3866550''>form.</span> <span m=''3867590''>So</span> <span m=''3867740''>you</span>
  <span m=''3867870''>can</span> <span m=''3867950''>get</span> <span m=''3868100''>a</span>
  <span m=''3868160''>little</span> <span m=''3868430''>less</span> <span m=''3868670''>than</span>
  <span m=''3868830''>half</span> <span m=''3869140''>the</span> <span m=''3869250''>faces''</span>
  <span m=''3870550''>number</span> <span m=''3870850''>of</span> <span m=''3870900''>pieces,</span>
  <span m=''3871510''>but</span> <span m=''3871650''>that''s</span> <span m=''3871780''>pretty</span>
  <span m=''3871990''>pathetic.</span> <span m=''3876040''>It''s</span> <span m=''3876150''>a</span>
  <span m=''3876230''>problem</span> <span m=''3876550''>that</span> <span m=''3876640''>seemed</span>
  <span m=''3876860''>like</span> <span m=''3877020''>it would</span> <span m=''3877120''>be
  a good</span> <span m=''3877370''>idea,</span> <span m=''3877840''>but</span> <span
  m=''3878030''>so</span> <span m=''3878150''>far it</span> <span m=''3878340''>hasn''t</span>
  <span m=''3878820''>seemed</span> <span m=''3879150''>to</span> <span m=''3879260''>make</span>
  <span m=''3879460''>the</span> <span m=''3879560''>problem</span> <span m=''3879780''>much</span>
  <span m=''3880030''>easier.</span> </p><p><span m=''3884670''>What</span> <span
  m=''3884910''>do I</span> <span m=''3884940''>mean</span> <span m=''3885120''>by</span>
  <span m=''3885270''>pieces?</span> <span m=''3886810''>Well,</span> <span m=''3887730''>we''re</span>
  <span m=''3888020''>all</span> <span m=''3888250''>about</span> <span m=''3888730''>one</span>
  <span m=''3888970''>piece</span> <span m=''3889200''>unfolding,</span> <span m=''3889580''>so</span>
  <span m=''3889690''>now</span> <span m=''3890730''>your</span> <span m=''3890850''>cutting</span>
  <span m=''3891260''>can</span> <span m=''3891850''>have</span> <span m=''3892070''>cycles</span>
  <span m=''3892460''>in</span> <span m=''3892570''>it</span> <span m=''3893170''>and</span>
  <span m=''3893340''>disconnect</span> <span m=''3893990''>the</span> <span m=''3894270''>surface</span>
  <span m=''3894660''>into</span> <span m=''3894810''>multiple</span> <span m=''3895210''>parts.</span>
  </p><p><span m=''3895780''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''3899390''>PROFESSOR:
  Multiple</span> <span m=''3899800''>connected</span> <span m=''3900110''>components.</span>
  <span m=''3915440''>The</span> <span m=''3915620''>tricky</span> <span m=''3915890''>part</span>
  <span m=''3916090''>is</span> <span m=''3916190''>to</span> <span m=''3916310''>pair</span>
  <span m=''3916550''>up</span> <span m=''3916640''>the</span> <span m=''3916740''>faces</span>
  <span m=''3917050''>so</span> <span m=''3917170''>that</span> <span m=''3917290''>everybody</span>
  <span m=''3917760''>has</span> <span m=''3918780''>a</span> <span m=''3918830''>mate.</span>
  <span m=''3920050''>That''s</span> <span m=''3920260''>not</span> <span m=''3920430''>always</span>
  <span m=''3921020''>possible.</span> </p><p><span m=''3922510''>AUDIENCE: [INAUDIBLE]?</span>
  </p><p><span m=''3924710''>PROFESSOR: Yeah.</span> <span m=''3924800''>You</span>
  <span m=''3925010''>would</span> <span m=''3925100''>hope</span> <span m=''3925350''>that</span>
  <span m=''3925530''>one</span> <span m=''3925950''>third,</span> <span m=''3926400''>but--</span>
  <span m=''3928410''>I</span> <span m=''3928590''>mean,</span> <span m=''3928880''>you</span>
  <span m=''3928940''>can</span> <span m=''3929370''>do</span> <span m=''3929510''>lots</span>
  <span m=''3929750''>of</span> <span m=''3929790''>little</span> <span m=''3930040''>local</span>
  <span m=''3930270''>arguments</span> <span m=''3930700''>and prove</span> <span
  m=''3930970''>this</span> <span m=''3931120''>constant,</span> <span m=''3931610''>but</span>
  <span m=''3933440''>the</span> <span m=''3933520''>big</span> <span m=''3933710''>question</span>
  <span m=''3934020''>is,</span> <span m=''3934220''>can</span> <span m=''3934260''>you</span>
  <span m=''3934340''>get</span> <span m=''3934460''>less</span> <span m=''3934690''>than</span>
  <span m=''3934800''>a</span> <span m=''3934860''>constant?</span> </p><p><span m=''3944730''>So</span>
  <span m=''3945120''>last</span> <span m=''3945430''>topic</span> <span m=''3945780''>for</span>
  <span m=''3945960''>today</span> <span m=''3947770''>is</span> <span m=''3948040''>edge</span>
  <span m=''3948260''>unfolding</span> <span m=''3949450''>non-convex</span> <span
  m=''3950350''>polyhedra.</span> <span m=''3956970''>Sort</span> <span m=''3957170''>of</span>
  <span m=''3957280''>did</span> <span m=''3957470''>that</span> <span m=''3958790''>problem</span>
  <span m=''3959270''>addressed,</span> <span m=''3960210''>and</span> <span m=''3960440''>now</span>
  <span m=''3961780''>this</span> <span m=''3961990''>is</span> <span m=''3962110''>not</span>
  <span m=''3962360''>always</span> <span m=''3962620''>possible.</span> <span m=''3963330''>So</span>
  <span m=''3963380''>I</span> <span m=''3963430''>want</span> <span m=''3963600''>to</span>
  <span m=''3963660''>give</span> <span m=''3963800''>you</span> <span m=''3963920''>a</span>
  <span m=''3963960''>polyhedron</span> <span m=''3965510''>where</span> <span m=''3965780''>you</span>
  <span m=''3965930''>cannot</span> <span m=''3966200''>edge</span> <span m=''3966390''>unfold</span>
  <span m=''3966650''>it.</span> <span m=''3966910''>This</span> <span m=''3967120''>is</span>
  <span m=''3967210''>actually</span> <span m=''3967670''>pretty</span> <span m=''3967990''>easy,</span>
  <span m=''3968930''>and</span> <span m=''3969210''>we</span> <span m=''3969340''>did</span>
  <span m=''3969530''>it</span> <span m=''3969620''>way</span> <span m=''3969750''>back</span>
  <span m=''3970000''>in</span> <span m=''3970080''>''98</span> <span m=''3970510''>when</span>
  <span m=''3970580''>we</span> <span m=''3970690''>started</span> <span m=''3970960''>working</span>
  <span m=''3971230''>on</span> <span m=''3971545''>folding,</span> <span m=''3972340''>but</span>
  <span m=''3972550''>it''s</span> <span m=''3972750''>kind</span> <span m=''3972930''>of</span>
  <span m=''3972990''>cheating.</span> </p><p><span m=''3974810''>This</span> <span
  m=''3975010''>is</span> <span m=''3975140''>a</span> <span m=''3975210''>box</span>
  <span m=''3975650''>on</span> <span m=''3975780''>a</span> <span m=''3975830''>box,</span>
  <span m=''3977240''>and</span> <span m=''3977410''>the</span> <span m=''3977540''>only</span>
  <span m=''3977860''>edges</span> <span m=''3978290''>here</span> <span m=''3978630''>are</span>
  <span m=''3978700''>the</span> <span m=''3978830''>edges</span> <span m=''3979210''>of</span>
  <span m=''3979310''>the</span> <span m=''3979420''>two</span> <span m=''3979580''>boxes.</span>
  <span m=''3980790''>There''s</span> <span m=''3980990''>no</span> <span m=''3981190''>edges</span>
  <span m=''3981760''>connecting</span> <span m=''3982310''>the</span> <span m=''3982450''>outside</span>
  <span m=''3982940''>of</span> <span m=''3983020''>this</span> <span m=''3983120''>face</span>
  <span m=''3983460''>to</span> <span m=''3983570''>the</span> <span m=''3983720''>inside</span>
  <span m=''3984110''>of</span> <span m=''3984190''>that</span> <span m=''3984420''>face.</span>
  <span m=''3984670''>That</span> <span m=''3984890''>face</span> <span m=''3985900''>here</span>
  <span m=''3986250''>is</span> <span m=''3986450''>a</span> <span m=''3986540''>donut.</span>
  <span m=''3988930''>It''s</span> <span m=''3989040''>a</span> <span m=''3989220''>square</span>
  <span m=''3989590''>donut.</span> </p><p><span m=''3993080''>So</span> <span m=''3993290''>if</span>
  <span m=''3993350''>you''re</span> <span m=''3993670''>only</span> <span m=''3993960''>cutting</span>
  <span m=''3994220''>along</span> <span m=''3994470''>edges,</span> <span m=''3995280''>that</span>
  <span m=''3995550''>face</span> <span m=''3995960''>is</span> <span m=''3996100''>intact.</span>
  <span m=''3997590''>Now</span> <span m=''3997990''>I</span> <span m=''3998160''>ask</span>
  <span m=''3998520''>you,</span> <span m=''3999600''>where</span> <span m=''3999960''>does</span>
  <span m=''4000160''>the</span> <span m=''4000280''>top</span> <span m=''4000660''>box</span>
  <span m=''4001090''>go?</span> <span m=''4003100''>The</span> <span m=''4003200''>top</span>
  <span m=''4003490''>box has</span> <span m=''4003890''>five</span> <span m=''4004380''>square</span>
  <span m=''4004710''>faces,</span> <span m=''4005110''>not</span> <span m=''4005350''>six.</span>
  <span m=''4005660''>There''s</span> <span m=''4005820''>nothing</span> <span m=''4006100''>on</span>
  <span m=''4006190''>the</span> <span m=''4006260''>bottom.</span> <span m=''4007490''>And</span>
  <span m=''4007900''>somehow,</span> <span m=''4008490''>it</span> <span m=''4008560''>has</span>
  <span m=''4008740''>to</span> <span m=''4008830''>be</span> <span m=''4008950''>attached</span>
  <span m=''4009500''>to</span> <span m=''4009570''>the</span> <span m=''4009670''>rest</span>
  <span m=''4009920''>if</span> <span m=''4010030''>I</span> <span m=''4010090''>want</span>
  <span m=''4010310''>one</span> <span m=''4010520''>piece.</span> <span m=''4010810''>That</span>
  <span m=''4010980''>means</span> <span m=''4011270''>that</span> <span m=''4011390''>all</span>
  <span m=''4011650''>five</span> <span m=''4011990''>faces</span> <span m=''4012960''>fit</span>
  <span m=''4013140''>in</span> <span m=''4013330''>here,</span> <span m=''4014170''>but</span>
  <span m=''4014440''>there''s</span> <span m=''4014720''>only</span> <span m=''4014960''>room</span>
  <span m=''4015120''>for</span> <span m=''4015270''>one</span> <span m=''4015750''>in</span>
  <span m=''4015910''>terms</span> <span m=''4016110''>of</span> <span m=''4016210''>area</span>
  <span m=''4016990''>so</span> <span m=''4017150''>you''re</span> <span m=''4017320''>screwed.</span>
  </p><p><span m=''4019050''>But</span> <span m=''4019280''>this</span> <span m=''4019460''>is</span>
  <span m=''4019620''>cheating</span> <span m=''4020090''>because</span> <span m=''4022020''>what</span>
  <span m=''4022230''>I</span> <span m=''4022280''>really</span> <span m=''4022580''>wanted</span>
  <span m=''4022880''>to</span> <span m=''4022980''>do</span> <span m=''4023290''>was</span>
  <span m=''4023490''>generalize</span> <span m=''4024140''>this</span> <span m=''4024370''>problem,</span>
  <span m=''4025280''>edge</span> <span m=''4025520''>unfolding</span> <span m=''4025920''>of</span>
  <span m=''4026000''>convex</span> <span m=''4026480''>polyhedra.</span> <span m=''4028080''>Now,</span>
  <span m=''4028220''>I</span> <span m=''4028290''>know</span> <span m=''4028880''>they''re</span>
  <span m=''4029030''>not</span> <span m=''4029210''>going</span> <span m=''4029300''>to</span>
  <span m=''4029350''>look</span> <span m=''4029510''>convex,</span> <span m=''4030000''>but</span>
  <span m=''4030530''>that</span> <span m=''4030820''>thing</span> <span m=''4031100''>is</span>
  <span m=''4031250''>really</span> <span m=''4031800''>not</span> <span m=''4032040''>convex.</span>
  <span m=''4033240''>It''s</span> <span m=''4033420''>really</span> <span m=''4033680''>not</span>
  <span m=''4033860''>convex</span> <span m=''4034260''>in</span> <span m=''4034370''>the</span>
  <span m=''4034470''>sense</span> <span m=''4034740''>that</span> <span m=''4035130''>you</span>
  <span m=''4035230''>have</span> <span m=''4035440''>this</span> <span m=''4035660''>face</span>
  <span m=''4036290''>that</span> <span m=''4036800''>is</span> <span m=''4036930''>not</span>
  <span m=''4037150''>even</span> <span m=''4037400''>topologically</span> <span m=''4037740''>a</span>
  <span m=''4038080''>disk.</span> <span m=''4038500''>It</span> <span m=''4038570''>has</span>
  <span m=''4038750''>a</span> <span m=''4038800''>hole</span> <span m=''4039110''>in</span>
  <span m=''4039190''>it.</span> <span m=''4039750''>Convex</span> <span m=''4039960''>polyhedra</span>
  <span m=''4040580''>don''t</span> <span m=''4040910''>have</span> <span m=''4041300''>that.</span>
  </p><p><span m=''4042160''>So</span> <span m=''4042440''>in</span> <span m=''4042550''>some</span>
  <span m=''4042770''>sense,</span> <span m=''4043150''>this</span> <span m=''4043220''>is</span>
  <span m=''4043920''>a</span> <span m=''4043990''>topological</span> <span m=''4044740''>problem,</span>
  <span m=''4045210''>you</span> <span m=''4045350''>might</span> <span m=''4045580''>say.</span>
  <span m=''4047500''>And</span> <span m=''4047660''>you</span> <span m=''4047750''>might</span>
  <span m=''4047960''>hope</span> <span m=''4049370''>that</span> <span m=''4049510''>if</span>
  <span m=''4049640''>I</span> <span m=''4049700''>looked</span> <span m=''4049960''>at</span>
  <span m=''4050060''>polyhedra</span> <span m=''4050600''>that</span> <span m=''4050800''>are</span>
  <span m=''4050970''>topologically</span> <span m=''4051950''>convex,</span> <span
  m=''4053310''>maybe</span> <span m=''4053620''>those</span> <span m=''4054000''>would</span>
  <span m=''4054410''>unfold</span> <span m=''4055140''>by</span> <span m=''4055320''>edge</span>
  <span m=''4055550''>cuts.</span> <span m=''4057020''>"Topologically</span> <span
  m=''4057850''>convex"</span> <span m=''4058300''>means</span> <span m=''4058620''>that</span>
  <span m=''4059480''>if</span> <span m=''4059620''>you</span> <span m=''4059710''>just</span>
  <span m=''4059920''>move</span> <span m=''4060130''>the</span> <span m=''4060210''>vertices</span>
  <span m=''4060710''>around</span> <span m=''4061090''>but</span> <span m=''4061200''>preserve</span>
  <span m=''4061840''>the</span> <span m=''4062030''>edge</span> <span m=''4062370''>structure,</span>
  <span m=''4063570''>then</span> <span m=''4065040''>it</span> <span m=''4065390''>becomes</span>
  <span m=''4065730''>a</span> <span m=''4065830''>convex</span> <span m=''4066220''>polyhedron.</span>
  <span m=''4066820''>In</span> <span m=''4066860''>other</span> <span m=''4066990''>words,</span>
  <span m=''4067150''>I</span> <span m=''4067210''>take</span> <span m=''4067420''>a</span>
  <span m=''4067490''>convex</span> <span m=''4067820''>polyhedron,</span> <span m=''4068250''>which</span>
  <span m=''4068550''>we</span> <span m=''4068740''>think</span> <span m=''4069080''>maybe</span>
  <span m=''4069920''>has</span> <span m=''4070170''>an</span> <span m=''4070240''>edge</span>
  <span m=''4070400''>unfolding,</span> <span m=''4070850''>and</span> <span m=''4070930''>then</span>
  <span m=''4071040''>I</span> <span m=''4071110''>just</span> <span m=''4071340''>pull</span>
  <span m=''4071530''>the</span> <span m=''4071590''>vertices</span> <span m=''4072020''>around</span>
  <span m=''4072330''>but</span> <span m=''4072430''>preserve</span> <span m=''4072830''>all</span>
  <span m=''4072970''>the</span> <span m=''4073040''>faces.</span> <span m=''4075150''>Then</span>
  <span m=''4075620''>can</span> <span m=''4075800''>you</span> <span m=''4075900''>edge</span>
  <span m=''4076050''>unfold</span> <span m=''4076420''>those?</span> <span m=''4077070''>And</span>
  <span m=''4077210''>the</span> <span m=''4077290''>answer</span> <span m=''4077600''>is</span>
  <span m=''4077760''>no.</span> </p><p><span m=''4079470''>I</span> <span m=''4079530''>have</span>
  <span m=''4079760''>one</span> <span m=''4079980''>more</span> <span m=''4080250''>example</span>
  <span m=''4080640''>before</span> <span m=''4080910''>we</span> <span m=''4081020''>get</span>
  <span m=''4081220''>there.</span> <span m=''4083400''>This</span> <span m=''4083620''>polyhedron,</span>
  <span m=''4084170''>at</span> <span m=''4084260''>least</span> <span m=''4084820''>all</span>
  <span m=''4085010''>the</span> <span m=''4085090''>faces</span> <span m=''4085500''>are</span>
  <span m=''4085590''>disks.</span> <span m=''4086160''>There''s</span> <span m=''4086320''>no</span>
  <span m=''4086430''>holes.</span> <span m=''4087600''>So</span> <span m=''4087710''>it''s</span>
  <span m=''4087820''>a</span> <span m=''4087860''>cube</span> <span m=''4088360''>with</span>
  <span m=''4088500''>little</span> <span m=''4088730''>bites</span> <span m=''4089100''>taken</span>
  <span m=''4089410''>out</span> <span m=''4089560''>of</span> <span m=''4089760''>all</span>
  <span m=''4089890''>the</span> <span m=''4090030''>edges,</span> <span m=''4090950''>same</span>
  <span m=''4091180''>paper.</span> <span m=''4092370''>And</span> <span m=''4092600''>this</span>
  <span m=''4092770''>thing</span> <span m=''4092950''>also</span> <span m=''4093200''>does</span>
  <span m=''4093360''>not</span> <span m=''4093630''>unfold.</span> <span m=''4093820''>It''s</span>
  <span m=''4093930''>a</span> <span m=''4093970''>little</span> <span m=''4094170''>less</span>
  <span m=''4094380''>obvious.</span> </p><p><span m=''4097830''>What''s</span> <span
  m=''4098029''>cheating</span> <span m=''4098340''>about</span> <span m=''4098560''>this</span>
  <span m=''4098720''>example</span> <span m=''4099180''>is</span> <span m=''4099240''>you</span>
  <span m=''4099330''>have</span> <span m=''4099500''>two</span> <span m=''4099660''>faces,</span>
  <span m=''4100109''>like</span> <span m=''4100270''>this</span> <span m=''4100420''>purple</span>
  <span m=''4100720''>one</span> <span m=''4100950''>and</span> <span m=''4101020''>the</span>
  <span m=''4101109''>yellow</span> <span m=''4101359''>one,</span> <span m=''4102090''>that</span>
  <span m=''4102290''>share</span> <span m=''4102910''>two</span> <span m=''4103180''>different</span>
  <span m=''4103590''>edges.</span> <span m=''4104859''>And</span> <span m=''4104979''>for</span>
  <span m=''4105080''>convex</span> <span m=''4105490''>polyhedra,</span> <span m=''4106090''>two</span>
  <span m=''4106279''>faces</span> <span m=''4106689''>either</span> <span m=''4106890''>share</span>
  <span m=''4107210''>an</span> <span m=''4107290''>edge</span> <span m=''4107740''>or
  a</span> <span m=''4107930''>vertex</span> <span m=''4108510''>or</span> <span m=''4108640''>nothing,</span>
  <span m=''4109649''>but</span> <span m=''4110520''>they</span> <span m=''4110609''>can''t</span>
  <span m=''4110830''>reach</span> <span m=''4111020''>around</span> <span m=''4111520''>and</span>
  <span m=''4111649''>do</span> <span m=''4111910''>to</span> <span m=''4112460''>joins.</span>
  <span m=''4114300''>Again,</span> <span m=''4114680''>this</span> <span m=''4114830''>is</span>
  <span m=''4114920''>not</span> <span m=''4115170''>topologically</span> <span m=''4115850''>convex,</span>
  <span m=''4118050''>but</span> <span m=''4118189''>this</span> <span m=''4118399''>is.</span>
  </p><p><span m=''4120390''>So</span> <span m=''4120649''>this is</span> <span m=''4120880''>two</span>
  <span m=''4121050''>views</span> <span m=''4121399''>of</span> <span m=''4121479''>the</span>
  <span m=''4121569''>same</span> <span m=''4121840''>thing,</span> <span m=''4123300''>and</span>
  <span m=''4123450''>if</span> <span m=''4123600''>I</span> <span m=''4123939''>take</span>
  <span m=''4124189''>these</span> <span m=''4124370''>spikes</span> <span m=''4124890''>and</span>
  <span m=''4124990''>I</span> <span m=''4125060''>just</span> <span m=''4125319''>push</span>
  <span m=''4125510''>that</span> <span m=''4125710''>vertex</span> <span m=''4126120''>down</span>
  <span m=''4126640''>to</span> <span m=''4126810''>be</span> <span m=''4127109''>really</span>
  <span m=''4127399''>close</span> <span m=''4127859''>to</span> <span m=''4127970''>this</span>
  <span m=''4128189''>triangle,</span> <span m=''4129460''>this</span> <span m=''4129620''>will</span>
  <span m=''4129819''>be</span> <span m=''4129930''>convex.</span> <span m=''4130710''>So</span>
  <span m=''4130779''>it''s</span> <span m=''4130870''>just</span> <span m=''4131010''>a</span>
  <span m=''4131050''>convex</span> <span m=''4131399''>polyhedron</span> <span m=''4131659''>that</span>
  <span m=''4131920''>I</span> <span m=''4132020''>pull</span> <span m=''4132430''>on</span>
  <span m=''4132670''>four of</span> <span m=''4133020''>the</span> <span m=''4133140''>points.</span>
  <span m=''4135060''>Same</span> <span m=''4135359''>facial</span> <span m=''4135720''>structure.</span>
  <span m=''4136580''>This</span> <span m=''4137040''>has</span> <span m=''4137290''>no</span>
  <span m=''4137479''>edge</span> <span m=''4137660''>unfolding</span> <span m=''4139431''>and</span>
  <span m=''4139970''>we''re</span> <span m=''4140080''>going</span> <span m=''4140160''>to</span>
  <span m=''4140210''>prove</span> <span m=''4140439''>that.</span> </p><p><span m=''4152830''>This</span>
  <span m=''4153020''>example</span> <span m=''4153380''>is</span> <span m=''4153460''>even</span>
  <span m=''4153660''>stronger</span> <span m=''4154350''>in</span> <span m=''4154790''>that</span>
  <span m=''4154990''>all</span> <span m=''4155279''>the</span> <span m=''4155359''>faces</span>
  <span m=''4155740''>are</span> <span m=''4155810''>triangles.</span> <span m=''4165560''>So</span>
  <span m=''4166270''>what</span> <span m=''4166450''>we''re</span> <span m=''4166600''>going</span>
  <span m=''4166729''>to</span> <span m=''4166830''>do</span> <span m=''4167229''>is</span>
  <span m=''4167529''>take</span> <span m=''4169560''>this</span> <span m=''4169790''>thing.</span>
  <span m=''4170189''>It''s</span> <span m=''4170359''>kind</span> <span m=''4170510''>of</span>
  <span m=''4170609''>appropriate</span> <span m=''4171330''>for</span> <span m=''4171470''>this</span>
  <span m=''4171600''>season.</span> <span m=''4200680''>So</span> <span m=''4200840''>I''ve</span>
  <span m=''4200900''>got</span> <span m=''4201080''>a</span> <span m=''4201790''>tetrahedral</span>
  <span m=''4202260''>spike</span> <span m=''4202630''>on</span> <span m=''4202770''>top.</span>
  <span m=''4203690''>Think</span> <span m=''4203850''>of</span> <span m=''4203930''>that</span>
  <span m=''4204120''>as</span> <span m=''4204270''>going</span> <span m=''4204580''>out</span>
  <span m=''4204760''>of</span> <span m=''4204850''>the</span> <span m=''4204920''>board.</span>
  <span m=''4205830''>And</span> <span m=''4205990''>then</span> <span m=''4206160''>in</span>
  <span m=''4206430''>the</span> <span m=''4207520''>plane</span> <span m=''4207780''>of</span>
  <span m=''4207840''>the</span> <span m=''4207920''>board</span> <span m=''4208430''>is</span>
  <span m=''4208610''>this</span> <span m=''4209370''>triangle,</span> <span m=''4210180''>and</span>
  <span m=''4210420''>then I</span> <span m=''4210490''>just</span> <span m=''4210790''>add</span>
  <span m=''4210980''>in</span> <span m=''4211060''>all</span> <span m=''4211180''>the</span>
  <span m=''4211290''>edges</span> <span m=''4211540''>to</span> <span m=''4211640''>make</span>
  <span m=''4211790''>it a</span> <span m=''4211890''>triangulation.</span> </p><p><span
  m=''4213480''>Adding</span> <span m=''4213820''>edges</span> <span m=''4214100''>is</span>
  <span m=''4214290''>a</span> <span m=''4214420''>worry</span> <span m=''4215080''>because</span>
  <span m=''4215360''>that''s</span> <span m=''4215560''>where</span> <span m=''4215710''>we''re</span>
  <span m=''4215870''>allowed</span> <span m=''4216070''>to</span> <span m=''4216160''>cut,</span>
  <span m=''4216500''>so</span> <span m=''4216670''>you</span> <span m=''4216770''>really</span>
  <span m=''4216950''>have</span> <span m=''4217060''>to</span> <span m=''4217160''>worry</span>
  <span m=''4217350''>about</span> <span m=''4217510''>all</span> <span m=''4217620''>those</span>
  <span m=''4217770''>edges</span> <span m=''4218010''>we</span> <span m=''4218403''>add.</span>
  <span m=''4218796''>If</span> <span m=''4219190''>we</span> <span m=''4219340''>add
  them</span> <span m=''4219460''>in</span> <span m=''4219520''>that</span> <span
  m=''4219720''>way,</span> <span m=''4220490''>I</span> <span m=''4220600''>claim,</span>
  <span m=''4221720''>you</span> <span m=''4221890''>take</span> <span m=''4222100''>this--</span>
  <span m=''4222360''>we</span> <span m=''4222480''>call</span> <span m=''4222690''>it</span>
  <span m=''4222870''>the</span> <span m=''4223120''>witch''s</span> <span m=''4223230''>hat--</span>
  <span m=''4224950''>then</span> <span m=''4225160''>you</span> <span m=''4225330''>multiply,</span>
  <span m=''4226450''>in</span> <span m=''4226520''>some</span> <span m=''4226720''>sense,</span>
  <span m=''4227060''>by</span> <span m=''4227950''>a</span> <span m=''4228050''>tetrahedron,</span>
  <span m=''4229690''>meaning</span> <span m=''4230030''>I</span> <span m=''4230110''>take</span>
  <span m=''4230440''>four</span> <span m=''4230770''>copies</span> <span m=''4231210''>of</span>
  <span m=''4231350''>this</span> <span m=''4232000''>hat,</span> <span m=''4232370''>I</span>
  <span m=''4232500''>put</span> <span m=''4232720''>one</span> <span m=''4233030''>on</span>
  <span m=''4233200''>each</span> <span m=''4234270''>face</span> <span m=''4234770''>of</span>
  <span m=''4235050''>the</span> <span m=''4235140''>tetrahedron,</span> <span m=''4236390''>and</span>
  <span m=''4236490''>you</span> <span m=''4236620''>get</span> <span m=''4237330''>that</span>
  <span m=''4237520''>example.</span> </p><p><span m=''4239470''>Here''s</span> <span
  m=''4239680''>one</span> <span m=''4241060''>witch''s</span> <span m=''4241410''>hat</span>
  <span m=''4241690''>and</span> <span m=''4241810''>they''re</span> <span m=''4241920''>just</span>
  <span m=''4242100''>joined</span> <span m=''4242350''>along</span> <span m=''4242610''>edges</span>
  <span m=''4243050''>to</span> <span m=''4243200''>make</span> <span m=''4243410''>the</span>
  <span m=''4243510''>tetrahedron.</span> <span m=''4245550''>You</span> <span m=''4245690''>could</span>
  <span m=''4245800''>do</span> <span m=''4245880''>this</span> <span m=''4246060''>with</span>
  <span m=''4246180''>bigger</span> <span m=''4246440''>polyhedra,</span> <span m=''4246910''>too,</span>
  <span m=''4247130''>like</span> <span m=''4247310''>octahedron,</span> <span m=''4247960''>anything</span>
  <span m=''4248290''>with</span> <span m=''4248870''>equilateral</span> <span m=''4249250''>triangles,</span>
  <span m=''4249800''>but</span> <span m=''4250570''>tetrahedron</span> <span m=''4251130''>is</span>
  <span m=''4251410''>the</span> <span m=''4251500''>smallest</span> <span m=''4251980''>where
  it</span> <span m=''4252090''>works.</span> <span m=''4252410''>Just</span> <span
  m=''4252770''>two of</span> <span m=''4253010''>them</span> <span m=''4253120''>glued</span>
  <span m=''4253440''>face</span> <span m=''4253700''>to</span> <span m=''4253760''>face</span>
  <span m=''4254010''>would</span> <span m=''4254130''>not</span> <span m=''4254320''>work,</span>
  <span m=''4255160''>but</span> <span m=''4255590''>this</span> <span m=''4255800''>way</span>
  <span m=''4256290''>does</span> <span m=''4256460''>work.</span> <span m=''4256760''>Is</span>
  <span m=''4257100''>that</span> <span m=''4257440''>true?</span> <span m=''4262350''>Now</span>
  <span m=''4262800''>I''ve got to</span> <span m=''4263120''>think</span> <span m=''4263310''>about</span>
  <span m=''4263530''>two of</span> <span m=''4263680''>them</span> <span m=''4263840''>joined</span>
  <span m=''4264580''>face</span> <span m=''4264780''>to</span> <span m=''4264880''>face.</span>
  <span m=''4265510''>I</span> <span m=''4265580''>don''t</span> <span m=''4265740''>think</span>
  <span m=''4265890''>it</span> <span m=''4265980''>works.</span> <span m=''4266350''>Otherwise,</span>
  <span m=''4266570''>we would</span> <span m=''4266770''>have</span> <span m=''4266840''>done</span>
  <span m=''4267010''>that.</span> <span m=''4269910''>Oh</span> <span m=''4269970''>yes,</span>
  <span m=''4270530''>I</span> <span m=''4270590''>think</span> <span m=''4270810''>I</span>
  <span m=''4271040''>see</span> <span m=''4271520''>why.</span> </p><p><span m=''4279380''>Why</span>
  <span m=''4279870''>doesn''t</span> <span m=''4280170''>this</span> <span m=''4280380''>work?</span>
  <span m=''4281780''>I</span> <span m=''4281910''>should</span> <span m=''4282120''>say</span>
  <span m=''4282290''>it</span> <span m=''4282390''>doesn''t</span> <span m=''4282680''>work</span>
  <span m=''4282960''>if</span> <span m=''4283100''>the</span> <span m=''4283190''>spikes</span>
  <span m=''4283630''>are</span> <span m=''4283910''>really</span> <span m=''4284440''>tall</span>
  <span m=''4285540''>and</span> <span m=''4285910''>the</span> <span m=''4286300''>base</span>
  <span m=''4286780''>is</span> <span m=''4286990''>really</span> <span m=''4287400''>flat.</span>
  <span m=''4288880''>I''m</span> <span m=''4289060''>going</span> <span m=''4289160''>to</span>
  <span m=''4289240''>define</span> <span m=''4289580''>what</span> <span m=''4289690''>"really"</span>
  <span m=''4289960''>means,</span> <span m=''4290470''>but</span> <span m=''4291420''>we''ll</span>
  <span m=''4291700''>get</span> <span m=''4291880''>there.</span> <span m=''4296790''>So</span>
  <span m=''4296970''>here''s</span> <span m=''4297340''>our</span> <span m=''4298110''>witch''s</span>
  <span m=''4298470''>hat.</span> </p><p><span m=''4303160''>When</span> <span m=''4303310''>this</span>
  <span m=''4303410''>spike</span> <span m=''4303710''>is</span> <span m=''4303820''>really</span>
  <span m=''4304130''>tall,</span> <span m=''4305080''>these</span> <span m=''4305390''>angles,</span>
  <span m=''4306490''>alpha,</span> <span m=''4307430''>are</span> <span m=''4307530''>very</span>
  <span m=''4307750''>close</span> <span m=''4308060''>to</span> <span m=''4308170''>90,</span>
  <span m=''4308660''>a little</span> <span m=''4308930''>bit</span> <span m=''4309050''>under</span>
  <span m=''4309290''>90.</span> <span m=''4310600''>This</span> <span m=''4310980''>angle</span>
  <span m=''4311320''>in</span> <span m=''4311470''>the</span> <span m=''4311590''>floor</span>
  <span m=''4312120''>here--</span> <span m=''4313410''>well,</span> <span m=''4313770''>this</span>
  <span m=''4313990''>angle</span> <span m=''4314280''>in</span> <span m=''4314360''>the</span>
  <span m=''4314440''>floor</span> <span m=''4314880''>is</span> <span m=''4315100''>about</span>
  <span m=''4315490''>60,</span> <span m=''4316440''>probably</span> <span m=''4316720''>actually</span>
  <span m=''4316970''>is</span> <span m=''4317100''>exactly</span> <span m=''4317520''>60.</span>
  <span m=''4317850''>This</span> <span m=''4318040''>is</span> <span m=''4318140''>an</span>
  <span m=''4318200''>equilateral</span> <span m=''4318660''>triangle.</span> <span
  m=''4319900''>So</span> <span m=''4320080''>if</span> <span m=''4320160''>this</span>
  <span m=''4320350''>thing</span> <span m=''4320520''>is</span> <span m=''4320640''>very</span>
  <span m=''4320990''>flat,</span> <span m=''4321950''>this</span> <span m=''4322150''>angle</span>
  <span m=''4322580''>will be</span> <span m=''4322760''>almost</span> <span m=''4323320''>300</span>
  <span m=''4324720''>because</span> <span m=''4324890''>it''s</span> <span m=''4325260''>360</span>
  <span m=''4325770''>minus</span> <span m=''4326310''>60.</span> <span m=''4327250''>It''ll</span>
  <span m=''4327520''>be</span> <span m=''4327660''>a</span> <span m=''4327720''>little</span>
  <span m=''4327980''>bit</span> <span m=''4329710''>less</span> <span m=''4330930''>than</span>
  <span m=''4331050''>300</span> <span m=''4331560''>but</span> <span m=''4332430''>almost</span>
  <span m=''4332770''>300.</span> </p><p><span m=''4335360''>These</span> <span m=''4335540''>matter.</span>
  <span m=''4337950''>In</span> <span m=''4338080''>particular,</span> <span m=''4339280''>the</span>
  <span m=''4339490''>total</span> <span m=''4340440''>sum</span> <span m=''4340650''>of</span>
  <span m=''4340750''>angles</span> <span m=''4341060''>here</span> <span m=''4341800''>is</span>
  <span m=''4342050''>300</span> <span m=''4342770''>plus</span> <span m=''4343260''>twice</span>
  <span m=''4343650''>90,</span> <span m=''4345170''>which</span> <span m=''4345410''>is</span>
  <span m=''4345850''>big.</span> <span m=''4346210''>It''s</span> <span m=''4346390''>bigger</span>
  <span m=''4346610''>than</span> <span m=''4346740''>360.</span> <span m=''4348170''>That''s</span>
  <span m=''4348580''>the</span> <span m=''4348680''>point.</span> <span m=''4348960''>In</span>
  <span m=''4349060''>fact,</span> <span m=''4350080''>300</span> <span m=''4351240''>plus</span>
  <span m=''4351540''>one</span> <span m=''4351920''>of</span> <span m=''4352030''>these</span>
  <span m=''4352240''>angles,</span> <span m=''4352970''>90,</span> <span m=''4353420''>would</span>
  <span m=''4353680''>be</span> <span m=''4354390''>almost</span> <span m=''4354950''>390,</span>
  <span m=''4355840''>which</span> <span m=''4356020''>is</span> <span m=''4356230''>way</span>
  <span m=''4356410''>above</span> <span m=''4356700''>360.</span> <span m=''4358260''>So</span>
  <span m=''4359340''>this</span> <span m=''4359490''>has</span> <span m=''4359620''>negative</span>
  <span m=''4359900''>curvature,</span> <span m=''4360360''>and</span> <span m=''4360430''>even</span>
  <span m=''4360630''>if</span> <span m=''4360720''>you</span> <span m=''4360820''>cut</span>
  <span m=''4361030''>out</span> <span m=''4361180''>one</span> <span m=''4361330''>of</span>
  <span m=''4361450''>the</span> <span m=''4361590''>spike</span> <span m=''4361880''>triangles,</span>
  <span m=''4362330''>it</span> <span m=''4362390''>would</span> <span m=''4362510''>still</span>
  <span m=''4362740''>have</span> <span m=''4362870''>negative</span> <span m=''4363180''>curvature.</span>
  </p><p><span m=''4364480''>That''s</span> <span m=''4364670''>going</span> <span
  m=''4364780''>to</span> <span m=''4364840''>be</span> <span m=''4364950''>bad</span>
  <span m=''4365300''>news</span> <span m=''4366690''>because</span> <span m=''4368240''>let''s</span>
  <span m=''4368840''>just</span> <span m=''4369040''>imagine</span> <span m=''4369500''>for</span>
  <span m=''4369610''>the</span> <span m=''4369710''>moment.</span> <span m=''4369990''>We</span>
  <span m=''4370090''>know</span> <span m=''4370670''>unfolding</span> <span m=''4371130''>things</span>
  <span m=''4371340''>with</span> <span m=''4371400''>boundary is</span> <span m=''4371810''>hard,</span>
  <span m=''4372670''>but</span> <span m=''4372800''>let''s</span> <span m=''4372950''>pretend</span>
  <span m=''4373690''>for</span> <span m=''4373810''>now</span> <span m=''4374160''>that</span>
  <span m=''4374500''>you</span> <span m=''4374690''>wanted</span> <span m=''4374960''>to</span>
  <span m=''4375010''>unfold</span> <span m=''4375370''>a</span> <span m=''4375410''>hat</span>
  <span m=''4375820''>in</span> <span m=''4375980''>isolation.</span> <span m=''4377340''>You</span>
  <span m=''4377430''>wanted</span> <span m=''4377660''>to</span> <span m=''4377710''>unfold</span>
  <span m=''4378230''>it</span> <span m=''4378480''>into</span> <span m=''4378680''>one</span>
  <span m=''4378860''>piece</span> <span m=''4379130''>without</span> <span m=''4379290''>overlap.</span>
  <span m=''4381610''>Think</span> <span m=''4381820''>about</span> <span m=''4382210''>what</span>
  <span m=''4382420''>you</span> <span m=''4382580''>could</span> <span m=''4382740''>do.</span>
  <span m=''4384480''>I</span> <span m=''4384650''>have</span> <span m=''4384840''>to</span>
  <span m=''4384970''>cut</span> <span m=''4385700''>with</span> <span m=''4385950''>a</span>
  <span m=''4386260''>spanning</span> <span m=''4387290''>forest,</span> <span m=''4389110''>I</span>
  <span m=''4389260''>guess,</span> <span m=''4390270''>meaning</span> <span m=''4390620''>it''s</span>
  <span m=''4390880''>acyclic,</span> <span m=''4392080''>it''s</span> <span m=''4392260''>got</span>
  <span m=''4392390''>to</span> <span m=''4392430''>hit</span> <span m=''4392620''>all</span>
  <span m=''4392780''>the</span> <span m=''4392830''>vertices.</span> <span m=''4394030''>There''s</span>
  <span m=''4394240''>only</span> <span m=''4394960''>four</span> <span m=''4395290''>vertices</span>
  <span m=''4395730''>here.</span> <span m=''4396410''>How</span> <span m=''4396630''>could</span>
  <span m=''4396740''>I</span> <span m=''4396800''>hit</span> <span m=''4396940''>all</span>
  <span m=''4397060''>the</span> <span m=''4397130''>vertices</span> <span m=''4398040''>with</span>
  <span m=''4398260''>a</span> <span m=''4398400''>forest?</span> </p><p><span m=''4399500''>You</span>
  <span m=''4399610''>may</span> <span m=''4399760''>recall</span> <span m=''4400230''>from</span>
  <span m=''4400540''>way</span> <span m=''4400670''>back</span> <span m=''4400920''>when</span>
  <span m=''4401130''>that</span> <span m=''4401300''>trees</span> <span m=''4401670''>have</span>
  <span m=''4401880''>leaves.</span> <span m=''4402420''>Every</span> <span m=''4402650''>tree</span>
  <span m=''4402890''>has</span> <span m=''4403080''>at</span> <span m=''4403150''>least</span>
  <span m=''4403400''>two</span> <span m=''4403590''>leaves.</span> <span m=''4405460''>Here</span>
  <span m=''4405660''>I</span> <span m=''4405680''>might</span> <span m=''4405870''>have</span>
  <span m=''4406030''>multiple</span> <span m=''4406400''>trees,</span> <span m=''4406670''>maybe,</span>
  <span m=''4406910''>but</span> <span m=''4407420''>unlikely,</span> <span m=''4408460''>and</span>
  <span m=''4408880''>I</span> <span m=''4408970''>have</span> <span m=''4409110''>to</span>
  <span m=''4409180''>have</span> <span m=''4409290''>at</span> <span m=''4409350''>least</span>
  <span m=''4409550''>to</span> <span m=''4409670''>leaves.</span> <span m=''4409920''>Where</span>
  <span m=''4410210''>could</span> <span m=''4410380''>those</span> <span m=''4410630''>two</span>
  <span m=''4410810''>leaves</span> <span m=''4411110''>be?</span> <span m=''4412150''>Could</span>
  <span m=''4412370''>they</span> <span m=''4412520''>be</span> <span m=''4413080''>at</span>
  <span m=''4413340''>any</span> <span m=''4413800''>leaves</span> <span m=''4414120''>or</span>
  <span m=''4414250''>vertices at</span> <span m=''4414670''>degree</span> <span m=''4414930''>one?</span>
  <span m=''4415500''>Could</span> <span m=''4415690''>they</span> <span m=''4415800''>be</span>
  <span m=''4416290''>at</span> <span m=''4416500''>any</span> <span m=''4416870''>of</span>
  <span m=''4416950''>these</span> <span m=''4417170''>three</span> <span m=''4417310''>vertices?</span>
  <span m=''4418670''>No,</span> <span m=''4418890''>because</span> <span m=''4419100''>they</span>
  <span m=''4419220''>have</span> <span m=''4419390''>negative</span> <span m=''4419730''>curvature.</span>
  <span m=''4420180''>We</span> <span m=''4420300''>know</span> <span m=''4420830''>a</span>
  <span m=''4420890''>vertex</span> <span m=''4421370''>with</span> <span m=''4421450''>negative</span>
  <span m=''4421710''>curvature</span> <span m=''4422040''>has</span> <span m=''4422230''>to</span>
  <span m=''4422310''>have</span> <span m=''4422400''>at</span> <span m=''4422460''>least</span>
  <span m=''4422680''>two</span> <span m=''4422880''>cuts</span> <span m=''4423170''>incident</span>
  <span m=''4423475''>to it.</span> <span m=''4423780''>You</span> <span m=''4423890''>can''t</span>
  <span m=''4424260''>stop</span> <span m=''4425460''>at</span> <span m=''4425620''>these</span>
  <span m=''4425830''>three</span> <span m=''4425990''>vertices.</span> <span m=''4426960''>That</span>
  <span m=''4427180''>only</span> <span m=''4427460''>leaves</span> <span m=''4427700''>one</span>
  <span m=''4428040''>vertex</span> <span m=''4429640''>and</span> <span m=''4429850''>the</span>
  <span m=''4429920''>boundary.</span> </p><p><span m=''4432030''>So</span> <span
  m=''4432450''>the</span> <span m=''4432560''>only</span> <span m=''4432850''>thing</span>
  <span m=''4432960''>you</span> <span m=''4433080''>can</span> <span m=''4433200''>do</span>
  <span m=''4433310''>if</span> <span m=''4433390''>you</span> <span m=''4433510''>want</span>
  <span m=''4433660''>to</span> <span m=''4433700''>visit</span> <span m=''4433990''>all</span>
  <span m=''4434190''>the</span> <span m=''4434250''>vertices</span> <span m=''4435280''>and</span>
  <span m=''4435480''>start</span> <span m=''4435800''>somewhere</span> <span m=''4436050''>on</span>
  <span m=''4436120''>the</span> <span m=''4436190''>boundary</span> <span m=''4436650''>and</span>
  <span m=''4436860''>get</span> <span m=''4437130''>to</span> <span m=''4437240''>the</span>
  <span m=''4437330''>x,</span> <span m=''4437840''>get</span> <span m=''4438000''>to</span>
  <span m=''4438100''>the</span> <span m=''4438180''>peak.</span> <span m=''4445280''>That''s</span>
  <span m=''4445590''>all</span> <span m=''4445740''>you</span> <span m=''4445900''>can</span>
  <span m=''4446060''>do.</span> <span m=''4446390''>You</span> <span m=''4446500''>couldn''t</span>
  <span m=''4446760''>have</span> <span m=''4447050''>multiple</span> <span m=''4447670''>connections</span>
  <span m=''4448080''>to</span> <span m=''4448180''>the</span> <span m=''4448270''>boundary</span>
  <span m=''4448600''>because</span> <span m=''4448730''>then</span> <span m=''4448880''>you</span>
  <span m=''4448970''>would</span> <span m=''4449040''>disconnect.</span> <span m=''4450780''>Then</span>
  <span m=''4450930''>there''s</span> <span m=''4451090''>really</span> <span m=''4451410''>only</span>
  <span m=''4451670''>two</span> <span m=''4451850''>choices</span> <span m=''4452340''>and</span>
  <span m=''4452440''>they''re</span> <span m=''4453580''>reflectionally</span> <span
  m=''4453845''>symmetric.</span> </p><p><span m=''4456480''>And</span> <span m=''4456590''>we''re</span>
  <span m=''4456710''>only</span> <span m=''4456960''>allowed</span> <span m=''4457160''>to</span>
  <span m=''4457210''>go</span> <span m=''4457320''>along</span> <span m=''4457570''>edges.</span>
  <span m=''4458310''>It''s</span> <span m=''4458490''>super</span> <span m=''4458850''>constrained.</span>
  <span m=''4459760''>You</span> <span m=''4459880''>can</span> <span m=''4459970''>go</span>
  <span m=''4460120''>here,</span> <span m=''4460430''>walk</span> <span m=''4460690''>around,</span>
  <span m=''4460970''>and</span> <span m=''4461050''>go</span> <span m=''4461180''>up,</span>
  <span m=''4461870''>or</span> <span m=''4462130''>you can</span> <span m=''4462260''>walk</span>
  <span m=''4462520''>around</span> <span m=''4462690''>the</span> <span m=''4462780''>other</span>
  <span m=''4462930''>way</span> <span m=''4463070''>and</span> <span m=''4463150''>go</span>
  <span m=''4463260''>up.</span> <span m=''4464440''>Those</span> <span m=''4464620''>are</span>
  <span m=''4464690''>actually</span> <span m=''4464960''>slightly</span> <span m=''4465370''>different</span>
  <span m=''4465750''>because</span> <span m=''4466230''>you</span> <span m=''4466350''>have</span>
  <span m=''4466480''>two</span> <span m=''4466630''>choices</span> <span m=''4467050''>of</span>
  <span m=''4467140''>which</span> <span m=''4467330''>edge</span> <span m=''4467540''>to</span>
  <span m=''4467640''>follow</span> <span m=''4467890''>here.</span> <span m=''4469280''>They''re</span>
  <span m=''4469480''>both</span> <span m=''4471280''>screwed</span> <span m=''4472040''>because</span>
  <span m=''4472810''>if</span> <span m=''4473070''>you</span> <span m=''4473240''>look</span>
  <span m=''4473430''>at</span> <span m=''4473550''>this</span> <span m=''4473780''>point,</span>
  <span m=''4474610''>the</span> <span m=''4474720''>white</span> <span m=''4474960''>dot,</span>
  <span m=''4475652''>or</span> <span m=''4476000''>the</span> <span m=''4476110''>white</span>
  <span m=''4476320''>dot</span> <span m=''4476540''>up</span> <span m=''4476690''>there,</span>
  <span m=''4477690''>what</span> <span m=''4477880''>remains</span> <span m=''4478480''>here</span>
  <span m=''4478860''>on</span> <span m=''4479130''>the</span> <span m=''4479400''>outside</span>
  <span m=''4480610''>is</span> <span m=''4481800''>almost</span> <span m=''4482170''>300</span>
  <span m=''4482510''>degrees</span> <span m=''4482790''>of</span> <span m=''4482850''>material</span>
  <span m=''4483290''>on</span> <span m=''4483390''>the</span> <span m=''4483470''>base</span>
  <span m=''4484230''>plus</span> <span m=''4484710''>one</span> <span m=''4485110''>of</span>
  <span m=''4485230''>the</span> <span m=''4485330''>90</span> <span m=''4485600''>degree</span>
  <span m=''4485870''>faces,</span> <span m=''4486290''>the</span> <span m=''4486380''>back</span>
  <span m=''4486670''>one</span> <span m=''4486840''>that</span> <span m=''4486940''>you</span>
  <span m=''4487040''>can''t</span> <span m=''4487330''>see.</span> <span m=''4487910''>It''s</span>
  <span m=''4488090''>easier</span> <span m=''4488430''>to</span> <span m=''4488510''>see</span>
  <span m=''4488690''>here.</span> <span m=''4489320''>You</span> <span m=''4489390''>have</span>
  <span m=''4489510''>the</span> <span m=''4489580''>300</span> <span m=''4490000''>degrees</span>
  <span m=''4490270''>on</span> <span m=''4490340''>the</span> <span m=''4490410''>bottom</span>
  <span m=''4491200''>and</span> <span m=''4491390''>then</span> <span m=''4491530''>the</span>
  <span m=''4491640''>white</span> <span m=''4492180''>face</span> <span m=''4492810''>is</span>
  <span m=''4492970''>still</span> <span m=''4493190''>attached</span> <span m=''4493640''>to</span>
  <span m=''4493770''>it,</span> <span m=''4494630''>and</span> <span m=''4494830''>that''s</span>
  <span m=''4495220''>almost</span> <span m=''4495680''>390.</span> <span m=''4497540''>When</span>
  <span m=''4497730''>you</span> <span m=''4497840''>flatten</span> <span m=''4498190''>that</span>
  <span m=''4498390''>thing,</span> <span m=''4498670''>it''s</span> <span m=''4498790''>going</span>
  <span m=''4498910''>to</span> <span m=''4498950''>overlap</span> <span m=''4499380''>itself</span>
  <span m=''4499840''>at</span> <span m=''4500040''>that</span> <span m=''4500220''>point.</span>
  <span m=''4501650''>Bad</span> <span m=''4502030''>news.</span> </p><p><span m=''4503020''>So</span>
  <span m=''4503200''>this</span> <span m=''4503360''>just</span> <span m=''4503510''>says,</span>
  <span m=''4503970''>if</span> <span m=''4504120''>I</span> <span m=''4504160''>look</span>
  <span m=''4504350''>at</span> <span m=''4504410''>a</span> <span m=''4504430''>hat
  in</span> <span m=''4504740''>isolation,</span> <span m=''4505810''>it</span> <span
  m=''4505990''>can''t</span> <span m=''4506290''>unfold,</span> <span m=''4507490''>but</span>
  <span m=''4507590''>that''s</span> <span m=''4507670''>not</span> <span m=''4507830''>what</span>
  <span m=''4507950''>I</span> <span m=''4508010''>care</span> <span m=''4508290''>about.</span>
  <span m=''4508510''>I</span> <span m=''4508580''>care</span> <span m=''4508850''>about</span>
  <span m=''4509330''>four</span> <span m=''4509670''>of</span> <span m=''4509750''>them</span>
  <span m=''4509930''>joined</span> <span m=''4510260''>together.</span> <span m=''4517050''>Suppose</span>
  <span m=''4517440''>you</span> <span m=''4517530''>had</span> <span m=''4517680''>some</span>
  <span m=''4517820''>unfolding</span> <span m=''4518190''>of</span> <span m=''4518280''>the</span>
  <span m=''4518350''>whole</span> <span m=''4518630''>thing,</span> <span m=''4519550''>and</span>
  <span m=''4519710''>then</span> <span m=''4519850''>I</span> <span m=''4519900''>look</span>
  <span m=''4520150''>at,</span> <span m=''4520290''>well,</span> <span m=''4520645''>what</span>
  <span m=''4521000''>cuts</span> <span m=''4521290''>happen</span> <span m=''4521710''>within</span>
  <span m=''4524810''>the</span> <span m=''4524920''>witch''s</span> <span m=''4525220''>hat?</span>
  <span m=''4527090''>I</span> <span m=''4527220''>know</span> <span m=''4527390''>the</span>
  <span m=''4527500''>witch''s</span> <span m=''4527770''>hat</span> <span m=''4527970''>cannot</span>
  <span m=''4528310''>remain</span> <span m=''4528670''>in</span> <span m=''4528790''>one</span>
  <span m=''4529010''>piece.</span> <span m=''4529460''>Therefore,</span> <span m=''4529790''>it
  must</span> <span m=''4530010''>be</span> <span m=''4530110''>disconnected</span>
  <span m=''4530780''>into</span> <span m=''4530980''>multiple</span> <span m=''4531400''>pieces,</span>
  <span m=''4532840''>something</span> <span m=''4533270''>like</span> <span m=''4533470''>this.</span>
  <span m=''4535100''>Again,</span> <span m=''4535870''>the</span> <span m=''4536010''>cuts</span>
  <span m=''4536330''>have</span> <span m=''4536690''>to</span> <span m=''4536790''>visit</span>
  <span m=''4537560''>all</span> <span m=''4537770''>the</span> <span m=''4537840''>vertices</span>
  <span m=''4538310''>somehow,</span> <span m=''4545050''>but</span> <span m=''4546190''>we</span>
  <span m=''4546360''>know</span> <span m=''4546640''>from</span> <span m=''4546830''>the</span>
  <span m=''4546950''>perspective</span> <span m=''4547390''>of</span> <span m=''4547490''>a</span>
  <span m=''4547570''>single</span> <span m=''4547890''>hat,</span> <span m=''4548320''>that</span>
  <span m=''4548640''>hat</span> <span m=''4548900''>must</span> <span m=''4549210''>split</span>
  <span m=''4549580''>into</span> <span m=''4549810''>two</span> <span m=''4550010''>parts.</span>
  </p><p><span m=''4551590''>There</span> <span m=''4551690''>are</span> <span m=''4552780''>lots</span>
  <span m=''4553000''>of</span> <span m=''4553070''>things</span> <span m=''4553230''>you</span>
  <span m=''4553340''>could</span> <span m=''4553480''>consider.</span> <span m=''4554430''>Let''s</span>
  <span m=''4554640''>suppose</span> <span m=''4554960''>this</span> <span m=''4555130''>is</span>
  <span m=''4555230''>possible,</span> <span m=''4556700''>not</span> <span m=''4556850''>even</span>
  <span m=''4557060''>worry</span> <span m=''4557300''>about</span> <span m=''4557570''>these</span>
  <span m=''4557740''>kinds</span> <span m=''4557940''>of</span> <span m=''4558000''>pictures.</span>
  <span m=''4559540''>Well,</span> <span m=''4559760''>I</span> <span m=''4559900''>claim</span>
  <span m=''4561590''>we</span> <span m=''4561710''>have</span> <span m=''4561910''>a</span>
  <span m=''4561980''>problem.</span> </p><p><span m=''4587710''>Here''s</span> <span
  m=''4587900''>a</span> <span m=''4587970''>tetrahedron.</span> <span m=''4591410''>These</span>
  <span m=''4591720''>vertices</span> <span m=''4592110''>are</span> <span m=''4592220''>all</span>
  <span m=''4592310''>the</span> <span m=''4592400''>same</span> <span m=''4593010''>point,</span>
  <span m=''4593440''>actually.</span> <span m=''4594450''>I''ve</span> <span m=''4594560''>just</span>
  <span m=''4594750''>unfolded</span> <span m=''4595190''>the</span> <span m=''4595290''>tetrahedron</span>
  <span m=''4595810''>because</span> <span m=''4595980''>it''s</span> <span m=''4596100''>way</span>
  <span m=''4596300''>easier to</span> <span m=''4596670''>draw</span> <span m=''4597190''>in</span>
  <span m=''4597370''>two</span> <span m=''4597540''>dimensions.</span> <span m=''4601720''>So</span>
  <span m=''4601840''>if</span> <span m=''4601940''>I</span> <span m=''4602000''>look</span>
  <span m=''4602260''>at</span> <span m=''4602380''>the</span> <span m=''4602520''>hat</span>
  <span m=''4602775''>that</span> <span m=''4603030''>is</span> <span m=''4603530''>on</span>
  <span m=''4603760''>this</span> <span m=''4603930''>triangle,</span> <span m=''4606670''>this</span>
  <span m=''4606860''>hat</span> <span m=''4607070''>gets</span> <span m=''4607260''>disconnected</span>
  <span m=''4607720''>into</span> <span m=''4607990''>two</span> <span m=''4608150''>parts.</span>
  <span m=''4609070''>There''s</span> <span m=''4609230''>only</span> <span m=''4609530''>three</span>
  <span m=''4610400''>connection</span> <span m=''4610780''>points</span> <span m=''4611090''>to
  the</span> <span m=''4611210''>rest</span> <span m=''4611460''>of</span> <span m=''4611500''>the</span>
  <span m=''4611580''>world.</span> </p><p><span m=''4612300''>So</span> <span m=''4612500''>what</span>
  <span m=''4612660''>these</span> <span m=''4612830''>pictures</span> <span m=''4613160''>have</span>
  <span m=''4613420''>to</span> <span m=''4613540''>look</span> <span m=''4613730''>like</span>
  <span m=''4614530''>is</span> <span m=''4614780''>they</span> <span m=''4614890''>connect</span>
  <span m=''4615590''>two</span> <span m=''4615860''>of</span> <span m=''4615980''>the</span>
  <span m=''4616060''>vertices</span> <span m=''4617320''>by</span> <span m=''4617540''>a</span>
  <span m=''4617610''>collection</span> <span m=''4617970''>of</span> <span m=''4618060''>cuts.</span>
  <span m=''4619590''>If</span> <span m=''4619710''>you''re</span> <span m=''4619800''>going</span>
  <span m=''4619890''>to</span> <span m=''4619950''>cut</span> <span m=''4620140''>into</span>
  <span m=''4620340''>two</span> <span m=''4620615''>halves,</span> <span m=''4620890''>you''ve</span>
  <span m=''4621040''>got</span> <span m=''4621210''>to</span> <span m=''4621250''>have</span>
  <span m=''4621420''>a</span> <span m=''4621490''>path</span> <span m=''4621890''>across,</span>
  <span m=''4623380''>and</span> <span m=''4623520''>there''s</span> <span m=''4623650''>only</span>
  <span m=''4623870''>three</span> <span m=''4624030''>vertices</span> <span m=''4624520''>to</span>
  <span m=''4625230''>visit.</span> <span m=''4628150''>There''s</span> <span m=''4628290''>some</span>
  <span m=''4628630''>collection</span> <span m=''4629020''>of</span> <span m=''4629250''>cuts</span>
  <span m=''4629550''>that</span> <span m=''4629650''>go</span> <span m=''4629870''>from,</span>
  <span m=''4630340''>let''s</span> <span m=''4630430''>say,</span> <span m=''4630510''>this</span>
  <span m=''4630710''>vertex to</span> <span m=''4631040''>this</span> <span m=''4631240''>vertex.</span>
  <span m=''4631570''>At</span> <span m=''4631640''>this</span> <span m=''4631810''>point,</span>
  <span m=''4632080''>everything''s</span> <span m=''4632290''>symmetric.</span> <span
  m=''4633440''>Maybe</span> <span m=''4633770''>it would</span> <span m=''4634100''>be</span>
  <span m=''4634200''>more</span> <span m=''4634390''>obvious</span> <span m=''4634700''>if
  I</span> <span m=''4634800''>started</span> <span m=''4635110''>the</span> <span
  m=''4635180''>center.</span> <span m=''4636760''>It</span> <span m=''4636960''>could</span>
  <span m=''4637110''>be</span> <span m=''4637270''>from</span> <span m=''4637440''>here</span>
  <span m=''4637690''>to</span> <span m=''4637750''>there,</span> <span m=''4638110''>could</span>
  <span m=''4638230''>be</span> <span m=''4638340''>from</span> <span m=''4638470''>here
  to</span> <span m=''4638680''>there or</span> <span m=''4639120''>from</span> <span
  m=''4639280''>here</span> <span m=''4639460''>to</span> <span m=''4639530''>there,</span>
  <span m=''4640180''>but</span> <span m=''4640320''>at</span> <span m=''4640390''>least</span>
  <span m=''4640590''>one</span> <span m=''4640740''>of</span> <span m=''4640790''>those</span>
  <span m=''4640960''>things</span> <span m=''4641170''>exist,</span> <span m=''4642190''>and</span>
  <span m=''4642840''>by</span> <span m=''4642980''>rotational</span> <span m=''4643490''>symmetry</span>
  <span m=''4643880''>of</span> <span m=''4643950''>this</span> <span m=''4644080''>diagram,</span>
  <span m=''4644900''>say it''s</span> <span m=''4645120''>that</span> <span m=''4645290''>one.</span>
  </p><p><span m=''4647990''>Well,</span> <span m=''4648540''>what</span> <span m=''4648710''>happens</span>
  <span m=''4649240''>to</span> <span m=''4649390''>this</span> <span m=''4649620''>face?</span>
  <span m=''4650540''>Could</span> <span m=''4650770''>there</span> <span m=''4650900''>be</span>
  <span m=''4651100''>something</span> <span m=''4651440''>like</span> <span m=''4651640''>this?</span>
  <span m=''4652780''>No,</span> <span m=''4653940''>because</span> <span m=''4654680''>then</span>
  <span m=''4654940''>this</span> <span m=''4655180''>would</span> <span m=''4655360''>be</span>
  <span m=''4655590''>disconnected</span> <span m=''4656170''>from</span> <span m=''4656330''>the</span>
  <span m=''4656390''>rest</span> <span m=''4656630''>of</span> <span m=''4656690''>the</span>
  <span m=''4656760''>world.</span> <span m=''4658480''>So</span> <span m=''4658670''>suddenly,</span>
  <span m=''4659250''>this</span> <span m=''4659520''>hat</span> <span m=''4659810''>is</span>
  <span m=''4660020''>constrained.</span> <span m=''4661720''>Maybe</span> <span m=''4662110''>it</span>
  <span m=''4662210''>could</span> <span m=''4662380''>look</span> <span m=''4662550''>like</span>
  <span m=''4662760''>this.</span> <span m=''4664020''>You</span> <span m=''4664190''>have</span>
  <span m=''4664290''>a</span> <span m=''4664350''>choice.</span> <span m=''4664640''>It</span>
  <span m=''4664730''>could</span> <span m=''4664870''>look</span> <span m=''4665050''>like</span>
  <span m=''4665190''>that</span> <span m=''4665670''>or</span> <span m=''4665870''>like</span>
  <span m=''4666040''>that,</span> <span m=''4666400''>but</span> <span m=''4666450''>by</span>
  <span m=''4666580''>reflectional</span> <span m=''4667050''>symmetry,</span> <span
  m=''4667560''>same</span> <span m=''4667850''>thing.</span> <span m=''4668100''>So</span>
  <span m=''4668290''>let''s</span> <span m=''4668460''>say</span> <span m=''4668550''>this</span>
  <span m=''4668770''>one.</span> <span m=''4669740''>Remember,</span> <span m=''4670000''>x</span>
  <span m=''4670290''>is</span> <span m=''4670420''>the</span> <span m=''4670490''>same</span>
  <span m=''4670760''>everywhere.</span> </p><p><span m=''4673100''>Well,</span> <span
  m=''4673230''>that</span> <span m=''4673440''>means</span> <span m=''4674060''>this</span>
  <span m=''4674530''>is</span> <span m=''4674660''>impossible</span> <span m=''4676280''>because</span>
  <span m=''4677020''>this</span> <span m=''4677260''>edge</span> <span m=''4677490''>is</span>
  <span m=''4677590''>actually</span> <span m=''4677890''>glued</span> <span m=''4678170''>to</span>
  <span m=''4678260''>this</span> <span m=''4678500''>edge,</span> <span m=''4679420''>and</span>
  <span m=''4679670''>so</span> <span m=''4679780''>then</span> <span m=''4679970''>this</span>
  <span m=''4680360''>thing</span> <span m=''4680610''>would</span> <span m=''4680750''>be</span>
  <span m=''4680860''>disconnected</span> <span m=''4681440''>from</span> <span m=''4681570''>the</span>
  <span m=''4681640''>rest</span> <span m=''4681890''>of</span> <span m=''4681950''>the</span>
  <span m=''4682030''>world.</span> <span m=''4683220''>So</span> <span m=''4683820''>there''s</span>
  <span m=''4684010''>a</span> <span m=''4684090''>couple</span> <span m=''4684380''>of</span>
  <span m=''4684460''>possibilities.</span> <span m=''4685280''>It</span> <span m=''4685360''>could</span>
  <span m=''4685590''>look</span> <span m=''4685800''>like</span> <span m=''4686700''>this,</span>
  <span m=''4687500''>or it</span> <span m=''4687790''>could</span> <span m=''4687990''>look</span>
  <span m=''4688190''>like</span> <span m=''4688530''>this.</span> <span m=''4692700''>It</span>
  <span m=''4692740''>was</span> <span m=''4692850''>one</span> <span m=''4693050''>of</span>
  <span m=''4693100''>those</span> <span m=''4693300''>two</span> <span m=''4693460''>for</span>
  <span m=''4693580''>this</span> <span m=''4693780''>face.</span> <span m=''4694000''>We''ve</span>
  <span m=''4694070''>got</span> <span m=''4694210''>one</span> <span m=''4694410''>face</span>
  <span m=''4694670''>left.</span> </p><p><span m=''4698120''>This</span> <span m=''4699060''>is</span>
  <span m=''4699220''>impossible</span> <span m=''4701100''>because</span> <span m=''4701690''>this</span>
  <span m=''4701900''>edge</span> <span m=''4702110''>glues</span> <span m=''4702370''>to</span>
  <span m=''4702470''>this</span> <span m=''4702750''>one,</span> <span m=''4703190''>so</span>
  <span m=''4703340''>imagine</span> <span m=''4703720''>this</span> <span m=''4703920''>thing</span>
  <span m=''4704140''>being</span> <span m=''4704330''>picked</span> <span m=''4704610''>up</span>
  <span m=''4704730''>and</span> <span m=''4704820''>moved</span> <span m=''4705080''>over</span>
  <span m=''4705280''>here.</span> <span m=''4706070''>So we</span> <span m=''4706130''>have</span>
  <span m=''4706310''>a</span> <span m=''4706360''>wiggly</span> <span m=''4706680''>line</span>
  <span m=''4706930''>here</span> <span m=''4707290''>and</span> <span m=''4707460''>then</span>
  <span m=''4707650''>this</span> <span m=''4707760''>stuff,</span> <span m=''4708770''>and</span>
  <span m=''4708960''>so</span> <span m=''4709040''>that</span> <span m=''4709260''>would</span>
  <span m=''4709370''>be</span> <span m=''4709500''>disconnected</span> <span m=''4709990''>from</span>
  <span m=''4710110''>the</span> <span m=''4710180''>rest</span> <span m=''4710410''>of</span>
  <span m=''4710450''>the</span> <span m=''4710530''>world,</span> <span m=''4711310''>so</span>
  <span m=''4711440''>that</span> <span m=''4711690''>can''t</span> <span m=''4711870''>happen.</span>
  <span m=''4713660''>What</span> <span m=''4713930''>about</span> <span m=''4715450''>this</span>
  <span m=''4715820''>one?</span> <span m=''4716660''>Is</span> <span m=''4716960''>that</span>
  <span m=''4717300''>the</span> <span m=''4717390''>harder</span> <span m=''4717650''>one?</span>
  <span m=''4718340''>I don''t</span> <span m=''4718730''>know.</span> <span m=''4721330''>It''s</span>
  <span m=''4721540''>been</span> <span m=''4721660''>a</span> <span m=''4721760''>while</span>
  <span m=''4722030''>since</span> <span m=''4722220''>I''ve</span> <span m=''4722340''>used</span>
  <span m=''4722560''>the</span> <span m=''4722670''>argument.</span> </p><p><span
  m=''4723280''>If</span> <span m=''4723400''>we</span> <span m=''4723470''>have</span>
  <span m=''4723640''>this</span> <span m=''4724510''>together</span> <span m=''4724790''>with</span>
  <span m=''4724920''>this,</span> <span m=''4725200''>that''s</span> <span m=''4725390''>clearly</span>
  <span m=''4725700''>bad</span> <span m=''4725970''>because</span> <span m=''4726140''>that</span>
  <span m=''4726330''>forms</span> <span m=''4726560''>a</span> <span m=''4726630''>cycle.</span>
  <span m=''4728010''>No</span> <span m=''4728440''>good.</span> <span m=''4730290''>But</span>
  <span m=''4730400''>what</span> <span m=''4730530''>if</span> <span m=''4730650''>I</span>
  <span m=''4730730''>have</span> <span m=''4731020''>this</span> <span m=''4731310''>together</span>
  <span m=''4731660''>with</span> <span m=''4731890''>this</span> <span m=''4732080''>one?</span>
  <span m=''4737380''>It</span> <span m=''4737510''>gets</span> <span m=''4737650''>hard</span>
  <span m=''4737830''>to</span> <span m=''4737880''>see.</span> <span m=''4742130''>It''s</span>
  <span m=''4742340''>bad.</span> <span m=''4743110''>It''s</span> <span m=''4743300''>a</span>
  <span m=''4743370''>cycle.</span> <span m=''4743990''>It</span> <span m=''4744340''>starts</span>
  <span m=''4745310''>and</span> <span m=''4745520''>ends</span> <span m=''4745800''>at</span>
  <span m=''4745920''>x,</span> <span m=''4747150''>and</span> <span m=''4747380''>if</span>
  <span m=''4747480''>you</span> <span m=''4747600''>fold</span> <span m=''4747910''>it</span>
  <span m=''4747970''>up</span> <span m=''4748160''>right,</span> <span m=''4748370''>you''ll</span>
  <span m=''4748500''>see</span> <span m=''4748640''>there''s</span> <span m=''4748800''>really</span>
  <span m=''4749030''>two</span> <span m=''4749170''>sides</span> <span m=''4749500''>to</span>
  <span m=''4749570''>that</span> <span m=''4749770''>cycle.</span> <span m=''4750470''>It''s</span>
  <span m=''4750610''>actually</span> <span m=''4750860''>forced,</span> <span m=''4751700''>so</span>
  <span m=''4752040''>that''s</span> <span m=''4752180''>bad.</span> </p><p><span
  m=''4753550''>All</span> <span m=''4753630''>right,</span> <span m=''4753940''>one</span>
  <span m=''4754110''>more</span> <span m=''4754250''>choice,</span> <span m=''4756880''>this</span>
  <span m=''4757120''>one.</span> <span m=''4759380''>If</span> <span m=''4759630''>I</span>
  <span m=''4759710''>do</span> <span m=''4760320''>this</span> <span m=''4760840''>together</span>
  <span m=''4761240''>with</span> <span m=''4761500''>this</span> <span m=''4761730''>one,</span>
  <span m=''4762640''>that''s</span> <span m=''4762870''>going</span> <span m=''4762990''>to</span>
  <span m=''4763060''>be</span> <span m=''4763180''>bad</span> <span m=''4763470''>because</span>
  <span m=''4763670''>that''s</span> <span m=''4763860''>a</span> <span m=''4763930''>cycle.</span>
  <span m=''4764310''>We</span> <span m=''4764400''>start</span> <span m=''4764680''>and</span>
  <span m=''4764790''>end</span> <span m=''4764990''>at</span> <span m=''4765120''>x.</span>
  <span m=''4767360''>What</span> <span m=''4767640''>if</span> <span m=''4767800''>I</span>
  <span m=''4767890''>do</span> <span m=''4768660''>this</span> <span m=''4769010''>one</span>
  <span m=''4769630''>and</span> <span m=''4769780''>that</span> <span m=''4770010''>one?</span>
  <span m=''4770190''>Well,</span> <span m=''4770310''>that''s</span> <span m=''4770520''>also</span>
  <span m=''4770800''>bad</span> <span m=''4771060''>because</span> <span m=''4771240''>here''s</span>
  <span m=''4771430''>a</span> <span m=''4771490''>cycle</span> <span m=''4772010''>that</span>
  <span m=''4772110''>starts</span> <span m=''4772340''>at</span> <span m=''4772410''>x,</span>
  <span m=''4772780''>ends</span> <span m=''4772980''>at</span> <span m=''4773450''>x.</span>
  <span m=''4773880''>This and</span> <span m=''4774180''>this</span> <span m=''4774410''>form</span>
  <span m=''4774660''>the</span> <span m=''4775015''>inner of the</span> <span m=''4775370''>cycle.</span>
  <span m=''4776540''>All</span> <span m=''4776770''>cases</span> <span m=''4777510''>are</span>
  <span m=''4777660''>bad,</span> <span m=''4778970''>so</span> <span m=''4779360''>no</span>
  <span m=''4780660''>edge</span> <span m=''4782260''>unfolding.</span> <span m=''4786960''>Tragic.</span>
  </p><p><span m=''4789910''>We</span> <span m=''4790020''>can</span> <span m=''4790160''>think</span>
  <span m=''4790350''>briefly</span> <span m=''4790720''>about</span> <span m=''4790930''>the</span>
  <span m=''4791020''>case--</span> <span m=''4791660''>do I</span> <span m=''4792090''>have</span>
  <span m=''4792160''>time?</span> <span m=''4792680''>I</span> <span m=''4792880''>have</span>
  <span m=''4793100''>10</span> <span m=''4793300''>seconds.</span> <span m=''4794720''>About</span>
  <span m=''4795010''>the</span> <span m=''4795100''>case</span> <span m=''4795360''>where</span>
  <span m=''4795490''>there</span> <span m=''4795730''>are</span> <span m=''4795980''>two</span>
  <span m=''4796180''>triangles.</span> <span m=''4796960''>I</span> <span m=''4797040''>guess</span>
  <span m=''4797280''>I</span> <span m=''4797300''>should</span> <span m=''4797510''>draw</span>
  <span m=''4797680''>them</span> <span m=''4799350''>like</span> <span m=''4799770''>this.</span>
  <span m=''4801960''>So</span> <span m=''4802020''>this</span> <span m=''4802250''>point</span>
  <span m=''4803290''>is</span> <span m=''4803490''>the</span> <span m=''4803550''>same</span>
  <span m=''4803830''>as</span> <span m=''4803940''>this</span> <span m=''4804140''>point.</span>
  <span m=''4805340''>So</span> <span m=''4805380''>if</span> <span m=''4805500''>I</span>
  <span m=''4805580''>try</span> <span m=''4805780''>to</span> <span m=''4805890''>simplify</span>
  <span m=''4806360''>this,</span> <span m=''4806550''>instead</span> <span m=''4806760''>of</span>
  <span m=''4806840''>using</span> <span m=''4807070''>four</span> <span m=''4807330''>hats,</span>
  <span m=''4807650''>I</span> <span m=''4807690''>just</span> <span m=''4807890''>use</span>
  <span m=''4808080''>two</span> <span m=''4808230''>hats,</span> <span m=''4808650''>put</span>
  <span m=''4808760''>one</span> <span m=''4808930''>here,</span> <span m=''4809230''>one</span>
  <span m=''4809280''>here.</span> <span m=''4810220''>Then</span> <span m=''4811480''>I</span>
  <span m=''4811620''>could</span> <span m=''4811830''>do</span> <span m=''4812150''>something</span>
  <span m=''4812620''>like</span> <span m=''4814070''>this,</span> <span m=''4814660''>I</span>
  <span m=''4814760''>think,</span> <span m=''4816060''>and</span> <span m=''4816200''>maybe</span>
  <span m=''4816450''>that''s</span> <span m=''4816670''>OK</span> <span m=''4818060''>if</span>
  <span m=''4818200''>there''s</span> <span m=''4818370''>no</span> <span m=''4818490''>cycle</span>
  <span m=''4818870''>formed</span> <span m=''4819110''>there.</span> <span m=''4820530''>So</span>
  <span m=''4820720''>we</span> <span m=''4820840''>really</span> <span m=''4821160''>needed</span>
  <span m=''4821770''>the</span> <span m=''4821890''>tetrahedron</span> <span m=''4822520''>somehow.</span>
  <span m=''4823240''>I</span> <span m=''4823340''>think</span> <span m=''4823500''>it</span>
  <span m=''4823580''>does</span> <span m=''4823740''>work</span> <span m=''4823920''>for</span>
  <span m=''4824190''>octahedron</span> <span m=''4824380''>and</span> <span m=''4824640''>larger</span>
  <span m=''4824980''>also,</span> <span m=''4826080''>but</span> <span m=''4826360''>just
  two</span> <span m=''4826690''>triangles</span> <span m=''4826970''>is</span> <span
  m=''4827250''>not</span> <span m=''4827440''>enough.</span> </p><p><span m=''4829610''>And</span>
  <span m=''4830440''>that</span> <span m=''4830780''>is</span> <span m=''4831690''>unfolding.</span>
  <span m=''4832875''>We</span> <span m=''4833330''>did</span> <span m=''4833900''>not</span>
  <span m=''4834120''>always</span> <span m=''4834640''>edge</span> <span m=''4834970''>foldable</span>
  <span m=''4835410''>for</span> <span m=''4835550''>general</span> <span m=''4835850''>polyhedra,</span>
  <span m=''4836770''>even</span> <span m=''4837080''>topologically</span> <span m=''4837770''>convex</span>
  <span m=''4838190''>polyhedra.</span> <span m=''4839280''>Next</span> <span m=''4839450''>time,</span>
  <span m=''4839590''>we''ll</span> <span m=''4839690''>talk</span> <span m=''4839910''>more</span>
  <span m=''4840110''>about</span> <span m=''4840340''>general</span> <span m=''4840670''>unfolding</span>
  <span m=''4841210''>of</span> <span m=''4841440''>arbitrary</span> <span m=''4841890''>polyhedra.</span>
  </p>'
type: course
uid: b850f671a0e779b2c326bdc52ba0e18d

---
None