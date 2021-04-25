---
about_this_resource_text: <p><strong>Description:</strong> This lecture explores algorithms
  for unfolding 2D chains including ODE, pointed pseudotriangulations, and the energy
  method. Locking rules are then extrapolated to address Spherical Carpenter's Rule,
  infinitesimally locked linkages, and locked 3D chains.</p> <p><strong>Speaker:</strong>
  Erik Demaine</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: wPPf9S7IiAs
  parent_uid: 9631a66a55cf940a72c3a1dd0aa3dc53
  title: Video-YouTube-Stream
  type: Video
  uid: ce31b7b8e946649c0dfb7cfcb87401d3
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/wPPf9S7IiAs/default.jpg
  parent_uid: 9631a66a55cf940a72c3a1dd0aa3dc53
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: f59609dda4087fbfd04657cecf8c51a0
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: 9631a66a55cf940a72c3a1dd0aa3dc53
  title: Video-iTunes U-MP4
  type: Video
  uid: 588d536a8c695c149c37501ecd739bab
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_lec13_300k.mp4
  parent_uid: 9631a66a55cf940a72c3a1dd0aa3dc53
  title: Video-Internet Archive-MP4
  type: Video
  uid: 2eb4022a0166f36cefa74f915592bfb3
- id: 3Play-3PlayYouTubeid-MP4
  media_location: wPPf9S7IiAs
  parent_uid: 9631a66a55cf940a72c3a1dd0aa3dc53
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: b8ae677cfa96f19527a4e9797948a089
- id: wPPf9S7IiAs.srt
  parent_uid: 9631a66a55cf940a72c3a1dd0aa3dc53
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-13-locked-linkages/wPPf9S7IiAs.srt
  title: 3play caption file
  type: null
  uid: 5ce9856972ba56460f459e0357e5b5aa
- id: wPPf9S7IiAs.pdf
  parent_uid: 9631a66a55cf940a72c3a1dd0aa3dc53
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-13-locked-linkages/wPPf9S7IiAs.pdf
  title: 3play pdf file
  type: null
  uid: 3afb0feb7ce34f53a066239e0be4a001
- id: Caption-3Play YouTube id-SRT
  parent_uid: 9631a66a55cf940a72c3a1dd0aa3dc53
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 22c628aca9755cacbb15a47b52a7bb7f
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 9631a66a55cf940a72c3a1dd0aa3dc53
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 744c3883ee2f714023387e1e9bdd8073
inline_embed_id: 6864098lecture13:lockedlinkages1548482
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: lecture-13-locked-linkages
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-13-locked-linkages
template_type: Tabbed
title: 'Lecture 13: Locked Linkages'
transcript: '<p><span m=''36370''>PROFESSOR: All</span> <span m=''36470''>right,</span>
  <span m=''36770''>let''s</span> <span m=''37080''>get</span> <span m=''37190''>started.</span>
  <span m=''39200''>So</span> <span m=''39370''>today</span> <span m=''39740''>we''re</span>
  <span m=''40440''>continuing</span> <span m=''40940''>the</span> <span m=''41020''>theme</span>
  <span m=''41360''>of</span> <span m=''41700''>locked</span> <span m=''42000''>linkages.</span>
  <span m=''43120''>Last</span> <span m=''43340''>time</span> <span m=''43670''>we</span>
  <span m=''43800''>talked</span> <span m=''44070''>about</span> <span m=''44320''>the</span>
  <span m=''44410''>Carpenter''s</span> <span m=''44880''>Rule</span> <span m=''45110''>Theorem,</span>
  <span m=''45600''>which</span> <span m=''45970''>brought</span> <span m=''46240''>together</span>
  <span m=''46550''>all</span> <span m=''46820''>of</span> <span m=''46960''>the</span>
  <span m=''47080''>rigidity</span> <span m=''47540''>theory and</span> <span m=''47860''>tensegrity</span>
  <span m=''48420''>theory</span> <span m=''48670''>we</span> <span m=''48830''>had</span>
  <span m=''49050''>built,</span> <span m=''49390''>essentially,</span> <span m=''50620''>and</span>
  <span m=''51100''>showed</span> <span m=''51400''>that</span> <span m=''51650''>there</span>
  <span m=''51800''>were</span> <span m=''51940''>no</span> <span m=''52570''>locked</span>
  <span m=''54170''>2D</span> <span m=''55090''>chains,</span> <span m=''56390''>paths</span>
  <span m=''56950''>or</span> <span m=''57070''>cycles,</span> <span m=''57750''>as</span>
  <span m=''57980''>graphs.</span> </p><p><span m=''59040''>And</span> <span m=''59260''>in</span>
  <span m=''59340''>general</span> <span m=''61650''>you</span> <span m=''61860''>can</span>
  <span m=''62040''>think</span> <span m=''62890''>in</span> <span m=''63350''>2D,</span>
  <span m=''64660''>you</span> <span m=''64830''>can</span> <span m=''64980''>think</span>
  <span m=''65209''>in</span> <span m=''65349''>3D,</span> <span m=''67130''>and</span>
  <span m=''67370''>you</span> <span m=''67480''>can</span> <span m=''67630''>think</span>
  <span m=''67870''>in</span> <span m=''67960''>4D</span> <span m=''68400''>and</span>
  <span m=''68500''>higher.</span> <span m=''70210''>I drew</span> <span m=''70450''>this</span>
  <span m=''70760''>table</span> <span m=''71110''>way</span> <span m=''71650''>at</span>
  <span m=''71770''>the</span> <span m=''71840''>beginning</span> <span m=''72490''>of</span>
  <span m=''72530''>class.</span> <span m=''74560''>And</span> <span m=''74830''>you</span>
  <span m=''74940''>can</span> <span m=''75070''>think</span> <span m=''75210''>about</span>
  <span m=''75490''>chains,</span> <span m=''78340''>which</span> <span m=''78560''>are--</span>
  <span m=''81080''>these</span> <span m=''81280''>are</span> <span m=''81370''>so-called</span>
  <span m=''81780''>open</span> <span m=''82080''>chains,</span> <span m=''82750''>like</span>
  <span m=''82930''>robotic</span> <span m=''83310''>arms.</span> <span m=''84470''>Paths</span>
  <span m=''85140''>is</span> <span m=''85430''>a</span> <span m=''85490''>graph.</span>
  <span m=''86690''>And</span> <span m=''87230''>polygons</span> <span m=''89950''>are</span>
  <span m=''90120''>closed</span> <span m=''90500''>chains.</span> </p><p><span m=''92630''>And</span>
  <span m=''92930''>then</span> <span m=''93060''>another</span> <span m=''93350''>case</span>
  <span m=''93670''>it''s</span> <span m=''93810''>interesting</span> <span m=''94350''>to</span>
  <span m=''94500''>think</span> <span m=''94660''>about,</span> <span m=''94960''>and</span>
  <span m=''95210''>there''s</span> <span m=''95410''>been</span> <span m=''95530''>a</span>
  <span m=''95590''>lot</span> <span m=''95760''>of</span> <span m=''95820''>work</span>
  <span m=''96030''>on,</span> <span m=''96170''>are</span> <span m=''96270''>trees</span>
  <span m=''97330''>where</span> <span m=''97820''>you</span> <span m=''97970''>don''t</span>
  <span m=''98150''>have</span> <span m=''98320''>any</span> <span m=''98520''>cycles</span>
  <span m=''99520''>in</span> <span m=''99690''>your</span> <span m=''99830''>graph,</span>
  <span m=''100190''>but</span> <span m=''100320''>you</span> <span m=''100460''>could</span>
  <span m=''100580''>have</span> <span m=''101430''>branching</span> <span m=''101800''>points</span>
  <span m=''102150''>with</span> <span m=''102330''>degree</span> <span m=''102630''>more</span>
  <span m=''102870''>than</span> <span m=''103060''>2.</span> <span m=''104890''>You</span>
  <span m=''104980''>may</span> <span m=''105130''>recall</span> <span m=''106050''>Carpenter''s</span>
  <span m=''106460''>Rule</span> <span m=''106650''>Theorem</span> <span m=''107010''>worked</span>
  <span m=''107300''>whenever</span> <span m=''107670''>you</span> <span m=''107820''>had</span>
  <span m=''109140''>a</span> <span m=''109240''>graph</span> <span m=''109620''>of</span>
  <span m=''109720''>maximum</span> <span m=''110240''>degree</span> <span m=''110590''>2.</span>
  <span m=''111050''>So</span> <span m=''111250''>it</span> <span m=''111420''>allowed</span>
  <span m=''111710''>even</span> <span m=''111900''>multiple</span> <span m=''113170''>chains</span>
  <span m=''113940''>in</span> <span m=''114130''>one</span> <span m=''114680''>graph</span>
  <span m=''115430''>that</span> <span m=''115520''>could</span> <span m=''115630''>be</span>
  <span m=''115730''>disconnected.</span> <span m=''116980''>But</span> <span m=''117120''>it</span>
  <span m=''117160''>forbade</span> <span m=''117900''>any</span> <span m=''118130''>kind</span>
  <span m=''118360''>of</span> <span m=''118470''>tree</span> <span m=''118870''>branching</span>
  <span m=''119360''>stuff.</span> </p><p><span m=''122020''>So</span> <span m=''122310''>Carpenter''s</span>
  <span m=''122700''>Rule</span> <span m=''122880''>Theorem</span> <span m=''123270''>is</span>
  <span m=''123550''>that</span> <span m=''123680''>there''s</span> <span m=''123920''>no</span>
  <span m=''125080''>locked</span> <span m=''126390''>chains</span> <span m=''127490''>in</span>
  <span m=''127800''>2D.</span> <span m=''127990''>So</span> <span m=''128199''>we</span>
  <span m=''128720''>did</span> <span m=''128960''>that.</span> <span m=''131640''>But</span>
  <span m=''131890''>trees,</span> <span m=''132390''>there</span> <span m=''132610''>are</span>
  <span m=''132760''>locked</span> <span m=''133120''>trees</span> <span m=''133470''>in</span>
  <span m=''133610''>2D.</span> <span m=''136020''>3D</span> <span m=''136790''>there
  are</span> <span m=''137130''>locked</span> <span m=''138140''>chains.</span> <span
  m=''140140''>And</span> <span m=''140270''>these</span> <span m=''140450''>are</span>
  <span m=''140550''>two</span> <span m=''141080''>results</span> <span m=''141500''>that</span>
  <span m=''141600''>we</span> <span m=''141720''>will</span> <span m=''141860''>talk</span>
  <span m=''142120''>about</span> <span m=''143200''>in</span> <span m=''144380''>today''s</span>
  <span m=''144780''>lecture.</span> </p><p><span m=''146380''>And</span> <span m=''147050''>that</span>
  <span m=''147260''>implies</span> <span m=''148060''>that</span> <span m=''148160''>there
  are</span> <span m=''148350''>locked</span> <span m=''149120''>trees,</span> <span
  m=''149840''>sort</span> <span m=''150290''>of</span> <span m=''150830''>obvious.</span>
  <span m=''151190''>Trees</span> <span m=''151520''>are</span> <span m=''151620''>more</span>
  <span m=''151880''>general</span> <span m=''152380''>than</span> <span m=''153650''>open</span>
  <span m=''154160''>chains.</span> <span m=''154620''>And</span> <span m=''154700''>because</span>
  <span m=''154980''>there''s</span> <span m=''155130''>a</span> <span m=''155200''>locked</span>
  <span m=''155540''>open</span> <span m=''155840''>chain</span> <span m=''156110''>in</span>
  <span m=''156210''>3D,</span> <span m=''156700''>there''s</span> <span m=''157070''>also</span>
  <span m=''157340''>a locked</span> <span m=''157580''>tree.</span> </p><p><span
  m=''159260''>In</span> <span m=''159450''>4D,</span> <span m=''160000''>though,</span>
  <span m=''160320''>it</span> <span m=''160460''>switches.</span> <span m=''162450''>So</span>
  <span m=''162940''>none</span> <span m=''163210''>of</span> <span m=''163300''>these</span>
  <span m=''163940''>things</span> <span m=''164210''>are</span> <span m=''164310''>locked.</span>
  <span m=''164700''>Of</span> <span m=''164790''>course,</span> <span m=''165000''>there</span>
  <span m=''165140''>are</span> <span m=''165280''>locked</span> <span m=''165640''>graphs</span>
  <span m=''166190''>in</span> <span m=''166290''>general.</span> <span m=''168000''>But</span>
  <span m=''168040''>if</span> <span m=''168130''>you</span> <span m=''168230''>look</span>
  <span m=''168400''>at</span> <span m=''168490''>trees,</span> <span m=''168910''>or</span>
  <span m=''168990''>paths,</span> <span m=''169400''>or</span> <span m=''169490''>cycles,</span>
  <span m=''170650''>none</span> <span m=''170820''>of</span> <span m=''170920''>them</span>
  <span m=''171070''>can</span> <span m=''171220''>lock.</span> <span m=''171760''>We</span>
  <span m=''171950''>won''t</span> <span m=''172100''>have</span> <span m=''172280''>time</span>
  <span m=''172530''>to</span> <span m=''172960''>talk</span> <span m=''173150''>about</span>
  <span m=''173370''>that</span> <span m=''173560''>today,</span> <span m=''173810''>maybe</span>
  <span m=''174130''>another</span> <span m=''174380''>class.</span> </p><p><span
  m=''177430''>Essentially</span> <span m=''177770''>we''re</span> <span m=''177970''>always</span>
  <span m=''178250''>thinking</span> <span m=''178540''>about</span> <span m=''178860''>an</span>
  <span m=''178940''>intrinsically</span> <span m=''179650''>one</span> <span m=''179860''>dimensional</span>
  <span m=''180270''>structure.</span> <span m=''180890''>These</span> <span m=''181690''>edges,</span>
  <span m=''182210''>bars,</span> <span m=''182670''>are</span> <span m=''182780''>always</span>
  <span m=''183130''>one</span> <span m=''183330''>dimensional.</span> <span m=''184260''>In</span>
  <span m=''184470''>2D,</span> <span m=''186080''>where</span> <span m=''186540''>the</span>
  <span m=''186990''>space</span> <span m=''187430''>are</span> <span m=''187500''>living</span>
  <span m=''187830''>in,</span> <span m=''187980''>the</span> <span m=''188090''>ambient</span>
  <span m=''188450''>dimension</span> <span m=''188850''>is</span> <span m=''188950''>just</span>
  <span m=''189120''>one</span> <span m=''189430''>more</span> <span m=''189770''>than</span>
  <span m=''190210''>the</span> <span m=''190330''>dimension</span> <span m=''190720''>of</span>
  <span m=''190800''>your</span> <span m=''190930''>edges,</span> <span m=''191390''>it''s</span>
  <span m=''191620''>really</span> <span m=''191970''>interesting.</span> <span m=''192700''>And</span>
  <span m=''192890''>that''s</span> <span m=''193100''>what</span> <span m=''193200''>we</span>
  <span m=''194130''>saw</span> <span m=''194560''>for</span> <span m=''194720''>chains</span>
  <span m=''195070''>and</span> <span m=''195140''>what we''ll</span> <span m=''195380''>see</span>
  <span m=''195600''>for</span> <span m=''195730''>trees.</span> </p><p><span m=''197370''>In</span>
  <span m=''197600''>3D</span> <span m=''198940''>it</span> <span m=''199080''>gets</span>
  <span m=''199310''>tricky.</span> <span m=''199740''>This</span> <span m=''199920''>mismatch</span>
  <span m=''200400''>of</span> <span m=''200540''>two</span> <span m=''200920''>in</span>
  <span m=''201040''>dimension</span> <span m=''202480''>allows</span> <span m=''202790''>you</span>
  <span m=''202890''>to</span> <span m=''202970''>lock</span> <span m=''203230''>things,</span>
  <span m=''203500''>kind</span> <span m=''203770''>of</span> <span m=''203880''>like</span>
  <span m=''204210''>knots.</span> <span m=''205340''>And</span> <span m=''205730''>in</span>
  <span m=''205860''>4D</span> <span m=''206430''>there''s</span> <span m=''206620''>such--</span>
  <span m=''207520''>there''s</span> <span m=''207680''>so</span> <span m=''207840''>much</span>
  <span m=''208030''>freedom</span> <span m=''208480''>in</span> <span m=''208550''>the</span>
  <span m=''208640''>way</span> <span m=''208800''>you</span> <span m=''208940''>move,</span>
  <span m=''209350''>somehow,</span> <span m=''210270''>nothing</span> <span m=''210540''>can</span>
  <span m=''210680''>lock,</span> <span m=''211380''>in</span> <span m=''211500''>the</span>
  <span m=''211560''>same</span> <span m=''211770''>way that</span> <span m=''211990''>there</span>
  <span m=''212120''>are</span> <span m=''212150''>no</span> <span m=''212290''>knots</span>
  <span m=''212680''>in</span> <span m=''212870''>4D.</span> <span m=''215840''>Cool.</span>
  </p><p><span m=''217340''>So</span> <span m=''217530''>that''s</span> <span m=''217860''>the</span>
  <span m=''218390''>reminder</span> <span m=''218860''>summary</span> <span m=''219220''>about</span>
  <span m=''219520''>locked</span> <span m=''219790''>linkages,</span> <span m=''220310''>what</span>
  <span m=''220460''>they</span> <span m=''220600''>are,</span> <span m=''221410''>and</span>
  <span m=''221680''>what''s</span> <span m=''221890''>known</span> <span m=''222070''>about</span>
  <span m=''222370''>them.</span> <span m=''223920''>Now</span> <span m=''224080''>we''ve</span>
  <span m=''224230''>seen</span> <span m=''224550''>that</span> <span m=''224750''>chains</span>
  <span m=''225220''>aren''t</span> <span m=''225400''>locked.</span> <span m=''226690''>But</span>
  <span m=''226910''>before</span> <span m=''227200''>I</span> <span m=''227230''>get</span>
  <span m=''227400''>trees</span> <span m=''227960''>I</span> <span m=''228040''>want</span>
  <span m=''228230''>to</span> <span m=''228270''>talk</span> <span m=''228510''>about</span>
  <span m=''228890''>algorithms</span> <span m=''229360''>for</span> <span m=''229470''>actually</span>
  <span m=''229740''>doing</span> <span m=''229960''>this.</span> <span m=''230415''>This</span>
  <span m=''230870''>is,</span> <span m=''231020''>after</span> <span m=''231350''>all,</span>
  <span m=''231520''>geometric</span> <span m=''231970''>folding</span> <span m=''232360''>algorithms.</span>
  </p><p><span m=''233430''>We''ve</span> <span m=''233590''>seen</span> <span m=''233790''>a</span>
  <span m=''233850''>proof</span> <span m=''234340''>that</span> <span m=''234670''>they</span>
  <span m=''234800''>exist,</span> <span m=''236140''>that</span> <span m=''236170''>in</span>
  <span m=''236270''>fact</span> <span m=''236560''>if</span> <span m=''236650''>we</span>
  <span m=''236730''>had</span> <span m=''236940''>a</span> <span m=''237000''>chain,</span>
  <span m=''237310''>there''s</span> <span m=''237490''>an</span> <span m=''237560''>expansive</span>
  <span m=''238190''>motion</span> <span m=''238620''>increases</span> <span m=''239140''>all</span>
  <span m=''239290''>the</span> <span m=''239360''>distances</span> <span m=''240490''>and</span>
  <span m=''242450''>therefore</span> <span m=''242790''>doesn''t</span> <span m=''243060''>collide</span>
  <span m=''243380''>with</span> <span m=''243510''>itself,</span> <span m=''244300''>and</span>
  <span m=''244480''>eventually</span> <span m=''245110''>straightens</span> <span
  m=''245700''>all</span> <span m=''245960''>the</span> <span m=''246120''>outermost</span>
  <span m=''247790''>open</span> <span m=''248070''>chains</span> <span m=''248550''>and</span>
  <span m=''248820''>convexifies</span> <span m=''250030''>all</span> <span m=''250310''>the</span>
  <span m=''250660''>closed</span> <span m=''251020''>chains</span> <span m=''251440''>that</span>
  <span m=''251550''>are</span> <span m=''251670''>outermost,</span> <span m=''252260''>not</span>
  <span m=''252410''>containing</span> <span m=''252840''>anything.</span> </p><p><span
  m=''255780''>But</span> <span m=''255950''>how</span> <span m=''256120''>do</span>
  <span m=''256200''>we</span> <span m=''256329''>actually</span> <span m=''256670''>find</span>
  <span m=''257230''>such a</span> <span m=''257490''>motion?</span> <span m=''259570''>And</span>
  <span m=''259750''>this</span> <span m=''259930''>has</span> <span m=''260060''>been</span>
  <span m=''260310''>the</span> <span m=''260390''>subject</span> <span m=''260800''>of</span>
  <span m=''260899''>some</span> <span m=''261089''>study.</span> <span m=''261430''>There</span>
  <span m=''261570''>are</span> <span m=''261610''>three</span> <span m=''261959''>algorithms</span>
  <span m=''262470''>for</span> <span m=''262600''>doing</span> <span m=''262890''>it.</span>
  </p><p><span m=''268590''>So we''ll</span> <span m=''268960''>call</span> <span
  m=''269190''>this</span> <span m=''269440''>unfolding</span> <span m=''271370''>2D</span>
  <span m=''271900''>chains,</span> <span m=''275940''>unfolding</span> <span m=''276610''>being</span>
  <span m=''278260''>the</span> <span m=''278380''>goal</span> <span m=''278700''>of</span>
  <span m=''278840''>straightening</span> <span m=''279450''>or</span> <span m=''279550''>convexifying.</span>
  <span m=''282040''>And</span> <span m=''282310''>the</span> <span m=''282390''>first</span>
  <span m=''282690''>algorithm</span> <span m=''283890''>is</span> <span m=''284110''>just</span>
  <span m=''284360''>to</span> <span m=''284460''>mimic</span> <span m=''284870''>the</span>
  <span m=''284960''>proof</span> <span m=''285240''>that</span> <span m=''285350''>we</span>
  <span m=''285470''>saw.</span> </p><p><span m=''299700''>I</span> <span m=''299760''>call</span>
  <span m=''300010''>that</span> <span m=''300210''>proof</span> <span m=''300700''>CDR,</span>
  <span m=''301075''>because it''s</span> <span m=''301450''>Connelly-Demain-Rote.</span>
  <span m=''303060''>And</span> <span m=''304950''>if</span> <span m=''305170''>you</span>
  <span m=''305360''>think</span> <span m=''305610''>about</span> <span m=''305900''>what</span>
  <span m=''306100''>we</span> <span m=''306280''>proved,</span> <span m=''307100''>we</span>
  <span m=''307540''>just</span> <span m=''307780''>looked</span> <span m=''307970''>at</span>
  <span m=''308110''>the</span> <span m=''308410''>sort</span> <span m=''308530''>of</span>
  <span m=''308630''>infinitesimal</span> <span m=''309350''>case.</span> <span m=''309650''>We</span>
  <span m=''309740''>said,</span> <span m=''310030''>if</span> <span m=''310110''>we''re</span>
  <span m=''310250''>at</span> <span m=''310350''>some</span> <span m=''310500''>position</span>
  <span m=''311460''>then</span> <span m=''312070''>at</span> <span m=''312160''>least,</span>
  <span m=''312890''>for</span> <span m=''313210''>an</span> <span m=''313680''>infinitesimal</span>
  <span m=''314340''>amount</span> <span m=''314540''>of</span> <span m=''314620''>time,</span>
  <span m=''314980''>we</span> <span m=''315110''>can</span> <span m=''315240''>increase</span>
  <span m=''315680''>all</span> <span m=''315820''>the</span> <span m=''315900''>distances.</span>
  <span m=''316330''>All</span> <span m=''316460''>the</span> <span m=''316540''>struts</span>
  <span m=''316840''>can</span> <span m=''316990''>increase</span> <span m=''317320''>in</span>
  <span m=''317400''>length,</span> <span m=''318320''>and</span> <span m=''318590''>the</span>
  <span m=''318660''>bars</span> <span m=''318900''>stay</span> <span m=''319090''>the</span>
  <span m=''319190''>same</span> <span m=''319450''>length.</span> </p><p><span m=''321000''>That''s</span>
  <span m=''321290''>really</span> <span m=''321700''>only</span> <span m=''321910''>specifying</span>
  <span m=''322400''>the</span> <span m=''322460''>first</span> <span m=''322720''>derivative</span>
  <span m=''323550''>of a</span> <span m=''323700''>motion.</span> <span m=''324410''>So</span>
  <span m=''324460''>if</span> <span m=''324550''>you</span> <span m=''324630''>think</span>
  <span m=''324840''>of</span> <span m=''324940''>motion</span> <span m=''325430''>as</span>
  <span m=''325580''>being,</span> <span m=''325910''>I don''t</span> <span m=''326030''>know,</span>
  <span m=''327170''>some</span> <span m=''327410''>configuration</span> <span m=''327980''>C</span>
  <span m=''328400''>that''s</span> <span m=''328580''>a</span> <span m=''328640''>function</span>
  <span m=''328990''>of</span> <span m=''329100''>time,</span> <span m=''330430''>and</span>
  <span m=''330590''>you</span> <span m=''332040''>take</span> <span m=''332230''>the</span>
  <span m=''332320''>derivative</span> <span m=''332740''>with</span> <span m=''332900''>respect</span>
  <span m=''333230''>to</span> <span m=''333320''>t,</span> <span m=''334010''>then</span>
  <span m=''334170''>we</span> <span m=''334320''>computed</span> <span m=''334790''>what</span>
  <span m=''334980''>that</span> <span m=''335160''>derivative</span> <span m=''335620''>should</span>
  <span m=''335830''>be.</span> <span m=''336160''>That</span> <span m=''336350''>was</span>
  <span m=''336540''>the</span> <span m=''336630''>first</span> <span m=''336860''>order</span>
  <span m=''337090''>motion.</span> <span m=''337440''>I</span> <span m=''337500''>think</span>
  <span m=''337690''>we</span> <span m=''337780''>called</span> <span m=''338060''>it</span>
  <span m=''339720''>d,</span> <span m=''341055''>which is a</span> <span m=''341500''>little</span>
  <span m=''341690''>confusing.</span> <span m=''342270''>This</span> <span m=''342360''>is</span>
  <span m=''342580''>the d</span> <span m=''343050''>that we</span> <span m=''343200''>computed.</span>
  </p><p><span m=''345380''>And</span> <span m=''345580''>we</span> <span m=''345690''>said,</span>
  <span m=''346070''>well</span> <span m=''347090''>that''s</span> <span m=''347720''>an</span>
  <span m=''347870''>infinitesimal</span> <span m=''349220''>motion</span> <span m=''349710''>of</span>
  <span m=''350150''>some</span> <span m=''350530''>tensegrity.</span> <span m=''351340''>We</span>
  <span m=''351440''>can</span> <span m=''351600''>find</span> <span m=''351830''>it
  with</span> <span m=''351970''>linear</span> <span m=''352230''>programming.</span>
  <span m=''352780''>So</span> <span m=''352900''>at</span> <span m=''352970''>any</span>
  <span m=''353160''>moment</span> <span m=''353480''>in</span> <span m=''353590''>time</span>
  <span m=''354230''>we</span> <span m=''354440''>can</span> <span m=''354580''>figure</span>
  <span m=''354900''>out</span> <span m=''355050''>what</span> <span m=''357070''>our</span>
  <span m=''357150''>derivative</span> <span m=''357510''>should</span> <span m=''357690''>be.</span>
  <span m=''358210''>This</span> <span m=''358440''>is</span> <span m=''358570''>what''s</span>
  <span m=''358770''>called</span> <span m=''359000''>an</span> <span m=''359070''>ordinary</span>
  <span m=''359490''>differential</span> <span m=''359950''>equation,</span> <span
  m=''360720''>for</span> <span m=''360790''>those</span> <span m=''361010''>who have</span>
  <span m=''361120''>taking</span> <span m=''361490''>1803</span> <span m=''362260''>or</span>
  <span m=''362310''>whatever.</span> <span m=''363650''>You</span> <span m=''363900''>just</span>
  <span m=''364380''>solve</span> <span m=''364820''>it.</span> </p><p><span m=''365500''>And</span>
  <span m=''365690''>a</span> <span m=''365740''>very</span> <span m=''365960''>easy</span>
  <span m=''366190''>way</span> <span m=''366320''>to</span> <span m=''366410''>solve</span>
  <span m=''366720''>it</span> <span m=''366780''>is</span> <span m=''366890''>if</span>
  <span m=''367000''>you</span> <span m=''367090''>imagine</span> <span m=''367990''>configuration</span>
  <span m=''368640''>space,</span> <span m=''369370''>you</span> <span m=''369470''>start</span>
  <span m=''369780''>somewhere,</span> <span m=''370610''>you</span> <span m=''370750''>compute</span>
  <span m=''371170''>which</span> <span m=''371240''>way</span> <span m=''371380''>to</span>
  <span m=''371460''>go,</span> <span m=''372050''>you</span> <span m=''372170''>move</span>
  <span m=''372500''>a</span> <span m=''372590''>little</span> <span m=''372890''>bit</span>
  <span m=''373020''>in</span> <span m=''373120''>that</span> <span m=''373290''>direction.</span>
  <span m=''373640''>You''re</span> <span m=''373780''>only</span> <span m=''373970''>supposed</span>
  <span m=''374290''>to</span> <span m=''374370''>go</span> <span m=''374590''>for
  an</span> <span m=''374790''>infinitesimal</span> <span m=''375410''>amount.</span>
  <span m=''375710''>But</span> <span m=''375870''>it goes</span> <span m=''376020''>some</span>
  <span m=''376590''>positive</span> <span m=''377120''>epsilon.</span> </p><p><span
  m=''378070''>Then</span> <span m=''378260''>recompute</span> <span m=''378760''>your</span>
  <span m=''378910''>new</span> <span m=''379070''>direction,</span> <span m=''380020''>follow</span>
  <span m=''380340''>that,</span> <span m=''381050''>recompute</span> <span m=''381250''>your</span>
  <span m=''381570''>new</span> <span m=''381740''>direction,</span> <span m=''382170''>follow</span>
  <span m=''382490''>that</span> <span m=''382720''>for</span> <span m=''382800''>a</span>
  <span m=''382840''>little</span> <span m=''383030''>bit,</span> <span m=''383590''>and</span>
  <span m=''383750''>keep</span> <span m=''383920''>going.</span> <span m=''384500''>And</span>
  <span m=''384710''>you''re</span> <span m=''385150''>almost</span> <span m=''385620''>tracking</span>
  <span m=''386100''>the</span> <span m=''386220''>intended</span> <span m=''386670''>curve.</span>
  <span m=''386960''>It''s</span> <span m=''387100''>not</span> <span m=''387270''>quite</span>
  <span m=''387810''>perfect.</span> </p><p><span m=''388510''>But</span> <span m=''388730''>as</span>
  <span m=''389200''>your</span> <span m=''389470''>step</span> <span m=''389750''>size,</span>
  <span m=''390240''>this</span> <span m=''390410''>epsilon,</span> <span m=''391440''>goes</span>
  <span m=''391720''>to</span> <span m=''391820''>0</span> <span m=''392780''>you</span>
  <span m=''393370''>approximate</span> <span m=''394400''>the</span> <span m=''394530''>intended</span>
  <span m=''395240''>path.</span> <span m=''395970''>And</span> <span m=''396310''>that''s,</span>
  <span m=''396760''>I</span> <span m=''396820''>mean</span> <span m=''396980''>how</span>
  <span m=''397720''>close</span> <span m=''397970''>you</span> <span m=''398060''>approximate</span>
  <span m=''398520''>is</span> <span m=''398650''>computed</span> <span m=''399090''>in</span>
  <span m=''399180''>the</span> <span m=''399280''>textbook.</span> <span m=''399680''>You
  can</span> <span m=''399820''>see</span> <span m=''400650''>that</span> <span m=''400850''>for</span>
  <span m=''400970''>details.</span> <span m=''401380''>This is</span> <span m=''401620''>a</span>
  <span m=''401670''>method</span> <span m=''401960''>called</span> <span m=''402170''>forward</span>
  <span m=''402530''>Euler.</span> <span m=''403350''>It''s</span> <span m=''403690''>like</span>
  <span m=''403870''>the</span> <span m=''404170''>simplest</span> <span m=''404690''>way</span>
  <span m=''404880''>to</span> <span m=''404970''>solve</span> <span m=''406270''>an</span>
  <span m=''406380''>ordinary</span> <span m=''406650''>differential</span> <span
  m=''406940''>equation.</span> <span m=''407310''>There are</span> <span m=''407440''>much</span>
  <span m=''407650''>better</span> <span m=''407900''>ways.</span> <span m=''408850''>But</span>
  <span m=''408980''>it''s</span> <span m=''409110''>easiest</span> <span m=''409510''>to</span>
  <span m=''409580''>think</span> <span m=''409780''>about,</span> <span m=''410600''>and</span>
  <span m=''410860''>reason</span> <span m=''411130''>about.</span> </p><p><span m=''411810''>And</span>
  <span m=''412100''>so</span> <span m=''412180''>it</span> <span m=''412270''>gives</span>
  <span m=''412440''>you</span> <span m=''412580''>some</span> <span m=''413060''>approximate</span>
  <span m=''414510''>solution.</span> <span m=''417670''>Let</span> <span m=''417830''>me</span>
  <span m=''418100''>show it</span> <span m=''418350''>to you.</span> </p><p><span
  m=''423130''>I''m going to show you</span> <span m=''423560''>three</span> <span
  m=''423770''>methods.</span> <span m=''424750''>The</span> <span m=''424870''>top</span>
  <span m=''425150''>one</span> <span m=''425310''>is</span> <span m=''425420''>the
  one</span> <span m=''425600''>I''m</span> <span m=''425690''>talking</span> <span
  m=''426060''>about.</span> <span m=''426830''>So</span> <span m=''427200''>we''re</span>
  <span m=''427370''>starting</span> <span m=''427690''>with</span> <span m=''427800''>the</span>
  <span m=''427890''>same</span> <span m=''428160''>polygon</span> <span m=''428425''>on
  the</span> <span m=''428690''>left,</span> <span m=''429510''>simple</span> <span
  m=''429880''>little</span> <span m=''430220''>v</span> <span m=''430420''>shape.</span>
  <span m=''431760''>A</span> <span m=''431800''>second</span> <span m=''432150''>method</span>
  <span m=''432720''>is</span> <span m=''432820''>called</span> <span m=''433240''>pseudo-triangulation.</span>
  <span m=''433595''>We''ll</span> <span m=''433950''>talk</span> <span m=''434210''>about</span>
  <span m=''434410''>that</span> <span m=''434570''>next.</span> <span m=''434840''>The</span>
  <span m=''434890''>third</span> <span m=''435080''>method''s</span> <span m=''435400''>called</span>
  <span m=''435590''>energy.</span> <span m=''436310''>That</span> <span m=''436510''>one''s</span>
  <span m=''436720''>one</span> <span m=''436910''>you''ve</span> <span m=''437030''>seen.</span>
  </p><p><span m=''437970''>Let''s</span> <span m=''438160''>start</span> <span m=''438380''>with</span>
  <span m=''438470''>the</span> <span m=''438540''>first</span> <span m=''438850''>method,</span>
  <span m=''439810''>where</span> <span m=''442450''>we</span> <span m=''442580''>take</span>
  <span m=''442790''>some</span> <span m=''442940''>example</span> <span m=''443320''>like</span>
  <span m=''443480''>this</span> <span m=''443660''>teeth</span> <span m=''443890''>example,</span>
  <span m=''445080''>and</span> <span m=''445550''>we,</span> <span m=''447310''>at</span>
  <span m=''447450''>each</span> <span m=''447600''>step,</span> <span m=''447930''>compute</span>
  <span m=''448610''>what</span> <span m=''448850''>is</span> <span m=''449190''>the,</span>
  <span m=''450930''>in some</span> <span m=''451140''>sense,</span> <span m=''451350''>the</span>
  <span m=''451440''>biggest</span> <span m=''451960''>expanse of</span> <span m=''452340''>motion</span>
  <span m=''452750''>you</span> <span m=''452880''>could</span> <span m=''453010''>do.</span>
  <span m=''453440''>We</span> <span m=''453560''>go</span> <span m=''453690''>a</span>
  <span m=''453720''>little</span> <span m=''453980''>bit</span> <span m=''454130''>in</span>
  <span m=''454220''>that</span> <span m=''454380''>direction.</span> </p><p><span
  m=''454900''>So</span> <span m=''455230''>in</span> <span m=''455380''>these</span>
  <span m=''455550''>animations,</span> <span m=''456060''>the</span> <span m=''456170''>edge</span>
  <span m=''456350''>links</span> <span m=''456560''>are</span> <span m=''456640''>changing</span>
  <span m=''457120''>a</span> <span m=''457170''>little</span> <span m=''457420''>bit.</span>
  <span m=''458310''>And</span> <span m=''458510''>I''ve</span> <span m=''458590''>chosen</span>
  <span m=''458880''>the</span> <span m=''458960''>step</span> <span m=''459170''>size</span>
  <span m=''459440''>so</span> <span m=''459560''>the edge</span> <span m=''459810''>lengths</span>
  <span m=''460030''>change</span> <span m=''460290''>by,</span> <span m=''460420''>at</span>
  <span m=''460500''>most,</span> <span m=''460800''>10%,</span> <span m=''461480''>something</span>
  <span m=''461770''>like</span> <span m=''461930''>that.</span> <span m=''462840''>And</span>
  <span m=''462960''>here,</span> <span m=''463330''>this</span> <span m=''463540''>one,</span>
  <span m=''463870''>left</span> <span m=''464130''>side</span> <span m=''464300''>we''re</span>
  <span m=''464390''>zooming,</span> <span m=''464800''>right</span> <span m=''465010''>side</span>
  <span m=''465230''>we''re</span> <span m=''465320''>not</span> <span m=''465490''>zooming.</span>
  </p><p><span m=''467210''>These</span> <span m=''467390''>are</span> <span m=''467590''>somewhat</span>
  <span m=''467860''>older</span> <span m=''468160''>animations.</span> <span m=''468620''>So</span>
  <span m=''469030''>apologies</span> <span m=''469295''>for</span> <span m=''469560''>the</span>
  <span m=''469640''>frame</span> <span m=''469920''>rate.</span> <span m=''471580''>What</span>
  <span m=''471840''>else do I</span> <span m=''472130''>want</span> <span m=''472240''>to</span>
  <span m=''472300''>say?</span> </p><p><span m=''473010''>This</span> <span m=''473220''>is</span>
  <span m=''473350''>an</span> <span m=''473440''>example--</span> <span m=''474240''>well,</span>
  <span m=''474630''>notice</span> <span m=''474930''>it''s</span> <span m=''475100''>pulling</span>
  <span m=''475380''>the</span> <span m=''475500''>teeth</span> <span m=''475790''>off</span>
  <span m=''476180''>sort</span> <span m=''476380''>of</span> <span m=''476450''>from</span>
  <span m=''476660''>the</span> <span m=''476800''>end.</span> <span m=''477650''>If</span>
  <span m=''477820''>you</span> <span m=''477930''>want</span> <span m=''478080''>to</span>
  <span m=''478130''>be</span> <span m=''478210''>expensive</span> <span m=''478670''>you</span>
  <span m=''478800''>cannot</span> <span m=''479110''>pull</span> <span m=''479270''>the</span>
  <span m=''479340''>teeth</span> <span m=''479530''>apart.</span> <span m=''480260''>We''re</span>
  <span m=''480350''>going</span> <span m=''480430''>to</span> <span m=''480490''>see</span>
  <span m=''480680''>other</span> <span m=''480830''>ways</span> <span m=''481040''>to</span>
  <span m=''481140''>do</span> <span m=''481270''>the</span> <span m=''481390''>teeth</span>
  <span m=''481630''>in</span> <span m=''481730''>a</span> <span m=''481770''>moment.</span>
  </p><p><span m=''482710''>Here''s</span> <span m=''482970''>another</span> <span
  m=''483270''>example.</span> <span m=''483660''>Both</span> <span m=''483920''>of</span>
  <span m=''484010''>these</span> <span m=''484180''>examples</span> <span m=''484660''>at</span>
  <span m=''484790''>some</span> <span m=''485040''>point</span> <span m=''485730''>we''re</span>
  <span m=''485880''>conjectured</span> <span m=''486480''>to</span> <span m=''486630''>be</span>
  <span m=''487300''>locked.</span> <span m=''488430''>Before</span> <span m=''488920''>the</span>
  <span m=''489050''>Carpenter''s</span> <span m=''489510''>Rule</span> <span m=''489700''>Theorem</span>
  <span m=''489940''>was</span> <span m=''490080''>proved,</span> <span m=''490420''>a</span>
  <span m=''490460''>lot</span> <span m=''490660''>of</span> <span m=''490730''>people</span>
  <span m=''491320''>were</span> <span m=''491700''>trying</span> <span m=''491940''>to</span>
  <span m=''492000''>find</span> <span m=''492230''>counter</span> <span m=''492480''>examples.</span>
  <span m=''493920''>There</span> <span m=''494070''>aren''t</span> <span m=''494230''>any.</span>
  </p><p><span m=''498080''>So</span> <span m=''498280''>this</span> <span m=''498470''>is</span>
  <span m=''498590''>nice.</span> <span m=''498775''>It</span> <span m=''498960''>preserve</span>
  <span m=''499350''>five-fold</span> <span m=''499770''>rotational</span> <span m=''500230''>symmetry.</span>
  <span m=''502560''>And</span> <span m=''503060''>you</span> <span m=''503330''>can</span>
  <span m=''503520''>do</span> <span m=''503730''>it</span> <span m=''504080''>for</span>
  <span m=''504500''>multiple</span> <span m=''505800''>shapes</span> <span m=''506160''>as</span>
  <span m=''506260''>well.</span> <span m=''506570''>So</span> <span m=''506680''>here
  we</span> <span m=''506860''>have</span> <span m=''506970''>one</span> <span m=''507160''>polygon</span>
  <span m=''507620''>in</span> <span m=''507710''>the</span> <span m=''507800''>center,</span>
  <span m=''508290''>four</span> <span m=''508790''>arcs,</span> <span m=''509890''>four</span>
  <span m=''510500''>paths</span> <span m=''510950''>on</span> <span m=''511060''>the</span>
  <span m=''511180''>outside.</span> <span m=''513940''>In</span> <span m=''514070''>this</span>
  <span m=''514260''>case,</span> <span m=''514500''>the</span> <span m=''514580''>simulation</span>
  <span m=''515260''>stopped</span> <span m=''515870''>when</span> <span m=''516049''>one</span>
  <span m=''516179''>of</span> <span m=''516250''>them</span> <span m=''516380''>convexified</span>
  <span m=''517720''>because</span> <span m=''518159''>I</span> <span m=''518289''>didn''t</span>
  <span m=''518470''>implement</span> <span m=''518840''>all</span> <span m=''519020''>of
  the</span> <span m=''519140''>algorithm.</span> <span m=''521120''>At</span> <span
  m=''521280''>that</span> <span m=''521440''>point</span> <span m=''521610''>you</span>
  <span m=''521690''>just</span> <span m=''521919''>have</span> <span m=''522030''>to</span>
  <span m=''522130''>rigidify</span> <span m=''522610''>that</span> <span m=''522760''>polygon</span>
  <span m=''523230''>and</span> <span m=''523520''>expand</span> <span m=''523929''>the</span>
  <span m=''524010''>rest.</span> </p><p><span m=''526600''>So</span> <span m=''526780''>that</span>
  <span m=''526960''>gives</span> <span m=''527110''>you</span> <span m=''527200''>an</span>
  <span m=''527280''>idea</span> <span m=''528400''>sort of</span> <span m=''528580''>visually</span>
  <span m=''529140''>what</span> <span m=''529310''>this</span> <span m=''529490''>looks</span>
  <span m=''529690''>like.</span> <span m=''531200''>Qualitatively,</span> <span m=''532240''>we</span>
  <span m=''532380''>can</span> <span m=''532520''>say</span> <span m=''532940''>a</span>
  <span m=''532990''>bunch</span> <span m=''533260''>of</span> <span m=''533340''>cool</span>
  <span m=''533550''>things</span> <span m=''533780''>about</span> <span m=''534030''>this</span>
  <span m=''534180''>method.</span> <span m=''535070''>One</span> <span m=''535300''>is</span>
  <span m=''535420''>that''s</span> <span m=''536330''>it''s</span> <span m=''536530''>the</span>
  <span m=''536670''>only</span> <span m=''536880''>method</span> <span m=''538130''>that''s</span>
  <span m=''538340''>strictly</span> <span m=''538680''>expansive,</span> <span m=''540660''>strictly</span>
  <span m=''541130''>meaning</span> <span m=''542950''>not</span> <span m=''543190''>only</span>
  <span m=''543410''>do</span> <span m=''543620''>the</span> <span m=''544200''>struts</span>
  <span m=''544820''>not</span> <span m=''545660''>decrease</span> <span m=''546100''>in</span>
  <span m=''546170''>length,</span> <span m=''546610''>but</span> <span m=''546750''>they</span>
  <span m=''546870''>also</span> <span m=''547130''>don''t</span> <span m=''547370''>stay</span>
  <span m=''547540''>the</span> <span m=''547650''>same</span> <span m=''547990''>whenever</span>
  <span m=''548280''>that''s</span> <span m=''548510''>possible.</span> <span m=''549530''>They</span>
  <span m=''549650''>strictly</span> <span m=''550100''>increase.</span> </p><p><span
  m=''551150''>Now,</span> <span m=''551400''>there</span> <span m=''551520''>are</span>
  <span m=''551570''>some</span> <span m=''551740''>exceptions.</span> <span m=''552510''>If</span>
  <span m=''552680''>I</span> <span m=''552750''>have</span> <span m=''553820''>a</span>
  <span m=''553890''>bar,</span> <span m=''554990''>obviously,</span> <span m=''555630''>if</span>
  <span m=''555800''>I</span> <span m=''555890''>add</span> <span m=''556020''>a</span>
  <span m=''556080''>strut</span> <span m=''556420''>here</span> <span m=''556750''>it''s</span>
  <span m=''556940''>not</span> <span m=''557080''>going</span> <span m=''557160''>to</span>
  <span m=''557220''>strictly</span> <span m=''557580''>increase</span> <span m=''557900''>in</span>
  <span m=''558000''>length.</span> <span m=''558680''>Also,</span> <span m=''559650''>if</span>
  <span m=''559800''>I</span> <span m=''559850''>have</span> <span m=''560040''>a</span>
  <span m=''560090''>bunch</span> <span m=''560350''>of</span> <span m=''560420''>bars</span>
  <span m=''560720''>that</span> <span m=''560810''>are</span> <span m=''560900''>collinear</span>
  <span m=''562020''>and</span> <span m=''562220''>I</span> <span m=''562280''>add</span>
  <span m=''562460''>a</span> <span m=''562510''>strut</span> <span m=''562900''>from</span>
  <span m=''563100''>here</span> <span m=''563340''>to</span> <span m=''563390''>here,</span>
  <span m=''564690''>that''s</span> <span m=''564830''>not</span> <span m=''564970''>going</span>
  <span m=''565080''>to</span> <span m=''565120''>increase</span> <span m=''565510''>in</span>
  <span m=''565600''>length.</span> <span m=''565780''>It''s</span> <span m=''565930''>not</span>
  <span m=''566080''>possible.</span> </p><p><span m=''567090''>But</span> <span m=''567280''>all</span>
  <span m=''567580''>other</span> <span m=''567830''>struts</span> <span m=''568620''>will</span>
  <span m=''568770''>strictly</span> <span m=''569270''>increase</span> <span m=''569650''>in</span>
  <span m=''569730''>length.</span> <span m=''570400''>You</span> <span m=''570510''>can
  check.</span> <span m=''570900''>That''s</span> <span m=''571590''>what</span> <span
  m=''571790''>we</span> <span m=''571930''>proved</span> <span m=''572320''>here.</span>
  <span m=''575150''>So</span> <span m=''575330''>that''s</span> <span m=''575830''>nice.</span>
  </p><p><span m=''578190''>Another</span> <span m=''578530''>fun</span> <span m=''578840''>fact,</span>
  <span m=''581480''>I</span> <span m=''581590''>didn''t</span> <span m=''581780''>write</span>
  <span m=''581990''>it</span> <span m=''582110''>here,</span> <span m=''582860''>but</span>
  <span m=''583060''>it</span> <span m=''583230''>preserves</span> <span m=''583620''>symmetry</span>
  <span m=''587020''>if</span> <span m=''587070''>you</span> <span m=''587170''>do</span>
  <span m=''587340''>it</span> <span m=''587440''>right.</span> <span m=''591350''>You</span>
  <span m=''591560''>may</span> <span m=''591730''>notice</span> <span m=''592200''>in</span>
  <span m=''592290''>this</span> <span m=''592460''>example</span> <span m=''592920''>actually,</span>
  <span m=''593720''>it was</span> <span m=''593980''>originally</span> <span m=''594390''>four-fold</span>
  <span m=''594880''>rotationally</span> <span m=''595200''>symmetric.</span> <span
  m=''595610''>It</span> <span m=''595750''>does</span> <span m=''596210''>rotate</span>
  <span m=''596690''>a</span> <span m=''596760''>little</span> <span m=''597100''>bit.</span>
  <span m=''598360''>That''s</span> <span m=''598860''>from</span> <span m=''599310''>computational</span>
  <span m=''599910''>error.</span> <span m=''600220''>And</span> <span m=''600320''>you</span>
  <span m=''600440''>could</span> <span m=''600600''>correct</span> <span m=''600900''>for</span>
  <span m=''600980''>that.</span> <span m=''601660''>I</span> <span m=''601760''>didn''t</span>
  <span m=''601980''>correct</span> <span m=''602250''>for</span> <span m=''602500''>it.</span>
  </p><p><span m=''605050''>It</span> <span m=''605130''>should,</span> <span m=''605450''>in</span>
  <span m=''605630''>theory,</span> <span m=''606460''>preserve</span> <span m=''607000''>the</span>
  <span m=''607190''>four-fold</span> <span m=''609110''>symmetry</span> <span m=''609570''>there.</span>
  <span m=''611700''>Good.</span> <span m=''612660''>We</span> <span m=''612960''>can</span>
  <span m=''613090''>compute</span> <span m=''613510''>one</span> <span m=''613720''>step.</span>
  <span m=''614640''>So</span> <span m=''614770''>how</span> <span m=''614920''>fast</span>
  <span m=''615230''>can</span> <span m=''615330''>you</span> <span m=''615430''>compute</span>
  <span m=''615690''>this</span> <span m=''615870''>thing?</span> </p><p><span m=''618310''>We
  can</span> <span m=''618460''>compute</span> <span m=''618850''>one</span> <span
  m=''619020''>step</span> <span m=''619310''>in</span> <span m=''619410''>polynomial</span>
  <span m=''619910''>time.</span> <span m=''620250''>That''s</span> <span m=''620800''>finding</span>
  <span m=''621100''>an</span> <span m=''621160''>infinitesimal</span> <span m=''621730''>motion</span>
  <span m=''622260''>of</span> <span m=''622520''>a</span> <span m=''622630''>tensegrity.</span>
  <span m=''623580''>That''s</span> <span m=''623800''>linear</span> <span m=''624020''>programming.</span>
  </p><p><span m=''627970''>But</span> <span m=''629490''>how</span> <span m=''629750''>many</span>
  <span m=''630030''>steps</span> <span m=''630400''>does</span> <span m=''630570''>it</span>
  <span m=''630710''>make?</span> <span m=''631820''>We</span> <span m=''631970''>don''t</span>
  <span m=''632120''>really</span> <span m=''632460''>know.</span> <span m=''632850''>There</span>
  <span m=''633020''>is</span> <span m=''633120''>a bound</span> <span m=''633450''>in</span>
  <span m=''633540''>the</span> <span m=''633640''>textbook.</span> <span m=''635180''>It''s</span>
  <span m=''635590''>not</span> <span m=''635870''>very</span> <span m=''636630''>small.</span>
  </p><p><span m=''638390''>It''s</span> <span m=''638730''>also--</span> <span m=''641600''>with</span>
  <span m=''642070''>forward</span> <span m=''642360''>Euler</span> <span m=''642860''>you</span>
  <span m=''643010''>lose</span> <span m=''643200''>a</span> <span m=''643240''>bit</span>
  <span m=''643370''>of</span> <span m=''643460''>accuracy.</span> <span m=''644960''>Now</span>
  <span m=''644990''>you</span> <span m=''645170''>could</span> <span m=''645650''>correct</span>
  <span m=''646170''>for</span> <span m=''646320''>accuracy,</span> <span m=''647440''>force</span>
  <span m=''647750''>all</span> <span m=''647840''>the edge</span> <span m=''648050''>lengths</span>
  <span m=''648270''>to</span> <span m=''648340''>be</span> <span m=''648420''>the</span>
  <span m=''648500''>same,</span> <span m=''648850''>then</span> <span m=''648880''>you
  won''t</span> <span m=''649080''>preserve</span> <span m=''649400''>the</span> <span
  m=''649470''>symmetry.</span> <span m=''650080''>There''s a</span> <span m=''650350''>bit
  of</span> <span m=''650700''>trade</span> <span m=''650940''>off</span> <span m=''651070''>here.</span>
  <span m=''651720''>I</span> <span m=''651810''>don''t</span> <span m=''651910''>want</span>
  <span m=''652050''>to</span> <span m=''652140''>spend</span> <span m=''652400''>too</span>
  <span m=''652490''>much</span> <span m=''652670''>time</span> <span m=''652880''>on
  it.</span> </p><p><span m=''653030''>This is</span> <span m=''653210''>the</span>
  <span m=''653320''>first</span> <span m=''653600''>algorithm.</span> <span m=''655080''>Although</span>
  <span m=''655380''>it''s</span> <span m=''655630''>the</span> <span m=''655830''>only</span>
  <span m=''656060''>one</span> <span m=''656200''>that''s</span> <span m=''656280''>strictly</span>
  <span m=''656930''>expensive,</span> <span m=''658280''>to</span> <span m=''658410''>me</span>
  <span m=''658500''>it''s</span> <span m=''658630''>not</span> <span m=''658790''>the</span>
  <span m=''658890''>nicest.</span> <span m=''659550''>So</span> <span m=''659750''>I''m</span>
  <span m=''659870''>going</span> <span m=''659980''>to</span> <span m=''660070''>move</span>
  <span m=''660300''>on</span> <span m=''665830''>to the</span> <span m=''665950''>next</span>
  <span m=''666330''>method</span> <span m=''666860''>which</span> <span m=''667030''>is</span>
  <span m=''667620''>pointed</span> <span m=''668050''>pseudo-triangulations.</span>
  </p><p><span m=''673970''>This</span> <span m=''674200''>is</span> <span m=''674250''>a</span>
  <span m=''674290''>method</span> <span m=''674680''>by</span> <span m=''675100''>Ileana</span>
  <span m=''675450''>Streinu,</span> <span m=''676360''>basically</span> <span m=''676730''>at
  the</span> <span m=''676840''>same</span> <span m=''677100''>time</span> <span m=''677490''>as</span>
  <span m=''677900''>the</span> <span m=''678900''>original</span> <span m=''680350''>Carpenter''s</span>
  <span m=''680770''>Rule</span> <span m=''680990''>Theorem.</span> <span m=''682830''>And</span>
  <span m=''683260''>these</span> <span m=''683470''>are</span> <span m=''683520''>examples</span>
  <span m=''684000''>of</span> <span m=''684080''>what</span> <span m=''684220''>are</span>
  <span m=''684280''>called</span> <span m=''684960''>pointed</span> <span m=''685760''>pseudo-triangulations</span>
  <span m=''686970''>for</span> <span m=''687130''>a</span> <span m=''687180''>given</span>
  <span m=''687470''>set</span> <span m=''687670''>of</span> <span m=''687780''>points.</span>
  </p><p><span m=''688830''>So</span> <span m=''689440''>in</span> <span m=''689610''>general,</span>
  <span m=''690150''>a</span> <span m=''690200''>pseudo-triangle</span> <span m=''691980''>is</span>
  <span m=''692120''>a</span> <span m=''692180''>polygon</span> <span m=''694040''>that</span>
  <span m=''694150''>has</span> <span m=''694610''>three</span> <span m=''695560''>convex</span>
  <span m=''696440''>vertices.</span> <span m=''696980''>So a</span> <span m=''697060''>triangle</span>
  <span m=''697570''>has</span> <span m=''698300''>three</span> <span m=''698390''>convex</span>
  <span m=''698660''>vertices</span> <span m=''699130''>and</span> <span m=''699210''>that''s</span>
  <span m=''699430''>it.</span> <span m=''700020''>A</span> <span m=''700310''>pseudo-triangle,</span>
  <span m=''701020''>I</span> <span m=''701150''>allow</span> <span m=''701790''>a</span>
  <span m=''701870''>bunch</span> <span m=''702220''>of</span> <span m=''702850''>reflex</span>
  <span m=''703290''>vertices</span> <span m=''704670''>in</span> <span m=''704830''>between</span>
  <span m=''706830''>those</span> <span m=''707070''>guys.</span> <span m=''707260''>So</span>
  <span m=''707360''>this</span> <span m=''707510''>should</span> <span m=''707660''>be</span>
  <span m=''707760''>a</span> <span m=''707830''>polygon.</span> <span m=''708550''>I''ve</span>
  <span m=''708650''>drawn</span> <span m=''708860''>it</span> <span m=''708940''>curved.</span>
  </p><p><span m=''711200''>And</span> <span m=''711440''>if</span> <span m=''711530''>you</span>
  <span m=''711630''>check</span> <span m=''712130''>in</span> <span m=''712320''>this</span>
  <span m=''712960''>figure,</span> <span m=''713980''>all</span> <span m=''714300''>of</span>
  <span m=''714470''>the</span> <span m=''714570''>faces</span> <span m=''715430''>are</span>
  <span m=''715580''>pseudo-triangles.</span> <span m=''716460''>Most</span> <span
  m=''716750''>of</span> <span m=''716800''>them</span> <span m=''716990''>here are</span>
  <span m=''717270''>actually</span> <span m=''717530''>quadrilaterals.</span> <span
  m=''719180''>But</span> <span m=''719370''>in</span> <span m=''719490''>particular,</span>
  <span m=''719920''>that''s</span> <span m=''720250''>a</span> <span m=''720300''>pseudo-triangle.</span>
  <span m=''721090''>Sometimes</span> <span m=''721660''>there''s</span> <span m=''721810''>actual</span>
  <span m=''722180''>triangles.</span> <span m=''724610''>Here</span> <span m=''724830''>they''re</span>
  <span m=''724970''>all</span> <span m=''725120''>quads</span> <span m=''725520''>or</span>
  <span m=''725620''>triangles.</span> </p><p><span m=''727130''>And</span> <span
  m=''727460''>a</span> <span m=''727790''>pointed</span> <span m=''728120''>pseudo-triangulation</span>
  <span m=''730040''>has</span> <span m=''730310''>the</span> <span m=''730420''>property</span>
  <span m=''731720''>that</span> <span m=''732040''>at</span> <span m=''732400''>every</span>
  <span m=''732740''>vertex</span> <span m=''734630''>all</span> <span m=''734910''>of</span>
  <span m=''735020''>the</span> <span m=''735160''>edges</span> <span m=''735460''>incident</span>
  <span m=''735860''>to</span> <span m=''736000''>it</span> <span m=''736430''>lie</span>
  <span m=''736990''>in</span> <span m=''737120''>a</span> <span m=''737280''>half</span>
  <span m=''737630''>plane.</span> <span m=''739410''>They</span> <span m=''739520''>all</span>
  <span m=''739850''>lie</span> <span m=''740400''>on</span> <span m=''740530''>that</span>
  <span m=''740600''>side.</span> <span m=''741340''>In</span> <span m=''741430''>other</span>
  <span m=''741590''>words,</span> <span m=''741800''>there''s</span> <span m=''741990''>an</span>
  <span m=''742110''>angle</span> <span m=''742900''>that''s</span> <span m=''743150''>bigger</span>
  <span m=''743460''>than</span> <span m=''743610''>180</span> <span m=''744190''>degrees.</span>
  <span m=''746315''>So</span> <span m=''746800''>this</span> <span m=''747010''>was</span>
  <span m=''747160''>a</span> <span m=''747240''>pseudo-triangle,</span> <span m=''751310''>and</span>
  <span m=''751480''>this</span> <span m=''751640''>is</span> <span m=''751750''>pointed.</span>
  <span m=''754870''>And</span> <span m=''755280''>if</span> <span m=''755390''>you</span>
  <span m=''755490''>check</span> <span m=''755720''>this</span> <span m=''755880''>example,</span>
  <span m=''757420''>every</span> <span m=''757760''>vertex</span> <span m=''758330''>has</span>
  <span m=''758570''>an</span> <span m=''758660''>angle</span> <span m=''758930''>that''s</span>
  <span m=''759050''>bigger</span> <span m=''759310''>than</span> <span m=''759460''>180</span>
  <span m=''759980''>degrees.</span> </p><p><span m=''764510''>Obviously</span> <span
  m=''765020''>the</span> <span m=''765120''>ones</span> <span m=''765290''>on</span>
  <span m=''765340''>the</span> <span m=''765450''>outside</span> <span m=''765810''>have</span>
  <span m=''766080''>to.</span> <span m=''766850''>They''re</span> <span m=''767170''>always</span>
  <span m=''767370''>convex.</span> <span m=''769290''>And</span> <span m=''769760''>pointed</span>
  <span m=''770170''>pseudo-triangulations</span> <span m=''771240''>are--</span>
  <span m=''773820''>they''re</span> <span m=''774350''>not</span> <span m=''774580''>only</span>
  <span m=''774740''>supposed</span> <span m=''774970''>to</span> <span m=''775010''>have</span>
  <span m=''775120''>these</span> <span m=''775270''>two</span> <span m=''775400''>properties,</span>
  <span m=''775850''>but</span> <span m=''775950''>you''re</span> <span m=''776090''>also</span>
  <span m=''776290''>supposed</span> <span m=''776580''>to</span> <span m=''776630''>have</span>
  <span m=''776830''>as</span> <span m=''776940''>many</span> <span m=''777300''>edges</span>
  <span m=''777560''>as</span> <span m=''777680''>possible,</span> <span m=''778360''>subject</span>
  <span m=''778830''>to</span> <span m=''778900''>having</span> <span m=''779120''>these</span>
  <span m=''779280''>two</span> <span m=''779390''>properties.</span> <span m=''779970''>If</span>
  <span m=''780080''>you</span> <span m=''780160''>tried</span> <span m=''780530''>to</span>
  <span m=''780630''>add</span> <span m=''780980''>any</span> <span m=''781320''>edge</span>
  <span m=''782010''>to</span> <span m=''782140''>either</span> <span m=''782410''>of
  these</span> <span m=''782620''>examples,</span> <span m=''783900''>you</span> <span
  m=''784170''>would</span> <span m=''784950''>violate</span> <span m=''785750''>the</span>
  <span m=''785850''>pointed</span> <span m=''786230''>property.</span> </p><p><span
  m=''786980''>If</span> <span m=''787080''>I</span> <span m=''787160''>added</span>
  <span m=''787470''>this</span> <span m=''787680''>edge,</span> <span m=''788380''>then</span>
  <span m=''788875''>I''d</span> <span m=''789690''>destroy</span> <span m=''790170''>this</span>
  <span m=''790380''>180</span> <span m=''790850''>degree</span> <span m=''791090''>angle.</span>
  <span m=''791630''>Any</span> <span m=''791900''>edge</span> <span m=''792070''>you</span>
  <span m=''792170''>consider,</span> <span m=''792630''>either</span> <span m=''792880''>you</span>
  <span m=''793080''>get</span> <span m=''793240''>a</span> <span m=''793300''>crossing--</span>
  <span m=''793750''>which is</span> <span m=''794020''>not allowed--</span> <span
  m=''794990''>or</span> <span m=''797630''>one</span> <span m=''797850''>of</span>
  <span m=''797900''>the</span> <span m=''797960''>vertices</span> <span m=''798380''>loses
  a</span> <span m=''798870''>180</span> <span m=''799450''>degree</span> <span m=''800110''>angle.</span>
  </p><p><span m=''801250''>So</span> <span m=''801400''>this</span> <span m=''801600''>is</span>
  <span m=''801820''>actually</span> <span m=''802120''>a really</span> <span m=''802480''>powerful</span>
  <span m=''802900''>concept.</span> <span m=''803480''>And</span> <span m=''804170''>it</span>
  <span m=''804270''>was</span> <span m=''804390''>introduced</span> <span m=''804980''>by</span>
  <span m=''805100''>this</span> <span m=''805250''>paper</span> <span m=''805500''>by</span>
  <span m=''805620''>Streinu</span> <span m=''805920''>in</span> <span m=''806060''>2000.</span>
  <span m=''807470''>It</span> <span m=''807750''>has</span> <span m=''808070''>lots</span>
  <span m=''808380''>of</span> <span m=''808490''>theory</span> <span m=''808840''>built</span>
  <span m=''809110''>around</span> <span m=''809370''>it</span> <span m=''809460''>by</span>
  <span m=''809590''>now.</span> <span m=''810390''>I''m</span> <span m=''810470''>not</span>
  <span m=''810610''>going</span> <span m=''810710''>to</span> <span m=''810760''>talk</span>
  <span m=''810960''>about</span> <span m=''811190''>that</span> <span m=''811390''>theory.</span>
  <span m=''811830''>I</span> <span m=''811930''>want</span> <span m=''812030''>to</span>
  <span m=''812130''>talk</span> <span m=''812230''>about</span> <span m=''812320''>how</span>
  <span m=''812500''>it</span> <span m=''812560''>applies</span> <span m=''813030''>to</span>
  <span m=''813460''>Carpenter''s</span> <span m=''813870''>Rule</span> <span m=''814690''>problem.</span>
  </p><p><span m=''819550''>I</span> <span m=''819630''>guess</span> <span m=''819820''>the</span>
  <span m=''819890''>first</span> <span m=''820170''>thing</span> <span m=''820340''>to</span>
  <span m=''820470''>say</span> <span m=''820740''>is</span> <span m=''820920''>that</span>
  <span m=''821120''>if</span> <span m=''821320''>you</span> <span m=''821480''>have,</span>
  <span m=''825570''>say,</span> <span m=''825710''>a</span> <span m=''825770''>polygon--</span>
  <span m=''828300''>maybe</span> <span m=''828590''>I</span> <span m=''828640''>should</span>
  <span m=''828860''>do</span> <span m=''828970''>a</span> <span m=''829030''>real</span>
  <span m=''829280''>example,</span> <span m=''830070''>so I''ll</span> <span m=''830120''>make</span>
  <span m=''830360''>it</span> <span m=''830470''>not</span> <span m=''830680''>so</span>
  <span m=''830860''>giant.</span> <span m=''836230''>OK,</span> <span m=''836480''>you
  take</span> <span m=''836710''>a</span> <span m=''836770''>polygon.</span> <span
  m=''838330''>So</span> <span m=''838550''>far</span> <span m=''838780''>it''s</span>
  <span m=''838900''>pointed,</span> <span m=''839710''>right?</span> <span m=''839950''>Every</span>
  <span m=''840180''>vertex--</span> <span m=''841180''>one</span> <span m=''841370''>of</span>
  <span m=''841430''>the</span> <span m=''841530''>two</span> <span m=''841660''>sides</span>
  <span m=''841980''>has</span> <span m=''842990''>an</span> <span m=''843080''>angle</span>
  <span m=''843520''>bigger</span> <span m=''843740''>than</span> <span m=''843860''>180.</span>
  </p><p><span m=''845090''>So</span> <span m=''845250''>just</span> <span m=''845520''>add</span>
  <span m=''845870''>as</span> <span m=''845980''>many</span> <span m=''846280''>edges</span>
  <span m=''846590''>as</span> <span m=''846690''>you</span> <span m=''846870''>can</span>
  <span m=''847260''>while</span> <span m=''847430''>still</span> <span m=''847650''>being</span>
  <span m=''847850''>pointed.</span> <span m=''850485''>Do,</span> <span m=''850910''>do,</span>
  <span m=''851030''>do.</span> <span m=''852200''>This</span> <span m=''852460''>one,</span>
  <span m=''854710''>that</span> <span m=''854940''>looks</span> <span m=''855250''>OK.</span>
  </p><p><span m=''859480''>I</span> <span m=''859670''>think</span> <span m=''859920''>that''s</span>
  <span m=''860180''>it.</span> <span m=''860590''>I</span> <span m=''860620''>think</span>
  <span m=''860770''>this</span> <span m=''860940''>is</span> <span m=''861060''>a</span>
  <span m=''861130''>pseudo-triangulation.</span> <span m=''862710''>I''ve</span>
  <span m=''862880''>added</span> <span m=''863180''>as</span> <span m=''863290''>many</span>
  <span m=''863560''>edges as</span> <span m=''863810''>I</span> <span m=''863860''>can</span>
  <span m=''864120''>while</span> <span m=''864250''>still</span> <span m=''864440''>being</span>
  <span m=''864680''>point.</span> <span m=''864950''>It</span> <span m=''865060''>turns</span>
  <span m=''865280''>out</span> <span m=''865380''>if</span> <span m=''865460''>you</span>
  <span m=''865550''>start</span> <span m=''865810''>with</span> <span m=''865880''>something</span>
  <span m=''866190''>that''s</span> <span m=''866330''>pointed,</span> <span m=''867060''>you''ll</span>
  <span m=''867200''>be</span> <span m=''867400''>able</span> <span m=''867580''>to</span>
  <span m=''867650''>keep</span> <span m=''867870''>adding</span> <span m=''868120''>edges,</span>
  <span m=''868620''>keep</span> <span m=''868810''>it pointed.</span> <span m=''869270''>And</span>
  <span m=''869390''>in</span> <span m=''869470''>the</span> <span m=''869610''>end</span>
  <span m=''869920''>all of</span> <span m=''870250''>the</span> <span m=''870340''>faces</span>
  <span m=''870730''>will</span> <span m=''870930''>be</span> <span m=''871070''>pseudo-triangles.</span>
  <span m=''872930''>So</span> <span m=''873110''>mission</span> <span m=''873400''>accomplished.</span>
  </p><p><span m=''874660''>This</span> <span m=''874730''>is</span> <span m=''874840''>a
  pointed</span> <span m=''875200''>pseudo-triangulation</span> <span m=''875930''>that</span>
  <span m=''876080''>contains,</span> <span m=''877240''>as</span> <span m=''877480''>a</span>
  <span m=''877540''>subgraph,</span> <span m=''879100''>my</span> <span m=''879390''>original</span>
  <span m=''879870''>polygon.</span> <span m=''883190''>So</span> <span m=''884300''>these</span>
  <span m=''884520''>are</span> <span m=''884560''>the</span> <span m=''884690''>edge</span>
  <span m=''884890''>lengths</span> <span m=''885130''>I</span> <span m=''885180''>want</span>
  <span m=''885510''>to</span> <span m=''885600''>preserve.</span> <span m=''886120''>Those</span>
  <span m=''886320''>should</span> <span m=''886490''>stay</span> <span m=''886680''>rigid.</span>
  <span m=''887720''>I''m</span> <span m=''887870''>going</span> <span m=''887980''>to</span>
  <span m=''888040''>be</span> <span m=''888170''>kind</span> <span m=''888400''>of</span>
  <span m=''888480''>crazy</span> <span m=''889380''>and</span> <span m=''889590''>also</span>
  <span m=''889970''>preserve</span> <span m=''890340''>the</span> <span m=''890430''>lengths</span>
  <span m=''890800''>of</span> <span m=''890910''>all</span> <span m=''891080''>of</span>
  <span m=''891150''>these</span> <span m=''891380''>edges.</span> </p><p><span m=''893070''>Now</span>
  <span m=''893210''>if</span> <span m=''893290''>you</span> <span m=''893390''>did</span>
  <span m=''893560''>that,</span> <span m=''893840''>this</span> <span m=''894000''>thing</span>
  <span m=''894130''>would</span> <span m=''894270''>be</span> <span m=''894990''>rigid,</span>
  <span m=''895910''>which</span> <span m=''896010''>is</span> <span m=''896110''>not</span>
  <span m=''896360''>so</span> <span m=''896480''>exciting.</span> <span m=''897290''>All</span>
  <span m=''897520''>you</span> <span m=''897610''>need</span> <span m=''897770''>to</span>
  <span m=''897870''>do</span> <span m=''898010''>to</span> <span m=''898080''>fix</span>
  <span m=''898330''>that</span> <span m=''898810''>is</span> <span m=''899020''>remove</span>
  <span m=''899380''>one</span> <span m=''899980''>of</span> <span m=''900210''>these</span>
  <span m=''900960''>added</span> <span m=''901300''>edges</span> <span m=''902340''>that''s</span>
  <span m=''902530''>on</span> <span m=''902670''>the</span> <span m=''902750''>convex</span>
  <span m=''903180''>hull</span> <span m=''903520''>on</span> <span m=''903640''>the</span>
  <span m=''903760''>outer</span> <span m=''903980''>boundary</span> <span m=''904420''>here.</span>
  <span m=''905530''>Then</span> <span m=''905760''>it</span> <span m=''905900''>will</span>
  <span m=''906040''>have</span> <span m=''906300''>one</span> <span m=''906530''>degree</span>
  <span m=''906790''>of</span> <span m=''906860''>freedom.</span> </p><p><span m=''908500''>So</span>
  <span m=''908560''>there will be</span> <span m=''908690''>two</span> <span m=''909050''>ways</span>
  <span m=''909260''>to</span> <span m=''909370''>move</span> <span m=''909530''>it.</span>
  <span m=''909610''>One</span> <span m=''909790''>is</span> <span m=''909880''>to</span>
  <span m=''909960''>expand</span> <span m=''910320''>this</span> <span m=''910700''>distance,</span>
  <span m=''910950''>the other is</span> <span m=''911230''>to</span> <span m=''911330''>contract</span>
  <span m=''911665''>it.</span> <span m=''912690''>And</span> <span m=''913050''>the</span>
  <span m=''913130''>one</span> <span m=''913270''>that</span> <span m=''913380''>expands</span>
  <span m=''913790''>that</span> <span m=''913950''>distance</span> <span m=''915250''>will</span>
  <span m=''915460''>expand</span> <span m=''915820''>all</span> <span m=''916060''>distances.</span>
  <span m=''917770''>So</span> <span m=''917890''>if</span> <span m=''917970''>you</span>
  <span m=''918080''>look</span> <span m=''918240''>at</span> <span m=''918320''>some</span>
  <span m=''918480''>other</span> <span m=''918670''>pair,</span> <span m=''918940''>like</span>
  <span m=''919270''>this</span> <span m=''919500''>guy,</span> <span m=''922730''>every</span>
  <span m=''923070''>other</span> <span m=''923600''>pair</span> <span m=''923830''>of</span>
  <span m=''923880''>distances</span> <span m=''924340''>will</span> <span m=''924600''>expand</span>
  <span m=''924990''>or</span> <span m=''925120''>stay</span> <span m=''925360''>the</span>
  <span m=''925450''>same.</span> </p><p><span m=''927790''>So</span> <span m=''927870''>this</span>
  <span m=''929870''>thing</span> <span m=''930070''>is</span> <span m=''930200''>expansive.</span>
  <span m=''933930''>But</span> <span m=''934050''>not</span> <span m=''934240''>strictly</span>
  <span m=''934580''>expensive,</span> <span m=''935090''>because</span> <span m=''935520''>we''re</span>
  <span m=''935670''>preserving</span> <span m=''936780''>these</span> <span m=''937000''>lengths.</span>
  <span m=''937250''>These</span> <span m=''937420''>ones</span> <span m=''937610''>will</span>
  <span m=''937690''>stay</span> <span m=''937880''>the</span> <span m=''937940''>same.</span>
  <span m=''939720''>So</span> <span m=''939890''>let</span> <span m=''940020''>me</span>
  <span m=''940130''>show</span> <span m=''940380''>you</span> <span m=''941880''>some</span>
  <span m=''942120''>of</span> <span m=''942170''>the</span> <span m=''942270''>things</span>
  <span m=''942530''>that</span> <span m=''942650''>can</span> <span m=''942780''>happen.</span>
  </p><p><span m=''943990''>So</span> <span m=''944970''>this</span> <span m=''945240''>is</span>
  <span m=''945360''>sort</span> <span m=''945580''>of</span> <span m=''945660''>at</span>
  <span m=''945840''>the</span> <span m=''945910''>heart</span> <span m=''946160''>of</span>
  <span m=''946230''>the</span> <span m=''946360''>algorithm.</span> <span m=''946920''>I''m</span>
  <span m=''947230''>not</span> <span m=''947400''>going</span> <span m=''947490''>to</span>
  <span m=''947550''>go</span> <span m=''947690''>into</span> <span m=''947830''>all</span>
  <span m=''947940''>the</span> <span m=''948030''>details.</span> <span m=''948450''>This</span>
  <span m=''948590''>can</span> <span m=''948720''>happen</span> <span m=''949010''>like</span>
  <span m=''949210''>n</span> <span m=''949430''>cubed</span> <span m=''949740''>times,</span>
  <span m=''950540''>where</span> <span m=''951790''>you</span> <span m=''951910''>say,</span>
  <span m=''952230''>OK</span> <span m=''952480''>I''ve</span> <span m=''952850''>added</span>
  <span m=''953170''>in</span> <span m=''953290''>all</span> <span m=''953410''>these</span>
  <span m=''953580''>edges.</span> <span m=''953900''>Here''s</span> <span m=''954090''>a</span>
  <span m=''954140''>nice</span> <span m=''954360''>pseudo-triangle</span> <span m=''955060''>here.</span>
  <span m=''955320''>It happens</span> <span m=''955610''>to</span> <span m=''955670''>be</span>
  <span m=''955770''>a</span> <span m=''955810''>triangle</span> <span m=''956260''>with</span>
  <span m=''956340''>some</span> <span m=''956480''>stuff</span> <span m=''956780''>on</span>
  <span m=''956830''>the</span> <span m=''956910''>bottom,</span> <span m=''957220''>stuff</span>
  <span m=''957470''>on</span> <span m=''957530''>the</span> <span m=''957630''>top.</span>
  </p><p><span m=''958230''>As</span> <span m=''958500''>I</span> <span m=''958580''>flex</span>
  <span m=''959000''>this</span> <span m=''959280''>to</span> <span m=''959500''>expand</span>
  <span m=''959970''>the</span> <span m=''960050''>distances</span> <span m=''960325''>this</span>
  <span m=''960600''>is</span> <span m=''960750''>going</span> <span m=''960870''>to</span>
  <span m=''960920''>move</span> <span m=''961150''>like</span> <span m=''961360''>that.</span>
  <span m=''961980''>At</span> <span m=''962170''>some</span> <span m=''962370''>point,</span>
  <span m=''962620''>those</span> <span m=''962810''>three</span> <span m=''962960''>points</span>
  <span m=''963240''>will</span> <span m=''963330''>become</span> <span m=''963650''>collinear,</span>
  <span m=''964600''>got</span> <span m=''964740''>to</span> <span m=''964820''>deal</span>
  <span m=''965020''>with</span> <span m=''965160''>that.</span> <span m=''966720''>And</span>
  <span m=''966880''>the</span> <span m=''966970''>way</span> <span m=''967120''>you</span>
  <span m=''967240''>deal</span> <span m=''967500''>with</span> <span m=''967650''>it</span>
  <span m=''967760''>is</span> <span m=''968310''>as</span> <span m=''968680''>you</span>
  <span m=''968810''>continue</span> <span m=''969330''>moving,</span> <span m=''970230''>it''s</span>
  <span m=''970410''>no</span> <span m=''970680''>longer</span> <span m=''970920''>the</span>
  <span m=''971040''>case</span> <span m=''971350''>that</span> <span m=''971450''>those</span>
  <span m=''971710''>two</span> <span m=''971890''>blue</span> <span m=''972230''>edges</span>
  <span m=''973480''>are</span> <span m=''973750''>the</span> <span m=''974250''>edges</span>
  <span m=''974570''>in the</span> <span m=''974710''>pseudo-triangulation.</span>
  <span m=''975530''>Now</span> <span m=''975850''>it''s</span> <span m=''976050''>this</span>
  <span m=''976210''>one</span> <span m=''976490''>red</span> <span m=''976730''>edge.</span>
  </p><p><span m=''977630''>This</span> <span m=''977790''>is</span> <span m=''977880''>called</span>
  <span m=''978080''>a</span> <span m=''978130''>flip.</span> <span m=''978490''>And</span>
  <span m=''978570''>you</span> <span m=''978670''>see,</span> <span m=''979250''>we</span>
  <span m=''979360''>used</span> <span m=''979520''>to</span> <span m=''979580''>have</span>
  <span m=''979740''>a</span> <span m=''979830''>quadrilateral</span> <span m=''980165''>up</span>
  <span m=''980500''>here an a</span> <span m=''980830''>triangle</span> <span m=''981290''>down</span>
  <span m=''981500''>here.</span> <span m=''982180''>Now</span> <span m=''982370''>we</span>
  <span m=''982440''>have</span> <span m=''982530''>a</span> <span m=''982590''>triangle</span>
  <span m=''982980''>up here</span> <span m=''983290''>and</span> <span m=''983360''>a</span>
  <span m=''983420''>quadrilateral</span> <span m=''984450''>over</span> <span m=''984700''>here.</span>
  <span m=''986030''>That''s</span> <span m=''986250''>pretty</span> <span m=''986560''>intuitive.</span>
  <span m=''987800''>You</span> <span m=''987920''>preserve</span> <span m=''988330''>that</span>
  <span m=''988410''>it''s a</span> <span m=''988660''>pseudo-triangulation</span>
  <span m=''989530''>as</span> <span m=''989700''>you</span> <span m=''989880''>move</span>
  <span m=''990160''>this.</span> </p><p><span m=''992610''>If</span> <span m=''992970''>you</span>
  <span m=''993080''>tried</span> <span m=''993350''>to</span> <span m=''993410''>go</span>
  <span m=''993570''>too</span> <span m=''993780''>far</span> <span m=''994060''>here</span>
  <span m=''995520''>you</span> <span m=''995660''>would</span> <span m=''995770''>actually</span>
  <span m=''996000''>get</span> <span m=''996110''>a</span> <span m=''996180''>convex</span>
  <span m=''997210''>quadrilateral.</span> <span m=''998130''>If</span> <span m=''998260''>this</span>
  <span m=''999140''>kept</span> <span m=''999440''>going</span> <span m=''1000510''>then</span>
  <span m=''1000660''>this</span> <span m=''1000820''>would</span> <span m=''1000920''>be</span>
  <span m=''1001040''>a</span> <span m=''1001090''>convex</span> <span m=''1001450''>quadrilateral.</span>
  <span m=''1001980''>That''s</span> <span m=''1002210''>not</span> <span m=''1002320''>a</span>
  <span m=''1002430''>pseudo-triangulation,</span> <span m=''1003130''>that''s</span>
  <span m=''1003310''>bad.</span> </p><p><span m=''1004420''>But</span> <span m=''1004600''>you</span>
  <span m=''1004690''>can</span> <span m=''1004860''>always</span> <span m=''1005060''>do</span>
  <span m=''1005170''>these</span> <span m=''1005340''>flips</span> <span m=''1005640''>to</span>
  <span m=''1005730''>fix</span> <span m=''1006030''>it</span> <span m=''1006150''>as</span>
  <span m=''1006320''>you</span> <span m=''1006420''>go</span> <span m=''1006560''>along.</span>
  <span m=''1006850''>And it</span> <span m=''1006980''>turns</span> <span m=''1007190''>out</span>
  <span m=''1007300''>this</span> <span m=''1007430''>will</span> <span m=''1007520''>only</span>
  <span m=''1007710''>happen</span> <span m=''1007980''>a</span> <span m=''1008030''>polynomial</span>
  <span m=''1008600''>number</span> <span m=''1008820''>of</span> <span m=''1008900''>times.</span>
  </p><p><span m=''1009520''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''1011830''>PROFESSOR:
  Like</span> <span m=''1012070''>shown,</span> <span m=''1012510''>is</span> <span
  m=''1012910''>how I</span> <span m=''1013160''>flipped</span> <span m=''1013480''>it.</span>
  </p><p><span m=''1014051''>AUDIENCE: Is it</span> <span m=''1014522''>[INAUDIBLE]</span>
  <span m=''1014993''>to a</span> <span m=''1015464''>red?</span> </p><p><span m=''1016410''>PROFESSOR:
  Yeah,</span> <span m=''1016870''>the</span> <span m=''1017030''>red</span> <span
  m=''1018110''>edge</span> <span m=''1018750''>now</span> <span m=''1019100''>goes</span>
  <span m=''1020330''>from</span> <span m=''1020560''>here</span> <span m=''1020800''>to</span>
  <span m=''1020880''>there.</span> <span m=''1022310''>Whereas</span> <span m=''1022490''>before</span>
  <span m=''1022870''>there</span> <span m=''1023010''>were</span> <span m=''1023110''>two</span>
  <span m=''1023290''>segments</span> <span m=''1024190''>that</span> <span m=''1024280''>went</span>
  <span m=''1024490''>from</span> <span m=''1024630''>here</span> <span m=''1024819''>to</span>
  <span m=''1024900''>there,</span> <span m=''1025270''>now</span> <span m=''1025420''>I''m</span>
  <span m=''1025520''>going</span> <span m=''1025640''>to</span> <span m=''1025700''>go</span>
  <span m=''1025859''>straight</span> <span m=''1026240''>from</span> <span m=''1026390''>there
  to there.</span> <span m=''1028060''>That''s</span> <span m=''1028319''>the</span>
  <span m=''1028400''>difference.</span> </p><p><span m=''1031230''>This</span> <span
  m=''1031329''>is</span> <span m=''1031490''>the</span> <span m=''1031550''>general</span>
  <span m=''1031859''>picture,</span> <span m=''1032540''>you</span> <span m=''1032660''>have</span>
  <span m=''1032839''>to</span> <span m=''1032950''>believe</span> <span m=''1033240''>me,</span>
  <span m=''1034480''>because</span> <span m=''1034740''>I</span> <span m=''1034810''>want</span>
  <span m=''1034990''>to</span> <span m=''1035260''>talk</span> <span m=''1035500''>about</span>
  <span m=''1035670''>other</span> <span m=''1035839''>things.</span> <span m=''1037310''>And,</span>
  <span m=''1038079''>cool.</span> </p><p><span m=''1038619''>So</span> <span m=''1038760''>here''s</span>
  <span m=''1039000''>an</span> <span m=''1039210''>example</span> <span m=''1039660''>of
  it</span> <span m=''1039780''>actually</span> <span m=''1040210''>running.</span>
  <span m=''1041890''>So we</span> <span m=''1042020''>have</span> <span m=''1042200''>some</span>
  <span m=''1042359''>polygon</span> <span m=''1043030''>in</span> <span m=''1043210''>the</span>
  <span m=''1043310''>top</span> <span m=''1043609''>left.</span> <span m=''1045510''>We''ve</span>
  <span m=''1045849''>deleted</span> <span m=''1046430''>the</span> <span m=''1046619''>edge</span>
  <span m=''1047050''>that''s</span> <span m=''1047490''>cyan.</span> <span m=''1048750''>So</span>
  <span m=''1048870''>that</span> <span m=''1049030''>one''s</span> <span m=''1049190''>going</span>
  <span m=''1049320''>to</span> <span m=''1049370''>expand.</span> <span m=''1051930''>And</span>
  <span m=''1052340''>we</span> <span m=''1052680''>move</span> <span m=''1053120''>a</span>
  <span m=''1053180''>little</span> <span m=''1053440''>bit.</span> <span m=''1054940''>This</span>
  <span m=''1055120''>is</span> <span m=''1055240''>moving</span> <span m=''1055510''>a</span>
  <span m=''1055560''>little</span> <span m=''1055810''>bit.</span> <span m=''1056810''>This</span>
  <span m=''1057070''>is</span> <span m=''1057160''>moving</span> <span m=''1057430''>a</span>
  <span m=''1057480''>little</span> <span m=''1057690''>bit</span> <span m=''1057870''>more.</span>
  </p><p><span m=''1058770''>At</span> <span m=''1058950''>this</span> <span m=''1059160''>point,</span>
  <span m=''1059490''>these</span> <span m=''1059810''>three</span> <span m=''1060030''>points</span>
  <span m=''1060480''>are</span> <span m=''1060680''>collinear.</span> <span m=''1061240''>Actually,</span>
  <span m=''1061510''>the</span> <span m=''1061600''>way</span> <span m=''1061690''>it''s</span>
  <span m=''1061830''>drawn</span> <span m=''1062040''>it</span> <span m=''1062090''>looks</span>
  <span m=''1062260''>like</span> <span m=''1062480''>a</span> <span m=''1062540''>little</span>
  <span m=''1062700''>bit</span> <span m=''1062910''>too</span> <span m=''1063080''>far.</span>
  <span m=''1064010''>But</span> <span m=''1064140''>they</span> <span m=''1064220''>should</span>
  <span m=''1064400''>be</span> <span m=''1064520''>collinear.</span> <span m=''1065640''>That</span>
  <span m=''1065800''>would</span> <span m=''1065890''>be</span> <span m=''1066020''>a</span>
  <span m=''1066050''>violation,</span> <span m=''1066590''>because</span> <span m=''1066770''>this</span>
  <span m=''1066950''>would</span> <span m=''1067080''>be--</span> <span m=''1067490''>if</span>
  <span m=''1067640''>we</span> <span m=''1067730''>go</span> <span m=''1067890''>any</span>
  <span m=''1068050''>farther--</span> <span m=''1068420''>that would</span> <span
  m=''1068600''>be a</span> <span m=''1068750''>violation</span> <span m=''1069210''>because</span>
  <span m=''1069370''>this</span> <span m=''1069510''>would</span> <span m=''1069550''>be
  a</span> <span m=''1069710''>convex</span> <span m=''1070100''>quadrilateral.</span>
  <span m=''1071180''>So</span> <span m=''1071370''>we</span> <span m=''1071460''>do</span>
  <span m=''1071590''>a</span> <span m=''1071630''>flip</span> <span m=''1071980''>here,</span>
  <span m=''1072990''>and</span> <span m=''1073300''>we</span> <span m=''1073400''>end</span>
  <span m=''1073520''>up</span> <span m=''1073630''>with</span> <span m=''1073730''>that</span>
  <span m=''1073940''>edge</span> <span m=''1074180''>instead.</span> </p><p><span
  m=''1075520''>So</span> <span m=''1075660''>now</span> <span m=''1075790''>everything''s</span>
  <span m=''1076140''>a</span> <span m=''1076190''>pseudo-triangle,</span> <span m=''1076940''>everything''s</span>
  <span m=''1077320''>pointed,</span> <span m=''1078380''>everything''s</span> <span
  m=''1078550''>happy.</span> <span m=''1079700''>You</span> <span m=''1079990''>keep</span>
  <span m=''1080200''>going,</span> <span m=''1080810''>then</span> <span m=''1081200''>these</span>
  <span m=''1081510''>three</span> <span m=''1081690''>points</span> <span m=''1082040''>become</span>
  <span m=''1082320''>collinear.</span> <span m=''1082970''>So</span> <span m=''1083090''>you</span>
  <span m=''1083200''>end up</span> <span m=''1083380''>getting</span> <span m=''1083640''>that</span>
  <span m=''1083890''>edge.</span> <span m=''1084960''>And</span> <span m=''1085330''>you</span>
  <span m=''1085430''>keep</span> <span m=''1085660''>going.</span> </p><p><span m=''1086800''>And</span>
  <span m=''1087050''>all</span> <span m=''1087410''>throughout</span> <span m=''1087720''>this</span>
  <span m=''1087890''>motion</span> <span m=''1089950''>all</span> <span m=''1090140''>pairwise</span>
  <span m=''1090510''>distances</span> <span m=''1091040''>are</span> <span m=''1091140''>not</span>
  <span m=''1091510''>decreasing.</span> <span m=''1092250''>Everything''s</span>
  <span m=''1092660''>expanding</span> <span m=''1093280''>or</span> <span m=''1093380''>staying</span>
  <span m=''1093660''>the</span> <span m=''1093750''>same.</span> <span m=''1094800''>And</span>
  <span m=''1095090''>then</span> <span m=''1095250''>the</span> <span m=''1095360''>wrap</span>
  <span m=''1095650''>up</span> <span m=''1096650''>looks</span> <span m=''1096840''>like</span>
  <span m=''1097070''>this.</span> </p><p><span m=''1097530''>In</span> <span m=''1097610''>the</span>
  <span m=''1097760''>end,</span> <span m=''1098560''>you</span> <span m=''1098650''>get</span>
  <span m=''1098770''>a</span> <span m=''1098810''>convex</span> <span m=''1099240''>polygon.</span>
  <span m=''1099870''>Then</span> <span m=''1100190''>you''re</span> <span m=''1100350''>stuck,</span>
  <span m=''1100780''>because</span> <span m=''1100980''>there''s</span> <span m=''1101130''>no</span>
  <span m=''1101310''>edge</span> <span m=''1101470''>to</span> <span m=''1101560''>remove</span>
  <span m=''1101880''>on</span> <span m=''1101970''>the</span> <span m=''1102090''>outside.</span>
  <span m=''1103850''>You''ve</span> <span m=''1104000''>got</span> <span m=''1104120''>to</span>
  <span m=''1104190''>keep</span> <span m=''1104430''>all of</span> <span m=''1104670''>those</span>
  <span m=''1104900''>edges.</span> </p><p><span m=''1107970''>So</span> <span m=''1108150''>that</span>
  <span m=''1108430''>is</span> <span m=''1108700''>the</span> <span m=''1109490''>pseudo-triangulation</span>
  <span m=''1110400''>method</span> <span m=''1110750''>in</span> <span m=''1110920''>a</span>
  <span m=''1110990''>nutshell.</span> <span m=''1111670''>And</span> <span m=''1112650''>it''s</span>
  <span m=''1112940''>expansive.</span> <span m=''1114400''>It</span> <span m=''1114550''>has</span>
  <span m=''1114850''>a</span> <span m=''1114910''>polynomial</span> <span m=''1117700''>in</span>
  <span m=''1117960''>n</span> <span m=''1120470''>number</span> <span m=''1120750''>of</span>
  <span m=''1120820''>moves.</span> </p><p><span m=''1128640''>It''s</span> <span
  m=''1128860''>not</span> <span m=''1129560''>clear</span> <span m=''1131240''>how</span>
  <span m=''1131510''>quickly</span> <span m=''1131880''>you</span> <span m=''1132030''>can</span>
  <span m=''1132170''>compute</span> <span m=''1132530''>the</span> <span m=''1132620''>moves.</span>
  <span m=''1137750''>I</span> <span m=''1137890''>know an</span> <span m=''1138150''>exponential</span>
  <span m=''1138620''>time</span> <span m=''1138860''>algorithm.</span> <span m=''1139420''>There</span>
  <span m=''1139520''>might</span> <span m=''1139690''>be</span> <span m=''1139840''>faster</span>
  <span m=''1140240''>one.</span> <span m=''1141070''>I don''t</span> <span m=''1141250''>think</span>
  <span m=''1141440''>this</span> <span m=''1141620''>has</span> <span m=''1141740''>been</span>
  <span m=''1141900''>resolved.</span> <span m=''1142620''>Let me</span> <span m=''1142890''>just</span>
  <span m=''1143160''>check</span> <span m=''1143420''>my</span> <span m=''1143520''>notes</span>
  <span m=''1143910''>here.</span> </p><p><span m=''1145930''>It says</span> <span
  m=''1146400''>best</span> <span m=''1146690''>algorithm is</span> <span m=''1147130''>exponential</span>
  <span m=''1147930''>to</span> <span m=''1148030''>compute</span> <span m=''1148350''>one</span>
  <span m=''1148540''>move.</span> <span m=''1148790''>In</span> <span m=''1148920''>these</span>
  <span m=''1149140''>examples,</span> <span m=''1149650''>where</span> <span m=''1149760''>they''re</span>
  <span m=''1149920''>all</span> <span m=''1150340''>quadrilaterals</span> <span m=''1151700''>or</span>
  <span m=''1151830''>triangles,</span> <span m=''1152450''>it''s</span> <span m=''1152590''>really</span>
  <span m=''1152810''>easy</span> <span m=''1152990''>to</span> <span m=''1153090''>compute</span>
  <span m=''1153420''>them.</span> <span m=''1154190''>In</span> <span m=''1154240''>general,</span>
  <span m=''1154560''>if</span> <span m=''1154640''>you</span> <span m=''1154730''>get</span>
  <span m=''1154930''>complicated</span> <span m=''1155500''>things,</span> <span
  m=''1156950''>it''s</span> <span m=''1157090''>unclear.</span> </p><p><span m=''1157820''>Pseudo-triangulations</span>
  <span m=''1158670''>though</span> <span m=''1158830''>have</span> <span m=''1158990''>a</span>
  <span m=''1159040''>lot</span> <span m=''1159220''>of</span> <span m=''1159290''>nice</span>
  <span m=''1159490''>structure.</span> <span m=''1159910''>So</span> <span m=''1160040''>maybe</span>
  <span m=''1160290''>it''s</span> <span m=''1160420''>easier</span> <span m=''1160780''>than</span>
  <span m=''1160970''>general</span> <span m=''1161890''>linkage</span> <span m=''1162310''>folding.</span>
  <span m=''1164660''>This,</span> <span m=''1165210''>I</span> <span m=''1165290''>have</span>
  <span m=''1165560''>here,</span> <span m=''1166100''>implementing</span> <span m=''1166530''>this</span>
  <span m=''1166680''>algorithm</span> <span m=''1167050''>would</span> <span m=''1167190''>be</span>
  <span m=''1167320''>a</span> <span m=''1167390''>cool</span> <span m=''1167610''>project.</span>
  </p><p><span m=''1170430''>Oh,</span> <span m=''1170650''>another</span> <span m=''1171010''>open</span>
  <span m=''1171210''>problem</span> <span m=''1171560''>is</span> <span m=''1172300''>how</span>
  <span m=''1172520''>many</span> <span m=''1172800''>steps</span> <span m=''1173210''>does</span>
  <span m=''1173400''>this</span> <span m=''1173590''>algorithm</span> <span m=''1173980''>really</span>
  <span m=''1174220''>need?</span> <span m=''1174990''>Can</span> <span m=''1175140''>you</span>
  <span m=''1175230''>prove</span> <span m=''1175440''>a</span> <span m=''1175490''>pseudo-polynomial</span>
  <span m=''1176300''>bound?</span> <span m=''1177045''>I''m</span> <span m=''1177300''>not</span>
  <span m=''1177490''>sure.</span> </p><p><span m=''1178880''>But</span> <span m=''1178980''>let</span>
  <span m=''1179100''>me</span> <span m=''1179200''>tell</span> <span m=''1179380''>you</span>
  <span m=''1179500''>about</span> <span m=''1180530''>my</span> <span m=''1180680''>personal</span>
  <span m=''1181110''>favorite</span> <span m=''1181480''>algorithm,</span> <span
  m=''1183150''>the</span> <span m=''1183530''>energy</span> <span m=''1183910''>method.</span>
  <span m=''1186340''>This</span> <span m=''1186470''>is</span> <span m=''1186600''>also</span>
  <span m=''1186840''>the</span> <span m=''1186940''>most</span> <span m=''1187210''>recent,</span>
  <span m=''1189636''>in</span> <span m=''1190090''>2004.</span> <span m=''1193320''>The</span>
  <span m=''1193450''>weird</span> <span m=''1193680''>thing</span> <span m=''1193830''>about</span>
  <span m=''1194040''>this</span> <span m=''1194220''>algorithm</span> <span m=''1194480''>is
  that</span> <span m=''1194740''>it is</span> <span m=''1195000''>not</span> <span
  m=''1195300''>expansive.</span> </p><p><span m=''1201760''>It''s</span> <span m=''1201940''>really</span>
  <span m=''1202210''>easy</span> <span m=''1202450''>to</span> <span m=''1202560''>compute</span>
  <span m=''1202930''>one</span> <span m=''1203100''>step</span> <span m=''1203370''>of</span>
  <span m=''1203420''>the</span> <span m=''1203530''>algorithm.</span> <span m=''1206420''>I</span>
  <span m=''1206790''>can</span> <span m=''1206930''>do</span> <span m=''1207070''>it</span>
  <span m=''1207200''>in</span> <span m=''1207430''>quadratic</span> <span m=''1207940''>time,</span>
  <span m=''1210130''>even</span> <span m=''1210310''>exactly.</span> <span m=''1214880''>This</span>
  <span m=''1215080''>one</span> <span m=''1215250''>you</span> <span m=''1215340''>have</span>
  <span m=''1215550''>to</span> <span m=''1215740''>specify</span> <span m=''1216170''>some</span>
  <span m=''1216410''>error</span> <span m=''1216870''>tolerance</span> <span m=''1217290''>epsilon.</span>
  <span m=''1217690''>This</span> <span m=''1217860''>one</span> <span m=''1217950''>you</span>
  <span m=''1218030''>have</span> <span m=''1218180''>to</span> <span m=''1218220''>specify</span>
  <span m=''1218620''>some</span> <span m=''1218820''>error</span> <span m=''1218960''>tolerance</span>
  <span m=''1219380''>epsilon.</span> <span m=''1220160''>Here</span> <span m=''1220340''>you</span>
  <span m=''1220440''>can</span> <span m=''1220550''>do</span> <span m=''1220640''>it</span>
  <span m=''1220690''>perfectly</span> <span m=''1221190''>if</span> <span m=''1221360''>you</span>
  <span m=''1221450''>have</span> <span m=''1221970''>exact</span> <span m=''1222290''>square</span>
  <span m=''1222540''>roots.</span> </p><p><span m=''1224480''>And</span> <span m=''1226090''>the</span>
  <span m=''1226190''>number</span> <span m=''1226540''>of</span> <span m=''1226600''>steps</span>
  <span m=''1226960''>is</span> <span m=''1227090''>also</span> <span m=''1227400''>small.</span>
  <span m=''1238570''>It has</span> <span m=''1238840''>a</span> <span m=''1238900''>pseudo-polynomial</span>
  <span m=''1240670''>number</span> <span m=''1240910''>of</span> <span m=''1240970''>steps.</span>
  <span m=''1241250''>Have</span> <span m=''1241420''>I</span> <span m=''1241590''>talked</span>
  <span m=''1241900''>about</span> <span m=''1242090''>pseudo-polynomial</span> <span
  m=''1242840''>yet?</span> <span m=''1244070''>Maybe,</span> <span m=''1244350''>briefly</span>
  <span m=''1244740''>at</span> <span m=''1244840''>some</span> <span m=''1245000''>point.</span>
  <span m=''1245510''>Let</span> <span m=''1245630''>me</span> <span m=''1245740''>tell</span>
  <span m=''1245930''>you</span> <span m=''1247220''>what</span> <span m=''1247710''>I</span>
  <span m=''1247850''>mean.</span> </p><p><span m=''1249890''>I</span> <span m=''1249960''>want</span>
  <span m=''1250140''>to</span> <span m=''1250180''>be</span> <span m=''1250320''>polynomial</span>
  <span m=''1250940''>in</span> <span m=''1251400''>the</span> <span m=''1251490''>number</span>
  <span m=''1251780''>vertices</span> <span m=''1252290''>n</span> <span m=''1253370''>and</span>
  <span m=''1253560''>another</span> <span m=''1253840''>parameter</span> <span m=''1254740''>r.</span>
  <span m=''1255672''>r</span> <span m=''1256140''>is</span> <span m=''1256260''>going</span>
  <span m=''1256390''>to</span> <span m=''1256470''>be,</span> <span m=''1257360''>basically,</span>
  <span m=''1257850''>the</span> <span m=''1257880''>maximum</span> <span m=''1258650''>distance</span>
  <span m=''1259370''>in</span> <span m=''1259530''>your</span> <span m=''1259750''>initial</span>
  <span m=''1260100''>configuration</span> <span m=''1261330''>divided</span> <span
  m=''1261780''>by</span> <span m=''1262020''>the</span> <span m=''1262140''>minimum</span>
  <span m=''1262530''>distance.</span> <span m=''1264050''>Exactly</span> <span m=''1264440''>how</span>
  <span m=''1264510''>you</span> <span m=''1264590''>define</span> <span m=''1264900''>distance,</span>
  <span m=''1265390''>don''t</span> <span m=''1265550''>worry</span> <span m=''1265710''>about</span>
  <span m=''1266030''>it.</span> <span m=''1267040''>Not</span> <span m=''1267200''>a</span>
  <span m=''1267240''>big</span> <span m=''1267420''>deal.</span> </p><p><span m=''1268600''>So</span>
  <span m=''1268650''>this</span> <span m=''1268880''>is</span> <span m=''1269020''>a</span>
  <span m=''1269100''>geometric</span> <span m=''1269780''>feature</span> <span m=''1270310''>of</span>
  <span m=''1270390''>the</span> <span m=''1270500''>input.</span> <span m=''1270810''>It
  has</span> <span m=''1270970''>nothing</span> <span m=''1271220''>to</span> <span
  m=''1271300''>do</span> <span m=''1271400''>with</span> <span m=''1271540''>n.</span>
  <span m=''1272200''>n</span> <span m=''1272440''>could</span> <span m=''1272590''>stay</span>
  <span m=''1272760''>fixed</span> <span m=''1273120''>and</span> <span m=''1273190''>you</span>
  <span m=''1273280''>could</span> <span m=''1273420''>change</span> <span m=''1273740''>this</span>
  <span m=''1273950''>to</span> <span m=''1274060''>whatever</span> <span m=''1274320''>you</span>
  <span m=''1274460''>want</span> <span m=''1275330''>by</span> <span m=''1275430''>making</span>
  <span m=''1275780''>nastier</span> <span m=''1276190''>and nastier</span> <span
  m=''1276510''>examples.</span> <span m=''1277620''>Nastiness</span> <span m=''1278510''>is</span>
  <span m=''1278670''>measured</span> <span m=''1278980''>here</span> <span m=''1279150''>by</span>
  <span m=''1280450''>how</span> <span m=''1280740''>big</span> <span m=''1281020''>your</span>
  <span m=''1281120''>linkages</span> <span m=''1281610''>versus</span> <span m=''1281900''>how</span>
  <span m=''1282090''>tight</span> <span m=''1282490''>things</span> <span m=''1282750''>get.</span>
  </p><p><span m=''1284130''>So</span> <span m=''1284280''>as</span> <span m=''1284350''>long</span>
  <span m=''1284520''>as</span> <span m=''1284590''>that''s</span> <span m=''1284780''>reasonable,</span>
  <span m=''1285730''>this</span> <span m=''1285890''>is</span> <span m=''1286010''>going</span>
  <span m=''1286150''>to</span> <span m=''1286220''>be</span> <span m=''1286750''>a</span>
  <span m=''1286830''>polynomial</span> <span m=''1287510''>number</span> <span m=''1287860''>of  moves.</span>
  <span m=''1288090''>So</span> <span m=''1288290''>this</span> <span m=''1288450''>is</span>
  <span m=''1288550''>a</span> <span m=''1288610''>good</span> <span m=''1288830''>bound.</span>
  <span m=''1289110''>It''s</span> <span m=''1289260''>better</span> <span m=''1289500''>than</span>
  <span m=''1289690''>all</span> <span m=''1289820''>the</span> <span m=''1289940''>others</span>
  <span m=''1291420''>that''s</span> <span m=''1291850''>been proved</span> <span
  m=''1292320''>anyway.</span> <span m=''1292940''>It might</span> <span m=''1293200''>hold</span>
  <span m=''1293490''>for</span> <span m=''1293690''>some</span> <span m=''1293970''>of</span>
  <span m=''1294010''>the</span> <span m=''1294120''>other</span> <span m=''1294250''>methods.</span>
  </p><p><span m=''1295980''>Here,</span> <span m=''1296540''>of</span> <span m=''1296670''>course,</span>
  <span m=''1296920''>we</span> <span m=''1297020''>have</span> <span m=''1297170''>a</span>
  <span m=''1297400''>better</span> <span m=''1297890''>bound</span> <span m=''1298140''>on</span>
  <span m=''1298210''>the</span> <span m=''1298260''>number</span> <span m=''1298520''>moves.</span>
  <span m=''1298870''>But</span> <span m=''1298990''>each</span> <span m=''1299160''>move</span>
  <span m=''1299400''>is</span> <span m=''1299530''>kind</span> <span m=''1299720''>of</span>
  <span m=''1299820''>complicated.</span> <span m=''1300470''>It''s</span> <span m=''1301100''>pseudo-triangulation.</span>
  <span m=''1303120''>So</span> <span m=''1303390''>there is</span> <span m=''1303650''>a</span>
  <span m=''1303710''>trade</span> <span m=''1303980''>off</span> <span m=''1304150''>between</span>
  <span m=''1304350''>complexity</span> <span m=''1304840''>of</span> <span m=''1304900''>move</span>
  <span m=''1305260''>and</span> <span m=''1305760''>number</span> <span m=''1306080''>of</span>
  <span m=''1306130''>moves.</span> <span m=''1306790''>But</span> <span m=''1306920''>this</span>
  <span m=''1307170''>gets</span> <span m=''1307410''>a</span> <span m=''1307460''>decent</span>
  <span m=''1307790''>bound</span> <span m=''1308010''>for</span> <span m=''1308130''>everything.</span>
  </p><p><span m=''1312280''>You''ve</span> <span m=''1312490''>seen</span> <span
  m=''1312700''>this</span> <span m=''1312870''>method.</span> <span m=''1313200''>I</span>
  <span m=''1313250''>showed</span> <span m=''1313540''>it in</span> <span m=''1313780''>lecture</span>
  <span m=''1314110''>one.</span> <span m=''1315690''>But</span> <span m=''1315960''>it''s</span>
  <span m=''1316120''>interesting</span> <span m=''1316530''>to</span> <span m=''1316600''>contrast</span>
  <span m=''1317140''>it</span> <span m=''1317250''>with</span> <span m=''1317580''>the</span>
  <span m=''1318860''>CDR</span> <span m=''1319360''>method,</span> <span m=''1320910''>which</span>
  <span m=''1321450''>sort</span> <span m=''1321680''>of</span> <span m=''1322110''>unrolled</span>
  <span m=''1322550''>the</span> <span m=''1322660''>teeth</span> <span m=''1322900''>from</span>
  <span m=''1323070''>the</span> <span m=''1323220''>end.</span> <span m=''1324130''>Here,</span>
  <span m=''1324830''>this</span> <span m=''1325070''>method</span> <span m=''1325520''>basically</span>
  <span m=''1325940''>pulls</span> <span m=''1326250''>the</span> <span m=''1326360''>teeth</span>
  <span m=''1326610''>right</span> <span m=''1326965''>apart.</span> <span m=''1328490''>And</span>
  <span m=''1328600''>that''s</span> <span m=''1328800''>possible</span> <span m=''1329300''>because</span>
  <span m=''1329650''>it''s</span> <span m=''1329800''>not</span> <span m=''1330170''>required</span>
  <span m=''1330820''>to</span> <span m=''1330920''>be</span> <span m=''1331040''>expansive.</span>
  </p><p><span m=''1332940''>And</span> <span m=''1333260''>we</span> <span m=''1333330''>have</span>
  <span m=''1333680''>the</span> <span m=''1336270''>double</span> <span m=''1336590''>tree.</span>
  <span m=''1339590''>This</span> <span m=''1339800''>one</span> <span m=''1339930''>looks</span>
  <span m=''1340230''>more</span> <span m=''1340510''>or</span> <span m=''1340530''>less</span>
  <span m=''1340750''>the</span> <span m=''1340820''>same.</span> <span m=''1341070''>It''s</span>
  <span m=''1341190''>a</span> <span m=''1341230''>little</span> <span m=''1341490''>smoother,</span>
  <span m=''1341980''>I</span> <span m=''1342060''>would</span> <span m=''1342210''>say,</span>
  <span m=''1342370''>than</span> <span m=''1342530''>the</span> <span m=''1342660''>other</span>
  <span m=''1342810''>method.</span> <span m=''1343640''>I</span> <span m=''1343720''>don''t</span>
  <span m=''1343880''>have</span> <span m=''1344030''>it</span> <span m=''1344150''>side</span>
  <span m=''1344350''>by</span> <span m=''1344440''>side.</span> <span m=''1344780''>So
  it''s a</span> <span m=''1344970''>little</span> <span m=''1345140''>hard</span>
  <span m=''1345450''>to</span> <span m=''1345940''>guess.</span> </p><p><span m=''1348060''>And</span>
  <span m=''1348320''>what''s</span> <span m=''1348490''>really</span> <span m=''1348640''>exciting</span>
  <span m=''1349010''>about</span> <span m=''1349190''>this</span> <span m=''1349350''>method,</span>
  <span m=''1349610''>to</span> <span m=''1349710''>me,</span> <span m=''1349840''>is</span>
  <span m=''1349970''>that</span> <span m=''1350090''>you</span> <span m=''1350210''>can</span>
  <span m=''1350580''>run</span> <span m=''1350790''>it</span> <span m=''1350880''>for</span>
  <span m=''1351010''>really</span> <span m=''1351290''>large</span> <span m=''1351530''>examples</span>
  <span m=''1353230''>in</span> <span m=''1353390''>like</span> <span m=''1353700''>a</span>
  <span m=''1353770''>minute or</span> <span m=''1354035''>so.</span> <span m=''1354910''>500</span>
  <span m=''1355350''>vertices,</span> <span m=''1355790''>no</span> <span m=''1355900''>big</span>
  <span m=''1356100''>deal.</span> <span m=''1357620''>Whereas,</span> <span m=''1358570''>because</span>
  <span m=''1358760''>each</span> <span m=''1358900''>step</span> <span m=''1359150''>is</span>
  <span m=''1359300''>pretty</span> <span m=''1359560''>easy</span> <span m=''1359820''>to</span>
  <span m=''1359900''>compute</span> <span m=''1360260''>in</span> <span m=''1360340''>quadratic</span>
  <span m=''1360750''>time,</span> <span m=''1361560''>with</span> <span m=''1361880''>this</span>
  <span m=''1362060''>method</span> <span m=''1362420''>you</span> <span m=''1362560''>need
  it</span> <span m=''1362830''>to</span> <span m=''1362920''>solve</span> <span m=''1365420''>a</span>
  <span m=''1365560''>convex</span> <span m=''1365990''>program.</span> <span m=''1366470''>And</span>
  <span m=''1366570''>that''s</span> <span m=''1366860''>a</span> <span m=''1366930''>little</span>
  <span m=''1367550''>costly</span> <span m=''1368860''>for</span> <span m=''1369010''>large</span>
  <span m=''1369280''>examples.</span> </p><p><span m=''1373200''>Cool.</span> <span
  m=''1374370''>So</span> <span m=''1374600''>that''s</span> <span m=''1375060''>the</span>
  <span m=''1375150''>energy</span> <span m=''1375550''>method.</span> <span m=''1375930''>Now
  I''m</span> <span m=''1375990''>going</span> <span m=''1376080''>to</span> <span
  m=''1376120''>actually</span> <span m=''1376380''>tell</span> <span m=''1376540''>you</span>
  <span m=''1376620''>how</span> <span m=''1376790''>it</span> <span m=''1376830''>works.</span>
  </p><p><span m=''1382320''>Big</span> <span m=''1382480''>difference</span> <span
  m=''1382830''>is</span> <span m=''1382970''>it''s not</span> <span m=''1383190''>expansive.</span>
  <span m=''1389510''>And</span> <span m=''1389690''>the</span> <span m=''1389800''>idea</span>
  <span m=''1390110''>is,</span> <span m=''1390430''>well,</span> <span m=''1391370''>being</span>
  <span m=''1391600''>expansive</span> <span m=''1392240''>on</span> <span m=''1392460''>every</span>
  <span m=''1392910''>edge,</span> <span m=''1393380''>that''s</span> <span m=''1393610''>kind</span>
  <span m=''1393810''>of</span> <span m=''1393880''>hard.</span> <span m=''1394710''>How</span>
  <span m=''1394910''>do</span> <span m=''1394980''>I</span> <span m=''1395070''>figure</span>
  <span m=''1395340''>that out?</span> <span m=''1395780''>Oh, it</span> <span m=''1396110''>makes</span>
  <span m=''1396390''>my</span> <span m=''1396480''>brain</span> <span m=''1396760''>hurt.</span>
  <span m=''1397100''>I''ve got</span> <span m=''1397190''>to</span> <span m=''1397230''>solve</span>
  <span m=''1397470''>this</span> <span m=''1397580''>tensegrity.</span> </p><p><span
  m=''1398930''>But</span> <span m=''1400460''>if</span> <span m=''1400610''>I</span>
  <span m=''1400690''>was</span> <span m=''1400820''>just</span> <span m=''1401060''>expansive</span>
  <span m=''1401520''>on</span> <span m=''1401690''>average,</span> <span m=''1402800''>maybe</span>
  <span m=''1403050''>that would</span> <span m=''1403290''>be</span> <span m=''1403420''>good</span>
  <span m=''1403570''>enough.</span> <span m=''1404570''>That''s</span> <span m=''1404770''>the</span>
  <span m=''1404860''>crazy</span> <span m=''1405190''>idea.</span> </p><p><span m=''1407150''>So</span>
  <span m=''1407470''>we</span> <span m=''1407600''>define</span> <span m=''1408190''>this</span>
  <span m=''1408650''>energy</span> <span m=''1409070''>function</span> <span m=''1416570''>that</span>
  <span m=''1416700''>does</span> <span m=''1416970''>just</span> <span m=''1417210''>that.</span>
  <span m=''1418610''>It''s</span> <span m=''1418710''>a</span> <span m=''1418760''>function</span>
  <span m=''1419490''>on</span> <span m=''1419810''>configurations.</span> <span m=''1427290''>So</span>
  <span m=''1427460''>I''m</span> <span m=''1427560''>going</span> <span m=''1427660''>to</span>
  <span m=''1427710''>write</span> <span m=''1427930''>E</span> <span m=''1428140''>of</span>
  <span m=''1428220''>C.</span> <span m=''1430830''>No</span> <span m=''1430990''>M</span>
  <span m=''1431510''>in</span> <span m=''1431600''>this</span> <span m=''1431770''>equation.</span>
  </p><p><span m=''1434230''>We''re</span> <span m=''1434320''>going</span> <span
  m=''1434470''>to</span> <span m=''1434550''>sum</span> <span m=''1434990''>over</span>
  <span m=''1435290''>all</span> <span m=''1435660''>edges</span> <span m=''1436890''>Ew,</span>
  <span m=''1438480''>and</span> <span m=''1438880''>then</span> <span m=''1439060''>sum</span>
  <span m=''1439620''>over all</span> <span m=''1440390''>vertices</span> <span m=''1442740''>U</span>
  <span m=''1443730''>different</span> <span m=''1444180''>from</span> <span m=''1444460''>V
  and</span> <span m=''1444830''>W.</span> <span m=''1446300''>And</span> <span m=''1446560''>we''re</span>
  <span m=''1446670''>going</span> <span m=''1446780''>to</span> <span m=''1446860''>take</span>
  <span m=''1447120''>1</span> <span m=''1448040''>over</span> <span m=''1449030''>the</span>
  <span m=''1449110''>distance</span> <span m=''1450620''>from</span> <span m=''1450890''>U</span>
  <span m=''1451600''>to</span> <span m=''1451880''>the</span> <span m=''1452280''>edge.</span>
  <span m=''1453990''>This</span> <span m=''1454180''>is</span> <span m=''1454400''>just</span>
  <span m=''1454530''>saying</span> <span m=''1455210''>sum</span> <span m=''1455530''>over</span>
  <span m=''1455730''>all</span> <span m=''1456220''>non-incident</span> <span m=''1457210''>vertices</span>
  <span m=''1457610''>and</span> <span m=''1457720''>edges,</span> <span m=''1458970''>take</span>
  <span m=''1459190''>their</span> <span m=''1459320''>distance--</span> <span m=''1460860''>there''s</span>
  <span m=''1461070''>many</span> <span m=''1461320''>ways</span> <span m=''1461500''>you</span>
  <span m=''1461600''>could</span> <span m=''1461710''>define</span> <span m=''1462030''>that,</span>
  <span m=''1462300''>like</span> <span m=''1462500''>the</span> <span m=''1462580''>minimum</span>
  <span m=''1462880''>distance</span> <span m=''1463200''>between</span> <span m=''1463430''>them</span>
  <span m=''1463730''>would</span> <span m=''1463890''>be</span> <span m=''1464010''>fine--</span>
  <span m=''1464700''>take</span> <span m=''1464910''>the</span> <span m=''1464970''>reciprocal,</span>
  <span m=''1465970''>add</span> <span m=''1466190''>them</span> <span m=''1466320''>all</span>
  <span m=''1466510''>up.</span> <span m=''1467450''>This</span> <span m=''1467630''>is</span>
  <span m=''1467710''>my</span> <span m=''1467870''>energy</span> <span m=''1468230''>function.</span>
  </p><p><span m=''1469900''>Kind</span> <span m=''1470060''>of</span> <span m=''1470210''>weird.</span>
  <span m=''1470920''>But</span> <span m=''1471110''>it''s</span> <span m=''1471460''>averaging</span>
  <span m=''1473290''>not</span> <span m=''1473820''>of</span> <span m=''1474090''>distances,</span>
  <span m=''1474560''>but</span> <span m=''1474700''>1</span> <span m=''1474970''>over</span>
  <span m=''1475160''>distances.</span> <span m=''1476640''>So</span> <span m=''1476830''>why</span>
  <span m=''1477100''>is</span> <span m=''1477200''>that</span> <span m=''1477380''>so</span>
  <span m=''1477520''>interesting?</span> <span m=''1478150''>Because</span> <span
  m=''1479570''>distances</span> <span m=''1480080''>are</span> <span m=''1480180''>always</span>
  <span m=''1480500''>positive.</span> <span m=''1481110''>So</span> <span m=''1481300''>I
  only</span> <span m=''1481380''>have</span> <span m=''1481520''>to</span> <span
  m=''1481610''>go</span> <span m=''1481810''>over</span> <span m=''1482000''>here.</span>
  </p><p><span m=''1482790''>If</span> <span m=''1482860''>I</span> <span m=''1482920''>write</span>
  <span m=''1483200''>distance</span> <span m=''1483900''>in</span> <span m=''1484080''>the</span>
  <span m=''1484210''>x-axis,</span> <span m=''1485590''>and</span> <span m=''1486630''>1</span>
  <span m=''1486950''>over</span> <span m=''1487150''>the</span> <span m=''1487280''>distance</span>
  <span m=''1488240''>in</span> <span m=''1488340''>the</span> <span m=''1488430''>y-axis,</span>
  <span m=''1489940''>the</span> <span m=''1490050''>plot</span> <span m=''1490410''>of</span>
  <span m=''1490460''>that</span> <span m=''1490670''>function</span> <span m=''1491020''>looks</span>
  <span m=''1491230''>like</span> <span m=''1491410''>this.</span> <span m=''1492550''>It</span>
  <span m=''1492920''>has</span> <span m=''1493100''>this</span> <span m=''1493290''>vertical</span>
  <span m=''1493740''>asymptote</span> <span m=''1494410''>at</span> <span m=''1494650''>0.</span>
  </p><p><span m=''1496190''>So</span> <span m=''1497010''>if</span> <span m=''1497270''>the</span>
  <span m=''1497420''>distance</span> <span m=''1497840''>were</span> <span m=''1497990''>to</span>
  <span m=''1498050''>go</span> <span m=''1498210''>to</span> <span m=''1498290''>0,</span>
  <span m=''1498740''>which</span> <span m=''1498900''>is</span> <span m=''1499010''>bad</span>
  <span m=''1499470''>for</span> <span m=''1499600''>me</span> <span m=''1499740''>because</span>
  <span m=''1499960''>that''s</span> <span m=''1500180''>one</span> <span m=''1500320''>thing</span>
  <span m=''1500500''>start</span> <span m=''1500740''>crossing--</span> <span m=''1502130''>they</span>
  <span m=''1502240''>will</span> <span m=''1502340''>start</span> <span m=''1502620''>touching</span>
  <span m=''1503020''>at</span> <span m=''1503160''>d equals</span> <span m=''1503480''>0,</span>
  <span m=''1503740''>and</span> <span m=''1503810''>after</span> <span m=''1504070''>that</span>
  <span m=''1504300''>they</span> <span m=''1504330''>might</span> <span m=''1504540''>cross--</span>
  <span m=''1505760''>the</span> <span m=''1505920''>energy</span> <span m=''1506270''>shoots</span>
  <span m=''1506580''>to</span> <span m=''1506800''>positive</span> <span m=''1507290''>infinity.</span>
  <span m=''1509360''>So</span> <span m=''1509400''>if</span> <span m=''1509500''>I</span>
  <span m=''1509560''>take</span> <span m=''1509770''>the</span> <span m=''1509850''>sum</span>
  <span m=''1510190''>over</span> <span m=''1510430''>all</span> <span m=''1510580''>these,</span>
  <span m=''1511010''>if</span> <span m=''1511210''>any</span> <span m=''1511560''>of</span>
  <span m=''1511660''>the</span> <span m=''1511750''>distances</span> <span m=''1512630''>decrease</span>
  <span m=''1513110''>to</span> <span m=''1513230''>0</span> <span m=''1514460''>then</span>
  <span m=''1514710''>the</span> <span m=''1514820''>energy</span> <span m=''1515130''>will</span>
  <span m=''1515240''>shoot</span> <span m=''1515470''>to</span> <span m=''1515560''>infinity.</span>
  </p><p><span m=''1517890''>What</span> <span m=''1518130''>if</span> <span m=''1518600''>my</span>
  <span m=''1518770''>distances</span> <span m=''1519380''>increase?</span> <span
  m=''1520960''>Because</span> <span m=''1521160''>I</span> <span m=''1521320''>know</span>
  <span m=''1522210''>expansive</span> <span m=''1522740''>motions</span> <span m=''1523150''>exist.</span>
  <span m=''1524960''>That''s what</span> <span m=''1525180''>we</span> <span m=''1525340''>proved</span>
  <span m=''1525580''>last</span> <span m=''1525870''>time.</span> <span m=''1528560''>I''m</span>
  <span m=''1528660''>not</span> <span m=''1528860''>going</span> <span m=''1528990''>to</span>
  <span m=''1529270''>compute</span> <span m=''1529680''>them.</span> <span m=''1530390''>But</span>
  <span m=''1530530''>I</span> <span m=''1530580''>know</span> <span m=''1530720''>they''re</span>
  <span m=''1530920''>out</span> <span m=''1531070''>there</span> <span m=''1531240''>somewhere.</span>
  </p><p><span m=''1533240''>If I</span> <span m=''1533330''>had</span> <span m=''1533530''>an</span>
  <span m=''1533620''>expansive</span> <span m=''1534150''>motion,</span> <span m=''1534530''>all</span>
  <span m=''1534840''>of</span> <span m=''1534940''>these</span> <span m=''1535160''>distances</span>
  <span m=''1536080''>increase.</span> <span m=''1538210''>So</span> <span m=''1538360''>that</span>
  <span m=''1538510''>means</span> <span m=''1538730''>this</span> <span m=''1538990''>reciprocal</span>
  <span m=''1539990''>decreases.</span> <span m=''1541810''>So</span> <span m=''1541860''>I</span>
  <span m=''1541980''>have--</span> <span m=''1542490''>it''s</span> <span m=''1542680''>hard</span>
  <span m=''1542870''>to</span> <span m=''1542920''>imagine--</span> <span m=''1543320''>I</span>
  <span m=''1543370''>have</span> <span m=''1543530''>this</span> <span m=''1543680''>giant</span>
  <span m=''1544580''>dimensional</span> <span m=''1545160''>configuration</span>
  <span m=''1545810''>space.</span> <span m=''1546150''>It has</span> <span m=''1546430''>d</span>
  <span m=''1546620''>times</span> <span m=''1546910''>n</span> <span m=''1547040''>dimensions,</span>
  <span m=''1547510''>whatever.</span> <span m=''1548295''>A</span> <span m=''1548610''>lot</span>
  <span m=''1548810''>of</span> <span m=''1548870''>stuff.</span> </p><p><span m=''1551660''>I''m</span>
  <span m=''1551900''>somewhere.</span> <span m=''1553910''>But</span> <span m=''1554040''>if</span>
  <span m=''1554170''>I</span> <span m=''1554500''>now</span> <span m=''1554740''>plotted--</span>
  <span m=''1556000''>imagine</span> <span m=''1556410''>that''s</span> <span m=''1557280''>in</span>
  <span m=''1557530''>two</span> <span m=''1557720''>dimensions,</span> <span m=''1558370''>in
  the</span> <span m=''1558590''>plane</span> <span m=''1558880''>here,</span> <span
  m=''1560190''>so</span> <span m=''1560370''>that''s</span> <span m=''1560670''>there--</span>
  <span m=''1561590''>and</span> <span m=''1561630''>then</span> <span m=''1561850''>in
  the</span> <span m=''1561950''>third</span> <span m=''1562170''>dimension</span>
  <span m=''1562520''>I</span> <span m=''1562580''>plot</span> <span m=''1562940''>what</span>
  <span m=''1563140''>is</span> <span m=''1563280''>this</span> <span m=''1563470''>energy</span>
  <span m=''1563870''>landscape.</span> <span m=''1564430''>For</span> <span m=''1564590''>each</span>
  <span m=''1564770''>of</span> <span m=''1564820''>these</span> <span m=''1564980''>configurations</span>
  <span m=''1565670''>I</span> <span m=''1565730''>compute</span> <span m=''1566090''>some</span>
  <span m=''1566260''>height.</span> <span m=''1566840''>What</span> <span m=''1567030''>is</span>
  <span m=''1567130''>my</span> <span m=''1567290''>energy?</span> </p><p><span m=''1568080''>I</span>
  <span m=''1568160''>get</span> <span m=''1568350''>some</span> <span m=''1568520''>3D</span>
  <span m=''1568810''>surface</span> <span m=''1569210''>here.</span> <span m=''1570690''>In</span>
  <span m=''1570890''>general,</span> <span m=''1571180''>it''s</span> <span m=''1571290''>going</span>
  <span m=''1571410''>to</span> <span m=''1571460''>be</span> <span m=''1572050''>d</span>
  <span m=''1572190''>times</span> <span m=''1572430''>n</span> <span m=''1572580''>plus</span>
  <span m=''1572830''>1</span> <span m=''1573060''>dimensions.</span> <span m=''1575050''>Here''s</span>
  <span m=''1575370''>the</span> <span m=''1575440''>configuration</span> <span m=''1576020''>space.</span>
  <span m=''1576350''>We</span> <span m=''1576470''>plot</span> <span m=''1576830''>over</span>
  <span m=''1577090''>that.</span> </p><p><span m=''1578540''>What</span> <span m=''1578860''>I''m</span>
  <span m=''1579000''>saying</span> <span m=''1579350''>is,</span> <span m=''1579560''>because</span>
  <span m=''1579860''>expansive</span> <span m=''1580220''>motions</span> <span m=''1580610''>exist,</span>
  <span m=''1581880''>there</span> <span m=''1581990''>has</span> <span m=''1582200''>to</span>
  <span m=''1582270''>be a motion</span> <span m=''1582730''>for</span> <span m=''1582890''>every</span>
  <span m=''1583140''>point</span> <span m=''1583600''>that</span> <span m=''1584030''>decreases</span>
  <span m=''1584580''>energy.</span> <span m=''1586080''>Because</span> <span m=''1586270''>if</span>
  <span m=''1586360''>you</span> <span m=''1586490''>decrease</span> <span m=''1586900''>every</span>
  <span m=''1587120''>distance,</span> <span m=''1587590''>you</span> <span m=''1587750''>also</span>
  <span m=''1588070''>decrease</span> <span m=''1588520''>them</span> <span m=''1588710''>on</span>
  <span m=''1588870''>average</span> <span m=''1589450''>in</span> <span m=''1589560''>this</span>
  <span m=''1589750''>sense.</span> <span m=''1591310''>If</span> <span m=''1591460''>every</span>
  <span m=''1591690''>term</span> <span m=''1591960''>decreases,</span> <span m=''1592690''>then</span>
  <span m=''1592730''>of</span> <span m=''1592820''>course,</span> <span m=''1593100''>the
  sum</span> <span m=''1593430''>will.</span> <span m=''1594740''>So</span> <span
  m=''1594910''>this</span> <span m=''1595150''>means</span> <span m=''1596100''>energy</span>
  <span m=''1599100''>decreasing</span> <span m=''1603670''>motions</span> <span m=''1604820''>exist.</span>
  </p><p><span m=''1609616''>Now</span> <span m=''1610120''>energy</span> <span m=''1610470''>decreasing</span>
  <span m=''1611040''>feels</span> <span m=''1611310''>like</span> <span m=''1611470''>a</span>
  <span m=''1611540''>good</span> <span m=''1611750''>thing.</span> <span m=''1611950''>Because</span>
  <span m=''1612150''>I</span> <span m=''1612260''>start</span> <span m=''1612620''>somewhere,</span>
  <span m=''1614361''>it</span> <span m=''1614760''>has</span> <span m=''1614940''>some</span>
  <span m=''1615190''>energy,</span> <span m=''1615820''>not</span> <span m=''1616080''>infinity.</span>
  <span m=''1617480''>If</span> <span m=''1617610''>I</span> <span m=''1617680''>decrease</span>
  <span m=''1618120''>the</span> <span m=''1618230''>energy,</span> <span m=''1618620''>it''s</span>
  <span m=''1618750''>really</span> <span m=''1618980''>hard</span> <span m=''1619310''>for</span>
  <span m=''1619490''>my</span> <span m=''1619650''>energy</span> <span m=''1619990''>to</span>
  <span m=''1620060''>go</span> <span m=''1620250''>to</span> <span m=''1620330''>plus</span>
  <span m=''1620610''>infinity.</span> <span m=''1621912''>It</span> <span m=''1622280''>can''t</span>
  <span m=''1622480''>happen.</span> <span m=''1623880''>So</span> <span m=''1624020''>all</span>
  <span m=''1624260''>I</span> <span m=''1624330''>need</span> <span m=''1624550''>to</span>
  <span m=''1624650''>do</span> <span m=''1625960''>is</span> <span m=''1627930''>follow</span>
  <span m=''1629850''>any</span> <span m=''1631700''>energy</span> <span m=''1632150''>decreasing</span>
  <span m=''1632610''>motion.</span> </p><p></p><p><span m=''1638830''>It</span> <span
  m=''1638940''>might</span> <span m=''1639200''>be</span> <span m=''1639290''>an</span>
  <span m=''1639360''>expansive</span> <span m=''1639830''>one,</span> <span m=''1640020''>but</span>
  <span m=''1640130''>probably</span> <span m=''1640660''>not.</span> <span m=''1641910''>We</span>
  <span m=''1641970''>know</span> <span m=''1642220''>that</span> <span m=''1642410''>there</span>
  <span m=''1642570''>are</span> <span m=''1642710''>energy</span> <span m=''1642980''>decreasing</span>
  <span m=''1643470''>motions</span> <span m=''1643790''>because</span> <span m=''1644240''>there</span>
  <span m=''1644510''>are</span> <span m=''1644570''>expansive</span> <span m=''1645050''>motions.</span>
  <span m=''1645820''>But</span> <span m=''1646000''>let''s</span> <span m=''1646140''>just</span>
  <span m=''1646270''>take</span> <span m=''1646410''>any</span> <span m=''1646690''>energy</span>
  <span m=''1647000''>decreasing</span> <span m=''1647440''>motion,</span> <span m=''1647840''>sort</span>
  <span m=''1648100''>of</span> <span m=''1648300''>expansive</span> <span m=''1648790''>on</span>
  <span m=''1648910''>average.</span> <span m=''1650960''>Then</span> <span m=''1651220''>it</span>
  <span m=''1651440''>won''t</span> <span m=''1653780''>self-intersect</span> <span
  m=''1655860''>because</span> <span m=''1656870''>if</span> <span m=''1657050''>energy</span>
  <span m=''1657380''>decreases</span> <span m=''1658420''>it will</span> <span m=''1658570''>never</span>
  <span m=''1658800''>get</span> <span m=''1658950''>to</span> <span m=''1659010''>plus</span>
  <span m=''1659270''>infinity.</span> <span m=''1659720''>And</span> <span m=''1659800''>therefore</span>
  <span m=''1660100''>none</span> <span m=''1660310''>of</span> <span m=''1660400''>the</span>
  <span m=''1660480''>distances</span> <span m=''1660940''>will</span> <span m=''1661070''>go</span>
  <span m=''1661200''>to</span> <span m=''1661280''>0.</span> </p><p><span m=''1664500''>So</span>
  <span m=''1664780''>what</span> <span m=''1664970''>this</span> <span m=''1665140''>algorithm</span>
  <span m=''1665510''>does</span> <span m=''1665850''>is</span> <span m=''1666150''>follow</span>
  <span m=''1668060''>the</span> <span m=''1668340''>gradient.</span> <span m=''1677500''>So</span>
  <span m=''1678140''>I</span> <span m=''1678260''>should</span> <span m=''1678930''>say</span>
  <span m=''1679090''>something</span> <span m=''1679420''>about</span> <span m=''1679640''>what</span>
  <span m=''1679820''>this</span> <span m=''1680020''>notation</span> <span m=''1680380''>is.</span>
  <span m=''1680500''>This</span> <span m=''1680690''>is</span> <span m=''1681840''>whatever,</span>
  <span m=''1682100''>higher</span> <span m=''1682330''>order</span> <span m=''1682510''>calculus.</span>
  </p><p><span m=''1686340''>You</span> <span m=''1686540''>live</span> <span m=''1686750''>in</span>
  <span m=''1686850''>some</span> <span m=''1687140''>space.</span> <span m=''1689120''>You''re</span>
  <span m=''1689340''>on like</span> <span m=''1689720''>some</span> <span m=''1689990''>hill,</span>
  <span m=''1690310''>or</span> <span m=''1690460''>whatever.</span> <span m=''1690940''>You''re</span>
  <span m=''1692296''>on some</span> <span m=''1692690''>surface.</span> <span m=''1693380''>And</span>
  <span m=''1693750''>you</span> <span m=''1693870''>say</span> <span m=''1694030''>well</span>
  <span m=''1694140''>I''d</span> <span m=''1694270''>really</span> <span m=''1694480''>like</span>
  <span m=''1694730''>to</span> <span m=''1694840''>go</span> <span m=''1694990''>downhill</span>
  <span m=''1695640''>from</span> <span m=''1695840''>here.</span> </p><p><span m=''1696560''>And</span>
  <span m=''1696700''>there</span> <span m=''1696780''>might</span> <span m=''1696940''>be</span>
  <span m=''1697050''>many</span> <span m=''1697290''>downhill</span> <span m=''1697640''>options.</span>
  <span m=''1698030''>There</span> <span m=''1698110''>might</span> <span m=''1698260''>be</span>
  <span m=''1698350''>many</span> <span m=''1698610''>uphill</span> <span m=''1698890''>options.</span>
  <span m=''1699270''>This is</span> <span m=''1699370''>some</span> <span m=''1699620''>crazy</span>
  <span m=''1700050''>high</span> <span m=''1700180''>dimensional</span> <span m=''1700930''>choice.</span>
  </p><p><span m=''1701960''>Just</span> <span m=''1702200''>take</span> <span m=''1702440''>the</span>
  <span m=''1702580''>option</span> <span m=''1703130''>that</span> <span m=''1703230''>decreases</span>
  <span m=''1704390''>energy</span> <span m=''1704790''>the</span> <span m=''1704890''>fastest,</span>
  <span m=''1705890''>the</span> <span m=''1706000''>most</span> <span m=''1706400''>downhill.</span>
  <span m=''1707210''>That</span> <span m=''1707430''>is</span> <span m=''1708250''>negative</span>
  <span m=''1708940''>gradient</span> <span m=''1709390''>of</span> <span m=''1709490''>E.</span>
  <span m=''1711160''>Believe</span> <span m=''1711400''>me</span> <span m=''1711520''>that</span>
  <span m=''1711650''>it</span> <span m=''1711740''>exists.</span> <span m=''1712260''>It</span>
  <span m=''1712380''>exists</span> <span m=''1712700''>because</span> <span m=''1713060''>this</span>
  <span m=''1713590''>energy</span> <span m=''1713960''>function</span> <span m=''1714350''>is</span>
  <span m=''1714460''>smooth,</span> <span m=''1714990''>in</span> <span m=''1715110''>some</span>
  <span m=''1715310''>sense.</span> </p><p><span m=''1718460''>You''re</span> <span
  m=''1718550''>basically</span> <span m=''1718870''>taking</span> <span m=''1719130''>first</span>
  <span m=''1719350''>derivatives.</span> <span m=''1719930''>That</span> <span m=''1720130''>gives</span>
  <span m=''1720310''>you</span> <span m=''1720450''>the</span> <span m=''1721110''>highest</span>
  <span m=''1721510''>chain--</span> <span m=''1721910''>or</span> <span m=''1722050''>you</span>
  <span m=''1722160''>take</span> <span m=''1722340''>the</span> <span m=''1722420''>place</span>
  <span m=''1722680''>that</span> <span m=''1722780''>has</span> <span m=''1722930''>the
  highest</span> <span m=''1723190''>change</span> <span m=''1723570''>and</span>
  <span m=''1723630''>boom.</span> <span m=''1724390''>That</span> <span m=''1724590''>gives</span>
  <span m=''1724750''>it</span> <span m=''1724860''>to</span> <span m=''1724950''>you.</span>
  </p><p><span m=''1725060''>It''s</span> <span m=''1725210''>very</span> <span m=''1725390''>easy</span>
  <span m=''1725570''>to</span> <span m=''1725650''>compute</span> <span m=''1726390''>because</span>
  <span m=''1726640''>this</span> <span m=''1726860''>function</span> <span m=''1727190''>has</span>
  <span m=''1727510''>quadratically</span> <span m=''1728100''>many</span> <span m=''1728330''>terms.</span>
  <span m=''1728690''>It</span> <span m=''1728770''>takes</span> <span m=''1728990''>about</span>
  <span m=''1729210''>n</span> <span m=''1729340''>squared</span> <span m=''1729650''>time</span>
  <span m=''1729940''>to</span> <span m=''1730080''>find</span> <span m=''1730370''>it.</span>
  <span m=''1731930''>And</span> <span m=''1732650''>that</span> <span m=''1732870''>gives</span>
  <span m=''1733050''>you</span> <span m=''1735130''>some</span> <span m=''1735550''>energy</span>
  <span m=''1735870''>decrease</span> <span m=''1736200''>in motion.</span> <span
  m=''1736550''>It''s</span> <span m=''1736620''>just</span> <span m=''1736790''>an</span>
  <span m=''1736850''>easy</span> <span m=''1737110''>one</span> <span m=''1737280''>to</span>
  <span m=''1737340''>find.</span> <span m=''1737990''>And</span> <span m=''1738170''>that''s</span>
  <span m=''1738390''>what</span> <span m=''1738490''>we''re</span> <span m=''1738670''>animating</span>
  <span m=''1739790''>all</span> <span m=''1740000''>the</span> <span m=''1740070''>time.</span>
  </p><p><span m=''1740480''>So we</span> <span m=''1740670''>just</span> <span m=''1741230''>find</span>
  <span m=''1741450''>energy</span> <span m=''1741900''>decreasing</span> <span m=''1742270''>motion,</span>
  <span m=''1742570''>move</span> <span m=''1742740''>a</span> <span m=''1742790''>little</span>
  <span m=''1743050''>bit</span> <span m=''1743170''>in</span> <span m=''1743260''>that</span>
  <span m=''1743440''>direction.</span> <span m=''1744230''>Not</span> <span m=''1744430''>too</span>
  <span m=''1744590''>much,</span> <span m=''1744940''>because</span> <span m=''1745140''>if</span>
  <span m=''1745250''>you</span> <span m=''1745350''>go--</span> <span m=''1746040''>it''s</span>
  <span m=''1746510''>again</span> <span m=''1746760''>a</span> <span m=''1746810''>first</span>
  <span m=''1747060''>derivative.</span> <span m=''1747960''>This</span> <span m=''1748070''>is</span>
  <span m=''1748160''>only</span> <span m=''1748370''>an</span> <span m=''1748410''>infinitesimal</span>
  <span m=''1749010''>motion.</span> </p><p><span m=''1749710''>But</span> <span m=''1749820''>we''re</span>
  <span m=''1749930''>actually</span> <span m=''1750170''>going</span> <span m=''1750280''>to</span>
  <span m=''1751630''>move</span> <span m=''1751840''>in</span> <span m=''1751880''>that</span>
  <span m=''1752030''>direction</span> <span m=''1752330''>for a</span> <span m=''1752500''>positive</span>
  <span m=''1752880''>amount</span> <span m=''1753110''>of</span> <span m=''1753200''>time.</span>
  <span m=''1753740''>As long as</span> <span m=''1754080''>we</span> <span m=''1754180''>don''t</span>
  <span m=''1754320''>go</span> <span m=''1754440''>too</span> <span m=''1754670''>far,</span>
  <span m=''1755160''>and</span> <span m=''1755320''>we</span> <span m=''1755430''>can</span>
  <span m=''1755600''>find</span> <span m=''1755850''>how</span> <span m=''1756010''>far</span>
  <span m=''1756300''>by</span> <span m=''1756410''>binary</span> <span m=''1756770''>search,</span>
  <span m=''1757910''>we</span> <span m=''1758160''>won''t</span> <span m=''1758380''>self-intersect.</span>
  <span m=''1759370''>Because</span> <span m=''1759560''>we know</span> <span m=''1759680''>locally</span>
  <span m=''1760330''>it''s</span> <span m=''1760470''>decreasing</span> <span m=''1760920''>energy.</span>
  <span m=''1761350''>If</span> <span m=''1761770''>we</span> <span m=''1761870''>go</span>
  <span m=''1762040''>small</span> <span m=''1762340''>enough</span> <span m=''1762500''>step</span>
  <span m=''1762700''>it</span> <span m=''1762780''>really</span> <span m=''1763030''>will</span>
  <span m=''1763300''>decrease</span> <span m=''1763680''>energy,</span> <span m=''1765140''>and</span>
  <span m=''1765500''>then</span> <span m=''1765650''>life</span> <span m=''1765860''>is</span>
  <span m=''1765970''>good.</span> </p><p><span m=''1766660''>So</span> <span m=''1766810''>it''s</span>
  <span m=''1766960''>really</span> <span m=''1767210''>easy</span> <span m=''1768810''>to</span>
  <span m=''1769010''>do</span> <span m=''1769150''>this.</span> <span m=''1770600''>Super</span>
  <span m=''1770930''>simple</span> <span m=''1771240''>algorithm.</span> <span m=''1773170''>Good.</span>
  <span m=''1775150''>It''s</span> <span m=''1775270''>non-expansive</span> <span
  m=''1776000''>because</span> <span m=''1776320''>we''re</span> <span m=''1776680''>only</span>
  <span m=''1777460''>decreasing</span> <span m=''1777870''>the</span> <span m=''1778000''>average,</span>
  <span m=''1778960''>not</span> <span m=''1779140''>each</span> <span m=''1779320''>of</span>
  <span m=''1779390''>the</span> <span m=''1779490''>terms.</span> <span m=''1781932''>Do,</span>
  <span m=''1782385''>do, do,</span> <span m=''1782840''>do,</span> <span m=''1782970''>do.</span>
  </p><p><span m=''1784730''>You</span> <span m=''1784900''>can</span> <span m=''1785010''>prove</span>
  <span m=''1786530''>the</span> <span m=''1786680''>number</span> <span m=''1786950''>of</span>
  <span m=''1787000''>steps--</span> <span m=''1787470''>this</span> <span m=''1787540''>is</span>
  <span m=''1787670''>the</span> <span m=''1788480''>part</span> <span m=''1788670''>I''m</span>
  <span m=''1788790''>most</span> <span m=''1789010''>proud</span> <span m=''1789320''>of</span>
  <span m=''1789460''>here--</span> <span m=''1790980''>is</span> <span m=''1791970''>pseudo-polynomial,</span>
  <span m=''1793130''>polynomial</span> <span m=''1794350''>in</span> <span m=''1794900''>n</span>
  <span m=''1795640''>and</span> <span m=''1795890''>r.</span> <span m=''1798220''>What</span>
  <span m=''1798430''>is</span> <span m=''1798540''>the</span> <span m=''1798640''>polynomial?</span>
  <span m=''1800420''>n</span> <span m=''1801225''>to the</span> <span m=''1801570''>123</span>
  <span m=''1803250''>times</span> <span m=''1803500''>r</span> <span m=''1803850''>to</span>
  <span m=''1803980''>the</span> <span m=''1804080''>81.</span> <span m=''1806010''>This</span>
  <span m=''1806190''>is</span> <span m=''1806290''>the</span> <span m=''1806400''>largest</span>
  <span m=''1807090''>polynomial</span> <span m=''1807610''>bound</span> <span m=''1807880''>I</span>
  <span m=''1807940''>know of</span> <span m=''1808890''>that''s</span> <span m=''1809090''>not</span>
  <span m=''1809410''>dependent</span> <span m=''1809780''>on</span> <span m=''1809910''>dimension.</span>
  <span m=''1812010''>So</span> <span m=''1812060''>I''m</span> <span m=''1812150''>very</span>
  <span m=''1812360''>proud.</span> </p><p><span m=''1812710''>In</span> <span m=''1812800''>practice,</span>
  <span m=''1813480''>the</span> <span m=''1813590''>number</span> <span m=''1813820''>of</span>
  <span m=''1813870''>steps</span> <span m=''1814220''>is</span> <span m=''1814450''>much,</span>
  <span m=''1814890''>much</span> <span m=''1814970''>smaller</span> <span m=''1815290''>than</span>
  <span m=''1815410''>this.</span> <span m=''1815770''>This is</span> <span m=''1815870''>what</span>
  <span m=''1816010''>we</span> <span m=''1816120''>could</span> <span m=''1816270''>prove</span>
  <span m=''1816620''>in</span> <span m=''1816760''>an</span> <span m=''1816870''>easy</span>
  <span m=''1817180''>way.</span> <span m=''1817870''>If</span> <span m=''1817940''>you</span>
  <span m=''1818070''>want</span> <span m=''1818270''>a</span> <span m=''1818340''>project,</span>
  <span m=''1818890''>it''s</span> <span m=''1818980''>a</span> <span m=''1819030''>little</span>
  <span m=''1819240''>tedious,</span> <span m=''1820000''>but</span> <span m=''1820030''>it</span>
  <span m=''1820080''>would</span> <span m=''1820240''>be</span> <span m=''1820390''>easy,</span>
  <span m=''1820740''>I''m</span> <span m=''1820830''>pretty</span> <span m=''1821020''>sure.</span>
  <span m=''1821700''>You</span> <span m=''1821880''>could</span> <span m=''1822050''>decrease</span>
  <span m=''1822500''>this</span> <span m=''1822720''>to,</span> <span m=''1822870''>I
  don''t</span> <span m=''1823080''>know,</span> <span m=''1824070''>at</span> <span
  m=''1824180''>least</span> <span m=''1824450''>n to</span> <span m=''1824670''>the</span>
  <span m=''1824800''>20</span> <span m=''1825300''>or</span> <span m=''1825410''>something</span>
  <span m=''1826670''>by</span> <span m=''1826820''>being</span> <span m=''1827030''>a</span>
  <span m=''1827080''>little</span> <span m=''1827270''>more</span> <span m=''1827430''>careful</span>
  <span m=''1827840''>on</span> <span m=''1827890''>the</span> <span m=''1828000''>analysis.</span>
  </p><p><span m=''1828720''>But</span> <span m=''1828820''>once</span> <span m=''1828900''>we</span>
  <span m=''1828990''>got</span> <span m=''1829200''>something</span> <span m=''1829550''>that</span>
  <span m=''1829610''>was</span> <span m=''1829790''>pseudo-polynomial</span> <span
  m=''1830360''>we</span> <span m=''1830450''>were</span> <span m=''1830870''>happy.</span>
  <span m=''1832010''>So</span> <span m=''1832090''>we</span> <span m=''1832170''>could</span>
  <span m=''1832290''>leave</span> <span m=''1832760''>others</span> <span m=''1833100''>to</span>
  <span m=''1833210''>figure</span> <span m=''1833490''>out</span> <span m=''1834130''>the</span>
  <span m=''1834250''>right</span> <span m=''1834540''>bound.</span> <span m=''1835110''>It''s</span>
  <span m=''1835260''>a</span> <span m=''1835300''>little</span> <span m=''1835500''>tricky</span>
  <span m=''1835890''>with</span> <span m=''1836120''>these</span> <span m=''1836290''>gradient</span>
  <span m=''1836610''>descent</span> <span m=''1836890''>algorithms</span> <span m=''1837280''>to</span>
  <span m=''1837370''>get</span> <span m=''1837770''>good</span> <span m=''1837960''>bounds.</span>
  <span m=''1838890''>In</span> <span m=''1839000''>practice</span> <span m=''1839420''>they</span>
  <span m=''1839490''>work</span> <span m=''1839720''>really</span> <span m=''1839880''>well,</span>
  <span m=''1840150''>because</span> <span m=''1840560''>the</span> <span m=''1840640''>gradient</span>
  <span m=''1840890''>is</span> <span m=''1841030''>not</span> <span m=''1841210''>as</span>
  <span m=''1841320''>nasty</span> <span m=''1841830''>as</span> <span m=''1842530''>you</span>
  <span m=''1842650''>might</span> <span m=''1843410''>imagine</span> <span m=''1843780''>it</span>
  <span m=''1843870''>to</span> <span m=''1843950''>be</span> <span m=''1844030''>in</span>
  <span m=''1844100''>the</span> <span m=''1844170''>worst</span> <span m=''1844370''>case.</span>
  </p><p><span m=''1844640''>But</span> <span m=''1844710''>the</span> <span m=''1844820''>worst</span>
  <span m=''1845020''>case</span> <span m=''1845190''>bound,</span> <span m=''1845370''>hey,</span>
  <span m=''1845600''>it''s</span> <span m=''1845830''>pseudo-polynomial.</span> <span
  m=''1847670''>It''s</span> <span m=''1848030''>a</span> <span m=''1848080''>nice</span>
  <span m=''1848320''>theoretical</span> <span m=''1848790''>guarantee.</span> <span
  m=''1849290''>And</span> <span m=''1849470''>in</span> <span m=''1849550''>practice</span>
  <span m=''1849990''>it</span> <span m=''1850080''>also</span> <span m=''1850660''>happens</span>
  <span m=''1851000''>to</span> <span m=''1851100''>work.</span> <span m=''1851350''>Like</span>
  <span m=''1851490''>these</span> <span m=''1851660''>examples</span> <span m=''1852140''>only</span>
  <span m=''1852380''>take,</span> <span m=''1852900''>I</span> <span m=''1852960''>don''t</span>
  <span m=''1853060''>know,</span> <span m=''1853230''>a</span> <span m=''1853720''>few
  hundred</span> <span m=''1853910''>steps,</span> <span m=''1854720''>1,000</span>
  <span m=''1855070''>steps,</span> <span m=''1855520''>whatever.</span> </p><p><span
  m=''1855950''>AUDIENCE: Where do those</span> <span m=''1856802''>numbers</span>
  <span m=''1857228''>come</span> <span m=''1857654''>from?</span> </p><p><span m=''1858510''>PROFESSOR:
  Where</span> <span m=''1858650''>does</span> <span m=''1858780''>123</span> <span
  m=''1859580''>come</span> <span m=''1859780''>from?</span> <span m=''1860370''>We</span>
  <span m=''1860440''>really</span> <span m=''1860640''>wanted</span> <span m=''1860960''>it</span>
  <span m=''1861090''>to</span> <span m=''1861170''>be</span> <span m=''1861290''>1,</span>
  <span m=''1861420''>2, 3.</span> <span m=''1862140''>81</span> <span m=''1862500''>is</span>
  <span m=''1862580''>my</span> <span m=''1862690''>birth</span> <span m=''1862970''>year.</span>
  </p><p><span m=''1863796''>[LAUGHTER]</span> </p><p><span m=''1865780''>PROFESSOR:
  That''s</span> <span m=''1865840''>why</span> <span m=''1865990''>I</span> <span
  m=''1866010''>like</span> <span m=''1866240''>this</span> <span m=''1866410''>number</span>
  <span m=''1866650''>so</span> <span m=''1866790''>much.</span> <span m=''1867445''>Oh,</span>
  <span m=''1867730''>actually</span> <span m=''1868100''>here</span> <span m=''1868310''>I</span>
  <span m=''1868340''>have</span> <span m=''1868570''>41</span> <span m=''1869020''>written.</span>
  <span m=''1869760''>I''m</span> <span m=''1869830''>pretty</span> <span m=''1870010''>sure</span>
  <span m=''1870160''>it''s</span> <span m=''1870260''>81</span> <span m=''1870670''>though.</span>
  <span m=''1871080''>I should correct</span> <span m=''1871490''>the notes,</span>
  <span m=''1872460''>double</span> <span m=''1872680''>check,</span> <span m=''1873210''>something.</span>
  </p><p><span m=''1875362''>It''s</span> <span m=''1875800''>really</span> <span
  m=''1876090''>you''re</span> <span m=''1876290''>just</span> <span m=''1876490''>adding</span>
  <span m=''1876800''>up</span> <span m=''1876910''>twos</span> <span m=''1877150''>and</span>
  <span m=''1877260''>threes</span> <span m=''1877790''>a</span> <span m=''1877910''>lot,</span>
  <span m=''1878730''>and</span> <span m=''1878950''>fours,</span> <span m=''1879450''>and</span>
  <span m=''1879600''>things</span> <span m=''1879860''>like</span> <span m=''1879970''>that</span>
  <span m=''1880170''>a</span> <span m=''1880200''>whole</span> <span m=''1880530''>bunch</span>
  <span m=''1880750''>of</span> <span m=''1880830''>times.</span> <span m=''1881310''>And</span>
  <span m=''1881490''>then</span> <span m=''1881650''>just</span> <span m=''1881890''>luckily</span>
  <span m=''1882240''>it</span> <span m=''1882590''>came</span> <span m=''1882770''>out</span>
  <span m=''1882880''>to</span> <span m=''1883010''>a</span> <span m=''1883040''>nice</span>
  <span m=''1883290''>number.</span> <span m=''1884090''>As</span> <span m=''1884160''>far</span>
  <span m=''1884330''>as</span> <span m=''1884430''>I</span> <span m=''1884490''>know,</span>
  <span m=''1884840''>not</span> <span m=''1885020''>intentional.</span> </p><p><span
  m=''1886940''>There</span> <span m=''1887060''>are</span> <span m=''1887100''>few</span>
  <span m=''1887290''>authors</span> <span m=''1887630''>though,</span> <span m=''1887770''>so</span>
  <span m=''1887910''>I</span> <span m=''1888000''>don''t</span> <span m=''1888140''>know.</span>
  <span m=''1888810''>Maybe</span> <span m=''1889060''>one</span> <span m=''1889230''>of</span>
  <span m=''1889290''>them</span> <span m=''1889410''>increased</span> <span m=''1889770''>a
  bound</span> <span m=''1890150''>to</span> <span m=''1890260''>make</span> <span
  m=''1890470''>it</span> <span m=''1891550''>a</span> <span m=''1891640''>little</span>
  <span m=''1891870''>cooler</span> <span m=''1892230''>number</span> <span m=''1892540''>in</span>
  <span m=''1892620''>the</span> <span m=''1892710''>end.</span> <span m=''1895480''>Good.</span>
  </p><p><span m=''1897860''>So</span> <span m=''1898020''>that''s</span> <span m=''1898300''>pseudo-polynomial</span>
  <span m=''1898980''>number of</span> <span m=''1899250''>steps.</span> <span m=''1899600''>It''s</span>
  <span m=''1899730''>interesting,</span> <span m=''1900300''>each</span> <span m=''1900510''>of</span>
  <span m=''1900590''>the</span> <span m=''1900650''>steps</span> <span m=''1901000''>is</span>
  <span m=''1901110''>actually</span> <span m=''1901450''>a very</span> <span m=''1901670''>nice</span>
  <span m=''1901950''>motion.</span> <span m=''1902240''>It</span> <span m=''1902340''>just</span>
  <span m=''1902560''>moves</span> <span m=''1902800''>along</span> <span m=''1903020''>a</span>
  <span m=''1903070''>straight</span> <span m=''1903340''>line</span> <span m=''1904080''>in
  the</span> <span m=''1904210''>configuration</span> <span m=''1904750''>space.</span>
  </p><p><span m=''1905930''>I would be</span> <span m=''1906080''>nice</span> <span
  m=''1906350''>to</span> <span m=''1906440''>know</span> <span m=''1906620''>whether</span>
  <span m=''1906950''>you</span> <span m=''1907130''>can</span> <span m=''1907280''>actually</span>
  <span m=''1907580''>achieve</span> <span m=''1907880''>a</span> <span m=''1907940''>polynomial</span>
  <span m=''1908570''>number</span> <span m=''1908820''>of</span> <span m=''1908880''>steps</span>
  <span m=''1909870''>independent</span> <span m=''1910370''>of</span> <span m=''1910500''>r.</span>
  <span m=''1910800''>I</span> <span m=''1910900''>think</span> <span m=''1911110''>the</span>
  <span m=''1911210''>answer</span> <span m=''1911470''>is</span> <span m=''1911580''>no,</span>
  <span m=''1911900''>it''s</span> <span m=''1912040''>not</span> <span m=''1912220''>possible</span>
  <span m=''1913300''>for</span> <span m=''1913480''>some</span> <span m=''1913710''>linkages</span>
  <span m=''1914260''>that</span> <span m=''1914360''>are</span> <span m=''1914450''>really</span>
  <span m=''1914680''>tight.</span> <span m=''1915780''>I</span> <span m=''1915920''>think</span>
  <span m=''1916090''>you</span> <span m=''1916170''>need</span> <span m=''1916410''>a
  dependence,</span> <span m=''1916715''>a</span> <span m=''1917020''>polynomial</span>
  <span m=''1917490''>dependence,</span> <span m=''1917920''>on</span> <span m=''1918020''>r--</span>
  <span m=''1918470''>at least a</span> <span m=''1918920''>linear</span> <span m=''1919200''>dependence</span>
  <span m=''1919620''>on</span> <span m=''1919720''>r.</span> <span m=''1920075''>But
  I</span> <span m=''1920430''>don''t</span> <span m=''1920550''>know</span> <span
  m=''1920630''>how</span> <span m=''1920740''>to</span> <span m=''1920810''>prove</span>
  <span m=''1921020''>that.</span> <span m=''1921550''>It''s a</span> <span m=''1921820''>nice</span>
  <span m=''1922080''>open</span> <span m=''1922290''>problem.</span> </p><p><span
  m=''1923830''>Another</span> <span m=''1924190''>fun</span> <span m=''1924420''>problem,</span>
  <span m=''1924750''>these</span> <span m=''1925160''>examples</span> <span m=''1925840''>with</span>
  <span m=''1925990''>polygons</span> <span m=''1927210''>end</span> <span m=''1927430''>up</span>
  <span m=''1927620''>with</span> <span m=''1928900''>a</span> <span m=''1929020''>particular</span>
  <span m=''1929520''>convex</span> <span m=''1929940''>shape</span> <span m=''1930710''>in</span>
  <span m=''1930840''>the</span> <span m=''1930990''>end.</span> <span m=''1932210''>Is</span>
  <span m=''1932380''>that</span> <span m=''1932550''>shape</span> <span m=''1932790''>unique?</span>
  <span m=''1934130''>If I</span> <span m=''1934230''>gave</span> <span m=''1934480''>you</span>
  <span m=''1934580''>the</span> <span m=''1934670''>sequence</span> <span m=''1935000''>of</span>
  <span m=''1935070''>edge</span> <span m=''1935250''>lengths</span> <span m=''1935490''>here,</span>
  <span m=''1935650''>they''re</span> <span m=''1935830''>all</span> <span m=''1936560''>1,</span>
  <span m=''1937200''>or they''re</span> <span m=''1937590''>almost</span> <span m=''1937890''>1.</span>
  <span m=''1938190''>Not</span> <span m=''1938510''>quite</span> <span m=''1938600''>the</span>
  <span m=''1938700''>same.</span> <span m=''1939200''>No, sorry,</span> <span m=''1939400''>they</span>
  <span m=''1939530''>get</span> <span m=''1939720''>tinier</span> <span m=''1940590''>as
  you</span> <span m=''1940710''>go</span> <span m=''1940830''>to</span> <span m=''1940910''>the</span>
  <span m=''1940980''>center.</span> </p><p><span m=''1941320''>But</span> <span m=''1941500''>for</span>
  <span m=''1941590''>that</span> <span m=''1941810''>sequence</span> <span m=''1942120''>of</span>
  <span m=''1942220''>edge</span> <span m=''1942370''>lengths,</span> <span m=''1942550''>is</span>
  <span m=''1942680''>there a</span> <span m=''1942840''>unique</span> <span m=''1943310''>minimum</span>
  <span m=''1943650''>energy</span> <span m=''1944390''>configuration?</span> <span
  m=''1945390''>I</span> <span m=''1945450''>think</span> <span m=''1945650''>so.</span>
  <span m=''1946430''>But</span> <span m=''1946860''>I</span> <span m=''1946990''>don''t</span>
  <span m=''1947130''>know.</span> </p><p><span m=''1949390''>We</span> <span m=''1949530''>know</span>
  <span m=''1949820''>that this</span> <span m=''1950100''>method</span> <span m=''1950340''>will</span>
  <span m=''1950460''>get</span> <span m=''1950600''>to</span> <span m=''1950670''>convex,</span>
  <span m=''1951640''>because</span> <span m=''1952470''>only</span> <span m=''1952730''>at</span>
  <span m=''1952800''>the</span> <span m=''1952870''>convex</span> <span m=''1953280''>configuration</span>
  <span m=''1953930''>do</span> <span m=''1954020''>you</span> <span m=''1954100''>no</span>
  <span m=''1954280''>longer</span> <span m=''1954540''>have</span> <span m=''1954700''>an</span>
  <span m=''1954770''>expansive</span> <span m=''1955150''>motion</span> <span m=''1955640''>and
  no</span> <span m=''1955770''>longer</span> <span m=''1956060''>have</span> <span
  m=''1956320''>a</span> <span m=''1956370''>decreasing</span> <span m=''1957530''>energy</span>
  <span m=''1957860''>motion,</span> <span m=''1958260''>maybe.</span> <span m=''1960400''>Cool.</span>
  </p><p><span m=''1960820''>Those</span> <span m=''1961050''>are</span> <span m=''1961140''>the
  three</span> <span m=''1961410''>algorithms.</span> <span m=''1962150''>Any</span>
  <span m=''1962360''>questions</span> <span m=''1962740''>about</span> <span m=''1963000''>them?</span>
  </p><p><span m=''1969230''>Before</span> <span m=''1969490''>we</span> <span m=''1969570''>go</span>
  <span m=''1969680''>to</span> <span m=''1969770''>trees,</span> <span m=''1970580''>again,</span>
  <span m=''1971700''>tell</span> <span m=''1971880''>you</span> <span m=''1972080''>a</span>
  <span m=''1972170''>cool</span> <span m=''1972440''>application</span> <span m=''1972715''>to</span>
  <span m=''1972990''>origami,</span> <span m=''1981540''>which</span> <span m=''1981810''>is</span>
  <span m=''1982000''>to</span> <span m=''1982150''>rigid</span> <span m=''1982460''>origami.</span>
  <span m=''1987040''>Remember,</span> <span m=''1987420''>rigid</span> <span m=''1987810''>origami,</span>
  <span m=''1988940''>we''re</span> <span m=''1989060''>not</span> <span m=''1989270''>allowed</span>
  <span m=''1989530''>to</span> <span m=''1989610''>add</span> <span m=''1989790''>any</span>
  <span m=''1989950''>creases.</span> <span m=''1990900''>And</span> <span m=''1991040''>all</span>
  <span m=''1991260''>of</span> <span m=''1991440''>the</span> <span m=''1991550''>faces</span>
  <span m=''1992170''>between</span> <span m=''1992560''>creases</span> <span m=''1993060''>have</span>
  <span m=''1993300''>to</span> <span m=''1993430''>stay</span> <span m=''1994290''>flat.</span>
  </p><p><span m=''1995370''>They''re</span> <span m=''1995480''>like</span> <span
  m=''1995700''>made</span> <span m=''1995900''>of--</span> <span m=''1996730''>imagine</span>
  <span m=''1997050''>you</span> <span m=''1997130''>have</span> <span m=''1998040''>pieces</span>
  <span m=''1998350''>of</span> <span m=''1998410''>metal</span> <span m=''1999050''>representing
  the</span> <span m=''1999520''>faces.</span> <span m=''1999920''>You</span> <span
  m=''2000050''>have</span> <span m=''2000520''>piano</span> <span m=''2000800''>hinges</span>
  <span m=''2001280''>making</span> <span m=''2001590''>the</span> <span m=''2001710''>edges.</span>
  <span m=''2002730''>That''s</span> <span m=''2002850''>rigid</span> <span m=''2003110''>origami.</span>
  </p><p><span m=''2004010''>That''s</span> <span m=''2004240''>kind</span> <span
  m=''2004360''>of</span> <span m=''2004480''>like</span> <span m=''2004660''>a</span>
  <span m=''2004720''>linkage.</span> <span m=''2005270''>In</span> <span m=''2005410''>particular,</span>
  <span m=''2006440''>when</span> <span m=''2006570''>you</span> <span m=''2006630''>have</span>
  <span m=''2006830''>a</span> <span m=''2006890''>single</span> <span m=''2007190''>vertex</span>
  <span m=''2007600''>origami--</span> <span m=''2011480''>say</span> <span m=''2011750''>that''s</span>
  <span m=''2012060''>five</span> <span m=''2012130''>foldable,</span> <span m=''2012410''>I
  don''t</span> <span m=''2012730''>know.</span> <span m=''2015060''>And</span> <span
  m=''2015330''>if</span> <span m=''2015510''>you</span> <span m=''2015630''>say</span>
  <span m=''2015910''>each</span> <span m=''2016080''>of</span> <span m=''2016160''>these</span>
  <span m=''2016500''>wedges</span> <span m=''2017020''>is</span> <span m=''2017210''>a</span>
  <span m=''2017300''>rigid</span> <span m=''2018040''>piece</span> <span m=''2018270''>of</span>
  <span m=''2018350''>metal,</span> <span m=''2020960''>well</span> <span m=''2021220''>we</span>
  <span m=''2021350''>already</span> <span m=''2021560''>know</span> <span m=''2022340''>this</span>
  <span m=''2022730''>kind of</span> <span m=''2022810''>set</span> <span m=''2023040''>up</span>
  <span m=''2023240''>can</span> <span m=''2023410''>be</span> <span m=''2023680''>modeled</span>
  <span m=''2024110''>by</span> <span m=''2024330''>its</span> <span m=''2024510''>boundary.</span>
  <span m=''2026380''>Ignore</span> <span m=''2026700''>the</span> <span m=''2026820''>interior.</span>
  <span m=''2027980''>Just</span> <span m=''2028190''>think</span> <span m=''2028350''>of</span>
  <span m=''2028450''>there</span> <span m=''2028590''>being</span> <span m=''2028890''>hinges</span>
  <span m=''2030790''>of</span> <span m=''2030900''>this</span> <span m=''2031070''>one</span>
  <span m=''2031260''>dimensional</span> <span m=''2032120''>structure</span> <span
  m=''2033690''>like</span> <span m=''2033850''>that.</span> </p><p><span m=''2036040''>So</span>
  <span m=''2036190''>that</span> <span m=''2036670''>looks</span> <span m=''2036860''>a</span>
  <span m=''2036910''>lot</span> <span m=''2037120''>like</span> <span m=''2037300''>a</span>
  <span m=''2037360''>linkage.</span> <span m=''2039110''>These</span> <span m=''2039380''>have</span>
  <span m=''2039530''>to</span> <span m=''2039640''>stay</span> <span m=''2039880''>rigid.</span>
  <span m=''2041170''>They''re</span> <span m=''2041250''>not</span> <span m=''2041490''>straight</span>
  <span m=''2041830''>lines.</span> <span m=''2042400''>It''s</span> <span m=''2042510''>a</span>
  <span m=''2042560''>little</span> <span m=''2042740''>different.</span> <span m=''2043780''>It''s</span>
  <span m=''2043910''>almost</span> <span m=''2044290''>the</span> <span m=''2044350''>same.</span>
  </p><p><span m=''2045400''>If</span> <span m=''2045550''>you</span> <span m=''2045670''>think</span>
  <span m=''2045880''>about</span> <span m=''2046130''>how</span> <span m=''2046290''>you''re</span>
  <span m=''2046460''>allowed</span> <span m=''2046680''>to</span> <span m=''2046750''>fold</span>
  <span m=''2047050''>these</span> <span m=''2047250''>things--</span> <span m=''2048650''>really</span>
  <span m=''2048960''>you  should</span> <span m=''2049120''>think</span> <span m=''2049260''>about</span>
  <span m=''2049460''>it</span> <span m=''2049520''>here,</span> <span m=''2049810''>I</span>
  <span m=''2049840''>guess--</span> <span m=''2050650''>what</span> <span m=''2050800''>happens,</span>
  <span m=''2052040''>by a</span> <span m=''2052219''>continuous</span> <span m=''2052750''>motion</span>
  <span m=''2054150''>what</span> <span m=''2054310''>happens</span> <span m=''2054670''>is</span>
  <span m=''2054800''>that</span> <span m=''2054909''>you''re</span> <span m=''2055520''>living</span>
  <span m=''2055870''>on</span> <span m=''2055969''>a</span> <span m=''2056020''>sphere.</span>
  <span m=''2057600''>So you</span> <span m=''2057800''>start</span> <span m=''2058150''>out</span>
  <span m=''2059810''>on</span> <span m=''2060020''>the</span> <span m=''2060130''>equator</span>
  <span m=''2060590''>of</span> <span m=''2060659''>the</span> <span m=''2060750''>sphere.</span>
  <span m=''2062310''>This</span> <span m=''2062530''>thing,</span> <span m=''2062810''>just</span>
  <span m=''2063010''>plop</span> <span m=''2063250''>it</span> <span m=''2063320''>down</span>
  <span m=''2063590''>the</span> <span m=''2063679''>equator.</span> <span m=''2064040''>The</span>
  <span m=''2064139''>boundary</span> <span m=''2064639''>lies</span> <span m=''2064909''>on</span>
  <span m=''2065020''>the</span> <span m=''2065530''>boundary of</span> <span m=''2065840''>the</span>
  <span m=''2065920''>sphere.</span> <span m=''2066139''>The</span> <span m=''2066414''>interior
  of the</span> <span m=''2066690''>paper is</span> <span m=''2067120''>inside</span>
  <span m=''2067550''>the</span> <span m=''2067630''>sphere,</span> <span m=''2068659''>right</span>
  <span m=''2068880''>along</span> <span m=''2069230''>the</span> <span m=''2070010''>flat</span>
  <span m=''2070300''>part</span> <span m=''2070520''>there.</span> </p><p><span m=''2071659''>As</span>
  <span m=''2071840''>you</span> <span m=''2071980''>fold,</span> <span m=''2072969''>these</span>
  <span m=''2073210''>points</span> <span m=''2073790''>will</span> <span m=''2074100''>stay</span>
  <span m=''2074620''>on</span> <span m=''2074840''>the</span> <span m=''2074920''>sphere.</span>
  <span m=''2075909''>And</span> <span m=''2076199''>these</span> <span m=''2076389''>edge</span>
  <span m=''2076620''>links</span> <span m=''2076940''>will</span> <span m=''2077230''>be</span>
  <span m=''2077389''>preserved,</span> <span m=''2078590''>their</span> <span m=''2078810''>arcs</span>
  <span m=''2079310''>on</span> <span m=''2079489''>the</span> <span m=''2079570''>spheres.</span>
  <span m=''2079940''>There will</span> <span m=''2080040''>be</span> <span m=''2080179''>great</span>
  <span m=''2080429''>circular</span> <span m=''2080780''>arcs</span> <span m=''2081040''>at</span>
  <span m=''2081100''>all</span> <span m=''2081260''>times.</span> </p><p><span m=''2082580''>So</span>
  <span m=''2082739''>folding</span> <span m=''2083270''>this</span> <span m=''2083510''>thing</span>
  <span m=''2084030''>in</span> <span m=''2084170''>three</span> <span m=''2084370''>space</span>
  <span m=''2084710''>is</span> <span m=''2084830''>really</span> <span m=''2085060''>equivalent</span>
  <span m=''2085540''>to</span> <span m=''2085620''>folding</span> <span m=''2087050''>this</span>
  <span m=''2087429''>linkage</span> <span m=''2088250''>on</span> <span m=''2088460''>the</span>
  <span m=''2088540''>sphere.</span> <span m=''2090150''>And</span> <span m=''2090320''>that</span>
  <span m=''2090500''>looks</span> <span m=''2090710''>an</span> <span m=''2090790''>awful</span>
  <span m=''2091030''>lot</span> <span m=''2091210''>like</span> <span m=''2091389''>a</span>
  <span m=''2091469''>polygon</span> <span m=''2092150''>on</span> <span m=''2092250''>a</span>
  <span m=''2092330''>sphere.</span> <span m=''2092650''>What</span> <span m=''2092810''>we</span>
  <span m=''2092929''>really</span> <span m=''2093179''>want</span> <span m=''2093739''>is</span>
  <span m=''2093969''>a</span> <span m=''2094050''>spherical</span> <span m=''2095000''>Carpenter''s</span>
  <span m=''2095449''>Rule</span> <span m=''2095659''>Theorem.</span> </p><p><span
  m=''2102980''>And</span> <span m=''2103190''>there is.</span> <span m=''2105430''>This
  is</span> <span m=''2105880''>by</span> <span m=''2106190''>Streinu</span> <span
  m=''2106560''>and</span> <span m=''2106750''>Whiteley.</span> <span m=''2110940''>So</span>
  <span m=''2112580''>if you</span> <span m=''2112660''>have</span> <span m=''2112830''>a</span>
  <span m=''2112890''>closed</span> <span m=''2113260''>chain,</span> <span m=''2113600''>a</span>
  <span m=''2113660''>polygon,</span> <span m=''2116102''>of</span> <span m=''2116510''>total</span>
  <span m=''2116870''>length</span> <span m=''2122370''>at</span> <span m=''2122560''>most</span>
  <span m=''2122890''>2</span> <span m=''2123070''>pi</span> <span m=''2124500''>on</span>
  <span m=''2124760''>a</span> <span m=''2124810''>unit</span> <span m=''2125150''>sphere</span>
  <span m=''2131660''>then</span> <span m=''2132140''>you</span> <span m=''2132290''>have</span>
  <span m=''2133320''>a</span> <span m=''2133730''>connected</span> <span m=''2134150''>configuration</span>
  <span m=''2134800''>space.</span> <span m=''2141320''>So</span> <span m=''2141470''>in</span>
  <span m=''2141540''>the</span> <span m=''2141620''>plane,</span> <span m=''2143800''>closed</span>
  <span m=''2144030''>chain</span> <span m=''2144300''>always</span> <span m=''2144590''>had</span>
  <span m=''2144740''>a</span> <span m=''2144800''>connected</span> <span m=''2145120''>configuration</span>
  <span m=''2145660''>space.</span> <span m=''2145920''>On</span> <span m=''2146010''>the</span>
  <span m=''2146080''>sphere</span> <span m=''2147120''>you</span> <span m=''2147300''>need</span>
  <span m=''2147520''>that</span> <span m=''2147600''>the</span> <span m=''2147690''>chain</span>
  <span m=''2147920''>is</span> <span m=''2148030''>not</span> <span m=''2148230''>too</span>
  <span m=''2148390''>long,</span> <span m=''2150190''>because</span> <span m=''2150390''>there''s</span>
  <span m=''2150640''>only</span> <span m=''2151030''>sort</span> <span m=''2151210''>of</span>
  <span m=''2151290''>a</span> <span m=''2151350''>bounded</span> <span m=''2151710''>amount</span>
  <span m=''2151910''>of</span> <span m=''2152000''>room</span> <span m=''2152210''>on</span>
  <span m=''2152330''>the</span> <span m=''2152410''>sphere.</span> </p><p><span m=''2153310''>The</span>
  <span m=''2153430''>equator</span> <span m=''2155100''>has</span> <span m=''2155470''>total</span>
  <span m=''2155790''>length</span> <span m=''2157660''>2</span> <span m=''2157915''>pi,</span>
  <span m=''2159050''>perimeter</span> <span m=''2160270''>of</span> <span m=''2161180''>the</span>
  <span m=''2161270''>equator.</span> <span m=''2163720''>For</span> <span m=''2163930''>unit</span>
  <span m=''2164330''>sphere</span> <span m=''2164800''>it''s</span> <span m=''2164940''>2</span>
  <span m=''2165050''>pi.</span> <span m=''2166230''>So</span> <span m=''2166370''>we''re</span>
  <span m=''2166490''>just</span> <span m=''2166680''>canonically</span> <span m=''2167090''>making</span>
  <span m=''2167410''>it a</span> <span m=''2167520''>unit</span> <span m=''2167800''>sphere.</span>
  <span m=''2168540''>And</span> <span m=''2168870''>2</span> <span m=''2169040''>pi</span>
  <span m=''2169290''>really</span> <span m=''2169540''>corresponds</span> <span m=''2170040''>to</span>
  <span m=''2170140''>this</span> <span m=''2170310''>situation,</span> <span m=''2170940''>which</span>
  <span m=''2171230''>is</span> <span m=''2171530''>360</span> <span m=''2172100''>degrees.</span>
  <span m=''2172520''>That''s</span> <span m=''2172740''>how</span> <span m=''2172820''>much</span>
  <span m=''2173360''>total</span> <span m=''2173600''>length</span> <span m=''2173820''>we</span>
  <span m=''2173920''>have.</span> <span m=''2174190''>So</span> <span m=''2174360''>it</span>
  <span m=''2174430''>just</span> <span m=''2174600''>fits</span> <span m=''2174820''>in</span>
  <span m=''2174860''>the</span> <span m=''2174920''>equator,</span> <span m=''2175670''>life</span>
  <span m=''2175890''>is</span> <span m=''2176010''>good.</span> </p><p><span m=''2177000''>The</span>
  <span m=''2177090''>reason</span> <span m=''2177370''>you</span> <span m=''2177490''>want
  it</span> <span m=''2177710''>to</span> <span m=''2177780''>have</span> <span m=''2177950''>length</span>
  <span m=''2178170''>at</span> <span m=''2178270''>most</span> <span m=''2178580''>2</span>
  <span m=''2178700''>pi</span> <span m=''2179140''>is</span> <span m=''2179280''>because</span>
  <span m=''2179600''>then</span> <span m=''2179810''>you</span> <span m=''2180080''>actually</span>
  <span m=''2180530''>do</span> <span m=''2180700''>have</span> <span m=''2180890''>a</span>
  <span m=''2180970''>convex</span> <span m=''2181460''>configuration.</span> <span
  m=''2182880''>In</span> <span m=''2183000''>the</span> <span m=''2183080''>case</span>
  <span m=''2183290''>of</span> <span m=''2183360''>2</span> <span m=''2183500''>pi,</span>
  <span m=''2183780''>it lies</span> <span m=''2184040''>along</span> <span m=''2184250''>the</span>
  <span m=''2184340''>equator.</span> <span m=''2185040''>If</span> <span m=''2185160''>it''s</span>
  <span m=''2185300''>smaller</span> <span m=''2185610''>than</span> <span m=''2185780''>2</span>
  <span m=''2185920''>pi</span> <span m=''2186200''>it''ll</span> <span m=''2186420''>be</span>
  <span m=''2186650''>like</span> <span m=''2186980''>some</span> <span m=''2187330''>smaller</span>
  <span m=''2187750''>portion.</span> <span m=''2188980''>This</span> <span m=''2189150''>would</span>
  <span m=''2189230''>be</span> <span m=''2189380''>less</span> <span m=''2189670''>than</span>
  <span m=''2189820''>2</span> <span m=''2189950''>pi</span> <span m=''2191450''>on</span>
  <span m=''2191610''>the</span> <span m=''2191790''>sphere.</span> </p><p><span m=''2195600''>If</span>
  <span m=''2195760''>it''s</span> <span m=''2196300''>greater</span> <span m=''2196690''>than</span>
  <span m=''2196860''>2</span> <span m=''2197010''>pi,</span> <span m=''2197370''>you</span>
  <span m=''2197560''>can''t</span> <span m=''2197880''>draw it</span> <span m=''2198280''>convexly</span>
  <span m=''2199140''>on</span> <span m=''2199220''>the</span> <span m=''2199290''>sphere.</span>
  <span m=''2199500''>You</span> <span m=''2199630''>can</span> <span m=''2199790''>draw</span>
  <span m=''2200010''>something.</span> <span m=''2200480''>Like</span> <span m=''2200690''>I</span>
  <span m=''2200750''>could</span> <span m=''2200910''>draw</span> <span m=''2201720''>something</span>
  <span m=''2202020''>like</span> <span m=''2202190''>this,</span> <span m=''2202410''>that''ll</span>
  <span m=''2202550''>have</span> <span m=''2202760''>really</span> <span m=''2203010''>long</span>
  <span m=''2203270''>length</span> <span m=''2205100''>on</span> <span m=''2205240''>the</span>
  <span m=''2205310''>sphere.</span> <span m=''2206090''>But</span> <span m=''2206270''>there
  will</span> <span m=''2206440''>be</span> <span m=''2206570''>no</span> <span m=''2207170''>way</span>
  <span m=''2207350''>to</span> <span m=''2207460''>convexify</span> <span m=''2207840''>it.</span>
  <span m=''2208160''>You</span> <span m=''2208250''>get</span> <span m=''2208580''>stuck</span>
  <span m=''2209190''>at</span> <span m=''2209300''>some</span> <span m=''2209440''>point.</span>
  </p><p><span m=''2210480''>And as</span> <span m=''2210690''>long</span> <span m=''2210930''>as</span>
  <span m=''2211000''>you</span> <span m=''2211100''>don''t</span> <span m=''2211260''>have</span>
  <span m=''2211410''>that</span> <span m=''2211610''>situation,</span> <span m=''2212670''>you</span>
  <span m=''2212830''>can</span> <span m=''2212960''>take</span> <span m=''2213220''>this--</span>
  <span m=''2214510''>what</span> <span m=''2214770''>this</span> <span m=''2214950''>actually</span>
  <span m=''2215210''>implies</span> <span m=''2215920''>is</span> <span m=''2216040''>that</span>
  <span m=''2216160''>your</span> <span m=''2216300''>polygon</span> <span m=''2216770''>at</span>
  <span m=''2216870''>all</span> <span m=''2217030''>times</span> <span m=''2217300''>will</span>
  <span m=''2217410''>lie in</span> <span m=''2217680''>a</span> <span m=''2217700''>hemisphere.</span>
  <span m=''2218940''>You</span> <span m=''2219030''>take</span> <span m=''2219210''>that</span>
  <span m=''2219330''>hemisphere</span> <span m=''2219950''>and</span> <span m=''2220100''>you</span>
  <span m=''2220180''>sort</span> <span m=''2220380''>of</span> <span m=''2220510''>unroll</span>
  <span m=''2221120''>it,</span> <span m=''2221400''>you</span> <span m=''2221550''>splay
  it</span> <span m=''2222010''>out,</span> <span m=''2222260''>you</span> <span m=''2222370''>project</span>
  <span m=''2222665''>it</span> <span m=''2222960''>to</span> <span m=''2223050''>the</span>
  <span m=''2223140''>plane.</span> <span m=''2224010''>You</span> <span m=''2224090''>apply</span>
  <span m=''2224300''>the</span> <span m=''2224420''>planar</span> <span m=''2224730''>Carpenter''s</span>
  <span m=''2225180''>Rule</span> <span m=''2225360''>Theorem.</span> </p><p><span
  m=''2226630''>You</span> <span m=''2227010''>apply</span> <span m=''2227330''>the</span>
  <span m=''2227430''>fact</span> <span m=''2227830''>that</span> <span m=''2228070''>unrolling</span>
  <span m=''2229200''>operation,</span> <span m=''2229770''>or</span> <span m=''2229830''>that</span>
  <span m=''2230060''>projection</span> <span m=''2230750''>if</span> <span m=''2230870''>you</span>
  <span m=''2231010''>will--</span> <span m=''2231890''>I</span> <span m=''2231970''>think</span>
  <span m=''2232150''>it''s</span> <span m=''2232290''>like</span> <span m=''2232440''>projection</span>
  <span m=''2233200''>from</span> <span m=''2236770''>some</span> <span m=''2236980''>point</span>
  <span m=''2237200''>here</span> <span m=''2237590''>out</span> <span m=''2238010''>to
  the</span> <span m=''2238100''>plane--</span> <span m=''2240010''>that</span> <span
  m=''2240200''>projection</span> <span m=''2241090''>preserves</span> <span m=''2241730''>infinitesimal</span>
  <span m=''2242450''>flexibility</span> <span m=''2243150''>of</span> <span m=''2245300''>tensegrities.</span>
  <span m=''2246520''>So</span> <span m=''2246730''>it''ll</span> <span m=''2246880''>still</span>
  <span m=''2247250''>have</span> <span m=''2247400''>the</span> <span m=''2247460''>expensive</span>
  <span m=''2247900''>motion</span> <span m=''2248470''>in</span> <span m=''2248540''>the</span>
  <span m=''2248620''>plane.</span> <span m=''2249630''>And</span> <span m=''2249840''>then</span>
  <span m=''2249960''>you</span> <span m=''2250050''>could</span> <span m=''2250200''>turn</span>
  <span m=''2250490''>in</span> <span m=''2251660''>to an</span> <span m=''2251810''>expansive</span>
  <span m=''2252230''>motion</span> <span m=''2252630''>on</span> <span m=''2252730''>the</span>
  <span m=''2252810''>sphere.</span> <span m=''2253590''>And</span> <span m=''2253670''>eventually</span>
  <span m=''2254070''>you''ll</span> <span m=''2254210''>get</span> <span m=''2254300''>a</span>
  <span m=''2254350''>convex</span> <span m=''2255050''>polygon.</span> </p><p><span
  m=''2256620''>So</span> <span m=''2256770''>that''s</span> <span m=''2256930''>sort</span>
  <span m=''2257050''>of</span> <span m=''2257090''>how</span> <span m=''2257280''>this</span>
  <span m=''2257450''>is</span> <span m=''2257560''>proved.</span> <span m=''2258850''>Then</span>
  <span m=''2259300''>you</span> <span m=''2259430''>can</span> <span m=''2259560''>apply</span>
  <span m=''2259890''>it</span> <span m=''2260070''>to</span> <span m=''2260330''>rigid</span>
  <span m=''2260610''>origami,</span> <span m=''2261020''>and</span> <span m=''2261080''>say
  for</span> <span m=''2261410''>single</span> <span m=''2261720''>vertex</span> <span
  m=''2262350''>origami,</span> <span m=''2262870''>it''s</span> <span m=''2263130''>always</span>
  <span m=''2263530''>rigidly</span> <span m=''2263940''>foldable.</span> <span m=''2264920''>Any</span>
  <span m=''2265180''>state</span> <span m=''2265560''>you</span> <span m=''2265680''>want</span>
  <span m=''2265850''>to</span> <span m=''2265910''>reach</span> <span m=''2266570''>can</span>
  <span m=''2266790''>be</span> <span m=''2266950''>reached</span> <span m=''2268130''>by</span>
  <span m=''2268370''>continuous</span> <span m=''2268870''>motion,</span> <span m=''2269700''>without</span>
  <span m=''2270130''>bending</span> <span m=''2270490''>any</span> <span m=''2270640''>of
  the</span> <span m=''2270750''>faces.</span> <span m=''2273890''>So</span> <span
  m=''2274260''>a</span> <span m=''2274320''>fun</span> <span m=''2274620''>little</span>
  <span m=''2274860''>application.</span> </p><p><span m=''2281320''>And</span> <span
  m=''2281710''>one</span> <span m=''2281960''>of</span> <span m=''2282030''>the</span>
  <span m=''2282110''>few</span> <span m=''2282300''>things</span> <span m=''2282530''>we</span>
  <span m=''2282610''>know</span> <span m=''2282790''>about</span> <span m=''2282940''>rigid</span>
  <span m=''2283230''>origami,</span> <span m=''2284250''>for</span> <span m=''2285550''>multiple</span>
  <span m=''2285880''>vertices</span> <span m=''2286350''>it</span> <span m=''2286410''>gets</span>
  <span m=''2286580''>a</span> <span m=''2286620''>lot</span> <span m=''2286780''>harder.</span>
  <span m=''2288170''>Not</span> <span m=''2288370''>always</span> <span m=''2288540''>possible,</span>
  <span m=''2289880''>and</span> <span m=''2291760''>we</span> <span m=''2291790''>don''t</span>
  <span m=''2291920''>have</span> <span m=''2292060''>a</span> <span m=''2292100''>nice</span>
  <span m=''2292320''>characterization.</span> </p><p><span m=''2304480''>So</span>
  <span m=''2305510''>finally,</span> <span m=''2306040''>let''s</span> <span m=''2306290''>move</span>
  <span m=''2306510''>onto</span> <span m=''2307800''>locked</span> <span m=''2308240''>trees</span>
  <span m=''2309220''>in</span> <span m=''2309450''>the</span> <span m=''2309550''>plane.</span>
  <span m=''2314910''>So</span> <span m=''2315120''>these</span> <span m=''2315380''>are</span>
  <span m=''2315690''>sort</span> <span m=''2315900''>of</span> <span m=''2315990''>the</span>
  <span m=''2316080''>classic</span> <span m=''2316540''>examples.</span> <span m=''2318100''>The</span>
  <span m=''2318240''>top</span> <span m=''2318660''>two</span> <span m=''2319760''>were</span>
  <span m=''2319980''>in a</span> <span m=''2320340''>1998</span> <span m=''2321150''>paper.</span>
  <span m=''2321520''>This</span> <span m=''2321680''>was</span> <span m=''2321790''>when</span>
  <span m=''2321910''>I</span> <span m=''2321970''>started</span> <span m=''2323030''>working</span>
  <span m=''2323530''>on</span> <span m=''2324110''>folding</span> <span m=''2324540''>stuff,</span>
  <span m=''2325820''>very</span> <span m=''2326010''>beginning.</span> <span m=''2327366''>A</span>
  <span m=''2327770''>whole</span> <span m=''2328010''>bunch</span> <span m=''2328260''>of</span>
  <span m=''2328320''>people</span> <span m=''2329520''>from</span> <span m=''2329850''>a</span>
  <span m=''2329900''>big</span> <span m=''2330090''>workshop.</span> </p><p><span
  m=''2332120''>First</span> <span m=''2332400''>example is</span> <span m=''2332850''>this</span>
  <span m=''2333020''>one.</span> <span m=''2333970''>And</span> <span m=''2334460''>it''s</span>
  <span m=''2334630''>a</span> <span m=''2334690''>bunch</span> <span m=''2335100''>of</span>
  <span m=''2336430''>sort</span> <span m=''2336700''>of</span> <span m=''2337130''>arms</span>
  <span m=''2337760''>tucked</span> <span m=''2338110''>into</span> <span m=''2338340''>their</span>
  <span m=''2338510''>armpits,</span> <span m=''2340080''>and</span> <span m=''2340550''>in</span>
  <span m=''2340750''>a</span> <span m=''2340840''>cyclic</span> <span m=''2341500''>way.</span>
  <span m=''2342550''>And</span> <span m=''2343200''>the</span> <span m=''2343520''>dotted</span>
  <span m=''2343930''>circles</span> <span m=''2344780''>mean</span> <span m=''2345210''>objects</span>
  <span m=''2346030''>in</span> <span m=''2346200''>this</span> <span m=''2346370''>mirror</span>
  <span m=''2346680''>are</span> <span m=''2346840''>closer</span> <span m=''2347160''>than</span>
  <span m=''2347330''>they</span> <span m=''2347450''>appear.</span> </p><p><span
  m=''2348530''>So</span> <span m=''2349070''>imagine</span> <span m=''2350590''>that</span>
  <span m=''2352080''>all</span> <span m=''2352340''>of</span> <span m=''2352480''>these</span>
  <span m=''2352710''>points</span> <span m=''2353270''>are</span> <span m=''2353730''>actually</span>
  <span m=''2354100''>really,</span> <span m=''2354660''>really</span> <span m=''2354910''>close</span>
  <span m=''2355430''>and</span> <span m=''2355590''>tight</span> <span m=''2355850''>in</span>
  <span m=''2355980''>here.</span> <span m=''2357050''>And</span> <span m=''2357220''>this</span>
  <span m=''2357390''>guy''s</span> <span m=''2357620''>actually</span> <span m=''2357880''>really</span>
  <span m=''2358230''>close</span> <span m=''2358750''>and</span> <span m=''2358870''>tight</span>
  <span m=''2359140''>against</span> <span m=''2359450''>this</span> <span m=''2359610''>edge.</span>
  <span m=''2361340''>So</span> <span m=''2361600''>I''ve</span> <span m=''2361690''>drawn</span>
  <span m=''2361920''>it</span> <span m=''2361990''>with</span> <span m=''2362080''>lots</span>
  <span m=''2362310''>of</span> <span m=''2362370''>slack</span> <span m=''2362670''>so</span>
  <span m=''2362770''>you</span> <span m=''2362870''>can</span> <span m=''2362990''>see</span>
  <span m=''2363300''>the</span> <span m=''2363390''>combinatorial</span> <span m=''2363950''>structure.</span>
  <span m=''2364350''>But</span> <span m=''2364500''>geometrically</span> <span m=''2365150''>it''s</span>
  <span m=''2365330''>much</span> <span m=''2365550''>tighter.</span> </p><p><span
  m=''2367070''>Then</span> <span m=''2367380''>the</span> <span m=''2367490''>intuition</span>
  <span m=''2367960''>is</span> <span m=''2368120''>that</span> <span m=''2368210''>you</span>
  <span m=''2368320''>can''t</span> <span m=''2368640''>get</span> <span m=''2368790''>any</span>
  <span m=''2369010''>of</span> <span m=''2369060''>these</span> <span m=''2369240''>arms</span>
  <span m=''2369730''>open</span> <span m=''2371100''>unless</span> <span m=''2371580''>you</span>
  <span m=''2371720''>could</span> <span m=''2371870''>somehow</span> <span m=''2372510''>expand</span>
  <span m=''2373890''>one</span> <span m=''2374070''>of</span> <span m=''2374130''>these</span>
  <span m=''2374300''>wedges.</span> <span m=''2375430''>It''s</span> <span m=''2375540''>like,</span>
  <span m=''2375660''>if</span> <span m=''2375750''>you</span> <span m=''2375870''>could</span>
  <span m=''2376010''>expand</span> <span m=''2376520''>this</span> <span m=''2376710''>angle</span>
  <span m=''2377990''>then</span> <span m=''2378160''>this</span> <span m=''2378320''>guy</span>
  <span m=''2378460''>would</span> <span m=''2378590''>have</span> <span m=''2378780''>room</span>
  <span m=''2378950''>to</span> <span m=''2379020''>come</span> <span m=''2379250''>out.</span>
  </p><p><span m=''2380200''>But</span> <span m=''2380340''>how</span> <span m=''2380510''>do</span>
  <span m=''2380600''>I</span> <span m=''2380670''>expand</span> <span m=''2380980''>that</span>
  <span m=''2381110''>angle?</span> <span m=''2381450''>Well I''d</span> <span m=''2381520''>have</span>
  <span m=''2381700''>to</span> <span m=''2381810''>compress</span> <span m=''2382420''>the</span>
  <span m=''2382560''>other</span> <span m=''2382780''>angles</span> <span m=''2383190''>because</span>
  <span m=''2383360''>of</span> <span m=''2383440''>the</span> <span m=''2383560''>cyclic</span>
  <span m=''2383980''>picture.</span> <span m=''2384470''>And</span> <span m=''2384960''>I</span>
  <span m=''2385090''>can''t,</span> <span m=''2385510''>if</span> <span m=''2385660''>I</span>
  <span m=''2385700''>look</span> <span m=''2385950''>at</span> <span m=''2386070''>some</span>
  <span m=''2386240''>other</span> <span m=''2386450''>angle</span> <span m=''2386650''>like</span>
  <span m=''2386820''>this</span> <span m=''2386970''>one,</span> <span m=''2387450''>I</span>
  <span m=''2387620''>can''t</span> <span m=''2387880''>compress</span> <span m=''2388330''>it</span>
  <span m=''2388490''>because</span> <span m=''2388900''>the</span> <span m=''2389050''>arm</span>
  <span m=''2389350''>is</span> <span m=''2389460''>in</span> <span m=''2389550''>the</span>
  <span m=''2389650''>way.</span> </p><p><span m=''2390830''>So</span> <span m=''2390970''>I</span>
  <span m=''2391030''>can''t</span> <span m=''2391580''>open</span> <span m=''2392630''>an</span>
  <span m=''2392700''>arm</span> <span m=''2393000''>until</span> <span m=''2393330''>I''ve</span>
  <span m=''2393540''>closed</span> <span m=''2394440''>some</span> <span m=''2394640''>other</span>
  <span m=''2394860''>arm.</span> <span m=''2395080''>And I</span> <span m=''2395150''>can''t</span>
  <span m=''2395370''>close</span> <span m=''2395610''>an</span> <span m=''2395700''>arm</span>
  <span m=''2395930''>before</span> <span m=''2396140''>I''ve</span> <span m=''2396230''>opened</span>
  <span m=''2396500''>it.</span> <span m=''2396920''>And</span> <span m=''2397080''>so</span>
  <span m=''2397190''>nothing</span> <span m=''2397470''>can</span> <span m=''2397600''>happen.</span>
  </p><p><span m=''2398090''>That''s</span> <span m=''2398370''>the</span> <span m=''2399340''>intuition</span>
  <span m=''2399900''>behind</span> <span m=''2400120''>the proof.</span> <span m=''2400390''>The</span>
  <span m=''2400660''>details</span> <span m=''2401060''>are</span> <span m=''2401100''>very</span>
  <span m=''2401280''>messy,</span> <span m=''2401665''>because you</span> <span m=''2402050''>have
  to</span> <span m=''2402140''>define</span> <span m=''2402600''>open</span> <span
  m=''2402870''>and</span> <span m=''2402970''>closed,</span> <span m=''2403470''>and</span>
  <span m=''2404640''>what</span> <span m=''2405210''>things</span> <span m=''2405540''>must</span>
  <span m=''2405840''>happen</span> <span m=''2406110''>before</span> <span m=''2406410''>what</span>
  <span m=''2406620''>things.</span> </p><p><span m=''2408140''>This</span> <span
  m=''2408410''>example</span> <span m=''2408810''>should</span> <span m=''2408970''>look</span>
  <span m=''2409120''>familiar</span> <span m=''2409550''>because</span> <span m=''2410030''>if</span>
  <span m=''2410230''>you</span> <span m=''2410490''>double</span> <span m=''2411010''>it,</span>
  <span m=''2411360''>if you replace</span> <span m=''2411720''>every</span> <span
  m=''2411940''>edge</span> <span m=''2412090''>with</span> <span m=''2412190''>two</span>
  <span m=''2412410''>edges,</span> <span m=''2413190''>we</span> <span m=''2413280''>get</span>
  <span m=''2413450''>one</span> <span m=''2413630''>of</span> <span m=''2413680''>the</span>
  <span m=''2413750''>examples</span> <span m=''2414220''>that</span> <span m=''2414300''>was</span>
  <span m=''2414430''>expanding</span> <span m=''2416300''>with</span> <span m=''2416450''>the</span>
  <span m=''2416530''>five-fold</span> <span m=''2416940''>symmetry.</span> <span
  m=''2419260''>So</span> <span m=''2420970''>people</span> <span m=''2421300''>have</span>
  <span m=''2421570''>sort</span> <span m=''2421800''>of</span> <span m=''2421890''>known</span>
  <span m=''2422190''>for</span> <span m=''2422330''>a</span> <span m=''2422400''>while,</span>
  <span m=''2422770''>and</span> <span m=''2422840''>then</span> <span m=''2422950''>we</span>
  <span m=''2423180''>finally</span> <span m=''2423600''>proved,</span> <span m=''2423970''>that</span>
  <span m=''2424060''>this</span> <span m=''2424280''>is</span> <span m=''2424420''>locked.</span>
  <span m=''2426550''>If</span> <span m=''2426780''>you</span> <span m=''2426880''>double</span>
  <span m=''2427240''>it,</span> <span m=''2427450''>people</span> <span m=''2427710''>thought</span>
  <span m=''2427920''>well</span> <span m=''2428050''>maybe</span> <span m=''2428320''>it''s</span>
  <span m=''2428440''>still</span> <span m=''2428670''>locked.</span> </p><p><span
  m=''2429250''>Turns</span> <span m=''2429520''>out</span> <span m=''2429690''>no,</span>
  <span m=''2429980''>because</span> <span m=''2430550''>the</span> <span m=''2430620''>center</span>
  <span m=''2430940''>vertex</span> <span m=''2431830''>can</span> <span m=''2432010''>expand</span>
  <span m=''2433870''>in</span> <span m=''2434050''>a</span> <span m=''2434120''>polygon,</span>
  <span m=''2434730''>but</span> <span m=''2434870''>with</span> <span m=''2434980''>a</span>
  <span m=''2435060''>tree</span> <span m=''2435330''>it can''t.</span> <span m=''2436600''>OK,</span>
  <span m=''2436980''>big</span> <span m=''2437320''>deal.</span> </p><p><span m=''2438900''>These</span>
  <span m=''2439150''>examples,</span> <span m=''2440520''>this</span> <span m=''2440670''>is</span>
  <span m=''2440790''>just</span> <span m=''2441160''>yet</span> <span m=''2441380''>another</span>
  <span m=''2441660''>way</span> <span m=''2441780''>to</span> <span m=''2441870''>do</span>
  <span m=''2442000''>that.</span> <span m=''2442910''>But</span> <span m=''2442930''>what''s</span>
  <span m=''2443100''>interesting</span> <span m=''2443620''>is</span> <span m=''2443740''>if</span>
  <span m=''2443860''>you</span> <span m=''2443970''>double</span> <span m=''2444340''>some</span>
  <span m=''2444740''>of</span> <span m=''2444850''>the</span> <span m=''2445000''>edges</span>
  <span m=''2447060''>you</span> <span m=''2447150''>get</span> <span m=''2447330''>this</span>
  <span m=''2447540''>tree.</span> <span m=''2448700''>So you</span> <span m=''2448850''>have</span>
  <span m=''2448950''>1</span> <span m=''2449390''>degree</span> <span m=''2449680''>3</span>
  <span m=''2449850''>vertex</span> <span m=''2450280''>in</span> <span m=''2450340''>the</span>
  <span m=''2450440''>center.</span> <span m=''2451610''>And</span> <span m=''2452040''>you</span>
  <span m=''2452160''>go</span> <span m=''2452440''>around,</span> <span m=''2452740''>you</span>
  <span m=''2452840''>visit</span> <span m=''2453200''>this</span> <span m=''2453500''>arm.</span>
  <span m=''2454160''>You</span> <span m=''2454280''>go</span> <span m=''2454430''>back,</span>
  <span m=''2454760''>you</span> <span m=''2454850''>visit</span> <span m=''2455130''>this</span>
  <span m=''2455330''>arm.</span> </p><p><span m=''2456040''>Turns</span> <span m=''2456260''>out</span>
  <span m=''2456390''>this</span> <span m=''2456590''>really</span> <span m=''2456860''>does</span>
  <span m=''2457130''>simulate</span> <span m=''2458080''>this</span> <span m=''2458270''>tree,</span>
  <span m=''2458860''>because</span> <span m=''2459180''>we</span> <span m=''2459280''>haven''t</span>
  <span m=''2459610''>touched</span> <span m=''2459850''>the</span> <span m=''2459950''>central</span>
  <span m=''2461000''>degree 3</span> <span m=''2461320''>vertex.</span> <span m=''2461720''>And</span>
  <span m=''2461820''>this</span> <span m=''2461970''>is</span> <span m=''2462090''>nice</span>
  <span m=''2462300''>because</span> <span m=''2462470''>it</span> <span m=''2462530''>has</span>
  <span m=''2462730''>one</span> <span m=''2463790''>degree</span> <span m=''2464060''>3</span>
  <span m=''2464230''>vertex.</span> <span m=''2465300''>Everything</span> <span m=''2465690''>else</span>
  <span m=''2465930''>is</span> <span m=''2466040''>degree</span> <span m=''2466320''>2</span>
  <span m=''2467010''>or</span> <span m=''2467110''>1.</span> </p><p><span m=''2467890''>So</span>
  <span m=''2468310''>in</span> <span m=''2468510''>the</span> <span m=''2468660''>Carpenter''s</span>
  <span m=''2469050''>Rule</span> <span m=''2469250''>theorem</span> <span m=''2469420''>where</span>
  <span m=''2469540''>we</span> <span m=''2469650''>said</span> <span m=''2469840''>maximum</span>
  <span m=''2470240''>degree</span> <span m=''2470530''>2,</span> <span m=''2471630''>it''s</span>
  <span m=''2471800''>really</span> <span m=''2472010''>tight.</span> <span m=''2472330''>And</span>
  <span m=''2472440''>as</span> <span m=''2472670''>soon as</span> <span m=''2472800''>you</span>
  <span m=''2472890''>add</span> <span m=''2473040''>one</span> <span m=''2473400''>vertex</span>
  <span m=''2473780''>of</span> <span m=''2473850''>degree</span> <span m=''2474170''>3</span>
  <span m=''2474810''>you</span> <span m=''2474980''>can be</span> <span m=''2475220''>locked.</span>
  <span m=''2476800''>That was</span> <span m=''2477090''>the</span> <span m=''2477170''>point</span>
  <span m=''2477410''>of</span> <span m=''2477480''>this</span> <span m=''2477650''>example.</span>
  </p><p><span m=''2480000''>What</span> <span m=''2480260''>other</span> <span m=''2480440''>fun</span>
  <span m=''2480660''>things</span> <span m=''2480910''>can</span> <span m=''2481060''>you</span>
  <span m=''2481160''>do</span> <span m=''2481300''>with</span> <span m=''2481380''>trees?</span>
  <span m=''2482010''>Well,</span> <span m=''2483260''>three</span> <span m=''2483450''>years</span>
  <span m=''2483660''>ago</span> <span m=''2483890''>in</span> <span m=''2483970''>this</span>
  <span m=''2484120''>class</span> <span m=''2484610''>we</span> <span m=''2485000''>started</span>
  <span m=''2485320''>thinking</span> <span m=''2485570''>about</span> <span m=''2485780''>other</span>
  <span m=''2486020''>locked</span> <span m=''2486250''>trees.</span> <span m=''2487360''>How</span>
  <span m=''2487570''>low</span> <span m=''2487870''>could</span> <span m=''2488050''>you</span>
  <span m=''2488170''>go?</span> <span m=''2489510''>How</span> <span m=''2489700''>many</span>
  <span m=''2489920''>edges</span> <span m=''2490180''>do</span> <span m=''2490350''>need</span>
  <span m=''2490600''>to</span> <span m=''2490680''>get</span> <span m=''2490860''>locked?</span>
  </p><p><span m=''2491980''>This</span> <span m=''2492190''>example--</span> <span
  m=''2494760''>no</span> <span m=''2494910''>I</span> <span m=''2494970''>guess</span>
  <span m=''2495190''>this</span> <span m=''2495380''>example</span> <span m=''2495760''>would</span>
  <span m=''2495930''>be</span> <span m=''2496050''>minimum.</span> <span m=''2496890''>Here
  I''ve</span> <span m=''2497180''>drawn it</span> <span m=''2497380''>with</span>
  <span m=''2497550''>eight</span> <span m=''2497770''>petals.</span> <span m=''2498120''>You</span>
  <span m=''2498250''>can</span> <span m=''2498340''>get</span> <span m=''2498470''>away</span>
  <span m=''2498620''>with</span> <span m=''2498780''>five</span> <span m=''2499170''>petals,</span>
  <span m=''2500770''>or</span> <span m=''2500980''>are</span> <span m=''2501020''>five</span>
  <span m=''2501330''>arms,</span> <span m=''2501870''>each</span> <span m=''2502120''>of</span>
  <span m=''2502250''>length</span> <span m=''2502520''>3.</span> <span m=''2503200''>So</span>
  <span m=''2503320''>that''s</span> <span m=''2503470''>15</span> <span m=''2503990''>edges.</span>
  <span m=''2504500''>That</span> <span m=''2504640''>was</span> <span m=''2504800''>the</span>
  <span m=''2504890''>state</span> <span m=''2505160''>of</span> <span m=''2505240''>the</span>
  <span m=''2505380''>art.</span> </p><p><span m=''2506170''>And</span> <span m=''2506320''>then</span>
  <span m=''2506440''>we</span> <span m=''2506540''>had</span> <span m=''2506710''>this</span>
  <span m=''2506920''>crazy</span> <span m=''2507990''>idea</span> <span m=''2509630''>in</span>
  <span m=''2509770''>a</span> <span m=''2509830''>problem</span> <span m=''2510110''>session</span>
  <span m=''2510650''>of</span> <span m=''2510860''>this</span> <span m=''2511630''>locked</span>
  <span m=''2512130''>chain,</span> <span m=''2512780''>locked</span> <span m=''2513210''>tree.</span>
  <span m=''2515010''>It</span> <span m=''2515050''>has</span> <span m=''2515280''>two</span>
  <span m=''2515570''>degree</span> <span m=''2515860''>3</span> <span m=''2516040''>vertices.</span>
  <span m=''2517530''>And it</span> <span m=''2517860''>kind</span> <span m=''2518110''>of</span>
  <span m=''2518180''>just</span> <span m=''2518360''>winds</span> <span m=''2518840''>in</span>
  <span m=''2518970''>there.</span> <span m=''2519360''>We''re</span> <span m=''2519460''>going</span>
  <span m=''2519570''>to</span> <span m=''2519700''>see</span> <span m=''2519970''>why</span>
  <span m=''2520170''>these</span> <span m=''2520350''>things</span> <span m=''2520530''>are</span>
  <span m=''2520590''>locked.</span> </p><p><span m=''2521360''>But OK,</span> <span
  m=''2521580''>that''s</span> <span m=''2521840''>kind of neat.</span> <span m=''2522170''>11,</span>
  <span m=''2522630''>that''s</span> <span m=''2522850''>much</span> <span m=''2523020''>better</span>
  <span m=''2523180''>than</span> <span m=''2523320''>15.</span> <span m=''2523740''>Can</span>
  <span m=''2523910''>we</span> <span m=''2524010''>do</span> <span m=''2524120''>better?</span>
  <span m=''2524820''>And</span> <span m=''2525360''>every</span> <span m=''2525630''>week</span>
  <span m=''2525970''>we</span> <span m=''2526100''>improved</span> <span m=''2526450''>it,</span>
  <span m=''2527450''>for</span> <span m=''2527770''>a</span> <span m=''2527830''>few</span>
  <span m=''2528110''>weeks.</span> </p><p><span m=''2528890''>This</span> <span m=''2529150''>one</span>
  <span m=''2529880''>looks</span> <span m=''2530150''>messier,</span> <span m=''2530660''>but</span>
  <span m=''2530810''>it</span> <span m=''2530860''>has</span> <span m=''2531040''>one</span>
  <span m=''2531320''>fewer</span> <span m=''2531620''>edge.</span> <span m=''2533140''>And</span>
  <span m=''2533370''>then</span> <span m=''2533830''>this</span> <span m=''2534030''>one</span>
  <span m=''2534340''>came</span> <span m=''2534540''>along,</span> <span m=''2534910''>and
  we''re</span> <span m=''2535200''>like</span> <span m=''2535270''>whoa.</span> <span
  m=''2536930''>So</span> <span m=''2537100''>symmetric,</span> <span m=''2538260''>so</span>
  <span m=''2538470''>beautiful.</span> <span m=''2540860''>What''s</span> <span m=''2541210''>interesting</span>
  <span m=''2541690''>is</span> <span m=''2541780''>it</span> <span m=''2541900''>doesn''t</span>
  <span m=''2542170''>have</span> <span m=''2542380''>the</span> <span m=''2542550''>cyclic</span>
  <span m=''2542880''>structure.</span> <span m=''2545580''>It''s</span> <span m=''2545760''>almost</span>
  <span m=''2546070''>flat,</span> <span m=''2546540''>in</span> <span m=''2546640''>fact.</span>
  </p><p><span m=''2547600''>You</span> <span m=''2547650''>could</span> <span m=''2547810''>think</span>
  <span m=''2547980''>of</span> <span m=''2548080''>all</span> <span m=''2548210''>these</span>
  <span m=''2548580''>guys</span> <span m=''2548840''>being</span> <span m=''2549030''>in</span>
  <span m=''2549120''>one</span> <span m=''2549310''>point.</span> <span m=''2549630''>All</span>
  <span m=''2549760''>these</span> <span m=''2549940''>guys</span> <span m=''2550140''>being</span>
  <span m=''2550270''>in</span> <span m=''2550340''>one</span> <span m=''2550500''>point.</span>
  <span m=''2551030''>All</span> <span m=''2551210''>those</span> <span m=''2551360''>guys</span>
  <span m=''2551530''>being</span> <span m=''2551700''>in one</span> <span m=''2551860''>point.</span>
  <span m=''2552170''>It''s like</span> <span m=''2552370''>they''re,</span> <span
  m=''2552510''>all</span> <span m=''2552710''>three,</span> <span m=''2552960''>collinear.</span>
  <span m=''2554460''>So</span> <span m=''2554570''>it''s</span> <span m=''2554670''>a</span>
  <span m=''2554710''>very</span> <span m=''2554930''>different</span> <span m=''2555310''>kind</span>
  <span m=''2555500''>of</span> <span m=''2555580''>example.</span> </p><p><span m=''2556360''>Before</span>
  <span m=''2556690''>we</span> <span m=''2556800''>thought</span> <span m=''2557600''>locked</span>
  <span m=''2557880''>trees</span> <span m=''2558150''>required</span> <span m=''2558670''>this</span>
  <span m=''2558920''>kind</span> <span m=''2559050''>of</span> <span m=''2559120''>cyclic</span>
  <span m=''2560070''>condition.</span> <span m=''2563170''>And</span> <span m=''2563400''>so,</span>
  <span m=''2563530''>for</span> <span m=''2563700''>example,</span> <span m=''2565600''>we</span>
  <span m=''2565850''>conjectured--</span> <span m=''2566950''>or</span> <span m=''2567320''>I</span>
  <span m=''2567430''>guess</span> <span m=''2567620''>Poon,</span> <span m=''2568100''>one</span>
  <span m=''2568230''>of</span> <span m=''2568320''>the</span> <span m=''2568440''>authors</span>
  <span m=''2568810''>here--</span> <span m=''2569480''>conjectured</span> <span m=''2570020''>that</span>
  <span m=''2570960''>there would</span> <span m=''2571090''>be</span> <span m=''2571240''>no</span>
  <span m=''2571480''>way</span> <span m=''2571590''>to</span> <span m=''2571690''>lock</span>
  <span m=''2571940''>something</span> <span m=''2572240''>if</span> <span m=''2572350''>all</span>
  <span m=''2572540''>the</span> <span m=''2572660''>edges</span> <span m=''2572930''>were</span>
  <span m=''2573140''>horizontal</span> <span m=''2573630''>and</span> <span m=''2573710''>vertical.</span>
  <span m=''2574750''>Because</span> <span m=''2576160''>if</span> <span m=''2576420''>you</span>
  <span m=''2576570''>have</span> <span m=''2576740''>that</span> <span m=''2576970''>you</span>
  <span m=''2577520''>couldn''t</span> <span m=''2577770''>have</span> <span m=''2578050''>five</span>
  <span m=''2578320''>things</span> <span m=''2578560''>in</span> <span m=''2578660''>a</span>
  <span m=''2578710''>circle.</span> </p><p><span m=''2579770''>Now</span> <span m=''2580010''>suddenly</span>
  <span m=''2580265''>we</span> <span m=''2580520''>think,</span> <span m=''2580740''>oh,</span>
  <span m=''2581160''>this</span> <span m=''2581320''>is</span> <span m=''2581500''>interesting.</span>
  <span m=''2582030''>Because</span> <span m=''2583990''>it has</span> <span m=''2584170''>two</span>
  <span m=''2584690''>degree</span> <span m=''2584950''>3</span> <span m=''2585060''>vertices.</span>
  <span m=''2585970''>It''s so</span> <span m=''2586100''>symmetric.</span> <span
  m=''2587140''>Surely</span> <span m=''2587510''>this</span> <span m=''2587670''>is</span>
  <span m=''2587770''>the</span> <span m=''2587910''>fewest</span> <span m=''2588440''>possible</span>
  <span m=''2588920''>edges</span> <span m=''2589220''>we</span> <span m=''2589340''>could</span>
  <span m=''2589480''>get</span> <span m=''2589610''>away</span> <span m=''2589850''>with.</span>
  </p><p><span m=''2591840''>But</span> <span m=''2592060''>no,</span> <span m=''2593200''>then</span>
  <span m=''2593310''>we</span> <span m=''2593430''>found</span> <span m=''2593740''>the</span>
  <span m=''2593960''>eight</span> <span m=''2594820''>edge</span> <span m=''2595080''>example.</span>
  <span m=''2596550''>And</span> <span m=''2596960''>this</span> <span m=''2597220''>is</span>
  <span m=''2597710''>kind</span> <span m=''2597940''>of</span> <span m=''2598030''>funny.</span>
  <span m=''2598580''>It''s</span> <span m=''2598750''>like</span> <span m=''2598930''>instead</span>
  <span m=''2599350''>of</span> <span m=''2600130''>being</span> <span m=''2600320''>nice</span>
  <span m=''2600580''>and</span> <span m=''2600710''>symmetric,</span> <span m=''2602940''>essentially,</span>
  <span m=''2603320''>what</span> <span m=''2603430''>we''re</span> <span m=''2603510''>doing</span>
  <span m=''2603690''>is</span> <span m=''2603770''>removing</span> <span m=''2604120''>this</span>
  <span m=''2604310''>edge.</span> <span m=''2605110''>And</span> <span m=''2605270''>we</span>
  <span m=''2605340''>want</span> <span m=''2605510''>to</span> <span m=''2605570''>instead</span>
  <span m=''2605910''>attach</span> <span m=''2606300''>it in</span> <span m=''2606470''>here.</span>
  <span m=''2607500''>But</span> <span m=''2607640''>then</span> <span m=''2607800''>we</span>
  <span m=''2607890''>have</span> <span m=''2608000''>to</span> <span m=''2608150''>futz</span>
  <span m=''2608440''>around</span> <span m=''2608700''>with the</span> <span m=''2608770''>vertices</span>
  <span m=''2609270''>to</span> <span m=''2609380''>make</span> <span m=''2609570''>it</span>
  <span m=''2609640''>work</span> <span m=''2609880''>out</span> <span m=''2610050''>and</span>
  <span m=''2610150''>be</span> <span m=''2610480''>a</span> <span m=''2610560''>tree.</span>
  </p><p><span m=''2611070''>And</span> <span m=''2611390''>now</span> <span m=''2611590''>has</span>
  <span m=''2611890''>only</span> <span m=''2612170''>one</span> <span m=''2613630''>degree</span>
  <span m=''2613900''>3</span> <span m=''2614070''>vertex.</span> <span m=''2615020''>So</span>
  <span m=''2615130''>it</span> <span m=''2615190''>also</span> <span m=''2615430''>has</span>
  <span m=''2615590''>that</span> <span m=''2615790''>nice</span> <span m=''2615960''>property.</span>
  <span m=''2616830''>It only</span> <span m=''2617040''>has</span> <span m=''2617250''>eight</span>
  <span m=''2617400''>edges.</span> <span m=''2617750''>And</span> <span m=''2617920''>this,</span>
  <span m=''2618230''>we</span> <span m=''2618250''>believe,</span> <span m=''2618680''>is</span>
  <span m=''2618700''>optimal.</span> </p><p><span m=''2623140''>And</span> <span
  m=''2623200''>we</span> <span m=''2623300''>can</span> <span m=''2623450''>actually</span>
  <span m=''2623710''>prove</span> <span m=''2623990''>something</span> <span m=''2624300''>along</span>
  <span m=''2624510''>those</span> <span m=''2624680''>lines.</span> <span m=''2627120''>So</span>
  <span m=''2627520''>a</span> <span m=''2627650''>linear</span> <span m=''2630900''>tree</span>
  <span m=''2632370''>is</span> <span m=''2632620''>one</span> <span m=''2632930''>where</span>
  <span m=''2633370''>all</span> <span m=''2633660''>the</span> <span m=''2633740''>vertices</span>
  <span m=''2637860''>lie</span> <span m=''2639490''>nearly</span> <span m=''2639890''>on</span>
  <span m=''2640010''>the</span> <span m=''2640080''>line.</span> <span m=''2644930''>So</span>
  <span m=''2645000''>this</span> <span m=''2645200''>is</span> <span m=''2645330''>a</span>
  <span m=''2645420''>linear</span> <span m=''2645890''>locked</span> <span m=''2646300''>tree.</span>
  <span m=''2647360''>And</span> <span m=''2647540''>we</span> <span m=''2647650''>can</span>
  <span m=''2647770''>prove</span> <span m=''2648000''>that</span> <span m=''2648120''>among</span>
  <span m=''2648420''>all</span> <span m=''2648730''>linear</span> <span m=''2649030''>locked</span>
  <span m=''2649270''>trees,</span> <span m=''2649640''>they</span> <span m=''2649740''>must</span>
  <span m=''2650280''>have</span> <span m=''2650800''>at</span> <span m=''2650970''>least</span>
  <span m=''2651310''>eight</span> <span m=''2651520''>edges.</span> </p><p><span
  m=''2655952''>Locked</span> <span m=''2657390''>linear</span> <span m=''2659060''>tree</span>
  <span m=''2660710''>has</span> <span m=''2661950''>at</span> <span m=''2662040''>least</span>
  <span m=''2662400''>eight</span> <span m=''2662810''>edges.</span> <span m=''2664130''>So</span>
  <span m=''2664200''>at least</span> <span m=''2664420''>among</span> <span m=''2664750''>linear</span>
  <span m=''2665020''>locked</span> <span m=''2665290''>trees</span> <span m=''2666160''>that</span>
  <span m=''2666350''>example</span> <span m=''2666760''>is</span> <span m=''2667060''>optimal.</span>
  <span m=''2668390''>But</span> <span m=''2669720''>maybe</span> <span m=''2670310''>you</span>
  <span m=''2670440''>could</span> <span m=''2670620''>use</span> <span m=''2670970''>the</span>
  <span m=''2671100''>second</span> <span m=''2671510''>dimension</span> <span m=''2672490''>to</span>
  <span m=''2673470''>do</span> <span m=''2673590''>something</span> <span m=''2673930''>better</span>
  <span m=''2674700''>than eight</span> <span m=''2674970''>edges.</span> <span m=''2675400''>But</span>
  <span m=''2675540''>I</span> <span m=''2675600''>don''t</span> <span m=''2675770''>think</span>
  <span m=''2675930''>so.</span> <span m=''2676840''>That''s</span> <span m=''2677110''>an</span>
  <span m=''2677200''>open</span> <span m=''2677410''>problem.</span> </p><p><span
  m=''2679230''>What</span> <span m=''2679540''>other</span> <span m=''2679800''>good</span>
  <span m=''2679990''>things</span> <span m=''2680240''>can</span> <span m=''2680410''>we</span>
  <span m=''2680520''>do?</span> <span m=''2681110''>You</span> <span m=''2681260''>can</span>
  <span m=''2681350''>make</span> <span m=''2681550''>it</span> <span m=''2681620''>orthogonal.</span>
  <span m=''2683110''>You</span> <span m=''2683290''>can</span> <span m=''2683430''>mimic</span>
  <span m=''2683800''>exactly</span> <span m=''2684250''>this</span> <span m=''2684410''>structure</span>
  <span m=''2685570''>with</span> <span m=''2685790''>an</span> <span m=''2685880''>orthogonal</span>
  <span m=''2686390''>structure,</span> <span m=''2686810''>all</span> <span m=''2686960''>the</span>
  <span m=''2687090''>edges</span> <span m=''2687440''>horizontal</span> <span m=''2687930''>and</span>
  <span m=''2688020''>vertical.</span> <span m=''2688840''>Just</span> <span m=''2689050''>expand</span>
  <span m=''2689470''>each</span> <span m=''2689630''>of</span> <span m=''2689720''>these</span>
  <span m=''2690350''>vertices</span> <span m=''2690870''>into</span> <span m=''2691270''>very</span>
  <span m=''2691680''>tiny,</span> <span m=''2692170''>and</span> <span m=''2692240''>if</span>
  <span m=''2692360''>this</span> <span m=''2692530''>is</span> <span m=''2692650''>drawn</span>
  <span m=''2692880''>really</span> <span m=''2693120''>squished,</span> <span m=''2694120''>these</span>
  <span m=''2694290''>are</span> <span m=''2694370''>super</span> <span m=''2694690''>short</span>
  <span m=''2695030''>edges.</span> <span m=''2695450''>So</span> <span m=''2695470''>they</span>
  <span m=''2695590''>really</span> <span m=''2695820''>don''t</span> <span m=''2696000''>change</span>
  <span m=''2696360''>the</span> <span m=''2696480''>motion</span> <span m=''2696790''>space</span>
  <span m=''2697250''>hardly</span> <span m=''2697540''>at</span> <span m=''2697600''>all.</span>
  <span m=''2698550''>You</span> <span m=''2698650''>can</span> <span m=''2698740''>actually</span>
  <span m=''2698970''>prove</span> <span m=''2699210''>that.</span> </p><p><span m=''2699910''>And</span>
  <span m=''2700090''>this</span> <span m=''2700250''>is</span> <span m=''2700370''>also</span>
  <span m=''2700690''>locked.</span> <span m=''2701780''>That''s</span> <span m=''2701930''>one</span>
  <span m=''2702080''>of</span> <span m=''2702160''>the</span> <span m=''2702200''>nice</span>
  <span m=''2702390''>things</span> <span m=''2702550''>you</span> <span m=''2702650''>do</span>
  <span m=''2702830''>once</span> <span m=''2702990''>you</span> <span m=''2703070''>get</span>
  <span m=''2703210''>out</span> <span m=''2703430''>of</span> <span m=''2703540''>the</span>
  <span m=''2703660''>cyclic</span> <span m=''2704070''>kind</span> <span m=''2704260''>of</span>
  <span m=''2704330''>structure.</span> </p><p><span m=''2707540''>I</span> <span
  m=''2707630''>think</span> <span m=''2708050''>I</span> <span m=''2708130''>have</span>
  <span m=''2709100''>something</span> <span m=''2709460''>else,</span> <span m=''2709840''>no.</span>
  <span m=''2710110''>OK,</span> <span m=''2710590''>stay</span> <span m=''2710990''>there.</span>
  <span m=''2715180''>Yeah,</span> <span m=''2715840''>actually</span> <span m=''2716110''>maybe</span>
  <span m=''2716330''>I</span> <span m=''2716360''>do</span> <span m=''2716510''>want</span>
  <span m=''2716640''>to</span> <span m=''2716700''>go</span> <span m=''2716830''>there.</span>
  </p><p><span m=''2721870''>This</span> <span m=''2722230''>is</span> <span m=''2722350''>an</span>
  <span m=''2722440''>example,</span> <span m=''2723240''>it</span> <span m=''2723340''>has</span>
  <span m=''2723580''>a</span> <span m=''2723640''>cyclic</span> <span m=''2724000''>structure</span>
  <span m=''2724490''>again.</span> <span m=''2724980''>Same</span> <span m=''2725220''>paper,</span>
  <span m=''2727270''>last</span> <span m=''2727560''>year.</span> <span m=''2730020''>This</span>
  <span m=''2730210''>is</span> <span m=''2730340''>a</span> <span m=''2730420''>newer</span>
  <span m=''2730680''>example.</span> <span m=''2731750''>And it</span> <span m=''2731950''>has</span>
  <span m=''2732130''>the</span> <span m=''2732220''>property</span> <span m=''2732560''>that</span>
  <span m=''2732730''>all</span> <span m=''2732940''>of</span> <span m=''2733020''>the</span>
  <span m=''2733150''>edge</span> <span m=''2733330''>lengths</span> <span m=''2733580''>are</span>
  <span m=''2733630''>the</span> <span m=''2733760''>same,</span> <span m=''2735110''>and</span>
  <span m=''2736760''>nothing</span> <span m=''2737070''>touches.</span> </p><p><span
  m=''2738960''>Now</span> <span m=''2740000''>you''ll</span> <span m=''2740180''>appreciate</span>
  <span m=''2740610''>this</span> <span m=''2740760''>in</span> <span m=''2741180''>a</span>
  <span m=''2741250''>little</span> <span m=''2741470''>while,</span> <span m=''2742290''>how</span>
  <span m=''2742550''>crazy</span> <span m=''2742950''>this</span> <span m=''2743160''>is.</span>
  <span m=''2743730''>Because</span> <span m=''2744910''>all</span> <span m=''2745170''>of</span>
  <span m=''2745240''>the</span> <span m=''2745340''>previous</span> <span m=''2745700''>examples</span>
  <span m=''2747190''>required</span> <span m=''2747920''>things</span> <span m=''2748130''>to</span>
  <span m=''2748220''>be</span> <span m=''2748340''>very</span> <span m=''2748660''>close</span>
  <span m=''2748970''>and</span> <span m=''2749110''>tight.</span> <span m=''2749560''>And</span>
  <span m=''2749810''>we</span> <span m=''2749940''>crucially</span> <span m=''2750440''>use</span>
  <span m=''2750810''>very</span> <span m=''2751230''>tight</span> <span m=''2753300''>proximity</span>
  <span m=''2754230''>in</span> <span m=''2754420''>order</span> <span m=''2754570''>to</span>
  <span m=''2754640''>prove</span> <span m=''2755370''>things</span> <span m=''2755570''>are</span>
  <span m=''2755670''>locked.</span> </p><p><span m=''2757150''>And</span> <span m=''2757390''>if</span>
  <span m=''2757570''>you</span> <span m=''2757730''>take</span> <span m=''2760260''>the</span>
  <span m=''2760400''>example</span> <span m=''2760800''>that looks</span> <span m=''2760980''>like</span>
  <span m=''2761140''>this,</span> <span m=''2764150''>with</span> <span m=''2764530''>six</span>
  <span m=''2765370''>arms--</span> <span m=''2772930''>I</span> <span m=''2773030''>didn''t</span>
  <span m=''2773200''>draw it</span> <span m=''2773410''>very</span> <span m=''2773650''>well.</span>
  <span m=''2774250''>But</span> <span m=''2774360''>if</span> <span m=''2774440''>you</span>
  <span m=''2774500''>draw it</span> <span m=''2774690''>with</span> <span m=''2774810''>six</span>
  <span m=''2775070''>arms,</span> <span m=''2775700''>these</span> <span m=''2776110''>are</span>
  <span m=''2776180''>like</span> <span m=''2776340''>equilateral</span> <span m=''2776860''>triangles,</span>
  <span m=''2777790''>the</span> <span m=''2777900''>edge lengths</span> <span m=''2778320''>will</span>
  <span m=''2778520''>be</span> <span m=''2779100''>almost</span> <span m=''2779480''>all</span>
  <span m=''2779600''>the</span> <span m=''2779680''>same.</span> <span m=''2779980''>In
  fact, if</span> <span m=''2780300''>you</span> <span m=''2780430''>allow</span>
  <span m=''2780640''>them</span> <span m=''2780800''>to</span> <span m=''2780940''>touch</span>
  <span m=''2781360''>they</span> <span m=''2781450''>will</span> <span m=''2781610''>be</span>
  <span m=''2781700''>exactly</span> <span m=''2782130''>the</span> <span m=''2782260''>same.</span>
  </p><p><span m=''2783440''>So</span> <span m=''2783510''>there was</span> <span
  m=''2783720''>this</span> <span m=''2783890''>open</span> <span m=''2784120''>question,</span>
  <span m=''2784590''>well,</span> <span m=''2784830''>if</span> <span m=''2784960''>I</span>
  <span m=''2785020''>want</span> <span m=''2785270''>them</span> <span m=''2785420''>to</span>
  <span m=''2785530''>be</span> <span m=''2785760''>exactly</span> <span m=''2786250''>the</span>
  <span m=''2786350''>same</span> <span m=''2786590''>but</span> <span m=''2786770''>not</span>
  <span m=''2787060''>touch,</span> <span m=''2787740''>can</span> <span m=''2787900''>you</span>
  <span m=''2787990''>still</span> <span m=''2788250''>lock?</span> <span m=''2789180''>We</span>
  <span m=''2789300''>thought</span> <span m=''2789530''>no,</span> <span m=''2790350''>but</span>
  <span m=''2790490''>in</span> <span m=''2790560''>fact</span> <span m=''2790820''>you</span>
  <span m=''2790920''>can</span> <span m=''2791050''>do</span> <span m=''2791240''>it.</span>
  <span m=''2791940''>And</span> <span m=''2792120''>this</span> <span m=''2792310''>is</span>
  <span m=''2792460''>very</span> <span m=''2792740''>tricky</span> <span m=''2793100''>to</span>
  <span m=''2793190''>prove</span> <span m=''2793410''>locked</span> <span m=''2793710''>because</span>
  <span m=''2794090''>we</span> <span m=''2794190''>can''t</span> <span m=''2794450''>make</span>
  <span m=''2794640''>these</span> <span m=''2795180''>arbitrarily</span> <span m=''2795870''>tight.</span>
  <span m=''2796660''>It</span> <span m=''2796800''>really</span> <span m=''2797070''>has</span>
  <span m=''2797290''>to</span> <span m=''2797380''>look</span> <span m=''2797590''>like</span>
  <span m=''2797770''>this,</span> <span m=''2798160''>because</span> <span m=''2798560''>the</span>
  <span m=''2798660''>edge</span> <span m=''2798810''>lengths</span> <span m=''2799020''>are</span>
  <span m=''2799090''>all</span> <span m=''2799180''>the</span> <span m=''2799240''>same.</span>
  </p><p><span m=''2800350''>Now</span> <span m=''2800430''>this</span> <span m=''2800650''>has</span>
  <span m=''2800800''>seven-fold</span> <span m=''2802910''>symmetry.</span> <span
  m=''2806030''>Because</span> <span m=''2806100''>sixfold</span> <span m=''2806540''>they</span>
  <span m=''2806620''>would</span> <span m=''2806740''>all</span> <span m=''2806890''>touch.</span>
  <span m=''2808400''>It''s tricky.</span> <span m=''2812200''>Cool.</span> </p><p><span
  m=''2815890''>A</span> <span m=''2816000''>big</span> <span m=''2816200''>open</span>
  <span m=''2816400''>question</span> <span m=''2816680''>here,</span> <span m=''2817050''>of</span>
  <span m=''2817150''>course,</span> <span m=''2817370''>is to</span> <span m=''2817470''>characterize</span>
  <span m=''2818010''>locked</span> <span m=''2818270''>trees.</span> <span m=''2819300''>I</span>
  <span m=''2819410''>think</span> <span m=''2819580''>that''s</span> <span m=''2820050''>quite</span>
  <span m=''2820460''>hard,</span> <span m=''2821870''>because</span> <span m=''2822180''>in</span>
  <span m=''2822270''>particular,</span> <span m=''2822680''>if you''re given</span>
  <span m=''2823070''>a</span> <span m=''2823140''>tree</span> <span m=''2823390''>and</span>
  <span m=''2823470''>you</span> <span m=''2823570''>want</span> <span m=''2823730''>to</span>
  <span m=''2823780''>know</span> <span m=''2823940''>does</span> <span m=''2824140''>that</span>
  <span m=''2824230''>go</span> <span m=''2824380''>from</span> <span m=''2824580''>this</span>
  <span m=''2824800''>configuration</span> <span m=''2825390''>to</span> <span m=''2825480''>this</span>
  <span m=''2825670''>configuration,</span> <span m=''2826720''>that''s</span> <span
  m=''2826980''>known</span> <span m=''2827130''>to</span> <span m=''2827200''>be</span>
  <span m=''2827340''>p</span> <span m=''2827480''>space</span> <span m=''2827770''>complete,</span>
  <span m=''2828190''>which</span> <span m=''2828350''>is</span> <span m=''2828530''>really,</span>
  <span m=''2828930''>really</span> <span m=''2829010''>hard.</span> <span m=''2830400''>But</span>
  <span m=''2830730''>all</span> <span m=''2830950''>of</span> <span m=''2831020''>those</span>
  <span m=''2831170''>examples</span> <span m=''2831640''>are</span> <span m=''2831770''>locked.</span>
  <span m=''2832180''>So</span> <span m=''2832500''>maybe</span> <span m=''2833200''>unlocked</span>
  <span m=''2833740''>trees</span> <span m=''2834400''>have</span> <span m=''2834630''>some</span>
  <span m=''2834810''>special</span> <span m=''2835170''>structure</span> <span m=''2835520''>that''s</span>
  <span m=''2835700''>easy</span> <span m=''2835910''>to</span> <span m=''2835990''>find.</span>
  </p><p><span m=''2837020''>I</span> <span m=''2837180''>guess</span> <span m=''2837620''>not.</span>
  <span m=''2838090''>But</span> <span m=''2838910''>who</span> <span m=''2839050''>knows?</span>
  <span m=''2840230''>What</span> <span m=''2840430''>I</span> <span m=''2840500''>do</span>
  <span m=''2840720''>think</span> <span m=''2840890''>has</span> <span m=''2841070''>a</span>
  <span m=''2841120''>nice</span> <span m=''2841300''>structure</span> <span m=''2841700''>are</span>
  <span m=''2841830''>these</span> <span m=''2842020''>linear</span> <span m=''2842370''>locked</span>
  <span m=''2842590''>trees.</span> <span m=''2843990''>They''re</span> <span m=''2844180''>pretty</span>
  <span m=''2844370''>simple.</span> <span m=''2844800''>They''re</span> <span m=''2844820''>basically</span>
  <span m=''2845160''>one</span> <span m=''2845340''>dimensional.</span> </p><p><span
  m=''2846230''>And</span> <span m=''2846310''>I</span> <span m=''2846370''>think</span>
  <span m=''2846580''>we</span> <span m=''2846710''>could</span> <span m=''2846840''>characterize</span>
  <span m=''2847470''>linear</span> <span m=''2847770''>lock</span> <span m=''2848000''>trees</span>
  <span m=''2848790''>in</span> <span m=''2848950''>polynomial</span> <span m=''2849450''>time.</span>
  <span m=''2850170''>Maybe</span> <span m=''2850380''>we''ll work</span> <span m=''2850670''>on</span>
  <span m=''2850770''>that</span> <span m=''2850990''>this</span> <span m=''2851380''>afternoon.</span>
  <span m=''2853430''>But</span> <span m=''2853570''>that</span> <span m=''2853740''>is</span>
  <span m=''2853850''>open.</span> </p><p><span m=''2856590''>All</span> <span m=''2856670''>right,</span>
  <span m=''2857390''>next</span> <span m=''2857610''>thing</span> <span m=''2857760''>I</span>
  <span m=''2857800''>want</span> <span m=''2857960''>to</span> <span m=''2858010''>talk</span>
  <span m=''2858240''>about</span> <span m=''2858460''>is</span> <span m=''2858580''>how</span>
  <span m=''2858800''>the</span> <span m=''2858880''>heck</span> <span m=''2859100''>do</span>
  <span m=''2859180''>you</span> <span m=''2859290''>prove</span> <span m=''2859780''>that
  these</span> <span m=''2859970''>things</span> <span m=''2860160''>are</span> <span
  m=''2860250''>locked?</span> </p><p><span m=''2861440''>Now</span> <span m=''2861850''>historically</span>
  <span m=''2862470''>there</span> <span m=''2862570''>have</span> <span m=''2862670''>been</span>
  <span m=''2862790''>lots</span> <span m=''2863050''>of</span> <span m=''2863130''>different</span>
  <span m=''2863420''>proofs.</span> <span m=''2863780''>And</span> <span m=''2864200''>this</span>
  <span m=''2864980''>tree</span> <span m=''2865300''>still</span> <span m=''2865610''>does</span>
  <span m=''2865730''>not</span> <span m=''2865900''>have</span> <span m=''2866090''>a</span>
  <span m=''2866150''>nice</span> <span m=''2866480''>proof</span> <span m=''2866860''>that
  it''s</span> <span m=''2867130''>locked.</span> <span m=''2868000''>But</span> <span
  m=''2868090''>all</span> <span m=''2868280''>the</span> <span m=''2868400''>other</span>
  <span m=''2868580''>trees</span> <span m=''2868990''>I</span> <span m=''2869100''>can</span>
  <span m=''2869270''>give</span> <span m=''2869390''>you</span> <span m=''2869510''>very</span>
  <span m=''2869940''>succinct</span> <span m=''2870420''>proofs</span> <span m=''2871110''>that</span>
  <span m=''2871270''>they''re</span> <span m=''2871400''>locked.</span> <span m=''2872260''>And</span>
  <span m=''2872480''>so</span> <span m=''2872570''>I</span> <span m=''2872600''>want</span>
  <span m=''2872740''>to</span> <span m=''2872800''>tell</span> <span m=''2872970''>you</span>
  <span m=''2873080''>how</span> <span m=''2873370''>we</span> <span m=''2873490''>do</span>
  <span m=''2873610''>that.</span> <span m=''2883230''>Because</span> <span m=''2883470''>it</span>
  <span m=''2883600''>uses</span> <span m=''2884320''>tensegrity</span> <span m=''2885120''>theory,</span>
  <span m=''2886005''>our</span> <span m=''2886390''>good</span> <span m=''2886570''>friend.</span>
  </p><p><span m=''2894120''>This</span> <span m=''2894260''>is</span> <span m=''2894380''>the</span>
  <span m=''2894520''>idea</span> <span m=''2894930''>of</span> <span m=''2895550''>infinitesimally</span>
  <span m=''2897900''>locked</span> <span m=''2898430''>linkages.</span> <span m=''2918210''>So</span>
  <span m=''2918400''>ignore</span> <span m=''2918660''>this</span> <span m=''2918890''>part</span>
  <span m=''2919070''>of</span> <span m=''2919150''>the</span> <span m=''2919260''>picture</span>
  <span m=''2919550''>for</span> <span m=''2919660''>now.</span> <span m=''2919990''>If</span>
  <span m=''2920190''>we</span> <span m=''2920330''>take</span> <span m=''2920550''>some</span>
  <span m=''2920780''>tree,</span> <span m=''2922340''>most</span> <span m=''2922620''>of</span>
  <span m=''2922680''>the</span> <span m=''2922750''>examples</span> <span m=''2923240''>I</span>
  <span m=''2923310''>drew</span> <span m=''2923510''>these</span> <span m=''2923680''>little</span>
  <span m=''2924300''>scion</span> <span m=''2924660''>circles</span> <span m=''2925020''>to</span>
  <span m=''2925090''>say,</span> <span m=''2925370''>well,</span> <span m=''2925510''>these</span>
  <span m=''2925620''>guys</span> <span m=''2925850''>are</span> <span m=''2925940''>really</span>
  <span m=''2926200''>tight.</span> <span m=''2927700''>And</span> <span m=''2927880''>the</span>
  <span m=''2927950''>intuition</span> <span m=''2928450''>is</span> <span m=''2928620''>the</span>
  <span m=''2928820''>tighter</span> <span m=''2929210''>you</span> <span m=''2929350''>make</span>
  <span m=''2929600''>it,</span> <span m=''2930130''>the</span> <span m=''2930250''>less</span>
  <span m=''2930580''>that</span> <span m=''2930760''>configuration</span> <span m=''2931410''>can</span>
  <span m=''2931560''>move.</span> </p><p><span m=''2932530''>If</span> <span m=''2932700''>you</span>
  <span m=''2932860''>look,</span> <span m=''2933300''>we''re</span> <span m=''2933710''>claiming</span>
  <span m=''2934040''>the</span> <span m=''2934120''>configuration</span> <span m=''2934380''>space</span>
  <span m=''2934640''>is</span> <span m=''2934970''>disconnected.</span> <span m=''2935460''>But</span>
  <span m=''2935570''>not</span> <span m=''2935740''>only</span> <span m=''2935920''>that,</span>
  <span m=''2936130''>we</span> <span m=''2936230''>have</span> <span m=''2936380''>this</span>
  <span m=''2936530''>configuration</span> <span m=''2936860''>and</span> <span m=''2937190''>we</span>
  <span m=''2937280''>say</span> <span m=''2938110''>there''s</span> <span m=''2938300''>a</span>
  <span m=''2938370''>small</span> <span m=''2938980''>ball</span> <span m=''2939750''>of</span>
  <span m=''2939950''>motions</span> <span m=''2940430''>that</span> <span m=''2940510''>you</span>
  <span m=''2940610''>could</span> <span m=''2940740''>possibly</span> <span m=''2941220''>do.</span>
  <span m=''2941390''>It</span> <span m=''2941530''>does</span> <span m=''2942190''>wiggle</span>
  <span m=''2942500''>a</span> <span m=''2942570''>little</span> <span m=''2942940''>bit.</span>
  <span m=''2943870''>And</span> <span m=''2944070''>then</span> <span m=''2944160''>there''s</span>
  <span m=''2944290''>other</span> <span m=''2944500''>stuff</span> <span m=''2944770''>over</span>
  <span m=''2944970''>here</span> <span m=''2945250''>that</span> <span m=''2945370''>you</span>
  <span m=''2945460''>can</span> <span m=''2945940''>never</span> <span m=''2946160''>reach</span>
  <span m=''2946440''>because</span> <span m=''2946590''>this</span> <span m=''2946750''>can''t</span>
  <span m=''2946930''>move</span> <span m=''2947100''>very</span> <span m=''2947290''>much.</span>
  </p><p><span m=''2952270''>Well</span> <span m=''2952560''>in</span> <span m=''2952630''>fact,</span>
  <span m=''2953190''>if</span> <span m=''2953340''>you</span> <span m=''2953460''>make</span>
  <span m=''2954780''>these</span> <span m=''2955040''>circles</span> <span m=''2956130''>tighter</span>
  <span m=''2956530''>and</span> <span m=''2956670''>tighter,</span> <span m=''2958060''>the</span>
  <span m=''2958170''>claim</span> <span m=''2958480''>is</span> <span m=''2958640''>that</span>
  <span m=''2958820''>this,</span> <span m=''2959970''>in</span> <span m=''2960140''>the</span>
  <span m=''2960210''>space</span> <span m=''2960500''>of</span> <span m=''2960590''>motions,</span>
  <span m=''2961830''>you</span> <span m=''2962030''>get</span> <span m=''2962200''>less</span>
  <span m=''2962500''>and less</span> <span m=''2962790''>freedom.</span> <span m=''2964750''>How</span>
  <span m=''2964960''>could</span> <span m=''2965110''>we</span> <span m=''2965230''>formalize</span>
  <span m=''2965760''>that?</span> <span m=''2966950''>As</span> <span m=''2967160''>you</span>
  <span m=''2967270''>draw</span> <span m=''2967470''>the</span> <span m=''2967570''>thing</span>
  <span m=''2967800''>tighter</span> <span m=''2968870''>you</span> <span m=''2968980''>get</span>
  <span m=''2969140''>less</span> <span m=''2969350''>and</span> <span m=''2969410''>less</span>
  <span m=''2969600''>motion.</span> </p><p><span m=''2972730''>Well,</span> <span
  m=''2973940''>let''s</span> <span m=''2974100''>go</span> <span m=''2974220''>to</span>
  <span m=''2974280''>the</span> <span m=''2974400''>limit.</span> <span m=''2975540''>Suppose</span>
  <span m=''2975990''>we</span> <span m=''2976070''>went</span> <span m=''2976290''>all</span>
  <span m=''2976630''>the</span> <span m=''2976730''>way</span> <span m=''2976930''>to</span>
  <span m=''2977010''>the</span> <span m=''2977140''>point</span> <span m=''2977540''>that</span>
  <span m=''2978500''>these</span> <span m=''2978710''>things</span> <span m=''2978990''>are</span>
  <span m=''2979250''>touching.</span> <span m=''2980890''>Now</span> <span m=''2981270''>this</span>
  <span m=''2981470''>is</span> <span m=''2981630''>going</span> <span m=''2981760''>to</span>
  <span m=''2981820''>be</span> <span m=''2981910''>a</span> <span m=''2981960''>little</span>
  <span m=''2982150''>tricky</span> <span m=''2983080''>mathematically,</span> <span
  m=''2983670''>because</span> <span m=''2983830''>we</span> <span m=''2983930''>have</span>
  <span m=''2984070''>to</span> <span m=''2984140''>remember</span> <span m=''2984550''>that
  this</span> <span m=''2985440''>vertex</span> <span m=''2985850''>is</span> <span
  m=''2986010''>in</span> <span m=''2986180''>this</span> <span m=''2986350''>wedge,</span>
  <span m=''2986770''>even</span> <span m=''2987000''>though</span> <span m=''2987140''>it''s</span>
  <span m=''2987240''>actually</span> <span m=''2987520''>right</span> <span m=''2987760''>on</span>
  <span m=''2987890''>top</span> <span m=''2988130''>of</span> <span m=''2988190''>this</span>
  <span m=''2988350''>point.</span> <span m=''2989330''>So</span> <span m=''2989490''>we
  have to</span> <span m=''2989600''>remember,</span> <span m=''2990280''>sort</span>
  <span m=''2990470''>of,</span> <span m=''2990520''>how</span> <span m=''2990750''>things</span>
  <span m=''2991050''>look</span> <span m=''2991300''>locally.</span> <span m=''2993190''>But</span>
  <span m=''2993550''>geometrically</span> <span m=''2995410''>the</span> <span m=''2995640''>picture</span>
  <span m=''2996030''>is</span> <span m=''2996140''>going</span> <span m=''2996280''>to</span>
  <span m=''2996350''>look</span> <span m=''2996590''>like</span> <span m=''3002620''>that.</span>
  </p><p><span m=''3004390''>If</span> <span m=''3004520''>you</span> <span m=''3004670''>look</span>
  <span m=''3005390''>from</span> <span m=''3005670''>afar,</span> <span m=''3006330''>you</span>
  <span m=''3006460''>won''t</span> <span m=''3006640''>be</span> <span m=''3006740''>able</span>
  <span m=''3006920''>to</span> <span m=''3006990''>tell</span> <span m=''3007300''>that</span>
  <span m=''3007400''>there''s</span> <span m=''3008060''>three</span> <span m=''3008320''>edges</span>
  <span m=''3008600''>along</span> <span m=''3008840''>here,</span> <span m=''3009290''>because</span>
  <span m=''3009470''>they''re</span> <span m=''3009620''>right</span> <span m=''3009820''>on</span>
  <span m=''3009940''>top</span> <span m=''3010150''>of</span> <span m=''3010260''>each</span>
  <span m=''3010420''>other.</span> <span m=''3011630''>But</span> <span m=''3011830''>if</span>
  <span m=''3012000''>you,</span> <span m=''3012240''>sort</span> <span m=''3012470''>of,</span>
  <span m=''3012560''>imagine</span> <span m=''3012980''>zooming</span> <span m=''3013330''>in</span>
  <span m=''3013450''>infinitesimally</span> <span m=''3014860''>in</span> <span m=''3015020''>each</span>
  <span m=''3015210''>of</span> <span m=''3015270''>these</span> <span m=''3015450''>vertices,</span>
  <span m=''3016070''>it''s</span> <span m=''3016270''>going</span> <span m=''3016420''>to</span>
  <span m=''3016490''>be</span> <span m=''3017670''>whatever</span> <span m=''3017960''>the</span>
  <span m=''3018050''>heck</span> <span m=''3018260''>it</span> <span m=''3018340''>is.</span>
  </p><p><span m=''3024620''>So</span> <span m=''3024790''>you</span> <span m=''3024890''>remember</span>
  <span m=''3025240''>the</span> <span m=''3025350''>fact</span> <span m=''3025640''>that</span>
  <span m=''3025750''>right</span> <span m=''3025940''>here</span> <span m=''3026210''>there</span>
  <span m=''3026420''>are</span> <span m=''3026570''>four</span> <span m=''3026860''>vertices.</span>
  <span m=''3027440''>And</span> <span m=''3027550''>this</span> <span m=''3027700''>is</span>
  <span m=''3027800''>how</span> <span m=''3027930''>they''re</span> <span m=''3028040''>connected</span>
  <span m=''3028450''>to</span> <span m=''3028530''>incident</span> <span m=''3028880''>edges.</span>
  <span m=''3029320''>There''s</span> <span m=''3029610''>actually</span> <span m=''3029910''>three</span>
  <span m=''3030130''>edges</span> <span m=''3030420''>here,</span> <span m=''3031290''>and</span>
  <span m=''3031930''>two</span> <span m=''3032130''>edges</span> <span m=''3032420''>here,</span>
  <span m=''3032780''>and</span> <span m=''3032880''>so</span> <span m=''3033030''>on.</span>
  <span m=''3036080''>So</span> <span m=''3036240''>that''s</span> <span m=''3036460''>how</span>
  <span m=''3036520''>you</span> <span m=''3036650''>describe</span> <span m=''3037160''>one</span>
  <span m=''3037340''>of</span> <span m=''3037430''>these,</span> <span m=''3038140''>we</span>
  <span m=''3038290''>call</span> <span m=''3038470''>them,</span> <span m=''3038600''>self-touching</span>
  <span m=''3043400''>linkages.</span> <span m=''3044890''>Because</span> <span m=''3045210''>the</span>
  <span m=''3045330''>edges</span> <span m=''3045790''>are</span> <span m=''3046230''>touching</span>
  <span m=''3046520''>each</span> <span m=''3046670''>other.</span> <span m=''3047822''>They''re</span>
  <span m=''3048270''>right</span> <span m=''3048480''>on</span> <span m=''3048590''>top</span>
  <span m=''3048800''>of</span> <span m=''3048870''>each</span> <span m=''3049040''>other.</span>
  </p><p><span m=''3051170''>Now</span> <span m=''3052700''>normally,</span> <span
  m=''3054420''>if</span> <span m=''3054570''>you</span> <span m=''3054710''>wanted</span>
  <span m=''3054950''>to</span> <span m=''3055020''>capture</span> <span m=''3055370''>this</span>
  <span m=''3055580''>notion</span> <span m=''3055850''>of</span> <span m=''3055930''>wiggling</span>
  <span m=''3056330''>a</span> <span m=''3056390''>little</span> <span m=''3056640''>bit,</span>
  <span m=''3057600''>we</span> <span m=''3057780''>could</span> <span m=''3057930''>define</span>
  <span m=''3058620''>the</span> <span m=''3058730''>idea</span> <span m=''3059100''>of</span>
  <span m=''3059200''>being</span> <span m=''3059400''>locked</span> <span m=''3060800''>within</span>
  <span m=''3061150''>epsilon.</span> <span m=''3065880''>So</span> <span m=''3067592''>a</span>
  <span m=''3067930''>configuration</span> <span m=''3068750''>is</span> <span m=''3068880''>locked</span>
  <span m=''3069150''>within</span> <span m=''3069350''>epsilon</span> <span m=''3070520''>if</span>
  <span m=''3070950''>it''s</span> <span m=''3071180''>impossible</span> <span m=''3076890''>to</span>
  <span m=''3077380''>get</span> <span m=''3078930''>farther</span> <span m=''3083440''>than</span>
  <span m=''3083660''>epsilon</span> <span m=''3086390''>in</span> <span m=''3086610''>configuration</span>
  <span m=''3087280''>space.</span> <span m=''3093290''>So</span> <span m=''3093560''>that''s</span>
  <span m=''3093840''>this</span> <span m=''3094050''>little</span> <span m=''3094310''>ball,</span>
  <span m=''3095500''>thinking</span> <span m=''3095770''>about</span> <span m=''3096140''>radius</span>
  <span m=''3096490''>epsilon</span> <span m=''3096910''>here.</span> </p><p><span
  m=''3098150''>And</span> <span m=''3098270''>if</span> <span m=''3098350''>you</span>
  <span m=''3098460''>can''t</span> <span m=''3098680''>get</span> <span m=''3098800''>outside</span>
  <span m=''3099150''>that</span> <span m=''3099320''>ball,</span> <span m=''3099700''>you
  have</span> <span m=''3100010''>some</span> <span m=''3100270''>weird</span> <span
  m=''3100510''>space</span> <span m=''3100900''>you</span> <span m=''3100930''>can</span>
  <span m=''3101040''>get</span> <span m=''3101230''>to.</span> <span m=''3101440''>But</span>
  <span m=''3101620''>if</span> <span m=''3101740''>it''s</span> <span m=''3101880''>bounded</span>
  <span m=''3102320''>by</span> <span m=''3103160''>a</span> <span m=''3103260''>ball</span>
  <span m=''3103480''>of</span> <span m=''3103570''>radius</span> <span m=''3103970''>epsilon</span>
  <span m=''3104480''>then</span> <span m=''3105800''>I</span> <span m=''3105940''>say</span>
  <span m=''3106290''>you''re</span> <span m=''3106470''>locked</span> <span m=''3106770''>within</span>
  <span m=''3106970''>epsilon.</span> <span m=''3107640''>And if</span> <span m=''3107790''>epsilon</span>
  <span m=''3108120''>is</span> <span m=''3108170''>small</span> <span m=''3108560''>that</span>
  <span m=''3108710''>really</span> <span m=''3108890''>means</span> <span m=''3109240''>there</span>
  <span m=''3109260''>are</span> <span m=''3109280''>other</span> <span m=''3109440''>things</span>
  <span m=''3109660''>you</span> <span m=''3109760''>can''t</span> <span m=''3109990''>get</span>
  <span m=''3110220''>to.</span> </p><p><span m=''3111650''>Well</span> <span m=''3111890''>as</span>
  <span m=''3111970''>soon</span> <span m=''3112170''>as</span> <span m=''3112270''>I</span>
  <span m=''3112330''>get</span> <span m=''3112490''>to</span> <span m=''3112560''>self-touching</span>
  <span m=''3113710''>I</span> <span m=''3113840''>can</span> <span m=''3114000''>actually</span>
  <span m=''3114270''>think</span> <span m=''3114460''>about</span> <span m=''3114770''>being</span>
  <span m=''3115380''>locked</span> <span m=''3116500''>within</span> <span m=''3116730''>epsilon</span>
  <span m=''3117090''>for</span> <span m=''3117190''>epsilon</span> <span m=''3117530''>equals</span>
  <span m=''3117810''>0,</span> <span m=''3123720''>also</span> <span m=''3124030''>known</span>
  <span m=''3124270''>as</span> <span m=''3124600''>being</span> <span m=''3124940''>rigid.</span>
  <span m=''3128070''>We''ve</span> <span m=''3128260''>already</span> <span m=''3128490''>talked</span>
  <span m=''3128790''>about</span> <span m=''3129040''>being</span> <span m=''3129210''>locked</span>
  <span m=''3129460''>within</span> <span m=''3129650''>0.</span> <span m=''3129880''>If</span>
  <span m=''3129950''>you</span> <span m=''3130050''>can''t</span> <span m=''3130270''>move</span>
  <span m=''3130470''>it</span> <span m=''3130520''>all,</span> <span m=''3131320''>that''s</span>
  <span m=''3131580''>rigid.</span> </p><p><span m=''3132560''>So</span> <span m=''3132710''>this</span>
  <span m=''3133000''>thing</span> <span m=''3133680''>could</span> <span m=''3133890''>actually</span>
  <span m=''3134190''>be</span> <span m=''3134330''>rigid.</span> <span m=''3134630''>Whereas</span>
  <span m=''3134850''>all</span> <span m=''3135190''>the</span> <span m=''3135290''>locked</span>
  <span m=''3135420''>trees,</span> <span m=''3136240''>they</span> <span m=''3136340''>can</span>
  <span m=''3136450''>never</span> <span m=''3136690''>be</span> <span m=''3136830''>rigid</span>
  <span m=''3137190''>because</span> <span m=''3137400''>I</span> <span m=''3137450''>don''t</span>
  <span m=''3137730''>want</span> <span m=''3137970''>them</span> <span m=''3138090''>to</span>
  <span m=''3138170''>really</span> <span m=''3138440''>touch.</span> <span m=''3138910''>This</span>
  <span m=''3139090''>is</span> <span m=''3139410''>an</span> <span m=''3139510''>analysis</span>
  <span m=''3140060''>tool.</span> <span m=''3140300''>I</span> <span m=''3140360''>don''t</span>
  <span m=''3140530''>like</span> <span m=''3140730''>trees</span> <span m=''3141040''>that</span>
  <span m=''3141100''>are self-touching.</span> <span m=''3141720''>It''s</span> <span
  m=''3141830''>kind</span> <span m=''3142030''>of</span> <span m=''3142780''>ugly</span>
  <span m=''3143150''>and</span> <span m=''3143270''>cheating.</span> </p><p><span
  m=''3146750''>And</span> <span m=''3146940''>so</span> <span m=''3147490''>real</span>
  <span m=''3147950''>trees,</span> <span m=''3148630''>non-self-touching</span> <span
  m=''3149050''>touching</span> <span m=''3149370''>trees</span> <span m=''3149740''>could</span>
  <span m=''3149880''>only</span> <span m=''3150170''>be</span> <span m=''3150290''>locked</span>
  <span m=''3150530''>within</span> <span m=''3150750''>some</span> <span m=''3150930''>positive</span>
  <span m=''3151310''>epsilon.</span> <span m=''3152400''>But</span> <span m=''3152660''>if</span>
  <span m=''3153020''>we</span> <span m=''3153230''>consider</span> <span m=''3153720''>for</span>
  <span m=''3153860''>the</span> <span m=''3153970''>moment</span> <span m=''3154360''>the</span>
  <span m=''3154440''>extreme</span> <span m=''3155030''>when</span> <span m=''3155150''>they''re</span>
  <span m=''3155310''>touching</span> <span m=''3156580''>then</span> <span m=''3156850''>we</span>
  <span m=''3156960''>could</span> <span m=''3157070''>hope</span> <span m=''3157240''>for</span>
  <span m=''3157350''>rigidity.</span> <span m=''3158110''>Rigidity</span> <span m=''3158380''>is</span>
  <span m=''3158650''>good</span> <span m=''3158880''>because</span> <span m=''3159080''>we</span>
  <span m=''3159230''>know</span> <span m=''3159360''>how</span> <span m=''3159500''>to</span>
  <span m=''3159580''>prove</span> <span m=''3159800''>things</span> <span m=''3160020''>are
  rigid.</span> <span m=''3160420''>We</span> <span m=''3160520''>know</span> <span
  m=''3160650''>how</span> <span m=''3160760''>to</span> <span m=''3160870''>test</span>
  <span m=''3161120''>things</span> <span m=''3161310''>are</span> <span m=''3161390''>rigid</span>
  <span m=''3161690''>in</span> <span m=''3161810''>two</span> <span m=''3161950''>dimensions.</span>
  <span m=''3163070''>It''s</span> <span m=''3163200''>pretty</span> <span m=''3163420''>easy.</span>
  </p><p><span m=''3164590''>We</span> <span m=''3164700''>could</span> <span m=''3164860''>test</span>
  <span m=''3165390''>is it</span> <span m=''3165640''>infinitesimally</span> <span
  m=''3166360''>rigid?</span> <span m=''3166620''>If</span> <span m=''3166720''>it''s</span>
  <span m=''3166820''>infinitesimally</span> <span m=''3167350''>rigid</span> <span
  m=''3167690''>we</span> <span m=''3167780''>know</span> <span m=''3167900''>it''s</span>
  <span m=''3168020''>rigid.</span> </p><p><span m=''3170770''>It''s</span> <span
  m=''3170940''>a</span> <span m=''3170990''>little</span> <span m=''3171240''>bit</span>
  <span m=''3171410''>trickier</span> <span m=''3173380''>because</span> <span m=''3175150''>we</span>
  <span m=''3175280''>have</span> <span m=''3175470''>to</span> <span m=''3175600''>represent</span>
  <span m=''3176100''>the</span> <span m=''3176190''>non-crossing</span> <span m=''3177180''>constraints.</span>
  <span m=''3178100''>And</span> <span m=''3178260''>that''s</span> <span m=''3178460''>what</span>
  <span m=''3178570''>these</span> <span m=''3178740''>purple</span> <span m=''3179080''>edges</span>
  <span m=''3179380''>do.</span> <span m=''3180650''>So</span> <span m=''3180980''>the</span>
  <span m=''3181140''>idea</span> <span m=''3181460''>is,</span> <span m=''3181710''>well</span>
  <span m=''3184430''>I</span> <span m=''3184530''>definitely</span> <span m=''3184830''>want</span>
  <span m=''3184970''>to</span> <span m=''3185030''>preserve</span> <span m=''3185370''>the</span>
  <span m=''3185450''>lengths</span> <span m=''3185700''>of</span> <span m=''3185740''>these</span>
  <span m=''3185900''>edges.</span> <span m=''3186780''>I''m</span> <span m=''3186970''>not</span>
  <span m=''3187140''>interested</span> <span m=''3187500''>in</span> <span m=''3187580''>expansive</span>
  <span m=''3188060''>motions,</span> <span m=''3188490''>because</span> <span m=''3188640''>that''s</span>
  <span m=''3188870''>a</span> <span m=''3188940''>subset</span> <span m=''3189630''>of</span>
  <span m=''3189790''>possible</span> <span m=''3190210''>motions.</span> </p><p><span
  m=''3190770''>But</span> <span m=''3190900''>I</span> <span m=''3190970''>do</span>
  <span m=''3191230''>know</span> <span m=''3192400''>that</span> <span m=''3192640''>this</span>
  <span m=''3192870''>vertex</span> <span m=''3193810''>should</span> <span m=''3194050''>move</span>
  <span m=''3194380''>away</span> <span m=''3194860''>from</span> <span m=''3195050''>this</span>
  <span m=''3195230''>edge,</span> <span m=''3195500''>or</span> <span m=''3195700''>stay</span>
  <span m=''3195960''>on</span> <span m=''3196100''>the</span> <span m=''3196230''>edge.</span>
  <span m=''3196530''>It''s</span> <span m=''3196940''>not</span> <span m=''3197160''>allowed</span>
  <span m=''3197450''>to</span> <span m=''3197520''>go</span> <span m=''3197670''>to</span>
  <span m=''3197730''>the</span> <span m=''3197880''>other</span> <span m=''3198040''>side</span>
  <span m=''3198300''>of</span> <span m=''3198370''>the</span> <span m=''3198510''>edge.</span>
  <span m=''3199610''>So</span> <span m=''3199700''>I</span> <span m=''3199840''>imagine</span>
  <span m=''3200270''>there''s</span> <span m=''3200450''>a</span> <span m=''3200510''>little</span>
  <span m=''3200810''>tiny</span> <span m=''3201170''>strut</span> <span m=''3201590''>here.</span>
  <span m=''3201850''>It''s</span> <span m=''3201990''>of</span> <span m=''3202130''>infinitesimal</span>
  <span m=''3202820''>length</span> <span m=''3203080''>right</span> <span m=''3203260''>now.</span>
  </p><p><span m=''3203840''>It</span> <span m=''3204000''>can</span> <span m=''3204130''>get</span>
  <span m=''3204310''>longer,</span> <span m=''3205360''>but</span> <span m=''3205500''>it</span>
  <span m=''3205560''>has</span> <span m=''3205790''>to</span> <span m=''3205870''>get</span>
  <span m=''3206000''>longer</span> <span m=''3206300''>in</span> <span m=''3206380''>that</span>
  <span m=''3206570''>direction.</span> <span m=''3206890''>You</span> <span m=''3206940''>have</span>
  <span m=''3207080''>to</span> <span m=''3207180''>move</span> <span m=''3207340''>away--</span>
  <span m=''3208020''>you have</span> <span m=''3208140''>to</span> <span m=''3208250''>stay</span>
  <span m=''3208590''>on</span> <span m=''3208740''>the</span> <span m=''3208850''>right</span>
  <span m=''3209090''>side</span> <span m=''3209420''>of</span> <span m=''3209520''>this</span>
  <span m=''3209720''>edge.</span> <span m=''3210560''>And you have</span> <span m=''3210650''>to</span>
  <span m=''3210740''>stay</span> <span m=''3210980''>on</span> <span m=''3211060''>the</span>
  <span m=''3211130''>left</span> <span m=''3211350''>side</span> <span m=''3211570''>of</span>
  <span m=''3211630''>this</span> <span m=''3211820''>edge.</span> </p><p><span m=''3212550''>It
  turns</span> <span m=''3212790''>out</span> <span m=''3213010''>you</span> <span
  m=''3213130''>really</span> <span m=''3213360''>can</span> <span m=''3213560''>represent</span>
  <span m=''3214010''>that</span> <span m=''3214820''>by a</span> <span m=''3215210''>strut.</span>
  <span m=''3216170''>It''s</span> <span m=''3216330''>now a</span> <span m=''3216510''>strut</span>
  <span m=''3216770''>between a</span> <span m=''3217080''>vertex</span> <span m=''3217460''>and</span>
  <span m=''3217550''>an</span> <span m=''3217690''>edge,</span> <span m=''3218150''>because</span>
  <span m=''3218330''>this</span> <span m=''3218500''>guy</span> <span m=''3218670''>can</span>
  <span m=''3218900''>slide</span> <span m=''3219200''>along</span> <span m=''3219420''>the</span>
  <span m=''3219530''>edge,</span> <span m=''3219760''>or</span> <span m=''3219830''>move</span>
  <span m=''3220020''>away</span> <span m=''3220230''>from</span> <span m=''3220440''>it.</span>
  <span m=''3221730''>But</span> <span m=''3222500''>it''s</span> <span m=''3222670''>a</span>
  <span m=''3222730''>strut.</span> <span m=''3223680''>And</span> <span m=''3223890''>you</span>
  <span m=''3224040''>can</span> <span m=''3224500''>think</span> <span m=''3224760''>of</span>
  <span m=''3224840''>this</span> <span m=''3225010''>as</span> <span m=''3225140''>a</span>
  <span m=''3225210''>tensegrity,</span> <span m=''3225840''>all</span> <span m=''3226130''>the</span>
  <span m=''3226230''>usual</span> <span m=''3226530''>tensegrity</span> <span m=''3227080''>theory</span>
  <span m=''3227310''>applies.</span> <span m=''3228170''>You</span> <span m=''3228320''>can</span>
  <span m=''3228430''>define</span> <span m=''3228810''>equilibrium</span> <span m=''3229250''>stresses,</span>
  <span m=''3230370''>polyhedral</span> <span m=''3230850''>liftings,</span> <span
  m=''3232690''>infinitesimal</span> <span m=''3233600''>rigidity.</span> </p><p><span
  m=''3234590''>And</span> <span m=''3234850''>so</span> <span m=''3236330''>what''s</span>
  <span m=''3236660''>actually</span> <span m=''3237180''>drawn</span> <span m=''3237520''>here--</span>
  <span m=''3239000''>you</span> <span m=''3239170''>should</span> <span m=''3239480''>look</span>
  <span m=''3239690''>at</span> <span m=''3239780''>the</span> <span m=''3239860''>book</span>
  <span m=''3240110''>for</span> <span m=''3240230''>more</span> <span m=''3240390''>details.</span>
  <span m=''3240800''>I</span> <span m=''3240850''>don''t</span> <span m=''3240970''>want</span>
  <span m=''3241080''>to</span> <span m=''3241130''>go</span> <span m=''3241240''>into</span>
  <span m=''3241460''>details</span> <span m=''3242000''>on</span> <span m=''3242070''>this.</span>
  <span m=''3242300''>But</span> <span m=''3243450''>originally</span> <span m=''3243890''>the</span>
  <span m=''3244000''>state</span> <span m=''3244270''>of</span> <span m=''3244310''>the</span>
  <span m=''3244460''>art</span> <span m=''3244700''>for</span> <span m=''3244800''>proving</span>
  <span m=''3245180''>something</span> <span m=''3245470''>like</span> <span m=''3245630''>this</span>
  <span m=''3245810''>is</span> <span m=''3245930''>locked</span> <span m=''3246310''>is</span>
  <span m=''3247350''>you</span> <span m=''3247540''>basically</span> <span m=''3248090''>give--</span>
  <span m=''3248880''>you</span> <span m=''3249000''>show</span> <span m=''3249410''>an</span>
  <span m=''3249510''>equilibrium</span> <span m=''3250030''>stress</span> <span m=''3250970''>that</span>
  <span m=''3251130''>is</span> <span m=''3251710''>positive</span> <span m=''3252340''>on</span>
  <span m=''3252470''>all</span> <span m=''3252620''>the</span> <span m=''3252680''>struts.</span>
  <span m=''3253850''>We</span> <span m=''3254010''>know</span> <span m=''3254360''>that</span>
  <span m=''3254510''>if</span> <span m=''3254630''>you</span> <span m=''3254730''>find</span>
  <span m=''3254940''>a</span> <span m=''3254990''>stress</span> <span m=''3255300''>that''s</span>
  <span m=''3255380''>positive</span> <span m=''3255790''>on</span> <span m=''3255930''>all</span>
  <span m=''3256110''>struts</span> <span m=''3256490''>than</span> <span m=''3256630''>all</span>
  <span m=''3256830''>the</span> <span m=''3256910''>struts</span> <span m=''3257230''>in</span>
  <span m=''3257330''>fact</span> <span m=''3257640''>must</span> <span m=''3257930''>act</span>
  <span m=''3258210''>as</span> <span m=''3258330''>bars.</span> </p><p><span m=''3259670''>What</span>
  <span m=''3259930''>that</span> <span m=''3260190''>means</span> <span m=''3260750''>is</span>
  <span m=''3260980''>that</span> <span m=''3262200''>this</span> <span m=''3262470''>length,</span>
  <span m=''3262800''>which</span> <span m=''3262970''>is</span> <span m=''3263070''>currently</span>
  <span m=''3263440''>0,</span> <span m=''3264350''>must</span> <span m=''3264730''>stay</span>
  <span m=''3265060''>0.</span> <span m=''3266370''>Therefore</span> <span m=''3266710''>this</span>
  <span m=''3266940''>vertex</span> <span m=''3267300''>is</span> <span m=''3267530''>actually</span>
  <span m=''3267890''>pinned</span> <span m=''3269270''>because</span> <span m=''3269570''>it</span>
  <span m=''3269650''>has</span> <span m=''3269820''>to</span> <span m=''3269910''>both</span>
  <span m=''3270220''>be</span> <span m=''3270350''>on</span> <span m=''3270490''>this</span>
  <span m=''3270680''>edge</span> <span m=''3271060''>and</span> <span m=''3271330''>be</span>
  <span m=''3271450''>on</span> <span m=''3271570''>this</span> <span m=''3271670''>edge.</span>
  <span m=''3272020''>That''s</span> <span m=''3272240''>what</span> <span m=''3272360''>a</span>
  <span m=''3272400''>0</span> <span m=''3272900''>length</span> <span m=''3273190''>bar</span>
  <span m=''3273510''>here</span> <span m=''3274210''>and</span> <span m=''3274400''>here</span>
  <span m=''3274610''>would</span> <span m=''3274760''>mean.</span> <span m=''3275010''>It</span>
  <span m=''3275190''>really</span> <span m=''3275450''>has</span> <span m=''3275620''>to</span>
  <span m=''3275710''>be</span> <span m=''3275840''>right</span> <span m=''3276040''>here.</span>
  <span m=''3276250''>It can''t</span> <span m=''3276510''>move</span> <span m=''3276690''>it</span>
  <span m=''3276780''>all.</span> <span m=''3277580''>And</span> <span m=''3277680''>therefore</span>
  <span m=''3277920''>this</span> <span m=''3278070''>whole</span> <span m=''3278250''>thing</span>
  <span m=''3278780''>is</span> <span m=''3278960''>rigid,</span> <span m=''3279860''>and</span>
  <span m=''3280050''>nothing</span> <span m=''3280340''>moves.</span> <span m=''3287480''>Clear?</span>
  </p><p><span m=''3288730''>So</span> <span m=''3288880''>we</span> <span m=''3288980''>can</span>
  <span m=''3289060''>use</span> <span m=''3289270''>all</span> <span m=''3289390''>the</span>
  <span m=''3289480''>tensegrity</span> <span m=''3290230''>stuff</span> <span m=''3290810''>to</span>
  <span m=''3291030''>prove</span> <span m=''3291540''>that</span> <span m=''3291820''>when</span>
  <span m=''3292010''>this</span> <span m=''3292190''>thing</span> <span m=''3292350''>is</span>
  <span m=''3292450''>actually</span> <span m=''3292790''>self-touching,</span> <span
  m=''3293420''>and</span> <span m=''3293490''>all</span> <span m=''3293610''>these</span>
  <span m=''3293820''>distances</span> <span m=''3294260''>are</span> <span m=''3294340''>0,</span>
  <span m=''3295270''>it is</span> <span m=''3295630''>rigid.</span> <span m=''3297020''>But</span>
  <span m=''3297870''>so</span> <span m=''3298150''>what?</span> <span m=''3298510''>Who</span>
  <span m=''3298760''>cares</span> <span m=''3299150''>about</span> <span m=''3299620''>the</span>
  <span m=''3299700''>self-touching</span> <span m=''3300330''>thing</span> <span
  m=''3300560''>being</span> <span m=''3300830''>rigid?</span> <span m=''3301890''>It''s</span>
  <span m=''3302030''>nice,</span> <span m=''3302700''>but</span> <span m=''3302830''>what</span>
  <span m=''3302970''>I</span> <span m=''3303010''>really</span> <span m=''3303330''>care</span>
  <span m=''3303550''>about</span> <span m=''3303790''>is</span> <span m=''3304020''>the</span>
  <span m=''3304100''>non-self-touching</span> <span m=''3305470''>configurations</span>
  <span m=''3306150''>are</span> <span m=''3306240''>locked</span> <span m=''3306520''>within</span>
  <span m=''3306720''>epsilon,</span> <span m=''3307600''>for</span> <span m=''3307710''>some</span>
  <span m=''3307870''>tiny</span> <span m=''3308170''>epsilon.</span> </p><p><span
  m=''3309540''>Well</span> <span m=''3309790''>good</span> <span m=''3309980''>news.</span>
  <span m=''3315800''>Rigidity</span> <span m=''3319160''>of</span> <span m=''3319590''>the</span>
  <span m=''3319780''>self-touching</span> <span m=''3320370''>configuration</span>
  <span m=''3321120''>implies</span> <span m=''3322870''>what''s</span> <span m=''3323220''>called</span>
  <span m=''3324350''>strongly</span> <span m=''3325020''>locked,</span> <span m=''3328620''>yet</span>
  <span m=''3328820''>another</span> <span m=''3329130''>term</span> <span m=''3329900''>which</span>
  <span m=''3330100''>I</span> <span m=''3330150''>need</span> <span m=''3330320''>to</span>
  <span m=''3330420''>define.</span> <span m=''3332690''>Strongly</span> <span m=''3333170''>locked</span>
  <span m=''3340260''>means</span> <span m=''3340790''>that</span> <span m=''3342380''>sufficiently</span>
  <span m=''3343160''>small,</span> <span m=''3345240''>sufficiently</span> <span
  m=''3350830''>small</span> <span m=''3351240''>perturbations</span> <span m=''3358590''>of
  the</span> <span m=''3358920''>linkage,</span> <span m=''3361755''>or</span> <span
  m=''3362190''>I</span> <span m=''3362370''>should</span> <span m=''3362560''>say</span>
  <span m=''3362750''>of</span> <span m=''3362880''>the</span> <span m=''3363050''>linkage</span>
  <span m=''3363560''>configuration,</span> <span m=''3375140''>are</span> <span m=''3375360''>locked</span>
  <span m=''3376960''>within</span> <span m=''3377270''>epsilon</span> <span m=''3381060''>for</span>
  <span m=''3381380''>any</span> <span m=''3381580''>epsilon.</span> </p><p><span
  m=''3386170''>This</span> <span m=''3386380''>is</span> <span m=''3386480''>exactly</span>
  <span m=''3387110''>the</span> <span m=''3387210''>property</span> <span m=''3387650''>I</span>
  <span m=''3387690''>wanted</span> <span m=''3387960''>to</span> <span m=''3388000''>formalize,</span>
  <span m=''3390420''>saying</span> <span m=''3390760''>that</span> <span m=''3392120''>if</span>
  <span m=''3392300''>you</span> <span m=''3392420''>draw</span> <span m=''3392690''>the</span>
  <span m=''3392800''>example</span> <span m=''3393330''>tighter</span> <span m=''3394710''>it</span>
  <span m=''3394860''>can</span> <span m=''3394990''>move</span> <span m=''3395200''>less.</span>
  <span m=''3396660''>For</span> <span m=''3396880''>any</span> <span m=''3397100''>epsilon,</span>
  <span m=''3398180''>we</span> <span m=''3398400''>want</span> <span m=''3398580''>to</span>
  <span m=''3398640''>say</span> <span m=''3398900''>you</span> <span m=''3399100''>can</span>
  <span m=''3399200''>only</span> <span m=''3399390''>move</span> <span m=''3399610''>within</span>
  <span m=''3399860''>epsilon,</span> <span m=''3402390''>there''s</span> <span m=''3402600''>some</span>
  <span m=''3402840''>notion</span> <span m=''3403150''>of</span> <span m=''3403230''>sufficiently</span>
  <span m=''3403810''>small</span> <span m=''3405100''>such</span> <span m=''3405390''>that</span>
  <span m=''3405520''>if</span> <span m=''3405650''>I</span> <span m=''3405730''>take</span>
  <span m=''3406020''>this</span> <span m=''3406200''>example</span> <span m=''3407640''>and</span>
  <span m=''3407960''>imagine</span> <span m=''3408400''>currently</span> <span m=''3408890''>all</span>
  <span m=''3409060''>the</span> <span m=''3409120''>vertices</span> <span m=''3409500''>are</span>
  <span m=''3409570''>on</span> <span m=''3409660''>top</span> <span m=''3409900''>of</span>
  <span m=''3410020''>each</span> <span m=''3410180''>other.</span> <span m=''3410930''>But</span>
  <span m=''3410940''>now</span> <span m=''3411070''>I</span> <span m=''3411170''>perturb</span>
  <span m=''3411610''>it</span> <span m=''3411660''>a</span> <span m=''3411690''>little</span>
  <span m=''3411910''>bit,</span> <span m=''3412270''>which</span> <span m=''3412360''>involves</span>
  <span m=''3412900''>changing</span> <span m=''3413460''>not</span> <span m=''3413680''>only</span>
  <span m=''3413870''>the</span> <span m=''3413950''>vertex</span> <span m=''3414310''>coordinates,</span>
  <span m=''3414720''>but</span> <span m=''3414870''>also</span> <span m=''3415150''>the</span>
  <span m=''3415290''>edge</span> <span m=''3415480''>lengths--</span> <span m=''3416080''>but</span>
  <span m=''3416260''>a</span> <span m=''3416360''>tiny</span> <span m=''3416780''>amount,</span>
  <span m=''3417640''>some</span> <span m=''3417870''>delta</span> <span m=''3418730''>that''s</span>
  <span m=''3418900''>a</span> <span m=''3418950''>function</span> <span m=''3419290''>of</span>
  <span m=''3419370''>epsilon.</span> </p><p><span m=''3421740''>Whatever</span> <span
  m=''3422160''>epsilon</span> <span m=''3422500''>you</span> <span m=''3422620''>choose,</span>
  <span m=''3423180''>there''s</span> <span m=''3423360''>a</span> <span m=''3423400''>very</span>
  <span m=''3423740''>small</span> <span m=''3424500''>disk</span> <span m=''3424830''>I</span>
  <span m=''3424890''>can</span> <span m=''3425040''>draw</span> <span m=''3425280''>like</span>
  <span m=''3425500''>this,</span> <span m=''3425870''>such</span> <span m=''3426000''>that
  as</span> <span m=''3426210''>long</span> <span m=''3426420''>as</span> <span m=''3426520''>all</span>
  <span m=''3426710''>the</span> <span m=''3426780''>vertices</span> <span m=''3427180''>stay</span>
  <span m=''3427370''>within</span> <span m=''3427610''>that</span> <span m=''3427800''>disk</span>
  <span m=''3429600''>your</span> <span m=''3430090''>example</span> <span m=''3430730''>will</span>
  <span m=''3430910''>be</span> <span m=''3431050''>locked</span> <span m=''3431290''>within</span>
  <span m=''3431470''>epsilon.</span> <span m=''3433150''>This</span> <span m=''3433320''>is</span>
  <span m=''3433430''>great</span> <span m=''3433880''>because</span> <span m=''3434150''>it</span>
  <span m=''3434260''>lets</span> <span m=''3434490''>us</span> <span m=''3434600''>analyze</span>
  <span m=''3435090''>rigidity,</span> <span m=''3435670''>which</span> <span m=''3435870''>is</span>
  <span m=''3436040''>easy</span> <span m=''3437010''>for</span> <span m=''3437200''>self-touching</span>
  <span m=''3437820''>configurations,</span> <span m=''3438490''>which</span> <span
  m=''3438670''>are</span> <span m=''3438730''>not</span> <span m=''3438940''>interesting</span>
  <span m=''3439390''>in</span> <span m=''3439840''>some</span> <span m=''3440070''>sense.</span>
  <span m=''3440940''>But</span> <span m=''3441110''>we</span> <span m=''3441250''>get</span>
  <span m=''3441410''>to</span> <span m=''3441490''>conclude</span> <span m=''3442010''>something</span>
  <span m=''3442440''>about</span> <span m=''3443250''>the</span> <span m=''3443380''>perturbations</span>
  <span m=''3444200''>which</span> <span m=''3444470''>are</span> <span m=''3444830''>not</span>
  <span m=''3445160''>self-touching</span> <span m=''3445750''>and</span> <span m=''3445820''>therefore</span>
  <span m=''3446100''>nice.</span> <span m=''3446900''>And</span> <span m=''3447050''>we</span>
  <span m=''3447150''>get</span> <span m=''3447330''>the</span> <span m=''3447410''>property</span>
  <span m=''3447790''>we</span> <span m=''3447870''>want,</span> <span m=''3448190''>that</span>
  <span m=''3448310''>you''re</span> <span m=''3448440''>locked</span> <span m=''3448700''>within</span>
  <span m=''3448890''>epsilon</span> <span m=''3449690''>for</span> <span m=''3449870''>any</span>
  <span m=''3450030''>epsilon</span> <span m=''3450370''>you</span> <span m=''3450470''>want.</span>
  <span m=''3450720''>You</span> <span m=''3450790''>just</span> <span m=''3450960''>draw
  it</span> <span m=''3451140''>tighter</span> <span m=''3452410''>you''ll</span>
  <span m=''3452640''>be</span> <span m=''3452780''>locked</span> <span m=''3453080''>within</span>
  <span m=''3453210''>a</span> <span m=''3453280''>smaller</span> <span m=''3453670''>epsilon.</span>
  </p><p><span m=''3457540''>So</span> <span m=''3457850''>this</span> <span m=''3458060''>is</span>
  <span m=''3458140''>pretty</span> <span m=''3458340''>cool.</span> <span m=''3459400''>And</span>
  <span m=''3460150''>I</span> <span m=''3460260''>didn''t</span> <span m=''3460450''>defined</span>
  <span m=''3460740''>perturbation.</span> <span m=''3461900''>But</span> <span m=''3462010''>I</span>
  <span m=''3462100''>just</span> <span m=''3462360''>mean</span> <span m=''3463720''>every</span>
  <span m=''3466270''>vertex</span> <span m=''3469620''>stays</span> <span m=''3470130''>within</span>
  <span m=''3472640''>a</span> <span m=''3472730''>radius</span> <span m=''3474220''>delta</span>
  <span m=''3474910''>disk.</span> <span m=''3479520''>And</span> <span m=''3479810''>sufficiently</span>
  <span m=''3480280''>small</span> <span m=''3480680''>here</span> <span m=''3481070''>is</span>
  <span m=''3481960''>delta,</span> <span m=''3483412''>which is a</span> <span m=''3483900''>function</span>
  <span m=''3484180''>of</span> <span m=''3484240''>epsilon.</span> </p><p><span m=''3489890''>So</span>
  <span m=''3490060''>this</span> <span m=''3490270''>is</span> <span m=''3490370''>pretty</span>
  <span m=''3490600''>cool.</span> <span m=''3492130''>And it</span> <span m=''3492290''>turns</span>
  <span m=''3492550''>out</span> <span m=''3492700''>also--</span> <span m=''3493570''>this</span>
  <span m=''3493710''>is</span> <span m=''3493800''>proved</span> <span m=''3494110''>much</span>
  <span m=''3494380''>later--</span> <span m=''3494970''>these</span> <span m=''3495150''>results</span>
  <span m=''3495480''>are</span> <span m=''3495590''>like</span> <span m=''3495860''>2002.</span>
  <span m=''3496570''>And</span> <span m=''3496650''>then</span> <span m=''3496790''>2006</span>
  <span m=''3499960''>proved</span> <span m=''3500290''>that</span> <span m=''3500860''>if</span>
  <span m=''3501020''>you</span> <span m=''3501090''>take</span> <span m=''3501320''>any</span>
  <span m=''3501580''>self-touching</span> <span m=''3502160''>configuration,</span>
  <span m=''3502860''>which</span> <span m=''3503260''>is</span> <span m=''3503430''>like</span>
  <span m=''3503640''>this,</span> <span m=''3503900''>you</span> <span m=''3504650''>specify</span>
  <span m=''3505050''>the</span> <span m=''3505150''>geometry</span> <span m=''3505630''>where</span>
  <span m=''3505750''>things</span> <span m=''3506050''>are</span> <span m=''3506160''>all</span>
  <span m=''3506410''>on</span> <span m=''3506590''>top</span> <span m=''3506770''>of</span>
  <span m=''3506870''>each</span> <span m=''3507040''>other.</span> <span m=''3507580''>And</span>
  <span m=''3507830''>then</span> <span m=''3508030''>you''d</span> <span m=''3508530''>say</span>
  <span m=''3508800''>what</span> <span m=''3508990''>you</span> <span m=''3509100''>want</span>
  <span m=''3509470''>every</span> <span m=''3509670''>vertex</span> <span m=''3510100''>to
  look</span> <span m=''3510320''>like.</span> <span m=''3511130''>It turns</span>
  <span m=''3511340''>out</span> <span m=''3511490''>there</span> <span m=''3511610''>really</span>
  <span m=''3511970''>is</span> <span m=''3512410''>a</span> <span m=''3512490''>valid</span>
  <span m=''3512980''>perturbation</span> <span m=''3514660''>that</span> <span m=''3515980''>preserves</span>
  <span m=''3516380''>that</span> <span m=''3516530''>combinatorial</span> <span m=''3517080''>structure</span>
  <span m=''3518040''>and</span> <span m=''3518220''>is</span> <span m=''3518310''>arbitrarily</span>
  <span m=''3518860''>small.</span> </p><p><span m=''3520010''>So</span> <span m=''3520120''>here,</span>
  <span m=''3520330''>of</span> <span m=''3520400''>course,</span> <span m=''3520620''>I''ve</span>
  <span m=''3520740''>drawn</span> <span m=''3521070''>it</span> <span m=''3521220''>so</span>
  <span m=''3521400''>it''s</span> <span m=''3521530''>clear.</span> <span m=''3521820''>You</span>
  <span m=''3521970''>can</span> <span m=''3522210''>perturb</span> <span m=''3522580''>things.</span>
  <span m=''3523610''>And</span> <span m=''3523890''>I</span> <span m=''3523970''>changed</span>
  <span m=''3524250''>the</span> <span m=''3524330''>edge</span> <span m=''3524490''>lengths</span>
  <span m=''3524710''>a</span> <span m=''3524750''>little</span> <span m=''3524980''>bit.</span>
  <span m=''3525290''>But</span> <span m=''3526290''>I</span> <span m=''3526450''>can</span>
  <span m=''3526620''>actually</span> <span m=''3527040''>realize</span> <span m=''3527650''>this</span>
  <span m=''3528640''>combinatorial</span> <span m=''3529190''>structure.</span> <span
  m=''3529570''>It turns</span> <span m=''3529780''>out</span> <span m=''3529860''>that''s</span>
  <span m=''3530050''>always</span> <span m=''3530310''>possible.</span> <span m=''3532360''>So</span>
  <span m=''3532460''>you can</span> <span m=''3532530''>take</span> <span m=''3532710''>any</span>
  <span m=''3532960''>self-touching</span> <span m=''3533520''>linkage,</span> <span
  m=''3534110''>you</span> <span m=''3534300''>can</span> <span m=''3534440''>perturb</span>
  <span m=''3534850''>it</span> <span m=''3535040''>so it''s</span> <span m=''3535230''>not</span>
  <span m=''3535430''>self-touching,</span> <span m=''3536040''>and</span> <span m=''3536210''>it
  is</span> <span m=''3536490''>arbitrarily</span> <span m=''3537290''>locked</span>
  <span m=''3538420''>within</span> <span m=''3538550''>epsilon.</span> </p><p><span
  m=''3542680''>And</span> <span m=''3544160''>the</span> <span m=''3544290''>way</span>
  <span m=''3544440''>you</span> <span m=''3544570''>prove</span> <span m=''3544850''>it,</span>
  <span m=''3545780''>or</span> <span m=''3545940''>one</span> <span m=''3546160''>way</span>
  <span m=''3546300''>to</span> <span m=''3546390''>prove</span> <span m=''3546790''>that</span>
  <span m=''3546890''>something</span> <span m=''3547230''>is</span> <span m=''3547330''>rigid,</span>
  <span m=''3548240''>is</span> <span m=''3548460''>to</span> <span m=''3548570''>say</span>
  <span m=''3548910''>well</span> <span m=''3549210''>this</span> <span m=''3549320''>proof</span>
  <span m=''3549500''>is</span> <span m=''3549630''>infinitesimally</span> <span m=''3550320''>rigid</span>
  <span m=''3551170''>by</span> <span m=''3551300''>constructing</span> <span m=''3551930''>an</span>
  <span m=''3552010''>equilibrium</span> <span m=''3552520''>stress</span> <span m=''3552820''>that''s</span>
  <span m=''3553120''>positive</span> <span m=''3553630''>on</span> <span m=''3553740''>all</span>
  <span m=''3553900''>these</span> <span m=''3554070''>0</span> <span m=''3554310''>length</span>
  <span m=''3554540''>struts.</span> <span m=''3555345''>As</span> <span m=''3555600''>long
  as</span> <span m=''3555890''>it''s</span> <span m=''3555990''>positive</span> <span
  m=''3556410''>all</span> <span m=''3556800''>those</span> <span m=''3557020''>0</span>
  <span m=''3557100''>length</span> <span m=''3557270''>struts</span> <span m=''3557620''>you
  know</span> <span m=''3559280''>that</span> <span m=''3559595''>they''re</span>
  <span m=''3560380''>effectively</span> <span m=''3560880''>bars.</span> <span m=''3561860''>Usually</span>
  <span m=''3562450''>once</span> <span m=''3562740''>they''re</span> <span m=''3562880''>bars</span>
  <span m=''3563290''>it''s</span> <span m=''3563410''>really</span> <span m=''3563660''>obvious</span>
  <span m=''3564310''>that</span> <span m=''3564500''>the</span> <span m=''3564590''>thing</span>
  <span m=''3564770''>is</span> <span m=''3564880''>rigid</span> <span m=''3565270''>because</span>
  <span m=''3565480''>it</span> <span m=''3565880''>pins</span> <span m=''3566230''>vertices</span>
  <span m=''3566990''>into</span> <span m=''3567200''>corners.</span> <span m=''3568570''>Then</span>
  <span m=''3568660''>you know that</span> <span m=''3569100''>the</span> <span m=''3569190''>whole</span>
  <span m=''3569360''>thing</span> <span m=''3569600''>is</span> <span m=''3569790''>infinitesimally</span>
  <span m=''3570370''>rigid,</span> <span m=''3570640''>therefore</span> <span m=''3570930''>it''s</span>
  <span m=''3571040''>rigid,</span> <span m=''3571700''>therefore it''s</span> <span
  m=''3572110''>strongly</span> <span m=''3572500''>locked.</span> </p><p><span m=''3573850''>And</span>
  <span m=''3574120''>you</span> <span m=''3574230''>could</span> <span m=''3574380''>see</span>
  <span m=''3574680''>some</span> <span m=''3574850''>examples</span> <span m=''3575290''>of</span>
  <span m=''3575380''>doing</span> <span m=''3575580''>that</span> <span m=''3575800''>in</span>
  <span m=''3575900''>the</span> <span m=''3575980''>book.</span> <span m=''3576520''>But</span>
  <span m=''3576650''>this</span> <span m=''3576800''>is</span> <span m=''3576920''>no</span>
  <span m=''3577080''>longer</span> <span m=''3577380''>the</span> <span m=''3577470''>state</span>
  <span m=''3577700''>of</span> <span m=''3577760''>the</span> <span m=''3577900''>art.</span>
  <span m=''3578130''>There are now</span> <span m=''3578460''>easier</span> <span
  m=''3578800''>ways</span> <span m=''3579150''>to</span> <span m=''3579230''>prove</span>
  <span m=''3579500''>that</span> <span m=''3579580''>trees</span> <span m=''3579920''>are</span>
  <span m=''3580020''>locked--</span> <span m=''3580350''>some</span> <span m=''3580560''>trees.</span>
  <span m=''3581140''>It doesn''t</span> <span m=''3581410''>always</span> <span m=''3581620''>work.</span>
  <span m=''3581890''>Of</span> <span m=''3581970''>course,</span> <span m=''3582200''>it</span>
  <span m=''3582260''>might</span> <span m=''3582420''>be</span> <span m=''3582510''>infinitesimally</span>
  <span m=''3583090''>flexible.</span> <span m=''3584060''>Lots</span> <span m=''3584250''>of</span>
  <span m=''3584330''>things</span> <span m=''3584540''>could</span> <span m=''3584690''>fail.</span>
  </p><p><span m=''3586360''>But</span> <span m=''3586570''>if</span> <span m=''3586710''>it</span>
  <span m=''3587040''>succeeds</span> <span m=''3587520''>in</span> <span m=''3587600''>proving</span>
  <span m=''3587880''>something</span> <span m=''3588210''>is</span> <span m=''3588300''>rigid,</span>
  <span m=''3589240''>then</span> <span m=''3589560''>you know it''s</span> <span
  m=''3589920''>strongly</span> <span m=''3590280''>locked</span> <span m=''3590570''>and</span>
  <span m=''3590610''>you''re</span> <span m=''3590710''>happy.</span> <span m=''3594350''>So</span>
  <span m=''3594400''>it''s</span> <span m=''3594510''>a</span> <span m=''3594560''>conservative</span>
  <span m=''3595150''>test,</span> <span m=''3595910''>you might</span> <span m=''3596100''>say.</span>
  <span m=''3596300''>It would be a cool</span> <span m=''3596740''>thing to</span>
  <span m=''3596920''>implement.</span> <span m=''3597710''>This</span> <span m=''3597820''>is</span>
  <span m=''3597920''>not</span> <span m=''3598110''>hard,</span> <span m=''3598245''>it''s</span>
  <span m=''3598380''>just</span> <span m=''3598590''>linear</span> <span m=''3598790''>programming.</span>
  </p><p><span m=''3602150''>But</span> <span m=''3604180''>there''s</span> <span
  m=''3604390''>a</span> <span m=''3604470''>cooler</span> <span m=''3604820''>way</span>
  <span m=''3605030''>that''s</span> <span m=''3605170''>even</span> <span m=''3605420''>more--</span>
  <span m=''3606800''>like</span> <span m=''3606930''>one</span> <span m=''3607110''>where</span>
  <span m=''3607300''>I can</span> <span m=''3607460''>really</span> <span m=''3607670''>draw</span>
  <span m=''3607850''>the</span> <span m=''3607960''>pictures</span> <span m=''3608380''>here,</span>
  <span m=''3608980''>you know</span> <span m=''3609240''>we had</span> <span m=''3609450''>to</span>
  <span m=''3609680''>draw</span> <span m=''3609920''>all</span> <span m=''3610010''>these</span>
  <span m=''3610450''>diagrams</span> <span m=''3611100''>and</span> <span m=''3611210''>figure</span>
  <span m=''3611440''>out</span> <span m=''3611570''>that</span> <span m=''3611690''>stress</span>
  <span m=''3612110''>positive</span> <span m=''3612610''>numbers</span> <span m=''3613000''>worked</span>
  <span m=''3613280''>on</span> <span m=''3613390''>all</span> <span m=''3613530''>these</span>
  <span m=''3613690''>edges,</span> <span m=''3614210''>and</span> <span m=''3615282''>eh,</span>
  <span m=''3616194''>it''s</span> <span m=''3616650''>tedious.</span> <span m=''3621080''>There''s</span>
  <span m=''3621250''>a</span> <span m=''3621310''>much</span> <span m=''3621550''>slicker</span>
  <span m=''3621880''>way.</span> </p><p><span m=''3633270''>And</span> <span m=''3635140''>for</span>
  <span m=''3635290''>whatever</span> <span m=''3635650''>reason,</span> <span m=''3636020''>they</span>
  <span m=''3636160''>have</span> <span m=''3636320''>become</span> <span m=''3637040''>known</span>
  <span m=''3637320''>as</span> <span m=''3637670''>the</span> <span m=''3637820''>rules.</span>
  <span m=''3638780''>There</span> <span m=''3638890''>are</span> <span m=''3638930''>two</span>
  <span m=''3639130''>of</span> <span m=''3639230''>them.</span> <span m=''3640160''>Although</span>
  <span m=''3640650''>we''ve</span> <span m=''3640970''>tried</span> <span m=''3641230''>to</span>
  <span m=''3641290''>come</span> <span m=''3641480''>up</span> <span m=''3641580''>with</span>
  <span m=''3641660''>various</span> <span m=''3641940''>rule</span> <span m=''3642110''>threes,</span>
  <span m=''3644480''>the</span> <span m=''3644800''>ones</span> <span m=''3645030''>that</span>
  <span m=''3645130''>have</span> <span m=''3645470''>been</span> <span m=''3645720''>tried</span>
  <span m=''3646060''>and</span> <span m=''3646180''>tested</span> <span m=''3646600''>and</span>
  <span m=''3646680''>used</span> <span m=''3646870''>all</span> <span m=''3647010''>over</span>
  <span m=''3647100''>the</span> <span m=''3647210''>place</span> <span m=''3647530''>are</span>
  <span m=''3647680''>rule</span> <span m=''3647850''>one</span> <span m=''3648610''>and</span>
  <span m=''3648880''>rule</span> <span m=''3649090''>two.</span> </p><p><span m=''3653420''>So</span>
  <span m=''3654340''>rule</span> <span m=''3654530''>one.</span> <span m=''3656930''>You''ll</span>
  <span m=''3657060''>see</span> <span m=''3657240''>why</span> <span m=''3657420''>this</span>
  <span m=''3657570''>is</span> <span m=''3657650''>interesting</span> <span m=''3658130''>in</span>
  <span m=''3658200''>a</span> <span m=''3658240''>moment.</span> <span m=''3661420''>I</span>
  <span m=''3661550''>have</span> <span m=''3661780''>some</span> <span m=''3662030''>linkage,</span>
  <span m=''3663430''>self-touching</span> <span m=''3664200''>linkage.</span> <span
  m=''3664810''>We''re</span> <span m=''3664930''>in</span> <span m=''3664980''>the</span>
  <span m=''3665050''>same</span> <span m=''3665280''>framework.</span> <span m=''3666500''>Suppose</span>
  <span m=''3667530''>these</span> <span m=''3667800''>two</span> <span m=''3667940''>edges</span>
  <span m=''3669220''>have</span> <span m=''3669490''>the</span> <span m=''3669570''>same</span>
  <span m=''3669860''>length.</span> <span m=''3670690''>I''m</span> <span m=''3670870''>drawing</span>
  <span m=''3671890''>this</span> <span m=''3672060''>one</span> <span m=''3672180''>slightly</span>
  <span m=''3672480''>smaller</span> <span m=''3672800''>just</span> <span m=''3672930''>so</span>
  <span m=''3673010''>I</span> <span m=''3673060''>can</span> <span m=''3673210''>show</span>
  <span m=''3673410''>you,</span> <span m=''3673700''>which</span> <span m=''3673790''>is</span>
  <span m=''3673920''>on</span> <span m=''3674020''>which</span> <span m=''3674200''>side.</span>
  </p><p><span m=''3676330''>But</span> <span m=''3676480''>suppose</span> <span m=''3676830''>they</span>
  <span m=''3676870''>have</span> <span m=''3677050''>the</span> <span m=''3677110''>same</span>
  <span m=''3677370''>length.</span> <span m=''3677790''>And</span> <span m=''3677960''>suppose</span>
  <span m=''3678900''>that</span> <span m=''3679050''>both</span> <span m=''3679360''>of</span>
  <span m=''3679430''>these</span> <span m=''3679640''>angles</span> <span m=''3681570''>are</span>
  <span m=''3682690''>acute,</span> <span m=''3683350''>strictly,</span> <span m=''3684770''>less</span>
  <span m=''3684980''>than</span> <span m=''3685090''>90.</span> <span m=''3688470''>What</span>
  <span m=''3688620''>do</span> <span m=''3688660''>you</span> <span m=''3688750''>think</span>
  <span m=''3688930''>happens</span> <span m=''3689340''>in</span> <span m=''3689410''>this</span>
  <span m=''3689580''>picture?</span> <span m=''3689930''>I</span> <span m=''3689980''>have</span>
  <span m=''3690150''>this</span> <span m=''3690320''>bar</span> <span m=''3690630''>floating</span>
  <span m=''3691050''>around.</span> <span m=''3691450''>And I</span> <span m=''3691520''>have</span>
  <span m=''3691690''>these</span> <span m=''3691890''>three</span> <span m=''3692060''>bars.</span>
  <span m=''3693700''>What</span> <span m=''3693950''>happens</span> <span m=''3694360''>to</span>
  <span m=''3694450''>this</span> <span m=''3694660''>bar?</span> </p><p><span m=''3696792''>AUDIENCE:
  It''s confined</span> <span m=''3697235''>to be</span> <span m=''3697678''>against</span>
  <span m=''3698121''>the other bar.</span> </p><p><span m=''3698570''>PROFESSOR:
  It''s</span> <span m=''3698760''>confined</span> <span m=''3699280''>to</span> <span
  m=''3699380''>be</span> <span m=''3699530''>right</span> <span m=''3699840''>against</span>
  <span m=''3700200''>this</span> <span m=''3700380''>edge.</span> <span m=''3700790''>It</span>
  <span m=''3700910''>can''t</span> <span m=''3701180''>move</span> <span m=''3701720''>at</span>
  <span m=''3701870''>all</span> <span m=''3702610''>until</span> <span m=''3703510''>this</span>
  <span m=''3703750''>angle--</span> <span m=''3705020''>both</span> <span m=''3705470''>of</span>
  <span m=''3705540''>these,</span> <span m=''3706220''>and</span> <span m=''3706360''>I</span>
  <span m=''3706420''>guess</span> <span m=''3706620''>at</span> <span m=''3706670''>least</span>
  <span m=''3706880''>one</span> <span m=''3707060''>of</span> <span m=''3707120''>them</span>
  <span m=''3707300''>would</span> <span m=''3707350''>have</span> <span m=''3707500''>to</span>
  <span m=''3707600''>get</span> <span m=''3707800''>to</span> <span m=''3707890''>90,</span>
  <span m=''3708730''>then</span> <span m=''3708960''>you</span> <span m=''3709080''>could</span>
  <span m=''3709210''>try</span> <span m=''3709380''>to</span> <span m=''3709450''>slide</span>
  <span m=''3709730''>it</span> <span m=''3709820''>out.</span> <span m=''3710820''>Like</span>
  <span m=''3711050''>if this</span> <span m=''3711200''>one</span> <span m=''3711330''>goes</span>
  <span m=''3711730''>beyond</span> <span m=''3712020''>90</span> <span m=''3712330''>then</span>
  <span m=''3712480''>you</span> <span m=''3712620''>can</span> <span m=''3713250''>slide</span>
  <span m=''3713560''>out.</span> </p><p><span m=''3714720''>As</span> <span m=''3715020''>long</span>
  <span m=''3715240''>as</span> <span m=''3715350''>they''re</span> <span m=''3715470''>both</span>
  <span m=''3715750''>less</span> <span m=''3715980''>than</span> <span m=''3716090''>90</span>
  <span m=''3718250''>it''s</span> <span m=''3718580''>pinned</span> <span m=''3718890''>there.</span>
  <span m=''3721670''>So</span> <span m=''3721780''>what</span> <span m=''3721960''>I''m</span>
  <span m=''3722100''>going</span> <span m=''3722220''>to</span> <span m=''3722310''>do</span>
  <span m=''3723150''>is</span> <span m=''3723320''>redraw</span> <span m=''3723850''>this</span>
  <span m=''3724050''>diagram</span> <span m=''3724840''>as</span> <span m=''3728460''>with</span>
  <span m=''3728960''>two</span> <span m=''3729230''>edges</span> <span m=''3729570''>there,</span>
  <span m=''3730970''>which</span> <span m=''3731280''>I</span> <span m=''3731340''>mean,</span>
  <span m=''3731580''>you</span> <span m=''3731600''>can</span> <span m=''3731710''>just</span>
  <span m=''3731890''>ignore.</span> <span m=''3733580''>The</span> <span m=''3733700''>point</span>
  <span m=''3733870''>is</span> <span m=''3734010''>if</span> <span m=''3734130''>there''s</span>
  <span m=''3734260''>something</span> <span m=''3734530''>attached</span> <span m=''3735030''>here</span>
  <span m=''3735250''>and</span> <span m=''3735320''>here--</span> <span m=''3736700''>maybe</span>
  <span m=''3736940''>many</span> <span m=''3737200''>things,</span> <span m=''3737460''>it''s</span>
  <span m=''3737590''>a</span> <span m=''3737780''>tree,</span> <span m=''3738260''>who</span>
  <span m=''3738350''>knows?--</span> <span m=''3739390''>you</span> <span m=''3739510''>can</span>
  <span m=''3739630''>just</span> <span m=''3739780''>attach</span> <span m=''3740180''>them</span>
  <span m=''3740560''>right</span> <span m=''3740790''>there.</span> </p><p><span
  m=''3742770''>This</span> <span m=''3742940''>is</span> <span m=''3743080''>a</span>
  <span m=''3743170''>simplification</span> <span m=''3743900''>to</span> <span m=''3743980''>the</span>
  <span m=''3744050''>linkage.</span> <span m=''3744440''>It</span> <span m=''3744570''>does</span>
  <span m=''3744710''>not</span> <span m=''3744990''>behave</span> <span m=''3745270''>the</span>
  <span m=''3745360''>same.</span> <span m=''3746190''>But</span> <span m=''3747480''>it</span>
  <span m=''3747580''>has</span> <span m=''3747750''>the</span> <span m=''3747820''>same</span>
  <span m=''3748120''>rigidity.</span> <span m=''3749260''>Because</span> <span m=''3749430''>if</span>
  <span m=''3749570''>all</span> <span m=''3749730''>I</span> <span m=''3749800''>care</span>
  <span m=''3750020''>about</span> <span m=''3750200''>is</span> <span m=''3750320''>rigidity,</span>
  <span m=''3751640''>I</span> <span m=''3751890''>care</span> <span m=''3751950''>about</span>
  <span m=''3752230''>can</span> <span m=''3752410''>I</span> <span m=''3752460''>move</span>
  <span m=''3752730''>at</span> <span m=''3752880''>all?</span> <span m=''3754290''>So</span>
  <span m=''3755350''>in</span> <span m=''3755520''>order</span> <span m=''3755650''>for</span>
  <span m=''3755750''>this</span> <span m=''3755950''>guy</span> <span m=''3756070''>to</span>
  <span m=''3756160''>move</span> <span m=''3756350''>and</span> <span m=''3756430''>all,</span>
  <span m=''3756780''>these</span> <span m=''3756990''>guys</span> <span m=''3757160''>would</span>
  <span m=''3757300''>first</span> <span m=''3757590''>have</span> <span m=''3757730''>to</span>
  <span m=''3757830''>move</span> <span m=''3758870''>for</span> <span m=''3759090''>quite</span>
  <span m=''3759380''>a</span> <span m=''3759450''>while,</span> <span m=''3760500''>a</span>
  <span m=''3760590''>positive</span> <span m=''3761080''>amount</span> <span m=''3761320''>of</span>
  <span m=''3761400''>time.</span> <span m=''3761710''>I</span> <span m=''3761840''>just</span>
  <span m=''3762020''>want</span> <span m=''3762170''>to</span> <span m=''3762210''>know</span>
  <span m=''3762400''>can</span> <span m=''3762550''>I</span> <span m=''3762590''>move</span>
  <span m=''3762790''>0</span> <span m=''3763240''>or</span> <span m=''3763320''>more</span>
  <span m=''3763530''>than</span> <span m=''3763710''>0?</span> </p><p><span m=''3764640''>If</span>
  <span m=''3764800''>I</span> <span m=''3764890''>can</span> <span m=''3765020''>move</span>
  <span m=''3765190''>more</span> <span m=''3765370''>than</span> <span m=''3765510''>0</span>
  <span m=''3766320''>I</span> <span m=''3766410''>could</span> <span m=''3766540''>move</span>
  <span m=''3766700''>this</span> <span m=''3766880''>guy</span> <span m=''3767010''>more</span>
  <span m=''3767240''>than</span> <span m=''3767390''>0</span> <span m=''3767830''>without</span>
  <span m=''3768300''>this</span> <span m=''3768390''>guy</span> <span m=''3768550''>moving</span>
  <span m=''3768850''>at</span> <span m=''3768910''>all.</span> <span m=''3770070''>So</span>
  <span m=''3770130''>really</span> <span m=''3770420''>I</span> <span m=''3770470''>don''t</span>
  <span m=''3770620''>care</span> <span m=''3770850''>about</span> <span m=''3771050''>how</span>
  <span m=''3771170''>this</span> <span m=''3771380''>guy</span> <span m=''3771490''>moves.</span>
  <span m=''3771760''>He''s</span> <span m=''3771960''>effectively</span> <span m=''3772500''>pinned</span>
  <span m=''3772860''>for</span> <span m=''3773090''>at least a</span> <span m=''3773390''>small</span>
  <span m=''3773720''>amount</span> <span m=''3773940''>of</span> <span m=''3774020''>time.</span>
  <span m=''3775240''>I</span> <span m=''3775330''>really</span> <span m=''3775570''>care</span>
  <span m=''3775770''>about</span> <span m=''3775990''>can</span> <span m=''3776140''>the</span>
  <span m=''3776230''>rest</span> <span m=''3776480''>move</span> <span m=''3776680''>it</span>
  <span m=''3776740''>all?</span> <span m=''3777480''>So</span> <span m=''3777620''>you</span>
  <span m=''3777780''>can</span> <span m=''3777910''>simplify</span> <span m=''3778430''>your</span>
  <span m=''3778540''>linkage</span> <span m=''3778870''>like</span> <span m=''3779050''>this,</span>
  <span m=''3779760''>and</span> <span m=''3779900''>the</span> <span m=''3779970''>rigidity</span>
  <span m=''3780440''>will</span> <span m=''3780570''>be</span> <span m=''3780690''>preserved.</span>
  </p><p><span m=''3782180''>This</span> <span m=''3782570''>is</span> <span m=''3782860''>awesome</span>
  <span m=''3783290''>because</span> <span m=''3783510''>it''s</span> <span m=''3783740''>easy</span>
  <span m=''3784060''>to</span> <span m=''3784140''>see</span> <span m=''3784580''>when</span>
  <span m=''3784720''>this</span> <span m=''3784810''>applies.</span> <span m=''3785800''>And</span>
  <span m=''3785960''>you</span> <span m=''3786040''>just</span> <span m=''3786200''>simplify</span>
  <span m=''3786680''>your</span> <span m=''3786800''>linkage</span> <span m=''3787200''>until</span>
  <span m=''3787440''>you</span> <span m=''3787670''>can</span> <span m=''3787970''>just</span>
  <span m=''3788200''>tell</span> <span m=''3788500''>whether</span> <span m=''3788730''>it''s</span>
  <span m=''3788860''>rigid.</span> </p><p><span m=''3790520''>All right</span> <span
  m=''3790710''>rule</span> <span m=''3790940''>two</span> <span m=''3791150''>is</span>
  <span m=''3791280''>sort</span> <span m=''3791480''>of</span> <span m=''3791560''>a</span>
  <span m=''3791610''>special</span> <span m=''3791950''>case.</span> <span m=''3794310''>It
  looks</span> <span m=''3794470''>like</span> <span m=''3794620''>this.</span> <span
  m=''3796760''>So</span> <span m=''3796920''>here,</span> <span m=''3797410''>this</span>
  <span m=''3797640''>bar and</span> <span m=''3797860''>this</span> <span m=''3798060''>bar</span>
  <span m=''3799050''>actually</span> <span m=''3799450''>share</span> <span m=''3799690''>an</span>
  <span m=''3799760''>endpoint.</span> </p><p><span m=''3801280''>And</span> <span
  m=''3801450''>again,</span> <span m=''3801730''>I</span> <span m=''3801800''>need</span>
  <span m=''3802010''>that</span> <span m=''3802130''>this</span> <span m=''3802330''>angle</span>
  <span m=''3802550''>is</span> <span m=''3802650''>acute.</span> <span m=''3803980''>And</span>
  <span m=''3804160''>I</span> <span m=''3804220''>need</span> <span m=''3804500''>that</span>
  <span m=''3804640''>these</span> <span m=''3804960''>two</span> <span m=''3805930''>have</span>
  <span m=''3806200''>the</span> <span m=''3806280''>same</span> <span m=''3806550''>length.</span>
  <span m=''3811060''>And</span> <span m=''3811460''>I</span> <span m=''3811510''>can</span>
  <span m=''3811680''>simplify</span> <span m=''3814150''>to</span> <span m=''3816270''>that,</span>
  <span m=''3817770''>where</span> <span m=''3818040''>if</span> <span m=''3818140''>anything</span>
  <span m=''3818450''>was</span> <span m=''3818590''>attached</span> <span m=''3819030''>here</span>
  <span m=''3819735''>it</span> <span m=''3820040''>just</span> <span m=''3820210''>gets</span>
  <span m=''3820380''>attached</span> <span m=''3820790''>there.</span> </p><p><span
  m=''3823590''>Let''s</span> <span m=''3823780''>try</span> <span m=''3823990''>it</span>
  <span m=''3824070''>out.</span> <span m=''3830560''>Actually,</span> <span m=''3830810''>I</span>
  <span m=''3830890''>could</span> <span m=''3831040''>use</span> <span m=''3831190''>some</span>
  <span m=''3831330''>more</span> <span m=''3831510''>boards.</span> <span m=''3852950''>So</span>
  <span m=''3853840''>I''m</span> <span m=''3853920''>just</span> <span m=''3854180''>going</span>
  <span m=''3854300''>to</span> <span m=''3854410''>copy</span> <span m=''3855040''>the</span>
  <span m=''3855170''>example</span> <span m=''3857010''>we</span> <span m=''3857130''>had</span>
  <span m=''3857640''>from</span> <span m=''3858110''>before.</span> <span m=''3859730''>And</span>
  <span m=''3859840''>this</span> <span m=''3859960''>will</span> <span m=''3860060''>work</span>
  <span m=''3860290''>on</span> <span m=''3860440''>basically</span> <span m=''3860760''>all</span>
  <span m=''3860910''>the</span> <span m=''3861080''>examples</span> <span m=''3861380''>I''ve
  shown</span> <span m=''3861680''>you</span> <span m=''3861780''>except</span> <span
  m=''3862080''>the</span> <span m=''3862220''>equilateral</span> <span m=''3862670''>one.</span>
  </p><p><span m=''3879000''>This</span> <span m=''3879230''>is</span> <span m=''3879440''>the</span>
  <span m=''3880670''>one, two,</span> <span m=''3881141''>three,</span> <span m=''3882083''>four,</span>
  <span m=''3882554''>five, six,</span> <span m=''3883025''>seven,</span> <span m=''3883496''>eight</span>
  <span m=''3883970''>bar</span> <span m=''3884270''>example.</span> <span m=''3884700''>This
  is</span> <span m=''3885810''>conjectured</span> <span m=''3886350''>minimum.</span>
  <span m=''3888070''>Let''s</span> <span m=''3888260''>prove</span> <span m=''3888490''>that
  it''s</span> <span m=''3888770''>locked.</span> </p><p><span m=''3892160''>See any</span>
  <span m=''3892500''>rule</span> <span m=''3892740''>one''s</span> <span m=''3893030''>we</span>
  <span m=''3893100''>could</span> <span m=''3893210''>apply?</span> <span m=''3897300''>Do
  you see</span> <span m=''3897640''>any</span> <span m=''3897990''>edges</span> <span
  m=''3898610''>that</span> <span m=''3898760''>are</span> <span m=''3899600''>effectively</span>
  <span m=''3900040''>wedged</span> <span m=''3900500''>against</span> <span m=''3900800''>another</span>
  <span m=''3901120''>edge?</span> <span m=''3901810''>Remember,</span> <span m=''3903310''>all</span>
  <span m=''3903580''>of</span> <span m=''3903690''>these</span> <span m=''3903900''>vertices</span>
  <span m=''3904430''>are</span> <span m=''3904520''>actually</span> <span m=''3905250''>on</span>
  <span m=''3905430''>top</span> <span m=''3905660''>of</span> <span m=''3905770''>each</span>
  <span m=''3905940''>other,</span> <span m=''3908000''>we''re</span> <span m=''3908230''>thinking</span>
  <span m=''3908440''>about</span> <span m=''3908650''>the self-touching</span> <span
  m=''3909150''>version.</span> <span m=''3909480''>These</span> <span m=''3909680''>guys</span>
  <span m=''3909870''>are</span> <span m=''3909910''>actually</span> <span m=''3910200''>touching,</span>
  <span m=''3911280''>and</span> <span m=''3911440''>these</span> <span m=''3911630''>guys</span>
  <span m=''3911860''>are</span> <span m=''3911900''>actually</span> <span m=''3912230''>touching.</span>
  </p><p><span m=''3913562''>AUDIENCE: This</span> <span m=''3914053''>rule</span>
  <span m=''3914544''>one</span> <span m=''3915035''>[INAUDIBLE].</span> </p><p><span
  m=''3916510''>PROFESSOR: There''s</span> <span m=''3916670''>a</span> <span m=''3916750''>rule</span>
  <span m=''3916920''>one--</span> </p><p><span m=''3919612''>AUDIENCE: That one,</span>
  <span m=''3920085''>there.</span> </p><p><span m=''3920560''>PROFESSOR: --here?</span>
  <span m=''3921450''>Yeah,</span> <span m=''3921890''>good.</span> <span m=''3922600''>This</span>
  <span m=''3922840''>edge</span> <span m=''3923970''>is</span> <span m=''3924180''>pinned</span>
  <span m=''3924420''>against</span> <span m=''3924730''>this</span> <span m=''3924940''>edge.</span>
  <span m=''3925960''>Because</span> <span m=''3926120''>look,</span> <span m=''3926310''>we</span>
  <span m=''3926410''>have</span> <span m=''3926610''>acute</span> <span m=''3926910''>angles</span>
  <span m=''3927330''>here,</span> <span m=''3928340''>namely</span> <span m=''3928670''>0.</span>
  <span m=''3930100''>There''s</span> <span m=''3930220''>an</span> <span m=''3930280''>acute</span>
  <span m=''3930570''>angle</span> <span m=''3930840''>here,</span> <span m=''3931240''>that''s</span>
  <span m=''3931470''>0.</span> <span m=''3932700''>And</span> <span m=''3932890''>this</span>
  <span m=''3933190''>edge,</span> <span m=''3933490''>if</span> <span m=''3933560''>these</span>
  <span m=''3933750''>guys</span> <span m=''3933940''>are</span> <span m=''3933990''>on</span>
  <span m=''3934070''>top</span> <span m=''3934300''>of</span> <span m=''3934390''>each</span>
  <span m=''3934550''>other,</span> <span m=''3934910''>and</span> <span m=''3935010''>these</span>
  <span m=''3935060''>guys</span> <span m=''3935240''>aer on top</span> <span m=''3935420''>of</span>
  <span m=''3935550''>each</span> <span m=''3935750''>other,</span> <span m=''3935910''>these</span>
  <span m=''3936120''>two</span> <span m=''3936240''>edges</span> <span m=''3936500''>have</span>
  <span m=''3936630''>the</span> <span m=''3936700''>same</span> <span m=''3936940''>length.</span>
  <span m=''3937720''>Therefore</span> <span m=''3938520''>these</span> <span m=''3938730''>are</span>
  <span m=''3938810''>pinned</span> <span m=''3939050''>together.</span> </p><p><span
  m=''3941760''>So</span> <span m=''3941870''>let</span> <span m=''3941980''>me</span>
  <span m=''3942120''>redraw</span> <span m=''3942510''>it</span> <span m=''3943780''>when</span>
  <span m=''3945120''>they''re</span> <span m=''3945280''>pinned</span> <span m=''3945490''>together.</span>
  <span m=''3958790''>I''m drawing</span> <span m=''3959040''>things</span> <span
  m=''3959250''>with curves</span> <span m=''3959700''>just</span> <span m=''3959850''>so</span>
  <span m=''3959960''>it''s</span> <span m=''3960070''>easier</span> <span m=''3960410''>to</span>
  <span m=''3960540''>draw,</span> <span m=''3960930''>but</span> <span m=''3961180''>you</span>
  <span m=''3961300''>understand</span> <span m=''3961660''>this</span> <span m=''3961820''>is</span>
  <span m=''3961880''>also</span> <span m=''3962820''>basically</span> <span m=''3963230''>flat.</span>
  <span m=''3964620''>Again</span> <span m=''3964910''>these</span> <span m=''3965120''>guys</span>
  <span m=''3965550''>are</span> <span m=''3965640''>all</span> <span m=''3967530''>on</span>
  <span m=''3967730''>top of</span> <span m=''3968000''>each</span> <span m=''3968160''>other,</span>
  <span m=''3968380''>these</span> <span m=''3968620''>are on top of</span> <span
  m=''3969050''>each</span> <span m=''3969210''>other,</span> <span m=''3969400''>these</span>
  <span m=''3969600''>are on</span> <span m=''3969750''>top</span> <span m=''3969950''>of</span>
  <span m=''3970040''>each</span> <span m=''3970180''>other.</span> </p><p><span m=''3972730''>Did
  I</span> <span m=''3972940''>do that</span> <span m=''3973020''>right?</span> <span
  m=''3974200''>I think</span> <span m=''3974330''>so,</span> <span m=''3974550''>yep.</span>
  <span m=''3975680''>Anymore?</span> </p><p><span m=''3977476''>AUDIENCE: [INAUDIBLE].</span>
  </p><p><span m=''3977910''>PROFESSOR: Yes,</span> <span m=''3978660''>on</span>
  <span m=''3978750''>the</span> <span m=''3978840''>right</span> <span m=''3979050''>side.</span>
  <span m=''3979700''>It''s</span> <span m=''3979800''>another</span> <span m=''3980060''>rule</span>
  <span m=''3980260''>one.</span> <span m=''3981890''>Here</span> <span m=''3982080''>it''s</span>
  <span m=''3982210''>actually</span> <span m=''3982520''>pretty</span> <span m=''3982720''>symmetric.</span>
  </p><p><span m=''3985290''>Is</span> <span m=''3985450''>this</span> <span m=''3985720''>locked?</span>
  <span m=''3986060''>Is</span> <span m=''3986220''>this</span> <span m=''3986360''>rigid?</span>
  <span m=''3986770''>It''s kind</span> <span m=''3986970''>of</span> <span m=''3987010''>hard</span>
  <span m=''3987160''>to</span> <span m=''3987220''>say.</span> <span m=''3987500''>But</span>
  <span m=''3988400''>now</span> <span m=''3988580''>it''s</span> <span m=''3988760''>going
  to</span> <span m=''3988980''>be</span> <span m=''3989100''>pretty</span> <span
  m=''3989320''>obvious.</span> </p><p><span m=''3990410''>Because</span> <span m=''3991480''>when</span>
  <span m=''3991710''>these</span> <span m=''3991940''>guys</span> <span m=''3992150''>join</span>
  <span m=''3992370''>together</span> <span m=''3992680''>that</span> <span m=''3992840''>means</span>
  <span m=''3992990''>these</span> <span m=''3993140''>two</span> <span m=''3993260''>vertices</span>
  <span m=''3993670''>really</span> <span m=''3993940''>are on</span> <span m=''3994130''>top</span>
  <span m=''3994350''>of</span> <span m=''3994440''>each</span> <span m=''3994590''>other</span>
  <span m=''3994780''>for</span> <span m=''3994890''>positive</span> <span m=''3995280''>time.</span>
  <span m=''3995490''>Same</span> <span m=''3995710''>for</span> <span m=''3995800''>these.</span>
  <span m=''3997000''>So</span> <span m=''3997210''>a new</span> <span m=''3997390''>example</span>
  <span m=''3998370''>looks</span> <span m=''3998650''>like</span> <span m=''3999620''>two</span>
  <span m=''3999780''>triangles</span> <span m=''4001230''>with</span> <span m=''4001370''>an</span>
  <span m=''4001470''>edge</span> <span m=''4001780''>floating</span> <span m=''4002110''>there.</span>
  </p><p><span m=''4003970''>Now it''s</span> <span m=''4004210''>pretty</span> <span
  m=''4004440''>obvious</span> <span m=''4004790''>this</span> <span m=''4004930''>is</span>
  <span m=''4005040''>rigid.</span> <span m=''4005410''>But</span> <span m=''4005550''>if</span>
  <span m=''4005660''>you</span> <span m=''4005780''>really</span> <span m=''4006080''>want</span>
  <span m=''4006290''>to</span> <span m=''4006350''>make</span> <span m=''4006530''>it</span>
  <span m=''4006610''>obvious</span> <span m=''4007580''>you</span> <span m=''4007720''>can</span>
  <span m=''4007830''>apply</span> <span m=''4008100''>rule</span> <span m=''4008350''>two</span>
  <span m=''4010062''>to</span> <span m=''4012050''>this</span> <span m=''4012260''>guy.</span>
  <span m=''4013080''>And</span> <span m=''4013450''>then</span> <span m=''4013600''>these</span>
  <span m=''4013810''>guys</span> <span m=''4014350''>are</span> <span m=''4014530''>pinned</span>
  <span m=''4014770''>together.</span> <span m=''4015770''>And</span> <span m=''4015970''>then</span>
  <span m=''4016500''>you</span> <span m=''4016810''>have</span> <span m=''4021110''>two</span>
  <span m=''4021480''>triangles.</span> <span m=''4022560''>Two</span> <span m=''4022690''>triangles</span>
  <span m=''4023640''>are</span> <span m=''4023790''>rigid.</span> </p><p><span m=''4025640''>I</span>
  <span m=''4025660''>think</span> <span m=''4025790''>that''s</span> <span m=''4026000''>pretty</span>
  <span m=''4026150''>obvious.</span> <span m=''4027300''>You</span> <span m=''4027420''>could</span>
  <span m=''4027560''>check</span> <span m=''4027790''>it,</span> <span m=''4027930''>whether</span>
  <span m=''4028440''>they''re</span> <span m=''4028500''>infinitesimally</span> <span
  m=''4028970''>rigid,</span> <span m=''4029370''>whatever</span> <span m=''4029640''>you</span>
  <span m=''4029740''>feel</span> <span m=''4029950''>like.</span> <span m=''4030580''>But</span>
  <span m=''4031750''>because</span> <span m=''4032020''>that''s</span> <span m=''4032280''>rigid,</span>
  <span m=''4032650''>this</span> <span m=''4032810''>is</span> <span m=''4032940''>rigid,</span>
  <span m=''4033260''>this</span> <span m=''4033440''>is</span> <span m=''4033570''>rigid,</span>
  <span m=''4033880''>this</span> <span m=''4034070''>is</span> <span m=''4034190''>ridged.</span>
  <span m=''4034470''>Because</span> <span m=''4034650''>these</span> <span m=''4034810''>operations</span>
  <span m=''4035280''>preserve</span> <span m=''4035610''>rigidity.</span> </p><p><span
  m=''4036120''>They</span> <span m=''4036250''>don''t</span> <span m=''4036430''>preserve</span>
  <span m=''4036740''>locked</span> <span m=''4037140''>or</span> <span m=''4037230''>whatever,</span>
  <span m=''4037710''>but</span> <span m=''4037750''>they</span> <span m=''4037830''>preserve</span>
  <span m=''4038140''>rigidity.</span> <span m=''4039250''>Once</span> <span m=''4039450''>you
  know that</span> <span m=''4039745''>this</span> <span m=''4040040''>is</span> <span
  m=''4040160''>rigid</span> <span m=''4040490''>you know that it''s</span> <span
  m=''4040930''>strongly</span> <span m=''4041390''>locked.</span> <span m=''4041860''>So</span>
  <span m=''4042050''>when</span> <span m=''4042140''>you</span> <span m=''4042250''>perturb</span>
  <span m=''4042670''>it</span> <span m=''4042810''>so</span> <span m=''4042930''>these</span>
  <span m=''4043140''>guys</span> <span m=''4043320''>are</span> <span m=''4043390''>not</span>
  <span m=''4043660''>on</span> <span m=''4043780''>top</span> <span m=''4044000''>of</span>
  <span m=''4044090''>each</span> <span m=''4044230''>other,</span> <span m=''4044420''>but</span>
  <span m=''4044590''>they''re</span> <span m=''4044770''>slightly</span> <span m=''4045100''>spread</span>
  <span m=''4045370''>out,</span> <span m=''4046520''>it</span> <span m=''4046620''>will</span>
  <span m=''4046720''>be</span> <span m=''4046850''>locked</span> <span m=''4047090''>within</span>
  <span m=''4047280''>epsilon,</span> <span m=''4047660''>for</span> <span m=''4047800''>any</span>
  <span m=''4047930''>epsilon</span> <span m=''4048260''>you</span> <span m=''4048360''>want.</span>
  </p><p><span m=''4049960''>Now</span> <span m=''4050000''>this</span> <span m=''4050330''>is</span>
  <span m=''4050510''>super</span> <span m=''4050870''>easy.</span> <span m=''4051320''>And</span>
  <span m=''4051440''>this</span> <span m=''4051600''>is</span> <span m=''4051690''>how</span>
  <span m=''4051990''>we</span> <span m=''4052130''>were</span> <span m=''4052270''>able</span>
  <span m=''4052450''>to</span> <span m=''4052500''>iterate</span> <span m=''4052840''>through</span>
  <span m=''4052990''>all</span> <span m=''4053110''>those</span> <span m=''4053630''>locked</span>
  <span m=''4053880''>trees,</span> <span m=''4054220''>and</span> <span m=''4054330''>say,</span>
  <span m=''4054590''>oh</span> <span m=''4054640''>yeah,</span> <span m=''4055650''>this</span>
  <span m=''4055870''>is</span> <span m=''4055960''>still</span> <span m=''4056750''>rigid,</span>
  <span m=''4057200''>so it''s</span> <span m=''4057240''>still</span> <span m=''4057480''>strongly</span>
  <span m=''4057870''>locked.</span> <span m=''4058950''>Now</span> <span m=''4059090''>this</span>
  <span m=''4059200''>doesn''t</span> <span m=''4059440''>always</span> <span m=''4059680''>work.</span>
  <span m=''4061220''>But</span> <span m=''4061370''>it</span> <span m=''4061480''>seems</span>
  <span m=''4061720''>pretty</span> <span m=''4061940''>good.</span> </p><p><span
  m=''4062740''>And</span> <span m=''4062910''>one</span> <span m=''4063090''>of</span>
  <span m=''4063150''>the</span> <span m=''4063220''>conjectures</span> <span m=''4063710''>on</span>
  <span m=''4063810''>the</span> <span m=''4063900''>tables</span> <span m=''4064270''>is
  that</span> <span m=''4064380''>for</span> <span m=''4064520''>linear</span> <span
  m=''4065410''>trees</span> <span m=''4067010''>rules</span> <span m=''4067380''>one
  and</span> <span m=''4067670''>two</span> <span m=''4067870''>are</span> <span m=''4068330''>kind</span>
  <span m=''4068580''>of</span> <span m=''4068650''>almost</span> <span m=''4069020''>enough.</span>
  <span m=''4069530''>It''s</span> <span m=''4069680''>not</span> <span m=''4069890''>literally</span>
  <span m=''4070300''>true.</span> <span m=''4071020''>But</span> <span m=''4071170''>it''s</span>
  <span m=''4071300''>hopefully</span> <span m=''4071750''>mostly</span> <span m=''4072170''>true.</span>
  </p><p><span m=''4072822''>AUDIENCE: It seems</span> <span m=''4073224''>that</span>
  <span m=''4074430''>that</span> <span m=''4074470''>argument</span> <span m=''4074950''>would
  mean</span> <span m=''4075430''>you wouldn''t</span> <span m=''4075910''>need</span>
  <span m=''4076870''>one of</span> <span m=''4077350''>the</span> <span m=''4077830''>n''s</span>
  <span m=''4078310''>on--</span> </p><p><span m=''4080720''>PROFESSOR: Right,</span>
  <span m=''4081020''>so</span> <span m=''4081190''>we</span> <span m=''4081300''>could</span>
  <span m=''4081430''>think</span> <span m=''4081610''>about</span> <span m=''4081830''>this</span>
  <span m=''4081990''>example.</span> <span m=''4083260''>And</span> <span m=''4083520''>you''re</span>
  <span m=''4083680''>asking</span> <span m=''4084170''>do</span> <span m=''4084280''>you</span>
  <span m=''4084450''>need--</span> <span m=''4085630''>does</span> <span m=''4085810''>this</span>
  <span m=''4086020''>need</span> <span m=''4086210''>to</span> <span m=''4086280''>be</span>
  <span m=''4086400''>that</span> <span m=''4086620''>long or</span> <span m=''4086960''>could</span>
  <span m=''4087080''>we</span> <span m=''4087190''>throw</span> <span m=''4087400''>away</span>
  <span m=''4087540''>the</span> <span m=''4087660''>last</span> <span m=''4088000''>bar?</span>
  <span m=''4090010''>Right,</span> <span m=''4090520''>it</span> <span m=''4090590''>looks</span>
  <span m=''4090800''>like</span> <span m=''4090930''>that''s</span> <span m=''4091170''>good.</span>
  <span m=''4091670''>If</span> <span m=''4091870''>you</span> <span m=''4091970''>throw</span>
  <span m=''4092200''>away</span> <span m=''4092330''>this</span> <span m=''4092510''>bar</span>
  <span m=''4093250''>it''s</span> <span m=''4093370''>still</span> <span m=''4093590''>the</span>
  <span m=''4093680''>case</span> <span m=''4094020''>that</span> <span m=''4094210''>this</span>
  <span m=''4094440''>edge</span> <span m=''4096609''>you</span> <span m=''4096990''>can</span>
  <span m=''4097420''>apply</span> <span m=''4097979''>rule</span> <span m=''4098260''>one,</span>
  <span m=''4098720''>and</span> <span m=''4098890''>say</span> <span m=''4099029''>that
  it''s</span> <span m=''4099260''>pinned</span> <span m=''4099580''>against</span>
  <span m=''4099740''>this</span> <span m=''4099939''>edge.</span> </p><p><span m=''4101580''>And</span>
  <span m=''4101810''>once</span> <span m=''4102080''>those</span> <span m=''4102390''>are</span>
  <span m=''4102460''>there,</span> <span m=''4103310''>this</span> <span m=''4103540''>thing</span>
  <span m=''4103720''>basically</span> <span m=''4104060''>acts</span> <span m=''4104310''>as</span>
  <span m=''4104410''>a</span> <span m=''4104470''>single</span> <span m=''4104770''>triangle,</span>
  <span m=''4105960''>and</span> <span m=''4106069''>life</span> <span m=''4106290''>is</span>
  <span m=''4106420''>good.</span> <span m=''4106979''>Yeah,</span> <span m=''4107250''>so</span>
  <span m=''4107410''>you</span> <span m=''4107520''>can</span> <span m=''4107660''>remove</span>
  <span m=''4107899''>this</span> <span m=''4108060''>one</span> <span m=''4108229''>edge.</span>
  <span m=''4109580''>You</span> <span m=''4109740''>could</span> <span m=''4109910''>not</span>
  <span m=''4110180''>remove</span> <span m=''4110479''>both</span> <span m=''4110770''>of</span>
  <span m=''4110840''>the</span> <span m=''4110970''>edges,</span> <span m=''4113220''>at</span>
  <span m=''4113330''>least</span> <span m=''4113520''>for</span> <span m=''4113660''>rule</span>
  <span m=''4113890''>one</span> <span m=''4114090''>to</span> <span m=''4114180''>apply,</span>
  <span m=''4114740''>because</span> <span m=''4115109''>then</span> <span m=''4115270''>this</span>
  <span m=''4115470''>guy''s</span> <span m=''4115740''>not</span> <span m=''4115970''>wedged</span>
  <span m=''4116260''>into</span> <span m=''4116430''>anything.</span> <span m=''4116819''>He''s</span>
  <span m=''4116910''>wedged</span> <span m=''4117149''>on</span> <span m=''4117250''>this</span>
  <span m=''4117410''>side</span> <span m=''4117770''>but he''s</span> <span m=''4117930''>not</span>
  <span m=''4118080''>wedged</span> <span m=''4118310''>on</span> <span m=''4118410''>that</span>
  <span m=''4118600''>side.</span> </p><p><span m=''4120020''>But</span> <span m=''4120160''>you</span>
  <span m=''4120250''>can</span> <span m=''4120390''>remove</span> <span m=''4120620''>this</span>
  <span m=''4120810''>edge.</span> <span m=''4121640''>And</span> <span m=''4121810''>that''s</span>
  <span m=''4122029''>a</span> <span m=''4122189''>super</span> <span m=''4122540''>easy</span>
  <span m=''4122729''>way</span> <span m=''4122870''>to</span> <span m=''4122950''>prove
  that</span> <span m=''4123270''>this</span> <span m=''4123420''>thing</span> <span
  m=''4123569''>is</span> <span m=''4123680''>locked.</span> <span m=''4123960''>We</span>
  <span m=''4124050''>didn''t</span> <span m=''4124229''>know</span> <span m=''4124380''>this</span>
  <span m=''4124609''>when we</span> <span m=''4124840''>wrote</span> <span m=''4125130''>the</span>
  <span m=''4125220''>textbook,</span> <span m=''4125899''>otherwise</span> <span
  m=''4126180''>we would</span> <span m=''4126359''>have</span> <span m=''4126439''>given</span>
  <span m=''4126660''>that</span> <span m=''4126850''>proof.</span> <span m=''4127740''>There''s</span>
  <span m=''4127890''>one</span> <span m=''4128069''>based</span> <span m=''4128310''>on</span>
  <span m=''4128399''>stresses</span> <span m=''4128870''>in</span> <span m=''4128970''>the</span>
  <span m=''4129060''>textbook.</span> </p><p><span m=''4130740''>But</span> <span
  m=''4130970''>here,</span> <span m=''4131229''>yeah,</span> <span m=''4131810''>you</span>
  <span m=''4131930''>can</span> <span m=''4132149''>make</span> <span m=''4132380''>very</span>
  <span m=''4132580''>easy</span> <span m=''4132760''>judgments</span> <span m=''4133200''>like</span>
  <span m=''4133350''>that.</span> <span m=''4133700''>Now it doesn''t</span> <span
  m=''4133939''>mean</span> <span m=''4134729''>that</span> <span m=''4134970''>it''s</span>
  <span m=''4135520''>not</span> <span m=''4135830''>locked</span> <span m=''4136380''>when</span>
  <span m=''4136500''>you</span> <span m=''4136670''>remove</span> <span m=''4136880''>two
  of</span> <span m=''4137069''>the</span> <span m=''4137240''>edges.</span> <span
  m=''4140609''>I''m</span> <span m=''4140689''>not</span> <span m=''4141010''>sure,</span>
  <span m=''4141795''>no</span> <span m=''4142080''>I</span> <span m=''4142140''>think</span>
  <span m=''4142300''>it''s</span> <span m=''4142430''>not</span> <span m=''4142590''>locked.</span>
  <span m=''4143090''>But</span> <span m=''4143810''>just</span> <span m=''4143970''>because</span>
  <span m=''4144140''>the</span> <span m=''4144319''>rules</span> <span m=''4144520''>don''t</span>
  <span m=''4144660''>apply</span> <span m=''4144960''>doesn''t</span> <span m=''4145240''>tell</span>
  <span m=''4145430''>you</span> <span m=''4145569''>that''s</span> <span m=''4145830''>not</span>
  <span m=''4146000''>locked.</span> <span m=''4146729''>But</span> <span m=''4146880''>it
  at</span> <span m=''4146939''>least</span> <span m=''4147149''>makes</span> <span
  m=''4147319''>it</span> <span m=''4147380''>hard</span> <span m=''4147729''>to prove.</span>
  <span m=''4149370''>And</span> <span m=''4149560''>it''s</span> <span m=''4149700''>a</span>
  <span m=''4149740''>good</span> <span m=''4149960''>sort</span> <span m=''4150090''>of</span>
  <span m=''4150200''>guideline.</span> </p><p><span m=''4154970''>Questions?</span>
  <span m=''4156234''>Yeah.</span> </p><p><span m=''4157202''>AUDIENCE: Did</span>
  <span m=''4157686''>the perturbations</span> <span m=''4158170''>that are</span>
  <span m=''4158654''>positive</span> <span m=''4159138''>and</span> <span m=''4159622''>finite</span>
  <span m=''4160590''>have numbers?</span> <span m=''4161074''>Like,</span> <span
  m=''4161558''>what''s--</span> <span m=''4162042''>it''s sort of</span> <span m=''4162526''>disturbing</span>
  <span m=''4163020''>that</span> <span m=''4163229''>they get</span> <span m=''4163677''>very,</span>
  <span m=''4164125''>very</span> <span m=''4164573''>small--</span> <span m=''4165917''>what
  are</span> <span m=''4166365''>they?</span> </p><p><span m=''4166819''>PROFESSOR:
  So</span> <span m=''4167000''>you</span> <span m=''4167090''>want</span> <span m=''4167270''>to</span>
  <span m=''4167330''>know</span> <span m=''4168600''>how</span> <span m=''4168990''>big</span>
  <span m=''4169310''>is</span> <span m=''4169500''>delta?</span> <span m=''4170160''>How</span>
  <span m=''4170410''>big</span> <span m=''4170630''>is</span> <span m=''4170740''>epsilon?</span>
  <span m=''4171149''>Well</span> <span m=''4171319''>it</span> <span m=''4171450''>depends,</span>
  <span m=''4172410''>of course,</span> <span m=''4173279''>how</span> <span m=''4173910''>much</span>
  <span m=''4175050''>motion</span> <span m=''4175439''>you</span> <span m=''4175560''>want</span>
  <span m=''4175720''>to</span> <span m=''4175779''>allow,</span> <span m=''4177010''>how</span>
  <span m=''4177210''>small</span> <span m=''4177529''>the</span> <span m=''4177609''>perturbations</span>
  <span m=''4178149''>have</span> <span m=''4178330''>to</span> <span m=''4178420''>be.</span>
  </p><p><span m=''4179310''>And I</span> <span m=''4179529''>don''t</span> <span
  m=''4179680''>have</span> <span m=''4179859''>a</span> <span m=''4179939''>great</span>
  <span m=''4180310''>answer.</span> <span m=''4180760''>I</span> <span m=''4180880''>do</span>
  <span m=''4181350''>recall</span> <span m=''4181810''>that</span> <span m=''4181920''>we</span>
  <span m=''4182200''>computed</span> <span m=''4182475''>a</span> <span m=''4182750''>bound,</span>
  <span m=''4184120''>probably</span> <span m=''4184420''>in</span> <span m=''4184490''>terms</span>
  <span m=''4184710''>of</span> <span m=''4185420''>something</span> <span m=''4185760''>like</span>
  <span m=''4185990''>r,</span> <span m=''4186760''>the</span> <span m=''4186850''>maximum</span>
  <span m=''4187200''>distance</span> <span m=''4187529''>divided</span> <span m=''4188640''>by</span>
  <span m=''4188840''>the</span> <span m=''4188960''>smallest</span> <span m=''4189520''>non
  0</span> <span m=''4190020''>distance.</span> <span m=''4191600''>So</span> <span
  m=''4191840''>it</span> <span m=''4191890''>depends</span> <span m=''4193380''>how</span>
  <span m=''4193560''>close</span> <span m=''4193990''>to</span> <span m=''4194220''>tight</span>
  <span m=''4194520''>you</span> <span m=''4194700''>are</span> <span m=''4194920''>in</span>
  <span m=''4195040''>other</span> <span m=''4195210''>places.</span> <span m=''4196050''>And
  it</span> <span m=''4196300''>depends</span> <span m=''4196530''>on</span> <span
  m=''4196590''>your</span> <span m=''4196700''>epsilon.</span> </p><p><span m=''4197250''>There</span>
  <span m=''4197420''>is</span> <span m=''4197510''>an</span> <span m=''4197570''>explicit</span>
  <span m=''4197980''>bound.</span> <span m=''4199010''>I</span> <span m=''4199060''>think</span>
  <span m=''4199340''>it''s</span> <span m=''4199490''>polynomial</span> <span m=''4200010''>on</span>
  <span m=''4200080''>those</span> <span m=''4200260''>two</span> <span m=''4200370''>things.</span>
  <span m=''4200750''>But</span> <span m=''4200890''>I</span> <span m=''4200950''>don''t</span>
  <span m=''4201170''>quite</span> <span m=''4201410''>remember.</span> </p><p><span
  m=''4202970''>So</span> <span m=''4203140''>you</span> <span m=''4203250''>can</span>
  <span m=''4203470''>actually</span> <span m=''4203710''>compute</span> <span m=''4204040''>how</span>
  <span m=''4204190''>much</span> <span m=''4204520''>perturbation</span> <span m=''4205110''>will</span>
  <span m=''4206530''>give</span> <span m=''4206690''>you</span> <span m=''4206800''>locked</span>
  <span m=''4207090''>within</span> <span m=''4207310''>epsilon.</span> <span m=''4208060''>But</span>
  <span m=''4208360''>it''s</span> <span m=''4209100''>certainly</span> <span m=''4209410''>not</span>
  <span m=''4209590''>clean.</span> <span m=''4210870''>It''s</span> <span m=''4211020''>actually</span>
  <span m=''4211270''>not</span> <span m=''4211480''>too</span> <span m=''4211610''>hard</span>
  <span m=''4211800''>to</span> <span m=''4211870''>prove</span> <span m=''4213230''>this</span>
  <span m=''4213350''>statement</span> <span m=''4213850''>just</span> <span m=''4214050''>using</span>
  <span m=''4214300''>topology.</span> </p><p><span m=''4221140''>Should</span> <span
  m=''4221430''>I</span> <span m=''4221540''>try</span> <span m=''4221740''>to</span>
  <span m=''4221850''>remember</span> <span m=''4222160''>how</span> <span m=''4222300''>to</span>
  <span m=''4222390''>prove</span> <span m=''4222640''>it?</span> <span m=''4227730''>Basically,</span>
  <span m=''4230490''>yeah,</span> <span m=''4233600''>so</span> <span m=''4233770''>there''s</span>
  <span m=''4233950''>this</span> <span m=''4234110''>fun</span> <span m=''4234300''>fact.</span>
  <span m=''4234610''>Suppose</span> <span m=''4234980''>you</span> <span m=''4235080''>have</span>
  <span m=''4235260''>some</span> <span m=''4235440''>tensegrity.</span> </p><p><span
  m=''4237280''>So</span> <span m=''4237460''>tensegrities</span> <span m=''4238170''>are</span>
  <span m=''4238250''>kind</span> <span m=''4238480''>of</span> <span m=''4238670''>hard.</span>
  <span m=''4239370''>They</span> <span m=''4239500''>say,</span> <span m=''4239750''>look,</span>
  <span m=''4240180''>a</span> <span m=''4240250''>bar</span> <span m=''4240830''>has</span>
  <span m=''4240990''>this</span> <span m=''4241160''>length,</span> <span m=''4241600''>ain''t</span>
  <span m=''4241720''>changing.</span> <span m=''4244190''>Let''s</span> <span m=''4244370''>be</span>
  <span m=''4244460''>a</span> <span m=''4244510''>little</span> <span m=''4244680''>more</span>
  <span m=''4244830''>flexible.</span> <span m=''4245390''>What</span> <span m=''4245570''>if</span>
  <span m=''4245660''>you</span> <span m=''4245760''>said,</span> <span m=''4246180''>oh,</span>
  <span m=''4246400''>this</span> <span m=''4246590''>bar</span> <span m=''4246990''>can</span>
  <span m=''4247140''>change</span> <span m=''4247390''>within</span> <span m=''4247600''>epsilon?</span>
  <span m=''4248800''>Because</span> <span m=''4249040''>in</span> <span m=''4249210''>reality</span>
  <span m=''4249680''>you</span> <span m=''4249800''>could</span> <span m=''4249920''>probably</span>
  <span m=''4250200''>pull</span> <span m=''4250390''>the</span> <span m=''4250540''>metal</span>
  <span m=''4250610''>a</span> <span m=''4250720''>little</span> <span m=''4251000''>bit,</span>
  <span m=''4251280''>just</span> <span m=''4251460''>not</span> <span m=''4251600''>very</span>
  <span m=''4251760''>much.</span> </p><p><span m=''4253970''>Struts,</span> <span
  m=''4255330''>it''s</span> <span m=''4255420''>not</span> <span m=''4255600''>supposed</span>
  <span m=''4255820''>to</span> <span m=''4255880''>get</span> <span m=''4256000''>smaller.</span>
  <span m=''4256330''>Let''s</span> <span m=''4256490''>say</span> <span m=''4256620''>it
  can</span> <span m=''4256730''>get</span> <span m=''4257010''>epsilon</span> <span
  m=''4257400''>smaller</span> <span m=''4257940''>than it''s</span> <span m=''4258240''>supposed
  to.</span> <span m=''4260050''>It turns</span> <span m=''4260300''>out</span> <span
  m=''4260400''>if</span> <span m=''4260490''>you</span> <span m=''4260590''>take</span>
  <span m=''4260860''>some</span> <span m=''4261030''>tensegrity</span> <span m=''4261680''>that''s</span>
  <span m=''4261910''>rigid,</span> <span m=''4262900''>and</span> <span m=''4263050''>then</span>
  <span m=''4263190''>you</span> <span m=''4263330''>add</span> <span m=''4263640''>this</span>
  <span m=''4263820''>little</span> <span m=''4264040''>bit</span> <span m=''4264170''>of</span>
  <span m=''4264250''>flexibility</span> <span m=''4264920''>so</span> <span m=''4265030''>the</span>
  <span m=''4265110''>edges</span> <span m=''4265410''>can</span> <span m=''4265530''>change</span>
  <span m=''4265780''>in length</span> <span m=''4265960''>a</span> <span m=''4266020''>tiny</span>
  <span m=''4266480''>amount,</span> <span m=''4268210''>then</span> <span m=''4269550''>before</span>
  <span m=''4270710''>you</span> <span m=''4271040''>made</span> <span m=''4271210''>this</span>
  <span m=''4271360''>change</span> <span m=''4272350''>your</span> <span m=''4272460''>configuration</span>
  <span m=''4273000''>was</span> <span m=''4273310''>a point,</span> <span m=''4273680''>and</span>
  <span m=''4273980''>there</span> <span m=''4274110''>might have</span> <span m=''4274310''>been</span>
  <span m=''4274460''>other</span> <span m=''4274680''>stuff.</span> <span m=''4274970''>But</span>
  <span m=''4275350''>locally</span> <span m=''4275740''>you</span> <span m=''4275830''>couldn''t</span>
  <span m=''4275990''>move</span> <span m=''4276180''>at</span> <span m=''4276250''>all.</span>
  </p><p><span m=''4277070''>If</span> <span m=''4277210''>you</span> <span m=''4277350''>add</span>
  <span m=''4277500''>this</span> <span m=''4277630''>flexibility,</span> <span m=''4279170''>the</span>
  <span m=''4279300''>new</span> <span m=''4279500''>picture</span> <span m=''4281090''>is</span>
  <span m=''4281550''>a</span> <span m=''4281640''>point</span> <span m=''4282400''>with</span>
  <span m=''4282530''>a</span> <span m=''4282590''>tiny</span> <span m=''4282920''>ball</span>
  <span m=''4283190''>around</span> <span m=''4283490''>it.</span> <span m=''4284500''>And</span>
  <span m=''4284860''>whatever,</span> <span m=''4285460''>I</span> <span m=''4285540''>mean</span>
  <span m=''4285690''>this</span> <span m=''4285850''>might</span> <span m=''4286030''>change</span>
  <span m=''4286350''>a</span> <span m=''4286390''>little</span> <span m=''4286560''>bit</span>
  <span m=''4286710''>also.</span> <span m=''4288350''>But</span> <span m=''4288590''>the</span>
  <span m=''4288670''>point</span> <span m=''4288850''>is</span> <span m=''4288960''>this</span>
  <span m=''4289120''>point</span> <span m=''4289340''>doesn''t</span> <span m=''4289590''>get</span>
  <span m=''4289720''>much</span> <span m=''4289930''>bigger</span> <span m=''4290270''>when</span>
  <span m=''4290400''>you</span> <span m=''4290500''>add</span> <span m=''4290700''>just</span>
  <span m=''4290840''>a</span> <span m=''4290890''>little</span> <span m=''4291160''>bit</span>
  <span m=''4291270''>of</span> <span m=''4291340''>flexibility.</span> </p><p><span
  m=''4292170''>This</span> <span m=''4292350''>is</span> <span m=''4292480''>a</span>
  <span m=''4292540''>fact</span> <span m=''4293100''>that</span> <span m=''4293210''>was</span>
  <span m=''4293390''>known</span> <span m=''4294010''>in</span> <span m=''4294130''>rigidity</span>
  <span m=''4294530''>theory.</span> <span m=''4294780''>It''s called</span> <span
  m=''4294950''>sloppy</span> <span m=''4295440''>rigidity.</span> <span m=''4296920''>And</span>
  <span m=''4297240''>it''s</span> <span m=''4297360''>essentially</span> <span m=''4297820''>what''s</span>
  <span m=''4298030''>going</span> <span m=''4298290''>on</span> <span m=''4298430''>here--</span>
  <span m=''4299190''>that</span> <span m=''4299310''>we''re</span> <span m=''4299440''>adding</span>
  <span m=''4299680''>a</span> <span m=''4299730''>little</span> <span m=''4299960''>bit</span>
  <span m=''4300080''>of</span> <span m=''4300150''>perturbation.</span> <span m=''4300650''>Before</span>
  <span m=''4300940''>you</span> <span m=''4301010''>couldn''t</span> <span m=''4301160''>move</span>
  <span m=''4301360''>at</span> <span m=''4301420''>all.</span> <span m=''4302030''>Now
  you</span> <span m=''4302280''>can</span> <span m=''4302360''>move</span> <span
  m=''4302510''>a</span> <span m=''4302550''>little</span> <span m=''4302760''>bit.</span>
  <span m=''4302960''>We</span> <span m=''4303060''>just</span> <span m=''4303240''>had</span>
  <span m=''4303340''>to</span> <span m=''4303400''>generalize</span> <span m=''4303900''>from</span>
  <span m=''4304070''>regular</span> <span m=''4304400''>tensegrity</span> <span m=''4304960''>so</span>
  <span m=''4305140''>these</span> <span m=''4305780''>weird</span> <span m=''4306030''>tensegrities</span>
  <span m=''4306690''>with</span> <span m=''4306860''>sliding</span> <span m=''4307250''>struts.</span>
  </p><p><span m=''4309620''>And</span> <span m=''4310030''>this is</span> <span m=''4310380''>kind</span>
  <span m=''4310640''>of</span> <span m=''4310750''>intuitive.</span> <span m=''4312160''>To</span>
  <span m=''4312320''>really</span> <span m=''4312580''>check</span> <span m=''4312890''>it</span>
  <span m=''4313160''>you</span> <span m=''4313350''>just</span> <span m=''4314020''>need</span>
  <span m=''4314180''>to</span> <span m=''4314260''>check</span> <span m=''4314520''>that
  the</span> <span m=''4314770''>constraints</span> <span m=''4315230''>on</span>
  <span m=''4315330''>edges</span> <span m=''4315600''>and</span> <span m=''4315690''>struts</span>
  <span m=''4316100''>are</span> <span m=''4316860''>closed</span> <span m=''4317190''>sets,</span>
  <span m=''4317650''>and then</span> <span m=''4318010''>the</span> <span m=''4318520''>have</span>
  <span m=''4318790''>to</span> <span m=''4318880''>behave</span> <span m=''4319140''>this</span>
  <span m=''4319300''>way.</span> <span m=''4319840''>But</span> <span m=''4319980''>you</span>
  <span m=''4320090''>can</span> <span m=''4320220''>actually</span> <span m=''4320480''>compute</span>
  <span m=''4320920''>how</span> <span m=''4321550''>quickly</span> <span m=''4321890''>they</span>
  <span m=''4322060''>change.</span> <span m=''4323000''>It''s</span> <span m=''4323150''>just</span>
  <span m=''4323320''>messy.</span> <span m=''4325470''>So I''ll</span> <span m=''4325680''>leave</span>
  <span m=''4325830''>it</span> <span m=''4325980''>at</span> <span m=''4326080''>that.</span>
  <span m=''4327090''>Hey,</span> <span m=''4327270''>there''s</span> <span m=''4327450''>a</span>
  <span m=''4327520''>little</span> <span m=''4328410''>proof</span> <span m=''4328930''>addition,</span>
  <span m=''4329795''>glad</span> <span m=''4330170''>I</span> <span m=''4330350''>still</span>
  <span m=''4330570''>remember</span> <span m=''4330850''>it.</span> </p><p><span
  m=''4332150''>Other</span> <span m=''4332350''>questions?</span> <span m=''4332750''>This
  is</span> <span m=''4332960''>the</span> <span m=''4333120''>end</span> <span m=''4333290''>of</span>
  <span m=''4333400''>2D</span> <span m=''4333780''>trees.</span> <span m=''4334970''>And</span>
  <span m=''4335160''>now</span> <span m=''4335290''>I</span> <span m=''4335310''>want</span>
  <span m=''4335470''>to</span> <span m=''4335540''>talk</span> <span m=''4335780''>briefly</span>
  <span m=''4336210''>about</span> <span m=''4337030''>3D</span> <span m=''4337720''>chains.</span>
  <span m=''4339920''>So we</span> <span m=''4340050''>did</span> <span m=''4340220''>this</span>
  <span m=''4340390''>one,</span> <span m=''4341951''>now</span> <span m=''4342330''>I</span>
  <span m=''4342380''>want</span> <span m=''4342540''>to</span> <span m=''4342610''>do</span>
  <span m=''4342720''>this</span> <span m=''4342940''>one.</span> </p><p><span m=''4360230''>Actually</span>
  <span m=''4360480''>this</span> <span m=''4360680''>is</span> <span m=''4360790''>one</span>
  <span m=''4360950''>of</span> <span m=''4361000''>the</span> <span m=''4361330''>oldest</span>
  <span m=''4361690''>results,</span> <span m=''4362320''>from</span> <span m=''4362450''>1998.</span>
  <span m=''4363860''>So</span> <span m=''4364270''>right</span> <span m=''4364470''>around</span>
  <span m=''4364670''>the</span> <span m=''4364730''>same</span> <span m=''4364920''>time</span>
  <span m=''4365200''>as</span> <span m=''4365370''>the</span> <span m=''4365600''>locked</span>
  <span m=''4365820''>trees.</span> <span m=''4384190''>I</span> <span m=''4384290''>may
  have shown</span> <span m=''4384680''>this</span> <span m=''4384830''>example</span>
  <span m=''4385250''>last</span> <span m=''4385530''>time,</span> <span m=''4385840''>or</span>
  <span m=''4386340''>in</span> <span m=''4386420''>lecture</span> <span m=''4386720''>one.</span>
  <span m=''4387040''>But</span> <span m=''4387530''>here</span> <span m=''4387730''>it
  is</span> <span m=''4387880''>again.</span> </p><p><span m=''4389040''>Three</span>
  <span m=''4389430''>bars</span> <span m=''4389790''>in</span> <span m=''4389870''>the</span>
  <span m=''4389940''>center,</span> <span m=''4391170''>and</span> <span m=''4391550''>two</span>
  <span m=''4391770''>really</span> <span m=''4392010''>long</span> <span m=''4392280''>bars</span>
  <span m=''4392560''>in</span> <span m=''4392650''>the</span> <span m=''4392760''>ends.</span>
  <span m=''4393210''>We</span> <span m=''4393340''>call</span> <span m=''4393530''>this</span>
  <span m=''4394770''>knitting</span> <span m=''4395040''>needles,</span> <span m=''4405300''>because
  it''s</span> <span m=''4405470''>like</span> <span m=''4405660''>two</span> <span
  m=''4406220''>knitting</span> <span m=''4406430''>needles</span> <span m=''4407040''>with</span>
  <span m=''4407400''>a</span> <span m=''4407450''>short</span> <span m=''4407750''>string</span>
  <span m=''4408010''>connecting</span> <span m=''4408360''>them,</span> <span m=''4408620''>tied</span>
  <span m=''4408950''>in</span> <span m=''4409070''>a</span> <span m=''4409120''>knot,</span>
  <span m=''4409630''>sort</span> <span m=''4409890''>of.</span> </p><p><span m=''4410400''>Topologically</span>
  <span m=''4411140''>this</span> <span m=''4411340''>is</span> <span m=''4411460''>not</span>
  <span m=''4411860''>knotted.</span> <span m=''4411980''>If</span> <span m=''4412120''>you</span>
  <span m=''4412280''>could</span> <span m=''4412930''>add</span> <span m=''4413240''>extra</span>
  <span m=''4413520''>creases</span> <span m=''4413920''>here</span> <span m=''4414410''>you</span>
  <span m=''4414560''>could</span> <span m=''4414710''>pull</span> <span m=''4414870''>that</span>
  <span m=''4415050''>through,</span> <span m=''4415270''>no</span> <span m=''4415400''>problem.</span>
  <span m=''4416640''>But</span> <span m=''4416840''>if this</span> <span m=''4417010''>is</span>
  <span m=''4417120''>rigid,</span> <span m=''4418010''>like a</span> <span m=''4418310''>linkage,</span>
  <span m=''4420090''>then</span> <span m=''4420960''>this</span> <span m=''4421200''>thing</span>
  <span m=''4421420''>is</span> <span m=''4421540''>locked</span> <span m=''4426290''>provided</span>
  <span m=''4431060''>each</span> <span m=''4431500''>end</span> <span m=''4431830''>bar</span>
  <span m=''4438210''>has</span> <span m=''4438970''>length</span> <span m=''4441740''>strictly</span>
  <span m=''4442220''>greater</span> <span m=''4442550''>than</span> <span m=''4443040''>the</span>
  <span m=''4443140''>sum</span> <span m=''4443670''>of</span> <span m=''4444000''>the</span>
  <span m=''4444080''>middle</span> <span m=''4444320''>bars.</span> </p><p><span
  m=''4451730''>So</span> <span m=''4451980''>there''s</span> <span m=''4452170''>three</span>
  <span m=''4452450''>middle</span> <span m=''4452660''>bars</span> <span m=''4453020''>here,</span>
  <span m=''4454140''>add</span> <span m=''4454350''>up</span> <span m=''4454460''>their</span>
  <span m=''4454580''>lengths,</span> <span m=''4455230''>it</span> <span m=''4455350''>should</span>
  <span m=''4455500''>be</span> <span m=''4455600''>shorter</span> <span m=''4456070''>than</span>
  <span m=''4456300''>this</span> <span m=''4456470''>one</span> <span m=''4456680''>and
  it</span> <span m=''4456740''>should</span> <span m=''4456920''>be</span> <span
  m=''4457010''>shorter</span> <span m=''4457320''>than</span> <span m=''4457500''>this</span>
  <span m=''4457690''>one.</span> <span m=''4459050''>That''s</span> <span m=''4459360''>the</span>
  <span m=''4459750''>cutoff.</span> <span m=''4460570''>And</span> <span m=''4460710''>I</span>
  <span m=''4460740''>believe</span> <span m=''4461930''>once</span> <span m=''4462180''>it''s</span>
  <span m=''4462570''>the</span> <span m=''4462670''>other</span> <span m=''4462790''>way</span>
  <span m=''4462890''>around,</span> <span m=''4463430''>this</span> <span m=''4463600''>is</span>
  <span m=''4463720''>not</span> <span m=''4463900''>locked.</span> </p><p><span m=''4476370''>Sadly,</span>
  <span m=''4476820''>rules</span> <span m=''4477070''>one</span> <span m=''4477250''>and</span>
  <span m=''4477380''>do</span> <span m=''4477730''>not</span> <span m=''4478330''>prove</span>
  <span m=''4478540''>this</span> <span m=''4478790''>thing</span> <span m=''4478940''>is</span>
  <span m=''4479060''>locked.</span> <span m=''4479900''>They</span> <span m=''4480050''>only</span>
  <span m=''4480220''>work</span> <span m=''4480420''>in</span> <span m=''4480510''>two</span>
  <span m=''4480630''>dimensions.</span> <span m=''4481920''>But</span> <span m=''4482110''>for</span>
  <span m=''4482190''>this</span> <span m=''4482390''>one</span> <span m=''4482560''>example--</span>
  <span m=''4483990''>and</span> <span m=''4484650''>to tell</span> <span m=''4484940''>you</span>
  <span m=''4485030''>the</span> <span m=''4485090''>truth,</span> <span m=''4485340''>this
  is</span> <span m=''4485500''>pretty</span> <span m=''4485700''>much</span> <span
  m=''4485880''>the</span> <span m=''4486000''>only</span> <span m=''4486280''>example</span>
  <span m=''4487290''>of</span> <span m=''4487490''>a</span> <span m=''4487540''>locked</span>
  <span m=''4487930''>open</span> <span m=''4488220''>chain</span> <span m=''4488540''>that</span>
  <span m=''4488630''>we</span> <span m=''4488740''>have--</span> <span m=''4491220''>there''s</span>
  <span m=''4491320''>a</span> <span m=''4491400''>really</span> <span m=''4491680''>simple,</span>
  <span m=''4492830''>nice</span> <span m=''4493040''>proof.</span> <span m=''4494180''>Let</span>
  <span m=''4494260''>me</span> <span m=''4494550''>draw</span> <span m=''4494750''>the</span>
  <span m=''4494870''>picture</span> <span m=''4495150''>again.</span> </p><p><span
  m=''4495996''>AUDIENCE: Do you need</span> <span m=''4496482''>the bottom one?</span>
  </p><p><span m=''4499400''>PROFESSOR: You''re</span> <span m=''4499560''>asking</span>
  <span m=''4499880''>do</span> <span m=''4500020''>I</span> <span m=''4500100''>need</span>
  <span m=''4500310''>three</span> <span m=''4500570''>bars</span> <span m=''4500910''>in</span>
  <span m=''4501000''>the</span> <span m=''4501100''>center,</span> <span m=''4501690''>or</span>
  <span m=''4501820''>could</span> <span m=''4501980''>I</span> <span m=''4502030''>get</span>
  <span m=''4502220''>away</span> <span m=''4502460''>with</span> <span m=''4503370''>two?</span>
  <span m=''4504010''>In</span> <span m=''4504080''>fact,</span> <span m=''4504410''>to</span>
  <span m=''4504510''>draw</span> <span m=''4504750''>this</span> <span m=''4504960''>in</span>
  <span m=''4505060''>3D</span> <span m=''4505520''>you</span> <span m=''4505620''>need</span>
  <span m=''4505860''>three</span> <span m=''4506030''>bars.</span> <span m=''4507780''>That''s</span>
  <span m=''4508190''>maybe</span> <span m=''4508450''>not</span> <span m=''4508630''>obvious.</span>
  </p><p><span m=''4513370''>But</span> <span m=''4513510''>if</span> <span m=''4513690''>you</span>
  <span m=''4513810''>tried</span> <span m=''4514120''>to</span> <span m=''4514230''>draw</span>
  <span m=''4514460''>it</span> <span m=''4514530''>would</span> <span m=''4514660''>just</span>
  <span m=''4514890''>four</span> <span m=''4515090''>bars,</span> <span m=''4516990''>like</span>
  <span m=''4517560''>this,</span> <span m=''4521720''>it''s</span> <span m=''4521890''>not</span>
  <span m=''4522050''>really</span> <span m=''4522250''>possible</span> <span m=''4522780''>because</span>
  <span m=''4523130''>these</span> <span m=''4523330''>three</span> <span m=''4523540''>points</span>
  <span m=''4523980''>are</span> <span m=''4524190''>coplanar,</span> <span m=''4525290''>as</span>
  <span m=''4525670''>all</span> <span m=''4525930''>three</span> <span m=''4526130''>points</span>
  <span m=''4526420''>are,</span> <span m=''4527770''>and</span> <span m=''4528020''>then</span>
  <span m=''4528890''>yeah.</span> <span m=''4529672''>You can''t</span> <span m=''4530010''>get</span>
  <span m=''4530170''>this</span> <span m=''4530310''>weaving</span> <span m=''4530590''>pattern.</span>
  </p><p><span m=''4531550''>This</span> <span m=''4531730''>guy''s</span> <span m=''4531940''>going</span>
  <span m=''4532070''>to</span> <span m=''4532120''>be</span> <span m=''4532260''>either</span>
  <span m=''4532430''>above</span> <span m=''4532670''>or</span> <span m=''4532740''>below</span>
  <span m=''4532990''>the</span> <span m=''4533090''>plane.</span> <span m=''4533490''>And</span>
  <span m=''4533600''>this</span> <span m=''4533740''>guy''s</span> <span m=''4533920''>going</span>
  <span m=''4534030''>to</span> <span m=''4534100''>be</span> <span m=''4534520''>above</span>
  <span m=''4534780''>or</span> <span m=''4534850''>below</span> <span m=''4535080''>the</span>
  <span m=''4535170''>plane.</span> <span m=''4535460''>And</span> <span m=''4535640''>in</span>
  <span m=''4535710''>all</span> <span m=''4535840''>cases,</span> <span m=''4536310''>you</span>
  <span m=''4536410''>don''t</span> <span m=''4536490''>get</span> <span m=''4536630''>this</span>
  <span m=''4536810''>weaving.</span> <span m=''4539030''>So</span> <span m=''4539230''>you</span>
  <span m=''4539380''>really</span> <span m=''4539580''>need</span> <span m=''4540270''>the</span>
  <span m=''4540410''>five.</span> </p><p><span m=''4541540''>This</span> <span m=''4541700''>is</span>
  <span m=''4541810''>the</span> <span m=''4541900''>minimum.</span> <span m=''4542240''>You</span>
  <span m=''4542350''>can</span> <span m=''4542480''>prove</span> <span m=''4542710''>all</span>
  <span m=''4542970''>four</span> <span m=''4543270''>bar</span> <span m=''4544030''>3D</span>
  <span m=''4544330''>chains</span> <span m=''4544760''>to</span> <span m=''4544860''>not</span>
  <span m=''4545070''>lock.</span> <span m=''4546370''>But</span> <span m=''4546460''>with</span>
  <span m=''4546630''>five</span> <span m=''4547080''>you</span> <span m=''4547230''>can</span>
  <span m=''4547350''>do</span> <span m=''4547490''>it.</span> <span m=''4550320''>Good</span>
  <span m=''4550470''>question.</span> </p><p><span m=''4552290''>So</span> <span
  m=''4552620''>here''s</span> <span m=''4552900''>how</span> <span m=''4553040''>we''re</span>
  <span m=''4553150''>going</span> <span m=''4553260''>to</span> <span m=''4553330''>prove</span>
  <span m=''4553680''>that this</span> <span m=''4553880''>thing</span> <span m=''4554100''>is</span>
  <span m=''4554230''>locked.</span> <span m=''4558860''>So</span> <span m=''4559040''>there</span>
  <span m=''4559160''>are</span> <span m=''4559180''>these</span> <span m=''4559380''>three</span>
  <span m=''4559600''>edges,</span> <span m=''4560020''>they</span> <span m=''4560120''>have</span>
  <span m=''4560300''>various</span> <span m=''4560650''>lengths,</span> <span m=''4561050''>who</span>
  <span m=''4561140''>knows?</span> <span m=''4561980''>But</span> <span m=''4562520''>add
  up</span> <span m=''4562860''>the</span> <span m=''4562950''>lengths,</span> <span
  m=''4563290''>divide</span> <span m=''4563630''>by</span> <span m=''4563770''>2,</span>
  <span m=''4564310''>and</span> <span m=''4564470''>measure</span> <span m=''4564860''>out</span>
  <span m=''4565070''>that</span> <span m=''4565370''>far.</span> <span m=''4566130''>So</span>
  <span m=''4566300''>I''m</span> <span m=''4566380''>going</span> <span m=''4566480''>to</span>
  <span m=''4566540''>call</span> <span m=''4566730''>that</span> <span m=''4566960''>the</span>
  <span m=''4567040''>midpoint</span> <span m=''4568110''>of</span> <span m=''4568270''>those</span>
  <span m=''4568480''>three</span> <span m=''4568690''>segments.</span> </p><p><span
  m=''4572390''>I</span> <span m=''4572500''>want</span> <span m=''4572720''>to</span>
  <span m=''4572790''>center</span> <span m=''4573240''>a</span> <span m=''4573290''>ball</span>
  <span m=''4573550''>here.</span> <span m=''4575750''>It''s</span> <span m=''4576050''>going</span>
  <span m=''4576180''>to</span> <span m=''4576260''>look</span> <span m=''4580712''>something</span>
  <span m=''4581170''>like</span> <span m=''4581370''>that.</span> <span m=''4582780''>It''s</span>
  <span m=''4582870''>a</span> <span m=''4582930''>3D</span> <span m=''4583380''>ball</span>
  <span m=''4584520''>centered</span> <span m=''4584980''>there.</span> <span m=''4585900''>So</span>
  <span m=''4586260''>it''s</span> <span m=''4586840''>a</span> <span m=''4586880''>ball,</span>
  <span m=''4592240''>diameter</span> <span m=''4596220''>equal</span> <span m=''4596580''>to</span>
  <span m=''4596800''>the</span> <span m=''4596920''>sum</span> <span m=''4597300''>of</span>
  <span m=''4597430''>the</span> <span m=''4597510''>middle</span> <span m=''4597730''>bars.</span>
  <span m=''4602190''>So</span> <span m=''4602380''>radius</span> <span m=''4602740''>is</span>
  <span m=''4602830''>half</span> <span m=''4603070''>that.</span> </p><p><span m=''4603640''>And</span>
  <span m=''4604100''>the</span> <span m=''4604170''>center</span> <span m=''4607050''>is</span>
  <span m=''4607330''>the</span> <span m=''4607400''>midpoint</span> <span m=''4614230''>of</span>
  <span m=''4614540''>the sum</span> <span m=''4614850''>of the</span> <span m=''4614920''>middle</span>
  <span m=''4615090''>bars,</span> <span m=''4615360''>whatever.</span> <span m=''4619970''>So</span>
  <span m=''4620210''>the</span> <span m=''4620340''>radius</span> <span m=''4620820''>is</span>
  <span m=''4620950''>half</span> <span m=''4621440''>the</span> <span m=''4621550''>sum</span>
  <span m=''4621800''>of</span> <span m=''4621850''>the</span> <span m=''4621920''>middle</span>
  <span m=''4622110''>bars.</span> <span m=''4622420''>And</span> <span m=''4622520''>this</span>
  <span m=''4622690''>is</span> <span m=''4622810''>at</span> <span m=''4623000''>half</span>
  <span m=''4623500''>the</span> <span m=''4623580''>sum</span> <span m=''4623800''>of</span>
  <span m=''4623850''>the</span> <span m=''4623910''>middle</span> <span m=''4624120''>bars.</span>
  <span m=''4625050''>Therefore</span> <span m=''4625720''>these</span> <span m=''4625910''>middle</span>
  <span m=''4626110''>bars</span> <span m=''4626670''>stay</span> <span m=''4627140''>inside</span>
  <span m=''4628880''>the</span> <span m=''4628990''>ball.</span> </p><p><span m=''4631290''>Maybe</span>
  <span m=''4631670''>they</span> <span m=''4631790''>touch</span> <span m=''4632030''>the</span>
  <span m=''4632100''>boundary.</span> <span m=''4633280''>But</span> <span m=''4633660''>they''re</span>
  <span m=''4633780''>inside</span> <span m=''4634055''>or</span> <span m=''4634330''>on</span>
  <span m=''4634440''>the</span> <span m=''4634500''>boundary</span> <span m=''4634890''>of</span>
  <span m=''4634980''>the</span> <span m=''4635050''>ball.</span> <span m=''4636570''>So</span>
  <span m=''4636740''>that</span> <span m=''4636850''>means</span> <span m=''4637100''>the</span>
  <span m=''4639430''>middle</span> <span m=''4639690''>bars</span> <span m=''4641790''>are</span>
  <span m=''4641980''>in</span> <span m=''4642180''>the</span> <span m=''4642290''>ball.</span>
  <span m=''4646640''>Maybe</span> <span m=''4646870''>just</span> <span m=''4647120''>barely,</span>
  <span m=''4647710''>but</span> <span m=''4648640''>no</span> <span m=''4648720''>matter</span>
  <span m=''4648970''>how</span> <span m=''4649170''>you</span> <span m=''4649310''>move</span>
  <span m=''4649490''>this</span> <span m=''4649690''>thing--</span> <span m=''4650340''>I</span>
  <span m=''4650430''>mean</span> <span m=''4650670''>if</span> <span m=''4651020''>you</span>
  <span m=''4651300''>move</span> <span m=''4651580''>this</span> <span m=''4651790''>point</span>
  <span m=''4652110''>then</span> <span m=''4652270''>the</span> <span m=''4652370''>ball</span>
  <span m=''4652630''>moves</span> <span m=''4652870''>with</span> <span m=''4653050''>it.</span>
  <span m=''4653870''>So</span> <span m=''4654050''>no</span> <span m=''4654140''>matter</span>
  <span m=''4654310''>how</span> <span m=''4654520''>this</span> <span m=''4654680''>thing</span>
  <span m=''4654840''>folds,</span> <span m=''4655640''>those</span> <span m=''4655860''>three</span>
  <span m=''4656020''>bar</span> <span m=''4656280''>stay</span> <span m=''4656480''>inside</span>
  <span m=''4656780''>the</span> <span m=''4656850''>ball.</span> </p><p><span m=''4657390''>What</span>
  <span m=''4657570''>about</span> <span m=''4657970''>these</span> <span m=''4658200''>bars?</span>
  <span m=''4658470''>Or</span> <span m=''4658530''>what</span> <span m=''4658680''>about</span>
  <span m=''4658900''>the</span> <span m=''4659020''>endpoints?</span> <span m=''4661000''>Well</span>
  <span m=''4661180''>if</span> <span m=''4661340''>this</span> <span m=''4661550''>point</span>
  <span m=''4661810''>is</span> <span m=''4661910''>inside</span> <span m=''4662280''>the</span>
  <span m=''4662350''>ball,</span> <span m=''4662590''>which</span> <span m=''4662770''>it</span>
  <span m=''4662840''>is,</span> <span m=''4663090''>and</span> <span m=''4663190''>this</span>
  <span m=''4663350''>point</span> <span m=''4663550''>is</span> <span m=''4663640''>inside</span>
  <span m=''4663940''>the</span> <span m=''4664000''>ball,</span> <span m=''4664240''>which</span>
  <span m=''4664430''>it</span> <span m=''4664510''>is,</span> <span m=''4665500''>then</span>
  <span m=''4666750''>this</span> <span m=''4666930''>thing</span> <span m=''4667600''>is</span>
  <span m=''4667840''>longer</span> <span m=''4668440''>than</span> <span m=''4668620''>the</span>
  <span m=''4668750''>diameter</span> <span m=''4669400''>of</span> <span m=''4669490''>the</span>
  <span m=''4669570''>ball.</span> <span m=''4670530''>This</span> <span m=''4670680''>thing</span>
  <span m=''4670810''>is</span> <span m=''4670910''>greater</span> <span m=''4671290''>than</span>
  <span m=''4671470''>the</span> <span m=''4671600''>sum</span> <span m=''4671830''>of</span>
  <span m=''4671880''>the</span> <span m=''4671960''>middle</span> <span m=''4672170''>bars.</span>
  <span m=''4672880''>The</span> <span m=''4672980''>diameter</span> <span m=''4673440''>of
  the</span> <span m=''4673550''>ball is</span> <span m=''4673840''>the</span> <span
  m=''4673920''>sum</span> <span m=''4674120''>of</span> <span m=''4674170''>the</span>
  <span m=''4674240''>middle</span> <span m=''4674420''>bars.</span> </p><p><span
  m=''4674630''>So</span> <span m=''4674760''>if</span> <span m=''4674860''>I</span>
  <span m=''4674900''>take</span> <span m=''4675070''>any</span> <span m=''4675300''>point</span>
  <span m=''4675560''>inside</span> <span m=''4675920''>the</span> <span m=''4675990''>ball</span>
  <span m=''4676820''>and</span> <span m=''4677550''>move</span> <span m=''4677860''>straight</span>
  <span m=''4678340''>from</span> <span m=''4678510''>there</span> <span m=''4679300''>by</span>
  <span m=''4680200''>the</span> <span m=''4680420''>radius</span> <span m=''4680880''>of</span>
  <span m=''4681030''>the--</span> <span m=''4681790''>more</span> <span m=''4682170''>than</span>
  <span m=''4682400''>the</span> <span m=''4682760''>diameter</span> <span m=''4683220''>of</span>
  <span m=''4683310''>the</span> <span m=''4683370''>ball,</span> <span m=''4683720''>I</span>
  <span m=''4683810''>must</span> <span m=''4684090''>go</span> <span m=''4684210''>outside</span>
  <span m=''4684640''>the</span> <span m=''4684710''>ball.</span> <span m=''4686500''>So</span>
  <span m=''4688260''>the</span> <span m=''4688430''>endpoints</span> <span m=''4691780''>are</span>
  <span m=''4692270''>outside</span> <span m=''4692770''>the</span> <span m=''4692840''>ball.</span>
  </p><p><span m=''4696530''>How</span> <span m=''4696770''>the</span> <span m=''4696850''>heck</span>
  <span m=''4697100''>are you</span> <span m=''4697240''>going</span> <span m=''4697370''>untie</span>
  <span m=''4697750''>that</span> <span m=''4697960''>not</span> <span m=''4698250''>when</span>
  <span m=''4698410''>all</span> <span m=''4698720''>of</span> <span m=''4698840''>the</span>
  <span m=''4698970''>interior</span> <span m=''4699320''>vertices</span> <span m=''4699760''>stay</span>
  <span m=''4700160''>inside</span> <span m=''4700440''>of</span> <span m=''4700480''>the</span>
  <span m=''4700560''>ball,</span> <span m=''4701120''>and</span> <span m=''4701290''>these</span>
  <span m=''4701470''>guys</span> <span m=''4701690''>stay</span> <span m=''4701910''>outside</span>
  <span m=''4702270''>the</span> <span m=''4702340''>ball?</span> <span m=''4702920''>To</span>
  <span m=''4703070''>formalize</span> <span m=''4703580''>how</span> <span m=''4703740''>the</span>
  <span m=''4703820''>heck,</span> <span m=''4704520''>you</span> <span m=''4704660''>can</span>
  <span m=''4704860''>say</span> <span m=''4706370''>well</span> <span m=''4708325''>if</span>
  <span m=''4708600''>you</span> <span m=''4708960''>ignore</span> <span m=''4709350''>what''s</span>
  <span m=''4709540''>inside</span> <span m=''4709850''>the</span> <span m=''4709920''>ball--</span>
  <span m=''4710130''>something''s</span> <span m=''4710510''>happening</span> <span
  m=''4710870''>there,</span> <span m=''4711030''>who</span> <span m=''4711130''>knows?</span>
  <span m=''4711960''>But</span> <span m=''4712070''>outside</span> <span m=''4712590''>it''s</span>
  <span m=''4712930''>like</span> <span m=''4713090''>there''s</span> <span m=''4713240''>a</span>
  <span m=''4713290''>ball</span> <span m=''4713600''>and</span> <span m=''4713670''>there''s</span>
  <span m=''4713800''>two</span> <span m=''4713950''>sticks</span> <span m=''4714300''>coming</span>
  <span m=''4714570''>out</span> <span m=''4714700''>of</span> <span m=''4714800''>it.</span>
  <span m=''4716250''>So</span> <span m=''4717490''>you</span> <span m=''4717750''>can</span>
  <span m=''4718100''>just</span> <span m=''4718360''>imagine,</span> <span m=''4718760''>for</span>
  <span m=''4718870''>example,</span> <span m=''4719310''>tying</span> <span m=''4719760''>a</span>
  <span m=''4719860''>string</span> <span m=''4721380''>between</span> <span m=''4721840''>the</span>
  <span m=''4721930''>two</span> <span m=''4722110''>ends.</span> </p><p><span m=''4723640''>And</span>
  <span m=''4724260''>something</span> <span m=''4724570''>happens</span> <span m=''4725410''>in</span>
  <span m=''4725660''>the</span> <span m=''4725760''>inside.</span> <span m=''4726160''>But</span>
  <span m=''4726540''>if</span> <span m=''4726690''>you</span> <span m=''4726790''>think</span>
  <span m=''4727000''>of</span> <span m=''4727160''>just</span> <span m=''4727440''>from</span>
  <span m=''4727570''>the</span> <span m=''4727670''>outside</span> <span m=''4728100''>perspective,</span>
  <span m=''4728890''>these</span> <span m=''4728990''>sticks</span> <span m=''4729260''>just</span>
  <span m=''4729410''>move</span> <span m=''4729600''>around.</span> <span m=''4729850''>It''s</span>
  <span m=''4729950''>really</span> <span m=''4730180''>easy</span> <span m=''4730430''>to</span>
  <span m=''4730620''>not</span> <span m=''4730920''>tangle</span> <span m=''4731230''>this</span>
  <span m=''4731400''>cord</span> <span m=''4733580''>when</span> <span m=''4733920''>these</span>
  <span m=''4734020''>sticks</span> <span m=''4734290''>move</span> <span m=''4734470''>around.</span>
  </p><p><span m=''4736120''>So</span> <span m=''4736290''>now,</span> <span m=''4737230''>in</span>
  <span m=''4737420''>order</span> <span m=''4738230''>for</span> <span m=''4738420''>this</span>
  <span m=''4738650''>thing</span> <span m=''4738840''>to</span> <span m=''4738940''>become</span>
  <span m=''4739260''>unlocked,</span> <span m=''4740510''>to</span> <span m=''4740710''>straighten</span>
  <span m=''4741080''>out</span> <span m=''4741270''>for</span> <span m=''4741370''>example,</span>
  <span m=''4742690''>somehow</span> <span m=''4743210''>inside</span> <span m=''4744210''>you</span>
  <span m=''4744260''>have</span> <span m=''4744470''>to</span> <span m=''4744590''>do</span>
  <span m=''4744780''>some</span> <span m=''4744980''>magic</span> <span m=''4746050''>to</span>
  <span m=''4746170''>get</span> <span m=''4746330''>rid</span> <span m=''4746470''>of</span>
  <span m=''4746570''>this</span> <span m=''4746740''>topology.</span> <span m=''4748120''>Well</span>
  <span m=''4748260''>what do</span> <span m=''4748460''>I</span> <span m=''4748520''>mean?</span>
  <span m=''4749190''>Well</span> <span m=''4750230''>if</span> <span m=''4750410''>you</span>
  <span m=''4750530''>could</span> <span m=''4750680''>do</span> <span m=''4750970''>it</span>
  <span m=''4751500''>inside,</span> <span m=''4752110''>you</span> <span m=''4752230''>could</span>
  <span m=''4752910''>do</span> <span m=''4753170''>that</span> <span m=''4753350''>motion</span>
  <span m=''4753790''>even</span> <span m=''4754120''>when</span> <span m=''4754260''>there''s</span>
  <span m=''4754440''>a</span> <span m=''4754490''>string</span> <span m=''4754810''>tied</span>
  <span m=''4755070''>out</span> <span m=''4755210''>here.</span> </p><p><span m=''4756210''>But</span>
  <span m=''4756400''>when</span> <span m=''4756530''>I</span> <span m=''4756600''>tie</span>
  <span m=''4756820''>the</span> <span m=''4756950''>string</span> <span m=''4757230''>out</span>
  <span m=''4757300''>here,</span> <span m=''4757550''>it</span> <span m=''4757710''>is</span>
  <span m=''4758050''>a knot.</span> <span m=''4758330''>It''s</span> <span m=''4758460''>a</span>
  <span m=''4758510''>trefoil</span> <span m=''4758980''>know.</span> <span m=''4759830''>There''s</span>
  <span m=''4760020''>no</span> <span m=''4760280''>way to</span> <span m=''4760480''>untie</span>
  <span m=''4760680''>a trefoil</span> <span m=''4761320''>know</span> <span m=''4761490''>without</span>
  <span m=''4761760''>crossing.</span> <span m=''4763070''>So</span> <span m=''4763190''>either</span>
  <span m=''4763430''>there''s</span> <span m=''4763620''>crossing</span> <span m=''4763980''>in</span>
  <span m=''4764060''>here--</span> <span m=''4765090''>which</span> <span m=''4765230''>better</span>
  <span m=''4765440''>be--</span> <span m=''4766000''>or</span> <span m=''4766150''>there''s</span>
  <span m=''4766280''>crossing</span> <span m=''4766640''>out</span> <span m=''4766720''>here.</span>
  </p><p><span m=''4766890''>There</span> <span m=''4767010''>can''t</span> <span
  m=''4767330''>be</span> <span m=''4767480''>crossing</span> <span m=''4767900''>out</span>
  <span m=''4767990''>here.</span> <span m=''4768110''>It''s</span> <span m=''4768230''>just</span>
  <span m=''4768420''>two</span> <span m=''4768530''>sticks</span> <span m=''4768850''>and</span>
  <span m=''4768940''>a</span> <span m=''4769010''>string.</span> <span m=''4770180''>You</span>
  <span m=''4770330''>can</span> <span m=''4770500''>easily</span> <span m=''4770920''>arrange</span>
  <span m=''4771210''>the</span> <span m=''4771290''>motion</span> <span m=''4771580''>of</span>
  <span m=''4771670''>the</span> <span m=''4771740''>string</span> <span m=''4772010''>to</span>
  <span m=''4772100''>not</span> <span m=''4772300''>cross</span> <span m=''4772810''>the</span>
  <span m=''4772940''>two</span> <span m=''4773080''>sticks.</span> </p><p><span m=''4775130''>Therefore</span>
  <span m=''4776370''>this</span> <span m=''4776570''>thing</span> <span m=''4776810''>in</span>
  <span m=''4776940''>fact</span> <span m=''4777290''>cannot</span> <span m=''4777670''>untie.</span>
  <span m=''4778820''>Therefore</span> <span m=''4779110''>this</span> <span m=''4779300''>thing</span>
  <span m=''4779690''>is</span> <span m=''4779920''>locked,</span> <span m=''4780900''>cannot</span>
  <span m=''4781190''>straighten</span> <span m=''4781500''>out.</span> <span m=''4783880''>So</span>
  <span m=''4785260''>that''s</span> <span m=''4785490''>locked</span> <span m=''4785760''>3D</span>
  <span m=''4786030''>chains.</span> <span m=''4787060''>Let</span> <span m=''4787180''>me</span>
  <span m=''4787270''>tell</span> <span m=''4787490''>you</span> <span m=''4787570''>a</span>
  <span m=''4787600''>bunch</span> <span m=''4787810''>of</span> <span m=''4787860''>cool</span>
  <span m=''4788080''>open</span> <span m=''4788320''>problems.</span> </p><p><span
  m=''4789490''>This</span> <span m=''4789700''>is</span> <span m=''4789830''>really</span>
  <span m=''4790230''>the</span> <span m=''4790390''>only</span> <span m=''4790640''>good</span>
  <span m=''4790800''>example</span> <span m=''4791270''>of</span> <span m=''4791340''>a</span>
  <span m=''4791390''>locked</span> <span m=''4791630''>3D</span> <span m=''4791880''>chain</span>
  <span m=''4792120''>we</span> <span m=''4792210''>have.</span> <span m=''4793150''>And</span>
  <span m=''4793340''>it</span> <span m=''4793470''>has</span> <span m=''4793880''>length</span>
  <span m=''4794230''>ratios,</span> <span m=''4795250''>the</span> <span m=''4795300''>best</span>
  <span m=''4795580''>you</span> <span m=''4795680''>could</span> <span m=''4795820''>do</span>
  <span m=''4796040''>is</span> <span m=''4796170''>like</span> <span m=''4796420''>1</span>
  <span m=''4796900''>to</span> <span m=''4797180''>3</span> <span m=''4797440''>plus</span>
  <span m=''4797700''>epsilon.</span> <span m=''4799040''>If</span> <span m=''4799120''>each</span>
  <span m=''4799320''>of</span> <span m=''4799390''>these</span> <span m=''4799590''>is</span>
  <span m=''4799700''>length</span> <span m=''4799950''>1,</span> <span m=''4800590''>these</span>
  <span m=''4800800''>have</span> <span m=''4800960''>to</span> <span m=''4801060''>be</span>
  <span m=''4801210''>3</span> <span m=''4801380''>plus</span> <span m=''4801620''>epsilon.</span>
  </p><p><span m=''4802580''>Is</span> <span m=''4802790''>that</span> <span m=''4803150''>the</span>
  <span m=''4803230''>best?</span> <span m=''4804330''>Or</span> <span m=''4804510''>could</span>
  <span m=''4804700''>it</span> <span m=''4804810''>be,</span> <span m=''4805100''>for</span>
  <span m=''4805270''>example,</span> <span m=''4805960''>that</span> <span m=''4806800''>all</span>
  <span m=''4807010''>the</span> <span m=''4807130''>edges</span> <span m=''4807400''>or</span>
  <span m=''4807470''>between</span> <span m=''4808130''>length</span> <span m=''4808380''>1</span>
  <span m=''4808590''>and</span> <span m=''4808730''>2,</span> <span m=''4809530''>and</span>
  <span m=''4809720''>the</span> <span m=''4809800''>chain</span> <span m=''4810020''>is</span>
  <span m=''4810140''>locked?</span> <span m=''4810590''>We</span> <span m=''4810700''>don''t</span>
  <span m=''4810840''>know.</span> </p><p><span m=''4811920''>In</span> <span m=''4812050''>the</span>
  <span m=''4812120''>extreme</span> <span m=''4812460''>case,</span> <span m=''4812790''>what</span>
  <span m=''4812960''>if</span> <span m=''4813080''>all</span> <span m=''4813340''>the</span>
  <span m=''4813470''>edge</span> <span m=''4813620''>lengths</span> <span m=''4813840''>of</span>
  <span m=''4813900''>the</span> <span m=''4813990''>same,</span> <span m=''4814830''>all</span>
  <span m=''4815080''>length</span> <span m=''4815320''>1?</span> <span m=''4816550''>Is</span>
  <span m=''4816740''>there</span> <span m=''4816880''>a</span> <span m=''4816940''>locked</span>
  <span m=''4817510''>3D</span> <span m=''4817820''>chain?</span> <span m=''4818120''>We</span>
  <span m=''4818210''>now</span> <span m=''4818410''>know</span> <span m=''4818570''>there''s</span>
  <span m=''4818730''>a</span> <span m=''4818790''>locked</span> <span m=''4819170''>2D</span>
  <span m=''4819360''>tree,</span> <span m=''4821260''>but</span> <span m=''4822310''>for</span>
  <span m=''4822460''>chains</span> <span m=''4822830''>it''s</span> <span m=''4823200''>tricky.</span>
  <span m=''4823600''>It''s</span> <span m=''4823750''>even</span> <span m=''4824070''>open</span>
  <span m=''4824850''>if</span> <span m=''4825000''>you</span> <span m=''4825110''>add</span>
  <span m=''4825290''>thickness.</span> </p><p><span m=''4826170''>You</span> <span
  m=''4826290''>say,</span> <span m=''4826520''>hey,</span> <span m=''4827500''>let''s</span>
  <span m=''4827990''>think</span> <span m=''4828180''>about</span> <span m=''4828730''>a</span>
  <span m=''4828830''>3D</span> <span m=''4829890''>chain,</span> <span m=''4830970''>all</span>
  <span m=''4831190''>the</span> <span m=''4831330''>edge</span> <span m=''4831460''>lengths</span>
  <span m=''4831640''>are</span> <span m=''4831720''>the</span> <span m=''4831820''>same,</span>
  <span m=''4832630''>and</span> <span m=''4832900''>you</span> <span m=''4833010''>get</span>
  <span m=''4833170''>to</span> <span m=''4833240''>specify</span> <span m=''4833730''>some</span>
  <span m=''4834000''>radius</span> <span m=''4834530''>of</span> <span m=''4834730''>the</span>
  <span m=''4834800''>bars.</span> <span m=''4836500''>For a</span> <span m=''4836650''>while</span>
  <span m=''4836900''>I</span> <span m=''4836950''>thought</span> <span m=''4837180''>maybe</span>
  <span m=''4837400''>this</span> <span m=''4837580''>was</span> <span m=''4837680''>locked.</span>
  <span m=''4838020''>I</span> <span m=''4838070''>don''t</span> <span m=''4838230''>think</span>
  <span m=''4838380''>it</span> <span m=''4838450''>is.</span> <span m=''4840990''>We
  can</span> <span m=''4841290''>unfold.</span> </p><p><span m=''4842920''>All</span>
  <span m=''4843100''>of</span> <span m=''4843180''>these</span> <span m=''4843340''>questions</span>
  <span m=''4843730''>are</span> <span m=''4843850''>open,</span> <span m=''4845100''>and</span>
  <span m=''4845400''>pretty</span> <span m=''4845590''>fascinating.</span> <span
  m=''4846130''>Especially</span> <span m=''4846530''>because</span> <span m=''4846820''>proteins</span>
  <span m=''4847350''>are</span> <span m=''4847490''>a</span> <span m=''4847550''>lot</span>
  <span m=''4847850''>like</span> <span m=''4848620''>equilateral--</span> <span m=''4850300''>like</span>
  <span m=''4850430''>all</span> <span m=''4850650''>the edge</span> <span m=''4850880''>lengths</span>
  <span m=''4851100''>the</span> <span m=''4851150''>same--</span> <span m=''4852040''>3D</span>
  <span m=''4852410''>chains.</span> <span m=''4853840''>It''s</span> <span m=''4854020''>even</span>
  <span m=''4854310''>open</span> <span m=''4854610''>for</span> <span m=''4854920''>equilateral</span>
  <span m=''4855710''>3D</span> <span m=''4856290''>trees.</span> </p><p><span m=''4857580''>So</span>
  <span m=''4857700''>we</span> <span m=''4857770''>know</span> <span m=''4857910''>2D</span>
  <span m=''4858450''>equilateral</span> <span m=''4858940''>trees</span> <span m=''4859190''>can</span>
  <span m=''4859390''>lock.</span> <span m=''4859590''>But</span> <span m=''4859720''>3D,</span>
  <span m=''4861400''>it''s</span> <span m=''4861620''>open.</span> <span m=''4863190''>I</span>
  <span m=''4863260''>think</span> <span m=''4863410''>that''s</span> <span m=''4863590''>enough</span>
  <span m=''4863890''>open</span> <span m=''4864140''>problems.</span> <span m=''4864640''>Lots</span>
  <span m=''4864860''>of</span> <span m=''4864910''>cool</span> <span m=''4865090''>questions</span>
  <span m=''4865460''>here.</span> <span m=''4866490''>All right,</span> <span m=''4866840''>I</span>
  <span m=''4866900''>have</span> <span m=''4867200''>one</span> <span m=''4867370''>more.</span>
  <span m=''4867580''>It''s</span> <span m=''4867700''>just</span> <span m=''4867870''>fun.</span>
  </p><p><span m=''4868800''>Even</span> <span m=''4870040''>if</span> <span m=''4870210''>you</span>
  <span m=''4870310''>have</span> <span m=''4871790''>a</span> <span m=''4871840''>3D</span>
  <span m=''4872190''>chain</span> <span m=''4874810''>where</span> <span m=''4875120''>all</span>
  <span m=''4875350''>the</span> <span m=''4875480''>edges</span> <span m=''4875770''>are</span>
  <span m=''4875890''>on</span> <span m=''4876000''>top</span> <span m=''4876290''>of</span>
  <span m=''4876410''>each</span> <span m=''4876590''>other</span> <span m=''4876870''>on</span>
  <span m=''4877080''>a</span> <span m=''4877140''>line</span> <span m=''4877380''>segment--</span>
  <span m=''4877790''>it''s like</span> <span m=''4877940''>a</span> <span m=''4878010''>linear</span>
  <span m=''4878510''>tree</span> <span m=''4878940''>but</span> <span m=''4879080''>now</span>
  <span m=''4879260''>it''s</span> <span m=''4879370''>a</span> <span m=''4879450''>linear</span>
  <span m=''4880290''>3D</span> <span m=''4881000''>chain--</span> <span m=''4883180''>it''s</span>
  <span m=''4883460''>like</span> <span m=''4883620''>a</span> <span m=''4883670''>bundle</span>
  <span m=''4884130''>of</span> <span m=''4884290''>segments.</span> <span m=''4884880''>Is</span>
  <span m=''4885050''>that</span> <span m=''4885310''>locked?</span> <span m=''4886780''>I</span>
  <span m=''4886860''>don''t</span> <span m=''4887050''>think</span> <span m=''4887260''>so.</span>
  <span m=''4887580''>But</span> <span m=''4887780''>even</span> <span m=''4888010''>that</span>
  <span m=''4888200''>is</span> <span m=''4888330''>tricky</span> <span m=''4888650''>to</span>
  <span m=''4888730''>come</span> <span m=''4888930''>up</span> <span m=''4889030''>with</span>
  <span m=''4889160''>algorithm.</span> </p><p><span m=''4890080''>Maybe</span> <span
  m=''4890200''>we''ll</span> <span m=''4890390''>work</span> <span m=''4890570''>on</span>
  <span m=''4890680''>some</span> <span m=''4890880''>of</span> <span m=''4890930''>these</span>
  <span m=''4891160''>in</span> <span m=''4891290''>the</span> <span m=''4891390''>problem</span>
  <span m=''4891630''>session.</span> <span m=''4892940''>That''s</span> <span m=''4893450''>it.</span>
  </p>'
type: course
uid: 9631a66a55cf940a72c3a1dd0aa3dc53

---
None