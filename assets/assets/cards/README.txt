카드 안쪽 그림 바꾸기
====================

카드 테두리 안쪽 그림 칸은 기본으로 "등급별 한 가지 색 배경 + 코드로 그린 기술 아이콘"입니다.
이 폴더에 아래 이름으로 PNG(또는 같은 이름의 JPG는 안 됨, PNG만)를 넣고 다시 빌드하면 그 그림으로 바뀝니다.

1) 등급별 안쪽 배경 (그림 칸 전체를 채움, 아이콘은 그 위에 그려짐)
   bg_common.png      일반
   bg_uncommon.png    고급
   bg_rare.png        희귀
   bg_epic.png        영웅
   bg_legendary.png   전설
   bg_mythic.png      신화
   bg_immortal.png    불멸

2) 기술별 안쪽 그림 (있으면 아이콘 대신 이 그림을 그림 칸에 꽉 채움)
   skill_arrow.png       마법 화살
   skill_blade.png       회전 칼날
   skill_bomb.png        폭탄
   skill_fireball.png    파이어볼
   skill_flameField.png  화염 장판
   skill_hydra.png       히드라
   skill_lightning.png   번개
   skill_laser.png       레이저
   skill_chain.png       체인 라이트닝
   skill_steelSkin.png   강철 피부
   skill_regen.png       재생
   skill_swift.png       신속
   skill_shield.png      보호막
   skill_heart.png       생명의 심장
   skill_magnet.png      자석
   skill_vampire.png     흡혈
   skill_venom.png       중독
   skill_thorns.png      가시 갑옷

권장 크기: 가로 512 × 세로 446 (비율 약 8:7). 다른 비율이면 가운데를 기준으로 잘라서 채웁니다.
그림 칸의 기본 배경색(코드): lib/game/defs.dart 의 kRarityInner
