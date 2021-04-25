---
about_this_resource_text: <p><strong>Description:</strong> This lecture focuses on
  the folding of the backbone chain of proteins in relation to fixed-angle linkages.
  Four problems types (span, flattening, flat-state connectivity, locked) are presented,
  followed by the canonicalization of a producible chain.</p><p><strong>Speaker:</strong>
  Erik Demaine</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: 82t7g2itzm4
  parent_uid: 55e0b22bad2ff7cb29fe5f04e732832f
  title: Video-YouTube-Stream
  type: Video
  uid: c0bd19fce3d726f81500f2d3b0ca3420
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/82t7g2itzm4/default.jpg
  parent_uid: 55e0b22bad2ff7cb29fe5f04e732832f
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: c0f7349a808a5418c2554fe222ace474
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: 55e0b22bad2ff7cb29fe5f04e732832f
  title: Video-iTunes U-MP4
  type: Video
  uid: 3e7f18b50e1fc25031e2a89f56b43466
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_lec20_300k.mp4
  parent_uid: 55e0b22bad2ff7cb29fe5f04e732832f
  title: Video-Internet Archive-MP4
  type: Video
  uid: 14e0b5a0751e64810a461bb7de01c4f4
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 82t7g2itzm4
  parent_uid: 55e0b22bad2ff7cb29fe5f04e732832f
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: e34a63b780a092ca95888f2e5f95566f
- id: 82t7g2itzm4.srt
  parent_uid: 55e0b22bad2ff7cb29fe5f04e732832f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-20-protein-chains/82t7g2itzm4.srt
  title: 3play caption file
  type: null
  uid: 5786cb848819e7a177ece7aeacb347cc
- id: 82t7g2itzm4.pdf
  parent_uid: 55e0b22bad2ff7cb29fe5f04e732832f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-20-protein-chains/82t7g2itzm4.pdf
  title: 3play pdf file
  type: null
  uid: 0941fb42a91bcdfd0af6deded3820105
- id: Caption-3Play YouTube id-SRT
  parent_uid: 55e0b22bad2ff7cb29fe5f04e732832f
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 3b72ca4a9fafd195aa32c1ad2fdd3f44
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 55e0b22bad2ff7cb29fe5f04e732832f
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: d71d81f89c574587bf0f4e9f0b266687
inline_embed_id: 44465642lecture20:proteinchains67341818
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: lecture-20-protein-chains
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/lecture-20-protein-chains
template_type: Tabbed
title: 'Lecture 20: Protein Chains'
transcript: '<p><span m=''4210''>PROFESSOR: Today</span> <span m=''4810''>we''re</span>
  <span m=''4980''>going</span> <span m=''5090''>to</span> <span m=''5200''>talk</span>
  <span m=''5400''>about</span> <span m=''5690''>protein</span> <span m=''6090''>folding</span>
  <span m=''6740''>and</span> <span m=''7100''>its</span> <span m=''7260''>relation</span>
  <span m=''7740''>to</span> <span m=''8000''>linkage</span> <span m=''8350''>folding.</span>
  <span m=''9070''>We''re</span> <span m=''9190''>going</span> <span m=''9300''>to</span>
  <span m=''9360''>look</span> <span m=''9560''>at</span> <span m=''9710''>a</span>
  <span m=''9960''>mechanical</span> <span m=''10790''>model</span> <span m=''11250''>of</span>
  <span m=''11930''>proteins.</span> <span m=''13200''>This</span> <span m=''13600''>is</span>
  <span m=''13720''>an</span> <span m=''13820''>example</span> <span m=''14230''>of</span>
  <span m=''14310''>a</span> <span m=''14380''>protein</span> <span m=''14790''>from</span>
  <span m=''14960''>lecture</span> <span m=''15260''>one.</span> <span m=''16160''>There''s</span>
  <span m=''16450''>a</span> <span m=''16470''>ton</span> <span m=''16760''>out</span>
  <span m=''16940''>there</span> <span m=''17210''>in</span> <span m=''17270''>this</span>
  <span m=''17690''>place</span> <span m=''17960''>called</span> <span m=''18150''>the</span>
  <span m=''18240''>protein</span> <span m=''18610''>data</span> <span m=''18860''>bank,</span>
  <span m=''19710''>all</span> <span m=''19920''>freely</span> <span m=''20270''>available.</span>
  <span m=''21200''>It''s</span> <span m=''21350''>really</span> <span m=''21610''>hard</span>
  <span m=''21820''>to</span> <span m=''21880''>get</span> <span m=''22060''>pictures</span>
  <span m=''22910''>like</span> <span m=''23140''>this.</span> <span m=''23750''>But</span>
  <span m=''23960''>you</span> <span m=''24080''>get</span> <span m=''24270''>some</span>
  <span m=''24460''>idea</span> <span m=''24770''>that</span> <span m=''24930''>there''s</span>
  <span m=''25150''>a</span> <span m=''25460''>linkage</span> <span m=''26390''>embedded</span>
  <span m=''26900''>in</span> <span m=''27040''>here.</span> <span m=''27250''>You</span>
  <span m=''27400''>see</span> <span m=''27640''>various</span> <span m=''28580''>little</span>
  <span m=''29890''>spheres</span> <span m=''30480''>and</span> <span m=''30670''>edges.</span>
  <span m=''31040''>That''s,</span> <span m=''31270''>of</span> <span m=''31400''>course,</span>
  <span m=''31630''>not</span> <span m=''31780''>reality.</span> <span m=''32350''>Those</span>
  <span m=''32610''>spheres</span> <span m=''32890''>are</span> <span m=''32970''>actually</span>
  <span m=''33350''>atoms</span> <span m=''33910''>and</span> <span m=''34030''>they''re</span>
  <span m=''34270''>kind</span> <span m=''34490''>of</span> <span m=''34620''>amorphous</span>
  <span m=''35110''>blobs.</span> <span m=''35920''>The</span> <span m=''36490''>edges</span>
  <span m=''36870''>are</span> <span m=''36980''>chemical</span> <span m=''37410''>bonds.</span>
  <span m=''38500''>And</span> <span m=''38650''>those</span> <span m=''38850''>are</span>
  <span m=''39170''>connections.</span> <span m=''39680''>We</span> <span m=''39770''>don''t</span>
  <span m=''39930''>know</span> <span m=''40060''>whether</span> <span m=''40250''>they''re--</span>
  <span m=''40705''>it''s</span> <span m=''41160''>not</span> <span m=''41280''>really</span>
  <span m=''41440''>matter,</span> <span m=''41900''>but</span> <span m=''42030''>it''s</span>
  <span m=''43090''>force.</span> </p><p><span m=''46190''>This</span> <span m=''46400''>is</span>
  <span m=''46520''>a</span> <span m=''46600''>rather</span> <span m=''46880''>messy</span>
  <span m=''47220''>picture.</span> <span m=''47510''>This</span> <span m=''47770''>is</span>
  <span m=''48020''>what</span> <span m=''48200''>a</span> <span m=''48270''>protein</span>
  <span m=''48720''>folds</span> <span m=''49040''>into,</span> <span m=''49380''>some</span>
  <span m=''49730''>3D</span> <span m=''50060''>shape.</span> <span m=''50420''>Most</span>
  <span m=''50650''>proteins</span> <span m=''51040''>fold</span> <span m=''51330''>consistently</span>
  <span m=''52170''>into</span> <span m=''52550''>one</span> <span m=''52880''>shape.</span>
  <span m=''54350''>We</span> <span m=''54470''>don''t</span> <span m=''54640''>really</span>
  <span m=''54840''>know</span> <span m=''55000''>how</span> <span m=''55170''>that</span>
  <span m=''55320''>happens.</span> <span m=''55770''>We</span> <span m=''55870''>can''t</span>
  <span m=''56680''>watch</span> <span m=''57310''>it</span> <span m=''57450''>happen.</span>
  <span m=''58450''>So</span> <span m=''60980''>the</span> <span m=''61070''>big</span>
  <span m=''61330''>challenge</span> <span m=''61650''>is</span> <span m=''61970''>to</span>
  <span m=''62060''>know</span> <span m=''62220''>how</span> <span m=''62410''>proteins</span>
  <span m=''62850''>fold.</span> <span m=''63680''>Given</span> <span m=''63970''>a</span>
  <span m=''64040''>protein,</span> <span m=''64680''>what</span> <span m=''64870''>does
  it</span> <span m=''65019''>fold</span> <span m=''65349''>into?</span> <span m=''66150''>That''s</span>
  <span m=''66350''>the</span> <span m=''66440''>protein</span> <span m=''66770''>folding</span>
  <span m=''67130''>problem.</span> <span m=''67780''>Major</span> <span m=''68300''>unsolved</span>
  <span m=''68670''>problem</span> <span m=''68990''>in</span> <span m=''69090''>biology,</span>
  <span m=''69505''>biochemistry.</span> </p><p><span m=''71290''>The</span> <span
  m=''71690''>protein</span> <span m=''72060''>design</span> <span m=''72440''>problem</span>
  <span m=''72790''>is</span> <span m=''72930''>I</span> <span m=''73010''>want</span>
  <span m=''73380''>to</span> <span m=''73490''>make</span> <span m=''73680''>a</span>
  <span m=''73740''>particular</span> <span m=''74160''>3D</span> <span m=''74440''>shape</span>
  <span m=''74770''>so</span> <span m=''74940''>that</span> <span m=''75070''>it</span>
  <span m=''75360''>docks</span> <span m=''75740''>into</span> <span m=''75960''>something,</span>
  <span m=''76510''>binds</span> <span m=''76870''>to</span> <span m=''76990''>a</span>
  <span m=''77030''>virus,</span> <span m=''77570''>whatever,</span> <span m=''79790''>what</span>
  <span m=''80620''>protein</span> <span m=''81020''>should</span> <span m=''81210''>I</span>
  <span m=''81270''>synthesize</span> <span m=''82070''>in</span> <span m=''82240''>order</span>
  <span m=''82780''>for</span> <span m=''83040''>it</span> <span m=''83140''>to</span>
  <span m=''83150''>fold</span> <span m=''83430''>into</span> <span m=''83610''>that</span>
  <span m=''83830''>shape?</span> <span m=''85070''>That</span> <span m=''85340''>is</span>
  <span m=''85530''>potentially</span> <span m=''86060''>an</span> <span m=''86120''>easier</span>
  <span m=''86460''>question</span> <span m=''86790''>algorithmically</span> <span
  m=''87440''>and it''s</span> <span m=''87710''>the</span> <span m=''88490''>really</span>
  <span m=''88710''>useful</span> <span m=''89030''>one</span> <span m=''89190''>from</span>
  <span m=''89310''>a</span> <span m=''89470''>drug</span> <span m=''89690''>design</span>
  <span m=''90080''>standpoint.</span> <span m=''90950''>Some</span> <span m=''91620''>new</span>
  <span m=''91730''>virus</span> <span m=''92050''>comes</span> <span m=''92240''>along,</span>
  <span m=''92910''>you</span> <span m=''93000''>design</span> <span m=''93310''>a</span>
  <span m=''93360''>drug</span> <span m=''93620''>to</span> <span m=''93720''>attack</span>
  <span m=''94050''>it</span> <span m=''94220''>and</span> <span m=''94320''>only</span>
  <span m=''94640''>it,</span> <span m=''95450''>you</span> <span m=''95600''>build</span>
  <span m=''96080''>it.</span> <span m=''96640''>Usually</span> <span m=''97100''>you
  would</span> <span m=''97240''>manufacture</span> <span m=''97820''>some</span>
  <span m=''98010''>synthetic</span> <span m=''98460''>DNA,</span> <span m=''99340''>you</span>
  <span m=''99440''>feed</span> <span m=''99720''>it</span> <span m=''99840''>into</span>
  <span m=''100120''>the</span> <span m=''100400''>cell,</span> <span m=''101500''>DNA</span>
  <span m=''101920''>goes</span> <span m=''102220''>to</span> <span m=''102350''>the</span>
  <span m=''102580''>RNA,</span> <span m=''103100''>goes to</span> <span m=''103440''>the</span>
  <span m=''103730''>mRNA,</span> <span m=''104270''>goes</span> <span m=''104510''>to</span>
  <span m=''104640''>the</span> <span m=''104860''>protein.</span> <span m=''106240''>You
  all</span> <span m=''106660''>remember</span> <span m=''107220''>biology</span>
  <span m=''107610''>101,</span> <span m=''108110''>hopefully.</span> <span m=''109950''>We</span>
  <span m=''110080''>don''t</span> <span m=''110230''>need</span> <span m=''110360''>to</span>
  <span m=''110450''>know</span> <span m=''110540''>much</span> <span m=''110760''>about</span>
  <span m=''110990''>it.</span> </p><p><span m=''112130''>If</span> <span m=''112300''>you</span>
  <span m=''112450''>look</span> <span m=''112810''>at</span> <span m=''113270''>what''s</span>
  <span m=''113480''>called</span> <span m=''113630''>the</span> <span m=''113690''>backbone</span>
  <span m=''114300''>of</span> <span m=''114350''>the</span> <span m=''114440''>protein,
  a</span> <span m=''114850''>protein''s</span> <span m=''115260''>basically</span>
  <span m=''115700''>a</span> <span m=''115750''>chain</span> <span m=''116920''>and</span>
  <span m=''117150''>attached</span> <span m=''117530''>to</span> <span m=''117620''>the</span>
  <span m=''117720''>chain</span> <span m=''117980''>are</span> <span m=''118090''>various</span>
  <span m=''118480''>amino</span> <span m=''118800''>acids.</span> <span m=''119660''>Today</span>
  <span m=''120250''>I''m</span> <span m=''120410''>going</span> <span m=''120610''>to</span>
  <span m=''120730''>ignore</span> <span m=''121050''>the</span> <span m=''121180''>amino</span>
  <span m=''121460''>acids,</span> <span m=''121980''>which</span> <span m=''122190''>is</span>
  <span m=''122280''>a</span> <span m=''122320''>little</span> <span m=''122530''>crazy,</span>
  <span m=''123510''>and</span> <span m=''123770''>just</span> <span m=''124030''>think</span>
  <span m=''124230''>about</span> <span m=''124540''>the</span> <span m=''124620''>backbone</span>
  <span m=''125200''>chain.</span> <span m=''126270''>Backbone</span> <span m=''126730''>chain</span>
  <span m=''126960''>looks</span> <span m=''127170''>something</span> <span m=''127660''>like</span>
  <span m=''127850''>this.</span> <span m=''129479''>One</span> <span m=''129590''>of</span>
  <span m=''129650''>the</span> <span m=''129740''>challenges</span> <span m=''130259''>of</span>
  <span m=''130340''>video</span> <span m=''130590''>recording</span> <span m=''131009''>a</span>
  <span m=''131100''>class is</span> <span m=''131530''>I</span> <span m=''131590''>can</span>
  <span m=''131750''>only</span> <span m=''131990''>use</span> <span m=''133280''>copyright</span>
  <span m=''133720''>free</span> <span m=''134170''>or</span> <span m=''134580''>Creative</span>
  <span m=''134840''>Commons</span> <span m=''135260''>images.</span> <span m=''136440''>This
  one,</span> <span m=''136620''>I</span> <span m=''136680''>couldn''t</span> <span
  m=''136920''>get</span> <span m=''137060''>one,</span> <span m=''137380''>so I</span>
  <span m=''137610''>had</span> <span m=''137790''>to</span> <span m=''137850''>draw
  it.</span> </p><p><span m=''140180''>There''s</span> <span m=''140430''>various</span>
  <span m=''140720''>measurements</span> <span m=''141250''>here</span> <span m=''141590''>in</span>
  <span m=''141790''>certain</span> <span m=''142080''>numbers</span> <span m=''142420''>of</span>
  <span m=''142530''>angstroms.</span> <span m=''143330''>Those</span> <span m=''143600''>are</span>
  <span m=''143670''>the</span> <span m=''143840''>chemical</span> <span m=''144250''>bonds.</span>
  <span m=''144720''>Various</span> <span m=''146280''>atoms</span> <span m=''146780''>here--</span>
  <span m=''147710''>nitrogen,</span> <span m=''148210''>carbon,</span> <span m=''148450''>and</span>
  <span m=''148730''>so</span> <span m=''148880''>on,</span> <span m=''149850''>hydrogen.</span>
  <span m=''151590''>But</span> <span m=''151750''>basically,</span> <span m=''152180''>it''s</span>
  <span m=''152310''>a</span> <span m=''152380''>chain that</span> <span m=''152840''>zigzags</span>
  <span m=''153370''>back</span> <span m=''153580''>and</span> <span m=''153710''>forth.</span>
  <span m=''154260''>You</span> <span m=''154360''>can</span> <span m=''154400''>also</span>
  <span m=''154630''>see</span> <span m=''154840''>the</span> <span m=''155040''>angles</span>
  <span m=''155480''>here.</span> <span m=''155670''>They''re</span> <span m=''155810''>not</span>
  <span m=''156020''>quite</span> <span m=''156320''>all</span> <span m=''156480''>the</span>
  <span m=''156560''>same,</span> <span m=''156890''>but</span> <span m=''157030''>they''re</span>
  <span m=''157150''>very</span> <span m=''157380''>similar.</span> <span m=''157970''>All</span>
  <span m=''158130''>the</span> <span m=''158220''>lengths</span> <span m=''158560''>in</span>
  <span m=''158700''>the</span> <span m=''158900''>angles</span> <span m=''159320''>are</span>
  <span m=''159810''>close.</span> <span m=''162950''>It</span> <span m=''163330''>zigzags--</span>
  <span m=''163840''>this</span> <span m=''163970''>is</span> <span m=''164070''>really</span>
  <span m=''164280''>in</span> <span m=''164370''>three</span> <span m=''164570''>dimensions.</span>
  <span m=''165180''>I</span> <span m=''165300''>tried</span> <span m=''165550''>to</span>
  <span m=''165660''>draw</span> <span m=''165860''>the</span> <span m=''165980''>spheres</span>
  <span m=''166270''>so</span> <span m=''166410''>you</span> <span m=''166480''>could</span>
  <span m=''166620''>see</span> <span m=''166740''>the</span> <span m=''166840''>three</span>
  <span m=''167070''>dimensionality,</span> <span m=''167660''>but</span> <span m=''167800''>it''s</span>
  <span m=''167930''>a</span> <span m=''167950''>little</span> <span m=''168130''>tricky.</span>
  <span m=''169080''>And</span> <span m=''169320''>then</span> <span m=''169450''>attached</span>
  <span m=''169920''>on</span> <span m=''170020''>the</span> <span m=''170120''>sides</span>
  <span m=''170550''>are</span> <span m=''170660''>the</span> <span m=''170820''>amino</span>
  <span m=''171090''>acids.</span> <span m=''171690''>I''m</span> <span m=''171830''>going</span>
  <span m=''171920''>to</span> <span m=''171970''>focus</span> <span m=''172330''>just</span>
  <span m=''172560''>on</span> <span m=''172630''>the</span> <span m=''172710''>backbone.</span>
  </p><p><span m=''173800''>The</span> <span m=''173920''>way</span> <span m=''174260''>this</span>
  <span m=''174550''>thing</span> <span m=''174810''>is</span> <span m=''174940''>allowed</span>
  <span m=''175360''>to</span> <span m=''175440''>fold--</span> <span m=''176980''>these</span>
  <span m=''177190''>lengths,</span> <span m=''177600''>as</span> <span m=''177660''>far</span>
  <span m=''177850''>as</span> <span m=''177930''>we</span> <span m=''178030''>know,</span>
  <span m=''178360''>are</span> <span m=''178890''>pretty</span> <span m=''179370''>static.</span>
  <span m=''179695''>They</span> <span m=''180020''>probably</span> <span m=''180320''>would</span>
  <span m=''180440''>jiggle a</span> <span m=''180830''>little</span> <span m=''181040''>bit.</span>
  <span m=''181260''>But</span> <span m=''181640''>you</span> <span m=''181790''>can</span>
  <span m=''181910''>think</span> <span m=''182110''>of</span> <span m=''182190''>them</span>
  <span m=''182370''>as</span> <span m=''182480''>edges.</span> <span m=''182850''>So
  you can</span> <span m=''183190''>think</span> <span m=''183410''>of</span> <span
  m=''183500''>this</span> <span m=''183680''>as</span> <span m=''183780''>a</span>
  <span m=''183840''>linkage.</span> <span m=''185210''>The</span> <span m=''185320''>catch</span>
  <span m=''185650''>is,</span> <span m=''186160''>also,</span> <span m=''187050''>the</span>
  <span m=''187200''>angles</span> <span m=''187600''>are</span> <span m=''187680''>fixed</span>
  <span m=''189360''>because</span> <span m=''189550''>the</span> <span m=''189650''>way</span>
  <span m=''189850''>this</span> <span m=''190080''>atom</span> <span m=''190350''>wants</span>
  <span m=''190560''>to</span> <span m=''190660''>bind</span> <span m=''190950''>to</span>
  <span m=''191000''>other</span> <span m=''191240''>things</span> <span m=''191850''>has</span>
  <span m=''192320''>very</span> <span m=''192680''>fixed</span> <span m=''193430''>angle</span>
  <span m=''193730''>patterns.</span> <span m=''194060''>If you</span> <span m=''194170''>ever</span>
  <span m=''194390''>played</span> <span m=''194610''>with</span> <span m=''194740''>a</span>
  <span m=''194960''>chemistry</span> <span m=''195600''>construction</span> <span
  m=''196090''>set,</span> <span m=''197080''>that''s</span> <span m=''197760''>how</span>
  <span m=''197840''>they</span> <span m=''197930''>work.</span> <span m=''198150''>They</span>
  <span m=''198240''>have</span> <span m=''198420''>holes</span> <span m=''199060''>at</span>
  <span m=''199630''>just</span> <span m=''199850''>particular</span> <span m=''200330''>angles.</span>
  </p><p><span m=''201520''>So</span> <span m=''201670''>if</span> <span m=''201740''>you</span>
  <span m=''201840''>think</span> <span m=''202050''>of</span> <span m=''202150''>like</span>
  <span m=''202350''>a</span> <span m=''202430''>robotic</span> <span m=''202850''>arm,</span>
  <span m=''203310''>normally--</span> <span m=''205070''>like</span> <span m=''205280''>here,</span>
  <span m=''205490''>I</span> <span m=''205540''>have</span> <span m=''205750''>it</span>
  <span m=''206040''>two</span> <span m=''206530''>edge</span> <span m=''206890''>robotic</span>
  <span m=''207370''>arm,</span> <span m=''207590''>let''s</span> <span m=''207800''>say.</span>
  <span m=''208330''>Normally,</span> <span m=''208750''>you have</span> <span m=''208920''>two</span>
  <span m=''209080''>degrees</span> <span m=''209410''>of</span> <span m=''209490''>freedom</span>
  <span m=''209820''>in</span> <span m=''209940''>three</span> <span m=''210150''>dimensions.</span>
  <span m=''210660''>You</span> <span m=''210840''>can</span> <span m=''210980''>change</span>
  <span m=''211350''>the</span> <span m=''211490''>angle</span> <span m=''212570''>and</span>
  <span m=''212850''>you</span> <span m=''213010''>can</span> <span m=''213210''>spin</span>
  <span m=''214220''>around</span> <span m=''215040''>this</span> <span m=''215250''>edge.</span>
  <span m=''216430''>Now,</span> <span m=''216750''>it''s</span> <span m=''216900''>saying</span>
  <span m=''217130''>the</span> <span m=''217240''>angle</span> <span m=''217570''>is</span>
  <span m=''217710''>fixed--</span> <span m=''218190''>for</span> <span m=''218260''>example,</span>
  <span m=''218610''>here</span> <span m=''218840''>it''s,</span> <span m=''219300''>say,
  at</span> <span m=''219490''>90</span> <span m=''219750''>degrees.</span> <span
  m=''220210''>All</span> <span m=''220520''>I</span> <span m=''220590''>can</span>
  <span m=''220750''>do</span> <span m=''220870''>is</span> <span m=''220970''>spin.</span>
  <span m=''222000''>I''m</span> <span m=''222150''>not</span> <span m=''222340''>allowed</span>
  <span m=''222700''>to</span> <span m=''223310''>flex</span> <span m=''223690''>my</span>
  <span m=''224310''>muscle in</span> <span m=''224660''>this</span> <span m=''224830''>way.</span>
  <span m=''225950''>So</span> <span m=''226100''>that</span> <span m=''226360''>is</span>
  <span m=''226520''>the</span> <span m=''226600''>model.</span> <span m=''226920''>All
  of--</span> <span m=''227480''>in</span> <span m=''227640''>this</span> <span m=''227790''>case,</span>
  <span m=''228000''>we</span> <span m=''228080''>have</span> <span m=''228180''>a</span>
  <span m=''228240''>tree--</span> <span m=''229110''>all</span> <span m=''229390''>of</span>
  <span m=''229490''>the</span> <span m=''229620''>angles</span> <span m=''230280''>here</span>
  <span m=''230680''>are</span> <span m=''230810''>fixed.</span> <span m=''231760''>But</span>
  <span m=''231890''>you</span> <span m=''232010''>can</span> <span m=''232140''>still,</span>
  <span m=''232480''>for</span> <span m=''232600''>example,</span> <span m=''232910''>take</span>
  <span m=''233100''>this</span> <span m=''233290''>entire</span> <span m=''233820''>sub</span>
  <span m=''234050''>chain</span> <span m=''234660''>and</span> <span m=''234870''>spin</span>
  <span m=''235190''>it</span> <span m=''235290''>around</span> <span m=''235580''>this</span>
  <span m=''235730''>edge.</span> <span m=''236680''>That''ll</span> <span m=''236900''>preserve</span>
  <span m=''237260''>all</span> <span m=''237350''>the</span> <span m=''237440''>angles</span>
  <span m=''237820''>and all</span> <span m=''237910''>the lengths.</span> <span m=''239410''>That''s</span>
  <span m=''239640''>all</span> <span m=''239790''>you''re</span> <span m=''239930''>allowed</span>
  <span m=''240150''>to</span> <span m=''240230''>do.</span> <span m=''240420''>You</span>
  <span m=''240530''>take</span> <span m=''240770''>an</span> <span m=''240840''>edge,</span>
  <span m=''241080''>you</span> <span m=''241170''>spin</span> <span m=''241660''>it--</span>
  <span m=''242020''>spin</span> <span m=''242300''>one</span> <span m=''242700''>half</span>
  <span m=''243100''>of</span> <span m=''243180''>the</span> <span m=''243320''>edge</span>
  <span m=''243510''>relative</span> <span m=''243870''>to</span> <span m=''243960''>the</span>
  <span m=''244060''>other</span> <span m=''244200''>half.</span> </p><p><span m=''245490''>These</span>
  <span m=''245700''>are</span> <span m=''245780''>called</span> <span m=''246220''>fixed</span>
  <span m=''246650''>angle</span> <span m=''246980''>linkages.</span> <span m=''249710''>And</span>
  <span m=''249930''>they have</span> <span m=''250090''>been</span> <span m=''250220''>studied</span>
  <span m=''251060''>quite</span> <span m=''251280''>a</span> <span m=''251330''>lot</span>
  <span m=''251620''>because</span> <span m=''252130''>of</span> <span m=''252300''>their</span>
  <span m=''252620''>connection</span> <span m=''253090''>to</span> <span m=''253260''>protein</span>
  <span m=''253630''>folding.</span> <span m=''259959''>So</span> <span m=''260120''>embedded</span>
  <span m=''260610''>in</span> <span m=''260860''>the</span> <span m=''260970''>term</span>
  <span m=''261209''>linkage,</span> <span m=''261690''>we</span> <span m=''261810''>assume</span>
  <span m=''262120''>that</span> <span m=''262240''>the</span> <span m=''262400''>edge</span>
  <span m=''262580''>lengths</span> <span m=''262820''>are</span> <span m=''262890''>fixed,</span>
  <span m=''263330''>and</span> <span m=''263460''>then</span> <span m=''263610''>we</span>
  <span m=''263760''>add</span> <span m=''264610''>the</span> <span m=''264730''>constraint</span>
  <span m=''265210''>that</span> <span m=''265290''>the</span> <span m=''265450''>angles</span>
  <span m=''265810''>are</span> <span m=''265890''>fixed.</span> <span m=''268420''>And</span>
  <span m=''268820''>the</span> <span m=''268890''>motivation</span> <span m=''269420''>is</span>
  <span m=''269560''>the</span> <span m=''269690''>backbone</span> <span m=''270460''>is</span>
  <span m=''270570''>something</span> <span m=''271010''>like--</span> <span m=''271670''>the</span>
  <span m=''271960''>backbone</span> <span m=''272340''>of</span> <span m=''272440''>a</span>
  <span m=''272510''>protein</span> <span m=''274530''>is</span> <span m=''274750''>something</span>
  <span m=''275090''>like</span> <span m=''275320''>a</span> <span m=''275420''>fixed</span>
  <span m=''275730''>angle</span> <span m=''275990''>tree.</span> <span m=''279480''>Of</span>
  <span m=''279520''>course,</span> <span m=''279850''>it''s</span> <span m=''279890''>not</span>
  <span m=''280150''>much</span> <span m=''280520''>of</span> <span m=''280600''>a</span>
  <span m=''280670''>tree.</span> <span m=''280950''>Most</span> <span m=''281270''>of</span>
  <span m=''281390''>it</span> <span m=''281500''>is</span> <span m=''281630''>a</span>
  <span m=''281710''>chain.</span> <span m=''282210''>There''s</span> <span m=''282400''>just</span>
  <span m=''283060''>small</span> <span m=''284210''>objects</span> <span m=''284660''>hanging</span>
  <span m=''285030''>off,</span> <span m=''285730''>and</span> <span m=''285850''>if</span>
  <span m=''285940''>you</span> <span m=''286070''>add</span> <span m=''286200''>the</span>
  <span m=''286310''>amino</span> <span m=''286570''>acid</span> <span m=''286930''>there
  are</span> <span m=''287100''>bigger</span> <span m=''287390''>things</span> <span
  m=''287640''>hanging</span> <span m=''287950''>off,</span> <span m=''288100''>but</span>
  <span m=''288240''>still</span> <span m=''288570''>constant</span> <span m=''288960''>size.</span>
  <span m=''290110''>They''ll</span> <span m=''290240''>have</span> <span m=''290390''>some</span>
  <span m=''290540''>cycles.</span> <span m=''291020''>They''re</span> <span m=''291090''>not</span>
  <span m=''291280''>trees.</span> <span m=''292170''>But</span> <span m=''294230''>it''s</span>
  <span m=''295070''>slightly</span> <span m=''295520''>more</span> <span m=''295730''>approximately--</span>
  <span m=''297000''>I should draw</span> <span m=''297760''>wavier</span> <span m=''297910''>lines.</span>
  <span m=''299760''>It''s</span> <span m=''299990''>a</span> <span m=''300050''>chain.</span>
  <span m=''301770''>Usually</span> <span m=''302190''>an</span> <span m=''302270''>open</span>
  <span m=''302530''>chain</span> <span m=''302840''>although</span> <span m=''302960''>occasionally</span>
  <span m=''303710''>a</span> <span m=''304000''>closed</span> <span m=''304290''>chain.</span>
  </p><p><span m=''311410''>So</span> <span m=''311700''>we</span> <span m=''311830''>think</span>
  <span m=''312000''>a</span> <span m=''312060''>lot</span> <span m=''312370''>about</span>
  <span m=''312700''>fixed angle</span> <span m=''312960''>chain</span> <span m=''313420''>and</span>
  <span m=''313520''>sometimes</span> <span m=''313950''>about</span> <span m=''314210''>fixed</span>
  <span m=''314490''>angle</span> <span m=''314760''>trees.</span> <span m=''315920''>Now,</span>
  <span m=''316910''>fixed</span> <span m=''317290''>angle</span> <span m=''317550''>linkages</span>
  <span m=''318040''>are</span> <span m=''318370''>harder</span> <span m=''318990''>to</span>
  <span m=''319100''>think</span> <span m=''319310''>about</span> <span m=''319700''>than</span>
  <span m=''320130''>universal</span> <span m=''320670''>joints--</span> <span m=''321030''>that''s</span>
  <span m=''321240''>the</span> <span m=''321340''>usual</span> <span m=''321640''>kind</span>
  <span m=''321850''>of</span> <span m=''321950''>linkage.</span> <span m=''324070''>So</span>
  <span m=''325050''>we</span> <span m=''325250''>know</span> <span m=''325450''>3D</span>
  <span m=''325880''>linkages</span> <span m=''326320''>are</span> <span m=''326690''>kind</span>
  <span m=''326860''>of</span> <span m=''326950''>tough.</span> <span m=''327310''>Nonetheless,</span>
  <span m=''327780''>we</span> <span m=''327870''>found</span> <span m=''328070''>lots</span>
  <span m=''328310''>of</span> <span m=''328430''>really</span> <span m=''328640''>interesting</span>
  <span m=''329020''>mathematical</span> <span m=''329610''>problems</span> <span
  m=''329960''>to</span> <span m=''330060''>solve</span> <span m=''330340''>here,</span>
  <span m=''330820''>and</span> <span m=''331160''>that</span> <span m=''331360''>is</span>
  <span m=''331620''>the</span> <span m=''331710''>topic</span> <span m=''332450''>of</span>
  <span m=''332600''>today.</span> </p><p><span m=''333280''>At</span> <span m=''333490''>some</span>
  <span m=''333790''>level,</span> <span m=''334420''>we</span> <span m=''334720''>are</span>
  <span m=''335870''>thinking</span> <span m=''336110''>about</span> <span m=''336410''>the</span>
  <span m=''336500''>mechanics</span> <span m=''337250''>of</span> <span m=''337370''>protein</span>
  <span m=''337740''>folding.</span> <span m=''338290''>We''re</span> <span m=''338530''>throwing</span>
  <span m=''339070''>away</span> <span m=''339350''>energy.</span> <span m=''339850''>We''re</span>
  <span m=''339970''>throwing</span> <span m=''340360''>away</span> <span m=''340750''>the</span>
  <span m=''341830''>actuators</span> <span m=''342750''>in</span> <span m=''342930''>real</span>
  <span m=''343180''>life</span> <span m=''343730''>that</span> <span m=''343870''>make</span>
  <span m=''344070''>proteins</span> <span m=''344480''>fold.</span> <span m=''345220''>We''re</span>
  <span m=''345350''>just</span> <span m=''345640''>imagining,</span> <span m=''346230''>given</span>
  <span m=''346630''>this</span> <span m=''347100''>mechanical</span> <span m=''347680''>model</span>
  <span m=''348000''>of</span> <span m=''348090''>how a</span> <span m=''348310''>protein</span>
  <span m=''348690''>might</span> <span m=''348860''>fold,</span> <span m=''350330''>what''s</span>
  <span m=''350610''>possible.</span> <span m=''351690''>So</span> <span m=''351920''>in</span>
  <span m=''352080''>some</span> <span m=''352230''>sense,</span> <span m=''352450''>it''s</span>
  <span m=''352570''>broader</span> <span m=''352960''>than</span> <span m=''353120''>reality.</span>
  <span m=''354420''>And</span> <span m=''354780''>the</span> <span m=''354850''>hope</span>
  <span m=''355090''>is</span> <span m=''355210''>you</span> <span m=''355330''>find</span>
  <span m=''355930''>an</span> <span m=''356130''>interesting</span> <span m=''356750''>algorithm</span>
  <span m=''357300''>for</span> <span m=''358170''>how</span> <span m=''358360''>to</span>
  <span m=''358440''>fold</span> <span m=''358740''>these</span> <span m=''358960''>protein</span>
  <span m=''359370''>chains.</span> <span m=''359920''>And</span> <span m=''360130''>maybe</span>
  <span m=''360410''>that''s</span> <span m=''360660''>the</span> <span m=''360760''>algorithm</span>
  <span m=''361140''>that</span> <span m=''361300''>nature</span> <span m=''361790''>is</span>
  <span m=''361980''>implementing.</span> <span m=''363410''>That''s</span> <span
  m=''363690''>the</span> <span m=''363810''>kind</span> <span m=''364010''>of</span>
  <span m=''364830''>general</span> <span m=''365120''>picture.</span> <span m=''365420''>We''re</span>
  <span m=''365560''>not</span> <span m=''365780''>constrained</span> <span m=''366300''>by</span>
  <span m=''367380''>reality,</span> <span m=''369120''>and</span> <span m=''369350''>by</span>
  <span m=''370090''>how</span> <span m=''370400''>nature</span> <span m=''370760''>actually</span>
  <span m=''371190''>folds</span> <span m=''371490''>things.</span> </p><p><span m=''375040''>So</span>
  <span m=''375210''>I''m</span> <span m=''375310''>going</span> <span m=''375400''>to</span>
  <span m=''375490''>talk</span> <span m=''375790''>today</span> <span m=''376190''>about</span>
  <span m=''376820''>four</span> <span m=''377400''>main</span> <span m=''378530''>problems</span>
  <span m=''380310''>here.</span> <span m=''382632''>The</span> <span m=''383110''>first</span>
  <span m=''383360''>one''s</span> <span m=''383550''>called</span> <span m=''383790''>span.</span>
  <span m=''385140''>Second</span> <span m=''385530''>one''s</span> <span m=''385900''>called</span>
  <span m=''386220''>flattening.</span> <span m=''389170''>Third</span> <span m=''389500''>one</span>
  <span m=''390050''>is</span> <span m=''391530''>flat</span> <span m=''391790''>state</span>
  <span m=''392070''>connectivity.</span> <span m=''401330''>And</span> <span m=''401660''>the</span>
  <span m=''401720''>fourth</span> <span m=''402050''>one</span> <span m=''403840''>is</span>
  <span m=''404150''>locked,</span> <span m=''405610''>our</span> <span m=''405750''>good</span>
  <span m=''405930''>friend</span> <span m=''406250''>locked</span> <span m=''406490''>chains.</span>
  <span m=''410420''>And</span> <span m=''410580''>of</span> <span m=''410680''>course</span>
  <span m=''410990''>there are locked</span> <span m=''411360''>chains</span> <span
  m=''411800''>because</span> <span m=''412460''>we''re</span> <span m=''412630''>constraining</span>
  <span m=''413110''>linkages</span> <span m=''413520''>even</span> <span m=''413750''>more</span>
  <span m=''414000''>than</span> <span m=''414160''>before.</span> <span m=''414580''>So</span>
  <span m=''414720''>you</span> <span m=''414810''>could</span> <span m=''414880''>take</span>
  <span m=''415100''>knitting</span> <span m=''415320''>needles,</span> <span m=''415650''>it''ll</span>
  <span m=''415790''>still</span> <span m=''416020''>be</span> <span m=''416140''>locked.</span>
  <span m=''416860''>So</span> <span m=''417010''>you</span> <span m=''417100''>add</span>
  <span m=''417430''>extra</span> <span m=''417770''>constraints.</span> <span m=''418690''>Makes</span>
  <span m=''418820''>it</span> <span m=''418890''>harder</span> <span m=''419150''>to</span>
  <span m=''419230''>fold.</span> <span m=''420470''>But</span> <span m=''420730''>there
  are</span> <span m=''420890''>actually</span> <span m=''421120''>some</span> <span
  m=''421280''>interesting</span> <span m=''421580''>positive</span> <span m=''422020''>results</span>
  <span m=''422460''>we</span> <span m=''422590''>can</span> <span m=''422780''>give</span>
  <span m=''423510''>of</span> <span m=''423560''>chains</span> <span m=''423870''>that</span>
  <span m=''424000''>are</span> <span m=''424120''>not</span> <span m=''424360''>locked</span>
  <span m=''424690''>in</span> <span m=''424760''>some</span> <span m=''424950''>sense.</span>
  </p><p><span m=''425800''>And</span> <span m=''425960''>flat state</span> <span
  m=''426320''>connectivity</span> <span m=''426615''>is</span> <span m=''426910''>about</span>
  <span m=''427190''>the</span> <span m=''427270''>same</span> <span m=''427570''>kind</span>
  <span m=''427760''>of</span> <span m=''427860''>thing,</span> <span m=''428510''>where</span>
  <span m=''428670''>instead</span> <span m=''428880''>of</span> <span m=''428950''>worrying</span>
  <span m=''429220''>about</span> <span m=''429440''>getting</span> <span m=''429630''>from</span>
  <span m=''429790''>anywhere</span> <span m=''430130''>to</span> <span m=''430180''>anywhere,</span>
  <span m=''430660''>we</span> <span m=''430770''>just</span> <span m=''431010''>worry</span>
  <span m=''431160''>about</span> <span m=''431370''>getting</span> <span m=''431580''>from</span>
  <span m=''431770''>one</span> <span m=''431940''>flat</span> <span m=''432280''>state</span>
  <span m=''432590''>to</span> <span m=''432690''>another</span> <span m=''432930''>flat</span>
  <span m=''433270''>state.</span> <span m=''433510''>Flat</span> <span m=''433810''>means</span>
  <span m=''434220''>lying</span> <span m=''434500''>in</span> <span m=''434590''>a</span>
  <span m=''434650''>plane.</span> <span m=''435500''>Flattening</span> <span m=''435980''>is</span>
  <span m=''436080''>about</span> <span m=''436460''>is</span> <span m=''436630''>there</span>
  <span m=''436750''>such</span> <span m=''437020''>a</span> <span m=''437220''>configuration.</span>
  <span m=''438940''>And</span> <span m=''439180''>span</span> <span m=''439850''>is</span>
  <span m=''440030''>about</span> <span m=''440830''>given</span> <span m=''442000''>robotic</span>
  <span m=''442480''>arm--</span> <span m=''442730''>like</span> <span m=''442920''>a</span>
  <span m=''442980''>more</span> <span m=''443150''>complicated</span> <span m=''443690''>one,</span>
  <span m=''443890''>like</span> <span m=''444110''>with</span> <span m=''444210''>multiple</span>
  <span m=''445320''>edges--</span> <span m=''445980''>how</span> <span m=''446200''>far</span>
  <span m=''447300''>apart</span> <span m=''447580''>can</span> <span m=''447660''>the</span>
  <span m=''447760''>endpoints</span> <span m=''448190''>get,</span> <span m=''448440''>and</span>
  <span m=''448550''>how</span> <span m=''448760''>close</span> <span m=''449070''>can</span>
  <span m=''449180''>the</span> <span m=''449280''>endpoints</span> <span m=''449720''>get.</span>
  <span m=''450470''>The</span> <span m=''450550''>universal</span> <span m=''451010''>chain</span>
  <span m=''451240''>is</span> <span m=''451350''>not</span> <span m=''451500''>very</span>
  <span m=''451720''>exciting.</span> <span m=''452690''>Farthest</span> <span m=''453050''>it</span>
  <span m=''453180''>can</span> <span m=''453430''>get is</span> <span m=''453540''>when</span>
  <span m=''453680''>it''s</span> <span m=''453810''>straight,</span> <span m=''454540''>and</span>
  <span m=''454920''>the</span> <span m=''455170''>least</span> <span m=''455460''>far</span>
  <span m=''455710''>it</span> <span m=''455820''>can</span> <span m=''455940''>get</span>
  <span m=''456060''>is</span> <span m=''456220''>when</span> <span m=''456490''>it''s</span>
  <span m=''456630''>closed.</span> <span m=''457290''>You</span> <span m=''457410''>can</span>
  <span m=''457540''>always</span> <span m=''457730''>do</span> <span m=''457840''>that,</span>
  <span m=''459350''>I</span> <span m=''459460''>think.</span> <span m=''460720''>Well,</span>
  <span m=''460980''>no,</span> <span m=''461160''>I guess</span> <span m=''461790''>you
  can''t</span> <span m=''461980''>always</span> <span m=''462290''>close</span> <span
  m=''462560''>it</span> <span m=''462630''>up.</span> <span m=''463790''>That''s</span>
  <span m=''464045''>a</span> <span m=''464300''>little</span> <span m=''464550''>nontrivial.</span>
  <span m=''466330''>But</span> <span m=''466640''>for</span> <span m=''466890''>fixed</span>
  <span m=''467170''>angle</span> <span m=''467430''>linkages,</span> <span m=''467820''>you</span>
  <span m=''467950''>can''t</span> <span m=''468210''>straighten</span> <span m=''468530''>out</span>
  <span m=''468810''>because</span> <span m=''469030''>you</span> <span m=''469120''>have</span>
  <span m=''469220''>to</span> <span m=''469320''>preserve</span> <span m=''469630''>the</span>
  <span m=''469730''>angles.</span> <span m=''470570''>So</span> <span m=''470880''>it''s</span>
  <span m=''471030''>kind</span> <span m=''471220''>of</span> <span m=''471290''>what</span>
  <span m=''471490''>is</span> <span m=''471640''>the</span> <span m=''471720''>straightest</span>
  <span m=''472560''>like</span> <span m=''472890''>configuration,</span> <span m=''473640''>given</span>
  <span m=''474030''>that the</span> <span m=''474120''>angles</span> <span m=''474460''>are</span>
  <span m=''474520''>fixed.</span> </p><p><span m=''477130''>So</span> <span m=''477230''>let''s</span>
  <span m=''477410''>start</span> <span m=''477600''>with</span> <span m=''477810''>span.</span>
  <span m=''489830''>So</span> <span m=''490020''>the</span> <span m=''490100''>span</span>
  <span m=''490670''>of</span> <span m=''491000''>a</span> <span m=''491100''>configuration</span>
  <span m=''492640''>is</span> <span m=''493070''>the</span> <span m=''493170''>distance</span>
  <span m=''495090''>between</span> <span m=''495450''>the</span> <span m=''495580''>endpoints.</span>
  <span m=''501470''>And</span> <span m=''504650''>in</span> <span m=''504750''>general,</span>
  <span m=''505180''>you''ll find</span> <span m=''505600''>the</span> <span m=''505710''>max</span>
  <span m=''506040''>span</span> <span m=''506520''>and</span> <span m=''506690''>the</span>
  <span m=''506750''>min</span> <span m=''506970''>span.</span> <span m=''508380''>This</span>
  <span m=''509290''>search</span> <span m=''509690''>was</span> <span m=''510280''>begun</span>
  <span m=''510760''>by</span> <span m=''511130''>a</span> <span m=''511150''>guy</span>
  <span m=''511270''>named</span> <span m=''511480''>Mike</span> <span m=''511740''>Soss,</span>
  <span m=''512400''>who</span> <span m=''512520''>was</span> <span m=''512740''>a</span>
  <span m=''512799''>PhD</span> <span m=''513159''>student</span> <span m=''513450''>at</span>
  <span m=''513539''>McGill.</span> <span m=''515890''>And</span> <span m=''516630''>he</span>
  <span m=''516740''>proved</span> <span m=''517289''>that</span> <span m=''517380''>if</span>
  <span m=''517510''>you</span> <span m=''517650''>want</span> <span m=''517809''>to</span>
  <span m=''517909''>find,</span> <span m=''520039''>for</span> <span m=''520210''>example,</span>
  <span m=''520620''>a flat</span> <span m=''521169''>state</span> <span m=''522600''>that</span>
  <span m=''522789''>lives</span> <span m=''523049''>in</span> <span m=''523210''>two</span>
  <span m=''523370''>dimensions</span> <span m=''527520''>with</span> <span m=''529170''>the</span>
  <span m=''529250''>minimum</span> <span m=''530950''>or</span> <span m=''531450''>the</span>
  <span m=''531530''>maximum</span> <span m=''532930''>span,</span> <span m=''535460''>this</span>
  <span m=''535810''>is</span> <span m=''536290''>NP-hard.</span> <span m=''539340''>This</span>
  <span m=''539510''>is</span> <span m=''539630''>in</span> <span m=''539750''>his</span>
  <span m=''539970''>PhD</span> <span m=''540390''>thesis.</span> <span m=''542860''>Question?</span>
  </p><p><span m=''545082''>AUDIENCE: If you have</span> <span m=''545576''>a</span>
  <span m=''546070''>linkage or</span> <span m=''546564''>[INAUDIBLE]</span> <span
  m=''547552''>chain</span> <span m=''548046''>that</span> <span m=''549034''>actually</span>
  <span m=''549528''>loops</span> <span m=''550022''>around,</span> <span m=''551504''>is</span>
  <span m=''551998''>there a</span> <span m=''552492''>span because</span> <span m=''552986''>there
  is no endpoint?</span> </p><p><span m=''553980''>PROFESSOR: Oh,</span> <span m=''554540''>here</span>
  <span m=''554780''>I''m</span> <span m=''554910''>assuming</span> <span m=''555370''>open</span>
  <span m=''555850''>chain--</span> <span m=''556350''>I</span> <span m=''556450''>should</span>
  <span m=''556680''>say</span> <span m=''556820''>that--</span> <span m=''562190''>which</span>
  <span m=''562440''>most</span> <span m=''562710''>proteins</span> <span m=''563020''>are.</span>
  <span m=''563750''>I''ve</span> <span m=''564100''>been</span> <span m=''564250''>talking</span>
  <span m=''564490''>about</span> <span m=''564680''>trees</span> <span m=''564980''>and</span>
  <span m=''565080''>stuff.</span> <span m=''565760''>Here</span> <span m=''566010''>I</span>
  <span m=''566030''>mean</span> <span m=''566250''>chain,</span> <span m=''566560''>otherwise</span>
  <span m=''567430''>there aren''t</span> <span m=''567690''>two</span> <span m=''567850''>end</span>
  <span m=''568020''>points to</span> <span m=''568400''>think</span> <span m=''568550''>about.</span>
  <span m=''570330''>Good.</span> <span m=''572570''>So</span> <span m=''572810''>here</span>
  <span m=''573130''>are his</span> <span m=''573480''>NP-hardness</span> <span m=''574150''>proofs.</span>
  <span m=''575040''>[INAUDIBLE]</span> <span m=''575330''>the</span> <span m=''575400''>problems</span>
  <span m=''575750''>are</span> <span m=''575800''>NP-complete.</span> <span m=''577180''>They''re</span>
  <span m=''577810''>pretty</span> <span m=''578560''>simple.</span> <span m=''579880''>The</span>
  <span m=''579940''>problem</span> <span m=''580280''>here we''re</span> <span m=''580540''>reducing</span>
  <span m=''581070''>from</span> <span m=''581360''>is</span> <span m=''581910''>partition.</span>
  <span m=''582840''>I</span> <span m=''582990''>give</span> <span m=''583080''>you</span>
  <span m=''583170''>a</span> <span m=''583200''>bunch</span> <span m=''583420''>of</span>
  <span m=''583490''>integers.</span> <span m=''584050''>I</span> <span m=''584150''>want</span>
  <span m=''584330''>to</span> <span m=''584390''>divide</span> <span m=''584710''>them</span>
  <span m=''584850''>into two</span> <span m=''585040''>halves</span> <span m=''585700''>of</span>
  <span m=''585900''>equal</span> <span m=''586140''>sum.</span> <span m=''587660''>And</span>
  <span m=''587910''>the</span> <span m=''588020''>top</span> <span m=''588360''>example</span>
  <span m=''589090''>is</span> <span m=''589540''>minimum</span> <span m=''590420''>flat</span>
  <span m=''590920''>span</span> <span m=''591410''>problem.</span> </p><p><span m=''592220''>So</span>
  <span m=''593230''>you</span> <span m=''593380''>make</span> <span m=''593560''>an</span>
  <span m=''593630''>orthogonal</span> <span m=''594200''>chain</span> <span m=''595210''>where</span>
  <span m=''595310''>the</span> <span m=''595400''>horizontal</span> <span m=''595900''>edges</span>
  <span m=''596150''>are</span> <span m=''596240''>long</span> <span m=''596720''>and</span>
  <span m=''596860''>they''re</span> <span m=''597060''>proportional</span> <span
  m=''597650''>to</span> <span m=''597840''>the</span> <span m=''597970''>integers</span>
  <span m=''598380''>you''re</span> <span m=''598440''>given,</span> <span m=''599220''>the</span>
  <span m=''599360''>vertical</span> <span m=''599730''>edges</span> <span m=''599980''>are</span>
  <span m=''600070''>really</span> <span m=''600280''>tiny.</span> <span m=''601490''>And</span>
  <span m=''601770''>so</span> <span m=''601990''>what</span> <span m=''602150''>you''d</span>
  <span m=''602300''>like</span> <span m=''602520''>to</span> <span m=''602640''>do--</span>
  <span m=''603460''>all</span> <span m=''603620''>you</span> <span m=''603760''>can</span>
  <span m=''603890''>do is</span> <span m=''604060''>sort</span> <span m=''604250''>of</span>
  <span m=''604340''>flip</span> <span m=''605230''>because</span> <span m=''605440''>you</span>
  <span m=''605550''>have</span> <span m=''605710''>to</span> <span m=''605820''>stay</span>
  <span m=''606000''>in</span> <span m=''606090''>the</span> <span m=''606180''>plane,</span>
  <span m=''606950''>you</span> <span m=''607080''>can</span> <span m=''607240''>flip</span>
  <span m=''607560''>one</span> <span m=''607720''>of</span> <span m=''607830''>the</span>
  <span m=''608230''>vertical</span> <span m=''608640''>edges,</span> <span m=''608920''>say,</span>
  <span m=''609340''>and</span> <span m=''609540''>make</span> <span m=''609840''>any</span>
  <span m=''610080''>of</span> <span m=''610130''>these</span> <span m=''610280''>edges</span>
  <span m=''610570''>go</span> <span m=''610700''>left</span> <span m=''610950''>or</span>
  <span m=''611090''>right.</span> <span m=''611690''>You</span> <span m=''611800''>get</span>
  <span m=''612070''>that</span> <span m=''612280''>freedom.</span> <span m=''614300''>So</span>
  <span m=''614670''>each</span> <span m=''614930''>integer,</span> <span m=''615240''>you</span>
  <span m=''615320''>get</span> <span m=''615460''>to</span> <span m=''615530''>choose.</span>
  <span m=''615840''>Do I</span> <span m=''615920''>go</span> <span m=''616080''>right</span>
  <span m=''616290''>by</span> <span m=''616370''>that</span> <span m=''616550''>amount</span>
  <span m=''616860''>and</span> <span m=''617090''>or</span> <span m=''617350''>do</span>
  <span m=''617470''>I</span> <span m=''617560''>go</span> <span m=''618040''>left</span>
  <span m=''618530''>by</span> <span m=''618660''>that</span> <span m=''618830''>amount?</span>
  <span m=''619590''>And</span> <span m=''619780''>if</span> <span m=''619930''>the</span>
  <span m=''620060''>amount</span> <span m=''620290''>you</span> <span m=''620380''>go</span>
  <span m=''620510''>left</span> <span m=''620770''>is</span> <span m=''620860''>equal</span>
  <span m=''621090''>to</span> <span m=''621170''>the</span> <span m=''621250''>amount</span>
  <span m=''621460''>you</span> <span m=''621540''>go</span> <span m=''621690''>right--</span>
  <span m=''621920''>in</span> <span m=''622000''>other</span> <span m=''622190''>words,</span>
  <span m=''622390''>is</span> <span m=''622500''>it</span> <span m=''622560''>partitioned</span>
  <span m=''623000''>into</span> <span m=''623190''>two</span> <span m=''623330''>equal</span>
  <span m=''623610''>sums--</span> <span m=''624490''>then</span> <span m=''624850''>those</span>
  <span m=''625100''>endpoints</span> <span m=''625490''>will</span> <span m=''625590''>be</span>
  <span m=''625720''>aligned,</span> <span m=''626280''>and</span> <span m=''626290''>then</span>
  <span m=''626420''>their</span> <span m=''626540''>distance</span> <span m=''626880''>will</span>
  <span m=''627000''>be</span> <span m=''627120''>very</span> <span m=''627340''>tiny.</span>
  <span m=''628000''>Otherwise,</span> <span m=''628450''>it</span> <span m=''628530''>will</span>
  <span m=''628620''>be</span> <span m=''628750''>quite</span> <span m=''628990''>large</span>
  <span m=''629270''>because</span> <span m=''629470''>the</span> <span m=''629530''>horizontal</span>
  <span m=''629970''>distances</span> <span m=''630480''>are</span> <span m=''630570''>all</span>
  <span m=''630680''>big.</span> <span m=''631860''>So</span> <span m=''632100''>it''s</span>
  <span m=''632240''>kind</span> <span m=''632410''>of</span> <span m=''632530''>a</span>
  <span m=''632930''>very</span> <span m=''633190''>easy</span> <span m=''633640''>NP-hardness</span>
  <span m=''634320''>proof.</span> </p><p><span m=''636160''>To</span> <span m=''636470''>maximize</span>
  <span m=''638420''>your</span> <span m=''638550''>flat</span> <span m=''638870''>span,</span>
  <span m=''639450''>instead</span> <span m=''639910''>of</span> <span m=''640060''>mapping</span>
  <span m=''640460''>your</span> <span m=''640600''>integers</span> <span m=''640990''>on</span>
  <span m=''641130''>to</span> <span m=''641240''>lengths,</span> <span m=''641550''>you</span>
  <span m=''641640''>map</span> <span m=''641860''>them</span> <span m=''642010''>on</span>
  <span m=''642120''>to</span> <span m=''642230''>angles--</span> <span m=''642960''>return</span>
  <span m=''643200''>angles.</span> <span m=''643690''>I</span> <span m=''643780''>won''t</span>
  <span m=''644140''>specify</span> <span m=''644780''>that</span> <span m=''644980''>too</span>
  <span m=''645110''>precisely.</span> <span m=''646170''>But</span> <span m=''646280''>again,</span>
  <span m=''646510''>if</span> <span m=''647220''>you</span> <span m=''647340''>make</span>
  <span m=''647560''>your</span> <span m=''647680''>total</span> <span m=''648620''>counterclockwise</span>
  <span m=''649260''>turn</span> <span m=''649470''>equal</span> <span m=''649780''>to</span>
  <span m=''649890''>your</span> <span m=''650000''>total</span> <span m=''650520''>clockwise</span>
  <span m=''651070''>turn,</span> <span m=''651930''>then</span> <span m=''652290''>the</span>
  <span m=''652420''>two</span> <span m=''652710''>end</span> <span m=''653080''>edges,</span>
  <span m=''653500''>which</span> <span m=''653680''>are</span> <span m=''653770''>super,</span>
  <span m=''654250''>super</span> <span m=''654460''>long,</span> <span m=''655230''>will</span>
  <span m=''655400''>be</span> <span m=''655540''>parallel.</span> <span m=''656670''>And</span>
  <span m=''657690''>to</span> <span m=''657880''>maximize</span> <span m=''658530''>the</span>
  <span m=''658600''>distance</span> <span m=''658920''>between</span> <span m=''659080''>the</span>
  <span m=''659140''>endpoints,</span> <span m=''659530''>you</span> <span m=''659610''>want</span>
  <span m=''659840''>them to</span> <span m=''659930''>be</span> <span m=''660090''>parallel.</span>
  <span m=''661150''>If</span> <span m=''661630''>you</span> <span m=''661760''>make</span>
  <span m=''661970''>them</span> <span m=''662100''>go</span> <span m=''662830''>some</span>
  <span m=''663060''>other</span> <span m=''663290''>angle,</span> <span m=''663940''>they''re</span>
  <span m=''664160''>closer.</span> <span m=''666690''>Now,</span> <span m=''666810''>both</span>
  <span m=''667170''>of</span> <span m=''667280''>these</span> <span m=''667540''>proofs</span>
  <span m=''667980''>rely</span> <span m=''668510''>on</span> <span m=''669580''>the</span>
  <span m=''670610''>requirement</span> <span m=''671890''>that</span> <span m=''672040''>you</span>
  <span m=''672170''>want</span> <span m=''672440''>a</span> <span m=''672480''>flat</span>
  <span m=''672920''>configuration</span> <span m=''673630''>with</span> <span m=''673790''>minimum</span>
  <span m=''674210''>or</span> <span m=''674250''>maximum</span> <span m=''674700''>span.</span>
  <span m=''675470''>Now,</span> <span m=''675610''>there''s</span> <span m=''675770''>a</span>
  <span m=''675830''>claim</span> <span m=''676210''>that</span> <span m=''676450''>flat</span>
  <span m=''676720''>configurations</span> <span m=''677370''>matter</span> <span
  m=''677820''>for</span> <span m=''677970''>proteins,</span> <span m=''680250''>so</span>
  <span m=''680650''>it''s</span> <span m=''680820''>a</span> <span m=''680880''>natural</span>
  <span m=''681690''>constraint.</span> <span m=''682300''>But</span> <span m=''682470''>what</span>
  <span m=''682630''>about</span> <span m=''682890''>the</span> <span m=''682960''>general</span>
  <span m=''683300''>problem?</span> <span m=''683800''>What</span> <span m=''683850''>about,</span>
  <span m=''684570''>I</span> <span m=''684690''>have</span> <span m=''684840''>something</span>
  <span m=''685160''>in</span> <span m=''685220''>three</span> <span m=''685450''>dimensions,</span>
  <span m=''685940''>I</span> <span m=''685990''>want</span> <span m=''686190''>to</span>
  <span m=''686230''>maximize--</span> <span m=''687080''>I</span> <span m=''687160''>have</span>
  <span m=''687280''>a</span> <span m=''687330''>fixed</span> <span m=''687590''>angle</span>
  <span m=''687810''>chain in</span> <span m=''688060''>3D,</span> <span m=''689030''>maximize</span>
  <span m=''689610''>or</span> <span m=''689670''>minimize</span> <span m=''690380''>the</span>
  <span m=''690460''>span?</span> </p><p><span m=''694530''>Both</span> <span m=''694740''>of</span>
  <span m=''694810''>those</span> <span m=''694980''>problems</span> <span m=''695290''>are</span>
  <span m=''695410''>open.</span> <span m=''696290''>Can</span> <span m=''696460''>you</span>
  <span m=''696550''>solve</span> <span m=''696840''>them</span> <span m=''697170''>in</span>
  <span m=''697280''>polynomial</span> <span m=''697820''>time?</span> <span m=''699010''>For</span>
  <span m=''701340''>3D</span> <span m=''702590''>max</span> <span m=''704150''>span,</span>
  <span m=''709240''>so</span> <span m=''709370''>the</span> <span m=''709520''>non</span>
  <span m=''709800''>flat</span> <span m=''710060''>version</span> <span m=''711130''>just</span>
  <span m=''711330''>for</span> <span m=''711450''>maximization,</span> <span m=''712710''>there''s</span>
  <span m=''712880''>been</span> <span m=''713030''>a</span> <span m=''713090''>lot</span>
  <span m=''713300''>of</span> <span m=''713370''>work.</span> <span m=''713940''>And</span>
  <span m=''714140''>there</span> <span m=''714230''>are</span> <span m=''714290''>two</span>
  <span m=''715180''>papers</span> <span m=''715680''>on</span> <span m=''715800''>the</span>
  <span m=''715870''>subject.</span> <span m=''716250''>One</span> <span m=''716410''>of</span>
  <span m=''716470''>them is</span> <span m=''716720''>by</span> <span m=''716870''>Nadia</span>
  <span m=''717610''>and</span> <span m=''718090''>Joe</span> <span m=''718350''>O''Rourke.</span>
  <span m=''719240''>Another</span> <span m=''719480''>one</span> <span m=''719750''>is</span>
  <span m=''720000''>by</span> <span m=''720510''>Borcea</span> <span m=''720770''>and</span>
  <span m=''721110''>Streinu.</span> <span m=''722830''>And</span> <span m=''725110''>I</span>
  <span m=''725190''>just</span> <span m=''725350''>want</span> <span m=''725460''>to</span>
  <span m=''725550''>quickly</span> <span m=''725890''>summarize</span> <span m=''726410''>that</span>
  <span m=''726660''>because</span> <span m=''727260''>there''s</span> <span m=''727440''>a</span>
  <span m=''727500''>lot</span> <span m=''727680''>of</span> <span m=''728230''>stuff</span>
  <span m=''728590''>there.</span> <span m=''728840''>But</span> <span m=''729130''>essentially,</span>
  <span m=''729510''>they</span> <span m=''729700''>find</span> <span m=''731230''>what</span>
  <span m=''731610''>the</span> <span m=''731710''>structure</span> <span m=''732410''>of</span>
  <span m=''732570''>those</span> <span m=''732830''>spans</span> <span m=''733510''>look</span>
  <span m=''733710''>like.</span> <span m=''733930''>I</span> <span m=''733970''>have</span>
  <span m=''734220''>an</span> <span m=''735220''>early</span> <span m=''736000''>figure</span>
  <span m=''736670''>that''s</span> <span m=''736920''>in</span> <span m=''737110''>our</span>
  <span m=''737220''>book</span> <span m=''737710''>before</span> <span m=''738030''>all</span>
  <span m=''738130''>this</span> <span m=''738280''>work</span> <span m=''738480''>was</span>
  <span m=''738640''>done.</span> </p><p><span m=''739870''>The</span> <span m=''739980''>simple</span>
  <span m=''740450''>chain,</span> <span m=''740880''>this</span> <span m=''741070''>black</span>
  <span m=''741360''>guy</span> <span m=''741720''>at</span> <span m=''741830''>1,</span>
  <span m=''742296''>2</span> <span m=''742762''>3,</span> <span m=''743560''>4</span>
  <span m=''743890''>bars</span> <span m=''744780''>open</span> <span m=''745070''>chain,</span>
  <span m=''745330''>and</span> <span m=''745450''>in</span> <span m=''745700''>that</span>
  <span m=''746300''>black</span> <span m=''746660''>three</span> <span m=''746860''>dimensional</span>
  <span m=''747250''>state,</span> <span m=''747710''>it</span> <span m=''748000''>maximizes</span>
  <span m=''748860''>the</span> <span m=''748950''>span,</span> <span m=''749460''>the</span>
  <span m=''749890''>green</span> <span m=''751020''>span</span> <span m=''751710''>there.</span>
  <span m=''752590''>And</span> <span m=''752750''>if</span> <span m=''752850''>you</span>
  <span m=''752970''>look</span> <span m=''753140''>from</span> <span m=''753320''>above,</span>
  <span m=''753790''>which</span> <span m=''753980''>is</span> <span m=''754090''>this</span>
  <span m=''754260''>picture--</span> <span m=''755460''>of course,</span> <span m=''755540''>the
  end points</span> <span m=''756060''>look</span> <span m=''756190''>much</span>
  <span m=''756380''>closer</span> <span m=''757400''>in</span> <span m=''758100''>projection--</span>
  <span m=''759470''>and</span> <span m=''760060''>the</span> <span m=''760590''>red</span>
  <span m=''761360''>configuration</span> <span m=''762090''>is</span> <span m=''762190''>the</span>
  <span m=''762280''>max</span> <span m=''762590''>span</span> <span m=''762800''>if</span>
  <span m=''762900''>you</span> <span m=''763030''>restrict</span> <span m=''763460''>to</span>
  <span m=''763500''>flat</span> <span m=''763880''>configurations.</span> <span m=''765050''>So</span>
  <span m=''765550''>here,</span> <span m=''765840''>of</span> <span m=''765940''>course,</span>
  <span m=''766170''>3D</span> <span m=''766510''>buys</span> <span m=''766840''>you</span>
  <span m=''766960''>something.</span> <span m=''767790''>In</span> <span m=''767890''>general,</span>
  <span m=''768880''>it</span> <span m=''769100''>always</span> <span m=''769390''>will.</span>
  <span m=''769870''>An</span> <span m=''770040''>interesting</span> <span m=''770540''>thing</span>
  <span m=''770820''>is</span> <span m=''771000''>that</span> <span m=''771120''>this</span>
  <span m=''771320''>max</span> <span m=''771710''>span--</span> <span m=''772880''>the</span>
  <span m=''773000''>green</span> <span m=''773420''>line--</span> <span m=''774130''>passes</span>
  <span m=''774700''>through</span> <span m=''774950''>another</span> <span m=''775240''>vertex.</span>
  <span m=''776740''>It</span> <span m=''776840''>seems</span> <span m=''777060''>kind</span>
  <span m=''777310''>of</span> <span m=''777420''>weird.</span> <span m=''778340''>And</span>
  <span m=''778580''>in</span> <span m=''778620''>fact,</span> <span m=''778860''>there''s</span>
  <span m=''779040''>a</span> <span m=''779100''>general</span> <span m=''781070''>theorem</span>
  <span m=''781480''>there</span> <span m=''781740''>sort of</span> <span m=''783070''>characterizing</span>
  <span m=''783640''>the</span> <span m=''783700''>structure</span> <span m=''784520''>of</span>
  <span m=''784630''>these</span> <span m=''784860''>chains.</span> <span m=''786000''>It''s</span>
  <span m=''786160''>still</span> <span m=''786370''>not</span> <span m=''786580''>known</span>
  <span m=''786810''>whether</span> <span m=''787000''>we</span> <span m=''787110''>can</span>
  <span m=''787220''>solve</span> <span m=''787450''>this</span> <span m=''787580''>problem</span>
  <span m=''787860''>in</span> <span m=''787950''>polynomial</span> <span m=''788450''>time.</span>
  </p><p><span m=''788830''>But</span> <span m=''789680''>for</span> <span m=''790070''>orthogonal</span>
  <span m=''791680''>chains,</span> <span m=''792270''>where</span> <span m=''792410''>all</span>
  <span m=''792550''>the</span> <span m=''792690''>angles</span> <span m=''795610''>are</span>
  <span m=''795850''>90</span> <span m=''796120''>degrees,</span> <span m=''803820''>we</span>
  <span m=''804020''>can</span> <span m=''804150''>solve</span> <span m=''804500''>that</span>
  <span m=''804780''>in</span> <span m=''806460''>linear</span> <span m=''806880''>time,</span>
  <span m=''807190''>I</span> <span m=''807250''>guess.</span> <span m=''811490''>And</span>
  <span m=''811750''>here''s</span> <span m=''812950''>what</span> <span m=''813130''>it</span>
  <span m=''813220''>looks</span> <span m=''813470''>like.</span> <span m=''819550''>Suppose</span>
  <span m=''819870''>you</span> <span m=''819960''>have</span> <span m=''820080''>some</span>
  <span m=''820280''>orthogonal</span> <span m=''820800''>chain.</span> <span m=''821020''>Orthogonal</span>
  <span m=''821480''>chains</span> <span m=''821750''>are</span> <span m=''821810''>nice</span>
  <span m=''822090''>because</span> <span m=''822380''>you</span> <span m=''822490''>can</span>
  <span m=''822600''>draw</span> <span m=''822780''>them</span> <span m=''822920''>in</span>
  <span m=''822980''>the</span> <span m=''823080''>plane</span> <span m=''823650''>as</span>
  <span m=''823870''>a</span> <span m=''823920''>staircase.</span> <span m=''824890''>So</span>
  <span m=''825030''>there''s</span> <span m=''825210''>a</span> <span m=''825250''>nice</span>
  <span m=''825880''>canonical</span> <span m=''826400''>configuration.</span> </p><p><span
  m=''830420''>One</span> <span m=''830780''>way</span> <span m=''830980''>to</span>
  <span m=''831200''>think</span> <span m=''831420''>about</span> <span m=''831890''>how</span>
  <span m=''832080''>to</span> <span m=''832160''>find</span> <span m=''832660''>the</span>
  <span m=''836230''>max</span> <span m=''836600''>span</span> <span m=''836830''>configuration--</span>
  <span m=''838320''>I''m</span> <span m=''838410''>just</span> <span m=''838790''>going</span>
  <span m=''838930''>to</span> <span m=''839310''>give</span> <span m=''839530''>a</span>
  <span m=''839630''>high</span> <span m=''839800''>level</span> <span m=''840040''>overview</span>
  <span m=''840400''>here,</span> <span m=''840630''>this</span> <span m=''840780''>won''t</span>
  <span m=''840950''>be</span> <span m=''841030''>a</span> <span m=''841070''>complete</span>
  <span m=''841390''>algorithm--</span> <span m=''842390''>is</span> <span m=''842550''>you</span>
  <span m=''842830''>triangulated</span> <span m=''843670''>that</span> <span m=''843980''>staircase</span>
  <span m=''845100''>in</span> <span m=''845260''>this</span> <span m=''845420''>sort</span>
  <span m=''845590''>of</span> <span m=''845680''>obvious</span> <span m=''846030''>way</span>
  <span m=''846200''>of</span> <span m=''846290''>connecting</span> <span m=''847170''>every</span>
  <span m=''847350''>endpoint</span> <span m=''847710''>to</span> <span m=''847800''>the</span>
  <span m=''847900''>one,</span> <span m=''848140''>two</span> <span m=''848320''>ahead.</span>
  <span m=''852290''>And</span> <span m=''852500''>think</span> <span m=''852770''>about</span>
  <span m=''853540''>this</span> <span m=''853770''>as</span> <span m=''853910''>like</span>
  <span m=''854110''>a</span> <span m=''854170''>body</span> <span m=''854630''>that''s</span>
  <span m=''854880''>hinging</span> <span m=''855680''>around</span> <span m=''856060''>here</span>
  <span m=''856280''>because</span> <span m=''856490''>I</span> <span m=''856570''>can</span>
  <span m=''857040''>spin--</span> <span m=''857890''>if I</span> <span m=''858010''>spin</span>
  <span m=''858330''>the</span> <span m=''858430''>left</span> <span m=''858740''>part</span>
  <span m=''858970''>of</span> <span m=''859040''>this</span> <span m=''859230''>chain</span>
  <span m=''859550''>around</span> <span m=''859880''>this</span> <span m=''860030''>edge,</span>
  <span m=''860310''>it''s</span> <span m=''860460''>like</span> <span m=''860640''>hinging</span>
  <span m=''860960''>that</span> <span m=''861150''>triangle</span> <span m=''861560''>around</span>
  <span m=''861810''>that</span> <span m=''861940''>hinge.</span> <span m=''862780''>Same</span>
  <span m=''863030''>thing.</span> <span m=''863740''>You</span> <span m=''863880''>could</span>
  <span m=''864030''>think</span> <span m=''864230''>of</span> <span m=''864320''>these</span>
  <span m=''864490''>triangles</span> <span m=''864980''>as</span> <span m=''865070''>just</span>
  <span m=''865280''>being</span> <span m=''865540''>hinged</span> <span m=''865800''>together,</span>
  <span m=''866270''>like</span> <span m=''866530''>in</span> <span m=''866800''>rigid</span>
  <span m=''867250''>origami.</span> <span m=''870070''>It''s</span> <span m=''870220''>the</span>
  <span m=''870280''>same</span> <span m=''870790''>class</span> <span m=''871180''>of</span>
  <span m=''871260''>motions.</span> </p><p><span m=''872940''>And</span> <span m=''873230''>now</span>
  <span m=''873820''>you</span> <span m=''874080''>can--</span> <span m=''875650''>what</span>
  <span m=''875770''>I''m</span> <span m=''875840''>going</span> <span m=''875940''>to</span>
  <span m=''876010''>do</span> <span m=''876100''>is</span> <span m=''876210''>compute</span>
  <span m=''876590''>a</span> <span m=''876780''>shortest</span> <span m=''877300''>path</span>
  <span m=''877630''>in</span> <span m=''877880''>this</span> <span m=''878170''>surface</span>
  <span m=''879260''>from</span> <span m=''879450''>here</span> <span m=''880430''>to</span>
  <span m=''880560''>here.</span> <span m=''881100''>Confusingly,</span> <span m=''881650''>this</span>
  <span m=''881810''>is</span> <span m=''881920''>called</span> <span m=''882140''>a</span>
  <span m=''882200''>geodesic</span> <span m=''882820''>shortest</span> <span m=''883140''>path</span>
  <span m=''883440''>although</span> <span m=''883540''>it''s</span> <span m=''883750''>not</span>
  <span m=''883900''>really</span> <span m=''884130''>related</span> <span m=''884640''>to</span>
  <span m=''884740''>geodesics</span> <span m=''885390''>from</span> <span m=''886330''>polyhedral</span>
  <span m=''886760''>surfaces.</span> <span m=''887870''>But</span> <span m=''888000''>if</span>
  <span m=''888150''>I</span> <span m=''888560''>compute</span> <span m=''888810''>a
  shortest</span> <span m=''889140''>path,</span> <span m=''889490''>it''s</span>
  <span m=''889660''>going</span> <span m=''889780''>to</span> <span m=''889850''>go</span>
  <span m=''890210''>like</span> <span m=''890370''>to</span> <span m=''890490''>this</span>
  <span m=''890750''>vertex</span> <span m=''891310''>and</span> <span m=''891430''>then</span>
  <span m=''891590''>probably</span> <span m=''892650''>to</span> <span m=''892990''>that</span>
  <span m=''893240''>vertex.</span> <span m=''893495''>But</span> <span m=''893750''>I''m</span>
  <span m=''893890''>constrained</span> <span m=''894400''>to</span> <span m=''894920''>stay</span>
  <span m=''895180''>inside</span> <span m=''895640''>the</span> <span m=''895720''>union</span>
  <span m=''896020''>of</span> <span m=''896130''>those</span> <span m=''896310''>triangles.</span>
  <span m=''896850''>I</span> <span m=''896920''>want</span> <span m=''897110''>to</span>
  <span m=''897160''>go</span> <span m=''897310''>from</span> <span m=''897480''>one</span>
  <span m=''897630''>endpoint</span> <span m=''897980''>to</span> <span m=''898080''>another.</span>
  </p><p><span m=''899340''>Then</span> <span m=''899790''>I</span> <span m=''899870''>claim</span>
  <span m=''901130''>that--</span> <span m=''902390''>OK,</span> <span m=''902570''>these</span>
  <span m=''903220''>two</span> <span m=''903390''>edges</span> <span m=''903690''>will</span>
  <span m=''903870''>stay</span> <span m=''904070''>planar,</span> <span m=''904440''>of</span>
  <span m=''904510''>course</span> <span m=''905090''>they</span> <span m=''905220''>form</span>
  <span m=''905460''>a</span> <span m=''905500''>triangle--</span> <span m=''906700''>I</span>
  <span m=''906810''>claim</span> <span m=''907300''>these</span> <span m=''908460''>four</span>
  <span m=''908810''>edges</span> <span m=''909200''>will</span> <span m=''909420''>stay</span>
  <span m=''909620''>planar,</span> <span m=''910270''>and in</span> <span m=''910590''>the</span>
  <span m=''910660''>orthogonal</span> <span m=''911050''>case</span> <span m=''911280''>they''ll</span>
  <span m=''911390''>stay</span> <span m=''911590''>zigzag.</span> <span m=''912920''>And</span>
  <span m=''913160''>then</span> <span m=''913380''>also</span> <span m=''913750''>these</span>
  <span m=''914010''>two</span> <span m=''914150''>guys</span> <span m=''914480''>will</span>
  <span m=''914580''>stay</span> <span m=''914960''>in</span> <span m=''915080''>their</span>
  <span m=''915250''>own</span> <span m=''915370''>plane.</span> <span m=''916430''>And</span>
  <span m=''916620''>then</span> <span m=''917840''>I</span> <span m=''917930''>claim</span>
  <span m=''918210''>that</span> <span m=''918330''>actually</span> <span m=''918590''>this</span>
  <span m=''918920''>wiggly</span> <span m=''919270''>line,</span> <span m=''919580''>which</span>
  <span m=''919740''>is</span> <span m=''919840''>not</span> <span m=''920110''>straight</span>
  <span m=''920960''>because</span> <span m=''921170''>it</span> <span m=''921530''>bends</span>
  <span m=''921820''>here</span> <span m=''922060''>and</span> <span m=''922130''>it
  bends</span> <span m=''922500''>here,</span> <span m=''923260''>the</span> <span
  m=''923360''>total</span> <span m=''923700''>length</span> <span m=''923910''>of</span>
  <span m=''923980''>that</span> <span m=''924130''>wiggly</span> <span m=''924390''>line</span>
  <span m=''924620''>is</span> <span m=''924820''>the</span> <span m=''924920''>max</span>
  <span m=''925180''>span.</span> </p><p><span m=''926180''>And</span> <span m=''926340''>you</span>
  <span m=''926440''>achieve</span> <span m=''926860''>that</span> <span m=''927460''>by</span>
  <span m=''927620''>folding</span> <span m=''928220''>this</span> <span m=''928430''>planar</span>
  <span m=''928780''>part</span> <span m=''929070''>with</span> <span m=''929210''>respect</span>
  <span m=''929580''>to</span> <span m=''929660''>this</span> <span m=''929860''>planar</span>
  <span m=''930120''>part</span> <span m=''930520''>with</span> <span m=''930730''>respect</span>
  <span m=''931040''>to</span> <span m=''931100''>this</span> <span m=''931300''>planar</span>
  <span m=''931500''>part</span> <span m=''932190''>so</span> <span m=''932480''>that</span>
  <span m=''932860''>the</span> <span m=''933220''>wiggly</span> <span m=''933500''>lines</span>
  <span m=''933790''>become</span> <span m=''934660''>aligned</span> <span m=''935100''>and</span>
  <span m=''935220''>straight.</span> <span m=''936570''>And</span> <span m=''936780''>that''s</span>
  <span m=''936980''>very</span> <span m=''937160''>hard</span> <span m=''937380''>to</span>
  <span m=''937470''>draw.</span> <span m=''937740''>But</span> <span m=''938150''>it</span>
  <span m=''938310''>can</span> <span m=''938470''>be</span> <span m=''938590''>done,</span>
  <span m=''939210''>and</span> <span m=''939420''>that''s</span> <span m=''939600''>what</span>
  <span m=''939720''>you</span> <span m=''939810''>do</span> <span m=''939990''>in</span>
  <span m=''940060''>the</span> <span m=''940140''>orthogonal</span> <span m=''940590''>case</span>
  <span m=''940880''>and</span> <span m=''940980''>that</span> <span m=''941140''>gives</span>
  <span m=''941300''>you</span> <span m=''942100''>the</span> <span m=''942400''>answer</span>
  <span m=''942730''>in</span> <span m=''942810''>linear</span> <span m=''943080''>time</span>
  <span m=''944890''>with</span> <span m=''945080''>enough</span> <span m=''945340''>work.</span>
  <span m=''948400''>For</span> <span m=''948570''>non</span> <span m=''948770''>orthogonal</span>
  <span m=''949250''>though,</span> <span m=''950080''>it''s</span> <span m=''950220''>open</span>
  <span m=''950680''>whether</span> <span m=''950880''>you can</span> <span m=''951130''>do</span>
  <span m=''951290''>this</span> <span m=''951490''>in</span> <span m=''951550''>polynomial</span>
  <span m=''952050''>time.</span> <span m=''952880''>Maybe</span> <span m=''953150''>it''s</span>
  <span m=''953270''>NP-hard,</span> <span m=''953770''>actually.</span> <span m=''954747''>I
  don''t know.</span> <span m=''965960''>That''s</span> <span m=''966100''>all</span>
  <span m=''966200''>I</span> <span m=''966260''>want</span> <span m=''966450''>to</span>
  <span m=''966510''>say</span> <span m=''966710''>about</span> <span m=''967050''>span.</span>
  </p><p><span m=''968490''>Next,</span> <span m=''968850''>we</span> <span m=''968970''>go</span>
  <span m=''969270''>to</span> <span m=''969510''>flattening.</span> <span m=''980550''>The</span>
  <span m=''980640''>first</span> <span m=''980900''>question</span> <span m=''981220''>about</span>
  <span m=''981840''>flattening,</span> <span m=''982640''>and</span> <span m=''982900''>the</span>
  <span m=''982980''>main</span> <span m=''983220''>one</span> <span m=''983860''>we''ll</span>
  <span m=''984090''>talk</span> <span m=''984330''>about</span> <span m=''984620''>here</span>
  <span m=''984920''>until</span> <span m=''985150''>we</span> <span m=''985270''>get</span>
  <span m=''985460''>to</span> <span m=''985540''>flat</span> <span m=''985970''>state</span>
  <span m=''986050''>connectivity,</span> <span m=''986550''>is</span> <span m=''987360''>does</span>
  <span m=''988350''>a</span> <span m=''988700''>fixed</span> <span m=''989030''>angle</span>
  <span m=''989290''>chain</span> <span m=''990050''>have</span> <span m=''990580''>a</span>
  <span m=''990670''>flat</span> <span m=''991020''>state</span> <span m=''991330''>at</span>
  <span m=''991420''>all?</span> <span m=''992740''>Can</span> <span m=''992830''>you</span>
  <span m=''992980''>even</span> <span m=''993190''>draw</span> <span m=''993460''>it</span>
  <span m=''993560''>in</span> <span m=''993760''>the</span> <span m=''993850''>plane</span>
  <span m=''995060''>without</span> <span m=''995400''>crossing?</span> <span m=''995880''>So</span>
  <span m=''996260''>we''re</span> <span m=''996950''>restricted</span> <span m=''997410''>here</span>
  <span m=''997600''>to</span> <span m=''997670''>have</span> <span m=''998700''>no</span>
  <span m=''999220''>self</span> <span m=''999490''>intersections.</span> <span m=''1000480''>We</span>
  <span m=''1000620''>want</span> <span m=''1001400''>flat</span> <span m=''1001760''>state,</span>
  <span m=''1006680''>no</span> <span m=''1006910''>self</span> <span m=''1007050''>intersection.</span>
  <span m=''1011020''>Then</span> <span m=''1011210''>there</span> <span m=''1011320''>would</span>
  <span m=''1011460''>be</span> <span m=''1011570''>a</span> <span m=''1011620''>question</span>
  <span m=''1012030''>of</span> <span m=''1012170''>given</span> <span m=''1012480''>some</span>
  <span m=''1012680''>configuration,</span> <span m=''1013270''>can I</span> <span
  m=''1013420''>actually</span> <span m=''1013970''>continuously</span> <span m=''1014620''>get</span>
  <span m=''1014800''>to</span> <span m=''1014890''>a</span> <span m=''1014960''>flat</span>
  <span m=''1015220''>state?</span> <span m=''1015660''>But</span> <span m=''1015760''>the</span>
  <span m=''1015910''>simplest</span> <span m=''1016310''>question is</span> <span
  m=''1016700''>ignore</span> <span m=''1018150''>getting</span> <span m=''1018440''>there.</span>
  <span m=''1018650''>Just,</span> <span m=''1018950''>is</span> <span m=''1019240''>there</span>
  <span m=''1019600''>a</span> <span m=''1019690''>flat</span> <span m=''1020010''>state?</span>
  <span m=''1021140''>And</span> <span m=''1021330''>this</span> <span m=''1021500''>problem</span>
  <span m=''1022310''>is</span> <span m=''1022640''>NP-hard.</span> <span m=''1024290''>Again,</span>
  <span m=''1024690''>Mike</span> <span m=''1024910''>Soss</span> <span m=''1025349''>and</span>
  <span m=''1025569''>his</span> <span m=''1025740''>advisor</span> <span m=''1026130''>Godfried</span>
  <span m=''1026460''>Toussaint.</span> </p><p><span m=''1029950''>It''s</span> <span
  m=''1030119''>a</span> <span m=''1030170''>little</span> <span m=''1030390''>more</span>
  <span m=''1030560''>complicated,</span> <span m=''1031109''>but</span> <span m=''1031220''>it''s</span>
  <span m=''1031369''>basically</span> <span m=''1031800''>the</span> <span m=''1031920''>same</span>
  <span m=''1032160''>idea</span> <span m=''1032550''>as that</span> <span m=''1032730''>very</span>
  <span m=''1032940''>simple</span> <span m=''1033310''>proof,</span> <span m=''1034630''>which</span>
  <span m=''1034849''>was</span> <span m=''1035060''>just</span> <span m=''1035280''>to</span>
  <span m=''1035329''>map</span> <span m=''1035650''>integers</span> <span m=''1036450''>to</span>
  <span m=''1037130''>a</span> <span m=''1037410''>little</span> <span m=''1037640''>zigzag</span>
  <span m=''1038589''>staircase</span> <span m=''1039170''>here.</span> <span m=''1040400''>So</span>
  <span m=''1040930''>the</span> <span m=''1041099''>goal</span> <span m=''1041380''>is</span>
  <span m=''1041480''>to</span> <span m=''1041579''>force</span> <span m=''1042470''>x</span>
  <span m=''1042829''>to</span> <span m=''1042930''>end</span> <span m=''1043180''>up</span>
  <span m=''1043560''>being--</span> <span m=''1043849''>the</span> <span m=''1044060''>two</span>
  <span m=''1044240''>endpoints</span> <span m=''1044680''>of</span> <span m=''1044760''>the</span>
  <span m=''1044839''>green</span> <span m=''1045099''>curve--</span> <span m=''1045470''>to</span>
  <span m=''1045569''>be</span> <span m=''1045710''>aligned</span> <span m=''1045990''>with</span>
  <span m=''1046119''>each</span> <span m=''1046290''>other.</span> <span m=''1046480''>That</span>
  <span m=''1046680''>will</span> <span m=''1046810''>exist</span> <span m=''1047210''>if</span>
  <span m=''1047329''>and</span> <span m=''1047420''>only</span> <span m=''1047690''>if</span>
  <span m=''1047829''>there</span> <span m=''1048030''>is</span> <span m=''1048140''>a</span>
  <span m=''1048210''>partition</span> <span m=''1048710''>of</span> <span m=''1049040''>given</span>
  <span m=''1049290''>integers.</span> <span m=''1050850''>And</span> <span m=''1051510''>there''s</span>
  <span m=''1051820''>all</span> <span m=''1051980''>this</span> <span m=''1052200''>infrastructure</span>
  <span m=''1052890''>that''s</span> <span m=''1053080''>sort of--</span> <span m=''1054570''>there''s</span>
  <span m=''1054650''>little</span> <span m=''1054980''>lock</span> <span m=''1055270''>here</span>
  <span m=''1055950''>and</span> <span m=''1056170''>a</span> <span m=''1056230''>key,</span>
  <span m=''1057100''>and</span> <span m=''1057720''>some</span> <span m=''1058210''>structure</span>
  <span m=''1058640''>on</span> <span m=''1058780''>the</span> <span m=''1058860''>left.</span>
  <span m=''1059470''>Basically</span> <span m=''1059990''>forces</span> <span m=''1060570''>the</span>
  <span m=''1060680''>picture</span> <span m=''1061330''>to</span> <span m=''1061460''>look</span>
  <span m=''1061650''>like</span> <span m=''1061840''>that.</span> </p><p><span m=''1063990''>So</span>
  <span m=''1064120''>the</span> <span m=''1064210''>first</span> <span m=''1064450''>claim</span>
  <span m=''1064660''>is</span> <span m=''1064770''>that</span> <span m=''1064880''>the</span>
  <span m=''1064950''>black</span> <span m=''1065330''>stuff</span> <span m=''1066200''>is</span>
  <span m=''1066510''>basically</span> <span m=''1067070''>unique.</span> <span m=''1067510''>I</span>
  <span m=''1067570''>think</span> <span m=''1067740''>there''s</span> <span m=''1067910''>one</span>
  <span m=''1068310''>global</span> <span m=''1068640''>reflection</span> <span m=''1069150''>you</span>
  <span m=''1069270''>can</span> <span m=''1069390''>do</span> <span m=''1070000''>that</span>
  <span m=''1070090''>doesn''t</span> <span m=''1070320''>affect</span> <span m=''1070610''>anything.</span>
  <span m=''1071290''>But you</span> <span m=''1071460''>try</span> <span m=''1071690''>any</span>
  <span m=''1071960''>of</span> <span m=''1072030''>the</span> <span m=''1072170''>other</span>
  <span m=''1072760''>flips.</span> <span m=''1073270''>Again,</span> <span m=''1073470''>we''re</span>
  <span m=''1073730''>restricted</span> <span m=''1074190''>to</span> <span m=''1074260''>flat</span>
  <span m=''1074590''>states</span> <span m=''1074890''>here.</span> <span m=''1075190''>So</span>
  <span m=''1075340''>there''s</span> <span m=''1075530''>only</span> <span m=''1075820''>sort</span>
  <span m=''1076010''>of</span> <span m=''1076110''>a</span> <span m=''1076700''>bounded</span>
  <span m=''1076980''>number</span> <span m=''1077200''>of</span> <span m=''1077270''>things</span>
  <span m=''1077470''>you</span> <span m=''1077590''>can</span> <span m=''1077700''>do,</span>
  <span m=''1077960''>a</span> <span m=''1077980''>finite</span> <span m=''1078250''>number</span>
  <span m=''1078450''>of</span> <span m=''1078520''>things</span> <span m=''1078680''>you</span>
  <span m=''1078800''>can</span> <span m=''1078920''>do.</span> <span m=''1079760''>You</span>
  <span m=''1079830''>try</span> <span m=''1080085''>all of</span> <span m=''1080340''>them,</span>
  <span m=''1080490''>they</span> <span m=''1080620''>self</span> <span m=''1080850''>intersect.</span>
  <span m=''1081890''>So</span> <span m=''1082030''>the</span> <span m=''1082120''>black</span>
  <span m=''1082380''>thing is</span> <span m=''1082630''>basically</span> <span m=''1083080''>forced,</span>
  <span m=''1083980''>and</span> <span m=''1084190''>it</span> <span m=''1084290''>forces</span>
  <span m=''1084840''>the</span> <span m=''1084990''>endpoint--</span> <span m=''1085480''>this</span>
  <span m=''1085660''>endpoint</span> <span m=''1086050''>x--</span> <span m=''1086320''>from</span>
  <span m=''1086460''>the</span> <span m=''1086550''>black</span> <span m=''1086930''>side</span>
  <span m=''1087650''>to</span> <span m=''1087830''>be</span> <span m=''1087960''>aligned</span>
  <span m=''1088420''>with</span> <span m=''1088560''>this</span> <span m=''1088760''>very</span>
  <span m=''1089140''>narrow</span> <span m=''1089510''>spike.</span> <span m=''1090970''>And</span>
  <span m=''1091680''>because</span> <span m=''1091920''>the</span> <span m=''1092030''>angles</span>
  <span m=''1092320''>are</span> <span m=''1092390''>preserved,</span> <span m=''1092740''>that</span>
  <span m=''1092920''>red</span> <span m=''1093110''>guy''s</span> <span m=''1093380''>going</span>
  <span m=''1093530''>to</span> <span m=''1093630''>be</span> <span m=''1093800''>vertical.</span>
  <span m=''1094240''>It</span> <span m=''1094290''>can''t</span> <span m=''1094470''>go</span>
  <span m=''1094620''>down</span> <span m=''1095140''>so</span> <span m=''1095300''>it</span>
  <span m=''1095340''>must</span> <span m=''1095550''>go</span> <span m=''1095710''>up.</span>
  </p><p><span m=''1096320''>And</span> <span m=''1096590''>so</span> <span m=''1096770''>only</span>
  <span m=''1097070''>if</span> <span m=''1097190''>this</span> <span m=''1097390''>thing</span>
  <span m=''1097560''>is</span> <span m=''1097660''>aligned</span> <span m=''1098560''>in</span>
  <span m=''1098720''>the</span> <span m=''1098810''>center,</span> <span m=''1099290''>aligned</span>
  <span m=''1099530''>with</span> <span m=''1099670''>x--</span> <span m=''1100690''>in</span>
  <span m=''1100780''>other</span> <span m=''1100920''>words,</span> <span m=''1101200''>this</span>
  <span m=''1101230''>problem</span> <span m=''1101770''>has</span> <span m=''1102120''>a</span>
  <span m=''1102190''>partition--</span> <span m=''1103570''>will</span> <span m=''1103950''>this</span>
  <span m=''1104440''>have</span> <span m=''1104760''>a</span> <span m=''1104820''>flat</span>
  <span m=''1105140''>state.</span> <span m=''1106580''>So</span> <span m=''1106770''>it''s</span>
  <span m=''1106900''>not</span> <span m=''1107850''>the</span> <span m=''1107970''>most</span>
  <span m=''1108200''>exciting</span> <span m=''1108570''>example.</span> <span m=''1108890''>This</span>
  <span m=''1109020''>is</span> <span m=''1109100''>only</span> <span m=''1109340''>a</span>
  <span m=''1109390''>weak</span> <span m=''1109760''>NP-hardness</span> <span m=''1110260''>proof.</span>
  <span m=''1111620''>Lots</span> <span m=''1111890''>of</span> <span m=''1111960''>interesting</span>
  <span m=''1112320''>questions</span> <span m=''1113130''>still</span> <span m=''1113450''>open</span>
  <span m=''1113690''>here,</span> <span m=''1114430''>like</span> <span m=''1114610''>if</span>
  <span m=''1114730''>all</span> <span m=''1114860''>the</span> <span m=''1114930''>links</span>
  <span m=''1115380''>are</span> <span m=''1116720''>the</span> <span m=''1116820''>same,</span>
  <span m=''1117660''>if they''re</span> <span m=''1117950''>all</span> <span m=''1118110''>equal,</span>
  <span m=''1119830''>then</span> <span m=''1120170''>we</span> <span m=''1120280''>don''t</span>
  <span m=''1120420''>know.</span> <span m=''1121270''>Or</span> <span m=''1121380''>if
  all the</span> <span m=''1121660''>links</span> <span m=''1121990''>are</span> <span
  m=''1122510''>even</span> <span m=''1122780''>polynomially</span> <span m=''1123320''>bounded,</span>
  <span m=''1123760''>this</span> <span m=''1123940''>needs</span> <span m=''1124160''>really,</span>
  <span m=''1124600''>really</span> <span m=''1124730''>long</span> <span m=''1125060''>lengths</span>
  <span m=''1125410''>verses</span> <span m=''1125820''>really,</span> <span m=''1126200''>really</span>
  <span m=''1126390''>tiny</span> <span m=''1126700''>links</span> <span m=''1126980''>exponentially--</span>
  <span m=''1128650''>exponential</span> <span m=''1128955''>in</span> <span m=''1129260''>ratio.</span>
  <span m=''1130640''>All</span> <span m=''1130810''>these</span> <span m=''1130950''>problems</span>
  <span m=''1131290''>are</span> <span m=''1131460''>open.</span> <span m=''1133080''>And</span>
  <span m=''1133140''>that''s</span> <span m=''1133290''>flattening.</span> <span
  m=''1134680''>So we''re</span> <span m=''1134850''>going</span> <span m=''1135120''>very</span>
  <span m=''1135320''>quickly</span> <span m=''1136200''>because</span> <span m=''1136390''>there</span>
  <span m=''1136740''>isn''t--</span> <span m=''1138110''>well,</span> <span m=''1138820''>partly</span>
  <span m=''1139100''>because</span> <span m=''1139330''>I''m</span> <span m=''1139650''>more</span>
  <span m=''1139830''>excited</span> <span m=''1140140''>about</span> <span m=''1140330''>this--</span>
  <span m=''1140490''>but</span> <span m=''1140600''>there''s</span> <span m=''1140750''>more</span>
  <span m=''1140960''>work</span> <span m=''1141210''>in</span> <span m=''1141370''>these</span>
  <span m=''1141570''>two</span> <span m=''1142180''>parts.</span> <span m=''1143420''>So</span>
  <span m=''1143630''>I''m</span> <span m=''1143900''>going</span> <span m=''1144000''>to</span>
  <span m=''1144070''>focus</span> <span m=''1144440''>on</span> <span m=''1144540''>that.</span>
  </p><p><span m=''1145220''>Next</span> <span m=''1145490''>topic</span> <span m=''1145890''>is</span>
  <span m=''1147010''>flat</span> <span m=''1147370''>state</span> <span m=''1147540''>connectivity.</span>
  <span m=''1161540''>So</span> <span m=''1162570''>the</span> <span m=''1162720''>idea</span>
  <span m=''1163060''>is</span> <span m=''1163310''>to</span> <span m=''1163470''>think</span>
  <span m=''1163660''>about</span> <span m=''1164000''>the</span> <span m=''1164150''>configuration</span>
  <span m=''1164870''>space</span> <span m=''1165340''>of</span> <span m=''1165450''>these</span>
  <span m=''1165690''>fixed</span> <span m=''1165960''>angle</span> <span m=''1166400''>chains,</span>
  <span m=''1166890''>let''s</span> <span m=''1167080''>say.</span> <span m=''1168470''>And</span>
  <span m=''1168650''>we</span> <span m=''1168780''>kind of</span> <span m=''1169090''>know</span>
  <span m=''1169300''>that</span> <span m=''1169470''>it''s</span> <span m=''1169620''>going</span>
  <span m=''1169730''>to</span> <span m=''1169800''>be</span> <span m=''1169920''>disconnected</span>
  <span m=''1170580''>because</span> <span m=''1170960''>there are</span> <span m=''1171120''>knitting</span>
  <span m=''1171370''>needles,</span> <span m=''1171650''>there</span> <span m=''1171930''>are</span>
  <span m=''1172060''>nasty</span> <span m=''1172450''>things.</span> <span m=''1173320''>So</span>
  <span m=''1173880''>there''s</span> <span m=''1174860''>maybe</span> <span m=''1175210''>various</span>
  <span m=''1175710''>connective</span> <span m=''1176090''>components.</span> <span
  m=''1180410''>But</span> <span m=''1180620''>let''s</span> <span m=''1180830''>say</span>
  <span m=''1181040''>that</span> <span m=''1181180''>we</span> <span m=''1181430''>really</span>
  <span m=''1181680''>care</span> <span m=''1182040''>about</span> <span m=''1183680''>flat</span>
  <span m=''1184160''>states.</span> </p><p><span m=''1187590''>And</span> <span m=''1187770''>the</span>
  <span m=''1187840''>question</span> <span m=''1188220''>is,</span> <span m=''1188520''>are</span>
  <span m=''1188700''>they</span> <span m=''1189000''>connected</span> <span m=''1190190''>to</span>
  <span m=''1190320''>each</span> <span m=''1190470''>other?</span> <span m=''1191080''>So</span>
  <span m=''1191220''>in</span> <span m=''1191290''>other</span> <span m=''1191440''>words,</span>
  <span m=''1191620''>do</span> <span m=''1191740''>all</span> <span m=''1191960''>the</span>
  <span m=''1192030''>flat</span> <span m=''1192360''>states--</span> <span m=''1193350''>mark</span>
  <span m=''1193550''>them</span> <span m=''1193680''>with</span> <span m=''1193810''>x''s--</span>
  <span m=''1194790''>do</span> <span m=''1194890''>they</span> <span m=''1195140''>all</span>
  <span m=''1195520''>appear?</span> <span m=''1195940''>There''s</span> <span m=''1196110''>only</span>
  <span m=''1196350''>finitely</span> <span m=''1196810''>many.</span> <span m=''1197330''>So</span>
  <span m=''1197540''>configurations,</span> <span m=''1198240''>there''s</span> <span
  m=''1198830''>this</span> <span m=''1199140''>continuum</span> <span m=''1199445''>that</span>
  <span m=''1199750''>there</span> <span m=''1199940''>are these</span> <span m=''1200120''>messy</span>
  <span m=''1200390''>blobs,</span> <span m=''1200780''>semi</span> <span m=''1201230''>algebraic</span>
  <span m=''1201640''>sets.</span> <span m=''1202420''>The</span> <span m=''1202520''>flat</span>
  <span m=''1202810''>states,</span> <span m=''1203380''>those</span> <span m=''1203650''>are</span>
  <span m=''1203740''>discrete</span> <span m=''1204220''>things.</span> <span m=''1205050''>Because</span>
  <span m=''1205280''>we</span> <span m=''1205380''>have</span> <span m=''1205510''>fixed</span>
  <span m=''1205770''>angles,</span> <span m=''1206150''>you</span> <span m=''1206260''>can</span>
  <span m=''1206380''>flip</span> <span m=''1206650''>or</span> <span m=''1206710''>not</span>
  <span m=''1206940''>flip</span> <span m=''1207150''>every</span> <span m=''1207410''>edge.</span>
  <span m=''1208150''>So</span> <span m=''1208190''>[INAUDIBLE]</span> <span m=''1208270''>most</span>
  <span m=''1208520''>exponentially</span> <span m=''1209060''>many</span> <span m=''1209320''>of</span>
  <span m=''1209380''>them,</span> <span m=''1209860''>so</span> <span m=''1210050''>finite.</span>
  <span m=''1211300''>Are</span> <span m=''1211480''>they</span> <span m=''1211660''>all</span>
  <span m=''1211940''>in</span> <span m=''1212070''>one</span> <span m=''1212330''>component?</span>
  <span m=''1212930''>So</span> <span m=''1213110''>I</span> <span m=''1213210''>can</span>
  <span m=''1213390''>get--</span> <span m=''1213990''>if</span> <span m=''1214120''>I</span>
  <span m=''1214190''>pick</span> <span m=''1214480''>two</span> <span m=''1214710''>of</span>
  <span m=''1214770''>my</span> <span m=''1214930''>favorite</span> <span m=''1215830''>flat</span>
  <span m=''1216100''>states,</span> <span m=''1216400''>there''s</span> <span m=''1216570''>a</span>
  <span m=''1216630''>path</span> <span m=''1216910''>between</span> <span m=''1217210''>them?</span>
  <span m=''1218090''>Or are</span> <span m=''1218480''>some</span> <span m=''1218890''>of</span>
  <span m=''1218990''>them</span> <span m=''1219370''>in</span> <span m=''1219730''>multiple</span>
  <span m=''1220110''>components?</span> </p><p><span m=''1221560''>So</span> <span
  m=''1221610''>in</span> <span m=''1221680''>this</span> <span m=''1221860''>case,</span>
  <span m=''1222310''>we</span> <span m=''1222480''>call</span> <span m=''1222750''>it</span>
  <span m=''1222900''>flat</span> <span m=''1223140''>state</span> <span m=''1223390''>disconnected.</span>
  <span m=''1227730''>And</span> <span m=''1228100''>if</span> <span m=''1228220''>they''re</span>
  <span m=''1228360''>all</span> <span m=''1228710''>like</span> <span m=''1228890''>this,</span>
  <span m=''1229250''>we</span> <span m=''1229380''>call</span> <span m=''1229620''>it</span>
  <span m=''1229740''>flat</span> <span m=''1229990''>state</span> <span m=''1230150''>connected.</span>
  <span m=''1232530''>And</span> <span m=''1232620''>we''d</span> <span m=''1232710''>just</span>
  <span m=''1232910''>like</span> <span m=''1233080''>to</span> <span m=''1233180''>know</span>
  <span m=''1233450''>which</span> <span m=''1234520''>chains,</span> <span m=''1235130''>which</span>
  <span m=''1235420''>fixed</span> <span m=''1235710''>angle</span> <span m=''1236010''>trees,</span>
  <span m=''1236530''>whatever,</span> <span m=''1237570''>are</span> <span m=''1237840''>flat</span>
  <span m=''1238150''>state</span> <span m=''1238400''>connected</span> <span m=''1239050''>versus</span>
  <span m=''1239360''>flat</span> <span m=''1239600''>state</span> <span m=''1239800''>disconnected.</span>
  <span m=''1241340''>I</span> <span m=''1241470''>would</span> <span m=''1241650''>say,</span>
  <span m=''1242850''>the</span> <span m=''1243590''>big</span> <span m=''1244010''>open</span>
  <span m=''1244280''>problem</span> <span m=''1244610''>here</span> <span m=''1245680''>is</span>
  <span m=''1248300''>every</span> <span m=''1248620''>fixed</span> <span m=''1249020''>angle</span>
  <span m=''1249570''>chain,</span> <span m=''1250490''>open</span> <span m=''1250760''>chain</span>
  <span m=''1251530''>flat</span> <span m=''1251840''>state</span> <span m=''1252110''>connected?</span>
  <span m=''1253572''>That is still</span> <span m=''1254040''>open.</span> <span
  m=''1254910''>We</span> <span m=''1254970''>have</span> <span m=''1255120''>lots</span>
  <span m=''1255540''>of</span> <span m=''1255730''>results</span> <span m=''1256190''>in</span>
  <span m=''1259540''>that</span> <span m=''1259720''>direction.</span> </p><p><span
  m=''1261220''>So</span> <span m=''1261290''>the</span> <span m=''1261420''>top</span>
  <span m=''1261820''>four</span> <span m=''1262210''>results</span> <span m=''1262590''>are</span>
  <span m=''1262650''>about</span> <span m=''1262870''>open</span> <span m=''1263210''>chains,</span>
  <span m=''1263620''>but</span> <span m=''1263750''>they</span> <span m=''1263840''>have</span>
  <span m=''1264020''>an</span> <span m=''1264110''>extra</span> <span m=''1264490''>constraint.</span>
  <span m=''1265510''>For</span> <span m=''1265850''>example,</span> <span m=''1266260''>open</span>
  <span m=''1266560''>chains</span> <span m=''1266890''>that</span> <span m=''1267000''>have</span>
  <span m=''1267410''>a</span> <span m=''1267480''>monotone</span> <span m=''1268070''>configuration,</span>
  <span m=''1268730''>like</span> <span m=''1269040''>the</span> <span m=''1269200''>staircase.</span>
  <span m=''1270520''>Those</span> <span m=''1271290''>are</span> <span m=''1271500''>flat</span>
  <span m=''1271760''>state</span> <span m=''1271910''>connected.</span> <span m=''1274440''>In</span>
  <span m=''1274580''>fact,</span> <span m=''1274860''>whenever</span> <span m=''1275230''>the</span>
  <span m=''1275710''>angles</span> <span m=''1276220''>between</span> <span m=''1276620''>the</span>
  <span m=''1276750''>edges</span> <span m=''1277210''>are</span> <span m=''1278000''>either</span>
  <span m=''1278280''>orthogonal</span> <span m=''1278820''>or</span> <span m=''1279150''>obtuse,</span>
  <span m=''1280740''>then</span> <span m=''1282120''>they''re</span> <span m=''1282250''>flat</span>
  <span m=''1282520''>state</span> <span m=''1282660''>connected.</span> <span m=''1284030''>When</span>
  <span m=''1284200''>the</span> <span m=''1284300''>angles</span> <span m=''1284580''>are</span>
  <span m=''1284680''>acute,</span> <span m=''1285220''>we''re</span> <span m=''1285410''>not</span>
  <span m=''1285600''>really</span> <span m=''1285810''>sure.</span> <span m=''1286400''>If</span>
  <span m=''1286610''>all</span> <span m=''1286750''>the</span> <span m=''1286850''>angles</span>
  <span m=''1287100''>are</span> <span m=''1287230''>equal</span> <span m=''1287620''>and</span>
  <span m=''1287860''>acute,</span> <span m=''1288650''>then</span> <span m=''1288850''>we</span>
  <span m=''1288950''>can</span> <span m=''1289100''>do</span> <span m=''1289260''>it.</span>
  <span m=''1289760''>But</span> <span m=''1289870''>if</span> <span m=''1289970''>they''re</span>
  <span m=''1290070''>different</span> <span m=''1290480''>and</span> <span m=''1290590''>acute,</span>
  <span m=''1290880''>we</span> <span m=''1290990''>don''t</span> <span m=''1291150''>know.</span>
  <span m=''1293090''>Unless</span> <span m=''1293680''>the</span> <span m=''1294210''>edges</span>
  <span m=''1294630''>are</span> <span m=''1294760''>all</span> <span m=''1294970''>unit</span>
  <span m=''1295290''>length</span> <span m=''1296310''>and</span> <span m=''1296500''>the</span>
  <span m=''1296610''>angles</span> <span m=''1296940''>are</span> <span m=''1297040''>in</span>
  <span m=''1297120''>this</span> <span m=''1297310''>funny</span> <span m=''1297580''>range,</span>
  <span m=''1298410''>then</span> <span m=''1298590''>we</span> <span m=''1298700''>can</span>
  <span m=''1298840''>do</span> <span m=''1298980''>it.</span> </p><p><span m=''1299210''>So
  there''s</span> <span m=''1299430''>all</span> <span m=''1299560''>these</span>
  <span m=''1299720''>special</span> <span m=''1300140''>cases</span> <span m=''1300630''>we</span>
  <span m=''1300670''>can</span> <span m=''1300800''>solve.</span> <span m=''1302020''>The</span>
  <span m=''1302250''>most</span> <span m=''1302550''>relevant</span> <span m=''1303010''>to</span>
  <span m=''1303120''>proteins</span> <span m=''1303620''>is</span> <span m=''1303740''>actually</span>
  <span m=''1304230''>obtuse</span> <span m=''1305080''>chains,</span> <span m=''1305770''>so</span>
  <span m=''1306110''>we''ve</span> <span m=''1306330''>solved</span> <span m=''1306720''>sort</span>
  <span m=''1306910''>of</span> <span m=''1306970''>the</span> <span m=''1307070''>main</span>
  <span m=''1307310''>problem</span> <span m=''1308470''>with</span> <span m=''1308600''>this</span>
  <span m=''1309140''>second</span> <span m=''1309470''>result.</span> <span m=''1310910''>But</span>
  <span m=''1311040''>there''s</span> <span m=''1311230''>a</span> <span m=''1311290''>natural</span>
  <span m=''1311840''>theoretical</span> <span m=''1312370''>question</span> <span
  m=''1312680''>here</span> <span m=''1312870''>is,</span> <span m=''1313000''>are</span>
  <span m=''1313450''>all</span> <span m=''1313960''>open</span> <span m=''1314210''>chains</span>
  <span m=''1314520''>flat state</span> <span m=''1314940''>connected</span> <span
  m=''1315970''>or</span> <span m=''1316450''>do</span> <span m=''1316580''>we</span>
  <span m=''1316700''>get</span> <span m=''1316980''>disconnectivity?</span> <span
  m=''1317590''>I</span> <span m=''1317690''>will</span> <span m=''1317810''>show</span>
  <span m=''1317980''>you</span> <span m=''1318170''>that--</span> <span m=''1318870''>I''ll</span>
  <span m=''1319000''>show</span> <span m=''1319170''>the</span> <span m=''1319320''>orthogonal</span>
  <span m=''1319780''>case</span> <span m=''1320100''>in</span> <span m=''1320210''>a</span>
  <span m=''1320270''>little</span> <span m=''1320460''>bit.</span> </p><p><span m=''1321890''>We</span>
  <span m=''1322080''>can</span> <span m=''1322200''>do</span> <span m=''1322300''>some</span>
  <span m=''1322500''>stuff if</span> <span m=''1322730''>you</span> <span m=''1322820''>have</span>
  <span m=''1322910''>multiple</span> <span m=''1323370''>chains</span> <span m=''1323780''>that</span>
  <span m=''1323900''>are</span> <span m=''1324040''>attached</span> <span m=''1324490''>to</span>
  <span m=''1324570''>some</span> <span m=''1325170''>blob</span> <span m=''1325590''>like</span>
  <span m=''1325780''>a</span> <span m=''1325850''>cell.</span> <span m=''1327100''>Closed</span>
  <span m=''1327450''>chains</span> <span m=''1327860''>is</span> <span m=''1327970''>a</span>
  <span m=''1328040''>little</span> <span m=''1328280''>bit--</span> <span m=''1330920''>for</span>
  <span m=''1331100''>disconnected,</span> <span m=''1333490''>we</span> <span m=''1333700''>don''t</span>
  <span m=''1333890''>have</span> <span m=''1335060''>very</span> <span m=''1335450''>interesting</span>
  <span m=''1335910''>examples,</span> <span m=''1336570''>I</span> <span m=''1336660''>would</span>
  <span m=''1336820''>say.</span> <span m=''1336970''>This</span> <span m=''1337120''>is</span>
  <span m=''1337250''>funny</span> <span m=''1337560''>because</span> <span m=''1338010''>locked</span>
  <span m=''1338320''>examples</span> <span m=''1338770''>are</span> <span m=''1338970''>easy</span>
  <span m=''1339230''>to</span> <span m=''1339330''>come</span> <span m=''1339540''>by</span>
  <span m=''1340410''>but</span> <span m=''1340750''>flat</span> <span m=''1340990''>state</span>
  <span m=''1341210''>disconnected</span> <span m=''1341750''>examples</span> <span
  m=''1342210''>are</span> <span m=''1342330''>little</span> <span m=''1342520''>trickier</span>
  <span m=''1342950''>because</span> <span m=''1343160''>flat</span> <span m=''1343440''>is</span>
  <span m=''1343570''>so</span> <span m=''1343880''>constrained.</span> <span m=''1345550''>So</span>
  <span m=''1345760''>let</span> <span m=''1345890''>me</span> <span m=''1346030''>just</span>
  <span m=''1346180''>show</span> <span m=''1346410''>you</span> <span m=''1346590''>these</span>
  <span m=''1346840''>examples.</span> </p><p><span m=''1349320''>This</span> <span
  m=''1349640''>is</span> <span m=''1349880''>what</span> <span m=''1350050''>we</span>
  <span m=''1350150''>call</span> <span m=''1350470''>a</span> <span m=''1350550''>partially</span>
  <span m=''1351270''>rigid</span> <span m=''1352820''>fixed</span> <span m=''1353060''>angle</span>
  <span m=''1353330''>tree.</span> <span m=''1353740''>So</span> <span m=''1353890''>not</span>
  <span m=''1354180''>only</span> <span m=''1354460''>are</span> <span m=''1354570''>the</span>
  <span m=''1354760''>angles</span> <span m=''1355580''>fixed,</span> <span m=''1356510''>but</span>
  <span m=''1356680''>also</span> <span m=''1357150''>the</span> <span m=''1357270''>black</span>
  <span m=''1357980''>edges</span> <span m=''1360200''>are</span> <span m=''1360380''>not--</span>
  <span m=''1360780''>in fact,</span> <span m=''1361120''>only</span> <span m=''1361390''>the</span>
  <span m=''1361500''>blue</span> <span m=''1361770''>edges</span> <span m=''1362100''>here</span>
  <span m=''1362380''>are</span> <span m=''1362520''>allowed</span> <span m=''1362810''>to</span>
  <span m=''1362900''>spin.</span> <span m=''1363650''>Everything</span> <span m=''1364070''>else</span>
  <span m=''1364340''>is</span> <span m=''1364660''>held</span> <span m=''1364900''>rigid.</span>
  <span m=''1365680''>So</span> <span m=''1365800''>these</span> <span m=''1366030''>arms</span>
  <span m=''1366390''>are</span> <span m=''1366480''>somehow</span> <span m=''1366890''>forced</span>
  <span m=''1367370''>to</span> <span m=''1367470''>be</span> <span m=''1367590''>in</span>
  <span m=''1367670''>exactly</span> <span m=''1368130''>that</span> <span m=''1368310''>geometry.</span>
  <span m=''1369310''>I</span> <span m=''1369340''>can</span> <span m=''1369530''>spin</span>
  <span m=''1369840''>it</span> <span m=''1370000''>around</span> <span m=''1370500''>this</span>
  <span m=''1370710''>edge,</span> <span m=''1371720''>so</span> <span m=''1372210''>spin</span>
  <span m=''1372520''>it</span> <span m=''1372640''>up</span> <span m=''1372850''>into</span>
  <span m=''1373080''>3D,</span> <span m=''1373520''>for</span> <span m=''1373650''>example.</span>
  <span m=''1374580''>These</span> <span m=''1374740''>are</span> <span m=''1374840''>two</span>
  <span m=''1375040''>different</span> <span m=''1375410''>flat</span> <span m=''1375700''>states</span>
  <span m=''1376020''>of</span> <span m=''1376120''>the</span> <span m=''1376220''>same</span>
  <span m=''1376610''>linkage.</span> </p><p><span m=''1379390''>The</span> <span
  m=''1379530''>only</span> <span m=''1379730''>difference</span> <span m=''1380120''>between</span>
  <span m=''1380370''>these</span> <span m=''1380570''>two--</span> <span m=''1381320''>I</span>
  <span m=''1381440''>haven''t</span> <span m=''1381660''>rotated</span> <span m=''1382160''>or</span>
  <span m=''1382240''>anything--</span> <span m=''1382560''>is that</span> <span m=''1382880''>I''ve</span>
  <span m=''1383060''>taken</span> <span m=''1383360''>each</span> <span m=''1383640''>of</span>
  <span m=''1383780''>these</span> <span m=''1384100''>arms</span> <span m=''1385160''>and</span>
  <span m=''1385470''>flipped</span> <span m=''1385830''>it</span> <span m=''1385910''>around</span>
  <span m=''1387110''>a</span> <span m=''1387220''>blue</span> <span m=''1387460''>axis.</span>
  <span m=''1388740''>If</span> <span m=''1388810''>I</span> <span m=''1388870''>do</span>
  <span m=''1389040''>all</span> <span m=''1389270''>four</span> <span m=''1389580''>of</span>
  <span m=''1389660''>them,</span> <span m=''1389940''>I</span> <span m=''1390080''>would</span>
  <span m=''1390220''>get</span> <span m=''1390370''>this</span> <span m=''1390530''>picture.</span>
  <span m=''1390880''>But</span> <span m=''1391010''>the</span> <span m=''1391110''>claim</span>
  <span m=''1391380''>is,</span> <span m=''1391490''>you</span> <span m=''1391630''>cannot</span>
  <span m=''1392020''>do</span> <span m=''1392140''>that</span> <span m=''1392440''>without</span>
  <span m=''1392820''>self</span> <span m=''1393200''>intersection.</span> <span m=''1394570''>The</span>
  <span m=''1394700''>intuition</span> <span m=''1395220''>is,</span> <span m=''1395630''>when</span>
  <span m=''1395740''>there</span> <span m=''1396000''>aren''t</span> <span m=''1396200''>very--</span>
  <span m=''1396720''>oh,</span> <span m=''1397170''>one</span> <span m=''1397390''>other</span>
  <span m=''1397560''>thing</span> <span m=''1398676''>that</span> <span m=''1399040''>makes</span>
  <span m=''1399320''>it</span> <span m=''1399380''>slightly</span> <span m=''1399800''>more</span>
  <span m=''1399970''>interesting.</span> <span m=''1400300''>It''s</span> <span m=''1400400''>weird</span>
  <span m=''1400670''>to</span> <span m=''1400750''>say,</span> <span m=''1401010''>well</span>
  <span m=''1401160''>why</span> <span m=''1401380''>did</span> <span m=''1401520''>you</span>
  <span m=''1401640''>force</span> <span m=''1401930''>some</span> <span m=''1402170''>of</span>
  <span m=''1402210''>the</span> <span m=''1402340''>edges</span> <span m=''1402610''>to</span>
  <span m=''1402710''>be</span> <span m=''1402840''>rigid</span> <span m=''1403100''>and</span>
  <span m=''1403250''>not</span> <span m=''1403470''>others?</span> <span m=''1404940''>One</span>
  <span m=''1405240''>way</span> <span m=''1405390''>to</span> <span m=''1405480''>force</span>
  <span m=''1405830''>that</span> <span m=''1406110''>is</span> <span m=''1406270''>to</span>
  <span m=''1406400''>use</span> <span m=''1406560''>a</span> <span m=''1406900''>general</span>
  <span m=''1407230''>graph.</span> <span m=''1408150''>If</span> <span m=''1408230''>you</span>
  <span m=''1408350''>add</span> <span m=''1408650''>some</span> <span m=''1408810''>extra</span>
  <span m=''1409130''>edges</span> <span m=''1409650''>to sort of</span> <span m=''1409770''>brace</span>
  <span m=''1410140''>this</span> <span m=''1410350''>and</span> <span m=''1410460''>all</span>
  <span m=''1410640''>these</span> <span m=''1410810''>angles</span> <span m=''1411110''>are</span>
  <span m=''1411190''>fixed,</span> <span m=''1411970''>then</span> <span m=''1412160''>this</span>
  <span m=''1412390''>linkage</span> <span m=''1412750''>will</span> <span m=''1412880''>behave</span>
  <span m=''1413290''>exactly</span> <span m=''1413730''>like</span> <span m=''1413910''>that</span>
  <span m=''1414100''>one.</span> <span m=''1415340''>So</span> <span m=''1415420''>that</span>
  <span m=''1415690''>at</span> <span m=''1415770''>least</span> <span m=''1417400''>is</span>
  <span m=''1417620''>somewhat</span> <span m=''1418010''>more</span> <span m=''1418180''>natural,</span>
  <span m=''1418560''>although</span> <span m=''1418840''>what</span> <span m=''1419090''>we</span>
  <span m=''1419210''>really</span> <span m=''1419430''>care</span> <span m=''1419630''>about</span>
  <span m=''1419920''>are</span> <span m=''1420840''>chains,</span> <span m=''1421950''>maybe</span>
  <span m=''1422310''>trees.</span> <span m=''1423730''>But</span> <span m=''1423900''>we</span>
  <span m=''1424010''>don''t</span> <span m=''1424240''>know</span> <span m=''1424440''>whether</span>
  <span m=''1424660''>there''s a--</span> <span m=''1425570''>we</span> <span m=''1425700''>also</span>
  <span m=''1425940''>don''t</span> <span m=''1426110''>know</span> <span m=''1426290''>whether</span>
  <span m=''1426530''>all</span> <span m=''1427920''>fixed</span> <span m=''1428210''>angle</span>
  <span m=''1428450''>trees</span> <span m=''1428890''>are</span> <span m=''1429040''>flat</span>
  <span m=''1429320''>state</span> <span m=''1429460''>connected.</span> <span m=''1430470''>These</span>
  <span m=''1430650''>are</span> <span m=''1430720''>the</span> <span m=''1432340''>worst</span>
  <span m=''1432560''>examples</span> <span m=''1432970''>we</span> <span m=''1433070''>know.</span>
  </p><p><span m=''1434100''>Let</span> <span m=''1434230''>me</span> <span m=''1434340''>give</span>
  <span m=''1434480''>you</span> <span m=''1434530''>an</span> <span m=''1434610''>idea</span>
  <span m=''1434840''>of</span> <span m=''1434910''>why</span> <span m=''1435440''>it</span>
  <span m=''1437230''>doesn''t</span> <span m=''1437500''>work.</span> <span m=''1437920''>This</span>
  <span m=''1438000''>is</span> <span m=''1438120''>a</span> <span m=''1438170''>little</span>
  <span m=''1438420''>animation</span> <span m=''1438730''>of</span> <span m=''1440440''>just</span>
  <span m=''1440720''>a</span> <span m=''1440850''>couple</span> <span m=''1441220''>of</span>
  <span m=''1441380''>moves</span> <span m=''1441940''>attempted,</span> <span m=''1442290''>and
  it''s just</span> <span m=''1442400''>going</span> <span m=''1442840''>cycle</span>
  <span m=''1443880''>through</span> <span m=''1444080''>that.</span> <span m=''1446690''>And</span>
  <span m=''1446900''>these</span> <span m=''1447090''>are</span> <span m=''1447180''>some</span>
  <span m=''1449310''>static</span> <span m=''1449780''>images</span> <span m=''1450340''>of</span>
  <span m=''1450550''>the</span> <span m=''1450610''>same</span> <span m=''1450910''>kind</span>
  <span m=''1451120''>of</span> <span m=''1451240''>thing.</span> <span m=''1452910''>So</span>
  <span m=''1453070''>the</span> <span m=''1453170''>intuition</span> <span m=''1453630''>is</span>
  <span m=''1453770''>the</span> <span m=''1453850''>following--</span> <span m=''1454300''>you
  have</span> <span m=''1454450''>four arms.</span> <span m=''1455480''>You</span>
  <span m=''1455600''>have</span> <span m=''1455830''>two</span> <span m=''1456300''>sides</span>
  <span m=''1456810''>to</span> <span m=''1456920''>the</span> <span m=''1457020''>plane,</span>
  <span m=''1457300''>there''s</span> <span m=''1457490''>up</span> <span m=''1457780''>and</span>
  <span m=''1457940''>down.</span> <span m=''1459250''>The</span> <span m=''1459350''>four
  arms</span> <span m=''1460230''>and</span> <span m=''1460400''>two</span> <span
  m=''1460550''>sides,</span> <span m=''1462000''>at</span> <span m=''1462150''>least</span>
  <span m=''1462500''>two</span> <span m=''1462740''>of</span> <span m=''1462830''>them</span>
  <span m=''1463000''>are</span> <span m=''1463060''>going</span> <span m=''1463160''>to</span>
  <span m=''1463200''>have</span> <span m=''1463300''>to</span> <span m=''1463390''>go</span>
  <span m=''1463520''>to</span> <span m=''1463600''>the</span> <span m=''1463720''>same</span>
  <span m=''1464000''>side.</span> <span m=''1464780''>The</span> <span m=''1464910''>best</span>
  <span m=''1465160''>you</span> <span m=''1465260''>can</span> <span m=''1465330''>do</span>
  <span m=''1465440''>is</span> <span m=''1465570''>two</span> <span m=''1465770''>and</span>
  <span m=''1465880''>two,</span> <span m=''1466210''>or</span> <span m=''1466310''>three</span>
  <span m=''1466540''>and</span> <span m=''1466630''>one.</span> <span m=''1467020''>But</span>
  <span m=''1467470''>in</span> <span m=''1467600''>either</span> <span m=''1467780''>case,</span>
  <span m=''1468060''>you</span> <span m=''1468140''>have</span> <span m=''1468420''>two</span>
  <span m=''1468650''>sides</span> <span m=''1469640''>go</span> <span m=''1469760''>to</span>
  <span m=''1469820''>the--</span> <span m=''1470300''>two</span> <span m=''1470780''>arms</span>
  <span m=''1471200''>that</span> <span m=''1471290''>go</span> <span m=''1471450''>on</span>
  <span m=''1471560''>the</span> <span m=''1471620''>same</span> <span m=''1471870''>side.</span>
  </p><p><span m=''1472700''>Now,</span> <span m=''1472910''>it</span> <span m=''1473060''>could</span>
  <span m=''1473300''>be,</span> <span m=''1474050''>like</span> <span m=''1474290''>in</span>
  <span m=''1474450''>this</span> <span m=''1474810''>image,</span> <span m=''1475400''>that</span>
  <span m=''1475570''>they''re</span> <span m=''1475860''>opposite</span> <span m=''1476380''>arms.</span>
  <span m=''1477100''>So</span> <span m=''1477310''>there''s</span> <span m=''1477540''>this</span>
  <span m=''1477780''>arm</span> <span m=''1478060''>here</span> <span m=''1479060''>and</span>
  <span m=''1479430''>there''s</span> <span m=''1479650''>this</span> <span m=''1479900''>arm</span>
  <span m=''1480120''>here.</span> <span m=''1481260''>So</span> <span m=''1481390''>they''re</span>
  <span m=''1481570''>connected</span> <span m=''1482160''>by</span> <span m=''1482290''>a</span>
  <span m=''1482390''>180</span> <span m=''1482770''>degree</span> <span m=''1483070''>angle.</span>
  <span m=''1484260''>And</span> <span m=''1484660''>those</span> <span m=''1485000''>guys,</span>
  <span m=''1485310''>when</span> <span m=''1485470''>they</span> <span m=''1485670''>fold</span>
  <span m=''1485990''>up,</span> <span m=''1486460''>actually</span> <span m=''1486940''>these</span>
  <span m=''1487220''>edges</span> <span m=''1487630''>will</span> <span m=''1487730''>just</span>
  <span m=''1487900''>hit</span> <span m=''1488080''>each</span> <span m=''1488290''>other</span>
  <span m=''1488870''>dead on.</span> <span m=''1490160''>So</span> <span m=''1490400''>that''s</span>
  <span m=''1492010''>kind</span> <span m=''1492250''>of</span> <span m=''1492360''>obvious</span>
  <span m=''1492690''>from</span> <span m=''1492850''>a</span> <span m=''1492910''>geometric</span>
  <span m=''1493380''>standpoint.</span> <span m=''1493780''>Maybe</span> <span m=''1494060''>you
  call</span> <span m=''1494280''>it</span> <span m=''1494360''>cheating</span> <span
  m=''1494680''>for</span> <span m=''1494760''>them</span> <span m=''1494900''>to</span>
  <span m=''1494960''>hit</span> <span m=''1495140''>dead</span> <span m=''1495330''>on.</span>
  <span m=''1495520''>You</span> <span m=''1495650''>can</span> <span m=''1495920''>twiddle</span>
  <span m=''1496190''>the</span> <span m=''1496310''>edge</span> <span m=''1496520''>lengths</span>
  <span m=''1496830''>so</span> <span m=''1496910''>that</span> <span m=''1497010''>they</span>
  <span m=''1497160''>will</span> <span m=''1497520''>properly</span> <span m=''1497940''>intersect</span>
  <span m=''1499120''>without</span> <span m=''1499930''>dead</span> <span m=''1500110''>on</span>
  <span m=''1500320''>collision,</span> <span m=''1501060''>without</span> <span m=''1501350''>being</span>
  <span m=''1501550''>degenerate</span> <span m=''1502010''>basically.</span> <span
  m=''1504040''>The</span> <span m=''1504250''>alternative</span> <span m=''1504920''>is</span>
  <span m=''1505100''>that--</span> <span m=''1505340''>and</span> <span m=''1505500''>this</span>
  <span m=''1505660''>is</span> <span m=''1505750''>a</span> <span m=''1505790''>little</span>
  <span m=''1506010''>harder</span> <span m=''1506360''>to</span> <span m=''1506450''>see</span>
  <span m=''1506650''>geometrically,</span> <span m=''1507290''>and</span> <span m=''1507360''>that''s</span>
  <span m=''1507830''>why</span> <span m=''1508080''>we</span> <span m=''1508220''>drew</span>
  <span m=''1508370''>that</span> <span m=''1508990''>animation--</span> <span m=''1510040''>is</span>
  <span m=''1510320''>that</span> <span m=''1510450''>you</span> <span m=''1513280''>have</span>
  <span m=''1513450''>one</span> <span m=''1513720''>arm</span> <span m=''1514000''>and</span>
  <span m=''1514080''>you</span> <span m=''1514160''>have</span> <span m=''1514310''>an</span>
  <span m=''1514390''>adjacent</span> <span m=''1514960''>arm</span> <span m=''1515260''>connected</span>
  <span m=''1515600''>by</span> <span m=''1515730''>a</span> <span m=''1515780''>90</span>
  <span m=''1516060''>degree</span> <span m=''1516340''>angle.</span> </p><p><span
  m=''1517410''>Now</span> <span m=''1517430''>here,</span> <span m=''1517810''>there''s</span>
  <span m=''1518060''>clearly</span> <span m=''1518350''>some</span> <span m=''1518540''>collision</span>
  <span m=''1518910''>going</span> <span m=''1519170''>on.</span> <span m=''1519560''>And</span>
  <span m=''1519740''>if</span> <span m=''1519840''>you</span> <span m=''1519950''>happen</span>
  <span m=''1520320''>to</span> <span m=''1520380''>fold</span> <span m=''1520680''>it</span>
  <span m=''1520730''>up</span> <span m=''1520880''>90</span> <span m=''1521170''>degrees</span>
  <span m=''1521510''>like</span> <span m=''1521670''>that</span> <span m=''1521890''>and
  then fold</span> <span m=''1522280''>the</span> <span m=''1522400''>other</span>
  <span m=''1522540''>guy,</span> <span m=''1522700''>obviously</span> <span m=''1523130''>you
  get</span> <span m=''1523310''>stuck.</span> <span m=''1524170''>But</span> <span
  m=''1524330''>maybe</span> <span m=''1524730''>you fold it</span> <span m=''1524930''>a</span>
  <span m=''1525070''>little</span> <span m=''1525350''>bit</span> <span m=''1525650''>and</span>
  <span m=''1525720''>the</span> <span m=''1525830''>other</span> <span m=''1525960''>guy</span>
  <span m=''1526090''>goes</span> <span m=''1526290''>a</span> <span m=''1526330''>little</span>
  <span m=''1526490''>bit</span> <span m=''1526620''>more</span> <span m=''1527110''>and</span>
  <span m=''1527510''>there</span> <span m=''1527640''>could</span> <span m=''1527790''>be</span>
  <span m=''1527920''>some</span> <span m=''1528210''>dance</span> <span m=''1528590''>between</span>
  <span m=''1528910''>those</span> <span m=''1529180''>two</span> <span m=''1529460''>degrees</span>
  <span m=''1529780''>of</span> <span m=''1529870''>freedom,</span> <span m=''1530270''>those</span>
  <span m=''1530500''>two</span> <span m=''1530650''>arms,</span> <span m=''1531620''>that</span>
  <span m=''1531810''>somehow</span> <span m=''1532410''>gets</span> <span m=''1532670''>them</span>
  <span m=''1533470''>both</span> <span m=''1533770''>to</span> <span m=''1533920''>pass</span>
  <span m=''1534270''>over</span> <span m=''1534410''>to</span> <span m=''1534580''>the</span>
  <span m=''1534680''>other side.</span> <span m=''1535290''>It''s obviously</span>
  <span m=''1535530''>not</span> <span m=''1535590''>possible.</span> <span m=''1536260''>How</span>
  <span m=''1536470''>do</span> <span m=''1536540''>you</span> <span m=''1536630''>prove</span>
  <span m=''1536900''>it?</span> <span m=''1537830''>Well,</span> <span m=''1538540''>you</span>
  <span m=''1538710''>could</span> <span m=''1538860''>prove</span> <span m=''1539090''>it</span>
  <span m=''1539170''>with</span> <span m=''1539440''>topology--</span> <span m=''1540340''>knot</span>
  <span m=''1541090''>theory</span> <span m=''1541410''>or</span> <span m=''1541490''>link</span>
  <span m=''1541900''>theory.</span> <span m=''1543330''>So</span> <span m=''1543550''>it''s
  a</span> <span m=''1543660''>very</span> <span m=''1543860''>cute</span> <span m=''1544150''>proof.</span>
  </p><p><span m=''1545390''>You</span> <span m=''1545580''>start</span> <span m=''1546040''>with--</span>
  <span m=''1547250''>so</span> <span m=''1547400''>here''s</span> <span m=''1547680''>the</span>
  <span m=''1548030''>full</span> <span m=''1548240''>example,</span> <span m=''1548650''>but</span>
  <span m=''1548780''>I''ve</span> <span m=''1548890''>highlighted</span> <span m=''1549390''>the</span>
  <span m=''1549490''>two</span> <span m=''1549780''>arms</span> <span m=''1550110''>in</span>
  <span m=''1550230''>red</span> <span m=''1551010''>that</span> <span m=''1551180''>are</span>
  <span m=''1551360''>going</span> <span m=''1551710''>to</span> <span m=''1551920''>move.</span>
  <span m=''1552990''>And</span> <span m=''1553120''>I</span> <span m=''1553210''>imagine</span>
  <span m=''1553750''>connecting</span> <span m=''1554270''>the</span> <span m=''1554420''>endpoints</span>
  <span m=''1555660''>of</span> <span m=''1556040''>each</span> <span m=''1556340''>arm</span>
  <span m=''1557210''>with</span> <span m=''1557480''>these</span> <span m=''1557670''>little</span>
  <span m=''1558210''>blue</span> <span m=''1558500''>ropes</span> <span m=''1559720''>underneath</span>
  <span m=''1560370''>the</span> <span m=''1560490''>plane.</span> <span m=''1562160''>They''re</span>
  <span m=''1562300''>both</span> <span m=''1562520''>going</span> <span m=''1562720''>on</span>
  <span m=''1562800''>the</span> <span m=''1562860''>same</span> <span m=''1563090''>side.</span>
  <span m=''1563370''>Let''s</span> <span m=''1563600''>say</span> <span m=''1563740''>they</span>
  <span m=''1563860''>somehow</span> <span m=''1564290''>pass</span> <span m=''1564560''>through</span>
  <span m=''1564700''>each</span> <span m=''1564810''>other</span> <span m=''1564990''>on</span>
  <span m=''1565140''>the</span> <span m=''1565240''>top</span> <span m=''1565510''>side.</span>
  <span m=''1566310''>Then</span> <span m=''1566480''>I''m</span> <span m=''1566650''>free</span>
  <span m=''1566940''>to</span> <span m=''1567040''>connect</span> <span m=''1567350''>stuff</span>
  <span m=''1567590''>on</span> <span m=''1567660''>the</span> <span m=''1567740''>bottom,</span>
  <span m=''1568220''>and</span> <span m=''1568290''>I</span> <span m=''1568350''>shouldn''t</span>
  <span m=''1568640''>collide</span> <span m=''1568950''>with</span> <span m=''1569060''>that.</span>
  <span m=''1570400''>So</span> <span m=''1570640''>if</span> <span m=''1570990''>somehow,</span>
  <span m=''1572150''>both</span> <span m=''1572400''>of</span> <span m=''1572480''>these</span>
  <span m=''1572660''>guys</span> <span m=''1572930''>flip</span> <span m=''1573190''>over--</span>
  <span m=''1574210''>so</span> <span m=''1575520''>arm</span> <span m=''1575760''>on</span>
  <span m=''1575850''>the</span> <span m=''1575930''>left,</span> <span m=''1576280''>A3</span>
  <span m=''1577280''>flips</span> <span m=''1577630''>over.</span> <span m=''1578350''>A3</span>
  <span m=''1578670''>stays</span> <span m=''1578960''>where</span> <span m=''1579100''>it</span>
  <span m=''1579160''>is</span> <span m=''1579410''>but</span> <span m=''1579590''>now</span>
  <span m=''1580680''>the</span> <span m=''1580850''>arm</span> <span m=''1581080''>is</span>
  <span m=''1581200''>on</span> <span m=''1581300''>the</span> <span m=''1581500''>top,</span>
  <span m=''1582020''>the</span> <span m=''1582190''>north</span> <span m=''1582450''>side</span>
  <span m=''1582770''>instead</span> <span m=''1583060''>of</span> <span m=''1583150''>the</span>
  <span m=''1583230''>south</span> <span m=''1583530''>side.</span> </p><p></p><p><span
  m=''1584580''>And</span> <span m=''1585750''>the</span> <span m=''1586020''>other</span>
  <span m=''1586300''>guy,</span> <span m=''1587450''>from</span> <span m=''1587660''>B
  to</span> <span m=''1588100''>B3,</span> <span m=''1589240''>used</span> <span m=''1589490''>to</span>
  <span m=''1589550''>go</span> <span m=''1589740''>like</span> <span m=''1589930''>this</span>
  <span m=''1590490''>and</span> <span m=''1590710''>now it</span> <span m=''1590940''>goes</span>
  <span m=''1591120''>like</span> <span m=''1591300''>this.</span> <span m=''1591800''>If</span>
  <span m=''1592010''>that</span> <span m=''1592210''>happens</span> <span m=''1592660''>somehow,</span>
  <span m=''1593900''>then</span> <span m=''1594040''>these</span> <span m=''1594180''>ropes</span>
  <span m=''1594560''>could</span> <span m=''1594720''>remain</span> <span m=''1595000''>intact</span>
  <span m=''1595410''>during</span> <span m=''1595610''>that</span> <span m=''1595750''>whole</span>
  <span m=''1595910''>motion.</span> <span m=''1596450''>On</span> <span m=''1596570''>the</span>
  <span m=''1596720''>top,</span> <span m=''1597570''>you</span> <span m=''1597650''>have</span>
  <span m=''1597880''>two</span> <span m=''1598780''>closed</span> <span m=''1599170''>loops</span>
  <span m=''1599530''>that</span> <span m=''1599660''>are</span> <span m=''1599770''>not</span>
  <span m=''1600260''>interlocked.</span> <span m=''1601370''>On</span> <span m=''1601450''>the</span>
  <span m=''1601520''>bottom,</span> <span m=''1601880''>you</span> <span m=''1601950''>have</span>
  <span m=''1602130''>two</span> <span m=''1602290''>closed</span> <span m=''1602600''>loops</span>
  <span m=''1602850''>that</span> <span m=''1603010''>are</span> <span m=''1603230''>interlocked.</span>
  <span m=''1604130''>So</span> <span m=''1604290''>there''s</span> <span m=''1604440''>no</span>
  <span m=''1604660''>way</span> <span m=''1604780''>to</span> <span m=''1604840''>get</span>
  <span m=''1605030''>from</span> <span m=''1605170''>there</span> <span m=''1605320''>to</span>
  <span m=''1605390''>there</span> <span m=''1605580''>without</span> <span m=''1605870''>colliding</span>
  <span m=''1606320''>somewhere.</span> <span m=''1607050''>The</span> <span m=''1607140''>blue</span>
  <span m=''1607340''>stuff</span> <span m=''1607590''>didn''t</span> <span m=''1607800''>move,</span>
  <span m=''1608310''>so</span> <span m=''1608470''>the</span> <span m=''1608570''>red</span>
  <span m=''1608750''>stuff</span> <span m=''1608970''>must</span> <span m=''1609250''>have
  collided.</span> <span m=''1610610''>So</span> <span m=''1610760''>even</span> <span
  m=''1611000''>just</span> <span m=''1611190''>topologically,</span> <span m=''1611950''>you</span>
  <span m=''1612130''>are</span> <span m=''1612330''>screwed.</span> <span m=''1616310''>That</span>
  <span m=''1616590''>is</span> <span m=''1616690''>their</span> <span m=''1616900''>only</span>
  <span m=''1617170''>negative</span> <span m=''1617540''>example.</span> <span m=''1619130''>Lots</span>
  <span m=''1619390''>of</span> <span m=''1619590''>interesting</span> <span m=''1620000''>open</span>
  <span m=''1620210''>questions</span> <span m=''1620630''>here.</span> </p><p><span
  m=''1622420''>On</span> <span m=''1622680''>the</span> <span m=''1622770''>positive</span>
  <span m=''1623240''>side,</span> <span m=''1625140''>let</span> <span m=''1625360''>me</span>
  <span m=''1625470''>show</span> <span m=''1625780''>you</span> <span m=''1626690''>for</span>
  <span m=''1627260''>orthogonal</span> <span m=''1627950''>chains--</span> <span
  m=''1628360''>and</span> <span m=''1628440''>the</span> <span m=''1628510''>same</span>
  <span m=''1628820''>algorithm</span> <span m=''1629210''>works</span> <span m=''1629430''>for</span>
  <span m=''1629660''>obtuse</span> <span m=''1630230''>chains,</span> <span m=''1630810''>all</span>
  <span m=''1630950''>the</span> <span m=''1631040''>angles</span> <span m=''1631300''>are</span>
  <span m=''1631370''>obtuse--</span> <span m=''1632870''>how</span> <span m=''1633350''>they</span>
  <span m=''1633570''>are</span> <span m=''1633680''>flat</span> <span m=''1634020''>state</span>
  <span m=''1634310''>connected.</span> <span m=''1635310''>So</span> <span m=''1635580''>in</span>
  <span m=''1635640''>order</span> <span m=''1635770''>to</span> <span m=''1635810''>show</span>
  <span m=''1635990''>it''s</span> <span m=''1636120''>flat state</span> <span m=''1636530''>connected,</span>
  <span m=''1637910''>I</span> <span m=''1637990''>want</span> <span m=''1638140''>to</span>
  <span m=''1638190''>think</span> <span m=''1638380''>about</span> <span m=''1638680''>two</span>
  <span m=''1638890''>flat</span> <span m=''1639220''>states</span> <span m=''1640260''>and</span>
  <span m=''1640460''>show</span> <span m=''1640720''>that</span> <span m=''1640960''>I</span>
  <span m=''1641070''>can</span> <span m=''1641910''>fold</span> <span m=''1642190''>from</span>
  <span m=''1642350''>one</span> <span m=''1642500''>to</span> <span m=''1642590''>the</span>
  <span m=''1642730''>other</span> <span m=''1643650''>via</span> <span m=''1643930''>some</span>
  <span m=''1644130''>intermediate</span> <span m=''1644630''>3D</span> <span m=''1645370''>stuff.</span>
  <span m=''1647620''>Let''s</span> <span m=''1647840''>start</span> <span m=''1648050''>with</span>
  <span m=''1648180''>one</span> <span m=''1648410''>of</span> <span m=''1648500''>the</span>
  <span m=''1648580''>flat</span> <span m=''1648870''>states.</span> </p><p><span
  m=''1650650''>So</span> <span m=''1650860''>it''s</span> <span m=''1650980''>orthogonal.</span>
  <span m=''1652260''>So</span> <span m=''1652450''>in</span> <span m=''1652970''>two</span>
  <span m=''1653170''>dimensions,</span> <span m=''1654370''>all</span> <span m=''1654590''>the</span>
  <span m=''1654720''>edges</span> <span m=''1654990''>will</span> <span m=''1655100''>be</span>
  <span m=''1655210''>horizontal</span> <span m=''1655790''>or</span> <span m=''1655830''>vertical.</span>
  <span m=''1656250''>In</span> <span m=''1656340''>3D,</span> <span m=''1656740''>they</span>
  <span m=''1656870''>can</span> <span m=''1657080''>kind</span> <span m=''1657280''>of</span>
  <span m=''1657360''>be</span> <span m=''1657530''>in</span> <span m=''1657620''>many,</span>
  <span m=''1658740''>many</span> <span m=''1658840''>different</span> <span m=''1659090''>angles,</span>
  <span m=''1660240''>many</span> <span m=''1660470''>different</span> <span m=''1660750''>dihedral</span>
  <span m=''1660950''>triangles.</span> <span m=''1661345''>In</span> <span m=''1661740''>2D,</span>
  <span m=''1662110''>it''s</span> <span m=''1662280''>pretty</span> <span m=''1662470''>simple.</span>
  <span m=''1663500''>And</span> <span m=''1663830''>all</span> <span m=''1663990''>I</span>
  <span m=''1664050''>need</span> <span m=''1664240''>to</span> <span m=''1664320''>do</span>
  <span m=''1664500''>is</span> <span m=''1664590''>sort</span> <span m=''1664760''>of</span>
  <span m=''1664840''>pick</span> <span m=''1665190''>up</span> <span m=''1665340''>that</span>
  <span m=''1665600''>chain,</span> <span m=''1666010''>and</span> <span m=''1666210''>I''m</span>
  <span m=''1666290''>going</span> <span m=''1666380''>to</span> <span m=''1666530''>try</span>
  <span m=''1666710''>to</span> <span m=''1666800''>pick</span> <span m=''1667000''>it</span>
  <span m=''1667080''>up</span> <span m=''1667220''>into</span> <span m=''1667460''>a</span>
  <span m=''1667530''>staircase</span> <span m=''1668130''>because</span> <span m=''1668290''>there''s</span>
  <span m=''1668440''>only</span> <span m=''1668650''>one</span> <span m=''1668940''>staircase.</span>
  <span m=''1669750''>If</span> <span m=''1669870''>I</span> <span m=''1669940''>can</span>
  <span m=''1670070''>make</span> <span m=''1670280''>it</span> <span m=''1670350''>a</span>
  <span m=''1670410''>staircase,</span> <span m=''1671460''>I</span> <span m=''1671570''>make</span>
  <span m=''1672690''>flat</span> <span m=''1672890''>configuration</span> <span m=''1673180''>A</span>
  <span m=''1673470''>a</span> <span m=''1673610''>staircase,</span> <span m=''1673890''>flat</span>
  <span m=''1674170''>configuration</span> <span m=''1674850''>B</span> <span m=''1675010''>a</span>
  <span m=''1675050''>staircase,</span> <span m=''1675910''>and just</span> <span
  m=''1676190''>FedEx</span> <span m=''1676610''>in</span> <span m=''1676670''>the</span>
  <span m=''1676740''>middle.</span> <span m=''1678230''>Once</span> <span m=''1678470''>they''re</span>
  <span m=''1678540''>both</span> <span m=''1678720''>staircases,</span> <span m=''1679450''>I</span>
  <span m=''1679570''>play</span> <span m=''1679820''>one</span> <span m=''1680010''>motion</span>
  <span m=''1680300''>and the</span> <span m=''1680590''>other one</span> <span m=''1680760''>backwards,</span>
  <span m=''1682130''>get</span> <span m=''1682290''>from</span> <span m=''1682460''>anywhere</span>
  <span m=''1682740''>to</span> <span m=''1682800''>anywhere.</span> </p><p><span
  m=''1683410''>So</span> <span m=''1683550''>here''s</span> <span m=''1683770''>all</span>
  <span m=''1683890''>you</span> <span m=''1684000''>do</span> <span m=''1684180''>you.</span>
  <span m=''1684320''>You take</span> <span m=''1684550''>the</span> <span m=''1684650''>first</span>
  <span m=''1684970''>edge</span> <span m=''1685670''>and</span> <span m=''1685810''>you</span>
  <span m=''1685900''>just</span> <span m=''1686170''>rotate</span> <span m=''1686620''>it</span>
  <span m=''1686730''>up</span> <span m=''1686940''>to</span> <span m=''1687050''>the</span>
  <span m=''1687200''>red</span> <span m=''1687400''>line</span> <span m=''1688590''>A.</span>
  <span m=''1690330''>And</span> <span m=''1690550''>then</span> <span m=''1691740''>you</span>
  <span m=''1691890''>take</span> <span m=''1692070''>the</span> <span m=''1692160''>next</span>
  <span m=''1692420''>edge</span> <span m=''1693200''>and</span> <span m=''1693350''>you</span>
  <span m=''1693440''>take</span> <span m=''1693660''>both</span> <span m=''1693930''>of</span>
  <span m=''1694000''>those</span> <span m=''1694190''>edges,</span> <span m=''1694500''>and</span>
  <span m=''1694590''>you</span> <span m=''1694690''>just</span> <span m=''1694890''>rotate</span>
  <span m=''1695470''>them</span> <span m=''1696180''>like</span> <span m=''1696350''>this,</span>
  <span m=''1696930''>so</span> <span m=''1697120''>you</span> <span m=''1697210''>get</span>
  <span m=''1697420''>that</span> <span m=''1697710''>little</span> <span m=''1698120''>2-step</span>
  <span m=''1699170''>staircase.</span> <span m=''1701130''>Now</span> <span m=''1701360''>I''d</span>
  <span m=''1701500''>really</span> <span m=''1701720''>like</span> <span m=''1701910''>to</span>
  <span m=''1702000''>pick</span> <span m=''1702200''>up</span> <span m=''1702310''>this</span>
  <span m=''1702540''>edge,</span> <span m=''1702950''>but</span> <span m=''1703130''>I</span>
  <span m=''1703320''>want</span> <span m=''1703560''>to</span> <span m=''1703650''>first</span>
  <span m=''1704100''>get</span> <span m=''1704320''>these</span> <span m=''1704570''>two</span>
  <span m=''1704750''>edges</span> <span m=''1705140''>in</span> <span m=''1705310''>a</span>
  <span m=''1705390''>plane</span> <span m=''1705800''>with</span> <span m=''1705920''>that</span>
  <span m=''1706120''>edge.</span> <span m=''1706940''>So</span> <span m=''1707000''>I</span>
  <span m=''1707080''>rotate</span> <span m=''1707620''>this</span> <span m=''1707910''>flag</span>
  <span m=''1708640''>over</span> <span m=''1708870''>to</span> <span m=''1708980''>the</span>
  <span m=''1709040''>left,</span> <span m=''1710010''>I</span> <span m=''1710140''>get</span>
  <span m=''1710660''>those</span> <span m=''1710970''>two</span> <span m=''1711110''>guys.</span>
  <span m=''1712740''>And</span> <span m=''1712890''>now</span> <span m=''1713090''>they''re</span>
  <span m=''1713240''>in</span> <span m=''1713310''>a</span> <span m=''1713370''>plane</span>
  <span m=''1713640''>with</span> <span m=''1713770''>this,</span> <span m=''1714060''>and</span>
  <span m=''1714180''>I</span> <span m=''1714270''>just</span> <span m=''1714510''>lift</span>
  <span m=''1714730''>that</span> <span m=''1714960''>up.</span> <span m=''1715750''>Then</span>
  <span m=''1715910''>I''m</span> <span m=''1715990''>going</span> <span m=''1716110''>to</span>
  <span m=''1716170''>flip,</span> <span m=''1716770''>then</span> <span m=''1717120''>rotate</span>
  <span m=''1717500''>up.</span> <span m=''1718200''>Flip,</span> <span m=''1718550''>rotate,</span>
  <span m=''1718890''>flip,</span> <span m=''1719140''>rotate.</span> </p><p><span
  m=''1720600''>Here''s</span> <span m=''1720910''>some</span> <span m=''1721090''>more</span>
  <span m=''1722320''>examples.</span> <span m=''1722810''>So</span> <span m=''1723180''>if</span>
  <span m=''1723330''>at</span> <span m=''1723430''>this</span> <span m=''1723610''>point,</span>
  <span m=''1724250''>I</span> <span m=''1724370''>have</span> <span m=''1724820''>this</span>
  <span m=''1725070''>staircase--</span> <span m=''1728030''>sorry,</span> <span m=''1728150''>I</span>
  <span m=''1728320''>guess</span> <span m=''1728680''>originally</span> <span m=''1729150''>I</span>
  <span m=''1729210''>have</span> <span m=''1729520''>from</span> <span m=''1729780''>V3</span>
  <span m=''1730550''>to</span> <span m=''1730770''>D</span> <span m=''1731050''>up</span>
  <span m=''1731330''>there.</span> <span m=''1732650''>it''s</span> <span m=''1732840''>not</span>
  <span m=''1733100''>in</span> <span m=''1733230''>plane</span> <span m=''1733530''>with</span>
  <span m=''1733660''>this</span> <span m=''1733860''>guy,</span> <span m=''1734570''>so</span>
  <span m=''1734710''>I</span> <span m=''1734780''>just</span> <span m=''1734970''>rotate</span>
  <span m=''1735680''>it</span> <span m=''1735940''>like</span> <span m=''1736090''>that.</span>
  <span m=''1736310''>I''m</span> <span m=''1736410''>spinning</span> <span m=''1736840''>around</span>
  <span m=''1737170''>this</span> <span m=''1737360''>edge.</span> <span m=''1738530''>So</span>
  <span m=''1738690''>now</span> <span m=''1738890''>I</span> <span m=''1738970''>have</span>
  <span m=''1739230''>from</span> <span m=''1739380''>B3 to</span> <span m=''1739770''>#,</span>
  <span m=''1741250''>and</span> <span m=''1741470''>then</span> <span m=''1741690''>I</span>
  <span m=''1741790''>rotate</span> <span m=''1742140''>it</span> <span m=''1742310''>up</span>
  <span m=''1742530''>along</span> <span m=''1742860''>that</span> <span m=''1743090''>green</span>
  <span m=''1743410''>arc.</span> <span m=''1744510''>And</span> <span m=''1744700''>I</span>
  <span m=''1744770''>get</span> <span m=''1744980''>a</span> <span m=''1745030''>bigger</span>
  <span m=''1745330''>staircase</span> <span m=''1746700''>above</span> <span m=''1747670''>the</span>
  <span m=''1747780''>chain and</span> <span m=''1748240''>because</span> <span m=''1748500''>everything''s</span>
  <span m=''1748840''>staying</span> <span m=''1749100''>above,</span> <span m=''1749410''>it</span>
  <span m=''1749720''>will</span> <span m=''1749830''>never</span> <span m=''1750140''>penetrate</span>
  <span m=''1750560''>the</span> <span m=''1750630''>plane</span> <span m=''1750950''>and
  will</span> <span m=''1751090''>never</span> <span m=''1751310''>hit</span> <span
  m=''1751430''>anybody</span> <span m=''1751870''>else.</span> <span m=''1752690''>And</span>
  <span m=''1752880''>I''m</span> <span m=''1752960''>building</span> <span m=''1753310''>a</span>
  <span m=''1753370''>staircase</span> <span m=''1754030''>by</span> <span m=''1754220''>design.</span>
  <span m=''1754740''>I always</span> <span m=''1755100''>rotate</span> <span m=''1755580''>this--</span>
  <span m=''1756240''>there''s</span> <span m=''1756290''>actually</span> <span m=''1756550''>two</span>
  <span m=''1756750''>ways</span> <span m=''1756980''>I</span> <span m=''1757050''>could</span>
  <span m=''1757190''>be</span> <span m=''1757310''>in plane--</span> <span m=''1757570''>but</span>
  <span m=''1757830''>I</span> <span m=''1758270''>always</span> <span m=''1758500''>rotate
  it</span> <span m=''1758950''>so</span> <span m=''1759050''>that</span> <span m=''1759190''>when</span>
  <span m=''1759320''>I</span> <span m=''1759380''>pick</span> <span m=''1759900''>an</span>
  <span m=''1760040''>edge</span> <span m=''1760220''>up,</span> <span m=''1760400''>it''ll</span>
  <span m=''1760610''>be</span> <span m=''1760940''>in a</span> <span m=''1761010''>staircase.</span>
  <span m=''1762280''>So</span> <span m=''1762420''>this</span> <span m=''1762560''>is</span>
  <span m=''1762640''>actually</span> <span m=''1762920''>really</span> <span m=''1763230''>easy.</span>
  </p><p><span m=''1763940''>And</span> <span m=''1764230''>slight</span> <span m=''1764570''>generalization</span>
  <span m=''1765310''>is</span> <span m=''1765520''>to</span> <span m=''1766470''>obtuse</span>
  <span m=''1766850''>chains,</span> <span m=''1767310''>then</span> <span m=''1768900''>instead</span>
  <span m=''1769270''>of</span> <span m=''1769420''>making</span> <span m=''1769730''>a</span>
  <span m=''1769780''>staircase,</span> <span m=''1770390''>we</span> <span m=''1770530''>make</span>
  <span m=''1770850''>a</span> <span m=''1772040''>monotone.</span> <span m=''1774336''>Let</span>
  <span m=''1774810''>me get this</span> <span m=''1774990''>right.</span> <span m=''1778580''>Yeah,</span>
  <span m=''1779000''>sum</span> <span m=''1779260''>z</span> <span m=''1779490''>monotone</span>
  <span m=''1780020''>state.</span> <span m=''1780440''>So</span> <span m=''1780550''>it</span>
  <span m=''1780630''>goes</span> <span m=''1780820''>monotone</span> <span m=''1781390''>and</span>
  <span m=''1781530''>z,</span> <span m=''1781990''>out</span> <span m=''1782190''>of</span>
  <span m=''1782290''>the</span> <span m=''1782370''>plane,</span> <span m=''1783310''>that''s</span>
  <span m=''1783550''>enough</span> <span m=''1783840''>to</span> <span m=''1784000''>avoid</span>
  <span m=''1784240''>collision,</span> <span m=''1785110''>and</span> <span m=''1785300''>you</span>
  <span m=''1785400''>get</span> <span m=''1785500''>a</span> <span m=''1785580''>canonical</span>
  <span m=''1786050''>configuration.</span> <span m=''1787100''>Also,</span> <span
  m=''1787610''>if</span> <span m=''1787710''>you</span> <span m=''1787810''>have</span>
  <span m=''1788210''>acute</span> <span m=''1788620''>angles</span> <span m=''1789450''>but</span>
  <span m=''1789640''>all</span> <span m=''1789840''>the</span> <span m=''1789960''>angles</span>
  <span m=''1790260''>are</span> <span m=''1790380''>equal,</span> <span m=''1791620''>then</span>
  <span m=''1791740''>there''s</span> <span m=''1791930''>a</span> <span m=''1791990''>natural</span>
  <span m=''1793390''>conical</span> <span m=''1793840''>state,</span> <span m=''1794240''>which</span>
  <span m=''1794430''>is</span> <span m=''1794480''>just</span> <span m=''1794660''>like</span>
  <span m=''1794810''>a</span> <span m=''1794890''>compressed</span> <span m=''1795290''>staircase.</span>
  <span m=''1796320''>And</span> <span m=''1796500''>that</span> <span m=''1796690''>will</span>
  <span m=''1796840''>work</span> <span m=''1797070''>here,</span> <span m=''1797310''>too.</span>
  <span m=''1797830''>That</span> <span m=''1798040''>takes</span> <span m=''1798260''>more</span>
  <span m=''1798600''>effort.</span> <span m=''1798940''>That</span> <span m=''1798970''>was</span>
  <span m=''1799140''>in</span> <span m=''1799240''>a</span> <span m=''1799290''>separate</span>
  <span m=''1799650''>paper.</span> <span m=''1803000''>But</span> <span m=''1803220''>big</span>
  <span m=''1803410''>open</span> <span m=''1803640''>question</span> <span m=''1804000''>is,</span>
  <span m=''1804850''>chains</span> <span m=''1805130''>with</span> <span m=''1805250''>arbitrary</span>
  <span m=''1805680''>angles.</span> <span m=''1806140''>We</span> <span m=''1806230''>have</span>
  <span m=''1806320''>no</span> <span m=''1806480''>idea.</span> <span m=''1807620''>It
  is</span> <span m=''1807810''>very</span> <span m=''1808010''>hard</span> <span
  m=''1808270''>to</span> <span m=''1808380''>do</span> <span m=''1809440''>an</span>
  <span m=''1809500''>operation</span> <span m=''1810390''>like</span> <span m=''1810570''>this.</span>
  <span m=''1811290''>Wow,</span> <span m=''1811620''>we</span> <span m=''1811720''>are</span>
  <span m=''1811800''>burning</span> <span m=''1812180''>through</span> <span m=''1812390''>this.</span>
  <span m=''1812550''>This is</span> <span m=''1812700''>fun.</span> </p><p><span
  m=''1815670''>So</span> <span m=''1817510''>the</span> <span m=''1817630''>next</span>
  <span m=''1817870''>topic</span> <span m=''1818220''>is</span> <span m=''1818430''>about</span>
  <span m=''1819160''>locked</span> <span m=''1820080''>chains.</span> <span m=''1822875''>Now</span>
  <span m=''1823300''>as</span> <span m=''1823550''>I</span> <span m=''1823590''>said,</span>
  <span m=''1823820''>you</span> <span m=''1823930''>can</span> <span m=''1824070''>take</span>
  <span m=''1824250''>a</span> <span m=''1824310''>knitting</span> <span m=''1824560''>needles</span>
  <span m=''1824860''>example,</span> <span m=''1827000''>which</span> <span m=''1827140''>has</span>
  <span m=''1827770''>five</span> <span m=''1828260''>edges.</span> <span m=''1834210''>And</span>
  <span m=''1834390''>that</span> <span m=''1834520''>will</span> <span m=''1834610''>still</span>
  <span m=''1834830''>be</span> <span m=''1834970''>locked</span> <span m=''1835360''>if</span>
  <span m=''1835370''>you</span> <span m=''1835510''>force the</span> <span m=''1835910''>angles</span>
  <span m=''1836210''>to</span> <span m=''1836310''>be</span> <span m=''1836450''>fixed</span>
  <span m=''1837070''>because</span> <span m=''1837300''>it</span> <span m=''1837380''>was</span>
  <span m=''1837560''>locked</span> <span m=''1837840''>without</span> <span m=''1838100''>the</span>
  <span m=''1838210''>angles</span> <span m=''1838510''>being</span> <span m=''1838700''>fixed.</span>
  <span m=''1839910''>Now,</span> <span m=''1840080''>it</span> <span m=''1840150''>required</span>
  <span m=''1840800''>a</span> <span m=''1840900''>length</span> <span m=''1841180''>ratio</span>
  <span m=''1842080''>of</span> <span m=''1842820''>3:1,</span> <span m=''1843780''>I</span>
  <span m=''1843830''>think.</span> <span m=''1844540''>This</span> <span m=''1844910''>edge</span>
  <span m=''1845110''>had</span> <span m=''1845260''>to</span> <span m=''1845320''>be</span>
  <span m=''1845440''>longer</span> <span m=''1845750''>than</span> <span m=''1845920''>the</span>
  <span m=''1845990''>sum</span> <span m=''1846290''>of</span> <span m=''1846390''>those</span>
  <span m=''1846650''>three.</span> </p><p><span m=''1850440''>So</span> <span m=''1851000''>let</span>
  <span m=''1851140''>me</span> <span m=''1851430''>put</span> <span m=''1851740''>down</span>
  <span m=''1852740''>some</span> <span m=''1852960''>open</span> <span m=''1853180''>problems.</span>
  <span m=''1855230''>So</span> <span m=''1855370''>you</span> <span m=''1855420''>may</span>
  <span m=''1855550''>recall</span> <span m=''1856030''>in</span> <span m=''1856250''>the</span>
  <span m=''1856370''>case</span> <span m=''1856950''>of</span> <span m=''1858150''>universal</span>
  <span m=''1858770''>chains--</span> <span m=''1860180''>universal</span> <span m=''1860630''>joints,</span>
  <span m=''1861240''>I</span> <span m=''1861300''>should</span> <span m=''1861480''>say--</span>
  <span m=''1870290''>the</span> <span m=''1870390''>big</span> <span m=''1870590''>open</span>
  <span m=''1870820''>question</span> <span m=''1872240''>was,</span> <span m=''1872660''>can</span>
  <span m=''1872920''>you</span> <span m=''1873090''>lock</span> <span m=''1874040''>a</span>
  <span m=''1874090''>universal</span> <span m=''1874640''>joint</span> <span m=''1874970''>3D</span>
  <span m=''1875330''>chain</span> <span m=''1876250''>with</span> <span m=''1876910''>unit</span>
  <span m=''1877380''>edge</span> <span m=''1877560''>lengths?</span> <span m=''1879860''>So,</span>
  <span m=''1880090''>equilateral--</span> <span m=''1881690''>every</span> <span
  m=''1881950''>edge</span> <span m=''1882100''>is</span> <span m=''1882180''>the</span>
  <span m=''1882260''>same</span> <span m=''1882510''>length.</span> <span m=''1884900''>Is</span>
  <span m=''1885140''>there</span> <span m=''1885280''>a</span> <span m=''1885320''>locked</span>
  <span m=''1885580''>chain</span> <span m=''1885880''>like</span> <span m=''1886090''>the</span>
  <span m=''1886170''>knitting</span> <span m=''1886430''>needles</span> <span m=''1887170''>when
  all</span> <span m=''1887430''>the edge</span> <span m=''1887700''>lengths are</span>
  <span m=''1887930''>the</span> <span m=''1888080''>same.</span> <span m=''1888380''>And</span>
  <span m=''1888500''>one</span> <span m=''1888680''>of</span> <span m=''1888730''>the</span>
  <span m=''1888800''>motivations</span> <span m=''1889390''>for</span> <span m=''1889490''>that</span>
  <span m=''1889780''>is</span> <span m=''1889980''>in</span> <span m=''1890100''>proteins,</span>
  <span m=''1891420''>the</span> <span m=''1891550''>edge</span> <span m=''1891720''>lengths</span>
  <span m=''1891990''>are</span> <span m=''1892090''>all</span> <span m=''1892310''>within</span>
  <span m=''1892730''>like</span> <span m=''1892940''>50%</span> <span m=''1893820''>of</span>
  <span m=''1893900''>each</span> <span m=''1894060''>other.</span> <span m=''1895390''>So</span>
  <span m=''1896490''>it''s</span> <span m=''1896620''>pretty</span> <span m=''1896830''>natural,</span>
  <span m=''1897260''>of</span> <span m=''1897420''>course.</span> <span m=''1898900''>We</span>
  <span m=''1899150''>don''t</span> <span m=''1899320''>have</span> <span m=''1901820''>universal</span>
  <span m=''1903040''>joints</span> <span m=''1903610''>with</span> <span m=''1903780''>proteins.</span>
  <span m=''1904430''>We</span> <span m=''1904480''>have</span> <span m=''1904670''>fixed</span>
  <span m=''1904920''>angle</span> <span m=''1905160''>joints.</span> </p><p><span
  m=''1908560''>So</span> <span m=''1908810''>the</span> <span m=''1908900''>big open</span>
  <span m=''1909350''>problem</span> <span m=''1909630''>for</span> <span m=''1909810''>fixed</span>
  <span m=''1910120''>angle</span> <span m=''1910350''>joints--</span> <span m=''1912670''>I
  guess</span> <span m=''1912810''>we''ll</span> <span m=''1912910''>do</span> <span
  m=''1913020''>this</span> <span m=''1913240''>in</span> <span m=''1913350''>parts--</span>
  <span m=''1915730''>is</span> <span m=''1916010''>there</span> <span m=''1920110''>a</span>
  <span m=''1920300''>locked</span> <span m=''1923310''>3D</span> <span m=''1925180''>fixed</span>
  <span m=''1925660''>angle</span> <span m=''1925960''>chain</span> <span m=''1943030''>that''s</span>
  <span m=''1943560''>equilateral?</span> <span m=''1944600''>I''m</span> <span m=''1944950''>going</span>
  <span m=''1945050''>to</span> <span m=''1945100''>add</span> <span m=''1945310''>some</span>
  <span m=''1945510''>conditions</span> <span m=''1945960''>here.</span> <span m=''1950910''>So</span>
  <span m=''1951200''>that''s the</span> <span m=''1951540''>first</span> <span m=''1951820''>natural</span>
  <span m=''1952100''>question.</span> <span m=''1952560''>Knitting</span> <span m=''1952840''>needles</span>
  <span m=''1954010''>doesn''t</span> <span m=''1954300''>suffice.</span> <span m=''1954780''>We</span>
  <span m=''1954880''>need</span> <span m=''1955010''>a</span> <span m=''1955090''>3:1</span>
  <span m=''1955620''>length</span> <span m=''1955870''>ratio,</span> <span m=''1956120''>as</span>
  <span m=''1956230''>far</span> <span m=''1956390''>as</span> <span m=''1956490''>we</span>
  <span m=''1956610''>know.</span> <span m=''1963100''>Turns</span> <span m=''1963310''>out</span>
  <span m=''1963400''>that</span> <span m=''1963540''>question''s</span> <span m=''1963890''>not</span>
  <span m=''1964050''>very</span> <span m=''1964180''>interesting.</span> <span m=''1965180''>I
  need</span> <span m=''1965600''>to do</span> <span m=''1966010''>slightly</span>
  <span m=''1966460''>nonlinear</span> <span m=''1967540''>editing</span> <span m=''1967900''>here.</span>
  </p><p><span m=''1968600''>So</span> <span m=''1968700''>you</span> <span m=''1968780''>take
  your</span> <span m=''1969110''>knitting</span> <span m=''1969280''>needles</span>
  <span m=''1969590''>example,</span> <span m=''1970990''>and</span> <span m=''1971090''>you</span>
  <span m=''1971120''>just</span> <span m=''1971210''>subdivide</span> <span m=''1971750''>the</span>
  <span m=''1971880''>edges</span> <span m=''1972180''>into</span> <span m=''1972420''>lots</span>
  <span m=''1972740''>of</span> <span m=''1973020''>little</span> <span m=''1973270''>tiny</span>
  <span m=''1973580''>bars.</span> <span m=''1973920''>It</span> <span m=''1974070''>doesn''t</span>
  <span m=''1974320''>have</span> <span m=''1974420''>to</span> <span m=''1974500''>be</span>
  <span m=''1974610''>this</span> <span m=''1974830''>extreme.</span> <span m=''1975500''>You</span>
  <span m=''1975770''>could</span> <span m=''1976020''>not</span> <span m=''1976310''>subdivide</span>
  <span m=''1976760''>these</span> <span m=''1976940''>edges</span> <span m=''1977270''>at
  all,</span> <span m=''1977660''>and</span> <span m=''1978050''>make</span> <span
  m=''1978300''>these</span> <span m=''1978530''>guys</span> <span m=''1978810''>subdivide</span>
  <span m=''1979230''>them</span> <span m=''1979350''>into</span> <span m=''1979530''>like</span>
  <span m=''1979700''>three</span> <span m=''1979880''>or</span> <span m=''1979940''>four</span>
  <span m=''1980180''>parts.</span> <span m=''1981350''>Because</span> <span m=''1981560''>the</span>
  <span m=''1981690''>angles</span> <span m=''1982020''>are</span> <span m=''1982090''>fixed,</span>
  <span m=''1982900''>these</span> <span m=''1983380''>guys</span> <span m=''1984310''>act</span>
  <span m=''1984750''>as</span> <span m=''1985080''>a</span> <span m=''1985140''>single</span>
  <span m=''1985670''>[INAUDIBLE].</span> <span m=''1986360''>There''s</span> <span
  m=''1986640''>really</span> <span m=''1986880''>no</span> <span m=''1987140''>difference.</span>
  <span m=''1988010''>Maybe</span> <span m=''1988330''>you</span> <span m=''1988450''>make
  a</span> <span m=''1988790''>slight</span> <span m=''1989340''>curve</span> <span
  m=''1989700''>there</span> <span m=''1989920''>and</span> <span m=''1990010''>then</span>
  <span m=''1990100''>they</span> <span m=''1990200''>can</span> <span m=''1991000''>bend</span>
  <span m=''1991350''>a</span> <span m=''1991410''>little</span> <span m=''1991650''>bit,</span>
  <span m=''1992190''>but</span> <span m=''1992340''>really</span> <span m=''1992600''>not</span>
  <span m=''1992800''>much.</span> <span m=''1994100''>So</span> <span m=''1994440''>if</span>
  <span m=''1994600''>you</span> <span m=''1994700''>just</span> <span m=''1995070''>say,</span>
  <span m=''1995460''>oh,</span> <span m=''1995650''>I</span> <span m=''1995730''>want</span>
  <span m=''1995990''>it to</span> <span m=''1996070''>be</span> <span m=''1996480''>unit</span>
  <span m=''1996740''>length.</span> <span m=''1997070''>I</span> <span m=''1997140''>don''t</span>
  <span m=''1997340''>constrain</span> <span m=''1997710''>what</span> <span m=''1997840''>the</span>
  <span m=''1997980''>angles</span> <span m=''1998350''>are</span> <span m=''1998960''>but
  I</span> <span m=''1999150''>fix</span> <span m=''1999440''>them,</span> <span m=''2000720''>then</span>
  <span m=''2001480''>it''s</span> <span m=''2001650''>trivial</span> <span m=''2002070''>to
  come up with</span> <span m=''2002440''>locked</span> <span m=''2002700''>examples.</span>
  <span m=''2003570''>So</span> <span m=''2003840''>that''s</span> <span m=''2004050''>not</span>
  <span m=''2004190''>very</span> <span m=''2004360''>interesting.</span> </p><p><span
  m=''2007000''>What</span> <span m=''2007210''>if</span> <span m=''2007370''>I</span>
  <span m=''2007440''>make</span> <span m=''2007800''>it</span> <span m=''2008020''>not</span>
  <span m=''2008230''>only</span> <span m=''2008490''>equilateral--</span> <span m=''2009380''>the</span>
  <span m=''2009450''>lengths</span> <span m=''2009770''>are</span> <span m=''2009820''>the</span>
  <span m=''2009950''>same--</span> <span m=''2010650''>if</span> <span m=''2010890''>I</span>
  <span m=''2010960''>make</span> <span m=''2011200''>it</span> <span m=''2011310''>equiangular.</span>
  <span m=''2017850''>Because,</span> <span m=''2018200''>again,</span> <span m=''2018500''>in</span>
  <span m=''2018620''>proteins,</span> <span m=''2019290''>all</span> <span m=''2019510''>the</span>
  <span m=''2019630''>angles</span> <span m=''2020210''>are</span> <span m=''2021170''>similar.</span>
  <span m=''2021750''>They''re</span> <span m=''2021960''>around</span> <span m=''2022490''>110,</span>
  <span m=''2023610''>108,</span> <span m=''2024400''>something</span> <span m=''2024730''>like</span>
  <span m=''2024910''>that.</span> <span m=''2025150''>They''re</span> <span m=''2025600''>all</span>
  <span m=''2025690''>pretty</span> <span m=''2025920''>close,</span> <span m=''2027120''>I</span>
  <span m=''2027280''>think</span> <span m=''2027500''>within</span> <span m=''2027810''>10
  to</span> <span m=''2028200''>20%</span> <span m=''2028750''>of</span> <span m=''2028830''>each</span>
  <span m=''2028990''>other.</span> <span m=''2030450''>Well,</span> <span m=''2030550''>there''s</span>
  <span m=''2031080''>also a</span> <span m=''2031460''>locked</span> <span m=''2031710''>example.</span>
  <span m=''2032580''>And</span> <span m=''2032820''>just</span> <span m=''2033000''>to</span>
  <span m=''2033080''>show</span> <span m=''2033280''>you</span> <span m=''2033520''>how</span>
  <span m=''2034780''>research</span> <span m=''2035250''>was</span> <span m=''2035430''>done</span>
  <span m=''2035760''>back</span> <span m=''2036120''>at</span> <span m=''2036210''>the</span>
  <span m=''2036320''>turn</span> <span m=''2036580''>of</span> <span m=''2036660''>the</span>
  <span m=''2036750''>century,</span> <span m=''2037740''>this is</span> <span m=''2037980''>pre-web</span>
  <span m=''2038325''>2.0,</span> <span m=''2039850''>pre-Ajax</span> <span m=''2040790''>and</span>
  <span m=''2040890''>all</span> <span m=''2041080''>that</span> <span m=''2041310''>fancy</span>
  <span m=''2041700''>stuff.</span> <span m=''2042380''>We</span> <span m=''2042550''>used</span>
  <span m=''2042930''>Ascii</span> <span m=''2043450''>Art.</span> <span m=''2044800''>Email</span>
  <span m=''2045330''>was</span> <span m=''2045520''>the</span> <span m=''2045680''>tool</span>
  <span m=''2045970''>of</span> <span m=''2046090''>choice.</span> <span m=''2047050''>I</span>
  <span m=''2047080''>know</span> <span m=''2047260''>it''s</span> <span m=''2047370''>hard</span>
  <span m=''2047570''>to</span> <span m=''2047610''>imagine</span> <span m=''2048010''>a</span>
  <span m=''2048090''>time--</span> <span m=''2049130''>2002,</span> <span m=''2050190''>so</span>
  <span m=''2050489''>long</span> <span m=''2050739''>ago.</span> <span m=''2052780''>And</span>
  <span m=''2053280''>I</span> <span m=''2053380''>tracked</span> <span m=''2053659''>this</span>
  <span m=''2053840''>down.</span> <span m=''2054110''>This</span> <span m=''2054250''>is</span>
  <span m=''2054389''>the</span> <span m=''2054540''>original</span> <span m=''2055739''>claim</span>
  <span m=''2056150''>it</span> <span m=''2056389''>looks--</span> <span m=''2056889''>we</span>
  <span m=''2056980''>call</span> <span m=''2057170''>this</span> <span m=''2057330''>the</span>
  <span m=''2057440''>crossed</span> <span m=''2057889''>legs</span> <span m=''2058139''>example</span>
  <span m=''2058630''>because</span> <span m=''2058870''>it''s</span> <span m=''2059300''>like</span>
  <span m=''2059520''>two</span> <span m=''2059699''>legs</span> <span m=''2059940''>crossed</span>
  <span m=''2060230''>around</span> <span m=''2060400''>each</span> <span m=''2060550''>other.</span>
  <span m=''2061300''>And</span> <span m=''2062570''>this</span> <span m=''2062790''>is</span>
  <span m=''2062949''>the</span> <span m=''2063469''>first</span> <span m=''2063719''>time</span>
  <span m=''2063909''>we</span> <span m=''2064020''>thought,</span> <span m=''2064230''>oh,</span>
  <span m=''2064400''>maybe</span> <span m=''2064679''>it</span> <span m=''2064760''>could</span>
  <span m=''2064870''>be</span> <span m=''2065000''>done,</span> <span m=''2065800''>unit</span>
  <span m=''2065900''>length.</span> <span m=''2066210''>This</span> <span m=''2066360''>is</span>
  <span m=''2066440''>Stefan</span> <span m=''2066739''>Langerman.</span> </p><p><span
  m=''2069300''>And</span> <span m=''2069920''>here,</span> <span m=''2070239''>for</span>
  <span m=''2070380''>the</span> <span m=''2070489''>first</span> <span m=''2070840''>time</span>
  <span m=''2071179''>ever--</span> <span m=''2072400''>this</span> <span m=''2072989''>is</span>
  <span m=''2073130''>not</span> <span m=''2073300''>the</span> <span m=''2073380''>first</span>
  <span m=''2073639''>model,</span> <span m=''2074100''>but</span> <span m=''2074199''>this</span>
  <span m=''2074250''>is</span> <span m=''2074360''>the</span> <span m=''2074449''>first</span>
  <span m=''2074719''>photograph</span> <span m=''2075270''>of</span> <span m=''2075389''>any</span>
  <span m=''2075530''>model</span> <span m=''2075840''>I''m</span> <span m=''2075969''>aware</span>
  <span m=''2076230''>of--</span> <span m=''2076790''>this</span> <span m=''2076969''>is</span>
  <span m=''2077100''>the</span> <span m=''2077219''>crossed</span> <span m=''2077540''>legs</span>
  <span m=''2077750''>example.</span> <span m=''2079420''>This</span> <span m=''2079679''>is</span>
  <span m=''2079780''>made</span> <span m=''2080080''>with</span> <span m=''2080320''>a</span>
  <span m=''2080810''>construction</span> <span m=''2081300''>toy</span> <span m=''2081469''>that</span>
  <span m=''2081590''>used</span> <span m=''2081830''>to</span> <span m=''2081900''>be</span>
  <span m=''2082030''>sold</span> <span m=''2082320''>around</span> <span m=''2082540''>here</span>
  <span m=''2082719''>but</span> <span m=''2082860''>is</span> <span m=''2082969''>no</span>
  <span m=''2083139''>longer in</span> <span m=''2083469''>production.</span> <span
  m=''2084860''>So</span> <span m=''2085050''>they''re</span> <span m=''2085170''>pretty</span>
  <span m=''2085380''>hard</span> <span m=''2085580''>to</span> <span m=''2085639''>get.</span>
  <span m=''2086290''>It''s</span> <span m=''2086560''>straws--</span> <span m=''2088030''>nicely</span>
  <span m=''2088320''>colored</span> <span m=''2088600''>straws--</span> <span m=''2089250''>and</span>
  <span m=''2089440''>the</span> <span m=''2089550''>cool</span> <span m=''2089810''>part</span>
  <span m=''2090090''>are</span> <span m=''2090210''>these</span> <span m=''2091489''>connectors.</span>
  </p><p><span m=''2092830''>So</span> <span m=''2092980''>the</span> <span m=''2093080''>connectors</span>
  <span m=''2093860''>force</span> <span m=''2094380''>particular</span> <span m=''2094860''>angles.</span>
  <span m=''2095239''>In</span> <span m=''2095300''>this</span> <span m=''2095480''>case,</span>
  <span m=''2095780''>every</span> <span m=''2096080''>angle</span> <span m=''2096310''>is</span>
  <span m=''2096409''>45</span> <span m=''2096840''>degrees.</span> <span m=''2097800''>So</span>
  <span m=''2097830''>this</span> <span m=''2098020''>is</span> <span m=''2098110''>equiangular</span>
  <span m=''2099290''>and</span> <span m=''2099820''>equilateral</span> <span m=''2100260''>because</span>
  <span m=''2100450''>all</span> <span m=''2100590''>the</span> <span m=''2100670''>straws,</span>
  <span m=''2101340''>I''m</span> <span m=''2101540''>told,</span> <span m=''2101810''>are</span>
  <span m=''2101870''>the</span> <span m=''2101990''>same</span> <span m=''2102210''>length.</span>
  <span m=''2102560''>That''s</span> <span m=''2103115''>how they''re</span> <span
  m=''2103440''>sold.</span> <span m=''2104410''>And</span> <span m=''2104680''>you</span>
  <span m=''2104820''>can</span> <span m=''2104960''>do</span> <span m=''2105140''>edge</span>
  <span m=''2105310''>spins.</span> <span m=''2107850''>Whoops,</span> <span m=''2109410''>that''s</span>
  <span m=''2109550''>called</span> <span m=''2109760''>cheating.</span> <span m=''2111640''>It''s</span>
  <span m=''2111840''>not</span> <span m=''2112020''>totally</span> <span m=''2112400''>obvious</span>
  <span m=''2112760''>that</span> <span m=''2112860''>this</span> <span m=''2113020''>is</span>
  <span m=''2113140''>locked.</span> <span m=''2115400''>The</span> <span m=''2115610''>problem</span>
  <span m=''2115930''>with</span> <span m=''2116060''>the</span> <span m=''2116130''>model</span>
  <span m=''2116590''>is</span> <span m=''2116680''>that the</span> <span m=''2116840''>edges</span>
  <span m=''2117180''>can</span> <span m=''2117480''>bend.</span> <span m=''2118680''>But</span>
  <span m=''2118880''>if</span> <span m=''2119090''>you</span> <span m=''2119540''>treat</span>
  <span m=''2119800''>it</span> <span m=''2119970''>properly</span> <span m=''2121400''>and</span>
  <span m=''2121820''>only</span> <span m=''2122310''>spin</span> <span m=''2122810''>around</span>
  <span m=''2123450''>the</span> <span m=''2124090''>edges,</span> <span m=''2126060''>then</span>
  <span m=''2127100''>you''re</span> <span m=''2127640''>stuck.</span> </p><p><span
  m=''2128840''>Now,</span> <span m=''2130130''>there</span> <span m=''2130310''>is</span>
  <span m=''2130410''>one</span> <span m=''2130600''>thing</span> <span m=''2130750''>you</span>
  <span m=''2130890''>can</span> <span m=''2131020''>do.</span> <span m=''2132260''>See</span>
  <span m=''2132525''>if</span> <span m=''2132790''>I--</span> <span m=''2137340''>yeah,</span>
  <span m=''2137800''>like</span> <span m=''2137960''>this.</span> <span m=''2139600''>So</span>
  <span m=''2139750''>here,</span> <span m=''2139940''>I''m</span> <span m=''2140030''>almost</span>
  <span m=''2140400''>in</span> <span m=''2140490''>a</span> <span m=''2140540''>plane.</span>
  <span m=''2141140''>I''ve</span> <span m=''2141280''>got</span> <span m=''2141430''>the</span>
  <span m=''2141520''>purple</span> <span m=''2141820''>edge</span> <span m=''2142130''>right</span>
  <span m=''2142420''>against</span> <span m=''2142920''>the</span> <span m=''2144050''>pink</span>
  <span m=''2144270''>one.</span> <span m=''2145450''>Easier to</span> <span m=''2145680''>see
  from that</span> <span m=''2145850''>angle?</span> <span m=''2146070''>I</span>
  <span m=''2146503''>don''t know.</span> <span m=''2147370''>So</span> <span m=''2147630''>here,</span>
  <span m=''2148160''>this</span> <span m=''2148410''>guy</span> <span m=''2148600''>can</span>
  <span m=''2148790''>come</span> <span m=''2149050''>out</span> <span m=''2150290''>and</span>
  <span m=''2150820''>this</span> <span m=''2151040''>guy</span> <span m=''2151230''>can</span>
  <span m=''2152690''>barely</span> <span m=''2153110''>go</span> <span m=''2154030''>on</span>
  <span m=''2154290''>the</span> <span m=''2154410''>edge.</span> <span m=''2154630''>So</span>
  <span m=''2154780''>actually,</span> <span m=''2155020''>this</span> <span m=''2155170''>doesn''t</span>
  <span m=''2155410''>quite</span> <span m=''2155580''>work</span> <span m=''2155750''>for</span>
  <span m=''2155860''>equilateral.</span> <span m=''2156370''>It</span> <span m=''2156430''>works</span>
  <span m=''2156680''>for</span> <span m=''2156820''>one</span> <span m=''2157000''>plus</span>
  <span m=''2157210''>epsilon.</span> <span m=''2157720''>That''s</span> <span m=''2157940''>why</span>
  <span m=''2158070''>I</span> <span m=''2158120''>added</span> <span m=''2158420''>these</span>
  <span m=''2158610''>little</span> <span m=''2159310''>nubs</span> <span m=''2159720''>at</span>
  <span m=''2159800''>the</span> <span m=''2159890''>end.</span> <span m=''2161420''>So</span>
  <span m=''2161610''>if</span> <span m=''2162460''>they''re</span> <span m=''2162750''>all</span>
  <span m=''2162900''>exactly</span> <span m=''2163530''>equal</span> <span m=''2163830''>length</span>
  <span m=''2164090''>and</span> <span m=''2164200''>you</span> <span m=''2164340''>allow</span>
  <span m=''2165170''>just</span> <span m=''2166020''>abrasion</span> <span m=''2166730''>of</span>
  <span m=''2166870''>the</span> <span m=''2167000''>endpoint,</span> <span m=''2167930''>then</span>
  <span m=''2168140''>this</span> <span m=''2168310''>could</span> <span m=''2168460''>go</span>
  <span m=''2168600''>around</span> <span m=''2169140''>like</span> <span m=''2169300''>that</span>
  <span m=''2169550''>and</span> <span m=''2169680''>then</span> <span m=''2169790''>you''d</span>
  <span m=''2169920''>be</span> <span m=''2170280''>unlocked.</span> </p><p><span
  m=''2171950''>But</span> <span m=''2172080''>if</span> <span m=''2172180''>you</span>
  <span m=''2172270''>just</span> <span m=''2172490''>add</span> <span m=''2172790''>slightly--</span>
  <span m=''2173880''>either</span> <span m=''2174090''>you</span> <span m=''2174220''>change</span>
  <span m=''2174480''>the</span> <span m=''2174590''>angles</span> <span m=''2174860''>to</span>
  <span m=''2174950''>be</span> <span m=''2175200''>not</span> <span m=''2175440''>quite</span>
  <span m=''2175700''>equal,</span> <span m=''2176310''>so</span> <span m=''2177050''>make</span>
  <span m=''2177230''>this</span> <span m=''2177380''>a</span> <span m=''2177420''>little</span>
  <span m=''2177560''>smaller,</span> <span m=''2177990''>or</span> <span m=''2178170''>you</span>
  <span m=''2178260''>make</span> <span m=''2178410''>the</span> <span m=''2178500''>lengths</span>
  <span m=''2178770''>a</span> <span m=''2178810''>little</span> <span m=''2179060''>bit</span>
  <span m=''2179220''>longer</span> <span m=''2179590''>at</span> <span m=''2179680''>the</span>
  <span m=''2179820''>ends--</span> <span m=''2180720''>then</span> <span m=''2181270''>the</span>
  <span m=''2181370''>claim</span> <span m=''2181630''>is</span> <span m=''2181730''>it''s</span>
  <span m=''2181880''>locked.</span> <span m=''2182200''>We</span> <span m=''2182270''>don''t</span>
  <span m=''2182400''>actually</span> <span m=''2182620''>have</span> <span m=''2182700''>a</span>
  <span m=''2182750''>formal</span> <span m=''2183050''>proof</span> <span m=''2183290''>of</span>
  <span m=''2183390''>this.</span> <span m=''2184040''>We''re</span> <span m=''2184160''>just</span>
  <span m=''2184360''>remembering,</span> <span m=''2184790''>hey,</span> <span m=''2185010''>we</span>
  <span m=''2185140''>should</span> <span m=''2185330''>probably</span> <span m=''2186280''>write</span>
  <span m=''2186450''>this</span> <span m=''2186610''>up.</span> <span m=''2186750''>I
  was</span> <span m=''2186920''>talking</span> <span m=''2187150''>to</span> <span
  m=''2187190''>Stefan</span> <span m=''2187590''>last</span> <span m=''2187830''>night.</span>
  <span m=''2192060''>So</span> <span m=''2192190''>someday</span> <span m=''2192540''>we''ll</span>
  <span m=''2192780''>prove</span> <span m=''2193020''>that this</span> <span m=''2193290''>is</span>
  <span m=''2193410''>locked.</span> <span m=''2194260''>But it</span> <span m=''2194440''>certainly</span>
  <span m=''2194760''>looks</span> <span m=''2195010''>like</span> <span m=''2195230''>it.</span>
  <span m=''2195760''>So</span> <span m=''2196590''>this</span> <span m=''2196740''>isn''t</span>
  <span m=''2196970''>open</span> <span m=''2197300''>yet.</span> <span m=''2198540''>I</span>
  <span m=''2198620''>mean,</span> <span m=''2199100''>modulo</span> <span m=''2199620''>the</span>
  <span m=''2199740''>details</span> <span m=''2200140''>of</span> <span m=''2200210''>that</span>
  <span m=''2200410''>proof.</span> <span m=''2201180''>Equilateral</span> <span m=''2201760''>and</span>
  <span m=''2201970''>equiangular</span> <span m=''2202830''>seems</span> <span m=''2203700''>easy</span>
  <span m=''2204090''>to</span> <span m=''2204260''>lock</span> <span m=''2204550''>with</span>
  <span m=''2204730''>fixed</span> <span m=''2205010''>angle</span> <span m=''2205250''>chains.</span>
  <span m=''2206370''>In</span> <span m=''2206420''>fact,</span> <span m=''2206650''>even</span>
  <span m=''2206860''>easier,</span> <span m=''2207550''>this</span> <span m=''2207960''>example</span>
  <span m=''2208530''>only</span> <span m=''2208810''>has</span> <span m=''2209820''>four</span>
  <span m=''2210170''>edges.</span> <span m=''2211270''>So</span> <span m=''2211500''>even</span>
  <span m=''2211740''>less</span> <span m=''2212070''>than</span> <span m=''2212270''>the</span>
  <span m=''2212380''>knitting</span> <span m=''2212630''>needles.</span> </p><p><span
  m=''2214060''>Fixed</span> <span m=''2214330''>angles</span> <span m=''2216920''>make</span>
  <span m=''2217480''>for</span> <span m=''2219410''>complicated</span> <span m=''2220020''>motions,</span>
  <span m=''2220430''>I</span> <span m=''2220490''>guess.</span> <span m=''2221410''>Make</span>
  <span m=''2221560''>it</span> <span m=''2221630''>hard</span> <span m=''2221880''>to</span>
  <span m=''2221970''>unlock</span> <span m=''2222390''>things.</span> <span m=''2223250''>So
  I</span> <span m=''2223530''>need to add</span> <span m=''2223770''>one</span> <span
  m=''2223970''>more</span> <span m=''2224140''>constraint,</span> <span m=''2225140''>and</span>
  <span m=''2225340''>the</span> <span m=''2225430''>constraint</span> <span m=''2225870''>is</span>
  <span m=''2226120''>obtuse.</span> <span m=''2228780''>So</span> <span m=''2228910''>again,</span>
  <span m=''2229340''>all</span> <span m=''2229650''>of</span> <span m=''2229740''>these</span>
  <span m=''2229910''>properties</span> <span m=''2231650''>are</span> <span m=''2231960''>enjoyed</span>
  <span m=''2232700''>by</span> <span m=''2233070''>proteins.</span> <span m=''2235170''>Protein</span>
  <span m=''2235660''>backbones</span> <span m=''2236660''>have</span> <span m=''2236850''>all</span>
  <span m=''2236980''>these</span> <span m=''2237130''>properties.</span> <span m=''2237520''>Even</span>
  <span m=''2237770''>if</span> <span m=''2237860''>you</span> <span m=''2237980''>looked</span>
  <span m=''2238190''>at</span> <span m=''2238290''>fixed</span> <span m=''2238520''>angle</span>
  <span m=''2238770''>trees,</span> <span m=''2240430''>is</span> <span m=''2240710''>there</span>
  <span m=''2240940''>something</span> <span m=''2241270''>like</span> <span m=''2241460''>this</span>
  <span m=''2241790''>that''s</span> <span m=''2242000''>locked?</span> <span m=''2242610''>And</span>
  <span m=''2242860''>now,</span> <span m=''2243300''>we</span> <span m=''2243470''>don''t</span>
  <span m=''2243580''>know.</span> <span m=''2245070''>And</span> <span m=''2245210''>this</span>
  <span m=''2245280''>seems</span> <span m=''2245570''>quite</span> <span m=''2245780''>tricky.</span>
  <span m=''2246790''>I</span> <span m=''2246840''>guess</span> <span m=''2247110''>the</span>
  <span m=''2247210''>intuition</span> <span m=''2247660''>is</span> <span m=''2247810''>that</span>
  <span m=''2247910''>obtuse--</span> <span m=''2248760''>and</span> <span m=''2249020''>usually</span>
  <span m=''2249350''>we</span> <span m=''2249450''>think</span> <span m=''2249620''>about</span>
  <span m=''2249820''>orthogonal,</span> <span m=''2250390''>just</span> <span m=''2250560''>cause
  it''s</span> <span m=''2250800''>easier to</span> <span m=''2251170''>draw</span>
  <span m=''2251330''>the</span> <span m=''2251430''>pictures,</span> <span m=''2251860''>but</span>
  <span m=''2252040''>reality</span> <span m=''2252480''>is</span> <span m=''2252580''>more</span>
  <span m=''2252750''>like</span> <span m=''2252970''>108</span> <span m=''2253420''>degrees--</span>
  <span m=''2255500''>the</span> <span m=''2255610''>conjecture</span> <span m=''2255870''>is</span>
  <span m=''2257010''>obtuse</span> <span m=''2257440''>fixed</span> <span m=''2257720''>angle</span>
  <span m=''2257990''>chains</span> <span m=''2258370''>behave</span> <span m=''2258790''>kind</span>
  <span m=''2259050''>of</span> <span m=''2259310''>like</span> <span m=''2259790''>universal</span>
  <span m=''2260250''>joints.</span> <span m=''2261240''>And</span> <span m=''2261440''>with</span>
  <span m=''2261560''>universal</span> <span m=''2261990''>joints,</span> <span m=''2262240''>we</span>
  <span m=''2262370''>don''t</span> <span m=''2262520''>know</span> <span m=''2262750''>whether</span>
  <span m=''2263790''>equilateral</span> <span m=''2264175''>is</span> <span m=''2264440''>enough.</span>
  <span m=''2265370''>So</span> <span m=''2267580''>it''s</span> <span m=''2267730''>tricky.</span>
  <span m=''2269026''>Yeah,</span> <span m=''2269460''>question.</span> </p><p><span
  m=''2271230''>AUDIENCE: In the previous</span> <span m=''2271700''>example,</span>
  <span m=''2272640''>you showed</span> <span m=''2273110''>the</span> <span m=''2274990''>ribbon</span>
  <span m=''2276400''>thing--</span> </p><p><span m=''2277820''>PROFESSOR: The</span>
  <span m=''2277920''>subdivided.</span> </p><p><span m=''2278780''>AUDIENCE: Subdivided</span>
  <span m=''2279254''>into a</span> <span m=''2279728''>bunch of</span> <span m=''2280202''>little</span>
  <span m=''2280676''>interconnecting</span> <span m=''2281150''>pieces.</span> <span
  m=''2282098''>What if</span> <span m=''2282572''>you, instead,</span> <span m=''2285610''>made</span>
  <span m=''2285900''>your</span> <span m=''2286190''>ribbon</span> <span m=''2286490''>lengths</span>
  <span m=''2287000''>basically</span> <span m=''2289100''>a bunch of</span> <span
  m=''2289330''>little</span> <span m=''2289910''>unit</span> <span m=''2291505''>obtuse</span>
  <span m=''2291970''>angle</span> <span m=''2292900''>connectors,</span> <span m=''2293365''>and</span>
  <span m=''2293830''>then</span> <span m=''2294295''>when</span> <span m=''2294760''>you</span>
  <span m=''2295230''>hit the</span> <span m=''2295350''>big</span> <span m=''2295690''>terms</span>
  <span m=''2296100''>it''s</span> <span m=''2296280''>just</span> <span m=''2296850''>obtuse,</span>
  <span m=''2297272''>obtuse,</span> <span m=''2297694''>obtuse,</span> <span m=''2298116''>obtuse.</span>
  </p><p><span m=''2298540''>PROFESSOR: Yeah,</span> <span m=''2298770''>you</span>
  <span m=''2299450''>can</span> <span m=''2299800''>make</span> <span m=''2300010''>this</span>
  <span m=''2300170''>example</span> <span m=''2300630''>be</span> <span m=''2300770''>entirely</span>
  <span m=''2301280''>obtuse.</span> <span m=''2301630''>You can</span> <span m=''2301980''>make</span>
  <span m=''2302190''>every</span> <span m=''2302430''>angle</span> <span m=''2302660''>obtuse.</span>
  <span m=''2303040''>Here,</span> <span m=''2303300''>you</span> <span m=''2303430''>could</span>
  <span m=''2303540''>arc a</span> <span m=''2303710''>little</span> <span m=''2303980''>bit.</span>
  <span m=''2304750''>Here,</span> <span m=''2305030''>you</span> <span m=''2305130''>could</span>
  <span m=''2305260''>arc</span> <span m=''2305440''>some</span> <span m=''2305570''>more,</span>
  <span m=''2305800''>but</span> <span m=''2305920''>not</span> <span m=''2306180''>too</span>
  <span m=''2306380''>sharp.</span> <span m=''2307550''>And</span> <span m=''2307970''>because</span>
  <span m=''2308210''>here,</span> <span m=''2308570''>we</span> <span m=''2308760''>actually</span>
  <span m=''2309020''>know</span> <span m=''2309200''>that this</span> <span m=''2309590''>part</span>
  <span m=''2309930''>can</span> <span m=''2310090''>be</span> <span m=''2310200''>made</span>
  <span m=''2310420''>a</span> <span m=''2310480''>string.</span> <span m=''2310880''>We</span>
  <span m=''2310960''>don''t</span> <span m=''2311110''>really</span> <span m=''2311310''>care</span>
  <span m=''2311580''>what</span> <span m=''2311700''>it</span> <span m=''2311770''>looks</span>
  <span m=''2311970''>like.</span> <span m=''2312690''>So</span> <span m=''2312740''>you</span>
  <span m=''2312830''>can</span> <span m=''2312930''>make</span> <span m=''2313090''>it</span>
  <span m=''2313150''>fairly</span> <span m=''2313440''>obtuse.</span> <span m=''2313970''>It''s
  just</span> <span m=''2314190''>that</span> <span m=''2314280''>these</span> <span
  m=''2314500''>guys</span> <span m=''2314700''>should</span> <span m=''2314910''>not</span>
  <span m=''2315240''>bend</span> <span m=''2315580''>much.</span> <span m=''2316000''>They</span>
  <span m=''2316110''>have</span> <span m=''2316290''>to</span> <span m=''2316960''>be</span>
  <span m=''2317100''>long</span> <span m=''2317470''>no</span> <span m=''2317560''>matter</span>
  <span m=''2317790''>how</span> <span m=''2317960''>you</span> <span m=''2318100''>fold</span>
  <span m=''2318380''>them.</span> </p><p><span m=''2319560''>So</span> <span m=''2319780''>if</span>
  <span m=''2320020''>you</span> <span m=''2320180''>want</span> <span m=''2322270''>equilateral</span>
  <span m=''2323420''>and</span> <span m=''2323680''>obtuse,</span> <span m=''2324280''>that''s</span>
  <span m=''2324490''>also</span> <span m=''2324800''>easy.</span> <span m=''2325890''>But</span>
  <span m=''2326040''>to</span> <span m=''2326140''>make</span> <span m=''2326330''>all</span>
  <span m=''2326550''>the</span> <span m=''2326670''>angles</span> <span m=''2327030''>actually</span>
  <span m=''2327480''>be</span> <span m=''2327710''>equal,</span> <span m=''2328660''>as</span>
  <span m=''2328750''>far</span> <span m=''2329000''>as</span> <span m=''2329100''>we</span>
  <span m=''2329230''>know</span> <span m=''2329370''>you</span> <span m=''2329560''>cannot</span>
  <span m=''2330120''>take</span> <span m=''2330420''>that</span> <span m=''2330710''>knitting</span>
  <span m=''2330985''>needles</span> <span m=''2331260''>subdivided.</span> <span
  m=''2332430''>Make</span> <span m=''2332650''>all</span> <span m=''2332850''>the</span>
  <span m=''2332910''>lengths</span> <span m=''2333180''>equal,</span> <span m=''2333450''>and</span>
  <span m=''2333680''>all</span> <span m=''2333790''>the</span> <span m=''2333870''>angles</span>
  <span m=''2334160''>equal,</span> <span m=''2334410''>and</span> <span m=''2334730''>make</span>
  <span m=''2334900''>them</span> <span m=''2335030''>obtuse.</span> <span m=''2336370''>That''s</span>
  <span m=''2336600''>open.</span> <span m=''2337300''>But</span> <span m=''2337470''>any</span>
  <span m=''2337710''>two</span> <span m=''2337920''>out</span> <span m=''2338040''>of</span>
  <span m=''2338120''>the</span> <span m=''2338200''>three,</span> <span m=''2338540''>it''s</span>
  <span m=''2338690''>easy.</span> <span m=''2342650''>Of</span> <span m=''2342770''>course,</span>
  <span m=''2343490''>in</span> <span m=''2343520''>reality</span> <span m=''2344000''>they''re</span>
  <span m=''2344100''>not</span> <span m=''2344300''>quite</span> <span m=''2344540''>equilateral.</span>
  <span m=''2345090''>They''re</span> <span m=''2345130''>not</span> <span m=''2345310''>quite</span>
  <span m=''2345740''>equiangular.</span> <span m=''2346720''>But</span> <span m=''2346910''>it''s</span>
  <span m=''2347060''>still</span> <span m=''2347260''>open</span> <span m=''2347550''>for</span>
  <span m=''2347660''>those.</span> <span m=''2347940''>If</span> <span m=''2348080''>you</span>
  <span m=''2348180''>have</span> <span m=''2348320''>like</span> <span m=''2348480''>a</span>
  <span m=''2348530''>small</span> <span m=''2348900''>range</span> <span m=''2349270''>for</span>
  <span m=''2349360''>the</span> <span m=''2349460''>lengths</span> <span m=''2349900''>and</span>
  <span m=''2349980''>a</span> <span m=''2350040''>small</span> <span m=''2350320''>range</span>
  <span m=''2350550''>for</span> <span m=''2350630''>the</span> <span m=''2350750''>angles,</span>
  <span m=''2351580''>this is</span> <span m=''2351810''>open.</span> <span m=''2352170''>We</span>
  <span m=''2352290''>pose</span> <span m=''2352500''>it</span> <span m=''2352600''>this</span>
  <span m=''2352770''>way</span> <span m=''2352960''>because</span> <span m=''2353130''>it''s</span>
  <span m=''2353320''>the</span> <span m=''2353410''>cleanest</span> <span m=''2353840''>geometrically.</span>
  </p><p><span m=''2355600''>But</span> <span m=''2355830''>the</span> <span m=''2356350''>real</span>
  <span m=''2356600''>question</span> <span m=''2356970''>you</span> <span m=''2357080''>care</span>
  <span m=''2357290''>about</span> <span m=''2357560''>is</span> <span m=''2360290''>when</span>
  <span m=''2360400''>these</span> <span m=''2360580''>are</span> <span m=''2360670''>fuzzy</span>
  <span m=''2361070''>constraints.</span> <span m=''2361750''>Obtuse</span> <span
  m=''2362120''>is</span> <span m=''2362250''>real,</span> <span m=''2362610''>but</span>
  <span m=''2362860''>these</span> <span m=''2363080''>guys</span> <span m=''2363360''>are</span>
  <span m=''2364020''>fuzzier.</span> <span m=''2366790''>So</span> <span m=''2367810''>if</span>
  <span m=''2368050''>you</span> <span m=''2368170''>think</span> <span m=''2368360''>about</span>
  <span m=''2369140''>proteins,</span> <span m=''2370440''>which</span> <span m=''2370760''>fold</span>
  <span m=''2371000''>very</span> <span m=''2371220''>well</span> <span m=''2371590''>in</span>
  <span m=''2371760''>nature,</span> <span m=''2372980''>there</span> <span m=''2373120''>are</span>
  <span m=''2373450''>a</span> <span m=''2373470''>couple</span> <span m=''2373850''>of</span>
  <span m=''2374330''>reasons</span> <span m=''2374870''>they</span> <span m=''2375000''>might</span>
  <span m=''2375320''>fold</span> <span m=''2375640''>well.</span> <span m=''2376190''>We</span>
  <span m=''2376410''>know,</span> <span m=''2377300''>as</span> <span m=''2377420''>far</span>
  <span m=''2377600''>as</span> <span m=''2377710''>fixed</span> <span m=''2377930''>angle</span>
  <span m=''2378150''>chains</span> <span m=''2378520''>go,</span> <span m=''2379150''>it''s</span>
  <span m=''2379350''>actually</span> <span m=''2379690''>quite</span> <span m=''2379880''>easy</span>
  <span m=''2380110''>to</span> <span m=''2380180''>find</span> <span m=''2380410''>locked</span>
  <span m=''2380640''>examples.</span> <span m=''2381650''>And,</span> <span m=''2382590''>this</span>
  <span m=''2382830''>is</span> <span m=''2382930''>somewhat</span> <span m=''2383330''>intuitive</span>
  <span m=''2383910''>but</span> <span m=''2384200''>bear</span> <span m=''2384360''>with</span>
  <span m=''2384560''>me,</span> <span m=''2385170''>because</span> <span m=''2385540''>they
  are</span> <span m=''2385710''>locked</span> <span m=''2385970''>examples</span>
  <span m=''2386450''>in</span> <span m=''2386500''>this</span> <span m=''2386650''>configuration</span>
  <span m=''2387240''>space,</span> <span m=''2387630''>we</span> <span m=''2387700''>believe</span>
  <span m=''2388370''>these</span> <span m=''2388540''>configuration</span> <span
  m=''2389140''>spaces</span> <span m=''2389790''>are</span> <span m=''2390000''>really</span>
  <span m=''2390310''>ugly</span> <span m=''2390580''>nasty.</span> <span m=''2391860''>So</span>
  <span m=''2392230''>it</span> <span m=''2392390''>would</span> <span m=''2392530''>be</span>
  <span m=''2392650''>very</span> <span m=''2393040''>hard--</span> <span m=''2393500''>even</span>
  <span m=''2393810''>if</span> <span m=''2393960''>you</span> <span m=''2394090''>know,</span>
  <span m=''2394930''>oh</span> <span m=''2395110''>I</span> <span m=''2395200''>only</span>
  <span m=''2395430''>need</span> <span m=''2395600''>to</span> <span m=''2395660''>fold</span>
  <span m=''2395890''>something</span> <span m=''2396200''>in</span> <span m=''2396290''>my</span>
  <span m=''2396450''>component--</span> <span m=''2398560''>if</span> <span m=''2398750''>these</span>
  <span m=''2398940''>guys</span> <span m=''2399170''>are</span> <span m=''2399230''>highly</span>
  <span m=''2399500''>disconnected</span> <span m=''2400120''>and</span> <span m=''2400250''>flat</span>
  <span m=''2400470''>states</span> <span m=''2400690''>are</span> <span m=''2400780''>all</span>
  <span m=''2400920''>over</span> <span m=''2401050''>the</span> <span m=''2401150''>place,</span>
  <span m=''2402040''>it''s</span> <span m=''2402220''>probably</span> <span m=''2403450''>even</span>
  <span m=''2403800''>within</span> <span m=''2404060''>this</span> <span m=''2404220''>connected</span>
  <span m=''2404530''>component,</span> <span m=''2405000''>it</span> <span m=''2405090''>looks</span>
  <span m=''2405350''>really</span> <span m=''2405660''>ugly.</span> </p><p><span
  m=''2406740''>And</span> <span m=''2406940''>so</span> <span m=''2407100''>it''s</span>
  <span m=''2407220''>very</span> <span m=''2407450''>hard</span> <span m=''2407880''>to</span>
  <span m=''2408180''>find</span> <span m=''2408470''>a</span> <span m=''2408520''>path</span>
  <span m=''2408830''>from</span> <span m=''2409000''>one</span> <span m=''2409170''>state</span>
  <span m=''2409410''>to</span> <span m=''2409520''>another.</span> <span m=''2410650''>Probably</span>
  <span m=''2411640''>pieced</span> <span m=''2411860''>based</span> <span m=''2412060''>complete,</span>
  <span m=''2412360''>although</span> <span m=''2412570''>we</span> <span m=''2412690''>don''t</span>
  <span m=''2412860''>know</span> <span m=''2413010''>that</span> <span m=''2413270''>for
  sure.</span> <span m=''2415840''>But</span> <span m=''2416030''>that''s</span> <span
  m=''2416260''>the</span> <span m=''2416380''>intuition.</span> <span m=''2416940''>Locked</span>
  <span m=''2417390''>equals</span> <span m=''2417860''>messy.</span> <span m=''2419430''>When</span>
  <span m=''2419590''>there</span> <span m=''2419690''>are</span> <span m=''2419760''>no</span>
  <span m=''2420020''>locked</span> <span m=''2420330''>configurations,</span> <span
  m=''2421050''>like</span> <span m=''2421310''>carpenter''s</span> <span m=''2421740''>rules,</span>
  <span m=''2422470''>we</span> <span m=''2422640''>get</span> <span m=''2422800''>really</span>
  <span m=''2423050''>nice</span> <span m=''2423290''>algorithms.</span> <span m=''2423800''>It''s</span>
  <span m=''2423890''>super</span> <span m=''2424210''>easy</span> <span m=''2424430''>to</span>
  <span m=''2424490''>get</span> <span m=''2424690''>from</span> <span m=''2424830''>state</span>
  <span m=''2425080''>A to</span> <span m=''2425330''>state</span> <span m=''2425580''>B.</span>
  <span m=''2427360''>Now,</span> <span m=''2427620''>if</span> <span m=''2427780''>you''re</span>
  <span m=''2427940''>nature</span> <span m=''2428710''>or</span> <span m=''2428850''>you''re</span>
  <span m=''2428960''>designing</span> <span m=''2429410''>nature,</span> <span m=''2429790''>let''s</span>
  <span m=''2429970''>say,</span> <span m=''2430250''>or</span> <span m=''2430600''>you''re</span>
  <span m=''2430780''>building</span> <span m=''2431050''>your</span> <span m=''2431240''>own</span>
  <span m=''2431490''>virtual</span> <span m=''2432090''>world,</span> <span m=''2433320''>Second</span>
  <span m=''2433660''>Life,</span> <span m=''2434760''>and</span> <span m=''2434950''>you</span>
  <span m=''2435080''>want</span> <span m=''2435210''>to</span> <span m=''2435280''>design</span>
  <span m=''2435590''>proteins,</span> <span m=''2436520''>you</span> <span m=''2436710''>would</span>
  <span m=''2436860''>like</span> <span m=''2437050''>to</span> <span m=''2437150''>design</span>
  <span m=''2437530''>them</span> <span m=''2437660''>in</span> <span m=''2437730''>such</span>
  <span m=''2437970''>a</span> <span m=''2438040''>way</span> <span m=''2438200''>that</span>
  <span m=''2438360''>they</span> <span m=''2438500''>fold</span> <span m=''2438820''>easily</span>
  <span m=''2439380''>because</span> <span m=''2439790''>it</span> <span m=''2439850''>happens</span>
  <span m=''2440190''>all</span> <span m=''2440320''>the</span> <span m=''2440400''>time.</span>
  </p><p><span m=''2440740''>Every</span> <span m=''2441620''>thing</span> <span m=''2441940''>that</span>
  <span m=''2442080''>is</span> <span m=''2442340''>being</span> <span m=''2442660''>acted</span>
  <span m=''2443080''>on</span> <span m=''2443260''>by</span> <span m=''2443480''>our</span>
  <span m=''2443570''>body,</span> <span m=''2443880''>every</span> <span m=''2444190''>living</span>
  <span m=''2444500''>thing</span> <span m=''2444690''>that</span> <span m=''2444790''>we</span>
  <span m=''2444950''>know</span> <span m=''2445560''>has</span> <span m=''2445810''>tons</span>
  <span m=''2446150''>of</span> <span m=''2446210''>little</span> <span m=''2446440''>proteins</span>
  <span m=''2446910''>that</span> <span m=''2447030''>are</span> <span m=''2447160''>doing</span>
  <span m=''2447480''>all</span> <span m=''2447640''>the</span> <span m=''2447730''>work.</span>
  <span m=''2448120''>They</span> <span m=''2448430''>are</span> <span m=''2448740''>folded</span>
  <span m=''2449120''>into their</span> <span m=''2449220''>shape</span> <span m=''2449500''>and</span>
  <span m=''2449570''>they</span> <span m=''2449670''>do</span> <span m=''2449810''>something.</span>
  <span m=''2451340''>That''s</span> <span m=''2451500''>proteins</span> <span m=''2451870''>plus</span>
  <span m=''2452100''>RNA,</span> <span m=''2452610''>but</span> <span m=''2452800''>mostly</span>
  <span m=''2453170''>proteins.</span> <span m=''2454570''>So</span> <span m=''2456310''>to</span>
  <span m=''2456690''>understand</span> <span m=''2457050''>life,</span> <span m=''2457340''>we</span>
  <span m=''2457410''>should</span> <span m=''2457550''>understand</span> <span m=''2458000''>proteins.</span>
  <span m=''2458480''>Now,</span> <span m=''2458550''>how</span> <span m=''2458920''>to</span>
  <span m=''2459040''>proteins</span> <span m=''2459730''>fold</span> <span m=''2460240''>so</span>
  <span m=''2460530''>well</span> <span m=''2461080''>when</span> <span m=''2461460''>we</span>
  <span m=''2461590''>know</span> <span m=''2462000''>there</span> <span m=''2462100''>are</span>
  <span m=''2462210''>all</span> <span m=''2462410''>these</span> <span m=''2462570''>locked</span>
  <span m=''2462870''>configurations?</span> <span m=''2464480''>One</span> <span
  m=''2464700''>possible</span> <span m=''2465160''>answer</span> <span m=''2465610''>is
  that</span> <span m=''2465710''>proteins</span> <span m=''2466140''>have</span>
  <span m=''2466300''>extra</span> <span m=''2466580''>structure,</span> <span m=''2467010''>namely</span>
  <span m=''2467420''>these</span> <span m=''2467720''>three</span> <span m=''2467930''>things,</span>
  <span m=''2468610''>which</span> <span m=''2468830''>somehow</span> <span m=''2469240''>make</span>
  <span m=''2469480''>it</span> <span m=''2469570''>very</span> <span m=''2469830''>easy</span>
  <span m=''2470180''>to</span> <span m=''2470280''>algorithmically</span> <span m=''2470910''>go</span>
  <span m=''2471120''>from</span> <span m=''2471280''>A</span> <span m=''2471480''>to</span>
  <span m=''2471560''>B.</span> <span m=''2473140''>Notice</span> <span m=''2473590''>I''m</span>
  <span m=''2473740''>not</span> <span m=''2474440''>assuming</span> <span m=''2474820''>anything</span>
  <span m=''2475360''>about</span> <span m=''2476020''>how</span> <span m=''2476370''>proteins</span>
  <span m=''2476880''>fold</span> <span m=''2478740''>in</span> <span m=''2478910''>terms</span>
  <span m=''2479200''>of</span> <span m=''2479770''>what</span> <span m=''2479990''>is</span>
  <span m=''2480230''>the</span> <span m=''2480440''>mechanism</span> <span m=''2480980''>that</span>
  <span m=''2481090''>drives</span> <span m=''2481450''>them</span> <span m=''2482170''>because</span>
  <span m=''2483200''>we</span> <span m=''2483360''>don''t</span> <span m=''2483540''>really</span>
  <span m=''2483870''>understand</span> <span m=''2484450''>those</span> <span m=''2484640''>mechanisms.</span>
  <span m=''2485760''>There''s</span> <span m=''2485920''>hydrophobia,</span> <span
  m=''2486700''>which</span> <span m=''2486850''>we</span> <span m=''2486920''>don''t</span>
  <span m=''2487060''>really</span> <span m=''2487430''>know</span> <span m=''2487570''>how</span>
  <span m=''2487760''>it</span> <span m=''2487800''>works.</span> </p><p><span m=''2488730''>So</span>
  <span m=''2488750''>all</span> <span m=''2488950''>these</span> <span m=''2489080''>little</span>
  <span m=''2489280''>forces</span> <span m=''2491510''>that</span> <span m=''2491700''>we</span>
  <span m=''2491940''>don''t</span> <span m=''2492140''>fully</span> <span m=''2492510''>understand.</span>
  <span m=''2495170''>We</span> <span m=''2495410''>understand</span> <span m=''2495780''>lots</span>
  <span m=''2495970''>of</span> <span m=''2496030''>parts</span> <span m=''2496290''>of</span>
  <span m=''2496330''>the</span> <span m=''2496400''>story,</span> <span m=''2496760''>but</span>
  <span m=''2496780''>not</span> <span m=''2496970''>the</span> <span m=''2497050''>whole</span>
  <span m=''2497210''>story.</span> <span m=''2499400''>And</span> <span m=''2499500''>what''s</span>
  <span m=''2499540''>convenient</span> <span m=''2499980''>about</span> <span m=''2500390''>these</span>
  <span m=''2500600''>kinds</span> <span m=''2500810''>of</span> <span m=''2500900''>problems</span>
  <span m=''2501220''>is</span> <span m=''2501320''>you</span> <span m=''2501430''>don''t</span>
  <span m=''2501590''>need</span> <span m=''2501760''>to</span> <span m=''2501840''>assume</span>
  <span m=''2502100''>anything</span> <span m=''2502590''>about</span> <span m=''2502850''>how</span>
  <span m=''2503140''>it</span> <span m=''2503230''>actually</span> <span m=''2503570''>happens.</span>
  <span m=''2504800''>All</span> <span m=''2505120''>we''re assuming</span> <span
  m=''2505620''>is</span> <span m=''2505730''>the</span> <span m=''2505810''>mechanical</span>
  <span m=''2506320''>behavior</span> <span m=''2506620''>of the</span> <span m=''2506920''>proteins,</span>
  <span m=''2507950''>and</span> <span m=''2508020''>how</span> <span m=''2508190''>they</span>
  <span m=''2508300''>could</span> <span m=''2508500''>possibly</span> <span m=''2509060''>fold.</span>
  <span m=''2510140''>And</span> <span m=''2511360''>the</span> <span m=''2511930''>idea</span>
  <span m=''2512230''>is</span> <span m=''2512440''>if</span> <span m=''2512560''>there''s</span>
  <span m=''2512740''>locked</span> <span m=''2512890''>configurations,</span> <span
  m=''2513600''>that''s</span> <span m=''2513780''>probably</span> <span m=''2514280''>the</span>
  <span m=''2514390''>wrong</span> <span m=''2514600''>model</span> <span m=''2514930''>because</span>
  <span m=''2515260''>then</span> <span m=''2515450''>everything''s</span> <span m=''2515830''>messy.</span>
  <span m=''2516530''>Now</span> <span m=''2516770''>there''s</span> <span m=''2516970''>also</span>
  <span m=''2517180''>evolution</span> <span m=''2517790''>coming</span> <span m=''2518060''>into</span>
  <span m=''2518200''>play</span> <span m=''2518420''>and</span> <span m=''2518520''>maybe</span>
  <span m=''2518760''>some</span> <span m=''2518990''>proteins</span> <span m=''2519370''>are</span>
  <span m=''2519450''>easy</span> <span m=''2519660''>to</span> <span m=''2519740''>fold,</span>
  <span m=''2520000''>some</span> <span m=''2520520''>proteins</span> <span m=''2520870''>are</span>
  <span m=''2520930''>hard</span> <span m=''2521150''>to</span> <span m=''2521210''>fold.</span>
  <span m=''2522010''>That''s</span> <span m=''2522240''>an</span> <span m=''2522320''>interesting</span>
  <span m=''2522740''>question</span> <span m=''2523180''>which</span> <span m=''2523360''>should</span>
  <span m=''2523680''>be</span> <span m=''2523960''>experimented</span> <span m=''2524600''>with.</span>
  <span m=''2525540''>But</span> <span m=''2525860''>let''s</span> <span m=''2526890''>hope</span>
  <span m=''2527340''>that</span> <span m=''2527810''>there''s</span> <span m=''2528130''>a</span>
  <span m=''2528180''>model.</span> </p><p><span m=''2528790''>Things</span> <span
  m=''2529010''>are</span> <span m=''2529180''>mutating</span> <span m=''2529570''>randomly.</span>
  <span m=''2529990''>You</span> <span m=''2530110''>really</span> <span m=''2530320''>like</span>
  <span m=''2530530''>everything</span> <span m=''2530920''>to</span> <span m=''2530980''>fold</span>
  <span m=''2531430''>nicely.</span> <span m=''2532570''>Maybe</span> <span m=''2532970''>it''s</span>
  <span m=''2533120''>because</span> <span m=''2533650''>you</span> <span m=''2533810''>have</span>
  <span m=''2534050''>all</span> <span m=''2534270''>three</span> <span m=''2534500''>of</span>
  <span m=''2534550''>these</span> <span m=''2534740''>properties,</span> <span m=''2535300''>approximately,</span>
  <span m=''2536420''>in</span> <span m=''2536570''>real</span> <span m=''2536820''>proteins.</span>
  <span m=''2539950''>So</span> <span m=''2540600''>general</span> <span m=''2540880''>idea</span>
  <span m=''2541260''>is that</span> <span m=''2541360''>nature</span> <span m=''2542830''>has</span>
  <span m=''2543100''>some</span> <span m=''2543320''>extra</span> <span m=''2543580''>constraints</span>
  <span m=''2544140''>that</span> <span m=''2544270''>make</span> <span m=''2545080''>protein</span>
  <span m=''2545410''>folding</span> <span m=''2545770''>easy.</span> <span m=''2547180''>Just</span>
  <span m=''2547390''>have to</span> <span m=''2547530''>figure</span> <span m=''2547820''>out</span>
  <span m=''2548610''>what</span> <span m=''2548800''>they</span> <span m=''2548960''>are</span>
  <span m=''2549510''>and</span> <span m=''2549700''>why</span> <span m=''2549920''>it</span>
  <span m=''2550010''>makes</span> <span m=''2550230''>them</span> <span m=''2550340''>easy.</span>
  <span m=''2550790''>Unfortunately,</span> <span m=''2551290''>this is still</span>
  <span m=''2551570''>an</span> <span m=''2551630''>open</span> <span m=''2551870''>problem.</span>
  <span m=''2552190''>If</span> <span m=''2552290''>this</span> <span m=''2552440''>had</span>
  <span m=''2552640''>an</span> <span m=''2552730''>algorithm,</span> <span m=''2553580''>that</span>
  <span m=''2553720''>would</span> <span m=''2553790''>be</span> <span m=''2553890''>a</span>
  <span m=''2553930''>natural</span> <span m=''2554230''>candidate</span> <span m=''2554690''>for</span>
  <span m=''2554820''>what</span> <span m=''2554950''>nature''s</span> <span m=''2555350''>doing</span>
  <span m=''2555700''>using</span> <span m=''2556090''>its</span> <span m=''2556230''>mechanical--</span>
  <span m=''2557400''>or</span> <span m=''2557530''>using</span> <span m=''2557880''>it''s</span>
  <span m=''2558310''>energies</span> <span m=''2558800''>and</span> <span m=''2558910''>forces,</span>
  <span m=''2559300''>and</span> <span m=''2559400''>so</span> <span m=''2559540''>on.</span>
  </p><p><span m=''2562420''>This</span> <span m=''2562580''>would</span> <span m=''2562680''>be</span>
  <span m=''2562830''>a</span> <span m=''2562880''>rather</span> <span m=''2563140''>unsatisfactory</span>
  <span m=''2564020''>ending</span> <span m=''2564450''>if</span> <span m=''2564580''>this</span>
  <span m=''2564790''>was--</span> <span m=''2565715''>if</span> <span m=''2566010''>the</span>
  <span m=''2566160''>climax</span> <span m=''2566640''>was</span> <span m=''2566770''>an</span>
  <span m=''2566850''>open</span> <span m=''2567100''>problem.</span> <span m=''2569570''>We</span>
  <span m=''2569740''>have</span> <span m=''2569920''>a</span> <span m=''2569970''>theorem</span>
  <span m=''2570330''>too.</span> <span m=''2573150''>And</span> <span m=''2573530''>this</span>
  <span m=''2573700''>is</span> <span m=''2573800''>what</span> <span m=''2573970''>I''ll</span>
  <span m=''2574460''>cover</span> <span m=''2574820''>in</span> <span m=''2574930''>most</span>
  <span m=''2575280''>detail.</span> <span m=''2580350''>And</span> <span m=''2580950''>it''s
  a</span> <span m=''2581210''>paper</span> <span m=''2581540''>called</span> <span
  m=''2581720''>producible</span> <span m=''2582420''>protein</span> <span m=''2582870''>chains.</span>
  <span m=''2584620''>Protein</span> <span m=''2585090''>chains</span> <span m=''2585530''>just</span>
  <span m=''2585780''>means</span> <span m=''2586010''>fixed</span> <span m=''2586300''>angle</span>
  <span m=''2587080''>chains,</span> <span m=''2587560''>open</span> <span m=''2587810''>chains.</span>
  <span m=''2589590''>And</span> <span m=''2590230''>the</span> <span m=''2590410''>idea</span>
  <span m=''2590660''>is</span> <span m=''2590750''>well,</span> <span m=''2590920''>yeah,</span>
  <span m=''2591460''>there</span> <span m=''2591610''>are</span> <span m=''2591640''>these</span>
  <span m=''2591870''>constraints</span> <span m=''2593680''>or</span> <span m=''2593810''>there</span>
  <span m=''2594190''>are</span> <span m=''2594210''>these</span> <span m=''2594400''>extra</span>
  <span m=''2594690''>features.</span> <span m=''2595160''>We</span> <span m=''2595280''>don''t</span>
  <span m=''2595420''>know</span> <span m=''2595500''>how</span> <span m=''2595640''>to</span>
  <span m=''2595740''>exploit</span> <span m=''2596110''>them,</span> <span m=''2596330''>so</span>
  <span m=''2597300''>let''s</span> <span m=''2597490''>not</span> <span m=''2597600''>even</span>
  <span m=''2597770''>worry</span> <span m=''2597940''>about them.</span> <span m=''2598300''>Suppose</span>
  <span m=''2598960''>they</span> <span m=''2599080''>don''t</span> <span m=''2599250''>even</span>
  <span m=''2599460''>exist.</span> <span m=''2600410''>Maybe</span> <span m=''2600820''>I''m</span>
  <span m=''2600920''>going</span> <span m=''2601020''>to</span> <span m=''2601070''>assume</span>
  <span m=''2601350''>obtuse,</span> <span m=''2601980''>but</span> <span m=''2602860''>none</span>
  <span m=''2603050''>of</span> <span m=''2603100''>the</span> <span m=''2603270''>others.</span>
  </p><p><span m=''2606220''>There''s</span> <span m=''2606450''>another</span> <span
  m=''2606790''>constraint</span> <span m=''2608770''>in</span> <span m=''2608980''>how</span>
  <span m=''2609370''>proteins</span> <span m=''2610030''>fold,</span> <span m=''2611100''>or</span>
  <span m=''2611260''>really</span> <span m=''2611450''>how</span> <span m=''2611610''>proteins</span>
  <span m=''2612030''>are</span> <span m=''2612140''>created.</span> <span m=''2615650''>They''re</span>
  <span m=''2615880''>created</span> <span m=''2616340''>by</span> <span m=''2616580''>a</span>
  <span m=''2616650''>machine,</span> <span m=''2617290''>a</span> <span m=''2617830''>molecular</span>
  <span m=''2618320''>machine</span> <span m=''2618650''>made</span> <span m=''2618840''>up</span>
  <span m=''2618990''>of</span> <span m=''2619120''>a</span> <span m=''2619170''>whole</span>
  <span m=''2619410''>bunch</span> <span m=''2619650''>of</span> <span m=''2619840''>proteins</span>
  <span m=''2620290''>and</span> <span m=''2620520''>RNA,</span> <span m=''2622260''>called</span>
  <span m=''2622410''>the</span> <span m=''2622490''>ribosome.</span> <span m=''2623632''>You</span>
  <span m=''2623970''>may</span> <span m=''2624110''>have</span> <span m=''2624200''>heard</span>
  <span m=''2624380''>of.</span> <span m=''2624980''>It</span> <span m=''2625170''>translates</span>
  <span m=''2626000''>messenger</span> <span m=''2626520''>RNA</span> <span m=''2626960''>into</span>
  <span m=''2627200''>proteins.</span> <span m=''2628520''>So</span> <span m=''2628630''>there''s</span>
  <span m=''2628770''>some</span> <span m=''2629010''>mRNA</span> <span m=''2629790''>around</span>
  <span m=''2630250''>here,</span> <span m=''2630670''>maybe.</span> <span m=''2631300''>Don''t</span>
  <span m=''2631460''>know</span> <span m=''2631530''>exactly</span> <span m=''2632010''>how</span>
  <span m=''2632120''>this</span> <span m=''2632280''>machine</span> <span m=''2632570''>works.</span>
  <span m=''2633300''>But</span> <span m=''2633510''>there</span> <span m=''2633720''>are</span>
  <span m=''2633800''>actually</span> <span m=''2634070''>very</span> <span m=''2634520''>accurate</span>
  <span m=''2635540''>three</span> <span m=''2635760''>dimensional</span> <span m=''2636120''>reconstructions</span>
  <span m=''2636750''>of</span> <span m=''2636910''>the</span> <span m=''2637010''>ribosome.</span>
  </p><p><span m=''2638370''>With</span> <span m=''2638530''>no</span> <span m=''2638670''>copyright</span>
  <span m=''2639110''>free</span> <span m=''2639260''>images,</span> <span m=''2639790''>you''re</span>
  <span m=''2639970''>going</span> <span m=''2640100''>to</span> <span m=''2640150''>have</span>
  <span m=''2640330''>to--</span> <span m=''2640610''>there''s</span> <span m=''2640770''>a</span>
  <span m=''2640830''>link</span> <span m=''2641140''>on</span> <span m=''2641290''>the</span>
  <span m=''2641380''>slide</span> <span m=''2641880''>that</span> <span m=''2642030''>goes</span>
  <span m=''2642290''>to</span> <span m=''2643630''>the</span> <span m=''2644170''>cool</span>
  <span m=''2644510''>and</span> <span m=''2644630''>3D</span> <span m=''2645350''>models</span>
  <span m=''2645720''>of</span> <span m=''2645800''>the</span> <span m=''2645890''>ribosome,</span>
  <span m=''2647240''>with</span> <span m=''2647430''>a</span> <span m=''2647480''>slice</span>
  <span m=''2647860''>away.</span> <span m=''2648320''>So</span> <span m=''2648370''>you</span>
  <span m=''2648480''>can</span> <span m=''2648600''>see</span> <span m=''2649010''>there''s</span>
  <span m=''2649180''>a</span> <span m=''2649290''>tunnel</span> <span m=''2649720''>down</span>
  <span m=''2649970''>here,</span> <span m=''2651010''>and</span> <span m=''2651890''>the</span>
  <span m=''2652030''>protein</span> <span m=''2652450''>get</span> <span m=''2652620''>sort</span>
  <span m=''2652840''>of</span> <span m=''2652940''>created</span> <span m=''2653530''>here.</span>
  <span m=''2653740''>The</span> <span m=''2654130''>background</span> <span m=''2654750''>gets</span>
  <span m=''2654860''>created</span> <span m=''2655150''>here.</span> <span m=''2655690''>And
  it</span> <span m=''2655920''>starts</span> <span m=''2656220''>going</span> <span
  m=''2656510''>through</span> <span m=''2656640''>this</span> <span m=''2656820''>tunnel.</span>
  <span m=''2657550''>There''s</span> <span m=''2657730''>a</span> <span m=''2657790''>bend</span>
  <span m=''2658140''>in</span> <span m=''2658230''>the</span> <span m=''2658340''>tunnel</span>
  <span m=''2658710''>around</span> <span m=''2659120''>here,</span> <span m=''2659980''>where</span>
  <span m=''2660430''>it''s</span> <span m=''2660690''>conjectured</span> <span m=''2660970''>and</span>
  <span m=''2661250''>an</span> <span m=''2661410''>amino</span> <span m=''2661760''>acid</span>
  <span m=''2662040''>gets</span> <span m=''2662220''>attached.</span> <span m=''2663340''>And</span>
  <span m=''2663520''>then</span> <span m=''2664100''>it</span> <span m=''2664350''>goes</span>
  <span m=''2664640''>out</span> <span m=''2664780''>the</span> <span m=''2664890''>tunnel</span>
  <span m=''2665270''>and</span> <span m=''2665450''>the</span> <span m=''2665540''>protein</span>
  <span m=''2665910''>starts</span> <span m=''2666230''>spewing</span> <span m=''2666690''>out</span>
  <span m=''2666840''>here</span> <span m=''2667190''>and</span> <span m=''2667440''>presumably</span>
  <span m=''2668070''>folding</span> <span m=''2668460''>at</span> <span m=''2668570''>the</span>
  <span m=''2668650''>same</span> <span m=''2668890''>time.</span> <span m=''2669180''>We
  don''t</span> <span m=''2669380''>really</span> <span m=''2669600''>know.</span>
  <span m=''2671770''>So</span> <span m=''2671940''>this</span> <span m=''2672140''>is</span>
  <span m=''2672260''>how</span> <span m=''2672510''>proteins</span> <span m=''2673120''>are</span>
  <span m=''2673540''>created.</span> <span m=''2676620''>The</span> <span m=''2676700''>birds</span>
  <span m=''2677000''>and</span> <span m=''2677110''>bees,</span> <span m=''2677500''>I</span>
  <span m=''2677590''>guess,</span> <span m=''2677930''>of</span> <span m=''2678030''>proteins.</span>
  </p><p><span m=''2679030''>So</span> <span m=''2681220''>what''s</span> <span m=''2681520''>interesting</span>
  <span m=''2682050''>about</span> <span m=''2682340''>this</span> <span m=''2682530''>is</span>
  <span m=''2682670''>it''s</span> <span m=''2682880''>not</span> <span m=''2683170''>like</span>
  <span m=''2683490''>a</span> <span m=''2683550''>protein</span> <span m=''2684050''>exists</span>
  <span m=''2684710''>and</span> <span m=''2684850''>then</span> <span m=''2684970''>folds,</span>
  <span m=''2685790''>which</span> <span m=''2685990''>is</span> <span m=''2686110''>how</span>
  <span m=''2686380''>a</span> <span m=''2686430''>lot</span> <span m=''2686680''>of</span>
  <span m=''2687560''>people</span> <span m=''2687850''>might</span> <span m=''2688120''>think</span>
  <span m=''2688300''>about</span> <span m=''2688560''>it</span> <span m=''2688740''>at</span>
  <span m=''2689030''>first</span> <span m=''2689410''>glance.</span> <span m=''2690780''>That''s
  the</span> <span m=''2691100''>natural</span> <span m=''2691460''>way</span> <span
  m=''2691600''>to</span> <span m=''2691670''>model</span> <span m=''2691950''>protein</span>
  <span m=''2692240''>folding--</span> <span m=''2692540''>start</span> <span m=''2692750''>with</span>
  <span m=''2692840''>a</span> <span m=''2692890''>protein,</span> <span m=''2693320''>say,
  and</span> <span m=''2693700''>just</span> <span m=''2693890''>zigzag</span> <span
  m=''2694950''>configuration.</span> <span m=''2695270''>If</span> <span m=''2695590''>it''s</span>
  <span m=''2695820''>obtuse,</span> <span m=''2696240''>there''s</span> <span m=''2696400''>a</span>
  <span m=''2696450''>nice</span> <span m=''2696980''>zigzag</span> <span m=''2697380''>monotone</span>
  <span m=''2697750''>configuration.</span> <span m=''2698420''>Then</span> <span
  m=''2698460''>you</span> <span m=''2698550''>see</span> <span m=''2698800''>what</span>
  <span m=''2699060''>is</span> <span m=''2699800''>the</span> <span m=''2699880''>best</span>
  <span m=''2700120''>configuration</span> <span m=''2700750''>I</span> <span m=''2700810''>could</span>
  <span m=''2700970''>fold</span> <span m=''2701200''>into,</span> <span m=''2701600''>for
  some</span> <span m=''2701790''>notion</span> <span m=''2702040''>of</span> <span
  m=''2702100''>best.</span> <span m=''2705530''>And</span> <span m=''2705720''>that''s</span>
  <span m=''2705940''>sort</span> <span m=''2706190''>of</span> <span m=''2706260''>what</span>
  <span m=''2706410''>this</span> <span m=''2706570''>configuration</span> <span m=''2707240''>space</span>
  <span m=''2707500''>picture is</span> <span m=''2707910''>about.</span> </p><p><span
  m=''2708450''>It''s</span> <span m=''2709240''>if I already</span> <span m=''2709580''>have</span>
  <span m=''2709880''>a</span> <span m=''2709950''>protein,</span> <span m=''2710740''>what</span>
  <span m=''2710950''>configurations</span> <span m=''2711630''>can</span> <span m=''2711810''>I</span>
  <span m=''2711890''>reach</span> <span m=''2712230''>by</span> <span m=''2712350''>motions?</span>
  <span m=''2713060''>And</span> <span m=''2713210''>that</span> <span m=''2713350''>is</span>
  <span m=''2713470''>interesting.</span> <span m=''2714000''>That''s</span> <span
  m=''2714200''>important</span> <span m=''2714630''>because</span> <span m=''2714850''>you''re</span>
  <span m=''2714990''>still</span> <span m=''2715170''>going</span> <span m=''2715270''>to</span>
  <span m=''2715350''>have</span> <span m=''2715520''>to</span> <span m=''2716140''>reach</span>
  <span m=''2716360''>by a</span> <span m=''2716550''>motion.</span> <span m=''2717050''>But,</span>
  <span m=''2717490''>it''s</span> <span m=''2717940''>actually</span> <span m=''2718390''>more</span>
  <span m=''2718610''>flexible</span> <span m=''2718865''>than</span> <span m=''2719120''>that</span>
  <span m=''2720210''>because</span> <span m=''2720870''>the</span> <span m=''2720950''>protein</span>
  <span m=''2721380''>could</span> <span m=''2721560''>just</span> <span m=''2721800''>be</span>
  <span m=''2721930''>partially</span> <span m=''2722500''>built.</span> <span m=''2723720''>The</span>
  <span m=''2724200''>rest</span> <span m=''2724460''>of</span> <span m=''2724510''>the</span>
  <span m=''2724580''>protein</span> <span m=''2724930''>hasn''t</span> <span m=''2725320''>been</span>
  <span m=''2725450''>built.</span> <span m=''2726720''>And</span> <span m=''2726870''>it</span>
  <span m=''2726920''>could</span> <span m=''2727210''>start</span> <span m=''2727460''>folding</span>
  <span m=''2727760''>already.</span> <span m=''2728960''>It</span> <span m=''2729020''>might</span>
  <span m=''2729210''>be</span> <span m=''2729400''>easier to</span> <span m=''2729780''>fold</span>
  <span m=''2730130''>when</span> <span m=''2730230''>you</span> <span m=''2730340''>don''t</span>
  <span m=''2730500''>have</span> <span m=''2730760''>the</span> <span m=''2730870''>obstacles</span>
  <span m=''2732300''>of</span> <span m=''2732420''>your</span> <span m=''2732630''>existing</span>
  <span m=''2733030''>protein.</span> <span m=''2733460''>So</span> <span m=''2733600''>that''s</span>
  <span m=''2734750''>both</span> <span m=''2734950''>a</span> <span m=''2735040''>worry,</span>
  <span m=''2736010''>but</span> <span m=''2736120''>it''s</span> <span m=''2736270''>also</span>
  <span m=''2737350''>a</span> <span m=''2737460''>convenient</span> <span m=''2738530''>structure</span>
  <span m=''2739050''>because</span> <span m=''2739550''>this</span> <span m=''2739740''>ribosome</span>
  <span m=''2740440''>is</span> <span m=''2740610''>a</span> <span m=''2740730''>giant</span>
  <span m=''2741490''>obstacle.</span> <span m=''2743160''>Bigger</span> <span m=''2743450''>than</span>
  <span m=''2743620''>most</span> <span m=''2743880''>proteins.</span> <span m=''2745550''>If</span>
  <span m=''2745700''>your</span> <span m=''2745810''>protein''s</span> <span m=''2746140''>really</span>
  <span m=''2746480''>long,</span> <span m=''2746780''>maybe</span> <span m=''2747080''>it</span>
  <span m=''2747190''>could</span> <span m=''2747270''>go</span> <span m=''2747400''>over</span>
  <span m=''2747590''>here.</span> </p><p><span m=''2748110''>But</span> <span m=''2748250''>most</span>
  <span m=''2748480''>the</span> <span m=''2748610''>time,</span> <span m=''2748900''>it''s</span>
  <span m=''2749080''>going</span> <span m=''2749190''>to</span> <span m=''2749260''>stay</span>
  <span m=''2749600''>on</span> <span m=''2749760''>one</span> <span m=''2749950''>side</span>
  <span m=''2750330''>of</span> <span m=''2750490''>this</span> <span m=''2750650''>plane</span>
  <span m=''2752300''>because</span> <span m=''2752530''>locally,</span> <span m=''2753440''>this</span>
  <span m=''2753610''>thing</span> <span m=''2753740''>is</span> <span m=''2753840''>basically</span>
  <span m=''2754220''>flat,</span> <span m=''2754980''>if</span> <span m=''2755080''>you</span>
  <span m=''2755180''>look</span> <span m=''2755220''>at</span> <span m=''2755310''>the</span>
  <span m=''2755490''>real</span> <span m=''2756010''>3D</span> <span m=''2756510''>pictures,</span>
  <span m=''2756910''>not</span> <span m=''2757070''>the</span> <span m=''2757180''>schematic.</span>
  <span m=''2759330''>Now,</span> <span m=''2759490''>this</span> <span m=''2759800''>is</span>
  <span m=''2759930''>good</span> <span m=''2760100''>news</span> <span m=''2760380''>for</span>
  <span m=''2760810''>a</span> <span m=''2760940''>geometer</span> <span m=''2761280''>because</span>
  <span m=''2761670''>there''s</span> <span m=''2761840''>this</span> <span m=''2762020''>giant</span>
  <span m=''2762540''>obstacle--</span> <span m=''2763420''>think</span> <span m=''2763590''>of</span>
  <span m=''2763670''>it</span> <span m=''2763750''>as</span> <span m=''2763850''>a</span>
  <span m=''2763900''>half</span> <span m=''2764190''>space--</span> <span m=''2765340''>which</span>
  <span m=''2765590''>the</span> <span m=''2765710''>protein</span> <span m=''2766080''>cannot</span>
  <span m=''2766600''>penetrate</span> <span m=''2767140''>while</span> <span m=''2767630''>it''s</span>
  <span m=''2767920''>being</span> <span m=''2768210''>produced</span> <span m=''2768620''>over</span>
  <span m=''2768800''>here.</span> <span m=''2772820''>That''s</span> <span m=''2773060''>it.</span>
  <span m=''2774010''>That</span> <span m=''2774760''>half</span> <span m=''2775050''>space</span>
  <span m=''2775500''>constraint</span> <span m=''2776910''>is</span> <span m=''2777080''>enough</span>
  <span m=''2777480''>to</span> <span m=''2777700''>get</span> <span m=''2778030''>really</span>
  <span m=''2778330''>good</span> <span m=''2778540''>algorithms</span> <span m=''2779050''>for</span>
  <span m=''2780180''>folding</span> <span m=''2780580''>your</span> <span m=''2780750''>chain.</span>
  <span m=''2781100''>It''s</span> <span m=''2781260''>weird</span> <span m=''2781520''>because</span>
  <span m=''2782250''>we''ve</span> <span m=''2782390''>made</span> <span m=''2782620''>a</span>
  <span m=''2782690''>problem</span> <span m=''2782960''>both</span> <span m=''2783110''>harder</span>
  <span m=''2784140''>because</span> <span m=''2785010''>the</span> <span m=''2785200''>protein
  is</span> <span m=''2785630''>only</span> <span m=''2785820''>partially</span> <span
  m=''2786250''>produced</span> <span m=''2786810''>at</span> <span m=''2786900''>any</span>
  <span m=''2787100''>time</span> <span m=''2787350''>and</span> <span m=''2787390''>it</span>
  <span m=''2787450''>can fold,</span> <span m=''2787960''>which</span> <span m=''2788110''>is</span>
  <span m=''2788180''>part</span> <span m=''2788440''>of</span> <span m=''2788540''>it,</span>
  <span m=''2789510''>but</span> <span m=''2789660''>we''ve</span> <span m=''2789820''>also
  made our</span> <span m=''2790190''>life</span> <span m=''2790430''>easier</span>
  <span m=''2790730''>because</span> <span m=''2790930''>there''s</span> <span m=''2791080''>this</span>
  <span m=''2791220''>big</span> <span m=''2791410''>obstacle.</span> </p><p><span
  m=''2792900''>AUDIENCE:</span> <span m=''2793380''>[INAUDIBLE]</span> <span m=''2793860''>makes</span>
  <span m=''2794340''>sense why there''s</span> <span m=''2794820''>only obtuse</span>
  <span m=''2795300''>angles</span> <span m=''2795780''>there,</span> <span m=''2796260''>right?</span>
  </p><p><span m=''2797710''>PROFESSOR: Yeah,</span> <span m=''2798310''>right.</span>
  <span m=''2799030''>Out</span> <span m=''2799230''>of</span> <span m=''2799320''>this,</span>
  <span m=''2799510''>we''re</span> <span m=''2799620''>going</span> <span m=''2799750''>to</span>
  <span m=''2799800''>get</span> <span m=''2799980''>that</span> <span m=''2800090''>the</span>
  <span m=''2800240''>angles</span> <span m=''2800670''>and</span> <span m=''2800760''>the</span>
  <span m=''2800850''>protein</span> <span m=''2801260''>are</span> <span m=''2801440''>constrained.</span>
  <span m=''2802310''>And</span> <span m=''2802550''>in</span> <span m=''2802620''>particular,</span>
  <span m=''2803880''>for</span> <span m=''2804080''>this</span> <span m=''2804400''>angle--</span>
  <span m=''2807550''>it</span> <span m=''2807890''>depends.</span> <span m=''2808430''>I</span>
  <span m=''2808500''>mean,</span> <span m=''2809520''>in</span> <span m=''2809880''>this</span>
  <span m=''2810070''>picture</span> <span m=''2810370''>because</span> <span m=''2810650''>it''s</span>
  <span m=''2810780''>perpendicular</span> <span m=''2811175''>here,</span> <span
  m=''2811570''>yeah,</span> <span m=''2814630''>the</span> <span m=''2814840''>sharpest</span>
  <span m=''2815220''>angle</span> <span m=''2815460''>you</span> <span m=''2815590''>could</span>
  <span m=''2815710''>make</span> <span m=''2815910''>is</span> <span m=''2816010''>90</span>
  <span m=''2816250''>degrees,</span> <span m=''2817200''>more</span> <span m=''2817400''>or</span>
  <span m=''2817420''>less.</span> <span m=''2818870''>That''s a</span> <span m=''2819040''>good</span>
  <span m=''2819160''>point.</span> <span m=''2820760''>So</span> <span m=''2820860''>it''s</span>
  <span m=''2821330''>a</span> <span m=''2821560''>convenient</span> <span m=''2822100''>match</span>
  <span m=''2822530''>between</span> <span m=''2823490''>the</span> <span m=''2823610''>chemistry,</span>
  <span m=''2824170''>which</span> <span m=''2824390''>also</span> <span m=''2824670''>forces</span>
  <span m=''2825000''>the</span> <span m=''2825090''>angles</span> <span m=''2825380''>to</span>
  <span m=''2825470''>be</span> <span m=''2825650''>obtuse,</span> <span m=''2825900''>I</span>
  <span m=''2825920''>guess.</span> <span m=''2827300''>I</span> <span m=''2827380''>don''t</span>
  <span m=''2827510''>know</span> <span m=''2827710''>a</span> <span m=''2827780''>ton</span>
  <span m=''2827950''>of</span> <span m=''2828030''>chemistry.</span> <span m=''2829030''>But</span>
  <span m=''2829210''>also,</span> <span m=''2829430''>the</span> <span m=''2829540''>ribosome</span>
  <span m=''2830000''>just</span> <span m=''2830150''>geometrically</span> <span m=''2830740''>forces.</span>
  <span m=''2831380''>We''re</span> <span m=''2831510''>going</span> <span m=''2831620''>to</span>
  <span m=''2831670''>use</span> <span m=''2831950''>a</span> <span m=''2832030''>property</span>
  <span m=''2832430''>like</span> <span m=''2832660''>that.</span> </p><p><span m=''2833240''>Our</span>
  <span m=''2833410''>model</span> <span m=''2833700''>is</span> <span m=''2833800''>going</span>
  <span m=''2833930''>to</span> <span m=''2834010''>be</span> <span m=''2834180''>a</span>
  <span m=''2834220''>little</span> <span m=''2834570''>bit</span> <span m=''2834780''>more--</span>
  <span m=''2836640''>both</span> <span m=''2836960''>more</span> <span m=''2837150''>general</span>
  <span m=''2837570''>and</span> <span m=''2837930''>simpler.</span> <span m=''2840190''>We''re</span>
  <span m=''2840430''>going</span> <span m=''2840550''>to</span> <span m=''2840600''>imagine</span>
  <span m=''2841050''>that</span> <span m=''2841450''>the</span> <span m=''2841600''>ribosome</span>
  <span m=''2841830''>is</span> <span m=''2841940''>a</span> <span m=''2842270''>cone.</span>
  <span m=''2843860''>It''s</span> <span m=''2844020''>part</span> <span m=''2844550''>of</span>
  <span m=''2844680''>the</span> <span m=''2844880''>upper</span> <span m=''2845170''>come</span>
  <span m=''2845490''>here.</span> <span m=''2845800''>This</span> <span m=''2846000''>is</span>
  <span m=''2846170''>like</span> <span m=''2846865''>a</span> <span m=''2847350''>mirror</span>
  <span m=''2847590''>image.</span> <span m=''2849320''>And</span> <span m=''2850610''>in</span>
  <span m=''2851020''>reality, that</span> <span m=''2851310''>cone</span> <span m=''2851560''>is</span>
  <span m=''2851670''>actually</span> <span m=''2852400''>a</span> <span m=''2852480''>plane</span>
  <span m=''2853010''>and</span> <span m=''2853090''>everything</span> <span m=''2853440''>above</span>
  <span m=''2853720''>the</span> <span m=''2853820''>plane.</span> <span m=''2854380''>But</span>
  <span m=''2854570''>to</span> <span m=''2854640''>be</span> <span m=''2854750''>more</span>
  <span m=''2854930''>general,</span> <span m=''2855310''>we''re</span> <span m=''2855430''>going</span>
  <span m=''2855660''>to</span> <span m=''2855770''>allow</span> <span m=''2856110''>some</span>
  <span m=''2856810''>angle</span> <span m=''2857160''>alpha</span> <span m=''2857500''>here.</span>
  <span m=''2858020''>It''s</span> <span m=''2858220''>also</span> <span m=''2858410''>just</span>
  <span m=''2858650''>easier</span> <span m=''2858940''>to</span> <span m=''2859020''>think</span>
  <span m=''2859210''>about</span> <span m=''2859460''>when</span> <span m=''2859600''>alpha
  is</span> <span m=''2859900''>smaller</span> <span m=''2860360''>than</span> <span
  m=''2860710''>90,</span> <span m=''2861310''>but</span> <span m=''2862110''>everything</span>
  <span m=''2862480''>I</span> <span m=''2862510''>say</span> <span m=''2862680''>will</span>
  <span m=''2862840''>work</span> <span m=''2863030''>when</span> <span m=''2863130''>alpha</span>
  <span m=''2863330''>equals</span> <span m=''2863570''>90</span> <span m=''2863860''>and</span>
  <span m=''2863950''>that</span> <span m=''2864120''>is</span> <span m=''2864470''>sort
  of the</span> <span m=''2864710''>reality</span> <span m=''2865640''>case.</span>
  </p><p><span m=''2867120''>So</span> <span m=''2867760''>the</span> <span m=''2867860''>model</span>
  <span m=''2868280''>is--</span> <span m=''2870050''>so</span> <span m=''2870220''>the</span>
  <span m=''2870360''>ribosome</span> <span m=''2871350''>is</span> <span m=''2871440''>a</span>
  <span m=''2871520''>cone.</span> <span m=''2872560''>We</span> <span m=''2872740''>call</span>
  <span m=''2872920''>this</span> <span m=''2873170''>the</span> <span m=''2873260''>half</span>
  <span m=''2873650''>angle</span> <span m=''2873960''>of</span> <span m=''2874050''>the</span>
  <span m=''2874160''>cone.</span> <span m=''2874680''>From</span> <span m=''2875000''>the</span>
  <span m=''2875160''>vertical</span> <span m=''2875580''>axis</span> <span m=''2876640''>to</span>
  <span m=''2876900''>the</span> <span m=''2877220''>edge</span> <span m=''2877430''>of</span>
  <span m=''2877480''>the</span> <span m=''2877570''>cone</span> <span m=''2877800''>is</span>
  <span m=''2877920''>alpha.</span> <span m=''2878900''>So</span> <span m=''2878950''>if</span>
  <span m=''2879040''>you were</span> <span m=''2879190''>going</span> <span m=''2879550''>from</span>
  <span m=''2879730''>one</span> <span m=''2879850''>axis</span> <span m=''2880140''>to</span>
  <span m=''2880220''>the</span> <span m=''2880310''>other,</span> <span m=''2880510''>it
  would be 2</span> <span m=''2880830''>alpha.</span> <span m=''2883240''>The</span>
  <span m=''2884640''>model</span> <span m=''2885040''>is,</span> <span m=''2886170''>you</span>
  <span m=''2886270''>start</span> <span m=''2886630''>with</span> <span m=''2886780''>one</span>
  <span m=''2887370''>link</span> <span m=''2887850''>of</span> <span m=''2888020''>your</span>
  <span m=''2888130''>chain,</span> <span m=''2888450''>which</span> <span m=''2888610''>is</span>
  <span m=''2888740''>inside</span> <span m=''2889160''>the</span> <span m=''2889240''>cone.</span>
  <span m=''2889920''>It''s</span> <span m=''2890110''>spews</span> <span m=''2890630''>out</span>
  <span m=''2892490''>through</span> <span m=''2892820''>the</span> <span m=''2892980''>apex.</span>
  <span m=''2894960''>That''s</span> <span m=''2895550''>the</span> <span m=''2895690''>exit</span>
  <span m=''2896000''>of</span> <span m=''2896130''>the</span> <span m=''2896230''>tunnel.</span>
  <span m=''2896850''>Here,</span> <span m=''2897020''>we''re</span> <span m=''2897270''>allowing</span>
  <span m=''2897680''>the</span> <span m=''2897770''>tunnel</span> <span m=''2898070''>to</span>
  <span m=''2898170''>be</span> <span m=''2898310''>actually</span> <span m=''2898590''>quite</span>
  <span m=''2898950''>free.</span> <span m=''2899930''>Doesn''t</span> <span m=''2900170''>have</span>
  <span m=''2900360''>to</span> <span m=''2900470''>be</span> <span m=''2900640''>perpendicular</span>
  <span m=''2901550''>to</span> <span m=''2902540''>the</span> <span m=''2902670''>apex</span>
  <span m=''2903920''>or</span> <span m=''2904280''>the</span> <span m=''2904470''>plane</span>
  <span m=''2904790''>of</span> <span m=''2904870''>the</span> <span m=''2905030''>apex.</span>
  <span m=''2905860''>So</span> <span m=''2906230''>the</span> <span m=''2906570''>edge</span>
  <span m=''2906850''>comes</span> <span m=''2907130''>out,</span> <span m=''2907360''>and</span>
  <span m=''2907450''>as</span> <span m=''2907700''>soon</span> <span m=''2907920''>as</span>
  <span m=''2909420''>the</span> <span m=''2909620''>endpoint</span> <span m=''2910220''>of</span>
  <span m=''2910340''>the</span> <span m=''2910420''>chain</span> <span m=''2910780''>reaches</span>
  <span m=''2911210''>here,</span> <span m=''2911850''>then</span> <span m=''2911930''>a</span>
  <span m=''2912010''>new</span> <span m=''2912170''>link</span> <span m=''2912360''>is</span>
  <span m=''2912490''>created.</span> </p><p><span m=''2913430''>This</span> <span
  m=''2913580''>is</span> <span m=''2913680''>like</span> <span m=''2913850''>a</span>
  <span m=''2913900''>very</span> <span m=''2914280''>simple</span> <span m=''2914640''>model</span>
  <span m=''2914980''>for</span> <span m=''2916150''>how</span> <span m=''2917200''>a</span>
  <span m=''2917360''>chain can</span> <span m=''2917540''>come</span> <span m=''2917880''>out</span>
  <span m=''2918150''>of</span> <span m=''2918250''>a</span> <span m=''2918330''>cone</span>
  <span m=''2919040''>without</span> <span m=''2919350''>worrying</span> <span m=''2919680''>about</span>
  <span m=''2919880''>what''s</span> <span m=''2920050''>happening</span> <span m=''2920410''>inside</span>
  <span m=''2920790''>the</span> <span m=''2920880''>cone.</span> <span m=''2921940''>Imagining</span>
  <span m=''2922390''>everything''s</span> <span m=''2922870''>totally</span> <span
  m=''2923210''>free.</span> <span m=''2924410''>This</span> <span m=''2924570''>is</span>
  <span m=''2924690''>like</span> <span m=''2924890''>you</span> <span m=''2925020''>can</span>
  <span m=''2925140''>allow</span> <span m=''2925360''>self</span> <span m=''2925610''>intersection</span>
  <span m=''2926110''>in the</span> <span m=''2926200''>cone,</span> <span m=''2926460''>who</span>
  <span m=''2926590''>knows</span> <span m=''2926820''>what.</span> <span m=''2927530''>But</span>
  <span m=''2927670''>once</span> <span m=''2927900''>you</span> <span m=''2927990''>come</span>
  <span m=''2928200''>outside</span> <span m=''2928580''>the</span> <span m=''2928660''>cone,</span>
  <span m=''2928930''>you''re</span> <span m=''2929030''>not</span> <span m=''2929190''>allowed</span>
  <span m=''2929430''>to</span> <span m=''2929490''>self</span> <span m=''2929740''>intersect</span>
  <span m=''2930570''>and</span> <span m=''2931050''>you''re</span> <span m=''2931200''>not</span>
  <span m=''2931350''>allowed</span> <span m=''2931580''>to</span> <span m=''2931620''>intersect</span>
  <span m=''2932040''>the</span> <span m=''2932120''>cone.</span> <span m=''2933120''>Once</span>
  <span m=''2933280''>you</span> <span m=''2933380''>come</span> <span m=''2933580''>out,</span>
  <span m=''2933780''>you</span> <span m=''2933900''>can''t</span> <span m=''2934100''>go</span>
  <span m=''2934210''>back</span> <span m=''2934460''>in.</span> <span m=''2936560''>So</span>
  <span m=''2936790''>that</span> <span m=''2936980''>is</span> <span m=''2937090''>a</span>
  <span m=''2937140''>model</span> <span m=''2937440''>of</span> <span m=''2937550''>producing</span>
  <span m=''2939140''>protein</span> <span m=''2939560''>chains.</span> <span m=''2940860''>And</span>
  <span m=''2941320''>if</span> <span m=''2941620''>you</span> <span m=''2941750''>have</span>
  <span m=''2942730''>a</span> <span m=''2942890''>cone</span> <span m=''2943330''>of</span>
  <span m=''2943530''>angle</span> <span m=''2943840''>alpha,</span> <span m=''2944240''>we</span>
  <span m=''2944390''>call</span> <span m=''2944620''>this</span> <span m=''2944790''>an</span>
  <span m=''2944930''>alpha</span> <span m=''2945740''>producible</span> <span m=''2946940''>chain.</span>
  <span m=''2950090''>For</span> <span m=''2950270''>whatever</span> <span m=''2950570''>reason,</span>
  <span m=''2950900''>we</span> <span m=''2951100''>often</span> <span m=''2951390''>call</span>
  <span m=''2951630''>it</span> <span m=''2951950''>beta</span> <span m=''2952260''>producible</span>
  <span m=''2952780''>chain.</span> <span m=''2953962''>Just</span> <span m=''2954370''>change</span>
  <span m=''2954720''>the</span> <span m=''2954770''>variable.</span> </p><p><span
  m=''2980660''>So</span> <span m=''2980820''>if</span> <span m=''2980880''>you</span>
  <span m=''2980960''>think</span> <span m=''2981130''>of</span> <span m=''2981190''>the</span>
  <span m=''2981280''>ribosome</span> <span m=''2981810''>as</span> <span m=''2981930''>a</span>
  <span m=''2982010''>cone</span> <span m=''2982360''>with</span> <span m=''2982550''>half</span>
  <span m=''2982790''>angle</span> <span m=''2983000''>beta,</span> <span m=''2983930''>you</span>
  <span m=''2984040''>can</span> <span m=''2984180''>produce</span> <span m=''2984480''>it</span>
  <span m=''2984570''>like</span> <span m=''2984760''>this.</span> <span m=''2985610''>That
  is</span> <span m=''2985860''>beta</span> <span m=''2986080''>producible.</span>
  <span m=''2986610''>Now</span> <span m=''2986730''>this</span> <span m=''2986910''>is</span>
  <span m=''2986990''>a</span> <span m=''2987040''>pretty</span> <span m=''2987290''>powerful</span>
  <span m=''2987670''>model</span> <span m=''2988540''>because</span> <span m=''2989810''>you</span>
  <span m=''2990020''>only</span> <span m=''2990230''>have</span> <span m=''2990390''>to</span>
  <span m=''2990490''>worry</span> <span m=''2990640''>about</span> <span m=''2990850''>it</span>
  <span m=''2990910''>link</span> <span m=''2991140''>by</span> <span m=''2991270''>link.</span>
  <span m=''2991650''>You</span> <span m=''2991720''>don''t</span> <span m=''2991840''>have</span>
  <span m=''2991970''>to</span> <span m=''2992070''>worry</span> <span m=''2992220''>about</span>
  <span m=''2992450''>the</span> <span m=''2992540''>rest</span> <span m=''2992810''>of</span>
  <span m=''2992890''>the</span> <span m=''2992970''>chain</span> <span m=''2993300''>until</span>
  <span m=''2993600''>it</span> <span m=''2994160''>spews</span> <span m=''2994370''>outside</span>
  <span m=''2994770''>of</span> <span m=''2994870''>the</span> <span m=''2994960''>cone.</span>
  <span m=''2995770''>But</span> <span m=''2995930''>it''s</span> <span m=''2996060''>restrictive</span>
  <span m=''2996570''>in</span> <span m=''2996640''>that</span> <span m=''2996740''>you</span>
  <span m=''2996870''>cannot</span> <span m=''2997210''>penetrate</span> <span m=''2997640''>the</span>
  <span m=''2997710''>cone.</span> <span m=''3001560''>All</span> <span m=''3001670''>right.</span>
  </p><p><span m=''3002820''>One</span> <span m=''3003060''>thing</span> <span m=''3003330''>we</span>
  <span m=''3003460''>can</span> <span m=''3003610''>talk</span> <span m=''3003880''>about</span>
  <span m=''3004560''>is</span> <span m=''3004890''>angles.</span> <span m=''3006810''>So</span>
  <span m=''3008480''>I''m</span> <span m=''3008640''>going</span> <span m=''3008740''>to</span>
  <span m=''3008830''>write</span> <span m=''3011020''>call</span> <span m=''3011240''>a</span>
  <span m=''3011320''>chain</span> <span m=''3011720''>a</span> <span m=''3011960''>less</span>
  <span m=''3012270''>than</span> <span m=''3012370''>or</span> <span m=''3012380''>equal</span>
  <span m=''3012590''>to</span> <span m=''3012670''>alpha</span> <span m=''3013040''>chain</span>
  <span m=''3014810''>if</span> <span m=''3015670''>all</span> <span m=''3015900''>the</span>
  <span m=''3016000''>turn</span> <span m=''3016290''>angles</span> <span m=''3016680''>are</span>
  <span m=''3016860''>less</span> <span m=''3017140''>than</span> <span m=''3017280''>or</span>
  <span m=''3017360''>equal</span> <span m=''3017530''>to</span> <span m=''3017750''>alpha.</span>
  <span m=''3022420''>I don''t know</span> <span m=''3022650''>if</span> <span m=''3022770''>I''ve</span>
  <span m=''3022910''>used</span> <span m=''3023190''>turn</span> <span m=''3023550''>angles</span>
  <span m=''3024160''>in</span> <span m=''3024260''>this</span> <span m=''3024460''>class.</span>
  <span m=''3024860''>Probably.</span> <span m=''3026900''>If</span> <span m=''3027080''>I</span>
  <span m=''3027150''>have</span> <span m=''3027510''>two</span> <span m=''3027720''>edges,</span>
  <span m=''3029240''>the</span> <span m=''3029460''>angle</span> <span m=''3029840''>would</span>
  <span m=''3029990''>be</span> <span m=''3030150''>this.</span> <span m=''3031270''>The</span>
  <span m=''3031400''>turn</span> <span m=''3031650''>angle</span> <span m=''3032050''>would</span>
  <span m=''3032200''>be</span> <span m=''3032340''>this,</span> <span m=''3032800''>the</span>
  <span m=''3033000''>supplement.</span> <span m=''3038410''>Yeah.</span> <span m=''3038610''>I</span>
  <span m=''3038680''>guess</span> <span m=''3038850''>we used</span> <span m=''3039050''>turn
  angles</span> <span m=''3039490''>way</span> <span m=''3039600''>back</span> <span
  m=''3039820''>in</span> <span m=''3039900''>origami</span> <span m=''3040380''>land,</span>
  <span m=''3041210''>Kawasaki''s</span> <span m=''3041810''>theorem</span> <span
  m=''3042040''>and</span> <span m=''3042130''>so</span> <span m=''3042280''>on.</span>
  <span m=''3042840''>It''s</span> <span m=''3042940''>just,</span> <span m=''3043170''>if</span>
  <span m=''3043250''>you''re</span> <span m=''3043380''>going</span> <span m=''3043600''>straight,</span>
  <span m=''3043880''>how</span> <span m=''3043970''>much</span> <span m=''3044160''>do
  you</span> <span m=''3044240''>have</span> <span m=''3044340''>to</span> <span m=''3044440''>turn</span>
  <span m=''3045040''>to</span> <span m=''3045900''>get</span> <span m=''3046060''>to</span>
  <span m=''3046170''>the</span> <span m=''3046220''>next</span> <span m=''3046480''>edge.</span>
  </p><p><span m=''3047750''>So</span> <span m=''3047970''>we''d</span> <span m=''3048150''>like</span>
  <span m=''3049290''>fairly</span> <span m=''3049640''>obtuse</span> <span m=''3050030''>things.</span>
  <span m=''3050430''>So</span> <span m=''3050640''>alpha</span> <span m=''3050940''>is</span>
  <span m=''3051030''>going</span> <span m=''3051160''>to</span> <span m=''3051220''>be</span>
  <span m=''3051320''>small.</span> <span m=''3051880''>There isn''t</span> <span
  m=''3052200''>a</span> <span m=''3052270''>ton</span> <span m=''3052480''>of</span>
  <span m=''3052570''>turn.</span> <span m=''3053760''>But</span> <span m=''3053860''>in</span>
  <span m=''3053930''>general,</span> <span m=''3054580''>less than</span> <span m=''3054820''>or
  equal to</span> <span m=''3055100''>alpha</span> <span m=''3055430''>chain</span>
  <span m=''3056510''>for</span> <span m=''3056650''>some</span> <span m=''3056870''>alpha.</span>
  <span m=''3057440''>Now</span> <span m=''3057610''>there''s</span> <span m=''3057750''>a</span>
  <span m=''3057820''>relation--</span> <span m=''3058690''>as</span> <span m=''3058870''>Jason
  was</span> <span m=''3059220''>mentioning,</span> <span m=''3059570''>there''s</span>
  <span m=''3059680''>a</span> <span m=''3059730''>relation</span> <span m=''3060070''>between</span>
  <span m=''3060320''>alpha and</span> <span m=''3060710''>beta</span> <span m=''3062060''>in</span>
  <span m=''3062330''>the</span> <span m=''3062550''>ribosome</span> <span m=''3063150''>because</span>
  <span m=''3063320''>you</span> <span m=''3063550''>always</span> <span m=''3063780''>exited</span>
  <span m=''3064170''>orthogonally</span> <span m=''3064970''>to</span> <span m=''3065170''>the</span>
  <span m=''3066160''>plane</span> <span m=''3066710''>that</span> <span m=''3066840''>was</span>
  <span m=''3067010''>your</span> <span m=''3067220''>cone.</span> <span m=''3068730''>The</span>
  <span m=''3069160''>sharpest</span> <span m=''3069630''>angle</span> <span m=''3069850''>you</span>
  <span m=''3069970''>could</span> <span m=''3070080''>get</span> <span m=''3070220''>was</span>
  <span m=''3070420''>90</span> <span m=''3070950''>degree</span> <span m=''3071280''>turn</span>
  <span m=''3071910''>angle.</span> <span m=''3074120''>Here,</span> <span m=''3074670''>we''re</span>
  <span m=''3074870''>a</span> <span m=''3074920''>little</span> <span m=''3075290''>freer</span>
  <span m=''3075790''>because</span> <span m=''3076360''>this</span> <span m=''3076940''>edge</span>
  <span m=''3077310''>can</span> <span m=''3077840''>wiggle</span> <span m=''3078170''>around</span>
  <span m=''3078580''>as</span> <span m=''3078690''>long</span> <span m=''3078930''>as</span>
  <span m=''3079020''>it</span> <span m=''3079120''>touches</span> <span m=''3079390''>the</span>
  <span m=''3079480''>apex.</span> </p><p><span m=''3080950''>So</span> <span m=''3081510''>if</span>
  <span m=''3081800''>you''re</span> <span m=''3082070''>up</span> <span m=''3082250''>against</span>
  <span m=''3082640''>the</span> <span m=''3082740''>cone,</span> <span m=''3084290''>you</span>
  <span m=''3084450''>have to</span> <span m=''3084660''>slide</span> <span m=''3085070''>out</span>
  <span m=''3085220''>into</span> <span m=''3085420''>the</span> <span m=''3085560''>complimentary</span>
  <span m=''3086190''>cone--</span> <span m=''3086430''>that</span> <span m=''3086570''>was</span>
  <span m=''3086770''>the</span> <span m=''3087380''>previous</span> <span m=''3087790''>picture--</span>
  <span m=''3089590''>and</span> <span m=''3089790''>as</span> <span m=''3089870''>soon</span>
  <span m=''3090130''>as</span> <span m=''3090250''>you</span> <span m=''3090380''>get</span>
  <span m=''3090600''>there,</span> <span m=''3091490''>you</span> <span m=''3091620''>could</span>
  <span m=''3091750''>create</span> <span m=''3091990''>a</span> <span m=''3092030''>new</span>
  <span m=''3092230''>edge</span> <span m=''3092410''>which is</span> <span m=''3092670''>like</span>
  <span m=''3092840''>this.</span> <span m=''3094310''>So</span> <span m=''3094460''>the</span>
  <span m=''3094560''>sharpest</span> <span m=''3095030''>angle</span> <span m=''3095300''>you</span>
  <span m=''3095480''>can</span> <span m=''3095650''>get</span> <span m=''3096250''>is</span>
  <span m=''3096470''>actually</span> <span m=''3097150''>twice</span> <span m=''3097650''>beta.</span>
  <span m=''3099110''>In</span> <span m=''3099270''>general,</span> <span m=''3100030''>we''re</span>
  <span m=''3100540''>going</span> <span m=''3100650''>to</span> <span m=''3100700''>have</span>
  <span m=''3102120''>alpha</span> <span m=''3102420''>over</span> <span m=''3102670''>2</span>
  <span m=''3104700''>is</span> <span m=''3104860''>less than</span> <span m=''3104990''>or</span>
  <span m=''3105120''>equal</span> <span m=''3105260''>to</span> <span m=''3105300''>beta.</span>
  <span m=''3105640''>That</span> <span m=''3105840''>is--</span> <span m=''3106190''>you</span>
  <span m=''3106350''>can</span> <span m=''3106460''>get</span> <span m=''3106620''>up</span>
  <span m=''3106790''>to</span> <span m=''3107980''>beta</span> <span m=''3108410''>equals</span>
  <span m=''3108620''>2</span> <span m=''3108820''>alpha.</span> <span m=''3110670''>Get</span>
  <span m=''3111120''>that right.</span> <span m=''3116940''>And</span> <span m=''3117190''>also</span>
  <span m=''3117490''>in</span> <span m=''3117610''>the</span> <span m=''3117740''>obtuse</span>
  <span m=''3118100''>case,</span> <span m=''3118410''>this</span> <span m=''3118580''>is</span>
  <span m=''3118680''>not</span> <span m=''3119040''>too</span> <span m=''3119190''>exciting.</span>
  <span m=''3121300''>But</span> <span m=''3121500''>it''s</span> <span m=''3121660''>true.</span>
  </p><p><span m=''3125650''>There''s</span> <span m=''3125920''>actually</span> <span
  m=''3126210''>some</span> <span m=''3126600''>problems</span> <span m=''3126950''>here.</span>
  <span m=''3127140''>When</span> <span m=''3127350''>you</span> <span m=''3127590''>have</span>
  <span m=''3127880''>that</span> <span m=''3128080''>full</span> <span m=''3128230''>flexibility</span>
  <span m=''3128990''>and</span> <span m=''3129120''>you</span> <span m=''3129300''>set</span>
  <span m=''3131690''>alpha</span> <span m=''3132020''>to</span> <span m=''3132150''>two</span>
  <span m=''3132320''>beta,</span> <span m=''3132730''>not</span> <span m=''3133180''>the</span>
  <span m=''3133270''>other</span> <span m=''3133390''>way</span> <span m=''3133460''>around.</span>
  <span m=''3135760''>I''m</span> <span m=''3135970''>going</span> <span m=''3136170''>to</span>
  <span m=''3136290''>assume</span> <span m=''3136580''>here</span> <span m=''3138290''>that</span>
  <span m=''3139990''>alpha</span> <span m=''3140260''>equals</span> <span m=''3140700''>beta.</span>
  <span m=''3142430''>This will</span> <span m=''3142670''>be</span> <span m=''3143370''>convenient.</span>
  <span m=''3144500''>And it''s</span> <span m=''3144930''>the</span> <span m=''3145080''>interesting</span>
  <span m=''3145490''>case</span> <span m=''3145930''>because,</span> <span m=''3146460''>in</span>
  <span m=''3146620''>reality,</span> <span m=''3147090''>the</span> <span m=''3147200''>cone</span>
  <span m=''3148080''>has</span> <span m=''3148440''>a</span> <span m=''3148490''>half</span>
  <span m=''3148770''>angle</span> <span m=''3149020''>of</span> <span m=''3149140''>90</span>
  <span m=''3149440''>degrees.</span> <span m=''3149860''>So</span> <span m=''3150110''>beta</span>
  <span m=''3150360''>is</span> <span m=''3150510''>90.</span> <span m=''3152110''>And</span>
  <span m=''3152500''>the</span> <span m=''3152600''>sharpest</span> <span m=''3153090''>angle</span>
  <span m=''3153350''>we''re</span> <span m=''3153470''>going</span> <span m=''3153580''>to</span>
  <span m=''3153640''>make</span> <span m=''3153890''>was</span> <span m=''3154060''>always</span>
  <span m=''3154400''>obtuse.</span> <span m=''3155020''>So</span> <span m=''3155680''>saying</span>
  <span m=''3156130''>that</span> <span m=''3156280''>you</span> <span m=''3156400''>have</span>
  <span m=''3156550''>a</span> <span m=''3156600''>less</span> <span m=''3156830''>than</span>
  <span m=''3156930''>or</span> <span m=''3157030''>equal</span> <span m=''3157070''>to</span>
  <span m=''3157150''>90</span> <span m=''3157470''>chain</span> <span m=''3158080''>is</span>
  <span m=''3158260''>just</span> <span m=''3158510''>fine.</span> <span m=''3159510''>But</span>
  <span m=''3160060''>on</span> <span m=''3160160''>the</span> <span m=''3160240''>mathematical</span>
  <span m=''3160750''>side,</span> <span m=''3161440''>I</span> <span m=''3161520''>think</span>
  <span m=''3161670''>we</span> <span m=''3161770''>saw</span> <span m=''3161960''>the</span>
  <span m=''3162090''>case</span> <span m=''3162380''>when</span> <span m=''3162620''>alpha</span>
  <span m=''3162990''>is</span> <span m=''3163140''>less</span> <span m=''3163380''>than</span>
  <span m=''3163480''>or</span> <span m=''3163580''>equal</span> <span m=''3163670''>to</span>
  <span m=''3163730''>beta,</span> <span m=''3166010''>but</span> <span m=''3166400''>not</span>
  <span m=''3167530''>when</span> <span m=''3167650''>alpha</span> <span m=''3167830''>over</span>
  <span m=''3168020''>2</span> <span m=''3168230''>is </span> <span m=''3168470''>less
  than</span> <span m=''3168760''>or equal to</span> <span m=''3168840''>beta.</span>
  <span m=''3169280''>That''s</span> <span m=''3169490''>a</span> <span m=''3169560''>weaker</span>
  <span m=''3169850''>constraint.</span> <span m=''3171520''>So</span> <span m=''3171700''>there</span>
  <span m=''3171880''>is</span> <span m=''3171960''>a</span> <span m=''3172030''>range</span>
  <span m=''3172490''>where</span> <span m=''3172730''>it''s</span> <span m=''3173640''>not</span>
  <span m=''3173850''>so</span> <span m=''3173980''>easy.</span> </p><p><span m=''3178350''>Now,</span>
  <span m=''3178960''>what</span> <span m=''3179150''>do</span> <span m=''3179260''>I</span>
  <span m=''3179350''>claim</span> <span m=''3179650''>about</span> <span m=''3179920''>these</span>
  <span m=''3180110''>chains</span> <span m=''3181080''>other</span> <span m=''3181270''>than</span>
  <span m=''3181540''>their</span> <span m=''3181790''>angles</span> <span m=''3182180''>are</span>
  <span m=''3182250''>not</span> <span m=''3182450''>so</span> <span m=''3182540''>sharp?</span>
  <span m=''3185240''>I</span> <span m=''3185370''>claim</span> <span m=''3185660''>they''re</span>
  <span m=''3185850''>good</span> <span m=''3186680''>algorithms</span> <span m=''3187410''>for</span>
  <span m=''3187730''>folding</span> <span m=''3188190''>them.</span> <span m=''3190580''>What</span>
  <span m=''3190840''>could</span> <span m=''3190990''>I</span> <span m=''3191050''>possibly</span>
  <span m=''3191570''>mean?</span> <span m=''3192450''>There</span> <span m=''3192570''>are</span>
  <span m=''3192630''>still</span> <span m=''3192850''>locked</span> <span m=''3193140''>configurations.</span>
  <span m=''3194690''>Is that</span> <span m=''3195110''>true?</span> <span m=''3196560''>Well,</span>
  <span m=''3199540''>I</span> <span m=''3199590''>mean</span> <span m=''3199770''>presumably--</span>
  <span m=''3201140''>this</span> <span m=''3201330''>is</span> <span m=''3201440''>acute--</span>
  <span m=''3202010''>but</span> <span m=''3202600''>you</span> <span m=''3202740''>take</span>
  <span m=''3203130''>the</span> <span m=''3203440''>obtuse</span> <span m=''3203940''>versions</span>
  <span m=''3204830''>of</span> <span m=''3204950''>this</span> <span m=''3205180''>guy.</span>
  <span m=''3205930''>Because</span> <span m=''3206100''>I</span> <span m=''3206150''>didn''t</span>
  <span m=''3206360''>constrain</span> <span m=''3206690''>the</span> <span m=''3206800''>edge</span>
  <span m=''3206980''>lengths</span> <span m=''3207200''>or</span> <span m=''3207280''>anything,</span>
  <span m=''3207600''>I</span> <span m=''3207660''>just</span> <span m=''3207820''>said</span>
  <span m=''3208040''>that</span> <span m=''3209130''>the</span> <span m=''3209280''>angles</span>
  <span m=''3209600''>are</span> <span m=''3209690''>obtuse.</span> </p><p><span m=''3210640''>So</span>
  <span m=''3210760''>I</span> <span m=''3210860''>could</span> <span m=''3211010''>just</span>
  <span m=''3211140''>sort</span> <span m=''3211290''>of</span> <span m=''3211350''>round</span>
  <span m=''3211620''>these</span> <span m=''3211770''>corners,</span> <span m=''3212760''>make</span>
  <span m=''3213090''>it</span> <span m=''3213320''>obtuse.</span> <span m=''3213540''>You
  know, add</span> <span m=''3213830''>lots</span> <span m=''3214070''>of</span> <span
  m=''3214130''>dots</span> <span m=''3214620''>just</span> <span m=''3214830''>at</span>
  <span m=''3214900''>the</span> <span m=''3214990''>corners</span> <span m=''3216050''>that</span>
  <span m=''3216230''>would</span> <span m=''3216340''>be</span> <span m=''3216450''>obtuse.</span>
  <span m=''3217360''>And</span> <span m=''3218690''>a</span> <span m=''3218800''>chain</span>
  <span m=''3219210''>like</span> <span m=''3219650''>this</span> <span m=''3219970''>will</span>
  <span m=''3220100''>be</span> <span m=''3220250''>producible.</span> <span m=''3220900''>A
  chain</span> <span m=''3221230''>with</span> <span m=''3221410''>these</span> <span
  m=''3221620''>angles</span> <span m=''3222010''>and</span> <span m=''3222090''>these</span>
  <span m=''3222280''>edge</span> <span m=''3222480''>lengths</span> <span m=''3223190''>can</span>
  <span m=''3223440''>be</span> <span m=''3223570''>produced</span> <span m=''3224050''>from</span>
  <span m=''3224220''>a</span> <span m=''3224290''>cone.</span> <span m=''3225040''>But</span>
  <span m=''3226180''>this</span> <span m=''3226540''>configuration</span> <span m=''3227370''>of</span>
  <span m=''3227480''>this</span> <span m=''3227640''>chain</span> <span m=''3228340''>cannot</span>
  <span m=''3228720''>be</span> <span m=''3228840''>produced,</span> <span m=''3229700''>I</span>
  <span m=''3229840''>claim.</span> <span m=''3230760''>I</span> <span m=''3230900''>claim</span>
  <span m=''3231260''>anything</span> <span m=''3231720''>that</span> <span m=''3231800''>can</span>
  <span m=''3231990''>be</span> <span m=''3232150''>produced</span> <span m=''3233760''>is</span>
  <span m=''3234010''>in</span> <span m=''3234230''>one</span> <span m=''3234510''>connected</span>
  <span m=''3234900''>component.</span> <span m=''3236600''>So</span> <span m=''3236750''>while</span>
  <span m=''3237070''>I</span> <span m=''3237170''>can</span> <span m=''3237320''>make</span>
  <span m=''3237520''>a</span> <span m=''3237580''>linkage</span> <span m=''3238030''>that</span>
  <span m=''3238180''>is</span> <span m=''3238380''>locked</span> <span m=''3238930''>and</span>
  <span m=''3239040''>that</span> <span m=''3239190''>there</span> <span m=''3239320''>are</span>
  <span m=''3239400''>bad</span> <span m=''3239800''>configurations</span> <span m=''3240480''>you</span>
  <span m=''3240600''>can''t</span> <span m=''3240810''>get</span> <span m=''3240940''>out</span>
  <span m=''3241140''>of,</span> <span m=''3241740''>the</span> <span m=''3241840''>things</span>
  <span m=''3242040''>you</span> <span m=''3242150''>can</span> <span m=''3242250''>actually</span>
  <span m=''3242550''>make,</span> <span m=''3243080''>you</span> <span m=''3243270''>can</span>
  <span m=''3243410''>always</span> <span m=''3243730''>get</span> <span m=''3243870''>out</span>
  <span m=''3244180''>of.</span> </p><p><span m=''3245220''>So</span> <span m=''3245360''>there''s</span>
  <span m=''3245530''>going</span> <span m=''3245680''>to</span> <span m=''3245770''>be</span>
  <span m=''3246950''>the</span> <span m=''3247100''>space</span> <span m=''3247520''>of</span>
  <span m=''3247730''>producible</span> <span m=''3249480''>configurations.</span>
  <span m=''3253500''>Maybe</span> <span m=''3253790''>there''s</span> <span m=''3253970''>some</span>
  <span m=''3254100''>stuff</span> <span m=''3254350''>that''s</span> <span m=''3254520''>unproducible</span>
  <span m=''3255200''>but</span> <span m=''3255340''>still</span> <span m=''3255530''>connected</span>
  <span m=''3255900''>to</span> <span m=''3256040''>it.</span> <span m=''3256800''>I</span>
  <span m=''3256970''>don''t</span> <span m=''3257100''>know.</span> <span m=''3257690''>It</span>
  <span m=''3257730''>doesn''t</span> <span m=''3257910''>matter</span> <span m=''3258150''>too</span>
  <span m=''3258270''>much.</span> <span m=''3258550''>I</span> <span m=''3258590''>won''t</span>
  <span m=''3258780''>worry</span> <span m=''3258970''>about</span> <span m=''3259210''>this</span>
  <span m=''3259320''>stuff.</span> <span m=''3260460''>There''s</span> <span m=''3260710''>other</span>
  <span m=''3260980''>bad</span> <span m=''3261550''>locked</span> <span m=''3261890''>configurations</span>
  <span m=''3263290''>that</span> <span m=''3263650''>cannot</span> <span m=''3264450''>reach</span>
  <span m=''3264700''>here.</span> <span m=''3265330''>But</span> <span m=''3265550''>everything</span>
  <span m=''3265990''>that''s</span> <span m=''3266140''>producible</span> <span m=''3266420''>is</span>
  <span m=''3266700''>in</span> <span m=''3266900''>one</span> <span m=''3267160''>connected</span>
  <span m=''3267530''>component</span> <span m=''3268000''>of</span> <span m=''3268160''>the</span>
  <span m=''3268250''>configuration</span> <span m=''3268840''>space.</span> <span
  m=''3269510''>That''s</span> <span m=''3269760''>property</span> <span m=''3270150''>one.</span>
  <span m=''3270800''>That''s</span> <span m=''3270960''>kind</span> <span m=''3271110''>of</span>
  <span m=''3271180''>nice.</span> <span m=''3272420''>Also,</span> <span m=''3273870''>all</span>
  <span m=''3274040''>the</span> <span m=''3274110''>flat</span> <span m=''3274410''>states</span>
  <span m=''3274690''>are</span> <span m=''3274750''>going</span> <span m=''3274880''>to</span>
  <span m=''3274930''>be</span> <span m=''3275080''>in</span> <span m=''3275140''>here.</span>
  <span m=''3277130''>This</span> <span m=''3277220''>is</span> <span m=''3277340''>actually</span>
  <span m=''3277630''>pretty</span> <span m=''3277830''>easy.</span> <span m=''3278120''>I</span>
  <span m=''3278160''>just</span> <span m=''3278360''>need</span> <span m=''3278480''>to</span>
  <span m=''3278540''>prove</span> <span m=''3278730''>that</span> <span m=''3278820''>flat</span>
  <span m=''3279100''>states</span> <span m=''3279340''>are</span> <span m=''3279480''>producible,</span>
  <span m=''3280570''>which</span> <span m=''3280790''>we''ll</span> <span m=''3280970''>worry</span>
  <span m=''3281140''>about</span> <span m=''3281340''>later.</span> </p><p><span
  m=''3282320''>So</span> <span m=''3282640''>in</span> <span m=''3282780''>particular,</span>
  <span m=''3283290''>these</span> <span m=''3283550''>guys</span> <span m=''3283810''>are</span>
  <span m=''3283910''>flat</span> <span m=''3284180''>state</span> <span m=''3284330''>connected.</span>
  <span m=''3285930''>All</span> <span m=''3286180''>the</span> <span m=''3286280''>producible</span>
  <span m=''3286870''>protein</span> <span m=''3287290''>chains</span> <span m=''3287740''>are</span>
  <span m=''3287870''>flat</span> <span m=''3288130''>state</span> <span m=''3288280''>connected.</span>
  <span m=''3289500''>That''s</span> <span m=''3289680''>interesting</span> <span
  m=''3290090''>because</span> <span m=''3290260''>we</span> <span m=''3290370''>don''t</span>
  <span m=''3290510''>even</span> <span m=''3290690''>know</span> <span m=''3290820''>that</span>
  <span m=''3290930''>all</span> <span m=''3291080''>chains</span> <span m=''3291560''>are</span>
  <span m=''3291640''>flat</span> <span m=''3291910''>state</span> <span m=''3292070''>connected.</span>
  <span m=''3293060''>But</span> <span m=''3293180''>here--</span> <span m=''3294360''>I</span>
  <span m=''3294550''>guess</span> <span m=''3294710''>we</span> <span m=''3294820''>know</span>
  <span m=''3294930''>that</span> <span m=''3295050''>obtuse</span> <span m=''3295350''>chains</span>
  <span m=''3295650''>are</span> <span m=''3295730''>flat state</span> <span m=''3296160''>connected,</span>
  <span m=''3297510''>so</span> <span m=''3299450''>maybe</span> <span m=''3299750''>it''s</span>
  <span m=''3299870''>not</span> <span m=''3300040''>so</span> <span m=''3300380''>surprising.</span>
  <span m=''3301350''>But</span> <span m=''3302040''>what''s</span> <span m=''3302240''>important</span>
  <span m=''3302560''>is</span> <span m=''3302670''>not</span> <span m=''3302850''>only</span>
  <span m=''3303060''>are the</span> <span m=''3303160''>flat</span> <span m=''3303460''>states</span>
  <span m=''3303610''>connected</span> <span m=''3303940''>to</span> <span m=''3304030''>each</span>
  <span m=''3304190''>other</span> <span m=''3304440''>and</span> <span m=''3304690''>the</span>
  <span m=''3304780''>producible</span> <span m=''3305240''>states</span> <span m=''3305520''>are</span>
  <span m=''3305630''>connected</span> <span m=''3305980''>to</span> <span m=''3306050''>each</span>
  <span m=''3306190''>other,</span> <span m=''3306760''>but</span> <span m=''3306980''>producible</span>
  <span m=''3307245''>is</span> <span m=''3307510''>connected</span> <span m=''3307860''>to</span>
  <span m=''3308490''>flat</span> <span m=''3308820''>states.</span> <span m=''3309170''>Everything</span>
  <span m=''3309660''>is</span> <span m=''3309830''>together</span> <span m=''3310170''>here.</span>
  <span m=''3313020''>I</span> <span m=''3313100''>might</span> <span m=''3313250''>have</span>
  <span m=''3313390''>more</span> <span m=''3313570''>properties.</span> <span m=''3314120''>But</span>
  <span m=''3314250''>that''s</span> <span m=''3314460''>already</span> <span m=''3314680''>some</span>
  <span m=''3314860''>good</span> <span m=''3315030''>news.</span> <span m=''3315220''>And</span>
  <span m=''3315300''>there''s</span> <span m=''3315430''>algorithms</span> <span
  m=''3315890''>to</span> <span m=''3316000''>do</span> <span m=''3316110''>all</span>
  <span m=''3316330''>of</span> <span m=''3316400''>this.</span> </p><p><span m=''3319160''>How</span>
  <span m=''3319450''>do</span> <span m=''3319530''>we</span> <span m=''3319670''>prove</span>
  <span m=''3319960''>it?</span> <span m=''3321890''>Well,</span> <span m=''3328490''>as</span>
  <span m=''3328680''>usual</span> <span m=''3329030''>we</span> <span m=''3329180''>use</span>
  <span m=''3329460''>the</span> <span m=''3329570''>FedEx</span> <span m=''3329940''>method.</span>
  <span m=''3331890''>And</span> <span m=''3332170''>in</span> <span m=''3332460''>some</span>
  <span m=''3332680''>sense,</span> <span m=''3332950''>one</span> <span m=''3333160''>of</span>
  <span m=''3333250''>the</span> <span m=''3333560''>challenges</span> <span m=''3334690''>is</span>
  <span m=''3338760''>what</span> <span m=''3339080''>is</span> <span m=''3339360''>the</span>
  <span m=''3339450''>natural</span> <span m=''3339870''>canonical</span> <span m=''3340370''>state</span>
  <span m=''3341410''>for</span> <span m=''3343180''>protein</span> <span m=''3343640''>chains?</span>
  <span m=''3346050''>In</span> <span m=''3346200''>fact,</span> <span m=''3346430''>we''re</span>
  <span m=''3346580''>just</span> <span m=''3346770''>going</span> <span m=''3346880''>to</span>
  <span m=''3346940''>assume</span> <span m=''3347410''>that</span> <span m=''3347740''>our</span>
  <span m=''3347960''>chain</span> <span m=''3348390''>is--</span> <span m=''3350650''>in</span>
  <span m=''3351000''>reality,</span> <span m=''3351460''>we''re</span> <span m=''3351540''>going</span>
  <span m=''3351650''>to</span> <span m=''3351690''>assume</span> <span m=''3351970''>that</span>
  <span m=''3352100''>it''s</span> <span m=''3352300''>an</span> <span m=''3352360''>orthogonal</span>
  <span m=''3352880''>chain--</span> <span m=''3353600''>an</span> <span m=''3353730''>obtuse</span>
  <span m=''3354470''>chain,</span> <span m=''3354990''>I</span> <span m=''3355040''>should</span>
  <span m=''3355250''>say.</span> <span m=''3356080''>But</span> <span m=''3356190''>in</span>
  <span m=''3356280''>general,</span> <span m=''3357180''>for</span> <span m=''3357470''>any</span>
  <span m=''3358150''>less than</span> <span m=''3358440''>or equal to</span> <span
  m=''3358680''>alpha</span> <span m=''3359040''>chain,</span> <span m=''3359660''>for</span>
  <span m=''3359890''>whatever</span> <span m=''3360210''>alpha</span> <span m=''3360510''>you</span>
  <span m=''3360670''>like--</span> <span m=''3361080''>and</span> <span m=''3361240''>it</span>
  <span m=''3361300''>will</span> <span m=''3361520''>be</span> <span m=''3361810''>the</span>
  <span m=''3361940''>half</span> <span m=''3362230''>angle</span> <span m=''3362500''>of</span>
  <span m=''3362590''>the</span> <span m=''3362690''>cone,</span> <span m=''3363510''>so</span>
  <span m=''3363670''>alpha</span> <span m=''3363840''>equals</span> <span m=''3364220''>beta--</span>
  <span m=''3367200''>we</span> <span m=''3367400''>will</span> <span m=''3367580''>define</span>
  <span m=''3368050''>a</span> <span m=''3368170''>canonical</span> <span m=''3368770''>configuration.</span>
  <span m=''3382010''>I</span> <span m=''3382030''>think</span> <span m=''3382220''>we</span>
  <span m=''3382310''>called</span> <span m=''3382570''>it</span> <span m=''3382710''>the</span>
  <span m=''3382990''>alpha</span> <span m=''3383370''>CCC.</span> </p><p><span m=''3388060''>So</span>
  <span m=''3390550''>it''s</span> <span m=''3390700''>going</span> <span m=''3390810''>to</span>
  <span m=''3390870''>be</span> <span m=''3390970''>kind</span> <span m=''3391220''>of</span>
  <span m=''3391290''>like</span> <span m=''3391480''>a</span> <span m=''3391540''>helix.</span>
  <span m=''3392440''>I</span> <span m=''3392620''>think</span> <span m=''3392790''>I</span>
  <span m=''3392820''>have</span> <span m=''3393000''>an</span> <span m=''3393310''>example,</span>
  <span m=''3394670''>an</span> <span m=''3394840''>actual</span> <span m=''3395210''>computed</span>
  <span m=''3395680''>example.</span> <span m=''3396910''>That''s</span> <span m=''3397140''>not</span>
  <span m=''3397300''>the</span> <span m=''3397380''>best</span> <span m=''3397700''>picture</span>
  <span m=''3398040''>because</span> <span m=''3398170''>you</span> <span m=''3398280''>can''t</span>
  <span m=''3398470''>see</span> <span m=''3398600''>everything</span> <span m=''3398880''>that''s</span>
  <span m=''3399040''>going</span> <span m=''3399290''>on.</span> <span m=''3399520''>But</span>
  <span m=''3399710''>this</span> <span m=''3400370''>is</span> <span m=''3400570''>an</span>
  <span m=''3400700''>actual</span> <span m=''3401510''>canonical</span> <span m=''3401930''>configuration</span>
  <span m=''3402510''>of</span> <span m=''3402620''>a</span> <span m=''3402690''>particular</span>
  <span m=''3403690''>chain.</span> <span m=''3407980''>Let</span> <span m=''3408100''>me</span>
  <span m=''3408220''>tell</span> <span m=''3408370''>you</span> <span m=''3408470''>how</span>
  <span m=''3408640''>it</span> <span m=''3408700''>works</span> <span m=''3408950''>in</span>
  <span m=''3409050''>general.</span> <span m=''3410410''>So</span> <span m=''3410450''>in</span>
  <span m=''3410510''>general,</span> <span m=''3410870''>we</span> <span m=''3410890''>have</span>
  <span m=''3411180''>some</span> <span m=''3412510''>chain,</span> <span m=''3412930''>v1,</span>
  <span m=''3413520''>v2--</span> <span m=''3414660''>sorry,</span> <span m=''3414990''>starting</span>
  <span m=''3415320''>at</span> <span m=''3415420''>v0,</span> <span m=''3415990''>v1,</span>
  <span m=''3416320''>v2.</span> <span m=''3418560''>I</span> <span m=''3418650''>want</span>
  <span m=''3418820''>to</span> <span m=''3418890''>define</span> <span m=''3419270''>a</span>
  <span m=''3419660''>canonical--</span> <span m=''3420120''>and</span> <span m=''3420220''>there''s</span>
  <span m=''3420470''>defined</span> <span m=''3420940''>lengths</span> <span m=''3421260''>between</span>
  <span m=''3421580''>the</span> <span m=''3421680''>two.</span> <span m=''3422310''>And</span>
  <span m=''3422530''>there''s</span> <span m=''3422680''>defined</span> <span m=''3423050''>angles</span>
  <span m=''3423660''>between</span> <span m=''3424010''>every</span> <span m=''3424260''>triple</span>
  <span m=''3425540''>in</span> <span m=''3425790''>sequence.</span> </p><p><span
  m=''3428240''>So</span> <span m=''3428500''>I''m</span> <span m=''3428680''>going</span>
  <span m=''3428790''>to</span> <span m=''3428860''>start</span> <span m=''3429150''>with</span>
  <span m=''3429310''>v0</span> <span m=''3429780''>somewhere.</span> <span m=''3431190''>Doesn''t</span>
  <span m=''3431400''>really</span> <span m=''3431580''>matter</span> <span m=''3431860''>by</span>
  <span m=''3432010''>translation.</span> <span m=''3432620''>Say,</span> <span m=''3432790''>the</span>
  <span m=''3432900''>origin</span> <span m=''3433350''>of</span> <span m=''3433590''>space.</span>
  <span m=''3435870''>And</span> <span m=''3438950''>what</span> <span m=''3439280''>I''m</span>
  <span m=''3439400''>going</span> <span m=''3439630''>to</span> <span m=''3439760''>do</span>
  <span m=''3440670''>is</span> <span m=''3440920''>draw</span> <span m=''3441280''>a</span>
  <span m=''3441380''>cone</span> <span m=''3444800''>whose</span> <span m=''3445010''>apex</span>
  <span m=''3445440''>is</span> <span m=''3445570''>that</span> <span m=''3445780''>v0.</span>
  <span m=''3447460''>And</span> <span m=''3447810''>the</span> <span m=''3447980''>half</span>
  <span m=''3448310''>angle</span> <span m=''3451030''>here</span> <span m=''3451570''>is</span>
  <span m=''3451800''>going</span> <span m=''3451910''>to</span> <span m=''3451980''>be</span>
  <span m=''3452130''>alpha</span> <span m=''3452480''>over</span> <span m=''3452710''>two,</span>
  <span m=''3453410''>not</span> <span m=''3453670''>alpha.</span> <span m=''3454710''>This</span>
  <span m=''3454850''>is</span> <span m=''3454990''>a</span> <span m=''3455080''>smaller</span>
  <span m=''3455600''>cone</span> <span m=''3455930''>than--</span> <span m=''3456500''>by</span>
  <span m=''3456690''>a</span> <span m=''3456750''>factor</span> <span m=''3457080''>of</span>
  <span m=''3457160''>two--</span> <span m=''3458000''>than</span> <span m=''3458270''>the</span>
  <span m=''3458990''>ribosome.</span> <span m=''3460160''>That''s</span> <span m=''3460370''>important.</span>
  <span m=''3462370''>So</span> <span m=''3462650''>there''s</span> <span m=''3462970''>this</span>
  <span m=''3463760''>vertical</span> <span m=''3464240''>line.</span> <span m=''3465730''>And</span>
  <span m=''3466170''>to</span> <span m=''3466320''>pick</span> <span m=''3466640''>v1,</span>
  <span m=''3467050''>I''m</span> <span m=''3467120''>just</span> <span m=''3467290''>going</span>
  <span m=''3467400''>to</span> <span m=''3468180''>use</span> <span m=''3468980''>the</span>
  <span m=''3469140''>right</span> <span m=''3469400''>edge,</span> <span m=''3469870''>which</span>
  <span m=''3470080''>is--</span> <span m=''3471270''>let''s</span> <span m=''3471320''>say</span>
  <span m=''3471420''>this</span> <span m=''3471640''>is</span> <span m=''3471770''>the</span>
  <span m=''3471940''>x</span> <span m=''3472230''>direction.</span> </p><p><span
  m=''3472960''>This</span> <span m=''3473100''>is</span> <span m=''3473360''>the</span>
  <span m=''3473500''>z</span> <span m=''3473720''>direction.</span> <span m=''3474610''>Maximum</span>
  <span m=''3475100''>x-coordinate.</span> <span m=''3476960''>It''s</span> <span
  m=''3477090''>going</span> <span m=''3477180''>to</span> <span m=''3477240''>lie</span>
  <span m=''3477480''>on</span> <span m=''3477560''>the</span> <span m=''3477640''>cone,</span>
  <span m=''3478010''>maximum</span> <span m=''3478390''>x-coordinate.</span> <span
  m=''3478860''>That''s</span> <span m=''3479150''>v1.</span> <span m=''3480420''>Now,</span>
  <span m=''3480810''>v1--</span> <span m=''3482520''>let</span> <span m=''3482590''>me</span>
  <span m=''3483670''>redraw</span> <span m=''3484010''>this</span> <span m=''3484200''>picture</span>
  <span m=''3484470''>a</span> <span m=''3484530''>little</span> <span m=''3484730''>lower.</span>
  <span m=''3485560''>So</span> <span m=''3485770''>there</span> <span m=''3486060''>was</span>
  <span m=''3487790''>v0,</span> <span m=''3489500''>v1.</span> <span m=''3490640''>Now</span>
  <span m=''3490750''>I</span> <span m=''3490820''>want</span> <span m=''3490990''>to</span>
  <span m=''3491040''>draw</span> <span m=''3491220''>v2,</span> <span m=''3491550''>and</span>
  <span m=''3491880''>I</span> <span m=''3492030''>want</span> <span m=''3492210''>to</span>
  <span m=''3492260''>draw</span> <span m=''3492410''>it</span> <span m=''3492470''>above.</span>
  <span m=''3495390''>So</span> <span m=''3495500''>what</span> <span m=''3495620''>I''ll</span>
  <span m=''3495740''>do</span> <span m=''3496540''>is</span> <span m=''3496810''>draw</span>
  <span m=''3497530''>a</span> <span m=''3497590''>vertical</span> <span m=''3497960''>column</span>
  <span m=''3500960''>whose</span> <span m=''3501260''>half</span> <span m=''3501640''>angle</span>
  <span m=''3501940''>here</span> <span m=''3503090''>is</span> <span m=''3503420''>alpha</span>
  <span m=''3503680''>over</span> <span m=''3503880''>two.</span> <span m=''3507270''>I</span>
  <span m=''3507340''>want</span> <span m=''3507530''>to</span> <span m=''3507580''>draw</span>
  <span m=''3507770''>v2</span> <span m=''3508170''>on</span> <span m=''3508360''>the</span>
  <span m=''3508440''>cone</span> <span m=''3508770''>here.</span> <span m=''3509290''>Of</span>
  <span m=''3509450''>course,</span> <span m=''3509670''>the</span> <span m=''3510000''>height</span>
  <span m=''3510250''>of</span> <span m=''3510360''>the</span> <span m=''3510450''>cone</span>
  <span m=''3510780''>is</span> <span m=''3510900''>the</span> <span m=''3510990''>length</span>
  <span m=''3511230''>of</span> <span m=''3511310''>the</span> <span m=''3511420''>edge,</span>
  <span m=''3512340''>not</span> <span m=''3512490''>the</span> <span m=''3512570''>height.</span>
  <span m=''3515200''>You</span> <span m=''3515380''>could</span> <span m=''3515480''>think</span>
  <span m=''3515630''>of</span> <span m=''3515690''>the</span> <span m=''3515780''>cone</span>
  <span m=''3515980''>as</span> <span m=''3516080''>infinite.</span> </p><p><span
  m=''3516870''>And</span> <span m=''3517090''>then</span> <span m=''3517210''>I</span>
  <span m=''3517730''>just</span> <span m=''3517920''>clip</span> <span m=''3518140''>this</span>
  <span m=''3518420''>to</span> <span m=''3518550''>when</span> <span m=''3518690''>it</span>
  <span m=''3518730''>has</span> <span m=''3518900''>the</span> <span m=''3518990''>right</span>
  <span m=''3519170''>length.</span> <span m=''3520240''>So</span> <span m=''3520390''>again,</span>
  <span m=''3521100''>this</span> <span m=''3521270''>might</span> <span m=''3521500''>be</span>
  <span m=''3521650''>a</span> <span m=''3521700''>different</span> <span m=''3522000''>height</span>
  <span m=''3522240''>cone.</span> <span m=''3522970''>I</span> <span m=''3523180''>clip</span>
  <span m=''3523470''>it</span> <span m=''3523610''>to</span> <span m=''3523710''>whatever</span>
  <span m=''3524070''>the</span> <span m=''3524180''>length</span> <span m=''3524470''>v1,</span>
  <span m=''3524900''>v2</span> <span m=''3525150''>is.</span> <span m=''3525470''>I</span>
  <span m=''3525600''>want</span> <span m=''3525880''>it to</span> <span m=''3525950''>be</span>
  <span m=''3526040''>somewhere</span> <span m=''3526420''>on</span> <span m=''3526500''>this</span>
  <span m=''3526670''>cone,</span> <span m=''3528040''>but</span> <span m=''3528240''>now</span>
  <span m=''3528430''>I''m</span> <span m=''3528580''>constrained</span> <span m=''3529070''>to</span>
  <span m=''3529120''>have</span> <span m=''3529310''>the</span> <span m=''3529410''>correct</span>
  <span m=''3529850''>angle</span> <span m=''3530140''>at</span> <span m=''3530410''>v1.</span>
  <span m=''3531070''>I</span> <span m=''3531150''>can''t</span> <span m=''3531430''>just</span>
  <span m=''3531610''>put</span> <span m=''3531770''>it</span> <span m=''3531860''>over</span>
  <span m=''3532100''>here,</span> <span m=''3532870''>because</span> <span m=''3532960''>then</span>
  <span m=''3533100''>the</span> <span m=''3533200''>angle</span> <span m=''3533410''>here</span>
  <span m=''3533550''>would</span> <span m=''3533640''>be</span> <span m=''3533760''>180.</span>
  <span m=''3534430''>Presumably,</span> <span m=''3535060''>I</span> <span m=''3535080''>don''t</span>
  <span m=''3535240''>want</span> <span m=''3535400''>to</span> <span m=''3535450''>make
  a</span> <span m=''3535620''>180</span> <span m=''3536100''>degree</span> <span
  m=''3536340''>angle.</span> <span m=''3537630''>So</span> <span m=''3537840''>in</span>
  <span m=''3537910''>reality,</span> <span m=''3538440''>what</span> <span m=''3538580''>happens</span>
  <span m=''3539010''>is</span> <span m=''3539230''>that</span> <span m=''3539390''>there''s</span>
  <span m=''3539570''>a</span> <span m=''3539670''>cone</span> <span m=''3540620''>which</span>
  <span m=''3540950''>is--</span> <span m=''3546000''>whose</span> <span m=''3546770''>axis</span>
  <span m=''3547930''>is</span> <span m=''3548170''>the</span> <span m=''3548280''>edge</span>
  <span m=''3548690''>v0,</span> <span m=''3548940''>v1.</span> <span m=''3549580''>So
  I</span> <span m=''3549710''>extend</span> <span m=''3550220''>v0</span> <span m=''3550710''>v1</span>
  <span m=''3551860''>out</span> <span m=''3552160''>here,</span> <span m=''3552710''>which,</span>
  <span m=''3552910''>in</span> <span m=''3553020''>this</span> <span m=''3553190''>case,</span>
  <span m=''3553400''>happens</span> <span m=''3553760''>to</span> <span m=''3553880''>lie</span>
  <span m=''3554090''>here.</span> <span m=''3555410''>And</span> <span m=''3555710''>I</span>
  <span m=''3555730''>make</span> <span m=''3555960''>a</span> <span m=''3556050''>cone</span>
  <span m=''3556320''>like</span> <span m=''3556520''>that.</span> <span m=''3559210''>Let</span>
  <span m=''3559300''>me</span> <span m=''3559430''>draw</span> <span m=''3559630''>it</span>
  <span m=''3559760''>slightly</span> <span m=''3560030''>more</span> <span m=''3560220''>accurately.</span>
  </p><p><span m=''3566810''>In</span> <span m=''3567060''>this</span> <span m=''3567210''>case,</span>
  <span m=''3567570''>the</span> <span m=''3569050''>center</span> <span m=''3570880''>axis</span>
  <span m=''3571310''>of</span> <span m=''3571420''>the</span> <span m=''3571530''>cone</span>
  <span m=''3572550''>would</span> <span m=''3572800''>go</span> <span m=''3573000''>right</span>
  <span m=''3573190''>here,</span> <span m=''3573390''>whatever</span> <span m=''3573660''>the</span>
  <span m=''3573750''>extension</span> <span m=''3574290''>of</span> <span m=''3574420''>v0,</span>
  <span m=''3574800''>v1</span> <span m=''3575120''>was.</span> <span m=''3577990''>And</span>
  <span m=''3580280''>to</span> <span m=''3580990''>have</span> <span m=''3581180''>the</span>
  <span m=''3581290''>right</span> <span m=''3581500''>angle</span> <span m=''3581770''>at</span>
  <span m=''3581850''>v1,</span> <span m=''3582610''>v2</span> <span m=''3582960''>must</span>
  <span m=''3583360''>be</span> <span m=''3583550''>on</span> <span m=''3583740''>that</span>
  <span m=''3583970''>cone.</span> <span m=''3585210''>Conveniently,</span> <span
  m=''3585890''>there</span> <span m=''3586100''>are</span> <span m=''3586250''>two</span>
  <span m=''3586430''>intersection</span> <span m=''3586950''>points</span> <span
  m=''3587510''>between</span> <span m=''3587820''>those</span> <span m=''3588000''>two</span>
  <span m=''3588120''>cones.</span> <span m=''3589300''>I</span> <span m=''3589400''>could</span>
  <span m=''3589440''>choose</span> <span m=''3589640''>either</span> <span m=''3589970''>one</span>
  <span m=''3590140''>of</span> <span m=''3590240''>them</span> <span m=''3590400''>to</span>
  <span m=''3590520''>be</span> <span m=''3590690''>v2.</span> <span m=''3592240''>And</span>
  <span m=''3592380''>I</span> <span m=''3592490''>will</span> <span m=''3592650''>choose</span>
  <span m=''3593120''>the</span> <span m=''3594060''>counterclockwise</span> <span
  m=''3594960''>most</span> <span m=''3595370''>one,</span> <span m=''3596300''>which</span>
  <span m=''3596610''>is</span> <span m=''3596930''>this</span> <span m=''3597160''>one.</span>
  <span m=''3598560''>This</span> <span m=''3598760''>is</span> <span m=''3598870''>going</span>
  <span m=''3599020''>to</span> <span m=''3599080''>be</span> <span m=''3599180''>v2.</span>
  <span m=''3600692''>So I</span> <span m=''3601190''>draw</span> <span m=''3601470''>that</span>
  <span m=''3601680''>edge.</span> <span m=''3603880''>Now</span> <span m=''3604950''>I</span>
  <span m=''3605060''>repeat.</span> </p><p><span m=''3606090''>So</span> <span m=''3606270''>for</span>
  <span m=''3606420''>v2,</span> <span m=''3607230''>I''m</span> <span m=''3607350''>going</span>
  <span m=''3607440''>to</span> <span m=''3607510''>draw</span> <span m=''3607670''>a</span>
  <span m=''3607700''>vertical</span> <span m=''3608140''>cone</span> <span m=''3608910''>whose</span>
  <span m=''3609130''>half</span> <span m=''3609400''>angle--</span> <span m=''3609970''>here,</span>
  <span m=''3610180''>the</span> <span m=''3610270''>half</span> <span m=''3610520''>angle</span>
  <span m=''3610800''>is</span> <span m=''3610900''>always</span> <span m=''3611110''>alpha</span>
  <span m=''3611420''>over</span> <span m=''3611640''>two.</span> <span m=''3612940''>Half</span>
  <span m=''3613030''>angle</span> <span m=''3613330''>is</span> <span m=''3613440''>alpha</span>
  <span m=''3613840''>over</span> <span m=''3613950''>two.</span> <span m=''3614930''>This</span>
  <span m=''3615380''>cone</span> <span m=''3617880''>had</span> <span m=''3621150''>half</span>
  <span m=''3621470''>angle,</span> <span m=''3622170''>whatever</span> <span m=''3622520''>the</span>
  <span m=''3622660''>angle</span> <span m=''3623960''>v0,</span> <span m=''3624280''>v1,</span>
  <span m=''3624920''>v2</span> <span m=''3626070''>was.</span> <span m=''3627840''>Was
  that</span> <span m=''3627960''>the</span> <span m=''3628060''>half</span> <span
  m=''3628360''>angle</span> <span m=''3628590''>or</span> <span m=''3629130''>angle?</span>
  <span m=''3629460''>The half</span> <span m=''3629790''>angle.</span> <span m=''3630810''>I
  think this is</span> <span m=''3631160''>right.</span> <span m=''3634080''>OK.</span>
  <span m=''3636110''>And</span> <span m=''3636370''>then I</span> <span m=''3636450''>take</span>
  <span m=''3636630''>the</span> <span m=''3636740''>intersection</span> <span m=''3637260''>of</span>
  <span m=''3637340''>those</span> <span m=''3637520''>two</span> <span m=''3637640''>cones,</span>
  <span m=''3638910''>and</span> <span m=''3639760''>that</span> <span m=''3639960''>will</span>
  <span m=''3640070''>give</span> <span m=''3640220''>me</span> <span m=''3640380''>where</span>
  <span m=''3640660''>v3</span> <span m=''3641040''>is.</span> </p><p><span m=''3641750''>So</span>
  <span m=''3641920''>I do</span> <span m=''3642040''>the</span> <span m=''3642170''>same</span>
  <span m=''3642420''>thing</span> <span m=''3642680''>for</span> <span m=''3642780''>v2,</span>
  <span m=''3643260''>for v3,</span> <span m=''3643840''>and</span> <span m=''3643950''>so</span>
  <span m=''3644100''>on.</span> <span m=''3645040''>I</span> <span m=''3645140''>have</span>
  <span m=''3645300''>a</span> <span m=''3645340''>unique</span> <span m=''3645630''>choice</span>
  <span m=''3645990''>at</span> <span m=''3646060''>every</span> <span m=''3646330''>moment.</span>
  <span m=''3650400''>Yeah,</span> <span m=''3650780''>basically.</span> <span m=''3652890''>And</span>
  <span m=''3653130''>the</span> <span m=''3653540''>only</span> <span m=''3653730''>exception</span>
  <span m=''3654120''>was</span> <span m=''3654250''>at</span> <span m=''3654350''>the</span>
  <span m=''3654430''>beginning</span> <span m=''3654810''>here,</span> <span m=''3655000''>when</span>
  <span m=''3655140''>I</span> <span m=''3655190''>had</span> <span m=''3655360''>a</span>
  <span m=''3655390''>vertical</span> <span m=''3655880''>line.</span> <span m=''3657340''>These</span>
  <span m=''3657820''>two</span> <span m=''3657970''>cones</span> <span m=''3658220''>could</span>
  <span m=''3658360''>actually</span> <span m=''3658580''>be</span> <span m=''3658790''>equal,</span>
  <span m=''3659300''>and</span> <span m=''3659490''>then</span> <span m=''3659600''>the</span>
  <span m=''3659680''>intersection</span> <span m=''3660200''>is</span> <span m=''3660570''>the</span>
  <span m=''3660690''>entire</span> <span m=''3661060''>cone.</span> <span m=''3661810''>And</span>
  <span m=''3661980''>that</span> <span m=''3662130''>case,</span> <span m=''3662410''>I</span>
  <span m=''3662490''>guess</span> <span m=''3662720''>I''d</span> <span m=''3662780''>choose</span>
  <span m=''3663140''>the</span> <span m=''3663220''>maximum</span> <span m=''3663650''>x-coordinate</span>
  <span m=''3664170''>one</span> <span m=''3664350''>again.</span> <span m=''3665380''>And</span>
  <span m=''3665530''>then</span> <span m=''3665850''>I</span> <span m=''3666000''>have</span>
  <span m=''3666140''>a</span> <span m=''3666210''>canonical</span> <span m=''3666820''>choice</span>
  <span m=''3667350''>of</span> <span m=''3667500''>everything</span> <span m=''3668630''>along</span>
  <span m=''3668830''>the</span> <span m=''3668900''>way.</span> <span m=''3669080''>It</span>
  <span m=''3669140''>will</span> <span m=''3669300''>always</span> <span m=''3669570''>go</span>
  <span m=''3669730''>up.</span> <span m=''3670010''>And</span> <span m=''3670120''>it
  sort of</span> <span m=''3670230''>spinals</span> <span m=''3670890''>around</span>
  <span m=''3671200''>because</span> <span m=''3671510''>of</span> <span m=''3671620''>the</span>
  <span m=''3671790''>counter</span> <span m=''3672030''>clockwise</span> <span m=''3672940''>most</span>
  <span m=''3673280''>choice.</span> <span m=''3674180''>And</span> <span m=''3674600''>the</span>
  <span m=''3674720''>result</span> <span m=''3675540''>is</span> <span m=''3675840''>a</span>
  <span m=''3675990''>picture</span> <span m=''3676810''>like</span> <span m=''3677000''>this.</span>
  <span m=''3682770''>Anything else</span> <span m=''3683030''>I need to</span> <span
  m=''3683310''>say</span> <span m=''3683490''>here?</span> </p><p><span m=''3686380''>I</span>
  <span m=''3686490''>claim</span> <span m=''3688910''>this</span> <span m=''3689130''>canonical</span>
  <span m=''3689590''>configuration</span> <span m=''3691190''>lies</span> <span m=''3692450''>in</span>
  <span m=''3694000''>an</span> <span m=''3694170''>alpha</span> <span m=''3694580''>over</span>
  <span m=''3694880''>2</span> <span m=''3695840''>half</span> <span m=''3696320''>angle</span>
  <span m=''3697070''>cone.</span> <span m=''3701270''>That''s</span> <span m=''3701610''>true</span>
  <span m=''3701900''>by</span> <span m=''3702120''>construction.</span> <span m=''3704090''>The</span>
  <span m=''3704580''>challenge</span> <span m=''3704900''>is,</span> <span m=''3705220''>does</span>
  <span m=''3705390''>the</span> <span m=''3705450''>construction</span> <span m=''3705960''>really</span>
  <span m=''3706200''>work?</span> <span m=''3707410''>So</span> <span m=''3707550''>I</span>
  <span m=''3707610''>start,</span> <span m=''3708240''>obviously,</span> <span m=''3708590''>with</span>
  <span m=''3708770''>one</span> <span m=''3709420''>cone,</span> <span m=''3709880''>and</span>
  <span m=''3709990''>I</span> <span m=''3710040''>can</span> <span m=''3710200''>think</span>
  <span m=''3710360''>of</span> <span m=''3710450''>this</span> <span m=''3710630''>as</span>
  <span m=''3710770''>actually</span> <span m=''3711050''>an</span> <span m=''3711110''>infinite</span>
  <span m=''3711480''>cone</span> <span m=''3711750''>that</span> <span m=''3711820''>goes</span>
  <span m=''3712060''>out</span> <span m=''3712340''>to</span> <span m=''3712760''>infinity</span>
  <span m=''3713180''>here.</span> <span m=''3713920''>And</span> <span m=''3714290''>I</span>
  <span m=''3714380''>claim</span> <span m=''3714620''>the</span> <span m=''3714730''>entire</span>
  <span m=''3715230''>construction</span> <span m=''3715700''>will</span> <span m=''3715840''>lie</span>
  <span m=''3716010''>inside</span> <span m=''3716340''>that</span> <span m=''3716520''>cone.</span>
  <span m=''3718090''>And</span> <span m=''3718310''>it''s</span> <span m=''3718390''>kind</span>
  <span m=''3718530''>of</span> <span m=''3718600''>obvious</span> <span m=''3718900''>because</span>
  <span m=''3719600''>v1--</span> <span m=''3720930''>I</span> <span m=''3721190''>chose</span>
  <span m=''3721510''>v2</span> <span m=''3721880''>to</span> <span m=''3722010''>lie</span>
  <span m=''3722620''>in</span> <span m=''3723870''>the</span> <span m=''3724010''>same</span>
  <span m=''3726320''>cone,</span> <span m=''3726660''>just</span> <span m=''3726830''>translated</span>
  <span m=''3727410''>up</span> <span m=''3727620''>to</span> <span m=''3727770''>start
  at</span> <span m=''3728240''>v1</span> <span m=''3728610''>instead</span> <span
  m=''3728860''>of</span> <span m=''3728930''>starting</span> <span m=''3729240''>at</span>
  <span m=''3729290''>v0.</span> <span m=''3730790''>Of</span> <span m=''3730900''>course,</span>
  <span m=''3731160''>this</span> <span m=''3731340''>cone</span> <span m=''3731600''>is</span>
  <span m=''3731700''>contained</span> <span m=''3732190''>in</span> <span m=''3732270''>this</span>
  <span m=''3732420''>bigger</span> <span m=''3732680''>one.</span> </p><p><span m=''3733880''>And</span>
  <span m=''3734100''>by</span> <span m=''3734250''>induction,</span> <span m=''3734505''>in</span>
  <span m=''3734760''>fact,</span> <span m=''3735070''>the</span> <span m=''3735170''>entire</span>
  <span m=''3735720''>rest</span> <span m=''3735960''>of</span> <span m=''3736020''>the</span>
  <span m=''3736100''>chain</span> <span m=''3736470''>will</span> <span m=''3736730''>lie</span>
  <span m=''3737050''>in</span> <span m=''3737270''>this</span> <span m=''3737920''>smaller</span>
  <span m=''3738360''>cone.</span> <span m=''3738730''>Therefore,</span> <span m=''3739330''>it</span>
  <span m=''3739500''>lies</span> <span m=''3739780''>in</span> <span m=''3739860''>the</span>
  <span m=''3739930''>big</span> <span m=''3740110''>one,</span> <span m=''3740280''>also.</span>
  <span m=''3742440''>OK.</span> <span m=''3744530''>Fine.</span> <span m=''3745540''>So</span>
  <span m=''3745680''>by</span> <span m=''3745800''>construction</span> <span m=''3746300''>it</span>
  <span m=''3746370''>will</span> <span m=''3746560''>lie</span> <span m=''3747210''>in
  alpha</span> <span m=''3747510''>over</span> <span m=''3747680''>two</span> <span
  m=''3747910''>cone.</span> <span m=''3748630''>The</span> <span m=''3748840''>worry</span>
  <span m=''3749230''>is</span> <span m=''3749490''>that</span> <span m=''3749630''>these</span>
  <span m=''3749810''>two</span> <span m=''3749960''>cones</span> <span m=''3750230''>don''t</span>
  <span m=''3750430''>intersect.</span> <span m=''3753380''>Here</span> <span m=''3753660''>we</span>
  <span m=''3753750''>have</span> <span m=''3753940''>an</span> <span m=''3754040''>angle.</span>
  <span m=''3755100''>The</span> <span m=''3755300''>half</span> <span m=''3755600''>angle</span>
  <span m=''3755840''>of</span> <span m=''3755960''>the</span> <span m=''3756050''>cone</span>
  <span m=''3756420''>is</span> <span m=''3756690''>whatever</span> <span m=''3757040''>angle</span>
  <span m=''3757860''>the</span> <span m=''3758100''>angle</span> <span m=''3758350''>is</span>
  <span m=''3758510''>at</span> <span m=''3758720''>v1.</span> <span m=''3759920''>Sorry,</span>
  <span m=''3760100''>this</span> <span m=''3760230''>should</span> <span m=''3760460''>not</span>
  <span m=''3760640''>be</span> <span m=''3760740''>the</span> <span m=''3760860''>angle.</span>
  <span m=''3761180''>This</span> <span m=''3761260''>should</span> <span m=''3761430''>be</span>
  <span m=''3761510''>the</span> <span m=''3761620''>turn</span> <span m=''3761850''>angle.</span>
  <span m=''3768740''>That</span> <span m=''3768970''>angle</span> <span m=''3769320''>is</span>
  <span m=''3769610''>how</span> <span m=''3769710''>much</span> <span m=''3769900''>you</span>
  <span m=''3769990''>turn</span> <span m=''3770380''>from</span> <span m=''3770760''>v0,</span>
  <span m=''3771130''>v1.</span> </p><p><span m=''3772310''>Now,</span> <span m=''3772500''>we</span>
  <span m=''3772640''>know</span> <span m=''3772960''>that--</span> <span m=''3773330''>we''re</span>
  <span m=''3773520''>assuming</span> <span m=''3774150''>that--</span> <span m=''3774280''>the</span>
  <span m=''3774380''>turn angles</span> <span m=''3774880''>are</span> <span m=''3774990''>all,</span>
  <span m=''3775170''>at</span> <span m=''3775290''>most,</span> <span m=''3775550''>alpha.</span>
  <span m=''3778700''>The</span> <span m=''3779950''>turn angle</span> <span m=''3780400''>cone</span>
  <span m=''3780640''>could</span> <span m=''3780750''>actually</span> <span m=''3781040''>be</span>
  <span m=''3781340''>twice</span> <span m=''3781660''>as</span> <span m=''3781800''>big</span>
  <span m=''3782710''>as</span> <span m=''3783030''>the</span> <span m=''3783140''>vertical</span>
  <span m=''3783530''>cone</span> <span m=''3783790''>that</span> <span m=''3783910''>we
  were always</span> <span m=''3784230''>using.</span> <span m=''3784620''>We</span>
  <span m=''3784780''>always</span> <span m=''3784990''>use</span> <span m=''3785170''>a</span>
  <span m=''3785210''>vertical</span> <span m=''3785600''>cone,</span> <span m=''3786340''>half</span>
  <span m=''3786600''>angle</span> <span m=''3786870''>alpha</span> <span m=''3787120''>over</span>
  <span m=''3787330''>two.</span> <span m=''3788640''>But</span> <span m=''3790310''>it''s</span>
  <span m=''3790710''>OK</span> <span m=''3791020''>because</span> <span m=''3791340''>we</span>
  <span m=''3791500''>always</span> <span m=''3791820''>keep</span> <span m=''3792120''>these</span>
  <span m=''3792410''>edges,</span> <span m=''3792940''>like</span> <span m=''3793340''>v0,</span>
  <span m=''3793580''>v1,</span> <span m=''3794250''>was</span> <span m=''3794440''>on</span>
  <span m=''3794570''>the</span> <span m=''3794750''>edge</span> <span m=''3795000''>of</span>
  <span m=''3795070''>the</span> <span m=''3795180''>cone.</span> <span m=''3797750''>And</span>
  <span m=''3797860''>so</span> <span m=''3798180''>when</span> <span m=''3798420''>we</span>
  <span m=''3798510''>extend</span> <span m=''3798940''>it,</span> <span m=''3799160''>it</span>
  <span m=''3799320''>lies</span> <span m=''3799680''>on</span> <span m=''3799760''>the</span>
  <span m=''3799890''>edge</span> <span m=''3800210''>of</span> <span m=''3800350''>this</span>
  <span m=''3800600''>vertical</span> <span m=''3800980''>cone.</span> <span m=''3802470''>So</span>
  <span m=''3802700''>its</span> <span m=''3802940''>angle--</span> <span m=''3804360''>in</span>
  <span m=''3804850''>the</span> <span m=''3805170''>most</span> <span m=''3805670''>extreme</span>
  <span m=''3806030''>case--</span> <span m=''3806920''>its</span> <span m=''3807110''>half</span>
  <span m=''3807370''>angle</span> <span m=''3807640''>is</span> <span m=''3807910''>alpha,</span>
  <span m=''3809140''>which</span> <span m=''3809380''>would</span> <span m=''3809550''>look</span>
  <span m=''3809740''>like</span> <span m=''3810020''>this.</span> </p><p><span m=''3811420''>We''ll</span>
  <span m=''3811530''>go</span> <span m=''3811720''>all</span> <span m=''3812100''>the</span>
  <span m=''3812190''>way</span> <span m=''3812380''>over</span> <span m=''3812700''>from</span>
  <span m=''3812900''>the</span> <span m=''3812990''>right</span> <span m=''3813220''>side</span>
  <span m=''3813400''>of</span> <span m=''3813460''>the</span> <span m=''3813530''>cone
  to</span> <span m=''3813780''>the</span> <span m=''3813880''>left</span> <span m=''3814170''>side</span>
  <span m=''3814330''>of</span> <span m=''3814410''>the</span> <span m=''3814510''>cone.</span>
  <span m=''3814860''>In</span> <span m=''3815020''>general,</span> <span m=''3815350''>it''s
  not going</span> <span m=''3815600''>to</span> <span m=''3815640''>be</span> <span
  m=''3815760''>right</span> <span m=''3815940''>and</span> <span m=''3816020''>left,</span>
  <span m=''3816270''>but</span> <span m=''3816380''>it''s</span> <span m=''3816510''>going</span>
  <span m=''3816610''>to</span> <span m=''3816660''>be</span> <span m=''3816780''>some</span>
  <span m=''3817030''>side</span> <span m=''3817430''>and</span> <span m=''3817630''>the</span>
  <span m=''3818080''>antipodal</span> <span m=''3818670''>point.</span> <span m=''3820210''>And</span>
  <span m=''3820770''>because</span> <span m=''3821290''>the</span> <span m=''3822020''>double</span>
  <span m=''3822420''>angle</span> <span m=''3822650''>of</span> <span m=''3822750''>the</span>
  <span m=''3822840''>cone</span> <span m=''3823250''>is</span> <span m=''3823460''>alpha,</span>
  <span m=''3824610''>it''s</span> <span m=''3824770''>still</span> <span m=''3825020''>OK.</span>
  <span m=''3825700''>You will</span> <span m=''3825920''>intersect</span> <span m=''3826370''>somewhere</span>
  <span m=''3826680''>on</span> <span m=''3826760''>the</span> <span m=''3826850''>cone.</span>
  <span m=''3829600''>This</span> <span m=''3829800''>is</span> <span m=''3829930''>a</span>
  <span m=''3830190''>subtle</span> <span m=''3830680''>detail,</span> <span m=''3831130''>but</span>
  <span m=''3831290''>it''s</span> <span m=''3831430''>really</span> <span m=''3831690''>crucial</span>
  <span m=''3832190''>because</span> <span m=''3832490''>we</span> <span m=''3832590''>start</span>
  <span m=''3832910''>with</span> <span m=''3833040''>a</span> <span m=''3833130''>chain</span>
  <span m=''3833560''>that</span> <span m=''3834050''>has</span> <span m=''3834230''>relatively</span>
  <span m=''3834740''>large</span> <span m=''3835150''>angles,</span> <span m=''3835500''>alpha.</span>
  </p><p><span m=''3836840''>And</span> <span m=''3837040''>we</span> <span m=''3837150''>get</span>
  <span m=''3837360''>it</span> <span m=''3837520''>into--</span> <span m=''3837960''>we</span>
  <span m=''3838070''>squeeze</span> <span m=''3838520''>it</span> <span m=''3838600''>into--</span>
  <span m=''3838910''>a cone</span> <span m=''3839930''>that</span> <span m=''3840090''>still</span>
  <span m=''3840300''>has</span> <span m=''3840500''>double--</span> <span m=''3841010''>twice</span>
  <span m=''3841820''>its</span> <span m=''3841960''>angle</span> <span m=''3842270''>is</span>
  <span m=''3842420''>alpha,</span> <span m=''3843380''>but</span> <span m=''3843710''>we</span>
  <span m=''3843880''>kind</span> <span m=''3844160''>of</span> <span m=''3844240''>compress</span>
  <span m=''3844820''>it</span> <span m=''3845040''>into</span> <span m=''3845710''>something</span>
  <span m=''3846030''>of</span> <span m=''3846100''>half</span> <span m=''3846380''>angle</span>
  <span m=''3846680''>alpha</span> <span m=''3846920''>over</span> <span m=''3847140''>two.</span>
  <span m=''3848100''>You</span> <span m=''3848220''>might</span> <span m=''3848400''>think,
  oh,</span> <span m=''3848580''>I''m</span> <span m=''3848870''>just</span> <span
  m=''3849470''>changing</span> <span m=''3849880''>the</span> <span m=''3849960''>definition</span>
  <span m=''3850235''>and</span> <span m=''3850510''>calling</span> <span m=''3850790''>it</span>
  <span m=''3850810''>half</span> <span m=''3851120''>angle.</span> <span m=''3851780''>Therefore,</span>
  <span m=''3852220''>it gets</span> <span m=''3852450''>to an</span> <span m=''3852570''>alpha</span>
  <span m=''3852810''>over</span> <span m=''3852960''>two.</span> <span m=''3853120''>But</span>
  <span m=''3853290''>it''s</span> <span m=''3854000''>a</span> <span m=''3854070''>little</span>
  <span m=''3854270''>tricky</span> <span m=''3854620''>to</span> <span m=''3854800''>actually</span>
  <span m=''3855080''>get</span> <span m=''3855210''>it</span> <span m=''3855320''>to</span>
  <span m=''3855400''>fit</span> <span m=''3855600''>in</span> <span m=''3855830''>a</span>
  <span m=''3855880''>vertical</span> <span m=''3856980''>alpha</span> <span m=''3857210''>over</span>
  <span m=''3857390''>two</span> <span m=''3857540''>cone.</span> <span m=''3858520''>Once</span>
  <span m=''3858760''>we</span> <span m=''3858870''>have</span> <span m=''3859140''>this,</span>
  <span m=''3859940''>it''s</span> <span m=''3860110''>really</span> <span m=''3860370''>easy</span>
  <span m=''3860730''>to</span> <span m=''3861070''>canonicalize</span> <span m=''3861850''>a</span>
  <span m=''3861930''>chain,</span> <span m=''3862510''>a</span> <span m=''3862600''>producible</span>
  <span m=''3863120''>chain.</span> <span m=''3863470''>So</span> <span m=''3863680''>let</span>
  <span m=''3863830''>me</span> <span m=''3863930''>tell</span> <span m=''3864130''>you</span>
  <span m=''3864850''>how</span> <span m=''3865230''>to</span> <span m=''3865300''>do</span>
  <span m=''3865430''>that.</span> </p><p><span m=''3892380''>So</span> <span m=''3892440''>we''re</span>
  <span m=''3892530''>going</span> <span m=''3892800''>use</span> <span m=''3893560''>the</span>
  <span m=''3893660''>FedEx</span> <span m=''3894120''>method</span> <span m=''3894510''>of</span>
  <span m=''3894620''>taking</span> <span m=''3894940''>some</span> <span m=''3895200''>configuration</span>
  <span m=''3896220''>and</span> <span m=''3896390''>canonicalizing</span> <span m=''3897100''>it,</span>
  <span m=''3897270''>and</span> <span m=''3897390''>then</span> <span m=''3897570''>uncanonicalizing</span>
  <span m=''3898410''>to</span> <span m=''3898610''>something</span> <span m=''3899000''>else.</span>
  <span m=''3899910''>We''re</span> <span m=''3900070''>also</span> <span m=''3900380''>going</span>
  <span m=''3900620''>to</span> <span m=''3900730''>use</span> <span m=''3901090''>a</span>
  <span m=''3901150''>new</span> <span m=''3901350''>method,</span> <span m=''3901740''>which</span>
  <span m=''3901930''>I</span> <span m=''3901990''>just</span> <span m=''3902300''>came</span>
  <span m=''3902490''>up</span> <span m=''3902620''>with</span> <span m=''3902720''>the</span>
  <span m=''3902810''>term.</span> <span m=''3903360''>Is</span> <span m=''3903530''>called</span>
  <span m=''3903770''>the</span> <span m=''3903860''>momento</span> <span m=''3904480''>method</span>
  <span m=''3905650''>which</span> <span m=''3905950''>is</span> <span m=''3906060''>you</span>
  <span m=''3906190''>play</span> <span m=''3906940''>the</span> <span m=''3907050''>movie</span>
  <span m=''3907630''>in</span> <span m=''3908010''>reverse.</span> <span m=''3910370''>So,</span>
  <span m=''3910950''>I</span> <span m=''3911070''>guess,</span> <span m=''3911270''>also</span>
  <span m=''3911510''>the</span> <span m=''3911620''>Merlin</span> <span m=''3911980''>method.</span>
  <span m=''3914130''>That''s</span> <span m=''3914320''>more</span> <span m=''3914520''>complicated.</span>
  <span m=''3916820''>So</span> <span m=''3917190''>we</span> <span m=''3917410''>have</span>
  <span m=''3917750''>a</span> <span m=''3917810''>movie</span> <span m=''3918700''>here</span>
  <span m=''3919220''>in</span> <span m=''3919350''>mind,</span> <span m=''3921460''>which</span>
  <span m=''3921670''>is</span> <span m=''3922060''>how</span> <span m=''3922450''>was</span>
  <span m=''3922690''>the</span> <span m=''3922820''>chain</span> <span m=''3923200''>produced?</span>
  </p><p><span m=''3924210''>So</span> <span m=''3924360''>what</span> <span m=''3924500''>I</span>
  <span m=''3924560''>want</span> <span m=''3924730''>to</span> <span m=''3924770''>show</span>
  <span m=''3925550''>is</span> <span m=''3925740''>that</span> <span m=''3925870''>if--</span>
  <span m=''3926730''>I</span> <span m=''3926840''>want</span> <span m=''3926980''>to</span>
  <span m=''3927030''>start</span> <span m=''3927410''>with</span> <span m=''3927770''>a</span>
  <span m=''3928170''>producible</span> <span m=''3929920''>configuration</span> <span
  m=''3931610''>and</span> <span m=''3931970''>chain.</span> <span m=''3934790''>Somehow,</span>
  <span m=''3935410''>it</span> <span m=''3935550''>got</span> <span m=''3935750''>produced.</span>
  <span m=''3937180''>So</span> <span m=''3938950''>you</span> <span m=''3939110''>had</span>
  <span m=''3939340''>your</span> <span m=''3939480''>cone</span> <span m=''3940800''>and</span>
  <span m=''3941010''>the</span> <span m=''3941090''>thing</span> <span m=''3941440''>starts</span>
  <span m=''3941750''>spewing</span> <span m=''3942110''>out</span> <span m=''3942330''>and
  folding,</span> <span m=''3943010''>and</span> <span m=''3943090''>doing</span>
  <span m=''3943310''>whatever.</span> <span m=''3945160''>That''s</span> <span m=''3945860''>an</span>
  <span m=''3946020''>animation,</span> <span m=''3946690''>in</span> <span m=''3946780''>some</span>
  <span m=''3946970''>sense,</span> <span m=''3947310''>of</span> <span m=''3947930''>one</span>
  <span m=''3948200''>edge</span> <span m=''3948420''>coming</span> <span m=''3948750''>out</span>
  <span m=''3948950''>and</span> <span m=''3949050''>stuff</span> <span m=''3949300''>is</span>
  <span m=''3949440''>folding</span> <span m=''3949750''>at</span> <span m=''3949850''>the</span>
  <span m=''3949930''>same</span> <span m=''3950140''>time.</span> <span m=''3950390''>Then</span>
  <span m=''3950590''>an</span> <span m=''3950850''>edge is</span> <span m=''3951000''>created,</span>
  <span m=''3951440''>then</span> <span m=''3951550''>another</span> <span m=''3951830''>edge</span>
  <span m=''3951980''>comes</span> <span m=''3952220''>out,</span> <span m=''3952410''>and</span>
  <span m=''3952530''>so on.</span> <span m=''3953250''>What</span> <span m=''3953460''>I</span>
  <span m=''3953500''>want</span> <span m=''3953660''>to</span> <span m=''3953730''>do</span>
  <span m=''3953880''>is</span> <span m=''3954010''>play</span> <span m=''3954170''>that</span>
  <span m=''3954360''>movie</span> <span m=''3954870''>backwards.</span> <span m=''3955570''>It''s
  a</span> <span m=''3955790''>pretty</span> <span m=''3956180''>intuitive</span>
  <span m=''3956580''>idea.</span> <span m=''3957690''>I</span> <span m=''3957780''>just</span>
  <span m=''3957940''>want</span> <span m=''3958070''>to</span> <span m=''3958120''>start</span>
  <span m=''3958420''>feeding</span> <span m=''3958720''>the</span> <span m=''3958820''>edges</span>
  <span m=''3959070''>back</span> <span m=''3959360''>into</span> <span m=''3959610''>the</span>
  <span m=''3959720''>cone,</span> <span m=''3961310''>and</span> <span m=''3961530''>just</span>
  <span m=''3961860''>keep</span> <span m=''3962030''>stuffing</span> <span m=''3962450''>them</span>
  <span m=''3962610''>in.</span> </p><p><span m=''3963000''>Now,</span> <span m=''3963230''>what</span>
  <span m=''3963420''>happens</span> <span m=''3963760''>out</span> <span m=''3963880''>here</span>
  <span m=''3964500''>is</span> <span m=''3964710''>easy</span> <span m=''3965060''>because</span>
  <span m=''3966080''>we</span> <span m=''3966210''>know</span> <span m=''3966320''>it</span>
  <span m=''3966410''>doesn''t</span> <span m=''3966660''>penetrate</span> <span m=''3967070''>the</span>
  <span m=''3967160''>cone.</span> <span m=''3967560''>That''s</span> <span m=''3967810''>the</span>
  <span m=''3967900''>assumption.</span> <span m=''3968960''>And we know</span> <span
  m=''3969200''>whatever</span> <span m=''3969880''>was</span> <span m=''3970160''>created</span>
  <span m=''3970620''>here</span> <span m=''3970850''>could</span> <span m=''3971020''>be</span>
  <span m=''3971340''>uncreated,</span> <span m=''3972120''>as</span> <span m=''3972270''>long</span>
  <span m=''3972560''>as</span> <span m=''3972780''>you</span> <span m=''3973160''>can</span>
  <span m=''3973410''>afford</span> <span m=''3973890''>to</span> <span m=''3974150''>erase</span>
  <span m=''3974620''>edges</span> <span m=''3975890''>one</span> <span m=''3976100''>by</span>
  <span m=''3976270''>one.</span> <span m=''3976850''>That''s</span> <span m=''3977120''>the</span>
  <span m=''3977160''>tricky</span> <span m=''3977440''>part.</span> <span m=''3978310''>How</span>
  <span m=''3978490''>do I erase</span> <span m=''3978950''>an</span> <span m=''3979020''>edge?</span>
  <span m=''3979200''>And usually,</span> <span m=''3979590''>I</span> <span m=''3979670''>can''t.</span>
  <span m=''3981590''>But</span> <span m=''3982550''>I</span> <span m=''3982640''>don''t</span>
  <span m=''3982810''>have</span> <span m=''3982920''>to</span> <span m=''3983030''>erase</span>
  <span m=''3983370''>any</span> <span m=''3983680''>edge.</span> <span m=''3983950''>Like,</span>
  <span m=''3984200''>if I</span> <span m=''3984260''>had</span> <span m=''3984410''>to</span>
  <span m=''3984450''>erase</span> <span m=''3984750''>this</span> <span m=''3984940''>one,</span>
  <span m=''3985770''>that</span> <span m=''3985940''>would</span> <span m=''3986030''>be</span>
  <span m=''3986140''>hard</span> <span m=''3986440''>because</span> <span m=''3986760''>some</span>
  <span m=''3987060''>motion</span> <span m=''3987660''>here</span> <span m=''3987950''>might</span>
  <span m=''3988210''>penetrate</span> <span m=''3988710''>where</span> <span m=''3988850''>that</span>
  <span m=''3989000''>edge</span> <span m=''3989790''>ought to have</span> <span m=''3989980''>been.</span>
  <span m=''3991080''>And</span> <span m=''3991850''>erasing the</span> <span m=''3992350''>edge</span>
  <span m=''3992500''>will</span> <span m=''3993330''>make</span> <span m=''3993520''>it--</span>
  <span m=''3997090''>adding</span> <span m=''3997540''>the</span> <span m=''3997680''>edge</span>
  <span m=''3998010''>makes</span> <span m=''3998240''>it</span> <span m=''3998300''>harder</span>
  <span m=''3998570''>to</span> <span m=''3998670''>fold.</span> <span m=''3999320''>So</span>
  <span m=''3999460''>I</span> <span m=''3999500''>can''t</span> <span m=''3999700''>erase</span>
  <span m=''4000020''>it.</span> </p><p><span m=''4002000''>But</span> <span m=''4002190''>the</span>
  <span m=''4002370''>edges</span> <span m=''4002640''>I</span> <span m=''4002710''>have</span>
  <span m=''4002880''>to</span> <span m=''4003020''>erase</span> <span m=''4003240''>are</span>
  <span m=''4003290''>the</span> <span m=''4003420''>ones</span> <span m=''4003630''>that</span>
  <span m=''4003730''>have</span> <span m=''4003900''>been</span> <span m=''4004020''>fully</span>
  <span m=''4004440''>inserted</span> <span m=''4004900''>into</span> <span m=''4005120''>the
  cone.</span> <span m=''4005610''>So</span> <span m=''4005710''>if</span> <span m=''4005820''>I</span>
  <span m=''4005880''>can</span> <span m=''4006060''>somehow</span> <span m=''4006480''>do</span>
  <span m=''4006650''>something</span> <span m=''4007170''>inside</span> <span m=''4007550''>the</span>
  <span m=''4007650''>cone,</span> <span m=''4009280''>I</span> <span m=''4009320''>would</span>
  <span m=''4009490''>be</span> <span m=''4009890''>OK.</span> <span m=''4012070''>All</span>
  <span m=''4012380''>this</span> <span m=''4012580''>work,</span> <span m=''4013550''>defining</span>
  <span m=''4013930''>a canonical</span> <span m=''4014520''>configuration,</span>
  <span m=''4015610''>was</span> <span m=''4015840''>about</span> <span m=''4016140''>forcing</span>
  <span m=''4016650''>a</span> <span m=''4016700''>chain</span> <span m=''4017070''>to</span>
  <span m=''4017200''>stay</span> <span m=''4017470''>inside</span> <span m=''4017800''>a</span>
  <span m=''4017880''>cone--</span> <span m=''4018200''>and</span> <span m=''4018290''>not</span>
  <span m=''4018590''>only</span> <span m=''4018890''>an</span> <span m=''4018980''>alpha</span>
  <span m=''4019320''>cone,</span> <span m=''4019650''>which</span> <span m=''4019810''>is</span>
  <span m=''4019920''>what</span> <span m=''4020090''>we''re</span> <span m=''4020210''>going</span>
  <span m=''4020450''>to</span> <span m=''4020540''>have</span> <span m=''4021500''>as</span>
  <span m=''4021700''>the</span> <span m=''4021800''>ribosome,</span> <span m=''4022350''>but</span>
  <span m=''4022500''>an</span> <span m=''4022630''>alpha</span> <span m=''4022940''>over</span>
  <span m=''4023210''>two</span> <span m=''4023450''>cone.</span> <span m=''4023800''>This</span>
  <span m=''4024090''>is</span> <span m=''4024350''>smaller</span> <span m=''4024880''>than</span>
  <span m=''4025050''>my</span> <span m=''4025230''>ribosome</span> <span m=''4025790''>cone</span>
  <span m=''4027030''>by</span> <span m=''4027160''>factor</span> <span m=''4027510''>of</span>
  <span m=''4027580''>two.</span> <span m=''4027920''>And</span> <span m=''4028070''>I</span>
  <span m=''4028130''>need</span> <span m=''4028430''>that.</span> </p><p><span m=''4030452''>Why</span>
  <span m=''4031100''>do</span> <span m=''4031230''>I</span> <span m=''4031320''>need</span>
  <span m=''4031550''>that?</span> <span m=''4031820''>Because</span> <span m=''4033560''>this</span>
  <span m=''4033930''>thing,</span> <span m=''4034600''>I</span> <span m=''4034730''>have</span>
  <span m=''4034900''>no</span> <span m=''4035190''>control</span> <span m=''4035670''>over</span>
  <span m=''4035820''>the</span> <span m=''4035980''>outside</span> <span m=''4037180''>chain.</span>
  <span m=''4038110''>So</span> <span m=''4038240''>the</span> <span m=''4038340''>way</span>
  <span m=''4038510''>that</span> <span m=''4038680''>it</span> <span m=''4038760''>approaches</span>
  <span m=''4039180''>the</span> <span m=''4039270''>cone</span> <span m=''4039540''>could</span>
  <span m=''4039780''>be</span> <span m=''4039970''>as</span> <span m=''4040140''>sharp</span>
  <span m=''4040600''>as</span> <span m=''4040850''>like</span> <span m=''4041140''>this,</span>
  <span m=''4042630''>where</span> <span m=''4042800''>I</span> <span m=''4042840''>have</span>
  <span m=''4043770''>the</span> <span m=''4043850''>first</span> <span m=''4044210''>edge</span>
  <span m=''4044600''>that</span> <span m=''4044790''>is--</span> <span m=''4045580''>the</span>
  <span m=''4046010''>current</span> <span m=''4046310''>edge</span> <span m=''4046540''>that
  is--</span> <span m=''4046710''>inside</span> <span m=''4047120''>the</span> <span
  m=''4047220''>cone.</span> <span m=''4047820''>As</span> <span m=''4047880''>far</span>
  <span m=''4048020''>as</span> <span m=''4048100''>the</span> <span m=''4048180''>movie
  is</span> <span m=''4048540''>concerned,</span> <span m=''4048890''>there''s</span>
  <span m=''4048980''>only</span> <span m=''4049160''>one</span> <span m=''4049410''>edge.</span>
  <span m=''4050140''>There''s</span> <span m=''4050290''>nothing</span> <span m=''4050610''>up</span>
  <span m=''4050740''>here.</span> <span m=''4052100''>I</span> <span m=''4052240''>want</span>
  <span m=''4052380''>to</span> <span m=''4052440''>put</span> <span m=''4052620''>something</span>
  <span m=''4053000''>up</span> <span m=''4053140''>here,</span> <span m=''4054050''>in</span>
  <span m=''4054210''>a</span> <span m=''4054280''>cone,</span> <span m=''4054700''>naturally.</span>
  <span m=''4058030''>But</span> <span m=''4058160''>I</span> <span m=''4058250''>don''t</span>
  <span m=''4058440''>get</span> <span m=''4058590''>to</span> <span m=''4058680''>control</span>
  <span m=''4059890''>the</span> <span m=''4059980''>first</span> <span m=''4060350''>angle</span>
  <span m=''4061060''>because</span> <span m=''4061330''>that</span> <span m=''4061530''>is</span>
  <span m=''4061670''>controlled</span> <span m=''4062020''>by</span> <span m=''4062140''>this</span>
  <span m=''4062300''>motion.</span> <span m=''4062680''>Maybe</span> <span m=''4063030''>it
  really</span> <span m=''4063280''>needed</span> <span m=''4063560''>to</span> <span
  m=''4063650''>go</span> <span m=''4064780''>sharp</span> <span m=''4065100''>like</span>
  <span m=''4065270''>that</span> <span m=''4065460''>so</span> <span m=''4065560''>that
  it</span> <span m=''4065680''>could</span> <span m=''4065840''>make</span> <span
  m=''4066000''>a</span> <span m=''4066050''>sharper</span> <span m=''4066460''>angle</span>
  <span m=''4066850''>or</span> <span m=''4066920''>whatever.</span> </p><p><span
  m=''4072720''>So</span> <span m=''4074840''>you</span> <span m=''4075160''>might</span>
  <span m=''4075370''>say,</span> <span m=''4075580''>well,</span> <span m=''4075950''>of</span>
  <span m=''4076060''>course</span> <span m=''4076310''>I can</span> <span m=''4076590''>put</span>
  <span m=''4076780''>it</span> <span m=''4076970''>inside</span> <span m=''4078210''>and</span>
  <span m=''4078320''>alpha</span> <span m=''4078670''>cone,</span> <span m=''4079690''>which</span>
  <span m=''4079810''>is</span> <span m=''4079940''>the</span> <span m=''4080020''>same</span>
  <span m=''4080380''>as</span> <span m=''4081120''>this</span> <span m=''4081450''>alpha.</span>
  <span m=''4083020''>Sorry--</span> <span m=''4083760''>bad</span> <span m=''4084210''>picture.</span>
  <span m=''4084890''>This</span> <span m=''4085090''>is</span> <span m=''4085200''>alpha.</span>
  <span m=''4087910''>This</span> <span m=''4088110''>would</span> <span m=''4088230''>be</span>
  <span m=''4088380''>a</span> <span m=''4088440''>problem</span> <span m=''4089300''>because</span>
  <span m=''4089590''>I</span> <span m=''4089630''>have</span> <span m=''4089810''>this</span>
  <span m=''4089960''>weird</span> <span m=''4090310''>angle</span> <span m=''4090680''>coming</span>
  <span m=''4090970''>in,</span> <span m=''4091680''>and</span> <span m=''4091840''>now</span>
  <span m=''4092400''>suddenly</span> <span m=''4092890''>I</span> <span m=''4092930''>have</span>
  <span m=''4093150''>to</span> <span m=''4093250''>bend</span> <span m=''4093650''>back</span>
  <span m=''4093920''>like</span> <span m=''4094060''>that.</span> <span m=''4094480''>Maybe</span>
  <span m=''4094780''>the</span> <span m=''4094880''>turn</span> <span m=''4095110''>angle</span>
  <span m=''4095330''>here</span> <span m=''4095460''>is</span> <span m=''4095560''>not</span>
  <span m=''4095810''>so</span> <span m=''4095940''>sharp</span> <span m=''4096250''>as</span>
  <span m=''4096609''>alpha.</span> <span m=''4096729''>Maybe</span> <span m=''4097090''>it''s</span>
  <span m=''4098160''>one</span> <span m=''4098410''>degree.</span> <span m=''4099620''>So</span>
  <span m=''4099770''>I</span> <span m=''4099850''>really</span> <span m=''4100319''>can''t</span>
  <span m=''4101399''>force</span> <span m=''4101859''>the</span> <span m=''4101960''>rest</span>
  <span m=''4102210''>of</span> <span m=''4102250''>my</span> <span m=''4102390''>chain</span>
  <span m=''4102680''>to</span> <span m=''4102819''>lie</span> <span m=''4103149''>in</span>
  <span m=''4103279''>this</span> <span m=''4103450''>cone.</span> <span m=''4105210''>But</span>
  <span m=''4106109''>I</span> <span m=''4106270''>claim</span> <span m=''4107160''>I</span>
  <span m=''4107270''>can</span> <span m=''4107460''>force</span> <span m=''4107800''>it</span>
  <span m=''4108340''>to</span> <span m=''4108560''>lie</span> <span m=''4109390''>in</span>
  <span m=''4109580''>this</span> <span m=''4109870''>cone,</span> <span m=''4111910''>with</span>
  <span m=''4112180''>half</span> <span m=''4112470''>angle</span> <span m=''4112750''>alpha</span>
  <span m=''4113140''>over</span> <span m=''4113390''>two.</span> <span m=''4115140''>This</span>
  <span m=''4115359''>is</span> <span m=''4115529''>a</span> <span m=''4115750''>little</span>
  <span m=''4116210''>more</span> <span m=''4116479''>subtle.</span> <span m=''4118800''>Oh,</span>
  <span m=''4119319''>right.</span> <span m=''4119990''>I</span> <span m=''4120060''>wanted</span>
  <span m=''4120310''>to</span> <span m=''4120390''>mention</span> <span m=''4120710''>that</span>
  <span m=''4120840''>helices</span> <span m=''4121270''>appear</span> <span m=''4121600''>in</span>
  <span m=''4121740''>nature.</span> <span m=''4123800''>They</span> <span m=''4123939''>appear</span>
  <span m=''4124240''>in</span> <span m=''4124310''>proteins,</span> <span m=''4125319''>but</span>
  <span m=''4125560''>they</span> <span m=''4125670''>also</span> <span m=''4125870''>appear</span>
  <span m=''4126200''>in</span> <span m=''4126330''>this</span> <span m=''4126529''>crazy</span>
  <span m=''4127290''>climber</span> <span m=''4127689''>plant.</span> <span m=''4129390''>Marty,</span>
  <span m=''4129560''>have</span> <span m=''4129630''>you</span> <span m=''4129689''>seen</span>
  <span m=''4129870''>this</span> <span m=''4130020''>in</span> <span m=''4130120''>Costa</span>
  <span m=''4130370''>Rica?</span> </p><p><span m=''4130729''>AUDIENCE: Yeah.</span>
  </p><p><span m=''4131580''>PROFESSOR: Yeah.</span> <span m=''4132090''>There''s</span>
  <span m=''4132290''>some</span> <span m=''4132529''>really</span> <span m=''4132960''>incredible</span>
  <span m=''4133590''>wildlife</span> <span m=''4133990''>in</span> <span m=''4134080''>Costa
  Rica.</span> <span m=''4134470''>I''ve</span> <span m=''4134569''>never</span> <span
  m=''4134779''>been</span> <span m=''4134939''>there,</span> <span m=''4135520''>but</span>
  <span m=''4135649''>I''ve</span> <span m=''4135740''>seen</span> <span m=''4135890''>lots</span>
  <span m=''4136090''>of</span> <span m=''4136160''>pictures</span> <span m=''4136520''>and</span>
  <span m=''4136670''>this</span> <span m=''4136859''>is</span> <span m=''4138729''>spirals</span>
  <span m=''4139189''>in</span> <span m=''4139300''>practice.</span> <span m=''4140890''>Also,</span>
  <span m=''4142710''>proteins</span> <span m=''4143220''>tend</span> <span m=''4143390''>to</span>
  <span m=''4143439''>form</span> <span m=''4143689''>these</span> <span m=''4143859''>things.</span>
  <span m=''4144090''>They</span> <span m=''4144130''>call</span> <span m=''4144310''>them</span>
  <span m=''4144420''>out</span> <span m=''4144620''>alpha</span> <span m=''4144729''>helices</span>
  <span m=''4145149''>because</span> <span m=''4145350''>they</span> <span m=''4145520''>spin</span>
  <span m=''4145670''>like</span> <span m=''4145870''>an</span> <span m=''4145939''>alpha,</span>
  <span m=''4146399''>I</span> <span m=''4146470''>guess.</span> <span m=''4148979''>So</span>
  <span m=''4149490''>it''s</span> <span m=''4149670''>kind</span> <span m=''4149850''>of</span>
  <span m=''4149920''>neat</span> <span m=''4150140''>that</span> <span m=''4150310''>the</span>
  <span m=''4150450''>canonical</span> <span m=''4150899''>configuration,</span> <span
  m=''4151410''>which</span> <span m=''4151560''>is</span> <span m=''4151640''>totally</span>
  <span m=''4152229''>geometrically</span> <span m=''4152890''>motivated,</span> <span
  m=''4153840''>also</span> <span m=''4154210''>appears</span> <span m=''4154569''>in</span>
  <span m=''4154660''>biology.</span> <span m=''4156591''>Not</span> <span m=''4157010''>that</span>
  <span m=''4157140''>kind</span> <span m=''4157300''>of</span> <span m=''4157370''>biology</span>
  <span m=''4157810''>though.</span> </p><p><span m=''4159710''>So</span> <span m=''4160370''>here</span>
  <span m=''4160750''>is</span> <span m=''4161029''>the</span> <span m=''4161439''>picture.</span>
  <span m=''4162279''>I</span> <span m=''4162410''>have</span> <span m=''4163359''>the</span>
  <span m=''4163479''>big</span> <span m=''4163750''>cone.</span> <span m=''4164430''>That</span>
  <span m=''4164649''>is</span> <span m=''4164800''>my</span> <span m=''4164950''>ribosome,</span>
  <span m=''4165250''>and</span> <span m=''4165620''>here</span> <span m=''4165830''>I''m</span>
  <span m=''4165890''>going</span> <span m=''4166010''>to</span> <span m=''4166080''>write</span>
  <span m=''4166340''>beta</span> <span m=''4167450''>for</span> <span m=''4167660''>the--</span>
  <span m=''4168410''>beta</span> <span m=''4168649''>for</span> <span m=''4168790''>big,</span>
  <span m=''4169439''>I guess.</span> <span m=''4170170''>And</span> <span m=''4170510''>then</span>
  <span m=''4171040''>we</span> <span m=''4171240''>know</span> <span m=''4171630''>that</span>
  <span m=''4171779''>we</span> <span m=''4171910''>can</span> <span m=''4172069''>canonicalize</span>
  <span m=''4172640''>a</span> <span m=''4173100''>chain,</span> <span m=''4174240''>or</span>
  <span m=''4174380''>there</span> <span m=''4174609''>at</span> <span m=''4174720''>least</span>
  <span m=''4174970''>exists a</span> <span m=''4175420''>canonical</span> <span m=''4175930''>configuration</span>
  <span m=''4176560''>of</span> <span m=''4176649''>the</span> <span m=''4176750''>chain,</span>
  <span m=''4177899''>where</span> <span m=''4178779''>everything</span> <span m=''4179229''>lies</span>
  <span m=''4179569''>inside</span> <span m=''4180000''>a</span> <span m=''4180040''>cone</span>
  <span m=''4180900''>of</span> <span m=''4181220''>half</span> <span m=''4181810''>angle</span>
  <span m=''4182220''>alpha</span> <span m=''4182560''>over</span> <span m=''4182779''>two.</span>
  <span m=''4183830''>Now</span> <span m=''4184040''>the</span> <span m=''4184160''>problem</span>
  <span m=''4184550''>is</span> <span m=''4184840''>that</span> <span m=''4185859''>cone,</span>
  <span m=''4186720''>we</span> <span m=''4186859''>want</span> <span m=''4187109''>it</span>
  <span m=''4187210''>to</span> <span m=''4187310''>be</span> <span m=''4187580''>at</span>
  <span m=''4187720''>a</span> <span m=''4187770''>funny</span> <span m=''4188140''>angle.</span>
  <span m=''4191399''>Let</span> <span m=''4191460''>me</span> <span m=''4191569''>draw</span>
  <span m=''4191970''>a</span> <span m=''4192149''>real</span> <span m=''4192350''>picture.</span>
  </p><p><span m=''4199780''>Here''s</span> <span m=''4199930''>a</span> <span m=''4200000''>ribosome.</span>
  <span m=''4202380''>It has</span> <span m=''4202490''>a</span> <span m=''4202540''>big</span>
  <span m=''4202910''>angle</span> <span m=''4204060''>here.</span> <span m=''4205110''>We''ll
  call</span> <span m=''4205610''>alpha.</span> <span m=''4208120''>Now,</span> <span
  m=''4209190''>I''m</span> <span m=''4209350''>going</span> <span m=''4209470''>to</span>
  <span m=''4209590''>do</span> <span m=''4209720''>the</span> <span m=''4209840''>not</span>
  <span m=''4210130''>extreme</span> <span m=''4210490''>case,</span> <span m=''4211020''>try</span>
  <span m=''4211220''>to</span> <span m=''4211300''>be</span> <span m=''4211420''>a</span>
  <span m=''4211470''>little</span> <span m=''4211630''>more</span> <span m=''4211820''>general.</span>
  <span m=''4213350''>There''s</span> <span m=''4213410''>some</span> <span m=''4213730''>edge</span>
  <span m=''4214320''>that is</span> <span m=''4214570''>currently</span> <span m=''4214930''>entering,</span>
  <span m=''4215490''>and</span> <span m=''4215620''>we</span> <span m=''4215710''>have</span>
  <span m=''4215810''>no</span> <span m=''4216040''>control</span> <span m=''4216560''>over</span>
  <span m=''4216740''>that</span> <span m=''4216980''>edge</span> <span m=''4217290''>or</span>
  <span m=''4217450''>the</span> <span m=''4217590''>rest</span> <span m=''4217880''>of</span>
  <span m=''4217960''>the</span> <span m=''4218050''>chain.</span> <span m=''4220040''>That''s</span>
  <span m=''4220600''>determined</span> <span m=''4221060''>by</span> <span m=''4221180''>the</span>
  <span m=''4221290''>movie</span> <span m=''4221590''>which</span> <span m=''4221770''>we''re</span>
  <span m=''4221850''>trying</span> <span m=''4222050''>to</span> <span m=''4222120''>play</span>
  <span m=''4222280''>backwards.</span> <span m=''4224520''>What</span> <span m=''4225240''>we</span>
  <span m=''4225360''>have</span> <span m=''4225600''>to</span> <span m=''4225710''>control,</span>
  <span m=''4226900''>and</span> <span m=''4226970''>what</span> <span m=''4227060''>we''re</span>
  <span m=''4227180''>free</span> <span m=''4227380''>to</span> <span m=''4227450''>control,</span>
  <span m=''4228220''>is</span> <span m=''4228360''>the</span> <span m=''4228470''>rest</span>
  <span m=''4228730''>of</span> <span m=''4228830''>the</span> <span m=''4228920''>chain</span>
  <span m=''4229340''>because</span> <span m=''4229520''>as</span> <span m=''4229620''>far</span>
  <span m=''4229760''>as</span> <span m=''4229850''>the</span> <span m=''4229920''>movie</span>
  <span m=''4230130''>is</span> <span m=''4230220''>concerned,</span> <span m=''4230530''>that</span>
  <span m=''4230630''>hasn''t</span> <span m=''4230900''>been</span> <span m=''4231190''>created</span>
  <span m=''4231660''>yet</span> <span m=''4231890''>or</span> <span m=''4232860''>it''s</span>
  <span m=''4233030''>already</span> <span m=''4233240''>been</span> <span m=''4233400''>destroyed,</span>
  <span m=''4233950''>depending</span> <span m=''4234350''>on whether</span> <span
  m=''4234460''>you''re</span> <span m=''4234560''>playing</span> <span m=''4234830''>forwards</span>
  <span m=''4235180''>or</span> <span m=''4235240''>backwards.</span> </p><p><span
  m=''4236930''>We</span> <span m=''4237050''>need</span> <span m=''4237230''>to</span>
  <span m=''4237310''>say</span> <span m=''4237460''>what</span> <span m=''4237600''>happens</span>
  <span m=''4237950''>to</span> <span m=''4238080''>it.</span> <span m=''4238230''>And</span>
  <span m=''4238570''>what</span> <span m=''4238790''>I</span> <span m=''4238870''>want</span>
  <span m=''4239180''>to</span> <span m=''4239270''>happen</span> <span m=''4240210''>is</span>
  <span m=''4240380''>so</span> <span m=''4240490''>that</span> <span m=''4240680''>by</span>
  <span m=''4240830''>the</span> <span m=''4240940''>time</span> <span m=''4241180''>this</span>
  <span m=''4241360''>edge</span> <span m=''4241590''>is</span> <span m=''4241710''>inside,</span>
  <span m=''4243530''>that</span> <span m=''4243840''>edge</span> <span m=''4244310''>plus</span>
  <span m=''4244640''>the</span> <span m=''4244740''>rest</span> <span m=''4245100''>is</span>
  <span m=''4245240''>in</span> <span m=''4245360''>the</span> <span m=''4245450''>canonical</span>
  <span m=''4245900''>configuration.</span> <span m=''4247250''>If</span> <span m=''4247380''>I</span>
  <span m=''4247440''>can</span> <span m=''4247570''>achieve</span> <span m=''4247870''>that,</span>
  <span m=''4248180''>then</span> <span m=''4248370''>as</span> <span m=''4248710''>edges</span>
  <span m=''4249030''>come</span> <span m=''4249260''>in</span> <span m=''4249660''>they</span>
  <span m=''4249760''>become</span> <span m=''4250110''>canonicalized,</span> <span
  m=''4250970''>and</span> <span m=''4251070''>then</span> <span m=''4251210''>everything</span>
  <span m=''4251540''>will</span> <span m=''4251640''>be</span> <span m=''4251780''>canonical</span>
  <span m=''4252370''>and</span> <span m=''4252550''>inside</span> <span m=''4252850''>the</span>
  <span m=''4252930''>cone and</span> <span m=''4253190''>we''re</span> <span m=''4253300''>done.</span>
  <span m=''4254490''>That''s our</span> <span m=''4254775''>goal.</span> <span m=''4256370''>Canonicalization.</span>
  <span m=''4257120''>So,</span> <span m=''4259360''>what''s</span> <span m=''4259650''>the</span>
  <span m=''4259740''>deal?</span> </p><p><span m=''4260290''>Well,</span> <span m=''4260930''>in</span>
  <span m=''4261100''>reality,</span> <span m=''4262900''>there''s</span> <span m=''4263130''>some</span>
  <span m=''4263390''>cone--</span> <span m=''4266761''>yeah,</span> <span m=''4267240''>it</span>
  <span m=''4267320''>can</span> <span m=''4267450''>penetrate</span> <span m=''4267930''>like</span>
  <span m=''4268130''>that--</span> <span m=''4269240''>could</span> <span m=''4269430''>penetrate</span>
  <span m=''4270010''>the</span> <span m=''4270160''>outside</span> <span m=''4270560''>cone.</span>
  <span m=''4271550''>This is</span> <span m=''4272540''>getting</span> <span m=''4272890''>messy.</span>
  <span m=''4275790''>So</span> <span m=''4275830''>if</span> <span m=''4275930''>I</span>
  <span m=''4275980''>extend</span> <span m=''4276400''>this</span> <span m=''4276590''>line,</span>
  <span m=''4279710''>there''s</span> <span m=''4279960''>a</span> <span m=''4280020''>cone</span>
  <span m=''4280340''>of</span> <span m=''4280420''>half</span> <span m=''4280700''>angle</span>
  <span m=''4280950''>here,</span> <span m=''4281300''>which</span> <span m=''4281360''>is</span>
  <span m=''4281440''>equal</span> <span m=''4281700''>to</span> <span m=''4281840''>whatever</span>
  <span m=''4282120''>the</span> <span m=''4282230''>turn</span> <span m=''4282500''>angle</span>
  <span m=''4282840''>is</span> <span m=''4285540''>at</span> <span m=''4285920''>that</span>
  <span m=''4286250''>vertex,</span> <span m=''4286830''>which</span> <span m=''4286900''>is,</span>
  <span m=''4287010''>again,</span> <span m=''4287260''>specified.</span> <span m=''4288780''>We''re</span>
  <span m=''4288920''>not</span> <span m=''4289160''>free</span> <span m=''4289400''>to</span>
  <span m=''4289690''>set</span> <span m=''4289930''>it</span> <span m=''4290040''>to</span>
  <span m=''4290140''>whatever</span> <span m=''4290420''>we</span> <span m=''4290480''>want.</span>
  <span m=''4291180''>We</span> <span m=''4291270''>know</span> <span m=''4291440''>the</span>
  <span m=''4291540''>next</span> <span m=''4291800''>edge</span> <span m=''4291980''>must</span>
  <span m=''4292470''>lie</span> <span m=''4293060''>on</span> <span m=''4293290''>this</span>
  <span m=''4293480''>cone.</span> <span m=''4296460''>What</span> <span m=''4296710''>I</span>
  <span m=''4296790''>do--</span> <span m=''4301380''>now,</span> <span m=''4302290''>on</span>
  <span m=''4302490''>the</span> <span m=''4302590''>other</span> <span m=''4302740''>hand,</span>
  <span m=''4303670''>off</span> <span m=''4303860''>to</span> <span m=''4303970''>the</span>
  <span m=''4304060''>side,</span> <span m=''4304540''>I</span> <span m=''4304640''>have</span>
  <span m=''4304860''>in</span> <span m=''4304930''>mind</span> <span m=''4305320''>a</span>
  <span m=''4305350''>vertical</span> <span m=''4305820''>cone</span> <span m=''4306700''>whose</span>
  <span m=''4306940''>half</span> <span m=''4307210''>angle</span> <span m=''4307530''>is</span>
  <span m=''4307790''>alpha</span> <span m=''4308070''>over</span> <span m=''4308320''>two.</span>
  <span m=''4308900''>So</span> <span m=''4309040''>it''s</span> <span m=''4309150''>quite</span>
  <span m=''4309420''>small.</span> <span m=''4311310''>And</span> <span m=''4311500''>I</span>
  <span m=''4311580''>know--</span> <span m=''4313324''>how</span> <span m=''4313760''>do</span>
  <span m=''4313830''>we</span> <span m=''4313930''>do</span> <span m=''4314030''>it--</span>
  <span m=''4314130''>initially,</span> <span m=''4315290''>the</span> <span m=''4315400''>first</span>
  <span m=''4315680''>edge</span> <span m=''4315900''>was</span> <span m=''4316060''>along</span>
  <span m=''4316480''>the</span> <span m=''4317170''>maximum</span> <span m=''4317740''>x</span>
  <span m=''4318470''>direction,</span> <span m=''4318970''>and</span> <span m=''4319080''>then</span>
  <span m=''4319260''>it</span> <span m=''4319770''>spirals</span> <span m=''4320200''>up</span>
  <span m=''4320330''>from</span> <span m=''4320490''>there.</span> <span m=''4323380''>OK.</span>
  </p><p><span m=''4326290''>Here''s</span> <span m=''4326520''>what</span> <span
  m=''4326650''>I''m</span> <span m=''4326750''>going</span> <span m=''4326860''>to</span>
  <span m=''4326950''>do.</span> <span m=''4327880''>There</span> <span m=''4328030''>are</span>
  <span m=''4328090''>sort</span> <span m=''4328270''>of</span> <span m=''4328360''>two</span>
  <span m=''4328530''>situations.</span> <span m=''4329940''>What</span> <span m=''4330170''>I''d</span>
  <span m=''4330270''>like</span> <span m=''4330500''>to</span> <span m=''4330640''>do</span>
  <span m=''4331460''>is</span> <span m=''4331830''>put</span> <span m=''4332030''>a</span>
  <span m=''4332100''>cone</span> <span m=''4332640''>here</span> <span m=''4333940''>that</span>
  <span m=''4334200''>is</span> <span m=''4335070''>vertical.</span> <span m=''4337660''>Something</span>
  <span m=''4337960''>like</span> <span m=''4338140''>that.</span> <span m=''4340010''>Just</span>
  <span m=''4340260''>like</span> <span m=''4340420''>I</span> <span m=''4340510''>have</span>
  <span m=''4340740''>here.</span> <span m=''4341590''>The</span> <span m=''4341750''>trouble</span>
  <span m=''4342120''>is,</span> <span m=''4342310''>the</span> <span m=''4342460''>right</span>
  <span m=''4342840''>side</span> <span m=''4343250''>of</span> <span m=''4343360''>this</span>
  <span m=''4343560''>cone</span> <span m=''4344780''>does</span> <span m=''4344960''>not</span>
  <span m=''4345210''>intersect</span> <span m=''4345770''>the</span> <span m=''4345860''>boundary</span>
  <span m=''4346280''>of</span> <span m=''4346360''>this</span> <span m=''4346540''>cone.</span>
  <span m=''4346870''>And</span> <span m=''4347050''>need it</span> <span m=''4347390''>to</span>
  <span m=''4347610''>in</span> <span m=''4347710''>order</span> <span m=''4347880''>to</span>
  <span m=''4347950''>form</span> <span m=''4348180''>the</span> <span m=''4348250''>right</span>
  <span m=''4348420''>angle</span> <span m=''4348690''>here.</span> <span m=''4349060''>It''s</span>
  <span m=''4349230''>going</span> <span m=''4349340''>to--</span> <span m=''4349600''>it</span>
  <span m=''4349850''>might</span> <span m=''4350050''>go</span> <span m=''4350180''>through</span>
  <span m=''4350330''>the</span> <span m=''4350410''>middle</span> <span m=''4350640''>of</span>
  <span m=''4350740''>the</span> <span m=''4350840''>cone</span> <span m=''4351070''>like</span>
  <span m=''4351430''>it</span> <span m=''4351590''>does</span> <span m=''4351750''>here.</span>
  <span m=''4352670''>So</span> <span m=''4352710''>then</span> <span m=''4352840''>what</span>
  <span m=''4352940''>I</span> <span m=''4353020''>do</span> <span m=''4353130''>is</span>
  <span m=''4353230''>I</span> <span m=''4353290''>take</span> <span m=''4353510''>this</span>
  <span m=''4353660''>canonical</span> <span m=''4354080''>configuration</span> <span
  m=''4354690''>and</span> <span m=''4354860''>I</span> <span m=''4354920''>rotate</span>
  <span m=''4355440''>it</span> <span m=''4356500''>so</span> <span m=''4356830''>that--</span>
  <span m=''4357750''>this</span> <span m=''4358010''>is</span> <span m=''4358670''>hard</span>
  <span m=''4358900''>to</span> <span m=''4358980''>draw--</span> <span m=''4361000''>it''ll</span>
  <span m=''4361240''>be</span> <span m=''4361370''>something</span> <span m=''4361720''>like</span>
  <span m=''4361990''>this.</span> <span m=''4365180''>There''s</span> <span m=''4365320''>no</span>
  <span m=''4365450''>hope of</span> <span m=''4365620''>seeing</span> <span m=''4365960''>this.</span>
  </p><p><span m=''4367690''>So</span> <span m=''4367840''>it''s</span> <span m=''4368090''>on</span>
  <span m=''4368320''>the</span> <span m=''4368410''>surface</span> <span m=''4368830''>of</span>
  <span m=''4368920''>this</span> <span m=''4369110''>cone.</span> <span m=''4369420''>It''s</span>
  <span m=''4369550''>not on</span> <span m=''4369820''>the</span> <span m=''4369890''>far</span>
  <span m=''4370190''>right</span> <span m=''4370410''>edge.</span> <span m=''4370720''>It''s</span>
  <span m=''4370890''>going</span> <span m=''4371030''>to</span> <span m=''4371100''>be</span>
  <span m=''4371260''>some</span> <span m=''4372050''>intermediate</span> <span m=''4372590''>point.</span>
  <span m=''4373420''>And</span> <span m=''4374010''>that''s</span> <span m=''4374220''>exactly</span>
  <span m=''4374620''>where</span> <span m=''4374750''>it</span> <span m=''4374790''>intersects</span>
  <span m=''4375260''>this</span> <span m=''4375430''>cone.</span> <span m=''4375690''>It''s</span>
  <span m=''4376050''>just</span> <span m=''4376270''>like</span> <span m=''4376410''>the</span>
  <span m=''4376500''>previous</span> <span m=''4376820''>picture,</span> <span m=''4377130''>just</span>
  <span m=''4377340''>harder</span> <span m=''4377580''>to</span> <span m=''4377670''>see.</span>
  <span m=''4378890''>I''m</span> <span m=''4379030''>taking</span> <span m=''4379260''>the</span>
  <span m=''4379340''>intersection</span> <span m=''4379850''>of</span> <span m=''4379940''>these</span>
  <span m=''4380110''>two</span> <span m=''4380260''>cones.</span> <span m=''4381120''>If</span>
  <span m=''4381230''>I</span> <span m=''4381300''>just</span> <span m=''4381470''>rotate</span>
  <span m=''4381880''>the</span> <span m=''4381950''>picture,</span> <span m=''4382810''>then</span>
  <span m=''4383030''>it</span> <span m=''4383090''>will</span> <span m=''4383230''>lie
  in the</span> <span m=''4383490''>intersection--</span> <span m=''4384370''>if</span>
  <span m=''4384560''>they</span> <span m=''4384700''>intersect.</span> <span m=''4386480''>But</span>
  <span m=''4386910''>they</span> <span m=''4387000''>might</span> <span m=''4387210''>not</span>
  <span m=''4387380''>intersect.</span> <span m=''4390750''>So</span> <span m=''4391140''>let</span>
  <span m=''4391390''>me</span> <span m=''4391920''>go</span> <span m=''4392190''>here</span>
  <span m=''4393516''>and</span> <span m=''4393910''>try</span> <span m=''4394205''>it</span>
  <span m=''4394500''>again.</span> </p><p><span m=''4399270''>So</span> <span m=''4399330''>the</span>
  <span m=''4399500''>easy</span> <span m=''4399810''>case</span> <span m=''4400870''>is</span>
  <span m=''4401040''>when</span> <span m=''4401200''>I</span> <span m=''4401260''>can</span>
  <span m=''4401430''>draw</span> <span m=''4401620''>a</span> <span m=''4401650''>vertical</span>
  <span m=''4402060''>cone</span> <span m=''4402720''>and</span> <span m=''4402900''>it</span>
  <span m=''4403030''>intersects</span> <span m=''4403590''>the</span> <span m=''4404390''>cone
  that</span> <span m=''4404710''>I</span> <span m=''4404760''>need</span> <span m=''4404960''>to</span>
  <span m=''4405020''>intersect.</span> <span m=''4407480''>The</span> <span m=''4407780''>harder</span>
  <span m=''4408260''>case</span> <span m=''4409610''>is--</span> <span m=''4410890''>maybe</span>
  <span m=''4411130''>it''s</span> <span m=''4411250''>more</span> <span m=''4411470''>extreme.</span>
  <span m=''4413950''>Maybe</span> <span m=''4414400''>it''s</span> <span m=''4414550''>a</span>
  <span m=''4414640''>very</span> <span m=''4415150''>tight</span> <span m=''4415470''>angle</span>
  <span m=''4415770''>here.</span> <span m=''4418690''>So</span> <span m=''4418910''>there''s</span>
  <span m=''4419110''>a</span> <span m=''4419270''>very</span> <span m=''4419680''>small</span>
  <span m=''4420100''>turn</span> <span m=''4420300''>angle.</span> <span m=''4421390''>I</span>
  <span m=''4421450''>have</span> <span m=''4421620''>to</span> <span m=''4421690''>intersect</span>
  <span m=''4422050''>this</span> <span m=''4422200''>cone.</span> <span m=''4422740''>Because</span>
  <span m=''4423370''>the cone</span> <span m=''4423790''>that</span> <span m=''4423900''>I''m</span>
  <span m=''4424030''>working</span> <span m=''4424370''>with</span> <span m=''4424590''>is</span>
  <span m=''4424810''>actually</span> <span m=''4425100''>smaller--</span> <span m=''4426980''>it''s</span>
  <span m=''4427180''>half</span> <span m=''4428120''>of</span> <span m=''4428210''>this</span>
  <span m=''4429730''>angle--</span> <span m=''4430580''>it</span> <span m=''4430690''>might</span>
  <span m=''4430890''>not</span> <span m=''4431050''>intersect</span> <span m=''4431410''>this</span>
  <span m=''4431570''>cone.</span> <span m=''4431790''>In</span> <span m=''4431900''>that</span>
  <span m=''4432110''>case,</span> <span m=''4433070''>I''m</span> <span m=''4433230''>going</span>
  <span m=''4433440''>to</span> <span m=''4433790''>rotate</span> <span m=''4434200''>the</span>
  <span m=''4434310''>cone</span> <span m=''4434950''>to</span> <span m=''4435360''>fall</span>
  <span m=''4435760''>over</span> <span m=''4435990''>a</span> <span m=''4436040''>little</span>
  <span m=''4436220''>bit.</span> <span m=''4439740''>So</span> <span m=''4439900''>instead</span>
  <span m=''4440150''>of</span> <span m=''4440210''>being</span> <span m=''4440360''>like</span>
  <span m=''4440530''>that,</span> <span m=''4440790''>it''s</span> <span m=''4441000''>going</span>
  <span m=''4441140''>to</span> <span m=''4441210''>be</span> <span m=''4441620''>like</span>
  <span m=''4441910''>this.</span> <span m=''4448190''>OK.</span> </p><p><span m=''4448370''>So</span>
  <span m=''4448490''>I</span> <span m=''4448540''>want</span> <span m=''4449310''>the</span>
  <span m=''4449500''>intersection</span> <span m=''4449990''>of</span> <span m=''4450030''>these</span>
  <span m=''4450190''>two</span> <span m=''4450310''>cones,</span> <span m=''4450630''>which</span>
  <span m=''4450780''>I''ve</span> <span m=''4450930''>conveniently</span> <span m=''4451420''>made</span>
  <span m=''4452410''>this</span> <span m=''4453180''>edge</span> <span m=''4453460''>here.</span>
  <span m=''4455280''>So</span> <span m=''4455430''>the</span> <span m=''4455530''>first</span>
  <span m=''4455810''>edge</span> <span m=''4455960''>will</span> <span m=''4456210''>lie</span>
  <span m=''4456480''>along</span> <span m=''4456630''>here,</span> <span m=''4457040''>and
  then</span> <span m=''4457070''>it''s</span> <span m=''4457240''>going</span> <span
  m=''4457330''>to</span> <span m=''4457380''>spiral out</span> <span m=''4457860''>from</span>
  <span m=''4458050''>there.</span> <span m=''4458920''>So</span> <span m=''4459110''>I</span>
  <span m=''4459190''>still have</span> <span m=''4459470''>the</span> <span m=''4459550''>canonical</span>
  <span m=''4459980''>configuration.</span> <span m=''4460280''>I''ve</span> <span
  m=''4460580''>just</span> <span m=''4460810''>tilted</span> <span m=''4461130''>it.</span>
  <span m=''4462900''>Tilting</span> <span m=''4463260''>is</span> <span m=''4463400''>going</span>
  <span m=''4463670''>to</span> <span m=''4463770''>be</span> <span m=''4463900''>necessary</span>
  <span m=''4464600''>because</span> <span m=''4464970''>I</span> <span m=''4465030''>have</span>
  <span m=''4465230''>this</span> <span m=''4465380''>angle</span> <span m=''4465720''>to</span>
  <span m=''4465830''>match</span> <span m=''4466120''>up.</span> <span m=''4467000''>The</span>
  <span m=''4467140''>convenient</span> <span m=''4467770''>thing</span> <span m=''4468870''>about</span>
  <span m=''4469310''>the</span> <span m=''4469410''>canonical--</span> <span m=''4470530''>the</span>
  <span m=''4470980''>alpha</span> <span m=''4471270''>CCC,</span> <span m=''4472710''>canonical</span>
  <span m=''4472850''>configuration--</span> <span m=''4474230''>is</span> <span m=''4474460''>that</span>
  <span m=''4475270''>I</span> <span m=''4475450''>have</span> <span m=''4475740''>this</span>
  <span m=''4476390''>half</span> <span m=''4476630''>angle of</span> <span m=''4477010''>alpha</span>
  <span m=''4477370''>over</span> <span m=''4477630''>two,</span> <span m=''4478940''>so</span>
  <span m=''4479090''>I</span> <span m=''4479180''>can</span> <span m=''4479360''>afford</span>
  <span m=''4479750''>to</span> <span m=''4479860''>tilt</span> <span m=''4480220''>it</span>
  <span m=''4480900''>by</span> <span m=''4481060''>up</span> <span m=''4481320''>to</span>
  <span m=''4481570''>alpha</span> <span m=''4481920''>over</span> <span m=''4482130''>two.</span>
  <span m=''4483800''>It</span> <span m=''4483920''>will</span> <span m=''4484060''>still</span>
  <span m=''4484340''>stay</span> <span m=''4484690''>within</span> <span m=''4485310''>the</span>
  <span m=''4485460''>ribosome,</span> <span m=''4486040''>which</span> <span m=''4486210''>is</span>
  <span m=''4486350''>of</span> <span m=''4487310''>half</span> <span m=''4487640''>angle</span>
  <span m=''4487920''>alpha.</span> </p><p><span m=''4489570''>And</span> <span m=''4490220''>all</span>
  <span m=''4490420''>I</span> <span m=''4490480''>need</span> <span m=''4490730''>to</span>
  <span m=''4490830''>show</span> <span m=''4491120''>here--</span> <span m=''4491610''>and</span>
  <span m=''4492690''>once</span> <span m=''4492850''>you</span> <span m=''4493820''>think</span>
  <span m=''4493970''>about</span> <span m=''4494200''>it</span> <span m=''4494340''>for
  a</span> <span m=''4494440''>while,</span> <span m=''4494620''>it''s</span> <span
  m=''4495040''>obvious--</span> <span m=''4495610''>that</span> <span m=''4496990''>ideally,</span>
  <span m=''4497690''>I</span> <span m=''4497770''>don''t</span> <span m=''4497980''>tilt
  it at</span> <span m=''4498390''>all.</span> <span m=''4498860''>I''ve got</span>
  <span m=''4499050''>tons</span> <span m=''4499330''>of</span> <span m=''4499420''>room.</span>
  <span m=''4499840''>Huge</span> <span m=''4500160''>amount</span> <span m=''4500370''>of</span>
  <span m=''4500450''>room</span> <span m=''4500600''>here.</span> <span m=''4501600''>But</span>
  <span m=''4501800''>sometimes</span> <span m=''4502220''>I''ll</span> <span m=''4502290''>have</span>
  <span m=''4502460''>to</span> <span m=''4502580''>tilt</span> <span m=''4502860''>it,</span>
  <span m=''4503340''>but</span> <span m=''4503690''>by at</span> <span m=''4503770''>most</span>
  <span m=''4504050''>alpha</span> <span m=''4504330''>over</span> <span m=''4504530''>two.</span>
  <span m=''4504830''>So</span> <span m=''4505000''>I</span> <span m=''4505110''>will</span>
  <span m=''4505240''>stay</span> <span m=''4505600''>inside</span> <span m=''4506760''>the</span>
  <span m=''4506860''>ribosome,</span> <span m=''4507300''>because</span> <span m=''4507480''>this</span>
  <span m=''4507670''>apex</span> <span m=''4508180''>was</span> <span m=''4508480''>inside</span>
  <span m=''4508880''>the</span> <span m=''4508970''>cone</span> <span m=''4509830''>and</span>
  <span m=''4510050''>the</span> <span m=''4510140''>smaller</span> <span m=''4510630''>cone,</span>
  <span m=''4511210''>even</span> <span m=''4511430''>if</span> <span m=''4511550''>I</span>
  <span m=''4511630''>tilt</span> <span m=''4512020''>it</span> <span m=''4512210''>all</span>
  <span m=''4512440''>the</span> <span m=''4512530''>way</span> <span m=''4513380''>to</span>
  <span m=''4513540''>meet</span> <span m=''4513840''>this</span> <span m=''4514020''>edge,</span>
  <span m=''4516160''>it</span> <span m=''4516280''>will</span> <span m=''4516380''>stay</span>
  <span m=''4516540''>inside</span> <span m=''4516830''>the</span> <span m=''4516900''>cone.</span>
  <span m=''4517090''>In</span> <span m=''4517180''>fact,</span> <span m=''4518410''>it''ll</span>
  <span m=''4518490''>stay</span> <span m=''4518640''>inside</span> <span m=''4518910''>the</span>
  <span m=''4518980''>big</span> <span m=''4519180''>cone.</span> <span m=''4519430''>In</span>
  <span m=''4519510''>fact,</span> <span m=''4519800''>this</span> <span m=''4519980''>cone</span>
  <span m=''4520610''>that</span> <span m=''4520760''>I</span> <span m=''4521000''>tilt--</span>
  <span m=''4521920''>the</span> <span m=''4522020''>one</span> <span m=''4522140''>that</span>
  <span m=''4522220''>contains</span> <span m=''4522730''>the</span> <span m=''4522840''>rest</span>
  <span m=''4523080''>of</span> <span m=''4523140''>the</span> <span m=''4523250''>canonical</span>
  <span m=''4523690''>configuration--</span> <span m=''4524560''>will</span> <span
  m=''4524820''>always</span> <span m=''4525170''>contain</span> <span m=''4526240''>the</span>
  <span m=''4527100''>up</span> <span m=''4527300''>direction.</span> <span m=''4529840''>That''s</span>
  <span m=''4530110''>how</span> <span m=''4530220''>to</span> <span m=''4530310''>see</span>
  <span m=''4530510''>it.</span> </p><p><span m=''4531790''>If</span> <span m=''4531890''>it</span>
  <span m=''4532060''>always</span> <span m=''4532240''>contains</span> <span m=''4532550''>the</span>
  <span m=''4532670''>up</span> <span m=''4532810''>direction,</span> <span m=''4533670''>then</span>
  <span m=''4533830''>at</span> <span m=''4533930''>most,</span> <span m=''4534950''>it''s</span>
  <span m=''4535120''>that</span> <span m=''4535380''>big.</span> <span m=''4537160''>And</span>
  <span m=''4537430''>that</span> <span m=''4537640''>will--</span> <span m=''4538890''>because</span>
  <span m=''4540560''>that''s</span> <span m=''4540750''>an</span> <span m=''4540860''>angle</span>
  <span m=''4541190''>of</span> <span m=''4541310''>alpha</span> <span m=''4542150''>because</span>
  <span m=''4542330''>that</span> <span m=''4542380''>was</span> <span m=''4542530''>the</span>
  <span m=''4542580''>half</span> <span m=''4542850''>angle</span> <span m=''4543050''>of</span>
  <span m=''4543150''>the</span> <span m=''4543220''>big</span> <span m=''4543410''>cone.</span>
  <span m=''4544370''>So</span> <span m=''4544460''>that will be a</span> <span m=''4544770''>half</span>
  <span m=''4545080''>angle</span> <span m=''4545590''>of</span> <span m=''4545710''>alpha</span>
  <span m=''4545950''>over</span> <span m=''4546150''>two.</span> <span m=''4546850''>As</span>
  <span m=''4546900''>long</span> <span m=''4547110''>as</span> <span m=''4547170''>you</span>
  <span m=''4547290''>contain</span> <span m=''4547760''>the</span> <span m=''4547920''>up</span>
  <span m=''4548100''>direction</span> <span m=''4548570''>at all</span> <span m=''4548780''>times,</span>
  <span m=''4549630''>you</span> <span m=''4549770''>will</span> <span m=''4549850''>not</span>
  <span m=''4550100''>fall</span> <span m=''4550280''>outside</span> <span m=''4550620''>the</span>
  <span m=''4550680''>big</span> <span m=''4550850''>cone.</span> <span m=''4553140''>So</span>
  <span m=''4555720''>the</span> <span m=''4555830''>rest</span> <span m=''4556080''>is</span>
  <span m=''4556160''>just</span> <span m=''4556350''>momento.</span> <span m=''4556810''>So</span>
  <span m=''4557280''>you</span> <span m=''4557470''>play</span> <span m=''4557840''>this</span>
  <span m=''4558170''>movie</span> <span m=''4558440''>backwards.</span> <span m=''4559420''>As</span>
  <span m=''4559710''>things</span> <span m=''4559970''>come in</span> <span m=''4560340''>here,</span>
  <span m=''4562060''>this</span> <span m=''4562330''>cone</span> <span m=''4562690''>is</span>
  <span m=''4562830''>going</span> <span m=''4562970''>to</span> <span m=''4563130''>wiggle</span>
  <span m=''4563460''>back</span> <span m=''4563700''>and</span> <span m=''4563800''>forth,</span>
  <span m=''4564250''>depending</span> <span m=''4564650''>on</span> <span m=''4564710''>how</span>
  <span m=''4564890''>this</span> <span m=''4565070''>angle</span> <span m=''4565360''>changes.</span>
  <span m=''4566990''>Once</span> <span m=''4567310''>the</span> <span m=''4567440''>edge</span>
  <span m=''4567670''>gets</span> <span m=''4567840''>all</span> <span m=''4568030''>the</span>
  <span m=''4568110''>way</span> <span m=''4568330''>in,</span> <span m=''4569200''>you</span>
  <span m=''4569440''>absorb</span> <span m=''4569920''>it</span> <span m=''4570020''>into</span>
  <span m=''4570250''>the</span> <span m=''4570380''>canonical</span> <span m=''4570850''>configuration.</span>
  </p><p><span m=''4571780''>Little</span> <span m=''4572060''>bit</span> <span m=''4572180''>of</span>
  <span m=''4572250''>work</span> <span m=''4572480''>there</span> <span m=''4572640''>but</span>
  <span m=''4572780''>you</span> <span m=''4572880''>just</span> <span m=''4573020''>sort</span>
  <span m=''4573150''>of</span> <span m=''4573340''>twist</span> <span m=''4573630''>the</span>
  <span m=''4573710''>cone</span> <span m=''4573980''>around</span> <span m=''4574870''>until</span>
  <span m=''4576250''>that</span> <span m=''4576510''>algorithm</span> <span m=''4576795''>that</span>
  <span m=''4577080''>we</span> <span m=''4577100''>described</span> <span m=''4577480''>for</span>
  <span m=''4577590''>producing</span> <span m=''4577970''>canonical</span> <span
  m=''4578440''>configuration</span> <span m=''4579040''>would</span> <span m=''4579230''>actually</span>
  <span m=''4579540''>produce</span> <span m=''4579880''>what''s</span> <span m=''4580080''>inside</span>
  <span m=''4580470''>the</span> <span m=''4580550''>cone.</span> <span m=''4581370''>Then</span>
  <span m=''4581560''>the</span> <span m=''4581650''>next</span> <span m=''4581900''>edge</span>
  <span m=''4582080''>comes</span> <span m=''4582350''>in,</span> <span m=''4582730''>cone</span>
  <span m=''4583110''>wiggles</span> <span m=''4583390''>around</span> <span m=''4584100''>until</span>
  <span m=''4584310''>the</span> <span m=''4584430''>edge</span> <span m=''4584610''>gets</span>
  <span m=''4584780''>all</span> <span m=''4584930''>the</span> <span m=''4584990''>way</span>
  <span m=''4585150''>in,</span> <span m=''4585410''>then</span> <span m=''4585560''>you</span>
  <span m=''4585970''>canonicalize</span> <span m=''4586630''>what''s</span> <span
  m=''4586810''>inside</span> <span m=''4587100''>the</span> <span m=''4587190''>cone,</span>
  <span m=''4587890''>and</span> <span m=''4588020''>repeat.</span> <span m=''4589370''>So</span>
  <span m=''4589850''>if</span> <span m=''4590060''>you</span> <span m=''4590160''>had</span>
  <span m=''4590340''>a</span> <span m=''4590390''>way</span> <span m=''4590550''>to</span>
  <span m=''4590630''>get</span> <span m=''4590810''>it</span> <span m=''4590910''>out,</span>
  <span m=''4591430''>you</span> <span m=''4591550''>could</span> <span m=''4591680''>put</span>
  <span m=''4591850''>it</span> <span m=''4591920''>back</span> <span m=''4592160''>in</span>
  <span m=''4592450''>and</span> <span m=''4592760''>keep</span> <span m=''4592960''>track</span>
  <span m=''4593330''>of</span> <span m=''4593430''>all</span> <span m=''4593560''>the</span>
  <span m=''4593620''>stuff</span> <span m=''4593850''>that</span> <span m=''4593950''>happens</span>
  <span m=''4594300''>on</span> <span m=''4594390''>the</span> <span m=''4594490''>inside.</span>
  <span m=''4595900''>That''s</span> <span m=''4596120''>what</span> <span m=''4596220''>this</span>
  <span m=''4596390''>theorem</span> <span m=''4596610''>says.</span> <span m=''4598180''>And</span>
  <span m=''4598440''>then</span> <span m=''4598640''>there''s</span> <span m=''4598810''>just</span>
  <span m=''4599400''>slightly</span> <span m=''4599790''>more</span> <span m=''4600960''>to</span>
  <span m=''4601210''>say.</span> </p><p><span m=''4603290''>If</span> <span m=''4603480''>you</span>
  <span m=''4603590''>have</span> <span m=''4603810''>a</span> <span m=''4603870''>flat</span>
  <span m=''4604290''>state,</span> <span m=''4609820''>we</span> <span m=''4609940''>want</span>
  <span m=''4610110''>to</span> <span m=''4610170''>prove</span> <span m=''4610410''>these</span>
  <span m=''4610580''>things</span> <span m=''4610810''>are</span> <span m=''4610890''>flat</span>
  <span m=''4611180''>state</span> <span m=''4611340''>connected.</span> <span m=''4612680''>So</span>
  <span m=''4612920''>take</span> <span m=''4613200''>some</span> <span m=''4613420''>flat</span>
  <span m=''4613780''>state--</span> <span m=''4615550''>I</span> <span m=''4615680''>really</span>
  <span m=''4615900''>should</span> <span m=''4616050''>have</span> <span m=''4616270''>only</span>
  <span m=''4616530''>obtuse</span> <span m=''4616870''>angles.</span> <span m=''4619220''>I</span>
  <span m=''4619350''>claim</span> <span m=''4619630''>this</span> <span m=''4619780''>flat
  state</span> <span m=''4620260''>can</span> <span m=''4620490''>be</span> <span
  m=''4620620''>produced</span> <span m=''4621340''>using</span> <span m=''4622100''>a</span>
  <span m=''4622240''>cone of</span> <span m=''4623450''>the</span> <span m=''4623670''>appropriate</span>
  <span m=''4624180''>angle.</span> <span m=''4625210''>If</span> <span m=''4625620''>the</span>
  <span m=''4625790''>sharpest</span> <span m=''4626220''>turn</span> <span m=''4626420''>angle</span>
  <span m=''4626660''>here</span> <span m=''4626900''>is</span> <span m=''4627000''>alpha,</span>
  <span m=''4627370''>then</span> <span m=''4627530''>you</span> <span m=''4627610''>need</span>
  <span m=''4627770''>an</span> <span m=''4627870''>alpha</span> <span m=''4628180''>cone.</span>
  <span m=''4629970''>And</span> <span m=''4630330''>the</span> <span m=''4630420''>way</span>
  <span m=''4630530''>to</span> <span m=''4630610''>think</span> <span m=''4630800''>about</span>
  <span m=''4631030''>that</span> <span m=''4631310''>is</span> <span m=''4631510''>to</span>
  <span m=''4631670''>think</span> <span m=''4631860''>of</span> <span m=''4631960''>the</span>
  <span m=''4632080''>cone</span> <span m=''4632470''>moving</span> <span m=''4633290''>instead</span>
  <span m=''4633700''>of</span> <span m=''4634420''>as</span> <span m=''4634730''>the</span>
  <span m=''4635690''>chain</span> <span m=''4635990''>moving.</span> <span m=''4637110''>It''s
  a</span> <span m=''4637160''>lot</span> <span m=''4637380''>easier.</span> <span
  m=''4637790''>So</span> <span m=''4637970''>you</span> <span m=''4638240''>want</span>
  <span m=''4638520''>the</span> <span m=''4638610''>chain</span> <span m=''4638930''>to</span>
  <span m=''4639040''>lie</span> <span m=''4639250''>around</span> <span m=''4639520''>here.</span>
  </p><p><span m=''4640560''>So</span> <span m=''4640610''>you</span> <span m=''4640740''>start</span>
  <span m=''4641130''>by</span> <span m=''4642960''>moving</span> <span m=''4643340''>the</span>
  <span m=''4643450''>cone,</span> <span m=''4645690''>I</span> <span m=''4645750''>guess</span>
  <span m=''4645970''>like</span> <span m=''4646120''>this.</span> <span m=''4647500''>So</span>
  <span m=''4647590''>that it</span> <span m=''4647800''>just</span> <span m=''4648020''>barely</span>
  <span m=''4648370''>touches</span> <span m=''4648740''>the</span> <span m=''4648830''>plane,</span>
  <span m=''4649790''>and</span> <span m=''4650410''>this</span> <span m=''4650640''>edge</span>
  <span m=''4650880''>spews</span> <span m=''4651210''>out.</span> <span m=''4653470''>Is
  that</span> <span m=''4653600''>the</span> <span m=''4653690''>right</span> <span
  m=''4653850''>way</span> <span m=''4653930''>to</span> <span m=''4654020''>think</span>
  <span m=''4654180''>about</span> <span m=''4654410''>it?</span> <span m=''4654863''>I</span>
  <span m=''4655256''>don''t know.</span> <span m=''4655650''>Should</span> <span
  m=''4655830''>be</span> <span m=''4655960''>like</span> <span m=''4656150''>this.</span>
  <span m=''4657020''>So</span> <span m=''4657180''>you</span> <span m=''4657590''>take</span>
  <span m=''4657810''>the</span> <span m=''4657900''>cone.</span> <span m=''4658780''>This</span>
  <span m=''4659190''>is</span> <span m=''4659310''>like</span> <span m=''4659740''>putting</span>
  <span m=''4660240''>frosting</span> <span m=''4660730''>on</span> <span m=''4660800''>a</span>
  <span m=''4660870''>cake.</span> <span m=''4661740''>So</span> <span m=''4662080''>you</span>
  <span m=''4662240''>move</span> <span m=''4662450''>your</span> <span m=''4662570''>cone</span>
  <span m=''4662800''>like</span> <span m=''4663000''>here.</span> <span m=''4663480''>You</span>
  <span m=''4663600''>squirt</span> <span m=''4664020''>out</span> <span m=''4664360''>some--</span>
  <span m=''4665540''>this</span> <span m=''4666280''>edge.</span> <span m=''4667920''>Then,</span>
  <span m=''4670320''>you</span> <span m=''4670510''>do</span> <span m=''4670720''>it</span>
  <span m=''4670890''>so</span> <span m=''4671080''>that</span> <span m=''4671250''>when</span>
  <span m=''4671400''>you''re</span> <span m=''4671530''>here</span> <span m=''4671910''>and</span>
  <span m=''4671980''>the</span> <span m=''4672060''>new</span> <span m=''4672210''>edge
  is</span> <span m=''4672500''>created,</span> <span m=''4674110''>it''s</span> <span
  m=''4674330''>still</span> <span m=''4674530''>in</span> <span m=''4674620''>the</span>
  <span m=''4674700''>plane.</span> <span m=''4676120''>And</span> <span m=''4676330''>then</span>
  <span m=''4676560''>you</span> <span m=''4676880''>just</span> <span m=''4677020''>sort</span>
  <span m=''4677190''>of</span> <span m=''4677360''>move</span> <span m=''4677900''>around</span>
  <span m=''4678280''>there.</span> <span m=''4678550''>I''m</span> <span m=''4678850''>just</span>
  <span m=''4679050''>going to</span> <span m=''4679350''>leave it as</span> <span
  m=''4679420''>a</span> <span m=''4679560''>sketch</span> <span m=''4679920''>like</span>
  <span m=''4680080''>that.</span> </p><p><span m=''4681970''>Once</span> <span m=''4682190''>you</span>
  <span m=''4682290''>know</span> <span m=''4682420''>that</span> <span m=''4682540''>you</span>
  <span m=''4682660''>can</span> <span m=''4682800''>produce</span> <span m=''4683270''>any</span>
  <span m=''4683460''>flat</span> <span m=''4683810''>state,</span> <span m=''4684600''>of</span>
  <span m=''4684700''>course,</span> <span m=''4685000''>you</span> <span m=''4685100''>can</span>
  <span m=''4685600''>reorient</span> <span m=''4686350''>yourself</span> <span m=''4686890''>by</span>
  <span m=''4687060''>relativity</span> <span m=''4688060''>so</span> <span m=''4688410''>that</span>
  <span m=''4688910''>the</span> <span m=''4689150''>chain</span> <span m=''4689390''>is</span>
  <span m=''4689490''>moving</span> <span m=''4689730''>instead</span> <span m=''4690000''>of</span>
  <span m=''4690120''>the cone.</span> <span m=''4690860''>So</span> <span m=''4691050''>you</span>
  <span m=''4691230''>can</span> <span m=''4691370''>produce</span> <span m=''4691660''>this</span>
  <span m=''4691790''>thing</span> <span m=''4691960''>with</span> <span m=''4692070''>a</span>
  <span m=''4692230''>ribosome.</span> <span m=''4693410''>Once</span> <span m=''4693630''>you
  know</span> <span m=''4693790''>all</span> <span m=''4693940''>flat</span> <span
  m=''4694240''>states</span> <span m=''4694550''>can</span> <span m=''4694730''>be</span>
  <span m=''4695560''>produced</span> <span m=''4696210''>and</span> <span m=''4696320''>you</span>
  <span m=''4696490''>know</span> <span m=''4696780''>all</span> <span m=''4697070''>producible</span>
  <span m=''4697950''>configurations</span> <span m=''4698590''>can</span> <span m=''4698720''>be</span>
  <span m=''4698820''>canonicalized,</span> <span m=''4699940''>then</span> <span
  m=''4700110''>you know it''s</span> <span m=''4700510''>flat state</span> <span
  m=''4700920''>connected</span> <span m=''4701390''>and</span> <span m=''4701480''>you
  know all</span> <span m=''4701950''>canonical</span> <span m=''4702530''>things</span>
  <span m=''4702870''>are</span> <span m=''4703040''>flattenable</span> <span m=''4703660''>and</span>
  <span m=''4703770''>vice</span> <span m=''4704010''>versa,</span> <span m=''4705080''>by</span>
  <span m=''4705190''>continuous</span> <span m=''4705660''>motions</span> <span m=''4706030''>without</span>
  <span m=''4706270''>self</span> <span m=''4706460''>intersection.</span> <span m=''4707900''>And</span>
  <span m=''4708030''>all</span> <span m=''4708200''>of</span> <span m=''4708290''>this</span>
  <span m=''4708500''>is</span> <span m=''4708640''>algorithmic.</span> <span m=''4709810''>It
  can</span> <span m=''4710200''>tell</span> <span m=''4710420''>you</span> <span
  m=''4710570''>how</span> <span m=''4710690''>to</span> <span m=''4710780''>go</span>
  <span m=''4711430''>from</span> <span m=''4711660''>one</span> <span m=''4711810''>place</span>
  <span m=''4712050''>to</span> <span m=''4712130''>another.</span> </p><p><span m=''4713550''>And</span>
  <span m=''4714320''>so</span> <span m=''4714530''>this</span> <span m=''4714800''>is</span>
  <span m=''4714980''>a</span> <span m=''4715100''>candidate</span> <span m=''4715770''>algorithm,</span>
  <span m=''4716260''>I</span> <span m=''4716360''>would</span> <span m=''4716540''>say,</span>
  <span m=''4716750''>for</span> <span m=''4716920''>how</span> <span m=''4717110''>nature</span>
  <span m=''4717480''>folds</span> <span m=''4717780''>proteins.</span> <span m=''4718790''>Just</span>
  <span m=''4719070''>thinking</span> <span m=''4719300''>about</span> <span m=''4719490''>the</span>
  <span m=''4719550''>mechanics,</span> <span m=''4720410''>not</span> <span m=''4720640''>worrying</span>
  <span m=''4720850''>about</span> <span m=''4721020''>how</span> <span m=''4721170''>it''s</span>
  <span m=''4721270''>implemented.</span> <span m=''4722330''>Maybe</span> <span m=''4723900''>you</span>
  <span m=''4724010''>take</span> <span m=''4724270''>this</span> <span m=''4724460''>model</span>
  <span m=''4724870''>and</span> <span m=''4724950''>then</span> <span m=''4725100''>you</span>
  <span m=''4725200''>try</span> <span m=''4725440''>to</span> <span m=''4725520''>make</span>
  <span m=''4725760''>it</span> <span m=''4726370''>physical</span> <span m=''4727700''>forces,</span>
  <span m=''4730450''>and</span> <span m=''4730680''>you</span> <span m=''4730770''>get</span>
  <span m=''4730910''>a way</span> <span m=''4731080''>to</span> <span m=''4731150''>fold</span>
  <span m=''4731400''>proteins.</span> <span m=''4732220''>That,</span> <span m=''4732390''>of</span>
  <span m=''4732490''>course,</span> <span m=''4733120''>remains</span> <span m=''4733550''>a</span>
  <span m=''4733590''>mystery.</span> <span m=''4734120''>But</span> <span m=''4734250''>next</span>
  <span m=''4734490''>time</span> <span m=''4734710''>we</span> <span m=''4734820''>will</span>
  <span m=''4734980''>talk</span> <span m=''4735230''>about</span> <span m=''4736520''>some</span>
  <span m=''4737040''>very</span> <span m=''4737230''>simple</span> <span m=''4737620''>models</span>
  <span m=''4738630''>that</span> <span m=''4738800''>are</span> <span m=''4738910''>motivated</span>
  <span m=''4739590''>more</span> <span m=''4739860''>closely</span> <span m=''4740440''>via</span>
  <span m=''4740800''>biology</span> <span m=''4741830''>of</span> <span m=''4741980''>how</span>
  <span m=''4742240''>proteins</span> <span m=''4742650''>might</span> <span m=''4742800''>actually</span>
  <span m=''4743160''>fold,</span> <span m=''4744030''>and</span> <span m=''4744320''>talk</span>
  <span m=''4744510''>about</span> <span m=''4744780''>the</span> <span m=''4744930''>complexities</span>
  <span m=''4745340''>that</span> <span m=''4745750''>you</span> <span m=''4745830''>get</span>
  <span m=''4746020''>there.</span> </p>'
type: course
uid: 55e0b22bad2ff7cb29fe5f04e732832f

---
None