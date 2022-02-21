# Undead Legacy 한글 번역 기록

1. [Undead Legacy 2.5.49](#undead-legacy-2549)
1. [Undead Legacy 2.5.48](#undead-legacy-2548)
      * [2.5.48 추가](#2548-추가)
      * [2.5.48 삭제](#2548-삭제)
      * [2.5.48 변경](#2548-변경)
3. [Undead Legacy 2.5.47](#undead-legacy-2547)
      * [2.5.47 삭제](#2547-삭제)
      * [2.5.47 누락](#2547-누락)
      * [제가 변경한 것](#제가-변경한-것)
      * [용어 정리 기록용](#용어-정리-기록용)

* [Bug](#Bug)
* [특이사항](#특이사항)

---

# Undead Legacy 2.5.49

* Localization.txt 변경 없음.
* buffs.xml
    * 방어구 손상도 버프 관련 수정



---

## Bug 

* 드론 전문가 (~2.5.49)
     * 설명은 25%-200%이나 실제 적용 값은 20%-100%
          * ulmPerkDroneSpecialist1,"Drone carry weight limit increased by [decea3]25%[-] units"
          * ulmPerkDroneSpecialist2,"Drone carry weight limit increased by [decea3]50%[-] units"
          * ulmPerkDroneSpecialist3,"Drone carry weight limit increased by [decea3]100%[-] units"
          * ulmPerkDroneSpecialist4,"Drone carry weight limit increased by [decea3]150%[-] units"
          * ulmPerkDroneSpecialist5,"Drone carry weight limit increased by [decea3]200%[-] units"

## 특이사항

* uiTotal,"Total: {0}"
* opt0P,"Disabled"
* opt100P,"Standard"

---

# Undead Legacy 2.5.48

## 2.5.48 추가

1. 액션 스킬 레벨업 개별 메시지 -> uiActionSkillLevelUp 하나로 통합
     * uiActionSkillLevelUp,"Your [decea3]{0}[-] skill has improved to level [decea3]{1}[-]!"
     * uiActionSkillLevelUp,"[decea3]{0}[-] 액션 스킬이 [decea3]{1}[-] 레벨로 향상되었습니다!"
1. 군 잠행용 부츠 설명 추가, armorMilitaryStealthBoots
     * armorMilitaryStealthBootsDesc,"These boots have no stamina use penalty and muffle noise from movement."
     * armorMilitaryStealthBootsDesc,"이 부츠는 스태미너 소모 페널티와 이동으로 인한 소음이 없습니다"
1. 야간 투시경 설명 바닐라에서 변경
     * apparelNightvisionGoggles,"Night Vision Goggles"
     * apparelNightvisionGoggles,"야간 투시경"
     * apparelNightvisionGogglesDesc,"These night vision goggles provide a little face protection and when activated allow you to see better in the dark."
     * apparelNightvisionGogglesDesc,"이 야간 투시경은 얼굴을 약간 보호해주고 작동하면 어둠 속에서도 더 잘 볼 수 있습니다."
1. 방어구 손상도 버프 추가
     * Damaged, 손상된
     * Broken, 부서진
     * Headgear, 투구
     * Chest Armor, 가슴 방어구
     * Gloves, 장갑
     * Leg Armor, 다리 갑옷
     * Boots, 부츠
     * ulmBuffArmorDamagedHead,"Damaged Headgear"
          * ulmBuffArmorDamagedHead,"손상된 투구"
          * ulmBuffArmorDamagedHeadDesc,"Your [decea3]Headgear[-] is damaged."
          * ulmBuffArmorDamagedHeadDesc,"[decea3]투구[-]가 손상되었습니다."
          * ulmBuffArmorDamagedChest,"Damaged Chest Armor"
          * ulmBuffArmorDamagedChest,"손상된 가슴 방어구"
          * ulmBuffArmorDamagedChestDesc,"Your [decea3]Chest Armor[-] is damaged."
          * ulmBuffArmorDamagedChestDesc,"[decea3]가슴 방어구[-]가 손상되었습니다."
          * ulmBuffArmorDamagedHands,"Damaged Gloves"
          * ulmBuffArmorDamagedHands,"손상된 장갑"
          * ulmBuffArmorDamagedHandsDesc,"Your [decea3]Gloves[-] are damaged."
          * ulmBuffArmorDamagedHandsDesc,"[decea3]장갑[-]이 손상되었습니다."
          * ulmBuffArmorDamagedLegs,"Damaged Leg Armor"
          * ulmBuffArmorDamagedLegs,"손상된 다리 갑옷"
          * ulmBuffArmorDamagedLegsDesc,"Your [decea3]Leg Armor[-] is damaged."
          * ulmBuffArmorDamagedLegsDesc,"[decea3]다리 갑옷[-]이 손상되었습니다."
          * ulmBuffArmorDamagedFeet,"Damaged Boots"
          * ulmBuffArmorDamagedFeet,"손상된 부츠"
          * ulmBuffArmorDamagedFeetDesc,"Your [decea3]Boots[-] are damaged."
          * ulmBuffArmorDamagedFeetDesc,"[decea3]부츠[-]가 손상되었습니다."
          * ulmBuffArmorBrokenHead,"Broken Headgear"
          * ulmBuffArmorBrokenHead,"부서진 투구"
          * ulmBuffArmorBrokenHeadDesc,"Your [decea3]Headgear[-] is broken."
          * ulmBuffArmorBrokenHeadDesc,"[decea3]투구[-]가 부서졌습니다."
          * ulmBuffArmorBrokenChest,"Broken Chest Armor"
          * ulmBuffArmorBrokenChest,"부서진 가슴 방어구"
          * ulmBuffArmorBrokenChestDesc,"Your [decea3]Chest Armor[-] is broken."
          * ulmBuffArmorBrokenChestDesc,"[decea3]가슴 방어구[-]가 부서졌습니다."
          * ulmBuffArmorBrokenHands,"Broken Gloves"
          * ulmBuffArmorBrokenHands,"부서진 장갑"
          * ulmBuffArmorBrokenHandsDesc,"Your [decea3]Gloves[-] are broken."
          * ulmBuffArmorBrokenHandsDesc,"[decea3]장갑[-]이 부서졌습니다."
          * ulmBuffArmorBrokenLegs,"Broken Leg Armor"
          * ulmBuffArmorBrokenLegs,"부서진 다리 갑옷"
          * ulmBuffArmorBrokenLegsDesc,"Your [decea3]Leg Armor[-] is broken."
          * ulmBuffArmorBrokenLegsDesc,"[decea3]다리 갑옷[-]이 부서졌습니다."
          * ulmBuffArmorBrokenFeet,"Broken Boots"
          * ulmBuffArmorBrokenFeet,"부서진 부츠"
          * ulmBuffArmorBrokenFeetDesc,"Your [decea3]Boots[-] are broken."
          * ulmBuffArmorBrokenFeetDesc,"[decea3]부츠[-]가 부서졌습니다."

---

## 2.5.48 삭제

1. ulmMeleeKnifeBayonet,"총검"
1. ulmMeleeKnifeBayonetDesc,"나무를 잘라 [decea3]송진[-]을 얻는 데 유용하며, 선인장을 잘라 [decea3]유카[-]를 얻는데 좋습니다. 동물 내장을 제거하는데도 유용합니다."
1. ulmMeleeKnifeCleaver,"식칼"
1. 액션 스킬 레벨업 통합에 따른 개별 메시지 삭제
    * actionPerkSniperRiflesLevelUp,"[decea3]저격용 소총[-] 액션 스킬이 향상되었습니다!"
    * actionPerkArcheryLevelUp,"[decea3]활과 석궁[-] 액션 스킬이 향상되었습니다!"
    * actionPerkSpearsLevelUp,"[decea3]창[-] 액션 스킬이 향상되었습니다!"
    * actionPerkLockPickingLevelUp,"[decea3]자물쇠 따기[-] 액션 스킬이 향상되었습니다!"
    * actionPerkLootingLevelUp,"[decea3]아이템 획득[-] 액션 스킬이 향상되었습니다!"
    * actionPerkButcherLevelUp,"[decea3]동물 수확[-] 액션 스킬이 향상되었습니다!"
    * actionPerkStrengthLevelUp,"[decea3]역도[-] 액션 스킬이 향상되었습니다!"
    * actionPerkAssaultRiflesLevelUp,"[decea3]기관총[-] 액션 스킬이 향상되었습니다!"
    * actionPerkClubsLevelUp,"[decea3]곤봉[-] 액션 스킬이 향상되었습니다!"
    * actionPerkSledgehammersLevelUp,"[decea3]슬레지 해머[-] 액션 스킬이 향상되었습니다!"
    * actionPerkAxesLevelUp,"[decea3]벌목 도구[-] 액션 스킬이 향상되었습니다!"
    * actionPerkShovelsLevelUp,"[decea3]발굴 도구[-] 액션 스킬이 향상되었습니다!"
    * actionPerkMiningLevelUp,"[decea3]채광 도구[-] 액션 스킬이 향상되었습니다!"
    * actionPerkShotgunsLevelUp,"[decea3]샷건[-] 액션 스킬이 향상되었습니다!"
    * actionPerkBrawlerLevelUp,"[decea3]싸움꾼[-] 액션 스킬이 향상되었습니다!"
    * actionPerkResistHeatLevelUp,"[decea3]더위 저항[-] 액션 스킬이 향상되었습니다!"
    * actionPerkResistColdLevelUp,"[decea3]추위 저항[-] 액션 스킬이 향상되었습니다!"
    * actionPerkResistPainLevelUp,"[decea3]고통 저항[-] 액션 스킬이 향상되었습니다!"
    * actionPerkHealingLevelUp,"[decea3]회복[-] 액션 스킬이 향상되었습니다!"
    * actionPerkHandgunsLevelUp,"[decea3]권총[-] 액션 스킬이 향상되었습니다!"
    * actionPerkBladesLevelUp,"[decea3]검과 단검[-] 액션 스킬이 향상되었습니다!"
    * actionPerkAthleticsLevelUp,"[decea3]육상[-] 액션 스킬이 향상되었습니다!"
    * actionPerkSneakingLevelUp,"[decea3]은신[-] 액션 스킬이 향상되었습니다!"
    * actionPerkAssasinLevelUp,"[decea3]암살[-] 액션 스킬이 향상되었습니다!"
    * actionPerkSubmachineGunsLevelUp,"[decea3]기관단총[-] 액션 스킬이 향상되었습니다!"
    * actionPerkExplosivesLevelUp,"[decea3]폭발물[-] 액션 스킬이 향상되었습니다!"
    * actionPerkShockersLevelUp,"[decea3]진압봉[-] 액션 스킬이 향상되었습니다!"
    * actionPerkTurretsLevelUp,"[decea3]포탑[-] 액션 스킬이 향상되었습니다!"
    * actionPerkTradingLevelUp,"[decea3]거래[-] 액션 스킬이 향상되었습니다!"
    * actionPerkQuestingLevelUp,"[decea3]퀘스트[-] 액션 스킬이 향상되었습니다!"
    * actionPerkSalvagingLevelUp,"[decea3]분해 도구[-] 액션 스킬이 향상되었습니다!"
    * 
---

## 2.5.48 변경

1. 진압봉
    * ulmBookShockers,"Baton Weapons"
    * ulmBookShockersDesc,"Reading this skill book will increase your level in [decea3]Baton Weapons[-] action skill by [decea3]1[-]."
1. 아이템 획득, actionPerkLooting
    * 아이템 획득 속도 8%-40%에서 10%-50%로 변경
    * actionPerkLooting1,"아이템 획득 속도 [decea3]+10%[-]\n전리품 스테이지 [decea3]+5%[-] 증가"
    * actionPerkLooting2,"아이템 획득 속도 [decea3]+20%[-]\n전리품 스테이지 [decea3]+10%[-] 증가"
    * actionPerkLooting3,"아이템 획득 속도 [decea3]+30%[-]\n전리품 스테이지 [decea3]+15%[-] 증가"
    * actionPerkLooting4,"아이템 획득 속도 [decea3]+40%[-]\n전리품 스테이지 [decea3]+20%[-] 증가"
    * actionPerkLooting5,"아이템 획득 속도 [decea3]+50%[-]\n전리품 스테이지 [decea3]+25%[-] 증가"
1. 멋진 교환자, perkBetterBarter
    * 3,4,5렙에 있던 상인 뒷거래 아이템 수량 보너스 삭제
    * 사고 파는 아이템 가격 4%-20%에서 5%-25%로 변경
    * perkBetterBarter1,"상인에게 사고 파는 아이템 가격이 [decea3]5%[-] 좋아짐."
    * perkBetterBarter2,"상인에게 사고 파는 아이템 가격이 [decea3]10%[-] 좋아짐."
    * perkBetterBarter3,"상인에게 사고 파는 아이템 가격이 [decea3]15%[-] 좋아짐."
    * perkBetterBarter4,"상인에게 사고 파는 아이템 가격이 [decea3]20%[-] 좋아짐."
    * perkBetterBarter5,"상인에게 사고 파는 아이템 가격이 [decea3]25%[-] 좋아짐."
1. 거래 액션 스킬, actionPerkTrading
    * 1,2,3,4,5렙에 상인 뒷거래 아이템 수량 보너스 추가
    * 상인에게 사는 아이템 가격 좋아짐 삭제
    * 상인에게 파는 아이템 가격 4%-20%에서 5%-25%로 변경
    * actionPerkTrading1,"상인에게 파는 아이템 가격이 [decea3]5%[-] 좋아짐.\n상인과의 뒷거래 아이템 수량이 [decea3]+1[-] 증가함."
    * actionPerkTrading2,"상인에게 파는 아이템 가격이 [decea3]10%[-] 좋아짐.\n상인과의 뒷거래 아이템 수량이 [decea3]+2[-] 증가함."
    * actionPerkTrading3,"상인에게 파는 아이템 가격이 [decea3]15%[-] 좋아짐.\n상인과의 뒷거래 아이템 수량이 [decea3]+3[-] 증가함."
    * actionPerkTrading4,"상인에게 파는 아이템 가격이 [decea3]20%[-] 좋아짐.\n상인과의 뒷거래 아이템 수량이 [decea3]+4[-] 증가함."
    * actionPerkTrading5,"상인에게 파는 아이템 가격이 [decea3]25%[-] 좋아짐.\n상인과의 뒷거래 아이템 수량이 [decea3]+5[-] 증가함."
1. 운 좋은 약탈자, perkLuckyLooter
    * 전리품 탐색 속도 8%-40%에서 10%-50%로 변경
          * perkLuckyLooter1,"전리품 탐색 속도가 [decea3]10%[-] 빨라짐.\n전리품 스테이지 [decea3]+5%[-] 증가."
          * perkLuckyLooter2,"전리품 탐색 속도가 [decea3]20%[-] 빨라짐.\n전리품 스테이지 [decea3]+10%[-] 증가."
          * perkLuckyLooter3,"전리품 탐색 속도가 [decea3]30%[-] 빨라짐.\n전리품 스테이지 [decea3]+15%[-] 증가."
          * perkLuckyLooter4,"전리품 탐색 속도가 [decea3]40%[-] 빨라짐.\n전리품 스테이지 [decea3]+20%[-] 증가."
          * perkLuckyLooter5,"전리품 탐색 속도가 [decea3]50%[-] 빨라짐.\n전리품 스테이지 [decea3]+25%[-] 증가."


---

# Undead Legacy 2.5.47


## 2.5.47 삭제

* zombieSteveCrawler,"크롤러"
* zombieSteveCrawlerFeral,"흉포한 크롤러"
* zombieWight,"혼령"
* zombieMutated,"돌연변이"
* zombieMutatedFeral,"흉포한 돌연변이"
* zombieMutatedRadiated,"방사능 돌연변이"
* zombiePartyGirl,"스트리퍼 좀비"
* zombiePartyGirlFeral,"흉포한 스트리퍼 좀비"
* zombiePartyGirlRadiated,"방사능 스트리퍼 좀비"
* drinkJarGrandpasAwesomeSauce,"할아버지의 끝내주는 소스"
* medicalFirstAidKit,"응급 치료 키트"
* meleeClubIron,"철 곤봉"
* meleeClubIronDesc,"목재 곤봉보다 튼튼하며 추가 데미지를 줍니다. 무릎과 두개골을 박살내는 데 좋은 무기입니다."
* motionsensor,"모션 센서"
* armorSteelSetSchematic,"강철 방어구 도면 세트"
* batterybank,"배터리 저장고"
* bladeTrap,"칼날 함정"
* cementMixer,"시멘트 믹서"
* dartTrap,"다트 함정"
* drinkJarBeer,"맥주"
* drinkJarCoffee,"커피" 
* drinkJarGoldenRodTea,"미역취 차"
* drinkJarGrandpasMoonshine,"할아버지의 밀주 도면"
* drinkJarGrandpasLearningElixir,"할아버지의 학습 영약"
* drinkJarRedTea,"홍차"
* drinkYuccaJuiceSmoothie,"유카즙 스무디"
* drugAntibiotics,"항생제"
* drugHerbalAntibiotics,"허브 항생제"
* electricfencepost,"전기 울타리 구역"
* electrictimerrelay,"전기 타이머 계전기"
* foodBakedPotato,"구운 감자"
* foodBaconAndEggs,"베이컨과 달걀"
* foodBlueberryPie,"블루베리 파이"
* foodBoiledMeat,"삶은 고기"
* foodCanSham,"엉터리 고기 통조림"
* foodChiliDog,"칠리 핫도그"
* foodCornBread,"옥수수빵"
* foodFishTacos,"생선 타코"
* foodGrilledMeat,"구운 고기"
* foodGumboStew,"검보 스튜"
* foodHoboStew,"재활용 스튜"
* foodMeatStew,"고기 스튜"
* foodPumpkinBread,"호박빵"
* foodPumpkinPie,"호박 파이"
* foodShepardsPie,"셰퍼드 파이"
* foodSpaghetti,"스파게티"
* foodSteakAndPotato,"스테이크와 감자 식사"
* foodVegetableStew,"야채 스튜"
* foodTunaFishGravyToast,"참치 그레이비 토스트"
* foodPumpkinCheesecake,"호박 치즈케이크"
* gunBowT3CompoundCrossbow,"컴파운드 석궁"
* medicalFirstAidBandage,"응급 치료용 붕대"
* medicalPlasterCast,"깁스"
* pressureplate,"트리거 발판 1x1"
* resourceMilitaryFiber,"군용 섬유"
* resourceOil,"기름"
* shotgunTurret,"산탄총 자동 터렛"
* speaker,"스피커"
* spotlightPlayer,"스포트라이트"
* switch,"스위치"

---

## 2.5.47 누락

### 일단 제껄로 추가했습니다.

* animalBossGrace,"변종 거대 멧돼지 그레이스"
* animalCoyote,"코요테"
* animalDireWolf,"다이어울프"
* animalMountainLion,"퓨마"
* animalSnake,"뱀"
* animalWolf,"늑대"
* animalZombieBear,"좀비 곰"
* animalZombieVultureRadiated,"방사능 독수리"
* zombieLab,"감염된 과학자"
* zombieLabFeral,"흉포한 과학자"
* zombieLabRadiated,"방사능 과학자"
* zombieJanitor,"청소부 좀비"
* zombieJanitorFeral,"흉포한 청소부 좀비"
* zombieJanitorRadiated,"방사능 청소부 좀비"
* armorMiningHelmetDesc,"뛰어난 방어력을 제공하고 광산이나 건설현장에서 자주 필요로 합니다."
* modArmorDoubleStoragePocketDesc,"[decea3]방어구 개조[-]\n방어구에 장착해서 인벤토리 무게를 확장합니다."
* modArmorStoragePocketDesc,"[decea3]방어구 개조[-]\n방어구에 장착해서 인벤토리 무게를 확장합니다."
* modArmorTripleStoragePocketDesc,"[decea3]방어구 개조[-]\n방어구에 장착해서 인벤토리 무게를 확장합니다."
* modClothingStoragePocketDesc,"[decea3]의복 개조[-]\n의복에 장착해서 인벤토리 무게를 확장합니다."
* modClothingCargoStoragePocketDesc,"[decea3]의복 개조[-]\n의복에 장착해서 인벤토리 무게를 확장합니다."
* modClothingCargoStoragePocketDesc,"[decea3]의복 개조[-]\n의복에 장착해서 인벤토리 무게를 확장합니다."
* ulmMeleeClubTitaniumBlueprint,"티타늄 곤봉 도면"
* ulmMeleeClubTitaniumBlueprintDesc,"새로운 제작 도면을 배울 수 있습니다. 이미 알고 있는 경우 사용 시 XP를 제공합니다."
* perkPistolPeteTakeAimDesc,"스코프 혹은 쇠 조준경 사용 시 9mm 무기가 [decea3]20%[-] 더 넓은 반경을 갖습니다"
* perkPistolPeteTakeAimLongDesc,"스코프 혹은 쇠 조준경 사용 시 9mm 무기가 [decea3]20%[-] 더 넓은 반경을 갖습니다"
* perkPistolPeteSwissKneesDesc,"연속으로 다리를 맞출 경우 적을 불구로 만들 확률이 [decea3]10%[-]만큼 높아집니다"
* perkPistolPeteSwissKneesLongDesc,"연속으로 다리를 맞출 경우 적을 불구로 만들 확률이 [decea3]10%[-]만큼 높아집니다"
* perkPistolPeteSteadyHandDesc,"9mm 무기를 속사할 때 정확도가 높아집니다"
* perkPistolPeteSteadyHandLongDesc,"9mm 무기를 속사할 때 정확도가 높아집니다"
* perkPistolPeteMaintenanceDesc,"9mm 무기의 내구도가 [decea3]20%[-] 느리게 저하됩니다"
* perkPistolPeteMaintenanceLongDesc,"9mm 무기의 내구도가 [decea3]20%[-] 느리게 저하됩니다"
* perkPistolPeteHPAmmoDesc,"9mm 탄약 (HP)를 제작할 수 있습니다"
* perkPistolPeteHPAmmoLongDesc,"9mm 탄약 (HP)를 제작할 수 있습니다"
* perkPistolPeteAPAmmoDesc,"9mm 탄약 (AP)를 제작할 수 있습니다"
* perkPistolPeteAPAmmoLongDesc,"9mm 탄약 (AP)를 제작할 수 있습니다"
* perkPistolPeteDamageDesc,"9mm 무기가 [decea3]10%[-] 더 많은 데미지를 가합니다"
* perkPistolPeteDamageLongDesc,"9mm 무기가 [decea3]10%[-] 더 많은 데미지를 가합니다"
* perkPistolPeteCompleteDesc,"9mm 무기가 아주 가까이 있는 적의 방어구를 [decea3]20%[-]만큼 무시합니다"
* perkPistolPeteCompleteLongDesc,"9mm 무기가 아주 가까이 있는 적의 방어구를 [decea3]20%[-]만큼 무시합니다"
* ulmContainerSmallSafeVariantHelper,"작은 금고"
* ulmContainerSmallSafeVariantHelperDesc,"조그마합니다, 하지만 귀중품을 안전하게 보관합니다.\n[808080]여러가지 형태 포함.[-]"
* cellarDoorDoubleWoodPicked,"목재 창고 문\n[808080](잠금 해제됨)[-]"
* cellarDoorDoubleIronPicked,"철제 창고 문\n[808080](잠금 해제됨)[-]"
* cellarDoorDoubleSteelPicked,"강철 창고 문\n[808080](잠금 해제됨)[-]"
* shuttersWood01Picked,"목재 셔터\n[808080](잠금 해제됨)[-]"
* shuttersWood02Picked,"목재 셔터\n[808080](잠금 해제됨)[-]"
* shuttersIron01Picked,"철제 셔터\n[808080](잠금 해제됨)[-]"
* shuttersIron02Picked,"철제 셔터\n[808080](잠금 해제됨)[-]"
* shuttersSteel01Picked,"강철 셔터\n[808080](잠금 해제됨)[-]"
* shuttersSteel02Picked,"강철 셔터\n[808080](잠금 해제됨)[-]"
* rollUpDoor3x3WhitePicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor3x3BrownPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor3x3RedPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor3x3OrangePicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor3x3YellowPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor3x3GreenPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor3x3BluePicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor3x3PurplePicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor3x3GreyPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor3x3BlackPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor3x3PinkPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor5x4WhitePicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor5x4BrownPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor5x4RedPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor5x4OrangePicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor5x4YellowPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor5x4GreenPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor5x4BluePicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor5x4PurplePicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor5x4GreyPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor5x4BlackPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor5x4PinkPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor7x4WhitePicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor7x4BrownPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor7x4RedPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor7x4OrangePicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor7x4YellowPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor7x4GreenPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor7x4BluePicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor7x4PurplePicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor7x4GreyPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor7x4BlackPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* rollUpDoor7x4PinkPicked,"롤업 문\n[808080](잠금 해제됨)[-]"
* ulmDoorWoodDoubleVariantHelper
    * "Wooden Double Doors"
    * "나무 쌍여닫이문"
* ulmDoorMetalDoubleVariantHelper
    * "Metal Double Doors"
    * "철 쌍여닫이문
* awningShapes:VariantHelper,"차양 형태"
* materialmatIron,"골진 철"
* * sectionalPlaidChair
    * "Old Armchair"
    * "낡은 안락의자"

---

## 제가 변경한 것

1. KEY
    * JellyMan
    * Zuxico

1. infectionDesc
    * "당신은 감염되었습니다. "
    * "당신은 감염되었습니다. 항생제, 꿀 또는 허브 항생제를 사용하여 감염을 치료하십시오. 치료하지 않으면 점점 약해져서 결국 죽게 됩니다."
1. statDegradationPerUse
    * "성능 저하"
    * "내구도 저하"
1. xuiFeelsLike
    * "같은 느낌"
    * "체온"
1. 한/영 어순 차이
    * lootVehicleEmpty
          * "[73E9B2][{0}][-] 열기 {1}{2}\n[808080](비어 있음)[-]"
          * "[73E9B2][{0}][-] {1} 열기{2}\n[808080](비어 있음)[-]"
    * lootVehicleNew
          * "[73E9B2][{0}][-] 조사 {1}{2}\n[73E9B2](손대지 않음)[-]"
          * "[73E9B2][{0}][-] {1} 조사{2}\n[73E9B2](손대지 않음)[-]"
    * lootVehicleTouched
          * "[73E9B2][{0}][-] 열기 {1}{2}"
          * "[73E9B2][{0}][-] {1} 열기{2}"
    * lootVehicleSecureJammed
          * "[73E9B2][{0}][-] 사용 {1}{2}\n[808080](걸림)[-]"
          * "[73E9B2][{0}][-] {1} 열기{2}\n[808080](걸림)[-]"
    * lootVehicleSecureLocked
          * "[73E9B2][{0}][-] 사용 {1}{2}\n[808080](잠김)[-]"
          * "[73E9B2][{0}][-] {1} 열기{2}\n[808080](잠김)[-]"
    * lootVehicleSecureUnlocked
          * "[73E9B2][{0}][-] 사용 {1}{2}\n[808080](잠금 해제됨)[-]"
          * "[73E9B2][{0}][-] {1} 열기{2}\n[808080](잠금 해제됨)[-]"
1. typeCannedFood
    * "캔 음식"
    * "통조림"
1. UI 벗어나는 글자
    * uiMapCursor
          * "마우스 커서 좌표"
          * "커서 좌표"
    * uiMapPlayer
          * "플레이어 현재 위치"
          * "현재 위치"
1. 정비소 UI
    * uiUpgrade
          * "품질 향상"
          * "강화"
    * uiUpgradeChance
          * "품질 향상 확률"
          * "강화 확률"
    * uiUpgradeCost
          * "품질 향상 비용"
          * "강화 비용"
    * uiUpgradeFail
          * "[FF1919]품질 강화 실패[-]"
          * "[FF1919]강화 실패[-]"
    * uiUpgradeSuccess
          * "[73E9B2]품질 강화 성공![-]"
          * "[73E9B2]강화 성공[-]"
    * uiUpgradeRemoveMods
          * "[decea3]개조 부품이 장착된 상태로 강화할 수 없습니다.[-]"
          * "[decea3]개조 부품 장착됨[-]"
    * uiUpgradeRequiresRepairs
          * "[decea3]아이템을 먼저 수리해야 합니다.[-]"
          * "[decea3]수리 필요[-]"
1. Baton 관련, 별도의 Electric Perk이 있으므로 '곤봉'과 햇갈리지 않게
    * 모든 Baton 무기/스킬/스킬북 이름을 진압봉으로 변경, 다른 이름으로 변경하고자하면 진압봉으로 찾아 바꾸기.
    * typeBatons
          * "단봉"
          * "진압봉"
    * meleeWpnBatonT2StunBaton
          * "전기 호신봉"
          * "전기 진압봉"
    * meleeWpnBatonT0PipeBaton
          * "파이프 곤봉"
          * "파이프 진압봉"
    * meleeWpnBatonT0PipeBatonDesc
          * "폐부품과 파이프로 만든 곤봉입니다. 가볍긴 한데, 그래도 제대로 된 한 방을 날릴 수 있습니다."
          * "고물 부품과 파이프로 만든 진압봉입니다. 무게는 가볍지만 괜찮게 두드려팰 수 있습니다."
    * ulmMeleeBatonPoliceBaton
          * "경찰봉"
          * "경찰 진압봉"
    * ulmMeleeBatonPoliceBatonDesc
          * "고무를 입힌 플라스틱으로 겉을 감싼 철심이 박혀 있는 표준 경찰봉입니다."
          * "단단한 철심에 고무로 감싼 경찰 표준으로 만든 경찰 진압봉"
    * ulmMeleeBatonPoliceBatonWithBlade
          * "개조된 경찰봉"
          * "사제 경찰 진압봉"
    * ulmMeleeBatonPoliceBatonWithBladeDesc
          * "누군가가 이 경찰봉을 개조해서 진압력이 더 좋아졌습니다."
          * "사제로 개조해 진압성능이 추가된 경찰 진압봉"
    * perkElectrocutioner,"단봉"
    * perkElectrocutioner1,"단봉이 [decea3]10%[-]의 추가 데미지를 주며 적을 [decea3]20%[-] 더 오래 기절시킴."
    * perkElectrocutioner2,"단봉이 [decea3]20%[-]의 추가 데미지를 주며 적을 [decea3]40%[-] 더 오래 기절시킴."
    * perkElectrocutioner3,"단봉이 [decea3]30%[-]의 추가 데미지를 주며 적을 [decea3]60%[-] 더 오래 기절시킴."
    * perkElectrocutioner4,"단봉이 [decea3]40%[-]의 추가 데미지를 주며 적을 [decea3]80%[-] 더 오래 기절시킴."
    * perkElectrocutioner5,"단봉이 [decea3]50%[-]의 추가 데미지를 주며 적을 [decea3]100%[-] 더 오래 기절시킴."
    * perkElectrocutioner,"진압봉"
    * perkElectrocutioner1,"진압봉이 [decea3]10%[-]의 추가 데미지를 주며 적을 [decea3]20%[-] 더 오래 기절시킴."
    * perkElectrocutioner2,"진압봉이 [decea3]20%[-]의 추가 데미지를 주며 적을 [decea3]40%[-] 더 오래 기절시킴."
    * perkElectrocutioner3,"진압봉이 [decea3]30%[-]의 추가 데미지를 주며 적을 [decea3]60%[-] 더 오래 기절시킴."
    * perkElectrocutioner4,"진압봉이 [decea3]40%[-]의 추가 데미지를 주며 적을 [decea3]80%[-] 더 오래 기절시킴."
    * perkElectrocutioner5,"진압봉이 [decea3]50%[-]의 추가 데미지를 주며 적을 [decea3]100%[-] 더 오래 기절시킴."
    * actionPerkShockers
          * "단봉"
          * "진압봉"
    * actionPerkShockersLevelUp
          * "[decea3]단봉[-] 액션 스킬이 향상되었습니다!"
          * "[decea3]진압봉[-] 액션 스킬이 향상되었습니다!"
    * perkFlurryOfBlows1,"곤봉, 너클, 단검, 도검과 단봉의 공격 속도가 [decea3]10%[-] 증가함. 모든 근접 무기로 적을 처치 시 [decea3]5[-]의 스태미너를 회복함."
    * perkFlurryOfBlows2,"곤봉, 너클, 단검, 도검과 단봉의 공격 속도가 [decea3]17%[-] 증가함. 모든 근접 무기로 적을 처치 시 [decea3]10[-]의 스태미너를 회복함."
    * perkFlurryOfBlows3,"곤봉, 너클, 단검, 도검과 단봉의 공격 속도가 [decea3]25%[-] 증가함. 모든 근접 무기로 적을 처치 시 [decea3]20[-]의 스태미너를 회복함."
    * perkFlurryOfBlows1,"곤봉, 너클, 단검, 도검과 진압봉의 공격 속도가 [decea3]10%[-] 증가함. 모든 근접 무기로 적을 처치 시 [decea3]5[-]의 스태미너를 회복함."
    * perkFlurryOfBlows2,"곤봉, 너클, 단검, 도검과 진압봉의 공격 속도가 [decea3]17%[-] 증가함. 모든 근접 무기로 적을 처치 시 [decea3]10[-]의 스태미너를 회복함."
    * perkFlurryOfBlows3,"곤봉, 너클, 단검, 도검과 진압봉의 공격 속도가 [decea3]25%[-] 증가함. 모든 근접 무기로 적을 처치 시 [decea3]20[-]의 스태미너를 회복함."
    * attIntellectDesc,"[decea3]지능[-] 스킬을 빨리 배울 수 있게 해주고, 다음 무기에 추가 헤드샷 데미지와 사지 절단 확률을 부여합니다.\n[decea3]SMG[-], [decea3]폭발물[-], [decea3]휴대용 포탑[-], [decea3]전기 호신봉[-]"
1. groupVariantHelpers
    * "Variant Helpers"
    * "변형 도우미"
1. gold
    * "Gold"
    * "금"
1. typePoweredCutting
    * "전동 절단 도구"
    * "전동 벌목 도구"
1. 클로 해머 -> 장도리
    * meleeToolRepairT1ClawHammer,"클로 해머"
    * meleeToolRepairT1ClawHammerBlueprint,"클로 해머 도면"
1. 임팩트 드라이버, 실제 플레이어들이 다른 '전동' 도구와 햇갈려함.
    * 전동 드릴 -> 임팩트 드라이버
          * meleeToolSalvageT3ImpactDriver,"전동 드릴"
          * meleeToolSalvageT3ImpactDriverSchematic, "전동 드릴 도면"        
          * perkSalvageOperations1,"렌치, 라쳇, 전동 드릴같은 분해 도구가 [decea3]10%[-] 추가 데미지를 주며 분해 시 자원을 [decea3]10%[-] 더 많이 획득함."
          * perkSalvageOperations2,"렌치, 라쳇, 전동 드릴같은 분해 도구가 [decea3]20%[-] 추가 데미지를 주며 분해 시 자원을 [decea3]20%[-] 더 많이 획득함."
          * perkSalvageOperations3,"렌치, 라쳇, 전동 드릴같은 분해 도구가 [decea3]30%[-] 추가 데미지를 주며 분해 시 자원을 [decea3]30%[-] 더 많이 획득함."
          * perkSalvageOperations4,"렌치, 라쳇, 전동 드릴같은 분해 도구가 [decea3]40%[-] 추가 데미지를 주며 분해 시 자원을 [decea3]40%[-] 더 많이 획득함."
          * perkSalvageOperations5,"렌치, 라쳇, 전동 드릴같은 분해 도구가 [decea3]50%[-] 추가 데미지를 주며 분해 시 자원을 [decea3]50%[-] 더 많이 획득함."
          * abandonedVehicleRepairTip,"가끔 수리 가능한 차량을 발견할 수도 있습니다. 차량의 종류에 따라 수리에 필요한 키트가 다릅니다.\n자전거 - 자전거 수리 키트,\n미니바이크 - 미니바이크 수리 키트,\n오토바이 - 오토바이 수리 키트,\n자동차 - 자동차 수리 키트,\n두돈반 트럭 - 트럭 수리 키트.\n\n[decea3]수리 가능[-]한 차량을 수리하려면 [decea3]렌치[-], [decea3]라쳇[-] 또는 [decea3]전동 드릴[-]을 손에 들고 인벤토리에 차량의 종류와 매칭되는 [decea3]수리 키트[-]를 가지고 있어야 합니다. 그리고 [decea3]수리 가능[-]한 차량 앞에 서서 상호 작용 키(기본: [decea3]E[-])를 누른 채 나오는 다이얼 메뉴에서 수리 항목을 선택하여 수리할 수 있습니다."
1. 락픽->자물쇠 따개, 실핀->머리핀
    * blockcommand_pick1
          * "자물쇠 따기\n[808080](락픽)[-]"
          * "자물쇠 따기\n[808080](자물쇠 따개)[-]"
    * blockcommand_pick2
          * "자물쇠 따기\n[808080](실핀)[-]"
          * "자물쇠 따기\n[808080](머리핀)[-]"
    * uiLockAutoPick
          * "자동 해제"
          * "자동 따기"
    * uiLockAutoPickChance
          * "자동 해제 확률: [decea3]{0}%[-]"
          * "자동 따기 확률: [decea3]{0}%[-]"
    * drugJailBreakersDesc
          * "잠시 동안 자물쇠 따기 스킬과 도구(락픽, 실핀)의 내구도를 [decea3]200%[-] 향상시킵니다."
          * "일시적으로 자물쇠 따는 기술이 증가하고 자물쇠 따기 도구의 내구도를 [decea3]200%[-] 향상시킵니다."
    * resourceLockPick
          * "락픽"
          * "자물쇠 따개"
    * resourceLockPickDesc
          * "인벤토리에 락픽을 가지고 있으면 E키를 누른 상태로 자물쇠 따기를 시도할 수 있습니다.\n도구 벨트 위에 장착되어 있지 않아도 됩니다."
          * "인벤토리에 자물쇠 따개가 있으면 'E'키를 꾹 누르고 자물쇠 따기 행동으로 잠긴 것을 딸 수 있습니다.\n자물쇠 따개를 도구 벨트에 장착할 필요는 없습니다."
    * resourceLockPickBlueprint
          * "락픽 도면"
          * "자물쇠 따개 도면"
    * ulmResourceBobbyPin
          * "실핀"
          * "머리핀"
    * ulmResourceBobbyPinDesc
          * "일반적인 금속으로 만든 머리핀입니다. 머리카락을 고정하는 데 쓰거나 급한 대로 락픽처럼 쓸 수 있습니다."
          * "쇠로 만든 것 같은 재질의 머리핀입니다. 머리카락을 고정하는데 쓰거나 급한 대로 자물솨 따개처럼 쓸 수 있습니다.
    * ulmResourceBobbyPinBlueprint
          * "실핀 도면"
          * "머리핀 도면"
    * 자물쇠 따기 레벨 -> 자물쇠 따는 기술 (drugJailBreakersDesc)
          * perkLockPicking1,"자물쇠 따기 레벨 [decea3]+25[-] 증가.\n락픽과 실핀이 [decea3]20%[-]의 추가 내구도를 가짐."
          * perkLockPicking2,"자물쇠 따기 레벨 [decea3]+50[-] 증가.\n락픽과 실핀이 [decea3]40%[-]의 추가 내구도를 가짐."
          * perkLockPicking3,"자물쇠 따기 레벨 [decea3]+75[-] 증가.\n락픽과 실핀이 [decea3]60%[-]의 추가 내구도를 가짐."
          * perkLockPicking4,"자물쇠 따기 레벨 [decea3]+100[-] 증가.\n락픽과 실핀이 [decea3]80%[-]의 추가 내구도를 가짐."
          * perkLockPicking1,"자물쇠 따는 기술 [decea3]+25[-] 증가.\n머리핀이 [decea3]20%[-] 추가 내구도를 가짐."
          * perkLockPicking2,"자물쇠 따는 기술 [decea3]+50[-] 증가.\n머리핀이 [decea3]40%[-] 추가 내구도를 가짐."
          * perkLockPicking3,"자물쇠 따는 기술 [decea3]+75[-] 증가.\n머리핀이 [decea3]60%[-] 추가 내구도를 가짐."
          * perkLockPicking4,"자물쇠 따는 기술 [decea3]+100[-] 증가.\n머리핀이 [decea3]80%[-] 추가 내구도를 가짐."
          * actionPerkLockPicking1,"자물쇠 따기 레벨 [decea3]+20[-] 증가.\n락픽과 실핀이 [decea3]20%[-]의 추가 내구도를 가짐."
          * actionPerkLockPicking2,"자물쇠 따기 레벨 [decea3]+40[-] 증가.\n락픽과 실핀이 [decea3]40%[-]의 추가 내구도를 가짐."
          * actionPerkLockPicking3,"자물쇠 따기 레벨 [decea3]+60[-] 증가.\n락픽과 실핀이 [decea3]60%[-]의 추가 내구도를 가짐."
          * actionPerkLockPicking4,"자물쇠 따기 레벨 [decea3]+80[-] 증가.\n락픽과 실핀이 [decea3]80%[-]의 추가 내구도를 가짐."
          * actionPerkLockPicking5,"자물쇠 따기 레벨 [decea3]+100[-] 증가.\n락픽과 실핀이 [decea3]100%[-]의 추가 내구도를 가짐."
          * actionPerkLockPicking1,"자물쇠 따는 기술 [decea3]+20[-] 증가.\n자물쇠 따개와 머리핀의 내구도 [decea3]20%[-] 향상"
          * actionPerkLockPicking2,"자물쇠 따는 기술 [decea3]+40[-] 증가.\n자물쇠 따개와 머리핀의 내구도 [decea3]40%[-] 향상"
          * actionPerkLockPicking3,"자물쇠 따는 기술 [decea3]+60[-] 증가.\n자물쇠 따개와 머리핀의 내구도 [decea3]60%[-] 향상"
          * actionPerkLockPicking4,"자물쇠 따는 기술 [decea3]+80[-] 증가.\n자물쇠 따개와 머리핀의 내구도 [decea3]80%[-] 향상"
          * actionPerkLockPicking5,"자물쇠 따는 기술 [decea3]+100[-] 증가.\n자물쇠 따개와 머리핀의 내구도 [decea3]100%[-] 향상"
    * perkGreatHeistCompleteDesc
          * "자물쇠 따기 레벨이 [decea3]+25[-] 증가하며\n[decea3]실핀[-] 제작 방법을 해금하고 [decea3]실핀[-]과 [decea3]락픽[-] 내구도가 [decea3]25%[-] 증가합니다."
          * "[decea3]자물쇠 따는 기술 +25[-] 증가.\n[decea3]머리핀[-] 제작 방법을 해금하고 [decea3]머리핀[-]과 [decea3]자물쇠 따개[-]의 내구도가 [decea3]25%[-] 증가합니다."
    * perkGreatHeistCompleteLongDesc
          * "자물쇠 따는 기술이 [decea3]+25[-] 증가하며\n[decea3]실핀[-] 제작 방법을 해금하고 [decea3]실핀[-]과 [decea3]락픽[-] 내구도가 [decea3]25%[-] 증가합니다."
          * "[decea3]자물쇠 따는 기술 +25[-] 증가.\n[decea3]머리핀[-] 제작 방법을 해금하고 [decea3]머리핀[-]과 [decea3]자물쇠 따개[-]의 내구도가 [decea3]25%[-] 증가합니다."
1. 제작품이 바닐라 번역인 경우 도면을 바닐라 번역에 맞게 변경
    * tripwirepostBlueprint
          * "와이어 함정 도면"
          * "와이어 함정 구역 도면"
1. Powered, 바닐라 번역은 (전원 연결됨), (전력 필요)로 변경하고 제작품 key 없는 것은 최하단에 추가
    * garageDoorMetal_v1PoweredBlueprint,"강철 차고 문 3x2 (전력 필요) 도면"
    * vaultDoor03_PoweredBlueprint,"금고 문 03 (전력 필요) 도면"
    * vaultHatch_v3_PoweredBlueprint,"금고 해치 v3 (전력 필요) 도면"
    * garageDoorIndustrial_PoweredBlueprint,"금속 차고 문 5x3 (전력 필요) 도면"
    * metalReinforcedWoodDrawBridgePoweredBlueprint,"강화형 도개교 (전력 필요) 도면"
    * ulmDoorSciFi01PoweredBlueprint,"철제 보안 출입문 (전력 필요) 도면"
    * ulmDoorSciFi02PoweredBlueprint,"철제 보안 유리 출입문 (전력 필요) 도면"
    * ulmDoorSciFi03PoweredBlueprint,"철제 보안 게이트 (전력 필요) 도면"
    * ulmDoorSciFi04PoweredBlueprint,"철제 보안 방폭문 (전력 필요) 도면"
    * ulmDoorSciFi01Powered,"철제 보안 출입문 (전력 필요)"
    * ulmDoorSciFi02Powered,"철제 보안 유리 출입문 (전력 필요)"
    * ulmDoorSciFi03Powered,"철제 보안 게이트 (전력 필요)"
    * ulmDoorSciFi04Powered,"철제 보안 방폭문 (전력 필요)"
    * 최하단에 추가
          * garageDoorMetal_v1Powered,""강철 차고 문 3x2 (전력 필요)"
          * vaultDoor03_Powered,"금고 문 03 (전력 필요)"
          * vaultHatch_v3_Powered,금고 해치 v3 (전력 필요)"
          * garageDoorIndustrial_Powered,금속 차고 문 5x3 (전력 필요)
          * metalReinforcedWoodDrawBridgePowered,강화형 도개교 (전력 필요)
1. 한 번에 여러개도 다운된다고 합니다.
    * actionSkillDeathPenalty
          * "기억 상실을 겪어 [decea3]액션 스킬[-] 중 하나의 레벨이 다운되었습니다."
          * "기억 상실을 겪어 일부 [decea3]액션 스킬[-]의 레벨이 1 다운되었습니다."
1. 소드오프 샷건 개조 -> 총신 절단 샷건 개조(바닐라 번역)
    * modShotgunSawedOffBarrel,"소드오프 샷건 개조"
    * modShotgunSawedOffBarrelSchematic,"소드오프 샷건 개조"
1. 물 펌프
    * ulmBlockWaterpumpDesc
          * "방사능으로 덜 오염된 토양 깊숙한 곳에서 탁한 물(게임 내 1 시간마다 1 수치)을 천천히 다시 퍼 올립니다."
          * "토양 깊숙한 곳에서 방사능에 덜 오염된 탁한 물(게임시간 1 시간마다 1 개)을 천천히 퍼 올립니다."
1. 원시적인 우물
    * ulmCollectorWellWoodDesc
          * "방사능으로 덜 오염된 토양 깊숙한 곳에서 탁한 물(게임 내 2 시간마다 1 수치)을 천천히 다시 퍼 올립니다."
          * "토양 깊숙한 곳에서 방사능에 덜 오염된 탁한 물(게임시간 2 시간마다 1 개)을 천천히 퍼 올립니다."
1. 도로 안전 바리케이드
    * ulmLightRoadBarricadePlayerDesc
          * "조명을 켜고 유지하기에 충분한 전력을 생성하기 위해 배터리가 내장되어 있습니다."
          * "배터리가 내장되어 있어 충분한 전력을 생산해 조명을 계속 켜둘 수 있습니다."
1. 군용 트럭 -> 두돈반 트럭
    * ulmVehicleMilitaryTruck,"두돈반 트럭"
    * ulmVehicleMilitaryTruckDesertTarp1,"두돈반 트럭"
    * ulmVehicleMilitaryTruckDesertTarp2,"두돈반 트럭"
    * ulmVehicleMilitaryTruckDesertTarp3,"두돈반 트럭"
    * ulmVehicleMilitaryTruckDesertRails,"두돈반 트럭"
    * ulmVehicleMilitaryTruckCamoTarp1,"두돈반 트럭"
    * ulmVehicleMilitaryTruckCamoTarp2,"두돈반 트럭"
    * ulmVehicleMilitaryTruckCamoTarp3,"두돈반 트럭"
    * ulmVehicleMilitaryTruckCamoRails,"두돈반 트럭"

---

## 용어 정리 기록용

1. uiAmmoAndExplosives
    * "탄약/폭약"
    * "탄약/폭발물"
1. 갑옷 -> 방어구
    * uiArmor
          * "갑옷"
          * "방어구"
    * uiClothingAndArmor
          * "의복/갑옷"
          * "의복/방어구"
    * uiClothingArmorMods
          * "의복/갑옷 개조"
          * "의복/방어구 개조"
    * statArmorRating
          * "갑옷 등급"
          * "방어구 등급"
    * typeArmor
          * "갑옷"
          * "방어구"
    * groupClothingAndArmor
          * "의복/갑옷"
          * "의복/방어구"
    * modArmorPlatingBasic
          * "갑옷 플레이트 추가 개조"
          * "방어구 플레이트 추가 개조"
    * modArmorPlatingBasicSchematic
          * "갑옷 플레이트 추가 개조 도면"
          * "방어구 플레이트 추가 개조 도면"
    * modArmorPlatingReinforced
          * "고급 갑옷 플레이트 추가 개조"
          * "고급 방어구 플레이트 추가 개조"
    * modArmorPlatingReinforcedSchematic
          * "고급 갑옷 플레이트 추가 개조 도면"
          * "고급 방어구 플레이트 추가 개조 도면"
1. 보관함/저장소
    * uiContainer
          * "저장소"
          * "보관함"
    * groupLoot
          * "저장소"
          * "보관함"
    * groupStorage
          * "보관함"
          * "저장소"
    * typeLoot
          * "저장소"
          * "보관함"
1. ui KEY /로 통일
    * uiExplosivesAndMines
          * "폭발물과 지뢰"
          * "폭발물/지뢰"
    * groupWeaponsTools,"무기/도구"
1. 자동차 용어 통일
    * typeAutomotive
          * "차량"
          * "자동차"
    * groupAutomotive,"자동차"
