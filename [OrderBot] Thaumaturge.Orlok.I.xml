<?xml version="1.0" encoding="UTF-8"?>
<!--
Thaumaturge Level I Log
Author: Orlok
Version 1.0
-->

<Profile>
  <Name>ThaumaturgeHunter</Name>
  <KillRadius>50</KillRadius>
  <!-->
The area the profile will scout:
<-->

  <!-->Ladybug<-->
  <GrindAreas>
    <GrindArea name="Thaumaturge_1_0">
      <Hotspots>
        <HotSpot Radius="90" XYZ="334.2293, 69.80108, 169.9605" name="Thaumaturge_1_0" />
      </Hotspots>
      <TargetMobs>
        <TargetMob Id="49" />
      </TargetMobs>
      <MinLevel>1</MinLevel>
      <MaxLevel>50</MaxLevel>
    </GrindArea>

    <!-->HugeHornet<-->
      <GrindArea name="Thaumaturge_1_1">
        <Hotspots>
          <HotSpot Radius="90" XYZ="38.3153, 13.00743, 410.9605" name="Thaumaturge_1_1" />
        </Hotspots>
        <TargetMobs>
          <TargetMob Id="632" />
        </TargetMobs>
        <MinLevel>1</MinLevel>
        <MaxLevel>50</MaxLevel>
      </GrindArea>

    <!-->Cactuar<-->
    <GrindArea name="Thaumaturge_1_2">
      <Hotspots>
        <HotSpot Radius="90" XYZ="333.8014, 69.68659, 175.8505" name="Thaumaturge_1_2" />
      </Hotspots>
      <TargetMobs>
        <TargetMob Id="287" />
      </TargetMobs>
      <MinLevel>1</MinLevel>
      <MaxLevel>50</MaxLevel>
    </GrindArea>


    <!-->SnappingShrew<-->
    <GrindArea name="Thaumaturge_1_3">
      <Hotspots>
        <HotSpot Radius="90" XYZ="333.8014, 69.68659, 175.8505" name="Thaumaturge_1_3" />
      </Hotspots>
      <TargetMobs>
        <TargetMob Id="318" />
      </TargetMobs>
      <MinLevel>1</MinLevel>
      <MaxLevel>50</MaxLevel>
    </GrindArea>

    <!-->SyrphidCloud<-->
    <GrindArea name="Thaumaturge_1_4">
      <Hotspots>
        <HotSpot Radius="90" XYZ="4.195383, -0.3896301, -224.4393" name="Thaumaturge_1_4" />
      </Hotspots>
      <TargetMobs>
        <TargetMob Id="201" />
      </TargetMobs>
      <MinLevel>1</MinLevel>
      <MaxLevel>50</MaxLevel>
    </GrindArea>

    <!-->YarzonFeeder<-->
    <GrindArea name="Thaumaturge_1_5">
      <Hotspots>
        <HotSpot Radius="90" XYZ="126.7918, 57.94094, 277.3894" name="Thaumaturge_1_5" />
      </Hotspots>
      <TargetMobs>
        <TargetMob Id="284" />
      </TargetMobs>
      <MinLevel>1</MinLevel>
      <MaxLevel>50</MaxLevel>
    </GrindArea>

    <!-->RustyCoblyn<-->
    <GrindArea name="Thaumaturge_1_6">
      <Hotspots>
        <HotSpot Radius="90" XYZ="6.279166, 55.06238, 310.8722" name="Thaumaturge_1_6" />
      </Hotspots>
      <TargetMobs>
        <TargetMob Id="276" />
      </TargetMobs>
      <MinLevel>1</MinLevel>
      <MaxLevel>50</MaxLevel>
    </GrindArea>

    <!-->SprigganGraverobber<-->
    <GrindArea name="Thaumaturge_1_7">
      <Hotspots>
        <HotSpot Radius="90" XYZ="-193.921, -29.78915, 90.61917" name="Thaumaturge_1_7" />
      </Hotspots>
      <TargetMobs>
        <TargetMob Id="317" />
      </TargetMobs>
      <MinLevel>1</MinLevel>
      <MaxLevel>50</MaxLevel>
    </GrindArea>


    <!-->QiqirnShellsweeper<-->
    <GrindArea name="Thaumaturge_1_8">
      <Hotspots>
        <HotSpot Radius="90" XYZ="-233.163, 16.62488, -58.03273" name="Thaumaturge_1_8" />
      </Hotspots>
      <TargetMobs>
        <TargetMob Id="266" />
      </TargetMobs>
      <MinLevel>1</MinLevel>
      <MaxLevel>50</MaxLevel>
    </GrindArea>


    <!-->SunBat<-->
    <GrindArea name="Thaumaturge_1_9">
      <Hotspots>
        <HotSpot Radius="90" XYZ="159.4196, -0.7509269, -153.0909" name="Thaumaturge_1_9" />
      </Hotspots>
      <TargetMobs>
        <TargetMob Id="279" />
      </TargetMobs>
      <MinLevel>1</MinLevel>
      <MaxLevel>50</MaxLevel>
    </GrindArea>
    </GrindAreas>
  <Order>
    <If Condition="not HuntRankCompleted(ClassJobType.Thaumaturge,1)">
      <!-->Ladybug<-->
      <If Condition="not HuntEntryCompleted(ClassJobType.Thaumaturge,0)">
        <If Condition="not IsOnMap(140)">
          <TeleportTo Name="Horizon" AetheryteId="17" />
        </If>
        <Grind grindRef="Thaumaturge_1_0" PostCombatDelay="5" while="not HuntEntryCompleted(ClassJobType.Thaumaturge,0)" />
      </If>
      <!-->HugeHornet<-->
      <If Condition="not HuntEntryCompleted(ClassJobType.Thaumaturge,1)">
        <If Condition="not IsOnMap(141)">
          <TeleportTo Name="Black Brush Station" AetheryteId="53" />
        </If>
        <Grind grindRef="Thaumaturge_1_1" PostCombatDelay="5" while="not HuntEntryCompleted(ClassJobType.Thaumaturge,1)" />
      </If>
      <!-->Cactuar<-->
      <If Condition="not HuntEntryCompleted(ClassJobType.Thaumaturge,2)">
        <If Condition="not IsOnMap(140)">
          <TeleportTo Name="Horizon" AetheryteId="17" />
        </If>
        <Grind grindRef="Thaumaturge_1_2" PostCombatDelay="5" while="not HuntEntryCompleted(ClassJobType.Thaumaturge,2)" />
      </If>
      <!-->SnappingShrew<-->
      <If Condition="not HuntEntryCompleted(ClassJobType.Thaumaturge,3)">
        <If Condition="not IsOnMap(141)">
          <TeleportTo Name="Black Brush Station" AetheryteId="53" />
        </If>
        <Grind grindRef="Thaumaturge_1_3" PostCombatDelay="5" while="not HuntEntryCompleted(ClassJobType.Thaumaturge,3)" />
      </If>
      <!-->SyrphidCloud<-->
      <If Condition="not HuntEntryCompleted(ClassJobType.Thaumaturge,4)">
        <If Condition="not IsOnMap(141)">
          <TeleportTo Name="Black Brush Station" AetheryteId="53" />
        </If>
        <Grind grindRef="Thaumaturge_1_4" PostCombatDelay="5" while="not HuntEntryCompleted(ClassJobType.Thaumaturge,4)" />
      </If>
      <!-->YarzonFeeder<-->
      <If Condition="not HuntEntryCompleted(ClassJobType.Thaumaturge,5)">
        <If Condition="not IsOnMap(140)">
          <TeleportTo Name="Horizon" AetheryteId="17" />
        </If>
        <Grind grindRef="Thaumaturge_1_5" PostCombatDelay="5" while="not HuntEntryCompleted(ClassJobType.Thaumaturge,5)" />
      </If>
      <!-->RustyCoblyn<-->
      <If Condition="not HuntEntryCompleted(ClassJobType.Thaumaturge,6)">
        <If Condition="not IsOnMap(140)">
          <TeleportTo Name="Horizon" AetheryteId="17" />
        </If>
        <Grind grindRef="Thaumaturge_1_6" PostCombatDelay="5" while="not HuntEntryCompleted(ClassJobType.Thaumaturge,6)" />
      </If>
      <!-->SprigganGraverobber<-->
      <If Condition="not HuntEntryCompleted(ClassJobType.Thaumaturge,7)">
        <If Condition="not IsOnMap(141)">
          <TeleportTo Name="Black Brush Station" AetheryteId="53" />
        </If>
        <Grind grindRef="Thaumaturge_1_7" PostCombatDelay="5" while="not HuntEntryCompleted(ClassJobType.Thaumaturge,7)" />
      </If>
      <!-->QiqirnShellsweeper<-->
      <If Condition="not HuntEntryCompleted(ClassJobType.Thaumaturge,8)">
        <If Condition="not IsOnMap(141)">
          <TeleportTo Name="Black Brush Station" AetheryteId="53" />
        </If>
        <Grind grindRef="Thaumaturge_1_8" PostCombatDelay="5" while="not HuntEntryCompleted(ClassJobType.Thaumaturge,8)" />
      </If>
      <!-->SunBat<-->
      <If Condition="not HuntEntryCompleted(ClassJobType.Thaumaturge,9)">
        <If Condition="not IsOnMap(141)">
          <TeleportTo Name="Black Brush Station" AetheryteId="53" />
        </If>
        <Grind grindRef="Thaumaturge_1_9" PostCombatDelay="5" while="not HuntEntryCompleted(ClassJobType.Thaumaturge,9)" />
      </If>
      
    </If>
  </Order>
  <!-->
This profile has been completed! Feel free to donate @ YoelR@Verizon.net for more profiles! 
	<-->
</Profile>
