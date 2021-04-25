---
about_this_resource_text: <p><strong>Description:</strong> This class covers how the
  pebble algorithm works with first a proof of the 2k property, and then 2k-3. Generic
  rigidity and the running time of the algorithm is discussed, and software simulations
  running the algorithm are shown.</p> <p><strong>Speaker:</strong> Erik Demaine</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: yvatNaV6Bog
  parent_uid: 02d98a0c1ba96ee4f8f430099fc5f03c
  title: Video-YouTube-Stream
  type: Video
  uid: 843579e5d8ad5e4247d61e034818bfe3
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/yvatNaV6Bog/default.jpg
  parent_uid: 02d98a0c1ba96ee4f8f430099fc5f03c
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 2dd597f3a97569563f679130f7eabdd4
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: 02d98a0c1ba96ee4f8f430099fc5f03c
  title: Video-iTunes U-MP4
  type: Video
  uid: 08ac7fc2248147de27532156801a8ce1
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_class11_300k.mp4
  parent_uid: 02d98a0c1ba96ee4f8f430099fc5f03c
  title: Video-Internet Archive-MP4
  type: Video
  uid: 3a8f836171e3802465508970c39a2eef
- id: 3Play-3PlayYouTubeid-MP4
  media_location: yvatNaV6Bog
  parent_uid: 02d98a0c1ba96ee4f8f430099fc5f03c
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: b2b6b7a7f86556a44f80a0a0603c64c4
- id: yvatNaV6Bog.srt
  parent_uid: 02d98a0c1ba96ee4f8f430099fc5f03c
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/class-11-generic-rigidity/yvatNaV6Bog.srt
  title: 3play caption file
  type: null
  uid: 7dd1a369d5244285a6cb322f49af0851
- id: yvatNaV6Bog.pdf
  parent_uid: 02d98a0c1ba96ee4f8f430099fc5f03c
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/class-11-generic-rigidity/yvatNaV6Bog.pdf
  title: 3play pdf file
  type: null
  uid: 37e1d8f57df39052427adffb0e9df820
- id: Caption-3Play YouTube id-SRT
  parent_uid: 02d98a0c1ba96ee4f8f430099fc5f03c
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 2cee7286c6358a860bdb274b83fce7d3
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 02d98a0c1ba96ee4f8f430099fc5f03c
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 52384c8af3c8b76e647d2b358f67174f
inline_embed_id: 20704658class11:genericrigidity46263250
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: class-11-generic-rigidity
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/class-11-generic-rigidity
template_type: Tabbed
title: 'Class 11: Generic Rigidity'
transcript: '<p><span m=''3280''>PROFESSOR: All</span> <span m=''3340''>right,</span>
  <span m=''3540''>so</span> <span m=''3930''>lecture</span> <span m=''4300''>11</span>
  <span m=''4740''>was</span> <span m=''4970''>about</span> <span m=''6540''>generic</span>
  <span m=''6990''>rigidity</span> <span m=''8170''>of</span> <span m=''8540''>linkages.</span>
  <span m=''9200''>So</span> <span m=''9300''>we''ve</span> <span m=''9450''>got</span>
  <span m=''10420''>bars</span> <span m=''11000''>and</span> <span m=''11550''>vertices</span>
  <span m=''12740''>connected</span> <span m=''12980''>together</span> <span m=''13290''>in</span>
  <span m=''13360''>a</span> <span m=''13420''>graph.</span> <span m=''14400''>And</span>
  <span m=''14590''>generically,</span> <span m=''15170''>the</span> <span m=''15270''>graph</span>
  <span m=''15590''>is</span> <span m=''15730''>all</span> <span m=''15850''>that</span>
  <span m=''15950''>matters.</span> <span m=''16870''>And</span> <span m=''17540''>we</span>
  <span m=''17870''>characterize</span> <span m=''18520''>in</span> <span m=''18620''>two</span>
  <span m=''18800''>ways,</span> <span m=''19050''>Henneberg</span> <span m=''19450''>construction</span>
  <span m=''20150''>and</span> <span m=''20540''>Laman</span> <span m=''22450''>when</span>
  <span m=''23090''>graphs</span> <span m=''23630''>are</span> <span m=''23840''>generically</span>
  <span m=''24290''>rigid.</span> </p><p><span m=''25110''>And</span> <span m=''25290''>in</span>
  <span m=''25360''>particular,</span> <span m=''25860''>there</span> <span m=''26020''>was</span>
  <span m=''26120''>this</span> <span m=''26260''>pebble</span> <span m=''26590''>algorithm</span>
  <span m=''27110''>that</span> <span m=''27270''>was</span> <span m=''27380''>supposed</span>
  <span m=''27610''>to</span> <span m=''27710''>tell</span> <span m=''27910''>you</span>
  <span m=''28070''>in</span> <span m=''28160''>polynomial</span> <span m=''28700''>time</span>
  <span m=''29010''>whether</span> <span m=''29270''>you''re</span> <span m=''29610''>a</span>
  <span m=''29650''>graph</span> <span m=''29980''>was</span> <span m=''30350''>Laman</span>
  <span m=''30570''>or</span> <span m=''30660''>not.</span> <span m=''31510''>And</span>
  <span m=''32240''>everyone</span> <span m=''32870''>pretty</span> <span m=''33090''>much</span>
  <span m=''33360''>asked</span> <span m=''33640''>about</span> <span m=''34120''>this,</span>
  <span m=''34460''>about</span> <span m=''34730''>the</span> <span m=''34810''>details,</span>
  <span m=''35310''>including</span> <span m=''35560''>myself</span> <span m=''36030''>when</span>
  <span m=''36140''>I</span> <span m=''36190''>watched</span> <span m=''36460''>it</span>
  <span m=''36890''>like, huh,</span> <span m=''37140''>that seems</span> <span m=''37380''>a</span>
  <span m=''37440''>little</span> <span m=''37730''>sketchy.</span> <span m=''38900''>So</span>
  <span m=''39050''>I</span> <span m=''39150''>thought</span> <span m=''39350''>I''d</span>
  <span m=''39490''>spend</span> <span m=''39720''>most</span> <span m=''39980''>of</span>
  <span m=''40060''>today</span> <span m=''40390''>going</span> <span m=''40620''>through</span>
  <span m=''40860''>how</span> <span m=''41880''>that</span> <span m=''42090''>algorithm</span>
  <span m=''42520''>works</span> <span m=''42770''>exactly</span> <span m=''43630''>and</span>
  <span m=''43800''>also</span> <span m=''44050''>why</span> <span m=''44270''>it''s</span>
  <span m=''44450''>correct,</span> <span m=''45300''>which</span> <span m=''45650''>is</span>
  <span m=''45760''>definitely</span> <span m=''46080''>not</span> <span m=''47010''>obviously.</span>
  <span m=''47580''>It</span> <span m=''47920''>vaguely</span> <span m=''48300''>feels</span>
  <span m=''48640''>correct,</span> <span m=''49750''>but</span> <span m=''51760''>we''ll</span>
  <span m=''51890''>see</span> <span m=''52090''>why</span> <span m=''52460''>it</span>
  <span m=''52600''>actually</span> <span m=''52960''>is.</span> </p><p><span m=''54030''>Remember</span>
  <span m=''54480''>Laman''s</span> <span m=''54950''>Theorem,</span> <span m=''60470''>Laman</span>
  <span m=''60780''>characterization</span> <span m=''62170''>is</span> <span m=''62410''>that</span>
  <span m=''62630''>your</span> <span m=''63000''>graph</span> <span m=''63410''>is</span>
  <span m=''64480''>generically</span> <span m=''64970''>rigid</span> <span m=''70760''>if</span>
  <span m=''71010''>and</span> <span m=''71100''>only</span> <span m=''71400''>if</span>
  <span m=''72710''>every</span> <span m=''73030''>subgraph--</span> <span m=''77400''>let''s</span>
  <span m=''77590''>say</span> <span m=''78850''>every</span> <span m=''79340''>k</span>
  <span m=''79700''>vertices</span> <span m=''83800''>induces</span> <span m=''87090''>at</span>
  <span m=''87230''>most</span> <span m=''87550''>to</span> <span m=''87690''>2k</span>
  <span m=''87860''>minus</span> <span m=''88210''>3</span> <span m=''88460''>edges.</span>
  <span m=''92580''>That''s</span> <span m=''92890''>part</span> <span m=''93160''>one.</span>
  <span m=''93700''>And</span> <span m=''93980''>you</span> <span m=''94110''>also</span>
  <span m=''94380''>need</span> <span m=''94720''>that</span> <span m=''95000''>the</span>
  <span m=''95130''>number</span> <span m=''95400''>of</span> <span m=''95480''>edges</span>
  <span m=''96990''>overall</span> <span m=''97260''>in</span> <span m=''97530''>the</span>
  <span m=''97630''>graph</span> <span m=''99220''>is</span> <span m=''100650''>2n</span>
  <span m=''102240''>minus</span> <span m=''102630''>3</span> <span m=''102840''>where</span>
  <span m=''103110''>n is</span> <span m=''103240''>the</span> <span m=''103330''>total</span>
  <span m=''103640''>number</span> <span m=''103940''>vertices.</span> </p><p><span
  m=''105760''>So</span> <span m=''105850''>this</span> <span m=''106060''>was</span>
  <span m=''106190''>just</span> <span m=''106400''>the</span> <span m=''106470''>degree</span>
  <span m=''106770''>of</span> <span m=''106850''>freedom</span> <span m=''107140''>count.</span>
  <span m=''107450''>You</span> <span m=''107540''>have</span> <span m=''108580''>2n</span>
  <span m=''108910''>degrees</span> <span m=''109200''>of</span> <span m=''109290''>freedom</span>
  <span m=''109550''>for</span> <span m=''109690''>every</span> <span m=''109890''>vertex</span>
  <span m=''110420''>minus</span> <span m=''110820''>3</span> <span m=''111110''>for</span>
  <span m=''111250''>the</span> <span m=''111390''>rigid</span> <span m=''111690''>motions,</span>
  <span m=''112230''>two</span> <span m=''112400''>translations,</span> <span m=''113030''>one</span>
  <span m=''113190''>rotation.</span> <span m=''114140''>So</span> <span m=''114240''>that''s</span>
  <span m=''114370''>the</span> <span m=''114400''>number</span> <span m=''114610''>of</span>
  <span m=''114680''>edges</span> <span m=''114850''>you</span> <span m=''114970''>should</span>
  <span m=''115140''>have</span> <span m=''115300''>total.</span> <span m=''117170''>Sorry.</span>
  <span m=''117490''>This is</span> <span m=''117610''>for</span> <span m=''117780''>minimally</span>
  <span m=''118180''>generically</span> <span m=''118640''>rigid.</span> <span m=''122280''>And</span>
  <span m=''122490''>then</span> <span m=''124140''>to</span> <span m=''124350''>make</span>
  <span m=''124610''>it</span> <span m=''124850''>balance,</span> <span m=''125470''>you</span>
  <span m=''125590''>want</span> <span m=''125710''>to</span> <span m=''125770''>guarantee</span>
  <span m=''126140''>that</span> <span m=''126270''>every</span> <span m=''127710''>k</span>
  <span m=''127920''>vertices</span> <span m=''128530''>doesn''t</span> <span m=''128800''>have</span>
  <span m=''129070''>too</span> <span m=''129280''>many</span> <span m=''129580''>edges.</span>
  <span m=''129960''>Because</span> <span m=''130110''>if</span> <span m=''130220''>it</span>
  <span m=''130310''>has</span> <span m=''130479''>too</span> <span m=''130610''>many</span>
  <span m=''130800''>edges,</span> <span m=''131140''>there''d</span> <span m=''131210''>be</span>
  <span m=''131350''>too</span> <span m=''131520''>few</span> <span m=''131740''>somewhere</span>
  <span m=''132110''>else.</span> <span m=''132740''>This</span> <span m=''132910''>part
  would be</span> <span m=''133300''>overbrace,</span> <span m=''133770''>some</span>
  <span m=''133950''>other</span> <span m=''134140''>part</span> <span m=''134360''>would</span>
  <span m=''134450''>be</span> <span m=''134590''>underbrace, and</span> <span m=''135220''>you''d</span>
  <span m=''135330''>be</span> <span m=''135470''>flexible.</span> <span m=''136590''>That''s</span>
  <span m=''136800''>the</span> <span m=''136880''>intuition.</span> </p><p><span
  m=''139180''>And</span> <span m=''139450''>so</span> <span m=''139640''>the</span>
  <span m=''140360''>tricky</span> <span m=''140680''>part</span> <span m=''141030''>comes</span>
  <span m=''141290''>down</span> <span m=''141560''>to</span> <span m=''142570''>how</span>
  <span m=''142880''>do</span> <span m=''142940''>you</span> <span m=''143100''>check</span>
  <span m=''143440''>whether</span> <span m=''143810''>every</span> <span m=''144110''>k</span>
  <span m=''144270''>vertices</span> <span m=''144720''>induces</span> <span m=''145690''>2k</span>
  <span m=''145960''>minus</span> <span m=''146220''>3</span> <span m=''146430''>edges</span>
  <span m=''147290''>because</span> <span m=''147600''>they''re</span> <span m=''147750''>exponentially</span>
  <span m=''148300''>many</span> <span m=''148520''>choices.</span> <span m=''148950''>There''s</span>
  <span m=''149120''>2</span> <span m=''149390''>to</span> <span m=''149550''>the</span>
  <span m=''149780''>n</span> <span m=''150500''>different</span> <span m=''150750''>choices</span>
  <span m=''151200''>of</span> <span m=''151480''>subsets</span> <span m=''152040''>or</span>
  <span m=''152110''>vertices.</span> <span m=''152900''>For</span> <span m=''153050''>each</span>
  <span m=''153220''>of</span> <span m=''153270''>them,</span> <span m=''153410''>you''d</span>
  <span m=''153480''>have</span> <span m=''153640''>to</span> <span m=''153750''>check.</span>
  <span m=''154040''>That''s</span> <span m=''154280''>no</span> <span m=''154390''>good.</span>
  <span m=''155290''>So</span> <span m=''155350''>the</span> <span m=''155480''>algorithm</span>
  <span m=''156180''>wants</span> <span m=''156380''>to</span> <span m=''156450''>check</span>
  <span m=''156710''>this.</span> <span m=''157000''>And</span> <span m=''157290''>I''m</span>
  <span m=''157370''>going</span> <span m=''157470''>to</span> <span m=''157550''>call</span>
  <span m=''157820''>this</span> <span m=''158030''>property</span> <span m=''159050''>the</span>
  <span m=''159450''>2k</span> <span m=''159980''>minus</span> <span m=''160420''>3</span>
  <span m=''160640''>property.</span> </p><p><span m=''164110''>And</span> <span m=''164340''>we''re</span>
  <span m=''164510''>going</span> <span m=''164620''>to</span> <span m=''164710''>warm</span>
  <span m=''164990''>up</span> <span m=''165190''>with</span> <span m=''165410''>a</span>
  <span m=''165520''>simpler</span> <span m=''165930''>problem,</span> <span m=''166460''>which</span>
  <span m=''166560''>is</span> <span m=''166680''>to</span> <span m=''166810''>check</span>
  <span m=''167100''>to</span> <span m=''167190''>the</span> <span m=''167470''>2k</span>
  <span m=''167980''>property</span> <span m=''169070''>without</span> <span m=''169470''>the</span>
  <span m=''169590''>minus</span> <span m=''170020''>3.</span> <span m=''171810''>So</span>
  <span m=''172030''>2k</span> <span m=''172450''>property</span> <span m=''172980''>is</span>
  <span m=''173160''>just</span> <span m=''175810''>every</span> <span m=''176170''>k</span>
  <span m=''176380''>vertices</span> <span m=''182610''>induce</span> <span m=''185910''>at</span>
  <span m=''186090''>most</span> <span m=''186570''>2k</span> <span m=''187940''>edges.</span>
  <span m=''191050''>So</span> <span m=''191130''>this''ll</span> <span m=''191410''>be</span>
  <span m=''191580''>a</span> <span m=''191770''>little</span> <span m=''192060''>easier</span>
  <span m=''192410''>to</span> <span m=''192500''>think</span> <span m=''192720''>about,</span>
  <span m=''192990''>more</span> <span m=''193260''>or</span> <span m=''193280''>less</span>
  <span m=''193540''>the</span> <span m=''193620''>same,</span> <span m=''194585''>a</span>
  <span m=''195080''>lot</span> <span m=''195260''>easier</span> <span m=''195530''>to</span>
  <span m=''195590''>argue</span> <span m=''195930''>about.</span> <span m=''197200''>And</span>
  <span m=''197420''>then</span> <span m=''197550''>we''ll</span> <span m=''197670''>see</span>
  <span m=''197890''>how</span> <span m=''198030''>to</span> <span m=''198100''>modify</span>
  <span m=''198520''>the</span> <span m=''198660''>algorithm</span> <span m=''198930''>to</span>
  <span m=''199130''>check</span> <span m=''199470''>the</span> <span m=''199570''>2k</span>
  <span m=''199880''>minus</span> <span m=''200180''>3</span> <span m=''200350''>property.</span>
  </p><p><span m=''201840''>Was</span> <span m=''202000''>the</span> <span m=''202200''>property</span>
  <span m=''202830''>clear</span> <span m=''203710''>and</span> <span m=''204380''>in</span>
  <span m=''204490''>particular</span> <span m=''204920''>inducing?</span> <span m=''206170''>Inducing</span>
  <span m=''206620''>means</span> <span m=''206950''>that</span> <span m=''208350''>you</span>
  <span m=''208500''>have</span> <span m=''208720''>some</span> <span m=''208820''>set</span>
  <span m=''209020''>of</span> <span m=''209070''>vertices,</span> <span m=''210450''>and</span>
  <span m=''210630''>there''s</span> <span m=''210940''>the</span> <span m=''211060''>rest</span>
  <span m=''211340''>of</span> <span m=''211390''>the</span> <span m=''211450''>vertices,</span>
  <span m=''211900''>n</span> <span m=''212050''>minus</span> <span m=''212360''>k</span>
  <span m=''212540''>of</span> <span m=''212640''>them.</span> <span m=''213310''>You</span>
  <span m=''213490''>only</span> <span m=''213690''>look</span> <span m=''213880''>at</span>
  <span m=''213980''>edges</span> <span m=''214580''>where</span> <span m=''214930''>both</span>
  <span m=''215290''>endpoints</span> <span m=''216360''>are</span> <span m=''216550''>in</span>
  <span m=''216740''>the</span> <span m=''216820''>set,</span> <span m=''217200''>both</span>
  <span m=''217440''>of</span> <span m=''217510''>them</span> <span m=''217710''>are</span>
  <span m=''218060''>among</span> <span m=''218420''>the</span> <span m=''218510''>k</span>
  <span m=''218690''>vertices.</span> <span m=''219750''>So</span> <span m=''219810''>you</span>
  <span m=''219980''>ignore</span> <span m=''222020''>vertices</span> <span m=''223060''>that</span>
  <span m=''223510''>have</span> <span m=''223770''>one</span> <span m=''224100''>end
  in</span> <span m=''224500''>k</span> <span m=''224800''>and</span> <span m=''224890''>the</span>
  <span m=''224990''>other</span> <span m=''225210''>end</span> <span m=''225630''>outside.</span>
  <span m=''226030''>And</span> <span m=''226120''>you</span> <span m=''226250''>ignore,</span>
  <span m=''227130''>obviously,</span> <span m=''227500''>edges</span> <span m=''227870''>that</span>
  <span m=''227980''>have</span> <span m=''228140''>both</span> <span m=''228420''>ends</span>
  <span m=''229040''>outside.</span> <span m=''229670''>Just count</span> <span m=''230090''>these</span>
  <span m=''230300''>guys.</span> </p><p><span m=''234000''>So</span> <span m=''235140''>how</span>
  <span m=''235270''>do</span> <span m=''235350''>we</span> <span m=''235440''>do</span>
  <span m=''235560''>this?</span> <span m=''237010''>Give</span> <span m=''237190''>you</span>
  <span m=''237350''>the</span> <span m=''237500''>algorithm.</span> <span m=''238310''>Actually,</span>
  <span m=''239880''>let</span> <span m=''240070''>me</span> <span m=''240180''>first</span>
  <span m=''240400''>give</span> <span m=''240530''>you</span> <span m=''240610''>the</span>
  <span m=''240740''>idea</span> <span m=''241100''>of</span> <span m=''241170''>the</span>
  <span m=''241280''>algorithm</span> <span m=''242000''>before</span> <span m=''242280''>we</span>
  <span m=''242390''>go</span> <span m=''242520''>to</span> <span m=''242620''>the</span>
  <span m=''242740''>actual</span> <span m=''243100''>algorithm.</span> <span m=''244840''>And</span>
  <span m=''245100''>this</span> <span m=''245290''>is</span> <span m=''245830''>review,</span>
  <span m=''246930''>but</span> <span m=''247110''>pretty</span> <span m=''247300''>soon</span>
  <span m=''247540''>we''ll</span> <span m=''247680''>get</span> <span m=''247920''>to</span>
  <span m=''248570''>stuff</span> <span m=''248820''>that</span> <span m=''248920''>wasn''t</span>
  <span m=''249220''>covered</span> <span m=''249590''>in</span> <span m=''249770''>lecture.</span>
  <span m=''264280''>So</span> <span m=''264830''>the</span> <span m=''264990''>idea</span>
  <span m=''265220''>is</span> <span m=''266660''>every</span> <span m=''267220''>vertex</span>
  <span m=''269570''>has</span> <span m=''269950''>two</span> <span m=''270380''>pebbles</span>
  <span m=''271290''>inside</span> <span m=''271940''>of</span> <span m=''272030''>it.</span>
  <span m=''273501''>I''ll</span> <span m=''273920''>draw</span> <span m=''274360''>as</span>
  <span m=''274930''>two</span> <span m=''275360''>red</span> <span m=''275660''>dots.</span>
  </p><p><span m=''277300''>And</span> <span m=''277930''>they</span> <span m=''278120''>can</span>
  <span m=''279430''>cover</span> <span m=''280260''>incident</span> <span m=''280990''>edges.</span>
  <span m=''282130''>So</span> <span m=''282170''>they</span> <span m=''282290''>can''t</span>
  <span m=''282520''>move</span> <span m=''282660''>very</span> <span m=''282860''>far.</span>
  <span m=''283090''>They</span> <span m=''283190''>have</span> <span m=''283360''>to</span>
  <span m=''283470''>stay</span> <span m=''283710''>basically</span> <span m=''284160''>on</span>
  <span m=''284570''>the</span> <span m=''284980''>inside</span> <span m=''285600''>or</span>
  <span m=''285810''>on</span> <span m=''285940''>the</span> <span m=''286010''>boundary</span>
  <span m=''286500''>of</span> <span m=''286580''>the</span> <span m=''286670''>vertex.</span>
  <span m=''287260''>That''s</span> <span m=''287570''>how I''m</span> <span m=''287800''>going</span>
  <span m=''287890''>to</span> <span m=''287980''>draw it.</span> <span m=''289560''>Each</span>
  <span m=''289840''>pebble</span> <span m=''295820''>can</span> <span m=''296540''>cover</span>
  <span m=''301960''>one</span> <span m=''302440''>incident</span> <span m=''302990''>edge.</span>
  <span m=''308910''>So</span> <span m=''309160''>for</span> <span m=''309360''>example,</span>
  <span m=''311950''>there''s</span> <span m=''312080''>a</span> <span m=''312140''>little</span>
  <span m=''312330''>graph.</span> <span m=''316680''>I</span> <span m=''316810''>could</span>
  <span m=''317010''>take--</span> <span m=''318160''>let''s</span> <span m=''318520''>maybe</span>
  <span m=''318770''>I leave</span> <span m=''319050''>one</span> <span m=''319250''>of</span>
  <span m=''319300''>the</span> <span m=''319400''>pebbles</span> <span m=''319780''>in</span>
  <span m=''319850''>the</span> <span m=''319930''>middle.</span> <span m=''320350''>I</span>
  <span m=''320530''>can</span> <span m=''320710''>move</span> <span m=''320940''>one</span>
  <span m=''321100''>of</span> <span m=''321170''>the</span> <span m=''321260''>pebbles</span>
  <span m=''321720''>to</span> <span m=''321830''>cover</span> <span m=''322830''>one</span>
  <span m=''323000''>of</span> <span m=''323050''>the</span> <span m=''323190''>edges.</span>
  </p><p><span m=''324240''>So</span> <span m=''324280''>I''ll</span> <span m=''324380''>put</span>
  <span m=''324540''>it</span> <span m=''324710''>this</span> <span m=''324850''>intersection</span>
  <span m=''325460''>to</span> <span m=''325590''>denote</span> <span m=''325870''>it''s</span>
  <span m=''326020''>covering</span> <span m=''326330''>this</span> <span m=''326480''>edge,</span>
  <span m=''327440''>but</span> <span m=''327580''>it</span> <span m=''327660''>still</span>
  <span m=''327830''>belongs</span> <span m=''328220''>to</span> <span m=''328310''>this</span>
  <span m=''328500''>vertex.</span> <span m=''329000''>Pebbles</span> <span m=''329340''>cannot</span>
  <span m=''329730''>change</span> <span m=''330000''>vertices.</span> <span m=''330460''>They
  have</span> <span m=''330760''>to</span> <span m=''330880''>stay</span> <span m=''331640''>local.</span>
  <span m=''332970''>These</span> <span m=''333250''>two</span> <span m=''333350''>pebbles</span>
  <span m=''333760''>could just</span> <span m=''333970''>stay</span> <span m=''334200''>where</span>
  <span m=''334330''>they</span> <span m=''334500''>are.</span> <span m=''335860''>Here,</span>
  <span m=''336120''>we</span> <span m=''336240''>could</span> <span m=''336560''>put</span>
  <span m=''336790''>one</span> <span m=''337000''>pebble</span> <span m=''337310''>here,</span>
  <span m=''337740''>another</span> <span m=''338000''>pebble</span> <span m=''338290''>there,</span>
  <span m=''339270''>one pebble</span> <span m=''339580''>here,</span> <span m=''340270''>one</span>
  <span m=''340580''>pebble</span> <span m=''340780''>here.</span> <span m=''341360''>This</span>
  <span m=''341570''>is</span> <span m=''341630''>what</span> <span m=''341800''>I</span>
  <span m=''341860''>call</span> <span m=''342110''>a</span> <span m=''342180''>pebble</span>
  <span m=''342510''>cover</span> <span m=''342820''>cause</span> <span m=''343000''>every</span>
  <span m=''343360''>edge</span> <span m=''343600''>is</span> <span m=''343710''>covered</span>
  <span m=''344100''>by</span> <span m=''344270''>some</span> <span m=''344540''>pebble.</span>
  </p><p><span m=''346750''>That''s</span> <span m=''349510''>the</span> <span m=''349610''>goal</span>
  <span m=''352070''>in</span> <span m=''352190''>a</span> <span m=''352260''>pebble</span>
  <span m=''352620''>cover</span> <span m=''353430''>is</span> <span m=''353660''>to</span>
  <span m=''353750''>cover</span> <span m=''354090''>every</span> <span m=''354400''>edge.</span>
  <span m=''357950''>You</span> <span m=''358150''>need</span> <span m=''358320''>to</span>
  <span m=''358390''>cover</span> <span m=''358660''>it</span> <span m=''358730''>once.</span>
  <span m=''364270''>And</span> <span m=''365110''>the</span> <span m=''365590''>pebbles</span>
  <span m=''365940''>can</span> <span m=''366100''>either</span> <span m=''366390''>cover</span>
  <span m=''366720''>an</span> <span m=''366790''>edge</span> <span m=''368620''>or</span>
  <span m=''369030''>they</span> <span m=''369190''>can</span> <span m=''369340''>be</span>
  <span m=''369540''>free.</span> <span m=''371030''>Free</span> <span m=''371870''>if</span>
  <span m=''372090''>they''re</span> <span m=''372250''>just</span> <span m=''372470''>hanging</span>
  <span m=''372790''>out</span> <span m=''373060''>in</span> <span m=''373130''>the</span>
  <span m=''373240''>inside</span> <span m=''373630''>here</span> <span m=''373800''>not</span>
  <span m=''374000''>being</span> <span m=''374160''>used</span> <span m=''374380''>for</span>
  <span m=''374470''>anything.</span> <span m=''376450''>So</span> <span m=''376600''>our</span>
  <span m=''376720''>goal</span> <span m=''376930''>is</span> <span m=''377000''>to</span>
  <span m=''377090''>find</span> <span m=''377400''>pebble</span> <span m=''377650''>covers.</span>
  <span m=''378470''>But</span> <span m=''378990''>the</span> <span m=''379080''>first</span>
  <span m=''379320''>claim,</span> <span m=''380100''>why</span> <span m=''380280''>do</span>
  <span m=''380360''>I</span> <span m=''380420''>care</span> <span m=''380620''>about</span>
  <span m=''380820''>pebble</span> <span m=''381060''>covers,</span> <span m=''381420''>I</span>
  <span m=''381520''>claimed</span> <span m=''381840''>that</span> <span m=''382450''>having</span>
  <span m=''382790''>a</span> <span m=''382850''>pebble</span> <span m=''383130''>cover</span>
  <span m=''383470''>is</span> <span m=''383620''>equivalent</span> <span m=''384160''>to</span>
  <span m=''384260''>the 2k</span> <span m=''384380''>property.</span> <span m=''386520''>So</span>
  <span m=''386680''>that''s</span> <span m=''386850''>what</span> <span m=''386990''>I</span>
  <span m=''387040''>want</span> <span m=''387270''>to</span> <span m=''388460''>show.</span>
  </p><p><span m=''398160''>So</span> <span m=''398250''>let''s</span> <span m=''398360''>start
  with</span> <span m=''398680''>that.</span> <span m=''399020''>This</span> <span
  m=''399260''>is</span> <span m=''399590''>why</span> <span m=''399890''>everything</span>
  <span m=''400250''>is</span> <span m=''400360''>working.</span> <span m=''401860''>A</span>
  <span m=''401970''>graph</span> <span m=''402290''>has</span> <span m=''402600''>a</span>
  <span m=''402670''>2k</span> <span m=''403010''>property</span> <span m=''404370''>if</span>
  <span m=''404660''>and</span> <span m=''404740''>only</span> <span m=''405030''>if</span>
  <span m=''405420''>it</span> <span m=''405560''>has</span> <span m=''406120''>a</span>
  <span m=''406220''>pebble</span> <span m=''406560''>cover.</span> <span m=''411740''>So</span>
  <span m=''411950''>that''s</span> <span m=''413860''>why</span> <span m=''414130''>we</span>
  <span m=''414290''>care</span> <span m=''414600''>about</span> <span m=''414860''>these</span>
  <span m=''415020''>pebble</span> <span m=''415310''>coverings.</span> <span m=''415730''>And
  this</span> <span m=''415930''>is</span> <span m=''415980''>actually</span> <span
  m=''416260''>pretty</span> <span m=''416530''>easy</span> <span m=''416740''>to</span>
  <span m=''416830''>prove</span> <span m=''421090''>and</span> <span m=''421310''>gives</span>
  <span m=''421520''>a</span> <span m=''421580''>lot</span> <span m=''421750''>of</span>
  <span m=''421820''>intuition</span> <span m=''422330''>for</span> <span m=''422500''>why</span>
  <span m=''423520''>everything</span> <span m=''423910''>works</span> <span m=''424180''>here.</span>
  <span m=''424630''>So</span> <span m=''424760''>let''s</span> <span m=''424980''>start</span>
  <span m=''425270''>with</span> <span m=''427060''>the</span> <span m=''427170''>left</span>
  <span m=''427420''>direction.</span> </p><p><span m=''429240''>So</span> <span m=''429450''>suppose</span>
  <span m=''430100''>I</span> <span m=''430220''>have</span> <span m=''430480''>a</span>
  <span m=''430550''>pebble</span> <span m=''430840''>cover.</span> <span m=''431180''>Suppose</span>
  <span m=''431470''>somehow</span> <span m=''431760''>I''ve</span> <span m=''431970''>achieved</span>
  <span m=''432410''>this</span> <span m=''432590''>property,</span> <span m=''433470''>covering</span>
  <span m=''433810''>all</span> <span m=''433940''>the</span> <span m=''434060''>edges,</span>
  <span m=''435140''>using</span> <span m=''435500''>only</span> <span m=''435720''>two</span>
  <span m=''435900''>pebbles</span> <span m=''436350''>per</span> <span m=''436530''>vertex.</span>
  <span m=''437500''>I</span> <span m=''437640''>claim</span> <span m=''437990''>that</span>
  <span m=''438120''>we</span> <span m=''438270''>then</span> <span m=''438480''>satisfy</span>
  <span m=''438970''>the</span> <span m=''439100''>2k</span> <span m=''439440''>property.</span>
  <span m=''440690''>2k</span> <span m=''440990''>property</span> <span m=''441420''>says</span>
  <span m=''441730''>you</span> <span m=''441860''>take</span> <span m=''442060''>any</span>
  <span m=''442250''>key</span> <span m=''442400''>vertices,</span> <span m=''442940''>you</span>
  <span m=''443080''>induce</span> <span m=''443220''>at</span> <span m=''443710''>most
  two</span> <span m=''443920''>key</span> <span m=''444070''>edges.</span> <span
  m=''444510''>So</span> <span m=''444580''>let''s</span> <span m=''444930''>consider</span>
  <span m=''445340''>k</span> <span m=''445530''>vertices.</span> <span m=''448220''>Someone</span>
  <span m=''448850''>chooses</span> <span m=''449230''>k</span> <span m=''449380''>vertices.</span>
  <span m=''450600''>doesn''t</span> <span m=''450650''>matter</span> <span m=''450960''>which.</span>
  <span m=''452206''>It</span> <span m=''452600''>should</span> <span m=''452890''>hold</span>
  <span m=''453120''>for</span> <span m=''453290''>all</span> <span m=''453550''>of</span>
  <span m=''453600''>them,</span> <span m=''454510''>for</span> <span m=''454630''>all</span>
  <span m=''454740''>choices.</span> </p><p><span m=''456810''>So</span> <span m=''457180''>we''ve</span>
  <span m=''457280''>got</span> <span m=''458060''>a k</span> <span m=''458300''>vertices</span>
  <span m=''458740''>here.</span> <span m=''460290''>n</span> <span m=''460490''>minus</span>
  <span m=''460830''>k</span> <span m=''461030''>vertices</span> <span m=''461890''>remaining.</span>
  <span m=''462900''>We</span> <span m=''463040''>claim</span> <span m=''463430''>that</span>
  <span m=''463630''>the</span> <span m=''463710''>number</span> <span m=''463970''>of</span>
  <span m=''464040''>edges</span> <span m=''464450''>induced</span> <span m=''464850''>by</span>
  <span m=''465000''>those</span> <span m=''465200''>k</span> <span m=''465360''>vertices</span>
  <span m=''465860''>is</span> <span m=''466000''>at</span> <span m=''466100''>most</span>
  <span m=''466360''>2k.</span> <span m=''467670''>So</span> <span m=''467850''>look</span>
  <span m=''468020''>at</span> <span m=''468090''>one</span> <span m=''468230''>of</span>
  <span m=''468310''>these</span> <span m=''468500''>edges</span> <span m=''468900''>that''s</span>
  <span m=''469030''>wholly</span> <span m=''469370''>inside,</span> <span m=''469980''>that''s</span>
  <span m=''470140''>induced</span> <span m=''470540''>by</span> <span m=''470760''>these</span>
  <span m=''471000''>k</span> <span m=''471150''>vertices.</span> <span m=''475381''>I</span>
  <span m=''475780''>claim,</span> <span m=''476420''>well,</span> <span m=''476670''>that</span>
  <span m=''476900''>edge</span> <span m=''477350''>must</span> <span m=''477630''>be</span>
  <span m=''478350''>covered</span> <span m=''478770''>by</span> <span m=''478920''>a</span>
  <span m=''478990''>pebble.</span> <span m=''480370''>Which</span> <span m=''480600''>pebble?</span>
  <span m=''481190''>Well,</span> <span m=''481410''>either</span> <span m=''481920''>this</span>
  <span m=''482130''>one</span> <span m=''483450''>or</span> <span m=''484040''>one</span>
  <span m=''484260''>on</span> <span m=''484370''>the</span> <span m=''484500''>other</span>
  <span m=''484700''>side.</span> <span m=''485840''>But</span> <span m=''485990''>the</span>
  <span m=''486080''>point</span> <span m=''486250''>is</span> <span m=''486380''>it</span>
  <span m=''486490''>is</span> <span m=''486610''>covered</span> <span m=''486920''>by</span>
  <span m=''487080''>a</span> <span m=''487360''>pebble</span> <span m=''488040''>among</span>
  <span m=''488400''>these</span> <span m=''488620''>vertices.</span> </p><p><span
  m=''490920''>My</span> <span m=''491100''>concern</span> <span m=''491590''>is,</span>
  <span m=''492460''>well,</span> <span m=''492780''>maybe</span> <span m=''493140''>you</span>
  <span m=''493260''>worry</span> <span m=''493510''>about</span> <span m=''493890''>an</span>
  <span m=''494020''>edge</span> <span m=''494310''>like</span> <span m=''494490''>this.</span>
  <span m=''498590''>Or,</span> <span m=''498820''>maybe</span> <span m=''499650''>you</span>
  <span m=''499800''>worry</span> <span m=''500010''>about a</span> <span m=''500370''>pebble</span>
  <span m=''500650''>here</span> <span m=''501570''>that''s</span> <span m=''501760''>covering</span>
  <span m=''502120''>this</span> <span m=''502320''>edge,</span> <span m=''502530''>but</span>
  <span m=''502650''>that</span> <span m=''502810''>edge</span> <span m=''503020''>is</span>
  <span m=''503130''>not</span> <span m=''503290''>one</span> <span m=''503430''>of</span>
  <span m=''503510''>the</span> <span m=''503610''>induced</span> <span m=''503940''>edges.</span>
  <span m=''505300''>So</span> <span m=''505900''>these</span> <span m=''506070''>vertices</span>
  <span m=''506480''>are</span> <span m=''506630''>relevant.</span> <span m=''507420''>It''s</span>
  <span m=''508000''>just</span> <span m=''508480''>the</span> <span m=''508810''>pebbles</span>
  <span m=''509490''>inside,</span> <span m=''511600''>just</span> <span m=''511850''>among</span>
  <span m=''512340''>these</span> <span m=''512990''>2k</span> <span m=''513390''>pebbles.</span>
  <span m=''513740''>So</span> <span m=''514090''>in</span> <span m=''514220''>here,</span>
  <span m=''514510''>there</span> <span m=''514679''>are</span> <span m=''514740''>2k</span>
  <span m=''514890''>pebbles.</span> </p><p><span m=''516840''>They</span> <span m=''517080''>must</span>
  <span m=''517549''>fully</span> <span m=''517909''>cover</span> <span m=''519140''>the</span>
  <span m=''519270''>induced</span> <span m=''519600''>subgraph.</span> <span m=''520159''>They</span>
  <span m=''520260''>must</span> <span m=''520480''>cover</span> <span m=''520720''>all</span>
  <span m=''520980''>the</span> <span m=''521110''>edges</span> <span m=''521409''>in</span>
  <span m=''521500''>here.</span> <span m=''522890''>That</span> <span m=''523080''>means</span>
  <span m=''523350''>they''re at</span> <span m=''523510''>most</span> <span m=''523850''>2k</span>
  <span m=''524290''>edges</span> <span m=''525470''>because</span> <span m=''525890''>there''s</span>
  <span m=''526090''>one</span> <span m=''526450''>pebble</span> <span m=''526980''>per</span>
  <span m=''527310''>edge at</span> <span m=''527780''>least.</span> <span m=''529390''>And</span>
  <span m=''529620''>so</span> <span m=''529770''>there''s</span> <span m=''529950''>2k</span>
  <span m=''530080''>pebbles</span> <span m=''530530''>in</span> <span m=''530610''>here.</span>
  <span m=''531410''>This</span> <span m=''531580''>means</span> <span m=''531820''>they''re
  at</span> <span m=''532020''>must</span> <span m=''533370''>2k</span> <span m=''535220''>induced</span>
  <span m=''535350''>edges.</span> <span m=''541340''>Clear?</span> </p><p><span m=''542200''>That''s</span>
  <span m=''542530''>the</span> <span m=''542700''>obvious</span> <span m=''543320''>direction.</span>
  <span m=''545320''>This</span> <span m=''545500''>doesn''t</span> <span m=''545730''>really</span>
  <span m=''545970''>exploit</span> <span m=''546380''>very</span> <span m=''546540''>much</span>
  <span m=''546910''>about</span> <span m=''547820''>pebbles.</span> <span m=''549120''>The</span>
  <span m=''549230''>other</span> <span m=''549360''>direction</span> <span m=''549730''>is
  a</span> <span m=''549840''>little</span> <span m=''550000''>more</span> <span m=''550190''>interesting.</span>
  <span m=''553360''>Why</span> <span m=''553640''>should</span> <span m=''553840''>these</span>
  <span m=''554010''>pebble</span> <span m=''554300''>covers</span> <span m=''554640''>exist?</span>
  <span m=''555000''>Because</span> <span m=''555150''>they</span> <span m=''555260''>seem</span>
  <span m=''555540''>pretty</span> <span m=''556060''>constrained.</span> <span m=''556720''>Pebbles</span>
  <span m=''557050''>can''t</span> <span m=''557250''>move</span> <span m=''557410''>very</span>
  <span m=''557630''>far.</span> <span m=''559046''>It''s</span> <span m=''559520''>not</span>
  <span m=''559720''>really</span> <span m=''559960''>clearly</span> <span m=''561530''>the</span>
  <span m=''561600''>same,</span> <span m=''562700''>but</span> <span m=''562830''>it</span>
  <span m=''562910''>is.</span> <span m=''564300''>So</span> <span m=''564740''>if</span>
  <span m=''565010''>we</span> <span m=''565150''>have</span> <span m=''565580''>the</span>
  <span m=''565680''>2k</span> <span m=''566050''>property--</span> </p><p><span m=''566940''>So</span>
  <span m=''567140''>now</span> <span m=''567350''>we</span> <span m=''567460''>know</span>
  <span m=''568320''>that</span> <span m=''568550''>every</span> <span m=''568920''>subgraph</span>
  <span m=''569490''>of</span> <span m=''569610''>k</span> <span m=''569770''>vertices</span>
  <span m=''571170''>induces</span> <span m=''571690''>at</span> <span m=''571780''>most</span>
  <span m=''571990''>2k</span> <span m=''572360''>edges.</span> <span m=''573210''>Now,</span>
  <span m=''573380''>we</span> <span m=''573480''>want</span> <span m=''573690''>to</span>
  <span m=''573760''>prove</span> <span m=''574200''>that</span> <span m=''574600''>a</span>
  <span m=''574700''>pebble</span> <span m=''575000''>cover</span> <span m=''575290''>exists.</span>
  <span m=''580030''>I''m</span> <span m=''580180''>going</span> <span m=''580320''>to</span>
  <span m=''580400''>wait.</span> <span m=''582760''>It</span> <span m=''582900''>will</span>
  <span m=''583060''>become</span> <span m=''583430''>obvious</span> <span m=''584350''>momentarily.</span>
  <span m=''586180''>This</span> <span m=''586400''>is</span> <span m=''586750''>fun.</span>
  <span m=''588400''>Sometimes,</span> <span m=''588940''>it''s</span> <span m=''589070''>easier</span>
  <span m=''589340''>to</span> <span m=''589420''>prove</span> <span m=''589670''>a</span>
  <span m=''589770''>theorem</span> <span m=''590040''>than</span> <span m=''590160''>it</span>
  <span m=''590250''>is to</span> <span m=''590470''>come</span> <span m=''590670''>up</span>
  <span m=''590800''>with</span> <span m=''590930''>an</span> <span m=''591020''>algorithm.</span>
  <span m=''591610''>But</span> <span m=''591760''>in</span> <span m=''591840''>this</span>
  <span m=''592000''>case,</span> <span m=''592190''>it''s</span> <span m=''592310''>easier</span>
  <span m=''592550''>to</span> <span m=''592620''>come</span> <span m=''592810''>up</span>
  <span m=''592930''>with</span> <span m=''593030''>an</span> <span m=''593110''>algorithm</span>
  <span m=''593660''>than</span> <span m=''593840''>it is</span> <span m=''594100''>to
  prove</span> <span m=''594460''>a theorem.</span> </p><p><span m=''595280''>And</span>
  <span m=''595450''>you</span> <span m=''595580''>can</span> <span m=''595710''>use</span>
  <span m=''595960''>the</span> <span m=''596120''>algorithm</span> <span m=''596530''>itself</span>
  <span m=''596950''>to</span> <span m=''597080''>prove</span> <span m=''597720''>the</span>
  <span m=''597830''>theorem,</span> <span m=''598580''>so</span> <span m=''598840''>I''m</span>
  <span m=''598940''>going</span> <span m=''599050''>to</span> <span m=''599100''>prove</span>
  <span m=''599340''>this</span> <span m=''599540''>in</span> <span m=''599640''>a</span>
  <span m=''599680''>moment.</span> <span m=''600440''>Stay</span> <span m=''600720''>tuned.</span>
  <span m=''604820''>Meanwhile,</span> <span m=''605400''>we</span> <span m=''605500''>have</span>
  <span m=''605930''>an</span> <span m=''606030''>algorithm.</span> <span m=''609170''>This</span>
  <span m=''609270''>algorithm</span> <span m=''609710''>is</span> <span m=''609820''>an</span>
  <span m=''609870''>example</span> <span m=''610400''>of</span> <span m=''610480''>what</span>
  <span m=''610620''>we</span> <span m=''610730''>call</span> <span m=''611210''>an</span>
  <span m=''611350''>incremental</span> <span m=''612260''>style</span> <span m=''612600''>algorithm</span>
  <span m=''613150''>where</span> <span m=''613370''>you</span> <span m=''613720''>imagine</span>
  <span m=''614220''>starting</span> <span m=''614610''>with</span> <span m=''614800''>the</span>
  <span m=''614930''>empty</span> <span m=''615200''>graph</span> <span m=''615950''>and</span>
  <span m=''616130''>then</span> <span m=''616260''>you</span> <span m=''616370''>put</span>
  <span m=''616580''>in</span> <span m=''616770''>all</span> <span m=''616950''>the</span>
  <span m=''617090''>edges</span> <span m=''617360''>that</span> <span m=''617470''>belong</span>
  <span m=''618240''>one</span> <span m=''618480''>at</span> <span m=''618580''>a</span>
  <span m=''618690''>time.</span> <span m=''619870''>So</span> <span m=''620100''>add</span>
  <span m=''620540''>edges</span> <span m=''620980''>one</span> <span m=''621190''>at</span>
  <span m=''621240''>a</span> <span m=''621370''>time</span> <span m=''622830''>starting</span>
  <span m=''623180''>from</span> <span m=''623330''>nothing.</span> </p><p><span m=''629140''>One</span>
  <span m=''629490''>detail</span> <span m=''630080''>is</span> <span m=''630810''>we''re</span>
  <span m=''630950''>going</span> <span m=''631090''>to</span> <span m=''631390''>imagine</span>
  <span m=''631900''>as</span> <span m=''632160''>edges</span> <span m=''632500''>get</span>
  <span m=''632650''>added,</span> <span m=''633000''>we</span> <span m=''633120''>want</span>
  <span m=''633340''>to</span> <span m=''633490''>direct</span> <span m=''633970''>them.</span>
  <span m=''634840''>We''re</span> <span m=''634970''>going</span> <span m=''635160''>to</span>
  <span m=''635270''>direct</span> <span m=''635890''>edges</span> <span m=''642480''>from</span>
  <span m=''642710''>the</span> <span m=''642810''>pebble</span> <span m=''643200''>that</span>
  <span m=''643320''>covers</span> <span m=''643650''>them</span> <span m=''646240''>to</span>
  <span m=''646640''>the</span> <span m=''646810''>other</span> <span m=''646990''>side.</span>
  <span m=''649410''>So</span> <span m=''649550''>if</span> <span m=''649650''>we</span>
  <span m=''649760''>have</span> <span m=''650680''>an</span> <span m=''650840''>edge</span>
  <span m=''652300''>and</span> <span m=''652660''>we</span> <span m=''652800''>have</span>
  <span m=''654695''>a</span> <span m=''655100''>pebble</span> <span m=''656490''>over</span>
  <span m=''656730''>here,</span> <span m=''658220''>than</span> <span m=''658470''>I''m</span>
  <span m=''658580''>going</span> <span m=''658780''>to</span> <span m=''658890''>imagine</span>
  <span m=''659230''>the</span> <span m=''659340''>edge as</span> <span m=''659660''>being</span>
  <span m=''659840''>directed</span> <span m=''660590''>from</span> <span m=''661690''>the</span>
  <span m=''661790''>pebble</span> <span m=''662100''>to</span> <span m=''662190''>the</span>
  <span m=''662260''>other</span> <span m=''662400''>side.</span> </p><p><span m=''664220''>That''s</span>
  <span m=''664340''>just</span> <span m=''664510''>for</span> <span m=''664630''>convenience</span>
  <span m=''665130''>for</span> <span m=''665250''>expressing</span> <span m=''665520''>the</span>
  <span m=''665790''>algorithm</span> <span m=''666880''>in</span> <span m=''666930''>a</span>
  <span m=''666980''>moment.</span> <span m=''669530''>So</span> <span m=''669820''>now</span>
  <span m=''672060''>this</span> <span m=''672290''>is</span> <span m=''672470''>for
  the</span> <span m=''672830''>2k</span> <span m=''673210''>property.</span> <span
  m=''674860''>We''ll</span> <span m=''674970''>get</span> <span m=''675150''>to</span>
  <span m=''675230''>an</span> <span m=''675320''>algorithm</span> <span m=''675660''>for</span>
  <span m=''675810''>2k</span> <span m=''676090''>minus</span> <span m=''676400''>3</span>
  <span m=''676620''>a</span> <span m=''676680''>little</span> <span m=''676850''>bit.</span>
  <span m=''689150''>So</span> <span m=''689560''>now</span> <span m=''689840''>we</span>
  <span m=''690010''>have</span> <span m=''690360''>a</span> <span m=''690420''>4</span>
  <span m=''690640''>loop</span> <span m=''691000''>over</span> <span m=''691840''>the</span>
  <span m=''692240''>edge</span> <span m=''692480''>is</span> <span m=''692580''>we''re</span>
  <span m=''692700''>going</span> <span m=''692810''>to</span> <span m=''692870''>add.</span>
  <span m=''694990''>And</span> <span m=''696120''>when</span> <span m=''696310''>I</span>
  <span m=''697070''>immediately</span> <span m=''697570''>add</span> <span m=''697740''>an</span>
  <span m=''697840''>edge,</span> <span m=''698300''>it</span> <span m=''698410''>will</span>
  <span m=''698540''>not</span> <span m=''698750''>be</span> <span m=''698860''>covered,</span>
  <span m=''699270''>so it''s</span> <span m=''699700''>not</span> <span m=''699940''>directed,</span>
  <span m=''700660''>just</span> <span m=''700790''>some</span> <span m=''701040''>edge</span>
  <span m=''702040''>v-w.</span> </p><p><span m=''704000''>I</span> <span m=''704120''>would</span>
  <span m=''704320''>like</span> <span m=''704570''>to</span> <span m=''704680''>put</span>
  <span m=''704880''>a</span> <span m=''704940''>pebble</span> <span m=''705270''>here,</span>
  <span m=''705610''>but</span> <span m=''705640''>it</span> <span m=''705730''>could</span>
  <span m=''705890''>be</span> <span m=''706660''>both</span> <span m=''706950''>pebbles</span>
  <span m=''707420''>at</span> <span m=''707890''>w are</span> <span m=''708100''>occupied</span>
  <span m=''708590''>for</span> <span m=''708710''>some</span> <span m=''708920''>other</span>
  <span m=''709160''>edges.</span> <span m=''709650''>It</span> <span m=''709970''>could</span>
  <span m=''710130''>be</span> <span m=''712960''>the</span> <span m=''713120''>pebbles</span>
  <span m=''713480''>for</span> <span m=''713630''>v are</span> <span m=''714120''>also</span>
  <span m=''714450''>occupied</span> <span m=''714850''>for</span> <span m=''715000''>some</span>
  <span m=''715190''>other</span> <span m=''715400''>edges.</span> <span m=''716020''>That
  would</span> <span m=''716260''>be</span> <span m=''716510''>annoying.</span> <span
  m=''716900''>I</span> <span m=''716980''>want</span> <span m=''717210''>to</span>
  <span m=''717370''>somehow</span> <span m=''717820''>reassign</span> <span m=''718250''>a</span>
  <span m=''718310''>pebble</span> <span m=''718780''>to</span> <span m=''719000''>cover</span>
  <span m=''719270''>this</span> <span m=''719470''>edge,</span> <span m=''720400''>so</span>
  <span m=''720580''>what</span> <span m=''720720''>I''m</span> <span m=''720790''>going</span>
  <span m=''720910''>to</span> <span m=''720980''>do</span> <span m=''735920''>inside</span>
  <span m=''736470''>this</span> <span m=''736720''>4</span> <span m=''736980''>loop</span>
  <span m=''737800''>is</span> <span m=''738200''>search</span> <span m=''740830''>for</span>
  <span m=''741730''>available</span> <span m=''742220''>pebbles.</span> </p><p><span
  m=''743840''>And in</span> <span m=''744150''>this</span> <span m=''744320''>case,</span>
  <span m=''744760''>what</span> <span m=''745190''>turns</span> <span m=''745420''>out</span>
  <span m=''745560''>to</span> <span m=''745630''>be</span> <span m=''745770''>right</span>
  <span m=''746580''>is</span> <span m=''746890''>a</span> <span m=''747030''>directed</span>
  <span m=''747610''>path</span> <span m=''748660''>in</span> <span m=''748800''>this</span>
  <span m=''748980''>directed</span> <span m=''749380''>graph</span> <span m=''751700''>from</span>
  <span m=''752560''>either</span> <span m=''753250''>v</span> <span m=''753710''>or</span>
  <span m=''753930''>w</span> <span m=''756030''>to</span> <span m=''756490''>a</span>
  <span m=''756620''>free</span> <span m=''756930''>pebble.</span> <span m=''765790''>Either</span>
  <span m=''766030''>I</span> <span m=''766070''>find</span> <span m=''766370''>one</span>
  <span m=''766540''>or</span> <span m=''766660''>I</span> <span m=''766720''>don''t.</span>
  <span m=''768010''>If</span> <span m=''768200''>I</span> <span m=''768260''>find</span>
  <span m=''768560''>one,</span> <span m=''770240''>let''s</span> <span m=''770460''>say</span>
  <span m=''770610''>from</span> <span m=''770870''>v,</span> <span m=''772160''>there''s</span>
  <span m=''772505''>some</span> <span m=''772850''>edge</span> <span m=''773760''>and</span>
  <span m=''773900''>then</span> <span m=''774100''>some</span> <span m=''774330''>other</span>
  <span m=''774560''>edge</span> <span m=''775580''>and</span> <span m=''775830''>some</span>
  <span m=''776010''>other</span> <span m=''776230''>edge.</span> <span m=''777020''>And</span>
  <span m=''777190''>eventually,</span> <span m=''777700''>I</span> <span m=''777830''>find</span>
  <span m=''778130''>a</span> <span m=''778210''>free</span> <span m=''778530''>pebble.</span>
  <span m=''778870''>Remember a</span> <span m=''779230''>free</span> <span m=''779460''>pebble
  is</span> <span m=''779860''>one</span> <span m=''780070''>that''s</span> <span
  m=''780240''>floating</span> <span m=''780700''>on</span> <span m=''780780''>the</span>
  <span m=''780870''>inside,</span> <span m=''781320''>not</span> <span m=''781510''>being</span>
  <span m=''781680''>used</span> <span m=''781900''>for</span> <span m=''782000''>anything.</span>
  </p><p><span m=''783340''>So</span> <span m=''783550''>what</span> <span m=''783690''>does</span>
  <span m=''783790''>my</span> <span m=''783950''>picture</span> <span m=''784330''>look</span>
  <span m=''784510''>like?</span> <span m=''785700''>Remember</span> <span m=''785990''>edges</span>
  <span m=''786310''>are</span> <span m=''786390''>directed</span> <span m=''786760''>from</span>
  <span m=''787030''>the</span> <span m=''787130''>pebbles.</span> <span m=''787610''>That</span>
  <span m=''787750''>means</span> <span m=''787930''>there</span> <span m=''788040''>was</span>
  <span m=''788180''>a</span> <span m=''788240''>pebble</span> <span m=''788610''>at
  v</span> <span m=''788850''>being</span> <span m=''789050''>used</span> <span m=''789280''>for</span>
  <span m=''789370''>that</span> <span m=''789580''>edge.</span> <span m=''789870''>There
  was</span> <span m=''790050''>a</span> <span m=''790120''>pebble</span> <span m=''790640''>at</span>
  <span m=''790740''>this</span> <span m=''790930''>vertex</span> <span m=''791360''>being</span>
  <span m=''791530''>used</span> <span m=''791700''>for</span> <span m=''791780''>that</span>
  <span m=''791990''>edge.</span> <span m=''792770''>There was a</span> <span m=''792890''>pebble</span>
  <span m=''793210''>at</span> <span m=''793270''>this</span> <span m=''793440''>vertex</span>
  <span m=''793800''>being</span> <span m=''793980''>used</span> <span m=''794160''>for</span>
  <span m=''794240''>that</span> <span m=''794440''>edge.</span> <span m=''796560''>In</span>
  <span m=''796730''>this</span> <span m=''796920''>case,</span> <span m=''797730''>what</span>
  <span m=''797780''>do</span> <span m=''797860''>I</span> <span m=''797950''>do?</span>
  </p><p><span m=''804120''>AUDIENCE: Reverse.</span> </p><p><span m=''805050''>PROFESSOR:
  Reverse</span> <span m=''805500''>them,</span> <span m=''805850''>yeah.</span> <span
  m=''806840''>Just</span> <span m=''807090''>reverse</span> <span m=''807430''>all</span>
  <span m=''807560''>the</span> <span m=''807670''>edges.</span> <span m=''808680''>So</span>
  <span m=''809310''>I</span> <span m=''809460''>have</span> <span m=''809690''>this</span>
  <span m=''809860''>edge,</span> <span m=''810130''>v-w,</span> <span m=''811310''>here.</span>
  <span m=''812060''>I</span> <span m=''812190''>want</span> <span m=''812540''>to</span>
  <span m=''812590''>put</span> <span m=''812760''>a</span> <span m=''812820''>pebble</span>
  <span m=''813090''>here,</span> <span m=''813730''>so</span> <span m=''813860''>I''m</span>
  <span m=''813920''>going</span> <span m=''814050''>to</span> <span m=''814280''>reassign</span>
  <span m=''816270''>this</span> <span m=''816500''>guy</span> <span m=''817160''>to</span>
  <span m=''817350''>be</span> <span m=''817530''>over</span> <span m=''817690''>there,</span>
  <span m=''818270''>this</span> <span m=''818460''>guy</span> <span m=''818650''>to</span>
  <span m=''818740''>be</span> <span m=''818900''>over</span> <span m=''819050''>there,</span>
  <span m=''819840''>this</span> <span m=''819980''>guy</span> <span m=''820150''>to</span>
  <span m=''820190''>be</span> <span m=''820340''>over</span> <span m=''820460''>there,</span>
  <span m=''821680''>and</span> <span m=''821810''>so</span> <span m=''821940''>on.</span>
  <span m=''822310''>So</span> <span m=''823190''>I</span> <span m=''823320''>end</span>
  <span m=''823600''>up</span> <span m=''823830''>with--</span> <span m=''827310''>that''s</span>
  <span m=''827430''>in the</span> <span m=''827510''>way.</span> <span m=''828500''>Put</span>
  <span m=''828840''>w</span> <span m=''829090''>over</span> <span m=''829300''>here.</span>
  <span m=''830420''>The</span> <span m=''830530''>new</span> <span m=''830660''>picture</span>
  <span m=''831180''>is</span> <span m=''831590''>I</span> <span m=''831630''>have</span>
  <span m=''831830''>v and w.</span> <span m=''835170''>And</span> <span m=''835330''>I''m</span>
  <span m=''835440''>going to</span> <span m=''835480''>have</span> <span m=''835790''>left</span>
  <span m=''836040''>4</span> <span m=''836200''>directed</span> <span m=''836650''>edges.</span>
  </p><p><span m=''841540''>So</span> <span m=''842040''>now</span> <span m=''844100''>this</span>
  <span m=''844330''>pebble</span> <span m=''844610''>got</span> <span m=''844770''>assigned</span>
  <span m=''845110''>to</span> <span m=''845200''>be</span> <span m=''845310''>here.</span>
  <span m=''846790''>I</span> <span m=''846900''>can''t</span> <span m=''847120''>draw</span>
  <span m=''847550''>left</span> <span m=''847970''>apparently.</span> <span m=''849150''>The</span>
  <span m=''849280''>other</span> <span m=''849480''>left.</span> <span m=''852640''>This</span>
  <span m=''852730''>pebble</span> <span m=''852890''>assigned</span> <span m=''853210''>there.</span>
  <span m=''853510''>This</span> <span m=''853710''>pebble,</span> <span m=''854060''>the</span>
  <span m=''854140''>free</span> <span m=''854530''>pebble,</span> <span m=''854690''>gets</span>
  <span m=''854900''>used</span> <span m=''855190''>up.</span> <span m=''855940''>And</span>
  <span m=''856160''>now</span> <span m=''856430''>we''ve</span> <span m=''856550''>got</span>
  <span m=''856700''>a</span> <span m=''856750''>free</span> <span m=''856960''>pebble</span>
  <span m=''857300''>over</span> <span m=''857560''>here.</span> <span m=''858410''>And</span>
  <span m=''858500''>now</span> <span m=''858670''>we</span> <span m=''858790''>can</span>
  <span m=''858920''>assign</span> <span m=''859290''>it</span> <span m=''859440''>to</span>
  <span m=''859570''>be</span> <span m=''860010''>on</span> <span m=''860230''>the</span>
  <span m=''860370''>edge</span> <span m=''860560''>v-w.</span> <span m=''861580''>So</span>
  <span m=''861700''>if</span> <span m=''861790''>I</span> <span m=''861860''>can</span>
  <span m=''862020''>find</span> <span m=''862290''>such</span> <span m=''862450''>a</span>
  <span m=''862500''>path</span> <span m=''862780''>from</span> <span m=''862990''>v</span>
  <span m=''863370''>or</span> <span m=''863750''>from w,</span> <span m=''863920''>I''m</span>
  <span m=''864420''>happy</span> <span m=''864860''>because</span> <span m=''865030''>then</span>
  <span m=''865180''>I</span> <span m=''865250''>can</span> <span m=''865400''>reassign.</span>
  </p><p><span m=''878370''>If</span> <span m=''878640''>I</span> <span m=''878710''>find</span>
  <span m=''879130''>such</span> <span m=''880160''>a</span> <span m=''880250''>path,</span>
  <span m=''881600''>I</span> <span m=''881750''>just</span> <span m=''882090''>shift</span>
  <span m=''882340''>the</span> <span m=''882430''>pebbles</span> <span m=''882800''>like</span>
  <span m=''882990''>that,</span> <span m=''885660''>and</span> <span m=''886210''>I''m</span>
  <span m=''886320''>done.</span> <span m=''891010''>But</span> <span m=''891160''>what</span>
  <span m=''891300''>if</span> <span m=''891430''>I</span> <span m=''891520''>can''t?</span>
  <span m=''892320''>This</span> <span m=''892530''>is</span> <span m=''892630''>the</span>
  <span m=''892730''>critical</span> <span m=''893150''>issue,</span> <span m=''893440''>and</span>
  <span m=''893660''>it is</span> <span m=''893970''>also</span> <span m=''894310''>core</span>
  <span m=''894710''>to</span> <span m=''894860''>this</span> <span m=''895050''>part</span>
  <span m=''895240''>of</span> <span m=''895300''>the</span> <span m=''895380''>proof</span>
  <span m=''896130''>that</span> <span m=''896240''>we</span> <span m=''896340''>haven''t</span>
  <span m=''896570''>discover--</span> <span m=''897240''>haven''t</span> <span m=''897570''>yet</span>
  <span m=''897810''>done.</span> <span m=''899690''>Why</span> <span m=''899940''>would</span>
  <span m=''900110''>we</span> <span m=''900250''>hope</span> <span m=''900510''>for</span>
  <span m=''900950''>pebble</span> <span m=''901250''>covers</span> <span m=''901580''>to</span>
  <span m=''901680''>exist</span> <span m=''902030''>in</span> <span m=''902090''>the</span>
  <span m=''902170''>first</span> <span m=''902410''>place?</span> <span m=''902670''>We</span>
  <span m=''902770''>don''t</span> <span m=''902890''>know.</span> <span m=''904410''>I</span>
  <span m=''904610''>claim</span> <span m=''905090''>if</span> <span m=''905250''>this</span>
  <span m=''905420''>algorithm</span> <span m=''905840''>fails</span> <span m=''906360''>to</span>
  <span m=''906460''>find</span> <span m=''906810''>a</span> <span m=''906850''>path</span>
  <span m=''907780''>in</span> <span m=''907920''>this</span> <span m=''908070''>situation,</span>
  <span m=''909200''>then</span> <span m=''909570''>you</span> <span m=''909720''>can</span>
  <span m=''909870''>immediately</span> <span m=''910400''>say</span> <span m=''911310''>you</span>
  <span m=''911450''>do</span> <span m=''911570''>not</span> <span m=''911820''>satisfy</span>
  <span m=''912240''>the</span> <span m=''912370''>2k</span> <span m=''912790''>property.</span>
  </p><p><span m=''913600''>I''d</span> <span m=''913740''>like</span> <span m=''913880''>to</span>
  <span m=''913980''>say</span> <span m=''914140''>there''s</span> <span m=''914340''>no</span>
  <span m=''914520''>pebble</span> <span m=''914950''>cover,</span> <span m=''916090''>but</span>
  <span m=''916290''>that''s</span> <span m=''916450''>a</span> <span m=''916500''>little</span>
  <span m=''916660''>harder.</span> <span m=''917090''>I''m</span> <span m=''917210''>going</span>
  <span m=''917310''>to</span> <span m=''917370''>say</span> <span m=''920640''>you</span>
  <span m=''920740''>do</span> <span m=''920840''>not</span> <span m=''921070''>satisfy</span>
  <span m=''921480''>the</span> <span m=''921590''>2k</span> <span m=''921900''>property.</span>
  <span m=''933820''>And</span> <span m=''934550''>we</span> <span m=''934730''>actually</span>
  <span m=''934990''>know</span> <span m=''935380''>already,</span> <span m=''936330''>from</span>
  <span m=''936510''>this</span> <span m=''936740''>part,</span> <span m=''937750''>pebble</span>
  <span m=''937990''>cover</span> <span m=''938270''>implies</span> <span m=''938650''>2k</span>
  <span m=''938990''>property.</span> <span m=''939380''>The</span> <span m=''939520''>contrapositive,</span>
  <span m=''940360''>which</span> <span m=''940530''>we''ve</span> <span m=''940660''>already</span>
  <span m=''940870''>proved,</span> <span m=''941190''>is</span> <span m=''941490''>if</span>
  <span m=''942270''>you</span> <span m=''942360''>do</span> <span m=''942480''>not</span>
  <span m=''942770''>satisfy</span> <span m=''943140''>the</span> <span m=''943240''>2k</span>
  <span m=''943550''>property,</span> <span m=''944010''>you</span> <span m=''944130''>do</span>
  <span m=''944270''>not</span> <span m=''944530''>have</span> <span m=''944700''>a</span>
  <span m=''944790''>pebble</span> <span m=''945050''>cover.</span> <span m=''945950''>So</span>
  <span m=''946090''>that</span> <span m=''946280''>will</span> <span m=''946420''>actually</span>
  <span m=''946650''>guarantee</span> <span m=''947170''>correctness</span> <span
  m=''948190''>of</span> <span m=''948320''>the</span> <span m=''948440''>algorithm.</span>
  <span m=''948810''>If</span> <span m=''948950''>I</span> <span m=''949020''>can
  prove</span> <span m=''949400''>this</span> <span m=''949610''>part,</span> <span
  m=''949980''>that</span> <span m=''950400''>it violates</span> <span m=''950850''>2k</span>
  <span m=''951140''>property,</span> <span m=''951530''>then</span> <span m=''951690''>I''ll</span>
  <span m=''951810''>know</span> <span m=''951980''>there</span> <span m=''952100''>was</span>
  <span m=''952270''>no</span> <span m=''952430''>pebble</span> <span m=''952690''>cover,</span>
  <span m=''953010''>and</span> <span m=''953350''>I''m</span> <span m=''953810''>done.</span>
  </p><p><span m=''956960''>So</span> <span m=''957190''>why</span> <span m=''957490''>is</span>
  <span m=''957620''>this</span> <span m=''957770''>true.</span> <span m=''959090''>I</span>
  <span m=''959220''>claim</span> <span m=''960690''>if</span> <span m=''960860''>you</span>
  <span m=''961000''>look</span> <span m=''961250''>at</span> <span m=''962480''>all</span>
  <span m=''962760''>the</span> <span m=''962840''>nodes</span> <span m=''964460''>reachable</span>
  <span m=''965970''>by</span> <span m=''966090''>directed</span> <span m=''966520''>paths</span>
  <span m=''968600''>from</span> <span m=''968930''>v</span> <span m=''969260''>and</span>
  <span m=''969560''>w,</span> <span m=''973220''>then</span> <span m=''973490''>that</span>
  <span m=''973750''>is</span> <span m=''973880''>a</span> <span m=''973940''>set</span>
  <span m=''974160''>of</span> <span m=''974260''>nodes</span> <span m=''974700''>that</span>
  <span m=''974850''>induce</span> <span m=''975900''>more</span> <span m=''976390''>than</span>
  <span m=''976630''>2k</span> <span m=''977590''>edges.</span> <span m=''978620''>So</span>
  <span m=''978680''>let''s</span> <span m=''978840''>say</span> <span m=''978930''>their</span>
  <span m=''979100''>k</span> <span m=''979340''>nodes</span> <span m=''980140''>you</span>
  <span m=''980340''>can</span> <span m=''980480''>reach.</span> <span m=''982820''>I</span>
  <span m=''982980''>claim</span> <span m=''983350''>there</span> <span m=''983510''>will</span>
  <span m=''983650''>be</span> <span m=''984200''>more</span> <span m=''984430''>than</span>
  <span m=''984570''>2k</span> <span m=''984930''>edges</span> <span m=''985210''>among</span>
  <span m=''985490''>them.</span> <span m=''986330''>Why?</span> <span m=''989570''>It''s</span>
  <span m=''989700''>fun</span> <span m=''989840''>to</span> <span m=''989890''>have</span>
  <span m=''990190''>proof</span> <span m=''990490''>in</span> <span m=''990610''>the</span>
  <span m=''990690''>middle</span> <span m=''990910''>of</span> <span m=''991490''>an</span>
  <span m=''991580''>algorithm.</span> </p><p><span m=''994510''>So</span> <span m=''994660''>here</span>
  <span m=''994830''>we''ve</span> <span m=''994980''>got</span> <span m=''995300''>to</span>
  <span m=''995570''>v</span> <span m=''996520''>and</span> <span m=''996740''>w,</span>
  <span m=''997980''>and</span> <span m=''998310''>these</span> <span m=''998540''>are</span>
  <span m=''998600''>the</span> <span m=''998760''>k</span> <span m=''999240''>nodes</span>
  <span m=''999620''>that</span> <span m=''999730''>are</span> <span m=''999830''>reachable</span>
  <span m=''1000230''>from</span> <span m=''1000400''>v and w,</span> <span m=''1000980''>which</span>
  <span m=''1001160''>means</span> <span m=''1001920''>all</span> <span m=''1002180''>of</span>
  <span m=''1002270''>the</span> <span m=''1002410''>other</span> <span m=''1002640''>edges</span>
  <span m=''1003210''>are</span> <span m=''1003330''>pointing</span> <span m=''1004040''>into</span>
  <span m=''1005120''>this</span> <span m=''1005260''>set.</span> <span m=''1006150''>And
  then,</span> <span m=''1006310''>over</span> <span m=''1006520''>here,</span> <span
  m=''1006700''>we</span> <span m=''1006810''>have</span> <span m=''1007390''>everybody</span>
  <span m=''1007880''>else.</span> <span m=''1008310''>I</span> <span m=''1008350''>mean</span>
  <span m=''1008510''>it</span> <span m=''1008570''>might</span> <span m=''1008740''>be</span>
  <span m=''1008820''>everyone.</span> <span m=''1009430''>But</span> <span m=''1011310''>potentially,</span>
  <span m=''1011820''>there''s</span> <span m=''1012870''>some</span> <span m=''1013130''>vertices</span>
  <span m=''1013540''>over</span> <span m=''1013730''>here.</span> <span m=''1014050''>All</span>
  <span m=''1014320''>the</span> <span m=''1014420''>edges</span> <span m=''1014720''>are</span>
  <span m=''1015070''>directed</span> <span m=''1015420''>from</span> <span m=''1015610''>right</span>
  <span m=''1015810''>to</span> <span m=''1015900''>left,</span> <span m=''1016690''>otherwise</span>
  <span m=''1017040''>we</span> <span m=''1017150''>could</span> <span m=''1017280''>reach</span>
  <span m=''1017500''>more</span> <span m=''1017710''>stuff.</span> </p><p><span m=''1020350''>So</span>
  <span m=''1020870''>what''s</span> <span m=''1021060''>the</span> <span m=''1021140''>situation?</span>
  <span m=''1021680''>v-w</span> <span m=''1022023''>is</span> <span m=''1022710''>uncovered.</span>
  <span m=''1023740''>There''s no</span> <span m=''1023910''>pebbles</span> <span
  m=''1024280''>that</span> <span m=''1024380''>cover</span> <span m=''1024770''>it.</span>
  <span m=''1030660''>Every</span> <span m=''1030930''>other</span> <span m=''1031130''>edge
  is</span> <span m=''1031430''>covered</span> <span m=''1031869''>because</span>
  <span m=''1032589''>there''s</span> <span m=''1032750''>only</span> <span m=''1032940''>one</span>
  <span m=''1033190''>uncovered</span> <span m=''1033630''>edge</span> <span m=''1033839''>at</span>
  <span m=''1033880''>any</span> <span m=''1034040''>moment.</span> <span m=''1035079''>These</span>
  <span m=''1035300''>edges</span> <span m=''1035579''>are</span> <span m=''1035700''>all</span>
  <span m=''1035819''>covered</span> <span m=''1036349''>from</span> <span m=''1036670''>this</span>
  <span m=''1036900''>end.</span> <span m=''1037240''>That''s</span> <span m=''1037480''>what</span>
  <span m=''1037619''>these</span> <span m=''1037839''>directions</span> <span m=''1038339''>mean,</span>
  <span m=''1039710''>which</span> <span m=''1039839''>means</span> <span m=''1040069''>all</span>
  <span m=''1040349''>the</span> <span m=''1040450''>pebbles</span> <span m=''1040829''>in</span>
  <span m=''1040930''>here</span> <span m=''1041810''>are</span> <span m=''1041980''>used</span>
  <span m=''1042290''>to</span> <span m=''1042369''>cover</span> <span m=''1042740''>induced</span>
  <span m=''1043160''>edges.</span> </p><p><span m=''1045160''>So</span> <span m=''1045510''>all</span>
  <span m=''1046030''>the</span> <span m=''1046119''>pebbles</span> <span m=''1046530''>in</span>
  <span m=''1046630''>here</span> <span m=''1047349''>are</span> <span m=''1047440''>covering</span>
  <span m=''1047819''>induced</span> <span m=''1048119''>edges,</span> <span m=''1048640''>and</span>
  <span m=''1048900''>yet,</span> <span m=''1049300''>there''s</span> <span m=''1049550''>one</span>
  <span m=''1049870''>induced</span> <span m=''1050220''>edge</span> <span m=''1050420''>that</span>
  <span m=''1050540''>is</span> <span m=''1050660''>not</span> <span m=''1050870''>covered.</span>
  <span m=''1052180''>Now</span> <span m=''1052630''>they''re</span> <span m=''1052770''>exactly</span>
  <span m=''1053140''>2k</span> <span m=''1053460''>pebbles.</span> <span m=''1054130''>They''re</span>
  <span m=''1054260''>all</span> <span m=''1054510''>being</span> <span m=''1054760''>used.</span>
  <span m=''1056120''>I''m</span> <span m=''1056270''>assuming</span> <span m=''1056760''>here</span>
  <span m=''1056940''>you</span> <span m=''1057060''>never</span> <span m=''1057460''>have</span>
  <span m=''1058120''>two</span> <span m=''1058230''>pebbles</span> <span m=''1058570''>covering</span>
  <span m=''1058890''>the</span> <span m=''1058960''>same</span> <span m=''1059210''>edge,</span>
  <span m=''1060880''>so</span> <span m=''1061040''>that</span> <span m=''1061230''>means--</span>
  <span m=''1062050''>so</span> <span m=''1062340''>there''s</span> <span m=''1062520''>2k</span>
  <span m=''1062860''>pebbles.</span> <span m=''1064520''>They''re</span> <span m=''1064760''>all</span>
  <span m=''1064990''>used</span> <span m=''1065710''>to</span> <span m=''1066520''>cover</span>
  <span m=''1066880''>induced</span> <span m=''1067180''>edges,</span> <span m=''1068015''>which</span>
  <span m=''1068290''>implies</span> <span m=''1068700''>you</span> <span m=''1068800''>have</span>
  <span m=''1069050''>exactly</span> <span m=''1069590''>2k</span> <span m=''1070730''>plus</span>
  <span m=''1071210''>1</span> <span m=''1071980''>edges.</span> <span m=''1074220''>Plus</span>
  <span m=''1074490''>1</span> <span m=''1074710''>is</span> <span m=''1074910''>v-w.</span>
  </p><p><span m=''1076800''>That</span> <span m=''1076990''>means</span> <span m=''1078630''>that</span>
  <span m=''1078790''>means</span> <span m=''1078990''>the</span> <span m=''1079090''>graph</span>
  <span m=''1079440''>that</span> <span m=''1079560''>we''ve</span> <span m=''1079750''>created</span>
  <span m=''1080340''>so</span> <span m=''1080450''>far</span> <span m=''1080970''>violates</span>
  <span m=''1081510''>the</span> <span m=''1081590''>2k</span> <span m=''1081940''>property.</span>
  <span m=''1082620''>Now,</span> <span m=''1082660''>we</span> <span m=''1082750''>haven''t</span>
  <span m=''1082990''>added</span> <span m=''1083220''>all</span> <span m=''1083340''>the</span>
  <span m=''1083450''>edges</span> <span m=''1083700''>yet,</span> <span m=''1083980''>but</span>
  <span m=''1084080''>if</span> <span m=''1084200''>we</span> <span m=''1084310''>add</span>
  <span m=''1084450''>more</span> <span m=''1084690''>edge,</span> <span m=''1084870''>it''s</span>
  <span m=''1085110''>going</span> <span m=''1085230''>to</span> <span m=''1085290''>get</span>
  <span m=''1085570''>even</span> <span m=''1085800''>worse</span> <span m=''1086140''>potentially.</span>
  <span m=''1087430''>If we</span> <span m=''1087540''>have</span> <span m=''1087730''>2k</span>
  <span m=''1088040''>plus</span> <span m=''1088270''>1</span> <span m=''1088440''>edges</span>
  <span m=''1088700''>now,</span> <span m=''1089460''>in</span> <span m=''1089790''>the</span>
  <span m=''1089980''>actual</span> <span m=''1090420''>graph,</span> <span m=''1090780''>we''ll</span>
  <span m=''1091210''>have</span> <span m=''1091440''>at</span> <span m=''1091510''>least</span>
  <span m=''1091910''>2k</span> <span m=''1092270''>plus</span> <span m=''1092540''>1</span>
  <span m=''1092710''>edges.</span> <span m=''1094660''>So</span> <span m=''1094930''>if</span>
  <span m=''1095580''>this</span> <span m=''1095790''>search</span> <span m=''1096060''>fails,</span>
  <span m=''1097250''>you</span> <span m=''1097430''>know</span> <span m=''1098450''>that</span>
  <span m=''1098600''>you</span> <span m=''1098710''>violate</span> <span m=''1099070''>the</span>
  <span m=''1099160''>2k</span> <span m=''1099490''>property,</span> <span m=''1101370''>which</span>
  <span m=''1101490''>means</span> <span m=''1101730''>you know that</span> <span
  m=''1102160''>there''s</span> <span m=''1102320''>no</span> <span m=''1102460''>pebble</span>
  <span m=''1102760''>cover.</span> </p><p><span m=''1103200''>So</span> <span m=''1103340''>that</span>
  <span m=''1103530''>proves</span> <span m=''1103740''>correctness</span> <span m=''1104140''>of</span>
  <span m=''1104210''>the</span> <span m=''1104330''>algorithm.</span> <span m=''1105260''>Now</span>
  <span m=''1105410''>we</span> <span m=''1105500''>can</span> <span m=''1105620''>come</span>
  <span m=''1105770''>back</span> <span m=''1105980''>to</span> <span m=''1106070''>this</span>
  <span m=''1106250''>claim.</span> <span m=''1108230''>This</span> <span m=''1108560''>follows,</span>
  <span m=''1110090''>by</span> <span m=''1110220''>correctness</span> <span m=''1110700''>of</span>
  <span m=''1110770''>the</span> <span m=''1110880''>algorithm,</span> <span m=''1117600''>why.</span>
  <span m=''1118460''>We</span> <span m=''1118550''>want</span> <span m=''1118710''>to</span>
  <span m=''1118760''>prove</span> <span m=''1119010''>if</span> <span m=''1119300''>we</span>
  <span m=''1119390''>have</span> <span m=''1119560''>the</span> <span m=''1119670''>2k</span>
  <span m=''1120000''>property,</span> <span m=''1120950''>then</span> <span m=''1121100''>you</span>
  <span m=''1121200''>have</span> <span m=''1121360''>a</span> <span m=''1121430''>pebble</span>
  <span m=''1121710''>copper.</span> <span m=''1122440''>Well,</span> <span m=''1122820''>if</span>
  <span m=''1123090''>I</span> <span m=''1123190''>have</span> <span m=''1123360''>the</span>
  <span m=''1123450''>2k</span> <span m=''1123770''>property,</span> <span m=''1124680''>this</span>
  <span m=''1124890''>algorithm</span> <span m=''1125430''>will</span> <span m=''1125580''>work.</span>
  <span m=''1128090''>This</span> <span m=''1128520''>case</span> <span m=''1128810''>can</span>
  <span m=''1128980''>never</span> <span m=''1129270''>happen</span> <span m=''1129690''>because</span>
  <span m=''1130300''>it</span> <span m=''1130410''>can</span> <span m=''1130520''>only</span>
  <span m=''1130700''>happen</span> <span m=''1130960''>when</span> <span m=''1131080''>you</span>
  <span m=''1131170''>violate</span> <span m=''1131600''>the</span> <span m=''1131690''>2k</span>
  <span m=''1131960''>property.</span> </p><p><span m=''1132390''>So</span> <span
  m=''1132570''>if</span> <span m=''1132750''>you</span> <span m=''1132850''>have</span>
  <span m=''1133070''>the</span> <span m=''1133190''>2k</span> <span m=''1133530''>property,</span>
  <span m=''1134330''>this</span> <span m=''1134500''>algorithm,</span> <span m=''1135270''>you</span>
  <span m=''1135420''>can</span> <span m=''1135540''>keep</span> <span m=''1135760''>running</span>
  <span m=''1136060''>it.</span> <span m=''1136450''>You will</span> <span m=''1136790''>always</span>
  <span m=''1137100''>find</span> <span m=''1137330''>a</span> <span m=''1137390''>path.</span>
  <span m=''1137920''>You''ll</span> <span m=''1138070''>be</span> <span m=''1138190''>able</span>
  <span m=''1138330''>to</span> <span m=''1138410''>shift</span> <span m=''1138640''>the</span>
  <span m=''1138730''>pebbles</span> <span m=''1139150''>and</span> <span m=''1139310''>always</span>
  <span m=''1139600''>cover</span> <span m=''1139890''>things,</span> <span m=''1141070''>and</span>
  <span m=''1141230''>so</span> <span m=''1141310''>you</span> <span m=''1141480''>get</span>
  <span m=''1141720''>a</span> <span m=''1141840''>pebble</span> <span m=''1142130''>cover</span>
  <span m=''1142440''>from</span> <span m=''1142650''>the</span> <span m=''1142750''>algorithm.</span>
  <span m=''1144110''>The</span> <span m=''1144230''>end.</span> <span m=''1147640''>That''s</span>
  <span m=''1147900''>how</span> <span m=''1147990''>you</span> <span m=''1148150''>argue</span>
  <span m=''1148430''>that</span> <span m=''1148550''>if</span> <span m=''1148690''>you</span>
  <span m=''1148770''>have</span> <span m=''1148870''>the</span> <span m=''1148960''>2k</span>
  <span m=''1149260''>property,</span> <span m=''1149850''>you</span> <span m=''1149950''>get</span>
  <span m=''1150020''>a</span> <span m=''1150130''>pebble</span> <span m=''1150380''>cover.</span>
  <span m=''1151600''>And it''s</span> <span m=''1152710''>nifty.</span> </p><p><span
  m=''1153170''>Without</span> <span m=''1153510''>this</span> <span m=''1153700''>algorithm,</span>
  <span m=''1154120''>this</span> <span m=''1154320''>would</span> <span m=''1154430''>be</span>
  <span m=''1154560''>quite</span> <span m=''1155380''>tricky</span> <span m=''1155760''>to</span>
  <span m=''1156320''>specify.</span> <span m=''1157660''>But</span> <span m=''1157910''>the</span>
  <span m=''1158120''>algorithm</span> <span m=''1158650''>tells</span> <span m=''1159120''>you</span>
  <span m=''1159320''>where</span> <span m=''1159540''>the</span> <span m=''1159640''>violation</span>
  <span m=''1160330''>would</span> <span m=''1160480''>be,</span> <span m=''1161430''>tells</span>
  <span m=''1161710''>you</span> <span m=''1161860''>where</span> <span m=''1162110''>you</span>
  <span m=''1162230''>would</span> <span m=''1162330''>violate</span> <span m=''1162760''>the</span>
  <span m=''1162850''>2k</span> <span m=''1163150''>property.</span> <span m=''1164220''>And</span>
  <span m=''1164420''>that</span> <span m=''1164590''>lets</span> <span m=''1164790''>you</span>
  <span m=''1165230''>prove</span> <span m=''1165530''>the</span> <span m=''1165600''>claim</span>
  <span m=''1166130''>ultimately.</span> <span m=''1167880''>Any</span> <span m=''1167990''>questions</span>
  <span m=''1168370''>about</span> <span m=''1168600''>that.</span> <span m=''1170580''>This,</span>
  <span m=''1170800''>I</span> <span m=''1170870''>think,</span> <span m=''1171060''>is</span>
  <span m=''1171500''>the</span> <span m=''1171580''>heart</span> <span m=''1171860''>of</span>
  <span m=''1172090''>pebble</span> <span m=''1172430''>algorithms</span> <span m=''1172840''>and</span>
  <span m=''1172940''>why</span> <span m=''1173090''>they</span> <span m=''1173200''>work.</span>
  <span m=''1173960''>It''s</span> <span m=''1174050''>the</span> <span m=''1174120''>cleanest</span>
  <span m=''1174470''>part.</span> <span m=''1175360''>It</span> <span m=''1175600''>gets</span>
  <span m=''1175820''>a</span> <span m=''1175880''>little</span> <span m=''1176100''>bit</span>
  <span m=''1176290''>messier</span> <span m=''1176790''>to</span> <span m=''1176960''>do</span>
  <span m=''1177310''>the</span> <span m=''1177500''>2k</span> <span m=''1177820''>minus</span>
  <span m=''1178150''>3</span> <span m=''1178530''>thing,</span> <span m=''1178840''>so</span>
  <span m=''1178950''>we''ll</span> <span m=''1179060''>move</span> <span m=''1179220''>to</span>
  <span m=''1179330''>that</span> <span m=''1179520''>next.</span> </p><p><span m=''1181380''>Maybe</span>
  <span m=''1181680''>before</span> <span m=''1182350''>we</span> <span m=''1182480''>go</span>
  <span m=''1182670''>there,</span> <span m=''1183550''>we</span> <span m=''1183700''>can</span>
  <span m=''1183840''>talk</span> <span m=''1184060''>about</span> <span m=''1184310''>the</span>
  <span m=''1184440''>running</span> <span m=''1184680''>time</span> <span m=''1184890''>of</span>
  <span m=''1184940''>the</span> <span m=''1185020''>algorithm</span> <span m=''1188870''>for</span>
  <span m=''1189050''>those</span> <span m=''1190840''>so</span> <span m=''1191090''>inclined.</span>
  <span m=''1207680''>So</span> <span m=''1207950''>the</span> <span m=''1208090''>heart</span>
  <span m=''1208310''>of</span> <span m=''1208390''>the</span> <span m=''1208520''>algorithm</span>
  <span m=''1209040''>is</span> <span m=''1209730''>this</span> <span m=''1209850''>step,</span>
  <span m=''1210200''>search</span> <span m=''1210540''>for</span> <span m=''1210690''>directed</span>
  <span m=''1211080''>path</span> <span m=''1211395''>for v</span> <span m=''1211710''>or</span>
  <span m=''1211770''>w</span> <span m=''1212170''>to a</span> <span m=''1212380''>free</span>
  <span m=''1212670''>pebble.</span> <span m=''1214330''>This</span> <span m=''1214690''>is</span>
  <span m=''1214990''>essentially</span> <span m=''1215400''>some</span> <span m=''1215640''>of</span>
  <span m=''1215700''>the</span> <span m=''1215800''>nodes</span> <span m=''1216130''>have</span>
  <span m=''1216330''>free</span> <span m=''1216510''>pebbles.</span> <span m=''1217010''>Those</span>
  <span m=''1217190''>are</span> <span m=''1217350''>like</span> <span m=''1217670''>good</span>
  <span m=''1217850''>nodes.</span> </p><p><span m=''1219370''>But</span> <span m=''1219530''>basically,</span>
  <span m=''1219780''>we''ve</span> <span m=''1219920''>got</span> <span m=''1220050''>a</span>
  <span m=''1220110''>directed</span> <span m=''1220490''>graph.</span> <span m=''1221340''>We</span>
  <span m=''1221510''>want</span> <span m=''1221830''>to</span> <span m=''1223220''>find</span>
  <span m=''1223610''>all</span> <span m=''1224110''>the</span> <span m=''1224310''>nodes</span>
  <span m=''1224700''>that</span> <span m=''1224810''>are</span> <span m=''1224890''>reachable</span>
  <span m=''1225340''>from</span> <span m=''1225560''>v,</span> <span m=''1225930''>see</span>
  <span m=''1226300''>if</span> <span m=''1226670''>there''s</span> <span m=''1227530''>any</span>
  <span m=''1227720''>good</span> <span m=''1227900''>nodes</span> <span m=''1228150''>that</span>
  <span m=''1228230''>have</span> <span m=''1228400''>free</span> <span m=''1228560''>pebbles,</span>
  <span m=''1228940''>search</span> <span m=''1229320''>from</span> <span m=''1229460''>all</span>
  <span m=''1229610''>the nodes</span> <span m=''1230360''>from</span> <span m=''1230710''>w.</span>
  <span m=''1231120''>This</span> <span m=''1231400''>you</span> <span m=''1231510''>could</span>
  <span m=''1231640''>do</span> <span m=''1231710''>with</span> <span m=''1231820''>a</span>
  <span m=''1231890''>depth first</span> <span m=''1232270''>search</span> <span m=''1232570''>or
  a</span> <span m=''1232720''>breadth</span> <span m=''1232940''>first</span> <span
  m=''1233110''>search</span> <span m=''1233380''>or</span> <span m=''1233500''>your</span>
  <span m=''1233650''>favorite</span> <span m=''1234020''>search</span> <span m=''1234280''>algorithm.</span>
  <span m=''1235360''>Takes</span> <span m=''1235620''>linear</span> <span m=''1235940''>time.</span>
  <span m=''1236580''>Order</span> <span m=''1236820''>the</span> <span m=''1236970''>number
  of</span> <span m=''1237200''>vertices</span> <span m=''1237680''>plus the</span>
  <span m=''1237950''>number</span> <span m=''1238130''>of</span> <span m=''1238210''>edges</span>
  <span m=''1238540''>in</span> <span m=''1238610''>the</span> <span m=''1238700''>graph.</span>
  </p><p><span m=''1241350''>We</span> <span m=''1241570''>do</span> <span m=''1241840''>this</span>
  <span m=''1242100''>search</span> <span m=''1243380''>v</span> <span m=''1243680''>times.</span>
  <span m=''1247090''>Why</span> <span m=''1247330''>v</span> <span m=''1247570''>times?</span>
  <span m=''1254210''>So</span> <span m=''1254570''>we</span> <span m=''1254730''>add</span>
  <span m=''1255040''>edges</span> <span m=''1255370''>one</span> <span m=''1255560''>at</span>
  <span m=''1255630''>a</span> <span m=''1255730''>time.</span> <span m=''1257950''>We''re</span>
  <span m=''1258160''>hoping</span> <span m=''1258520''>that</span> <span m=''1258660''>we</span>
  <span m=''1258780''>have</span> <span m=''1259000''>the</span> <span m=''1259100''>2k</span>
  <span m=''1259440''>property.</span> <span m=''1261560''>The</span> <span m=''1261690''>2k</span>
  <span m=''1262020''>property</span> <span m=''1262410''>implies</span> <span m=''1262870''>that,</span>
  <span m=''1262940''>in</span> <span m=''1263050''>particular,</span> <span m=''1263480''>there</span>
  <span m=''1263680''>at</span> <span m=''1263760''>most</span> <span m=''1264110''>2v</span>
  <span m=''1264760''>edges.</span> <span m=''1265980''>So</span> <span m=''1266040''>in</span>
  <span m=''1266140''>general,</span> <span m=''1266560''>we</span> <span m=''1266660''>do</span>
  <span m=''1266680''>this</span> <span m=''1266970''>e</span> <span m=''1267140''>times.</span>
  <span m=''1268550''>We</span> <span m=''1268730''>keep</span> <span m=''1268960''>adding</span>
  <span m=''1269290''>edges.</span> <span m=''1269880''>We would</span> <span m=''1270100''>add</span>
  <span m=''1270570''>e</span> <span m=''1270750''>edges</span> <span m=''1271170''>to</span>
  <span m=''1271280''>the</span> <span m=''1271380''>graph</span> <span m=''1271880''>hopefully.</span>
  </p><p><span m=''1273850''>In</span> <span m=''1274070''>general,</span> <span m=''1274470''>e</span>
  <span m=''1274640''>can</span> <span m=''1274790''>be</span> <span m=''1274920''>much</span>
  <span m=''1275140''>larger</span> <span m=''1275430''>than</span> <span m=''1275630''>v</span>
  <span m=''1276190''>in</span> <span m=''1276320''>a</span> <span m=''1276360''>graph.</span>
  <span m=''1276780''>e</span> <span m=''1276960''>could</span> <span m=''1277110''>v</span>
  <span m=''1277510''>squared,</span> <span m=''1278645''>the</span> <span m=''1279010''>worst</span>
  <span m=''1279220''>case.</span> <span m=''1280330''>But</span> <span m=''1280930''>this</span>
  <span m=''1281210''>algorithm</span> <span m=''1281700''>will</span> <span m=''1281950''>fail</span>
  <span m=''1282720''>by</span> <span m=''1282940''>the</span> <span m=''1283050''>time</span>
  <span m=''1283310''>you</span> <span m=''1283470''>add</span> <span m=''1283730''>2k</span>
  <span m=''1284050''>plus</span> <span m=''1284290''>1</span> <span m=''1284500''>edges</span>
  <span m=''1285250''>because</span> <span m=''1285420''>then</span> <span m=''1285550''>you</span>
  <span m=''1285650''>definitely</span> <span m=''1285950''>don''t</span> <span m=''1286150''>satisfy</span>
  <span m=''1286530''>the</span> <span m=''1286650''>2k</span> <span m=''1286960''>property</span>
  <span m=''1287410''>over</span> <span m=''1287600''>the</span> <span m=''1288010''>entire</span>
  <span m=''1288440''>graph,</span> <span m=''1288740''>so</span> <span m=''1289320''>particularly
  you</span> <span m=''1289730''>won''t</span> <span m=''1289910''>satisfy</span>
  <span m=''1290340''>it on</span> <span m=''1290480''>some</span> <span m=''1290760''>subset</span>
  <span m=''1291160''>of</span> <span m=''1291440''>vertices.</span> <span m=''1294320''>So</span>
  <span m=''1294600''>you will</span> <span m=''1294950''>only</span> <span m=''1295200''>have</span>
  <span m=''1295340''>to</span> <span m=''1295430''>run</span> <span m=''1295580''>this</span>
  <span m=''1295770''>loop v</span> <span m=''1296170''>times,</span> <span m=''1296560''>not
  e</span> <span m=''1296940''>times--</span> <span m=''1297480''>or</span> <span
  m=''1297710''>2v</span> <span m=''1298050''>times.</span> </p><p><span m=''1299170''>So</span>
  <span m=''1299360''>this</span> <span m=''1299560''>is</span> <span m=''1299780''>a</span>
  <span m=''1299820''>little</span> <span m=''1300000''>bit</span> <span m=''1300180''>smaller,</span>
  <span m=''1301230''>and</span> <span m=''1301420''>so</span> <span m=''1301560''>this</span>
  <span m=''1301770''>product</span> <span m=''1302320''>is</span> <span m=''1304110''>v</span>
  <span m=''1304220''>squared</span> <span m=''1304680''>plus</span> <span m=''1304930''>ve.</span>
  <span m=''1307670''>Normally,</span> <span m=''1308080''>we</span> <span m=''1308210''>write</span>
  <span m=''1308500''>ve,</span> <span m=''1308940''>but</span> <span m=''1309710''>this
  is</span> <span m=''1310020''>slightly</span> <span m=''1310330''>more</span> <span
  m=''1310510''>precise,</span> <span m=''1311060''>which</span> <span m=''1311555''>is</span>
  <span m=''1312050''>the same</span> <span m=''1312370''>as</span> <span m=''1312830''>Bellman</span>
  <span m=''1313140''>Ford</span> <span m=''1313370''>algorithm</span> <span m=''1313710''>if</span>
  <span m=''1313840''>you''ve</span> <span m=''1314300''>taken</span> <span m=''1314570''>algorithms.</span>
  <span m=''1316490''>I''ll</span> <span m=''1316660''>just</span> <span m=''1316850''>mention</span>
  <span m=''1317320''>that</span> <span m=''1317650''>there</span> <span m=''1317840''>is</span>
  <span m=''1317940''>an</span> <span m=''1318030''>algorithm</span> <span m=''1318520''>slightly</span>
  <span m=''1319170''>fancier</span> <span m=''1319680''>that</span> <span m=''1320050''>just</span>
  <span m=''1320380''>requires</span> <span m=''1320860''>this</span> <span m=''1321080''>term.</span>
  <span m=''1322370''>This is</span> <span m=''1322520''>possible.</span> <span m=''1325390''>You</span>
  <span m=''1325500''>don''t</span> <span m=''1325700''>need</span> <span m=''1325930''>this</span>
  <span m=''1326120''>ve</span> <span m=''1326660''>part.</span> <span m=''1328300''>but</span>
  <span m=''1328570''>it''s</span> <span m=''1329260''>beside</span> <span m=''1329590''>the</span>
  <span m=''1329680''>point</span> <span m=''1329990''>to</span> <span m=''1330980''>our</span>
  <span m=''1331190''>goal,</span> <span m=''1331530''>which</span> <span m=''1331600''>is</span>
  <span m=''1331700''>just to</span> <span m=''1331890''>understand</span> <span m=''1332400''>when</span>
  <span m=''1332760''>things</span> <span m=''1333000''>are</span> <span m=''1333080''>rigid,</span>
  <span m=''1334320''>when</span> <span m=''1334460''>they''re</span> <span m=''1334570''>not</span>
  <span m=''1335430''>in</span> <span m=''1335620''>an</span> <span m=''1335840''>efficient</span>
  <span m=''1336450''>amount</span> <span m=''1336680''>of</span> <span m=''1336770''>time.</span>
  </p><p><span m=''1336980''>So</span> <span m=''1337130''>this is</span> <span m=''1337360''>polynomial</span>
  <span m=''1337950''>in</span> <span m=''1338020''>any</span> <span m=''1338190''>case.</span>
  <span m=''1339680''>This</span> <span m=''1339900''>also</span> <span m=''1340100''>the</span>
  <span m=''1340200''>best</span> <span m=''1340490''>known</span> <span m=''1340670''>algorithm,</span>
  <span m=''1341240''>v</span> <span m=''1341340''>squared.</span> <span m=''1342500''>Open</span>
  <span m=''1342760''>problem</span> <span m=''1343050''>is</span> <span m=''1343140''>whether</span>
  <span m=''1343310''>you</span> <span m=''1343390''>could</span> <span m=''1343530''>do</span>
  <span m=''1343630''>better.</span> <span m=''1347770''>Questions?</span> <span m=''1349103''>Yeah?</span>
  </p><p><span m=''1349566''>AUDIENCE: Is</span> <span m=''1350030''>there</span>
  <span m=''1350380''>more</span> <span m=''1350760''>than</span> <span m=''1352540''>2v</span>
  <span m=''1353554''>edges</span> <span m=''1354048''>instead of,</span> <span m=''1354542''>[INAUDIBLE]</span>
  <span m=''1355530''>that</span> <span m=''1355640''>[INAUDIBLE]</span> <span m=''1356900''>problem.</span>
  </p><p><span m=''1357740''>PROFESSOR: Yes,</span> <span m=''1358020''>there</span>
  <span m=''1358180''>are</span> <span m=''1358210''>more</span> <span m=''1358470''>than</span>
  <span m=''1358670''>to</span> <span m=''1358920''>v</span> <span m=''1359140''>edges.</span>
  <span m=''1359570''>Oh,</span> <span m=''1359935''>right!</span> <span m=''1360300''>So</span>
  <span m=''1360480''>there''s</span> <span m=''1360830''>done.</span> <span m=''1361630''>Great.</span>
  <span m=''1363280''>You</span> <span m=''1363420''>can</span> <span m=''1363530''>just</span>
  <span m=''1363690''>check</span> <span m=''1363910''>in</span> <span m=''1363980''>the</span>
  <span m=''1364090''>beginning,</span> <span m=''1364490''>are</span> <span m=''1364630''>there</span>
  <span m=''1364780''>more</span> <span m=''1364940''>than</span> <span m=''1365100''>to</span>
  <span m=''1365270''>v</span> <span m=''1365450''>edges.</span> <span m=''1365980''>If</span>
  <span m=''1366150''>so,</span> <span m=''1366550''>you</span> <span m=''1366670''>do</span>
  <span m=''1366790''>not</span> <span m=''1367010''>satisfy</span> <span m=''1367410''>the</span>
  <span m=''1369000''>2k</span> <span m=''1369710''>property,</span> <span m=''1370760''>and</span>
  <span m=''1371130''>so</span> <span m=''1371710''>you</span> <span m=''1371820''>can</span>
  <span m=''1371970''>stop.</span> <span m=''1372880''>So</span> <span m=''1373060''>that</span>
  <span m=''1373260''>takes</span> <span m=''1373460''>constant</span> <span m=''1373820''>time</span>
  <span m=''1374070''>to</span> <span m=''1374150''>check</span> <span m=''1374380''>those</span>
  <span m=''1374570''>cases,</span> <span m=''1374940''>otherwise</span> <span m=''1375430''>e</span>
  <span m=''1375600''>is</span> <span m=''1375710''>small.</span> <span m=''1376780''>And</span>
  <span m=''1377480''>then</span> <span m=''1377630''>you</span> <span m=''1377750''>only</span>
  <span m=''1377930''>take</span> <span m=''1378120''>the</span> <span m=''1378230''>square</span>
  <span m=''1378440''>time.</span> <span m=''1378910''>Thanks.</span> <span m=''1380220''>That''s</span>
  <span m=''1380410''>key.</span> </p><p><span m=''1386520''>So</span> <span m=''1387020''>that</span>
  <span m=''1387220''>was</span> <span m=''1387420''>the</span> <span m=''1387550''>2k</span>
  <span m=''1387940''>property.</span> <span m=''1390420''>Let''s</span> <span m=''1390860''>do</span>
  <span m=''1392950''>2k</span> <span m=''1393330''>minus</span> <span m=''1393730''>3.</span>
  <span m=''1408960''>For</span> <span m=''1409120''>the</span> <span m=''1409240''>2k</span>
  <span m=''1409510''>minus</span> <span m=''1409820''>3</span> <span m=''1410000''>algorithm,</span>
  <span m=''1410400''>it''s</span> <span m=''1410530''>going</span> <span m=''1410640''>to</span>
  <span m=''1410700''>be</span> <span m=''1410870''>pretty</span> <span m=''1411260''>much</span>
  <span m=''1411560''>the</span> <span m=''1411680''>same</span> <span m=''1411990''>as</span>
  <span m=''1412110''>this</span> <span m=''1412290''>algorithm.</span> <span m=''1413880''>So</span>
  <span m=''1414070''>in</span> <span m=''1414160''>particular,</span> <span m=''1414620''>every</span>
  <span m=''1414840''>vertex</span> <span m=''1415270''>is</span> <span m=''1415380''>to</span>
  <span m=''1415490''>attach</span> <span m=''1415810''>pebbles.</span> <span m=''1416900''>Each</span>
  <span m=''1416980''>pebble</span> <span m=''1417410''>can</span> <span m=''1417610''>cover</span>
  <span m=''1417940''>when</span> <span m=''1418100''>it''s</span> <span m=''1418300''>in
  an</span> <span m=''1418420''>edge,</span> <span m=''1418720''>otherwise</span>
  <span m=''1419070''>it''s</span> <span m=''1419240''>free.</span> <span m=''1420060''>Our</span>
  <span m=''1420200''>goal</span> <span m=''1420380''>is</span> <span m=''1420470''>to</span>
  <span m=''1420560''>cover</span> <span m=''1420850''>every</span> <span m=''1421130''>edge.</span>
  </p><p><span m=''1422730''>But</span> <span m=''1423090''>it''s</span> <span m=''1423330''>slightly</span>
  <span m=''1423740''>differently.</span> <span m=''1424120''>We have</span> <span
  m=''1424210''>to</span> <span m=''1424310''>deal</span> <span m=''1424480''>with</span>
  <span m=''1424580''>this</span> <span m=''1424730''>minus</span> <span m=''1425130''>3</span>
  <span m=''1425380''>business.</span> <span m=''1426640''>And</span> <span m=''1427660''>for</span>
  <span m=''1427860''>that</span> <span m=''1428140''>we</span> <span m=''1428240''>need</span>
  <span m=''1428560''>another</span> <span m=''1430420''>claim,</span> <span m=''1440460''>which</span>
  <span m=''1440620''>is</span> <span m=''1440770''>that</span> <span m=''1441100''>a</span>
  <span m=''1441370''>graph</span> <span m=''1441710''>has</span> <span m=''1442060''>a</span>
  <span m=''1442120''>2k</span> <span m=''1442440''>minus</span> <span m=''1442790''>3</span>
  <span m=''1442980''>property</span> <span m=''1447530''>if</span> <span m=''1447740''>and</span>
  <span m=''1447840''>only</span> <span m=''1448110''>if</span> <span m=''1449920''>g</span>
  <span m=''1450450''>plus</span> <span m=''1451030''>three</span> <span m=''1451490''>copies</span>
  <span m=''1452010''>of</span> <span m=''1452120''>an</span> <span m=''1452220''>edge</span>
  <span m=''1452500''>e</span> <span m=''1454640''>has</span> <span m=''1455350''>the</span>
  <span m=''1455670''>2k</span> <span m=''1456140''>property</span> <span m=''1461550''>for</span>
  <span m=''1462200''>every</span> <span m=''1462550''>edge,</span> <span m=''1468200''>e</span>
  <span m=''1469016''>and</span> <span m=''1469424''>g.</span> <span m=''1470610''>Should</span>
  <span m=''1470850''>probably</span> <span m=''1471140''>say</span> <span m=''1472190''>g</span>
  <span m=''1472720''>has.</span> </p><p><span m=''1475280''>So</span> <span m=''1475420''>I</span>
  <span m=''1475450''>want</span> <span m=''1475590''>to</span> <span m=''1475730''>know</span>
  <span m=''1475860''>whether</span> <span m=''1476040''>my--</span> <span m=''1476380''>ultimately,</span>
  <span m=''1476860''>I</span> <span m=''1476930''>care</span> <span m=''1477190''>whether</span>
  <span m=''1477380''>my</span> <span m=''1477500''>graph</span> <span m=''1477730''>has</span>
  <span m=''1477910''>a</span> <span m=''1477980''>2k</span> <span m=''1478290''>minus</span>
  <span m=''1478560''>3</span> <span m=''1478710''>property.</span> <span m=''1479040''>This</span>
  <span m=''1479220''>is</span> <span m=''1479320''>most</span> <span m=''1479740''>of</span>
  <span m=''1479890''>the</span> <span m=''1480030''>Laman</span> <span m=''1480470''>condition.</span>
  <span m=''1481620''>It''s</span> <span m=''1481690''>the</span> <span m=''1481780''>hard</span>
  <span m=''1482000''>part</span> <span m=''1482230''>to</span> <span m=''1482320''>check.</span>
  <span m=''1483330''>And</span> <span m=''1483900''>2k</span> <span m=''1484220''>property</span>
  <span m=''1484460''>is</span> <span m=''1484650''>what</span> <span m=''1484770''>I</span>
  <span m=''1484830''>know</span> <span m=''1485060''>how</span> <span m=''1485190''>to</span>
  <span m=''1485300''>check.</span> <span m=''1485920''>So</span> <span m=''1486090''>I</span>
  <span m=''1486160''>claim</span> <span m=''1486510''>all</span> <span m=''1486730''>you</span>
  <span m=''1486830''>need</span> <span m=''1487000''>to</span> <span m=''1487110''>do</span>
  <span m=''1487270''>to</span> <span m=''1487360''>check</span> <span m=''1487640''>it--</span>
  <span m=''1488190''>this</span> <span m=''1488350''>would</span> <span m=''1488470''>actually</span>
  <span m=''1488720''>be</span> <span m=''1488820''>an</span> <span m=''1488910''>algorithm.</span>
  <span m=''1489770''>For</span> <span m=''1489940''>every</span> <span m=''1490210''>edge,</span>
  <span m=''1491610''>turn</span> <span m=''1491850''>that</span> <span m=''1492130''>single</span>
  <span m=''1492460''>edge</span> <span m=''1492680''>into</span> <span m=''1492920''>four</span>
  <span m=''1493170''>copies</span> <span m=''1493540''>of</span> <span m=''1493650''>the</span>
  <span m=''1493780''>edge,</span> <span m=''1494280''>add</span> <span m=''1494510''>three</span>
  <span m=''1494700''>more,</span> <span m=''1495470''>check</span> <span m=''1495740''>whether</span>
  <span m=''1495970''>it has</span> <span m=''1496150''>the</span> <span m=''1496200''>2k</span>
  <span m=''1496510''>property,</span> <span m=''1497510''>remove</span> <span m=''1497880''>those</span>
  <span m=''1498120''>extra</span> <span m=''1498390''>three</span> <span m=''1498560''>copies,</span>
  <span m=''1499480''>take</span> <span m=''1499670''>the</span> <span m=''1499760''>next</span>
  <span m=''1500030''>edge,</span> <span m=''1500390''>add</span> <span m=''1500690''>three</span>
  <span m=''1500840''>copies,</span> <span m=''1501500''>check</span> <span m=''1501760''>the</span>
  <span m=''1501850''>2k</span> <span m=''1502120''>property.</span> </p><p><span
  m=''1503150''>So</span> <span m=''1503600''>with</span> <span m=''1504060''>another</span>
  <span m=''1504570''>factor</span> <span m=''1505190''>of</span> <span m=''1506300''>e,</span>
  <span m=''1506730''>which</span> <span m=''1507280''>has</span> <span m=''1507530''>to</span>
  <span m=''1507630''>be</span> <span m=''1507930''>order</span> <span m=''1508200''>v,</span>
  <span m=''1509290''>if</span> <span m=''1509390''>you''re</span> <span m=''1509510''>willing</span>
  <span m=''1509730''>to</span> <span m=''1509840''>spend</span> <span m=''1510180''>v</span>
  <span m=''1510380''>cubed</span> <span m=''1510700''>time,</span> <span m=''1511750''>you</span>
  <span m=''1511910''>can</span> <span m=''1511990''>just</span> <span m=''1512150''>run</span>
  <span m=''1512360''>this</span> <span m=''1512540''>algorithm</span> <span m=''1513720''>for</span>
  <span m=''1513900''>each</span> <span m=''1514110''>edge,</span> <span m=''1515240''>quadruple</span>
  <span m=''1515780''>it,</span> <span m=''1516710''>see</span> <span m=''1516880''>whether
  it</span> <span m=''1517150''>still</span> <span m=''1517350''>has</span> <span
  m=''1517540''>the</span> <span m=''1517600''>2k</span> <span m=''1517900''>property.</span>
  <span m=''1519580''>So</span> <span m=''1519760''>that''s</span> <span m=''1520740''>the</span>
  <span m=''1520850''>connection</span> <span m=''1521430''>between</span> <span m=''1521690''>these</span>
  <span m=''1521810''>2</span> <span m=''1521930''>things.</span> <span m=''1522330''>Let</span>
  <span m=''1522370''>me</span> <span m=''1522500''>prove</span> <span m=''1522790''>this</span>
  <span m=''1522960''>claim.</span> <span m=''1523800''>And</span> <span m=''1523990''>then</span>
  <span m=''1524140''>I''ll</span> <span m=''1524220''>tell</span> <span m=''1524420''>you</span>
  <span m=''1524660''>a</span> <span m=''1524730''>better</span> <span m=''1525040''>algorithm</span>
  <span m=''1525210''>that</span> <span m=''1525440''>only</span> <span m=''1525650''>takes</span>
  <span m=''1525900''>v</span> <span m=''1526020''>squared</span> <span m=''1526330''>time.</span>
  </p><p><span m=''1533069''>Which</span> <span m=''1533530''>one''s</span> <span
  m=''1533680''>easier?</span> <span m=''1535450''>In</span> <span m=''1536940''>both</span>
  <span m=''1537160''>cases,</span> <span m=''1537600''>I</span> <span m=''1537690''>want</span>
  <span m=''1537980''>to</span> <span m=''1538400''>take</span> <span m=''1538870''>k</span>
  <span m=''1539110''>vertices.</span> <span m=''1544790''>And</span> <span m=''1545100''>then</span>
  <span m=''1545410''>I''ll</span> <span m=''1545720''>do</span> <span m=''1546810''>in</span>
  <span m=''1547250''>this</span> <span m=''1547500''>direction</span> <span m=''1547960''>first.</span>
  <span m=''1551090''>So</span> <span m=''1553110''>how</span> <span m=''1553210''>do</span>
  <span m=''1553300''>we</span> <span m=''1553420''>prove</span> <span m=''1553670''>this?</span>
  <span m=''1553900''>First,</span> <span m=''1554270''>this is</span> <span m=''1554490''>actually</span>
  <span m=''1554730''>really</span> <span m=''1554970''>easy.</span> <span m=''1556580''>Suppose</span>
  <span m=''1557100''>g</span> <span m=''1557300''>has</span> <span m=''1557530''>a</span>
  <span m=''1557600''>2k</span> <span m=''1557920''>minus</span> <span m=''1558210''>3</span>
  <span m=''1558380''>property.</span> <span m=''1559330''>So</span> <span m=''1559920''>if</span>
  <span m=''1560040''>I</span> <span m=''1560110''>have</span> <span m=''1560290''>k</span>
  <span m=''1560460''>vertices</span> <span m=''1560930''>here,</span> <span m=''1561710''>I</span>
  <span m=''1561840''>know</span> <span m=''1562170''>that</span> <span m=''1562520''>the</span>
  <span m=''1563220''>number</span> <span m=''1563500''>of</span> <span m=''1563570''>edges</span>
  <span m=''1563940''>in</span> <span m=''1564070''>here</span> <span m=''1564880''>is</span>
  <span m=''1565120''>at</span> <span m=''1565200''>most</span> <span m=''1565530''>2k</span>
  <span m=''1565820''>minus</span> <span m=''1566150''>3.</span> </p><p><span m=''1566470''>So
  here''s</span> <span m=''1566780''>k</span> <span m=''1566960''>vertices.</span>
  <span m=''1568070''>Looking</span> <span m=''1568300''>at</span> <span m=''1568400''>the</span>
  <span m=''1568480''>number</span> <span m=''1568700''>of</span> <span m=''1568770''>induced</span>
  <span m=''1569020''>edges,</span> <span m=''1569540''>it''s</span> <span m=''1569870''>going</span>
  <span m=''1569990''>to</span> <span m=''1570050''>be</span> <span m=''1570210''>at</span>
  <span m=''1570300''>most</span> <span m=''1570680''>2k</span> <span m=''1570970''>minus</span>
  <span m=''1571340''>3.</span> <span m=''1573270''>What</span> <span m=''1573430''>I''m</span>
  <span m=''1573560''>claiming</span> <span m=''1574080''>is</span> <span m=''1574350''>then</span>
  <span m=''1574610''>if</span> <span m=''1574800''>I</span> <span m=''1575220''>quadruple</span>
  <span m=''1575800''>an</span> <span m=''1575870''>edge,</span> <span m=''1576440''>if</span>
  <span m=''1576820''>I</span> <span m=''1576950''>add</span> <span m=''1577210''>three</span>
  <span m=''1577420''>new</span> <span m=''1577590''>edges,</span> <span m=''1578770''>I</span>
  <span m=''1578850''>have</span> <span m=''1579030''>at</span> <span m=''1579100''>most</span>
  <span m=''1579370''>2k</span> <span m=''1580270''>edges</span> <span m=''1581170''>afterwards.</span>
  <span m=''1582370''>I</span> <span m=''1582430''>think</span> <span m=''1582580''>that''s</span>
  <span m=''1582740''>pretty</span> <span m=''1582910''>clear.</span> <span m=''1583730''>2k</span>
  <span m=''1584050''>minus</span> <span m=''1584350''>3</span> <span m=''1584500''>would
  be</span> <span m=''1584640''>4</span> <span m=''1584930''>at</span> <span m=''1585000''>most.</span>
  <span m=''1585780''>If</span> <span m=''1585870''>I</span> <span m=''1585930''>add</span>
  <span m=''1586240''>three</span> <span m=''1586450''>copies</span> <span m=''1586840''>of</span>
  <span m=''1586940''>any</span> <span m=''1587210''>edge,</span> <span m=''1587530''>could</span>
  <span m=''1587670''>be</span> <span m=''1587840''>in</span> <span m=''1587950''>this</span>
  <span m=''1588120''>set</span> <span m=''1588400''>or</span> <span m=''1588580''>outside</span>
  <span m=''1588950''>the</span> <span m=''1589030''>set</span> <span m=''1589360''>would
  be even</span> <span m=''1589570''>better,</span> <span m=''1590770''>the</span>
  <span m=''1590990''>number</span> <span m=''1591240''>of</span> <span m=''1591300''>edges</span>
  <span m=''1591580''>inside</span> <span m=''1591890''>the</span> <span m=''1592040''>set</span>
  <span m=''1592190''>will</span> <span m=''1592330''>be</span> <span m=''1592460''>at</span>
  <span m=''1592550''>most</span> <span m=''1592810''>2k.</span> </p><p><span m=''1593740''>So</span>
  <span m=''1593880''>this</span> <span m=''1594090''>is</span> <span m=''1594230''>in
  g.</span> <span m=''1596080''>This</span> <span m=''1596330''>implies</span> <span
  m=''1597420''>there''s</span> <span m=''1597600''>at most</span> <span m=''1597950''>2k</span>
  <span m=''1599670''>and</span> <span m=''1600970''>g</span> <span m=''1601070''>plus</span>
  <span m=''1602150''>thrice</span> <span m=''1602980''>e.</span> <span m=''1605620''>This</span>
  <span m=''1605810''>is</span> <span m=''1605930''>non-standard</span> <span m=''1606430''>notation</span>
  <span m=''1606880''>by</span> <span m=''1607000''>the</span> <span m=''1607110''>way.</span>
  <span m=''1607360''>It</span> <span m=''1607450''>just</span> <span m=''1607680''>means</span>
  <span m=''1608320''>add</span> <span m=''1608600''>three</span> <span m=''1608800''>copies</span>
  <span m=''1609190''>of</span> <span m=''1609290''>that</span> <span m=''1609500''>edge.</span>
  <span m=''1610080''>So</span> <span m=''1610810''>we</span> <span m=''1611090''>would</span>
  <span m=''1611240''>normally</span> <span m=''1611570''>draw</span> <span m=''1611810''>that</span>
  <span m=''1612060''>like</span> <span m=''1613430''>this,</span> <span m=''1615330''>four</span>
  <span m=''1615520''>copies</span> <span m=''1615870''>of</span> <span m=''1615950''>the</span>
  <span m=''1616050''>edge.</span> <span m=''1618020''>So</span> <span m=''1618230''>that</span>
  <span m=''1618450''>was</span> <span m=''1618770''>half</span> <span m=''1619140''>of</span>
  <span m=''1619360''>the</span> <span m=''1619480''>claim,</span> <span m=''1622070''>pretty</span>
  <span m=''1622280''>trivial.</span> <span m=''1622700''>The</span> <span m=''1622810''>other</span>
  <span m=''1622980''>half</span> <span m=''1623210''>is</span> <span m=''1623370''>almost</span>
  <span m=''1623820''>as</span> <span m=''1623940''>trivial.</span> </p><p><span m=''1629620''>So</span>
  <span m=''1630100''>on</span> <span m=''1630170''>the</span> <span m=''1630300''>other</span>
  <span m=''1630470''>direction,</span> <span m=''1632000''>we</span> <span m=''1632300''>assume</span>
  <span m=''1632930''>that g</span> <span m=''1633080''>plus</span> <span m=''1633500''>3e</span>
  <span m=''1634000''>has</span> <span m=''1634590''>this</span> <span m=''1634750''>property</span>
  <span m=''1635110''>for</span> <span m=''1635300''>every</span> <span m=''1635610''>edge.</span>
  <span m=''1636980''>And</span> <span m=''1637170''>now</span> <span m=''1637400''>we</span>
  <span m=''1637490''>need</span> <span m=''1637680''>to</span> <span m=''1637780''>prove</span>
  <span m=''1639130''>that</span> <span m=''1639340''>g</span> <span m=''1639550''>has</span>
  <span m=''1639740''>a</span> <span m=''1639800''>2k</span> <span m=''1640110''>minus</span>
  <span m=''1640450''>3</span> <span m=''1640620''>property</span> <span m=''1641100''>for</span>
  <span m=''1641340''>every</span> <span m=''1641590''>set</span> <span m=''1641790''>of</span>
  <span m=''1641880''>k</span> <span m=''1642050''>vertices.</span> <span m=''1642560''>So</span>
  <span m=''1642570''>we''re</span> <span m=''1642640''>looking</span> <span m=''1642900''>at</span>
  <span m=''1642980''>that</span> <span m=''1643170''>set</span> <span m=''1643320''>of</span>
  <span m=''1643410''>k</span> <span m=''1643560''>vertices.</span> <span m=''1644150''>We</span>
  <span m=''1644280''>want</span> <span m=''1644470''>to</span> <span m=''1644750''>argue</span>
  <span m=''1645060''>that</span> <span m=''1645190''>in g,</span> <span m=''1646250''>there''s</span>
  <span m=''1646430''>at</span> <span m=''1646510''>most</span> <span m=''1646910''>2k</span>
  <span m=''1647180''>minus</span> <span m=''1647480''>3</span> <span m=''1647670''>edges.</span>
  <span m=''1648790''>What</span> <span m=''1648890''>we</span> <span m=''1649000''>know</span>
  <span m=''1649580''>is</span> <span m=''1649800''>that</span> <span m=''1649910''>in</span>
  <span m=''1650070''>here,</span> <span m=''1650580''>in g</span> <span m=''1651640''>plus</span>
  <span m=''1651970''>3</span> <span m=''1652330''>e for</span> <span m=''1652480''>any</span>
  <span m=''1652750''>e--</span> <span m=''1653020''>so</span> <span m=''1653770''>it''s</span>
  <span m=''1653880''>a</span> <span m=''1653920''>little</span> <span m=''1654120''>awkward--</span>
  <span m=''1655270''>but</span> <span m=''1655330''>let</span> <span m=''1655630''>me</span>
  <span m=''1655730''>start</span> <span m=''1655950''>by</span> <span m=''1656050''>drawing</span>
  <span m=''1656340''>g.</span> </p><p><span m=''1657850''>We</span> <span m=''1657950''>want</span>
  <span m=''1658190''>to</span> <span m=''1658260''>claim</span> <span m=''1659220''>that</span>
  <span m=''1659520''>the</span> <span m=''1659630''>number</span> <span m=''1659870''>of</span>
  <span m=''1659940''>edges</span> <span m=''1660220''>in</span> <span m=''1660290''>here</span>
  <span m=''1660520''>is</span> <span m=''1660630''>at</span> <span m=''1660710''>most</span>
  <span m=''1660960''>2k</span> <span m=''1661240''>minus</span> <span m=''1661690''>3,</span>
  <span m=''1662000''>so</span> <span m=''1662140''>I''ll</span> <span m=''1662220''>put</span>
  <span m=''1662400''>a</span> <span m=''1662600''>question</span> <span m=''1662930''>mark.</span>
  <span m=''1667180''>So</span> <span m=''1668000''>there</span> <span m=''1668190''>are</span>
  <span m=''1668240''>2</span> <span m=''1668370''>possibilities</span> <span m=''1669170''>here.</span>
  <span m=''1669410''>It</span> <span m=''1669550''>could</span> <span m=''1669750''>be</span>
  <span m=''1670550''>either</span> <span m=''1670870''>this</span> <span m=''1671490''>graph</span>
  <span m=''1671800''>is</span> <span m=''1671940''>completely</span> <span m=''1672540''>empty.</span>
  <span m=''1673090''>If</span> <span m=''1673260''>there</span> <span m=''1673410''>are</span>
  <span m=''1673440''>no</span> <span m=''1673690''>edges</span> <span m=''1674010''>in</span>
  <span m=''1674100''>here,</span> <span m=''1675050''>then</span> <span m=''1675270''>surely</span>
  <span m=''1675640''>there are at</span> <span m=''1675850''>most</span> <span m=''1676110''>2k</span>
  <span m=''1676380''>minus</span> <span m=''1676700''>3</span> <span m=''1676890''>of</span>
  <span m=''1677000''>them,</span> <span m=''1677220''>assuming</span> <span m=''1677570''>k</span>
  <span m=''1678210''>is</span> <span m=''1678380''>bigger</span> <span m=''1678700''>than</span>
  <span m=''1678990''>1,</span> <span m=''1680620''>which</span> <span m=''1681230''>I</span>
  <span m=''1681660''>haven''t</span> <span m=''1681980''>mentioned.</span> </p><p><span
  m=''1682440''>But</span> <span m=''1682620''>throughout</span> <span m=''1682950''>here,</span>
  <span m=''1683220''>I</span> <span m=''1683270''>need</span> <span m=''1683470''>the</span>
  <span m=''1683590''>k</span> <span m=''1683780''>is</span> <span m=''1683920''>bigger</span>
  <span m=''1684130''>than</span> <span m=''1684280''>1.</span> <span m=''1684850''>You</span>
  <span m=''1684950''>can</span> <span m=''1685040''>never</span> <span m=''1685260''>have</span>
  <span m=''1685410''>negative</span> <span m=''1685720''>1</span> <span m=''1685970''>edges</span>
  <span m=''1686470''>on</span> <span m=''1686980''>subgraphs,</span> <span m=''1687335''>so</span>
  <span m=''1688580''>the</span> <span m=''1688930''>2k</span> <span m=''1689290''>in</span>
  <span m=''1689390''>the</span> <span m=''1689480''>2k</span> <span m=''1689750''>minus</span>
  <span m=''1690030''>3</span> <span m=''1690150''>property</span> <span m=''1690530''>only</span>
  <span m=''1690840''>hold</span> <span m=''1691610''>for</span> <span m=''1691830''>at</span>
  <span m=''1691880''>least</span> <span m=''1692280''>2</span> <span m=''1692490''>vertices.</span>
  <span m=''1693630''>K is</span> <span m=''1693890''>at least</span> <span m=''1694130''>2.</span>
  <span m=''1697070''>So</span> <span m=''1697240''>if there are</span> <span m=''1697370''>no</span>
  <span m=''1697510''>edges,</span> <span m=''1697860''>find</span> <span m=''1698110''>I''m</span>
  <span m=''1698200''>done.</span> <span m=''1699250''>If</span> <span m=''1699440''>there</span>
  <span m=''1699630''>are</span> <span m=''1699820''>edges</span> <span m=''1700150''>in</span>
  <span m=''1700240''>here,</span> <span m=''1701310''>then</span> <span m=''1701660''>I</span>
  <span m=''1701820''>can</span> <span m=''1702000''>do</span> <span m=''1702150''>this</span>
  <span m=''1702360''>trick.</span> <span m=''1703270''>So</span> <span m=''1703450''>there''s</span>
  <span m=''1703630''>some</span> <span m=''1703850''>edge.</span> <span m=''1704160''>Pick</span>
  <span m=''1704760''>your</span> <span m=''1704880''>favorite</span> <span m=''1705310''>edge.</span>
  <span m=''1705830''>Call</span> <span m=''1706170''>it e</span> <span m=''1707670''>in</span>
  <span m=''1707850''>this</span> <span m=''1708020''>subset.</span> <span m=''1709360''>Produce</span>
  <span m=''1710040''>out</span> <span m=''1710270''>of</span> <span m=''1710380''>it</span>
  <span m=''1711530''>g</span> <span m=''1711890''>plus</span> <span m=''1712220''>3e,</span>
  <span m=''1713330''>which</span> <span m=''1713570''>just</span> <span m=''1713810''>looks</span>
  <span m=''1713990''>like</span> <span m=''1714160''>the</span> <span m=''1714240''>same</span>
  <span m=''1714480''>thing,</span> <span m=''1714810''>but</span> <span m=''1714950''>now</span>
  <span m=''1715140''>it''s</span> <span m=''1715260''>got</span> <span m=''1715450''>four</span>
  <span m=''1715660''>copies</span> <span m=''1716020''>of</span> <span m=''1716110''>that</span>
  <span m=''1716300''>edge.</span> </p><p><span m=''1718280''>This</span> <span m=''1718600''>we</span>
  <span m=''1718750''>know</span> <span m=''1719070''>has</span> <span m=''1719360''>at</span>
  <span m=''1719450''>most</span> <span m=''1719820''>2k</span> <span m=''1720480''>edges</span>
  <span m=''1721230''>in</span> <span m=''1721360''>here.</span> <span m=''1722590''>The</span>
  <span m=''1722720''>original</span> <span m=''1723070''>graph</span> <span m=''1723530''>is</span>
  <span m=''1723720''>exactly</span> <span m=''1724110''>the</span> <span m=''1724180''>same</span>
  <span m=''1724440''>except</span> <span m=''1724750''>it</span> <span m=''1724830''>lacks</span>
  <span m=''1725080''>those</span> <span m=''1725260''>three</span> <span m=''1725440''>edges,</span>
  <span m=''1725760''>therefore,</span> <span m=''1726610''>there''s at</span> <span
  m=''1726780''>most</span> <span m=''1727050''>2k</span> <span m=''1727330''>minus</span>
  <span m=''1727620''>3</span> <span m=''1727800''>of them.</span> <span m=''1729380''>So</span>
  <span m=''1729740''>it''s</span> <span m=''1729940''>really</span> <span m=''1730170''>the</span>
  <span m=''1730290''>same</span> <span m=''1731470''>proof</span> <span m=''1731770''>in</span>
  <span m=''1731930''>both</span> <span m=''1732150''>directions.</span> <span m=''1733190''>Here,</span>
  <span m=''1733590''>you</span> <span m=''1734310''>have</span> <span m=''1734480''>to</span>
  <span m=''1734580''>use</span> <span m=''1734810''>your</span> <span m=''1734940''>freedom</span>
  <span m=''1735430''>in</span> <span m=''1735600''>choosing</span> <span m=''1735880''>e</span>
  <span m=''1736140''>to</span> <span m=''1736250''>choose</span> <span m=''1736490''>an</span>
  <span m=''1736590''>edge</span> <span m=''1736830''>that</span> <span m=''1736990''>is</span>
  <span m=''1737140''>induced</span> <span m=''1737580''>in</span> <span m=''1737680''>this</span>
  <span m=''1738430''>subgraph.</span> <span m=''1739090''>You</span> <span m=''1739220''>can''t</span>
  <span m=''1739480''>choose</span> <span m=''1739770''>some</span> <span m=''1740040''>other</span>
  <span m=''1740260''>edge</span> <span m=''1740510''>out</span> <span m=''1740640''>here.</span>
  <span m=''1745380''>Question?</span> </p><p><span m=''1745800''>AUDIENCE: So</span>
  <span m=''1746266''>this seems</span> <span m=''1746732''>kind of</span> <span m=''1747198''>cheap</span>
  <span m=''1748130''>because</span> <span m=''1748596''>we''re</span> <span m=''1749062''>using</span>
  <span m=''1749528''>the</span> <span m=''1749994''>graph</span> <span m=''1750460''>as</span>
  <span m=''1750845''>a</span> <span m=''1751230''>linkage</span> <span m=''1754640''>in</span>
  <span m=''1755090''>the end,</span> <span m=''1755440''>so</span> <span m=''1757040''>adding</span>
  <span m=''1757190''>these</span> <span m=''1757710''>extra</span> <span m=''1758440''>edges,</span>
  <span m=''1759040''>they</span> <span m=''1759260''>all</span> <span m=''1759910''>collapse</span>
  <span m=''1760420''>into</span> <span m=''1760610''>one.</span> </p><p><span m=''1761345''>PROFESSOR:
  Ah,</span> <span m=''1761790''>interesting.</span> <span m=''1762370''>Right.</span>
  <span m=''1762720''>So</span> <span m=''1762980''>why</span> <span m=''1763940''>this</span>
  <span m=''1764220''>feels</span> <span m=''1764450''>like</span> <span m=''1764640''>cheating</span>
  <span m=''1765010''>because,</span> <span m=''1766040''>from</span> <span m=''1766290''>a</span>
  <span m=''1766350''>linkage</span> <span m=''1766770''>perspective,</span> <span
  m=''1767410''>these</span> <span m=''1768490''>2</span> <span m=''1768630''>guys</span>
  <span m=''1769110''>have</span> <span m=''1769350''>exactly</span> <span m=''1769830''>the</span>
  <span m=''1769960''>same</span> <span m=''1770200''>constraints.</span> </p><p><span
  m=''1770550''>AUDIENCE: Yeah.</span> </p><p><span m=''1772440''>PROFESSOR: I</span>
  <span m=''1772620''>agree.</span> <span m=''1773020''>It''s</span> <span m=''1773220''>weird.</span>
  <span m=''1774420''>At</span> <span m=''1774820''>this</span> <span m=''1775070''>point,</span>
  <span m=''1776620''>this</span> <span m=''1777420''>is</span> <span m=''1777590''>a</span>
  <span m=''1777710''>device.</span> <span m=''1778350''>You</span> <span m=''1778470''>could</span>
  <span m=''1778630''>think</span> <span m=''1778820''>of</span> <span m=''1778910''>it</span>
  <span m=''1779000''>as</span> <span m=''1779140''>adding</span> <span m=''1779430''>edges.</span>
  <span m=''1780240''>Another</span> <span m=''1780610''>way</span> <span m=''1780710''>to</span>
  <span m=''1780800''>think</span> <span m=''1781010''>of</span> <span m=''1781100''>it</span>
  <span m=''1781180''>is</span> <span m=''1781630''>this</span> <span m=''1781910''>edge</span>
  <span m=''1782210''>has</span> <span m=''1782560''>to</span> <span m=''1782700''>be</span>
  <span m=''1782910''>covered</span> <span m=''1783360''>by</span> <span m=''1783510''>four</span>
  <span m=''1783820''>pebbles.</span> <span m=''1785250''>That''s</span> <span m=''1785460''>probably</span>
  <span m=''1785810''>a</span> <span m=''1785860''>little</span> <span m=''1786120''>more</span>
  <span m=''1786480''>intuitive.</span> <span m=''1787310''>So</span> <span m=''1787540''>having</span>
  <span m=''1787870''>to</span> <span m=''1787940''>cover</span> <span m=''1788260''>an
  edge</span> <span m=''1788400''>by</span> <span m=''1788530''>four</span> <span
  m=''1788770''>pebbles,</span> <span m=''1789140''>essentially,</span> <span m=''1789810''>is</span>
  <span m=''1789950''>pinning</span> <span m=''1790340''>the</span> <span m=''1790480''>edge.</span>
  <span m=''1791540''>Because</span> <span m=''1792070''>on</span> <span m=''1792250''>the</span>
  <span m=''1792340''>one</span> <span m=''1792540''>hand,</span> <span m=''1792780''>you</span>
  <span m=''1792880''>have</span> <span m=''1793020''>a</span> <span m=''1793070''>single</span>
  <span m=''1793370''>pebble</span> <span m=''1793700''>just</span> <span m=''1793880''>to</span>
  <span m=''1793960''>say</span> <span m=''1794390''>this</span> <span m=''1794630''>is</span>
  <span m=''1794810''>an</span> <span m=''1794930''>edge.</span> </p><p><span m=''1795780''>And</span>
  <span m=''1796010''>then</span> <span m=''1796110''>you</span> <span m=''1796190''>have</span>
  <span m=''1796320''>three</span> <span m=''1796510''>more</span> <span m=''1796700''>pebbles</span>
  <span m=''1797110''>to</span> <span m=''1797230''>eat</span> <span m=''1797470''>up</span>
  <span m=''1797640''>the</span> <span m=''1797740''>translations</span> <span m=''1798300''>and</span>
  <span m=''1798390''>rotations.</span> <span m=''1799040''>That''s</span> <span m=''1799230''>intuitively</span>
  <span m=''1799730''>what''s</span> <span m=''1799940''>going</span> <span m=''1800210''>on.</span>
  <span m=''1801480''>I</span> <span m=''1801730''>agree</span> <span m=''1801980''>this</span>
  <span m=''1802190''>looks</span> <span m=''1802430''>weird.</span> <span m=''1804470''>And</span>
  <span m=''1804740''>at</span> <span m=''1804830''>this</span> <span m=''1805000''>point,</span>
  <span m=''1805200''>we''re</span> <span m=''1805330''>just</span> <span m=''1805640''>playing</span>
  <span m=''1806390''>the</span> <span m=''1806490''>graph</span> <span m=''1806750''>theory</span>
  <span m=''1807010''>game</span> <span m=''1807310''>and</span> <span m=''1807390''>ignoring</span>
  <span m=''1807800''>the</span> <span m=''1807870''>linkages.</span> <span m=''1808740''>That''s</span>
  <span m=''1809040''>the</span> <span m=''1809100''>short</span> <span m=''1809320''>answer</span>
  <span m=''1809570''>why</span> <span m=''1809730''>this</span> <span m=''1809870''>is</span>
  <span m=''1810000''>OK.</span> <span m=''1811090''>But</span> <span m=''1811280''>ultimately,</span>
  <span m=''1811900''>intuitively,</span> <span m=''1812460''>what''s</span> <span
  m=''1812690''>going</span> <span m=''1812980''>on</span> <span m=''1813110''>is</span>
  <span m=''1813240''>that</span> <span m=''1814100''>these</span> <span m=''1814410''>three</span>
  <span m=''1814640''>edges</span> <span m=''1814890''>are</span> <span m=''1814960''>just</span>
  <span m=''1815180''>representing</span> <span m=''1815820''>the</span> <span m=''1815930''>translations</span>
  <span m=''1816205''>and</span> <span m=''1816480''>rotations</span> <span m=''1817040''>being</span>
  <span m=''1817260''>eaten.</span> </p><p><span m=''1818750''>And</span> <span m=''1818910''>they</span>
  <span m=''1819000''>have</span> <span m=''1819190''>to</span> <span m=''1819320''>be</span>
  <span m=''1819620''>somehow</span> <span m=''1820070''>eatable</span> <span m=''1821230''>universally</span>
  <span m=''1821940''>at</span> <span m=''1822010''>every</span> <span m=''1822270''>edge.</span>
  <span m=''1822660''>That''s</span> <span m=''1822910''>what</span> <span m=''1823240''>this</span>
  <span m=''1823470''>is</span> <span m=''1823560''>saying.</span> <span m=''1825270''>I
  don''t</span> <span m=''1825410''>have</span> <span m=''1825530''>a</span> <span
  m=''1825580''>great</span> <span m=''1825800''>intuition</span> <span m=''1826230''>for</span>
  <span m=''1826340''>that,</span> <span m=''1826610''>but</span> <span m=''1827300''>it</span>
  <span m=''1827480''>is--</span> <span m=''1828660''>pretty</span> <span m=''1828850''>sure</span>
  <span m=''1829050''>you</span> <span m=''1829160''>do</span> <span m=''1829280''>need</span>
  <span m=''1829450''>to</span> <span m=''1829530''>say</span> <span m=''1829740''>for</span>
  <span m=''1829900''>every</span> <span m=''1830270''>edge,</span> <span m=''1830530''>not</span>
  <span m=''1830750''>just</span> <span m=''1830940''>some</span> <span m=''1831260''>edge.</span>
  </p><p><span m=''1835950''>So</span> <span m=''1837160''>at</span> <span m=''1837310''>this</span>
  <span m=''1837450''>point,</span> <span m=''1837630''>you</span> <span m=''1837710''>have</span>
  <span m=''1837860''>a</span> <span m=''1837930''>polynomial</span> <span m=''1838410''>time</span>
  <span m=''1838650''>algorithm,</span> <span m=''1839060''>so I''m</span> <span m=''1839580''>done.</span>
  <span m=''1840360''>But</span> <span m=''1840490''>let</span> <span m=''1840640''>me</span>
  <span m=''1840770''>briefly</span> <span m=''1841160''>mention</span> <span m=''1841550''>how</span>
  <span m=''1841690''>you</span> <span m=''1841890''>could</span> <span m=''1842050''>make</span>
  <span m=''1842280''>it</span> <span m=''1842810''>faster</span> <span m=''1844260''>by</span>
  <span m=''1844520''>modifying</span> <span m=''1845160''>this</span> <span m=''1845360''>algorithm</span>
  <span m=''1846130''>to</span> <span m=''1846340''>do</span> <span m=''1846590''>the</span>
  <span m=''1846760''>2k</span> <span m=''1847160''>minus</span> <span m=''1848040''>3</span>
  <span m=''1848270''>situation.</span> <span m=''1850360''>Dare</span> <span m=''1850700''>I--</span>
  <span m=''1852605''>I</span> <span m=''1852860''>won''t</span> <span m=''1853300''>literally</span>
  <span m=''1853760''>modify</span> <span m=''1854160''>the</span> <span m=''1854250''>algorithm.</span>
  <span m=''1854630''>I''ll</span> <span m=''1854970''>write</span> <span m=''1855930''>a</span>
  <span m=''1856010''>new</span> <span m=''1856150''>version.</span> <span m=''1857090''>But</span>
  <span m=''1857240''>I''m</span> <span m=''1857340''>going</span> <span m=''1857440''>to</span>
  <span m=''1857490''>use</span> <span m=''1857720''>that</span> <span m=''1857940''>as</span>
  <span m=''1858170''>a</span> <span m=''1858450''>subroutine</span> <span m=''1859090''>basically.</span>
  </p><p><span m=''1875990''>And</span> <span m=''1876330''>so</span> <span m=''1877420''>algorithm</span>
  <span m=''1882890''>2k</span> <span m=''1883440''>minus</span> <span m=''1883830''>3</span>
  <span m=''1884070''>version.</span> <span m=''1886150''>So</span> <span m=''1886290''>it''s</span>
  <span m=''1886390''>going</span> <span m=''1886510''>to</span> <span m=''1886570''>be</span>
  <span m=''1886700''>the</span> <span m=''1886780''>same</span> <span m=''1887020''>style.</span>
  <span m=''1887770''>We''re</span> <span m=''1887870''>going</span> <span m=''1887950''>to</span>
  <span m=''1888010''>add</span> <span m=''1888260''>edges</span> <span m=''1888530''>one</span>
  <span m=''1888700''>at</span> <span m=''1888750''>a</span> <span m=''1888850''>time.</span>
  <span m=''1889390''>We''ll</span> <span m=''1889460''>direct</span> <span m=''1889740''>the</span>
  <span m=''1889840''>edges</span> <span m=''1890130''>in</span> <span m=''1890220''>the</span>
  <span m=''1890280''>same</span> <span m=''1890550''>way</span> <span m=''1890970''>for</span>
  <span m=''1891210''>each</span> <span m=''1891500''>added</span> <span m=''1891790''>edge</span>
  <span m=''1892010''>v-w.</span> <span m=''1893610''>I''ll</span> <span m=''1893800''>just</span>
  <span m=''1893990''>write</span> <span m=''1894220''>for</span> <span m=''1894330''>each</span>
  <span m=''1894760''>added</span> <span m=''1895080''>edge</span> <span m=''1900047''>v-w.</span>
  <span m=''1905700''>Before</span> <span m=''1906470''>I</span> <span m=''1906620''>just</span>
  <span m=''1906820''>tried</span> <span m=''1907160''>to</span> <span m=''1907670''>add</span>
  <span m=''1907920''>the</span> <span m=''1908050''>edge</span> <span m=''1908440''>and</span>
  <span m=''1908760''>cover</span> <span m=''1909140''>it</span> <span m=''1909360''>with</span>
  <span m=''1910000''>pebble.</span> <span m=''1911400''>Now,</span> <span m=''1911560''>I</span>
  <span m=''1911630''>want</span> <span m=''1911830''>to</span> <span m=''1911890''>cover</span>
  <span m=''1912230''>it</span> <span m=''1912320''>with</span> <span m=''1912530''>four</span>
  <span m=''1912780''>pebbles.</span> <span m=''1913270''>I</span> <span m=''1913360''>want</span>
  <span m=''1913690''>to</span> <span m=''1914700''>basically</span> <span m=''1915080''>add</span>
  <span m=''1915280''>the</span> <span m=''1915410''>edge</span> <span m=''1915630''>four</span>
  <span m=''1915850''>times.</span> </p><p><span m=''1927150''>I''m</span> <span m=''1927340''>going</span>
  <span m=''1927480''>to</span> <span m=''1927560''>write</span> <span m=''1927850''>as</span>
  <span m=''1928140''>above</span> <span m=''1929660''>to</span> <span m=''1929840''>mean</span>
  <span m=''1931340''>this</span> <span m=''1931660''>step.</span> <span m=''1932660''>So</span>
  <span m=''1932820''>every</span> <span m=''1933070''>time</span> <span m=''1933280''>I</span>
  <span m=''1933340''>add</span> <span m=''1933530''>the</span> <span m=''1933650''>edge,</span>
  <span m=''1934040''>I</span> <span m=''1934150''>search</span> <span m=''1934500''>for
  a</span> <span m=''1934670''>directed</span> <span m=''1935030''>path</span> <span
  m=''1935450''>from</span> <span m=''1935750''>v or</span> <span m=''1936010''>w</span>
  <span m=''1937110''>for</span> <span m=''1937390''>free</span> <span m=''1937670''>pebble.</span>
  <span m=''1938520''>When</span> <span m=''1938660''>I</span> <span m=''1938730''>find</span>
  <span m=''1939050''>it,</span> <span m=''1939520''>I</span> <span m=''1939660''>do</span>
  <span m=''1939880''>the</span> <span m=''1940420''>pebble</span> <span m=''1940700''>shift.</span>
  <span m=''1942000''>I</span> <span m=''1942090''>do</span> <span m=''1942220''>that</span>
  <span m=''1942520''>four</span> <span m=''1942770''>times.</span> <span m=''1944170''>Then</span>
  <span m=''1944370''>basically,</span> <span m=''1944690''>I</span> <span m=''1944760''>have</span>
  <span m=''1945030''>four</span> <span m=''1945420''>pebbles</span> <span m=''1945880''>on</span>
  <span m=''1946020''>the</span> <span m=''1946160''>edge,</span> <span m=''1946490''>or</span>
  <span m=''1946600''>you</span> <span m=''1946670''>could think of</span> <span m=''1947000''>them</span>
  <span m=''1947180''>as</span> <span m=''1947300''>being</span> <span m=''1947490''>four</span>
  <span m=''1947700''>copies</span> <span m=''1948100''>of</span> <span m=''1948210''>the</span>
  <span m=''1948320''>edge,</span> <span m=''1948650''>each</span> <span m=''1948880''>has</span>
  <span m=''1949080''>one</span> <span m=''1949320''>pebble.</span> </p><p><span m=''1950560''>Either</span>
  <span m=''1950810''>I</span> <span m=''1950880''>succeed</span> <span m=''1951200''>and</span>
  <span m=''1951520''>I</span> <span m=''1951570''>get</span> <span m=''1951730''>all</span>
  <span m=''1951890''>four,</span> <span m=''1952390''>or</span> <span m=''1952570''>I</span>
  <span m=''1952620''>don''t</span> <span m=''1952890''>get</span> <span m=''1953010''>all</span>
  <span m=''1953170''>four.</span> <span m=''1956500''>On</span> <span m=''1956760''>success,</span>
  <span m=''1962130''>this</span> <span m=''1962350''>is</span> <span m=''1962440''>just</span>
  <span m=''1962620''>a</span> <span m=''1962680''>temporary</span> <span m=''1963120''>measure.</span>
  <span m=''1963530''>At</span> <span m=''1963620''>that</span> <span m=''1963790''>point,</span>
  <span m=''1964120''>I''m</span> <span m=''1964220''>going</span> <span m=''1964320''>to</span>
  <span m=''1964420''>delete</span> <span m=''1964660''>three</span> <span m=''1964890''>of
  the</span> <span m=''1964990''>copies.</span> <span m=''1966480''>Put</span> <span
  m=''1966620''>it</span> <span m=''1966710''>back</span> <span m=''1966980''>to</span>
  <span m=''1967110''>a</span> <span m=''1967190''>regular</span> <span m=''1967630''>single</span>
  <span m=''1967990''>edge.</span> <span m=''1968800''>This</span> <span m=''1969070''>frees</span>
  <span m=''1970740''>three</span> <span m=''1970910''>pebbles</span> <span m=''1971960''>for</span>
  <span m=''1972160''>future</span> <span m=''1972500''>use.</span> <span m=''1974410''>So</span>
  <span m=''1974450''>I</span> <span m=''1974480''>don''t</span> <span m=''1974650''>want</span>
  <span m=''1974810''>every</span> <span m=''1975120''>edge</span> <span m=''1975290''>to</span>
  <span m=''1975370''>be</span> <span m=''1975490''>quadrupled.</span> <span m=''1978910''>I</span>
  <span m=''1979010''>don''t</span> <span m=''1979140''>want</span> <span m=''1979270''>them</span>
  <span m=''1979410''>all</span> <span m=''1979500''>to be</span> <span m=''1979570''>quadrupled</span>
  <span m=''1980100''>at</span> <span m=''1980300''>once.</span> <span m=''1980790''>I</span>
  <span m=''1980880''>want</span> <span m=''1981060''>to</span> <span m=''1981120''>try</span>
  <span m=''1981500''>quadrupling</span> <span m=''1982050''>one</span> <span m=''1982210''>edge,</span>
  <span m=''1982430''>then</span> <span m=''1982590''>try</span> <span m=''1982830''>quadrupling</span>
  <span m=''1983400''>the</span> <span m=''1983480''>next</span> <span m=''1983750''>edge,</span>
  <span m=''1983950''>try</span> <span m=''1984180''>quadrupling</span> <span m=''1984690''>the</span>
  <span m=''1984760''>next</span> <span m=''1985020''>edge.</span> </p><p><span m=''1985210''>But</span>
  <span m=''1986140''>when</span> <span m=''1986320''>I''m</span> <span m=''1986960''>quadrupling</span>
  <span m=''1987440''>an</span> <span m=''1987520''>edge,</span> <span m=''1987720''>all</span>
  <span m=''1987910''>the</span> <span m=''1988040''>other</span> <span m=''1988250''>edges</span>
  <span m=''1988520''>exist</span> <span m=''1988860''>as</span> <span m=''1988940''>single</span>
  <span m=''1989260''>edges.</span> <span m=''1990690''>So</span> <span m=''1990910''>I</span>
  <span m=''1991030''>delete</span> <span m=''1992160''>the</span> <span m=''1992280''>three</span>
  <span m=''1992470''>copies.</span> <span m=''1992980''>And</span> <span m=''1992990''>then</span>
  <span m=''1993120''>this</span> <span m=''1993300''>four</span> <span m=''1993470''>loop</span>
  <span m=''1993660''>continues</span> <span m=''1994700''>and</span> <span m=''1994870''>tries</span>
  <span m=''1995070''>the</span> <span m=''1995170''>next</span> <span m=''1995430''>edge.</span>
  <span m=''1997400''>On</span> <span m=''1997610''>failure--</span> <span m=''2000670''>here</span>
  <span m=''2000930''>I''m</span> <span m=''2000990''>going</span> <span m=''2001100''>to</span>
  <span m=''2001540''>say</span> <span m=''2001780''>something</span> <span m=''2002120''>more</span>
  <span m=''2002290''>interesting--</span> <span m=''2002600''>Normally,</span> <span
  m=''2002890''>on</span> <span m=''2003040''>failure</span> <span m=''2003300''>I''d</span>
  <span m=''2003430''>say,</span> <span m=''2003590''>well,</span> <span m=''2004150''>you</span>
  <span m=''2004250''>don''t</span> <span m=''2004410''>satisfy</span> <span m=''2004770''>the</span>
  <span m=''2004880''>2k</span> <span m=''2005140''>minus</span> <span m=''2005380''>3</span>
  <span m=''2005520''>property.</span> <span m=''2006500''>Game</span> <span m=''2006730''>over.</span>
  </p><p><span m=''2007690''>But</span> <span m=''2007860''>you</span> <span m=''2008040''>can</span>
  <span m=''2008830''>be</span> <span m=''2008980''>a</span> <span m=''2009030''>little</span>
  <span m=''2009240''>more</span> <span m=''2009850''>sophisticated.</span> <span
  m=''2011820''>Just</span> <span m=''2011990''>say</span> <span m=''2013850''>delete</span>
  <span m=''2014090''>all</span> <span m=''2014220''>the</span> <span m=''2014310''>copies</span>
  <span m=''2014670''>of</span> <span m=''2014750''>e.</span> <span m=''2014970''>I</span>
  <span m=''2015420''>guess</span> <span m=''2015680''>there''s</span> <span m=''2015850''>four
  of</span> <span m=''2016080''>them.</span> <span m=''2016960''>Whatever</span> <span
  m=''2017270''>pebbles</span> <span m=''2017690''>you</span> <span m=''2017900''>can</span>
  <span m=''2018060''>acquire,</span> <span m=''2019080''>you</span> <span m=''2019170''>give</span>
  <span m=''2019350''>them</span> <span m=''2019520''>up.</span> <span m=''2020690''>Delete</span>
  <span m=''2020980''>the</span> <span m=''2021110''>edge</span> <span m=''2021550''>and</span>
  <span m=''2022470''>call</span> <span m=''2022740''>the</span> <span m=''2022870''>edge</span>
  <span m=''2023100''>redundant.</span> <span m=''2028870''>Basically,</span> <span
  m=''2029530''>in</span> <span m=''2029660''>this</span> <span m=''2029880''>case,</span>
  <span m=''2030190''>you</span> <span m=''2030320''>could</span> <span m=''2030470''>argue</span>
  <span m=''2031250''>that</span> <span m=''2031450''>edge</span> <span m=''2031760''>was</span>
  <span m=''2031920''>superfluous</span> <span m=''2032650''>for</span> <span m=''2032810''>rigidity</span>
  <span m=''2033260''>purposes.</span> <span m=''2033850''>You</span> <span m=''2033930''>didn''t</span>
  <span m=''2034190''>need</span> <span m=''2034400''>it.</span> </p><p><span m=''2035650''>So</span>
  <span m=''2036470''>the</span> <span m=''2036610''>algorithm</span> <span m=''2037000''>doesn''t</span>
  <span m=''2037240''>just</span> <span m=''2037440''>fail.</span> <span m=''2037800''>It</span>
  <span m=''2037890''>says</span> <span m=''2038340''>this</span> <span m=''2038540''>was</span>
  <span m=''2038740''>a</span> <span m=''2038790''>useless</span> <span m=''2039170''>edge.</span>
  <span m=''2040230''>And</span> <span m=''2040380''>it''ll</span> <span m=''2040460''>tell</span>
  <span m=''2040660''>you</span> <span m=''2040820''>which</span> <span m=''2041020''>edges</span>
  <span m=''2041360''>are</span> <span m=''2041670''>useful,</span> <span m=''2042320''>which</span>
  <span m=''2042530''>ones</span> <span m=''2042720''>are</span> <span m=''2042790''>non-redundant</span>
  <span m=''2043750''>from</span> <span m=''2044050''>a</span> <span m=''2044130''>rigidity</span>
  <span m=''2044560''>standpoint.</span> <span m=''2045660''>And</span> <span m=''2045720''>then</span>
  <span m=''2045820''>when</span> <span m=''2045910''>you''re</span> <span m=''2046040''>done,</span>
  <span m=''2049050''>you</span> <span m=''2049270''>will</span> <span m=''2049400''>be</span>
  <span m=''2049590''>rigid</span> <span m=''2052420''>if</span> <span m=''2052630''>and</span>
  <span m=''2052710''>only</span> <span m=''2052989''>if</span> <span m=''2053790''>the</span>
  <span m=''2054120''>number</span> <span m=''2054540''>of</span> <span m=''2054600''>non-redundant</span>
  <span m=''2055290''>edges</span> <span m=''2055780''>that</span> <span m=''2055909''>remain</span>
  <span m=''2063690''>equals</span> <span m=''2064400''>2n</span> <span m=''2064790''>minus</span>
  <span m=''2065170''>3.</span> </p><p><span m=''2067139''>So</span> <span m=''2067310''>that''s</span>
  <span m=''2067790''>the</span> <span m=''2067880''>last</span> <span m=''2068190''>part</span>
  <span m=''2068389''>of</span> <span m=''2068449''>the</span> <span m=''2068550''>Laman</span>
  <span m=''2068960''>check.</span> <span m=''2069690''>So</span> <span m=''2069909''>this</span>
  <span m=''2070239''>is</span> <span m=''2070489''>giving</span> <span m=''2070760''>you</span>
  <span m=''2070900''>a</span> <span m=''2070920''>little</span> <span m=''2071120''>bit</span>
  <span m=''2071270''>more</span> <span m=''2071429''>information</span> <span m=''2071870''>than</span>
  <span m=''2072040''>just</span> <span m=''2072330''>do</span> <span m=''2072480''>I</span>
  <span m=''2072570''>satisfy</span> <span m=''2073010''>the</span> <span m=''2073139''>2k</span>
  <span m=''2073420''>minus</span> <span m=''2073750''>3</span> <span m=''2073880''>property.</span>
  <span m=''2074719''>To</span> <span m=''2074820''>get</span> <span m=''2074989''>that,
  you</span> <span m=''2075250''>just</span> <span m=''2075560''>check</span> <span
  m=''2075770''>whether</span> <span m=''2075940''>you</span> <span m=''2076070''>ever</span>
  <span m=''2076250''>failed.</span> <span m=''2077560''>But</span> <span m=''2077710''>in</span>
  <span m=''2077780''>this</span> <span m=''2077940''>case,</span> <span m=''2078250''>you</span>
  <span m=''2078350''>can</span> <span m=''2078360''>actually</span> <span m=''2078620''>see,</span>
  <span m=''2079210''>ah,</span> <span m=''2079460''>these</span> <span m=''2079770''>are</span>
  <span m=''2079949''>the</span> <span m=''2080489''>useless</span> <span m=''2080860''>edges.</span>
  <span m=''2081590''>They''re</span> <span m=''2082300''>those</span> <span m=''2082820''>overbracing</span>
  <span m=''2083489''>edges.</span> <span m=''2084489''>Everything</span> <span m=''2084889''>else</span>
  <span m=''2085110''>is</span> <span m=''2085199''>useful.</span> </p><p><span m=''2085980''>And</span>
  <span m=''2086120''>if</span> <span m=''2086219''>I</span> <span m=''2086300''>end</span>
  <span m=''2086510''>up</span> <span m=''2086630''>having</span> <span m=''2087000''>enough</span>
  <span m=''2087250''>useful</span> <span m=''2087620''>edges</span> <span m=''2087949''>to</span>
  <span m=''2088070''>n</span> <span m=''2088179''>minus</span> <span m=''2088429''>3</span>
  <span m=''2088630''>of</span> <span m=''2088690''>them,</span> <span m=''2089270''>then</span>
  <span m=''2089699''>I</span> <span m=''2089840''>know</span> <span m=''2091429''>I''m</span>
  <span m=''2091590''>rigid.</span> <span m=''2091980''>Otherwise,</span> <span m=''2092420''>I''m</span>
  <span m=''2092480''>going</span> <span m=''2092590''>to</span> <span m=''2092630''>be</span>
  <span m=''2092739''>flexible.</span> <span m=''2093530''>So</span> <span m=''2093659''>this</span>
  <span m=''2093900''>gives</span> <span m=''2094060''>you</span> <span m=''2094190''>all</span>
  <span m=''2094409''>the</span> <span m=''2094500''>information</span> <span m=''2095449''>you</span>
  <span m=''2095600''>want.</span> <span m=''2096320''>With</span> <span m=''2096429''>a</span>
  <span m=''2096480''>little</span> <span m=''2096690''>bit</span> <span m=''2096860''>more</span>
  <span m=''2097070''>effort,</span> <span m=''2097420''>you</span> <span m=''2097560''>could</span>
  <span m=''2097690''>even</span> <span m=''2097900''>figure</span> <span m=''2098170''>out</span>
  <span m=''2099370''>if</span> <span m=''2099540''>I''m</span> <span m=''2099920''>flexible,</span>
  <span m=''2100600''>which</span> <span m=''2100850''>parts</span> <span m=''2101230''>are</span>
  <span m=''2101330''>rigid</span> <span m=''2102040''>and</span> <span m=''2102620''>which</span>
  <span m=''2102840''>parts</span> <span m=''2103330''>can</span> <span m=''2103570''>move</span>
  <span m=''2103850''>relative</span> <span m=''2104190''>to</span> <span m=''2104310''>each</span>
  <span m=''2104460''>other.</span> </p><p><span m=''2106160''>This,</span> <span
  m=''2106330''>of</span> <span m=''2106430''>course,</span> <span m=''2106840''>generically</span>
  <span m=''2107330''>rigid.</span> <span m=''2110300''>Finally,</span> <span m=''2111220''>let</span>
  <span m=''2111330''>me</span> <span m=''2111450''>show</span> <span m=''2111770''>you</span>
  <span m=''2112360''>this</span> <span m=''2112590''>thing</span> <span m=''2112830''>in</span>
  <span m=''2112980''>action.</span> <span m=''2114970''>So</span> <span m=''2116030''>look</span>
  <span m=''2116390''>over</span> <span m=''2116680''>there.</span> <span m=''2118010''>This</span>
  <span m=''2118320''>is</span> <span m=''2118370''>an</span> <span m=''2118440''>implementation</span>
  <span m=''2119090''>by</span> <span m=''2119320''>Audrey</span> <span m=''2119640''>Lee-Saint</span>
  <span m=''2120010''>John.</span> <span m=''2121780''>And</span> <span m=''2122230''>so</span>
  <span m=''2122320''>here''s</span> <span m=''2122580''>a</span> <span m=''2122650''>simple</span>
  <span m=''2123210''>graph.</span> <span m=''2124050''>You</span> <span m=''2124210''>can</span>
  <span m=''2124370''>probably</span> <span m=''2124730''>see</span> <span m=''2125550''>this</span>
  <span m=''2125740''>top</span> <span m=''2126050''>part</span> <span m=''2126280''>is</span>
  <span m=''2126440''>flexible.</span> <span m=''2126765''>It''s</span> <span m=''2127090''>quadrilateral.</span>
  <span m=''2128070''>Bottom</span> <span m=''2128340''>part</span> <span m=''2128600''>is</span>
  <span m=''2128890''>overbraced.</span> <span m=''2131200''>This</span> <span m=''2131440''>is</span>
  <span m=''2131540''>in</span> <span m=''2131650''>2</span> <span m=''2131780''>dimensions,</span>
  <span m=''2132260''>right?</span> <span m=''2132440''>So</span> <span m=''2132590''>just</span>
  <span m=''2132860''>triangles</span> <span m=''2133300''>would</span> <span m=''2133390''>be</span>
  <span m=''2133500''>enough,</span> <span m=''2133830''>but</span> <span m=''2133960''>I''ve</span>
  <span m=''2134080''>added</span> <span m=''2134750''>an</span> <span m=''2134870''>extra</span>
  <span m=''2135150''>edge</span> <span m=''2135430''>here.</span> </p><p><span m=''2136750''>And</span>
  <span m=''2136860''>this</span> <span m=''2137020''>is</span> <span m=''2137110''>going</span>
  <span m=''2137230''>to</span> <span m=''2137320''>check</span> <span m=''2137720''>the
  Laman</span> <span m=''2138180''>condition</span> <span m=''2138610''>one</span>
  <span m=''2138920''>step</span> <span m=''2139200''>at</span> <span m=''2139270''>a</span>
  <span m=''2139330''>time.</span> <span m=''2140240''>So</span> <span m=''2140390''>we</span>
  <span m=''2140460''>start</span> <span m=''2140680''>with</span> <span m=''2140790''>2</span>
  <span m=''2140950''>pebbles</span> <span m=''2141470''>everywhere.</span> <span
  m=''2142340''>We</span> <span m=''2142410''>start</span> <span m=''2142680''>by</span>
  <span m=''2142790''>adding</span> <span m=''2143090''>that</span> <span m=''2143300''>top</span>
  <span m=''2143580''>edge.</span> <span m=''2144650''>Right</span> <span m=''2144930''>now,</span>
  <span m=''2145090''>there are four</span> <span m=''2145520''>pebbles</span> <span
  m=''2145920''>on</span> <span m=''2146060''>that</span> <span m=''2146220''>edge,</span>
  <span m=''2146640''>so</span> <span m=''2146800''>it''s</span> <span m=''2146980''>great.</span>
  <span m=''2147190''>I</span> <span m=''2147250''>can</span> <span m=''2147400''>just</span>
  <span m=''2147570''>add</span> <span m=''2147790''>the</span> <span m=''2147920''>edge.</span>
  <span m=''2148250''>Let''s</span> <span m=''2148470''>say</span> <span m=''2150100''>I</span>
  <span m=''2150250''>added</span> <span m=''2150630''>it</span> <span m=''2150720''>four</span>
  <span m=''2150930''>times.</span> <span m=''2151370''>There are</span> <span m=''2151450''>four</span>
  <span m=''2151710''>pebbles</span> <span m=''2151980''>there.</span> <span m=''2152470''>But</span>
  <span m=''2152620''>then</span> <span m=''2152880''>in</span> <span m=''2152950''>the</span>
  <span m=''2153090''>end,</span> <span m=''2153520''>I</span> <span m=''2153640''>just</span>
  <span m=''2153850''>need</span> <span m=''2153980''>one.</span> <span m=''2154770''>So</span>
  <span m=''2155300''>let''s</span> <span m=''2155680''>skip</span> <span m=''2156000''>that</span>
  <span m=''2156200''>step.</span> <span m=''2156470''>And</span> <span m=''2156570''>now</span>
  <span m=''2156750''>I''ve</span> <span m=''2156920''>got</span> <span m=''2157130''>the</span>
  <span m=''2157230''>one</span> <span m=''2157450''>pebble</span> <span m=''2157730''>from</span>
  <span m=''2157910''>b,</span> <span m=''2158290''>and</span> <span m=''2158670''>we''re</span>
  <span m=''2159050''>happy.</span> <span m=''2160190''>So</span> <span m=''2160350''>that</span>
  <span m=''2160640''>is</span> <span m=''2160820''>its</span> <span m=''2160970''>own</span>
  <span m=''2161210''>rigid</span> <span m=''2161550''>component.</span> </p><p><span
  m=''2163270''>Next,</span> <span m=''2163630''>let''s</span> <span m=''2163770''>add</span>
  <span m=''2163960''>this</span> <span m=''2164160''>edge</span> <span m=''2164450''>ef.</span>
  <span m=''2165700''>So</span> <span m=''2165900''>this</span> <span m=''2166080''>also</span>
  <span m=''2166290''>has</span> <span m=''2166450''>four</span> <span m=''2166620''>pebbles</span>
  <span m=''2166910''>on it,</span> <span m=''2167180''>so</span> <span m=''2167710''>we''re</span>
  <span m=''2167830''>done.</span> <span m=''2169010''>Next,</span> <span m=''2169300''>we</span>
  <span m=''2169360''>have</span> <span m=''2169420''>cd.</span> <span m=''2169810''>That</span>
  <span m=''2170030''>also</span> <span m=''2170310''>has--</span> <span m=''2170720''>you</span>
  <span m=''2170840''>could</span> <span m=''2171020''>change</span> <span m=''2171310''>the</span>
  <span m=''2171440''>order</span> <span m=''2171690''>if</span> <span m=''2171790''>you</span>
  <span m=''2172150''>think</span> <span m=''2172310''>this</span> <span m=''2172470''>one''s</span>
  <span m=''2172630''>a</span> <span m=''2172670''>little</span> <span m=''2172820''>trivial.</span>
  <span m=''2173150''>Now</span> <span m=''2173360''>is</span> <span m=''2173460''>when</span>
  <span m=''2173560''>the</span> <span m=''2173670''>action</span> <span m=''2173970''>happens.</span>
  <span m=''2174940''>Let''s</span> <span m=''2175210''>add</span> <span m=''2175480''>this</span>
  <span m=''2175710''>edge</span> <span m=''2176130''>bc.</span> <span m=''2177690''>So</span>
  <span m=''2177880''>currently,</span> <span m=''2178270''>it</span> <span m=''2178340''>is</span>
  <span m=''2178570''>only</span> <span m=''2178970''>covered</span> <span m=''2179550''>by</span>
  <span m=''2180610''>three</span> <span m=''2180830''>pebbles.</span> <span m=''2181380''>But</span>
  <span m=''2181510''>we</span> <span m=''2181640''>need</span> <span m=''2181820''>a</span>
  <span m=''2181860''>fourth.</span> <span m=''2183910''>So</span> <span m=''2184270''>we''re</span>
  <span m=''2184420''>going</span> <span m=''2184720''>to</span> <span m=''2185160''>take</span>
  <span m=''2185430''>one</span> <span m=''2185570''>of</span> <span m=''2185640''>these</span>
  <span m=''2185940''>free</span> <span m=''2186210''>pebbles</span> <span m=''2186580''>on</span>
  <span m=''2186760''>a</span> <span m=''2187620''>and</span> <span m=''2187900''>move</span>
  <span m=''2188190''>it</span> <span m=''2188550''>along</span> <span m=''2188910''>b.</span>
  </p><p><span m=''2189150''>We</span> <span m=''2189280''>found</span> <span m=''2189620''>that</span>
  <span m=''2189820''>by</span> <span m=''2189930''>starting</span> <span m=''2190290''>from
  b and</span> <span m=''2190470''>searching</span> <span m=''2191340''>out</span>
  <span m=''2191960''>and</span> <span m=''2192130''>finding</span> <span m=''2192420''>a</span>
  <span m=''2192460''>free</span> <span m=''2192630''>pebble.</span> <span m=''2193160''>So</span>
  <span m=''2193390''>we</span> <span m=''2193480''>just</span> <span m=''2193720''>flip</span>
  <span m=''2193900''>that</span> <span m=''2194070''>edge.</span> <span m=''2194870''>Now</span>
  <span m=''2195010''>we''ve</span> <span m=''2195120''>got</span> <span m=''2195250''>a</span>
  <span m=''2195290''>free</span> <span m=''2195500''>pebble</span> <span m=''2195800''>on
  b.</span> <span m=''2195950''>Now</span> <span m=''2196376''>we''ve</span> <span
  m=''2196802''>got</span> <span m=''2197230''>four</span> <span m=''2197590''>pebbles</span>
  <span m=''2197920''>on</span> <span m=''2198040''>bc,</span> <span m=''2198610''>and</span>
  <span m=''2198670''>we</span> <span m=''2198770''>can</span> <span m=''2198900''>add</span>
  <span m=''2199040''>the</span> <span m=''2199160''>edge.</span> <span m=''2199930''>But</span>
  <span m=''2200070''>we</span> <span m=''2200250''>only</span> <span m=''2200440''>actually</span>
  <span m=''2200710''>take</span> <span m=''2200900''>one</span> <span m=''2201090''>of</span>
  <span m=''2201170''>them.</span> <span m=''2202280''>So</span> <span m=''2202300''>I''m</span>
  <span m=''2202910''>skipping</span> <span m=''2203260''>the</span> <span m=''2203350''>part</span>
  <span m=''2203580''>where we</span> <span m=''2203770''>add</span> <span m=''2203940''>the</span>
  <span m=''2204010''>four</span> <span m=''2204200''>copies</span> <span m=''2204550''>and</span>
  <span m=''2204640''>immediately</span> <span m=''2205030''>remove</span> <span m=''2205330''>three
  of them</span> <span m=''2205760''>because</span> <span m=''2205950''>that''s</span>
  <span m=''2206370''>silly.</span> </p><p><span m=''2208510''>Cool.</span> <span
  m=''2208810''>So</span> <span m=''2208960''>that''s</span> <span m=''2209310''>its</span>
  <span m=''2209480''>own</span> <span m=''2209670''>rigid</span> <span m=''2209940''>component</span>
  <span m=''2210210''>it</span> <span m=''2210480''>turns</span> <span m=''2210720''>out.</span>
  <span m=''2210910''>Each</span> <span m=''2211110''>of</span> <span m=''2211180''>these</span>
  <span m=''2211360''>things</span> <span m=''2211580''>is</span> <span m=''2211780''>independently--</span>
  <span m=''2213320''>the</span> <span m=''2213440''>colors</span> <span m=''2213930''>represent</span>
  <span m=''2214570''>rigid</span> <span m=''2214840''>components.</span> <span m=''2215690''>And</span>
  <span m=''2215910''>right</span> <span m=''2216080''>now</span> <span m=''2216590''>nothing</span>
  <span m=''2217030''>is</span> <span m=''2217180''>tied</span> <span m=''2217450''>together.</span>
  <span m=''2217820''>Everything''s</span> <span m=''2218200''>flexible.</span> <span
  m=''2218780''>Flexible</span> <span m=''2219030''>at</span> <span m=''2219230''>b.</span>
  <span m=''2219450''>Flexible</span> <span m=''2219800''>at</span> <span m=''2219940''>c.</span>
  <span m=''2221750''>Let''s</span> <span m=''2222030''>add</span> <span m=''2222290''>this</span>
  <span m=''2222430''>diagonal</span> <span m=''2223940''>df.</span> <span m=''2225770''>So</span>
  <span m=''2225940''>right</span> <span m=''2226110''>now, it</span> <span m=''2226240''>only</span>
  <span m=''2226390''>has</span> <span m=''2226520''>one</span> <span m=''2226760''>pebble,</span>
  <span m=''2227040''>which</span> <span m=''2227230''>means</span> <span m=''2227450''>we</span>
  <span m=''2228100''>need</span> <span m=''2228240''>four</span> <span m=''2228450''>pebbles.</span>
  </p><p><span m=''2228750''>So</span> <span m=''2228890''>we''re</span> <span m=''2228960''>actually</span>
  <span m=''2229180''>going</span> <span m=''2229270''>to</span> <span m=''2229310''>have</span>
  <span m=''2229430''>to</span> <span m=''2230290''>get</span> <span m=''2230460''>one
  at</span> <span m=''2230610''>f,</span> <span m=''2230960''>and we''re</span> <span
  m=''2231040''>going</span> <span m=''2231140''>to</span> <span m=''2231180''>have</span>
  <span m=''2231470''>to</span> <span m=''2231570''>get</span> <span m=''2231740''>one</span>
  <span m=''2231900''>at</span> <span m=''2232020''>d</span> <span m=''2232270''>because</span>
  <span m=''2233000''>there</span> <span m=''2233110''>can</span> <span m=''2233210''>only</span>
  <span m=''2233360''>be</span> <span m=''2233490''>two</span> <span m=''2233690''>at</span>
  <span m=''2233750''>each.</span> <span m=''2234880''>So</span> <span m=''2235630''>first,</span>
  <span m=''2236010''>we''ll</span> <span m=''2236160''>do</span> <span m=''2237330''>I</span>
  <span m=''2237470''>guess</span> <span m=''2237660''>a</span> <span m=''2237720''>search</span>
  <span m=''2237980''>from</span> <span m=''2238150''>d, and</span> <span m=''2239020''>we</span>
  <span m=''2239100''>immediately</span> <span m=''2239460''>find</span> <span m=''2239660''>a</span>
  <span m=''2239730''>pebble.</span> <span m=''2240470''>We</span> <span m=''2240590''>move</span>
  <span m=''2240790''>it</span> <span m=''2240870''>down</span> <span m=''2241130''>there.</span>
  <span m=''2241820''>Great.</span> <span m=''2242810''>Then,</span> <span m=''2243000''>we</span>
  <span m=''2243290''>search</span> <span m=''2243600''>from</span> <span m=''2243700''>f.</span>
  <span m=''2244160''>We</span> <span m=''2244180''>find</span> <span m=''2244380''>a</span>
  <span m=''2244430''>pebble</span> <span m=''2244710''>there.</span> <span m=''2245330''>We</span>
  <span m=''2245500''>move</span> <span m=''2245720''>it.</span> <span m=''2246460''>Boom!</span>
  <span m=''2246770''>We''ve</span> <span m=''2248470''>got</span> <span m=''2248630''>our</span>
  <span m=''2248750''>edge,</span> <span m=''2249170''>added</span> <span m=''2249650''>all
  four</span> <span m=''2249850''>pebbles.</span> </p><p><span m=''2251430''>Eventually</span>
  <span m=''2251800''>we''re</span> <span m=''2251920''>going</span> <span m=''2252040''>to</span>
  <span m=''2252110''>run</span> <span m=''2252250''>out</span> <span m=''2252360''>of</span>
  <span m=''2252420''>pebbles,</span> <span m=''2253220''>but</span> <span m=''2253410''>right</span>
  <span m=''2253570''>now,</span> <span m=''2253880''>we are</span> <span m=''2254000''>very</span>
  <span m=''2254240''>flexible.</span> <span m=''2255690''>Let''s</span> <span m=''2255890''>add</span>
  <span m=''2256030''>this</span> <span m=''2256180''>other</span> <span m=''2256360''>diagonal.</span>
  <span m=''2256630''>This</span> <span m=''2257080''>should</span> <span m=''2257260''>also</span>
  <span m=''2257460''>be</span> <span m=''2257570''>possible.</span> <span m=''2257950''>Right</span>
  <span m=''2258110''>now,</span> <span m=''2258250''>there''s</span> <span m=''2258400''>one</span>
  <span m=''2258610''>pebble</span> <span m=''2259050''>at e,</span> <span m=''2259250''>one
  pebble at</span> <span m=''2259600''>c.</span> <span m=''2261000''>We''ve</span>
  <span m=''2261170''>got</span> <span m=''2261360''>to</span> <span m=''2261770''>find</span>
  <span m=''2262170''>two</span> <span m=''2262300''>more</span> <span m=''2262450''>pebbles.</span>
  <span m=''2263350''>So</span> <span m=''2263520''>first,</span> <span m=''2263930''>we''ll</span>
  <span m=''2264050''>follow</span> <span m=''2264410''>this</span> <span m=''2264550''>edge.</span>
  <span m=''2264900''>Find</span> <span m=''2265140''>a</span> <span m=''2265190''>free</span>
  <span m=''2265380''>pebble at</span> <span m=''2265720''>f.</span> <span m=''2265930''>That
  was</span> <span m=''2266240''>easy.</span> <span m=''2267660''>Next,</span> <span
  m=''2268030''>we''ll</span> <span m=''2268180''>look</span> <span m=''2268420''>at</span>
  <span m=''2269970''>from</span> <span m=''2270250''>c.</span> <span m=''2271242''>There''s</span>
  <span m=''2271740''>only</span> <span m=''2271920''>one</span> <span m=''2272110''>way</span>
  <span m=''2272290''>we</span> <span m=''2272450''>can</span> <span m=''2272550''>go</span>
  <span m=''2272680''>from</span> <span m=''2272850''>c.</span> <span m=''2273060''>We</span>
  <span m=''2273170''>can''t</span> <span m=''2273400''>follow</span> <span m=''2273720''>the</span>
  <span m=''2273810''>back</span> <span m=''2274110''>edge.</span> <span m=''2274380''>Got</span>
  <span m=''2274520''>to</span> <span m=''2274600''>go</span> <span m=''2274730''>forward.</span>
  <span m=''2275650''>Got</span> <span m=''2275770''>a</span> <span m=''2275840''>pebble</span>
  <span m=''2276185''>at</span> <span m=''2276530''>d.</span> <span m=''2277810''>Flip</span>
  <span m=''2278110''>it</span> <span m=''2278170''>around.</span> <span m=''2279040''>Now,</span>
  <span m=''2279250''>we''ve</span> <span m=''2279410''>got</span> <span m=''2279710''>four</span>
  <span m=''2279880''>pebbles</span> <span m=''2280370''>on</span> <span m=''2280980''>c</span>
  <span m=''2281050''>and</span> <span m=''2281320''>e,</span> <span m=''2282380''>so</span>
  <span m=''2282530''>we</span> <span m=''2282650''>can</span> <span m=''2282770''>add</span>
  <span m=''2282910''>the</span> <span m=''2283020''>edge.</span> </p><p><span m=''2285980''>Now,</span>
  <span m=''2286040''>let''s</span> <span m=''2286290''>add</span> <span m=''2286520''>ef.</span>
  <span m=''2287030''>Right</span> <span m=''2287170''>now,</span> <span m=''2287320''>we''ve</span>
  <span m=''2287420''>only</span> <span m=''2287580''>got</span> <span m=''2287750''>one</span>
  <span m=''2288050''>pebble,</span> <span m=''2288480''>yet</span> <span m=''2288680''>we</span>
  <span m=''2288830''>need</span> <span m=''2289320''>four.</span> <span m=''2290810''>So</span>
  <span m=''2291110''>let''s</span> <span m=''2291350''>start</span> <span m=''2291660''>by</span>
  <span m=''2291790''>searching</span> <span m=''2292130''>from</span> <span m=''2292230''>a.</span>
  <span m=''2292730''>Oh, we</span> <span m=''2292830''>found</span> <span m=''2293030''>a
  pebble</span> <span m=''2293350''>immediately.</span> <span m=''2293860''>In</span>
  <span m=''2293960''>general,</span> <span m=''2294320''>we would have</span> <span
  m=''2294600''>to</span> <span m=''2294700''>follow</span> <span m=''2294980''>many</span>
  <span m=''2295270''>edges.</span> <span m=''2297570''>So</span> <span m=''2297680''>there''s</span>
  <span m=''2298000''>a</span> <span m=''2298360''>from</span> <span m=''2298720''>f.</span>
  <span m=''2299540''>There</span> <span m=''2299760''>are</span> <span m=''2299830''>two</span>
  <span m=''2300010''>ways</span> <span m=''2300220''>we</span> <span m=''2300320''>could</span>
  <span m=''2300470''>go.</span> <span m=''2300710''>Either</span> <span m=''2300970''>one</span>
  <span m=''2301150''>of</span> <span m=''2301210''>them</span> <span m=''2301380''>would</span>
  <span m=''2301490''>have</span> <span m=''2301590''>given</span> <span m=''2301840''>us</span>
  <span m=''2301980''>a</span> <span m=''2302040''>pebble.</span> <span m=''2302620''>Let''s</span>
  <span m=''2302850''>flip</span> <span m=''2303060''>the</span> <span m=''2303170''>yellow</span>
  <span m=''2303470''>edge.</span> <span m=''2304460''>Boom!</span> <span m=''2304610''>We''ve</span>
  <span m=''2304840''>got</span> <span m=''2305040''>f,</span> <span m=''2306790''>one</span>
  <span m=''2306990''>pebble,</span> <span m=''2307270''>but</span> <span m=''2307400''>we</span>
  <span m=''2307480''>need</span> <span m=''2307630''>another</span> <span m=''2307880''>one.</span>
  </p><p><span m=''2308740''>Now,</span> <span m=''2308960''>we</span> <span m=''2309060''>cannot</span>
  <span m=''2309400''>get</span> <span m=''2309530''>another</span> <span m=''2309790''>pebble</span>
  <span m=''2310020''>from</span> <span m=''2310150''>e</span> <span m=''2310390''>because</span>
  <span m=''2310580''>we</span> <span m=''2310690''>just</span> <span m=''2310840''>flipped</span>
  <span m=''2311030''>the</span> <span m=''2311140''>edge,</span> <span m=''2312160''>but</span>
  <span m=''2312280''>we</span> <span m=''2312420''>can</span> <span m=''2312500''>get</span>
  <span m=''2312620''>a</span> <span m=''2312690''>pebble</span> <span m=''2313000''>from
  d,</span> <span m=''2313200''>so</span> <span m=''2314400''>we</span> <span m=''2314530''>flip</span>
  <span m=''2314740''>that</span> <span m=''2314950''>edge.</span> <span m=''2316580''>And</span>
  <span m=''2317470''>now</span> <span m=''2317660''>we</span> <span m=''2317760''>can</span>
  <span m=''2317880''>add</span> <span m=''2318030''>the</span> <span m=''2318130''>edge</span>
  <span m=''2318360''>af</span> <span m=''2319380''>to</span> <span m=''2319520''>more</span>
  <span m=''2319720''>edges.</span> <span m=''2321350''>It''s</span> <span m=''2321580''>a</span>
  <span m=''2321620''>little</span> <span m=''2321810''>tedious.</span> <span m=''2323770''>So</span>
  <span m=''2324760''>next</span> <span m=''2325040''>is</span> <span m=''2325130''>cf.</span>
  <span m=''2325920''>We''re</span> <span m=''2326315''>running</span> <span m=''2326710''>out</span>
  <span m=''2326810''>of</span> <span m=''2326890''>pebbles</span> <span m=''2327260''>here.</span>
  <span m=''2328030''>There''s</span> <span m=''2328240''>only</span> <span m=''2329390''>five</span>
  <span m=''2329840''>pebbles</span> <span m=''2330200''>total</span> <span m=''2330530''>in</span>
  <span m=''2330600''>the</span> <span m=''2330680''>system.</span> <span m=''2331450''>We</span>
  <span m=''2331580''>need</span> <span m=''2331730''>four of</span> <span m=''2332030''>them</span>
  <span m=''2332220''>right</span> <span m=''2332400''>here</span> <span m=''2333580''>because</span>
  <span m=''2333770''>we''re</span> <span m=''2333890''>getting</span> <span m=''2334240''>almost</span>
  <span m=''2334650''>rigid.</span> </p><p><span m=''2336050''>So</span> <span m=''2336760''>let''s</span>
  <span m=''2336950''>see.</span> <span m=''2337190''>We''ve</span> <span m=''2337330''>got</span>
  <span m=''2337860''>cf.</span> <span m=''2339306''>Let''s</span> <span m=''2339790''>start</span>
  <span m=''2340020''>from</span> <span m=''2340180''>searching</span> <span m=''2340530''>from</span>
  <span m=''2340760''>f.</span> <span m=''2341180''>There''s</span> <span m=''2341320''>only</span>
  <span m=''2341480''>one</span> <span m=''2341670''>way</span> <span m=''2341820''>we</span>
  <span m=''2341990''>can</span> <span m=''2342110''>go.</span> <span m=''2342470''>We
  find</span> <span m=''2342690''>a</span> <span m=''2342750''>pebble.</span> <span
  m=''2343130''>We</span> <span m=''2343250''>flip</span> <span m=''2343490''>it</span>
  <span m=''2343570''>around.</span> <span m=''2344550''>Now</span> <span m=''2344790''>we''ve</span>
  <span m=''2344950''>got</span> <span m=''2345240''>c.</span> <span m=''2347220''>There''s</span>
  <span m=''2347390''>only</span> <span m=''2347640''>one</span> <span m=''2347960''>way</span>
  <span m=''2348120''>to</span> <span m=''2348200''>go</span> <span m=''2348370''>from</span>
  <span m=''2348540''>c.</span> <span m=''2348870''>We</span> <span m=''2349200''>find</span>
  <span m=''2349430''>the</span> <span m=''2349510''>pebble at</span> <span m=''2350000''>e.</span>
  <span m=''2350900''>And</span> <span m=''2351290''>we</span> <span m=''2351500''>flip</span>
  <span m=''2351730''>it</span> <span m=''2351800''>around.</span> <span m=''2352120''>Now</span>
  <span m=''2352300''>we''ve</span> <span m=''2352440''>got</span> <span m=''2353000''>the</span>
  <span m=''2353120''>two</span> <span m=''2353270''>pebbles.</span> <span m=''2354960''>Cool.</span>
  </p><p><span m=''2356150''>So</span> <span m=''2356340''>we''ve</span> <span m=''2356480''>got</span>
  <span m=''2356680''>the</span> <span m=''2356780''>three</span> <span m=''2357040''>pebbles</span>
  <span m=''2357300''>here,</span> <span m=''2357490''>which</span> <span m=''2357700''>are</span>
  <span m=''2357800''>representing</span> <span m=''2358390''>our</span> <span m=''2358490''>translations</span>
  <span m=''2359120''>and</span> <span m=''2359240''>rotations.</span> <span m=''2360230''>The</span>
  <span m=''2360390''>only</span> <span m=''2360700''>other</span> <span m=''2360880''>pebble</span>
  <span m=''2361210''>left</span> <span m=''2361490''>is</span> <span m=''2361630''>this</span>
  <span m=''2361840''>one,</span> <span m=''2362190''>which</span> <span m=''2362330''>is</span>
  <span m=''2362500''>basically</span> <span m=''2363000''>representing</span> <span
  m=''2363620''>the</span> <span m=''2363740''>degree</span> <span m=''2364040''>of</span>
  <span m=''2364110''>freedom</span> <span m=''2364770''>in</span> <span m=''2364940''>this</span>
  <span m=''2365090''>quadrilateral.</span> <span m=''2366490''>So</span> <span m=''2366660''>when</span>
  <span m=''2366770''>we</span> <span m=''2366880''>go</span> <span m=''2367080''>to</span>
  <span m=''2367270''>add</span> <span m=''2367580''>the</span> <span m=''2367680''>last</span>
  <span m=''2368020''>edge,</span> <span m=''2368280''>which</span> <span m=''2368510''>is--</span>
  <span m=''2368890''>so at</span> <span m=''2369090''>this</span> <span m=''2369270''>point,</span>
  <span m=''2369460''>this</span> <span m=''2369590''>is</span> <span m=''2369700''>a</span>
  <span m=''2369760''>ridge</span> <span m=''2369960''>it</span> <span m=''2370030''>component</span>
  <span m=''2371030''>because of</span> <span m=''2371240''>the</span> <span m=''2371350''>triangles.</span>
  <span m=''2373290''>And</span> <span m=''2373350''>we</span> <span m=''2373470''>go</span>
  <span m=''2373920''>to</span> <span m=''2374000''>add</span> <span m=''2374210''>the</span>
  <span m=''2374290''>last</span> <span m=''2374570''>edge,</span> <span m=''2374960''>we</span>
  <span m=''2375260''>will</span> <span m=''2375560''>fail</span> <span m=''2376020''>to</span>
  <span m=''2376130''>find</span> <span m=''2376380''>enough</span> <span m=''2376590''>pebbles.</span>
  </p><p><span m=''2378310''>Let''s</span> <span m=''2378540''>see.</span> <span m=''2378930''>We</span>
  <span m=''2378970''>can</span> <span m=''2379110''>find</span> <span m=''2379380''>three</span>
  <span m=''2379580''>of</span> <span m=''2379640''>them.</span> <span m=''2380430''>We</span>
  <span m=''2380590''>can</span> <span m=''2380680''>grab</span> <span m=''2380900''>the</span>
  <span m=''2380980''>one</span> <span m=''2381120''>from</span> <span m=''2381240''>e.</span>
  <span m=''2382060''>Or</span> <span m=''2382240''>let''s</span> <span m=''2382590''>see</span>
  <span m=''2382940''>so--</span> <span m=''2384470''>it''s</span> <span m=''2384650''>not</span>
  <span m=''2384770''>going</span> <span m=''2384870''>to</span> <span m=''2384950''>show</span>
  <span m=''2385180''>us.</span> <span m=''2385860''>But</span> <span m=''2386020''>from</span>
  <span m=''2386190''>e,</span> <span m=''2386590''>we</span> <span m=''2386750''>can</span>
  <span m=''2386900''>grab</span> <span m=''2387270''>f,</span> <span m=''2387810''>the</span>
  <span m=''2388140''>pebble</span> <span m=''2388470''>at</span> <span m=''2388650''>f.</span>
  <span m=''2390410''>From</span> <span m=''2390650''>d, we</span> <span m=''2390980''>can</span>
  <span m=''2391070''>grab</span> <span m=''2391340''>the</span> <span m=''2391430''>pebble</span>
  <span m=''2391795''>at c.</span> <span m=''2392160''>From</span> <span m=''2392360''>d,</span>
  <span m=''2392700''>we can</span> <span m=''2392790''>grab</span> <span m=''2393040''>the</span>
  <span m=''2393170''>other</span> <span m=''2393340''>pebble at</span> <span m=''2393730''>f.</span>
  <span m=''2394740''>We''ve</span> <span m=''2394860''>got</span> <span m=''2395130''>three</span>
  <span m=''2395320''>pebbles,</span> <span m=''2395700''>but</span> <span m=''2395850''>there''s</span>
  <span m=''2396040''>no</span> <span m=''2396200''>way</span> <span m=''2396380''>to</span>
  <span m=''2396540''>get</span> <span m=''2396720''>to</span> <span m=''2396810''>this</span>
  <span m=''2397010''>pebble</span> <span m=''2397950''>because</span> <span m=''2398800''>both</span>
  <span m=''2399020''>of</span> <span m=''2399080''>these</span> <span m=''2399250''>edges</span>
  <span m=''2399560''>are</span> <span m=''2399650''>directed</span> <span m=''2400080''>down.</span>
  <span m=''2400800''>So</span> <span m=''2400920''>you</span> <span m=''2400990''>can</span>
  <span m=''2401090''>never</span> <span m=''2401330''>get</span> <span m=''2401510''>from</span>
  <span m=''2401640''>the</span> <span m=''2401740''>below</span> <span m=''2402030''>part</span>
  <span m=''2402350''>to</span> <span m=''2402450''>the</span> <span m=''2402600''>above</span>
  <span m=''2402850''>part.</span> </p><p><span m=''2404150''>So</span> <span m=''2404800''>it''s</span>
  <span m=''2404890''>not</span> <span m=''2405040''>obvious</span> <span m=''2405420''>that</span>
  <span m=''2405510''>this</span> <span m=''2405710''>is</span> <span m=''2405810''>working.</span>
  <span m=''2406230''>That''s</span> <span m=''2406430''>what</span> <span m=''2406550''>the</span>
  <span m=''2406640''>proof is</span> <span m=''2407020''>for.</span> <span m=''2408400''>But</span>
  <span m=''2409530''>at</span> <span m=''2409650''>least</span> <span m=''2410240''>you</span>
  <span m=''2410460''>see</span> <span m=''2410660''>it</span> <span m=''2410720''>in</span>
  <span m=''2410890''>action.</span> <span m=''2411410''>I''ll</span> <span m=''2411620''>just</span>
  <span m=''2411770''>run</span> <span m=''2411940''>it</span> <span m=''2412030''>very</span>
  <span m=''2412200''>quickly</span> <span m=''2412560''>for</span> <span m=''2412700''>another</span>
  <span m=''2412940''>graph.</span> <span m=''2414716''>Let''s</span> <span m=''2415138''>say</span>
  <span m=''2415560''>a</span> <span m=''2415670''>big</span> <span m=''2415970''>one.</span>
  <span m=''2417600''>This</span> <span m=''2417680''>one</span> <span m=''2417880''>is</span>
  <span m=''2418070''>minimally,</span> <span m=''2418450''>generically</span> <span
  m=''2418910''>rigid.</span> <span m=''2420220''>So</span> <span m=''2421120''>it''s</span>
  <span m=''2421470''>fun</span> <span m=''2421660''>to</span> <span m=''2421740''>watch</span>
  <span m=''2422040''>for</span> <span m=''2422180''>a</span> <span m=''2422250''>while.</span>
  <span m=''2423250''>You</span> <span m=''2423400''>get</span> <span m=''2425010''>pebbles</span>
  <span m=''2426620''>moving</span> <span m=''2426880''>around.</span> <span m=''2427935''>In</span>
  <span m=''2428370''>this</span> <span m=''2428560''>case,</span> <span m=''2428780''>you</span>
  <span m=''2428880''>have</span> <span m=''2429020''>some</span> <span m=''2429200''>longer</span>
  <span m=''2429530''>paths</span> <span m=''2429820''>you</span> <span m=''2429900''>have</span>
  <span m=''2430020''>to</span> <span m=''2430120''>follow</span> <span m=''2431410''>to</span>
  <span m=''2431530''>get</span> <span m=''2431680''>enough</span> <span m=''2432090''>pebbles.</span>
  <span m=''2433090''>It</span> <span m=''2433240''>depends</span> <span m=''2433610''>a</span>
  <span m=''2433670''>lot</span> <span m=''2433880''>on</span> <span m=''2433960''>the</span>
  <span m=''2434050''>insertion</span> <span m=''2434440''>order</span> <span m=''2434780''>that</span>
  <span m=''2435150''>you use.</span> </p><p><span m=''2441950''>So</span> <span m=''2443170''>in</span>
  <span m=''2443270''>each</span> <span m=''2443420''>case,</span> <span m=''2443690''>you</span>
  <span m=''2443760''>need</span> <span m=''2443920''>four</span> <span m=''2444110''>pebbles,</span>
  <span m=''2444560''>two</span> <span m=''2444730''>on</span> <span m=''2444830''>each</span>
  <span m=''2444990''>side.</span> <span m=''2446110''>And</span> <span m=''2446370''>if</span>
  <span m=''2446450''>so,</span> <span m=''2446620''>you</span> <span m=''2446780''>can</span>
  <span m=''2447010''>add</span> <span m=''2447070''>your</span> <span m=''2447130''>edge.</span>
  <span m=''2447380''>Otherwise,</span> <span m=''2447690''>you</span> <span m=''2447780''>can''t.</span>
  <span m=''2448270''>What I</span> <span m=''2448450''>haven''t</span> <span m=''2448730''>described</span>
  <span m=''2449210''>is</span> <span m=''2449330''>this</span> <span m=''2449480''>color</span>
  <span m=''2449750''>coding</span> <span m=''2450990''>which</span> <span m=''2451240''>is</span>
  <span m=''2451350''>figuring</span> <span m=''2451720''>out</span> <span m=''2451860''>when</span>
  <span m=''2452030''>you</span> <span m=''2452120''>have</span> <span m=''2452350''>rigid</span>
  <span m=''2452610''>components.</span> <span m=''2454190''>Roughly</span> <span
  m=''2454640''>speaking,</span> <span m=''2455240''>to</span> <span m=''2455340''>find</span>
  <span m=''2455770''>what</span> <span m=''2456980''>your</span> <span m=''2457290''>rigid</span>
  <span m=''2457530''>component</span> <span m=''2457860''>is--</span> <span m=''2458010''>if</span>
  <span m=''2458110''>you''re</span> <span m=''2458250''>an</span> <span m=''2458320''>edge,</span>
  <span m=''2458590''>you</span> <span m=''2458700''>want</span> <span m=''2458840''>to</span>
  <span m=''2458900''>know</span> <span m=''2459050''>what</span> <span m=''2459220''>rigid</span>
  <span m=''2459510''>component</span> <span m=''2459930''>am</span> <span m=''2460090''>I</span>
  <span m=''2460180''>in--</span> <span m=''2461110''>you</span> <span m=''2462240''>basically</span>
  <span m=''2462590''>just</span> <span m=''2462910''>search</span> <span m=''2463300''>for</span>
  <span m=''2463420''>all</span> <span m=''2463920''>the</span> <span m=''2464020''>vertices</span>
  <span m=''2464480''>that</span> <span m=''2464590''>are</span> <span m=''2464710''>reachable</span>
  <span m=''2465250''>from</span> <span m=''2465520''>your</span> <span m=''2466220''>edge.</span>
  <span m=''2467510''>Those</span> <span m=''2467650''>are</span> <span m=''2467770''>all</span>
  <span m=''2467930''>in</span> <span m=''2468010''>your</span> <span m=''2468120''>rigid</span>
  <span m=''2468390''>component.</span> </p><p><span m=''2469240''>That''s</span>
  <span m=''2469690''>what</span> <span m=''2469900''>we</span> <span m=''2470490''>saw.</span>
  <span m=''2471440''>So</span> <span m=''2471610''>this</span> <span m=''2471790''>graph</span>
  <span m=''2471990''>happens</span> <span m=''2472230''>to</span> <span m=''2472330''>be</span>
  <span m=''2472430''>minimally</span> <span m=''2472800''>rigid,</span> <span m=''2473075''>and
  it</span> <span m=''2473350''>detects</span> <span m=''2473700''>that.</span> <span
  m=''2476300''>But</span> <span m=''2476400''>then</span> <span m=''2476610''>it</span>
  <span m=''2476740''>can</span> <span m=''2476940''>be</span> <span m=''2477040''>a</span>
  <span m=''2477100''>little</span> <span m=''2477300''>bit</span> <span m=''2477440''>more</span>
  <span m=''2477660''>as</span> <span m=''2477760''>in</span> <span m=''2477840''>your
  rigid</span> <span m=''2478050''>component.</span> <span m=''2479180''>Some</span>
  <span m=''2479550''>of</span> <span m=''2479700''>the</span> <span m=''2480150''>incoming</span>
  <span m=''2480700''>edges--</span> <span m=''2482390''>let''s</span> <span m=''2482850''>see.</span>
  <span m=''2484350''>Draw a</span> <span m=''2484470''>picture.</span> <span m=''2486390''>So</span>
  <span m=''2486460''>here''s</span> <span m=''2486860''>everything</span> <span m=''2487270''>you</span>
  <span m=''2487440''>can</span> <span m=''2487620''>reach</span> <span m=''2488010''>from</span>
  <span m=''2488470''>v-w.</span> <span m=''2490410''>And</span> <span m=''2490670''>say</span>
  <span m=''2490790''>you''re</span> <span m=''2490900''>following</span> <span m=''2491470''>an</span>
  <span m=''2491590''>incoming</span> <span m=''2492010''>edge</span> <span m=''2492280''>here</span>
  <span m=''2492430''>from</span> <span m=''2492890''>some</span> <span m=''2493480''>other</span>
  <span m=''2493660''>vertex</span> <span m=''2494020''>u.</span> </p><p><span m=''2494830''>And</span>
  <span m=''2495000''>then</span> <span m=''2495110''>suppose</span> <span m=''2495530''>these</span>
  <span m=''2495780''>are</span> <span m=''2495870''>all</span> <span m=''2496000''>the</span>
  <span m=''2496080''>things</span> <span m=''2496400''>you</span> <span m=''2496540''>can</span>
  <span m=''2496690''>reach</span> <span m=''2496940''>from</span> <span m=''2497140''>you.</span>
  <span m=''2498540''>If</span> <span m=''2498700''>there</span> <span m=''2498980''>are</span>
  <span m=''2499090''>zero</span> <span m=''2499530''>pebbles</span> <span m=''2499930''>out</span>
  <span m=''2500090''>here,</span> <span m=''2501110''>then</span> <span m=''2501400''>this</span>
  <span m=''2501590''>whole</span> <span m=''2501890''>thing</span> <span m=''2502160''>is</span>
  <span m=''2502290''>a</span> <span m=''2502370''>rigid</span> <span m=''2502610''>component.</span>
  <span m=''2503860''>And</span> <span m=''2504000''>you</span> <span m=''2504060''>just</span>
  <span m=''2504220''>keep</span> <span m=''2504400''>doing</span> <span m=''2504650''>that.</span>
  <span m=''2504830''>You</span> <span m=''2504920''>check</span> <span m=''2505220''>an</span>
  <span m=''2505320''>incoming</span> <span m=''2505730''>edge.</span> <span m=''2506360''>If</span>
  <span m=''2506510''>there''s</span> <span m=''2506690''>zero</span> <span m=''2507010''>pebbles</span>
  <span m=''2507590''>in</span> <span m=''2507770''>that</span> <span m=''2507980''>reachable</span>
  <span m=''2508670''>piece,</span> <span m=''2509090''>then</span> <span m=''2509260''>you</span>
  <span m=''2509370''>merge.</span> <span m=''2510150''>And</span> <span m=''2510220''>you</span>
  <span m=''2510300''>keep</span> <span m=''2510500''>doing</span> <span m=''2510740''>that.</span>
  <span m=''2511000''>Those</span> <span m=''2511270''>are</span> <span m=''2511420''>all</span>
  <span m=''2511560''>the</span> <span m=''2511660''>things</span> <span m=''2511920''>that</span>
  <span m=''2512010''>are</span> <span m=''2512100''>rigidly</span> <span m=''2512530''>attached</span>
  <span m=''2512980''>to you.</span> </p><p><span m=''2513740''>So</span> <span m=''2513930''>I
  won''t</span> <span m=''2514030''>prove</span> <span m=''2514250''>that.</span>
  <span m=''2514510''>It''s</span> <span m=''2514680''>a</span> <span m=''2514720''>little</span>
  <span m=''2514870''>tricky</span> <span m=''2515130''>to</span> <span m=''2515200''>prove,</span>
  <span m=''2516040''>but</span> <span m=''2516170''>it''s</span> <span m=''2516380''>fairly</span>
  <span m=''2516630''>easy</span> <span m=''2516820''>to</span> <span m=''2516900''>compute.</span>
  <span m=''2517400''>And</span> <span m=''2517600''>you</span> <span m=''2517690''>could</span>
  <span m=''2517800''>actually</span> <span m=''2518040''>do</span> <span m=''2518210''>it
  in</span> <span m=''2518340''>the</span> <span m=''2518400''>same</span> <span m=''2518610''>amount</span>
  <span m=''2518830''>of</span> <span m=''2518910''>time.</span> <span m=''2519200''>As</span>
  <span m=''2519420''>you''re</span> <span m=''2519540''>building</span> <span m=''2519870''>this</span>
  <span m=''2520030''>thing</span> <span m=''2520220''>up,</span> <span m=''2520790''>you</span>
  <span m=''2520920''>can</span> <span m=''2521010''>do</span> <span m=''2521100''>the</span>
  <span m=''2521230''>color</span> <span m=''2521510''>coding to</span> <span m=''2521870''>figure</span>
  <span m=''2522170''>out</span> <span m=''2522780''>which</span> <span m=''2523020''>things</span>
  <span m=''2523270''>are</span> <span m=''2523630''>in</span> <span m=''2523770''>the</span>
  <span m=''2523830''>same</span> <span m=''2524060''>component,</span> <span m=''2524460''>which</span>
  <span m=''2524660''>things</span> <span m=''2524860''>are</span> <span m=''2524920''>in</span>
  <span m=''2524990''>different</span> <span m=''2525270''>components.</span> <span
  m=''2527880''>Let''s</span> <span m=''2528060''>see.</span> <span m=''2529820''>So</span>
  <span m=''2530540''>another</span> <span m=''2530770''>fun</span> <span m=''2531010''>fact</span>
  <span m=''2532170''>is</span> <span m=''2534180''>this</span> <span m=''2534840''>little</span>
  <span m=''2535230''>part.</span> </p><p><span m=''2537110''>This</span> <span m=''2537360''>says</span>
  <span m=''2537600''>it''s</span> <span m=''2537790''>the</span> <span m=''2538010''>2k</span>
  <span m=''2538850''>minus</span> <span m=''2539360''>3</span> <span m=''2539670''>property.</span>
  <span m=''2540870''>The</span> <span m=''2540970''>same</span> <span m=''2541260''>algorithm</span>
  <span m=''2541640''>you</span> <span m=''2541790''>could</span> <span m=''2541930''>use</span>
  <span m=''2542200''>to</span> <span m=''2542300''>check</span> <span m=''2543110''>5k</span>
  <span m=''2543950''>minus</span> <span m=''2544390''>27,</span> <span m=''2545130''>or</span>
  <span m=''2545680''>whatever</span> <span m=''2546010''>you</span> <span m=''2546130''>want,</span>
  <span m=''2546770''>for</span> <span m=''2546970''>fixed</span> <span m=''2547630''>numbers</span>
  <span m=''2548410''>like</span> <span m=''2548610''>two</span> <span m=''2548790''>and</span>
  <span m=''2548920''>three,</span> <span m=''2549960''>the</span> <span m=''2550170''>same</span>
  <span m=''2550470''>pebble</span> <span m=''2550920''>algorithm</span> <span m=''2553140''>can</span>
  <span m=''2553320''>detect</span> <span m=''2553960''>that</span> <span m=''2555170''>ak</span>
  <span m=''2555590''>minus</span> <span m=''2555990''>b</span> <span m=''2556510''>property.</span>
  <span m=''2557430''>And</span> <span m=''2557570''>that''s</span> <span m=''2557760''>actually</span>
  <span m=''2558000''>useful</span> <span m=''2558310''>for</span> <span m=''2558460''>a</span>
  <span m=''2558510''>lot</span> <span m=''2558690''>of</span> <span m=''2558770''>different</span>
  <span m=''2559050''>things.</span> <span m=''2559630''>This</span> <span m=''2559750''>is</span>
  <span m=''2559880''>done</span> <span m=''2560090''>originally</span> <span m=''2560430''>by</span>
  <span m=''2561350''>Lee</span> <span m=''2561700''>and</span> <span m=''2561920''>Streinu.</span>
  <span m=''2562550''>Same lee,</span> <span m=''2565040''>and</span> <span m=''2565320''>Streinu</span>
  <span m=''2565690''>we''ll</span> <span m=''2566620''>be</span> <span m=''2566750''>seeing</span>
  <span m=''2567000''>some</span> <span m=''2567160''>of</span> <span m=''2567240''>her</span>
  <span m=''2567470''>results</span> <span m=''2567860''>in</span> <span m=''2567970''>a</span>
  <span m=''2568020''>couple</span> <span m=''2568310''>of</span> <span m=''2568410''>classes</span>
  <span m=''2568840''>as</span> <span m=''2568940''>well.</span> </p><p><span m=''2571460''>For</span>
  <span m=''2571780''>example--</span> <span m=''2574860''>so</span> <span m=''2575040''>this</span>
  <span m=''2575250''>is</span> <span m=''2575530''>that--</span> <span m=''2577650''>3D</span>
  <span m=''2578300''>body</span> <span m=''2578790''>and</span> <span m=''2579020''>bar.</span>
  <span m=''2579970''>So</span> <span m=''2580150''>actually</span> <span m=''2580420''>let</span>
  <span m=''2580540''>me</span> <span m=''2580640''>show</span> <span m=''2580860''>you</span>
  <span m=''2582070''>the</span> <span m=''2582210''>kind</span> <span m=''2582410''>of</span>
  <span m=''2582490''>scenario</span> <span m=''2582980''>we''re</span> <span m=''2583070''>thinking</span>
  <span m=''2583340''>about.</span> <span m=''2584610''>So</span> <span m=''2584730''>I</span>
  <span m=''2584770''>mentioned</span> <span m=''2585210''>3D.</span> <span m=''2586140''>If</span>
  <span m=''2586450''>we</span> <span m=''2586570''>have</span> <span m=''2587660''>vertices</span>
  <span m=''2588700''>and</span> <span m=''2589960''>bars</span> <span m=''2590420''>between</span>
  <span m=''2590760''>them,</span> <span m=''2591050''>we</span> <span m=''2591270''>don''t</span>
  <span m=''2591430''>know</span> <span m=''2591590''>how</span> <span m=''2591730''>to</span>
  <span m=''2591820''>characterize</span> <span m=''2592480''>generic</span> <span
  m=''2592860''>rigidity.</span> <span m=''2593950''>But</span> <span m=''2594080''>a</span>
  <span m=''2594160''>slightly</span> <span m=''2594680''>different</span> <span m=''2594970''>problem,</span>
  <span m=''2595440''>which</span> <span m=''2595510''>is</span> <span m=''2595660''>3D</span>
  <span m=''2596080''>bodies,</span> <span m=''2596710''>these</span> <span m=''2596890''>are</span>
  <span m=''2596990''>polyhedron.</span> <span m=''2598880''>And</span> <span m=''2599430''>they</span>
  <span m=''2599580''>have</span> <span m=''2599830''>bars</span> <span m=''2600360''>connected</span>
  <span m=''2600870''>between</span> <span m=''2601280''>them.</span> <span m=''2602380''>This</span>
  <span m=''2602710''>we</span> <span m=''2602830''>know</span> <span m=''2602960''>how</span>
  <span m=''2603060''>to</span> <span m=''2603140''>solve</span> <span m=''2603560''>in</span>
  <span m=''2603730''>3D</span> <span m=''2604450''>and</span> <span m=''2604670''>in</span>
  <span m=''2605020''>any</span> <span m=''2605240''>dimension.</span> </p><p><span
  m=''2607600''>And</span> <span m=''2608420''>so</span> <span m=''2608610''>this</span>
  <span m=''2608810''>is</span> <span m=''2609000''>a</span> <span m=''2609650''>picture</span>
  <span m=''2610630''>of</span> <span m=''2610920''>not</span> <span m=''2611200''>only</span>
  <span m=''2611440''>having--</span> <span m=''2612600''>so</span> <span m=''2612780''>their</span>
  <span m=''2612960''>bodies</span> <span m=''2613920''>can</span> <span m=''2614100''>spin</span>
  <span m=''2614650''>unlike</span> <span m=''2615010''>vertices.</span> <span m=''2615430''>Vertices</span>
  <span m=''2615830''>can''t</span> <span m=''2616030''>rotate.</span> <span m=''2616410''>Nothing</span>
  <span m=''2616670''>happens</span> <span m=''2617050''>when</span> <span m=''2617150''>you</span>
  <span m=''2617240''>rotate</span> <span m=''2617530''>a</span> <span m=''2617590''>vertex.</span>
  <span m=''2618460''>Bodies</span> <span m=''2618780''>have</span> <span m=''2618910''>this</span>
  <span m=''2619040''>extra</span> <span m=''2619300''>degree</span> <span m=''2619530''>of</span>
  <span m=''2619620''>freedom.</span> <span m=''2624000''>So</span> <span m=''2624240''>there</span>
  <span m=''2624360''>are</span> <span m=''2624410''>two</span> <span m=''2624600''>things</span>
  <span m=''2624820''>we''re</span> <span m=''2624960''>allowing</span> <span m=''2625270''>here,</span>
  <span m=''2625400''>one</span> <span m=''2625580''>is</span> <span m=''2625690''>to</span>
  <span m=''2625810''>add</span> <span m=''2625980''>a</span> <span m=''2626020''>hinge</span>
  <span m=''2626620''>between</span> <span m=''2627000''>two</span> <span m=''2627130''>bodies</span>
  <span m=''2628010''>and</span> <span m=''2628210''>the</span> <span m=''2628320''>other
  is</span> <span m=''2628580''>to</span> <span m=''2628690''>add</span> <span m=''2628900''>bars</span>
  <span m=''2629450''>connecting</span> <span m=''2629830''>them</span> <span m=''2630000''>from</span>
  <span m=''2630200''>various</span> <span m=''2630580''>random</span> <span m=''2630940''>points.</span>
  <span m=''2631410''>And</span> <span m=''2631550''>it''s</span> <span m=''2631680''>generic,</span>
  <span m=''2632290''>so</span> <span m=''2632410''>these</span> <span m=''2632640''>points</span>
  <span m=''2632920''>will</span> <span m=''2633020''>never</span> <span m=''2633280''>coincide.</span>
  </p><p><span m=''2634050''>I</span> <span m=''2634180''>think</span> <span m=''2634340''>that''s</span>
  <span m=''2634540''>what</span> <span m=''2634840''>makes</span> <span m=''2635110''>this</span>
  <span m=''2635270''>different</span> <span m=''2635530''>from</span> <span m=''2635740''>a</span>
  <span m=''2636130''>vertex.</span> <span m=''2636600''>Vertex bars</span> <span
  m=''2636860''>always</span> <span m=''2637120''>coincide.</span> <span m=''2638250''>Here,</span>
  <span m=''2638500''>they</span> <span m=''2638680''>all</span> <span m=''2638870''>just</span>
  <span m=''2639040''>attach</span> <span m=''2639470''>to</span> <span m=''2639550''>generic</span>
  <span m=''2639930''>points.</span> <span m=''2641090''>So</span> <span m=''2641180''>it</span>
  <span m=''2641240''>turns</span> <span m=''2641460''>out</span> <span m=''2641570''>you</span>
  <span m=''2641680''>can</span> <span m=''2641810''>simulate</span> <span m=''2642980''>a</span>
  <span m=''2643230''>hinge</span> <span m=''2643760''>by</span> <span m=''2644180''>five</span>
  <span m=''2644830''>bars.</span> <span m=''2645470''>They''re</span> <span m=''2645500''>equivalent.</span>
  <span m=''2647680''>So</span> <span m=''2648390''>both</span> <span m=''2648610''>of</span>
  <span m=''2648680''>these</span> <span m=''2648870''>can</span> <span m=''2649020''>be</span>
  <span m=''2649130''>captured</span> <span m=''2649700''>by</span> <span m=''2650440''>6K</span>
  <span m=''2651150''>minus</span> <span m=''2651570''>6</span> <span m=''2652440''>property.</span>
  <span m=''2653390''>Turns</span> <span m=''2653660''>out</span> <span m=''2653800''>these</span>
  <span m=''2653980''>things</span> <span m=''2654180''>will</span> <span m=''2654260''>be</span>
  <span m=''2654370''>generically</span> <span m=''2654850''>rigid</span> <span m=''2655170''>if</span>
  <span m=''2655360''>and</span> <span m=''2655440''>only</span> <span m=''2655710''>if</span>
  <span m=''2655940''>you</span> <span m=''2656090''>satisfy</span> <span m=''2656540''>the</span>
  <span m=''2656640''>6K</span> <span m=''2657030''>minus</span> <span m=''2657290''>6</span>
  <span m=''2657470''>property</span> <span m=''2657850''>and</span> <span m=''2658010''>you</span>
  <span m=''2658100''>have</span> <span m=''2658270''>exactly</span> <span m=''2658700''>6K</span>
  <span m=''2659090''>minus</span> <span m=''2659420''>6</span> <span m=''2660450''>bars.</span>
  </p><p><span m=''2661930''>And</span> <span m=''2662270''>this is</span> <span m=''2662530''>proved</span>
  <span m=''2662940''>by</span> <span m=''2664290''>two</span> <span m=''2664645''>or</span>
  <span m=''2665000''>three</span> <span m=''2665370''>people.</span> <span m=''2667150''>I</span>
  <span m=''2667200''>mean</span> <span m=''2667340''>you</span> <span m=''2667470''>need</span>
  <span m=''2667640''>to</span> <span m=''2668000''>add</span> <span m=''2668280''>two</span>
  <span m=''2668430''>results</span> <span m=''2668820''>together,</span> <span m=''2670020''>one</span>
  <span m=''2670280''>from</span> <span m=''2670590''>the</span> <span m=''2671490''>''90s</span>
  <span m=''2672000''>and</span> <span m=''2672130''>one</span> <span m=''2672330''>from</span>
  <span m=''2672560''>much</span> <span m=''2672780''>older,</span> <span m=''2673130''>I</span>
  <span m=''2673190''>think,</span> <span m=''2673600''>in</span> <span m=''2674060''>graph</span>
  <span m=''2674370''>theory.</span> <span m=''2674900''>But</span> <span m=''2675430''>in</span>
  <span m=''2675540''>particular,</span> <span m=''2676710''>Tae</span> <span m=''2677070''>was</span>
  <span m=''2677250''>involved</span> <span m=''2678840''>from</span> <span m=''2679030''>1984.</span>
  <span m=''2681260''>And</span> <span m=''2681480''>it''s</span> <span m=''2681840''>funny.</span>
  <span m=''2682060''>The</span> <span m=''2682150''>paper</span> <span m=''2682410''>starts</span>
  <span m=''2682690''>out</span> <span m=''2682800''>with,</span> <span m=''2683040''>if</span>
  <span m=''2683250''>you</span> <span m=''2683360''>ask</span> <span m=''2683570''>any</span>
  <span m=''2683710''>structural</span> <span m=''2684120''>engineer</span> <span
  m=''2684460''>if</span> <span m=''2684510''>you</span> <span m=''2684590''>have</span>
  <span m=''2684700''>two</span> <span m=''2684860''>bodies</span> <span m=''2685190''>how</span>
  <span m=''2685320''>many</span> <span m=''2685480''>bars</span> <span m=''2685790''>you</span>
  <span m=''2685910''>have</span> <span m=''2686050''>to</span> <span m=''2686170''>add</span>
  <span m=''2686520''>to</span> <span m=''2687020''>rigidify</span> <span m=''2687460''>them,</span>
  <span m=''2687660''>they</span> <span m=''2687790''>will</span> <span m=''2687930''>say</span>
  <span m=''2688160''>six.</span> <span m=''2688720''>I''m like,</span> <span m=''2688970''>OK,</span>
  <span m=''2689220''>I</span> <span m=''2689250''>didn''t</span> <span m=''2689600''>know</span>
  <span m=''2689790''>that.</span> <span m=''2690090''>But</span> <span m=''2690680''>six</span>
  <span m=''2690970''>is</span> <span m=''2691090''>the</span> <span m=''2691190''>right</span>
  <span m=''2691360''>answer.</span> <span m=''2692130''>And</span> <span m=''2692500''>that''s</span>
  <span m=''2692710''>why</span> <span m=''2692970''>the</span> <span m=''2693070''>6K</span>
  <span m=''2693450''>minus</span> <span m=''2693800''>6</span> <span m=''2694760''>basically.</span>
  <span m=''2696340''>And</span> <span m=''2696730''>and</span> <span m=''2697100''>we</span>
  <span m=''2697310''>can</span> <span m=''2697410''>use</span> <span m=''2697590''>this</span>
  <span m=''2697690''>pebble</span> <span m=''2697950''>algorithm</span> <span m=''2698340''>to</span>
  <span m=''2698430''>solve</span> <span m=''2698680''>that</span> <span m=''2699930''>for</span>
  <span m=''2700070''>free</span> <span m=''2700550''>basically.</span> </p><p><span
  m=''2701240''>And</span> <span m=''2701490''>this</span> <span m=''2701660''>is</span>
  <span m=''2701770''>actually</span> <span m=''2702070''>implemented</span> <span
  m=''2703970''>here</span> <span m=''2704380''>in</span> <span m=''2704470''>the</span>
  <span m=''2704540''>same</span> <span m=''2704870''>kind</span> <span m=''2705040''>of</span>
  <span m=''2705100''>software.</span> <span m=''2705660''>I''ll</span> <span m=''2706110''>just</span>
  <span m=''2706310''>run</span> <span m=''2706480''>it</span> <span m=''2707210''>quickly</span>
  <span m=''2707690''>because</span> <span m=''2708615''>it''s</span> <span m=''2708880''>a
  lot of</span> <span m=''2708960''>pebbles.</span> <span m=''2709910''>Every</span>
  <span m=''2710270''>vertex</span> <span m=''2710750''>has</span> <span m=''2711020''>six</span>
  <span m=''2711270''>pebbles.</span> <span m=''2712910''>You</span> <span m=''2713100''>just</span>
  <span m=''2713410''>keep</span> <span m=''2713610''>going.</span> <span m=''2715370''>You</span>
  <span m=''2715910''>need</span> <span m=''2716080''>to</span> <span m=''2716160''>cover</span>
  <span m=''2716510''>every</span> <span m=''2716810''>edge</span> <span m=''2718010''>with</span>
  <span m=''2720000''>how</span> <span m=''2720560''>many</span> <span m=''2720810''>pebbles?</span>
  <span m=''2722930''>Before it</span> <span m=''2723070''>was</span> <span m=''2723240''>four,</span>
  <span m=''2723660''>so</span> <span m=''2723780''>now</span> <span m=''2723900''>it</span>
  <span m=''2723940''>should</span> <span m=''2724160''>be</span> <span m=''2724340''>7,</span>
  <span m=''2725440''>I</span> <span m=''2725550''>believe,</span> <span m=''2726640''>one</span>
  <span m=''2726880''>more</span> <span m=''2727200''>than</span> <span m=''2728640''>the</span>
  <span m=''2728740''>six</span> <span m=''2729160''>here.</span> <span m=''2729460''>So</span>
  <span m=''2729570''>6k</span> <span m=''2729810''>minus</span> <span m=''2730130''>6.</span>
  </p><p><span m=''2732060''>Anyway,</span> <span m=''2732390''>this</span> <span
  m=''2733450''>graph,</span> <span m=''2734340''>while</span> <span m=''2734620''>it''s
  not</span> <span m=''2734790''>obvious,</span> <span m=''2735570''>is</span> <span
  m=''2735780''>minimally</span> <span m=''2736180''>rigid</span> <span m=''2736870''>in</span>
  <span m=''2737040''>this</span> <span m=''2737190''>world.</span> <span m=''2737850''>And</span>
  <span m=''2738020''>it</span> <span m=''2738130''>corresponds</span> <span m=''2738770''>exactly</span>
  <span m=''2739350''>to</span> <span m=''2740660''>the</span> <span m=''2740920''>left</span>
  <span m=''2741300''>example.</span> <span m=''2742570''>It''s</span> <span m=''2742650''>hard</span>
  <span m=''2742850''>to</span> <span m=''2742930''>see</span> <span m=''2743150''>because</span>
  <span m=''2743880''>we''ve</span> <span m=''2744190''>replaced</span> <span m=''2744650''>the</span>
  <span m=''2744750''>hinges</span> <span m=''2745120''>here</span> <span m=''2745425''>by</span>
  <span m=''2746260''>six</span> <span m=''2746820''>bars.</span> <span m=''2747590''>So</span>
  <span m=''2747870''>that''s</span> <span m=''2748030''>why</span> <span m=''2748160''>we</span>
  <span m=''2748270''>got</span> <span m=''2748420''>all</span> <span m=''2748560''>the</span>
  <span m=''2748890''>six--</span> <span m=''2749440''>all</span> <span m=''2749740''>the</span>
  <span m=''2750010''>duplicated</span> <span m=''2750540''>edges.</span> <span m=''2751290''>Here,</span>
  <span m=''2751500''>you</span> <span m=''2751610''>see</span> <span m=''2751870''>the</span>
  <span m=''2751990''>duplicated</span> <span m=''2752780''>are</span> <span m=''2752870''>different</span>
  <span m=''2753300''>from a</span> <span m=''2753410''>rigidity</span> <span m=''2753870''>standpoint</span>
  <span m=''2754125''>because</span> <span m=''2754610''>having</span> <span m=''2754890''>three</span>
  <span m=''2755160''>edges</span> <span m=''2755450''>between</span> <span m=''2755830''>the</span>
  <span m=''2755920''>same</span> <span m=''2756270''>pair</span> <span m=''2756490''>of</span>
  <span m=''2756550''>objects</span> <span m=''2757550''>is</span> <span m=''2757710''>no</span>
  <span m=''2757840''>longer</span> <span m=''2758240''>just</span> <span m=''2758460''>the</span>
  <span m=''2758520''>same</span> <span m=''2758740''>as</span> <span m=''2758840''>having</span>
  <span m=''2759080''>one</span> <span m=''2759270''>edge</span> <span m=''2759970''>because</span>
  <span m=''2760370''>they</span> <span m=''2760490''>attach</span> <span m=''2760900''>to</span>
  <span m=''2760990''>different</span> <span m=''2761300''>points.</span> <span m=''2762310''>Each</span>
  <span m=''2762400''>one</span> <span m=''2762640''>can</span> <span m=''2762790''>spin.</span>
  </p><p><span m=''2763070''>These</span> <span m=''2763270''>are</span> <span m=''2763470''>universal</span>
  <span m=''2763970''>joints</span> <span m=''2764280''>by</span> <span m=''2764410''>the</span>
  <span m=''2764520''>way.</span> <span m=''2765170''>So</span> <span m=''2766520''>these</span>
  <span m=''2766710''>bars</span> <span m=''2767030''>can</span> <span m=''2767170''>rotate</span>
  <span m=''2767600''>around</span> <span m=''2768110''>the</span> <span m=''2768190''>body.</span>
  <span m=''2768510''>The</span> <span m=''2768590''>body</span> <span m=''2768900''>can</span>
  <span m=''2769050''>spin.</span> <span m=''2769540''>Lots</span> <span m=''2769770''>of</span>
  <span m=''2769850''>things</span> <span m=''2770070''>can</span> <span m=''2770190''>happen.</span>
  <span m=''2770940''>But</span> <span m=''2771130''>this</span> <span m=''2771310''>is</span>
  <span m=''2771430''>enough</span> <span m=''2771540''>to</span> <span m=''2771920''>rigidify.</span>
  <span m=''2772760''>Is</span> <span m=''2773180''>there a</span> <span m=''2773340''>question?</span>
  <span m=''2775940''>Cool.</span> <span m=''2776480''>I''m</span> <span m=''2776600''>not</span>
  <span m=''2776730''>going</span> <span m=''2776830''>to</span> <span m=''2776890''>prove</span>
  <span m=''2777110''>that.</span> <span m=''2777360''>You</span> <span m=''2777540''>can</span>
  <span m=''2777860''>read</span> <span m=''2778020''>the</span> <span m=''2778110''>papers</span>
  <span m=''2778500''>if</span> <span m=''2778680''>you''re</span> <span m=''2778850''>interested.</span>
  <span m=''2780770''>But</span> <span m=''2780820''>it''s</span> <span m=''2781000''>interesting.</span>
  <span m=''2781510''>Bodies</span> <span m=''2782070''>and</span> <span m=''2782190''>bars</span>
  <span m=''2782520''>are</span> <span m=''2782600''>so</span> <span m=''2782750''>much</span>
  <span m=''2782960''>easier</span> <span m=''2783380''>than</span> <span m=''2784850''>other</span>
  <span m=''2785040''>things.</span> </p><p><span m=''2786470''>One</span> <span m=''2786720''>other</span>
  <span m=''2786920''>thing</span> <span m=''2787100''>you</span> <span m=''2787200''>can</span>
  <span m=''2787320''>do</span> <span m=''2787460''>is</span> <span m=''2787560''>called</span>
  <span m=''2787840''>angular</span> <span m=''2788260''>rigidity.</span> <span m=''2789680''>This</span>
  <span m=''2789880''>is</span> <span m=''2790020''>a</span> <span m=''2790070''>fairly</span>
  <span m=''2790370''>new</span> <span m=''2790510''>result</span> <span m=''2791020''>by</span>
  <span m=''2791240''>same</span> <span m=''2791490''>people.</span> <span m=''2793920''>If</span>
  <span m=''2794080''>you</span> <span m=''2794160''>have</span> <span m=''2794300''>a</span>
  <span m=''2794360''>bunch</span> <span m=''2794590''>of</span> <span m=''2794720''>lines</span>
  <span m=''2795160''>in</span> <span m=''2795310''>3D,</span> <span m=''2796000''>and</span>
  <span m=''2796270''>you</span> <span m=''2796350''>have</span> <span m=''2796570''>angular</span>
  <span m=''2797020''>constraints.</span> <span m=''2797550''>In</span> <span m=''2797620''>this</span>
  <span m=''2797800''>case,</span> <span m=''2798620''>every</span> <span m=''2798960''>triple</span>
  <span m=''2799430''>of</span> <span m=''2799520''>these</span> <span m=''2799710''>lines</span>
  <span m=''2800060''>has</span> <span m=''2800230''>an</span> <span m=''2800320''>angular</span>
  <span m=''2800640''>constraint</span> <span m=''2800905''>that</span> <span m=''2801170''>it</span>
  <span m=''2801250''>must</span> <span m=''2801490''>be</span> <span m=''2801680''>equal</span>
  <span m=''2801980''>to</span> <span m=''2802120''>alpha.</span> <span m=''2802720''>That''s</span>
  <span m=''2802950''>what''s</span> <span m=''2803020''>drawn</span> <span m=''2803370''>on</span>
  <span m=''2803470''>this</span> <span m=''2803550''>spherical</span> <span m=''2803980''>picture.</span>
  <span m=''2804820''>Over</span> <span m=''2805030''>here,</span> <span m=''2805500''>we</span>
  <span m=''2805650''>have</span> <span m=''2805870''>two</span> <span m=''2806080''>bodies.</span>
  </p><p><span m=''2806660''>So</span> <span m=''2806960''>here</span> <span m=''2807120''>we</span>
  <span m=''2807210''>have</span> <span m=''2807360''>lines.</span> <span m=''2807810''>Here,</span>
  <span m=''2807940''>we</span> <span m=''2808020''>have</span> <span m=''2808190''>bodies.</span>
  <span m=''2809310''>And</span> <span m=''2810160''>there</span> <span m=''2810680''>are</span>
  <span m=''2810870''>three</span> <span m=''2811850''>constraints</span> <span m=''2812530''>that</span>
  <span m=''2812890''>fix</span> <span m=''2813230''>the</span> <span m=''2813560''>angles</span>
  <span m=''2813970''>between</span> <span m=''2815290''>how</span> <span m=''2815520''>the</span>
  <span m=''2815630''>angles</span> <span m=''2816050''>meet</span> <span m=''2816300''>at</span>
  <span m=''2816410''>these</span> <span m=''2816590''>bodies.</span> <span m=''2817600''>And</span>
  <span m=''2817750''>they</span> <span m=''2817830''>claim</span> <span m=''2818210''>is</span>
  <span m=''2818390''>that</span> <span m=''2818550''>both</span> <span m=''2818770''>of</span>
  <span m=''2818860''>these</span> <span m=''2819130''>are</span> <span m=''2819670''>angularly</span>
  <span m=''2820440''>rigid,</span> <span m=''2820960''>meaning</span> <span m=''2822060''>things</span>
  <span m=''2822310''>can</span> <span m=''2822480''>still</span> <span m=''2823060''>slide</span>
  <span m=''2823390''>up</span> <span m=''2823510''>and</span> <span m=''2823650''>down,</span>
  <span m=''2823950''>but</span> <span m=''2824120''>the</span> <span m=''2824210''>angles</span>
  <span m=''2824610''>are</span> <span m=''2824710''>all</span> <span m=''2824810''>fixed.</span>
  <span m=''2826560''>And</span> <span m=''2827000''>you</span> <span m=''2827160''>can</span>
  <span m=''2827380''>test</span> <span m=''2827760''>this</span> <span m=''2828570''>again.</span>
  </p><p><span m=''2830040''>This</span> <span m=''2830240''>case</span> <span m=''2830470''>actually</span>
  <span m=''2830750''>turns</span> <span m=''2831040''>out</span> <span m=''2831400''>it''s</span>
  <span m=''2831780''>the</span> <span m=''2832120''>2k</span> <span m=''2832510''>minus</span>
  <span m=''2832830''>3</span> <span m=''2833010''>property</span> <span m=''2833490''>again,</span>
  <span m=''2834040''>same as</span> <span m=''2834340''>Laman.</span> <span m=''2835370''>This</span>
  <span m=''2835570''>one,</span> <span m=''2836525''>I''ve</span> <span m=''2836860''>forgotten.</span>
  <span m=''2837390''>I have to</span> <span m=''2837670''>check.</span> <span m=''2837970''>I</span>
  <span m=''2838030''>think it''s</span> <span m=''2838230''>3k</span> <span m=''2838640''>minus</span>
  <span m=''2838980''>3.</span> <span m=''2841440''>Yeah,</span> <span m=''2841650''>3k</span>
  <span m=''2841950''>minus</span> <span m=''2842240''>3.</span> <span m=''2843350''>So</span>
  <span m=''2844160''>cool</span> <span m=''2844380''>things.</span> <span m=''2845440''>One</span>
  <span m=''2845640''>last</span> <span m=''2845980''>question.</span> <span m=''2847580''>Connected</span>
  <span m=''2848190''>banana.</span> <span m=''2848730''>So</span> <span m=''2851370''>there''s</span>
  <span m=''2851590''>this</span> <span m=''2851760''>three</span> <span m=''2851960''>banana</span>
  <span m=''2852280''>example--</span> <span m=''2852800''>or</span> <span m=''2852910''>two</span>
  <span m=''2853060''>banana</span> <span m=''2853360''>example.</span> <span m=''2853840''>I''m
  getting</span> <span m=''2854050''>ahead</span> <span m=''2854180''>of</span> <span
  m=''2854240''>myself--</span> <span m=''2855630''>which</span> <span m=''2856140''>was</span>
  <span m=''2856880''>weird.</span> <span m=''2857160''>You</span> <span m=''2857220''>have</span>
  <span m=''2857390''>this</span> <span m=''2857510''>one</span> <span m=''2857670''>banana</span>
  <span m=''2857920''>on</span> <span m=''2857980''>the</span> <span m=''2858090''>left,</span>
  <span m=''2858410''>one</span> <span m=''2858600''>banana</span> <span m=''2858850''>on</span>
  <span m=''2858950''>the</span> <span m=''2859030''>right.</span> </p><p><span m=''2859590''>And</span>
  <span m=''2859810''>there''s</span> <span m=''2860030''>this</span> <span m=''2860370''>implicit,</span>
  <span m=''2861360''>implied</span> <span m=''2861850''>hinge,</span> <span m=''2862170''>as</span>
  <span m=''2862490''>they</span> <span m=''2862600''>call</span> <span m=''2862850''>it,</span>
  <span m=''2863290''>between</span> <span m=''2863720''>the</span> <span m=''2863860''>two</span>
  <span m=''2864170''>points.</span> <span m=''2864520''>The</span> <span m=''2864590''>whole</span>
  <span m=''2864780''>thing</span> <span m=''2864940''>is</span> <span m=''2865030''>flexible,</span>
  <span m=''2865690''>but</span> <span m=''2865820''>if</span> <span m=''2865910''>you</span>
  <span m=''2866010''>check</span> <span m=''2866280''>it,</span> <span m=''2866370''>it</span>
  <span m=''2866480''>satisfies</span> <span m=''2866835''>the</span> <span m=''2867190''>Lama</span>
  <span m=''2867430''>condition.</span> <span m=''2867860''>It</span> <span m=''2868060''>satisfies</span>
  <span m=''2869500''>3k</span> <span m=''2869870''>minus</span> <span m=''2870240''>6,</span>
  <span m=''2870590''>which</span> <span m=''2870800''>is</span> <span m=''2870930''>what</span>
  <span m=''2871710''>it</span> <span m=''2871790''>should</span> <span m=''2872060''>be</span>
  <span m=''2872520''>for</span> <span m=''2872950''>3D</span> <span m=''2873330''>rigidity.</span>
  <span m=''2873840''>This</span> <span m=''2874040''>is</span> <span m=''2874130''>a</span>
  <span m=''2874230''>3D.</span> <span m=''2875830''>Now,</span> <span m=''2875990''>this</span>
  <span m=''2876210''>graph</span> <span m=''2876500''>is--</span> <span m=''2877430''>seems</span>
  <span m=''2877750''>trivial--</span> <span m=''2878210''>I</span> <span m=''2878250''>mean</span>
  <span m=''2878400''>it</span> <span m=''2878490''>seems</span> <span m=''2878740''>easy</span>
  <span m=''2879030''>to</span> <span m=''2879100''>figure</span> <span m=''2879460''>out</span>
  <span m=''2879660''>that</span> <span m=''2879780''>this</span> <span m=''2879970''>is</span>
  <span m=''2880070''>flexible</span> <span m=''2880530''>because</span> <span m=''2881250''>there''s</span>
  <span m=''2881440''>a</span> <span m=''2881550''>two</span> <span m=''2881760''>cut.</span>
  <span m=''2882010''>There are</span> <span m=''2882220''>two</span> <span m=''2882420''>vertices</span>
  <span m=''2882840''>you can remove</span> <span m=''2884040''>that</span> <span
  m=''2884260''>disconnect</span> <span m=''2884810''>the</span> <span m=''2884880''>graph</span>
  <span m=''2885180''>into</span> <span m=''2885370''>two</span> <span m=''2885540''>pieces.</span>
  </p><p><span m=''2886430''>So</span> <span m=''2886720''>if</span> <span m=''2886830''>you</span>
  <span m=''2886940''>could</span> <span m=''2887090''>just</span> <span m=''2887750''>subdivide,</span>
  <span m=''2888530''>do</span> <span m=''2888630''>the</span> <span m=''2888720''>left</span>
  <span m=''2888940''>part</span> <span m=''2889150''>separately</span> <span m=''2889580''>from</span>
  <span m=''2889700''>the</span> <span m=''2889790''>right</span> <span m=''2890010''>part,</span>
  <span m=''2891600''>you</span> <span m=''2891760''>should</span> <span m=''2892000''>be</span>
  <span m=''2892100''>able</span> <span m=''2892250''>to</span> <span m=''2892320''>figure</span>
  <span m=''2892550''>this</span> <span m=''2892740''>out.</span> <span m=''2892930''>Unfortunately,</span>
  <span m=''2893590''>this</span> <span m=''2893840''>example</span> <span m=''2894310''>can</span>
  <span m=''2894570''>be</span> <span m=''2894690''>made</span> <span m=''2894960''>more</span>
  <span m=''2895220''>connected,</span> <span m=''2895650''>and</span> <span m=''2895720''>that''s</span>
  <span m=''2895910''>what</span> <span m=''2896000''>the</span> <span m=''2896090''>question</span>
  <span m=''2896420''>was.</span> <span m=''2897690''>So</span> <span m=''2898240''>this</span>
  <span m=''2898470''>is an</span> <span m=''2898850''>old</span> <span m=''2899050''>example</span>
  <span m=''2899480''>by</span> <span m=''2900005''>Henry</span> <span m=''2900270''>Crapo.</span>
  <span m=''2903690''>A</span> <span m=''2904190''>modification</span> <span m=''2904930''>by</span>
  <span m=''2905230''>Walter</span> <span m=''2905640''>Whiteley</span> <span m=''2906600''>is</span>
  <span m=''2906890''>that</span> <span m=''2907020''>if</span> <span m=''2907180''>you</span>
  <span m=''2907330''>add</span> <span m=''2907590''>a</span> <span m=''2907640''>single</span>
  <span m=''2907980''>point</span> <span m=''2908270''>here</span> <span m=''2908590''>and</span>
  <span m=''2908750''>attach</span> <span m=''2909240''>it</span> <span m=''2909740''>to</span>
  <span m=''2910110''>those</span> <span m=''2910520''>two</span> <span m=''2910700''>points--</span>
  <span m=''2911930''>sorry,</span> <span m=''2912130''>those</span> <span m=''2912350''>three</span>
  <span m=''2912580''>points--</span> <span m=''2913380''>this</span> <span m=''2913600''>will</span>
  <span m=''2913730''>be</span> <span m=''2914270''>three</span> <span m=''2914550''>connected,</span>
  <span m=''2915410''>still</span> <span m=''2915740''>be</span> <span m=''2915880''>flexible,</span>
  <span m=''2917180''>and</span> <span m=''2917350''>still</span> <span m=''2917550''>satisfy</span>
  <span m=''2917970''>Laman</span> <span m=''2919210''>because</span> <span m=''2919410''>we</span>
  <span m=''2919550''>added</span> <span m=''2919790''>three</span> <span m=''2920010''>edges</span>
  <span m=''2920300''>and</span> <span m=''2920390''>one</span> <span m=''2920570''>vertex,</span>
  <span m=''2920835''>so</span> <span m=''2921100''>it</span> <span m=''2921310''>still</span>
  <span m=''2922190''>satisfies</span> <span m=''2922700''>Laman.</span> </p><p><span
  m=''2923990''>So</span> <span m=''2924180''>that</span> <span m=''2924560''>sucks.</span>
  <span m=''2924850''>We</span> <span m=''2925000''>think,</span> <span m=''2925180''>oh,</span>
  <span m=''2925440''>maybe</span> <span m=''2925800''>four</span> <span m=''2926140''>connected.</span>
  <span m=''2926670''>Well,</span> <span m=''2926920''>you</span> <span m=''2927070''>can</span>
  <span m=''2927230''>make</span> <span m=''2927460''>it</span> <span m=''2927620''>four</span>
  <span m=''2927820''>connected,</span> <span m=''2928280''>too,</span> <span m=''2929470''>by</span>
  <span m=''2929890''>adding</span> <span m=''2930310''>a</span> <span m=''2930370''>triangle</span>
  <span m=''2930940''>in</span> <span m=''2930990''>the</span> <span m=''2931080''>center</span>
  <span m=''2931500''>and</span> <span m=''2931620''>connecting</span> <span m=''2932140''>these</span>
  <span m=''2932430''>six,</span> <span m=''2933420''>adding</span> <span m=''2933610''>these
  6</span> <span m=''2934100''>connections.</span> <span m=''2935720''>Well,</span>
  <span m=''2936150''>what</span> <span m=''2936350''>about</span> <span m=''2936690''>5</span>
  <span m=''2937180''>connected?</span> <span m=''2937690''>Well,</span> <span m=''2937800''>five</span>
  <span m=''2938150''>connected,</span> <span m=''2938570''>you</span> <span m=''2938690''>can</span>
  <span m=''2938840''>also</span> <span m=''2939160''>do.</span> <span m=''2939940''>And</span>
  <span m=''2940080''>this</span> <span m=''2940230''>is</span> <span m=''2940360''>an</span>
  <span m=''2940430''>example</span> <span m=''2940850''>called</span> <span m=''2941140''>the</span>
  <span m=''2941230''>banana</span> <span m=''2941870''>spider.</span> <span m=''2943670''>Although</span>
  <span m=''2943990''>it</span> <span m=''2944110''>seems</span> <span m=''2944360''>a</span>
  <span m=''2944410''>bit</span> <span m=''2944560''>of</span> <span m=''2944930''>a</span>
  <span m=''2945130''>misnomer.</span> <span m=''2945400''>It</span> <span m=''2945670''>should</span>
  <span m=''2945840''>be--</span> <span m=''2946450''>but</span> <span m=''2946770''>I</span>
  <span m=''2946920''>guess</span> <span m=''2947090''>banana</span> <span m=''2947370''>spiders</span>
  <span m=''2947710''>are</span> <span m=''2947790''>actual</span> <span m=''2948100''>object--</span>
  <span m=''2948590''>actual</span> <span m=''2949120''>species.</span> </p><p><span
  m=''2950060''>This</span> <span m=''2950240''>really</span> <span m=''2950450''>should</span>
  <span m=''2950600''>be</span> <span m=''2950710''>a</span> <span m=''2950760''>banana</span>
  <span m=''2951040''>insect</span> <span m=''2951620''>because</span> <span m=''2951930''>this</span>
  <span m=''2952110''>guy</span> <span m=''2952220''>has</span> <span m=''2952490''>six</span>
  <span m=''2952890''>legs,</span> <span m=''2954540''>three</span> <span m=''2954760''>on
  the</span> <span m=''2954880''>left,</span> <span m=''2955190''>three</span> <span
  m=''2955390''>on</span> <span m=''2955480''>the</span> <span m=''2955570''>right.</span>
  <span m=''2956640''>So if</span> <span m=''2957060''>it is</span> <span m=''2957300''>an</span>
  <span m=''2957380''>octahedron</span> <span m=''2957730''>in</span> <span m=''2957820''>the</span>
  <span m=''2957920''>center,</span> <span m=''2958850''>and</span> <span m=''2959040''>then</span>
  <span m=''2959170''>you</span> <span m=''2959420''>add</span> <span m=''2959740''>these</span>
  <span m=''2959930''>three</span> <span m=''2960090''>connections,</span> <span m=''2960550''>and</span>
  <span m=''2960710''>you</span> <span m=''2960830''>can</span> <span m=''2960960''>actually</span>
  <span m=''2961220''>prove</span> <span m=''2961540''>that</span> <span m=''2962010''>any</span>
  <span m=''2962310''>graph</span> <span m=''2962670''>you</span> <span m=''2962770''>have,</span>
  <span m=''2963490''>any</span> <span m=''2963790''>example</span> <span m=''2964890''>that''s</span>
  <span m=''2965290''>maybe</span> <span m=''2965670''>only</span> <span m=''2966180''>one</span>
  <span m=''2966440''>or</span> <span m=''2966550''>two</span> <span m=''2966800''>or</span>
  <span m=''2966890''>three</span> <span m=''2967090''>connected,</span> <span m=''2967480''>whatever,</span>
  <span m=''2968420''>you</span> <span m=''2968630''>can</span> <span m=''2968780''>make</span>
  <span m=''2969010''>it</span> <span m=''2969150''>five</span> <span m=''2969410''>connected</span>
  <span m=''2969900''>by</span> <span m=''2970110''>whenever</span> <span m=''2970460''>you</span>
  <span m=''2970530''>have</span> <span m=''2970770''>two</span> <span m=''2970960''>four</span>
  <span m=''2971230''>connected</span> <span m=''2971590''>components--</span> <span
  m=''2972600''>or</span> <span m=''2972690''>five</span> <span m=''2972970''>things</span>
  <span m=''2973160''>components</span> <span m=''2973650''>I</span> <span m=''2973700''>guess--</span>
  <span m=''2974730''>just</span> <span m=''2974930''>add</span> <span m=''2975220''>a</span>
  <span m=''2975480''>spider</span> <span m=''2975910''>in</span> <span m=''2975990''>the</span>
  <span m=''2976060''>middle</span> <span m=''2976420''>to</span> <span m=''2976780''>bridge</span>
  <span m=''2977040''>them,</span> <span m=''2977800''>and</span> <span m=''2978040''>it</span>
  <span m=''2978100''>will</span> <span m=''2978240''>be</span> <span m=''2978440''>as</span>
  <span m=''2978680''>flexible</span> <span m=''2979230''>as</span> <span m=''2979330''>before.</span>
  <span m=''2980210''>And</span> <span m=''2980350''>it</span> <span m=''2980390''>will</span>
  <span m=''2980490''>still</span> <span m=''2980730''>satisfy</span> <span m=''2981130''>Laman.</span>
  </p><p><span m=''2981960''>So</span> <span m=''2982990''>five</span> <span m=''2983340''>connectivity</span>
  <span m=''2983930''>doesn''t</span> <span m=''2984200''>buy</span> <span m=''2984410''>you</span>
  <span m=''2984570''>anything</span> <span m=''2985160''>unfortunately.</span> <span
  m=''2986700''>I</span> <span m=''2986840''>guess</span> <span m=''2987040''>you</span>
  <span m=''2987140''>could</span> <span m=''2987270''>ask</span> <span m=''2987420''>for</span>
  <span m=''2987530''>six</span> <span m=''2987900''>connectivity,</span> <span m=''2988340''>but</span>
  <span m=''2989070''>six</span> <span m=''2989380''>connectivity,</span> <span m=''2989840''>I</span>
  <span m=''2989910''>think,</span> <span m=''2990120''>is</span> <span m=''2990980''>impossible</span>
  <span m=''2991840''>because</span> <span m=''2992150''>you</span> <span m=''2992300''>only</span>
  <span m=''2992530''>have</span> <span m=''2992790''>3n</span> <span m=''2993110''>minus</span>
  <span m=''2993380''>6</span> <span m=''2993640''>edges.</span> <span m=''2996530''>That''s</span>
  <span m=''2996810''>the</span> <span m=''2997050''>limit.</span> <span m=''2998220''>So</span>
  <span m=''2998350''>sadly,</span> <span m=''2998670''>connectivity</span> <span
  m=''2999250''>is</span> <span m=''2999370''>not</span> <span m=''2999750''>the</span>
  <span m=''2999850''>right--</span> <span m=''3000210''>doesn''t</span> <span m=''3000700''>buy
  us</span> <span m=''3001070''>anything.</span> <span m=''3002160''>And</span> <span
  m=''3002250''>that''s</span> <span m=''3002900''>what</span> <span m=''3003060''>we</span>
  <span m=''3003180''>know</span> <span m=''3003400''>about</span> <span m=''3004450''>vertex</span>
  <span m=''3005080''>and</span> <span m=''3005410''>bar</span> <span m=''3006410''>structures</span>
  <span m=''3007600''>in</span> <span m=''3007980''>3D</span> <span m=''3009160''>sadly.</span>
  <span m=''3009800''>Tough</span> <span m=''3010080''>open</span> <span m=''3010350''>problem.</span>
  <span m=''3011990''>Any</span> <span m=''3012640''>questions?</span> <span m=''3015400''>That''s</span>
  <span m=''3015730''>it</span> <span m=''3016130''>for</span> <span m=''3016350''>today.</span>
  </p>'
type: course
uid: 02d98a0c1ba96ee4f8f430099fc5f03c

---
None