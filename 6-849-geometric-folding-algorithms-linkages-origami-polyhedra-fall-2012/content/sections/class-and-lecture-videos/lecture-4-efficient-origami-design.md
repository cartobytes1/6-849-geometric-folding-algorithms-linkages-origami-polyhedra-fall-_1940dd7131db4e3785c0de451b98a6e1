---
about_this_resource_text: <p><strong>Description:</strong> This lecture continues
  to discuss the tree method and characterizing a uniaxial base. Another algorithm,
  Origamizer, is presented with introductory examples of folding a cube, checkerboard,
  and arbitrary polyhedra.</p> <p><strong>Speaker:</strong> Erik Demaine</p><p>&nbsp;</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: AxCavqjfy6w
  parent_uid: e6b610dc823591a52f1328a955f86095
  title: Video-YouTube-Stream
  type: Video
  uid: 493861699b2b2841a5913ca1ae05f05a
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/AxCavqjfy6w/default.jpg
  parent_uid: e6b610dc823591a52f1328a955f86095
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 6303fdbbc21467352f5e44cdc61df98b
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: e6b610dc823591a52f1328a955f86095
  title: Video-iTunes U-MP4
  type: Video
  uid: c8e76715ff94995f2703c1e2e34364b1
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_lec04_300k.mp4
  parent_uid: e6b610dc823591a52f1328a955f86095
  title: Video-Internet Archive-MP4
  type: Video
  uid: 891d9d2f6a3fd1fce31ee5931719b6e3
- id: 3Play-3PlayYouTubeid-MP4
  media_location: AxCavqjfy6w
  parent_uid: e6b610dc823591a52f1328a955f86095
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: ca99776a3faf038ffe0eaf9ca420d207
- id: AxCavqjfy6w.srt
  parent_uid: e6b610dc823591a52f1328a955f86095
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-4-efficient-origami-design/AxCavqjfy6w.srt
  title: 3play caption file
  type: null
  uid: 934796461296d3ad0da34646941727ef
- id: AxCavqjfy6w.pdf
  parent_uid: e6b610dc823591a52f1328a955f86095
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-4-efficient-origami-design/AxCavqjfy6w.pdf
  title: 3play pdf file
  type: null
  uid: 4dfe7a2f3bd689730752e005f5a0dcbb
- id: Caption-3Play YouTube id-SRT
  parent_uid: e6b610dc823591a52f1328a955f86095
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ca9198fd0b2eecbb304e5496ca90b9a7
- id: Transcript-3Play YouTube id-PDF
  parent_uid: e6b610dc823591a52f1328a955f86095
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 864a721b95fb8b2b659c3693c174573d
inline_embed_id: 88988361lecture4:efficientorigamidesign85749214
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: lecture-4-efficient-origami-design
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-4-efficient-origami-design
template_type: Tabbed
title: 'Lecture 4: Efficient Origami Design'
transcript: '<p><span m=''76020''>PROFESSOR: All</span> <span m=''76120''>right.</span>
  <span m=''76340''>Let''s</span> <span m=''76510''>get</span> <span m=''76630''>started.</span>
  <span m=''79460''>So</span> <span m=''79640''>we</span> <span m=''79740''>have</span>
  <span m=''79930''>a</span> <span m=''80020''>fun</span> <span m=''80320''>lecture</span>
  <span m=''80660''>today</span> <span m=''81150''>about</span> <span m=''81650''>efficient</span>
  <span m=''82090''>origami</span> <span m=''82560''>design.</span> <span m=''83580''>Last</span>
  <span m=''84120''>Monday,</span> <span m=''84690''>we</span> <span m=''84900''>did</span>
  <span m=''85200''>inefficient</span> <span m=''85760''>origami</span> <span m=''86210''>design,</span>
  <span m=''86670''>but</span> <span m=''86840''>it</span> <span m=''86920''>was</span>
  <span m=''87080''>universal.</span> <span m=''87730''>We</span> <span m=''87870''>could
  fold</span> <span m=''88200''>anything.</span> <span m=''90000''>And</span> <span
  m=''90630''>let''s</span> <span m=''90770''>see,</span> <span m=''90890''>Thursday,</span>
  <span m=''91210''>we</span> <span m=''91330''>talked</span> <span m=''91590''>about</span>
  <span m=''91770''>some</span> <span m=''91890''>basic</span> <span m=''92240''>foldability,</span>
  <span m=''93240''>crease</span> <span m=''93520''>patterns,</span> <span m=''94120''>what</span>
  <span m=''94290''>make the</span> <span m=''94520''>valid.</span> </p><p><span m=''95410''>That''ll</span>
  <span m=''96010''>ground</span> <span m=''96310''>us</span> <span m=''96470''>a</span>
  <span m=''96520''>little</span> <span m=''96730''>bit</span> <span m=''96950''>today</span>
  <span m=''97400''>when</span> <span m=''98180''>designing</span> <span m=''98620''>some</span>
  <span m=''98770''>crease</span> <span m=''99010''>patterns.</span> <span m=''100060''>Although,</span>
  <span m=''100310''>we''re</span> <span m=''100440''>going</span> <span m=''100550''>to</span>
  <span m=''100750''>stay</span> <span m=''101030''>fairly</span> <span m=''101350''>high</span>
  <span m=''101540''>level</span> <span m=''102300''>today</span> <span m=''102780''>because</span>
  <span m=''102950''>there are</span> <span m=''103100''>two</span> <span m=''103380''>big</span>
  <span m=''103600''>methods</span> <span m=''104020''>I</span> <span m=''104070''>want</span>
  <span m=''104220''>to</span> <span m=''104290''>talk</span> <span m=''104530''>about.</span>
  <span m=''105250''>One</span> <span m=''105410''>is</span> <span m=''105590''>tree</span>
  <span m=''105830''>method</span> <span m=''106590''>which</span> <span m=''106820''>is</span>
  <span m=''106940''>hit</span> <span m=''107080''>it</span> <span m=''107220''>pretty</span>
  <span m=''107470''>big</span> <span m=''107820''>in</span> <span m=''108120''>the</span>
  <span m=''108780''>impractical</span> <span m=''109450''>origami</span> <span m=''109860''>design.</span>
  <span m=''110380''>Lot</span> <span m=''110660''>of</span> <span m=''111160''>modern</span>
  <span m=''111790''>complex</span> <span m=''112260''>origami</span> <span m=''112630''>designers</span>
  <span m=''113070''>use</span> <span m=''113270''>it</span> <span m=''113880''>either</span>
  <span m=''114180''>in</span> <span m=''114260''>their</span> <span m=''114390''>head</span>
  <span m=''114820''>or</span> <span m=''115230''>occasionally</span> <span m=''115640''>on</span>
  <span m=''115770''>a</span> <span m=''115820''>computer.</span> </p><p><span m=''117270''>I</span>
  <span m=''117390''>demoed</span> <span m=''117650''>it</span> <span m=''117780''>quickly</span>
  <span m=''118160''>last</span> <span m=''118450''>time.</span> <span m=''119160''>So
  we</span> <span m=''119540''>are</span> <span m=''119630''>going</span> <span m=''119740''>to</span>
  <span m=''119790''>see</span> <span m=''121690''>some</span> <span m=''121940''>level</span>
  <span m=''122160''>of</span> <span m=''122230''>detail</span> <span m=''122510''>how</span>
  <span m=''122680''>that</span> <span m=''122860''>works.</span> <span m=''123390''>And</span>
  <span m=''123480''>then,</span> <span m=''123960''>I</span> <span m=''124130''>want</span>
  <span m=''124300''>to</span> <span m=''124360''>talk</span> <span m=''124570''>about</span>
  <span m=''124890''>Orgamizer</span> <span m=''125590''>which</span> <span m=''125750''>is</span>
  <span m=''125850''>one</span> <span m=''126010''>of</span> <span m=''126070''>the</span>
  <span m=''126170''>latest</span> <span m=''127430''>techniques</span> <span m=''128009''>for</span>
  <span m=''128280''>designing</span> <span m=''128960''>crazy,</span> <span m=''129460''>arbitrary,</span>
  <span m=''130280''>three-dimensional</span> <span m=''130870''>shapes</span> <span
  m=''131250''>that</span> <span m=''131880''>seems</span> <span m=''132170''>to</span>
  <span m=''132240''>be</span> <span m=''132370''>pretty</span> <span m=''132610''>efficient.</span>
  <span m=''133030''>Although</span> <span m=''133280''>we</span> <span m=''133400''>don''t</span>
  <span m=''133610''>have</span> <span m=''133790''>a</span> <span m=''133860''>formal</span>
  <span m=''134390''>sense</span> <span m=''134740''>in</span> <span m=''134850''>which</span>
  <span m=''135090''>it</span> <span m=''135180''>is</span> <span m=''136150''>efficient,</span>
  <span m=''137010''>it</span> <span m=''137150''>has</span> <span m=''137330''>some</span>
  <span m=''137460''>nice</span> <span m=''137670''>properties.</span> </p><p><span
  m=''138990''>And</span> <span m=''139550''>it''s</span> <span m=''139700''>pretty</span>
  <span m=''139910''>cool,</span> <span m=''140250''>and</span> <span m=''140380''>I</span>
  <span m=''140440''>can</span> <span m=''140590''>also</span> <span m=''140900''>demo
  it.</span> <span m=''141260''>It''s</span> <span m=''141470''>also</span> <span
  m=''141780''>freely</span> <span m=''142660''>downloadable</span> <span m=''144000''>software</span>
  <span m=''144500''>for</span> <span m=''144680''>Windows.</span> <span m=''147330''>Good.</span>
  <span m=''148250''>So</span> <span m=''148820''>just</span> <span m=''149090''>to</span>
  <span m=''149160''>get</span> <span m=''149950''>you</span> <span m=''150070''>motivated</span>
  <span m=''150750''>a</span> <span m=''150810''>little</span> <span m=''151050''>bit,</span>
  <span m=''152140''>I</span> <span m=''152250''>brought</span> <span m=''152880''>a</span>
  <span m=''153090''>bunch</span> <span m=''153470''>of</span> <span m=''153560''>examples.</span>
  <span m=''155150''>I''ll</span> <span m=''155310''>show</span> <span m=''155470''>you</span>
  <span m=''155630''>more</span> <span m=''156320''>later.</span> <span m=''157570''>But</span>
  <span m=''157610''>this</span> <span m=''157810''>is</span> <span m=''157860''>the</span>
  <span m=''157930''>sort</span> <span m=''158170''>of</span> <span m=''158280''>thing</span>
  <span m=''158480''>you</span> <span m=''158620''>can</span> <span m=''158770''>do</span>
  <span m=''158980''>with</span> <span m=''159130''>the</span> <span m=''159220''>tree</span>
  <span m=''159440''>method.</span> <span m=''159750''>It''s</span> <span m=''159890''>not</span>
  <span m=''160060''>going</span> <span m=''160150''>to</span> <span m=''160210''>be</span>
  <span m=''160330''>the</span> <span m=''160430''>tree</span> <span m=''160630''>method</span>
  <span m=''160940''>as</span> <span m=''161140''>I</span> <span m=''161210''>presented</span>
  <span m=''161770''>here.</span> </p><p><span m=''162540''>This</span> <span m=''162810''>is</span>
  <span m=''163030''>a</span> <span m=''163300''>variation</span> <span m=''163870''>on</span>
  <span m=''164020''>it</span> <span m=''164070''>called</span> <span m=''164280''>box</span>
  <span m=''164590''>pleating</span> <span m=''165760''>which</span> <span m=''166050''>you</span>
  <span m=''166160''>can</span> <span m=''166310''>read</span> <span m=''166480''>about</span>
  <span m=''166760''>in</span> <span m=''167050''><i>Origami</i></span> <span m=''167340''><i>Design</i></span>
  <span m=''167640''><i>Secrets.</i></span> <span m=''168430''>And</span> <span m=''169150''>I</span>
  <span m=''169210''>don''t</span> <span m=''169440''>think</span> <span m=''169580''>Jason</span>
  <span m=''169890''>will</span> <span m=''170000''>talk</span> <span m=''170200''>about</span>
  <span m=''170440''>that</span> <span m=''170670''>either.</span> <span m=''171120''>But</span>
  <span m=''172810''>it''s</span> <span m=''173870''>a</span> <span m=''173950''>variation</span>
  <span m=''174520''>on</span> <span m=''174670''>what</span> <span m=''174820''>we''ll</span>
  <span m=''174950''>be</span> <span m=''175070''>talking</span> <span m=''175390''>about.</span>
  <span m=''175600''>It</span> <span m=''175690''>lets</span> <span m=''175900''>you</span>
  <span m=''175990''>do</span> <span m=''176220''>crazy</span> <span m=''176620''>things</span>
  <span m=''176950''>like</span> <span m=''177320''>these</span> <span m=''178300''>two</span>
  <span m=''178530''>praying</span> <span m=''178840''>mantises,</span> <span m=''179410''>one</span>
  <span m=''179640''>eating</span> <span m=''179920''>the</span> <span m=''180090''>other.</span>
  </p><p><span m=''181800''>This</span> <span m=''181930''>is</span> <span m=''182120''>a</span>
  <span m=''182200''>design</span> <span m=''182570''>by</span> <span m=''182780''>Robert</span>
  <span m=''183090''>Lang.</span> <span m=''183910''>Fairly</span> <span m=''184620''>new.</span>
  <span m=''185210''>I don''t</span> <span m=''185360''>have</span> <span m=''185530''>a</span>
  <span m=''185600''>year</span> <span m=''185800''>here,</span> <span m=''186000''>but</span>
  <span m=''186130''>I</span> <span m=''186190''>think</span> <span m=''186390''>it''s</span>
  <span m=''186660''>last</span> <span m=''187010''>year</span> <span m=''187210''>or</span>
  <span m=''187280''>something.</span> <span m=''188590''>And</span> <span m=''189290''>that''s</span>
  <span m=''189620''>the</span> <span m=''189710''>sort</span> <span m=''190000''>of</span>
  <span m=''190140''>thing</span> <span m=''190940''>you</span> <span m=''191190''>can</span>
  <span m=''191700''>do</span> <span m=''192010''>getting</span> <span m=''192300''>all</span>
  <span m=''192530''>the limbs,</span> <span m=''193040''>all</span> <span m=''193240''>the</span>
  <span m=''193350''>right</span> <span m=''193590''>proportions,</span> <span m=''194780''>even</span>
  <span m=''195070''>multiple</span> <span m=''195560''>characters</span> <span m=''196890''>by</span>
  <span m=''197220''>representing</span> <span m=''197870''>your</span> <span m=''198010''>model</span>
  <span m=''198500''>as</span> <span m=''198810''>a</span> <span m=''198860''>stick</span>
  <span m=''199120''>figure.</span> </p><p><span m=''199630''>And</span> <span m=''200050''>that''s</span>
  <span m=''200280''>what</span> <span m=''201180''>the</span> <span m=''201310''>tree</span>
  <span m=''201440''>method</span> <span m=''201700''>is</span> <span m=''201790''>all</span>
  <span m=''201920''>about and</span> <span m=''202290''>doing</span> <span m=''202500''>that</span>
  <span m=''203030''>efficiently.</span> <span m=''204880''>So</span> <span m=''206980''>this</span>
  <span m=''207250''>is</span> <span m=''207420''>a</span> <span m=''207480''>statement</span>
  <span m=''207920''>last</span> <span m=''208230''>time</span> <span m=''208480''>of</span>
  <span m=''208670''>the</span> <span m=''208870''>theorem.</span> <span m=''210200''>There''s</span>
  <span m=''210470''>some</span> <span m=''210610''>catches</span> <span m=''211250''>to</span>
  <span m=''211540''>this.</span> <span m=''212150''>It''s</span> <span m=''212410''>an</span>
  <span m=''212540''>algorithm.</span> <span m=''213670''>Find</span> <span m=''214020''>a</span>
  <span m=''214090''>folding</span> <span m=''214560''>of</span> <span m=''214640''>the</span>
  <span m=''214740''>smallest</span> <span m=''215270''>square</span> <span m=''215740''>possible</span>
  <span m=''216710''>into</span> <span m=''217310''>and</span> <span m=''217520''>origami</span>
  <span m=''217930''>base</span> <span m=''218370''>with</span> <span m=''218580''>the</span>
  <span m=''218670''>desired</span> <span m=''220510''>tree</span> <span m=''221070''>as</span>
  <span m=''222990''>a</span> <span m=''223040''>shadow</span> <span m=''223530''>or</span>
  <span m=''223710''>as</span> <span m=''223820''>a</span> <span m=''223890''>projection.</span>
  </p><p><span m=''225520''>So</span> <span m=''225700''>you</span> <span m=''225780''>remember,</span>
  <span m=''227180''>this</span> <span m=''227380''>kind</span> <span m=''227630''>of</span>
  <span m=''227760''>picture.</span> <span m=''228320''>You</span> <span m=''228510''>want</span>
  <span m=''228660''>to</span> <span m=''228700''>make</span> <span m=''228890''>a</span>
  <span m=''228950''>lizard.</span> <span m=''229340''>You</span> <span m=''229450''>specify</span>
  <span m=''230550''>the</span> <span m=''230650''>lengths</span> <span m=''230990''>of</span>
  <span m=''231100''>each</span> <span m=''231300''>of</span> <span m=''231370''>these</span>
  <span m=''231550''>limbs</span> <span m=''231900''>and</span> <span m=''231970''>how</span>
  <span m=''232160''>they''re</span> <span m=''232290''>connected</span> <span m=''232670''>together</span>
  <span m=''233040''>into</span> <span m=''233280''>a</span> <span m=''233350''>tree.</span>
  <span m=''234120''>And</span> <span m=''234420''>then,</span> <span m=''234580''>you</span>
  <span m=''234720''>want</span> <span m=''234910''>to</span> <span m=''234980''>build</span>
  <span m=''237280''>an</span> <span m=''237540''>origami</span> <span m=''238140''>model</span>
  <span m=''238590''>on</span> <span m=''238780''>top</span> <span m=''239080''>of</span>
  <span m=''239190''>that,</span> <span m=''240300''>so</span> <span m=''240440''>to</span>
  <span m=''240520''>speak.</span> <span m=''242290''>So</span> <span m=''242630''>that</span>
  <span m=''246756''>it</span> <span m=''247220''>looks</span> <span m=''247340''>something</span>
  <span m=''247670''>like</span> <span m=''247890''>this.</span> </p><p><span m=''252320''>And</span>
  <span m=''252640''>you</span> <span m=''252750''>want</span> <span m=''252900''>to</span>
  <span m=''252960''>find</span> <span m=''253230''>a</span> <span m=''253280''>square</span>
  <span m=''253570''>the</span> <span m=''253680''>folds</span> <span m=''254000''>into</span>
  <span m=''254190''>such</span> <span m=''254440''>a</span> <span m=''254480''>shape.</span>
  <span m=''255190''>This</span> <span m=''255310''>projection</span> <span m=''255750''>is</span>
  <span m=''255880''>exactly</span> <span m=''256279''>that</span> <span m=''256480''>tree.</span>
  <span m=''257200''>Now, say</span> <span m=''257500''>it''s</span> <span m=''257630''>an</span>
  <span m=''257700''>algorithm,</span> <span m=''258410''>and</span> <span m=''258540''>it</span>
  <span m=''258630''>finds</span> <span m=''258850''>the</span> <span m=''258920''>smallest</span>
  <span m=''259360''>square.</span> <span m=''260320''>But</span> <span m=''260490''>to</span>
  <span m=''260589''>do</span> <span m=''260769''>that,</span> <span m=''261870''>essentially</span>
  <span m=''262310''>requires</span> <span m=''262740''>exponential</span> <span m=''263270''>time.</span>
  <span m=''263600''>We''ll</span> <span m=''264100''>prove</span> <span m=''264320''>in</span>
  <span m=''264370''>the</span> <span m=''264470''>next</span> <span m=''264820''>class</span>
  <span m=''265210''>that</span> <span m=''265310''>this</span> <span m=''265470''>problem,</span>
  <span m=''266130''>in</span> <span m=''266250''>general,</span> <span m=''266670''>is</span>
  <span m=''266790''>NP-complete.</span> </p><p><span m=''268370''>So</span> <span
  m=''268550''>it''s</span> <span m=''268660''>really</span> <span m=''269010''>hard.</span>
  <span m=''270660''>But</span> <span m=''270900''>there</span> <span m=''271060''>is</span>
  <span m=''271160''>an</span> <span m=''271240''>exponential</span> <span m=''271800''>time</span>
  <span m=''272080''>algorithm,</span> <span m=''272260''>and</span> <span m=''272410''>I</span>
  <span m=''272440''>didn''t</span> <span m=''272670''>say</span> <span m=''272810''>efficient</span>
  <span m=''273260''>here.</span> <span m=''274270''>It''s</span> <span m=''274470''>efficient
  in</span> <span m=''274950''>terms</span> <span m=''275150''>of</span> <span m=''275240''>design,</span>
  <span m=''276130''>quality,</span> <span m=''277080''>or</span> <span m=''277400''>in</span>
  <span m=''277470''>terms</span> <span m=''277700''>of</span> <span m=''277790''>algorithm.</span>
  <span m=''278260''>But</span> <span m=''278390''>you</span> <span m=''278530''>have</span>
  <span m=''278690''>to</span> <span m=''278800''>pick</span> <span m=''279020''>one</span>
  <span m=''279240''>of</span> <span m=''279360''>the</span> <span m=''279460''>two.</span>
  <span m=''280210''>So</span> <span m=''281100''>in</span> <span m=''281880''>TreeMaker</span>
  <span m=''282370''>the</span> <span m=''282490''>program,</span> <span m=''283630''>there''s</span>
  <span m=''283830''>an</span> <span m=''283920''>efficient</span> <span m=''284290''>algorithm,</span>
  <span m=''284920''>which</span> <span m=''285000''>finds</span> <span m=''285600''>a</span>
  <span m=''285870''>reasonably</span> <span m=''286780''>good-sized</span> <span
  m=''287230''>square.</span> <span m=''287600''>But</span> <span m=''287730''>it''s</span>
  <span m=''287850''>not</span> <span m=''288030''>guaranteed</span> <span m=''288410''>to</span>
  <span m=''288470''>be</span> <span m=''288610''>optimal.</span> <span m=''288880''>It''s</span>
  <span m=''289150''>just</span> <span m=''289420''>a</span> <span m=''289480''>local</span>
  <span m=''289830''>optimum.</span> </p><p><span m=''291200''>In</span> <span m=''291350''>principle,</span>
  <span m=''291900''>you</span> <span m=''291950''>could</span> <span m=''292070''>spend</span>
  <span m=''292280''>exponential</span> <span m=''292800''>time</span> <span m=''293080''>here.</span>
  <span m=''294250''>So</span> <span m=''294450''>slow</span> <span m=''294715''>algorithm</span>
  <span m=''295290''>and</span> <span m=''295460''>get</span> <span m=''295690''>the</span>
  <span m=''295840''>smallest</span> <span m=''296210''>square.</span> <span m=''296900''>So</span>
  <span m=''297210''>it</span> <span m=''297410''>depends.</span> <span m=''298680''>The</span>
  <span m=''298910''>other</span> <span m=''299110''>catch is</span> <span m=''299580''>this</span>
  <span m=''299790''>folding.</span> <span m=''300750''>We''re</span> <span m=''300900''>still</span>
  <span m=''301230''>working</span> <span m=''301630''>on</span> <span m=''301760''>proving</span>
  <span m=''302160''>that</span> <span m=''302330''>this</span> <span m=''302890''>does</span>
  <span m=''303080''>not</span> <span m=''303290''>actually</span> <span m=''303570''>self-intersect</span>
  <span m=''304510''>in</span> <span m=''304670''>the</span> <span m=''304790''>folded</span>
  <span m=''305120''>state.</span> <span m=''307030''>I</span> <span m=''307440''>checked</span>
  <span m=''307710''>the</span> <span m=''307820''>dates.</span> <span m=''308080''>We''ve</span>
  <span m=''308210''>been</span> <span m=''308310''>working</span> <span m=''308590''>on</span>
  <span m=''308670''>that</span> <span m=''308880''>for</span> <span m=''309010''>six</span>
  <span m=''309290''>years.</span> <span m=''310830''>But</span> <span m=''311840''>it''s</span>
  <span m=''312390''>closing</span> <span m=''312770''>in.</span> <span m=''313340''>Maybe</span>
  <span m=''313640''>next</span> <span m=''313920''>year</span> <span m=''314070''>we''ll</span>
  <span m=''314220''>have</span> <span m=''315090''>a</span> <span m=''315220''>draft</span>
  <span m=''315630''>of</span> <span m=''316330''>this</span> <span m=''316530''>proof.</span>
  <span m=''316770''>It''s</span> <span m=''316930''>quite--</span> <span m=''317250''>it''s</span>
  <span m=''317460''>many,</span> <span m=''317960''>many</span> <span m=''318110''>pages.</span>
  </p><p><span m=''321640''>Good.</span> <span m=''324010''>So</span> <span m=''324310''>those</span>
  <span m=''324570''>are</span> <span m=''324600''>the</span> <span m=''324720''>catches.</span>
  <span m=''325730''>Now,</span> <span m=''325870''>let</span> <span m=''326000''>me</span>
  <span m=''326170''>tell</span> <span m=''326430''>you</span> <span m=''326590''>about</span>
  <span m=''326830''>this</span> <span m=''327160''>term</span> <span m=''327380''>uniaxial.</span>
  <span m=''328960''>Essentially,</span> <span m=''329250''>it</span> <span m=''329540''>just</span>
  <span m=''329780''>means</span> <span m=''330310''>tree</span> <span m=''330530''>shapes.</span>
  <span m=''331470''>But</span> <span m=''331690''>I''d</span> <span m=''331800''>like</span>
  <span m=''331970''>to</span> <span m=''332070''>be</span> <span m=''332190''>a</span>
  <span m=''332240''>little</span> <span m=''332450''>bit</span> <span m=''332600''>more</span>
  <span m=''332760''>formal</span> <span m=''333110''>about</span> <span m=''333410''>that.</span>
  <span m=''334050''>And</span> <span m=''334330''>last</span> <span m=''334580''>time,</span>
  <span m=''334730''>I</span> <span m=''334780''>showed</span> <span m=''335080''>you</span>
  <span m=''335330''>the</span> <span m=''335875''>standard</span> <span m=''336260''>origami</span>
  <span m=''336730''>bases.</span> <span m=''338120''>All</span> <span m=''338480''>of</span>
  <span m=''338730''>these</span> <span m=''339230''>are</span> <span m=''339430''>uniaxial,</span>
  <span m=''340450''>I</span> <span m=''340550''>think,</span> <span m=''341000''>except</span>
  <span m=''342420''>the</span> <span m=''342540''>pinwheel</span> <span m=''343020''>which</span>
  <span m=''343190''>we</span> <span m=''343320''>folded.</span> </p><p><span m=''344830''>So</span>
  <span m=''344990''>the</span> <span m=''345110''>pinwheel--</span> <span m=''346450''>so</span>
  <span m=''346840''>let</span> <span m=''347010''>me</span> <span m=''347120''>tell</span>
  <span m=''347270''>you</span> <span m=''347380''>intuitively</span> <span m=''347970''>what</span>
  <span m=''348640''>uniaxial</span> <span m=''349160''>means.</span> <span m=''349470''>It</span>
  <span m=''349560''>means</span> <span m=''349810''>you</span> <span m=''349940''>can</span>
  <span m=''350080''>take</span> <span m=''350320''>all</span> <span m=''350450''>these</span>
  <span m=''350620''>flaps</span> <span m=''350980''>of</span> <span m=''351070''>paper</span>
  <span m=''351870''>and</span> <span m=''352020''>lie</span> <span m=''352320''>them,</span>
  <span m=''353240''>place</span> <span m=''353490''>them</span> <span m=''353620''>along</span>
  <span m=''354240''>a</span> <span m=''354340''>line.</span> <span m=''355590''>And</span>
  <span m=''356180''>the</span> <span m=''357170''>hinges</span> <span m=''357700''>between</span>
  <span m=''358720''>those</span> <span m=''359690''>flaps</span> <span m=''360120''>are</span>
  <span m=''360180''>all</span> <span m=''360370''>perpendicular</span> <span m=''360980''>to</span>
  <span m=''361090''>that</span> <span m=''361280''>line.</span> <span m=''362670''>So</span>
  <span m=''363580''>this</span> <span m=''363750''>is</span> <span m=''363880''>the</span>
  <span m=''364020''>axis.</span> <span m=''366500''>Whereas</span> <span m=''366680''>something</span>
  <span m=''366980''>like</span> <span m=''367180''>this,</span> <span m=''368350''>essentially</span>
  <span m=''369060''>there</span> <span m=''369330''>are</span> <span m=''369370''>four</span>
  <span m=''369910''>axes.</span> <span m=''370780''>The</span> <span m=''370870''>flaps</span>
  <span m=''371410''>are</span> <span m=''372340''>here,</span> <span m=''372600''>or</span>
  <span m=''372670''>two</span> <span m=''372880''>axes</span> <span m=''373280''>I</span>
  <span m=''373400''>guess.</span> </p><p><span m=''374240''>But</span> <span m=''374740''>definitely</span>
  <span m=''375120''>not</span> <span m=''375380''>one.</span> <span m=''375980''>So</span>
  <span m=''376180''>these</span> <span m=''376810''>cannot</span> <span m=''377120''>be</span>
  <span m=''377390''>lined</span> <span m=''377670''>up</span> <span m=''377780''>along</span>
  <span m=''378010''>a</span> <span m=''378080''>line,</span> <span m=''378790''>even</span>
  <span m=''379010''>if</span> <span m=''379140''>you''ve</span> <span m=''380590''>flapped</span>
  <span m=''380850''>them</span> <span m=''381000''>around</span> <span m=''381300''>some</span>
  <span m=''381490''>other</span> <span m=''381670''>way.</span> <span m=''382880''>That''s</span>
  <span m=''383100''>intuitive</span> <span m=''383550''>definition.</span> <span
  m=''384740''>Multiaxial</span> <span m=''386070''>is</span> <span m=''386210''>not</span>
  <span m=''386410''>a</span> <span m=''386630''>formally</span> <span m=''387030''>defined</span>
  <span m=''387400''>thing.</span> <span m=''387960''>But</span> <span m=''388140''>uniaxial</span>
  <span m=''388860''>we</span> <span m=''388980''>can</span> <span m=''389130''>formally</span>
  <span m=''389520''>define.</span> <span m=''390390''>And</span> <span m=''390640''>it</span>
  <span m=''390720''>will</span> <span m=''390850''>capture</span> <span m=''392530''>things</span>
  <span m=''392810''>like</span> <span m=''393050''>this</span> <span m=''393310''>water</span>
  <span m=''393560''>bomb</span> <span m=''393800''>base,</span> <span m=''394520''>all</span>
  <span m=''394750''>the</span> <span m=''394850''>other</span> <span m=''395000''>bases</span>
  <span m=''395380''>there,</span> <span m=''396260''>as</span> <span m=''396560''>well</span>
  <span m=''396890''>as</span> <span m=''397040''>bases</span> <span m=''397740''>like</span>
  <span m=''397980''>this.</span> </p><p><span m=''400370''>And</span> <span m=''401690''>it''s</span>
  <span m=''401940''>defined</span> <span m=''402260''>by</span> <span m=''402360''>Robert</span>
  <span m=''402690''>Lang,</span> <span m=''403070''>I</span> <span m=''403100''>think</span>
  <span m=''404240''>probably</span> <span m=''404690''>around</span> <span m=''405060''>''94</span>
  <span m=''406896''>was the</span> <span m=''407370''>first</span> <span m=''407700''>publication.</span>
  <span m=''419550''>And</span> <span m=''419970''>it''s</span> <span m=''420250''>just</span>
  <span m=''420570''>a</span> <span m=''420880''>bunch</span> <span m=''421470''>of</span>
  <span m=''421720''>conditions.</span> <span m=''431170''>And</span> <span m=''431420''>a</span>
  <span m=''431460''>bunch</span> <span m=''431680''>of</span> <span m=''431730''>them</span>
  <span m=''431870''>are</span> <span m=''431940''>just</span> <span m=''432350''>technical</span>
  <span m=''432850''>to</span> <span m=''432920''>make</span> <span m=''433140''>things</span>
  <span m=''433370''>work</span> <span m=''433600''>out</span> <span m=''433720''>mathematically.</span>
  <span m=''436090''>First</span> <span m=''436320''>thing</span> <span m=''436500''>I''d</span>
  <span m=''436570''>like</span> <span m=''436760''>to</span> <span m=''436860''>say</span>
  <span m=''437700''>is</span> <span m=''437940''>that</span> <span m=''438250''>the</span>
  <span m=''438380''>entire</span> <span m=''439260''>base--</span> <span m=''439760''>base</span>
  <span m=''440010''>just</span> <span m=''440220''>means</span> <span m=''440950''>origami</span>
  <span m=''442230''>for</span> <span m=''442420''>our</span> <span m=''442580''>purposes.</span>
  <span m=''444380''>It''s</span> <span m=''444780''>sort</span> <span m=''445050''>of</span>
  <span m=''446060''>practical</span> <span m=''446620''>distinction</span> <span
  m=''447060''>not</span> <span m=''447230''>a</span> <span m=''447280''>mathematical</span>
  <span m=''447870''>one.</span> <span m=''448940''>Is</span> <span m=''449100''>that</span>
  <span m=''449230''>everything</span> <span m=''449700''>lies</span> <span m=''450090''>above</span>
  <span m=''450570''>the</span> <span m=''450660''>floor.</span> </p><p><span m=''451410''>So</span>
  <span m=''451590''>the</span> <span m=''451690''>floor</span> <span m=''452110''>is</span>
  <span m=''452340''>equal to</span> <span m=''452620''>zero,</span> <span m=''453480''>and</span>
  <span m=''453790''>we''ll</span> <span m=''453890''>just</span> <span m=''454040''>say</span>
  <span m=''454210''>everything''s</span> <span m=''454620''>above</span> <span m=''454960''>that.</span>
  <span m=''455260''>And</span> <span m=''455440''>the</span> <span m=''455930''>action</span>
  <span m=''456340''>is</span> <span m=''456460''>going</span> <span m=''456580''>to</span>
  <span m=''456640''>be</span> <span m=''456760''>in</span> <span m=''456840''>the</span>
  <span m=''456920''>floor.</span> <span m=''457260''>That''s</span> <span m=''457560''>where</span>
  <span m=''458480''>I''ve</span> <span m=''458980''>drawn</span> <span m=''459140''>it</span>
  <span m=''459230''>that</span> <span m=''459410''>way.</span> <span m=''459570''>Here,</span>
  <span m=''459730''>there''s a</span> <span m=''459940''>floor.</span> <span m=''461890''>And</span>
  <span m=''462250''>the</span> <span m=''462360''>tree</span> <span m=''463010''>is</span>
  <span m=''463310''>going</span> <span m=''463460''>to</span> <span m=''463530''>lie</span>
  <span m=''463850''>on</span> <span m=''464040''>the</span> <span m=''464110''>floor,</span>
  <span m=''464460''>and</span> <span m=''464530''>everything</span> <span m=''464880''>else</span>
  <span m=''465050''>is</span> <span m=''465180''>above</span> <span m=''465470''>that.</span>
  </p><p><span m=''469000''>Second</span> <span m=''469510''>property.</span> <span
  m=''477670''>Sort</span> <span m=''478000''>of</span> <span m=''478100''>a</span>
  <span m=''478180''>shadow</span> <span m=''479060''>property.</span> <span m=''481530''>If</span>
  <span m=''481640''>I</span> <span m=''481690''>look</span> <span m=''481970''>at</span>
  <span m=''482120''>where</span> <span m=''482620''>the</span> <span m=''482770''>base</span>
  <span m=''483410''>meets</span> <span m=''483940''>the</span> <span m=''484030''>floor</span>
  <span m=''484310''>is</span> <span m=''484590''>equals to</span> <span m=''484940''>zero,</span>
  <span m=''486790''>that''s</span> <span m=''487120''>the</span> <span m=''487190''>same</span>
  <span m=''487540''>thing</span> <span m=''488310''>as</span> <span m=''488450''>if</span>
  <span m=''488590''>I</span> <span m=''488640''>look</span> <span m=''488890''>at</span>
  <span m=''489000''>the</span> <span m=''489080''>shadow</span> <span m=''490380''>onto</span>
  <span m=''491300''>the</span> <span m=''491410''>floor.</span> <span m=''498890''>This</span>
  <span m=''499110''>is</span> <span m=''499220''>essentially</span> <span m=''499670''>saying</span>
  <span m=''500540''>that</span> <span m=''500730''>this</span> <span m=''501050''>base</span>
  <span m=''501550''>does</span> <span m=''501700''>not</span> <span m=''501890''>have</span>
  <span m=''502100''>any</span> <span m=''502300''>overhang.</span> </p><p><span m=''503730''>So</span>
  <span m=''503910''>if</span> <span m=''504000''>it</span> <span m=''504090''>had,</span>
  <span m=''504620''>for</span> <span m=''504780''>example,</span> <span m=''506080''>some</span>
  <span m=''506340''>feature</span> <span m=''506680''>like</span> <span m=''506900''>this</span>
  <span m=''507220''>that</span> <span m=''507410''>hung</span> <span m=''507710''>over</span>
  <span m=''508180''>its</span> <span m=''508360''>shadow--</span> <span m=''509580''>was</span>
  <span m=''510020''>more--</span> <span m=''511650''>went</span> <span m=''511880''>out</span>
  <span m=''512070''>here.</span> <span m=''512340''>The</span> <span m=''512440''>shadow</span>
  <span m=''512750''>goes</span> <span m=''512950''>out</span> <span m=''513049''>here,</span>
  <span m=''513440''>but</span> <span m=''513510''>the</span> <span m=''513600''>base</span>
  <span m=''514000''>does</span> <span m=''514110''>not.</span> <span m=''514350''>That''s</span>
  <span m=''514590''>not</span> <span m=''514700''>allowed.</span> <span m=''515610''>So</span>
  <span m=''515659''>I</span> <span m=''515700''>want</span> <span m=''515870''>everything--</span>
  <span m=''516830''>actually</span> <span m=''517100''>want</span> <span m=''517289''>things</span>
  <span m=''517480''>to</span> <span m=''517570''>get</span> <span m=''518120''>smaller</span>
  <span m=''518760''>as</span> <span m=''518880''>you</span> <span m=''519000''>go</span>
  <span m=''519210''>up</span> <span m=''519890''>in</span> <span m=''520070''>z.</span>
  </p><p><span m=''521809''>This is</span> <span m=''522150''>a</span> <span m=''522220''>stronger</span>
  <span m=''523510''>statement</span> <span m=''523980''>of</span> <span m=''524070''>property</span>
  <span m=''524480''>two.</span> <span m=''528290''>And</span> <span m=''528470''>then,</span>
  <span m=''528620''>I</span> <span m=''528690''>want</span> <span m=''528880''>to</span>
  <span m=''528950''>define</span> <span m=''529260''>this</span> <span m=''529410''>notion</span>
  <span m=''529900''>flaps.</span> <span m=''533070''>And</span> <span m=''533400''>the</span>
  <span m=''533470''>basic</span> <span m=''533820''>idea</span> <span m=''534740''>is</span>
  <span m=''535020''>that</span> <span m=''538080''>you</span> <span m=''538190''>have</span>
  <span m=''538410''>faces</span> <span m=''539940''>of</span> <span m=''540180''>the</span>
  <span m=''540260''>crease</span> <span m=''540530''>pattern.</span> <span m=''548310''>so</span>
  <span m=''548490''>the</span> <span m=''548560''>faces</span> <span m=''549080''>are</span>
  <span m=''549190''>just</span> <span m=''550710''>the</span> <span m=''550880''>regions</span>
  <span m=''552260''>we</span> <span m=''552390''>get</span> <span m=''552600''>out
  of</span> <span m=''552980''>the</span> <span m=''553080''>creases,</span> <span
  m=''553500''>all</span> <span m=''553610''>these</span> <span m=''553760''>triangles</span>
  <span m=''554300''>for</span> <span m=''554390''>example.</span> <span m=''555250''>I</span>
  <span m=''555350''>can</span> <span m=''555530''>divide</span> <span m=''556000''>them,</span>
  <span m=''556330''>partition</span> <span m=''556890''>them</span> <span m=''557170''>into</span>
  <span m=''557430''>groups</span> <span m=''557880''>which</span> <span m=''558100''>I</span>
  <span m=''558160''>call</span> <span m=''558380''>flaps.</span> </p><p><span m=''558930''>So</span>
  <span m=''559010''>for</span> <span m=''559100''>example,</span> <span m=''560100''>these</span>
  <span m=''560380''>two</span> <span m=''561190''>guys</span> <span m=''561440''>over</span>
  <span m=''561600''>here</span> <span m=''561900''>form</span> <span m=''562290''>one</span>
  <span m=''562520''>flap.</span> <span m=''563020''>They</span> <span m=''563160''>fold</span>
  <span m=''563510''>together.</span> <span m=''564360''>They''re</span> <span m=''564480''>going</span>
  <span m=''564620''>to</span> <span m=''564680''>be</span> <span m=''564820''>manipulated</span>
  <span m=''565410''>together.</span> <span m=''566430''>And</span> <span m=''567430''>so</span>
  <span m=''567770''>in</span> <span m=''567860''>this</span> <span m=''568020''>case,</span>
  <span m=''568330''>I''ll</span> <span m=''568430''>get</span> <span m=''568490''>four</span>
  <span m=''568670''>flaps.</span> <span m=''582790''>Anything</span> <span m=''583290''>I</span>
  <span m=''583330''>want</span> <span m=''583570''>to</span> <span m=''583680''>say</span>
  <span m=''584010''>here?</span> <span m=''584480''>Yeah.</span> <span m=''585310''>Each</span>
  <span m=''585580''>flap</span> <span m=''588660''>is</span> <span m=''588840''>going</span>
  <span m=''588950''>to</span> <span m=''589020''>project</span> <span m=''600030''>to</span>
  <span m=''600600''>a line</span> <span m=''601010''>segment.</span> </p><p><span
  m=''612470''>It''s</span> <span m=''612670''>going</span> <span m=''612800''>to</span>
  <span m=''612880''>be</span> <span m=''613170''>one</span> <span m=''613450''>of</span>
  <span m=''613550''>the</span> <span m=''613720''>edges</span> <span m=''614140''>of</span>
  <span m=''614280''>the</span> <span m=''614370''>tree.</span> <span m=''617340''>So</span>
  <span m=''617980''>then,</span> <span m=''618070''>there''s the</span> <span m=''618290''>notion</span>
  <span m=''618950''>of</span> <span m=''619030''>a</span> <span m=''619080''>hinge</span>
  <span m=''619390''>crease.</span> <span m=''626300''>And</span> <span m=''626620''>these</span>
  <span m=''626820''>are</span> <span m=''626890''>just</span> <span m=''627110''>creases</span>
  <span m=''627800''>shared</span> <span m=''629030''>by</span> <span m=''629460''>two</span>
  <span m=''629640''>flaps.</span> <span m=''631690''>So</span> <span m=''632000''>they''re</span>
  <span m=''632180''>the</span> <span m=''632460''>creases</span> <span m=''632950''>that</span>
  <span m=''636740''>separate</span> <span m=''637220''>one</span> <span m=''637380''>flap
  from</span> <span m=''637790''>another.</span> <span m=''641150''>These</span> <span
  m=''641420''>will</span> <span m=''641580''>always</span> <span m=''643360''>require</span>
  <span m=''644220''>that</span> <span m=''644640''>they</span> <span m=''645360''>projects</span>
  <span m=''645950''>to</span> <span m=''647950''>a</span> <span m=''648870''>point.</span>
  </p><p><span m=''651910''>So</span> <span m=''652040''>this</span> <span m=''652200''>is</span>
  <span m=''652240''>equivalent</span> <span m=''652670''>to</span> <span m=''652730''>saying</span>
  <span m=''652950''>the</span> <span m=''653030''>hinge</span> <span m=''653270''>crease</span>
  <span m=''653630''>is</span> <span m=''654030''>vertical.</span> <span m=''654650''>It''s</span>
  <span m=''654790''>perpendicular</span> <span m=''655540''>to</span> <span m=''655710''>the</span>
  <span m=''655840''>floor.</span> <span m=''656320''>I''m</span> <span m=''656490''>always</span>
  <span m=''656710''>projecting</span> <span m=''657600''>straight</span> <span m=''657920''>down</span>
  <span m=''658130''>onto</span> <span m=''658280''>the</span> <span m=''658350''>floor</span>
  <span m=''658800''>orthographically,</span> <span m=''660070''>just</span> <span
  m=''661330''>setting</span> <span m=''661670''>z</span> <span m=''661850''>to</span>
  <span m=''661930''>zero.</span> <span m=''664680''>And</span> <span m=''665990''>so
  that''s</span> <span m=''666180''>saying</span> <span m=''666500''>these</span>
  <span m=''667620''>are</span> <span m=''667660''>the</span> <span m=''667730''>hinges.</span>
  <span m=''668950''>They</span> <span m=''669110''>should</span> <span m=''669330''>be</span>
  <span m=''669600''>vertical.</span> <span m=''672000''>So</span> <span m=''672110''>projection</span>
  <span m=''672560''>is</span> <span m=''672670''>a</span> <span m=''672730''>point.</span>
  </p><p><span m=''673690''>And</span> <span m=''673900''>then</span> <span m=''674230''>from</span>
  <span m=''674520''>those</span> <span m=''674760''>two</span> <span m=''674870''>properties,</span>
  <span m=''675390''>I</span> <span m=''675460''>can</span> <span m=''675610''>define</span>
  <span m=''676480''>a</span> <span m=''676580''>graph</span> <span m=''677110''>which</span>
  <span m=''677340''>I</span> <span m=''677420''>want</span> <span m=''677640''>to</span>
  <span m=''677740''>be</span> <span m=''677910''>a</span> <span m=''677970''>tree.</span>
  <span m=''688820''>So</span> <span m=''689040''>each</span> <span m=''689300''>flap</span>
  <span m=''689730''>I</span> <span m=''689890''>want</span> <span m=''690110''>to</span>
  <span m=''690160''>make</span> <span m=''690440''>an</span> <span m=''690590''>edge</span>
  <span m=''691200''>of</span> <span m=''691490''>my</span> <span m=''691650''>graph.</span>
  <span m=''692910''>And</span> <span m=''693100''>that</span> <span m=''693280''>edge</span>
  <span m=''693520''>is</span> <span m=''693610''>going</span> <span m=''693740''>to</span>
  <span m=''693800''>be</span> <span m=''693930''>the</span> <span m=''694040''>line</span>
  <span m=''694310''>segment</span> <span m=''695050''>that</span> <span m=''695520''>the</span>
  <span m=''695530''>flap</span> <span m=''696010''>projects,</span> <span m=''696790''>each</span>
  <span m=''696990''>flat</span> <span m=''697400''>projects</span> <span m=''697790''>to.</span>
  <span m=''699200''>And</span> <span m=''699460''>I''m</span> <span m=''699550''>going</span>
  <span m=''699660''>to</span> <span m=''699750''>connect</span> <span m=''700200''>those</span>
  <span m=''700670''>edges</span> <span m=''701060''>together</span> <span m=''702580''>at</span>
  <span m=''703060''>vertices</span> <span m=''705680''>when</span> <span m=''707890''>the</span>
  <span m=''707980''>flaps</span> <span m=''710950''>share</span> <span m=''712360''>the</span>
  <span m=''712410''>hinge</span> <span m=''712730''>crease.</span> </p><p><span m=''721680''>All</span>
  <span m=''721790''>right.</span> <span m=''722120''>That''s</span> <span m=''722400''>a</span>
  <span m=''722460''>graph</span> <span m=''722930''>which</span> <span m=''723400''>you</span>
  <span m=''723500''>can</span> <span m=''723600''>define.</span> <span m=''724630''>And</span>
  <span m=''724810''>that</span> <span m=''725050''>graph</span> <span m=''726230''>is</span>
  <span m=''726420''>a</span> <span m=''726490''>tree.</span> <span m=''727570''>That''s</span>
  <span m=''727800''>the</span> <span m=''727900''>constraint.</span> <span m=''730720''>And</span>
  <span m=''731250''>I</span> <span m=''731310''>think</span> <span m=''731580''>I</span>
  <span m=''731610''>have</span> <span m=''731910''>even</span> <span m=''732340''>more.</span>
  <span m=''735680''>I''ve got</span> <span m=''736140''>one</span> <span m=''736310''>more</span>
  <span m=''736480''>property.</span> <span m=''757140''>I</span> <span m=''757310''>think
  I</span> <span m=''757590''>actually</span> <span m=''757940''>want</span> <span
  m=''758430''>projects</span> <span m=''758875''>here.</span> <span m=''760220''>Let''s</span>
  <span m=''760670''>try</span> <span m=''760990''>that.</span> </p><p><span m=''765600''>All</span>
  <span m=''765680''>right.</span> <span m=''766040''>This</span> <span m=''766230''>is</span>
  <span m=''766310''>a</span> <span m=''766370''>bunch</span> <span m=''766600''>of</span>
  <span m=''766690''>formalism</span> <span m=''767420''>to</span> <span m=''767910''>state</span>
  <span m=''768310''>what''s</span> <span m=''768500''>pretty</span> <span m=''768740''>intuitive.</span>
  <span m=''769940''>I</span> <span m=''772120''>want</span> <span m=''772380''>all</span>
  <span m=''772570''>the</span> <span m=''772640''>flaps</span> <span m=''773060''>of</span>
  <span m=''773140''>paper</span> <span m=''773520''>to</span> <span m=''773600''>be</span>
  <span m=''774150''>vertical,</span> <span m=''774920''>so</span> <span m=''775110''>they</span>
  <span m=''775220''>project</span> <span m=''775620''>to</span> <span m=''775700''>a
  line</span> <span m=''775970''>segment.</span> <span m=''777710''>When</span> <span
  m=''778310''>I</span> <span m=''778530''>look</span> <span m=''779090''>from</span>
  <span m=''779650''>the--</span> <span m=''780210''>when</span> <span m=''780360''>I</span>
  <span m=''780390''>look</span> <span m=''780620''>at</span> <span m=''780800''>the</span>
  <span m=''780890''>projection,</span> <span m=''783140''>I</span> <span m=''783280''>can</span>
  <span m=''783550''>define</span> <span m=''785310''>a</span> <span m=''785440''>graph</span>
  <span m=''785890''>where</span> <span m=''786210''>there''s</span> <span m=''786380''>an</span>
  <span m=''786470''>edge</span> <span m=''786770''>for</span> <span m=''786940''>each</span>
  <span m=''787140''>flap,</span> <span m=''788230''>where</span> <span m=''788430''>it''s</span>
  <span m=''788560''>projecting.</span> </p><p><span m=''789200''>And</span> <span
  m=''789380''>I</span> <span m=''789470''>join</span> <span m=''789830''>those</span>
  <span m=''790020''>edges</span> <span m=''790250''>together.</span> <span m=''791070''>Here,</span>
  <span m=''791370''>I''m</span> <span m=''791450''>joinging</span> <span m=''791710''>four</span>
  <span m=''791940''>them</span> <span m=''792130''>at</span> <span m=''792200''>a</span>
  <span m=''792240''>vertex.</span> <span m=''792700''>Because</span> <span m=''793610''>if</span>
  <span m=''793780''>you</span> <span m=''793980''>unfold</span> <span m=''794440''>it,</span>
  <span m=''795090''>they</span> <span m=''795220''>all</span> <span m=''795470''>share</span>
  <span m=''796330''>hinge</span> <span m=''796630''>creases.</span> <span m=''797020''>Hinge</span>
  <span m=''797210''>creases</span> <span m=''797610''>in</span> <span m=''797710''>this</span>
  <span m=''797900''>case</span> <span m=''798170''>are</span> <span m=''798330''>the</span>
  <span m=''798540''>perpendicular.</span> <span m=''799330''>These</span> <span m=''799720''>four</span>
  <span m=''799940''>guys.</span> <span m=''802230''>So</span> <span m=''802430''>because--</span>
  <span m=''804336''>it''s hard to</span> <span m=''804720''>manipulate.</span> <span
  m=''806180''>I''ve</span> <span m=''806370''>got</span> <span m=''806510''>a</span>
  <span m=''806560''>flap</span> <span m=''806870''>over</span> <span m=''807070''>here.</span>
  <span m=''807420''>A flap</span> <span m=''807730''>over</span> <span m=''807950''>here.</span>
  <span m=''808340''>They</span> <span m=''808480''>share</span> <span m=''809290''>a</span>
  <span m=''809310''>hinge,</span> <span m=''810270''>so</span> <span m=''810670''>I</span>
  <span m=''810810''>connect</span> <span m=''811150''>them</span> <span m=''811290''>together</span>
  <span m=''811710''>in</span> <span m=''811790''>the</span> <span m=''811880''>graph.</span>
  </p><p><span m=''812700''>It''s</span> <span m=''812830''>just</span> <span m=''813010''>a</span>
  <span m=''813060''>formal</span> <span m=''813390''>way</span> <span m=''813520''>to</span>
  <span m=''813620''>make</span> <span m=''813800''>the</span> <span m=''813880''>graph</span>
  <span m=''814260''>correct.</span> <span m=''815966''>It</span> <span m=''816400''>may</span>
  <span m=''816550''>seem</span> <span m=''816880''>tedious,</span> <span m=''817960''>but</span>
  <span m=''819310''>this</span> <span m=''819560''>definition</span> <span m=''820090''>sidesteps</span>
  <span m=''820550''>some</span> <span m=''820850''>issues</span> <span m=''821320''>which</span>
  <span m=''821560''>would</span> <span m=''821750''>occur</span> <span m=''822080''>if</span>
  <span m=''822180''>you</span> <span m=''822270''>defined</span> <span m=''822630''>it
  in</span> <span m=''822800''>the</span> <span m=''822860''>more</span> <span m=''823070''>obvious</span>
  <span m=''823440''>way</span> <span m=''823660''>which</span> <span m=''823870''>is</span>
  <span m=''823990''>just</span> <span m=''824240''>take</span> <span m=''824410''>the</span>
  <span m=''824490''>projection,</span> <span m=''825340''>call</span> <span m=''825600''>it</span>
  <span m=''825660''>a</span> <span m=''825720''>tree.</span> <span m=''827080''>But</span>
  <span m=''827260''>I</span> <span m=''827320''>don''t</span> <span m=''827450''>want</span>
  <span m=''827560''>to</span> <span m=''827600''>get</span> <span m=''827740''>into</span>
  <span m=''827980''>why</span> <span m=''828270''>you</span> <span m=''828350''>need</span>
  <span m=''828510''>to</span> <span m=''828610''>do</span> <span m=''828780''>it</span>
  <span m=''829010''>this</span> <span m=''829210''>way</span> <span m=''829410''>exactly.</span>
  <span m=''829980''>Maybe,</span> <span m=''830370''>we''ll</span> <span m=''830470''>see</span>
  <span m=''830620''>it</span> <span m=''830690''>at</span> <span m=''830790''>some</span>
  <span m=''830940''>point.</span> </p><p><span m=''831940''>Essentially,</span> <span
  m=''832280''>some</span> <span m=''832490''>flaps</span> <span m=''832860''>can</span>
  <span m=''832980''>be</span> <span m=''833080''>hidden</span> <span m=''833380''>inside</span>
  <span m=''833710''>others,</span> <span m=''834250''>so</span> <span m=''834440''>you</span>
  <span m=''834590''>need</span> <span m=''834780''>this</span> <span m=''834940''>definition</span>
  <span m=''835430''>for it</span> <span m=''835620''>to</span> <span m=''835740''>really</span>
  <span m=''835950''>work.</span> <span m=''839260''>And</span> <span m=''839360''>then,</span>
  <span m=''839490''>there''s</span> <span m=''839650''>this</span> <span m=''839810''>extra</span>
  <span m=''840190''>constraint</span> <span m=''841110''>which</span> <span m=''841350''>is</span>
  <span m=''841630''>that</span> <span m=''842510''>my</span> <span m=''842780''>base</span>
  <span m=''843110''>is</span> <span m=''843240''>pointy</span> <span m=''843810''>at</span>
  <span m=''844030''>the</span> <span m=''844130''>leaves.</span> <span m=''844580''>Leaves</span>
  <span m=''844970''>are</span> <span m=''845120''>the</span> <span m=''846250''>vertices</span>
  <span m=''846930''>of</span> <span m=''847050''>the</span> <span m=''847140''>tree</span>
  <span m=''847320''>to</span> <span m=''847400''>have</span> <span m=''847600''>only</span>
  <span m=''847770''>one</span> <span m=''848070''>incident</span> <span m=''848440''>edge.</span>
  <span m=''849320''>And</span> <span m=''849720''>so</span> <span m=''849900''>I</span>
  <span m=''851070''>want</span> <span m=''851310''>there</span> <span m=''851400''>to</span>
  <span m=''851470''>be</span> <span m=''851600''>only</span> <span m=''851830''>one</span>
  <span m=''852060''>point</span> <span m=''852390''>that lives at the</span> <span
  m=''852740''>leaf.</span> </p><p><span m=''853800''>Obviously,</span> <span m=''854910''>elsewhere</span>
  <span m=''855270''>in</span> <span m=''855340''>the</span> <span m=''855430''>tree,</span>
  <span m=''855720''>there''s</span> <span m=''855910''>a</span> <span m=''855960''>whole</span>
  <span m=''856350''>bunch</span> <span m=''856600''>of</span> <span m=''856680''>points,</span>
  <span m=''856990''>a</span> <span m=''857050''>whole</span> <span m=''857270''>vertical</span>
  <span m=''857640''>segment,</span> <span m=''858480''>that</span> <span m=''858620''>all</span>
  <span m=''858750''>projects</span> <span m=''859140''>to</span> <span m=''859210''>that</span>
  <span m=''859380''>point.</span> <span m=''859600''>Here, I</span> <span m=''859900''>just</span>
  <span m=''860010''>want</span> <span m=''860190''>one.</span> <span m=''861460''>That''s</span>
  <span m=''861680''>important</span> <span m=''862030''>because</span> <span m=''862290''>I</span>
  <span m=''862370''>want</span> <span m=''862540''>to</span> <span m=''862600''>think</span>
  <span m=''862800''>about</span> <span m=''863010''>where</span> <span m=''863120''>the</span>
  <span m=''863220''>leaves</span> <span m=''863570''>are.</span> <span m=''864010''>And</span>
  <span m=''864320''>the</span> <span m=''864370''>whole</span> <span m=''864660''>idea</span>
  <span m=''865080''>in</span> <span m=''865220''>the</span> <span m=''865300''>tree</span>
  <span m=''865490''>method</span> <span m=''865790''>is</span> <span m=''865890''>to</span>
  <span m=''865990''>think</span> <span m=''866240''>about</span> <span m=''866500''>how</span>
  <span m=''866710''>to</span> <span m=''866800''>place</span> <span m=''867130''>the</span>
  <span m=''867220''>leaves</span> <span m=''868250''>on</span> <span m=''868450''>your</span>
  <span m=''868570''>piece</span> <span m=''868790''>of</span> <span m=''868860''>paper</span>
  <span m=''869640''>so</span> <span m=''869890''>that</span> <span m=''870080''>this</span>
  <span m=''870760''>folding</span> <span m=''871220''>exists.</span> </p><p><span
  m=''873790''>So</span> <span m=''874260''>that''s</span> <span m=''874500''>what</span>
  <span m=''874640''>we''re</span> <span m=''874770''>going</span> <span m=''874900''>to</span>
  <span m=''874980''>do.</span> <span m=''891220''>The</span> <span m=''891330''>tree</span>
  <span m=''891520''>method</span> <span m=''891820''>is</span> <span m=''891960''>kind</span>
  <span m=''892210''>of</span> <span m=''892410''>surprising</span> <span m=''893100''>in</span>
  <span m=''893170''>its</span> <span m=''893240''>simplicity.</span> <span m=''894800''>There''s</span>
  <span m=''895000''>a</span> <span m=''895050''>bunch</span> <span m=''895290''>of</span>
  <span m=''895330''>details</span> <span m=''895700''>to</span> <span m=''895790''>make</span>
  <span m=''896000''>it</span> <span m=''896060''>work.</span> <span m=''896410''>But</span>
  <span m=''896430''>the</span> <span m=''896550''>idea</span> <span m=''896810''>is</span>
  <span m=''897040''>actually</span> <span m=''897290''>very</span> <span m=''897540''>simple.</span>
  <span m=''900350''>Let''s</span> <span m=''900540''>suppose</span> <span m=''901860''>you</span>
  <span m=''902020''>want</span> <span m=''902170''>ability</span> <span m=''902560''>uniaxial</span>
  <span m=''903170''>base.</span> <span m=''904680''>I''ll</span> <span m=''904870''>tell</span>
  <span m=''905050''>you</span> <span m=''905180''>something</span> <span m=''905580''>that</span>
  <span m=''905660''>must</span> <span m=''906130''>be</span> <span m=''906250''>satisfied</span>
  <span m=''906930''>by</span> <span m=''907100''>your</span> <span m=''907310''>uniaxial</span>
  <span m=''907940''>base,</span> <span m=''908990''>a</span> <span m=''909060''>necessary</span>
  <span m=''909590''>condition.</span> </p><p><span m=''912490''>Assuming</span> <span
  m=''914360''>you''re</span> <span m=''914540''>starting</span> <span m=''914970''>from</span>
  <span m=''915330''>a</span> <span m=''915420''>convex</span> <span m=''915950''>piece</span>
  <span m=''916130''>of</span> <span m=''916220''>paper,</span> <span m=''920866''>which</span>
  <span m=''921337''>is</span> <span m=''921810''>the</span> <span m=''921930''>case</span>
  <span m=''922390''>we</span> <span m=''922420''>usually</span> <span m=''922780''>care</span>
  <span m=''922980''>about.</span> <span m=''923725''>Actually,</span> <span m=''924220''>we''re</span>
  <span m=''924500''>starting</span> <span m=''924770''>from a</span> <span m=''924940''>square,</span>
  <span m=''925210''>a</span> <span m=''925480''>rectangle,</span> <span m=''926240''>or</span>
  <span m=''926300''>something</span> <span m=''927270''>convex.</span> <span m=''929970''>Here''s</span>
  <span m=''930270''>what</span> <span m=''930400''>has</span> <span m=''930610''>to</span>
  <span m=''930700''>be</span> <span m=''930840''>true.</span> <span m=''949740''>I</span>
  <span m=''950260''>didn''t</span> <span m=''950950''>give</span> <span m=''951170''>a</span>
  <span m=''951230''>name,</span> <span m=''951560''>but</span> <span m=''952140''>this</span>
  <span m=''952600''>graph</span> <span m=''955900''>that''s</span> <span m=''956040''>supposed</span>
  <span m=''956300''>to</span> <span m=''956360''>be</span> <span m=''956470''>a</span>
  <span m=''956540''>tree,</span> <span m=''957440''>I''m</span> <span m=''957510''>going</span>
  <span m=''957610''>to</span> <span m=''957680''>call</span> <span m=''958520''>the</span>
  <span m=''958600''>shadow</span> <span m=''959010''>tree</span> <span m=''963810''>for</span>
  <span m=''964190''>obvious</span> <span m=''964530''>reasons.</span> </p><p><span
  m=''965850''>And</span> <span m=''966120''>now, I</span> <span m=''966260''>want</span>
  <span m=''966470''>to</span> <span m=''966550''>take</span> <span m=''966890''>two</span>
  <span m=''967090''>points</span> <span m=''967840''>in</span> <span m=''967960''>the</span>
  <span m=''968030''>shadow</span> <span m=''968400''>tree,</span> <span m=''969200''>measure</span>
  <span m=''969630''>their</span> <span m=''969790''>distance</span> <span m=''970600''>in</span>
  <span m=''970800''>a</span> <span m=''970960''>tree</span> <span m=''971280''>sense.</span>
  <span m=''971990''>So</span> <span m=''972720''>I</span> <span m=''972760''>have</span>
  <span m=''972990''>some</span> <span m=''974050''>tree</span> <span m=''974550''>like</span>
  <span m=''974800''>this.</span> <span m=''976370''>I</span> <span m=''976450''>have</span>
  <span m=''976660''>two</span> <span m=''976830''>points</span> <span m=''977300''>like,</span>
  <span m=''977500''>say,</span> <span m=''977740''>this</span> <span m=''977990''>point</span>
  <span m=''978980''>and</span> <span m=''979080''>that</span> <span m=''979320''>point.</span>
  <span m=''980130''>The</span> <span m=''980260''>distance</span> <span m=''980700''>between</span>
  <span m=''981060''>them</span> <span m=''981760''>is</span> <span m=''981980''>the</span>
  <span m=''982040''>distance</span> <span m=''982630''>as</span> <span m=''982910''>measured</span>
  <span m=''983870''>if</span> <span m=''984000''>you</span> <span m=''984080''>had</span>
  <span m=''984230''>to</span> <span m=''984310''>walk</span> <span m=''984620''>in</span>
  <span m=''984760''>the</span> <span m=''984850''>tree,</span> <span m=''986000''>how</span>
  <span m=''986240''>far</span> <span m=''986580''>is</span> <span m=''986710''>it</span>
  <span m=''986850''>to</span> <span m=''986940''>go</span> <span m=''987190''>from</span>
  <span m=''987410''>here</span> <span m=''987620''>to</span> <span m=''987690''>here.</span>
  </p><p><span m=''988490''>And</span> <span m=''988580''>because</span> <span m=''988930''>our</span>
  <span m=''989040''>tree</span> <span m=''989300''>is</span> <span m=''989430''>a</span>
  <span m=''989490''>metric</span> <span m=''989880''>tree,</span> <span m=''990100''>because</span>
  <span m=''990390''>we</span> <span m=''990480''>specified</span> <span m=''991060''>all</span>
  <span m=''991160''>the</span> <span m=''991270''>edge</span> <span m=''991440''>lengths,</span>
  <span m=''991690''>we</span> <span m=''991800''>can</span> <span m=''992040''>just</span>
  <span m=''992690''>add</span> <span m=''992880''>up</span> <span m=''992970''>those</span>
  <span m=''993160''>lengths,</span> <span m=''993420''>measure</span> <span m=''993690''>them.</span>
  <span m=''994850''>And</span> <span m=''994970''>that''s</span> <span m=''995140''>the</span>
  <span m=''995210''>distance</span> <span m=''995620''>between</span> <span m=''995820''>two</span>
  <span m=''995970''>points</span> <span m=''996930''>in</span> <span m=''997170''>the</span>
  <span m=''997250''>tree.</span> <span m=''998160''>That</span> <span m=''998370''>must</span>
  <span m=''998670''>be</span> <span m=''999350''>less</span> <span m=''999650''>than</span>
  <span m=''999770''>or</span> <span m=''999870''>equal</span> <span m=''1000120''>to</span>
  <span m=''1001730''>the</span> <span m=''1001810''>distance</span> <span m=''1002330''>between</span>
  <span m=''1002520''>those</span> <span m=''1002700''>two</span> <span m=''1002860''>points</span>
  <span m=''1005430''>on</span> <span m=''1005600''>the</span> <span m=''1005660''>piece</span>
  <span m=''1005870''>of</span> <span m=''1005940''>paper.</span> </p><p><span m=''1026960''>What</span>
  <span m=''1027190''>does</span> <span m=''1027369''>that</span> <span m=''1027609''>mean?</span>
  <span m=''1028730''>So</span> <span m=''1028940''>on</span> <span m=''1029000''>piece</span>
  <span m=''1029200''>of</span> <span m=''1029250''>paper</span> <span m=''1030100''>that''s</span>
  <span m=''1030410''>convex--</span> <span m=''1032160''>so</span> <span m=''1032380''>it</span>
  <span m=''1032540''>might</span> <span m=''1032760''>not</span> <span m=''1032900''>be</span>
  <span m=''1032980''>a</span> <span m=''1033040''>square,</span> <span m=''1033400''>but</span>
  <span m=''1034700''>square''s</span> <span m=''1035349''>easier</span> <span m=''1035660''>picture</span>
  <span m=''1036020''>draw.</span> <span m=''1037089''>The</span> <span m=''1037220''>distance</span>
  <span m=''1037579''>between</span> <span m=''1037810''>them</span> <span m=''1038170''>is</span>
  <span m=''1038349''>that.</span> <span m=''1040060''>Pretty</span> <span m=''1041099''>simple.</span>
  <span m=''1042260''>So</span> <span m=''1042440''>what</span> <span m=''1042560''>does</span>
  <span m=''1042690''>this</span> <span m=''1042829''>mean?</span> <span m=''1044599''>I''m</span>
  <span m=''1044750''>taking</span> <span m=''1045119''>this</span> <span m=''1045230''>square.</span>
  <span m=''1045750''>Somehow,</span> <span m=''1046005''>I''m</span> <span m=''1046260''>folding</span>
  <span m=''1046760''>it</span> <span m=''1046910''>into</span> <span m=''1047329''>a</span>
  <span m=''1047410''>base</span> <span m=''1048119''>whose</span> <span m=''1048349''>projection</span>
  <span m=''1049050''>is</span> <span m=''1049300''>the</span> <span m=''1049380''>tree.</span>
  </p><p><span m=''1050650''>So</span> <span m=''1051400''>I</span> <span m=''1051500''>look</span>
  <span m=''1051730''>at</span> <span m=''1051800''>these</span> <span m=''1051970''>two</span>
  <span m=''1052100''>points,</span> <span m=''1052950''>p</span> <span m=''1053150''>and</span>
  <span m=''1053280''>q,</span> <span m=''1056630''>I</span> <span m=''1056770''>fold</span>
  <span m=''1057200''>them</span> <span m=''1057720''>somewhere</span> <span m=''1058190''>in</span>
  <span m=''1058280''>the</span> <span m=''1058360''>3D</span> <span m=''1058660''>picture</span>
  <span m=''1058940''>which</span> <span m=''1059100''>is</span> <span m=''1059180''>not</span>
  <span m=''1059440''>drawn</span> <span m=''1059750''>up</span> <span m=''1059900''>here.</span>
  <span m=''1060980''>Those</span> <span m=''1061270''>points--</span> <span m=''1061850''>so</span>
  <span m=''1061940''>maybe</span> <span m=''1062190''>there''s</span> <span m=''1062380''>a
  p</span> <span m=''1062843''>up</span> <span m=''1063306''>here</span> <span m=''1064370''>and</span>
  <span m=''1064530''>a q up</span> <span m=''1064630''>here.</span> <span m=''1066070''>I</span>
  <span m=''1066180''>project</span> <span m=''1066740''>those</span> <span m=''1067000''>points</span>
  <span m=''1067690''>down</span> <span m=''1068080''>onto</span> <span m=''1068460''>the</span>
  <span m=''1068580''>floor</span> <span m=''1069090''>which</span> <span m=''1069380''>is</span>
  <span m=''1069510''>going</span> <span m=''1069650''>to</span> <span m=''1069700''>fall</span>
  <span m=''1070020''>on</span> <span m=''1070270''>the</span> <span m=''1070370''>tree</span>
  <span m=''1070950''>by</span> <span m=''1071100''>this</span> <span m=''1071320''>definition.</span>
  </p><p><span m=''1073000''>Call</span> <span m=''1073300''>that,</span> <span m=''1073560''>let''s</span>
  <span m=''1073700''>say,</span> <span m=''1073840''>p</span> <span m=''1074140''>prime</span>
  <span m=''1074690''>for</span> <span m=''1074850''>the</span> <span m=''1075010''>projected</span>
  <span m=''1075480''>version</span> <span m=''1075810''>of</span> <span m=''1075890''>p,</span>
  <span m=''1076390''>q</span> <span m=''1076890''>prime.</span> <span m=''1078160''>I</span>
  <span m=''1078250''>measure</span> <span m=''1078630''>the</span> <span m=''1078760''>distance</span>
  <span m=''1079190''>here.</span> <span m=''1080360''>That</span> <span m=''1080620''>has</span>
  <span m=''1080920''>to</span> <span m=''1081020''>be--</span> <span m=''1082720''>the</span>
  <span m=''1082840''>distance</span> <span m=''1083740''>between</span> <span m=''1083990''>p</span>
  <span m=''1084210''>prime</span> <span m=''1084490''>and q</span> <span m=''1084630''>prime</span>
  <span m=''1084840''>in</span> <span m=''1084960''>the</span> <span m=''1085050''>tree</span>
  <span m=''1085270''>should</span> <span m=''1085450''>be</span> <span m=''1085560''>less</span>
  <span m=''1085820''>than</span> <span m=''1085930''>or</span> <span m=''1085980''>equal</span>
  <span m=''1086210''>to</span> <span m=''1086350''>the</span> <span m=''1086450''>distance</span>
  <span m=''1086840''>between</span> <span m=''1087120''>p</span> <span m=''1087370''>and</span>
  <span m=''1087500''>q</span> <span m=''1087950''>in the</span> <span m=''1088400''>piece</span>
  <span m=''1088610''>of</span> <span m=''1088690''>paper,</span> <span m=''1089070''>for</span>
  <span m=''1089270''>every</span> <span m=''1089750''>pair</span> <span m=''1090020''>points</span>
  <span m=''1090300''>p</span> <span m=''1090440''>and</span> <span m=''1090550''>q.</span>
  </p><p><span m=''1091110''>That''s</span> <span m=''1091370''>the</span> <span m=''1091420''>condition.</span>
  <span m=''1093870''>It''s</span> <span m=''1094780''>almost</span> <span m=''1095340''>trivial</span>
  <span m=''1095900''>to</span> <span m=''1096020''>show</span> <span m=''1097350''>because</span>
  <span m=''1098870''>when</span> <span m=''1099650''>I</span> <span m=''1099780''>take</span>
  <span m=''1100070''>this</span> <span m=''1100250''>segment</span> <span m=''1100660''>of</span>
  <span m=''1100790''>paper,</span> <span m=''1102480''>I</span> <span m=''1102600''>fold</span>
  <span m=''1102840''>the</span> <span m=''1102890''>piece</span> <span m=''1103070''>of</span>
  <span m=''1103170''>paper.</span> <span m=''1103490''>But</span> <span m=''1103620''>in</span>
  <span m=''1103720''>particular,</span> <span m=''1104390''>I</span> <span m=''1104500''>fold</span>
  <span m=''1104980''>p</span> <span m=''1105130''>and</span> <span m=''1105230''>q</span>
  <span m=''1105440''>somehow.</span> <span m=''1106250''>I</span> <span m=''1106340''>can''t</span>
  <span m=''1106750''>get</span> <span m=''1106940''>p</span> <span m=''1107130''>and</span>
  <span m=''1107240''>q</span> <span m=''1107440''>farther</span> <span m=''1107910''>away</span>
  <span m=''1108130''>from</span> <span m=''1108330''>each</span> <span m=''1108500''>other</span>
  <span m=''1109280''>because</span> <span m=''1109560''>folding</span> <span m=''1110020''>only</span>
  <span m=''1110260''>makes</span> <span m=''1110570''>things</span> <span m=''1110930''>closer.</span>
  </p><p><span m=''1112650''>There,</span> <span m=''1112860''>I''m</span> <span m=''1112940''>assuming</span>
  <span m=''1113350''>that</span> <span m=''1113480''>the</span> <span m=''1113570''>piece
  of</span> <span m=''1113800''>paper is</span> <span m=''1114160''>convex.</span>
  <span m=''1115530''>There''s</span> <span m=''1115710''>no</span> <span m=''1115870''>way</span>
  <span m=''1115960''>to</span> <span m=''1116040''>fold</span> <span m=''1116570''>and</span>
  <span m=''1116830''>stretch</span> <span m=''1117580''>pq</span> <span m=''1118040''>because</span>
  <span m=''1118220''>that''s</span> <span m=''1118430''>a</span> <span m=''1118470''>segment</span>
  <span m=''1118840''>of</span> <span m=''1118920''>paper. It</span> <span m=''1119320''>can</span>
  <span m=''1119510''>only</span> <span m=''1120040''>contract.</span> <span m=''1121670''>I</span>
  <span m=''1121730''>mean,</span> <span m=''1122420''>you</span> <span m=''1122550''>can
  fold</span> <span m=''1122920''>the</span> <span m=''1123020''>segment</span> <span
  m=''1123410''>something</span> <span m=''1123670''>like</span> <span m=''1123860''>this.</span>
  <span m=''1124950''>Then,</span> <span m=''1125100''>the</span> <span m=''1125190''>distance</span>
  <span m=''1125670''>between p and</span> <span m=''1126110''>q</span> <span m=''1127170''>gets</span>
  <span m=''1127440''>smaller</span> <span m=''1128380''>than</span> <span m=''1128760''>the</span>
  <span m=''1129090''>length</span> <span m=''1129380''>of</span> <span m=''1129470''>this</span>
  <span m=''1130550''>segment.</span> <span m=''1130890''>Because</span> <span m=''1131120''>if</span>
  <span m=''1131260''>I</span> <span m=''1131330''>took</span> <span m=''1131610''>this--</span>
  <span m=''1133725''>this</span> <span m=''1134150''>line</span> <span m=''1134370''>segment</span>
  <span m=''1134670''>of</span> <span m=''1134750''>paper</span> <span m=''1135120''>that</span>
  <span m=''1135220''>got</span> <span m=''1135460''>folded.</span> <span m=''1136650''>If</span>
  <span m=''1136760''>I</span> <span m=''1136820''>project</span> <span m=''1137310''>it</span>
  <span m=''1137390''>onto</span> <span m=''1137630''>the</span> <span m=''1137710''>line</span>
  <span m=''1138020''>here,</span> <span m=''1138240''>it''s</span> <span m=''1138360''>only</span>
  <span m=''1138560''>going</span> <span m=''1138690''>to</span> <span m=''1138760''>get</span>
  <span m=''1138930''>shorter.</span> </p><p><span m=''1141120''>So</span> <span m=''1141220''>I</span>
  <span m=''1141290''>fold</span> <span m=''1141570''>p and</span> <span m=''1141890''>q.</span>
  <span m=''1142030''>They</span> <span m=''1142220''>get</span> <span m=''1142390''>closer</span>
  <span m=''1144290''>in</span> <span m=''1144560''>three-space.</span> <span m=''1145750''>And</span>
  <span m=''1145940''>then,</span> <span m=''1146050''>I</span> <span m=''1146090''>project</span>
  <span m=''1146510''>them</span> <span m=''1146640''>down</span> <span m=''1146830''>to</span>
  <span m=''1146920''>the</span> <span m=''1147030''>floor.</span> <span m=''1148430''>They</span>
  <span m=''1148680''>can</span> <span m=''1149130''>also</span> <span m=''1149500''>only</span>
  <span m=''1149730''>get</span> <span m=''1149900''>closer</span> <span m=''1151010''>when</span>
  <span m=''1151140''>I</span> <span m=''1151220''>do</span> <span m=''1151340''>that.</span>
  <span m=''1156170''>So</span> <span m=''1156310''>that''s</span> <span m=''1156540''>essentially</span>
  <span m=''1156980''>the</span> <span m=''1157100''>proof.</span> <span m=''1158476''>Do</span>
  <span m=''1158870''>I</span> <span m=''1158980''>need</span> <span m=''1159150''>to</span>
  <span m=''1159230''>spell</span> <span m=''1159530''>that</span> <span m=''1159710''>out?</span>
  <span m=''1160220''>So</span> <span m=''1160370''>you</span> <span m=''1160450''>have</span>
  <span m=''1160750''>the</span> <span m=''1160940''>line</span> <span m=''1161150''>segment</span>
  <span m=''1162100''>on</span> <span m=''1162220''>the</span> <span m=''1162290''>paper.</span>
  <span m=''1162850''>You</span> <span m=''1162970''>fold it.</span> <span m=''1163410''>It</span>
  <span m=''1163490''>gets</span> <span m=''1163660''>shorter.</span> <span m=''1164420''>You</span>
  <span m=''1164560''>project</span> <span m=''1164830''>it</span> <span m=''1165100''>onto</span>
  <span m=''1165330''>the</span> <span m=''1165400''>floor.</span> <span m=''1165880''>It</span>
  <span m=''1165970''>also</span> <span m=''1166230''>get</span> <span m=''1166400''>shorter.</span>
  </p><p><span m=''1166730''>Therefore,</span> <span m=''1167590''>whatever</span>
  <span m=''1167990''>this</span> <span m=''1168190''>distance</span> <span m=''1168465''>is</span>
  <span m=''1168740''>on</span> <span m=''1168850''>the</span> <span m=''1168940''>tree</span>
  <span m=''1169210''>has</span> <span m=''1169430''>to</span> <span m=''1169530''>be</span>
  <span m=''1169690''>less</span> <span m=''1169930''>than</span> <span m=''1170030''>or</span>
  <span m=''1170130''>equal</span> <span m=''1170250''>to</span> <span m=''1170910''>the</span>
  <span m=''1170980''>distance</span> <span m=''1171320''>you</span> <span m=''1171400''>started</span>
  <span m=''1171750''>with.</span> <span m=''1172310''>So</span> <span m=''1172340''>this</span>
  <span m=''1172550''>may</span> <span m=''1172710''>seem</span> <span m=''1172950''>kind</span>
  <span m=''1173180''>of</span> <span m=''1173250''>trivial.</span> <span m=''1174400''>But</span>
  <span m=''1174740''>the</span> <span m=''1174840''>surprising</span> <span m=''1175380''>thing</span>
  <span m=''1176250''>is</span> <span m=''1176490''>it</span> <span m=''1176620''>this</span>
  <span m=''1176810''>is</span> <span m=''1176940''>really</span> <span m=''1177290''>all</span>
  <span m=''1177600''>you</span> <span m=''1177790''>need.</span> <span m=''1180180''>So</span>
  <span m=''1180260''>this</span> <span m=''1180520''>is</span> <span m=''1180760''>true</span>
  <span m=''1181090''>between</span> <span m=''1181510''>any</span> <span m=''1181790''>two</span>
  <span m=''1181980''>points</span> <span m=''1182320''>in</span> <span m=''1182390''>the</span>
  <span m=''1182480''>shadow</span> <span m=''1182850''>tree.</span> </p><p><span
  m=''1183600''>In</span> <span m=''1183620''>fact,</span> <span m=''1183990''>we''re</span>
  <span m=''1184090''>going</span> <span m=''1184190''>to</span> <span m=''1184290''>focus</span>
  <span m=''1184470''>on</span> <span m=''1184570''>the</span> <span m=''1184650''>leaves.</span>
  <span m=''1185060''>We''ll</span> <span m=''1185170''>say,</span> <span m=''1185500''>all</span>
  <span m=''1185620''>right,</span> <span m=''1186220''>so</span> <span m=''1186370''>in</span>
  <span m=''1186490''>particular,</span> <span m=''1187590''>I''ve</span> <span m=''1187750''>got</span>
  <span m=''1187940''>a</span> <span m=''1188010''>place</span> <span m=''1188320''>this</span>
  <span m=''1188500''>leaf,</span> <span m=''1189220''>and</span> <span m=''1189770''>each</span>
  <span m=''1190020''>of</span> <span m=''1190130''>these</span> <span m=''1190340''>six</span>
  <span m=''1190660''>leaves</span> <span m=''1191000''>here,</span> <span m=''1191750''>I</span>
  <span m=''1191820''>have</span> <span m=''1192020''>to</span> <span m=''1192120''>place</span>
  <span m=''1192430''>them</span> <span m=''1192600''>somewhere</span> <span m=''1193140''>on</span>
  <span m=''1193210''>the</span> <span m=''1193310''>piece</span> <span m=''1193510''>of</span>
  <span m=''1193600''>paper.</span> <span m=''1194430''>I</span> <span m=''1194530''>better</span>
  <span m=''1194890''>do</span> <span m=''1195170''>it</span> <span m=''1195670''>so</span>
  <span m=''1195940''>that that</span> <span m=''1196190''>condition</span> <span
  m=''1196560''>is</span> <span m=''1196640''>satisfied.</span> <span m=''1198310''>I</span>
  <span m=''1198380''>have</span> <span m=''1198640''>to</span> <span m=''1199240''>place</span>
  <span m=''1199540''>these</span> <span m=''1199720''>two</span> <span m=''1199880''>leaves</span>
  <span m=''1200210''>and</span> <span m=''1200300''>the</span> <span m=''1200390''>piece</span>
  <span m=''1200590''>of</span> <span m=''1200680''>paper--</span> <span m=''1201150''>let''s</span>
  <span m=''1201400''>say</span> <span m=''1201990''>this</span> <span m=''1202310''>distance</span>
  <span m=''1202860''>is</span> <span m=''1203090''>one,</span> <span m=''1204250''>and</span>
  <span m=''1204490''>this</span> <span m=''1204710''>distance</span> <span m=''1205280''>is</span>
  <span m=''1205590''>one.</span> </p><p><span m=''1206750''>These</span> <span m=''1206980''>two</span>
  <span m=''1207150''>leaves</span> <span m=''1207430''>have</span> <span m=''1207660''>to</span>
  <span m=''1207750''>be</span> <span m=''1207900''>placed</span> <span m=''1208220''>on</span>
  <span m=''1208270''>the</span> <span m=''1208360''>piece</span> <span m=''1208560''>of</span>
  <span m=''1208630''>paper</span> <span m=''1208970''>such</span> <span m=''1209210''>that</span>
  <span m=''1209850''>their</span> <span m=''1210060''>distance is</span> <span m=''1210550''>at</span>
  <span m=''1210610''>least</span> <span m=''1210870''>two.</span> <span m=''1212110''>And</span>
  <span m=''1212460''>the distance</span> <span m=''1212870''>between</span> <span
  m=''1213090''>these</span> <span m=''1213280''>two</span> <span m=''1213410''>guys</span>
  <span m=''1213650''>has</span> <span m=''1213820''>to</span> <span m=''1213910''>be</span>
  <span m=''1214020''>at</span> <span m=''1214090''>least</span> <span m=''1214350''>two</span>
  <span m=''1214870''>and</span> <span m=''1215150''>between</span> <span m=''1215430''>these</span>
  <span m=''1215590''>two</span> <span m=''1215710''>guys</span> <span m=''1215960''>has</span>
  <span m=''1216120''>to</span> <span m=''1216210''>be</span> <span m=''1216310''>at</span>
  <span m=''1216370''>least</span> <span m=''1216630''>two.</span> <span m=''1217300''>And</span>
  <span m=''1217850''>same</span> <span m=''1218180''>over</span> <span m=''1218370''>here.</span>
  <span m=''1218620''>Let''s</span> <span m=''1218760''>say</span> <span m=''1218890''>all</span>
  <span m=''1219030''>the</span> <span m=''1219160''>edge</span> <span m=''1219320''>lengths</span>
  <span m=''1219560''>are</span> <span m=''1219660''>one.</span> <span m=''1220270''>And</span>
  <span m=''1220590''>the</span> <span m=''1220670''>distance</span> <span m=''1221050''>between,</span>
  <span m=''1221310''>say,</span> <span m=''1221720''>this</span> <span m=''1222020''>leaf</span>
  <span m=''1222960''>and</span> <span m=''1223500''>this</span> <span m=''1223730''>leaf</span>
  <span m=''1224940''>has</span> <span m=''1225200''>to</span> <span m=''1225300''>be</span>
  <span m=''1225460''>at</span> <span m=''1225520''>least</span> <span m=''1225920''>three</span>
  <span m=''1226620''>because</span> <span m=''1226830''>the</span> <span m=''1226920''>distance</span>
  <span m=''1227290''>in</span> <span m=''1227400''>the</span> <span m=''1227490''>tree</span>
  <span m=''1227840''>is</span> <span m=''1228070''>three.</span> </p><p><span m=''1229510''>So</span>
  <span m=''1231230''>at</span> <span m=''1231440''>the</span> <span m=''1231530''>very</span>
  <span m=''1231790''>least,</span> <span m=''1232220''>we</span> <span m=''1232320''>should</span>
  <span m=''1232390''>place</span> <span m=''1232650''>the</span> <span m=''1232740''>points</span>
  <span m=''1232990''>on</span> <span m=''1233050''>the</span> <span m=''1233130''>paper</span>
  <span m=''1233550''>so that</span> <span m=''1233640''>those</span> <span m=''1233860''>conditions</span>
  <span m=''1234230''>are</span> <span m=''1234310''>satisfied,</span> <span m=''1234570''>and</span>
  <span m=''1234830''>it</span> <span m=''1234990''>turns</span> <span m=''1235270''>out,</span>
  <span m=''1235430''>that''s</span> <span m=''1235630''>enough</span> <span m=''1236450''>as</span>
  <span m=''1236630''>long</span> <span m=''1236940''>as</span> <span m=''1237010''>you</span>
  <span m=''1237130''>find</span> <span m=''1237450''>a</span> <span m=''1237500''>placement</span>
  <span m=''1237960''>of</span> <span m=''1238020''>the</span> <span m=''1238100''>points</span>
  <span m=''1238480''>such</span> <span m=''1238710''>as</span> <span m=''1238790''>those</span>
  <span m=''1238980''>conditions</span> <span m=''1239350''>are</span> <span m=''1239420''>satisfied.</span>
  <span m=''1240260''>There</span> <span m=''1240400''>will</span> <span m=''1240690''>be</span>
  <span m=''1240840''>a</span> <span m=''1240890''>folding</span> <span m=''1241930''>where</span>
  <span m=''1242080''>those</span> <span m=''1242410''>leaves</span> <span m=''1242680''>actually</span>
  <span m=''1243040''>come</span> <span m=''1243230''>from</span> <span m=''1243390''>those</span>
  <span m=''1243580''>points</span> <span m=''1243860''>of</span> <span m=''1243930''>paper.</span>
  </p><p><span m=''1244710''>That''s</span> <span m=''1244960''>the</span> <span m=''1245060''>crazy</span>
  <span m=''1245420''>part.</span> <span m=''1246500''>But</span> <span m=''1246750''>this</span>
  <span m=''1247090''>idea</span> <span m=''1247410''>is</span> <span m=''1247580''>actually</span>
  <span m=''1247900''>kind</span> <span m=''1248140''>of</span> <span m=''1249020''>obvious</span>
  <span m=''1249310''>in</span> <span m=''1249600''>some</span> <span m=''1249780''>sense.</span>
  <span m=''1250070''>I</span> <span m=''1250150''>mean,</span> <span m=''1250880''>once</span>
  <span m=''1251100''>you</span> <span m=''1251190''>know</span> <span m=''1251380''>it,</span>
  <span m=''1251470''>it''s</span> <span m=''1251600''>really</span> <span m=''1251860''>obvious.</span>
  <span m=''1252390''>But</span> <span m=''1253690''>what''s</span> <span m=''1253940''>surprising</span>
  <span m=''1254540''>is</span> <span m=''1254670''>it</span> <span m=''1254790''>this</span>
  <span m=''1255010''>is</span> <span m=''1255430''>all</span> <span m=''1255690''>you</span>
  <span m=''1255780''>need</span> <span m=''1256020''>to</span> <span m=''1256140''>worry</span>
  <span m=''1256440''>about.</span> <span m=''1257010''>There''s</span> <span m=''1257200''>a</span>
  <span m=''1257250''>lot</span> <span m=''1257400''>of</span> <span m=''1257460''>details</span>
  <span m=''1257850''>that</span> <span m=''1257970''>make</span> <span m=''1258150''>that</span>
  <span m=''1258320''>work,</span> <span m=''1258710''>but</span> <span m=''1259360''>you</span>
  <span m=''1259480''>can.</span> </p><p><span m=''1261490''>So</span> <span m=''1265450''>let</span>
  <span m=''1265640''>me</span> <span m=''1265760''>just</span> <span m=''1265960''>mention</span>
  <span m=''1266290''>one</span> <span m=''1266480''>detail</span> <span m=''1266940''>which</span>
  <span m=''1267120''>is</span> <span m=''1267280''>the</span> <span m=''1267810''>scale</span>
  <span m=''1269020''>factor.</span> <span m=''1269960''>If</span> <span m=''1270160''>you</span>
  <span m=''1270290''>fix</span> <span m=''1270800''>the</span> <span m=''1270910''>size,</span>
  <span m=''1271860''>the</span> <span m=''1272290''>edge</span> <span m=''1272490''>lengths</span>
  <span m=''1272730''>on</span> <span m=''1272830''>the</span> <span m=''1272930''>tree</span>
  <span m=''1273360''>which</span> <span m=''1273560''>is</span> <span m=''1273650''>the</span>
  <span m=''1273760''>usual,</span> <span m=''1274300''>which</span> <span m=''1274510''>is</span>
  <span m=''1274590''>one</span> <span m=''1274740''>way</span> <span m=''1274830''>to</span>
  <span m=''1274910''>think</span> <span m=''1275090''>about</span> <span m=''1275360''>it,</span>
  <span m=''1277000''>and</span> <span m=''1277320''>you</span> <span m=''1277430''>start</span>
  <span m=''1277680''>with</span> <span m=''1277800''>some</span> <span m=''1277970''>square--</span>
  <span m=''1278760''>like</span> <span m=''1278950''>if</span> <span m=''1279040''>I</span>
  <span m=''1279100''>start</span> <span m=''1279360''>with</span> <span m=''1279490''>a</span>
  <span m=''1279550''>one</span> <span m=''1279750''>by</span> <span m=''1279880''>one</span>
  <span m=''1280100''>square,</span> <span m=''1280320''>there''s</span> <span m=''1280510''>no</span>
  <span m=''1280780''>way</span> <span m=''1280970''>I''m</span> <span m=''1281050''>going</span>
  <span m=''1281150''>to</span> <span m=''1281210''>fold</span> <span m=''1281460''>that</span>
  <span m=''1281650''>tree.</span> <span m=''1281860''>There''s</span> <span m=''1282010''>just</span>
  <span m=''1282200''>not</span> <span m=''1282350''>enough</span> <span m=''1283150''>distance</span>
  <span m=''1283820''>in</span> <span m=''1284020''>the</span> <span m=''1284170''>square.</span>
  </p><p><span m=''1284870''>So</span> <span m=''1284990''>what</span> <span m=''1285090''>I''d</span>
  <span m=''1285130''>like</span> <span m=''1285310''>to</span> <span m=''1285390''>do</span>
  <span m=''1285490''>is</span> <span m=''1285610''>find</span> <span m=''1285830''>the</span>
  <span m=''1285920''>smallest</span> <span m=''1286430''>square</span> <span m=''1286820''>that</span>
  <span m=''1286950''>can fold</span> <span m=''1287350''>into</span> <span m=''1287520''>this</span>
  <span m=''1287740''>thing.</span> <span m=''1288970''>Or</span> <span m=''1289180''>equivalently</span>
  <span m=''1289820''>find--</span> <span m=''1290870''>you</span> <span m=''1291010''>can</span>
  <span m=''1291120''>think</span> <span m=''1291280''>of</span> <span m=''1291350''>scaling</span>
  <span m=''1291810''>the</span> <span m=''1291900''>piece</span> <span m=''1292080''>of</span>
  <span m=''1292140''>paper,</span> <span m=''1292780''>or</span> <span m=''1293080''>you</span>
  <span m=''1293180''>can</span> <span m=''1293340''>think</span> <span m=''1293540''>of</span>
  <span m=''1293630''>scaling</span> <span m=''1294110''>the</span> <span m=''1294220''>tree</span>
  <span m=''1295420''>with</span> <span m=''1295570''>a</span> <span m=''1295610''>fixed</span>
  <span m=''1295920''>piece</span> <span m=''1296090''>of</span> <span m=''1296170''>paper.</span>
  <span m=''1297150''>Doesn''t</span> <span m=''1297340''>really</span> <span m=''1297530''>matter.</span>
  <span m=''1298850''>In</span> <span m=''1298990''>general,</span> <span m=''1300310''>you</span>
  <span m=''1300460''>get</span> <span m=''1300690''>this</span> <span m=''1301430''>problem</span>
  <span m=''1302590''>which</span> <span m=''1302930''>I''ll</span> <span m=''1303110''>call</span>
  <span m=''1303400''>scale</span> <span m=''1303730''>optimization.</span> <span
  m=''1304450''>This</span> <span m=''1304610''>is</span> <span m=''1304690''>the</span>
  <span m=''1304770''>hard</span> <span m=''1305040''>problem.</span> </p><p><span
  m=''1313970''>So</span> <span m=''1319270''>let''s</span> <span m=''1319530''>say--</span>
  <span m=''1337940''>just</span> <span m=''1338100''>defining</span> <span m=''1338440''>some</span>
  <span m=''1338590''>variables.</span> <span m=''1339000''>So</span> <span m=''1339290''>P</span>
  <span m=''1339630''>i,</span> <span m=''1340510''>I''m</span> <span m=''1340620''>going</span>
  <span m=''1340730''>to</span> <span m=''1340990''>maybe</span> <span m=''1341270''>number</span>
  <span m=''1341540''>the</span> <span m=''1341660''>leaves</span> <span m=''1342470''>or</span>
  <span m=''1342610''>label</span> <span m=''1343000''>label</span> <span m=''1343310''>them</span>
  <span m=''1343470''>somehow,</span> <span m=''1344060''>various</span> <span m=''1344310''>letters.</span>
  <span m=''1345150''>And</span> <span m=''1345500''>then,</span> <span m=''1345680''>P</span>
  <span m=''1345890''>i</span> <span m=''1346110''>is</span> <span m=''1346240''>going</span>
  <span m=''1346360''>to</span> <span m=''1346430''>be</span> <span m=''1346550''>the</span>
  <span m=''1346650''>point</span> <span m=''1347690''>where</span> <span m=''1347800''>that--</span>
  <span m=''1348640''>of</span> <span m=''1348830''>paper</span> <span m=''1349310''>that</span>
  <span m=''1349460''>actually</span> <span m=''1349770''>forms</span> <span m=''1350200''>that</span>
  <span m=''1350410''>leaf</span> <span m=''1350680''>in</span> <span m=''1350850''>the</span>
  <span m=''1350920''>folded</span> <span m=''1351290''>state.</span> <span m=''1352020''>That</span>
  <span m=''1352280''>leaf</span> <span m=''1352990''>which</span> <span m=''1353180''>corresponds</span>
  <span m=''1353700''>to</span> <span m=''1353840''>a</span> <span m=''1353930''>single</span>
  <span m=''1354950''>point</span> <span m=''1355190''>of</span> <span m=''1355280''>paper</span>
  <span m=''1357240''>projects</span> <span m=''1357410''>to that</span> <span m=''1357620''>leaf.</span>
  </p><p><span m=''1360900''>And</span> <span m=''1361140''>then,</span> <span m=''1361420''>my</span>
  <span m=''1361570''>goal</span> <span m=''1362050''>is</span> <span m=''1362260''>to</span>
  <span m=''1362380''>maximize</span> <span m=''1364550''>some</span> <span m=''1364810''>scale</span>
  <span m=''1365190''>factor</span> <span m=''1365700''>which</span> <span m=''1365990''>I''ll</span>
  <span m=''1366190''>call</span> <span m=''1366490''>lambda.</span> <span m=''1370990''>Subject</span>
  <span m=''1371480''>to</span> <span m=''1371560''>a</span> <span m=''1371600''>bunch</span>
  <span m=''1371840''>of</span> <span m=''1371930''>constraints</span> <span m=''1375600''>which</span>
  <span m=''1375890''>are</span> <span m=''1375940''>just</span> <span m=''1376150''>those</span>
  <span m=''1376370''>constraints,</span> <span m=''1379390''>except</span> <span
  m=''1379770''>that I</span> <span m=''1380100''>add a</span> <span m=''1380150''>scale</span>
  <span m=''1380430''>factor.</span> <span m=''1390100''>So</span> <span m=''1390250''>for</span>
  <span m=''1390320''>every</span> <span m=''1390640''>pair</span> <span m=''1390890''>of</span>
  <span m=''1390960''>leaves,</span> <span m=''1391340''>i</span> <span m=''1391540''>and</span>
  <span m=''1391740''>j,</span> <span m=''1394910''>I''m</span> <span m=''1395050''>going</span>
  <span m=''1395160''>to</span> <span m=''1395200''>measure</span> <span m=''1395550''>the</span>
  <span m=''1395670''>distance</span> <span m=''1396080''>between</span> <span m=''1396390''>those</span>
  <span m=''1396660''>leaves</span> <span m=''1397470''>in</span> <span m=''1397620''>the</span>
  <span m=''1397710''>tree.</span> <span m=''1398190''>This</span> <span m=''1398370''>as</span>
  <span m=''1398490''>a</span> <span m=''1398550''>tree</span> <span m=''1398780''>distance.</span>
  </p><p><span m=''1399930''>Compare</span> <span m=''1400310''>that</span> <span
  m=''1400620''>to</span> <span m=''1400710''>the</span> <span m=''1400830''>distance</span>
  <span m=''1401430''>and</span> <span m=''1401590''>the</span> <span m=''1401670''>piece</span>
  <span m=''1401870''>of</span> <span m=''1401940''>paper</span> <span m=''1402300''>between</span>
  <span m=''1402560''>those</span> <span m=''1402730''>two</span> <span m=''1402850''>points,</span>
  <span m=''1403215''>the</span> <span m=''1403580''>Euclidean</span> <span m=''1404290''>distance.</span>
  <span m=''1405450''>And</span> <span m=''1405870''>instead</span> <span m=''1406210''>of</span>
  <span m=''1406280''>requiring</span> <span m=''1406700''>that</span> <span m=''1406770''>this</span>
  <span m=''1406980''>is</span> <span m=''1407080''>greater</span> <span m=''1407300''>than</span>
  <span m=''1407380''>or</span> <span m=''1407400''>equal</span> <span m=''1407610''>to</span>
  <span m=''1407680''>this,</span> <span m=''1407930''>which</span> <span m=''1408120''>is</span>
  <span m=''1408210''>the</span> <span m=''1408310''>usual</span> <span m=''1408610''>one,</span>
  <span m=''1408820''>I''m</span> <span m=''1408910''>going</span> <span m=''1409010''>to</span>
  <span m=''1409080''>add</span> <span m=''1409350''>in</span> <span m=''1409520''>the</span>
  <span m=''1409630''>scale</span> <span m=''1409950''>factor</span> <span m=''1410580''>which</span>
  <span m=''1410950''>you</span> <span m=''1411010''>can</span> <span m=''1411150''>think</span>
  <span m=''1411360''>of</span> <span m=''1411520''>as</span> <span m=''1413250''>shrinking</span>
  <span m=''1413760''>this</span> <span m=''1414230''>or</span> <span m=''1414410''>expanding</span>
  <span m=''1414860''>that.</span> <span m=''1415110''>It</span> <span m=''1415200''>doesn''t</span>
  <span m=''1415440''>matter.</span> <span m=''1416540''>But</span> <span m=''1416720''>I</span>
  <span m=''1416790''>want</span> <span m=''1417120''>to--</span> <span m=''1418720''>because</span>
  <span m=''1418920''>here</span> <span m=''1420120''>I''m</span> <span m=''1420190''>sort</span>
  <span m=''1420380''>of</span> <span m=''1420440''>shrinking</span> <span m=''1421040''>this</span>
  <span m=''1421280''>amount.</span> </p><p><span m=''1421630''>I</span> <span m=''1421730''>want</span>
  <span m=''1421960''>to</span> <span m=''1422970''>maximize</span> <span m=''1423840''>that</span>
  <span m=''1424080''>factor,</span> <span m=''1424600''>so I shrink it</span> <span
  m=''1425370''>the</span> <span m=''1425470''>least</span> <span m=''1426060''>possible.</span>
  <span m=''1427360''>You</span> <span m=''1427480''>can</span> <span m=''1427660''>formulate</span>
  <span m=''1428120''>it</span> <span m=''1428910''>this</span> <span m=''1429100''>way</span>
  <span m=''1429410''>or</span> <span m=''1429850''>maybe</span> <span m=''1430010''>a</span>
  <span m=''1430350''>more</span> <span m=''1430600''>intuitive</span> <span m=''1430990''>way.</span>
  <span m=''1431560''>But</span> <span m=''1431690''>this</span> <span m=''1431890''>is</span>
  <span m=''1432110''>the</span> <span m=''1433080''>standard</span> <span m=''1433460''>set</span>
  <span m=''1433670''>up.</span> <span m=''1434640''>And</span> <span m=''1434860''>this</span>
  <span m=''1435050''>is</span> <span m=''1435170''>something--</span> <span m=''1435770''>this</span>
  <span m=''1435950''>is</span> <span m=''1436100''>called</span> <span m=''1436380''>a</span>
  <span m=''1436540''>nonlinear</span> <span m=''1437020''>optimization</span> <span
  m=''1437620''>problem.</span> <span m=''1438000''>It''s</span> <span m=''1438120''>something</span>
  <span m=''1438500''>that</span> <span m=''1439080''>lots</span> <span m=''1439300''>of</span>
  <span m=''1439340''>people</span> <span m=''1439600''>think</span> <span m=''1439790''>about.</span>
  <span m=''1441060''>There are</span> <span m=''1441240''>heuristics</span> <span
  m=''1441730''>to</span> <span m=''1441810''>solve</span> <span m=''1442140''>it.</span>
  </p><p><span m=''1442770''>You</span> <span m=''1442870''>can</span> <span m=''1442900''>solve</span>
  <span m=''1443130''>in an</span> <span m=''1443300''>exponential</span> <span m=''1443800''>time.</span>
  <span m=''1444960''>In</span> <span m=''1445040''>general,</span> <span m=''1445400''>it''s
  NP-complete,</span> <span m=''1446140''>and</span> <span m=''1446330''>we''ll</span>
  <span m=''1446440''>see</span> <span m=''1446830''>next</span> <span m=''1446960''>class</span>
  <span m=''1447290''>that</span> <span m=''1447570''>actually</span> <span m=''1447860''>this</span>
  <span m=''1448070''>problem</span> <span m=''1449340''>of</span> <span m=''1449540''>origami</span>
  <span m=''1449770''>design</span> <span m=''1450190''>is</span> <span m=''1450300''>NP-complete.</span>
  <span m=''1451540''>So</span> <span m=''1451720''>there''s</span> <span m=''1452150''>not</span>
  <span m=''1452630''>going</span> <span m=''1452760''>to</span> <span m=''1452830''>be</span>
  <span m=''1453040''>anything</span> <span m=''1453370''>better</span> <span m=''1453660''>than</span>
  <span m=''1454220''>heuristics</span> <span m=''1454850''>and</span> <span m=''1455360''>and</span>
  <span m=''1455580''>slow</span> <span m=''1455830''>algorithms.</span> <span m=''1458730''>So</span>
  <span m=''1459080''>the idea</span> <span m=''1459310''>is,</span> <span m=''1459480''>you</span>
  <span m=''1459570''>solve</span> <span m=''1459870''>that.</span> </p><p><span m=''1460670''>Now,</span>
  <span m=''1461380''>you</span> <span m=''1461560''>have</span> <span m=''1462550''>your</span>
  <span m=''1462700''>leaves</span> <span m=''1463960''>on</span> <span m=''1464090''>your</span>
  <span m=''1464190''>piece</span> <span m=''1464390''>of</span> <span m=''1464460''>paper</span>
  <span m=''1464960''>somewhere.</span> <span m=''1465610''>Now</span> <span m=''1465820''>what?</span>
  <span m=''1467090''>Now,</span> <span m=''1467300''>you</span> <span m=''1467430''>have</span>
  <span m=''1467710''>to</span> <span m=''1468850''>figure</span> <span m=''1469480''>out</span>
  <span m=''1469590''>how</span> <span m=''1469730''>everything</span> <span m=''1470120''>folds.</span>
  <span m=''1471730''>That''s</span> <span m=''1471960''>where</span> <span m=''1472090''>we</span>
  <span m=''1472200''>get</span> <span m=''1472380''>to</span> <span m=''1472480''>some</span>
  <span m=''1472690''>real</span> <span m=''1473580''>combinatorial,</span> <span
  m=''1474430''>some</span> <span m=''1474640''>discrete</span> <span m=''1476090''>geometry.</span>
  <span m=''1477656''>Fun</span> <span m=''1478140''>stuff.</span> <span m=''1485130''>Yeah.</span>
  <span m=''1485270''>I</span> <span m=''1485340''>have</span> <span m=''1485550''>one</span>
  <span m=''1485890''>extra</span> <span m=''1486270''>motivation</span> <span m=''1486920''>here.</span>
  </p><p><span m=''1488750''>Origami</span> <span m=''1489160''>design</span> <span
  m=''1489510''>is</span> <span m=''1489640''>fun, but</span> <span m=''1489960''>here''s</span>
  <span m=''1490200''>a</span> <span m=''1490610''>puzzle</span> <span m=''1490950''>you</span>
  <span m=''1491080''>can solve,</span> <span m=''1491560''>too.</span> <span m=''1496170''>Which</span>
  <span m=''1496410''>we</span> <span m=''1496520''>can</span> <span m=''1496670''>already</span>
  <span m=''1497050''>see.</span> <span m=''1505020''>Margulis</span> <span m=''1505490''>napkin</span>
  <span m=''1505830''>problem.</span> <span m=''1507860''>Origin</span> <span m=''1508360''>of</span>
  <span m=''1508460''>this</span> <span m=''1508500''>problem</span> <span m=''1508730''>is</span>
  <span m=''1508830''>not</span> <span m=''1509260''>entirely</span> <span m=''1509730''>clear,</span>
  <span m=''1509990''>but</span> <span m=''1510130''>I</span> <span m=''1510200''>think</span>
  <span m=''1510380''>it</span> <span m=''1510470''>came</span> <span m=''1510650''>from</span>
  <span m=''1510850''>Russia</span> <span m=''1511190''>originally.</span> <span m=''1513690''>And</span>
  <span m=''1515120''>the</span> <span m=''1515280''>problem,</span> <span m=''1516000''>the</span>
  <span m=''1516120''>puzzle</span> <span m=''1516500''>is</span> <span m=''1516560''>usually</span>
  <span m=''1516860''>stated</span> <span m=''1517260''>as</span> <span m=''1517420''>follows.</span>
  </p><p><span m=''1518060''>Prove</span> <span m=''1518940''>that</span> <span m=''1519060''>if</span>
  <span m=''1519170''>you</span> <span m=''1519280''>take</span> <span m=''1520230''>a
  unit</span> <span m=''1520650''>square</span> <span m=''1520960''>paper--</span>
  <span m=''1521400''>so it</span> <span m=''1521520''>has</span> <span m=''1521730''>perimeter</span>
  <span m=''1522290''>four</span> <span m=''1524130''>that</span> <span m=''1524350''>you</span>
  <span m=''1524510''>can,</span> <span m=''1525400''>no</span> <span m=''1525500''>matter</span>
  <span m=''1525610''>how</span> <span m=''1525860''>you</span> <span m=''1526020''>fold</span>
  <span m=''1526370''>it,</span> <span m=''1527090''>the</span> <span m=''1527200''>perimeter</span>
  <span m=''1527720''>always</span> <span m=''1528020''>gets</span> <span m=''1528250''>smaller.</span>
  <span m=''1529770''>Never</span> <span m=''1530270''>bigger</span> <span m=''1530490''>than</span>
  <span m=''1530670''>four.</span> <span m=''1531740''>We</span> <span m=''1531900''>used</span>
  <span m=''1532040''>a</span> <span m=''1532080''>very</span> <span m=''1532290''>similar</span>
  <span m=''1532690''>thing</span> <span m=''1532890''>here.</span> <span m=''1533100''>We</span>
  <span m=''1533200''>said,</span> <span m=''1533410''>if</span> <span m=''1533510''>you</span>
  <span m=''1533580''>have</span> <span m=''1533720''>two</span> <span m=''1533850''>points,</span>
  <span m=''1534420''>they''re</span> <span m=''1534540''>distance</span> <span m=''1534980''>can
  only</span> <span m=''1535240''>get</span> <span m=''1535400''>smaller.</span> </p><p><span
  m=''1536690''>That''s</span> <span m=''1536970''>true.</span> <span m=''1538230''>Margulis</span>
  <span m=''1538660''>napkin</span> <span m=''1538990''>puzzle</span> <span m=''1539390''>is</span>
  <span m=''1539510''>not</span> <span m=''1539740''>true.</span> <span m=''1541300''>That''s</span>
  <span m=''1541600''>the</span> <span m=''1541820''>difference.</span> <span m=''1542330''>Perimeter</span>
  <span m=''1542760''>is</span> <span m=''1542900''>different</span> <span m=''1543280''>from</span>
  <span m=''1543700''>distance.</span> <span m=''1544610''>And</span> <span m=''1544820''>in</span>
  <span m=''1544860''>fact,</span> <span m=''1545170''>you</span> <span m=''1545250''>can</span>
  <span m=''1545370''>fold</span> <span m=''1545580''>a</span> <span m=''1545620''>piece</span>
  <span m=''1545830''>of</span> <span m=''1545910''>paper</span> <span m=''1546230''>to</span>
  <span m=''1546290''>make</span> <span m=''1546480''>the</span> <span m=''1546560''>perimeter</span>
  <span m=''1547030''>arbitrarily</span> <span m=''1547740''>large,</span> <span m=''1549610''>which</span>
  <span m=''1549860''>is</span> <span m=''1549960''>pretty</span> <span m=''1550190''>crazy.</span>
  <span m=''1550770''>And</span> <span m=''1550920''>this</span> <span m=''1551080''>is</span>
  <span m=''1551170''>something</span> <span m=''1551540''>that</span> <span m=''1551660''>Robert</span>
  <span m=''1551830''>Lang</span> <span m=''1552150''>proved</span> <span m=''1553000''>few</span>
  <span m=''1553190''>years</span> <span m=''1553450''>ago,</span> <span m=''1555030''>using--</span>
  </p><p><span m=''1555720''>It''s</span> <span m=''1555950''>sort</span> <span m=''1556120''>of</span>
  <span m=''1556190''>easy</span> <span m=''1556520''>once</span> <span m=''1556790''>you</span>
  <span m=''1556880''>have</span> <span m=''1557850''>the</span> <span m=''1558000''>fact--</span>
  <span m=''1558490''>which</span> <span m=''1558530''>I</span> <span m=''1558570''>haven''t</span>
  <span m=''1558870''>quite</span> <span m=''1559640''>written</span> <span m=''1559910''>down</span>
  <span m=''1560190''>here,</span> <span m=''1560450''>but</span> <span m=''1560910''>I''ve</span>
  <span m=''1561060''>been</span> <span m=''1561180''>saying.</span> <span m=''1562150''>As</span>
  <span m=''1562260''>long</span> <span m=''1562700''>as</span> <span m=''1562830''>you</span>
  <span m=''1563040''>place</span> <span m=''1563420''>your</span> <span m=''1563540''>points</span>
  <span m=''1563970''>subject</span> <span m=''1564310''>to</span> <span m=''1564390''>this</span>
  <span m=''1564570''>property,</span> <span m=''1565520''>there</span> <span m=''1565770''>is</span>
  <span m=''1565880''>a</span> <span m=''1565930''>folding</span> <span m=''1566800''>that</span>
  <span m=''1566950''>has</span> <span m=''1567450''>that</span> <span m=''1567690''>shadow</span>
  <span m=''1567970''>tree.</span> <span m=''1570890''>And</span> <span m=''1571080''>so</span>
  <span m=''1571410''>the</span> <span m=''1571610''>idea with</span> <span m=''1571760''>the</span>
  <span m=''1571850''>Margulis</span> <span m=''1573040''>napkin</span> <span m=''1573350''>problem</span>
  <span m=''1573620''>is</span> <span m=''1573720''>let''s</span> <span m=''1573950''>make</span>
  <span m=''1574350''>a</span> <span m=''1574430''>really</span> <span m=''1574840''>spiky</span>
  <span m=''1575370''>tree,</span> <span m=''1576720''>a</span> <span m=''1576810''>star.</span>
  </p><p><span m=''1580810''>I</span> <span m=''1580900''>want</span> <span m=''1581050''>to</span>
  <span m=''1581100''>fold</span> <span m=''1581950''>the</span> <span m=''1582040''>smallest</span>
  <span m=''1582400''>square</span> <span m=''1582680''>possible,</span> <span m=''1583720''>so</span>
  <span m=''1583920''>that</span> <span m=''1584200''>projection</span> <span m=''1584690''>is</span>
  <span m=''1584820''>this</span> <span m=''1585030''>thing.</span> <span m=''1585780''>Let''s</span>
  <span m=''1586020''>say</span> <span m=''1587020''>that</span> <span m=''1587170''>it</span>
  <span m=''1587260''>has--</span> <span m=''1589830''>I</span> <span m=''1589980''>won''t</span>
  <span m=''1590190''>say</span> <span m=''1590310''>how</span> <span m=''1590490''>many</span>
  <span m=''1591140''>limbs</span> <span m=''1591330''>it</span> <span m=''1591400''>has.</span>
  <span m=''1591750''>But</span> <span m=''1591870''>the</span> <span m=''1591970''>idea</span>
  <span m=''1592220''>is,</span> <span m=''1592320''>if</span> <span m=''1592420''>you''re</span>
  <span m=''1592630''>using</span> <span m=''1592950''>paper</span> <span m=''1593250''>efficiently,</span>
  <span m=''1594420''>in</span> <span m=''1594550''>fact,</span> <span m=''1595190''>the</span>
  <span m=''1595380''>folding</span> <span m=''1596140''>will</span> <span m=''1596330''>be</span>
  <span m=''1596600''>very</span> <span m=''1597150''>narrow.</span> <span m=''1597600''>It''ll</span>
  <span m=''1597740''>be a</span> <span m=''1597930''>pretty</span> <span m=''1598240''>efficient</span>
  <span m=''1598630''>use</span> <span m=''1598840''>of</span> <span m=''1598930''>paper,</span>
  <span m=''1599970''>hopefully.</span> </p><p><span m=''1601060''>And</span> <span
  m=''1601230''>so</span> <span m=''1602130''>the</span> <span m=''1602270''>actual</span>
  <span m=''1602700''>3D</span> <span m=''1603020''>state</span> <span m=''1603340''>will</span>
  <span m=''1603440''>just</span> <span m=''1603640''>be</span> <span m=''1603770''>a</span>
  <span m=''1603810''>little</span> <span m=''1604070''>bit</span> <span m=''1604820''>taller</span>
  <span m=''1605550''>than</span> <span m=''1605740''>that</span> <span m=''1605990''>tree.</span>
  <span m=''1606960''>And</span> <span m=''1607160''>then,</span> <span m=''1607260''>you</span>
  <span m=''1607340''>just</span> <span m=''1607580''>wash</span> <span m=''1607900''>it.</span>
  <span m=''1608510''>And</span> <span m=''1608830''>the idea</span> <span m=''1608980''>is
  that</span> <span m=''1609230''>then</span> <span m=''1609390''>the</span> <span
  m=''1609480''>perimeter</span> <span m=''1609800''>is</span> <span m=''1609860''>really</span>
  <span m=''1610090''>big.</span> <span m=''1610330''>You''ve</span> <span m=''1610440''>got</span>
  <span m=''1610620''>a--</span> <span m=''1610760''>the</span> <span m=''1611010''>perimeter</span>
  <span m=''1611370''>as</span> <span m=''1611460''>you</span> <span m=''1611590''>walk</span>
  <span m=''1611820''>around</span> <span m=''1612170''>the</span> <span m=''1612290''>edges</span>
  <span m=''1612590''>of</span> <span m=''1612650''>that</span> <span m=''1612820''>tree.</span>
  <span m=''1613370''>So</span> <span m=''1613520''>how</span> <span m=''1613870''>big
  a</span> <span m=''1614155''>tree</span> <span m=''1614440''>can</span> <span m=''1614610''>I</span>
  <span m=''1614670''>get?</span> <span m=''1616760''>I''d</span> <span m=''1616910''>like</span>
  <span m=''1617090''>to</span> <span m=''1617190''>somehow</span> <span m=''1617540''>place</span>
  <span m=''1617890''>these</span> <span m=''1618090''>leaves--</span> <span m=''1619130''>now,</span>
  <span m=''1619330''>what''s</span> <span m=''1619550''>the</span> <span m=''1619640''>constraint</span>
  <span m=''1621160''>on</span> <span m=''1621300''>the</span> <span m=''1621370''>leaves?</span>
  </p><p><span m=''1621640''>Let''s</span> <span m=''1621820''>say</span> <span m=''1622000''>all</span>
  <span m=''1622180''>of</span> <span m=''1622260''>these</span> <span m=''1622540''>are</span>
  <span m=''1622780''>length</span> <span m=''1623040''>one.</span> <span m=''1624480''>Then,</span>
  <span m=''1624750''>this</span> <span m=''1624980''>says</span> <span m=''1625230''>it</span>
  <span m=''1625360''>every</span> <span m=''1625620''>pair</span> <span m=''1625840''>of</span>
  <span m=''1625910''>leaves</span> <span m=''1626700''>must</span> <span m=''1626900''>be</span>
  <span m=''1627150''>at</span> <span m=''1627220''>least</span> <span m=''1627450''>distance</span>
  <span m=''1627850''>two</span> <span m=''1628110''>way</span> <span m=''1628270''>from</span>
  <span m=''1628450''>each</span> <span m=''1628610''>other.</span> <span m=''1630150''>So</span>
  <span m=''1630260''>I</span> <span m=''1630310''>got</span> <span m=''1630430''>to</span>
  <span m=''1630490''>place</span> <span m=''1630780''>these</span> <span m=''1631330''>dots</span>
  <span m=''1631710''>in</span> <span m=''1631860''>the</span> <span m=''1631930''>square</span>
  <span m=''1632900''>so</span> <span m=''1633040''>that</span> <span m=''1633170''>every</span>
  <span m=''1633430''>pair</span> <span m=''1633670''>has</span> <span m=''1633840''>distance</span>
  <span m=''1634200''>at</span> <span m=''1634270''>least</span> <span m=''1634520''>two.</span>
  <span m=''1635100''>This</span> <span m=''1635290''>is</span> <span m=''1635430''>like</span>
  <span m=''1635690''>saying--</span> <span m=''1636590''>here''s</span> <span m=''1636800''>my</span>
  <span m=''1636960''>square.</span> <span m=''1638350''>--I''d</span> <span m=''1638580''>like</span>
  <span m=''1638910''>to</span> <span m=''1639050''>place</span> <span m=''1639640''>dots</span>
  <span m=''1641470''>so</span> <span m=''1641630''>their</span> <span m=''1641890''>distance</span>
  <span m=''1642340''>is</span> <span m=''1642480''>at</span> <span m=''1642540''>least</span>
  <span m=''1642810''>distance</span> <span m=''1643080''>two.</span> </p><p><span
  m=''1643300''>That''s</span> <span m=''1643510''>like</span> <span m=''1643640''>saying</span>
  <span m=''1643850''>if,</span> <span m=''1643950''>I</span> <span m=''1644030''>drew</span>
  <span m=''1644380''>a</span> <span m=''1644460''>unit</span> <span m=''1645150''>disk</span>
  <span m=''1646290''>around</span> <span m=''1647480''>two</span> <span m=''1647750''>points--</span>
  <span m=''1649190''>I</span> <span m=''1649430''>got</span> <span m=''1649570''>to</span>
  <span m=''1649620''>remember.</span> <span m=''1649910''>You should</span> <span
  m=''1650130''>always</span> <span m=''1650200''>draw</span> <span m=''1650370''>the</span>
  <span m=''1650470''>disk</span> <span m=''1650740''>first</span> <span m=''1651200''>and</span>
  <span m=''1651350''>then</span> <span m=''1651480''>the</span> <span m=''1651570''>center.</span>
  <span m=''1652530''>Much</span> <span m=''1652760''>easier.</span> <span m=''1653900''>Those</span>
  <span m=''1654410''>disks</span> <span m=''1654900''>should</span> <span m=''1655120''>not</span>
  <span m=''1655320''>be</span> <span m=''1655450''>overlapping.</span> <span m=''1656460''>If</span>
  <span m=''1656560''>this</span> <span m=''1656770''>is</span> <span m=''1657390''>length</span>
  <span m=''1657660''>one,</span> <span m=''1658460''>and</span> <span m=''1658700''>this</span>
  <span m=''1658890''>is</span> <span m=''1659350''>length</span> <span m=''1659690''>one,</span>
  <span m=''1661750''>the</span> <span m=''1662030''>disks</span> <span m=''1662330''>will</span>
  <span m=''1662470''>be</span> <span m=''1662610''>overlapping</span> <span m=''1663170''>if</span>
  <span m=''1663300''>and</span> <span m=''1663390''>only</span> <span m=''1663650''>if</span>
  <span m=''1664355''>this</span> <span m=''1664740''>distance</span> <span m=''1665110''>is</span>
  <span m=''1665210''>smaller</span> <span m=''1665620''>than</span> <span m=''1665780''>two.</span>
  </p><p><span m=''1666140''>I</span> <span m=''1666290''>want</span> <span m=''1666500''>it
  always</span> <span m=''1666750''>to</span> <span m=''1666820''>be</span> <span
  m=''1666920''>greater than</span> <span m=''1667190''>or</span> <span m=''1667250''>equal</span>
  <span m=''1667490''>to</span> <span m=''1667590''>two.</span> <span m=''1668420''>So</span>
  <span m=''1668580''>I</span> <span m=''1668650''>just</span> <span m=''1668850''>have</span>
  <span m=''1668970''>to</span> <span m=''1669060''>place</span> <span m=''1669400''>a</span>
  <span m=''1669450''>whole</span> <span m=''1669650''>bunch</span> <span m=''1669890''>of</span>
  <span m=''1669960''>disks</span> <span m=''1670780''>in</span> <span m=''1670920''>the</span>
  <span m=''1670990''>square</span> <span m=''1672710''>so</span> <span m=''1672910''>that</span>
  <span m=''1673070''>they''re</span> <span m=''1673180''>not</span> <span m=''1673350''>overlapping.</span>
  <span m=''1674010''>So</span> <span m=''1674150''>how</span> <span m=''1674400''>big</span>
  <span m=''1674590''>a</span> <span m=''1674650''>square</span> <span m=''1674940''>do</span>
  <span m=''1675040''>I</span> <span m=''1675120''>need</span> <span m=''1675340''>to</span>
  <span m=''1675430''>do</span> <span m=''1675570''>that?</span> <span m=''1677690''>This</span>
  <span m=''1677880''>is</span> <span m=''1677990''>a</span> <span m=''1678060''>well-studied</span>
  <span m=''1678540''>problem,</span> <span m=''1678870''>is</span> <span m=''1679110''>the</span>
  <span m=''1679240''>disk</span> <span m=''1679460''>packing</span> <span m=''1679780''>problem.</span>
  <span m=''1680850''>A</span> <span m=''1680910''>lot</span> <span m=''1681170''>of</span>
  <span m=''1681260''>results</span> <span m=''1681620''>known</span> <span m=''1681790''>about</span>
  <span m=''1682090''>it.</span> <span m=''1682670''>It''s</span> <span m=''1682830''>quite</span>
  <span m=''1683050''>difficult.</span> </p><p><span m=''1684450''>But</span> <span
  m=''1684630''>we</span> <span m=''1684730''>don''t</span> <span m=''1684840''>need</span>
  <span m=''1685000''>to</span> <span m=''1685070''>be</span> <span m=''1685290''>super</span>
  <span m=''1685640''>smart</span> <span m=''1685950''>here</span> <span m=''1686350''>to</span>
  <span m=''1686450''>get</span> <span m=''1686670''>a</span> <span m=''1686740''>good</span>
  <span m=''1686920''>bound.</span> <span m=''1687910''>Let''s</span> <span m=''1688190''>put</span>
  <span m=''1688340''>a</span> <span m=''1688400''>point--</span> <span m=''1689130''>let''s</span>
  <span m=''1689340''>put</span> <span m=''1689510''>points</span> <span m=''1690130''>along</span>
  <span m=''1690670''>a</span> <span m=''1690770''>grid.</span> <span m=''1692830''>I''m</span>
  <span m=''1692990''>going</span> <span m=''1693120''>to</span> <span m=''1693190''>regret</span>
  <span m=''1693550''>making</span> <span m=''1693850''>such</span> <span m=''1694090''>a</span>
  <span m=''1694140''>big</span> <span m=''1694340''>grid.</span> <span m=''1698960''>Let''s</span>
  <span m=''1699240''>say,</span> <span m=''1700710''>an</span> <span m=''1700820''>n</span>
  <span m=''1701000''>by</span> <span m=''1701160''>n</span> <span m=''1701370''>grid.</span>
  </p><p><span m=''1707380''>And</span> <span m=''1707540''>I''m</span> <span m=''1707620''>going</span>
  <span m=''1707730''>to</span> <span m=''1708570''>set</span> <span m=''1709000''>the</span>
  <span m=''1709520''>size</span> <span m=''1709870''>of</span> <span m=''1709930''>my</span>
  <span m=''1710070''>disks</span> <span m=''1710545''>right</span> <span m=''1711020''>so
  that</span> <span m=''1711190''>these</span> <span m=''1711480''>guys</span> <span
  m=''1712400''>just</span> <span m=''1712630''>barely</span> <span m=''1713000''>touch.</span>
  <span m=''1718290''>This</span> <span m=''1718500''>is</span> <span m=''1718620''>actually</span>
  <span m=''1718910''>not</span> <span m=''1719230''>a</span> <span m=''1719330''>terribly</span>
  <span m=''1719680''>good</span> <span m=''1719890''>packing.</span> <span m=''1720870''>You</span>
  <span m=''1720960''>should</span> <span m=''1721150''>do a</span> <span m=''1721440''>triangular</span>
  <span m=''1721940''>grid</span> <span m=''1722120''>instead</span> <span m=''1722390''>of</span>
  <span m=''1722480''>a</span> <span m=''1722540''>square</span> <span m=''1722830''>grid.</span>
  <span m=''1723810''>But</span> <span m=''1724810''>it''ll</span> <span m=''1725010''>be</span>
  <span m=''1725270''>good</span> <span m=''1725460''>enough</span> <span m=''1725730''>asymptotically.</span>
  <span m=''1727610''>You</span> <span m=''1727660''>get</span> <span m=''1727790''>the</span>
  <span m=''1727900''>idea.</span> </p><p><span m=''1729070''>If</span> <span m=''1729200''>I</span>
  <span m=''1729270''>set</span> <span m=''1729580''>the</span> <span m=''1729700''>size</span>
  <span m=''1730070''>of</span> <span m=''1730150''>my</span> <span m=''1730310''>paper</span>
  <span m=''1731060''>to</span> <span m=''1731310''>be</span> <span m=''1731530''>n</span>
  <span m=''1731710''>by</span> <span m=''1731860''>n,</span> <span m=''1732840''>I</span>
  <span m=''1732980''>can</span> <span m=''1733160''>fit</span> <span m=''1734140''>about</span>
  <span m=''1734560''>n</span> <span m=''1734740''>squared</span> <span m=''1735420''>unit</span>
  <span m=''1735750''>disks</span> <span m=''1736010''>in</span> <span m=''1736120''>there.</span>
  <span m=''1738030''>N</span> <span m=''1738260''>by</span> <span m=''1738410''>n</span>
  <span m=''1738620''>paper</span> <span m=''1740850''>folds</span> <span m=''1742810''>something</span>
  <span m=''1743240''>like</span> <span m=''1744250''>n</span> <span m=''1744410''>plus</span>
  <span m=''1744650''>1</span> <span m=''1744880''>squared.</span> <span m=''1745340''>But</span>
  <span m=''1745500''>let''s</span> <span m=''1745710''>just</span> <span m=''1745830''>say,</span>
  <span m=''1746060''>approximately</span> <span m=''1747300''>n</span> <span m=''1747520''>squared</span>
  <span m=''1748870''>disks.</span> <span m=''1750320''>So</span> <span m=''1750500''>that</span>
  <span m=''1750700''>means</span> <span m=''1751260''>I</span> <span m=''1751440''>can</span>
  <span m=''1752760''>make</span> <span m=''1752990''>a</span> <span m=''1753050''>star</span>
  <span m=''1753500''>with</span> <span m=''1753650''>about</span> <span m=''1753970''>n</span>
  <span m=''1754210''>squared</span> <span m=''1754830''>limbs.</span> <span m=''1756170''>It''s</span>
  <span m=''1756250''>insane.</span> <span m=''1757990''>It''s</span> <span m=''1758100''>like</span>
  <span m=''1758310''>super</span> <span m=''1758620''>efficient.</span> </p><p><span
  m=''1759400''>Each</span> <span m=''1759670''>of</span> <span m=''1759780''>these</span>
  <span m=''1759980''>little</span> <span m=''1760210''>portions</span> <span m=''1760650''>of</span>
  <span m=''1760750''>paper</span> <span m=''1761100''>ends</span> <span m=''1761300''>up</span>
  <span m=''1761410''>being</span> <span m=''1761600''>one</span> <span m=''1761770''>of</span>
  <span m=''1761840''>these</span> <span m=''1761980''>segments.</span> <span m=''1762470''>That''s</span>
  <span m=''1762670''>the</span> <span m=''1762760''>claim is,</span> <span m=''1763120''>you</span>
  <span m=''1763250''>could</span> <span m=''1763390''>fold</span> <span m=''1763640''>that.</span>
  <span m=''1764620''>So</span> <span m=''1764680''>once</span> <span m=''1764830''>you</span>
  <span m=''1764930''>fold</span> <span m=''1765200''>this</span> <span m=''1765380''>thing,</span>
  <span m=''1765870''>I</span> <span m=''1766300''>have</span> <span m=''1766390''>an</span>
  <span m=''1766490''>n</span> <span m=''1766660''>by</span> <span m=''1766830''>n</span>
  <span m=''1766980''>square.</span> <span m=''1767230''>You</span> <span m=''1767310''>started</span>
  <span m=''1767680''>with</span> <span m=''1767840''>perimeter</span> <span m=''1768230''>about</span>
  <span m=''1768480''>four</span> <span m=''1768810''>n</span> <span m=''1770100''>And</span>
  <span m=''1770280''>now,</span> <span m=''1771070''>I</span> <span m=''1771150''>have</span>
  <span m=''1771310''>perimeter</span> <span m=''1771670''>about</span> <span m=''1771870''>n</span>
  <span m=''1772060''>squared.</span> <span m=''1773200''>That''s</span> <span m=''1773440''>huge</span>
  <span m=''1773840''>with</span> <span m=''1774000''>respect</span> <span m=''1774350''>to</span>
  <span m=''1774420''>four n.</span> </p><p><span m=''1775480''>So</span> <span m=''1775670''>this</span>
  <span m=''1776640''>is</span> <span m=''1777000''>much</span> <span m=''1777370''>bigger</span>
  <span m=''1778320''>than</span> <span m=''1778530''>four</span> <span m=''1778870''>n,</span>
  <span m=''1779150''>for</span> <span m=''1779320''>n</span> <span m=''1779530''>sufficiently</span>
  <span m=''1779980''>large.</span> </p><p><span m=''1782316''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''1782780''>about the</span> <span m=''1783244''>length</span> <span m=''1783708''>flaps.</span>
  </p><p><span m=''1785250''>PROFESSOR: Here, I</span> <span m=''1785540''>was</span>
  <span m=''1785640''>assuming</span> <span m=''1785950''>all</span> <span m=''1786060''>the</span>
  <span m=''1786140''>flaps</span> <span m=''1786450''>are</span> <span m=''1786540''>length</span>
  <span m=''1786760''>one.</span> <span m=''1787300''>So</span> <span m=''1787520''>the</span>
  <span m=''1787630''>disks</span> <span m=''1787930''>are</span> <span m=''1788470''>size</span>
  <span m=''1788790''>one,</span> <span m=''1789250''>and</span> <span m=''1789390''>so</span>
  <span m=''1789600''>it''s</span> <span m=''1789730''>an</span> <span m=''1789820''>n</span>
  <span m=''1789980''>by</span> <span m=''1790130''>n</span> <span m=''1790280''>square.</span>
  <span m=''1794544''>Clear?</span> <span m=''1795040''>So</span> <span m=''1795240''>this</span>
  <span m=''1795460''>is</span> <span m=''1795690''>more</span> <span m=''1795930''>motivation</span>
  <span m=''1796510''>for</span> <span m=''1796670''>why</span> <span m=''1796990''>this</span>
  <span m=''1797300''>theorem</span> <span m=''1797570''>is</span> <span m=''1797670''>interesting.</span>
  <span m=''1798210''>It</span> <span m=''1798280''>lets</span> <span m=''1798470''>you</span>
  <span m=''1798560''>solve</span> <span m=''1798870''>this</span> <span m=''1799080''>fun</span>
  <span m=''1799270''>math</span> <span m=''1799540''>puzzle</span> <span m=''1801280''>and</span>
  <span m=''1801590''>show</span> <span m=''1802730''>not</span> <span m=''1802960''>only</span>
  <span m=''1803140''>does</span> <span m=''1803260''>a</span> <span m=''1803330''>perimeter</span>
  <span m=''1803700''>not</span> <span m=''1804580''>go--</span> <span m=''1805680''>not</span>
  <span m=''1805850''>only</span> <span m=''1806020''>does</span> <span m=''1806160''>the</span>
  <span m=''1806240''>perimeter</span> <span m=''1806570''>not</span> <span m=''1807000''>only</span>
  <span m=''1807270''>go</span> <span m=''1807420''>down,</span> <span m=''1808716''>but</span>
  <span m=''1809150''>it</span> <span m=''1809280''>can</span> <span m=''1809460''>go</span>
  <span m=''1809620''>arbitrarily</span> <span m=''1810210''>high.</span> </p><p><span
  m=''1811520''>It just</span> <span m=''1811720''>takes</span> <span m=''1811900''>a</span>
  <span m=''1811950''>lot</span> <span m=''1812120''>of</span> <span m=''1812200''>folding.</span>
  <span m=''1816370''>So</span> <span m=''1816760''>let''s</span> <span m=''1819150''>say</span>
  <span m=''1819330''>something</span> <span m=''1819640''>about</span> <span m=''1819840''>how</span>
  <span m=''1820210''>we</span> <span m=''1820440''>prove</span> <span m=''1820880''>that</span>
  <span m=''1820930''>once</span> <span m=''1821160''>you</span> <span m=''1821240''>have</span>
  <span m=''1821610''>a</span> <span m=''1821660''>valid</span> <span m=''1822060''>placement</span>
  <span m=''1822280''>of</span> <span m=''1822390''>the</span> <span m=''1822490''>points,</span>
  <span m=''1822820''>you</span> <span m=''1822920''>can</span> <span m=''1823050''>actually</span>
  <span m=''1823320''>fill</span> <span m=''1823560''>in</span> <span m=''1823610''>the</span>
  <span m=''1823710''>creases,</span> <span m=''1824620''>find</span> <span m=''1826130''>folding.</span>
  <span m=''1841970''>Let</span> <span m=''1842090''>me</span> <span m=''1842300''>bring</span>
  <span m=''1842470''>up</span> <span m=''1842600''>an</span> <span m=''1842690''>example.</span>
  <span m=''1847030''>So</span> <span m=''1847130''>this</span> <span m=''1847350''>is</span>
  <span m=''1847480''>actually</span> <span m=''1847760''>the</span> <span m=''1847840''>example</span>
  <span m=''1848270''>I</span> <span m=''1848340''>keep</span> <span m=''1848590''>using</span>
  <span m=''1849140''>which</span> <span m=''1849330''>is,</span> <span m=''1850200''>you</span>
  <span m=''1850300''>want</span> <span m=''1850430''>to</span> <span m=''1850470''>make</span>
  <span m=''1850640''>a</span> <span m=''1850690''>lizard</span> <span m=''1851110''>or</span>
  <span m=''1851210''>some</span> <span m=''1851400''>generic</span> <span m=''1853540''>four-legged</span>
  <span m=''1854570''>tail</span> <span m=''1854980''>and</span> <span m=''1855100''>head</span>
  <span m=''1856450''>kind</span> <span m=''1856730''>of</span> <span m=''1856790''>creature.</span>
  </p><p><span m=''1858090''>This</span> <span m=''1858280''>is</span> <span m=''1858400''>the</span>
  <span m=''1858690''>output</span> <span m=''1859150''>from</span> <span m=''1859350''>TreeMaker,</span>
  <span m=''1860900''>complete</span> <span m=''1861200''>with</span> <span m=''1861350''>crease</span>
  <span m=''1861570''>pattern and</span> <span m=''1861950''>everything.</span> <span
  m=''1862810''>But</span> <span m=''1862860''>here,</span> <span m=''1863030''>I''ve</span>
  <span m=''1863120''>labeled</span> <span m=''1863680''>all</span> <span m=''1863990''>the--</span>
  <span m=''1864670''>or</span> <span m=''1864840''>actually</span> <span m=''1865080''>Robert</span>
  <span m=''1865410''>Lang,</span> <span m=''1865790''>I</span> <span m=''1865870''>think,</span>
  <span m=''1866120''>has</span> <span m=''1866340''>labeled</span> <span m=''1866830''>all</span>
  <span m=''1867310''>of--</span> <span m=''1867450''>this</span> <span m=''1867610''>a</span>
  <span m=''1867680''>figure</span> <span m=''1867920''>from</span> <span m=''1868080''>our</span>
  <span m=''1868170''>book.</span> <span m=''1868920''>--all</span> <span m=''1869190''>the</span>
  <span m=''1869590''>vertices</span> <span m=''1870380''>of</span> <span m=''1870640''>the</span>
  <span m=''1870740''>tree</span> <span m=''1872240''>and</span> <span m=''1872310''>the</span>
  <span m=''1872390''>shadow.</span> <span m=''1873270''>And</span> <span m=''1873440''>then,</span>
  <span m=''1873640''>we''re</span> <span m=''1873950''>labeling</span> <span m=''1874520''>where</span>
  <span m=''1875350''>they</span> <span m=''1875480''>come</span> <span m=''1875750''>from</span>
  <span m=''1876020''>on</span> <span m=''1876120''>the</span> <span m=''1876200''>piece</span>
  <span m=''1876410''>of</span> <span m=''1876490''>paper.</span> </p><p><span m=''1879750''>So</span>
  <span m=''1880080''>in</span> <span m=''1880180''>particular,</span> <span m=''1880740''>you</span>
  <span m=''1880790''>see</span> <span m=''1881030''>something</span> <span m=''1881360''>like</span>
  <span m=''1881530''>a</span> <span m=''1881590''>leaf</span> <span m=''1881870''>h.</span>
  <span m=''1882730''>And</span> <span m=''1882920''>it</span> <span m=''1883010''>comes</span>
  <span m=''1883290''>from</span> <span m=''1883470''>this</span> <span m=''1883660''>one</span>
  <span m=''1884670''>point</span> <span m=''1884980''>on</span> <span m=''1885140''>the</span>
  <span m=''1885220''>paper.</span> <span m=''1886410''>This</span> <span m=''1886800''>leaf</span>
  <span m=''1887170''>d</span> <span m=''1888380''>comes from</span> <span m=''1888520''>this</span>
  <span m=''1888730''>point,</span> <span m=''1889380''>and</span> <span m=''1889740''>g</span>
  <span m=''1890190''>comes</span> <span m=''1890470''>from</span> <span m=''1890570''>that</span>
  <span m=''1890790''>point.</span> <span m=''1891030''>It''s</span> <span m=''1891140''>actually</span>
  <span m=''1891450''>kind</span> <span m=''1891660''>of</span> <span m=''1891730''>similarly</span>
  <span m=''1892300''>oriented</span> <span m=''1892920''>to</span> <span m=''1893370''>this</span>
  <span m=''1893570''>guy.</span> <span m=''1893710''>The</span> <span m=''1893830''>interior</span>
  <span m=''1894860''>vertices,</span> <span m=''1895430''>they</span> <span m=''1895520''>come
  from</span> <span m=''1895910''>several</span> <span m=''1896250''>points.</span>
  <span m=''1896730''>It''s</span> <span m=''1896890''>a</span> <span m=''1896930''>little</span>
  <span m=''1897090''>messy.</span> </p><p><span m=''1898440''>But</span> <span m=''1898680''>let''s--</span>
  <span m=''1899390''>one</span> <span m=''1899650''>of</span> <span m=''1899730''>the</span>
  <span m=''1899810''>things</span> <span m=''1900120''>is</span> <span m=''1900250''>to</span>
  <span m=''1900350''>try</span> <span m=''1900550''>to</span> <span m=''1900650''>locate</span>
  <span m=''1901000''>where</span> <span m=''1901100''>those</span> <span m=''1901310''>points</span>
  <span m=''1901730''>ought to</span> <span m=''1901800''>be.</span> <span m=''1903146''>s</span>
  <span m=''1904940''>So</span> <span m=''1905240''>there''s</span> <span m=''1905420''>this</span>
  <span m=''1905580''>idea</span> <span m=''1905950''>of</span> <span m=''1906100''>an</span>
  <span m=''1906180''>active</span> <span m=''1906500''>path</span> <span m=''1908550''>which</span>
  <span m=''1908810''>is</span> <span m=''1910130''>a</span> <span m=''1910520''>path</span>
  <span m=''1910880''>in</span> <span m=''1911060''>the</span> <span m=''1911150''>tree</span>
  <span m=''1912810''>between</span> <span m=''1913320''>two</span> <span m=''1914350''>leaves.</span>
  <span m=''1915720''>I''ll</span> <span m=''1915880''>call</span> <span m=''1916070''>them</span>
  <span m=''1916220''>shadow</span> <span m=''1916630''>leaves</span> <span m=''1917110''>to</span>
  <span m=''1917220''>say</span> <span m=''1917570''>that they''re</span> <span m=''1917720''>in</span>
  <span m=''1917780''>the</span> <span m=''1917850''>shadow</span> <span m=''1918170''>tree.</span>
  </p><p><span m=''1923650''>And</span> <span m=''1924980''>the</span> <span m=''1925130''>length</span>
  <span m=''1925470''>of</span> <span m=''1925580''>that</span> <span m=''1925800''>path</span>
  <span m=''1928830''>equals</span> <span m=''1932850''>the</span> <span m=''1934150''>distance</span>
  <span m=''1938490''>in</span> <span m=''1938790''>the</span> <span m=''1938910''>paper.</span>
  <span m=''1942120''>So</span> <span m=''1942310''>in</span> <span m=''1942400''>the</span>
  <span m=''1942540''>case</span> <span m=''1943130''>of</span> <span m=''1943910''>making</span>
  <span m=''1944280''>a</span> <span m=''1944350''>star</span> <span m=''1944710''>graph,</span>
  <span m=''1945020''>this</span> <span m=''1945210''>is</span> <span m=''1945310''>exactly</span>
  <span m=''1945770''>when</span> <span m=''1946160''>the</span> <span m=''1946360''>disks</span>
  <span m=''1947340''>kiss,</span> <span m=''1948140''>when</span> <span m=''1948240''>the</span>
  <span m=''1948340''>just</span> <span m=''1948590''>touch</span> <span m=''1948820''>each</span>
  <span m=''1948970''>other</span> <span m=''1949170''>on</span> <span m=''1949250''>the</span>
  <span m=''1949320''>boundary.</span> <span m=''1952130''>So</span> <span m=''1954000''>in</span>
  <span m=''1954080''>other</span> <span m=''1954220''>words,</span> <span m=''1954450''>we</span>
  <span m=''1954470''>have</span> <span m=''1954670''>this</span> <span m=''1954840''>inequality,</span>
  <span m=''1955860''>saying</span> <span m=''1956130''>the</span> <span m=''1956230''>distance</span>
  <span m=''1956710''>between</span> <span m=''1957280''>in</span> <span m=''1957440''>the</span>
  <span m=''1957530''>paper</span> <span m=''1957960''>should</span> <span m=''1958110''>be</span>
  <span m=''1958200''>greater</span> <span m=''1958360''>than</span> <span m=''1958460''>or</span>
  <span m=''1958510''>equal</span> <span m=''1958730''>to</span> <span m=''1958830''>distance</span>
  <span m=''1959590''>in</span> <span m=''1959720''>the</span> <span m=''1959800''>tree.</span>
  </p><p><span m=''1960630''>If</span> <span m=''1960800''>that</span> <span m=''1961050''>inequality</span>
  <span m=''1961650''>is</span> <span m=''1961760''>actually</span> <span m=''1962310''>an</span>
  <span m=''1962470''>equality,</span> <span m=''1963090''>if</span> <span m=''1963220''>they''re</span>
  <span m=''1963340''>the</span> <span m=''1963490''>same</span> <span m=''1963870''>thing,</span>
  <span m=''1964940''>then</span> <span m=''1965610''>it''s</span> <span m=''1965810''>kind</span>
  <span m=''1965990''>of</span> <span m=''1966170''>critical.</span> <span m=''1966640''>I</span>
  <span m=''1966720''>can''t</span> <span m=''1967760''>get</span> <span m=''1967960''>those</span>
  <span m=''1968140''>points</span> <span m=''1968410''>any</span> <span m=''1968620''>closer</span>
  <span m=''1969020''>in</span> <span m=''1969090''>the</span> <span m=''1969180''>paper.</span>
  <span m=''1970730''>Those</span> <span m=''1971010''>things</span> <span m=''1971290''>I</span>
  <span m=''1971370''>call</span> <span m=''1971620''>active</span> <span m=''1971920''>paths.</span>
  <span m=''1972970''>And</span> <span m=''1973180''>that</span> <span m=''1973540''>is</span>
  <span m=''1975340''>some</span> <span m=''1975640''>of</span> <span m=''1975710''>the</span>
  <span m=''1975810''>lines</span> <span m=''1976160''>up</span> <span m=''1976330''>here.</span>
  <span m=''1977440''>I</span> <span m=''1977530''>guess</span> <span m=''1977860''>the</span>
  <span m=''1978870''>black</span> <span m=''1979970''>dashed</span> <span m=''1980450''>line,</span>
  <span m=''1981170''>actually,</span> <span m=''1981510''>in</span> <span m=''1981630''>a</span>
  <span m=''1981710''>lot</span> <span m=''1981930''>of</span> <span m=''1982000''>the</span>
  <span m=''1982100''>dash</span> <span m=''1982400''>lines.</span> <span m=''1983880''>All</span>
  <span m=''1984160''>of</span> <span m=''1984250''>the</span> <span m=''1984350''>dash</span>
  <span m=''1984680''>lines,</span> <span m=''1985160''>I</span> <span m=''1985220''>think.</span>
  </p><p><span m=''1986360''>So</span> <span m=''1986520''>for</span> <span m=''1986700''>example,</span>
  <span m=''1987650''>d</span> <span m=''1988030''>to</span> <span m=''1988410''>h,</span>
  <span m=''1990160''>that''s</span> <span m=''1990390''>a</span> <span m=''1990470''>distance</span>
  <span m=''1990900''>between</span> <span m=''1991250''>two</span> <span m=''1991660''>leaves.</span>
  <span m=''1992650''>And</span> <span m=''1992930''>if</span> <span m=''1993020''>you</span>
  <span m=''1993120''>measure</span> <span m=''1993370''>the</span> <span m=''1993470''>distance</span>
  <span m=''1993780''>here,</span> <span m=''1993940''>it''s</span> <span m=''1994355''>two.</span>
  <span m=''1994770''>And</span> <span m=''1995230''>just</span> <span m=''1995480''>imagine,</span>
  <span m=''1996390''>this</span> <span m=''1996830''>example</span> <span m=''1997340''>has
  been</span> <span m=''1997480''>set</span> <span m=''1997660''>up</span> <span m=''1997820''>so</span>
  <span m=''1997980''>this</span> <span m=''1998220''>is</span> <span m=''1998340''>exactly</span>
  <span m=''1998880''>two.</span> <span m=''1999130''>So</span> <span m=''1999300''>this</span>
  <span m=''1999480''>is</span> <span m=''1999590''>tight.</span> <span m=''1999910''>I</span>
  <span m=''1999960''>can''t</span> <span m=''2000270''>move h</span> <span m=''2000670''>any</span>
  <span m=''2000840''>closer</span> <span m=''2001170''>to d</span> <span m=''2001270''>or</span>
  <span m=''2001540''>vice</span> <span m=''2001800''>versa.</span> <span m=''2002950''>And</span>
  <span m=''2003170''>also</span> <span m=''2003710''>from</span> <span m=''2004840''>h</span>
  <span m=''2005120''>to</span> <span m=''2005300''>a,</span> <span m=''2005625''>a
  is</span> <span m=''2005950''>actually</span> <span m=''2006210''>in</span> <span
  m=''2006280''>the</span> <span m=''2006360''>middle</span> <span m=''2006630''>of</span>
  <span m=''2006710''>the</span> <span m=''2006800''>paper</span> <span m=''2007620''>and</span>
  <span m=''2007780''>corresponds</span> <span m=''2008320''>to</span> <span m=''2008440''>that</span>
  <span m=''2009020''>flap.</span> </p><p><span m=''2010180''>That''s</span> <span
  m=''2010500''>all</span> <span m=''2011020''>of</span> <span m=''2011120''>those</span>
  <span m=''2012780''>green,</span> <span m=''2013260''>actually</span> <span m=''2013540''>it''s
  just</span> <span m=''2013780''>the</span> <span m=''2013870''>green</span> <span
  m=''2014110''>lines,</span> <span m=''2014390''>green</span> <span m=''2014790''>dashed</span>
  <span m=''2015100''>lines</span> <span m=''2015930''>are</span> <span m=''2016310''>active.</span>
  <span m=''2017190''>They''re</span> <span m=''2017380''>kind</span> <span m=''2017560''>of</span>
  <span m=''2017650''>critical.</span> <span m=''2018960''>And</span> <span m=''2019160''>what''s</span>
  <span m=''2019340''>nice</span> <span m=''2019650''>is</span> <span m=''2019740''>that</span>
  <span m=''2019980''>subdivides</span> <span m=''2020580''>my</span> <span m=''2020720''>piece</span>
  <span m=''2020950''>of</span> <span m=''2021030''>paper</span> <span m=''2021480''>into</span>
  <span m=''2022090''>a</span> <span m=''2022110''>bunch</span> <span m=''2022370''>of</span>
  <span m=''2022440''>smaller</span> <span m=''2022790''>shapes.</span> <span m=''2023800''>So</span>
  <span m=''2023940''>I</span> <span m=''2024010''>have</span> <span m=''2024740''>a</span>
  <span m=''2024800''>little</span> <span m=''2025010''>triangle</span> <span m=''2025380''>out</span>
  <span m=''2025500''>here.</span> <span m=''2025650''>That</span> <span m=''2025820''>turns</span>
  <span m=''2026030''>out</span> <span m=''2026140''>to</span> <span m=''2026210''>be</span>
  <span m=''2026320''>junk.</span> <span m=''2026650''>We''re</span> <span m=''2026750''>not</span>
  <span m=''2026950''>going</span> <span m=''2027060''>to</span> <span m=''2027450''>need</span>
  <span m=''2027600''>it</span> <span m=''2027680''>because</span> <span m=''2027850''>the</span>
  <span m=''2027910''>sort</span> <span m=''2028070''>of</span> <span m=''2028140''>outside</span>
  <span m=''2028600''>the</span> <span m=''2028670''>diagram.</span> </p><p><span
  m=''2029260''>You</span> <span m=''2029370''>could</span> <span m=''2029490''>folder</span>
  <span m=''2030220''>underneath.</span> <span m=''2030690''>Get</span> <span m=''2030810''>rid</span>
  <span m=''2030930''>of</span> <span m=''2031030''>it.</span> <span m=''2033420''>You''ve</span>
  <span m=''2033650''>got</span> <span m=''2034120''>a</span> <span m=''2034210''>quadrilateral</span>
  <span m=''2034950''>here</span> <span m=''2035460''>between</span> <span m=''2035940''>the</span>
  <span m=''2036050''>green</span> <span m=''2036260''>lines.</span> <span m=''2036820''>We''ve
  got a</span> <span m=''2037310''>triangle</span> <span m=''2037710''>up here,</span>
  <span m=''2038160''>a triangle at the</span> <span m=''2038650''>top,</span> <span
  m=''2038970''>triangle</span> <span m=''2039340''>on the</span> <span m=''2039420''>left.</span>
  <span m=''2040700''>All</span> <span m=''2041020''>we</span> <span m=''2041120''>need</span>
  <span m=''2041320''>to</span> <span m=''2041420''>do</span> <span m=''2041700''>is</span>
  <span m=''2041870''>fill</span> <span m=''2042210''>in</span> <span m=''2042440''>those</span>
  <span m=''2042710''>little</span> <span m=''2042950''>parts.</span> <span m=''2044190''>Fill</span>
  <span m=''2044490''>in</span> <span m=''2044570''>that</span> <span m=''2044740''>triangle.</span>
  <span m=''2045190''>Fill</span> <span m=''2045500''>in that</span> <span m=''2045690''>quadrilateral.</span>
  </p><p><span m=''2046410''>Of</span> <span m=''2046530''>course,</span> <span m=''2046940''>in</span>
  <span m=''2047040''>general,</span> <span m=''2047380''>there</span> <span m=''2047470''>might</span>
  <span m=''2047630''>not</span> <span m=''2047760''>be</span> <span m=''2047890''>any</span>
  <span m=''2048080''>active</span> <span m=''2048340''>paths,</span> <span m=''2048670''>and</span>
  <span m=''2048730''>we</span> <span m=''2048790''>haven''t</span> <span m=''2049050''>simplified</span>
  <span m=''2049489''>the</span> <span m=''2049570''>diagram</span> <span m=''2049949''>at</span>
  <span m=''2050010''>all.</span> <span m=''2050889''>But</span> <span m=''2050989''>if</span>
  <span m=''2051080''>there</span> <span m=''2051210''>are</span> <span m=''2051239''>no</span>
  <span m=''2051480''>active</span> <span m=''2051800''>paths,</span> <span m=''2052239''>you''re</span>
  <span m=''2052420''>really</span> <span m=''2052750''>probably</span> <span m=''2053130''>not</span>
  <span m=''2053330''>very</span> <span m=''2053500''>efficient.</span> <span m=''2053896''>That</span>
  <span m=''2054690''>means</span> <span m=''2054920''>none</span> <span m=''2055159''>of</span>
  <span m=''2055250''>these</span> <span m=''2055440''>constraints</span> <span m=''2055850''>are</span>
  <span m=''2055920''>tight.</span> <span m=''2057080''>That</span> <span m=''2057260''>means</span>
  <span m=''2057520''>you</span> <span m=''2057730''>could</span> <span m=''2058090''>increase</span>
  <span m=''2059389''>the</span> <span m=''2059489''>scale</span> <span m=''2059800''>factor</span>
  <span m=''2060620''>lambda,</span> <span m=''2061960''>make</span> <span m=''2062179''>a</span>
  <span m=''2062239''>better</span> <span m=''2062560''>model.</span> </p><p><span
  m=''2063719''>You</span> <span m=''2063860''>can</span> <span m=''2063989''>increase</span>
  <span m=''2064389''>lambda</span> <span m=''2064550''>at</span> <span m=''2064630''>least</span>
  <span m=''2064860''>a</span> <span m=''2064909''>little</span> <span m=''2065170''>bit.</span>
  <span m=''2065460''>If</span> <span m=''2065620''>all</span> <span m=''2065889''>of</span>
  <span m=''2065960''>these</span> <span m=''2066179''>are</span> <span m=''2066300''>strictly</span>
  <span m=''2066880''>greater,</span> <span m=''2067909''>you</span> <span m=''2068050''>can</span>
  <span m=''2068199''>increase</span> <span m=''2068540''>lambda</span> <span m=''2068840''>until</span>
  <span m=''2069120''>one</span> <span m=''2069320''>of</span> <span m=''2069380''>them</span>
  <span m=''2069510''>becomes</span> <span m=''2069840''>equal.</span> <span m=''2071070''>So</span>
  <span m=''2071190''>you</span> <span m=''2071239''>should</span> <span m=''2071460''>have</span>
  <span m=''2071600''>at</span> <span m=''2071670''>least</span> <span m=''2071920''>one</span>
  <span m=''2072110''>active</span> <span m=''2072400''>path.</span> <span m=''2072679''>And</span>
  <span m=''2072760''>in</span> <span m=''2072830''>fact</span> <span m=''2073139''>if</span>
  <span m=''2073250''>you''re</span> <span m=''2073370''>efficient,</span> <span m=''2073739''>you</span>
  <span m=''2073820''>should</span> <span m=''2073969''>have</span> <span m=''2074070''>lots</span>
  <span m=''2074300''>of</span> <span m=''2074400''>active</span> <span m=''2074650''>paths.</span>
  <span m=''2077300''>I don''t</span> <span m=''2078420''>think</span> <span m=''2078639''>I</span>
  <span m=''2078699''>need</span> <span m=''2078900''>to</span> <span m=''2078980''>be</span>
  <span m=''2079179''>too</span> <span m=''2079489''>formal</span> <span m=''2079909''>about</span>
  <span m=''2080210''>that.</span> <span m=''2086080''>But</span> <span m=''2086219''>it''s</span>
  <span m=''2086389''>true.</span> </p><p><span m=''2089380''>And</span> <span m=''2089480''>here''s</span>
  <span m=''2089730''>one</span> <span m=''2089949''>thing</span> <span m=''2090110''>you</span>
  <span m=''2090239''>can</span> <span m=''2090389''>show</span> <span m=''2090800''>about</span>
  <span m=''2092050''>active</span> <span m=''2092389''>paths.</span> <span m=''2093469''>So
  what would</span> <span m=''2093880''>be</span> <span m=''2094040''>really</span>
  <span m=''2094330''>nice,</span> <span m=''2094909''>in</span> <span m=''2095050''>this</span>
  <span m=''2095230''>example,</span> <span m=''2095750''>I</span> <span m=''2095810''>have</span>
  <span m=''2095949''>triangles</span> <span m=''2096590''>and</span> <span m=''2096679''>quadrilaterals.</span>
  <span m=''2097450''>In</span> <span m=''2097530''>general,</span> <span m=''2097880''>I''m</span>
  <span m=''2097950''>going</span> <span m=''2098040''>to</span> <span m=''2098080''>have</span>
  <span m=''2098250''>a</span> <span m=''2098290''>whole</span> <span m=''2098470''>bunch</span>
  <span m=''2098710''>of</span> <span m=''2098760''>different</span> <span m=''2099040''>shapes.</span>
  <span m=''2100490''>Some</span> <span m=''2100750''>of</span> <span m=''2100790''>them</span>
  <span m=''2100910''>could</span> <span m=''2101040''>even</span> <span m=''2101250''>be</span>
  <span m=''2101380''>non-convex</span> <span m=''2101910''>which</span> <span m=''2102240''>would</span>
  <span m=''2102410''>be</span> <span m=''2102570''>annoying.</span> </p><p><span
  m=''2103770''>I</span> <span m=''2103890''>would</span> <span m=''2104040''>really</span>
  <span m=''2104300''>just</span> <span m=''2104510''>like</span> <span m=''2104670''>to</span>
  <span m=''2104750''>deal</span> <span m=''2104940''>with</span> <span m=''2104990''>triangles</span>
  <span m=''2105470''>because</span> <span m=''2106080''>I</span> <span m=''2106190''>like</span>
  <span m=''2106380''>triangles--</span> <span m=''2107020''>geometer.</span> <span
  m=''2107670''>And</span> <span m=''2107950''>triangles</span> <span m=''2108320''>are</span>
  <span m=''2108390''>simple.</span> <span m=''2109300''>And</span> <span m=''2109470''>it</span>
  <span m=''2109530''>looks</span> <span m=''2109810''>like</span> <span m=''2110000''>the</span>
  <span m=''2110100''>crease</span> <span m=''2110340''>pattern in a</span> <span
  m=''2110750''>triangle</span> <span m=''2111170''>is</span> <span m=''2111280''>pretty</span>
  <span m=''2111840''>simple.</span> <span m=''2112500''>In</span> <span m=''2112600''>fact,</span>
  <span m=''2112880''>it''s</span> <span m=''2112900''>just</span> <span m=''2113450''>angular</span>
  <span m=''2113830''>bisectors</span> <span m=''2114440''>of</span> <span m=''2114510''>the</span>
  <span m=''2114610''>triangle</span> <span m=''2115370''>plus</span> <span m=''2115690''>a</span>
  <span m=''2115740''>few</span> <span m=''2116120''>extra</span> <span m=''2116620''>perpendicular</span>
  <span m=''2117220''>folds.</span> <span m=''2119940''>So</span> <span m=''2120510''>that</span>
  <span m=''2120800''>would</span> <span m=''2120880''>be</span> <span m=''2120980''>kind</span>
  <span m=''2121200''>of</span> <span m=''2121270''>nice</span> <span m=''2122140''>if</span>
  <span m=''2122340''>I</span> <span m=''2122380''>could</span> <span m=''2122520''>get</span>
  <span m=''2122680''>everything</span> <span m=''2123690''>triangles.</span> <span
  m=''2124220''>To</span> <span m=''2124340''>do</span> <span m=''2124500''>that,</span>
  <span m=''2124760''>I</span> <span m=''2124860''>need</span> <span m=''2124930''>lots</span>
  <span m=''2125190''>of</span> <span m=''2125280''>active</span> <span m=''2125560''>paths.</span>
  </p><p><span m=''2126640''>So</span> <span m=''2126770''>how</span> <span m=''2126930''>can</span>
  <span m=''2127060''>I</span> <span m=''2127100''>guarantee</span> <span m=''2128010''>that</span>
  <span m=''2128340''>there''s</span> <span m=''2128620''>lots</span> <span m=''2128840''>of</span>
  <span m=''2128940''>active</span> <span m=''2129240''>paths?</span> <span m=''2130360''>I''m</span>
  <span m=''2130520''>going</span> <span m=''2131530''>wave</span> <span m=''2131760''>my</span>
  <span m=''2131880''>hands</span> <span m=''2132150''>a</span> <span m=''2132200''>little</span>
  <span m=''2132360''>bit</span> <span m=''2132490''>about</span> <span m=''2132670''>how</span>
  <span m=''2132820''>this is</span> <span m=''2133130''>done.</span> <span m=''2137580''>But</span>
  <span m=''2137630''>the</span> <span m=''2137750''>idea</span> <span m=''2137980''>is</span>
  <span m=''2138310''>to</span> <span m=''2141680''>augment</span> <span m=''2142250''>the</span>
  <span m=''2142350''>tree.</span> <span m=''2143200''>So</span> <span m=''2143330''>I</span>
  <span m=''2143400''>have</span> <span m=''2143640''>some</span> <span m=''2143850''>tree</span>
  <span m=''2144050''>that</span> <span m=''2144180''>I</span> <span m=''2144250''>actually</span>
  <span m=''2144760''>want</span> <span m=''2144970''>to</span> <span m=''2145020''>make,</span>
  <span m=''2146060''>like</span> <span m=''2146370''>lizard.</span> <span m=''2147490''>And</span>
  <span m=''2148070''>I''m</span> <span m=''2148220''>going</span> <span m=''2148320''>to</span>
  <span m=''2148380''>add</span> <span m=''2148640''>some</span> <span m=''2148820''>extra</span>
  <span m=''2149100''>stuff.</span> <span m=''2149930''>Like</span> <span m=''2150030''>maybe</span>
  <span m=''2150340''>I''ll</span> <span m=''2150500''>add</span> <span m=''2151010''>a</span>
  <span m=''2151310''>branch</span> <span m=''2151720''>here</span> <span m=''2152020''>and</span>
  <span m=''2152100''>a</span> <span m=''2152150''>branch</span> <span m=''2152490''>here
  or</span> <span m=''2152820''>whatever.</span> <span m=''2153880''>Whatever</span>
  <span m=''2154020''>it takes.</span> </p><p><span m=''2157130''>I</span> <span m=''2157250''>got</span>
  <span m=''2157380''>to</span> <span m=''2157460''>do</span> <span m=''2157570''>so</span>
  <span m=''2157950''>carefully.</span> <span m=''2159830''>So</span> <span m=''2160010''>let</span>
  <span m=''2160160''>me</span> <span m=''2160270''>say</span> <span m=''2160450''>what</span>
  <span m=''2160570''>that</span> <span m=''2160730''>means.</span> <span m=''2165400''>So</span>
  <span m=''2165570''>I''m</span> <span m=''2165620''>going</span> <span m=''2165710''>to</span>
  <span m=''2165780''>add</span> <span m=''2166140''>extra</span> <span m=''2166630''>leaves</span>
  <span m=''2174310''>to</span> <span m=''2174440''>the</span> <span m=''2174520''>shadow</span>
  <span m=''2174860''>tree.</span> <span m=''2179340''>My</span> <span m=''2179520''>goal</span>
  <span m=''2180020''>is</span> <span m=''2180310''>to</span> <span m=''2180530''>make</span>
  <span m=''2181930''>the</span> <span m=''2182180''>active</span> <span m=''2182630''>paths</span>
  <span m=''2185210''>triangulate</span> <span m=''2186090''>the</span> <span m=''2186280''>paper</span>
  <span m=''2207300''>without</span> <span m=''2207790''>changing</span> <span m=''2208170''>the</span>
  <span m=''2208240''>scale</span> <span m=''2208540''>factor.</span> </p><p><span
  m=''2217040''>So</span> <span m=''2217080''>this</span> <span m=''2217290''>is</span>
  <span m=''2217420''>kind</span> <span m=''2217670''>of</span> <span m=''2217770''>a</span>
  <span m=''2217830''>cheat.</span> <span m=''2218460''>And</span> <span m=''2218890''>most
  of</span> <span m=''2219120''>the</span> <span m=''2219220''>time,</span> <span
  m=''2219460''>you</span> <span m=''2219550''>don''t</span> <span m=''2219730''>actually</span>
  <span m=''2220000''>need</span> <span m=''2220200''>this</span> <span m=''2220370''>cheat.</span>
  <span m=''2220740''>But</span> <span m=''2221480''>for</span> <span m=''2221640''>proving</span>
  <span m=''2221960''>things,</span> <span m=''2222510''>it</span> <span m=''2223150''>makes</span>
  <span m=''2223400''>life</span> <span m=''2223600''>a</span> <span m=''2223640''>little</span>
  <span m=''2223860''>easier.</span> <span m=''2226330''>So</span> <span m=''2226550''>we</span>
  <span m=''2226660''>want</span> <span m=''2226870''>to</span> <span m=''2226930''>show</span>
  <span m=''2227250''>that</span> <span m=''2227380''>it''s</span> <span m=''2227510''>enough</span>
  <span m=''2227860''>to</span> <span m=''2227980''>place</span> <span m=''2228890''>the</span>
  <span m=''2228980''>vertices</span> <span m=''2229500''>subject</span> <span m=''2229860''>to</span>
  <span m=''2229950''>this,</span> <span m=''2230340''>the</span> <span m=''2230520''>leaves</span>
  <span m=''2230800''>subject</span> <span m=''2231180''>to</span> <span m=''2231270''>this</span>
  <span m=''2231450''>constraint.</span> <span m=''2234080''>So</span> <span m=''2234540''>ideally,</span>
  <span m=''2235140''>we</span> <span m=''2235290''>make</span> <span m=''2235510''>our</span>
  <span m=''2235660''>tree.</span> </p><p><span m=''2236090''>But</span> <span m=''2236200''>if</span>
  <span m=''2236290''>we</span> <span m=''2236420''>make</span> <span m=''2236610''>an</span>
  <span m=''2236690''>even</span> <span m=''2236930''>more</span> <span m=''2237210''>complicated</span>
  <span m=''2237850''>tree,</span> <span m=''2238790''>like</span> <span m=''2238960''>with</span>
  <span m=''2239070''>these</span> <span m=''2239300''>extra</span> <span m=''2239720''>little</span>
  <span m=''2239930''>limbs,</span> <span m=''2241170''>we</span> <span m=''2241310''>can</span>
  <span m=''2242010''>get</span> <span m=''2242180''>rid</span> <span m=''2242370''>of</span>
  <span m=''2242480''>them</span> <span m=''2242650''>at</span> <span m=''2242750''>the</span>
  <span m=''2242880''>end.</span> <span m=''2243050''>You</span> <span m=''2243150''>just</span>
  <span m=''2243530''>fold</span> <span m=''2243860''>them</span> <span m=''2244030''>over</span>
  <span m=''2244330''>and</span> <span m=''2244480''>collapse</span> <span m=''2244930''>this</span>
  <span m=''2245130''>flap</span> <span m=''2245420''>against</span> <span m=''2245750''>an</span>
  <span m=''2245910''>adjacent</span> <span m=''2246220''>flap.</span> <span m=''2247770''>So</span>
  <span m=''2248080''>if</span> <span m=''2248650''>we</span> <span m=''2248760''>make</span>
  <span m=''2248950''>our</span> <span m=''2249050''>life</span> <span m=''2249250''>harder,</span>
  <span m=''2250760''>that''s</span> <span m=''2250970''>OK,</span> <span m=''2251240''>too.</span>
  <span m=''2251900''>If</span> <span m=''2252110''>we</span> <span m=''2252200''>could</span>
  <span m=''2252340''>fold</span> <span m=''2252500''>a</span> <span m=''2252560''>more</span>
  <span m=''2252820''>complicated</span> <span m=''2253350''>tree,</span> <span m=''2253580''>in</span>
  <span m=''2253680''>particular</span> <span m=''2254100''>we</span> <span m=''2254230''>folded
  the</span> <span m=''2254610''>tree</span> <span m=''2254830''>we</span> <span m=''2254910''>wanted.</span>
  </p><p><span m=''2255540''>If</span> <span m=''2255690''>we</span> <span m=''2255800''>can</span>
  <span m=''2255930''>do</span> <span m=''2256060''>that</span> <span m=''2256250''>without</span>
  <span m=''2256600''>changing</span> <span m=''2256940''>the</span> <span m=''2257010''>scale</span>
  <span m=''2257330''>factor,</span> <span m=''2258850''>then</span> <span m=''2259450''>great.</span>
  <span m=''2261270''>Then,</span> <span m=''2261990''>we</span> <span m=''2262550''>did</span>
  <span m=''2262700''>what</span> <span m=''2262820''>we</span> <span m=''2262930''>wanted</span>
  <span m=''2263270''>to</span> <span m=''2263350''>do.</span> <span m=''2263480''>We</span>
  <span m=''2263610''>folded</span> <span m=''2264930''>our</span> <span m=''2265160''>piece</span>
  <span m=''2265370''>of</span> <span m=''2265440''>paper</span> <span m=''2265780''>with</span>
  <span m=''2265940''>the</span> <span m=''2266030''>desired</span> <span m=''2266900''>scale</span>
  <span m=''2267200''>factor.</span> <span m=''2268270''>In</span> <span m=''2268420''>reality,</span>
  <span m=''2268850''>we''re</span> <span m=''2268960''>actually</span> <span m=''2269190''>going</span>
  <span m=''2269300''>to</span> <span m=''2269340''>move</span> <span m=''2269580''>the</span>
  <span m=''2269680''>leaves</span> <span m=''2269970''>around</span> <span m=''2270200''>a</span>
  <span m=''2270250''>little</span> <span m=''2270450''>bit</span> <span m=''2270790''>so</span>
  <span m=''2270940''>that</span> <span m=''2271250''>we</span> <span m=''2271450''>have</span>
  <span m=''2271710''>to</span> <span m=''2271810''>do.</span> </p><p><span m=''2273220''>We''re</span>
  <span m=''2273290''>going</span> <span m=''2273380''>to</span> <span m=''2273430''>move</span>
  <span m=''2273670''>around</span> <span m=''2273930''>the</span> <span m=''2273990''>leaves</span>
  <span m=''2274250''>that</span> <span m=''2274280''>you</span> <span m=''2274430''>already</span>
  <span m=''2274640''>placed</span> <span m=''2275100''>in</span> <span m=''2275230''>order</span>
  <span m=''2275400''>to</span> <span m=''2275540''>make</span> <span m=''2275750''>room</span>
  <span m=''2275910''>for</span> <span m=''2276020''>the</span> <span m=''2276140''>new</span>
  <span m=''2276370''>leaves.</span> <span m=''2277400''>But</span> <span m=''2277530''>here''s</span>
  <span m=''2277720''>the</span> <span m=''2277840''>idea.</span> <span m=''2278520''>We</span>
  <span m=''2280060''>have</span> <span m=''2280210''>these</span> <span m=''2280380''>leaves.</span>
  <span m=''2281600''>There''s</span> <span m=''2281820''>some</span> <span m=''2282100''>active</span>
  <span m=''2282400''>paths,</span> <span m=''2282880''>these</span> <span m=''2283040''>green</span>
  <span m=''2283270''>lines.</span> <span m=''2284470''>And</span> <span m=''2285670''>we''d</span>
  <span m=''2285840''>really-- we</span> <span m=''2286240''>have</span> <span m=''2286380''>this</span>
  <span m=''2286520''>quadrilateral</span> <span m=''2286865''>in</span> <span m=''2287210''>the</span>
  <span m=''2287310''>center.</span> <span m=''2287610''>We''d</span> <span m=''2287770''>really</span>
  <span m=''2288010''>like</span> <span m=''2288260''>to</span> <span m=''2288370''>subdivide</span>
  <span m=''2288990''>it.</span> <span m=''2289380''>Like</span> <span m=''2289540''>this</span>
  <span m=''2289700''>black</span> <span m=''2290050''>line</span> <span m=''2290280''>is</span>
  <span m=''2290410''>kind</span> <span m=''2290530''>of</span> <span m=''2290610''>asking</span>
  <span m=''2291090''>for</span> <span m=''2291370''>it.</span> </p><p><span m=''2291420''>It
  would</span> <span m=''2291490''>be</span> <span m=''2291640''>really</span> <span
  m=''2291870''>nice</span> <span m=''2292150''>if</span> <span m=''2292260''>we</span>
  <span m=''2292380''>could</span> <span m=''2292510''>just</span> <span m=''2293140''>add</span>
  <span m=''2293410''>in</span> <span m=''2294460''>an</span> <span m=''2294610''>active</span>
  <span m=''2294910''>paths</span> <span m=''2295230''>there.</span> <span m=''2296590''>And</span>
  <span m=''2296780''>you</span> <span m=''2296920''>can</span> <span m=''2297090''>do</span>
  <span m=''2297300''>it.</span> <span m=''2297930''>Let''s</span> <span m=''2298020''>see</span>
  <span m=''2298150''>if</span> <span m=''2298270''>I</span> <span m=''2298350''>can</span>
  <span m=''2298510''>identify</span> <span m=''2299160''>what</span> <span m=''2299530''>we''re</span>
  <span m=''2299770''>talking</span> <span m=''2300120''>about</span> <span m=''2300340''>here.</span>
  <span m=''2301170''>So</span> <span m=''2302060''>a</span> <span m=''2302390''>fun</span>
  <span m=''2302610''>thing</span> <span m=''2302770''>about</span> <span m=''2302940''>active</span>
  <span m=''2303230''>paths,</span> <span m=''2303570''>you</span> <span m=''2303730''>look</span>
  <span m=''2303890''>at</span> <span m=''2303990''>two</span> <span m=''2304160''>leaves</span>
  <span m=''2304450''>like</span> <span m=''2304590''>g d</span> <span m=''2304850''>here,</span>
  <span m=''2306240''>which</span> <span m=''2306590''>corresponds</span> <span m=''2307130''>to</span>
  <span m=''2307240''>this</span> <span m=''2307440''>path</span> <span m=''2308200''>g
  d</span> <span m=''2308480''>here,</span> <span m=''2309300''>because</span> <span
  m=''2310310''>it''s</span> <span m=''2310530''>active,</span> <span m=''2311140''>you
  know</span> <span m=''2311620''>this</span> <span m=''2312100''>length</span> <span
  m=''2312500''>is</span> <span m=''2312650''>exactly</span> <span m=''2313240''>the</span>
  <span m=''2313340''>length</span> <span m=''2314040''>traced</span> <span m=''2314390''>right</span>
  <span m=''2314550''>here.</span> </p><p><span m=''2315490''>So</span> <span m=''2315610''>that</span>
  <span m=''2315720''>means,</span> <span m=''2315950''>this</span> <span m=''2316190''>segment</span>
  <span m=''2316620''>has</span> <span m=''2316880''>to</span> <span m=''2316970''>be</span>
  <span m=''2317100''>folded</span> <span m=''2317550''>right</span> <span m=''2317770''>along</span>
  <span m=''2318070''>the</span> <span m=''2318160''>tree</span> <span m=''2318410''>here.</span>
  <span m=''2319080''>You</span> <span m=''2319200''>know</span> <span m=''2319450''>that</span>
  <span m=''2319620''>this</span> <span m=''2319790''>segment</span> <span m=''2320490''>is</span>
  <span m=''2320690''>that.</span> <span m=''2321340''>And</span> <span m=''2321520''>so</span>
  <span m=''2321610''>in</span> <span m=''2321680''>particular,</span> <span m=''2322080''>you
  know</span> <span m=''2322480''>where</span> <span m=''2322620''>c</span> <span
  m=''2322960''>is</span> <span m=''2323610''>on</span> <span m=''2323790''>that</span>
  <span m=''2324000''>segment.</span> <span m=''2324790''>C</span> <span m=''2325000''>actually</span>
  <span m=''2325280''>comes</span> <span m=''2325500''>from</span> <span m=''2325640''>multiple</span>
  <span m=''2326060''>points</span> <span m=''2326380''>in</span> <span m=''2326440''>this</span>
  <span m=''2326600''>diagram.</span> <span m=''2327360''>But</span> <span m=''2327480''>you</span>
  <span m=''2327590''>know</span> <span m=''2327840''>that</span> <span m=''2328030''>this</span>
  <span m=''2328230''>point</span> <span m=''2328520''>right</span> <span m=''2328720''>here</span>
  <span m=''2329440''>must</span> <span m=''2329850''>fold</span> <span m=''2330140''>to</span>
  <span m=''2330220''>c.</span> <span m=''2332345''>And you</span> <span m=''2332770''>know</span>
  <span m=''2332930''>this</span> <span m=''2333150''>point</span> <span m=''2333450''>must</span>
  <span m=''2333720''>fold</span> <span m=''2333980''>here</span> <span m=''2334630''>and</span>
  <span m=''2334790''>so on.</span> <span m=''2335260''>These</span> <span m=''2335460''>guys</span>
  <span m=''2336140''>correspond.</span> </p><p><span m=''2340500''>So</span> <span
  m=''2340940''>that''s</span> <span m=''2341380''>good.</span> <span m=''2341730''>So</span>
  <span m=''2341800''>if</span> <span m=''2341930''>I</span> <span m=''2342010''>look</span>
  <span m=''2342250''>at</span> <span m=''2342410''>this</span> <span m=''2343390''>quadrilateral,</span>
  <span m=''2344590''>it</span> <span m=''2344770''>corresponds</span> <span m=''2345320''>so</span>
  <span m=''2345490''>g</span> <span m=''2345990''>to</span> <span m=''2346100''>c</span>
  <span m=''2346650''>to</span> <span m=''2347103''>d</span> <span m=''2347556''>to</span>
  <span m=''2348010''>c</span> <span m=''2348440''>to</span> <span m=''2348670''>h</span>
  <span m=''2349720''>to</span> <span m=''2350080''>c</span> <span m=''2350720''>to</span>
  <span m=''2350980''>b</span> <span m=''2352276''>to</span> <span m=''2352708''>a</span>
  <span m=''2353140''>back</span> <span m=''2353450''>to</span> <span m=''2353570''>b</span>
  <span m=''2354530''>back</span> <span m=''2354790''>to</span> <span m=''2354890''>c.</span>
  <span m=''2356220''>And</span> <span m=''2356330''>so</span> <span m=''2356440''>my</span>
  <span m=''2356610''>guess</span> <span m=''2356860''>is</span> <span m=''2356990''>if</span>
  <span m=''2357130''>you</span> <span m=''2357250''>add</span> <span m=''2357500''>a</span>
  <span m=''2357570''>little</span> <span m=''2358560''>limb</span> <span m=''2359270''>in</span>
  <span m=''2359420''>here--</span> <span m=''2365300''>I</span> <span m=''2365390''>think</span>
  <span m=''2365630''>I</span> <span m=''2365690''>can</span> <span m=''2365850''>draw
  on</span> <span m=''2366250''>this.</span> <span m=''2366670''>That would</span>
  <span m=''2367380''>be</span> <span m=''2367470''>nice.</span> <span m=''2370050''>Should</span>
  <span m=''2370280''>really</span> <span m=''2370570''>tell</span> <span m=''2370830''>you</span>
  <span m=''2371090''>about--</span> <span m=''2372780''>is this</span> <span m=''2372950''>going</span>
  <span m=''2373060''>to</span> <span m=''2373130''>work?</span> <span m=''2375120''>Yes.</span>
  <span m=''2375600''>It''s</span> <span m=''2375790''>kind</span> <span m=''2375980''>of</span>
  <span m=''2376050''>white,</span> <span m=''2376460''>but there</span> <span m=''2376910''>we
  go.</span> <span m=''2379940''>So</span> <span m=''2382320''>great.</span> <span
  m=''2384020''>Draw a</span> <span m=''2384360''>fun</span> <span m=''2384580''>diagram</span>
  <span m=''2385070''>here.</span> </p><p><span m=''2388450''>This</span> <span m=''2388660''>is</span>
  <span m=''2388800''>how I</span> <span m=''2388930''>make</span> <span m=''2389130''>my</span>
  <span m=''2389230''>lecture</span> <span m=''2389520''>notes</span> <span m=''2389750''>if</span>
  <span m=''2389830''>you''re</span> <span m=''2389970''>curious.</span> <span m=''2390760''>This
  is</span> <span m=''2390830''>a tablet</span> <span m=''2391230''>PC.</span> <span
  m=''2396100''>Now,</span> <span m=''2396430''>I''ve</span> <span m=''2396590''>got</span>
  <span m=''2396840''>some--</span> <span m=''2402160''>Tell me if</span> <span m=''2402320''>I</span>
  <span m=''2402390''>make</span> <span m=''2402590''>a</span> <span m=''2402640''>mistake,</span>
  <span m=''2403570''>those</span> <span m=''2403640''>who know</span> <span m=''2403800''>what</span>
  <span m=''2403890''>I''m</span> <span m=''2404000''>drawing.</span> <span m=''2408088''>What
  the</span> <span m=''2408540''>hell</span> <span m=''2408900''>is</span> <span m=''2409090''>this?</span>
  <span m=''2410060''>I</span> <span m=''2410890''>think</span> <span m=''2411060''>it</span>
  <span m=''2411170''>goes</span> <span m=''2411470''>there.</span> <span m=''2412916''>There.</span>
  <span m=''2415320''>There.</span> <span m=''2416150''>I''ll</span> <span m=''2416640''>explain</span>
  <span m=''2417290''>what I''m</span> <span m=''2417550''>drawing</span> <span m=''2417890''>once</span>
  <span m=''2418100''>I''ve</span> <span m=''2418210''>drawn</span> <span m=''2418440''>it.</span>
  <span m=''2418880''>It''s</span> <span m=''2419180''>easier.</span> <span m=''2421920''>Something</span>
  <span m=''2422200''>like</span> <span m=''2422380''>that.</span> </p><p><span m=''2423180''>This</span>
  <span m=''2423300''>is</span> <span m=''2423490''>a</span> <span m=''2424880''>bunch</span>
  <span m=''2425110''>of</span> <span m=''2425220''>disks</span> <span m=''2425930''>and</span>
  <span m=''2426270''>a</span> <span m=''2426300''>bunch</span> <span m=''2426510''>of</span>
  <span m=''2426590''>other</span> <span m=''2426850''>things,</span> <span m=''2427330''>there''s</span>
  <span m=''2427480''>only</span> <span m=''2427710''>one</span> <span m=''2427960''>here</span>
  <span m=''2428490''>called</span> <span m=''2428740''>rivers.</span> <span m=''2430490''>And</span>
  <span m=''2430730''>this</span> <span m=''2430890''>is</span> <span m=''2431030''>a</span>
  <span m=''2431100''>geometric</span> <span m=''2431680''>way</span> <span m=''2431810''>to</span>
  <span m=''2431910''>think</span> <span m=''2432130''>about</span> <span m=''2432390''>the</span>
  <span m=''2432490''>constraints.</span> <span m=''2434260''>If</span> <span m=''2434450''>you</span>
  <span m=''2434620''>look</span> <span m=''2434970''>at</span> <span m=''2436230''>this</span>
  <span m=''2436460''>structure--</span> <span m=''2439160''>so</span> <span m=''2439400''>I</span>
  <span m=''2439500''>have</span> <span m=''2440480''>a</span> <span m=''2440600''>disk</span>
  <span m=''2440960''>down</span> <span m=''2441180''>here</span> <span m=''2441400''>corresponding</span>
  <span m=''2441920''>to</span> <span m=''2442030''>d.</span> <span m=''2442290''>I
  have</span> <span m=''2442420''>a</span> <span m=''2442490''>disk</span> <span m=''2442785''>corresponding</span>
  <span m=''2443080''>to</span> <span m=''2443420''>h,</span> <span m=''2443910''>a
  disk corresponding</span> <span m=''2444420''>to</span> <span m=''2444750''>g,</span>
  <span m=''2445205''>a</span> <span m=''2445660''>river</span> <span m=''2446370''>corresponding</span>
  <span m=''2446930''>to</span> <span m=''2447040''>the</span> <span m=''2447150''>segment</span>
  <span m=''2447650''>b c.</span> </p><p><span m=''2448540''>The</span> <span m=''2448630''>reason</span>
  <span m=''2448900''>I</span> <span m=''2448920''>only</span> <span m=''2449130''>have</span>
  <span m=''2449280''>one</span> <span m=''2449470''>river is</span> <span m=''2449850''>there''s</span>
  <span m=''2450000''>only</span> <span m=''2450200''>one</span> <span m=''2450690''>interior</span>
  <span m=''2451300''>edge</span> <span m=''2451860''>in this</span> <span m=''2452140''>tree.</span>
  <span m=''2452420''>Everything</span> <span m=''2452770''>else</span> <span m=''2452950''>is</span>
  <span m=''2453040''>a</span> <span m=''2453110''>leaf</span> <span m=''2453350''>edge.</span>
  <span m=''2454160''>So</span> <span m=''2454320''>leaf</span> <span m=''2454590''>edges</span>
  <span m=''2454930''>are</span> <span m=''2455020''>going</span> <span m=''2455170''>to</span>
  <span m=''2455240''>be</span> <span m=''2455390''>disks.</span> <span m=''2456330''>All</span>
  <span m=''2456550''>non</span> <span m=''2456810''>leaf</span> <span m=''2457050''>edges</span>
  <span m=''2457400''>are</span> <span m=''2457480''>going</span> <span m=''2457610''>to</span>
  <span m=''2457680''>be</span> <span m=''2457810''>rivers.</span> <span m=''2458760''>And</span>
  <span m=''2458940''>the</span> <span m=''2459030''>structure,</span> <span m=''2459690''>the</span>
  <span m=''2459710''>way</span> <span m=''2459880''>that</span> <span m=''2460040''>those</span>
  <span m=''2460300''>things</span> <span m=''2460930''>connect</span> <span m=''2461300''>to</span>
  <span m=''2461400''>each</span> <span m=''2461570''>other</span> <span m=''2461810''>is</span>
  <span m=''2461960''>the</span> <span m=''2462050''>same</span> <span m=''2462650''>as</span>
  <span m=''2462890''>the</span> <span m=''2462970''>structure</span> <span m=''2463360''>in</span>
  <span m=''2463460''>this</span> <span m=''2463715''>tree.</span> </p><p><span m=''2464560''>So</span>
  <span m=''2464690''>you''ve</span> <span m=''2464810''>got</span> <span m=''2465570''>the</span>
  <span m=''2465680''>three</span> <span m=''2465960''>disks</span> <span m=''2466270''>down</span>
  <span m=''2466500''>here,</span> <span m=''2467020''>which</span> <span m=''2467390''>corresponds</span>
  <span m=''2467770''>to</span> <span m=''2467830''>these</span> <span m=''2468030''>leaf</span>
  <span m=''2468260''>edges.</span> <span m=''2468930''>They</span> <span m=''2469100''>all</span>
  <span m=''2469360''>touch</span> <span m=''2469660''>a</span> <span m=''2469710''>common</span>
  <span m=''2470060''>river</span> <span m=''2470390''>because</span> <span m=''2470900''>all</span>
  <span m=''2471130''>of</span> <span m=''2471210''>those</span> <span m=''2471410''>edges</span>
  <span m=''2471830''>are</span> <span m=''2472040''>incident</span> <span m=''2472890''>to</span>
  <span m=''2473040''>that</span> <span m=''2474820''>edge</span> <span m=''2475320''>in</span>
  <span m=''2475490''>the</span> <span m=''2475580''>center.</span> <span m=''2476380''>And</span>
  <span m=''2476550''>there''s</span> <span m=''2476710''>three</span> <span m=''2476920''>disks</span>
  <span m=''2477170''>on</span> <span m=''2477240''>the</span> <span m=''2477330''>top</span>
  <span m=''2477620''>that</span> <span m=''2477720''>correspond</span> <span m=''2478160''>to</span>
  <span m=''2478230''>the</span> <span m=''2478340''>three</span> <span m=''2478570''>leaf</span>
  <span m=''2478950''>edges</span> <span m=''2479070''>up</span> <span m=''2479240''>here.</span>
  </p><p><span m=''2481100''>This</span> <span m=''2481270''>is</span> <span m=''2481380''>really</span>
  <span m=''2481610''>just</span> <span m=''2481830''>the</span> <span m=''2481910''>same</span>
  <span m=''2482240''>thing.</span> <span m=''2482540''>It''s</span> <span m=''2482630''>saying</span>
  <span m=''2482950''>that</span> <span m=''2483830''>if</span> <span m=''2484270''>you</span>
  <span m=''2484410''>want</span> <span m=''2484570''>to</span> <span m=''2484640''>look,</span>
  <span m=''2484840''>say,</span> <span m=''2485100''>at</span> <span m=''2485250''>the</span>
  <span m=''2485340''>distance</span> <span m=''2485650''>between</span> <span m=''2485950''>h</span>
  <span m=''2486380''>and</span> <span m=''2486850''>a</span> <span m=''2488160''>here.</span>
  <span m=''2488440''>The</span> <span m=''2488570''>distance between</span> <span
  m=''2489070''>h</span> <span m=''2489350''>and a</span> <span m=''2489510''>should</span>
  <span m=''2490050''>be</span> <span m=''2490190''>length</span> <span m=''2490480''>three.</span>
  <span m=''2491140''>And</span> <span m=''2491400''>those</span> <span m=''2491660''>three</span>
  <span m=''2491990''>lengths</span> <span m=''2492360''>are</span> <span m=''2492420''>represented</span>
  <span m=''2492940''>by</span> <span m=''2493850''>the</span> <span m=''2493940''>size</span>
  <span m=''2494180''>of</span> <span m=''2494270''>this</span> <span m=''2494500''>disk,</span>
  <span m=''2495090''>followed</span> <span m=''2495400''>by</span> <span m=''2495550''>the</span>
  <span m=''2495900''>width</span> <span m=''2496180''>of</span> <span m=''2496280''>this</span>
  <span m=''2496450''>river,</span> <span m=''2497060''>followed</span> <span m=''2497410''>by</span>
  <span m=''2497550''>the</span> <span m=''2497660''>size</span> <span m=''2498100''>of</span>
  <span m=''2498300''>the a</span> <span m=''2498400''>disk.</span> </p><p><span m=''2499660''>It''s</span>
  <span m=''2500350''>say</span> <span m=''2500610''>exactly</span> <span m=''2501100''>the</span>
  <span m=''2501210''>same</span> <span m=''2501420''>constraints,</span> <span m=''2501830''>just</span>
  <span m=''2502040''>represented</span> <span m=''2502510''>geometrically.</span>
  <span m=''2503500''>Now,</span> <span m=''2503640''>if</span> <span m=''2503740''>I''m</span>
  <span m=''2503830''>lucky,</span> <span m=''2504610''>these</span> <span m=''2505110''>regions</span>
  <span m=''2505500''>actually</span> <span m=''2505900''>kiss,</span> <span m=''2506260''>they</span>
  <span m=''2506370''>touch</span> <span m=''2506680''>at</span> <span m=''2506800''>points.</span>
  <span m=''2507530''>That''s</span> <span m=''2507770''>when</span> <span m=''2507900''>things</span>
  <span m=''2508120''>are</span> <span m=''2508220''>active.</span> <span m=''2509550''>And</span>
  <span m=''2509620''>you</span> <span m=''2509720''>could</span> <span m=''2509870''>draw</span>
  <span m=''2510730''>straight</span> <span m=''2511090''>across</span> <span m=''2511540''>from</span>
  <span m=''2511840''>a</span> <span m=''2512010''>to</span> <span m=''2512110''>h</span>
  <span m=''2512940''>and</span> <span m=''2513420''>never</span> <span m=''2513720''>go</span>
  <span m=''2513940''>in</span> <span m=''2514040''>these</span> <span m=''2514300''>outside</span>
  <span m=''2514740''>regions.</span> </p><p><span m=''2516050''>If</span> <span m=''2516130''>you''re</span>
  <span m=''2516230''>not</span> <span m=''2516450''>lucky,</span> <span m=''2517060''>they</span>
  <span m=''2517170''>won''t</span> <span m=''2517390''>touch.</span> <span m=''2518640''>If</span>
  <span m=''2518810''>they</span> <span m=''2518920''>don''t</span> <span m=''2519130''>touch,</span>
  <span m=''2519900''>make</span> <span m=''2520080''>them</span> <span m=''2520210''>touch.</span>
  <span m=''2521620''>That''s</span> <span m=''2521860''>all</span> <span m=''2522020''>I</span>
  <span m=''2522110''>want</span> <span m=''2522320''>to</span> <span m=''2522410''>do.</span>
  <span m=''2524210''>And</span> <span m=''2524480''>so</span> <span m=''2524710''>I</span>
  <span m=''2524900''>just</span> <span m=''2525160''>want</span> <span m=''2525410''>to</span>
  <span m=''2526720''>blow</span> <span m=''2527300''>up</span> <span m=''2527500''>these</span>
  <span m=''2527700''>regions,</span> <span m=''2528240''>make</span> <span m=''2528520''>them</span>
  <span m=''2528930''>longer,</span> <span m=''2529400''>for</span> <span m=''2529580''>example,</span>
  <span m=''2531780''>until</span> <span m=''2532170''>things</span> <span m=''2532430''>touch.</span>
  <span m=''2533280''>When</span> <span m=''2533420''>they</span> <span m=''2533520''>touch</span>
  <span m=''2533800''>enough,</span> <span m=''2534920''>if you</span> <span m=''2535060''>do</span>
  <span m=''2535220''>it</span> <span m=''2535310''>right,</span> <span m=''2535580''>you</span>
  <span m=''2535710''>can</span> <span m=''2535800''>actually</span> <span m=''2536040''>get</span>
  <span m=''2536180''>them</span> <span m=''2536290''>to</span> <span m=''2536380''>triangulate.</span>
  </p><p><span m=''2537670''>That''s</span> <span m=''2537900''>my</span> <span m=''2538100''>very</span>
  <span m=''2538590''>hand</span> <span m=''2538920''>wavy</span> <span m=''2539710''>argument.</span>
  <span m=''2540270''>It''s</span> <span m=''2540490''>proved</span> <span m=''2540880''>formally</span>
  <span m=''2541230''>in</span> <span m=''2541310''>the</span> <span m=''2541380''>book,</span>
  <span m=''2542110''>and</span> <span m=''2542410''>it''s</span> <span m=''2542500''>a</span>
  <span m=''2542550''>little</span> <span m=''2542740''>bit</span> <span m=''2542910''>technical.</span>
  <span m=''2543740''>So</span> <span m=''2544760''>I</span> <span m=''2544860''>think</span>
  <span m=''2545070''>I</span> <span m=''2545160''>will</span> <span m=''2545590''>move</span>
  <span m=''2545800''>on</span> <span m=''2548520''>and</span> <span m=''2549180''>tell</span>
  <span m=''2549510''>you</span> <span m=''2551430''>what</span> <span m=''2551600''>to</span>
  <span m=''2551680''>do</span> <span m=''2551800''>with</span> <span m=''2551860''>triangles.</span>
  </p><p><span m=''2609610''>So</span> <span m=''2611480''>suppose</span> <span m=''2611730''>you</span>
  <span m=''2611840''>have</span> <span m=''2612000''>some</span> <span m=''2612180''>triangle.</span>
  <span m=''2614310''>And</span> <span m=''2614560''>each</span> <span m=''2614810''>of</span>
  <span m=''2614890''>these</span> <span m=''2615240''>edges</span> <span m=''2615730''>is</span>
  <span m=''2615830''>an</span> <span m=''2615930''>active</span> <span m=''2616280''>path.</span>
  <span m=''2616970''>So</span> <span m=''2617100''>there''s</span> <span m=''2617240''>some</span>
  <span m=''2617440''>leaf</span> <span m=''2617710''>here.</span> <span m=''2621130''>We''ll</span>
  <span m=''2621650''>call</span> <span m=''2621850''>them</span> <span m=''2622030''>a,</span>
  <span m=''2622300''>b,</span> <span m=''2622460''>and</span> <span m=''2622590''>c.</span>
  <span m=''2624700''>And</span> <span m=''2624950''>this</span> <span m=''2626390''>segment</span>
  <span m=''2626770''>we</span> <span m=''2626860''>know will</span> <span m=''2627140''>map</span>
  <span m=''2627390''>right</span> <span m=''2627640''>along</span> <span m=''2627970''>the</span>
  <span m=''2628030''>floor</span> <span m=''2629670''>to</span> <span m=''2629830''>make</span>
  <span m=''2630150''>up</span> <span m=''2630390''>that</span> <span m=''2631550''>path,</span>
  <span m=''2632660''>that</span> <span m=''2632850''>active</span> <span m=''2633150''>path</span>
  <span m=''2633880''>in</span> <span m=''2634030''>the</span> <span m=''2634110''>tree.</span>
  <span m=''2636430''>Like</span> <span m=''2636630''>I</span> <span m=''2636670''>said,</span>
  <span m=''2637050''>we''re</span> <span m=''2637190''>going</span> <span m=''2637280''>to</span>
  <span m=''2637340''>follow</span> <span m=''2637660''>along</span> <span m=''2638850''>angular</span>
  <span m=''2639240''>bisectors.</span> </p><p><span m=''2645260''>You</span> <span
  m=''2645430''>may</span> <span m=''2645560''>know</span> <span m=''2646410''>the</span>
  <span m=''2646750''>angular</span> <span m=''2647070''>bisectors</span> <span m=''2648293''>of</span>
  <span m=''2648706''>a</span> <span m=''2649120''>triangle</span> <span m=''2649560''>meet
  at</span> <span m=''2649870''>a</span> <span m=''2649920''>single</span> <span m=''2650210''>point.</span>
  <span m=''2652750''>And</span> <span m=''2653550''>then,</span> <span m=''2653720''>we''re</span>
  <span m=''2653820''>going</span> <span m=''2653940''>to</span> <span m=''2654010''>make</span>
  <span m=''2654240''>some</span> <span m=''2654640''>perpendicular</span> <span m=''2655200''>folds</span>
  <span m=''2667200''>like</span> <span m=''2667410''>that.</span> <span m=''2670990''>Where</span>
  <span m=''2671220''>the</span> <span m=''2671390''>perpendicular</span> <span m=''2672010''>folds</span>
  <span m=''2672310''>go,</span> <span m=''2673280''>well,</span> <span m=''2673420''>they</span>
  <span m=''2673550''>go</span> <span m=''2673840''>whenever</span> <span m=''2674230''>there''s</span>
  <span m=''2676838''>a</span> <span m=''2677320''>shadow</span> <span m=''2678140''>vertex</span>
  <span m=''2679100''>along</span> <span m=''2679470''>this</span> <span m=''2679640''>segment.</span>
  </p><p><span m=''2680680''>Remember</span> <span m=''2681390''>this</span> <span
  m=''2681820''>edge,</span> <span m=''2683020''>b c</span> <span m=''2684330''>corresponds</span>
  <span m=''2684920''>to</span> <span m=''2685020''>some</span> <span m=''2685360''>path</span>
  <span m=''2686290''>between</span> <span m=''2686550''>b</span> <span m=''2686880''>and</span>
  <span m=''2687130''>c</span> <span m=''2687930''>in</span> <span m=''2688140''>the</span>
  <span m=''2688230''>tree</span> <span m=''2689440''>which</span> <span m=''2689620''>looks</span>
  <span m=''2689840''>like</span> <span m=''2690070''>whatever.</span> <span m=''2692170''>And</span>
  <span m=''2692340''>so</span> <span m=''2692450''>for</span> <span m=''2692600''>each</span>
  <span m=''2692830''>of</span> <span m=''2692920''>these</span> <span m=''2693130''>branching</span>
  <span m=''2693550''>points</span> <span m=''2693810''>that</span> <span m=''2693900''>we</span>
  <span m=''2694030''>visit</span> <span m=''2694730''>along</span> <span m=''2695230''>that,</span>
  <span m=''2695510''>we</span> <span m=''2695660''>can</span> <span m=''2695780''>just</span>
  <span m=''2695950''>measure.</span> <span m=''2696810''>As</span> <span m=''2696970''>we</span>
  <span m=''2697070''>move</span> <span m=''2697240''>along</span> <span m=''2697490''>here,</span>
  <span m=''2697790''>we</span> <span m=''2697880''>get</span> <span m=''2698060''>to</span>
  <span m=''2698150''>some</span> <span m=''2698310''>vertex</span> <span m=''2698750''>then</span>
  <span m=''2698980''>another</span> <span m=''2699140''>vertex then</span> <span
  m=''2699560''>another</span> <span m=''2699920''>vertex</span> <span m=''2700320''>then</span>
  <span m=''2701020''>c,</span> <span m=''2701280''>except I did</span> <span m=''2701680''>it</span>
  <span m=''2701830''>backwards.</span> </p><p><span m=''2704630''>And</span> <span
  m=''2704800''>so</span> <span m=''2704990''>for</span> <span m=''2705260''>each</span>
  <span m=''2705530''>of</span> <span m=''2705620''>these</span> <span m=''2705880''>guys,</span>
  <span m=''2706780''>I</span> <span m=''2706890''>know</span> <span m=''2707100''>that</span>
  <span m=''2707250''>I</span> <span m=''2707330''>need</span> <span m=''2707570''>to</span>
  <span m=''2707690''>be</span> <span m=''2707900''>able</span> <span m=''2708080''>to</span>
  <span m=''2708200''>articulate</span> <span m=''2708790''>there. I</span> <span
  m=''2708950''>need</span> <span m=''2709170''>a</span> <span m=''2709190''>hinge</span>
  <span m=''2709510''>crease.</span> <span m=''2710510''>And</span> <span m=''2710670''>so</span>
  <span m=''2710750''>I</span> <span m=''2710820''>just</span> <span m=''2710980''>put</span>
  <span m=''2711120''>in</span> <span m=''2711230''>a</span> <span m=''2711260''>hinge</span>
  <span m=''2711500''>grace</span> <span m=''2712740''>perpendicular</span> <span
  m=''2713480''>to</span> <span m=''2713600''>the</span> <span m=''2713710''>floor,</span>
  <span m=''2714390''>essentially,</span> <span m=''2714800''>because</span> <span
  m=''2714990''>we</span> <span m=''2715100''>know</span> <span m=''2715240''>this</span>
  <span m=''2715440''>is</span> <span m=''2715540''>mapping</span> <span m=''2715870''>to</span>
  <span m=''2715960''>the</span> <span m=''2716060''>floor.</span> </p><p><span m=''2717370''>And</span>
  <span m=''2717780''>conveniently,</span> <span m=''2718440''>those</span> <span
  m=''2718690''>will all</span> <span m=''2719120''>line</span> <span m=''2719350''>up.</span>
  <span m=''2719560''>So</span> <span m=''2719740''>if</span> <span m=''2719840''>I</span>
  <span m=''2719900''>have some</span> <span m=''2720140''>vertex</span> <span m=''2720720''>here--</span>
  <span m=''2720910''>let''s</span> <span m=''2721080''>call</span> <span m=''2721290''>it</span>
  <span m=''2721900''>d.</span> <span m=''2722730''>--d</span> <span m=''2723560''>will</span>
  <span m=''2723680''>be</span> <span m=''2723850''>here.</span> <span m=''2724150''>But</span>
  <span m=''2724300''>d</span> <span m=''2724440''>will</span> <span m=''2724580''>also</span>
  <span m=''2724960''>be</span> <span m=''2725150''>here.</span> <span m=''2725900''>Because</span>
  <span m=''2726060''>if</span> <span m=''2726210''>I</span> <span m=''2726270''>follow</span>
  <span m=''2726590''>the</span> <span m=''2726680''>path</span> <span m=''2726950''>from</span>
  <span m=''2727090''>b</span> <span m=''2727240''>to</span> <span m=''2727370''>a,</span>
  <span m=''2727720''>a is</span> <span m=''2728070''>some</span> <span m=''2728240''>other</span>
  <span m=''2728430''>guy,</span> <span m=''2728670''>maybe</span> <span m=''2728930''>this</span>
  <span m=''2729120''>one,</span> <span m=''2730580''>I</span> <span m=''2730730''>also</span>
  <span m=''2730980''>have</span> <span m=''2731110''>to</span> <span m=''2731200''>go</span>
  <span m=''2731330''>through d.</span> <span m=''2732960''>And</span> <span m=''2733170''>so</span>
  <span m=''2733280''>these</span> <span m=''2733480''>things</span> <span m=''2733680''>will</span>
  <span m=''2733810''>conveniently</span> <span m=''2734400''>line</span> <span m=''2734740''>up</span>
  <span m=''2734910''>perfectly.</span> <span m=''2735480''>I''m</span> <span m=''2735750''>not</span>
  <span m=''2735940''>going</span> <span m=''2736050''>to</span> <span m=''2736120''>prove</span>
  <span m=''2736350''>that</span> <span m=''2736570''>again.</span> <span m=''2736880''>But</span>
  <span m=''2737040''>it''s</span> <span m=''2737180''>true.</span> </p><p><span m=''2739420''>And</span>
  <span m=''2739610''>you</span> <span m=''2739700''>just</span> <span m=''2739920''>get</span>
  <span m=''2740070''>this</span> <span m=''2740250''>really</span> <span m=''2740560''>nice</span>
  <span m=''2740970''>simple</span> <span m=''2741460''>to</span> <span m=''2741540''>fold</span>
  <span m=''2742350''>thing.</span> <span m=''2745600''>Shoot,</span> <span m=''2745800''>I''ll</span>
  <span m=''2745920''>fold</span> <span m=''2746190''>one</span> <span m=''2746370''>if</span>
  <span m=''2746470''>you</span> <span m=''2746550''>haven''t.</span> <span m=''2746920''>This</span>
  <span m=''2747090''>is</span> <span m=''2747330''>a</span> <span m=''2747410''>standard</span>
  <span m=''2747790''>rabbit</span> <span m=''2748100''>ear</span> <span m=''2748710''>molecule</span>
  <span m=''2749320''>in</span> <span m=''2750140''>making</span> <span m=''2750500''>origami.</span>
  <span m=''2750960''>You have a</span> <span m=''2751020''>little</span> <span m=''2751260''>triangle.</span>
  <span m=''2751670''>You</span> <span m=''2751770''>want</span> <span m=''2751870''>to</span>
  <span m=''2751910''>make</span> <span m=''2752080''>it</span> <span m=''2752140''>an</span>
  <span m=''2752240''>ear.</span> <span m=''2753080''>You</span> <span m=''2753210''>squeeze</span>
  <span m=''2753670''>along</span> <span m=''2754020''>the</span> <span m=''2754270''>angular</span>
  <span m=''2754580''>bisectors,</span> <span m=''2755260''>and</span> <span m=''2755360''>it</span>
  <span m=''2755420''>makes</span> <span m=''2755640''>a</span> <span m=''2755690''>cute</span>
  <span m=''2755920''>rabbit</span> <span m=''2756420''>ear.</span> </p><p><span m=''2758150''>And</span>
  <span m=''2758360''>you</span> <span m=''2758540''>can</span> <span m=''2758680''>see</span>
  <span m=''2758920''>it</span> <span m=''2759250''>also,</span> <span m=''2759650''>the</span>
  <span m=''2759770''>crease</span> <span m=''2759980''>pattern,</span> <span m=''2760310''>in</span>
  <span m=''2760410''>here</span> <span m=''2761760''>like</span> <span m=''2763040''>in</span>
  <span m=''2763330''>this</span> <span m=''2763660''>triangle</span> <span m=''2764410''>in</span>
  <span m=''2764710''>the</span> <span m=''2764910''>upper</span> <span m=''2765160''>right.</span>
  <span m=''2765980''>You''ve</span> <span m=''2766120''>got</span> <span m=''2766310''>the</span>
  <span m=''2766430''>red</span> <span m=''2766740''>lines</span> <span m=''2767090''>which</span>
  <span m=''2767260''>are</span> <span m=''2767310''>the</span> <span m=''2767410''>angular</span>
  <span m=''2767730''>bisectors.</span> <span m=''2768940''>And</span> <span m=''2769110''>then,</span>
  <span m=''2769230''>you''ve</span> <span m=''2769390''>got</span> <span m=''2769740''>all</span>
  <span m=''2769930''>those</span> <span m=''2770150''>perpendicular</span> <span
  m=''2770750''>folds.</span> <span m=''2771470''>And</span> <span m=''2771670''>they</span>
  <span m=''2771790''>go</span> <span m=''2771980''>exactly</span> <span m=''2772930''>where</span>
  <span m=''2773060''>those</span> <span m=''2773280''>letters</span> <span m=''2773610''>go.</span>
  <span m=''2774680''>And</span> <span m=''2775810''>the</span> <span m=''2776270''>triangle</span>
  <span m=''2776660''>at</span> <span m=''2776730''>the</span> <span m=''2776830''>top</span>
  <span m=''2777150''>is</span> <span m=''2777300''>similar.</span> </p><p><span m=''2778430''>It''s</span>
  <span m=''2778820''>a</span> <span m=''2778870''>little</span> <span m=''2779090''>different</span>
  <span m=''2779440''>because</span> <span m=''2780170''>the</span> <span m=''2780950''>very</span>
  <span m=''2781200''>top</span> <span m=''2781620''>edge</span> <span m=''2781840''>of</span>
  <span m=''2781900''>the</span> <span m=''2781990''>paper</span> <span m=''2782280''>is</span>
  <span m=''2782360''>not</span> <span m=''2782560''>actually</span> <span m=''2782820''>active.</span>
  <span m=''2783550''>So</span> <span m=''2783760''>there''s</span> <span m=''2783970''>really</span>
  <span m=''2784180''>a</span> <span m=''2784230''>special</span> <span m=''2784580''>case</span>
  <span m=''2784870''>there.</span> <span m=''2787030''>Upper right</span> <span m=''2787480''>is</span>
  <span m=''2787600''>also</span> <span m=''2787860''>not</span> <span m=''2788030''>active.</span>
  <span m=''2788410''>Oh,</span> <span m=''2788760''>that''s</span> <span m=''2789200''>annoying.</span>
  <span m=''2790460''>Yeah.</span> <span m=''2793240''>There''s</span> <span m=''2793450''>a</span>
  <span m=''2793500''>little</span> <span m=''2793730''>bit</span> <span m=''2793880''>of</span>
  <span m=''2793970''>extra</span> <span m=''2794250''>stuff</span> <span m=''2794470''>that</span>
  <span m=''2794570''>happens</span> <span m=''2794900''>at</span> <span m=''2795000''>the</span>
  <span m=''2795080''>boundary</span> <span m=''2795390''>of</span> <span m=''2795440''>the</span>
  <span m=''2795520''>paper</span> <span m=''2795850''>where you</span> <span m=''2796000''>don''t</span>
  <span m=''2796150''>have</span> <span m=''2796320''>active</span> <span m=''2796590''>paths.</span>
  <span m=''2797450''>But</span> <span m=''2797620''>it''s,</span> <span m=''2798450''>as</span>
  <span m=''2798570''>you</span> <span m=''2798690''>can</span> <span m=''2798800''>see</span>
  <span m=''2798950''>from</span> <span m=''2799080''>the</span> <span m=''2799160''>crease</span>
  <span m=''2799360''>pattern,</span> <span m=''2799590''>it''s</span> <span m=''2799710''>basically</span>
  <span m=''2800110''>the</span> <span m=''2800200''>same.</span> </p><p><span m=''2801770''>In</span>
  <span m=''2801880''>fact,</span> <span m=''2804140''>I</span> <span m=''2804240''>could</span>
  <span m=''2804390''>call</span> <span m=''2804590''>it</span> <span m=''2804670''>the</span>
  <span m=''2804760''>same.</span> <span m=''2806200''>It''s</span> <span m=''2806380''>a</span>
  <span m=''2806420''>little</span> <span m=''2806640''>bit</span> <span m=''2807300''>less</span>
  <span m=''2807510''>pretty</span> <span m=''2807730''>because</span> <span m=''2807870''>this</span>
  <span m=''2808020''>is</span> <span m=''2808130''>not</span> <span m=''2808320''>green.</span>
  <span m=''2808595''>And so</span> <span m=''2808870''>you</span> <span m=''2808980''>don''t</span>
  <span m=''2809160''>actually</span> <span m=''2809420''>know</span> <span m=''2809610''>that</span>
  <span m=''2809750''>c</span> <span m=''2809930''>is</span> <span m=''2810070''>here.</span>
  <span m=''2810300''>And you</span> <span m=''2810450''>don''t</span> <span m=''2810630''>know</span>
  <span m=''2810780''>that b</span> <span m=''2810890''>is</span> <span m=''2811180''>there.</span>
  <span m=''2812030''>But</span> <span m=''2812670''>you</span> <span m=''2812820''>know</span>
  <span m=''2813110''>about</span> <span m=''2813630''>all</span> <span m=''2813890''>the</span>
  <span m=''2814010''>other</span> <span m=''2814240''>edges.</span> <span m=''2814620''>There''s</span>
  <span m=''2814710''>just</span> <span m=''2814900''>one</span> <span m=''2815070''>edge</span>
  <span m=''2815250''>you</span> <span m=''2815330''>might</span> <span m=''2815500''>not</span>
  <span m=''2815680''>know</span> <span m=''2815840''>about.</span> <span m=''2816500''>And</span>
  <span m=''2816620''>so</span> <span m=''2816700''>you</span> <span m=''2816780''>can</span>
  <span m=''2816910''>figure</span> <span m=''2817190''>out</span> <span m=''2817250''>what</span>
  <span m=''2817380''>the</span> <span m=''2817480''>right</span> <span m=''2817660''>edge</span>
  <span m=''2817890''>is</span> <span m=''2818070''>based</span> <span m=''2818330''>on</span>
  <span m=''2818420''>the</span> <span m=''2818540''>other</span> <span m=''2819460''>edges</span>
  <span m=''2819740''>of</span> <span m=''2819790''>the</span> <span m=''2819870''>triangle,</span>
  <span m=''2820125''>the</span> <span m=''2820380''>other</span> <span m=''2820600''>two</span>
  <span m=''2820760''>edges.</span> </p><p><span m=''2824210''>That''s</span> <span
  m=''2824420''>just</span> <span m=''2824620''>a</span> <span m=''2824670''>feature.</span>
  <span m=''2825190''>You</span> <span m=''2825330''>can</span> <span m=''2825450''>triangulate</span>
  <span m=''2825890''>everything</span> <span m=''2826320''>except</span> <span m=''2826840''>the</span>
  <span m=''2828480''>boundary.</span> <span m=''2829000''>You</span> <span m=''2829100''>may</span>
  <span m=''2829200''>not</span> <span m=''2829240''>be</span> <span m=''2829320''>able</span>
  <span m=''2829460''>to</span> <span m=''2829530''>get</span> <span m=''2829660''>active</span>
  <span m=''2829940''>paths</span> <span m=''2831020''>in</span> <span m=''2831140''>this</span>
  <span m=''2831310''>step.</span> <span m=''2836070''>That</span> <span m=''2836260''>kind</span>
  <span m=''2836580''>of</span> <span m=''2837330''>does</span> <span m=''2837540''>the</span>
  <span m=''2837600''>tree</span> <span m=''2837800''>method</span> <span m=''2838300''>in</span>
  <span m=''2838630''>a</span> <span m=''2839240''>super</span> <span m=''2839660''>abbreviated</span>
  <span m=''2840180''>version.</span> </p><p><span m=''2843980''>I</span> <span m=''2844130''>showed</span>
  <span m=''2844410''>you a</span> <span m=''2844550''>demo</span> <span m=''2844860''>last</span>
  <span m=''2845160''>time,</span> <span m=''2845470''>just</span> <span m=''2845780''>in</span>
  <span m=''2846240''>case</span> <span m=''2846470''>you</span> <span m=''2846560''>forgot.</span>
  <span m=''2847930''>You</span> <span m=''2848110''>draw</span> <span m=''2848570''>your</span>
  <span m=''2848750''>favorite</span> <span m=''2849160''>tree.</span> <span m=''2850310''>See</span>
  <span m=''2850460''>if</span> <span m=''2850550''>I</span> <span m=''2850630''>can
  get it</span> <span m=''2850980''>to</span> <span m=''2851060''>do</span> <span
  m=''2851150''>the</span> <span m=''2851250''>same</span> <span m=''2851500''>one.</span>
  <span m=''2857360''>And</span> <span m=''2857990''>you</span> <span m=''2858880''>optimize,</span>
  <span m=''2860560''>generate</span> <span m=''2861010''>a crease</span> <span m=''2861250''>pattern.</span>
  <span m=''2861645''>Oh, it''s a</span> <span m=''2862040''>different</span> <span
  m=''2862330''>one.</span> <span m=''2863350''>Fun.</span> <span m=''2864150''>There
  it</span> <span m=''2864510''>is.</span> <span m=''2866930''>And</span> <span m=''2867220''>here,</span>
  <span m=''2867750''>TreeMaker</span> <span m=''2868280''>knows</span> <span m=''2868520''>how</span>
  <span m=''2868630''>to</span> <span m=''2868720''>draw</span> <span m=''2868910''>the</span>
  <span m=''2869040''>disks.</span> <span m=''2869580''>It</span> <span m=''2869710''>doesn''t</span>
  <span m=''2870020''>currently</span> <span m=''2870320''>know</span> <span m=''2870470''>how</span>
  <span m=''2870580''>to</span> <span m=''2870670''>draw</span> <span m=''2870820''>the</span>
  <span m=''2870940''>rivers</span> <span m=''2871300''>because</span> <span m=''2871490''>it''s</span>
  <span m=''2871670''>kind</span> <span m=''2871840''>of</span> <span m=''2871930''>tricky</span>
  <span m=''2872280''>to</span> <span m=''2872370''>make</span> <span m=''2872590''>a</span>
  <span m=''2872660''>snakey</span> <span m=''2873420''>path</span> <span m=''2874300''>in
  a</span> <span m=''2874540''>computer</span> <span m=''2874860''>program.</span>
  </p><p><span m=''2875790''>But</span> <span m=''2876130''>you</span> <span m=''2876320''>see</span>
  <span m=''2876690''>the</span> <span m=''2876810''>three</span> <span m=''2877030''>disks</span>
  <span m=''2877330''>down</span> <span m=''2877560''>here,</span> <span m=''2877850''>the</span>
  <span m=''2877950''>three</span> <span m=''2878140''>disks</span> <span m=''2878400''>up</span>
  <span m=''2878550''>there,</span> <span m=''2879380''>and</span> <span m=''2879900''>you</span>
  <span m=''2880020''>can</span> <span m=''2880150''>imagine</span> <span m=''2880660''>the</span>
  <span m=''2880760''>one</span> <span m=''2880980''>river</span> <span m=''2881290''>in</span>
  <span m=''2881370''>the</span> <span m=''2881450''>middle</span> <span m=''2881740''>representing</span>
  <span m=''2882820''>the</span> <span m=''2882940''>central</span> <span m=''2883850''>segment</span>
  <span m=''2884570''>of</span> <span m=''2884830''>your</span> <span m=''2886020''>tree.</span>
  <span m=''2887460''>And</span> <span m=''2887970''>one</span> <span m=''2888180''>of</span>
  <span m=''2888240''>the</span> <span m=''2888330''>problems</span> <span m=''2888680''>on</span>
  <span m=''2888740''>the</span> <span m=''2888810''>problems set,</span> <span m=''2889270''>problem</span>
  <span m=''2889490''>set</span> <span m=''2889650''>one</span> <span m=''2889800''>is</span>
  <span m=''2889890''>released,</span> <span m=''2890700''>is</span> <span m=''2890900''>to</span>
  <span m=''2891020''>just</span> <span m=''2891230''>make</span> <span m=''2891490''>something</span>
  <span m=''2892110''>using</span> <span m=''2892410''>TreeMaker.</span> </p><p><span
  m=''2892800''>I</span> <span m=''2892900''>would</span> <span m=''2893020''>encourage</span>
  <span m=''2893340''>you</span> <span m=''2893490''>to</span> <span m=''2893590''>start</span>
  <span m=''2893810''>simple</span> <span m=''2894310''>unless</span> <span m=''2894560''>you</span>
  <span m=''2894810''>know what</span> <span m=''2894900''>you''re</span> <span m=''2895010''>doing.</span>
  <span m=''2895420''>You</span> <span m=''2895830''>don''t</span> <span m=''2895970''>have</span>
  <span m=''2896090''>to</span> <span m=''2896180''>use</span> <span m=''2896280''>the</span>
  <span m=''2896360''>program.</span> <span m=''2896750''>You</span> <span m=''2896870''>could</span>
  <span m=''2896990''>do</span> <span m=''2897080''>it</span> <span m=''2897150''>by</span>
  <span m=''2897260''>hand,</span> <span m=''2897730''>placing</span> <span m=''2898060''>disks.</span>
  <span m=''2898380''>That''s</span> <span m=''2898630''>how</span> <span m=''2899350''>most</span>
  <span m=''2899580''>origamists</span> <span m=''2900100''>actually</span> <span
  m=''2900420''>do</span> <span m=''2900570''>it.</span> <span m=''2900760''>I''m</span>
  <span m=''2900880''>sure</span> <span m=''2901060''>Jason</span> <span m=''2901380''>will</span>
  <span m=''2901470''>do</span> <span m=''2901570''>it</span> <span m=''2901660''>that</span>
  <span m=''2901850''>way.</span> <span m=''2903850''>You</span> <span m=''2904050''>can</span>
  <span m=''2905210''>use</span> <span m=''2905400''>the</span> <span m=''2905490''>program,</span>
  <span m=''2906040''>print</span> <span m=''2906280''>out</span> <span m=''2906400''>a</span>
  <span m=''2906460''>crease</span> <span m=''2906700''>pattern,</span> <span m=''2907650''>see</span>
  <span m=''2907840''>what</span> <span m=''2907940''>it</span> <span m=''2908020''>looks</span>
  <span m=''2908220''>like.</span> </p><p><span m=''2911760''>Next</span> <span m=''2911990''>thing.</span>
  <span m=''2916320''>If</span> <span m=''2916970''>you</span> <span m=''2917090''>want</span>
  <span m=''2917250''>to</span> <span m=''2917320''>do</span> <span m=''2917430''>this</span>
  <span m=''2917620''>in</span> <span m=''2917720''>reality--</span> <span m=''2918200''>and</span>
  <span m=''2918390''>what</span> <span m=''2918560''>TreeMaker</span> <span m=''2919010''>is</span>
  <span m=''2919130''>doing</span> <span m=''2919360''>is</span> <span m=''2919480''>not</span>
  <span m=''2919820''>this</span> <span m=''2919960''>triangulation.</span> <span
  m=''2921100''>Doing</span> <span m=''2921290''>a</span> <span m=''2921330''>triangulation</span>
  <span m=''2921870''>is</span> <span m=''2921970''>a</span> <span m=''2922010''>bit</span>
  <span m=''2922130''>of</span> <span m=''2922220''>a</span> <span m=''2922290''>pain,</span>
  <span m=''2922670''>but</span> <span m=''2922700''>you</span> <span m=''2922820''>could</span>
  <span m=''2922940''>keep</span> <span m=''2923130''>modifying</span> <span m=''2923600''>your</span>
  <span m=''2923730''>tree</span> <span m=''2924490''>until</span> <span m=''2924750''>it</span>
  <span m=''2924800''>triangulates.</span> <span m=''2925390''>The</span> <span m=''2925510''>alternative</span>
  <span m=''2926430''>is</span> <span m=''2926600''>you</span> <span m=''2926690''>just</span>
  <span m=''2926910''>deal</span> <span m=''2927170''>with</span> <span m=''2927330''>polygons</span>
  <span m=''2927860''>that</span> <span m=''2927960''>are</span> <span m=''2928030''>bigger</span>
  <span m=''2928270''>than</span> <span m=''2928430''>triangles.</span> </p><p><span
  m=''2929670''>And</span> <span m=''2929880''>there''s</span> <span m=''2930040''>this</span>
  <span m=''2930190''>thing</span> <span m=''2930400''>called</span> <span m=''2930720''>the</span>
  <span m=''2930800''>universal</span> <span m=''2931250''>molecule</span> <span m=''2931820''>by
  Robert</span> <span m=''2932250''>Lang.</span> <span m=''2932980''>Here</span> <span
  m=''2933200''>it</span> <span m=''2933260''>is</span> <span m=''2933460''>for</span>
  <span m=''2934200''>a</span> <span m=''2934320''>quadrilateral.</span> <span m=''2935610''>And</span>
  <span m=''2935870''>it</span> <span m=''2936270''>makes</span> <span m=''2936620''>it--</span>
  <span m=''2936850''>this</span> <span m=''2937110''>works</span> <span m=''2937380''>for</span>
  <span m=''2937540''>any</span> <span m=''2937850''>convex</span> <span m=''2938960''>polygon.</span>
  <span m=''2941070''>Now</span> <span m=''2941260''>sometimes,</span> <span m=''2941840''>you''re</span>
  <span m=''2941950''>active</span> <span m=''2942200''>paths</span> <span m=''2942460''>don''t</span>
  <span m=''2942610''>decompose</span> <span m=''2943430''>your</span> <span m=''2943890''>shape</span>
  <span m=''2944220''>into</span> <span m=''2944470''>convex</span> <span m=''2944830''>polygons.</span>
  <span m=''2945360''>And</span> <span m=''2945420''>this</span> <span m=''2945510''>still</span>
  <span m=''2945810''>doesn''t</span> <span m=''2946050''>work.</span> <span m=''2946710''>You</span>
  <span m=''2946820''>still</span> <span m=''2947110''>have</span> <span m=''2947270''>to</span>
  <span m=''2947380''>do</span> <span m=''2947620''>something</span> <span m=''2948140''>here.</span>
  <span m=''2948370''>You</span> <span m=''2948480''>need</span> <span m=''2948690''>to</span>
  <span m=''2948870''>add</span> <span m=''2949130''>some</span> <span m=''2949280''>extra</span>
  <span m=''2949530''>leaf</span> <span m=''2949750''>edges</span> <span m=''2950080''>to</span>
  <span m=''2950190''>the</span> <span m=''2950300''>tree</span> <span m=''2951060''>to</span>
  <span m=''2951190''>just</span> <span m=''2951420''>fill</span> <span m=''2951650''>things</span>
  <span m=''2951910''>up.</span> </p><p><span m=''2953790''>But</span> <span m=''2954490''>you</span>
  <span m=''2954840''>don''t</span> <span m=''2955140''>have</span> <span m=''2955310''>to</span>
  <span m=''2955430''>stop.</span> <span m=''2955910''>You</span> <span m=''2956040''>have</span>
  <span m=''2956210''>to</span> <span m=''2956280''>go</span> <span m=''2956400''>all</span>
  <span m=''2956630''>the</span> <span m=''2956710''>way</span> <span m=''2956840''>to</span>
  <span m=''2956930''>the</span> <span m=''2957040''>point</span> <span m=''2957240''>of</span>
  <span m=''2957320''>triangulation.</span> <span m=''2958440''>You</span> <span m=''2958540''>can</span>
  <span m=''2958650''>stop</span> <span m=''2958950''>at</span> <span m=''2959030''>the</span>
  <span m=''2959120''>point</span> <span m=''2959430''>which</span> <span m=''2959680''>happens</span>
  <span m=''2960000''>most</span> <span m=''2960210''>the</span> <span m=''2960310''>time</span>
  <span m=''2960690''>when</span> <span m=''2961370''>all</span> <span m=''2961610''>of</span>
  <span m=''2961740''>the</span> <span m=''2962000''>faces</span> <span m=''2962380''>are</span>
  <span m=''2962460''>convex.</span> <span m=''2963150''>And</span> <span m=''2963320''>then,</span>
  <span m=''2963450''>it''s</span> <span m=''2963610''>a</span> <span m=''2963680''>slightly</span>
  <span m=''2964080''>more</span> <span m=''2964320''>general</span> <span m=''2965330''>picture</span>
  <span m=''2966170''>what</span> <span m=''2966340''>happens.</span> <span m=''2967440''>Intuitively,</span>
  <span m=''2968030''>what</span> <span m=''2968200''>you</span> <span m=''2968290''>want</span>
  <span m=''2968470''>to</span> <span m=''2968550''>do</span> <span m=''2968730''>is,</span>
  <span m=''2969060''>this</span> <span m=''2969310''>is</span> <span m=''2969450''>the</span>
  <span m=''2969550''>tree</span> <span m=''2969810''>you</span> <span m=''2970260''>want</span>
  <span m=''2970640''>to</span> <span m=''2970760''>make</span> <span m=''2971820''>among</span>
  <span m=''2972250''>those</span> <span m=''2972590''>leaves.</span> </p><p><span
  m=''2973010''>All</span> <span m=''2973210''>the</span> <span m=''2973490''>boundary</span>
  <span m=''2973860''>edges</span> <span m=''2974130''>here</span> <span m=''2974690''>are</span>
  <span m=''2974880''>active paths.</span> <span m=''2975305''>You have</span> <span
  m=''2975730''>g d</span> <span m=''2976203''>h a.</span> <span m=''2977510''>Those</span>
  <span m=''2977710''>are</span> <span m=''2977780''>active</span> <span m=''2978050''>paths,
  so</span> <span m=''2978540''>you</span> <span m=''2978680''>know</span> <span m=''2978960''>where</span>
  <span m=''2979160''>all</span> <span m=''2979450''>of</span> <span m=''2979560''>those</span>
  <span m=''2981530''>branching</span> <span m=''2981900''>points</span> <span m=''2982160''>are</span>
  <span m=''2982280''>in</span> <span m=''2982350''>the</span> <span m=''2982420''>middle.</span>
  <span m=''2983690''>You''d</span> <span m=''2983850''>like</span> <span m=''2984140''>to</span>
  <span m=''2984230''>build</span> <span m=''2984490''>that.</span> <span m=''2984720''>And</span>
  <span m=''2984870''>so what</span> <span m=''2985000''>we''re</span> <span m=''2985230''>going</span>
  <span m=''2985330''>to</span> <span m=''2985430''>do</span> <span m=''2985590''>is</span>
  <span m=''2985710''>build</span> <span m=''2985990''>it</span> <span m=''2986200''>bottom</span>
  <span m=''2986570''>up</span> <span m=''2987460''>in</span> <span m=''2987630''>the</span>
  <span m=''2987850''>literal</span> <span m=''2988240''>sense</span> <span m=''2988740''>from
  z</span> <span m=''2989070''>equals</span> <span m=''2989400''>zero,</span> <span
  m=''2989960''>increasing</span> <span m=''2990550''>z.</span> </p><p><span m=''2992050''>And</span>
  <span m=''2992400''>what</span> <span m=''2992590''>that</span> <span m=''2992760''>corresponds</span>
  <span m=''2993350''>to</span> <span m=''2993440''>in</span> <span m=''2993540''>this</span>
  <span m=''2993720''>picture</span> <span m=''2994650''>is</span> <span m=''2994950''>shrinking</span>
  <span m=''2995890''>or</span> <span m=''2996070''>offsetting</span> <span m=''2996620''>these</span>
  <span m=''2996870''>edges</span> <span m=''2997270''>inward.</span> <span m=''2999580''>So</span>
  <span m=''2999720''>you</span> <span m=''3000210''>offset</span> <span m=''3000610''>these</span>
  <span m=''3000800''>all</span> <span m=''3000960''>by</span> <span m=''3001100''>the</span>
  <span m=''3001200''>same</span> <span m=''3001460''>amount.</span> <span m=''3001790''>That''s</span>
  <span m=''3002010''>like</span> <span m=''3002160''>traveling</span> <span m=''3002700''>up</span>
  <span m=''3003600''>over</span> <span m=''3003830''>here.</span> <span m=''3004190''>So</span>
  <span m=''3004230''>you see</span> <span m=''3004460''>the</span> <span m=''3004560''>red</span>
  <span m=''3004750''>lines</span> <span m=''3005050''>here</span> <span m=''3005210''>correspond</span>
  <span m=''3005680''>to</span> <span m=''3005760''>the</span> <span m=''3005890''>red</span>
  <span m=''3006230''>cross</span> <span m=''3006540''>sections.</span> <span m=''3007890''>So</span>
  <span m=''3007920''>I</span> <span m=''3008000''>just</span> <span m=''3008190''>see</span>
  <span m=''3008410''>what</span> <span m=''3008750''>happens</span> <span m=''3009160''>in</span>
  <span m=''3009270''>cross</span> <span m=''3009580''>section</span> <span m=''3009870''>is</span>
  <span m=''3010010''>I</span> <span m=''3010070''>shrink</span> <span m=''3010800''>things</span>
  <span m=''3011040''>in.</span> </p><p><span m=''3011460''>And</span> <span m=''3011590''>the</span>
  <span m=''3011660''>first</span> <span m=''3011990''>thing</span> <span m=''3012120''>that</span>
  <span m=''3012240''>happens</span> <span m=''3013480''>at</span> <span m=''3013690''>this</span>
  <span m=''3013850''>first</span> <span m=''3014130''>critical</span> <span m=''3014750''>red</span>
  <span m=''3015580''>drawing</span> <span m=''3016750''>is</span> <span m=''3016910''>that</span>
  <span m=''3017020''>the</span> <span m=''3017120''>path</span> <span m=''3017510''>from
  d</span> <span m=''3017740''>to</span> <span m=''3018160''>a</span> <span m=''3019030''>becomes</span>
  <span m=''3019490''>critical,</span> <span m=''3020890''>becomes</span> <span m=''3021380''>active.</span>
  <span m=''3022860''>Before</span> <span m=''3023280''>it was</span> <span m=''3023560''>inactive</span>
  <span m=''3024350''>that--</span> <span m=''3025380''>that</span> <span m=''3025470''>was</span>
  <span m=''3025720''>kind</span> <span m=''3025890''>of</span> <span m=''3025960''>annoying</span>
  <span m=''3026300''>for</span> <span m=''3026410''>me.</span> <span m=''3026530''>I</span>
  <span m=''3026590''>wanted it</span> <span m=''3027030''>to</span> <span m=''3027070''>be</span>
  <span m=''3027180''>triangulated,</span> <span m=''3027750''>but</span> <span m=''3027860''>it</span>
  <span m=''3027950''>wasn''t.</span> <span m=''3028680''>The</span> <span m=''3028780''>distance</span>
  <span m=''3029180''>from</span> <span m=''3029320''>a</span> <span m=''3029470''>to
  d</span> <span m=''3029580''>in</span> <span m=''3030180''>the</span> <span m=''3030260''>piece</span>
  <span m=''3030580''>of</span> <span m=''3030680''>paper</span> <span m=''3032070''>was</span>
  <span m=''3035850''>bigger</span> <span m=''3036230''>than</span> <span m=''3037440''>the</span>
  <span m=''3037590''>distance</span> <span m=''3038410''>between</span> <span m=''3038710''>the</span>
  <span m=''3038790''>leaves</span> <span m=''3039300''>in</span> <span m=''3039430''>the</span>
  <span m=''3039520''>tree.</span> </p><p><span m=''3040180''>I</span> <span m=''3040280''>wanted</span>
  <span m=''3040650''>them</span> <span m=''3040780''>to</span> <span m=''3040890''>be</span>
  <span m=''3041090''>equal.</span> <span m=''3041530''>Well,</span> <span m=''3041640''>it</span>
  <span m=''3041720''>turns</span> <span m=''3041960''>out,</span> <span m=''3042070''>if</span>
  <span m=''3042160''>you</span> <span m=''3042250''>shrink</span> <span m=''3042540''>this</span>
  <span m=''3042750''>thing,</span> <span m=''3042990''>eventually</span> <span m=''3043460''>they</span>
  <span m=''3043670''>might</span> <span m=''3043920''>become</span> <span m=''3044230''>equal.</span>
  <span m=''3044650''>And</span> <span m=''3044750''>that''s</span> <span m=''3044930''>what</span>
  <span m=''3045030''>happens.</span> <span m=''3045520''>And</span> <span m=''3045620''>that''s</span>
  <span m=''3045690''>what</span> <span m=''3045830''>TreeMaker</span> <span m=''3046670''>computes.</span>
  <span m=''3047670''>And</span> <span m=''3047750''>what</span> <span m=''3047870''>you</span>
  <span m=''3047930''>should</span> <span m=''3048100''>do</span> <span m=''3048260''>if</span>
  <span m=''3048350''>you''re</span> <span m=''3048480''>building</span> <span m=''3048770''>the</span>
  <span m=''3048840''>universal</span> <span m=''3049260''>molecule.</span> <span
  m=''3049800''>If</span> <span m=''3050170''>you</span> <span m=''3050270''>discover,</span>
  <span m=''3050780''>oh,</span> <span m=''3050950''>now</span> <span m=''3051360''>a</span>
  <span m=''3051785''>d</span> <span m=''3052470''>is</span> <span m=''3052790''>active,</span>
  <span m=''3053680''>now,</span> <span m=''3054140''>I</span> <span m=''3054260''>subdivide</span>
  <span m=''3054850''>into</span> <span m=''3055050''>two</span> <span m=''3055200''>triangles.</span>
  <span m=''3055730''>And</span> <span m=''3055870''>then,</span> <span m=''3055980''>I</span>
  <span m=''3056040''>do</span> <span m=''3056210''>the</span> <span m=''3056320''>thing</span>
  <span m=''3056620''>in</span> <span m=''3056730''>the</span> <span m=''3056830''>two</span>
  <span m=''3056960''>triangles.</span> </p><p><span m=''3057960''>And</span> <span
  m=''3058060''>generally,</span> <span m=''3058430''>you start</span> <span m=''3058660''>with</span>
  <span m=''3058760''>some</span> <span m=''3058920''>convex</span> <span m=''3059280''>polygon.</span>
  <span m=''3060180''>You</span> <span m=''3060260''>shrink</span> <span m=''3060570''>it.</span>
  <span m=''3060750''>At</span> <span m=''3060930''>some</span> <span m=''3061110''>point,</span>
  <span m=''3061430''>some</span> <span m=''3062110''>diagonal</span> <span m=''3062560''>might</span>
  <span m=''3062760''>become</span> <span m=''3063020''>active.</span> <span m=''3063370''>You</span>
  <span m=''3063470''>split it</span> <span m=''3063720''>into</span> <span m=''3063990''>two,</span>
  <span m=''3064650''>just</span> <span m=''3064830''>keep</span> <span m=''3065000''>going</span>
  <span m=''3065290''>in</span> <span m=''3065370''>the</span> <span m=''3065470''>two.</span>
  <span m=''3067240''>And</span> <span m=''3068840''>there''s</span> <span m=''3069010''>one</span>
  <span m=''3069230''>other</span> <span m=''3069430''>thing</span> <span m=''3069710''>which</span>
  <span m=''3069900''>can</span> <span m=''3070030''>happen,</span> <span m=''3070510''>which</span>
  <span m=''3070580''>is</span> <span m=''3070660''>what''s</span> <span m=''3070830''>happening</span>
  <span m=''3071180''>at</span> <span m=''3071270''>the</span> <span m=''3071390''>end</span>
  <span m=''3071550''>of</span> <span m=''3071650''>a</span> <span m=''3071690''>triangle.</span>
  <span m=''3072640''>You</span> <span m=''3072780''>shrink.</span> <span m=''3073600''>And</span>
  <span m=''3073780''>then,</span> <span m=''3073950''>it</span> <span m=''3074030''>could</span>
  <span m=''3074180''>be</span> <span m=''3074300''>two</span> <span m=''3074470''>vertices</span>
  <span m=''3075020''>actually</span> <span m=''3075320''>collide</span> <span m=''3075710''>with</span>
  <span m=''3075840''>each</span> <span m=''3076030''>other.</span> </p><p><span m=''3077040''>And</span>
  <span m=''3077200''>then,</span> <span m=''3077320''>you</span> <span m=''3077400''>just</span>
  <span m=''3077600''>think</span> <span m=''3077760''>of</span> <span m=''3077830''>them</span>
  <span m=''3077960''>as</span> <span m=''3078060''>one</span> <span m=''3078230''>vertex</span>
  <span m=''3078620''>and</span> <span m=''3078710''>keep</span> <span m=''3078960''>shrinking.</span>
  <span m=''3080360''>So</span> <span m=''3080510''>that''s</span> <span m=''3080830''>the</span>
  <span m=''3080900''>general</span> <span m=''3081250''>universal</span> <span m=''3081670''>molecule</span>
  <span m=''3082130''>construction.</span> <span m=''3083250''>You</span> <span m=''3083380''>see</span>
  <span m=''3084820''>in</span> <span m=''3084980''>a</span> <span m=''3085070''>sort</span>
  <span m=''3085300''>of--</span> <span m=''3085740''>these</span> <span m=''3086200''>are</span>
  <span m=''3086290''>the</span> <span m=''3086900''>cross</span> <span m=''3087150''>sections</span>
  <span m=''3087510''>from</span> <span m=''3087790''>above.</span> <span m=''3089380''>You</span>
  <span m=''3089540''>see</span> <span m=''3089870''>that</span> <span m=''3090420''>as</span>
  <span m=''3090600''>you</span> <span m=''3090700''>go</span> <span m=''3090870''>up,</span>
  <span m=''3091150''>things</span> <span m=''3091400''>are</span> <span m=''3091470''>getting</span>
  <span m=''3091670''>smaller.</span> <span m=''3092290''>That</span> <span m=''3092490''>is</span>
  <span m=''3092740''>one</span> <span m=''3093720''>of</span> <span m=''3093760''>the</span>
  <span m=''3093820''>statements</span> <span m=''3094190''>of</span> <span m=''3094290''>the</span>
  <span m=''3094650''>uniaxial</span> <span m=''3094990''>base</span> <span m=''3096020''>as</span>
  <span m=''3096090''>you</span> <span m=''3096190''>go</span> <span m=''3096330''>up.</span>
  <span m=''3096870''>Cross</span> <span m=''3097100''>sections</span> <span m=''3097440''>get</span>
  <span m=''3097590''>tinier.</span> </p><p><span m=''3100470''>And</span> <span m=''3100940''>that</span>
  <span m=''3101150''>gives</span> <span m=''3101290''>you</span> <span m=''3101380''>the</span>
  <span m=''3101490''>crease</span> <span m=''3101750''>pattern.</span> <span m=''3102050''>If</span>
  <span m=''3102150''>you</span> <span m=''3102260''>follow</span> <span m=''3102640''>along</span>
  <span m=''3103730''>where</span> <span m=''3103950''>the</span> <span m=''3104040''>vertices</span>
  <span m=''3104590''>go</span> <span m=''3104780''>during</span> <span m=''3105040''>this</span>
  <span m=''3105200''>process,</span> <span m=''3105700''>and</span> <span m=''3105760''>you</span>
  <span m=''3105860''>draw in</span> <span m=''3106290''>and</span> <span m=''3106440''>all</span>
  <span m=''3106590''>the</span> <span m=''3106660''>active</span> <span m=''3106970''>path</span>
  <span m=''3107300''>that</span> <span m=''3107360''>you</span> <span m=''3107460''>create</span>
  <span m=''3107690''>along</span> <span m=''3107950''>the</span> <span m=''3108020''>way,</span>
  <span m=''3108760''>that''s</span> <span m=''3108940''>your</span> <span m=''3109050''>crease</span>
  <span m=''3109270''>pattern.</span> <span m=''3114490''>So</span> <span m=''3114660''>that''s</span>
  <span m=''3114870''>how</span> <span m=''3114950''>you</span> <span m=''3115090''>do</span>
  <span m=''3115230''>it</span> <span m=''3115380''>more</span> <span m=''3115570''>practically</span>
  <span m=''3116250''>is</span> <span m=''3116630''>you</span> <span m=''3116760''>use</span>
  <span m=''3116930''>the</span> <span m=''3117010''>universal</span> <span m=''3117420''>molecule.</span>
  <span m=''3117870''>But</span> <span m=''3118130''>to</span> <span m=''3118200''>prove</span>
  <span m=''3118460''>it,</span> <span m=''3118660''>you</span> <span m=''3118800''>don''t</span>
  <span m=''3118980''>actually</span> <span m=''3119240''>need</span> <span m=''3119420''>that.</span>
  </p><p><span m=''3122560''>All</span> <span m=''3122660''>right.</span> <span m=''3123450''>I</span>
  <span m=''3123620''>have</span> <span m=''3124000''>now</span> <span m=''3124320''>some</span>
  <span m=''3127700''>more</span> <span m=''3128000''>real</span> <span m=''3128240''>examples</span>
  <span m=''3129720''>by</span> <span m=''3130240''>Robert</span> <span m=''3130550''>Lang
  and</span> <span m=''3130900''>by</span> <span m=''3131040''>Jason</span> <span
  m=''3131400''>Ku.</span> <span m=''3133030''>So</span> <span m=''3133210''>here</span>
  <span m=''3133510''>is</span> <span m=''3134550''>Roosevelt</span> <span m=''3135030''>elk.</span>
  <span m=''3135850''>And</span> <span m=''3137225''>Rob</span> <span m=''3137790''>is</span>
  <span m=''3137910''>all</span> <span m=''3138100''>about</span> <span m=''3138620''>getting</span>
  <span m=''3139940''>very</span> <span m=''3140630''>realistic</span> <span m=''3141520''>form.</span>
  <span m=''3141900''>So</span> <span m=''3142380''>all</span> <span m=''3142690''>of</span>
  <span m=''3142830''>the</span> <span m=''3143230''>branching</span> <span m=''3144130''>measurements</span>
  <span m=''3144640''>and--</span> <span m=''3144940''>I''m</span> <span m=''3145070''>sure</span>
  <span m=''3145310''>if</span> <span m=''3145400''>you</span> <span m=''3145640''>knew</span>
  <span m=''3145990''>a</span> <span m=''3146050''>lot</span> <span m=''3146280''>about</span>
  <span m=''3146500''>elks,</span> <span m=''3146880''>you</span> <span m=''3146990''>could</span>
  <span m=''3147130''>recognizes</span> <span m=''3147470''>this</span> <span m=''3147810''>a</span>
  <span m=''3147920''>Roosevelt</span> <span m=''3148380''>elk</span> <span m=''3148660''>not</span>
  <span m=''3148840''>some</span> <span m=''3149020''>other</span> <span m=''3149260''>elk.</span>
  </p><p><span m=''3150380''>And</span> <span m=''3150580''>you</span> <span m=''3150690''>can</span>
  <span m=''3150800''>achieve</span> <span m=''3151200''>that</span> <span m=''3151460''>level</span>
  <span m=''3151780''>of</span> <span m=''3151870''>detail</span> <span m=''3152360''>and</span>
  <span m=''3152450''>realism</span> <span m=''3153510''>using</span> <span m=''3153990''>the</span>
  <span m=''3154070''>tree</span> <span m=''3154260''>method</span> <span m=''3154570''>because</span>
  <span m=''3154740''>you</span> <span m=''3154880''>can</span> <span m=''3155000''>control</span>
  <span m=''3155540''>all</span> <span m=''3155830''>of</span> <span m=''3156000''>the</span>
  <span m=''3156270''>relative</span> <span m=''3156680''>lengths</span> <span m=''3157330''>of</span>
  <span m=''3157480''>those</span> <span m=''3157630''>segments</span> <span m=''3158080''>and</span>
  <span m=''3158180''>get</span> <span m=''3158700''>perfect</span> <span m=''3159060''>branching</span>
  <span m=''3159400''>structure</span> <span m=''3159820''>and</span> <span m=''3160120''>get</span>
  <span m=''3160330''>the</span> <span m=''3160430''>right</span> <span m=''3160630''>proportions</span>
  <span m=''3161120''>for</span> <span m=''3161190''>the</span> <span m=''3161280''>legs</span>
  <span m=''3161570''>and</span> <span m=''3161690''>tail and so</span> <span m=''3162150''>on.</span>
  </p><p><span m=''3163310''>And</span> <span m=''3163570''>you</span> <span m=''3163670''>can</span>
  <span m=''3163800''>see</span> <span m=''3164050''>here,</span> <span m=''3166000''>the--</span>
  <span m=''3166530''>and</span> <span m=''3166630''>you</span> <span m=''3166730''>can</span>
  <span m=''3167210''>go</span> <span m=''3167360''>to</span> <span m=''3167600''>Robert</span>
  <span m=''3167830''>Lang''s</span> <span m=''3168150''>webpage,</span> <span m=''3168680''>landorigami.com</span>
  <span m=''3169270''>and</span> <span m=''3170110''>print</span> <span m=''3170450''>this</span>
  <span m=''3170640''>out.</span> <span m=''3171190''>And</span> <span m=''3171810''>try</span>
  <span m=''3172050''>it</span> <span m=''3172130''>out</span> <span m=''3172320''>if</span>
  <span m=''3172450''>you</span> <span m=''3172570''>want.</span> <span m=''3172790''>This</span>
  <span m=''3172960''>will</span> <span m=''3173080''>fold</span> <span m=''3173440''>not</span>
  <span m=''3173670''>this</span> <span m=''3173970''>but</span> <span m=''3174220''>the</span>
  <span m=''3174310''>base</span> <span m=''3174710''>for</span> <span m=''3174870''>that</span>
  <span m=''3175120''>model.</span> <span m=''3176110''>And</span> <span m=''3176370''>you</span>
  <span m=''3176450''>could</span> <span m=''3176560''>see</span> <span m=''3176730''>the</span>
  <span m=''3176860''>disks.</span> <span m=''3177570''>And</span> <span m=''3177830''>you</span>
  <span m=''3177930''>can</span> <span m=''3178040''>see</span> <span m=''3178220''>some</span>
  <span m=''3178460''>approximation</span> <span m=''3179180''>of</span> <span m=''3179250''>the</span>
  <span m=''3179360''>rivers</span> <span m=''3179740''>here.</span> <span m=''3181220''>But</span>
  <span m=''3181380''>they''re</span> <span m=''3181490''>not</span> <span m=''3181680''>quite</span>
  <span m=''3182030''>drawn</span> <span m=''3182340''>in in</span> <span m=''3182530''>this</span>
  <span m=''3182750''>particular</span> <span m=''3183820''>diagram.</span> </p><p><span
  m=''3186220''>But</span> <span m=''3186430''>a</span> <span m=''3186510''>lot</span>
  <span m=''3186860''>of</span> <span m=''3187110''>detail.</span> <span m=''3187460''>And</span>
  <span m=''3187580''>if</span> <span m=''3187710''>you</span> <span m=''3187930''>look</span>
  <span m=''3188140''>carefully,</span> <span m=''3188560''>you</span> <span m=''3188670''>can</span>
  <span m=''3188800''>really</span> <span m=''3189010''>read</span> <span m=''3189240''>off</span>
  <span m=''3189430''>what</span> <span m=''3189620''>the</span> <span m=''3189700''>tree</span>
  <span m=''3190030''>is</span> <span m=''3190190''>here.</span> <span m=''3190360''>You</span>
  <span m=''3190510''>can</span> <span m=''3190640''>see</span> <span m=''3191190''>how</span>
  <span m=''3191390''>these</span> <span m=''3191570''>things</span> <span m=''3191760''>are</span>
  <span m=''3191850''>separated,</span> <span m=''3192500''>and</span> <span m=''3192650''>it</span>
  <span m=''3192700''>will</span> <span m=''3192850''>correspond</span> <span m=''3193370''>to</span>
  <span m=''3193430''>the</span> <span m=''3193530''>branching</span> <span m=''3193860''>structure</span>
  <span m=''3194290''>over</span> <span m=''3194410''>there.</span> <span m=''3196850''>Here''s</span>
  <span m=''3197170''>a</span> <span m=''3197260''>more</span> <span m=''3197480''>complicated</span>
  <span m=''3198080''>one.</span> <span m=''3199390''>Scorpion</span> <span m=''3200080''>varleg</span>
  <span m=''3202240''>which</span> <span m=''3202500''>you</span> <span m=''3202590''>can</span>
  <span m=''3202740''>also</span> <span m=''3203010''>fold</span> <span m=''3204020''>at</span>
  <span m=''3204200''>lifesize</span> <span m=''3205440''>if</span> <span m=''3205850''>you''re</span>
  <span m=''3206230''>really</span> <span m=''3206510''>crazy.</span> </p><p><span
  m=''3207450''>And</span> <span m=''3210690''>you</span> <span m=''3210840''>can</span>
  <span m=''3210970''>also</span> <span m=''3211190''>see</span> <span m=''3211380''>from</span>
  <span m=''3211520''>these</span> <span m=''3211680''>kinds</span> <span m=''3211860''>of</span>
  <span m=''3211920''>diagrams</span> <span m=''3212420''>that</span> <span m=''3213550''>paper</span>
  <span m=''3213940''>usage</span> <span m=''3214340''>is</span> <span m=''3214430''>super</span>
  <span m=''3214890''>efficient</span> <span m=''3215560''>in</span> <span m=''3215730''>these</span>
  <span m=''3215930''>designs.</span> <span m=''3216530''>And</span> <span m=''3216710''>presumably</span>
  <span m=''3217150''>that''s</span> <span m=''3217400''>how</span> <span m=''3218460''>Robert</span>
  <span m=''3218790''>design</span> <span m=''3219170''>them.</span> <span m=''3220200''>The</span>
  <span m=''3220500''>only</span> <span m=''3220860''>paper</span> <span m=''3221160''>we''re</span>
  <span m=''3221320''>wasting</span> <span m=''3221860''>in</span> <span m=''3221930''>some</span>
  <span m=''3222100''>sense</span> <span m=''3222340''>is</span> <span m=''3222730''>the</span>
  <span m=''3222820''>little</span> <span m=''3223060''>regions</span> <span m=''3223440''>between</span>
  <span m=''3224070''>the</span> <span m=''3224220''>disks</span> <span m=''3224640''>and</span>
  <span m=''3226710''>the</span> <span m=''3226790''>rivers</span> <span m=''3227910''>which</span>
  <span m=''3228100''>is</span> <span m=''3228220''>quite</span> <span m=''3228450''>small.</span>
  <span m=''3229490''>Most</span> <span m=''3229710''>of the</span> <span m=''3229810''>papers</span>
  <span m=''3230170''>getting</span> <span m=''3230420''>absorbed</span> <span m=''3230820''>into</span>
  <span m=''3231040''>the</span> <span m=''3231150''>flaps.</span> </p><p><span m=''3234570''>Here''s</span>
  <span m=''3235350''>one</span> <span m=''3235490''>of</span> <span m=''3235530''>the</span>
  <span m=''3235590''>first</span> <span m=''3235890''>models</span> <span m=''3236150''>by</span>
  <span m=''3236250''>Jason</span> <span m=''3236560''>Ku that</span> <span m=''3236880''>I</span>
  <span m=''3236950''>saw,</span> <span m=''3237810''>the</span> <span m=''3237930''>Nazgul</span>
  <span m=''3238640''>from</span> <span m=''3238970''><i>Lord</i></span> <span m=''3239130''><i>of</i></span>
  <span m=''3239180''><i>the</i></span> <span m=''3239260''><i>Rings</i>.</span> <span
  m=''3240380''>And</span> <span m=''3241660''>pretty</span> <span m=''3242150''>complicated.</span>
  <span m=''3242890''>So</span> <span m=''3243570''>here,</span> <span m=''3243750''>the</span>
  <span m=''3243870''>bold</span> <span m=''3244160''>lines</span> <span m=''3244590''>show</span>
  <span m=''3244820''>you</span> <span m=''3245420''>essentially</span> <span m=''3245760''>where</span>
  <span m=''3245910''>the</span> <span m=''3246040''>disks</span> <span m=''3246380''>and</span>
  <span m=''3246520''>the</span> <span m=''3246590''>rivers</span> <span m=''3246920''>are</span>
  <span m=''3247660''>that have</span> <span m=''3247740''>been--</span> </p><p><span
  m=''3247900''>AUDIENCE: Those are</span> <span m=''3248130''>actually the</span>
  <span m=''3248526''>hinge</span> <span m=''3248922''>creases.</span> </p><p><span
  m=''3249320''>PROFESSOR: Oh, those</span> <span m=''3249600''>are hinge</span> <span
  m=''3249890''>creases.</span> <span m=''3250610''>Yeah.</span> <span m=''3252200''>Good.</span>
  <span m=''3252820''>And</span> <span m=''3253030''>the</span> <span m=''3253190''>top</span>
  <span m=''3253450''>is the</span> <span m=''3253580''>actual</span> <span m=''3253940''>crease</span>
  <span m=''3254170''>pattern.</span> <span m=''3256150''>And</span> <span m=''3257020''>it''s</span>
  <span m=''3257160''>pretty</span> <span m=''3257400''>awesome.</span> <span m=''3257860''>You''ve</span>
  <span m=''3258020''>got</span> <span m=''3258170''>a</span> <span m=''3258210''>horse</span>
  <span m=''3258450''>and</span> <span m=''3258550''>rider</span> <span m=''3258890''>out</span>
  <span m=''3259000''>of</span> <span m=''3259090''>one</span> <span m=''3259610''>square</span>
  <span m=''3259910''>paper.</span> <span m=''3264110''>Here''s</span> <span m=''3264470''>a</span>
  <span m=''3264620''>shrimp.</span> <span m=''3266260''>He''s</span> <span m=''3266720''>super</span>
  <span m=''3267120''>complicated</span> <span m=''3267800''>and</span> <span m=''3267940''>super</span>
  <span m=''3268420''>realistic.</span> <span m=''3269440''>It</span> <span m=''3269620''>looks</span>
  <span m=''3269830''>very</span> <span m=''3270650''>shrimpy.</span> <span m=''3272010''>I</span>
  <span m=''3272170''>know some</span> <span m=''3272370''>people</span> <span m=''3272660''>who</span>
  <span m=''3273140''>are</span> <span m=''3273240''>freaked</span> <span m=''3273560''>out</span>
  <span m=''3273740''>by</span> <span m=''3273880''>shrimp.</span> <span m=''3274210''>And</span>
  <span m=''3274370''>so</span> <span m=''3274500''>this</span> <span m=''3274660''>should</span>
  <span m=''3275230''>really</span> <span m=''3275470''>elicit</span> <span m=''3275930''>that</span>
  <span m=''3276250''>similar</span> <span m=''3276600''>response.</span> </p><p><span
  m=''3277320''>Or</span> <span m=''3278400''>other</span> <span m=''3278610''>people</span>
  <span m=''3278900''>get</span> <span m=''3279060''>really</span> <span m=''3279260''>hungry</span>
  <span m=''3279580''>at</span> <span m=''3279670''>this</span> <span m=''3279830''>point,</span>
  <span m=''3280120''>I</span> <span m=''3280220''>guess.</span> <span m=''3282140''>But</span>
  <span m=''3282210''>you</span> <span m=''3282380''>could</span> <span m=''3282520''>see</span>
  <span m=''3282680''>the</span> <span m=''3282800''>tree</span> <span m=''3283070''>is</span>
  <span m=''3283440''>pretty</span> <span m=''3284740''>dense</span> <span m=''3285040''>here,</span>
  <span m=''3285180''>lots</span> <span m=''3285440''>of</span> <span m=''3285530''>little</span>
  <span m=''3285720''>features</span> <span m=''3287380''>getting</span> <span m=''3287660''>that</span>
  <span m=''3287840''>branching</span> <span m=''3288180''>right.</span> <span m=''3289980''>And</span>
  <span m=''3290450''>one</span> <span m=''3290920''>last</span> <span m=''3291220''>example</span>
  <span m=''3291690''>is</span> <span m=''3291760''>this</span> <span m=''3291910''>butterfly</span>
  <span m=''3292770''>which</span> <span m=''3292930''>is</span> <span m=''3293040''>pretty</span>
  <span m=''3294160''>awesome</span> <span m=''3294790''>in</span> <span m=''3295020''>its</span>
  <span m=''3295390''>realism.</span> <span m=''3296790''>And</span> <span m=''3297890''>I</span>
  <span m=''3297990''>guess</span> <span m=''3298330''>the</span> <span m=''3298450''>tree</span>
  <span m=''3298650''>is</span> <span m=''3298750''>a</span> <span m=''3298810''>lot</span>
  <span m=''3299060''>simpler</span> <span m=''3299370''>here.</span> <span m=''3300160''>But</span>
  <span m=''3300320''>there''s</span> <span m=''3301950''>a</span> <span m=''3302020''>lot</span>
  <span m=''3302170''>of</span> <span m=''3302260''>extra</span> <span m=''3302550''>creases</span>
  <span m=''3302960''>here.</span> <span m=''3303120''>You</span> <span m=''3303260''>see</span>
  <span m=''3303510''>just</span> <span m=''3303800''>for getting</span> <span m=''3304300''>the</span>
  <span m=''3304380''>flaps</span> <span m=''3305190''>nice</span> <span m=''3305390''>and</span>
  <span m=''3305440''>narrow.</span> </p><p><span m=''3307130''>So</span> <span m=''3308520''>in</span>
  <span m=''3308570''>general,</span> <span m=''3309520''>these</span> <span m=''3309650''>kinds</span>
  <span m=''3309930''>of</span> <span m=''3310230''>constructions</span> <span m=''3311740''>will</span>
  <span m=''3311880''>make</span> <span m=''3312150''>this</span> <span m=''3312590''>guy</span>
  <span m=''3312830''>rather</span> <span m=''3313150''>pointy</span> <span m=''3313560''>and</span>
  <span m=''3313690''>tall.</span> <span m=''3314590''>And</span> <span m=''3314900''>you</span>
  <span m=''3315020''>can</span> <span m=''3315140''>just</span> <span m=''3315710''>squash</span>
  <span m=''3316110''>it</span> <span m=''3316290''>back.</span> <span m=''3316540''>And</span>
  <span m=''3316720''>it''s</span> <span m=''3316870''>called</span> <span m=''3317030''>a</span>
  <span m=''3317090''>sync</span> <span m=''3317350''>fold</span> <span m=''3318090''>and</span>
  <span m=''3318250''>make</span> <span m=''3318430''>it</span> <span m=''3318710''>tinier</span>
  <span m=''3319670''>like--</span> <span m=''3321960''>you</span> <span m=''3322080''>have</span>
  <span m=''3322460''>something</span> <span m=''3322760''>like</span> <span m=''3322930''>this.</span>
  <span m=''3323180''>The</span> <span m=''3323310''>flaps</span> <span m=''3323700''>are</span>
  <span m=''3323880''>you</span> <span m=''3324000''>think are</span> <span m=''3324270''>too</span>
  <span m=''3324450''>tall.</span> <span m=''3325280''>You</span> <span m=''3325640''>just</span>
  <span m=''3328670''>fold</span> <span m=''3329040''>here.</span> <span m=''3330300''>Which,</span>
  <span m=''3330440''>if</span> <span m=''3330550''>you</span> <span m=''3330690''>look</span>
  <span m=''3330870''>at</span> <span m=''3330950''>the</span> <span m=''3331040''>crease</span>
  <span m=''3331300''>pattern,</span> <span m=''3332600''>makes</span> <span m=''3332990''>just</span>
  <span m=''3333170''>an</span> <span m=''3333270''>offset</span> <span m=''3333690''>version</span>
  <span m=''3334030''>of</span> <span m=''3334110''>the</span> <span m=''3334220''>original.</span>
  <span m=''3335840''>And</span> <span m=''3336030''>hey,</span> <span m=''3336170''>now</span>
  <span m=''3336340''>your</span> <span m=''3336470''>flaps</span> <span m=''3336830''>are</span>
  <span m=''3336980''>half</span> <span m=''3337180''>is</span> <span m=''3337460''>tall.</span>
  </p><p><span m=''3338050''>And</span> <span m=''3338240''>if</span> <span m=''3338350''>you''re</span>
  <span m=''3338600''>a</span> <span m=''3338980''>proper</span> <span m=''3339450''>origamist,</span>
  <span m=''3341140''>you--</span> <span m=''3344640''>I shouldn''t</span> <span m=''3345010''>do
  this</span> <span m=''3345390''>live.</span> <span m=''3350760''>You</span> <span
  m=''3350890''>change</span> <span m=''3351150''>the</span> <span m=''3351220''>mountain</span>
  <span m=''3351440''>valley</span> <span m=''3351710''>assignment</span> <span m=''3352060''>a</span>
  <span m=''3352110''>little</span> <span m=''3352300''>bit,</span> <span m=''3353400''>and</span>
  <span m=''3353980''>you</span> <span m=''3354140''>sync</span> <span m=''3354540''>everything</span>
  <span m=''3354960''>on</span> <span m=''3355050''>the</span> <span m=''3355180''>inside</span>
  <span m=''3355840''>instead</span> <span m=''3356210''>of</span> <span m=''3356560''>just</span>
  <span m=''3356800''>folding</span> <span m=''3356950''>it</span> <span m=''3357110''>over.</span>
  <span m=''3362728''>It''s not going</span> <span m=''3363206''>to look</span> <span
  m=''3363690''>super</span> <span m=''3364030''>pretty.</span> <span m=''3365370''>But</span>
  <span m=''3366210''>same</span> <span m=''3367010''>tree</span> <span m=''3367230''>structure,</span>
  <span m=''3368290''>just</span> <span m=''3368450''>the</span> <span m=''3368530''>flaps</span>
  <span m=''3368880''>are</span> <span m=''3368970''>half</span> <span m=''3369180''>as</span>
  <span m=''3369250''>tall.</span> </p><p><span m=''3371680''>So</span> <span m=''3371890''>that''s</span>
  <span m=''3372150''>all</span> <span m=''3372260''>this</span> <span m=''3372850''>pleating</span>
  <span m=''3373160''>here.</span> <span m=''3374740''>And</span> <span m=''3375040''>I</span>
  <span m=''3375110''>think</span> <span m=''3375330''>that''s</span> <span m=''3375570''>it</span>
  <span m=''3375720''>for</span> <span m=''3376190''>my</span> <span m=''3376510''>little</span>
  <span m=''3377700''>tour.</span> <span m=''3378310''>And</span> <span m=''3379370''>Jason</span>
  <span m=''3379750''>Ku</span> <span m=''3380010''>next.</span> <span m=''3381350''>Next</span>
  <span m=''3381690''>Monday</span> <span m=''3382230''>we''ll</span> <span m=''3382370''>be</span>
  <span m=''3382500''>talking</span> <span m=''3382870''>more</span> <span m=''3383220''>about</span>
  <span m=''3383610''>the</span> <span m=''3383740''>artistic</span> <span m=''3384190''>side,</span>
  <span m=''3384670''>history</span> <span m=''3385050''>of</span> <span m=''3385260''>origami</span>
  <span m=''3385490''>design,</span> <span m=''3386290''>and</span> <span m=''3387630''>what</span>
  <span m=''3387790''>it</span> <span m=''3387870''>takes</span> <span m=''3388040''>to</span>
  <span m=''3388140''>really</span> <span m=''3388320''>make</span> <span m=''3388620''>something</span>
  <span m=''3389300''>real</span> <span m=''3389970''>by</span> <span m=''3390110''>these</span>
  <span m=''3390760''>approaches.</span> <span m=''3391150''>That</span> <span m=''3391260''>should</span>
  <span m=''3391400''>be</span> <span m=''3391500''>lots</span> <span m=''3391710''>of</span>
  <span m=''3391790''>fun.</span> </p><p><span m=''3393690''>I</span> <span m=''3393810''>want</span>
  <span m=''3393970''>to</span> <span m=''3394010''>move</span> <span m=''3394250''>on</span>
  <span m=''3394520''>to</span> <span m=''3394690''>other</span> <span m=''3394890''>kinds</span>
  <span m=''3395140''>of</span> <span m=''3395250''>efficient</span> <span m=''3395570''>origami</span>
  <span m=''3396010''>design.</span> <span m=''3397380''>Less</span> <span m=''3398840''>directly</span>
  <span m=''3399390''>applicable</span> <span m=''3399970''>to</span> <span m=''3401460''>real</span>
  <span m=''3401760''>origami</span> <span m=''3402130''>design</span> <span m=''3403510''>so</span>
  <span m=''3403710''>to</span> <span m=''3403800''>speak,</span> <span m=''3404220''>at</span>
  <span m=''3404300''>least</span> <span m=''3404530''>currently.</span> <span m=''3406400''>But</span>
  <span m=''3406620''>mathematically</span> <span m=''3407430''>more</span> <span
  m=''3407680''>powerful.</span> <span m=''3408370''>Uniaxial</span> <span m=''3408830''>bases</span>
  <span m=''3409180''>are</span> <span m=''3409270''>nice,</span> <span m=''3409740''>but</span>
  <span m=''3410390''>it''s</span> <span m=''3410520''>not</span> <span m=''3410700''>everything</span>
  <span m=''3411150''>you</span> <span m=''3411270''>might</span> <span m=''3411470''>want</span>
  <span m=''3411610''>to</span> <span m=''3411660''>fold.</span> <span m=''3412840''>So</span>
  <span m=''3413040''>what</span> <span m=''3413190''>if</span> <span m=''3413320''>we</span>
  <span m=''3413390''>want</span> <span m=''3413580''>to</span> <span m=''3413620''>fold</span>
  <span m=''3416210''>other</span> <span m=''3416480''>stuff.</span> </p><p><span
  m=''3423180''>And</span> <span m=''3423720''>to</span> <span m=''3424350''>a</span>
  <span m=''3424460''>geometer,</span> <span m=''3425200''>most</span> <span m=''3425590''>natural</span>
  <span m=''3425950''>version</span> <span m=''3426290''>of</span> <span m=''3426450''>folding</span>
  <span m=''3427240''>other</span> <span m=''3427490''>stuff</span> <span m=''3427810''>or</span>
  <span m=''3427940''>folding</span> <span m=''3428250''>anything</span> <span m=''3428650''>is</span>
  <span m=''3428940''>a</span> <span m=''3429020''>polyhedron.</span> <span m=''3429740''>You</span>
  <span m=''3429860''>have</span> <span m=''3429990''>a</span> <span m=''3430040''>bunch</span>
  <span m=''3430320''>of</span> <span m=''3430830''>polygons,</span> <span m=''3431410''>flat</span>
  <span m=''3431770''>panels</span> <span m=''3432270''>in</span> <span m=''3432430''>3D,</span>
  <span m=''3433300''>somehow</span> <span m=''3433640''>joined</span> <span m=''3433890''>together</span>
  <span m=''3434280''>to</span> <span m=''3434350''>make</span> <span m=''3434530''>some</span>
  <span m=''3434720''>surface.</span> <span m=''3435570''>How do I</span> <span m=''3435840''>fold</span>
  <span m=''3436110''>that?</span> </p><p><span m=''3437130''>And</span> <span m=''3437320''>let''s</span>
  <span m=''3437490''>start</span> <span m=''3437760''>with</span> <span m=''3437910''>a</span>
  <span m=''3437980''>super</span> <span m=''3438510''>simple</span> <span m=''3438820''>example</span>
  <span m=''3439810''>which</span> <span m=''3440040''>is</span> <span m=''3440210''>I</span>
  <span m=''3440410''>want</span> <span m=''3440610''>to</span> <span m=''3440690''>fold</span>
  <span m=''3441160''>a</span> <span m=''3441260''>square</span> <span m=''3442620''>into</span>
  <span m=''3443560''>a</span> <span m=''3443650''>cube.</span> <span m=''3445600''>How</span>
  <span m=''3445860''>big</span> <span m=''3446660''>a</span> <span m=''3446730''>square</span>
  <span m=''3447010''>do</span> <span m=''3447090''>I</span> <span m=''3447170''>need</span>
  <span m=''3447490''>to</span> <span m=''3447560''>fold</span> <span m=''3448720''>a</span>
  <span m=''3448790''>unit</span> <span m=''3449050''>cube?</span> <span m=''3450590''>Or</span>
  <span m=''3451910''>how</span> <span m=''3452090''>big</span> <span m=''3452300''>cube</span>
  <span m=''3452650''>can I fold</span> <span m=''3453070''>for a unit</span> <span
  m=''3453460''>square?</span> <span m=''3453850''>Either</span> <span m=''3454315''>way.</span>
  <span m=''3456450''>And</span> <span m=''3458410''>I''m</span> <span m=''3458620''>going</span>
  <span m=''3458750''>to</span> <span m=''3458820''>make</span> <span m=''3459140''>it</span>
  <span m=''3460400''>a</span> <span m=''3460600''>one</span> <span m=''3462430''>by</span>
  <span m=''3462650''>one</span> <span m=''3463110''>square.</span> <span m=''3463700''>And</span>
  <span m=''3464125''>I''m</span> <span m=''3464550''>going</span> <span m=''3464790''>to</span>
  <span m=''3464840''>fold</span> <span m=''3465170''>it</span> <span m=''3465260''>into</span>
  <span m=''3467140''>a</span> <span m=''3467220''>cube</span> <span m=''3467680''>of</span>
  <span m=''3467800''>dimension</span> <span m=''3468320''>x.</span> </p><p><span
  m=''3471060''>And</span> <span m=''3471210''>I</span> <span m=''3471240''>want</span>
  <span m=''3471430''>to</span> <span m=''3471480''>know--</span> <span m=''3473070''>it
  looks</span> <span m=''3473280''>funny.</span> <span m=''3475160''>It''s</span>
  <span m=''3475390''>the</span> <span m=''3475560''>quintuple</span> <span m=''3476080''>x</span>
  <span m=''3476450''>cubed.</span> <span m=''3479460''>It''s</span> <span m=''3479640''>the</span>
  <span m=''3479780''>x-coordinate.</span> <span m=''3480670''>That''s</span> <span
  m=''3480960''>my</span> <span m=''3481090''>motivation.</span> <span m=''3486800''>So</span>
  <span m=''3487110''>we</span> <span m=''3487320''>talked--</span> <span m=''3488140''>one</span>
  <span m=''3488340''>thing</span> <span m=''3488480''>we</span> <span m=''3488590''>can</span>
  <span m=''3488710''>think</span> <span m=''3488910''>about</span> <span m=''3489660''>is</span>
  <span m=''3490240''>what</span> <span m=''3490530''>makes</span> <span m=''3490760''>the</span>
  <span m=''3490840''>corners</span> <span m=''3491270''>of</span> <span m=''3491370''>the</span>
  <span m=''3491450''>cubes</span> <span m=''3493330''>and</span> <span m=''3493520''>how</span>
  <span m=''3493790''>far</span> <span m=''3494060''>away</span> <span m=''3494250''>should</span>
  <span m=''3494460''>they</span> <span m=''3494580''>be.</span> </p><p><span m=''3495910''>So</span>
  <span m=''3496120''>if</span> <span m=''3496230''>I</span> <span m=''3496300''>want</span>
  <span m=''3496480''>to</span> <span m=''3496540''>fold</span> <span m=''3496810''>this</span>
  <span m=''3496990''>cube,</span> <span m=''3498220''>I</span> <span m=''3498330''>look</span>
  <span m=''3498570''>at,</span> <span m=''3498650''>let''s</span> <span m=''3498840''>say,</span>
  <span m=''3498940''>the</span> <span m=''3499200''>opposite</span> <span m=''3499680''>corners</span>
  <span m=''3500790''>of</span> <span m=''3500940''>the</span> <span m=''3501030''>cube.</span>
  <span m=''3502420''>They''re</span> <span m=''3502560''>pretty</span> <span m=''3502840''>far</span>
  <span m=''3503140''>away</span> <span m=''3503400''>on</span> <span m=''3503520''>the</span>
  <span m=''3503610''>cube.</span> <span m=''3504920''>And</span> <span m=''3505080''>I</span>
  <span m=''3505150''>know</span> <span m=''3505380''>that</span> <span m=''3505620''>by</span>
  <span m=''3505750''>folding</span> <span m=''3506170''>I</span> <span m=''3506210''>could</span>
  <span m=''3506350''>only</span> <span m=''3506560''>make</span> <span m=''3506740''>distance</span>
  <span m=''3507080''>is</span> <span m=''3507170''>smaller.</span> <span m=''3508400''>So</span>
  <span m=''3508560''>somehow,</span> <span m=''3509290''>if</span> <span m=''3509380''>I</span>
  <span m=''3509440''>measure</span> <span m=''3509840''>the</span> <span m=''3511180''>shortest</span>
  <span m=''3511560''>path</span> <span m=''3512080''>on</span> <span m=''3512420''>the</span>
  <span m=''3512520''>cube,</span> <span m=''3513370''>from</span> <span m=''3513440''>this</span>
  <span m=''3513590''>point</span> <span m=''3513790''>to</span> <span m=''3513850''>this</span>
  <span m=''3514030''>point,</span> <span m=''3514660''>it''s</span> <span m=''3516460''>that</span>
  <span m=''3518970''>if</span> <span m=''3519070''>you</span> <span m=''3519180''>believe--</span>
  <span m=''3520010''>when</span> <span m=''3520130''>you</span> <span m=''3520240''>unfold</span>
  <span m=''3520650''>this</span> <span m=''3520810''>thing,</span> <span m=''3520980''>it</span>
  <span m=''3521050''>should</span> <span m=''3521230''>be</span> <span m=''3521390''>flat.</span>
  </p><p><span m=''3522720''>If I</span> <span m=''3522930''>unfolds</span> <span
  m=''3524190''>to</span> <span m=''3524260''>just</span> <span m=''3524440''>those</span>
  <span m=''3524620''>two</span> <span m=''3524750''>squares,</span> <span m=''3525240''>it''s</span>
  <span m=''3525420''>a</span> <span m=''3525460''>straight</span> <span m=''3525750''>line</span>
  <span m=''3526880''>between</span> <span m=''3527130''>the</span> <span m=''3527230''>two.</span>
  <span m=''3528710''>And</span> <span m=''3528910''>so</span> <span m=''3529000''>that</span>
  <span m=''3529220''>goes</span> <span m=''3529420''>to</span> <span m=''3529520''>the</span>
  <span m=''3529590''>midpoint</span> <span m=''3530050''>of</span> <span m=''3530120''>this</span>
  <span m=''3530300''>edge</span> <span m=''3530560''>and</span> <span m=''3530640''>then</span>
  <span m=''3530770''>over</span> <span m=''3530960''>there.</span> <span m=''3531610''>And</span>
  <span m=''3531830''>you</span> <span m=''3531940''>measure</span> <span m=''3532220''>that</span>
  <span m=''3532440''>length.</span> <span m=''3533700''>And</span> <span m=''3534230''>oh,</span>
  <span m=''3534460''>trigonometry.</span> <span m=''3537510''>Root</span> <span m=''3537800''>five,</span>
  <span m=''3539010''>that''s</span> <span m=''3539130''>not</span> <span m=''3539270''>what</span>
  <span m=''3539390''>I</span> <span m=''3539450''>wanted.</span> <span m=''3544090''>So</span>
  <span m=''3544280''>we have</span> <span m=''3544470''>x</span> <span m=''3545430''>here,</span>
  <span m=''3546710''>2x</span> <span m=''3547270''>here.</span> <span m=''3549460''>So</span>
  <span m=''3551140''>this</span> <span m=''3551480''>distance</span> <span m=''3554630''>is--</span>
  <span m=''3557182''>yeah,</span> <span m=''3557680''>I</span> <span m=''3557840''>see.</span>
  <span m=''3564250''>Why</span> <span m=''3564400''>is</span> <span m=''3564510''>that</span>
  <span m=''3564680''>different</span> <span m=''3565030''>from</span> <span m=''3565160''>what</span>
  <span m=''3565280''>I</span> <span m=''3565340''>have</span> <span m=''3565540''>written</span>
  <span m=''3565760''>down?</span> </p><p><span m=''3573940''>Because</span> <span
  m=''3574120''>that</span> <span m=''3574250''>was</span> <span m=''3574360''>not</span>
  <span m=''3574540''>the</span> <span m=''3574630''>diameter</span> <span m=''3575070''>of</span>
  <span m=''3575130''>the</span> <span m=''3575220''>cube.</span> <span m=''3575590''>I
  see.</span> </p><p><span m=''3577710''>AUDIENCE: You want</span> <span m=''3578190''>them</span>
  <span m=''3578670''>equidistant.</span> </p><p><span m=''3580660''>PROFESSOR: No.</span>
  <span m=''3580870''>I</span> <span m=''3581260''>do</span> <span m=''3581440''>want</span>
  <span m=''3581660''>this</span> <span m=''3581880''>but,</span> <span m=''3581990''>I</span>
  <span m=''3582070''>think</span> <span m=''3584360''>if</span> <span m=''3584530''>I</span>
  <span m=''3584600''>go</span> <span m=''3584750''>from</span> <span m=''3584990''>the</span>
  <span m=''3585120''>center</span> <span m=''3585580''>of</span> <span m=''3585650''>this</span>
  <span m=''3585820''>square--</span> <span m=''3587160''>this</span> <span m=''3587390''>is</span>
  <span m=''3587490''>hard</span> <span m=''3587690''>to</span> <span m=''3587740''>draw.</span>
  <span m=''3588120''>--to</span> <span m=''3588570''>the</span> <span m=''3588720''>center</span>
  <span m=''3589110''>of</span> <span m=''3589180''>the</span> <span m=''3589270''>back</span>
  <span m=''3589370''>square,</span> <span m=''3592300''>which</span> <span m=''3592480''>is</span>
  <span m=''3592760''>back</span> <span m=''3593030''>here,</span> <span m=''3594570''>that</span>
  <span m=''3594850''>distance</span> <span m=''3595310''>is</span> <span m=''3595450''>going</span>
  <span m=''3595600''>to</span> <span m=''3595680''>be</span> <span m=''3596320''>wrapping</span>
  <span m=''3596830''>around.</span> <span m=''3598980''>Which</span> <span m=''3599260''>is</span>
  <span m=''3599400''>just</span> <span m=''3599690''>going</span> <span m=''3599830''>to</span>
  <span m=''3599890''>be</span> <span m=''3600040''>like</span> <span m=''3600280''>2x.</span>
  <span m=''3602550''>Is</span> <span m=''3602630''>that</span> <span m=''3602730''>bigger</span>
  <span m=''3602970''>or</span> <span m=''3603040''>smaller</span> <span m=''3603340''>than
  root</span> <span m=''3603610''>5x?</span> </p><p><span m=''3604836''>AUDIENCE:
  It''s</span> <span m=''3605302''>smaller.</span> </p><p><span m=''3605770''>PROFESSOR:
  Smaller.</span> <span m=''3607580''>Interesting.</span> <span m=''3611676''>One,</span>
  <span m=''3612500''>two,</span> <span m=''3612960''>three,</span> <span m=''3614020''>four.</span>
  <span m=''3616100''>What did</span> <span m=''3616440''>I</span> <span m=''3616690''>do</span>
  <span m=''3616840''>wrong?</span> <span m=''3621610''>Oh,</span> <span m=''3622000''>I</span>
  <span m=''3622120''>see.</span> <span m=''3622410''>OK.</span> <span m=''3623710''>Here''s</span>
  <span m=''3623960''>a</span> <span m=''3624010''>fun</span> <span m=''3624270''>fact.</span>
  <span m=''3625600''>This</span> <span m=''3625790''>is</span> <span m=''3625920''>actually</span>
  <span m=''3626300''>the</span> <span m=''3626900''>smallest</span> <span m=''3627950''>antipodal</span>
  <span m=''3628490''>distance.</span> <span m=''3629280''>Get</span> <span m=''3629430''>this</span>
  <span m=''3629590''>right.</span> <span m=''3630470''>So</span> <span m=''3630570''>if</span>
  <span m=''3630620''>you</span> <span m=''3630710''>take</span> <span m=''3630940''>some</span>
  <span m=''3631140''>point</span> <span m=''3631470''>on</span> <span m=''3631610''>the</span>
  <span m=''3631690''>cube,</span> <span m=''3632530''>and</span> <span m=''3632680''>you</span>
  <span m=''3632850''>look</span> <span m=''3633060''>at</span> <span m=''3633150''>the</span>
  <span m=''3633240''>point</span> <span m=''3633510''>farthest</span> <span m=''3634080''>away</span>
  <span m=''3634290''>from</span> <span m=''3634500''>it</span> <span m=''3634570''>on</span>
  <span m=''3634670''>the</span> <span m=''3634780''>other</span> <span m=''3634960''>side</span>
  <span m=''3635170''>of</span> <span m=''3635230''>the</span> <span m=''3635310''>cube,</span>
  <span m=''3635635''>it</span> <span m=''3635960''>will</span> <span m=''3636090''>always</span>
  <span m=''3636490''>be</span> <span m=''3636650''>at</span> <span m=''3636720''>least</span>
  <span m=''3637230''>2x</span> <span m=''3637600''>away.</span> </p><p><span m=''3638780''>So</span>
  <span m=''3638970''>here,</span> <span m=''3639250''>it''s</span> <span m=''3639410''>bigger.</span>
  <span m=''3639830''>This</span> <span m=''3640050''>is</span> <span m=''3640230''>probably</span>
  <span m=''3640520''>the</span> <span m=''3640620''>diameter.</span> <span m=''3641450''>It''s</span>
  <span m=''3641890''>bigger</span> <span m=''3642120''>than</span> <span m=''3642250''>2x,</span>
  <span m=''3642630''>but it will</span> <span m=''3642900''>always</span> <span m=''3643020''>be
  at least</span> <span m=''3643440''>2x</span> <span m=''3643790''>away.</span> <span
  m=''3644130''>This</span> <span m=''3644330''>is</span> <span m=''3644450''>actually</span>
  <span m=''3645920''>the</span> <span m=''3646030''>smallest</span> <span m=''3646560''>situation</span>
  <span m=''3647070''>you can</span> <span m=''3647320''>get.</span> <span m=''3648380''>And</span>
  <span m=''3648570''>so</span> <span m=''3649180''>I</span> <span m=''3649350''>want</span>
  <span m=''3649560''>to</span> <span m=''3649620''>think</span> <span m=''3649880''>about</span>
  <span m=''3650280''>the</span> <span m=''3650420''>point</span> <span m=''3650720''>that</span>
  <span m=''3650850''>corresponds</span> <span m=''3651470''>to</span> <span m=''3651580''>the</span>
  <span m=''3651700''>center</span> <span m=''3652280''>of</span> <span m=''3652450''>the</span>
  <span m=''3652550''>square.</span> <span m=''3653260''>Right?</span> <span m=''3653870''>Yes.</span>
  <span m=''3655880''>Now</span> <span m=''3657030''>maybe</span> <span m=''3657380''>that</span>
  <span m=''3657550''>maps</span> <span m=''3657800''>to</span> <span m=''3657900''>the</span>
  <span m=''3658020''>center</span> <span m=''3658990''>like</span> <span m=''3659210''>this.</span>
  <span m=''3659810''>And</span> <span m=''3660300''>the</span> <span m=''3660460''>antipodal</span>
  <span m=''3660890''>points</span> <span m=''3661290''>is</span> <span m=''3661700''>2x</span>
  <span m=''3662050''>away,</span> <span m=''3662270''>or</span> <span m=''3662360''>maybe</span>
  <span m=''3662580''>it''s</span> <span m=''3662720''>bigger.</span> </p><p><span
  m=''3663390''>But</span> <span m=''3663580''>at</span> <span m=''3663670''>least</span>
  <span m=''3664040''>I</span> <span m=''3664110''>know</span> <span m=''3664490''>that</span>
  <span m=''3664780''>this</span> <span m=''3665810''>length</span> <span m=''3667650''>is</span>
  <span m=''3667980''>greater</span> <span m=''3668450''>than</span> <span m=''3668670''>or</span>
  <span m=''3668780''>equal</span> <span m=''3669060''>to</span> <span m=''3669180''>2x</span>
  <span m=''3671560''>because</span> <span m=''3672260''>that''s--</span> <span m=''3672900''>the</span>
  <span m=''3673350''>antipodal</span> <span m=''3674190''>point</span> <span m=''3674440''>has</span>
  <span m=''3674770''>to</span> <span m=''3674860''>be</span> <span m=''3674980''>made</span>
  <span m=''3675200''>from</span> <span m=''3675350''>that.</span> <span m=''3676540''>I</span>
  <span m=''3676690''>need</span> <span m=''3676920''>to</span> <span m=''3677030''>think</span>
  <span m=''3677260''>about</span> <span m=''3677540''>all</span> <span m=''3677750''>situation</span>
  <span m=''3678290''>because</span> <span m=''3678470''>I</span> <span m=''3678500''>really</span>
  <span m=''3678780''>want</span> <span m=''3678940''>to</span> <span m=''3678990''>think</span>
  <span m=''3679160''>about</span> <span m=''3679370''>the</span> <span m=''3679450''>center</span>
  <span m=''3679720''>of</span> <span m=''3679760''>the</span> <span m=''3679850''>square.</span>
  <span m=''3680540''>Once</span> <span m=''3680830''>that</span> <span m=''3681080''>is</span>
  <span m=''3681220''>at</span> <span m=''3681310''>least</span> <span m=''3681630''>2x,</span>
  <span m=''3682730''>then</span> <span m=''3682910''>I</span> <span m=''3682980''>know</span>
  <span m=''3683260''>that</span> <span m=''3683685''>the</span> <span m=''3684550''>side</span>
  <span m=''3685010''>of</span> <span m=''3685100''>the</span> <span m=''3685190''>square</span>
  <span m=''3685660''>is</span> <span m=''3685800''>at</span> <span m=''3685940''>least</span>
  <span m=''3688030''>2</span> <span m=''3688200''>root</span> <span m=''3688380''>2x.</span>
  <span m=''3689580''>Yes.</span> </p><p><span m=''3695450''>And</span> <span m=''3695700''>so</span>
  <span m=''3696060''>I</span> <span m=''3696190''>know</span> <span m=''3696390''>that</span>
  <span m=''3696660''>this</span> <span m=''3697170''>is</span> <span m=''3697910''>one.</span>
  <span m=''3700780''>And</span> <span m=''3701220''>you</span> <span m=''3701360''>work</span>
  <span m=''3701570''>it</span> <span m=''3701660''>out.</span> <span m=''3701880''>And</span>
  <span m=''3701990''>x</span> <span m=''3702270''>is</span> <span m=''3702740''>root</span>
  <span m=''3703030''>2</span> <span m=''3703220''>over</span> <span m=''3703390''>4.</span>
  <span m=''3706910''>Or</span> <span m=''3707100''>it''s</span> <span m=''3707210''>at</span>
  <span m=''3707280''>most</span> <span m=''3707580''>that.</span> <span m=''3709370''>And</span>
  <span m=''3709720''>so</span> <span m=''3709830''>that</span> <span m=''3710020''>gives</span>
  <span m=''3710180''>you</span> <span m=''3710290''>some</span> <span m=''3710920''>bound</span>
  <span m=''3711380''>on</span> <span m=''3711790''>what</span> <span m=''3711960''>it</span>
  <span m=''3712080''>takes.</span> <span m=''3712380''>So</span> <span m=''3712460''>this</span>
  <span m=''3712620''>is</span> <span m=''3712690''>actually</span> <span m=''3712980''>really</span>
  <span m=''3713180''>the</span> <span m=''3713330''>only</span> <span m=''3713570''>technique</span>
  <span m=''3714110''>we</span> <span m=''3714240''>know</span> <span m=''3715000''>to</span>
  <span m=''3715130''>prove</span> <span m=''3715570''>lower</span> <span m=''3715840''>bounds</span>
  <span m=''3716210''>on</span> <span m=''3716340''>how</span> <span m=''3716686''>much--</span>
  <span m=''3717032''>how</span> <span m=''3717380''>big</span> <span m=''3717550''>a</span>
  <span m=''3717610''>square</span> <span m=''3717850''>you</span> <span m=''3717950''>need</span>
  <span m=''3718140''>to</span> <span m=''3718230''>make</span> <span m=''3718420''>something.</span>
  </p><p><span m=''3719520''>It''s</span> <span m=''3719680''>this</span> <span m=''3719850''>kind</span>
  <span m=''3720060''>of</span> <span m=''3720640''>distance</span> <span m=''3721000''>increasing</span>
  <span m=''3721500''>argument.</span> <span m=''3722540''>And</span> <span m=''3722710''>it</span>
  <span m=''3722790''>turns</span> <span m=''3723040''>out</span> <span m=''3723190''>you</span>
  <span m=''3723310''>can</span> <span m=''3723430''>actually</span> <span m=''3723670''>achieve</span>
  <span m=''3724080''>x</span> <span m=''3724370''>equals</span> <span m=''3724800''>this.</span>
  <span m=''3725390''>So</span> <span m=''3725500''>this</span> <span m=''3725690''>is</span>
  <span m=''3725800''>what</span> <span m=''3726090''>I</span> <span m=''3726380''>call</span>
  <span m=''3726680''>lower</span> <span m=''3726940''>bound.</span> <span m=''3727230''>It</span>
  <span m=''3727390''>says,</span> <span m=''3727500''>you</span> <span m=''3727600''>can''t</span>
  <span m=''3727830''>do</span> <span m=''3727930''>any</span> <span m=''3728060''>better</span>
  <span m=''3728340''>than</span> <span m=''3728490''>this.</span> <span m=''3729440''>But</span>
  <span m=''3729460''>there''s</span> <span m=''3729620''>also</span> <span m=''3729870''>a</span>
  <span m=''3729920''>matching</span> <span m=''3730320''>upper</span> <span m=''3730580''>bound</span>
  <span m=''3734810''>which</span> <span m=''3735180''>achieves</span> <span m=''3735300''>this</span>
  <span m=''3736310''>and</span> <span m=''3748722''>not</span> <span m=''3749230''>going
  to draw it</span> <span m=''3749470''>perfectly.</span> </p><p><span m=''3760950''>So</span>
  <span m=''3761500''>there</span> <span m=''3761740''>are the</span> <span m=''3761840''>six</span>
  <span m=''3762130''>sides of</span> <span m=''3762330''>the</span> <span m=''3762450''>cube.</span>
  <span m=''3762760''>You''ve</span> <span m=''3762910''>got</span> <span m=''3763120''>one,</span>
  <span m=''3763540''>two,</span> <span m=''3763960''>three,</span> <span m=''3764380''>four,</span>
  <span m=''3764800''>five.</span> <span m=''3765220''>And</span> <span m=''3765640''>the
  sixth one is</span> <span m=''3765730''>split</span> <span m=''3765940''>into</span>
  <span m=''3766120''>quarters.</span> <span m=''3767470''>And</span> <span m=''3767680''>you</span>
  <span m=''3767800''>can</span> <span m=''3767900''>see, you</span> <span m=''3768310''>just</span>
  <span m=''3768560''>actually</span> <span m=''3769420''>fold</span> <span m=''3769880''>here,</span>
  <span m=''3770370''>here,</span> <span m=''3771390''>here,</span> <span m=''3771710''>and</span>
  <span m=''3771810''>here</span> <span m=''3772390''>to</span> <span m=''3772510''>get</span>
  <span m=''3772690''>rid</span> <span m=''3772820''>of</span> <span m=''3772900''>that</span>
  <span m=''3773090''>excess.</span> <span m=''3773880''>And</span> <span m=''3774070''>it</span>
  <span m=''3774130''>will</span> <span m=''3774260''>come</span> <span m=''3774460''>together</span>
  <span m=''3774810''>as</span> <span m=''3774920''>a</span> <span m=''3774980''>cube.</span>
  <span m=''3775440''>You also</span> <span m=''3775600''>fold</span> <span m=''3775810''>along</span>
  <span m=''3776040''>the</span> <span m=''3776130''>edges of</span> <span m=''3776440''>the</span>
  <span m=''3776540''>cube.</span> <span m=''3777320''>And</span> <span m=''3777560''>it</span>
  <span m=''3777720''>perfectly</span> <span m=''3778240''>achieves</span> <span m=''3779620''>this</span>
  <span m=''3779800''>property.</span> </p><p><span m=''3780180''>That from</span>
  <span m=''3780480''>the</span> <span m=''3780570''>center</span> <span m=''3781580''>of</span>
  <span m=''3781720''>the</span> <span m=''3781810''>paper,</span> <span m=''3782870''>you</span>
  <span m=''3782980''>have</span> <span m=''3783170''>exactly</span> <span m=''3784640''>one</span>
  <span m=''3785890''>this</span> <span m=''3786290''>distance</span> <span m=''3787050''>2</span>
  <span m=''3787230''>root</span> <span m=''3787400''>2x</span> <span m=''3788820''>to</span>
  <span m=''3789220''>the</span> <span m=''3789480''>antipodal</span> <span m=''3790050''>point</span>
  <span m=''3790300''>which</span> <span m=''3790480''>is</span> <span m=''3790590''>the</span>
  <span m=''3790670''>center</span> <span m=''3791020''>of</span> <span m=''3791080''>the</span>
  <span m=''3791220''>opposite</span> <span m=''3791650''>face.</span> <span m=''3792690''>Question?</span>
  </p><p><span m=''3793130''>AUDIENCE: Sorry.</span> <span m=''3793584''>Can you</span>
  <span m=''3794038''>explain</span> <span m=''3794492''>where the</span> <span m=''3794946''>2x
  came from</span> <span m=''3795854''>[INAUDIBLE]?</span> </p><p><span m=''3797670''>PROFESSOR:
  I</span> <span m=''3797810''>wave</span> <span m=''3798070''>my</span> <span m=''3798230''>hands.</span>
  <span m=''3800440''>So</span> <span m=''3801370''>I''m</span> <span m=''3801520''>thinking</span>
  <span m=''3801750''>about</span> <span m=''3801920''>an</span> <span m=''3802000''>arbitrary</span>
  <span m=''3802530''>point</span> <span m=''3802750''>on</span> <span m=''3802870''>the</span>
  <span m=''3802950''>surface</span> <span m=''3803340''>of</span> <span m=''3803410''>the</span>
  <span m=''3803520''>cube.</span> <span m=''3804410''>Here,</span> <span m=''3805150''>it</span>
  <span m=''3805550''>should</span> <span m=''3805740''>be</span> <span m=''3805850''>clear</span>
  <span m=''3806040''>it''s</span> <span m=''3806180''>2x.</span> <span m=''3806560''>There''s</span>
  <span m=''3806730''>x</span> <span m=''3807130''>right</span> <span m=''3807330''>here.</span>
  <span m=''3808350''>And</span> <span m=''3808550''>there''s</span> <span m=''3808690''>1/2x</span>
  <span m=''3809220''>here.</span> <span m=''3810290''>And</span> <span m=''3810600''>there''s</span>
  <span m=''3810740''>1/2x</span> <span m=''3811540''>on</span> <span m=''3811710''>the</span>
  <span m=''3811800''>back.</span> <span m=''3812800''>And</span> <span m=''3813260''>I</span>
  <span m=''3813380''>looked</span> <span m=''3813650''>at</span> <span m=''3813820''>another</span>
  <span m=''3814290''>situation</span> <span m=''3814860''>which</span> <span m=''3815020''>is</span>
  <span m=''3815110''>when</span> <span m=''3815640''>it</span> <span m=''3815910''>was</span>
  <span m=''3816060''>at</span> <span m=''3816170''>a</span> <span m=''3816230''>corner</span>
  <span m=''3816930''>that</span> <span m=''3817290''>bigger</span> <span m=''3817560''>than</span>
  <span m=''3817710''>2x.</span> </p><p><span m=''3818760''>And I</span> <span m=''3818850''>claim</span>
  <span m=''3819120''>if</span> <span m=''3819200''>you</span> <span m=''3819300''>interpolate</span>
  <span m=''3819800''>in</span> <span m=''3819880''>the</span> <span m=''3819960''>middle,</span>
  <span m=''3820210''>you''ll</span> <span m=''3820350''>get</span> <span m=''3820520''>something</span>
  <span m=''3820870''>in</span> <span m=''3821010''>the</span> <span m=''3821080''>middle,</span>
  <span m=''3821410''>in</span> <span m=''3821490''>between</span> <span m=''3821950''>2x</span>
  <span m=''3822730''>and root</span> <span m=''3823030''>5x.</span> <span m=''3824920''>For</span>
  <span m=''3825050''>example,</span> <span m=''3825340''>if</span> <span m=''3825470''>take</span>
  <span m=''3825690''>a</span> <span m=''3825760''>point</span> <span m=''3826400''>here</span>
  <span m=''3826830''>that''s</span> <span m=''3827300''>closer</span> <span m=''3827750''>to</span>
  <span m=''3827860''>the</span> <span m=''3828000''>corner,</span> <span m=''3828940''>then</span>
  <span m=''3829770''>that</span> <span m=''3830530''>point--</span> <span m=''3830720''>you</span>
  <span m=''3830790''>should</span> <span m=''3830930''>probably</span> <span m=''3831220''>also</span>
  <span m=''3831440''>think</span> <span m=''3831640''>about</span> <span m=''3831880''>the</span>
  <span m=''3832010''>edge</span> <span m=''3832270''>case.</span> <span m=''3833300''>But</span>
  <span m=''3833440''>you</span> <span m=''3833530''>check</span> <span m=''3833750''>all</span>
  <span m=''3833980''>of</span> <span m=''3834050''>them,</span> <span m=''3834760''>and</span>
  <span m=''3834850''>they''re</span> <span m=''3834970''>at</span> <span m=''3835020''>least</span>
  <span m=''3835250''>2x.</span> <span m=''3835780''>That''s</span> <span m=''3835990''>what</span>
  <span m=''3836100''>I''m</span> <span m=''3836210''>claiming.</span> </p><p><span
  m=''3837480''>So</span> <span m=''3837580''>I</span> <span m=''3837680''>didn''t</span>
  <span m=''3837760''>really</span> <span m=''3837950''>prove</span> <span m=''3838160''>that</span>
  <span m=''3838410''>formally.</span> <span m=''3839330''>But</span> <span m=''3839880''>claim</span>
  <span m=''3840120''>is</span> <span m=''3840290''>2x</span> <span m=''3840840''>is</span>
  <span m=''3841030''>the</span> <span m=''3841100''>smallest</span> <span m=''3842010''>antepodal</span>
  <span m=''3842690''>pair</span> <span m=''3843030''>you</span> <span m=''3843180''>could</span>
  <span m=''3843360''>get.</span> </p><p><span m=''3843820''>AUDIENCE: What</span>
  <span m=''3844235''>does</span> <span m=''3844650''>antipodal</span> <span m=''3844857''>mean?</span>
  </p><p><span m=''3845480''>PROFESSOR: Antipodal</span> <span m=''3845700''>simple</span>
  <span m=''3846030''>means</span> <span m=''3846550''>on</span> <span m=''3846710''>the</span>
  <span m=''3846860''>other</span> <span m=''3847050''>side.</span> <span m=''3847750''>The</span>
  <span m=''3847920''>anti</span> <span m=''3848270''>pode,</span> <span m=''3848620''>the</span>
  <span m=''3848790''>opposite</span> <span m=''3849220''>pole,</span> <span m=''3850250''>like</span>
  <span m=''3850470''>from</span> <span m=''3850580''>North</span> <span m=''3850830''>Pole</span>
  <span m=''3850980''>to</span> <span m=''3851050''>South</span> <span m=''3851300''>Pole.</span>
  </p><p><span m=''3851600''>AUDIENCE: [INAUDIBLE].</span> </p><p><span m=''3854730''>PROFESSOR:
  Right</span> <span m=''3854960''>now,</span> <span m=''3855140''>we</span> <span
  m=''3855250''>know</span> <span m=''3855800''>we''re</span> <span m=''3855990''>taking</span>
  <span m=''3856390''>whatever</span> <span m=''3856870''>point</span> <span m=''3857380''>is</span>
  <span m=''3857550''>the</span> <span m=''3857630''>center</span> <span m=''3857960''>of</span>
  <span m=''3858060''>the</span> <span m=''3858150''>square.</span> <span m=''3858430''>It</span>
  <span m=''3858710''>maps</span> <span m=''3858890''>somewhere</span> <span m=''3859340''>in</span>
  <span m=''3859430''>the</span> <span m=''3859530''>cube.</span> <span m=''3860350''>I</span>
  <span m=''3860440''>take</span> <span m=''3860680''>the antipode</span> <span m=''3861150''>from</span>
  <span m=''3861380''>there.</span> <span m=''3861760''>I</span> <span m=''3861800''>know</span>
  <span m=''3861940''>that</span> <span m=''3862060''>has</span> <span m=''3862230''>to</span>
  <span m=''3862330''>be</span> <span m=''3862460''>at</span> <span m=''3862550''>least</span>
  <span m=''3863350''>2x</span> <span m=''3863740''>away.</span> <span m=''3866540''>And</span>
  <span m=''3867820''>if</span> <span m=''3868070''>you</span> <span m=''3868160''>look</span>
  <span m=''3868320''>at</span> <span m=''3868380''>the</span> <span m=''3868490''>distance</span>
  <span m=''3868900''>map</span> <span m=''3869230''>here,</span> <span m=''3869850''>the</span>
  <span m=''3869940''>farthest</span> <span m=''3870340''>away</span> <span m=''3870500''>point</span>
  <span m=''3870730''>in</span> <span m=''3870810''>the</span> <span m=''3870880''>squared</span>
  <span m=''3871690''>from</span> <span m=''3871940''>the</span> <span m=''3872030''>center</span>
  <span m=''3872480''>is</span> <span m=''3872790''>the</span> <span m=''3873500''>corner</span>
  <span m=''3873820''>point.</span> </p><p><span m=''3874230''>So</span> <span m=''3874380''>I</span>
  <span m=''3874460''>know</span> <span m=''3874610''>that that</span> <span m=''3875020''>distance</span>
  <span m=''3875950''>can</span> <span m=''3876070''>only</span> <span m=''3876250''>get</span>
  <span m=''3876410''>smaller.</span> <span m=''3876760''>And other</span> <span m=''3877000''>distances</span>
  <span m=''3877410''>only</span> <span m=''3877610''>get</span> <span m=''3877770''>smaller.</span>
  <span m=''3878800''>So</span> <span m=''3878900''>if</span> <span m=''3878920''>I</span>
  <span m=''3879060''>have</span> <span m=''3879350''>to</span> <span m=''3879450''>make</span>
  <span m=''3879650''>a</span> <span m=''3879720''>2x</span> <span m=''3880110''>distance</span>
  <span m=''3880510''>from</span> <span m=''3880670''>there,</span> <span m=''3881610''>this</span>
  <span m=''3881800''>is</span> <span m=''3881920''>my</span> <span m=''3882070''>best</span>
  <span m=''3882630''>chance</span> <span m=''3882940''>for</span> <span m=''3883030''>doing</span>
  <span m=''3883300''>it.</span> <span m=''3883770''>And</span> <span m=''3883870''>that</span>
  <span m=''3884010''>gives</span> <span m=''3884150''>you</span> <span m=''3884520''>a</span>
  <span m=''3884650''>lower</span> <span m=''3884890''>bound.</span> <span m=''3885200''>Doesn''t</span>
  <span m=''3885410''>mean</span> <span m=''3885540''>it</span> <span m=''3885600''>can</span>
  <span m=''3885700''>be</span> <span m=''3885800''>achieved.</span> <span m=''3886180''>But</span>
  <span m=''3886340''>this</span> <span m=''3886870''>shows</span> <span m=''3887170''>you</span>
  <span m=''3887320''>that</span> <span m=''3887450''>you</span> <span m=''3887560''>can</span>
  <span m=''3887730''>achieve</span> <span m=''3888020''>it.</span> <span m=''3889260''>This</span>
  <span m=''3889460''>is</span> <span m=''3889580''>a</span> <span m=''3889630''>result</span>
  <span m=''3890090''>by</span> <span m=''3890990''>Catalano,</span> <span m=''3891410''>Johnson,
  and</span> <span m=''3891860''>Lobe</span> <span m=''3892150''>in</span> <span m=''3892310''>2001.</span>
  </p><p><span m=''3893550''>It''s</span> <span m=''3893700''>like</span> <span m=''3893850''>the</span>
  <span m=''3894000''>only</span> <span m=''3894340''>optimality</span> <span m=''3894870''>result</span>
  <span m=''3895330''>we</span> <span m=''3895460''>have</span> <span m=''3895780''>for</span>
  <span m=''3895920''>folding</span> <span m=''3896260''>3D</span> <span m=''3896510''>shapes.</span>
  <span m=''3896840''>That''s</span> <span m=''3897020''>why</span> <span m=''3897140''>I</span>
  <span m=''3897170''>mention</span> <span m=''3897455''>it.</span> <span m=''3898110''>Tons</span>
  <span m=''3898400''>of</span> <span m=''3898490''>fun</span> <span m=''3898680''>open</span>
  <span m=''3898900''>problems</span> <span m=''3899470''>like</span> <span m=''3900320''>you
  don''t</span> <span m=''3900490''>want</span> <span m=''3900630''>to</span> <span
  m=''3900670''>make</span> <span m=''3900860''>a</span> <span m=''3900920''>square--</span>
  <span m=''3901230''>a</span> <span m=''3901540''>cube.</span> <span m=''3901920''>Maybe</span>
  <span m=''3902190''>you</span> <span m=''3902310''>want</span> <span m=''3902480''>to</span>
  <span m=''3902530''>make</span> <span m=''3904980''>a</span> <span m=''3905220''>triangle.</span>
  <span m=''3906190''>If</span> <span m=''3906270''>you</span> <span m=''3906380''>want</span>
  <span m=''3906480''>to</span> <span m=''3906520''>cover</span> <span m=''3906850''>a
  triangle</span> <span m=''3907110''>on</span> <span m=''3907230''>both</span> <span
  m=''3907410''>sides,</span> <span m=''3908240''>that''s</span> <span m=''3908290''>probably</span>
  <span m=''3908610''>open.</span> <span m=''3909280''>If</span> <span m=''3909360''>you</span>
  <span m=''3909470''>want</span> <span m=''3909570''>to</span> <span m=''3909610''>make</span>
  <span m=''3909780''>regular</span> <span m=''3910100''>tetrahedron,</span> <span
  m=''3910770''>that''s</span> <span m=''3911000''>probably</span> <span m=''3911300''>open.</span>
  </p><p><span m=''3912050''>Pretty</span> <span m=''3912200''>much</span> <span m=''3912390''>any</span>
  <span m=''3912600''>problem</span> <span m=''3912870''>you</span> <span m=''3913000''>pose</span>
  <span m=''3913290''>here</span> <span m=''3913490''>is</span> <span m=''3913600''>open.</span>
  <span m=''3914030''>It would</span> <span m=''3914210''>make</span> <span m=''3914450''>fun</span>
  <span m=''3914660''>project.</span> <span m=''3916610''>You</span> <span m=''3916770''>can</span>
  <span m=''3916910''>also</span> <span m=''3917130''>think</span> <span m=''3917320''>about,</span>
  <span m=''3917520''>instead</span> <span m=''3917760''>of</span> <span m=''3917820''>starting</span>
  <span m=''3918100''>from</span> <span m=''3918270''>square,</span> <span m=''3918590''>you</span>
  <span m=''3918680''>start</span> <span m=''3918920''>with</span> <span m=''3919070''>a</span>
  <span m=''3919200''>rectangle</span> <span m=''3919515''>of</span> <span m=''3919830''>some</span>
  <span m=''3920330''>given</span> <span m=''3920800''>aspect</span> <span m=''3921210''>ratio.</span>
  <span m=''3922000''>What''s</span> <span m=''3922180''>the</span> <span m=''3922260''>biggest</span>
  <span m=''3922560''>cube</span> <span m=''3922720''>you can</span> <span m=''3922990''>make?</span>
  <span m=''3923710''>That''s</span> <span m=''3923890''>kind</span> <span m=''3924030''>of</span>
  <span m=''3924110''>fun</span> <span m=''3924320''>because</span> <span m=''3924610''>in
  the</span> <span m=''3924970''>limit</span> <span m=''3925320''>for a</span> <span
  m=''3925490''>super</span> <span m=''3925770''>long</span> <span m=''3925970''>rectangle,</span>
  <span m=''3926880''>you</span> <span m=''3927185''>should do</span> <span m=''3927490''>strip</span>
  <span m=''3927810''>wrapping.</span> </p><p><span m=''3928800''>For a</span> <span
  m=''3928980''>square,</span> <span m=''3929350''>we</span> <span m=''3929440''>have</span>
  <span m=''3929560''>the</span> <span m=''3929640''>right</span> <span m=''3929800''>answer.</span>
  <span m=''3930520''>What''s</span> <span m=''3930680''>the</span> <span m=''3930770''>right</span>
  <span m=''3930940''>answer in</span> <span m=''3931240''>between?</span> <span m=''3932880''>Who
  knows.</span> <span m=''3937550''>The</span> <span m=''3937640''>next</span> <span
  m=''3937910''>thing</span> <span m=''3938070''>I</span> <span m=''3938110''>wanted</span>
  <span m=''3938260''>to</span> <span m=''3938400''>talk</span> <span m=''3938660''>about</span>
  <span m=''3941335''>where</span> <span m=''3941790''>there''s</span> <span m=''3942070''>been</span>
  <span m=''3942230''>some</span> <span m=''3942460''>recent</span> <span m=''3942780''>progress</span>
  <span m=''3943840''>is</span> <span m=''3944030''>checkerboard</span> <span m=''3944610''>folding.</span>
  </p><p><span m=''3953630''>In</span> <span m=''3953780''>lecture</span> <span m=''3954130''>one,</span>
  <span m=''3954440''>I</span> <span m=''3954540''>showed</span> <span m=''3954910''>you</span>
  <span m=''3955650''>this</span> <span m=''3955980''>model</span> <span m=''3956620''>which</span>
  <span m=''3956840''>I</span> <span m=''3956930''>never</span> <span m=''3957190''>go</span>
  <span m=''3957350''>anywhere</span> <span m=''3957670''>without,</span> <span m=''3958940''>the</span>
  <span m=''3959330''>four by</span> <span m=''3959730''>four</span> <span m=''3959950''>checkerboard</span>
  <span m=''3963540''>folded</span> <span m=''3963890''>from</span> <span m=''3964060''>one</span>
  <span m=''3964210''>square</span> <span m=''3964510''>paper,</span> <span m=''3965280''>white</span>
  <span m=''3965490''>on</span> <span m=''3965590''>one</span> <span m=''3965750''>side</span>
  <span m=''3966460''>and</span> <span m=''3966700''>red</span> <span m=''3966850''>on</span>
  <span m=''3966950''>the</span> <span m=''3967080''>other.</span> <span m=''3968020''>And</span>
  <span m=''3968110''>so</span> <span m=''3969120''>I</span> <span m=''3969240''>think</span>
  <span m=''3969480''>this</span> <span m=''3969650''>is</span> <span m=''3969760''>probably</span>
  <span m=''3970390''>the</span> <span m=''3970490''>most</span> <span m=''3970730''>efficient</span>
  <span m=''3971110''>way</span> <span m=''3971260''>to</span> <span m=''3971340''>fold</span>
  <span m=''3971700''>a</span> <span m=''3971740''>four</span> <span m=''3971950''>by</span>
  <span m=''3972070''>four</span> <span m=''3972260''>checkerboard.</span> </p><p><span
  m=''3973310''>You</span> <span m=''3973420''>start</span> <span m=''3973690''>with</span>
  <span m=''3973810''>a</span> <span m=''3973860''>square</span> <span m=''3974450''>of</span>
  <span m=''3974500''>one</span> <span m=''3974680''>size, and</span> <span m=''3974990''>you</span>
  <span m=''3975140''>shrink</span> <span m=''3975510''>both</span> <span m=''3975710''>dimensions</span>
  <span m=''3976160''>by</span> <span m=''3976320''>two.</span> <span m=''3977240''>And</span>
  <span m=''3977470''>you</span> <span m=''3977550''>get</span> <span m=''3977690''>a</span>
  <span m=''3977740''>four</span> <span m=''3978090''>by four checkerboard.</span>
  <span m=''3978540''>But</span> <span m=''3978670''>we</span> <span m=''3978770''>don''t</span>
  <span m=''3978920''>know</span> <span m=''3979230''>if</span> <span m=''3979360''>this</span>
  <span m=''3979530''>is</span> <span m=''3979630''>the</span> <span m=''3979720''>best</span>
  <span m=''3979960''>way</span> <span m=''3980060''>to</span> <span m=''3980140''>fold</span>
  <span m=''3980300''>a</span> <span m=''3980380''>checkerboard.</span> <span m=''3981310''>Be</span>
  <span m=''3981410''>nice</span> <span m=''3981660''>to</span> <span m=''3981770''>know.</span>
  <span m=''3982940''>And</span> <span m=''3985190''>this</span> <span m=''3985360''>has</span>
  <span m=''3985490''>been</span> <span m=''3985620''>studied</span> <span m=''3986890''>for</span>
  <span m=''3987150''>a</span> <span m=''3987230''>while.</span> <span m=''3988610''>And</span>
  <span m=''3989440''>this</span> <span m=''3989780''>is</span> <span m=''3989900''>not</span>
  <span m=''3990260''>the</span> <span m=''3990380''>standard</span> <span m=''3990820''>method</span>
  <span m=''3991110''>for</span> <span m=''3991220''>folding</span> <span m=''3991550''>a</span>
  <span m=''3991620''>checkerboard.</span> <span m=''3992500''>But</span> <span m=''3992620''>it''s</span>
  <span m=''3992710''>actually</span> <span m=''3993210''>pretty</span> <span m=''3993570''>efficient</span>
  <span m=''3994010''>which</span> <span m=''3994180''>is</span> <span m=''3994290''>kind</span>
  <span m=''3994490''>of</span> <span m=''3995480''>crazy.</span> </p><p><span m=''3997180''>So</span>
  <span m=''3997320''>you</span> <span m=''3997390''>take</span> <span m=''3997590''>a</span>
  <span m=''3997650''>square,</span> <span m=''3998520''>white</span> <span m=''3998770''>on</span>
  <span m=''3998840''>one</span> <span m=''3999000''>side</span> <span m=''3999280''>and</span>
  <span m=''3999390''>brown</span> <span m=''3999650''>on</span> <span m=''3999720''>the</span>
  <span m=''3999850''>other.</span> <span m=''4000620''>You</span> <span m=''4000780''>do</span>
  <span m=''4000930''>this</span> <span m=''4001230''>accordion</span> <span m=''4001700''>pleat.</span>
  <span m=''4002310''>You</span> <span m=''4002440''>get</span> <span m=''4002680''>a</span>
  <span m=''4002770''>bunch</span> <span m=''4003050''>of</span> <span m=''4003170''>nice</span>
  <span m=''4003530''>color</span> <span m=''4003860''>reversals,</span> <span m=''4005650''>bunch</span>
  <span m=''4005850''>of</span> <span m=''4005910''>squares.</span> <span m=''4006420''>And</span>
  <span m=''4006510''>then,</span> <span m=''4006610''>you</span> <span m=''4006690''>just</span>
  <span m=''4006940''>need</span> <span m=''4007120''>to</span> <span m=''4007400''>make</span>
  <span m=''4007700''>a</span> <span m=''4008380''>square</span> <span m=''4008900''>of</span>
  <span m=''4008960''>squares</span> <span m=''4010010''>from</span> <span m=''4010300''>that.</span>
  <span m=''4010910''>So</span> <span m=''4011060''>general</span> <span m=''4011370''>problem</span>
  <span m=''4011650''>is,</span> <span m=''4011760''>I</span> <span m=''4011800''>want</span>
  <span m=''4011950''>to</span> <span m=''4012000''>fold</span> <span m=''4012240''>an</span>
  <span m=''4012310''>n</span> <span m=''4012500''>by</span> <span m=''4012660''>n</span>
  <span m=''4012810''>checkerboard</span> <span m=''4013870''>from</span> <span m=''4014140''>the</span>
  <span m=''4014210''>smallest</span> <span m=''4014620''>possible</span> <span m=''4015010''>square.</span>
  </p><p><span m=''4015360''>How</span> <span m=''4015540''>big</span> <span m=''4015790''>does
  it</span> <span m=''4015900''>have</span> <span m=''4016060''>to</span> <span m=''4016160''>be</span>
  <span m=''4016520''>as</span> <span m=''4016690''>a</span> <span m=''4016760''>function</span>
  <span m=''4017090''>of</span> <span m=''4017180''>n?</span> <span m=''4018340''>And</span>
  <span m=''4018540''>the</span> <span m=''4018610''>standard</span> <span m=''4018970''>approach</span>
  <span m=''4020790''>is--</span> <span m=''4021560''>well,</span> <span m=''4021670''>this</span>
  <span m=''4021850''>is</span> <span m=''4021910''>the</span> <span m=''4022000''>first</span>
  <span m=''4022410''>method</span> <span m=''4023310''>that</span> <span m=''4023440''>does</span>
  <span m=''4023600''>it</span> <span m=''4023700''>for</span> <span m=''4023880''>all</span>
  <span m=''4024150''>n</span> <span m=''4024930''>in</span> <span m=''4025070''>a</span>
  <span m=''4025180''>general</span> <span m=''4025560''>simple</span> <span m=''4025940''>way.</span>
  <span m=''4026590''>But</span> <span m=''4026810''>the</span> <span m=''4026900''>practical</span>
  <span m=''4027430''>foldings</span> <span m=''4027820''>people</span> <span m=''4028120''>have
  designed,</span> <span m=''4028420''>like</span> <span m=''4028590''>four</span>
  <span m=''4028800''>by</span> <span m=''4028920''>four</span> <span m=''4029300''>and</span>
  <span m=''4029540''>there are a</span> <span m=''4029590''>bunch</span> <span m=''4029810''>of</span>
  <span m=''4029880''>eight by</span> <span m=''4030030''>eights</span> <span m=''4030380''>out</span>
  <span m=''4030530''>there,</span> <span m=''4031220''>are</span> <span m=''4031750''>little</span>
  <span m=''4031950''>more</span> <span m=''4032110''>efficient</span> <span m=''4032460''>than</span>
  <span m=''4032580''>this.</span> </p><p><span m=''4032850''>But</span> <span m=''4033300''>they</span>
  <span m=''4033390''>have</span> <span m=''4033510''>the</span> <span m=''4033590''>same</span>
  <span m=''4033800''>asymptotics</span> <span m=''4034410''>which</span> <span m=''4034705''>is</span>
  <span m=''4035320''>the</span> <span m=''4035440''>perimeter</span> <span m=''4035930''>of</span>
  <span m=''4036010''>the</span> <span m=''4036090''>square</span> <span m=''4036550''>you</span>
  <span m=''4036680''>start</span> <span m=''4037060''>with</span> <span m=''4037690''>has</span>
  <span m=''4037940''>to</span> <span m=''4038030''>be</span> <span m=''4038440''>about</span>
  <span m=''4038810''>twice</span> <span m=''4039750''>n</span> <span m=''4040000''>squared</span>
  <span m=''4040580''>to</span> <span m=''4040740''>make</span> <span m=''4040890''>an</span>
  <span m=''4041000''>n</span> <span m=''4041160''>by</span> <span m=''4041330''>n</span>
  <span m=''4042030''>checkerboard.</span> <span m=''4042600''>And</span> <span m=''4042780''>the</span>
  <span m=''4042880''>reason</span> <span m=''4043710''>that</span> <span m=''4043930''>is,</span>
  <span m=''4044235''>is</span> <span m=''4044540''>if</span> <span m=''4044680''>you</span>
  <span m=''4044800''>look</span> <span m=''4044950''>at</span> <span m=''4045010''>the</span>
  <span m=''4045110''>checkerboard</span> <span m=''4045590''>pattern,</span> <span
  m=''4047010''>we''re</span> <span m=''4047170''>trying</span> <span m=''4047540''>to</span>
  <span m=''4047610''>get</span> <span m=''4047850''>color</span> <span m=''4048160''>reversals</span>
  <span m=''4048820''>along</span> <span m=''4049180''>all</span> <span m=''4049700''>of</span>
  <span m=''4049790''>these</span> <span m=''4050060''>lines</span> <span m=''4050640''>between</span>
  <span m=''4051400''>the</span> <span m=''4051530''>red</span> <span m=''4052360''>and</span>
  <span m=''4052820''>the</span> <span m=''4053360''>white,</span> <span m=''4053960''>brown</span>
  <span m=''4054190''>and</span> <span m=''4054280''>white.</span> </p><p><span m=''4055680''>And</span>
  <span m=''4055920''>the</span> <span m=''4056010''>way</span> <span m=''4056160''>we''re</span>
  <span m=''4056270''>doing</span> <span m=''4056490''>that</span> <span m=''4056650''>here</span>
  <span m=''4056920''>is</span> <span m=''4056990''>we''re</span> <span m=''4057120''>taking</span>
  <span m=''4057430''>the</span> <span m=''4057500''>boundary</span> <span m=''4058060''>of</span>
  <span m=''4058140''>the</span> <span m=''4058230''>paper,</span> <span m=''4059020''>and</span>
  <span m=''4059260''>we''re</span> <span m=''4059370''>mapping</span> <span m=''4059860''>it</span>
  <span m=''4060020''>along</span> <span m=''4060720''>all</span> <span m=''4060940''>the</span>
  <span m=''4061020''>color</span> <span m=''4061280''>reversals.</span> <span m=''4062710''>And</span>
  <span m=''4062900''>if</span> <span m=''4062990''>you</span> <span m=''4063110''>work</span>
  <span m=''4063350''>out</span> <span m=''4063880''>how</span> <span m=''4064070''>much</span>
  <span m=''4064290''>color</span> <span m=''4064650''>reversal</span> <span m=''4065020''>is</span>
  <span m=''4065130''>there</span> <span m=''4065320''>in</span> <span m=''4065380''>an</span>
  <span m=''4065500''>n</span> <span m=''4065755''>by</span> <span m=''4066010''>n</span>
  <span m=''4066200''>thing,</span> <span m=''4066480''>it''s</span> <span m=''4066610''>about</span>
  <span m=''4067040''>twice</span> <span m=''4067380''>n</span> <span m=''4067530''>squared.</span>
  <span m=''4069200''>And</span> <span m=''4069400''>so</span> <span m=''4069540''>either</span>
  <span m=''4069820''>your</span> <span m=''4070000''>perimeter</span> <span m=''4070450''>has</span>
  <span m=''4070740''>to</span> <span m=''4070840''>be</span> <span m=''4071030''>at</span>
  <span m=''4071090''>least</span> <span m=''4071310''>that</span> <span m=''4071490''>large</span>
  <span m=''4072100''>if</span> <span m=''4072330''>you''re</span> <span m=''4072470''>going</span>
  <span m=''4072610''>to</span> <span m=''4072770''>cover</span> <span m=''4073160''>the</span>
  <span m=''4073260''>color</span> <span m=''4073580''>reversals</span> <span m=''4073940''>with</span>
  <span m=''4074080''>perimeter.</span> </p><p><span m=''4074960''>And</span> <span
  m=''4075100''>for</span> <span m=''4075320''>a</span> <span m=''4075370''>long</span>
  <span m=''4075560''>time,</span> <span m=''4075770''>we</span> <span m=''4075890''>thought</span>
  <span m=''4076120''>that</span> <span m=''4076260''>was</span> <span m=''4076430''>the</span>
  <span m=''4076510''>best</span> <span m=''4076830''>we</span> <span m=''4076920''>could</span>
  <span m=''4077090''>do</span> <span m=''4078130''>was</span> <span m=''4078310''>to</span>
  <span m=''4078410''>cover</span> <span m=''4079690''>color</span> <span m=''4079980''>reversals</span>
  <span m=''4080330''>with a</span> <span m=''4080460''>perimeter of</span> <span
  m=''4080820''>paper.</span> <span m=''4081090''>Of</span> <span m=''4081160''>course,</span>
  <span m=''4081480''>know</span> <span m=''4081660''>that</span> <span m=''4081800''>you</span>
  <span m=''4081920''>can</span> <span m=''4082070''>take</span> <span m=''4082840''>a</span>
  <span m=''4082970''>square</span> <span m=''4083210''>of</span> <span m=''4083260''>paper</span>
  <span m=''4083620''>make</span> <span m=''4083770''>the</span> <span m=''4083850''>perimeter</span>
  <span m=''4084230''>arbitrarily</span> <span m=''4084760''>large.</span> <span m=''4085630''>So</span>
  <span m=''4087000''>this</span> <span m=''4087170''>was</span> <span m=''4087330''>never</span>
  <span m=''4087630''>really</span> <span m=''4087880''>a</span> <span m=''4087950''>lower</span>
  <span m=''4088240''>bound.</span> <span m=''4088770''>We</span> <span m=''4088890''>never</span>
  <span m=''4089140''>really</span> <span m=''4089350''>knew</span> <span m=''4089610''>that</span>
  <span m=''4089810''>you</span> <span m=''4090280''>needed</span> <span m=''4090850''>2n</span>
  <span m=''4091200''>squared.</span> </p><p><span m=''4092890''>The</span> <span
  m=''4093090''>four by</span> <span m=''4093490''>four</span> <span m=''4093780''>achieves</span>
  <span m=''4094160''>2n</span> <span m=''4094410''>squared.</span> <span m=''4095440''>We</span>
  <span m=''4095620''>think</span> <span m=''4095820''>it''s</span> <span m=''4096010''>the</span>
  <span m=''4096109''>best</span> <span m=''4096930''>for</span> <span m=''4097060''>four</span>
  <span m=''4097250''>by</span> <span m=''4097370''>four,</span> <span m=''4098720''>but</span>
  <span m=''4098930''>we</span> <span m=''4099080''>proved</span> <span m=''4099359''>last</span>
  <span m=''4099779''>year--</span> <span m=''4100630''>this</span> <span m=''4100800''>is</span>
  <span m=''4100939''>with</span> <span m=''4102319''>Marty</span> <span m=''4102750''>and</span>
  <span m=''4103380''>[INAUDIBLE]</span> <span m=''4104250''>and</span> <span m=''4104390''>Robert</span>
  <span m=''4104660''>Lang--</span> <span m=''4105359''>that</span> <span m=''4105520''>you</span>
  <span m=''4105670''>can</span> <span m=''4105830''>do</span> <span m=''4105970''>better</span>
  <span m=''4106550''>and</span> <span m=''4106850''>get</span> <span m=''4107290''>perimeter</span>
  <span m=''4107640''>about</span> <span m=''4107910''>n</span> <span m=''4108100''>squared.</span>
  <span m=''4109130''>Now,</span> <span m=''4109180''>there</span> <span m=''4109279''>are</span>
  <span m=''4109340''>some</span> <span m=''4109510''>lower</span> <span m=''4109630''>order</span>
  <span m=''4109890''>terms</span> <span m=''4110220''>there,</span> <span m=''4110350''>the</span>
  <span m=''4110550''>order</span> <span m=''4110810''>n</span> <span m=''4111060''>parts.</span>
  <span m=''4111359''>So</span> <span m=''4111450''>this</span> <span m=''4111580''>is</span>
  <span m=''4111689''>really</span> <span m=''4111920''>only</span> <span m=''4112100''>practical</span>
  <span m=''4112510''>for</span> <span m=''4112640''>large</span> <span m=''4113050''>n.</span>
  </p><p><span m=''4113880''>I</span> <span m=''4114029''>think--</span> <span m=''4115649''>I''ll</span>
  <span m=''4115840''>elaborate</span> <span m=''4116240''>on</span> <span m=''4116350''>that</span>
  <span m=''4116470''>a</span> <span m=''4116529''>little</span> <span m=''4116710''>more</span>
  <span m=''4117324''>in a</span> <span m=''4117609''>moment.</span> <span m=''4118850''>But</span>
  <span m=''4119020''>here''s</span> <span m=''4119250''>the</span> <span m=''4119390''>idea.</span>
  <span m=''4119689''>Instead</span> <span m=''4120080''>of</span> <span m=''4120160''>visiting</span>
  <span m=''4120609''>all</span> <span m=''4120930''>the</span> <span m=''4122830''>boundaries</span>
  <span m=''4123609''>between</span> <span m=''4124029''>red</span> <span m=''4124250''>and</span>
  <span m=''4124330''>white</span> <span m=''4124550''>squares,</span> <span m=''4124960''>I</span>
  <span m=''4125060''>just</span> <span m=''4125319''>want</span> <span m=''4125439''>to</span>
  <span m=''4125479''>visit</span> <span m=''4125770''>the</span> <span m=''4125859''>squares</span>
  <span m=''4126250''>themselves.</span> <span m=''4127620''>So</span> <span m=''4127779''>if</span>
  <span m=''4127899''>I</span> <span m=''4128050''>could</span> <span m=''4128270''>fold</span>
  <span m=''4129460''>a,</span> <span m=''4129770''>in</span> <span m=''4130080''>this</span>
  <span m=''4130250''>case</span> <span m=''4130439''>a</span> <span m=''4130520''>rectangle</span>
  <span m=''4131060''>paper</span> <span m=''4131529''>into</span> <span m=''4131810''>this</span>
  <span m=''4132050''>shape</span> <span m=''4132830''>which</span> <span m=''4133040''>has</span>
  <span m=''4133550''>slits</span> <span m=''4134229''>down</span> <span m=''4134450''>the</span>
  <span m=''4134529''>sides,</span> <span m=''4135319''>and</span> <span m=''4135490''>it</span>
  <span m=''4135529''>has</span> <span m=''4135710''>these</span> <span m=''4135850''>flaps</span>
  <span m=''4136340''>hanging</span> <span m=''4136720''>out.</span> </p><p><span
  m=''4137250''>Now,</span> <span m=''4137390''>you''ve</span> <span m=''4137569''>seen</span>
  <span m=''4137979''>how</span> <span m=''4138140''>to</span> <span m=''4138210''>make</span>
  <span m=''4138390''>flaps</span> <span m=''4138710''>super</span> <span m=''4139040''>efficiently.</span>
  <span m=''4139620''>You</span> <span m=''4139760''>really</span> <span m=''4140000''>don''t</span>
  <span m=''4140180''>need</span> <span m=''4140330''>to</span> <span m=''4140800''>shrink</span>
  <span m=''4141130''>the</span> <span m=''4141229''>paper</span> <span m=''4141550''>by</span>
  <span m=''4141700''>very</span> <span m=''4141930''>much</span> <span m=''4142490''>to</span>
  <span m=''4142670''>make</span> <span m=''4142859''>this</span> <span m=''4143040''>pattern.</span>
  <span m=''4144370''>Then,</span> <span m=''4145120''>you</span> <span m=''4145270''>take</span>
  <span m=''4145760''>these</span> <span m=''4146229''>guys--</span> <span m=''4146870''>and</span>
  <span m=''4147050''>everything</span> <span m=''4147490''>is</span> <span m=''4147649''>white</span>
  <span m=''4147890''>side</span> <span m=''4148080''>up.</span> <span m=''4148779''>You</span>
  <span m=''4148899''>take</span> <span m=''4149240''>these</span> <span m=''4149850''>flaps,</span>
  <span m=''4150760''>fold</span> <span m=''4151100''>them</span> <span m=''4151260''>over.</span>
  <span m=''4153090''>They</span> <span m=''4153319''>become</span> <span m=''4153700''>brown.</span>
  </p><p><span m=''4155189''>And</span> <span m=''4155729''>these</span> <span m=''4156080''>guys</span>
  <span m=''4156370''>fall</span> <span m=''4156740''>over.</span> <span m=''4157229''>These</span>
  <span m=''4157460''>fall</span> <span m=''4157770''>down.</span> <span m=''4158470''>These</span>
  <span m=''4158640''>guys</span> <span m=''4158850''>fall</span> <span m=''4159090''>up.</span>
  <span m=''4159359''>You</span> <span m=''4159450''>can</span> <span m=''4159560''>actually</span>
  <span m=''4159779''>make</span> <span m=''4159970''>any</span> <span m=''4160210''>two</span>
  <span m=''4160370''>color</span> <span m=''4160649''>pixel</span> <span m=''4160950''>pattern</span>
  <span m=''4161330''>from</span> <span m=''4161500''>this</span> <span m=''4162120''>idea.</span>
  <span m=''4162770''>And</span> <span m=''4163040''>it</span> <span m=''4163120''>will</span>
  <span m=''4163260''>make</span> <span m=''4164350''>white</span> <span m=''4164630''>squares</span>
  <span m=''4164960''>on</span> <span m=''4165050''>top</span> <span m=''4165300''>of</span>
  <span m=''4165370''>the</span> <span m=''4165450''>brown</span> <span m=''4165819''>surface</span>
  <span m=''4166710''>that</span> <span m=''4166880''>you</span> <span m=''4167240''>folded.</span>
  <span m=''4168420''>So</span> <span m=''4168550''>this</span> <span m=''4168750''>is</span>
  <span m=''4168880''>the</span> <span m=''4169170''>starting</span> <span m=''4169569''>point.</span>
  <span m=''4169870''>You</span> <span m=''4169970''>just</span> <span m=''4170170''>fold</span>
  <span m=''4170520''>everything</span> <span m=''4170899''>over.</span> <span m=''4171140''>And
  you</span> <span m=''4171279''>get</span> <span m=''4171410''>your</span> <span
  m=''4171520''>checkerboard.</span> </p><p><span m=''4173350''>And</span> <span m=''4173590''>now,</span>
  <span m=''4173870''>essentially,</span> <span m=''4174279''>you''re</span> <span
  m=''4174390''>visiting</span> <span m=''4174850''>each</span> <span m=''4175029''>square</span>
  <span m=''4175580''>only</span> <span m=''4175760''>once</span> <span m=''4176760''>instead</span>
  <span m=''4177140''>of</span> <span m=''4177270''>the</span> <span m=''4177359''>boundary</span>
  <span m=''4177850''>edge</span> <span m=''4178040''>for</span> <span m=''4178220''>all</span>
  <span m=''4178359''>the</span> <span m=''4178439''>squares.</span> <span m=''4178850''>And</span>
  <span m=''4178960''>so</span> <span m=''4179090''>you</span> <span m=''4179200''>end</span>
  <span m=''4179319''>up</span> <span m=''4179430''>using</span> <span m=''4179740''>only</span>
  <span m=''4179960''>n</span> <span m=''4180080''>squared</span> <span m=''4180439''>instead
  of</span> <span m=''4180609''>twice</span> <span m=''4180950''>n</span> <span m=''4181080''>squared.</span>
  <span m=''4182040''>And</span> <span m=''4182130''>you</span> <span m=''4182229''>can</span>
  <span m=''4182350''>do</span> <span m=''4182479''>it</span> <span m=''4182550''>if</span>
  <span m=''4182649''>you</span> <span m=''4182740''>start</span> <span m=''4182990''>from
  a</span> <span m=''4183149''>square</span> <span m=''4183500''>also.</span> <span
  m=''4183779''>You</span> <span m=''4183930''>just</span> <span m=''4184160''>need</span>
  <span m=''4184319''>more</span> <span m=''4184529''>flaps.</span> <span m=''4187260''>And</span>
  <span m=''4188200''>there''s</span> <span m=''4188859''>a</span> <span m=''4189020''>bunch</span>
  <span m=''4189380''>of</span> <span m=''4189620''>tabs</span> <span m=''4190000''>sticking</span>
  <span m=''4190390''>up</span> <span m=''4190529''>here,</span> <span m=''4190920''>and</span>
  <span m=''4190990''>a</span> <span m=''4191029''>bunch</span> <span m=''4191260''>of</span>
  <span m=''4191350''>tabs</span> <span m=''4191649''>sticking</span> <span m=''4192000''>up</span>
  <span m=''4192109''>there.</span> </p><p><span m=''4192920''>You</span> <span m=''4193060''>can</span>
  <span m=''4193189''>fold</span> <span m=''4193390''>this</span> <span m=''4193520''>again</span>
  <span m=''4193729''>super efficiently,</span> <span m=''4194550''>using</span> <span
  m=''4195590''>all these</span> <span m=''4195690''>standard</span> <span m=''4196050''>techniques.</span>
  <span m=''4197590''>And</span> <span m=''4197790''>then,</span> <span m=''4197930''>you</span>
  <span m=''4198040''>make</span> <span m=''4198230''>a</span> <span m=''4198300''>checkerboard</span>
  <span m=''4199130''>twice</span> <span m=''4199510''>as</span> <span m=''4199640''>efficient</span>
  <span m=''4201190''>for</span> <span m=''4201380''>large</span> <span m=''4201670''>n</span>
  <span m=''4202260''>as</span> <span m=''4202830''>we''ve</span> <span m=''4203190''>previously</span>
  <span m=''4203660''>thought</span> <span m=''4203870''>possible.</span> <span m=''4204370''>Now,</span>
  <span m=''4204530''>we</span> <span m=''4204600''>still</span> <span m=''4204810''>don''t</span>
  <span m=''4204940''>know whether</span> <span m=''4205130''>this</span> <span m=''4205330''>is</span>
  <span m=''4205430''>optimal.</span> <span m=''4207200''>We</span> <span m=''4207380''>think</span>
  <span m=''4207600''>it</span> <span m=''4207700''>is.</span> <span m=''4208330''>But</span>
  <span m=''4209340''>we</span> <span m=''4210030''>thought</span> <span m=''4210280''>so</span>
  <span m=''4210430''>before</span> <span m=''4210900''>also.</span> <span m=''4214340''>Who</span>
  <span m=''4214630''>knows?</span> </p><p><span m=''4216640''>So</span> <span m=''4216830''>big</span>
  <span m=''4216970''>open</span> <span m=''4217250''>problem</span> <span m=''4217530''>is</span>
  <span m=''4217680''>[INAUDIBLE]</span> <span m=''4218450''>for</span> <span m=''4218610''>anything.</span>
  <span m=''4219410''>In</span> <span m=''4219560''>terms</span> <span m=''4219790''>of</span>
  <span m=''4219910''>actual</span> <span m=''4220290''>values</span> <span m=''4220620''>of</span>
  <span m=''4220700''>n,</span> <span m=''4221650''>for</span> <span m=''4222210''>n</span>
  <span m=''4222620''>bigger</span> <span m=''4222950''>than</span> <span m=''4223500''>16,</span>
  <span m=''4225270''>this</span> <span m=''4225510''>method</span> <span m=''4225870''>is</span>
  <span m=''4226030''>better</span> <span m=''4226380''>than</span> <span m=''4226720''>the</span>
  <span m=''4228340''>standard</span> <span m=''4228870''>approach.</span> <span m=''4231120''>Although</span>
  <span m=''4231340''>if</span> <span m=''4231440''>you</span> <span m=''4231580''>look</span>
  <span m=''4231810''>just</span> <span m=''4232040''>at</span> <span m=''4232160''>seamless--</span>
  <span m=''4235940''>so</span> <span m=''4236290''>seamless,</span> <span m=''4236830''>I</span>
  <span m=''4237010''>didn''t</span> <span m=''4237330''>mention,</span> <span m=''4237750''>but</span>
  <span m=''4237900''>we''re</span> <span m=''4238030''>going</span> <span m=''4238130''>to</span>
  <span m=''4238200''>talk</span> <span m=''4238410''>about it</span> <span m=''4238640''>more</span>
  <span m=''4238840''>in</span> <span m=''4238890''>a</span> <span m=''4238930''>moment.</span>
  </p><p><span m=''4239820''>When</span> <span m=''4240010''>I</span> <span m=''4240040''>make</span>
  <span m=''4240260''>a</span> <span m=''4240320''>square</span> <span m=''4240720''>of
  a</span> <span m=''4240760''>checkerboard,</span> <span m=''4241870''>I''d</span>
  <span m=''4242060''>really</span> <span m=''4242350''>like</span> <span m=''4243500''>this</span>
  <span m=''4243690''>to</span> <span m=''4243780''>be</span> <span m=''4243920''>a</span>
  <span m=''4244000''>single</span> <span m=''4244390''>panel of</span> <span m=''4244800''>paper</span>
  <span m=''4245160''>not</span> <span m=''4245450''>divided</span> <span m=''4245880''>into</span>
  <span m=''4246110''>little</span> <span m=''4246330''>panels.</span> <span m=''4247200''>And</span>
  <span m=''4247400''>like</span> <span m=''4247570''>in</span> <span m=''4247690''>this</span>
  <span m=''4247900''>checkerboard,</span> <span m=''4249200''>this</span> <span m=''4249450''>white</span>
  <span m=''4249690''>square</span> <span m=''4250030''>has</span> <span m=''4250610''>a</span>
  <span m=''4250660''>bunch</span> <span m=''4250890''>of</span> <span m=''4250940''>seems</span>
  <span m=''4251270''>on it.</span> <span m=''4251450''>It''s</span> <span m=''4251630''>made
  out</span> <span m=''4251840''>of</span> <span m=''4252180''>three</span> <span
  m=''4252570''>smaller</span> <span m=''4253090''>triangles.</span> <span m=''4254080''>And</span>
  <span m=''4254350''>that''s</span> <span m=''4254540''>not</span> <span m=''4254690''>so</span>
  <span m=''4254810''>nice.</span> </p><p><span m=''4255710''>This</span> <span m=''4255900''>method</span>
  <span m=''4256220''>is</span> <span m=''4256320''>seamless.</span> <span m=''4257240''>You</span>
  <span m=''4257340''>get</span> <span m=''4257480''>whole</span> <span m=''4258540''>panels</span>
  <span m=''4259220''>making</span> <span m=''4259520''>each</span> <span m=''4259700''>of</span>
  <span m=''4259780''>your</span> <span m=''4259900''>squares,</span> <span m=''4260230''>so</span>
  <span m=''4260370''>it</span> <span m=''4260420''>looks</span> <span m=''4260620''>a</span>
  <span m=''4260680''>little</span> <span m=''4260870''>prettier.</span> <span m=''4261930''>If</span>
  <span m=''4261990''>you</span> <span m=''4262090''>look</span> <span m=''4262230''>at</span>
  <span m=''4262290''>the</span> <span m=''4262370''>best</span> <span m=''4262980''>eight</span>
  <span m=''4263130''>by</span> <span m=''4263250''>eight</span> <span m=''4263550''>seamless</span>
  <span m=''4263930''>folding,</span> <span m=''4264450''>this</span> <span m=''4264680''>beats</span>
  <span m=''4265070''>the</span> <span m=''4265170''>best</span> <span m=''4265550''>seamless
  eight</span> <span m=''4265810''>by</span> <span m=''4266070''>eight</span> <span
  m=''4266330''>folding.</span> <span m=''4267550''>Although</span> <span m=''4268000''>it''s</span>
  <span m=''4268470''>rather</span> <span m=''4268810''>difficult to</span> <span
  m=''4269290''>fold.</span> <span m=''4269700''>Hasn''t</span> <span m=''4270020''>yet</span>
  <span m=''4270190''>been</span> <span m=''4270300''>folded.</span> <span m=''4271490''>That
  would</span> <span m=''4271640''>be a good</span> <span m=''4271910''>project</span>
  <span m=''4272350''>also.</span> <span m=''4276070''>Build</span> <span m=''4276350''>an</span>
  <span m=''4276460''>actual</span> <span m=''4276850''>checkerboard</span> <span
  m=''4277310''>with</span> <span m=''4277420''>this</span> <span m=''4277580''>method.</span>
  </p><p><span m=''4281450''>Questions?</span> <span m=''4284040''>Now,</span> <span
  m=''4284250''>I</span> <span m=''4284310''>want</span> <span m=''4284520''>to</span>
  <span m=''4284560''>move</span> <span m=''4284750''>to</span> <span m=''4284870''>the</span>
  <span m=''4284980''>general</span> <span m=''4285350''>case.</span> <span m=''4285810''>So</span>
  <span m=''4285980''>I</span> <span m=''4286060''>talked</span> <span m=''4286320''>a</span>
  <span m=''4286360''>little</span> <span m=''4286540''>bit</span> <span m=''4286660''>about</span>
  <span m=''4286890''>checkerboards</span> <span m=''4287700''>and</span> <span m=''4287910''>about</span>
  <span m=''4288220''>cubes.</span> <span m=''4289100''>Let''s</span> <span m=''4289270''>think</span>
  <span m=''4289420''>about</span> <span m=''4289630''>arbitrary</span> <span m=''4290150''>polyhedra.</span>
  <span m=''4291320''>And</span> <span m=''4291540''>this</span> <span m=''4291730''>is</span>
  <span m=''4291900''>the</span> <span m=''4292240''>Origamizer.</span> <span m=''4314340''>So</span>
  <span m=''4314750''>Origamizer''s</span> <span m=''4315850''>actually</span> <span
  m=''4316120''>two</span> <span m=''4316310''>things.</span> <span m=''4316880''>It''s</span>
  <span m=''4317050''>a</span> <span m=''4317100''>computer</span> <span m=''4317460''>program</span>
  <span m=''4317990''>for</span> <span m=''4318170''>Windows that</span> <span m=''4318520''>you</span>
  <span m=''4318730''>can</span> <span m=''4318850''>download,</span> <span m=''4320460''>and</span>
  <span m=''4321040''>it''s</span> <span m=''4321400''>an</span> <span m=''4321510''>algorithm.</span>
  </p><p><span m=''4322880''>And</span> <span m=''4323200''>they''re</span> <span
  m=''4323320''>not</span> <span m=''4323550''>quite</span> <span m=''4323810''>the</span>
  <span m=''4323890''>same.</span> <span m=''4324730''>So</span> <span m=''4324850''>there''s</span>
  <span m=''4325060''>original</span> <span m=''4326120''>computer</span> <span m=''4326470''>program</span>
  <span m=''4326990''>and</span> <span m=''4327090''>Tomohiro</span> <span m=''4327450''>Tachi</span>
  <span m=''4327850''>wrote</span> <span m=''4328040''>a</span> <span m=''4328090''>couple</span>
  <span m=''4328360''>papers</span> <span m=''4328700''>about</span> <span m=''4328990''>it.</span>
  <span m=''4329750''>That</span> <span m=''4330760''>program</span> <span m=''4331190''>does</span>
  <span m=''4331330''>not</span> <span m=''4331660''>always</span> <span m=''4332020''>work.</span>
  <span m=''4333020''>Doesn''t</span> <span m=''4333260''>make</span> <span m=''4333490''>every</span>
  <span m=''4333760''>polyhedron.</span> <span m=''4335140''>It</span> <span m=''4335270''>need</span>
  <span m=''4335490''>some</span> <span m=''4336700''>finesse</span> <span m=''4337280''>to</span>
  <span m=''4337400''>make</span> <span m=''4337610''>it</span> <span m=''4338100''>work,</span>
  <span m=''4338520''>but</span> <span m=''4338650''>it''s</span> <span m=''4338780''>super</span>
  <span m=''4339030''>efficient.</span> </p><p><span m=''4339990''>And it''s</span>
  <span m=''4340260''>practical.</span> <span m=''4340790''>He''s</span> <span m=''4340890''>made</span>
  <span m=''4341040''>lots</span> <span m=''4341250''>of</span> <span m=''4341310''>models</span>
  <span m=''4341630''>with</span> <span m=''4341800''>it</span> <span m=''4342440''>like</span>
  <span m=''4342690''>the</span> <span m=''4342770''>bunny</span> <span m=''4343060''>you''ve</span>
  <span m=''4343190''>seen</span> <span m=''4343460''>on</span> <span m=''4343590''>the</span>
  <span m=''4343780''>poster.</span> <span m=''4345450''>There''s</span> <span m=''4345710''>the</span>
  <span m=''4345850''>algorithm,</span> <span m=''4346520''>which</span> <span m=''4346610''>we</span>
  <span m=''4347190''>developed</span> <span m=''4347520''>together.</span> <span
  m=''4347980''>And</span> <span m=''4348130''>we</span> <span m=''4348240''>know</span>
  <span m=''4348870''>it''s</span> <span m=''4349180''>similar.</span> <span m=''4350520''>And</span>
  <span m=''4350700''>we</span> <span m=''4350800''>know</span> <span m=''4350990''>it</span>
  <span m=''4351060''>always</span> <span m=''4351370''>works.</span> <span m=''4352630''>But</span>
  <span m=''4353180''>it''s</span> <span m=''4353420''>a</span> <span m=''4353490''>little</span>
  <span m=''4353780''>bit</span> <span m=''4353990''>less</span> <span m=''4354250''>practical.</span>
  <span m=''4355910''>So</span> <span m=''4356490''>it''s--</span> <span m=''4358450''>theory''s</span>
  <span m=''4358810''>always</span> <span m=''4358960''>a</span> <span m=''4359010''>little</span>
  <span m=''4359170''>behind</span> <span m=''4359520''>practice,</span> <span m=''4360080''>let''s</span>
  <span m=''4360290''>say.</span> </p><p><span m=''4360460''>So</span> <span m=''4360620''>there''s</span>
  <span m=''4360830''>a</span> <span m=''4360890''>practical</span> <span m=''4361310''>thing</span>
  <span m=''4361490''>here.</span> <span m=''4362110''>There''s</span> <span m=''4362230''>also
  a</span> <span m=''4362500''>theoretically</span> <span m=''4363020''>guaranteed</span>
  <span m=''4363470''>thing</span> <span m=''4363660''>here.</span> <span m=''4364170''>They''re</span>
  <span m=''4364280''>not</span> <span m=''4364470''>quite</span> <span m=''4364740''>the</span>
  <span m=''4364790''>same,</span> <span m=''4365050''>but</span> <span m=''4365200''>they''re</span>
  <span m=''4365310''>very</span> <span m=''4365500''>similar.</span> <span m=''4366580''>I''m</span>
  <span m=''4366700''>going</span> <span m=''4366780''>to</span> <span m=''4366860''>tell</span>
  <span m=''4367030''>you</span> <span m=''4367200''>a</span> <span m=''4367230''>little.</span>
  <span m=''4367690''>I''ll</span> <span m=''4367810''>show</span> <span m=''4367920''>you</span>
  <span m=''4368040''>both,</span> <span m=''4368760''>basically.</span> <span m=''4370640''>But</span>
  <span m=''4370810''>the</span> <span m=''4370940''>idea</span> <span m=''4371240''>is,</span>
  <span m=''4374910''>a</span> <span m=''4375060''>practical</span> <span m=''4375540''>algorithm</span>
  <span m=''4376160''>to</span> <span m=''4376290''>fold</span> <span m=''4377340''>any</span>
  <span m=''4377810''>polyhedron.</span> </p><p><span m=''4391710''>And</span> <span
  m=''4391960''>practical</span> <span m=''4392440''>here</span> <span m=''4392640''>is</span>
  <span m=''4392730''>a</span> <span m=''4392780''>bit</span> <span m=''4393950''>vague.</span>
  <span m=''4394360''>We</span> <span m=''4394460''>don''t--</span> <span m=''4394790''>that''s</span>
  <span m=''4395010''>not</span> <span m=''4395170''>a</span> <span m=''4395910''>theorem.</span>
  <span m=''4396920''>We</span> <span m=''4397050''>don''t</span> <span m=''4397190''>know</span>
  <span m=''4397270''>how</span> <span m=''4397350''>to</span> <span m=''4397460''>define</span>
  <span m=''4397810''>practical</span> <span m=''4400210''>in</span> <span m=''4400390''>mathematics</span>
  <span m=''4401010''>anyway.</span> <span m=''4404550''>It</span> <span m=''4404590''>has</span>
  <span m=''4404770''>some</span> <span m=''4405000''>fun</span> <span m=''4405270''>features,</span>
  <span m=''4405660''>though,</span> <span m=''4406100''>mathematically.</span> <span
  m=''4407200''>One</span> <span m=''4407370''>is</span> <span m=''4407490''>that
  it''s</span> <span m=''4407690''>seamless.</span> <span m=''4409050''>So</span>
  <span m=''4409430''>for it</span> <span m=''4409630''>to</span> <span m=''4409730''>be</span>
  <span m=''4409850''>seamless,</span> <span m=''4410490''>I</span> <span m=''4410640''>need</span>
  <span m=''4410830''>to</span> <span m=''4410930''>assume</span> <span m=''4412160''>convex</span>
  <span m=''4413740''>faces.</span> </p><p><span m=''4416690''>So</span> <span m=''4416900''>faces</span>
  <span m=''4417360''>are</span> <span m=''4417470''>the</span> <span m=''4417610''>sides</span>
  <span m=''4418020''>of</span> <span m=''4418120''>the</span> <span m=''4418250''>polyhedron.</span>
  <span m=''4419130''>So</span> <span m=''4419270''>like</span> <span m=''4419420''>in</span>
  <span m=''4419500''>a</span> <span m=''4419530''>cube,</span> <span m=''4419960''>every</span>
  <span m=''4420200''>face is</span> <span m=''4420640''>a</span> <span m=''4420950''>square.</span>
  <span m=''4421890''>Those</span> <span m=''4422380''>are</span> <span m=''4422440''>convex.</span>
  <span m=''4423510''>And</span> <span m=''4423950''>provided</span> <span m=''4424400''>all</span>
  <span m=''4424530''>the</span> <span m=''4424610''>faces</span> <span m=''4424970''>are</span>
  <span m=''4425070''>convex,</span> <span m=''4425470''>if</span> <span m=''4425560''>they''re</span>
  <span m=''4425650''>not,</span> <span m=''4425930''>you have</span> <span m=''4426050''>to</span>
  <span m=''4426150''>cut</span> <span m=''4426350''>them</span> <span m=''4426500''>up</span>
  <span m=''4426680''>into</span> <span m=''4426900''>convex</span> <span m=''4427290''>pieces.</span>
  <span m=''4428920''>My</span> <span m=''4429130''>folding</span> <span m=''4429480''>will</span>
  <span m=''4429690''>be</span> <span m=''4430310''>seamless</span> <span m=''4430920''>in</span>
  <span m=''4431080''>that</span> <span m=''4431320''>it</span> <span m=''4431430''>will</span>
  <span m=''4431560''>be</span> <span m=''4431670''>covered</span> <span m=''4431970''>by</span>
  <span m=''4432585''>an</span> <span m=''4432850''>entire</span> <span m=''4433230''>piece</span>
  <span m=''4433410''>of</span> <span m=''4433500''>paper.</span> <span m=''4433740''>There</span>
  <span m=''4433870''>maybe</span> <span m=''4434180''>other</span> <span m=''4434350''>things</span>
  <span m=''4434610''>hidden</span> <span m=''4434860''>underneath.</span> </p><p><span
  m=''4436090''>But</span> <span m=''4437390''>there</span> <span m=''4437530''>won''t</span>
  <span m=''4437780''>be</span> <span m=''4437890''>any</span> <span m=''4438060''>visible</span>
  <span m=''4438460''>seems</span> <span m=''4438860''>on</span> <span m=''4439050''>the</span>
  <span m=''4439150''>top</span> <span m=''4439440''>side.</span> <span m=''4441300''>So</span>
  <span m=''4441560''>that''s</span> <span m=''4441820''>nice.</span> <span m=''4444870''>It''s</span>
  <span m=''4445060''>also</span> <span m=''4446450''>water</span> <span m=''4446790''>tight.</span>
  <span m=''4453290''>And</span> <span m=''4453520''>for</span> <span m=''4453600''>this,</span>
  <span m=''4453800''>I</span> <span m=''4453870''>have</span> <span m=''4454040''>an</span>
  <span m=''4454100''>illustration.</span> <span m=''4455700''>This</span> <span m=''4455940''>is</span>
  <span m=''4456050''>a</span> <span m=''4456110''>feature</span> <span m=''4456630''>missed</span>
  <span m=''4457120''>by</span> <span m=''4457320''>the</span> <span m=''4457410''>strip</span>
  <span m=''4457670''>method.</span> <span m=''4458140''>And</span> <span m=''4458340''>if</span>
  <span m=''4458440''>you''ve</span> <span m=''4458590''>always</span> <span m=''4458810''>felt</span>
  <span m=''4459020''>like</span> <span m=''4459220''>the</span> <span m=''4459310''>strip</span>
  <span m=''4459520''>method</span> <span m=''4459770''>of</span> <span m=''4459850''>making</span>
  <span m=''4460110''>anything</span> <span m=''4460450''>is</span> <span m=''4460570''>cheating,</span>
  <span m=''4461270''>here''s</span> <span m=''4461640''>a</span> <span m=''4461690''>nice</span>
  <span m=''4462310''>formal</span> <span m=''4462660''>sense</span> <span m=''4462980''>in</span>
  <span m=''4463030''>which</span> <span m=''4463200''>it''s</span> <span m=''4463300''>cheating.</span>
  </p><p><span m=''4465220''>We</span> <span m=''4465340''>didn''t</span> <span m=''4465850''>realize</span>
  <span m=''4466310''>it</span> <span m=''4466430''>until</span> <span m=''4466910''>we</span>
  <span m=''4467030''>start</span> <span m=''4467270''>talking</span> <span m=''4467560''>about</span>
  <span m=''4467760''>Origamizer</span> <span m=''4468560''>which</span> <span m=''4469050''>does</span>
  <span m=''4469230''>not</span> <span m=''4469440''>have</span> <span m=''4469640''>this</span>
  <span m=''4470350''>cheating</span> <span m=''4470800''>sense.</span> <span m=''4471820''>So</span>
  <span m=''4471840''>here</span> <span m=''4472270''>I''m</span> <span m=''4472440''>trying</span>
  <span m=''4472650''>to</span> <span m=''4472700''>make</span> <span m=''4472930''>a</span>
  <span m=''4473020''>3D</span> <span m=''4473410''>surface,</span> <span m=''4474980''>looks</span>
  <span m=''4475140''>like</span> <span m=''4475270''>a</span> <span m=''4475340''>saddle</span>
  <span m=''4475730''>surface,</span> <span m=''4477060''>by a</span> <span m=''4477340''>strip.</span>
  <span m=''4478590''>If</span> <span m=''4478780''>I</span> <span m=''4478850''>just</span>
  <span m=''4479100''>visited</span> <span m=''4479410''>the</span> <span m=''4479510''>guys</span>
  <span m=''4480030''>in</span> <span m=''4480200''>this</span> <span m=''4480310''>nice</span>
  <span m=''4480520''>zigzag</span> <span m=''4481020''>order,</span> <span m=''4481510''>which</span>
  <span m=''4481835''>I</span> <span m=''4482160''>know</span> <span m=''4482400''>is</span>
  <span m=''4482550''>possible,</span> <span m=''4483800''>I</span> <span m=''4483900''>get</span>
  <span m=''4484070''>all</span> <span m=''4484190''>these</span> <span m=''4484390''>slits</span>
  <span m=''4484930''>down</span> <span m=''4485140''>the</span> <span m=''4485220''>sides.</span>
  </p><p><span m=''4486020''>This</span> <span m=''4486180''>thing</span> <span m=''4486310''>would</span>
  <span m=''4486440''>not</span> <span m=''4486660''>hold</span> <span m=''4486940''>water.</span>
  <span m=''4487550''>If</span> <span m=''4487610''>you</span> <span m=''4487730''>poured</span>
  <span m=''4487970''>water</span> <span m=''4488280''>on</span> <span m=''4488440''>it,</span>
  <span m=''4488590''>it would</span> <span m=''4488730''>fall</span> <span m=''4489050''>through</span>
  <span m=''4489230''>all</span> <span m=''4489380''>the</span> <span m=''4489450''>cracks.</span>
  <span m=''4491270''>And</span> <span m=''4491770''>if</span> <span m=''4492020''>I</span>
  <span m=''4492110''>fold</span> <span m=''4492440''>it</span> <span m=''4492550''>right,</span>
  <span m=''4493850''>like</span> <span m=''4494030''>in</span> <span m=''4494120''>this</span>
  <span m=''4494320''>picture,</span> <span m=''4495110''>there</span> <span m=''4495240''>should</span>
  <span m=''4495440''>be</span> <span m=''4495590''>no</span> <span m=''4495810''>seems</span>
  <span m=''4496160''>in</span> <span m=''4496260''>here.</span> <span m=''4496690''>The</span>
  <span m=''4496800''>square,</span> <span m=''4497600''>the</span> <span m=''4497700''>boundary</span>
  <span m=''4498190''>of</span> <span m=''4498270''>the</span> <span m=''4498350''>squares</span>
  <span m=''4498990''>is</span> <span m=''4499280''>what''s</span> <span m=''4499510''>drawn</span>
  <span m=''4499760''>in</span> <span m=''4499850''>red.</span> <span m=''4500450''>So</span>
  <span m=''4500610''>here</span> <span m=''4500730''>the</span> <span m=''4500850''>boundary</span>
  <span m=''4501320''>of</span> <span m=''4501410''>your</span> <span m=''4501560''>piece</span>
  <span m=''4501770''>of</span> <span m=''4501850''>paper</span> <span m=''4502740''>gets</span>
  <span m=''4503020''>mapped</span> <span m=''4503340''>all</span> <span m=''4503640''>over</span>
  <span m=''4503770''>the</span> <span m=''4503880''>place.</span> <span m=''4504160''>So
  it''s</span> <span m=''4504300''>lots</span> <span m=''4504530''>of</span> <span
  m=''4504600''>holes.</span> </p><p><span m=''4505600''>Here,</span> <span m=''4506060''>I</span>
  <span m=''4506120''>want</span> <span m=''4506340''>the</span> <span m=''4506410''>boundary</span>
  <span m=''4506900''>of</span> <span m=''4506970''>the</span> <span m=''4507060''>paper</span>
  <span m=''4507480''>to</span> <span m=''4507610''>be</span> <span m=''4507730''>the</span>
  <span m=''4507820''>same</span> <span m=''4508270''>as</span> <span m=''4508400''>the</span>
  <span m=''4508480''>boundary</span> <span m=''4509470''>of</span> <span m=''4509740''>the</span>
  <span m=''4509850''>surface.</span> <span m=''4511600''>So</span> <span m=''4511800''>the</span>
  <span m=''4511940''>only</span> <span m=''4512230''>place</span> <span m=''4512480''>the</span>
  <span m=''4512570''>water</span> <span m=''4512810''>to</span> <span m=''4512940''>run</span>
  <span m=''4513110''>off</span> <span m=''4513310''>is</span> <span m=''4513450''>at</span>
  <span m=''4513620''>the</span> <span m=''4513720''>edge.</span> <span m=''4514980''>I</span>
  <span m=''4515060''>mean,</span> <span m=''4515300''>obviously,</span> <span m=''4515810''>this</span>
  <span m=''4515990''>thing</span> <span m=''4516140''>is</span> <span m=''4516240''>not</span>
  <span m=''4516430''>a</span> <span m=''4517120''>closed</span> <span m=''4517770''>solid.</span>
  <span m=''4518690''>But</span> <span m=''4518820''>if</span> <span m=''4518910''>you</span>
  <span m=''4519020''>actually</span> <span m=''4519270''>made</span> <span m=''4519440''>a</span>
  <span m=''4519480''>cube,</span> <span m=''4520840''>you''re</span> <span m=''4520970''>still</span>
  <span m=''4521200''>going</span> <span m=''4521310''>to</span> <span m=''4521360''>get</span>
  <span m=''4521520''>some</span> <span m=''4521690''>edge</span> <span m=''4521980''>because</span>
  <span m=''4522110''>the</span> <span m=''4522190''>boundary</span> <span m=''4522510''>paper</span>
  <span m=''4522760''>has</span> <span m=''4522890''>to</span> <span m=''4522950''>go</span>
  <span m=''4523070''>somewhere.</span> </p><p><span m=''4524090''>But</span> <span
  m=''4524200''>if</span> <span m=''4524280''>you</span> <span m=''4524390''>then</span>
  <span m=''4524590''>sewed</span> <span m=''4524900''>up</span> <span m=''4525030''>the</span>
  <span m=''4525150''>edge,</span> <span m=''4526440''>it</span> <span m=''4526530''>would</span>
  <span m=''4526850''>totally</span> <span m=''4527230''>hold</span> <span m=''4527440''>water.</span>
  <span m=''4530220''>So</span> <span m=''4530310''>that</span> <span m=''4530640''>is</span>
  <span m=''4530880''>the</span> <span m=''4531100''>informal</span> <span m=''4532140''>version
  of</span> <span m=''4532430''>watertight.</span> <span m=''4533390''>The</span>
  <span m=''4533480''>formal</span> <span m=''4533810''>version</span> <span m=''4534230''>is</span>
  <span m=''4535900''>the</span> <span m=''4535950''>boundary</span> <span m=''4536470''>of</span>
  <span m=''4536550''>the</span> <span m=''4536620''>paper</span> <span m=''4542400''>maps</span>
  <span m=''4545560''>within</span> <span m=''4546520''>some</span> <span m=''4546820''>tiny</span>
  <span m=''4547230''>distance</span> <span m=''4547890''>epsilon</span> <span m=''4549350''>of</span>
  <span m=''4549730''>the</span> <span m=''4549810''>boundary</span> <span m=''4550180''>of</span>
  <span m=''4550260''>the</span> <span m=''4550340''>surface,</span> <span m=''4551100''>boundary
  of</span> <span m=''4551390''>the</span> <span m=''4551640''>polyhedron.</span>
  </p><p><span m=''4558470''>And</span> <span m=''4558600''>here,</span> <span m=''4559850''>when</span>
  <span m=''4560090''>I</span> <span m=''4560200''>say</span> <span m=''4560440''>polyhedron,</span>
  <span m=''4562260''>I</span> <span m=''4562380''>really</span> <span m=''4562730''>means</span>
  <span m=''4562980''>something</span> <span m=''4563520''>that''s</span> <span m=''4564610''>topologically</span>
  <span m=''4565490''>a</span> <span m=''4565560''>disk.</span> <span m=''4572770''>Brief</span>
  <span m=''4573060''>topology.</span> <span m=''4575410''>This</span> <span m=''4575600''>is</span>
  <span m=''4575720''>a</span> <span m=''4575780''>disk.</span> <span m=''4578050''>This</span>
  <span m=''4578120''>is</span> <span m=''4578260''>a</span> <span m=''4578340''>disk.</span>
  <span m=''4580730''>This</span> <span m=''4583260''>is</span> <span m=''4583390''>not</span>
  <span m=''4583600''>a</span> <span m=''4583650''>disk.</span> <span m=''4588520''>Cube</span>
  <span m=''4589060''>is</span> <span m=''4589200''>not</span> <span m=''4589410''>a
  disk.</span> <span m=''4590586''>It''s a</span> <span m=''4590980''>sphere.</span>
  <span m=''4594590''>This</span> <span m=''4595320''>is</span> <span m=''4595480''>a</span>
  <span m=''4595560''>disk.</span> <span m=''4596010''>A</span> <span m=''4596070''>piece</span>
  <span m=''4596300''>of</span> <span m=''4596360''>paper</span> <span m=''4596730''>is</span>
  <span m=''4596820''>a</span> <span m=''4596910''>disk.</span> <span m=''4597320''>So</span>
  <span m=''4597470''>really</span> <span m=''4597720''>the</span> <span m=''4597840''>only</span>
  <span m=''4598060''>things</span> <span m=''4598220''>you</span> <span m=''4598310''>could</span>
  <span m=''4598450''>fold</span> <span m=''4598660''>topologically</span> <span m=''4599390''>in</span>
  <span m=''4599470''>a</span> <span m=''4599520''>pure</span> <span m=''4599810''>sense</span>
  <span m=''4600230''>in</span> <span m=''4600340''>a</span> <span m=''4600400''>water</span>
  <span m=''4600720''>tight</span> <span m=''4600980''>sense</span> <span m=''4601890''>are</span>
  <span m=''4602020''>disks.</span> </p><p><span m=''4603270''>You</span> <span m=''4603400''>can''t</span>
  <span m=''4603930''>glue</span> <span m=''4604180''>things</span> <span m=''4604440''>together.</span>
  <span m=''4604900''>That''s</span> <span m=''4605060''>not</span> <span m=''4605600''>in</span>
  <span m=''4605770''>the</span> <span m=''4605860''>rules.</span> <span m=''4606760''>So</span>
  <span m=''4606900''>I</span> <span m=''4606980''>can''t</span> <span m=''4607260''>make--</span>
  <span m=''4607600''>I</span> <span m=''4607690''>could</span> <span m=''4608030''>fold</span>
  <span m=''4608520''>this.</span> <span m=''4609550''>But</span> <span m=''4609740''>I''d</span>
  <span m=''4609810''>have</span> <span m=''4610070''>to</span> <span m=''4610180''>have</span>
  <span m=''4610390''>an</span> <span m=''4610520''>extra</span> <span m=''4610860''>seem</span>
  <span m=''4611150''>somewhere</span> <span m=''4611910''>in</span> <span m=''4612090''>order</span>
  <span m=''4612240''>to</span> <span m=''4612360''>make</span> <span m=''4612610''>this</span>
  <span m=''4613360''>thing</span> <span m=''4613660''>just</span> <span m=''4613900''>be</span>
  <span m=''4614020''>a</span> <span m=''4614070''>disk.</span> <span m=''4614730''>I</span>
  <span m=''4614890''>could</span> <span m=''4615060''>fold</span> <span m=''4615270''>a</span>
  <span m=''4615340''>cube.</span> <span m=''4616160''>But</span> <span m=''4616300''>I</span>
  <span m=''4616340''>have</span> <span m=''4616590''>to</span> <span m=''4616690''>have</span>
  <span m=''4616880''>some</span> <span m=''4617060''>seem</span> <span m=''4617990''>somewhere.</span>
  <span m=''4618950''>Here--</span> <span m=''4619350''>the</span> <span m=''4619690''>top--</span>
  <span m=''4620600''>a</span> <span m=''4620730''>square</span> <span m=''4621060''>gets</span>
  <span m=''4621230''>cut</span> <span m=''4621390''>into</span> <span m=''4621560''>four</span>
  <span m=''4621770''>pieces</span> <span m=''4622840''>in</span> <span m=''4623010''>order</span>
  <span m=''4623150''>to</span> <span m=''4623270''>make</span> <span m=''4623490''>it</span>
  <span m=''4623560''>into</span> <span m=''4623770''>a</span> <span m=''4623850''>disk.</span>
  </p><p><span m=''4624280''>Any</span> <span m=''4625200''>higher</span> <span m=''4625480''>topology</span>
  <span m=''4626090''>can</span> <span m=''4626350''>be</span> <span m=''4626660''>cut</span>
  <span m=''4626900''>down</span> <span m=''4627270''>and</span> <span m=''4627390''>made</span>
  <span m=''4627560''>a</span> <span m=''4627600''>disk.</span> <span m=''4628590''>So</span>
  <span m=''4628740''>this</span> <span m=''4628900''>is</span> <span m=''4628950''>still</span>
  <span m=''4629150''>universal.</span> <span m=''4629770''>But</span> <span m=''4629900''>in</span>
  <span m=''4629980''>terms</span> <span m=''4630180''>of</span> <span m=''4630280''>the</span>
  <span m=''4630380''>water</span> <span m=''4630550''>tightness,</span> <span m=''4630980''>you
  have</span> <span m=''4631110''>to</span> <span m=''4631220''>think</span> <span
  m=''4631400''>about</span> <span m=''4631610''>the</span> <span m=''4631690''>disk</span>
  <span m=''4631990''>version.</span> </p><p><span m=''4634270''>AUDIENCE: Erik?</span>
  </p><p><span m=''4635230''>PROFESSOR: Yes.</span> </p><p><span m=''4635660''>AUDIENCE:
  Even</span> <span m=''4636090''>when</span> <span m=''4636426''>you</span> <span
  m=''4636762''>go</span> <span m=''4637100''>back and</span> <span m=''4637200''>forth</span>
  <span m=''4637620''>with the</span> <span m=''4638104''>script</span> <span m=''4638588''>method,</span>
  <span m=''4639072''>you could</span> <span m=''4639556''>argue that</span> <span
  m=''4640040''>that was</span> <span m=''4640524''>topologically</span> <span m=''4641008''>a</span>
  <span m=''4641492''>disk.</span> </p><p><span m=''4641980''>PROFESSOR: Oh,</span>
  <span m=''4642140''>yeah.</span> <span m=''4642720''>Anything,</span> <span m=''4643360''>any</span>
  <span m=''4643590''>folding</span> <span m=''4643940''>you</span> <span m=''4644030''>make</span>
  <span m=''4644270''>is</span> <span m=''4644350''>still</span> <span m=''4644560''>topologically</span>
  <span m=''4645025''>a</span> <span m=''4645490''>disk.</span> <span m=''4645650''>This
  is</span> <span m=''4645760''>making</span> <span m=''4646100''>a</span> <span m=''4646160''>disk.</span>
  <span m=''4646940''>But</span> <span m=''4647060''>it''s</span> <span m=''4647230''>doesn''t</span>
  <span m=''4647650''>preserve</span> <span m=''4647980''>the</span> <span m=''4648060''>boundary.</span>
  </p><p><span m=''4649060''>AUDIENCE: It</span> <span m=''4649440''>what?</span>
  </p><p><span m=''4649820''>PROFESSOR: It''s</span> <span m=''4649900''>not</span>
  <span m=''4650090''>preserving</span> <span m=''4650470''>the</span> <span m=''4650560''>boundary.</span>
  <span m=''4650980''>So</span> <span m=''4651100''>yeah.</span> <span m=''4651340''>Any</span>
  <span m=''4651640''>origami,</span> <span m=''4652490''>you''re</span> <span m=''4652620''>still</span>
  <span m=''4652900''>disk</span> <span m=''4653160''>like,</span> <span m=''4653620''>and</span>
  <span m=''4654070''>you''re</span> <span m=''4654260''>watertight</span> <span m=''4654990''>for</span>
  <span m=''4655200''>some</span> <span m=''4655560''>disk</span> <span m=''4655840''>surface.</span>
  <span m=''4656300''>But</span> <span m=''4656430''>I</span> <span m=''4656590''>want</span>
  <span m=''4656770''>to</span> <span m=''4656810''>make</span> <span m=''4657350''>this</span>
  <span m=''4657840''>disk</span> <span m=''4658120''>surface</span> <span m=''4658490''>with</span>
  <span m=''4658730''>that</span> <span m=''4658990''>boundary.</span> <span m=''4660520''>And</span>
  <span m=''4661400''>watertightness</span> <span m=''4662060''>is</span> <span m=''4662180''>supposed</span>
  <span m=''4662360''>to</span> <span m=''4662440''>match</span> <span m=''4662900''>the</span>
  <span m=''4663010''>given</span> <span m=''4663380''>boundary.</span> <span m=''4664310''>But</span>
  <span m=''4664480''>that</span> <span m=''4664900''>boundary</span> <span m=''4665190''>must</span>
  <span m=''4665600''>form</span> <span m=''4665860''>a</span> <span m=''4665910''>disk.</span>
  <span m=''4666270''>That''s</span> <span m=''4666470''>the</span> <span m=''4666560''>point.</span>
  <span m=''4666980''>I</span> <span m=''4667070''>can''t</span> <span m=''4667400''>say,</span>
  <span m=''4667740''>oh,</span> <span m=''4667900''>there''s</span> <span m=''4668090''>no</span>
  <span m=''4668260''>boundary</span> <span m=''4668620''>in a</span> <span m=''4668720''>cube.</span>
  <span m=''4668950''>So</span> <span m=''4669100''>you</span> <span m=''4669260''>have--</span>
  <span m=''4670235''>so the boundary of</span> <span m=''4670490''>paper</span> <span
  m=''4670740''>goes</span> <span m=''4670940''>nowhere.</span> <span m=''4671490''>That''s</span>
  <span m=''4671700''>not</span> <span m=''4671970''>allowed.</span> </p><p><span
  m=''4673530''>So</span> <span m=''4673680''>you</span> <span m=''4673740''>get</span>
  <span m=''4673880''>to</span> <span m=''4673950''>specify</span> <span m=''4674235''>it,</span>
  <span m=''4674520''>but it</span> <span m=''4674760''>has</span> <span m=''4674970''>to</span>
  <span m=''4675030''>be</span> <span m=''4675180''>a</span> <span m=''4675220''>disk.</span>
  <span m=''4677892''>I''m going to</span> <span m=''4678270''>wave</span> <span m=''4678600''>my</span>
  <span m=''4678810''>hand</span> <span m=''4679030''>some</span> <span m=''4679190''>more.</span>
  <span m=''4680070''>There''s</span> <span m=''4680320''>another</span> <span m=''4680620''>feature</span>
  <span m=''4680980''>which</span> <span m=''4681160''>you</span> <span m=''4681270''>can</span>
  <span m=''4681410''>see</span> <span m=''4681590''>in</span> <span m=''4681690''>this</span>
  <span m=''4681850''>picture.</span> <span m=''4682140''>This</span> <span m=''4682350''>is</span>
  <span m=''4682730''>a</span> <span m=''4682910''>schematic</span> <span m=''4683470''>of</span>
  <span m=''4683530''>what</span> <span m=''4683700''>Origamizer</span> <span m=''4684590''>would</span>
  <span m=''4684760''>produce</span> <span m=''4685610''>which</span> <span m=''4685860''>is</span>
  <span m=''4685980''>that</span> <span m=''4686150''>there''s</span> <span m=''4686340''>some</span>
  <span m=''4686590''>extra</span> <span m=''4686980''>stuff</span> <span m=''4687690''>underneath.</span>
  </p><p><span m=''4689510''>It''s</span> <span m=''4690230''>slightly</span> <span
  m=''4690600''>lighter</span> <span m=''4690910''>because</span> <span m=''4691100''>it''s</span>
  <span m=''4691240''>on</span> <span m=''4691360''>the</span> <span m=''4691450''>bottom</span>
  <span m=''4691820''>side</span> <span m=''4692230''>there.</span> <span m=''4693020''>But</span>
  <span m=''4693120''>you</span> <span m=''4693200''>can</span> <span m=''4693350''>see</span>
  <span m=''4693480''>along</span> <span m=''4693770''>every</span> <span m=''4694190''>edge,</span>
  <span m=''4694850''>these</span> <span m=''4695070''>are</span> <span m=''4695110''>the</span>
  <span m=''4695260''>edges</span> <span m=''4695560''>of</span> <span m=''4695640''>the</span>
  <span m=''4695730''>actual</span> <span m=''4696190''>polyhedron.</span> <span m=''4696770''>And</span>
  <span m=''4696910''>then,</span> <span m=''4697020''>there''s</span> <span m=''4697200''>these</span>
  <span m=''4697440''>extra</span> <span m=''4697810''>little</span> <span m=''4698150''>tabs,</span>
  <span m=''4698650''>extra</span> <span m=''4698950''>flaps</span> <span m=''4700020''>on</span>
  <span m=''4700160''>the</span> <span m=''4700300''>underside.</span> <span m=''4701190''>This</span>
  <span m=''4701350''>is</span> <span m=''4701470''>actually</span> <span m=''4701770''>necessary.</span>
  <span m=''4702440''>If</span> <span m=''4702610''>you</span> <span m=''4702770''>want</span>
  <span m=''4703350''>watertightness,</span> <span m=''4704160''>you</span> <span
  m=''4704270''>can''t</span> <span m=''4704600''>fold</span> <span m=''4704850''>exactly</span>
  <span m=''4705400''>that</span> <span m=''4705570''>polyhedron.</span> </p><p><span
  m=''4707100''>You</span> <span m=''4707260''>fold</span> <span m=''4707730''>a</span>
  <span m=''4707810''>slightly</span> <span m=''4708280''>thickened</span> <span m=''4708520''>version.</span>
  <span m=''4709720''>But</span> <span m=''4709900''>you</span> <span m=''4710030''>can</span>
  <span m=''4710190''>keep</span> <span m=''4710430''>all</span> <span m=''4710600''>those</span>
  <span m=''4710780''>flaps</span> <span m=''4711100''>on</span> <span m=''4711190''>one</span>
  <span m=''4711440''>side.</span> <span m=''4711980''>So</span> <span m=''4711990''>if</span>
  <span m=''4712070''>you''re</span> <span m=''4712190''>making</span> <span m=''4712490''>something</span>
  <span m=''4712780''>like</span> <span m=''4712980''>a</span> <span m=''4713020''>cube,</span>
  <span m=''4714520''>you</span> <span m=''4714610''>can</span> <span m=''4714730''>put</span>
  <span m=''4714860''>all</span> <span m=''4714980''>the</span> <span m=''4715060''>garbage</span>
  <span m=''4715360''>on</span> <span m=''4715450''>the</span> <span m=''4715560''>inside</span>
  <span m=''4715835''>where</span> <span m=''4716110''>no</span> <span m=''4716210''>one
  can</span> <span m=''4716350''>see</span> <span m=''4716660''>it.</span> <span m=''4718320''>So</span>
  <span m=''4718480''>there''s</span> <span m=''4719150''>another</span> <span m=''4719450''>feature</span>
  <span m=''4719780''>here</span> <span m=''4720490''>is</span> <span m=''4720730''>we</span>
  <span m=''4720850''>get</span> <span m=''4721800''>a</span> <span m=''4721900''>little</span>
  <span m=''4722190''>extra.</span> </p><p><span m=''4728200''>And</span> <span m=''4728310''>that''s</span>
  <span m=''4728560''>necessary</span> <span m=''4729100''>if</span> <span m=''4729160''>you</span>
  <span m=''4729270''>want</span> <span m=''4729510''>watertightness.</span> <span
  m=''4730880''>And</span> <span m=''4731090''>it''s</span> <span m=''4731190''>sort</span>
  <span m=''4731390''>of</span> <span m=''4731480''>the</span> <span m=''4731570''>trick</span>
  <span m=''4731940''>that</span> <span m=''4732090''>makes</span> <span m=''4732410''>all</span>
  <span m=''4732650''>of</span> <span m=''4732760''>this</span> <span m=''4733050''>possible</span>
  <span m=''4733600''>and</span> <span m=''4733690''>efficient</span> <span m=''4734150''>and</span>
  <span m=''4734280''>so</span> <span m=''4734430''>on.</span> <span m=''4737570''>So</span>
  <span m=''4738150''>the</span> <span m=''4738560''>high</span> <span m=''4738770''>level</span>
  <span m=''4739060''>idea</span> <span m=''4739620''>of</span> <span m=''4740100''>Origamizer</span>
  <span m=''4740455''>is</span> <span m=''4740810''>we''re</span> <span m=''4740890''>going</span>
  <span m=''4740980''>to</span> <span m=''4741050''>say,</span> <span m=''4741840''>there''s</span>
  <span m=''4742010''>all</span> <span m=''4742190''>these</span> <span m=''4742510''>faces</span>
  <span m=''4743030''>that</span> <span m=''4743160''>we</span> <span m=''4743310''>need</span>
  <span m=''4743640''>to</span> <span m=''4744720''>make.</span> <span m=''4745780''>So</span>
  <span m=''4745930''>just</span> <span m=''4746350''>plop</span> <span m=''4746650''>them</span>
  <span m=''4746800''>down</span> <span m=''4747050''>on</span> <span m=''4747120''>the</span>
  <span m=''4747200''>piece</span> <span m=''4747430''>of</span> <span m=''4747490''>paper</span>
  <span m=''4747810''>somewhere.</span> <span m=''4749010''>And</span> <span m=''4749150''>then,</span>
  <span m=''4749350''>fold</span> <span m=''4749760''>away</span> <span m=''4750020''>the</span>
  <span m=''4750160''>excess.</span> <span m=''4751390''>Get</span> <span m=''4751520''>rid</span>
  <span m=''4751660''>of</span> <span m=''4751770''>it</span> <span m=''4752350''>by</span>
  <span m=''4752610''>tucking.</span> </p><p><span m=''4753850''>And</span> <span
  m=''4754120''>that</span> <span m=''4754400''>excess</span> <span m=''4754820''>paper</span>
  <span m=''4755200''>is</span> <span m=''4755310''>going</span> <span m=''4755440''>to</span>
  <span m=''4755510''>get</span> <span m=''4755700''>mapped</span> <span m=''4756060''>into</span>
  <span m=''4756270''>these</span> <span m=''4756550''>little</span> <span m=''4757560''>chunks</span>
  <span m=''4758100''>here.</span> <span m=''4759480''>And</span> <span m=''4760230''>maybe</span>
  <span m=''4760490''>I''ll</span> <span m=''4760570''>show</span> <span m=''4760740''>you</span>
  <span m=''4761480''>a</span> <span m=''4761520''>demo.</span> <span m=''4768110''>So</span>
  <span m=''4768390''>you</span> <span m=''4768560''>takes</span> <span m=''4768930''>something</span>
  <span m=''4769200''>like--</span> <span m=''4771430''>this</span> <span m=''4771600''>is</span>
  <span m=''4771690''>similar</span> <span m=''4772120''>to</span> <span m=''4772270''>the</span>
  <span m=''4772360''>thing</span> <span m=''4772590''>I was</span> <span m=''4772720''>showing.</span>
  <span m=''4774510''>And</span> <span m=''4775310''>I</span> <span m=''4775610''>forgot
  a</span> <span m=''4776070''>mouse.</span> <span m=''4780610''>There</span> <span
  m=''4780900''>are</span> <span m=''4780930''>all</span> <span m=''4781030''>the</span>
  <span m=''4781100''>faces</span> <span m=''4781520''>in</span> <span m=''4781600''>the</span>
  <span m=''4781690''>plane.</span> </p><p><span m=''4782660''>And</span> <span m=''4782850''>they''ve</span>
  <span m=''4782990''>conveniently</span> <span m=''4783700''>already</span> <span
  m=''4784230''>been</span> <span m=''4785060''>arranged.</span> <span m=''4785490''>I</span>
  <span m=''4785560''>can''t</span> <span m=''4785890''>zoom</span> <span m=''4786150''>out</span>
  <span m=''4786340''>because</span> <span m=''4786590''>I</span> <span m=''4786880''>lack</span>
  <span m=''4787720''>scroll</span> <span m=''4788020''>wheel.</span> <span m=''4788720''>But</span>
  <span m=''4789970''>there''s</span> <span m=''4791110''>a</span> <span m=''4791770''>square</span>
  <span m=''4794240''>that</span> <span m=''4794650''>makes</span> <span m=''4795030''>the--</span>
  <span m=''4795345''>yeah, or a</span> <span m=''4795660''>multi-touch</span> <span
  m=''4796090''>trackpad.</span> <span m=''4797460''>Sorry.</span> <span m=''4799300''>And</span>
  <span m=''4799510''>all</span> <span m=''4799700''>the</span> <span m=''4799800''>faces</span>
  <span m=''4800300''>are</span> <span m=''4800390''>just</span> <span m=''4800610''>there.</span>
  <span m=''4800900''>And</span> <span m=''4800980''>then</span> <span m=''4801060''>there''s</span>
  <span m=''4801230''>this</span> <span m=''4801410''>extra</span> <span m=''4801760''>stuff.</span>
  <span m=''4802350''>And</span> <span m=''4802560''>now</span> <span m=''4802770''>I</span>
  <span m=''4802900''>say--</span> <span m=''4805360''>I</span> <span m=''4805410''>should</span>
  <span m=''4805560''>probably</span> <span m=''4805810''>do</span> <span m=''4805900''>this,</span>
  <span m=''4806180''>too.</span> <span m=''4806760''>Maybe</span> <span m=''4807150''>not.</span>
  <span m=''4808130''>Well, all</span> <span m=''4808450''>right.</span> </p><p><span
  m=''4809520''>And</span> <span m=''4809940''>then</span> <span m=''4810280''>I</span>
  <span m=''4810560''>say,</span> <span m=''4813650''>crease</span> <span m=''4813860''>pattern.</span>
  <span m=''4815010''>Boom.</span> <span m=''4815510''>That</span> <span m=''4815700''>folds</span>
  <span m=''4815940''>away</span> <span m=''4816120''>the</span> <span m=''4816240''>excess.</span>
  <span m=''4816810''>And</span> <span m=''4816980''>then,</span> <span m=''4817150''>just</span>
  <span m=''4817380''>the</span> <span m=''4817470''>white</span> <span m=''4817730''>faces,</span>
  <span m=''4818320''>these</span> <span m=''4818560''>guys</span> <span m=''4818930''>which</span>
  <span m=''4819090''>correspond</span> <span m=''4820160''>faces</span> <span m=''4820490''>over</span>
  <span m=''4820680''>there,</span> <span m=''4821820''>are</span> <span m=''4823940''>used.</span>
  <span m=''4824520''>And</span> <span m=''4824640''>then,</span> <span m=''4824850''>you</span>
  <span m=''4824980''>just</span> <span m=''4825180''>fold</span> <span m=''4825400''>away</span>
  <span m=''4825780''>the</span> <span m=''4825890''>extra</span> <span m=''4826160''>junk.</span>
  <span m=''4827440''>Easy.</span> <span m=''4829940''>You</span> <span m=''4830150''>want</span>
  <span m=''4830340''>to</span> <span m=''4830400''>make</span> <span m=''4830760''>a</span>
  <span m=''4830860''>bunny.</span> <span m=''4835280''>This</span> <span m=''4835510''>is</span>
  <span m=''4835620''>actually an</span> <span m=''4835940''>example</span> <span
  m=''4836400''>where</span> <span m=''4836770''>it</span> <span m=''4837090''>will</span>
  <span m=''4838600''>not</span> <span m=''4838980''>work</span> <span m=''4840430''>by</span>
  <span m=''4840570''>itself.</span> </p><p><span m=''4841400''>Because</span> <span
  m=''4841700''>as</span> <span m=''4841840''>I</span> <span m=''4841890''>said,</span>
  <span m=''4842060''>this</span> <span m=''4842150''>algorithm is</span> <span m=''4842570''>not</span>
  <span m=''4842810''>quite</span> <span m=''4843020''>guaranteed</span> <span m=''4843520''>to</span>
  <span m=''4843680''>work.</span> <span m=''4845550''>So</span> <span m=''4846020''>I''m</span>
  <span m=''4846350''>going</span> <span m=''4846700''>to</span> <span m=''4847770''>change</span>
  <span m=''4848260''>the</span> <span m=''4848350''>boundary</span> <span m=''4848770''>little</span>
  <span m=''4848990''>bit</span> <span m=''4849780''>by</span> <span m=''4850230''>cutting</span>
  <span m=''4853180''>to</span> <span m=''4853320''>the</span> <span m=''4853440''>ears.</span>
  <span m=''4855180''>And</span> <span m=''4855440''>so</span> <span m=''4855530''>this</span>
  <span m=''4855690''>is</span> <span m=''4855800''>still--</span> <span m=''4856060''>it</span>
  <span m=''4856230''>was</span> <span m=''4856360''>a</span> <span m=''4856430''>disk</span>
  <span m=''4856680''>before.</span> <span m=''4857360''>It''s</span> <span m=''4857530''>a</span>
  <span m=''4857600''>disk</span> <span m=''4857850''>after</span> <span m=''4858240''>because</span>
  <span m=''4858400''>there''s</span> <span m=''4858560''>this</span> <span m=''4858690''>boundary</span>
  <span m=''4859060''>here.</span> <span m=''4860810''>But</span> <span m=''4861110''>it</span>
  <span m=''4861230''>turns</span> <span m=''4861480''>out,</span> <span m=''4861640''>now</span>
  <span m=''4861850''>the</span> <span m=''4861970''>algorithm</span> <span m=''4862520''>will</span>
  <span m=''4862690''>work,</span> <span m=''4863050''>assuming</span> <span m=''4863810''>I</span>
  <span m=''4863930''>didn''t</span> <span m=''4864190''>mess</span> <span m=''4864470''>up.</span>
  </p><p><span m=''4869070''>It''s</span> <span m=''4869520''>bouncing</span> <span
  m=''4869840''>around</span> <span m=''4870070''>a</span> <span m=''4870140''>little</span>
  <span m=''4870350''>bit.</span> <span m=''4871760''>You</span> <span m=''4871850''>can</span>
  <span m=''4871990''>see</span> <span m=''4872100''>it''s</span> <span m=''4872240''>pretty</span>
  <span m=''4872510''>efficient</span> <span m=''4872910''>here.</span> <span m=''4873480''>There''s</span>
  <span m=''4873680''>very</span> <span m=''4874010''>tiny</span> <span m=''4874300''>gaps</span>
  <span m=''4874660''>between</span> <span m=''4875020''>the</span> <span m=''4875600''>triangles.</span>
  <span m=''4877010''>There''s</span> <span m=''4877230''>actually</span> <span m=''4877520''>a</span>
  <span m=''4877570''>little</span> <span m=''4877760''>bit</span> <span m=''4877880''>a</span>
  <span m=''4877910''>violation</span> <span m=''4878480''>here.</span> <span m=''4879090''>What''s</span>
  <span m=''4879270''>happening,</span> <span m=''4879940''>which</span> <span m=''4880100''>you</span>
  <span m=''4880190''>can</span> <span m=''4880310''>see</span> <span m=''4881280''>here,</span>
  <span m=''4881820''>is,</span> <span m=''4882100''>on</span> <span m=''4882200''>the</span>
  <span m=''4882310''>inside</span> <span m=''4883350''>are</span> <span m=''4883530''>all</span>
  <span m=''4883650''>this</span> <span m=''4883810''>extra</span> <span m=''4884120''>structure,</span>
  <span m=''4884570''>these</span> <span m=''4885110''>flaps.</span> <span m=''4886160''>And</span>
  <span m=''4886380''>sometimes</span> <span m=''4887150''>they''re</span> <span m=''4887340''>so</span>
  <span m=''4887520''>big</span> <span m=''4887970''>that they</span> <span m=''4888070''>actually</span>
  <span m=''4888340''>penetrate</span> <span m=''4888770''>the</span> <span m=''4888850''>surface.</span>
  </p><p><span m=''4889780''>But</span> <span m=''4889930''>that</span> <span m=''4890190''>can</span>
  <span m=''4890310''>be</span> <span m=''4890430''>dealt</span> <span m=''4890650''>with</span>
  <span m=''4891600''>by</span> <span m=''4892020''>just</span> <span m=''4892440''>a</span>
  <span m=''4892600''>little</span> <span m=''4892770''>bit</span> <span m=''4892900''>of</span>
  <span m=''4892980''>cutting,</span> <span m=''4894480''>maybe</span> <span m=''4894730''>a</span>
  <span m=''4894770''>little</span> <span m=''4894980''>more</span> <span m=''4895220''>cutting.</span>
  <span m=''4896730''>Not</span> <span m=''4896910''>cutting</span> <span m=''4897310''>in</span>
  <span m=''4897380''>the</span> <span m=''4897450''>literal</span> <span m=''4897740''>sense.</span>
  <span m=''4898800''>But</span> <span m=''4899030''>we</span> <span m=''4899140''>just</span>
  <span m=''4899280''>subdivided</span> <span m=''4899940''>these</span> <span m=''4900190''>panels</span>
  <span m=''4900600''>into</span> <span m=''4900780''>lots</span> <span m=''4901030''>of</span>
  <span m=''4901110''>smaller</span> <span m=''4901450''>panels.</span> <span m=''4902260''>And</span>
  <span m=''4902510''>now,</span> <span m=''4902810''>it</span> <span m=''4902940''>is</span>
  <span m=''4903090''>valid.</span> <span m=''4905450''>This</span> <span m=''4905650''>not</span>
  <span m=''4905890''>the</span> <span m=''4906300''>design</span> <span m=''4906800''>that</span>
  <span m=''4907285''>you''ve</span> <span m=''4907770''>seen on the</span> <span
  m=''4907840''>poster.</span> <span m=''4908310''>The</span> <span m=''4908520''>design</span>
  <span m=''4908780''>on</span> <span m=''4908900''>poster''s</span> <span m=''4909230''>little</span>
  <span m=''4909400''>more</span> <span m=''4909560''>efficient.</span> </p><p><span
  m=''4910390''>I''m</span> <span m=''4910560''>not</span> <span m=''4910900''>so</span>
  <span m=''4911270''>expert.</span> <span m=''4912020''>I''m</span> <span m=''4912050''>not</span>
  <span m=''4912230''>so</span> <span m=''4912390''>pro</span> <span m=''4912730''>that</span>
  <span m=''4912900''>I</span> <span m=''4912980''>can</span> <span m=''4913190''>make</span>
  <span m=''4913400''>exactly</span> <span m=''4913770''>that</span> <span m=''4913950''>design.</span>
  <span m=''4914820''>So it''s</span> <span m=''4915020''>a</span> <span m=''4915060''>little</span>
  <span m=''4915430''>inefficient</span> <span m=''4915900''>on</span> <span m=''4916020''>the</span>
  <span m=''4916150''>sides</span> <span m=''4916510''>here.</span> <span m=''4917020''>But</span>
  <span m=''4917160''>you</span> <span m=''4917280''>can</span> <span m=''4917400''>use</span>
  <span m=''4917570''>this</span> <span m=''4917700''>tool</span> <span m=''4917900''>to</span>
  <span m=''4917950''>make</span> <span m=''4918230''>super</span> <span m=''4918530''>complicated</span>
  <span m=''4919530''>3D</span> <span m=''4919840''>models.</span> <span m=''4921120''>Let</span>
  <span m=''4921360''>me</span> <span m=''4921550''>quickly</span> <span m=''4921980''>tell</span>
  <span m=''4922220''>you</span> <span m=''4923310''>what</span> <span m=''4923470''>goes</span>
  <span m=''4923620''>into</span> <span m=''4923690''>the</span> <span m=''4923900''>algorithm.</span>
  <span m=''4926110''>So</span> <span m=''4927140''>the</span> <span m=''4927240''>first</span>
  <span m=''4927520''>part</span> <span m=''4927900''>is</span> <span m=''4928060''>to</span>
  <span m=''4928150''>figure</span> <span m=''4928470''>out</span> <span m=''4928560''>where</span>
  <span m=''4928980''>all</span> <span m=''4929100''>these</span> <span m=''4929300''>tucks</span>
  <span m=''4929640''>are</span> <span m=''4929700''>going</span> <span m=''4929850''>to</span>
  <span m=''4929900''>go.</span> </p><p><span m=''4930820''>They</span> <span m=''4931030''>lie</span>
  <span m=''4931360''>essentially</span> <span m=''4931900''>along</span> <span m=''4932230''>angular</span>
  <span m=''4932590''>bisectors</span> <span m=''4933970''>on</span> <span m=''4934140''>one</span>
  <span m=''4934350''>side</span> <span m=''4935310''>of</span> <span m=''4935480''>every</span>
  <span m=''4935760''>edge.</span> <span m=''4936410''>But</span> <span m=''4936650''>at
  the</span> <span m=''4936730''>vertices,</span> <span m=''4937520''>things</span>
  <span m=''4937820''>are</span> <span m=''4938270''>super</span> <span m=''4938610''>complicated.</span>
  <span m=''4939820''>And</span> <span m=''4940400''>in</span> <span m=''4940570''>general,</span>
  <span m=''4941110''>if</span> <span m=''4941260''>you</span> <span m=''4941350''>have</span>
  <span m=''4941510''>a</span> <span m=''4941560''>non-convex</span> <span m=''4942120''>surface</span>
  <span m=''4942480''>with</span> <span m=''4942610''>tons</span> <span m=''4942880''>of</span>
  <span m=''4942940''>material</span> <span m=''4943360''>coming</span> <span m=''4943600''>together,</span>
  <span m=''4944350''>what</span> <span m=''4944560''>I''d</span> <span m=''4944680''>like</span>
  <span m=''4944940''>to</span> <span m=''4945070''>do</span> <span m=''4945770''>is</span>
  <span m=''4945930''>add</span> <span m=''4946140''>lots</span> <span m=''4946480''>of</span>
  <span m=''4946600''>little</span> <span m=''4946780''>flaps</span> <span m=''4947380''>on</span>
  <span m=''4947530''>the</span> <span m=''4947600''>side.</span> <span m=''4948570''>So</span>
  <span m=''4948800''>that</span> <span m=''4948980''>when</span> <span m=''4949190''>I</span>
  <span m=''4949570''>open</span> <span m=''4949900''>it</span> <span m=''4950010''>up--</span>
  <span m=''4951190''>so</span> <span m=''4951380''>let</span> <span m=''4951450''>me</span>
  <span m=''4952050''>draw</span> <span m=''4952190''>you</span> <span m=''4952350''>a</span>
  <span m=''4952410''>generic</span> <span m=''4952840''>picture.</span> </p><p><span
  m=''4953700''>So</span> <span m=''4953800''>we</span> <span m=''4953850''>have</span>
  <span m=''4954060''>two</span> <span m=''4954520''>faces</span> <span m=''4955010''>coming</span>
  <span m=''4955270''>together.</span> <span m=''4956350''>What</span> <span m=''4956510''>I''d</span>
  <span m=''4956600''>like</span> <span m=''4956780''>to</span> <span m=''4956890''>do</span>
  <span m=''4957190''>is</span> <span m=''4957510''>add</span> <span m=''4957760''>a</span>
  <span m=''4957800''>flap</span> <span m=''4958980''>here</span> <span m=''4960680''>and</span>
  <span m=''4961160''>a</span> <span m=''4961310''>corresponding</span> <span m=''4961950''>one</span>
  <span m=''4962230''>just</span> <span m=''4962490''>behind</span> <span m=''4962910''>it.</span>
  <span m=''4963900''>So</span> <span m=''4964100''>that''s</span> <span m=''4964380''>sort</span>
  <span m=''4964600''>of</span> <span m=''4964690''>a</span> <span m=''4964800''>tab.</span>
  <span m=''4969110''>And</span> <span m=''4969470''>I</span> <span m=''4969550''>can</span>
  <span m=''4970230''>unfold</span> <span m=''4970810''>that</span> <span m=''4970990''>and</span>
  <span m=''4971050''>think</span> <span m=''4971270''>of</span> <span m=''4971360''>some</span>
  <span m=''4971590''>other</span> <span m=''4971850''>surface</span> <span m=''4972220''>that</span>
  <span m=''4972320''>I''m</span> <span m=''4972430''>trying</span> <span m=''4972690''>to</span>
  <span m=''4972760''>fold.</span> <span m=''4973470''>So</span> <span m=''4974020''>I</span>
  <span m=''4974150''>really</span> <span m=''4974440''>wanted</span> <span m=''4974760''>just</span>
  <span m=''4974990''>those</span> <span m=''4975160''>two</span> <span m=''4975300''>polygons.</span>
  <span m=''4976450''>But</span> <span m=''4976600''>now,</span> <span m=''4976760''>I''ve</span>
  <span m=''4976910''>made</span> <span m=''4977150''>some</span> <span m=''4977310''>other</span>
  <span m=''4977490''>thing</span> <span m=''4977660''>which</span> <span m=''4977820''>is</span>
  <span m=''4977890''>still</span> <span m=''4978150''>a</span> <span m=''4978230''>disk.</span>
  <span m=''4979610''>You</span> <span m=''4979800''>can</span> <span m=''4979950''>add</span>
  <span m=''4980280''>those</span> <span m=''4980520''>faces</span> <span m=''4980940''>in</span>
  <span m=''4981020''>such</span> <span m=''4981270''>a</span> <span m=''4981350''>way</span>
  <span m=''4982090''>that</span> <span m=''4982380''>you</span> <span m=''4982570''>will</span>
  <span m=''4982700''>have,</span> <span m=''4982980''>at</span> <span m=''4983090''>most,</span>
  <span m=''4983400''>360</span> <span m=''4983980''>degrees</span> <span m=''4984280''>of</span>
  <span m=''4984350''>material</span> <span m=''4984820''>everywhere.</span> </p><p><span
  m=''4985690''>So</span> <span m=''4985820''>even</span> <span m=''4986090''>though</span>
  <span m=''4986200''>in</span> <span m=''4986270''>the</span> <span m=''4986410''>original</span>
  <span m=''4986880''>thing,</span> <span m=''4987760''>you</span> <span m=''4987950''>had</span>
  <span m=''4988280''>maybe</span> <span m=''4988610''>tons</span> <span m=''4988940''>of</span>
  <span m=''4989020''>material</span> <span m=''4989440''>coming</span> <span m=''4989660''>together</span>
  <span m=''4989970''>which</span> <span m=''4990110''>you</span> <span m=''4990190''>cannot</span>
  <span m=''4990520''>make</span> <span m=''4990720''>with</span> <span m=''4990850''>real</span>
  <span m=''4991050''>paper,</span> <span m=''4991900''>you</span> <span m=''4992060''>add</span>
  <span m=''4992340''>in</span> <span m=''4992440''>a</span> <span m=''4992490''>bunch</span>
  <span m=''4992730''>of</span> <span m=''4992810''>tabs</span> <span m=''4993140''>along</span>
  <span m=''4993360''>the</span> <span m=''4993480''>edges</span> <span m=''4993810''>and</span>
  <span m=''4993890''>a</span> <span m=''4993940''>few</span> <span m=''4994140''>more</span>
  <span m=''4994350''>at</span> <span m=''4994440''>the</span> <span m=''4994510''>vertices.</span>
  <span m=''4995480''>You</span> <span m=''4995700''>can</span> <span m=''4996640''>fix</span>
  <span m=''4997120''>things</span> <span m=''4997510''>so</span> <span m=''4997770''>that
  the</span> <span m=''4998020''>thing</span> <span m=''4998160''>is</span> <span
  m=''4998260''>actually</span> <span m=''4998660''>makeable</span> <span m=''4999110''>from</span>
  <span m=''4999350''>one</span> <span m=''4999490''>sheet</span> <span m=''4999690''>of</span>
  <span m=''4999760''>paper.</span> <span m=''5000940''>That''s</span> <span m=''5001720''>the</span>
  <span m=''5001800''>high</span> <span m=''5001940''>level</span> <span m=''5002190''>idea.</span>
  <span m=''5002860''>Doing</span> <span m=''5003140''>that is</span> <span m=''5003380''>a</span>
  <span m=''5003410''>bit</span> <span m=''5003570''>detailed.</span> <span m=''5004060''>The</span>
  <span m=''5004140''>paper</span> <span m=''5004400''>isn''t</span> <span m=''5004570''>even</span>
  <span m=''5004760''>published.</span> <span m=''5005140''>These</span> <span m=''5005350''>are</span>
  <span m=''5005430''>some</span> <span m=''5005600''>figures</span> <span m=''5005950''>from</span>
  <span m=''5006160''>it.</span> </p><p><span m=''5006850''>But</span> <span m=''5007030''>this</span>
  <span m=''5007190''>is</span> <span m=''5007300''>some--</span> <span m=''5007520''>way</span>
  <span m=''5007700''>this</span> <span m=''5007930''>is</span> <span m=''5008030''>how</span>
  <span m=''5008200''>you</span> <span m=''5008380''>resolve</span> <span m=''5008730''>a</span>
  <span m=''5008770''>vertex</span> <span m=''5009300''>with</span> <span m=''5009440''>some</span>
  <span m=''5009690''>triangulation</span> <span m=''5010700''>stuff.</span> <span
  m=''5011050''>Each</span> <span m=''5011300''>of</span> <span m=''5011400''>these</span>
  <span m=''5012520''>corresponds</span> <span m=''5013050''>to</span> <span m=''5013150''>a</span>
  <span m=''5013200''>flap</span> <span m=''5013740''>in</span> <span m=''5013880''>the</span>
  <span m=''5013980''>original</span> <span m=''5014310''>thing.</span> <span m=''5015180''>And</span>
  <span m=''5015410''>then,</span> <span m=''5017610''>this</span> <span m=''5017810''>is</span>
  <span m=''5017940''>where</span> <span m=''5018120''>we''re</span> <span m=''5018300''>a</span>
  <span m=''5018380''>little</span> <span m=''5018590''>impractical.</span> <span
  m=''5020216''>It</span> <span m=''5020560''>doesn''t</span> <span m=''5020810''>quite</span>
  <span m=''5020990''>match</span> <span m=''5021440''>what</span> <span m=''5021700''>we</span>
  <span m=''5021820''>do</span> <span m=''5022030''>in</span> <span m=''5022160''>practice</span>
  <span m=''5022770''>in</span> <span m=''5023240''>the</span> <span m=''5023650''>computer</span>
  <span m=''5023980''>program.</span> <span m=''5024900''>But</span> <span m=''5025020''>the</span>
  <span m=''5025110''>idea</span> <span m=''5025350''>is,</span> <span m=''5025530''>you</span>
  <span m=''5025680''>imagine,</span> <span m=''5026100''>you</span> <span m=''5026200''>have</span>
  <span m=''5026560''>your</span> <span m=''5026720''>faces</span> <span m=''5027140''>which</span>
  <span m=''5027300''>you</span> <span m=''5027390''>want</span> <span m=''5027650''>to</span>
  <span m=''5027730''>bring</span> <span m=''5027980''>together</span> <span m=''5028400''>somehow.</span>
  </p><p><span m=''5030430''>They''re</span> <span m=''5030910''>distributed</span>
  <span m=''5031620''>in</span> <span m=''5031890''>the</span> <span m=''5032450''>piece</span>
  <span m=''5032660''>of</span> <span m=''5032740''>paper</span> <span m=''5033090''>somewhere.</span>
  <span m=''5034690''>But</span> <span m=''5034810''>you''d</span> <span m=''5034950''>really</span>
  <span m=''5035200''>like</span> <span m=''5035430''>to</span> <span m=''5035840''>connect</span>
  <span m=''5036270''>them</span> <span m=''5036400''>together</span> <span m=''5036810''>when</span>
  <span m=''5037400''>they</span> <span m=''5037480''>have</span> <span m=''5037610''>matching</span>
  <span m=''5037990''>edges.</span> <span m=''5038270''>So</span> <span m=''5038520''>this</span>
  <span m=''5038720''>edge</span> <span m=''5038940''>might</span> <span m=''5039650''>be</span>
  <span m=''5039780''>glued</span> <span m=''5040050''>to</span> <span m=''5040110''>some</span>
  <span m=''5040400''>edge</span> <span m=''5040570''>of</span> <span m=''5040620''>some</span>
  <span m=''5040810''>other</span> <span m=''5040980''>triangle.</span> <span m=''5042700''>And</span>
  <span m=''5042900''>I</span> <span m=''5042980''>need</span> <span m=''5043190''>to</span>
  <span m=''5043300''>just</span> <span m=''5043510''>navigate</span> <span m=''5044150''>these</span>
  <span m=''5044770''>little</span> <span m=''5045360''>river-like</span> <span m=''5046120''>strips</span>
  <span m=''5047970''>to</span> <span m=''5048110''>visit</span> <span m=''5048380''>one</span>
  <span m=''5048560''>edge</span> <span m=''5048810''>from</span> <span m=''5048850''>the</span>
  <span m=''5048950''>other.</span> <span m=''5049150''>And we</span> <span m=''5049280''>proved</span>
  <span m=''5049550''>that</span> <span m=''5049650''>if</span> <span m=''5049940''>these</span>
  <span m=''5050380''>guys</span> <span m=''5050640''>are</span> <span m=''5050720''>sufficiently</span>
  <span m=''5051230''>tiny,</span> <span m=''5052050''>you</span> <span m=''5052190''>can</span>
  <span m=''5052320''>always</span> <span m=''5052560''>do</span> <span m=''5052690''>that.</span>
  </p><p><span m=''5053270''>And</span> <span m=''5053480''>of</span> <span m=''5053560''>course,</span>
  <span m=''5053880''>in</span> <span m=''5053980''>reality,</span> <span m=''5054380''>you</span>
  <span m=''5054490''>want</span> <span m=''5054850''>to</span> <span m=''5055190''>arrange</span>
  <span m=''5055590''>things,</span> <span m=''5055810''>so</span> <span m=''5055930''>you</span>
  <span m=''5056070''>can</span> <span m=''5056180''>do</span> <span m=''5056270''>it</span>
  <span m=''5056350''>efficiently</span> <span m=''5056860''>with</span> <span m=''5056990''>little</span>
  <span m=''5057200''>wastage.</span> <span m=''5057700''>But</span> <span m=''5057810''>we</span>
  <span m=''5057940''>proved</span> <span m=''5058150''>at</span> <span m=''5058220''>least</span>
  <span m=''5058450''>it''s</span> <span m=''5058570''>possible</span> <span m=''5059110''>with</span>
  <span m=''5059230''>this</span> <span m=''5059410''>kind</span> <span m=''5059610''>of</span>
  <span m=''5060100''>wiggly</span> <span m=''5060430''>path</span> <span m=''5060730''>stuff.</span>
  <span m=''5064530''>So</span> <span m=''5064700''>now</span> <span m=''5065020''>our</span>
  <span m=''5065400''>picture,</span> <span m=''5065900''>the</span> <span m=''5066010''>thing</span>
  <span m=''5066180''>we''re</span> <span m=''5066280''>trying</span> <span m=''5066510''>to</span>
  <span m=''5066560''>make</span> <span m=''5066850''>looks</span> <span m=''5067050''>something</span>
  <span m=''5067350''>like</span> <span m=''5067570''>that.</span> <span m=''5068190''>Where</span>
  <span m=''5068280''>we</span> <span m=''5068410''>have--</span> <span m=''5069070''>originally</span>
  <span m=''5069440''>it was</span> <span m=''5069600''>four</span> <span m=''5069810''>triangles,</span>
  <span m=''5070400''>the</span> <span m=''5070480''>gray</span> <span m=''5070660''>triangles.</span>
  <span m=''5071480''>We</span> <span m=''5071680''>added</span> <span m=''5072020''>in</span>
  <span m=''5072110''>these</span> <span m=''5072300''>extra</span> <span m=''5072560''>flaps</span>
  <span m=''5073030''>so</span> <span m=''5073180''>that</span> <span m=''5074180''>it''s</span>
  <span m=''5074350''>nice</span> <span m=''5075310''>and</span> <span m=''5075440''>well-behaved.</span>
  </p><p><span m=''5076720''>And</span> <span m=''5077190''>each</span> <span m=''5077380''>of</span>
  <span m=''5077440''>those</span> <span m=''5077610''>flaps</span> <span m=''5077930''>we''re</span>
  <span m=''5078265''>covering</span> <span m=''5078600''>from</span> <span m=''5078770''>both</span>
  <span m=''5078970''>sides.</span> <span m=''5080780''>And</span> <span m=''5081530''>if</span>
  <span m=''5081770''>you</span> <span m=''5083270''>think</span> <span m=''5083480''>the</span>
  <span m=''5084300''>red</span> <span m=''5084980''>diagram--</span> <span m=''5086050''>I''ll</span>
  <span m=''5086280''>get</span> <span m=''5086430''>this</span> <span m=''5086600''>right.</span>
  <span m=''5088610''>The</span> <span m=''5088730''>red</span> <span m=''5088910''>diagram</span>
  <span m=''5089310''>corresponds</span> <span m=''5089800''>to</span> <span m=''5089900''>that.</span>
  <span m=''5090190''>It''s</span> <span m=''5090320''>just</span> <span m=''5090520''>been</span>
  <span m=''5090770''>kind</span> <span m=''5090910''>of</span> <span m=''5090970''>squashed.</span>
  <span m=''5092060''>So</span> <span m=''5092190''>there are</span> <span m=''5092410''>four</span>
  <span m=''5092650''>triangles,</span> <span m=''5093530''>which</span> <span m=''5093620''>correspond</span>
  <span m=''5094100''>to</span> <span m=''5094180''>the</span> <span m=''5094300''>four</span>
  <span m=''5094650''>top</span> <span m=''5094970''>flaps.</span> <span m=''5095530''>And</span>
  <span m=''5095890''>there''s</span> <span m=''5096160''>this</span> <span m=''5096350''>outer</span>
  <span m=''5097930''>chunk</span> <span m=''5098270''>which</span> <span m=''5098470''>corresponds</span>
  <span m=''5099660''>to</span> <span m=''5100690''>that</span> <span m=''5100990''>flap.</span>
  <span m=''5102010''>And</span> <span m=''5103660''>then,</span> <span m=''5103850''>you</span>
  <span m=''5103990''>look</span> <span m=''5104180''>at</span> <span m=''5104260''>the</span>
  <span m=''5104360''>dual</span> <span m=''5104730''>which</span> <span m=''5104900''>is</span>
  <span m=''5105010''>the</span> <span m=''5105100''>blue</span> <span m=''5105310''>diagram.</span>
  </p><p><span m=''5105950''>You</span> <span m=''5106060''>take</span> <span m=''5106310''>that</span>
  <span m=''5106530''>picture,</span> <span m=''5107320''>and</span> <span m=''5107520''>that''s</span>
  <span m=''5107820''>how</span> <span m=''5107950''>you</span> <span m=''5108190''>set</span>
  <span m=''5108450''>up</span> <span m=''5108640''>the</span> <span m=''5110350''>crease</span>
  <span m=''5110650''>pattern</span> <span m=''5110980''>essentially.</span> <span
  m=''5111390''>So</span> <span m=''5111520''>these</span> <span m=''5111770''>are</span>
  <span m=''5111810''>the</span> <span m=''5111980''>original</span> <span m=''5112890''>four</span>
  <span m=''5113140''>triangles.</span> <span m=''5113730''>And</span> <span m=''5113820''>then.</span>
  <span m=''5113930''>There''s</span> <span m=''5114100''>all</span> <span m=''5114200''>this</span>
  <span m=''5114440''>stuff</span> <span m=''5115320''>that</span> <span m=''5115450''>represents</span>
  <span m=''5116190''>the</span> <span m=''5116280''>structure</span> <span m=''5117360''>of</span>
  <span m=''5117530''>that</span> <span m=''5117800''>thing</span> <span m=''5117980''>that</span>
  <span m=''5118090''>we</span> <span m=''5118220''>want</span> <span m=''5118400''>to</span>
  <span m=''5118440''>make.</span> <span m=''5119230''>And</span> <span m=''5119380''>then,</span>
  <span m=''5119530''>you</span> <span m=''5119680''>just</span> <span m=''5120090''>have</span>
  <span m=''5120240''>to</span> <span m=''5120350''>fill</span> <span m=''5120590''>in</span>
  <span m=''5120650''>the</span> <span m=''5120730''>creases</span> <span m=''5121160''>in</span>
  <span m=''5121270''>the</span> <span m=''5121350''>middle.</span> <span m=''5122220''>And</span>
  <span m=''5122360''>you</span> <span m=''5122450''>do</span> <span m=''5122620''>that</span>
  <span m=''5123220''>just</span> <span m=''5124190''>with</span> <span m=''5124350''>something--</span>
  <span m=''5124900''>this</span> <span m=''5125100''>is</span> <span m=''5125230''>how</span>
  <span m=''5125560''>you</span> <span m=''5125730''>do</span> <span m=''5125900''>it</span>
  <span m=''5125990''>guaranteed</span> <span m=''5126440''>correct.</span> <span
  m=''5126900''>And</span> <span m=''5127020''>we</span> <span m=''5127120''>saw</span>
  <span m=''5127480''>I</span> <span m=''5127570''>had</span> <span m=''5127730''>to</span>
  <span m=''5127810''>do</span> <span m=''5128450''>lots</span> <span m=''5128700''>of</span>
  <span m=''5128780''>subdivision</span> <span m=''5129360''>here.</span> <span m=''5129570''>What</span>
  <span m=''5129690''>I</span> <span m=''5129760''>called,</span> <span m=''5130160''>accidentally,</span>
  <span m=''5130620''>cutting.</span> </p><p><span m=''5132030''>But</span> <span
  m=''5132530''>just</span> <span m=''5132720''>lots</span> <span m=''5133050''>of</span>
  <span m=''5133150''>pleats</span> <span m=''5133650''>there.</span> <span m=''5134660''>Because,</span>
  <span m=''5134850''>essentially,</span> <span m=''5135270''>this</span> <span m=''5135590''>is</span>
  <span m=''5135940''>the</span> <span m=''5136190''>edge.</span> <span m=''5137350''>And</span>
  <span m=''5137550''>we</span> <span m=''5137650''>want</span> <span m=''5137850''>that</span>
  <span m=''5138010''>edge</span> <span m=''5138240''>to</span> <span m=''5138380''>lie
  in</span> <span m=''5138690''>a</span> <span m=''5138770''>tiny</span> <span m=''5139160''>little</span>
  <span m=''5139400''>tab.</span> <span m=''5140300''>So</span> <span m=''5140410''>it''s</span>
  <span m=''5140520''>got</span> <span m=''5140660''>to</span> <span m=''5140730''>go</span>
  <span m=''5140940''>up</span> <span m=''5141140''>and</span> <span m=''5141230''>down
  and</span> <span m=''5141620''>up</span> <span m=''5141660''>and</span> <span m=''5141770''>down
  and</span> <span m=''5142160''>up</span> <span m=''5142190''>and</span> <span m=''5142270''>down,</span>
  <span m=''5142450''>accordion</span> <span m=''5142900''>style.</span> <span m=''5143970''>And</span>
  <span m=''5144320''>if</span> <span m=''5144440''>you</span> <span m=''5144530''>do</span>
  <span m=''5144690''>it</span> <span m=''5144810''>right,</span> <span m=''5145520''>all</span>
  <span m=''5145730''>those</span> <span m=''5145910''>things</span> <span m=''5146110''>will</span>
  <span m=''5146220''>collapse</span> <span m=''5146800''>down</span> <span m=''5147090''>to</span>
  <span m=''5147650''>a</span> <span m=''5147760''>little</span> <span m=''5148550''>tab</span>
  <span m=''5148990''>attached</span> <span m=''5149400''>to</span> <span m=''5149480''>that</span>
  <span m=''5149680''>edge</span> <span m=''5150260''>which</span> <span m=''5150360''>is</span>
  <span m=''5150480''>also</span> <span m=''5150770''>attach</span> <span m=''5151110''>that</span>
  <span m=''5151320''>edge.</span> <span m=''5151530''>And</span> <span m=''5151600''>they</span>
  <span m=''5151730''>will</span> <span m=''5151880''>get</span> <span m=''5152090''>joined</span>
  <span m=''5152400''>up.</span> <span m=''5152940''>Then,</span> <span m=''5153060''>you''ve</span>
  <span m=''5153190''>got</span> <span m=''5153350''>to</span> <span m=''5153390''>get</span>
  <span m=''5153650''>rid</span> <span m=''5153840''>of</span> <span m=''5153950''>all</span>
  <span m=''5154090''>this</span> <span m=''5154240''>stuff</span> <span m=''5154530''>in</span>
  <span m=''5154620''>the</span> <span m=''5154690''>middle.</span> </p><p><span m=''5155270''>And</span>
  <span m=''5156160''>rough</span> <span m=''5156350''>idea</span> <span m=''5156570''>is,</span>
  <span m=''5156720''>if</span> <span m=''5157010''>you</span> <span m=''5157190''>pack
  it</span> <span m=''5157610''>with--</span> <span m=''5157980''>or</span> <span
  m=''5158230''>I</span> <span m=''5158270''>guess</span> <span m=''5158430''>you</span>
  <span m=''5158530''>cover</span> <span m=''5158900''>it</span> <span m=''5158940''>with</span>
  <span m=''5159140''>disks</span> <span m=''5160230''>so</span> <span m=''5160440''>that</span>
  <span m=''5160560''>everything</span> <span m=''5160950''>is</span> <span m=''5161050''>again</span>
  <span m=''5161310''>very</span> <span m=''5161510''>tiny.</span> <span m=''5162730''>And</span>
  <span m=''5163110''>you</span> <span m=''5163230''>fold</span> <span m=''5163640''>what''s</span>
  <span m=''5163800''>called</span> <span m=''5163940''>the</span> <span m=''5164020''>[INAUDIBLE]</span>
  <span m=''5164720''>with</span> <span m=''5164730''>those</span> <span m=''5164970''>points.</span>
  <span m=''5166430''>And</span> <span m=''5166650''>it</span> <span m=''5166730''>works.</span>
  <span m=''5169020''>It''s</span> <span m=''5169410''>a</span> <span m=''5169480''>complicated</span>
  <span m=''5170590''>but</span> <span m=''5170760''>very</span> <span m=''5170980''>cool.</span>
  <span m=''5171850''>And</span> <span m=''5173550''>the</span> <span m=''5173650''>paper</span>
  <span m=''5174230''>hopefully</span> <span m=''5174550''>will</span> <span m=''5174690''>be</span>
  <span m=''5175020''>released</span> <span m=''5175440''>later</span> <span m=''5175690''>this</span>
  <span m=''5175880''>year</span> <span m=''5176650''>finally.</span> <span m=''5177560''>And</span>
  <span m=''5178700''>that''s</span> <span m=''5178950''>Origamizer.</span> <span
  m=''5179560''>And</span> <span m=''5179640''>that''s</span> <span m=''5179810''>efficient</span>
  <span m=''5180140''>origami</span> <span m=''5180480''>design.</span> </p>'
type: course
uid: e6b610dc823591a52f1328a955f86095

---
None