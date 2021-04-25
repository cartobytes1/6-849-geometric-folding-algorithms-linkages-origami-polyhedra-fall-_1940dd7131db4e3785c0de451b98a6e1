---
about_this_resource_text: <p><strong>Description:</strong> This lecture begins how
  to construct a gluing tree. Combinatorial bounds and algorithms are proved for gluing
  results, which include the general case, edge-to-edge, and bounded sharpness. The
  different gluings for the cross are also shown.</p> <p><strong>Speaker:</strong>
  Erik Demaine</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: 64Kp4kgRdzs
  parent_uid: 717265785f926c4605e4166360070c79
  title: Video-YouTube-Stream
  type: Video
  uid: 6b2786c54d7121955a967596f18b367f
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/64Kp4kgRdzs/default.jpg
  parent_uid: 717265785f926c4605e4166360070c79
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 0e5b4b2ec79d671c2ab276c1af0926d2
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: 717265785f926c4605e4166360070c79
  title: Video-iTunes U-MP4
  type: Video
  uid: 9b561217303075fe72e50a1616d94711
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_lec18_300k.mp4
  parent_uid: 717265785f926c4605e4166360070c79
  title: Video-Internet Archive-MP4
  type: Video
  uid: 1100f3e46076b721a6446ae271fd2d9f
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 64Kp4kgRdzs
  parent_uid: 717265785f926c4605e4166360070c79
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 67008c6ceb62ca401069d1d2f24d451d
- id: 64Kp4kgRdzs.srt
  parent_uid: 717265785f926c4605e4166360070c79
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-18-gluing-algorithms/64Kp4kgRdzs.srt
  title: 3play caption file
  type: null
  uid: ad750f015cb5682361f74ca0e8bbb84d
- id: 64Kp4kgRdzs.pdf
  parent_uid: 717265785f926c4605e4166360070c79
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-18-gluing-algorithms/64Kp4kgRdzs.pdf
  title: 3play pdf file
  type: null
  uid: fcebd9778044182ef88662b5542b9282
- id: Caption-3Play YouTube id-SRT
  parent_uid: 717265785f926c4605e4166360070c79
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b1a4176cd30c8e12ad2afae7e70734f3
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 717265785f926c4605e4166360070c79
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: cef31e94d7dd00cf45580ab8f87b4612
inline_embed_id: 39446937lecture18:gluingalgorithms25924247
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: lecture-18-gluing-algorithms
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-18-gluing-algorithms
template_type: Tabbed
title: 'Lecture 18: Gluing Algorithms'
transcript: '<p><span m=''3310''>PROFESSOR: All</span> <span m=''3400''>right,</span>
  <span m=''3600''>let''s</span> <span m=''3760''>get</span> <span m=''3870''>started.</span>
  <span m=''5620''>We</span> <span m=''5990''>are</span> <span m=''6210''>continuing</span>
  <span m=''6860''>our</span> <span m=''7180''>theme</span> <span m=''7710''>of</span>
  <span m=''8029''>folding</span> <span m=''8740''>polygons</span> <span m=''9470''>into</span>
  <span m=''11640''>convex</span> <span m=''12270''>polyhedra.</span> <span m=''14520''>Let''s</span>
  <span m=''15010''>do a</span> <span m=''15420''>quick</span> <span m=''16430''>reminder,</span>
  <span m=''17670''>we''re</span> <span m=''17790''>talking</span> <span m=''18050''>about</span>
  <span m=''18800''>gluing</span> <span m=''19200''>up</span> <span m=''19340''>the</span>
  <span m=''19450''>boundary</span> <span m=''20547''>of</span> <span m=''21421''>a</span>
  <span m=''21860''>polygon</span> <span m=''22360''>to</span> <span m=''22470''>itself.</span>
  </p><p><span m=''29030''>And</span> <span m=''29530''>we</span> <span m=''29640''>were</span>
  <span m=''29720''>representing</span> <span m=''30310''>that</span> <span m=''31330''>with</span>
  <span m=''32090''>gluing</span> <span m=''32570''>trees</span> <span m=''33080''>last</span>
  <span m=''33420''>time.</span> <span m=''35640''>So</span> <span m=''35870''>I</span>
  <span m=''35900''>want</span> <span m=''36110''>to</span> <span m=''36170''>do</span>
  <span m=''36280''>an</span> <span m=''36370''>actual</span> <span m=''36670''>example</span>
  <span m=''37970''>of</span> <span m=''38080''>a</span> <span m=''38130''>gluing</span>
  <span m=''38460''>tree.</span> <span m=''39320''>So</span> <span m=''39350''>this</span>
  <span m=''39550''>is</span> <span m=''39660''>how</span> <span m=''39780''>you</span>
  <span m=''39930''>make</span> <span m=''40140''>a</span> <span m=''40190''>cube</span>
  <span m=''40540''>out</span> <span m=''40630''>of</span> <span m=''40730''>a cross,</span>
  <span m=''42190''>my</span> <span m=''42340''>favorite</span> <span m=''42690''>example.</span>
  </p><p><span m=''45910''>And</span> <span m=''47000''>a</span> <span m=''47190''>valid</span>
  <span m=''47710''>gluing,</span> <span m=''48440''>it''s</span> <span m=''48630''>an</span>
  <span m=''48710''>Alexandroff</span> <span m=''49400''>gluing</span> <span m=''49780''>because</span>
  <span m=''50130''>it</span> <span m=''50190''>has</span> <span m=''50380''>no</span>
  <span m=''50510''>crossing,</span> <span m=''51150''>so</span> <span m=''51340''>its</span>
  <span m=''51460''>topologically</span> <span m=''51660''>a</span> <span m=''52050''>sphere.</span>
  <span m=''52380''>Everything</span> <span m=''52740''>is</span> <span m=''52870''>glued
  to</span> <span m=''53060''>everything.</span> <span m=''54410''>And</span> <span
  m=''55160''>it</span> <span m=''55490''>never</span> <span m=''55780''>glues</span>
  <span m=''56060''>more</span> <span m=''56370''>than</span> <span m=''56790''>360</span>
  <span m=''57400''>degrees</span> <span m=''57700''>of material</span> <span m=''58200''>to
  any</span> <span m=''58450''>point.</span> <span m=''58910''>In</span> <span m=''59000''>fact,</span>
  <span m=''59270''>it''s</span> <span m=''59390''>going</span> <span m=''59490''>to</span>
  <span m=''59550''>be</span> <span m=''59700''>270</span> <span m=''60210''>at</span>
  <span m=''60270''>every</span> <span m=''60520''>point,</span> <span m=''62180''>because</span>
  <span m=''62390''>that''s</span> <span m=''62890''>the</span> <span m=''62990''>curvature</span>
  <span m=''63430''>of every</span> <span m=''63600''>vertex</span> <span m=''64030''>of</span>
  <span m=''64099''>a</span> <span m=''64160''>cube.</span> </p><p><span m=''66210''>And</span>
  <span m=''67530''>the</span> <span m=''67650''>gluing</span> <span m=''68070''>tree</span>
  <span m=''68290''>was,</span> <span m=''68480''>if</span> <span m=''68660''>we</span>
  <span m=''68860''>sort</span> <span m=''69100''>of</span> <span m=''69200''>turned</span>
  <span m=''69490''>this</span> <span m=''69660''>inside</span> <span m=''70100''>out</span>
  <span m=''72050''>and</span> <span m=''72210''>think</span> <span m=''72420''>of</span>
  <span m=''72590''>the</span> <span m=''72730''>polygon</span> <span m=''73170''>as</span>
  <span m=''73270''>being</span> <span m=''73450''>on</span> <span m=''73530''>the</span>
  <span m=''73650''>outside</span> <span m=''74160''>instead</span> <span m=''74260''>of</span>
  <span m=''74390''>the</span> <span m=''74550''>inside,</span> <span m=''75220''>it''s</span>
  <span m=''75380''>really</span> <span m=''75570''>hard</span> <span m=''75790''>to</span>
  <span m=''75860''>see</span> <span m=''76180''>here</span> <span m=''77030''>how</span>
  <span m=''77220''>to</span> <span m=''77370''>convert</span> <span m=''77650''>that</span>
  <span m=''77790''>into</span> <span m=''77980''>a gluing</span> <span m=''78260''>tree,</span>
  <span m=''78930''>though</span> <span m=''79080''>you</span> <span m=''79170''>can</span>
  <span m=''79310''>do</span> <span m=''79510''>it.</span> <span m=''80340''>It''s</span>
  <span m=''80840''>the</span> <span m=''81010''>way</span> <span m=''81170''>that</span>
  <span m=''81330''>these</span> <span m=''81710''>arrows</span> <span m=''82100''>nest.</span>
  <span m=''83130''>But</span> <span m=''83350''>it''s</span> <span m=''83500''>a</span>
  <span m=''83540''>little</span> <span m=''83710''>easier</span> <span m=''83980''>to</span>
  <span m=''84030''>think</span> <span m=''84260''>of</span> <span m=''84370''>on</span>
  <span m=''84580''>the</span> <span m=''84670''>sphere</span> <span m=''85140''>or
  on</span> <span m=''85300''>the</span> <span m=''85400''>polyhedron,</span> <span
  m=''86010''>because</span> <span m=''86310''>then</span> <span m=''86450''>turning</span>
  <span m=''86710''>inside</span> <span m=''87000''>out</span> <span m=''87170''>is</span>
  <span m=''87280''>just</span> <span m=''88070''>upside</span> <span m=''88360''>down.</span>
  <span m=''88670''>It''s</span> <span m=''88930''>not</span> <span m=''89060''>a</span>
  <span m=''89100''>big</span> <span m=''89260''>deal.</span> </p><p><span m=''89980''>So</span>
  <span m=''90040''>if</span> <span m=''90100''>we</span> <span m=''90180''>look</span>
  <span m=''90370''>at</span> <span m=''90430''>where</span> <span m=''90550''>the</span>
  <span m=''90720''>cut</span> <span m=''91110''>are</span> <span m=''92400''>on</span>
  <span m=''93170''>the</span> <span m=''95430''>cube,</span> <span m=''98042''>it</span>
  <span m=''98540''>looks</span> <span m=''98730''>something</span> <span m=''99040''>like</span>
  <span m=''99250''>this.</span> <span m=''100280''>That</span> <span m=''100870''>should</span>
  <span m=''101080''>be</span> <span m=''101240''>a cross.</span> <span m=''101910''>This</span>
  <span m=''102080''>is</span> <span m=''102170''>the</span> <span m=''102290''>top</span>
  <span m=''102590''>of</span> <span m=''102650''>the</span> <span m=''102740''>cross,</span>
  <span m=''103120''>this</span> <span m=''103290''>is</span> <span m=''103350''>the</span>
  <span m=''103440''>bottom</span> <span m=''103705''>of the</span> <span m=''103970''>cross.</span>
  <span m=''104730''>It</span> <span m=''104990''>goes</span> <span m=''105130''>around</span>
  <span m=''105380''>the</span> <span m=''105440''>back side.</span> </p><p><span
  m=''107420''>So</span> <span m=''107510''>then</span> <span m=''108590''>the</span>
  <span m=''108810''>gluing</span> <span m=''109110''>tree is</span> <span m=''109360''>essentially</span>
  <span m=''109740''>this</span> <span m=''110070''>doubled.</span> <span m=''110640''>If</span>
  <span m=''110830''>we</span> <span m=''110920''>walk</span> <span m=''111250''>around</span>
  <span m=''111770''>the</span> <span m=''112000''>outside</span> <span m=''112610''>of</span>
  <span m=''112720''>the</span> <span m=''112810''>cuts,</span> <span m=''113690''>that</span>
  <span m=''113900''>is</span> <span m=''114050''>the</span> <span m=''114140''>gluing</span>
  <span m=''114450''>tree.</span> <span m=''115310''>So</span> <span m=''115460''>I</span>
  <span m=''115550''>can</span> <span m=''115720''>see,</span> <span m=''116710''>there''s</span>
  <span m=''117420''>this</span> <span m=''117660''>segment,</span> <span m=''118560''>then</span>
  <span m=''118850''>this</span> <span m=''119060''>segment,</span> <span m=''119680''>then</span>
  <span m=''119910''>that</span> <span m=''120170''>segment.</span> <span m=''122460''>Then</span>
  <span m=''122660''>we''re</span> <span m=''122780''>back</span> <span m=''123090''>here,</span>
  <span m=''124360''>then</span> <span m=''124740''>we</span> <span m=''125060''>go</span>
  <span m=''125510''>up</span> <span m=''126800''>one,</span> <span m=''128400''>two,</span>
  <span m=''129789''>and</span> <span m=''130020''>then</span> <span m=''130160''>we</span>
  <span m=''130270''>turn</span> <span m=''130460''>around.</span> </p><p><span m=''130810''>That''s</span>
  <span m=''131030''>a</span> <span m=''131080''>leaf,</span> <span m=''132180''>and</span>
  <span m=''132450''>so</span> <span m=''132550''>it''s</span> <span m=''132680''>going</span>
  <span m=''132780''>to</span> <span m=''132840''>look</span> <span m=''133020''>like</span>
  <span m=''133210''>this</span> <span m=''133800''>weird</span> <span m=''134190''>h</span>
  <span m=''135000''>shape.</span> <span m=''136530''>And</span> <span m=''136980''>these</span>
  <span m=''137220''>are</span> <span m=''139520''>vertices.</span> <span m=''146290''>That''s</span>
  <span m=''146580''>right,</span> <span m=''146830''>all</span> <span m=''147060''>of
  these</span> <span m=''147160''>should</span> <span m=''147370''>be</span> <span
  m=''147520''>vertices.</span> </p><p><span m=''149760''>And</span> <span m=''149940''>locally</span>
  <span m=''150270''>you</span> <span m=''150800''>can</span> <span m=''150910''>see,</span>
  <span m=''151260''>ah,</span> <span m=''151610''>this is</span> <span m=''151730''>a</span>
  <span m=''151780''>90</span> <span m=''152010''>degree</span> <span m=''152310''>angle.</span>
  <span m=''152820''>This</span> <span m=''152910''>is</span> <span m=''153040''>actually</span>
  <span m=''153320''>the</span> <span m=''153440''>top</span> <span m=''153760''>of</span>
  <span m=''153850''>the</span> <span m=''153960''>cross,</span> <span m=''154530''>remember</span>
  <span m=''154770''>the</span> <span m=''154870''>polygon</span> <span m=''155340''>is</span>
  <span m=''155440''>now</span> <span m=''155620''>out</span> <span m=''155810''>here.</span>
  <span m=''156980''>That''s</span> <span m=''157230''>going</span> <span m=''157330''>to</span>
  <span m=''157380''>be</span> <span m=''157470''>the</span> <span m=''157590''>top</span>
  <span m=''157850''>across.</span> <span m=''158340''>This</span> <span m=''158500''>is</span>
  <span m=''158590''>where</span> <span m=''158750''>it</span> <span m=''158840''>turns,</span>
  <span m=''159220''>it</span> <span m=''159280''>gets</span> <span m=''159460''>a</span>
  <span m=''159500''>little</span> <span m=''159660''>confusing</span> <span m=''160120''>because</span>
  <span m=''160340''>of</span> <span m=''160540''>the</span> <span m=''160620''>way</span>
  <span m=''160750''>I''ve</span> <span m=''160830''>drawn</span> <span m=''161070''>it.</span>
  </p><p><span m=''161500''>Here''s</span> <span m=''161760''>the</span> <span m=''161850''>bottom</span>
  <span m=''162140''>of</span> <span m=''162180''>the</span> <span m=''162270''>cross.</span>
  <span m=''162640''>Those</span> <span m=''162860''>parts</span> <span m=''163060''>are</span>
  <span m=''163120''>easy</span> <span m=''163390''>to</span> <span m=''163470''>see.</span>
  <span m=''163730''>The</span> <span m=''163830''>rest</span> <span m=''164120''>is</span>
  <span m=''164240''>little</span> <span m=''164900''>awkward.</span> </p><p><span
  m=''166050''>But</span> <span m=''166420''>for</span> <span m=''166580''>algorithms,</span>
  <span m=''167080''>this</span> <span m=''167210''>is</span> <span m=''167320''>a</span>
  <span m=''167410''>great</span> <span m=''167670''>way</span> <span m=''167790''>to</span>
  <span m=''167880''>think</span> <span m=''168060''>about</span> <span m=''168330''>things.</span>
  <span m=''168860''>And</span> <span m=''169020''>also</span> <span m=''169360''>for</span>
  <span m=''169670''>proving</span> <span m=''170080''>bounds</span> <span m=''170430''>and</span>
  <span m=''170510''>how</span> <span m=''170730''>many</span> <span m=''170930''>different</span>
  <span m=''171190''>ways</span> <span m=''171380''>to</span> <span m=''171460''>fold,</span>
  <span m=''172220''>it''s</span> <span m=''172320''>really</span> <span m=''172550''>useful</span>
  <span m=''172840''>to</span> <span m=''172910''>think</span> <span m=''173130''>about</span>
  <span m=''173680''>gluing</span> <span m=''173850''>trees.</span> <span m=''174300''>Of
  course,</span> <span m=''174520''>all</span> <span m=''174750''>of these</span>
  <span m=''174910''>views are</span> <span m=''175190''>equivalent,</span> <span
  m=''176330''>but</span> <span m=''177020''>a</span> <span m=''177090''>lot</span>
  <span m=''177250''>of</span> <span m=''177330''>things</span> <span m=''177530''>will</span>
  <span m=''177590''>be</span> <span m=''177700''>easier</span> <span m=''177960''>to</span>
  <span m=''178020''>analyze</span> <span m=''178450''>here.</span> <span m=''179840''>So,</span>
  <span m=''180070''>clear?</span> </p><p><span m=''182300''>Let</span> <span m=''183650''>me</span>
  <span m=''183780''>first</span> <span m=''183990''>tell</span> <span m=''184110''>you</span>
  <span m=''184280''>what</span> <span m=''184560''>we''re</span> <span m=''184700''>going</span>
  <span m=''184810''>to</span> <span m=''184880''>prove</span> <span m=''185130''>today.</span>
  <span m=''187860''>We''re</span> <span m=''187960''>going</span> <span m=''188090''>to</span>
  <span m=''188190''>do</span> <span m=''188570''>combinatorial</span> <span m=''189120''>bounds</span>
  <span m=''190680''>and</span> <span m=''192440''>algorithms</span> <span m=''195760''>for</span>
  <span m=''196390''>all</span> <span m=''196590''>of</span> <span m=''196690''>this.</span>
  <span m=''200460''>And</span> <span m=''201150''>let''s</span> <span m=''201340''>see.</span>
  <span m=''201790''>So</span> <span m=''202070''>I</span> <span m=''202190''>want</span>
  <span m=''203090''>general</span> <span m=''204000''>gluings,</span> <span m=''206490''>general</span>
  <span m=''206800''>situation,</span> <span m=''208370''>edge-to-edge</span> <span
  m=''209000''>gluings,</span> <span m=''213060''>and</span> <span m=''213380''>a</span>
  <span m=''213990''>particular</span> <span m=''214600''>kind</span> <span m=''214800''>of</span>
  <span m=''214880''>polygon</span> <span m=''215390''>called</span> <span m=''215650''>bounded</span>
  <span m=''216100''>sharpness.</span> <span m=''224120''>And</span> <span m=''224350''>then</span>
  <span m=''224550''>I</span> <span m=''224650''>want</span> <span m=''225120''>two</span>
  <span m=''225680''>columns.</span> </p><p><span m=''229610''>The</span> <span m=''229710''>first</span>
  <span m=''229920''>question</span> <span m=''230160''>is,</span> <span m=''230230''>how</span>
  <span m=''230400''>many</span> <span m=''230580''>gluings</span> <span m=''230960''>are</span>
  <span m=''231160''>there?</span> <span m=''232510''>And</span> <span m=''232640''>whenever</span>
  <span m=''232910''>we</span> <span m=''233020''>get</span> <span m=''233140''>a</span>
  <span m=''233190''>bound</span> <span m=''233510''>on</span> <span m=''233600''>the</span>
  <span m=''233660''>number</span> <span m=''233890''>of</span> <span m=''233960''>gluings,</span>
  <span m=''234320''>we''re</span> <span m=''234450''>also</span> <span m=''234740''>going</span>
  <span m=''234870''>to</span> <span m=''234940''>get</span> <span m=''235640''>an</span>
  <span m=''235760''>enumeration</span> <span m=''236380''>algorithm.</span> <span
  m=''239430''>Remember,</span> <span m=''239660''>there</span> <span m=''239840''>are</span>
  <span m=''239880''>three</span> <span m=''240140''>goals.</span> </p><p><span m=''240620''>The</span>
  <span m=''240720''>first</span> <span m=''240910''>goal was</span> <span m=''241270''>decision.</span>
  <span m=''241780''>Is</span> <span m=''241980''>there</span> <span m=''242170''>any</span>
  <span m=''242450''>folding?</span> <span m=''243280''>Second</span> <span m=''243640''>goal</span>
  <span m=''243880''>was</span> <span m=''244390''>enumeration,</span> <span m=''245830''>give</span>
  <span m=''246000''>me</span> <span m=''246150''>all</span> <span m=''246340''>the</span>
  <span m=''246420''>foldings.</span> <span m=''247070''>And</span> <span m=''247270''>third</span>
  <span m=''247440''>goal</span> <span m=''247640''>was</span> <span m=''248180''>counting,</span>
  <span m=''248660''>I</span> <span m=''248720''>think.</span> <span m=''249210''>How</span>
  <span m=''249450''>many</span> <span m=''249700''>different</span> <span m=''249980''>solutions</span>
  <span m=''250340''>are</span> <span m=''250490''>there?</span> <span m=''252985''>For</span>
  <span m=''253430''>[INAUDIBLE],</span> <span m=''253800''>this</span> <span m=''253960''>is</span>
  <span m=''254090''>mainly</span> <span m=''254620''>about</span> <span m=''255020''>decision</span>
  <span m=''256820''>and</span> <span m=''257620''>enumeration.</span> <span m=''259290''>And</span>
  <span m=''259959''>this</span> <span m=''260170''>number</span> <span m=''260470''>of
  gluings,</span> <span m=''260760''>that''s</span> <span m=''261040''>the</span>
  <span m=''261320''>combinatorial</span> <span m=''262490''>problem.</span> </p><p><span
  m=''263540''>So</span> <span m=''263670''>it</span> <span m=''263750''>turns</span>
  <span m=''264020''>out,</span> <span m=''264310''>for</span> <span m=''264410''>everything</span>
  <span m=''264800''>the</span> <span m=''264910''>we''ll</span> <span m=''265040''>do,</span>
  <span m=''265490''>these</span> <span m=''265770''>two</span> <span m=''266040''>have</span>
  <span m=''266230''>the</span> <span m=''266310''>same</span> <span m=''266560''>answer.</span>
  <span m=''267180''>So</span> <span m=''267340''>I''m</span> <span m=''267450''>going</span>
  <span m=''267540''>to</span> <span m=''267610''>put</span> <span m=''267740''>it
  in</span> <span m=''267830''>one</span> <span m=''268010''>column.</span> <span
  m=''269050''>But</span> <span m=''269240''>sometimes</span> <span m=''269660''>for
  a</span> <span m=''269820''>decision,</span> <span m=''270310''>you</span> <span
  m=''270430''>can</span> <span m=''270560''>do</span> <span m=''270660''>it a</span>
  <span m=''270740''>little</span> <span m=''270940''>faster</span> <span m=''271410''>than</span>
  <span m=''271570''>enumerating</span> <span m=''271620''>them.</span> <span m=''273740''>In</span>
  <span m=''273880''>particular,</span> <span m=''274450''>because</span> <span m=''275890''>the</span>
  <span m=''276000''>number</span> <span m=''276370''>of</span> <span m=''276420''>gluings</span>
  <span m=''277920''>can</span> <span m=''278080''>be</span> <span m=''278210''>exponential.</span>
  </p><p><span m=''280420''>We</span> <span m=''280520''>saw</span> <span m=''280670''>last</span>
  <span m=''280920''>time</span> <span m=''281050''>that it</span> <span m=''281210''>could</span>
  <span m=''281350''>actually</span> <span m=''281550''>be</span> <span m=''281680''>infinite.</span>
  <span m=''282560''>I''m</span> <span m=''282700''>going</span> <span m=''282800''>to</span>
  <span m=''282870''>fix</span> <span m=''283250''>that,</span> <span m=''283650''>don''t</span>
  <span m=''283890''>worry.</span> <span m=''284320''>We''ll</span> <span m=''284630''>make</span>
  <span m=''284840''>it</span> <span m=''284950''>finite.</span> <span m=''285700''>And</span>
  <span m=''285950''>then</span> <span m=''286700''>the</span> <span m=''286930''>right</span>
  <span m=''287140''>bound</span> <span m=''287340''>is</span> <span m=''287440''>exponential.</span>
  <span m=''287940''>There''s</span> <span m=''288140''>upper</span> <span m=''288480''>and</span>
  <span m=''288650''>lower</span> <span m=''288880''>bounds</span> <span m=''289190''>of</span>
  <span m=''289290''>two</span> <span m=''289500''>to the</span> <span m=''289780''>theta</span>
  <span m=''290440''>n.</span> </p><p><span m=''294833''>And</span> <span m=''295560''>also</span>
  <span m=''295890''>here,</span> <span m=''298810''>bounded</span> <span m=''299230''>sharpness</span>
  <span m=''299690''>is</span> <span m=''299810''>interesting</span> <span m=''300300''>because</span>
  <span m=''300620''>it''s</span> <span m=''300780''>polynomial.</span> <span m=''304490''>And</span>
  <span m=''304680''>so</span> <span m=''304840''>this</span> <span m=''305080''>is</span>
  <span m=''305210''>also</span> <span m=''305490''>polynomial.</span> <span m=''318600''>The</span>
  <span m=''318750''>one</span> <span m=''319180''>result</span> <span m=''319570''>here</span>
  <span m=''319700''>that is</span> <span m=''319940''>not</span> <span m=''320280''>tight</span>
  <span m=''320970''>is</span> <span m=''321210''>this</span> <span m=''321390''>one.</span>
  <span m=''322900''>It''s</span> <span m=''323030''>an</span> <span m=''323140''>open</span>
  <span m=''323410''>question</span> <span m=''323830''>whether</span> <span m=''324080''>for</span>
  <span m=''324770''>the</span> <span m=''324920''>general</span> <span m=''325310''>setup,</span>
  <span m=''325780''>the</span> <span m=''325880''>most</span> <span m=''326190''>interesting</span>
  <span m=''326630''>scenario,</span> <span m=''327070''>just</span> <span m=''327250''>give</span>
  <span m=''327410''>you</span> <span m=''327480''>a</span> <span m=''327520''>polygon,</span>
  <span m=''328005''>is</span> <span m=''328490''>there</span> <span m=''328650''>any</span>
  <span m=''328900''>gluing?</span> </p><p><span m=''329910''>The</span> <span m=''329990''>best</span>
  <span m=''330260''>algorithm</span> <span m=''330670''>we</span> <span m=''330770''>know
  is</span> <span m=''330930''>exponential,</span> <span m=''332860''>even</span>
  <span m=''333150''>to</span> <span m=''333270''>decide</span> <span m=''333730''>whether</span>
  <span m=''333940''>there''s</span> <span m=''334160''>a</span> <span m=''334220''>gluing.</span>
  <span m=''335250''>So</span> <span m=''335280''>I</span> <span m=''335360''>put</span>
  <span m=''335510''>a</span> <span m=''335560''>star</span> <span m=''335850''>there</span>
  <span m=''336020''>to</span> <span m=''336090''>say</span> <span m=''336270''>that.</span>
  <span m=''337270''>It is</span> <span m=''337380''>not</span> <span m=''337620''>tight.</span>
  <span m=''338610''>The open</span> <span m=''338850''>problem is,</span> <span m=''339240''>can
  you</span> <span m=''339440''>do</span> <span m=''339560''>it in</span> <span m=''339680''>polynomial?</span>
  <span m=''340220''>I</span> <span m=''340300''>suspect</span> <span m=''341190''>yes,</span>
  <span m=''341670''>but</span> <span m=''342510''>we</span> <span m=''342620''>worked</span>
  <span m=''342850''>on it</span> <span m=''343270''>a</span> <span m=''343370''>long</span>
  <span m=''343550''>time</span> <span m=''343760''>ago</span> <span m=''344140''>and</span>
  <span m=''344280''>failed.</span> </p><p><span m=''346090''>For</span> <span m=''346300''>the</span>
  <span m=''346370''>special</span> <span m=''346710''>case</span> <span m=''346930''>of</span>
  <span m=''347110''>edge-to-edge</span> <span m=''347750''>gluings,</span> <span
  m=''348830''>which</span> <span m=''349130''>is</span> <span m=''349240''>when</span>
  <span m=''349390''>you</span> <span m=''349530''>only</span> <span m=''349780''>glue</span>
  <span m=''349980''>whole</span> <span m=''350340''>edges</span> <span m=''350700''>of</span>
  <span m=''350820''>the</span> <span m=''350900''>polygons</span> <span m=''351630''>to</span>
  <span m=''351890''>other</span> <span m=''352170''>whole</span> <span m=''352460''>edges,</span>
  <span m=''353510''>there</span> <span m=''353750''>is</span> <span m=''353830''>a</span>
  <span m=''354780''>n</span> <span m=''354970''>to</span> <span m=''355070''>the</span>
  <span m=''355210''>order</span> <span m=''355460''>one</span> <span m=''356800''>algorithm.</span>
  <span m=''359070''>You</span> <span m=''359230''>can</span> <span m=''359380''>think</span>
  <span m=''359570''>of</span> <span m=''359650''>this</span> <span m=''359810''>as</span>
  <span m=''359920''>an</span> <span m=''360000''>edge-to-edge</span> <span m=''360410''>gluing</span>
  <span m=''360640''>if</span> <span m=''360750''>you</span> <span m=''360850''>imagine</span>
  <span m=''361210''>this</span> <span m=''361400''>as</span> <span m=''361490''>being</span>
  <span m=''361700''>two</span> <span m=''361900''>edges.</span> <span m=''362360''>If
  I</span> <span m=''362460''>actually</span> <span m=''363290''>draw a</span> <span
  m=''363550''>vertex</span> <span m=''364020''>there,</span> <span m=''364450''>then</span>
  <span m=''364570''>this</span> <span m=''364720''>is</span> <span m=''364840''>an</span>
  <span m=''364940''>edge-to-edge</span> <span m=''365400''>gluing.</span> <span m=''366380''>And</span>
  <span m=''366580''>then</span> <span m=''366730''>there''s</span> <span m=''366890''>a</span>
  <span m=''366950''>polynomial</span> <span m=''367460''>algorithm</span> <span m=''367830''>to</span>
  <span m=''367960''>tell</span> <span m=''368200''>you,</span> <span m=''368450''>is</span>
  <span m=''368710''>there</span> <span m=''368900''>any</span> <span m=''369080''>folding?</span>
  </p><p><span m=''372310''>If</span> <span m=''372460''>you</span> <span m=''372580''>want</span>
  <span m=''372710''>to</span> <span m=''372800''>list</span> <span m=''373010''>all</span>
  <span m=''373920''>of</span> <span m=''374020''>the</span> <span m=''374090''>gluings</span>
  <span m=''374500''>though,</span> <span m=''374890''>you</span> <span m=''375130''>need</span>
  <span m=''375300''>exponential</span> <span m=''375760''>time</span> <span m=''375960''>because</span>
  <span m=''376220''>there</span> <span m=''376330''>can</span> <span m=''376450''>be</span>
  <span m=''376560''>exponentially</span> <span m=''377110''>many.</span> <span m=''378870''>But</span>
  <span m=''379570''>everything</span> <span m=''380150''>except</span> <span m=''380530''>this</span>
  <span m=''380680''>one</span> <span m=''380860''>result</span> <span m=''381250''>is</span>
  <span m=''381430''>the</span> <span m=''381520''>best</span> <span m=''381770''>you</span>
  <span m=''381840''>could</span> <span m=''381970''>hope</span> <span m=''382453''>for.</span>
  <span m=''382936''>Bounded</span> <span m=''383420''>sharpness</span> <span m=''384200''>is</span>
  <span m=''385060''>a</span> <span m=''385170''>natural</span> <span m=''385540''>sense</span>
  <span m=''385800''>in</span> <span m=''385900''>which</span> <span m=''386730''>this</span>
  <span m=''386960''>exponential</span> <span m=''387480''>is</span> <span m=''388050''>kind</span>
  <span m=''388230''>of</span> <span m=''388320''>cheating.</span> <span m=''389310''>Let''s</span>
  <span m=''389490''>see,</span> <span m=''389750''>let</span> <span m=''389850''>me</span>
  <span m=''389980''>tell</span> <span m=''390210''>you</span> <span m=''390855''>about</span>
  <span m=''391430''>bounded</span> <span m=''391790''>sharpness.</span> </p><p><span
  m=''402420''>I</span> <span m=''402500''>want</span> <span m=''402700''>to</span>
  <span m=''402760''>bound</span> <span m=''403140''>how</span> <span m=''403510''>sharp</span>
  <span m=''404930''>an</span> <span m=''405100''>angle</span> <span m=''405400''>can</span>
  <span m=''405540''>be</span> <span m=''405680''>in</span> <span m=''405780''>a</span>
  <span m=''405840''>polygon.</span> <span m=''407610''>This</span> <span m=''407820''>is</span>
  <span m=''407940''>a</span> <span m=''408020''>really</span> <span m=''409050''>sharp</span>
  <span m=''409370''>angle.</span> <span m=''410530''>If</span> <span m=''413510''>every</span>
  <span m=''413900''>angle--</span> <span m=''417930''>is that</span> <span m=''418080''>actually</span>
  <span m=''418430''>the</span> <span m=''418530''>sharpness</span> <span m=''418960''>I</span>
  <span m=''419030''>want?</span> <span m=''420120''>Actually,</span> <span m=''420380''>no.</span>
  <span m=''421700''>Sorry,</span> <span m=''422580''>I''m</span> <span m=''423020''>getting</span>
  <span m=''423900''>inside</span> <span m=''424290''>out</span> <span m=''424440''>already.</span>
  </p><p><span m=''426470''>Actually,</span> <span m=''426790''>what</span> <span
  m=''427000''>I</span> <span m=''427420''>care</span> <span m=''427680''>about</span>
  <span m=''428040''>are</span> <span m=''428910''>reflex</span> <span m=''429320''>vertices.</span>
  <span m=''432990''>I</span> <span m=''433070''>don''t</span> <span m=''433170''>want</span>
  <span m=''433290''>to</span> <span m=''433330''>have</span> <span m=''433500''>a</span>
  <span m=''433610''>super</span> <span m=''433930''>big</span> <span m=''434140''>angles</span>
  <span m=''434520''>here.</span> <span m=''436010''>So if</span> <span m=''436230''>every</span>
  <span m=''436530''>angle</span> <span m=''437370''>is</span> <span m=''437570''>at</span>
  <span m=''437660''>least</span> <span m=''438700''>360</span> <span m=''440410''>minus</span>
  <span m=''440870''>some</span> <span m=''441070''>epsilon--</span> <span m=''443120''>for</span>
  <span m=''443415''>a</span> <span m=''443710''>constant</span> <span m=''445120''>epsilon--</span>
  <span m=''449910''>then</span> <span m=''450450''>I</span> <span m=''450580''>call</span>
  <span m=''450760''>my</span> <span m=''450910''>polygon</span> <span m=''451320''>bounded</span>
  <span m=''451770''>sharpness.</span> <span m=''454640''>If your</span> <span m=''454740''>polygon</span>
  <span m=''455240''>has</span> <span m=''455430''>bounded</span> <span m=''455730''>sharpness,</span>
  <span m=''457160''>we</span> <span m=''457370''>get</span> <span m=''457680''>a</span>
  <span m=''457910''>polynomial</span> <span m=''458880''>bound</span> <span m=''459360''>on</span>
  <span m=''459580''>the</span> <span m=''459660''>number</span> <span m=''459890''>of</span>
  <span m=''459950''>gluings</span> <span m=''460320''>and a</span> <span m=''460460''>polynomial</span>
  <span m=''460790''>algorithm</span> <span m=''461370''>to</span> <span m=''461480''>list</span>
  <span m=''461710''>all</span> <span m=''461870''>the</span> <span m=''461950''>gluings.</span>
  </p><p><span m=''462940''>This</span> <span m=''463150''>is</span> <span m=''463230''>really</span>
  <span m=''463430''>the</span> <span m=''463530''>sense</span> <span m=''463820''>in</span>
  <span m=''463900''>which</span> <span m=''464130''>this</span> <span m=''464310''>is</span>
  <span m=''464410''>all</span> <span m=''464570''>practical.</span> <span m=''466350''>Give</span>
  <span m=''466490''>me</span> <span m=''466620''>a</span> <span m=''466670''>polygon</span>
  <span m=''467260''>that''s</span> <span m=''467450''>going</span> <span m=''467550''>to</span>
  <span m=''467590''>have</span> <span m=''467760''>some</span> <span m=''468730''>sharpest</span>
  <span m=''469180''>angle,</span> <span m=''469930''>call</span> <span m=''470140''>that</span>
  <span m=''470380''>the</span> <span m=''470460''>bound.</span> <span m=''473160''>If</span>
  <span m=''473470''>epsilon</span> <span m=''473810''>gets</span> <span m=''473950''>really</span>
  <span m=''474160''>tiny,</span> <span m=''474480''>if</span> <span m=''474590''>your</span>
  <span m=''474850''>reflex</span> <span m=''475200''>angles</span> <span m=''475440''>get</span>
  <span m=''475610''>really</span> <span m=''475790''>close to</span> <span m=''476080''>360,</span>
  <span m=''477200''>then</span> <span m=''477800''>this</span> <span m=''477950''>bound
  will</span> <span m=''478270''>go</span> <span m=''478420''>up.</span> </p><p><span
  m=''478850''>But</span> <span m=''479536''>as</span> <span m=''479942''>long</span>
  <span m=''480350''>as</span> <span m=''480490''>you''re</span> <span m=''480590''>not</span>
  <span m=''481180''>too</span> <span m=''481360''>extreme,</span> <span m=''483170''>you''re</span>
  <span m=''483930''>all</span> <span m=''484100''>set.</span> <span m=''488370''>I</span>
  <span m=''488530''>mean</span> <span m=''488760''>less</span> <span m=''488990''>than</span>
  <span m=''489100''>or</span> <span m=''489170''>equal</span> <span m=''489370''>to,</span>
  <span m=''490213''>yes,</span> <span m=''491160''>thank</span> <span m=''491560''>you.</span>
  <span m=''495200''>Yeah,</span> <span m=''495510''>that would be a</span> <span
  m=''495890''>weird</span> <span m=''496220''>polygon</span> <span m=''497015''>if
  all the</span> <span m=''497320''>angles</span> <span m=''497690''>were</span> <span
  m=''497780''>so</span> <span m=''497960''>big.</span> <span m=''499150''>I</span>
  <span m=''499270''>think</span> <span m=''499520''>that</span> <span m=''499710''>doesn''t</span>
  <span m=''500120''>exist.</span> </p><p><span m=''501270''>So</span> <span m=''501320''>for</span>
  <span m=''501470''>example,</span> <span m=''501950''>convex</span> <span m=''502450''>polygons</span>
  <span m=''503330''>always</span> <span m=''503560''>have</span> <span m=''503680''>bounded</span>
  <span m=''503940''>sharpness.</span> <span m=''504540''>Epsilon</span> <span m=''505030''>is</span>
  <span m=''505190''>180</span> <span m=''506430''>in</span> <span m=''506500''>that</span>
  <span m=''506680''>situation.</span> <span m=''508250''>So,</span> <span m=''509830''>that''s</span>
  <span m=''510110''>good.</span> <span m=''514120''>I</span> <span m=''514270''>told</span>
  <span m=''514510''>you</span> <span m=''514580''>about</span> <span m=''514770''>edge-to-edge</span>
  <span m=''515299''>gluings.</span> <span m=''515870''>Just</span> <span m=''516059''>glue</span>
  <span m=''516450''>whole</span> <span m=''516730''>edges to whole</span> <span m=''516929''>edges.</span>
  </p><p><span m=''517950''>What</span> <span m=''518090''>I</span> <span m=''518120''>haven''t</span>
  <span m=''518409''>really</span> <span m=''518640''>told</span> <span m=''518900''>you</span>
  <span m=''519039''>is</span> <span m=''519700''>how</span> <span m=''520010''>we</span>
  <span m=''520150''>made</span> <span m=''520350''>this</span> <span m=''520549''>finite,</span>
  <span m=''521049''>so</span> <span m=''521179''>let</span> <span m=''521320''>me</span>
  <span m=''521450''>go</span> <span m=''521710''>to</span> <span m=''521890''>that.</span>
  <span m=''522630''>And</span> <span m=''523340''>when</span> <span m=''523500''>I</span>
  <span m=''523600''>say</span> <span m=''523840''>gluings</span> <span m=''524520''>here,</span>
  <span m=''524860''>I</span> <span m=''524920''>really</span> <span m=''525290''>mean</span>
  <span m=''526920''>a</span> <span m=''527180''>combinatorial</span> <span m=''527690''>type</span>
  <span m=''527970''>of</span> <span m=''528070''>gluing,</span> <span m=''532580''>because</span>
  <span m=''532780''>we</span> <span m=''532960''>had</span> <span m=''533320''>rolling</span>
  <span m=''533670''>belts.</span> <span m=''534750''>So</span> <span m=''535050''>there</span>
  <span m=''535240''>were</span> <span m=''537350''>infinitely</span> <span m=''537840''>many</span>
  <span m=''538130''>actual</span> <span m=''538680''>gluings,</span> <span m=''539870''>but</span>
  <span m=''540010''>I''m</span> <span m=''540090''>going</span> <span m=''540200''>to</span>
  <span m=''540470''>think</span> <span m=''540770''>of</span> <span m=''540850''>most</span>
  <span m=''541150''>of</span> <span m=''541220''>those</span> <span m=''541420''>as</span>
  <span m=''541520''>being</span> <span m=''541740''>the</span> <span m=''541820''>same</span>
  <span m=''542160''>thing</span> <span m=''542940''>and</span> <span m=''543140''>just</span>
  <span m=''543390''>distinguish</span> <span m=''543920''>essentially</span> <span
  m=''544350''>what</span> <span m=''544710''>the</span> <span m=''544810''>gluing</span>
  <span m=''545200''>tree</span> <span m=''545480''>looks</span> <span m=''545780''>like</span>
  <span m=''546020''>combinatorially.</span> <span m=''547490''>So</span> <span m=''547640''>let</span>
  <span m=''547790''>me</span> <span m=''547940''>define</span> <span m=''548310''>that.</span>
  </p><p><span m=''549336''>The</span> <span m=''549680''>first</span> <span m=''549990''>part</span>
  <span m=''550780''>is</span> <span m=''551100''>what</span> <span m=''551310''>I</span>
  <span m=''551370''>call</span> <span m=''551750''>the</span> <span m=''551920''>abstract</span>
  <span m=''554660''>gluing</span> <span m=''554900''>tree.</span> <span m=''559310''>So</span>
  <span m=''559460''>this</span> <span m=''559670''>is</span> <span m=''559810''>just</span>
  <span m=''560200''>what</span> <span m=''560660''>the</span> <span m=''560760''>picture</span>
  <span m=''561100''>looks</span> <span m=''561320''>like</span> <span m=''561470''>in</span>
  <span m=''561570''>general.</span> <span m=''562070''>So</span> <span m=''562840''>for</span>
  <span m=''562940''>example,</span> <span m=''563980''>the</span> <span m=''564110''>one</span>
  <span m=''564310''>over</span> <span m=''564490''>there--</span> <span m=''565280''>the</span>
  <span m=''565640''>cube--</span> <span m=''566780''>combinatorially</span> <span
  m=''568450''>the</span> <span m=''568560''>tree</span> <span m=''568800''>looks</span>
  <span m=''569030''>like</span> <span m=''569220''>this.</span> <span m=''571010''>It</span>
  <span m=''571090''>has</span> <span m=''571960''>four</span> <span m=''572240''>leaves</span>
  <span m=''572810''>and</span> <span m=''572990''>a</span> <span m=''573070''>kind</span>
  <span m=''573260''>of</span> <span m=''573330''>wishbone</span> <span m=''574480''>configuration.</span>
  <span m=''575620''>So</span> <span m=''575720''>I''m</span> <span m=''575800''>not</span>
  <span m=''575960''>trying</span> <span m=''576130''>to</span> <span m=''576200''>measure</span>
  <span m=''576440''>the</span> <span m=''576560''>lengths</span> <span m=''576900''>or</span>
  <span m=''576960''>anything,</span> <span m=''577300''>just</span> <span m=''578150''>that''s</span>
  <span m=''578460''>the</span> <span m=''578690''>abstract</span> <span m=''579210''>picture,</span>
  <span m=''581690''>no</span> <span m=''581840''>metric.</span> </p><p><span m=''583580''>And</span>
  <span m=''584060''>then</span> <span m=''584360''>the</span> <span m=''584430''>second</span>
  <span m=''584760''>part</span> <span m=''586030''>is I''m</span> <span m=''586470''>going</span>
  <span m=''586570''>to</span> <span m=''586640''>specify</span> <span m=''593080''>which</span>
  <span m=''594170''>polygon</span> <span m=''594710''>vertices</span> <span m=''595180''>and</span>
  <span m=''595320''>edges</span> <span m=''595710''>are</span> <span m=''595940''>where.</span>
  <span m=''622310''>And</span> <span m=''622560''>I''m</span> <span m=''622640''>going</span>
  <span m=''622780''>to</span> <span m=''622830''>specify</span> <span m=''623230''>that</span>
  <span m=''623470''>at</span> <span m=''623660''>things called</span> <span m=''623940''>junctions.</span>
  <span m=''625310''>So</span> <span m=''626310''>in</span> <span m=''626470''>particular,</span>
  <span m=''627150''>at</span> <span m=''627380''>leaves</span> <span m=''628420''>I</span>
  <span m=''628530''>want</span> <span m=''628680''>to</span> <span m=''628740''>say,</span>
  <span m=''629230''>oh</span> <span m=''629430''>this</span> <span m=''629750''>is
  vertex</span> <span m=''630200''>one.</span> </p><p><span m=''632740''>At</span>
  <span m=''633470''>places</span> <span m=''633950''>like</span> <span m=''634150''>this,</span>
  <span m=''634370''>where</span> <span m=''634490''>three</span> <span m=''635070''>edges</span>
  <span m=''635400''>come</span> <span m=''635580''>together,</span> <span m=''636340''>I</span>
  <span m=''636460''>want</span> <span m=''636600''>to</span> <span m=''636640''>specify</span>
  <span m=''637070''>for</span> <span m=''637270''>each</span> <span m=''637460''>one,</span>
  <span m=''637770''>oh</span> <span m=''638020''>this</span> <span m=''638200''>is</span>
  <span m=''638350''>vertex</span> <span m=''638780''>two,</span> <span m=''639570''>this</span>
  <span m=''639830''>is</span> <span m=''640120''>edge</span> <span m=''640640''>eight,</span>
  <span m=''641640''>this</span> <span m=''641900''>is</span> <span m=''642190''>vertex</span>
  <span m=''643640''>10,</span> <span m=''644350''>whatever.</span> <span m=''644760''>I''m</span>
  <span m=''644850''>making</span> <span m=''645140''>up</span> <span m=''645230''>these</span>
  <span m=''645390''>numbers.</span> <span m=''645760''>They</span> <span m=''645790''>don''t</span>
  <span m=''645950''>necessarily</span> <span m=''646380''>correspond,</span> <span
  m=''647260''>but</span> <span m=''647390''>they</span> <span m=''647460''>should</span>
  <span m=''647660''>appear</span> <span m=''647960''>in</span> <span m=''648050''>order</span>
  <span m=''648810''>because</span> <span m=''649030''>this</span> <span m=''649200''>is</span>
  <span m=''649290''>the</span> <span m=''649380''>polygon</span> <span m=''649880''>after</span>
  <span m=''650150''>all,</span> <span m=''650690''>just</span> <span m=''651130''>warped</span>
  <span m=''651490''>inside</span> <span m=''651840''>out.</span> </p><p><span m=''655670''>Also</span>
  <span m=''656370''>this</span> <span m=''656580''>one.</span> <span m=''657590''>Also,</span>
  <span m=''659750''>I didn''t really</span> <span m=''659830''>draw</span> <span
  m=''659970''>this</span> <span m=''660150''>picture</span> <span m=''660440''>big</span>
  <span m=''660650''>enough,</span> <span m=''661330''>but</span> <span m=''661430''>if</span>
  <span m=''661580''>I</span> <span m=''661670''>have</span> <span m=''662530''>two</span>
  <span m=''662730''>parts</span> <span m=''663020''>of</span> <span m=''663060''>the</span>
  <span m=''663120''>gluing</span> <span m=''663380''>tree</span> <span m=''663950''>where
  a</span> <span m=''664250''>vertex</span> <span m=''665430''>glues</span> <span
  m=''666080''>against</span> <span m=''666320''>something--</span> <span m=''666790''>it
  could</span> <span m=''666960''>be</span> <span m=''667080''>another</span> <span
  m=''667320''>vertex</span> <span m=''667770''>or</span> <span m=''667870''>it</span>
  <span m=''667970''>could</span> <span m=''668040''>be</span> <span m=''668160''>an</span>
  <span m=''668250''>edge--</span> <span m=''669600''>I</span> <span m=''669690''>also</span>
  <span m=''670130''>consider</span> <span m=''670500''>those</span> <span m=''670760''>junctions.</span>
  <span m=''672250''>So</span> <span m=''672400''>junctions</span> <span m=''673080''>are</span>
  <span m=''673180''>going</span> <span m=''673330''>to</span> <span m=''673400''>be</span>
  <span m=''674130''>all</span> <span m=''674510''>the</span> <span m=''674600''>vertices--</span>
  <span m=''675780''>the</span> <span m=''675890''>only</span> <span m=''676080''>exception</span>
  <span m=''676550''>is</span> <span m=''677020''>when</span> <span m=''677140''>there''s</span>
  <span m=''677290''>an</span> <span m=''677390''>edge</span> <span m=''677640''>gluing</span>
  <span m=''677850''>to</span> <span m=''677960''>an</span> <span m=''678030''>edge,</span>
  <span m=''678560''>I</span> <span m=''678660''>don''t</span> <span m=''678740''>consider</span>
  <span m=''679010''>that</span> <span m=''679160''>a</span> <span m=''679230''>junction</span>
  <span m=''680040''>because</span> <span m=''680270''>there''s</span> <span m=''680430''>going</span>
  <span m=''680570''>to</span> <span m=''680630''>be</span> <span m=''680780''>fairly</span>
  <span m=''681060''>many</span> <span m=''681310''>of</span> <span m=''681380''>those.</span>
  <span m=''681710''>I</span> <span m=''681780''>want there</span> <span m=''682100''>to</span>
  <span m=''682150''>be</span> <span m=''682300''>finite.</span> </p><p><span m=''683260''>So</span>
  <span m=''683390''>everything</span> <span m=''684010''>of</span> <span m=''684170''>degree</span>
  <span m=''684460''>one,</span> <span m=''685160''>everything</span> <span m=''685550''>of</span>
  <span m=''685600''>degree</span> <span m=''685860''>three</span> <span m=''686090''>or</span>
  <span m=''686160''>more,</span> <span m=''686920''>for</span> <span m=''687050''>degree</span>
  <span m=''687320''>two</span> <span m=''687950''>there</span> <span m=''688080''>has</span>
  <span m=''688190''>to</span> <span m=''688260''>be</span> <span m=''688340''>at</span>
  <span m=''688400''>least</span> <span m=''688650''>one</span> <span m=''688830''>vertex.</span>
  <span m=''690890''>So</span> <span m=''692110''>degree</span> <span m=''695060''>not</span>
  <span m=''695240''>equal</span> <span m=''695490''>to</span> <span m=''695580''>2,</span>
  <span m=''696440''>or</span> <span m=''698430''>at</span> <span m=''698630''>least</span>
  <span m=''699100''>one</span> <span m=''699470''>vertex.</span> <span m=''700940''>Those</span>
  <span m=''701170''>are junctions.</span> <span m=''702310''>For</span> <span m=''702460''>each</span>
  <span m=''702900''>I''m</span> <span m=''703060''>going</span> <span m=''703170''>to</span>
  <span m=''703220''>mark</span> <span m=''703590''>where</span> <span m=''703760''>they</span>
  <span m=''703950''>are.</span> <span m=''704550''>That''s</span> <span m=''704780''>part</span>
  <span m=''705010''>of</span> <span m=''705110''>my</span> <span m=''705260''>abstract</span>
  <span m=''705660''>gluing</span> <span m=''705920''>tree,</span> <span m=''707350''>specifying</span>
  <span m=''707820''>where</span> <span m=''707940''>the</span> <span m=''708020''>junctures</span>
  <span m=''708430''>are,</span> <span m=''708560''>how</span> <span m=''708700''>they''re</span>
  <span m=''708850''>configured.</span> </p><p><span m=''709680''>And</span> <span
  m=''709880''>then</span> <span m=''710830''>for</span> <span m=''710970''>each</span>
  <span m=''711160''>one,</span> <span m=''712200''>wherever</span> <span m=''712720''>there''s</span>
  <span m=''713050''>part</span> <span m=''713290''>of</span> <span m=''713340''>the</span>
  <span m=''713420''>polygon</span> <span m=''713810''>coming</span> <span m=''714050''>together,</span>
  <span m=''714370''>I</span> <span m=''714420''>specify</span> <span m=''714940''>which</span>
  <span m=''715200''>vertex</span> <span m=''715590''>or</span> <span m=''715810''>edge</span>
  <span m=''716450''>is</span> <span m=''716640''>coming</span> <span m=''716940''>there.</span>
  <span m=''717260''>Now</span> <span m=''717410''>when</span> <span m=''717520''>I</span>
  <span m=''717630''>specify</span> <span m=''717820''>an</span> <span m=''718250''>edge,
  I don''t</span> <span m=''718440''>say</span> <span m=''718600''>what</span> <span
  m=''718900''>point</span> <span m=''719200''>on</span> <span m=''719300''>the</span>
  <span m=''719430''>edge,</span> <span m=''720040''>because</span> <span m=''720220''>that</span>
  <span m=''720390''>could</span> <span m=''720560''>be</span> <span m=''720700''>infinite.</span>
  <span m=''721340''>There</span> <span m=''721450''>could</span> <span m=''721560''>be</span>
  <span m=''721660''>a</span> <span m=''721680''>whole</span> <span m=''721880''>range</span>
  <span m=''722230''>of</span> <span m=''722310''>points,</span> <span m=''722640''>there</span>
  <span m=''722740''>could</span> <span m=''722920''>be.</span> <span m=''723740''>We''ll
  worry</span> <span m=''723950''>about</span> <span m=''724150''>that</span> <span
  m=''724310''>later.</span> <span m=''726990''>I</span> <span m=''727100''>just</span>
  <span m=''727240''>specify</span> <span m=''727740''>that</span> <span m=''728190''>edge</span>
  <span m=''728660''>eight is</span> <span m=''728850''>there.</span> </p><p><span
  m=''730310''>So</span> <span m=''730390''>this</span> <span m=''730560''>is</span>
  <span m=''730600''>what</span> <span m=''730770''>I</span> <span m=''730820''>call</span>
  <span m=''731130''>combinatorial</span> <span m=''731850''>type</span> <span m=''732080''>of</span>
  <span m=''732170''>gluing.</span> <span m=''732840''>And in</span> <span m=''733090''>this</span>
  <span m=''733250''>case,</span> <span m=''733510''>there are</span> <span m=''733670''>only</span>
  <span m=''733860''>finitely</span> <span m=''734330''>many</span> <span m=''734570''>gluings,</span>
  <span m=''735680''>finitely</span> <span m=''735860''>many</span> <span m=''736860''>types,</span>
  <span m=''737410''>but</span> <span m=''738500''>it</span> <span m=''738780''>can</span>
  <span m=''738950''>be</span> <span m=''739070''>exponential.</span> <span m=''740070''>It''s</span>
  <span m=''740750''>still</span> <span m=''740980''>big,</span> <span m=''741580''>just</span>
  <span m=''741790''>not</span> <span m=''741900''>quite</span> <span m=''742120''>as</span>
  <span m=''742230''>big.</span> </p><p><span m=''753620''>So</span> <span m=''753800''>just</span>
  <span m=''754020''>to</span> <span m=''754100''>get</span> <span m=''754270''>warmed</span>
  <span m=''754530''>up</span> <span m=''754670''>a</span> <span m=''754730''>little,</span>
  <span m=''755620''>let''s</span> <span m=''755880''>prove</span> <span m=''756700''>this</span>
  <span m=''757000''>exponential</span> <span m=''757810''>upper</span> <span m=''758080''>bound</span>
  <span m=''758640''>that</span> <span m=''758750''>is</span> <span m=''759040''>only</span>
  <span m=''759520''>2</span> <span m=''759790''>to the</span> <span m=''759930''>order</span>
  <span m=''760190''>n.</span> <span m=''761340''>That</span> <span m=''761550''>will</span>
  <span m=''761710''>in</span> <span m=''761790''>particular</span> <span m=''762260''>convince</span>
  <span m=''762570''>you</span> <span m=''762680''>that</span> <span m=''762890''>there''s</span>
  <span m=''763090''>only</span> <span m=''763310''>finitely</span> <span m=''763750''>many</span>
  <span m=''764040''>of</span> <span m=''764120''>these,</span> <span m=''764995''>although</span>
  <span m=''765370''>I</span> <span m=''765510''>think</span> <span m=''765790''>that''s</span>
  <span m=''766330''>probably</span> <span m=''766730''>obvious</span> <span m=''767030''>that
  it''s</span> <span m=''767260''>finite.</span> <span m=''768360''>It''s</span> <span
  m=''768540''>conceivable</span> <span m=''769040''>it could</span> <span m=''769180''>be</span>
  <span m=''769380''>more</span> <span m=''769580''>than</span> <span m=''769720''>exponential.</span>
  </p><p><span m=''775220''>This</span> <span m=''775420''>is</span> <span m=''775570''>not</span>
  <span m=''775810''>a</span> <span m=''775890''>particularly</span> <span m=''776390''>exciting</span>
  <span m=''777710''>bound,</span> <span m=''777990''>but</span> <span m=''778100''>we''re</span>
  <span m=''778230''>going</span> <span m=''778330''>to</span> <span m=''778370''>use</span>
  <span m=''778530''>a</span> <span m=''778590''>lot</span> <span m=''778770''>of</span>
  <span m=''778850''>the</span> <span m=''778930''>same</span> <span m=''779190''>ideas</span>
  <span m=''779580''>in</span> <span m=''779760''>the</span> <span m=''779880''>other</span>
  <span m=''780070''>proofs,</span> <span m=''781790''>in</span> <span m=''781950''>particular</span>
  <span m=''782390''>this</span> <span m=''782660''>one</span> <span m=''782920''>which</span>
  <span m=''783170''>is</span> <span m=''784090''>more</span> <span m=''784380''>interesting.</span>
  <span m=''789700''>I</span> <span m=''789830''>want</span> <span m=''790020''>to</span>
  <span m=''790100''>look</span> <span m=''790340''>at</span> <span m=''791330''>leaves</span>
  <span m=''792533''>of</span> <span m=''793500''>my</span> <span m=''793740''>tree.</span>
  <span m=''795380''>And</span> <span m=''795560''>we</span> <span m=''795660''>have</span>
  <span m=''795760''>to</span> <span m=''795890''>remember</span> <span m=''796290''>back</span>
  <span m=''796610''>to the</span> <span m=''797110''>previous</span> <span m=''797530''>lecture,</span>
  <span m=''800450''>who</span> <span m=''800630''>can</span> <span m=''800790''>be</span>
  <span m=''800940''>at</span> <span m=''801050''>the</span> <span m=''801130''>leaves?</span>
  <span m=''803080''>Well,</span> <span m=''803430''>if could</span> <span m=''803640''>be</span>
  <span m=''803720''>a</span> <span m=''803840''>vertex</span> <span m=''805190''>or</span>
  <span m=''805330''>it</span> <span m=''805430''>could</span> <span m=''805460''>be</span>
  <span m=''805570''>an</span> <span m=''805640''>edge.</span> </p><p><span m=''806880''>When</span>
  <span m=''807060''>it</span> <span m=''807090''>was</span> <span m=''807270''>an</span>
  <span m=''807360''>edge,</span> <span m=''807660''>we</span> <span m=''807770''>called</span>
  <span m=''808010''>it</span> <span m=''808090''>a</span> <span m=''808140''>fold</span>
  <span m=''808500''>point.</span> <span m=''809230''>When</span> <span m=''809390''>we</span>
  <span m=''809500''>folded</span> <span m=''810060''>in</span> <span m=''810250''>the</span>
  <span m=''810340''>middle</span> <span m=''810600''>of</span> <span m=''810720''>an</span>
  <span m=''810800''>edge--</span> <span m=''811240''>so</span> <span m=''811450''>here''s</span>
  <span m=''811890''>an</span> <span m=''812185''>edge</span> <span m=''812480''>of
  the</span> <span m=''812570''>polygon</span> <span m=''813730''>and</span> <span
  m=''814010''>I</span> <span m=''814090''>end</span> <span m=''814330''>up</span>
  <span m=''815390''>subdividing</span> <span m=''816090''>it</span> <span m=''816230''>and</span>
  <span m=''816410''>gluing</span> <span m=''816730''>the</span> <span m=''816840''>edge</span>
  <span m=''817050''>onto</span> <span m=''817280''>itself--</span> <span m=''818790''>right</span>
  <span m=''819030''>there</span> <span m=''819710''>is</span> <span m=''819830''>180</span>
  <span m=''820360''>degrees</span> <span m=''820670''>of</span> <span m=''820740''>curvature.</span>
  <span m=''821710''>Total</span> <span m=''821990''>amount</span> <span m=''822180''>of</span>
  <span m=''822270''>curvature</span> <span m=''822730''>is</span> <span m=''822820''>720,</span>
  <span m=''824520''>therefore</span> <span m=''825190''>I</span> <span m=''825310''>only</span>
  <span m=''825550''>have--</span> <span m=''826730''>I</span> <span m=''826850''>can''t</span>
  <span m=''827080''>count,</span> <span m=''827370''>I''m</span> <span m=''827460''>jetlagged--</span>
  <span m=''827880''>four of</span> <span m=''828310''>them.</span> <span m=''829420''>At</span>
  <span m=''829560''>most</span> <span m=''829780''>four</span> <span m=''830450''>fold</span>
  <span m=''830720''>points.</span> </p><p><span m=''832200''>Everybody</span> <span
  m=''832690''>else</span> <span m=''832920''>is</span> <span m=''833030''>a</span>
  <span m=''833080''>vertex.</span> <span m=''834560''>So</span> <span m=''834610''>if</span>
  <span m=''834700''>I</span> <span m=''834800''>have n</span> <span m=''835050''>vertices,</span>
  <span m=''836110''>I</span> <span m=''836230''>have</span> <span m=''836450''>at</span>
  <span m=''836550''>most</span> <span m=''838340''>n</span> <span m=''838510''>plus</span>
  <span m=''838760''>4</span> <span m=''839000''>leaves.</span> <span m=''843880''>That''s</span>
  <span m=''844130''>already</span> <span m=''844400''>feeling</span> <span m=''844730''>good.</span>
  <span m=''845970''>I</span> <span m=''846660''>pull</span> <span m=''847150''>a</span>
  <span m=''847310''>rabbit</span> <span m=''847650''>out</span> <span m=''847770''>of</span>
  <span m=''847820''>a hat and</span> <span m=''848220''>tell</span> <span m=''848450''>you</span>
  <span m=''848640''>that</span> <span m=''848770''>if</span> <span m=''848910''>I</span>
  <span m=''848970''>have</span> <span m=''849390''>only</span> <span m=''849680''>n</span>
  <span m=''849830''>plus</span> <span m=''850050''>4</span> <span m=''850260''>leaves,</span>
  <span m=''851060''>there</span> <span m=''851200''>are</span> <span m=''851260''>2</span>
  <span m=''851550''>to the</span> <span m=''851740''>order</span> <span m=''852060''>n</span>
  <span m=''853040''>trees</span> <span m=''854220''>on</span> <span m=''854420''>that</span>
  <span m=''854590''>many</span> <span m=''854810''>leaves.</span> </p><p><span m=''860970''>Actually,</span>
  <span m=''861530''>I</span> <span m=''862030''>should be</span> <span m=''862530''>a</span>
  <span m=''862570''>little</span> <span m=''862800''>more</span> <span m=''862980''>careful.</span>
  <span m=''865580''>If</span> <span m=''865760''>I</span> <span m=''865820''>can</span>
  <span m=''865980''>bound</span> <span m=''866210''>the</span> <span m=''866270''>number</span>
  <span m=''866570''>of</span> <span m=''866650''>nodes</span> <span m=''867070''>in</span>
  <span m=''867170''>the</span> <span m=''867270''>tree,</span> <span m=''868560''>then</span>
  <span m=''868910''>I''ll</span> <span m=''869100''>get</span> <span m=''869290''>an</span>
  <span m=''869420''>exponential</span> <span m=''869930''>bound</span> <span m=''870200''>on</span>
  <span m=''870320''>the</span> <span m=''870390''>number</span> <span m=''870680''>of</span>
  <span m=''870730''>trees.</span> <span m=''871060''>And</span> <span m=''871160''>that</span>
  <span m=''871320''>will</span> <span m=''871440''>be</span> <span m=''871600''>part</span>
  <span m=''871880''>one,</span> <span m=''872250''>the</span> <span m=''872390''>abstract</span>
  <span m=''872820''>gluing</span> <span m=''873110''>tree.</span> <span m=''874590''>But</span>
  <span m=''874800''>right</span> <span m=''874960''>now</span> <span m=''875110''>I
  have</span> <span m=''875250''>a</span> <span m=''875300''>bound</span> <span m=''875500''>on</span>
  <span m=''875590''>the</span> <span m=''875640''>number</span> <span m=''875850''>of</span>
  <span m=''875930''>leaves,</span> <span m=''876320''>not</span> <span m=''876500''>the</span>
  <span m=''876580''>number</span> <span m=''876810''>of</span> <span m=''876890''>nodes.</span>
  </p><p><span m=''877530''>And</span> <span m=''877720''>there''s</span> <span m=''877890''>a</span>
  <span m=''877950''>difference</span> <span m=''878340''>here,</span> <span m=''878580''>because</span>
  <span m=''879450''>if</span> <span m=''879620''>you</span> <span m=''879720''>have</span>
  <span m=''880130''>a</span> <span m=''880220''>tree</span> <span m=''881160''>which</span>
  <span m=''881350''>has</span> <span m=''881560''>a</span> <span m=''881620''>whole</span>
  <span m=''881990''>bunch</span> <span m=''882730''>of</span> <span m=''882990''>degree</span>
  <span m=''883300''>2</span> <span m=''883520''>vertices,</span> <span m=''888730''>then</span>
  <span m=''889310''>that</span> <span m=''889550''>would</span> <span m=''889640''>be</span>
  <span m=''889770''>bad,</span> <span m=''892020''>because</span> <span m=''892240''>I</span>
  <span m=''892290''>only</span> <span m=''892460''>have</span> <span m=''892590''>two</span>
  <span m=''892770''>leaves</span> <span m=''893190''>I</span> <span m=''893300''>have</span>
  <span m=''893450''>arbitrarily</span> <span m=''893990''>many</span> <span m=''894230''>nodes.</span>
  <span m=''895770''>But</span> <span m=''896710''>every</span> <span m=''897040''>time</span>
  <span m=''897320''>I</span> <span m=''897410''>have</span> <span m=''897720''>one</span>
  <span m=''897910''>of</span> <span m=''898010''>these</span> <span m=''899330''>degree</span>
  <span m=''899730''>2</span> <span m=''899910''>nodes,</span> <span m=''900190''>we</span>
  <span m=''900340''>already</span> <span m=''900660''>threw</span> <span m=''900960''>away</span>
  <span m=''902020''>the</span> <span m=''902130''>degree</span> <span m=''902430''>2</span>
  <span m=''902640''>nodes</span> <span m=''903040''>that</span> <span m=''903160''>had</span>
  <span m=''903410''>no</span> <span m=''903520''>vertices</span> <span m=''904010''>at</span>
  <span m=''904200''>them,</span> <span m=''904740''>because</span> <span m=''905000''>there</span>
  <span m=''905130''>are</span> <span m=''905170''>infinitely</span> <span m=''905570''>many</span>
  <span m=''905770''>of</span> <span m=''905820''>those</span> <span m=''906320''>and
  those don''t</span> <span m=''906540''>count.</span> <span m=''906870''>So</span>
  <span m=''907050''>once</span> <span m=''907230''>we</span> <span m=''907340''>throw</span>
  <span m=''907500''>that</span> <span m=''907690''>away,</span> <span m=''908260''>the</span>
  <span m=''908410''>only</span> <span m=''908650''>degree</span> <span m=''908920''>two</span>
  <span m=''911970''>junctions</span> <span m=''912340''>are</span> <span m=''912440''>the</span>
  <span m=''912560''>ones</span> <span m=''912750''>that</span> <span m=''912840''>have</span>
  <span m=''913000''>a</span> <span m=''913040''>vertex,</span> <span m=''913500''>which
  is</span> <span m=''913790''>why--</span> <span m=''914700''>these</span> <span
  m=''914920''>dots</span> <span m=''915290''>are</span> <span m=''915360''>supposed</span>
  <span m=''915630''>to</span> <span m=''915670''>be</span> <span m=''915740''>the</span>
  <span m=''915830''>actual</span> <span m=''916160''>vertices</span> <span m=''916590''>of</span>
  <span m=''916640''>the</span> <span m=''916720''>polygon.</span> <span m=''917200''>So
  it</span> <span m=''917320''>might</span> <span m=''917500''>be</span> <span m=''917580''>an</span>
  <span m=''917650''>edge</span> <span m=''917890''>here,</span> <span m=''918560''>it</span>
  <span m=''918690''>might be an</span> <span m=''918770''>edge</span> <span m=''919020''>there.</span>
  </p><p><span m=''919530''>There''s</span> <span m=''919700''>at</span> <span m=''919790''>least</span>
  <span m=''920000''>one</span> <span m=''920150''>vertex</span> <span m=''920540''>at</span>
  <span m=''920600''>each</span> <span m=''920800''>of</span> <span m=''920900''>them.</span>
  <span m=''921660''>So</span> <span m=''921820''>the</span> <span m=''921950''>total</span>
  <span m=''922340''>number</span> <span m=''922600''>of</span> <span m=''922650''>nodes</span>
  <span m=''922920''>here</span> <span m=''923110''>is</span> <span m=''923390''>indeed</span>
  <span m=''923740''>order</span> <span m=''924050''>n.</span> <span m=''925460''>I</span>
  <span m=''925510''>mean,</span> <span m=''925710''>it''s</span> <span m=''925850''>probably</span>
  <span m=''926130''>actually</span> <span m=''926420''>at most</span> <span m=''926850''>n</span>
  <span m=''927190''>plus</span> <span m=''927520''>4</span> <span m=''927850''>again.</span>
  </p><p><span m=''928740''>But</span> <span m=''929360''>if</span> <span m=''930080''>we''re</span>
  <span m=''930270''>sloppy</span> <span m=''930660''>you say, well the</span> <span
  m=''930970''>number</span> <span m=''931220''>of leaves</span> <span m=''931470''>is</span>
  <span m=''931620''>at</span> <span m=''931690''>most</span> <span m=''931920''>n</span>
  <span m=''932040''>plus</span> <span m=''932260''>4.</span> <span m=''932450''>The</span>
  <span m=''932550''>number</span> <span m=''932960''>of</span> <span m=''933640''>degree</span>
  <span m=''933950''>2</span> <span m=''934230''>nodes</span> <span m=''934980''>is</span>
  <span m=''935330''>at</span> <span m=''935420''>most</span> <span m=''936190''>n.</span>
  <span m=''937310''>Then</span> <span m=''937460''>there</span> <span m=''937640''>could</span>
  <span m=''937760''>be</span> <span m=''937880''>some</span> <span m=''938050''>degree</span>
  <span m=''938300''>three</span> <span m=''938490''>nodes.</span> <span m=''939290''>It''s</span>
  <span m=''939380''>also</span> <span m=''939680''>at</span> <span m=''939770''>most</span>
  <span m=''940100''>n</span> <span m=''940240''>plus</span> <span m=''940460''>4</span>
  <span m=''940860''>in</span> <span m=''940980''>total,</span> <span m=''941440''>or</span>
  <span m=''941700''>n</span> <span m=''941910''>is</span> <span m=''942040''>all</span>
  <span m=''942180''>I</span> <span m=''942230''>care</span> <span m=''942440''>about.</span>
  </p><p><span m=''944470''>You</span> <span m=''944600''>could</span> <span m=''944950''>be</span>
  <span m=''945440''>more</span> <span m=''945610''>careful</span> <span m=''946100''>and
  figure</span> <span m=''946350''>out</span> <span m=''946390''>what</span> <span
  m=''946500''>the</span> <span m=''946590''>consonant</span> <span m=''946965''>is.</span>
  <span m=''947340''>But</span> <span m=''949510''>we</span> <span m=''949640''>get</span>
  <span m=''949870''>from</span> <span m=''950020''>this,</span> <span m=''950335''>this</span>
  <span m=''950650''>is</span> <span m=''950850''>order</span> <span m=''951130''>n</span>
  <span m=''951290''>nodes.</span> <span m=''954530''>And</span> <span m=''954790''>once</span>
  <span m=''954970''>you</span> <span m=''955070''>have</span> <span m=''955680''>that</span>
  <span m=''955880''>the</span> <span m=''955930''>tree</span> <span m=''956150''>has</span>
  <span m=''956390''>a</span> <span m=''956450''>linear</span> <span m=''956700''>number</span>
  <span m=''956930''>of</span> <span m=''957010''>nodes,</span> <span m=''957470''>I''ll</span>
  <span m=''957680''>tell</span> <span m=''957910''>you</span> <span m=''958470''>this</span>
  <span m=''958640''>is</span> <span m=''959570''>one</span> <span m=''959780''>of</span>
  <span m=''959830''>the</span> <span m=''959930''>[? Kadhalan ?]</span> <span m=''960390''>problems,</span>
  <span m=''961220''>that</span> <span m=''961350''>there''s</span> <span m=''961490''>only</span>
  <span m=''961710''>2</span> <span m=''961860''>the</span> <span m=''962100''>order</span>
  <span m=''962320''>n</span> <span m=''962560''>such</span> <span m=''962850''>trees.</span>
  </p><p><span m=''963470''>But</span> <span m=''963600''>that''s</span> <span m=''963840''>only</span>
  <span m=''964210''>part</span> <span m=''964490''>one</span> <span m=''965460''>of</span>
  <span m=''965930''>the</span> <span m=''966040''>combinatorial</span> <span m=''966630''>type</span>
  <span m=''966900''>of the</span> <span m=''966990''>gluing.</span> <span m=''967600''>We</span>
  <span m=''967790''>also</span> <span m=''968040''>have</span> <span m=''968200''>to</span>
  <span m=''968310''>worry</span> <span m=''968510''>about</span> <span m=''969520''>which</span>
  <span m=''969760''>vertices</span> <span m=''970210''>are</span> <span m=''970310''>where.</span>
  <span m=''973540''>I</span> <span m=''973580''>want</span> <span m=''973760''>to</span>
  <span m=''973820''>show</span> <span m=''974040''>that that</span> <span m=''974500''>is</span>
  <span m=''975330''>only</span> <span m=''975580''>exponential.</span> </p><p><span
  m=''984150''>So</span> <span m=''984700''>imagine</span> <span m=''988180''>at</span>
  <span m=''988310''>this</span> <span m=''988460''>point</span> <span m=''988610''>you''ve</span>
  <span m=''988710''>fixed</span> <span m=''989110''>the</span> <span m=''989360''>combinatorial</span>
  <span m=''989940''>structure</span> <span m=''990290''>of</span> <span m=''990340''>the</span>
  <span m=''990440''>tree,</span> <span m=''990910''>but</span> <span m=''991200''>you</span>
  <span m=''991320''>have</span> <span m=''991440''>no</span> <span m=''991560''>idea</span>
  <span m=''991960''>what''s</span> <span m=''992295''>what.</span> <span m=''993720''>So</span>
  <span m=''993840''>in</span> <span m=''993910''>particular,</span> <span m=''995270''>at</span>
  <span m=''995480''>these</span> <span m=''996320''>points--</span> <span m=''997430''>and</span>
  <span m=''997890''>maybe</span> <span m=''998270''>also</span> <span m=''1000060''>you''ve</span>
  <span m=''1000350''>defined</span> <span m=''1000810''>some</span> <span m=''1000990''>degree</span>
  <span m=''1001290''>2</span> <span m=''1001450''>junctions,</span> <span m=''1002090''>which</span>
  <span m=''1002300''>you know</span> <span m=''1002685''>are</span> <span m=''1003070''>supposed</span>
  <span m=''1003340''>to</span> <span m=''1003400''>have</span> <span m=''1003620''>at</span>
  <span m=''1003660''>least</span> <span m=''1003880''>one</span> <span m=''1004040''>vertex--</span>
  <span m=''1006830''>the</span> <span m=''1007720''>first</span> <span m=''1008000''>thing</span>
  <span m=''1008170''>I</span> <span m=''1008210''>want</span> <span m=''1008410''>to</span>
  <span m=''1008470''>specify</span> <span m=''1009140''>is,</span> <span m=''1009490''>for</span>
  <span m=''1009650''>each</span> <span m=''1009840''>of</span> <span m=''1009920''>these</span>
  <span m=''1010110''>little</span> <span m=''1010360''>dots</span> <span m=''1010990''>that</span>
  <span m=''1011150''>come</span> <span m=''1011360''>together--</span> <span m=''1012720''>these</span>
  <span m=''1012950''>are</span> <span m=''1013000''>the</span> <span m=''1013150''>junctions--</span>
  <span m=''1016140''>is</span> <span m=''1016330''>it</span> <span m=''1016420''>a</span>
  <span m=''1016450''>vertex,</span> <span m=''1016910''>or</span> <span m=''1017030''>is</span>
  <span m=''1017130''>it</span> <span m=''1017220''>an</span> <span m=''1017340''>edge?</span>
  <span m=''1019510''>So</span> <span m=''1019820''>that''s</span> <span m=''1020060''>just</span>
  <span m=''1020240''>binary</span> <span m=''1020570''>information</span> <span m=''1021070''>for</span>
  <span m=''1021170''>each</span> <span m=''1021340''>one.</span> <span m=''1021570''>I''ll</span>
  <span m=''1021710''>fill</span> <span m=''1021970''>it</span> <span m=''1022040''>in,</span>
  <span m=''1022250''>say</span> <span m=''1022420''>if</span> <span m=''1022520''>it''s</span>
  <span m=''1022650''>a</span> <span m=''1022690''>vertex,</span> <span m=''1023220''>I''ll</span>
  <span m=''1023230''>leave</span> <span m=''1023390''>it</span> <span m=''1023460''>open</span>
  <span m=''1023810''>if</span> <span m=''1023950''>it''s</span> <span m=''1024109''>an</span>
  <span m=''1024190''>edge.</span> </p><p><span m=''1025900''>In</span> <span m=''1025930''>fact,</span>
  <span m=''1026230''>I</span> <span m=''1026300''>know</span> <span m=''1026680''>that</span>
  <span m=''1027460''>at most</span> <span m=''1027750''>one</span> <span m=''1028050''>edge</span>
  <span m=''1028410''>comes</span> <span m=''1028630''>together</span> <span m=''1028990''>at</span>
  <span m=''1029040''>any</span> <span m=''1029220''>point.</span> <span m=''1029550''>Otherwise,</span>
  <span m=''1029930''>you''d</span> <span m=''1030050''>have</span> <span m=''1030200''>too</span>
  <span m=''1030359''>much</span> <span m=''1031050''>material</span> <span m=''1031329''>glued</span>
  <span m=''1031609''>there.</span> <span m=''1033140''>So</span> <span m=''1033290''>maybe</span>
  <span m=''1033470''>it</span> <span m=''1033530''>looks</span> <span m=''1034450''>something</span>
  <span m=''1034810''>like</span> <span m=''1034990''>this.</span> <span m=''1035975''>It</span>
  <span m=''1036450''>could</span> <span m=''1036569''>be</span> <span m=''1036680''>a</span>
  <span m=''1036730''>fold</span> <span m=''1037020''>point,</span> <span m=''1037390''>maybe</span>
  <span m=''1037609''>another</span> <span m=''1037890''>fold</span> <span m=''1038190''>point.</span>
  <span m=''1042640''>Something</span> <span m=''1042849''>like</span> <span m=''1043040''>that.</span>
  </p><p><span m=''1044040''>So</span> <span m=''1044210''>that</span> <span m=''1044440''>coloring,</span>
  <span m=''1045210''>black</span> <span m=''1045460''>and</span> <span m=''1045540''>white,</span>
  <span m=''1046220''>there''s</span> <span m=''1046390''>only</span> <span m=''1046630''>2
  to</span> <span m=''1046880''>the</span> <span m=''1047040''>order</span> <span
  m=''1047770''>and</span> <span m=''1048830''>such</span> <span m=''1049360''>colorings.</span>
  <span m=''1050030''>Call</span> <span m=''1050180''>it a</span> <span m=''1050350''>vertex</span>
  <span m=''1051570''>edge</span> <span m=''1051930''>coloring,</span> <span m=''1055590''>because</span>
  <span m=''1055810''>again</span> <span m=''1056070''>there''s</span> <span m=''1056240''>order</span>
  <span m=''1056450''>n</span> <span m=''1057450''>dots.</span> <span m=''1057940''>Each</span>
  <span m=''1058160''>one,</span> <span m=''1058520''>there''s</span> <span m=''1058690''>two</span>
  <span m=''1058840''>choices,</span> <span m=''1059610''>black</span> <span m=''1059910''>or</span>
  <span m=''1059970''>white,</span> <span m=''1060980''>vertex</span> <span m=''1061340''>or</span>
  <span m=''1061440''>edge.</span> </p><p><span m=''1065610''>And</span> <span m=''1065780''>now</span>
  <span m=''1066810''>what</span> <span m=''1066950''>we</span> <span m=''1067090''>really</span>
  <span m=''1067320''>care</span> <span m=''1067510''>about</span> <span m=''1067720''>is</span>
  <span m=''1067980''>where</span> <span m=''1068110''>the</span> <span m=''1068210''>vertices,</span>
  <span m=''1069650''>because</span> <span m=''1069840''>remember,</span> <span m=''1070110''>this</span>
  <span m=''1070360''>is</span> <span m=''1070530''>the</span> <span m=''1070630''>polygon</span>
  <span m=''1071410''>in</span> <span m=''1071580''>order.</span> <span m=''1073330''>So</span>
  <span m=''1073470''>if</span> <span m=''1073570''>I</span> <span m=''1073650''>could</span>
  <span m=''1073850''>tell</span> <span m=''1074040''>you,</span> <span m=''1075660''>let''s</span>
  <span m=''1075870''>say</span> <span m=''1076050''>which</span> <span m=''1076370''>vertex</span>
  <span m=''1076760''>is</span> <span m=''1076850''>vertex</span> <span m=''1077200''>one?</span>
  <span m=''1077600''>Maybe</span> <span m=''1078690''>this</span> <span m=''1078960''>vertex</span>
  <span m=''1079410''>is</span> <span m=''1079490''>vertex</span> <span m=''1079860''>one.</span>
  <span m=''1080990''>Then</span> <span m=''1081130''>I</span> <span m=''1081180''>know</span>
  <span m=''1081320''>this</span> <span m=''1081530''>is</span> <span m=''1081630''>vertex</span>
  <span m=''1082020''>two,</span> <span m=''1082690''>I know</span> <span m=''1082930''>this</span>
  <span m=''1083100''>is</span> <span m=''1083200''>vertex</span> <span m=''1083590''>three,</span>
  <span m=''1084240''>I</span> <span m=''1084330''>know</span> <span m=''1084480''>this</span>
  <span m=''1084670''>is</span> <span m=''1084850''>edge</span> <span m=''1085320''>three</span>
  <span m=''1085730''>or</span> <span m=''1085920''>whichever</span> <span m=''1086310''>edge</span>
  <span m=''1086470''>connects</span> <span m=''1086860''>V3</span> <span m=''1087510''>three</span>
  <span m=''1088020''>and</span> <span m=''1088440''>V4.</span> </p><p><span m=''1089600''>This</span>
  <span m=''1089770''>is</span> <span m=''1089910''>also</span> <span m=''1090250''>edge</span>
  <span m=''1090580''>three,</span> <span m=''1091290''>and</span> <span m=''1091390''>so</span>
  <span m=''1091540''>on.</span> <span m=''1091690''>I</span> <span m=''1091750''>could</span>
  <span m=''1091910''>just</span> <span m=''1092050''>walk</span> <span m=''1092280''>around</span>
  <span m=''1093010''>and</span> <span m=''1093250''>label</span> <span m=''1093540''>them</span>
  <span m=''1093870''>in</span> <span m=''1094030''>order.</span> <span m=''1095210''>All</span>
  <span m=''1095430''>I</span> <span m=''1095520''>needed</span> <span m=''1095740''>to</span>
  <span m=''1095870''>do</span> <span m=''1096070''>is</span> <span m=''1096180''>know
  where</span> <span m=''1096570''>vertex</span> <span m=''1096920''>one</span> <span
  m=''1097160''>is.</span> <span m=''1098380''>There''s</span> <span m=''1098580''>only</span>
  <span m=''1098910''>n</span> <span m=''1100700''>possibilities</span> <span m=''1101300''>for</span>
  <span m=''1101380''>that.</span> </p><p><span m=''1108040''>There''s</span> <span
  m=''1108290''>n</span> <span m=''1108820''>filled</span> <span m=''1109110''>circles,</span>
  <span m=''1109500''>which</span> <span m=''1109680''>are</span> <span m=''1109730''>where</span>
  <span m=''1109820''>the</span> <span m=''1109920''>vertices</span> <span m=''1110370''>are.</span>
  <span m=''1111540''>One</span> <span m=''1111820''>of</span> <span m=''1111900''>them</span>
  <span m=''1112060''>is</span> <span m=''1112180''>V1,</span> <span m=''1112960''>so</span>
  <span m=''1113140''>there''s</span> <span m=''1113300''>only</span> <span m=''1113480''>n</span>
  <span m=''1113680''>choices</span> <span m=''1114060''>for</span> <span m=''1114400''>it.</span>
  <span m=''1114910''>You</span> <span m=''1115150''>multiply</span> <span m=''1116900''>all</span>
  <span m=''1117150''>of</span> <span m=''1117210''>these</span> <span m=''1117440''>things</span>
  <span m=''1117670''>together,</span> <span m=''1119480''>n</span> <span m=''1119910''>times</span>
  <span m=''1120180''>2</span> <span m=''1120340''>to the</span> <span m=''1120460''>order</span>
  <span m=''1120650''>n,</span> <span m=''1120830''>times</span> <span m=''1121050''>2</span>
  <span m=''1121200''>to the</span> <span m=''1121360''>order</span> <span m=''1121580''>n,</span>
  <span m=''1122390''>that</span> <span m=''1122670''>result</span> <span m=''1123030''>is</span>
  <span m=''1123170''>2</span> <span m=''1123350''>to the</span> <span m=''1123570''>some</span>
  <span m=''1123810''>other</span> <span m=''1124120''>order</span> <span m=''1124430''>n.</span>
  <span m=''1127320''>That''s</span> <span m=''1127590''>total</span> <span m=''1127850''>number</span>
  <span m=''1128090''>of</span> <span m=''1128170''>choices.</span> </p><p><span m=''1130380''>So</span>
  <span m=''1130450''>that''s</span> <span m=''1130680''>a</span> <span m=''1130980''>rough</span>
  <span m=''1131530''>but</span> <span m=''1132630''>fine</span> <span m=''1133120''>upper</span>
  <span m=''1133370''>bound.</span> <span m=''1135090''>I''m</span> <span m=''1135140''>not</span>
  <span m=''1135280''>going</span> <span m=''1135380''>to</span> <span m=''1135450''>try</span>
  <span m=''1135710''>to</span> <span m=''1135850''>tune</span> <span m=''1136040''>this</span>
  <span m=''1136210''>constant.</span> <span m=''1136850''>I</span> <span m=''1136940''>guess</span>
  <span m=''1137160''>it would</span> <span m=''1137300''>be an</span> <span m=''1137670''>open
  problem</span> <span m=''1137970''>to</span> <span m=''1138100''>get</span> <span
  m=''1138260''>a</span> <span m=''1138320''>really</span> <span m=''1138550''>good</span>
  <span m=''1138710''>bound</span> <span m=''1138930''>on</span> <span m=''1139000''>the</span>
  <span m=''1139100''>constant.</span> <span m=''1139530''>I''m</span> <span m=''1139620''>not</span>
  <span m=''1139810''>sure</span> <span m=''1139950''>if</span> <span m=''1140150''>even</span>
  <span m=''1140370''>one</span> <span m=''1140510''>has</span> <span m=''1140670''>been</span>
  <span m=''1140800''>worked</span> <span m=''1141040''>out,</span> <span m=''1141840''>but</span>
  <span m=''1141930''>what</span> <span m=''1142070''>I</span> <span m=''1142120''>will</span>
  <span m=''1142240''>show</span> <span m=''1142410''>you</span> <span m=''1142590''>is</span>
  <span m=''1142700''>that</span> <span m=''1142830''>this</span> <span m=''1143000''>is</span>
  <span m=''1143330''>pretty</span> <span m=''1143550''>much</span> <span m=''1143780''>tight,</span>
  <span m=''1144660''>so</span> <span m=''1144900''>you</span> <span m=''1145060''>can''t</span>
  <span m=''1145260''>hope</span> <span m=''1145460''>to</span> <span m=''1145570''>do</span>
  <span m=''1145740''>much</span> <span m=''1146000''>better</span> <span m=''1146230''>than</span>
  <span m=''1146400''>this</span> <span m=''1147140''>because</span> <span m=''1147540''>there''s</span>
  <span m=''1147710''>a</span> <span m=''1147810''>2</span> <span m=''1148130''>to</span>
  <span m=''1148350''>the</span> <span m=''1148450''>omega</span> <span m=''1148770''>n</span>
  <span m=''1149320''>lower</span> <span m=''1149610''>bound</span> <span m=''1150750''>on</span>
  <span m=''1150990''>the</span> <span m=''1151070''>number</span> <span m=''1151490''>of</span>
  <span m=''1154030''>gluings.</span> </p><p><span m=''1157220''>And</span> <span
  m=''1157310''>that</span> <span m=''1158330''>is</span> <span m=''1158620''>this</span>
  <span m=''1158950''>crazy</span> <span m=''1159270''>example.</span> <span m=''1161170''>I''ll</span>
  <span m=''1161910''>draw it</span> <span m=''1162230''>also</span> <span m=''1162660''>on</span>
  <span m=''1162790''>the</span> <span m=''1162880''>board.</span> <span m=''1164860''>It''s</span>
  <span m=''1165020''>a</span> <span m=''1165070''>little</span> <span m=''1165260''>tricky</span>
  <span m=''1165560''>to</span> <span m=''1165640''>draw.</span> <span m=''1166410''>It''s
  a</span> <span m=''1166590''>very</span> <span m=''1167130''>spiky</span> <span
  m=''1167640''>star,</span> <span m=''1171290''>something</span> <span m=''1171740''>like</span>
  <span m=''1171930''>that.</span> </p><p><span m=''1172500''>So</span> <span m=''1173130''>I</span>
  <span m=''1173240''>have</span> <span m=''1173450''>e</span> <span m=''1173915''>points,</span>
  <span m=''1176430''>and</span> <span m=''1177810''>n</span> <span m=''1178200''>spikes,</span>
  <span m=''1181430''>n</span> <span m=''1181710''>convex</span> <span m=''1182350''>corners.</span>
  <span m=''1185090''>The</span> <span m=''1185330''>convex</span> <span m=''1185810''>angle,</span>
  <span m=''1186290''>I</span> <span m=''1186390''>think,</span> <span m=''1186700''>is</span>
  <span m=''1187010''>alpha.</span> <span m=''1187420''>Let</span> <span m=''1187580''>me</span>
  <span m=''1187730''>match</span> <span m=''1188090''>the</span> <span m=''1188190''>notation.</span>
  <span m=''1189772''>Yes,</span> <span m=''1190170''>convex</span> <span m=''1190610''>angle</span>
  <span m=''1190870''>is</span> <span m=''1190990''>alpha.</span> </p><p><span m=''1192060''>The</span>
  <span m=''1192190''>reflex</span> <span m=''1192670''>angle</span> <span m=''1193030''>here</span>
  <span m=''1193970''>is</span> <span m=''1194210''>beta,</span> <span m=''1195380''>but</span>
  <span m=''1195510''>otherwise</span> <span m=''1195920''>it''s</span> <span m=''1196060''>completely</span>
  <span m=''1196410''>symmetric.</span> <span m=''1197020''>So</span> <span m=''1197170''>all</span>
  <span m=''1197665''>the</span> <span m=''1198160''>reflex</span> <span m=''1198540''>angles</span>
  <span m=''1198810''>are</span> <span m=''1198860''>beta,</span> <span m=''1199530''>all</span>
  <span m=''1199760''>the</span> <span m=''1199850''>convex</span> <span m=''1200260''>angles</span>
  <span m=''1200630''>are</span> <span m=''1200910''>alpha.</span> <span m=''1201616''>I</span>
  <span m=''1202042''>have</span> <span m=''1202470''>n</span> <span m=''1202700''>spikes.</span>
  </p><p><span m=''1203630''>I</span> <span m=''1207240''>want</span> <span m=''1207810''>these</span>
  <span m=''1208150''>points--</span> <span m=''1209120''>it''s</span> <span m=''1209240''>hard</span>
  <span m=''1209420''>to</span> <span m=''1209490''>draw,</span> <span m=''1209730''>but</span>
  <span m=''1209880''>I</span> <span m=''1209930''>want</span> <span m=''1210130''>them</span>
  <span m=''1210250''>to</span> <span m=''1210300''>be</span> <span m=''1210430''>very,</span>
  <span m=''1210930''>very</span> <span m=''1211070''>close</span> <span m=''1211380''>to</span>
  <span m=''1211460''>the</span> <span m=''1211580''>center.</span> <span m=''1213450''>Take</span>
  <span m=''1213700''>the</span> <span m=''1213790''>limit.</span> <span m=''1214920''>In</span>
  <span m=''1215070''>the</span> <span m=''1215160''>limit,</span> <span m=''1217360''>alpha
  is</span> <span m=''1217630''>0.</span> <span m=''1218680''>So</span> <span m=''1218880''>alpha</span>
  <span m=''1219230''>is</span> <span m=''1219350''>going</span> <span m=''1219500''>to</span>
  <span m=''1219570''>be</span> <span m=''1220360''>some</span> <span m=''1220640''>very</span>
  <span m=''1220900''>tiny</span> <span m=''1221250''>amount</span> <span m=''1221490''>epsilon.</span>
  </p><p><span m=''1224020''>Beta.</span> <span m=''1227280''>What''s</span> <span
  m=''1227590''>the</span> <span m=''1227690''>limit</span> <span m=''1227970''>of</span>
  <span m=''1228050''>beta?</span> <span m=''1230690''>180,</span> <span m=''1231520''>360?</span>
  <span m=''1232920''>No,</span> <span m=''1234080''>it''s</span> <span m=''1234250''>not</span>
  <span m=''1234510''>360.</span> <span m=''1235080''>That''s</span> <span m=''1235520''>what''s</span>
  <span m=''1235710''>important.</span> </p><p><span m=''1239210''>360</span> <span
  m=''1242270''>times</span> <span m=''1242510''>1</span> <span m=''1242690''>minus</span>
  <span m=''1242940''>1</span> <span m=''1243090''>over</span> <span m=''1243270''>n,</span>
  <span m=''1243680''>yeah.</span> <span m=''1244520''>It''s</span> <span m=''1244650''>like</span>
  <span m=''1244790''>360</span> <span m=''1245240''>minus</span> <span m=''1245680''>360</span>
  <span m=''1246170''>over</span> <span m=''1246370''>n.</span> <span m=''1251050''>Believe</span>
  <span m=''1251370''>it</span> <span m=''1251420''>or</span> <span m=''1251470''>not,</span>
  <span m=''1251680''>this</span> <span m=''1251830''>is</span> <span m=''1251950''>a</span>
  <span m=''1252030''>big</span> <span m=''1252300''>number,</span> <span m=''1254170''>in</span>
  <span m=''1254360''>that</span> <span m=''1254470''>it</span> <span m=''1254610''>doesn''t</span>
  <span m=''1254890''>depend</span> <span m=''1255210''>on</span> <span m=''1255330''>epsilon.</span>
  <span m=''1256380''>So</span> <span m=''1256770''>it''s</span> <span m=''1256970''>going</span>
  <span m=''1257110''>to</span> <span m=''1257180''>be,</span> <span m=''1257650''>what,</span>
  <span m=''1257880''>a</span> <span m=''1257960''>little</span> <span m=''1258210''>bit</span>
  <span m=''1259830''>smaller--</span> <span m=''1260690''>going</span> <span m=''1260810''>to</span>
  <span m=''1260870''>be</span> <span m=''1260980''>some</span> <span m=''1261120''>minus</span>
  <span m=''1261460''>epsilon</span> <span m=''1261840''>prime.</span> </p><p><span
  m=''1262140''>But</span> <span m=''1262460''>I</span> <span m=''1262530''>really</span>
  <span m=''1262770''>don''t</span> <span m=''1262950''>care</span> <span m=''1263160''>about</span>
  <span m=''1263460''>the</span> <span m=''1263580''>epsilons.</span> <span m=''1264170''>They''re</span>
  <span m=''1264460''>kind of</span> <span m=''1264810''>irrelevant.</span> <span
  m=''1266620''>Let</span> <span m=''1266710''>me</span> <span m=''1267080''>just</span>
  <span m=''1267300''>cross</span> <span m=''1267630''>them</span> <span m=''1267770''>out,</span>
  <span m=''1268050''>but</span> <span m=''1268230''>they''re</span> <span m=''1268380''>really</span>
  <span m=''1268610''>there.</span> </p><p><span m=''1270140''>So</span> <span m=''1270820''>alpha</span>
  <span m=''1271130''>is</span> <span m=''1271280''>basically</span> <span m=''1271690''>0,</span>
  <span m=''1273370''>beta</span> <span m=''1273810''>is</span> <span m=''1274780''>a</span>
  <span m=''1274910''>chunk</span> <span m=''1275360''>less</span> <span m=''1275710''>than</span>
  <span m=''1275960''>360.</span> <span m=''1277180''>What</span> <span m=''1277360''>this</span>
  <span m=''1277540''>means</span> <span m=''1277850''>is</span> <span m=''1278790''>in</span>
  <span m=''1278980''>the</span> <span m=''1279060''>limit</span> <span m=''1279930''>I</span>
  <span m=''1280060''>can</span> <span m=''1280400''>take</span> <span m=''1280980''>one</span>
  <span m=''1281180''>of</span> <span m=''1281230''>these</span> <span m=''1281390''>alphas</span>
  <span m=''1282120''>and</span> <span m=''1282320''>glue</span> <span m=''1282600''>it</span>
  <span m=''1282770''>into</span> <span m=''1283750''>one</span> <span m=''1283940''>of</span>
  <span m=''1284040''>the</span> <span m=''1284140''>betas,</span> <span m=''1285360''>and</span>
  <span m=''1285500''>it</span> <span m=''1285550''>will</span> <span m=''1285650''>still</span>
  <span m=''1285830''>be</span> <span m=''1285960''>less</span> <span m=''1286190''>than</span>
  <span m=''1286290''>360.</span> <span m=''1286605''>In</span> <span m=''1286920''>fact</span>
  <span m=''1287770''>I</span> <span m=''1287880''>could</span> <span m=''1288030''>glue</span>
  <span m=''1288150''>n</span> <span m=''1288560''>of the</span> <span m=''1288810''>alpha.</span>
  <span m=''1289270''>I</span> <span m=''1289350''>could</span> <span m=''1289500''>glue</span>
  <span m=''1289720''>all</span> <span m=''1290050''>of</span> <span m=''1290150''>these</span>
  <span m=''1290310''>spikes</span> <span m=''1291220''>into</span> <span m=''1291560''>one</span>
  <span m=''1291750''>of</span> <span m=''1291840''>these</span> <span m=''1292090''>gaps.</span>
  </p><p><span m=''1294080''>Remember,</span> <span m=''1294320''>the</span> <span
  m=''1294500''>limiting</span> <span m=''1294850''>picture</span> <span m=''1295340''>looks</span>
  <span m=''1295550''>like</span> <span m=''1295710''>this.</span> <span m=''1299300''>That''s</span>
  <span m=''1299500''>maybe</span> <span m=''1299710''>more</span> <span m=''1299870''>convincing.</span>
  <span m=''1300270''>It</span> <span m=''1300670''>doesn''t</span> <span m=''1300900''>look</span>
  <span m=''1301370''>that</span> <span m=''1301570''>way</span> <span m=''1301710''>here.</span>
  <span m=''1302520''>This</span> <span m=''1302820''>is</span> <span m=''1303140''>nothing.</span>
  <span m=''1303940''>Of</span> <span m=''1304060''>course,</span> <span m=''1304340''>I</span>
  <span m=''1304390''>can fit</span> <span m=''1304730''>arbitrarily</span> <span
  m=''1305280''>many</span> <span m=''1305560''>of</span> <span m=''1305610''>them</span>
  <span m=''1305760''>into</span> <span m=''1305980''>this</span> <span m=''1306190''>gap</span>
  <span m=''1307380''>and</span> <span m=''1307540''>it will</span> <span m=''1307640''>still</span>
  <span m=''1307910''>sum</span> <span m=''1308210''>to</span> <span m=''1308320''>less</span>
  <span m=''1308570''>than</span> <span m=''1308650''>360.</span> </p><p><span m=''1310750''>So</span>
  <span m=''1311660''>this</span> <span m=''1311880''>is</span> <span m=''1312030''>kind</span>
  <span m=''1312220''>of</span> <span m=''1312330''>the</span> <span m=''1312420''>key</span>
  <span m=''1312840''>to why</span> <span m=''1313070''>this</span> <span m=''1313450''>example</span>
  <span m=''1313850''>works.</span> <span m=''1316960''>I''ve</span> <span m=''1317040''>got</span>
  <span m=''1317220''>tons</span> <span m=''1317470''>a</span> <span m=''1317550''>room</span>
  <span m=''1317740''>for</span> <span m=''1317920''>alphas</span> <span m=''1319380''>in</span>
  <span m=''1319650''>the</span> <span m=''1319770''>complement</span> <span m=''1320370''>of</span>
  <span m=''1320480''>betas.</span> <span m=''1324680''>Now,</span> <span m=''1326900''>I</span>
  <span m=''1327010''>would</span> <span m=''1327160''>like</span> <span m=''1327360''>to</span>
  <span m=''1327470''>make</span> <span m=''1327650''>this</span> <span m=''1327800''>not</span>
  <span m=''1328030''>only</span> <span m=''1328650''>an</span> <span m=''1328800''>exponential</span>
  <span m=''1329390''>lower</span> <span m=''1329670''>bound</span> <span m=''1329940''>on</span>
  <span m=''1330070''>the</span> <span m=''1330570''>general</span> <span m=''1330980''>case,</span>
  <span m=''1331320''>but</span> <span m=''1331430''>also</span> <span m=''1331700''>on</span>
  <span m=''1331790''>the</span> <span m=''1331900''>edge-to-edge</span> <span m=''1332510''>case,</span>
  <span m=''1333220''>because</span> <span m=''1333410''>that''s</span> <span m=''1334160''>a</span>
  <span m=''1334280''>little</span> <span m=''1334470''>bit</span> <span m=''1334610''>stronger</span>
  <span m=''1335060''>to</span> <span m=''1335140''>say</span> <span m=''1335310''>even</span>
  <span m=''1335600''>edge-to-edge</span> <span m=''1336080''>gluings</span> <span
  m=''1336360''>there</span> <span m=''1336460''>can</span> <span m=''1336570''>be</span>
  <span m=''1336690''>exponentially</span> <span m=''1337180''>many.</span> </p><p><span
  m=''1337880''>To</span> <span m=''1338000''>do</span> <span m=''1338180''>that,</span>
  <span m=''1338910''>I''m</span> <span m=''1339070''>going</span> <span m=''1339340''>to</span>
  <span m=''1339530''>take</span> <span m=''1339980''>the</span> <span m=''1340320''>midpoint</span>
  <span m=''1341090''>of</span> <span m=''1341610''>one</span> <span m=''1341860''>of</span>
  <span m=''1341920''>the</span> <span m=''1342050''>edges,</span> <span m=''1343080''>call</span>
  <span m=''1343320''>that</span> <span m=''1343480''>a</span> <span m=''1343510''>vertex,</span>
  <span m=''1344600''>and</span> <span m=''1344810''>take</span> <span m=''1345090''>the</span>
  <span m=''1345470''>perimeter</span> <span m=''1346100''>antipode,</span> <span
  m=''1347300''>which</span> <span m=''1347520''>is</span> <span m=''1347640''>like</span>
  <span m=''1347830''>here</span> <span m=''1349090''>hopefully,</span> <span m=''1349590''>more</span>
  <span m=''1349790''>or</span> <span m=''1349820''>less.</span> <span m=''1350420''>So</span>
  <span m=''1351080''>I</span> <span m=''1351150''>want</span> <span m=''1351340''>the</span>
  <span m=''1351420''>left</span> <span m=''1351600''>parameter</span> <span m=''1351900''>and</span>
  <span m=''1351970''>the</span> <span m=''1352030''>right</span> <span m=''1352220''>perimeter</span>
  <span m=''1352570''>to</span> <span m=''1352670''>be</span> <span m=''1352850''>equal,</span>
  <span m=''1354020''>also</span> <span m=''1354280''>call</span> <span m=''1354450''>that</span>
  <span m=''1354640''>a</span> <span m=''1354680''>vertex.</span> <span m=''1355930''>And</span>
  <span m=''1356140''>now</span> <span m=''1356270''>one</span> <span m=''1356440''>thing</span>
  <span m=''1356610''>we</span> <span m=''1356750''>know</span> <span m=''1356900''>how</span>
  <span m=''1357020''>to</span> <span m=''1357140''>do</span> <span m=''1357410''>is</span>
  <span m=''1357720''>perimeter</span> <span m=''1358150''>halving.</span> </p><p><span
  m=''1358520''>Now,</span> <span m=''1358680''>we were</span> <span m=''1358860''>only</span>
  <span m=''1359010''>supposed to</span> <span m=''1359270''>do</span> <span m=''1359530''>perimeter</span>
  <span m=''1359920''>halving</span> <span m=''1360250''>on</span> <span m=''1360380''>convex</span>
  <span m=''1360850''>polygons,</span> <span m=''1361400''>but</span> <span m=''1361530''>it</span>
  <span m=''1361670''>turns</span> <span m=''1361890''>out</span> <span m=''1362000''>it</span>
  <span m=''1362060''>will</span> <span m=''1362180''>work</span> <span m=''1362400''>on</span>
  <span m=''1362490''>this</span> <span m=''1362650''>polygon</span> <span m=''1363090''>too.</span>
  <span m=''1363850''>So</span> <span m=''1363880''>I''m</span> <span m=''1363940''>going</span>
  <span m=''1364020''>to</span> <span m=''1364070''>glue</span> <span m=''1364240''>this</span>
  <span m=''1364840''>half</span> <span m=''1365130''>edge</span> <span m=''1365350''>to</span>
  <span m=''1365440''>this</span> <span m=''1365620''>half</span> <span m=''1365900''>edge,</span>
  <span m=''1366870''>then</span> <span m=''1367050''>I''m going to glue</span> <span
  m=''1367390''>this</span> <span m=''1367600''>edge</span> <span m=''1367760''>to</span>
  <span m=''1367870''>this</span> <span m=''1368080''>edge,</span> <span m=''1368790''>then</span>
  <span m=''1368950''>this</span> <span m=''1369100''>one</span> <span m=''1369250''>to</span>
  <span m=''1369320''>this</span> <span m=''1369490''>one,</span> <span m=''1370180''>and</span>
  <span m=''1370580''>so</span> <span m=''1370780''>on.</span> <span m=''1371770''>So</span>
  <span m=''1371880''>just</span> <span m=''1372610''>do</span> <span m=''1372740''>that</span>
  <span m=''1372960''>gluing.</span> </p><p><span m=''1374550''>And</span> <span m=''1377610''>the</span>
  <span m=''1377720''>only</span> <span m=''1377940''>thing</span> <span m=''1378090''>to</span>
  <span m=''1378160''>worry</span> <span m=''1378390''>about</span> <span m=''1378660''>is</span>
  <span m=''1378820''>that</span> <span m=''1378890''>you</span> <span m=''1379000''>glue</span>
  <span m=''1379160''>two</span> <span m=''1379350''>betas</span> <span m=''1379720''>together.</span>
  <span m=''1380350''>That</span> <span m=''1380730''>would</span> <span m=''1380930''>be</span>
  <span m=''1381050''>more</span> <span m=''1381220''>than</span> <span m=''1381350''>360.</span>
  <span m=''1381940''>Anything</span> <span m=''1382360''>else,</span> <span m=''1382670''>beta</span>
  <span m=''1383230''>to</span> <span m=''1383360''>any</span> <span m=''1383530''>number</span>
  <span m=''1383770''>of</span> <span m=''1383840''>alpha''s</span> <span m=''1384320''>is</span>
  <span m=''1384500''>OK.</span> <span m=''1385680''>At</span> <span m=''1385840''>this</span>
  <span m=''1386000''>point</span> <span m=''1386190''>it is</span> <span m=''1386410''>really</span>
  <span m=''1386740''>helpful</span> <span m=''1387140''>to</span> <span m=''1387250''>draw</span>
  <span m=''1387570''>a</span> <span m=''1387640''>gluing</span> <span m=''1387980''>tree,</span>
  <span m=''1389344''>so</span> <span m=''1390120''>let</span> <span m=''1390330''>me</span>
  <span m=''1390430''>do</span> <span m=''1390560''>that.</span> </p><p><span m=''1405410''>So</span>
  <span m=''1405590''>gluing</span> <span m=''1407050''>tree</span> <span m=''1407340''>for</span>
  <span m=''1407490''>perimeter</span> <span m=''1407990''>halving</span> <span m=''1408780''>is</span>
  <span m=''1408990''>path.</span> <span m=''1410560''>And</span> <span m=''1412310''>do
  I</span> <span m=''1412460''>give</span> <span m=''1412610''>these</span> <span
  m=''1412790''>guys</span> <span m=''1413010''>names,</span> <span m=''1413320''>probably</span>
  <span m=''1413650''>x</span> <span m=''1413900''>and</span> <span m=''1414010''>y?</span>
  <span m=''1415224''>Yeah,</span> <span m=''1416040''>that''s</span> <span m=''1416180''>what</span>
  <span m=''1416300''>I would</span> <span m=''1416490''>call</span> <span m=''1416740''>them,</span>
  <span m=''1417110''>so naturally</span> <span m=''1417710''>that''s</span> <span
  m=''1417880''>what</span> <span m=''1417990''>I</span> <span m=''1418040''>called</span>
  <span m=''1418300''>them.</span> </p><p><span m=''1420580''>We</span> <span m=''1420660''>have</span>
  <span m=''1420820''>x</span> <span m=''1421140''>over</span> <span m=''1421330''>here,</span>
  <span m=''1422230''>we</span> <span m=''1422350''>have</span> <span m=''1422450''>y</span>
  <span m=''1422860''>over</span> <span m=''1423060''>here.</span> <span m=''1424350''>And</span>
  <span m=''1424370''>then</span> <span m=''1424460''>we</span> <span m=''1424540''>have</span>
  <span m=''1424800''>the</span> <span m=''1424910''>perimeter</span> <span m=''1425330''>in
  between.</span> <span m=''1426690''>So</span> <span m=''1426870''>let''s</span>
  <span m=''1427140''>just</span> <span m=''1427480''>check</span> <span m=''1427820''>what</span>
  <span m=''1428000''>happens.</span> <span m=''1428420''>Here</span> <span m=''1428620''>we</span>
  <span m=''1428740''>get</span> <span m=''1429560''>an</span> <span m=''1429740''>alpha</span>
  <span m=''1430120''>on</span> <span m=''1430420''>one</span> <span m=''1430650''>side--</span>
  <span m=''1431090''>I''m</span> <span m=''1431150''>going</span> <span m=''1431250''>to</span>
  <span m=''1431330''>say</span> <span m=''1431560''>the</span> <span m=''1431710''>right</span>
  <span m=''1431960''>side</span> <span m=''1432200''>is</span> <span m=''1432400''>the</span>
  <span m=''1432510''>bottom,</span> <span m=''1433430''>let''s</span> <span m=''1433710''>say.</span>
  <span m=''1435230''>I''m</span> <span m=''1435330''>not</span> <span m=''1435460''>going
  to</span> <span m=''1435660''>try</span> <span m=''1435850''>to</span> <span m=''1435900''>think</span>
  <span m=''1436080''>about</span> <span m=''1436320''>it.</span> </p><p><span m=''1436430''>So</span>
  <span m=''1436530''>there''s</span> <span m=''1436740''>an</span> <span m=''1436820''>alpha,</span>
  <span m=''1438310''>and</span> <span m=''1438440''>that</span> <span m=''1438650''>meets</span>
  <span m=''1438930''>a</span> <span m=''1439000''>beta.</span> <span m=''1440880''>And</span>
  <span m=''1441090''>then</span> <span m=''1441260''>it</span> <span m=''1441330''>just</span>
  <span m=''1441510''>alternates</span> <span m=''1441970''>from</span> <span m=''1442080''>there.</span>
  <span m=''1442320''>There''s</span> <span m=''1442490''>an</span> <span m=''1442580''>alpha,</span>
  <span m=''1443470''>it</span> <span m=''1443600''>meets</span> <span m=''1443790''>a</span>
  <span m=''1443870''>beta,</span> <span m=''1444370''>but</span> <span m=''1444590''>on</span>
  <span m=''1444690''>the</span> <span m=''1444810''>other</span> <span m=''1444950''>side.</span>
  <span m=''1445850''>And a</span> <span m=''1446000''>beta</span> <span m=''1447040''>meets</span>
  <span m=''1447200''>an</span> <span m=''1447430''>alpha</span> <span m=''1447800''>and</span>
  <span m=''1447980''>so</span> <span m=''1448140''>on.</span> <span m=''1449400''>At</span>
  <span m=''1449550''>the</span> <span m=''1449700''>end,</span> <span m=''1450040''>it''s</span>
  <span m=''1450190''>probably</span> <span m=''1451980''>the</span> <span m=''1452100''>reverse,</span>
  <span m=''1452375''>like</span> <span m=''1452650''>alpha,</span> <span m=''1453980''>beta.</span>
  <span m=''1454940''>I''ve</span> <span m=''1455120''>drawn</span> <span m=''1455330''>it</span>
  <span m=''1455420''>up</span> <span m=''1455570''>here</span> <span m=''1456240''>at</span>
  <span m=''1456380''>the</span> <span m=''1456450''>very</span> <span m=''1456680''>top.</span>
  </p><p><span m=''1459200''>The</span> <span m=''1459460''>alpha''s</span> <span
  m=''1459860''>red,</span> <span m=''1460770''>betas</span> <span m=''1461100''>are</span>
  <span m=''1461340''>black</span> <span m=''1462220''>so</span> <span m=''1462370''>you</span>
  <span m=''1462440''>can</span> <span m=''1462560''>distinguish</span> <span m=''1462990''>them.</span>
  <span m=''1463560''>But</span> <span m=''1463680''>that''s</span> <span m=''1464100''>clearly</span>
  <span m=''1464450''>an</span> <span m=''1464600''>OK</span> <span m=''1464940''>gluing</span>
  <span m=''1465380''>because</span> <span m=''1465570''>it''s</span> <span m=''1465670''>just</span>
  <span m=''1465880''>one</span> <span m=''1466060''>alpha</span> <span m=''1466340''>gluing</span>
  <span m=''1466620''>to</span> <span m=''1466730''>one</span> <span m=''1466890''>beta.</span>
  <span m=''1467180''>We</span> <span m=''1467270''>know</span> <span m=''1467470''>we</span>
  <span m=''1467590''>can glue</span> <span m=''1468020''>tons</span> <span m=''1468300''>of</span>
  <span m=''1468390''>alphas</span> <span m=''1468730''>into</span> <span m=''1468940''>one</span>
  <span m=''1469100''>beta.</span> <span m=''1471040''>That''s</span> <span m=''1471300''>one</span>
  <span m=''1471580''>gluing.</span> </p><p><span m=''1472370''>The</span> <span m=''1472480''>fun</span>
  <span m=''1472680''>part</span> <span m=''1472930''>is that</span> <span m=''1473190''>there
  are</span> <span m=''1473340''>exponentially</span> <span m=''1473930''>many</span>
  <span m=''1474220''>of</span> <span m=''1474280''>these</span> <span m=''1474460''>gluings</span>
  <span m=''1475610''>which</span> <span m=''1475850''>look</span> <span m=''1476020''>like</span>
  <span m=''1476210''>this,</span> <span m=''1477450''>where</span> <span m=''1477610''>you</span>
  <span m=''1477740''>take</span> <span m=''1478110''>some</span> <span m=''1478500''>of</span>
  <span m=''1478690''>the</span> <span m=''1479530''>betas</span> <span m=''1481070''>and</span>
  <span m=''1481370''>turn</span> <span m=''1481570''>them</span> <span m=''1481710''>into</span>
  <span m=''1481940''>leaves,</span> <span m=''1483080''>kind</span> <span m=''1483250''>of</span>
  <span m=''1483310''>squeeze</span> <span m=''1483740''>them</span> <span m=''1483910''>out.</span>
  <span m=''1485610''>And</span> <span m=''1486050''>the</span> <span m=''1486170''>result</span>
  <span m=''1486690''>is</span> <span m=''1487030''>that</span> <span m=''1487150''>you</span>
  <span m=''1487260''>get</span> <span m=''1487520''>two</span> <span m=''1487740''>alphas</span>
  <span m=''1488200''>gluing</span> <span m=''1488430''>to</span> <span m=''1488550''>a</span>
  <span m=''1488610''>beta,</span> <span m=''1489160''>which</span> <span m=''1489270''>is</span>
  <span m=''1489410''>fine.</span> <span m=''1490720''>The</span> <span m=''1490830''>beta</span>
  <span m=''1491120''>glues</span> <span m=''1491330''>to</span> <span m=''1491420''>itself,</span>
  <span m=''1491880''>which</span> <span m=''1492100''>is</span> <span m=''1492200''>fine.</span>
  <span m=''1492630''>I</span> <span m=''1492700''>mean,</span> <span m=''1492940''>it''s
  a</span> <span m=''1493050''>vertex.</span> </p><p><span m=''1494470''>It''s</span>
  <span m=''1495000''>comforting</span> <span m=''1496250''>that</span> <span m=''1496420''>it</span>
  <span m=''1496500''>has</span> <span m=''1496760''>an</span> <span m=''1496900''>angle</span>
  <span m=''1497210''>almost</span> <span m=''1497590''>360.</span> <span m=''1498060''>Therefore,</span>
  <span m=''1498340''>there''s</span> <span m=''1498500''>very</span> <span m=''1498780''>little</span>
  <span m=''1499000''>curvature</span> <span m=''1499530''>out</span> <span m=''1499740''>at</span>
  <span m=''1499830''>that</span> <span m=''1500020''>leaf,</span> <span m=''1500800''>but</span>
  <span m=''1500940''>we</span> <span m=''1501030''>don''t</span> <span m=''1501250''>really</span>
  <span m=''1501520''>need</span> <span m=''1501710''>to</span> <span m=''1501790''>check</span>
  <span m=''1502040''>that.</span> <span m=''1502670''>It</span> <span m=''1502890''>is</span>
  <span m=''1503240''>just</span> <span m=''1503440''>necessary</span> <span m=''1503840''>for</span>
  <span m=''1503950''>this</span> <span m=''1504130''>to</span> <span m=''1504220''>work.</span>
  <span m=''1506060''>Of</span> <span m=''1506220''>course,</span> <span m=''1506460''>beta
  is</span> <span m=''1506790''>less than</span> <span m=''1507080''>360</span> <span
  m=''1507530''>by</span> <span m=''1507710''>itself.</span> </p><p><span m=''1510560''>Here''s</span>
  <span m=''1510800''>an</span> <span m=''1510850''>example</span> <span m=''1511310''>where</span>
  <span m=''1511500''>I</span> <span m=''1511590''>squeezed</span> <span m=''1512070''>two</span>
  <span m=''1512300''>of the</span> <span m=''1512420''>betas</span> <span m=''1512720''>right</span>
  <span m=''1512990''>next</span> <span m=''1513230''>to</span> <span m=''1513320''>each</span>
  <span m=''1513480''>other,</span> <span m=''1514140''>then</span> <span m=''1514310''>three</span>
  <span m=''1514580''>alpha''s</span> <span m=''1515270''>come</span> <span m=''1515490''>together</span>
  <span m=''1516230''>and</span> <span m=''1516440''>glue</span> <span m=''1516580''>to</span>
  <span m=''1516680''>a</span> <span m=''1516740''>beta.</span> <span m=''1518130''>But</span>
  <span m=''1518630''>what''s</span> <span m=''1518890''>nice</span> <span m=''1519260''>is</span>
  <span m=''1519390''>we</span> <span m=''1519490''>don''t</span> <span m=''1519680''>have</span>
  <span m=''1519820''>to</span> <span m=''1519930''>think</span> <span m=''1520120''>about</span>
  <span m=''1520350''>the</span> <span m=''1520400''>polygon.</span> <span m=''1521480''>We</span>
  <span m=''1521630''>just</span> <span m=''1521940''>think</span> <span m=''1522130''>about</span>
  <span m=''1522350''>the</span> <span m=''1522420''>gluing</span> <span m=''1522740''>tree.</span>
  <span m=''1523020''>And we say,</span> <span m=''1523220''>well</span> <span m=''1523980''>if</span>
  <span m=''1524170''>I</span> <span m=''1524330''>pull</span> <span m=''1525530''>this</span>
  <span m=''1526420''>down--</span> <span m=''1528100''>so</span> <span m=''1528450''>I</span>
  <span m=''1528630''>end</span> <span m=''1528880''>up</span> <span m=''1529070''>with</span>
  <span m=''1530240''>that--</span> <span m=''1531290''>that''s</span> <span m=''1531410''>going</span>
  <span m=''1531530''>to</span> <span m=''1531590''>be</span> <span m=''1531700''>just</span>
  <span m=''1531980''>fine</span> <span m=''1532250''>as</span> <span m=''1532360''>long</span>
  <span m=''1532590''>as</span> <span m=''1532710''>I</span> <span m=''1532860''>also</span>
  <span m=''1533230''>pull</span> <span m=''1533470''>one</span> <span m=''1533650''>on</span>
  <span m=''1533750''>the</span> <span m=''1533850''>top.</span> </p><p><span m=''1534550''>I</span>
  <span m=''1534660''>have</span> <span m=''1534920''>to</span> <span m=''1535610''>squeeze</span>
  <span m=''1536140''>the</span> <span m=''1536230''>same</span> <span m=''1536560''>number
  of</span> <span m=''1536820''>betas</span> <span m=''1537140''>on</span> <span m=''1537210''>the</span>
  <span m=''1537310''>top</span> <span m=''1537540''>and the</span> <span m=''1537680''>bottom,</span>
  <span m=''1537980''>otherwise</span> <span m=''1538400''>these</span> <span m=''1538560''>links</span>
  <span m=''1538810''>won''t</span> <span m=''1538980''>match</span> <span m=''1539250''>up.</span>
  <span m=''1539820''>As</span> <span m=''1539970''>long</span> <span m=''1540280''>as</span>
  <span m=''1540410''>I</span> <span m=''1540480''>do</span> <span m=''1540630''>that,</span>
  <span m=''1541210''>I</span> <span m=''1541320''>get</span> <span m=''1541480''>a</span>
  <span m=''1541520''>valid</span> <span m=''1541860''>gluing.</span> <span m=''1543690''>So</span>
  <span m=''1543790''>what</span> <span m=''1543950''>I''m</span> <span m=''1544020''>going</span>
  <span m=''1544150''>to</span> <span m=''1544240''>do,</span> <span m=''1545130''>I</span>
  <span m=''1545260''>have</span> <span m=''1546860''>n</span> <span m=''1547500''>betas</span>
  <span m=''1548450''>total.</span> <span m=''1549990''>So</span> <span m=''1550140''>I</span>
  <span m=''1550240''>have</span> <span m=''1550650''>n</span> <span m=''1550860''>over</span>
  <span m=''1551080''>2</span> <span m=''1552480''>betas</span> <span m=''1553940''>on</span>
  <span m=''1554110''>the</span> <span m=''1554190''>top</span> <span m=''1555300''>and</span>
  <span m=''1555720''>n</span> <span m=''1555880''>over</span> <span m=''1556040''>2</span>
  <span m=''1556230''>betas</span> <span m=''1556580''>on</span> <span m=''1556690''>the</span>
  <span m=''1556760''>bottom.</span> <span m=''1559650''>I''m</span> <span m=''1559830''>going</span>
  <span m=''1560060''>to</span> <span m=''1560160''>squeeze</span> <span m=''1563770''>n</span>
  <span m=''1563960''>over</span> <span m=''1564150''>4</span> <span m=''1565480''>on</span>
  <span m=''1565630''>the</span> <span m=''1565720''>top</span> <span m=''1567220''>and</span>
  <span m=''1567440''>n</span> <span m=''1567610''>over</span> <span m=''1567790''>4</span>
  <span m=''1568020''>on</span> <span m=''1568110''>the</span> <span m=''1568180''>bottom,</span>
  <span m=''1569640''>so</span> <span m=''1569830''>half</span> <span m=''1570120''>of</span>
  <span m=''1570240''>them.</span> </p><p><span m=''1576160''>That</span> <span m=''1576350''>way</span>
  <span m=''1576780''>the</span> <span m=''1576880''>lengths</span> <span m=''1577140''>will</span>
  <span m=''1577240''>match</span> <span m=''1577530''>up,</span> <span m=''1578520''>and</span>
  <span m=''1579190''>I</span> <span m=''1579770''>happen</span> <span m=''1580160''>to</span>
  <span m=''1580270''>know</span> <span m=''1580460''>there''s</span> <span m=''1580620''>a</span>
  <span m=''1580670''>lot</span> <span m=''1580860''>of</span> <span m=''1580910''>ways</span>
  <span m=''1581130''>to</span> <span m=''1581230''>do</span> <span m=''1581350''>this.</span>
  <span m=''1582130''>The</span> <span m=''1582500''>actual</span> <span m=''1582890''>number</span>
  <span m=''1583320''>is</span> <span m=''1583600''>n</span> <span m=''1583780''>over</span>
  <span m=''1584000''>2</span> <span m=''1584810''>choose</span> <span m=''1585160''>n</span>
  <span m=''1585350''>over</span> <span m=''1585580''>4</span> <span m=''1586560''>for</span>
  <span m=''1587050''>the</span> <span m=''1587170''>top</span> <span m=''1587620''>and</span>
  <span m=''1587770''>the</span> <span m=''1587850''>same</span> <span m=''1588170''>for</span>
  <span m=''1588260''>the</span> <span m=''1588360''>bottom.</span> <span m=''1588950''>So</span>
  <span m=''1589060''>it''s</span> <span m=''1589200''>this</span> <span m=''1589320''>squared,</span>
  <span m=''1591150''>and</span> <span m=''1591510''>I''m</span> <span m=''1591580''>just</span>
  <span m=''1591760''>going</span> <span m=''1591880''>to</span> <span m=''1591960''>tell</span>
  <span m=''1592170''>you</span> <span m=''1592530''>that</span> <span m=''1592760''>is</span>
  <span m=''1592950''>2</span> <span m=''1593140''>to</span> <span m=''1593220''>the</span>
  <span m=''1593480''>theta</span> <span m=''1593660''>n.</span> </p><p><span m=''1597140''>Actually,</span>
  <span m=''1598470''>I</span> <span m=''1598560''>think</span> <span m=''1598720''>you</span>
  <span m=''1598840''>can</span> <span m=''1598980''>be</span> <span m=''1599140''>pretty</span>
  <span m=''1599420''>precise.</span> <span m=''1602090''>Can</span> <span m=''1602260''>you?</span>
  <span m=''1603150''>I''ve</span> <span m=''1603260''>forgotten.</span> </p><p><span
  m=''1604510''>Isn''t</span> <span m=''1606470''>n</span> <span m=''1606670''>choose</span>
  <span m=''1606980''>n</span> <span m=''1607130''>over</span> <span m=''1607310''>2--</span>
  <span m=''1608400''>it''s</span> <span m=''1608550''>very</span> <span m=''1608740''>close</span>
  <span m=''1609180''>to</span> <span m=''1610000''>2</span> <span m=''1610410''>to
  the</span> <span m=''1610860''>n</span> <span m=''1610970''>over</span> <span m=''1611150''>2,</span>
  <span m=''1611460''>I</span> <span m=''1611520''>believe.</span> <span m=''1613104''>Is</span>
  <span m=''1613512''>that</span> <span m=''1613920''>right?</span> <span m=''1615660''>But</span>
  <span m=''1615810''>not</span> <span m=''1616020''>exactly,</span> <span m=''1616960''>yeah.</span>
  </p><p><span m=''1618010''>All right, I''m</span> <span m=''1618160''>going</span>
  <span m=''1618260''>to</span> <span m=''1618320''>be</span> <span m=''1618430''>sloppy.</span>
  <span m=''1620181''>It''s</span> <span m=''1620610''>2</span> <span m=''1620930''>to
  the theta</span> <span m=''1621220''>n.</span> <span m=''1621760''>You</span> <span
  m=''1621920''>could</span> <span m=''1622080''>figure</span> <span m=''1622320''>out</span>
  <span m=''1622390''>what</span> <span m=''1622500''>the</span> <span m=''1622590''>constant</span>
  <span m=''1622970''>is</span> <span m=''1623130''>there.</span> <span m=''1623860''>I</span>
  <span m=''1623880''>think</span> <span m=''1624060''>I</span> <span m=''1624110''>have</span>
  <span m=''1624710''>a</span> <span m=''1625700''>bound</span> <span m=''1626020''>written</span>
  <span m=''1626280''>down,</span> <span m=''1626610''>maybe.</span> <span m=''1629450''>Oh,
  it</span> <span m=''1629590''>is</span> <span m=''1629880''>the</span> <span m=''1629950''>power</span>
  <span m=''1630270''>of 2,</span> <span m=''1630680''>yeah.</span> <span m=''1631980''>It</span>
  <span m=''1632090''>is</span> <span m=''1632470''>equal,</span> <span m=''1632820''>I
  believe,</span> <span m=''1633910''>according</span> <span m=''1634200''>to</span>
  <span m=''1634290''>my</span> <span m=''1634400''>notes.</span> </p><p><span m=''1637990''>So</span>
  <span m=''1638210''>this</span> <span m=''1638390''>is</span> <span m=''1638520''>going</span>
  <span m=''1638670''>to</span> <span m=''1638740''>be</span> <span m=''1640130''>2</span>
  <span m=''1640690''>to</span> <span m=''1640790''>the</span> <span m=''1641120''>n</span>
  <span m=''1641470''>over</span> <span m=''1641770''>4</span> <span m=''1642100''>squared,</span>
  <span m=''1642690''>which</span> <span m=''1642780''>is</span> <span m=''1642900''>2
  to</span> <span m=''1643120''>the</span> <span m=''1643210''>n</span> <span m=''1643380''>over</span>
  <span m=''1643560''>2</span> <span m=''1645160''>exactly.</span> <span m=''1650250''>Yeah?</span>
  </p><p><span m=''1651260''>AUDIENCE: [INAUDIBLE]?</span> </p><p><span m=''1657260''>PROFESSOR:
  I</span> <span m=''1657500''>only</span> <span m=''1657850''>am</span> <span m=''1657960''>allowed</span>
  <span m=''1658210''>to</span> <span m=''1658270''>squeeze</span> <span m=''1658550''>betas,</span>
  <span m=''1658950''>not</span> <span m=''1659110''>alphas.</span> <span m=''1659930''>But</span>
  <span m=''1660100''>I</span> <span m=''1660170''>can</span> <span m=''1660390''>do</span>
  <span m=''1660640''>whatever</span> <span m=''1661000''>pattern</span> <span m=''1661340''>I</span>
  <span m=''1661370''>want</span> <span m=''1661570''>on</span> <span m=''1661650''>the</span>
  <span m=''1661740''>top</span> <span m=''1662050''>and</span> <span m=''1662190''>separately</span>
  <span m=''1662650''>any</span> <span m=''1662850''>pattern</span> <span m=''1663180''>I</span>
  <span m=''1663230''>want</span> <span m=''1663430''>on</span> <span m=''1663500''>the</span>
  <span m=''1663570''>bottom.</span> <span m=''1665150''>Because</span> <span m=''1665860''>what''s</span>
  <span m=''1666240''>key</span> <span m=''1666450''>is</span> <span m=''1666560''>by</span>
  <span m=''1666690''>squeezing</span> <span m=''1667100''>betas</span> <span m=''1667450''>I</span>
  <span m=''1667540''>preserve</span> <span m=''1668070''>the</span> <span m=''1668160''>parity,</span>
  <span m=''1669050''>because</span> <span m=''1670450''>when</span> <span m=''1670610''>I</span>
  <span m=''1670650''>squeeze</span> <span m=''1671000''>away</span> <span m=''1671350''>a</span>
  <span m=''1671440''>beta</span> <span m=''1671880''>I</span> <span m=''1671980''>bring</span>
  <span m=''1672190''>two</span> <span m=''1672340''>alphas</span> <span m=''1672690''>together.</span>
  <span m=''1673280''>So</span> <span m=''1673440''>the</span> <span m=''1673550''>parity</span>
  <span m=''1674180''>and</span> <span m=''1674450''>who''s</span> <span m=''1674730''>matching</span>
  <span m=''1675160''>whom</span> <span m=''1675410''>on</span> <span m=''1675490''>the</span>
  <span m=''1675570''>top</span> <span m=''1675820''>and the</span> <span m=''1675940''>bottom</span>
  <span m=''1676320''>is always</span> <span m=''1676500''>the</span> <span m=''1676570''>same.</span>
  <span m=''1676880''>And the</span> <span m=''1677200''>beta</span> <span m=''1677460''>on</span>
  <span m=''1677550''>the</span> <span m=''1677630''>top</span> <span m=''1677880''>will</span>
  <span m=''1678000''>always</span> <span m=''1678220''>be</span> <span m=''1678360''>matching</span>
  <span m=''1678800''>some</span> <span m=''1679070''>number</span> <span m=''1679300''>of</span>
  <span m=''1679370''>alpha''s</span> <span m=''1679690''>on</span> <span m=''1679780''>the</span>
  <span m=''1679860''>bottom,</span> <span m=''1680270''>and</span> <span m=''1680380''>vice</span>
  <span m=''1680640''>versa.</span> </p><p><span m=''1681930''>So</span> <span m=''1681940''>it</span>
  <span m=''1682000''>doesn''t</span> <span m=''1682250''>matter</span> <span m=''1682840''>what</span>
  <span m=''1683090''>pattern</span> <span m=''1683390''>I</span> <span m=''1683440''>do
  on</span> <span m=''1683610''>the</span> <span m=''1683710''>top,</span> <span m=''1683970''>or</span>
  <span m=''1684120''>what</span> <span m=''1684300''>pattern</span> <span m=''1684510''>I</span>
  <span m=''1684620''>do</span> <span m=''1684760''>on</span> <span m=''1684840''>the</span>
  <span m=''1684910''>bottom.</span> <span m=''1685360''>It just</span> <span m=''1685760''>matters</span>
  <span m=''1686080''>they have</span> <span m=''1686200''>the</span> <span m=''1686270''>same</span>
  <span m=''1686530''>length,</span> <span m=''1686830''>so</span> <span m=''1687000''>I</span>
  <span m=''1687160''>arbitrarily</span> <span m=''1687730''>chose</span> <span m=''1688040''>them</span>
  <span m=''1688260''>to</span> <span m=''1688400''>both</span> <span m=''1688710''>be</span>
  <span m=''1689390''>n</span> <span m=''1689520''>over</span> <span m=''1689690''>4.</span>
  <span m=''1690100''>Well, it</span> <span m=''1690250''>wasn''t</span> <span m=''1690480''>arbitrary,</span>
  <span m=''1691090''>but</span> <span m=''1691210''>I</span> <span m=''1691290''>chose</span>
  <span m=''1691570''>it</span> <span m=''1691700''>to</span> <span m=''1691790''>be</span>
  <span m=''1691920''>that</span> <span m=''1692200''>because</span> <span m=''1692480''>I</span>
  <span m=''1692530''>knew</span> <span m=''1692650''>there</span> <span m=''1692790''>would
  be</span> <span m=''1692900''>a</span> <span m=''1692960''>lot</span> <span m=''1693240''>of</span>
  <span m=''1693380''>those</span> <span m=''1693550''>choices.</span> </p><p><span
  m=''1693960''>There</span> <span m=''1694080''>are</span> <span m=''1694120''>more,</span>
  <span m=''1694460''>of</span> <span m=''1694540''>course.</span> <span m=''1694830''>Really</span>
  <span m=''1695130''>I</span> <span m=''1695190''>should</span> <span m=''1695400''>sum</span>
  <span m=''1695690''>this</span> <span m=''1696450''>over</span> <span m=''1696690''>all</span>
  <span m=''1696810''>choices</span> <span m=''1697220''>of</span> <span m=''1697310''>n</span>
  <span m=''1697430''>over</span> <span m=''1697630''>4,</span> <span m=''1698680''>but</span>
  <span m=''1699300''>this</span> <span m=''1699580''>is</span> <span m=''1699880''>good</span>
  <span m=''1700020''>enough.</span> <span m=''1701470''>That</span> <span m=''1701680''>summation</span>
  <span m=''1702080''>would</span> <span m=''1702190''>not</span> <span m=''1702350''>improve</span>
  <span m=''1702640''>the</span> <span m=''1702720''>bound</span> <span m=''1702970''>by</span>
  <span m=''1703070''>much.</span> </p><p><span m=''1710870''>So</span> <span m=''1711000''>that''s</span>
  <span m=''1711190''>sort</span> <span m=''1711330''>of</span> <span m=''1711410''>the</span>
  <span m=''1711490''>bad</span> <span m=''1711810''>news.</span> <span m=''1712340''>These</span>
  <span m=''1712590''>are</span> <span m=''1712780''>really</span> <span m=''1713000''>nasty</span>
  <span m=''1713430''>polygons.</span> <span m=''1713910''>They have</span> <span
  m=''1714110''>exponentially</span> <span m=''1714720''>many</span> <span m=''1714910''>gluings.</span>
  <span m=''1715960''>For</span> <span m=''1716130''>fun,</span> <span m=''1716490''>we</span>
  <span m=''1716650''>actually</span> <span m=''1717410''>did</span> <span m=''1717700''>this</span>
  <span m=''1720300''>for</span> <span m=''1720540''>small</span> <span m=''1720940''>n.</span>
  <span m=''1723640''>It''s</span> <span m=''1723760''>been</span> <span m=''1723890''>a</span>
  <span m=''1724165''>while.</span> <span m=''1725230''>This</span> <span m=''1725800''>was</span>
  <span m=''1726340''>some</span> <span m=''1726520''>time</span> <span m=''1726770''>ago</span>
  <span m=''1727010''>that</span> <span m=''1727110''>we</span> <span m=''1727230''>made</span>
  <span m=''1727460''>all</span> <span m=''1727680''>these.</span> <span m=''1728440''>I
  think it</span> <span m=''1728670''>actually</span> <span m=''1729060''>was</span>
  <span m=''1729260''>before</span> <span m=''1729600''>2002,</span> <span m=''1730260''>but</span>
  <span m=''1730440''>that</span> <span m=''1730640''>was</span> <span m=''1730820''>when</span>
  <span m=''1731040''>the</span> <span m=''1731130''>paper</span> <span m=''1731460''>appeared.</span>
  </p><p><span m=''1732980''>So</span> <span m=''1733220''>here</span> <span m=''1733640''>is</span>
  <span m=''1733990''>a</span> <span m=''1734050''>four</span> <span m=''1734380''>star,</span>
  <span m=''1735850''>and</span> <span m=''1736110''>these</span> <span m=''1736390''>are</span>
  <span m=''1737670''>I</span> <span m=''1737760''>think</span> <span m=''1737980''>all</span>
  <span m=''1738330''>of the</span> <span m=''1738420''>possible</span> <span m=''1739130''>gluings.</span>
  <span m=''1739430''>Maybe</span> <span m=''1739670''>just</span> <span m=''1739840''>some</span>
  <span m=''1740040''>of</span> <span m=''1740110''>them,</span> <span m=''1741100''>it''s</span>
  <span m=''1741200''>been</span> <span m=''1741340''>awhile,</span> <span m=''1741650''>I</span>
  <span m=''1741960''>could</span> <span m=''1742110''>think</span> <span m=''1742260''>about</span>
  <span m=''1742560''>it.</span> <span m=''1745850''>Not</span> <span m=''1746100''>drawn</span>
  <span m=''1746320''>as</span> <span m=''1746440''>gluing</span> <span m=''1746690''>trees</span>
  <span m=''1746860''>here,</span> <span m=''1747000''>but drawn</span> <span m=''1747430''>as</span>
  <span m=''1747550''>actual</span> <span m=''1747940''>gulings</span> <span m=''1748280''>on</span>
  <span m=''1748350''>the</span> <span m=''1748430''>polygon.</span> <span m=''1748880''>Here</span>
  <span m=''1749690''>instead</span> <span m=''1750070''>of</span> <span m=''1750150''>drawing</span>
  <span m=''1750430''>the gluings</span> <span m=''1750820''>on</span> <span m=''1750910''>the</span>
  <span m=''1751020''>outside,</span> <span m=''1752260''>which</span> <span m=''1752550''>is</span>
  <span m=''1752680''>how</span> <span m=''1752820''>they</span> <span m=''1752900''>happen</span>
  <span m=''1753280''>in the</span> <span m=''1753360''>gluing</span> <span m=''1753500''>three,</span>
  <span m=''1753870''>I''ve</span> <span m=''1753970''>drawn them</span> <span m=''1754030''>on
  the</span> <span m=''1754260''>inside,</span> <span m=''1754610''>just</span> <span
  m=''1754750''>because</span> <span m=''1754870''>it''s</span> <span m=''1755020''>easier</span>
  <span m=''1755300''>to</span> <span m=''1755390''>draw.</span> </p><p><span m=''1756870''>And</span>
  <span m=''1757020''>then</span> <span m=''1757200''>we</span> <span m=''1757590''>built</span>
  <span m=''1757850''>them</span> <span m=''1758050''>in</span> <span m=''1758120''>the</span>
  <span m=''1758200''>same</span> <span m=''1758440''>way</span> <span m=''1758530''>that
  I</span> <span m=''1758770''>built</span> <span m=''1758970''>one</span> <span m=''1759450''>like</span>
  <span m=''1759640''>I</span> <span m=''1759660''>showed</span> <span m=''1759860''>you</span>
  <span m=''1759960''>last</span> <span m=''1760210''>time,</span> <span m=''1760390''>where</span>
  <span m=''1760520''>we</span> <span m=''1760620''>just</span> <span m=''1760840''>took</span>
  <span m=''1761010''>a</span> <span m=''1761060''>polygon,</span> <span m=''1761900''>started</span>
  <span m=''1762670''>taping</span> <span m=''1763120''>edges</span> <span m=''1763380''>together,</span>
  <span m=''1764030''>and</span> <span m=''1764240''>these</span> <span m=''1764490''>are</span>
  <span m=''1764600''>the</span> <span m=''1764870''>roughly</span> <span m=''1765280''>taped</span>
  <span m=''1766210''>versions.</span> <span m=''1767740''>And</span> <span m=''1768220''>then</span>
  <span m=''1768450''>you</span> <span m=''1768880''>guess</span> <span m=''1769320''>where</span>
  <span m=''1769610''>the</span> <span m=''1769970''>crease</span> <span m=''1770200''>signs</span>
  <span m=''1770490''>are,</span> <span m=''1770680''>and</span> <span m=''1770750''>then</span>
  <span m=''1770850''>you</span> <span m=''1770960''>can</span> <span m=''1771090''>draw</span>
  <span m=''1771250''>the</span> <span m=''1771360''>crease</span> <span m=''1771510''>lines</span>
  <span m=''1771780''>on</span> <span m=''1771880''>here.</span> <span m=''1772080''>And</span>
  <span m=''1772180''>two</span> <span m=''1772350''>of</span> <span m=''1772410''>them</span>
  <span m=''1772580''>are</span> <span m=''1772700''>drawn</span> <span m=''1773980''>sort</span>
  <span m=''1774200''>of</span> <span m=''1774280''>worked</span> <span m=''1774600''>out</span>
  <span m=''1774800''>where</span> <span m=''1775000''>exactly</span> <span m=''1775400''>the</span>
  <span m=''1775510''>crease lines</span> <span m=''1775890''>have</span> <span m=''1776070''>to</span>
  <span m=''1776170''>be,</span> <span m=''1776350''>according</span> <span m=''1776700''>to</span>
  <span m=''1776960''>getting</span> <span m=''1777170''>all</span> <span m=''1777300''>the</span>
  <span m=''1777360''>edge</span> <span m=''1777590''>links</span> <span m=''1777810''>to</span>
  <span m=''1777900''>match.</span> </p><p><span m=''1780030''>And</span> <span m=''1780210''>then</span>
  <span m=''1780400''>you</span> <span m=''1780600''>can</span> <span m=''1780790''>make</span>
  <span m=''1781060''>your</span> <span m=''1781160''>polygons.</span> <span m=''1781600''>That
  is</span> <span m=''1781930''>n</span> <span m=''1782060''>equals</span> <span m=''1782310''>4,</span>
  <span m=''1783370''>then</span> <span m=''1783590''>we</span> <span m=''1783720''>did</span>
  <span m=''1784160''>n</span> <span m=''1784320''>equals</span> <span m=''1785800''>8.</span>
  <span m=''1787130''>I</span> <span m=''1787190''>guess</span> <span m=''1787370''>we</span>
  <span m=''1787440''>want</span> <span m=''1787620''>n</span> <span m=''1787790''>to</span>
  <span m=''1787860''>be</span> <span m=''1788070''>even</span> <span m=''1788300''>here</span>
  <span m=''1788530''>for</span> <span m=''1788770''>convenience.</span> </p><p><span
  m=''1791750''>And</span> <span m=''1792150''>there''s</span> <span m=''1792430''>more,</span>
  <span m=''1793180''>although</span> <span m=''1793390''>still</span> <span m=''1793600''>not</span>
  <span m=''1794020''>a</span> <span m=''1794040''>huge</span> <span m=''1794440''>number.</span>
  <span m=''1794740''>I</span> <span m=''1794800''>think</span> <span m=''1796990''>these</span>
  <span m=''1797150''>are</span> <span m=''1797180''>the</span> <span m=''1797470''>top</span>
  <span m=''1797740''>sides</span> <span m=''1798070''>and</span> <span m=''1798160''>these</span>
  <span m=''1798320''>are</span> <span m=''1798370''>the</span> <span m=''1798480''>bottom</span>
  <span m=''1798780''>sides.</span> <span m=''1801410''>And</span> <span m=''1801950''>you</span>
  <span m=''1802190''>can</span> <span m=''1802330''>see,</span> <span m=''1802720''>in</span>
  <span m=''1802830''>some</span> <span m=''1803050''>cases</span> <span m=''1803470''>it</span>
  <span m=''1803570''>was</span> <span m=''1803720''>a</span> <span m=''1803780''>little</span>
  <span m=''1804000''>tricky</span> <span m=''1804310''>to</span> <span m=''1804430''>tell</span>
  <span m=''1804610''>where</span> <span m=''1804710''>the</span> <span m=''1804810''>creases</span>
  <span m=''1805180''>are,</span> <span m=''1805300''>because</span> <span m=''1805500''>they
  were</span> <span m=''1805700''>almost</span> <span m=''1806060''>flat</span> <span
  m=''1806440''>or</span> <span m=''1806530''>possibly</span> <span m=''1807000''>actually</span>
  <span m=''1807330''>exactly</span> <span m=''1807770''>flat.</span> <span m=''1808130''>Like</span>
  <span m=''1808320''>here</span> <span m=''1808430''>they</span> <span m=''1808610''>are</span>
  <span m=''1808760''>flat.</span> </p><p><span m=''1810060''>But</span> <span m=''1810880''>it''s</span>
  <span m=''1811040''>a</span> <span m=''1811080''>fun</span> <span m=''1811280''>exercise.</span>
  <span m=''1811540''>You</span> <span m=''1811800''>can,</span> <span m=''1812880''>whenever</span>
  <span m=''1813150''>you</span> <span m=''1813260''>have</span> <span m=''1813460''>these</span>
  <span m=''1813620''>gluings,</span> <span m=''1814130''>reconstruct</span> <span
  m=''1814720''>the</span> <span m=''1814750''>polyhedra.</span> <span m=''1815180''>Of</span>
  <span m=''1815310''>course</span> <span m=''1815530''>now</span> <span m=''1816560''>that</span>
  <span m=''1816670''>we</span> <span m=''1816770''>have</span> <span m=''1816960''>algorithms</span>
  <span m=''1817370''>for</span> <span m=''1817560''>Alexandroff''s</span> <span m=''1818180''>theorem,</span>
  <span m=''1818290''>we</span> <span m=''1818390''>could</span> <span m=''1818530''>try</span>
  <span m=''1818680''>plugging</span> <span m=''1819020''>these</span> <span m=''1819200''>into</span>
  <span m=''1819410''>the</span> <span m=''1819550''>programs</span> <span m=''1821230''>and</span>
  <span m=''1821640''>they</span> <span m=''1821780''>should</span> <span m=''1822010''>give</span>
  <span m=''1822180''>us</span> <span m=''1823400''>exact</span> <span m=''1823890''>3D</span>
  <span m=''1824140''>polyhedra,</span> <span m=''1824680''>from</span> <span m=''1824900''>which</span>
  <span m=''1825120''>we</span> <span m=''1825330''>could</span> <span m=''1826290''>figure</span>
  <span m=''1826600''>out where</span> <span m=''1826740''>the crease</span> <span
  m=''1827020''>lines</span> <span m=''1827240''>are.</span> <span m=''1829252''>It
  would</span> <span m=''1829700''>be</span> <span m=''1829820''>a</span> <span m=''1829870''>fun,</span>
  <span m=''1830800''>small,</span> <span m=''1831420''>mini-project,</span> <span
  m=''1832250''>I</span> <span m=''1832330''>guess,</span> <span m=''1832640''>to</span>
  <span m=''1832770''>do</span> <span m=''1832880''>that.</span> <span m=''1833290''>This</span>
  <span m=''1833440''>is</span> <span m=''1833550''>all</span> <span m=''1833700''>from</span>
  <span m=''1834360''>ages</span> <span m=''1834650''>ago.</span> </p><p><span m=''1837800''>At</span>
  <span m=''1838020''>this</span> <span m=''1838210''>point</span> <span m=''1838570''>I</span>
  <span m=''1838670''>want</span> <span m=''1839020''>to</span> <span m=''1840150''>move</span>
  <span m=''1840470''>on</span> <span m=''1840960''>to</span> <span m=''1842590''>this</span>
  <span m=''1842840''>result,</span> <span m=''1843800''>which</span> <span m=''1844140''>is</span>
  <span m=''1844280''>the</span> <span m=''1844380''>good</span> <span m=''1844600''>news.</span>
  <span m=''1844910''>This is</span> <span m=''1845010''>sort</span> <span m=''1845260''>of</span>
  <span m=''1845350''>bad</span> <span m=''1845600''>news</span> <span m=''1845810''>that</span>
  <span m=''1845910''>there</span> <span m=''1846040''>are</span> <span m=''1846160''>exponentially</span>
  <span m=''1846690''>many</span> <span m=''1847520''>different</span> <span m=''1847990''>gluings.</span>
  <span m=''1849910''>It''s</span> <span m=''1850110''>not</span> <span m=''1850280''>so</span>
  <span m=''1850500''>bad</span> <span m=''1851010''>in</span> <span m=''1851410''>that
  at</span> <span m=''1851640''>least</span> <span m=''1851880''>we</span> <span m=''1852000''>can</span>
  <span m=''1852120''>enumerate</span> <span m=''1852550''>them</span> <span m=''1852690''>in</span>
  <span m=''1852750''>the</span> <span m=''1852820''>same</span> <span m=''1853060''>amount</span>
  <span m=''1853250''>of</span> <span m=''1853330''>time.</span> <span m=''1853550''>We''ll</span>
  <span m=''1853650''>get</span> <span m=''1853800''>to</span> <span m=''1853870''>that</span>
  <span m=''1854050''>later.</span> </p><p><span m=''1855110''>While</span> <span
  m=''1855330''>we''re</span> <span m=''1855460''>in</span> <span m=''1855510''>the</span>
  <span m=''1855610''>combinatorial</span> <span m=''1856270''>streak,</span> <span
  m=''1856600''>I</span> <span m=''1856690''>want</span> <span m=''1856850''>to</span>
  <span m=''1856910''>prove</span> <span m=''1857220''>that</span> <span m=''1857350''>there''s</span>
  <span m=''1857580''>only</span> <span m=''1858380''>a</span> <span m=''1858450''>polynomial</span>
  <span m=''1859140''>number</span> <span m=''1859540''>of</span> <span m=''1860210''>combinatorially</span>
  <span m=''1860790''>distinct</span> <span m=''1861180''>gluings</span> <span m=''1861490''>for</span>
  <span m=''1861820''>bounded</span> <span m=''1862230''>sharpness</span> <span m=''1862690''>polygons.</span>
  <span m=''1864250''>So</span> <span m=''1864360''>of</span> <span m=''1864440''>course,</span>
  <span m=''1864740''>this</span> <span m=''1865850''>star</span> <span m=''1866190''>polygon</span>
  <span m=''1866670''>does</span> <span m=''1866840''>not</span> <span m=''1867050''>have</span>
  <span m=''1867220''>bounded</span> <span m=''1867540''>sharpness.</span> <span m=''1868510''>We</span>
  <span m=''1868640''>set</span> <span m=''1869330''>beta</span> <span m=''1869720''>to</span>
  <span m=''1869830''>be</span> <span m=''1869960''>very,</span> <span m=''1870440''>very</span>
  <span m=''1870610''>close</span> <span m=''1871100''>to</span> <span m=''1871660''>360.</span>
  </p><p><span m=''1874160''>It</span> <span m=''1874230''>may</span> <span m=''1874390''>be</span>
  <span m=''1874510''>worth</span> <span m=''1875720''>talking</span> <span m=''1876020''>about</span>
  <span m=''1876180''>this</span> <span m=''1876320''>a</span> <span m=''1876360''>little</span>
  <span m=''1876620''>bit,</span> <span m=''1876830''>because</span> <span m=''1877080''>it</span>
  <span m=''1877160''>wasn''t</span> <span m=''1877490''>exactly</span> <span m=''1878140''>360.</span>
  <span m=''1881020''>It</span> <span m=''1881150''>was</span> <span m=''1881370''>bounded</span>
  <span m=''1881690''>away</span> <span m=''1881920''>from</span> <span m=''1882100''>360</span>
  <span m=''1882590''>by</span> <span m=''1882760''>this</span> <span m=''1882960''>value</span>
  <span m=''1883230''>of</span> <span m=''1883525''>360</span> <span m=''1883820''>divided</span>
  <span m=''1884250''>by</span> <span m=''1884440''>n.</span> <span m=''1884870''>Now</span>
  <span m=''1885010''>I</span> <span m=''1885130''>said</span> <span m=''1885380''>that</span>
  <span m=''1885530''>was</span> <span m=''1885710''>a</span> <span m=''1885800''>big</span>
  <span m=''1886140''>number,</span> <span m=''1886910''>because</span> <span m=''1887190''>it</span>
  <span m=''1887260''>was</span> <span m=''1888990''>much,</span> <span m=''1889320''>much</span>
  <span m=''1889450''>bigger</span> <span m=''1889750''>than</span> <span m=''1889940''>alpha.</span>
  <span m=''1890680''>Bigger</span> <span m=''1890870''>than</span> <span m=''1891030''>n</span>
  <span m=''1891220''>times</span> <span m=''1891490''>alpha</span> <span m=''1891770''>even,</span>
  <span m=''1892520''>because</span> <span m=''1892730''>I</span> <span m=''1892780''>can</span>
  <span m=''1892900''>make</span> <span m=''1893070''>alpha</span> <span m=''1893420''>very</span>
  <span m=''1893660''>close</span> <span m=''1893940''>to</span> <span m=''1894030''>0.</span>
  </p><p><span m=''1895410''>But</span> <span m=''1895570''>it is</span> <span m=''1895810''>not</span>
  <span m=''1896170''>what</span> <span m=''1896280''>we</span> <span m=''1896380''>call</span>
  <span m=''1896610''>bounded</span> <span m=''1896890''>sharpness.</span> <span m=''1897420''>Bounded</span>
  <span m=''1897720''>sharpness</span> <span m=''1898220''>was</span> <span m=''1898350''>360</span>
  <span m=''1898870''>minus</span> <span m=''1899660''>a</span> <span m=''1899720''>constant--</span>
  <span m=''1900880''>I</span> <span m=''1900940''>really</span> <span m=''1901120''>shouldn''t</span>
  <span m=''1901330''>have</span> <span m=''1901450''>called</span> <span m=''1901670''>it</span>
  <span m=''1901750''>epsilon</span> <span m=''1902140''>because</span> <span m=''1902530''>it''s</span>
  <span m=''1902920''>confusing.</span> <span m=''1904070''>Let</span> <span m=''1904150''>me</span>
  <span m=''1904270''>call</span> <span m=''1904580''>it</span> <span m=''1905540''>gamma</span>
  <span m=''1905850''>just</span> <span m=''1906160''>got</span> <span m=''1906710''>another</span>
  <span m=''1906960''>Greek</span> <span m=''1907180''>letter.</span> <span m=''1910310''>Gamma</span>
  <span m=''1910630''>is</span> <span m=''1910740''>not</span> <span m=''1910910''>arbitrarily</span>
  <span m=''1911510''>small.</span> <span m=''1911810''>It</span> <span m=''1911920''>is</span>
  <span m=''1912090''>a</span> <span m=''1912180''>constant</span> <span m=''1912700''>value,</span>
  <span m=''1914800''>whereas</span> <span m=''1915080''>over</span> <span m=''1915270''>here</span>
  <span m=''1915500''>it''s</span> <span m=''1915620''>not</span> <span m=''1915800''>constant.</span>
  <span m=''1916780''>It''s</span> <span m=''1917240''>a</span> <span m=''1917300''>constant</span>
  <span m=''1917690''>divided</span> <span m=''1918040''>by</span> <span m=''1918180''>n,</span>
  <span m=''1918540''>that''s</span> <span m=''1918750''>sub-constant.</span> </p><p><span
  m=''1920640''>So</span> <span m=''1920760''>this</span> <span m=''1920960''>is</span>
  <span m=''1921060''>not</span> <span m=''1921290''>bounded</span> <span m=''1921480''>sharpness,</span>
  <span m=''1921730''>just</span> <span m=''1922000''>to</span> <span m=''1922850''>check.</span>
  <span m=''1923740''>But</span> <span m=''1923900''>if</span> <span m=''1924130''>we</span>
  <span m=''1924270''>have</span> <span m=''1924950''>all</span> <span m=''1925230''>the</span>
  <span m=''1925430''>reflex</span> <span m=''1925840''>angles,</span> <span m=''1926280''>at</span>
  <span m=''1926420''>most</span> <span m=''1926840''>360</span> <span m=''1927830''>minus</span>
  <span m=''1928170''>an</span> <span m=''1928260''>actual</span> <span m=''1928600''>constant</span>
  <span m=''1929120''>bigger</span> <span m=''1929350''>than</span> <span m=''1929510''>0,</span>
  <span m=''1930410''>then</span> <span m=''1930690''>we</span> <span m=''1930820''>can</span>
  <span m=''1930930''>get</span> <span m=''1931040''>a</span> <span m=''1931100''>polynomial</span>
  <span m=''1931930''>bound</span> <span m=''1932400''>on</span> <span m=''1932760''>the</span>
  <span m=''1933440''>number</span> <span m=''1933820''>of</span> <span m=''1933900''>combinatorially</span>
  <span m=''1934520''>distinct</span> <span m=''1935150''>gluings.</span> <span m=''1935740''>So</span>
  <span m=''1935980''>let</span> <span m=''1936120''>me</span> <span m=''1936270''>show</span>
  <span m=''1936420''>that</span> <span m=''1936670''>to you.</span> </p><p><span
  m=''1963740''>Here''s</span> <span m=''1964000''>the</span> <span m=''1964060''>cool</span>
  <span m=''1964270''>thing</span> <span m=''1964430''>about</span> <span m=''1964700''>bounded</span>
  <span m=''1965020''>sharpness.</span> <span m=''1973190''>How</span> <span m=''1973360''>many</span>
  <span m=''1973600''>leaves</span> <span m=''1974810''>can</span> <span m=''1975060''>the</span>
  <span m=''1975160''>gluing</span> <span m=''1975450''>tree</span> <span m=''1975660''>have?</span>
  <span m=''1977100''>Each</span> <span m=''1977320''>leaf</span> <span m=''1977710''>is</span>
  <span m=''1977900''>either</span> <span m=''1979110''>an</span> <span m=''1979250''>edge,</span>
  <span m=''1979810''>like</span> <span m=''1979970''>it''s</span> <span m=''1980070''>a</span>
  <span m=''1980120''>fold</span> <span m=''1980420''>point.</span> <span m=''1981150''>In</span>
  <span m=''1981250''>that</span> <span m=''1981420''>case,</span> <span m=''1981710''>the</span>
  <span m=''1981800''>curvature</span> <span m=''1982790''>is</span> <span m=''1982970''>180</span>
  <span m=''1983510''>degrees.</span> <span m=''1985120''>Or</span> <span m=''1985290''>it''s
  a</span> <span m=''1985400''>vertex.</span> </p><p><span m=''1987310''>If</span>
  <span m=''1987460''>it''s</span> <span m=''1987610''>a</span> <span m=''1987650''>vertex,</span>
  <span m=''1990220''>the</span> <span m=''1990340''>curvature</span> <span m=''1990780''>at</span>
  <span m=''1990850''>that</span> <span m=''1991080''>point</span> <span m=''1992050''>is</span>
  <span m=''1992580''>360</span> <span m=''1993100''>minus</span> <span m=''1993450''>the</span>
  <span m=''1993570''>angle</span> <span m=''1993920''>at</span> <span m=''1993990''>that</span>
  <span m=''1994210''>point.</span> <span m=''1996094''>360</span> <span m=''1998920''>minus</span>
  <span m=''2000090''>the</span> <span m=''2000220''>angle,</span> <span m=''2000710''>let''s
  call it</span> <span m=''2000980''>alpha.</span> <span m=''2002020''>Now,</span>
  <span m=''2002180''>we</span> <span m=''2002330''>know</span> <span m=''2002510''>that</span>
  <span m=''2002680''>every</span> <span m=''2003000''>angle</span> <span m=''2003290''>alpha</span>
  <span m=''2004020''>is</span> <span m=''2004220''>at</span> <span m=''2004290''>most</span>
  <span m=''2004530''>360</span> <span m=''2004980''>minus</span> <span m=''2005330''>gamma.</span>
  <span m=''2007040''>So</span> <span m=''2007440''>if</span> <span m=''2007780''>this</span>
  <span m=''2008020''>is</span> <span m=''2008140''>going</span> <span m=''2008360''>to</span>
  <span m=''2008480''>be</span> <span m=''2008740''>at</span> <span m=''2008850''>least</span>
  <span m=''2013090''>360</span> <span m=''2013820''>minus</span> <span m=''2014360''>gamma,</span>
  <span m=''2015470''>which</span> <span m=''2015650''>is</span> <span m=''2015750''>just</span>
  <span m=''2015950''>gamma.</span> </p><p><span m=''2019070''>So</span> <span m=''2019380''>every</span>
  <span m=''2019780''>vertex,</span> <span m=''2021400''>every</span> <span m=''2021670''>leaf</span>
  <span m=''2021990''>of</span> <span m=''2022120''>the</span> <span m=''2022220''>tree,</span>
  <span m=''2023540''>has</span> <span m=''2023780''>curvature</span> <span m=''2024720''>at</span>
  <span m=''2024850''>least</span> <span m=''2025520''>gamma.</span> <span m=''2026370''>Gamma</span>
  <span m=''2026620''>is</span> <span m=''2026710''>a</span> <span m=''2026800''>constant.</span>
  <span m=''2028100''>Total</span> <span m=''2028480''>curvature</span> <span m=''2029940''>is</span>
  <span m=''2030130''>720,</span> <span m=''2035800''>exactly.</span> <span m=''2038450''>Therefore,</span>
  <span m=''2038770''>the</span> <span m=''2038880''>number</span> <span m=''2039200''>of</span>
  <span m=''2039240''>leaves</span> <span m=''2042650''>is</span> <span m=''2042930''>at</span>
  <span m=''2043020''>most</span> <span m=''2044600''>720</span> <span m=''2045150''>over</span>
  <span m=''2045300''>gamma,</span> <span m=''2048760''>which</span> <span m=''2049000''>is</span>
  <span m=''2049070''>a</span> <span m=''2049120''>constant.</span> </p><p><span m=''2052880''>That''s</span>
  <span m=''2053050''>going</span> <span m=''2053170''>to</span> <span m=''2053210''>help.</span>
  <span m=''2054780''>We</span> <span m=''2054900''>don''t</span> <span m=''2055050''>have</span>
  <span m=''2055190''>to</span> <span m=''2055310''>worry</span> <span m=''2055590''>about</span>
  <span m=''2057250''>trees</span> <span m=''2057510''>with</span> <span m=''2057670''>n</span>
  <span m=''2057900''>leaves.</span> <span m=''2058679''>We</span> <span m=''2058800''>only</span>
  <span m=''2058969''>have</span> <span m=''2059130''>to</span> <span m=''2059230''>worry</span>
  <span m=''2059389''>about</span> <span m=''2059710''>trees</span> <span m=''2060000''>with</span>
  <span m=''2060989''>20</span> <span m=''2061350''>leaves,</span> <span m=''2061620''>some</span>
  <span m=''2061850''>constant</span> <span m=''2062340''>number</span> <span m=''2062570''>of</span>
  <span m=''2062650''>leaves.</span> <span m=''2063679''>Again,</span> <span m=''2063960''>as</span>
  <span m=''2064790''>the</span> <span m=''2065080''>bound</span> <span m=''2065370''>on</span>
  <span m=''2065469''>sharpness</span> <span m=''2066520''>goes</span> <span m=''2066760''>down,</span>
  <span m=''2067250''>the</span> <span m=''2067639''>number</span> <span m=''2067850''>of</span>
  <span m=''2067909''>leaves</span> <span m=''2068090''>will</span> <span m=''2068190''>go</span>
  <span m=''2068360''>up</span> <span m=''2068810''>in</span> <span m=''2069530''>this</span>
  <span m=''2069710''>inverse</span> <span m=''2070090''>proportional</span> <span
  m=''2070639''>way,</span> <span m=''2071560''>but</span> <span m=''2071780''>it''s</span>
  <span m=''2071969''>a</span> <span m=''2072010''>constant.</span> </p><p><span m=''2073690''>So</span>
  <span m=''2074290''>at</span> <span m=''2074380''>least</span> <span m=''2074600''>for</span>
  <span m=''2074719''>part</span> <span m=''2075030''>one,</span> <span m=''2076510''>we''re</span>
  <span m=''2076659''>golden.</span> <span m=''2077400''>I</span> <span m=''2077500''>mean,</span>
  <span m=''2077699''>the</span> <span m=''2077790''>number</span> <span m=''2078219''>of</span>
  <span m=''2078750''>gluing</span> <span m=''2079020''>trees,</span> <span m=''2079370''>I</span>
  <span m=''2079429''>said</span> <span m=''2079679''>over</span> <span m=''2079860''>here--</span>
  <span m=''2080999''>where</span> <span m=''2081379''>is</span> <span m=''2081760''>it?</span>
  <span m=''2083060''>If</span> <span m=''2083300''>I</span> <span m=''2083389''>have</span>
  <span m=''2083694''>n</span> <span m=''2084000''>nodes</span> <span m=''2084679''>in</span>
  <span m=''2084750''>my</span> <span m=''2084909''>tree,</span> <span m=''2085174''>I''ll</span>
  <span m=''2085440''>only</span> <span m=''2085960''>have</span> <span m=''2086460''>2</span>
  <span m=''2086719''>to</span> <span m=''2086989''>the</span> <span m=''2087179''>order
  n</span> <span m=''2087460''>trees.</span> <span m=''2088900''>So</span> <span m=''2089000''>if</span>
  <span m=''2089100''>I</span> <span m=''2089199''>can</span> <span m=''2089230''>reduce</span>
  <span m=''2089590''>the</span> <span m=''2089670''>number</span> <span m=''2089900''>of</span>
  <span m=''2089949''>nodes</span> <span m=''2090170''>in</span> <span m=''2090230''>my</span>
  <span m=''2090370''>tree,</span> <span m=''2091090''>I</span> <span m=''2091230''>will</span>
  <span m=''2091370''>reduce</span> <span m=''2091650''>the</span> <span m=''2091719''>number</span>
  <span m=''2091960''>of</span> <span m=''2092020''>trees</span> <span m=''2092409''>correspondingly.</span>
  </p><p><span m=''2096940''>If</span> <span m=''2097130''>there''s</span> <span m=''2097310''>only
  a</span> <span m=''2097560''>constant</span> <span m=''2097970''>number</span> <span
  m=''2098130''>of</span> <span m=''2098190''>nodes,</span> <span m=''2099000''>there
  will</span> <span m=''2099120''>be</span> <span m=''2099220''>a</span> <span m=''2099270''>constant</span>
  <span m=''2099770''>number</span> <span m=''2100030''>of</span> <span m=''2100090''>trees.</span>
  <span m=''2100983''>It</span> <span m=''2101710''>doesn''t</span> <span m=''2101920''>matter</span>
  <span m=''2102140''>that</span> <span m=''2102550''>a</span> <span m=''2102690''>constant</span>
  <span m=''2103030''>gets</span> <span m=''2103210''>exponentiated,</span> <span
  m=''2103880''>it''ll</span> <span m=''2104240''>still</span> <span m=''2104440''>be</span>
  <span m=''2104550''>constant.</span> <span m=''2106520''>So</span> <span m=''2106640''>that''s</span>
  <span m=''2107200''>good</span> <span m=''2107350''>news,</span> <span m=''2107620''>except</span>
  <span m=''2107840''>we bounded</span> <span m=''2108320''>again</span> <span m=''2108570''>the</span>
  <span m=''2108650''>number</span> <span m=''2108890''>of</span> <span m=''2108950''>leaves,</span>
  <span m=''2109330''>not</span> <span m=''2109530''>the</span> <span m=''2109610''>number</span>
  <span m=''2109970''>of</span> <span m=''2110050''>nodes.</span> <span m=''2111410''>So</span>
  <span m=''2111690''>we</span> <span m=''2111780''>have</span> <span m=''2111950''>to</span>
  <span m=''2112070''>be</span> <span m=''2113130''>a</span> <span m=''2113250''>little</span>
  <span m=''2113480''>bit</span> <span m=''2113660''>careful,</span> <span m=''2114460''>because</span>
  <span m=''2115110''>in</span> <span m=''2115260''>particular</span> <span m=''2119710''>we</span>
  <span m=''2119780''>can</span> <span m=''2119930''>have</span> <span m=''2120490''>degree</span>
  <span m=''2120790''>2</span> <span m=''2121630''>junctions,</span> <span m=''2122940''>which</span>
  <span m=''2123240''>are</span> <span m=''2123370''>real</span> <span m=''2123630''>junctions--</span>
  <span m=''2124200''>they</span> <span m=''2124500''>might</span> <span m=''2124750''>look</span>
  <span m=''2124910''>like</span> <span m=''2125090''>this</span> <span m=''2125400''>where</span>
  <span m=''2125570''>a vertex</span> <span m=''2126040''>comes</span> <span m=''2126320''>to</span>
  <span m=''2126420''>an</span> <span m=''2126520''>edge.</span> <span m=''2127820''>There''s</span>
  <span m=''2128360''>got</span> <span m=''2128510''>to</span> <span m=''2128580''>be</span>
  <span m=''2129090''>about</span> <span m=''2129400''>n</span> <span m=''2129600''>of</span>
  <span m=''2129720''>those,</span> <span m=''2130100''>because</span> <span m=''2130240''>the</span>
  <span m=''2130320''>vertices</span> <span m=''2130680''>have</span> <span m=''2130850''>to</span>
  <span m=''2130940''>be</span> <span m=''2131060''>somewhere.</span> </p><p><span
  m=''2132250''>We''re</span> <span m=''2132400''>saying</span> <span m=''2133460''>there</span>
  <span m=''2133660''>aren''t</span> <span m=''2133770''>very</span> <span m=''2133990''>many</span>
  <span m=''2134390''>at</span> <span m=''2134610''>the</span> <span m=''2134680''>leaves.</span>
  <span m=''2136150''>And</span> <span m=''2136350''>therefore,</span> <span m=''2136860''>at</span>
  <span m=''2137090''>the</span> <span m=''2137260''>degree</span> <span m=''2137550''>three</span>
  <span m=''2137790''>and</span> <span m=''2137860''>higher</span> <span m=''2138180''>junctions,</span>
  <span m=''2138580''>there</span> <span m=''2138700''>can''t</span> <span m=''2138910''>be</span>
  <span m=''2139010''>very</span> <span m=''2139220''>many.</span> <span m=''2140910''>Maybe</span>
  <span m=''2141220''>I</span> <span m=''2141240''>haven''t</span> <span m=''2141480''>said</span>
  <span m=''2141650''>this,</span> <span m=''2141940''>but</span> <span m=''2141950''>if</span>
  <span m=''2142030''>you</span> <span m=''2142100''>have</span> <span m=''2142200''>a</span>
  <span m=''2142250''>tree</span> <span m=''2142520''>with</span> <span m=''2142800''>L</span>
  <span m=''2143080''>leaves,</span> <span m=''2143990''>you''ll</span> <span m=''2144150''>only</span>
  <span m=''2144430''>have</span> <span m=''2145400''>at</span> <span m=''2145760''>most</span>
  <span m=''2146030''>L</span> <span m=''2146280''>internal</span> <span m=''2146740''>nodes,</span>
  <span m=''2147520''>branching</span> <span m=''2147900''>nodes.</span> <span m=''2149210''>But</span>
  <span m=''2149370''>degree</span> <span m=''2149460''>two</span> <span m=''2149740''>nodes,</span>
  <span m=''2150020''>there</span> <span m=''2150100''>could</span> <span m=''2150240''>be</span>
  <span m=''2150370''>arbitrarily</span> <span m=''2150910''>many.</span> </p><p><span
  m=''2152710''>So</span> <span m=''2153060''>what</span> <span m=''2153290''>we</span>
  <span m=''2153430''>come</span> <span m=''2153680''>to</span> <span m=''2153970''>is,</span>
  <span m=''2155070''>if</span> <span m=''2155260''>I</span> <span m=''2155320''>have</span>
  <span m=''2155710''>L</span> <span m=''2156030''>leaves</span> <span m=''2157166''>in</span>
  <span m=''2157662''>a</span> <span m=''2158160''>tree,</span> <span m=''2159510''>then</span>
  <span m=''2159700''>I''ll</span> <span m=''2159730''>only</span> <span m=''2160090''>get</span>
  <span m=''2160320''>2 to</span> <span m=''2160620''>the</span> <span m=''2160790''>order</span>
  <span m=''2161180''>L</span> <span m=''2162570''>gluings.</span> <span m=''2163230''>This</span>
  <span m=''2163380''>is</span> <span m=''2163480''>what</span> <span m=''2163630''>we</span>
  <span m=''2163740''>need</span> <span m=''2163910''>to</span> <span m=''2164000''>prove.</span>
  <span m=''2168880''>It</span> <span m=''2169040''>will</span> <span m=''2169190''>tell</span>
  <span m=''2169410''>us</span> <span m=''2169600''>that</span> <span m=''2169690''>in</span>
  <span m=''2169780''>particular,</span> <span m=''2170080''>if</span> <span m=''2170380''>we</span>
  <span m=''2170470''>have</span> <span m=''2170600''>a</span> <span m=''2170660''>constant</span>
  <span m=''2171070''>number</span> <span m=''2171290''>of</span> <span m=''2171350''>leaves,</span>
  <span m=''2171770''>as</span> <span m=''2172570''>comes</span> <span m=''2172820''>from</span>
  <span m=''2173020''>the</span> <span m=''2173100''>bounded</span> <span m=''2173410''>sharpens</span>
  <span m=''2173830''>case,</span> <span m=''2174730''>I</span> <span m=''2174890''>will</span>
  <span m=''2175050''>get--</span> <span m=''2176920''>constant</span> <span m=''2177205''>number</span>
  <span m=''2177490''>of gluings?</span> <span m=''2177900''>That''s</span> <span
  m=''2178120''>not</span> <span m=''2178260''>right.</span> </p><p><span m=''2180480''>There''s</span>
  <span m=''2180900''>some</span> <span m=''2181120''>polynomial</span> <span m=''2181690''>on</span>
  <span m=''2181770''>n</span> <span m=''2182620''>times</span> <span m=''2184300''>2
  to</span> <span m=''2184590''>the</span> <span m=''2184750''>order</span> <span
  m=''2185020''>L.</span> <span m=''2190340''>Ah,</span> <span m=''2190810''>that''s</span>
  <span m=''2191060''>why.</span> <span m=''2196090''>I should look</span> <span m=''2196260''>at</span>
  <span m=''2196300''>my</span> <span m=''2196410''>notes</span> <span m=''2196850''>occasionally.</span>
  <span m=''2198060''>The</span> <span m=''2198220''>right</span> <span m=''2198410''>bound</span>
  <span m=''2198760''>to</span> <span m=''2198830''>n</span> <span m=''2199060''>to</span>
  <span m=''2199310''>the</span> <span m=''2199450''>order</span> <span m=''2199710''>L.</span>
  </p><p><span m=''2199940''>In</span> <span m=''2200020''>fact,</span> <span m=''2200240''>what</span>
  <span m=''2200360''>I</span> <span m=''2200390''>wrote</span> <span m=''2200600''>is</span>
  <span m=''2200690''>an</span> <span m=''2200790''>open</span> <span m=''2201050''>problem.</span>
  <span m=''2203210''>I</span> <span m=''2203430''>think</span> <span m=''2204030''>maybe</span>
  <span m=''2204670''>it''s</span> <span m=''2205060''>n</span> <span m=''2205290''>to
  the</span> <span m=''2205410''>order</span> <span m=''2205640''>1</span> <span m=''2205930''>times</span>
  <span m=''2207120''>2 to</span> <span m=''2207360''>the</span> <span m=''2207500''>order</span>
  <span m=''2207730''>L.</span> <span m=''2208420''>This</span> <span m=''2208580''>is</span>
  <span m=''2208690''>what</span> <span m=''2208870''>you''d</span> <span m=''2208990''>call</span>
  <span m=''2209200''>a</span> <span m=''2209250''>fixed</span> <span m=''2209490''>parameter</span>
  <span m=''2209800''>tractable</span> <span m=''2210270''>bound,</span> <span m=''2212390''>but</span>
  <span m=''2212520''>no</span> <span m=''2212620''>such</span> <span m=''2212870''>upper</span>
  <span m=''2212930''>bound is</span> <span m=''2213360''>known.</span> <span m=''2213760''>That</span>
  <span m=''2213830''>might</span> <span m=''2214020''>be</span> <span m=''2214140''>fun</span>
  <span m=''2214300''>to</span> <span m=''2214370''>work</span> <span m=''2214550''>on</span>
  <span m=''2214690''>in the</span> <span m=''2214760''>problem</span> <span m=''2215120''>session.</span>
  <span m=''2215480''>It might</span> <span m=''2215690''>not</span> <span m=''2215850''>be</span>
  <span m=''2215950''>difficult,</span> <span m=''2217560''>just</span> <span m=''2217780''>at</span>
  <span m=''2217860''>the</span> <span m=''2217970''>time</span> <span m=''2218250''>I</span>
  <span m=''2218300''>didn''t</span> <span m=''2218480''>know</span> <span m=''2218610''>those</span>
  <span m=''2218770''>bounds</span> <span m=''2219010''>were</span> <span m=''2219080''>important.</span>
  </p><p><span m=''2223070''>So</span> <span m=''2223250''>we</span> <span m=''2223330''>still</span>
  <span m=''2223510''>have to</span> <span m=''2223620''>prove</span> <span m=''2223850''>this,</span>
  <span m=''2225430''>n</span> <span m=''2225720''>to the</span> <span m=''2225850''>order</span>
  <span m=''2226110''>L.</span> <span m=''2234430''>This is</span> <span m=''2234640''>the</span>
  <span m=''2234730''>part where</span> <span m=''2235170''>my</span> <span m=''2235240''>notes
  are</span> <span m=''2235450''>wrong.</span> <span m=''2241580''>Here''s</span>
  <span m=''2241890''>the</span> <span m=''2241970''>idea,</span> <span m=''2242150''>we
  have</span> <span m=''2242240''>a</span> <span m=''2242330''>small</span> <span
  m=''2242660''>number of</span> <span m=''2242900''>leaves,</span> <span m=''2243290''>we''re</span>
  <span m=''2243390''>worried</span> <span m=''2243720''>about</span> <span m=''2243980''>these</span>
  <span m=''2244200''>degree</span> <span m=''2244680''>2</span> <span m=''2245420''>junctions.</span>
  <span m=''2246200''>But</span> <span m=''2246410''>I</span> <span m=''2246470''>claim,</span>
  <span m=''2248130''>actually</span> <span m=''2249450''>there isn''t</span> <span
  m=''2249640''>a lot</span> <span m=''2249940''>going</span> <span m=''2250230''>on.</span>
  </p><p><span m=''2253690''>Because</span> <span m=''2254010''>one</span> <span m=''2254510''>of</span>
  <span m=''2254580''>the</span> <span m=''2254660''>great</span> <span m=''2254860''>things</span>
  <span m=''2255070''>we</span> <span m=''2255190''>can</span> <span m=''2255320''>do,</span>
  <span m=''2255550''>over</span> <span m=''2255790''>here</span> <span m=''2256060''>we</span>
  <span m=''2256180''>said</span> <span m=''2256620''>for</span> <span m=''2256790''>every</span>
  <span m=''2257160''>dot,</span> <span m=''2257500''>was</span> <span m=''2258180''>it</span>
  <span m=''2258250''>a</span> <span m=''2258290''>vertex</span> <span m=''2258890''>or</span>
  <span m=''2258980''>was it</span> <span m=''2259290''>an</span> <span m=''2259430''>edge?</span>
  <span m=''2262640''>We</span> <span m=''2262820''>can''t</span> <span m=''2263030''>afford</span>
  <span m=''2263310''>that</span> <span m=''2263440''>anymore,</span> <span m=''2263870''>because</span>
  <span m=''2264560''>there''s</span> <span m=''2265330''>n</span> <span m=''2265510''>dots
  still.</span> <span m=''2266490''>We</span> <span m=''2266600''>can''t</span> <span
  m=''2266780''>afford</span> <span m=''2267090''>2 to</span> <span m=''2267220''>the</span>
  <span m=''2267430''>order</span> <span m=''2267870''>n.</span> </p><p><span m=''2268880''>Where</span>
  <span m=''2269050''>we</span> <span m=''2269180''>can</span> <span m=''2269410''>afford</span>
  <span m=''2269730''>it is</span> <span m=''2269940''>at</span> <span m=''2270100''>the</span>
  <span m=''2270190''>leaves,</span> <span m=''2271160''>because</span> <span m=''2271310''>there''s</span>
  <span m=''2271450''>only</span> <span m=''2271680''>L</span> <span m=''2271880''>of</span>
  <span m=''2271990''>those,</span> <span m=''2272920''>and</span> <span m=''2273260''>at</span>
  <span m=''2273350''>the</span> <span m=''2273420''>branching</span> <span m=''2273860''>nodes.</span>
  <span m=''2275220''>So</span> <span m=''2275360''>everything</span> <span m=''2275740''>except</span>
  <span m=''2276710''>these</span> <span m=''2277080''>degree</span> <span m=''2277390''>2</span>
  <span m=''2277650''>problems</span> <span m=''2279320''>we</span> <span m=''2279720''>could</span>
  <span m=''2279930''>specify.</span> <span m=''2280580''>And</span> <span m=''2280700''>really</span>
  <span m=''2280940''>we</span> <span m=''2281070''>could</span> <span m=''2281180''>specify</span>
  <span m=''2281550''>anything</span> <span m=''2281920''>we</span> <span m=''2282040''>want.</span>
  </p><p><span m=''2283180''>So</span> <span m=''2283330''>yeah,</span> <span m=''2283650''>we</span>
  <span m=''2283750''>could</span> <span m=''2283880''>specify,</span> <span m=''2284470''>is</span>
  <span m=''2284670''>it</span> <span m=''2285170''>a</span> <span m=''2285270''>vertex</span>
  <span m=''2285700''>or</span> <span m=''2285800''>is</span> <span m=''2285890''>it</span>
  <span m=''2285980''>an</span> <span m=''2286080''>edge?</span> <span m=''2287040''>But</span>
  <span m=''2287220''>we</span> <span m=''2287360''>could</span> <span m=''2287530''>make</span>
  <span m=''2287740''>life</span> <span m=''2288080''>even</span> <span m=''2288360''>easier--</span>
  <span m=''2290792''>hm,</span> <span m=''2292644''>I</span> <span m=''2293110''>have</span>
  <span m=''2293280''>an</span> <span m=''2293370''>idea</span> <span m=''2293640''>for</span>
  <span m=''2293780''>solving</span> <span m=''2294090''>this</span> <span m=''2294240''>open</span>
  <span m=''2294490''>problem.</span> <span m=''2294800''>Do</span> <span m=''2294870''>I</span>
  <span m=''2294980''>want</span> <span m=''2295120''>to</span> <span m=''2295180''>solve</span>
  <span m=''2295440''>it</span> <span m=''2295510''>right</span> <span m=''2295700''>now?</span>
  <span m=''2297530''>Yeah,</span> <span m=''2297930''>let''s</span> <span m=''2298130''>do</span>
  <span m=''2298310''>it.</span> </p><p><span m=''2302610''>Let me</span> <span m=''2302920''>think</span>
  <span m=''2303160''>for</span> <span m=''2303220''>a</span> <span m=''2303270''>second.</span>
  <span m=''2305126''>I</span> <span m=''2305600''>think</span> <span m=''2306230''>that''s</span>
  <span m=''2306460''>going</span> <span m=''2306560''>to</span> <span m=''2306630''>work.</span>
  <span m=''2306910''>OK,</span> <span m=''2307270''>cool,</span> <span m=''2308470''>cool.</span>
  <span m=''2309160''>I</span> <span m=''2309890''>needed</span> <span m=''2310120''>to</span>
  <span m=''2310200''>rewrite</span> <span m=''2310510''>these</span> <span m=''2310660''>notes</span>
  <span m=''2310870''>anyway,</span> <span m=''2311240''>so</span> <span m=''2311540''>I
  might</span> <span m=''2311800''>as</span> <span m=''2311930''>well prove</span>
  <span m=''2312110''>a</span> <span m=''2312170''>stronger</span> <span m=''2312500''>result.</span>
  </p><p><span m=''2314560''>All</span> <span m=''2314620''>right,</span> <span m=''2314940''>so</span>
  <span m=''2315430''>let</span> <span m=''2315570''>me</span> <span m=''2315970''>draw</span>
  <span m=''2316190''>a</span> <span m=''2316240''>picture.</span> <span m=''2322300''>There''s</span>
  <span m=''2322530''>branching</span> <span m=''2323000''>nodes,</span> <span m=''2323300''>and</span>
  <span m=''2323380''>I</span> <span m=''2323420''>surely</span> <span m=''2323760''>draw</span>
  <span m=''2324060''>one</span> <span m=''2324220''>of</span> <span m=''2324290''>these</span>
  <span m=''2324460''>longer</span> <span m=''2324870''>so</span> <span m=''2325000''>I</span>
  <span m=''2325090''>can</span> <span m=''2325430''>say,</span> <span m=''2325690''>oh</span>
  <span m=''2325890''>there''s</span> <span m=''2326120''>some degree</span> <span
  m=''2326470''>two</span> <span m=''2326600''>junctions</span> <span m=''2327060''>here.</span>
  <span m=''2327300''>Those</span> <span m=''2327530''>are</span> <span m=''2327630''>annoying,</span>
  <span m=''2328670''>ignore</span> <span m=''2328950''>those.</span> <span m=''2329640''>For</span>
  <span m=''2329740''>everything</span> <span m=''2330070''>else--</span> <span m=''2330360''>the</span>
  <span m=''2330460''>leaves</span> <span m=''2331640''>and</span> <span m=''2332350''>the</span>
  <span m=''2332600''>branching</span> <span m=''2332950''>nodes--</span> <span m=''2333940''>I''m</span>
  <span m=''2334080''>going</span> <span m=''2334190''>to</span> <span m=''2334310''>specify</span>
  <span m=''2335410''>the</span> <span m=''2335530''>same</span> <span m=''2335780''>binary</span>
  <span m=''2336240''>thing.</span> <span m=''2336530''>Is</span> <span m=''2336690''>it</span>
  <span m=''2336750''>a</span> <span m=''2336870''>vertex,</span> <span m=''2337180''>or</span>
  <span m=''2337490''>is</span> <span m=''2337620''>it an</span> <span m=''2337880''>edge?</span>
  <span m=''2338990''>But</span> <span m=''2339190''>now</span> <span m=''2339910''>there''s</span>
  <span m=''2340070''>only</span> <span m=''2341320''>order</span> <span m=''2341600''>L</span>
  <span m=''2341780''>of</span> <span m=''2341890''>them.</span> </p><p><span m=''2342160''>There''s</span>
  <span m=''2342350''>L</span> <span m=''2342635''>leaves,</span> <span m=''2342920''>so
  there''s</span> <span m=''2343400''>at</span> <span m=''2343480''>most</span> <span
  m=''2343710''>L</span> <span m=''2343870''>minus</span> <span m=''2344180''>1</span>
  <span m=''2344370''>internal</span> <span m=''2344750''>nodes.</span> <span m=''2345610''>Each</span>
  <span m=''2345810''>of</span> <span m=''2345870''>them</span> <span m=''2346160''>has</span>
  <span m=''2346580''>some</span> <span m=''2346740''>degree,</span> <span m=''2347140''>but</span>
  <span m=''2347360''>the</span> <span m=''2347470''>total</span> <span m=''2349480''>number</span>
  <span m=''2349710''>of</span> <span m=''2349750''>these</span> <span m=''2349930''>dots</span>
  <span m=''2350220''>will</span> <span m=''2350390''>be</span> <span m=''2350940''>order</span>
  <span m=''2351210''>L</span> <span m=''2351510''>if I</span> <span m=''2351720''>ignore</span>
  <span m=''2352570''>the</span> <span m=''2352690''>degree</span> <span m=''2352970''>2.</span>
  <span m=''2354510''>So</span> <span m=''2354920''>that''s</span> <span m=''2355310''>2
  to</span> <span m=''2355570''>the</span> <span m=''2355740''>order</span> <span
  m=''2356030''>L</span> <span m=''2357950''>vertex</span> <span m=''2358630''>edge</span>
  <span m=''2359840''>colorings,</span> <span m=''2363320''>just</span> <span m=''2363560''>like</span>
  <span m=''2363730''>before</span> <span m=''2366340''>except</span> <span m=''2366520''>now</span>
  <span m=''2366780''>with L,</span> <span m=''2370570''>of</span> <span m=''2371340''>leaves</span>
  <span m=''2374590''>and</span> <span m=''2375170''>branching</span> <span m=''2375660''>nodes.</span>
  </p><p><span m=''2377420''>Oh,</span> <span m=''2377780''>I</span> <span m=''2377910''>see</span>
  <span m=''2378080''>the</span> <span m=''2378190''>problem.</span> <span m=''2379050''>Darn
  it.</span> <span m=''2384730''>What</span> <span m=''2384890''>I''d</span> <span
  m=''2384980''>like</span> <span m=''2385170''>to</span> <span m=''2385290''>do</span>
  <span m=''2385440''>is</span> <span m=''2385560''>mimic</span> <span m=''2385910''>the</span>
  <span m=''2386020''>same</span> <span m=''2386270''>proof</span> <span m=''2386540''>and</span>
  <span m=''2386660''>say,</span> <span m=''2386940''>well</span> <span m=''2388240''>choose</span>
  <span m=''2388540''>where</span> <span m=''2388730''>V1</span> <span m=''2389240''>is</span>
  <span m=''2390280''>and</span> <span m=''2390450''>then</span> <span m=''2390590''>just</span>
  <span m=''2390840''>label</span> <span m=''2391150''>them</span> <span m=''2391420''>around.</span>
  <span m=''2393360''>There''s</span> <span m=''2393510''>a</span> <span m=''2393560''>problem</span>
  <span m=''2393860''>with</span> <span m=''2394000''>that,</span> <span m=''2394410''>though.</span>
  <span m=''2394640''>Say V1</span> <span m=''2395010''>is</span> <span m=''2395140''>here.</span>
  </p><p><span m=''2398460''>Where''s</span> <span m=''2398740''>V2?</span> <span
  m=''2399840''>Well,</span> <span m=''2400040''>maybe</span> <span m=''2400320''>this</span>
  <span m=''2400530''>is</span> <span m=''2400650''>an</span> <span m=''2400730''>edge,</span>
  <span m=''2401080''>maybe</span> <span m=''2401320''>this</span> <span m=''2401500''>is</span>
  <span m=''2401600''>an</span> <span m=''2401680''>edge.</span> <span m=''2402430''>This,</span>
  <span m=''2403060''>I</span> <span m=''2403100''>have</span> <span m=''2403250''>no</span>
  <span m=''2403440''>idea.</span> <span m=''2403960''>Is</span> <span m=''2404490''>it
  an</span> <span m=''2404670''>edge?</span> <span m=''2405030''>Is it</span> <span
  m=''2405090''>a</span> <span m=''2405150''>vertex?</span> </p><p><span m=''2406310''>I</span>
  <span m=''2406460''>can''t</span> <span m=''2406730''>tell.</span> <span m=''2407860''>At</span>
  <span m=''2407970''>degree</span> <span m=''2408270''>2</span> <span m=''2408420''>junctions,</span>
  <span m=''2408870''>I</span> <span m=''2408960''>have</span> <span m=''2409110''>a</span>
  <span m=''2409170''>problem.</span> <span m=''2411230''>That''s</span> <span m=''2411390''>kind</span>
  <span m=''2411550''>of</span> <span m=''2411620''>annoying.</span> </p><p><span
  m=''2413770''>To</span> <span m=''2414350''>fix</span> <span m=''2414810''>that--</span>
  <span m=''2415140''>and</span> <span m=''2415805''>so</span> <span m=''2416100''>this</span>
  <span m=''2416310''>is</span> <span m=''2416430''>still</span> <span m=''2416640''>going</span>
  <span m=''2416750''>to</span> <span m=''2416800''>be</span> <span m=''2416930''>open,</span>
  <span m=''2417440''>alas.</span> <span m=''2418670''>To</span> <span m=''2418810''>fix</span>
  <span m=''2419090''>that</span> <span m=''2419780''>I</span> <span m=''2419930''>need</span>
  <span m=''2420200''>to--</span> <span m=''2421790''>I</span> <span m=''2421910''>really</span>
  <span m=''2422180''>want</span> <span m=''2422370''>to</span> <span m=''2422430''>know</span>
  <span m=''2422650''>which</span> <span m=''2423550''>dot</span> <span m=''2423870''>is</span>
  <span m=''2424060''>which</span> <span m=''2424270''>vertex</span> <span m=''2426370''>for</span>
  <span m=''2426540''>reasons</span> <span m=''2427160''>to</span> <span m=''2427350''>be</span>
  <span m=''2427590''>determined.</span> <span m=''2428090''>But</span> <span m=''2428210''>in</span>
  <span m=''2428310''>particular,</span> <span m=''2428790''>that</span> <span m=''2428970''>is</span>
  <span m=''2429090''>part</span> <span m=''2429360''>of</span> <span m=''2430120''>number</span>
  <span m=''2430340''>two.</span> <span m=''2433980''>So</span> <span m=''2434110''>I''m</span>
  <span m=''2434210''>just</span> <span m=''2434380''>going</span> <span m=''2434520''>to</span>
  <span m=''2435120''>give</span> <span m=''2435340''>up</span> <span m=''2435770''>and</span>
  <span m=''2435950''>say,</span> <span m=''2436210''>well</span> <span m=''2440690''>there''s</span>
  <span m=''2441460''>2n</span> <span m=''2442490''>different</span> <span m=''2442790''>things</span>
  <span m=''2443390''>that</span> <span m=''2443540''>they</span> <span m=''2443660''>could</span>
  <span m=''2443820''>be,</span> <span m=''2444710''>n</span> <span m=''2444890''>vertices</span>
  <span m=''2445320''>and</span> <span m=''2445480''>edges.</span> </p><p><span m=''2448940''>Do
  I</span> <span m=''2449000''>want</span> <span m=''2449150''>to</span> <span m=''2449220''>do</span>
  <span m=''2449330''>it</span> <span m=''2449410''>that</span> <span m=''2449590''>way?</span>
  <span m=''2452230''>Maybe</span> <span m=''2452540''>n</span> <span m=''2453540''>choose</span>
  <span m=''2453960''>order</span> <span m=''2454300''>L.</span> <span m=''2456360''>I''m</span>
  <span m=''2456550''>just</span> <span m=''2456690''>going</span> <span m=''2456810''>to</span>
  <span m=''2456880''>write</span> <span m=''2457100''>down</span> <span m=''2457830''>wherever</span>
  <span m=''2458360''>I</span> <span m=''2458430''>have</span> <span m=''2458690''>a</span>
  <span m=''2459100''>filled</span> <span m=''2459570''>dot--</span> <span m=''2460250''>I</span>
  <span m=''2460390''>guess this one</span> <span m=''2460700''>is</span> <span m=''2460810''>not</span>
  <span m=''2461030''>filled.</span> <span m=''2461790''>Maybe</span> <span m=''2462020''>this</span>
  <span m=''2462200''>one''s</span> <span m=''2462400''>filled,</span> <span m=''2463450''>filled.</span>
  <span m=''2464510''>I just</span> <span m=''2464630''>going</span> <span m=''2464750''>to</span>
  <span m=''2464820''>write</span> <span m=''2465000''>down,</span> <span m=''2465240''>what</span>
  <span m=''2465420''>is</span> <span m=''2465540''>the</span> <span m=''2465630''>vertex</span>
  <span m=''2466030''>number</span> <span m=''2466240''>there?</span> </p><p><span
  m=''2466690''>This</span> <span m=''2466870''>is</span> <span m=''2466980''>maybe</span>
  <span m=''2467420''>V3,</span> <span m=''2468090''>V5,</span> <span m=''2470150''>V20,</span>
  <span m=''2474890''>V21,</span> <span m=''2476310''>whatever,</span> <span m=''2477480''>for</span>
  <span m=''2477590''>each</span> <span m=''2477760''>of</span> <span m=''2477830''>the</span>
  <span m=''2477900''>filled</span> <span m=''2478160''>dots</span> <span m=''2478540''>among</span>
  <span m=''2479050''>the</span> <span m=''2479120''>vertices</span> <span m=''2479490''>that</span>
  <span m=''2479600''>I</span> <span m=''2479670''>can</span> <span m=''2479770''>see,</span>
  <span m=''2480210''>ignoring</span> <span m=''2480870''>again</span> <span m=''2481260''>the</span>
  <span m=''2481880''>degree</span> <span m=''2482130''>two</span> <span m=''2482280''>junctions.</span>
  <span m=''2483850''>There''s</span> <span m=''2484700''>order</span> <span m=''2486010''>L</span>
  <span m=''2486230''>of</span> <span m=''2486340''>them.</span> <span m=''2486965''>I</span>
  <span m=''2487290''>just</span> <span m=''2487480''>going</span> <span m=''2487610''>to</span>
  <span m=''2487690''>for</span> <span m=''2487880''>each</span> <span m=''2488110''>one</span>
  <span m=''2488360''>pick</span> <span m=''2488590''>out</span> <span m=''2488720''>one</span>
  <span m=''2488870''>of</span> <span m=''2488930''>the</span> <span m=''2489000''>labels.</span>
  <span m=''2491041''>Again,</span> <span m=''2491650''>the</span> <span m=''2491760''>order</span>
  <span m=''2491980''>is</span> <span m=''2492080''>determined,</span> <span m=''2492770''>so</span>
  <span m=''2492800''>this</span> <span m=''2493000''>is</span> <span m=''2493130''>the</span>
  <span m=''2493220''>right</span> <span m=''2493400''>number</span> <span m=''2493680''>of</span>
  <span m=''2493750''>them.</span> </p><p><span m=''2494560''>And</span> <span m=''2495050''>this</span>
  <span m=''2495280''>is</span> <span m=''2495690''>n</span> <span m=''2495810''>to
  the</span> <span m=''2496130''>order</span> <span m=''2496360''>L</span> <span m=''2497410''>at</span>
  <span m=''2498270''>most.</span> <span m=''2500270''>So</span> <span m=''2500400''>this</span>
  <span m=''2500570''>is</span> <span m=''2500680''>where</span> <span m=''2500910''>I''m</span>
  <span m=''2501320''>being</span> <span m=''2501510''>a</span> <span m=''2501560''>bit</span>
  <span m=''2501720''>wasteful.</span> <span m=''2502550''>It would</span> <span m=''2502870''>be</span>
  <span m=''2502960''>interesting</span> <span m=''2503330''>to</span> <span m=''2503390''>try</span>
  <span m=''2503540''>to</span> <span m=''2503600''>get</span> <span m=''2503730''>around</span>
  <span m=''2503990''>that.</span> <span m=''2507300''>This</span> <span m=''2507540''>was</span>
  <span m=''2508290''>actual</span> <span m=''2508700''>vertex</span> <span m=''2509160''>labelings.</span>
  </p><p><span m=''2516040''>So</span> <span m=''2516180''>now,</span> <span m=''2517050''>among</span>
  <span m=''2517430''>the</span> <span m=''2517510''>vertices</span> <span m=''2517920''>I</span>
  <span m=''2518000''>can</span> <span m=''2518200''>see--</span> <span m=''2519200''>the</span>
  <span m=''2519330''>degree</span> <span m=''2519600''>three</span> <span m=''2519760''>junctions,</span>
  <span m=''2520360''>and</span> <span m=''2520560''>the</span> <span m=''2520630''>leaves,</span>
  <span m=''2522490''>and</span> <span m=''2522710''>higher</span> <span m=''2522930''>degree</span>
  <span m=''2523160''>junctions--</span> <span m=''2524770''>I</span> <span m=''2524890''>know</span>
  <span m=''2525100''>which</span> <span m=''2525290''>vertices</span> <span m=''2525680''>are</span>
  <span m=''2525750''>glued</span> <span m=''2525990''>there.</span> <span m=''2526360''>I</span>
  <span m=''2526460''>can</span> <span m=''2526540''>also</span> <span m=''2527640''>figure</span>
  <span m=''2527960''>out</span> <span m=''2528040''>which</span> <span m=''2528240''>edges</span>
  <span m=''2529730''>are</span> <span m=''2529880''>glued</span> <span m=''2530120''>there
  by</span> <span m=''2530530''>similar</span> <span m=''2530910''>labeling,</span>
  <span m=''2532460''>although I</span> <span m=''2532730''>don''t</span> <span m=''2532910''>think</span>
  <span m=''2533060''>I</span> <span m=''2533090''>actually</span> <span m=''2533590''>care.</span>
  <span m=''2534716''>No, I</span> <span m=''2535110''>probably</span> <span m=''2535380''>care,</span>
  <span m=''2536170''>because</span> <span m=''2537760''>it''s</span> <span m=''2537930''>part</span>
  <span m=''2538180''>of</span> <span m=''2538680''>number</span> <span m=''2538910''>2.</span>
  <span m=''2539610''>So</span> <span m=''2539770''>I</span> <span m=''2539940''>do</span>
  <span m=''2540110''>have</span> <span m=''2540270''>to</span> <span m=''2540370''>also</span>
  <span m=''2540660''>label</span> <span m=''2541330''>the</span> <span m=''2541470''>open</span>
  <span m=''2541770''>circles</span> <span m=''2542820''>which</span> <span m=''2543110''>edge</span>
  <span m=''2543480''>is</span> <span m=''2543740''>there.</span> <span m=''2545150''>But</span>
  <span m=''2545450''>a</span> <span m=''2545550''>similar</span> <span m=''2545970''>bound</span>
  <span m=''2546210''>holds.</span> </p><p><span m=''2548890''>What''s</span> <span
  m=''2549120''>left?</span> <span m=''2553560''>What''s</span> <span m=''2553700''>left</span>
  <span m=''2554000''>are</span> <span m=''2554090''>the</span> <span m=''2554180''>degree</span>
  <span m=''2554450''>2</span> <span m=''2554600''>vertices.</span> <span m=''2555930''>I</span>
  <span m=''2556040''>don''t</span> <span m=''2556150''>know</span> <span m=''2556250''>anything</span>
  <span m=''2556590''>about</span> <span m=''2556840''>them.</span> <span m=''2560690''>This</span>
  <span m=''2560920''>is</span> <span m=''2561060''>particularly</span> <span m=''2562250''>tricky</span>
  <span m=''2562770''>when</span> <span m=''2563000''>I</span> <span m=''2563070''>have</span>
  <span m=''2563780''>some</span> <span m=''2564060''>edge</span> <span m=''2566850''>here.</span>
  </p><p><span m=''2567330''>But</span> <span m=''2567940''>let''s</span> <span m=''2568200''>first</span>
  <span m=''2568430''>think</span> <span m=''2568590''>about</span> <span m=''2568860''>the</span>
  <span m=''2568940''>case</span> <span m=''2569190''>where</span> <span m=''2569300''>I</span>
  <span m=''2569330''>have</span> <span m=''2569490''>a</span> <span m=''2569520''>vertex,</span>
  <span m=''2572130''>add</span> <span m=''2572300''>a</span> <span m=''2572360''>leaf,</span>
  <span m=''2573990''>and</span> <span m=''2574420''>I</span> <span m=''2574490''>have</span>
  <span m=''2574740''>these</span> <span m=''2574900''>degree</span> <span m=''2575150''>two</span>
  <span m=''2576890''>junctions.</span> <span m=''2578140''>And</span> <span m=''2578480''>I</span>
  <span m=''2578740''>don''t</span> <span m=''2578870''>know</span> <span m=''2579100''>which</span>
  <span m=''2579340''>edge is</span> <span m=''2579680''>here,</span> <span m=''2580290''>which</span>
  <span m=''2580490''>vertex</span> <span m=''2580880''>is</span> <span m=''2580990''>here.</span>
  <span m=''2581730''>In</span> <span m=''2581920''>this</span> <span m=''2582130''>case,</span>
  <span m=''2582360''>because</span> <span m=''2582540''>everything''s</span> <span
  m=''2582830''>small,</span> <span m=''2583100''>I</span> <span m=''2583150''>might</span>
  <span m=''2583320''>be</span> <span m=''2583400''>able</span> <span m=''2583540''>to</span>
  <span m=''2583590''>figure</span> <span m=''2583840''>out.</span> </p><p><span m=''2583990''>But</span>
  <span m=''2584110''>here,</span> <span m=''2584680''>where''s</span> <span m=''2585180''>the</span>
  <span m=''2585340''>V3</span> <span m=''2586160''>to</span> <span m=''2586240''>V4</span>
  <span m=''2586980''>transition?</span> <span m=''2587960''>Could</span> <span m=''2588100''>be</span>
  <span m=''2588240''>here,</span> <span m=''2589000''>or it</span> <span m=''2589020''>could</span>
  <span m=''2589200''>be</span> <span m=''2589320''>here.</span> <span m=''2590900''>It</span>
  <span m=''2590930''>could</span> <span m=''2591110''>be</span> <span m=''2591240''>here.</span>
  <span m=''2593040''>I</span> <span m=''2593710''>can''t</span> <span m=''2593890''>afford</span>
  <span m=''2594400''>to</span> <span m=''2594500''>figure</span> <span m=''2594870''>it</span>
  <span m=''2594930''>out.</span> </p><p><span m=''2596330''>Fortunately,</span> <span
  m=''2597400''>I</span> <span m=''2597450''>don''t</span> <span m=''2597600''>have</span>
  <span m=''2597800''>to</span> <span m=''2597920''>figure</span> <span m=''2598230''>it</span>
  <span m=''2598280''>out.</span> <span m=''2600720''>It''s</span> <span m=''2600920''>not</span>
  <span m=''2601110''>so</span> <span m=''2601220''>obvious.</span> <span m=''2601580''>From</span>
  <span m=''2601710''>this</span> <span m=''2601860''>picture</span> <span m=''2602140''>you</span>
  <span m=''2602260''>can''t</span> <span m=''2602480''>see</span> <span m=''2603260''>what''s</span>
  <span m=''2603470''>going</span> <span m=''2603710''>on,</span> <span m=''2603920''>but</span>
  <span m=''2604090''>this</span> <span m=''2604660''>came</span> <span m=''2604960''>from
  a</span> <span m=''2605210''>polygon.</span> <span m=''2606520''>This</span> <span
  m=''2606700''>is</span> <span m=''2606810''>an</span> <span m=''2606900''>actual</span>
  <span m=''2607310''>vertex,</span> <span m=''2607860''>this</span> <span m=''2608240''>is</span>
  <span m=''2608420''>an</span> <span m=''2608520''>actual</span> <span m=''2608920''>vertex.</span>
  <span m=''2610290''>So</span> <span m=''2610370''>this</span> <span m=''2611900''>edge</span>
  <span m=''2612250''>length</span> <span m=''2614000''>is</span> <span m=''2615350''>the</span>
  <span m=''2615500''>total</span> <span m=''2615830''>perimeter</span> <span m=''2616270''>from</span>
  <span m=''2616470''>V3</span> <span m=''2616880''>to</span> <span m=''2616960''>V5</span>
  <span m=''2617450''>along</span> <span m=''2617930''>the</span> <span m=''2618030''>polygon.</span>
  <span m=''2619690''>I</span> <span m=''2619820''>know</span> <span m=''2619990''>how</span>
  <span m=''2620170''>long</span> <span m=''2620470''>that</span> <span m=''2620650''>is.</span>
  </p><p><span m=''2623040''>So</span> <span m=''2625510''>also</span> <span m=''2626160''>if</span>
  <span m=''2627170''>that</span> <span m=''2627350''>was</span> <span m=''2627480''>going</span>
  <span m=''2627660''>clockwise</span> <span m=''2628200''>from</span> <span m=''2628360''>V3</span>
  <span m=''2628760''>around</span> <span m=''2628930''>the</span> <span m=''2629010''>polygon--</span>
  <span m=''2630070''>actually,</span> <span m=''2630320''>that''s</span> <span m=''2630500''>probably</span>
  <span m=''2630740''>counter-clockwise</span> <span m=''2631430''>in</span> <span
  m=''2631490''>the</span> <span m=''2631580''>polygon</span> <span m=''2632030''>because</span>
  <span m=''2632180''>everything''s</span> <span m=''2632550''>inside</span> <span
  m=''2632860''>out.</span> <span m=''2633420''>If</span> <span m=''2633490''>I</span>
  <span m=''2633540''>go</span> <span m=''2633670''>the</span> <span m=''2633850''>other</span>
  <span m=''2634090''>way--</span> <span m=''2634440''>let''s</span> <span m=''2634830''>be</span>
  <span m=''2634960''>relative--</span> <span m=''2636030''>from</span> <span m=''2636260''>V3,</span>
  <span m=''2637255''>I</span> <span m=''2637620''>can</span> <span m=''2637770''>measure</span>
  <span m=''2638070''>out</span> <span m=''2638720''>the</span> <span m=''2638800''>same</span>
  <span m=''2639040''>length.</span> <span m=''2640560''>So</span> <span m=''2640750''>in</span>
  <span m=''2640850''>fact,</span> <span m=''2641360''>I</span> <span m=''2641460''>have</span>
  <span m=''2641510''>some</span> <span m=''2641780''>polygon--</span> <span m=''2642310''>maybe</span>
  <span m=''2642520''>it</span> <span m=''2642610''>looks</span> <span m=''2642890''>like</span>
  <span m=''2643100''>this,</span> <span m=''2643330''>whatever.</span> </p><p><span
  m=''2644050''>I</span> <span m=''2644230''>go</span> <span m=''2644450''>from</span>
  <span m=''2644900''>V3</span> <span m=''2645960''>to</span> <span m=''2646300''>V5,</span>
  <span m=''2649010''>and</span> <span m=''2649290''>I</span> <span m=''2649360''>measure</span>
  <span m=''2649760''>out</span> <span m=''2649890''>that</span> <span m=''2650110''>length.</span>
  <span m=''2651270''>And</span> <span m=''2651590''>I</span> <span m=''2651640''>go</span>
  <span m=''2651860''>the</span> <span m=''2652060''>other</span> <span m=''2652400''>way</span>
  <span m=''2652680''>from</span> <span m=''2652900''>V3,</span> <span m=''2654090''>and</span>
  <span m=''2654310''>I</span> <span m=''2654470''>know</span> <span m=''2654750''>this</span>
  <span m=''2655150''>is</span> <span m=''2655260''>getting</span> <span m=''2655680''>glued</span>
  <span m=''2655780''>to that.</span> <span m=''2657910''>So</span> <span m=''2658140''>I</span>
  <span m=''2658240''>know</span> <span m=''2658470''>where</span> <span m=''2658570''>the</span>
  <span m=''2658680''>vertices</span> <span m=''2659220''>are</span> <span m=''2661290''>from</span>
  <span m=''2661510''>the</span> <span m=''2661590''>lengths.</span> <span m=''2663770''>I</span>
  <span m=''2663930''>can</span> <span m=''2664110''>figure</span> <span m=''2664520''>out</span>
  <span m=''2664710''>exactly</span> <span m=''2665350''>what</span> <span m=''2665520''>this</span>
  <span m=''2665670''>picture</span> <span m=''2665980''>must</span> <span m=''2666270''>be</span>
  <span m=''2666940''>when</span> <span m=''2667170''>I</span> <span m=''2667240''>have--</span>
  <span m=''2667590''>in</span> <span m=''2667680''>this</span> <span m=''2667830''>case,</span>
  <span m=''2668140''>I</span> <span m=''2668240''>happen</span> <span m=''2668410''>to</span>
  <span m=''2668460''>maybe</span> <span m=''2668730''>get</span> <span m=''2668860''>a</span>
  <span m=''2668900''>vertex</span> <span m=''2669300''>going</span> <span m=''2669480''>to</span>
  <span m=''2669560''>another</span> <span m=''2669770''>vertex.</span> <span m=''2670230''>In</span>
  <span m=''2670320''>general,</span> <span m=''2671050''>probably</span> <span m=''2671370''>get</span>
  <span m=''2671550''>some</span> <span m=''2671740''>vertex</span> <span m=''2672700''>gluing</span>
  <span m=''2672990''>to</span> <span m=''2673090''>some</span> <span m=''2673310''>edge,</span>
  <span m=''2674310''>and</span> <span m=''2674770''>maybe</span> <span m=''2675110''>vice</span>
  <span m=''2675370''>versa.</span> </p><p><span m=''2676050''>But if I can</span>
  <span m=''2676170''>figure</span> <span m=''2676660''>out</span> <span m=''2676810''>exactly</span>
  <span m=''2677310''>what</span> <span m=''2677470''>that</span> <span m=''2677630''>pattern</span>
  <span m=''2678000''>is,</span> <span m=''2678200''>I</span> <span m=''2678280''>can</span>
  <span m=''2678450''>figure</span> <span m=''2678650''>out</span> <span m=''2678750''>the</span>
  <span m=''2678830''>label</span> <span m=''2679320''>of</span> <span m=''2679440''>these</span>
  <span m=''2679670''>guys,</span> <span m=''2682660''>because</span> <span m=''2683740''>I</span>
  <span m=''2683840''>know</span> <span m=''2684070''>exactly</span> <span m=''2684410''>what''s</span>
  <span m=''2684570''>happening</span> <span m=''2684950''>there.</span> <span m=''2686280''>So</span>
  <span m=''2686350''>that''s</span> <span m=''2686480''>good.</span> <span m=''2686640''>If</span>
  <span m=''2686760''>it''s</span> <span m=''2687190''>a</span> <span m=''2687240''>vertex</span>
  <span m=''2687710''>to</span> <span m=''2687810''>vertex</span> <span m=''2690340''>edge</span>
  <span m=''2692220''>in</span> <span m=''2692970''>the</span> <span m=''2693260''>gluing</span>
  <span m=''2693670''>tree</span> <span m=''2693910''>like</span> <span m=''2694110''>this,</span>
  <span m=''2694920''>I</span> <span m=''2694990''>can figure out</span> <span m=''2695470''>everything</span>
  <span m=''2696990''>between</span> <span m=''2697680''>that</span> <span m=''2698210''>pair.</span>
  </p><p><span m=''2708486''>Is</span> <span m=''2708870''>that</span> <span m=''2709090''>enough?</span>
  <span m=''2710900''>Almost.</span> <span m=''2717800''>So</span> <span m=''2717950''>if</span>
  <span m=''2718130''>I</span> <span m=''2718210''>have</span> <span m=''2718360''>a</span>
  <span m=''2718400''>leaf</span> <span m=''2719230''>where</span> <span m=''2719350''>this</span>
  <span m=''2719580''>is</span> <span m=''2719710''>a</span> <span m=''2719760''>vertex,</span>
  <span m=''2722070''>which I was</span> <span m=''2722210''>usually</span> <span
  m=''2722510''>denoting</span> <span m=''2722860''>by a</span> <span m=''2723130''>filled</span>
  <span m=''2723490''>circle,</span> <span m=''2726260''>I</span> <span m=''2726380''>have</span>
  <span m=''2726520''>various</span> <span m=''2726880''>degree</span> <span m=''2727150''>2</span>
  <span m=''2727280''>junctions</span> <span m=''2727700''>which</span> <span m=''2727890''>I</span>
  <span m=''2728000''>ignore</span> <span m=''2729210''>until</span> <span m=''2729610''>I</span>
  <span m=''2729680''>get</span> <span m=''2729920''>to</span> <span m=''2730060''>a</span>
  <span m=''2730130''>degree</span> <span m=''2730540''>three</span> <span m=''2730930''>or</span>
  <span m=''2731180''>higher</span> <span m=''2731500''>junction.</span> <span m=''2733600''>Now</span>
  <span m=''2733850''>at</span> <span m=''2734040''>this</span> <span m=''2734330''>place,</span>
  <span m=''2736600''>even</span> <span m=''2736840''>just</span> <span m=''2737030''>looking</span>
  <span m=''2737420''>at</span> <span m=''2737720''>this</span> <span m=''2738045''>dot</span>
  <span m=''2738370''>and</span> <span m=''2738890''>this</span> <span m=''2739150''>dot,</span>
  <span m=''2739625''>I</span> <span m=''2740100''>know</span> <span m=''2740290''>at</span>
  <span m=''2740370''>least</span> <span m=''2740670''>one</span> <span m=''2740840''>of</span>
  <span m=''2740900''>them</span> <span m=''2740990''>must</span> <span m=''2741240''>be
  a</span> <span m=''2741350''>vertex.</span> <span m=''2741830''>Because</span> <span
  m=''2742010''>I</span> <span m=''2742070''>can''t</span> <span m=''2742320''>glue</span>
  <span m=''2742440''>two</span> <span m=''2742720''>edges</span> <span m=''2743070''>together</span>
  <span m=''2743490''>plus</span> <span m=''2743780''>other</span> <span m=''2744010''>stuff.</span>
  <span m=''2745440''>I</span> <span m=''2745530''>can</span> <span m=''2745710''>glue</span>
  <span m=''2745830''>at</span> <span m=''2745910''>most</span> <span m=''2746190''>one</span>
  <span m=''2746370''>edge.</span> </p><p><span m=''2746610''>So</span> <span m=''2746690''>maybe</span>
  <span m=''2747000''>this</span> <span m=''2747180''>one''s</span> <span m=''2747330''>an</span>
  <span m=''2747430''>edge,</span> <span m=''2747650''>like</span> <span m=''2747850''>in</span>
  <span m=''2747960''>the</span> <span m=''2748050''>picture</span> <span m=''2748810''>that</span>
  <span m=''2748930''>we</span> <span m=''2749010''>did</span> <span m=''2749130''>before.</span>
  <span m=''2750360''>But</span> <span m=''2750590''>one</span> <span m=''2750780''>of</span>
  <span m=''2750830''>them</span> <span m=''2750950''>has</span> <span m=''2751130''>to</span>
  <span m=''2751210''>be a</span> <span m=''2751320''>vertex.</span> <span m=''2751830''>And</span>
  <span m=''2752010''>then</span> <span m=''2752770''>I</span> <span m=''2752940''>can</span>
  <span m=''2753120''>figure</span> <span m=''2753410''>out</span> <span m=''2753520''>exactly</span>
  <span m=''2753910''>what''s</span> <span m=''2754060''>happening</span> <span m=''2754450''>there,</span>
  <span m=''2754770''>because</span> <span m=''2754970''>I</span> <span m=''2755010''>have</span>
  <span m=''2755160''>this</span> <span m=''2755300''>vertex</span> <span m=''2755650''>to</span>
  <span m=''2755730''>vertex</span> <span m=''2756510''>thing.</span> </p><p><span
  m=''2756720''>And</span> <span m=''2756820''>I</span> <span m=''2756880''>know</span>
  <span m=''2757140''>the</span> <span m=''2757240''>labels.</span> <span m=''2757770''>I</span>
  <span m=''2757840''>know</span> <span m=''2758050''>this</span> <span m=''2758240''>is</span>
  <span m=''2758420''>V5</span> <span m=''2759180''>and</span> <span m=''2759310''>this</span>
  <span m=''2759480''>is</span> <span m=''2759650''>V13,</span> <span m=''2761160''>whatever.</span>
  <span m=''2761970''>I</span> <span m=''2762150''>know</span> <span m=''2762350''>exactly</span>
  <span m=''2762750''>what''s</span> <span m=''2762890''>happening</span> <span m=''2763210''>on</span>
  <span m=''2763280''>the</span> <span m=''2763360''>right</span> <span m=''2763590''>side,</span>
  <span m=''2763980''>I</span> <span m=''2764050''>measure</span> <span m=''2764420''>backwards,</span>
  <span m=''2764950''>I</span> <span m=''2765020''>know</span> <span m=''2765150''>exactly</span>
  <span m=''2765450''>what''s</span> <span m=''2765560''>happening</span> <span m=''2766010''>on
  the left side and</span> <span m=''2766290''>who''s</span> <span m=''2766490''>going</span>
  <span m=''2766720''>to</span> <span m=''2766790''>what.</span> <span m=''2767770''>So</span>
  <span m=''2767880''>that</span> <span m=''2767970''>determines</span> <span m=''2768400''>everything.</span>
  </p><p><span m=''2770350''>The</span> <span m=''2770450''>problem</span> <span m=''2770870''>is</span>
  <span m=''2771690''>when</span> <span m=''2771970''>I</span> <span m=''2772050''>have</span>
  <span m=''2773230''>an</span> <span m=''2773380''>edge</span> <span m=''2773720''>here,</span>
  <span m=''2775910''>because</span> <span m=''2775990''>then</span> <span m=''2776150''>I</span>
  <span m=''2776210''>don''t</span> <span m=''2776430''>know</span> <span m=''2776710''>where</span>
  <span m=''2776970''>it</span> <span m=''2777020''>is</span> <span m=''2777440''>along</span>
  <span m=''2777700''>the</span> <span m=''2777810''>edge.</span> <span m=''2778370''>I</span>
  <span m=''2778450''>can''t</span> <span m=''2778670''>measure</span> <span m=''2778910''>lengths</span>
  <span m=''2779190''>anymore,</span> <span m=''2780610''>somewhere</span> <span m=''2781030''>in</span>
  <span m=''2781090''>the</span> <span m=''2781160''>middle</span> <span m=''2781390''>of</span>
  <span m=''2781490''>the</span> <span m=''2781610''>edge.</span> <span m=''2784890''>And</span>
  <span m=''2785060''>indeed,</span> <span m=''2785980''>if</span> <span m=''2786190''>I</span>
  <span m=''2786280''>have</span> <span m=''2788360''>something</span> <span m=''2788690''>like</span>
  <span m=''2788890''>this,</span> <span m=''2793010''>where</span> <span m=''2793220''>all</span>
  <span m=''2793580''>of</span> <span m=''2793710''>these</span> <span m=''2794310''>angles--</span>
  <span m=''2794750''>I</span> <span m=''2794820''>mean</span> <span m=''2794990''>this</span>
  <span m=''2795210''>for</span> <span m=''2795330''>example</span> <span m=''2795690''>is</span>
  <span m=''2795820''>in</span> <span m=''2795920''>a</span> <span m=''2795990''>convex</span>
  <span m=''2796380''>polygon,</span> <span m=''2797520''>this</span> <span m=''2797730''>could</span>
  <span m=''2797860''>be</span> <span m=''2798700''>a</span> <span m=''2798840''>perimeter</span>
  <span m=''2799210''>halving--</span> <span m=''2801030''>and</span> <span m=''2801340''>it''s</span>
  <span m=''2801490''>not</span> <span m=''2801810''>determined</span> <span m=''2802770''>what''s</span>
  <span m=''2802950''>happening</span> <span m=''2803310''>here</span> <span m=''2803520''>because</span>
  <span m=''2803960''>this</span> <span m=''2804130''>is</span> <span m=''2804230''>a</span>
  <span m=''2804300''>rolling</span> <span m=''2804590''>belt.</span> <span m=''2806860''>I''ll
  show</span> <span m=''2807090''>you</span> <span m=''2807240''>how</span> <span
  m=''2807580''>undetermined</span> <span m=''2808050''>it</span> <span m=''2808160''>is.</span>
  </p><p><span m=''2808730''>Suppose</span> <span m=''2809080''>you</span> <span m=''2809170''>have</span>
  <span m=''2809580''>a</span> <span m=''2809660''>bunch</span> <span m=''2809950''>of</span>
  <span m=''2810000''>vertices</span> <span m=''2810490''>like</span> <span m=''2810670''>this,</span>
  <span m=''2812110''>and</span> <span m=''2812350''>then</span> <span m=''2813710''>some</span>
  <span m=''2813950''>vertices</span> <span m=''2815880''>like</span> <span m=''2816040''>this.</span>
  <span m=''2818690''>Depending</span> <span m=''2819170''>on</span> <span m=''2819320''>where</span>
  <span m=''2819720''>I</span> <span m=''2820190''>bend</span> <span m=''2820430''>around</span>
  <span m=''2820830''>for</span> <span m=''2821010''>E5,</span> <span m=''2822970''>these</span>
  <span m=''2823250''>guys</span> <span m=''2823660''>could</span> <span m=''2823830''>be</span>
  <span m=''2823960''>here.</span> <span m=''2824950''>They</span> <span m=''2825090''>could</span>
  <span m=''2825380''>be</span> <span m=''2825710''>here,</span> <span m=''2826380''>or</span>
  <span m=''2826530''>here,</span> <span m=''2827020''>or</span> <span m=''2827130''>here.</span>
  <span m=''2827980''>They</span> <span m=''2828100''>could</span> <span m=''2828290''>be</span>
  <span m=''2828890''>in</span> <span m=''2829140''>the</span> <span m=''2829250''>middle</span>
  <span m=''2830980''>straddling</span> <span m=''2831570''>this.</span> </p><p><span
  m=''2832720''>In</span> <span m=''2832810''>fact,</span> <span m=''2833020''>there</span>
  <span m=''2833260''>are</span> <span m=''2833360''>about</span> <span m=''2835010''>n</span>
  <span m=''2835230''>squared</span> <span m=''2836430''>different</span> <span m=''2836720''>places</span>
  <span m=''2837720''>where</span> <span m=''2837920''>these</span> <span m=''2838140''>guys</span>
  <span m=''2838350''>could</span> <span m=''2838540''>be,</span> <span m=''2838750''>relative</span>
  <span m=''2839200''>to</span> <span m=''2839300''>these</span> <span m=''2839520''>guys.</span>
  <span m=''2840780''>Because</span> <span m=''2840860''>there''s</span> <span m=''2840980''>going</span>
  <span m=''2841110''>to</span> <span m=''2841170''>be</span> <span m=''2841360''>n</span>
  <span m=''2841590''>transitions</span> <span m=''2842240''>from--</span> <span m=''2842990''>if</span>
  <span m=''2843180''>this</span> <span m=''2843370''>is</span> <span m=''2843510''>n</span>
  <span m=''2844370''>and</span> <span m=''2844590''>this</span> <span m=''2844760''>is</span>
  <span m=''2844870''>n--</span> <span m=''2846220''>n</span> <span m=''2846410''>transitions</span>
  <span m=''2846900''>from</span> <span m=''2847110''>this</span> <span m=''2847320''>versus</span>
  <span m=''2847650''>that</span> <span m=''2847920''>guy,</span> <span m=''2848500''>then</span>
  <span m=''2848670''>n</span> <span m=''2848840''>transitions</span> <span m=''2849400''>from</span>
  <span m=''2849750''>these</span> <span m=''2850050''>versus</span> <span m=''2850370''>that</span>
  <span m=''2850660''>guy,</span> <span m=''2850880''>n</span> <span m=''2851070''>transitions</span>
  <span m=''2851960''>versus</span> <span m=''2852240''>that</span> <span m=''2852450''>guy,</span>
  <span m=''2852990''>total</span> <span m=''2853320''>of about</span> <span m=''2853660''>n</span>
  <span m=''2853800''>squared.</span> <span m=''2855530''>Actually</span> <span m=''2855790''>if</span>
  <span m=''2856110''>this</span> <span m=''2856280''>is</span> <span m=''2856380''>n</span>
  <span m=''2856540''>and this</span> <span m=''2856610''>is</span> <span m=''2856690''>n,
  it''s</span> <span m=''2857110''>exactly</span> <span m=''2857520''>n</span> <span
  m=''2857660''>squared.</span> </p><p><span m=''2859440''>So</span> <span m=''2859530''>we''re</span>
  <span m=''2859610''>not</span> <span m=''2859790''>quite</span> <span m=''2860010''>done,</span>
  <span m=''2860910''>but</span> <span m=''2861180''>I</span> <span m=''2861260''>claim</span>
  <span m=''2861690''>that</span> <span m=''2861860''>there''s</span> <span m=''2862020''>really</span>
  <span m=''2862300''>only</span> <span m=''2863220''>order</span> <span m=''2863470''>n</span>
  <span m=''2863630''>squared</span> <span m=''2863920''>left.</span> <span m=''2864220''>It''s</span>
  <span m=''2864350''>always</span> <span m=''2864640''>from</span> <span m=''2864810''>the</span>
  <span m=''2864900''>rolling</span> <span m=''2865200''>belts.</span> <span m=''2866020''>We</span>
  <span m=''2866220''>know</span> <span m=''2866360''>from</span> <span m=''2866540''>last</span>
  <span m=''2866800''>time</span> <span m=''2866960''>there''s</span> <span m=''2867150''>at</span>
  <span m=''2867230''>most</span> <span m=''2867530''>three</span> <span m=''2868350''>rolling</span>
  <span m=''2868670''>belts,</span> <span m=''2871370''>so</span> <span m=''2871790''>at</span>
  <span m=''2871950''>most</span> <span m=''2872210''>quadratic</span> <span m=''2872680''>per</span>
  <span m=''2872840''>belt.</span> <span m=''2874050''>So</span> <span m=''2875270''>total</span>
  <span m=''2875600''>outcome</span> <span m=''2876000''>is</span> <span m=''2876930''>polynomial</span>
  <span m=''2879200''>for</span> <span m=''2879420''>what''s</span> <span m=''2879660''>left,</span>
  <span m=''2880050''>what</span> <span m=''2880140''>we</span> <span m=''2880250''>haven''t</span>
  <span m=''2880570''>specified,</span> <span m=''2881220''>for</span> <span m=''2881340''>how</span>
  <span m=''2881550''>the</span> <span m=''2882120''>degree</span> <span m=''2882380''>2</span>
  <span m=''2882500''>vertices</span> <span m=''2882980''>behave.</span> </p><p><span
  m=''2883520''>These</span> <span m=''2883570''>are</span> <span m=''2883690''>all</span>
  <span m=''2883920''>degree</span> <span m=''2884170''>2</span> <span m=''2884310''>junctions.</span>
  <span m=''2885710''>It''s</span> <span m=''2885990''>here,</span> <span m=''2886360''>or</span>
  <span m=''2886710''>they''re</span> <span m=''2886870''>here,</span> <span m=''2887870''>we</span>
  <span m=''2887990''>don''t</span> <span m=''2888120''>know.</span> <span m=''2889676''>So</span>
  <span m=''2890120''>if</span> <span m=''2890180''>you</span> <span m=''2890320''>want</span>
  <span m=''2890490''>to</span> <span m=''2890530''>get</span> <span m=''2890680''>the</span>
  <span m=''2890760''>full</span> <span m=''2890970''>specification</span> <span m=''2891660''>of
  what''s</span> <span m=''2891740''>where,</span> <span m=''2893040''>you</span>
  <span m=''2893180''>do</span> <span m=''2893370''>all</span> <span m=''2893600''>this</span>
  <span m=''2894330''>work.</span> <span m=''2894820''>And</span> <span m=''2895080''>then</span>
  <span m=''2895220''>for</span> <span m=''2895320''>the</span> <span m=''2895430''>degree</span>
  <span m=''2895700''>two</span> <span m=''2895820''>junctions,</span> <span m=''2896240''>you</span>
  <span m=''2896330''>have</span> <span m=''2896430''>to</span> <span m=''2896530''>deal</span>
  <span m=''2896730''>with</span> <span m=''2896850''>the</span> <span m=''2896950''>rolling</span>
  <span m=''2897220''>belts.</span> </p><p><span m=''2898810''>The way</span> <span
  m=''2898920''>to</span> <span m=''2899020''>prove</span> <span m=''2899240''>this</span>
  <span m=''2899460''>is</span> <span m=''2899560''>say,</span> <span m=''2899750''>well,</span>
  <span m=''2900170''>if</span> <span m=''2900270''>I</span> <span m=''2900330''>have</span>
  <span m=''2900520''>a</span> <span m=''2900920''>leaf</span> <span m=''2901170''>that''s</span>
  <span m=''2901350''>a</span> <span m=''2901390''>vertex,</span> <span m=''2902360''>I</span>
  <span m=''2902500''>can</span> <span m=''2902670''>get</span> <span m=''2902800''>rid</span>
  <span m=''2902950''>of</span> <span m=''2903060''>it</span> <span m=''2903190''>and</span>
  <span m=''2903330''>induct.</span> <span m=''2904510''>In</span> <span m=''2904650''>the</span>
  <span m=''2904790''>end,</span> <span m=''2905100''>I''ll</span> <span m=''2905190''>have</span>
  <span m=''2905430''>at</span> <span m=''2905510''>most</span> <span m=''2906030''>four</span>
  <span m=''2906520''>leaves</span> <span m=''2907020''>because</span> <span m=''2907250''>there''s</span>
  <span m=''2907430''>at</span> <span m=''2907520''>most</span> <span m=''2907750''>four</span>
  <span m=''2908025''>fold points.</span> <span m=''2909440''>So I have a</span> <span
  m=''2909730''>constant</span> <span m=''2910200''>number of</span> <span m=''2910490''>leaves.</span>
  <span m=''2912810''>You look</span> <span m=''2913230''>at</span> <span m=''2913290''>each</span>
  <span m=''2913460''>belt,</span> <span m=''2914000''>each</span> <span m=''2914220''>of</span>
  <span m=''2914280''>them is</span> <span m=''2914520''>quadratic</span> <span m=''2915840''>and</span>
  <span m=''2917410''>polynomial.</span> </p><p><span m=''2920020''>If</span> <span
  m=''2920230''>you</span> <span m=''2920390''>work</span> <span m=''2920690''>out</span>
  <span m=''2921070''>the</span> <span m=''2921170''>bounds</span> <span m=''2921530''>here--</span>
  <span m=''2921700''>we''ve</span> <span m=''2921870''>tried</span> <span m=''2922140''>to</span>
  <span m=''2922200''>be</span> <span m=''2922340''>a</span> <span m=''2922400''>little</span>
  <span m=''2922590''>more</span> <span m=''2922760''>precise--</span> <span m=''2923670''>you</span>
  <span m=''2923850''>could</span> <span m=''2924020''>prove</span> <span m=''2924350''>an</span>
  <span m=''2924430''>overall</span> <span m=''2924880''>bound</span> <span m=''2925240''>of</span>
  <span m=''2925640''>n</span> <span m=''2925980''>to</span> <span m=''2926100''>the</span>
  <span m=''2926270''>2L</span> <span m=''2927480''>minus</span> <span m=''2928550''>2</span>
  <span m=''2929880''>for</span> <span m=''2930120''>L</span> <span m=''2930290''>leaves.</span>
  <span m=''2933220''>And</span> <span m=''2933330''>we</span> <span m=''2933420''>have</span>
  <span m=''2933540''>slightly</span> <span m=''2933890''>better</span> <span m=''2934120''>bounds</span>
  <span m=''2934380''>for</span> <span m=''2934480''>L</span> <span m=''2934640''>equals</span>
  <span m=''2934890''>4</span> <span m=''2936330''>and</span> <span m=''2936930''>L</span>
  <span m=''2937110''>equals</span> <span m=''2937410''>3,</span> <span m=''2938010''>but</span>
  <span m=''2939780''>that''s</span> <span m=''2940010''>pretty</span> <span m=''2940160''>good.</span>
  <span m=''2942370''>But</span> <span m=''2943070''>the</span> <span m=''2943290''>proof</span>
  <span m=''2943550''>I</span> <span m=''2943640''>gave</span> <span m=''2943860''>is</span>
  <span m=''2943960''>at</span> <span m=''2944040''>least</span> <span m=''2944440''>n
  to</span> <span m=''2944740''>the</span> <span m=''2944880''>order</span> <span
  m=''2945160''>L.</span> <span m=''2945910''>We</span> <span m=''2946000''>could</span>
  <span m=''2946120''>n</span> <span m=''2946420''>to the</span> <span m=''2946590''>order</span>
  <span m=''2946860''>L</span> <span m=''2947510''>count</span> <span m=''2948080''>different</span>
  <span m=''2948530''>things</span> <span m=''2948760''>here,</span> <span m=''2949770''>and</span>
  <span m=''2950370''>then</span> <span m=''2950610''>some</span> <span m=''2950890''>N
  to</span> <span m=''2951140''>the</span> <span m=''2951240''>constant</span> <span
  m=''2951670''>at</span> <span m=''2951780''>the</span> <span m=''2951870''>end.</span>
  </p><p><span m=''2958200''>This</span> <span m=''2958440''>ends</span> <span m=''2958800''>the</span>
  <span m=''2959090''>combinatorial</span> <span m=''2960020''>part.</span> <span
  m=''2960330''>Now</span> <span m=''2960520''>we''re</span> <span m=''2960610''>going</span>
  <span m=''2960730''>to</span> <span m=''2960780''>get</span> <span m=''2960940''>to</span>
  <span m=''2961020''>algorithms.</span> <span m=''2962820''>So</span> <span m=''2962910''>we''ve</span>
  <span m=''2963070''>proved</span> <span m=''2963940''>all</span> <span m=''2964150''>of</span>
  <span m=''2964240''>these</span> <span m=''2964470''>things.</span> <span m=''2965420''>Exponential</span>
  <span m=''2965940''>upper</span> <span m=''2966150''>and</span> <span m=''2966220''>lower</span>
  <span m=''2966450''>bounds</span> <span m=''2967070''>for</span> <span m=''2967220''>the</span>
  <span m=''2967340''>general</span> <span m=''2967640''>case</span> <span m=''2967960''>and</span>
  <span m=''2968050''>edge-to-edge</span> <span m=''2968540''>case,</span> <span m=''2969290''>and</span>
  <span m=''2969710''>polynomial</span> <span m=''2970270''>for</span> <span m=''2970600''>bounded</span>
  <span m=''2970930''>sharpness,</span> <span m=''2972800''>or</span> <span m=''2973050''>when</span>
  <span m=''2973180''>you</span> <span m=''2973250''>have</span> <span m=''2973530''>a</span>
  <span m=''2974070''>reasonable</span> <span m=''2974440''>number</span> <span m=''2974680''>of</span>
  <span m=''2974800''>leaves</span> <span m=''2975150''>in</span> <span m=''2975310''>your</span>
  <span m=''2975460''>tree.</span> </p><p><span m=''3008300''>I''m</span> <span m=''3008320''>going</span>
  <span m=''3008440''>to</span> <span m=''3008530''>start</span> <span m=''3008980''>with</span>
  <span m=''3010120''>this</span> <span m=''3010990''>edge-to-edge</span> <span m=''3012140''>gluing</span>
  <span m=''3014440''>algorithm.</span> <span m=''3032140''>This</span> <span m=''3032370''>is</span>
  <span m=''3032490''>going</span> <span m=''3032690''>to</span> <span m=''3032820''>use</span>
  <span m=''3033170''>a</span> <span m=''3033360''>technique</span> <span m=''3033900''>called</span>
  <span m=''3034370''>dynamic</span> <span m=''3034730''>programming,</span> <span
  m=''3039350''>which</span> <span m=''3039780''>some</span> <span m=''3040070''>of</span>
  <span m=''3040180''>you have</span> <span m=''3040360''>seen</span> <span m=''3040570''>before,</span>
  <span m=''3041210''>some</span> <span m=''3041510''>of</span> <span m=''3041630''>you</span>
  <span m=''3041690''>haven''t.</span> <span m=''3043590''>It''s a</span> <span m=''3043800''>very</span>
  <span m=''3043970''>simple</span> <span m=''3044270''>idea.</span> <span m=''3045190''>You</span>
  <span m=''3045470''>take</span> <span m=''3045800''>your</span> <span m=''3045970''>problem</span>
  <span m=''3046430''>that</span> <span m=''3046490''>you</span> <span m=''3046600''>want</span>
  <span m=''3046720''>to</span> <span m=''3046770''>solve--</span> <span m=''3047080''>which</span>
  <span m=''3047290''>is</span> <span m=''3047590''>I</span> <span m=''3047690''>have</span>
  <span m=''3047860''>a</span> <span m=''3047900''>polygon--</span> <span m=''3048900''>and</span>
  <span m=''3049120''>you</span> <span m=''3049200''>split</span> <span m=''3049490''>it</span>
  <span m=''3049590''>up</span> <span m=''3049780''>into</span> <span m=''3050240''>sub-problems.</span>
  </p><p><span m=''3052146''>You</span> <span m=''3052580''>solve</span> <span m=''3052840''>each</span>
  <span m=''3053000''>of</span> <span m=''3053060''>the</span> <span m=''3053130''>sub-problems,</span>
  <span m=''3054830''>and</span> <span m=''3055070''>one</span> <span m=''3055260''>of</span>
  <span m=''3055360''>the</span> <span m=''3055440''>sub-problems</span> <span m=''3055970''>is</span>
  <span m=''3056110''>actually</span> <span m=''3056380''>the</span> <span m=''3056480''>whole</span>
  <span m=''3056650''>problem,</span> <span m=''3057570''>and</span> <span m=''3057820''>then</span>
  <span m=''3057920''>you''re</span> <span m=''3058010''>done.</span> <span m=''3059500''>In</span>
  <span m=''3059670''>our</span> <span m=''3059790''>case,</span> <span m=''3061000''>a</span>
  <span m=''3061100''>sub-problem</span> <span m=''3061680''>is</span> <span m=''3061870''>going</span>
  <span m=''3062080''>to</span> <span m=''3062190''>be</span> <span m=''3062310''>some</span>
  <span m=''3062610''>sub-chain</span> <span m=''3064200''>from</span> <span m=''3064420''>one</span>
  <span m=''3064670''>vertex</span> <span m=''3065950''>to</span> <span m=''3066110''>another</span>
  <span m=''3066390''>vertex</span> <span m=''3068320''>of</span> <span m=''3068810''>the</span>
  <span m=''3068980''>polygon.</span> <span m=''3075680''>So</span> <span m=''3075900''>I</span>
  <span m=''3075980''>have</span> <span m=''3076280''>some</span> <span m=''3076480''>polygon,</span>
  <span m=''3078090''>and</span> <span m=''3078480''>I just</span> <span m=''3078640''>look</span>
  <span m=''3078830''>at</span> <span m=''3079150''>some</span> <span m=''3079690''>interval</span>
  <span m=''3080310''>of</span> <span m=''3080440''>the</span> <span m=''3080510''>boundary</span>
  <span m=''3081990''>from</span> <span m=''3083320''>VI</span> <span m=''3084860''>to</span>
  <span m=''3085000''>VJ.</span> </p><p><span m=''3086060''>And</span> <span m=''3086190''>the</span>
  <span m=''3086310''>idea</span> <span m=''3086620''>is,</span> <span m=''3087450''>well</span>
  <span m=''3087590''>suppose</span> <span m=''3088320''>that</span> <span m=''3088450''>VI</span>
  <span m=''3089130''>is</span> <span m=''3089350''>glued</span> <span m=''3089730''>to</span>
  <span m=''3089840''>VJ.</span> <span m=''3091730''>How</span> <span m=''3092080''>many</span>
  <span m=''3092300''>different</span> <span m=''3092590''>ways,</span> <span m=''3093080''>or</span>
  <span m=''3093170''>how</span> <span m=''3093770''>should</span> <span m=''3094010''>I</span>
  <span m=''3094070''>glue</span> <span m=''3094360''>the</span> <span m=''3094480''>part</span>
  <span m=''3094760''>in</span> <span m=''3094890''>between?</span> <span m=''3098540''>How</span>
  <span m=''3098730''>should</span> <span m=''3098890''>I</span> <span m=''3098940''>glue</span>
  <span m=''3099120''>this</span> <span m=''3099410''>into</span> <span m=''3099680''>itself?</span>
  <span m=''3100770''>Because</span> <span m=''3100950''>there''s</span> <span m=''3101290''>no</span>
  <span m=''3101430''>crossings,</span> <span m=''3101930''>there''s</span> <span
  m=''3102090''>going</span> <span m=''3102200''>to</span> <span m=''3102260''>be</span>
  <span m=''3102350''>no</span> <span m=''3102510''>gluings</span> <span m=''3102800''>from</span>
  <span m=''3102940''>inside</span> <span m=''3103200''>to</span> <span m=''3103310''>outside.</span>
  </p><p><span m=''3105900''>So</span> <span m=''3106080''>that''s</span> <span m=''3106290''>the</span>
  <span m=''3106370''>sub-problem.</span> <span m=''3107510''>And</span> <span m=''3107650''>of</span>
  <span m=''3107760''>course</span> <span m=''3108190''>if</span> <span m=''3108440''>I</span>
  <span m=''3108610''>say</span> <span m=''3108940''>from</span> <span m=''3111270''>the</span>
  <span m=''3111390''>interval</span> <span m=''3111660''>from</span> <span m=''3111810''>V1</span>
  <span m=''3112330''>to</span> <span m=''3112770''>V1,</span> <span m=''3113700''>that</span>
  <span m=''3113900''>is</span> <span m=''3114030''>the</span> <span m=''3114130''>entire</span>
  <span m=''3114560''>problem.</span> <span m=''3115500''>Of</span> <span m=''3115560''>course</span>
  <span m=''3115810''>V1</span> <span m=''3116100''>is</span> <span m=''3116220''>glued</span>
  <span m=''3116400''>to</span> <span m=''3116470''>V1.</span> <span m=''3117440''>So</span>
  <span m=''3117570''>in</span> <span m=''3117650''>particular,</span> <span m=''3120230''>the</span>
  <span m=''3120320''>V1</span> <span m=''3120850''>to</span> <span m=''3121020''>V1</span>
  <span m=''3121480''>sub-problem</span> <span m=''3122980''>is</span> <span m=''3123370''>what</span>
  <span m=''3123590''>we</span> <span m=''3123690''>want</span> <span m=''3123850''>to</span>
  <span m=''3123900''>solve.</span> </p><p><span m=''3125740''>So</span> <span m=''3125840''>this</span>
  <span m=''3126150''>is</span> <span m=''3127300''>our</span> <span m=''3127440''>goal.</span>
  <span m=''3129020''>So</span> <span m=''3129120''>I''m</span> <span m=''3129160''>going</span>
  <span m=''3129270''>to</span> <span m=''3129350''>tell</span> <span m=''3129540''>you</span>
  <span m=''3129640''>how</span> <span m=''3129770''>to</span> <span m=''3129840''>solve</span>
  <span m=''3130090''>all</span> <span m=''3130430''>of</span> <span m=''3130510''>these</span>
  <span m=''3130670''>sub-problems,</span> <span m=''3131190''>and</span> <span m=''3131290''>therefore</span>
  <span m=''3131610''>how</span> <span m=''3131710''>to</span> <span m=''3131810''>solve</span>
  <span m=''3132130''>what</span> <span m=''3132240''>we</span> <span m=''3132370''>actually</span>
  <span m=''3132630''>want</span> <span m=''3132770''>to</span> <span m=''3132830''>solve.</span>
  <span m=''3133960''>That''s</span> <span m=''3134160''>dynamic</span> <span m=''3134550''>programming.</span>
  <span m=''3137530''>So</span> <span m=''3137750''>let''s</span> <span m=''3137990''>try</span>
  <span m=''3138150''>to</span> <span m=''3138240''>solve</span> <span m=''3138680''>one</span>
  <span m=''3138890''>of</span> <span m=''3138950''>these</span> <span m=''3139080''>sub-problems,</span>
  <span m=''3140720''>VI</span> <span m=''3141600''>to</span> <span m=''3141760''>VJ.</span>
  <span m=''3143190''>How</span> <span m=''3143500''>are</span> <span m=''3143600''>we</span>
  <span m=''3143610''>going</span> <span m=''3143710''>to</span> <span m=''3143780''>solve</span>
  <span m=''3144080''>it?</span> </p><p><span m=''3147710''>So</span> <span m=''3147930''>I''m</span>
  <span m=''3148230''>going</span> <span m=''3148670''>to</span> <span m=''3150280''>draw</span>
  <span m=''3150770''>a</span> <span m=''3150830''>picture.</span> <span m=''3151900''>It</span>
  <span m=''3152340''>looks</span> <span m=''3152510''>like</span> <span m=''3152710''>this.</span>
  <span m=''3153940''>This</span> <span m=''3154000''>is</span> <span m=''3154170''>now</span>
  <span m=''3154410''>thinking</span> <span m=''3154700''>about</span> <span m=''3154890''>the</span>
  <span m=''3154970''>gluing</span> <span m=''3155310''>tree,</span> <span m=''3155580''>so
  the</span> <span m=''3155680''>polygon''s</span> <span m=''3156120''>on</span> <span
  m=''3156170''>the</span> <span m=''3156310''>outside</span> <span m=''3157710''>here.</span>
  <span m=''3159070''>That''s</span> <span m=''3159770''>one</span> <span m=''3160170''>of
  the</span> <span m=''3160320''>main</span> <span m=''3160520''>reasons</span> <span
  m=''3161090''>gluing</span> <span m=''3161280''>trees</span> <span m=''3161460''>were</span>
  <span m=''3161550''>developed,</span> <span m=''3161960''>just</span> <span m=''3162180''>to</span>
  <span m=''3162410''>describe</span> <span m=''3162970''>this</span> <span m=''3163130''>algorithm.</span>
  <span m=''3163450''>This</span> <span m=''3163580''>algorthim''s</span> <span m=''3163990''>actually</span>
  <span m=''3164240''>quite</span> <span m=''3164440''>old,</span> <span m=''3165540''>1996</span>
  <span m=''3166960''>by</span> <span m=''3167100''>[INAUDIBLE]</span> <span m=''3167630''>and</span>
  <span m=''3167720''>[INAUDIBLE].</span> </p><p><span m=''3169030''>The</span> <span
  m=''3169160''>edge-to-edge</span> <span m=''3169620''>case was</span> <span m=''3169980''>before</span>
  <span m=''3171020''>I</span> <span m=''3171190''>joined</span> <span m=''3171500''>this</span>
  <span m=''3171660''>group.</span> <span m=''3171970''>And</span> <span m=''3172110''>then</span>
  <span m=''3173330''>later</span> <span m=''3173600''>together</span> <span m=''3174020''>we</span>
  <span m=''3174150''>did</span> <span m=''3174590''>the</span> <span m=''3174770''>general</span>
  <span m=''3175110''>case,</span> <span m=''3175470''>unbounded</span> <span m=''3175810''>sharpness,</span>
  <span m=''3176540''>which is what</span> <span m=''3176680''>we''ll</span> <span
  m=''3176780''>do</span> <span m=''3176890''>next.</span> <span m=''3179890''>So</span>
  <span m=''3179990''>this</span> <span m=''3180040''>is</span> <span m=''3180170''>at</span>
  <span m=''3180290''>the</span> <span m=''3180360''>heart</span> <span m=''3180600''>of</span>
  <span m=''3180740''>everything.</span> </p><p><span m=''3181320''>So</span> <span
  m=''3181870''>we</span> <span m=''3181990''>have</span> <span m=''3182120''>VO</span>
  <span m=''3182280''>to</span> <span m=''3182470''>VJ</span> <span m=''3183540''>glued</span>
  <span m=''3183780''>together.</span> <span m=''3184170''>We</span> <span m=''3184260''>want</span>
  <span m=''3184480''>to</span> <span m=''3184530''>know</span> <span m=''3184660''>how</span>
  <span m=''3184830''>to</span> <span m=''3184930''>glue</span> <span m=''3185150''>together</span>
  <span m=''3185510''>the</span> <span m=''3185620''>rest.</span> <span m=''3187620''>Well,</span>
  <span m=''3187810''>maybe</span> <span m=''3188170''>some</span> <span m=''3188390''>vertices</span>
  <span m=''3188890''>get glued in</span> <span m=''3189380''>here</span> <span m=''3190740''>in</span>
  <span m=''3190880''>addition</span> <span m=''3191290''>to</span> <span m=''3191390''>VI
  and</span> <span m=''3191750''>VJ,</span> <span m=''3192620''>maybe</span> <span
  m=''3192960''>not.</span> <span m=''3195890''>Let''s</span> <span m=''3196100''>think</span>
  <span m=''3196260''>about</span> <span m=''3196480''>what</span> <span m=''3196620''>gets</span>
  <span m=''3196860''>glued</span> <span m=''3197030''>to</span> <span m=''3197110''>this</span>
  <span m=''3197300''>edge.</span> </p><p><span m=''3198610''>There''s</span> <span
  m=''3198760''>the</span> <span m=''3198900''>edge</span> <span m=''3199370''>from</span>
  <span m=''3199610''>VI</span> <span m=''3200320''>to</span> <span m=''3200960''>VI
  plus</span> <span m=''3201140''>1.</span> <span m=''3201770''>And</span> <span m=''3201930''>this</span>
  <span m=''3202070''>is</span> <span m=''3202180''>an</span> <span m=''3202260''>edge-to-edge</span>
  <span m=''3202770''>gluing,</span> <span m=''3203100''>so</span> <span m=''3203260''>what</span>
  <span m=''3203420''>gets</span> <span m=''3203620''>glued</span> <span m=''3203830''>there</span>
  <span m=''3204110''>is</span> <span m=''3204310''>an</span> <span m=''3204400''>actual</span>
  <span m=''3204790''>edge.</span> <span m=''3207790''>What</span> <span m=''3208140''>edge</span>
  <span m=''3208320''>could</span> <span m=''3208420''>it</span> <span m=''3208480''>be?</span>
  <span m=''3208820''>Some</span> <span m=''3209130''>edge</span> <span m=''3209570''>over</span>
  <span m=''3209750''>here,</span> <span m=''3211130''>I</span> <span m=''3211350''>don''t</span>
  <span m=''3211490''>know</span> <span m=''3211600''>which</span> <span m=''3211770''>one.</span>
  <span m=''3213256''>The</span> <span m=''3213670''>power</span> <span m=''3213890''>of</span>
  <span m=''3213970''>the</span> <span m=''3214030''>dynamic</span> <span m=''3214420''>programming</span>
  <span m=''3214950''>is</span> <span m=''3215040''>you</span> <span m=''3215160''>don''t</span>
  <span m=''3215300''>need</span> <span m=''3215480''>to</span> <span m=''3215580''>know.</span>
  </p><p><span m=''3216330''>It''s</span> <span m=''3216520''>some</span> <span m=''3216740''>edge,</span>
  <span m=''3217560''>VK,</span> <span m=''3217995''>VK</span> <span m=''3218430''>plus</span>
  <span m=''3218690''>1</span> <span m=''3220070''>gets</span> <span m=''3220300''>glued</span>
  <span m=''3221230''>there.</span> <span m=''3224920''>There''s</span> <span m=''3225030''>only</span>
  <span m=''3225220''>one</span> <span m=''3225440''>of</span> <span m=''3225530''>them,</span>
  <span m=''3226680''>it''s</span> <span m=''3227040''>out</span> <span m=''3227160''>there</span>
  <span m=''3227300''>somewhere.</span> <span m=''3227710''>It has</span> <span m=''3227950''>to
  have</span> <span m=''3228130''>matching</span> <span m=''3228430''>edge</span>
  <span m=''3228590''>length,</span> <span m=''3229480''>but</span> <span m=''3229620''>there</span>
  <span m=''3229730''>could</span> <span m=''3229880''>be</span> <span m=''3229990''>many</span>
  <span m=''3230200''>choices,</span> <span m=''3230830''>all of</span> <span m=''3231070''>which</span>
  <span m=''3231280''>have</span> <span m=''3231370''>matching</span> <span m=''3231710''>edge
  length.</span> <span m=''3232060''>Maybe</span> <span m=''3232330''>all</span> <span
  m=''3232440''>the edge</span> <span m=''3232600''>lengths</span> <span m=''3232780''>are</span>
  <span m=''3232910''>the</span> <span m=''3233000''>same,</span> <span m=''3234220''>but</span>
  <span m=''3235060''>there''s</span> <span m=''3235320''>at</span> <span m=''3235420''>most</span>
  <span m=''3237100''>n</span> <span m=''3237320''>choices</span> <span m=''3241120''>for</span>
  <span m=''3242600''>that</span> <span m=''3242790''>edge.</span> <span m=''3245550''>It''s</span>
  <span m=''3245690''>actually</span> <span m=''3246250''>at</span> <span m=''3246580''>most</span>
  <span m=''3246893''>J</span> <span m=''3246920''>minus</span> <span m=''3247060''>I</span>
  <span m=''3247550''>choices</span> <span m=''3248040''>plus</span> <span m=''3248250''>1.</span>
  <span m=''3248940''>But</span> <span m=''3250160''>there''s</span> <span m=''3250310''>at</span>
  <span m=''3250370''>most</span> <span m=''3250610''>n</span> <span m=''3250770''>edges</span>
  <span m=''3251180''>in</span> <span m=''3251320''>here,</span> <span m=''3252790''>so</span>
  <span m=''3252980''>there''s</span> <span m=''3253110''>at</span> <span m=''3253170''>most</span>
  <span m=''3253440''>n</span> <span m=''3253650''>different</span> <span m=''3253880''>possibilities.</span>
  <span m=''3254590''>Just</span> <span m=''3254760''>try</span> <span m=''3255010''>them</span>
  <span m=''3255160''>all.</span> <span m=''3256820''>Think</span> <span m=''3256990''>about</span>
  <span m=''3257250''>all</span> <span m=''3257470''>of</span> <span m=''3257540''>them.</span>
  </p><p><span m=''3258640''>I</span> <span m=''3258750''>haven''t</span> <span m=''3259030''>said</span>
  <span m=''3259220''>here</span> <span m=''3259430''>whether</span> <span m=''3259650''>I''m</span>
  <span m=''3259750''>doing--</span> <span m=''3260300''>or</span> <span m=''3260590''>I</span>
  <span m=''3260710''>have?</span> <span m=''3260910''>I</span> <span m=''3261210''>guess</span>
  <span m=''3261400''>I''ve</span> <span m=''3261480''>been</span> <span m=''3261620''>pointing</span>
  <span m=''3261890''>here.</span> <span m=''3263170''>I</span> <span m=''3263300''>really</span>
  <span m=''3263620''>want</span> <span m=''3263760''>to</span> <span m=''3263820''>do</span>
  <span m=''3263910''>both</span> <span m=''3264140''>of</span> <span m=''3264210''>these</span>
  <span m=''3264370''>algorithms</span> <span m=''3264740''>at</span> <span m=''3264840''>once,</span>
  <span m=''3265170''>but</span> <span m=''3265300''>I''ll</span> <span m=''3265500''>start</span>
  <span m=''3265720''>with</span> <span m=''3265800''>this</span> <span m=''3265970''>one,</span>
  <span m=''3267000''>which</span> <span m=''3267210''>is</span> <span m=''3267340''>just</span>
  <span m=''3267920''>find</span> <span m=''3268210''>all</span> <span m=''3268420''>the</span>
  <span m=''3268490''>gluings</span> <span m=''3268920''>in</span> <span m=''3269000''>exponential</span>
  <span m=''3269530''>time,</span> <span m=''3270270''>which</span> <span m=''3270430''>is</span>
  <span m=''3270530''>optimal</span> <span m=''3271020''>in</span> <span m=''3271070''>the</span>
  <span m=''3271140''>worst</span> <span m=''3271360''>case</span> <span m=''3271610''>because</span>
  <span m=''3271780''>there</span> <span m=''3271880''>can</span> <span m=''3272010''>be</span>
  <span m=''3272120''>exponentially</span> <span m=''3272660''>many</span> <span m=''3272930''>outputs.</span>
  <span m=''3277330''>So</span> <span m=''3277540''>try</span> <span m=''3277920''>all</span>
  <span m=''3278380''>n</span> <span m=''3278590''>choices</span> <span m=''3279120''>for</span>
  <span m=''3279280''>VK</span> <span m=''3279430''>VK</span> <span m=''3279970''>plus</span>
  <span m=''3280250''>1.</span> </p><p><span m=''3281020''>What</span> <span m=''3281180''>happens</span>
  <span m=''3281520''>when</span> <span m=''3281640''>I</span> <span m=''3281700''>do</span>
  <span m=''3281860''>one</span> <span m=''3282020''>of</span> <span m=''3282120''>them?</span>
  <span m=''3283410''>I might</span> <span m=''3283600''>choose</span> <span m=''3283850''>one</span>
  <span m=''3284070''>of them.</span> <span m=''3289570''>Well,</span> <span m=''3290010''>the</span>
  <span m=''3290150''>new</span> <span m=''3290320''>picture</span> <span m=''3290800''>will</span>
  <span m=''3291030''>be--</span> <span m=''3298270''>so</span> <span m=''3298815''>the</span>
  <span m=''3299170''>topological</span> <span m=''3299850''>picture</span> <span
  m=''3300190''>is</span> <span m=''3300540''>I</span> <span m=''3300610''>still</span>
  <span m=''3300900''>have</span> <span m=''3301800''>VI</span> <span m=''3302610''>glued</span>
  <span m=''3303100''>to</span> <span m=''3303220''>VJ.</span> </p><p><span m=''3306000''>Then
  I</span> <span m=''3306110''>also</span> <span m=''3306420''>have</span> <span m=''3307610''>here</span>
  <span m=''3307870''>VK</span> <span m=''3309630''>and</span> <span m=''3311500''>VI</span>
  <span m=''3311690''>plus 1</span> <span m=''3312300''>glued</span> <span m=''3312510''>together.</span>
  <span m=''3313020''>And</span> <span m=''3313320''>I</span> <span m=''3313400''>have</span>
  <span m=''3313600''>VI</span> <span m=''3313770''>also</span> <span m=''3314360''>glued</span>
  <span m=''3314690''>to</span> <span m=''3315770''>VK</span> <span m=''3316400''>plus</span>
  <span m=''3316670''>1.</span> <span m=''3318410''>Now it''s</span> <span m=''3318680''>possible</span>
  <span m=''3319130''>actually</span> <span m=''3319360''>VK</span> <span m=''3319630''>plus</span>
  <span m=''3319820''>1</span> <span m=''3319950''>and</span> <span m=''3320010''>VJ</span>
  <span m=''3320130''>are</span> <span m=''3320360''>the</span> <span m=''3320480''>same</span>
  <span m=''3320750''>thing,</span> <span m=''3320990''>in</span> <span m=''3321050''>which</span>
  <span m=''3321220''>case</span> <span m=''3321420''>there''s</span> <span m=''3321570''>no</span>
  <span m=''3321720''>loop</span> <span m=''3321950''>here.</span> </p><p><span m=''3322910''>And</span>
  <span m=''3323060''>that''s</span> <span m=''3323270''>the</span> <span m=''3323350''>case</span>
  <span m=''3323570''>when</span> <span m=''3323740''>no</span> <span m=''3323900''>extra</span>
  <span m=''3324150''>vertex</span> <span m=''3324530''>got</span> <span m=''3324680''>glued</span>
  <span m=''3324890''>in</span> <span m=''3325010''>there.</span> <span m=''3325710''>But</span>
  <span m=''3326270''>this</span> <span m=''3326530''>is</span> <span m=''3326750''>the</span>
  <span m=''3326820''>generic</span> <span m=''3327210''>situation.</span> <span m=''3329266''>If</span>
  <span m=''3329730''>this</span> <span m=''3329880''>is</span> <span m=''3329990''>link</span>
  <span m=''3330160''>0,</span> <span m=''3330500''>then</span> <span m=''3330650''>these</span>
  <span m=''3330820''>guys</span> <span m=''3331010''>are</span> <span m=''3331050''>the</span>
  <span m=''3331150''>same.</span> </p><p><span m=''3333140''>So</span> <span m=''3333410''>really</span>
  <span m=''3333740''>what</span> <span m=''3333900''>I</span> <span m=''3333960''>have</span>
  <span m=''3334240''>now</span> <span m=''3334490''>are</span> <span m=''3334670''>two</span>
  <span m=''3334930''>different</span> <span m=''3335370''>sub-problems.</span> <span
  m=''3336530''>There''s</span> <span m=''3336690''>this</span> <span m=''3336880''>thing,</span>
  <span m=''3337150''>which</span> <span m=''3337360''>is</span> <span m=''3337570''>VI</span>
  <span m=''3338130''>plus</span> <span m=''3338440''>1,</span> <span m=''3339706''>dot,</span>
  <span m=''3340130''>dot,</span> <span m=''3340390''>VK.</span> <span m=''3341520''>And</span>
  <span m=''3341710''>there''s</span> <span m=''3341850''>this</span> <span m=''3342050''>one</span>
  <span m=''3342250''>which</span> <span m=''3342440''>is</span> <span m=''3342610''>VK</span>
  <span m=''3343080''>plus</span> <span m=''3343370''>1</span> <span m=''3344224''>dot,</span>
  <span m=''3344651''>dot,</span> <span m=''3345410''>VJ.</span> <span m=''3348760''>The</span>
  <span m=''3348890''>idea</span> <span m=''3349130''>with</span> <span m=''3349250''>the</span>
  <span m=''3349340''>sub-problems</span> <span m=''3350090''>is</span> <span m=''3350370''>to</span>
  <span m=''3350570''>solve</span> <span m=''3350970''>the</span> <span m=''3351140''>sub-problems</span>
  <span m=''3351520''>in</span> <span m=''3351720''>order</span> <span m=''3352120''>by</span>
  <span m=''3352360''>increasing</span> <span m=''3352930''>chain</span> <span m=''3353240''>length.</span>
  </p><p><span m=''3354540''>So</span> <span m=''3354700''>start</span> <span m=''3355000''>with</span>
  <span m=''3355120''>very</span> <span m=''3355330''>short</span> <span m=''3355580''>ones.</span>
  <span m=''3357020''>And I</span> <span m=''3357080''>saw</span> <span m=''3357290''>longer</span>
  <span m=''3357700''>and</span> <span m=''3357760''>longer</span> <span m=''3358040''>ones</span>
  <span m=''3358240''>using</span> <span m=''3358660''>the</span> <span m=''3358750''>previous</span>
  <span m=''3359120''>results.</span> <span m=''3359860''>If</span> <span m=''3360050''>I''ve</span>
  <span m=''3360190''>already</span> <span m=''3360630''>computed</span> <span m=''3361180''>the</span>
  <span m=''3361280''>answers</span> <span m=''3362160''>to</span> <span m=''3363110''>VK</span>
  <span m=''3363290''>plus</span> <span m=''3363500''>1</span> <span m=''3363640''>to</span>
  <span m=''3363700''>VJ</span> <span m=''3364100''>because</span> <span m=''3364380''>that</span>
  <span m=''3364560''>is</span> <span m=''3364650''>smaller</span> <span m=''3365090''>than</span>
  <span m=''3365200''>the</span> <span m=''3365310''>original--</span> <span m=''3366000''>look,</span>
  <span m=''3366270''>there''s</span> <span m=''3366350''>two</span> <span m=''3366550''>edges</span>
  <span m=''3366900''>fewer</span> <span m=''3367330''>at</span> <span m=''3367420''>least.</span>
  <span m=''3368480''>This</span> <span m=''3368660''>thing</span> <span m=''3368800''>is</span>
  <span m=''3368900''>at</span> <span m=''3368980''>least</span> <span m=''3369190''>2</span>
  <span m=''3369330''>smaller</span> <span m=''3369750''>than</span> <span m=''3369890''>the</span>
  <span m=''3369990''>original</span> <span m=''3370350''>chain</span> <span m=''3371130''>because</span>
  <span m=''3371250''>here''s</span> <span m=''3371440''>two</span> <span m=''3371530''>edges.</span>
  </p><p><span m=''3372720''>So</span> <span m=''3372860''>I</span> <span m=''3372960''>wanted</span>
  <span m=''3373290''>to</span> <span m=''3373370''>solve</span> <span m=''3373620''>VI</span>
  <span m=''3373780''>to</span> <span m=''3373990''>VJ.</span> <span m=''3374520''>I</span>
  <span m=''3374630''>guessed</span> <span m=''3375240''>what</span> <span m=''3375560''>VK</span>
  <span m=''3376050''>to</span> <span m=''3376200''>VK</span> <span m=''3376360''>plus</span>
  <span m=''3376590''>1</span> <span m=''3377280''>was,</span> <span m=''3377690''>meaning</span>
  <span m=''3378080''>I</span> <span m=''3378240''>tried</span> <span m=''3378500''>all</span>
  <span m=''3378670''>the</span> <span m=''3378720''>possibilities</span> <span m=''3379380''>for</span>
  <span m=''3379510''>each</span> <span m=''3379690''>one.</span> <span m=''3380340''>I</span>
  <span m=''3380440''>say,</span> <span m=''3380620''>well</span> <span m=''3380790''>what</span>
  <span m=''3380950''>are</span> <span m=''3381050''>all</span> <span m=''3381150''>the</span>
  <span m=''3381220''>possibilities</span> <span m=''3381740''>for</span> <span m=''3381840''>this?</span>
  <span m=''3382340''>What</span> <span m=''3382560''>are</span> <span m=''3382840''>all</span>
  <span m=''3382940''>the</span> <span m=''3383000''>possibilities</span> <span m=''3383530''>for</span>
  <span m=''3383620''>this?</span> <span m=''3384620''>Take</span> <span m=''3384970''>the</span>
  <span m=''3385070''>cross-product.</span> </p><p><span m=''3386340''>Just</span>
  <span m=''3386510''>multiply</span> <span m=''3386980''>those</span> <span m=''3387190''>sets</span>
  <span m=''3387690''>together.</span> <span m=''3388500''>Those</span> <span m=''3388740''>are</span>
  <span m=''3388830''>all</span> <span m=''3388980''>the</span> <span m=''3389050''>possible</span>
  <span m=''3389990''>gluings.</span> <span m=''3390750''>And</span> <span m=''3390840''>then</span>
  <span m=''3390960''>I</span> <span m=''3391470''>sum</span> <span m=''3391750''>that.</span>
  <span m=''3392050''>I</span> <span m=''3393090''>take</span> <span m=''3393310''>all</span>
  <span m=''3393500''>the</span> <span m=''3393590''>options</span> <span m=''3394370''>for</span>
  <span m=''3394590''>all</span> <span m=''3394830''>the</span> <span m=''3394900''>different</span>
  <span m=''3395150''>values</span> <span m=''3395450''>of</span> <span m=''3395550''>K.</span>
  </p><p><span m=''3398380''>And</span> <span m=''3398570''>that''s</span> <span m=''3398770''>it.</span>
  <span m=''3400010''>That</span> <span m=''3400220''>output</span> <span m=''3400600''>is</span>
  <span m=''3400910''>all</span> <span m=''3401120''>the</span> <span m=''3401190''>possible</span>
  <span m=''3402020''>gluings.</span> <span m=''3404310''>So</span> <span m=''3404460''>this</span>
  <span m=''3404610''>should</span> <span m=''3404800''>actually</span> <span m=''3405100''>give</span>
  <span m=''3405260''>another</span> <span m=''3405540''>way</span> <span m=''3405690''>to</span>
  <span m=''3405790''>prove</span> <span m=''3406090''>that</span> <span m=''3406250''>the</span>
  <span m=''3406350''>number</span> <span m=''3406780''>of</span> <span m=''3406910''>different</span>
  <span m=''3407220''>gluings</span> <span m=''3407600''>is</span> <span m=''3407800''>only</span>
  <span m=''3409700''>exponential,</span> <span m=''3410240''>but</span> <span m=''3410380''>this</span>
  <span m=''3410520''>is</span> <span m=''3410620''>just</span> <span m=''3410810''>for</span>
  <span m=''3410880''>the</span> <span m=''3411010''>edge-to-edge</span> <span m=''3411510''>case.</span>
  <span m=''3415710''>Maybe</span> <span m=''3415890''>I</span> <span m=''3415940''>should</span>
  <span m=''3416050''>write</span> <span m=''3416210''>that</span> <span m=''3416360''>down.</span>
  </p><p><span m=''3418270''>So</span> <span m=''3419450''>we</span> <span m=''3419830''>have</span>
  <span m=''3421570''>for</span> <span m=''3421810''>each</span> <span m=''3422070''>choice</span>
  <span m=''3422350''>of</span> <span m=''3422450''>K</span> <span m=''3427440''>output--</span>
  <span m=''3430020''>let''s</span> <span m=''3430220''>say,</span> <span m=''3430450''>and</span>
  <span m=''3430650''>for</span> <span m=''3430900''>each</span> <span m=''3434460''>solution</span>
  <span m=''3437510''>to</span> <span m=''3438120''>the</span> <span m=''3438250''>smaller</span>
  <span m=''3438660''>sub-problem</span> <span m=''3438880''>VK</span> <span m=''3439640''>plus</span>
  <span m=''3439930''>1</span> <span m=''3440960''>to</span> <span m=''3441140''>VJ.</span>
  <span m=''3441280''>And</span> <span m=''3442340''>then</span> <span m=''3442620''>for</span>
  <span m=''3442810''>each</span> <span m=''3445210''>solution</span> <span m=''3446830''>to</span>
  <span m=''3448040''>VK</span> <span m=''3448590''>plus</span> <span m=''3448740''>1</span>
  <span m=''3449770''>to</span> <span m=''3449950''>VK</span> <span m=''3453531''>output.</span>
  <span m=''3456340''>This</span> <span m=''3456430''>is</span> <span m=''3456530''>very</span>
  <span m=''3456680''>simple.</span> <span m=''3457020''>This</span> <span m=''3457200''>is</span>
  <span m=''3457310''>just</span> <span m=''3457510''>a</span> <span m=''3457560''>product</span>
  <span m=''3458000''>over</span> <span m=''3458260''>various</span> <span m=''3458620''>things.</span>
  <span m=''3460190''>There''s</span> <span m=''3461730''>only</span> <span m=''3462050''>order</span>
  <span m=''3462280''>n</span> <span m=''3462570''>choices</span> <span m=''3462970''>here.</span>
  </p><p><span m=''3465610''>This</span> <span m=''3465830''>thing,</span> <span m=''3466300''>it</span>
  <span m=''3466470''>depends</span> <span m=''3466750''>how</span> <span m=''3466870''>many</span>
  <span m=''3467080''>solutions</span> <span m=''3467520''>there</span> <span m=''3467690''>are</span>
  <span m=''3467990''>to</span> <span m=''3468130''>those</span> <span m=''3468320''>sub-problems,</span>
  <span m=''3469460''>but</span> <span m=''3469620''>it''s</span> <span m=''3469750''>the</span>
  <span m=''3469840''>product</span> <span m=''3470260''>of</span> <span m=''3470380''>the</span>
  <span m=''3470470''>two.</span> <span m=''3471860''>And</span> <span m=''3472210''>then</span>
  <span m=''3472400''>that''s</span> <span m=''3472660''>the</span> <span m=''3473370''>total</span>
  <span m=''3474370''>output.</span> <span m=''3476970''>Believe</span> <span m=''3477280''>me,</span>
  <span m=''3477660''>this</span> <span m=''3477900''>runs</span> <span m=''3478290''>in</span>
  <span m=''3479290''>exponential</span> <span m=''3479820''>time.</span> <span m=''3480050''>That''s</span>
  <span m=''3480250''>not</span> <span m=''3480400''>very</span> <span m=''3480570''>hard</span>
  <span m=''3480840''>to</span> <span m=''3480920''>prove.</span> </p><p><span m=''3481780''>What''s</span>
  <span m=''3482030''>interesting</span> <span m=''3482530''>is</span> <span m=''3482650''>we</span>
  <span m=''3482780''>can</span> <span m=''3482930''>make</span> <span m=''3483100''>the</span>
  <span m=''3483200''>same</span> <span m=''3483570''>algorithm</span> <span m=''3484050''>with</span>
  <span m=''3484190''>a</span> <span m=''3484250''>little</span> <span m=''3484570''>bit</span>
  <span m=''3484730''>of</span> <span m=''3484830''>tweaking</span> <span m=''3486830''>get</span>
  <span m=''3487100''>a</span> <span m=''3487230''>polynomial</span> <span m=''3488030''>time</span>
  <span m=''3488470''>decision</span> <span m=''3488860''>algorithm.</span> <span
  m=''3492080''>That''s</span> <span m=''3492350''>cool.</span> <span m=''3494010''>How</span>
  <span m=''3494250''>do</span> <span m=''3494330''>we</span> <span m=''3494450''>make</span>
  <span m=''3494650''>it</span> <span m=''3494730''>a</span> <span m=''3494790''>polynomial</span>
  <span m=''3495330''>decision</span> <span m=''3495690''>algorithm?</span> </p><p><span
  m=''3498170''>I</span> <span m=''3498270''>can''t</span> <span m=''3498590''>afford</span>
  <span m=''3499100''>to</span> <span m=''3499250''>store</span> <span m=''3499670''>every</span>
  <span m=''3499950''>solution</span> <span m=''3500480''>for</span> <span m=''3500620''>every</span>
  <span m=''3500840''>sub-problem</span> <span m=''3501350''>because</span> <span
  m=''3501700''>there</span> <span m=''3501830''>can</span> <span m=''3501970''>be</span>
  <span m=''3502070''>exponentially</span> <span m=''3502590''>many.</span> <span
  m=''3503220''>So</span> <span m=''3503500''>I</span> <span m=''3503600''>only</span>
  <span m=''3503840''>get</span> <span m=''3504000''>to</span> <span m=''3504070''>store</span>
  <span m=''3504350''>one</span> <span m=''3504750''>solution</span> <span m=''3505790''>for</span>
  <span m=''3505980''>every</span> <span m=''3506200''>sub-problem.</span> <span m=''3509280''>So</span>
  <span m=''3509540''>this</span> <span m=''3509740''>is</span> <span m=''3509890''>the</span>
  <span m=''3509980''>great</span> <span m=''3510200''>idea.</span> <span m=''3516370''>Let''s</span>
  <span m=''3516540''>say</span> <span m=''3522960''>for</span> <span m=''3523060''>each</span>
  <span m=''3523220''>sub-problem,</span> <span m=''3527090''>let''s</span> <span
  m=''3527330''>say</span> <span m=''3527670''>VI</span> <span m=''3528680''>to</span>
  <span m=''3528780''>VK</span> <span m=''3531450''>only</span> <span m=''3531830''>store</span>
  <span m=''3535830''>the</span> <span m=''3535970''>solution</span> <span m=''3538730''>that</span>
  <span m=''3538900''>minimizes</span> <span m=''3541660''>the</span> <span m=''3541750''>amount</span>
  <span m=''3541990''>of</span> <span m=''3542080''>stuff</span> <span m=''3543010''>glued</span>
  <span m=''3543430''>into</span> <span m=''3543730''>VI</span> <span m=''3543930''>VJ.</span>
  </p><p><span m=''3550260''>So</span> <span m=''3550510''>the</span> <span m=''3550580''>sum</span>
  <span m=''3550810''>of</span> <span m=''3550860''>the</span> <span m=''3550980''>angles</span>
  <span m=''3552020''>glued</span> <span m=''3553670''>at</span> <span m=''3555270''>VI,</span>
  <span m=''3557440''>which</span> <span m=''3558120''>is</span> <span m=''3559500''>the</span>
  <span m=''3559590''>same</span> <span m=''3559810''>thing</span> <span m=''3560020''>as</span>
  <span m=''3560130''>VJ</span> <span m=''3561540''>because</span> <span m=''3561730''>they</span>
  <span m=''3561930''>are</span> <span m=''3562100''>already</span> <span m=''3562190''>glued</span>
  <span m=''3562410''>together.</span> <span m=''3564270''>That''s what</span> <span
  m=''3564510''>we</span> <span m=''3564580''>were</span> <span m=''3564730''>told.</span>
  <span m=''3565810''>So</span> <span m=''3566670''>I</span> <span m=''3566770''>had</span>
  <span m=''3566940''>many</span> <span m=''3567160''>choices</span> <span m=''3567590''>here.</span>
  </p><p><span m=''3567840''>I</span> <span m=''3567950''>had</span> <span m=''3568590''>all</span>
  <span m=''3568780''>the</span> <span m=''3568840''>choices</span> <span m=''3569170''>for</span>
  <span m=''3569280''>K.</span> <span m=''3569890''>I</span> <span m=''3569980''>had</span>
  <span m=''3570150''>all</span> <span m=''3570300''>the</span> <span m=''3570380''>choices</span>
  <span m=''3571080''>for</span> <span m=''3571360''>up</span> <span m=''3571530''>here.</span>
  <span m=''3572210''>I had</span> <span m=''3572500''>all</span> <span m=''3572610''>the</span>
  <span m=''3572680''>choices</span> <span m=''3573020''>for</span> <span m=''3573130''>up</span>
  <span m=''3573260''>here.</span> </p><p><span m=''3573470''>Well</span> <span m=''3573590''>actually</span>
  <span m=''3573900''>now</span> <span m=''3574150''>I''m</span> <span m=''3574290''>just</span>
  <span m=''3574450''>going</span> <span m=''3574540''>to</span> <span m=''3574610''>think</span>
  <span m=''3574780''>about</span> <span m=''3575010''>one</span> <span m=''3575320''>choice</span>
  <span m=''3575620''>up</span> <span m=''3575770''>here,</span> <span m=''3576350''>which</span>
  <span m=''3576450''>is</span> <span m=''3576560''>what</span> <span m=''3576800''>is</span>
  <span m=''3576940''>the</span> <span m=''3577030''>choice</span> <span m=''3578040''>that</span>
  <span m=''3578190''>minimizes</span> <span m=''3578950''>the</span> <span m=''3579100''>angle</span>
  <span m=''3579420''>glued</span> <span m=''3579630''>here?</span> <span m=''3580600''>And</span>
  <span m=''3580800''>what</span> <span m=''3580950''>is</span> <span m=''3581050''>the</span>
  <span m=''3581130''>choice</span> <span m=''3581590''>over</span> <span m=''3581780''>here</span>
  <span m=''3582100''>that</span> <span m=''3582260''>minimizes</span> <span m=''3582880''>the</span>
  <span m=''3582990''>angle</span> <span m=''3583270''>glued</span> <span m=''3583510''>there?</span>
  <span m=''3584650''>Why</span> <span m=''3584880''>the</span> <span m=''3584990''>minimum?</span>
  <span m=''3585800''>Because</span> <span m=''3586090''>some</span> <span m=''3586340''>of</span>
  <span m=''3586410''>these</span> <span m=''3587390''>are</span> <span m=''3587670''>wrong.</span>
  </p><p><span m=''3588140''>I</span> <span m=''3588260''>should</span> <span m=''3588460''>actually</span>
  <span m=''3588670''>say</span> <span m=''3588880''>output</span> <span m=''3589370''>if</span>
  <span m=''3590210''>it''s</span> <span m=''3590370''>Alexandroff.</span> <span m=''3592270''>We</span>
  <span m=''3592890''>only</span> <span m=''3593070''>want</span> <span m=''3593210''>to</span>
  <span m=''3593280''>output</span> <span m=''3593600''>Alexandroff</span> <span m=''3594140''>gluings.</span>
  <span m=''3594490''>We</span> <span m=''3594600''>only</span> <span m=''3594790''>want</span>
  <span m=''3594930''>to</span> <span m=''3594980''>output</span> <span m=''3595360''>gluings</span>
  <span m=''3595800''>where</span> <span m=''3596050''>the</span> <span m=''3596170''>total</span>
  <span m=''3596550''>sum</span> <span m=''3596770''>of</span> <span m=''3596820''>the</span>
  <span m=''3596920''>angles</span> <span m=''3597240''>is</span> <span m=''3597350''>less</span>
  <span m=''3597570''>than</span> <span m=''3597670''>or</span> <span m=''3597770''>equal</span>
  <span m=''3597790''>to</span> <span m=''3597860''>360.</span> <span m=''3598530''>I</span>
  <span m=''3598590''>need</span> <span m=''3598740''>to</span> <span m=''3598820''>check</span>
  <span m=''3599060''>that</span> <span m=''3601200''>for</span> <span m=''3601360''>every</span>
  <span m=''3601610''>one.</span> </p><p><span m=''3603070''>If</span> <span m=''3603230''>I</span>
  <span m=''3603300''>want</span> <span m=''3603820''>to</span> <span m=''3603970''>have</span>
  <span m=''3604130''>the</span> <span m=''3604200''>most</span> <span m=''3604660''>chance</span>
  <span m=''3605060''>of</span> <span m=''3605170''>it</span> <span m=''3605300''>being</span>
  <span m=''3605510''>Alexandroff,</span> <span m=''3606260''>if</span> <span m=''3606480''>I</span>
  <span m=''3606590''>got</span> <span m=''3606890''>the</span> <span m=''3607010''>least</span>
  <span m=''3607410''>possible</span> <span m=''3607880''>angle</span> <span m=''3608140''>glued</span>
  <span m=''3608320''>here</span> <span m=''3608630''>and</span> <span m=''3608830''>glued</span>
  <span m=''3609020''>here,</span> <span m=''3609690''>that''s</span> <span m=''3609910''>my</span>
  <span m=''3610230''>best</span> <span m=''3610620''>hope</span> <span m=''3610830''>of</span>
  <span m=''3610950''>it</span> <span m=''3611020''>working.</span> <span m=''3611530''>Now</span>
  <span m=''3611660''>I</span> <span m=''3611720''>still</span> <span m=''3611960''>have</span>
  <span m=''3612110''>flexibility,</span> <span m=''3612730''>which</span> <span m=''3612900''>is</span>
  <span m=''3613040''>I</span> <span m=''3613090''>get</span> <span m=''3613280''>to</span>
  <span m=''3613370''>choose</span> <span m=''3613620''>k.</span> <span m=''3614700''>There''s</span>
  <span m=''3614820''>still n</span> <span m=''3615090''>choices</span> <span m=''3615640''>for</span>
  <span m=''3615760''>k,</span> <span m=''3616890''>but</span> <span m=''3616990''>everything</span>
  <span m=''3617370''>else</span> <span m=''3617580''>is</span> <span m=''3617710''>determined</span>
  <span m=''3618170''>at</span> <span m=''3618260''>that</span> <span m=''3618450''>point.</span>
  <span m=''3619510''>Once</span> <span m=''3619750''>I</span> <span m=''3619800''>fix</span>
  <span m=''3620120''>K</span> <span m=''3620530''>I</span> <span m=''3620630''>see,</span>
  <span m=''3620910''>well</span> <span m=''3621140''>does</span> <span m=''3621380''>this</span>
  <span m=''3621550''>work,</span> <span m=''3622380''>yes</span> <span m=''3622590''>or</span>
  <span m=''3622660''>no?</span> </p><p><span m=''3623730''>If</span> <span m=''3623910''>it</span>
  <span m=''3624040''>works,</span> <span m=''3624800''>that</span> <span m=''3624930''>gives</span>
  <span m=''3625120''>me</span> <span m=''3625250''>one</span> <span m=''3625550''>candidate</span>
  <span m=''3626560''>for</span> <span m=''3626720''>how</span> <span m=''3626870''>much</span>
  <span m=''3627080''>material</span> <span m=''3627500''>gets</span> <span m=''3627710''>glued</span>
  <span m=''3627880''>here.</span> <span m=''3628740''>It</span> <span m=''3629170''>could</span>
  <span m=''3629330''>be</span> <span m=''3629440''>a</span> <span m=''3629500''>lot,</span>
  <span m=''3629750''>could</span> <span m=''3629850''>be</span> <span m=''3629960''>a</span>
  <span m=''3630010''>little.</span> <span m=''3630260''>I</span> <span m=''3630370''>try</span>
  <span m=''3630600''>for</span> <span m=''3630780''>all</span> <span m=''3630980''>K,</span>
  <span m=''3631650''>I</span> <span m=''3631750''>take</span> <span m=''3631980''>the</span>
  <span m=''3632060''>smallest</span> <span m=''3632580''>one.</span> <span m=''3633480''>So</span>
  <span m=''3633580''>it''s</span> <span m=''3633670''>the</span> <span m=''3633740''>same</span>
  <span m=''3634200''>loop,</span> <span m=''3634730''>except</span> <span m=''3635510''>there''s</span>
  <span m=''3635700''>no</span> <span m=''3635910''>four</span> <span m=''3636150''>loops</span>
  <span m=''3636540''>here.</span> <span m=''3637010''>It''s</span> <span m=''3637140''>just</span>
  <span m=''3637290''>for</span> <span m=''3637390''>every</span> <span m=''3637580''>choice</span>
  <span m=''3637860''>of</span> <span m=''3637940''>K,</span> <span m=''3638660''>I</span>
  <span m=''3638750''>look</span> <span m=''3638950''>at</span> <span m=''3639030''>the</span>
  <span m=''3639300''>solution</span> <span m=''3639810''>to</span> <span m=''3639920''>VK</span>
  <span m=''3640270''>plus</span> <span m=''3640490''>1</span> <span m=''3640650''>to</span>
  <span m=''3640720''>VJ,</span> <span m=''3641390''>the</span> <span m=''3641610''>solution</span>
  <span m=''3642070''>for</span> <span m=''3642220''>VI</span> <span m=''3642490''>plus</span>
  <span m=''3642740''>1</span> <span m=''3643280''>to</span> <span m=''3643400''>VK.</span>
  </p><p><span m=''3643860''>If</span> <span m=''3644000''>it''s</span> <span m=''3644150''>Alexandroff,</span>
  <span m=''3645280''>I</span> <span m=''3645390''>don''t</span> <span m=''3645570''>output</span>
  <span m=''3646040''>it.</span> <span m=''3646250''>But</span> <span m=''3646400''>I</span>
  <span m=''3646500''>check,</span> <span m=''3648350''>is</span> <span m=''3648510''>it</span>
  <span m=''3648670''>the</span> <span m=''3648760''>best</span> <span m=''3648960''>solution</span>
  <span m=''3649310''>so</span> <span m=''3649480''>far</span> <span m=''3650240''>in</span>
  <span m=''3650400''>terms</span> <span m=''3650710''>of</span> <span m=''3651590''>the</span>
  <span m=''3651770''>total</span> <span m=''3652100''>angle</span> <span m=''3652310''>glued</span>
  <span m=''3652520''>of</span> <span m=''3652610''>VI</span> <span m=''3652770''>and</span>
  <span m=''3653010''>VJ.</span> <span m=''3655150''>I</span> <span m=''3655660''>keep</span>
  <span m=''3655910''>looping</span> <span m=''3656270''>until</span> <span m=''3656380''>I</span>
  <span m=''3656470''>find</span> <span m=''3656720''>the</span> <span m=''3656790''>very</span>
  <span m=''3657020''>best</span> <span m=''3657300''>one,</span> <span m=''3657720''>and</span>
  <span m=''3657890''>I</span> <span m=''3657990''>output</span> <span m=''3658210''>that</span>
  <span m=''3658450''>one.</span> <span m=''3659600''>That</span> <span m=''3659790''>would</span>
  <span m=''3659940''>be</span> <span m=''3660850''>the</span> <span m=''3660980''>solution</span>
  <span m=''3661360''>that</span> <span m=''3661500''>I</span> <span m=''3661590''>store.</span>
  </p><p><span m=''3663550''>The</span> <span m=''3663690''>result</span> <span m=''3664140''>is,</span>
  <span m=''3665960''>the</span> <span m=''3666090''>running</span> <span m=''3666370''>time</span>
  <span m=''3667300''>is</span> <span m=''3667520''>actually</span> <span m=''3667900''>polynomial,</span>
  <span m=''3668700''>because</span> <span m=''3670380''>the</span> <span m=''3670530''>number</span>
  <span m=''3670950''>of</span> <span m=''3671010''>sub-problems--</span> <span m=''3672130''>a</span>
  <span m=''3672420''>sub-problem</span> <span m=''3672930''>is</span> <span m=''3673060''>determined</span>
  <span m=''3673570''>by</span> <span m=''3674100''>two</span> <span m=''3674310''>vertices.</span>
  <span m=''3674880''>There''s</span> <span m=''3675010''>only</span> <span m=''3675240''>n</span>
  <span m=''3675430''>of</span> <span m=''3675510''>these,</span> <span m=''3675770''>n</span>
  <span m=''3675930''>of</span> <span m=''3676020''>these.</span> <span m=''3676800''>So</span>
  <span m=''3676920''>the</span> <span m=''3676970''>number</span> <span m=''3677240''>of</span>
  <span m=''3677290''>sub-problems</span> <span m=''3678030''>is</span> <span m=''3678320''>n</span>
  <span m=''3678520''>squared.</span> <span m=''3681040''>For</span> <span m=''3681240''>each</span>
  <span m=''3681410''>sub-problem</span> <span m=''3682150''>I</span> <span m=''3682300''>need</span>
  <span m=''3683020''>to</span> <span m=''3683320''>look</span> <span m=''3683490''>at</span>
  <span m=''3683610''>order</span> <span m=''3683880''>n</span> <span m=''3684110''>choices</span>
  <span m=''3685277''>for</span> <span m=''3686500''>K.</span> <span m=''3688540''>And</span>
  <span m=''3688730''>so</span> <span m=''3688910''>the</span> <span m=''3689120''>total</span>
  <span m=''3689400''>running</span> <span m=''3689710''>time</span> <span m=''3690640''>is</span>
  <span m=''3691050''>n</span> <span m=''3691270''>squared</span> <span m=''3692220''>times</span>
  <span m=''3692860''>n,</span> <span m=''3694580''>which</span> <span m=''3694820''>is</span>
  <span m=''3695260''>n</span> <span m=''3695510''>cubed.</span> </p><p><span m=''3697950''>And</span>
  <span m=''3698110''>that</span> <span m=''3698320''>will</span> <span m=''3698450''>tell</span>
  <span m=''3698680''>you</span> <span m=''3699160''>if</span> <span m=''3699510''>there''s</span>
  <span m=''3699630''>any</span> <span m=''3699870''>hope</span> <span m=''3700120''>of</span>
  <span m=''3700230''>anything</span> <span m=''3700630''>working,</span> <span m=''3701840''>if</span>
  <span m=''3701880''>there''s</span> <span m=''3702120''>any</span> <span m=''3702410''>gluing</span>
  <span m=''3703360''>this</span> <span m=''3703550''>will</span> <span m=''3703660''>find</span>
  <span m=''3704010''>one,</span> <span m=''3705070''>because</span> <span m=''3706580''>it''s</span>
  <span m=''3706780''>always</span> <span m=''3706980''>trying</span> <span m=''3707210''>to</span>
  <span m=''3707260''>minimize</span> <span m=''3707700''>the</span> <span m=''3707770''>angles</span>
  <span m=''3708040''>that</span> <span m=''3708295''>get</span> <span m=''3708550''>glued</span>
  <span m=''3708950''>together</span> <span m=''3714040''>That''s</span> <span m=''3714290''>is</span>
  <span m=''3714560''>edge-to-edge.</span> <span m=''3720030''>Now</span> <span m=''3720290''>we</span>
  <span m=''3720380''>can</span> <span m=''3720510''>generalize.</span> <span m=''3721520''>It''s</span>
  <span m=''3721620''>a</span> <span m=''3721680''>little</span> <span m=''3722000''>bit</span>
  <span m=''3722160''>messy,</span> <span m=''3723554''>but</span> <span m=''3724470''>we</span>
  <span m=''3724530''>can</span> <span m=''3724790''>generalize</span> <span m=''3725470''>to</span>
  <span m=''3726310''>arbitrary</span> <span m=''3726790''>gluings.</span> </p><p><span
  m=''3732770''>Let</span> <span m=''3732950''>me</span> <span m=''3733100''>sketch</span>
  <span m=''3733610''>a</span> <span m=''3733640''>little</span> <span m=''3733840''>bit</span>
  <span m=''3734120''>how</span> <span m=''3734500''>that</span> <span m=''3734660''>goes.</span>
  <span m=''3742030''>So</span> <span m=''3742130''>we''ve</span> <span m=''3742270''>seen</span>
  <span m=''3742700''>now</span> <span m=''3744650''>this</span> <span m=''3744920''>result</span>
  <span m=''3745710''>for</span> <span m=''3745850''>algorithms</span> <span m=''3746650''>and</span>
  <span m=''3746980''>this</span> <span m=''3747140''>result</span> <span m=''3747450''>for</span>
  <span m=''3747560''>algorithms.</span> <span m=''3748800''>And</span> <span m=''3749040''>now
  I''m</span> <span m=''3749090''>going</span> <span m=''3749170''>to</span> <span
  m=''3749240''>tell</span> <span m=''3749400''>you</span> <span m=''3749490''>about</span>
  <span m=''3749710''>this</span> <span m=''3749920''>result.</span> <span m=''3751000''>I</span>
  <span m=''3751110''>wish</span> <span m=''3751610''>there</span> <span m=''3751720''>was</span>
  <span m=''3751850''>a</span> <span m=''3751920''>result</span> <span m=''3752250''>here</span>
  <span m=''3752430''>to</span> <span m=''3752500''>tell</span> <span m=''3752700''>you</span>
  <span m=''3752830''>about,</span> <span m=''3753170''>but</span> <span m=''3753310''>there</span>
  <span m=''3753570''>isn''t.</span> </p><p><span m=''3754050''>So</span> <span m=''3754260''>this</span>
  <span m=''3754430''>last</span> <span m=''3754690''>part</span> <span m=''3754900''>that</span>
  <span m=''3755000''>I</span> <span m=''3755060''>did</span> <span m=''3755310''>where</span>
  <span m=''3755410''>the</span> <span m=''3755570''>decision</span> <span m=''3755960''>algorithm</span>
  <span m=''3756310''>is</span> <span m=''3756420''>very</span> <span m=''3756620''>efficient,</span>
  <span m=''3757590''>we</span> <span m=''3757700''>don''t</span> <span m=''3757960''>know</span>
  <span m=''3758030''>how</span> <span m=''3758170''>to</span> <span m=''3758280''>generalize</span>
  <span m=''3758830''>that</span> <span m=''3759160''>to</span> <span m=''3759420''>the</span>
  <span m=''3759600''>general</span> <span m=''3759900''>case,</span> <span m=''3760780''>arbitrary</span>
  <span m=''3761210''>gluings.</span> <span m=''3762260''>This</span> <span m=''3762390''>only</span>
  <span m=''3762620''>works</span> <span m=''3762800''>for</span> <span m=''3762890''>edge-to-edge.</span>
  <span m=''3763440''>We</span> <span m=''3763610''>assumed</span> <span m=''3763940''>a</span>
  <span m=''3764030''>whole</span> <span m=''3764360''>edge,</span> <span m=''3765010''>VK</span>
  <span m=''3765340''>VK</span> <span m=''3765640''>plus</span> <span m=''3765850''>1</span>
  <span m=''3766060''>was</span> <span m=''3766200''>glued</span> <span m=''3766480''>to</span>
  <span m=''3766630''>VI VI</span> <span m=''3767020''>plus</span> <span m=''3767240''>1.</span>
  </p><p><span m=''3769480''>But</span> <span m=''3770220''>the</span> <span m=''3770540''>enumeration</span>
  <span m=''3771210''>part</span> <span m=''3771590''>where</span> <span m=''3771770''>we</span>
  <span m=''3771880''>said,</span> <span m=''3772190''>oh</span> <span m=''3772370''>just</span>
  <span m=''3772580''>give</span> <span m=''3772710''>me</span> <span m=''3772870''>all</span>
  <span m=''3773060''>the</span> <span m=''3773150''>solutions,</span> <span m=''3773810''>that</span>
  <span m=''3774230''>we</span> <span m=''3774440''>can</span> <span m=''3774600''>get</span>
  <span m=''3774750''>to</span> <span m=''3774840''>work.</span> <span m=''3775100''>It''s</span>
  <span m=''3775240''>just</span> <span m=''3775500''>slightly</span> <span m=''3775790''>more</span>
  <span m=''3775950''>complicated.</span> <span m=''3778250''>Let</span> <span m=''3778450''>me</span>
  <span m=''3781180''>tell</span> <span m=''3781330''>you</span> <span m=''3781440''>how</span>
  <span m=''3781650''>it</span> <span m=''3781740''>gets</span> <span m=''3781920''>more</span>
  <span m=''3782070''>complicated.</span> </p><p><span m=''3784770''>So</span> <span
  m=''3785720''>one</span> <span m=''3786020''>difference</span> <span m=''3786570''>is</span>
  <span m=''3786830''>that</span> <span m=''3788510''>there</span> <span m=''3788640''>are</span>
  <span m=''3788670''>more</span> <span m=''3788880''>kinds</span> <span m=''3789310''>of</span>
  <span m=''3789400''>sub-problems,</span> <span m=''3790930''>this</span> <span m=''3791110''>is</span>
  <span m=''3791280''>the</span> <span m=''3791380''>heart</span> <span m=''3791680''>of</span>
  <span m=''3791940''>the</span> <span m=''3792140''>problem.</span> <span m=''3792930''>We</span>
  <span m=''3793080''>have</span> <span m=''3793320''>the</span> <span m=''3793430''>VI</span>
  <span m=''3794000''>to</span> <span m=''3794100''>VJ</span> <span m=''3794600''>sub-problem</span>
  <span m=''3795800''>just</span> <span m=''3796000''>like</span> <span m=''3796140''>before,</span>
  <span m=''3796540''>that''s</span> <span m=''3796810''>easy.</span> <span m=''3798510''>And</span>
  <span m=''3798660''>then</span> <span m=''3798820''>we</span> <span m=''3798910''>have</span>
  <span m=''3799190''>the</span> <span m=''3800144''>VI</span> <span m=''3800621''>to</span>
  <span m=''3801100''>EJ</span> <span m=''3801772''>sub-problem.</span> </p><p><span
  m=''3803550''>So</span> <span m=''3803700''>this</span> <span m=''3803900''>one</span>
  <span m=''3804130''>was</span> <span m=''3804340''>VI</span> <span m=''3804660''>was</span>
  <span m=''3804830''>glued</span> <span m=''3805010''>to</span> <span m=''3805070''>VJ,</span>
  <span m=''3806020''>very</span> <span m=''3806310''>clear</span> <span m=''3807360''>what</span>
  <span m=''3807540''>that</span> <span m=''3807730''>means.</span> <span m=''3808830''>Here</span>
  <span m=''3809460''>we</span> <span m=''3809620''>have</span> <span m=''3810260''>VI</span>
  <span m=''3810790''>is</span> <span m=''3810990''>glued</span> <span m=''3811220''>to</span>
  <span m=''3811450''>an</span> <span m=''3811720''>edge</span> <span m=''3813150''>EJ.</span>
  <span m=''3816190''>The</span> <span m=''3816680''>trouble</span> <span m=''3817060''>with</span>
  <span m=''3817210''>that</span> <span m=''3818660''>is</span> <span m=''3818810''>we</span>
  <span m=''3818930''>don''t</span> <span m=''3819090''>know</span> <span m=''3819250''>where</span>
  <span m=''3819570''>on</span> <span m=''3819640''>the</span> <span m=''3819740''>edge
  it''s</span> <span m=''3820020''>glued.</span> <span m=''3821200''>It''s</span>
  <span m=''3821370''>somewhere</span> <span m=''3823180''>on</span> <span m=''3823260''>the</span>
  <span m=''3823390''>edge.</span> </p><p><span m=''3825220''>This</span> <span m=''3825350''>is</span>
  <span m=''3825460''>where</span> <span m=''3825610''>things</span> <span m=''3825920''>get</span>
  <span m=''3826190''>trickier.</span> <span m=''3828200''>And</span> <span m=''3828380''>there''s</span>
  <span m=''3828540''>also</span> <span m=''3828770''>the</span> <span m=''3829000''>symmetric</span>
  <span m=''3829510''>case,</span> <span m=''3829750''>of</span> <span m=''3829860''>course,</span>
  <span m=''3830150''>where</span> <span m=''3830420''>it''s</span> <span m=''3830630''>EI</span>
  <span m=''3831030''>to</span> <span m=''3831240''>VJ.</span> <span m=''3832280''>But</span>
  <span m=''3832440''>we</span> <span m=''3832560''>don''t</span> <span m=''3832680''>really</span>
  <span m=''3832900''>need</span> <span m=''3833030''>to</span> <span m=''3833100''>worry</span>
  <span m=''3833220''>about</span> <span m=''3833430''>that, it''s</span> <span m=''3833720''>symmetric.</span>
  <span m=''3842670''>So</span> <span m=''3843330''>what</span> <span m=''3843660''>does</span>
  <span m=''3843860''>a</span> <span m=''3844020''>solution</span> <span m=''3844640''>look</span>
  <span m=''3844880''>like?</span> </p><p><span m=''3849310''>So</span> <span m=''3849480''>before,
  a</span> <span m=''3849930''>solution</span> <span m=''3850350''>was</span> <span
  m=''3850540''>an</span> <span m=''3850630''>entire</span> <span m=''3851040''>gluing.</span>
  <span m=''3852560''>Now,</span> <span m=''3853340''>because</span> <span m=''3854390''>the</span>
  <span m=''3854880''>gluings</span> <span m=''3855180''>can</span> <span m=''3855400''>be</span>
  <span m=''3855540''>infinite.</span> <span m=''3855990''>There can</span> <span
  m=''3856110''>be infinitely</span> <span m=''3856690''>many</span> <span m=''3856890''>different</span>
  <span m=''3857180''>gluings.</span> <span m=''3857560''>I</span> <span m=''3857620''>can''t</span>
  <span m=''3858000''>actually</span> <span m=''3858300''>list</span> <span m=''3858620''>every
  one</span> <span m=''3859000''>explicitly.</span> <span m=''3860050''>I''ve</span>
  <span m=''3860230''>actually</span> <span m=''3860500''>got</span> <span m=''3860650''>to</span>
  <span m=''3860750''>explain</span> <span m=''3861150''>ranges</span> <span m=''3861670''>of</span>
  <span m=''3861790''>gluings</span> <span m=''3862140''>if</span> <span m=''3862290''>I</span>
  <span m=''3862340''>have</span> <span m=''3862520''>any</span> <span m=''3862650''>hope</span>
  <span m=''3862880''>of</span> <span m=''3862990''>capturing</span> <span m=''3863350''>all</span>
  <span m=''3863610''>of them.</span> </p><p><span m=''3864880''>So</span> <span m=''3865180''>what</span>
  <span m=''3866100''>a</span> <span m=''3866150''>solution</span> <span m=''3866550''>is</span>
  <span m=''3866620''>going</span> <span m=''3866850''>to</span> <span m=''3866970''>look</span>
  <span m=''3867160''>like</span> <span m=''3868050''>is</span> <span m=''3868710''>the</span>
  <span m=''3868890''>combinatorial</span> <span m=''3869530''>type</span> <span m=''3869800''>of</span>
  <span m=''3869970''>the</span> <span m=''3870050''>gluing,</span> <span m=''3879360''>which</span>
  <span m=''3879600''>was</span> <span m=''3879870''>this</span> <span m=''3879980''>stuff.</span>
  <span m=''3880310''>You</span> <span m=''3880470''>have</span> <span m=''3880560''>an</span>
  <span m=''3880620''>abstract</span> <span m=''3881040''>gluing</span> <span m=''3881140''>tree,</span>
  <span m=''3881600''>you get</span> <span m=''3881680''>which</span> <span m=''3881870''>vertices</span>
  <span m=''3882240''>glue</span> <span m=''3882390''>to</span> <span m=''3882460''>what</span>
  <span m=''3882620''>edges.</span> <span m=''3883770''>So</span> <span m=''3883820''>you</span>
  <span m=''3883920''>have</span> <span m=''3884060''>pretty</span> <span m=''3884270''>much</span>
  <span m=''3884490''>the</span> <span m=''3884570''>whole</span> <span m=''3884730''>picture,</span>
  <span m=''3885930''>just</span> <span m=''3886130''>not</span> <span m=''3886310''>exactly</span>
  <span m=''3886920''>where</span> <span m=''3887200''>each</span> <span m=''3887360''>vertex</span>
  <span m=''3887760''>is</span> <span m=''3887880''>glued</span> <span m=''3888080''>to</span>
  <span m=''3888160''>which</span> <span m=''3888370''>edge.</span> </p><p><span m=''3889710''>Then</span>
  <span m=''3891360''>I</span> <span m=''3891560''>also</span> <span m=''3891970''>will</span>
  <span m=''3892110''>tell</span> <span m=''3892340''>you</span> <span m=''3893050''>a</span>
  <span m=''3893140''>total</span> <span m=''3894690''>angle</span> <span m=''3895010''>of</span>
  <span m=''3895110''>material</span> <span m=''3901800''>glued</span> <span m=''3903580''>at</span>
  <span m=''3903860''>VI</span> <span m=''3904070''>so</span> <span m=''3904500''>far.</span>
  <span m=''3906010''>In</span> <span m=''3906090''>both</span> <span m=''3906300''>these</span>
  <span m=''3906470''>cases,</span> <span m=''3906880''>I</span> <span m=''3906950''>want</span>
  <span m=''3907130''>to</span> <span m=''3907170''>know</span> <span m=''3907280''>how</span>
  <span m=''3907450''>much</span> <span m=''3908070''>stuff</span> <span m=''3908410''>in</span>
  <span m=''3908510''>my</span> <span m=''3909910''>gluing</span> <span m=''3910770''>at</span>
  <span m=''3910980''>VI</span> <span m=''3911320''>so I can</span> <span m=''3911680''>tell</span>
  <span m=''3911890''>whether it''s</span> <span m=''3912170''>Alexandroff.</span>
  <span m=''3914500''>And</span> <span m=''3914990''>then</span> <span m=''3917250''>in</span>
  <span m=''3917360''>the</span> <span m=''3917450''>case</span> <span m=''3917850''>where</span>
  <span m=''3918410''>I</span> <span m=''3918730''>glue</span> <span m=''3918880''>a</span>
  <span m=''3918980''>vertex</span> <span m=''3919390''>to an edge,</span> <span m=''3922570''>what</span>
  <span m=''3922760''>I''m</span> <span m=''3922860''>going</span> <span m=''3923080''>to</span>
  <span m=''3923200''>do</span> <span m=''3923600''>is</span> <span m=''3924000''>give</span>
  <span m=''3924210''>you</span> <span m=''3924350''>an</span> <span m=''3924450''>interval.</span>
  </p><p><span m=''3928535''>The</span> <span m=''3929030''>Interval''s</span> <span
  m=''3929430''>always</span> <span m=''3929650''>going</span> <span m=''3929860''>to</span>
  <span m=''3929970''>be</span> <span m=''3931120''>starting</span> <span m=''3931660''>at</span>
  <span m=''3931760''>0,</span> <span m=''3933020''>and</span> <span m=''3935160''>going</span>
  <span m=''3935470''>to</span> <span m=''3935590''>some</span> <span m=''3935850''>value</span>
  <span m=''3936240''>x.</span> <span m=''3936680''>x</span> <span m=''3937120''>is</span>
  <span m=''3937790''>less</span> <span m=''3938130''>than</span> <span m=''3938260''>or</span>
  <span m=''3938350''>equal</span> <span m=''3938620''>to</span> <span m=''3940800''>the</span>
  <span m=''3940910''>length</span> <span m=''3941200''>of</span> <span m=''3941300''>the</span>
  <span m=''3941440''>edge,</span> <span m=''3942530''>VJ.</span> <span m=''3946510''>And</span>
  <span m=''3946680''>this</span> <span m=''3946880''>is</span> <span m=''3946980''>the</span>
  <span m=''3947130''>interval</span> <span m=''3947660''>along</span> <span m=''3948010''>the</span>
  <span m=''3948140''>edge</span> <span m=''3948920''>where</span> <span m=''3949330''>VI</span>
  <span m=''3949800''>can</span> <span m=''3950070''>glue.</span> <span m=''3953510''>So</span>
  <span m=''3953660''>I''m</span> <span m=''3953760''>going</span> <span m=''3953920''>to</span>
  <span m=''3954040''>tell</span> <span m=''3954320''>you</span> <span m=''3954740''>an</span>
  <span m=''3954890''>actual</span> <span m=''3955320''>interval</span> <span m=''3955790''>here</span>
  <span m=''3957550''>from</span> <span m=''3957870''>the</span> <span m=''3957940''>edge</span>
  <span m=''3958240''>EJ.</span> </p><p><span m=''3960320''>As</span> <span m=''3960500''>long</span>
  <span m=''3960800''>as</span> <span m=''3960870''>you</span> <span m=''3960980''>glue</span>
  <span m=''3961350''>VI</span> <span m=''3961650''>to</span> <span m=''3961790''>somewhere</span>
  <span m=''3962100''>between</span> <span m=''3962420''>there</span> <span m=''3962580''>and</span>
  <span m=''3962690''>there,</span> <span m=''3963270''>this</span> <span m=''3963470''>stuff</span>
  <span m=''3963740''>works.</span> <span m=''3964810''>Whatever</span> <span m=''3964980''>I</span>
  <span m=''3965160''>specified</span> <span m=''3966170''>works</span> <span m=''3966400''>over</span>
  <span m=''3966580''>there.</span> <span m=''3966980''>You</span> <span m=''3967120''>can''t</span>
  <span m=''3967380''>go</span> <span m=''3967530''>beyond</span> <span m=''3967890''>some</span>
  <span m=''3968080''>point.</span> <span m=''3976040''>That</span> <span m=''3976210''>will</span>
  <span m=''3976310''>turn</span> <span m=''3976450''>out</span> <span m=''3976580''>to</span>
  <span m=''3976660''>be</span> <span m=''3976740''>enough.</span> </p><p><span m=''3992420''>So</span>
  <span m=''3995790''>while</span> <span m=''3995970''>there''s</span> <span m=''3996160''>the</span>
  <span m=''3996210''>VI</span> <span m=''3996400''>to</span> <span m=''3996570''>VJ</span>
  <span m=''3996910''>case,</span> <span m=''3997270''>it''s</span> <span m=''3998670''>less</span>
  <span m=''3998950''>interesting.</span> <span m=''3999750''>Let''s</span> <span
  m=''3999970''>think</span> <span m=''4000150''>about</span> <span m=''4001310''>now</span>
  <span m=''4001580''>if</span> <span m=''4001700''>I</span> <span m=''4001760''>want</span>
  <span m=''4001950''>to</span> <span m=''4001990''>actually</span> <span m=''4002370''>solve</span>
  <span m=''4003110''>the</span> <span m=''4004200''>VI</span> <span m=''4007200''>to</span>
  <span m=''4008200''>EJ</span> <span m=''4009790''>case.</span> <span m=''4013370''>What</span>
  <span m=''4013680''>could</span> <span m=''4013890''>happen?</span> </p><p><span
  m=''4015130''>Before</span> <span m=''4015560''>there</span> <span m=''4015660''>was</span>
  <span m=''4016040''>only</span> <span m=''4016250''>one--</span> <span m=''4016900''>we</span>
  <span m=''4017350''>looked</span> <span m=''4017620''>at</span> <span m=''4017790''>what</span>
  <span m=''4018090''>glues</span> <span m=''4019200''>VI</span> <span m=''4019660''>to</span>
  <span m=''4019870''>VI</span> <span m=''4020040''>plus 1</span> <span m=''4020640''>and</span>
  <span m=''4020970''>it</span> <span m=''4021020''>was</span> <span m=''4021160''>one</span>
  <span m=''4021360''>edge.</span> <span m=''4022200''>It was a</span> <span m=''4022250''>little</span>
  <span m=''4022450''>easier</span> <span m=''4022780''>to</span> <span m=''4022850''>think</span>
  <span m=''4023030''>about.</span> <span m=''4025270''>Let''s</span> <span m=''4025490''>not</span>
  <span m=''4025630''>think</span> <span m=''4025780''>about</span> <span m=''4025950''>the</span>
  <span m=''4026030''>whole</span> <span m=''4026410''>edge,</span> <span m=''4026690''>but</span>
  <span m=''4026810''>let''s</span> <span m=''4026980''>think</span> <span m=''4027160''>about</span>
  <span m=''4027570''>locally</span> <span m=''4028120''>what</span> <span m=''4028340''>happens</span>
  <span m=''4029900''>just</span> <span m=''4030250''>after</span> <span m=''4030510''>VI.</span>
  <span m=''4031410''>Something</span> <span m=''4031840''>gets</span> <span m=''4031990''>glued</span>
  <span m=''4032200''>there.</span> </p><p><span m=''4033480''>Now</span> <span m=''4033580''>it</span>
  <span m=''4033650''>could</span> <span m=''4033920''>be</span> <span m=''4034690''>EJ</span>
  <span m=''4035210''>actually</span> <span m=''4035570''>gets</span> <span m=''4035760''>glued</span>
  <span m=''4035940''>there.</span> <span m=''4036100''>It could</span> <span m=''4036260''>be</span>
  <span m=''4036380''>we</span> <span m=''4036520''>continue</span> <span m=''4036970''>gluing.</span>
  <span m=''4037290''>That''s</span> <span m=''4037710''>kind</span> <span m=''4037870''>of</span>
  <span m=''4037910''>like</span> <span m=''4038100''>zipping,</span> <span m=''4038580''>although</span>
  <span m=''4038980''>not</span> <span m=''4039380''>exactly</span> <span m=''4039720''>what</span>
  <span m=''4039810''>we were</span> <span m=''4039990''>calling</span> <span m=''4040280''>zipping</span>
  <span m=''4040590''>before.</span> <span m=''4041650''>Here</span> <span m=''4043640''>I</span>
  <span m=''4043720''>call it</span> <span m=''4043980''>zipping,</span> <span m=''4045580''>good</span>
  <span m=''4045680''>choice.</span> </p><p><span m=''4047200''>So</span> <span m=''4047380''>one</span>
  <span m=''4047550''>option</span> <span m=''4047870''>is</span> <span m=''4048010''>that</span>
  <span m=''4048110''>you</span> <span m=''4048350''>zip</span> <span m=''4049010''>for</span>
  <span m=''4049480''>a</span> <span m=''4049560''>little</span> <span m=''4049800''>while.</span>
  <span m=''4050620''>Now,</span> <span m=''4050730''>how</span> <span m=''4050990''>long</span>
  <span m=''4051290''>would</span> <span m=''4051430''>you</span> <span m=''4051650''>zip?</span>
  <span m=''4052440''>A</span> <span m=''4052520''>couple</span> <span m=''4052820''>options.</span>
  <span m=''4053930''>You</span> <span m=''4054210''>zip</span> <span m=''4054520''>until</span>
  <span m=''4054920''>you</span> <span m=''4055080''>hit</span> <span m=''4055200''>a</span>
  <span m=''4055250''>vertex,</span> <span m=''4055690''>you</span> <span m=''4055760''>can''t</span>
  <span m=''4055980''>stop</span> <span m=''4056250''>in</span> <span m=''4056310''>the</span>
  <span m=''4056390''>middle</span> <span m=''4056850''>of</span> <span m=''4056990''>two</span>
  <span m=''4057170''>edges.</span> </p><p><span m=''4058240''>So</span> <span m=''4058300''>maybe</span>
  <span m=''4058630''>you</span> <span m=''4058710''>hit</span> <span m=''4058830''>a</span>
  <span m=''4058870''>vertex</span> <span m=''4059270''>here</span> <span m=''4059440''>first,</span>
  <span m=''4060160''>maybe</span> <span m=''4060410''>you</span> <span m=''4060500''>hit</span>
  <span m=''4060630''>a</span> <span m=''4060670''>vertex</span> <span m=''4061060''>here</span>
  <span m=''4061260''>first,</span> <span m=''4061630''>and</span> <span m=''4061700''>the</span>
  <span m=''4061750''>next</span> <span m=''4061970''>vertex</span> <span m=''4062330''>here
  is</span> <span m=''4062610''>farther</span> <span m=''4062920''>away.</span> <span
  m=''4064520''>So</span> <span m=''4064600''>there''s</span> <span m=''4064980''>two</span>
  <span m=''4065130''>pictures.</span> <span m=''4066450''>Let</span> <span m=''4066570''>me</span>
  <span m=''4066660''>draw</span> <span m=''4066840''>the</span> <span m=''4066970''>two</span>
  <span m=''4067090''>pictures.</span> <span m=''4068841''>It</span> <span m=''4069220''>could</span>
  <span m=''4069410''>be</span> <span m=''4069780''>hit</span> <span m=''4070130''>you
  hit</span> <span m=''4070280''>VI</span> <span m=''4070585''>plus 1</span> <span
  m=''4070890''>first.</span> </p><p><span m=''4076320''>So</span> <span m=''4076500''>here''s</span>
  <span m=''4076960''>EJ.</span> <span m=''4078690''>It</span> <span m=''4078850''>could</span>
  <span m=''4079090''>be</span> <span m=''4079650''>you</span> <span m=''4080096''>hit</span>
  <span m=''4081434''>the</span> <span m=''4082620''>vertex</span> <span m=''4083110''>of</span>
  <span m=''4083190''>EJ</span> <span m=''4083550''>first.</span> <span m=''4091330''>In</span>
  <span m=''4091510''>this</span> <span m=''4091710''>case,</span> <span m=''4092460''>you</span>
  <span m=''4092560''>get</span> <span m=''4092670''>a</span> <span m=''4092720''>sub-problem</span>
  <span m=''4093380''>which</span> <span m=''4093470''>is</span> <span m=''4093680''>VI
  plus</span> <span m=''4093840''>1</span> <span m=''4095490''>to</span> <span m=''4095670''>EJ.</span>
  <span m=''4096550''>These</span> <span m=''4096790''>are</span> <span m=''4096890''>glued</span>
  <span m=''4097140''>to</span> <span m=''4097250''>each</span> <span m=''4097399''>other.</span>
  <span m=''4098910''>In</span> <span m=''4098930''>this</span> <span m=''4099109''>case,</span>
  <span m=''4099569''>you</span> <span m=''4099729''>get</span> <span m=''4100210''>this</span>
  <span m=''4100580''>vertex,</span> <span m=''4101130''>which</span> <span m=''4101350''>I</span>
  <span m=''4101380''>think</span> <span m=''4101560''>is</span> <span m=''4101680''>VJ</span>
  <span m=''4103350''>gets</span> <span m=''4103640''>glued</span> <span m=''4103979''>to</span>
  <span m=''4104200''>the</span> <span m=''4104420''>edge</span> <span m=''4104850''>EI,</span>
  <span m=''4107910''>which</span> <span m=''4108090''>is</span> <span m=''4108180''>just</span>
  <span m=''4108830''>the</span> <span m=''4108920''>symmetric</span> <span m=''4110010''>case</span>
  <span m=''4110275''>I was</span> <span m=''4110540''>talking</span> <span m=''4110850''>about</span>
  <span m=''4111000''>here.</span> </p><p><span m=''4113460''>Edge</span> <span m=''4113870''>EI</span>
  <span m=''4114090''>is</span> <span m=''4114260''>glued</span> <span m=''4114500''>to</span>
  <span m=''4114660''>Vertex</span> <span m=''4115100''>VJ.</span> <span m=''4117319''>So</span>
  <span m=''4117520''>those</span> <span m=''4117700''>are</span> <span m=''4117760''>smaller</span>
  <span m=''4118149''>sub-problems.</span> <span m=''4118819''>You</span> <span m=''4118960''>solve</span>
  <span m=''4119260''>those,</span> <span m=''4120120''>and</span> <span m=''4120290''>then</span>
  <span m=''4120529''>from</span> <span m=''4120830''>that</span> <span m=''4121069''>you
  will</span> <span m=''4121370''>see</span> <span m=''4121620''>whether</span> <span
  m=''4121880''>this</span> <span m=''4122149''>actually</span> <span m=''4122439''>gives</span>
  <span m=''4122569''>you</span> <span m=''4122630''>a</span> <span m=''4122680''>solution</span>
  <span m=''4123149''>to</span> <span m=''4123270''>the</span> <span m=''4123370''>original</span>
  <span m=''4124240''>sub-problem</span> <span m=''4124700''>you</span> <span m=''4124840''>wanted</span>
  <span m=''4125000''>to</span> <span m=''4125090''>solve.</span> <span m=''4127250''>That''s</span>
  <span m=''4127560''>the</span> <span m=''4127660''>zip</span> <span m=''4127890''>case.</span>
  </p><p><span m=''4128670''>There''s</span> <span m=''4128859''>another</span> <span
  m=''4129109''>case</span> <span m=''4130250''>which</span> <span m=''4131470''>we</span>
  <span m=''4131569''>call</span> <span m=''4131920''>tug.</span> <span m=''4135689''>In</span>
  <span m=''4135970''>the</span> <span m=''4136069''>tug</span> <span m=''4136370''>case--</span>
  <span m=''4138200''>so</span> <span m=''4138350''>that</span> <span m=''4138609''>was</span>
  <span m=''4139000''>supposing,</span> <span m=''4139720''>we''ll</span> <span m=''4139840''>maybe</span>
  <span m=''4140189''>nothing</span> <span m=''4140689''>else</span> <span m=''4140939''>gets</span>
  <span m=''4141140''>glued</span> <span m=''4141359''>in</span> <span m=''4141490''>here.</span>
  <span m=''4143590''>But</span> <span m=''4143760''>maybe</span> <span m=''4144100''>another</span>
  <span m=''4144340''>vertex</span> <span m=''4144760''>gets</span> <span m=''4144920''>glued</span>
  <span m=''4145100''>in</span> <span m=''4145229''>there,</span> <span m=''4145540''>that''s</span>
  <span m=''4145859''>the</span> <span m=''4146100''>tug.</span> <span m=''4146439''>To</span>
  <span m=''4146540''>pick</span> <span m=''4146810''>a</span> <span m=''4146870''>vertex,</span>
  <span m=''4147630''>I</span> <span m=''4147770''>pull</span> <span m=''4148040''>it</span>
  <span m=''4148290''>in.</span> </p><p><span m=''4149750''>So</span> <span m=''4149990''>in</span>
  <span m=''4150069''>that</span> <span m=''4150260''>case</span> <span m=''4150660''>we</span>
  <span m=''4150830''>get</span> <span m=''4155740''>a</span> <span m=''4156200''>picture</span>
  <span m=''4156470''>like</span> <span m=''4156649''>this.</span> <span m=''4160770''>So</span>
  <span m=''4160790''>here''s</span> <span m=''4161220''>EJ,</span> <span m=''4162460''>here''s</span>
  <span m=''4162760''>VI,</span> <span m=''4164439''>and</span> <span m=''4164590''>now</span>
  <span m=''4164760''>there''s</span> <span m=''4164880''>some</span> <span m=''4165090''>other</span>
  <span m=''4165260''>vertex</span> <span m=''4166250''>VK</span> <span m=''4167899''>that</span>
  <span m=''4167920''>gets</span> <span m=''4168250''>glued</span> <span m=''4168430''>in</span>
  <span m=''4168529''>there.</span> <span m=''4169060''>Which</span> <span m=''4169250''>vertex?</span>
  <span m=''4169779''>I</span> <span m=''4169899''>don''t</span> <span m=''4170029''>know,</span>
  <span m=''4170339''>try</span> <span m=''4170649''>them</span> <span m=''4170750''>all.</span>
  </p><p><span m=''4172510''>Just</span> <span m=''4172720''>like</span> <span m=''4172859''>before,</span>
  <span m=''4173240''>before we were</span> <span m=''4173630''>choosing</span> <span
  m=''4173960''>an</span> <span m=''4174050''>edge</span> <span m=''4174319''>that</span>
  <span m=''4174420''>gets</span> <span m=''4174630''>glued</span> <span m=''4174819''>in.</span>
  <span m=''4175850''>Now</span> <span m=''4176069''>it''s</span> <span m=''4176189''>not</span>
  <span m=''4176310''>necessarily</span> <span m=''4176670''>a whole edge,</span>
  <span m=''4177149''>but</span> <span m=''4177520''>if</span> <span m=''4177790''>there''s</span>
  <span m=''4178000''>any</span> <span m=''4178170''>vertex</span> <span m=''4178600''>that</span>
  <span m=''4178660''>glues</span> <span m=''4178859''>in,</span> <span m=''4181020''>pick</span>
  <span m=''4181520''>who''s</span> <span m=''4181750''>the</span> <span m=''4181819''>next</span>
  <span m=''4182069''>one.</span> <span m=''4182720''>And</span> <span m=''4182890''>now</span>
  <span m=''4183050''>I</span> <span m=''4183149''>get</span> <span m=''4183290''>a</span>
  <span m=''4183350''>sub-problem</span> <span m=''4183899''>here</span> <span m=''4184100''>which</span>
  <span m=''4184279''>is</span> <span m=''4184399''>VI</span> <span m=''4185740''>to</span>
  <span m=''4185850''>VK.</span> <span m=''4186930''>I</span> <span m=''4187080''>get
  a</span> <span m=''4187319''>sub-problem</span> <span m=''4187680''>here</span>
  <span m=''4188410''>which</span> <span m=''4188680''>is</span> <span m=''4189479''>VK</span>
  <span m=''4190259''>to</span> <span m=''4191060''>EJ.</span> </p><p><span m=''4193210''>I</span>
  <span m=''4193359''>solve</span> <span m=''4193700''>each</span> <span m=''4193890''>of</span>
  <span m=''4193960''>those,</span> <span m=''4194630''>I</span> <span m=''4194790''>take</span>
  <span m=''4195020''>the</span> <span m=''4195090''>cross-product,</span> <span m=''4196610''>I</span>
  <span m=''4196810''>do</span> <span m=''4196950''>that</span> <span m=''4197140''>for</span>
  <span m=''4197280''>all</span> <span m=''4197400''>values</span> <span m=''4197700''>of</span>
  <span m=''4197790''>K</span> <span m=''4198590''>just</span> <span m=''4198840''>like</span>
  <span m=''4199130''>I</span> <span m=''4199290''>did</span> <span m=''4200380''>here,</span>
  <span m=''4201680''>except</span> <span m=''4201810''>the</span> <span m=''4201890''>labels</span>
  <span m=''4202250''>have</span> <span m=''4202340''>changed</span> <span m=''4202650''>a</span>
  <span m=''4202680''>little</span> <span m=''4202850''>bit,</span> <span m=''4203680''>and</span>
  <span m=''4203870''>I</span> <span m=''4203920''>find</span> <span m=''4204210''>all</span>
  <span m=''4204330''>the</span> <span m=''4204440''>outputs.</span> <span m=''4204970''>And</span>
  <span m=''4205190''>again,</span> <span m=''4205570''>you</span> <span m=''4205600''>can</span>
  <span m=''4205740''>show</span> <span m=''4205970''>that</span> <span m=''4206130''>it''s</span>
  <span m=''4206300''>exponential</span> <span m=''4206850''>time</span> <span m=''4207230''>at
  most.</span> <span m=''4209390''>So</span> <span m=''4211510''>that''s an</span>
  <span m=''4211720''>algorithm.</span> </p><p><span m=''4213990''>Now,</span> <span
  m=''4216190''>it''s</span> <span m=''4216380''>exponential</span> <span m=''4216910''>time,</span>
  <span m=''4217560''>but</span> <span m=''4217820''>really</span> <span m=''4218190''>it''s</span>
  <span m=''4218370''>not</span> <span m=''4218580''>so</span> <span m=''4218840''>bad</span>
  <span m=''4219750''>because</span> <span m=''4221700''>it''s</span> <span m=''4221930''>at</span>
  <span m=''4222020''>most</span> <span m=''4222450''>cubic</span> <span m=''4222910''>like</span>
  <span m=''4223110''>we</span> <span m=''4223220''>had</span> <span m=''4223450''>before.</span>
  <span m=''4224680''>But</span> <span m=''4224840''>we''re</span> <span m=''4224960''>doing</span>
  <span m=''4225260''>extra</span> <span m=''4225650''>work,</span> <span m=''4226140''>which</span>
  <span m=''4226360''>is</span> <span m=''4226450''>something</span> <span m=''4226920''>like</span>
  <span m=''4227170''>the</span> <span m=''4227320''>number</span> <span m=''4227720''>of</span>
  <span m=''4228790''>gluings</span> <span m=''4231510''>dealt</span> <span m=''4231900''>with</span>
  <span m=''4232170''>at</span> <span m=''4232270''>each</span> <span m=''4232460''>stage</span>
  <span m=''4234230''>per</span> <span m=''4235640''>sub-problem.</span> <span m=''4237590''>Now,</span>
  <span m=''4237780''>it''s</span> <span m=''4237990''>not</span> <span m=''4238160''>just</span>
  <span m=''4238340''>the</span> <span m=''4238420''>number</span> <span m=''4238660''>of</span>
  <span m=''4238730''>actual</span> <span m=''4239100''>solutions,</span> <span m=''4241310''>because</span>
  <span m=''4242160''>we</span> <span m=''4242440''>generate</span> <span m=''4242850''>all</span>
  <span m=''4243170''>possible</span> <span m=''4243710''>solutions</span> <span m=''4244150''>and
  then</span> <span m=''4244330''>check</span> <span m=''4244570''>whether</span>
  <span m=''4244760''>they''re</span> <span m=''4244930''>Alexandroff.</span> </p><p><span
  m=''4246370''>So</span> <span m=''4246990''>if</span> <span m=''4248550''>you</span>
  <span m=''4248640''>have</span> <span m=''4248850''>some</span> <span m=''4249040''>example
  that</span> <span m=''4249480''>happens</span> <span m=''4249950''>to</span> <span
  m=''4250040''>be</span> <span m=''4250190''>unique</span> <span m=''4250620''>in</span>
  <span m=''4250720''>the</span> <span m=''4250820''>way</span> <span m=''4250940''>that</span>
  <span m=''4251070''>it</span> <span m=''4251140''>glues</span> <span m=''4251390''>up,</span>
  <span m=''4252150''>this</span> <span m=''4252850''>bound</span> <span m=''4253140''>will</span>
  <span m=''4253230''>not</span> <span m=''4253410''>actually</span> <span m=''4253680''>be</span>
  <span m=''4253780''>very</span> <span m=''4254000''>good.</span> <span m=''4254240''>It''s
  still</span> <span m=''4254440''>going</span> <span m=''4254540''>to</span> <span
  m=''4254600''>consider</span> <span m=''4254980''>lots</span> <span m=''4255270''>of</span>
  <span m=''4255350''>options.</span> <span m=''4256120''>But</span> <span m=''4257790''>in</span>
  <span m=''4258040''>the</span> <span m=''4258160''>case</span> <span m=''4259290''>of</span>
  <span m=''4260510''>bounded</span> <span m=''4260960''>sharpness,</span> <span m=''4262730''>where</span>
  <span m=''4262850''>the</span> <span m=''4262950''>number</span> <span m=''4263250''>of</span>
  <span m=''4263320''>gluings</span> <span m=''4263650''>is</span> <span m=''4263830''>only</span>
  <span m=''4264150''>polynomial--</span> <span m=''4265275''>and</span> <span m=''4265550''>it''s</span>
  <span m=''4265830''>polynomial</span> <span m=''4266350''>for a</span> <span m=''4266570''>strong</span>
  <span m=''4266900''>reason</span> <span m=''4267290''>that</span> <span m=''4267420''>the</span>
  <span m=''4267520''>trees</span> <span m=''4267780''>can''t</span> <span m=''4267980''>get</span>
  <span m=''4268120''>very</span> <span m=''4268310''>complicated--</span> <span m=''4270320''>then</span>
  <span m=''4270650''>we</span> <span m=''4270770''>can</span> <span m=''4270920''>actually</span>
  <span m=''4271390''>turn</span> <span m=''4271670''>this</span> <span m=''4271960''>into</span>
  <span m=''4272240''>a</span> <span m=''4272300''>polynomial</span> <span m=''4272910''>algorithm.</span>
  </p><p><span m=''4273290''>This</span> <span m=''4273470''>will</span> <span m=''4273570''>be</span>
  <span m=''4273740''>n</span> <span m=''4273950''>cubed</span> <span m=''4274340''>times</span>
  <span m=''4274830''>that</span> <span m=''4275080''>bound.</span> <span m=''4275880''>As</span>
  <span m=''4276260''>long</span> <span m=''4276530''>as</span> <span m=''4276610''>your</span>
  <span m=''4276810''>polygon</span> <span m=''4277210''>is</span> <span m=''4277330''>bounded</span>
  <span m=''4277620''>sharpness,</span> <span m=''4279140''>you</span> <span m=''4279310''>can</span>
  <span m=''4279390''>show</span> <span m=''4279570''>that</span> <span m=''4279720''>at</span>
  <span m=''4279810''>every</span> <span m=''4280070''>stage</span> <span m=''4280480''>of</span>
  <span m=''4280560''>course</span> <span m=''4281030''>the</span> <span m=''4281130''>number</span>
  <span m=''4281350''>of</span> <span m=''4281550''>gluings</span> <span m=''4281730''>will</span>
  <span m=''4281880''>also</span> <span m=''4282160''>be</span> <span m=''4282290''>polynomial.</span>
  <span m=''4284170''>And</span> <span m=''4284330''>so</span> <span m=''4284470''>then</span>
  <span m=''4284710''>even</span> <span m=''4284950''>the</span> <span m=''4285030''>number</span>
  <span m=''4285260''>of</span> <span m=''4285370''>gluings</span> <span m=''4285690''>you</span>
  <span m=''4285770''>have</span> <span m=''4285870''>to</span> <span m=''4285990''>consider</span>
  <span m=''4286480''>and</span> <span m=''4286580''>check</span> <span m=''4286960''>will</span>
  <span m=''4287080''>be</span> <span m=''4287230''>polynomial.</span> <span m=''4287750''>So</span>
  <span m=''4287880''>the</span> <span m=''4287950''>whole</span> <span m=''4288130''>thing</span>
  <span m=''4288340''>will</span> <span m=''4288460''>be</span> <span m=''4289080''>polynomial</span>
  <span m=''4289630''>time,</span> <span m=''4289970''>that</span> <span m=''4290190''>is</span>
  <span m=''4291020''>this</span> <span m=''4291240''>result</span> <span m=''4292720''>and</span>
  <span m=''4293180''>this</span> <span m=''4293350''>result.</span> </p><p><span
  m=''4296810''>So</span> <span m=''4297300''>if</span> <span m=''4297590''>your</span>
  <span m=''4297690''>polygon</span> <span m=''4298130''>is</span> <span m=''4298240''>vaguely</span>
  <span m=''4298580''>reasonable,</span> <span m=''4299400''>this</span> <span m=''4299550''>is</span>
  <span m=''4299660''>actually a</span> <span m=''4300060''>really</span> <span m=''4300260''>good</span>
  <span m=''4300390''>algorithm.</span> <span m=''4300750''>This</span> <span m=''4300840''>algorithm</span>
  <span m=''4301240''>has</span> <span m=''4301430''>been</span> <span m=''4301560''>implemented</span>
  <span m=''4302140''>by</span> <span m=''4302300''>two</span> <span m=''4302570''>groups,</span>
  <span m=''4303060''>one</span> <span m=''4303330''>[INAUDIBLE]</span> <span m=''4304780''>in</span>
  <span m=''4304840''>mathematica</span> <span m=''4305990''>and</span> <span m=''4306200''>another</span>
  <span m=''4307060''>[INAUDIBLE],</span> <span m=''4307855''>which</span> <span m=''4308150''>sadly</span>
  <span m=''4308580''>is</span> <span m=''4308680''>not--</span> <span m=''4309020''>his</span>
  <span m=''4309400''>implementation</span> <span m=''4309940''>used</span> <span
  m=''4310120''>to</span> <span m=''4310160''>be</span> <span m=''4310250''>on</span>
  <span m=''4310330''>the</span> <span m=''4310400''>web,</span> <span m=''4310660''>I</span>
  <span m=''4310770''>can''t</span> <span m=''4311030''>find</span> <span m=''4311270''>it</span>
  <span m=''4311360''>anymore.</span> <span m=''4313400''>But</span> <span m=''4314170''>you</span>
  <span m=''4314960''>get</span> <span m=''4315280''>either</span> <span m=''4315550''>implementation,</span>
  <span m=''4316640''>plug-in</span> <span m=''4317180''>your</span> <span m=''4317340''>polygon,</span>
  <span m=''4317610''>and</span> <span m=''4317880''>it</span> <span m=''4317990''>just</span>
  <span m=''4318160''>lists</span> <span m=''4318460''>all</span> <span m=''4318800''>the</span>
  <span m=''4318870''>possible</span> <span m=''4319250''>gluings.</span> </p><p><span
  m=''4320850''>So</span> <span m=''4321720''>that''s</span> <span m=''4322060''>all</span>
  <span m=''4322170''>the</span> <span m=''4322260''>theory</span> <span m=''4322600''>for</span>
  <span m=''4322750''>today.</span> <span m=''4323390''>Now</span> <span m=''4323510''>I</span>
  <span m=''4323590''>want</span> <span m=''4323730''>to</span> <span m=''4323770''>show</span>
  <span m=''4323920''>you</span> <span m=''4324040''>a</span> <span m=''4324070''>whole</span>
  <span m=''4324220''>bunch</span> <span m=''4324440''>of</span> <span m=''4324530''>gluings</span>
  <span m=''4325150''>for</span> <span m=''4325350''>fun.</span> <span m=''4326110''>Once</span>
  <span m=''4326290''>you</span> <span m=''4326370''>have</span> <span m=''4326660''>all</span>
  <span m=''4326920''>the</span> <span m=''4327030''>stuff,</span> <span m=''4327450''>we</span>
  <span m=''4327530''>have</span> <span m=''4327650''>these</span> <span m=''4327800''>programs,</span>
  <span m=''4328810''>you</span> <span m=''4328990''>get</span> <span m=''4329160''>to</span>
  <span m=''4329240''>play.</span> </p><p><span m=''4330670''>So</span> <span m=''4331750''>our</span>
  <span m=''4331940''>first</span> <span m=''4332840''>play</span> <span m=''4333440''>is</span>
  <span m=''4335840''>not</span> <span m=''4336330''>that.</span> <span m=''4336890''>That
  was the</span> <span m=''4337160''>last</span> <span m=''4337540''>play.</span>
  <span m=''4338800''>First</span> <span m=''4339050''>thing,</span> <span m=''4339410''>we</span>
  <span m=''4339550''>saw</span> <span m=''4339720''>this</span> <span m=''4339890''>before.</span>
  <span m=''4340330''>I''ll</span> <span m=''4340430''>just</span> <span m=''4340680''>remind</span>
  <span m=''4341060''>you</span> <span m=''4342060''>what</span> <span m=''4342230''>it</span>
  <span m=''4342300''>looks</span> <span m=''4342570''>like</span> <span m=''4343090''>and</span>
  <span m=''4343320''>tell</span> <span m=''4343490''>you</span> <span m=''4343640''>a</span>
  <span m=''4343680''>little</span> <span m=''4343900''>bit</span> <span m=''4344050''>about</span>
  <span m=''4344690''>what''s</span> <span m=''4344870''>going</span> <span m=''4345110''>on</span>
  <span m=''4345250''>here.</span> </p><p><span m=''4345440''>So</span> <span m=''4345580''>this</span>
  <span m=''4345800''>was</span> <span m=''4346040''>the</span> <span m=''4347650''>cube.</span>
  <span m=''4348660''>And</span> <span m=''4348920''>then</span> <span m=''4349110''>it''s</span>
  <span m=''4349300''>eventually</span> <span m=''4349660''>going</span> <span m=''4349770''>to</span>
  <span m=''4349830''>fold</span> <span m=''4350070''>into</span> <span m=''4350230''>a
  cross.</span> <span m=''4351130''>The</span> <span m=''4351240''>real</span> <span
  m=''4351550''>study</span> <span m=''4351870''>here</span> <span m=''4352120''>is</span>
  <span m=''4352320''>for</span> <span m=''4352500''>the</span> <span m=''4352610''>Latin</span>
  <span m=''4352950''>Cross--</span> <span m=''4353360''>which</span> <span m=''4353520''>is</span>
  <span m=''4353570''>the</span> <span m=''4353660''>picture</span> <span m=''4353930''>I</span>
  <span m=''4353980''>keep</span> <span m=''4354200''>drawing</span> <span m=''4355710''>at</span>
  <span m=''4355840''>the</span> <span m=''4355920''>beginning</span> <span m=''4356310''>of</span>
  <span m=''4356500''>lecture</span> <span m=''4357580''>and</span> <span m=''4357910''>which</span>
  <span m=''4358090''>will</span> <span m=''4358630''>now</span> <span m=''4358830''>be</span>
  <span m=''4359010''>unfolded--</span> <span m=''4359790''>what</span> <span m=''4360100''>other</span>
  <span m=''4361320''>convex</span> <span m=''4361760''>polyhedra</span> <span m=''4362260''>can</span>
  <span m=''4362410''>you</span> <span m=''4362520''>glue</span> <span m=''4363100''>that</span>
  <span m=''4363370''>polygon</span> <span m=''4363910''>into?</span> <span m=''4364280''>So</span>
  <span m=''4364440''>it''s</span> <span m=''4364650''>like</span> <span m=''4365670''>you''re</span>
  <span m=''4366080''>not</span> <span m=''4366290''>told</span> <span m=''4366570''>what
  the</span> <span m=''4366650''>creases</span> <span m=''4367020''>are.</span> <span
  m=''4367670''>You</span> <span m=''4367770''>just</span> <span m=''4367970''>want</span>
  <span m=''4368080''>to</span> <span m=''4368140''>look</span> <span m=''4368330''>at</span>
  <span m=''4368410''>gluings,</span> <span m=''4369160''>the</span> <span m=''4369370''>resulting</span>
  <span m=''4369760''>creases.</span> </p><p><span m=''4370940''>This</span> <span
  m=''4371030''>is</span> <span m=''4371180''>one</span> <span m=''4371650''>convex</span>
  <span m=''4372170''>polyhedron</span> <span m=''4372670''>you</span> <span m=''4372810''>can</span>
  <span m=''4372960''>make.</span> <span m=''4373990''>This</span> <span m=''4374370''>is</span>
  <span m=''4374470''>something</span> <span m=''4374770''>that</span> <span m=''4374860''>can</span>
  <span m=''4375000''>come from</span> <span m=''4375320''>Alexandroff''s</span> <span
  m=''4375830''>theorem</span> <span m=''4376190''>that you</span> <span m=''4376350''>actually</span>
  <span m=''4376600''>get</span> <span m=''4376700''>a</span> <span m=''4376750''>flat,</span>
  <span m=''4377180''>doubly-covered</span> <span m=''4378180''>convex</span> <span
  m=''4378660''>polygon.</span> <span m=''4379780''>It''s</span> <span m=''4379950''>technically</span>
  <span m=''4380480''>a</span> <span m=''4380540''>polyhedron,</span> <span m=''4381110''>according</span>
  <span m=''4381420''>to</span> <span m=''4381510''>Alexandroff.</span> <span m=''4383320''>These</span>
  <span m=''4383650''>are</span> <span m=''4383780''>all</span> <span m=''4384220''>edge-to-edge</span>
  <span m=''4384860''>gluings</span> <span m=''4385470''>if</span> <span m=''4386400''>the</span>
  <span m=''4386740''>length</span> <span m=''4387130''>two</span> <span m=''4387330''>edges</span>
  <span m=''4387800''>are</span> <span m=''4387930''>actually</span> <span m=''4388180''>subdivided</span>
  <span m=''4388690''>into</span> <span m=''4388960''>two</span> <span m=''4389160''>length</span>
  <span m=''4389380''>one</span> <span m=''4389580''>edges.</span> <span m=''4391070''>And</span>
  <span m=''4391270''>this</span> <span m=''4391470''>video</span> <span m=''4391970''>only</span>
  <span m=''4392340''>enumerates</span> <span m=''4393210''>the</span> <span m=''4393370''>edge-to-edge</span>
  <span m=''4393990''>gluings,</span> <span m=''4394400''>because</span> <span m=''4394710''>at</span>
  <span m=''4394820''>this</span> <span m=''4395020''>point</span> <span m=''4395450''>we</span>
  <span m=''4395480''>only</span> <span m=''4395700''>had</span> <span m=''4395900''>the</span>
  <span m=''4396020''>edge-to-edge</span> <span m=''4396490''>algorithm.</span> </p><p><span
  m=''4397355''>I</span> <span m=''4397700''>forget,</span> <span m=''4398040''>this</span>
  <span m=''4398210''>video</span> <span m=''4398510''>is</span> <span m=''4398640''>''98,</span>
  <span m=''4399530''>I</span> <span m=''4399640''>think.</span> <span m=''4400090''>This</span>
  <span m=''4400340''>algorithm</span> <span m=''4400790''>was in</span> <span m=''4400930''>''96,</span>
  <span m=''4401425''>so</span> <span m=''4401920''>they</span> <span m=''4402060''>had
  just</span> <span m=''4402290''>implemented</span> <span m=''4402690''>that.</span>
  <span m=''4403690''>And</span> <span m=''4403960''>then</span> <span m=''4404540''>that''s</span>
  <span m=''4404730''>when</span> <span m=''4404870''>I</span> <span m=''4404970''>joined.</span>
  <span m=''4405390''>I was</span> <span m=''4405540''>just</span> <span m=''4405810''>starting</span>
  <span m=''4406170''>out</span> <span m=''4406300''>as</span> <span m=''4406390''>a</span>
  <span m=''4406440''>grad</span> <span m=''4406670''>student</span> <span m=''4407060''>and
  said,</span> <span m=''4407260''>OK</span> <span m=''4408270''>let''s</span> <span
  m=''4408430''>make</span> <span m=''4408590''>a</span> <span m=''4408640''>video.</span>
  <span m=''4409030''>That would be</span> <span m=''4409150''>cool.</span> </p><p><span
  m=''4410140''>So</span> <span m=''4410920''>I</span> <span m=''4411040''>think</span>
  <span m=''4411190''>there''s</span> <span m=''4411320''>one</span> <span m=''4411480''>more.</span>
  <span m=''4413160''>And</span> <span m=''4413550''>this</span> <span m=''4413710''>is
  the</span> <span m=''4413830''>only</span> <span m=''4414020''>one</span> <span
  m=''4414230''>where</span> <span m=''4414960''>we</span> <span m=''4415160''>actually</span>
  <span m=''4415410''>have the</span> <span m=''4415580''>animations.</span> <span
  m=''4417380''>This</span> <span m=''4418260''>octahedron,</span> <span m=''4419160''>this</span>
  <span m=''4419330''>was</span> <span m=''4419480''>tricky</span> <span m=''4419770''>to</span>
  <span m=''4419860''>find,</span> <span m=''4420170''>beceause</span> <span m=''4420360''>at
  this</span> <span m=''4420520''>point</span> <span m=''4420730''>there</span> <span
  m=''4420810''>were</span> <span m=''4420880''>no</span> <span m=''4421020''>algorithms</span>
  <span m=''4421560''>for</span> <span m=''4421680''>Alexandroff''s</span> <span m=''4422210''>theorem.</span>
  <span m=''4422920''>So</span> <span m=''4423050''>we</span> <span m=''4423170''>found</span>
  <span m=''4423490''>it</span> <span m=''4423620''>by</span> <span m=''4424240''>taking</span>
  <span m=''4424560''>a</span> <span m=''4424610''>piece</span> <span m=''4424850''>of</span>
  <span m=''4425080''>cardboard,</span> <span m=''4426080''>gluing</span> <span m=''4426400''>it</span>
  <span m=''4426470''>up,</span> <span m=''4427420''>getting</span> <span m=''4427650''>a</span>
  <span m=''4427710''>protractor,</span> <span m=''4428470''>and</span> <span m=''4428610''>measuring</span>
  <span m=''4428950''>all</span> <span m=''4429050''>the</span> <span m=''4429140''>dihedral</span>
  <span m=''4429410''>angles,</span> <span m=''4430350''>and</span> <span m=''4430560''>then</span>
  <span m=''4430760''>typing</span> <span m=''4431000''>them in.</span> <span m=''4431600''>And</span>
  <span m=''4431780''>Lo</span> <span m=''4431900''>and</span> <span m=''4431970''>behold,</span>
  <span m=''4433050''>in</span> <span m=''4433200''>that</span> <span m=''4433590''>animation</span>
  <span m=''4434170''>they</span> <span m=''4434270''>don''t</span> <span m=''4434530''>perfectly</span>
  <span m=''4434960''>close</span> <span m=''4435220''>up,</span> <span m=''4435360''>but</span>
  <span m=''4435470''>it''s</span> <span m=''4435600''>very</span> <span m=''4435800''>close,</span>
  <span m=''4438090''>up</span> <span m=''4438240''>to</span> <span m=''4438360''>the</span>
  <span m=''4438630''>measurement</span> <span m=''4439040''>error</span> <span m=''4439340''>of</span>
  <span m=''4439480''>the</span> <span m=''4439570''>protractor.</span> </p><p><span
  m=''4440110''>So</span> <span m=''4440330''>for</span> <span m=''4440530''>edge-to-edge</span>
  <span m=''4441050''>gluings,</span> <span m=''4441910''>there are</span> <span m=''4442040''>exactly</span>
  <span m=''4442400''>five</span> <span m=''4442890''>convex</span> <span m=''4443290''>polyhedra</span>
  <span m=''4443790''>you</span> <span m=''4443930''>can</span> <span m=''4444050''>make</span>
  <span m=''4444250''>from</span> <span m=''4444380''>that</span> <span m=''4444550''>cross.</span>
  <span m=''4448760''>But</span> <span m=''4448980''>if</span> <span m=''4449110''>you</span>
  <span m=''4449230''>allow</span> <span m=''4449370''>non-edge-to-edge</span> <span
  m=''4450190''>gluings--</span> <span m=''4450520''>and</span> <span m=''4450860''>so</span>
  <span m=''4451010''>some</span> <span m=''4451230''>years</span> <span m=''4451470''>later</span>
  <span m=''4451780''>when</span> <span m=''4451890''>we</span> <span m=''4452100''>came</span>
  <span m=''4452310''>up</span> <span m=''4452450''>with</span> <span m=''4452530''>that</span>
  <span m=''4452700''>algorithm</span> <span m=''4453130''>and</span> <span m=''4453260''>implemented</span>
  <span m=''4453770''>it,</span> <span m=''4454190''>we</span> <span m=''4454280''>discovered</span>
  <span m=''4454740''>there</span> <span m=''4454820''>are</span> <span m=''4455010''>85</span>
  <span m=''4456320''>gluings</span> <span m=''4456710''>of</span> <span m=''4456820''>the</span>
  <span m=''4456910''>cross.</span> <span m=''4457870''>This</span> <span m=''4458100''>is</span>
  <span m=''4458530''>only</span> <span m=''4458780''>six</span> <span m=''4459010''>of</span>
  <span m=''4459110''>them.</span> <span m=''4460300''>We''re</span> <span m=''4460500''>going</span>
  <span m=''4460610''>to</span> <span m=''4460710''>do</span> <span m=''4460870''>it</span>
  <span m=''4461320''>starting</span> <span m=''4461660''>with</span> <span m=''4461780''>the</span>
  <span m=''4461870''>cube,</span> <span m=''4462260''>and</span> <span m=''4462390''>then</span>
  <span m=''4462490''>we''re</span> <span m=''4462620''>going</span> <span m=''4462880''>to</span>
  <span m=''4463090''>go</span> <span m=''4463270''>in</span> <span m=''4463470''>increasing</span>
  <span m=''4464060''>order</span> <span m=''4464420''>of</span> <span m=''4464800''>faces.</span>
  </p><p><span m=''4466130''>So</span> <span m=''4466330''>there''s</span> <span m=''4466650''>two</span>
  <span m=''4467730''>flat,</span> <span m=''4468170''>doubly-covered</span> <span
  m=''4469260''>quadrilaterals.</span> <span m=''4470000''>They''re</span> <span m=''4470250''>different.</span>
  <span m=''4472730''>Then</span> <span m=''4473130''>there</span> <span m=''4473370''>is</span>
  <span m=''4473480''>a</span> <span m=''4473530''>bunch</span> <span m=''4473780''>of</span>
  <span m=''4473850''>tetrahedra</span> <span m=''4474170''>that</span> <span m=''4474490''>you</span>
  <span m=''4474670''>can</span> <span m=''4474790''>make.</span> <span m=''4475030''>None</span>
  <span m=''4475180''>of</span> <span m=''4475250''>them</span> <span m=''4475370''>are</span>
  <span m=''4475450''>regular.</span> <span m=''4475990''>One</span> <span m=''4476180''>of</span>
  <span m=''4476270''>them</span> <span m=''4476420''>was</span> <span m=''4476580''>edge-to-edge,</span>
  <span m=''4477360''>I</span> <span m=''4477660''>think</span> <span m=''4477910''>it</span>
  <span m=''4478060''>might</span> <span m=''4478360''>be</span> <span m=''4478490''>this</span>
  <span m=''4478720''>one.</span> <span m=''4480540''>I</span> <span m=''4480630''>think</span>
  <span m=''4480820''>there''s</span> <span m=''4480990''>some</span> <span m=''4481170''>more</span>
  <span m=''4481470''>tetrahedra</span> <span m=''4482490''>at</span> <span m=''4482660''>the</span>
  <span m=''4482760''>top</span> <span m=''4483080''>there.</span> <span m=''4483880''>The</span>
  <span m=''4484140''>blue</span> <span m=''4484350''>labels</span> <span m=''4484700''>here</span>
  <span m=''4484950''>say</span> <span m=''4485600''>what they</span> <span m=''4485730''>are.</span>
  </p><p><span m=''4486390''>For</span> <span m=''4486570''>each</span> <span m=''4486760''>one</span>
  <span m=''4486980''>of</span> <span m=''4487060''>these</span> <span m=''4487420''>we</span>
  <span m=''4488140''>taped</span> <span m=''4488480''>up</span> <span m=''4488650''>the--</span>
  <span m=''4489000''>we</span> <span m=''4489200''>knew</span> <span m=''4489540''>what</span>
  <span m=''4489680''>the</span> <span m=''4489800''>gluing</span> <span m=''4490180''>was.</span>
  <span m=''4490470''>We</span> <span m=''4490620''>taped</span> <span m=''4490970''>it</span>
  <span m=''4491050''>up,</span> <span m=''4491480''>and</span> <span m=''4491660''>then</span>
  <span m=''4491910''>we</span> <span m=''4493050''>played</span> <span m=''4493250''>with</span>
  <span m=''4493410''>it</span> <span m=''4493530''>until</span> <span m=''4493730''>we</span>
  <span m=''4493830''>figured</span> <span m=''4494040''>out,</span> <span m=''4494370''>this</span>
  <span m=''4494540''>must</span> <span m=''4494800''>be</span> <span m=''4494890''>the</span>
  <span m=''4494980''>creases.</span> <span m=''4495470''>Then</span> <span m=''4495650''>we</span>
  <span m=''4495770''>actually</span> <span m=''4496280''>drew</span> <span m=''4496510''>in
  that</span> <span m=''4496850''>create pattern,</span> <span m=''4497250''>folded</span>
  <span m=''4497510''>it</span> <span m=''4497570''>up,</span> <span m=''4497740''>and</span>
  <span m=''4497810''>verified</span> <span m=''4498200''>that</span> <span m=''4498390''>is</span>
  <span m=''4498610''>the</span> <span m=''4498710''>right</span> <span m=''4499490''>answer.</span>
  <span m=''4500370''>Because</span> <span m=''4500550''>again,</span> <span m=''4500850''>at</span>
  <span m=''4500970''>this</span> <span m=''4501120''>point</span> <span m=''4501330''>no</span>
  <span m=''4501520''>algorithm</span> <span m=''4501900''>for</span> <span m=''4502040''>Alexandroff''s</span>
  <span m=''4502630''>theorem.</span> </p><p><span m=''4504260''>More</span> <span
  m=''4504590''>tetrahedra.</span> <span m=''4505200''>Here</span> <span m=''4505420''>we</span>
  <span m=''4505530''>get</span> <span m=''4505740''>to</span> <span m=''4505840''>the</span>
  <span m=''4505950''>five-sided</span> <span m=''4507150''>polyhedra.</span> <span
  m=''4507610''>I</span> <span m=''4507690''>think</span> <span m=''4507980''>this</span>
  <span m=''4508190''>one</span> <span m=''4508690''>is</span> <span m=''4508950''>edge-to-edge</span>
  <span m=''4509400''>and is</span> <span m=''4509870''>in</span> <span m=''4509960''>the</span>
  <span m=''4510030''>video.</span> <span m=''4510730''>It''s a</span> <span m=''4510850''>little</span>
  <span m=''4511010''>hard</span> <span m=''4511190''>to</span> <span m=''4511270''>tell</span>
  <span m=''4511560''>from</span> <span m=''4511830''>the--</span> <span m=''4513580''>actually,</span>
  <span m=''4514360''>you</span> <span m=''4514540''>can</span> <span m=''4514660''>tell</span>
  <span m=''4514830''>from</span> <span m=''4514950''>the</span> <span m=''4515040''>pictures.</span>
  <span m=''4515410''>Here</span> <span m=''4516050''>there''s</span> <span m=''4516300''>two</span>
  <span m=''4516660''>sevens.</span> <span m=''4517240''>That</span> <span m=''4517400''>means</span>
  <span m=''4517610''>seven</span> <span m=''4517970''>glued</span> <span m=''4518170''>to</span>
  <span m=''4518260''>seven.</span> </p><p><span m=''4518580''>That</span> <span m=''4518710''>means</span>
  <span m=''4518890''>this</span> <span m=''4519060''>is</span> <span m=''4519130''>a</span>
  <span m=''4519190''>fold</span> <span m=''4519470''>point,</span> <span m=''4520130''>this</span>
  <span m=''4520310''>edge</span> <span m=''4520500''>is</span> <span m=''4520610''>glued</span>
  <span m=''4520780''>to</span> <span m=''4520860''>that</span> <span m=''4521070''>edge.</span>
  <span m=''4521630''>Over</span> <span m=''4521830''>here,</span> <span m=''4522140''>every</span>
  <span m=''4522420''>edge</span> <span m=''4522580''>has</span> <span m=''4522720''>only</span>
  <span m=''4522910''>one</span> <span m=''4523100''>label,</span> <span m=''4524050''>where</span>
  <span m=''4524170''>again</span> <span m=''4524400''>this</span> <span m=''4524550''>is</span>
  <span m=''4524660''>considered</span> <span m=''4525060''>two</span> <span m=''4525230''>edges.</span>
  <span m=''4526590''>So</span> <span m=''4526620''>this</span> <span m=''4526790''>was</span>
  <span m=''4526930''>the</span> <span m=''4527040''>edge-to-edge</span> <span m=''4527240''>gluing.</span>
  <span m=''4532490''>I</span> <span m=''4532670''>think</span> <span m=''4532890''>a</span>
  <span m=''4532910''>couple</span> <span m=''4533200''>more</span> <span m=''4533480''>slides.</span>
  </p><p><span m=''4534350''>We</span> <span m=''4534615''>get</span> <span m=''4534880''>another</span>
  <span m=''4535160''>pentahedron</span> <span m=''4535960''>and</span> <span m=''4536170''>then</span>
  <span m=''4536590''>starting</span> <span m=''4537000''>to</span> <span m=''4537110''>get</span>
  <span m=''4537290''>hexahedra</span> <span m=''4537730''>other</span> <span m=''4538090''>than</span>
  <span m=''4538280''>the</span> <span m=''4538370''>cube,</span> <span m=''4541480''>lots</span>
  <span m=''4541700''>of</span> <span m=''4541770''>them.</span> <span m=''4542990''>Then</span>
  <span m=''4543210''>we</span> <span m=''4543290''>start</span> <span m=''4543500''>getting</span>
  <span m=''4543760''>octahedra.</span> <span m=''4544340''>The</span> <span m=''4544420''>last</span>
  <span m=''4544750''>one</span> <span m=''4544870''>in</span> <span m=''4544950''>the</span>
  <span m=''4545030''>video</span> <span m=''4545360''>was</span> <span m=''4545550''>octahedron.</span>
  <span m=''4546940''>It''s</span> <span m=''4547060''>not</span> <span m=''4547230''>this</span>
  <span m=''4547410''>one,</span> <span m=''4547610''>this</span> <span m=''4547770''>one</span>
  <span m=''4548690''>has</span> <span m=''4548930''>some</span> <span m=''4549080''>fold</span>
  <span m=''4549310''>points.</span> <span m=''4551141''>It</span> <span m=''4551570''>must</span>
  <span m=''4551890''>be--</span> <span m=''4552710''>these</span> <span m=''4552880''>are</span>
  <span m=''4552960''>all</span> <span m=''4553330''>octahedra,</span> <span m=''4554050''>so</span>
  <span m=''4554180''>it''s</span> <span m=''4554280''>one</span> <span m=''4554430''>of</span>
  <span m=''4554520''>these.</span> </p><p><span m=''4556272''>This</span> <span m=''4556710''>guy.</span>
  <span m=''4558640''>Of</span> <span m=''4558680''>course,</span> <span m=''4558860''>it''s</span>
  <span m=''4558980''>hard</span> <span m=''4559150''>to</span> <span m=''4559220''>tell</span>
  <span m=''4559460''>from</span> <span m=''4559660''>a</span> <span m=''4560430''>static</span>
  <span m=''4560840''>image,</span> <span m=''4561220''>but yeah,</span> <span m=''4561600''>obviously</span>
  <span m=''4561880''>that</span> <span m=''4562020''>was</span> <span m=''4562160''>the</span>
  <span m=''4562250''>octahedron</span> <span m=''4562730''>from</span> <span m=''4562990''>the</span>
  <span m=''4563490''>video.</span> <span m=''4564910''>And</span> <span m=''4565130''>that</span>
  <span m=''4565370''>is</span> <span m=''4565590''>all.</span> <span m=''4565975''>So</span>
  <span m=''4566360''>actually,</span> <span m=''4566650''>there''s</span> <span m=''4566810''>only</span>
  <span m=''4567030''>23</span> <span m=''4567600''>distinct</span> <span m=''4568090''>polyhedra</span>
  <span m=''4568740''>you</span> <span m=''4568870''>can</span> <span m=''4569010''>make,</span>
  <span m=''4569400''>but</span> <span m=''4569600''>you</span> <span m=''4569720''>can</span>
  <span m=''4569850''>make</span> <span m=''4570050''>them</span> <span m=''4570180''>out
  of</span> <span m=''4570410''>85</span> <span m=''4571450''>gluings.</span> </p><p><span
  m=''4572680''>So</span> <span m=''4572890''>85</span> <span m=''4573720''>gluings.</span>
  <span m=''4574260''>If</span> <span m=''4574680''>one</span> <span m=''4575030''>of</span>
  <span m=''4575100''>them</span> <span m=''4575320''>is</span> <span m=''4575980''>symmetric,</span>
  <span m=''4576530''>the</span> <span m=''4576640''>cube</span> <span m=''4577330''>is</span>
  <span m=''4577520''>symmetric.</span> <span m=''4578330''>So</span> <span m=''4578480''>that''s</span>
  <span m=''4578700''>one.</span> <span m=''4579650''>And</span> <span m=''4579760''>then</span>
  <span m=''4579840''>the</span> <span m=''4579960''>other</span> <span m=''4580170''>84,</span>
  <span m=''4581430''>there''s</span> <span m=''4581970''>everything</span> <span
  m=''4582500''>and</span> <span m=''4582680''>its</span> <span m=''4583300''>reflectional</span>
  <span m=''4583920''>inverse,</span> <span m=''4584320''>because</span> <span m=''4584520''>this</span>
  <span m=''4584730''>polygon</span> <span m=''4585170''>is</span> <span m=''4585300''>symmetric.</span>
  <span m=''4586660''>So</span> <span m=''4586960''>it''s</span> <span m=''4587910''>84</span>
  <span m=''4588320''>divided</span> <span m=''4588630''>by</span> <span m=''4588760''>2,</span>
  <span m=''4589290''>which</span> <span m=''4589480''>is</span> <span m=''4590150''>42,</span>
  <span m=''4590540''>a</span> <span m=''4590930''>good</span> <span m=''4591120''>number.</span>
  <span m=''4591860''>42</span> <span m=''4592670''>actual</span> <span m=''4594310''>honest</span>
  <span m=''4594850''>gluings</span> <span m=''4595460''>plus</span> <span m=''4595750''>the</span>
  <span m=''4595830''>cube.</span> </p><p><span m=''4597680''>But</span> <span m=''4597920''>those</span>
  <span m=''4598100''>42</span> <span m=''4599420''>gluings,</span> <span m=''4599900''>a</span>
  <span m=''4599970''>lot</span> <span m=''4600190''>of</span> <span m=''4600240''>them</span>
  <span m=''4600360''>generate</span> <span m=''4600720''>the</span> <span m=''4600800''>same</span>
  <span m=''4601190''>polyhedron,</span> <span m=''4601595''>because</span> <span
  m=''4602000''>there''s</span> <span m=''4602150''>only</span> <span m=''4602500''>23</span>
  <span m=''4603040''>distinct</span> <span m=''4603530''>polyhedra</span> <span m=''4603840''>in</span>
  <span m=''4604150''>the</span> <span m=''4604630''>end.</span> <span m=''4604710''>I
  don''t</span> <span m=''4604870''>have</span> <span m=''4605050''>it</span> <span
  m=''4605110''>here,</span> <span m=''4605280''>it''s</span> <span m=''4605410''>on</span>
  <span m=''4605530''>my</span> <span m=''4605680''>web</span> <span m=''4605880''>page.</span>
  <span m=''4606490''>You</span> <span m=''4606590''>could</span> <span m=''4606690''>look
  up</span> <span m=''4606830''>all</span> <span m=''4607100''>85,</span> <span m=''4607650''>and</span>
  <span m=''4607740''>it</span> <span m=''4607970''>says</span> <span m=''4608290''>which</span>
  <span m=''4608450''>ones</span> <span m=''4608660''>are</span> <span m=''4608690''>the</span>
  <span m=''4608800''>same</span> <span m=''4609110''>as</span> <span m=''4609220''>which</span>
  <span m=''4609380''>ones.</span> <span m=''4610000''>And it</span> <span m=''4610100''>was</span>
  <span m=''4610200''>a</span> <span m=''4610270''>real</span> <span m=''4610450''>surprise</span>
  <span m=''4610840''>when</span> <span m=''4610910''>we</span> <span m=''4610990''>were</span>
  <span m=''4611080''>building</span> <span m=''4611440''>them.</span> </p><p><span
  m=''4611500''>It was</span> <span m=''4611620''>like,</span> <span m=''4611770''>wait</span>
  <span m=''4612350''>this</span> <span m=''4612490''>looks</span> <span m=''4612660''>identical</span>
  <span m=''4613130''>to</span> <span m=''4613240''>this</span> <span m=''4613410''>other</span>
  <span m=''4613580''>polyhedron,</span> <span m=''4614100''>and it''s</span> <span
  m=''4614360''>glued</span> <span m=''4614570''>in</span> <span m=''4614680''>a</span>
  <span m=''4614720''>very</span> <span m=''4614990''>different</span> <span m=''4615300''>way.</span>
  <span m=''4616280''>Sort</span> <span m=''4616510''>of</span> <span m=''4616630''>an</span>
  <span m=''4616760''>extrasymmetry</span> <span m=''4617405''>of</span> <span m=''4617690''>that</span>
  <span m=''4617950''>polyhedron,</span> <span m=''4618550''>as</span> <span m=''4618670''>opposed</span>
  <span m=''4618970''>to</span> <span m=''4619040''>the</span> <span m=''4619160''>cross</span>
  <span m=''4619460''>itself.</span> <span m=''4619960''>It was</span> <span m=''4620360''>pretty</span>
  <span m=''4620540''>cool.</span> </p><p><span m=''4623510''>An</span> <span m=''4623690''>interesting</span>
  <span m=''4624420''>thing</span> <span m=''4624660''>to</span> <span m=''4624820''>note</span>
  <span m=''4625130''>here</span> <span m=''4626740''>is</span> <span m=''4627240''>that</span>
  <span m=''4629640''>we</span> <span m=''4629860''>only</span> <span m=''4630450''>bisect</span>
  <span m=''4631120''>the</span> <span m=''4631250''>edges,</span> <span m=''4633640''>right?</span>
  <span m=''4633810''>There''s</span> <span m=''4634880''>a</span> <span m=''4634920''>lot</span>
  <span m=''4635110''>of</span> <span m=''4635210''>edge-to-edge</span> <span m=''4635680''>stuff,</span>
  <span m=''4636190''>and</span> <span m=''4636370''>then</span> <span m=''4636510''>some</span>
  <span m=''4636750''>of</span> <span m=''4636790''>the</span> <span m=''4636910''>edges</span>
  <span m=''4637160''>get</span> <span m=''4637310''>cut</span> <span m=''4637510''>in</span>
  <span m=''4637590''>half.</span> <span m=''4638890''>And</span> <span m=''4639260''>in</span>
  <span m=''4639390''>this</span> <span m=''4639570''>case</span> <span m=''4639790''>actually,</span>
  <span m=''4640190''>they look</span> <span m=''4640390''>mostly</span> <span m=''4640640''>like</span>
  <span m=''4640840''>fold</span> <span m=''4641090''>points,</span> <span m=''4641710''>but</span>
  <span m=''4642150''>that''s</span> <span m=''4642360''>not</span> <span m=''4642540''>always</span>
  <span m=''4642760''>the</span> <span m=''4642840''>case.</span> </p><p><span m=''4644170''>It</span>
  <span m=''4644310''>turns</span> <span m=''4644640''>out,</span> <span m=''4645850''>if</span>
  <span m=''4646060''>you</span> <span m=''4646190''>have</span> <span m=''4647330''>a</span>
  <span m=''4647410''>polygon</span> <span m=''4648020''>were</span> <span m=''4648170''>all</span>
  <span m=''4648400''>the</span> <span m=''4648520''>edge</span> <span m=''4648720''>links</span>
  <span m=''4648970''>are</span> <span m=''4649050''>the</span> <span m=''4649120''>same</span>
  <span m=''4649530''>like</span> <span m=''4649730''>this</span> <span m=''4652000''>and</span>
  <span m=''4652460''>you</span> <span m=''4652580''>look</span> <span m=''4652750''>at</span>
  <span m=''4652830''>non-edge-to-edge</span> <span m=''4653600''>gluings,</span>
  <span m=''4654120''>and</span> <span m=''4654580''>there</span> <span m=''4654680''>are</span>
  <span m=''4654750''>no</span> <span m=''4654920''>rolling</span> <span m=''4655240''>belts--</span>
  <span m=''4655810''>because</span> <span m=''4656030''>if</span> <span m=''4656170''>there''s</span>
  <span m=''4656300''>rolling</span> <span m=''4656530''>belts,</span> <span m=''4656870''>it''s
  infinite</span> <span m=''4657350''>because you''re</span> <span m=''4657630''>not</span>
  <span m=''4657830''>going</span> <span m=''4657910''>to</span> <span m=''4657950''>have</span>
  <span m=''4658090''>anything</span> <span m=''4658360''>like</span> <span m=''4658590''>this.</span>
  <span m=''4660030''>Then</span> <span m=''4663670''>it</span> <span m=''4663830''>suffices</span>
  <span m=''4664780''>to</span> <span m=''4664910''>subdivide</span> <span m=''4665430''>every</span>
  <span m=''4665680''>edge</span> <span m=''4665840''>in</span> <span m=''4665920''>half.</span>
  <span m=''4666890''>And</span> <span m=''4667090''>then</span> <span m=''4667270''>every</span>
  <span m=''4667500''>non-edge-to-edge</span> <span m=''4668260''>gluing</span> <span
  m=''4668500''>will</span> <span m=''4668620''>become</span> <span m=''4669070''>an</span>
  <span m=''4669160''>edge-to-edge</span> <span m=''4669670''>gluing.</span> </p><p><span
  m=''4670540''>This</span> <span m=''4670720''>is</span> <span m=''4670850''>called</span>
  <span m=''4671120''>the</span> <span m=''4671230''>[INAUDIBLE]</span> <span m=''4672620''>half-length</span>
  <span m=''4674840''>theorem</span> <span m=''4675740''>in</span> <span m=''4675840''>our</span>
  <span m=''4675930''>book.</span> <span m=''4677010''>It was</span> <span m=''4677380''>proved</span>
  <span m=''4677550''>by</span> <span m=''4677690''>this</span> <span m=''4677840''>guy</span>
  <span m=''4677980''>[INAUDIBLE],</span> <span m=''4678270''>who was</span> <span
  m=''4678580''>one</span> <span m=''4678730''>of</span> <span m=''4678860''>the</span>
  <span m=''4679190''>implementers</span> <span m=''4679830''>of</span> <span m=''4680650''>the
  algorithms</span> <span m=''4681070''>for</span> <span m=''4681200''>enumerating</span>
  <span m=''4681610''>all</span> <span m=''4681750''>these</span> <span m=''4681900''>gluings.</span>
  <span m=''4683070''>And</span> <span m=''4683350''>he</span> <span m=''4683450''>proved</span>
  <span m=''4683680''>it</span> <span m=''4683740''>afterward.</span> <span m=''4684230''>The</span>
  <span m=''4684330''>code</span> <span m=''4684620''>doesn''t</span> <span m=''4684850''>actually</span>
  <span m=''4685100''>exploit</span> <span m=''4685440''>that</span> <span m=''4685630''>fact,</span>
  <span m=''4686100''>but</span> <span m=''4686460''>it''s</span> <span m=''4686520''>kind</span>
  <span m=''4686670''>of</span> <span m=''4686740''>neat.</span> <span m=''4687200''>All</span>
  <span m=''4687390''>you</span> <span m=''4687480''>have</span> <span m=''4687620''>to</span>
  <span m=''4687730''>worry</span> <span m=''4687880''>about</span> <span m=''4688200''>are</span>
  <span m=''4688760''>half</span> <span m=''4689040''>edges</span> <span m=''4689330''>in</span>
  <span m=''4689450''>this</span> <span m=''4689610''>case</span> <span m=''4689840''>where
  all</span> <span m=''4690110''>the edge</span> <span m=''4690500''>links are</span>
  <span m=''4690570''>the</span> <span m=''4690640''>same.</span> </p><p><span m=''4692900''>All</span>
  <span m=''4693000''>right,</span> <span m=''4693200''>that''s</span> <span m=''4693460''>a
  cross.</span> <span m=''4693990''>And</span> <span m=''4694170''>it''s</span> <span
  m=''4694350''>kind</span> <span m=''4694530''>of</span> <span m=''4694900''>maybe</span>
  <span m=''4695220''>even</span> <span m=''4695390''>surprising</span> <span m=''4695705''>that</span>
  <span m=''4696020''>there''s</span> <span m=''4696190''>only</span> <span m=''4696390''>finitely</span>
  <span m=''4697490''>many</span> <span m=''4697780''>different</span> <span m=''4698260''>gluings,</span>
  <span m=''4698810''>but</span> <span m=''4698930''>there''s</span> <span m=''4699090''>no</span>
  <span m=''4699250''>way</span> <span m=''4699350''>to</span> <span m=''4699420''>get</span>
  <span m=''4699550''>a</span> <span m=''4699610''>rolling</span> <span m=''4699870''>belt</span>
  <span m=''4700140''>here.</span> <span m=''4701970''>Let''s</span> <span m=''4702390''>look</span>
  <span m=''4702700''>at--</span> <span m=''4703230''>oh,</span> <span m=''4703550''>here</span>
  <span m=''4703905''>are</span> <span m=''4704260''>all</span> <span m=''4704380''>the</span>
  <span m=''4704460''>polyhedra</span> <span m=''4704795''>in</span> <span m=''4705130''>a</span>
  <span m=''4705200''>pretty</span> <span m=''4705570''>3D</span> <span m=''4705910''>form.</span>
  <span m=''4708680''>Here</span> <span m=''4709300''>is</span> <span m=''4709600''>a</span>
  <span m=''4709790''>polygon</span> <span m=''4710300''>which</span> <span m=''4710440''>is</span>
  <span m=''4710540''>convex.</span> <span m=''4711240''>It</span> <span m=''4711370''>is</span>
  <span m=''4711530''>the</span> <span m=''4711650''>equilateral</span> <span m=''4712230''>triangle.</span>
  </p><p><span m=''4713270''>And</span> <span m=''4713470''>so,</span> <span m=''4713620''>no</span>
  <span m=''4713760''>surprise,</span> <span m=''4714250''>there</span> <span m=''4714500''>a</span>
  <span m=''4714560''>rolling</span> <span m=''4714830''>belts</span> <span m=''4715120''>here.</span>
  <span m=''4715900''>But</span> <span m=''4716020''>here''s</span> <span m=''4716380''>the</span>
  <span m=''4716470''>picture</span> <span m=''4716860''>of</span> <span m=''4716910''>how</span>
  <span m=''4717270''>all the</span> <span m=''4717350''>rolling</span> <span m=''4717920''>belts</span>
  <span m=''4718240''>fit</span> <span m=''4718450''>together.</span> <span m=''4719040''>In</span>
  <span m=''4719220''>principle,</span> <span m=''4719810''>you</span> <span m=''4719850''>can</span>
  <span m=''4720400''>extract</span> <span m=''4720860''>this</span> <span m=''4721020''>picture</span>
  <span m=''4721400''>from</span> <span m=''4722390''>this</span> <span m=''4722560''>algorithm.</span>
  <span m=''4724160''>Although</span> <span m=''4725730''>combined</span> <span m=''4726170''>with</span>
  <span m=''4726300''>an</span> <span m=''4726390''>algorithm</span> <span m=''4726710''>for</span>
  <span m=''4726830''>Alexandroff''s</span> <span m=''4727070''>theorem,</span> <span
  m=''4727590''>that''s</span> <span m=''4727800''>the</span> <span m=''4727840''>tricky</span>
  <span m=''4728110''>part.</span> </p><p><span m=''4728910''>So you</span> <span
  m=''4729060''>have</span> <span m=''4729190''>some</span> <span m=''4729340''>very</span>
  <span m=''4729530''>simple</span> <span m=''4729970''>gluings,</span> <span m=''4730150''>like</span>
  <span m=''4730320''>could</span> <span m=''4730520''>could fold</span> <span m=''4730680''>the</span>
  <span m=''4730760''>triangle</span> <span m=''4731110''>in</span> <span m=''4731170''>half,</span>
  <span m=''4731490''>get</span> <span m=''4731660''>this</span> <span m=''4731850''>doubly-covered</span>
  <span m=''4732350''>triangle,</span> <span m=''4733140''>you</span> <span m=''4733240''>can</span>
  <span m=''4733330''>make</span> <span m=''4733480''>a</span> <span m=''4733540''>regular</span>
  <span m=''4733810''>tetrahedron,</span> <span m=''4734680''>or</span> <span m=''4734870''>you</span>
  <span m=''4734960''>can</span> <span m=''4735120''>fold</span> <span m=''4735300''>the</span>
  <span m=''4735370''>triangle</span> <span m=''4735890''>into</span> <span m=''4736220''>a</span>
  <span m=''4736270''>flat</span> <span m=''4736620''>doubly-covered</span> <span
  m=''4737230''>rectangle</span> <span m=''4737790''>like</span> <span m=''4737980''>at</span>
  <span m=''4738070''>the</span> <span m=''4738200''>top.</span> <span m=''4739440''>And</span>
  <span m=''4739610''>then</span> <span m=''4739780''>there are</span> <span m=''4740000''>rolling</span>
  <span m=''4740320''>belts</span> <span m=''4740580''>in</span> <span m=''4740680''>between.</span>
  <span m=''4740985''>So</span> <span m=''4741540''>this</span> <span m=''4741750''>is</span>
  <span m=''4741850''>one</span> <span m=''4742070''>rolling</span> <span m=''4742380''>belt,</span>
  <span m=''4742830''>this</span> <span m=''4743170''>is</span> <span m=''4743280''>another</span>
  <span m=''4743820''>possible</span> <span m=''4744190''>rolling</span> <span m=''4744480''>belt,</span>
  <span m=''4744710''>another</span> <span m=''4744790''>possible</span> <span m=''4745280''>rolling</span>
  <span m=''4745420''>belt</span> <span m=''4745940''>each with a</span> <span m=''4746400''>gluing
  tree.</span> <span m=''4746740''>They''re</span> <span m=''4746810''>not all</span>
  <span m=''4747120''>drawn</span> <span m=''4747370''>here.</span> </p><p><span m=''4748730''>And</span>
  <span m=''4748910''>this</span> <span m=''4749110''>is</span> <span m=''4749210''>sort</span>
  <span m=''4749350''>of</span> <span m=''4749430''>the</span> <span m=''4749710''>topology</span>
  <span m=''4750530''>of</span> <span m=''4750750''>all</span> <span m=''4751290''>of</span>
  <span m=''4751420''>the</span> <span m=''4751500''>possible</span> <span m=''4752040''>gluings</span>
  <span m=''4752370''>you</span> <span m=''4752500''>could</span> <span m=''4752660''>make,</span>
  <span m=''4754260''>which</span> <span m=''4754360''>is</span> <span m=''4754450''>nice.</span>
  <span m=''4755720''>So a</span> <span m=''4755910''>triangle</span> <span m=''4756330''>is</span>
  <span m=''4756530''>relatively</span> <span m=''4757660''>simple.</span> <span m=''4760000''>The</span>
  <span m=''4760640''>square</span> <span m=''4761910''>is</span> <span m=''4762180''>a</span>
  <span m=''4762240''>little</span> <span m=''4762460''>messier.</span> <span m=''4764740''>There''s</span>
  <span m=''4765050''>again</span> <span m=''4765370''>a</span> <span m=''4765430''>bunch</span>
  <span m=''4765670''>of</span> <span m=''4766250''>particularly</span> <span m=''4767030''>nice</span>
  <span m=''4767880''>gluings</span> <span m=''4768400''>like</span> <span m=''4768720''>the</span>
  <span m=''4769750''>[INAUDIBLE],</span> <span m=''4771360''>the</span> <span m=''4773070''>folding</span>
  <span m=''4773510''>in</span> <span m=''4773580''>half</span> <span m=''4773960''>one</span>
  <span m=''4774160''>way,</span> <span m=''4774390''>folding</span> <span m=''4774730''>in
  half</span> <span m=''4775040''>the</span> <span m=''4775180''>other</span> <span
  m=''4775360''>way,</span> <span m=''4776580''>making</span> <span m=''4777040''>a</span>
  <span m=''4777110''>letter,</span> <span m=''4778820''>and</span> <span m=''4779010''>some</span>
  <span m=''4779580''>tetrahedra</span> <span m=''4781390''>that</span> <span m=''4781510''>are</span>
  <span m=''4781600''>just</span> <span m=''4781850''>drawn</span> <span m=''4782120''>here.</span>
  <span m=''4782340''>They''re</span> <span m=''4782580''>in</span> <span m=''4782980''>the</span>
  <span m=''4783060''>middle.</span> </p><p><span m=''4784420''>And</span> <span m=''4784630''>then</span>
  <span m=''4784760''>there''s</span> <span m=''4784910''>these</span> <span m=''4785030''>crazy</span>
  <span m=''4785410''>rolling</span> <span m=''4785680''>belts</span> <span m=''4785970''>for</span>
  <span m=''4786090''>how</span> <span m=''4786270''>they</span> <span m=''4786580''>fit</span>
  <span m=''4786720''>together.</span> <span m=''4787120''>So</span> <span m=''4787220''>this</span>
  <span m=''4787320''>is</span> <span m=''4787340''>in</span> <span m=''4787460''>unit</span>
  <span m=''4787900''>square</span> <span m=''4788890''>all</span> <span m=''4789130''>the</span>
  <span m=''4789220''>different</span> <span m=''4789500''>gluings.</span> <span m=''4791100''>And</span>
  <span m=''4791960''>one</span> <span m=''4792290''>of</span> <span m=''4792380''>the</span>
  <span m=''4792520''>fun</span> <span m=''4792810''>things,</span> <span m=''4793850''>some</span>
  <span m=''4794060''>of</span> <span m=''4794110''>them</span> <span m=''4794250''>are</span>
  <span m=''4794550''>octahedra,</span> <span m=''4795050''>I</span> <span m=''4795520''>have</span>
  <span m=''4796860''>a</span> <span m=''4796940''>list</span> <span m=''4797350''>here.</span>
  <span m=''4799930''>But</span> <span m=''4800080''>I</span> <span m=''4800140''>don''t</span>
  <span m=''4800340''>know</span> <span m=''4800580''>actually</span> <span m=''4800930''>which</span>
  <span m=''4802000''>one</span> <span m=''4802160''>of</span> <span m=''4802240''>these</span>
  <span m=''4802400''>belts</span> <span m=''4803020''>has</span> <span m=''4803250''>the</span>
  <span m=''4803490''>octahedra.</span> <span m=''4803830''>It might</span> <span
  m=''4804010''>be</span> <span m=''4804090''>a</span> <span m=''4804150''>couple</span>
  <span m=''4804450''>of</span> <span m=''4804530''>them.</span> </p><p><span m=''4805540''>And</span>
  <span m=''4805910''>it</span> <span m=''4806000''>turns</span> <span m=''4806290''>out,</span>
  <span m=''4807720''>for</span> <span m=''4808190''>octahedra</span> <span m=''4809100''>they</span>
  <span m=''4809250''>actually</span> <span m=''4809640''>figured</span> <span m=''4810160''>out</span>
  <span m=''4810300''>an</span> <span m=''4810400''>algorithm</span> <span m=''4810840''>just</span>
  <span m=''4811080''>for</span> <span m=''4811200''>octahedra</span> <span m=''4811840''>to</span>
  <span m=''4812020''>solve</span> <span m=''4812590''>Alexandroff''s</span> <span
  m=''4812865''>theorem.</span> <span m=''4813470''>This</span> <span m=''4813630''>is</span>
  <span m=''4813720''>again</span> <span m=''4813940''>before</span> <span m=''4814990''>Alexandroff</span>
  <span m=''4815440''>theorem</span> <span m=''4815740''>algorithms.</span> <span
  m=''4817040''>And</span> <span m=''4817150''>they</span> <span m=''4817210''>wanted</span>
  <span m=''4817450''>to</span> <span m=''4817550''>compute,</span> <span m=''4818000''>well</span>
  <span m=''4818280''>if</span> <span m=''4818420''>I</span> <span m=''4818480''>take</span>
  <span m=''4818710''>all</span> <span m=''4819050''>these</span> <span m=''4819210''>polyhdra,</span>
  <span m=''4819710''>which</span> <span m=''4819910''>one</span> <span m=''4820050''>has</span>
  <span m=''4820210''>the</span> <span m=''4820310''>maximum</span> <span m=''4820830''>volume?</span>
  </p><p><span m=''4821660''>So</span> <span m=''4821710''>if</span> <span m=''4821810''>I</span>
  <span m=''4821860''>take</span> <span m=''4822100''>a</span> <span m=''4822160''>square</span>
  <span m=''4822760''>paper,</span> <span m=''4823520''>what''s</span> <span m=''4823630''>the</span>
  <span m=''4823710''>maximum</span> <span m=''4824210''>volume</span> <span m=''4824510''>shape</span>
  <span m=''4825280''>you can</span> <span m=''4825390''>make?</span> <span m=''4826560''>And</span>
  <span m=''4828320''>there</span> <span m=''4828530''>it</span> <span m=''4828580''>is.</span>
  <span m=''4830900''>It''s</span> <span m=''4831030''>kind</span> <span m=''4831210''>of</span>
  <span m=''4831270''>fun.</span> <span m=''4833950''>One</span> <span m=''4834150''>of</span>
  <span m=''4834220''>those</span> <span m=''4834520''>octahedra.</span> </p><p><span
  m=''4835820''>And</span> <span m=''4836120''>this</span> <span m=''4836340''>is</span>
  <span m=''4836710''>a</span> <span m=''4838020''>prettier</span> <span m=''4838440''>picture</span>
  <span m=''4839440''>of--</span> <span m=''4840330''>so</span> <span m=''4840410''>here</span>
  <span m=''4840580''>they</span> <span m=''4840670''>actually</span> <span m=''4841010''>computed</span>
  <span m=''4841450''>all</span> <span m=''4841600''>the</span> <span m=''4841660''>polyhedra.</span>
  <span m=''4843080''>Obviously</span> <span m=''4843410''>not</span> <span m=''4843720''>all</span>
  <span m=''4844050''>infinitely</span> <span m=''4844440''>many</span> <span m=''4844730''>of</span>
  <span m=''4844820''>them,</span> <span m=''4845100''>but</span> <span m=''4845470''>various</span>
  <span m=''4845880''>snapshots</span> <span m=''4846450''>along</span> <span m=''4846820''>each</span>
  <span m=''4846990''>rolling</span> <span m=''4847270''>belt.</span> <span m=''4848360''>And</span>
  <span m=''4848630''>each</span> <span m=''4848880''>of</span> <span m=''4848970''>these</span>
  <span m=''4849160''>rolling</span> <span m=''4849470''>belts</span> <span m=''4849910''>corresponds</span>
  <span m=''4850550''>to</span> <span m=''4850730''>one</span> <span m=''4851020''>of</span>
  <span m=''4851140''>the</span> <span m=''4851240''>circles</span> <span m=''4852500''>over</span>
  <span m=''4852720''>here.</span> </p><p><span m=''4856400''>And</span> <span m=''4856700''>that''s</span>
  <span m=''4856880''>it.</span> <span m=''4857790''>Any</span> <span m=''4857950''>questions?</span>
  <span m=''4860370''>So</span> <span m=''4860550''>that''s</span> <span m=''4861510''>the</span>
  <span m=''4861630''>end</span> <span m=''4861850''>of</span> <span m=''4862010''>fun</span>
  <span m=''4862390''>with</span> <span m=''4862550''>gluings.</span> <span m=''4863250''>We''ll
  look</span> <span m=''4863430''>at</span> <span m=''4863500''>other</span> <span
  m=''4863730''>kinds</span> <span m=''4864020''>of</span> <span m=''4864280''>gluing</span>
  <span m=''4864510''>problems</span> <span m=''4865120''>next</span> <span m=''4865220''>class.</span>
  </p>'
type: course
uid: 717265785f926c4605e4166360070c79

---
None