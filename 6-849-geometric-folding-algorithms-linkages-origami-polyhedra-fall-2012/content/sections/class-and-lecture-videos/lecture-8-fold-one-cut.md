---
about_this_resource_text: <p><strong>Description:</strong> This lecture presents the
  fold and cut problem, and both the straight skeleton method and disk-packing method.
  Simple fold and cut is then generalized for folding surface of polyhedra.</p> <p><strong>Speaker:</strong>
  Erik Demaine</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: K0GuKDSX1FA
  parent_uid: a897cdc74509242426a481508e985777
  title: Video-YouTube-Stream
  type: Video
  uid: 4d9fb457dee029bb4b66c51359f55aff
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/K0GuKDSX1FA/default.jpg
  parent_uid: a897cdc74509242426a481508e985777
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 3e1c5d12133dfc284537e5d21bbc7f8d
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: a897cdc74509242426a481508e985777
  title: Video-iTunes U-MP4
  type: Video
  uid: a7b919fe137b5c7495af2eb73f0e2c68
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_lec08_300k.mp4
  parent_uid: a897cdc74509242426a481508e985777
  title: Video-Internet Archive-MP4
  type: Video
  uid: 919462e77ac9dc29f2489b6df42a1a32
- id: 3Play-3PlayYouTubeid-MP4
  media_location: K0GuKDSX1FA
  parent_uid: a897cdc74509242426a481508e985777
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 83a9fe2e6ae21513a7e6cd0d03feacab
- id: K0GuKDSX1FA.srt
  parent_uid: a897cdc74509242426a481508e985777
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-8-fold-one-cut/K0GuKDSX1FA.srt
  title: 3play caption file
  type: null
  uid: b8a8da163091034cb68e00a06fd92a4c
- id: K0GuKDSX1FA.pdf
  parent_uid: a897cdc74509242426a481508e985777
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-8-fold-one-cut/K0GuKDSX1FA.pdf
  title: 3play pdf file
  type: null
  uid: 7a4fb714227501a2118dc589e5f9c317
- id: Caption-3Play YouTube id-SRT
  parent_uid: a897cdc74509242426a481508e985777
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 4480eacc5fb3f571cd2270828fb744c4
- id: Transcript-3Play YouTube id-PDF
  parent_uid: a897cdc74509242426a481508e985777
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 72f2ef275c268e31402543595953e40d
inline_embed_id: 82398234lecture8:fold&onecut95818300
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: lecture-8-fold-one-cut
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-8-fold-one-cut
template_type: Tabbed
title: 'Lecture 8: Fold & One Cut'
transcript: '<p><span m=''3520''>PROFESSOR: All</span> <span m=''3610''>right.</span>
  <span m=''5070''>Today</span> <span m=''5590''>I</span> <span m=''5730''>think</span>
  <span m=''6110''>is</span> <span m=''6250''>the</span> <span m=''6420''>last</span>
  <span m=''7060''>lecture</span> <span m=''7660''>at</span> <span m=''7710''>least</span>
  <span m=''8210''>for</span> <span m=''8380''>the</span> <span m=''8590''>while</span>
  <span m=''9460''>about</span> <span m=''9740''>origami,</span> <span m=''10710''>and</span>
  <span m=''11230''>I''m</span> <span m=''11280''>going</span> <span m=''11370''>to</span>
  <span m=''11460''>talk</span> <span m=''11730''>about</span> <span m=''13180''>where</span>
  <span m=''13650''>I</span> <span m=''13730''>got</span> <span m=''13960''>started</span>
  <span m=''14400''>thinking</span> <span m=''14680''>about</span> <span m=''14900''>organic</span>
  <span m=''15260''>mathematics.</span> <span m=''21020''>The</span> <span m=''21090''>folding</span>
  <span m=''21470''>cup</span> <span m=''21690''>problem,</span> <span m=''25310''>and</span>
  <span m=''28070''>this</span> <span m=''28270''>is</span> <span m=''28330''>sort</span>
  <span m=''28500''>of</span> <span m=''28560''>motivated</span> <span m=''29060''>by</span>
  <span m=''29230''>a</span> <span m=''29290''>magic</span> <span m=''29680''>trick.</span>
  </p><p><span m=''31050''>The</span> <span m=''31250''>idea</span> <span m=''31670''>is</span>
  <span m=''32140''>you</span> <span m=''32490''>take</span> <span m=''32710''>a</span>
  <span m=''32770''>piece</span> <span m=''32960''>of</span> <span m=''33040''>paper.</span>
  <span m=''34040''>You</span> <span m=''34160''>fold</span> <span m=''34850''>it</span>
  <span m=''35070''>flat.</span> <span m=''40040''>You</span> <span m=''40190''>make</span>
  <span m=''40560''>one</span> <span m=''40840''>complete</span> <span m=''41200''>straight</span>
  <span m=''41440''>cut.</span> <span m=''49550''>You</span> <span m=''49700''>cut</span>
  <span m=''49880''>along</span> <span m=''50160''>a</span> <span m=''50230''>line.</span>
  <span m=''54290''>And</span> <span m=''54920''>you</span> <span m=''55080''>unfold</span>
  <span m=''55630''>the</span> <span m=''55710''>pieces,</span> <span m=''59460''>and</span>
  <span m=''59680''>the</span> <span m=''59760''>question</span> <span m=''60080''>is</span>
  <span m=''60190''>what</span> <span m=''60490''>shapes</span> <span m=''61160''>can</span>
  <span m=''61330''>you</span> <span m=''61450''>get</span> <span m=''61930''>by that</span>
  <span m=''62160''>process.</span> <span m=''63450''>So</span> <span m=''63660''>this</span>
  <span m=''63830''>is</span> <span m=''63980''>like</span> <span m=''65890''>a</span>
  <span m=''65960''>magic</span> <span m=''66230''>trick.</span> </p><p><span m=''66440''>I</span>
  <span m=''66490''>showed</span> <span m=''66780''>you</span> <span m=''67340''>making</span>
  <span m=''67610''>a</span> <span m=''67660''>swan</span> <span m=''68550''>which</span>
  <span m=''68680''>I</span> <span m=''68750''>have</span> <span m=''68970''>here</span>
  <span m=''69860''>just</span> <span m=''70000''>for--</span> <span m=''70705''>to</span>
  <span m=''71100''>jog your</span> <span m=''71590''>memory.</span> <span m=''72400''>You</span>
  <span m=''72480''>have</span> <span m=''73630''>a</span> <span m=''73970''>rectangle</span>
  <span m=''74500''>paper,</span> <span m=''75730''>and</span> <span m=''76100''>you</span>
  <span m=''76190''>can</span> <span m=''76320''>see</span> <span m=''76440''>the</span>
  <span m=''76600''>swan</span> <span m=''76820''>on</span> <span m=''76930''>there</span>
  <span m=''77090''>and</span> <span m=''77160''>you</span> <span m=''77280''>can
  see</span> <span m=''77490''>a bunch</span> <span m=''77730''>of creases.</span>
  <span m=''78770''>You</span> <span m=''78870''>fold</span> <span m=''79200''>along</span>
  <span m=''79590''>all</span> <span m=''79700''>the</span> <span m=''79800''>creases,</span>
  <span m=''81730''>not</span> <span m=''81940''>the swan</span> <span m=''82110''>lines,</span>
  <span m=''83460''>and</span> <span m=''83610''>you</span> <span m=''83730''>end</span>
  <span m=''83930''>up</span> <span m=''84140''>with</span> <span m=''84350''>all</span>
  <span m=''84690''>the</span> <span m=''84820''>edges</span> <span m=''85200''>of
  the</span> <span m=''85290''>swan</span> <span m=''86240''>lying</span> <span m=''86620''>right</span>
  <span m=''86800''>along</span> <span m=''87050''>that</span> <span m=''87220''>line.</span>
  <span m=''88110''>You</span> <span m=''88260''>cut</span> <span m=''88450''>along</span>
  <span m=''88730''>the</span> <span m=''88800''>line,</span> <span m=''92840''>and</span>
  <span m=''93040''>you</span> <span m=''93130''>get</span> <span m=''93360''>your</span>
  <span m=''93550''>swan,</span> <span m=''96460''>as we did</span> <span m=''97440''>before.</span>
  </p><p><span m=''98770''>And</span> <span m=''99100''>you</span> <span m=''99200''>also</span>
  <span m=''99390''>get</span> <span m=''99560''>the</span> <span m=''99720''>anti-swan.</span>
  <span m=''101085''>The</span> <span m=''101370''>other</span> <span m=''101510''>piece--</span>
  <span m=''101940''>I didn''t</span> <span m=''102020''>show</span> <span m=''102170''>that</span>
  <span m=''102340''>last</span> <span m=''102590''>time.</span> <span m=''103450''>But</span>
  <span m=''103570''>it''s</span> <span m=''103720''>really--</span> <span m=''104020''>it''s</span>
  <span m=''104210''>not</span> <span m=''104360''>like</span> <span m=''104530''>we''re</span>
  <span m=''104630''>making</span> <span m=''105020''>we''re</span> <span m=''105120''>not</span>
  <span m=''105280''>allowed</span> <span m=''105570''>to</span> <span m=''105640''>make</span>
  <span m=''105850''>any</span> <span m=''106010''>extra</span> <span m=''106260''>creases.</span>
  <span m=''106520''>We</span> <span m=''106630''>really</span> <span m=''106970''>want</span>
  <span m=''107350''>the</span> <span m=''107580''>swan.</span> <span m=''109420''>So</span>
  <span m=''111110''>we</span> <span m=''111580''>cut</span> <span m=''111770''>along</span>
  <span m=''112110''>exactly</span> <span m=''112470''>the</span> <span m=''112590''>edges</span>
  <span m=''112890''>of the</span> <span m=''113050''>swan</span> <span m=''113350''>by</span>
  <span m=''113660''>lining</span> <span m=''114020''>them</span> <span m=''114180''>up</span>
  <span m=''114360''>onto</span> <span m=''114620''>a</span> <span m=''114660''>line.</span>
  </p><p><span m=''114950''>So</span> <span m=''115080''>really,</span> <span m=''115500''>you
  could</span> <span m=''115750''>think</span> <span m=''115910''>of</span> <span
  m=''115980''>this</span> <span m=''116180''>as</span> <span m=''116280''>a</span>
  <span m=''116330''>magic</span> <span m=''116640''>trick</span> <span m=''116890''>in</span>
  <span m=''117010''>cutting,</span> <span m=''117760''>but</span> <span m=''117870''>you</span>
  <span m=''117950''>can</span> <span m=''118070''>also</span> <span m=''118310''>think</span>
  <span m=''118510''>of</span> <span m=''118600''>it</span> <span m=''118660''>as</span>
  <span m=''118760''>an</span> <span m=''118840''>origami</span> <span m=''119330''>problem,</span>
  <span m=''119740''>which</span> <span m=''119800''>is</span> <span m=''119950''>I</span>
  <span m=''120090''>want</span> <span m=''120280''>to</span> <span m=''120340''>line</span>
  <span m=''120630''>up</span> <span m=''120770''>all</span> <span m=''120920''>these</span>
  <span m=''121080''>edges</span> <span m=''121360''>by</span> <span m=''121490''>folding.</span>
  <span m=''122190''>How</span> <span m=''122390''>do</span> <span m=''122490''>I</span>
  <span m=''122580''>do</span> <span m=''122790''>it?</span> <span m=''123140''>And</span>
  <span m=''123530''>that</span> <span m=''123730''>way</span> <span m=''123930''>it</span>
  <span m=''124020''>connects</span> <span m=''124330''>to</span> <span m=''124420''>a</span>
  <span m=''124460''>lot</span> <span m=''124690''>origami</span> <span m=''125160''>design</span>
  <span m=''125920''>problems.</span> </p><p><span m=''127440''>This</span> <span
  m=''127680''>problem</span> <span m=''127930''>has</span> <span m=''128180''>an</span>
  <span m=''128289''>old</span> <span m=''128530''>history.</span> <span m=''131360''>It</span>
  <span m=''131490''>goes</span> <span m=''131700''>back</span> <span m=''131860''>to</span>
  <span m=''131960''>1721.</span> <span m=''133130''>This</span> <span m=''133280''>is</span>
  <span m=''133380''>the</span> <span m=''133510''>oldest</span> <span m=''133850''>reference</span>
  <span m=''134570''>we</span> <span m=''134760''>know.</span> <span m=''135000''>This</span>
  <span m=''135240''>is</span> <span m=''135400''>a</span> <span m=''135490''>Japanese</span>
  <span m=''136550''>puzzle</span> <span m=''136840''>book,</span> <span m=''138210''>Wakoku</span>
  <span m=''139730''>Chiyekurabe</span> <span m=''141120''>by</span> <span m=''141280''>Kan
  Chu Sen.</span> <span m=''142600''>And</span> <span m=''142990''>I</span> <span
  m=''143090''>think</span> <span m=''143320''>this</span> <span m=''143480''>is</span>
  <span m=''143670''>kind</span> <span m=''143930''>of</span> <span m=''144010''>like--</span>
  <span m=''144340''>it''s</span> <span m=''144510''>called</span> <span m=''144770''>"Mathematical</span>
  <span m=''145410''>Contests"</span> <span m=''146180''>is</span> <span m=''146410''>the</span>
  <span m=''146750''>translation.</span> <span m=''147630''>And</span> <span m=''148230''>it''s</span>
  <span m=''148460''>sort</span> <span m=''148630''>of</span> <span m=''148740''>like</span>
  <span m=''149850''>the</span> <span m=''150770''>old</span> <span m=''151200''>version</span>
  <span m=''151650''>of</span> <span m=''152990''>like</span> <span m=''153220''>these</span>
  <span m=''153370''>big</span> <span m=''153630''>problem</span> <span m=''154530''>solving</span>
  <span m=''155280''>sessions</span> <span m=''156520''>that</span> <span m=''157210''>kids</span>
  <span m=''157480''>do</span> <span m=''157620''>these</span> <span m=''157850''>days</span>
  <span m=''158660''>to</span> <span m=''158950''>get</span> <span m=''159100''>better</span>
  <span m=''159340''>at</span> <span m=''159420''>math,</span> <span m=''160030''>and</span>
  <span m=''160390''>one</span> <span m=''160600''>of</span> <span m=''160750''>the</span>
  <span m=''161580''>pages</span> <span m=''162400''>poses</span> <span m=''162820''>this</span>
  <span m=''162980''>problem.</span> <span m=''163470''>I</span> <span m=''163540''>have</span>
  <span m=''163720''>this</span> <span m=''163890''>Japanese</span> <span m=''164360''>emblem</span>
  <span m=''164710''>shape.</span> </p><p><span m=''165460''>Can</span> <span m=''165690''>I</span>
  <span m=''165770''>make</span> <span m=''166090''>it</span> <span m=''166510''>from</span>
  <span m=''166770''>a</span> <span m=''166830''>piece</span> <span m=''167040''>of</span>
  <span m=''167130''>paper</span> <span m=''167520''>by</span> <span m=''167670''>folding</span>
  <span m=''168080''>in</span> <span m=''168180''>one</span> <span m=''168360''>straight</span>
  <span m=''168620''>cut,</span> <span m=''169640''>and</span> <span m=''169870''>the</span>
  <span m=''169960''>answer</span> <span m=''170450''>is</span> <span m=''170950''>yes.</span>
  <span m=''171460''>And</span> <span m=''171580''>this</span> <span m=''171770''>is</span>
  <span m=''171920''>a</span> <span m=''171980''>solution</span> <span m=''172530''>if</span>
  <span m=''172630''>you</span> <span m=''172710''>cheat</span> <span m=''172980''>and</span>
  <span m=''173050''>look</span> <span m=''173210''>in</span> <span m=''173290''>the</span>
  <span m=''173380''>back</span> <span m=''173620''>of</span> <span m=''173680''>the</span>
  <span m=''173760''>book.</span> <span m=''175190''>So</span> <span m=''176160''>I''ll</span>
  <span m=''176300''>let</span> <span m=''176440''>you</span> <span m=''176540''>read</span>
  <span m=''176710''>that</span> <span m=''177020''>for</span> <span m=''177150''>minute.</span>
  </p><p><span m=''178030''>[LAUGHS]</span> </p><p><span m=''179680''>You''re</span>
  <span m=''180030''>making</span> <span m=''180470''>folds</span> <span m=''180910''>along</span>
  <span m=''181270''>lines</span> <span m=''181670''>that</span> <span m=''181800''>end</span>
  <span m=''181980''>up</span> <span m=''182120''>lining</span> <span m=''182590''>up</span>
  <span m=''182730''>other</span> <span m=''182950''>parts</span> <span m=''183310''>of</span>
  <span m=''184920''>the</span> <span m=''185020''>shape</span> <span m=''185370''>so</span>
  <span m=''185570''>that</span> <span m=''185720''>in</span> <span m=''185820''>the</span>
  <span m=''185950''>end</span> <span m=''186190''>everything</span> <span m=''186550''>lies</span>
  <span m=''186760''>along</span> <span m=''186970''>the</span> <span m=''187030''>line,</span>
  <span m=''187770''>then</span> <span m=''187940''>you</span> <span m=''188140''>cut</span>
  <span m=''188340''>along</span> <span m=''188380''>the</span> <span m=''188620''>line.</span>
  <span m=''190310''>We</span> <span m=''190490''>learned</span> <span m=''190710''>about</span>
  <span m=''190950''>this</span> <span m=''191460''>a</span> <span m=''191840''>bit</span>
  <span m=''192310''>later</span> <span m=''192920''>than</span> <span m=''193280''>the--</span>
  <span m=''194680''>we</span> <span m=''194870''>learned</span> <span m=''195040''>about</span>
  <span m=''195220''>this</span> <span m=''195340''>problem</span> <span m=''195560''>from</span>
  <span m=''195670''>Martin</span> <span m=''195940''>Gardner</span> <span m=''196280''>originally,</span>
  <span m=''197500''>and</span> <span m=''198380''>he</span> <span m=''198680''>knew</span>
  <span m=''198820''>about</span> <span m=''199080''>the</span> <span m=''199150''>magic</span>
  <span m=''199910''>world.</span> <span m=''200410''>So</span> <span m=''200540''>Houdini,</span>
  <span m=''201040''>before</span> <span m=''201400''>he</span> <span m=''201490''>was</span>
  <span m=''201630''>an</span> <span m=''201690''>escape</span> <span m=''202050''>artist,</span>
  <span m=''202430''>he</span> <span m=''202730''>was</span> <span m=''202910''>a</span>
  <span m=''202970''>general</span> <span m=''203230''>magician,</span> <span m=''204060''>and</span>
  <span m=''204340''>in</span> <span m=''204420''>1922,</span> <span m=''205440''>he</span>
  <span m=''205650''>wrote</span> <span m=''205970''>or</span> <span m=''206120''>probably</span>
  <span m=''206770''>had</span> <span m=''207100''>ghost</span> <span m=''207380''>written</span>
  <span m=''208050''>this</span> <span m=''208270''>book,</span> <span m=''208970''>"Houdini''s</span>
  <span m=''209450''>Paper</span> <span m=''209720''>Magic".</span> <span m=''210650''>And</span>
  <span m=''211780''>one</span> <span m=''212200''>of</span> <span m=''212310''>the</span>
  <span m=''212420''>pages</span> <span m=''213390''>is</span> <span m=''213810''>about</span>
  <span m=''214120''>folding,</span> <span m=''214820''>and</span> <span m=''215150''>it
  says</span> <span m=''215410''>here,</span> <span m=''215580''>you</span> <span
  m=''215700''>can</span> <span m=''215820''>take</span> <span m=''215990''>a</span>
  <span m=''216050''>square</span> <span m=''216320''>paper,</span> <span m=''216960''>fold</span>
  <span m=''217300''>it</span> <span m=''217390''>flat,</span> <span m=''217730''>make</span>
  <span m=''217940''>one</span> <span m=''218080''>straight</span> <span m=''218340''>cut,</span>
  <span m=''218580''>and</span> <span m=''218730''>get</span> <span m=''218850''>a</span>
  <span m=''218920''>regular</span> <span m=''219290''>five-pointed</span> <span m=''219870''>star.</span>
  </p><p><span m=''221060''>And</span> <span m=''221300''>that</span> <span m=''221340''>was</span>
  <span m=''221480''>pretty</span> <span m=''221680''>cool,</span> <span m=''223220''>and</span>
  <span m=''223370''>then</span> <span m=''223940''>other</span> <span m=''224100''>magicians</span>
  <span m=''224600''>picked</span> <span m=''224840''>it</span> <span m=''224900''>up,</span>
  <span m=''225050''>in</span> <span m=''225160''>particular</span> <span m=''225650''>this</span>
  <span m=''225860''>guy</span> <span m=''226120''>Gerald</span> <span m=''226280''>Lowe,</span>
  <span m=''226860''>who</span> <span m=''227290''>wrote</span> <span m=''227490''>this</span>
  <span m=''227650''>book</span> <span m=''227840''>"Paper</span> <span m=''228150''>Capers".</span>
  <span m=''228580''>It''s</span> <span m=''228660''>more</span> <span m=''229060''>like</span>
  <span m=''229600''>a</span> <span m=''229630''>very</span> <span m=''229820''>small</span>
  <span m=''230360''>book.</span> <span m=''230680''>Magic</span> <span m=''231030''>book.</span>
  <span m=''231750''>And</span> <span m=''232200''>he</span> <span m=''232310''>could</span>
  <span m=''232420''>make</span> <span m=''232590''>all</span> <span m=''232770''>sorts</span>
  <span m=''233070''>of</span> <span m=''233170''>different</span> <span m=''233730''>things</span>
  <span m=''233970''>and he</span> <span m=''234140''>would</span> <span m=''234280''>incorporate</span>
  <span m=''234840''>them</span> <span m=''235070''>into</span> <span m=''235340''>magic</span>
  <span m=''235670''>tricks.</span> <span m=''236330''>And</span> <span m=''236580''>he</span>
  <span m=''236740''>was</span> <span m=''236940''>primarily</span> <span m=''237560''>using</span>
  <span m=''238010''>simple</span> <span m=''238370''>folds.</span> <span m=''238660''>He
  would</span> <span m=''238940''>just</span> <span m=''239160''>fold</span> <span
  m=''239280''>along</span> <span m=''239630''>one</span> <span m=''239790''>line</span>
  <span m=''240010''>at</span> <span m=''240100''>a</span> <span m=''240170''>time,</span>
  <span m=''240910''>and</span> <span m=''242870''>make</span> <span m=''243210''>one</span>
  <span m=''243400''>straight</span> <span m=''243650''>cut,</span> <span m=''244420''>and</span>
  <span m=''244550''>go to</span> <span m=''244670''>make</span> <span m=''244890''>all</span>
  <span m=''244990''>these</span> <span m=''245740''>cool</span> <span m=''245950''>patterns.</span>
  </p><p><span m=''246500''>Like</span> <span m=''246700''>here,</span> <span m=''246980''>I</span>
  <span m=''247030''>have</span> <span m=''248030''>one</span> <span m=''248230''>of</span>
  <span m=''248310''>his</span> <span m=''249020''>examples</span> <span m=''250730''>redone.</span>
  <span m=''252080''>I start</span> <span m=''252290''>from</span> <span m=''252380''>a</span>
  <span m=''252580''>rectangle,</span> <span m=''253760''>I</span> <span m=''253830''>fold,</span>
  <span m=''254440''>I</span> <span m=''254730''>fold,</span> <span m=''255420''>I
  fold,</span> <span m=''256100''>I fold--</span> <span m=''256410''>these</span>
  <span m=''256570''>are</span> <span m=''256670''>all</span> <span m=''256750''>simple</span>
  <span m=''257050''>folds.</span> <span m=''257880''>I</span> <span m=''257990''>take</span>
  <span m=''258269''>my</span> <span m=''259000''>scissors,</span> <span m=''259680''>and</span>
  <span m=''259959''>I</span> <span m=''260100''>make</span> <span m=''260360''>one</span>
  <span m=''261149''>complete</span> <span m=''261510''>straight</span> <span m=''261800''>cut.</span>
  <span m=''264400''>And</span> <span m=''264540''>usually</span> <span m=''265160''>when</span>
  <span m=''265290''>I</span> <span m=''266260''>perform</span> <span m=''266760''>this</span>
  <span m=''266970''>trick,</span> <span m=''267780''>I</span> <span m=''267820''>say</span>
  <span m=''267970''>look!</span> <span m=''268650''>I</span> <span m=''268790''>made</span>
  <span m=''269810''>an</span> <span m=''269860''>isosceles</span> <span m=''270660''>triangle.</span>
  <span m=''272050''>Wow!</span> <span m=''273320''>I</span> <span m=''273480''>made</span>
  <span m=''273740''>five</span> <span m=''274280''>isosceles</span> <span m=''274890''>triangles.</span>
  <span m=''275220''>Amazing!</span> </p><p><span m=''276630''>And</span> <span m=''276850''>then</span>
  <span m=''277170''>I</span> <span m=''277270''>made</span> <span m=''277880''>everything,</span>
  <span m=''278480''>except</span> <span m=''278880''>the</span> <span m=''278970''>five</span>
  <span m=''279220''>isosceles</span> <span m=''279730''>triangles.</span> <span m=''280430''>So</span>
  <span m=''282010''>you</span> <span m=''282210''>saw</span> <span m=''282410''>that</span>
  <span m=''282610''>coming.</span> <span m=''283830''>And</span> <span m=''283990''>you</span>
  <span m=''284100''>could</span> <span m=''284220''>make</span> <span m=''284390''>an
  arrangement</span> <span m=''284820''>of</span> <span m=''284900''>five</span> <span
  m=''285170''>of</span> <span m=''285270''>these</span> <span m=''285560''>if</span>
  <span m=''285670''>you</span> <span m=''285820''>want.</span> <span m=''286170''>All</span>
  <span m=''286360''>that</span> <span m=''286550''>sort</span> <span m=''286740''>of</span>
  <span m=''286820''>very</span> <span m=''287030''>symmetric</span> <span m=''287560''>stuff</span>
  <span m=''287810''>is</span> <span m=''287960''>easy</span> <span m=''288260''>to</span>
  <span m=''288380''>do</span> <span m=''289040''>by</span> <span m=''289110''>simple</span>
  <span m=''289380''>folds.</span> <span m=''289670''>I''ll</span> <span m=''289780''>talk</span>
  <span m=''289980''>more</span> <span m=''290150''>about</span> <span m=''290350''>simple</span>
  <span m=''290590''>folds</span> <span m=''290830''>later,</span> <span m=''291910''>but</span>
  <span m=''292040''>we</span> <span m=''292180''>were</span> <span m=''292450''>really</span>
  <span m=''292730''>curious</span> <span m=''293130''>about</span> <span m=''293990''>the</span>
  <span m=''294600''>general</span> <span m=''294940''>challenge.</span> <span m=''295640''>So</span>
  <span m=''295820''>this</span> <span m=''296030''>is</span> <span m=''296170''>the--</span>
  <span m=''297730''>you</span> <span m=''297870''>can</span> <span m=''297970''>download</span>
  <span m=''298290''>this</span> <span m=''298480''>from</span> <span m=''298690''>my</span>
  <span m=''298820''>web</span> <span m=''299010''>page</span> <span m=''299260''>if</span>
  <span m=''299360''>you</span> <span m=''299480''>want</span> <span m=''299630''>to</span>
  <span m=''300020''>make</span> <span m=''300250''>one.</span> <span m=''300400''>It''s</span>
  <span m=''300550''>pretty--</span> <span m=''302250''>it''s</span> <span m=''302420''>a</span>
  <span m=''302470''>fun</span> <span m=''302680''>trick.</span> </p><p><span m=''305130''>Good.</span>
  <span m=''305610''>So I</span> <span m=''305810''>have</span> <span m=''305950''>some</span>
  <span m=''306130''>more</span> <span m=''306590''>interesting</span> <span m=''307020''>examples.</span>
  <span m=''308420''>See</span> <span m=''308640''>here</span> <span m=''308850''>I</span>
  <span m=''308900''>have</span> <span m=''309150''>a</span> <span m=''309210''>rectangle</span>
  <span m=''310310''>folded,</span> <span m=''311380''>and</span> <span m=''311790''>I</span>
  <span m=''311810''>make</span> <span m=''312790''>one</span> <span m=''313110''>complete</span>
  <span m=''313480''>straight</span> <span m=''313780''>cut.</span> <span m=''324000''>And</span>
  <span m=''326210''>this</span> <span m=''326470''>one</span> <span m=''326750''>has</span>
  <span m=''327160''>actually</span> <span m=''327450''>a</span> <span m=''327520''>line</span>
  <span m=''327710''>of</span> <span m=''327780''>symmetry,</span> <span m=''328370''>so
  I</span> <span m=''328480''>fold</span> <span m=''328770''>in</span> <span m=''328980''>half</span>
  <span m=''329280''>at</span> <span m=''329380''>the</span> <span m=''329450''>beginning.</span>
  <span m=''332330''>So</span> <span m=''332450''>I</span> <span m=''332540''>get</span>
  <span m=''333090''>an</span> <span m=''333270''>angel</span> <span m=''333560''>fish.</span>
  <span m=''335040''>Ooh!</span> </p><p><span m=''339240''>All right,</span> <span
  m=''339560''>you''re not</span> <span m=''339720''>impressed.</span> <span m=''340250''>Keep</span>
  <span m=''340430''>going.</span> <span m=''341880''>Here''s</span> <span m=''342230''>another</span>
  <span m=''342510''>one.</span> <span m=''343000''>One</span> <span m=''343190''>straight</span>
  <span m=''343480''>cut.</span> <span m=''344140''>We could</span> <span m=''344500''>go</span>
  <span m=''344640''>all</span> <span m=''344810''>day</span> <span m=''345030''>here.</span>
  <span m=''346890''>I</span> <span m=''346950''>mean,</span> <span m=''347060''>the</span>
  <span m=''347160''>point</span> <span m=''347350''>of</span> <span m=''347430''>today''s</span>
  <span m=''347710''>lecture</span> <span m=''348050''>is</span> <span m=''348250''>to</span>
  <span m=''349790''>see</span> <span m=''349970''>how</span> <span m=''350090''>this</span>
  <span m=''350240''>is</span> <span m=''350350''>done.</span> <span m=''350820''>In</span>
  <span m=''350900''>general.</span> <span m=''352220''>Here</span> <span m=''352430''>we</span>
  <span m=''352510''>have</span> <span m=''352810''>a</span> <span m=''352860''>butterfly.</span>
  <span m=''357280''>All</span> <span m=''357600''>right.</span> <span m=''357790''>You</span>
  <span m=''358130''>guys</span> <span m=''358420''>are</span> <span m=''358710''>tough</span>
  <span m=''358970''>to</span> <span m=''359080''>impress</span> <span m=''359430''>here.</span>
  </p><p><span m=''359870''>Here</span> <span m=''360020''>we</span> <span m=''360120''>go.</span>
  <span m=''361090''>This</span> <span m=''361290''>one</span> <span m=''361440''>is</span>
  <span m=''362460''>deemed</span> <span m=''362800''>thematic.</span> <span m=''363640''>It''s</span>
  <span m=''363740''>almost</span> <span m=''364000''>October,</span> <span m=''365120''>so</span>
  <span m=''365330''>it''s</span> <span m=''365650''>sort</span> <span m=''365870''>of</span>
  <span m=''366070''>appropriate.</span> <span m=''367400''>We''ll</span> <span m=''367630''>one</span>
  <span m=''367790''>straight</span> <span m=''368060''>cut.</span> <span m=''369560''>Haven''t</span>
  <span m=''369650''>done</span> <span m=''369770''>this</span> <span m=''369920''>one</span>
  <span m=''370820''>for</span> <span m=''370860''>quite</span> <span m=''371050''>awhile.</span>
  <span m=''371430''>Get</span> <span m=''371610''>tons</span> <span m=''371810''>of</span>
  <span m=''371910''>pieces,</span> <span m=''373135''>and</span> <span m=''373570''>if</span>
  <span m=''373720''>I''m</span> <span m=''373860''>lucky--</span> <span m=''376360''>open</span>
  <span m=''376480''>it up</span> <span m=''376730''>the</span> <span m=''376850''>right</span>
  <span m=''377020''>way</span> <span m=''377130''>around.</span> <span m=''379221''>Jack-o-lantern.</span>
  <span m=''384000''>Wow,</span> <span m=''384580''>it''s</span> <span m=''384760''>amazing!</span>
  <span m=''386220''>How</span> <span m=''386420''>is</span> <span m=''386550''>it</span>
  <span m=''386660''>possible?</span> </p><p><span m=''387580''>Obviously</span> <span
  m=''387930''>you</span> <span m=''388020''>can</span> <span m=''388130''>make</span>
  <span m=''388450''>many</span> <span m=''388760''>shapes</span> <span m=''389110''>all</span>
  <span m=''389260''>at</span> <span m=''389310''>once.</span> <span m=''389790''>That''s</span>
  <span m=''390030''>the</span> <span m=''390130''>general</span> <span m=''390390''>idea</span>
  <span m=''390700''>here.</span> <span m=''391120''>I''ll</span> <span m=''391500''>admit,</span>
  <span m=''391760''>I</span> <span m=''391850''>cheated</span> <span m=''392180''>here</span>
  <span m=''392480''>because</span> <span m=''392700''>I</span> <span m=''392760''>wanted</span>
  <span m=''393350''>kids</span> <span m=''393610''>to be able</span> <span m=''394110''>to
  fold this.</span> <span m=''395040''>The</span> <span m=''395760''>outer</span>
  <span m=''396470''>octagon</span> <span m=''397680''>was cut</span> <span m=''397890''>initially.</span>
  <span m=''398675''>Yeah,</span> <span m=''398930''>so</span> <span m=''399090''>it''s</span>
  <span m=''399200''>not</span> <span m=''399350''>from a</span> <span m=''399470''>rectangle.</span>
  <span m=''400830''>Just</span> <span m=''401060''>to</span> <span m=''401120''>make</span>
  <span m=''401250''>it</span> <span m=''401290''>easier</span> <span m=''401610''>to</span>
  <span m=''401680''>fold,</span> <span m=''401890''>but</span> <span m=''402040''>you</span>
  <span m=''402180''>could</span> <span m=''402330''>do</span> <span m=''402470''>it</span>
  <span m=''403100''>all</span> <span m=''403290''>at</span> <span m=''403350''>once.</span>
  </p><p><span m=''403860''>And</span> <span m=''404020''>now,</span> <span m=''404800''>the</span>
  <span m=''404910''>big</span> <span m=''405170''>demo.</span> <span m=''407620''>In</span>
  <span m=''407740''>fact,</span> <span m=''408020''>it''s</span> <span m=''408130''>so</span>
  <span m=''408310''>big</span> <span m=''408660''>I</span> <span m=''408690''>think</span>
  <span m=''408910''>I</span> <span m=''408940''>might</span> <span m=''409150''>want</span>
  <span m=''409250''>to</span> <span m=''409300''>use</span> <span m=''409460''>the</span>
  <span m=''409510''>exacto</span> <span m=''409900''>knife.</span> <span m=''412078''>Uh,</span>
  <span m=''412910''>we''ll</span> <span m=''413030''>try</span> <span m=''413220''>with</span>
  <span m=''413350''>scissors.</span> <span m=''415908''>Got a</span> <span m=''416390''>lot
  of</span> <span m=''416810''>layers.</span> <span m=''419540''>Oh,</span> <span
  m=''419980''>yeah.</span> <span m=''421530''>This is</span> <span m=''421700''>why
  I</span> <span m=''421810''>usually</span> <span m=''422070''>bring</span> <span
  m=''422240''>my</span> <span m=''422400''>own</span> <span m=''422800''>scissors.</span>
  <span m=''423991''>Just</span> <span m=''424390''>checking the</span> <span m=''424500''>other</span>
  <span m=''424640''>side.</span> </p><p><span m=''428930''>They''re</span> <span
  m=''429060''>better</span> <span m=''429370''>scissors.</span> <span m=''430220''>That''s</span>
  <span m=''430500''>what''s</span> <span m=''430640''>special</span> <span m=''431080''>about</span>
  <span m=''431210''>my</span> <span m=''431380''>scissors.</span> <span m=''432620''>All</span>
  <span m=''432960''>right,</span> <span m=''433430''>time</span> <span m=''433680''>for</span>
  <span m=''433770''>the</span> <span m=''433870''>exacto</span> <span m=''434260''>knife.</span>
  <span m=''434850''>Make</span> <span m=''435070''>sure</span> <span m=''435320''>I''m</span>
  <span m=''435470''>only</span> <span m=''435710''>cutting</span> <span m=''435970''>on</span>
  <span m=''436180''>the</span> <span m=''436250''>boundary</span> <span m=''436580''>between</span>
  <span m=''436860''>red</span> <span m=''437110''>and</span> <span m=''437220''>white.</span>
  <span m=''442820''>Yeah,</span> <span m=''443000''>my</span> <span m=''443110''>lecture</span>
  <span m=''443400''>notes.</span> <span m=''443700''>Yeah,</span> <span m=''443820''>who</span>
  <span m=''443950''>needs</span> <span m=''444150''>those?</span> <span m=''449340''>It''s</span>
  <span m=''449470''>flat.</span> <span m=''454292''>A little</span> <span m=''454760''>more</span>
  <span m=''454980''>cutting.</span> </p><p><span m=''459720''>I</span> <span m=''459860''>believe</span>
  <span m=''460260''>all</span> <span m=''460390''>the</span> <span m=''460470''>pieces</span>
  <span m=''460820''>in</span> <span m=''460880''>this</span> <span m=''461050''>case</span>
  <span m=''461270''>are</span> <span m=''461360''>rectangles.</span> <span m=''464620''>Exciting.</span>
  <span m=''466740''>All</span> <span m=''466870''>right,</span> <span m=''467220''>straight</span>
  <span m=''467450''>cut,</span> <span m=''467720''>right?</span> <span m=''469964''>I
  don''t</span> <span m=''470440''>remember</span> <span m=''470710''>which</span>
  <span m=''470790''>way</span> <span m=''471000''>this</span> <span m=''471230''>one</span>
  <span m=''471500''>opens.</span> <span m=''475325''>This</span> <span m=''475730''>should</span>
  <span m=''476040''>be</span> <span m=''476840''>the</span> <span m=''476920''>MIT</span>
  <span m=''477340''>logo.</span> <span m=''480060''>This</span> <span m=''480270''>one</span>
  <span m=''480545''>I</span> <span m=''480820''>encourage</span> <span m=''481220''>you</span>
  <span m=''481370''>to try</span> <span m=''481550''>at</span> <span m=''481650''>home.</span>
  <span m=''481900''>It''s</span> <span m=''483130''>pretty</span> <span m=''483330''>crazy.</span>
  <span m=''485350''>It''s</span> <span m=''485570''>definitely</span> <span m=''485630''>a</span>
  <span m=''485800''>hard</span> <span m=''486040''>folding.</span> <span m=''489130''>I''m</span>
  <span m=''489170''>getting</span> <span m=''489400''>used</span> <span m=''489500''>to</span>
  <span m=''489810''>it</span> <span m=''490176''>now.</span> </p><p><span m=''490910''>All</span>
  <span m=''490990''>right,</span> <span m=''491690''>so</span> <span m=''492000''>you</span>
  <span m=''492150''>could</span> <span m=''492250''>make</span> <span m=''492410''>anything</span>
  <span m=''493040''>is</span> <span m=''493150''>the</span> <span m=''493250''>point.</span>
  <span m=''493710''>Some</span> <span m=''494120''>are</span> <span m=''494480''>a</span>
  <span m=''494740''>little</span> <span m=''494940''>more</span> <span m=''495110''>difficult</span>
  <span m=''496110''>because</span> <span m=''496310''>they</span> <span m=''496400''>have</span>
  <span m=''496670''>more</span> <span m=''496900''>layers</span> <span m=''497240''>and</span>
  <span m=''497320''>so</span> <span m=''497460''>on.</span> <span m=''497580''>If</span>
  <span m=''497690''>I</span> <span m=''497950''>made</span> <span m=''498110''>it</span>
  <span m=''498230''>out</span> <span m=''498330''>of</span> <span m=''498430''>thinner</span>
  <span m=''498670''>paper</span> <span m=''499570''>like</span> <span m=''499710''>some</span>
  <span m=''499900''>of</span> <span m=''499950''>the</span> <span m=''500010''>math</span>
  <span m=''500415''>magicians</span> <span m=''500820''>do,</span> <span m=''501210''>it</span>
  <span m=''501350''>is</span> <span m=''501480''>super</span> <span m=''501780''>easy.</span>
  <span m=''503140''>Onion</span> <span m=''503420''>skin</span> <span m=''503650''>paper</span>
  <span m=''503950''>or</span> <span m=''504030''>something.</span> </p><p><span m=''504460''>I</span>
  <span m=''504920''>think</span> <span m=''505080''>I</span> <span m=''505140''>have</span>
  <span m=''505320''>some</span> <span m=''505890''>pictures</span> <span m=''506295''>of</span>
  <span m=''506700''>the piece</span> <span m=''507020''>patterns</span> <span m=''507650''>if</span>
  <span m=''507750''>you want</span> <span m=''507820''>to see</span> <span m=''510160''>what</span>
  <span m=''510630''>these</span> <span m=''510820''>look</span> <span m=''511020''>like.</span>
  <span m=''513500''>And</span> <span m=''513720''>these</span> <span m=''513900''>are</span>
  <span m=''514010''>all</span> <span m=''514280''>available</span> <span m=''514679''>for</span>
  <span m=''514799''>download.</span> <span m=''515260''>You</span> <span m=''515360''>want</span>
  <span m=''515480''>to</span> <span m=''515520''>impress</span> <span m=''515780''>your</span>
  <span m=''515919''>friends,</span> <span m=''518020''>go</span> <span m=''518190''>for</span>
  <span m=''518510''>it.</span> <span m=''525290''>They</span> <span m=''525610''>all
  use</span> <span m=''525690''>slightly</span> <span m=''525980''>different</span>
  <span m=''526270''>color</span> <span m=''526500''>codings,</span> <span m=''526830''>but</span>
  <span m=''526960''>it''s</span> <span m=''527160''>mountain or valley.</span> <span
  m=''530420''>And</span> <span m=''530670''>so</span> <span m=''530810''>we</span>
  <span m=''530950''>want</span> <span m=''531100''>to</span> <span m=''531170''>see</span>
  <span m=''531410''>how</span> <span m=''532770''>to</span> <span m=''532900''>make</span>
  <span m=''533100''>these.</span> </p><p><span m=''539330''>So</span> <span m=''539600''>let</span>
  <span m=''539700''>me</span> <span m=''539820''>state</span> <span m=''540260''>the
  theorem</span> <span m=''540540''>first.</span> <span m=''541390''>We</span> <span
  m=''541550''>have</span> <span m=''542780''>our</span> <span m=''542950''>good</span>
  <span m=''543140''>friend,</span> <span m=''543510''>the</span> <span m=''543630''>universality</span>
  <span m=''544330''>result,</span> <span m=''547840''>which</span> <span m=''548100''>is</span>
  <span m=''549920''>any</span> <span m=''551470''>set</span> <span m=''552245''>of</span>
  <span m=''552580''>line</span> <span m=''552840''>segments</span> <span m=''554040''>on</span>
  <span m=''554190''>your</span> <span m=''554310''>piece</span> <span m=''554530''>of</span>
  <span m=''554600''>paper</span> <span m=''560370''>can</span> <span m=''560790''>be--</span>
  <span m=''561605''>I''ll</span> <span m=''561910''>phrase</span> <span m=''562250''>it</span>
  <span m=''562350''>as</span> <span m=''562670''>can</span> <span m=''562850''>be</span>
  <span m=''562970''>aligned</span> <span m=''566230''>by</span> <span m=''566520''>flat</span>
  <span m=''566880''>folding.</span> <span m=''570440''>A</span> <span m=''570550''>line</span>
  <span m=''570840''>means</span> <span m=''571340''>when</span> <span m=''571450''>you</span>
  <span m=''571530''>make</span> <span m=''571720''>the</span> <span m=''571790''>flat</span>
  <span m=''572030''>folding,</span> <span m=''573710''>all</span> <span m=''573920''>the</span>
  <span m=''574040''>segments</span> <span m=''574520''>come</span> <span m=''574700''>onto</span>
  <span m=''574890''>a</span> <span m=''574930''>common</span> <span m=''575210''>line.</span>
  <span m=''575610''>Nothing</span> <span m=''576050''>else</span> <span m=''576270''>comes</span>
  <span m=''576490''>to</span> <span m=''576580''>that</span> <span m=''576770''>line,</span>
  <span m=''577400''>and</span> <span m=''577570''>therefore</span> <span m=''578930''>you</span>
  <span m=''579080''>cut</span> <span m=''579210''>a</span> <span m=''579260''>long</span>
  <span m=''579440''>line,</span> <span m=''579630''>you</span> <span m=''579720''>get</span>
  <span m=''579830''>exactly</span> <span m=''580310''>those</span> <span m=''580500''>line</span>
  <span m=''580700''>segments.</span> </p><p><span m=''582790''>And</span> <span m=''583000''>there</span>
  <span m=''583120''>are</span> <span m=''583170''>two</span> <span m=''584850''>methods</span>
  <span m=''585340''>for</span> <span m=''585710''>solving</span> <span m=''586060''>this</span>
  <span m=''586210''>problem.</span> <span m=''587580''>The</span> <span m=''587660''>first</span>
  <span m=''587960''>one</span> <span m=''588720''>is</span> <span m=''588930''>what</span>
  <span m=''589100''>I</span> <span m=''589160''>call</span> <span m=''589770''>straight</span>
  <span m=''590100''>skeleton</span> <span m=''590540''>method,</span> <span m=''596960''>and</span>
  <span m=''597390''>second</span> <span m=''597690''>one</span> <span m=''598946''>I''ll</span>
  <span m=''599390''>call</span> <span m=''599810''>the</span> <span m=''599900''>disk</span>
  <span m=''600185''>packing</span> <span m=''600470''>method.</span> <span m=''603560''>By</span>
  <span m=''603680''>slightly</span> <span m=''604110''>different</span> <span m=''604360''>authors.</span>
  <span m=''604990''>This</span> <span m=''605160''>one</span> <span m=''605410''>was</span>
  <span m=''605950''>me,</span> <span m=''606260''>my</span> <span m=''606420''>dad,</span>
  <span m=''606810''>and</span> <span m=''607000''>my</span> <span m=''607240''>advisor,</span>
  <span m=''607650''>Anna</span> <span m=''607820''>[INAUDIBLE].</span> <span m=''608700''>This</span>
  <span m=''608920''>one</span> <span m=''609250''>was</span> <span m=''609970''>Marshall</span>
  <span m=''610260''>Burn,</span> <span m=''610620''>me,</span> <span m=''611000''>David</span>
  <span m=''611270''>Epstein,</span> <span m=''611790''>Barry</span> <span m=''612030''>Hayes.</span>
  </p><p><span m=''614550''>This</span> <span m=''614720''>one''s</span> <span m=''614930''>slightly</span>
  <span m=''615430''>after</span> <span m=''615700''>this</span> <span m=''615900''>one.</span>
  <span m=''616360''>This</span> <span m=''616560''>is</span> <span m=''616640''>sort</span>
  <span m=''616840''>of</span> <span m=''616900''>my</span> <span m=''617040''>first</span>
  <span m=''617500''>computational</span> <span m=''618180''>origami</span> <span
  m=''618600''>paper.</span> <span m=''619470''>And</span> <span m=''621890''>they''re</span>
  <span m=''622090''>quite</span> <span m=''622410''>different.</span> <span m=''623250''>I</span>
  <span m=''623310''>mean</span> <span m=''623450''>at</span> <span m=''623630''>a</span>
  <span m=''623670''>high</span> <span m=''623840''>level,</span> <span m=''624540''>this</span>
  <span m=''624700''>one''s</span> <span m=''624880''>practical.</span> <span m=''626180''>This</span>
  <span m=''626410''>one</span> <span m=''626600''>is</span> <span m=''626750''>theoretically</span>
  <span m=''627400''>good,</span> <span m=''627610''>but</span> <span m=''627730''>impractical.</span>
  <span m=''629340''>This</span> <span m=''629610''>one''s</span> <span m=''629810''>actually</span>
  <span m=''630140''>theoretically</span> <span m=''630580''>bad</span> <span m=''630880''>in</span>
  <span m=''630990''>a</span> <span m=''631040''>few</span> <span m=''631490''>situations</span>
  <span m=''632220''>which</span> <span m=''632380''>we</span> <span m=''632490''>will</span>
  <span m=''632600''>get</span> <span m=''632790''>to,</span> <span m=''633700''>but</span>
  <span m=''633840''>it</span> <span m=''633980''>works</span> <span m=''634300''>very</span>
  <span m=''634490''>well</span> <span m=''634870''>almost</span> <span m=''635260''>always.</span>
  <span m=''635930''>In</span> <span m=''636316''>a</span> <span m=''636702''>formal</span>
  <span m=''637090''>sense</span> <span m=''637320''>of</span> <span m=''637410''>almost</span>
  <span m=''637720''>always.</span> <span m=''638510''>This</span> <span m=''638700''>one</span>
  <span m=''638840''>always</span> <span m=''639050''>works,</span> <span m=''640450''>but</span>
  <span m=''640660''>it''s</span> <span m=''641590''>a</span> <span m=''641670''>challenge</span>
  <span m=''642120''>to</span> <span m=''642210''>fold.</span> <span m=''642810''>All</span>
  <span m=''643060''>of the</span> <span m=''643140''>examples</span> <span m=''643570''>I</span>
  <span m=''643630''>showed</span> <span m=''643910''>you</span> <span m=''644100''>are</span>
  <span m=''644240''>made</span> <span m=''644450''>with</span> <span m=''644600''>the</span>
  <span m=''644640''>straight</span> <span m=''644870''>skeleton</span> <span m=''645260''>method.</span>
  </p><p><span m=''648140''>So</span> <span m=''648760''>that''s</span> <span m=''648970''>the</span>
  <span m=''649140''>idea.</span> <span m=''650360''>That''s</span> <span m=''650520''>where</span>
  <span m=''650730''>we''re</span> <span m=''650860''>going</span> <span m=''650940''>to</span>
  <span m=''651000''>talk</span> <span m=''651170''>about</span> <span m=''651380''>both</span>
  <span m=''651610''>of</span> <span m=''651680''>them.</span> <span m=''653250''>And</span>
  <span m=''653530''>first,</span> <span m=''654720''>I</span> <span m=''654810''>have</span>
  <span m=''654990''>a</span> <span m=''655040''>warm</span> <span m=''655340''>up--</span>
  <span m=''655870''>three</span> <span m=''656080''>warm</span> <span m=''656330''>ups.</span>
  <span m=''659030''>Suppose</span> <span m=''659670''>you</span> <span m=''659760''>had</span>
  <span m=''659900''>a</span> <span m=''659960''>square</span> <span m=''660330''>paper</span>
  <span m=''661130''>and</span> <span m=''661240''>you</span> <span m=''661350''>wanted</span>
  <span m=''661550''>to</span> <span m=''661640''>make</span> <span m=''661810''>a</span>
  <span m=''661900''>single</span> <span m=''662290''>cut.</span> <span m=''663136''>What</span>
  <span m=''663560''>folding</span> <span m=''663900''>do</span> <span m=''664020''>I</span>
  <span m=''664120''>do?</span> <span m=''666180''>Nothing!</span> <span m=''667235''>Yeah,</span>
  <span m=''667590''>that was</span> <span m=''667850''>easy.</span> </p><p><span
  m=''668970''>Let''s</span> <span m=''669250''>say</span> <span m=''669470''>I</span>
  <span m=''669610''>have</span> <span m=''670790''>two</span> <span m=''671030''>lines</span>
  <span m=''671370''>I</span> <span m=''671460''>want</span> <span m=''671660''>to</span>
  <span m=''671710''>make.</span> <span m=''673380''>What</span> <span m=''673530''>should</span>
  <span m=''673730''>I</span> <span m=''673770''>do?</span> <span m=''676460''>Fold</span>
  <span m=''676830''>between</span> <span m=''677190''>them.</span> <span m=''678370''>Fold
  the</span> <span m=''678480''>lines</span> <span m=''678720''>onto</span> <span
  m=''678920''>each</span> <span m=''679060''>other,</span> <span m=''679250''>which</span>
  <span m=''679430''>is</span> <span m=''681050''>angular</span> <span m=''681480''>bisector.</span>
  <span m=''682270''>If</span> <span m=''682420''>I</span> <span m=''682500''>extend</span>
  <span m=''682870''>the</span> <span m=''682950''>lines,</span> <span m=''684470''>and</span>
  <span m=''684690''>I</span> <span m=''685040''>bisect</span> <span m=''686830''>the</span>
  <span m=''686950''>angle</span> <span m=''687250''>there,</span> <span m=''689030''>then</span>
  <span m=''689750''>I</span> <span m=''689920''>will</span> <span m=''690060''>fold</span>
  <span m=''690330''>one</span> <span m=''690470''>line</span> <span m=''690690''>to
  the other.</span> <span m=''691180''>I</span> <span m=''691250''>brought</span>
  <span m=''691550''>one</span> <span m=''691780''>just</span> <span m=''692060''>to</span>
  <span m=''692290''>be</span> <span m=''692810''>totally</span> <span m=''693610''>obvious.</span>
  <span m=''694150''>You</span> <span m=''694230''>have</span> <span m=''694840''>two</span>
  <span m=''694990''>lines</span> <span m=''695820''>fold</span> <span m=''696040''>along</span>
  <span m=''696100''>the</span> <span m=''696400''>angular</span> <span m=''696670''>bisector</span>
  <span m=''697130''>of their</span> <span m=''697250''>extensions.</span> <span m=''698240''>It</span>
  <span m=''698360''>lines</span> <span m=''698600''>up</span> <span m=''698710''>the</span>
  <span m=''698800''>lines,</span> <span m=''699130''>and</span> <span m=''699210''>nothing</span>
  <span m=''699570''>else.</span> </p><p><span m=''703370''>OK,</span> <span m=''704390''>a</span>
  <span m=''704860''>little</span> <span m=''705080''>more</span> <span m=''705230''>exciting.</span>
  <span m=''709680''>What</span> <span m=''709840''>if</span> <span m=''709960''>I</span>
  <span m=''710040''>had</span> <span m=''710590''>a</span> <span m=''711070''>triangle?</span>
  <span m=''713400''>How</span> <span m=''713600''>would</span> <span m=''713710''>you</span>
  <span m=''713810''>line</span> <span m=''714000''>up</span> <span m=''714080''>the</span>
  <span m=''714220''>edges</span> <span m=''714520''>the</span> <span m=''714640''>triangle</span>
  <span m=''715170''>and</span> <span m=''715250''>nothing</span> <span m=''715530''>else?</span>
  <span m=''717590''>Rabbit</span> <span m=''717960''>ear.</span> <span m=''718732''>Yes.</span>
  <span m=''721830''>Rabbit</span> <span m=''722230''>ear</span> <span m=''723390''>is</span>
  <span m=''724160''>you fold</span> <span m=''724390''>along</span> <span m=''724720''>the</span>
  <span m=''724800''>three</span> <span m=''725030''>angular</span> <span m=''725300''>bisectors</span>
  <span m=''726080''>of</span> <span m=''726270''>the</span> <span m=''726360''>triangle.</span>
  <span m=''726850''>This is</span> <span m=''726930''>something</span> <span m=''727240''>we</span>
  <span m=''727340''>talked</span> <span m=''727570''>about</span> <span m=''727760''>in</span>
  <span m=''727820''>the</span> <span m=''727920''>tree</span> <span m=''728100''>method.</span>
  </p><p><span m=''730230''>This</span> <span m=''730410''>is</span> <span m=''730530''>one</span>
  <span m=''730780''>of</span> <span m=''730940''>the</span> <span m=''731180''>sort
  of</span> <span m=''731310''>gadgets</span> <span m=''731760''>we</span> <span m=''731850''>use</span>
  <span m=''732170''>in</span> <span m=''732290''>one</span> <span m=''732570''>of--</span>
  <span m=''732970''>where</span> <span m=''733120''>these</span> <span m=''733320''>were</span>
  <span m=''733430''>active</span> <span m=''733740''>paths.</span> <span m=''735310''>And</span>
  <span m=''736820''>we</span> <span m=''736980''>fold</span> <span m=''737280''>along</span>
  <span m=''737440''>those</span> <span m=''737630''>angular</span> <span m=''737900''>bisectors.</span>
  <span m=''738410''>Angular</span> <span m=''738660''>bisectors</span> <span m=''739180''>intuitively</span>
  <span m=''739630''>are</span> <span m=''739700''>very</span> <span m=''739960''>good</span>
  <span m=''740220''>because</span> <span m=''740610''>locally</span> <span m=''740970''>they</span>
  <span m=''741120''>line</span> <span m=''741430''>up</span> <span m=''741640''>edges.</span>
  <span m=''743060''>So</span> <span m=''743110''>if</span> <span m=''743210''>I</span>
  <span m=''743270''>fold</span> <span m=''743550''>along</span> <span m=''743690''>all</span>
  <span m=''743840''>three</span> <span m=''744100''>of</span> <span m=''744180''>them,</span>
  <span m=''744400''>and</span> <span m=''744710''>you</span> <span m=''744800''>may</span>
  <span m=''744930''>know</span> <span m=''745140''>that they</span> <span m=''745390''>always</span>
  <span m=''745560''>meet</span> <span m=''745730''>at</span> <span m=''745830''>a</span>
  <span m=''745890''>point,</span> <span m=''747140''>then</span> <span m=''747440''>I</span>
  <span m=''747530''>kind of</span> <span m=''748010''>line up</span> <span m=''748110''>all</span>
  <span m=''748260''>those</span> <span m=''748440''>edges.</span> </p><p><span m=''749030''>If
  I</span> <span m=''749150''>just</span> <span m=''749450''>fold</span> <span m=''749720''>along</span>
  <span m=''749860''>those</span> <span m=''750030''>three</span> <span m=''750210''>edges,</span>
  <span m=''750450''>it</span> <span m=''750530''>won''t</span> <span m=''750730''>be</span>
  <span m=''750850''>flat</span> <span m=''751120''>foldable.</span> <span m=''751600''>It''s</span>
  <span m=''751730''>like</span> <span m=''751920''>this</span> <span m=''752660''>floppy</span>
  <span m=''753030''>thing.</span> <span m=''754090''>And</span> <span m=''754270''>so</span>
  <span m=''754470''>I''ve</span> <span m=''754810''>added</span> <span m=''755190''>in</span>
  <span m=''755910''>these</span> <span m=''756110''>perpendicular--</span> <span
  m=''756850''>the</span> <span m=''756960''>purple</span> <span m=''757280''>lines--</span>
  <span m=''758840''>to</span> <span m=''759040''>give</span> <span m=''759250''>me</span>
  <span m=''760020''>my</span> <span m=''760200''>hinges</span> <span m=''762050''>so</span>
  <span m=''762300''>I</span> <span m=''762410''>can</span> <span m=''762780''>manipulate</span>
  <span m=''763200''>these</span> <span m=''763380''>arms.</span> <span m=''763630''>You</span>
  <span m=''763760''>don''t</span> <span m=''763890''>have</span> <span m=''764030''>to</span>
  <span m=''764130''>use</span> <span m=''764250''>all</span> <span m=''764420''>of</span>
  <span m=''764510''>them.</span> <span m=''765080''>Then</span> <span m=''765240''>you</span>
  <span m=''765480''>flatten</span> <span m=''765850''>it,</span> <span m=''766310''>and</span>
  <span m=''766470''>now</span> <span m=''767570''>along</span> <span m=''767760''>this</span>
  <span m=''767940''>line</span> <span m=''768390''>are</span> <span m=''768540''>all</span>
  <span m=''768760''>the</span> <span m=''768840''>black</span> <span m=''769160''>guys.</span>
  <span m=''769950''>All the</span> <span m=''770400''>black</span> <span m=''770660''>lines.</span>
  <span m=''772660''>We''ve</span> <span m=''772800''>got</span> <span m=''773200''>a</span>
  <span m=''773260''>bunch</span> <span m=''773540''>of</span> <span m=''773630''>flat</span>
  <span m=''774080''>foldings.</span> </p><p><span m=''774660''>All</span> <span m=''775110''>right,</span>
  <span m=''775360''>so</span> <span m=''776806''>a</span> <span m=''777230''>general</span>
  <span m=''777570''>idea,</span> <span m=''778360''>and</span> <span m=''778670''>in
  the straight</span> <span m=''779010''>skeleton</span> <span m=''779300''>method,</span>
  <span m=''779680''>what</span> <span m=''779810''>we are</span> <span m=''779970''>going</span>
  <span m=''780150''>to</span> <span m=''780260''>use</span> <span m=''781020''>are</span>
  <span m=''781330''>angular</span> <span m=''781630''>bisectors</span> <span m=''782900''>and</span>
  <span m=''783200''>perpendicular</span> <span m=''783770''>folds.</span> <span m=''784070''>Perpendicular</span>
  <span m=''784580''>folds</span> <span m=''784820''>are</span> <span m=''784910''>also</span>
  <span m=''785190''>good</span> <span m=''785380''>because</span> <span m=''786730''>locally</span>
  <span m=''787090''>folds</span> <span m=''787340''>are a</span> <span m=''787380''>reflection</span>
  <span m=''787930''>if</span> <span m=''788050''>you</span> <span m=''788140''>fold</span>
  <span m=''788340''>flat.</span> <span m=''789110''>So</span> <span m=''789220''>this</span>
  <span m=''789960''>line</span> <span m=''790310''>will</span> <span m=''790420''>fold</span>
  <span m=''790690''>on</span> <span m=''790810''>top</span> <span m=''791110''>of</span>
  <span m=''791220''>this</span> <span m=''791400''>line.</span> </p><p><span m=''792290''>So</span>
  <span m=''792750''>perpendiculars</span> <span m=''793350''>are</span> <span m=''793410''>good.</span>
  <span m=''793610''>Angular</span> <span m=''793840''>bisectors</span> <span m=''794350''>are</span>
  <span m=''794410''>good.</span> <span m=''794540''>If</span> <span m=''794620''>you</span>
  <span m=''794710''>fold</span> <span m=''794900''>along</span> <span m=''795100''>all</span>
  <span m=''795330''>of</span> <span m=''795390''>them,</span> <span m=''795950''>you</span>
  <span m=''796030''>should</span> <span m=''796220''>line</span> <span m=''796440''>everything</span>
  <span m=''796810''>up.</span> <span m=''797690''>That''s the</span> <span m=''797910''>intuition,</span>
  <span m=''799230''>and</span> <span m=''801860''>the</span> <span m=''802330''>question</span>
  <span m=''802730''>is</span> <span m=''803400''>how</span> <span m=''803650''>do</span>
  <span m=''803750''>I</span> <span m=''803840''>fold</span> <span m=''804130''>a</span>
  <span m=''804170''>long</span> <span m=''804400''>enough</span> <span m=''804610''>angular</span>
  <span m=''804870''>bisectors</span> <span m=''805400''>and</span> <span m=''805500''>perpendiculars</span>
  <span m=''806100''>so</span> <span m=''806230''>that it</span> <span m=''806330''>actually</span>
  <span m=''806670''>folds</span> <span m=''806900''>flat.</span> <span m=''809090''>And</span>
  <span m=''809310''>that</span> <span m=''809490''>is</span> <span m=''809640''>the</span>
  <span m=''809730''>straight</span> <span m=''810020''>skeleton,</span> <span m=''811570''>or</span>
  <span m=''811690''>one</span> <span m=''811880''>way</span> <span m=''812000''>to</span>
  <span m=''812120''>do</span> <span m=''812230''>that</span> <span m=''812380''>is</span>
  <span m=''812520''>the</span> <span m=''812570''>straight</span> <span m=''812820''>skeleton.</span>
  </p><p><span m=''824020''>And</span> <span m=''824530''>this</span> <span m=''824870''>actually</span>
  <span m=''825280''>was</span> <span m=''825460''>invented</span> <span m=''826890''>a</span>
  <span m=''826940''>few</span> <span m=''827110''>years</span> <span m=''827320''>earlier.</span>
  <span m=''827910''>95,</span> <span m=''828620''>96</span> <span m=''830670''>by</span>
  <span m=''830880''>a</span> <span m=''830940''>couple</span> <span m=''831200''>of</span>
  <span m=''831260''>Austrians.</span> <span m=''832390''>That was</span> <span m=''832620''>in</span>
  <span m=''832690''>[INAUDIBLE]</span> <span m=''833380''>and</span> <span m=''833700''>actually</span>
  <span m=''834130''>four</span> <span m=''834350''>people.</span> <span m=''839950''>So</span>
  <span m=''840140''>let</span> <span m=''840280''>me</span> <span m=''840450''>write</span>
  <span m=''840650''>down</span> <span m=''840830''>a</span> <span m=''840880''>definition,</span>
  <span m=''841530''>and</span> <span m=''841640''>then</span> <span m=''841820''>we</span>
  <span m=''841930''>will--</span> <span m=''843800''>I''ll</span> <span m=''843930''>show</span>
  <span m=''844100''>you</span> <span m=''844250''>what</span> <span m=''844360''>it</span>
  <span m=''844430''>means.</span> </p><p><span m=''847040''>We''ve</span> <span m=''847180''>seen</span>
  <span m=''847490''>a</span> <span m=''847550''>thing</span> <span m=''847800''>like</span>
  <span m=''848120''>this</span> <span m=''848460''>very</span> <span m=''848660''>briefly</span>
  <span m=''849810''>in</span> <span m=''850040''>the</span> <span m=''850210''>universal</span>
  <span m=''850670''>molecule,</span> <span m=''851670''>but</span> <span m=''851810''>this</span>
  <span m=''851990''>is</span> <span m=''852070''>going</span> <span m=''852200''>to</span>
  <span m=''852270''>be</span> <span m=''852490''>more</span> <span m=''852720''>general</span>
  <span m=''853160''>in</span> <span m=''853470''>some</span> <span m=''853690''>sense.</span>
  <span m=''871660''>And</span> <span m=''871970''>actually,</span> <span m=''872230''>why</span>
  <span m=''872520''>don''t I</span> <span m=''872690''>put</span> <span m=''873180''>up
  an</span> <span m=''873260''>image</span> <span m=''873670''>of</span> <span m=''873870''>one</span>
  <span m=''875450''>while we''re</span> <span m=''877870''>defining</span> <span
  m=''878150''>it.</span> </p><p><span m=''919764''>All right,</span> <span m=''920300''>so</span>
  <span m=''920610''>it</span> <span m=''920820''>is</span> <span m=''921130''>trajectory</span>
  <span m=''921590''>of the</span> <span m=''921660''>vertices</span> <span m=''922450''>of</span>
  <span m=''922600''>the</span> <span m=''922720''>desired</span> <span m=''923130''>cut</span>
  <span m=''923380''>pattern--</span> <span m=''923550''>that''s</span> <span m=''923730''>our</span>
  <span m=''923830''>input.</span> <span m=''924290''>The</span> <span m=''925560''>graph</span>
  <span m=''925860''>of</span> <span m=''925990''>edges</span> <span m=''926280''>we</span>
  <span m=''926400''>want</span> <span m=''926640''>to</span> <span m=''926710''>cut</span>
  <span m=''926900''>out.</span> <span m=''928230''>As</span> <span m=''928460''>we</span>
  <span m=''928530''>simultaneously</span> <span m=''929280''>shrink</span> <span
  m=''929610''>each</span> <span m=''929840''>region.</span> <span m=''930300''>That''s</span>
  <span m=''930520''>every</span> <span m=''930800''>face</span> <span m=''931570''>outlined</span>
  <span m=''932200''>by</span> <span m=''932330''>those</span> <span m=''932560''>cuts.</span>
  <span m=''933490''>Keeping</span> <span m=''933870''>edges</span> <span m=''934120''>parallel</span>
  <span m=''934780''>and a</span> <span m=''935000''>uniform</span> <span m=''935380''>perpendicular</span>
  <span m=''935920''>distance</span> <span m=''936340''>from</span> <span m=''936610''>the</span>
  <span m=''936790''>original</span> <span m=''937140''>edges.</span> <span m=''938760''>So,</span>
  <span m=''939605''>a</span> <span m=''939920''>bit</span> <span m=''940050''>of</span>
  <span m=''940090''>a</span> <span m=''940140''>mouthful,</span> <span m=''940790''>but</span>
  <span m=''941210''>let</span> <span m=''941360''>me</span> <span m=''944080''>draw</span>
  <span m=''944230''>some</span> <span m=''944470''>pictures.</span> </p><p><span
  m=''945900''>Well,</span> <span m=''946260''>let''s</span> <span m=''946630''>maybe</span>
  <span m=''946860''>start</span> <span m=''947090''>with</span> <span m=''947220''>a</span>
  <span m=''947270''>triangle.</span> <span m=''948610''>So</span> <span m=''948880''>the</span>
  <span m=''949110''>idea</span> <span m=''949410''>with a</span> <span m=''949570''>triangle</span>
  <span m=''950790''>is</span> <span m=''951130''>you</span> <span m=''951330''>shrink--</span>
  <span m=''952420''>this</span> <span m=''952660''>is</span> <span m=''952740''>really</span>
  <span m=''952950''>the</span> <span m=''953050''>wrong</span> <span m=''953360''>order</span>
  <span m=''953680''>to</span> <span m=''953800''>do</span> <span m=''953940''>things.</span>
  <span m=''957030''>I</span> <span m=''957110''>want</span> <span m=''957250''>to</span>
  <span m=''957300''>shrink--</span> <span m=''957660''>there''s</span> <span m=''957830''>two</span>
  <span m=''958060''>regions</span> <span m=''958470''>for</span> <span m=''958550''>the</span>
  <span m=''958640''>triangle.</span> <span m=''958970''>There''s</span> <span m=''959080''>the</span>
  <span m=''959190''>inside</span> <span m=''959570''>and the</span> <span m=''959690''>outside.</span>
  <span m=''960500''>If I</span> <span m=''960600''>shrink</span> <span m=''960880''>the</span>
  <span m=''961000''>inside,</span> <span m=''962070''>I</span> <span m=''962220''>get</span>
  <span m=''962640''>these</span> <span m=''963870''>parallel</span> <span m=''964290''>lines.</span>
  <span m=''964760''>All--</span> <span m=''965120''>I</span> <span m=''965200''>want</span>
  <span m=''965390''>all</span> <span m=''965570''>of</span> <span m=''965640''>these</span>
  <span m=''965940''>distances</span> <span m=''966430''>to</span> <span m=''966550''>be</span>
  <span m=''966690''>equal.</span> <span m=''967420''>Those are</span> <span m=''967490''>the</span>
  <span m=''967560''>perpendicular</span> <span m=''968100''>distances.</span> <span
  m=''969900''>I keep</span> <span m=''970160''>shrinking,</span> <span m=''972130''>and</span>
  <span m=''972350''>at</span> <span m=''972430''>some</span> <span m=''972580''>point</span>
  <span m=''972910''>I</span> <span m=''972970''>can''t</span> <span m=''973180''>shrink</span>
  <span m=''973420''>anymore</span> <span m=''973730''>because</span> <span m=''973910''>I</span>
  <span m=''973950''>get</span> <span m=''974100''>a</span> <span m=''974160''>single</span>
  <span m=''974490''>point.</span> <span m=''975280''>The</span> <span m=''975640''>in-center</span>
  <span m=''975960''>of</span> <span m=''976010''>the</span> <span m=''976100''>triangle.</span>
  </p><p><span m=''976950''>If</span> <span m=''977050''>I</span> <span m=''977150''>watch</span>
  <span m=''977270''>where</span> <span m=''977490''>did</span> <span m=''977600''>the</span>
  <span m=''977670''>vertices</span> <span m=''978080''>go</span> <span m=''978300''>during</span>
  <span m=''978500''>that</span> <span m=''978690''>time,</span> <span m=''979490''>it''s</span>
  <span m=''979710''>along</span> <span m=''980130''>angular</span> <span m=''980410''>bisectors.</span>
  <span m=''981450''>Hey,</span> <span m=''982235''>our</span> <span m=''982510''>good</span>
  <span m=''982670''>friends,</span> <span m=''983600''>angular</span> <span m=''983850''>bisectors.</span>
  <span m=''984620''>Now</span> <span m=''984860''>I</span> <span m=''984930''>do</span>
  <span m=''985080''>the</span> <span m=''985170''>same</span> <span m=''985380''>thing</span>
  <span m=''985540''>on</span> <span m=''985610''>the</span> <span m=''985720''>outside.</span>
  <span m=''986230''>Shrinking</span> <span m=''987270''>the</span> <span m=''987450''>outside</span>
  <span m=''987840''>region is</span> <span m=''988320''>like</span> <span m=''988580''>expanding</span>
  <span m=''989180''>the</span> <span m=''989270''>triangle.</span> <span m=''990420''>As
  I</span> <span m=''990590''>expand</span> <span m=''991000''>the</span> <span m=''991080''>triangle,</span>
  <span m=''991460''>the</span> <span m=''991590''>outside</span> <span m=''991890''>gets</span>
  <span m=''992140''>smaller</span> <span m=''992610''>area.</span> </p><p><span m=''995120''>So</span>
  <span m=''995730''>actually,</span> <span m=''996020''>it''s</span> <span m=''996420''>just</span>
  <span m=''996620''>the</span> <span m=''996680''>same</span> <span m=''996960''>thing.</span>
  <span m=''997390''>I</span> <span m=''997550''>get</span> <span m=''997780''>concentric</span>
  <span m=''998960''>triangles,</span> <span m=''999740''>and</span> <span m=''999940''>I</span>
  <span m=''1000010''>just</span> <span m=''1000170''>keep</span> <span m=''1000340''>going</span>
  <span m=''1000590''>along</span> <span m=''1000790''>the</span> <span m=''1000860''>angular</span>
  <span m=''1001180''>bisectors.</span> <span m=''1002430''>So</span> <span m=''1002560''>that''s</span>
  <span m=''1002800''>it.</span> <span m=''1003280''>It''s</span> <span m=''1003430''>not</span>
  <span m=''1003640''>going</span> <span m=''1003730''>to</span> <span m=''1003780''>give</span>
  <span m=''1003930''>us</span> <span m=''1004080''>the</span> <span m=''1004180''>perpendicular</span>
  <span m=''1004780''>fold.</span> <span m=''1005460''>It''s</span> <span m=''1005580''>just</span>
  <span m=''1005800''>the</span> <span m=''1005890''>angular</span> <span m=''1006180''>bisector</span>
  <span m=''1006690''>parts.</span> <span m=''1007470''>Still</span> <span m=''1007770''>see
  a</span> <span m=''1008250''>triangle</span> <span m=''1008640''>in</span> <span
  m=''1008740''>there</span> <span m=''1008930''>somewhere.</span> </p><p><span m=''1011730''>OK,</span>
  <span m=''1012030''>that''s</span> <span m=''1012230''>a</span> <span m=''1012290''>really</span>
  <span m=''1012500''>simple</span> <span m=''1012790''>example,</span> <span m=''1013570''>and</span>
  <span m=''1013880''>the</span> <span m=''1013990''>only</span> <span m=''1014250''>event</span>
  <span m=''1014510''>that</span> <span m=''1014610''>happened</span> <span m=''1015050''>is</span>
  <span m=''1015280''>that</span> <span m=''1015950''>the</span> <span m=''1016170''>polygon</span>
  <span m=''1016640''>disappeared.</span> <span m=''1017640''>When</span> <span m=''1017770''>that</span>
  <span m=''1017910''>happens,</span> <span m=''1018250''>you</span> <span m=''1018350''>stop</span>
  <span m=''1019490''>with</span> <span m=''1019670''>that</span> <span m=''1019920''>particular</span>
  <span m=''1021000''>polygon.</span> </p><p><span m=''1023950''>In</span> <span m=''1024089''>general,</span>
  <span m=''1025680''>there</span> <span m=''1025900''>are</span> <span m=''1025950''>three</span>
  <span m=''1026180''>things</span> <span m=''1026420''>that</span> <span m=''1026500''>can</span>
  <span m=''1026640''>happen.</span> <span m=''1028400''>We call</span> <span m=''1028569''>these</span>
  <span m=''1028750''>events.</span> <span m=''1032210''>Three</span> <span m=''1032440''>interesting.</span>
  <span m=''1032900''>Things.</span> <span m=''1034589''>One</span> <span m=''1034819''>is</span>
  <span m=''1034970''>that</span> <span m=''1035130''>an</span> <span m=''1035300''>edge</span>
  <span m=''1036750''>disappears.</span> <span m=''1041550''>So</span> <span m=''1041720''>for</span>
  <span m=''1041869''>example,</span> <span m=''1042319''>locally,</span> <span m=''1042800''>if
  I</span> <span m=''1042849''>have</span> <span m=''1043200''>a</span> <span m=''1043260''>picture</span>
  <span m=''1043560''>like</span> <span m=''1043760''>this</span> <span m=''1044880''>and</span>
  <span m=''1045319''>I</span> <span m=''1045369''>shrink,</span> <span m=''1047300''>and</span>
  <span m=''1047609''>I</span> <span m=''1047650''>shrink,</span> <span m=''1049790''>and
  I</span> <span m=''1050020''>shrink,</span> <span m=''1050680''>at</span> <span
  m=''1050780''>some</span> <span m=''1050970''>point--</span> <span m=''1052500''>what''s</span>
  <span m=''1052620''>happening</span> <span m=''1052960''>is</span> <span m=''1053060''>these</span>
  <span m=''1053430''>angular</span> <span m=''1053760''>bisectors</span> <span m=''1054290''>are</span>
  <span m=''1054370''>meeting,</span> <span m=''1056730''>and</span> <span m=''1057200''>now</span>
  <span m=''1057630''>I</span> <span m=''1057760''>lost--</span> <span m=''1058220''>this</span>
  <span m=''1058400''>edge</span> <span m=''1058780''>shrinks</span> <span m=''1059110''>to</span>
  <span m=''1059200''>zero</span> <span m=''1059470''>length.</span> </p><p><span
  m=''1060410''>So</span> <span m=''1060590''>just</span> <span m=''1060760''>forget</span>
  <span m=''1060990''>about</span> <span m=''1061190''>the</span> <span m=''1061320''>edge.</span>
  <span m=''1061810''>Pretend</span> <span m=''1062090''>it</span> <span m=''1062140''>was</span>
  <span m=''1062260''>never</span> <span m=''1062470''>there.</span> <span m=''1062700''>Just</span>
  <span m=''1062880''>keeps</span> <span m=''1063040''>shrinking</span> <span m=''1063550''>now</span>
  <span m=''1063920''>what</span> <span m=''1064100''>is</span> <span m=''1064450''>these</span>
  <span m=''1064710''>two</span> <span m=''1064940''>edges.</span> <span m=''1065790''>And
  I</span> <span m=''1066110''>shrink,</span> <span m=''1067560''>and</span> <span
  m=''1068070''>I</span> <span m=''1068140''>shrink,</span> <span m=''1069140''>and
  I</span> <span m=''1069540''>shrink.</span> <span m=''1070900''>What</span> <span
  m=''1071050''>happens</span> <span m=''1071400''>is,</span> <span m=''1072120''>in
  some sense,</span> <span m=''1072530''>these</span> <span m=''1072990''>vertices</span>
  <span m=''1073550''>merge--</span> <span m=''1075460''>these</span> <span m=''1075630''>edges</span>
  <span m=''1075920''>merge,</span> <span m=''1076290''>and</span> <span m=''1076380''>now</span>
  <span m=''1076560''>I</span> <span m=''1076640''>have</span> <span m=''1076910''>one</span>
  <span m=''1077940''>guy</span> <span m=''1078140''>going</span> <span m=''1078370''>straight</span>
  <span m=''1078660''>up</span> <span m=''1078810''>there.</span> <span m=''1080400''>And</span>
  <span m=''1080620''>what</span> <span m=''1080820''>is</span> <span m=''1080960''>that</span>
  <span m=''1081190''>edge</span> <span m=''1081450''>doing?</span> <span m=''1081710''>It''s</span>
  <span m=''1081840''>not</span> <span m=''1082040''>an</span> <span m=''1082130''>angular</span>
  <span m=''1082410''>bisector of</span> <span m=''1082910''>this</span> <span m=''1083180''>or</span>
  <span m=''1083310''>this,</span> <span m=''1084280''>but</span> <span m=''1084390''>it''s</span>
  <span m=''1084520''>an</span> <span m=''1084610''>angular</span> <span m=''1084930''>bisector</span>
  <span m=''1085480''>of</span> <span m=''1085620''>the</span> <span m=''1085720''>extension</span>
  <span m=''1087550''>of</span> <span m=''1087730''>these</span> <span m=''1087910''>two</span>
  <span m=''1088070''>lines.</span> </p><p><span m=''1091620''>Because</span> <span
  m=''1092020''>if</span> <span m=''1092750''>you</span> <span m=''1092910''>look</span>
  <span m=''1093120''>at</span> <span m=''1093260''>this--</span> <span m=''1094410''>one</span>
  <span m=''1094620''>of</span> <span m=''1094700''>these</span> <span m=''1095480''>two</span>
  <span m=''1095650''>edges--</span> <span m=''1095950''>they are</span> <span m=''1096200''>parallel</span>
  <span m=''1096800''>to</span> <span m=''1096900''>the</span> <span m=''1097010''>two</span>
  <span m=''1097160''>original.</span> <span m=''1097620''>So</span> <span m=''1097760''>if</span>
  <span m=''1097840''>you</span> <span m=''1097940''>bisect</span> <span m=''1099050''>those</span>
  <span m=''1099210''>parallel</span> <span m=''1099490''>offsets,</span> <span m=''1099930''>it''s</span>
  <span m=''1100370''>the</span> <span m=''1100450''>same</span> <span m=''1100720''>thing</span>
  <span m=''1100950''>as</span> <span m=''1101060''>bisecting</span> <span m=''1102100''>the</span>
  <span m=''1102190''>original</span> <span m=''1102480''>edges</span> <span m=''1102810''>and</span>
  <span m=''1102930''>extension.</span> <span m=''1104490''>So</span> <span m=''1104680''>this</span>
  <span m=''1104970''>looks</span> <span m=''1105220''>good</span> <span m=''1105560''>because</span>
  <span m=''1106370''>these</span> <span m=''1106580''>two</span> <span m=''1106720''>folds</span>
  <span m=''1107040''>will</span> <span m=''1107260''>line</span> <span m=''1107520''>up</span>
  <span m=''1107650''>those</span> <span m=''1107850''>two</span> <span m=''1107960''>edges,</span>
  <span m=''1109560''>or</span> <span m=''1109720''>this</span> <span m=''1109930''>fold
  will</span> <span m=''1110180''>line up</span> <span m=''1110450''>these</span>
  <span m=''1110620''>two</span> <span m=''1110740''>edge.</span> <span m=''1111000''>This</span>
  <span m=''1111200''>fold will</span> <span m=''1111500''>line</span> <span m=''1111670''>up</span>
  <span m=''1111770''>those</span> <span m=''1111970''>two</span> <span m=''1112100''>edges.</span>
  <span m=''1112410''>This</span> <span m=''1112620''>fold</span> <span m=''1112910''>will</span>
  <span m=''1113300''>line</span> <span m=''1113600''>up</span> <span m=''1113710''>these</span>
  <span m=''1113890''>two</span> <span m=''1114090''>edges.</span> <span m=''1114620''>And</span>
  <span m=''1114710''>we''re</span> <span m=''1114810''>doing</span> <span m=''1115080''>kind</span>
  <span m=''1115250''>of</span> <span m=''1115320''>extra</span> <span m=''1115610''>alignment,</span>
  <span m=''1116080''>but</span> <span m=''1116770''>everything</span> <span m=''1117180''>looks</span>
  <span m=''1117570''>kosher.</span> </p><p><span m=''1120830''>Good.</span> <span
  m=''1123580''>So</span> <span m=''1123730''>when an</span> <span m=''1124110''>edge</span>
  <span m=''1124435''>disappears,</span> <span m=''1124760''>you</span> <span m=''1124890''>just</span>
  <span m=''1125530''>forget</span> <span m=''1125850''>about</span> <span m=''1126140''>it.</span>
  <span m=''1130650''>All right,</span> <span m=''1130900''>forget--</span> <span
  m=''1131890''>it''s</span> <span m=''1132325''>probably</span> <span m=''1132760''>"forgedaboutit"--</span>
  <span m=''1133480''>something</span> <span m=''1133810''>like</span> <span m=''1133980''>that.</span>
  <span m=''1136092''>All right.</span> <span m=''1137900''>Then</span> <span m=''1138210''>we</span>
  <span m=''1138350''>have--</span> <span m=''1140890''>a</span> <span m=''1140970''>region</span>
  <span m=''1141400''>can</span> <span m=''1141550''>disappear.</span> <span m=''1145850''>That''s</span>
  <span m=''1145960''>what</span> <span m=''1146050''>happened</span> <span m=''1146310''>with</span>
  <span m=''1146430''>the</span> <span m=''1146510''>triangle.</span> <span m=''1148970''>And</span>
  <span m=''1149120''>then</span> <span m=''1149920''>again,</span> <span m=''1150350''>you</span>
  <span m=''1150460''>forget</span> <span m=''1150730''>about</span> <span m=''1151020''>it.</span>
  <span m=''1155340''>There</span> <span m=''1155470''>may</span> <span m=''1155600''>be</span>
  <span m=''1155720''>many</span> <span m=''1155960''>regions.</span> <span m=''1156390''>You</span>
  <span m=''1156470''>have</span> <span m=''1156550''>to</span> <span m=''1156640''>keep</span>
  <span m=''1156820''>shrinking</span> <span m=''1157130''>the</span> <span m=''1157230''>other</span>
  <span m=''1157410''>regions,</span> <span m=''1157735''>but</span> <span m=''1158060''>when</span>
  <span m=''1158250''>one</span> <span m=''1158410''>disappears,</span> <span m=''1159140''>you''re</span>
  <span m=''1159280''>done.</span> </p><p><span m=''1161310''>Third</span> <span m=''1161510''>thing</span>
  <span m=''1161660''>that</span> <span m=''1161730''>can</span> <span m=''1161850''>happen</span>
  <span m=''1163500''>is</span> <span m=''1163750''>that</span> <span m=''1164140''>a</span>
  <span m=''1164230''>region</span> <span m=''1165030''>splits.</span> <span m=''1169950''>So</span>
  <span m=''1170220''>let''s</span> <span m=''1170490''>look</span> <span m=''1170690''>at</span>
  <span m=''1170760''>an</span> <span m=''1170900''>interesting</span> <span m=''1172390''>polygon.</span>
  <span m=''1176250''>This</span> <span m=''1176460''>one--</span> <span m=''1181040''>the</span>
  <span m=''1181100''>straight</span> <span m=''1181610''>edges.</span> <span m=''1182580''>And</span>
  <span m=''1183110''>when</span> <span m=''1183240''>I</span> <span m=''1183310''>shrink</span>
  <span m=''1183660''>this</span> <span m=''1183900''>guy--</span> <span m=''1187430''>see,</span>
  <span m=''1187590''>what''s</span> <span m=''1187770''>happening</span> <span m=''1188130''>is</span>
  <span m=''1188260''>this</span> <span m=''1188520''>edge</span> <span m=''1188850''>is</span>
  <span m=''1188930''>approaching</span> <span m=''1189390''>that</span> <span m=''1189600''>vertex,</span>
  <span m=''1194110''>and at</span> <span m=''1194270''>some</span> <span m=''1194480''>point</span>
  <span m=''1196490''>they</span> <span m=''1196640''>will</span> <span m=''1196760''>meet.</span>
  </p><p><span m=''1200670''>And</span> <span m=''1200830''>what</span> <span m=''1200950''>we''re</span>
  <span m=''1201070''>left</span> <span m=''1201340''>with</span> <span m=''1201710''>are</span>
  <span m=''1202060''>two</span> <span m=''1202230''>triangles</span> <span m=''1203160''>in</span>
  <span m=''1203240''>this</span> <span m=''1203410''>case.</span> <span m=''1204120''>And</span>
  <span m=''1204260''>generally</span> <span m=''1204640''>split</span> <span m=''1204890''>into</span>
  <span m=''1205090''>two</span> <span m=''1205240''>parts,</span> <span m=''1206060''>you</span>
  <span m=''1206140''>just</span> <span m=''1206340''>keep</span> <span m=''1206520''>shrinking</span>
  <span m=''1206850''>the</span> <span m=''1206940''>parts.</span> <span m=''1208380''>So</span>
  <span m=''1208540''>it''s</span> <span m=''1209290''>not</span> <span m=''1209460''>really</span>
  <span m=''1209710''>like</span> <span m=''1209900''>you''re</span> <span m=''1210010''>stopping</span>
  <span m=''1210480''>at</span> <span m=''1210530''>any</span> <span m=''1210720''>point.</span>
  <span m=''1211710''>Just</span> <span m=''1211870''>the</span> <span m=''1211940''>same</span>
  <span m=''1212220''>thing</span> <span m=''1212460''>over</span> <span m=''1212640''>and</span>
  <span m=''1212720''>over.</span> <span m=''1213890''>But</span> <span m=''1213990''>if</span>
  <span m=''1214070''>you''re</span> <span m=''1214210''>implementing</span> <span
  m=''1214650''>this</span> <span m=''1214810''>on</span> <span m=''1214900''>a</span>
  <span m=''1214970''>computer,</span> <span m=''1215380''>you</span> <span m=''1215490''>really</span>
  <span m=''1215670''>have</span> <span m=''1215800''>to</span> <span m=''1215930''>realize</span>
  <span m=''1216460''>that</span> <span m=''1216600''>happens.</span> <span m=''1217010''>Otherwise</span>
  <span m=''1217410''>you''d</span> <span m=''1217610''>shrink</span> <span m=''1217940''>them</span>
  <span m=''1218100''>beyond</span> <span m=''1218550''>each</span> <span m=''1218720''>other</span>
  <span m=''1218990''>and</span> <span m=''1219090''>it</span> <span m=''1219160''>would</span>
  <span m=''1219340''>be</span> <span m=''1219600''>self</span> <span m=''1219870''>intersecting</span>
  <span m=''1220440''>and</span> <span m=''1220520''>ugly.</span> </p><p><span m=''1222190''>But</span>
  <span m=''1222310''>you</span> <span m=''1222480''>do the</span> <span m=''1222640''>obvious</span>
  <span m=''1222950''>thing,</span> <span m=''1223250''>which</span> <span m=''1223460''>is</span>
  <span m=''1223540''>you</span> <span m=''1223700''>cut</span> <span m=''1224680''>where</span>
  <span m=''1224800''>they</span> <span m=''1224920''>split.</span> <span m=''1225990''>And</span>
  <span m=''1226220''>what</span> <span m=''1226290''>will</span> <span m=''1226410''>happen</span>
  <span m=''1226680''>in</span> <span m=''1226720''>this</span> <span m=''1226880''>case</span>
  <span m=''1227060''>with</span> <span m=''1227160''>straight</span> <span m=''1227410''>skeleton</span>
  <span m=''1228410''>is</span> <span m=''1228460''>you</span> <span m=''1228760''>keep</span>
  <span m=''1229020''>going</span> <span m=''1229300''>along</span> <span m=''1229520''>an
  angular</span> <span m=''1229850''>bisector</span> <span m=''1230910''>until</span>
  <span m=''1231480''>that</span> <span m=''1231900''>little</span> <span m=''1232150''>triangle</span>
  <span m=''1232530''>stops.</span> <span m=''1240430''>One</span> <span m=''1240610''>more</span>
  <span m=''1240810''>edge</span> <span m=''1241230''>here.</span> </p><p><span m=''1243970''>So</span>
  <span m=''1244180''>that''s</span> <span m=''1244460''>what the</span> <span m=''1244560''>straight</span>
  <span m=''1244800''>skeleton</span> <span m=''1245080''>will</span> <span m=''1245160''>look</span>
  <span m=''1245360''>like.</span> <span m=''1245600''>This</span> <span m=''1245890''>edge</span>
  <span m=''1246270''>is</span> <span m=''1246360''>an</span> <span m=''1246440''>angular</span>
  <span m=''1246680''>bisector</span> <span m=''1247030''>of</span> <span m=''1247120''>this</span>
  <span m=''1247290''>one</span> <span m=''1247540''>and this</span> <span m=''1247760''>one.</span>
  <span m=''1248560''>This</span> <span m=''1248620''>edge</span> <span m=''1248960''>is</span>
  <span m=''1249110''>an</span> <span m=''1249170''>angular</span> <span m=''1249280''>bisector</span>
  <span m=''1249590''>of</span> <span m=''1249760''>this</span> <span m=''1249990''>one</span>
  <span m=''1250150''>and</span> <span m=''1250220''>this</span> <span m=''1250400''>one.</span>
  <span m=''1251180''>In</span> <span m=''1251290''>general,</span> <span m=''1252220''>if</span>
  <span m=''1252360''>you</span> <span m=''1252720''>look</span> <span m=''1252980''>at</span>
  <span m=''1253040''>an</span> <span m=''1253150''>edge,</span> <span m=''1254090''>and</span>
  <span m=''1254250''>you</span> <span m=''1254330''>see</span> <span m=''1255690''>what</span>
  <span m=''1256360''>original</span> <span m=''1256870''>edge</span> <span m=''1257150''>can</span>
  <span m=''1257310''>I</span> <span m=''1257390''>reach</span> <span m=''1258070''>without</span>
  <span m=''1258430''>crossing</span> <span m=''1258960''>another</span> <span m=''1259240''>skeleton</span>
  <span m=''1259720''>edge,</span> <span m=''1260600''>those</span> <span m=''1260780''>are</span>
  <span m=''1260810''>the two</span> <span m=''1261200''>that you bisect.</span> </p><p><span
  m=''1262020''>So</span> <span m=''1262130''>it''s</span> <span m=''1262220''>really</span>
  <span m=''1262460''>easy</span> <span m=''1262730''>to</span> <span m=''1262800''>see.</span>
  <span m=''1263210''>Look</span> <span m=''1263380''>at</span> <span m=''1263450''>this</span>
  <span m=''1263640''>guy.</span> <span m=''1264220''>The only</span> <span m=''1264470''>two</span>
  <span m=''1264640''>I</span> <span m=''1264700''>can</span> <span m=''1264850''>reach</span>
  <span m=''1265070''>are</span> <span m=''1265120''>this</span> <span m=''1265320''>one</span>
  <span m=''1265550''>and this</span> <span m=''1265740''>one.</span> <span m=''1266540''>I</span>
  <span m=''1266620''>look</span> <span m=''1266800''>at</span> <span m=''1266870''>this</span>
  <span m=''1267050''>one,</span> <span m=''1267520''>the only</span> <span m=''1267720''>two
  I can</span> <span m=''1268130''>reach</span> <span m=''1268260''>are that</span>
  <span m=''1268480''>one</span> <span m=''1268670''>and</span> <span m=''1268760''>that</span>
  <span m=''1268940''>one.</span> <span m=''1269120''>So</span> <span m=''1269250''>it''s</span>
  <span m=''1269370''>an</span> <span m=''1269410''>angular</span> <span m=''1269710''>bisector</span>
  <span m=''1270170''>of</span> <span m=''1270240''>those</span> <span m=''1270460''>two.</span>
  <span m=''1271480''>In fact,</span> <span m=''1271700''>in</span> <span m=''1271770''>general,</span>
  <span m=''1272100''>if</span> <span m=''1272180''>you</span> <span m=''1272300''>finish</span>
  <span m=''1272590''>the</span> <span m=''1272740''>outside</span> <span m=''1273140''>here</span>
  <span m=''1273320''>too,</span> <span m=''1274085''>it''s</span> <span m=''1274530''>the</span>
  <span m=''1274610''>same</span> <span m=''1274830''>deal.</span> <span m=''1276750''>And</span>
  <span m=''1277230''>then--</span> <span m=''1277860''>yeah,</span> <span m=''1278200''>all
  right,</span> <span m=''1278780''>enough.</span> </p><p><span m=''1279740''>Here''s</span>
  <span m=''1280000''>a</span> <span m=''1280070''>bigger</span> <span m=''1280340''>example.</span>
  <span m=''1281740''>Little</span> <span m=''1281940''>turtle</span> <span m=''1283300''>drawn</span>
  <span m=''1283610''>on</span> <span m=''1283770''>a</span> <span m=''1283820''>triangular</span>
  <span m=''1284230''>grid,</span> <span m=''1285180''>and</span> <span m=''1285490''>you</span>
  <span m=''1285580''>can</span> <span m=''1285680''>see</span> <span m=''1285840''>there''s</span>
  <span m=''1286020''>angular</span> <span m=''1286300''>bisectors.</span> <span m=''1286950''>This</span>
  <span m=''1287110''>is</span> <span m=''1287230''>a</span> <span m=''1287300''>straight</span>
  <span m=''1287560''>skeleton.</span> <span m=''1288500''>This</span> <span m=''1288610''>guy,</span>
  <span m=''1288780''>for</span> <span m=''1288920''>example,</span> <span m=''1289280''>bisects</span>
  <span m=''1289820''>this</span> <span m=''1289970''>horizontal</span> <span m=''1290480''>edge</span>
  <span m=''1290650''>and</span> <span m=''1290710''>this</span> <span m=''1290840''>horizontal</span>
  <span m=''1291350''>edge</span> <span m=''1291540''>has</span> <span m=''1291720''>a</span>
  <span m=''1291770''>little</span> <span m=''1292110''>bit</span> <span m=''1292240''>of</span>
  <span m=''1292350''>a</span> <span m=''1292420''>boundary</span> <span m=''1292760''>case</span>
  <span m=''1293000''>we have</span> <span m=''1293120''>to think</span> <span m=''1293420''>about,</span>
  <span m=''1293800''>but</span> <span m=''1293940''>this</span> <span m=''1294110''>is</span>
  <span m=''1294210''>the</span> <span m=''1294320''>right</span> <span m=''1294530''>interpretation.</span>
  <span m=''1297740''>It''s</span> <span m=''1297770''>like</span> <span m=''1297970''>an</span>
  <span m=''1298160''>angle</span> <span m=''1298390''>of</span> <span m=''1298460''>180,</span>
  <span m=''1298905''>so you</span> <span m=''1299350''>bisect</span> <span m=''1299480''>it</span>
  <span m=''1299780''>to</span> <span m=''1299930''>90.</span> <span m=''1301770''>Other</span>
  <span m=''1301960''>fun</span> <span m=''1302230''>features.</span> </p><p><span
  m=''1303410''>Here</span> <span m=''1303590''>we</span> <span m=''1303690''>get</span>
  <span m=''1303800''>a</span> <span m=''1303850''>little</span> <span m=''1304040''>bit</span>
  <span m=''1304160''>of</span> <span m=''1304230''>action</span> <span m=''1304540''>on</span>
  <span m=''1304610''>the</span> <span m=''1304740''>outside</span> <span m=''1305160''>of</span>
  <span m=''1305290''>the</span> <span m=''1305370''>polygon.</span> <span m=''1306170''>So</span>
  <span m=''1306340''>far,</span> <span m=''1306520''>we</span> <span m=''1306630''>haven''t</span>
  <span m=''1306910''>seen</span> <span m=''1307100''>that.</span> <span m=''1308110''>So,
  like</span> <span m=''1308430''>these</span> <span m=''1308640''>guys</span> <span
  m=''1308890''>meet,</span> <span m=''1310280''>and</span> <span m=''1310710''>there</span>
  <span m=''1310890''>is</span> <span m=''1310980''>some</span> <span m=''1312810''>bigger--</span>
  <span m=''1314400''>there''s</span> <span m=''1314610''>a</span> <span m=''1314660''>bigger</span>
  <span m=''1315000''>turtle</span> <span m=''1315370''>here</span> <span m=''1315740''>somewhere.</span>
  <span m=''1316680''>It''s</span> <span m=''1316790''>hard</span> <span m=''1316980''>to</span>
  <span m=''1317050''>draw.</span> <span m=''1318630''>Anyway,</span> <span m=''1320780''>what''s</span>
  <span m=''1321000''>happening</span> <span m=''1321310''>is</span> <span m=''1321410''>this</span>
  <span m=''1321610''>edge</span> <span m=''1321780''>is</span> <span m=''1321840''>shrinking</span>
  <span m=''1322270''>to</span> <span m=''1322370''>zero</span> <span m=''1324060''>while</span>
  <span m=''1324370''>this</span> <span m=''1324560''>one is</span> <span m=''1324850''>offsetting</span>
  <span m=''1325380''>down</span> <span m=''1325590''>this</span> <span m=''1325790''>way</span>
  <span m=''1326080''>and</span> <span m=''1326170''>this</span> <span m=''1326310''>is</span>
  <span m=''1326610''>offsetting</span> <span m=''1326890''>down</span> <span m=''1327090''>this</span>
  <span m=''1327300''>way.</span> <span m=''1327680''>So</span> <span m=''1327770''>the</span>
  <span m=''1327880''>new</span> <span m=''1328040''>turtle</span> <span m=''1328830''>ends
  up</span> <span m=''1329120''>being</span> <span m=''1329300''>like</span> <span
  m=''1329510''>that.</span> <span m=''1332360''>And</span> <span m=''1332420''>so</span>
  <span m=''1332540''>on.</span> </p><p><span m=''1336780''>You''re</span> <span m=''1337080''>shrinking</span>
  <span m=''1337690''>every</span> <span m=''1338060''>face.</span> <span m=''1338860''>So</span>
  <span m=''1339130''>in</span> <span m=''1339220''>general,</span> <span m=''1339580''>you</span>
  <span m=''1339660''>have</span> <span m=''1339830''>a</span> <span m=''1339860''>whole</span>
  <span m=''1340050''>bunch</span> <span m=''1340270''>of</span> <span m=''1340350''>polygons.</span>
  <span m=''1341360''>Or</span> <span m=''1342290''>in</span> <span m=''1342440''>general</span>
  <span m=''1343060''>we''re</span> <span m=''1343250''>allowing</span> <span m=''1344130''>crazy</span>
  <span m=''1344500''>things</span> <span m=''1344840''>like</span> <span m=''1345650''>this</span>
  <span m=''1346290''>as</span> <span m=''1346610''>this</span> <span m=''1346940''>pattern</span>
  <span m=''1347300''>of</span> <span m=''1347410''>cuts</span> <span m=''1347740''>I</span>
  <span m=''1347780''>want</span> <span m=''1347960''>to</span> <span m=''1348010''>make.</span>
  <span m=''1349090''>Maybe</span> <span m=''1349330''>you</span> <span m=''1349420''>want</span>
  <span m=''1349580''>to</span> <span m=''1349750''>cut</span> <span m=''1349990''>your</span>
  <span m=''1350140''>square</span> <span m=''1350470''>into</span> <span m=''1350750''>five</span>
  <span m=''1351090''>pieces.</span> <span m=''1351970''>I''m</span> <span m=''1352070''>going</span>
  <span m=''1352150''>to</span> <span m=''1352190''>shrink</span> <span m=''1352440''>each</span>
  <span m=''1352650''>of</span> <span m=''1352750''>them</span> <span m=''1352940''>separately,</span>
  <span m=''1354550''>or</span> <span m=''1354770''>in</span> <span m=''1354850''>parallel.</span>
  <span m=''1355320''>It doesn''t</span> <span m=''1355560''>actually</span> <span
  m=''1355830''>matter.</span> </p><p><span m=''1357910''>So</span> <span m=''1358030''>in</span>
  <span m=''1358100''>this</span> <span m=''1358280''>case</span> <span m=''1358530''>there''s</span>
  <span m=''1358630''>just</span> <span m=''1358810''>going</span> <span m=''1358930''>to</span>
  <span m=''1359000''>be</span> <span m=''1359170''>five</span> <span m=''1359450''>angular</span>
  <span m=''1359740''>bisectors.</span> <span m=''1361410''>In</span> <span m=''1361520''>general,</span>
  <span m=''1361900''>there are</span> <span m=''1361980''>several</span> <span m=''1362260''>regions</span>
  <span m=''1362610''>you</span> <span m=''1362690''>shrink</span> <span m=''1362940''>all</span>
  <span m=''1363160''>of them.</span> <span m=''1364090''>A lot</span> <span m=''1364350''>of</span>
  <span m=''1364400''>the</span> <span m=''1364480''>time</span> <span m=''1364740''>we</span>
  <span m=''1364850''>think</span> <span m=''1365010''>about</span> <span m=''1365240''>polygons,</span>
  <span m=''1365890''>and</span> <span m=''1366010''>then</span> <span m=''1366150''>there''s</span>
  <span m=''1366330''>two</span> <span m=''1366490''>regions</span> <span m=''1366820''>to</span>
  <span m=''1366910''>shrink.</span> <span m=''1367860''>And</span> <span m=''1368340''>it</span>
  <span m=''1368470''>looks</span> <span m=''1368760''>like</span> <span m=''1368920''>you''re</span>
  <span m=''1369030''>expanding</span> <span m=''1369460''>the</span> <span m=''1369550''>turtle</span>
  <span m=''1369870''>to</span> <span m=''1369980''>go</span> <span m=''1370180''>out,</span>
  <span m=''1370500''>but</span> <span m=''1370630''>really</span> <span m=''1370900''>you''re</span>
  <span m=''1370960''>shrinking</span> <span m=''1371360''>the</span> <span m=''1371470''>outside</span>
  <span m=''1371780''>region.</span> <span m=''1372380''>It just</span> <span m=''1372580''>happens</span>
  <span m=''1372900''>to</span> <span m=''1372990''>be--</span> <span m=''1373530''>there''s</span>
  <span m=''1373680''>one</span> <span m=''1374010''>infinite</span> <span m=''1374340''>region</span>
  <span m=''1374680''>that</span> <span m=''1374820''>one</span> <span m=''1374940''>looks</span>
  <span m=''1375150''>weird.</span> </p><p><span m=''1379250''>A</span> <span m=''1379310''>couple</span>
  <span m=''1379590''>other</span> <span m=''1379790''>special</span> <span m=''1380150''>cases,</span>
  <span m=''1381870''>because</span> <span m=''1382080''>I</span> <span m=''1382130''>want</span>
  <span m=''1382360''>to</span> <span m=''1382430''>do</span> <span m=''1382600''>any</span>
  <span m=''1382960''>graph</span> <span m=''1383710''>and</span> <span m=''1383990''>not</span>
  <span m=''1384190''>just</span> <span m=''1384360''>polygons.</span> <span m=''1385380''>You</span>
  <span m=''1385490''>could</span> <span m=''1385650''>have</span> <span m=''1386480''>something</span>
  <span m=''1386820''>that</span> <span m=''1386890''>just</span> <span m=''1387120''>terminates.</span>
  <span m=''1388990''>So</span> <span m=''1389420''>a</span> <span m=''1389650''>degree</span>
  <span m=''1389960''>one</span> <span m=''1390180''>vertex</span> <span m=''1390640''>only</span>
  <span m=''1390790''>has</span> <span m=''1390930''>one</span> <span m=''1391160''>[?
  edge ?]</span> <span m=''1391550''>into</span> <span m=''1391860''>it.</span> <span
  m=''1392550''>In</span> <span m=''1392710''>this</span> <span m=''1392890''>case,</span>
  <span m=''1393130''>it''s</span> <span m=''1393250''>not</span> <span m=''1393450''>quite</span>
  <span m=''1393750''>well</span> <span m=''1393940''>defined</span> <span m=''1394270''>what</span>
  <span m=''1394440''>to</span> <span m=''1394540''>do</span> <span m=''1394820''>because</span>
  <span m=''1395230''>you</span> <span m=''1395490''>offset</span> <span m=''1396000''>this</span>
  <span m=''1396430''>and you</span> <span m=''1396900''>offset</span> <span m=''1397280''>this,</span>
  <span m=''1397630''>but</span> <span m=''1397660''>what</span> <span m=''1397830''>happens</span>
  <span m=''1398230''>here?</span> <span m=''1399340''>And</span> <span m=''1399580''>there</span>
  <span m=''1400190''>it''s sort</span> <span m=''1400360''>of</span> <span m=''1400430''>arbitrary.</span>
  </p><p><span m=''1400970''>You can</span> <span m=''1401060''>do</span> <span m=''1401150''>whatever</span>
  <span m=''1401390''>you</span> <span m=''1401500''>want,</span> <span m=''1401750''>but</span>
  <span m=''1402060''>the</span> <span m=''1402160''>simplest</span> <span m=''1402560''>thing</span>
  <span m=''1402680''>you</span> <span m=''1402800''>can</span> <span m=''1402940''>do</span>
  <span m=''1403630''>is</span> <span m=''1403880''>to</span> <span m=''1404020''>make</span>
  <span m=''1404340''>a--</span> <span m=''1405180''>imagine</span> <span m=''1405640''>that</span>
  <span m=''1405750''>there''s</span> <span m=''1405920''>a</span> <span m=''1405970''>little</span>
  <span m=''1406240''>vertical</span> <span m=''1406660''>segment</span> <span m=''1406980''>here</span>
  <span m=''1407110''>that</span> <span m=''1407230''>happens</span> <span m=''1407520''>to</span>
  <span m=''1407600''>be</span> <span m=''1407720''>length</span> <span m=''1407930''>zero,</span>
  <span m=''1408740''>and</span> <span m=''1408930''>it</span> <span m=''1409120''>expands</span>
  <span m=''1410340''>into</span> <span m=''1410760''>the</span> <span m=''1410990''>edge</span>
  <span m=''1411750''>of</span> <span m=''1411890''>a</span> <span m=''1411950''>rectangle.</span>
  <span m=''1414680''>So</span> <span m=''1414720''>you</span> <span m=''1414780''>end</span>
  <span m=''1414910''>up</span> <span m=''1415040''>with</span> <span m=''1415130''>these</span>
  <span m=''1415310''>245</span> <span m=''1417230''>degree</span> <span m=''1418990''>angular</span>
  <span m=''1420550''>bisectors</span> <span m=''1420910''>between this</span> <span
  m=''1421370''>vertical</span> <span m=''1421780''>edge</span> <span m=''1422020''>and</span>
  <span m=''1422150''>the</span> <span m=''1422580''>horizontal</span> <span m=''1423020''>one.</span>
  <span m=''1424760''>But</span> <span m=''1425370''>you have</span> <span m=''1425790''>some</span>
  <span m=''1425950''>flexibility</span> <span m=''1426520''>there.</span> <span m=''1427000''>You
  can</span> <span m=''1427070''>design</span> <span m=''1427370''>it</span> <span
  m=''1427430''>how</span> <span m=''1427540''>you</span> <span m=''1427700''>want.</span>
  </p><p><span m=''1428780''>The</span> <span m=''1428890''>other</span> <span m=''1429020''>case</span>
  <span m=''1429240''>you</span> <span m=''1429330''>can</span> <span m=''1429440''>have</span>
  <span m=''1429630''>is</span> <span m=''1429740''>a</span> <span m=''1429790''>degree</span>
  <span m=''1430100''>0</span> <span m=''1430500''>vertex.</span> <span m=''1430940''>There</span>
  <span m=''1431120''>are</span> <span m=''1431160''>no</span> <span m=''1432100''>edges</span>
  <span m=''1432720''>here.</span> <span m=''1433970''>This is</span> <span m=''1434150''>a</span>
  <span m=''1434230''>little</span> <span m=''1434450''>funny</span> <span m=''1434750''>in</span>
  <span m=''1434850''>the</span> <span m=''1434940''>way</span> <span m=''1435130''>I
  defined</span> <span m=''1435600''>it.</span> <span m=''1435770''>I</span> <span
  m=''1435840''>just</span> <span m=''1436020''>said</span> <span m=''1436180''>I</span>
  <span m=''1436220''>wanted</span> <span m=''1436500''>to</span> <span m=''1436620''>align</span>
  <span m=''1436880''>line</span> <span m=''1437170''>segments.</span> <span m=''1438030''>You</span>
  <span m=''1438170''>could</span> <span m=''1438300''>also</span> <span m=''1438600''>align</span>
  <span m=''1438890''>points</span> <span m=''1439440''>if</span> <span m=''1439550''>you</span>
  <span m=''1439650''>really</span> <span m=''1439870''>feel</span> <span m=''1440060''>like</span>
  <span m=''1440290''>it,</span> <span m=''1441050''>and</span> <span m=''1441230''>that</span>
  <span m=''1441360''>would</span> <span m=''1441460''>be</span> <span m=''1441590''>represented</span>
  <span m=''1442090''>by</span> <span m=''1442270''>a</span> <span m=''1442350''>dot</span>
  <span m=''1443030''>that</span> <span m=''1443140''>has</span> <span m=''1443330''>no</span>
  <span m=''1443800''>cuts</span> <span m=''1444220''>next</span> <span m=''1444420''>to</span>
  <span m=''1444520''>it.</span> </p><p><span m=''1444630''>If</span> <span m=''1444720''>you</span>
  <span m=''1444850''>want</span> <span m=''1445040''>to</span> <span m=''1445240''>cut
  out</span> <span m=''1445320''>just</span> <span m=''1445600''>this</span> <span
  m=''1445770''>point--</span> <span m=''1447560''>I</span> <span m=''1447670''>need</span>
  <span m=''1447980''>to</span> <span m=''1448220''>make</span> <span m=''1448430''>it</span>
  <span m=''1448540''>something.</span> <span m=''1448880''>You</span> <span m=''1449000''>could</span>
  <span m=''1449290''>think</span> <span m=''1449470''>of</span> <span m=''1449560''>it</span>
  <span m=''1449610''>as</span> <span m=''1449720''>a</span> <span m=''1449800''>tiny</span>
  <span m=''1450050''>triangle</span> <span m=''1450500''>for</span> <span m=''1450670''>consistency</span>
  <span m=''1451260''>with</span> <span m=''1451370''>this</span> <span m=''1451510''>picture.</span>
  <span m=''1452230''>We</span> <span m=''1452360''>think</span> <span m=''1452520''>of
  it</span> <span m=''1452590''>as</span> <span m=''1452720''>a</span> <span m=''1452760''>little</span>
  <span m=''1452930''>square.</span> <span m=''1453980''>And</span> <span m=''1454200''>so,</span>
  <span m=''1455050''>when</span> <span m=''1455240''>you</span> <span m=''1455320''>expand</span>
  <span m=''1456380''>it,</span> <span m=''1456660''>or</span> <span m=''1456830''>when</span>
  <span m=''1456990''>you</span> <span m=''1457090''>shrink</span> <span m=''1457430''>the</span>
  <span m=''1457590''>outside</span> <span m=''1457900''>region,</span> <span m=''1458950''>you</span>
  <span m=''1459110''>get</span> <span m=''1459280''>four</span> <span m=''1459775''>45</span>
  <span m=''1460270''>degrees</span> <span m=''1460560''>folds.</span> </p><p><span
  m=''1460870''>This</span> <span m=''1461060''>is</span> <span m=''1461330''>actually</span>
  <span m=''1461710''>how</span> <span m=''1463500''>[? Eichholtz ?]</span> <span
  m=''1464385''>et al</span> <span m=''1465290''>defined</span> <span m=''1465590''>it</span>
  <span m=''1466240''>back</span> <span m=''1466540''>in</span> <span m=''1467510''>''96,</span>
  <span m=''1468740''>and</span> <span m=''1468920''>it''s</span> <span m=''1469050''>a</span>
  <span m=''1469100''>fine</span> <span m=''1469330''>definition.</span> <span m=''1470400''>But</span>
  <span m=''1470550''>you</span> <span m=''1470680''>have</span> <span m=''1470810''>flexibility</span>
  <span m=''1471380''>here</span> <span m=''1471620''>in</span> <span m=''1471680''>your</span>
  <span m=''1471990''>design</span> <span m=''1472320''>process.</span> <span m=''1473780''>They''ll</span>
  <span m=''1473930''>all</span> <span m=''1474140''>work.</span> <span m=''1475880''>And</span>
  <span m=''1476050''>this</span> <span m=''1476190''>would</span> <span m=''1476290''>let</span>
  <span m=''1476420''>you</span> <span m=''1476510''>take</span> <span m=''1476690''>a</span>
  <span m=''1476720''>whole</span> <span m=''1476920''>bunch</span> <span m=''1477120''>of</span>
  <span m=''1477200''>points,</span> <span m=''1477550''>align</span> <span m=''1477910''>them</span>
  <span m=''1478040''>onto</span> <span m=''1478250''>a</span> <span m=''1478290''>common</span>
  <span m=''1478560''>line,</span> <span m=''1478800''>and</span> <span m=''1478930''>nothing</span>
  <span m=''1479230''>else</span> <span m=''1479430''>is</span> <span m=''1479530''>on</span>
  <span m=''1479660''>that</span> <span m=''1479840''>line.</span> <span m=''1481280''>Because</span>
  <span m=''1481500''>these</span> <span m=''1481690''>folds</span> <span m=''1481960''>are</span>
  <span m=''1482030''>going</span> <span m=''1482160''>to</span> <span m=''1482240''>push</span>
  <span m=''1482520''>everything</span> <span m=''1482870''>that''s</span> <span m=''1483100''>surrounding</span>
  <span m=''1483450''>the</span> <span m=''1483530''>point</span> <span m=''1484820''>away</span>
  <span m=''1485180''>from</span> <span m=''1485420''>the</span> <span m=''1485560''>line.</span>
  </p><p><span m=''1487910''>All</span> <span m=''1487980''>right.</span> <span m=''1489270''>Some</span>
  <span m=''1489540''>fun</span> <span m=''1489810''>facts.</span> <span m=''1490820''>Straight</span>
  <span m=''1491080''>skeleton</span> <span m=''1491420''>is</span> <span m=''1491560''>nice</span>
  <span m=''1491840''>and</span> <span m=''1491950''>small.</span> <span m=''1492410''>If</span>
  <span m=''1492510''>you</span> <span m=''1492600''>have</span> <span m=''1493540''>n</span>
  <span m=''1493960''>original</span> <span m=''1495570''>points</span> <span m=''1495870''>and</span>
  <span m=''1495960''>line</span> <span m=''1496170''>segments</span> <span m=''1496740''>in</span>
  <span m=''1496890''>your</span> <span m=''1497490''>desired</span> <span m=''1497880''>cut</span>
  <span m=''1498060''>pattern,</span> <span m=''1499020''>the</span> <span m=''1499130''>straight</span>
  <span m=''1499370''>skeleton</span> <span m=''1499770''>has</span> <span m=''1500080''>a</span>
  <span m=''1500150''>linear</span> <span m=''1500700''>n</span> <span m=''1501170''>number</span>
  <span m=''1501590''>of</span> <span m=''1502500''>line</span> <span m=''1502710''>segments--</span>
  <span m=''1503120''>linear</span> <span m=''1503480''>number</span> <span m=''1503700''>of</span>
  <span m=''1503780''>creases.</span> <span m=''1504570''>So</span> <span m=''1504710''>order</span>
  <span m=''1504960''>n.</span> </p><p><span m=''1511980''>Other</span> <span m=''1512310''>fun</span>
  <span m=''1512600''>facts--</span> <span m=''1513350''>there</span> <span m=''1513520''>is</span>
  <span m=''1513650''>a</span> <span m=''1513850''>one-to-one</span> <span m=''1514380''>correspondence</span>
  <span m=''1515100''>between</span> <span m=''1516280''>the</span> <span m=''1517700''>edges</span>
  <span m=''1518090''>you</span> <span m=''1518230''>want</span> <span m=''1518380''>to</span>
  <span m=''1518450''>cut</span> <span m=''1518660''>along,</span> <span m=''1520100''>like</span>
  <span m=''1521370''>let</span> <span m=''1521600''>me</span> <span m=''1521740''>pick</span>
  <span m=''1521940''>one</span> <span m=''1522110''>over</span> <span m=''1522300''>here</span>
  <span m=''1522550''>maybe.</span> <span m=''1523380''>Like</span> <span m=''1523550''>this--</span>
  <span m=''1524520''>this is</span> <span m=''1524630''>an edge I</span> <span m=''1524950''>want</span>
  <span m=''1525080''>to</span> <span m=''1525130''>cut</span> <span m=''1525290''>along,</span>
  <span m=''1525880''>and</span> <span m=''1526170''>regions</span> <span m=''1527000''>of</span>
  <span m=''1527210''>the</span> <span m=''1527290''>straight</span> <span m=''1527560''>skeleton.</span>
  </p><p><span m=''1528180''>So</span> <span m=''1528330''>here''s</span> <span m=''1528680''>a</span>
  <span m=''1528790''>region.</span> <span m=''1529200''>A</span> <span m=''1529290''>face</span>
  <span m=''1529700''>of</span> <span m=''1529820''>the</span> <span m=''1529890''>straight</span>
  <span m=''1530150''>skeleton.</span> <span m=''1531300''>This</span> <span m=''1531400''>guy.</span>
  <span m=''1531930''>There''s</span> <span m=''1532090''>exactly</span> <span m=''1532550''>one</span>
  <span m=''1533620''>cut edge</span> <span m=''1534100''>inside</span> <span m=''1534550''>of
  that.</span> <span m=''1534870''>That''s</span> <span m=''1535350''>always</span>
  <span m=''1535660''>the</span> <span m=''1535750''>case.</span> <span m=''1536060''>You</span>
  <span m=''1536200''>look</span> <span m=''1536340''>everywhere</span> <span m=''1536730''>here.</span>
  <span m=''1537560''>Every</span> <span m=''1537850''>region</span> <span m=''1538180''>of</span>
  <span m=''1538260''>the</span> <span m=''1538350''>straight</span> <span m=''1538590''>skeleton--</span>
  <span m=''1538950''>it''s</span> <span m=''1539310''>more</span> <span m=''1539520''>obvious</span>
  <span m=''1539780''>if</span> <span m=''1539900''>I</span> <span m=''1539950''>color</span>
  <span m=''1540220''>them</span> <span m=''1540370''>different</span> <span m=''1540630''>colors.</span>
  <span m=''1541480''>There''s</span> <span m=''1541670''>one</span> <span m=''1542370''>cut
  edge</span> <span m=''1542870''>inside.</span> </p><p><span m=''1543720''>And</span>
  <span m=''1543920''>all</span> <span m=''1544300''>of</span> <span m=''1544400''>those</span>
  <span m=''1544670''>guys</span> <span m=''1545350''>that</span> <span m=''1545550''>surround</span>
  <span m=''1547280''>that</span> <span m=''1547550''>cut edge</span> <span m=''1548590''>bisect</span>
  <span m=''1549580''>that</span> <span m=''1549860''>edge</span> <span m=''1551370''>and</span>
  <span m=''1551540''>another</span> <span m=''1551810''>one.</span> <span m=''1552580''>And</span>
  <span m=''1552650''>the</span> <span m=''1552750''>other</span> <span m=''1552910''>one</span>
  <span m=''1553070''>is</span> <span m=''1553160''>the</span> <span m=''1553260''>one</span>
  <span m=''1553390''>on</span> <span m=''1553460''>the</span> <span m=''1553580''>other</span>
  <span m=''1553760''>side.</span> <span m=''1554010''>In</span> <span m=''1554100''>general,
  you</span> <span m=''1554490''>take</span> <span m=''1554700''>one</span> <span
  m=''1554830''>of</span> <span m=''1554940''>the</span> <span m=''1555040''>straight</span>
  <span m=''1555280''>skeleton</span> <span m=''1555650''>edges.</span> <span m=''1556230''>There
  are</span> <span m=''1556370''>two</span> <span m=''1556530''>sides.</span> <span
  m=''1557250''>There''s</span> <span m=''1557400''>two</span> <span m=''1557540''>faces</span>
  <span m=''1558060''>of</span> <span m=''1558150''>the</span> <span m=''1558230''>straight</span>
  <span m=''1558480''>skeleton.</span> <span m=''1559000''>This</span> <span m=''1559060''>one''s</span>
  <span m=''1559320''>crazy and</span> <span m=''1559710''>non</span> <span m=''1559920''>convex.</span>
  <span m=''1560820''>This</span> <span m=''1560970''>one''s</span> <span m=''1561150''>just</span>
  <span m=''1561390''>a</span> <span m=''1561710''>little infinite</span> <span m=''1562210''>triangle</span>
  <span m=''1562630''>down</span> <span m=''1562810''>here,</span> <span m=''1563980''>and</span>
  <span m=''1564150''>that</span> <span m=''1564360''>edge</span> <span m=''1564710''>bisects</span>
  <span m=''1565280''>those</span> <span m=''1565540''>two</span> <span m=''1565770''>cut</span>
  <span m=''1565960''>edges.</span> </p><p><span m=''1566760''>So</span> <span m=''1566860''>it''s</span>
  <span m=''1566960''>very</span> <span m=''1567030''>easy</span> <span m=''1567210''>to</span>
  <span m=''1567300''>walk</span> <span m=''1567580''>around</span> <span m=''1567880''>the</span>
  <span m=''1567960''>structure.</span> <span m=''1568400''>See</span> <span m=''1568560''>what</span>
  <span m=''1568710''>it</span> <span m=''1568810''>bisects.</span> <span m=''1570410''>lots</span>
  <span m=''1570660''>of</span> <span m=''1570700''>things</span> <span m=''1570930''>get</span>
  <span m=''1571070''>bisected.</span> <span m=''1571950''>But,</span> <span m=''1573010''>it''s</span>
  <span m=''1573160''>not</span> <span m=''1573320''>flat</span> <span m=''1573540''>foldable,</span>
  <span m=''1574490''>so</span> <span m=''1574680''>we''re</span> <span m=''1574760''>not</span>
  <span m=''1574940''>done.</span> <span m=''1576360''>And</span> <span m=''1576490''>that''s</span>
  <span m=''1576720''>where</span> <span m=''1576990''>we</span> <span m=''1577100''>need</span>
  <span m=''1578030''>the</span> <span m=''1578120''>perpendiculars.</span> <span
  m=''1580740''>So--</span> </p><p><span m=''1599580''>I''ll</span> <span m=''1599680''>write
  down</span> <span m=''1599840''>the definition,</span> <span m=''1601160''>and</span>
  <span m=''1601330''>maybe</span> <span m=''1601550''>show</span> <span m=''1602450''>the</span>
  <span m=''1602890''>picture</span> <span m=''1603230''>we''re</span> <span m=''1603350''>going</span>
  <span m=''1603610''>for.</span> </p><p></p><p><span m=''1664260''>There''s</span>
  <span m=''1664370''>a</span> <span m=''1664410''>lot</span> <span m=''1664540''>of</span>
  <span m=''1664600''>structures</span> <span m=''1665020''>here.</span> <span m=''1665370''>There</span>
  <span m=''1665540''>is</span> <span m=''1665790''>what</span> <span m=''1665950''>I</span>
  <span m=''1666000''>call</span> <span m=''1666190''>the</span> <span m=''1666310''>cut</span>
  <span m=''1666610''>graph--</span> <span m=''1666980''>the</span> <span m=''1667060''>things</span>
  <span m=''1667260''>we''re</span> <span m=''1667340''>trying</span> <span m=''1667610''>to</span>
  <span m=''1667670''>make.</span> <span m=''1668440''>Then</span> <span m=''1668630''>there''s</span>
  <span m=''1668760''>the</span> <span m=''1668820''>straight</span> <span m=''1669450''>skeleton.</span>
  <span m=''1669805''>You</span> <span m=''1670160''>should</span> <span m=''1670390''>think</span>
  <span m=''1670590''>of</span> <span m=''1670660''>it as</span> <span m=''1670810''>a</span>
  <span m=''1670880''>graph</span> <span m=''1671540''>drawn</span> <span m=''1671610''>on
  a</span> <span m=''1671700''>paper.</span> <span m=''1672520''>It has</span> <span
  m=''1672630''>vertices</span> <span m=''1673060''>of</span> <span m=''1673140''>straight</span>
  <span m=''1673380''>skeleton,</span> <span m=''1673830''>which</span> <span m=''1674000''>is
  called</span> <span m=''1674880''>skeleton</span> <span m=''1675370''>vertices.</span>
  <span m=''1675880''>Regions</span> <span m=''1676220''>of straight</span> <span
  m=''1676480''>skeleton,</span> <span m=''1676940''>which</span> <span m=''1677070''>is</span>
  <span m=''1677150''>called</span> <span m=''1677330''>skeleton</span> <span m=''1677730''>regions.</span>
  <span m=''1678590''>Edges</span> <span m=''1678980''>of</span> <span m=''1679080''>the</span>
  <span m=''1679160''>cut</span> <span m=''1679380''>graph, which</span> <span m=''1679810''>are
  called</span> <span m=''1679990''>cut</span> <span m=''1680170''>edges,</span> <span
  m=''1680540''>and</span> <span m=''1680660''>so</span> <span m=''1680810''>on.</span>
  </p><p><span m=''1681930''>We''re</span> <span m=''1681980''>going</span> <span
  m=''1682070''>to</span> <span m=''1682120''>add</span> <span m=''1682290''>a</span>
  <span m=''1682330''>new</span> <span m=''1682470''>graph,</span> <span m=''1682870''>which</span>
  <span m=''1682940''>is</span> <span m=''1683030''>the</span> <span m=''1683130''>perpendicular</span>
  <span m=''1683800''>graph.</span> <span m=''1684940''>Which</span> <span m=''1685060''>you
  can think</span> <span m=''1685420''>of as</span> <span m=''1685590''>hinges</span>
  <span m=''1686100''>from</span> <span m=''1687440''>tree</span> <span m=''1687650''>method</span>
  <span m=''1687990''>of</span> <span m=''1688100''>origami</span> <span m=''1688410''>design.</span>
  <span m=''1690380''>So</span> <span m=''1690780''>what</span> <span m=''1690970''>is</span>
  <span m=''1691110''>this--</span> <span m=''1691680''>what</span> <span m=''1691790''>does</span>
  <span m=''1691890''>it</span> <span m=''1691970''>mean?</span> <span m=''1693460''>We</span>
  <span m=''1693660''>started</span> <span m=''1694070''>a</span> <span m=''1694130''>straight</span>
  <span m=''1694400''>skeleton</span> <span m=''1694810''>vertex.</span> <span m=''1695540''>Usually</span>
  <span m=''1696200''>there</span> <span m=''1696370''>are</span> <span m=''1696410''>three</span>
  <span m=''1696940''>skeleton</span> <span m=''1697600''>edges</span> <span m=''1697930''>coming</span>
  <span m=''1698170''>together.</span> <span m=''1698550''>Vertex--</span> <span m=''1698900''>sometimes</span>
  <span m=''1699310''>they''re</span> <span m=''1699450''>more</span> <span m=''1699820''>like</span>
  <span m=''1699980''>this</span> <span m=''1700060''>guy.</span> <span m=''1701060''>Four.</span>
  </p><p><span m=''1702100''>And</span> <span m=''1704160''>if</span> <span m=''1704320''>there''s</span>
  <span m=''1704490''>three</span> <span m=''1704780''>edges</span> <span m=''1705030''>coming</span>
  <span m=''1705270''>together,</span> <span m=''1705530''>there are</span> <span
  m=''1705680''>three</span> <span m=''1705960''>skeleton</span> <span m=''1706420''>regions.</span>
  <span m=''1707090''>For</span> <span m=''1707240''>each</span> <span m=''1707420''>one--</span>
  <span m=''1708650''>each</span> <span m=''1708820''>of</span> <span m=''1708880''>those</span>
  <span m=''1709050''>regions--</span> <span m=''1709500''>has</span> <span m=''1709880''>one</span>
  <span m=''1710100''>cut edge</span> <span m=''1710500''>in</span> <span m=''1710600''>it,</span>
  <span m=''1711180''>so</span> <span m=''1711380''>we</span> <span m=''1711490''>try</span>
  <span m=''1711720''>to</span> <span m=''1711850''>walk</span> <span m=''1712470''>perpendicular</span>
  <span m=''1713520''>and</span> <span m=''1713720''>toward</span> <span m=''1714670''>that</span>
  <span m=''1715700''>cut</span> <span m=''1715900''>edge.</span> <span m=''1716360''>So</span>
  <span m=''1716520''>here</span> <span m=''1716750''>I</span> <span m=''1716840''>walk</span>
  <span m=''1717070''>perpendicular.</span> <span m=''1717690''>I</span> <span m=''1717730''>meet</span>
  <span m=''1717940''>at</span> <span m=''1718030''>right</span> <span m=''1718220''>angles</span>
  <span m=''1718570''>here.</span> <span m=''1719130''>I</span> <span m=''1719210''>just</span>
  <span m=''1719360''>go</span> <span m=''1719470''>off</span> <span m=''1719590''>to</span>
  <span m=''1719700''>infinity.</span> </p><p><span m=''1721400''>Here</span> <span
  m=''1722330''>I</span> <span m=''1722490''>walk</span> <span m=''1722880''>perpendicular</span>
  <span m=''1723500''>to</span> <span m=''1723620''>this</span> <span m=''1723800''>cut
  edge,</span> <span m=''1724880''>and</span> <span m=''1725190''>that''s</span> <span
  m=''1725820''>cool,</span> <span m=''1726330''>but</span> <span m=''1726540''>then</span>
  <span m=''1727980''>I</span> <span m=''1728070''>leave</span> <span m=''1728380''>the</span>
  <span m=''1728460''>skeleton</span> <span m=''1728920''>region.</span> <span m=''1729990''>At</span>
  <span m=''1730100''>that</span> <span m=''1730290''>point</span> <span m=''1730740''>I
  enter</span> <span m=''1730820''>a</span> <span m=''1730860''>new</span> <span m=''1731060''>skeleton</span>
  <span m=''1731540''>region,</span> <span m=''1732230''>which</span> <span m=''1732340''>is</span>
  <span m=''1732460''>this</span> <span m=''1732650''>one,</span> <span m=''1733780''>this</span>
  <span m=''1733940''>non-convex</span> <span m=''1734670''>thing.</span> <span m=''1735110''>It</span>
  <span m=''1735250''>contains</span> <span m=''1735620''>one</span> <span m=''1735860''>et</span>
  <span m=''1736080''>edge,</span> <span m=''1736310''>and</span> <span m=''1736670''>when
  I--</span> <span m=''1737250''>where</span> <span m=''1737390''>was</span> <span
  m=''1737580''>I</span> <span m=''1737620''>here?</span> <span m=''1738080''>I entered.</span>
  <span m=''1739000''>Now</span> <span m=''1739140''>I</span> <span m=''1739230''>want</span>
  <span m=''1739440''>to</span> <span m=''1739560''>move</span> <span m=''1739880''>perpendicular</span>
  <span m=''1740660''>to</span> <span m=''1740780''>that</span> <span m=''1741390''>cut</span>
  <span m=''1741580''>edge,</span> <span m=''1741810''>so</span> <span m=''1741930''>that</span>
  <span m=''1742070''>when</span> <span m=''1742230''>I</span> <span m=''1742310''>cross</span>
  <span m=''1742680''>it,</span> <span m=''1743150''>I</span> <span m=''1743280''>cross</span>
  <span m=''1743580''>it</span> <span m=''1743640''>perpendicularly.</span> </p><p><span
  m=''1744720''>Now</span> <span m=''1744870''>I enter</span> <span m=''1745130''>a</span>
  <span m=''1745160''>new</span> <span m=''1745320''>region.</span> <span m=''1745740''>It</span>
  <span m=''1745880''>contains</span> <span m=''1746870''>this</span> <span m=''1747140''>cut</span>
  <span m=''1747340''>edge.</span> <span m=''1747940''>I</span> <span m=''1748110''>move</span>
  <span m=''1748390''>perpendicular</span> <span m=''1749230''>to</span> <span m=''1749510''>it,</span>
  <span m=''1751120''>and</span> <span m=''1751400''>I</span> <span m=''1751450''>don''t</span>
  <span m=''1751630''>actually</span> <span m=''1751910''>cross</span> <span m=''1752230''>it,</span>
  <span m=''1752410''>but</span> <span m=''1752560''>I</span> <span m=''1752650''>enter</span>
  <span m=''1752910''>a</span> <span m=''1752970''>new</span> <span m=''1753070''>region.</span>
  <span m=''1753840''>Now</span> <span m=''1754000''>I''m</span> <span m=''1754160''>in</span>
  <span m=''1754230''>the</span> <span m=''1754310''>region</span> <span m=''1754570''>of</span>
  <span m=''1754630''>this</span> <span m=''1754830''>cut</span> <span m=''1755010''>edge,</span>
  <span m=''1755260''>so</span> <span m=''1755360''>I</span> <span m=''1755430''>move</span>
  <span m=''1755630''>perpendicular</span> <span m=''1756130''>to</span> <span m=''1756200''>that.</span>
  <span m=''1756880''>And</span> <span m=''1756970''>wow,</span> <span m=''1757660''>I</span>
  <span m=''1757770''>hit</span> <span m=''1757940''>another</span> <span m=''1758230''>skeleton</span>
  <span m=''1758610''>vertex.</span> <span m=''1759100''>I</span> <span m=''1759170''>stop.</span>
  <span m=''1760550''>OK</span> <span m=''1760690''>this</span> <span m=''1760860''>example</span>
  <span m=''1761500''>is</span> <span m=''1761780''>because</span> <span m=''1761980''>it''s</span>
  <span m=''1762130''>on</span> <span m=''1762240''>a</span> <span m=''1762290''>triangular</span>
  <span m=''1762690''>grid,</span> <span m=''1762880''>there''s</span> <span m=''1763020''>lots</span>
  <span m=''1763230''>of</span> <span m=''1763300''>degeneracies</span> <span m=''1763960''>like</span>
  <span m=''1764130''>that.</span> <span m=''1764670''>Usually</span> <span m=''1765070''>you''d</span>
  <span m=''1765150''>eventually</span> <span m=''1765520''>go</span> <span m=''1765610''>off</span>
  <span m=''1765730''>to</span> <span m=''1765830''>infinity,</span> <span m=''1766720''>or</span>
  <span m=''1766970''>come</span> <span m=''1767180''>around</span> <span m=''1767460''>to</span>
  <span m=''1767520''>meet</span> <span m=''1767680''>yourself.</span> <span m=''1769030''>Here</span>
  <span m=''1769270''>I</span> <span m=''1769310''>happen</span> <span m=''1769580''>to</span>
  <span m=''1769640''>hit</span> <span m=''1769790''>a</span> <span m=''1769850''>different</span>
  <span m=''1770140''>vertex.</span> </p><p><span m=''1771440''>You</span> <span m=''1771540''>do</span>
  <span m=''1771660''>that</span> <span m=''1771920''>all</span> <span m=''1772160''>the</span>
  <span m=''1772230''>vertices.</span> <span m=''1774250''>All the</span> <span m=''1774510''>skeleton</span>
  <span m=''1774940''>vertices.</span> <span m=''1775540''>Now</span> <span m=''1775590''>there''s</span>
  <span m=''1775780''>some</span> <span m=''1775940''>weird</span> <span m=''1776160''>ones</span>
  <span m=''1777510''>like</span> <span m=''1777890''>this</span> <span m=''1778140''>one.</span>
  <span m=''1779750''>Notice</span> <span m=''1780020''>there</span> <span m=''1780120''>are</span>
  <span m=''1780160''>no</span> <span m=''1781010''>purple</span> <span m=''1781350''>lines</span>
  <span m=''1781710''>coming</span> <span m=''1781980''>out</span> <span m=''1782270''>from</span>
  <span m=''1782480''>here,</span> <span m=''1783420''>and</span> <span m=''1783610''>that''s</span>
  <span m=''1783810''>because</span> <span m=''1784180''>every</span> <span m=''1784560''>region</span>
  <span m=''1784870''>you</span> <span m=''1784990''>try</span> <span m=''1785190''>to</span>
  <span m=''1785260''>enter</span> <span m=''1785750''>you</span> <span m=''1785950''>immediately</span>
  <span m=''1786580''>leave.</span> <span m=''1787910''>So</span> <span m=''1788060''>if</span>
  <span m=''1788160''>I</span> <span m=''1788230''>tried--</span> <span m=''1788750''>there''s</span>
  <span m=''1788970''>four</span> <span m=''1789270''>regions</span> <span m=''1789670''>here.</span>
  <span m=''1790130''>Try</span> <span m=''1790330''>each</span> <span m=''1790480''>one</span>
  <span m=''1790640''>of</span> <span m=''1790720''>them.</span> <span m=''1791220''>Like</span>
  <span m=''1791370''>this</span> <span m=''1791580''>region</span> <span m=''1792330''>has</span>
  <span m=''1792630''>this</span> <span m=''1793350''>cut edge.</span> <span m=''1793800''>If</span>
  <span m=''1793920''>I</span> <span m=''1794000''>try</span> <span m=''1794220''>to</span>
  <span m=''1794320''>go</span> <span m=''1794460''>perpendicular</span> <span m=''1795070''>to</span>
  <span m=''1795250''>it,</span> <span m=''1795400''>I''d</span> <span m=''1795520''>enter</span>
  <span m=''1795790''>a</span> <span m=''1795850''>different</span> <span m=''1796140''>region,</span>
  <span m=''1796500''>so</span> <span m=''1796620''>I</span> <span m=''1796680''>can</span>
  <span m=''1796900''>actually</span> <span m=''1797160''>go</span> <span m=''1797350''>at</span>
  <span m=''1797430''>all.</span> <span m=''1798260''>Like</span> <span m=''1798440''>I</span>
  <span m=''1798830''>move</span> <span m=''1799160''>and</span> <span m=''1799220''>then
  I</span> <span m=''1799430''>instantly</span> <span m=''1799890''>stop.</span> </p><p><span
  m=''1800970''>So</span> <span m=''1801090''>you</span> <span m=''1801160''>could</span>
  <span m=''1801290''>think</span> <span m=''1801460''>of</span> <span m=''1801560''>there</span>
  <span m=''1801690''>being</span> <span m=''1802760''>like</span> <span m=''1802920''>a</span>
  <span m=''1802980''>zero</span> <span m=''1803380''>radius</span> <span m=''1805130''>thing</span>
  <span m=''1805350''>there.</span> <span m=''1805990''>That''s</span> <span m=''1806110''>sort</span>
  <span m=''1806350''>of the</span> <span m=''1806510''>degenerate</span> <span m=''1807020''>case</span>
  <span m=''1807290''>of</span> <span m=''1807400''>a</span> <span m=''1807480''>river</span>
  <span m=''1807760''>being</span> <span m=''1808000''>a</span> <span m=''1808060''>disc</span>
  <span m=''1808640''>Is it</span> <span m=''1808960''>being</span> <span m=''1809250''>a
  circle.</span> <span m=''1810400''>Same</span> <span m=''1810670''>thing</span>
  <span m=''1810830''>going</span> <span m=''1811090''>on.</span> <span m=''1811840''>All</span>
  <span m=''1812140''>of--</span> <span m=''1812410''>in</span> <span m=''1812700''>general</span>
  <span m=''1812980''>when</span> <span m=''1813080''>you</span> <span m=''1813140''>have</span>
  <span m=''1813320''>reflex</span> <span m=''1813700''>vertices</span> <span m=''1814170''>and</span>
  <span m=''1814270''>their</span> <span m=''1814640''>regular</span> <span m=''1814930''>bisectors</span>
  <span m=''1815370''>meeting,</span> <span m=''1815660''>you''re</span> <span m=''1815790''>going</span>
  <span m=''1815890''>to</span> <span m=''1815960''>lose</span> <span m=''1816260''>some</span>
  <span m=''1816470''>perpendiculars</span> <span m=''1817220''>because</span> <span
  m=''1817360''>you</span> <span m=''1817470''>can''t</span> <span m=''1818360''>enter</span>
  <span m=''1818640''>them.</span> <span m=''1820000''>Here''s</span> <span m=''1820230''>another</span>
  <span m=''1820530''>one</span> <span m=''1821270''>where</span> <span m=''1821490''>I
  just</span> <span m=''1821680''>have</span> <span m=''1821830''>one</span> <span
  m=''1822300''>perpendicular</span> <span m=''1822890''>edge</span> <span m=''1823100''>coming</span>
  <span m=''1823380''>out.</span> <span m=''1823550''>This</span> <span m=''1824420''>one</span>
  <span m=''1824590''>I</span> <span m=''1824660''>can</span> <span m=''1824810''>reach,</span>
  <span m=''1825990''>but</span> <span m=''1826040''>if</span> <span m=''1826130''>I</span>
  <span m=''1826220''>tried</span> <span m=''1826580''>to</span> <span m=''1826670''>be</span>
  <span m=''1826830''>perpendicular</span> <span m=''1827370''>to</span> <span m=''1827440''>either</span>
  <span m=''1827640''>of</span> <span m=''1827700''>these,</span> <span m=''1828000''>I</span>
  <span m=''1828170''>enter</span> <span m=''1828500''>the</span> <span m=''1828610''>wrong</span>
  <span m=''1828910''>region.</span> </p><p><span m=''1831320''>That''s</span> <span
  m=''1831530''>the</span> <span m=''1831610''>perpendicular</span> <span m=''1832210''>folds,</span>
  <span m=''1833170''>and</span> <span m=''1833290''>that''s</span> <span m=''1833460''>pretty</span>
  <span m=''1833640''>much</span> <span m=''1833840''>the</span> <span m=''1833920''>crease</span>
  <span m=''1834150''>pattern.</span> <span m=''1834660''>There</span> <span m=''1834780''>are</span>
  <span m=''1834930''>technically</span> <span m=''1835420''>a few</span> <span m=''1835580''>other</span>
  <span m=''1835750''>folds</span> <span m=''1836080''>you</span> <span m=''1836190''>have</span>
  <span m=''1836280''>to</span> <span m=''1836380''>deal</span> <span m=''1836560''>with,</span>
  <span m=''1837175''>but</span> <span m=''1837450''>that</span> <span m=''1837640''>is--</span>
  <span m=''1838160''>if</span> <span m=''1838210''>you</span> <span m=''1838320''>want</span>
  <span m=''1838530''>to</span> <span m=''1838580''>make</span> <span m=''1838810''>something</span>
  <span m=''1839230''>right</span> <span m=''1839430''>now,</span> <span m=''1840550''>just</span>
  <span m=''1840830''>apply</span> <span m=''1841160''>those</span> <span m=''1841340''>two</span>
  <span m=''1841470''>algorithms</span> <span m=''1843090''>and</span> <span m=''1843650''>you</span>
  <span m=''1843780''>get</span> <span m=''1843980''>your</span> <span m=''1844100''>shape.</span>
  <span m=''1844750''>Just</span> <span m=''1845140''>fold</span> <span m=''1845500''>along</span>
  <span m=''1845630''>that</span> <span m=''1845830''>crease</span> <span m=''1845910''>pattern.</span>
  <span m=''1846260''>It</span> <span m=''1846400''>will</span> <span m=''1846580''>be</span>
  <span m=''1847590''>flat</span> <span m=''1847865''>foldable</span> <span m=''1849260''>almost</span>
  <span m=''1849640''>always.</span> </p><p><span m=''1852410''>Why</span> <span m=''1852910''>is</span>
  <span m=''1853070''>it</span> <span m=''1853130''>flat</span> <span m=''1853600''>foldable?</span>
  <span m=''1854430''>So</span> <span m=''1854590''>one</span> <span m=''1854750''>thing</span>
  <span m=''1854910''>we</span> <span m=''1855030''>can</span> <span m=''1855160''>check</span>
  <span m=''1855620''>is</span> <span m=''1855870''>local</span> <span m=''1856190''>flat</span>
  <span m=''1856440''>foldability</span> <span m=''1857500''>at</span> <span m=''1857580''>least</span>
  <span m=''1857810''>satisfies</span> <span m=''1858380''>Kawasaki''s</span> <span
  m=''1859010''>condition</span> <span m=''1861020''>because</span> <span m=''1861720''>at</span>
  <span m=''1861850''>a</span> <span m=''1861920''>typical</span> <span m=''1862380''>vertex</span>
  <span m=''1862860''>you''re</span> <span m=''1862980''>going</span> <span m=''1863080''>to</span>
  <span m=''1863120''>have</span> <span m=''1863350''>three</span> <span m=''1864300''>skeleton</span>
  <span m=''1864810''>edges</span> <span m=''1865060''>coming</span> <span m=''1865310''>together.</span>
  <span m=''1867180''>And</span> <span m=''1867320''>so</span> <span m=''1867410''>there</span>
  <span m=''1867530''>are</span> <span m=''1867570''>three</span> <span m=''1867830''>faces</span>
  <span m=''1868320''>here.</span> <span m=''1868720''>Each</span> <span m=''1868940''>of</span>
  <span m=''1869020''>them</span> <span m=''1869160''>has</span> <span m=''1870210''>a</span>
  <span m=''1870540''>cut</span> <span m=''1870730''>edge</span> <span m=''1871990''>somewhere--</span>
  <span m=''1874490''>probably</span> <span m=''1874510''>draw</span> <span m=''1874610''>this</span>
  <span m=''1874970''>reasonably</span> <span m=''1875400''>well--</span> <span m=''1876010''>and</span>
  <span m=''1876200''>should</span> <span m=''1876380''>have</span> <span m=''1876510''>the</span>
  <span m=''1876600''>property</span> <span m=''1876990''>that</span> <span m=''1877110''>when</span>
  <span m=''1877280''>I</span> <span m=''1877360''>extend</span> <span m=''1877850''>these--</span>
  <span m=''1880140''>didn''t draw that</span> <span m=''1880415''>so well.</span>
  <span m=''1882250''>And</span> <span m=''1882320''>I</span> <span m=''1882370''>extend</span>
  <span m=''1882700''>these--</span> <span m=''1884120''>these are</span> <span m=''1884220''>angular</span>
  <span m=''1884530''>bisectors.</span> </p><p><span m=''1886600''>We</span> <span
  m=''1886750''>know</span> <span m=''1887020''>the</span> <span m=''1887170''>skeleton</span>
  <span m=''1887660''>edges</span> <span m=''1887920''>will</span> <span m=''1888590''>angularly</span>
  <span m=''1889030''>bisect</span> <span m=''1890390''>two</span> <span m=''1890670''>cut</span>
  <span m=''1890880''>edges.</span> <span m=''1891260''>The two</span> <span m=''1891560''>cut</span>
  <span m=''1891750''>edges</span> <span m=''1892100''>that</span> <span m=''1892230''>are</span>
  <span m=''1893370''>defined</span> <span m=''1893620''>by</span> <span m=''1893720''>these</span>
  <span m=''1893920''>guys.</span> <span m=''1894110''>So</span> <span m=''1894380''>I</span>
  <span m=''1894450''>should</span> <span m=''1894640''>get an</span> <span m=''1894780''>angular</span>
  <span m=''1895110''>bisector</span> <span m=''1895590''>here,</span> <span m=''1898370''>and</span>
  <span m=''1898520''>those</span> <span m=''1898690''>meet.</span> <span m=''1899390''>An
  angular</span> <span m=''1899730''>bisector</span> <span m=''1900210''>here.</span>
  <span m=''1902680''>And</span> <span m=''1902740''>then</span> <span m=''1902840''>I</span>
  <span m=''1902910''>also have</span> <span m=''1903180''>perpendicular</span> <span
  m=''1903770''>folds.</span> <span m=''1904120''>So</span> <span m=''1904560''>they</span>
  <span m=''1904730''>may</span> <span m=''1904860''>not</span> <span m=''1905030''>actually</span>
  <span m=''1905400''>meet</span> <span m=''1906640''>this</span> <span m=''1906850''>guy,</span>
  <span m=''1907050''>but</span> <span m=''1907210''>if</span> <span m=''1907340''>they</span>
  <span m=''1907460''>did,</span> <span m=''1908590''>they</span> <span m=''1908740''>certainly</span>
  <span m=''1909050''>meet</span> <span m=''1909210''>the</span> <span m=''1909280''>extension.</span>
  </p><p><span m=''1911311''>Hey,</span> <span m=''1911800''>that''s</span> <span
  m=''1912030''>our</span> <span m=''1912110''>good</span> <span m=''1912310''>friend,</span>
  <span m=''1912730''>the</span> <span m=''1913110''>rabbit</span> <span m=''1913410''>ear.</span>
  <span m=''1913790''>Just</span> <span m=''1913990''>regular</span> <span m=''1914350''>triangle</span>
  <span m=''1914740''>fold.</span> <span m=''1915630''>And</span> <span m=''1915790''>in</span>
  <span m=''1915860''>particular,</span> <span m=''1917110''>you</span> <span m=''1917190''>can</span>
  <span m=''1917330''>see</span> <span m=''1918210''>that</span> <span m=''1919330''>these</span>
  <span m=''1919650''>angles</span> <span m=''1921520''>are</span> <span m=''1921680''>equal.</span>
  <span m=''1923510''>I</span> <span m=''1923880''>call</span> <span m=''1924050''>this</span>
  <span m=''1924220''>three</span> <span m=''1924500''>prime.</span> <span m=''1926880''>It''s</span>
  <span m=''1927050''>like</span> <span m=''1927990''>180</span> <span m=''1928410''>minus</span>
  <span m=''1928810''>that,</span> <span m=''1929240''>I think.</span> <span m=''1930971''>If
  I''m not</span> <span m=''1931390''>mistaken.</span> <span m=''1932930''>And</span>
  <span m=''1933410''>this</span> <span m=''1933600''>is</span> <span m=''1933720''>one</span>
  <span m=''1934020''>prime.</span> <span m=''1935332''>Not</span> <span m=''1935740''>the</span>
  <span m=''1935820''>best</span> <span m=''1936070''>notation.</span> <span m=''1938000''>And</span>
  <span m=''1938450''>these</span> <span m=''1938700''>are</span> <span m=''1938820''>two</span>
  <span m=''1938980''>prime</span> <span m=''1939690''>and</span> <span m=''1940090''>two</span>
  <span m=''1940280''>prime.</span> </p><p><span m=''1941480''>And</span> <span m=''1941630''>so</span>
  <span m=''1941700''>I''ve</span> <span m=''1941820''>got</span> <span m=''1942060''>these</span>
  <span m=''1942290''>nice</span> <span m=''1942630''>angle</span> <span m=''1943000''>pairings.</span>
  <span m=''1944140''>That</span> <span m=''1944310''>means</span> <span m=''1944500''>if</span>
  <span m=''1944590''>I</span> <span m=''1944680''>add</span> <span m=''1944870''>the</span>
  <span m=''1944990''>odd</span> <span m=''1945290''>angles,</span> <span m=''1945700''>I</span>
  <span m=''1945750''>get</span> <span m=''1945910''>the</span> <span m=''1945990''>even</span>
  <span m=''1946190''>angles.</span> <span m=''1946460''>Same</span> <span m=''1946690''>thing.</span>
  <span m=''1947120''>So</span> <span m=''1947470''>I</span> <span m=''1947640''>definitely</span>
  <span m=''1947700''>have</span> <span m=''1947850''>Kawasaki''s</span> <span m=''1948440''>theorem</span>
  <span m=''1949840''>everywhere.</span> <span m=''1950320''>You</span> <span m=''1950450''>could</span>
  <span m=''1950590''>check--</span> <span m=''1950930''>it</span> <span m=''1951140''>works</span>
  <span m=''1951400''>even</span> <span m=''1951670''>when</span> <span m=''1951780''>you</span>
  <span m=''1951850''>have</span> <span m=''1952120''>these</span> <span m=''1952290''>degenerate</span>
  <span m=''1952710''>situations</span> <span m=''1953280''>where</span> <span m=''1955280''>more</span>
  <span m=''1955520''>than</span> <span m=''1955680''>three</span> <span m=''1956020''>skeleton</span>
  <span m=''1956520''>edges</span> <span m=''1956720''>come</span> <span m=''1956870''>together.</span>
  <span m=''1958250''>For</span> <span m=''1958420''>the</span> <span m=''1958530''>same</span>
  <span m=''1958760''>reason.</span> <span m=''1959040''>You</span> <span m=''1959130''>still</span>
  <span m=''1959320''>get</span> <span m=''1959440''>pairing.</span> <span m=''1960190''>Just</span>
  <span m=''1960460''>more</span> <span m=''1960620''>than</span> <span m=''1960740''>three</span>
  <span m=''1960960''>of</span> <span m=''1961050''>them.</span> <span m=''1963770''>All</span>
  <span m=''1963890''>right.</span> </p><p><span m=''1965740''>But</span> <span m=''1965900''>some</span>
  <span m=''1966040''>exciting</span> <span m=''1966420''>things</span> <span m=''1966630''>can</span>
  <span m=''1966760''>happen.</span> <span m=''1968000''>So</span> <span m=''1968100''>I''m</span>
  <span m=''1968170''>going</span> <span m=''1968270''>to</span> <span m=''1968660''>look</span>
  <span m=''1968910''>at</span> <span m=''1969070''>proving</span> <span m=''1969380''>foldability,</span>
  <span m=''1970660''>but</span> <span m=''1971270''>one</span> <span m=''1971620''>exciting</span>
  <span m=''1972010''>thing</span> <span m=''1972100''>that</span> <span m=''1972300''>can</span>
  <span m=''1972370''>happen</span> <span m=''1972710''>is</span> <span m=''1973050''>you</span>
  <span m=''1973180''>get</span> <span m=''1973310''>a</span> <span m=''1973370''>lot</span>
  <span m=''1973840''>of</span> <span m=''1974480''>perpendicular</span> <span m=''1975060''>folds</span>
  <span m=''1975860''>at</span> <span m=''1976070''>a</span> <span m=''1976120''>very</span>
  <span m=''1976570''>few</span> <span m=''1978530''>original</span> <span m=''1978940''>cut</span>
  <span m=''1979150''>lines.</span> <span m=''1979840''>So</span> <span m=''1979910''>here</span>
  <span m=''1980420''>I''m</span> <span m=''1980570''>trying</span> <span m=''1980760''>to</span>
  <span m=''1980820''>make</span> <span m=''1980970''>this</span> <span m=''1981110''>weird</span>
  <span m=''1981420''>pinwheel</span> <span m=''1981800''>shape.</span> <span m=''1982070''>I</span>
  <span m=''1982540''>want</span> <span m=''1982710''>to</span> <span m=''1982790''>cut</span>
  <span m=''1983040''>out</span> <span m=''1983650''>the</span> <span m=''1983750''>bold</span>
  <span m=''1984040''>lines</span> <span m=''1984310''>of</span> <span m=''1984390''>the</span>
  <span m=''1984470''>cut</span> <span m=''1984660''>line.</span> <span m=''1984910''>So</span>
  <span m=''1985050''>I</span> <span m=''1985100''>want</span> <span m=''1985250''>to</span>
  <span m=''1985320''>cut</span> <span m=''1985510''>out</span> <span m=''1985660''>this</span>
  <span m=''1985760''>square,</span> <span m=''1986860''>and</span> <span m=''1987040''>then</span>
  <span m=''1987220''>these</span> <span m=''1987950''>four</span> <span m=''1988280''>squares</span>
  <span m=''1988790''>arranged</span> <span m=''1989170''>in</span> <span m=''1989270''>a</span>
  <span m=''1989330''>pinwheel</span> <span m=''1989680''>pattern</span> <span m=''1990010''>around</span>
  <span m=''1990270''>that</span> <span m=''1990410''>one.</span> <span m=''1990600''>Why</span>
  <span m=''1990810''>you''d</span> <span m=''1990930''>want</span> <span m=''1991090''>to</span>
  <span m=''1991160''>do</span> <span m=''1991280''>that?</span> <span m=''1991610''>I
  don''t</span> <span m=''1991680''>know,</span> <span m=''1991920''>but</span> <span
  m=''1992470''>we''re</span> <span m=''1992600''>mathematicians</span> <span m=''1993280''>so</span>
  <span m=''1993450''>we''re</span> <span m=''1993510''>going</span> <span m=''1993630''>to</span>
  <span m=''1993690''>consider</span> <span m=''1994090''>all</span> <span m=''1994230''>the</span>
  <span m=''1994300''>cases.</span> </p><p><span m=''1995710''>So</span> <span m=''1995960''>the</span>
  <span m=''1996110''>straight</span> <span m=''1996350''>skeleton</span> <span m=''1996810''>is</span>
  <span m=''1997010''>the</span> <span m=''1997360''>thin</span> <span m=''1998180''>black</span>
  <span m=''1998500''>lines,</span> <span m=''1998980''>and</span> <span m=''1999090''>that''s</span>
  <span m=''1999330''>linear</span> <span m=''1999640''>size.</span> <span m=''2000000''>That''s</span>
  <span m=''2000210''>nice,</span> <span m=''2001640''>but</span> <span m=''2001790''>the</span>
  <span m=''2001880''>perpendiculars--</span> <span m=''2003370''>if</span> <span
  m=''2003640''>this</span> <span m=''2004060''>piece of</span> <span m=''2004400''>paper''s</span>
  <span m=''2004700''>infinite,</span> <span m=''2005150''>the number</span> <span
  m=''2005510''>of</span> <span m=''2005580''>perpendiculars</span> <span m=''2006060''>is</span>
  <span m=''2006330''>infinite.</span> <span m=''2007570''>If</span> <span m=''2007700''>you
  have</span> <span m=''2007850''>a</span> <span m=''2007890''>finite</span> <span
  m=''2008280''>piece</span> <span m=''2008460''>of</span> <span m=''2008530''>paper,</span>
  <span m=''2008870''>which</span> <span m=''2009050''>is</span> <span m=''2009180''>what
  you</span> <span m=''2009310''>usually</span> <span m=''2009730''>buy</span> <span
  m=''2009900''>in</span> <span m=''2010000''>the</span> <span m=''2010060''>store,</span>
  <span m=''2011470''>then</span> <span m=''2011800''>it''s a</span> <span m=''2011900''>finite</span>
  <span m=''2012250''>number</span> <span m=''2012470''>of</span> <span m=''2012530''>creases.</span>
  <span m=''2013610''>So</span> <span m=''2013730''>in</span> <span m=''2013800''>any</span>
  <span m=''2013980''>finite</span> <span m=''2014290''>region,</span> <span m=''2014770''>this</span>
  <span m=''2014990''>is</span> <span m=''2015050''>a</span> <span m=''2015130''>finite</span>
  <span m=''2015410''>number</span> <span m=''2015620''>of</span> <span m=''2015680''>creases,</span>
  <span m=''2016090''>but</span> <span m=''2017330''>it''s</span> <span m=''2017460''>a</span>
  <span m=''2017500''>lot</span> <span m=''2017730''>of them.</span> </p><p><span
  m=''2018250''>So</span> <span m=''2018430''>that''s</span> <span m=''2018630''>one</span>
  <span m=''2018840''>sad</span> <span m=''2019140''>thing.</span> <span m=''2019280''>You</span>
  <span m=''2019390''>can''t</span> <span m=''2019720''>bound</span> <span m=''2019990''>the</span>
  <span m=''2020060''>number</span> <span m=''2020280''>of</span> <span m=''2020340''>creases</span>
  <span m=''2020990''>as</span> <span m=''2021210''>a</span> <span m=''2021260''>function</span>
  <span m=''2021730''>of</span> <span m=''2022070''>the</span> <span m=''2022190''>number</span>
  <span m=''2022430''>of</span> <span m=''2022510''>cut</span> <span m=''2022720''>lines.</span>
  <span m=''2023650''>But</span> <span m=''2023760''>I</span> <span m=''2023780''>think</span>
  <span m=''2024110''>that''s</span> <span m=''2024370''>actually</span> <span m=''2024660''>necessary.</span>
  <span m=''2025280''>I</span> <span m=''2025310''>don''t</span> <span m=''2025510''>think</span>
  <span m=''2026040''>it''s</span> <span m=''2026200''>possible</span> <span m=''2026460''>to</span>
  <span m=''2026720''>solve</span> <span m=''2026940''>this</span> <span m=''2027060''>problem</span>
  <span m=''2027490''>while</span> <span m=''2027620''>bounding</span> <span m=''2028120''>the</span>
  <span m=''2028210''>number</span> <span m=''2028410''>of</span> <span m=''2028480''>creases</span>
  <span m=''2028960''>in</span> <span m=''2029080''>terms</span> <span m=''2029340''>of</span>
  <span m=''2029430''>the</span> <span m=''2029500''>number</span> <span m=''2029700''>of</span>
  <span m=''2029770''>cut</span> <span m=''2029950''>lines.</span> <span m=''2030640''>That''s</span>
  <span m=''2031010''>one</span> <span m=''2031180''>of</span> <span m=''2031230''>the</span>
  <span m=''2031310''>open</span> <span m=''2031540''>problems</span> <span m=''2032910''>getting</span>
  <span m=''2033260''>down</span> <span m=''2033650''>on</span> <span m=''2033780''>one</span>
  <span m=''2033950''>of</span> <span m=''2034030''>these</span> <span m=''2035420''>pictures.</span>
  <span m=''2036910''>One</span> <span m=''2037120''>of</span> <span m=''2037350''>these</span>
  <span m=''2037610''>slide--</span> <span m=''2038600''>lecture</span> <span m=''2038850''>notes.</span>
  </p><p><span m=''2040495''>There''s</span> <span m=''2040880''>something</span>
  <span m=''2041290''>else</span> <span m=''2041480''>even</span> <span m=''2041720''>more</span>
  <span m=''2041940''>annoying,</span> <span m=''2042280''>though.</span> <span m=''2042952''>It</span>
  <span m=''2043290''>happens</span> <span m=''2043640''>even</span> <span m=''2043970''>in</span>
  <span m=''2044140''>a</span> <span m=''2044180''>finite</span> <span m=''2044530''>piece</span>
  <span m=''2044720''>of</span> <span m=''2044770''>paper,</span> <span m=''2046300''>and</span>
  <span m=''2047340''>it''s</span> <span m=''2047590''>even</span> <span m=''2047900''>more</span>
  <span m=''2048190''>obscure</span> <span m=''2048620''>why</span> <span m=''2048820''>you''d</span>
  <span m=''2049010''>want</span> <span m=''2049179''>to</span> <span m=''2049219''>make</span>
  <span m=''2049460''>this.</span> <span m=''2049679''>But</span> <span m=''2049810''>the</span>
  <span m=''2049900''>bold</span> <span m=''2050429''>blue</span> <span m=''2050679''>lines</span>
  <span m=''2051780''>are</span> <span m=''2051989''>the</span> <span m=''2052120''>cuts,</span>
  <span m=''2053600''>and</span> <span m=''2053800''>then</span> <span m=''2054050''>the</span>
  <span m=''2054170''>thin</span> <span m=''2054409''>black</span> <span m=''2054710''>lines</span>
  <span m=''2055040''>are the</span> <span m=''2055199''>straight</span> <span m=''2055460''>skeleton.</span>
  <span m=''2057080''>You</span> <span m=''2057190''>could</span> <span m=''2057310''>tell</span>
  <span m=''2057440''>this</span> <span m=''2057540''>spans</span> <span m=''2057860''>many</span>
  <span m=''2058060''>years</span> <span m=''2058320''>because</span> <span m=''2058480''>I</span>
  <span m=''2058530''>keep</span> <span m=''2058730''>changing</span> <span m=''2059159''>notational</span>
  <span m=''2059639''>style,</span> <span m=''2061190''>and</span> <span m=''2061520''>this</span>
  <span m=''2061690''>is</span> <span m=''2061780''>from</span> <span m=''2061920''>the</span>
  <span m=''2062010''>textbook.</span> </p><p><span m=''2064080''>And</span> <span
  m=''2065040''>then</span> <span m=''2065300''>you</span> <span m=''2065429''>get</span>
  <span m=''2065610''>these</span> <span m=''2065790''>perpendicular</span> <span
  m=''2066400''>folds.</span> <span m=''2066730''>So I</span> <span m=''2066790''>haven''t</span>
  <span m=''2067040''>drawn</span> <span m=''2067190''>all</span> <span m=''2067400''>of</span>
  <span m=''2067480''>them</span> <span m=''2068120''>but</span> <span m=''2068290''>these</span>
  <span m=''2068659''>dash</span> <span m=''2068980''>lines,</span> <span m=''2069330''>the</span>
  <span m=''2069610''>light</span> <span m=''2069850''>blue.</span> <span m=''2071409''>And</span>
  <span m=''2072330''>this</span> <span m=''2072570''>example</span> <span m=''2073130''>is</span>
  <span m=''2073239''>set</span> <span m=''2073460''>up</span> <span m=''2073670''>so</span>
  <span m=''2073920''>that--</span> <span m=''2074360''>let me</span> <span m=''2074480''>get</span>
  <span m=''2074630''>this</span> <span m=''2074820''>right.</span> <span m=''2076350''>This</span>
  <span m=''2077550''>width</span> <span m=''2079710''>is</span> <span m=''2080000''>an</span>
  <span m=''2080190''>irrational</span> <span m=''2080739''>multiple</span> <span
  m=''2081870''>of</span> <span m=''2082420''>this</span> <span m=''2082832''>width</span>
  <span m=''2083656''>or this</span> <span m=''2084070''>width.</span> <span m=''2084590''>One</span>
  <span m=''2084719''>of</span> <span m=''2084850''>those.</span> <span m=''2086270''>Things</span>
  <span m=''2086510''>are</span> <span m=''2086690''>irrational,</span> <span m=''2089070''>so</span>
  <span m=''2089290''>they''re</span> <span m=''2089429''>not</span> <span m=''2089690''>very</span>
  <span m=''2089889''>nice</span> <span m=''2090170''>numbers.</span> <span m=''2090630''>And</span>
  <span m=''2091219''>what</span> <span m=''2091370''>I</span> <span m=''2091429''>need</span>
  <span m=''2091620''>to</span> <span m=''2091710''>do</span> <span m=''2091840''>to</span>
  <span m=''2091909''>finish</span> <span m=''2092230''>this</span> <span m=''2092389''>picture</span>
  <span m=''2093130''>is</span> <span m=''2093340''>these</span> <span m=''2093530''>guys</span>
  <span m=''2093770''>go--</span> <span m=''2094810''>they</span> <span m=''2094960''>enter</span>
  <span m=''2095219''>a new</span> <span m=''2095340''>skeleton</span> <span m=''2095739''>region.</span>
  </p><p><span m=''2096030''>They''re</span> <span m=''2096139''>actually</span> <span
  m=''2096360''>going</span> <span m=''2096460''>to</span> <span m=''2096520''>keep</span>
  <span m=''2096699''>going</span> <span m=''2096900''>straight</span> <span m=''2097180''>because</span>
  <span m=''2097330''>there''s</span> <span m=''2097510''>two</span> <span m=''2097730''>cut</span>
  <span m=''2097940''>lines</span> <span m=''2098220''>that are</span> <span m=''2098350''>parallel</span>
  <span m=''2098750''>to</span> <span m=''2098850''>each</span> <span m=''2098990''>other.</span>
  <span m=''2099810''>It''s</span> <span m=''2099910''>going</span> <span m=''2100010''>to</span>
  <span m=''2100070''>go</span> <span m=''2100200''>up</span> <span m=''2100320''>there,</span>
  <span m=''2100980''>and</span> <span m=''2101170''>it''s</span> <span m=''2101260''>going</span>
  <span m=''2101350''>to</span> <span m=''2101400''>cycle</span> <span m=''2101730''>around.</span>
  <span m=''2102020''>Let</span> <span m=''2102120''>me</span> <span m=''2102230''>do</span>
  <span m=''2102490''>one</span> <span m=''2102790''>round.</span> <span m=''2104310''>Who</span>
  <span m=''2104410''>did</span> <span m=''2104620''>I</span> <span m=''2104670''>move?</span>
  <span m=''2105720''>This</span> <span m=''2105970''>guy.</span> </p><p><span m=''2107210''>So</span>
  <span m=''2107410''>this</span> <span m=''2107650''>guy</span> <span m=''2107980''>I</span>
  <span m=''2108090''>just</span> <span m=''2108280''>extended</span> <span m=''2108750''>down.</span>
  <span m=''2109020''>He''s</span> <span m=''2109150''>going</span> <span m=''2109270''>to</span>
  <span m=''2109330''>turn</span> <span m=''2109430''>around,</span> <span m=''2110420''>make</span>
  <span m=''2110570''>180</span> <span m=''2111100''>degree</span> <span m=''2111380''>turn,</span>
  <span m=''2112070''>and</span> <span m=''2112260''>you</span> <span m=''2112380''>can</span>
  <span m=''2112620''>check</span> <span m=''2113090''>each</span> <span m=''2113310''>of</span>
  <span m=''2113390''>these.</span> <span m=''2113860''>Your</span> <span m=''2113940''>setups</span>
  <span m=''2114330''>do</span> <span m=''2114440''>180</span> <span m=''2114810''>degree</span>
  <span m=''2115180''>turn</span> <span m=''2115380''>around</span> <span m=''2115620''>this</span>
  <span m=''2115800''>axis,</span> <span m=''2116740''>around</span> <span m=''2117030''>this</span>
  <span m=''2117230''>axis</span> <span m=''2117640''>on</span> <span m=''2117710''>the</span>
  <span m=''2117790''>bottom,</span> <span m=''2118280''>and on</span> <span m=''2118700''>the</span>
  <span m=''2118740''>top</span> <span m=''2119060''>around</span> <span m=''2119290''>this</span>
  <span m=''2119480''>axis</span> <span m=''2120270''>and</span> <span m=''2120570''>around</span>
  <span m=''2120820''>this</span> <span m=''2121020''>axis.</span> <span m=''2121380''>Depending</span>
  <span m=''2121780''>wherever</span> <span m=''2122110''>you</span> <span m=''2122240''>enter,</span>
  <span m=''2122580''>it''s</span> <span m=''2122680''>like</span> <span m=''2122820''>a</span>
  <span m=''2122900''>racetrack.</span> <span m=''2123550''>Keep</span> <span m=''2123730''>going</span>
  <span m=''2123950''>around</span> <span m=''2124220''>and</span> <span m=''2124300''>around.</span>
  </p><p><span m=''2125190''>And</span> <span m=''2125370''>if</span> <span m=''2125460''>you</span>
  <span m=''2125570''>follow</span> <span m=''2125900''>that</span> <span m=''2126130''>one</span>
  <span m=''2126350''>guy</span> <span m=''2126980''>a</span> <span m=''2127080''>little</span>
  <span m=''2127260''>bit</span> <span m=''2127420''>farther,</span> <span m=''2128460''>it</span>
  <span m=''2128640''>looks</span> <span m=''2128810''>like</span> <span m=''2128950''>that.</span>
  <span m=''2129680''>And</span> <span m=''2129970''>a</span> <span m=''2130020''>little</span>
  <span m=''2130170''>bit</span> <span m=''2130320''>farther,</span> <span m=''2131080''>and
  it</span> <span m=''2131510''>looks like</span> <span m=''2131670''>that.</span>
  <span m=''2132460''>It</span> <span m=''2132600''>never</span> <span m=''2132880''>finishes.</span>
  <span m=''2134720''>So</span> <span m=''2134960''>in fact</span> <span m=''2135190''>you</span>
  <span m=''2135290''>completely</span> <span m=''2136000''>filled</span> <span m=''2136240''>this</span>
  <span m=''2136440''>region</span> <span m=''2136800''>with</span> <span m=''2136960''>creases.</span>
  <span m=''2138180''>It''s</span> <span m=''2138310''>like</span> <span m=''2138450''>a</span>
  <span m=''2138520''>dense</span> <span m=''2139590''>region</span> <span m=''2139840''>of
  creases.</span> <span m=''2140370''>Now</span> <span m=''2140420''>this</span> <span
  m=''2140800''>would</span> <span m=''2140940''>be</span> <span m=''2141080''>a</span>
  <span m=''2141160''>bitch</span> <span m=''2141440''>to fold.</span> <span m=''2144910''>I</span>
  <span m=''2144990''>don''t</span> <span m=''2145270''>recommend</span> <span m=''2145870''>you</span>
  <span m=''2145960''>try</span> <span m=''2146250''>it.</span> </p><p><span m=''2146610''>And</span>
  <span m=''2146820''>this</span> <span m=''2146990''>is</span> <span m=''2147090''>really</span>
  <span m=''2147460''>a</span> <span m=''2147550''>situation</span> <span m=''2148070''>where</span>
  <span m=''2148130''>this</span> <span m=''2148280''>algorithm</span> <span m=''2148660''>fails.</span>
  <span m=''2149900''>The</span> <span m=''2149990''>good</span> <span m=''2150190''>news</span>
  <span m=''2150420''>is</span> <span m=''2151250''>if</span> <span m=''2151390''>I</span>
  <span m=''2151470''>move</span> <span m=''2151760''>any</span> <span m=''2152020''>of</span>
  <span m=''2152070''>these</span> <span m=''2152250''>vertices--</span> <span m=''2153520''>the</span>
  <span m=''2153720''>cut vertices</span> <span m=''2154390''>the</span> <span m=''2154460''>tiniest</span>
  <span m=''2154970''>amount--</span> <span m=''2155940''>this</span> <span m=''2156100''>will</span>
  <span m=''2156210''>disappear.</span> <span m=''2157250''>I</span> <span m=''2157330''>really</span>
  <span m=''2157730''>had</span> <span m=''2158000''>to</span> <span m=''2158290''>be</span>
  <span m=''2158440''>very</span> <span m=''2158900''>careful</span> <span m=''2159290''>and</span>
  <span m=''2159360''>get</span> <span m=''2159480''>lots</span> <span m=''2159710''>of</span>
  <span m=''2159790''>degeneracy</span> <span m=''2160520''>for</span> <span m=''2160670''>this</span>
  <span m=''2160980''>to</span> <span m=''2161120''>happen.</span> </p><p><span m=''2164340''>We</span>
  <span m=''2164450''>don''t</span> <span m=''2164600''>actually</span> <span m=''2164800''>know</span>
  <span m=''2164900''>how</span> <span m=''2164990''>to</span> <span m=''2165060''>prove</span>
  <span m=''2165340''>that.</span> <span m=''2165980''>It''s</span> <span m=''2166140''>conjecture</span>
  <span m=''2167390''>that</span> <span m=''2167570''>if</span> <span m=''2167680''>you</span>
  <span m=''2167780''>take</span> <span m=''2168190''>any</span> <span m=''2169700''>cuts--</span>
  <span m=''2170070''>any</span> <span m=''2170260''>graph</span> <span m=''2170520''>of</span>
  <span m=''2170610''>cuts</span> <span m=''2170830''>you</span> <span m=''2170930''>want</span>
  <span m=''2171060''>to</span> <span m=''2171110''>make,</span> <span m=''2171930''>and</span>
  <span m=''2172240''>you</span> <span m=''2172500''>perturb</span> <span m=''2172990''>the</span>
  <span m=''2173060''>vertices</span> <span m=''2173530''>in</span> <span m=''2173600''>a</span>
  <span m=''2173700''>tiny</span> <span m=''2174130''>epsilon</span> <span m=''2175170''>disc</span>
  <span m=''2176110''>then</span> <span m=''2176350''>the</span> <span m=''2176430''>resulting</span>
  <span m=''2176820''>thing</span> <span m=''2176990''>will</span> <span m=''2177100''>not</span>
  <span m=''2177320''>have</span> <span m=''2177520''>this</span> <span m=''2177720''>density</span>
  <span m=''2178070''>behavior.</span> <span m=''2179070''>I''m</span> <span m=''2179540''>totally</span>
  <span m=''2179860''>sure</span> <span m=''2180040''>it''s</span> <span m=''2180140''>true,</span>
  <span m=''2180630''>but</span> <span m=''2180800''>we</span> <span m=''2180890''>don''t</span>
  <span m=''2181020''>have</span> <span m=''2181120''>the</span> <span m=''2181190''>proof.</span>
  </p><p><span m=''2182690''>So</span> <span m=''2182870''>that''s</span> <span m=''2183460''>life.</span>
  <span m=''2183960''>This</span> <span m=''2184170''>is</span> <span m=''2184280''>why</span>
  <span m=''2184410''>I</span> <span m=''2184470''>said</span> <span m=''2185230''>skeleton</span>
  <span m=''2185720''>method</span> <span m=''2186020''>works</span> <span m=''2186270''>almost</span>
  <span m=''2186620''>always.</span> <span m=''2188420''>There are these</span> <span
  m=''2189170''>annoying</span> <span m=''2189610''>situations</span> <span m=''2191170''>where</span>
  <span m=''2191840''>it</span> <span m=''2191900''>doesn''t</span> <span m=''2192110''>really</span>
  <span m=''2192270''>give</span> <span m=''2192410''>your</span> <span m=''2192550''>crease</span>
  <span m=''2192780''>pattern.</span> <span m=''2194090''>So if you</span> <span m=''2194220''>feel</span>
  <span m=''2194430''>like</span> <span m=''2194740''>unless</span> <span m=''2194970''>you</span>
  <span m=''2195680''>somehow</span> <span m=''2196130''>think</span> <span m=''2196350''>this</span>
  <span m=''2196510''>is</span> <span m=''2196640''>legitimate</span> <span m=''2196925''>to</span>
  <span m=''2197210''>make</span> <span m=''2197570''>infinitely</span> <span m=''2198010''>many</span>
  <span m=''2198230''>creases.</span> <span m=''2199240''>I</span> <span m=''2199430''>don''t</span>
  <span m=''2199590''>think</span> <span m=''2199740''>so.</span> </p><p><span m=''2204120''>All</span>
  <span m=''2204240''>right,</span> <span m=''2207240''>let</span> <span m=''2207360''>me</span>
  <span m=''2207480''>tell</span> <span m=''2207670''>you</span> <span m=''2207890''>a</span>
  <span m=''2207930''>few</span> <span m=''2208110''>more</span> <span m=''2208470''>things</span>
  <span m=''2208780''>to</span> <span m=''2208900''>make</span> <span m=''2209050''>this</span>
  <span m=''2209210''>practical</span> <span m=''2209700''>for</span> <span m=''2209930''>you.</span>
  <span m=''2211270''>You want</span> <span m=''2211470''>to--</span> <span m=''2211660''>what</span>
  <span m=''2211840''>you</span> <span m=''2211960''>really</span> <span m=''2212260''>want</span>
  <span m=''2212710''>is</span> <span m=''2213010''>a</span> <span m=''2213070''>mountain</span>
  <span m=''2213370''>valley</span> <span m=''2213710''>assignment.</span> <span m=''2214110''>Before</span>
  <span m=''2214460''>I</span> <span m=''2214490''>showed</span> <span m=''2214740''>you</span>
  <span m=''2214880''>lots</span> <span m=''2215090''>of</span> <span m=''2215180''>perpendicular</span>
  <span m=''2215545''>and</span> <span m=''2216300''>skeleton</span> <span m=''2216860''>edges,</span>
  <span m=''2218010''>and</span> <span m=''2219470''>basically</span> <span m=''2220020''>the</span>
  <span m=''2220130''>way</span> <span m=''2220250''>it</span> <span m=''2220330''>works</span>
  <span m=''2220820''>is</span> <span m=''2222290''>if</span> <span m=''2222430''>you</span>
  <span m=''2222570''>look</span> <span m=''2222790''>at</span> <span m=''2223090''>any</span>
  <span m=''2223350''>skeleton</span> <span m=''2223900''>edge</span> <span m=''2224840''>like</span>
  <span m=''2224960''>this</span> <span m=''2225150''>one,</span> <span m=''2226380''>it''s</span>
  <span m=''2226600''>bisecting</span> <span m=''2227260''>in</span> <span m=''2227320''>this</span>
  <span m=''2227500''>case</span> <span m=''2227830''>a</span> <span m=''2227900''>convex</span>
  <span m=''2228440''>angle.</span> <span m=''2229350''>So</span> <span m=''2229530''>I</span>
  <span m=''2229620''>make</span> <span m=''2229830''>it</span> <span m=''2229910''>a</span>
  <span m=''2229950''>mountain.</span> <span m=''2231050''>Here,</span> <span m=''2231320''>red</span>
  <span m=''2231520''>is</span> <span m=''2231620''>mountain,</span> <span m=''2232360''>blue
  is</span> <span m=''2232670''>valley.</span> <span m=''2233760''>Dot dashes</span>
  <span m=''2234310''>mountain,</span> <span m=''2234630''>dash is</span> <span m=''2235040''>valley.</span>
  <span m=''2235680''>That is the</span> <span m=''2236060''>standard.</span> </p><p><span
  m=''2237030''>Whenever</span> <span m=''2237440''>I''m</span> <span m=''2237580''>bisecting</span>
  <span m=''2238160''>a</span> <span m=''2238260''>reflex</span> <span m=''2238780''>angle,</span>
  <span m=''2239590''>then</span> <span m=''2239830''>I</span> <span m=''2239910''>make</span>
  <span m=''2240350''>the</span> <span m=''2241930''>skeleton</span> <span m=''2242440''>edge
  a</span> <span m=''2242650''>valley.</span> <span m=''2244350''>And</span> <span
  m=''2244590''>that''s</span> <span m=''2245820''>basically</span> <span m=''2246270''>true.</span>
  <span m=''2247310''>Convex</span> <span m=''2247700''>angles,</span> <span m=''2248110''>mountains,</span>
  <span m=''2248860''>reflex</span> <span m=''2249210''>angles,</span> <span m=''2249490''>valleys.</span>
  <span m=''2249780''>That''s</span> <span m=''2249960''>for</span> <span m=''2250030''>the</span>
  <span m=''2250130''>straight</span> <span m=''2250420''>skeleton</span> <span m=''2250820''>edges.</span>
  <span m=''2251670''>Yeah.</span> </p><p><span m=''2257740''>Like</span> <span m=''2258000''>this</span>
  <span m=''2258330''>fold,</span> <span m=''2258635''>or</span> <span m=''2259760''>this</span>
  <span m=''2259980''>one?</span> <span m=''2262060''>Oh,</span> <span m=''2262170''>this</span>
  <span m=''2262370''>guy.</span> <span m=''2263340''>All</span> <span m=''2263410''>right,</span>
  <span m=''2263700''>this</span> <span m=''2263880''>is</span> <span m=''2264020''>a</span>
  <span m=''2264080''>bit</span> <span m=''2264230''>of</span> <span m=''2264320''>a</span>
  <span m=''2264380''>special</span> <span m=''2264720''>case.</span> <span m=''2264970''>Here</span>
  <span m=''2265180''>I''m</span> <span m=''2265260''>really</span> <span m=''2265450''>bisecting</span>
  <span m=''2265990''>an</span> <span m=''2266060''>angle</span> <span m=''2266310''>of</span>
  <span m=''2266420''>zero.</span> <span m=''2268380''>To</span> <span m=''2268510''>extend</span>
  <span m=''2268840''>these</span> <span m=''2269010''>guys</span> <span m=''2269250''>out,</span>
  <span m=''2269400''>they</span> <span m=''2269480''>need</span> <span m=''2269700''>an</span>
  <span m=''2269800''>infinite,</span> <span m=''2270350''>and</span> <span m=''2270420''>they</span>
  <span m=''2270510''>form</span> <span m=''2270740''>a</span> <span m=''2270780''>zero</span>
  <span m=''2271160''>angle</span> <span m=''2271370''>because</span> <span m=''2271570''>they''re</span>
  <span m=''2271680''>parallel.</span> <span m=''2272500''>And I call</span> <span
  m=''2272930''>zero</span> <span m=''2273240''>a</span> <span m=''2273320''>convex</span>
  <span m=''2273800''>angle,</span> <span m=''2275210''>but</span> <span m=''2275460''>I</span>
  <span m=''2275550''>just</span> <span m=''2275710''>defined</span> <span m=''2276000''>it</span>
  <span m=''2276090''>that</span> <span m=''2276280''>way,</span> <span m=''2276980''>and</span>
  <span m=''2277090''>so</span> <span m=''2277350''>this</span> <span m=''2277590''>is</span>
  <span m=''2277720''>a</span> <span m=''2277770''>mountain.</span> </p><p><span m=''2278850''>Whereas</span>
  <span m=''2279510''>this</span> <span m=''2279740''>guy</span> <span m=''2282210''>bisecting</span>
  <span m=''2283660''>is</span> <span m=''2283840''>barely</span> <span m=''2284230''>convex.</span>
  <span m=''2285170''>Is that</span> <span m=''2285440''>really a</span> <span m=''2285720''>mountain?</span>
  <span m=''2288140''>No,</span> <span m=''2288960''>that''s</span> <span m=''2289140''>a</span>
  <span m=''2289190''>typo.</span> <span m=''2289790''>Good.</span> <span m=''2290460''>This</span>
  <span m=''2290650''>one</span> <span m=''2290800''>should</span> <span m=''2290990''>be</span>
  <span m=''2291120''>a</span> <span m=''2291160''>valley.</span> <span m=''2292390''>Pretty
  sure.</span> <span m=''2294940''>Yeah,</span> <span m=''2295640''>should</span>
  <span m=''2295870''>be a</span> <span m=''2296030''>valley--</span> <span m=''2296430''>wow,</span>
  <span m=''2296660''>this</span> <span m=''2296840''>is</span> <span m=''2297080''>a</span>
  <span m=''2297160''>weird</span> <span m=''2297540''>crease</span> <span m=''2297800''>pattern.</span>
  </p><p><span m=''2300610''>That''s</span> <span m=''2300790''>not</span> <span m=''2300960''>a</span>
  <span m=''2301030''>straight</span> <span m=''2301320''>skeleton</span> <span m=''2301790''>there.</span>
  <span m=''2302250''>Never</span> <span m=''2302560''>mind</span> <span m=''2302870''>this</span>
  <span m=''2303030''>picture--</span> <span m=''2303530''>I</span> <span m=''2303630''>knew</span>
  <span m=''2303740''>there was</span> <span m=''2303920''>always a</span> <span m=''2304180''>bug.</span>
  <span m=''2305350''>I</span> <span m=''2305430''>think</span> <span m=''2305730''>there''s</span>
  <span m=''2306600''>a</span> <span m=''2306670''>typo</span> <span m=''2307030''>in</span>
  <span m=''2307120''>the</span> <span m=''2307180''>book</span> <span m=''2308360''>as</span>
  <span m=''2308470''>we</span> <span m=''2308780''>say.</span> </p><p><span m=''2315390''>How</span>
  <span m=''2315700''>did</span> <span m=''2316010''>I</span> <span m=''2316190''>make
  the</span> <span m=''2316390''>initial</span> <span m=''2316670''>pattern</span>
  <span m=''2316950''>of the</span> <span m=''2317050''>turtle?</span> <span m=''2317340''>I</span>
  <span m=''2317440''>just</span> <span m=''2318100''>drew</span> <span m=''2318280''>something</span>
  <span m=''2318560''>that looked</span> <span m=''2318730''>like</span> <span m=''2318850''>a</span>
  <span m=''2318920''>turtle.</span> <span m=''2320140''>Anything.</span> <span m=''2322110''>I</span>
  <span m=''2322270''>happened</span> <span m=''2322590''>to</span> <span m=''2322670''>draw</span>
  <span m=''2322820''>this</span> <span m=''2323000''>on</span> <span m=''2323100''>a</span>
  <span m=''2323160''>grid,</span> <span m=''2323410''>but</span> <span m=''2323540''>there''s</span>
  <span m=''2323700''>no</span> <span m=''2323800''>reason</span> <span m=''2324030''>I</span>
  <span m=''2324080''>had</span> <span m=''2324300''>to.</span> </p><p><span m=''2340840''>I</span>
  <span m=''2340980''>designed</span> <span m=''2341380''>them.</span> <span m=''2341920''>So</span>
  <span m=''2342160''>in</span> <span m=''2343670''>this</span> <span m=''2343840''>example,</span>
  <span m=''2344310''>I</span> <span m=''2344430''>designed</span> <span m=''2344910''>the</span>
  <span m=''2344990''>ratios</span> <span m=''2345350''>to</span> <span m=''2345430''>be</span>
  <span m=''2345560''>really</span> <span m=''2345780''>nasty.</span> <span m=''2346650''>Like</span>
  <span m=''2347180''>root</span> <span m=''2347470''>2</span> <span m=''2347640''>over</span>
  <span m=''2347820''>10</span> <span m=''2348070''>ratio</span> <span m=''2348520''>or</span>
  <span m=''2348640''>something.</span> <span m=''2352980''>The</span> <span m=''2353070''>whole</span>
  <span m=''2353280''>thing</span> <span m=''2353490''>will--</span> <span m=''2353710''>if</span>
  <span m=''2353890''>I</span> <span m=''2353980''>perturb</span> <span m=''2354390''>these</span>
  <span m=''2354550''>vertices</span> <span m=''2354960''>at all,</span> <span m=''2355030''>the</span>
  <span m=''2355290''>whole</span> <span m=''2355520''>thing</span> <span m=''2355710''>will</span>
  <span m=''2355810''>fall</span> <span m=''2356050''>apart.</span> <span m=''2356410''>I</span>
  <span m=''2356480''>won''t</span> <span m=''2356700''>get</span> <span m=''2356820''>these</span>
  <span m=''2356980''>180</span> <span m=''2357450''>degree</span> <span m=''2357680''>turns.</span>
  <span m=''2358050''>Things</span> <span m=''2358250''>will</span> <span m=''2358380''>end</span>
  <span m=''2358510''>up</span> <span m=''2358610''>going</span> <span m=''2358820''>off</span>
  <span m=''2358910''>to</span> <span m=''2359010''>infinity.</span> </p><p><span
  m=''2360330''>The</span> <span m=''2360520''>hard</span> <span m=''2360770''>part</span>
  <span m=''2360940''>here</span> <span m=''2361080''>is</span> <span m=''2361180''>actually--</span>
  <span m=''2362010''>rational</span> <span m=''2362910''>ratios</span> <span m=''2363490''>are
  quite</span> <span m=''2363690''>common.</span> <span m=''2364710''>What''s</span>
  <span m=''2364920''>uncommon</span> <span m=''2365740''>in</span> <span m=''2365910''>this</span>
  <span m=''2366100''>picture</span> <span m=''2366740''>is</span> <span m=''2366940''>that</span>
  <span m=''2367090''>this</span> <span m=''2367240''>thing</span> <span m=''2367380''>is</span>
  <span m=''2367490''>closed</span> <span m=''2367930''>up,</span> <span m=''2368210''>and</span>
  <span m=''2368330''>you</span> <span m=''2368420''>never</span> <span m=''2368700''>escape.</span>
  <span m=''2369980''>Almost</span> <span m=''2370350''>always,</span> <span m=''2370750''>there''ll</span>
  <span m=''2370870''>be</span> <span m=''2370990''>a</span> <span m=''2371050''>little</span>
  <span m=''2371330''>gap</span> <span m=''2372380''>and</span> <span m=''2372600''>you''ll</span>
  <span m=''2372880''>eventually</span> <span m=''2373580''>reach</span> <span m=''2373790''>the</span>
  <span m=''2373870''>gap</span> <span m=''2374120''>and</span> <span m=''2374180''>then</span>
  <span m=''2374300''>go</span> <span m=''2374390''>off</span> <span m=''2374510''>to</span>
  <span m=''2374610''>infinity.</span> <span m=''2375470''>So</span> <span m=''2375490''>that''s</span>
  <span m=''2375670''>what</span> <span m=''2375770''>happens</span> <span m=''2376120''>in</span>
  <span m=''2376890''>a</span> <span m=''2376980''>typical</span> <span m=''2377390''>case.</span>
  </p><p><span m=''2383100''>So</span> <span m=''2383180''>if</span> <span m=''2383320''>you</span>
  <span m=''2383430''>drew</span> <span m=''2383610''>a</span> <span m=''2383660''>picture</span>
  <span m=''2383940''>on</span> <span m=''2384010''>the</span> <span m=''2384090''>grid</span>
  <span m=''2384290''>this</span> <span m=''2384430''>would</span> <span m=''2384530''>never</span>
  <span m=''2384750''>happen.</span> <span m=''2385110''>That</span> <span m=''2385420''>you
  can</span> <span m=''2385550''>prove.</span> <span m=''2386570''>Yeah.</span> <span
  m=''2388670''>Square</span> <span m=''2389000''>grid.</span> <span m=''2390400''>Probably</span>
  <span m=''2390850''>also the</span> <span m=''2391100''>triangular</span> <span
  m=''2391530''>grid.</span> <span m=''2391780''>You</span> <span m=''2391860''>need</span>
  <span m=''2392080''>to</span> <span m=''2392130''>be</span> <span m=''2392220''>a</span>
  <span m=''2392270''>little</span> <span m=''2392430''>careful</span> <span m=''2392740''>because</span>
  <span m=''2392900''>you</span> <span m=''2393020''>want</span> <span m=''2393340''>all</span>
  <span m=''2393520''>these</span> <span m=''2393680''>constructions</span> <span
  m=''2394330''>to</span> <span m=''2394500''>stay</span> <span m=''2394770''>on</span>
  <span m=''2394870''>the</span> <span m=''2394950''>grid,</span> <span m=''2395850''>but</span>
  <span m=''2396060''>I</span> <span m=''2396170''>think</span> <span m=''2396430''>something</span>
  <span m=''2396710''>like</span> <span m=''2396860''>that</span> <span m=''2397040''>is</span>
  <span m=''2397200''>true.</span> </p><p><span m=''2398310''>OK,</span> <span m=''2400480''>let''s</span>
  <span m=''2400720''>move</span> <span m=''2400980''>on</span> <span m=''2401400''>to</span>
  <span m=''2403150''>how</span> <span m=''2403420''>we</span> <span m=''2403610''>construct</span>
  <span m=''2404130''>a</span> <span m=''2404180''>folded</span> <span m=''2404570''>state.</span>
  <span m=''2404980''>When</span> <span m=''2405160''>this</span> <span m=''2405340''>algorithm</span>
  <span m=''2405750''>works,</span> <span m=''2406110''>when</span> <span m=''2406240''>it</span>
  <span m=''2406310''>gives</span> <span m=''2406500''>a</span> <span m=''2406550''>valid</span>
  <span m=''2406820''>crease</span> <span m=''2407070''>pattern,</span> <span m=''2408990''>you</span>
  <span m=''2409260''>know it''s</span> <span m=''2409530''>locally</span> <span m=''2409950''>flat</span>
  <span m=''2410210''>foldable</span> <span m=''2410560''>because</span> <span m=''2410890''>it
  satisfies</span> <span m=''2411220''>Kawasaki,</span> <span m=''2411850''>but</span>
  <span m=''2412030''>how</span> <span m=''2412200''>do</span> <span m=''2412290''>we</span>
  <span m=''2412430''>actually</span> <span m=''2412690''>know</span> <span m=''2412870''>that
  it</span> <span m=''2413050''>globally</span> <span m=''2413450''>folds</span> <span
  m=''2413700''>flat?</span> <span m=''2414230''>To</span> <span m=''2414360''>do</span>
  <span m=''2414460''>that,</span> <span m=''2414670''>you</span> <span m=''2414760''>have</span>
  <span m=''2414890''>to</span> <span m=''2415000''>describe</span> <span m=''2415380''>what</span>
  <span m=''2415550''>it</span> <span m=''2415640''>looks</span> <span m=''2415860''>like</span>
  <span m=''2416060''>after</span> <span m=''2416350''>it''s</span> <span m=''2416490''>folded.</span>
  </p><p><span m=''2417680''>And</span> <span m=''2418786''>the</span> <span m=''2419160''>idea</span>
  <span m=''2419640''>here</span> <span m=''2420100''>is</span> <span m=''2420390''>to</span>
  <span m=''2420550''>look</span> <span m=''2420780''>at</span> <span m=''2421520''>what</span>
  <span m=''2421660''>we</span> <span m=''2421800''>call</span> <span m=''2422210''>corridors</span>
  <span m=''2422950''>but</span> <span m=''2423070''>are</span> <span m=''2423140''>essentially</span>
  <span m=''2424030''>discrete</span> <span m=''2424410''>versions</span> <span m=''2424780''>of</span>
  <span m=''2424900''>rivers</span> <span m=''2425510''>from</span> <span m=''2425740''>tree</span>
  <span m=''2425950''>theory.</span> <span m=''2427030''>So</span> <span m=''2427130''>you</span>
  <span m=''2427260''>have</span> <span m=''2428330''>these</span> <span m=''2428540''>constant</span>
  <span m=''2429090''>width</span> <span m=''2429610''>strips</span> <span m=''2430100''>that</span>
  <span m=''2430220''>turn</span> <span m=''2430740''>at</span> <span m=''2431030''>skeleton</span>
  <span m=''2431500''>edges,</span> <span m=''2432770''>and</span> <span m=''2433410''>they</span>
  <span m=''2433740''>could</span> <span m=''2434300''>go</span> <span m=''2434450''>off</span>
  <span m=''2434630''>to</span> <span m=''2434730''>infinity</span> <span m=''2435300''>on</span>
  <span m=''2435400''>both</span> <span m=''2435590''>sides.</span> <span m=''2436030''>In</span>
  <span m=''2436150''>general</span> <span m=''2436590''>they</span> <span m=''2436720''>could</span>
  <span m=''2437020''>loop</span> <span m=''2437240''>around</span> <span m=''2437790''>and</span>
  <span m=''2437920''>meet</span> <span m=''2438100''>themselves</span> <span m=''2438850''>again,</span>
  <span m=''2440580''>but</span> <span m=''2440770''>in</span> <span m=''2440860''>this</span>
  <span m=''2441040''>case</span> <span m=''2441270''>they</span> <span m=''2441340''>actually</span>
  <span m=''2441600''>all</span> <span m=''2441790''>go</span> <span m=''2441930''>to</span>
  <span m=''2442020''>infinity.</span> </p><p><span m=''2444410''>And</span> <span
  m=''2444460''>if</span> <span m=''2444550''>you</span> <span m=''2444690''>look</span>
  <span m=''2444910''>at</span> <span m=''2445020''>one</span> <span m=''2445330''>of</span>
  <span m=''2445430''>those</span> <span m=''2445660''>strips--</span> <span m=''2446780''>you</span>
  <span m=''2446850''>could</span> <span m=''2446980''>actually</span> <span m=''2447310''>just</span>
  <span m=''2447730''>cut</span> <span m=''2447980''>this</span> <span m=''2448170''>out</span>
  <span m=''2449450''>of</span> <span m=''2449790''>your</span> <span m=''2450250''>textbook.</span>
  <span m=''2451260''>Just</span> <span m=''2451900''>slice</span> <span m=''2452320''>it</span>
  <span m=''2452400''>up</span> <span m=''2453000''>and</span> <span m=''2454000''>look</span>
  <span m=''2454240''>at</span> <span m=''2454300''>how</span> <span m=''2454490''>that''s</span>
  <span m=''2454650''>folding.</span> <span m=''2455290''>Well,</span> <span m=''2455700''>it</span>
  <span m=''2455780''>meets</span> <span m=''2456910''>a</span> <span m=''2456990''>skeleton</span>
  <span m=''2457490''>edge,</span> <span m=''2458500''>and</span> <span m=''2458710''>then</span>
  <span m=''2458930''>maybe</span> <span m=''2459180''>it meets</span> <span m=''2459310''>a</span>
  <span m=''2459420''>cut</span> <span m=''2459630''>edge.</span> <span m=''2459820''>Usually</span>
  <span m=''2460190''>you don''t</span> <span m=''2460410''>fold</span> <span m=''2460640''>those.</span>
  <span m=''2461120''>Then it meets</span> <span m=''2461520''>another</span> <span
  m=''2461740''>skeleton</span> <span m=''2462180''>edge.</span> <span m=''2462430''>It
  just</span> <span m=''2462630''>meets</span> <span m=''2463330''>edges</span> <span
  m=''2463740''>one</span> <span m=''2463960''>at</span> <span m=''2464020''>a</span>
  <span m=''2464130''>time.</span> <span m=''2464500''>It''s</span> <span m=''2464630''>never</span>
  <span m=''2464920''>complicated</span> <span m=''2466440''>because</span> <span
  m=''2466650''>we</span> <span m=''2466920''>divided</span> <span m=''2467450''>along</span>
  <span m=''2467690''>all</span> <span m=''2467810''>these</span> <span m=''2467980''>perpendicular</span>
  <span m=''2468500''>folds.</span> <span m=''2468820''>You</span> <span m=''2468950''>really</span>
  <span m=''2469210''>only</span> <span m=''2469400''>meet</span> <span m=''2469570''>one</span>
  <span m=''2469910''>edge</span> <span m=''2470150''>at</span> <span m=''2470190''>a</span>
  <span m=''2470300''>time.</span> </p><p><span m=''2472710''>Which</span> <span m=''2472920''>is</span>
  <span m=''2473210''>good.</span> <span m=''2474960''>In</span> <span m=''2475100''>fact,</span>
  <span m=''2476140''>if</span> <span m=''2476320''>you</span> <span m=''2476440''>look</span>
  <span m=''2476630''>at</span> <span m=''2476710''>one</span> <span m=''2476890''>of</span>
  <span m=''2476980''>these</span> <span m=''2477710''>skeleton</span> <span m=''2478150''>edges</span>
  <span m=''2479290''>it''s</span> <span m=''2479630''>creased</span> <span m=''2479940''>along,</span>
  <span m=''2481400''>normally</span> <span m=''2481850''>you</span> <span m=''2481940''>think</span>
  <span m=''2482160''>of</span> <span m=''2482240''>that</span> <span m=''2482400''>as</span>
  <span m=''2482500''>an</span> <span m=''2482570''>angular</span> <span m=''2482860''>bisector</span>
  <span m=''2483490''>of</span> <span m=''2484400''>these</span> <span m=''2484770''>two</span>
  <span m=''2484980''>cut</span> <span m=''2485220''>edges,</span> <span m=''2486560''>but</span>
  <span m=''2486690''>you</span> <span m=''2486810''>can</span> <span m=''2486970''>also</span>
  <span m=''2487430''>think</span> <span m=''2487700''>of</span> <span m=''2487810''>it</span>
  <span m=''2488020''>as</span> <span m=''2488190''>an angular</span> <span m=''2488540''>bisector</span>
  <span m=''2489020''>of</span> <span m=''2489110''>these</span> <span m=''2489340''>two</span>
  <span m=''2489500''>perpendicular</span> <span m=''2490220''>folds.</span> <span
  m=''2491510''>Because</span> <span m=''2491990''>if</span> <span m=''2492980''>you</span>
  <span m=''2493080''>bisect</span> <span m=''2493510''>these</span> <span m=''2493670''>two</span>
  <span m=''2493800''>things,</span> <span m=''2494650''>you</span> <span m=''2494760''>also</span>
  <span m=''2495040''>bisect</span> <span m=''2495500''>two</span> <span m=''2495620''>things</span>
  <span m=''2495840''>that</span> <span m=''2495930''>are</span> <span m=''2496020''>perpendicular</span>
  <span m=''2496630''>to</span> <span m=''2496740''>them.</span> <span m=''2497750''>It''s</span>
  <span m=''2497850''>like</span> <span m=''2497980''>two</span> <span m=''2498150''>wrongs</span>
  <span m=''2498430''>make</span> <span m=''2498600''>a</span> <span m=''2498670''>right</span>
  <span m=''2499530''>somehow.</span> </p><p><span m=''2500830''>So</span> <span m=''2500980''>this</span>
  <span m=''2501180''>guy</span> <span m=''2501310''>bisects</span> <span m=''2502510''>those</span>
  <span m=''2502740''>two</span> <span m=''2502880''>creases.</span> <span m=''2504130''>So</span>
  <span m=''2504370''>if</span> <span m=''2504500''>you</span> <span m=''2504620''>fold</span>
  <span m=''2504860''>along</span> <span m=''2505140''>here--</span> <span m=''2505700''>actually</span>
  <span m=''2506000''>you</span> <span m=''2506130''>align</span> <span m=''2506670''>these</span>
  <span m=''2506930''>creases.</span> <span m=''2507950''>It''s</span> <span m=''2508080''>a</span>
  <span m=''2508190''>duality--</span> <span m=''2508515''>you</span> <span m=''2508840''>are</span>
  <span m=''2508920''>aligning</span> <span m=''2509310''>the</span> <span m=''2509400''>perpendicular</span>
  <span m=''2510040''>folds.</span> <span m=''2510840''>That</span> <span m=''2510930''>fold</span>
  <span m=''2511210''>along</span> <span m=''2511370''>here,</span> <span m=''2511910''>you</span>
  <span m=''2512110''>line</span> <span m=''2512400''>up</span> <span m=''2512730''>this</span>
  <span m=''2512910''>fold</span> <span m=''2513040''>with</span> <span m=''2513160''>that</span>
  <span m=''2513360''>one,</span> <span m=''2513580''>this</span> <span m=''2513740''>fold</span>
  <span m=''2513890''>with</span> <span m=''2514010''>that</span> <span m=''2514210''>one.</span>
  <span m=''2514750''>I</span> <span m=''2514830''>fold</span> <span m=''2515080''>here,</span>
  <span m=''2515400''>I</span> <span m=''2515460''>lined</span> <span m=''2515700''>up</span>
  <span m=''2516250''>this</span> <span m=''2516660''>fold</span> <span m=''2516880''>with</span>
  <span m=''2516950''>that</span> <span m=''2517140''>one.</span> <span m=''2517290''>There''s</span>
  <span m=''2518050''>like</span> <span m=''2518250''>a</span> <span m=''2518710''>zero</span>
  <span m=''2519430''>length</span> <span m=''2519680''>fold</span> <span m=''2519970''>that''s</span>
  <span m=''2520140''>there.</span> <span m=''2521110''>You</span> <span m=''2521340''>fold</span>
  <span m=''2521420''>along</span> <span m=''2521680''>all</span> <span m=''2521810''>these</span>
  <span m=''2521960''>things.</span> <span m=''2522130''>You</span> <span m=''2522230''>line</span>
  <span m=''2522460''>up this</span> <span m=''2522610''>with</span> <span m=''2522740''>itself,</span>
  <span m=''2524010''>and</span> <span m=''2524140''>so</span> <span m=''2524280''>on.</span>
  </p><p><span m=''2525210''>So</span> <span m=''2525320''>you</span> <span m=''2525380''>follow</span>
  <span m=''2525720''>along</span> <span m=''2526010''>this</span> <span m=''2526180''>thing.</span>
  <span m=''2526540''>This</span> <span m=''2529140''>corridor</span> <span m=''2530010''>folds</span>
  <span m=''2530310''>down</span> <span m=''2530620''>to</span> <span m=''2531500''>basically</span>
  <span m=''2531900''>a</span> <span m=''2531960''>rectangle.</span> <span m=''2533260''>It''s</span>
  <span m=''2533370''>got</span> <span m=''2533540''>some</span> <span m=''2533690''>rough</span>
  <span m=''2533900''>edges</span> <span m=''2534190''>in</span> <span m=''2534260''>the</span>
  <span m=''2534370''>top</span> <span m=''2534610''>and</span> <span m=''2534670''>the</span>
  <span m=''2534750''>bottom,</span> <span m=''2535480''>but</span> <span m=''2535590''>it</span>
  <span m=''2535690''>lies</span> <span m=''2536030''>in</span> <span m=''2536850''>the</span>
  <span m=''2536910''>strip</span> <span m=''2537430''>in</span> <span m=''2537550''>3D,</span>
  <span m=''2538770''>and</span> <span m=''2539055''>I have a</span> <span m=''2539340''>picture</span>
  <span m=''2539680''>of that.</span> <span m=''2540960''>So</span> <span m=''2541180''>I</span>
  <span m=''2541280''>took</span> <span m=''2542020''>the</span> <span m=''2542140''>one</span>
  <span m=''2542340''>over</span> <span m=''2542530''>here--</span> <span m=''2543960''>this</span>
  <span m=''2544620''>blue</span> <span m=''2545450''>corridor--</span> <span m=''2546670''>and</span>
  <span m=''2546900''>if</span> <span m=''2546990''>you</span> <span m=''2547080''>fold</span>
  <span m=''2547350''>it</span> <span m=''2547410''>up,</span> <span m=''2547580''>it</span>
  <span m=''2547660''>looks</span> <span m=''2547870''>like</span> <span m=''2548040''>this.</span>
  </p><p><span m=''2549790''>OK,</span> <span m=''2549990''>now</span> <span m=''2550270''>in</span>
  <span m=''2550420''>particular,</span> <span m=''2551110''>you</span> <span m=''2551150''>can</span>
  <span m=''2551280''>check</span> <span m=''2551580''>at</span> <span m=''2551650''>this</span>
  <span m=''2551840''>point.</span> <span m=''2552090''>It''s</span> <span m=''2552210''>pretty</span>
  <span m=''2552410''>easy</span> <span m=''2552680''>to</span> <span m=''2552760''>check</span>
  <span m=''2553070''>because</span> <span m=''2553480''>of</span> <span m=''2553600''>all</span>
  <span m=''2553730''>this</span> <span m=''2553890''>bisectorness--</span> <span
  m=''2555730''>Bisector</span> <span m=''2556180''>goodness--</span> <span m=''2557340''>that</span>
  <span m=''2557670''>you</span> <span m=''2558230''>bring</span> <span m=''2558640''>into</span>
  <span m=''2558850''>alignment</span> <span m=''2559370''>all</span> <span m=''2559520''>the</span>
  <span m=''2559610''>cut</span> <span m=''2559810''>edges.</span> <span m=''2560760''>So</span>
  <span m=''2560860''>for</span> <span m=''2561000''>example,</span> <span m=''2562110''>this</span>
  <span m=''2562280''>guy,</span> <span m=''2562640''>because</span> <span m=''2563070''>it
  bisects</span> <span m=''2563470''>that</span> <span m=''2563890''>cut edge</span>
  <span m=''2564310''>and that</span> <span m=''2564520''>cut</span> <span m=''2564680''>edge,</span>
  <span m=''2565090''>it</span> <span m=''2565500''>brings</span> <span m=''2565740''>them</span>
  <span m=''2565880''>into</span> <span m=''2566060''>alignment.</span> <span m=''2566640''>And</span>
  <span m=''2566660''>you</span> <span m=''2566770''>can</span> <span m=''2566900''>see</span>
  <span m=''2567030''>that</span> <span m=''2567250''>somewhere</span> <span m=''2567610''>in</span>
  <span m=''2567690''>this</span> <span m=''2567820''>picture.</span> <span m=''2568070''>I</span>
  <span m=''2568110''>think</span> <span m=''2568270''>it''s</span> <span m=''2568410''>these</span>
  <span m=''2568630''>two</span> <span m=''2568750''>guys.</span> </p><p><span m=''2571200''>It</span>
  <span m=''2571370''>can</span> <span m=''2571550''>be</span> <span m=''2571680''>a</span>
  <span m=''2571730''>little</span> <span m=''2571900''>more</span> <span m=''2572080''>complicated.</span>
  <span m=''2573190''>Like</span> <span m=''2574480''>over</span> <span m=''2574700''>here</span>
  <span m=''2575510''>I</span> <span m=''2575620''>have</span> <span m=''2575760''>a</span>
  <span m=''2575820''>cut</span> <span m=''2576090''>edge,</span> <span m=''2576340''>then</span>
  <span m=''2576500''>I</span> <span m=''2576550''>have</span> <span m=''2577190''>a</span>
  <span m=''2577270''>bisector,</span> <span m=''2577990''>and</span> <span m=''2578060''>then</span>
  <span m=''2578160''>a</span> <span m=''2578210''>bisector,</span> <span m=''2578780''>and
  then</span> <span m=''2578920''>a</span> <span m=''2578960''>bisector,</span> <span
  m=''2579410''>and</span> <span m=''2579480''>then</span> <span m=''2579620''>another</span>
  <span m=''2579880''>cut</span> <span m=''2580080''>edge.</span> <span m=''2581230''>But</span>
  <span m=''2581410''>if</span> <span m=''2581560''>you</span> <span m=''2581700''>think</span>
  <span m=''2581920''>about</span> <span m=''2582210''>it</span> <span m=''2582330''>right,</span>
  <span m=''2582780''>it''s--</span> <span m=''2583330''>I</span> <span m=''2583400''>don''t</span>
  <span m=''2583590''>happen</span> <span m=''2584010''>to</span> <span m=''2584140''>meet</span>
  <span m=''2584920''>these</span> <span m=''2585850''>cut</span> <span m=''2586050''>edges,</span>
  <span m=''2586890''>but</span> <span m=''2587060''>I''m</span> <span m=''2587240''>effectively</span>
  <span m=''2588200''>bringing</span> <span m=''2588460''>this</span> <span m=''2588660''>into</span>
  <span m=''2588840''>alignment</span> <span m=''2589150''>with</span> <span m=''2589270''>this,</span>
  <span m=''2589550''>and</span> <span m=''2589630''>then</span> <span m=''2589770''>this</span>
  <span m=''2589950''>into</span> <span m=''2590110''>alignment</span> <span m=''2590400''>with</span>
  <span m=''2590500''>this,</span> <span m=''2590790''>and</span> <span m=''2590870''>then</span>
  <span m=''2591010''>this</span> <span m=''2591190''>into</span> <span m=''2591360''>alignment</span>
  <span m=''2591650''>with</span> <span m=''2591760''>that.</span> <span m=''2592320''>So</span>
  <span m=''2592480''>in</span> <span m=''2592540''>the</span> <span m=''2592670''>end,</span>
  <span m=''2592890''>I</span> <span m=''2592970''>line</span> <span m=''2593280''>this</span>
  <span m=''2593930''>with</span> <span m=''2594090''>that,</span> <span m=''2595270''>and</span>
  <span m=''2595460''>that''s</span> <span m=''2595650''>what''s</span> <span m=''2595790''>happening</span>
  <span m=''2598326''>up</span> <span m=''2598760''>here</span> <span m=''2599800''>on</span>
  <span m=''2599930''>the</span> <span m=''2600000''>left.</span> <span m=''2600910''>Where</span>
  <span m=''2601380''>I</span> <span m=''2601440''>don''t</span> <span m=''2601630''>quite</span>
  <span m=''2601920''>come</span> <span m=''2602130''>all</span> <span m=''2602260''>the</span>
  <span m=''2602330''>way</span> <span m=''2602460''>down,</span> <span m=''2602830''>but
  I</span> <span m=''2602980''>still</span> <span m=''2603240''>end</span> <span m=''2603340''>up</span>
  <span m=''2603440''>lining</span> <span m=''2603740''>everything</span> <span m=''2604090''>up.</span>
  </p><p><span m=''2604610''>So</span> <span m=''2604780''>this</span> <span m=''2604960''>is</span>
  <span m=''2605090''>the</span> <span m=''2605170''>solution</span> <span m=''2605640''>to</span>
  <span m=''2605710''>the</span> <span m=''2605790''>fold-and-cut</span> <span m=''2606250''>problem</span>
  <span m=''2606890''>as</span> <span m=''2607090''>long</span> <span m=''2607320''>as</span>
  <span m=''2607440''>it</span> <span m=''2607530''>actually</span> <span m=''2607960''>faults.</span>
  <span m=''2609700''>And</span> <span m=''2609910''>to</span> <span m=''2609960''>show</span>
  <span m=''2610160''>that</span> <span m=''2610300''>actually</span> <span m=''2610630''>folds,</span>
  <span m=''2611040''>you</span> <span m=''2611140''>just</span> <span m=''2611370''>need</span>
  <span m=''2611500''>to</span> <span m=''2611560''>show</span> <span m=''2612010''>that</span>
  <span m=''2612290''>these</span> <span m=''2613980''>corridors--</span> <span m=''2615200''>I</span>
  <span m=''2615290''>forget,</span> <span m=''2615580''>I</span> <span m=''2615620''>think</span>
  <span m=''2615780''>we</span> <span m=''2615860''>call</span> <span m=''2616010''>these</span>
  <span m=''2616150''>accordions.</span> <span m=''2616930''>It''s</span> <span m=''2617060''>been</span>
  <span m=''2617300''>a</span> <span m=''2617360''>long</span> <span m=''2617580''>time.</span>
  <span m=''2618000''>Since</span> <span m=''2618190''>''98</span> <span m=''2618870''>I
  wrote</span> <span m=''2619290''>this</span> <span m=''2619460''>paper</span> </p><p><span
  m=''2622230''>You</span> <span m=''2622330''>take</span> <span m=''2622520''>these</span>
  <span m=''2622680''>accordions</span> <span m=''2623560''>and</span> <span m=''2623720''>you</span>
  <span m=''2623820''>just</span> <span m=''2624060''>want</span> <span m=''2624210''>to</span>
  <span m=''2624280''>see</span> <span m=''2624450''>how</span> <span m=''2624690''>they</span>
  <span m=''2624830''>fit</span> <span m=''2625040''>together.</span> <span m=''2626250''>And
  low</span> <span m=''2626750''>and behold,</span> <span m=''2627100''>they</span>
  <span m=''2627190''>fit</span> <span m=''2627390''>together</span> <span m=''2628170''>in</span>
  <span m=''2628300''>a</span> <span m=''2628370''>tree</span> <span m=''2628770''>in</span>
  <span m=''2628900''>this</span> <span m=''2629810''>picture.</span> <span m=''2631620''>It</span>
  <span m=''2631780''>gets</span> <span m=''2631990''>more</span> <span m=''2632210''>complicated</span>
  <span m=''2633840''>in</span> <span m=''2633980''>another</span> <span m=''2634260''>picture,</span>
  <span m=''2634550''>which</span> <span m=''2634750''>I</span> <span m=''2634860''>will</span>
  <span m=''2635280''>show</span> <span m=''2635490''>you</span> <span m=''2636310''>in</span>
  <span m=''2636410''>a</span> <span m=''2636450''>moment.</span> <span m=''2637310''>But</span>
  <span m=''2637760''>in</span> <span m=''2638250''>this</span> <span m=''2638420''>situation</span>
  <span m=''2639100''>where</span> <span m=''2639900''>every</span> <span m=''2640170''>quarter</span>
  <span m=''2640550''>goes</span> <span m=''2640790''>off</span> <span m=''2640980''>to</span>
  <span m=''2641100''>infinity</span> <span m=''2641720''>on</span> <span m=''2641800''>both</span>
  <span m=''2641970''>sides,</span> <span m=''2642820''>you</span> <span m=''2642930''>get</span>
  <span m=''2643090''>a</span> <span m=''2643160''>nice</span> <span m=''2644100''>tree</span>
  <span m=''2644330''>structure.</span> <span m=''2645610''>And</span> <span m=''2645920''>as</span>
  <span m=''2646040''>long</span> <span m=''2646280''>as</span> <span m=''2646350''>you</span>
  <span m=''2646480''>could</span> <span m=''2646620''>fold</span> <span m=''2646850''>this</span>
  <span m=''2647040''>tree</span> <span m=''2647490''>flat,</span> <span m=''2648870''>then</span>
  <span m=''2649730''>you</span> <span m=''2649930''>can</span> <span m=''2650090''>fold</span>
  <span m=''2651170''>this</span> <span m=''2651390''>thing</span> <span m=''2651610''>flat.</span>
  <span m=''2652350''>Because</span> <span m=''2653430''>each</span> <span m=''2653670''>of</span>
  <span m=''2653740''>these</span> <span m=''2653980''>edges</span> <span m=''2654340''>of</span>
  <span m=''2654430''>the</span> <span m=''2654550''>tree</span> <span m=''2655250''>is
  this</span> <span m=''2655580''>very</span> <span m=''2655790''>simple</span> <span
  m=''2656200''>accordion</span> <span m=''2656590''>structure</span> <span m=''2656960''>which</span>
  <span m=''2657900''>trivially</span> <span m=''2658800''>falls</span> <span m=''2659130''>flat.</span>
  </p><p><span m=''2661200''>The</span> <span m=''2661360''>other</span> <span m=''2661570''>thing
  you</span> <span m=''2661720''>have to check</span> <span m=''2661990''>here is</span>
  <span m=''2662180''>you</span> <span m=''2662300''>actually</span> <span m=''2662590''>alternate</span>
  <span m=''2663080''>mountain</span> <span m=''2663330''>valley.</span> <span m=''2664230''>That''s</span>
  <span m=''2664390''>a</span> <span m=''2664430''>little</span> <span m=''2664600''>more</span>
  <span m=''2664750''>subtle,</span> <span m=''2665060''>especially</span> <span m=''2665440''>when</span>
  <span m=''2665610''>I</span> <span m=''2665660''>don''t</span> <span m=''2665900''>draw</span>
  <span m=''2666100''>the</span> <span m=''2666200''>mountain</span> <span m=''2666420''>valley</span>
  <span m=''2666700''>assignment.</span> <span m=''2667790''>But</span> <span m=''2668080''>it</span>
  <span m=''2668180''>turns</span> <span m=''2668460''>out</span> <span m=''2668900''>you</span>
  <span m=''2669030''>always</span> <span m=''2669380''>alternate</span> <span m=''2669880''>between</span>
  <span m=''2670120''>mountain</span> <span m=''2670380''>and</span> <span m=''2670470''>valley</span>
  <span m=''2670790''>in</span> <span m=''2670880''>this</span> <span m=''2671030''>picture,</span>
  <span m=''2672030''>which</span> <span m=''2672150''>is</span> <span m=''2672230''>great.</span>
  <span m=''2672570''>That''s</span> <span m=''2672780''>the</span> <span m=''2672860''>thing</span>
  <span m=''2673640''>we</span> <span m=''2673710''>know</span> <span m=''2674000''>always</span>
  <span m=''2674300''>folds</span> <span m=''2674520''>flats.</span> <span m=''2674850''>It''s
  like</span> <span m=''2674970''>a</span> <span m=''2675040''>1D</span> <span m=''2675400''>folding.</span>
  </p><p><span m=''2676720''>So</span> <span m=''2676860''>these</span> <span m=''2677140''>are</span>
  <span m=''2677220''>super</span> <span m=''2677600''>easy</span> <span m=''2677830''>to</span>
  <span m=''2677900''>fold.</span> <span m=''2678250''>You can</span> <span m=''2678380''>fold</span>
  <span m=''2678680''>each</span> <span m=''2678900''>of</span> <span m=''2678970''>them</span>
  <span m=''2679160''>if</span> <span m=''2679280''>you</span> <span m=''2679440''>cut</span>
  <span m=''2679830''>along</span> <span m=''2680020''>all</span> <span m=''2680280''>the</span>
  <span m=''2680380''>dash</span> <span m=''2680690''>lines</span> <span m=''2681580''>You
  can</span> <span m=''2681780''>fold each</span> <span m=''2681950''>separately.</span>
  <span m=''2682940''>Then</span> <span m=''2683120''>you</span> <span m=''2683210''>need</span>
  <span m=''2683380''>to</span> <span m=''2683480''>join</span> <span m=''2683760''>them</span>
  <span m=''2683880''>together</span> <span m=''2684490''>where</span> <span m=''2684660''>the</span>
  <span m=''2685160''>edges</span> <span m=''2685550''>here--</span> <span m=''2686150''>just</span>
  <span m=''2686380''>like</span> <span m=''2686640''>in tree</span> <span m=''2686910''>theory--</span>
  <span m=''2687190''>the</span> <span m=''2687290''>edges</span> <span m=''2687600''>here</span>
  <span m=''2687760''>correspond</span> <span m=''2688360''>to</span> <span m=''2688440''>these</span>
  <span m=''2689080''>rivers.</span> </p><p><span m=''2690180''>And</span> <span m=''2690320''>now</span>
  <span m=''2691300''>you</span> <span m=''2691400''>need</span> <span m=''2691560''>to</span>
  <span m=''2691650''>somehow</span> <span m=''2691920''>attach</span> <span m=''2692410''>them</span>
  <span m=''2692550''>here.</span> <span m=''2692820''>Check</span> <span m=''2693140''>that</span>
  <span m=''2693660''>where</span> <span m=''2693830''>you</span> <span m=''2693960''>attach</span>
  <span m=''2694410''>them,</span> <span m=''2694530''>there''s</span> <span m=''2694700''>no</span>
  <span m=''2694850''>crossings.</span> <span m=''2697360''>I''m</span> <span m=''2697490''>not</span>
  <span m=''2697660''>going</span> <span m=''2697770''>to</span> <span m=''2697990''>describe,</span>
  <span m=''2698470''>but</span> <span m=''2698540''>it''s</span> <span m=''2698720''>pretty</span>
  <span m=''2698970''>easy.</span> <span m=''2700140''>Plain</span> <span m=''2700430''>area</span>
  <span m=''2700790''>essentially</span> <span m=''2701190''>of</span> <span m=''2701250''>that</span>
  <span m=''2701420''>diagram,</span> <span m=''2702210''>and</span> <span m=''2702420''>then</span>
  <span m=''2702540''>you</span> <span m=''2702600''>need</span> <span m=''2702760''>to</span>
  <span m=''2702830''>fold</span> <span m=''2703140''>this</span> <span m=''2703300''>tree</span>
  <span m=''2703540''>flat.</span> <span m=''2704660''>Folding</span> <span m=''2705010''>a
  tree</span> <span m=''2705260''>flat</span> <span m=''2706440''>is</span> <span
  m=''2706580''>actually</span> <span m=''2706970''>kind</span> <span m=''2707160''>of</span>
  <span m=''2707270''>a</span> <span m=''2707360''>segue</span> <span m=''2707820''>into</span>
  <span m=''2708080''>next</span> <span m=''2708360''>lecture,</span> <span m=''2708660''>which</span>
  <span m=''2708800''>will</span> <span m=''2708890''>be</span> <span m=''2709040''>about</span>
  <span m=''2709290''>folding</span> <span m=''2709570''>linkages.</span> </p><p><span
  m=''2711720''>In</span> <span m=''2711860''>this</span> <span m=''2712030''>case,</span>
  <span m=''2712280''>it''s</span> <span m=''2712400''>really</span> <span m=''2712640''>easy.</span>
  <span m=''2713300''>You</span> <span m=''2713400''>just</span> <span m=''2713540''>pick</span>
  <span m=''2713760''>up</span> <span m=''2714050''>some</span> <span m=''2714340''>root,</span>
  <span m=''2714600''>like</span> <span m=''2714910''>the</span> <span m=''2715010''>letter</span>
  <span m=''2715270''>"A"</span> <span m=''2715480''>over</span> <span m=''2715630''>there,</span>
  <span m=''2716360''>and</span> <span m=''2716550''>you</span> <span m=''2716650''>hang</span>
  <span m=''2716970''>the</span> <span m=''2717060''>tree.</span> <span m=''2718020''>Pull</span>
  <span m=''2718300''>up.</span> <span m=''2719600''>Technically</span> <span m=''2720130''>this</span>
  <span m=''2720320''>is</span> <span m=''2720460''>like</span> <span m=''2720700''>a</span>
  <span m=''2720970''>[? depth ?]</span> <span m=''2721200''>[? first ?]</span> <span
  m=''2721410''>search</span> <span m=''2721830''>of the</span> <span m=''2722070''>tree.</span>
  <span m=''2722920''>So you</span> <span m=''2723100''>just</span> <span m=''2723290''>walk</span>
  <span m=''2723610''>down--</span> <span m=''2724400''>aways</span> <span m=''2724730''>walk</span>
  <span m=''2724990''>down</span> <span m=''2725380''>until</span> <span m=''2725640''>you''re</span>
  <span m=''2725800''>finished,</span> <span m=''2726210''>then</span> <span m=''2726340''>you</span>
  <span m=''2726430''>go</span> <span m=''2726560''>back</span> <span m=''2726780''>up.</span>
  <span m=''2727260''>Walk</span> <span m=''2727460''>down</span> <span m=''2727650''>some</span>
  <span m=''2727780''>more</span> <span m=''2727960''>branches.</span> </p><p><span
  m=''2728720''>You end</span> <span m=''2728920''>up</span> <span m=''2729000''>drawing</span>
  <span m=''2729260''>everything</span> <span m=''2729730''>downward</span> <span
  m=''2731180''>away</span> <span m=''2731440''>from</span> <span m=''2731700''>A.</span>
  <span m=''2732900''>And</span> <span m=''2733180''>it</span> <span m=''2733260''>will</span>
  <span m=''2733390''>be</span> <span m=''2733550''>a</span> <span m=''2733600''>flat</span>
  <span m=''2733880''>folding.</span> <span m=''2734200''>There won''t</span> <span
  m=''2734410''>be any</span> <span m=''2734580''>crossings</span> <span m=''2735070''>here.</span>
  <span m=''2736190''>And</span> <span m=''2736340''>then</span> <span m=''2736670''>this</span>
  <span m=''2736890''>is</span> <span m=''2737050''>a</span> <span m=''2737160''>1D</span>
  <span m=''2737490''>representation</span> <span m=''2738140''>of</span> <span m=''2738190''>what''s</span>
  <span m=''2738370''>really</span> <span m=''2738620''>going</span> <span m=''2738920''>on,</span>
  <span m=''2739200''>which</span> <span m=''2739280''>is</span> <span m=''2739420''>that</span>
  <span m=''2740100''>above</span> <span m=''2740530''>each</span> <span m=''2740720''>of</span>
  <span m=''2740810''>these</span> <span m=''2741000''>edges</span> <span m=''2742920''>is</span>
  <span m=''2743120''>really</span> <span m=''2743390''>an</span> <span m=''2743460''>accordion,</span>
  <span m=''2744340''>and</span> <span m=''2744480''>you</span> <span m=''2744670''>need
  to</span> <span m=''2744810''>adjoin</span> <span m=''2745080''>them</span> <span
  m=''2745220''>together</span> <span m=''2745560''>there.</span> <span m=''2746150''>So
  we''ll</span> <span m=''2746330''>basically</span> <span m=''2746720''>do</span>
  <span m=''2746870''>this</span> <span m=''2747010''>modular</span> <span m=''2747650''>folding</span>
  <span m=''2748060''>where</span> <span m=''2748170''>you</span> <span m=''2748250''>fold
  each</span> <span m=''2748620''>accordion</span> <span m=''2748930''>separately,</span>
  <span m=''2749770''>put</span> <span m=''2749960''>them</span> <span m=''2750080''>together</span>
  <span m=''2750460''>according</span> <span m=''2750770''>to</span> <span m=''2750850''>this.</span>
  <span m=''2751460''>Boom,</span> <span m=''2751750''>you</span> <span m=''2751760''>get</span>
  <span m=''2751880''>your</span> <span m=''2751990''>flat</span> <span m=''2752240''>folding.</span>
  </p><p><span m=''2752580''>From</span> <span m=''2752810''>this</span> <span m=''2753010''>picture,</span>
  <span m=''2753330''>you</span> <span m=''2753490''>could</span> <span m=''2753630''>read</span>
  <span m=''2753820''>out</span> <span m=''2754100''>the</span> <span m=''2754240''>mountain</span>
  <span m=''2754500''>valley</span> <span m=''2754760''>assignments</span> <span m=''2755170''>before</span>
  <span m=''2755430''>the</span> <span m=''2755580''>perpendicular</span> <span m=''2756310''>folds.</span>
  <span m=''2757250''>This</span> <span m=''2757450''>looks</span> <span m=''2757610''>like</span>
  <span m=''2757760''>a</span> <span m=''2757810''>valley,</span> <span m=''2758210''>this</span>
  <span m=''2758370''>looks</span> <span m=''2758520''>like</span> <span m=''2758660''>a</span>
  <span m=''2758700''>valley--</span> <span m=''2759470''>this</span> <span m=''2759640''>looks</span>
  <span m=''2759810''>like</span> <span m=''2760240''>a</span> <span m=''2760330''>perpendicular</span>
  <span m=''2760820''>fold</span> <span m=''2761000''>I</span> <span m=''2761060''>didn''t</span>
  <span m=''2761340''>use</span> <span m=''2761790''>because</span> <span m=''2761970''>there''s</span>
  <span m=''2763270''>no</span> <span m=''2763400''>crease</span> <span m=''2763690''>there.</span>
  <span m=''2763810''>That''s</span> <span m=''2764030''>flat.</span> <span m=''2765910''>Whereas</span>
  <span m=''2766210''>a</span> <span m=''2766290''>mountain--</span> <span m=''2767400''>mountain''s</span>
  <span m=''2767730''>probably</span> <span m=''2767970''>at</span> <span m=''2768070''>the</span>
  <span m=''2768160''>top</span> <span m=''2768500''>at</span> <span m=''2768670''>A.</span>
  </p><p><span m=''2770880''>What</span> <span m=''2771200''>really</span> <span m=''2771600''>happens--</span>
  <span m=''2773860''>if</span> <span m=''2774130''>you</span> <span m=''2774260''>want</span>
  <span m=''2774440''>to</span> <span m=''2774490''>know--</span> <span m=''2774720''>really</span>
  <span m=''2776470''>what</span> <span m=''2776630''>we''re</span> <span m=''2776730''>deciding</span>
  <span m=''2777120''>is</span> <span m=''2777220''>whether</span> <span m=''2777430''>this</span>
  <span m=''2777530''>starts</span> <span m=''2777900''>mountain</span> <span m=''2778240''>or</span>
  <span m=''2778320''>valley,</span> <span m=''2778720''>and</span> <span m=''2778780''>then</span>
  <span m=''2778910''>it</span> <span m=''2778960''>will</span> <span m=''2779110''>actually</span>
  <span m=''2779320''>alternate</span> <span m=''2779800''>back</span> <span m=''2780010''>and</span>
  <span m=''2780110''>forth</span> <span m=''2781390''>as</span> <span m=''2781560''>you</span>
  <span m=''2781680''>move</span> <span m=''2781930''>along the</span> <span m=''2782130''>perpendicular.</span>
  <span m=''2783772''>So</span> <span m=''2784270''>that''s</span> <span m=''2784640''>basically</span>
  <span m=''2784960''>how</span> <span m=''2785040''>you</span> <span m=''2785170''>construct</span>
  <span m=''2785540''>a</span> <span m=''2785590''>folded</span> <span m=''2785980''>state.</span>
  <span m=''2787760''>In</span> <span m=''2787920''>this</span> <span m=''2788110''>situation</span>
  <span m=''2788810''>of</span> <span m=''2789140''>so-called</span> <span m=''2789520''>linear</span>
  <span m=''2789950''>corridors.</span> <span m=''2791460''>Now there</span> <span
  m=''2791610''>are a</span> <span m=''2791660''>bunch</span> <span m=''2791880''>of</span>
  <span m=''2791970''>things</span> <span m=''2792230''>I</span> <span m=''2792960''>haven''t</span>
  <span m=''2793250''>mentioned,</span> <span m=''2795400''>but I</span> <span m=''2795610''>think--</span>
  <span m=''2796650''>I don''t</span> <span m=''2797050''>want</span> <span m=''2797160''>to</span>
  <span m=''2797230''>talk</span> <span m=''2797450''>about</span> <span m=''2797640''>them</span>
  <span m=''2797750''>too</span> <span m=''2797930''>much</span> <span m=''2798770''>so</span>
  <span m=''2798950''>I</span> <span m=''2799000''>get</span> <span m=''2799130''>out
  to</span> <span m=''2799360''>the</span> <span m=''2799450''>other</span> <span
  m=''2799610''>topics.</span> </p><p><span m=''2827590''>So,</span> <span m=''2830260''>what</span>
  <span m=''2830700''>I</span> <span m=''2830760''>just</span> <span m=''2830980''>talked</span>
  <span m=''2831230''>about</span> <span m=''2831500''>is</span> <span m=''2831770''>something</span>
  <span m=''2832050''>called</span> <span m=''2832220''>a</span> <span m=''2832270''>linear</span>
  <span m=''2832610''>corridor</span> <span m=''2833010''>case,</span> <span m=''2833340''>which</span>
  <span m=''2833550''>is</span> <span m=''2834210''>really</span> <span m=''2834410''>where</span>
  <span m=''2834570''>it''s</span> <span m=''2834740''>most</span> <span m=''2835110''>beautiful--</span>
  <span m=''2838640''>this</span> <span m=''2838900''>construction</span> <span m=''2839440''>of</span>
  <span m=''2839550''>a</span> <span m=''2839610''>folded</span> <span m=''2839920''>state--</span>
  <span m=''2840950''>and</span> <span m=''2842350''>linear</span> <span m=''2842660''>corridor</span>
  <span m=''2843110''>intuitively</span> <span m=''2843445''>is</span> <span m=''2843780''>something</span>
  <span m=''2844080''>like</span> <span m=''2844260''>this.</span> <span m=''2844450''>It</span>
  <span m=''2844530''>goes</span> <span m=''2844710''>off</span> <span m=''2844890''>to</span>
  <span m=''2844990''>infinite</span> <span m=''2845460''>on</span> <span m=''2845550''>both</span>
  <span m=''2845730''>sides.</span> <span m=''2846810''>Has</span> <span m=''2847000''>constant</span>
  <span m=''2847390''>width</span> <span m=''2847610''>all</span> <span m=''2847760''>the</span>
  <span m=''2847830''>way.</span> <span m=''2848370''>Of</span> <span m=''2848410''>course,</span>
  <span m=''2848620''>it''s</span> <span m=''2848730''>really</span> <span m=''2848960''>a</span>
  <span m=''2849020''>discrete</span> <span m=''2849420''>thing.</span> <span m=''2849660''>Not</span>
  <span m=''2849750''>a</span> <span m=''2849830''>smooth</span> <span m=''2850110''>thing.</span>
  </p><p><span m=''2854060''>Let</span> <span m=''2854270''>me</span> <span m=''2854390''>say</span>
  <span m=''2855950''>conjecture--</span> <span m=''2860170''>if</span> <span m=''2860440''>you''re</span>
  <span m=''2860690''>cut</span> <span m=''2860990''>graph</span> <span m=''2864460''>has</span>
  <span m=''2865060''>that</span> <span m=''2865310''>maximum</span> <span m=''2865950''>degree</span>
  <span m=''2866290''>2--</span> <span m=''2868380''>it</span> <span m=''2868800''>means</span>
  <span m=''2869040''>at</span> <span m=''2869120''>most</span> <span m=''2869450''>two</span>
  <span m=''2869680''>edges</span> <span m=''2870540''>at</span> <span m=''2870670''>every</span>
  <span m=''2870870''>vertex.</span> <span m=''2871810''>This</span> <span m=''2872000''>is</span>
  <span m=''2872130''>a</span> <span m=''2872460''>very</span> <span m=''2872710''>common</span>
  <span m=''2873060''>scenario.</span> <span m=''2873450''>This</span> <span m=''2873640''>is</span>
  <span m=''2873730''>if</span> <span m=''2873850''>you</span> <span m=''2873960''>want</span>
  <span m=''2874070''>to</span> <span m=''2874120''>make</span> <span m=''2874240''>a</span>
  <span m=''2874310''>polygon,</span> <span m=''2874810''>every</span> <span m=''2875020''>vertex</span>
  <span m=''2875390''>has</span> <span m=''2875560''>degree</span> <span m=''2875810''>2.</span>
  <span m=''2876520''>If you want</span> <span m=''2876780''>to make</span> <span
  m=''2876980''>several</span> <span m=''2877250''>polygons,</span> <span m=''2877730''>every</span>
  <span m=''2877920''>vertex</span> <span m=''2878270''>has</span> <span m=''2878430''>degree</span>
  <span m=''2878690''>2.</span> <span m=''2879260''>I''ll</span> <span m=''2879460''>even</span>
  <span m=''2879790''>let you have</span> <span m=''2879970''>vertices</span> <span
  m=''2880410''>of</span> <span m=''2880460''>degree</span> <span m=''2880700''>1</span>
  <span m=''2881280''>or</span> <span m=''2881420''>0</span> <span m=''2881820''>for</span>
  <span m=''2882010''>free,</span> <span m=''2882950''>but</span> <span m=''2883130''>mainly</span>
  <span m=''2883360''>we''re</span> <span m=''2883490''>thinking</span> <span m=''2883720''>about</span>
  <span m=''2884820''>degree</span> <span m=''2885070''>2</span> <span m=''2885290''>everywhere.</span>
  </p><p><span m=''2888620''>Then,</span> <span m=''2892210''>we</span> <span m=''2892380''>almost</span>
  <span m=''2892820''>always</span> <span m=''2897820''>have</span> <span m=''2898170''>a</span>
  <span m=''2899620''>linear</span> <span m=''2899920''>corridor.</span> <span m=''2904340''>So</span>
  <span m=''2904510''>this</span> <span m=''2904710''>is</span> <span m=''2904780''>why</span>
  <span m=''2904930''>the</span> <span m=''2905040''>situation''s</span> <span m=''2905610''>interesting,</span>
  <span m=''2906120''>although</span> <span m=''2906280''>unfortunately</span> <span
  m=''2906740''>this</span> <span m=''2906890''>is</span> <span m=''2906930''>still</span>
  <span m=''2907190''>a</span> <span m=''2907250''>conjecture.</span> <span m=''2908050''>I''m</span>
  <span m=''2908140''>sure</span> <span m=''2908370''>this</span> <span m=''2908540''>is</span>
  <span m=''2908640''>true,</span> <span m=''2909350''>but</span> <span m=''2909500''>proving</span>
  <span m=''2909850''>it--</span> <span m=''2910150''>I</span> <span m=''2910320''>don''t</span>
  <span m=''2910520''>quite</span> <span m=''2910790''>know</span> <span m=''2910950''>the</span>
  <span m=''2911110''>right</span> <span m=''2911190''>techniques.</span> </p><p><span
  m=''2913500''>So</span> <span m=''2913740''>in</span> <span m=''2913840''>this</span>
  <span m=''2914300''>typical</span> <span m=''2914700''>situation,</span> <span m=''2915960''>you</span>
  <span m=''2916110''>take</span> <span m=''2916520''>any</span> <span m=''2916820''>picture</span>
  <span m=''2917130''>you</span> <span m=''2917260''>want.</span> <span m=''2917820''>You</span>
  <span m=''2917920''>slightly</span> <span m=''2918550''>perturb</span> <span m=''2918920''>very</span>
  <span m=''2919130''>vertex</span> <span m=''2919610''>randomly,</span> <span m=''2920380''>say,</span>
  <span m=''2921250''>then</span> <span m=''2921590''>with</span> <span m=''2921730''>probability</span>
  <span m=''2922350''>1--</span> <span m=''2922760''>100%</span> <span m=''2923500''>probability--</span>
  <span m=''2924510''>you</span> <span m=''2924770''>will</span> <span m=''2924910''>get</span>
  <span m=''2925560''>only</span> <span m=''2925790''>linear</span> <span m=''2926090''>corridors.</span>
  <span m=''2929510''>And</span> <span m=''2929870''>that''s</span> <span m=''2930170''>the</span>
  <span m=''2930250''>situation</span> <span m=''2930920''>where</span> <span m=''2931150''>it</span>
  <span m=''2931260''>turns</span> <span m=''2931450''>into</span> <span m=''2931620''>a</span>
  <span m=''2931670''>tree.</span> <span m=''2932060''>It''s</span> <span m=''2932220''>easy</span>
  <span m=''2932420''>to</span> <span m=''2932490''>fold</span> <span m=''2933260''>life</span>
  <span m=''2933500''>is</span> <span m=''2933640''>good.</span> </p><p><span m=''2935750''>The</span>
  <span m=''2935920''>annoying</span> <span m=''2936210''>case</span> <span m=''2937750''>is</span>
  <span m=''2938110''>circular</span> <span m=''2938600''>corridor</span> <span m=''2938960''>case.</span>
  <span m=''2945640''>This</span> <span m=''2945820''>takes</span> <span m=''2946030''>a</span>
  <span m=''2946090''>lot</span> <span m=''2946250''>more</span> <span m=''2946380''>work</span>
  <span m=''2946600''>to</span> <span m=''2946680''>prove,</span> <span m=''2947060''>and
  I''m</span> <span m=''2947150''>not</span> <span m=''2947330''>going</span> <span
  m=''2947450''>to</span> <span m=''2947740''>talk</span> <span m=''2947980''>about</span>
  <span m=''2948170''>it</span> <span m=''2948240''>much.</span> <span m=''2949155''>A</span>
  <span m=''2949560''>circular</span> <span m=''2949990''>corridor</span> <span m=''2951660''>looks</span>
  <span m=''2951920''>like</span> <span m=''2953560''>this.</span> <span m=''2955550''>Here</span>
  <span m=''2955580''>we</span> <span m=''2955650''>have</span> <span m=''2955810''>these</span>
  <span m=''2955990''>in</span> <span m=''2956430''>with</span> <span m=''2956610''>rivers</span>
  <span m=''2956970''>also.</span> <span m=''2958120''>So</span> <span m=''2958350''>you</span>
  <span m=''2958480''>just</span> <span m=''2958680''>loop</span> <span m=''2958840''>around.</span>
  <span m=''2959590''>Still</span> <span m=''2959860''>constant</span> <span m=''2960240''>width</span>
  <span m=''2960440''>everywhere,</span> <span m=''2961980''>but</span> <span m=''2962140''>you</span>
  <span m=''2962280''>meet</span> <span m=''2962450''>yourself.</span> <span m=''2964050''>You</span>
  <span m=''2964190''>don''t</span> <span m=''2964350''>go</span> <span m=''2964450''>out</span>
  <span m=''2964600''>to</span> <span m=''2964680''>infinity.</span> </p><p><span
  m=''2967730''>It''s</span> <span m=''2967910''>harder.</span> <span m=''2969010''>Why</span>
  <span m=''2969180''>is</span> <span m=''2969280''>it</span> <span m=''2969360''>harder?</span>
  <span m=''2970560''>Well</span> <span m=''2970740''>in</span> <span m=''2970820''>particular,</span>
  <span m=''2972480''>if</span> <span m=''2972570''>you</span> <span m=''2972720''>look</span>
  <span m=''2972980''>at</span> <span m=''2974890''>how</span> <span m=''2975300''>one</span>
  <span m=''2975720''>corridor</span> <span m=''2976140''>folds,</span> <span m=''2977180''>it''s</span>
  <span m=''2977370''>no</span> <span m=''2977600''>longer--</span> <span m=''2978210''>it''s</span>
  <span m=''2978380''>like</span> <span m=''2978570''>the</span> <span m=''2978660''>same</span>
  <span m=''2978860''>situation</span> <span m=''2979290''>we</span> <span m=''2979360''>had</span>
  <span m=''2979610''>in like</span> <span m=''2979940''>lectures</span> <span m=''2980320''>two</span>
  <span m=''2980460''>and</span> <span m=''2980600''>three</span> <span m=''2981970''>where</span>
  <span m=''2982490''>we</span> <span m=''2982630''>had</span> <span m=''2983240''>on</span>
  <span m=''2983360''>the</span> <span m=''2983430''>one</span> <span m=''2983560''>hand</span>
  <span m=''2983700''>a</span> <span m=''2983760''>1D</span> <span m=''2984060''>folding</span>
  <span m=''2984400''>was</span> <span m=''2984520''>really</span> <span m=''2984790''>easy.</span>
  <span m=''2985560''>But</span> <span m=''2985690''>then</span> <span m=''2985910''>when</span>
  <span m=''2986040''>you</span> <span m=''2986280''>made</span> <span m=''2986580''>it</span>
  <span m=''2986710''>circular--</span> <span m=''2987800''>you''re just</span> <span
  m=''2987990''>folding</span> <span m=''2988280''>a</span> <span m=''2988330''>circle</span>
  <span m=''2988660''>instead</span> <span m=''2988880''>of</span> <span m=''2988960''>folding</span>
  <span m=''2989200''>a</span> <span m=''2989250''>line</span> <span m=''2989460''>segment--</span>
  <span m=''2990230''>now</span> <span m=''2990290''>you</span> <span m=''2990380''>had</span>
  <span m=''2990530''>this</span> <span m=''2990740''>wrap</span> <span m=''2991060''>around</span>
  <span m=''2991340''>issue.</span> </p><p><span m=''2991760''>So, like,</span> <span
  m=''2992230''>these</span> <span m=''2992490''>guys</span> <span m=''2992960''>would</span>
  <span m=''2993090''>have</span> <span m=''2993260''>to</span> <span m=''2993820''>line</span>
  <span m=''2994110''>up.</span> <span m=''2994310''>It</span> <span m=''2994380''>turns</span>
  <span m=''2994620''>out</span> <span m=''2994730''>they</span> <span m=''2994810''>will</span>
  <span m=''2995100''>line</span> <span m=''2995350''>up</span> <span m=''2995520''>because</span>
  <span m=''2995800''>everything</span> <span m=''2996410''>is</span> <span m=''2996600''>bisecting</span>
  <span m=''2996930''>and</span> <span m=''2997260''>whatnot.</span> <span m=''2998050''>These</span>
  <span m=''2998250''>edges</span> <span m=''2998480''>will</span> <span m=''2998640''>line</span>
  <span m=''2998860''>up,</span> <span m=''2999000''>but</span> <span m=''2999110''>now</span>
  <span m=''2999240''>you</span> <span m=''2999350''>have</span> <span m=''2999440''>to</span>
  <span m=''2999560''>join</span> <span m=''2999820''>them</span> <span m=''2999950''>together.</span>
  <span m=''3000940''>And</span> <span m=''3001110''>if</span> <span m=''3001200''>this</span>
  <span m=''3001470''>part</span> <span m=''3001970''>went</span> <span m=''3002170''>all</span>
  <span m=''3002350''>the</span> <span m=''3002440''>way</span> <span m=''3002560''>down</span>
  <span m=''3002800''>here</span> <span m=''3003450''>and</span> <span m=''3003570''>came</span>
  <span m=''3003730''>back</span> <span m=''3003950''>up,</span> <span m=''3004160''>then</span>
  <span m=''3004570''>you''d</span> <span m=''3004710''>get</span> <span m=''3004870''>an</span>
  <span m=''3004970''>intersection.</span> </p><p><span m=''3006920''>And</span> <span
  m=''3007630''>it</span> <span m=''3007780''>turns</span> <span m=''3008020''>out,</span>
  <span m=''3008460''>in</span> <span m=''3008680''>general,</span> <span m=''3011230''>I</span>
  <span m=''3011330''>get</span> <span m=''3011470''>a</span> <span m=''3011540''>choice</span>
  <span m=''3012000''>of</span> <span m=''3012200''>who''s</span> <span m=''3012480''>first</span>
  <span m=''3012840''>and</span> <span m=''3012920''>who''s</span> <span m=''3013100''>last.</span>
  <span m=''3013540''>I</span> <span m=''3013580''>have</span> <span m=''3013690''>a</span>
  <span m=''3013740''>circular</span> <span m=''3014180''>order</span> <span m=''3014470''>of</span>
  <span m=''3014550''>things,</span> <span m=''3014900''>and</span> <span m=''3015010''>I</span>
  <span m=''3015060''>get</span> <span m=''3015230''>to</span> <span m=''3015290''>choose</span>
  <span m=''3016490''>where I</span> <span m=''3016830''>break</span> <span m=''3017090''>that</span>
  <span m=''3017250''>circular</span> <span m=''3017590''>order</span> <span m=''3017850''>and
  make</span> <span m=''3018040''>it</span> <span m=''3018100''>a</span> <span m=''3018160''>linear</span>
  <span m=''3018470''>order.</span> <span m=''3019540''>Where</span> <span m=''3019790''>I
  do</span> <span m=''3019900''>the</span> <span m=''3020010''>wrap</span> <span m=''3020240''>around.</span>
  <span m=''3021000''>There''s</span> <span m=''3021200''>some</span> <span m=''3021410''>circular</span>
  <span m=''3021780''>corridors--</span> <span m=''3022860''>you</span> <span m=''3023020''>can''t</span>
  <span m=''3023350''>even</span> <span m=''3023950''>break</span> <span m=''3024220''>them</span>
  <span m=''3025410''>and</span> <span m=''3025740''>make</span> <span m=''3025890''>it</span>
  <span m=''3025970''>work.</span> <span m=''3027590''>Kind</span> <span m=''3027830''>of</span>
  <span m=''3028070''>depressing.</span> </p><p><span m=''3030200''>So</span> <span
  m=''3030400''>this</span> <span m=''3030620''>is</span> <span m=''3030690''>definitely</span>
  <span m=''3031110''>harder</span> <span m=''3031520''>and</span> <span m=''3031640''>that</span>
  <span m=''3031800''>sometimes</span> <span m=''3032630''>it''s</span> <span m=''3032820''>not</span>
  <span m=''3032950''>possible.</span> <span m=''3036680''>But</span> <span m=''3038070''>we</span>
  <span m=''3038280''>can</span> <span m=''3038480''>save</span> <span m=''3038750''>a</span>
  <span m=''3038800''>little</span> <span m=''3039070''>bit,</span> <span m=''3040270''>which</span>
  <span m=''3040450''>is--</span> <span m=''3042330''>I</span> <span m=''3042430''>don''t</span>
  <span m=''3042600''>have</span> <span m=''3042790''>an</span> <span m=''3042850''>example</span>
  <span m=''3043220''>handy.</span> <span m=''3043800''>I</span> <span m=''3043890''>wish</span>
  <span m=''3044110''>I</span> <span m=''3044160''>did.</span> <span m=''3044940''>I''ll</span>
  <span m=''3045380''>have to</span> <span m=''3045850''>reconstruct it.</span> <span
  m=''3046530''>This</span> <span m=''3046700''>is</span> <span m=''3046780''>so</span>
  <span m=''3046960''>long</span> <span m=''3047210''>ago.</span> </p><p><span m=''3050810''>Here''s</span>
  <span m=''3051210''>a</span> <span m=''3051290''>way</span> <span m=''3051460''>to</span>
  <span m=''3051550''>make</span> <span m=''3051760''>it</span> <span m=''3051910''>definitely</span>
  <span m=''3052250''>work.</span> <span m=''3053010''>Fold</span> <span m=''3053550''>all</span>
  <span m=''3053840''>the</span> <span m=''3053940''>cut</span> <span m=''3054160''>edges.</span>
  <span m=''3057300''>So</span> <span m=''3057440''>far</span> <span m=''3057810''>in
  the</span> <span m=''3058080''>pictures</span> <span m=''3058410''>I''ve</span>
  <span m=''3058510''>been</span> <span m=''3058620''>drawing,</span> <span m=''3059030''>I</span>
  <span m=''3059130''>didn''t</span> <span m=''3059410''>fold</span> <span m=''3059640''>along</span>
  <span m=''3059900''>the</span> <span m=''3059980''>cut</span> <span m=''3060170''>edges</span>
  <span m=''3060910''>because</span> <span m=''3061110''>I</span> <span m=''3061170''>really</span>
  <span m=''3061440''>wanted</span> <span m=''3062210''>to</span> <span m=''3062550''>separate</span>
  <span m=''3063120''>the</span> <span m=''3063310''>green</span> <span m=''3063610''>region</span>
  <span m=''3063880''>here</span> <span m=''3064050''>from</span> <span m=''3064220''>the</span>
  <span m=''3064310''>yellow</span> <span m=''3064560''>region.</span> <span m=''3064950''>If</span>
  <span m=''3065300''>I folded</span> <span m=''3065770''>this</span> <span m=''3065950''>up--</span>
  <span m=''3066710''>this</span> <span m=''3066890''>is</span> <span m=''3067080''>quite</span>
  <span m=''3067280''>a</span> <span m=''3067360''>complicated</span> <span m=''3067860''>one
  to</span> <span m=''3068155''>fold--</span> <span m=''3068820''>you</span> <span
  m=''3068940''>get</span> <span m=''3069160''>the</span> <span m=''3069250''>cut</span>
  <span m=''3069460''>lines</span> <span m=''3070260''>somewhere</span> <span m=''3070710''>like</span>
  <span m=''3071310''>over</span> <span m=''3071470''>there,</span> <span m=''3072320''>and</span>
  <span m=''3072480''>then</span> <span m=''3072610''>the</span> <span m=''3072700''>green</span>
  <span m=''3072940''>stuff</span> <span m=''3073190''>will</span> <span m=''3073310''>be</span>
  <span m=''3073470''>always</span> <span m=''3073690''>above</span> <span m=''3073990''>the</span>
  <span m=''3074080''>cut</span> <span m=''3074290''>line</span> <span m=''3074910''>and</span>
  <span m=''3075060''>the</span> <span m=''3075210''>yellow</span> <span m=''3075370''>stuff</span>
  <span m=''3075610''>will</span> <span m=''3075690''>be</span> <span m=''3075830''>below</span>
  <span m=''3076110''>the</span> <span m=''3076220''>cut</span> <span m=''3076430''>line.</span>
  </p><p><span m=''3077150''>In</span> <span m=''3077250''>general,</span> <span m=''3077670''>this</span>
  <span m=''3077720''>is</span> <span m=''3077800''>called</span> <span m=''3078000''>a</span>
  <span m=''3078050''>side</span> <span m=''3078340''>assignment.</span> <span m=''3078770''>You</span>
  <span m=''3078850''>have</span> <span m=''3078940''>a</span> <span m=''3079000''>bunch</span>
  <span m=''3079240''>of</span> <span m=''3079330''>regions</span> <span m=''3079700''>you</span>
  <span m=''3079800''>decide</span> <span m=''3080160''>which</span> <span m=''3080330''>ones</span>
  <span m=''3080560''>you</span> <span m=''3080690''>want</span> <span m=''3080820''>to</span>
  <span m=''3080860''>be</span> <span m=''3080960''>above</span> <span m=''3081270''>and</span>
  <span m=''3081330''>which</span> <span m=''3081500''>ones</span> <span m=''3081690''>you</span>
  <span m=''3081820''>want</span> <span m=''3081930''>to</span> <span m=''3081970''>be</span>
  <span m=''3082090''>below.</span> <span m=''3083190''>And</span> <span m=''3083390''>usually,</span>
  <span m=''3083930''>you</span> <span m=''3084050''>have</span> <span m=''3084270''>polygons,</span>
  <span m=''3084850''>and</span> <span m=''3084980''>you</span> <span m=''3085060''>say</span>
  <span m=''3085210''>the</span> <span m=''3085340''>interiors</span> <span m=''3085880''>are</span>
  <span m=''3085990''>above</span> <span m=''3086360''>and</span> <span m=''3086510''>the</span>
  <span m=''3086630''>exteriors</span> <span m=''3087110''>are</span> <span m=''3087180''>below.</span>
  <span m=''3088530''>But</span> <span m=''3089070''>in</span> <span m=''3089240''>general,</span>
  <span m=''3090350''>you</span> <span m=''3090380''>could</span> <span m=''3090510''>ask</span>
  <span m=''3090670''>for</span> <span m=''3090800''>anything</span> <span m=''3091090''>you</span>
  <span m=''3091200''>want.</span> <span m=''3091770''>You could</span> <span m=''3091880''>say</span>
  <span m=''3092230''>maybe</span> <span m=''3092540''>I</span> <span m=''3092570''>want</span>
  <span m=''3092810''>both</span> <span m=''3093070''>of</span> <span m=''3093150''>these</span>
  <span m=''3093350''>to</span> <span m=''3093440''>be</span> <span m=''3093570''>above.</span>
  <span m=''3094640''>If you</span> <span m=''3094730''>make</span> <span m=''3094900''>both</span>
  <span m=''3095110''>of</span> <span m=''3095170''>them</span> <span m=''3095320''>above,</span>
  <span m=''3095610''>you</span> <span m=''3095740''>have</span> <span m=''3096040''>to</span>
  <span m=''3096150''>valley</span> <span m=''3096580''>fold</span> <span m=''3097040''>along</span>
  <span m=''3097570''>all of</span> <span m=''3097830''>the</span> <span m=''3097900''>cut</span>
  <span m=''3098100''>lines.</span> </p><p><span m=''3099380''>So</span> <span m=''3099510''>if</span>
  <span m=''3099570''>you</span> <span m=''3099670''>do</span> <span m=''3099830''>that--</span>
  <span m=''3100180''>you</span> <span m=''3100260''>say</span> <span m=''3100440''>I</span>
  <span m=''3100480''>want</span> <span m=''3100680''>all</span> <span m=''3100920''>regions</span>
  <span m=''3101260''>to</span> <span m=''3101360''>be</span> <span m=''3101480''>above</span>
  <span m=''3101720''>the</span> <span m=''3101810''>cut</span> <span m=''3102270''>line--</span>
  <span m=''3102370''>you can</span> <span m=''3102510''>still</span> <span m=''3102770''>line</span>
  <span m=''3102980''>them</span> <span m=''3103110''>up.</span> <span m=''3103990''>You</span>
  <span m=''3104100''>end</span> <span m=''3104230''>up</span> <span m=''3104330''>folding</span>
  <span m=''3104650''>along</span> <span m=''3104860''>all</span> <span m=''3104950''>the</span>
  <span m=''3105030''>cut</span> <span m=''3105220''>edges</span> <span m=''3105480''>with</span>
  <span m=''3105610''>valleys.</span> <span m=''3107010''>And</span> <span m=''3107220''>then</span>
  <span m=''3108230''>wrap</span> <span m=''3108470''>around</span> <span m=''3108660''>is</span>
  <span m=''3108720''>super</span> <span m=''3108940''>easy.</span> <span m=''3111280''>We</span>
  <span m=''3111330''>take</span> <span m=''3111530''>this</span> <span m=''3111690''>thing,</span>
  <span m=''3111910''>and in</span> <span m=''3112000''>fact,</span> <span m=''3112290''>everyone''s</span>
  <span m=''3112780''>folding</span> <span m=''3113090''>along</span> <span m=''3113350''>the</span>
  <span m=''3113420''>black</span> <span m=''3113690''>lines.</span> <span m=''3114520''>So</span>
  <span m=''3114730''>really</span> <span m=''3114970''>everybody</span> <span m=''3115410''>comes</span>
  <span m=''3115690''>down</span> <span m=''3115930''>to</span> <span m=''3116010''>the</span>
  <span m=''3116120''>floor,</span> <span m=''3117550''>and</span> <span m=''3117720''>then</span>
  <span m=''3117880''>the</span> <span m=''3117980''>wrap</span> <span m=''3118210''>around</span>
  <span m=''3118410''>is</span> <span m=''3118490''>just</span> <span m=''3118720''>underneath</span>
  <span m=''3119130''>the</span> <span m=''3119200''>floor</span> <span m=''3120090''>and</span>
  <span m=''3120850''>life</span> <span m=''3121070''>is</span> <span m=''3121200''>good.</span>
  </p><p><span m=''3122610''>So</span> <span m=''3122680''>that''s</span> <span m=''3122900''>one</span>
  <span m=''3123060''>way</span> <span m=''3123190''>to</span> <span m=''3123300''>deal</span>
  <span m=''3123510''>with</span> <span m=''3123660''>this</span> <span m=''3124460''>case,</span>
  <span m=''3124880''>and</span> <span m=''3125080''>you</span> <span m=''3125160''>have</span>
  <span m=''3125250''>to</span> <span m=''3125340''>prove</span> <span m=''3125670''>that</span>
  <span m=''3125830''>works.</span> <span m=''3126250''>It''s</span> <span m=''3126290''>complicated.</span>
  <span m=''3129190''>I</span> <span m=''3129330''>would</span> <span m=''3129450''>rather</span>
  <span m=''3129720''>go</span> <span m=''3129850''>onto</span> <span m=''3130350''>other</span>
  <span m=''3130540''>topics.</span> </p><p><span m=''3133270''>I</span> <span m=''3133580''>do</span>
  <span m=''3133670''>think</span> <span m=''3133940''>this would</span> <span m=''3134030''>make</span>
  <span m=''3134200''>a</span> <span m=''3134260''>fun</span> <span m=''3134770''>project.</span>
  <span m=''3137040''>It''s</span> <span m=''3137210''>not</span> <span m=''3137430''>easy</span>
  <span m=''3139060''>to</span> <span m=''3139260''>make</span> <span m=''3139470''>these</span>
  <span m=''3139640''>crease</span> <span m=''3139830''>patterns.</span> <span m=''3140200''>Currently</span>
  <span m=''3140520''>we</span> <span m=''3140650''>draw</span> <span m=''3140850''>them</span>
  <span m=''3141030''>always</span> <span m=''3141430''>by</span> <span m=''3141580''>hand,</span>
  <span m=''3142050''>meaning</span> <span m=''3142310''>with</span> <span m=''3142450''>the</span>
  <span m=''3142550''>fancy</span> <span m=''3142910''>drawing</span> <span m=''3143190''>program</span>
  <span m=''3143500''>that</span> <span m=''3143570''>knows</span> <span m=''3143790''>how</span>
  <span m=''3143870''>to</span> <span m=''3143980''>do</span> <span m=''3144060''>angular</span>
  <span m=''3144360''>bisectors.</span> <span m=''3147470''>And</span> <span m=''3147910''>it''s</span>
  <span m=''3148340''>an</span> <span m=''3148450''>art</span> <span m=''3148820''>to</span>
  <span m=''3149340''>move</span> <span m=''3149620''>around</span> <span m=''3149920''>the</span>
  <span m=''3150000''>points</span> <span m=''3150590''>so</span> <span m=''3150830''>that</span>
  <span m=''3151750''>you</span> <span m=''3151900''>get</span> <span m=''3152070''>lots</span>
  <span m=''3152310''>of</span> <span m=''3152390''>alignments.</span> </p><p><span
  m=''3152930''>Like</span> <span m=''3153080''>when</span> <span m=''3153220''>you</span>
  <span m=''3153350''>get</span> <span m=''3153940''>four</span> <span m=''3154250''>straight</span>
  <span m=''3154480''>skeleton</span> <span m=''3155060''>edges</span> <span m=''3155340''>coming</span>
  <span m=''3155590''>together,</span> <span m=''3155920''>that</span> <span m=''3156100''>means</span>
  <span m=''3156260''>you</span> <span m=''3156340''>get</span> <span m=''3156530''>fewer</span>
  <span m=''3156840''>creases.</span> <span m=''3157240''>That''s</span> <span m=''3157440''>a</span>
  <span m=''3157500''>good</span> <span m=''3157720''>thing</span> <span m=''3158140''>whenever</span>
  <span m=''3158440''>you</span> <span m=''3158550''>can</span> <span m=''3158640''>make</span>
  <span m=''3158810''>that</span> <span m=''3158940''>happen.</span> <span m=''3159850''>So</span>
  <span m=''3159910''>when</span> <span m=''3160640''>you</span> <span m=''3160820''>could</span>
  <span m=''3161750''>give</span> <span m=''3161910''>me</span> <span m=''3162000''>software</span>
  <span m=''3162390''>to</span> <span m=''3162440''>help</span> <span m=''3162630''>do</span>
  <span m=''3162750''>that,</span> <span m=''3163470''>I</span> <span m=''3163660''>would</span>
  <span m=''3163800''>love</span> <span m=''3164280''>you.</span> </p><p><span m=''3167980''>So</span>
  <span m=''3168500''>let''s</span> <span m=''3169810''>move</span> <span m=''3169990''>on.</span>
  <span m=''3171260''>Any</span> <span m=''3171420''>questions</span> <span m=''3171840''>about</span>
  <span m=''3172080''>the</span> <span m=''3172160''>straight</span> <span m=''3172430''>skeleton</span>
  <span m=''3172830''>method?</span> <span m=''3173240''>Now</span> <span m=''3173410''>I''m</span>
  <span m=''3173510''>going</span> <span m=''3173660''>to</span> <span m=''3173760''>switch</span>
  <span m=''3174120''>over</span> <span m=''3175050''>to</span> <span m=''3175150''>disk</span>
  <span m=''3175400''>packing.</span> <span m=''3178758''>All right.</span> <span
  m=''3181180''>Same</span> <span m=''3181370''>problem,</span> <span m=''3183420''>but</span>
  <span m=''3183610''>now</span> <span m=''3184160''>I''ll</span> <span m=''3184280''>give</span>
  <span m=''3184400''>you</span> <span m=''3184480''>a</span> <span m=''3184520''>method</span>
  <span m=''3186040''>that</span> <span m=''3186190''>always</span> <span m=''3186400''>works</span>
  <span m=''3188310''>in</span> <span m=''3188510''>theory.</span> <span m=''3190300''>Just</span>
  <span m=''3193520''>difficult</span> <span m=''3193970''>in</span> <span m=''3194090''>practice.</span>
  </p><p><span m=''3199060''>I</span> <span m=''3199180''>think</span> <span m=''3199420''>this</span>
  <span m=''3199610''>is</span> <span m=''3199760''>good</span> <span m=''3199940''>chalk</span>
  <span m=''3200550''>because</span> <span m=''3201000''>it''s</span> <span m=''3201190''>yellow.</span>
  <span m=''3203710''>Generally,</span> <span m=''3204030''>if</span> <span m=''3204350''>it''s</span>
  <span m=''3204560''>yellow</span> <span m=''3204820''>on</span> <span m=''3204910''>the</span>
  <span m=''3205000''>outside</span> <span m=''3205410''>it</span> <span m=''3205560''>is</span>
  <span m=''3206630''>railroad</span> <span m=''3207160''>chalk,</span> <span m=''3207550''>which</span>
  <span m=''3207760''>is the</span> <span m=''3207870''>good</span> <span m=''3208030''>stuff.</span>
  <span m=''3208320''>But,</span> <span m=''3208950''>what the</span> <span m=''3209170''>problem</span>
  <span m=''3209480''>is--</span> <span m=''3209730''>we</span> <span m=''3209840''>have</span>
  <span m=''3209940''>bad</span> <span m=''3210160''>erasers.</span> <span m=''3212040''>It''s</span>
  <span m=''3212470''>persistence</span> <span m=''3212980''>of</span> <span m=''3213060''>vision.</span>
  <span m=''3213480''>You</span> <span m=''3213600''>just</span> <span m=''3213930''>get
  to</span> <span m=''3214010''>remember</span> <span m=''3214440''>what</span> <span
  m=''3214560''>I</span> <span m=''3214610''>used</span> <span m=''3214820''>to</span>
  <span m=''3214900''>write.</span> </p><p><span m=''3231220''>I</span> <span m=''3231370''>don''t
  want</span> <span m=''3231520''>to</span> <span m=''3231600''>write</span> <span
  m=''3231840''>down</span> <span m=''3232060''>the</span> <span m=''3232190''>algorithms.</span>
  <span m=''3232750''>It''s</span> <span m=''3233170''>complicated.</span> <span m=''3235040''>I</span>
  <span m=''3235170''>want</span> <span m=''3235370''>to</span> <span m=''3235720''>give</span>
  <span m=''3235880''>you</span> <span m=''3236000''>a</span> <span m=''3236020''>visual</span>
  <span m=''3236490''>overview</span> <span m=''3236930''>of</span> <span m=''3237070''>the</span>
  <span m=''3237150''>main</span> <span m=''3237350''>steps.</span> </p><p></p><p><span
  m=''3239240''>I guess there''s</span> <span m=''3240140''>nice</span> <span m=''3240380''>figures</span>
  <span m=''3240860''>do</span> <span m=''3240970''>that</span> <span m=''3241290''>for</span>
  <span m=''3241520''>us.</span> <span m=''3242910''>So</span> <span m=''3244730''>we</span>
  <span m=''3244850''>start</span> <span m=''3245130''>with</span> <span m=''3245910''>a</span>
  <span m=''3245990''>very</span> <span m=''3246210''>complicated</span> <span m=''3246760''>shape</span>
  <span m=''3246980''>we</span> <span m=''3247040''>want</span> <span m=''3247200''>to</span>
  <span m=''3247250''>make,</span> <span m=''3247990''>like</span> <span m=''3248200''>this</span>
  <span m=''3248380''>quadrilateral.</span> <span m=''3249740''>And</span> <span m=''3251390''>you</span>
  <span m=''3251590''>can</span> <span m=''3251720''>see</span> <span m=''3251880''>disk</span>
  <span m=''3252130''>packing</span> <span m=''3252530''>is involved.</span> <span
  m=''3253510''>The</span> <span m=''3253680''>very</span> <span m=''3253970''>first</span>
  <span m=''3254270''>thing</span> <span m=''3254470''>we</span> <span m=''3254580''>do--</span>
  <span m=''3254800''>and</span> <span m=''3254880''>I''ll</span> <span m=''3255040''>tell</span>
  <span m=''3255230''>you</span> <span m=''3255370''>why</span> <span m=''3255740''>in</span>
  <span m=''3255900''>a</span> <span m=''3255940''>moment--</span> <span m=''3256660''>is</span>
  <span m=''3256910''>thicken</span> <span m=''3258240''>the</span> <span m=''3258380''>graph</span>
  <span m=''3258740''>you</span> <span m=''3258870''>want</span> <span m=''3259020''>to</span>
  <span m=''3259080''>build.</span> <span m=''3259690''>So</span> <span m=''3259730''>maybe</span>
  <span m=''3259950''>it''s a</span> <span m=''3260060''>polygon,</span> <span m=''3260470''>maybe</span>
  <span m=''3260650''>it''s</span> <span m=''3260750''>a</span> <span m=''3260800''>graph--</span>
  <span m=''3261100''>I''ll</span> <span m=''3261190''>think</span> <span m=''3261350''>about</span>
  <span m=''3261540''>the</span> <span m=''3261610''>polygon</span> <span m=''3262050''>case</span>
  <span m=''3262250''>for</span> <span m=''3262350''>now</span> <span m=''3262520''>because</span>
  <span m=''3262680''>it''s</span> <span m=''3262820''>easier,</span> <span m=''3264120''>then</span>
  <span m=''3264260''>I''ll</span> <span m=''3264440''>come</span> <span m=''3264620''>back</span>
  <span m=''3264830''>to</span> <span m=''3264910''>the</span> <span m=''3265000''>general</span>
  <span m=''3265280''>case.</span> </p><p><span m=''3265610''>I</span> <span m=''3265690''>thicken</span>
  <span m=''3266010''>it</span> <span m=''3266160''>by</span> <span m=''3266350''>tiny</span>
  <span m=''3266800''>epsilon.</span> <span m=''3268980''>Just</span> <span m=''3269180''>offset</span>
  <span m=''3269550''>in</span> <span m=''3269630''>both</span> <span m=''3269820''>directions.</span>
  <span m=''3270240''>Just</span> <span m=''3270450''>like</span> <span m=''3270630''>as</span>
  <span m=''3270770''>if</span> <span m=''3270890''>you''re</span> <span m=''3271030''>starting</span>
  <span m=''3271500''>the</span> <span m=''3271570''>straight</span> <span m=''3271800''>skeleton</span>
  <span m=''3272050''>method,</span> <span m=''3272400''>but</span> <span m=''3272530''>then</span>
  <span m=''3272640''>you</span> <span m=''3272740''>stop</span> <span m=''3273080''>after</span>
  <span m=''3273340''>epsilon.</span> <span m=''3274090''>No</span> <span m=''3274380''>events</span>
  <span m=''3274670''>happen</span> <span m=''3275630''>in</span> <span m=''3275790''>epsilon</span>
  <span m=''3276240''>time.</span> </p><p><span m=''3278880''>OK,</span> <span m=''3280950''>then</span>
  <span m=''3281630''>I</span> <span m=''3281690''>have</span> <span m=''3281870''>this</span>
  <span m=''3282030''>picture--</span> <span m=''3283080''>the</span> <span m=''3283170''>purple</span>
  <span m=''3283500''>stuff,</span> <span m=''3284740''>pink</span> <span m=''3285030''>stuff,</span>
  <span m=''3285430''>whatever.</span> <span m=''3285750''>Magenta.</span> <span m=''3286960''>50%</span>
  <span m=''3287690''>magenta.</span> <span m=''3288160''>I happen</span> <span m=''3288440''>to</span>
  <span m=''3288540''>know</span> <span m=''3289560''>I drew</span> <span m=''3289680''>this</span>
  <span m=''3289860''>figure.</span> </p><p><span m=''3291390''>Now</span> <span m=''3291650''>I''m</span>
  <span m=''3291780''>going</span> <span m=''3291900''>to</span> <span m=''3292070''>take</span>
  <span m=''3292310''>some</span> <span m=''3292500''>50%</span> <span m=''3293070''>cyan</span>
  <span m=''3294750''>disks</span> <span m=''3295460''>and</span> <span m=''3295670''>pack</span>
  <span m=''3296120''>them</span> <span m=''3296500''>to</span> <span m=''3296620''>fill</span>
  <span m=''3296830''>this</span> <span m=''3297000''>region.</span> <span m=''3297370''>Now</span>
  <span m=''3297560''>what</span> <span m=''3297720''>I</span> <span m=''3297780''>want--</span>
  <span m=''3298660''>there''s</span> <span m=''3298830''>three</span> <span m=''3299090''>properties</span>
  <span m=''3299550''>I</span> <span m=''3299620''>want.</span> <span m=''3299930''>One</span>
  <span m=''3300110''>is</span> <span m=''3300210''>that</span> <span m=''3300360''>every</span>
  <span m=''3300690''>vertex,</span> <span m=''3301870''>but</span> <span m=''3302130''>you</span>
  <span m=''3302290''>have</span> <span m=''3302400''>to</span> <span m=''3302510''>think</span>
  <span m=''3302690''>about</span> <span m=''3302860''>each</span> <span m=''3303020''>region</span>
  <span m=''3303370''>separately</span> <span m=''3303680''>which</span> <span m=''3303990''>is</span>
  <span m=''3304250''>a</span> <span m=''3304270''>little</span> <span m=''3304470''>bit</span>
  <span m=''3304610''>confusing.</span> <span m=''3305290''>Let''s</span> <span m=''3305420''>think</span>
  <span m=''3305560''>about</span> <span m=''3305720''>the</span> <span m=''3305850''>outside.</span>
  <span m=''3306120''>It''s a</span> <span m=''3306390''>little</span> <span m=''3306650''>easier.</span>
  <span m=''3307100''>Bigger.</span> </p><p><span m=''3308680''>Every</span> <span
  m=''3308960''>vertex</span> <span m=''3309820''>of</span> <span m=''3310000''>this</span>
  <span m=''3310570''>graph</span> <span m=''3311000''>on</span> <span m=''3311060''>the</span>
  <span m=''3311170''>outside</span> <span m=''3312180''>should</span> <span m=''3312380''>be</span>
  <span m=''3312510''>the</span> <span m=''3312630''>center</span> <span m=''3313110''>of</span>
  <span m=''3313230''>a</span> <span m=''3313300''>disk.</span> <span m=''3314040''>There''s</span>
  <span m=''3314250''>a</span> <span m=''3314320''>disk</span> <span m=''3315070''>center</span>
  <span m=''3315410''>here.</span> <span m=''3316100''>There''s</span> <span m=''3316210''>a</span>
  <span m=''3316350''>disk center</span> <span m=''3316780''>here.</span> <span m=''3317520''>there''s</span>
  <span m=''3317570''>a disk</span> <span m=''3317680''>center</span> <span m=''3317930''>here,</span>
  <span m=''3318560''>and a</span> <span m=''3318630''>disk</span> <span m=''3318720''>center</span>
  <span m=''3318990''>there.</span> <span m=''3319930''>On</span> <span m=''3320030''>the</span>
  <span m=''3320130''>inside</span> <span m=''3320500''>it''s</span> <span m=''3320600''>also</span>
  <span m=''3320850''>true,</span> <span m=''3321090''>they''re</span> <span m=''3321220''>just</span>
  <span m=''3321480''>different</span> <span m=''3321760''>disks.</span> <span m=''3323680''>Then</span>
  <span m=''3323850''>also</span> <span m=''3324160''>I</span> <span m=''3324250''>want</span>
  <span m=''3324550''>the</span> <span m=''3324790''>edges</span> <span m=''3325880''>of</span>
  <span m=''3325980''>the</span> <span m=''3326060''>graph</span> <span m=''3326370''>to</span>
  <span m=''3326550''>be</span> <span m=''3326760''>covered</span> <span m=''3327740''>by
  a</span> <span m=''3327940''>radii</span> <span m=''3328660''>of</span> <span m=''3328820''>disks.</span>
  </p><p><span m=''3329855''>And</span> <span m=''3330290''>so</span> <span m=''3330390''>here''s</span>
  <span m=''3330500''>a</span> <span m=''3330590''>radius</span> <span m=''3330970''>of</span>
  <span m=''3331060''>one</span> <span m=''3331250''>disk.</span> <span m=''3331950''>Here''s</span>
  <span m=''3332280''>a</span> <span m=''3332350''>diameter</span> <span m=''3332890''>of</span>
  <span m=''3332950''>a</span> <span m=''3333010''>disc.</span> <span m=''3333800''>Here''s</span>
  <span m=''3333910''>a</span> <span m=''3333980''>radius</span> <span m=''3334320''>of</span>
  <span m=''3334420''>a</span> <span m=''3334480''>disk</span> <span m=''3334850''>that</span>
  <span m=''3335110''>covers</span> <span m=''3335680''>the</span> <span m=''3335770''>edge.</span>
  <span m=''3336820''>So</span> <span m=''3336940''>in</span> <span m=''3337000''>other</span>
  <span m=''3337150''>words,</span> <span m=''3337440''>I</span> <span m=''3337540''>want</span>
  <span m=''3337620''>to</span> <span m=''3337760''>fill--</span> <span m=''3338970''>along</span>
  <span m=''3339390''>the</span> <span m=''3339530''>edge</span> <span m=''3339770''>I</span>
  <span m=''3339810''>want</span> <span m=''3339950''>to</span> <span m=''3339990''>have</span>
  <span m=''3340180''>a</span> <span m=''3340230''>bunch</span> <span m=''3340500''>of</span>
  <span m=''3340570''>centers</span> <span m=''3341820''>so</span> <span m=''3342010''>that
  I</span> <span m=''3342220''>completely</span> <span m=''3342900''>cover</span>
  <span m=''3343330''>that</span> <span m=''3343570''>edge</span> <span m=''3343760''>with</span>
  <span m=''3343960''>blue.</span> <span m=''3344680''>You''ll</span> <span m=''3344790''>see</span>
  <span m=''3344980''>why</span> <span m=''3346070''>later.</span> <span m=''3346410''>Question?</span>
  </p><p><span m=''3351960''>The</span> <span m=''3352090''>disks</span> <span m=''3352360''>have</span>
  <span m=''3352560''>to</span> <span m=''3352670''>be</span> <span m=''3352780''>non-overlapping.</span>
  <span m=''3354630''>These</span> <span m=''3354940''>properties</span> <span m=''3355340''>are</span>
  <span m=''3355400''>actually</span> <span m=''3355640''>quite</span> <span m=''3356210''>challenging</span>
  <span m=''3356830''>to</span> <span m=''3356940''>achieve.</span> <span m=''3357750''>Your</span>
  <span m=''3357850''>question</span> <span m=''3358130''>is</span> <span m=''3358230''>why</span>
  <span m=''3358420''>do</span> <span m=''3358520''>we</span> <span m=''3358620''>use</span>
  <span m=''3358730''>small</span> <span m=''3359010''>disks.</span> <span m=''3363360''>Disk,</span>
  <span m=''3363780''>because</span> <span m=''3363910''>if</span> <span m=''3364050''>I</span>
  <span m=''3364120''>had</span> <span m=''3364300''>a</span> <span m=''3364360''>big</span>
  <span m=''3364630''>disk</span> <span m=''3364930''>here,</span> <span m=''3365680''>it</span>
  <span m=''3365820''>would</span> <span m=''3365970''>intersect</span> <span m=''3366520''>this</span>
  <span m=''3366720''>disk.</span> <span m=''3369990''>Now</span> <span m=''3370100''>I</span>
  <span m=''3370170''>didn''t</span> <span m=''3370410''>have</span> <span m=''3370580''>to</span>
  <span m=''3370670''>make</span> <span m=''3370890''>that</span> <span m=''3371120''>disk</span>
  <span m=''3371455''>so big,</span> <span m=''3371790''>but</span> <span m=''3371950''>if</span>
  <span m=''3372060''>I</span> <span m=''3372100''>made</span> <span m=''3372280''>that</span>
  <span m=''3372440''>one</span> <span m=''3372560''>smaller,</span> <span m=''3372980''>I''d</span>
  <span m=''3373030''>have</span> <span m=''3373160''>to</span> <span m=''3373230''>have</span>
  <span m=''3373350''>more</span> <span m=''3373540''>disks</span> <span m=''3373850''>here.</span>
  <span m=''3376500''>Or</span> <span m=''3376640''>here</span> <span m=''3376900''>there''s</span>
  <span m=''3377100''>also</span> <span m=''3377320''>two</span> <span m=''3377480''>small</span>
  <span m=''3377740''>disks.</span> <span m=''3377890''>That</span> <span m=''3378090''>one</span>
  <span m=''3378530''>I</span> <span m=''3379540''>probably</span> <span m=''3379920''>could</span>
  <span m=''3380090''>have</span> <span m=''3380200''>gotten</span> <span m=''3380420''>away</span>
  <span m=''3380660''>with</span> <span m=''3380840''>a</span> <span m=''3380900''>bigger</span>
  <span m=''3381150''>disk.</span> </p><p><span m=''3383420''>Oh,</span> <span m=''3383540''>no,</span>
  <span m=''3383710''>but</span> <span m=''3383850''>then</span> <span m=''3383990''>on</span>
  <span m=''3384070''>the</span> <span m=''3384160''>inside</span> <span m=''3384510''>you</span>
  <span m=''3384560''>have</span> <span m=''3384690''>a</span> <span m=''3384760''>problem.</span>
  <span m=''3386490''>So</span> <span m=''3386570''>these</span> <span m=''3386780''>guys</span>
  <span m=''3386940''>actually</span> <span m=''3387190''>have</span> <span m=''3387340''>to</span>
  <span m=''3387430''>match</span> <span m=''3387770''>up.</span> <span m=''3388070''>That''s</span>
  <span m=''3388190''>another</span> <span m=''3388450''>constraint.</span> <span
  m=''3389250''>And</span> <span m=''3389290''>the</span> <span m=''3389400''>inside</span>
  <span m=''3389710''>and</span> <span m=''3389770''>the</span> <span m=''3389860''>outside</span>
  <span m=''3390150''>have</span> <span m=''3390270''>to</span> <span m=''3390360''>match</span>
  <span m=''3390600''>up.</span> <span m=''3390730''>Here</span> <span m=''3390880''>there''s</span>
  <span m=''3391050''>a</span> <span m=''3391100''>slight</span> <span m=''3391400''>change</span>
  <span m=''3391650''>in</span> <span m=''3391740''>radii</span> <span m=''3392370''>to</span>
  <span m=''3392640''>compensate</span> <span m=''3393080''>for</span> <span m=''3393150''>the</span>
  <span m=''3393240''>epsilon.</span> <span m=''3393560''>Along</span> <span m=''3393800''>the</span>
  <span m=''3393900''>edges</span> <span m=''3394230''>they''re</span> <span m=''3394330''>exactly</span>
  <span m=''3394700''>the</span> <span m=''3394820''>same.</span> <span m=''3395810''>So</span>
  <span m=''3395850''>if</span> <span m=''3395970''>I</span> <span m=''3396050''>made</span>
  <span m=''3396310''>this</span> <span m=''3396480''>one</span> <span m=''3396830''>a</span>
  <span m=''3396920''>big</span> <span m=''3397160''>disk,</span> <span m=''3397850''>it</span>
  <span m=''3397980''>would</span> <span m=''3398080''>overlap</span> <span m=''3398460''>this</span>
  <span m=''3398650''>one.</span> <span m=''3399030''>So</span> <span m=''3399150''>I</span>
  <span m=''3399220''>could</span> <span m=''3399410''>make</span> <span m=''3399550''>that</span>
  <span m=''3399690''>one</span> <span m=''3399800''>smaller,</span> <span m=''3400290''>but</span>
  <span m=''3400470''>then--</span> <span m=''3401120''>other</span> <span m=''3401340''>problems.</span>
  </p><p><span m=''3402960''>So</span> <span m=''3403000''>you</span> <span m=''3403050''>have</span>
  <span m=''3403190''>to</span> <span m=''3403310''>simultaneously</span> <span m=''3404000''>balance</span>
  <span m=''3404320''>all</span> <span m=''3404410''>these</span> <span m=''3404560''>constraints,</span>
  <span m=''3405010''>which</span> <span m=''3405190''>is</span> <span m=''3405820''>a
  bit</span> <span m=''3405930''>exciting.</span> <span m=''3408270''>What</span>
  <span m=''3408500''>else?</span> <span m=''3408860''>The</span> <span m=''3408920''>discs</span>
  <span m=''3409150''>don''t</span> <span m=''3409280''>overlap.</span> <span m=''3410300''>And
  the</span> <span m=''3410400''>last</span> <span m=''3410700''>property</span> <span
  m=''3411010''>is that</span> <span m=''3411250''>the</span> <span m=''3411340''>gaps</span>
  <span m=''3411850''>between</span> <span m=''3412220''>the</span> <span m=''3412310''>disks</span>
  <span m=''3413240''>have</span> <span m=''3413490''>always</span> <span m=''3414000''>three</span>
  <span m=''3414610''>or</span> <span m=''3414700''>four</span> <span m=''3415010''>sides.</span>
  <span m=''3416970''>Why?</span> <span m=''3418010''>Because</span> <span m=''3418900''>I</span>
  <span m=''3419000''>want it</span> <span m=''3419390''>to.</span> <span m=''3419970''>It
  will</span> <span m=''3420280''>make</span> <span m=''3420550''>life</span> <span
  m=''3420830''>easier.</span> <span m=''3421770''>You</span> <span m=''3421910''>could</span>
  <span m=''3422160''>try</span> <span m=''3422410''>to</span> <span m=''3422520''>deal</span>
  <span m=''3422780''>with</span> <span m=''3423070''>more</span> <span m=''3423310''>sides,</span>
  <span m=''3423730''>but</span> <span m=''3425400''>three</span> <span m=''3425600''>and</span>
  <span m=''3425680''>four</span> <span m=''3426330''>is</span> <span m=''3426480''>nice.</span>
  <span m=''3428370''>Yeah,</span> <span m=''3428790''>I''ll</span> <span m=''3428950''>get</span>
  <span m=''3429110''>to</span> <span m=''3429200''>that.</span> </p><p><span m=''3430530''>Why</span>
  <span m=''3430770''>do</span> <span m=''3430870''>we</span> <span m=''3431000''>care</span>
  <span m=''3431270''>about</span> <span m=''3431530''>number</span> <span m=''3431760''>of</span>
  <span m=''3431810''>sides?</span> <span m=''3432240''>Because</span> <span m=''3432750''>I''m</span>
  <span m=''3432920''>going</span> <span m=''3433190''>to</span> <span m=''3433780''>draw</span>
  <span m=''3434060''>a</span> <span m=''3434110''>graph.</span> <span m=''3434820''>I''m</span>
  <span m=''3434950''>going</span> <span m=''3435040''>to</span> <span m=''3435110''>subdivide</span>
  <span m=''3435810''>my</span> <span m=''3435930''>original</span> <span m=''3436340''>graph</span>
  <span m=''3436630''>here</span> <span m=''3437030''>with</span> <span m=''3437270''>these</span>
  <span m=''3437500''>red</span> <span m=''3437710''>lines</span> <span m=''3438800''>to</span>
  <span m=''3438960''>say</span> <span m=''3439270''>whenever</span> <span m=''3439780''>disks</span>
  <span m=''3440630''>kiss,</span> <span m=''3441210''>I</span> <span m=''3441340''>will</span>
  <span m=''3441500''>draw--</span> <span m=''3442060''>connect</span> <span m=''3442340''>the</span>
  <span m=''3442430''>centers</span> <span m=''3442860''>of</span> <span m=''3442980''>those</span>
  <span m=''3443510''>disks.</span> </p><p><span m=''3446660''>And</span> <span m=''3447060''>because</span>
  <span m=''3447820''>these</span> <span m=''3448160''>gaps</span> <span m=''3448860''>always</span>
  <span m=''3449110''>have</span> <span m=''3449270''>three</span> <span m=''3449440''>or</span>
  <span m=''3449500''>four</span> <span m=''3449720''>sides--</span> <span m=''3451570''>it''s</span>
  <span m=''3451830''>not</span> <span m=''3452030''>the</span> <span m=''3452090''>best</span>
  <span m=''3452320''>example.</span> <span m=''3452620''>Here''s</span> <span m=''3452870''>like</span>
  <span m=''3453050''>three</span> <span m=''3453240''>sides.</span> <span m=''3454230''>The</span>
  <span m=''3455000''>red</span> <span m=''3455210''>lines</span> <span m=''3455450''>I</span>
  <span m=''3455500''>draw</span> <span m=''3455830''>will</span> <span m=''3456230''>outline</span>
  <span m=''3456430''>a</span> <span m=''3456490''>triangle.</span> <span m=''3456990''>Whenever</span>
  <span m=''3457300''>I have</span> <span m=''3457400''>three</span> <span m=''3457580''>sides,</span>
  <span m=''3458270''>whenever</span> <span m=''3458610''>I have</span> <span m=''3458650''>four</span>
  <span m=''3458940''>sides,</span> <span m=''3459800''>I''ll</span> <span m=''3459930''>have</span>
  <span m=''3460130''>a</span> <span m=''3460180''>quadrilateral.</span> <span m=''3461520''>So</span>
  <span m=''3461730''>I''ve subdivided</span> <span m=''3462490''>my</span> <span
  m=''3462700''>regions</span> <span m=''3463300''>into</span> <span m=''3463540''>triangles</span>
  <span m=''3464040''>and</span> <span m=''3464130''>quadrilaterals.</span> <span
  m=''3465820''>OK,</span> <span m=''3466220''>you</span> <span m=''3466330''>have</span>
  <span m=''3466440''>to</span> <span m=''3466540''>believe</span> <span m=''3466960''>that
  this</span> <span m=''3467150''>is</span> <span m=''3467240''>possible.</span> <span
  m=''3468300''>I</span> <span m=''3468440''>can</span> <span m=''3468650''>sketch</span>
  <span m=''3468970''>an</span> <span m=''3469060''>algorithm</span> <span m=''3469440''>for</span>
  <span m=''3469660''>you,</span> <span m=''3470700''>which</span> <span m=''3470950''>is</span>
  <span m=''3471020''>you</span> <span m=''3471130''>draw a</span> <span m=''3471560''>tiny</span>
  <span m=''3471980''>disk</span> <span m=''3472930''>at</span> <span m=''3473100''>each</span>
  <span m=''3473300''>of</span> <span m=''3473400''>the</span> <span m=''3473490''>corners,</span>
  <span m=''3475020''>and</span> <span m=''3475150''>then</span> <span m=''3475250''>you</span>
  <span m=''3475330''>draw</span> <span m=''3475480''>lots</span> <span m=''3475750''>of</span>
  <span m=''3475830''>tiny</span> <span m=''3476100''>this</span> <span m=''3476330''>along</span>
  <span m=''3476590''>the</span> <span m=''3476710''>edges</span> <span m=''3477070''>to</span>
  <span m=''3477180''>fill</span> <span m=''3477380''>the</span> <span m=''3477500''>edges.</span>
  </p><p><span m=''3478850''>And</span> <span m=''3479020''>that</span> <span m=''3479150''>will</span>
  <span m=''3479240''>satisfy</span> <span m=''3479690''>everything.</span> <span
  m=''3480400''>I</span> <span m=''3480430''>mean</span> <span m=''3480550''>the</span>
  <span m=''3480630''>disks</span> <span m=''3480900''>will be</span> <span m=''3481010''>non-overlapping</span>
  <span m=''3481670''>because</span> <span m=''3481840''>they''re</span> <span m=''3481950''>super</span>
  <span m=''3482210''>tiny.</span> <span m=''3482550''>They won''t</span> <span m=''3482790''>get</span>
  <span m=''3482960''>near</span> <span m=''3483190''>any</span> <span m=''3483360''>other</span>
  <span m=''3483520''>disks from</span> <span m=''3483940''>some</span> <span m=''3484140''>other</span>
  <span m=''3484320''>side.</span> <span m=''3485390''>And</span> <span m=''3486540''>what</span>
  <span m=''3486780''>other</span> <span m=''3487000''>good</span> <span m=''3487190''>things?</span>
  <span m=''3487650''>Oh,</span> <span m=''3487980''>but the</span> <span m=''3488310''>regions</span>
  <span m=''3488710''>will</span> <span m=''3488840''>be</span> <span m=''3489140''>ginormous.</span>
  <span m=''3489860''>They</span> <span m=''3489950''>won''t</span> <span m=''3490160''>have</span>
  <span m=''3490320''>three</span> <span m=''3490460''>or</span> <span m=''3490520''>four</span>
  <span m=''3490670''>sides.</span> <span m=''3491080''>They''ll have</span> <span
  m=''3491420''>100</span> <span m=''3491750''>sides,</span> <span m=''3492140''>a
  million</span> <span m=''3492440''>sides--</span> <span m=''3492770''>who</span>
  <span m=''3492850''>knows.</span> </p><p><span m=''3494000''>Well,</span> <span
  m=''3494660''>whenever</span> <span m=''3495010''>you</span> <span m=''3495110''>have</span>
  <span m=''3495340''>some</span> <span m=''3495800''>crazy</span> <span m=''3496270''>region</span>
  <span m=''3498050''>outlined</span> <span m=''3498460''>by</span> <span m=''3498580''>disks--</span>
  <span m=''3499550''>might</span> <span m=''3499790''>not</span> <span m=''3500230''>be</span>
  <span m=''3500360''>convex.</span> <span m=''3500830''>Whatever--</span> <span m=''3501780''>just</span>
  <span m=''3501960''>draw</span> <span m=''3502210''>the</span> <span m=''3502330''>biggest</span>
  <span m=''3502820''>disk</span> <span m=''3503070''>you</span> <span m=''3503180''>can</span>
  <span m=''3503450''>in</span> <span m=''3503540''>there.</span> <span m=''3505276''>I''ll
  get it</span> <span m=''3505750''>to turn</span> <span m=''3505970''>into</span>
  <span m=''3506140''>a</span> <span m=''3506180''>disk</span> <span m=''3506440''>eventually.</span>
  <span m=''3507890''>That</span> <span m=''3508100''>does</span> <span m=''3508280''>not</span>
  <span m=''3508610''>intersect</span> <span m=''3509080''>anybody,</span> <span m=''3509510''>but</span>
  <span m=''3510200''>if</span> <span m=''3510380''>it''s</span> <span m=''3510520''>the</span>
  <span m=''3510610''>biggest</span> <span m=''3510950''>possible,</span> <span m=''3511500''>it</span>
  <span m=''3511640''>will</span> <span m=''3511840''>actually</span> <span m=''3512200''>touch</span>
  <span m=''3512570''>at</span> <span m=''3512630''>least</span> <span m=''3512880''>three</span>
  <span m=''3513090''>sides.</span> <span m=''3514510''>If you</span> <span m=''3514910''>degenerate,</span>
  <span m=''3515200''>it</span> <span m=''3515490''>might</span> <span m=''3515630''>touch</span>
  <span m=''3515870''>four.</span> </p><p><span m=''3516880''>But</span> <span m=''3517050''>in</span>
  <span m=''3517180''>general,</span> <span m=''3517570''>it</span> <span m=''3517690''>will</span>
  <span m=''3518260''>touch</span> <span m=''3518550''>three</span> <span m=''3518710''>sides,</span>
  <span m=''3519520''>which</span> <span m=''3519610''>will</span> <span m=''3519720''>subdivide</span>
  <span m=''3520270''>that</span> <span m=''3520440''>region</span> <span m=''3520870''>into</span>
  <span m=''3521130''>three</span> <span m=''3521430''>pieces,</span> <span m=''3522470''>and</span>
  <span m=''3522620''>you</span> <span m=''3522710''>can</span> <span m=''3522840''>show</span>
  <span m=''3523030''>that those</span> <span m=''3523300''>pieces</span> <span m=''3523610''>are</span>
  <span m=''3523720''>all</span> <span m=''3523980''>little</span> <span m=''3524180''>bit</span>
  <span m=''3524360''>smaller</span> <span m=''3525280''>than</span> <span m=''3525380''>what</span>
  <span m=''3525500''>you</span> <span m=''3525570''>had</span> <span m=''3525730''>before</span>
  <span m=''3526030''>in</span> <span m=''3526100''>terms</span> <span m=''3526280''>of</span>
  <span m=''3526350''>number</span> <span m=''3526640''>of</span> <span m=''3526690''>sides.</span>
  <span m=''3527480''>Except</span> <span m=''3528070''>when</span> <span m=''3528170''>you</span>
  <span m=''3528260''>start</span> <span m=''3528500''>with</span> <span m=''3528610''>a</span>
  <span m=''3528660''>quadrilateral.</span> <span m=''3529510''>When there''s</span>
  <span m=''3529670''>four</span> <span m=''3529880''>sides,</span> <span m=''3530280''>you''ll</span>
  <span m=''3530470''>get</span> <span m=''3531020''>quadrilaterals</span> <span m=''3531640''>and</span>
  <span m=''3531700''>triangle.</span> </p><p><span m=''3532200''>So</span> <span
  m=''3532240''>you</span> <span m=''3532310''>can''t</span> <span m=''3532530''>go</span>
  <span m=''3532650''>below</span> <span m=''3533000''>three</span> <span m=''3533190''>and</span>
  <span m=''3533300''>four.</span> <span m=''3533930''>It''d be</span> <span m=''3534040''>great</span>
  <span m=''3534290''>if</span> <span m=''3534410''>we</span> <span m=''3534490''>could</span>
  <span m=''3534620''>always</span> <span m=''3534790''>get</span> <span m=''3534940''>down</span>
  <span m=''3535090''>to</span> <span m=''3535400''>three</span> <span m=''3535770''>sides</span>
  <span m=''3536130''>in</span> <span m=''3536220''>every</span> <span m=''3536440''>region,</span>
  <span m=''3537490''>but</span> <span m=''3537620''>we</span> <span m=''3537740''>can</span>
  <span m=''3537840''>get</span> <span m=''3537960''>down</span> <span m=''3538110''>to</span>
  <span m=''3538200''>three</span> <span m=''3538400''>or</span> <span m=''3538460''>four.</span>
  <span m=''3538780''>Anything</span> <span m=''3539130''>bigger</span> <span m=''3539350''>than</span>
  <span m=''3539480''>three</span> <span m=''3539650''>or</span> <span m=''3539710''>four</span>
  <span m=''3539960''>you</span> <span m=''3540050''>can</span> <span m=''3540170''>show.</span>
  <span m=''3540760''>This</span> <span m=''3540940''>will</span> <span m=''3541040''>make</span>
  <span m=''3541210''>it</span> <span m=''3541300''>strictly</span> <span m=''3541620''>smaller.</span>
  </p><p><span m=''3542130''>So</span> <span m=''3542270''>that</span> <span m=''3542440''>is</span>
  <span m=''3542570''>an</span> <span m=''3542810''>algorithm.</span> <span m=''3543420''>It''s
  not</span> <span m=''3543710''>super</span> <span m=''3543960''>efficient,</span>
  <span m=''3544860''>but</span> <span m=''3545060''>it</span> <span m=''3545150''>will</span>
  <span m=''3545290''>find</span> <span m=''3545530''>a</span> <span m=''3545620''>disk</span>
  <span m=''3545800''>packing</span> <span m=''3546160''>with</span> <span m=''3546290''>all</span>
  <span m=''3546420''>these</span> <span m=''3546570''>properties.</span> </p><p><span
  m=''3547510''>Then</span> <span m=''3547670''>we</span> <span m=''3547750''>do</span>
  <span m=''3547860''>the</span> <span m=''3547960''>subdivision.</span> <span m=''3549410''>Now</span>
  <span m=''3549720''>what</span> <span m=''3549820''>do</span> <span m=''3549860''>you</span>
  <span m=''3549930''>think</span> <span m=''3550140''>we''re</span> <span m=''3550240''>going</span>
  <span m=''3550350''>to</span> <span m=''3550420''>do?</span> <span m=''3550580''>What</span>
  <span m=''3550720''>do</span> <span m=''3550790''>we</span> <span m=''3550900''>do</span>
  <span m=''3551030''>with</span> <span m=''3551150''>the</span> <span m=''3551230''>triangles?</span>
  <span m=''3553220''>Rabbit</span> <span m=''3553630''>ear.</span> <span m=''3554940''>That''s</span>
  <span m=''3555230''>the</span> <span m=''3555490''>key</span> <span m=''3555750''>phrase</span>
  <span m=''3556090''>for</span> <span m=''3556210''>today.</span> <span m=''3557760''>So</span>
  <span m=''3558450''>remember</span> <span m=''3559040''>our</span> <span m=''3559160''>good</span>
  <span m=''3559310''>friend,</span> <span m=''3559560''>the</span> <span m=''3559650''>rabbit</span>
  <span m=''3559970''>ear,</span> <span m=''3560360''>and</span> <span m=''3560510''>then</span>
  <span m=''3560690''>there</span> <span m=''3560880''>was</span> <span m=''3561040''>the</span>
  <span m=''3561550''>universal</span> <span m=''3562050''>molecule--</span> <span
  m=''3562610''>Lang''s</span> <span m=''3562880''>universal</span> <span m=''3563320''>molecule</span>
  <span m=''3563800''>for</span> <span m=''3564020''>the</span> <span m=''3564120''>quadrilateral.</span>
  <span m=''3564760''>We''re</span> <span m=''3564860''>going</span> <span m=''3564940''>to</span>
  <span m=''3564980''>use</span> <span m=''3565160''>that</span> <span m=''3565780''>for</span>
  <span m=''3565890''>the</span> <span m=''3565990''>quadrilaterals.</span> </p><p><span
  m=''3567330''>And</span> <span m=''3567600''>it</span> <span m=''3567690''>turns</span>
  <span m=''3567980''>out</span> <span m=''3568270''>there''s</span> <span m=''3568410''>some</span>
  <span m=''3568600''>nice</span> <span m=''3568870''>properties</span> <span m=''3569370''>here,</span>
  <span m=''3570390''>which</span> <span m=''3570740''>is</span> <span m=''3573050''>the</span>
  <span m=''3573170''>perpendicular</span> <span m=''3573830''>folds</span> <span
  m=''3574070''>of</span> <span m=''3574130''>the</span> <span m=''3574210''>rabbit</span>
  <span m=''3574540''>ear</span> <span m=''3574800''>will</span> <span m=''3575020''>always</span>
  <span m=''3575520''>hit</span> <span m=''3575800''>right</span> <span m=''3576160''>at</span>
  <span m=''3576340''>the</span> <span m=''3576440''>kissing</span> <span m=''3576770''>point</span>
  <span m=''3577040''>between</span> <span m=''3577290''>the</span> <span m=''3577400''>two</span>
  <span m=''3577530''>disks.</span> <span m=''3578630''>And</span> <span m=''3578830''>same</span>
  <span m=''3579060''>thing</span> <span m=''3579700''>in</span> <span m=''3580450''>here.</span>
  <span m=''3581100''>We''ve</span> <span m=''3581230''>got</span> <span m=''3581400''>these</span>
  <span m=''3581560''>four</span> <span m=''3581780''>disks.</span> <span m=''3582050''>We''ve</span>
  <span m=''3582150''>got</span> <span m=''3582330''>this</span> <span m=''3582690''>quadrilateral</span>
  <span m=''3583390''>region</span> <span m=''3584180''>in</span> <span m=''3584320''>between.</span>
  <span m=''3585610''>and</span> <span m=''3586060''>the</span> <span m=''3586190''>perpendicular</span>
  <span m=''3586810''>folds</span> <span m=''3587160''>that</span> <span m=''3587260''>come</span>
  <span m=''3587590''>out</span> <span m=''3588190''>of</span> <span m=''3588930''>these</span>
  <span m=''3589480''>two</span> <span m=''3590120''>points.</span> <span m=''3590990''>You</span>
  <span m=''3591150''>may</span> <span m=''3591240''>not</span> <span m=''3591450''>remember</span>
  <span m=''3591760''>exactly</span> <span m=''3592610''>what''s</span> <span m=''3592840''>happening</span>
  <span m=''3593210''>here</span> <span m=''3593440''>as</span> <span m=''3593540''>we</span>
  <span m=''3594130''>shrink.</span> </p><p><span m=''3595440''>And</span> <span m=''3595640''>then</span>
  <span m=''3597111''>in</span> <span m=''3597490''>the</span> <span m=''3597960''>tree</span>
  <span m=''3598190''>method,</span> <span m=''3598820''>this</span> <span m=''3598980''>became</span>
  <span m=''3599280''>an</span> <span m=''3599360''>active</span> <span m=''3599660''>path.</span>
  <span m=''3599920''>There''s</span> <span m=''3600070''>no</span> <span m=''3600200''>notion</span>
  <span m=''3600470''>of</span> <span m=''3600540''>active</span> <span m=''3600800''>paths</span>
  <span m=''3601050''>here,</span> <span m=''3601840''>but</span> <span m=''3602070''>we</span>
  <span m=''3602220''>just</span> <span m=''3602830''>make</span> <span m=''3603180''>that</span>
  <span m=''3603500''>so.</span> <span m=''3604510''>That</span> <span m=''3605890''>these</span>
  <span m=''3606180''>perpendicular</span> <span m=''3606770''>folds</span> <span
  m=''3607100''>will</span> <span m=''3607250''>end</span> <span m=''3607400''>up</span>
  <span m=''3607520''>hitting</span> <span m=''3608240''>kissing</span> <span m=''3608580''>disks,</span>
  <span m=''3609780''>and</span> <span m=''3609950''>we''ll</span> <span m=''3610070''>end</span>
  <span m=''3610270''>up</span> <span m=''3610540''>actually</span> <span m=''3610860''>with</span>
  <span m=''3611020''>the</span> <span m=''3611140''>four</span> <span m=''3611530''>arm</span>
  <span m=''3611950''>starfish.</span> <span m=''3612760''>In</span> <span m=''3612870''>terms</span>
  <span m=''3613110''>of</span> <span m=''3613180''>the</span> <span m=''3613280''>tree</span>
  <span m=''3613550''>you</span> <span m=''3613670''>get</span> <span m=''3614720''>and</span>
  <span m=''3614985''>the</span> <span m=''3615250''>articulatable</span> <span m=''3616220''>flaps</span>
  <span m=''3616700''>here,</span> <span m=''3618090''>these</span> <span m=''3618390''>guys</span>
  <span m=''3618540''>will all</span> <span m=''3618770''>meet</span> <span m=''3618900''>at
  a</span> <span m=''3619090''>point.</span> <span m=''3620630''>That''s</span> <span
  m=''3620920''>just</span> <span m=''3621370''>the</span> <span m=''3621490''>way</span>
  <span m=''3621800''>this</span> <span m=''3621990''>works</span> <span m=''3622230''>with</span>
  <span m=''3622360''>disk</span> <span m=''3622560''>packing.</span> </p><p><span
  m=''3623470''>And</span> <span m=''3624780''>you</span> <span m=''3624900''>can</span>
  <span m=''3625030''>think</span> <span m=''3625200''>of</span> <span m=''3625310''>there</span>
  <span m=''3625440''>being</span> <span m=''3625640''>disks</span> <span m=''3625900''>here</span>
  <span m=''3626160''>and you''re</span> <span m=''3626260''>actually</span> <span
  m=''3626470''>applying</span> <span m=''3626860''>the</span> <span m=''3626940''>tree</span>
  <span m=''3627140''>method</span> <span m=''3627760''>to</span> <span m=''3627890''>that</span>
  <span m=''3628630''>flap</span> <span m=''3629070''>pattern,</span> <span m=''3630190''>and</span>
  <span m=''3630830''>that''s</span> <span m=''3631550''>probably</span> <span m=''3631780''>the
  easiest</span> <span m=''3632090''>way</span> <span m=''3632180''>to</span> <span
  m=''3632250''>think</span> <span m=''3632440''>about</span> <span m=''3632690''>it.</span>
  <span m=''3633430''>But</span> <span m=''3633650''>what''s</span> <span m=''3633890''>good</span>
  <span m=''3634100''>for</span> <span m=''3634270''>us--</span> <span m=''3635140''>do
  I</span> <span m=''3635180''>have</span> <span m=''3635310''>a</span> <span m=''3635370''>picture?</span>
  <span m=''3637080''>Not</span> <span m=''3637260''>yet.</span> <span m=''3637740''>But</span>
  <span m=''3637930''>the</span> <span m=''3638020''>point</span> <span m=''3638240''>is,</span>
  <span m=''3638730''>I have</span> <span m=''3638910''>perpendiculars</span> <span
  m=''3639540''>coming</span> <span m=''3639810''>out</span> <span m=''3639890''>of</span>
  <span m=''3639960''>here.</span> <span m=''3640480''>I have</span> <span m=''3640660''>perpendiculars</span>
  <span m=''3641280''>coming</span> <span m=''3641540''>out</span> <span m=''3641620''>of</span>
  <span m=''3641700''>here.</span> <span m=''3642150''>They</span> <span m=''3642310''>will</span>
  <span m=''3642490''>meet</span> <span m=''3643210''>because</span> <span m=''3643890''>these</span>
  <span m=''3644200''>disks</span> <span m=''3644740''>kiss</span> <span m=''3646070''>at</span>
  <span m=''3646150''>the</span> <span m=''3646230''>same</span> <span m=''3646450''>point</span>
  <span m=''3646710''>up</span> <span m=''3647450''>from</span> <span m=''3647590''>both</span>
  <span m=''3647760''>sides.</span> </p><p><span m=''3648720''>Perpendiculars</span>
  <span m=''3649290''>meet.</span> <span m=''3649780''>That''s</span> <span m=''3650040''>good.</span>
  <span m=''3650350''>That</span> <span m=''3650400''>means</span> <span m=''3650600''>I</span>
  <span m=''3650640''>don''t</span> <span m=''3650810''>get</span> <span m=''3650970''>perpendiculars</span>
  <span m=''3651500''>bouncing</span> <span m=''3652230''>all</span> <span m=''3652520''>over</span>
  <span m=''3652670''>the</span> <span m=''3652770''>place.</span> <span m=''3653360''>So</span>
  <span m=''3653520''>all</span> <span m=''3653740''>this</span> <span m=''3653910''>work</span>
  <span m=''3654260''>is</span> <span m=''3654410''>to</span> <span m=''3654510''>make</span>
  <span m=''3654660''>sure</span> <span m=''3654780''>that</span> <span m=''3654850''>perpendiculars</span>
  <span m=''3655490''>are</span> <span m=''3655550''>well</span> <span m=''3655740''>behaved.</span>
  <span m=''3656645''>It''s</span> <span m=''3656930''>a</span> <span m=''3656980''>lot</span>
  <span m=''3657210''>of</span> <span m=''3657270''>work</span> <span m=''3657460''>to</span>
  <span m=''3657570''>do</span> <span m=''3657740''>it,</span> <span m=''3658340''>but</span>
  <span m=''3658580''>it</span> <span m=''3659750''>does</span> <span m=''3659940''>it.</span>
  </p><p><span m=''3660540''>Now</span> <span m=''3660720''>when</span> <span m=''3660830''>you</span>
  <span m=''3660940''>fold</span> <span m=''3661260''>this</span> <span m=''3661490''>thing,</span>
  <span m=''3663090''>what</span> <span m=''3663290''>we</span> <span m=''3663440''>end</span>
  <span m=''3663620''>up</span> <span m=''3663760''>doing</span> <span m=''3664700''>is</span>
  <span m=''3664940''>lining</span> <span m=''3665410''>up--</span> <span m=''3665670''>remember</span>
  <span m=''3665890''>there</span> <span m=''3666440''>was</span> <span m=''3666840''>two</span>
  <span m=''3667060''>copies</span> <span m=''3667570''>of</span> <span m=''3667660''>my</span>
  <span m=''3667800''>polygon.</span> <span m=''3668770''>There''s</span> <span m=''3668920''>the</span>
  <span m=''3669010''>inner</span> <span m=''3669220''>copy</span> <span m=''3669550''>and</span>
  <span m=''3669630''>the</span> <span m=''3669710''>outer</span> <span m=''3669960''>copy.</span>
  <span m=''3671160''>I</span> <span m=''3671310''>end</span> <span m=''3671540''>up</span>
  <span m=''3671670''>lining</span> <span m=''3672200''>up</span> <span m=''3672480''>all</span>
  <span m=''3672830''>of</span> <span m=''3672970''>these</span> <span m=''3673250''>guys--</span>
  <span m=''3677960''>I''m</span> <span m=''3678160''>got</span> <span m=''3678300''>to</span>
  <span m=''3678360''>go</span> <span m=''3678470''>back</span> <span m=''3678640''>to
  the</span> <span m=''3678920''>picture.</span> <span m=''3679390''>I''m</span> <span
  m=''3679620''>sorry.</span> </p><p><span m=''3680870''>So</span> <span m=''3680990''>we</span>
  <span m=''3681060''>have</span> <span m=''3681190''>this</span> <span m=''3681340''>inner</span>
  <span m=''3681620''>copy,</span> <span m=''3682550''>and</span> <span m=''3683020''>what</span>
  <span m=''3683440''>these</span> <span m=''3683710''>molecules</span> <span m=''3684230''>end</span>
  <span m=''3684350''>up</span> <span m=''3684440''>doing</span> <span m=''3684680''>is</span>
  <span m=''3684790''>lining</span> <span m=''3685180''>up</span> <span m=''3685290''>all</span>
  <span m=''3685530''>the</span> <span m=''3685650''>edges</span> <span m=''3685870''>of</span>
  <span m=''3685930''>this</span> <span m=''3686010''>quad,</span> <span m=''3686540''>all</span>
  <span m=''3686700''>the</span> <span m=''3686810''>edges</span> <span m=''3687020''>of</span>
  <span m=''3687100''>this</span> <span m=''3687200''>quad,</span> <span m=''3687660''>all</span>
  <span m=''3687810''>the</span> <span m=''3688020''>edges</span> <span m=''3688280''>of</span>
  <span m=''3688370''>this</span> <span m=''3688490''>triangle.</span> <span m=''3689200''>All</span>
  <span m=''3689430''>those</span> <span m=''3689620''>edges</span> <span m=''3690030''>on</span>
  <span m=''3690110''>the</span> <span m=''3690250''>inside</span> <span m=''3690740''>will</span>
  <span m=''3690860''>become</span> <span m=''3691150''>lined</span> <span m=''3691370''>up</span>
  <span m=''3691500''>on</span> <span m=''3691600''>one</span> <span m=''3692240''>edge.</span>
  <span m=''3693020''>All</span> <span m=''3693380''>the</span> <span m=''3693450''>lines</span>
  <span m=''3693750''>on</span> <span m=''3693810''>the</span> <span m=''3693910''>outside</span>
  <span m=''3694310''>become</span> <span m=''3694640''>lined</span> <span m=''3694880''>up</span>
  <span m=''3695160''>on</span> <span m=''3695880''>another</span> <span m=''3696280''>line.</span>
  <span m=''3696980''>Turns</span> <span m=''3697210''>out</span> <span m=''3697300''>it</span>
  <span m=''3697350''>will</span> <span m=''3697460''>be</span> <span m=''3697610''>parallel</span>
  <span m=''3698250''>to</span> <span m=''3698660''>that</span> <span m=''3698860''>line.</span>
  </p><p><span m=''3699840''>But</span> <span m=''3699970''>what</span> <span m=''3700120''>we</span>
  <span m=''3700240''>really</span> <span m=''3700540''>wanted</span> <span m=''3700800''>to</span>
  <span m=''3700910''>line</span> <span m=''3701140''>up</span> <span m=''3701270''>were</span>
  <span m=''3701380''>these</span> <span m=''3701740''>edges,</span> <span m=''3702710''>and</span>
  <span m=''3702860''>you</span> <span m=''3702960''>can</span> <span m=''3703080''>see</span>
  <span m=''3703280''>why</span> <span m=''3703450''>we</span> <span m=''3703580''>had</span>
  <span m=''3703730''>to</span> <span m=''3703790''>do</span> <span m=''3703890''>the</span>
  <span m=''3704040''>outside</span> <span m=''3704450''>of the</span> <span m=''3704520''>beginning,</span>
  <span m=''3704860''>because</span> <span m=''3705010''>otherwise</span> <span m=''3705470''>we''d</span>
  <span m=''3705580''>get</span> <span m=''3705790''>tons</span> <span m=''3706050''>of</span>
  <span m=''3706200''>extra</span> <span m=''3706540''>junk</span> <span m=''3706940''>on</span>
  <span m=''3707150''>our</span> <span m=''3707270''>line.</span> <span m=''3708030''>We</span>
  <span m=''3708220''>only</span> <span m=''3708480''>want</span> <span m=''3709090''>these</span>
  <span m=''3709370''>edges</span> <span m=''3709680''>on</span> <span m=''3709820''>our</span>
  <span m=''3709900''>line.</span> </p><p><span m=''3710860''>So</span> <span m=''3711020''>we</span>
  <span m=''3711110''>did</span> <span m=''3711280''>the</span> <span m=''3711430''>offset</span>
  <span m=''3711920''>so</span> <span m=''3712020''>that</span> <span m=''3712180''>all</span>
  <span m=''3712440''>this</span> <span m=''3712620''>stuff</span> <span m=''3713330''>will</span>
  <span m=''3713470''>come</span> <span m=''3713710''>to</span> <span m=''3713850''>one</span>
  <span m=''3714200''>line.</span> <span m=''3714950''>All</span> <span m=''3715250''>this</span>
  <span m=''3715440''>stuff</span> <span m=''3715740''>on</span> <span m=''3715800''>the</span>
  <span m=''3715910''>outside</span> <span m=''3716210''>will</span> <span m=''3716340''>come</span>
  <span m=''3716540''>to</span> <span m=''3716650''>another</span> <span m=''3716980''>line.</span>
  <span m=''3717870''>And</span> <span m=''3718000''>then</span> <span m=''3718190''>we</span>
  <span m=''3718310''>get</span> <span m=''3718770''>this</span> <span m=''3718990''>picture.</span>
  <span m=''3721410''>So</span> <span m=''3721810''>this</span> <span m=''3722070''>is</span>
  <span m=''3722200''>one</span> <span m=''3722440''>line</span> <span m=''3722760''>at</span>
  <span m=''3722860''>the</span> <span m=''3722930''>bottom.</span> <span m=''3723790''>Another</span>
  <span m=''3723990''>line</span> <span m=''3724315''>at the top.</span> <span m=''3724640''>We</span>
  <span m=''3724780''>really</span> <span m=''3725050''>wanted</span> <span m=''3725330''>to</span>
  <span m=''3725480''>line</span> <span m=''3725720''>up</span> <span m=''3725820''>stuff--</span>
  <span m=''3727100''>the</span> <span m=''3727640''>blue</span> <span m=''3727930''>stuff</span>
  <span m=''3728230''>there.</span> </p><p><span m=''3729270''>And</span> <span m=''3729390''>there''s</span>
  <span m=''3729540''>still</span> <span m=''3729850''>some</span> <span m=''3730050''>junk</span>
  <span m=''3730360''>on</span> <span m=''3730470''>our</span> <span m=''3730620''>line.</span>
  <span m=''3730950''>These</span> <span m=''3731960''>cyan</span> <span m=''3732670''>triangles</span>
  <span m=''3733820''>represent</span> <span m=''3734310''>things</span> <span m=''3734510''>that</span>
  <span m=''3734620''>come</span> <span m=''3734920''>from</span> <span m=''3735100''>down</span>
  <span m=''3735340''>here,</span> <span m=''3736200''>but</span> <span m=''3736630''>we</span>
  <span m=''3737290''>really</span> <span m=''3737680''>don''t</span> <span m=''3737890''>want</span>
  <span m=''3738150''>them</span> <span m=''3738290''>to</span> <span m=''3738380''>cross</span>
  <span m=''3738690''>our</span> <span m=''3738790''>line.</span> <span m=''3739070''>They</span>
  <span m=''3739160''>just</span> <span m=''3739330''>happened</span> <span m=''3739700''>to.</span>
  <span m=''3740390''>So</span> <span m=''3740550''>we</span> <span m=''3740680''>have</span>
  <span m=''3740960''>to</span> <span m=''3741130''>sync</span> <span m=''3741580''>them</span>
  <span m=''3741780''>repeatedly.</span> <span m=''3742650''>Do</span> <span m=''3742780''>lots</span>
  <span m=''3743110''>of</span> <span m=''3743200''>folds</span> <span m=''3743590''>to</span>
  <span m=''3743690''>make</span> <span m=''3743880''>them</span> <span m=''3744030''>underneath</span>
  <span m=''3744500''>that</span> <span m=''3744630''>epsilon</span> <span m=''3745040''>line.</span>
  <span m=''3745730''>Then</span> <span m=''3745920''>we</span> <span m=''3746010''>can</span>
  <span m=''3746130''>cut along</span> <span m=''3746350''>our line,</span> <span
  m=''3747030''>and</span> <span m=''3747160''>we''re</span> <span m=''3747250''>done.</span>
  <span m=''3748240''>Easy.</span> </p><p><span m=''3753620''>To</span> <span m=''3753800''>prove</span>
  <span m=''3754090''>that</span> <span m=''3754190''>this</span> <span m=''3754380''>works,</span>
  <span m=''3756070''>we''ll</span> <span m=''3756200''>view</span> <span m=''3756390''>a</span>
  <span m=''3756430''>little</span> <span m=''3757410''>sketch.</span> <span m=''3757880''>This</span>
  <span m=''3758020''>is</span> <span m=''3758150''>kind</span> <span m=''3758340''>of</span>
  <span m=''3758430''>fun,</span> <span m=''3759410''>and</span> <span m=''3759560''>it''s</span>
  <span m=''3759990''>one</span> <span m=''3760280''>piece</span> <span m=''3760670''>of</span>
  <span m=''3760780''>what</span> <span m=''3760930''>we''re</span> <span m=''3761430''>in</span>
  <span m=''3761530''>the</span> <span m=''3761620''>process</span> <span m=''3762010''>of</span>
  <span m=''3762090''>doing</span> <span m=''3762290''>for</span> <span m=''3762400''>tree</span>
  <span m=''3762580''>maker.</span> <span m=''3763020''>This</span> <span m=''3763100''>is</span>
  <span m=''3763160''>sort</span> <span m=''3763360''>of</span> <span m=''3763430''>like</span>
  <span m=''3763630''>a</span> <span m=''3763710''>special</span> <span m=''3764100''>case</span>
  <span m=''3764370''>of</span> <span m=''3764450''>tree</span> <span m=''3764600''>maker.</span>
  <span m=''3764870''>You</span> <span m=''3764960''>just</span> <span m=''3765170''>have</span>
  <span m=''3765210''>very</span> <span m=''3765420''>simple</span> <span m=''3765720''>molecules</span>
  <span m=''3767320''>and a</span> <span m=''3767570''>relatively</span> <span m=''3767980''>simple</span>
  <span m=''3768290''>way</span> <span m=''3768440''>in</span> <span m=''3768520''>which</span>
  <span m=''3768740''>they''re</span> <span m=''3769220''>combined.</span> </p><p><span
  m=''3775380''>Here</span> <span m=''3775920''>I''ve</span> <span m=''3775930''>done</span>
  <span m=''3776070''>a</span> <span m=''3776120''>simpler</span> <span m=''3776950''>example.</span>
  <span m=''3777370''>I</span> <span m=''3777420''>want</span> <span m=''3777570''>to</span>
  <span m=''3777610''>make</span> <span m=''3777770''>a</span> <span m=''3777850''>square,</span>
  <span m=''3780060''>and</span> <span m=''3780440''>I</span> <span m=''3780560''>end</span>
  <span m=''3780720''>up</span> <span m=''3780800''>decomposing</span> <span m=''3781470''>in</span>
  <span m=''3781530''>this</span> <span m=''3781690''>case</span> <span m=''3781890''>into</span>
  <span m=''3782080''>nine</span> <span m=''3782750''>molecules--</span> <span m=''3783580''>nine</span>
  <span m=''3783840''>quadrilateral</span> <span m=''3784490''>molecules.</span> <span
  m=''3784765''>A</span> <span m=''3785040''>very</span> <span m=''3785200''>simple</span>
  <span m=''3785490''>disk packing</span> <span m=''3785980''>which</span> <span m=''3786120''>I
  have</span> <span m=''3786250''>not</span> <span m=''3786460''>shown</span> <span
  m=''3786650''>the disk</span> <span m=''3786910''>packing</span> <span m=''3787210''>here.</span>
  <span m=''3788170''>The</span> <span m=''3788280''>idea</span> <span m=''3788550''>is</span>
  <span m=''3788940''>I''m</span> <span m=''3789080''>going</span> <span m=''3789180''>to</span>
  <span m=''3789230''>make</span> <span m=''3789430''>some</span> <span m=''3789650''>cuts</span>
  <span m=''3790230''>in</span> <span m=''3790410''>my</span> <span m=''3790590''>paper</span>
  <span m=''3791580''>to</span> <span m=''3791820''>make</span> <span m=''3792150''>my</span>
  <span m=''3792270''>problem</span> <span m=''3792610''>easier.</span> </p><p><span
  m=''3793830''>I''m going</span> <span m=''3794000''>to have</span> <span m=''3794180''>to</span>
  <span m=''3794280''>pay</span> <span m=''3794510''>for</span> <span m=''3794640''>that,</span>
  <span m=''3794850''>because</span> <span m=''3795050''>later</span> <span m=''3795620''>I</span>
  <span m=''3795740''>really</span> <span m=''3796020''>want</span> <span m=''3796210''>those</span>
  <span m=''3796380''>edges</span> <span m=''3796670''>joined.</span> <span m=''3797100''>I''ll
  have</span> <span m=''3797470''>to glue them</span> <span m=''3797650''>back</span>
  <span m=''3797820''>together.</span> <span m=''3798430''>But</span> <span m=''3798730''>to</span>
  <span m=''3799110''>make it</span> <span m=''3799370''>easier</span> <span m=''3799680''>think</span>
  <span m=''3799920''>about,</span> <span m=''3800550''>I</span> <span m=''3800650''>cut</span>
  <span m=''3801580''>those</span> <span m=''3802910''>four</span> <span m=''3803220''>edges.</span>
  <span m=''3804290''>So</span> <span m=''3804380''>that</span> <span m=''3804580''>the</span>
  <span m=''3804870''>way</span> <span m=''3805200''>in</span> <span m=''3805340''>which</span>
  <span m=''3805610''>my</span> <span m=''3806060''>molecules</span> <span m=''3806660''>are</span>
  <span m=''3806750''>connected</span> <span m=''3807170''>to</span> <span m=''3807280''>each</span>
  <span m=''3807440''>other</span> <span m=''3808080''>is</span> <span m=''3808250''>a</span>
  <span m=''3808310''>tree,</span> <span m=''3809390''>because</span> <span m=''3809520''>I</span>
  <span m=''3809580''>like</span> <span m=''3809780''>trees.</span> <span m=''3810090''>They''re</span>
  <span m=''3810140''>easier</span> <span m=''3810410''>to</span> <span m=''3810490''>think</span>
  <span m=''3810680''>about.</span> <span m=''3811000''>Easier</span> <span m=''3811280''>to</span>
  <span m=''3811380''>do</span> <span m=''3811480''>induction</span> <span m=''3811900''>over.</span>
  </p><p><span m=''3812490''>So</span> <span m=''3812600''>that''s</span> <span m=''3812870''>the</span>
  <span m=''3812970''>blue</span> <span m=''3813860''>line</span> <span m=''3814670''>connecting</span>
  <span m=''3815070''>the</span> <span m=''3815150''>centers</span> <span m=''3815580''>in</span>
  <span m=''3815690''>a</span> <span m=''3815770''>tree.</span> <span m=''3816460''>The</span>
  <span m=''3816810''>other</span> <span m=''3816990''>remaining</span> <span m=''3817400''>edges</span>
  <span m=''3817910''>in</span> <span m=''3818030''>the</span> <span m=''3818110''>grid</span>
  <span m=''3818400''>have</span> <span m=''3818570''>been</span> <span m=''3818800''>cut</span>
  <span m=''3818990''>away.</span> </p><p><span m=''3821440''>Now</span> <span m=''3821640''>the</span>
  <span m=''3821770''>idea</span> <span m=''3822040''>is--</span> <span m=''3823140''>it''s</span>
  <span m=''3823260''>kind</span> <span m=''3823570''>of</span> <span m=''3823660''>like</span>
  <span m=''3824510''>what</span> <span m=''3824690''>I</span> <span m=''3824750''>was</span>
  <span m=''3824900''>drawing</span> <span m=''3825250''>for</span> <span m=''3825560''>the</span>
  <span m=''3825710''>linear</span> <span m=''3826000''>corridor</span> <span m=''3826380''>case.</span>
  <span m=''3827190''>You</span> <span m=''3827290''>have</span> <span m=''3827410''>a</span>
  <span m=''3827460''>tree,</span> <span m=''3828080''>you</span> <span m=''3828220''>pick</span>
  <span m=''3828530''>up</span> <span m=''3828740''>the</span> <span m=''3828820''>tree</span>
  <span m=''3829150''>from</span> <span m=''3829870''>some</span> <span m=''3830130''>node,</span>
  <span m=''3831020''>and</span> <span m=''3831210''>just</span> <span m=''3831380''>hang</span>
  <span m=''3831590''>it</span> <span m=''3831690''>down.</span> <span m=''3832710''>And
  in</span> <span m=''3832990''>this</span> <span m=''3833200''>case,</span> <span
  m=''3834170''>we</span> <span m=''3834390''>hang</span> <span m=''3834710''>it</span>
  <span m=''3834900''>from</span> <span m=''3835920''>this</span> <span m=''3836270''>molecule.</span>
  <span m=''3836870''>The</span> <span m=''3836940''>red</span> <span m=''3837230''>edges</span>
  <span m=''3837620''>are</span> <span m=''3837770''>mountain,</span> <span m=''3838620''>so</span>
  <span m=''3839280''>three</span> <span m=''3839520''>of</span> <span m=''3839570''>these</span>
  <span m=''3839760''>are</span> <span m=''3839820''>going</span> <span m=''3839970''>to</span>
  <span m=''3840060''>be</span> <span m=''3840180''>valley.</span> <span m=''3840940''>One</span>
  <span m=''3841150''>mountain.</span> </p><p><span m=''3842060''>The idea</span>
  <span m=''3842340''>is</span> <span m=''3842510''>this</span> <span m=''3842690''>thing</span>
  <span m=''3843090''>reaches</span> <span m=''3843460''>around</span> <span m=''3844390''>the</span>
  <span m=''3844490''>next</span> <span m=''3844770''>guy,</span> <span m=''3845385''>which</span>
  <span m=''3845640''>reaches</span> <span m=''3845680''>is</span> <span m=''3845780''>around</span>
  <span m=''3845990''>the</span> <span m=''3846050''>next</span> <span m=''3846290''>guy,</span>
  <span m=''3846540''>which</span> <span m=''3846600''>reaches</span> <span m=''3846760''>around</span>
  <span m=''3846990''>the</span> <span m=''3847040''>next</span> <span m=''3847310''>guy,</span>
  <span m=''3847900''>and</span> <span m=''3848210''>there''s</span> <span m=''3848400''>actually--</span>
  <span m=''3848930''>there''s</span> <span m=''3849140''>two</span> <span m=''3849340''>valleys</span>
  <span m=''3849790''>here--</span> <span m=''3849970''>two</span> <span m=''3850170''>little</span>
  <span m=''3850400''>pockets.</span> <span m=''3851400''>Each</span> <span m=''3851600''>of--</span>
  <span m=''3851730''>this</span> <span m=''3851910''>guy</span> <span m=''3852100''>goes</span>
  <span m=''3852320''>in</span> <span m=''3852420''>that</span> <span m=''3852610''>pocket,</span>
  <span m=''3852950''>this</span> <span m=''3853110''>guy</span> <span m=''3853220''>goes</span>
  <span m=''3853400''>in</span> <span m=''3853460''>that</span> <span m=''3853660''>pocket,</span>
  <span m=''3854240''>and</span> <span m=''3854420''>recursively,</span> <span m=''3855370''>it</span>
  <span m=''3855470''>just</span> <span m=''3855650''>works.</span> <span m=''3856190''>I</span>
  <span m=''3856270''>think</span> <span m=''3856500''>I</span> <span m=''3856540''>have</span>
  <span m=''3856710''>a</span> <span m=''3856780''>picture</span> <span m=''3857210''>of</span>
  <span m=''3858480''>what''s</span> <span m=''3858730''>actually</span> <span m=''3859100''>happening</span>
  <span m=''3859510''>here.</span> </p><p><span m=''3860095''>Yeah,</span> <span m=''3860740''>is</span>
  <span m=''3861170''>it''s</span> <span m=''3861330''>hard</span> <span m=''3861570''>to</span>
  <span m=''3861670''>really</span> <span m=''3861950''>draw,</span> <span m=''3862740''>but</span>
  <span m=''3863890''>each</span> <span m=''3864120''>of</span> <span m=''3864200''>these</span>
  <span m=''3864420''>forearm</span> <span m=''3864920''>starfish</span> <span m=''3865990''>has</span>
  <span m=''3866200''>one</span> <span m=''3866560''>mountain</span> <span m=''3867240''>and</span>
  <span m=''3867480''>three</span> <span m=''3867660''>valleys,</span> <span m=''3868970''>and</span>
  <span m=''3869130''>you</span> <span m=''3869220''>just</span> <span m=''3869500''>nestle</span>
  <span m=''3869950''>inside</span> <span m=''3870470''>your</span> <span m=''3870640''>parent</span>
  <span m=''3871090''>in</span> <span m=''3871180''>the</span> <span m=''3871260''>tree.</span>
  <span m=''3873070''>And</span> <span m=''3873400''>this</span> <span m=''3873590''>is</span>
  <span m=''3873720''>really</span> <span m=''3873970''>easy</span> <span m=''3874240''>to</span>
  <span m=''3874320''>show</span> <span m=''3874650''>that</span> <span m=''3874830''>there''s</span>
  <span m=''3874990''>no</span> <span m=''3875120''>crossings</span> <span m=''3875570''>here</span>
  <span m=''3875820''>because</span> <span m=''3876670''>just</span> <span m=''3876880''>joined</span>
  <span m=''3877100''>to your</span> <span m=''3877240''>parent,</span> <span m=''3878310''>and</span>
  <span m=''3879240''>it''s</span> <span m=''3879420''>a</span> <span m=''3879470''>nice</span>
  <span m=''3879880''>nesting</span> <span m=''3880310''>structure.</span> <span m=''3880820''>It''s</span>
  <span m=''3880910''>just</span> <span m=''3881150''>in</span> <span m=''3881240''>the</span>
  <span m=''3881300''>same</span> <span m=''3881550''>way</span> <span m=''3881700''>that</span>
  <span m=''3881860''>trees</span> <span m=''3882180''>can</span> <span m=''3882300''>be</span>
  <span m=''3882440''>folded</span> <span m=''3882780''>flat.</span> <span m=''3884270''>You</span>
  <span m=''3884460''>can</span> <span m=''3885060''>fold</span> <span m=''3885860''>all</span>
  <span m=''3886070''>these</span> <span m=''3886220''>molecules</span> <span m=''3886740''>flat</span>
  <span m=''3888910''>and</span> <span m=''3889270''>join</span> <span m=''3889470''>them</span>
  <span m=''3889580''>together</span> <span m=''3890010''>in</span> <span m=''3890160''>a</span>
  <span m=''3890220''>tree.</span> </p><p><span m=''3890960''>But</span> <span m=''3891100''>we</span>
  <span m=''3891200''>didn''t</span> <span m=''3891370''>really</span> <span m=''3891580''>have</span>
  <span m=''3891810''>a</span> <span m=''3891870''>tree.</span> <span m=''3892610''>We</span>
  <span m=''3892750''>had</span> <span m=''3892930''>all</span> <span m=''3893050''>those</span>
  <span m=''3893320''>extra</span> <span m=''3893720''>cuts</span> <span m=''3894070''>that</span>
  <span m=''3894160''>we</span> <span m=''3894280''>have</span> <span m=''3894430''>to</span>
  <span m=''3894570''>re-suture.</span> <span m=''3897380''>So</span> <span m=''3897620''>we</span>
  <span m=''3897710''>have</span> <span m=''3897970''>this</span> <span m=''3898150''>picture,</span>
  <span m=''3899410''>and</span> <span m=''3899540''>now</span> <span m=''3899690''>we</span>
  <span m=''3899800''>really</span> <span m=''3899970''>have</span> <span m=''3900060''>to</span>
  <span m=''3900160''>join</span> <span m=''3900450''>up</span> <span m=''3900540''>these</span>
  <span m=''3900720''>edges</span> <span m=''3901060''>and think</span> <span m=''3901260''>about</span>
  <span m=''3901460''>what</span> <span m=''3901600''>the</span> <span m=''3901680''>mountain</span>
  <span m=''3901910''>valley</span> <span m=''3902200''>assignment</span> <span m=''3902540''>is</span>
  <span m=''3902700''>there.</span> <span m=''3903520''>And</span> <span m=''3905360''>it</span>
  <span m=''3905510''>works.</span> </p><p><span m=''3908666''>This</span> <span m=''3909160''>green</span>
  <span m=''3910120''>thing</span> <span m=''3910950''>is</span> <span m=''3911140''>the</span>
  <span m=''3911230''>boundary,</span> <span m=''3913140''>and</span> <span m=''3913200''>then</span>
  <span m=''3913340''>I have</span> <span m=''3913560''>connected</span> <span m=''3914440''>the</span>
  <span m=''3914590''>dots.</span> <span m=''3915300''>Each</span> <span m=''3915490''>of</span>
  <span m=''3915550''>these</span> <span m=''3915740''>dots</span> <span m=''3916070''>corresponds</span>
  <span m=''3916520''>to</span> <span m=''3916640''>one</span> <span m=''3917030''>green</span>
  <span m=''3917370''>edge</span> <span m=''3917670''>here.</span> <span m=''3917830''>I</span>
  <span m=''3917870''>forget</span> <span m=''3918150''>whether</span> <span m=''3918320''>it''s</span>
  <span m=''3918510''>this</span> <span m=''3918620''>edge</span> <span m=''3919110''>or</span>
  <span m=''3919930''>that</span> <span m=''3920130''>one,</span> <span m=''3920340''>I</span>
  <span m=''3920420''>think.</span> <span m=''3922270''>It''s</span> <span m=''3922600''>just</span>
  <span m=''3922830''>a</span> <span m=''3922890''>single</span> <span m=''3923210''>edge.</span>
  </p><p><span m=''3925200''>And</span> <span m=''3925420''>so,</span> <span m=''3927910''>for</span>
  <span m=''3928050''>example,</span> <span m=''3928570''>these</span> <span m=''3928940''>two</span>
  <span m=''3929870''>are--</span> <span m=''3932070''>these</span> <span m=''3932650''>two</span>
  <span m=''3932900''>joins,</span> <span m=''3934930''>and</span> <span m=''3935120''>then</span>
  <span m=''3935280''>the</span> <span m=''3935380''>joins</span> <span m=''3935730''>above</span>
  <span m=''3936080''>that</span> <span m=''3936980''>nestle</span> <span m=''3937340''>around</span>
  <span m=''3937740''>it.</span> <span m=''3938600''>And</span> <span m=''3938830''>then</span>
  <span m=''3939000''>the</span> <span m=''3939140''>other</span> <span m=''3939400''>branch</span>
  <span m=''3939820''>at</span> <span m=''3939880''>the</span> <span m=''3939970''>top</span>
  <span m=''3940470''>are</span> <span m=''3940950''>joins,</span> <span m=''3941730''>and
  in</span> <span m=''3941890''>the</span> <span m=''3941980''>leftmost</span> <span
  m=''3942930''>cut</span> <span m=''3943370''>are</span> <span m=''3943490''>these</span>
  <span m=''3943750''>two</span> <span m=''3943880''>joins.</span> <span m=''3944610''>You</span>
  <span m=''3944680''>have</span> <span m=''3944790''>to</span> <span m=''3944880''>make</span>
  <span m=''3945050''>these</span> <span m=''3945200''>joins,</span> <span m=''3945720''>and</span>
  <span m=''3945880''>really</span> <span m=''3946130''>all</span> <span m=''3946280''>you</span>
  <span m=''3946340''>need</span> <span m=''3946490''>to</span> <span m=''3946580''>check</span>
  <span m=''3947270''>is</span> <span m=''3947520''>that these</span> <span m=''3947710''>joins</span>
  <span m=''3948000''>form</span> <span m=''3948230''>a</span> <span m=''3948260''>non-crossing</span>
  <span m=''3948970''>picture</span> <span m=''3949360''>like</span> <span m=''3949540''>they</span>
  <span m=''3949620''>do</span> <span m=''3949770''>here.</span> <span m=''3950650''>And</span>
  <span m=''3950810''>that''s</span> <span m=''3951020''>almost</span> <span m=''3951440''>obvious</span>
  <span m=''3951910''>because</span> <span m=''3952350''>this</span> <span m=''3952530''>is</span>
  <span m=''3952670''>a</span> <span m=''3952800''>planer</span> <span m=''3953200''>diagram</span>
  <span m=''3954240''>and</span> <span m=''3954660''>we''re</span> <span m=''3954840''>cutting</span>
  <span m=''3955180''>along</span> <span m=''3955480''>a</span> <span m=''3955560''>planer</span>
  <span m=''3955880''>tree,</span> <span m=''3956660''>and</span> <span m=''3957010''>so</span>
  <span m=''3957160''>this</span> <span m=''3957360''>is</span> <span m=''3957470''>again</span>
  <span m=''3957760''>a</span> <span m=''3957840''>depth</span> <span m=''3958060''>first</span>
  <span m=''3958250''>search</span> <span m=''3958500''>kind</span> <span m=''3958670''>of</span>
  <span m=''3958780''>thing.</span> </p><p><span m=''3959330''>So</span> <span m=''3959925''>there''s</span>
  <span m=''3960310''>one</span> <span m=''3961430''>tree</span> <span m=''3961710''>we</span>
  <span m=''3961820''>call</span> <span m=''3962010''>the</span> <span m=''3962100''>dual</span>
  <span m=''3962350''>tree</span> <span m=''3962690''>here</span> <span m=''3963510''>that</span>
  <span m=''3964190''>works</span> <span m=''3964580''>because</span> <span m=''3964750''>it''s</span>
  <span m=''3964890''>a</span> <span m=''3964940''>tree,</span> <span m=''3965590''>and
  then</span> <span m=''3965710''>there''s</span> <span m=''3965840''>the</span> <span
  m=''3965940''>cuts</span> <span m=''3966210''>you</span> <span m=''3966310''>make</span>
  <span m=''3966530''>which</span> <span m=''3966690''>are</span> <span m=''3966770''>different</span>
  <span m=''3967200''>trees--</span> <span m=''3967790''>primal</span> <span m=''3968180''>tree</span>
  <span m=''3968430''>if</span> <span m=''3968530''>you</span> <span m=''3968660''>want--</span>
  <span m=''3969310''>and</span> <span m=''3969630''>that</span> <span m=''3969780''>also</span>
  <span m=''3970140''>works</span> <span m=''3970650''>because</span> <span m=''3970760''>of</span>
  <span m=''3970820''>planarity.</span> <span m=''3972410''>And</span> <span m=''3972560''>it</span>
  <span m=''3972600''>all</span> <span m=''3972760''>works.</span> <span m=''3973490''>That''s</span>
  <span m=''3973720''>the</span> <span m=''3973800''>hand</span> <span m=''3974050''>wavy</span>
  <span m=''3975160''>version,</span> <span m=''3976840''>and</span> <span m=''3976940''>you</span>
  <span m=''3977050''>can</span> <span m=''3977150''>read</span> <span m=''3977280''>the</span>
  <span m=''3977350''>textbook</span> <span m=''3977685''>if</span> <span m=''3978020''>you</span>
  <span m=''3978120''>want</span> <span m=''3978150''>more</span> <span m=''3978300''>details.</span>
  </p><p><span m=''3980330''>Oh,</span> <span m=''3980780''>gosh.</span> <span m=''3981430''>If</span>
  <span m=''3981530''>you</span> <span m=''3981680''>want</span> <span m=''3981850''>to</span>
  <span m=''3981910''>solve</span> <span m=''3982880''>more</span> <span m=''3983120''>general</span>
  <span m=''3983470''>graphs,</span> <span m=''3983790''>you</span> <span m=''3983910''>can</span>
  <span m=''3984040''>do</span> <span m=''3984210''>it.</span> <span m=''3984720''>In</span>
  <span m=''3984850''>general,</span> <span m=''3985740''>you</span> <span m=''3985860''>have</span>
  <span m=''3985980''>to</span> <span m=''3986070''>offset</span> <span m=''3986460''>all</span>
  <span m=''3986730''>of</span> <span m=''3986800''>those</span> <span m=''3987250''>cut</span>
  <span m=''3987490''>lines,</span> <span m=''3988360''>and</span> <span m=''3988490''>you</span>
  <span m=''3988550''>get</span> <span m=''3988680''>all</span> <span m=''3988920''>these</span>
  <span m=''3989120''>things--</span> <span m=''3990390''>along</span> <span m=''3990780''>the</span>
  <span m=''3992480''>pink</span> <span m=''3992730''>lines</span> <span m=''3993060''>here</span>
  <span m=''3993810''>you</span> <span m=''3994240''>line</span> <span m=''3994660''>things</span>
  <span m=''3994960''>up,</span> <span m=''3995710''>but</span> <span m=''3995830''>you</span>
  <span m=''3995940''>really</span> <span m=''3996180''>want</span> <span m=''3996440''>to</span>
  <span m=''3996560''>line</span> <span m=''3996790''>up</span> <span m=''3997040''>these</span>
  <span m=''3998360''>blue</span> <span m=''3998670''>lines--</span> <span m=''3999360''>purple</span>
  <span m=''3999650''>lines.</span> <span m=''4000450''>And</span> <span m=''4000610''>so
  you</span> <span m=''4000700''>have</span> <span m=''4000810''>to</span> <span m=''4000870''>do</span>
  <span m=''4001000''>more</span> <span m=''4001190''>syncing</span> <span m=''4001700''>to</span>
  <span m=''4001830''>get it</span> <span m=''4002120''>to</span> <span m=''4002220''>work.</span>
  <span m=''4002860''>Now</span> <span m=''4002990''>I</span> <span m=''4003050''>have</span>
  <span m=''4003250''>all</span> <span m=''4003390''>the</span> <span m=''4003450''>things</span>
  <span m=''4003690''>I</span> <span m=''4003740''>want</span> <span m=''4003970''>to</span>
  <span m=''4004030''>line</span> <span m=''4004210''>up</span> <span m=''4004360''>on</span>
  <span m=''4004480''>this</span> <span m=''4004670''>line</span> <span m=''4004930''>and
  this</span> <span m=''4005120''>line.</span> <span m=''4005850''>I</span> <span
  m=''4005950''>fold</span> <span m=''4006120''>in</span> <span m=''4006200''>the</span>
  <span m=''4006260''>middle,</span> <span m=''4006720''>and now</span> <span m=''4007040''>they''re
  lined</span> <span m=''4007270''>up.</span> </p><p><span m=''4012070''>That</span>
  <span m=''4012300''>fold</span> <span m=''4012640''>in</span> <span m=''4012750''>the</span>
  <span m=''4012840''>middle--</span> <span m=''4013680''>yeah,</span> <span m=''4014020''>that
  will work.</span> <span m=''4014422''>Good.</span> <span m=''4015630''>Might have</span>
  <span m=''4016020''>to do</span> <span m=''4016130''>more</span> <span m=''4016310''>syncing.</span>
  <span m=''4020180''>Whew.</span> <span m=''4022120''>Questions</span> <span m=''4022510''>about</span>
  <span m=''4022820''>disk-packing</span> <span m=''4023340''>method?</span> <span
  m=''4023750''>This</span> <span m=''4024060''>is a</span> <span m=''4024080''>bit</span>
  <span m=''4024250''>of</span> <span m=''4024330''>a</span> <span m=''4024420''>whirlwind</span>
  <span m=''4024880''>tour,</span> <span m=''4026210''>but</span> <span m=''4026450''>I</span>
  <span m=''4026510''>wanted</span> <span m=''4026750''>to</span> <span m=''4026830''>get</span>
  <span m=''4026990''>through it</span> <span m=''4027150''>quickly</span> <span m=''4027540''>to</span>
  <span m=''4027670''>tell</span> <span m=''4027950''>you</span> <span m=''4028100''>about</span>
  <span m=''4028310''>a</span> <span m=''4028350''>new</span> <span m=''4028530''>result.</span>
  <span m=''4029340''>Just</span> <span m=''4029640''>got</span> <span m=''4030080''>accepted</span>
  <span m=''4030530''>to</span> <span m=''4030670''>a</span> <span m=''4030730''>conference</span>
  <span m=''4031670''>to</span> <span m=''4031950''>appear</span> <span m=''4034910''>in</span>
  <span m=''4035060''>October.</span> <span m=''4036490''>Pretty</span> <span m=''4036770''>soon.</span>
  </p><p><span m=''4042820''>And</span> <span m=''4043010''>it''s</span> <span m=''4043140''>a</span>
  <span m=''4043190''>project</span> <span m=''4043610''>that</span> <span m=''4043680''>started</span>
  <span m=''4044170''>in</span> <span m=''4044330''>this</span> <span m=''4044490''>class</span>
  <span m=''4044820''>in</span> <span m=''4044920''>the</span> <span m=''4045000''>problem</span>
  <span m=''4045280''>session</span> <span m=''4045820''>three</span> <span m=''4046000''>years</span>
  <span m=''4046200''>ago,</span> <span m=''4048490''>and</span> <span m=''4048680''>we</span>
  <span m=''4048760''>just</span> <span m=''4048920''>solved</span> <span m=''4049250''>it.</span>
  <span m=''4050090''>Took</span> <span m=''4050480''>awhile.</span> <span m=''4053310''>Took</span>
  <span m=''4053650''>another</span> <span m=''4053940''>co-author</span> <span m=''4054600''>to</span>
  <span m=''4054680''>chime</span> <span m=''4054970''>in.</span> <span m=''4059730''>And</span>
  <span m=''4059920''>it</span> <span m=''4060000''>goes</span> <span m=''4060240''>back</span>
  <span m=''4060510''>to</span> <span m=''4060670''>the</span> <span m=''4060910''>early</span>
  <span m=''4061180''>history</span> <span m=''4061710''>of</span> <span m=''4062030''>fold
  and</span> <span m=''4062380''>cut</span> <span m=''4062720''>which</span> <span
  m=''4062970''>is</span> <span m=''4063640''>simple</span> <span m=''4064040''>folds.</span>
  <span m=''4064640''>All the</span> <span m=''4064850''>magicians</span> <span m=''4065160''>were</span>
  <span m=''4065470''>using</span> <span m=''4065780''>simple</span> <span m=''4066080''>folds.</span>
  <span m=''4066400''>What</span> <span m=''4066660''>can</span> <span m=''4066790''>you</span>
  <span m=''4066910''>make</span> <span m=''4067140''>with</span> <span m=''4067190''>simple</span>
  <span m=''4067540''>folds?</span> </p><p><span m=''4068670''>Now</span> <span m=''4068770''>you''ve</span>
  <span m=''4068980''>been</span> <span m=''4069190''>wowed</span> <span m=''4069640''>and
  dowed</span> <span m=''4070020''>that you could</span> <span m=''4070430''>make</span>
  <span m=''4070610''>anything</span> <span m=''4071640''>with</span> <span m=''4072020''>arbitrary</span>
  <span m=''4072490''>folds,</span> <span m=''4072840''>but</span> <span m=''4072990''>simple</span>
  <span m=''4073220''>folds</span> <span m=''4073440''>you</span> <span m=''4073560''>cannot</span>
  <span m=''4073900''>make</span> <span m=''4074090''>anything.</span> <span m=''4075030''>Because</span>
  <span m=''4075370''>the</span> <span m=''4075470''>first</span> <span m=''4075830''>told</span>
  <span m=''4076050''>you</span> <span m=''4076160''>make,</span> <span m=''4078630''>say,</span>
  <span m=''4079040''>this</span> <span m=''4079250''>one,</span> <span m=''4080310''>has</span>
  <span m=''4080610''>to</span> <span m=''4080710''>be</span> <span m=''4080960''>a</span>
  <span m=''4081020''>line</span> <span m=''4081290''>of</span> <span m=''4081350''>symmetry</span>
  <span m=''4082220''>of</span> <span m=''4082390''>your</span> <span m=''4082510''>diagram.</span>
  <span m=''4085844''>Got to</span> <span m=''4086310''>stop</span> <span m=''4086540''>making</span>
  <span m=''4086830''>my life</span> <span m=''4087140''>hard.</span> </p><p><span
  m=''4089120''>If</span> <span m=''4089270''>you</span> <span m=''4089420''>can</span>
  <span m=''4089580''>fold</span> <span m=''4089830''>something,</span> <span m=''4090100''>you</span>
  <span m=''4090220''>can</span> <span m=''4090340''>never</span> <span m=''4090590''>unfold</span>
  <span m=''4091060''>it.</span> <span m=''4091170''>That''s</span> <span m=''4091380''>the</span>
  <span m=''4091450''>usual</span> <span m=''4091830''>simple</span> <span m=''4092140''>fold</span>
  <span m=''4092370''>model.</span> <span m=''4094040''>This</span> <span m=''4094460''>has</span>
  <span m=''4094720''>to</span> <span m=''4094870''>line</span> <span m=''4095140''>up--</span>
  <span m=''4095350''>the</span> <span m=''4095570''>cuts</span> <span m=''4095810''>you</span>
  <span m=''4095910''>want</span> <span m=''4096060''>to</span> <span m=''4096180''>line</span>
  <span m=''4096359''>up</span> <span m=''4096470''>over</span> <span m=''4096649''>here,</span>
  <span m=''4096970''>that</span> <span m=''4097220''>are</span> <span m=''4097390''>exactly</span>
  <span m=''4097859''>be</span> <span m=''4097960''>the</span> <span m=''4098069''>cuts</span>
  <span m=''4098290''>you</span> <span m=''4098390''>want</span> <span m=''4098510''>to</span>
  <span m=''4098580''>line</span> <span m=''4098770''>up</span> <span m=''4098910''>here.</span>
  <span m=''4099149''>So</span> <span m=''4099300''>you</span> <span m=''4099370''>can</span>
  <span m=''4099540''>only</span> <span m=''4099810''>make</span> <span m=''4100050''>symmetric</span>
  <span m=''4100470''>diagrams.</span> <span m=''4100950''>The first</span> <span
  m=''4101260''>fold</span> <span m=''4101410''>has</span> <span m=''4101600''>to</span>
  <span m=''4101680''>be</span> <span m=''4101790''>a</span> <span m=''4101840''>line</span>
  <span m=''4102029''>of</span> <span m=''4102140''>reflectional</span> <span m=''4102609''>symmetry.</span>
  </p><p><span m=''4104990''>But</span> <span m=''4105439''>is</span> <span m=''4105560''>that</span>
  <span m=''4105750''>the</span> <span m=''4105840''>only</span> <span m=''4106040''>property</span>
  <span m=''4106420''>you</span> <span m=''4106510''>need?</span> <span m=''4107890''>No.</span>
  <span m=''4108510''>Kind</span> <span m=''4108689''>of</span> <span m=''4108750''>have</span>
  <span m=''4108899''>to have</span> <span m=''4109060''>symmetry</span> <span m=''4109479''>for</span>
  <span m=''4109880''>while</span> <span m=''4110810''>until</span> <span m=''4111060''>you''re</span>
  <span m=''4111189''>done.</span> <span m=''4112020''>How</span> <span m=''4112210''>do</span>
  <span m=''4112270''>you</span> <span m=''4112410''>formalize</span> <span m=''4112920''>that?</span>
  <span m=''4113620''>Well,</span> <span m=''4113840''>we</span> <span m=''4114000''>came</span>
  <span m=''4114290''>up</span> <span m=''4114479''>with</span> <span m=''4115420''>an</span>
  <span m=''4115479''>algorithm</span> <span m=''4116090''>that</span> <span m=''4116319''>in</span>
  <span m=''4116710''>polynomial</span> <span m=''4117270''>time,</span> <span m=''4118560''>an</span>
  <span m=''4119029''>efficient</span> <span m=''4119359''>algorithm</span> <span
  m=''4120340''>will</span> <span m=''4121810''>tell</span> <span m=''4122069''>you</span>
  <span m=''4124830''>whether</span> <span m=''4125220''>a</span> <span m=''4125250''>given</span>
  <span m=''4125510''>polygon</span> <span m=''4125960''>can</span> <span m=''4126130''>be</span>
  <span m=''4126240''>made.</span> </p><p><span m=''4127090''>Like this</span> <span
  m=''4127290''>polygon</span> <span m=''4131100''>looks</span> <span m=''4131330''>good.</span>
  <span m=''4131640''>I</span> <span m=''4131760''>think--</span> <span m=''4134100''>yeah,</span>
  <span m=''4134560''>I</span> <span m=''4134580''>think</span> <span m=''4134750''>this</span>
  <span m=''4134910''>can</span> <span m=''4135040''>be</span> <span m=''4135160''>made.</span>
  <span m=''4136430''>So</span> <span m=''4136970''>I</span> <span m=''4137080''>think</span>
  <span m=''4137330''>I</span> <span m=''4137390''>would</span> <span m=''4137540''>fold</span>
  <span m=''4137800''>along</span> <span m=''4138720''>and</span> <span m=''4138890''>do
  a bisector</span> <span m=''4139500''>here,</span> <span m=''4140740''>and</span>
  <span m=''4140830''>then</span> <span m=''4140960''>this</span> <span m=''4141149''>basically</span>
  <span m=''4141479''>disappears.</span> <span m=''4142390''>Folding</span> <span
  m=''4142760''>over.</span> <span m=''4143670''>Then I</span> <span m=''4144010''>would
  fold</span> <span m=''4144365''>along and</span> <span m=''4144720''>get a</span>
  <span m=''4144840''>bisector</span> <span m=''4145260''>here,</span> <span m=''4145710''>and
  then</span> <span m=''4145920''>this</span> <span m=''4146160''>disappears</span>
  <span m=''4146840''>into</span> <span m=''4147060''>that,</span> <span m=''4148140''>and</span>
  <span m=''4148459''>then</span> <span m=''4152220''>maybe</span> <span m=''4152560''>I</span>
  <span m=''4152670''>can</span> <span m=''4152970''>fold</span> <span m=''4154100''>here.</span>
  <span m=''4155050''>Does that</span> <span m=''4155170''>work?</span> <span m=''4156580''>Barely.</span>
  <span m=''4157140''>I</span> <span m=''4157220''>mean</span> <span m=''4157420''>I''ve</span>
  <span m=''4157569''>got</span> <span m=''4157700''>to</span> <span m=''4157760''>make</span>
  <span m=''4157910''>sure</span> <span m=''4158040''>that this</span> <span m=''4158680''>blank</span>
  <span m=''4158950''>paper</span> <span m=''4159220''>does</span> <span m=''4159370''>not</span>
  <span m=''4159580''>come</span> <span m=''4159750''>onto</span> <span m=''4159979''>that.</span>
  </p><p><span m=''4162770''>But</span> <span m=''4162880''>if</span> <span m=''4162970''>that''s</span>
  <span m=''4163149''>a</span> <span m=''4163210''>problem,</span> <span m=''4164370''>I</span>
  <span m=''4164439''>can</span> <span m=''4164590''>probably</span> <span m=''4164930''>make--</span>
  <span m=''4166680''>I</span> <span m=''4166779''>could</span> <span m=''4166920''>make</span>
  <span m=''4167140''>a</span> <span m=''4167240''>fold</span> <span m=''4167580''>here,</span>
  <span m=''4167910''>for</span> <span m=''4168060''>example.</span> <span m=''4168950''>Shrinks</span>
  <span m=''4169340''>that</span> <span m=''4169560''>up.</span> <span m=''4170080''>There''s</span>
  <span m=''4170279''>lots</span> <span m=''4170479''>of</span> <span m=''4170529''>things</span>
  <span m=''4170720''>you</span> <span m=''4170830''>can</span> <span m=''4170960''>do.</span>
  <span m=''4172130''>This</span> <span m=''4172279''>is</span> <span m=''4172370''>a</span>
  <span m=''4172420''>borderline</span> <span m=''4173490''>case</span> <span m=''4173890''>whether</span>
  <span m=''4173960''>it''s</span> <span m=''4174050''>yes</span> <span m=''4174250''>or</span>
  <span m=''4174290''>no.</span> <span m=''4174529''>I</span> <span m=''4174660''>will</span>
  <span m=''4174810''>give</span> <span m=''4174979''>you</span> <span m=''4175109''>an</span>
  <span m=''4175200''>algorithm</span> <span m=''4175965''>that</span> <span m=''4176260''>does</span>
  <span m=''4176450''>it.</span> </p><p><span m=''4179410''>For</span> <span m=''4179950''>polygons</span>
  <span m=''4181410''>with</span> <span m=''4181609''>margin.</span> <span m=''4184620''>Bit
  of a</span> <span m=''4184910''>technical</span> <span m=''4186010''>condition.</span>
  <span m=''4187000''>Something</span> <span m=''4187330''>that</span> <span m=''4188450''>is</span>
  <span m=''4188640''>pretty</span> <span m=''4188830''>typical.</span> <span m=''4189080''>What</span>
  <span m=''4189220''>I</span> <span m=''4189290''>mean</span> <span m=''4189529''>is</span>
  <span m=''4190319''>the</span> <span m=''4190439''>thing</span> <span m=''4190640''>you''re</span>
  <span m=''4190750''>trying</span> <span m=''4190990''>to</span> <span m=''4191050''>cut</span>
  <span m=''4191240''>out</span> <span m=''4192200''>does</span> <span m=''4192380''>not</span>
  <span m=''4192660''>meet</span> <span m=''4193040''>the</span> <span m=''4193130''>boundary</span>
  <span m=''4193490''>of</span> <span m=''4193560''>the</span> <span m=''4193640''>paper.</span>
  <span m=''4194490''>There''s</span> <span m=''4194800''>no</span> <span m=''4194990''>margin</span>
  <span m=''4195450''>here.</span> <span m=''4195680''>It''d</span> <span m=''4195770''>be</span>
  <span m=''4195900''>hard</span> <span m=''4196100''>to</span> <span m=''4196160''>print
  out.</span> <span m=''4197240''>So</span> <span m=''4197480''>I</span> <span m=''4197570''>really</span>
  <span m=''4197830''>want</span> <span m=''4198090''>something</span> <span m=''4198450''>that</span>
  <span m=''4198550''>has</span> <span m=''4198730''>margin.</span> <span m=''4199160''>That''s</span>
  <span m=''4199360''>a</span> <span m=''4199420''>typical</span> <span m=''4199820''>case</span>
  <span m=''4200050''>we</span> <span m=''4200130''>care</span> <span m=''4200330''>about.</span>
  </p><p><span m=''4200900''>We</span> <span m=''4200950''>actually</span> <span m=''4201180''>need</span>
  <span m=''4201410''>this</span> <span m=''4201680''>for the</span> <span m=''4201950''>proof</span>
  <span m=''4202070''>to work.</span> <span m=''4202620''>We</span> <span m=''4202820''>also</span>
  <span m=''4203080''>need</span> <span m=''4203330''>that</span> <span m=''4203430''>it''s</span>
  <span m=''4203560''>a</span> <span m=''4203640''>single</span> <span m=''4204070''>polygon.</span>
  <span m=''4209160''>It</span> <span m=''4209240''>does</span> <span m=''4209390''>not</span>
  <span m=''4209610''>work</span> <span m=''4209840''>with</span> <span m=''4210330''>general</span>
  <span m=''4210630''>graphs.</span> <span m=''4211760''>This</span> <span m=''4211930''>algorithm.</span>
  <span m=''4212840''>Because</span> <span m=''4213120''>more</span> <span m=''4213310''>complicated</span>
  <span m=''4213810''>things</span> <span m=''4214010''>can</span> <span m=''4214130''>happen.</span>
  <span m=''4214380''>It</span> <span m=''4214420''>might</span> <span m=''4214650''>be</span>
  <span m=''4214760''>[INAUDIBLE].</span> <span m=''4215400''>for all we know,</span>
  <span m=''4216300''>the</span> <span m=''4216420''>general</span> <span m=''4216720''>case.</span>
  </p><p><span m=''4219290''>So</span> <span m=''4219430''>here''s</span> <span m=''4219680''>the</span>
  <span m=''4219810''>algorithm</span> <span m=''4221026''>that</span> <span m=''4221370''>I''ll</span>
  <span m=''4221470''>give</span> <span m=''4221610''>you</span> <span m=''4222205''>in</span>
  <span m=''4222560''>number</span> <span m=''4222960''>form.</span> <span m=''4225450''>First</span>
  <span m=''4225680''>thing</span> <span m=''4225800''>you</span> <span m=''4225910''>do</span>
  <span m=''4227230''>is</span> <span m=''4227530''>guess</span> <span m=''4227840''>the</span>
  <span m=''4227930''>first</span> <span m=''4228310''>fold.</span> <span m=''4228730''>This</span>
  <span m=''4228950''>is</span> <span m=''4230230''>a</span> <span m=''4230400''>powerful</span>
  <span m=''4230900''>idea</span> <span m=''4231200''>that</span> <span m=''4231530''>even</span>
  <span m=''4231880''>most</span> <span m=''4232110''>algorithmisists</span> <span
  m=''4233190''>don''t</span> <span m=''4233330''>necessarily</span> <span m=''4233710''>know.</span>
  <span m=''4234460''>The</span> <span m=''4234590''>idea</span> <span m=''4234890''>is</span>
  <span m=''4236240''>what</span> <span m=''4236450''>could</span> <span m=''4236500''>the</span>
  <span m=''4236570''>first</span> <span m=''4236830''>fold</span> <span m=''4237010''>be?</span>
  </p><p><span m=''4237430''>Has</span> <span m=''4237660''>to</span> <span m=''4237720''>be</span>
  <span m=''4237820''>a</span> <span m=''4237870''>line</span> <span m=''4238060''>of</span>
  <span m=''4238130''>reflection</span> <span m=''4238560''>symmetry.</span> <span
  m=''4239060''>Turns</span> <span m=''4239340''>out</span> <span m=''4239840''>there''s</span>
  <span m=''4239990''>a</span> <span m=''4240040''>linear</span> <span m=''4240300''>number</span>
  <span m=''4240630''>[INAUDIBLE]</span> <span m=''4240880''>most.</span> <span m=''4241270''>You</span>
  <span m=''4241370''>can</span> <span m=''4241520''>find</span> <span m=''4241760''>them</span>
  <span m=''4241890''>in</span> <span m=''4241960''>linear</span> <span m=''4242220''>time.</span>
  <span m=''4243310''>All</span> <span m=''4243440''>these</span> <span m=''4243620''>good</span>
  <span m=''4243760''>algorithms</span> <span m=''4244180''>for</span> <span m=''4244280''>finding</span>
  <span m=''4244620''>them.</span> </p><p><span m=''4245120''>But</span> <span m=''4245280''>which</span>
  <span m=''4245550''>fold</span> <span m=''4245810''>do</span> <span m=''4245920''>I</span>
  <span m=''4245990''>make</span> <span m=''4246220''>first?</span> <span m=''4247390''>The</span>
  <span m=''4247490''>answer</span> <span m=''4247810''>is</span> <span m=''4248420''>I</span>
  <span m=''4248510''>don''t</span> <span m=''4248690''>care.</span> <span m=''4248970''>Let''s</span>
  <span m=''4249170''>just</span> <span m=''4249300''>try</span> <span m=''4249510''>them</span>
  <span m=''4249680''>all</span> <span m=''4249850''>one</span> <span m=''4250020''>at</span>
  <span m=''4250080''>a</span> <span m=''4250190''>time.</span> <span m=''4251190''>This</span>
  <span m=''4251360''>is</span> <span m=''4251400''>what</span> <span m=''4251540''>I</span>
  <span m=''4251580''>call</span> <span m=''4251810''>guessing.</span> <span m=''4252510''>Just</span>
  <span m=''4252690''>imagine</span> <span m=''4253130''>from</span> <span m=''4253280''>now</span>
  <span m=''4253460''>on</span> <span m=''4253580''>that</span> <span m=''4253690''>we</span>
  <span m=''4253800''>made</span> <span m=''4254000''>the</span> <span m=''4254090''>right</span>
  <span m=''4254320''>guess,</span> <span m=''4254990''>but</span> <span m=''4255140''>if</span>
  <span m=''4255230''>you</span> <span m=''4255310''>end</span> <span m=''4255430''>up</span>
  <span m=''4255540''>failing</span> <span m=''4256170''>later</span> <span m=''4256500''>on</span>
  <span m=''4256720''>this</span> <span m=''4256880''>algorithm,</span> <span m=''4257250''>just</span>
  <span m=''4257420''>go</span> <span m=''4257530''>back</span> <span m=''4257780''>here</span>
  <span m=''4257990''>try</span> <span m=''4258170''>the</span> <span m=''4258270''>next</span>
  <span m=''4258520''>one.</span> <span m=''4259020''>There''s</span> <span m=''4259170''>only</span>
  <span m=''4259500''>N</span> <span m=''4259670''>of</span> <span m=''4259810''>them</span>
  <span m=''4260310''>to try.</span> </p><p><span m=''4261330''>So</span> <span m=''4261460''>you''re</span>
  <span m=''4261550''>going</span> <span m=''4261660''>to</span> <span m=''4261720''>multiply</span>
  <span m=''4262270''>the</span> <span m=''4262370''>running</span> <span m=''4262600''>time</span>
  <span m=''4262770''>of</span> <span m=''4262820''>the</span> <span m=''4262920''>rest
  of</span> <span m=''4263170''>the</span> <span m=''4263320''>algorithm</span> <span
  m=''4263690''>by</span> <span m=''4263830''>N,</span> <span m=''4264660''>and</span>
  <span m=''4264790''>if</span> <span m=''4264880''>this</span> <span m=''4265060''>is</span>
  <span m=''4265210''>N</span> <span m=''4265440''>to</span> <span m=''4266740''>N</span>
  <span m=''4266910''>squared--</span> <span m=''4267565''>which</span> <span m=''4267830''>I</span>
  <span m=''4267860''>think</span> <span m=''4268150''>the</span> <span m=''4268230''>rest</span>
  <span m=''4268410''>of the</span> <span m=''4268530''>algorithm</span> <span m=''4268850''>is
  N</span> <span m=''4268970''>squared--</span> <span m=''4269680''>the</span> <span
  m=''4269780''>whole</span> <span m=''4269990''>algorithm</span> <span m=''4270290''>will</span>
  <span m=''4270390''>be</span> <span m=''4270500''>N</span> <span m=''4270660''>cubed</span>
  <span m=''4271010''>because</span> <span m=''4271130''>you</span> <span m=''4271220''>just</span>
  <span m=''4271390''>run</span> <span m=''4271600''>this</span> <span m=''4271900''>over</span>
  <span m=''4272130''>and</span> <span m=''4272200''>over</span> <span m=''4272480''>for</span>
  <span m=''4272650''>each</span> <span m=''4272800''>possible</span> <span m=''4273140''>first</span>
  <span m=''4273470''>fold.</span> <span m=''4273970''>We</span> <span m=''4274070''>don''t</span>
  <span m=''4274180''>have</span> <span m=''4274340''>a</span> <span m=''4274390''>great</span>
  <span m=''4274620''>theory</span> <span m=''4274830''>to</span> <span m=''4274890''>find</span>
  <span m=''4275100''>the</span> <span m=''4275160''>first</span> <span m=''4275400''>fold.</span>
  <span m=''4276060''>Just</span> <span m=''4276375''>try them</span> <span m=''4276690''>all.</span>
  </p><p><span m=''4278270''>That''s</span> <span m=''4278450''>step</span> <span
  m=''4278680''>one.</span> <span m=''4280160''>Step</span> <span m=''4280550''>two--</span>
  <span m=''4282590''>that''s</span> <span m=''4282790''>the</span> <span m=''4282880''>only</span>
  <span m=''4283080''>guess</span> <span m=''4283330''>we''re</span> <span m=''4283430''>going</span>
  <span m=''4283540''>to</span> <span m=''4283590''>make.</span> <span m=''4285710''>Fold</span>
  <span m=''4286320''>down</span> <span m=''4287620''>to</span> <span m=''4287910''>convex</span>
  <span m=''4288450''>hull.</span> <span m=''4288840''>This</span> <span m=''4289060''>is</span>
  <span m=''4289230''>a</span> <span m=''4289310''>central</span> <span m=''4289750''>idea.</span>
  </p><p><span m=''4292390''>So</span> <span m=''4292430''>we</span> <span m=''4292510''>have</span>
  <span m=''4292720''>this</span> <span m=''4295040''>polygon</span> <span m=''4295480''>we</span>
  <span m=''4295570''>want</span> <span m=''4295750''>to</span> <span m=''4295790''>make.</span>
  <span m=''4296490''>There''s</span> <span m=''4296660''>all</span> <span m=''4296850''>this</span>
  <span m=''4297020''>extra</span> <span m=''4297290''>blank</span> <span m=''4297610''>paper.</span>
  <span m=''4298110''>I don''t</span> <span m=''4298360''>like</span> <span m=''4298570''>extra</span>
  <span m=''4298830''>blank</span> <span m=''4299060''>paper.</span> <span m=''4299340''>Just</span>
  <span m=''4299530''>get</span> <span m=''4299660''>rid</span> <span m=''4299810''>of</span>
  <span m=''4299910''>it.</span> <span m=''4300440''>Make</span> <span m=''4300610''>lots</span>
  <span m=''4300870''>of</span> <span m=''4300970''>folds</span> <span m=''4301810''>to</span>
  <span m=''4301900''>fold</span> <span m=''4302120''>the</span> <span m=''4302180''>blank</span>
  <span m=''4302420''>paper</span> <span m=''4302640''>onto</span> <span m=''4302830''>itself</span>
  <span m=''4303230''>until</span> <span m=''4303430''>it</span> <span m=''4303510''>gets</span>
  <span m=''4304100''>so</span> <span m=''4304350''>tiny</span> <span m=''4304750''>it</span>
  <span m=''4304830''>just</span> <span m=''4305050''>goes</span> <span m=''4305230''>slightly</span>
  <span m=''4305860''>around</span> <span m=''4306270''>the</span> <span m=''4306340''>convex</span>
  <span m=''4306720''>hull.</span> <span m=''4307820''>Convex</span> <span m=''4308190''>hull</span>
  <span m=''4308430''>is the</span> <span m=''4308510''>smallest</span> <span m=''4309080''>convex</span>
  <span m=''4309460''>polygon</span> <span m=''4309940''>that</span> <span m=''4310080''>contains</span>
  <span m=''4310550''>your</span> <span m=''4310700''>shape.</span> <span m=''4311850''>So</span>
  <span m=''4311990''>it''ll be</span> <span m=''4312120''>like</span> <span m=''4312310''>that.</span>
  <span m=''4312630''>It''ll</span> <span m=''4312750''>reduce</span> <span m=''4313090''>the</span>
  <span m=''4313180''>paper</span> <span m=''4313965''>down</span> <span m=''4314240''>to
  that.</span> </p><p><span m=''4315630''>And</span> <span m=''4315870''>I do this</span>
  <span m=''4316090''>a</span> <span m=''4316150''>lot.</span> <span m=''4317880''>I</span>
  <span m=''4318030''>might</span> <span m=''4318240''>as</span> <span m=''4318340''>well.</span>
  <span m=''4318980''>It</span> <span m=''4319110''>makes</span> <span m=''4319300''>the</span>
  <span m=''4319370''>problem</span> <span m=''4319630''>easier</span> <span m=''4319990''>because</span>
  <span m=''4320190''>I</span> <span m=''4320260''>have</span> <span m=''4320480''>less</span>
  <span m=''4320760''>blank</span> <span m=''4321030''>space</span> <span m=''4321280''>to</span>
  <span m=''4321380''>worry</span> <span m=''4321550''>about.</span> <span m=''4321740''>Blank</span>
  <span m=''4321990''>space is a</span> <span m=''4322260''>problem</span> <span m=''4322600''>because</span>
  <span m=''4322680''>if I</span> <span m=''4322860''>[? fold ?]</span> <span m=''4323100''>blank</span>
  <span m=''4323350''>space</span> <span m=''4323660''>onto</span> <span m=''4324080''>a</span>
  <span m=''4324170''>cut,</span> <span m=''4324590''>it''s</span> <span m=''4325060''>bad.</span>
  <span m=''4326120''>It''s</span> <span m=''4326240''>not</span> <span m=''4326410''>allowed.</span>
  </p><p><span m=''4329480''>So</span> <span m=''4329780''>the</span> <span m=''4329880''>next</span>
  <span m=''4330100''>thing</span> <span m=''4330240''>we</span> <span m=''4330330''>do</span>
  <span m=''4331900''>is</span> <span m=''4332130''>make</span> <span m=''4333270''>the</span>
  <span m=''4333560''>best</span> <span m=''4333990''>possible</span> <span m=''4335740''>safe</span>
  <span m=''4335970''>fold.</span> <span m=''4339820''>I</span> <span m=''4339870''>need</span>
  <span m=''4340030''>to</span> <span m=''4340120''>define</span> <span m=''4340510''>that,</span>
  <span m=''4342750''>but</span> <span m=''4342860''>a</span> <span m=''4343020''>safe</span>
  <span m=''4343120''>fold</span> <span m=''4343560''>is</span> <span m=''4343650''>just</span>
  <span m=''4343910''>the</span> <span m=''4343980''>folds</span> <span m=''4344250''>we''re</span>
  <span m=''4344350''>trying</span> <span m=''4344590''>to</span> <span m=''4344640''>make,</span>
  <span m=''4344900''>which</span> <span m=''4345120''>is</span> <span m=''4345800''>locally</span>
  <span m=''4346270''>they are</span> <span m=''4346470''>lines</span> <span m=''4346730''>of</span>
  <span m=''4346800''>symmetry.</span> <span m=''4347630''>So</span> <span m=''4347900''>like</span>
  <span m=''4348100''>this</span> <span m=''4348280''>one</span> <span m=''4349010''>was</span>
  <span m=''4349220''>a</span> <span m=''4349290''>good</span> <span m=''4349560''>fold</span>
  <span m=''4349880''>after</span> <span m=''4350120''>I</span> <span m=''4350190''>made</span>
  <span m=''4350440''>this</span> <span m=''4350620''>fold.</span> <span m=''4351160''>So</span>
  <span m=''4351300''>this</span> <span m=''4351470''>is--</span> <span m=''4352080''>all</span>
  <span m=''4352220''>the</span> <span m=''4352290''>right</span> <span m=''4352460''>stuff</span>
  <span m=''4352670''>here is</span> <span m=''4352910''>gone.</span> </p><p><span
  m=''4354010''>It''s</span> <span m=''4354110''>a</span> <span m=''4354150''>good</span>
  <span m=''4354740''>fold</span> <span m=''4354990''>because</span> <span m=''4355310''>it</span>
  <span m=''4355460''>folds</span> <span m=''4355800''>this</span> <span m=''4355900''>on</span>
  <span m=''4356020''>to</span> <span m=''4356110''>this,</span> <span m=''4356580''>and</span>
  <span m=''4356800''>it</span> <span m=''4356840''>folds</span> <span m=''4357030''>blank</span>
  <span m=''4357350''>space</span> <span m=''4357600''>onto</span> <span m=''4357750''>this</span>
  <span m=''4357980''>blank</span> <span m=''4358250''>space.</span> <span m=''4358960''>So</span>
  <span m=''4359100''>anything</span> <span m=''4359460''>that</span> <span m=''4359700''>comes</span>
  <span m=''4359940''>into--</span> <span m=''4360540''>on</span> <span m=''4360700''>top</span>
  <span m=''4360940''>of</span> <span m=''4361050''>each</span> <span m=''4361210''>other</span>
  <span m=''4361510''>is</span> <span m=''4361740''>identical.</span> <span m=''4362640''>That''s
  a</span> <span m=''4363000''>safe</span> <span m=''4363340''>fold.</span> <span
  m=''4365780''>And</span> <span m=''4367910''>repeat.</span> </p><p><span m=''4370140''>That''s</span>
  <span m=''4370570''>the</span> <span m=''4370660''>algorithm.</span> <span m=''4372720''>How</span>
  <span m=''4373300''>does</span> <span m=''4373430''>that</span> <span m=''4373630''>work?</span>
  <span m=''4378750''>Why</span> <span m=''4379170''>does</span> <span m=''4379370''>this</span>
  <span m=''4379530''>work?</span> <span m=''4380600''>So</span> <span m=''4380770''>it''s</span>
  <span m=''4380880''>the</span> <span m=''4381020''>obvious</span> <span m=''4381350''>algorithm,</span>
  <span m=''4381770''>basically.</span> <span m=''4382220''>It</span> <span m=''4382330''>says</span>
  <span m=''4383130''>make</span> <span m=''4383310''>safe</span> <span m=''4383490''>folds</span>
  <span m=''4383850''>until</span> <span m=''4384130''>you''re</span> <span m=''4384260''>done.</span>
  <span m=''4385080''>If</span> <span m=''4385260''>you</span> <span m=''4385450''>finish,</span>
  <span m=''4386570''>then</span> <span m=''4387100''>you''re</span> <span m=''4387700''>done.</span>
  <span m=''4388120''>And</span> <span m=''4388300''>then</span> <span m=''4388400''>the</span>
  <span m=''4388490''>answer''s</span> <span m=''4388750''>yes.</span> </p><p><span
  m=''4389470''>If</span> <span m=''4389610''>you</span> <span m=''4389730''>don''t</span>
  <span m=''4390040''>finish--</span> <span m=''4390550''>which</span> <span m=''4390710''>is</span>
  <span m=''4390790''>a</span> <span m=''4390830''>little</span> <span m=''4391080''>hard</span>
  <span m=''4391310''>to</span> <span m=''4391370''>check</span> <span m=''4391720''>because</span>
  <span m=''4391970''>you</span> <span m=''4392070''>can</span> <span m=''4392190''>always</span>
  <span m=''4392420''>make</span> <span m=''4392900''>microscopic</span> <span m=''4393620''>folds--</span>
  <span m=''4394480''>but</span> <span m=''4394610''>you</span> <span m=''4394920''>take</span>
  <span m=''4395130''>the</span> <span m=''4395230''>limit</span> <span m=''4395680''>and--</span>
  <span m=''4396070''>if</span> <span m=''4396420''>it''s</span> <span m=''4396600''>possible</span>
  <span m=''4396980''>to</span> <span m=''4397050''>do</span> <span m=''4397140''>this</span>
  <span m=''4397230''>in</span> <span m=''4397370''>polynomial</span> <span m=''4397840''>time--</span>
  <span m=''4398960''>you</span> <span m=''4399150''>find</span> <span m=''4399490''>that</span>
  <span m=''4399610''>out.</span> <span m=''4400130''>Turns</span> <span m=''4400400''>out</span>
  <span m=''4401090''>I</span> <span m=''4401190''>can''t</span> <span m=''4401920''>finish</span>
  <span m=''4402490''>by</span> <span m=''4402600''>making</span> <span m=''4403130''>safe</span>
  <span m=''4403330''>folds.</span> <span m=''4403750''>Then</span> <span m=''4403920''>you</span>
  <span m=''4404060''>can</span> <span m=''4404200''>show</span> <span m=''4404440''>that</span>
  <span m=''4404560''>actually</span> <span m=''4405240''>there</span> <span m=''4405340''>was</span>
  <span m=''4405450''>no</span> <span m=''4405700''>way</span> <span m=''4405860''>to</span>
  <span m=''4405940''>make</span> <span m=''4406300''>that</span> <span m=''4406530''>pattern</span>
  <span m=''4407090''>by</span> <span m=''4407370''>simple</span> <span m=''4407730''>folds.</span>
  </p><p><span m=''4409420''>So</span> <span m=''4409820''>let</span> <span m=''4409950''>me</span>
  <span m=''4410750''>give</span> <span m=''4410940''>you</span> <span m=''4411300''>an</span>
  <span m=''4411400''>idea</span> <span m=''4411820''>of</span> <span m=''4411920''>why</span>
  <span m=''4412080''>that''s</span> <span m=''4412390''>true.</span> <span m=''4416210''>After</span>
  <span m=''4416520''>I</span> <span m=''4416560''>make</span> <span m=''4416800''>a</span>
  <span m=''4416860''>single</span> <span m=''4417170''>fold--</span> <span m=''4418640''>the</span>
  <span m=''4418790''>first</span> <span m=''4419090''>fold--</span> <span m=''4419930''>my</span>
  <span m=''4420070''>picture</span> <span m=''4420990''>looks</span> <span m=''4421230''>like</span>
  <span m=''4421450''>this.</span> <span m=''4421990''>It''s</span> <span m=''4422090''>no</span>
  <span m=''4422190''>longer</span> <span m=''4422380''>a</span> <span m=''4422440''>polygon.</span>
  <span m=''4424275''>It''s</span> <span m=''4424640''>like</span> <span m=''4424860''>half</span>
  <span m=''4425100''>a</span> <span m=''4425170''>polygon.</span> <span m=''4425700''>It</span>
  <span m=''4425830''>ends</span> <span m=''4426560''>at</span> <span m=''4426960''>the</span>
  <span m=''4427510''>boundary</span> <span m=''4427860''>of the</span> <span m=''4427960''>paper.</span>
  <span m=''4428460''>It</span> <span m=''4428780''>begins</span> <span m=''4429120''>and</span>
  <span m=''4429210''>ends</span> <span m=''4429390''>with</span> <span m=''4429440''>the</span>
  <span m=''4429510''>boundary of</span> <span m=''4429820''>paper,</span> <span m=''4430120''>and
  you</span> <span m=''4430180''>have</span> <span m=''4430330''>some</span> <span
  m=''4430500''>chain</span> <span m=''4430790''>in</span> <span m=''4430870''>the</span>
  <span m=''4430930''>middle.</span> <span m=''4431500''>We call</span> <span m=''4431680''>this</span>
  <span m=''4431800''>a</span> <span m=''4431880''>passage.</span> <span m=''4432830''>It''s
  like a</span> <span m=''4433130''>path you</span> <span m=''4433570''>wander</span>
  <span m=''4433880''>along.</span> </p><p><span m=''4434870''>And</span> <span m=''4435450''>I</span>
  <span m=''4435620''>want</span> <span m=''4435820''>to</span> <span m=''4435880''>somehow</span>
  <span m=''4436150''>bring</span> <span m=''4436340''>all</span> <span m=''4436460''>those</span>
  <span m=''4436650''>edges</span> <span m=''4436910''>into</span> <span m=''4437100''>alignment.</span>
  <span m=''4439970''>Here</span> <span m=''4440190''>I''m already</span> <span m=''4440510''>using</span>
  <span m=''4440770''>it</span> <span m=''4440900''>as</span> <span m=''4441020''>a</span>
  <span m=''4441080''>polygon.</span> <span m=''4441800''>If</span> <span m=''4441970''>it</span>
  <span m=''4442050''>weren''t</span> <span m=''4442270''>a  polygon,</span> <span
  m=''4442690''>there</span> <span m=''4442770''>might</span> <span m=''4442930''>be</span>
  <span m=''4443030''>more</span> <span m=''4443250''>than</span> <span m=''4443370''>one</span>
  <span m=''4443540''>of</span> <span m=''4443630''>these.</span> </p><p><span m=''4445280''>Now</span>
  <span m=''4445380''>I</span> <span m=''4445430''>want</span> <span m=''4445640''>to</span>
  <span m=''4445690''>make</span> <span m=''4445870''>a</span> <span m=''4445910''>fold.</span>
  <span m=''4446550''>For</span> <span m=''4446650''>example,</span> <span m=''4446980''>this</span>
  <span m=''4447170''>fold</span> <span m=''4447460''>is</span> <span m=''4447940''>safe</span>
  <span m=''4448380''>because</span> <span m=''4448670''>it</span> <span m=''4448760''>folds</span>
  <span m=''4449110''>this</span> <span m=''4449210''>on</span> <span m=''4449330''>to</span>
  <span m=''4449410''>this,</span> <span m=''4449710''>and it</span> <span m=''4450090''>folds
  blank</span> <span m=''4450370''>space</span> <span m=''4450620''>onto</span> <span
  m=''4451030''>blank</span> <span m=''4451260''>space</span> <span m=''4451740''>if
  I</span> <span m=''4452460''>do it</span> <span m=''4452750''>right.</span> <span
  m=''4458140''>And</span> <span m=''4458380''>keep</span> <span m=''4458590''>doing</span>
  <span m=''4458870''>that.</span> <span m=''4459390''>Now</span> <span m=''4459560''>when</span>
  <span m=''4459730''>I</span> <span m=''4459790''>make</span> <span m=''4460000''>a</span>
  <span m=''4460050''>fold</span> <span m=''4460290''>like</span> <span m=''4460470''>this,</span>
  <span m=''4461110''>what</span> <span m=''4461270''>happens</span> <span m=''4462220''>is</span>
  <span m=''4462370''>I</span> <span m=''4462430''>can</span> <span m=''4462570''>think</span>
  <span m=''4462770''>of</span> <span m=''4462900''>this</span> <span m=''4463110''>region</span>
  <span m=''4464640''>that</span> <span m=''4464650''>I</span> <span m=''4464720''>folded--</span>
  <span m=''4465200''>the</span> <span m=''4465280''>smaller</span> <span m=''4465810''>side--</span>
  <span m=''4466480''>as</span> <span m=''4466790''>disappearing.</span> <span m=''4468240''>It</span>
  <span m=''4468350''>just</span> <span m=''4468530''>got</span> <span m=''4468690''>absorbed</span>
  <span m=''4469830''>into</span> <span m=''4470020''>the</span> <span m=''4470120''>paper</span>
  <span m=''4470410''>here.</span> </p><p><span m=''4470940''>So</span> <span m=''4471550''>the</span>
  <span m=''4471630''>graph</span> <span m=''4472000''>that I was</span> <span m=''4472170''>trying</span>
  <span m=''4472370''>to</span> <span m=''4472430''>line</span> <span m=''4472650''>up</span>
  <span m=''4472830''>got</span> <span m=''4473080''>smaller.</span> <span m=''4473850''>That''s</span>
  <span m=''4474040''>clearly</span> <span m=''4474370''>a</span> <span m=''4474420''>good</span>
  <span m=''4474650''>thing.</span> <span m=''4475570''>Makes</span> <span m=''4475800''>my</span>
  <span m=''4475890''>problem</span> <span m=''4476140''>easier.</span> <span m=''4477020''>The</span>
  <span m=''4477110''>piece</span> <span m=''4477300''>of</span> <span m=''4477370''>paper</span>
  <span m=''4477960''>I</span> <span m=''4478080''>was</span> <span m=''4478210''>folding</span>
  <span m=''4478770''>also</span> <span m=''4479090''>got</span> <span m=''4479280''>smaller.</span>
  <span m=''4480210''>That''s</span> <span m=''4480420''>a</span> <span m=''4480480''>good</span>
  <span m=''4480670''>thing.</span> <span m=''4482300''>But</span> <span m=''4482320''>that''s</span>
  <span m=''4482540''>not</span> <span m=''4482690''>always</span> <span m=''4482870''>true.</span>
  </p><p><span m=''4485610''>Suppose</span> <span m=''4486140''>you</span> <span m=''4486260''>had</span>
  <span m=''4487810''>a</span> <span m=''4487830''>piece</span> <span m=''4488020''>of</span>
  <span m=''4488060''>paper</span> <span m=''4488280''>like</span> <span m=''4488450''>this,</span>
  <span m=''4488745''>which</span> <span m=''4489040''>could</span> <span m=''4489140''>happen</span>
  <span m=''4489610''>after a</span> <span m=''4489960''>bunch</span> <span m=''4490180''>folding,</span>
  <span m=''4491020''>and</span> <span m=''4491120''>then</span> <span m=''4491220''>you</span>
  <span m=''4491300''>fold</span> <span m=''4491550''>along</span> <span m=''4492100''>a</span>
  <span m=''4492250''>line</span> <span m=''4492560''>like</span> <span m=''4492760''>that</span>
  <span m=''4493270''>because,</span> <span m=''4493830''>for</span> <span m=''4493920''>example,</span>
  <span m=''4494240''>your</span> <span m=''4494440''>passage</span> <span m=''4494880''>looks</span>
  <span m=''4495060''>like</span> <span m=''4495200''>that</span> <span m=''4495650''>or
  something.</span> </p><p><span m=''4496700''>When</span> <span m=''4496870''>I</span>
  <span m=''4496910''>make</span> <span m=''4497130''>the</span> <span m=''4497220''>fold--</span>
  <span m=''4498350''>this</span> <span m=''4498480''>has</span> <span m=''4498650''>to</span>
  <span m=''4498730''>go</span> <span m=''4498860''>off.</span> <span m=''4499910''>When</span>
  <span m=''4500090''>I</span> <span m=''4500140''>make</span> <span m=''4500370''>the</span>
  <span m=''4500430''>fold</span> <span m=''4501300''>I</span> <span m=''4501600''>get</span>
  <span m=''4502780''>this</span> <span m=''4503910''>crazy</span> <span m=''4504240''>thing.</span>
  <span m=''4504880''>Not</span> <span m=''4505060''>drawn</span> <span m=''4505280''>to</span>
  <span m=''4505330''>scale.</span> <span m=''4506600''>And</span> <span m=''4506810''>this</span>
  <span m=''4507320''>polygon</span> <span m=''4507800''>does</span> <span m=''4507940''>not</span>
  <span m=''4508160''>fit</span> <span m=''4508420''>inside</span> <span m=''4508810''>this</span>
  <span m=''4508950''>polygon.</span> <span m=''4509380''>So</span> <span m=''4509540''>my</span>
  <span m=''4509670''>paper</span> <span m=''4510090''>got</span> <span m=''4510500''>bigger</span>
  <span m=''4510810''>in</span> <span m=''4510890''>some</span> <span m=''4511080''>places.</span>
  </p><p><span m=''4511910''>And</span> <span m=''4512100''>that''s</span> <span m=''4512320''>a</span>
  <span m=''4512390''>worry,</span> <span m=''4512880''>because</span> <span m=''4513160''>now</span>
  <span m=''4513400''>I have</span> <span m=''4513600''>the</span> <span m=''4513700''>stuff--</span>
  <span m=''4514110''>maybe</span> <span m=''4514420''>it</span> <span m=''4514480''>happens</span>
  <span m=''4514790''>to</span> <span m=''4514860''>be</span> <span m=''4514960''>blank</span>
  <span m=''4515230''>space.</span> <span m=''4515960''>Maybe</span> <span m=''4516160''>there''s</span>
  <span m=''4516340''>other</span> <span m=''4516570''>junk</span> <span m=''4516920''>that</span>
  <span m=''4517010''>got</span> <span m=''4517210''>out</span> <span m=''4517350''>here.</span>
  <span m=''4518240''>And</span> <span m=''4518460''>now</span> <span m=''4518560''>have</span>
  <span m=''4518690''>to</span> <span m=''4519060''>worry</span> <span m=''4519440''>about</span>
  <span m=''4519670''>collisions</span> <span m=''4520100''>with</span> <span m=''4520240''>this</span>
  <span m=''4520390''>bigger</span> <span m=''4520680''>piece</span> <span m=''4520890''>of</span>
  <span m=''4520960''>paper.</span> <span m=''4521360''>And</span> <span m=''4521460''>this</span>
  <span m=''4521480''>is</span> <span m=''4521610''>always</span> <span m=''4521840''>our</span>
  <span m=''4521950''>sticking</span> <span m=''4522290''>point,</span> <span m=''4523960''>but</span>
  <span m=''4525340''>there''s</span> <span m=''4525570''>some</span> <span m=''4525610''>magic</span>
  <span m=''4526000''>you</span> <span m=''4526110''>can</span> <span m=''4526250''>do.</span>
  <span m=''4528550''>In</span> <span m=''4528650''>fact,</span> <span m=''4528920''>the</span>
  <span m=''4529010''>picture</span> <span m=''4529320''>cannot</span> <span m=''4529630''>look</span>
  <span m=''4529770''>like</span> <span m=''4529940''>this.</span> </p><p><span m=''4533110''>Because,</span>
  <span m=''4534610''>look,</span> <span m=''4534880''>you''ve</span> <span m=''4535070''>got</span>
  <span m=''4535290''>some</span> <span m=''4535480''>portion</span> <span m=''4535780''>of</span>
  <span m=''4535850''>your</span> <span m=''4535960''>passage</span> <span m=''4536820''>to</span>
  <span m=''4536960''>the</span> <span m=''4537040''>left</span> <span m=''4537300''>of</span>
  <span m=''4537380''>the</span> <span m=''4537460''>crease.</span> <span m=''4538240''>You''ve</span>
  <span m=''4538380''>got</span> <span m=''4538550''>some</span> <span m=''4538710''>portion</span>
  <span m=''4539020''>of the</span> <span m=''4539100''>passage</span> <span m=''4539530''>to</span>
  <span m=''4539610''>the</span> <span m=''4539700''>right.</span> <span m=''4540240''>One</span>
  <span m=''4540470''>of</span> <span m=''4540560''>them</span> <span m=''4540680''>has</span>
  <span m=''4540900''>to</span> <span m=''4541000''>be</span> <span m=''4541110''>shorter.</span>
  <span m=''4542460''>Plus,</span> <span m=''4543070''>this</span> <span m=''4543230''>is</span>
  <span m=''4543340''>a</span> <span m=''4543390''>line</span> <span m=''4543610''>of</span>
  <span m=''4543670''>symmetry.</span> <span m=''4544980''>So</span> <span m=''4545700''>wherever</span>
  <span m=''4546060''>I</span> <span m=''4546120''>have</span> <span m=''4546887''>a</span>
  <span m=''4548110''>portion</span> <span m=''4548400''>of</span> <span m=''4548480''>my</span>
  <span m=''4548590''>passage</span> <span m=''4548990''>over</span> <span m=''4549120''>here,</span>
  <span m=''4549680''>I</span> <span m=''4549790''>will have</span> <span m=''4550040''>a
  portion</span> <span m=''4550400''>of my</span> <span m=''4550460''>passage</span>
  <span m=''4550910''>over</span> <span m=''4551120''>here</span> <span m=''4551660''>until</span>
  <span m=''4552070''>I</span> <span m=''4552120''>run</span> <span m=''4552360''>out</span>
  <span m=''4552460''>of</span> <span m=''4552550''>length.</span> <span m=''4552880''>One</span>
  <span m=''4553090''>of</span> <span m=''4553140''>them</span> <span m=''4553260''>is</span>
  <span m=''4553320''>shorter.</span> </p><p><span m=''4554420''>So</span> <span m=''4554640''>the</span>
  <span m=''4554750''>shorter</span> <span m=''4555160''>one</span> <span m=''4555400''>like</span>
  <span m=''4555570''>this</span> <span m=''4555750''>one</span> <span m=''4556380''>gets</span>
  <span m=''4556590''>totally</span> <span m=''4557000''>absorbed</span> <span m=''4557360''>by</span>
  <span m=''4557470''>the</span> <span m=''4557560''>larger</span> <span m=''4557920''>one.</span>
  <span m=''4558670''>So the</span> <span m=''4558800''>shorter</span> <span m=''4559140''>side</span>
  <span m=''4559420''>always</span> <span m=''4559640''>disappears.</span> <span m=''4561410''>So</span>
  <span m=''4561570''>in</span> <span m=''4561640''>this</span> <span m=''4561800''>picture,</span>
  <span m=''4562750''>I</span> <span m=''4562840''>have</span> <span m=''4563150''>the</span>
  <span m=''4563250''>long</span> <span m=''4563580''>side</span> <span m=''4563870''>of</span>
  <span m=''4563920''>my</span> <span m=''4564050''>passage,</span> <span m=''4564620''>and</span>
  <span m=''4564760''>it''s</span> <span m=''4564890''>really</span> <span m=''4565110''>a</span>
  <span m=''4565170''>subset</span> <span m=''4565560''>of</span> <span m=''4565650''>the</span>
  <span m=''4565770''>original.</span> <span m=''4567210''>If</span> <span m=''4567400''>I</span>
  <span m=''4567480''>reduce</span> <span m=''4567910''>this</span> <span m=''4568130''>to</span>
  <span m=''4568240''>the</span> <span m=''4568340''>convex</span> <span m=''4568780''>hull,</span>
  <span m=''4570330''>like</span> <span m=''4570510''>this,</span> <span m=''4572340''>this</span>
  <span m=''4572450''>stuff</span> <span m=''4572740''>disappears.</span> <span m=''4574460''>And</span>
  <span m=''4574750''>in</span> <span m=''4574840''>general,</span> <span m=''4575750''>if</span>
  <span m=''4575910''>you</span> <span m=''4576050''>do</span> <span m=''4576240''>this</span>
  <span m=''4577220''>fold</span> <span m=''4577420''>down</span> <span m=''4577610''>to</span>
  <span m=''4577670''>convex</span> <span m=''4578070''>hull,</span> <span m=''4578430''>this</span>
  <span m=''4578630''>repeat</span> <span m=''4579780''>goes</span> <span m=''4579990''>back</span>
  <span m=''4580220''>to</span> <span m=''4580320''>step</span> <span m=''4580600''>two.</span>
  </p><p><span m=''4582060''>If you</span> <span m=''4582140''>fold</span> <span m=''4582350''>down</span>
  <span m=''4582530''>to</span> <span m=''4582600''>the</span> <span m=''4582700''>convex</span>
  <span m=''4583060''>hull,</span> <span m=''4583240''>you</span> <span m=''4583350''>can</span>
  <span m=''4583490''>show</span> <span m=''4583700''>that</span> <span m=''4583840''>not</span>
  <span m=''4584110''>only</span> <span m=''4584360''>does</span> <span m=''4584580''>your</span>
  <span m=''4584740''>passage--</span> <span m=''4585340''>the</span> <span m=''4585430''>thing</span>
  <span m=''4585570''>you</span> <span m=''4585690''>want</span> <span m=''4585810''>to</span>
  <span m=''4585870''>cut</span> <span m=''4586060''>out--</span> <span m=''4586300''>get</span>
  <span m=''4586460''>smaller,</span> <span m=''4586990''>but</span> <span m=''4587240''>you</span>
  <span m=''4587410''>piece</span> <span m=''4587640''>of</span> <span m=''4587710''>paper</span>
  <span m=''4588150''>also</span> <span m=''4588440''>gets</span> <span m=''4588660''>smaller.</span>
  <span m=''4590060''>Guaranteed.</span> <span m=''4590610''>And</span> <span m=''4590850''>once</span>
  <span m=''4591460''>you know</span> <span m=''4591860''>the paper</span> <span m=''4592160''>get</span>
  <span m=''4592290''>smaller</span> <span m=''4592630''>and</span> <span m=''4592950''>your</span>
  <span m=''4593420''>things</span> <span m=''4593600''>you''re</span> <span m=''4593710''>trying</span>
  <span m=''4593920''>to</span> <span m=''4593960''>align</span> <span m=''4594210''>get</span>
  <span m=''4594350''>smaller,</span> <span m=''4594980''>you</span> <span m=''4595100''>know</span>
  <span m=''4595350''>that</span> <span m=''4595480''>every</span> <span m=''4595710''>move</span>
  <span m=''4595920''>is</span> <span m=''4595980''>safe.</span> <span m=''4597740''>So</span>
  <span m=''4598230''>you</span> <span m=''4598380''>never</span> <span m=''4598650''>get</span>
  <span m=''4598890''>stuck</span> <span m=''4599700''>by</span> <span m=''4599810''>following</span>
  <span m=''4600160''>this</span> <span m=''4600320''>algorithm.</span> <span m=''4600830''>This</span>
  <span m=''4601000''>works</span> <span m=''4601130''>for</span> <span m=''4601340''>polygons</span>
  <span m=''4602340''>with</span> <span m=''4602540''>margin,</span> <span m=''4603440''>but</span>
  <span m=''4603600''>not</span> <span m=''4603870''>in</span> <span m=''4604020''>any</span>
  <span m=''4604250''>other</span> <span m=''4604430''>situation</span> <span m=''4604980''>as</span>
  <span m=''4605070''>far</span> <span m=''4605210''>as</span> <span m=''4605300''>we</span>
  <span m=''4605390''>can</span> <span m=''4605510''>tell.</span> </p><p><span m=''4608740''>Cool.</span>
  <span m=''4612470''>The</span> <span m=''4612570''>last</span> <span m=''4612840''>thing</span>
  <span m=''4612990''>I</span> <span m=''4613020''>wanted</span> <span m=''4613260''>to</span>
  <span m=''4613370''>leave</span> <span m=''4613580''>you</span> <span m=''4613760''>on</span>
  <span m=''4614050''>is</span> <span m=''4615020''>going</span> <span m=''4615350''>out</span>
  <span m=''4616660''>a</span> <span m=''4617210''>little</span> <span m=''4617460''>way</span>
  <span m=''4617620''>from</span> <span m=''4618990''>regular</span> <span m=''4619500''>2D</span>
  <span m=''4619900''>flat</span> <span m=''4620200''>sheets</span> <span m=''4620440''>of</span>
  <span m=''4620480''>paper.</span> <span m=''4621530''>You</span> <span m=''4621700''>can</span>
  <span m=''4621810''>generalize</span> <span m=''4622520''>and</span> <span m=''4622710''>go</span>
  <span m=''4622840''>up</span> <span m=''4622960''>a</span> <span m=''4623030''>dimension</span>
  <span m=''4624920''>to</span> <span m=''4626720''>folding</span> <span m=''4627830''>polyhedra</span>
  <span m=''4628470''>surface.</span> <span m=''4629000''>Here,</span> <span m=''4629180''>a
  surface</span> <span m=''4629610''>of</span> <span m=''4629710''>a</span> <span
  m=''4629790''>polyhedron.</span> </p><p><span m=''4630630''>You''ve</span> <span
  m=''4630760''>probably</span> <span m=''4631030''>done</span> <span m=''4631220''>this.</span>
  <span m=''4631410''>You</span> <span m=''4631500''>take</span> <span m=''4631780''>a</span>
  <span m=''4632120''>cereal</span> <span m=''4632460''>box</span> <span m=''4633000''>and</span>
  <span m=''4633300''>you</span> <span m=''4633440''>can</span> <span m=''4633580''>collapse</span>
  <span m=''4633990''>it</span> <span m=''4634090''>flat.</span> <span m=''4635730''>Is</span>
  <span m=''4635860''>that</span> <span m=''4635980''>always</span> <span m=''4636200''>possible?</span>
  <span m=''4637180''>It''s</span> <span m=''4637400''>called the</span> <span m=''4637640''>flattening</span>
  <span m=''4638070''>problem,</span> <span m=''4639220''>and</span> <span m=''4639410''>the</span>
  <span m=''4639500''>answer</span> <span m=''4639720''>is</span> <span m=''4639810''>yes.</span>
  <span m=''4641210''>And</span> <span m=''4641450''>you</span> <span m=''4641540''>can</span>
  <span m=''4641720''>think</span> <span m=''4641920''>of</span> <span m=''4642030''>it</span>
  <span m=''4642130''>as</span> <span m=''4642240''>a</span> <span m=''4642300''>fold
  and</span> <span m=''4642640''>cut</span> <span m=''4642890''>problem,</span> <span
  m=''4643390''>because</span> <span m=''4643690''>of</span> <span m=''4643760''>the</span>
  <span m=''4643830''>fold and</span> <span m=''4644120''>cut</span> <span m=''4644350''>problem,</span>
  <span m=''4644670''>you</span> <span m=''4644770''>have</span> <span m=''4645200''>some</span>
  <span m=''4645440''>polygon</span> <span m=''4645870''>like</span> <span m=''4646010''>this</span>
  <span m=''4646180''>diamond.</span> <span m=''4647070''>You</span> <span m=''4647230''>make</span>
  <span m=''4647480''>some</span> <span m=''4647920''>collection</span> <span m=''4648300''>of</span>
  <span m=''4648390''>folds</span> <span m=''4649170''>that</span> <span m=''4649260''>brings</span>
  <span m=''4649550''>the</span> <span m=''4649630''>boundary</span> <span m=''4650040''>of</span>
  <span m=''4650100''>the</span> <span m=''4650190''>diamond</span> <span m=''4651050''>to</span>
  <span m=''4651190''>align.</span> </p><p><span m=''4652690''>So</span> <span m=''4652800''>if</span>
  <span m=''4652870''>you</span> <span m=''4652960''>forget</span> <span m=''4653340''>about</span>
  <span m=''4653550''>what''s</span> <span m=''4653700''>happening</span> <span m=''4654030''>on</span>
  <span m=''4654100''>the</span> <span m=''4654190''>inside</span> <span m=''4654500''>of</span>
  <span m=''4654540''>the</span> <span m=''4654640''>paper--</span> <span m=''4654910''>you</span>
  <span m=''4654990''>just</span> <span m=''4655220''>look</span> <span m=''4655340''>at</span>
  <span m=''4655430''>the</span> <span m=''4655520''>boundary</span> <span m=''4655960''>of</span>
  <span m=''4656010''>the</span> <span m=''4656100''>paper--</span> <span m=''4657110''>you''re</span>
  <span m=''4657250''>folding</span> <span m=''4657760''>that</span> <span m=''4658270''>one-dimensional</span>
  <span m=''4659160''>boundary</span> <span m=''4660370''>so</span> <span m=''4660620''>that</span>
  <span m=''4660750''>it</span> <span m=''4660850''>collapses</span> <span m=''4661410''>down</span>
  <span m=''4661630''>to</span> <span m=''4661760''>a</span> <span m=''4661820''>single</span>
  <span m=''4662180''>line.</span> <span m=''4663590''>What</span> <span m=''4663770''>I</span>
  <span m=''4663850''>want</span> <span m=''4664070''>to</span> <span m=''4664150''>do</span>
  <span m=''4664360''>is</span> <span m=''4664600''>this</span> <span m=''4665290''>up</span>
  <span m=''4665460''>a</span> <span m=''4665520''>dimension.</span> <span m=''4666840''>I</span>
  <span m=''4666950''>take</span> <span m=''4667180''>a</span> <span m=''4667280''>3D</span>
  <span m=''4668360''>cube</span> <span m=''4668750''>of</span> <span m=''4668900''>paper--</span>
  <span m=''4669350''>solid</span> <span m=''4669940''>cube.</span> <span m=''4671510''>I</span>
  <span m=''4671680''>have</span> <span m=''4672640''>embedded</span> <span m=''4672950''>within</span>
  <span m=''4673230''>it</span> <span m=''4673390''>some</span> <span m=''4675030''>polygons</span>
  <span m=''4675770''>that</span> <span m=''4675880''>I</span> <span m=''4675930''>want</span>
  <span m=''4676120''>to</span> <span m=''4676170''>bring</span> <span m=''4676570''>to</span>
  <span m=''4676720''>a</span> <span m=''4676780''>common</span> <span m=''4677990''>plane.</span>
  <span m=''4680220''>And</span> <span m=''4680630''>I</span> <span m=''4680670''>want</span>
  <span m=''4680850''>to</span> <span m=''4680890''>fold</span> <span m=''4681330''>the</span>
  <span m=''4681410''>solid</span> <span m=''4681890''>cube</span> <span m=''4682830''>through</span>
  <span m=''4683180''>four</span> <span m=''4683400''>dimensions,</span> <span m=''4684690''>but</span>
  <span m=''4684910''>flat</span> <span m=''4685440''>so</span> <span m=''4685600''>it</span>
  <span m=''4685680''>ends</span> <span m=''4685850''>up</span> <span m=''4685970''>back</span>
  <span m=''4686250''>in</span> <span m=''4686370''>three</span> <span m=''4686610''>dimensions.</span>
  <span m=''4687520''>I</span> <span m=''4687610''>get</span> <span m=''4687760''>a</span>
  <span m=''4687820''>different</span> <span m=''4688190''>3D</span> <span m=''4688520''>solid,</span>
  <span m=''4689490''>but</span> <span m=''4689690''>with</span> <span m=''4690130''>multiple</span>
  <span m=''4690590''>layers</span> <span m=''4691280''>right</span> <span m=''4691470''>on</span>
  <span m=''4691540''>top</span> <span m=''4691790''>of each</span> <span m=''4691950''>other--</span>
  <span m=''4692670''>little</span> <span m=''4692910''>bit</span> <span m=''4693030''>a</span>
  <span m=''4693080''>fourth</span> <span m=''4693330''>dimension</span> <span m=''4694260''>hanging</span>
  <span m=''4694510''>out</span> <span m=''4694670''>there.</span> </p><p><span m=''4695050''>But</span>
  <span m=''4695150''>if</span> <span m=''4695270''>I</span> <span m=''4695320''>just</span>
  <span m=''4695590''>look</span> <span m=''4695740''>at</span> <span m=''4695810''>what''s</span>
  <span m=''4695970''>happening</span> <span m=''4696310''>to</span> <span m=''4696410''>the</span>
  <span m=''4696500''>boundary</span> <span m=''4697020''>of</span> <span m=''4697100''>my</span>
  <span m=''4697300''>polyhedron--</span> <span m=''4697960''>say</span> <span m=''4698170''>I
  start</span> <span m=''4698380''>with</span> <span m=''4698510''>a</span> <span
  m=''4698560''>dodecahedron</span> <span m=''4699120''>or</span> <span m=''4699310''>something</span>
  <span m=''4699630''>embedded</span> <span m=''4700000''>in</span> <span m=''4700110''>there--</span>
  <span m=''4701140''>and</span> <span m=''4701630''>I</span> <span m=''4701740''>want</span>
  <span m=''4701950''>to</span> <span m=''4701990''>fold</span> <span m=''4702320''>this</span>
  <span m=''4702490''>thing</span> <span m=''4702670''>so</span> <span m=''4702890''>all</span>
  <span m=''4703140''>the</span> <span m=''4703230''>sides</span> <span m=''4703590''>of</span>
  <span m=''4703660''>the</span> <span m=''4703760''>dodecahedron</span> <span m=''4704430''>come</span>
  <span m=''4704640''>to</span> <span m=''4704730''>a</span> <span m=''4704770''>common</span>
  <span m=''4705110''>plane.</span> <span m=''4705980''>That</span> <span m=''4706200''>is</span>
  <span m=''4706380''>the</span> <span m=''4706550''>3D</span> <span m=''4707020''>folding</span>
  <span m=''4707310''>cup</span> <span m=''4707510''>problem.</span> <span m=''4708210''>It</span>
  <span m=''4708330''>remains</span> <span m=''4708680''>unsolved.</span> </p><p><span
  m=''4709980''>I</span> <span m=''4710120''>suspect</span> <span m=''4710980''>it''s</span>
  <span m=''4711200''>possible</span> <span m=''4711460''>to</span> <span m=''4711720''>solve</span>
  <span m=''4712080''>even</span> <span m=''4712320''>with</span> <span m=''4712480''>straight</span>
  <span m=''4712740''>skeletons</span> <span m=''4713390''>and</span> <span m=''4713550''>perpendiculars,</span>
  <span m=''4714290''>but</span> <span m=''4714960''>it''s</span> <span m=''4715130''>really</span>
  <span m=''4715360''>hard</span> <span m=''4715620''>to</span> <span m=''4715670''>draw</span>
  <span m=''4715840''>the</span> <span m=''4715940''>pictures.</span> <span m=''4717100''>So</span>
  <span m=''4717420''>we</span> <span m=''4717610''>have</span> <span m=''4717760''>not</span>
  <span m=''4718700''>resolved</span> <span m=''4719020''>that</span> <span m=''4719180''>one</span>
  <span m=''4719330''>way</span> <span m=''4719480''>or the</span> <span m=''4719640''>other.</span>
  <span m=''4720320''>But</span> <span m=''4720490''>the</span> <span m=''4720580''>boundary</span>
  <span m=''4721060''>problem--</span> <span m=''4721590''>forget</span> <span m=''4721930''>about</span>
  <span m=''4722160''>what''s</span> <span m=''4722310''>happening</span> <span m=''4722620''>to</span>
  <span m=''4722700''>the</span> <span m=''4722870''>interior</span> <span m=''4723260''>and
  the</span> <span m=''4723430''>exterior</span> <span m=''4723870''>of</span> <span
  m=''4723930''>the</span> <span m=''4724010''>dodecahedron.</span> <span m=''4724720''>If
  you</span> <span m=''4724890''>just</span> <span m=''4725130''>look</span> <span
  m=''4725240''>at</span> <span m=''4725310''>the</span> <span m=''4725390''>surface</span>
  <span m=''4725800''>of</span> <span m=''4725850''>the</span> <span m=''4725940''>dodecahedron,</span>
  <span m=''4726530''>that</span> <span m=''4726780''>you</span> <span m=''4726860''>can</span>
  <span m=''4726990''>fold</span> <span m=''4727150''>in</span> <span m=''4727290''>3D--</span>
  <span m=''4728470''>we</span> <span m=''4728570''>think--</span> <span m=''4729630''>and</span>
  <span m=''4730810''>you</span> <span m=''4731060''>can</span> <span m=''4731220''>show</span>
  <span m=''4731970''>and</span> <span m=''4732260''>burn</span> <span m=''4732500''>in</span>
  <span m=''4732600''>haze</span> <span m=''4733500''>from</span> <span m=''4733760''>the</span>
  <span m=''4733870''>complexity</span> <span m=''4734370''>proof a</span> <span m=''4734710''>couple</span>
  <span m=''4734950''>lectures</span> <span m=''4735270''>ago,</span> <span m=''4736330''>and</span>
  <span m=''4736690''>also</span> <span m=''4737170''>on</span> <span m=''4737380''>this</span>
  <span m=''4737640''>disk-packing</span> <span m=''4738690''>method</span> <span
  m=''4739310''>with our</span> <span m=''4739420''>co-authors.</span> </p><p><span
  m=''4740460''>They</span> <span m=''4740590''>prove</span> <span m=''4740900''>just</span>
  <span m=''4741190''>two</span> <span m=''4741310''>years</span> <span m=''4741600''>ago</span>
  <span m=''4742880''>that</span> <span m=''4743160''>if</span> <span m=''4743260''>you</span>
  <span m=''4743350''>have</span> <span m=''4743550''>any</span> <span m=''4743890''>orientable</span>
  <span m=''4744660''>manifold,</span> <span m=''4746160''>which</span> <span m=''4746480''>is</span>
  <span m=''4746570''>things</span> <span m=''4746770''>like</span> <span m=''4746960''>polyhedron</span>
  <span m=''4748720''>but</span> <span m=''4748870''>no</span> <span m=''4749080''>Mobius</span>
  <span m=''4749460''>strips,</span> <span m=''4749830''>no</span> <span m=''4749990''>Klein</span>
  <span m=''4750290''>bundles,</span> <span m=''4750750''>and</span> <span m=''4750860''>other</span>
  <span m=''4751160''>ugly</span> <span m=''4751510''>things.</span> <span m=''4753460''>They</span>
  <span m=''4753550''>have</span> <span m=''4753660''>to</span> <span m=''4753740''>be</span>
  <span m=''4753850''>manifold,</span> <span m=''4754480''>so</span> <span m=''4754640''>you''re</span>
  <span m=''4754760''>not</span> <span m=''4754940''>allowed</span> <span m=''4755330''>to</span>
  <span m=''4756290''>join</span> <span m=''4756620''>three</span> <span m=''4757070''>triangles</span>
  <span m=''4757740''>together</span> <span m=''4758800''>along</span> <span m=''4759260''>a</span>
  <span m=''4759340''>single</span> <span m=''4759700''>edge.</span> <span m=''4760760''>That</span>
  <span m=''4760920''>would</span> <span m=''4761040''>be</span> <span m=''4761470''>forbidden.</span>
  <span m=''4763010''>So</span> <span m=''4763100''>it''s</span> <span m=''4763240''>locally</span>
  <span m=''4763600''>flat.</span> </p><p><span m=''4764970''>In such</span> <span
  m=''4765290''>a case,</span> <span m=''4766140''>you</span> <span m=''4766270''>can</span>
  <span m=''4766490''>flatten</span> <span m=''4767100''>the</span> <span m=''4767210''>thing.</span>
  <span m=''4767870''>And</span> <span m=''4768030''>the</span> <span m=''4768110''>proof</span>
  <span m=''4768440''>is</span> <span m=''4768750''>very</span> <span m=''4769070''>similar</span>
  <span m=''4769700''>to</span> <span m=''4769860''>the</span> <span m=''4769970''>disk-packing</span>
  <span m=''4771900''>method</span> <span m=''4772300''>of</span> <span m=''4772380''>fold
  and</span> <span m=''4772680''>cut,</span> <span m=''4772910''>and</span> <span
  m=''4773310''>in</span> <span m=''4773710''>the</span> <span m=''4773810''>textbook</span>
  <span m=''4774230''>we</span> <span m=''4774330''>talk</span> <span m=''4774570''>about</span>
  <span m=''4774760''>how</span> <span m=''4774890''>do you</span> <span m=''4775000''>apply</span>
  <span m=''4775350''>that</span> <span m=''4776020''>to</span> <span m=''4776170''>do</span>
  <span m=''4776470''>something</span> <span m=''4776840''>that''s</span> <span m=''4776980''>just</span>
  <span m=''4777230''>like</span> <span m=''4777440''>a</span> <span m=''4777510''>sphere.</span>
  <span m=''4777805''>A</span> <span m=''4778100''>regular</span> <span m=''4778460''>polyhedron.</span>
  <span m=''4779600''>That''s</span> <span m=''4779810''>pretty</span> <span m=''4780050''>easy</span>
  <span m=''4780280''>to</span> <span m=''4780380''>do</span> <span m=''4780520''>with</span>
  <span m=''4780670''>the disk-packing</span> <span m=''4781150''>method.</span> <span
  m=''4781490''>They</span> <span m=''4781630''>generalize</span> <span m=''4782170''>it</span>
  <span m=''4782270''>to</span> <span m=''4782360''>the</span> <span m=''4782450''>case</span>
  <span m=''4782680''>where</span> <span m=''4782820''>you</span> <span m=''4782890''>have</span>
  <span m=''4784020''>polyhedral</span> <span m=''4784810''>doughnuts</span> <span
  m=''4785440''>and</span> <span m=''4785540''>all</span> <span m=''4785650''>sorts</span>
  <span m=''4785900''>of</span> <span m=''4786500''>fun</span> <span m=''4786780''>things.</span>
  </p><p><span m=''4789200''>But</span> <span m=''4789390''>there''s</span> <span
  m=''4789550''>tons</span> <span m=''4789790''>of</span> <span m=''4789870''>open</span>
  <span m=''4790130''>problems</span> <span m=''4790480''>here.</span> <span m=''4790670''>So</span>
  <span m=''4790830''>we</span> <span m=''4790910''>know</span> <span m=''4791010''>how</span>
  <span m=''4791100''>to</span> <span m=''4791190''>flatten</span> <span m=''4791510''>surfaces,</span>
  <span m=''4792070''>and</span> <span m=''4792130''>that''s</span> <span m=''4792310''>useful</span>
  <span m=''4792610''>for</span> <span m=''4792740''>things</span> <span m=''4792970''>like</span>
  <span m=''4793120''>folding</span> <span m=''4793440''>airbags</span> <span m=''4793880''>flat.</span>
  <span m=''4795190''>But</span> <span m=''4795770''>can</span> <span m=''4795990''>you</span>
  <span m=''4796110''>fold</span> <span m=''4796420''>the</span> <span m=''4796490''>3D</span>
  <span m=''4796830''>solid</span> <span m=''4797230''>flat?</span> <span m=''4798660''>You</span>
  <span m=''4798830''>can</span> <span m=''4798970''>think</span> <span m=''4799210''>of--</span>
  <span m=''4800380''>we</span> <span m=''4800520''>have</span> <span m=''4800820''>here</span>
  <span m=''4801290''>1D</span> <span m=''4801810''>edges</span> <span m=''4802530''>which</span>
  <span m=''4802610''>we</span> <span m=''4802840''>are</span> <span m=''4804030''>collapsing</span>
  <span m=''4804590''>to</span> <span m=''4804780''>a 1D</span> <span m=''4805570''>line.</span>
  <span m=''4806890''>There</span> <span m=''4807070''>is</span> <span m=''4807170''>also</span>
  <span m=''4807660''>zero</span> <span m=''4807930''>dimensional</span> <span m=''4808500''>points</span>
  <span m=''4809010''>here,</span> <span m=''4809900''>which</span> <span m=''4809990''>we</span>
  <span m=''4810160''>don''t</span> <span m=''4810430''>bring</span> <span m=''4810740''>to</span>
  <span m=''4810870''>a</span> <span m=''4810930''>single</span> <span m=''4811360''>point.</span>
  <span m=''4812610''>It''d be</span> <span m=''4812730''>nice</span> <span m=''4813000''>if
  you</span> <span m=''4813300''>could--</span> <span m=''4813640''>the</span> <span
  m=''4813810''>generalized</span> <span m=''4814670''>fold and</span> <span m=''4814890''>cup</span>
  <span m=''4815090''>problem</span> <span m=''4815370''>is</span> <span m=''4815440''>you</span>
  <span m=''4815500''>take</span> <span m=''4815710''>a D</span> <span m=''4815930''>dimensional</span>
  <span m=''4816420''>thing,</span> <span m=''4817430''>and</span> <span m=''4817570''>you</span>
  <span m=''4817650''>have</span> <span m=''4817830''>all</span> <span m=''4818120''>of</span>
  <span m=''4818210''>these--</span> <span m=''4818940''>there''s</span> <span m=''4819130''>0,</span>
  <span m=''4819680''>1,</span> <span m=''4819950''>2,</span> <span m=''4820180''>3--</span>
  <span m=''4820510''>up</span> <span m=''4820660''>to</span> <span m=''4820950''>D
  dimensional</span> <span m=''4821440''>parts</span> <span m=''4821840''>to</span>
  <span m=''4822020''>it--</span> <span m=''4822720''>or</span> <span m=''4822830''>D
  minus</span> <span m=''4823210''>one-dimensional</span> <span m=''4823760''>parts.</span>
  </p><p><span m=''4824340''>You</span> <span m=''4824460''>want</span> <span m=''4824560''>to</span>
  <span m=''4824600''>bring</span> <span m=''4824800''>each</span> <span m=''4825030''>of</span>
  <span m=''4825120''>them</span> <span m=''4825300''>down</span> <span m=''4825790''>into</span>
  <span m=''4826070''>alignment</span> <span m=''4826600''>so</span> <span m=''4826720''>that</span>
  <span m=''4827300''>all</span> <span m=''4827620''>the</span> <span m=''4827760''>vertices</span>
  <span m=''4828490''>come</span> <span m=''4828690''>to</span> <span m=''4828800''>common</span>
  <span m=''4829050''>point,</span> <span m=''4829550''>all</span> <span m=''4829690''>the</span>
  <span m=''4829810''>edges</span> <span m=''4830050''>come</span> <span m=''4830480''>to
  a common</span> <span m=''4830930''>line,</span> <span m=''4831710''>all the</span>
  <span m=''4832090''>two-dimensional</span> <span m=''4832570''>faces</span> <span
  m=''4832940''>come</span> <span m=''4833110''>to a</span> <span m=''4833220''>common</span>
  <span m=''4833530''>plane,</span> <span m=''4833910''>and</span> <span m=''4834100''>so</span>
  <span m=''4834310''>on</span> <span m=''4834510''>up</span> <span m=''4834740''>the</span>
  <span m=''4835370''>dimension</span> <span m=''4835790''>hierarchy.</span> <span
  m=''4836820''>That</span> <span m=''4837010''>is</span> <span m=''4837160''>the</span>
  <span m=''4837310''>ultimate</span> <span m=''4837760''>open</span> <span m=''4838030''>problem.</span>
  <span m=''4838330''>I</span> <span m=''4838410''>think</span> <span m=''4838580''>we</span>
  <span m=''4838680''>end</span> <span m=''4838850''>the</span> <span m=''4838940''>book</span>
  <span m=''4839160''>with</span> <span m=''4839280''>it,</span> <span m=''4840130''>and</span>
  <span m=''4840310''>it''s</span> <span m=''4840460''>totally</span> <span m=''4840840''>unsolved.</span>
  </p><p><span m=''4842890''>Any</span> <span m=''4843090''>questions?</span> <span
  m=''4846310''>That''s</span> <span m=''4846620''>folding</span> <span m=''4846860''>and
  cutting</span> <span m=''4847240''>paper,</span> <span m=''4847630''>and</span>
  <span m=''4847780''>next</span> <span m=''4847960''>time</span> <span m=''4848150''>we''ll</span>
  <span m=''4848240''>start</span> <span m=''4848450''>linkages.</span> </p>'
type: course
uid: a897cdc74509242426a481508e985777

---
None