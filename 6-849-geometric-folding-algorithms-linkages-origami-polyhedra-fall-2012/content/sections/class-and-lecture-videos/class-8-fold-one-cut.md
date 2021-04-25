---
about_this_resource_text: <p><strong>Description:</strong> This lecture begins with
  a demonstration of software for fold and cut. Odd-degree vertices, and a comparison
  of skeleton method and tree method are discussed. Clarifications on the disk-packing
  method with a definition for the number of disks are given.</p> <p><strong>Speaker:</strong>
  Erik Demaine</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: wBR4Q6nFyqk
  parent_uid: a6a020bc3ad7752c2f7b8b541245e455
  title: Video-YouTube-Stream
  type: Video
  uid: 9b9669d692e558817b7378fd725cc9cc
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/wBR4Q6nFyqk/default.jpg
  parent_uid: a6a020bc3ad7752c2f7b8b541245e455
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: ebbdc5d767a5667b865fdea8808f012d
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: a6a020bc3ad7752c2f7b8b541245e455
  title: Video-iTunes U-MP4
  type: Video
  uid: d94363eb273b842f7e456c6761410673
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_class08_300k.mp4
  parent_uid: a6a020bc3ad7752c2f7b8b541245e455
  title: Video-Internet Archive-MP4
  type: Video
  uid: 4b565cb105effe8b43427810c47d2017
- id: 3Play-3PlayYouTubeid-MP4
  media_location: wBR4Q6nFyqk
  parent_uid: a6a020bc3ad7752c2f7b8b541245e455
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 4c4892bd391184d027935abdd1993677
- id: wBR4Q6nFyqk.srt
  parent_uid: a6a020bc3ad7752c2f7b8b541245e455
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/class-8-fold-one-cut/wBR4Q6nFyqk.srt
  title: 3play caption file
  type: null
  uid: b13e181f764b87a99f74dd16c9daa714
- id: wBR4Q6nFyqk.pdf
  parent_uid: a6a020bc3ad7752c2f7b8b541245e455
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/class-8-fold-one-cut/wBR4Q6nFyqk.pdf
  title: 3play pdf file
  type: null
  uid: 9ffe0b2ba358fefe66df372684c175d7
- id: Caption-3Play YouTube id-SRT
  parent_uid: a6a020bc3ad7752c2f7b8b541245e455
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: c1f54a5420398f3e9e34e969522d8564
- id: Transcript-3Play YouTube id-PDF
  parent_uid: a6a020bc3ad7752c2f7b8b541245e455
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: bcd61ee3c1d82b802577c97224b55e41
inline_embed_id: 74984908class8:fold&onecut2064960
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: class-8-fold-one-cut
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/class-8-fold-one-cut
template_type: Tabbed
title: "Class 8: Fold & One Cut\t\t\t\t"
transcript: '<p><span m=''3400''>PROFESSOR ERIK DEMAINE: All</span> <span m=''3480''>right,</span>
  <span m=''3720''>so</span> <span m=''4900''>this</span> <span m=''5160''>lecture</span>
  <span m=''5510''>we</span> <span m=''5660''>talked</span> <span m=''5910''>about</span>
  <span m=''6340''>fold</span> <span m=''6640''>and</span> <span m=''6830''>one</span>
  <span m=''7090''>cut,</span> <span m=''8230''>two</span> <span m=''8420''>methods</span>
  <span m=''8940''>and</span> <span m=''9060''>a</span> <span m=''9120''>little</span>
  <span m=''9290''>bit</span> <span m=''9450''>about</span> <span m=''9690''>polyhedron</span>
  <span m=''10210''>flattening,</span> <span m=''10850''>so most of</span> <span m=''11320''>the</span>
  <span m=''11430''>questions</span> <span m=''11860''>are</span> <span m=''11920''>about</span>
  <span m=''12430''>fold</span> <span m=''12600''>and</span> <span m=''12730''>one</span>
  <span m=''12890''>cut.</span> <span m=''13150''>I''ll</span> <span m=''13430''>stick</span>
  <span m=''13700''>to</span> <span m=''13780''>that.</span> <span m=''14970''>First</span>
  <span m=''15240''>question</span> <span m=''15580''>is,</span> <span m=''16820''>is</span>
  <span m=''16920''>there</span> <span m=''17030''>an</span> <span m=''17110''>equal</span>
  <span m=''17480''>software</span> <span m=''17900''>for</span> <span m=''18020''>doing</span>
  <span m=''18240''>fold-and-cut</span> <span m=''18750''>now?</span> <span m=''19330''>And</span>
  <span m=''19740''>the</span> <span m=''19840''>answer</span> <span m=''20140''>is</span>
  <span m=''20560''>yes,</span> <span m=''20890''>there''s</span> <span m=''21090''>some</span>
  <span m=''21240''>software.</span> <span m=''22710''>Maybe</span> <span m=''22960''>not</span>
  <span m=''23150''>the</span> <span m=''23230''>coolest</span> <span m=''23680''>possible</span>
  <span m=''24100''>yet,</span> <span m=''24420''>but</span> <span m=''24680''>it''s</span>
  <span m=''24890''>getting</span> <span m=''25140''>there.</span> <span m=''25840''>There''s</span>
  <span m=''26080''>two</span> <span m=''26710''>pieces</span> <span m=''26940''>of</span>
  <span m=''27050''>software.</span> <span m=''27450''>One</span> <span m=''27690''>is</span>
  <span m=''27850''>from</span> <span m=''28290''>Final</span> <span m=''28620''>Project</span>
  <span m=''30310''>after</span> <span m=''30640''>this</span> <span m=''30900''>lecture</span>
  <span m=''31170''>was</span> <span m=''31320''>given,</span> <span m=''32080''>2010.</span>
  </p><p><span m=''34150''>And</span> <span m=''34410''>another</span> <span m=''34710''>one</span>
  <span m=''34900''>is</span> <span m=''35110''>in</span> <span m=''35530''>SourceForge</span>
  <span m=''36170''>project</span> <span m=''36610''>called</span> <span m=''37080''>JOrigami,</span>
  <span m=''37790''>or</span> <span m=''38060''>J</span> <span m=''38290''>Origami.</span>
  <span m=''39880''>Both</span> <span m=''40170''>are</span> <span m=''40230''>written</span>
  <span m=''40510''>in</span> <span m=''40660''>Java,</span> <span m=''40980''>I</span>
  <span m=''41080''>believe.</span> <span m=''41640''>I</span> <span m=''41750''>have</span>
  <span m=''42070''>this</span> <span m=''42280''>one.</span> <span m=''43160''>This</span>
  <span m=''43410''>is</span> <span m=''43530''>the</span> <span m=''43640''>swan,</span>
  <span m=''45640''>which</span> <span m=''45710''>you''ve</span> <span m=''45860''>seen</span>
  <span m=''46090''>before.</span> <span m=''47620''>I</span> <span m=''47840''>have</span>
  <span m=''48100''>it</span> <span m=''48350''>here.</span> <span m=''48910''>We</span>
  <span m=''49030''>can</span> <span m=''50070''>try</span> <span m=''50350''>it</span>
  <span m=''50440''>out.</span> <span m=''55790''>It''s</span> <span m=''55970''>not</span>
  <span m=''56140''>online</span> <span m=''56510''>yet,</span> <span m=''56920''>because</span>
  <span m=''57510''>it</span> <span m=''57610''>could</span> <span m=''57800''>use</span>
  <span m=''58020''>some</span> <span m=''58340''>improvements,</span> <span m=''60500''>but</span>
  <span m=''61380''>it''s</span> <span m=''61820''>already</span> <span m=''62240''>pretty</span>
  <span m=''62530''>cool.</span> <span m=''64269''>So</span> <span m=''64420''>you</span>
  <span m=''64569''>can</span> <span m=''64709''>take</span> <span m=''64950''>something</span>
  <span m=''65290''>like</span> <span m=''66440''>the</span> <span m=''66710''>angelfish</span>
  <span m=''67330''>here,</span> <span m=''68390''>and</span> <span m=''69410''>if</span>
  <span m=''69530''>you</span> <span m=''69640''>like,</span> <span m=''72290''>it</span>
  <span m=''72470''>has</span> <span m=''72900''>an</span> <span m=''73090''>editor</span>
  <span m=''73490''>so you can</span> <span m=''73740''>move</span> <span m=''73930''>your</span>
  <span m=''74060''>polygon</span> <span m=''74510''>around.</span> </p><p><span m=''75530''>And</span>
  <span m=''75650''>you</span> <span m=''75750''>can</span> <span m=''75880''>say,</span>
  <span m=''76210''>OK,</span> <span m=''76370''>please</span> <span m=''76740''>give</span>
  <span m=''76920''>me</span> <span m=''77240''>the</span> <span m=''77350''>straight</span>
  <span m=''77990''>skeleton,</span> <span m=''79090''>first</span> <span m=''79490''>straight</span>
  <span m=''79790''>skeleton</span> <span m=''80240''>only,</span> <span m=''80610''>and</span>
  <span m=''80710''>it</span> <span m=''80800''>will</span> <span m=''81600''>update</span>
  <span m=''81940''>on</span> <span m=''82080''>the</span> <span m=''82150''>fly,
  and</span> <span m=''82650''>gives</span> <span m=''82800''>you</span> <span m=''82910''>some</span>
  <span m=''83110''>nice</span> <span m=''83360''>intuition</span> <span m=''83810''>about</span>
  <span m=''84020''>how</span> <span m=''84200''>that</span> <span m=''84600''>works.</span>
  <span m=''85570''>I</span> <span m=''85720''>know</span> <span m=''85790''>that</span>
  <span m=''85950''>looks</span> <span m=''86160''>weird</span> <span m=''86470''>that</span>
  <span m=''86600''>it</span> <span m=''87210''>goes</span> <span m=''87430''>up</span>
  <span m=''87550''>that</span> <span m=''87710''>way,</span> <span m=''87950''>but</span>
  <span m=''88040''>it is</span> <span m=''88290''>correct,</span> <span m=''89900''>because</span>
  <span m=''90100''>it''s</span> <span m=''90270''>bisecting</span> <span m=''91380''>this</span>
  <span m=''91680''>edge</span> <span m=''92940''>and</span> <span m=''95790''>some</span>
  <span m=''96060''>edge,</span> <span m=''96520''>this</span> <span m=''96730''>one</span>
  <span m=''96970''>I</span> <span m=''97050''>guess.</span> <span m=''99020''>They</span>
  <span m=''99280''>meet</span> <span m=''99520''>out</span> <span m=''99670''>here,</span>
  <span m=''99960''>and</span> <span m=''100030''>then</span> <span m=''100150''>you</span>
  <span m=''100260''>go</span> <span m=''100420''>that</span> <span m=''100610''>way.</span>
  <span m=''104290''>So</span> <span m=''104850''>you</span> <span m=''105010''>can
  play</span> <span m=''105240''>with</span> <span m=''105370''>that,</span> <span
  m=''105600''>and</span> <span m=''105680''>then</span> <span m=''105810''>you</span>
  <span m=''105910''>can</span> <span m=''106050''>add</span> <span m=''106220''>in</span>
  <span m=''106310''>the</span> <span m=''106400''>perpendiculars</span> <span m=''107010''>too.</span>
  <span m=''108120''>Takes</span> <span m=''108390''>a</span> <span m=''108440''>little</span>
  <span m=''108610''>bit</span> <span m=''108750''>longer,</span> <span m=''109140''>so</span>
  <span m=''109350''>the</span> <span m=''109450''>refresh</span> <span m=''109870''>may</span>
  <span m=''109960''>not</span> <span m=''110130''>be</span> <span m=''110320''>as</span>
  <span m=''110730''>immediate.</span> <span m=''112390''>But</span> <span m=''113180''>it</span>
  <span m=''113260''>works.</span> <span m=''114810''>It''s</span> <span m=''114890''>really</span>
  <span m=''115640''>complicated</span> <span m=''116190''>behavior</span> <span m=''116590''>in</span>
  <span m=''116670''>there,</span> <span m=''116960''>some</span> <span m=''117800''>spiraling</span>
  <span m=''118055''>in,</span> <span m=''118430''>spiraling</span> <span m=''118860''>out,</span>
  <span m=''119130''>but</span> <span m=''120100''>it''s</span> <span m=''120240''>fairly</span>
  <span m=''120460''>well-behaved.</span> </p><p><span m=''126220''>Here''s</span>
  <span m=''126710''>one</span> <span m=''126920''>of</span> <span m=''127010''>the</span>
  <span m=''127370''>simpler</span> <span m=''127850''>spiraling</span> <span m=''128370''>examples.</span>
  <span m=''133320''>This</span> <span m=''133510''>one</span> <span m=''133670''>is</span>
  <span m=''133770''>stable</span> <span m=''134140''>under</span> <span m=''134330''>perturbation</span>
  <span m=''135140''>more</span> <span m=''135400''>or less.</span> <span m=''135840''>You
  move</span> <span m=''136110''>the</span> <span m=''136210''>vertices</span> <span
  m=''136660''>all a</span> <span m=''136930''>little</span> <span m=''137140''>bit.</span>
  <span m=''138290''>They</span> <span m=''139950''>should</span> <span m=''140220''>continue</span>
  <span m=''140600''>spiraling.</span> <span m=''141420''>It looks</span> <span m=''141440''>like</span>
  <span m=''141695''>that one is a</span> <span m=''141950''>little</span> <span m=''142190''>bit</span>
  <span m=''142370''>degenerate.</span> <span m=''143650''>So</span> <span m=''143850''>we''ll</span>
  <span m=''143960''>go</span> <span m=''144140''>around,</span> <span m=''144620''>and</span>
  <span m=''144880''>as</span> <span m=''144980''>you</span> <span m=''145100''>go</span>
  <span m=''145530''>get</span> <span m=''145690''>bigger and</span> <span m=''145940''>bigger</span>
  <span m=''146170''>pieces</span> <span m=''146410''>of</span> <span m=''146490''>paper,</span>
  <span m=''146900''>you''ll</span> <span m=''147070''>get</span> <span m=''147220''>more</span>
  <span m=''147410''>and</span> <span m=''147470''>more</span> <span m=''147610''>creases.</span>
  <span m=''152210''>I</span> <span m=''152330''>should</span> <span m=''152690''>mention,</span>
  <span m=''154660''>you</span> <span m=''154860''>can</span> <span m=''155010''>add</span>
  <span m=''155260''>new</span> <span m=''155390''>vertices</span> <span m=''155930''>as</span>
  <span m=''156050''>well</span> <span m=''156990''>and</span> <span m=''157130''>draw</span>
  <span m=''158140''>polygon.</span> <span m=''159750''>You</span> <span m=''159970''>can</span>
  <span m=''160460''>delete</span> <span m=''160760''>edges.</span> <span m=''161680''>I''m</span>
  <span m=''161820''>holding</span> <span m=''162130''>all</span> <span m=''162230''>sorts</span>
  <span m=''162470''>of</span> <span m=''162730''>crazy</span> <span m=''163010''>modifier</span>
  <span m=''163430''>keys</span> <span m=''163650''>to</span> <span m=''163730''>make</span>
  <span m=''163890''>this</span> <span m=''164020''>happen,</span> <span m=''164470''>but</span>
  <span m=''164610''>it</span> <span m=''164780''>does</span> <span m=''165410''>work.</span>
  <span m=''167230''>The</span> <span m=''167330''>one</span> <span m=''167560''>other</span>
  <span m=''167740''>thing</span> <span m=''167880''>you</span> <span m=''168010''>can</span>
  <span m=''168120''>do</span> <span m=''168240''>is</span> <span m=''168340''>snap</span>
  <span m=''168670''>to</span> <span m=''168990''>a grid.</span> <span m=''169290''>This
  is</span> <span m=''169480''>probably</span> <span m=''169740''>hard</span> <span
  m=''169960''>to</span> <span m=''170040''>see,</span> <span m=''170300''>but</span>
  <span m=''170540''>there''s</span> <span m=''170840''>a</span> <span m=''170910''>square</span>
  <span m=''171230''>grid</span> <span m=''171410''>underneath.</span> <span m=''172320''>If</span>
  <span m=''172470''>you</span> <span m=''172540''>hold</span> <span m=''172720''>down</span>
  <span m=''172890''>Alt,</span> <span m=''173320''>it</span> <span m=''173500''>snaps</span>
  <span m=''173650''>to</span> <span m=''173780''>a</span> <span m=''173870''>square</span>
  <span m=''174140''>grid.</span> </p><p><span m=''176000''>I</span> <span m=''176120''>have</span>
  <span m=''176360''>one</span> <span m=''176530''>other</span> <span m=''176750''>example</span>
  <span m=''177220''>I''ve</span> <span m=''177440''>prepared.</span> <span m=''178160''>It
  has</span> <span m=''178280''>save</span> <span m=''178520''>and</span> <span m=''178600''>load,</span>
  <span m=''178920''>which is</span> <span m=''179210''>pretty</span> <span m=''179380''>cool.</span>
  <span m=''180330''>And</span> <span m=''182230''>this</span> <span m=''182440''>example</span>
  <span m=''184160''>is</span> <span m=''185150''>one</span> <span m=''185880''>of</span>
  <span m=''185980''>the</span> <span m=''186120''>dense</span> <span m=''186530''>instances.</span>
  <span m=''187980''>Although</span> <span m=''188310''>this</span> <span m=''188510''>one</span>
  <span m=''188680''>has</span> <span m=''188900''>rational</span> <span m=''189300''>multiples,</span>
  <span m=''189720''>so</span> <span m=''189850''>it</span> <span m=''189910''>doesn''t</span>
  <span m=''190120''>actually</span> <span m=''190410''>go</span> <span m=''190600''>forever.</span>
  <span m=''191430''>Because</span> <span m=''191580''>I</span> <span m=''191900''>drew</span>
  <span m=''192240''>it</span> <span m=''192290''>on</span> <span m=''192410''>the</span>
  <span m=''192670''>grid</span> <span m=''193170''>so</span> <span m=''193220''>that</span>
  <span m=''193370''>could</span> <span m=''193540''>get</span> <span m=''193650''>all</span>
  <span m=''193800''>the</span> <span m=''193880''>horizontal</span> <span m=''194145''>and</span>
  <span m=''194410''>verticals.</span> <span m=''195540''>And</span> <span m=''196050''>you</span>
  <span m=''196180''>can</span> <span m=''196320''>see</span> <span m=''196490''>in</span>
  <span m=''196580''>particular</span> <span m=''197660''>it</span> <span m=''197800''>stops</span>
  <span m=''198290''>here,</span> <span m=''200030''>because</span> <span m=''201060''>at</span>
  <span m=''201170''>some</span> <span m=''201340''>point</span> <span m=''201550''>it</span>
  <span m=''201730''>gives</span> <span m=''201970''>up</span> <span m=''202190''>in</span>
  <span m=''202400''>reflecting</span> <span m=''202910''>perpendiculars,</span> <span
  m=''203520''>says</span> <span m=''203760''>that''s</span> <span m=''204000''>enough.</span>
  <span m=''204920''>It won''t</span> <span m=''205100''>draw</span> <span m=''205320''>anymore.</span>
  </p><p><span m=''207190''>So</span> <span m=''207500''>it''s</span> <span m=''208080''>fairly</span>
  <span m=''208650''>robust</span> <span m=''209190''>in</span> <span m=''209260''>that</span>
  <span m=''209430''>sense.</span> <span m=''209750''>Occasionally</span> <span m=''210510''>it''s</span>
  <span m=''210750''>using</span> <span m=''211000''>some</span> <span m=''211820''>straight</span>
  <span m=''212120''>skeleton</span> <span m=''212490''>code</span> <span m=''212700''>they</span>
  <span m=''212840''>did</span> <span m=''213020''>not</span> <span m=''213260''>write,</span>
  <span m=''213520''>and</span> <span m=''213670''>it</span> <span m=''213730''>has</span>
  <span m=''213900''>some</span> <span m=''214080''>issues</span> <span m=''214440''>when</span>
  <span m=''214560''>you</span> <span m=''214630''>have</span> <span m=''214820''>really</span>
  <span m=''215030''>degenerate</span> <span m=''215950''>situations,</span> <span
  m=''216630''>which</span> <span m=''216810''>they</span> <span m=''216970''>tried</span>
  <span m=''217250''>to</span> <span m=''217360''>mitigate.</span> <span m=''218310''>But</span>
  <span m=''218400''>occasionally</span> <span m=''219010''>it''s</span> <span m=''219450''>not</span>
  <span m=''219600''>perfect.</span> <span m=''220020''>But</span> <span m=''220030''>there</span>
  <span m=''220130''>are</span> <span m=''220170''>lots</span> <span m=''220400''>of</span>
  <span m=''220640''>possible</span> <span m=''221020''>follow</span> <span m=''221280''>on</span>
  <span m=''221440''>projects</span> <span m=''221910''>to</span> <span m=''222050''>this</span>
  <span m=''222530''>work,</span> <span m=''223770''>improving</span> <span m=''224170''>the</span>
  <span m=''224600''>user</span> <span m=''224830''>interface.</span> <span m=''225200''>Actually</span>
  <span m=''225450''>putting</span> <span m=''225760''>it on</span> <span m=''225880''>the</span>
  <span m=''225950''>web</span> <span m=''226130''>for</span> <span m=''226250''>people</span>
  <span m=''226590''>to play</span> <span m=''226760''>with,</span> <span m=''226930''>I</span>
  <span m=''226990''>think,</span> <span m=''227180''>would</span> <span m=''227280''>be</span>
  <span m=''227380''>super</span> <span m=''227690''>cool.</span> <span m=''228510''>Alternatively,</span>
  <span m=''229170''>could</span> <span m=''229400''>port</span> <span m=''229600''>it</span>
  <span m=''229720''>to</span> <span m=''229870''>JavaScript--</span> <span m=''230420''>right</span>
  <span m=''230540''>now</span> <span m=''230690''>it''s</span> <span m=''230800''>in</span>
  <span m=''230890''>Java--</span> <span m=''231470''>and</span> <span m=''231620''>make</span>
  <span m=''231790''>it even</span> <span m=''232060''>more</span> <span m=''232360''>accessible</span>
  <span m=''232870''>run</span> <span m=''233310''>on</span> <span m=''233690''>iPhones</span>
  <span m=''234160''>and</span> <span m=''234260''>things</span> <span m=''234430''>like</span>
  <span m=''234570''>that.</span> </p><p><span m=''237990''>Still,</span> <span m=''238380''>one</span>
  <span m=''238920''>of</span> <span m=''238990''>the</span> <span m=''239080''>questions</span>
  <span m=''239410''>I''ve</span> <span m=''239500''>posed</span> <span m=''239740''>in</span>
  <span m=''239820''>lecture</span> <span m=''240190''>was,</span> <span m=''240860''>can</span>
  <span m=''241040''>you</span> <span m=''241160''>make</span> <span m=''241350''>a</span>
  <span m=''241420''>nice</span> <span m=''241730''>interface</span> <span m=''242290''>that</span>
  <span m=''242390''>would</span> <span m=''242540''>let</span> <span m=''242700''>you</span>
  <span m=''242830''>force</span> <span m=''243270''>degeneracies,</span> <span m=''244170''>make</span>
  <span m=''245410''>like</span> <span m=''245720''>in--</span> <span m=''247110''>I</span>
  <span m=''247300''>think</span> <span m=''247500''>the</span> <span m=''247700''>swan</span>
  <span m=''247970''>has</span> <span m=''248880''>instances</span> <span m=''249440''>of</span>
  <span m=''249560''>this,</span> <span m=''250380''>where</span> <span m=''252760''>you''d</span>
  <span m=''253080''>like</span> <span m=''260269''>more</span> <span m=''260570''>than</span>
  <span m=''260740''>three</span> <span m=''261050''>skeleton</span> <span m=''261610''>edges</span>
  <span m=''261940''>to</span> <span m=''262040''>come</span> <span m=''262240''>together</span>
  <span m=''262630''>at</span> <span m=''262700''>a</span> <span m=''262760''>point.</span>
  <span m=''263040''>Here</span> <span m=''263240''>they</span> <span m=''263460''>almost</span>
  <span m=''263990''>do.</span> <span m=''264720''>It would</span> <span m=''264960''>be</span>
  <span m=''265070''>nice</span> <span m=''265350''>to</span> <span m=''265650''>be</span>
  <span m=''265760''>able</span> <span m=''265980''>to</span> <span m=''266150''>say,</span>
  <span m=''266530''>and</span> <span m=''267090''>for it</span> <span m=''267490''>to</span>
  <span m=''267790''>snap</span> <span m=''268250''>to</span> <span m=''268360''>a</span>
  <span m=''268430''>position</span> <span m=''268850''>where</span> <span m=''268990''>many</span>
  <span m=''269250''>things</span> <span m=''269500''>come</span> <span m=''269680''>together.</span>
  <span m=''270020''>Because</span> <span m=''270200''>that,</span> <span m=''270480''>in</span>
  <span m=''270630''>general,</span> <span m=''270970''>reduces</span> <span m=''271420''>number</span>
  <span m=''271650''>of</span> <span m=''271730''>creases</span> <span m=''272060''>substantially.</span>
  </p><p><span m=''273210''>You</span> <span m=''273330''>could</span> <span m=''273440''>also</span>
  <span m=''273690''>try</span> <span m=''273870''>to</span> <span m=''273960''>compute</span>
  <span m=''274250''>the</span> <span m=''274330''>folded</span> <span m=''274660''>state.</span>
  <span m=''275010''>That</span> <span m=''275360''>would</span> <span m=''275450''>be</span>
  <span m=''275560''>another</span> <span m=''275880''>interesting</span> <span m=''276250''>project</span>
  <span m=''277840''>based</span> <span m=''278140''>on</span> <span m=''278430''>what</span>
  <span m=''278620''>we''re</span> <span m=''278760''>going</span> <span m=''278900''>to</span>
  <span m=''278980''>talk</span> <span m=''279240''>about</span> <span m=''279810''>in</span>
  <span m=''279980''>a</span> <span m=''280040''>little</span> <span m=''280250''>bit,</span>
  <span m=''281290''>folding</span> <span m=''281830''>the</span> <span m=''282150''>underlying</span>
  <span m=''282800''>structure</span> <span m=''283330''>of</span> <span m=''283410''>corridors.</span>
  <span m=''284340''>And</span> <span m=''284420''>then</span> <span m=''284530''>you</span>
  <span m=''284650''>can</span> <span m=''284780''>computer</span> <span m=''285110''>a
  crease</span> <span m=''285340''>pattern.</span> <span m=''285530''>And</span> <span
  m=''285630''>there</span> <span m=''285780''>you</span> <span m=''285860''>have</span>
  <span m=''286030''>various</span> <span m=''286320''>choices,</span> <span m=''286800''>and</span>
  <span m=''286870''>that</span> <span m=''286990''>lets</span> <span m=''287200''>you</span>
  <span m=''287290''>throw</span> <span m=''287550''>away</span> <span m=''287740''>some</span>
  <span m=''287940''>of</span> <span m=''287980''>these</span> <span m=''288150''>creases.</span>
  <span m=''288520''>Like</span> <span m=''288670''>this</span> <span m=''288840''>is</span>
  <span m=''288960''>much</span> <span m=''289230''>messier</span> <span m=''289680''>than</span>
  <span m=''289870''>the</span> <span m=''290310''>swan</span> <span m=''290620''>crease</span>
  <span m=''290920''>pattern</span> <span m=''291130''>that''s</span> <span m=''291290''>on</span>
  <span m=''291410''>my</span> <span m=''291520''>web</span> <span m=''291730''>page,</span>
  <span m=''292020''>because</span> <span m=''292250''>you</span> <span m=''292330''>don''t</span>
  <span m=''292490''>need</span> <span m=''292680''>all</span> <span m=''292940''>these</span>
  <span m=''293130''>folds.</span> <span m=''294050''>If</span> <span m=''294110''>you</span>
  <span m=''294200''>choose</span> <span m=''294470''>the</span> <span m=''294580''>right</span>
  <span m=''295190''>subset</span> <span m=''295590''>of</span> <span m=''295670''>folds</span>
  <span m=''295970''>you can</span> <span m=''297030''>save</span> <span m=''297290''>a</span>
  <span m=''297320''>lot</span> <span m=''297490''>of</span> <span m=''297570''>time.</span>
  <span m=''299690''>So,</span> <span m=''301100''>still</span> <span m=''301330''>lots</span>
  <span m=''301540''>of</span> <span m=''301650''>cool</span> <span m=''301900''>projects</span>
  <span m=''302420''>to</span> <span m=''302550''>do</span> <span m=''302690''>here.</span>
  <span m=''303400''>It''d</span> <span m=''303560''>be</span> <span m=''303650''>great</span>
  <span m=''303860''>to</span> <span m=''303940''>get</span> <span m=''304120''>this</span>
  <span m=''304340''>software</span> <span m=''304690''>online,</span> <span m=''305190''>but</span>
  <span m=''306080''>that''s</span> <span m=''306300''>its</span> <span m=''306440''>current</span>
  <span m=''306700''>state.</span> </p><p><span m=''307270''>Next</span> <span m=''307570''>question</span>
  <span m=''308160''>is,</span> <span m=''308990''>what</span> <span m=''309280''>about</span>
  <span m=''309640''>odd</span> <span m=''309970''>degree</span> <span m=''310280''>vertices?</span>
  <span m=''311180''>This</span> <span m=''311390''>is</span> <span m=''312650''>actually</span>
  <span m=''312970''>a pretty</span> <span m=''313190''>natural</span> <span m=''313580''>question.</span>
  <span m=''316490''>Even</span> <span m=''316760''>degree</span> <span m=''317010''>vertices</span>
  <span m=''317520''>seem</span> <span m=''317840''>nice</span> <span m=''318160''>because</span>
  <span m=''318360''>you</span> <span m=''318520''>can</span> <span m=''318710''>kind</span>
  <span m=''318970''>of--</span> <span m=''320420''>well,</span> <span m=''320650''>it</span>
  <span m=''320810''>relates</span> <span m=''321210''>to</span> <span m=''321460''>a</span>
  <span m=''321540''>page</span> <span m=''321850''>that I</span> <span m=''322020''>didn''t</span>
  <span m=''322250''>really</span> <span m=''322480''>talk</span> <span m=''322750''>very</span>
  <span m=''322910''>much</span> <span m=''323130''>about</span> <span m=''323870''>in</span>
  <span m=''324257''>the</span> <span m=''325420''>lecture,</span> <span m=''325830''>but</span>
  <span m=''325990''>it</span> <span m=''326050''>was</span> <span m=''326730''>in</span>
  <span m=''326880''>the</span> <span m=''326960''>lecture</span> <span m=''327260''>notes,</span>
  <span m=''328240''>this</span> <span m=''328420''>idea</span> <span m=''328670''>of</span>
  <span m=''328730''>a</span> <span m=''328790''>side</span> <span m=''329140''>assignment.</span>
  <span m=''330320''>So</span> <span m=''330380''>in</span> <span m=''330450''>general,</span>
  <span m=''331340''>if you have</span> <span m=''331600''>something</span> <span
  m=''331870''>like</span> <span m=''332020''>a</span> <span m=''332190''>swan,</span>
  <span m=''332480''>there''s</span> <span m=''332620''>the</span> <span m=''332710''>inside</span>
  <span m=''333040''>of</span> <span m=''333120''>the</span> <span m=''333260''>swan,</span>
  <span m=''333490''>the</span> <span m=''333600''>outside</span> <span m=''333930''>of
  the</span> <span m=''334070''>swan,</span> <span m=''334270''>and</span> <span m=''334340''>generally</span>
  <span m=''334690''>you have</span> <span m=''334820''>a</span> <span m=''334860''>bunch</span>
  <span m=''335110''>of</span> <span m=''335210''>regions.</span> </p><p><span m=''336070''>And</span>
  <span m=''336250''>for</span> <span m=''336360''>each</span> <span m=''336540''>region</span>
  <span m=''336860''>you''d</span> <span m=''336990''>like</span> <span m=''337160''>to</span>
  <span m=''337260''>know</span> <span m=''337420''>is</span> <span m=''337610''>it</span>
  <span m=''337720''>above</span> <span m=''338070''>the</span> <span m=''338170''>cut</span>
  <span m=''338410''>line</span> <span m=''338740''>or</span> <span m=''338900''>below</span>
  <span m=''339190''>the</span> <span m=''339310''>cut</span> <span m=''339510''>line?</span>
  <span m=''340130''>If</span> <span m=''340350''>you</span> <span m=''340590''>imagine</span>
  <span m=''341050''>the</span> <span m=''341140''>cut</span> <span m=''341340''>line</span>
  <span m=''341630''>as</span> <span m=''342420''>horizontal.</span> <span m=''343690''>And</span>
  <span m=''344180''>in</span> <span m=''344260''>general,</span> <span m=''344890''>the</span>
  <span m=''345000''>side</span> <span m=''345230''>assignment</span> <span m=''345600''>would</span>
  <span m=''345730''>specify,</span> <span m=''346300''>do</span> <span m=''346540''>I</span>
  <span m=''346660''>want</span> <span m=''346910''>my</span> <span m=''347020''>region</span>
  <span m=''347300''>above</span> <span m=''347560''>or</span> <span m=''347660''>below?</span>
  <span m=''348440''>And</span> <span m=''348590''>you</span> <span m=''348690''>could</span>
  <span m=''348810''>do</span> <span m=''348920''>whatever</span> <span m=''349190''>you</span>
  <span m=''349300''>want.</span> <span m=''350200''>Now</span> <span m=''350420''>with</span>
  <span m=''350570''>even</span> <span m=''350860''>degree</span> <span m=''351110''>vertices,</span>
  <span m=''351550''>this</span> <span m=''351710''>is</span> <span m=''351850''>great.</span>
  <span m=''352140''>You</span> <span m=''352160''>could</span> <span m=''352290''>just</span>
  <span m=''352470''>alternate</span> <span m=''352960''>around</span> <span m=''353410''>and</span>
  <span m=''353530''>say,</span> <span m=''354110''>above,</span> <span m=''354430''>below,</span>
  <span m=''354710''>above,</span> <span m=''354990''>below.</span> <span m=''355660''>With</span>
  <span m=''355820''>odd</span> <span m=''355940''>degree</span> <span m=''356140''>vertices,</span>
  <span m=''356580''>you</span> <span m=''356720''>can''t,</span> <span m=''357190''>so</span>
  <span m=''357370''>you''re</span> <span m=''357470''>going</span> <span m=''357570''>to</span>
  <span m=''357610''>have</span> <span m=''357820''>two</span> <span m=''358010''>regions</span>
  <span m=''358600''>that</span> <span m=''358720''>are</span> <span m=''358830''>adjacent</span>
  <span m=''359050''>to</span> <span m=''359250''>each</span> <span m=''359370''>other</span>
  <span m=''359600''>which</span> <span m=''359820''>are</span> <span m=''359930''>both</span>
  <span m=''360280''>above</span> <span m=''360730''>or</span> <span m=''360880''>both</span>
  <span m=''361220''>below.</span> </p><p><span m=''362730''>So</span> <span m=''363210''>what</span>
  <span m=''363510''>does</span> <span m=''363660''>that</span> <span m=''363850''>mean?</span>
  <span m=''366840''>It</span> <span m=''366980''>means</span> <span m=''367180''>it''s</span>
  <span m=''367300''>a</span> <span m=''367370''>little</span> <span m=''367600''>bit</span>
  <span m=''367740''>hard</span> <span m=''367990''>to</span> <span m=''368070''>cut.</span>
  <span m=''369960''>And</span> <span m=''370590''>there''s</span> <span m=''370810''>actually</span>
  <span m=''371150''>two</span> <span m=''371350''>models</span> <span m=''371760''>of</span>
  <span m=''371890''>cuts.</span> <span m=''372810''>There''s</span> <span m=''374260''>scissor</span>
  <span m=''374580''>cuts--</span> <span m=''376110''>which</span> <span m=''376580''>are</span>
  <span m=''377930''>in</span> <span m=''378080''>particular</span> <span m=''378510''>what</span>
  <span m=''378670''>the</span> <span m=''378770''>question</span> <span m=''379210''>poser</span>
  <span m=''379790''>had</span> <span m=''380050''>in</span> <span m=''380130''>mind,</span>
  <span m=''380450''>and</span> <span m=''380570''>probably</span> <span m=''380910''>what</span>
  <span m=''381080''>you</span> <span m=''381200''>might</span> <span m=''381380''>have</span>
  <span m=''381470''>had</span> <span m=''381660''>in</span> <span m=''381720''>mind</span>
  <span m=''381970''>in</span> <span m=''382050''>general--</span> <span m=''383090''>where</span>
  <span m=''383940''>the</span> <span m=''384060''>cut</span> <span m=''384380''>you''re</span>
  <span m=''384510''>going</span> <span m=''384730''>to</span> <span m=''384860''>make</span>
  <span m=''385140''>separates</span> <span m=''385910''>material</span> <span m=''386440''>from</span>
  <span m=''386970''>above</span> <span m=''387350''>and</span> <span m=''387430''>below</span>
  <span m=''387720''>the</span> <span m=''387830''>line.</span> <span m=''388670''>So</span>
  <span m=''388700''>this</span> <span m=''388900''>is</span> <span m=''389020''>the</span>
  <span m=''389130''>cut</span> <span m=''389330''>line</span> <span m=''389610''>here.</span>
  <span m=''392020''>And</span> <span m=''392540''>it''d</span> <span m=''392710''>be</span>
  <span m=''392840''>really</span> <span m=''393040''>nice</span> <span m=''393260''>if</span>
  <span m=''393350''>you</span> <span m=''393430''>had</span> <span m=''393540''>material</span>
  <span m=''393930''>on</span> <span m=''394020''>both</span> <span m=''394210''>sides,</span>
  <span m=''394500''>because</span> <span m=''394650''>that''s</span> <span m=''394820''>usually</span>
  <span m=''395090''>how</span> <span m=''395220''>scissors</span> <span m=''395590''>work,</span>
  <span m=''396420''>they</span> <span m=''396770''>tear</span> <span m=''397060''>apart</span>
  <span m=''398310''>material.</span> </p><p><span m=''400190''>An</span> <span m=''400310''>alternative</span>
  <span m=''401050''>is</span> <span m=''401350''>that</span> <span m=''401660''>you</span>
  <span m=''401770''>have</span> <span m=''403170''>a</span> <span m=''403230''>mathematical</span>
  <span m=''403910''>cut.</span> <span m=''405520''>And a</span> <span m=''405710''>mathematical</span>
  <span m=''406310''>cut</span> <span m=''406570''>can</span> <span m=''406760''>cut</span>
  <span m=''407080''>right</span> <span m=''407490''>along</span> <span m=''407860''>a</span>
  <span m=''408010''>crease</span> <span m=''408410''>line.</span> <span m=''409290''>So</span>
  <span m=''409440''>it</span> <span m=''409500''>could</span> <span m=''409660''>be</span>
  <span m=''409780''>you have</span> <span m=''410290''>two</span> <span m=''412080''>polygons,</span>
  <span m=''414100''>there''s</span> <span m=''414280''>a</span> <span m=''414340''>fold</span>
  <span m=''414760''>here</span> <span m=''414980''>between</span> <span m=''415330''>them,</span>
  <span m=''415940''>and</span> <span m=''416270''>you</span> <span m=''416490''>can</span>
  <span m=''416780''>cut</span> <span m=''417840''>right</span> <span m=''418120''>along</span>
  <span m=''418500''>that</span> <span m=''418740''>line.</span> <span m=''420260''>Maybe</span>
  <span m=''420490''>I</span> <span m=''420520''>shouldn''t</span> <span m=''420790''>draw</span>
  <span m=''421170''>scissors.</span> <span m=''422490''>Imagine</span> <span m=''422940''>a</span>
  <span m=''423220''>laser</span> <span m=''423600''>beam</span> <span m=''424530''>which</span>
  <span m=''424890''>can</span> <span m=''425850''>zap</span> <span m=''426270''>right</span>
  <span m=''426470''>along</span> <span m=''426740''>the</span> <span m=''426830''>line,</span>
  <span m=''427520''>so</span> <span m=''427640''>there''s</span> <span m=''427830''>no</span>
  <span m=''427980''>material</span> <span m=''428380''>on</span> <span m=''428450''>the</span>
  <span m=''428540''>left</span> <span m=''428760''>side</span> <span m=''428980''>of</span>
  <span m=''429050''>the</span> <span m=''429110''>line,</span> <span m=''429460''>just</span>
  <span m=''429690''>material</span> <span m=''430010''>on</span> <span m=''430080''>the</span>
  <span m=''430170''>right,</span> <span m=''430450''>but</span> <span m=''430630''>yet</span>
  <span m=''430840''>it</span> <span m=''430960''>separates</span> <span m=''431440''>the</span>
  <span m=''431530''>two</span> <span m=''431700''>things</span> <span m=''431970''>on</span>
  <span m=''432080''>the</span> <span m=''432160''>right.</span> </p><p><span m=''433240''>So</span>
  <span m=''435730''>we</span> <span m=''435850''>call</span> <span m=''436000''>that</span>
  <span m=''436100''>mathematical</span> <span m=''436740''>cut,</span> <span m=''437170''>because</span>
  <span m=''437850''>it</span> <span m=''438010''>is</span> <span m=''438210''>the</span>
  <span m=''438310''>natural</span> <span m=''438650''>definition</span> <span m=''439080''>mathematically.</span>
  <span m=''439690''>You''re</span> <span m=''439850''>erasing</span> <span m=''440380''>a</span>
  <span m=''440440''>line.</span> <span m=''441600''>But</span> <span m=''441810''>practically</span>
  <span m=''442230''>it''s a</span> <span m=''442340''>little</span> <span m=''442510''>hard</span>
  <span m=''442750''>to</span> <span m=''442830''>do.</span> <span m=''442990''>So</span>
  <span m=''443130''>scissor</span> <span m=''443420''>cuts</span> <span m=''443670''>are</span>
  <span m=''443780''>also</span> <span m=''444050''>nice.</span> <span m=''444400''>This
  is</span> <span m=''444570''>a</span> <span m=''444620''>more</span> <span m=''444820''>restrictive</span>
  <span m=''445220''>model.</span> <span m=''445990''>This</span> <span m=''446160''>is</span>
  <span m=''446310''>general</span> <span m=''446630''>model.</span> <span m=''447490''>So</span>
  <span m=''447710''>what</span> <span m=''447890''>I</span> <span m=''447940''>was</span>
  <span m=''448110''>talking</span> <span m=''448380''>about</span> <span m=''449020''>in</span>
  <span m=''449360''>lecture,</span> <span m=''449770''>implicitly</span> <span m=''450420''>use</span>
  <span m=''450610''>mathematical</span> <span m=''451270''>cuts.</span> <span m=''451570''>And</span>
  <span m=''451650''>that''s</span> <span m=''451930''>when</span> <span m=''452620''>you</span>
  <span m=''452770''>could</span> <span m=''452880''>make</span> <span m=''453070''>anything</span>
  <span m=''454040''>with</span> <span m=''454170''>one</span> <span m=''454400''>cut.</span>
  <span m=''456380''>But,</span> <span m=''458770''>it</span> <span m=''459020''>would</span>
  <span m=''459170''>be</span> <span m=''459280''>nice</span> <span m=''459520''>to</span>
  <span m=''459600''>get</span> <span m=''459790''>scissor</span> <span m=''460040''>cuts</span>
  <span m=''460310''>when</span> <span m=''460540''>possible.</span> <span m=''461290''>And</span>
  <span m=''461590''>when</span> <span m=''461750''>possible</span> <span m=''462330''>is</span>
  <span m=''462430''>basically</span> <span m=''463090''>when</span> <span m=''463280''>you</span>
  <span m=''463370''>have</span> <span m=''463690''>even</span> <span m=''463980''>degree</span>
  <span m=''464720''>at</span> <span m=''464870''>every</span> <span m=''465050''>vertex.</span>
  </p><p><span m=''466090''>And</span> <span m=''466250''>one</span> <span m=''466430''>fun</span>
  <span m=''466650''>example</span> <span m=''467210''>of</span> <span m=''467300''>that</span>
  <span m=''468070''>is</span> <span m=''468580''>checkerboard.</span> <span m=''468980''>This</span>
  <span m=''469190''>is actually</span> <span m=''469420''>an</span> <span m=''469500''>old</span>
  <span m=''469750''>magic</span> <span m=''470090''>trick.</span> <span m=''470690''>You</span>
  <span m=''470800''>have</span> <span m=''471280''>a</span> <span m=''471420''>piece</span>
  <span m=''471810''>of</span> <span m=''471940''>usually</span> <span m=''472260''>tissue</span>
  <span m=''472580''>paper,</span> <span m=''473190''>so</span> <span m=''473230''>it''s</span>
  <span m=''473360''>really</span> <span m=''473600''>thin,</span> <span m=''474580''>pre</span>
  <span m=''474820''>colored</span> <span m=''475510''>as</span> <span m=''476510''>checkered</span>
  <span m=''476890''>squares,</span> <span m=''477460''>both</span> <span m=''477820''>sides</span>
  <span m=''478210''>matching.</span> <span m=''479640''>And</span> <span m=''479880''>you</span>
  <span m=''480010''>can</span> <span m=''480150''>fold</span> <span m=''480460''>this,</span>
  <span m=''481020''>because</span> <span m=''481320''>every</span> <span m=''481510''>vertex</span>
  <span m=''481880''>here</span> <span m=''483520''>has</span> <span m=''483700''>degree</span>
  <span m=''483930''>4,</span> <span m=''485290''>so</span> <span m=''485470''>even</span>
  <span m=''485750''>degree,</span> <span m=''486520''>you</span> <span m=''486730''>can</span>
  <span m=''487170''>assign</span> <span m=''487740''>the</span> <span m=''487910''>black</span>
  <span m=''488810''>squares</span> <span m=''489210''>to</span> <span m=''489300''>be</span>
  <span m=''489440''>on</span> <span m=''489520''>one</span> <span m=''489720''>side</span>
  <span m=''489990''>or</span> <span m=''490060''>the</span> <span m=''490120''>blue</span>
  <span m=''490280''>squares</span> <span m=''490570''>to be</span> <span m=''490710''>one</span>
  <span m=''490950''>side,</span> <span m=''491080''>the</span> <span m=''491160''>white</span>
  <span m=''491610''>squares</span> <span m=''491910''>to</span> <span m=''491980''>be</span>
  <span m=''492050''>on</span> <span m=''492130''>the</span> <span m=''492220''>other</span>
  <span m=''492370''>side.</span> <span m=''492740''>And</span> <span m=''492840''>so</span>
  <span m=''492940''>you</span> <span m=''493040''>could</span> <span m=''493140''>make</span>
  <span m=''493190''>one</span> <span m=''493380''>cut</span> <span m=''493600''>and</span>
  <span m=''493690''>simultaneously</span> <span m=''494900''>cut</span> <span m=''495120''>out</span>
  <span m=''495340''>all</span> <span m=''495560''>the</span> <span m=''495650''>white</span>
  <span m=''495860''>squares</span> <span m=''496340''>and all the</span> <span m=''496630''>black</span>
  <span m=''496870''>squares</span> <span m=''497150''>which is</span> <span m=''497430''>kind</span>
  <span m=''497590''>of</span> <span m=''497650''>cool.</span> <span m=''498990''>This</span>
  <span m=''499130''>is</span> <span m=''499380''>old,</span> <span m=''500630''>decades</span>
  <span m=''501020''>old.</span> </p><p><span m=''503960''>So</span> <span m=''505380''>in</span>
  <span m=''505590''>general,</span> <span m=''515419''>you</span> <span m=''515610''>can</span>
  <span m=''515770''>do</span> <span m=''516030''>something</span> <span m=''516380''>with</span>
  <span m=''516500''>scissor</span> <span m=''516789''>cuts.</span> <span m=''520484''>Or</span>
  <span m=''520940''>scissor</span> <span m=''521760''>cuts</span> <span m=''521990''>are</span>
  <span m=''522059''>going</span> <span m=''522179''>to</span> <span m=''522240''>be</span>
  <span m=''522390''>possible</span> <span m=''522950''>if</span> <span m=''523140''>and</span>
  <span m=''523220''>only</span> <span m=''523549''>if</span> <span m=''524169''>you</span>
  <span m=''524960''>can</span> <span m=''525120''>find</span> <span m=''525340''>a</span>
  <span m=''525400''>side</span> <span m=''525690''>assignment</span> <span m=''531300''>that</span>
  <span m=''531670''>sort</span> <span m=''531890''>of</span> <span m=''531970''>alternates</span>
  <span m=''535570''>between</span> <span m=''536140''>above</span> <span m=''536700''>and</span>
  <span m=''536900''>below</span> <span m=''537320''>the</span> <span m=''537440''>cut</span>
  <span m=''537640''>line.</span> <span m=''542330''>Meaning</span> <span m=''542640''>when</span>
  <span m=''542760''>you</span> <span m=''542860''>have</span> <span m=''543110''>two</span>
  <span m=''543340''>regions</span> <span m=''544900''>that</span> <span m=''545120''>are
  adjacent,</span> <span m=''545670''>you</span> <span m=''545770''>don''t</span>
  <span m=''545910''>want</span> <span m=''546080''>them</span> <span m=''546210''>both</span>
  <span m=''546520''>to</span> <span m=''546620''>be</span> <span m=''546800''>above</span>
  <span m=''547110''>and</span> <span m=''547190''>below.</span> <span m=''547490''>You''d</span>
  <span m=''547640''>like</span> <span m=''547820''>one</span> <span m=''548010''>to</span>
  <span m=''548080''>be</span> <span m=''548230''>above,</span> <span m=''548590''>one</span>
  <span m=''548830''>to</span> <span m=''548920''>be below.</span> <span m=''550670''>And</span>
  <span m=''550830''>this</span> <span m=''551010''>is</span> <span m=''551120''>what''s</span>
  <span m=''551340''>called</span> <span m=''551700''>a</span> <span m=''551970''>face</span>
  <span m=''552360''>2-coloring</span> <span m=''553740''>in</span> <span m=''553960''>planar</span>
  <span m=''554280''>graphs.</span> <span m=''556420''>You</span> <span m=''556530''>want</span>
  <span m=''556630''>to</span> <span m=''556690''>color</span> <span m=''556980''>the</span>
  <span m=''557080''>faces,</span> <span m=''557650''>the</span> <span m=''557790''>regions</span>
  <span m=''558290''>of</span> <span m=''558470''>your</span> <span m=''559090''>graph,</span>
  <span m=''560470''>with</span> <span m=''560680''>two</span> <span m=''560860''>colors</span>
  <span m=''561400''>such</span> <span m=''561430''>that</span> <span m=''561720''>no</span>
  <span m=''561860''>two</span> <span m=''562090''>adjacent</span> <span m=''562890''>cells</span>
  <span m=''563220''>have</span> <span m=''563400''>the</span> <span m=''563460''>same</span>
  <span m=''563690''>color,</span> <span m=''564005''>no</span> <span m=''564320''>two</span>
  <span m=''564480''>adjacent</span> <span m=''564780''>faces</span> <span m=''565060''>have
  the</span> <span m=''565280''>same</span> <span m=''565490''>color,</span> <span
  m=''566140''>and</span> <span m=''566340''>that</span> <span m=''566500''>turns</span>
  <span m=''566740''>out</span> <span m=''566920''>to</span> <span m=''567050''>be</span>
  <span m=''567200''>equivalent</span> <span m=''567670''>to</span> <span m=''567760''>having</span>
  <span m=''568620''>all</span> <span m=''568840''>vertices</span> <span m=''569380''>of</span>
  <span m=''569470''>even</span> <span m=''569730''>degree.</span> </p><p><span m=''573940''>So</span>
  <span m=''574170''>this</span> <span m=''574360''>is</span> <span m=''574480''>why</span>
  <span m=''574900''>that</span> <span m=''575060''>question</span> <span m=''575340''>was</span>
  <span m=''575450''>asking</span> <span m=''575680''>about</span> <span m=''576040''>odd
  degree,</span> <span m=''576330''>because</span> <span m=''576540''>indeed</span>
  <span m=''576820''>with</span> <span m=''576940''>scissor</span> <span m=''577190''>cuts,</span>
  <span m=''578000''>you</span> <span m=''578110''>can''t</span> <span m=''578330''>do</span>
  <span m=''578460''>odd</span> <span m=''578590''>degree.</span> <span m=''580720''>There</span>
  <span m=''580940''>is</span> <span m=''581020''>a</span> <span m=''581090''>fun
  fact,</span> <span m=''581700''>though,</span> <span m=''582470''>that</span> <span
  m=''582820''>relates</span> <span m=''583460''>these</span> <span m=''583830''>two</span>
  <span m=''584030''>things.</span> <span m=''584870''>So</span> <span m=''585470''>if
  you</span> <span m=''585620''>have even</span> <span m=''585810''>degree</span>
  <span m=''586200''>like</span> <span m=''586390''>polygons,</span> <span m=''587060''>which</span>
  <span m=''587300''>is</span> <span m=''587470''>typical</span> <span m=''587880''>case,</span>
  <span m=''588710''>scissor</span> <span m=''588870''>cuts</span> <span m=''589150''>should</span>
  <span m=''589290''>be</span> <span m=''589420''>possible.</span> <span m=''593710''>Mathematical</span>
  <span m=''594290''>cuts</span> <span m=''594500''>can</span> <span m=''594620''>do</span>
  <span m=''594740''>everything.</span> <span m=''596260''>What</span> <span m=''596470''>if</span>
  <span m=''596600''>I</span> <span m=''596670''>have</span> <span m=''596860''>something</span>
  <span m=''597170''>that has</span> <span m=''597320''>odd</span> <span m=''597550''>degree</span>
  <span m=''597820''>vertices,</span> <span m=''598300''>but</span> <span m=''598430''>I</span>
  <span m=''598470''>still</span> <span m=''598690''>want</span> <span m=''598820''>to</span>
  <span m=''598860''>use</span> <span m=''599080''>scissor</span> <span m=''599290''>cuts?</span>
  <span m=''600110''>Well</span> <span m=''600330''>then,</span> <span m=''600510''>it</span>
  <span m=''600600''>turns</span> <span m=''600860''>out</span> <span m=''601060''>two</span>
  <span m=''601370''>cuts</span> <span m=''601680''>are</span> <span m=''601780''>enough,</span>
  <span m=''602690''>pretty</span> <span m=''602930''>much.</span> <span m=''604360''>That</span>
  <span m=''604720''>if</span> <span m=''605090''>you</span> <span m=''605200''>have,</span>
  <span m=''611850''>I''ll</span> <span m=''611960''>call it</span> <span m=''612350''>a</span>
  <span m=''612620''>2-edge-connected</span> <span m=''616170''>planar</span> <span
  m=''616590''>graph,</span> <span m=''623630''>equals</span> <span m=''624440''>the</span>
  <span m=''624570''>union</span> <span m=''626345''>of</span> <span m=''627620''>two</span>
  <span m=''629010''>even</span> <span m=''629230''>graphs.</span> <span m=''632030''>I</span>
  <span m=''632170''>should</span> <span m=''632390''>say</span> <span m=''632620''>even</span>
  <span m=''633170''>subgraphs.</span> <span m=''635144''>It</span> <span m=''635631''>doesn''t</span>
  <span m=''636120''>much</span> <span m=''636350''>matter.</span> </p><p><span m=''637260''>So</span>
  <span m=''638060''>there''s</span> <span m=''638380''>one</span> <span m=''638590''>exception,</span>
  <span m=''639430''>which</span> <span m=''639590''>is,</span> <span m=''639820''>if</span>
  <span m=''640000''>you</span> <span m=''640130''>have</span> <span m=''640580''>an</span>
  <span m=''640830''>edge</span> <span m=''641200''>in</span> <span m=''641390''>your</span>
  <span m=''642060''>desired</span> <span m=''642440''>set</span> <span m=''642590''>of</span>
  <span m=''642680''>cuts,</span> <span m=''643620''>that</span> <span m=''643800''>partitions</span>
  <span m=''646320''>the</span> <span m=''646460''>graph</span> <span m=''646770''>into</span>
  <span m=''646970''>two</span> <span m=''647160''>parts.</span> <span m=''648420''>So</span>
  <span m=''648520''>if</span> <span m=''648690''>you</span> <span m=''648840''>could</span>
  <span m=''649110''>delete</span> <span m=''649410''>an</span> <span m=''649510''>edge</span>
  <span m=''650250''>and</span> <span m=''650520''>disconnect</span> <span m=''651190''>the</span>
  <span m=''651270''>graph</span> <span m=''651540''>into</span> <span m=''652480''>more</span>
  <span m=''652720''>parts,</span> <span m=''654650''>there''s</span> <span m=''654980''>no</span>
  <span m=''655250''>hope</span> <span m=''655480''>of</span> <span m=''655600''>decomposing</span>
  <span m=''656180''>this</span> <span m=''656350''>into</span> <span m=''656530''>even</span>
  <span m=''656870''>graphs.</span> <span m=''658186''>I</span> <span m=''658530''>think.</span>
  <span m=''660740''>Should</span> <span m=''661030''>check</span> <span m=''661310''>that.</span>
  <span m=''662210''>But</span> <span m=''662460''>as</span> <span m=''662610''>long</span>
  <span m=''662840''>as</span> <span m=''662950''>you</span> <span m=''663230''>do</span>
  <span m=''663360''>not</span> <span m=''663580''>have</span> <span m=''663820''>such,</span>
  <span m=''664290''>these</span> <span m=''664370''>are</span> <span m=''664430''>called</span>
  <span m=''664680''>bridges,</span> <span m=''665380''>typically.</span> <span m=''667680''>So</span>
  <span m=''667790''>bridges</span> <span m=''668150''>are</span> <span m=''668230''>forbidden.</span>
  <span m=''669080''>If</span> <span m=''669200''>you</span> <span m=''669290''>have</span>
  <span m=''669530''>no</span> <span m=''669690''>bridges,</span> <span m=''670790''>then</span>
  <span m=''670980''>you''re</span> <span m=''671190''>at</span> <span m=''671260''>what''s</span>
  <span m=''671460''>called</span> <span m=''671650''>a</span> <span m=''671860''>2-edge-connected</span>
  <span m=''672400''>planar</span> <span m=''672670''>graph.</span> <span m=''673360''>And</span>
  <span m=''673570''>then</span> <span m=''673750''>you</span> <span m=''673880''>can</span>
  <span m=''674020''>decompose</span> <span m=''674510''>your</span> <span m=''674620''>graph</span>
  <span m=''674860''>into</span> <span m=''675070''>two</span> <span m=''675240''>parts,</span>
  <span m=''676400''>each</span> <span m=''676500''>of</span> <span m=''676600''>which</span>
  <span m=''676800''>is</span> <span m=''676950''>even.</span> <span m=''677300''>So</span>
  <span m=''677430''>you</span> <span m=''677570''>could</span> <span m=''677730''>fold,</span>
  <span m=''678180''>make</span> <span m=''678390''>one</span> <span m=''678520''>straight</span>
  <span m=''678780''>cut,</span> <span m=''679180''>and</span> <span m=''679380''>get</span>
  <span m=''679510''>one</span> <span m=''679720''>even</span> <span m=''679990''>graph,</span>
  <span m=''680640''>fold,</span> <span m=''681030''>make</span> <span m=''681200''>once</span>
  <span m=''681400''>straight</span> <span m=''681670''>cut,</span> <span m=''681940''>get</span>
  <span m=''682110''>the</span> <span m=''682250''>other</span> <span m=''682470''>even</span>
  <span m=''682730''>graph.</span> <span m=''683130''>Good</span> <span m=''683280''>luck</span>
  <span m=''683480''>folding</span> <span m=''683820''>it</span> <span m=''683920''>the</span>
  <span m=''684020''>second</span> <span m=''684380''>time</span> <span m=''684940''>if
  it</span> <span m=''685260''>decomposed.</span> </p><p><span m=''686910''>But</span>
  <span m=''687040''>in</span> <span m=''687350''>theory</span> <span m=''687660''>at</span>
  <span m=''687730''>least,</span> <span m=''688360''>with</span> <span m=''688560''>two</span>
  <span m=''688740''>scissor</span> <span m=''689040''>cuts,</span> <span m=''689780''>you</span>
  <span m=''689960''>can</span> <span m=''690100''>make</span> <span m=''690530''>anything</span>
  <span m=''691880''>that</span> <span m=''692270''>doesn''t</span> <span m=''692530''>have</span>
  <span m=''692730''>bridges.</span> <span m=''694530''>So</span> <span m=''694710''>that''s</span>
  <span m=''694920''>just</span> <span m=''695580''>kind</span> <span m=''695760''>of</span>
  <span m=''695840''>an</span> <span m=''695950''>aside.</span> <span m=''697130''>Some</span>
  <span m=''697340''>graph</span> <span m=''697650''>theory</span> <span m=''698340''>that</span>
  <span m=''699550''>tells</span> <span m=''699790''>you</span> <span m=''699900''>a</span>
  <span m=''699920''>little</span> <span m=''700110''>bit</span> <span m=''700260''>more</span>
  <span m=''700460''>about</span> <span m=''700640''>what</span> <span m=''700790''>you</span>
  <span m=''700890''>can</span> <span m=''700990''>do</span> <span m=''701110''>with</span>
  <span m=''701210''>two</span> <span m=''701390''>scissor</span> <span m=''701590''>cuts--</span>
  <span m=''702580''>pretty</span> <span m=''702810''>much</span> <span m=''703040''>everything.</span>
  <span m=''704420''>Any</span> <span m=''705020''>more</span> <span m=''705170''>questions</span>
  <span m=''705540''>about</span> <span m=''705870''>that?</span> <span m=''708230''>So</span>
  <span m=''708460''>that</span> <span m=''708720''>was odd</span> <span m=''708950''>degree</span>
  <span m=''709300''>vertices.</span> </p><p><span m=''713830''>Next</span> <span
  m=''714170''>questions</span> <span m=''715430''>are</span> <span m=''715560''>about</span>
  <span m=''718590''>folding</span> <span m=''719300''>and</span> <span m=''719370''>how</span>
  <span m=''719860''>exactly--</span> <span m=''720860''>so</span> <span m=''721100''>I</span>
  <span m=''721300''>kind</span> <span m=''721490''>of</span> <span m=''721780''>briefly</span>
  <span m=''722200''>sketched</span> <span m=''723410''>the proof</span> <span m=''723540''>for</span>
  <span m=''723880''>linear</span> <span m=''724270''>corridors,</span> <span m=''724820''>how</span>
  <span m=''725100''>you</span> <span m=''725280''>would</span> <span m=''725410''>fold</span>
  <span m=''727160''>or</span> <span m=''727280''>how</span> <span m=''727780''>you
  would</span> <span m=''728220''>prove</span> <span m=''728660''>that</span> <span
  m=''728790''>this</span> <span m=''728950''>thing</span> <span m=''729110''>actually</span>
  <span m=''729470''>folds.</span> <span m=''730230''>This</span> <span m=''730390''>is</span>
  <span m=''730510''>the</span> <span m=''731210''>skeleton</span> <span m=''731730''>method</span>
  <span m=''732060''>first.</span> <span m=''732840''>We''ll</span> <span m=''732940''>go</span>
  <span m=''733060''>to</span> <span m=''733150''>disk-packing</span> <span m=''733740''>afterwards.</span>
  <span m=''735270''>So</span> <span m=''735620''>how</span> <span m=''735830''>do</span>
  <span m=''735900''>you</span> <span m=''736140''>convert</span> <span m=''737290''>a</span>
  <span m=''737570''>set</span> <span m=''737820''>of</span> <span m=''737890''>linear</span>
  <span m=''738150''>quarters</span> <span m=''738520''>into</span> <span m=''738720''>a</span>
  <span m=''738790''>tree?</span> <span m=''739480''>Then</span> <span m=''739610''>once</span>
  <span m=''739780''>you</span> <span m=''739860''>have</span> <span m=''740050''>that</span>
  <span m=''740200''>correspondence,</span> <span m=''741490''>how</span> <span m=''741730''>does</span>
  <span m=''741960''>trees</span> <span m=''742460''>folding</span> <span m=''742780''>flat</span>
  <span m=''743120''>relate</span> <span m=''743500''>to</span> <span m=''743670''>corridors</span>
  <span m=''744170''>folding</span> <span m=''744460''>flat?</span> </p><p><span m=''746530''>And</span>
  <span m=''747020''>so</span> <span m=''747160''>I</span> <span m=''747670''>redrew</span>
  <span m=''747940''>this</span> <span m=''748150''>figure</span> <span m=''748710''>to</span>
  <span m=''748820''>make</span> <span m=''749040''>it a</span> <span m=''749110''>little</span>
  <span m=''749300''>bit</span> <span m=''749490''>clearer.</span> <span m=''750430''>So</span>
  <span m=''750570''>this</span> <span m=''750790''>is</span> <span m=''750910''>one</span>
  <span m=''751070''>of</span> <span m=''751140''>the</span> <span m=''751240''>images</span>
  <span m=''751650''>in</span> <span m=''751810''>the</span> <span m=''751900''>textbook</span>
  <span m=''753250''>where</span> <span m=''753620''>I just</span> <span m=''753910''>face</span>
  <span m=''754180''>colored,</span> <span m=''754810''>in</span> <span m=''754900''>this</span>
  <span m=''755080''>case</span> <span m=''755280''>with</span> <span m=''755400''>three</span>
  <span m=''755590''>colors,</span> <span m=''756120''>the</span> <span m=''757010''>corridors.</span>
  <span m=''757900''>Those are</span> <span m=''758260''>the</span> <span m=''758490''>regions</span>
  <span m=''758860''>of</span> <span m=''758960''>constant</span> <span m=''759340''>width</span>
  <span m=''759580''>bounded</span> <span m=''759860''>by</span> <span m=''759990''>perpendiculars.</span>
  <span m=''761940''>This</span> <span m=''762240''>is for</span> <span m=''762360''>making</span>
  <span m=''762620''>a</span> <span m=''762700''>turtle.</span> <span m=''763240''>That</span>
  <span m=''763530''>sort</span> <span m=''763770''>of</span> <span m=''764130''>doesn''t</span>
  <span m=''764440''>really</span> <span m=''764660''>matter.</span> <span m=''765450''>And</span>
  <span m=''765680''>this</span> <span m=''765830''>is</span> <span m=''765900''>the</span>
  <span m=''766000''>corresponding</span> <span m=''766560''>tree.</span> <span m=''767680''>And</span>
  <span m=''768360''>this</span> <span m=''769670''>is</span> <span m=''770200''>the</span>
  <span m=''770300''>folded</span> <span m=''770850''>state</span> <span m=''771320''>of</span>
  <span m=''771650''>this</span> <span m=''772160''>blue</span> <span m=''772410''>guy</span>
  <span m=''772670''>here</span> <span m=''773450''>between</span> <span m=''773810''>B</span>
  <span m=''773970''>and</span> <span m=''774120''>C.</span> </p><p><span m=''775130''>And</span>
  <span m=''775690''>to</span> <span m=''775910''>really</span> <span m=''776310''>illustrate</span>
  <span m=''776760''>what''s</span> <span m=''776980''>going</span> <span m=''777280''>on</span>
  <span m=''777440''>here,</span> <span m=''778230''>I</span> <span m=''778420''>folded</span>
  <span m=''778780''>this</span> <span m=''778960''>thing.</span> <span m=''779240''>It''s</span>
  <span m=''780370''>tricky</span> <span m=''780650''>to</span> <span m=''780730''>fold,</span>
  <span m=''781270''>let''s</span> <span m=''781450''>say.</span> <span m=''782690''>And</span>
  <span m=''783250''>I</span> <span m=''783510''>added</span> <span m=''784460''>a</span>
  <span m=''784540''>few</span> <span m=''784730''>paper</span> <span m=''785000''>clips</span>
  <span m=''785300''>to</span> <span m=''785420''>make</span> <span m=''785650''>it</span>
  <span m=''785980''>really</span> <span m=''786220''>stay.</span> <span m=''787240''>But</span>
  <span m=''787400''>if</span> <span m=''787570''>you</span> <span m=''787860''>hold</span>
  <span m=''788130''>it</span> <span m=''788230''>right,</span> <span m=''788980''>which
  is</span> <span m=''789240''>a</span> <span m=''789260''>little</span> <span m=''789410''>bit</span>
  <span m=''789580''>challenging,</span> <span m=''791460''>the</span> <span m=''792160''>projection</span>
  <span m=''793200''>of</span> <span m=''793400''>this</span> <span m=''794310''>structure</span>
  <span m=''795450''>is</span> <span m=''795670''>exactly</span> <span m=''796140''>this</span>
  <span m=''796350''>tree.</span> <span m=''797690''>Maybe</span> <span m=''798020''>let</span>
  <span m=''798200''>me</span> <span m=''798340''>show</span> <span m=''798600''>you</span>
  <span m=''799050''>some</span> <span m=''799400''>examples.</span> <span m=''800830''>Out</span>
  <span m=''801090''>here,</span> <span m=''801930''>for</span> <span m=''802110''>example,</span>
  <span m=''802670''>this</span> <span m=''803820''>flap</span> <span m=''805180''>is</span>
  <span m=''805540''>labeled</span> <span m=''805990''>A</span> <span m=''806180''>B,</span>
  <span m=''806830''>so</span> <span m=''807140''>it</span> <span m=''807270''>corresponds</span>
  <span m=''807780''>to</span> <span m=''807890''>this</span> <span m=''808080''>flap.</span>
  </p><p><span m=''809370''>And</span> <span m=''809610''>it</span> <span m=''809680''>corresponds</span>
  <span m=''810330''>to</span> <span m=''810470''>the</span> <span m=''810620''>material</span>
  <span m=''811240''>here</span> <span m=''811570''>between</span> <span m=''811970''>A</span>
  <span m=''812160''>and</span> <span m=''812310''>B.</span> <span m=''814180''>And</span>
  <span m=''814600''>this</span> <span m=''814850''>A</span> <span m=''815040''>part</span>
  <span m=''815470''>is</span> <span m=''815750''>at</span> <span m=''815960''>the</span>
  <span m=''816040''>very</span> <span m=''816560''>tip</span> <span m=''816820''>here,</span>
  <span m=''817780''>and</span> <span m=''818160''>attached</span> <span m=''818630''>to</span>
  <span m=''818720''>this</span> <span m=''819136''>is</span> <span m=''819552''>this</span>
  <span m=''819970''>guy.</span> <span m=''820190''>That</span> <span m=''820360''>would</span>
  <span m=''820500''>be</span> <span m=''820640''>this</span> <span m=''820900''>unlabeled</span>
  <span m=''821670''>pink</span> <span m=''821970''>edge,</span> <span m=''822730''>which</span>
  <span m=''822990''>corresponds</span> <span m=''823430''>to</span> <span m=''823500''>this</span>
  <span m=''823690''>one.</span> <span m=''823830''>It''s</span> <span m=''823950''>unlabeled,</span>
  <span m=''824450''>because</span> <span m=''824700''>it</span> <span m=''824770''>goes</span>
  <span m=''824980''>off</span> <span m=''825150''>to</span> <span m=''825280''>infinity</span>
  <span m=''825780''>in</span> <span m=''825910''>principle.</span> <span m=''826500''>So</span>
  <span m=''826560''>this</span> <span m=''826750''>would</span> <span m=''826860''>just</span>
  <span m=''827010''>keep</span> <span m=''827170''>going.</span> <span m=''828000''>This</span>
  <span m=''828180''>one</span> <span m=''828390''>turns</span> <span m=''828670''>around</span>
  <span m=''828990''>right</span> <span m=''829170''>here.</span> <span m=''829890''>Then</span>
  <span m=''830090''>there''s</span> <span m=''830290''>this</span> <span m=''830480''>edge,</span>
  <span m=''831260''>this</span> <span m=''831820''>bit</span> <span m=''831990''>of</span>
  <span m=''832070''>material.</span> <span m=''833290''>Sorry,</span> <span m=''833610''>it''s
  probably</span> <span m=''833960''>easier</span> <span m=''834140''>for you to</span>
  <span m=''834290''>see</span> <span m=''834470''>from</span> <span m=''834670''>that
  side.</span> </p><p><span m=''836320''>And</span> <span m=''836920''>that</span>
  <span m=''837170''>corresponds</span> <span m=''837680''>to</span> <span m=''837770''>this</span>
  <span m=''837990''>BC</span> <span m=''838460''>part,</span> <span m=''839540''>which</span>
  <span m=''839810''>is</span> <span m=''839930''>exactly</span> <span m=''840470''>this</span>
  <span m=''840730''>folding.</span> <span m=''841160''>And if I</span> <span m=''842260''>laser</span>
  <span m=''842710''>cut</span> <span m=''843240''>or even</span> <span m=''843830''>scissor</span>
  <span m=''843930''>cut</span> <span m=''844570''>down</span> <span m=''844950''>these</span>
  <span m=''845200''>two</span> <span m=''845420''>lines,</span> <span m=''847430''>and</span>
  <span m=''847750''>just</span> <span m=''847930''>cut</span> <span m=''848120''>out</span>
  <span m=''848290''>that</span> <span m=''848490''>little</span> <span m=''848700''>folded</span>
  <span m=''849080''>part,</span> <span m=''849400''>it</span> <span m=''849510''>would</span>
  <span m=''849660''>look</span> <span m=''849830''>exactly</span> <span m=''850390''>like</span>
  <span m=''850610''>this.</span> <span m=''851980''>So</span> <span m=''852480''>conversely,</span>
  <span m=''853740''>I</span> <span m=''853870''>was</span> <span m=''853990''>sort</span>
  <span m=''854140''>of</span> <span m=''854530''>begging</span> <span m=''854840''>the</span>
  <span m=''854910''>question</span> <span m=''855280''>by</span> <span m=''855390''>assuming</span>
  <span m=''855770''>I</span> <span m=''855830''>could</span> <span m=''855990''>fold</span>
  <span m=''856210''>this</span> <span m=''856400''>thing,</span> <span m=''857730''>if</span>
  <span m=''857880''>you</span> <span m=''857950''>don''t</span> <span m=''858150''>know</span>
  <span m=''858220''>how</span> <span m=''858370''>to</span> <span m=''858450''>fold</span>
  <span m=''858670''>this</span> <span m=''858840''>thing,</span> <span m=''859570''>you</span>
  <span m=''859760''>can</span> <span m=''860000''>go</span> <span m=''860130''>on</span>
  <span m=''860240''>the</span> <span m=''860360''>reverse</span> <span m=''860580''>direction</span>
  <span m=''861070''>and</span> <span m=''861240''>figure</span> <span m=''861490''>out</span>
  <span m=''861560''>how</span> <span m=''861730''>to</span> <span m=''861810''>fold</span>
  <span m=''862130''>it</span> <span m=''862730''>by</span> <span m=''862870''>first</span>
  <span m=''863360''>modeling</span> <span m=''863870''>these</span> <span m=''864090''>corridors</span>
  <span m=''864770''>as</span> <span m=''864960''>a</span> <span m=''865030''>tree.</span>
  </p><p><span m=''865720''>How</span> <span m=''865910''>do</span> <span m=''865970''>you</span>
  <span m=''866080''>do</span> <span m=''866210''>that?</span> <span m=''867010''>It''s</span>
  <span m=''867390''>just</span> <span m=''867740''>like</span> <span m=''868100''>in</span>
  <span m=''868770''>the</span> <span m=''868920''>tree</span> <span m=''869160''>method,</span>
  <span m=''870000''>going</span> <span m=''870280''>from</span> <span m=''871180''>crease</span>
  <span m=''871420''>pattern</span> <span m=''871760''>from</span> <span m=''872050''>the</span>
  <span m=''872130''>tree</span> <span m=''872310''>method</span> <span m=''873010''>to</span>
  <span m=''873270''>the</span> <span m=''873370''>shadow</span> <span m=''873710''>tree.</span>
  <span m=''875940''>Except</span> <span m=''876460''>there,</span> <span m=''876810''>we</span>
  <span m=''877020''>were</span> <span m=''877170''>given</span> <span m=''877460''>the</span>
  <span m=''877530''>shadow</span> <span m=''877800''>tree</span> <span m=''878010''>as</span>
  <span m=''878120''>input.</span> <span m=''878480''>Here,</span> <span m=''878730''>we</span>
  <span m=''878830''>have</span> <span m=''878980''>to</span> <span m=''879070''>compute</span>
  <span m=''879450''>it.</span> <span m=''881930''>But</span> <span m=''882070''>it''s</span>
  <span m=''882240''>like</span> <span m=''882390''>what</span> <span m=''882520''>you</span>
  <span m=''882610''>solved</span> <span m=''882890''>in</span> <span m=''882990''>the</span>
  <span m=''883100''>problem</span> <span m=''883380''>set.</span> <span m=''883935''>Is
  it</span> <span m=''884260''>one</span> <span m=''884500''>or</span> <span m=''884600''>two?</span>
  <span m=''886640''>For</span> <span m=''886810''>each</span> <span m=''887020''>of</span>
  <span m=''887090''>these</span> <span m=''887270''>corridors,</span> <span m=''888335''>it</span>
  <span m=''888630''>has</span> <span m=''888880''>fixed</span> <span m=''889170''>width,</span>
  <span m=''889500''>so</span> <span m=''889620''>you</span> <span m=''889770''>make</span>
  <span m=''889970''>an</span> <span m=''890120''>edge</span> <span m=''890890''>of</span>
  <span m=''891080''>that</span> <span m=''891280''>length.</span> <span m=''891605''>It''s</span>
  <span m=''891930''>not</span> <span m=''892190''>quite</span> <span m=''892390''>drawn</span>
  <span m=''892610''>to</span> <span m=''892680''>scale</span> <span m=''893000''>here.</span>
  <span m=''893140''>This</span> <span m=''893340''>has</span> <span m=''893440''>been</span>
  <span m=''893580''>scaled</span> <span m=''893900''>up</span> <span m=''894040''>by</span>
  <span m=''894710''>roughly</span> <span m=''894970''>a</span> <span m=''895010''>factor</span>
  <span m=''895350''>of</span> <span m=''895450''>two.</span> <span m=''896090''>So</span>
  <span m=''896240''>this</span> <span m=''896460''>length</span> <span m=''897450''>becomes</span>
  <span m=''897970''>this</span> <span m=''898160''>length.</span> </p><p><span m=''899740''>And</span>
  <span m=''899920''>you</span> <span m=''900050''>label</span> <span m=''900390''>it</span>
  <span m=''900500''>the</span> <span m=''900580''>same</span> <span m=''900840''>thing.</span>
  <span m=''901210''>This</span> <span m=''902310''>set</span> <span m=''902670''>of</span>
  <span m=''902730''>connecting</span> <span m=''903130''>component of</span> <span
  m=''903590''>perpendiculars</span> <span m=''904160''>A</span> <span m=''904966''>goes</span>
  <span m=''905370''>to</span> <span m=''905440''>that</span> <span m=''905680''>point.</span>
  <span m=''906130''>The</span> <span m=''906280''>connected</span> <span m=''906640''>component
  of</span> <span m=''907390''>perpendiculars</span> <span m=''908010''>here,</span>
  <span m=''908860''>this</span> <span m=''909100''>thing</span> <span m=''909330''>which</span>
  <span m=''909580''>branches,</span> <span m=''910220''>all</span> <span m=''910460''>of</span>
  <span m=''910550''>that</span> <span m=''910760''>is</span> <span m=''910900''>B.</span>
  <span m=''912050''>It''s</span> <span m=''912180''>like</span> <span m=''912370''>a</span>
  <span m=''912430''>hinge</span> <span m=''913070''>in</span> <span m=''913190''>the</span>
  <span m=''913280''>tree</span> <span m=''913460''>method.</span> <span m=''914200''>So</span>
  <span m=''914370''>that''s</span> <span m=''914610''>going</span> <span m=''914710''>to</span>
  <span m=''914760''>be</span> <span m=''914910''>a hinge</span> <span m=''915740''>between</span>
  <span m=''916090''>this</span> <span m=''916240''>flap</span> <span m=''917280''>and</span>
  <span m=''917690''>two</span> <span m=''917870''>other</span> <span m=''918060''>flaps,</span>
  <span m=''918590''>whatever</span> <span m=''919100''>touches</span> <span m=''920130''>the</span>
  <span m=''920290''>B</span> <span m=''921030''>perpendicular.</span> <span m=''921780''>So</span>
  <span m=''921960''>there''s</span> <span m=''922160''>this</span> <span m=''922590''>pink</span>
  <span m=''922780''>one,</span> <span m=''923410''>and</span> <span m=''923660''>there''s</span>
  <span m=''923850''>the</span> <span m=''923940''>cyan</span> <span m=''924370''>one.</span>
  <span m=''925370''>Cyan</span> <span m=''925730''>one</span> <span m=''925890''>is</span>
  <span m=''926020''>here.</span> <span m=''927800''>It''s</span> <span m=''928000''>attached</span>
  <span m=''928550''>to</span> <span m=''929370''>whatever</span> <span m=''929810''>C</span>
  <span m=''930110''>is</span> <span m=''930240''>attached</span> <span m=''930505''>to.</span>
  <span m=''931050''>so</span> <span m=''931300''>here''s</span> <span m=''931530''>C.</span>
  </p><p><span m=''932810''>It</span> <span m=''932950''>branches</span> <span m=''933340''>off</span>
  <span m=''933550''>here,</span> <span m=''933820''>bounces</span> <span m=''934220''>around.</span>
  <span m=''935000''>All</span> <span m=''935240''>that''s</span> <span m=''935470''>C,</span>
  <span m=''935770''>and it''s</span> <span m=''935920''>adjacent</span> <span m=''936140''>to</span>
  <span m=''936290''>the</span> <span m=''936400''>blue</span> <span m=''936670''>thing</span>
  <span m=''936930''>we</span> <span m=''937020''>just</span> <span m=''937240''>did.</span>
  <span m=''937830''>The</span> <span m=''937930''>yellow</span> <span m=''938280''>and</span>
  <span m=''938500''>the</span> <span m=''938580''>pink--</span> <span m=''939450''>that''s</span>
  <span m=''939680''>this</span> <span m=''939830''>yellow</span> <span m=''940230''>and</span>
  <span m=''940360''>this</span> <span m=''940540''>pink--</span> <span m=''942540''>connecting</span>
  <span m=''942900''>to</span> <span m=''943020''>D and</span> <span m=''943450''>G,</span>
  <span m=''944290''>and</span> <span m=''944540''>so</span> <span m=''944700''>on</span>
  <span m=''944960''>through</span> <span m=''945120''>the</span> <span m=''945230''>thing.</span>
  <span m=''945530''>So</span> <span m=''945730''>it''s</span> <span m=''945870''>actually</span>
  <span m=''946150''>really</span> <span m=''946340''>easy</span> <span m=''946590''>to</span>
  <span m=''946670''>map</span> <span m=''946960''>from</span> <span m=''947160''>here</span>
  <span m=''947770''>to</span> <span m=''947910''>the</span> <span m=''947980''>tree,</span>
  <span m=''948270''>just</span> <span m=''948490''>every</span> <span m=''948720''>corridor</span>
  <span m=''949770''>maps</span> <span m=''950070''>to</span> <span m=''950180''>an</span>
  <span m=''950260''>edge.</span> <span m=''951010''>Every</span> <span m=''951400''>connected</span>
  <span m=''951780''>component</span> <span m=''952180''>of</span> <span m=''952280''>the</span>
  <span m=''952410''>perpendicular</span> <span m=''953070''>graph</span> <span m=''953900''>maps</span>
  <span m=''954220''>to</span> <span m=''954520''>a</span> <span m=''954620''>point.</span>
  <span m=''956680''>And</span> <span m=''956790''>this</span> <span m=''956980''>is</span>
  <span m=''957090''>the</span> <span m=''957210''>projection.</span> <span m=''957740''>It</span>
  <span m=''958370''>will</span> <span m=''958530''>always</span> <span m=''958870''>look</span>
  <span m=''959050''>exactly</span> <span m=''959430''>like</span> <span m=''959590''>this.</span>
  </p><p><span m=''959900''>You''ll</span> <span m=''959920''>be</span> <span m=''960040''>able</span>
  <span m=''960210''>to</span> <span m=''960300''>independently</span> <span m=''960880''>manipulate</span>
  <span m=''961840''>each</span> <span m=''962040''>of</span> <span m=''962090''>these</span>
  <span m=''962260''>corridors</span> <span m=''962750''>as</span> <span m=''962930''>a</span>
  <span m=''962990''>flap.</span> <span m=''964580''>And</span> <span m=''964970''>individually</span>
  <span m=''965650''>it''s</span> <span m=''965940''>pretty</span> <span m=''966260''>easy</span>
  <span m=''966510''>to</span> <span m=''966590''>fold</span> <span m=''966920''>each</span>
  <span m=''967120''>corridor.</span> <span m=''968150''>It</span> <span m=''968300''>just</span>
  <span m=''968540''>looks</span> <span m=''968780''>like</span> <span m=''969970''>this</span>
  <span m=''970180''>accordion</span> <span m=''970680''>thing.</span> <span m=''971290''>So</span>
  <span m=''972140''>the</span> <span m=''973400''>faces</span> <span m=''973980''>will</span>
  <span m=''974150''>be</span> <span m=''974380''>stacked</span> <span m=''975280''>linearly</span>
  <span m=''976060''>in</span> <span m=''976190''>order</span> <span m=''976910''>from</span>
  <span m=''977450''>back</span> <span m=''977660''>to</span> <span m=''977750''>front,</span>
  <span m=''978740''>and</span> <span m=''980730''>be</span> <span m=''980940''>really</span>
  <span m=''981130''>clean.</span> <span m=''981490''>They''ll</span> <span m=''981840''>all</span>
  <span m=''982270''>line</span> <span m=''982510''>up</span> <span m=''983260''>in</span>
  <span m=''983420''>this</span> <span m=''983610''>nice</span> <span m=''984270''>vertical</span>
  <span m=''984620''>strip.</span> <span m=''988180''>So</span> <span m=''988330''>that''s</span>
  <span m=''988550''>easy</span> <span m=''988840''>to</span> <span m=''988960''>prove</span>
  <span m=''989510''>it</span> <span m=''989690''>exists</span> <span m=''990095''>from</span>
  <span m=''990500''>sketching</span> <span m=''990860''>the</span> <span m=''990940''>proof</span>
  <span m=''991220''>now.</span> <span m=''992320''>And</span> <span m=''992500''>then</span>
  <span m=''992660''>all</span> <span m=''992810''>you</span> <span m=''992910''>have</span>
  <span m=''993060''>to</span> <span m=''993150''>do</span> <span m=''993270''>is</span>
  <span m=''993370''>attach</span> <span m=''993830''>them</span> <span m=''994000''>together.</span>
  <span m=''994930''>So</span> <span m=''995160''>basically</span> <span m=''996630''>first</span>
  <span m=''996870''>you</span> <span m=''996960''>take</span> <span m=''997150''>this</span>
  <span m=''997290''>tree</span> <span m=''997490''>view,</span> <span m=''997990''>you</span>
  <span m=''998110''>fold</span> <span m=''998450''>it</span> <span m=''998590''>flat.</span>
  <span m=''999120''>Here,</span> <span m=''999390''>I</span> <span m=''999430''>can</span>
  <span m=''999600''>fold</span> <span m=''999780''>it</span> <span m=''999930''>flat</span>
  <span m=''1000010''>just</span> <span m=''1000200''>by</span> <span m=''1000290''>collapsing</span>
  <span m=''1000850''>the</span> <span m=''1000950''>top</span> <span m=''1001220''>and</span>
  <span m=''1001290''>bottom.</span> <span m=''1002200''>Then</span> <span m=''1002370''>I</span>
  <span m=''1002410''>replace</span> <span m=''1002890''>each</span> <span m=''1003090''>of</span>
  <span m=''1003160''>these</span> <span m=''1003370''>edges</span> <span m=''1003750''>with</span>
  <span m=''1003840''>one</span> <span m=''1004010''>of</span> <span m=''1004070''>these</span>
  <span m=''1004520''>vertical</span> <span m=''1005140''>accordion</span> <span m=''1005720''>strips.</span>
  </p><p><span m=''1007050''>And</span> <span m=''1007210''>then</span> <span m=''1007330''>I</span>
  <span m=''1007390''>just</span> <span m=''1007600''>need</span> <span m=''1007710''>to</span>
  <span m=''1007790''>check</span> <span m=''1008120''>that</span> <span m=''1008260''>at</span>
  <span m=''1008430''>each</span> <span m=''1008620''>vertex</span> <span m=''1009030''>I</span>
  <span m=''1009100''>can</span> <span m=''1009260''>actually</span> <span m=''1009580''>attach</span>
  <span m=''1010040''>everything</span> <span m=''1010370''>that</span> <span m=''1010480''>needs</span>
  <span m=''1010690''>to</span> <span m=''1010800''>attach</span> <span m=''1011260''>without</span>
  <span m=''1011610''>getting</span> <span m=''1011830''>crossings.</span> <span m=''1012470''>So</span>
  <span m=''1012530''>that''s</span> <span m=''1012760''>the</span> <span m=''1012850''>one</span>
  <span m=''1013030''>part</span> <span m=''1013190''>of</span> <span m=''1013230''>the</span>
  <span m=''1013300''>proof</span> <span m=''1013520''>I''m</span> <span m=''1013610''>not</span>
  <span m=''1013810''>going</span> <span m=''1013920''>to</span> <span m=''1013970''>show</span>
  <span m=''1014160''>you,</span> <span m=''1014870''>because</span> <span m=''1015060''>it''s</span>
  <span m=''1015180''>kind</span> <span m=''1015330''>of</span> <span m=''1015420''>tedious.</span>
  <span m=''1016000''>But</span> <span m=''1016970''>basically,</span> <span m=''1017400''>because</span>
  <span m=''1017850''>the</span> <span m=''1017960''>structure</span> <span m=''1018410''>was</span>
  <span m=''1019260''>planar,</span> <span m=''1019670''>because</span> <span m=''1019960''>it</span>
  <span m=''1020050''>came</span> <span m=''1020270''>from</span> <span m=''1020490''>one</span>
  <span m=''1020670''>sheet,</span> <span m=''1021660''>you</span> <span m=''1021820''>can
  show</span> <span m=''1022110''>there''s</span> <span m=''1022630''>not</span> <span
  m=''1022830''>going</span> <span m=''1022910''>to</span> <span m=''1022960''>be</span>
  <span m=''1023060''>any</span> <span m=''1023200''>crossings</span> <span m=''1023680''>there.</span>
  <span m=''1024760''>All</span> <span m=''1024980''>of</span> <span m=''1025079''>these</span>
  <span m=''1025270''>layers,</span> <span m=''1026380''>each</span> <span m=''1026560''>of</span>
  <span m=''1026619''>these</span> <span m=''1026780''>edges</span> <span m=''1027069''>expands</span>
  <span m=''1027480''>to</span> <span m=''1027579''>be</span> <span m=''1027710''>many</span>
  <span m=''1027960''>layers,</span> <span m=''1028420''>and</span> <span m=''1028540''>the</span>
  <span m=''1028630''>layers</span> <span m=''1028960''>will</span> <span m=''1029130''>nicely</span>
  <span m=''1029540''>connect</span> <span m=''1029829''>together.</span> <span m=''1031380''>So</span>
  <span m=''1031569''>that''s</span> <span m=''1031839''>the</span> <span m=''1032890''>sketch</span>
  <span m=''1033240''>of that</span> <span m=''1033410''>proof.</span> <span m=''1033810''>Any
  questions?</span> <span m=''1034260''>This</span> <span m=''1034430''>is</span>
  <span m=''1034560''>for</span> <span m=''1034740''>just</span> <span m=''1034950''>linear</span>
  <span m=''1035280''>corridors,</span> <span m=''1035710''>not</span> <span m=''1035880''>circular</span>
  <span m=''1036230''>ones.</span> </p><p><span m=''1038339''>OK.</span> <span m=''1041190''>Cool.</span>
  <span m=''1046680''>Next</span> <span m=''1046960''>question</span> <span m=''1048230''>is</span>
  <span m=''1048510''>about</span> <span m=''1048990''>the</span> <span m=''1049300''>bad</span>
  <span m=''1049680''>example</span> <span m=''1050760''>that</span> <span m=''1052490''>makes</span>
  <span m=''1052750''>a</span> <span m=''1052820''>dense</span> <span m=''1053260''>set</span>
  <span m=''1053430''>of</span> <span m=''1053530''>creases</span> <span m=''1053940''>that</span>
  <span m=''1054030''>completely</span> <span m=''1054600''>fills</span> <span m=''1054880''>the</span>
  <span m=''1055000''>plane,</span> <span m=''1055800''>and therefore</span> <span
  m=''1055960''>is</span> <span m=''1056220''>completely</span> <span m=''1056670''>unfoldable.</span>
  <span m=''1059270''>And</span> <span m=''1061170''>the</span> <span m=''1061250''>question</span>
  <span m=''1061560''>was,</span> <span m=''1061900''>is</span> <span m=''1062100''>it</span>
  <span m=''1062210''>really</span> <span m=''1062610''>unlikely</span> <span m=''1063270''>or</span>
  <span m=''1063410''>is</span> <span m=''1063510''>actually</span> <span m=''1064630''>very</span>
  <span m=''1064880''>likely</span> <span m=''1065260''>that</span> <span m=''1065390''>this</span>
  <span m=''1065560''>happens?</span> <span m=''1066210''>And</span> <span m=''1066410''>there</span>
  <span m=''1066540''>are</span> <span m=''1066610''>two</span> <span m=''1066800''>things</span>
  <span m=''1067080''>going</span> <span m=''1067350''>on.</span> <span m=''1067500''>Here''s</span>
  <span m=''1067750''>the</span> <span m=''1067840''>example,</span> <span m=''1068910''>again,</span>
  <span m=''1070390''>from</span> <span m=''1070580''>the</span> <span m=''1070670''>textbook.</span>
  <span m=''1071280''>So</span> <span m=''1071630''>it''s</span> <span m=''1071850''>got,</span>
  <span m=''1072080''>the</span> <span m=''1072280''>dark</span> <span m=''1072550''>blue
  is</span> <span m=''1072970''>the</span> <span m=''1073150''>desire</span> <span
  m=''1073510''>cut</span> <span m=''1073770''>graph,</span> <span m=''1074260''>then</span>
  <span m=''1074440''>the</span> <span m=''1074530''>black</span> <span m=''1074910''>lines</span>
  <span m=''1075300''>are</span> <span m=''1075460''>the</span> <span m=''1075640''>straight</span>
  <span m=''1075910''>skeleton,</span> <span m=''1076490''>and</span> <span m=''1076650''>then</span>
  <span m=''1077040''>the</span> <span m=''1077850''>dash</span> <span m=''1078360''>lines</span>
  <span m=''1078720''>are</span> <span m=''1078780''>the</span> <span m=''1078880''>beginning</span>
  <span m=''1079250''>of</span> <span m=''1079300''>the</span> <span m=''1079390''>perpendiculars.</span>
  <span m=''1080830''>And</span> <span m=''1081560''>the</span> <span m=''1081760''>point</span>
  <span m=''1082080''>was</span> <span m=''1082420''>to</span> <span m=''1082620''>make</span>
  <span m=''1083780''>this</span> <span m=''1084660''>corridor</span> <span m=''1085130''>width</span>
  <span m=''1086050''>verses</span> <span m=''1086910''>this</span> <span m=''1087260''>corridor</span>
  <span m=''1087680''>width</span> <span m=''1088180''>verses</span> <span m=''1088720''>this</span>
  <span m=''1088940''>quarter</span> <span m=''1089350''>width</span> <span m=''1089670''>versus</span>
  <span m=''1090030''>this</span> <span m=''1090200''>corner</span> <span m=''1090470''>width,</span>
  <span m=''1090660''>make</span> <span m=''1090830''>those</span> <span m=''1091000''>all</span>
  <span m=''1091220''>irrational</span> <span m=''1091710''>multiples</span> <span
  m=''1092160''>of</span> <span m=''1092250''>each</span> <span m=''1092420''>other.</span>
  <span m=''1093230''>And</span> <span m=''1093420''>then</span> <span m=''1093640''>as</span>
  <span m=''1093890''>this</span> <span m=''1094070''>thing</span> <span m=''1094360''>spirals</span>
  <span m=''1094800''>around,</span> <span m=''1095180''>it</span> <span m=''1095290''>never</span>
  <span m=''1095580''>finishes.</span> <span m=''1095855''>It</span> <span m=''1096130''>never</span>
  <span m=''1096380''>hits</span> <span m=''1096620''>itself.</span> </p><p><span
  m=''1097410''>And</span> <span m=''1097560''>so</span> <span m=''1097670''>it</span>
  <span m=''1097750''>just</span> <span m=''1097930''>keeps</span> <span m=''1098180''>going.</span>
  <span m=''1098610''>I</span> <span m=''1098690''>think</span> <span m=''1098950''>this</span>
  <span m=''1099160''>is</span> <span m=''1099310''>where</span> <span m=''1099530''>this</span>
  <span m=''1099700''>one''s</span> <span m=''1099950''>currently</span> <span m=''1100310''>going.</span>
  <span m=''1105470''>And</span> <span m=''1105640''>so</span> <span m=''1105800''>the</span>
  <span m=''1106330''>question</span> <span m=''1107290''>is,</span> <span m=''1107770''>well,</span>
  <span m=''1108680''>irrational</span> <span m=''1109180''>multiples</span> <span
  m=''1109590''>are</span> <span m=''1109670''>actually</span> <span m=''1109930''>very</span>
  <span m=''1110170''>common.</span> <span m=''1110760''>If</span> <span m=''1110930''>you,</span>
  <span m=''1111170''>for</span> <span m=''1111220''>example,</span> <span m=''1111660''>randomly</span>
  <span m=''1112120''>perturb</span> <span m=''1112510''>all</span> <span m=''1112620''>these</span>
  <span m=''1112790''>vertices</span> <span m=''1113360''>and</span> <span m=''1113430''>you</span>
  <span m=''1113530''>measure</span> <span m=''1113880''>the</span> <span m=''1114410''>sizes</span>
  <span m=''1114880''>of</span> <span m=''1115000''>those</span> <span m=''1115570''>corridors,</span>
  <span m=''1117370''>with</span> <span m=''1117860''>probability</span> <span m=''1118420''>1,</span>
  <span m=''1118810''>they</span> <span m=''1118920''>will</span> <span m=''1119090''>be</span>
  <span m=''1119400''>irrational</span> <span m=''1119780''>multiples</span> <span
  m=''1120210''>of</span> <span m=''1120310''>each</span> <span m=''1120480''>other,</span>
  <span m=''1120640''>because</span> <span m=''1120830''>irrationals</span> <span
  m=''1121350''>are</span> <span m=''1121430''>much</span> <span m=''1121970''>more</span>
  <span m=''1122160''>common</span> <span m=''1122600''>than</span> <span m=''1122750''>rational</span>
  <span m=''1123140''>numbers.</span> </p><p><span m=''1124390''>And</span> <span
  m=''1124470''>that''s</span> <span m=''1124670''>true.</span> <span m=''1125880''>But</span>
  <span m=''1127280''>the</span> <span m=''1127510''>other</span> <span m=''1127830''>thing</span>
  <span m=''1128040''>that</span> <span m=''1128180''>this</span> <span m=''1128360''>example</span>
  <span m=''1128900''>requires</span> <span m=''1129990''>is</span> <span m=''1130310''>this</span>
  <span m=''1130580''>outer</span> <span m=''1130890''>boundary.</span> <span m=''1132030''>We</span>
  <span m=''1132190''>need</span> <span m=''1132560''>that</span> <span m=''1132750''>none</span>
  <span m=''1132990''>of</span> <span m=''1133070''>these</span> <span m=''1133240''>perpendiculars</span>
  <span m=''1133870''>can</span> <span m=''1134070''>escape</span> <span m=''1134530''>out</span>
  <span m=''1134730''>to</span> <span m=''1134820''>infinity.</span> <span m=''1135340''>If</span>
  <span m=''1135510''>they</span> <span m=''1135660''>do,</span> <span m=''1136590''>they</span>
  <span m=''1136720''>won''t</span> <span m=''1137010''>stay</span> <span m=''1137250''>in</span>
  <span m=''1137370''>there.</span> <span m=''1137590''>Eventually,</span> <span m=''1138340''>if</span>
  <span m=''1138480''>there''s</span> <span m=''1138660''>a</span> <span m=''1138790''>tiny,</span>
  <span m=''1139240''>tiny</span> <span m=''1140060''>gap</span> <span m=''1140390''>here,</span>
  <span m=''1140660''>if</span> <span m=''1140740''>these</span> <span m=''1140950''>guys</span>
  <span m=''1141140''>didn''t</span> <span m=''1141370''>quite</span> <span m=''1141630''>match</span>
  <span m=''1141920''>up,</span> <span m=''1142740''>eventually</span> <span m=''1143400''>because</span>
  <span m=''1143580''>this</span> <span m=''1143740''>thing</span> <span m=''1143920''>is</span>
  <span m=''1144070''>dense,</span> <span m=''1144580''>it</span> <span m=''1144740''>will</span>
  <span m=''1144910''>find</span> <span m=''1145330''>that</span> <span m=''1145510''>little</span>
  <span m=''1145810''>gap</span> <span m=''1146120''>because</span> <span m=''1146330''>it</span>
  <span m=''1146410''>has</span> <span m=''1146600''>positive</span> <span m=''1147000''>length.</span>
  <span m=''1147250''>When</span> <span m=''1147390''>it</span> <span m=''1147490''>finds</span>
  <span m=''1147750''>the</span> <span m=''1147830''>gap,</span> <span m=''1148090''>it''s</span>
  <span m=''1148280''>going</span> <span m=''1148410''>to</span> <span m=''1148490''>spiral</span>
  <span m=''1148960''>around</span> <span m=''1149240''>and</span> <span m=''1149340''>around</span>
  <span m=''1149610''>and</span> <span m=''1149700''>around</span> <span m=''1149970''>and</span>
  <span m=''1150030''>go</span> <span m=''1150150''>out</span> <span m=''1150400''>to</span>
  <span m=''1150490''>infinity</span> <span m=''1151300''>instead</span> <span m=''1151640''>of</span>
  <span m=''1151700''>being</span> <span m=''1151890''>trapped</span> <span m=''1152250''>inside.</span>
  </p><p><span m=''1153450''>So</span> <span m=''1153650''>the</span> <span m=''1153810''>unlikely</span>
  <span m=''1154370''>thing</span> <span m=''1154630''>in</span> <span m=''1154790''>this</span>
  <span m=''1154970''>example</span> <span m=''1155235''>is</span> <span m=''1155500''>actually</span>
  <span m=''1155780''>this</span> <span m=''1155990''>outer</span> <span m=''1156350''>pink</span>
  <span m=''1157080''>polygon,</span> <span m=''1157740''>that</span> <span m=''1158780''>the</span>
  <span m=''1158940''>perpendicular</span> <span m=''1159650''>coming</span> <span
  m=''1160030''>out</span> <span m=''1160190''>this</span> <span m=''1160400''>way</span>
  <span m=''1161190''>bounced</span> <span m=''1161580''>around,</span> <span m=''1161650''>did</span>
  <span m=''1162200''>lots</span> <span m=''1162450''>of</span> <span m=''1162550''>things,</span>
  <span m=''1162870''>and</span> <span m=''1162970''>eventually</span> <span m=''1163890''>hit</span>
  <span m=''1164070''>the</span> <span m=''1164180''>same</span> <span m=''1164470''>vertex.</span>
  <span m=''1165020''>That''s</span> <span m=''1165220''>actually</span> <span m=''1166420''>unlikely.</span>
  <span m=''1167360''>Definitely</span> <span m=''1167970''>in</span> <span m=''1168080''>this</span>
  <span m=''1168240''>example</span> <span m=''1168710''>and in</span> <span m=''1168910''>general</span>
  <span m=''1169280''>we</span> <span m=''1169400''>claim</span> <span m=''1170180''>that</span>
  <span m=''1170700''>we</span> <span m=''1170870''>do</span> <span m=''1171010''>not</span>
  <span m=''1171300''>get</span> <span m=''1171490''>cycles</span> <span m=''1171910''>of</span>
  <span m=''1172180''>perpendiculars</span> <span m=''1173470''>except</span> <span
  m=''1174160''>in</span> <span m=''1174360''>one</span> <span m=''1174710''>kind</span>
  <span m=''1174940''>of</span> <span m=''1175010''>scenario,</span> <span m=''1176290''>which</span>
  <span m=''1177330''>I</span> <span m=''1177420''>guess</span> <span m=''1177620''>I</span>
  <span m=''1177680''>could</span> <span m=''1177830''>draw</span> <span m=''1178220''>in</span>
  <span m=''1178940''>the</span> <span m=''1179010''>software.</span> <span m=''1179710''>Let''s</span>
  <span m=''1180070''>try</span> <span m=''1180537''>it.</span> <span m=''1183340''>So</span>
  <span m=''1183610''>whenever</span> <span m=''1183930''>you</span> <span m=''1184080''>have</span>
  <span m=''1184550''>a</span> <span m=''1184910''>vertex</span> <span m=''1185350''>of</span>
  <span m=''1185490''>degree</span> <span m=''1185910''>more</span> <span m=''1186440''>than</span>
  <span m=''1190310''>two,</span> <span m=''1192780''>so</span> <span m=''1193060''>let''s</span>
  <span m=''1193380''>do</span> <span m=''1193780''>something</span> <span m=''1194220''>like</span>
  <span m=''1194640''>that.</span> </p><p><span m=''1198720''>Little</span> <span
  m=''1198930''>too</span> <span m=''1199100''>far</span> <span m=''1199440''>away.</span>
  <span m=''1199930''>So</span> <span m=''1200000''>let</span> <span m=''1200140''>me</span>
  <span m=''1200250''>just</span> <span m=''1200490''>add</span> <span m=''1200700''>a</span>
  <span m=''1200760''>little</span> <span m=''1201000''>guy</span> <span m=''1201300''>like</span>
  <span m=''1201620''>this.</span> <span m=''1205510''>And</span> <span m=''1207720''>this</span>
  <span m=''1207900''>a little</span> <span m=''1208100''>closer.</span> <span m=''1217360''>It''s</span>
  <span m=''1217570''>got</span> <span m=''1217690''>a</span> <span m=''1217740''>lot</span>
  <span m=''1217880''>of</span> <span m=''1217950''>spiraling.</span> <span m=''1218960''>Let''s</span>
  <span m=''1219100''>make</span> <span m=''1219270''>it a</span> <span m=''1219310''>little</span>
  <span m=''1219580''>bit</span> <span m=''1220000''>cleaner</span> <span m=''1220390''>here.</span>
  <span m=''1221700''>It''s</span> <span m=''1222000''>actually</span> <span m=''1222350''>kind</span>
  <span m=''1222510''>of</span> <span m=''1222580''>degenerate,</span> <span m=''1223300''>but</span>
  <span m=''1224760''>the</span> <span m=''1224880''>point</span> <span m=''1225090''>is,</span>
  <span m=''1226180''>if--</span> <span m=''1226510''>here</span> <span m=''1226750''>I</span>
  <span m=''1226790''>have</span> <span m=''1227170''>three</span> <span m=''1227510''>cut</span>
  <span m=''1227720''>edges.</span> <span m=''1229030''>I''ve</span> <span m=''1229050''>kind</span>
  <span m=''1229260''>of</span> <span m=''1229460''>made</span> <span m=''1229650''>them</span>
  <span m=''1229790''>roughly</span> <span m=''1230110''>equal</span> <span m=''1230470''>so</span>
  <span m=''1230620''>this</span> <span m=''1230990''>doesn''t</span> <span m=''1231270''>get</span>
  <span m=''1231590''>huge,</span> <span m=''1232510''>but</span> <span m=''1232610''>in</span>
  <span m=''1232720''>general,</span> <span m=''1233200''>if</span> <span m=''1233320''>you</span>
  <span m=''1233390''>have</span> <span m=''1233510''>any</span> <span m=''1233800''>straight</span>
  <span m=''1234080''>skeleton</span> <span m=''1234640''>vertex</span> <span m=''1235840''>and</span>
  <span m=''1236200''>you</span> <span m=''1236390''>reflect</span> <span m=''1236670''>it''</span>
  <span m=''1236950''>around</span> <span m=''1238440''>these</span> <span m=''1238880''>bisectors,</span>
  <span m=''1239890''>you</span> <span m=''1240010''>will</span> <span m=''1240150''>always</span>
  <span m=''1240490''>come</span> <span m=''1240680''>back</span> <span m=''1240900''>to</span>
  <span m=''1241000''>where</span> <span m=''1241140''>you</span> <span m=''1241210''>started.</span>
  </p><p><span m=''1243600''>So</span> <span m=''1244330''>this</span> <span m=''1244890''>requires</span>
  <span m=''1245330''>that each</span> <span m=''1245610''>of</span> <span m=''1245670''>these</span>
  <span m=''1245830''>angles</span> <span m=''1246170''>is</span> <span m=''1246260''>strictly</span>
  <span m=''1246610''>convex,</span> <span m=''1247220''>so</span> <span m=''1247330''>this</span>
  <span m=''1247420''>is why</span> <span m=''1247670''>you</span> <span m=''1247790''>need</span>
  <span m=''1248060''>at</span> <span m=''1248130''>least</span> <span m=''1248420''>three</span>
  <span m=''1249240''>cut</span> <span m=''1249450''>edges</span> <span m=''1249910''>to
  come</span> <span m=''1250100''>together</span> <span m=''1250460''>here.</span>
  <span m=''1251440''>But</span> <span m=''1251560''>once</span> <span m=''1251730''>you</span>
  <span m=''1251800''>have</span> <span m=''1251990''>at</span> <span m=''1252050''>least</span>
  <span m=''1252300''>three,</span> <span m=''1254470''>you''ll</span> <span m=''1254760''>always</span>
  <span m=''1255120''>cycle</span> <span m=''1255480''>around.</span> <span m=''1255870''>You''ll
  always</span> <span m=''1256250''>come</span> <span m=''1256400''>back</span> <span
  m=''1256580''>to</span> <span m=''1256680''>where</span> <span m=''1256770''>you</span>
  <span m=''1256830''>started.</span> <span m=''1257180''>It actually</span> <span
  m=''1257420''>happens</span> <span m=''1257730''>again</span> <span m=''1257990''>here.</span>
  <span m=''1258210''>This</span> <span m=''1258430''>guy</span> <span m=''1259140''>cycles</span>
  <span m=''1259580''>around</span> <span m=''1260030''>and</span> <span m=''1260140''>comes</span>
  <span m=''1260420''>back.</span> <span m=''1262720''>So</span> <span m=''1262910''>that''s--</span>
  <span m=''1263610''>well,</span> <span m=''1263810''>sorry,</span> <span m=''1264030''>that</span>
  <span m=''1264200''>one''s</span> <span m=''1264390''>actually</span> <span m=''1264900''>a
  little bit</span> <span m=''1264970''>special</span> <span m=''1266780''>because</span>
  <span m=''1266990''>of what</span> <span m=''1267150''>I</span> <span m=''1268160''>did</span>
  <span m=''1268410''>with</span> <span m=''1268550''>the</span> <span m=''1268650''>dragging.</span>
  <span m=''1269810''>In</span> <span m=''1270050''>general,</span> <span m=''1270650''>it''s</span>
  <span m=''1270780''>going to be</span> <span m=''1271240''>more</span> <span m=''1271480''>like</span>
  <span m=''1271780''>this.</span> </p><p><span m=''1274380''>It''s a</span> <span
  m=''1274420''>little</span> <span m=''1274580''>hard</span> <span m=''1274790''>to</span>
  <span m=''1274860''>see.</span> <span m=''1276610''>What''s</span> <span m=''1276880''>going</span>
  <span m=''1277140''>on</span> <span m=''1277270''>here</span> <span m=''1277610''>is</span>
  <span m=''1277950''>that</span> <span m=''1278120''>this</span> <span m=''1278370''>innermost</span>
  <span m=''1278860''>guy</span> <span m=''1279690''>cycles</span> <span m=''1280160''>around,</span>
  <span m=''1280590''>indeed,</span> <span m=''1281050''>but</span> <span m=''1281210''>everyone</span>
  <span m=''1281630''>else</span> <span m=''1282430''>spirals</span> <span m=''1283010''>around</span>
  <span m=''1284110''>and</span> <span m=''1284400''>keeps</span> <span m=''1285410''>going.</span>
  <span m=''1286320''>So</span> <span m=''1286480''>that''s</span> <span m=''1286700''>actually</span>
  <span m=''1286920''>the</span> <span m=''1287000''>perpendicular.</span> <span m=''1287270''>It</span>
  <span m=''1287540''>comes</span> <span m=''1287780''>from</span> <span m=''1287900''>here
  and</span> <span m=''1288180''>goes</span> <span m=''1288490''>that</span> <span
  m=''1288730''>way,</span> <span m=''1289560''>and</span> <span m=''1289860''>then</span>
  <span m=''1290010''>it</span> <span m=''1290200''>spirals</span> <span m=''1290590''>around.</span>
  <span m=''1290930''>It</span> <span m=''1290990''>hasn''t</span> <span m=''1291270''>finished</span>
  <span m=''1291600''>yet,</span> <span m=''1291850''>but</span> <span m=''1291970''>it</span>
  <span m=''1292040''>would</span> <span m=''1292210''>actually</span> <span m=''1292460''>spiral</span>
  <span m=''1292890''>all</span> <span m=''1293100''>the</span> <span m=''1293180''>way</span>
  <span m=''1293360''>out</span> <span m=''1293560''>to</span> <span m=''1293660''>infinity.</span>
  <span m=''1296170''>So</span> <span m=''1296390''>the</span> <span m=''1296560''>claim</span>
  <span m=''1296920''>is,</span> <span m=''1297340''>in</span> <span m=''1297490''>general,</span>
  <span m=''1298992''>the--</span> <span m=''1304340''>this</span> <span m=''1304390''>is</span>
  <span m=''1304550''>conjecture.</span> <span m=''1315050''>With</span> <span m=''1315260''>probability</span>
  <span m=''1315890''>1,</span> <span m=''1316420''>if</span> <span m=''1316600''>you</span>
  <span m=''1316890''>randomly</span> <span m=''1317340''>perturb</span> <span m=''1317820''>the
  vertices</span> <span m=''1318220''>slightly,</span> <span m=''1319920''>the</span>
  <span m=''1323090''>only</span> <span m=''1323550''>cycles</span> <span m=''1324250''>of</span>
  <span m=''1324420''>perpendiculars</span> <span m=''1325160''>that</span> <span
  m=''1325240''>you</span> <span m=''1325420''>get</span> <span m=''1336950''>are
  around</span> <span m=''1339680''>a</span> <span m=''1339970''>single</span> <span
  m=''1340360''>vertex.</span> </p><p><span m=''1345550''>So</span> <span m=''1345760''>something</span>
  <span m=''1346190''>like</span> <span m=''1346440''>this</span> <span m=''1346720''>example,</span>
  <span m=''1347910''>which</span> <span m=''1348300''>we</span> <span m=''1348420''>saw</span>
  <span m=''1348950''>where</span> <span m=''1349360''>there</span> <span m=''1349590''>is</span>
  <span m=''1349690''>a</span> <span m=''1349780''>straight</span> <span m=''1350080''>skeleton</span>
  <span m=''1350435''>edge</span> <span m=''1350790''>here,</span> <span m=''1351660''>here,</span>
  <span m=''1352400''>and</span> <span m=''1352630''>then</span> <span m=''1353360''>this</span>
  <span m=''1353600''>guy--</span> <span m=''1355570''>I</span> <span m=''1355730''>guess</span>
  <span m=''1355880''>I should draw the</span> <span m=''1356230''>skeleton</span>
  <span m=''1356680''>edges.</span> <span m=''1359040''>It''s</span> <span m=''1359150''>a</span>
  <span m=''1359190''>good</span> <span m=''1359350''>test</span> <span m=''1359620''>of</span>
  <span m=''1359690''>how</span> <span m=''1359860''>accurate</span> <span m=''1360180''>I</span>
  <span m=''1360260''>drew</span> <span m=''1360490''>it,</span> <span m=''1361120''>because</span>
  <span m=''1361490''>I</span> <span m=''1361580''>know</span> <span m=''1362250''>if</span>
  <span m=''1362430''>this</span> <span m=''1362580''>is</span> <span m=''1362700''>perpendicular,</span>
  <span m=''1363290''>this</span> <span m=''1363500''>is</span> <span m=''1363600''>perpendicular,</span>
  <span m=''1365030''>and</span> <span m=''1366170''>this</span> <span m=''1366340''>is</span>
  <span m=''1366450''>perpendicular,</span> <span m=''1367060''>this</span> <span
  m=''1367410''>will</span> <span m=''1367620''>always</span> <span m=''1367770''>come</span>
  <span m=''1368000''>back</span> <span m=''1368370''>to</span> <span m=''1368630''>its</span>
  <span m=''1368750''>starting</span> <span m=''1369080''>point.</span> <span m=''1369850''>It''s
  just</span> <span m=''1370290''>property</span> <span m=''1370660''>of</span> <span
  m=''1370750''>reflections.</span> <span m=''1371340''>Basically,</span> <span m=''1371670''>because</span>
  <span m=''1372010''>we</span> <span m=''1372120''>satisfy</span> <span m=''1372550''>Kawasaki</span>
  <span m=''1373170''>here,</span> <span m=''1373800''>this</span> <span m=''1373970''>must</span>
  <span m=''1374220''>be</span> <span m=''1374330''>true</span> <span m=''1376820''>because</span>
  <span m=''1377010''>these</span> <span m=''1377190''>are</span> <span m=''1377260''>bisectors</span>
  <span m=''1378100''>of</span> <span m=''1378370''>these</span> <span m=''1378590''>guys.</span>
  </p><p><span m=''1379690''>So</span> <span m=''1379870''>this</span> <span m=''1380120''>has</span>
  <span m=''1380470''>to</span> <span m=''1380560''>happen.</span> <span m=''1381320''>The</span>
  <span m=''1381430''>claim</span> <span m=''1381690''>is,</span> <span m=''1382190''>that''s</span>
  <span m=''1382490''>the</span> <span m=''1382600''>only</span> <span m=''1382860''>situation</span>
  <span m=''1383160''>it</span> <span m=''1383460''>happens.</span> <span m=''1384460''>And</span>
  <span m=''1384700''>if</span> <span m=''1384830''>this</span> <span m=''1385000''>is</span>
  <span m=''1385130''>all</span> <span m=''1385280''>that</span> <span m=''1385380''>happens,</span>
  <span m=''1385760''>you</span> <span m=''1385870''>can</span> <span m=''1386000''>prove</span>
  <span m=''1386250''>there''s</span> <span m=''1386410''>no</span> <span m=''1386530''>density,</span>
  <span m=''1387010''>and in</span> <span m=''1387160''>fact,</span> <span m=''1387480''>it</span>
  <span m=''1387630''>folds</span> <span m=''1387880''>flat.</span> <span m=''1388650''>So</span>
  <span m=''1388800''>this</span> <span m=''1388980''>is</span> <span m=''1389080''>the</span>
  <span m=''1389180''>good</span> <span m=''1389350''>case.</span> <span m=''1390420''>Unfortunately,</span>
  <span m=''1391000''>when</span> <span m=''1391150''>we</span> <span m=''1391250''>make</span>
  <span m=''1391450''>real</span> <span m=''1391630''>examples,</span> <span m=''1392050''>we</span>
  <span m=''1392180''>like</span> <span m=''1392460''>degeneracies</span> <span m=''1393260''>because</span>
  <span m=''1393620''>they</span> <span m=''1393730''>reduce</span> <span m=''1394060''>the</span>
  <span m=''1394130''>number</span> <span m=''1394380''>of</span> <span m=''1394450''>folds.</span>
  <span m=''1394990''>So</span> <span m=''1395200''>the</span> <span m=''1395330''>theory</span>
  <span m=''1395630''>says,</span> <span m=''1396430''>avoid</span> <span m=''1396770''>degeneracies</span>
  <span m=''1397410''>Let''s</span> <span m=''1398010''>perturb</span> <span m=''1398360''>things</span>
  <span m=''1398520''>slightly,</span> <span m=''1399250''>then</span> <span m=''1399370''>it''s</span>
  <span m=''1399500''>guaranteed</span> <span m=''1399920''>to</span> <span m=''1399980''>fold.</span>
  <span m=''1401960''>But</span> <span m=''1402170''>in</span> <span m=''1402290''>practice,</span>
  <span m=''1402700''>you</span> <span m=''1402820''>want</span> <span m=''1402950''>to</span>
  <span m=''1402990''>add</span> <span m=''1403190''>degeneracies,</span> <span m=''1403790''>just</span>
  <span m=''1404200''>carefully</span> <span m=''1405100''>so</span> <span m=''1405330''>that</span>
  <span m=''1405900''>you</span> <span m=''1406010''>don''t</span> <span m=''1406240''>get</span>
  <span m=''1406490''>dense</span> <span m=''1406720''>behavior</span> <span m=''1407150''>like</span>
  <span m=''1407340''>the</span> <span m=''1407430''>weird</span> <span m=''1407650''>example</span>
  <span m=''1408610''>I</span> <span m=''1408690''>showed</span> <span m=''1408960''>you.</span>
  </p><p><span m=''1411350''>So</span> <span m=''1411530''>that''s</span> <span m=''1412260''>clarification</span>
  <span m=''1412990''>why</span> <span m=''1417080''>we</span> <span m=''1417240''>think</span>
  <span m=''1417500''>this</span> <span m=''1417800''>does</span> <span m=''1417960''>not</span>
  <span m=''1418150''>happen.</span> <span m=''1420080''>Or, sorry,</span> <span m=''1420330''>why</span>
  <span m=''1420560''>we</span> <span m=''1420700''>think</span> <span m=''1420950''>with</span>
  <span m=''1421100''>probability</span> <span m=''1421550''>1</span> <span m=''1421820''>things</span>
  <span m=''1422060''>are</span> <span m=''1422130''>good.</span> <span m=''1423620''>But</span>
  <span m=''1423860''>sadly</span> <span m=''1424140''>we</span> <span m=''1424240''>can''t</span>
  <span m=''1424440''>prove</span> <span m=''1424600''>this.</span> <span m=''1424760''>Maybe</span>
  <span m=''1424950''>we''ll work</span> <span m=''1425250''>on</span> <span m=''1425380''>it</span>
  <span m=''1425420''>in the open</span> <span m=''1425610''>problem</span> <span
  m=''1426020''>session.</span> <span m=''1426340''>I</span> <span m=''1426390''>think</span>
  <span m=''1426600''>it''s</span> <span m=''1427320''>tractable,</span> <span m=''1427675''>I</span>
  <span m=''1428030''>just</span> <span m=''1428200''>haven''t</span> <span m=''1428400''>worked</span>
  <span m=''1428620''>on it</span> <span m=''1428820''>in a</span> <span m=''1428890''>long</span>
  <span m=''1429060''>time.</span> <span m=''1431940''>Questions?</span> <span m=''1435970''>OK.</span>
  </p><p><span m=''1436510''>So,</span> <span m=''1437620''>right.</span> <span m=''1437900''>The</span>
  <span m=''1438750''>claim</span> <span m=''1439030''>is</span> <span m=''1439140''>if</span>
  <span m=''1439270''>you</span> <span m=''1439390''>perturb</span> <span m=''1440720''>this</span>
  <span m=''1440970''>example,</span> <span m=''1441780''>everybody</span> <span m=''1442290''>will</span>
  <span m=''1442450''>escape</span> <span m=''1442850''>out</span> <span m=''1443030''>to</span>
  <span m=''1443120''>infinity</span> <span m=''1443560''>like</span> <span m=''1443760''>in</span>
  <span m=''1443860''>the</span> <span m=''1443970''>spiral.</span> <span m=''1446150''>OK.</span>
  <span m=''1446340''>So</span> <span m=''1446510''>I</span> <span m=''1446570''>think</span>
  <span m=''1446830''>this</span> <span m=''1447230''>is</span> <span m=''1447630''>the
  end</span> <span m=''1447890''>of</span> <span m=''1448010''>the</span> <span m=''1448140''>skeleton</span>
  <span m=''1448850''>method,</span> <span m=''1450050''>but</span> <span m=''1450220''>before</span>
  <span m=''1450550''>we</span> <span m=''1451050''>go</span> <span m=''1451250''>on,</span>
  <span m=''1451460''>I</span> <span m=''1451500''>want</span> <span m=''1451690''>to</span>
  <span m=''1451740''>show</span> <span m=''1452170''>some</span> <span m=''1452480''>examples.</span>
  <span m=''1453050''>So</span> <span m=''1454110''>problem</span> <span m=''1454420''>set--</span>
  <span m=''1455740''>we have</span> <span m=''1456110''>up</span> <span m=''1456270''>to</span>
  <span m=''1456390''>four</span> <span m=''1457180''>[INAUDIBLE]</span> <span m=''1457620''>later</span>
  <span m=''1457880''>today.</span> <span m=''1458540''>One</span> <span m=''1458680''>of</span>
  <span m=''1458740''>the</span> <span m=''1458830''>questions</span> <span m=''1459180''>is</span>
  <span m=''1459360''>design</span> <span m=''1459670''>your</span> <span m=''1460400''>own</span>
  <span m=''1460600''>folding</span> <span m=''1460950''>cut,</span> <span m=''1461200''>and</span>
  <span m=''1461390''>draw</span> <span m=''1461710''>it.</span> <span m=''1463060''>So</span>
  <span m=''1463590''>you</span> <span m=''1463760''>probably</span> <span m=''1464080''>want</span>
  <span m=''1464230''>to</span> <span m=''1464300''>draw</span> <span m=''1464540''>it</span>
  <span m=''1464610''>into</span> <span m=''1464860''>a</span> <span m=''1464880''>program</span>
  <span m=''1465190''>like</span> <span m=''1465370''>Inkscape</span> <span m=''1465910''>or</span>
  <span m=''1466060''>Adobe</span> <span m=''1466330''>Illustrator.</span> <span m=''1467630''>It</span>
  <span m=''1467820''>has</span> <span m=''1468070''>good</span> <span m=''1468840''>snapping,</span>
  <span m=''1469760''>so</span> <span m=''1469980''>you can find</span> <span m=''1470330''>intersections</span>
  <span m=''1470900''>and</span> <span m=''1471000''>things</span> <span m=''1471190''>like</span>
  <span m=''1471340''>that,</span> <span m=''1471660''>and compute</span> <span m=''1472450''>angular</span>
  <span m=''1472790''>bisectors</span> <span m=''1473430''>as</span> <span m=''1473650''>in</span>
  <span m=''1474350''>ruler</span> <span m=''1474670''>and compass.</span> </p><p><span
  m=''1477240''>And</span> <span m=''1477560''>these</span> <span m=''1477740''>are</span>
  <span m=''1477830''>some</span> <span m=''1478020''>examples</span> <span m=''1478500''>from</span>
  <span m=''1478680''>2010,</span> <span m=''1479450''>same</span> <span m=''1479770''>question.</span>
  <span m=''1480890''>There</span> <span m=''1481050''>are</span> <span m=''1481100''>lots</span>
  <span m=''1481390''>of</span> <span m=''1481590''>them, but</span> <span m=''1481760''>I</span>
  <span m=''1482040''>chose</span> <span m=''1482360''>three</span> <span m=''1483000''>that
  are</span> <span m=''1483150''>particularly</span> <span m=''1483690''>cool.</span>
  <span m=''1484000''>This</span> <span m=''1484140''>one</span> <span m=''1484250''>has</span>
  <span m=''1484420''>a</span> <span m=''1484470''>line</span> <span m=''1484650''>of</span>
  <span m=''1484710''>symmetry,</span> <span m=''1485005''>you</span> <span m=''1485300''>get</span>
  <span m=''1485980''>a</span> <span m=''1486370''>fish</span> <span m=''1486920''>bone</span>
  <span m=''1488460''>by</span> <span m=''1488775''>[? Ji, ?]</span> <span m=''1489090''>who''s</span>
  <span m=''1489490''>a</span> <span m=''1489990''>Ph.D.</span> <span m=''1490320''>student</span>
  <span m=''1490640''>in</span> <span m=''1490770''>the</span> <span m=''1490830''>media</span>
  <span m=''1491070''>lab.</span> <span m=''1492530''>This</span> <span m=''1493030''>is</span>
  <span m=''1493570''>by</span> <span m=''1494200''>[? Sarah Eisenstadt ?],</span>
  <span m=''1495150''>who''s</span> <span m=''1495790''>a</span> <span m=''1495930''>Ph.D.</span>
  <span m=''1496270''>student</span> <span m=''1496610''>in</span> <span m=''1496900''>CSAIL</span>
  <span m=''1498380''>working</span> <span m=''1498490''>on</span> <span m=''1498720''>folding</span>
  <span m=''1499060''>things.</span> <span m=''1499750''>Witch''s</span> <span m=''1500070''>hat</span>
  <span m=''1500830''>is</span> <span m=''1500940''>pretty</span> <span m=''1501160''>cool,</span>
  <span m=''1501960''>pretty</span> <span m=''1502220''>fairly</span> <span m=''1502560''>simple.</span>
  <span m=''1503470''>You</span> <span m=''1503600''>have</span> <span m=''1503740''>to</span>
  <span m=''1503850''>fold</span> <span m=''1504120''>your</span> <span m=''1504230''>examples.</span>
  <span m=''1504930''>It</span> <span m=''1505040''>can''t</span> <span m=''1505270''>be</span>
  <span m=''1505430''>too</span> <span m=''1505600''>complicated.</span> <span m=''1506870''>And</span>
  <span m=''1507060''>then</span> <span m=''1507640''>Jason</span> <span m=''1507940''>[?
  Ku ?],</span> <span m=''1508410''>who</span> <span m=''1508610''>we saw the</span>
  <span m=''1508710''>guest</span> <span m=''1508950''>lecture</span> <span m=''1509210''>by</span>
  <span m=''1510260''>wasn''t</span> <span m=''1511260''>sufficiently</span> <span
  m=''1511710''>impressed</span> <span m=''1512050''>by</span> <span m=''1512180''>my</span>
  <span m=''1512350''>jack o''</span> <span m=''1512720''>lantern,</span> <span m=''1513190''>so</span>
  <span m=''1513250''>he made a</span> <span m=''1513720''>really</span> <span m=''1513950''>complicated</span>
  <span m=''1514490''>one</span> <span m=''1515160''>and</span> <span m=''1515380''>folded</span>
  <span m=''1515690''>it.</span> <span m=''1517360''>So</span> <span m=''1517780''>those</span>
  <span m=''1518000''>are</span> <span m=''1518100''>some</span> <span m=''1518990''>inspiration</span>
  <span m=''1519670''>points.</span> </p><p><span m=''1521000''>And</span> <span m=''1521180''>I</span>
  <span m=''1521250''>thought</span> <span m=''1521460''>I''d</span> <span m=''1521590''>show</span>
  <span m=''1521820''>you</span> <span m=''1523170''>a</span> <span m=''1523400''>magic</span>
  <span m=''1523940''>trick</span> <span m=''1524320''>which</span> <span m=''1524560''>is</span>
  <span m=''1525610''>one</span> <span m=''1525910''>of</span> <span m=''1525990''>the</span>
  <span m=''1526270''>sources</span> <span m=''1526740''>for</span> <span m=''1526900''>inspiration</span>
  <span m=''1527530''>for</span> <span m=''1527680''>the</span> <span m=''1527810''>fold</span>
  <span m=''1528130''>and one</span> <span m=''1528330''>cut</span> <span m=''1528560''>problem.</span>
  <span m=''1531720''>So,</span> <span m=''1532786''>a piece of</span> <span m=''1533360''>paper.</span>
  <span m=''1534600''>So</span> <span m=''1534670''>this</span> <span m=''1534880''>is</span>
  <span m=''1534950''>a</span> <span m=''1534980''>magic</span> <span m=''1535270''>trick</span>
  <span m=''1535440''>of</span> <span m=''1535580''>unknown</span> <span m=''1536010''>origin.</span>
  <span m=''1536510''>It was</span> <span m=''1536710''>described</span> <span m=''1537090''>by</span>
  <span m=''1537180''>Martin</span> <span m=''1537500''>Gardner,</span> <span m=''1539540''>I</span>
  <span m=''1539560''>think,</span> <span m=''1539730''>probably</span> <span m=''1540310''>in</span>
  <span m=''1540470''>the</span> <span m=''1541210''>''60s,</span> <span m=''1542220''>and</span>
  <span m=''1542300''>then</span> <span m=''1542830''>the</span> <span m=''1542940''>book</span>
  <span m=''1543140''>appeared</span> <span m=''1543410''>in</span> <span m=''1543460''>the</span>
  <span m=''1543560''>''90s.</span> <span m=''1544540''>And</span> <span m=''1544760''>it''s</span>
  <span m=''1544890''>a</span> <span m=''1544950''>story</span> <span m=''1545460''>of</span>
  <span m=''1546010''>two</span> <span m=''1546170''>politicians,</span> <span m=''1547450''>and</span>
  <span m=''1547770''>let''s</span> <span m=''1547930''>just</span> <span m=''1548550''>be</span>
  <span m=''1548850''>generic.</span> <span m=''1549670''>Let''s</span> <span m=''1550100''>say</span>
  <span m=''1550430''>one</span> <span m=''1550620''>politician</span> <span m=''1551190''>was</span>
  <span m=''1551360''>very</span> <span m=''1551580''>much</span> <span m=''1551940''>liked</span>
  <span m=''1552260''>by</span> <span m=''1552380''>the</span> <span m=''1552490''>people,</span>
  <span m=''1552820''>and</span> <span m=''1552890''>the</span> <span m=''1553010''>other</span>
  <span m=''1553170''>politician</span> <span m=''1553770''>was</span> <span m=''1554070''>disliked</span>
  <span m=''1554510''>by</span> <span m=''1554630''>the</span> <span m=''1554730''>people.</span>
  <span m=''1555520''>Imagine</span> <span m=''1555900''>a</span> <span m=''1555970''>simple</span>
  <span m=''1556290''>world</span> <span m=''1556620''>where</span> <span m=''1556760''>it</span>
  <span m=''1556810''>was</span> <span m=''1556920''>so</span> <span m=''1557120''>simple.</span>
  </p><p><span m=''1559470''>And</span> <span m=''1560490''>by</span> <span m=''1560860''>a</span>
  <span m=''1560920''>freak</span> <span m=''1561220''>accident,</span> <span m=''1561720''>both</span>
  <span m=''1561960''>politicians</span> <span m=''1562530''>die</span> <span m=''1562790''>at</span>
  <span m=''1563010''>the</span> <span m=''1563080''>same</span> <span m=''1563420''>time.</span>
  <span m=''1564080''>And</span> <span m=''1564660''>they</span> <span m=''1564770''>both</span>
  <span m=''1565010''>happen</span> <span m=''1565240''>to</span> <span m=''1565290''>be</span>
  <span m=''1565410''>Christians,</span> <span m=''1565920''>so</span> <span m=''1566110''>they</span>
  <span m=''1566250''>go</span> <span m=''1566450''>to</span> <span m=''1566610''>the</span>
  <span m=''1566750''>gates</span> <span m=''1567030''>of</span> <span m=''1567120''>Heaven.</span>
  <span m=''1567570''>That''s</span> <span m=''1568020''>how the</span> <span m=''1568080''>story</span>
  <span m=''1568350''>goes.</span> <span m=''1569110''>And</span> <span m=''1569790''>arrive</span>
  <span m=''1569950''>at</span> <span m=''1570210''>the</span> <span m=''1570370''>gates</span>
  <span m=''1570440''>of</span> <span m=''1570670''>Heaven. I guess</span> <span m=''1570820''>Saint</span>
  <span m=''1571160''>Peter''s</span> <span m=''1571660''>the</span> <span m=''1571770''>keeper</span>
  <span m=''1572150''>of</span> <span m=''1572210''>the</span> <span m=''1572280''>gates,</span>
  <span m=''1572750''>and</span> <span m=''1573440''>Saint</span> <span m=''1573660''>Peter</span>
  <span m=''1573850''>says,</span> <span m=''1574040''>well</span> <span m=''1574320''>not</span>
  <span m=''1574560''>just</span> <span m=''1574770''>anyone</span> <span m=''1575130''>can</span>
  <span m=''1575280''>get</span> <span m=''1575440''>into</span> <span m=''1575650''>heaven.</span>
  <span m=''1576260''>You</span> <span m=''1576440''>have</span> <span m=''1576660''>to</span>
  <span m=''1576750''>have</span> <span m=''1577090''>a</span> <span m=''1577230''>ticket.</span>
  <span m=''1578320''>And</span> <span m=''1578790''>the</span> <span m=''1578880''>good</span>
  <span m=''1579030''>politician</span> <span m=''1579580''>being</span> <span m=''1579770''>liked</span>
  <span m=''1580010''>by</span> <span m=''1580120''>the</span> <span m=''1580210''>people</span>
  <span m=''1580470''>has</span> <span m=''1580680''>a</span> <span m=''1580750''>ticket,</span>
  <span m=''1581100''>which</span> <span m=''1581300''>he</span> <span m=''1581410''>folds</span>
  <span m=''1581710''>flat.</span> <span m=''1582250''>And</span> <span m=''1582600''>the
  bad</span> <span m=''1582790''>politician</span> <span m=''1583260''>has</span>
  <span m=''1583570''>no</span> <span m=''1583720''>ticket.</span> </p><p><span m=''1584820''>So</span>
  <span m=''1585020''>the bad</span> <span m=''1585280''>politician</span> <span m=''1585810''>says,</span>
  <span m=''1585950''>well</span> <span m=''1586240''>you know, we''ve</span> <span
  m=''1586820''>had</span> <span m=''1587000''>our</span> <span m=''1587080''>disagreements,</span>
  <span m=''1587750''>but</span> <span m=''1587920''>maybe</span> <span m=''1588160''>you</span>
  <span m=''1588310''>could</span> <span m=''1588500''>put</span> <span m=''1588650''>in</span>
  <span m=''1588770''>a</span> <span m=''1588820''>good</span> <span m=''1588960''>word</span>
  <span m=''1589240''>to</span> <span m=''1589310''>Saint</span> <span m=''1589540''>Peter</span>
  <span m=''1589990''>or</span> <span m=''1590050''>do</span> <span m=''1590190''>something</span>
  <span m=''1590730''>to</span> <span m=''1590880''>help</span> <span m=''1591060''>me</span>
  <span m=''1591210''>out.</span> <span m=''1591440''>I</span> <span m=''1591630''>hear</span>
  <span m=''1591840''>Heaven''s</span> <span m=''1592150''>a</span> <span m=''1592200''>nice</span>
  <span m=''1592420''>place.</span> <span m=''1593320''>Maybe</span> <span m=''1593590''>we</span>
  <span m=''1593750''>could</span> <span m=''1593890''>go there</span> <span m=''1594150''>together,</span>
  <span m=''1595320''>resolve</span> <span m=''1595640''>our</span> <span m=''1595730''>differences,</span>
  <span m=''1596210''>whatever.</span> <span m=''1597270''>So</span> <span m=''1597590''>the</span>
  <span m=''1598250''>good</span> <span m=''1598450''>politician,</span> <span m=''1599000''>having</span>
  <span m=''1599370''>a</span> <span m=''1599400''>ticket</span> <span m=''1599900''>and</span>
  <span m=''1600220''>a</span> <span m=''1600270''>pair</span> <span m=''1600430''>of</span>
  <span m=''1600490''>scissors</span> <span m=''1600860''>like</span> <span m=''1601050''>any</span>
  <span m=''1601240''>respecting</span> <span m=''1601670''>politician,</span> <span
  m=''1602670''>takes</span> <span m=''1603020''>his</span> <span m=''1603990''>ticket</span>
  <span m=''1604550''>and</span> <span m=''1604820''>makes</span> <span m=''1605030''>one</span>
  <span m=''1605340''>complete</span> <span m=''1605790''>straight</span> <span m=''1606130''>cut.</span>
  <span m=''1606790''>And</span> <span m=''1607110''>it''s</span> <span m=''1607300''>going</span>
  <span m=''1607410''>to</span> <span m=''1607460''>get</span> <span m=''1607570''>a</span>
  <span m=''1607630''>lot</span> <span m=''1607810''>of</span> <span m=''1607880''>pieces,</span>
  <span m=''1608440''>so</span> <span m=''1608510''>I''ve</span> <span m=''1608650''>got</span>
  <span m=''1608720''>to be,</span> <span m=''1609445''>hold</span> <span m=''1609890''>this</span>
  <span m=''1610290''>carefully.</span> <span m=''1613150''>So,</span> <span m=''1613985''>put</span>
  <span m=''1614330''>that</span> <span m=''1614750''>down.</span> <span m=''1615230''>And</span>
  <span m=''1616110''>he</span> <span m=''1616340''>hands</span> <span m=''1616740''>all</span>
  <span m=''1616880''>these</span> <span m=''1617060''>pieces</span> <span m=''1617940''>to</span>
  <span m=''1618210''>the</span> <span m=''1619420''>bad</span> <span m=''1619690''>politician,</span>
  <span m=''1620010''>says</span> <span m=''1620330''>there</span> <span m=''1620400''>you
  go.</span> <span m=''1621120''>The</span> <span m=''1621310''>bad politician</span>
  <span m=''1621720''>has</span> <span m=''1621890''>no</span> <span m=''1622050''>idea</span>
  <span m=''1622390''>what</span> <span m=''1622560''>they''re for,</span> <span m=''1623340''>so</span>
  <span m=''1623550''>he</span> <span m=''1623710''>hands</span> <span m=''1623910''>them</span>
  <span m=''1624010''>to</span> <span m=''1624090''>Saint</span> <span m=''1624290''>Peter.</span>
  </p><p><span m=''1624590''>Saint</span> <span m=''1624800''>Peter</span> <span m=''1627580''>starts</span>
  <span m=''1627690''>unfolding</span> <span m=''1628150''>the</span> <span m=''1628250''>pieces,</span>
  <span m=''1628890''>says,</span> <span m=''1629240''>I</span> <span m=''1629360''>wonder</span>
  <span m=''1629620''>what</span> <span m=''1629750''>shapes</span> <span m=''1630040''>I</span>
  <span m=''1630100''>get.</span> <span m=''1630380''>I</span> <span m=''1630450''>hear</span>
  <span m=''1630600''>there''s</span> <span m=''1630760''>a</span> <span m=''1630830''>cool</span>
  <span m=''1631260''>problem</span> <span m=''1631570''>about</span> <span m=''1631860''>this.</span>
  <span m=''1633240''>So</span> <span m=''1634220''>it''s</span> <span m=''1634390''>a</span>
  <span m=''1634470''>little</span> <span m=''1634820''>hard</span> <span m=''1635050''>to</span>
  <span m=''1635140''>do</span> <span m=''1635300''>without</span> <span m=''1635580''>a</span>
  <span m=''1635670''>table.</span> <span m=''1636430''>So</span> <span m=''1636540''>I''m</span>
  <span m=''1636640''>going</span> <span m=''1636740''>to</span> <span m=''1636790''>have</span>
  <span m=''1636970''>to</span> <span m=''1637070''>use</span> <span m=''1637390''>the</span>
  <span m=''1638040''>board.</span> <span m=''1639200''>First,</span> <span m=''1639550''>we</span>
  <span m=''1639640''>get</span> <span m=''1640160''>the</span> <span m=''1640390''>letter</span>
  <span m=''1640700''>H.</span> <span m=''1642360''>Then</span> <span m=''1642680''>we</span>
  <span m=''1642850''>get--</span> <span m=''1654800''>put</span> <span m=''1655000''>these</span>
  <span m=''1655210''>down</span> <span m=''1655460''>here.</span> <span m=''1656670''>Then</span>
  <span m=''1656870''>we</span> <span m=''1657000''>get</span> <span m=''1657240''>the</span>
  <span m=''1660470''>letter</span> <span m=''1661820''>E.</span> <span m=''1664870''>OK?</span>
  <span m=''1666010''>Then</span> <span m=''1666240''>we</span> <span m=''1666380''>get</span>
  <span m=''1667480''>letter</span> <span m=''1667690''>L,</span> <span m=''1668540''>and</span>
  <span m=''1668860''>the</span> <span m=''1668930''>letter</span> <span m=''1669220''>L.</span>
  <span m=''1669610''>And</span> <span m=''1669750''>if</span> <span m=''1669860''>it
  was</span> <span m=''1670020''>on</span> <span m=''1670120''>a</span> <span m=''1670180''>table,</span>
  <span m=''1670550''>I''d</span> <span m=''1670640''>arrange</span> <span m=''1671030''>it,</span>
  <span m=''1671460''>and</span> <span m=''1672040''>clearly</span> <span m=''1672330''>Saint</span>
  <span m=''1672520''>Peter''s</span> <span m=''1672840''>not</span> <span m=''1673020''>happy,</span>
  <span m=''1673420''>and</span> <span m=''1673550''>the</span> <span m=''1673630''>bad</span>
  <span m=''1673830''>politician</span> <span m=''1674280''>gets</span> <span m=''1674460''>sent</span>
  <span m=''1674750''>straight</span> <span m=''1675040''>to</span> <span m=''1675090''>hell.</span>
  <span m=''1675730''>The</span> <span m=''1675830''>good</span> <span m=''1675980''>politician</span>
  <span m=''1676890''>hung</span> <span m=''1677180''>on to</span> <span m=''1677500''>one</span>
  <span m=''1677720''>piece</span> <span m=''1678060''>cleverly,</span> <span m=''1679190''>and</span>
  <span m=''1680730''>his</span> <span m=''1680990''>ticket</span> <span m=''1681300''>is</span>
  <span m=''1681430''>still</span> <span m=''1681730''>more</span> <span m=''1681940''>or
  less intact,</span> <span m=''1682733''>and</span> <span m=''1683196''>he</span>
  <span m=''1683659''>gets into</span> <span m=''1684122''>heaven.</span> </p><p><span
  m=''1685050''>That''s</span> <span m=''1685320''>the</span> <span m=''1685630''>magic</span>
  <span m=''1685990''>trick.</span> <span m=''1687590''>It''s</span> <span m=''1687750''>very</span>
  <span m=''1687950''>simple</span> <span m=''1688660''>folding.</span> <span m=''1690520''>I''ve</span>
  <span m=''1690780''>known</span> <span m=''1690960''>this,</span> <span m=''1691490''>memorized</span>
  <span m=''1692030''>this</span> <span m=''1692210''>even,</span> <span m=''1692420''>for</span>
  <span m=''1692570''>years.</span> <span m=''1693990''>And</span> <span m=''1694200''>you</span>
  <span m=''1694310''>get</span> <span m=''1694540''>exactly</span> <span m=''1694950''>those</span>
  <span m=''1695170''>pieces.</span> <span m=''1695610''>So</span> <span m=''1695670''>pretty</span>
  <span m=''1695920''>cool.</span> <span m=''1697200''>Of</span> <span m=''1697360''>course,</span>
  <span m=''1698390''>from</span> <span m=''1698670''>a</span> <span m=''1698770''>mathematical</span>
  <span m=''1699420''>standpoint,</span> <span m=''1700540''>it''s</span> <span m=''1700770''>a</span>
  <span m=''1700790''>little</span> <span m=''1701000''>unsatisfying.</span> <span
  m=''1701370''>Because,</span> <span m=''1701930''>come</span> <span m=''1702120''>on,</span>
  <span m=''1702270''>use</span> <span m=''1702560''>three</span> <span m=''1702860''>pieces</span>
  <span m=''1703270''>for</span> <span m=''1703360''>the</span> <span m=''1703530''>H,</span>
  <span m=''1704250''>three</span> <span m=''1704610''>pieces for</span> <span m=''1704760''>the</span>
  <span m=''1705075''>E.</span> <span m=''1705730''>Surely</span> <span m=''1706100''>you</span>
  <span m=''1706220''>could</span> <span m=''1706360''>do</span> <span m=''1706450''>better.</span>
  <span m=''1707170''>And</span> <span m=''1707540''>from</span> <span m=''1707700''>a</span>
  <span m=''1707770''>rectangle,</span> <span m=''1708240''>you</span> <span m=''1708410''>can</span>
  <span m=''1708680''>kind</span> <span m=''1709100''>of</span> <span m=''1709310''>do</span>
  <span m=''1709440''>better.</span> <span m=''1710510''>It''s</span> <span m=''1711240''>a</span>
  <span m=''1711310''>little</span> <span m=''1711590''>awkward</span> <span m=''1712070''>because</span>
  <span m=''1712880''>the</span> <span m=''1713520''>pieces</span> <span m=''1713860''>are</span>
  <span m=''1713960''>not</span> <span m=''1714190''>all</span> <span m=''1714410''>the</span>
  <span m=''1714510''>same</span> <span m=''1714780''>size,</span> <span m=''1715150''>but</span>
  <span m=''1715280''>is</span> <span m=''1715440''>one</span> <span m=''1715750''>scissor</span>
  <span m=''1716080''>cut</span> <span m=''1716720''>because</span> <span m=''1716980''>all</span>
  <span m=''1717130''>the</span> <span m=''1717200''>vertices</span> <span m=''1717630''>are</span>
  <span m=''1717740''>even</span> <span m=''1717970''>degree.</span> </p><p><span
  m=''1718620''>You</span> <span m=''1718790''>cut</span> <span m=''1719050''>it,</span>
  <span m=''1719740''>and</span> <span m=''1720110''>you</span> <span m=''1720250''>get</span>
  <span m=''1720790''>all</span> <span m=''1721180''>these</span> <span m=''1721440''>pieces,</span>
  <span m=''1723500''>which</span> <span m=''1723850''>if</span> <span m=''1724040''>I</span>
  <span m=''1724170''>were</span> <span m=''1724710''>more</span> <span m=''1724940''>practiced</span>
  <span m=''1725460''>at</span> <span m=''1725580''>this,</span> <span m=''1726310''>I</span>
  <span m=''1726400''>could</span> <span m=''1726680''>immediately</span> <span m=''1727220''>pick</span>
  <span m=''1727450''>out</span> <span m=''1727580''>which</span> <span m=''1727740''>one''s</span>
  <span m=''1728010''>the</span> <span m=''1728230''>H.</span> <span m=''1731880''>OK,</span>
  <span m=''1732110''>I''ll</span> <span m=''1732240''>just</span> <span m=''1732410''>do</span>
  <span m=''1732470''>them</span> <span m=''1732600''>out</span> <span m=''1732710''>of</span>
  <span m=''1732790''>order.</span> <span m=''1733490''>Here</span> <span m=''1733850''>is</span>
  <span m=''1734110''>the</span> <span m=''1734210''>cross.</span> <span m=''1736270''>Well,</span>
  <span m=''1736430''>kind</span> <span m=''1736720''>of</span> <span m=''1736840''>a
  cross.</span> <span m=''1737340''>Not</span> <span m=''1737480''>quite</span> <span
  m=''1737780''>perfect</span> <span m=''1738130''>proportions,</span> <span m=''1738670''>but</span>
  <span m=''1738830''>good</span> <span m=''1738960''>enough.</span> <span m=''1741910''>This</span>
  <span m=''1742110''>is</span> <span m=''1742310''>the</span> <span m=''1742430''>letter</span>
  <span m=''1742750''>E.</span> <span m=''1743090''>This</span> <span m=''1743290''>one''s</span>
  <span m=''1743460''>actually</span> <span m=''1743720''>more</span> <span m=''1743910''>impressive</span>
  <span m=''1744280''>when</span> <span m=''1744380''>you</span> <span m=''1744500''>don''t</span>
  <span m=''1744750''>have</span> <span m=''1744930''>a</span> <span m=''1745000''>table,</span>
  <span m=''1745350''>because</span> <span m=''1745520''>you</span> <span m=''1745630''>can''t</span>
  <span m=''1745910''>tell</span> <span m=''1746110''>that</span> <span m=''1746220''>they''re</span>
  <span m=''1746380''>all</span> <span m=''1746550''>different</span> <span m=''1746870''>sizes.</span>
  <span m=''1748320''>The</span> <span m=''1748340''>letter</span> <span m=''1748580''>E.</span>
  <span m=''1749390''>We''ve</span> <span m=''1749670''>got</span> <span m=''1750020''>the</span>
  <span m=''1751480''>letter--</span> <span m=''1752310''>these</span> <span m=''1752650''>look</span>
  <span m=''1752820''>like</span> <span m=''1753010''>L''s.</span> <span m=''1754950''>And</span>
  <span m=''1755050''>they''re</span> <span m=''1755130''>small</span> <span m=''1755500''>L''s,</span>
  <span m=''1755900''>but</span> <span m=''1756110''>there</span> <span m=''1756310''>you
  go.</span> <span m=''1756610''>They''re</span> <span m=''1757550''>different</span>
  <span m=''1757800''>orientations.</span> <span m=''1758560''>And</span> <span m=''1758840''>then</span>
  <span m=''1759080''>I''ve</span> <span m=''1759180''>got</span> <span m=''1759370''>the</span>
  <span m=''1759450''>letter</span> <span m=''1759670''>H.</span> <span m=''1762934''>There
  you go.</span> <span m=''1763842''>OK.</span> </p><p><span m=''1764300''>So</span>
  <span m=''1764680''>that''s</span> <span m=''1764890''>our</span> <span m=''1765360''>new</span>
  <span m=''1765510''>and</span> <span m=''1765590''>improved</span> <span m=''1765920''>version</span>
  <span m=''1766700''>using</span> <span m=''1767080''>universality</span> <span m=''1767810''>of</span>
  <span m=''1767890''>folding</span> <span m=''1768210''>cut.</span> <span m=''1769290''>So</span>
  <span m=''1769430''>it</span> <span m=''1769480''>gives</span> <span m=''1769640''>you</span>
  <span m=''1769740''>some</span> <span m=''1769960''>idea</span> <span m=''1770390''>of</span>
  <span m=''1771160''>A,</span> <span m=''1771310''>where</span> <span m=''1771470''>folding</span>
  <span m=''1771930''>cut</span> <span m=''1772110''>came</span> <span m=''1772360''>from</span>
  <span m=''1773040''>in</span> <span m=''1773660''>recent</span> <span m=''1774030''>times,</span>
  <span m=''1774390''>is</span> <span m=''1774610''>the</span> <span m=''1774940''>magic</span>
  <span m=''1775300''>community.</span> <span m=''1775570''>I</span> <span m=''1775620''>mentioned</span>
  <span m=''1775920''>Harry</span> <span m=''1776120''>Houdini</span> <span m=''1776520''>did</span>
  <span m=''1776680''>some</span> <span m=''1776850''>tricks,</span> <span m=''1777210''>and</span>
  <span m=''1777400''>Gerald</span> <span m=''1777660''>[? Low ?],</span> <span m=''1778590''>but</span>
  <span m=''1778710''>there''s</span> <span m=''1778890''>a</span> <span m=''1778940''>bunch</span>
  <span m=''1779190''>of</span> <span m=''1779240''>these</span> <span m=''1779380''>tricks</span>
  <span m=''1779640''>around,</span> <span m=''1780470''>and</span> <span m=''1781080''>kind</span>
  <span m=''1781260''>of</span> <span m=''1781330''>cool.</span> <span m=''1781760''>So</span>
  <span m=''1781840''>the</span> <span m=''1781920''>checkerboard</span> <span m=''1782440''>trick</span>
  <span m=''1783200''>and</span> <span m=''1783590''>the</span> <span m=''1784580''>previous</span>
  <span m=''1785040''>hell</span> <span m=''1785260''>trick.</span> <span m=''1787020''>So</span>
  <span m=''1787430''>those</span> <span m=''1787640''>are</span> <span m=''1787730''>some</span>
  <span m=''1787920''>examples.</span> <span m=''1788570''>Now</span> <span m=''1788890''>we</span>
  <span m=''1789030''>move</span> <span m=''1789330''>onto</span> <span m=''1790790''>the</span>
  <span m=''1790900''>disk-packing</span> <span m=''1791440''>method.</span> </p><p><span
  m=''1792840''>So</span> <span m=''1793100''>I</span> <span m=''1793170''>have</span>
  <span m=''1793340''>one</span> <span m=''1793530''>question</span> <span m=''1793900''>about</span>
  <span m=''1794220''>this,</span> <span m=''1795370''>which</span> <span m=''1795650''>is,</span>
  <span m=''1795830''>how</span> <span m=''1796210''>exactly</span> <span m=''1797510''>do</span>
  <span m=''1797610''>we</span> <span m=''1797700''>go</span> <span m=''1797850''>from</span>
  <span m=''1798090''>the</span> <span m=''1798190''>disk-packing</span> <span m=''1799160''>to--</span>
  <span m=''1800350''>yeah,</span> <span m=''1800400''>cool</span> <span m=''1800880''>proof,</span>
  <span m=''1801380''>though,</span> <span m=''1801590''>cool proof,</span> <span
  m=''1801850''>bro.</span> <span m=''1803740''>So</span> <span m=''1804480''>how</span>
  <span m=''1804690''>do</span> <span m=''1804750''>we</span> <span m=''1804860''>go</span>
  <span m=''1804980''>from</span> <span m=''1805150''>the</span> <span m=''1805440''>disk-packing</span>
  <span m=''1806050''>to</span> <span m=''1806330''>the</span> <span m=''1806560''>decomposition</span>
  <span m=''1807220''>into</span> <span m=''1807430''>triangles</span> <span m=''1807940''>and</span>
  <span m=''1808070''>quadrilaterals.</span> <span m=''1809450''>So</span> <span m=''1809870''>I
  thought</span> <span m=''1809910''>I''d</span> <span m=''1809970''>just</span> <span
  m=''1810160''>review</span> <span m=''1810580''>this</span> <span m=''1810900''>slide.</span>
  <span m=''1812040''>We</span> <span m=''1812220''>start</span> <span m=''1812520''>with</span>
  <span m=''1812690''>our</span> <span m=''1812830''>graph.</span> <span m=''1813620''>We</span>
  <span m=''1813810''>offset</span> <span m=''1814260''>it</span> <span m=''1814430''>by</span>
  <span m=''1814830''>some</span> <span m=''1815070''>tiny</span> <span m=''1815370''>epsilon.</span>
  <span m=''1816420''>That''s</span> <span m=''1816670''>to</span> <span m=''1816770''>get</span>
  <span m=''1817020''>things</span> <span m=''1817680''>off</span> <span m=''1818060''>the</span>
  <span m=''1818170''>line,</span> <span m=''1818880''>basically.</span> <span m=''1819620''>Then</span>
  <span m=''1819780''>we</span> <span m=''1819880''>do</span> <span m=''1820000''>this</span>
  <span m=''1820240''>disk-packing.</span> <span m=''1821460''>And</span> <span m=''1822010''>remember</span>
  <span m=''1822410''>roughly</span> <span m=''1822770''>how</span> <span m=''1822940''>the</span>
  <span m=''1823060''>disk-packing</span> <span m=''1823540''>works.</span> </p><p><span
  m=''1823780''>We</span> <span m=''1823910''>put</span> <span m=''1824100''>some</span>
  <span m=''1824860''>disks</span> <span m=''1825360''>at</span> <span m=''1825680''>each</span>
  <span m=''1825910''>of</span> <span m=''1825990''>the</span> <span m=''1826090''>centers.</span>
  <span m=''1827100''>Here,</span> <span m=''1827420''>it''s</span> <span m=''1827710''>a</span>
  <span m=''1827800''>little</span> <span m=''1828030''>awkward</span> <span m=''1828310''>because</span>
  <span m=''1828480''>of the</span> <span m=''1828660''>offset,</span> <span m=''1829080''>but</span>
  <span m=''1829210''>you</span> <span m=''1829320''>put</span> <span m=''1829540''>one</span>
  <span m=''1829750''>at</span> <span m=''1829840''>each</span> <span m=''1830050''>of</span>
  <span m=''1830130''>these</span> <span m=''1830360''>four</span> <span m=''1830930''>corners.</span>
  <span m=''1831350''>Also</span> <span m=''1831630''>the</span> <span m=''1831740''>corners</span>
  <span m=''1832110''>of</span> <span m=''1832150''>the</span> <span m=''1832220''>piece</span>
  <span m=''1832440''>of</span> <span m=''1832490''>paper.</span> <span m=''1832940''>Why</span>
  <span m=''1833080''>not?</span> <span m=''1834260''>Then</span> <span m=''1834520''>you</span>
  <span m=''1834680''>also</span> <span m=''1834960''>pack</span> <span m=''1835440''>small</span>
  <span m=''1835700''>enough</span> <span m=''1835910''>disks</span> <span m=''1836100''>along</span>
  <span m=''1836390''>the</span> <span m=''1836570''>edge,</span> <span m=''1837070''>so</span>
  <span m=''1837160''>that you</span> <span m=''1837320''>cover</span> <span m=''1838030''>the</span>
  <span m=''1838200''>edge</span> <span m=''1838520''>by</span> <span m=''1839090''>diameters</span>
  <span m=''1839550''>of</span> <span m=''1839660''>the</span> <span m=''1839740''>disks.</span>
  <span m=''1840760''>I</span> <span m=''1840920''>do</span> <span m=''1841060''>that</span>
  <span m=''1841350''>the</span> <span m=''1841450''>same</span> <span m=''1841740''>on</span>
  <span m=''1841970''>all</span> <span m=''1842240''>the sides.</span> <span m=''1842760''>Basically,</span>
  <span m=''1843120''>you</span> <span m=''1843210''>try</span> <span m=''1843420''>to</span>
  <span m=''1843510''>put</span> <span m=''1843680''>a</span> <span m=''1843730''>big</span>
  <span m=''1843960''>one</span> <span m=''1844140''>in,</span> <span m=''1844300''>but</span>
  <span m=''1844430''>if</span> <span m=''1844540''>that</span> <span m=''1844730''>big</span>
  <span m=''1844880''>one</span> <span m=''1845040''>intersects,</span> <span m=''1845960''>you</span>
  <span m=''1846090''>decompose</span> <span m=''1846550''>it</span> <span m=''1846630''>into</span>
  <span m=''1846830''>half.</span> <span m=''1848020''>That''s how</span> <span m=''1848200''>the</span>
  <span m=''1848280''>algorithm</span> <span m=''1848650''>works.</span> </p><p><span
  m=''1850900''>So</span> <span m=''1850970''>now</span> <span m=''1851130''>you''ve</span>
  <span m=''1851330''>covered</span> <span m=''1851770''>the</span> <span m=''1851830''>vertices</span>
  <span m=''1852240''>and</span> <span m=''1852320''>the</span> <span m=''1852430''>edges,</span>
  <span m=''1852860''>but</span> <span m=''1853020''>you</span> <span m=''1853150''>may</span>
  <span m=''1853290''>have</span> <span m=''1853580''>big</span> <span m=''1853820''>gaps</span>
  <span m=''1854570''>like</span> <span m=''1854850''>this,</span> <span m=''1856150''>too</span>
  <span m=''1856320''>many</span> <span m=''1857700''>sides</span> <span m=''1858040''>on</span>
  <span m=''1858130''>this</span> <span m=''1858280''>gap.</span> <span m=''1858700''>And</span>
  <span m=''1858900''>so</span> <span m=''1859040''>then</span> <span m=''1859190''>you</span>
  <span m=''1859300''>just</span> <span m=''1859520''>greedily</span> <span m=''1859880''>put</span>
  <span m=''1860190''>the</span> <span m=''1860300''>largest</span> <span m=''1860810''>disk</span>
  <span m=''1861050''>you</span> <span m=''1861160''>can</span> <span m=''1861480''>in</span>
  <span m=''1861560''>those</span> <span m=''1861760''>gaps</span> <span m=''1862130''>until</span>
  <span m=''1862860''>all</span> <span m=''1863080''>you''re</span> <span m=''1863180''>left</span>
  <span m=''1863430''>with</span> <span m=''1863700''>in</span> <span m=''1863850''>these</span>
  <span m=''1863990''>yellow</span> <span m=''1864280''>gaps</span> <span m=''1864640''>are</span>
  <span m=''1864990''>triangles</span> <span m=''1865900''>and</span> <span m=''1866110''>quadrilaterals,</span>
  <span m=''1867220''>or</span> <span m=''1867710''>three-sided</span> <span m=''1868130''>gaps</span>
  <span m=''1868530''>and</span> <span m=''1868690''>four-sided</span> <span m=''1869130''>gaps.</span>
  <span m=''1869930''>And</span> <span m=''1870050''>then</span> <span m=''1870180''>all</span>
  <span m=''1870420''>we</span> <span m=''1870530''>do</span> <span m=''1871380''>is</span>
  <span m=''1871740''>draw</span> <span m=''1871960''>this</span> <span m=''1872140''>red</span>
  <span m=''1872370''>graph</span> <span m=''1872730''>by</span> <span m=''1872880''>putting</span>
  <span m=''1873210''>a</span> <span m=''1873240''>vertex</span> <span m=''1873760''>at</span>
  <span m=''1873890''>the</span> <span m=''1873980''>center</span> <span m=''1874460''>of</span>
  <span m=''1874540''>each</span> <span m=''1874780''>disk.</span> </p><p><span m=''1876100''>That''s
  what</span> <span m=''1876220''>the</span> <span m=''1876410''>question</span> <span
  m=''1876710''>was</span> <span m=''1876850''>about.</span> <span m=''1877350''>And</span>
  <span m=''1877530''>then</span> <span m=''1877630''>whenever</span> <span m=''1878050''>two</span>
  <span m=''1878280''>disks</span> <span m=''1879040''>touch,</span> <span m=''1880510''>we</span>
  <span m=''1880660''>call</span> <span m=''1880810''>this</span> <span m=''1881010''>kissing</span>
  <span m=''1881440''>disks</span> <span m=''1881880''>for</span> <span m=''1882330''>historic</span>
  <span m=''1882730''>reasons,</span> <span m=''1884720''>because</span> <span m=''1884850''>they''re
  just</span> <span m=''1885100''>barely</span> <span m=''1885470''>touching</span>
  <span m=''1885890''>I guess,</span> <span m=''1886655''>at</span> <span m=''1886960''>their</span>
  <span m=''1887150''>lips.</span> <span m=''1888220''>Got</span> <span m=''1888610''>a
  lot of lips</span> <span m=''1889000''>for</span> <span m=''1889120''>disks.</span>
  <span m=''1890590''>At least</span> <span m=''1890730''>we''re in</span> <span m=''1890960''>flat</span>
  <span m=''1891200''>land.</span> <span m=''1892370''>So</span> <span m=''1892980''>then</span>
  <span m=''1893380''>whenever</span> <span m=''1893730''>they</span> <span m=''1893920''>touch,</span>
  <span m=''1894270''>we</span> <span m=''1894400''>draw</span> <span m=''1894740''>the</span>
  <span m=''1895620''>edge</span> <span m=''1895850''>between</span> <span m=''1896130''>the</span>
  <span m=''1896210''>two</span> <span m=''1896610''>centers.</span> <span m=''1897790''>So</span>
  <span m=''1897960''>that</span> <span m=''1898180''>decomposes</span> <span m=''1898800''>this</span>
  <span m=''1898970''>piece</span> <span m=''1899180''>of</span> <span m=''1899260''>paper</span>
  <span m=''1899630''>into</span> <span m=''1899900''>parts,</span> <span m=''1900670''>and</span>
  <span m=''1900840''>because</span> <span m=''1901210''>the</span> <span m=''1901320''>gaps</span>
  <span m=''1901640''>are</span> <span m=''1901780''>three</span> <span m=''1901990''>sides,</span>
  <span m=''1902370''>those</span> <span m=''1902570''>will</span> <span m=''1902730''>correspond</span>
  <span m=''1903240''>to</span> <span m=''1903320''>triangles,</span> <span m=''1904190''>or</span>
  <span m=''1904340''>four</span> <span m=''1904620''>sides,</span> <span m=''1905060''>those</span>
  <span m=''1905270''>will</span> <span m=''1905360''>correspond</span> <span m=''1905930''>to</span>
  <span m=''1906100''>quadrilaterals.</span> </p><p><span m=''1907530''>So</span>
  <span m=''1907640''>that''s</span> <span m=''1907890''>all.</span> <span m=''1908600''>And</span>
  <span m=''1908700''>then</span> <span m=''1908880''>we</span> <span m=''1908980''>put</span>
  <span m=''1909160''>rabbit</span> <span m=''1909480''>ears</span> <span m=''1909670''>in</span>
  <span m=''1909750''>here,</span> <span m=''1910310''>and</span> <span m=''1910680''>line</span>
  <span m=''1910890''>universal</span> <span m=''1911900''>quad</span> <span m=''1912200''>molecules</span>
  <span m=''1912900''>in</span> <span m=''1913080''>there,</span> <span m=''1913970''>and</span>
  <span m=''1914310''>it</span> <span m=''1914400''>folds</span> <span m=''1914640''>flat.</span>
  <span m=''1915240''>It</span> <span m=''1915390''>will</span> <span m=''1915630''>align</span>
  <span m=''1915950''>all</span> <span m=''1916260''>of</span> <span m=''1916330''>the</span>
  <span m=''1916440''>red</span> <span m=''1916640''>edges</span> <span m=''1916970''>plus</span>
  <span m=''1917390''>these</span> <span m=''1917620''>black</span> <span m=''1917960''>edges</span>
  <span m=''1918450''>on</span> <span m=''1918680''>the</span> <span m=''1918810''>outside,</span>
  <span m=''1919490''>and it</span> <span m=''1919770''>will</span> <span m=''1920190''>align</span>
  <span m=''1920620''>all</span> <span m=''1920820''>these</span> <span m=''1921090''>inner</span>
  <span m=''1921360''>red</span> <span m=''1921550''>edges</span> <span m=''1922320''>with</span>
  <span m=''1922460''>these</span> <span m=''1922680''>black</span> <span m=''1922970''>edges,</span>
  <span m=''1923330''>and</span> <span m=''1923440''>then</span> <span m=''1923550''>we</span>
  <span m=''1923670''>do</span> <span m=''1923830''>the</span> <span m=''1924400''>sync</span>
  <span m=''1924630''>folds</span> <span m=''1924910''>that</span> <span m=''1925190''>we</span>
  <span m=''1925300''>mentioned.</span> <span m=''1925820''>And</span> <span m=''1926020''>that</span>
  <span m=''1926200''>will</span> <span m=''1926810''>get</span> <span m=''1926960''>one</span>
  <span m=''1927140''>of</span> <span m=''1927180''>these</span> <span m=''1927360''>out</span>
  <span m=''1927500''>of the</span> <span m=''1927630''>way</span> <span m=''1927800''>of</span>
  <span m=''1927890''>the</span> <span m=''1928050''>other,</span> <span m=''1928600''>and</span>
  <span m=''1928800''>we''ll</span> <span m=''1928900''>end</span> <span m=''1929070''>up</span>
  <span m=''1929270''>aligning</span> <span m=''1929870''>just</span> <span m=''1930450''>these</span>
  <span m=''1930910''>cut</span> <span m=''1931190''>edges.</span> <span m=''1934560''>So</span>
  <span m=''1934700''>that''s</span> <span m=''1935080''>a</span> <span m=''1935700''>quick</span>
  <span m=''1935940''>review</span> <span m=''1936360''>of</span> <span m=''1936620''>that</span>
  <span m=''1936850''>method.</span> </p><p><span m=''1939500''>So</span> <span m=''1939710''>one</span>
  <span m=''1939870''>question</span> <span m=''1940180''>is,</span> <span m=''1940670''>how</span>
  <span m=''1940870''>do</span> <span m=''1940940''>you</span> <span m=''1941140''>allocate</span>
  <span m=''1941710''>the</span> <span m=''1941800''>disks.</span> <span m=''1942230''>Is</span>
  <span m=''1942410''>there</span> <span m=''1942590''>sort</span> <span m=''1942800''>of</span>
  <span m=''1942890''>a</span> <span m=''1942980''>best</span> <span m=''1943350''>way?</span>
  <span m=''1944240''>And</span> <span m=''1945030''>I</span> <span m=''1945090''>guess</span>
  <span m=''1945290''>there</span> <span m=''1945440''>could</span> <span m=''1945590''>be</span>
  <span m=''1945720''>several</span> <span m=''1946040''>measures.</span> <span m=''1946380''>Maybe</span>
  <span m=''1946600''>you</span> <span m=''1946650''>don''t</span> <span m=''1946830''>want</span>
  <span m=''1947020''>really</span> <span m=''1947270''>tiny</span> <span m=''1947590''>disks,</span>
  <span m=''1947970''>because</span> <span m=''1948070''>that</span> <span m=''1948250''>tends</span>
  <span m=''1948470''>to</span> <span m=''1948560''>lead</span> <span m=''1948740''>to</span>
  <span m=''1948820''>very</span> <span m=''1949000''>tiny</span> <span m=''1949300''>folds.</span>
  <span m=''1950420''>But</span> <span m=''1950710''>the</span> <span m=''1950930''>standard</span>
  <span m=''1951310''>measure</span> <span m=''1951630''>here</span> <span m=''1951890''>is</span>
  <span m=''1952110''>how</span> <span m=''1952360''>many</span> <span m=''1952620''>disks</span>
  <span m=''1953040''>do</span> <span m=''1953130''>you</span> <span m=''1953230''>need,</span>
  <span m=''1953870''>because</span> <span m=''1954210''>that</span> <span m=''1954370''>will</span>
  <span m=''1954510''>reduce</span> <span m=''1954870''>the</span> <span m=''1954950''>number</span>
  <span m=''1955310''>of</span> <span m=''1955380''>folds.</span> <span m=''1956520''>So</span>
  <span m=''1956730''>can</span> <span m=''1956860''>you</span> <span m=''1956960''>minimize</span>
  <span m=''1957460''>the</span> <span m=''1957530''>number</span> <span m=''1957800''>of</span>
  <span m=''1957870''>disks,</span> <span m=''1958520''>and</span> <span m=''1959510''>in</span>
  <span m=''1959710''>general,</span> <span m=''1960210''>it''s</span> <span m=''1960450''>known</span>
  <span m=''1960760''>roughly</span> <span m=''1961070''>how</span> <span m=''1961250''>many</span>
  <span m=''1961490''>disks</span> <span m=''1961840''>you</span> <span m=''1961960''>need.</span>
  <span m=''1962310''>And</span> <span m=''1962490''>the</span> <span m=''1962590''>algorithm</span>
  <span m=''1963020''>I</span> <span m=''1963100''>just</span> <span m=''1963320''>told</span>
  <span m=''1963560''>you</span> <span m=''1964420''>achieves</span> <span m=''1964870''>that</span>
  <span m=''1965080''>number</span> <span m=''1965360''>of</span> <span m=''1965420''>disks.</span>
  </p><p><span m=''1967230''>So</span> <span m=''1968260''>first</span> <span m=''1968820''>I''ll</span>
  <span m=''1969000''>give</span> <span m=''1969200''>you</span> <span m=''1969560''>the</span>
  <span m=''1969650''>number.</span> <span m=''1972000''>Number</span> <span m=''1972360''>of</span>
  <span m=''1972810''>disks</span> <span m=''1973450''>is</span> <span m=''1973680''>proportional</span>
  <span m=''1974260''>to</span> <span m=''1975800''>the</span> <span m=''1975990''>integral--</span>
  <span m=''1978830''>I</span> <span m=''1978980''>didn''t</span> <span m=''1979080''>say
  it was the</span> <span m=''1979220''>easy</span> <span m=''1979510''>bound,</span>
  <span m=''1979940''>but</span> <span m=''1980520''>it</span> <span m=''1980690''>is</span>
  <span m=''1980930''>the</span> <span m=''1981160''>right</span> <span m=''1981390''>answer.</span>
  <span m=''1986810''>OK,</span> <span m=''1987190''>there''s a</span> <span m=''1987240''>lot</span>
  <span m=''1987530''>of</span> <span m=''1987590''>notation</span> <span m=''1988200''>in</span>
  <span m=''1988350''>here,</span> <span m=''1988620''>and</span> <span m=''1989090''>this</span>
  <span m=''1989270''>one</span> <span m=''1989480''>you</span> <span m=''1989580''>should</span>
  <span m=''1989770''>definitely</span> <span m=''1990100''>not</span> <span m=''1990470''>know</span>
  <span m=''1991260''>unless</span> <span m=''1991500''>you''ve</span> <span m=''1991680''>taken</span>
  <span m=''1992000''>a</span> <span m=''1992070''>computational</span> <span m=''1992590''>geometry</span>
  <span m=''1992970''>class.</span> <span m=''1993210''>Even</span> <span m=''1993500''>then,</span>
  <span m=''1993750''>you</span> <span m=''1993870''>probably</span> <span m=''1994400''>wouldn''t</span>
  <span m=''1994670''>know</span> <span m=''1994900''>it.</span> <span m=''1995390''>It''s</span>
  <span m=''1995490''>not</span> <span m=''1995630''>that</span> <span m=''1995810''>common.</span>
  <span m=''1996710''>It mostly</span> <span m=''1997130''>comes</span> <span m=''1997370''>up</span>
  <span m=''1997490''>in</span> <span m=''1997610''>meshing</span> <span m=''1998070''>and</span>
  <span m=''1998370''>disk-packing,</span> <span m=''1998655''>so</span> <span m=''1998940''>it''s</span>
  <span m=''1999330''>pretty</span> <span m=''1999550''>specific.</span> <span m=''2000150''>It''s</span>
  <span m=''2000640''>called</span> <span m=''2001240''>local</span> <span m=''2001710''>feature</span>
  <span m=''2002090''>size.</span> </p><p><span m=''2005390''>And</span> <span m=''2005550''>this</span>
  <span m=''2005720''>is</span> <span m=''2005840''>if,</span> <span m=''2006400''>once</span>
  <span m=''2006690''>I</span> <span m=''2006990''>define</span> <span m=''2007280''>it,</span>
  <span m=''2007390''>it is</span> <span m=''2007580''>actually</span> <span m=''2007900''>fairly</span>
  <span m=''2008230''>intuitive,</span> <span m=''2008910''>this</span> <span m=''2009130''>bound.</span>
  <span m=''2010940''>Local</span> <span m=''2011220''>feature</span> <span m=''2011500''>size</span>
  <span m=''2011800''>at</span> <span m=''2012080''>X.</span> <span m=''2012970''>So</span>
  <span m=''2014010''>we''re</span> <span m=''2014270''>imagining</span> <span m=''2014740''>some</span>
  <span m=''2014910''>kind</span> <span m=''2015100''>of</span> <span m=''2015220''>polygon</span>
  <span m=''2015870''>here.</span> <span m=''2018910''>And</span> <span m=''2019400''>at</span>
  <span m=''2019550''>every</span> <span m=''2019940''>point</span> <span m=''2020400''>of</span>
  <span m=''2020470''>the</span> <span m=''2020560''>polygon--</span> <span m=''2021140''>let''s</span>
  <span m=''2021550''>look</span> <span m=''2021740''>at</span> <span m=''2021800''>a</span>
  <span m=''2021840''>vertex</span> <span m=''2022380''>here--</span> <span m=''2022690''>but</span>
  <span m=''2023030''>it</span> <span m=''2023170''>works</span> <span m=''2023430''>for</span>
  <span m=''2023630''>any</span> <span m=''2023890''>point</span> <span m=''2024170''>along</span>
  <span m=''2024540''>the</span> <span m=''2024620''>boundary.</span> <span m=''2025400''>Actually</span>
  <span m=''2025620''>maybe</span> <span m=''2025880''>not</span> <span m=''2026050''>even</span>
  <span m=''2026260''>on</span> <span m=''2026390''>the</span> <span m=''2026470''>boundary,</span>
  <span m=''2027820''>but</span> <span m=''2028190''>we''re</span> <span m=''2028350''>interested</span>
  <span m=''2028660''>here--</span> <span m=''2029110''>this</span> <span m=''2029740''>notation</span>
  <span m=''2030310''>del</span> <span m=''2030610''>p</span> <span m=''2031830''>is</span>
  <span m=''2032130''>the</span> <span m=''2032220''>boundary</span> <span m=''2032620''>of</span>
  <span m=''2032660''>the</span> <span m=''2032740''>polygon.</span> <span m=''2033260''>So</span>
  <span m=''2033440''>this</span> <span m=''2033660''>is</span> <span m=''2033840''>del</span>
  <span m=''2034210''>p.</span> <span m=''2035770''>That</span> <span m=''2035880''>just</span>
  <span m=''2036070''>means</span> <span m=''2037110''>edges</span> <span m=''2037430''>and</span>
  <span m=''2037510''>vertices,</span> <span m=''2037950''>all</span> <span m=''2038210''>of
  those</span> <span m=''2038460''>points.</span> <span m=''2040310''>So</span> <span
  m=''2040470''>we</span> <span m=''2040570''>take</span> <span m=''2040770''>some</span>
  <span m=''2040920''>point</span> <span m=''2041120''>X</span> <span m=''2041350''>on</span>
  <span m=''2041490''>the</span> <span m=''2041560''>boundary,</span> <span m=''2042460''>and</span>
  <span m=''2042600''>we</span> <span m=''2042700''>look</span> <span m=''2042960''>at</span>
  <span m=''2043170''>the</span> <span m=''2043390''>smallest</span> <span m=''2044110''>disk</span>
  <span m=''2045330''>centered</span> <span m=''2045810''>at</span> <span m=''2045920''>that</span>
  <span m=''2046140''>point</span> <span m=''2047980''>that</span> <span m=''2048190''>touches</span>
  <span m=''2048679''>another</span> <span m=''2049000''>feature.</span> </p><p><span
  m=''2050730''>So</span> <span m=''2050940''>that''s</span> <span m=''2051150''>the</span>
  <span m=''2051219''>feature</span> <span m=''2051710''>size.</span> <span m=''2052090''>Features</span>
  <span m=''2052469''>here</span> <span m=''2052679''>are</span> <span m=''2052840''>edges</span>
  <span m=''2053230''>of</span> <span m=''2053320''>the</span> <span m=''2053420''>polygon.</span>
  <span m=''2053920''>That''s</span> <span m=''2054159''>all</span> <span m=''2054280''>we</span>
  <span m=''2054370''>have.</span> <span m=''2055719''>Now</span> <span m=''2055940''>of</span>
  <span m=''2056060''>course,</span> <span m=''2056400''>no</span> <span m=''2056510''>matter</span>
  <span m=''2056719''>what</span> <span m=''2056909''>size</span> <span m=''2057190''>disk,</span>
  <span m=''2057560''>you</span> <span m=''2057810''>hit</span> <span m=''2058070''>this</span>
  <span m=''2058250''>feature</span> <span m=''2058570''>and</span> <span m=''2058630''>you
  hit</span> <span m=''2058830''>this</span> <span m=''2059010''>feature,</span> <span
  m=''2059290''>so</span> <span m=''2059389''>those</span> <span m=''2059600''>don''t</span>
  <span m=''2059780''>count.</span> <span m=''2060040''>Those</span> <span m=''2060210''>are</span>
  <span m=''2060310''>incident</span> <span m=''2060770''>features.</span> <span m=''2061929''>So</span>
  <span m=''2062199''>in</span> <span m=''2062290''>general,</span> <span m=''2062679''>it</span>
  <span m=''2062840''>is</span> <span m=''2063060''>the</span> <span m=''2063250''>smallest</span>
  <span m=''2063780''>radius</span> <span m=''2064909''>disk</span> <span m=''2072510''>that</span>
  <span m=''2072840''>hits</span> <span m=''2074310''>a</span> <span m=''2074620''>non</span>
  <span m=''2075070''>incident</span> <span m=''2075730''>feature</span> <span m=''2078042''>on</span>
  <span m=''2078980''>incident</span> <span m=''2080850''>feature,</span> <span m=''2081730''>which</span>
  <span m=''2081900''>is</span> <span m=''2082030''>an</span> <span m=''2082139''>edge.</span>
  <span m=''2084500''>So</span> <span m=''2084630''>here,</span> <span m=''2085270''>as</span>
  <span m=''2085380''>soon</span> <span m=''2085620''>as</span> <span m=''2085739''>the</span>
  <span m=''2085840''>disk</span> <span m=''2086199''>gets</span> <span m=''2086650''>this</span>
  <span m=''2086940''>big,</span> <span m=''2087320''>it</span> <span m=''2087489''>hits</span>
  <span m=''2087770''>this</span> <span m=''2088030''>edge.</span> <span m=''2088870''>And</span>
  <span m=''2089090''>so</span> <span m=''2090120''>the</span> <span m=''2090290''>local</span>
  <span m=''2090560''>feature</span> <span m=''2090860''>size</span> <span m=''2091260''>is</span>
  <span m=''2091520''>this</span> <span m=''2092440''>radius.</span> <span m=''2094880''>In</span>
  <span m=''2095100''>general,</span> <span m=''2095440''>for</span> <span m=''2095570''>every</span>
  <span m=''2095790''>point,</span> <span m=''2096010''>you</span> <span m=''2096139''>can</span>
  <span m=''2096280''>draw</span> <span m=''2096460''>some</span> <span m=''2096730''>size</span>
  <span m=''2097050''>disk.</span> <span m=''2098272''>So</span> <span m=''2098650''>over</span>
  <span m=''2098920''>here,</span> <span m=''2099850''>it''s</span> <span m=''2099970''>going</span>
  <span m=''2100090''>to</span> <span m=''2100140''>be</span> <span m=''2100230''>a</span>
  <span m=''2100300''>little</span> <span m=''2100460''>bit</span> <span m=''2100630''>bigger.</span>
  <span m=''2100985''>You can</span> <span m=''2101450''>maybe</span> <span m=''2101720''>get</span>
  <span m=''2102580''>up</span> <span m=''2102740''>to</span> <span m=''2102830''>here.</span>
  </p><p><span m=''2106990''>Actually,</span> <span m=''2107510''>I</span> <span m=''2107560''>guess</span>
  <span m=''2107770''>it</span> <span m=''2107850''>should</span> <span m=''2108000''>be</span>
  <span m=''2108120''>non-adjacent.</span> <span m=''2109920''>That</span> <span m=''2109950''>was</span>
  <span m=''2110240''>going</span> <span m=''2110360''>to</span> <span m=''2110430''>be</span>
  <span m=''2110590''>a</span> <span m=''2110650''>little</span> <span m=''2110870''>bit</span>
  <span m=''2111840''>awkward.</span> <span m=''2112500''>I</span> <span m=''2112820''>also</span>
  <span m=''2113040''>don''t</span> <span m=''2113210''>want</span> <span m=''2113320''>to</span>
  <span m=''2113380''>count</span> <span m=''2113730''>this</span> <span m=''2113950''>edge,</span>
  <span m=''2114300''>because</span> <span m=''2114570''>if</span> <span m=''2114730''>I''m</span>
  <span m=''2114850''>right</span> <span m=''2115070''>here,</span> <span m=''2115840''>the</span>
  <span m=''2115970''>feature</span> <span m=''2116300''>size</span> <span m=''2116460''>is</span>
  <span m=''2116500''>super</span> <span m=''2116830''>tiny,</span> <span m=''2117090''>and</span>
  <span m=''2117350''>I</span> <span m=''2117960''>don''t</span> <span m=''2118100''>want</span>
  <span m=''2118820''>LFS</span> <span m=''2119100''>ever</span> <span m=''2119320''>to</span>
  <span m=''2119390''>be</span> <span m=''2119510''>0.</span> <span m=''2120480''>So</span>
  <span m=''2120630''>you</span> <span m=''2120780''>also</span> <span m=''2120980''>have</span>
  <span m=''2121080''>to</span> <span m=''2121180''>skip</span> <span m=''2121480''>the</span>
  <span m=''2123620''>adjacent</span> <span m=''2124380''>edges,</span> <span m=''2124810''>which</span>
  <span m=''2125000''>means</span> <span m=''2125270''>local</span> <span m=''2125550''>feature</span>
  <span m=''2125790''>size</span> <span m=''2126030''>of</span> <span m=''2126110''>this</span>
  <span m=''2126260''>point</span> <span m=''2126460''>is</span> <span m=''2126560''>going</span>
  <span m=''2126680''>to</span> <span m=''2126740''>be</span> <span m=''2126880''>more</span>
  <span m=''2127160''>like--</span> <span m=''2129690''>hard</span> <span m=''2130110''>to</span>
  <span m=''2130180''>draw</span> <span m=''2130340''>circles--</span> <span m=''2131660''>it''s</span>
  <span m=''2131780''>going</span> <span m=''2131900''>to</span> <span m=''2131950''>be</span>
  <span m=''2132070''>more</span> <span m=''2132240''>like</span> <span m=''2132440''>that</span>
  <span m=''2132700''>distance.</span> <span m=''2134370''>That''s</span> <span m=''2134580''>when</span>
  <span m=''2134670''>you</span> <span m=''2134750''>hit</span> <span m=''2136270''>a</span>
  <span m=''2136350''>non-adjacent</span> <span m=''2137180''>feature,</span> <span
  m=''2137590''>sorry.</span> </p><p><span m=''2137880''>So you</span> <span m=''2138000''>have</span>
  <span m=''2138090''>to</span> <span m=''2138160''>exclude</span> <span m=''2138510''>this</span>
  <span m=''2138700''>edge</span> <span m=''2139080''>that</span> <span m=''2139200''>you''re</span>
  <span m=''2139360''>on</span> <span m=''2139700''>and</span> <span m=''2139860''>the</span>
  <span m=''2139950''>two</span> <span m=''2140240''>adjacent</span> <span m=''2140530''>ones,</span>
  <span m=''2140760''>otherwise</span> <span m=''2141190''>this</span> <span m=''2141660''>definition</span>
  <span m=''2142090''>doesn''t</span> <span m=''2142300''>quite</span> <span m=''2142520''>work</span>
  <span m=''2142730''>out.</span> <span m=''2144100''>So</span> <span m=''2145050''>then</span>
  <span m=''2145230''>you</span> <span m=''2145360''>measure</span> <span m=''2145610''>this</span>
  <span m=''2145780''>for</span> <span m=''2145900''>all</span> <span m=''2146140''>points.</span>
  <span m=''2146670''>There''s</span> <span m=''2147280''>infinitely</span> <span
  m=''2147740''>many,</span> <span m=''2148050''>of</span> <span m=''2148150''>course,</span>
  <span m=''2148450''>continuum</span> <span m=''2149090''>along</span> <span m=''2149360''>the</span>
  <span m=''2149450''>boundary.</span> <span m=''2150360''>That''s</span> <span m=''2150460''>the</span>
  <span m=''2150580''>integral</span> <span m=''2151040''>over</span> <span m=''2151240''>X</span>
  <span m=''2151750''>in</span> <span m=''2152860''>the</span> <span m=''2152950''>boundary</span>
  <span m=''2153280''>of</span> <span m=''2153360''>P.</span> <span m=''2154070''>And</span>
  <span m=''2154290''>you</span> <span m=''2154390''>take</span> <span m=''2154620''>1</span>
  <span m=''2154990''>over</span> <span m=''2155450''>the</span> <span m=''2155570''>local</span>
  <span m=''2155880''>feature</span> <span m=''2156200''>size</span> <span m=''2156480''>of</span>
  <span m=''2156580''>X,</span> <span m=''2156860''>and</span> <span m=''2156940''>you</span>
  <span m=''2157070''>integrate</span> <span m=''2157570''>that</span> <span m=''2157880''>for</span>
  <span m=''2158030''>all</span> <span m=''2158250''>X.</span> <span m=''2159220''>It</span>
  <span m=''2159370''>gives</span> <span m=''2159540''>you</span> <span m=''2159750''>a</span>
  <span m=''2159820''>number,</span> <span m=''2160680''>and</span> <span m=''2161020''>it</span>
  <span m=''2161110''>turns</span> <span m=''2161370''>out,</span> <span m=''2162140''>some</span>
  <span m=''2162440''>constant</span> <span m=''2162990''>times</span> <span m=''2163200''>that</span>
  <span m=''2163340''>number</span> <span m=''2163660''>is</span> <span m=''2163820''>the</span>
  <span m=''2163930''>right</span> <span m=''2164130''>answer.</span> </p><p><span
  m=''2164890''>The algorithm</span> <span m=''2165230''>I</span> <span m=''2165410''>achieve,</span>
  <span m=''2165740''>which</span> <span m=''2166360''>I</span> <span m=''2166460''>described,</span>
  <span m=''2166980''>which</span> <span m=''2167010''>is</span> <span m=''2167100''>put</span>
  <span m=''2167270''>the</span> <span m=''2167350''>biggest</span> <span m=''2167720''>disk</span>
  <span m=''2167850''>you</span> <span m=''2167990''>can</span> <span m=''2168360''>or</span>
  <span m=''2168570''>divide</span> <span m=''2168850''>in</span> <span m=''2168940''>half</span>
  <span m=''2169250''>if</span> <span m=''2169370''>you</span> <span m=''2169480''>can''t</span>
  <span m=''2170240''>will</span> <span m=''2170470''>get</span> <span m=''2170620''>within</span>
  <span m=''2170880''>a</span> <span m=''2170950''>constant</span> <span m=''2171300''>factor</span>
  <span m=''2171630''>of</span> <span m=''2171780''>the</span> <span m=''2171880''>best</span>
  <span m=''2172240''>possible</span> <span m=''2172680''>bound</span> <span m=''2172990''>of</span>
  <span m=''2173260''>all</span> <span m=''2173610''>possible</span> <span m=''2174040''>to</span>
  <span m=''2174130''>disk-packings.</span> <span m=''2175480''>So</span> <span m=''2176630''>this</span>
  <span m=''2176850''>is</span> <span m=''2176990''>pretty</span> <span m=''2177210''>much</span>
  <span m=''2177460''>known.</span> <span m=''2177720''>You</span> <span m=''2177890''>get</span>
  <span m=''2178080''>within</span> <span m=''2178340''>a</span> <span m=''2178420''>constant</span>
  <span m=''2178770''>factor</span> <span m=''2179130''>of</span> <span m=''2179280''>the</span>
  <span m=''2179430''>optimal</span> <span m=''2179840''>disk-packing</span> <span
  m=''2180320''>if</span> <span m=''2181260''>you''re</span> <span m=''2181360''>counting</span>
  <span m=''2181720''>disks.</span> <span m=''2183070''>Not</span> <span m=''2183250''>a</span>
  <span m=''2183280''>great</span> <span m=''2183510''>number.</span> <span m=''2183850''>I</span>
  <span m=''2183890''>can''t</span> <span m=''2184160''>say</span> <span m=''2184290''>they''re</span>
  <span m=''2184710''>N</span> <span m=''2185010''>disks</span> <span m=''2185120''>or</span>
  <span m=''2185260''>N squared</span> <span m=''2185590''>disks,</span> <span m=''2186490''>because</span>
  <span m=''2186900''>you</span> <span m=''2187080''>just</span> <span m=''2187300''>can''t</span>
  <span m=''2187530''>do</span> <span m=''2187650''>that.</span> <span m=''2190120''>If</span>
  <span m=''2190560''>you</span> <span m=''2190640''>have</span> <span m=''2190730''>a</span>
  <span m=''2190800''>piece</span> <span m=''2191000''>of</span> <span m=''2191070''>paper</span>
  <span m=''2192050''>and</span> <span m=''2192310''>some</span> <span m=''2192640''>really</span>
  <span m=''2193030''>long--</span> <span m=''2193590''>here''s</span> <span m=''2193880''>your</span>
  <span m=''2194020''>cut</span> <span m=''2194270''>graph.</span> <span m=''2195020''>Doesn''t</span>
  <span m=''2195270''>quite</span> <span m=''2195530''>go</span> <span m=''2195680''>to</span>
  <span m=''2195780''>the</span> <span m=''2195990''>ends,</span> <span m=''2196320''>though--</span>
  <span m=''2197500''>then</span> <span m=''2197650''>you''ve</span> <span m=''2197790''>got</span>
  <span m=''2197960''>to</span> <span m=''2198000''>have</span> <span m=''2198180''>a
  tiny</span> <span m=''2198560''>disk</span> <span m=''2198810''>here,</span> <span
  m=''2199280''>and</span> <span m=''2199470''>that''s</span> <span m=''2199660''>going</span>
  <span m=''2199780''>to</span> <span m=''2199890''>require</span> <span m=''2200260''>you</span>
  <span m=''2200300''>to</span> <span m=''2200380''>have</span> <span m=''2200670''>a</span>
  <span m=''2200730''>bunch</span> <span m=''2200970''>of</span> <span m=''2201040''>disks.</span>
  <span m=''2201270''>Even</span> <span m=''2201500''>though</span> <span m=''2201610''>this</span>
  <span m=''2201840''>has</span> <span m=''2202110''>constant</span> <span m=''2202590''>size,</span>
  <span m=''2203620''>you''re</span> <span m=''2203740''>going</span> <span m=''2203860''>to</span>
  <span m=''2203930''>need,</span> <span m=''2204660''>I</span> <span m=''2204750''>don''t</span>
  <span m=''2204890''>know</span> <span m=''2204970''>how</span> <span m=''2205120''>many</span>
  <span m=''2205320''>disks</span> <span m=''2205600''>here.</span> </p><p><span m=''2206820''>Especially</span>
  <span m=''2207320''>if</span> <span m=''2207380''>your</span> <span m=''2207510''>paper''s</span>
  <span m=''2207870''>really</span> <span m=''2208110''>narrow,</span> <span m=''2208470''>you''re</span>
  <span m=''2208590''>going</span> <span m=''2208720''>to</span> <span m=''2208800''>need</span>
  <span m=''2208950''>a</span> <span m=''2209000''>lot</span> <span m=''2209170''>of</span>
  <span m=''2209280''>disks.</span> <span m=''2211210''>That''s</span> <span m=''2211510''>the</span>
  <span m=''2211570''>best</span> <span m=''2211790''>you</span> <span m=''2211890''>can</span>
  <span m=''2212000''>hope</span> <span m=''2212160''>for</span> <span m=''2212560''>disk-packing.</span>
  <span m=''2212770''>I</span> <span m=''2213130''>actually</span> <span m=''2213440''>brought</span>
  <span m=''2213890''>a</span> <span m=''2214210''>little</span> <span m=''2214450''>example</span>
  <span m=''2214920''>of</span> <span m=''2215000''>something</span> <span m=''2215370''>like</span>
  <span m=''2215630''>that</span> <span m=''2215900''>where</span> <span m=''2216810''>your</span>
  <span m=''2216970''>goal</span> <span m=''2217230''>is</span> <span m=''2217330''>just</span>
  <span m=''2217500''>to</span> <span m=''2217570''>cut</span> <span m=''2217810''>out</span>
  <span m=''2218000''>a</span> <span m=''2218060''>single</span> <span m=''2218400''>segment</span>
  <span m=''2218810''>in</span> <span m=''2218910''>the</span> <span m=''2218980''>middle</span>
  <span m=''2219200''>of</span> <span m=''2219240''>the</span> <span m=''2219330''>paper.</span>
  <span m=''2219680''>This</span> <span m=''2219880''>is</span> <span m=''2219990''>to</span>
  <span m=''2220070''>illustrate</span> <span m=''2221430''>odd</span> <span m=''2221670''>degree</span>
  <span m=''2221890''>vertices.</span> <span m=''2222380''>These</span> <span m=''2222550''>are</span>
  <span m=''2222600''>degree</span> <span m=''2222910''>1</span> <span m=''2223140''>vertices,
  and</span> <span m=''2223560''>you</span> <span m=''2223690''>might</span> <span
  m=''2223870''>think,</span> <span m=''2224060''>wow,</span> <span m=''2224810''>it''s</span>
  <span m=''2224900''>impossible</span> <span m=''2225510''>for</span> <span m=''2225620''>me</span>
  <span m=''2225720''>to</span> <span m=''2225810''>cut</span> <span m=''2226350''>this</span>
  <span m=''2226560''>thing</span> <span m=''2226890''>without,</span> <span m=''2227420''>I
  don''t</span> <span m=''2227820''>know,</span> <span m=''2228160''>just</span> <span
  m=''2228540''>cutting.</span> <span m=''2229310''>I</span> <span m=''2229420''>could</span>
  <span m=''2229770''>cut</span> <span m=''2229950''>with</span> <span m=''2230080''>my</span>
  <span m=''2230190''>X-ACTO</span> <span m=''2230570''>knife</span> <span m=''2230840''>from</span>
  <span m=''2231050''>here</span> <span m=''2231230''>to</span> <span m=''2231280''>here.</span>
  <span m=''2232210''>If</span> <span m=''2232310''>I</span> <span m=''2232410''>want</span>
  <span m=''2232470''>to</span> <span m=''2232520''>make</span> <span m=''2232670''>a</span>
  <span m=''2232720''>complete</span> <span m=''2233280''>straight</span> <span m=''2233480''>cut,</span>
  <span m=''2234640''>you</span> <span m=''2235130''>can fold</span> <span m=''2235560''>it</span>
  <span m=''2235640''>like</span> <span m=''2235840''>this.</span> <span m=''2237320''>This
  is</span> <span m=''2237440''>what</span> <span m=''2237720''>the</span> <span m=''2238290''>skeleton</span>
  <span m=''2238890''>method</span> <span m=''2239160''>would</span> <span m=''2239290''>give</span>
  <span m=''2239460''>you.</span> </p><p><span m=''2240610''>Fold</span> <span m=''2240850''>it</span>
  <span m=''2240930''>like</span> <span m=''2241140''>this,</span> <span m=''2241430''>and</span>
  <span m=''2241660''>then</span> <span m=''2241830''>you</span> <span m=''2241990''>use</span>
  <span m=''2242170''>your</span> <span m=''2242340''>laser</span> <span m=''2242840''>to</span>
  <span m=''2243120''>cut</span> <span m=''2243330''>right</span> <span m=''2243550''>along</span>
  <span m=''2243840''>the</span> <span m=''2243940''>line.</span> <span m=''2244320''>With</span>
  <span m=''2244460''>scissor</span> <span m=''2244710''>cuts,</span> <span m=''2244970''>it''s</span>
  <span m=''2245100''>not</span> <span m=''2245310''>so</span> <span m=''2245480''>bad,</span>
  <span m=''2245800''>right?</span> <span m=''2247050''>I</span> <span m=''2247160''>cut</span>
  <span m=''2247460''>slightly</span> <span m=''2248110''>in.</span> <span m=''2251260''>It''s
  pretty</span> <span m=''2251570''>much</span> <span m=''2251800''>cutting</span>
  <span m=''2252070''>along</span> <span m=''2252280''>the</span> <span m=''2252350''>line.</span>
  <span m=''2254200''>Just</span> <span m=''2254400''>not</span> <span m=''2254580''>quite.</span>
  <span m=''2256950''>I made</span> <span m=''2257390''>a tiny</span> <span m=''2257640''>mistake.</span>
  <span m=''2258190''>So</span> <span m=''2258270''>I</span> <span m=''2258380''>cut</span>
  <span m=''2258620''>off</span> <span m=''2258800''>a</span> <span m=''2258910''>line,</span>
  <span m=''2260360''>slightly</span> <span m=''2260720''>thicker</span> <span m=''2260970''>line,</span>
  <span m=''2261570''>and</span> <span m=''2261730''>I</span> <span m=''2261790''>get</span>
  <span m=''2262020''>my</span> <span m=''2262140''>slit</span> <span m=''2262460''>in</span>
  <span m=''2262550''>the</span> <span m=''2262640''>paper.</span> <span m=''2263220''>So</span>
  <span m=''2264730''>mathematical</span> <span m=''2265270''>cuts</span> <span m=''2266030''>are</span>
  <span m=''2266190''>not</span> <span m=''2266390''>really</span> <span m=''2266590''>that</span>
  <span m=''2266810''>bad.</span> <span m=''2267280''>You</span> <span m=''2267410''>just</span>
  <span m=''2268250''>are</span> <span m=''2268340''>cutting</span> <span m=''2268700''>a
  slightly</span> <span m=''2269280''>larger</span> <span m=''2269660''>version</span>
  <span m=''2270460''>than</span> <span m=''2270640''>the</span> <span m=''2270730''>single</span>
  <span m=''2271010''>slit</span> <span m=''2271490''>that</span> <span m=''2271700''>you
  wanted to</span> <span m=''2271840''>make.</span> <span m=''2272730''>You just</span>
  <span m=''2273080''>have to cut</span> <span m=''2273170''>very</span> <span m=''2273360''>carefully.</span>
  <span m=''2276160''>OK.</span> </p><p><span m=''2277200''>That</span> <span m=''2277440''>was</span>
  <span m=''2277920''>number</span> <span m=''2278320''>of</span> <span m=''2278400''>disks.</span>
  <span m=''2279590''>Next</span> <span m=''2279860''>question</span> <span m=''2280370''>is,</span>
  <span m=''2281420''>how</span> <span m=''2281650''>does</span> <span m=''2281830''>all</span>
  <span m=''2282070''>this</span> <span m=''2282250''>relate</span> <span m=''2282560''>to</span>
  <span m=''2282660''>the</span> <span m=''2282780''>tree</span> <span m=''2283020''>method?</span>
  <span m=''2283400''>This</span> <span m=''2283580''>is</span> <span m=''2283710''>kind</span>
  <span m=''2283860''>of</span> <span m=''2283950''>a neat</span> <span m=''2284140''>question.</span>
  <span m=''2284550''>Both</span> <span m=''2284870''>methods,</span> <span m=''2285840''>skeleton</span>
  <span m=''2286300''>method</span> <span m=''2286790''>and</span> <span m=''2286900''>the</span>
  <span m=''2286980''>disk-packing</span> <span m=''2287460''>method</span> <span
  m=''2287780''>relate</span> <span m=''2288160''>to</span> <span m=''2288940''>the</span>
  <span m=''2289040''>tree</span> <span m=''2289220''>method</span> <span m=''2289660''>in</span>
  <span m=''2290130''>different</span> <span m=''2290420''>ways.</span> <span m=''2291140''>I</span>
  <span m=''2291210''>thought I would</span> <span m=''2291430''>talk</span> <span
  m=''2291670''>about</span> <span m=''2291860''>that.</span> <span m=''2292620''>So</span>
  <span m=''2292650''>first,</span> <span m=''2292970''>let''s</span> <span m=''2293150''>compare</span>
  <span m=''2293490''>the</span> <span m=''2293610''>disk-packing</span> <span m=''2294200''>method</span>
  <span m=''2294580''>which</span> <span m=''2294740''>we</span> <span m=''2294820''>just</span>
  <span m=''2295030''>talked</span> <span m=''2295260''>about</span> <span m=''2295870''>to</span>
  <span m=''2296130''>the</span> <span m=''2296230''>tree</span> <span m=''2296450''>method.</span>
  <span m=''2297610''>Both</span> <span m=''2297840''>of</span> <span m=''2297910''>them</span>
  <span m=''2298040''>use</span> <span m=''2298260''>universal</span> <span m=''2298750''>molecules.</span>
  <span m=''2299850''>This</span> <span m=''2300060''>one</span> <span m=''2300310''>only</span>
  <span m=''2300560''>uses</span> <span m=''2300860''>universal</span> <span m=''2301300''>molecules</span>
  <span m=''2301760''>for</span> <span m=''2301880''>triangles</span> <span m=''2302380''>and</span>
  <span m=''2302520''>quads.</span> </p><p><span m=''2303970''>We</span> <span m=''2304190''>know</span>
  <span m=''2304350''>in</span> <span m=''2304440''>general,</span> <span m=''2304830''>the
  universal</span> <span m=''2305240''>molecule</span> <span m=''2305640''>works</span>
  <span m=''2305880''>for</span> <span m=''2306010''>any</span> <span m=''2306200''>convex</span>
  <span m=''2306650''>polygon.</span> <span m=''2307050''>This</span> <span m=''2307190''>is</span>
  <span m=''2307320''>an</span> <span m=''2307400''>example</span> <span m=''2307800''>of</span>
  <span m=''2308040''>a</span> <span m=''2308330''>pentagon.</span> <span m=''2309720''>And</span>
  <span m=''2309950''>it</span> <span m=''2310010''>works.</span> <span m=''2310690''>It</span>
  <span m=''2310890''>has</span> <span m=''2311060''>a</span> <span m=''2311100''>gusset</span>
  <span m=''2311620''>to</span> <span m=''2311850''>get</span> <span m=''2312070''>the</span>
  <span m=''2312400''>tree</span> <span m=''2312620''>lengths</span> <span m=''2312900''>right.</span>
  <span m=''2313510''>Here</span> <span m=''2313730''>we</span> <span m=''2313850''>use</span>
  <span m=''2314060''>gussets</span> <span m=''2314290''>to</span> <span m=''2314880''>kind</span>
  <span m=''2315200''>of</span> <span m=''2315320''>get</span> <span m=''2315490''>the</span>
  <span m=''2315580''>tree</span> <span m=''2315870''>lengths</span> <span m=''2316140''>right.</span>
  <span m=''2316390''>As</span> <span m=''2316610''>you</span> <span m=''2316730''>may</span>
  <span m=''2316870''>recall,</span> <span m=''2317200''>we</span> <span m=''2317250''>want</span>
  <span m=''2317460''>the</span> <span m=''2317540''>perpendiculars</span> <span m=''2318170''>to</span>
  <span m=''2318270''>go</span> <span m=''2318560''>to</span> <span m=''2319820''>the</span>
  <span m=''2320120''>disk</span> <span m=''2320610''>kissing</span> <span m=''2320990''>points,</span>
  <span m=''2321350''>those</span> <span m=''2321610''>tangencies.</span> <span m=''2323010''>Because</span>
  <span m=''2323390''>then</span> <span m=''2323560''>they</span> <span m=''2323670''>align</span>
  <span m=''2324020''>with</span> <span m=''2324140''>the</span> <span m=''2324280''>others,</span>
  <span m=''2324690''>and</span> <span m=''2324790''>then</span> <span m=''2324810''>we</span>
  <span m=''2324900''>never</span> <span m=''2325170''>get</span> <span m=''2325910''>the</span>
  <span m=''2326190''>perpendicular</span> <span m=''2326950''>spiraling</span> <span
  m=''2327610''>or</span> <span m=''2327660''>doing</span> <span m=''2327930''>other</span>
  <span m=''2328100''>bad</span> <span m=''2328340''>things.</span> </p><p><span m=''2329140''>So
  the</span> <span m=''2329220''>number</span> <span m=''2329400''>of</span> <span
  m=''2329470''>creases</span> <span m=''2329850''>becomes</span> <span m=''2330170''>proportional</span>
  <span m=''2330660''>to</span> <span m=''2330740''>the</span> <span m=''2330790''>number</span>
  <span m=''2331010''>of</span> <span m=''2331070''>disks.</span> <span m=''2331470''>The
  number</span> <span m=''2331740''>of disks</span> <span m=''2332170''>is this</span>
  <span m=''2332470''>messy</span> <span m=''2332810''>thing.</span> <span m=''2335190''>So</span>
  <span m=''2336180''>that''s</span> <span m=''2336540''>that.</span> <span m=''2337840''>Let''s</span>
  <span m=''2338010''>see,</span> <span m=''2338150''>what</span> <span m=''2338320''>else?</span>
  <span m=''2339700''>Here,</span> <span m=''2339950''>we</span> <span m=''2340090''>only</span>
  <span m=''2340320''>use</span> <span m=''2340530''>disks.</span> <span m=''2341320''>Over</span>
  <span m=''2341560''>here,</span> <span m=''2342160''>we</span> <span m=''2342310''>could</span>
  <span m=''2342520''>just</span> <span m=''2342700''>use</span> <span m=''2342850''>disks,</span>
  <span m=''2343070''>but</span> <span m=''2343400''>there''s</span> <span m=''2343600''>also</span>
  <span m=''2343910''>the</span> <span m=''2344030''>ability</span> <span m=''2344410''>to</span>
  <span m=''2344510''>use</span> <span m=''2344640''>rivers,</span> <span m=''2345040''>so</span>
  <span m=''2345130''>this</span> <span m=''2345320''>is</span> <span m=''2345460''>more</span>
  <span m=''2345670''>general</span> <span m=''2347090''>in that</span> <span m=''2347610''>we</span>
  <span m=''2347720''>can</span> <span m=''2347850''>do</span> <span m=''2348380''>bigger</span>
  <span m=''2349120''>polygons</span> <span m=''2349630''>than''</span> <span m=''2349720''>just</span>
  <span m=''2349890''>quads,</span> <span m=''2351220''>and</span> <span m=''2351720''>we</span>
  <span m=''2351950''>can</span> <span m=''2352230''>do</span> <span m=''2352410''>rivers,</span>
  <span m=''2352850''>not</span> <span m=''2353070''>just</span> <span m=''2354120''>circles.</span>
  <span m=''2354620''>Here,</span> <span m=''2354870''>the</span> <span m=''2355010''>input,</span>
  <span m=''2355440''>though,</span> <span m=''2355680''>is</span> <span m=''2355970''>a</span>
  <span m=''2356140''>tree</span> <span m=''2356540''>with</span> <span m=''2356660''>specified</span>
  <span m=''2357130''>lengths,</span> <span m=''2358310''>and</span> <span m=''2358540''>it''s</span>
  <span m=''2358670''>actually</span> <span m=''2359920''>NP-hard</span> <span m=''2360750''>to</span>
  <span m=''2361620''>place</span> <span m=''2362030''>the</span> <span m=''2362130''>disks</span>
  <span m=''2362840''>correctly.</span> <span m=''2363780''>We</span> <span m=''2364060''>proved</span>
  <span m=''2364330''>that</span> <span m=''2364530''>last</span> <span m=''2364950''>time.</span>
  <span m=''2366190''>Over</span> <span m=''2366470''>here,</span> <span m=''2367460''>the</span>
  <span m=''2367680''>input</span> <span m=''2368160''>is</span> <span m=''2368520''>a</span>
  <span m=''2368580''>polygon.</span> </p><p><span m=''2369350''>It''s</span> <span
  m=''2369530''>already</span> <span m=''2369900''>been</span> <span m=''2370060''>embedded</span>
  <span m=''2370480''>on</span> <span m=''2370590''>the</span> <span m=''2370660''>sheet</span>
  <span m=''2370880''>of</span> <span m=''2370960''>paper.</span> <span m=''2371250''>There''s</span>
  <span m=''2371580''>no</span> <span m=''2371770''>really</span> <span m=''2372000''>hard</span>
  <span m=''2372300''>decisions</span> <span m=''2372830''>here</span> <span m=''2373030''>except</span>
  <span m=''2373710''>you</span> <span m=''2373830''>have</span> <span m=''2373920''>to</span>
  <span m=''2374020''>fill</span> <span m=''2374900''>the</span> <span m=''2375100''>paper</span>
  <span m=''2375520''>with</span> <span m=''2375740''>disks.</span> <span m=''2376810''>But</span>
  <span m=''2377070''>that''s</span> <span m=''2377310''>not</span> <span m=''2377680''>so</span>
  <span m=''2377850''>hard.</span> <span m=''2379050''>So</span> <span m=''2379180''>you</span>
  <span m=''2379370''>can</span> <span m=''2379750''>do</span> <span m=''2379880''>this</span>
  <span m=''2380070''>in</span> <span m=''2380160''>polynomial</span> <span m=''2380650''>time.</span>
  <span m=''2380880''>Polynomial</span> <span m=''2381490''>and</span> <span m=''2382540''>even,</span>
  <span m=''2382810''>almost,</span> <span m=''2384150''>roughly</span> <span m=''2384580''>this</span>
  <span m=''2384820''>time.</span> <span m=''2385740''>Times</span> <span m=''2385990''>a</span>
  <span m=''2386040''>log</span> <span m=''2386310''>factor.</span> <span m=''2388220''>You</span>
  <span m=''2388410''>can</span> <span m=''2388940''>find</span> <span m=''2389430''>displacement</span>
  <span m=''2389990''>of</span> <span m=''2390100''>disks.</span> <span m=''2391090''>So</span>
  <span m=''2391120''>that''s</span> <span m=''2391360''>not</span> <span m=''2391500''>too</span>
  <span m=''2391610''>hard,</span> <span m=''2391880''>whereas</span> <span m=''2392130''>over</span>
  <span m=''2392320''>here,</span> <span m=''2392500''>it''s</span> <span m=''2392620''>NP-hard</span>
  <span m=''2393080''>to</span> <span m=''2393150''>place</span> <span m=''2393430''>a</span>
  <span m=''2393490''>disk,</span> <span m=''2394200''>optimally</span> <span m=''2394700''>at</span>
  <span m=''2394780''>least.</span> <span m=''2395810''>Find</span> <span m=''2396010''>a</span>
  <span m=''2396160''>displacement</span> <span m=''2396800''>you</span> <span m=''2396930''>could</span>
  <span m=''2397110''>do.</span> </p><p><span m=''2398250''>So</span> <span m=''2398410''>basically</span>
  <span m=''2398760''>the</span> <span m=''2398880''>inputs</span> <span m=''2399250''>differ,</span>
  <span m=''2399590''>and</span> <span m=''2399940''>it''s</span> <span m=''2400220''>using</span>
  <span m=''2400560''>the</span> <span m=''2400660''>same</span> <span m=''2404140''>backbone</span>
  <span m=''2404900''>or</span> <span m=''2404990''>the</span> <span m=''2405120''>same,</span>
  <span m=''2406020''>what do</span> <span m=''2406200''>you</span> <span m=''2406310''>call
  it,</span> <span m=''2407750''>front</span> <span m=''2408100''>end.</span> <span
  m=''2408310''>The</span> <span m=''2408380''>same</span> <span m=''2408590''>back</span>
  <span m=''2408940''>end, I</span> <span m=''2409290''>suppose,</span> <span m=''2411360''>after</span>
  <span m=''2411670''>we''ve</span> <span m=''2411780''>decomposed</span> <span m=''2412330''>into</span>
  <span m=''2412540''>a</span> <span m=''2412590''>bunch</span> <span m=''2412820''>of</span>
  <span m=''2412880''>molecules,</span> <span m=''2413370''>you</span> <span m=''2413450''>just</span>
  <span m=''2413620''>fold</span> <span m=''2413800''>the</span> <span m=''2413860''>molecules</span>
  <span m=''2414400''>and</span> <span m=''2414480''>you''re</span> <span m=''2414590''>basically</span>
  <span m=''2415030''>done.</span> <span m=''2415280''>Here</span> <span m=''2415480''>we</span>
  <span m=''2415530''>have</span> <span m=''2415620''>to</span> <span m=''2415680''>do</span>
  <span m=''2415780''>some</span> <span m=''2415960''>syncs</span> <span m=''2416290''>at</span>
  <span m=''2416390''>the</span> <span m=''2416510''>end,</span> <span m=''2417240''>but
  it''s</span> <span m=''2417620''>using</span> <span m=''2417900''>it</span> <span
  m=''2418000''>for</span> <span m=''2418090''>different</span> <span m=''2418380''>purposes.</span>
  <span m=''2419160''>Otherwise</span> <span m=''2419550''>they''re</span> <span m=''2419750''>very</span>
  <span m=''2419970''>similar.</span> <span m=''2420750''>And</span> <span m=''2420930''>indeed,</span>
  <span m=''2421180''>this</span> <span m=''2421390''>is</span> <span m=''2421510''>inspired</span>
  <span m=''2422010''>by</span> <span m=''2422920''>that.</span> </p><p><span m=''2425130''>OK,</span>
  <span m=''2425410''>so</span> <span m=''2425550''>that was</span> <span m=''2425830''>the</span>
  <span m=''2425870''>disk-packing</span> <span m=''2426400''>method.</span> <span
  m=''2427420''>Then</span> <span m=''2427620''>there''s</span> <span m=''2427820''>the</span>
  <span m=''2427930''>straight</span> <span m=''2428180''>skeleton</span> <span m=''2428630''>method.</span>
  <span m=''2428940''>These</span> <span m=''2429190''>look</span> <span m=''2429460''>much</span>
  <span m=''2429810''>more</span> <span m=''2430020''>different,</span> <span m=''2431060''>but</span>
  <span m=''2431210''>in</span> <span m=''2431300''>fact,</span> <span m=''2431520''>they</span>
  <span m=''2431660''>are</span> <span m=''2431840''>quite</span> <span m=''2432330''>related.</span>
  <span m=''2433050''>If</span> <span m=''2433130''>you</span> <span m=''2433620''>do</span>
  <span m=''2433830''>fold-and-cut</span> <span m=''2434520''>on</span> <span m=''2434670''>a</span>
  <span m=''2434730''>convex</span> <span m=''2435210''>polygon,</span> <span m=''2437090''>it</span>
  <span m=''2437350''>gives</span> <span m=''2437560''>you</span> <span m=''2437720''>roughly</span>
  <span m=''2438150''>the</span> <span m=''2438250''>universal</span> <span m=''2438690''>molecule,</span>
  <span m=''2439150''>just</span> <span m=''2439370''>with</span> <span m=''2439500''>no</span>
  <span m=''2439700''>gussets.</span> <span m=''2441270''>So</span> <span m=''2441670''>here,</span>
  <span m=''2442410''>neither</span> <span m=''2442880''>one</span> <span m=''2443050''>is</span>
  <span m=''2443170''>more</span> <span m=''2443340''>general</span> <span m=''2443660''>than</span>
  <span m=''2443780''>the</span> <span m=''2443930''>other.</span> <span m=''2444170''>The</span>
  <span m=''2444290''>universal</span> <span m=''2444720''>molecule</span> <span m=''2445140''>is</span>
  <span m=''2445240''>more</span> <span m=''2445470''>general</span> <span m=''2445880''>in
  that</span> <span m=''2446100''>it</span> <span m=''2446160''>has</span> <span m=''2446420''>gussets,</span>
  <span m=''2446860''>which</span> <span m=''2447060''>lets</span> <span m=''2447250''>it</span>
  <span m=''2447390''>control</span> <span m=''2447850''>the</span> <span m=''2447930''>tree</span>
  <span m=''2448390''>topology</span> <span m=''2448705''>you</span> <span m=''2449020''>get</span>
  <span m=''2449250''>and</span> <span m=''2449470''>control</span> <span m=''2449790''>the</span>
  <span m=''2449860''>lengths</span> <span m=''2450220''>you</span> <span m=''2450320''>get</span>
  <span m=''2450540''>in</span> <span m=''2450630''>the</span> <span m=''2450730''>tree.</span>
  </p><p><span m=''2451710''>Over</span> <span m=''2451920''>here,</span> <span m=''2452190''>we</span>
  <span m=''2452300''>saw</span> <span m=''2452840''>the</span> <span m=''2453020''>tree</span>
  <span m=''2453300''>just</span> <span m=''2453510''>happens.</span> <span m=''2454540''>You</span>
  <span m=''2454660''>can''t</span> <span m=''2454940''>control</span> <span m=''2455320''>the</span>
  <span m=''2455410''>tree.</span> <span m=''2457980''>The</span> <span m=''2458300''>shadow</span>
  <span m=''2458640''>tree</span> <span m=''2459100''>is</span> <span m=''2459240''>just
  a</span> <span m=''2459310''>tool</span> <span m=''2459530''>to</span> <span m=''2459610''>prove</span>
  <span m=''2459840''>that</span> <span m=''2459950''>it</span> <span m=''2460030''>falls</span>
  <span m=''2460240''>flat,</span> <span m=''2460860''>but</span> <span m=''2461080''>you</span>
  <span m=''2461200''>can</span> <span m=''2461330''>do</span> <span m=''2461430''>non</span>
  <span m=''2461690''>convex</span> <span m=''2462090''>polygons,</span> <span m=''2462600''>which</span>
  <span m=''2462780''>is</span> <span m=''2462900''>much</span> <span m=''2463120''>more</span>
  <span m=''2463280''>general</span> <span m=''2463700''>than</span> <span m=''2463880''>convex</span>
  <span m=''2464340''>polygons.</span> <span m=''2465400''>So</span> <span m=''2465570''>they</span>
  <span m=''2465710''>each</span> <span m=''2465850''>have</span> <span m=''2466030''>their</span>
  <span m=''2466220''>own</span> <span m=''2467840''>unique</span> <span m=''2468280''>claims</span>
  <span m=''2468620''>to</span> <span m=''2468710''>fame.</span> <span m=''2469630''>A</span>
  <span m=''2469850''>natural</span> <span m=''2470140''>question</span> <span m=''2470460''>is,</span>
  <span m=''2470630''>can</span> <span m=''2470840''>you</span> <span m=''2470970''>combine</span>
  <span m=''2471430''>them.</span> <span m=''2472010''>And</span> <span m=''2472270''>in</span>
  <span m=''2472360''>fact,</span> <span m=''2472610''>you</span> <span m=''2472700''>can.</span>
  </p><p><span m=''2473580''>And</span> <span m=''2473910''>this</span> <span m=''2474080''>was,</span>
  <span m=''2474660''>you</span> <span m=''2474780''>may</span> <span m=''2474940''>remember</span>
  <span m=''2476180''>a</span> <span m=''2476410''>bunch</span> <span m=''2476840''>of</span>
  <span m=''2476900''>lectures</span> <span m=''2477220''>ago--</span> <span m=''2477500''>I
  think</span> <span m=''2478230''>class</span> <span m=''2478650''>four</span> <span
  m=''2479010''>or so--</span> <span m=''2479990''>I</span> <span m=''2480060''>showed</span>
  <span m=''2480320''>this</span> <span m=''2480480''>slide</span> <span m=''2480900''>of</span>
  <span m=''2481220''>the</span> <span m=''2481980''>meat</span> <span m=''2482290''>of</span>
  <span m=''2482650''>origami</span> <span m=''2483100''>design</span> <span m=''2483440''>secrets</span>
  <span m=''2483860''>volume</span> <span m=''2484100''>two,</span> <span m=''2484980''>or</span>
  <span m=''2485340''>the</span> <span m=''2485390''>second</span> <span m=''2485630''>edition,</span>
  <span m=''2485940''>rather.</span> <span m=''2486950''>There''s</span> <span m=''2487280''>tree</span>
  <span m=''2487550''>theory,</span> <span m=''2487820''>which</span> <span m=''2487980''>we</span>
  <span m=''2488070''>talked</span> <span m=''2488320''>about.</span> <span m=''2489000''>There</span>
  <span m=''2489160''>was</span> <span m=''2489280''>a</span> <span m=''2489330''>box</span>
  <span m=''2489680''>pleating</span> <span m=''2489980''>tree</span> <span m=''2490220''>theory</span>
  <span m=''2490530''>which</span> <span m=''2490750''>we</span> <span m=''2490810''>briefly</span>
  <span m=''2491150''>showed.</span> <span m=''2491860''>And</span> <span m=''2491960''>there''s</span>
  <span m=''2492120''>this</span> <span m=''2492250''>more</span> <span m=''2492440''>general</span>
  <span m=''2492760''>thing</span> <span m=''2492920''>called</span> <span m=''2493100''>polygon</span>
  <span m=''2493540''>packing,</span> <span m=''2493910''>and</span> <span m=''2494020''>this</span>
  <span m=''2494200''>is</span> <span m=''2494340''>in</span> <span m=''2494460''>some</span>
  <span m=''2494710''>sense</span> <span m=''2495080''>the</span> <span m=''2495090''>fusion</span>
  <span m=''2495900''>of</span> <span m=''2497130''>straight</span> <span m=''2497390''>skeleton</span>
  <span m=''2497840''>method</span> <span m=''2498160''>of</span> <span m=''2498240''>fold-and-cut,</span>
  <span m=''2499180''>basically</span> <span m=''2499470''>the</span> <span m=''2499760''>straight</span>
  <span m=''2499920''>skeleton,</span> <span m=''2500740''>plus</span> <span m=''2502590''>tree</span>
  <span m=''2502860''>theory.</span> </p><p><span m=''2503840''>And</span> <span m=''2503980''>this</span>
  <span m=''2504130''>is</span> <span m=''2504250''>done</span> <span m=''2504690''>jointly</span>
  <span m=''2505050''>between</span> <span m=''2505970''>Robert</span> <span m=''2506250''>Lang</span>
  <span m=''2506530''>and</span> <span m=''2506880''>the</span> <span m=''2506960''>domains.</span>
  <span m=''2508170''>And</span> <span m=''2508450''>here''s</span> <span m=''2508680''>an</span>
  <span m=''2508800''>example</span> <span m=''2509430''>of</span> <span m=''2509960''>what</span>
  <span m=''2510100''>it</span> <span m=''2510180''>looks</span> <span m=''2510400''>like.</span>
  <span m=''2510640''>It''s a little</span> <span m=''2510860''>hard</span> <span
  m=''2511080''>to</span> <span m=''2511170''>see</span> <span m=''2511410''>here,</span>
  <span m=''2512040''>but</span> <span m=''2512250''>I</span> <span m=''2512340''>will</span>
  <span m=''2512510''>point</span> <span m=''2512790''>out</span> <span m=''2513550''>if</span>
  <span m=''2513670''>you</span> <span m=''2513790''>look</span> <span m=''2513920''>at</span>
  <span m=''2513980''>the</span> <span m=''2514070''>blue</span> <span m=''2514380''>lines,</span>
  <span m=''2514730''>which</span> <span m=''2514890''>are</span> <span m=''2515170''>the</span>
  <span m=''2515720''>cut</span> <span m=''2515970''>lines--</span> <span m=''2517630''>here,</span>
  <span m=''2517830''>of</span> <span m=''2517910''>course,</span> <span m=''2518220''>they''re</span>
  <span m=''2518440''>the</span> <span m=''2518790''>active</span> <span m=''2519360''>paths.</span>
  <span m=''2520570''>This</span> <span m=''2521200''>guy</span> <span m=''2522620''>is</span>
  <span m=''2522860''>non</span> <span m=''2523260''>convex.</span> <span m=''2525480''>And</span>
  <span m=''2525800''>if</span> <span m=''2525880''>you</span> <span m=''2526000''>look</span>
  <span m=''2526150''>at</span> <span m=''2526220''>the</span> <span m=''2526350''>red</span>
  <span m=''2526590''>stuff</span> <span m=''2526870''>in</span> <span m=''2526980''>there,</span>
  <span m=''2527680''>it</span> <span m=''2527830''>is</span> <span m=''2527960''>exactly</span>
  <span m=''2528510''>the</span> <span m=''2528630''>straight</span> <span m=''2529060''>skeleton</span>
  <span m=''2530190''>of</span> <span m=''2530370''>that</span> <span m=''2530610''>polygon.</span>
  <span m=''2532590''>So</span> <span m=''2532740''>those</span> <span m=''2533030''>red</span>
  <span m=''2533250''>lines</span> <span m=''2533580''>are the</span> <span m=''2533750''>straight</span>
  <span m=''2534010''>skeleton</span> <span m=''2534460''>of</span> <span m=''2534610''>this</span>
  <span m=''2534810''>blue</span> <span m=''2535650''>thing.</span> <span m=''2535860''>So</span>
  <span m=''2536010''>there</span> <span m=''2536200''>you</span> <span m=''2536310''>go.</span>
  <span m=''2536710''>I''ve</span> <span m=''2536910''>got</span> <span m=''2537260''>the</span>
  <span m=''2537850''>fold-and-cut</span> <span m=''2538530''>straight</span> <span
  m=''2538880''>skeleton</span> <span m=''2539290''>being</span> <span m=''2539530''>used</span>
  <span m=''2540840''>in</span> <span m=''2541000''>that</span> <span m=''2541210''>setting.</span>
  </p><p><span m=''2541550''>You''ve</span> <span m=''2541670''>got</span> <span m=''2541850''>perpendiculars</span>
  <span m=''2542420''>all</span> <span m=''2542700''>over</span> <span m=''2542820''>the</span>
  <span m=''2542920''>place,</span> <span m=''2543380''>which</span> <span m=''2543860''>is</span>
  <span m=''2544320''>an</span> <span m=''2544780''>annoying</span> <span m=''2545070''>feature
  of the</span> <span m=''2545440''>skeleton</span> <span m=''2545710''>method.</span>
  <span m=''2546090''>It</span> <span m=''2546190''>is</span> <span m=''2546310''>inherited</span>
  <span m=''2546820''>by</span> <span m=''2546940''>this</span> <span m=''2547140''>method.</span>
  <span m=''2547940''>And</span> <span m=''2548150''>if</span> <span m=''2548240''>you</span>
  <span m=''2548370''>look</span> <span m=''2548540''>at</span> <span m=''2548630''>something</span>
  <span m=''2548900''>like</span> <span m=''2550620''>this</span> <span m=''2552000''>rectangle.</span>
  <span m=''2553110''>It''s</span> <span m=''2553330''>convex,</span> <span m=''2554730''>but</span>
  <span m=''2554900''>you</span> <span m=''2555000''>have</span> <span m=''2555210''>gussets.</span>
  <span m=''2555920''>This</span> <span m=''2556080''>is</span> <span m=''2556220''>a</span>
  <span m=''2556290''>gusset,</span> <span m=''2556780''>this</span> <span m=''2556960''>is</span>
  <span m=''2557100''>a</span> <span m=''2557170''>gusset,</span> <span m=''2557660''>gusset,</span>
  <span m=''2558100''>gusset.</span> <span m=''2558490''>It''s a little</span> <span
  m=''2558690''>hard</span> <span m=''2558890''>to</span> <span m=''2558970''>see,</span>
  <span m=''2559550''>but</span> <span m=''2560490''>we</span> <span m=''2560630''>basically</span>
  <span m=''2560940''>split</span> <span m=''2561330''>the</span> <span m=''2561420''>rectangle</span>
  <span m=''2561880''>into</span> <span m=''2562030''>this</span> <span m=''2562230''>rectangle,</span>
  <span m=''2562720''>this</span> <span m=''2562830''>square,</span> <span m=''2563870''>this</span>
  <span m=''2564090''>rectangle,</span> <span m=''2565180''>this</span> <span m=''2565320''>square,</span>
  <span m=''2566280''>this</span> <span m=''2566570''>rectangle.</span> </p><p><span
  m=''2568510''>So</span> <span m=''2568770''>this</span> <span m=''2569010''>is</span>
  <span m=''2569140''>really</span> <span m=''2569340''>the</span> <span m=''2569440''>fusion</span>
  <span m=''2569810''>of</span> <span m=''2569920''>the</span> <span m=''2570010''>two.</span>
  <span m=''2570980''>It''s</span> <span m=''2571150''>not</span> <span m=''2571480''>yet</span>
  <span m=''2571710''>been</span> <span m=''2571890''>mathematically</span> <span
  m=''2572580''>formalized,</span> <span m=''2573100''>because</span> <span m=''2573260''>we''re</span>
  <span m=''2573370''>first</span> <span m=''2573810''>proving</span> <span m=''2574120''>that</span>
  <span m=''2574240''>the</span> <span m=''2574340''>tree</span> <span m=''2574530''>method</span>
  <span m=''2574810''>works.</span> <span m=''2575090''>Then</span> <span m=''2575360''>we</span>
  <span m=''2575440''>will</span> <span m=''2575650''>finally</span> <span m=''2576030''>get</span>
  <span m=''2576220''>to</span> <span m=''2576310''>this.</span> <span m=''2576870''>But</span>
  <span m=''2577090''>if</span> <span m=''2577210''>you</span> <span m=''2577330''>want</span>
  <span m=''2577610''>these</span> <span m=''2578370''>slightly</span> <span m=''2578900''>more</span>
  <span m=''2579130''>informal</span> <span m=''2579610''>but</span> <span m=''2579740''>practical</span>
  <span m=''2580160''>version,</span> <span m=''2581010''>read</span> <span m=''2582200''><i>Oragami</i></span>
  <span m=''2582580''><i>Design</i></span> <span m=''2582850''><i>Secrets</i></span>
  <span m=''2583240''>and it will</span> <span m=''2583590''>explain</span> <span
  m=''2584170''>all</span> <span m=''2584370''>the</span> <span m=''2584430''>different</span>
  <span m=''2584680''>cases</span> <span m=''2585200''>and</span> <span m=''2585300''>what</span>
  <span m=''2585400''>we</span> <span m=''2585500''>believe</span> <span m=''2585750''>is</span>
  <span m=''2585860''>a</span> <span m=''2585920''>correct</span> <span m=''2586190''>algorithm.</span>
  <span m=''2586710''>We</span> <span m=''2586810''>just</span> <span m=''2586900''>haven''t</span>
  <span m=''2587680''>proved</span> <span m=''2588060''>all</span> <span m=''2588150''>the</span>
  <span m=''2588240''>cases</span> <span m=''2589040''>yet.</span> <span m=''2589880''>And</span>
  <span m=''2590090''>you</span> <span m=''2590170''>can</span> <span m=''2590300''>use</span>
  <span m=''2590460''>it</span> <span m=''2590610''>to</span> <span m=''2590720''>design</span>
  <span m=''2591470''>cool</span> <span m=''2591660''>things</span> <span m=''2591920''>in</span>
  <span m=''2592070''>the</span> <span m=''2592160''>box</span> <span m=''2592470''>pleating</span>
  <span m=''2593200''>setting</span> <span m=''2593610''>and</span> <span m=''2593730''>get</span>
  <span m=''2593930''>more</span> <span m=''2594190''>efficient</span> <span m=''2594620''>than</span>
  <span m=''2594760''>if</span> <span m=''2594870''>you</span> <span m=''2595010''>required</span>
  <span m=''2595470''>rectangles</span> <span m=''2596160''>or</span> <span m=''2596240''>some</span>
  <span m=''2596420''>convex</span> <span m=''2597240''>shape.</span> <span m=''2599660''>Cool.</span>
  </p><p><span m=''2600230''>So</span> <span m=''2600480''>that''s</span> <span m=''2600870''>that.</span>
  <span m=''2603700''>What else do</span> <span m=''2603910''>we</span> <span m=''2603990''>have?</span>
  <span m=''2610490''>I</span> <span m=''2610990''>have one--</span> <span m=''2611420''>almost</span>
  <span m=''2611750''>done--</span> <span m=''2612250''>one</span> <span m=''2612440''>cool</span>
  <span m=''2612660''>open</span> <span m=''2612880''>question</span> <span m=''2613410''>posed</span>
  <span m=''2613800''>by</span> <span m=''2614600''>you</span> <span m=''2615290''>is,</span>
  <span m=''2616080''>what</span> <span m=''2616360''>if</span> <span m=''2616480''>instead</span>
  <span m=''2616800''>of</span> <span m=''2616900''>cutting</span> <span m=''2617210''>with</span>
  <span m=''2617370''>a</span> <span m=''2617440''>straight</span> <span m=''2618400''>line,</span>
  <span m=''2618870''>I</span> <span m=''2619030''>cut</span> <span m=''2619320''>with</span>
  <span m=''2619550''>a</span> <span m=''2619670''>constant</span> <span m=''2620180''>curvature</span>
  <span m=''2620630''>line?</span> <span m=''2621400''>So</span> <span m=''2621590''>a</span>
  <span m=''2621650''>piece</span> <span m=''2621880''>of</span> <span m=''2622530''>a</span>
  <span m=''2622600''>circular</span> <span m=''2622980''>arc.</span> <span m=''2624170''>Then,</span>
  <span m=''2624320''>of</span> <span m=''2624410''>course,</span> <span m=''2624630''>the</span>
  <span m=''2624720''>things</span> <span m=''2624990''>I</span> <span m=''2625050''>get</span>
  <span m=''2625260''>will</span> <span m=''2625400''>have</span> <span m=''2625580''>circular</span>
  <span m=''2626010''>arc</span> <span m=''2626210''>boundaries,</span> <span m=''2626600''>but</span>
  <span m=''2626730''>can</span> <span m=''2626900''>I</span> <span m=''2626950''>get</span>
  <span m=''2627160''>any</span> <span m=''2627390''>circular</span> <span m=''2627830''>arc</span>
  <span m=''2628000''>boundary</span> <span m=''2628940''>with</span> <span m=''2629650''>that</span>
  <span m=''2629880''>fixed</span> <span m=''2630150''>curvature?</span> <span m=''2631190''>Or</span>
  <span m=''2631595''>are</span> <span m=''2632000''>there</span> <span m=''2632690''>limitations?</span>
  <span m=''2633680''>And</span> <span m=''2634080''>at</span> <span m=''2634220''>first</span>
  <span m=''2634470''>I</span> <span m=''2634520''>thought</span> <span m=''2634690''>the</span>
  <span m=''2634790''>answer</span> <span m=''2634960''>is</span> <span m=''2635050''>clearly</span>
  <span m=''2635420''>yes,</span> <span m=''2635850''>but</span> <span m=''2638740''>I</span>
  <span m=''2638880''>do</span> <span m=''2639060''>wonder</span> <span m=''2639540''>about</span>
  <span m=''2640330''>situations</span> <span m=''2640980''>like</span> <span m=''2642250''>this.</span>
  </p><p><span m=''2644870''>Can</span> <span m=''2645000''>you</span> <span m=''2645240''>align</span>
  <span m=''2645620''>these</span> <span m=''2645870''>two</span> <span m=''2646090''>by</span>
  <span m=''2646290''>folding?</span> <span m=''2648190''>I haven''t</span> <span
  m=''2648370''>thought</span> <span m=''2648540''>about it</span> <span m=''2648770''>enough</span>
  <span m=''2649340''>to</span> <span m=''2649470''>be</span> <span m=''2649590''>sure,</span>
  <span m=''2650470''>but</span> <span m=''2651250''>not</span> <span m=''2651470''>totally</span>
  <span m=''2651750''>sure.</span> <span m=''2651950''>Whereas</span> <span m=''2652650''>if</span>
  <span m=''2652790''>I</span> <span m=''2652870''>have</span> <span m=''2653090''>things</span>
  <span m=''2653400''>like</span> <span m=''2656180''>this,</span> <span m=''2657460''>I</span>
  <span m=''2657580''>think</span> <span m=''2657720''>this</span> <span m=''2658410''>is</span>
  <span m=''2658540''>good.</span> <span m=''2658750''>I</span> <span m=''2658770''>mean,</span>
  <span m=''2658930''>I</span> <span m=''2658990''>could</span> <span m=''2659140''>fold</span>
  <span m=''2659410''>here,</span> <span m=''2659830''>and</span> <span m=''2659970''>in</span>
  <span m=''2660050''>general,</span> <span m=''2660380''>I</span> <span m=''2660450''>could</span>
  <span m=''2660620''>just</span> <span m=''2660930''>kind</span> <span m=''2661090''>of</span>
  <span m=''2661160''>pretend</span> <span m=''2661740''>there''s</span> <span m=''2661950''>a</span>
  <span m=''2662020''>segment.</span> <span m=''2662870''>And</span> <span m=''2662950''>the</span>
  <span m=''2663030''>segment</span> <span m=''2663490''>I</span> <span m=''2663560''>saw
  fold and</span> <span m=''2664100''>cut</span> <span m=''2664250''>on</span> <span
  m=''2664340''>the</span> <span m=''2664430''>segments,</span> <span m=''2664930''>and</span>
  <span m=''2665010''>that</span> <span m=''2665140''>will</span> <span m=''2665220''>also</span>
  <span m=''2665570''>align</span> <span m=''2665750''>the</span> <span m=''2665870''>circular</span>
  <span m=''2666200''>arc.</span> <span m=''2666400''>That</span> <span m=''2666540''>won''t</span>
  <span m=''2666670''>work</span> <span m=''2666860''>in</span> <span m=''2666960''>general,</span>
  <span m=''2667350''>but</span> <span m=''2668130''>I</span> <span m=''2668210''>feel</span>
  <span m=''2668400''>comfortable</span> <span m=''2668880''>if</span> <span m=''2668960''>they</span>
  <span m=''2669060''>have</span> <span m=''2669220''>the</span> <span m=''2669300''>same</span>
  <span m=''2669540''>orientation,</span> <span m=''2669970''>it</span> <span m=''2670030''>looks</span>
  <span m=''2670250''>good.</span> <span m=''2670580''>When</span> <span m=''2670710''>they</span>
  <span m=''2670830''>flip</span> <span m=''2671110''>orientations,</span> <span m=''2671660''>I''m</span>
  <span m=''2671770''>not</span> <span m=''2671980''>sure.</span> <span m=''2672940''>So</span>
  <span m=''2673650''>a neat</span> <span m=''2673870''>problem</span> <span m=''2674190''>to</span>
  <span m=''2674310''>think</span> <span m=''2674480''>about.</span> </p><p><span
  m=''2675820''>And</span> <span m=''2678600''>one</span> <span m=''2679780''>final</span>
  <span m=''2680050''>thing</span> <span m=''2680220''>is</span> <span m=''2680320''>about</span>
  <span m=''2680750''>flattening.</span> <span m=''2681300''>This</span> <span m=''2681460''>is</span>
  <span m=''2681650''>about</span> <span m=''2682000''>this</span> <span m=''2682270''>question,</span>
  <span m=''2683100''>this</span> <span m=''2683280''>picture.</span> <span m=''2684240''>So</span>
  <span m=''2684350''>we</span> <span m=''2684420''>said,</span> <span m=''2684840''>oh</span>
  <span m=''2684970''>great,</span> <span m=''2685530''>because</span> <span m=''2685780''>we</span>
  <span m=''2685900''>can</span> <span m=''2686010''>solve</span> <span m=''2686270''>fold-and-cut,</span>
  <span m=''2686890''>we</span> <span m=''2687060''>can</span> <span m=''2687280''>also</span>
  <span m=''2687520''>take</span> <span m=''2687720''>the</span> <span m=''2687790''>boundary</span>
  <span m=''2688180''>of that</span> <span m=''2688350''>polygon</span> <span m=''2688870''>and</span>
  <span m=''2689040''>flatten</span> <span m=''2689510''>it</span> <span m=''2690050''>like</span>
  <span m=''2690270''>this.</span> <span m=''2692180''>Of</span> <span m=''2692290''>course,</span>
  <span m=''2692590''>the</span> <span m=''2692690''>folding</span> <span m=''2693320''>of</span>
  <span m=''2693420''>the</span> <span m=''2693560''>interior</span> <span m=''2694130''>here</span>
  <span m=''2694370''>which</span> <span m=''2694530''>we''re</span> <span m=''2694730''>ignoring--</span>
  <span m=''2695660''>in</span> <span m=''2695790''>general,</span> <span m=''2696080''>this</span>
  <span m=''2696220''>whole</span> <span m=''2696460''>thing</span> <span m=''2696870''>goes</span>
  <span m=''2697170''>through</span> <span m=''2697310''>three</span> <span m=''2697540''>dimensions</span>
  <span m=''2698610''>until</span> <span m=''2698910''>we</span> <span m=''2699030''>end</span>
  <span m=''2699230''>up</span> <span m=''2699380''>here.</span> <span m=''2700110''>One</span>
  <span m=''2700340''>dimension</span> <span m=''2700850''>up,</span> <span m=''2701110''>if</span>
  <span m=''2701240''>we</span> <span m=''2701330''>solve</span> <span m=''2701550''>the</span>
  <span m=''2701640''>3D</span> <span m=''2702050''>fold-and-cut</span> <span m=''2702520''>problem</span>
  <span m=''2702800''>where you</span> <span m=''2702940''>have</span> <span m=''2703080''>a</span>
  <span m=''2703150''>polyhedron,</span> <span m=''2704120''>you</span> <span m=''2704220''>fold</span>
  <span m=''2704560''>it through</span> <span m=''2704770''>4D</span> <span m=''2705800''>back</span>
  <span m=''2706330''>into</span> <span m=''2706560''>3D</span> <span m=''2706930''>which</span>
  <span m=''2707090''>is</span> <span m=''2707190''>flat</span> <span m=''2707620''>so</span>
  <span m=''2707740''>that</span> <span m=''2707870''>you</span> <span m=''2708110''>align</span>
  <span m=''2708470''>all</span> <span m=''2708570''>the</span> <span m=''2708650''>boundaries</span>
  <span m=''2709190''>of</span> <span m=''2709480''>the</span> <span m=''2710640''>faces</span>
  <span m=''2711350''>of</span> <span m=''2711540''>that</span> <span m=''2711740''>polyhedron.</span>
  </p><p><span m=''2714220''>And</span> <span m=''2714390''>then</span> <span m=''2714520''>just</span>
  <span m=''2714690''>take</span> <span m=''2714860''>the</span> <span m=''2714930''>boundary</span>
  <span m=''2715350''>of</span> <span m=''2715430''>that</span> <span m=''2715620''>motion.</span>
  <span m=''2716040''>It''s</span> <span m=''2716250''>like</span> <span m=''2716450''>flattening</span>
  <span m=''2716930''>a</span> <span m=''2716980''>polyhedron</span> <span m=''2717790''>like</span>
  <span m=''2718050''>cereal</span> <span m=''2718330''>box</span> <span m=''2718640''>or</span>
  <span m=''2718690''>whatever.</span> <span m=''2719960''>And</span> <span m=''2720640''>indeed,</span>
  <span m=''2721030''>that</span> <span m=''2721220''>will</span> <span m=''2721370''>find</span>
  <span m=''2722040''>a</span> <span m=''2722170''>folded</span> <span m=''2722740''>state</span>
  <span m=''2723510''>of</span> <span m=''2723790''>a</span> <span m=''2724680''>polyhedron</span>
  <span m=''2726140''>that is</span> <span m=''2726460''>flat.</span> <span m=''2727630''>But</span>
  <span m=''2727770''>of</span> <span m=''2727840''>course,</span> <span m=''2728810''>you</span>
  <span m=''2728930''>can''t</span> <span m=''2729630''>really</span> <span m=''2729820''>use</span>
  <span m=''2729960''>that</span> <span m=''2730120''>motion,</span> <span m=''2730480''>because</span>
  <span m=''2730740''>it</span> <span m=''2730820''>goes</span> <span m=''2731010''>through</span>
  <span m=''2731190''>4D.</span> <span m=''2731910''>This</span> <span m=''2732070''>one
  will</span> <span m=''2732260''>go</span> <span m=''2732400''>through</span> <span
  m=''2732550''>3D,</span> <span m=''2733070''>so</span> <span m=''2733600''>if you</span>
  <span m=''2734020''>want it</span> <span m=''2734270''>to</span> <span m=''2734410''>flatten</span>
  <span m=''2734750''>this</span> <span m=''2734930''>linkage,</span> <span m=''2735450''>that''s</span>
  <span m=''2736150''>also</span> <span m=''2736400''>not</span> <span m=''2736620''>valid.</span>
  <span m=''2737960''>So</span> <span m=''2738000''>you</span> <span m=''2738100''>get</span>
  <span m=''2738210''>a</span> <span m=''2738260''>folded</span> <span m=''2738580''>state,</span>
  <span m=''2738970''>but</span> <span m=''2739070''>you</span> <span m=''2739150''>don''t</span>
  <span m=''2739300''>get</span> <span m=''2739420''>the</span> <span m=''2739500''>folding</span>
  <span m=''2739790''>motion</span> <span m=''2740740''>if</span> <span m=''2740900''>you</span>
  <span m=''2741000''>could</span> <span m=''2741150''>solve</span> <span m=''2741370''>3D</span>
  <span m=''2741620''>fold-and-cut.</span> </p><p><span m=''2743170''>Our</span> <span
  m=''2743310''>current</span> <span m=''2743560''>state</span> <span m=''2743790''>is,</span>
  <span m=''2743930''>we</span> <span m=''2744060''>don''t</span> <span m=''2744230''>know</span>
  <span m=''2744300''>how</span> <span m=''2744420''>to</span> <span m=''2744490''>solve</span>
  <span m=''2744755''>3D</span> <span m=''2745020''>fold-and-cut.</span> <span m=''2745920''>We</span>
  <span m=''2746090''>do</span> <span m=''2746270''>know</span> <span m=''2746440''>how</span>
  <span m=''2746580''>to</span> <span m=''2746680''>solve</span> <span m=''2747310''>polyhedron</span>
  <span m=''2747800''>flattening.</span> <span m=''2748230''>So</span> <span m=''2748370''>this</span>
  <span m=''2749380''>relation</span> <span m=''2749800''>is</span> <span m=''2749980''>just
  kind</span> <span m=''2750150''>of</span> <span m=''2750420''>interest,</span> <span
  m=''2751495''>it</span> <span m=''2751820''>doesn''t</span> <span m=''2752060''>imply</span>
  <span m=''2752410''>anything</span> <span m=''2752990''>super</span> <span m=''2753260''>useful.</span>
  <span m=''2755200''>An</span> <span m=''2755340''>open</span> <span m=''2755590''>problem</span>
  <span m=''2755930''>is,</span> <span m=''2756800''>so</span> <span m=''2756930''>we</span>
  <span m=''2757020''>know</span> <span m=''2757120''>how</span> <span m=''2757220''>to</span>
  <span m=''2757340''>solve</span> <span m=''2757730''>polyhedron</span> <span m=''2758060''>flattening</span>
  <span m=''2759000''>as</span> <span m=''2759180''>a</span> <span m=''2759230''>folded</span>
  <span m=''2759550''>state.</span> <span m=''2759930''>What</span> <span m=''2760050''>we</span>
  <span m=''2760160''>don''t</span> <span m=''2760390''>know</span> <span m=''2760530''>so</span>
  <span m=''2760690''>much</span> <span m=''2760910''>about</span> <span m=''2761180''>is</span>
  <span m=''2761380''>folding</span> <span m=''2761680''>motions.</span> <span m=''2762180''>There</span>
  <span m=''2762360''>is</span> <span m=''2762460''>a</span> <span m=''2762540''>recent</span>
  <span m=''2762850''>paper</span> <span m=''2764060''>from</span> <span m=''2764280''>just</span>
  <span m=''2764590''>last</span> <span m=''2764880''>year</span> <span m=''2767010''>which</span>
  <span m=''2767680''>will</span> <span m=''2767900''>continuously</span> <span m=''2768670''>flatten</span>
  <span m=''2769190''>by</span> <span m=''2769360''>continuous</span> <span m=''2769990''>motion</span>
  <span m=''2771010''>any</span> <span m=''2771380''>convex</span> <span m=''2772000''>polyhedron.</span>
  <span m=''2772640''>But</span> <span m=''2772790''>non</span> <span m=''2772990''>convex</span>
  <span m=''2773330''>polyhedron</span> <span m=''2773790''>we</span> <span m=''2773900''>still</span>
  <span m=''2774240''>don''t know.</span> </p><p><span m=''2774890''>These</span>
  <span m=''2775150''>are</span> <span m=''2775760''>roughly</span> <span m=''2776100''>hand</span>
  <span m=''2776360''>drawn</span> <span m=''2776600''>figures.</span> <span m=''2777830''>An
  interesting</span> <span m=''2778260''>project</span> <span m=''2778650''>would</span>
  <span m=''2778810''>be</span> <span m=''2778950''>to</span> <span m=''2779040''>actually</span>
  <span m=''2779320''>animate</span> <span m=''2779740''>their</span> <span m=''2779840''>motion.</span>
  <span m=''2780650''>I</span> <span m=''2780760''>think</span> <span m=''2780940''>it
  would look</span> <span m=''2781110''>pretty</span> <span m=''2781320''>cool</span>
  <span m=''2781650''>and</span> <span m=''2781750''>be</span> <span m=''2782170''>much</span>
  <span m=''2782360''>more</span> <span m=''2782490''>convincing</span> <span m=''2783650''>that</span>
  <span m=''2783790''>it</span> <span m=''2783850''>works.</span> <span m=''2784630''>I</span>
  <span m=''2784710''>mean,</span> <span m=''2784910''>I''m</span> <span m=''2785170''>convinced</span>
  <span m=''2785450''>that</span> <span m=''2785550''>it</span> <span m=''2785600''>works,</span>
  <span m=''2785890''>but</span> <span m=''2786000''>it''s</span> <span m=''2786140''>a</span>
  <span m=''2786180''>lot</span> <span m=''2786330''>harder</span> <span m=''2786630''>to</span>
  <span m=''2786700''>see</span> <span m=''2786890''>visually</span> <span m=''2787320''>from</span>
  <span m=''2787450''>these</span> <span m=''2787610''>pictures.</span> <span m=''2788130''>It''d</span>
  <span m=''2788410''>be</span> <span m=''2788530''>really</span> <span m=''2788700''>cool</span>
  <span m=''2788890''>to</span> <span m=''2788980''>see</span> <span m=''2789170''>the</span>
  <span m=''2789990''>motions,</span> <span m=''2791050''>the</span> <span m=''2791410''>actual</span>
  <span m=''2791710''>continuous</span> <span m=''2792160''>animation.</span> <span
  m=''2793940''>And</span> <span m=''2796190''>a</span> <span m=''2796290''>couple</span>
  <span m=''2796710''>last</span> <span m=''2797110''>project</span> <span m=''2797540''>ideas.</span>
  <span m=''2797910''>One</span> <span m=''2798380''>would</span> <span m=''2798510''>be</span>
  <span m=''2798650''>to</span> <span m=''2798770''>make</span> <span m=''2798970''>a</span>
  <span m=''2799030''>fold-and-cut</span> <span m=''2799640''>alphabet,</span> <span
  m=''2800210''>like</span> <span m=''2800460''>the</span> <span m=''2800560''>maze</span>
  <span m=''2800790''>software</span> <span m=''2801290''>that</span> <span m=''2801420''>you</span>
  <span m=''2801560''>just</span> <span m=''2801790''>used.</span> <span m=''2802040''>It
  would</span> <span m=''2802160''>be</span> <span m=''2802290''>fun</span> <span
  m=''2802480''>if</span> <span m=''2802570''>you</span> <span m=''2802650''>just</span>
  <span m=''2802810''>type</span> <span m=''2803000''>in</span> <span m=''2803100''>a</span>
  <span m=''2803140''>message,</span> <span m=''2803810''>and</span> <span m=''2804110''>out</span>
  <span m=''2804380''>comes</span> <span m=''2804630''>the</span> <span m=''2804720''>crease</span>
  <span m=''2804950''>patterns.</span> <span m=''2805480''>This is</span> <span m=''2805580''>sort</span>
  <span m=''2805900''>of</span> <span m=''2805950''>like</span> <span m=''2806110''>a</span>
  <span m=''2806170''>special</span> <span m=''2806520''>case</span> <span m=''2806780''>of</span>
  <span m=''2806880''>a</span> <span m=''2806950''>fold-and-cut</span> <span m=''2807460''>design</span>
  <span m=''2807790''>tool,</span> <span m=''2808040''>but</span> <span m=''2808220''>in</span>
  <span m=''2808830''>letters</span> <span m=''2809210''>it''s</span> <span m=''2809340''>a</span>
  <span m=''2809390''>little</span> <span m=''2809610''>bit</span> <span m=''2809740''>easier.</span>
  </p><p><span m=''2811330''>And</span> <span m=''2811600''>a</span> <span m=''2812080''>different</span>
  <span m=''2812680''>challenge</span> <span m=''2813140''>would</span> <span m=''2813300''>be</span>
  <span m=''2813550''>if</span> <span m=''2813680''>I</span> <span m=''2813730''>just</span>
  <span m=''2814020''>want</span> <span m=''2814160''>to</span> <span m=''2814210''>be</span>
  <span m=''2814300''>able</span> <span m=''2814440''>to</span> <span m=''2814500''>fold</span>
  <span m=''2814890''>a single</span> <span m=''2815270''>letter</span> <span m=''2815550''>at</span>
  <span m=''2815610''>a</span> <span m=''2815690''>time,</span> <span m=''2816600''>can</span>
  <span m=''2816810''>you</span> <span m=''2816940''>always</span> <span m=''2817160''>do</span>
  <span m=''2817360''>it with</span> <span m=''2817420''>simple</span> <span m=''2817770''>folds?</span>
  <span m=''2818570''>So</span> <span m=''2818740''>can</span> <span m=''2818890''>you</span>
  <span m=''2818980''>design</span> <span m=''2819340''>an alphabet</span> <span m=''2819610''>that</span>
  <span m=''2819880''>is</span> <span m=''2819980''>simply</span> <span m=''2820450''>fold-and-cuttable.</span>
  <span m=''2821660''>That</span> <span m=''2821840''>would</span> <span m=''2821950''>be</span>
  <span m=''2822220''>even</span> <span m=''2822450''>nicer.</span> <span m=''2823020''>And</span>
  <span m=''2823300''>there''s</span> <span m=''2823460''>some</span> <span m=''2823630''>magicians</span>
  <span m=''2824060''>who</span> <span m=''2824150''>worked</span> <span m=''2824380''>on</span>
  <span m=''2824470''>that,</span> <span m=''2824630''>but</span> <span m=''2824720''>they</span>
  <span m=''2824800''>couldn''t</span> <span m=''2825040''>get</span> <span m=''2825170''>all</span>
  <span m=''2825280''>the</span> <span m=''2825350''>letters,</span> <span m=''2826190''>so</span>
  <span m=''2826470''>it would be</span> <span m=''2826590''>nice</span> <span m=''2826850''>to</span>
  <span m=''2826940''>do</span> <span m=''2827250''>with</span> <span m=''2827460''>just</span>
  <span m=''2827660''>a</span> <span m=''2827710''>few</span> <span m=''2827900''>folds,</span>
  <span m=''2828300''>any</span> <span m=''2828510''>letter</span> <span m=''2828740''>of</span>
  <span m=''2828800''>the</span> <span m=''2828890''>alphabet,</span> <span m=''2829520''>any</span>
  <span m=''2829690''>digit.</span> <span m=''2830420''>This</span> <span m=''2830600''>is</span>
  <span m=''2830700''>one</span> <span m=''2830860''>we</span> <span m=''2830960''>did</span>
  <span m=''2831120''>for</span> <span m=''2831280''>our</span> <span m=''2831380''>conference</span>
  <span m=''2831830''>in</span> <span m=''2832140''>honor of</span> <span m=''2832380''>Martin</span>
  <span m=''2832640''>Gardner,</span> <span m=''2832950''>gathering</span> <span m=''2833300''>for</span>
  <span m=''2833400''>Gardner</span> <span m=''2833670''>five,</span> <span m=''2834450''>back</span>
  <span m=''2834640''>in</span> <span m=''2834730''>2002.</span> </p><p><span m=''2837140''>And</span>
  <span m=''2837850''>here''s</span> <span m=''2838160''>another</span> <span m=''2838680''>possible</span>
  <span m=''2839090''>idea</span> <span m=''2839340''>for a</span> <span m=''2839500''>project,</span>
  <span m=''2840250''>although</span> <span m=''2840370''>mostly</span> <span m=''2840810''>it''s
  an</span> <span m=''2841075''>excuse</span> <span m=''2841340''>to</span> <span
  m=''2841430''>show</span> <span m=''2841600''>you</span> <span m=''2841760''>really</span>
  <span m=''2841980''>cool</span> <span m=''2842200''>pictures.</span> <span m=''2843040''>This</span>
  <span m=''2843260''>is</span> <span m=''2843410''>Peter</span> <span m=''2843630''>Callesen,</span>
  <span m=''2844560''>and</span> <span m=''2844730''>he</span> <span m=''2844920''>takes</span>
  <span m=''2845370''>usually</span> <span m=''2845900''>four</span> <span m=''2846230''>sheets</span>
  <span m=''2846500''>of</span> <span m=''2846580''>paper,</span> <span m=''2847550''>cuts</span>
  <span m=''2847860''>them</span> <span m=''2849180''>probably</span> <span m=''2849450''>an</span>
  <span m=''2849520''>X-ACTO</span> <span m=''2849900''>knife</span> <span m=''2850220''>or</span>
  <span m=''2850310''>something,</span> <span m=''2851130''>and</span> <span m=''2851310''>then</span>
  <span m=''2851680''>from</span> <span m=''2851980''>that</span> <span m=''2852160''>material</span>
  <span m=''2852710''>that</span> <span m=''2852850''>he</span> <span m=''2854740''>acquires,</span>
  <span m=''2855760''>builds</span> <span m=''2856170''>a</span> <span m=''2856300''>3D</span>
  <span m=''2856560''>structure</span> <span m=''2856960''>on</span> <span m=''2857140''>that</span>
  <span m=''2857340''>sheet.</span> <span m=''2857600''>So</span> <span m=''2857690''>you</span>
  <span m=''2857770''>see</span> <span m=''2858000''>all</span> <span m=''2858170''>the</span>
  <span m=''2858240''>material</span> <span m=''2858525''>that</span> <span m=''2858810''>was</span>
  <span m=''2858900''>used,</span> <span m=''2859620''>and</span> <span m=''2859790''>these</span>
  <span m=''2859970''>are</span> <span m=''2860040''>just</span> <span m=''2860310''>amazing.</span>
  <span m=''2862230''>And</span> <span m=''2863240''>I</span> <span m=''2863330''>don''t</span>
  <span m=''2863510''>think</span> <span m=''2863680''>you</span> <span m=''2863760''>could</span>
  <span m=''2864060''>necessarily</span> <span m=''2864520''>do</span> <span m=''2864650''>this</span>
  <span m=''2864940''>level</span> <span m=''2865230''>of</span> <span m=''2865310''>fidelity</span>
  <span m=''2865900''>from</span> <span m=''2866120''>a</span> <span m=''2866190''>fold-and-cut</span>
  <span m=''2866530''>,</span> <span m=''2866910''>but</span> <span m=''2867030''>it</span>
  <span m=''2867090''>would</span> <span m=''2867260''>be</span> <span m=''2867420''>cool</span>
  <span m=''2867750''>to</span> <span m=''2868060''>do</span> <span m=''2868210''>a</span>
  <span m=''2868270''>fold-and-cut</span> <span m=''2868820''>and</span> <span m=''2868920''>then</span>
  <span m=''2869040''>build</span> <span m=''2869310''>a</span> <span m=''2869360''>sculpture</span>
  <span m=''2869910''>out</span> <span m=''2870130''>of</span> <span m=''2870310''>the</span>
  <span m=''2871080''>slits</span> <span m=''2871400''>that you</span> <span m=''2871560''>made.</span>
  </p><p><span m=''2874380''>And</span> <span m=''2874730''>I</span> <span m=''2874760''>mean,</span>
  <span m=''2874930''>it''s</span> <span m=''2875060''>really</span> <span m=''2875270''>cool</span>
  <span m=''2875500''>when</span> <span m=''2875620''>he</span> <span m=''2875730''>can</span>
  <span m=''2875860''>use</span> <span m=''2876280''>the</span> <span m=''2876510''>cutout</span>
  <span m=''2876890''>parts</span> <span m=''2877180''>to</span> <span m=''2877270''>be</span>
  <span m=''2877380''>shadows</span> <span m=''2877970''>of</span> <span m=''2878120''>the</span>
  <span m=''2878220''>things</span> <span m=''2878570''>that he</span> <span m=''2878720''>builds,</span>
  <span m=''2880250''>especially</span> <span m=''2880740''>when</span> <span m=''2880890''>those</span>
  <span m=''2881070''>shadows</span> <span m=''2881580''>are</span> <span m=''2881640''>more</span>
  <span m=''2881840''>complicated</span> <span m=''2882560''>than</span> <span m=''2882800''>the</span>
  <span m=''2883330''>sheet</span> <span m=''2883710''>he actually</span> <span m=''2883970''>assembles.</span>
  <span m=''2884410''>That''s</span> <span m=''2884660''>a</span> <span m=''2884710''>fairly</span>
  <span m=''2884980''>cool</span> <span m=''2885210''>effect</span> <span m=''2885520''>of</span>
  <span m=''2885660''>the</span> <span m=''2886410''>monsters</span> <span m=''2886850''>in</span>
  <span m=''2886920''>the</span> <span m=''2887010''>closet.</span> <span m=''2889190''>Pandora''s</span>
  <span m=''2889680''>box,</span> <span m=''2891110''>or</span> <span m=''2891240''>box</span>
  <span m=''2891520''>in a</span> <span m=''2891630''>box</span> <span m=''2891870''>in
  a</span> <span m=''2891950''>box.</span> <span m=''2892660''>You</span> <span m=''2892750''>can''t</span>
  <span m=''2892990''>see</span> <span m=''2893110''>that</span> <span m=''2893290''>here,</span>
  <span m=''2893520''>but</span> <span m=''2893830''>you</span> <span m=''2893960''>see</span>
  <span m=''2894170''>it</span> <span m=''2894570''>unfolding.</span> <span m=''2896290''>The</span>
  <span m=''2896850''>bones</span> <span m=''2897190''>inside</span> <span m=''2897580''>the</span>
  <span m=''2897640''>hand,</span> <span m=''2900400''>the</span> <span m=''2900860''>old</span>
  <span m=''2901260''>versus</span> <span m=''2901640''>new</span> <span m=''2901940''>cities.</span>
  <span m=''2905830''>Using</span> <span m=''2906110''>the</span> <span m=''2906210''>positive</span>
  <span m=''2906710''>and</span> <span m=''2906870''>the</span> <span m=''2906950''>negative.</span>
  <span m=''2907330''>There''s</span> <span m=''2907450''>actually</span> <span m=''2907710''>a</span>
  <span m=''2907760''>little</span> <span m=''2908360''>boat</span> <span m=''2908610''>up</span>
  <span m=''2908910''>there,</span> <span m=''2909603''>which</span> <span m=''2909966''>you
  can</span> <span m=''2910330''>see.</span> </p><p><span m=''2912360''>So</span>
  <span m=''2913150''>pretty</span> <span m=''2913470''>amazing</span> <span m=''2913820''>stuff.</span>
  <span m=''2914650''>And</span> <span m=''2915420''>for</span> <span m=''2915700''>free</span>
  <span m=''2916150''>versus</span> <span m=''2916650''>caged,</span> <span m=''2917190''>and</span>
  <span m=''2917310''>so</span> <span m=''2917450''>on.</span> <span m=''2919720''>Interesting</span>
  <span m=''2920150''>project</span> <span m=''2920520''>would be</span> <span m=''2920650''>to</span>
  <span m=''2920740''>try</span> <span m=''2920930''>to</span> <span m=''2921020''>make</span>
  <span m=''2921300''>art</span> <span m=''2921610''>out of</span> <span m=''2921870''>fold-and-cut,</span>
  <span m=''2922580''>just</span> <span m=''2922790''>doing</span> <span m=''2923010''>one</span>
  <span m=''2923220''>cut</span> <span m=''2923480''>instead</span> <span m=''2923850''>of</span>
  <span m=''2924030''>a zillion</span> <span m=''2924420''>cuts.</span> <span m=''2926640''>That''s</span>
  <span m=''2926900''>it.</span> <span m=''2927060''>Any</span> <span m=''2927240''>more</span>
  <span m=''2927440''>questions?</span> <span m=''2930202''>Yeah.</span> </p><p><span
  m=''2930685''>AUDIENCE: In</span> <span m=''2931168''>the</span> <span m=''2931651''>circle-packing</span>
  <span m=''2933583''>method,</span> <span m=''2934066''>how</span> <span m=''2934549''>do
  you</span> <span m=''2935032''>assign the</span> <span m=''2935515''>mountain-valley</span>
  <span m=''2936481''>[INAUDIBLE]?</span> </p><p><span m=''2937930''>PROFESSOR ERIK
  DEMAINE: OK,</span> <span m=''2938230''>in</span> <span m=''2938360''>the</span>
  <span m=''2938440''>circle-packing</span> <span m=''2939160''>method,</span> <span
  m=''2939650''>how do you assign</span> <span m=''2939930''>mountains</span> <span
  m=''2940240''>and valleys?</span> <span m=''2940530''>That</span> <span m=''2940660''>was</span>
  <span m=''2940840''>briefly</span> <span m=''2941240''>covered</span> <span m=''2941560''>in</span>
  <span m=''2941660''>lecture.</span> <span m=''2943530''>First</span> <span m=''2943740''>you</span>
  <span m=''2943810''>take</span> <span m=''2943990''>a</span> <span m=''2944050''>spanning</span>
  <span m=''2944430''>tree</span> <span m=''2944760''>of</span> <span m=''2944870''>all</span>
  <span m=''2945100''>of</span> <span m=''2945310''>the</span> <span m=''2945970''>molecules,</span>
  <span m=''2946880''>and</span> <span m=''2947050''>you</span> <span m=''2947120''>basically</span>
  <span m=''2947490''>fold</span> <span m=''2947850''>each</span> <span m=''2948040''>molecule</span>
  <span m=''2948480''>into</span> <span m=''2949400''>your</span> <span m=''2949560''>parent</span>
  <span m=''2950020''>in</span> <span m=''2950180''>the</span> <span m=''2950290''>tree.</span>
  <span m=''2951200''>So</span> <span m=''2952490''>each</span> <span m=''2952670''>one</span>
  <span m=''2952780''>has</span> <span m=''2952910''>a</span> <span m=''2952980''>direction,</span>
  <span m=''2953680''>and</span> <span m=''2953890''>from</span> <span m=''2954090''>that</span>
  <span m=''2954250''>you</span> <span m=''2954340''>can</span> <span m=''2954460''>extract</span>
  <span m=''2954840''>the</span> <span m=''2954920''>mountain-valley</span> <span
  m=''2955460''>assignment.</span> <span m=''2956370''>You</span> <span m=''2956470''>go</span>
  <span m=''2956640''>into</span> <span m=''2956850''>the</span> <span m=''2956930''>parent.</span>
  <span m=''2957320''>It''s a</span> <span m=''2957370''>mountain</span> <span m=''2957660''>there,</span>
  <span m=''2957840''>everyone</span> <span m=''2958120''>else''s</span> <span m=''2958450''>valley.</span>
  <span m=''2959210''>Basically</span> <span m=''2959490''>you''re</span> <span m=''2959640''>reversing</span>
  <span m=''2960070''>one</span> <span m=''2960260''>perpendicular</span> <span m=''2960830''>fold</span>
  <span m=''2961140''>per</span> <span m=''2961350''>molecule.</span> <span m=''2963190''>I</span>
  <span m=''2963270''>think.</span> <span m=''2964160''>Maybe</span> <span m=''2964390''>two.</span>
  <span m=''2965045''>With</span> <span m=''2965480''>triangles,</span> <span m=''2965920''>it''s</span>
  <span m=''2966020''>just</span> <span m=''2966220''>one.</span> </p><p><span m=''2966580''>For</span>
  <span m=''2967190''>quads</span> <span m=''2967540''>you</span> <span m=''2967630''>might</span>
  <span m=''2967800''>be</span> <span m=''2967920''>reversing</span> <span m=''2968330''>two.</span>
  <span m=''2969130''>So</span> <span m=''2969240''>you</span> <span m=''2969300''>start</span>
  <span m=''2969570''>with</span> <span m=''2970270''>all</span> <span m=''2970490''>of</span>
  <span m=''2970650''>the</span> <span m=''2971240''>straight</span> <span m=''2971470''>skeleton</span>
  <span m=''2971850''>being</span> <span m=''2972010''>mountains,</span> <span m=''2972430''>all</span>
  <span m=''2972590''>the</span> <span m=''2972670''>perpendiculars</span> <span m=''2973190''>being</span>
  <span m=''2973370''>valleys,</span> <span m=''2973820''>and</span> <span m=''2973900''>you
  have to</span> <span m=''2974170''>flip</span> <span m=''2974540''>a</span> <span
  m=''2974610''>few</span> <span m=''2974960''>to</span> <span m=''2975090''>just</span>
  <span m=''2975270''>get</span> <span m=''2975410''>them</span> <span m=''2975540''>to</span>
  <span m=''2975610''>fit</span> <span m=''2975930''>together.</span> <span m=''2978070''>Little</span>
  <span m=''2978250''>more</span> <span m=''2978380''>complicated</span> <span m=''2978840''>than</span>
  <span m=''2978920''>what</span> <span m=''2979040''>I</span> <span m=''2979090''>said,</span>
  <span m=''2979350''>but</span> <span m=''2979540''>I</span> <span m=''2979960''>would</span>
  <span m=''2980120''>need</span> <span m=''2980300''>a</span> <span m=''2980390''>slide</span>
  <span m=''2980810''>to</span> <span m=''2980900''>show</span> <span m=''2981130''>you</span>
  <span m=''2981950''>the</span> <span m=''2982010''>details.</span> <span m=''2982560''>It''s</span>
  <span m=''2982850''>in</span> <span m=''2983010''>the</span> <span m=''2983100''>textbook.</span>
  <span m=''2985490''>Anything</span> <span m=''2985760''>else?</span> <span m=''2987600''>All
  right,</span> <span m=''2987690''>that''s</span> <span m=''2987920''>fold-and-cut.</span>
  </p>'
type: course
uid: a6a020bc3ad7752c2f7b8b541245e455

---
None