---
about_this_resource_text: <p><strong>Description:</strong> This lecture reviews algorithms
  for testing flat-foldability for a 1D MV pattern and for single-vertex MV pattern.
  An exercise walks through determining local flat-foldability, and questions cover
  higher dimensions and motivations for flat-foldability.</p> <p><strong>Speaker:</strong>
  Erik Demaine</p>
course_id: 6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012
embedded_media:
- id: Video-YouTube-Stream
  media_location: yIjTCMlIgpU
  parent_uid: 87aeeef4bdff5c2fa8d7af79b364fe4a
  title: Video-YouTube-Stream
  type: Video
  uid: f8060a7a160e20ad491523e6d9b4bb02
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/yIjTCMlIgpU/default.jpg
  parent_uid: 87aeeef4bdff5c2fa8d7af79b364fe4a
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 4aae664fbc3edf7116b8289f3a12b97e
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id909720246
  parent_uid: 87aeeef4bdff5c2fa8d7af79b364fe4a
  title: Video-iTunes U-MP4
  type: Video
  uid: fb46605472ac4dfbbb010052c6de811c
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.849F12/MIT6_849F12_class03_300k.mp4
  parent_uid: 87aeeef4bdff5c2fa8d7af79b364fe4a
  title: Video-Internet Archive-MP4
  type: Video
  uid: 2a9f26422a707cc2fa4f942ffd89a894
- id: 3Play-3PlayYouTubeid-MP4
  media_location: yIjTCMlIgpU
  parent_uid: 87aeeef4bdff5c2fa8d7af79b364fe4a
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 65882eef476f40c61a53a398f85a974c
- id: yIjTCMlIgpU.srt
  parent_uid: 87aeeef4bdff5c2fa8d7af79b364fe4a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/class-3-single-vertex-crease-patterns/yIjTCMlIgpU.srt
  title: 3play caption file
  type: null
  uid: 28d7d685ff0944269a8873e9655250a4
- id: yIjTCMlIgpU.pdf
  parent_uid: 87aeeef4bdff5c2fa8d7af79b364fe4a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/class-3-single-vertex-crease-patterns/yIjTCMlIgpU.pdf
  title: 3play pdf file
  type: null
  uid: a239fef68f6c23f9e7aa100b313f501c
- id: Caption-3Play YouTube id-SRT
  parent_uid: 87aeeef4bdff5c2fa8d7af79b364fe4a
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 9960590c0939ae86cafde3757f667a06
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 87aeeef4bdff5c2fa8d7af79b364fe4a
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 4b6b922defebfa8e9cf622514db6e2dc
inline_embed_id: 50987739class3:single-vertexcreasepatterns68609595
layout: video
order_index: null
parent_uid: a370594e3650963ebb6270f5dc3b68ed
related_resources_text: ''
short_url: class-3-single-vertex-crease-patterns
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-849-geometric-folding-algorithms-linkages-origami-polyhedra-fall-2012/class-and-lecture-videos/class-3-single-vertex-crease-patterns
template_type: Tabbed
title: 'Class 3: Single-Vertex Crease Patterns'
transcript: '<p><span m=''3060''>PROFESSOR: OK,</span> <span m=''3520''>welcome</span>
  <span m=''3880''>back</span> <span m=''4170''>to</span> <span m=''4350''>6849.</span>
  <span m=''6830''>So</span> <span m=''7370''>last</span> <span m=''8330''>lecture,</span>
  <span m=''8870''>lecture</span> <span m=''9230''>three,</span> <span m=''10290''>we</span>
  <span m=''10360''>were</span> <span m=''10510''>talking</span> <span m=''10890''>about</span>
  <span m=''12410''>local</span> <span m=''13020''>foldability</span> <span m=''14200''>and</span>
  <span m=''14880''>some</span> <span m=''15210''>complicated</span> <span m=''16030''>flat</span>
  <span m=''16390''>folding,</span> <span m=''18190''>like</span> <span m=''18380''>a</span>
  <span m=''18910''>flapping</span> <span m=''19270''>bird</span> <span m=''19490''>here.</span>
  <span m=''20690''>We</span> <span m=''20850''>were</span> <span m=''20970''>looking</span>
  <span m=''21380''>at</span> <span m=''22150''>a</span> <span m=''22250''>single</span>
  <span m=''22550''>vertex</span> <span m=''24500''>and</span> <span m=''24810''>locally</span>
  <span m=''25400''>around</span> <span m=''25780''>that</span> <span m=''25950''>vertex</span>
  <span m=''26580''>what</span> <span m=''26680''>properties</span> <span m=''27220''>it</span>
  <span m=''27300''>would</span> <span m=''27430''>have</span> <span m=''27650''>to</span>
  <span m=''27760''>have.</span> <span m=''28750''>And</span> <span m=''29010''>we
  saw</span> <span m=''29310''>Kawasaki''s</span> <span m=''30000''>theorem</span>
  <span m=''30340''>which</span> <span m=''30530''>characterized</span> <span m=''30940''>the</span>
  <span m=''31080''>angles.</span> <span m=''31870''>And</span> <span m=''32150''>without</span>
  <span m=''32470''>a</span> <span m=''32509''>mountain</span> <span m=''32780''>valley</span>
  <span m=''33060''>assignment</span> <span m=''33520''>Kawasaki</span> <span m=''34100''>was</span>
  <span m=''34280''>all</span> <span m=''34510''>you</span> <span m=''34660''>needed.</span>
  <span m=''35670''>The</span> <span m=''35930''>alternating</span> <span m=''36220''>sum</span>
  <span m=''36410''>of</span> <span m=''36510''>angles</span> <span m=''36770''>should</span>
  <span m=''36970''>be</span> <span m=''37100''>0.</span> <span m=''38660''>And</span>
  <span m=''40030''>given</span> <span m=''40320''>a</span> <span m=''40370''>mountain</span>
  <span m=''40660''>valley</span> <span m=''41010''>pattern,</span> <span m=''41770''>locally</span>
  <span m=''43130''>we</span> <span m=''43320''>characterize</span> <span m=''43820''>things</span>
  <span m=''44070''>as</span> <span m=''44300''>a</span> <span m=''44390''>sequence,</span>
  <span m=''45010''>anything</span> <span m=''45310''>you</span> <span m=''45420''>can</span>
  <span m=''45530''>do</span> <span m=''45650''>by a</span> <span m=''45830''>sequence</span>
  <span m=''46250''>of</span> <span m=''46360''>crimps.</span> <span m=''46890''>So</span>
  <span m=''47770''>sort</span> <span m=''48310''>of</span> <span m=''48440''>a</span>
  <span m=''48550''>similar</span> <span m=''48970''>version</span> <span m=''49400''>to</span>
  <span m=''50680''>lecture</span> <span m=''50980''>two,</span> <span m=''51410''>which</span>
  <span m=''51610''>was</span> <span m=''51770''>about</span> <span m=''52090''>1D</span>
  <span m=''52610''>flat</span> <span m=''52920''>foldability.</span> <span m=''53550''>There</span>
  <span m=''53770''>we</span> <span m=''53900''>needed</span> <span m=''54180''>crimps</span>
  <span m=''54670''>and</span> <span m=''54775''>end</span> <span m=''54880''>folds.</span>
  <span m=''55720''>Here</span> <span m=''56010''>we</span> <span m=''56120''>needed</span>
  <span m=''57210''>just</span> <span m=''57490''>crimps,</span> <span m=''58090''>which</span>
  <span m=''58200''>is</span> <span m=''58320''>easier.</span> </p><p><span m=''60690''>So</span>
  <span m=''62090''>I''m</span> <span m=''62190''>going</span> <span m=''62290''>to</span>
  <span m=''62360''>jump</span> <span m=''62580''>into</span> <span m=''63090''>questions.</span>
  <span m=''63910''>And</span> <span m=''64209''>in</span> <span m=''64300''>particular,</span>
  <span m=''64840''>this</span> <span m=''65040''>is</span> <span m=''65239''>an</span>
  <span m=''66220''>opportunity</span> <span m=''66920''>for</span> <span m=''67080''>me</span>
  <span m=''67280''>to</span> <span m=''67440''>talk</span> <span m=''67700''>about</span>
  <span m=''68570''>the</span> <span m=''69030''>main</span> <span m=''69280''>thing</span>
  <span m=''69460''>that</span> <span m=''69570''>I</span> <span m=''69660''>skipped</span>
  <span m=''70210''>last</span> <span m=''70740''>class,</span> <span m=''71200''>class</span>
  <span m=''71510''>two,</span> <span m=''72640''>because</span> <span m=''73100''>it</span>
  <span m=''73200''>relates</span> <span m=''73720''>again</span> <span m=''74170''>to</span>
  <span m=''74290''>this</span> <span m=''74510''>lecture,</span> <span m=''74930''>which</span>
  <span m=''75050''>is</span> <span m=''75270''>how</span> <span m=''75550''>do</span>
  <span m=''75640''>we</span> <span m=''75740''>do</span> <span m=''75870''>this</span>
  <span m=''76080''>algorithmically?</span> <span m=''77480''>So</span> <span m=''77650''>it''s</span>
  <span m=''77750''>one</span> <span m=''77910''>thing</span> <span m=''78070''>to</span>
  <span m=''78130''>say,</span> <span m=''78370''>oh,</span> <span m=''78580''>just</span>
  <span m=''78780''>do</span> <span m=''78920''>crimps and</span> <span m=''79330''>end</span>
  <span m=''79490''>folds</span> <span m=''79780''>till</span> <span m=''79950''>you</span>
  <span m=''80090''>can''t</span> <span m=''80390''>anymore,</span> <span m=''81280''>and</span>
  <span m=''81470''>then</span> <span m=''81670''>when</span> <span m=''81790''>you</span>
  <span m=''81920''>run</span> <span m=''82110''>out</span> <span m=''82200''>of</span>
  <span m=''82280''>stuff</span> <span m=''82510''>to</span> <span m=''82620''>do,</span>
  <span m=''83550''>if</span> <span m=''83700''>you''re</span> <span m=''83810''>done,</span>
  <span m=''84080''>you''re</span> <span m=''84210''>done,</span> <span m=''84490''>otherwise</span>
  <span m=''84940''>it''s</span> <span m=''85000''>not</span> <span m=''85340''>flat</span>
  <span m=''85420''>foldable.</span> <span m=''86040''>That''s</span> <span m=''86340''>true.</span>
  <span m=''87270''>But</span> <span m=''87450''>the</span> <span m=''87580''>obvious</span>
  <span m=''87840''>way</span> <span m=''87950''>to</span> <span m=''88010''>implement</span>
  <span m=''88440''>that</span> <span m=''88590''>algorithm</span> <span m=''89010''>is</span>
  <span m=''89120''>to</span> <span m=''89240''>sweep</span> <span m=''89810''>over</span>
  <span m=''90050''>the</span> <span m=''90180''>crease</span> <span m=''90450''>pattern,</span>
  <span m=''90800''>look</span> <span m=''91000''>for</span> <span m=''91220''>any</span>
  <span m=''91390''>crimps or</span> <span m=''91800''>end</span> <span m=''91990''>folds.</span>
  <span m=''92380''>If you</span> <span m=''92480''>find</span> <span m=''92740''>one,</span>
  <span m=''92940''>do</span> <span m=''93120''>it,</span> <span m=''93450''>and</span>
  <span m=''93620''>then</span> <span m=''93740''>repeat</span> <span m=''94510''>and</span>
  <span m=''94610''>keep</span> <span m=''94860''>sweeping.</span> <span m=''95290''>And</span>
  <span m=''95480''>that</span> <span m=''95650''>would</span> <span m=''95780''>take</span>
  <span m=''96110''>quadratic</span> <span m=''96700''>time,</span> <span m=''97020''>because</span>
  <span m=''97530''>in</span> <span m=''97640''>the</span> <span m=''97730''>worst</span>
  <span m=''97980''>case</span> <span m=''98260''>every</span> <span m=''98530''>scan</span>
  <span m=''99390''>you</span> <span m=''99480''>have</span> <span m=''99590''>to</span>
  <span m=''100230''>look</span> <span m=''100450''>through</span> <span m=''100600''>the</span>
  <span m=''100730''>whole</span> <span m=''100990''>pattern</span> <span m=''101460''>and
  at</span> <span m=''101640''>the</span> <span m=''101700''>very</span> <span m=''102040''>end</span>
  <span m=''102200''>you</span> <span m=''102300''>find</span> <span m=''102550''>what</span>
  <span m=''102670''>you</span> <span m=''102730''>need</span> <span m=''102920''>to</span>
  <span m=''103030''>do.</span> <span m=''103590''>So</span> <span m=''103740''>after</span>
  <span m=''104020''>about</span> <span m=''104270''>n</span> <span m=''104460''>operations--</span>
  <span m=''105200''>n</span> <span m=''105420''>is</span> <span m=''105610''>the</span>
  <span m=''105740''>number</span> <span m=''106060''>of</span> <span m=''106130''>creases</span>
  <span m=''106570''>in</span> <span m=''106650''>your</span> <span m=''106780''>pattern--</span>
  <span m=''107480''>you</span> <span m=''107600''>find</span> <span m=''107830''>what</span>
  <span m=''107940''>you</span> <span m=''107980''>need</span> <span m=''108130''>to</span>
  <span m=''108220''>do,</span> <span m=''108360''>you</span> <span m=''108480''>do</span>
  <span m=''108610''>the</span> <span m=''108750''>operation,</span> <span m=''109010''>and</span>
  <span m=''109270''>then</span> <span m=''109380''>you</span> <span m=''109490''>repeat.</span>
  <span m=''110490''>So</span> <span m=''111340''>n</span> <span m=''111530''>plus</span>
  <span m=''111770''>n</span> <span m=''111920''>plus</span> <span m=''112150''>n,</span>
  <span m=''112350''>n</span> <span m=''112540''>times,</span> <span m=''112970''>is</span>
  <span m=''113200''>n</span> <span m=''113410''>squared.</span> <span m=''115050''>But</span>
  <span m=''115290''>you</span> <span m=''115420''>can</span> <span m=''115550''>do</span>
  <span m=''115670''>better</span> <span m=''116200''>and</span> <span m=''116700''>it''s</span>
  <span m=''117410''>been</span> <span m=''117560''>alluded</span> <span m=''117940''>to</span>
  <span m=''118190''>in</span> <span m=''119003''>the</span> <span m=''119770''>lectures,</span>
  <span m=''120430''>but</span> <span m=''120830''>it</span> <span m=''120870''>wasn''t</span>
  <span m=''121120''>covered.</span> <span m=''121790''>And</span> <span m=''122050''>so</span>
  <span m=''122140''>I</span> <span m=''122190''>wanted</span> <span m=''122340''>to</span>
  <span m=''122470''>cover</span> <span m=''122770''>it,</span> <span m=''122810''>because</span>
  <span m=''123000''>there''s</span> <span m=''123130''>actually a</span> <span m=''123460''>really</span>
  <span m=''123670''>simple</span> <span m=''123990''>way</span> <span m=''124100''>to</span>
  <span m=''124200''>do</span> <span m=''124330''>it.</span> <span m=''124460''>There''s</span>
  <span m=''124610''>one</span> <span m=''124850''>version</span> <span m=''125200''>in</span>
  <span m=''125370''>the</span> <span m=''125450''>textbook,</span> <span m=''126770''>but</span>
  <span m=''127050''>there</span> <span m=''127240''>is</span> <span m=''127360''>a</span>
  <span m=''127480''>simpler</span> <span m=''127850''>way.</span> <span m=''128669''>So</span>
  <span m=''130606''>I</span> <span m=''131070''>want to</span> <span m=''131100''>talk</span>
  <span m=''131350''>about</span> <span m=''131540''>that.</span> </p><p><span m=''133370''>This
  is</span> <span m=''133570''>a</span> <span m=''133650''>new</span> <span m=''133810''>way</span>
  <span m=''133940''>we</span> <span m=''134090''>just</span> <span m=''134340''>invented</span>
  <span m=''136800''>last</span> <span m=''137080''>week?</span> <span m=''137260''>This</span>
  <span m=''137440''>week?</span> <span m=''137680''>I</span> <span m=''137730''>forget.</span>
  <span m=''141210''>So</span> <span m=''141540''>I''m</span> <span m=''141690''>going</span>
  <span m=''141790''>to</span> <span m=''141980''>first</span> <span m=''142240''>talk</span>
  <span m=''142530''>about</span> <span m=''142780''>it</span> <span m=''142890''>in</span>
  <span m=''143120''>the</span> <span m=''143300''>1D</span> <span m=''143710''>scenario,</span>
  <span m=''145700''>but</span> <span m=''145940''>it''s</span> <span m=''146160''>pretty</span>
  <span m=''146400''>much</span> <span m=''146640''>the</span> <span m=''146740''>same</span>
  <span m=''149460''>for</span> <span m=''149630''>both.</span> <span m=''153790''>1D''s</span>
  <span m=''154130''>a</span> <span m=''154180''>little</span> <span m=''154370''>bit</span>
  <span m=''154500''>easier</span> <span m=''154770''>to</span> <span m=''154840''>think</span>
  <span m=''155020''>about,</span> <span m=''155300''>though.</span> <span m=''170670''>So</span>
  <span m=''171800''>1D</span> <span m=''172160''>mountain</span> <span m=''172410''>valley</span>
  <span m=''172700''>pattern</span> <span m=''177220''>something</span> <span m=''177570''>like</span>
  <span m=''177770''>this.</span> <span m=''187240''>So</span> <span m=''187540''>I''m</span>
  <span m=''187690''>going</span> <span m=''187800''>to</span> <span m=''187860''>follow</span>
  <span m=''188130''>the</span> <span m=''188250''>same</span> <span m=''188450''>approach,</span>
  <span m=''188900''>which</span> <span m=''189150''>is</span> <span m=''189270''>sweep</span>
  <span m=''189590''>left</span> <span m=''189810''>to</span> <span m=''189920''>right</span>
  <span m=''190160''>until</span> <span m=''190560''>I</span> <span m=''190680''>find</span>
  <span m=''191370''>either</span> <span m=''191570''>an</span> <span m=''191650''>end</span>
  <span m=''191860''>fold</span> <span m=''192200''>or a</span> <span m=''192430''>crimp</span>
  <span m=''192720''>that</span> <span m=''192850''>I</span> <span m=''192930''>can</span>
  <span m=''193110''>do.</span> <span m=''194150''>So</span> <span m=''194360''>in</span>
  <span m=''194440''>this</span> <span m=''194680''>case,</span> <span m=''195180''>maybe</span>
  <span m=''195560''>this</span> <span m=''195800''>would</span> <span m=''195890''>be</span>
  <span m=''196020''>the</span> <span m=''196120''>first</span> <span m=''197040''>thing</span>
  <span m=''197240''>that</span> <span m=''197390''>I</span> <span m=''197490''>find</span>
  <span m=''197930''>sweeping</span> <span m=''198240''>left</span> <span m=''198460''>to</span>
  <span m=''198550''>right.</span> <span m=''199230''>That''s</span> <span m=''199520''>a</span>
  <span m=''199570''>crimpable</span> <span m=''200070''>pair--</span> <span m=''200450''>or</span>
  <span m=''201200''>crimpable</span> <span m=''201820''>segment,</span> <span m=''202195''>I''m</span>
  <span m=''202570''>going</span> <span m=''202780''>to</span> <span m=''202810''>call</span>
  <span m=''203120''>it--</span> <span m=''203620''>is</span> <span m=''203830''>just</span>
  <span m=''204020''>one</span> <span m=''204240''>that</span> <span m=''204370''>is</span>
  <span m=''204520''>locally</span> <span m=''205010''>smallest.</span> <span m=''205710''>It''s</span>
  <span m=''205860''>less</span> <span m=''206110''>than</span> <span m=''206240''>or</span>
  <span m=''206350''>equal</span> <span m=''206630''>to</span> <span m=''206840''>its</span>
  <span m=''207080''>two</span> <span m=''207270''>neighbors</span> <span m=''207760''>in</span>
  <span m=''207920''>length,</span> <span m=''208520''>and</span> <span m=''209140''>it</span>
  <span m=''209480''>has</span> <span m=''209710''>two</span> <span m=''209960''>different</span>
  <span m=''210290''>assignments,</span> <span m=''211150''>M/V</span> <span m=''211600''>or</span>
  <span m=''211710''>V/M.</span> <span m=''212810''>So</span> <span m=''212990''>that''s</span>
  <span m=''213200''>a</span> <span m=''213250''>crimpable</span> <span m=''213740''>pair,</span>
  <span m=''214060''>because it''s</span> <span m=''214380''>shorter than</span> <span
  m=''214760''>those</span> <span m=''214930''>two</span> <span m=''215060''>guys.</span>
  <span m=''216630''>So</span> <span m=''216870''>that''s</span> <span m=''217170''>the</span>
  <span m=''217460''>basic</span> <span m=''217850''>algorithm,</span> <span m=''218230''>but</span>
  <span m=''218410''>what</span> <span m=''218560''>I</span> <span m=''218630''>do</span>
  <span m=''218870''>after</span> <span m=''219170''>that</span> <span m=''219420''>is</span>
  <span m=''219570''>going</span> <span m=''219700''>to</span> <span m=''219770''>be</span>
  <span m=''219890''>a</span> <span m=''219950''>little</span> <span m=''220120''>bit</span>
  <span m=''220280''>different.</span> </p><p><span m=''222670''>So</span> <span m=''223160''>I</span>
  <span m=''223400''>want</span> <span m=''223670''>to</span> <span m=''223750''>search</span>
  <span m=''225760''>left</span> <span m=''226100''>to</span> <span m=''226220''>right</span>
  <span m=''229950''>for</span> <span m=''230430''>a</span> <span m=''230560''>segment</span>
  <span m=''236610''>that''s</span> <span m=''236830''>either</span> <span m=''237150''>crimpable</span>
  <span m=''238360''>or</span> <span m=''238640''>end</span> <span m=''238860''>foldable.</span>
  <span m=''250140''>And</span> <span m=''250470''>there''s</span> <span m=''250610''>two</span>
  <span m=''250750''>situations.</span> <span m=''251710''>If</span> <span m=''251910''>I</span>
  <span m=''251980''>don''t</span> <span m=''252260''>find</span> <span m=''252540''>any</span>
  <span m=''254050''>operations</span> <span m=''254650''>to</span> <span m=''254760''>do,</span>
  <span m=''256120''>then</span> <span m=''257149''>we</span> <span m=''257320''>stop.</span>
  <span m=''258170''>And</span> <span m=''258450''>if</span> <span m=''258560''>there</span>
  <span m=''258660''>are</span> <span m=''258740''>any</span> <span m=''258940''>creases</span>
  <span m=''259310''>left</span> <span m=''259610''>we</span> <span m=''259720''>know</span>
  <span m=''259920''>that</span> <span m=''260110''>the</span> <span m=''260209''>resulting</span>
  <span m=''260680''>thing</span> <span m=''260910''>is</span> <span m=''261019''>not</span>
  <span m=''261250''>flat</span> <span m=''261470''>foldable</span> <span m=''261990''>from</span>
  <span m=''262240''>what</span> <span m=''262370''>we</span> <span m=''262510''>proved</span>
  <span m=''262800''>in</span> <span m=''262870''>lecture</span> <span m=''263240''>two.</span>
  <span m=''264350''>If</span> <span m=''264690''>there''s</span> <span m=''264860''>no</span>
  <span m=''265000''>crimp</span> <span m=''265160''>or end</span> <span m=''265490''>fold,
  you''re</span> <span m=''265840''>not flat</span> <span m=''266200''>foldable.</span>
  <span m=''269260''>But</span> <span m=''269890''>if</span> <span m=''270060''>you</span>
  <span m=''270160''>do</span> <span m=''270310''>find</span> <span m=''270600''>something,</span>
  <span m=''272120''>then</span> <span m=''273990''>do</span> <span m=''274160''>the</span>
  <span m=''274250''>fold.</span> <span m=''275390''>This</span> <span m=''275540''>is</span>
  <span m=''275690''>so</span> <span m=''275970''>far</span> <span m=''276320''>pretty</span>
  <span m=''276490''>obvious.</span> </p><p><span m=''277530''>I''m</span> <span m=''277740''>going</span>
  <span m=''277840''>to</span> <span m=''277910''>draw</span> <span m=''278120''>the</span>
  <span m=''278170''>picture</span> <span m=''278490''>for</span> <span m=''279120''>a</span>
  <span m=''279250''>crimp</span> <span m=''279490''>situation.</span> <span m=''281060''>So</span>
  <span m=''281300''>in</span> <span m=''281370''>the</span> <span m=''281450''>crimp</span>
  <span m=''281660''>situation--</span> <span m=''283430''>these</span> <span m=''283640''>are</span>
  <span m=''283710''>the</span> <span m=''284380''>previous</span> <span m=''284770''>and</span>
  <span m=''284860''>next</span> <span m=''285150''>creases--</span> <span m=''286310''>we</span>
  <span m=''286450''>have</span> <span m=''286590''>these</span> <span m=''286760''>lengths</span>
  <span m=''287110''>x,</span> <span m=''287380''>y,</span> <span m=''287600''>and</span>
  <span m=''287790''>z.</span> <span m=''288550''>We</span> <span m=''288680''>know</span>
  <span m=''288840''>that</span> <span m=''289050''>y</span> <span m=''289350''>is</span>
  <span m=''289490''>less</span> <span m=''289710''>than</span> <span m=''289810''>or
  equal</span> <span m=''289910''>to</span> <span m=''289990''>z</span> <span m=''290390''>and</span>
  <span m=''290730''>is</span> <span m=''290910''>less</span> <span m=''291120''>than</span>
  <span m=''291220''>or</span> <span m=''291320''>equal</span> <span m=''291350''>to</span>
  <span m=''291440''>x.</span> <span m=''292900''>And</span> <span m=''293220''>after</span>
  <span m=''293540''>we</span> <span m=''293630''>do</span> <span m=''293740''>the</span>
  <span m=''293850''>crimp,</span> <span m=''296390''>it</span> <span m=''296560''>looks</span>
  <span m=''296810''>like</span> <span m=''297070''>this.</span> <span m=''298470''>So</span>
  <span m=''298760''>we</span> <span m=''298880''>have</span> <span m=''299240''>x,</span>
  <span m=''299830''>y,</span> <span m=''300180''>and</span> <span m=''300390''>z</span>
  <span m=''300670''>here,</span> <span m=''301560''>but</span> <span m=''302320''>we''re</span>
  <span m=''302500''>then</span> <span m=''302710''>going</span> <span m=''302840''>to</span>
  <span m=''302900''>fuse</span> <span m=''303220''>this</span> <span m=''303410''>material</span>
  <span m=''303800''>together,</span> <span m=''304160''>because</span> <span m=''305020''>these</span>
  <span m=''305220''>creases</span> <span m=''305590''>are</span> <span m=''305680''>done</span>
  <span m=''305880''>with.</span> <span m=''306160''>We</span> <span m=''306210''>don''t</span>
  <span m=''306660''>really</span> <span m=''306860''>care</span> <span m=''307080''>about</span>
  <span m=''307300''>them.</span> <span m=''307880''>The</span> <span m=''307980''>new</span>
  <span m=''308140''>length</span> <span m=''308500''>that</span> <span m=''308600''>we</span>
  <span m=''308710''>get</span> <span m=''309260''>is</span> <span m=''309610''>x</span>
  <span m=''309990''>minus</span> <span m=''310380''>y</span> <span m=''310680''>plus</span>
  <span m=''311100''>z.</span> </p><p><span m=''314390''>OK.</span> <span m=''314610''>So</span>
  <span m=''314790''>that''s</span> <span m=''315050''>what</span> <span m=''315180''>I</span>
  <span m=''315220''>mean</span> <span m=''315420''>by</span> <span m=''315560''>do</span>
  <span m=''315750''>the</span> <span m=''315850''>fold.</span> <span m=''316800''>And</span>
  <span m=''320430''>we''ll</span> <span m=''320480''>also</span> <span m=''320740''>call</span>
  <span m=''320940''>this</span> <span m=''321060''>sort</span> <span m=''321330''>of</span>
  <span m=''321400''>merging</span> <span m=''321970''>the</span> <span m=''322060''>segments,</span>
  <span m=''326360''>meaning</span> <span m=''326640''>replace--</span> <span m=''327400''>so</span>
  <span m=''327590''>normally</span> <span m=''327900''>we</span> <span m=''327980''>have</span>
  <span m=''328080''>a</span> <span m=''328130''>sequence</span> <span m=''328470''>of</span>
  <span m=''328540''>lengths--</span> <span m=''328900''>replace</span> <span m=''329340''>x,
  y,</span> <span m=''329785''>z</span> <span m=''330530''>with</span> <span m=''330700''>x</span>
  <span m=''330870''>minus</span> <span m=''331110''>y</span> <span m=''331240''>plus</span>
  <span m=''331490''>z,</span> <span m=''332040''>remove</span> <span m=''332420''>these</span>
  <span m=''332620''>two</span> <span m=''332770''>creases</span> <span m=''333260''>which</span>
  <span m=''333490''>were,</span> <span m=''334000''>say,</span> <span m=''334280''>M
  and</span> <span m=''334760''>V.</span> </p><p><span m=''336470''>Now</span> <span
  m=''336670''>we</span> <span m=''336780''>want</span> <span m=''336970''>to</span>
  <span m=''337070''>continue.</span> <span m=''338340''>And</span> <span m=''338790''>the</span>
  <span m=''338910''>realization</span> <span m=''339580''>is</span> <span m=''339720''>that</span>
  <span m=''339790''>we</span> <span m=''339920''>don''t</span> <span m=''340210''>have</span>
  <span m=''340430''>to</span> <span m=''340540''>start</span> <span m=''340880''>over</span>
  <span m=''341190''>our</span> <span m=''341320''>search</span> <span m=''342380''>in</span>
  <span m=''342580''>searching</span> <span m=''342970''>left</span> <span m=''343190''>to</span>
  <span m=''343280''>right</span> <span m=''343530''>for a</span> <span m=''343710''>crimpable</span>
  <span m=''344160''>thing.</span> <span m=''345330''>If</span> <span m=''345500''>we</span>
  <span m=''346260''>went</span> <span m=''346570''>all</span> <span m=''346920''>the</span>
  <span m=''346990''>way</span> <span m=''347130''>through</span> <span m=''347300''>the</span>
  <span m=''347400''>pattern</span> <span m=''347770''>and</span> <span m=''347850''>then</span>
  <span m=''347970''>finally</span> <span m=''348450''>found</span> <span m=''348650''>a</span>
  <span m=''348710''>crimp</span> <span m=''348940''>at</span> <span m=''349020''>the</span>
  <span m=''349150''>end,</span> <span m=''349840''>should</span> <span m=''350070''>we</span>
  <span m=''350200''>start</span> <span m=''350530''>way</span> <span m=''350680''>back</span>
  <span m=''350940''>here?</span> <span m=''352300''>No.</span> <span m=''352790''>There''s</span>
  <span m=''352970''>no</span> <span m=''353080''>point.</span> <span m=''353530''>You</span>
  <span m=''353630''>might</span> <span m=''353830''>as</span> <span m=''353930''>well</span>
  <span m=''354080''>start</span> <span m=''354470''>basically</span> <span m=''354970''>where</span>
  <span m=''355200''>you</span> <span m=''355340''>just</span> <span m=''355590''>were.</span>
  <span m=''357000''>Not</span> <span m=''357230''>quite.</span> <span m=''358250''>You</span>
  <span m=''358310''>have</span> <span m=''358490''>to</span> <span m=''358590''>go</span>
  <span m=''358750''>back</span> <span m=''359080''>one</span> <span m=''359270''>step.</span>
  <span m=''360920''>So</span> <span m=''362690''>the</span> <span m=''362900''>next</span>
  <span m=''363160''>step</span> <span m=''363640''>in</span> <span m=''363790''>this</span>
  <span m=''363970''>algorithm</span> <span m=''365100''>is</span> <span m=''366690''>go</span>
  <span m=''366930''>back</span> <span m=''368810''>one</span> <span m=''369100''>step,</span>
  <span m=''371130''>and</span> <span m=''371350''>then</span> <span m=''371520''>continue</span>
  <span m=''371940''>the</span> <span m=''372020''>search.</span> <span m=''373510''>Back</span>
  <span m=''373820''>means</span> <span m=''374370''>left.</span> <span m=''380230''>And</span>
  <span m=''380590''>the</span> <span m=''380670''>search</span> <span m=''381500''>is</span>
  <span m=''383860''>this</span> <span m=''384060''>line.</span> <span m=''386070''>OK.</span>
  <span m=''386350''>So</span> <span m=''386540''>that''s</span> <span m=''386890''>an</span>
  <span m=''387170''>algorithm,</span> <span m=''387700''>a</span> <span m=''387800''>little</span>
  <span m=''388260''>loop</span> <span m=''388560''>there.</span> </p><p><span m=''390510''>So</span>
  <span m=''390850''>in</span> <span m=''391020''>this</span> <span m=''391190''>example</span>
  <span m=''395390''>we--</span> <span m=''396220''>the</span> <span m=''396630''>point</span>
  <span m=''397040''>of</span> <span m=''397260''>what''s</span> <span m=''397470''>going</span>
  <span m=''397730''>on</span> <span m=''397870''>and</span> <span m=''398080''>the</span>
  <span m=''398230''>reason</span> <span m=''398480''>this</span> <span m=''398650''>algorithm</span>
  <span m=''399060''>is</span> <span m=''399200''>correct</span> <span m=''399900''>is</span>
  <span m=''400060''>we</span> <span m=''400180''>just</span> <span m=''400420''>modified</span>
  <span m=''401060''>these</span> <span m=''401320''>three</span> <span m=''401570''>segments.</span>
  <span m=''402400''>And</span> <span m=''402520''>we</span> <span m=''402590''>replaced</span>
  <span m=''403100''>these</span> <span m=''403280''>three</span> <span m=''403400''>segments</span>
  <span m=''403800''>with</span> <span m=''403950''>a</span> <span m=''404020''>single</span>
  <span m=''404390''>segment</span> <span m=''405300''>which</span> <span m=''406060''>looks</span>
  <span m=''407300''>something</span> <span m=''407540''>like</span> <span m=''407730''>that.</span>
  <span m=''410880''>And</span> <span m=''411030''>the</span> <span m=''411140''>rest,</span>
  <span m=''412580''>the</span> <span m=''412680''>parts</span> <span m=''413000''>to</span>
  <span m=''413100''>the</span> <span m=''413180''>left</span> <span m=''413500''>and</span>
  <span m=''413600''>to</span> <span m=''413690''>the</span> <span m=''413810''>right</span>
  <span m=''414050''>are</span> <span m=''414150''>the</span> <span m=''414270''>same.</span>
  <span m=''415290''>I</span> <span m=''415420''>still</span> <span m=''415620''>claim</span>
  <span m=''415850''>we</span> <span m=''415930''>need</span> <span m=''416110''>to</span>
  <span m=''416180''>back</span> <span m=''416510''>up</span> <span m=''416660''>one</span>
  <span m=''416810''>segment</span> <span m=''417150''>and</span> <span m=''417180''>look</span>
  <span m=''417420''>at</span> <span m=''417560''>this</span> <span m=''417740''>one</span>
  <span m=''417920''>again,</span> <span m=''418910''>because</span> <span m=''419250''>now</span>
  <span m=''419540''>potentially</span> <span m=''420160''>this</span> <span m=''420480''>one</span>
  <span m=''420650''>might</span> <span m=''420880''>be</span> <span m=''421020''>crimpable</span>
  <span m=''422010''>whereas</span> <span m=''422290''>it</span> <span m=''422380''>wasn''t</span>
  <span m=''422700''>before.</span> <span m=''423190''>Because</span> <span m=''423490''>we</span>
  <span m=''423590''>changed</span> <span m=''423890''>this</span> <span m=''424040''>length,</span>
  <span m=''424430''>it</span> <span m=''424660''>may</span> <span m=''424850''>have</span>
  <span m=''424990''>gotten</span> <span m=''425860''>longer</span> <span m=''426430''>potentially.</span>
  <span m=''428090''>Or</span> <span m=''428210''>shorter.</span> <span m=''429370''>It</span>
  <span m=''429590''>could</span> <span m=''429730''>have</span> <span m=''429810''>changed.</span>
  <span m=''430330''>So</span> <span m=''430890''>this</span> <span m=''431190''>pair</span>
  <span m=''431460''>may be</span> <span m=''431730''>crimpable</span> <span m=''432240''>whereas</span>
  <span m=''432500''>it</span> <span m=''432590''>wasn''t</span> <span m=''432900''>before.</span>
  <span m=''433910''>So</span> <span m=''434050''>just</span> <span m=''434300''>to</span>
  <span m=''434560''>make</span> <span m=''434770''>sure,</span> <span m=''435560''>we''ll</span>
  <span m=''435730''>go</span> <span m=''436040''>left</span> <span m=''436340''>one</span>
  <span m=''436580''>step,</span> <span m=''437265''>and then</span> <span m=''437550''>we''ll</span>
  <span m=''437880''>check,</span> <span m=''438130''>is</span> <span m=''438340''>that</span>
  <span m=''438550''>segment</span> <span m=''438840''>crimpable?</span> <span m=''439530''>Is</span>
  <span m=''439660''>this</span> <span m=''439840''>one?</span> <span m=''440080''>Is</span>
  <span m=''440190''>this</span> <span m=''440370''>one?</span> <span m=''440950''>And</span>
  <span m=''441090''>just</span> <span m=''441240''>keep</span> <span m=''441410''>going.</span>
  </p><p><span m=''442700''>And</span> <span m=''443150''>I''m</span> <span m=''443380''>guessing</span>
  <span m=''443750''>this</span> <span m=''443920''>pattern</span> <span m=''444270''>is</span>
  <span m=''444370''>not</span> <span m=''446100''>is</span> <span m=''446280''>not</span>
  <span m=''446640''>flat</span> <span m=''446905''>foldable</span> <span m=''447360''>because</span>
  <span m=''447660''>of</span> <span m=''447750''>these</span> <span m=''447990''>two.</span>
  <span m=''448780''>We</span> <span m=''448920''>could</span> <span m=''449100''>check.</span>
  <span m=''452025''>Did</span> <span m=''452510''>I miss</span> <span m=''452890''>one?</span>
  <span m=''454350''>V,</span> <span m=''455080''>M,</span> <span m=''456316''>M.</span>
  <span m=''457050''>M</span> <span m=''457280''>is the</span> <span m=''457500''>little</span>
  <span m=''457780''>thing.</span> <span m=''460260''>So</span> <span m=''460410''>I</span>
  <span m=''460490''>think</span> <span m=''460670''>this</span> <span m=''460830''>is</span>
  <span m=''460940''>going</span> <span m=''461060''>to</span> <span m=''461140''>crimp.</span>
  <span m=''461960''>And</span> <span m=''462100''>then</span> <span m=''462220''>this</span>
  <span m=''462360''>will</span> <span m=''462440''>get</span> <span m=''462620''>end</span>
  <span m=''462820''>folded.</span> <span m=''463220''>But</span> <span m=''463390''>still</span>
  <span m=''464840''>this</span> <span m=''465080''>is</span> <span m=''465180''>a</span>
  <span m=''465250''>problem</span> <span m=''465720''>because</span> <span m=''465950''>of</span>
  <span m=''466050''>the</span> <span m=''466150''>two</span> <span m=''466340''>M''s.</span>
  <span m=''467580''>So</span> <span m=''468050''>this</span> <span m=''468210''>will</span>
  <span m=''468310''>not</span> <span m=''468540''>flat</span> <span m=''468790''>fold.</span>
  <span m=''469250''>We''ll</span> <span m=''469390''>be</span> <span m=''469520''>left</span>
  <span m=''469850''>with</span> <span m=''470530''>something</span> <span m=''470900''>like</span>
  <span m=''471100''>this,</span> <span m=''471400''>which</span> <span m=''471450''>is</span>
  <span m=''471560''>the</span> <span m=''471680''>two</span> <span m=''471900''>M''s</span>
  <span m=''472840''>and</span> <span m=''473040''>then</span> <span m=''473210''>we</span>
  <span m=''473310''>say,</span> <span m=''473510''>oh.</span> <span m=''474820''>We''ll</span>
  <span m=''475010''>reach</span> <span m=''475180''>the</span> <span m=''475280''>stop</span>
  <span m=''475620''>case.</span> <span m=''475960''>Can''t</span> <span m=''476240''>find</span>
  <span m=''476470''>a</span> <span m=''476530''>crimp</span> <span m=''476770''>or
  and</span> <span m=''476930''>end fold</span> <span m=''477570''>and</span> <span
  m=''477680''>there are</span> <span m=''477800''>still</span> <span m=''477990''>creases</span>
  <span m=''478360''>left.</span> <span m=''478680''>And</span> <span m=''478800''>so</span>
  <span m=''478960''>we</span> <span m=''479060''>know</span> <span m=''479770''>that</span>
  <span m=''479890''>we''re</span> <span m=''480000''>not</span> <span m=''481335''>flat</span>
  <span m=''481780''>foldable.</span> </p><p><span m=''483480''>But</span> <span m=''483660''>the</span>
  <span m=''484470''>reason</span> <span m=''485560''>I''m</span> <span m=''485670''>doing</span>
  <span m=''485970''>this</span> <span m=''486420''>fast</span> <span m=''488090''>resume</span>
  <span m=''488660''>of</span> <span m=''488850''>the</span> <span m=''488940''>search,</span>
  <span m=''489970''>continuing</span> <span m=''490390''>the</span> <span m=''490470''>search</span>
  <span m=''490760''>from</span> <span m=''490980''>one</span> <span m=''491170''>step</span>
  <span m=''491890''>to</span> <span m=''492070''>the</span> <span m=''492120''>left,</span>
  <span m=''492900''>is</span> <span m=''493090''>because</span> <span m=''493270''>we</span>
  <span m=''493390''>get</span> <span m=''493950''>a</span> <span m=''494070''>good</span>
  <span m=''494240''>running</span> <span m=''494510''>time.</span> <span m=''499870''>I''m</span>
  <span m=''500360''>going to</span> <span m=''500860''>use</span> <span m=''501140''>running</span>
  <span m=''501420''>time</span> <span m=''501670''>notation</span> <span m=''501980''>of</span>
  <span m=''502290''>order</span> <span m=''502610''>n.</span> <span m=''502850''>This</span>
  <span m=''503000''>means</span> <span m=''503200''>some</span> <span m=''503400''>constant</span>
  <span m=''503860''>times</span> <span m=''504180''>n.</span> <span m=''505570''>We</span>
  <span m=''505710''>don''t</span> <span m=''505830''>really</span> <span m=''506020''>care</span>
  <span m=''506210''>what</span> <span m=''506310''>the</span> <span m=''506380''>constant</span>
  <span m=''506750''>is,</span> <span m=''506980''>but</span> <span m=''507160''>the</span>
  <span m=''507250''>growth</span> <span m=''507500''>is</span> <span m=''507630''>linear</span>
  <span m=''508500''>in</span> <span m=''508670''>the</span> <span m=''508750''>number</span>
  <span m=''509070''>of</span> <span m=''509140''>creases</span> <span m=''509620''>that''s</span>
  <span m=''509850''>n.</span> <span m=''510930''>And</span> <span m=''511130''>the</span>
  <span m=''511200''>reason</span> <span m=''511490''>it''s</span> <span m=''511620''>linear</span>
  <span m=''512770''>is</span> <span m=''513039''>that</span> <span m=''513350''>the</span>
  <span m=''517669''>number</span> <span m=''517980''>of</span> <span m=''518100''>rightward</span>
  <span m=''518510''>steps</span> <span m=''518880''>that</span> <span m=''519000''>we</span>
  <span m=''519120''>make</span> <span m=''522980''>is</span> <span m=''523320''>going</span>
  <span m=''523460''>to</span> <span m=''523520''>be</span> <span m=''523650''>equal</span>
  <span m=''523970''>to</span> <span m=''524260''>n</span> <span m=''524490''>plus</span>
  <span m=''524840''>the</span> <span m=''524930''>number</span> <span m=''525310''>of</span>
  <span m=''525410''>leftward</span> <span m=''525810''>steps.</span> </p><p><span
  m=''531140''>Why is</span> <span m=''531380''>that?</span> <span m=''531730''>Because</span>
  <span m=''532790''>overall</span> <span m=''533230''>the</span> <span m=''533300''>search</span>
  <span m=''533600''>is</span> <span m=''533700''>going</span> <span m=''533970''>left</span>
  <span m=''534210''>to</span> <span m=''534320''>right,</span> <span m=''534780''>and</span>
  <span m=''534880''>if</span> <span m=''534980''>it</span> <span m=''535080''>doesn''t</span>
  <span m=''535190''>find</span> <span m=''535380''>anything</span> <span m=''535730''>it</span>
  <span m=''535950''>just</span> <span m=''536160''>takes</span> <span m=''536390''>n</span>
  <span m=''536610''>steps.</span> <span m=''536900''>You</span> <span m=''537030''>look</span>
  <span m=''537210''>at</span> <span m=''537250''>all</span> <span m=''537420''>the</span>
  <span m=''537510''>creases</span> <span m=''537920''>or</span> <span m=''538030''>all</span>
  <span m=''538120''>the</span> <span m=''538200''>segments.</span> <span m=''538525''>It''s</span>
  <span m=''538850''>basically</span> <span m=''539755''>n,</span> <span m=''540440''>n</span>
  <span m=''540590''>plus</span> <span m=''540820''>1,</span> <span m=''541100''>whatever.</span>
  <span m=''542850''>For each</span> <span m=''543070''>one, you</span> <span m=''543420''>check</span>
  <span m=''543690''>is</span> <span m=''543810''>it</span> <span m=''543890''>crimpable,</span>
  <span m=''544390''>end</span> <span m=''544550''>foldable.</span> <span m=''545030''>That</span>
  <span m=''545200''>takes</span> <span m=''545420''>constant</span> <span m=''545780''>time.</span>
  <span m=''546040''>You''re just</span> <span m=''546220''>comparing</span> <span
  m=''546650''>a</span> <span m=''546700''>couple</span> <span m=''546970''>of</span>
  <span m=''547070''>numbers.</span> <span m=''549130''>So</span> <span m=''549780''>I''m</span>
  <span m=''549880''>counting</span> <span m=''550050''>the</span> <span m=''550230''>number
  of</span> <span m=''550500''>rightward</span> <span m=''550800''>steps.</span> <span
  m=''551820''>The</span> <span m=''552040''>trouble</span> <span m=''552460''>with</span>
  <span m=''552630''>the</span> <span m=''552720''>search</span> <span m=''553110''>is</span>
  <span m=''553290''>that</span> <span m=''553450''>every</span> <span m=''553710''>time</span>
  <span m=''554010''>I</span> <span m=''554090''>find</span> <span m=''554410''>a</span>
  <span m=''554450''>fold</span> <span m=''554750''>to</span> <span m=''554870''>do</span>
  <span m=''555150''>I</span> <span m=''555300''>go</span> <span m=''555600''>back</span>
  <span m=''555930''>one</span> <span m=''556140''>step</span> <span m=''556950''>and</span>
  <span m=''557130''>so</span> <span m=''557320''>I''m</span> <span m=''557570''>kind</span>
  <span m=''557750''>of</span> <span m=''557820''>losing</span> <span m=''558200''>progress</span>
  <span m=''558700''>because</span> <span m=''558880''>I</span> <span m=''558950''>go</span>
  <span m=''559120''>backwards.</span> <span m=''559800''>There''s</span> <span m=''560290''>actually</span>
  <span m=''560580''>two</span> <span m=''560750''>reasons</span> <span m=''561090''>why</span>
  <span m=''561240''>that''s</span> <span m=''561510''>OK.</span> <span m=''561860''>One</span>
  <span m=''562110''>is</span> <span m=''562250''>you''re</span> <span m=''562560''>also</span>
  <span m=''562940''>decreasing</span> <span m=''563510''>n</span> <span m=''563730''>at</span>
  <span m=''563810''>the</span> <span m=''563910''>same</span> <span m=''564150''>time,</span>
  <span m=''565270''>because</span> <span m=''565520''>you''re</span> <span m=''565690''>replacing</span>
  <span m=''566050''>3</span> <span m=''566270''>things</span> <span m=''566540''>with</span>
  <span m=''566680''>1</span> <span m=''566920''>thing,</span> <span m=''568090''>so</span>
  <span m=''568250''>n</span> <span m=''568430''>goes</span> <span m=''568590''>down</span>
  <span m=''568750''>by</span> <span m=''568880''>2.</span> <span m=''569510''>But</span>
  <span m=''569650''>also,</span> <span m=''575390''>in</span> <span m=''575550''>order</span>
  <span m=''575660''>to</span> <span m=''575750''>make</span> <span m=''575920''>a</span>
  <span m=''575970''>rightward</span> <span m=''576280''>step</span> <span m=''576740''>either</span>
  <span m=''577710''>it''s</span> <span m=''577950''>in</span> <span m=''578080''>the</span>
  <span m=''578220''>full</span> <span m=''578520''>search</span> <span m=''579160''>or</span>
  <span m=''579480''>it''s</span> <span m=''579600''>because</span> <span m=''579900''>you</span>
  <span m=''580000''>went</span> <span m=''580170''>back</span> <span m=''580430''>one</span>
  <span m=''580590''>and you</span> <span m=''580650''>have</span> <span m=''580860''>to</span>
  <span m=''580950''>go</span> <span m=''581050''>right</span> <span m=''581290''>again.</span>
  <span m=''582010''>So</span> <span m=''582140''>this</span> <span m=''582340''>is</span>
  <span m=''582460''>true.</span> <span m=''583630''>And</span> <span m=''583750''>the</span>
  <span m=''583830''>point</span> <span m=''584030''>is</span> <span m=''584160''>the</span>
  <span m=''584280''>number</span> <span m=''584550''>of</span> <span m=''584600''>leftward</span>
  <span m=''585020''>steps</span> <span m=''585950''>is</span> <span m=''586170''>also</span>
  <span m=''587440''>at</span> <span m=''587630''>most</span> <span m=''587980''>n,</span>
  <span m=''589050''>because</span> <span m=''589480''>every</span> <span m=''589760''>time</span>
  <span m=''590840''>you</span> <span m=''590970''>do</span> <span m=''591120''>a</span>
  <span m=''591170''>leftward</span> <span m=''591500''>step</span> <span m=''591800''>you</span>
  <span m=''591880''>did</span> <span m=''592040''>a</span> <span m=''592090''>fold,</span>
  <span m=''592670''>and</span> <span m=''592890''>there''s</span> <span m=''593040''>only</span>
  <span m=''593260''>n</span> <span m=''593280''>folds</span> <span m=''593630''>to</span>
  <span m=''593780''>make.</span> <span m=''594680''>So--</span> <span m=''595800''>it''s</span>
  <span m=''595910''>actually</span> <span m=''596240''>less,</span> <span m=''596520''>because</span>
  <span m=''596820''>crimps</span> <span m=''597560''>do</span> <span m=''597710''>two</span>
  <span m=''597890''>at</span> <span m=''597960''>a</span> <span m=''598040''>time.</span>
  <span m=''598360''>But</span> <span m=''599100''>the</span> <span m=''599200''>point</span>
  <span m=''599420''>is</span> <span m=''599540''>this</span> <span m=''599720''>is</span>
  <span m=''599860''>at</span> <span m=''599950''>most</span> <span m=''600270''>2n.</span>
  <span m=''601641''>And</span> <span m=''602100''>so the</span> <span m=''602460''>number
  of</span> <span m=''602740''>rightward</span> <span m=''603010''>steps</span> <span
  m=''603230''>we</span> <span m=''603390''>make</span> <span m=''603610''>is</span>
  <span m=''603730''>linear.</span> <span m=''604250''>And</span> <span m=''604470''>so</span>
  <span m=''604620''>the</span> <span m=''604680''>overall</span> <span m=''604960''>running</span>
  <span m=''605240''>time</span> <span m=''605490''>is</span> <span m=''605610''>linear.</span>
  <span m=''607400''>For</span> <span m=''607530''>the</span> <span m=''607630''>algorithms</span>
  <span m=''608000''>people,</span> <span m=''608330''>this</span> <span m=''608550''>is</span>
  <span m=''609170''>a</span> <span m=''609230''>very</span> <span m=''609380''>simple</span>
  <span m=''609750''>amortization</span> <span m=''610470''>argument.</span> <span
  m=''610870''>We''re</span> <span m=''611000''>charging</span> <span m=''611410''>the</span>
  <span m=''611500''>leftward</span> <span m=''611880''>steps</span> <span m=''612250''>to</span>
  <span m=''612420''>the</span> <span m=''613210''>folds</span> <span m=''613520''>that</span>
  <span m=''613650''>we''re</span> <span m=''613750''>doing.</span> </p><p><span m=''615350''>So</span>
  <span m=''615530''>that''s</span> <span m=''615740''>an</span> <span m=''615820''>easy</span>
  <span m=''616070''>way</span> <span m=''616280''>to</span> <span m=''616450''>do</span>
  <span m=''617080''>1D</span> <span m=''617740''>flat</span> <span m=''618010''>foldability</span>
  <span m=''618550''>testing</span> <span m=''618960''>for</span> <span m=''619060''>mountain</span>
  <span m=''619300''>valley</span> <span m=''619550''>patterns.</span> </p><p><span
  m=''619940''>Yes?</span> </p><p><span m=''620900''>AUDIENCE: Why</span> <span m=''621330''>do
  you</span> <span m=''621470''>need</span> <span m=''621840''>to</span> <span m=''621930''>go</span>
  <span m=''622120''>back a</span> <span m=''622430''>step?</span> <span m=''623560''>So,</span>
  <span m=''623930''>the</span> <span m=''624250''>segment that</span> <span m=''624590''>you</span>
  <span m=''624770''>labelled</span> <span m=''625070''>x,</span> <span m=''625920''>its
  new</span> <span m=''626250''>length</span> <span m=''626980''>is</span> <span m=''627260''>x</span>
  <span m=''627760''>plus</span> <span m=''629310''>the</span> <span m=''629420''>quantity</span>
  <span m=''629820''>z</span> <span m=''630050''>minus</span> <span m=''630400''>y,</span>
  <span m=''630750''>and</span> <span m=''631000''>z</span> <span m=''631200''>is</span>
  <span m=''631320''>greater</span> <span m=''631570''>than</span> <span m=''631780''>y.</span>
  <span m=''632591''>So it''s</span> <span m=''633052''>x plus</span> <span m=''633513''>a
  positive</span> <span m=''634896''>number,</span> <span m=''635818''>right?</span>
  <span m=''636740''>So</span> <span m=''636930''>it''s</span> <span m=''638240''>only</span>
  <span m=''638460''>increasing</span> <span m=''638870''>in length,</span> <span
  m=''639830''>not</span> <span m=''640320''>decreasing.</span> </p><p><span m=''642110''>PROFESSOR:
  Only</span> <span m=''642350''>increasing.</span> <span m=''644020''>But</span>
  <span m=''644170''>that''s</span> <span m=''645550''>of</span> <span m=''645660''>interest,</span>
  <span m=''646110''>right?</span> <span m=''646340''>Because</span> <span m=''647060''>if</span>
  <span m=''647260''>you</span> <span m=''647410''>had</span> <span m=''647650''>something</span>
  <span m=''651030''>that</span> <span m=''651170''>wasn''t</span> <span m=''651460''>crimpable</span>
  <span m=''651910''>because</span> <span m=''652300''>this</span> <span m=''652470''>was</span>
  <span m=''652600''>too</span> <span m=''652770''>short,</span> <span m=''654860''>and</span>
  <span m=''655060''>then--</span> <span m=''656170''>OK,</span> <span m=''656470''>here''s</span>
  <span m=''656740''>an</span> <span m=''656790''>example.</span> <span m=''657780''>Good</span>
  <span m=''657930''>question.</span> <span m=''659100''>I</span> <span m=''659700''>hadn''t</span>
  <span m=''659950''>thoroughly</span> <span m=''660290''>checked.</span> <span m=''660560''>So</span>
  <span m=''661520''>we</span> <span m=''661650''>scan.</span> <span m=''662110''>This</span>
  <span m=''662290''>guy''s</span> <span m=''662490''>not</span> <span m=''662670''>crimpable</span>
  <span m=''663380''>because</span> <span m=''663840''>this</span> <span m=''664020''>guy''s</span>
  <span m=''664220''>too</span> <span m=''664350''>short.</span> <span m=''665250''>Then</span>
  <span m=''665550''>we</span> <span m=''665740''>reach--</span> <span m=''666800''>suppose</span>
  <span m=''667240''>then</span> <span m=''667420''>we</span> <span m=''667570''>jump</span>
  <span m=''667890''>to</span> <span m=''668040''>this</span> <span m=''668300''>guy.</span>
  <span m=''669050''>I''ll</span> <span m=''669320''>do</span> <span m=''669460''>valley</span>
  <span m=''669860''>mountain</span> <span m=''670250''>to</span> <span m=''670870''>make</span>
  <span m=''671040''>this</span> <span m=''671200''>definitely</span> <span m=''671480''>not</span>
  <span m=''671690''>crimpable.</span> <span m=''672300''>We</span> <span m=''672710''>look</span>
  <span m=''672970''>at</span> <span m=''673030''>this</span> <span m=''673210''>guy.</span>
  <span m=''673350''>We</span> <span m=''673510''>do</span> <span m=''673700''>the</span>
  <span m=''673820''>crimp.</span> <span m=''675110''>And</span> <span m=''675290''>now</span>
  <span m=''675590''>suddenly</span> <span m=''675980''>we</span> <span m=''676090''>have</span>
  <span m=''676280''>this</span> <span m=''676450''>nice</span> <span m=''676710''>big</span>
  <span m=''676900''>length.</span> <span m=''678710''>And</span> <span m=''678860''>so</span>
  <span m=''678980''>now</span> <span m=''679210''>this</span> <span m=''679580''>pair</span>
  <span m=''679875''>is</span> <span m=''680170''>crimpable.</span> <span m=''682256''>Good.</span>
  <span m=''682680''>So</span> <span m=''682880''>that''s</span> <span m=''683090''>why</span>
  <span m=''683220''>we</span> <span m=''683330''>need</span> <span m=''683500''>to</span>
  <span m=''683560''>go</span> <span m=''683700''>back</span> <span m=''683940''>a</span>
  <span m=''684000''>step.</span> <span m=''684240''>After</span> <span m=''684500''>we</span>
  <span m=''684600''>crimp</span> <span m=''684830''>this</span> <span m=''685020''>guy,</span>
  <span m=''685440''>this</span> <span m=''685690''>one</span> <span m=''685850''>becomes</span>
  <span m=''686230''>crimpable</span> <span m=''686990''>if it</span> <span m=''687210''>wasn''t</span>
  <span m=''687530''>before.</span> <span m=''688776''>Yeah.</span> <span m=''690700''>I</span>
  <span m=''690820''>could</span> <span m=''690980''>have</span> <span m=''691080''>easily</span>
  <span m=''691350''>believed that</span> <span m=''691690''>this</span> <span m=''691830''>step</span>
  <span m=''692040''>wasn''t</span> <span m=''692260''>necessary,</span> <span m=''692860''>but</span>
  <span m=''693000''>it</span> <span m=''693100''>definitely</span> <span m=''693350''>doesn''t</span>
  <span m=''693570''>hurt</span> <span m=''694070''>and</span> <span m=''694370''>it</span>
  <span m=''694470''>is</span> <span m=''694720''>indeed</span> <span m=''695020''>necessary.</span>
  <span m=''696760''>The</span> <span m=''697200''>key</span> <span m=''697410''>is</span>
  <span m=''697560''>that</span> <span m=''697640''>we</span> <span m=''697730''>don''t</span>
  <span m=''697860''>have</span> <span m=''697970''>to</span> <span m=''698080''>back</span>
  <span m=''698430''>up</span> <span m=''698530''>more</span> <span m=''698740''>than</span>
  <span m=''698870''>one</span> <span m=''699060''>step,</span> <span m=''699380''>because</span>
  <span m=''699670''>we''re</span> <span m=''700310''>only</span> <span m=''700560''>changing</span>
  <span m=''700920''>our</span> <span m=''701020''>neighbors,</span> <span m=''701620''>basically.</span>
  </p><p><span m=''703250''>Other</span> <span m=''703410''>questions</span> <span
  m=''703770''>about</span> <span m=''703980''>this</span> <span m=''704140''>algorithm?</span>
  </p><p><span m=''707240''>OK,</span> <span m=''707390''>well</span> <span m=''707550''>once</span>
  <span m=''707750''>we</span> <span m=''707830''>have</span> <span m=''708000''>this</span>
  <span m=''708210''>for--</span> <span m=''708830''>this</span> <span m=''709040''>is</span>
  <span m=''709150''>really</span> <span m=''709370''>for</span> <span m=''709520''>lecture</span>
  <span m=''709780''>two</span> <span m=''709960''>material,</span> <span m=''710440''>we</span>
  <span m=''710550''>can</span> <span m=''710710''>adapt</span> <span m=''711210''>it</span>
  <span m=''711410''>to</span> <span m=''711890''>lecture</span> <span m=''712230''>three</span>
  <span m=''712450''>material,</span> <span m=''713470''>which</span> <span m=''713640''>is</span>
  <span m=''713800''>the</span> <span m=''714000''>circular</span> <span m=''714470''>case.</span>
  <span m=''714910''>Instead</span> <span m=''715070''>of</span> <span m=''715150''>having</span>
  <span m=''715440''>a</span> <span m=''715500''>line</span> <span m=''715880''>we</span>
  <span m=''715960''>have</span> <span m=''716130''>a</span> <span m=''716180''>circle</span>
  <span m=''716530''>of</span> <span m=''716610''>paper.</span> <span m=''717540''>In</span>
  <span m=''717710''>that</span> <span m=''717870''>case,</span> <span m=''718230''>we</span>
  <span m=''718310''>only</span> <span m=''718550''>need</span> <span m=''718700''>to</span>
  <span m=''718810''>look</span> <span m=''718960''>for</span> <span m=''719100''>crimps,</span>
  <span m=''720110''>and</span> <span m=''720350''>so</span> <span m=''720660''>we</span>
  <span m=''720790''>do</span> <span m=''721010''>the</span> <span m=''721120''>same</span>
  <span m=''721420''>thing</span> <span m=''721690''>for</span> <span m=''721810''>crimps.</span>
  <span m=''727990''>I</span> <span m=''728010''>don''t</span> <span m=''728180''>think</span>
  <span m=''728360''>I</span> <span m=''728410''>really</span> <span m=''728650''>need</span>
  <span m=''728830''>to</span> <span m=''728950''>write</span> <span m=''729140''>this</span>
  <span m=''729310''>down,</span> <span m=''730310''>but</span> <span m=''733150''>algorithm</span>
  <span m=''734980''>for</span> <span m=''735320''>a</span> <span m=''735380''>single</span>
  <span m=''736200''>vertex</span> <span m=''738790''>mountain</span> <span m=''739200''>valley</span>
  <span m=''739630''>pattern.</span> <span m=''743960''>It''s</span> <span m=''744150''>basically</span>
  <span m=''744570''>the</span> <span m=''744640''>same</span> <span m=''744920''>algorithm.</span>
  <span m=''745710''>Instead</span> <span m=''746130''>of</span> <span m=''747300''>wherever</span>
  <span m=''747540''>you</span> <span m=''747660''>see</span> <span m=''747900''>left</span>
  <span m=''748450''>and</span> <span m=''748640''>right</span> <span m=''749040''>you</span>
  <span m=''749220''>replace</span> <span m=''749640''>it</span> <span m=''749750''>with</span>
  <span m=''750170''>clockwise</span> <span m=''750840''>and</span> <span m=''750940''>counterclockwise</span>
  <span m=''752050''>going</span> <span m=''752290''>around</span> <span m=''752540''>in</span>
  <span m=''752650''>a</span> <span m=''752710''>circle.</span> <span m=''754760''>There''s</span>
  <span m=''755010''>no</span> <span m=''755170''>obvious</span> <span m=''755460''>starting</span>
  <span m=''755750''>point</span> <span m=''755970''>you</span> <span m=''756040''>just</span>
  <span m=''756170''>start at an</span> <span m=''756580''>arbitrary</span> <span
  m=''757340''>segment,</span> <span m=''757830''>which</span> <span m=''758030''>in</span>
  <span m=''758100''>this</span> <span m=''758240''>case</span> <span m=''758440''>is</span>
  <span m=''758550''>an</span> <span m=''758660''>angle</span> <span m=''759480''>of</span>
  <span m=''760110''>the</span> <span m=''760470''>crease</span> <span m=''760800''>pattern.</span>
  <span m=''761160''>Maybe</span> <span m=''761400''>I should</span> <span m=''761610''>draw</span>
  <span m=''762772''>a little</span> <span m=''763200''>crease</span> <span m=''763500''>pattern,</span>
  <span m=''763770''>just for</span> <span m=''765516''>a</span> <span m=''766010''>picture.</span>
  </p><p><span m=''768990''>So</span> <span m=''769120''>you</span> <span m=''769200''>start,</span>
  <span m=''769500''>let''s</span> <span m=''769670''>say, at</span> <span m=''769800''>this</span>
  <span m=''770050''>segment.</span> <span m=''770510''>You</span> <span m=''770610''>see</span>
  <span m=''770930''>is</span> <span m=''771340''>this</span> <span m=''771550''>pair</span>
  <span m=''771850''>crimpable.</span> <span m=''773010''>If</span> <span m=''773210''>not</span>
  <span m=''773550''>continue,</span> <span m=''774140''>let''s say,</span> <span
  m=''774370''>clockwise.</span> <span m=''776670''>Keep</span> <span m=''776910''>going.</span>
  <span m=''777950''>If</span> <span m=''778010''>you</span> <span m=''778120''>ever</span>
  <span m=''778310''>find</span> <span m=''778570''>a</span> <span m=''778630''>crimpable</span>
  <span m=''779070''>pair,</span> <span m=''779330''>like</span> <span m=''779540''>these</span>
  <span m=''780100''>two</span> <span m=''780210''>guys--</span> <span m=''780500''>maybe</span>
  <span m=''780720''>this</span> <span m=''780880''>is</span> <span m=''780960''>mountain</span>
  <span m=''781270''>and</span> <span m=''781370''>valley</span> <span m=''781810''>and</span>
  <span m=''781900''>this</span> <span m=''782050''>is</span> <span m=''782150''>a</span>
  <span m=''782220''>locally</span> <span m=''782570''>smallest</span> <span m=''783040''>angle--</span>
  <span m=''783940''>you</span> <span m=''784090''>do</span> <span m=''784280''>the</span>
  <span m=''784400''>crimp,</span> <span m=''784810''>meaning</span> <span m=''785050''>you</span>
  <span m=''785150''>replace</span> <span m=''785680''>this</span> <span m=''786710''>angle</span>
  <span m=''787140''>x</span> <span m=''787500''>y</span> <span m=''788360''>and</span>
  <span m=''788580''>z</span> <span m=''789320''>with</span> <span m=''789790''>x</span>
  <span m=''790090''>minus</span> <span m=''790410''>y</span> <span m=''790600''>plus</span>
  <span m=''790980''>z,</span> <span m=''791750''>just</span> <span m=''791980''>as</span>
  <span m=''792120''>before.</span> <span m=''793610''>And</span> <span m=''793690''>then</span>
  <span m=''793830''>you</span> <span m=''793950''>step</span> <span m=''794800''>counterclockwise</span>
  <span m=''795680''>one</span> <span m=''795950''>step.</span> <span m=''797270''>And</span>
  <span m=''797470''>the</span> <span m=''797540''>point</span> <span m=''797740''>is</span>
  <span m=''798030''>the</span> <span m=''798300''>invariant</span> <span m=''798960''>you''re</span>
  <span m=''799040''>maintaining</span> <span m=''799600''>at</span> <span m=''799700''>all</span>
  <span m=''799950''>times</span> <span m=''800300''>during</span> <span m=''800500''>this</span>
  <span m=''800650''>algorithm,</span> <span m=''801070''>the</span> <span m=''801230''>interval</span>
  <span m=''803365''>of the</span> <span m=''803630''>segments</span> <span m=''804360''>from</span>
  <span m=''804790''>the</span> <span m=''804910''>very</span> <span m=''805140''>first</span>
  <span m=''805420''>segment</span> <span m=''805740''>you</span> <span m=''805870''>went</span>
  <span m=''806070''>to,</span> <span m=''806950''>up</span> <span m=''807160''>to</span>
  <span m=''807330''>but</span> <span m=''807460''>not</span> <span m=''807640''>including</span>
  <span m=''808060''>the</span> <span m=''808150''>segment</span> <span m=''808480''>you''re</span>
  <span m=''808620''>currently</span> <span m=''809010''>looking</span> <span m=''809380''>at,</span>
  <span m=''810030''>those</span> <span m=''810310''>are</span> <span m=''810400''>all</span>
  <span m=''810630''>guaranteed</span> <span m=''811160''>not</span> <span m=''811450''>crimpable</span>
  <span m=''811920''>at</span> <span m=''812100''>the</span> <span m=''812180''>moment.</span>
  <span m=''813160''>And</span> <span m=''813320''>so</span> <span m=''813480''>when</span>
  <span m=''813590''>you</span> <span m=''813700''>do</span> <span m=''813880''>a</span>
  <span m=''813950''>crimp,</span> <span m=''814500''>that</span> <span m=''814740''>may</span>
  <span m=''814910''>invalidate</span> <span m=''815600''>this</span> <span m=''815770''>one,
  and so</span> <span m=''816080''>you</span> <span m=''816170''>have</span> <span
  m=''816260''>to</span> <span m=''816360''>step</span> <span m=''816620''>backwards</span>
  <span m=''817020''>because</span> <span m=''817180''>you''re</span> <span m=''817310''>not</span>
  <span m=''817480''>sure</span> <span m=''817640''>whether</span> <span m=''817870''>that</span>
  <span m=''818040''>one''s</span> <span m=''818230''>crimpable</span> <span m=''818670''>anymore.</span>
  <span m=''819390''>But</span> <span m=''819560''>you</span> <span m=''819660''>maintain</span>
  <span m=''820010''>that</span> <span m=''820150''>invariant.</span> <span m=''820590''>And</span>
  <span m=''820710''>so</span> <span m=''821070''>when</span> <span m=''821800''>if</span>
  <span m=''821960''>you</span> <span m=''822200''>ever</span> <span m=''822450''>get</span>
  <span m=''822690''>back</span> <span m=''822990''>to</span> <span m=''825360''>the</span>
  <span m=''825470''>original</span> <span m=''826010''>angle that</span> <span m=''826380''>you
  were</span> <span m=''826610''>considering,</span> <span m=''827525''>the</span>
  <span m=''827800''>original</span> <span m=''828100''>segment,</span> <span m=''829440''>then</span>
  <span m=''829660''>you know that</span> <span m=''830160''>in</span> <span m=''830270''>fact</span>
  <span m=''830560''>everything</span> <span m=''831030''>is</span> <span m=''831160''>not</span>
  <span m=''831430''>crimpable,</span> <span m=''832270''>and</span> <span m=''832490''>then</span>
  <span m=''832920''>you''re</span> <span m=''833120''>in</span> <span m=''833180''>trouble.</span>
  <span m=''834190''>Maybe.</span> </p><p><span m=''835360''>Except</span> <span m=''835760''>for</span>
  <span m=''835870''>this</span> <span m=''836070''>issue</span> <span m=''836350''>which</span>
  <span m=''836550''>I</span> <span m=''836750''>also</span> <span m=''837000''>forgot</span>
  <span m=''837250''>about</span> <span m=''837440''>in</span> <span m=''837520''>lecture</span>
  <span m=''837850''>three--</span> <span m=''839240''>I mean,</span> <span m=''839410''>I
  didn''t</span> <span m=''839690''>forget</span> <span m=''839930''>about</span>
  <span m=''840180''>this</span> <span m=''840330''>time,</span> <span m=''840590''>but
  I</span> <span m=''840740''>forgot</span> <span m=''841100''>about</span> <span
  m=''841310''>it</span> <span m=''841430''>then--</span> <span m=''842000''>which</span>
  <span m=''842250''>is</span> <span m=''842370''>in</span> <span m=''842520''>the</span>
  <span m=''842600''>base</span> <span m=''842870''>case.</span> <span m=''846040''>You</span>
  <span m=''846230''>can</span> <span m=''846370''>never</span> <span m=''846740''>actually</span>
  <span m=''847410''>do</span> <span m=''847560''>everything</span> <span m=''847950''>by</span>
  <span m=''848060''>crimping,</span> <span m=''848900''>because</span> <span m=''849110''>at</span>
  <span m=''849210''>the</span> <span m=''849300''>very</span> <span m=''849570''>end</span>
  <span m=''850140''>your</span> <span m=''850450''>hope</span> <span m=''851230''>is</span>
  <span m=''851430''>that</span> <span m=''851510''>you</span> <span m=''851620''>have</span>
  <span m=''851840''>a</span> <span m=''851910''>cone</span> <span m=''852960''>with</span>
  <span m=''853480''>two</span> <span m=''853670''>creases</span> <span m=''854330''>that</span>
  <span m=''854440''>are</span> <span m=''854520''>both</span> <span m=''854800''>the</span>
  <span m=''854890''>same</span> <span m=''855200''>orientation.</span> <span m=''858740''>That</span>
  <span m=''858920''>is</span> <span m=''859010''>your</span> <span m=''859150''>goal.</span>
  <span m=''859820''>You</span> <span m=''859930''>know</span> <span m=''860110''>that</span>
  <span m=''860260''>there''s</span> <span m=''860540''>two</span> <span m=''860740''>more</span>
  <span m=''860980''>mountains</span> <span m=''861350''>or</span> <span m=''861430''>two</span>
  <span m=''861580''>more</span> <span m=''861740''>valleys</span> <span m=''862220''>and</span>
  <span m=''862420''>crimps</span> <span m=''862960''>pair</span> <span m=''863130''>them</span>
  <span m=''863280''>up.</span> <span m=''863870''>So</span> <span m=''864380''>you</span>
  <span m=''864830''>hope</span> <span m=''865140''>that</span> <span m=''865330''>you</span>
  <span m=''865470''>end</span> <span m=''865610''>up</span> <span m=''865760''>with</span>
  <span m=''865870''>the</span> <span m=''865970''>situation.</span> <span m=''866900''>If</span>
  <span m=''867060''>you</span> <span m=''867150''>do,</span> <span m=''868490''>and</span>
  <span m=''868650''>these</span> <span m=''868840''>two</span> <span m=''869010''>angles</span>
  <span m=''869310''>are</span> <span m=''869420''>equal,</span> <span m=''871000''>then</span>
  <span m=''871600''>you''re</span> <span m=''871700''>flat</span> <span m=''871960''>foldable.</span>
  <span m=''872640''>You</span> <span m=''872730''>have</span> <span m=''872850''>that</span>
  <span m=''873030''>one</span> <span m=''873230''>last</span> <span m=''873560''>fold</span>
  <span m=''873800''>to</span> <span m=''873880''>make.</span> <span m=''875650''>Otherwise,</span>
  <span m=''876780''>if</span> <span m=''876910''>you</span> <span m=''876980''>have</span>
  <span m=''877080''>anything</span> <span m=''877430''>else,</span> <span m=''878110''>you''re</span>
  <span m=''878230''>not</span> <span m=''878410''>flat</span> <span m=''878610''>foldable.</span>
  <span m=''879140''>That''s</span> <span m=''879420''>what</span> <span m=''879600''>we</span>
  <span m=''879780''>proved in</span> <span m=''880200''>lecture</span> <span m=''880540''>three,</span>
  <span m=''880770''>is</span> <span m=''880930''>that</span> <span m=''881010''>crimps</span>
  <span m=''881220''>are</span> <span m=''881380''>enough</span> <span m=''881580''>to</span>
  <span m=''881710''>get</span> <span m=''881860''>down</span> <span m=''882050''>to</span>
  <span m=''882130''>this</span> <span m=''882230''>situation</span> <span m=''882920''>where</span>
  <span m=''883250''>you</span> <span m=''883440''>have</span> <span m=''883620''>only</span>
  <span m=''883810''>two</span> <span m=''883950''>creases</span> <span m=''884330''>left,</span>
  <span m=''884650''>and</span> <span m=''884750''>that''s</span> <span m=''885650''>what''s</span>
  <span m=''885870''>foldable</span> <span m=''886250''>when</span> <span m=''886360''>you</span>
  <span m=''886480''>only</span> <span m=''886610''>have</span> <span m=''886780''>two</span>
  <span m=''886940''>creases.</span> </p><p><span m=''888840''>OK</span> <span m=''889000''>so</span>
  <span m=''889280''>this</span> <span m=''889700''>is</span> <span m=''889780''>becoming</span>
  <span m=''890210''>a</span> <span m=''890290''>cone as soon</span> <span m=''890840''>as</span>
  <span m=''890940''>you</span> <span m=''891030''>do</span> <span m=''891170''>operations.</span>
  <span m=''891750''>It''s</span> <span m=''891900''>just</span> <span m=''892110''>like</span>
  <span m=''892350''>the</span> <span m=''893020''>analysis</span> <span m=''893530''>we</span>
  <span m=''893620''>did.</span> <span m=''895040''>But</span> <span m=''895270''>this</span>
  <span m=''896010''>algorithm</span> <span m=''896390''>will</span> <span m=''896520''>run</span>
  <span m=''896680''>in</span> <span m=''896770''>linear</span> <span m=''897050''>time</span>
  <span m=''897330''>for</span> <span m=''897420''>the</span> <span m=''897530''>same</span>
  <span m=''897770''>reason.</span> <span m=''898090''>The</span> <span m=''898200''>number</span>
  <span m=''898500''>of</span> <span m=''898600''>clockwise</span> <span m=''899000''>steps</span>
  <span m=''899290''>equals</span> <span m=''900420''>at</span> <span m=''900510''>most</span>
  <span m=''900770''>n</span> <span m=''901020''>plus</span> <span m=''901400''>the</span>
  <span m=''901490''>number</span> <span m=''901860''>of</span> <span m=''902280''>counterclockwise</span>
  <span m=''902910''>steps.</span> <span m=''904100''>And</span> <span m=''904300''>so</span>
  <span m=''905106''>I</span> <span m=''905592''>guess I</span> <span m=''906080''>should</span>
  <span m=''906240''>maybe</span> <span m=''906590''>write</span> <span m=''906770''>"at</span>
  <span m=''907020''>most."</span> <span m=''908670''>And</span> <span m=''908830''>so</span>
  <span m=''909010''>this is</span> <span m=''909180''>linear</span> <span m=''909480''>time</span>
  <span m=''909750''>as</span> <span m=''909850''>well.</span> <span m=''910860''>Any</span>
  <span m=''911020''>questions</span> <span m=''911430''>about</span> <span m=''911680''>those</span>
  <span m=''911870''>algorithms?</span> </p><p><span m=''915080''>Yeah.</span> </p><p><span
  m=''915445''>AUDIENCE: For the</span> <span m=''915810''>simple</span> <span m=''916202''>one,</span>
  <span m=''916594''>could you</span> <span m=''916986''>run into</span> <span m=''917380''>some</span>
  <span m=''917580''>edge</span> <span m=''917800''>case</span> <span m=''918290''>where</span>
  <span m=''918990''>the</span> <span m=''919130''>very</span> <span m=''919510''>last</span>
  <span m=''919800''>crimp</span> <span m=''920360''>you</span> <span m=''920700''>considered</span>
  <span m=''921490''>makes</span> <span m=''922050''>the</span> <span m=''922350''>very</span>
  <span m=''922620''>first</span> <span m=''923300''>one,</span> <span m=''924160''>which</span>
  <span m=''924530''>wasn''t</span> <span m=''924900''>crimpable,</span> <span m=''925260''>crimpable</span>
  <span m=''925620''>and then</span> <span m=''925760''>you have</span> <span m=''926220''>to
  go around</span> <span m=''926600''>the</span> <span m=''926670''>circle</span>
  <span m=''927770''>again?</span> </p><p><span m=''929174''>PROFESSOR: Ah.</span>
  <span m=''930380''>OK.</span> <span m=''930670''>Good</span> <span m=''930850''>question.</span>
  <span m=''934820''>Right.</span> <span m=''935050''>So</span> <span m=''935170''>we</span>
  <span m=''935260''>said,</span> <span m=''935510''>OK,</span> <span m=''935740''>this</span>
  <span m=''935960''>is</span> <span m=''936090''>guaranteed</span> <span m=''936550''>not</span>
  <span m=''936770''>crimpable,</span> <span m=''937780''>but</span> <span m=''937980''>if</span>
  <span m=''938080''>you</span> <span m=''938210''>then</span> <span m=''938460''>crimp</span>
  <span m=''939000''>the</span> <span m=''939090''>very</span> <span m=''939450''>last</span>
  <span m=''939820''>segment</span> <span m=''941530''>this</span> <span m=''941730''>one</span>
  <span m=''941870''>may</span> <span m=''942010''>become</span> <span m=''942340''>crimpable,</span>
  <span m=''943920''>and</span> <span m=''944130''>then</span> <span m=''944310''>that</span>
  <span m=''944540''>may</span> <span m=''944680''>propagate</span> <span m=''945570''>and
  force you</span> <span m=''945830''>to go around</span> <span m=''946420''>a</span>
  <span m=''946500''>second</span> <span m=''946820''>time.</span> </p><p><span m=''948020''>AUDIENCE:
  So</span> <span m=''948370''>if</span> <span m=''948510''>that</span> <span m=''948670''>happens</span>
  <span m=''949040''>at</span> <span m=''949190''>each</span> <span m=''949570''>step,</span>
  <span m=''949660''>then</span> <span m=''950050''>at</span> <span m=''950180''>each</span>
  <span m=''950440''>step</span> <span m=''950630''>you</span> <span m=''950730''>go
  all the way</span> <span m=''951060''>around,</span> <span m=''951710''>and it</span>
  <span m=''951980''>could</span> <span m=''952250''>become</span> <span m=''952903''>quadratic.</span>
  </p><p><span m=''953306''>PROFESSOR: Ooh, interesting.</span> </p><p><span m=''953710''>AUDIENCE:
  But</span> <span m=''953995''>I''m not sure</span> <span m=''954280''>if it''s</span>
  <span m=''954610''>possible</span> <span m=''954950''>for that</span> <span m=''955290''>to</span>
  <span m=''955360''>happen</span> <span m=''955790''>every</span> <span m=''956262''>step.</span>
  </p><p><span m=''960510''>PROFESSOR: Good.</span> <span m=''960740''>Well,</span>
  <span m=''960970''>this</span> <span m=''961210''>is</span> <span m=''961350''>the</span>
  <span m=''961460''>nature of</span> <span m=''961770''>new</span> <span m=''961920''>algorithms.</span>
  <span m=''962970''>Yeah.</span> </p><p><span m=''963420''>AUDIENCE: The</span> <span
  m=''963890''>set</span> <span m=''964200''>of</span> <span m=''966465''>possibly</span>
  <span m=''966850''>crimpable</span> <span m=''967580''>things</span> <span m=''968180''>increases</span>
  <span m=''968760''>by</span> <span m=''969380''>at</span> <span m=''969530''>most</span>
  <span m=''969850''>1</span> <span m=''970030''>every</span> <span m=''970220''>time--</span>
  <span m=''970600''>or at most</span> <span m=''971030''>2</span> <span m=''971260''>every</span>
  <span m=''971480''>time</span> <span m=''971640''>you</span> <span m=''972090''>make
  a</span> <span m=''972430''>crimp.</span> </p><p><span m=''973270''>PROFESSOR: Yeah.</span>
  <span m=''973680''>So</span> <span m=''973870''>certainly</span> <span m=''974760''>you
  will</span> <span m=''974930''>only</span> <span m=''975110''>have</span> <span
  m=''975250''>to</span> <span m=''975340''>go</span> <span m=''975460''>around</span>
  <span m=''975710''>at</span> <span m=''975790''>most</span> <span m=''976040''>n</span>
  <span m=''976230''>times,</span> <span m=''976510''>but</span> <span m=''976860''>a</span>
  <span m=''977260''>quadratic</span> <span m=''977740''>bound</span> <span m=''978020''>overall</span>
  <span m=''978370''>is</span> <span m=''978480''>not</span> <span m=''978770''>very</span>
  <span m=''978920''>exciting.</span> </p><p><span m=''980520''>AUDIENCE: So</span>
  <span m=''981540''>it stays</span> <span m=''981890''>linear.</span> <span m=''983200''>The</span>
  <span m=''984400''>interval</span> <span m=''984930''>in</span> <span m=''985010''>which</span>
  <span m=''985330''>things</span> <span m=''985590''>are</span> <span m=''985690''>possibly</span>
  <span m=''986120''>crimpable</span> <span m=''986940''>expands</span> <span m=''987440''>by
  at</span> <span m=''987765''>most 2</span> <span m=''988090''>every time</span>
  <span m=''988380''>you</span> <span m=''989090''>make</span> <span m=''989280''>a</span>
  <span m=''989530''>crimp.</span> </p><p><span m=''989770''>PROFESSOR: I</span> <span
  m=''989900''>see.</span> <span m=''990320''>OK.</span> <span m=''991010''>So</span>
  <span m=''991180''>this</span> <span m=''991360''>is</span> <span m=''991700''>a</span>
  <span m=''991810''>different</span> <span m=''992220''>algorithm,</span> <span m=''992740''>unfortunately.</span>
  <span m=''993390''>But</span> <span m=''993950''>you</span> <span m=''994090''>maintain</span>
  <span m=''994470''>the</span> <span m=''994620''>interval</span> <span m=''995070''>of
  things</span> <span m=''995360''>that are</span> <span m=''995440''>guaranteed</span>
  <span m=''995840''>not</span> <span m=''996030''>crimpable</span> <span m=''996510''>and</span>
  <span m=''996580''>you</span> <span m=''996680''>can</span> <span m=''996830''>look</span>
  <span m=''997100''>at</span> <span m=''997210''>both</span> <span m=''997400''>ends</span>
  <span m=''998350''>whether</span> <span m=''998570''>you</span> <span m=''1000080''>can</span>
  <span m=''1000320''>crimp</span> <span m=''1000490''>something.</span> <span m=''1000840''>If</span>
  <span m=''1000940''>you</span> <span m=''1001040''>can,</span> <span m=''1001830''>fine,</span>
  <span m=''1002100''>you</span> <span m=''1002210''>do</span> <span m=''1002420''>it.</span>
  <span m=''1002520''>You</span> <span m=''1002610''>shrink</span> <span m=''1002900''>the</span>
  <span m=''1003010''>interval a</span> <span m=''1003430''>little</span> <span m=''1003640''>bit.</span>
  <span m=''1003925''>So</span> <span m=''1004210''>in</span> <span m=''1004380''>general</span>
  <span m=''1004680''>your</span> <span m=''1004830''>interval</span> <span m=''1005280''>is--</span>
  <span m=''1005640''>I have</span> <span m=''1006030''>colored</span> <span m=''1006220''>chalk,</span>
  <span m=''1006475''>I should</span> <span m=''1006730''>use</span> <span m=''1006900''>it--</span>
  <span m=''1008820''>your</span> <span m=''1009070''>interval</span> <span m=''1009760''>is</span>
  <span m=''1010030''>an</span> <span m=''1010130''>interval.</span> <span m=''1010930''>It</span>
  <span m=''1011100''>starts</span> <span m=''1011440''>somewhere,</span> <span m=''1012630''>ends</span>
  <span m=''1012940''>somewhere.</span> <span m=''1014650''>And</span> <span m=''1014850''>you''re</span>
  <span m=''1014930''>checking</span> <span m=''1015390''>is</span> <span m=''1015520''>this</span>
  <span m=''1015690''>guy</span> <span m=''1015880''>crimpable.</span> <span m=''1016550''>If</span>
  <span m=''1016960''>it''s</span> <span m=''1017060''>not</span> <span m=''1017270''>crimpable</span>
  <span m=''1017680''>you</span> <span m=''1017820''>can</span> <span m=''1017930''>extend</span>
  <span m=''1018230''>the</span> <span m=''1018310''>interval</span> <span m=''1018610''>a</span>
  <span m=''1018660''>little</span> <span m=''1018900''>bit.</span> <span m=''1019440''>If</span>
  <span m=''1019660''>it</span> <span m=''1020090''>is</span> <span m=''1020340''>crimpable</span>
  <span m=''1020780''>you</span> <span m=''1020890''>do</span> <span m=''1021020''>the</span>
  <span m=''1021120''>fold and you</span> <span m=''1021540''>actually</span> <span
  m=''1021820''>shrink</span> <span m=''1022150''>the</span> <span m=''1022260''>interval
  a</span> <span m=''1022630''>little</span> <span m=''1022810''>bit.</span> <span
  m=''1024720''>But</span> <span m=''1024880''>every</span> <span m=''1025079''>time</span>
  <span m=''1025290''>you</span> <span m=''1025349''>shrink</span> <span m=''1025599''>the</span>
  <span m=''1025720''>interval,</span> <span m=''1026050''>you</span> <span m=''1026170''>did</span>
  <span m=''1026329''>a</span> <span m=''1026369''>fold, and</span> <span m=''1026680''>that</span>
  <span m=''1026849''>only</span> <span m=''1027050''>happens</span> <span m=''1027400''>n</span>
  <span m=''1027569''>times.</span> <span m=''1028050''>Every</span> <span m=''1028240''>time</span>
  <span m=''1028420''>you</span> <span m=''1028490''>grow</span> <span m=''1028670''>the</span>
  <span m=''1028790''>interval,</span> <span m=''1029160''>you</span> <span m=''1029250''>grew</span>
  <span m=''1029430''>the</span> <span m=''1029530''>interval</span> <span m=''1029940''>and</span>
  <span m=''1030710''>you</span> <span m=''1030819''>can</span> <span m=''1030930''>only</span>
  <span m=''1031130''>grow</span> <span m=''1031420''>n</span> <span m=''1031599''>times.</span>
  <span m=''1032740''>Good.</span> </p><p><span m=''1034099''>So</span> <span m=''1034240''>that</span>
  <span m=''1034440''>will</span> <span m=''1034569''>clean</span> <span m=''1034829''>up</span>
  <span m=''1034950''>this</span> <span m=''1035060''>situation.</span> <span m=''1035589''>If</span>
  <span m=''1035680''>this</span> <span m=''1035890''>ends</span> <span m=''1036060''>up</span>
  <span m=''1036170''>being</span> <span m=''1036319''>crimpable,</span> <span m=''1036780''>you
  just</span> <span m=''1036930''>shrink</span> <span m=''1037290''>the</span> <span
  m=''1037390''>interval</span> <span m=''1037700''>from</span> <span m=''1038040''>the</span>
  <span m=''1038210''>other</span> <span m=''1038470''>side.</span> <span m=''1039599''>So</span>
  <span m=''1040109''>I</span> <span m=''1040220''>guess</span> <span m=''1040430''>if</span>
  <span m=''1040569''>I</span> <span m=''1040619''>wanted</span> <span m=''1040890''>to</span>
  <span m=''1040980''>just</span> <span m=''1041190''>tweak</span> <span m=''1041430''>this</span>
  <span m=''1041599''>algorithm</span> <span m=''1042089''>I</span> <span m=''1042200''>would</span>
  <span m=''1042369''>change</span> <span m=''1042730''>the</span> <span m=''1042829''>notion</span>
  <span m=''1043119''>of</span> <span m=''1043200''>first.</span> <span m=''1044849''>So</span>
  <span m=''1045020''>I</span> <span m=''1045119''>said,</span> <span m=''1045460''>oh,</span>
  <span m=''1045680''>this</span> <span m=''1045900''>guy is</span> <span m=''1046210''>the</span>
  <span m=''1046300''>first</span> <span m=''1046730''>one</span> <span m=''1046890''>that</span>
  <span m=''1047030''>I</span> <span m=''1047099''>visited.</span> <span m=''1048369''>But</span>
  <span m=''1048510''>if</span> <span m=''1049270''>I</span> <span m=''1049350''>end</span>
  <span m=''1049570''>up</span> <span m=''1049700''>crimping</span> <span m=''1050030''>this</span>
  <span m=''1050210''>guy, I</span> <span m=''1050470''>have</span> <span m=''1050660''>to</span>
  <span m=''1050760''>advance</span> <span m=''1051290''>the</span> <span m=''1051370''>first</span>
  <span m=''1052030''>to</span> <span m=''1052200''>be</span> <span m=''1052680''>the</span>
  <span m=''1052760''>very</span> <span m=''1052950''>next</span> <span m=''1053230''>interval.</span>
  <span m=''1054628''>Good.</span> <span m=''1056030''>Thank</span> <span m=''1056260''>you.</span>
  </p><p><span m=''1087048''>All right.</span> <span m=''1087580''>I''ll</span> <span
  m=''1087740''>correct</span> <span m=''1088040''>that</span> <span m=''1088210''>in</span>
  <span m=''1088310''>the</span> <span m=''1088400''>notes</span> <span m=''1088670''>as</span>
  <span m=''1088780''>well.</span> <span m=''1089630''>It was</span> <span m=''1089730''>almost</span>
  <span m=''1090060''>correct.</span> <span m=''1091270''>Think</span> <span m=''1091450''>now  that</span>
  <span m=''1091770''>should</span> <span m=''1091900''>be</span> <span m=''1092010''>correct.</span>
  <span m=''1092580''>Thanks</span> <span m=''1092820''>for</span> <span m=''1092950''>checking.</span>
  <span m=''1094170''>And</span> <span m=''1095050''>now</span> <span m=''1095290''>we</span>
  <span m=''1095390''>can</span> <span m=''1095510''>do</span> <span m=''1095640''>it</span>
  <span m=''1095690''>in</span> <span m=''1095790''>linear</span> <span m=''1096090''>time.</span>
  </p><p><span m=''1096450''>There''s</span> <span m=''1096660''>a</span> <span m=''1096730''>different</span>
  <span m=''1097010''>algorithm</span> <span m=''1097470''>in the</span> <span m=''1097570''>textbook,</span>
  <span m=''1099590''>which</span> <span m=''1099700''>uses</span> <span m=''1099950''>more</span>
  <span m=''1100130''>data</span> <span m=''1100350''>structures.</span> <span m=''1100840''>This</span>
  <span m=''1101040''>I</span> <span m=''1101100''>like</span> <span m=''1101370''>because</span>
  <span m=''1101560''>it''s</span> <span m=''1102130''>very</span> <span m=''1102290''>simple.</span>
  <span m=''1102670''>It''s just,</span> <span m=''1102870''>like,</span> <span m=''1103390''>storing</span>
  <span m=''1103690''>two</span> <span m=''1103830''>pointers</span> <span m=''1105130''>and</span>
  <span m=''1105300''>that''s it.</span> <span m=''1107020''>Other</span> <span m=''1107170''>questions?</span>
  </p><p><span m=''1109720''>OK.</span> <span m=''1110230''>That</span> <span m=''1110450''>does</span>
  <span m=''1110800''>algorithms.</span> <span m=''1111500''>That</span> <span m=''1111640''>was</span>
  <span m=''1111830''>the</span> <span m=''1112340''>new</span> <span m=''1112590''>material</span>
  <span m=''1113060''>I</span> <span m=''1113110''>wanted</span> <span m=''1113390''>to</span>
  <span m=''1113860''>cover.</span> <span m=''1116600''>Then</span> <span m=''1116890''>there</span>
  <span m=''1117100''>is</span> <span m=''1117270''>the</span> <span m=''1117960''>other--</span>
  <span m=''1119180''>the</span> <span m=''1119320''>actual</span> <span m=''1119670''>algorithm</span>
  <span m=''1120120''>that</span> <span m=''1120250''>was</span> <span m=''1121030''>briefly</span>
  <span m=''1121370''>described in</span> <span m=''1121850''>class is</span> <span
  m=''1122250''>this</span> <span m=''1122390''>local</span> <span m=''1122760''>foldability</span>
  <span m=''1123390''>algorithm.</span> <span m=''1123670''>So</span> <span m=''1123950''>you</span>
  <span m=''1124060''>have</span> <span m=''1124920''>now</span> <span m=''1125130''>not</span>
  <span m=''1125340''>just</span> <span m=''1125540''>a</span> <span m=''1125590''>single</span>
  <span m=''1125970''>vertex,</span> <span m=''1126560''>but</span> <span m=''1126680''>you</span>
  <span m=''1126750''>have</span> <span m=''1126930''>a</span> <span m=''1126970''>whole</span>
  <span m=''1127150''>crease</span> <span m=''1127390''>pattern.</span> <span m=''1128160''>You''d</span>
  <span m=''1128320''>like</span> <span m=''1128540''>to</span> <span m=''1128660''>assign</span>
  <span m=''1129120''>a</span> <span m=''1129160''>mountain</span> <span m=''1129420''>valley</span>
  <span m=''1129710''>assignment</span> <span m=''1130780''>to</span> <span m=''1131050''>it</span>
  <span m=''1132230''>that is</span> <span m=''1132540''>at</span> <span m=''1132620''>least</span>
  <span m=''1132840''>locally</span> <span m=''1133360''>good,</span> <span m=''1134030''>that</span>
  <span m=''1134510''>when</span> <span m=''1134670''>you</span> <span m=''1134790''>run</span>
  <span m=''1134980''>this</span> <span m=''1135170''>algorithm</span> <span m=''1135590''>at</span>
  <span m=''1135780''>each</span> <span m=''1135960''>vertex</span> <span m=''1136840''>it</span>
  <span m=''1137030''>gives</span> <span m=''1137330''>the</span> <span m=''1137450''>right</span>
  <span m=''1137630''>answer,</span> <span m=''1139040''>it</span> <span m=''1139130''>says</span>
  <span m=''1139370''>that, yeah,</span> <span m=''1139610''>it''s</span> <span m=''1139940''>locally</span>
  <span m=''1140310''>foldable</span> <span m=''1140800''>for</span> <span m=''1140980''>each</span>
  <span m=''1141160''>vertex.</span> <span m=''1141590''>It</span> <span m=''1141660''>doesn''t</span>
  <span m=''1141890''>mean</span> <span m=''1142010''>the</span> <span m=''1142240''>whole</span>
  <span m=''1142430''>thing</span> <span m=''1142630''>will</span> <span m=''1142740''>fold</span>
  <span m=''1143930''>flat,</span> <span m=''1144330''>but</span> <span m=''1145690''>it''s</span>
  <span m=''1145880''>a</span> <span m=''1145930''>start,</span> <span m=''1146280''>at</span>
  <span m=''1146380''>least.</span> <span m=''1146690''>It''s</span> <span m=''1146820''>a</span>
  <span m=''1146880''>necessary</span> <span m=''1147380''>condition</span> <span
  m=''1148180''>for</span> <span m=''1148440''>that.</span> </p><p><span m=''1150030''>So</span>
  <span m=''1150590''>I</span> <span m=''1150740''>just</span> <span m=''1150910''>want</span>
  <span m=''1151040''>to</span> <span m=''1151090''>give</span> <span m=''1151220''>you</span>
  <span m=''1151310''>a</span> <span m=''1151350''>few</span> <span m=''1151500''>examples</span>
  <span m=''1152070''>of</span> <span m=''1152200''>this</span> <span m=''1152360''>algorithm,</span>
  <span m=''1152680''>because</span> <span m=''1152900''>it</span> <span m=''1152980''>is</span>
  <span m=''1153130''>confusing.</span> <span m=''1153670''>I</span> <span m=''1153710''>didn''t</span>
  <span m=''1153890''>do</span> <span m=''1153990''>any</span> <span m=''1154160''>examples</span>
  <span m=''1154570''>in</span> <span m=''1154640''>lecture.</span> <span m=''1155820''>It''s</span>
  <span m=''1155980''>always</span> <span m=''1156150''>been</span> <span m=''1156290''>the</span>
  <span m=''1156350''>most</span> <span m=''1156550''>confusing</span> <span m=''1156900''>part</span>
  <span m=''1157130''>to</span> <span m=''1157240''>me,</span> <span m=''1157890''>and</span>
  <span m=''1160930''>especially</span> <span m=''1161500''>this</span> <span m=''1161830''>notion</span>
  <span m=''1162150''>of merging</span> <span m=''1162640''>cycles</span> <span m=''1162970''>and</span>
  <span m=''1163120''>paths.</span> <span m=''1164160''>So</span> <span m=''1164390''>for</span>
  <span m=''1164550''>starters,</span> <span m=''1164890''>these</span> <span m=''1165100''>are</span>
  <span m=''1165160''>the</span> <span m=''1165280''>examples</span> <span m=''1165740''>in</span>
  <span m=''1165920''>the</span> <span m=''1166010''>textbook.</span> <span m=''1166460''>They''re</span>
  <span m=''1166570''>pretty</span> <span m=''1166790''>simple,</span> <span m=''1168110''>but</span>
  <span m=''1168350''>at least</span> <span m=''1168625''>they''ll</span> <span m=''1168900''>get</span>
  <span m=''1169100''>us</span> <span m=''1169220''>warmed</span> <span m=''1169540''>up.</span>
  <span m=''1170210''>So</span> <span m=''1170670''>the</span> <span m=''1170840''>crease</span>
  <span m=''1171080''>pattern</span> <span m=''1171420''>is</span> <span m=''1171520''>the</span>
  <span m=''1171610''>bold</span> <span m=''1172010''>black</span> <span m=''1172330''>lines.</span>
  <span m=''1173305''>It''s</span> <span m=''1173790''>two</span> <span m=''1174070''>of</span>
  <span m=''1174130''>them.</span> <span m=''1174880''>And</span> <span m=''1175590''>in</span>
  <span m=''1175790''>this</span> <span m=''1176010''>case</span> <span m=''1176350''>it''s</span>
  <span m=''1176550''>the</span> <span m=''1176780''>generic</span> <span m=''1177210''>case,</span>
  <span m=''1177520''>so</span> <span m=''1177630''>there''s</span> <span m=''1177920''>a</span>
  <span m=''1178350''>unique</span> <span m=''1179090''>pairing</span> <span m=''1180190''>here.</span>
  <span m=''1180500''>There''s</span> <span m=''1180710''>only</span> <span m=''1180970''>one</span>
  <span m=''1181290''>crimpable</span> <span m=''1181780''>pair,</span> <span m=''1182150''>which</span>
  <span m=''1182380''>are</span> <span m=''1182510''>these</span> <span m=''1182750''>two</span>
  <span m=''1182890''>guys.</span> <span m=''1183240''>This</span> <span m=''1183410''>is</span>
  <span m=''1183500''>the</span> <span m=''1183640''>only</span> <span m=''1183880''>locally</span>
  <span m=''1184270''>smallest</span> <span m=''1184720''>angle.</span> <span m=''1185850''>So</span>
  <span m=''1186050''>those</span> <span m=''1186430''>two</span> <span m=''1186670''>have</span>
  <span m=''1187030''>to</span> <span m=''1187130''>be</span> <span m=''1187250''>crimped</span>
  <span m=''1187560''>first.</span> <span m=''1188360''>One''s</span> <span m=''1188590''>going</span>
  <span m=''1188700''>to</span> <span m=''1188760''>be a</span> <span m=''1188890''>mountain,</span>
  <span m=''1189230''>one''s</span> <span m=''1189410''>going to be a</span> <span
  m=''1189640''>valley.</span> <span m=''1189940''>So</span> <span m=''1190090''>we
  would</span> <span m=''1190170''>write</span> <span m=''1190430''>not</span> <span
  m=''1190630''>equals</span> <span m=''1191110''>in</span> <span m=''1191250''>this</span>
  <span m=''1191460''>blue</span> <span m=''1192240''>thing</span> <span m=''1192450''>to</span>
  <span m=''1192540''>represent</span> <span m=''1193010''>that</span> <span m=''1193190''>constraint.</span>
  <span m=''1194240''>This</span> <span m=''1194450''>will</span> <span m=''1194540''>be</span>
  <span m=''1194670''>all</span> <span m=''1194800''>that''s</span> <span m=''1194970''>left.</span>
  <span m=''1195240''>And</span> <span m=''1195330''>so</span> <span m=''1195440''>these</span>
  <span m=''1195640''>two</span> <span m=''1195770''>guys</span> <span m=''1196000''>have</span>
  <span m=''1196150''>to</span> <span m=''1196250''>be</span> <span m=''1196430''>equal.</span>
  <span m=''1197230''>It''s</span> <span m=''1197410''>symmetric,</span> <span m=''1197950''>so</span>
  <span m=''1198060''>it</span> <span m=''1198120''>looks</span> <span m=''1198380''>the</span>
  <span m=''1198500''>same</span> <span m=''1198900''>all</span> <span m=''1199050''>the</span>
  <span m=''1199120''>way</span> <span m=''1199220''>around.</span> <span m=''1200410''>And</span>
  <span m=''1200590''>so</span> <span m=''1200900''>when</span> <span m=''1201040''>you</span>
  <span m=''1201140''>see,</span> <span m=''1201490''>OK,</span> <span m=''1201710''>these</span>
  <span m=''1201940''>two</span> <span m=''1202050''>guys</span> <span m=''1202260''>have</span>
  <span m=''1202380''>to</span> <span m=''1202470''>be</span> <span m=''1202600''>not</span>
  <span m=''1202800''>equal,</span> <span m=''1203500''>but</span> <span m=''1203640''>also</span>
  <span m=''1204030''>these</span> <span m=''1204310''>two</span> <span m=''1204440''>guys</span>
  <span m=''1204670''>have</span> <span m=''1204810''>to</span> <span m=''1204910''>be</span>
  <span m=''1205020''>not</span> <span m=''1205200''>equal,</span> <span m=''1205720''>but</span>
  <span m=''1205970''>also</span> <span m=''1206340''>these</span> <span m=''1206630''>two</span>
  <span m=''1206750''>guys</span> <span m=''1206990''>have</span> <span m=''1207120''>to</span>
  <span m=''1207210''>be</span> <span m=''1207360''>not</span> <span m=''1207520''>equal,</span>
  <span m=''1207790''>this</span> <span m=''1207990''>is</span> <span m=''1208140''>what</span>
  <span m=''1208300''>we</span> <span m=''1208410''>call</span> <span m=''1208660''>a</span>
  <span m=''1208720''>cycle</span> <span m=''1209200''>of</span> <span m=''1209380''>constraints.</span>
  </p><p><span m=''1210580''>In</span> <span m=''1210690''>general,</span> <span m=''1211080''>you</span>
  <span m=''1211180''>get</span> <span m=''1211380''>paths.</span> <span m=''1211860''>Like,</span>
  <span m=''1212020''>this</span> <span m=''1212200''>one</span> <span m=''1212390''>starts</span>
  <span m=''1212790''>and</span> <span m=''1212900''>ends</span> <span m=''1213150''>at</span>
  <span m=''1213230''>infinity,</span> <span m=''1214400''>so</span> <span m=''1214470''>these</span>
  <span m=''1214670''>two</span> <span m=''1214800''>guys</span> <span m=''1214980''>have</span>
  <span m=''1215100''>to</span> <span m=''1215190''>be</span> <span m=''1215350''>equal,</span>
  <span m=''1215630''>these</span> <span m=''1215790''>two</span> <span m=''1215900''>guys</span>
  <span m=''1216100''>have</span> <span m=''1216210''>to</span> <span m=''1216280''>be</span>
  <span m=''1216390''>equal.</span> <span m=''1216650''>They</span> <span m=''1216760''>could</span>
  <span m=''1216900''>both</span> <span m=''1217120''>be</span> <span m=''1217230''>mountain,</span>
  <span m=''1217560''>both</span> <span m=''1217760''>be</span> <span m=''1217850''>valley,</span>
  <span m=''1218370''>doesn''t</span> <span m=''1218590''>matter.</span> <span m=''1219420''>These
  are</span> <span m=''1219610''>the</span> <span m=''1219750''>only</span> <span
  m=''1219950''>constraints.</span> <span m=''1221200''>But</span> <span m=''1221400''>this</span>
  <span m=''1221610''>cycle--</span> <span m=''1222170''>cycles</span> <span m=''1222660''>can</span>
  <span m=''1222810''>be</span> <span m=''1222930''>problems,</span> <span m=''1223460''>and</span>
  <span m=''1223560''>here</span> <span m=''1223820''>because</span> <span m=''1224140''>it''s</span>
  <span m=''1224280''>an</span> <span m=''1224370''>odd</span> <span m=''1224630''>cycle</span>
  <span m=''1225000''>of</span> <span m=''1225120''>not</span> <span m=''1225310''>equals</span>
  <span m=''1226420''>there''s</span> <span m=''1226640''>no</span> <span m=''1226800''>way</span>
  <span m=''1226930''>to</span> <span m=''1227070''>assign</span> <span m=''1227400''>it.</span>
  <span m=''1227580''>If you</span> <span m=''1227690''>say</span> <span m=''1227880''>mountain,</span>
  <span m=''1228580''>valley,</span> <span m=''1229230''>mountain,</span> <span m=''1229920''>then</span>
  <span m=''1230150''>these</span> <span m=''1230330''>two</span> <span m=''1230430''>guys</span>
  <span m=''1230650''>are</span> <span m=''1230710''>both</span> <span m=''1230910''>mountains,</span>
  <span m=''1231290''>which</span> <span m=''1231480''>violates</span> <span m=''1231930''>that</span>
  <span m=''1232040''>constraint.</span> <span m=''1233350''>In</span> <span m=''1233510''>general,</span>
  <span m=''1234110''>the</span> <span m=''1234440''>number</span> <span m=''1235050''>of</span>
  <span m=''1235300''>not</span> <span m=''1235560''>equals</span> <span m=''1236620''>should</span>
  <span m=''1236930''>be</span> <span m=''1237200''>even</span> <span m=''1237800''>in</span>
  <span m=''1238040''>each</span> <span m=''1238200''>cycle.</span> <span m=''1238980''>If
  it''s</span> <span m=''1239150''>ever</span> <span m=''1240070''>an</span> <span
  m=''1240160''>odd</span> <span m=''1240470''>number</span> <span m=''1240730''>of</span>
  <span m=''1240800''>not</span> <span m=''1240970''>equals,</span> <span m=''1241760''>you''re</span>
  <span m=''1241910''>in</span> <span m=''1241990''>trouble.</span> </p><p><span m=''1243010''>Here''s</span>
  <span m=''1243260''>an</span> <span m=''1243520''>example</span> <span m=''1244060''>where</span>
  <span m=''1244300''>the</span> <span m=''1244940''>cycle</span> <span m=''1245410''>is</span>
  <span m=''1245620''>even,</span> <span m=''1246770''>but</span> <span m=''1246950''>we</span>
  <span m=''1247100''>end</span> <span m=''1247250''>up</span> <span m=''1247370''>with</span>
  <span m=''1247510''>an</span> <span m=''1247630''>equals</span> <span m=''1248360''>here,</span>
  <span m=''1248730''>and so</span> <span m=''1248880''>the</span> <span m=''1248980''>number</span>
  <span m=''1249370''>of</span> <span m=''1249500''>not</span> <span m=''1249690''>equals</span>
  <span m=''1250050''>is</span> <span m=''1250130''>still</span> <span m=''1250410''>odd,</span>
  <span m=''1251200''>so</span> <span m=''1251330''>this</span> <span m=''1251480''>is</span>
  <span m=''1251580''>also</span> <span m=''1251840''>bad.</span> <span m=''1252510''>I
  mean,</span> <span m=''1252680''>it''s</span> <span m=''1252810''>just</span> <span
  m=''1253000''>replacing</span> <span m=''1253470''>this</span> <span m=''1254070''>segment</span>
  <span m=''1254440''>with</span> <span m=''1254580''>two</span> <span m=''1254770''>equal</span>
  <span m=''1255810''>creases.</span> <span m=''1257480''>Still</span> <span m=''1257720''>can''t</span>
  <span m=''1258240''>assign</span> <span m=''1258530''>a</span> <span m=''1258600''>mountain
  or</span> <span m=''1258940''>valley.</span> <span m=''1260290''>But</span> <span
  m=''1260470''>these</span> <span m=''1260660''>are</span> <span m=''1260750''>kind</span>
  <span m=''1260950''>of</span> <span m=''1261030''>simple</span> <span m=''1261350''>examples.</span>
  <span m=''1263310''>These</span> <span m=''1263490''>are</span> <span m=''1263560''>cycles</span>
  <span m=''1264160''>and</span> <span m=''1264380''>everything</span> <span m=''1264800''>was</span>
  <span m=''1264910''>uniquely</span> <span m=''1265300''>determined</span> <span
  m=''1265720''>here.</span> <span m=''1265900''>You</span> <span m=''1266010''>had</span>
  <span m=''1266390''>to</span> <span m=''1266995''>crimp</span> <span m=''1267480''>this</span>
  <span m=''1267690''>guy</span> <span m=''1267830''>first.</span> <span m=''1268200''>You</span>
  <span m=''1268280''>had</span> <span m=''1268540''>to</span> <span m=''1268610''>crimp</span>
  <span m=''1268820''>this</span> <span m=''1269000''>guy</span> <span m=''1269140''>first.</span>
  <span m=''1269900''>There</span> <span m=''1270000''>was</span> <span m=''1270090''>no</span>
  <span m=''1270230''>choice.</span> <span m=''1271280''>And</span> <span m=''1271590''>the</span>
  <span m=''1272340''>tricky</span> <span m=''1272620''>part</span> <span m=''1272790''>of</span>
  <span m=''1272830''>the</span> <span m=''1272950''>algorithm</span> <span m=''1273300''>is</span>
  <span m=''1273410''>when</span> <span m=''1273550''>you</span> <span m=''1273620''>have</span>
  <span m=''1273880''>choice,</span> <span m=''1274150''>when</span> <span m=''1274260''>you</span>
  <span m=''1274330''>have</span> <span m=''1274430''>multiple</span> <span m=''1274850''>equal</span>
  <span m=''1275140''>angles,</span> <span m=''1275870''>you</span> <span m=''1275990''>don''t</span>
  <span m=''1276150''>know</span> <span m=''1276280''>what</span> <span m=''1276450''>to</span>
  <span m=''1276530''>crimp</span> <span m=''1276780''>first.</span> <span m=''1277420''>The</span>
  <span m=''1277560''>algorithm</span> <span m=''1277950''>just</span> <span m=''1278170''>crimps</span>
  <span m=''1278450''>one</span> <span m=''1278680''>of</span> <span m=''1278740''>them</span>
  <span m=''1278880''>first,</span> <span m=''1279920''>but</span> <span m=''1280050''>then</span>
  <span m=''1280200''>it</span> <span m=''1280270''>might</span> <span m=''1280430''>have</span>
  <span m=''1280580''>to</span> <span m=''1280680''>fix</span> <span m=''1280960''>things.</span>
  <span m=''1281380''>So</span> <span m=''1281610''>I</span> <span m=''1281740''>came</span>
  <span m=''1281980''>up</span> <span m=''1282090''>with</span> <span m=''1282250''>a</span>
  <span m=''1282320''>simple</span> <span m=''1282610''>example</span> <span m=''1283030''>where</span>
  <span m=''1283160''>you</span> <span m=''1283230''>have</span> <span m=''1283420''>to</span>
  <span m=''1283550''>do</span> <span m=''1283700''>that.</span> <span m=''1283950''>I</span>
  <span m=''1284110''>think</span> <span m=''1284330''>it</span> <span m=''1284430''>will</span>
  <span m=''1285240''>help</span> <span m=''1285440''>clarify</span> <span m=''1285930''>how</span>
  <span m=''1286150''>this</span> <span m=''1286470''>merging</span> <span m=''1286900''>really</span>
  <span m=''1287110''>happens.</span> </p><p><span m=''1289650''>So</span> <span m=''1294250''>the</span>
  <span m=''1294330''>example</span> <span m=''1294880''>is--</span> <span m=''1297274''>it''s</span>
  <span m=''1297690''>hard</span> <span m=''1298100''>to</span> <span m=''1298170''>draw</span>
  <span m=''1298770''>an</span> <span m=''1298990''>equilateral</span> <span m=''1299480''>triangle</span>
  <span m=''1300470''>with</span> <span m=''1300890''>accurate</span> <span m=''1301330''>angles,</span>
  <span m=''1301800''>but</span> <span m=''1302165''>I''ll</span> <span m=''1302530''>do</span>
  <span m=''1302710''>my best--</span> <span m=''1303650''>and</span> <span m=''1303900''>then</span>
  <span m=''1304660''>these</span> <span m=''1305160''>are</span> <span m=''1305370''>supposed</span>
  <span m=''1305700''>to</span> <span m=''1305790''>be</span> <span m=''1306020''>right</span>
  <span m=''1306270''>angles.</span> <span m=''1313520''>OK.</span> <span m=''1313650''>So</span>
  <span m=''1313820''>that''s</span> <span m=''1314060''>my</span> <span m=''1314120''>crease</span>
  <span m=''1314440''>pattern.</span> <span m=''1317430''>And</span> <span m=''1317840''>some</span>
  <span m=''1318030''>of</span> <span m=''1318110''>this</span> <span m=''1318310''>is</span>
  <span m=''1318460''>forced.</span> <span m=''1322230''>This</span> <span m=''1322640''>guy--</span>
  <span m=''1323580''>at</span> <span m=''1323870''>this</span> <span m=''1324060''>vertex,</span>
  <span m=''1324570''>this</span> <span m=''1324760''>is</span> <span m=''1324860''>the</span>
  <span m=''1324990''>only</span> <span m=''1325200''>locally</span> <span m=''1325530''>smallest</span>
  <span m=''1325940''>angle.</span> <span m=''1326190''>It''s</span> <span m=''1326310''>only</span>
  <span m=''1326470''>60</span> <span m=''1326790''>degrees,</span> <span m=''1327090''>these</span>
  <span m=''1327260''>are</span> <span m=''1327320''>90.</span> <span m=''1327780''>This
  is</span> <span m=''1328070''>bigger</span> <span m=''1328280''>than</span> <span
  m=''1328430''>90.</span> <span m=''1329220''>So</span> <span m=''1329510''>this</span>
  <span m=''1330050''>has</span> <span m=''1330350''>to</span> <span m=''1330440''>be</span>
  <span m=''1330570''>crimped</span> <span m=''1330930''>first,</span> <span m=''1331280''>and</span>
  <span m=''1331370''>it''s</span> <span m=''1331530''>not</span> <span m=''1331710''>equal.</span>
  <span m=''1332660''>That</span> <span m=''1332810''>means</span> <span m=''1333080''>these</span>
  <span m=''1333300''>guys</span> <span m=''1333500''>are</span> <span m=''1333580''>equal.</span>
  <span m=''1333940''>We</span> <span m=''1334030''>don''t</span> <span m=''1334150''>really</span>
  <span m=''1334360''>care</span> <span m=''1334540''>about</span> <span m=''1334740''>those.</span>
  <span m=''1335160''>And</span> <span m=''1335370''>it''s</span> <span m=''1335800''>symmetric,</span>
  <span m=''1336440''>so</span> <span m=''1337300''>not</span> <span m=''1337470''>equal,</span>
  <span m=''1338810''>equal.</span> <span m=''1340010''>OK.</span> <span m=''1341250''>But</span>
  <span m=''1341520''>here</span> <span m=''1341750''>we</span> <span m=''1341850''>have</span>
  <span m=''1341980''>a</span> <span m=''1342050''>choice.</span> <span m=''1342370''>There''s</span>
  <span m=''1342560''>two 60</span> <span m=''1343090''>degree</span> <span m=''1343390''>angles.</span>
  <span m=''1343930''>This</span> <span m=''1344070''>does</span> <span m=''1344200''>not</span>
  <span m=''1344370''>look</span> <span m=''1344460''>very</span> <span m=''1344680''>flat</span>
  <span m=''1344970''>foldable.</span> <span m=''1345415''>I</span> <span m=''1345860''>think</span>
  <span m=''1346962''>I''d better</span> <span m=''1347320''>add</span> <span m=''1347920''>some
  more</span> <span m=''1348210''>creases</span> <span m=''1348730''>there.</span>
  <span m=''1351180''>Got</span> <span m=''1351340''>to</span> <span m=''1351380''>have</span>
  <span m=''1351630''>to</span> <span m=''1351730''>even</span> <span m=''1352050''>parity</span>
  <span m=''1352550''>at every</span> <span m=''1352890''>vertex.</span> </p><p><span
  m=''1354480''>So</span> <span m=''1354570''>now</span> <span m=''1354730''>we</span>
  <span m=''1354810''>have</span> <span m=''1354900''>a</span> <span m=''1354960''>choice.</span>
  <span m=''1355350''>Do</span> <span m=''1355360''>we</span> <span m=''1355480''>crimp</span>
  <span m=''1355810''>this</span> <span m=''1356090''>one</span> <span m=''1356280''>first</span>
  <span m=''1356630''>or</span> <span m=''1356760''>do</span> <span m=''1356900''>we
  crimp</span> <span m=''1357260''>the</span> <span m=''1357380''>other</span> <span
  m=''1357520''>one</span> <span m=''1357670''>first?</span> <span m=''1358630''>At</span>
  <span m=''1358790''>this</span> <span m=''1358970''>point, it''s</span> <span m=''1359200''>symmetric,</span>
  <span m=''1359710''>so</span> <span m=''1359830''>I''ll</span> <span m=''1359970''>do</span>
  <span m=''1360080''>this</span> <span m=''1360280''>one</span> <span m=''1360420''>first.</span>
  <span m=''1361860''>This''ll</span> <span m=''1362130''>be</span> <span m=''1362250''>my</span>
  <span m=''1362410''>pairing.</span> <span m=''1364400''>And</span> <span m=''1364690''>there</span>
  <span m=''1364800''>are</span> <span m=''1364850''>two</span> <span m=''1364990''>possibilities</span>
  <span m=''1365560''>here.</span> <span m=''1365820''>Either I</span> <span m=''1366090''>crimp</span>
  <span m=''1366340''>this</span> <span m=''1366500''>one</span> <span m=''1366650''>first</span>
  <span m=''1366920''>or crimp</span> <span m=''1367160''>this</span> <span m=''1367340''>one</span>
  <span m=''1367470''>first.</span> <span m=''1367750''>The algorithm</span> <span
  m=''1368250''>doesn''t</span> <span m=''1368540''>care.</span> <span m=''1368790''>So</span>
  <span m=''1368980''>let''s</span> <span m=''1369200''>suppose</span> <span m=''1369570''>it</span>
  <span m=''1369660''>does</span> <span m=''1369850''>this</span> <span m=''1370050''>one,</span>
  <span m=''1370210''>because</span> <span m=''1370420''>this</span> <span m=''1370580''>is</span>
  <span m=''1370700''>the bad</span> <span m=''1370820''>one.</span> <span m=''1372690''>OK.</span>
  <span m=''1372880''>Now</span> <span m=''1373100''>we</span> <span m=''1373190''>have</span>
  <span m=''1373390''>a</span> <span m=''1373480''>cycle</span> <span m=''1375770''>with</span>
  <span m=''1375990''>an</span> <span m=''1376080''>odd</span> <span m=''1376330''>number</span>
  <span m=''1376680''>not</span> <span m=''1376860''>equals.</span> <span m=''1377390''>So</span>
  <span m=''1377550''>this</span> <span m=''1377760''>is</span> <span m=''1377920''>not</span>
  <span m=''1378180''>possible</span> <span m=''1378740''>to</span> <span m=''1379360''>satisfy.</span>
  <span m=''1380690''>The</span> <span m=''1380780''>algorithm</span> <span m=''1381180''>doesn''t</span>
  <span m=''1381450''>stop</span> <span m=''1381700''>there.</span> <span m=''1381850''>It</span>
  <span m=''1381950''>says,</span> <span m=''1382290''>OK,</span> <span m=''1382900''>I</span>
  <span m=''1382990''>have</span> <span m=''1383240''>these</span> <span m=''1383430''>paths.</span>
  <span m=''1385710''>There''s</span> <span m=''1385950''>a</span> <span m=''1386000''>cycle</span>
  <span m=''1386380''>here</span> <span m=''1387870''>that''s</span> <span m=''1388050''>a</span>
  <span m=''1388100''>problem,</span> <span m=''1389270''>then</span> <span m=''1389410''>I</span>
  <span m=''1389540''>also</span> <span m=''1389830''>have</span> <span m=''1390230''>a</span>
  <span m=''1390460''>path</span> <span m=''1390840''>up</span> <span m=''1390990''>here.</span>
  <span m=''1393540''>How does</span> <span m=''1393680''>it</span> <span m=''1393760''>go?</span>
  <span m=''1393950''>There''s</span> <span m=''1394150''>a</span> <span m=''1394260''>path</span>
  <span m=''1396198''>that</span> <span m=''1396614''>goes</span> <span m=''1397030''>here,</span>
  <span m=''1397760''>here,</span> <span m=''1398330''>here,</span> <span m=''1398970''>here.</span>
  <span m=''1400660''>And</span> <span m=''1400890''>there''s</span> <span m=''1401050''>a</span>
  <span m=''1401120''>path</span> <span m=''1401420''>that</span> <span m=''1401540''>goes</span>
  <span m=''1401750''>here.</span> <span m=''1403860''>But</span> <span m=''1404200''>really
  it</span> <span m=''1404560''>looks</span> <span m=''1404820''>at</span> <span m=''1404900''>the</span>
  <span m=''1404980''>vertices</span> <span m=''1405420''>that</span> <span m=''1405530''>had</span>
  <span m=''1405770''>choice.</span> <span m=''1406350''>It</span> <span m=''1406840''>says,</span>
  <span m=''1407180''>look,</span> <span m=''1408900''>at</span> <span m=''1409100''>this</span>
  <span m=''1409270''>moment</span> <span m=''1409630''>I</span> <span m=''1409730''>had</span>
  <span m=''1409770''>a</span> <span m=''1409830''>choice</span> <span m=''1410100''>between</span>
  <span m=''1410560''>whether</span> <span m=''1410860''>to</span> <span m=''1410960''>fold</span>
  <span m=''1411180''>this</span> <span m=''1411370''>angle</span> <span m=''1411710''>or</span>
  <span m=''1411740''>this</span> <span m=''1411960''>angle.</span> <span m=''1412210''>In</span>
  <span m=''1412270''>general,</span> <span m=''1412810''>it</span> <span m=''1412860''>might</span>
  <span m=''1413010''>have</span> <span m=''1413090''>been</span> <span m=''1413200''>a</span>
  <span m=''1413250''>bunch</span> <span m=''1413510''>of</span> <span m=''1413590''>equal</span>
  <span m=''1413910''>angles.</span> <span m=''1415210''>We</span> <span m=''1415700''>see</span>
  <span m=''1415880''>here</span> <span m=''1416010''>that</span> <span m=''1416180''>there''s</span>
  <span m=''1416370''>a</span> <span m=''1416440''>cycle</span> <span m=''1417880''>that</span>
  <span m=''1418910''>the</span> <span m=''1419200''>other</span> <span m=''1419460''>choice</span>
  <span m=''1419970''>would''ve</span> <span m=''1420290''>involved</span> <span m=''1420710''>a</span>
  <span m=''1420800''>path.</span> </p><p><span m=''1422320''>And</span> <span m=''1422510''>so</span>
  <span m=''1422740''>we</span> <span m=''1423400''>merge.</span> <span m=''1423900''>In</span>
  <span m=''1424000''>general,</span> <span m=''1424290''>if</span> <span m=''1425110''>there''s</span>
  <span m=''1425280''>two</span> <span m=''1425440''>different</span> <span m=''1425890''>things--</span>
  <span m=''1428150''>one</span> <span m=''1428320''>could</span> <span m=''1428430''>be</span>
  <span m=''1428540''>a</span> <span m=''1428580''>cycle,</span> <span m=''1429120''>one</span>
  <span m=''1429200''>could</span> <span m=''1429290''>be</span> <span m=''1429390''>a</span>
  <span m=''1429450''>path,</span> <span m=''1429800''>they</span> <span m=''1429890''>could</span>
  <span m=''1430010''>both</span> <span m=''1430200''>be</span> <span m=''1430310''>cycles,</span>
  <span m=''1430810''>they</span> <span m=''1430900''>could</span> <span m=''1431030''>both</span>
  <span m=''1431220''>be</span> <span m=''1431340''>paths,</span> <span m=''1431700''>whatever--</span>
  <span m=''1433020''>if</span> <span m=''1433200''>I</span> <span m=''1433290''>ever</span>
  <span m=''1433480''>have</span> <span m=''1433660''>the</span> <span m=''1433780''>opportunity</span>
  <span m=''1434460''>to</span> <span m=''1435280''>join</span> <span m=''1435760''>those</span>
  <span m=''1436000''>two</span> <span m=''1436140''>parts</span> <span m=''1436490''>together</span>
  <span m=''1438000''>I''ll</span> <span m=''1438180''>do</span> <span m=''1438370''>it.</span>
  <span m=''1438650''>So</span> <span m=''1438840''>in</span> <span m=''1438900''>other</span>
  <span m=''1439050''>words,</span> <span m=''1439230''>I</span> <span m=''1439540''>do</span>
  <span m=''1439730''>the</span> <span m=''1439890''>other</span> <span m=''1440120''>crease</span>
  <span m=''1440370''>first.</span> <span m=''1441380''>Let</span> <span m=''1441470''>me</span>
  <span m=''1441580''>draw</span> <span m=''1441790''>that.</span> <span m=''1446930''>What</span>
  <span m=''1447210''>that</span> <span m=''1447380''>means</span> <span m=''1447750''>will</span>
  <span m=''1447900''>become</span> <span m=''1448310''>clear</span> <span m=''1448660''>once</span>
  <span m=''1448910''>we</span> <span m=''1449570''>actually</span> <span m=''1449880''>do</span>
  <span m=''1450080''>one.</span> <span m=''1452820''>So</span> <span m=''1453940''>I</span>
  <span m=''1454060''>want</span> <span m=''1454340''>to</span> <span m=''1454410''>do</span>
  <span m=''1455070''>this</span> <span m=''1455420''>first.</span> <span m=''1456090''>The</span>
  <span m=''1456210''>rest</span> <span m=''1456500''>is</span> <span m=''1456610''>the</span>
  <span m=''1456660''>same.</span> <span m=''1470010''>OK.</span> <span m=''1470610''>So</span>
  <span m=''1471020''>in</span> <span m=''1471210''>that</span> <span m=''1471540''>situation,</span>
  <span m=''1472670''>what</span> <span m=''1473420''>do</span> <span m=''1473460''>my</span>
  <span m=''1473610''>paths</span> <span m=''1474030''>and</span> <span m=''1474160''>cycle</span>
  <span m=''1474490''>look</span> <span m=''1474680''>like?</span> <span m=''1474930''>Well,</span>
  <span m=''1475760''>there</span> <span m=''1475870''>was</span> <span m=''1475990''>this</span>
  <span m=''1476140''>path</span> <span m=''1476520''>that</span> <span m=''1476620''>started</span>
  <span m=''1476950''>over</span> <span m=''1477140''>here.</span> <span m=''1477380''>It</span>
  <span m=''1477450''>used</span> <span m=''1477650''>to</span> <span m=''1477720''>go</span>
  <span m=''1477900''>like</span> <span m=''1478130''>this,</span> <span m=''1478470''>but</span>
  <span m=''1478620''>now</span> <span m=''1478810''>this</span> <span m=''1478980''>vertex</span>
  <span m=''1479340''>has</span> <span m=''1479470''>changed.</span> <span m=''1480530''>So</span>
  <span m=''1480600''>it''s</span> <span m=''1480720''>going</span> <span m=''1480830''>to</span>
  <span m=''1480910''>do</span> <span m=''1481040''>something</span> <span m=''1481460''>different</span>
  <span m=''1482680''>at</span> <span m=''1483230''>that</span> <span m=''1483660''>vertex.</span>
  <span m=''1484480''>Now it</span> <span m=''1484610''>goes</span> <span m=''1485020''>over</span>
  <span m=''1485230''>this</span> <span m=''1485470''>way.</span> <span m=''1486450''>I''m</span>
  <span m=''1486590''>just</span> <span m=''1486740''>following</span> <span m=''1487170''>the</span>
  <span m=''1487290''>constraints.</span> <span m=''1489240''>Now</span> <span m=''1489460''>those</span>
  <span m=''1489820''>two</span> <span m=''1489980''>guys</span> <span m=''1490290''>are</span>
  <span m=''1490360''>constrained</span> <span m=''1490830''>to</span> <span m=''1490910''>be</span>
  <span m=''1491110''>different.</span> <span m=''1492290''>And</span> <span m=''1492500''>these</span>
  <span m=''1492690''>are</span> <span m=''1492770''>constrained</span> <span m=''1493200''>to</span>
  <span m=''1493260''>be</span> <span m=''1493420''>equal.</span> <span m=''1493800''>So</span>
  <span m=''1493920''>lo</span> <span m=''1494090''>and</span> <span m=''1494170''>behold</span>
  <span m=''1494520''>we</span> <span m=''1494640''>merged</span> <span m=''1494880''>a</span>
  <span m=''1494970''>path</span> <span m=''1495220''>and</span> <span m=''1495280''>the</span>
  <span m=''1495370''>cycle</span> <span m=''1496100''>and</span> <span m=''1496250''>we</span>
  <span m=''1496340''>got</span> <span m=''1496590''>a</span> <span m=''1496680''>single</span>
  <span m=''1496990''>path.</span> <span m=''1497520''>The</span> <span m=''1497950''>other</span>
  <span m=''1498090''>paths</span> <span m=''1498480''>remain</span> <span m=''1498740''>the</span>
  <span m=''1498810''>same.</span> <span m=''1499740''>Just</span> <span m=''1500000''>these</span>
  <span m=''1500190''>two</span> <span m=''1500320''>guys</span> <span m=''1500630''>got</span>
  <span m=''1500810''>interchanged.</span> <span m=''1501420''>What</span> <span m=''1501570''>we''re</span>
  <span m=''1501680''>doing</span> <span m=''1502050''>is</span> <span m=''1502610''>basically</span>
  <span m=''1503570''>turning</span> <span m=''1503950''>here</span> <span m=''1504300''>and</span>
  <span m=''1504380''>turning</span> <span m=''1504690''>here</span> <span m=''1505050''>instead</span>
  <span m=''1505450''>of</span> <span m=''1505940''>going</span> <span m=''1506180''>that</span>
  <span m=''1506410''>way</span> <span m=''1506730''>and</span> <span m=''1507020''>going</span>
  <span m=''1507230''>that</span> <span m=''1507460''>way.</span> <span m=''1508210''>And</span>
  <span m=''1508570''>whenever</span> <span m=''1508950''>you</span> <span m=''1509000''>have</span>
  <span m=''1509190''>two</span> <span m=''1509390''>pieces</span> <span m=''1509840''>like</span>
  <span m=''1510030''>this,</span> <span m=''1510240''>and</span> <span m=''1510350''>one</span>
  <span m=''1510510''>of</span> <span m=''1510580''>which</span> <span m=''1510760''>is</span>
  <span m=''1510860''>a</span> <span m=''1510920''>cycle,</span> <span m=''1511630''>you</span>
  <span m=''1511810''>will</span> <span m=''1511980''>do</span> <span m=''1512130''>a</span>
  <span m=''1512200''>merge.</span> <span m=''1513310''>Merging</span> <span m=''1513670''>can</span>
  <span m=''1513820''>only</span> <span m=''1514110''>help</span> <span m=''1514360''>us,</span>
  <span m=''1514600''>because</span> <span m=''1514780''>they''ll</span> <span m=''1514920''>get</span>
  <span m=''1515100''>bigger</span> <span m=''1515380''>and</span> <span m=''1515460''>bigger</span>
  <span m=''1515720''>and</span> <span m=''1515790''>bigger.</span> <span m=''1516496''>The</span>
  <span m=''1516850''>bigger</span> <span m=''1517170''>these</span> <span m=''1517310''>sets</span>
  <span m=''1517580''>of</span> <span m=''1517660''>constraints</span> <span m=''1518150''>are,</span>
  <span m=''1519200''>essentially,</span> <span m=''1519590''>the</span> <span m=''1519690''>better</span>
  <span m=''1519990''>chance</span> <span m=''1520380''>that you''ll</span> <span
  m=''1520610''>get</span> <span m=''1520810''>the</span> <span m=''1520880''>parity</span>
  <span m=''1521270''>right.</span> </p><p><span m=''1522370''>I</span> <span m=''1522460''>can</span>
  <span m=''1522620''>never--</span> <span m=''1523140''>and</span> <span m=''1523290''>this
  is</span> <span m=''1523590''>argued</span> <span m=''1523980''>in</span> <span
  m=''1524750''>the</span> <span m=''1524840''>notes,</span> <span m=''1525230''>but</span>
  <span m=''1525990''>few--</span> <span m=''1528450''>it</span> <span m=''1528540''>never</span>
  <span m=''1528740''>hurts</span> <span m=''1529030''>to</span> <span m=''1529420''>merge</span>
  <span m=''1529780''>something,</span> <span m=''1530575''>is</span> <span m=''1530880''>the</span>
  <span m=''1530960''>point.</span> <span m=''1531650''>And</span> <span m=''1531800''>if</span>
  <span m=''1531890''>you''re</span> <span m=''1532010''>lucky--</span> <span m=''1532340''>if</span>
  <span m=''1532450''>you,</span> <span m=''1532580''>say,</span> <span m=''1532760''>merge</span>
  <span m=''1533060''>two</span> <span m=''1533330''>odd</span> <span m=''1533570''>cycles--</span>
  <span m=''1534180''>they</span> <span m=''1534280''>will</span> <span m=''1534440''>become</span>
  <span m=''1535010''>even.</span> <span m=''1536320''>If</span> <span m=''1536530''>you</span>
  <span m=''1536670''>merge</span> <span m=''1537470''>with</span> <span m=''1537600''>a</span>
  <span m=''1537670''>path,</span> <span m=''1538280''>you''ll</span> <span m=''1538440''>become</span>
  <span m=''1538690''>a</span> <span m=''1538750''>path.</span> <span m=''1539320''>And</span>
  <span m=''1539460''>so</span> <span m=''1539660''>you''re</span> <span m=''1539820''>golden.</span>
  <span m=''1540270''>Paths</span> <span m=''1540570''>are</span> <span m=''1540670''>always</span>
  <span m=''1540930''>good.</span> <span m=''1541990''>And</span> <span m=''1542160''>so</span>
  <span m=''1542260''>this</span> <span m=''1542490''>thing</span> <span m=''1542680''>becomes</span>
  <span m=''1544450''>flat</span> <span m=''1544740''>foldable,</span> <span m=''1546170''>or</span>
  <span m=''1546530''>at</span> <span m=''1546620''>least</span> <span m=''1546790''>locally</span>
  <span m=''1547190''>flat</span> <span m=''1547600''>foldable.</span> <span m=''1548732''>And</span>
  <span m=''1549240''>we</span> <span m=''1549350''>can</span> <span m=''1549550''>mark</span>
  <span m=''1549820''>in</span> <span m=''1551505''>a</span> <span m=''1551910''>crease</span>
  <span m=''1552110''>pattern,</span> <span m=''1552440''>I</span> <span m=''1552510''>guess.</span>
  <span m=''1552840''>You</span> <span m=''1552930''>could</span> <span m=''1553080''>make</span>
  <span m=''1553290''>this--</span> <span m=''1554570''>that''s</span> <span m=''1554740''>going</span>
  <span m=''1554860''>to</span> <span m=''1554930''>be</span> <span m=''1555140''>hard</span>
  <span m=''1555370''>to</span> <span m=''1555460''>see,</span> <span m=''1555690''>I</span>
  <span m=''1555770''>think--</span> <span m=''1556760''>mountain,</span> <span m=''1558190''>valley,</span>
  <span m=''1558980''>mountain,</span> <span m=''1561180''>valley,</span> <span m=''1562230''>mountain--</span>
  <span m=''1563140''>oh,</span> <span m=''1563300''>sorry--</span> <span m=''1564330''>equals,</span>
  <span m=''1567200''>not</span> <span m=''1567520''>equals,</span> <span m=''1569680''>this</span>
  <span m=''1569940''>is</span> <span m=''1570110''>not</span> <span m=''1570480''>equals,</span>
  <span m=''1572390''>not</span> <span m=''1572650''>equals,</span> <span m=''1574260''>not</span>
  <span m=''1574520''>equals,</span> <span m=''1575870''>equals.</span> <span m=''1578710''>These</span>
  <span m=''1578970''>guys</span> <span m=''1579200''>are</span> <span m=''1579290''>free.</span>
  <span m=''1579650''>So</span> <span m=''1579800''>you</span> <span m=''1580040''>can</span>
  <span m=''1580240''>make</span> <span m=''1580430''>one</span> <span m=''1580570''>of</span>
  <span m=''1580640''>them</span> <span m=''1580750''>mountain,</span> <span m=''1581160''>one
  of---</span> <span m=''1582240''>you can make</span> <span m=''1582610''>them all</span>
  <span m=''1582690''>mountains,</span> <span m=''1583380''>I</span> <span m=''1583440''>guess.</span>
  <span m=''1584220''>Or</span> <span m=''1584530''>not.</span> <span m=''1585790''>OK.</span>
  <span m=''1586050''>This</span> <span m=''1586210''>is</span> <span m=''1586380''>a</span>
  <span m=''1586950''>locally</span> <span m=''1587360''>valid</span> <span m=''1588180''>flat</span>
  <span m=''1588530''>folding.</span> <span m=''1589330''>And</span> <span m=''1589850''>it''s</span>
  <span m=''1590010''>hard</span> <span m=''1590190''>to</span> <span m=''1590260''>tell</span>
  <span m=''1590500''>whether</span> <span m=''1590760''>it</span> <span m=''1590820''>actually</span>
  <span m=''1591140''>works</span> <span m=''1592240''>except</span> <span m=''1592550''>by</span>
  <span m=''1592850''>folding</span> <span m=''1593150''>it.</span> <span m=''1593330''>So</span>
  <span m=''1594340''>here</span> <span m=''1594710''>I</span> <span m=''1594810''>made</span>
  <span m=''1595090''>one.</span> <span m=''1596180''>That''s</span> <span m=''1596580''>the</span>
  <span m=''1597710''>top</span> <span m=''1597910''>side,</span> <span m=''1598210''>I</span>
  <span m=''1598270''>think.</span> <span m=''1599540''>Ideally</span> <span m=''1599970''>I</span>
  <span m=''1600020''>got</span> <span m=''1600290''>the</span> <span m=''1600390''>same</span>
  <span m=''1600960''>crease</span> <span m=''1601230''>pattern</span> <span m=''1601570''>as</span>
  <span m=''1601720''>here.</span> <span m=''1601870''>The</span> <span m=''1602010''>reds</span>
  <span m=''1602290''>are</span> <span m=''1602370''>mountains.</span> <span m=''1604210''>Looks</span>
  <span m=''1604520''>the</span> <span m=''1604640''>same.</span> <span m=''1606250''>And</span>
  <span m=''1606430''>then--</span> </p><p><span m=''1607540''>It''s</span> <span
  m=''1607770''>clear</span> <span m=''1607980''>that this</span> <span m=''1608200''>pattern
  is</span> <span m=''1608540''>flat foldable,</span> <span m=''1608960''>right?</span>
  <span m=''1609270''>You just</span> <span m=''1609550''>simple</span> <span m=''1609880''>fold</span>
  <span m=''1610110''>here,</span> <span m=''1611100''>and</span> <span m=''1611290''>then</span>
  <span m=''1611400''>you''ve</span> <span m=''1611540''>got</span> <span m=''1611700''>a</span>
  <span m=''1611760''>single</span> <span m=''1612050''>vertex</span> <span m=''1612490''>and</span>
  <span m=''1612570''>that</span> <span m=''1612720''>single</span> <span m=''1612930''>vertex</span>
  <span m=''1613300''>is</span> <span m=''1613400''>flat</span> <span m=''1613600''>foldable.</span>
  <span m=''1614480''>But</span> <span m=''1615040''>this</span> <span m=''1615410''>does</span>
  <span m=''1615570''>not</span> <span m=''1615880''>do</span> <span m=''1616150''>that.</span>
  <span m=''1616510''>It does</span> <span m=''1616650''>a</span> <span m=''1616710''>kind</span>
  <span m=''1616890''>of</span> <span m=''1616970''>twist.</span> <span m=''1617905''>It''s</span>
  <span m=''1618170''>kind</span> <span m=''1618330''>of a</span> <span m=''1618510''>fun</span>
  <span m=''1618870''>mountain</span> <span m=''1619350''>valley</span> <span m=''1619620''>assignment</span>
  <span m=''1620030''>for it.</span> <span m=''1622420''>So</span> <span m=''1624030''>in</span>
  <span m=''1624130''>this</span> <span m=''1624270''>case</span> <span m=''1624480''>it</span>
  <span m=''1624570''>works.</span> <span m=''1624860''>In</span> <span m=''1624960''>general,</span>
  <span m=''1625360''>you</span> <span m=''1625480''>might</span> <span m=''1625670''>get</span>
  <span m=''1625850''>some</span> <span m=''1626060''>weird</span> <span m=''1626790''>mountain</span>
  <span m=''1627160''>valley</span> <span m=''1627530''>assignment that</span> <span
  m=''1627940''>doesn''t</span> <span m=''1628180''>work.</span> <span m=''1628480''>But</span>
  <span m=''1629870''>something</span> <span m=''1630250''>simple</span> <span m=''1630540''>like</span>
  <span m=''1630730''>this</span> <span m=''1630910''>pattern,</span> <span m=''1631220''>which</span>
  <span m=''1631530''>has</span> <span m=''1631990''>four</span> <span m=''1632240''>vertices,</span>
  <span m=''1633820''>always</span> <span m=''1633910''>will.</span> </p><p><span
  m=''1635345''>Any</span> <span m=''1635730''>more</span> <span m=''1636090''>questions</span>
  <span m=''1636480''>about</span> <span m=''1636700''>local</span> <span m=''1636930''>foldability?</span>
  <span m=''1637440''>That</span> <span m=''1637610''>gives</span> <span m=''1637750''>you</span>
  <span m=''1637830''>at</span> <span m=''1637900''>least</span> <span m=''1638150''>an</span>
  <span m=''1638350''>idea</span> <span m=''1638710''>of</span> <span m=''1638810''>what</span>
  <span m=''1639030''>the</span> <span m=''1639120''>merges</span> <span m=''1639500''>look</span>
  <span m=''1639680''>like.</span> <span m=''1640530''>It''s</span> <span m=''1640700''>hard</span>
  <span m=''1640940''>to</span> <span m=''1641010''>draw a</span> <span m=''1641240''>huge</span>
  <span m=''1641560''>example,</span> <span m=''1642140''>but--</span> <span m=''1642550''>Yeah.</span>
  </p><p><span m=''1642960''>AUDIENCE: So the generic</span> <span m=''1643370''>case,</span>
  <span m=''1643806''>you don''t</span> <span m=''1644242''>really have</span> <span
  m=''1644678''>a choice</span> <span m=''1645114''>at any--</span> </p><p><span m=''1645550''>PROFESSOR:
  In the</span> <span m=''1645680''>generic</span> <span m=''1646070''>case</span>
  <span m=''1646280''>you</span> <span m=''1646360''>have</span> <span m=''1646460''>no</span>
  <span m=''1646650''>choices,</span> <span m=''1647280''>and</span> <span m=''1647430''>so</span>
  <span m=''1647690''>you''ve</span> <span m=''1647920''>got</span> <span m=''1648190''>to--</span>
  <span m=''1649370''>you</span> <span m=''1649510''>just</span> <span m=''1649850''>check,</span>
  <span m=''1650730''>does</span> <span m=''1650910''>it</span> <span m=''1650980''>work.</span>
  <span m=''1651810''>And</span> <span m=''1652080''>if</span> <span m=''1652180''>it--</span>
  </p><p><span m=''1652640''>AUDIENCE: If you</span> <span m=''1653136''>have an odd</span>
  <span m=''1654624''>number</span> <span m=''1655120''>of</span> <span m=''1655616''>faces,</span>
  <span m=''1656112''>odd number</span> <span m=''1656608''>of sides,</span> <span
  m=''1657104''>then it''s not</span> <span m=''1657600''>going to work?</span> </p><p><span
  m=''1658340''>PROFESSOR: If</span> <span m=''1658500''>you</span> <span m=''1658590''>have</span>
  <span m=''1658780''>a</span> <span m=''1658850''>face</span> <span m=''1659250''>with</span>
  <span m=''1659400''>an</span> <span m=''1659470''>odd</span> <span m=''1659600''>number
  of</span> <span m=''1659950''>sides,</span> <span m=''1660140''>that</span> <span
  m=''1660320''>might</span> <span m=''1660550''>be</span> <span m=''1660680''>fine.</span>
  <span m=''1661180''>It</span> <span m=''1661300''>depends</span> <span m=''1661690''>on</span>
  <span m=''1661860''>these</span> <span m=''1662220''>assignments,</span> <span m=''1662760''>whether</span>
  <span m=''1662950''>they''re</span> <span m=''1663100''>not</span> <span m=''1663290''>equal
  or</span> <span m=''1663620''>equals.</span> <span m=''1665400''>Like</span> <span
  m=''1665560''>if</span> <span m=''1665690''>this</span> <span m=''1665900''>were</span>
  <span m=''1666690''>an</span> <span m=''1666750''>equal</span> <span m=''1667160''>sign,</span>
  <span m=''1668070''>then</span> <span m=''1669130''>you''d</span> <span m=''1669330''>be</span>
  <span m=''1670230''>happy.</span> <span m=''1670980''>And</span> <span m=''1671140''>that</span>
  <span m=''1671290''>would</span> <span m=''1671400''>happen,</span> <span m=''1671850''>for</span>
  <span m=''1671880''>example,</span> <span m=''1672320''>if</span> <span m=''1673750''>you</span>
  <span m=''1673880''>move</span> <span m=''1674180''>these</span> <span m=''1674380''>creases</span>
  <span m=''1674720''>to</span> <span m=''1674820''>be</span> <span m=''1674950''>very</span>
  <span m=''1675190''>small.</span> <span m=''1675600''>I''d</span> <span m=''1675690''>have</span>
  <span m=''1675850''>to</span> <span m=''1675950''>also</span> <span m=''1676170''>make</span>
  <span m=''1676350''>this</span> <span m=''1676500''>one</span> <span m=''1677150''>proportionally</span>
  <span m=''1677670''>big,</span> <span m=''1678680''>which</span> <span m=''1678940''>is</span>
  <span m=''1679070''>possible</span> <span m=''1679440''>if</span> <span m=''1679560''>I</span>
  <span m=''1679600''>move</span> <span m=''1679800''>this</span> <span m=''1679960''>vertex</span>
  <span m=''1680320''>way</span> <span m=''1680490''>over</span> <span m=''1680660''>here.</span>
  <span m=''1681400''>I''ll</span> <span m=''1681450''>have</span> <span m=''1681620''>a</span>
  <span m=''1681680''>triangle.</span> <span m=''1683270''>This</span> <span m=''1683390''>will</span>
  <span m=''1683480''>have</span> <span m=''1683580''>a</span> <span m=''1683660''>big</span>
  <span m=''1683910''>angle.</span> <span m=''1684310''>Then</span> <span m=''1684460''>I</span>
  <span m=''1684510''>can</span> <span m=''1684620''>have</span> <span m=''1684780''>a</span>
  <span m=''1684830''>small</span> <span m=''1685210''>angle</span> <span m=''1685430''>here</span>
  <span m=''1686190''>and</span> <span m=''1686440''>these</span> <span m=''1686740''>two</span>
  <span m=''1687040''>guys</span> <span m=''1687310''>will</span> <span m=''1687400''>be</span>
  <span m=''1688000''>made</span> <span m=''1688320''>not</span> <span m=''1688590''>equal</span>
  <span m=''1688970''>and these</span> <span m=''1689160''>two</span> <span m=''1689370''>will
  be</span> <span m=''1689500''>made</span> <span m=''1689680''>equal, and</span>
  <span m=''1690070''>then</span> <span m=''1690230''>the</span> <span m=''1690320''>parity''s</span>
  <span m=''1690760''>fine.</span> <span m=''1692400''>So</span> <span m=''1692640''>if</span>
  <span m=''1693890''>you</span> <span m=''1694150''>have</span> <span m=''1694350''>a</span>
  <span m=''1694430''>cycle</span> <span m=''1695280''>with</span> <span m=''1695420''>an</span>
  <span m=''1696160''>odd</span> <span m=''1696340''>number</span> <span m=''1696740''>of</span>
  <span m=''1696800''>not</span> <span m=''1697010''>equals,</span> <span m=''1697380''>then</span>
  <span m=''1697500''>you''re</span> <span m=''1698010''>screwed.</span> <span m=''1698820''>In
  the</span> <span m=''1698920''>generic</span> <span m=''1699240''>case</span> <span
  m=''1699460''>there''s</span> <span m=''1699560''>nothing</span> <span m=''1699820''>you</span>
  <span m=''1699940''>can</span> <span m=''1700070''>do.</span> </p><p><span m=''1700860''>When</span>
  <span m=''1700990''>you</span> <span m=''1701050''>have</span> <span m=''1701310''>equal</span>
  <span m=''1701770''>angles,</span> <span m=''1702350''>when</span> <span m=''1702460''>you</span>
  <span m=''1702520''>had</span> <span m=''1702700''>a</span> <span m=''1702760''>choice,</span>
  <span m=''1703570''>you</span> <span m=''1703670''>go</span> <span m=''1703820''>back</span>
  <span m=''1704160''>and</span> <span m=''1704260''>check</span> <span m=''1704500''>whether</span>
  <span m=''1704710''>the</span> <span m=''1705220''>choices</span> <span m=''1705630''>would</span>
  <span m=''1705770''>do</span> <span m=''1705900''>merges.</span> <span m=''1706310''>If</span>
  <span m=''1706480''>you</span> <span m=''1706570''>do,</span> <span m=''1706960''>you</span>
  <span m=''1707350''>do</span> <span m=''1707600''>them.</span> <span m=''1707860''>Overall,</span>
  <span m=''1708300''>this</span> <span m=''1708450''>turns</span> <span m=''1708670''>out
  to</span> <span m=''1708910''>take</span> <span m=''1709090''>a</span> <span m=''1709130''>linear</span>
  <span m=''1709420''>time</span> <span m=''1709760''>if</span> <span m=''1709860''>you''re</span>
  <span m=''1710000''>careful,</span> <span m=''1710820''>because</span> <span m=''1712430''>you</span>
  <span m=''1712590''>can</span> <span m=''1713120''>only</span> <span m=''1713420''>merge</span>
  <span m=''1713840''>so</span> <span m=''1713960''>many</span> <span m=''1714210''>times.</span>
  <span m=''1714640''>You have</span> <span m=''1714800''>at</span> <span m=''1714900''>most</span>
  <span m=''1715190''>n</span> <span m=''1715390''>parts</span> <span m=''1716330''>and</span>
  <span m=''1716620''>each</span> <span m=''1716810''>merge--</span> <span m=''1719565''>with</span>
  <span m=''1720030''>some</span> <span m=''1720330''>care.</span> <span m=''1720650''>You
  need</span> <span m=''1720790''>fancy</span> <span m=''1721080''>data</span> <span
  m=''1721280''>structures</span> <span m=''1721660''>to</span> <span m=''1721750''>get</span>
  <span m=''1721930''>this</span> <span m=''1722080''>to</span> <span m=''1722180''>work.</span>
  <span m=''1722850''>You need</span> <span m=''1723190''>find</span> <span m=''1723480''>stuff,</span>
  <span m=''1724260''>but</span> <span m=''1724390''>then</span> <span m=''1724530''>you''ll</span>
  <span m=''1724650''>get</span> <span m=''1725060''>linear</span> <span m=''1725360''>time</span>
  <span m=''1725600''>over</span> <span m=''1725800''>all.</span> <span m=''1727230''>Other</span>
  <span m=''1727390''>questions?</span> </p><p><span m=''1728974''>AUDIENCE: So what''s</span>
  <span m=''1729426''>the definition</span> <span m=''1730330''>of</span> <span m=''1730782''>merging,</span>
  <span m=''1731234''>again?</span> </p><p><span m=''1732140''>PROFESSOR: So</span>
  <span m=''1732270''>the</span> <span m=''1732360''>definition</span> <span m=''1732675''>of</span>
  <span m=''1732990''>merging</span> <span m=''1733750''>is</span> <span m=''1734190''>you</span>
  <span m=''1734360''>look</span> <span m=''1734540''>at</span> <span m=''1734750''>every</span>
  <span m=''1735060''>time</span> <span m=''1735330''>you</span> <span m=''1735410''>had</span>
  <span m=''1735590''>a</span> <span m=''1735670''>choice</span> <span m=''1736200''>in</span>
  <span m=''1736370''>running</span> <span m=''1736710''>this</span> <span m=''1736890''>algorithm--</span>
  <span m=''1739130''>which</span> <span m=''1739410''>you</span> <span m=''1739550''>have</span>
  <span m=''1739840''>to</span> <span m=''1740680''>not</span> <span m=''1740880''>just</span>
  <span m=''1741030''>run</span> <span m=''1741170''>this</span> <span m=''1741250''>algorithm</span>
  <span m=''1741630''>but</span> <span m=''1741700''>you</span> <span m=''1741780''>have</span>
  <span m=''1741910''>to</span> <span m=''1742020''>maintain</span> <span m=''1742630''>all</span>
  <span m=''1742860''>the</span> <span m=''1742960''>choices</span> <span m=''1743370''>that</span>
  <span m=''1743470''>you</span> <span m=''1743610''>had</span> <span m=''1743810''>made.</span>
  <span m=''1745260''>So</span> <span m=''1745410''>whenever</span> <span m=''1745660''>you</span>
  <span m=''1745780''>had</span> <span m=''1746010''>two</span> <span m=''1746390''>equal</span>
  <span m=''1746780''>angles--</span> <span m=''1747010''>in</span> <span m=''1747080''>general,</span>
  <span m=''1747350''>the</span> <span m=''1747460''>algorithm</span> <span m=''1747860''>is</span>
  <span m=''1748940''>you</span> <span m=''1749170''>look</span> <span m=''1749360''>at</span>
  <span m=''1749430''>a</span> <span m=''1749500''>sequence</span> <span m=''1749920''>of</span>
  <span m=''1750020''>equal</span> <span m=''1750360''>angles.</span> <span m=''1750880''>The</span>
  <span m=''1751250''>algorithm</span> <span m=''1751600''>maybe</span> <span m=''1751830''>chooses</span>
  <span m=''1752140''>the</span> <span m=''1752230''>first</span> <span m=''1752560''>one,</span>
  <span m=''1752810''>but</span> <span m=''1753080''>you</span> <span m=''1753230''>could</span>
  <span m=''1753350''>have</span> <span m=''1753470''>chosen</span> <span m=''1753820''>any.</span>
  <span m=''1754750''>You</span> <span m=''1754900''>see</span> <span m=''1755240''>for</span>
  <span m=''1755460''>each</span> <span m=''1755680''>of</span> <span m=''1755740''>the</span>
  <span m=''1755890''>other</span> <span m=''1756080''>possibilities,</span> <span
  m=''1756950''>would</span> <span m=''1757170''>that</span> <span m=''1757410''>end</span>
  <span m=''1757640''>up</span> <span m=''1758630''>combining</span> <span m=''1759270''>two</span>
  <span m=''1759440''>of</span> <span m=''1759500''>the</span> <span m=''1759600''>components.</span>
  <span m=''1761200''>So</span> <span m=''1762640''>the</span> <span m=''1762810''>constraints</span>
  <span m=''1763140''>sort</span> <span m=''1763470''>of</span> <span m=''1764030''>join</span>
  <span m=''1764340''>together</span> <span m=''1764840''>either</span> <span m=''1765150''>into</span>
  <span m=''1765380''>cycles</span> <span m=''1766300''>or</span> <span m=''1766440''>into</span>
  <span m=''1766580''>paths,</span> <span m=''1767910''>like</span> <span m=''1768040''>this</span>
  <span m=''1768270''>guy.</span> <span m=''1769330''>And</span> <span m=''1769690''>we</span>
  <span m=''1769790''>just</span> <span m=''1770000''>check,</span> <span m=''1770310''>if</span>
  <span m=''1770500''>I</span> <span m=''1770560''>do</span> <span m=''1770710''>this</span>
  <span m=''1770900''>other</span> <span m=''1771140''>change,</span> <span m=''1771480''>does</span>
  <span m=''1771680''>it</span> <span m=''1771780''>end</span> <span m=''1771970''>up</span>
  <span m=''1772540''>combining</span> <span m=''1773040''>two</span> <span m=''1773180''>of</span>
  <span m=''1773230''>those</span> <span m=''1773410''>components?</span> <span m=''1774230''>Before</span>
  <span m=''1774580''>I</span> <span m=''1774630''>had</span> <span m=''1774960''>1,</span>
  <span m=''1775890''>2,</span> <span m=''1776470''>3,</span> <span m=''1777080''>4</span>
  <span m=''1777480''>components.</span> <span m=''1778500''>Now</span> <span m=''1778680''>I</span>
  <span m=''1778760''>only</span> <span m=''1779020''>have</span> <span m=''1779260''>3</span>
  <span m=''1779470''>components.</span> <span m=''1780670''>So</span> <span m=''1781160''>just</span>
  <span m=''1781310''>see</span> <span m=''1781470''>what</span> <span m=''1781630''>happens.</span>
  <span m=''1782190''>If</span> <span m=''1782750''>that</span> <span m=''1782930''>decreases
  the</span> <span m=''1783380''>number</span> <span m=''1783580''>of</span> <span
  m=''1783640''>components</span> <span m=''1784050''>I</span> <span m=''1784110''>do</span>
  <span m=''1784310''>it.</span> <span m=''1784920''>And</span> <span m=''1785130''>you
  can</span> <span m=''1785300''>guarantee</span> <span m=''1785700''>this</span>
  <span m=''1785870''>never</span> <span m=''1786080''>hurts</span> <span m=''1786330''>you.</span>
  <span m=''1787370''>Keep</span> <span m=''1787600''>merging</span> <span m=''1787950''>components</span>
  <span m=''1788310''>until</span> <span m=''1788490''>you</span> <span m=''1788590''>can''t</span>
  <span m=''1788870''>anymore.</span> <span m=''1790520''>And</span> <span m=''1790600''>then</span>
  <span m=''1791030''>either it</span> <span m=''1791380''>works</span> <span m=''1791720''>and</span>
  <span m=''1791940''>you''ve</span> <span m=''1792060''>got</span> <span m=''1793030''>no</span>
  <span m=''1793180''>parity</span> <span m=''1793660''>problems</span> <span m=''1794210''>or</span>
  <span m=''1794310''>no</span> <span m=''1794450''>cycles,</span> <span m=''1795360''>or
  it</span> <span m=''1795510''>doesn''t</span> <span m=''1795790''>work.</span> <span
  m=''1795980''>If it</span> <span m=''1796090''>doesn''t</span> <span m=''1796350''>work,</span>
  <span m=''1796900''>there</span> <span m=''1797140''>is</span> <span m=''1797270''>no</span>
  <span m=''1797440''>local</span> <span m=''1798400''>foldable</span> <span m=''1798830''>assignment.</span>
  </p><p><span m=''1799280''>Yeah.</span> </p><p><span m=''1799722''>AUDIENCE: When
  you say</span> <span m=''1800164''>it''s linear,</span> <span m=''1800606''>are
  you counting</span> <span m=''1801210''>vertices</span> <span m=''1801670''>or</span>
  <span m=''1802160''>edges?</span> </p><p><span m=''1803960''>PROFESSOR: Let''s</span>
  <span m=''1804170''>say</span> <span m=''1804570''>number of</span> <span m=''1804840''>vertices</span>
  <span m=''1805210''>plus</span> <span m=''1805500''>edges.</span> <span m=''1805910''>That''s</span>
  <span m=''1806150''>the</span> <span m=''1806240''>safe</span> <span m=''1806730''>way</span>
  <span m=''1807220''>to</span> <span m=''1807540''>define</span> <span m=''1807920''>n</span>
  <span m=''1808390''>and then</span> <span m=''1809460''>linear</span> <span m=''1809870''>in</span>
  <span m=''1809950''>that.</span> <span m=''1810520''>Or</span> <span m=''1811260''>if</span>
  <span m=''1811470''>you</span> <span m=''1811640''>count</span> <span m=''1811880''>the</span>
  <span m=''1811980''>endpoints</span> <span m=''1812550''>here</span> <span m=''1812760''>it</span>
  <span m=''1812840''>doesn''t</span> <span m=''1813180''>matter</span> <span m=''1814020''>whether</span>
  <span m=''1814210''>you</span> <span m=''1814270''>just</span> <span m=''1814440''>count</span>
  <span m=''1814630''>vertices</span> <span m=''1815030''>or</span> <span m=''1815140''>edges.</span>
  <span m=''1816410''>The sum</span> <span m=''1816780''>of the</span> <span m=''1816870''>two</span>
  <span m=''1817080''>is</span> <span m=''1817190''>always</span> <span m=''1817370''>safe.</span>
  <span m=''1819780''>So</span> <span m=''1820050''>n</span> <span m=''1820260''>usually</span>
  <span m=''1820570''>just</span> <span m=''1820760''>means</span> <span m=''1820980''>the</span>
  <span m=''1821080''>size</span> <span m=''1821480''>of</span> <span m=''1821620''>the</span>
  <span m=''1821750''>input,</span> <span m=''1822300''>and</span> <span m=''1822570''>those</span>
  <span m=''1822720''>vertices</span> <span m=''1823130''>and</span> <span m=''1823200''>edges,</span>
  <span m=''1823610''>so</span> <span m=''1823780''>why</span> <span m=''1823940''>not</span>
  <span m=''1823980''>just</span> <span m=''1824170''>count</span> <span m=''1824410''>them
  both.</span> <span m=''1827440''>Other</span> <span m=''1827610''>questions?</span>
  <span m=''1829410''>Cool.</span> </p><p><span m=''1830580''>So</span> <span m=''1833220''>that''s</span>
  <span m=''1833500''>local</span> <span m=''1833760''>foldability.</span> <span m=''1834750''>I
  just</span> <span m=''1834940''>have a</span> <span m=''1835205''>few</span> <span
  m=''1835470''>more</span> <span m=''1836650''>little</span> <span m=''1836830''>things</span>
  <span m=''1837310''>and then</span> <span m=''1837590''>you</span> <span m=''1837810''>can</span>
  <span m=''1837960''>ask</span> <span m=''1838140''>more</span> <span m=''1838290''>questions.</span>
  <span m=''1840430''>Oh,</span> <span m=''1840690''>sorry.</span> <span m=''1840830''>I</span>
  <span m=''1840920''>have</span> <span m=''1841050''>one</span> <span m=''1841220''>more</span>
  <span m=''1841440''>example.</span> <span m=''1842070''>I forgot.</span> </p><p><span
  m=''1843220''>This</span> <span m=''1843510''>is</span> <span m=''1843620''>an</span>
  <span m=''1843670''>example</span> <span m=''1844020''>where</span> <span m=''1844130''>everything</span>
  <span m=''1844440''>works</span> <span m=''1844710''>fine.</span> <span m=''1845000''>You</span>
  <span m=''1845080''>don''t</span> <span m=''1845240''>get</span> <span m=''1845370''>any</span>
  <span m=''1845570''>cycles.</span> <span m=''1846170''>But</span> <span m=''1846320''>it''s</span>
  <span m=''1846480''>kind</span> <span m=''1846660''>of</span> <span m=''1846740''>a</span>
  <span m=''1846810''>fun</span> <span m=''1847010''>example.</span> <span m=''1847660''>The</span>
  <span m=''1847770''>crane.</span> <span m=''1849540''>I''d</span> <span m=''1849660''>never</span>
  <span m=''1849920''>analyzed</span> <span m=''1850280''>it</span> <span m=''1850360''>before,</span>
  <span m=''1850720''>so</span> <span m=''1851300''>I</span> <span m=''1851690''>spent</span>
  <span m=''1851940''>the</span> <span m=''1852010''>time</span> <span m=''1852220''>to</span>
  <span m=''1852300''>draw</span> <span m=''1852670''>one</span> <span m=''1852840''>of</span>
  <span m=''1852900''>these</span> <span m=''1853040''>pictures.</span> <span m=''1854030''>So</span>
  <span m=''1854160''>first</span> <span m=''1855010''>I</span> <span m=''1855110''>just</span>
  <span m=''1855290''>put</span> <span m=''1855430''>a</span> <span m=''1855470''>bunch</span>
  <span m=''1855700''>of</span> <span m=''1855760''>circles</span> <span m=''1856160''>down,</span>
  <span m=''1856830''>and</span> <span m=''1857020''>I</span> <span m=''1857090''>look</span>
  <span m=''1857320''>for</span> <span m=''1858190''>things</span> <span m=''1858420''>that</span>
  <span m=''1858520''>are</span> <span m=''1858610''>forced,</span> <span m=''1859310''>just</span>
  <span m=''1859730''>because</span> <span m=''1860040''>that</span> <span m=''1860640''>is</span>
  <span m=''1860830''>more</span> <span m=''1861040''>interesting.</span> <span m=''1861720''>I</span>
  <span m=''1861820''>tried</span> <span m=''1862060''>to</span> <span m=''1862170''>make</span>
  <span m=''1862360''>it</span> <span m=''1862430''>as</span> <span m=''1862540''>bad</span>
  <span m=''1862780''>as</span> <span m=''1862890''>possible.</span> <span m=''1863380''>It
  turns out</span> <span m=''1863580''>I</span> <span m=''1863710''>couldn''t</span>
  <span m=''1863950''>make</span> <span m=''1864120''>it</span> <span m=''1864200''>that</span>
  <span m=''1864680''>bad.</span> <span m=''1865010''>But</span> <span m=''1865170''>this</span>
  <span m=''1865370''>guy''s</span> <span m=''1865650''>forced,</span> <span m=''1866120''>because</span>
  <span m=''1866310''>it''s</span> <span m=''1866630''>the</span> <span m=''1866800''>only</span>
  <span m=''1867070''>locally</span> <span m=''1867410''>smallest</span> <span m=''1867850''>angle.</span>
  <span m=''1869490''>And</span> <span m=''1869700''>then</span> <span m=''1869840''>it''s</span>
  <span m=''1870030''>symmetrical</span> <span m=''1870640''>around.</span> <span
  m=''1871010''>So</span> <span m=''1872900''>this</span> <span m=''1873140''>guy''s</span>
  <span m=''1873430''>forced.</span> <span m=''1874770''>Four of</span> <span m=''1875120''>them</span>
  <span m=''1875270''>should</span> <span m=''1875420''>be</span> <span m=''1875550''>forced.</span>
  <span m=''1876800''>If I</span> <span m=''1877070''>advance,</span> <span m=''1877700''>yeah.</span>
  <span m=''1878840''>This</span> <span m=''1879060''>one,</span> <span m=''1879420''>this</span>
  <span m=''1879640''>one.</span> <span m=''1880150''>Those</span> <span m=''1880390''>are</span>
  <span m=''1880510''>all</span> <span m=''1880630''>forced</span> <span m=''1880910''>to</span>
  <span m=''1881000''>be</span> <span m=''1881100''>not</span> <span m=''1881290''>equal.</span>
  <span m=''1881770''>The rest</span> <span m=''1882080''>are</span> <span m=''1882330''>equal.</span>
  <span m=''1882610''>The</span> <span m=''1882750''>other</span> <span m=''1882960''>guys</span>
  <span m=''1883210''>have</span> <span m=''1883430''>ambiguity.</span> <span m=''1885130''>And</span>
  <span m=''1885350''>I</span> <span m=''1885860''>tried.</span> <span m=''1886160''>I</span>
  <span m=''1886250''>thought</span> <span m=''1886470''>this</span> <span m=''1886640''>would</span>
  <span m=''1886720''>be</span> <span m=''1886840''>a</span> <span m=''1886880''>great</span>
  <span m=''1887120''>place</span> <span m=''1887310''>to</span> <span m=''1887410''>find</span>
  <span m=''1887620''>the</span> <span m=''1887680''>cycle</span> <span m=''1888160''>and</span>
  <span m=''1888230''>then</span> <span m=''1888310''>we</span> <span m=''1888390''>could</span>
  <span m=''1888530''>resolve the</span> <span m=''1889000''>cycle,</span> <span m=''1889460''>because</span>
  <span m=''1889650''>I</span> <span m=''1889720''>know</span> <span m=''1889880''>this</span>
  <span m=''1890010''>should</span> <span m=''1890170''>work</span> <span m=''1890750''>in</span>
  <span m=''1890910''>the</span> <span m=''1891040''>end,</span> <span m=''1891990''>but</span>
  <span m=''1892900''>I</span> <span m=''1893040''>couldn''t</span> <span m=''1893450''>make</span>
  <span m=''1893640''>a</span> <span m=''1893700''>cycle.</span> <span m=''1894370''>It''s
  not</span> <span m=''1894680''>possible,</span> <span m=''1896240''>because</span>
  <span m=''1896450''>there''s</span> <span m=''1897010''>sort</span> <span m=''1897170''>of</span>
  <span m=''1897260''>this</span> <span m=''1897440''>cut</span> <span m=''1897680''>point</span>
  <span m=''1897950''>here.</span> <span m=''1898980''>And</span> <span m=''1899880''>you</span>
  <span m=''1900680''>once</span> <span m=''1900930''>you</span> <span m=''1901000''>go</span>
  <span m=''1901120''>to</span> <span m=''1901200''>one</span> <span m=''1901380''>side</span>
  <span m=''1901580''>of</span> <span m=''1901620''>the</span> <span m=''1901690''>pattern,</span>
  <span m=''1902000''>you</span> <span m=''1902110''>can''t</span> <span m=''1902300''>come</span>
  <span m=''1902460''>back</span> <span m=''1902690''>to</span> <span m=''1902790''>the</span>
  <span m=''1902930''>other</span> <span m=''1903120''>side.</span> </p><p><span m=''1904080''>I</span>
  <span m=''1904180''>could</span> <span m=''1904410''>make</span> <span m=''1904580''>a</span>
  <span m=''1904650''>really</span> <span m=''1905040''>long</span> <span m=''1905280''>path</span>
  <span m=''1905670''>though.</span> <span m=''1906220''>So I</span> <span m=''1906475''>chose--</span>
  <span m=''1906730''>there''s</span> <span m=''1906870''>a</span> <span m=''1906920''>lot</span>
  <span m=''1907060''>of</span> <span m=''1907120''>choices</span> <span m=''1907550''>here,</span>
  <span m=''1908240''>but</span> <span m=''1908290''>the</span> <span m=''1908390''>algorithm</span>
  <span m=''1908670''>just</span> <span m=''1908880''>chooses</span> <span m=''1909190''>one.</span>
  <span m=''1909410''>I</span> <span m=''1909490''>tried</span> <span m=''1909690''>to</span>
  <span m=''1909810''>make</span> <span m=''1910020''>the</span> <span m=''1910110''>longest</span>
  <span m=''1910590''>path</span> <span m=''1910900''>I</span> <span m=''1910980''>could.</span>
  <span m=''1911400''>It''s kind</span> <span m=''1911820''>of a</span> <span m=''1912180''>fun</span>
  <span m=''1912460''>puzzle.</span> <span m=''1913690''>Not</span> <span m=''1913850''>that</span>
  <span m=''1913980''>hard</span> <span m=''1914230''>to</span> <span m=''1914310''>solve.</span>
  <span m=''1915350''>It</span> <span m=''1915570''>gets</span> <span m=''1915740''>a</span>
  <span m=''1915790''>little</span> <span m=''1915960''>hard</span> <span m=''1916150''>to</span>
  <span m=''1916210''>draw</span> <span m=''1916550''>these</span> <span m=''1916650''>pairings.</span>
  <span m=''1917030''>Here</span> <span m=''1917210''>these</span> <span m=''1917500''>two</span>
  <span m=''1917640''>guys</span> <span m=''1917900''>are</span> <span m=''1917980''>paired</span>
  <span m=''1918240''>together</span> <span m=''1918660''>as</span> <span m=''1918770''>not</span>
  <span m=''1918940''>equal.</span> <span m=''1919260''>We</span> <span m=''1919340''>crimp</span>
  <span m=''1919610''>that</span> <span m=''1919880''>first.</span> <span m=''1920870''>Then</span>
  <span m=''1921150''>let''s</span> <span m=''1921340''>say</span> <span m=''1921470''>we</span>
  <span m=''1921610''>crimp</span> <span m=''1921930''>these</span> <span m=''1922210''>two.</span>
  <span m=''1923000''>Then</span> <span m=''1923170''>we''ve</span> <span m=''1923300''>got</span>
  <span m=''1923530''>two</span> <span m=''1923760''>angles</span> <span m=''1924110''>here,</span>
  <span m=''1924330''>each</span> <span m=''1924570''>of</span> <span m=''1924670''>which</span>
  <span m=''1924890''>I</span> <span m=''1924950''>think</span> <span m=''1925160''>is</span>
  <span m=''1925300''>90</span> <span m=''1925680''>degrees</span> <span m=''1926210''>after</span>
  <span m=''1926480''>you</span> <span m=''1926590''>do</span> <span m=''1926720''>the</span>
  <span m=''1926830''>crimps.</span> <span m=''1928320''>And</span> <span m=''1928550''>so</span>
  <span m=''1929030''>these</span> <span m=''1929380''>two</span> <span m=''1929600''>guys</span>
  <span m=''1929940''>have</span> <span m=''1930140''>to</span> <span m=''1930250''>be</span>
  <span m=''1930490''>equal.</span> <span m=''1930820''>That''s</span> <span m=''1931060''>what</span>
  <span m=''1931180''>this</span> <span m=''1931440''>notation</span> <span m=''1931900''>means.</span>
  <span m=''1933430''>So</span> <span m=''1933510''>here</span> <span m=''1933720''>there</span>
  <span m=''1934030''>were,</span> <span m=''1934170''>I</span> <span m=''1934370''>think</span>
  <span m=''1934550''>four</span> <span m=''1934810''>different</span> <span m=''1935090''>possibilities.</span>
  <span m=''1936500''>And</span> <span m=''1936640''>if</span> <span m=''1936760''>you</span>
  <span m=''1937090''>trace</span> <span m=''1937390''>all</span> <span m=''1937510''>the</span>
  <span m=''1937640''>paths,</span> <span m=''1938450''>you</span> <span m=''1938630''>get</span>
  <span m=''1939960''>these</span> <span m=''1940300''>guys.</span> <span m=''1940920''>So</span>
  <span m=''1941610''>there''s</span> <span m=''1941850''>some</span> <span m=''1942050''>simple</span>
  <span m=''1942490''>paths</span> <span m=''1942775''>out</span> <span m=''1943060''>here,</span>
  <span m=''1944120''>but</span> <span m=''1944220''>then</span> <span m=''1944350''>there''s</span>
  <span m=''1944530''>this</span> <span m=''1944710''>purple</span> <span m=''1945090''>path</span>
  <span m=''1945420''>in</span> <span m=''1945500''>the</span> <span m=''1945580''>middle,</span>
  <span m=''1945950''>which</span> <span m=''1947090''>starts</span> <span m=''1947480''>here,</span>
  <span m=''1948290''>goes</span> <span m=''1948560''>up</span> <span m=''1948790''>here,</span>
  <span m=''1949170''>over</span> <span m=''1949460''>here,</span> <span m=''1949870''>over</span>
  <span m=''1950150''>here,</span> <span m=''1950540''>along</span> <span m=''1950880''>this</span>
  <span m=''1951100''>crease,</span> <span m=''1951540''>over</span> <span m=''1951810''>here,</span>
  <span m=''1952570''>here,</span> <span m=''1953540''>here,</span> <span m=''1954190''>here,</span>
  <span m=''1956060''>up</span> <span m=''1956320''>there,</span> <span m=''1957130''>here,</span>
  <span m=''1957830''>here,</span> <span m=''1959880''>there,</span> <span m=''1960270''>back,</span>
  <span m=''1960730''>forth,</span> <span m=''1961390''>and</span> <span m=''1961590''>then</span>
  <span m=''1961890''>it</span> <span m=''1962020''>escapes</span> <span m=''1962470''>in</span>
  <span m=''1962570''>the</span> <span m=''1962690''>corner.</span> <span m=''1963830''>So</span>
  <span m=''1964510''>you</span> <span m=''1964700''>get</span> <span m=''1964840''>a</span>
  <span m=''1964880''>mountain</span> <span m=''1965110''>valley assignment</span>
  <span m=''1965650''>out</span> <span m=''1965850''>of</span> <span m=''1965920''>this.</span>
  <span m=''1966010''>I didn''t</span> <span m=''1966480''>test</span> <span m=''1966740''>whether</span>
  <span m=''1966980''>it was</span> <span m=''1967100''>possible.</span> <span m=''1968400''>Probably</span>
  <span m=''1968670''>not.</span> <span m=''1970110''>Anyway,</span> <span m=''1970410''>you</span>
  <span m=''1970570''>get</span> <span m=''1970910''>something,</span> <span m=''1971320''>and</span>
  <span m=''1971880''>it</span> <span m=''1972080''>might</span> <span m=''1972210''>be</span>
  <span m=''1972330''>possible.</span> <span m=''1973640''>Exercise</span> <span m=''1973945''>for</span>
  <span m=''1974250''>you to</span> <span m=''1974730''>try at</span> <span m=''1975180''>home.</span>
  <span m=''1976980''>All</span> <span m=''1977110''>right.</span> <span m=''1977670''>That</span>
  <span m=''1977750''>took</span> <span m=''1979040''>some</span> <span m=''1979200''>time</span>
  <span m=''1979410''>to</span> <span m=''1979510''>draw.</span> <span m=''1982720''>Cool.</span>
  <span m=''1983990''>That''s</span> <span m=''1984260''>local</span> <span m=''1984500''>foldability.</span>
  </p><p><span m=''1986980''>Now</span> <span m=''1987430''>with</span> <span m=''1987740''>the</span>
  <span m=''1987900''>Kawasaki</span> <span m=''1988480''>condition,</span> <span
  m=''1988900''>I</span> <span m=''1988960''>mentioned</span> <span m=''1989350''>briefly</span>
  <span m=''1989730''>in</span> <span m=''1989870''>lecture</span> <span m=''1990210''>three</span>
  <span m=''1990520''>that--</span> <span m=''1991880''>We</span> <span m=''1992010''>were</span>
  <span m=''1992080''>talking</span> <span m=''1992320''>about</span> <span m=''1992500''>convex</span>
  <span m=''1992970''>cones,</span> <span m=''1993250''>where</span> <span m=''1993350''>the</span>
  <span m=''1993440''>amount</span> <span m=''1993630''>of</span> <span m=''1993680''>material
  is</span> <span m=''1994180''>less</span> <span m=''1994400''>than</span> <span
  m=''1994500''>or</span> <span m=''1994600''>equal</span> <span m=''1994710''>to</span>
  <span m=''1994770''>360.</span> <span m=''1995800''>Someone</span> <span m=''1996160''>pointed</span>
  <span m=''1996500''>out</span> <span m=''1996960''>and</span> <span m=''1997180''>said,</span>
  <span m=''1997340''>oh,</span> <span m=''1997610''>out</span> <span m=''1997790''>of</span>
  <span m=''1997840''>paper</span> <span m=''1998250''>you</span> <span m=''1998390''>can''t</span>
  <span m=''1998660''>make</span> <span m=''1998840''>something</span> <span m=''1999120''>more</span>
  <span m=''1999300''>than</span> <span m=''1999430''>360.</span> <span m=''1999700''>And</span>
  <span m=''1999970''>it''s</span> <span m=''2000120''>true</span> <span m=''2000330''>if</span>
  <span m=''2000410''>you</span> <span m=''2000490''>start</span> <span m=''2000770''>from</span>
  <span m=''2000970''>one</span> <span m=''2001170''>sheet</span> <span m=''2001370''>of</span>
  <span m=''2001450''>paper.</span> <span m=''2001940''>But</span> <span m=''2002250''>if</span>
  <span m=''2002360''>you</span> <span m=''2002440''>start</span> <span m=''2002620''>with</span>
  <span m=''2002760''>multiple</span> <span m=''2003740''>sheets</span> <span m=''2004010''>of</span>
  <span m=''2004080''>material</span> <span m=''2004640''>and</span> <span m=''2004920''>join</span>
  <span m=''2005150''>them</span> <span m=''2005280''>together,</span> <span m=''2005690''>like</span>
  <span m=''2005890''>sew</span> <span m=''2006080''>them</span> <span m=''2006240''>up,</span>
  <span m=''2006880''>like</span> <span m=''2007110''>in</span> <span m=''2007190''>a</span>
  <span m=''2007260''>T-shirt,</span> <span m=''2009050''>you</span> <span m=''2009250''>can</span>
  <span m=''2009470''>get</span> <span m=''2010000''>non-convex</span> <span m=''2010680''>cones,</span>
  <span m=''2011010''>meaning</span> <span m=''2011240''>more</span> <span m=''2011440''>than</span>
  <span m=''2011600''>360</span> <span m=''2012160''>degrees of</span> <span m=''2012470''>material</span>
  <span m=''2012920''>here.</span> <span m=''2013230''>This</span> <span m=''2013410''>is,</span>
  <span m=''2013990''>let''s</span> <span m=''2014200''>say,</span> <span m=''2014670''>270,</span>
  <span m=''2015340''>let''s</span> <span m=''2015490''>call it?</span> <span m=''2015800''>So</span>
  <span m=''2016280''>you</span> <span m=''2016450''>double</span> <span m=''2016730''>that,</span>
  <span m=''2017700''>because</span> <span m=''2017830''>there''s</span> <span m=''2018000''>a</span>
  <span m=''2018050''>front</span> <span m=''2018320''>side</span> <span m=''2018540''>and</span>
  <span m=''2018640''>the</span> <span m=''2018710''>back</span> <span m=''2018950''>side</span>
  <span m=''2019130''>of</span> <span m=''2019190''>the</span> <span m=''2019250''>T-shirt.</span>
  <span m=''2019700''>Easier</span> <span m=''2020080''>to</span> <span m=''2020250''>see</span>
  <span m=''2020460''>in</span> <span m=''2020580''>a</span> <span m=''2020640''>3D</span>
  <span m=''2021010''>one.</span> <span m=''2021980''>You''ve</span> <span m=''2022160''>got</span>
  <span m=''2022660''>more</span> <span m=''2022950''>than</span> <span m=''2023090''>360</span>
  <span m=''2023640''>degrees</span> <span m=''2023970''>of</span> <span m=''2024050''>material</span>
  <span m=''2025030''>in</span> <span m=''2025190''>the</span> <span m=''2025320''>armpits.</span>
  <span m=''2027540''>So,</span> <span m=''2028470''>yes,</span> <span m=''2029280''>it''s</span>
  <span m=''2029500''>true.</span> </p><p><span m=''2030100''>And</span> <span m=''2031640''>what</span>
  <span m=''2031920''>happens,</span> <span m=''2032430''>as</span> <span m=''2032690''>I</span>
  <span m=''2033462''>mentioned</span> <span m=''2033850''>briefly,</span> <span m=''2035130''>is</span>
  <span m=''2035270''>there''s</span> <span m=''2035460''>a</span> <span m=''2035520''>new</span>
  <span m=''2035730''>case.</span> <span m=''2036610''>There''s sort</span> <span
  m=''2036870''>of two</span> <span m=''2037030''>situations</span> <span m=''2037730''>when</span>
  <span m=''2038260''>you</span> <span m=''2038340''>have</span> <span m=''2038950''>a</span>
  <span m=''2040390''>kind</span> <span m=''2040560''>of</span> <span m=''2040660''>a</span>
  <span m=''2040710''>mess</span> <span m=''2041180''>of</span> <span m=''2041350''>material</span>
  <span m=''2041790''>like</span> <span m=''2042000''>this,</span> <span m=''2042700''>more</span>
  <span m=''2042910''>than</span> <span m=''2043030''>360</span> <span m=''2043540''>degrees
  of</span> <span m=''2043820''>material.</span> <span m=''2044940''>There</span>
  <span m=''2045150''>are</span> <span m=''2045210''>two</span> <span m=''2045360''>possibilities.</span>
  <span m=''2046130''>Either</span> <span m=''2046300''>you</span> <span m=''2046450''>end</span>
  <span m=''2046580''>up</span> <span m=''2046690''>folding</span> <span m=''2047090''>it</span>
  <span m=''2047220''>to</span> <span m=''2047350''>lie</span> <span m=''2047630''>in</span>
  <span m=''2047880''>less</span> <span m=''2048210''>than</span> <span m=''2048350''>a</span>
  <span m=''2048400''>full</span> <span m=''2048630''>circle,</span> <span m=''2049400''>in</span>
  <span m=''2049659''>terms</span> <span m=''2049870''>of</span> <span m=''2049949''>the</span>
  <span m=''2050020''>boundary,</span> <span m=''2050969''>and</span> <span m=''2051020''>then</span>
  <span m=''2051150''>it''s</span> <span m=''2051310''>just</span> <span m=''2051580''>like</span>
  <span m=''2051860''>here.</span> <span m=''2052300''>The</span> <span m=''2052420''>alternating</span>
  <span m=''2052840''>sum</span> <span m=''2053060''>should</span> <span m=''2053250''>be</span>
  <span m=''2053469''>equal</span> <span m=''2053699''>to</span> <span m=''2053760''>0.</span>
  <span m=''2054659''>Or</span> <span m=''2055050''>you</span> <span m=''2055210''>end</span>
  <span m=''2055400''>up</span> <span m=''2056100''>folding</span> <span m=''2056449''>it</span>
  <span m=''2056560''>so that</span> <span m=''2056719''>it</span> <span m=''2056949''>encompasses</span>
  <span m=''2057600''>an</span> <span m=''2057690''>entire</span> <span m=''2058100''>circle,</span>
  <span m=''2059070''>and</span> <span m=''2059380''>then</span> <span m=''2059570''>you</span>
  <span m=''2059710''>end</span> <span m=''2059860''>up</span> <span m=''2060010''>with</span>
  <span m=''2060090''>this</span> <span m=''2060300''>alternating</span> <span m=''2060760''>sum</span>
  <span m=''2060969''>of</span> <span m=''2061060''>angles</span> <span m=''2061380''>being</span>
  <span m=''2061969''>plus</span> <span m=''2062250''>or</span> <span m=''2062300''>minus</span>
  <span m=''2062630''>360.</span> <span m=''2064010''>And</span> <span m=''2064310''>it''s</span>
  <span m=''2064449''>in</span> <span m=''2064550''>the</span> <span m=''2064659''>textbook.</span>
  <span m=''2065239''>It''s</span> <span m=''2065840''>not</span> <span m=''2066060''>so</span>
  <span m=''2066199''>easy</span> <span m=''2066380''>to</span> <span m=''2066469''>prove</span>
  <span m=''2066790''>that</span> <span m=''2066920''>that''s</span> <span m=''2067130''>all</span>
  <span m=''2067260''>that</span> <span m=''2067360''>happens,</span> <span m=''2067760''>but</span>
  <span m=''2067920''>you--</span> <span m=''2068760''>Basically,</span> <span m=''2069090''>you</span>
  <span m=''2069179''>can''t</span> <span m=''2069500''>twist</span> <span m=''2069880''>multiple</span>
  <span m=''2070280''>times,</span> <span m=''2070780''>because</span> <span m=''2071130''>then</span>
  <span m=''2071260''>you''d</span> <span m=''2071409''>end</span> <span m=''2071560''>up</span>
  <span m=''2071679''>with</span> <span m=''2071989''>a</span> <span m=''2072050''>crossing.</span>
  <span m=''2073659''>So</span> <span m=''2073810''>it''s</span> <span m=''2073909''>not</span>
  <span m=''2074060''>that</span> <span m=''2074370''>much</span> <span m=''2074560''>harder</span>
  <span m=''2074860''>to</span> <span m=''2074980''>analyze</span> <span m=''2075679''>these</span>
  <span m=''2075860''>kinds</span> <span m=''2076050''>of</span> <span m=''2076090''>situations.</span>
  <span m=''2076840''>You</span> <span m=''2076940''>can</span> <span m=''2077070''>do</span>
  <span m=''2077179''>it.</span> </p><p><span m=''2078420''>But</span> <span m=''2078550''>this</span>
  <span m=''2078710''>is</span> <span m=''2078830''>a</span> <span m=''2078900''>great</span>
  <span m=''2079170''>excuse</span> <span m=''2080050''>for</span> <span m=''2080219''>me</span>
  <span m=''2080350''>to</span> <span m=''2080420''>show</span> <span m=''2081280''>cool</span>
  <span m=''2081570''>ways</span> <span m=''2081760''>to</span> <span m=''2081840''>fold</span>
  <span m=''2082060''>T-shirts.</span> <span m=''2083030''>How</span> <span m=''2083179''>many</span>
  <span m=''2083320''>people</span> <span m=''2083630''>seen</span> <span m=''2083850''>this</span>
  <span m=''2084050''>video?</span> <span m=''2085130''>most.</span> <span m=''2086010''>It''s
  like</span> <span m=''2086239''>six</span> <span m=''2086449''>years</span> <span
  m=''2086639''>old.</span> <span m=''2087120''>Have</span> <span m=''2087300''>you</span>
  <span m=''2087409''>ever</span> <span m=''2087590''>tried</span> <span m=''2087880''>it?</span>
  </p><p><span m=''2088912''>[LAUGHTER]</span> </p><p><span m=''2091010''>I brought</span>
  <span m=''2091380''>an extra</span> <span m=''2091820''>little</span> <span m=''2092130''>T-shirt</span>
  <span m=''2092489''>here.</span> <span m=''2094130''>This</span> <span m=''2094400''>is</span>
  <span m=''2094790''>totally</span> <span m=''2095130''>for</span> <span m=''2095260''>fun.</span>
  <span m=''2097210''>You</span> <span m=''2097360''>pinch</span> <span m=''2097650''>here</span>
  <span m=''2098050''>and</span> <span m=''2098120''>here.</span> <span m=''2098880''>Bring</span>
  <span m=''2099060''>this</span> <span m=''2099210''>side</span> <span m=''2099440''>over</span>
  <span m=''2099600''>here.</span> <span m=''2100190''>You</span> <span m=''2100320''>pinch.</span>
  <span m=''2101160''>You</span> <span m=''2101280''>do</span> <span m=''2101520''>a</span>
  <span m=''2101570''>nice</span> <span m=''2101890''>flourish,</span> <span m=''2103062''>and</span>
  <span m=''2103484''>then you</span> <span m=''2103906''>get your</span> <span m=''2104330''>perfectly</span>
  <span m=''2104950''>folded--</span> <span m=''2105210''>I didn''t</span> <span m=''2105530''>do
  it</span> <span m=''2105850''>perfectly--</span> <span m=''2106720''>T-shirt</span>
  <span m=''2107610''>in</span> <span m=''2108280''>one</span> <span m=''2108700''>motion.</span>
  <span m=''2109160''>As</span> <span m=''2109270''>they</span> <span m=''2109390''>say,</span>
  <span m=''2109610''>in</span> <span m=''2109820''>two</span> <span m=''2110000''>seconds,</span>
  <span m=''2111480''>and</span> <span m=''2111730''>it</span> <span m=''2111800''>works</span>
  <span m=''2112070''>for</span> <span m=''2112310''>us.</span> <span m=''2114140''>So</span>
  <span m=''2114320''>it''s</span> <span m=''2114480''>a</span> <span m=''2114550''>great</span>
  <span m=''2114800''>T-shirts.</span> </p><p><span m=''2117150''>And</span> <span
  m=''2117770''>for</span> <span m=''2117950''>fun,</span> <span m=''2118570''>here''s</span>
  <span m=''2118900''>the--</span> <span m=''2120020''>this</span> <span m=''2120340''>is</span>
  <span m=''2120470''>like</span> <span m=''2120670''>the</span> <span m=''2120750''>high</span>
  <span m=''2120920''>tech</span> <span m=''2121180''>way</span> <span m=''2121320''>to</span>
  <span m=''2121430''>do</span> <span m=''2121600''>it.</span> <span m=''2123140''>There''s</span>
  <span m=''2123310''>actually</span> <span m=''2123530''>a</span> <span m=''2123590''>whole</span>
  <span m=''2123900''>bunch</span> <span m=''2124210''>of</span> <span m=''2125480''>T-shirt</span>
  <span m=''2125830''>folding</span> <span m=''2126150''>machines.</span> <span m=''2127250''>You</span>
  <span m=''2127530''>push</span> <span m=''2127710''>the</span> <span m=''2127810''>button.</span>
  <span m=''2128340''>It''s</span> <span m=''2128940''>a</span> <span m=''2128980''>bunch</span>
  <span m=''2129200''>of</span> <span m=''2129250''>simple</span> <span m=''2129530''>folds,</span>
  <span m=''2129910''>actually.</span> <span m=''2131040''>So it''s</span> <span m=''2131290''>a</span>
  <span m=''2131360''>nice</span> <span m=''2131630''>little</span> <span m=''2131830''>simple
  folding</span> <span m=''2132264''>machine.</span> </p><p><span m=''2132698''>[LAUGHTER]</span>
  </p><p><span m=''2134000''>It''s</span> <span m=''2134310''>kind</span> <span m=''2134470''>of</span>
  <span m=''2134560''>fun</span> <span m=''2135430''>to</span> <span m=''2135550''>watch.</span>
  <span m=''2135820''>Seems</span> <span m=''2136010''>like</span> <span m=''2136200''>a</span>
  <span m=''2136260''>lot</span> <span m=''2136440''>of</span> <span m=''2136500''>set</span>
  <span m=''2136680''>up</span> <span m=''2136820''>time.</span> <span m=''2139280''>You</span>
  <span m=''2139390''>have</span> <span m=''2139540''>set</span> <span m=''2139730''>up</span>
  <span m=''2139840''>time</span> <span m=''2140420''>with</span> <span m=''2140800''>the</span>
  <span m=''2142020''>fast</span> <span m=''2142320''>method</span> <span m=''2142610''>also.</span>
  <span m=''2143520''>So</span> <span m=''2143840''>It''s</span> <span m=''2143980''>kind</span>
  <span m=''2144110''>of</span> <span m=''2144190''>fun.</span> <span m=''2145430''>The</span>
  <span m=''2145520''>same</span> <span m=''2145730''>machine.</span> <span m=''2146170''>you</span>
  <span m=''2146190''>can</span> <span m=''2146320''>also</span> <span m=''2146550''>wrap</span>
  <span m=''2146870''>them</span> <span m=''2147000''>directly</span> <span m=''2147450''>into</span>
  <span m=''2147650''>bags.</span> <span m=''2148220''>Question?</span> </p><p><span
  m=''2149125''>AUDIENCE: Have you</span> <span m=''2150115''>in</span> <span m=''2150910''>clothing</span>
  <span m=''2151370''>stores</span> <span m=''2151600''>they</span> <span m=''2152078''>have</span>
  <span m=''2152556''>non-mechanical</span> <span m=''2153034''>versions of</span>
  <span m=''2153512''>those</span> <span m=''2153990''>that are just</span> <span
  m=''2154468''>plastic</span> <span m=''2154946''>boards.</span> </p><p><span m=''2155430''>PROFESSOR:
  And you</span> <span m=''2155795''>just--</span> </p><p><span m=''2156160''>AUDIENCE:
  That you</span> <span m=''2156586''>can flop</span> <span m=''2157012''>over</span>
  <span m=''2157438''>so that</span> <span m=''2157864''>all your T-shirts</span>
  <span m=''2158290''>are folded</span> <span m=''2158555''>the same.</span> </p><p><span
  m=''2158820''>PROFESSOR: It''s</span> <span m=''2159030''>not</span> <span m=''2159050''>automated.</span>
  <span m=''2159900''>Yes.</span> <span m=''2160310''>You</span> <span m=''2160500''>can</span>
  <span m=''2160650''>actually</span> <span m=''2160930''>buy--</span> <span m=''2161980''>I''ve</span>
  <span m=''2162870''>only</span> <span m=''2163120''>seen them</span> <span m=''2163310''>in</span>
  <span m=''2163480''>stores</span> <span m=''2163810''>rarely.</span> <span m=''2164310''>They''re</span>
  <span m=''2164440''>usually</span> <span m=''2164730''>in</span> <span m=''2164790''>the</span>
  <span m=''2164870''>back</span> <span m=''2165170''>room.</span> <span m=''2165930''>But</span>
  <span m=''2166730''>you</span> <span m=''2166880''>can</span> <span m=''2167010''>actually</span>
  <span m=''2167260''>buy</span> <span m=''2167740''>this</span> <span m=''2167950''>folding</span>
  <span m=''2168290''>machine. It''s</span> <span m=''2168620''>like</span> <span
  m=''2168760''>a</span> <span m=''2168820''>giant</span> <span m=''2169140''>piece</span>
  <span m=''2169330''>of</span> <span m=''2169400''>plastic</span> <span m=''2169850''>with</span>
  <span m=''2170010''>exactly--</span> <span m=''2171130''>maybe</span> <span m=''2171840''>only</span>
  <span m=''2172100''>three</span> <span m=''2172360''>creases,</span> <span m=''2172790''>I</span>
  <span m=''2172850''>think</span> <span m=''2173090''>typically.</span> <span m=''2174040''>And</span>
  <span m=''2174290''>then</span> <span m=''2174440''>you</span> <span m=''2174580''>just</span>
  <span m=''2174880''>do</span> <span m=''2175150''>them</span> <span m=''2175340''>in</span>
  <span m=''2175420''>some</span> <span m=''2175660''>order</span> <span m=''2175910''>manually</span>
  <span m=''2176460''>with</span> <span m=''2176530''>simple</span> <span m=''2176860''>folds,</span>
  <span m=''2177220''>and</span> <span m=''2177330''>it</span> <span m=''2177440''>does</span>
  <span m=''2177630''>make</span> <span m=''2177840''>really</span> <span m=''2178150''>nicely</span>
  <span m=''2178510''>folded</span> <span m=''2178850''>T-shirts.</span> <span m=''2180860''>Nicer</span>
  <span m=''2181110''>than</span> <span m=''2181280''>I</span> <span m=''2181360''>could</span>
  <span m=''2181520''>fold</span> <span m=''2181720''>by</span> <span m=''2181850''>hand,</span>
  <span m=''2182110''>anyway.</span> <span m=''2182875''>All right.</span> <span m=''2183350''>That</span>
  <span m=''2183510''>was</span> <span m=''2183640''>just</span> <span m=''2183800''>for</span>
  <span m=''2183910''>fun.</span> <span m=''2184840''>While we''re</span> <span m=''2185155''>on</span>
  <span m=''2185470''>the</span> <span m=''2185550''>topic</span> <span m=''2185930''>of</span>
  <span m=''2186060''>T-shirts.</span> </p><p><span m=''2189340''>Next</span> <span
  m=''2189600''>question</span> <span m=''2189940''>is</span> <span m=''2190070''>about</span>
  <span m=''2190490''>higher</span> <span m=''2190830''>dimensions.</span> <span m=''2191480''>So</span>
  <span m=''2191660''>I</span> <span m=''2191740''>mentioned</span> <span m=''2192090''>briefly,</span>
  <span m=''2193090''>yeah,</span> <span m=''2193350''>you</span> <span m=''2193480''>can</span>
  <span m=''2193580''>do</span> <span m=''2193680''>higher</span> <span m=''2193850''>dimensional</span>
  <span m=''2194220''>origami.</span> <span m=''2194640''>Not</span> <span m=''2194820''>much</span>
  <span m=''2195010''>is</span> <span m=''2195110''>known</span> <span m=''2195300''>about</span>
  <span m=''2195560''>it.</span> <span m=''2196010''>So</span> <span m=''2196200''>a</span>
  <span m=''2196520''>natural</span> <span m=''2196820''>thing</span> <span m=''2196990''>to
  ask</span> <span m=''2197310''>about</span> <span m=''2197560''>is</span> <span
  m=''2197780''>flat</span> <span m=''2198050''>foldability</span> <span m=''2198700''>for</span>
  <span m=''2199090''>higher</span> <span m=''2199380''>dimensions.</span> <span m=''2200130''>And</span>
  <span m=''2202250''>there are</span> <span m=''2202590''>exactly</span> <span m=''2203630''>two</span>
  <span m=''2203780''>papers</span> <span m=''2204260''>about</span> <span m=''2204610''>this.</span>
  <span m=''2205030''>Well,</span> <span m=''2205170''>maybe</span> <span m=''2205420''>even</span>
  <span m=''2205600''>just</span> <span m=''2205780''>one.</span> <span m=''2207350''>The</span>
  <span m=''2207690''>old</span> <span m=''2207900''>one</span> <span m=''2208140''>is</span>
  <span m=''2208280''>this</span> <span m=''2208440''>paper</span> <span m=''2208710''>by</span>
  <span m=''2208830''>Kawasaki--</span> <span m=''2209610''>same</span> <span m=''2209930''>guy</span>
  <span m=''2210680''>as</span> <span m=''2210970''>Kawasaki''s</span> <span m=''2211550''>condition--</span>
  <span m=''2212360''>and</span> <span m=''2212520''>this</span> <span m=''2212660''>is</span>
  <span m=''2212780''>in</span> <span m=''2212930''>this</span> <span m=''2213630''>book.</span>
  <span m=''2214640''>This</span> <span m=''2215123''>the</span> <span m=''2215606''>first--</span>
  <span m=''2216090''>this is a</span> <span m=''2216200''>hard</span> <span m=''2216460''>book</span>
  <span m=''2216630''>to</span> <span m=''2216710''>get</span> <span m=''2216830''>a</span>
  <span m=''2216880''>copy</span> <span m=''2217190''>of,</span> <span m=''2217300''><i>First</i></span>
  <span m=''2217570''><i>International</i></span> <span m=''2218000''><i>Meeting</i></span>
  <span m=''2218240''><i>of Origami</i></span> <span m=''2218730''><i>Science</i></span>
  <span m=''2219030''><i>and</i></span> <span m=''2219110''><i>Technology</i>.</span>
  <span m=''2219660''>These</span> <span m=''2219860''>days</span> <span m=''2220060''>it''s</span>
  <span m=''2220180''>called</span> <span m=''2220410''><i>Origami</i></span> <span
  m=''2220850''><i>Science,</i></span> <span m=''2221190''><i>Math,</i></span> <span
  m=''2221420''><i>and</i></span> <span m=''2221550''><i>Education,</i></span> <span
  m=''2222160''>OSME.</span> <span m=''2222980''>And</span> <span m=''2223230''>this</span>
  <span m=''2223400''>T-shirt</span> <span m=''2223740''>is</span> <span m=''2223860''>from</span>
  <span m=''2224080''>the</span> <span m=''2224190''>latest</span> <span m=''2224570''>one,</span>
  <span m=''2224720''>which</span> <span m=''2224900''>was</span> <span m=''2225010''>in</span>
  <span m=''2225100''>Singapore</span> <span m=''2227720''>two</span> <span m=''2227890''>years</span>
  <span m=''2228150''>ago,</span> <span m=''2228570''>I</span> <span m=''2228670''>think,</span>
  <span m=''2228840''>2010.</span> <span m=''2230330''>Next</span> <span m=''2230570''>one</span>
  <span m=''2230740''>is</span> <span m=''2231110''>in</span> <span m=''2231280''>a</span>
  <span m=''2231320''>year</span> <span m=''2231660''>or</span> <span m=''2231710''>two</span>
  <span m=''2231980''>in</span> <span m=''2232100''>Japan.</span> <span m=''2233270''>So</span>
  <span m=''2233430''>this</span> <span m=''2233540''>is</span> <span m=''2233660''>the</span>
  <span m=''2233720''>very</span> <span m=''2233910''>first</span> <span m=''2234190''>one.</span>
  <span m=''2234350''>This is</span> <span m=''2234510''>before</span> <span m=''2234840''>my</span>
  <span m=''2235020''>time.</span> <span m=''2235530''>And</span> <span m=''2235830''>there''s</span>
  <span m=''2236020''>this</span> <span m=''2236200''>paper.</span> <span m=''2236740''>It''s</span>
  <span m=''2236940''>a</span> <span m=''2237020''>translated</span> <span m=''2238200''>Japanese</span>
  <span m=''2238640''>paper,</span> <span m=''2238990''>so it</span> <span m=''2239110''>has</span>
  <span m=''2239870''>a few</span> <span m=''2240050''>typos.</span> <span m=''2240660''>We</span>
  <span m=''2240780''>also</span> <span m=''2240980''>have</span> <span m=''2241110''>the</span>
  <span m=''2241200''>Japanese</span> <span m=''2241620''>original if</span> <span
  m=''2242070''>you''re interested</span> <span m=''2242380''>in</span> <span m=''2242580''>reading</span>
  <span m=''2242880''>this</span> <span m=''2243030''>some</span> <span m=''2243180''>time.</span>
  </p><p><span m=''2243880''>You</span> <span m=''2244010''>see,</span> <span m=''2244270''>for</span>
  <span m=''2244510''>example,</span> <span m=''2244960''>here</span> <span m=''2245140''>is</span>
  <span m=''2245330''>folding</span> <span m=''2245750''>a</span> <span m=''2245840''>regular</span>
  <span m=''2246170''>piece</span> <span m=''2246370''>of</span> <span m=''2246420''>paper</span>
  <span m=''2246730''>in</span> <span m=''2246800''>half.</span> <span m=''2247170''>Here''s</span>
  <span m=''2247450''>folding</span> <span m=''2247780''>a</span> <span m=''2247850''>3D</span>
  <span m=''2248150''>solid</span> <span m=''2248490''>of</span> <span m=''2248550''>paper</span>
  <span m=''2248900''>in</span> <span m=''2249040''>half.</span> <span m=''2249970''>A</span>
  <span m=''2250040''>little</span> <span m=''2250130''>harder</span> <span m=''2250390''>to</span>
  <span m=''2250650''>imagine,</span> <span m=''2251190''>but</span> <span m=''2251880''>there</span>
  <span m=''2252080''>it</span> <span m=''2252130''>is.</span> <span m=''2252790''>And</span>
  <span m=''2253670''>let''s</span> <span m=''2253810''>see,</span> <span m=''2253910''>what''s</span>
  <span m=''2254110''>in</span> <span m=''2254200''>this</span> <span m=''2254360''>paper?</span>
  <span m=''2254750''>There''s</span> <span m=''2255060''>a</span> <span m=''2255910''>definition,</span>
  <span m=''2257120''>although</span> <span m=''2257350''>I</span> <span m=''2257480''>would</span>
  <span m=''2257630''>really</span> <span m=''2257910''>call</span> <span m=''2258210''>it</span>
  <span m=''2258360''>a</span> <span m=''2258490''>necessary</span> <span m=''2259190''>condition.</span>
  <span m=''2259530''>I think</span> <span m=''2260100''>this</span> <span m=''2260140''>is</span>
  <span m=''2260250''>not</span> <span m=''2260440''>a</span> <span m=''2260490''>good</span>
  <span m=''2260680''>definition</span> <span m=''2261290''>of</span> <span m=''2261390''>flat</span>
  <span m=''2261640''>origami</span> <span m=''2262060''>in</span> <span m=''2262160''>3D.</span>
  <span m=''2262620''>But</span> <span m=''2262980''>there</span> <span m=''2263180''>it</span>
  <span m=''2263240''>is.</span> <span m=''2263470''>This</span> <span m=''2263640''>is</span>
  <span m=''2263760''>the</span> <span m=''2263870''>definition.</span> <span m=''2265470''>What</span>
  <span m=''2265710''>it</span> <span m=''2265840''>says</span> <span m=''2266160''>is</span>
  <span m=''2266270''>basically,</span> <span m=''2267830''>locally</span> <span m=''2268430''>everything</span>
  <span m=''2268920''>works</span> <span m=''2269270''>out.</span> <span m=''2270020''>When</span>
  <span m=''2270220''>you</span> <span m=''2270310''>do</span> <span m=''2270460''>a</span>
  <span m=''2270520''>fold,</span> <span m=''2270910''>it''s</span> <span m=''2271060''>like</span>
  <span m=''2271240''>a</span> <span m=''2271300''>reflection.</span> <span m=''2272700''>If</span>
  <span m=''2272820''>you</span> <span m=''2272960''>do</span> <span m=''2273080''>it</span>
  <span m=''2273150''>instantaneously,</span> <span m=''2273960''>this</span> <span
  m=''2274160''>is</span> <span m=''2274240''>like</span> <span m=''2274400''>reflecting</span>
  <span m=''2274870''>this</span> <span m=''2275030''>piece</span> <span m=''2275320''>through</span>
  <span m=''2275550''>the</span> <span m=''2275650''>line</span> <span m=''2276340''>for</span>
  <span m=''2276460''>flat</span> <span m=''2276750''>folding.</span> <span m=''2277130''>This</span>
  <span m=''2277410''>is</span> <span m=''2277530''>like</span> <span m=''2277710''>reflecting</span>
  <span m=''2278140''>this</span> <span m=''2278290''>piece</span> <span m=''2278510''>through</span>
  <span m=''2278710''>the</span> <span m=''2278820''>plane.</span> <span m=''2280230''>And</span>
  <span m=''2280460''>so</span> <span m=''2281530''>one</span> <span m=''2281970''>condition</span>
  <span m=''2282360''>you</span> <span m=''2282470''>have</span> <span m=''2282830''>is</span>
  <span m=''2282960''>that</span> <span m=''2283150''>if</span> <span m=''2283290''>you--</span>
  <span m=''2284010''>it''s</span> <span m=''2284250''>easier</span> <span m=''2284520''>to</span>
  <span m=''2284600''>look</span> <span m=''2284800''>at</span> <span m=''2284890''>one</span>
  <span m=''2285050''>of</span> <span m=''2285310''>the</span> <span m=''2285380''>examples</span>
  <span m=''2285890''>in</span> <span m=''2285960''>the</span> <span m=''2286060''>paper.</span>
  </p><p><span m=''2287630''>So</span> <span m=''2287760''>you</span> <span m=''2287810''>have</span>
  <span m=''2288020''>this</span> <span m=''2288210''>crease</span> <span m=''2288490''>pattern,</span>
  <span m=''2288980''>which</span> <span m=''2289050''>you</span> <span m=''2289130''>can</span>
  <span m=''2289260''>draw</span> <span m=''2289460''>by</span> <span m=''2289660''>a</span>
  <span m=''2289730''>bunch</span> <span m=''2289990''>of</span> <span m=''2290110''>planes,</span>
  <span m=''2290600''>let''s</span> <span m=''2290810''>say.</span> <span m=''2291790''>If</span>
  <span m=''2291970''>you</span> <span m=''2292130''>kind of</span> <span m=''2292390''>walk</span>
  <span m=''2292720''>around</span> <span m=''2293030''>and</span> <span m=''2293120''>say,</span>
  <span m=''2293280''>OK,</span> <span m=''2293580''>I</span> <span m=''2293630''>go</span>
  <span m=''2293830''>through</span> <span m=''2294020''>this</span> <span m=''2294240''>crease,</span>
  <span m=''2294510''>which</span> <span m=''2294650''>means</span> <span m=''2294810''>I</span>
  <span m=''2294950''>reflect</span> <span m=''2295260''>through</span> <span m=''2295380''>that</span>
  <span m=''2296190''>plane,</span> <span m=''2296580''>then</span> <span m=''2296700''>I</span>
  <span m=''2296730''>reflect</span> <span m=''2296990''>through</span> <span m=''2297150''>this</span>
  <span m=''2297320''>plane,</span> <span m=''2297550''>this</span> <span m=''2297710''>plane,</span>
  <span m=''2297980''>this</span> <span m=''2298150''>plane,</span> <span m=''2298420''>you</span>
  <span m=''2298700''>can</span> <span m=''2298840''>take</span> <span m=''2299070''>any</span>
  <span m=''2299400''>sort</span> <span m=''2299620''>of</span> <span m=''2299720''>path,</span>
  <span m=''2300490''>any</span> <span m=''2300690''>cycle</span> <span m=''2301070''>through</span>
  <span m=''2301230''>this</span> <span m=''2302860''>world.</span> <span m=''2303450''>In</span>
  <span m=''2303580''>the</span> <span m=''2303720''>end</span> <span m=''2303930''>I</span>
  <span m=''2303970''>should</span> <span m=''2304300''>end</span> <span m=''2304520''>up</span>
  <span m=''2304680''>back</span> <span m=''2304930''>where</span> <span m=''2305050''>I</span>
  <span m=''2305100''>started.</span> <span m=''2305720''>Otherwise</span> <span m=''2306210''>I''m</span>
  <span m=''2306360''>ripping.</span> <span m=''2307410''>And</span> <span m=''2307480''>what</span>
  <span m=''2307600''>that</span> <span m=''2307750''>condition</span> <span m=''2308140''>says</span>
  <span m=''2308470''>is</span> <span m=''2308590''>that</span> <span m=''2308720''>if</span>
  <span m=''2308850''>you</span> <span m=''2308940''>take</span> <span m=''2309140''>the</span>
  <span m=''2309230''>sequence</span> <span m=''2309570''>of</span> <span m=''2309650''>reflections</span>
  <span m=''2309920''>and</span> <span m=''2310190''>you</span> <span m=''2310330''>compose</span>
  <span m=''2310740''>them,</span> <span m=''2311020''>you</span> <span m=''2311040''>end</span>
  <span m=''2311230''>up</span> <span m=''2311390''>with</span> <span m=''2312080''>no</span>
  <span m=''2312240''>reflection</span> <span m=''2312640''>at</span> <span m=''2312720''>all,</span>
  <span m=''2312940''>that</span> <span m=''2313180''>nothing</span> <span m=''2313540''>moved.</span>
  <span m=''2314740''>And</span> <span m=''2315020''>so</span> <span m=''2315110''>that''s</span>
  <span m=''2315340''>a</span> <span m=''2315400''>necessary</span> <span m=''2315880''>condition</span>
  <span m=''2316210''>for</span> <span m=''2316330''>flat foldability.</span> <span
  m=''2317670''>I</span> <span m=''2317770''>wouldn''t</span> <span m=''2317980''>call</span>
  <span m=''2318150''>it a</span> <span m=''2318230''>definition,</span> <span m=''2318900''>although</span>
  <span m=''2319560''>this</span> <span m=''2319810''>paper</span> <span m=''2320100''>did.</span>
  <span m=''2321300''>Natural</span> <span m=''2321610''>definition</span> <span m=''2322110''>is</span>
  <span m=''2322230''>more</span> <span m=''2322490''>like</span> <span m=''2324360''>what</span>
  <span m=''2324510''>we</span> <span m=''2324630''>draw</span> <span m=''2325350''>in</span>
  <span m=''2325510''>2D</span> <span m=''2327180''>for</span> <span m=''2327340''>flat
  folding,</span> <span m=''2328820''>where</span> <span m=''2329030''>we</span> <span
  m=''2329240''>add</span> <span m=''2329590''>another</span> <span m=''2329910''>layer,</span>
  <span m=''2330860''>another</span> <span m=''2331130''>dimension,</span> <span m=''2332040''>and</span>
  <span m=''2332170''>then</span> <span m=''2332300''>guarantee</span> <span m=''2332740''>no</span>
  <span m=''2332930''>collisions</span> <span m=''2333920''>in</span> <span m=''2334050''>that</span>
  <span m=''2334220''>dimension.</span> </p><p><span m=''2335860''>So</span> <span
  m=''2336720''>same</span> <span m=''2337010''>thing</span> <span m=''2337460''>in</span>
  <span m=''2337620''>3D.</span> <span m=''2338020''>It''s</span> <span m=''2338130''>just</span>
  <span m=''2338330''>harder</span> <span m=''2338580''>to</span> <span m=''2338670''>imagine</span>
  <span m=''2339090''>stacking</span> <span m=''2339580''>up</span> <span m=''2339710''>copies</span>
  <span m=''2340090''>of</span> <span m=''2340210''>3D.</span> <span m=''2340910''>Question?</span>
  </p><p><span m=''2341250''>AUDIENCE: Doesn''t</span> <span m=''2341640''>the</span>
  <span m=''2341750''>reflection</span> <span m=''2342055''>analogy</span> <span m=''2342680''>only</span>
  <span m=''2342940''>apply</span> <span m=''2343030''>to</span> <span m=''2343700''>simple</span>
  <span m=''2343950''>folds,</span> <span m=''2344640''>where the</span> <span m=''2345066''>plane
  goes</span> <span m=''2345918''>all the</span> <span m=''2346344''>way?</span> </p><p><span
  m=''2346770''>PROFESSOR: OK.</span> <span m=''2347200''>Good</span> <span m=''2347310''>question.</span>
  <span m=''2347700''>The</span> <span m=''2347800''>reflection</span> <span m=''2348240''>analogy</span>
  <span m=''2349120''>definitely</span> <span m=''2349400''>applies</span> <span m=''2349690''>to</span>
  <span m=''2349740''>simple</span> <span m=''2350030''>folds.</span> <span m=''2350320''>It</span>
  <span m=''2350520''>also</span> <span m=''2350850''>applies</span> <span m=''2351220''>to</span>
  <span m=''2351320''>non-simple</span> <span m=''2351810''>folds.</span> <span m=''2352040''>But</span>
  <span m=''2352190''>it</span> <span m=''2352290''>does</span> <span m=''2352460''>require</span>
  <span m=''2353010''>straight</span> <span m=''2353800''>folds,</span> <span m=''2354170''>which</span>
  <span m=''2354370''>here</span> <span m=''2354520''>mean</span> <span m=''2354750''>flat</span>
  <span m=''2355190''>folds,</span> <span m=''2356320''>like</span> <span m=''2356560''>planar</span>
  <span m=''2356920''>folds.</span> <span m=''2358100''>For</span> <span m=''2358240''>curve</span>
  <span m=''2358510''>creases,</span> <span m=''2358980''>you''re</span> <span m=''2359280''>not</span>
  <span m=''2359490''>really</span> <span m=''2359710''>reflecting,</span> <span m=''2360860''>because</span>
  <span m=''2361400''>you</span> <span m=''2361730''>can''t</span> <span m=''2361970''>fold</span>
  <span m=''2362120''>a</span> <span m=''2362310''>curve</span> <span m=''2362740''>crease</span>
  <span m=''2363100''>all</span> <span m=''2363300''>the</span> <span m=''2363400''>way.</span>
  <span m=''2363610''>You</span> <span m=''2363700''>can''t</span> <span m=''2363910''>fold</span>
  <span m=''2364060''>it</span> <span m=''2364170''>flat.</span> <span m=''2364900''>But</span>
  <span m=''2365020''>whenever</span> <span m=''2365280''>you</span> <span m=''2365380''>fold</span>
  <span m=''2365600''>something</span> <span m=''2365900''>all</span> <span m=''2366100''>the</span>
  <span m=''2366200''>way--</span> <span m=''2366590''>so</span> <span m=''2366630''>even
  in</span> <span m=''2366990''>something</span> <span m=''2367290''>like</span> <span
  m=''2367460''>this,</span> <span m=''2367660''>which</span> <span m=''2367850''>is</span>
  <span m=''2367970''>not</span> <span m=''2368180''>a</span> <span m=''2368240''>simple</span>
  <span m=''2368570''>fold</span> <span m=''2368900''>in</span> <span m=''2368950''>the</span>
  <span m=''2369080''>end--</span> <span m=''2370250''>you</span> <span m=''2370510''>can</span>
  <span m=''2371050''>check.</span> <span m=''2371580''>Essentially,</span> <span
  m=''2372030''>this</span> <span m=''2372210''>is</span> <span m=''2372320''>what</span>
  <span m=''2372530''>we--</span> <span m=''2372890''>on</span> <span m=''2373030''>the</span>
  <span m=''2373110''>circle,</span> <span m=''2374010''>when</span> <span m=''2374120''>we</span>
  <span m=''2374230''>said,</span> <span m=''2374520''>OK,</span> <span m=''2374750''>you</span>
  <span m=''2374890''>walk</span> <span m=''2375170''>this</span> <span m=''2375350''>way</span>
  <span m=''2375540''>and</span> <span m=''2375740''>then</span> <span m=''2375890''>you</span>
  <span m=''2376130''>just</span> <span m=''2376490''>change</span> <span m=''2376820''>direction.</span>
  <span m=''2377450''>That''s</span> <span m=''2377790''>essentially</span> <span
  m=''2378260''>the</span> <span m=''2378360''>reflection</span> <span m=''2378860''>that''s</span>
  <span m=''2379020''>happening</span> <span m=''2379790''>on</span> <span m=''2379970''>the</span>
  <span m=''2380040''>circle.</span> <span m=''2381210''>If</span> <span m=''2381350''>you</span>
  <span m=''2381510''>live</span> <span m=''2381730''>on</span> <span m=''2381840''>the</span>
  <span m=''2381920''>circle</span> <span m=''2382290''>you''re</span> <span m=''2382590''>reflecting</span>
  <span m=''2383110''>in</span> <span m=''2383180''>that</span> <span m=''2383270''>you''re</span>
  <span m=''2383470''>immediately</span> <span m=''2383850''>bouncing</span> <span
  m=''2384190''>back</span> <span m=''2384430''>at</span> <span m=''2384500''>that</span>
  <span m=''2384680''>crease.</span> </p><p><span m=''2385360''>It</span> <span m=''2385490''>turns</span>
  <span m=''2385700''>out</span> <span m=''2385800''>to</span> <span m=''2385870''>hold</span>
  <span m=''2386090''>in</span> <span m=''2386220''>2D</span> <span m=''2386550''>as</span>
  <span m=''2386660''>well.</span> <span m=''2387620''>So</span> <span m=''2387710''>if</span>
  <span m=''2387810''>you</span> <span m=''2388580''>look</span> <span m=''2388760''>at</span>
  <span m=''2388830''>the</span> <span m=''2388920''>effect</span> <span m=''2389250''>of</span>
  <span m=''2389330''>this</span> <span m=''2389520''>crease,</span> <span m=''2389870''>it</span>
  <span m=''2390000''>is</span> <span m=''2390160''>that</span> <span m=''2390270''>you''re</span>
  <span m=''2390410''>reflecting</span> <span m=''2391180''>this</span> <span m=''2391380''>part</span>
  <span m=''2392050''>over</span> <span m=''2392280''>that</span> <span m=''2392500''>crease.</span>
  <span m=''2394090''>I</span> <span m=''2394120''>guess</span> <span m=''2394320''>you</span>
  <span m=''2394420''>can</span> <span m=''2394550''>see</span> <span m=''2394750''>it</span>
  <span m=''2394850''>in</span> <span m=''2394970''>the</span> <span m=''2395050''>folding</span>
  <span m=''2395490''>too.</span> <span m=''2395810''>I</span> <span m=''2395890''>mean,</span>
  <span m=''2396590''>you</span> <span m=''2397180''>go</span> <span m=''2397290''>over</span>
  <span m=''2397440''>this</span> <span m=''2397610''>crease,</span> <span m=''2397880''>then</span>
  <span m=''2397990''>you</span> <span m=''2398080''>hit</span> <span m=''2398230''>this</span>
  <span m=''2398400''>line,</span> <span m=''2398720''>and</span> <span m=''2398790''>then</span>
  <span m=''2398880''>you</span> <span m=''2399000''>immediately</span> <span m=''2399380''>bounce</span>
  <span m=''2399770''>back</span> <span m=''2400050''>at</span> <span m=''2400150''>the</span>
  <span m=''2400230''>line.</span> <span m=''2400640''>That</span> <span m=''2400800''>is</span>
  <span m=''2400940''>actually a</span> <span m=''2401270''>reflection</span> <span
  m=''2402130''>through</span> <span m=''2402320''>the</span> <span m=''2402430''>line.</span>
  <span m=''2403570''>Good</span> <span m=''2403720''>question.</span> <span m=''2404120''>It''s</span>
  <span m=''2404460''>obvious</span> <span m=''2404800''>for</span> <span m=''2404900''>simple</span>
  <span m=''2405190''>folds,</span> <span m=''2405490''>but</span> <span m=''2406130''>reflection</span>
  <span m=''2406620''>actually</span> <span m=''2406900''>works</span> <span m=''2408020''>here</span>
  <span m=''2408310''>as</span> <span m=''2408400''>well.</span> <span m=''2408860''>We''ll</span>
  <span m=''2409010''>talk</span> <span m=''2409200''>more</span> <span m=''2409350''>about</span>
  <span m=''2409530''>that</span> <span m=''2409690''>in</span> <span m=''2409810''>the</span>
  <span m=''2409890''>next</span> <span m=''2410250''>lecture,</span> <span m=''2410740''>I
  believe.</span> </p><p><span m=''2413350''>OK.</span> <span m=''2414260''>I</span>
  <span m=''2414420''>was</span> <span m=''2414540''>looking</span> <span m=''2414810''>up</span>
  <span m=''2415030''>reference,</span> <span m=''2415780''>any</span> <span m=''2415970''>papers</span>
  <span m=''2416280''>that cited</span> <span m=''2416760''>that</span> <span m=''2416950''>one,</span>
  <span m=''2417250''>and</span> <span m=''2417430''>there''s</span> <span m=''2417650''>basically</span>
  <span m=''2418030''>one</span> <span m=''2418240''>paper,</span> <span m=''2419330''>which</span>
  <span m=''2419600''>is</span> <span m=''2419740''>this</span> <span m=''2421790''>kind</span>
  <span m=''2421990''>of</span> <span m=''2422080''>a</span> <span m=''2422140''>graphics/art/math</span>
  <span m=''2423720''>paper</span> <span m=''2425440''>talking</span> <span m=''2425850''>about</span>
  <span m=''2426120''>four-dimensional</span> <span m=''2426640''>origami.</span>
  <span m=''2427000''>It''s</span> <span m=''2427150''>basically</span> <span m=''2428570''>some</span>
  <span m=''2428810''>simulations</span> <span m=''2429460''>and</span> <span m=''2429920''>some</span>
  <span m=''2430190''>examples.</span> <span m=''2430840''>Here''s</span> <span m=''2431000''>the</span>
  <span m=''2431930''>not</span> <span m=''2432290''>folding</span> <span m=''2432600''>all</span>
  <span m=''2432770''>the</span> <span m=''2432850''>way</span> <span m=''2433050''>picture.</span>
  <span m=''2433990''>A</span> <span m=''2434030''>little</span> <span m=''2434210''>harder</span>
  <span m=''2435020''>to</span> <span m=''2435150''>imagine.</span> <span m=''2435590''>Here</span>
  <span m=''2435880''>they''re</span> <span m=''2436030''>doing,</span> <span m=''2436350''>I</span>
  <span m=''2436390''>think,</span> <span m=''2436830''>the</span> <span m=''2437030''>4D</span>
  <span m=''2437440''>analog</span> <span m=''2438040''>of</span> <span m=''2438190''>a</span>
  <span m=''2438320''>rabbit</span> <span m=''2438720''>ear</span> <span m=''2438910''>fold.</span>
  <span m=''2439840''>Little</span> <span m=''2440030''>hard</span> <span m=''2440230''>to</span>
  <span m=''2440310''>tell,</span> <span m=''2440710''>but</span> <span m=''2441080''>first
  they</span> <span m=''2441460''>do</span> <span m=''2441580''>a</span> <span m=''2441640''>simple</span>
  <span m=''2441960''>fold</span> <span m=''2442180''>along</span> <span m=''2442410''>a</span>
  <span m=''2442470''>bisector.</span> <span m=''2442910''>That</span> <span m=''2443100''>I</span>
  <span m=''2443150''>can</span> <span m=''2443320''>understand.</span> <span m=''2444200''>And</span>
  <span m=''2444460''>then</span> <span m=''2444580''>they</span> <span m=''2444670''>do</span>
  <span m=''2444810''>an</span> <span m=''2444960''>inside</span> <span m=''2445390''>reverse</span>
  <span m=''2445760''>fold.</span> <span m=''2446420''>And</span> <span m=''2446630''>then</span>
  <span m=''2447200''>you</span> <span m=''2447400''>end</span> <span m=''2447630''>up</span>
  <span m=''2447820''>with</span> <span m=''2448520''>1/4</span> <span m=''2449460''>of</span>
  <span m=''2449530''>the</span> <span m=''2449620''>tetrahedron.</span> <span m=''2451560''>So</span>
  <span m=''2451640''>if</span> <span m=''2452030''>you</span> <span m=''2452600''>divide,</span>
  <span m=''2453470''>this</span> <span m=''2453680''>is</span> <span m=''2453740''>the</span>
  <span m=''2453830''>centroid</span> <span m=''2454260''>of</span> <span m=''2454340''>the</span>
  <span m=''2454430''>tetrahedron.</span> <span m=''2456010''>It''s</span> <span m=''2456170''>really</span>
  <span m=''2456360''>hard</span> <span m=''2456570''>to</span> <span m=''2456770''>draw</span>
  <span m=''2457020''>these</span> <span m=''2457190''>pictures.</span> <span m=''2457650''>In</span>
  <span m=''2457900''>the</span> <span m=''2458000''>paper,</span> <span m=''2458400''>they</span>
  <span m=''2458490''>actually</span> <span m=''2458780''>showed</span> <span m=''2459070''>two</span>
  <span m=''2459290''>images,</span> <span m=''2459820''>and</span> <span m=''2459980''>if</span>
  <span m=''2460090''>you</span> <span m=''2460990''>align</span> <span m=''2461360''>them</span>
  <span m=''2461510''>with</span> <span m=''2461790''>your</span> <span m=''2461950''>eyes</span>
  <span m=''2462410''>then</span> <span m=''2462520''>you''ll</span> <span m=''2462690''>see</span>
  <span m=''2462940''>a</span> <span m=''2463000''>3D</span> <span m=''2463370''>image,</span>
  <span m=''2463710''>which</span> <span m=''2463900''>is</span> <span m=''2464050''>of</span>
  <span m=''2464160''>course</span> <span m=''2464390''>a</span> <span m=''2464480''>projection</span>
  <span m=''2464980''>of</span> <span m=''2465080''>the</span> <span m=''2465180''>4D</span>
  <span m=''2465540''>thing.</span> </p><p><span m=''2467350''>They</span> <span m=''2467550''>also</span>
  <span m=''2467850''>have</span> <span m=''2468120''>this</span> <span m=''2468270''>one.</span>
  <span m=''2468900''>Anyone</span> <span m=''2469225''>have</span> <span m=''2469550''>red-blue</span>
  <span m=''2470030''>glasses</span> <span m=''2470420''>with</span> <span m=''2470580''>them?</span>
  <span m=''2470820''>Then</span> <span m=''2470990''>you''ll</span> <span m=''2471120''>see</span>
  <span m=''2471370''>this</span> <span m=''2471660''>in</span> <span m=''2471790''>3D.</span>
  <span m=''2473310''>Here</span> <span m=''2473500''>you</span> <span m=''2473610''>can</span>
  <span m=''2474320''>watch</span> <span m=''2474620''>that</span> <span m=''2475150''>later.</span>
  <span m=''2475530''>This</span> <span m=''2475650''>is</span> <span m=''2475810''>their</span>
  <span m=''2476330''>4D</span> <span m=''2476760''>analog</span> <span m=''2477200''>of</span>
  <span m=''2477330''>a</span> <span m=''2477410''>flapping</span> <span m=''2477840''>bird,</span>
  <span m=''2478230''>I</span> <span m=''2478330''>guess.</span> <span m=''2479520''>It''s</span>
  <span m=''2479620''>pretty</span> <span m=''2479820''>hard</span> <span m=''2479980''>to</span>
  <span m=''2480050''>see</span> <span m=''2480240''>these</span> <span m=''2480420''>pictures,</span>
  <span m=''2480820''>though</span> <span m=''2481110''>But</span> <span m=''2481890''>this</span>
  <span m=''2482070''>is</span> <span m=''2482210''>the</span> <span m=''2482350''>state</span>
  <span m=''2482580''>of</span> <span m=''2482650''>the</span> <span m=''2482780''>art</span>
  <span m=''2483010''>in</span> <span m=''2483270''>4D</span> <span m=''2484050''>origami</span>
  <span m=''2484490''>as</span> <span m=''2484600''>far</span> <span m=''2484740''>as</span>
  <span m=''2484830''>I</span> <span m=''2484930''>know.</span> <span m=''2485730''>It''s</span>
  <span m=''2485810''>kind</span> <span m=''2485900''>of</span> <span m=''2486000''>neat</span>
  <span m=''2486170''>to</span> <span m=''2486250''>find.</span> <span m=''2486490''>This</span>
  <span m=''2486620''>is</span> <span m=''2486730''>a</span> <span m=''2486800''>pretty</span>
  <span m=''2487040''>recent</span> <span m=''2487330''>paper.</span> </p><p><span
  m=''2489650''>Questions</span> <span m=''2490010''>about</span> <span m=''2490210''>higher</span>
  <span m=''2490410''>dimensions?</span> <span m=''2493210''>Lots</span> <span m=''2493480''>of</span>
  <span m=''2493580''>things</span> <span m=''2493810''>are</span> <span m=''2493920''>open.</span>
  <span m=''2496620''>For</span> <span m=''2496770''>example,</span> <span m=''2497100''>single</span>
  <span m=''2497400''>vertex</span> <span m=''2498000''>flat foldability</span> <span
  m=''2498850''>could</span> <span m=''2499010''>be a</span> <span m=''2499120''>neat</span>
  <span m=''2499530''>problem.</span> <span m=''2501120''>I</span> <span m=''2501190''>don''t</span>
  <span m=''2501480''>think--</span> <span m=''2502860''>It</span> <span m=''2503060''>may</span>
  <span m=''2503310''>be</span> <span m=''2503470''>that</span> <span m=''2503600''>Kawasaki''s</span>
  <span m=''2504190''>condition</span> <span m=''2504550''>from</span> <span m=''2504690''>that</span>
  <span m=''2504860''>paper is</span> <span m=''2505260''>enough.</span> <span m=''2505610''>I</span>
  <span m=''2505960''>don''t</span> <span m=''2506120''>know.</span> <span m=''2506790''>Maybe</span>
  <span m=''2506970''>not.</span> </p><p><span m=''2509360''>OK.</span> <span m=''2510240''>Last</span>
  <span m=''2510600''>question,</span> <span m=''2510885''>just</span> <span m=''2511170''>kind</span>
  <span m=''2511320''>of</span> <span m=''2511540''>a</span> <span m=''2511610''>nice</span>
  <span m=''2511910''>place</span> <span m=''2512300''>to</span> <span m=''2512420''>end</span>
  <span m=''2512820''>is,</span> <span m=''2513910''>why</span> <span m=''2514190''>are
  we</span> <span m=''2514420''>spending</span> <span m=''2514830''>all</span> <span
  m=''2514940''>this</span> <span m=''2515070''>time</span> <span m=''2515270''>on</span>
  <span m=''2515330''>flat foldability.</span> <span m=''2516150''>Flat</span> <span
  m=''2516400''>origami''s</span> <span m=''2516830''>kind</span> <span m=''2517010''>of</span>
  <span m=''2517100''>boring.</span> <span m=''2518700''>And</span> <span m=''2519420''>so</span>
  <span m=''2519540''>why</span> <span m=''2519690''>do</span> <span m=''2519780''>we</span>
  <span m=''2519900''>spend</span> <span m=''2520160''>all</span> <span m=''2520280''>this</span>
  <span m=''2520420''>time</span> <span m=''2520630''>with</span> <span m=''2520760''>it?</span>
  <span m=''2521020''>It''s</span> <span m=''2521360''>good</span> <span m=''2521930''>to</span>
  <span m=''2522090''>check</span> <span m=''2523090''>why</span> <span m=''2523290''>are</span>
  <span m=''2523360''>we</span> <span m=''2523470''>doing</span> <span m=''2523710''>this.</span>
  <span m=''2524360''>One</span> <span m=''2524800''>answer</span> <span m=''2525130''>of</span>
  <span m=''2525210''>course</span> <span m=''2525440''>is</span> <span m=''2525590''>that</span>
  <span m=''2525990''>there''s</span> <span m=''2526290''>interesting</span> <span
  m=''2526630''>mathematics</span> <span m=''2527210''>here.</span> <span m=''2528950''>It''s</span>
  <span m=''2529180''>kind</span> <span m=''2529410''>of</span> <span m=''2529500''>a</span>
  <span m=''2529560''>natural</span> <span m=''2530110''>question.</span> <span m=''2530980''>Why</span>
  <span m=''2531210''>not?</span> <span m=''2532020''>That''s</span> <span m=''2532340''>the</span>
  <span m=''2533000''>math</span> <span m=''2533300''>cop-out</span> <span m=''2533790''>answer.</span>
  <span m=''2534850''>But</span> <span m=''2535030''>there are</span> <span m=''2535130''>actually</span>
  <span m=''2535420''>a lot</span> <span m=''2535590''>of</span> <span m=''2536030''>good</span>
  <span m=''2536190''>answers</span> <span m=''2536550''>as</span> <span m=''2536650''>well.</span>
  <span m=''2537480''>One</span> <span m=''2537770''>answer</span> <span m=''2538080''>is</span>
  <span m=''2538200''>that</span> <span m=''2538410''>flat origami</span> <span m=''2538970''>actually</span>
  <span m=''2539260''>is</span> <span m=''2539380''>pretty</span> <span m=''2539610''>cool.</span>
  <span m=''2539980''>There''s</span> <span m=''2540150''>a</span> <span m=''2540200''>whole</span>
  <span m=''2540390''>world</span> <span m=''2540730''>of</span> <span m=''2540990''>flat</span>
  <span m=''2541320''>tessellations,</span> <span m=''2542020''>where</span> <span
  m=''2542340''>you</span> <span m=''2542430''>fold a</span> <span m=''2542750''>repeating</span>
  <span m=''2543130''>pattern</span> <span m=''2543510''>in</span> <span m=''2543690''>your</span>
  <span m=''2544700''>sheet.</span> <span m=''2545060''>This</span> <span m=''2545220''>is</span>
  <span m=''2545330''>from</span> <span m=''2545470''>a</span> <span m=''2545550''>rectangle</span>
  <span m=''2545805''>of</span> <span m=''2546060''>paper.</span> <span m=''2546730''>What</span>
  <span m=''2546850''>you''re</span> <span m=''2546960''>seeing</span> <span m=''2547150''>here</span>
  <span m=''2547250''>is</span> <span m=''2547340''>a</span> <span m=''2547390''>shadow</span>
  <span m=''2547760''>pattern.</span> <span m=''2548140''>It''s</span> <span m=''2548260''>held</span>
  <span m=''2548480''>up</span> <span m=''2548620''>to a</span> <span m=''2548820''>window,</span>
  <span m=''2549570''>and</span> <span m=''2549820''>so</span> <span m=''2549940''>you</span>
  <span m=''2550040''>see</span> <span m=''2550230''>this</span> <span m=''2550560''>shadow</span>
  <span m=''2550820''>pattern,</span> <span m=''2551180''>which</span> <span m=''2551270''>looks</span>
  <span m=''2551460''>an</span> <span m=''2551560''>awful</span> <span m=''2551810''>lot</span>
  <span m=''2552010''>like</span> <span m=''2552240''>a</span> <span m=''2553230''>6</span>
  <span m=''2554390''>by</span> <span m=''2554500''>6</span> <span m=''2554740''>by</span>
  <span m=''2554840''>6</span> <span m=''2555090''>Rubik''s</span> <span m=''2555430''>cube.</span>
  <span m=''2556220''>That''s</span> <span m=''2556650''>the</span> <span m=''2557180''>design</span>
  <span m=''2557550''>here.</span> <span m=''2558420''>You</span> <span m=''2558570''>could</span>
  <span m=''2558710''>make</span> <span m=''2558890''>it</span> <span m=''2559230''>even</span>
  <span m=''2559410''>larger</span> <span m=''2559770''>if</span> <span m=''2559860''>you</span>
  <span m=''2559970''>want.</span> </p><p><span m=''2562030''>Another</span> <span
  m=''2562440''>answer</span> <span m=''2562820''>is,</span> <span m=''2562980''>well,</span>
  <span m=''2563360''>maybe</span> <span m=''2563660''>I</span> <span m=''2563710''>need</span>
  <span m=''2563920''>to</span> <span m=''2564000''>store</span> <span m=''2564320''>stuff.</span>
  <span m=''2564850''>And</span> <span m=''2565080''>while</span> <span m=''2565260''>I</span>
  <span m=''2565370''>can</span> <span m=''2565530''>unfold</span> <span m=''2566000''>things,</span>
  <span m=''2566310''>it''s kind</span> <span m=''2566500''>of</span> <span m=''2566570''>big</span>
  <span m=''2566760''>when</span> <span m=''2566890''>it''s</span> <span m=''2566980''>unfolded.</span>
  <span m=''2567420''>If</span> <span m=''2567530''>I</span> <span m=''2567590''>could</span>
  <span m=''2567740''>fold</span> <span m=''2568060''>it</span> <span m=''2568110''>all</span>
  <span m=''2568240''>the</span> <span m=''2568300''>way</span> <span m=''2568410''>flat--</span>
  <span m=''2568690''>maybe</span> <span m=''2568940''>I</span> <span m=''2568990''>care</span>
  <span m=''2569240''>about the</span> <span m=''2569540''>3D</span> <span m=''2569810''>shape,</span>
  <span m=''2570220''>but</span> <span m=''2570580''>if</span> <span m=''2570740''>I</span>
  <span m=''2570810''>could</span> <span m=''2570980''>fold</span> <span m=''2571240''>it</span>
  <span m=''2571290''>all</span> <span m=''2571440''>the</span> <span m=''2571500''>way</span>
  <span m=''2571630''>flat,</span> <span m=''2572380''>then</span> <span m=''2572610''>it
  would be</span> <span m=''2572730''>easier</span> <span m=''2572990''>to</span>
  <span m=''2573060''>store.</span> <span m=''2573370''>It''s</span> <span m=''2573490''>going</span>
  <span m=''2573590''>to</span> <span m=''2573640''>be</span> <span m=''2573750''>smaller,</span>
  <span m=''2574360''>more</span> <span m=''2574440''>compact,</span> <span m=''2574705''>I</span>
  <span m=''2574970''>can</span> <span m=''2575300''>roll it</span> <span m=''2575640''>up,</span>
  <span m=''2575850''>I</span> <span m=''2576010''>can</span> <span m=''2576100''>do</span>
  <span m=''2576210''>lots</span> <span m=''2576410''>of</span> <span m=''2576500''>things.</span>
  <span m=''2576810''>Airbag</span> <span m=''2577160''>folding</span> <span m=''2577560''>is</span>
  <span m=''2577660''>one</span> <span m=''2577840''>example.</span> <span m=''2578900''>Here</span>
  <span m=''2579120''>you</span> <span m=''2579230''>actually</span> <span m=''2579510''>start</span>
  <span m=''2579840''>with</span> <span m=''2579990''>a</span> <span m=''2580060''>3D</span>
  <span m=''2580390''>shape.</span> <span m=''2580750''>There''s</span> <span m=''2580920''>no</span>
  <span m=''2581100''>sort</span> <span m=''2581280''>of</span> <span m=''2581380''>unfold.</span>
  <span m=''2581830''>It''s</span> <span m=''2582060''>been</span> <span m=''2582220''>sewn</span>
  <span m=''2582640''>into</span> <span m=''2582860''>a</span> <span m=''2582940''>3D</span>
  <span m=''2583220''>shape.</span> <span m=''2583980''>And</span> <span m=''2584170''>then</span>
  <span m=''2584310''>you</span> <span m=''2584420''>want</span> <span m=''2584560''>to</span>
  <span m=''2584640''>collapse</span> <span m=''2585090''>it</span> <span m=''2585180''>into</span>
  <span m=''2585390''>some</span> <span m=''2585620''>nice</span> <span m=''2585890''>flat</span>
  <span m=''2586160''>shape</span> <span m=''2586790''>for</span> <span m=''2587110''>storage</span>
  <span m=''2587540''>in</span> <span m=''2587630''>your</span> <span m=''2587770''>steering</span>
  <span m=''2588120''>wheel,</span> <span m=''2588440''>or</span> <span m=''2588570''>the</span>
  <span m=''2588680''>side</span> <span m=''2588890''>of</span> <span m=''2588980''>your</span>
  <span m=''2589080''>car,</span> <span m=''2589390''>or</span> <span m=''2589440''>whatever.</span>
  <span m=''2590260''>And</span> <span m=''2591450''>this</span> <span m=''2592050''>is</span>
  <span m=''2592260''>an</span> <span m=''2592340''>example</span> <span m=''2592760''>of</span>
  <span m=''2593330''>folding</span> <span m=''2594160''>using</span> <span m=''2594610''>flat</span>
  <span m=''2595440''>origami</span> <span m=''2596210''>designs.</span> <span m=''2596710''>This</span>
  <span m=''2597140''>crease</span> <span m=''2597370''>pattern is</span> <span m=''2597820''>based</span>
  <span m=''2598110''>on</span> <span m=''2598815''>the</span> <span m=''2599240''>tree</span>
  <span m=''2599440''>method,</span> <span m=''2601000''>and</span> <span m=''2602410''>other</span>
  <span m=''2602620''>stuff</span> <span m=''2602830''>we</span> <span m=''2602910''>haven''t</span>
  <span m=''2603130''>covered</span> <span m=''2603390''>yet,</span> <span m=''2603580''>fold
  and</span> <span m=''2603870''>cut.</span> <span m=''2605530''>So</span> <span m=''2606310''>that''s</span>
  <span m=''2606650''>another.</span> <span m=''2607250''>That''s</span> <span m=''2607420''>sort</span>
  <span m=''2607590''>of</span> <span m=''2607640''>the</span> <span m=''2607720''>practical</span>
  <span m=''2608250''>answer.</span> </p><p><span m=''2609650''>And</span> <span m=''2609850''>then</span>
  <span m=''2609990''>there''s</span> <span m=''2610690''>more</span> <span m=''2610970''>mathematical</span>
  <span m=''2611610''>answers,</span> <span m=''2611940''>deeper</span> <span m=''2612240''>things.</span>
  <span m=''2612500''>Even</span> <span m=''2612750''>if</span> <span m=''2612870''>you</span>
  <span m=''2612970''>don''t</span> <span m=''2613150''>care</span> <span m=''2613340''>about</span>
  <span m=''2613580''>flat</span> <span m=''2613790''>folding</span> <span m=''2614090''>by</span>
  <span m=''2614260''>itself,</span> <span m=''2615120''>it</span> <span m=''2615300''>turns</span>
  <span m=''2615540''>out</span> <span m=''2615680''>to</span> <span m=''2615780''>relate</span>
  <span m=''2616040''>to</span> <span m=''2616130''>3D</span> <span m=''2616490''>folding</span>
  <span m=''2616840''>as</span> <span m=''2616930''>well.</span> <span m=''2617710''>This</span>
  <span m=''2617970''>is</span> <span m=''2618090''>a</span> <span m=''2618170''>paper</span>
  <span m=''2618830''>that''s</span> <span m=''2619030''>very</span> <span m=''2619200''>cool.</span>
  <span m=''2620500''>We</span> <span m=''2620940''>have</span> <span m=''2621250''>a</span>
  <span m=''2621810''>guest</span> <span m=''2622040''>lecture</span> <span m=''2622300''>by</span>
  <span m=''2622430''>Tomohiro</span> <span m=''2622810''>Tachi</span> <span m=''2623210''>coming</span>
  <span m=''2623560''>up. I</span> <span m=''2623920''>haven''t</span> <span m=''2624220''>scheduled</span>
  <span m=''2624660''>exactly</span> <span m=''2625030''>when</span> <span m=''2625180''>it</span>
  <span m=''2625240''>will</span> <span m=''2625370''>be,</span> <span m=''2626430''>because</span>
  <span m=''2626650''>it''s</span> <span m=''2626870''>in</span> <span m=''2627060''>the</span>
  <span m=''2628740''>in</span> <span m=''2628920''>the</span> <span m=''2629000''>box.</span>
  <span m=''2629770''>It''s</span> <span m=''2630870''>on</span> <span m=''2631070''>tape.</span>
  <span m=''2632220''>So</span> <span m=''2632400''>we''ll</span> <span m=''2632530''>be</span>
  <span m=''2632650''>watching</span> <span m=''2632960''>that</span> <span m=''2633190''>at</span>
  <span m=''2633270''>some</span> <span m=''2633420''>point.</span> <span m=''2633580''>He</span>
  <span m=''2633660''>was</span> <span m=''2633770''>actually</span> <span m=''2634010''>just</span>
  <span m=''2634200''>visiting a</span> <span m=''2634640''>couple</span> <span m=''2634910''>weeks</span>
  <span m=''2635150''>ago.</span> <span m=''2636580''>And</span> <span m=''2636650''>he</span>
  <span m=''2636750''>has</span> <span m=''2636880''>this</span> <span m=''2637020''>cool</span>
  <span m=''2637240''>theorem</span> <span m=''2637600''>which</span> <span m=''2637680''>says</span>
  <span m=''2637970''>that</span> <span m=''2638080''>if</span> <span m=''2638220''>you</span>
  <span m=''2638330''>have</span> <span m=''2639410''>a</span> <span m=''2639490''>plane</span>
  <span m=''2639840''>or</span> <span m=''2639950''>quad</span> <span m=''2640360''>mesh--</span>
  <span m=''2640750''>so a</span> <span m=''2640910''>particular</span> <span m=''2641370''>kind</span>
  <span m=''2641640''>of</span> <span m=''2641730''>crease</span> <span m=''2641950''>pattern,</span>
  <span m=''2642230''>every</span> <span m=''2642400''>vertex</span> <span m=''2643170''>has</span>
  <span m=''2643330''>four</span> <span m=''2643600''>incident</span> <span m=''2643810''>increases,</span>
  <span m=''2644440''>every</span> <span m=''2645120''>face</span> <span m=''2645490''>is</span>
  <span m=''2645820''>a</span> <span m=''2645900''>quadrilateral--</span> <span m=''2647170''>and</span>
  <span m=''2647460''>it''s</span> <span m=''2647600''>flat</span> <span m=''2647900''>foldable--</span>
  <span m=''2649130''>so</span> <span m=''2649310''>you</span> <span m=''2649490''>may</span>
  <span m=''2649630''>not</span> <span m=''2649820''>care</span> <span m=''2650000''>about</span>
  <span m=''2650180''>flat foldability,</span> <span m=''2650870''>but</span> <span
  m=''2651040''>you</span> <span m=''2651150''>need</span> <span m=''2651490''>this</span>
  <span m=''2651700''>Kawasaki</span> <span m=''2652250''>condition</span> <span m=''2652600''>to</span>
  <span m=''2652650''>guarantee</span> <span m=''2653090''>that</span> <span m=''2653260''>this</span>
  <span m=''2653500''>will</span> <span m=''2653650''>work--</span> <span m=''2654480''>then</span>
  <span m=''2654800''>it</span> <span m=''2654890''>has</span> <span m=''2655170''>a</span>
  <span m=''2655330''>rigid</span> <span m=''2655730''>folding</span> <span m=''2656160''>motion,</span>
  <span m=''2656610''>if</span> <span m=''2656810''>and</span> <span m=''2656890''>only</span>
  <span m=''2657170''>if</span> <span m=''2657360''>it</span> <span m=''2657460''>has</span>
  <span m=''2657760''>a</span> <span m=''2657840''>3D</span> <span m=''2658230''>state.</span>
  </p><p><span m=''2659150''>Let</span> <span m=''2659290''>me</span> <span m=''2659390''>show</span>
  <span m=''2659620''>you</span> <span m=''2660700''>some</span> <span m=''2660980''>examples.</span>
  <span m=''2661540''>So</span> <span m=''2661800''>this</span> <span m=''2662200''>a</span>
  <span m=''2662580''>kind</span> <span m=''2662740''>of</span> <span m=''2662810''>a</span>
  <span m=''2662890''>classic</span> <span m=''2663410''>origami</span> <span m=''2663990''>called</span>
  <span m=''2664300''>miura-ori.</span> <span m=''2666010''>And</span> <span m=''2666250''>it</span>
  <span m=''2666330''>has</span> <span m=''2666540''>this</span> <span m=''2666690''>cool</span>
  <span m=''2666880''>property that</span> <span m=''2667280''>even</span> <span m=''2667690''>if</span>
  <span m=''2667800''>these</span> <span m=''2667970''>panels</span> <span m=''2668510''>are</span>
  <span m=''2668580''>made</span> <span m=''2668810''>up</span> <span m=''2668990''>out
  of</span> <span m=''2669480''>rigid</span> <span m=''2669520''>material</span> <span
  m=''2669900''>like</span> <span m=''2670280''>sheet</span> <span m=''2670540''>metal</span>
  <span m=''2671390''>or</span> <span m=''2671650''>plastic</span> <span m=''2671945''>or</span>
  <span m=''2672240''>whatever,</span> <span m=''2673600''>if</span> <span m=''2673860''>these</span>
  <span m=''2674050''>are</span> <span m=''2674120''>hinges</span> <span m=''2674740''>you</span>
  <span m=''2674870''>can</span> <span m=''2675030''>still</span> <span m=''2675290''>fold</span>
  <span m=''2675630''>it.</span> <span m=''2675760''>And</span> <span m=''2675880''>this</span>
  <span m=''2676020''>is</span> <span m=''2676140''>an</span> <span m=''2676210''>animation</span>
  <span m=''2676680''>of</span> <span m=''2676770''>it</span> <span m=''2676840''>folding.</span>
  <span m=''2677450''>And</span> <span m=''2677650''>indeed</span> <span m=''2678020''>it</span>
  <span m=''2678190''>folds</span> <span m=''2678470''>flat.</span> <span m=''2679620''>And</span>
  <span m=''2679810''>what</span> <span m=''2679930''>the</span> <span m=''2680040''>theorem</span>
  <span m=''2680340''>is</span> <span m=''2680430''>saying</span> <span m=''2680850''>is</span>
  <span m=''2681260''>if</span> <span m=''2681450''>you</span> <span m=''2681600''>can</span>
  <span m=''2682030''>build</span> <span m=''2682510''>a</span> <span m=''2682560''>3D</span>
  <span m=''2682880''>picture</span> <span m=''2683200''>like</span> <span m=''2683380''>this,</span>
  <span m=''2683810''>any</span> <span m=''2684090''>one</span> <span m=''2684320''>of</span>
  <span m=''2684420''>these,</span> <span m=''2685310''>that</span> <span m=''2685520''>guarantees</span>
  <span m=''2686120''>that</span> <span m=''2686280''>there''s</span> <span m=''2686480''>this</span>
  <span m=''2687020''>folding</span> <span m=''2687370''>motion--</span> <span m=''2688760''>not</span>
  <span m=''2688910''>necessarily</span> <span m=''2689300''>all</span> <span m=''2689510''>the</span>
  <span m=''2689580''>way</span> <span m=''2689710''>to</span> <span m=''2689790''>flat,</span>
  <span m=''2690240''>but</span> <span m=''2690410''>at</span> <span m=''2690470''>least</span>
  <span m=''2691110''>part</span> <span m=''2691350''>way</span> <span m=''2691470''>to</span>
  <span m=''2691550''>flat.</span> <span m=''2691960''>And</span> <span m=''2692110''>often</span>
  <span m=''2692370''>you can</span> <span m=''2692470''>get</span> <span m=''2692610''>it</span>
  <span m=''2692770''>all</span> <span m=''2692900''>the</span> <span m=''2692960''>way</span>
  <span m=''2693070''>to</span> <span m=''2693160''>flat.</span> </p><p><span m=''2693900''>And</span>
  <span m=''2694060''>so</span> <span m=''2694880''>Tomohiro''s</span> <span m=''2695440''>developed</span>
  <span m=''2695810''>software</span> <span m=''2696690''>that</span> <span m=''2696820''>lets</span>
  <span m=''2697090''>you</span> <span m=''2698240''>start</span> <span m=''2698570''>with</span>
  <span m=''2698660''>something you</span> <span m=''2698950''>know works--</span>
  <span m=''2699710''>so</span> <span m=''2700020''>this</span> <span m=''2700200''>is</span>
  <span m=''2700340''>a</span> <span m=''2700410''>miura-ori</span> <span m=''2701070''>that''s</span>
  <span m=''2701300''>been</span> <span m=''2701440''>folded</span> <span m=''2701800''>partly--</span>
  <span m=''2702720''>and</span> <span m=''2702820''>then</span> <span m=''2702920''>just</span>
  <span m=''2702990''>start</span> <span m=''2703290''>pulling</span> <span m=''2703630''>on</span>
  <span m=''2703710''>the</span> <span m=''2703780''>vertices</span> <span m=''2704370''>and</span>
  <span m=''2704450''>messing</span> <span m=''2704790''>it</span> <span m=''2704850''>up</span>
  <span m=''2705100''>and</span> <span m=''2705210''>just</span> <span m=''2705500''>changing</span>
  <span m=''2705920''>the</span> <span m=''2706000''>shapes.</span> <span m=''2706380''>So</span>
  <span m=''2707830''>this</span> <span m=''2708140''>is</span> <span m=''2708230''>not</span>
  <span m=''2708390''>a</span> <span m=''2708440''>folding.</span> <span m=''2709480''>You''re</span>
  <span m=''2709670''>changing</span> <span m=''2710090''>how</span> <span m=''2710290''>the</span>
  <span m=''2710400''>paper</span> <span m=''2710700''>fits</span> <span m=''2710950''>together.</span>
  <span m=''2711300''>You''re</span> <span m=''2711440''>changing</span> <span m=''2711840''>the</span>
  <span m=''2711920''>crease</span> <span m=''2712150''>pattern.</span> <span m=''2712910''>As</span>
  <span m=''2713120''>you</span> <span m=''2713220''>do</span> <span m=''2713360''>that,</span>
  <span m=''2713570''>he</span> <span m=''2713710''>keeps</span> <span m=''2713920''>track</span>
  <span m=''2714160''>of</span> <span m=''2714220''>the</span> <span m=''2714290''>crease</span>
  <span m=''2714520''>pattern</span> <span m=''2715290''>and</span> <span m=''2715490''>he</span>
  <span m=''2715650''>adds</span> <span m=''2715950''>constraints</span> <span m=''2716970''>to</span>
  <span m=''2717100''>make</span> <span m=''2717250''>sure</span> <span m=''2717370''>that</span>
  <span m=''2717510''>it</span> <span m=''2717610''>stays</span> <span m=''2717910''>flat</span>
  <span m=''2718190''>foldable.</span> <span m=''2719310''>The</span> <span m=''2719410''>result</span>
  <span m=''2719810''>is</span> <span m=''2719960''>you</span> <span m=''2720090''>end</span>
  <span m=''2720240''>up</span> <span m=''2720350''>with</span> <span m=''2720500''>a</span>
  <span m=''2720570''>3D</span> <span m=''2721130''>embedding,</span> <span m=''2722410''>a</span>
  <span m=''2722500''>3D</span> <span m=''2722890''>folding,</span> <span m=''2724300''>and</span>
  <span m=''2724660''>you</span> <span m=''2724750''>have a</span> <span m=''2724930''>flat</span>
  <span m=''2725170''>foldable</span> <span m=''2725530''>crease</span> <span m=''2725790''>pattern
  that</span> <span m=''2726050''>goes</span> <span m=''2726240''>with</span> <span
  m=''2726430''>it.</span> <span m=''2726760''>And</span> <span m=''2726810''>that</span>
  <span m=''2727040''>guarantees</span> <span m=''2727320''>that</span> <span m=''2727600''>you</span>
  <span m=''2727700''>get a</span> <span m=''2727970''>motion.</span> <span m=''2728890''>Those</span>
  <span m=''2729120''>two</span> <span m=''2729270''>things.</span> <span m=''2729630''>So</span>
  <span m=''2729710''>this</span> <span m=''2730700''>technique</span> <span m=''2731550''>of</span>
  <span m=''2731710''>having</span> <span m=''2732040''>flat foldability</span> <span
  m=''2733210''>lets</span> <span m=''2733460''>him</span> <span m=''2733580''>design</span>
  <span m=''2734100''>crazy</span> <span m=''2734570''>crease</span> <span m=''2734810''>patterns</span>
  <span m=''2735680''>that</span> <span m=''2735810''>fold</span> <span m=''2736140''>into</span>
  <span m=''2736850''>whatever</span> <span m=''2737240''>shape</span> <span m=''2737550''>he</span>
  <span m=''2737710''>wants</span> <span m=''2739070''>with</span> <span m=''2739410''>a</span>
  <span m=''2739470''>nice</span> <span m=''2739730''>rigid</span> <span m=''2740020''>motion</span>
  <span m=''2740330''>where</span> <span m=''2740450''>all</span> <span m=''2740570''>these</span>
  <span m=''2740720''>panels</span> <span m=''2741060''>stay</span> <span m=''2741940''>rigid.</span>
  <span m=''2744020''>So</span> <span m=''2744620''>that''s</span> <span m=''2744850''>another</span>
  <span m=''2745810''>motivation</span> <span m=''2746380''>for</span> <span m=''2746830''>flat</span>
  <span m=''2747250''>foldability.</span> <span m=''2748666''>It''s</span> <span m=''2749010''>probably</span>
  <span m=''2749340''>used</span> <span m=''2749560''>elsewhere</span> <span m=''2749900''>as</span>
  <span m=''2749990''>well,</span> <span m=''2750170''>but</span> <span m=''2750290''>this</span>
  <span m=''2750460''>is</span> <span m=''2750580''>kind</span> <span m=''2750740''>of</span>
  <span m=''2750850''>the</span> <span m=''2751460''>coolest,</span> <span m=''2752220''>newest</span>
  <span m=''2752690''>example</span> <span m=''2753120''>I</span> <span m=''2753300''>know,</span>
  <span m=''2754390''>where</span> <span m=''2754630''>it''s</span> <span m=''2754730''>just</span>
  <span m=''2754910''>a</span> <span m=''2754950''>condition in</span> <span m=''2755380''>the</span>
  <span m=''2755500''>theorem,</span> <span m=''2755870''>and</span> <span m=''2756060''>in</span>
  <span m=''2756190''>order</span> <span m=''2756310''>to</span> <span m=''2756420''>check</span>
  <span m=''2756650''>that</span> <span m=''2756800''>condition</span> <span m=''2757230''>you</span>
  <span m=''2757320''>need</span> <span m=''2757480''>to</span> <span m=''2757540''>understand</span>
  <span m=''2758130''>flat foldability.</span> </p><p><span m=''2761460''>Other</span>
  <span m=''2761630''>questions?</span> <span m=''2764560''>That''s all</span> <span
  m=''2764760''>I</span> <span m=''2764870''>have</span> <span m=''2765080''>for</span>
  <span m=''2765750''>slides.</span> <span m=''2771530''>Cool.</span> <span m=''2773370''>That''s</span>
  <span m=''2773650''>the</span> <span m=''2773770''>end</span> <span m=''2774140''>of</span>
  <span m=''2774310''>class.</span> </p>'
type: course
uid: 87aeeef4bdff5c2fa8d7af79b364fe4a

---
None