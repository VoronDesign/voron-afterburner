**Voron Stealthburner Beta**
---
___
- [Introduction](#introduction)
- [Filename Nomenclature](#filename-nomenclature)
- [CHANGE LOG: *(Detailing significant changes)*](#change-log-detailing-significant-changes)
  - [2022-02-14 - Minor adjustments to ADXL mounts #87](#2022-02-14---minor-adjustments-to-adxl-mounts-87)
  - [2022-02-14 - Stealthburner ADXL Support and toolhead updates #86](#2022-02-14---stealthburner-adxl-support-and-toolhead-updates-86)
  - [2022-02-01 - Revised stealthburner_leds.cfg #80](#2022-02-01---revised-stealthburner_ledscfg-80)
  - [2022-02-01 - Stealthburner diffuser and mask updates #79](#2022-02-01---stealthburner-diffuser-and-mask-updates-79)
  - [2022-01-27 - Major updates for Stealthburner #76](#2022-01-27---major-updates-for-stealthburner-76)
  - [2022-01-27 - Corrected missing hole-bridge feature on main_body #75](#2022-01-27---corrected-missing-hole-bridge-feature-on-main_body-75)
  - [2022-01-27 - Corrected tiny unwanted artifact on motor plate #74](#2022-01-27---corrected-tiny-unwanted-artifact-on-motor-plate-74)
  - [2022-01-27 - Clockwork2 Updates focusing on filament tension and design finesse #73](#2022-01-27---clockwork2-updates-focusing-on-filament-tension-and-design-finesse-73)
  - [2022-01-20  - Set initial_RED to 1 #70](#2022-01-20----set-initial_red-to-1-70)
  - [2022-01-16 - Clockwork2 updates #67](#2022-01-16---clockwork2-updates-67)
  - [2022-01-14 - Small fixes for Dragon and Rapido TH #63](#2022-01-14---small-fixes-for-dragon-and-rapido-th-63)
  - [2022-01-14 - Toolhead updates #61](#2022-01-14---toolhead-updates-61)
  - [2022-01-06 - Stealthburner fan cutout updates and toolhead changes #53](#2022-01-06---stealthburner-fan-cutout-updates-and-toolhead-changes-53)
  - [2021-12-29 - Repaired missing features in Guidler and Motor Plate #41](#2021-12-29---repaired-missing-features-in-guidler-and-motor-plate-41)
  - [2021-12-29 - Made adjustments to V6/R6 Toolhead #39](#2021-12-29---made-adjustments-to-v6r6-toolhead-39)
  - [2021-12-29 - Stealthburner updates, CW2 adjustments, chain anchors, Phaetus fixes #38](#2021-12-29---stealthburner-updates-cw2-adjustments-chain-anchors-phaetus-fixes-38)
  - [2021-12-27 - Corrected CW2 filament path #23](#2021-12-27---corrected-cw2-filament-path-23)
  - [2021-12-24 - Sb betaupdate1 #21](#2021-12-24---sb-betaupdate1-21)
<br>

# Introduction

This marks the beta release of the next generation of the Voron Afterburner: Stealthburner

As with any beta release, the provided STLs and manuals are not final, and we ask the community to provide feedback in the `#stealthburner_beta`  channel on our discord server.

![image](https://user-images.githubusercontent.com/4352664/147270796-57a92610-b85f-49b1-8e2a-21ffb9f59b06.png)
<br>
![Voron Logo](http://vorondesign.com/images/voron_design_logo.png)

<br>

# Filename Nomenclature
`_____.stl` -> Base color<br>
`[a]-*.stl` ->  Accent color<br>
`[o]-*.stl` ->  Opaque (light doesn't penetrate)<br>
`[c]-*.stl` ->  Clear/Translucent (light can penetrate)<br>
`*-cw1.stl` ->  Clockwork1 Version<br>
`*-cw2.stl` ->  Clockwork2 Version<br>

<br>
<br>

# CHANGE LOG: *(Detailing significant changes)*

<br>

## 2022-02-14 - Minor adjustments to ADXL mounts [#87](https://github.com/VoronDesign/Voron-Afterburner/pull/87)
**Affected Files:**<br>

\~ `/Stealthburner/ADXL345_Mounts/sb_adxl_washer-beta0.stl`<br>

\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_adafruit_19mm_c-c.stl-beta1`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_generic_15.5mm_c-c.stl-beta1`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_ldo_15mm_c-c.stl-beta1`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_washer-beta1.stl`<br>

\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_adafruit_19mm_c-c.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_generic_15.5mm_c-c.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_ldo_15mm_c-c.stl`<br>

> **Minor Changes:**
> * Shortened ADXL mounting area height to allow for more thread engagement.  (Thanks HackerJack42)
> * Slightly adjusted profile of ADXL mounts to make the design flow better.
> * Renamed ADXL mounts to match the rest of the Beta components.

<br>

## 2022-02-14 - Stealthburner ADXL Support and toolhead updates [#86](https://github.com/VoronDesign/Voron-Afterburner/pull/86)
**Affected Files:**<br>
\~ `/Stealthburner/Toolheads/README.md`<br>

\+ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-front-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-front-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw1-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw2-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-front-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw1-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw2-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta4.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-front-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw1-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw2-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-front-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw1-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw2-beta3.stl`<br>
\+ `/Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-front-beta0.stl`<br>
\+ `/Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-rear-cw1-beta0.stl`<br>
\+ `/Stealthburner/Toolheads/revo_voron/stealthburner_toolhead_(revo_voron)-rear-cw2-beta0.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_adafruit_19mm_c-c.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_generic_15.5mm_c-c.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_mount_ldo_15mm_c-c.stl`<br>
\+ `/Stealthburner/ADXL345_Mounts/sb_adxl_washer.stl`<br>

\- `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-front-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-front-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw1-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw2-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-front-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw1-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw2-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta3.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta2.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta2.stl`<br>
\- `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-front-beta1.stl`<br>
\- `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw1-beta0.stl`<br>
\- `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw2-beta0.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-front-beta2.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw1-beta2.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw2-beta2.stl`<br>


> **Major Changes:**
> Added `revo_voron` toolhead in preperation for upcoming release!
> `dragon_front` hotend duct has been revised to alleviate heatcreep issues in certain situations while printing PLA.
> All toolhead front sections now come with integrated mounting points for ADXL345 sensors for Input Shaping.  Choose mount you need from the new `ADXL345_Mounts` folder.
> ADXL345 mounts have been added. Mounts for LDO, Adafruit, and most generic sensors included.
> All toolheads now include revised M3x50mm screw extraction feature which should eliminate an gaps between the toolhead and the carriage when installing a toolhead for the first time. (Thank you to everyone who printed any of the 19 test pieces and offered feedback!)
> 
>  **Minor Changes:**
> `rapido_rear` rear has been revised to allevaite fastener interference with Omron probes.
> Toolhead STL Readme updated to include E3D Revo Voron.

<br>

## 2022-02-01 - Revised stealthburner_leds.cfg [#80](https://github.com/VoronDesign/Voron-Afterburner/pull/80)

**Affected Files:**<br>
~ `Klipper_Macros/stealthburner_leds.cfg`

>Restructured the config a little and added step-by-step instructions on how to set up and  use this new-found goodness.
>
>Hopefully the quells a lot of the questions and confusion from people new to Klipper and macros.

<br>

## 2022-02-01 - Stealthburner diffuser and mask updates [#79](https://github.com/VoronDesign/Voron-Afterburner/pull/79)
**Affected Files:**<br>
\+ `/Stealthburner/[a]_stealthburner_main_body_beta5.stl`<br>
\+ `/Stealthburner/[c]_stealthburner_LED_diffuser-beta3.stl`<br>
\+ `/Stealthburner/[o]_stealthburner_LED_diffuser-mask-beta1.stl`<br>

\- `/Stealthburner/[c]_stealthburner_LED_diffuser-beta2.stl`<br>
\- `/Stealthburner/[o]_stealthburner_LED_diffuser-mask-beta0.stl`<br>

> **Major Changes:**<br>
>* added chamfers (a) to `main_body` diffuser cavity entrance to make getting that little >guy in there much easier.
>* created slightly more clearance to `diffuser`/`mask` mating surfaces.
>* added chamfer to print surface (b) of `diffuser_mask` to battle elephants foot.
>* added chamfers (c) to `diffuser` to help with printing and assembling.
>>
>  **Minor Changes:**<br>
> - removed a strange little polygon artifact from the bottom of `main_body` (d).

<br>

## 2022-01-27 - Major updates for Stealthburner [#76](https://github.com/VoronDesign/Voron-Afterburner/pull/76)
**Affected Files:**<br>
\+ `/Clockwork2/main_body-beta6.stl`<br>
\+ `/Stealthburner/[a]_stealthburner_main_body_beta4.stl`<br>
\+ `/Stealthburner/[c]_stealthburner_LED_diffuser-beta2.stl`<br>
\+ `/Stealthburner/[o]_stealthburner_LED_carrier-beta2.stl`<br>
\+ `/Stealthburner/[o]_stealthburner_LED_diffuser-mask-beta0.stl`<br>

\- `/Clockwork2/main_body-beta5.stl`<br>
\- `/Stealthburner/[a]_stealthburner_main_body_beta3.stl`<br>
\- `/Stealthburner/[c]_stealthburner_LED_diffuser-beta1.stl`<br>
\- `/Stealthburner/[c]_stealthburner_LED_carrier-beta1.stl`<br>

>Changes in this PR will mean that ALL diffusers and LED carriers from previous versions will **no longer be compatible**.  Please print the latest and greatest.
>
>`[a]` ->  Accent color <br>
>`[o]` ->  Opaque (light doesn't penetrate)<br>
>`[c]` ->  Clear/Translucent (light can penetrate)<br>
>
>- `main_body` has had nozzle LED retainer mechanism completely reworked.  The 17th version was the winner.  Thank you to all who printed the test pieces and reported back with feedback.
>- `main_body` has had some work done under the hood to try and help reduce light bleed from the Logo LED through somewhat translucent main body colors.
>- `main_body` nozzle led wiring channel slightly reworked to accommodate revised LED retainer springs.
>- `led_carrier` has been revised to accommodate thicker PCBs, but most importantly has had the bottom cut out.  **the LED carrier should now be printed out of an opaque filament**
>- `led_diffuser` has been redesigned (may still get some more massaging depending on feedback.
>- `led_diffuser_mask`  ......that's a new one.  The diffuser now fits inside of this impenetrable fortress for light. The diffuser mask should be printed out of an opaque material as well to keep the light contained and only spill it where we want.
>
>![image](https://user-images.githubusercontent.com/34219833/151489492-828ae1f5-051d-45f8-bebe-7ae1532a2b76.png)
>
>
>Repaired missing counterbore on CW2 Main Body.
>![image](https://user-images.githubusercontent.com/34219833/151511988-8ff86ecb-ecb7-46ec-818a-5d780dca8bf8.png)

<br>

## 2022-01-27 - Corrected missing hole-bridge feature on main_body [#75](https://github.com/VoronDesign/Voron-Afterburner/pull/75)

**Affected Files:**<br>
~ `/Clockwork2/main_body-beta5.stl`

<br>

## 2022-01-27 - Corrected tiny unwanted artifact on motor plate [#74](https://github.com/VoronDesign/Voron-Afterburner/pull/74)

**Affected Files:**<br>
~ `/Clockwork2/motor_plate-beta4.stl`

<br>

## 2022-01-27 - Clockwork2 Updates focusing on filament tension and design finesse [#73](https://github.com/VoronDesign/Voron-Afterburner/pull/73)

**Affected Files:**<br>
\+ `/Clockwork2/[a]_guidler_a-beta4.stl`<br>
\+ `/Clockwork2/[a]_guidler_b-beta4.stl`<br>
\+ `/Clockwork2/[a]_latch-beta1.stl`<br>
\+ `/Clockwork2/[a]_latch_shuttle-beta1.stl`<br>
\+ `/Clockwork2/main_body-beta5.stl`<br>
\+ `/Clockwork2/motor_plate-beta4.stl`<br>

\- `/Clockwork2/[a]_guidler_a-beta3.stl`<br>
\- `/Clockwork2/[a]_guidler_b-beta3.stl`<br>
\- `/Clockwork2/[a]_latch-beta0.stl`<br>
\- `/Clockwork2/[a]_latch_shuttle-beta0.stl`<br>
\- `/Clockwork2/main_body-beta4.stl`<br>
\- `/Clockwork2/motor_plate-beta3.stl`<br>

> **Clockwork2 Updates:**
> - Revised `main_body` to allow more travel of guidler...further increasing maximum allowable tension on filament (she won't go any more, Captain).
> - Reworked `main_body` and `motor_plate` in preparation of mounting locations for toolhead PCB designed by Hartk.
> - Adjusted depth of counter-bore on latch-locking bolt (M3x25) in `main_body` to give better thread-engagement.
> - Revised diameter of motor mount/adjustment slot on `motor_plate` to allow larger diameter washers to be used.
> - Reworked `guidler_a` to create more initial tension on filament.
> - Reworked `guidler_a` to reduce some unnecessary fore/aft clearance on driven gear.
> - Reworked `guidler_a` filament tensioner hole to be slotted rather than just a clearance hole to allow unrestricted movement of guidler.
> - Reworked orientation slot/tab on `guidler_a`. `guidler_b`, and `latch_shuttle` from a straight tab to an arc to prevent binding. (since it travels in an arc...).
> - Adjusted profile of `latch_shuttle` to accommodate additional travel of guidler or greater.
> - Adjusted `latch` to require slighty more force to lock the shuttle and to make the latch a little more "grabby" around it's locking bolt.

<br>

## 2022-01-20  - Set initial_RED to 1 [#70](https://github.com/VoronDesign/Voron-Afterburner/pull/70)
**Affected Files:**<br>
\~ `Klipper_Macros/stealthburner_leds.cfg`<br>

<br>

## 2022-01-16 - Clockwork2 updates [#67](https://github.com/VoronDesign/Voron-Afterburner/pull/67)
**Affected Files:**<br>
\+ `/Clockwork2/[a]_guidler_a-beta3.stl`<br>
\+ `/Clockwork2/[a]_guidler_b-beta3.stl`<br>
\+ `/Clockwork2/main_body-beta4.stl`<br>
\+ `/X_Carriage/[a]_x_bearing_block_SW_beta0.stl`<br>
\+ `/X_Carriage/x_frame_SW_left-beta1.stl`<br>
\+ `/X_Carriage/x_frame_SW_right-beta1.stl`<br>

\- `/Clockwork2/[a]_guidler_a-beta2.stl`<br>
\- `/Clockwork2/[a]_guidler_b-beta2.stl`<br>

> Some changes have been made to the guidler and main body to help improve filament engagement/tension over a wider variety of BMG gears.
> 
> **Changes:**
> * Guidler A and B update to allow for more travel (more filament engagement/tension).
> * Idler shaft area has additional support material added to deflection when pushing extruder to more extreme extrusion levels.
> * Main Body was updated to accommodate additional travel.
> * Switchwire X Frame update to allow more clearance for probe. (Thanks Steve)

<br>

## 2022-01-14 - Small fixes for Dragon and Rapido TH [#63](https://github.com/VoronDesign/Voron-Afterburner/pull/63)
**Affected Files:**<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta3.stl`<br>

\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta2.stl`<br 
> **Fixes:**
> * Added missing air-bleed ports for Dragon toolhead front.
> * Fixed hotend fan flow-straightener vane on Rapido toolhead front.

<br>

## 2022-01-14 - Toolhead updates [#61](https://github.com/VoronDesign/Voron-Afterburner/pull/61)
**Affected Files:**<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-front-beta2-.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw1-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6_r6)-rear-cw2-beta2.stl`<br>

\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta0.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta0.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta0.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta1.stl`<br>
\- `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta1.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-front-beta1.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw1-beta1.stl`<br>
\- `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw2-beta1.stl`<br>

> Some toolhead updates to correct some shortcomings on the previous revisions.
> 
> **Changes:**
> * V6/R6 toolhead cutout has been revised to optimize airflow across lower portion of heatsink and no long forces heat higher up the heatsink.
> * Dragon toolhead has had the nozzle height corrected.  It was roughly 1.4mm too high.
> * Rapido toolhead mounting bolt pattern has been rotated 12° to orient the metal strain-relief tab better.  Also added a tiny bit more clearance for strain-relief zip-tie.

<br>

## 2022-01-06 - Stealthburner fan cutout updates and toolhead changes [#53](https://github.com/VoronDesign/Voron-Afterburner/pull/53)
**Affected Files:**<br>

\~ `README.md` <br>
\~ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-front-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_bmo/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-front-beta0.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw1-beta0.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_dragon/stealthburner_toolhead_(dragon)-rear-cw2-beta0.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-front-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw1-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/phaetus_rapido/stealthburner_toolhead_(rapido)-rear-cw2-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-front-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw1-beta0.stl`<br>
\~ `/Stealthburner/Toolheads/revo_micro/stealthburner_toolhead_(revo_micro)-rear-cw2-beta0.stl`<br>
\~ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-front-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw1-beta1.stl`<br>
\~ `/Stealthburner/Toolheads/revo_six_&_v6/stealthburner_toolhead_(v6)-rear-cw2-beta1.stl`<br>

\+ `/Clockwork2/motor_plate-beta3.stl`<br>
\+ `/Stealthburner/[a]_stealthburner_main_body_beta3.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-front-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw1-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms6)-rear-cw2-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-front-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw1-beta2.stl`<br>
\+ `/Stealthburner/Toolheads/phaetus_bms/stealthburner_toolhead_(phaetus_bms7)-rear-cw2-beta2.stl`<br>

\- `/Clockwork2/motor_plate-beta2.stl`<br>
\- `/Stealthburner/[a]_stealthburner_main_body_beta2.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-front-beta1.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-rear-cw1-beta1.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-rear-cw2-beta1.stl`<br>

>**Stealthburner Updates:**
> 
> * Re-centered 5015 inlet to undo previous bad decision :)   (Delta and GDSTIME fans are perfectly centered)
> * Added a tiny bit of additional wiring clearance for 4014 fan wiring
> * Completely redesigned nozzle-nozzle LED wiring channel to give added strength to main body mounting screw locations
> * Made a couple of changes to 4010 fan area to ease fan installation
> * Tweaked bridging for upper wire retainer
> 
>**Toolhead Changes:**
> 
> * Added Phaetus Rapido toolhead
> * Fixed type on BMS toolhead
> * Split BMS toolhead up into 6 and 7 fin designs which should now support Zodiac version as well
> * Re-organized toolheads into sub-folders to make selecting the correct files easier
> * Updated Readme.md to be more helpful and supportive (thanks for the help Timmit!)
> 
>**Clockwork 2 Changes:**
> 
> * fixed a missing print-hack thingy for a chain anchor mount threaded insert

<br>

## 2021-12-29 - Repaired missing features in Guidler and Motor Plate [#41](https://github.com/VoronDesign/Voron-Afterburner/pull/41)
**Affected Files:**<br>
\+ `/Clockwork2/[a]_guidler_a-beta2.stl`<br>
\+ `/Clockwork2/[a]_guidler_b-beta2.stl`<br>
\+ `/Clockwork2/main_body-beta3.stl`<br>
\+ `/Clockwork2/motor_plate-beta2.stl`<br>

\- `/Clockwork2/[a]_guidler_a-beta1.stl`<br>
\- `/Clockwork2/[a]_guidler_b-beta1.stl`<br>
\- `/Clockwork2/main_body-beta2.stl`<br>
\- `/Clockwork2/motor_plate-beta1.stl`<br>

> A CAD error caused some features to go boom from the previous commit. These have been corrected. My apologies for not catching this. Thanks to Steve for notifying me as soon as you did.
> 
> Reprint:
> 
> * [a]_guidler_a-beta2.stl
> * [a]_guidler_b-beta2.stl
> 
> Don't necessarily need to reprint:
> 
> * main_body-beta3.stl
> * motor_plate-beta2.stl

## 2021-12-29 - Made adjustments to V6/R6 Toolhead [#39](https://github.com/VoronDesign/Voron-Afterburner/pull/39)
**Affected Files:**<br>
\~ `/Stealthburner/Toolheads/README.txt`<br>

\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-front-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw1-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw2-beta1.stl`<br>

\- `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-front-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw1-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw2-beta0.stl`<br>

## 2021-12-29 - Stealthburner updates, CW2 adjustments, chain anchors, Phaetus fixes #38
**Affected Files:**<br>
\+ `/Clockwork2/[a]_guidler_a-beta1.stl`<br>
\+ `/Clockwork2/[a]_guidler_b-beta1.stl`<br>
\+ `/Clockwork2/cable_door-beta1.stl`<br>
\+ `/Clockwork2/chain_anchor_2hole-beta1.stl`<br>
\+ `/Clockwork2/chain_anchor_2hole-SW-beta0.stl`<br>
\+ `/Clockwork2/chain_anchor_3hole-beta1.stl`<br>
\+ `/Clockwork2/chain_anchor_3hole-SW-beta0.stl`<br>
\+ `/Clockwork2/main_body-beta2.stl`<br>
\+ `/Clockwork2/motor_plate-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bmo)-front-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-front-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-rear-cw1-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-rear-cw2-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-front-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw1-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw2-beta1.stl`<br>
\+ `/Stealthburner/[a]_stealthburner_main_body_beta2.stl`<br>
\+ `/Stealthburner/[c]_stealthburner_LED_carrier-beta1.stl`<br>
\+ `/Stealthburner/[c]_stealthburner_LED_diffuser-beta1.stl`<br>

\- `/Clockwork2/[a]_guidler_a-beta0.stl`<br>
\- `/Clockwork2/[a]_guidler_b-beta0.stl`<br>
\- `/Clockwork2/cable_door-beta0.stl`<br>
\- `/Clockwork2/chain anchor_2hole-beta0.stl`<br>
\- `/Clockwork2/chain anchor_3hole-beta0.stl`<br>
\- `/Clockwork2/main_body-beta1.stl`<br>
\- `/Clockwork2/motor_plate-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bmo)-front-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bmo)-rear-cw1-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bmo)-rear-cw2-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-front-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-rear-cw1-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(phaetus_bms)-rear-cw2-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-front-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw1-beta0.stl`<br>
\- `/Stealthburner/Toolheads/stealthburner_toolhead_(v6)-rear-cw2-beta0.stl`<br>
\- `/Stealthburner/a_stealthburner_main_body_beta1.stl`<br>
\- `/Stealthburner/c_stealthburner_LED_carrier-beta1.stl`<br>
\- `/Stealthburner/c_stealthburner_LED_diffuser-beta1.stl`<br>

>**Corrected CW2 filament path**
>- Corrected 0.6mm misalignment for filament path with Clockwork2 Main Body.  Corrected small cutout issue on Revo Micro Toolhead Front that should not require a reprint.
>
>**Replace RevoMicro toolhead**
>- Replaced original Beta1 STL with version with repaired geometry
>
>**Revised filename on RevoMicro**
>
>**Added Switchwire cable chain anchors**
>
>**...and corrected SB file names**
>
>**Stealthburner Changes:**
>
>- Offset 5015 fan inlet slightly to align center of impeller better due to wide variances between fans from different manufacturers.
>- Reduced size of inlet loft at impeller to increase fan efficiency and greatly improve performance.
>- Added some additional clearance for Sanace B52 fans. (Hopefully they fit now)
>- Removed small amount of material on bottom of 5015 fan cutout that was causing some impellers to rub the Main Body.
>- Reduced mounting screw depth by 1mm on Phaetus-BMO Toolhead.
>- Revised corner radius on toolhead cutout for Phaetus-BMS to match actual parts vs. Phaetus CAD.
>- Fixed naming on several files.
>- Started to replace toolhead identification mark on Toolhead Rear.
>
>**Clockwork2 Changes:**
>- Added chain anchors for Voron Switchwire.
>- Adjusted all chain anchors to have better thread-engagement on M3x20 mounting bolt. (Does not require reprint if yours work ok)
>- Added some additional clearances to Main Body, Guidler, and Motor Plate to accommodate large variances in drive shafts and gears.  (Does not require reprint if yours work ok)
>- Added small alignment features to Motor Plate and Cable Cover to help aligned screw hole easier.
>- Revised hole size on cable door for better thread engagement.
>
>**Remove old stls**

<br>

## 2021-12-27 - Corrected CW2 filament path [#23](https://github.com/VoronDesign/Voron-Afterburner/pull/23)

**Affected Files:**<br>
\+ `/Clockwork2/main_body-beta1.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(revo_micro)-front-beta1.stl`<br>
\+ `/Clockwork2/main_body-beta0.stl`<br>
\+ `/Stealthburner/Toolheads/stealthburner_toolhead_(revo_micro)-front-beta0.stl`<br>

>Corrected 0.6mm misalignment for filament path with Clockwork2 Main Body. Corrected small cutout issue on Revo Micro Toolhead Front that should not require a reprint.

<br>

## 2021-12-24 - Sb betaupdate1 [#21](https://github.com/VoronDesign/Voron-Afterburner/pull/21)

**Affected Files:**<br>
\+ `/Stealthburner/a_stealthburner_main_body_beta1.stl`<br>
\+ `/Stealthburner/c_stealthburner_LED_carrier-beta1.stl`<br>
\+ `/Stealthburner/c_stealthburner_LED_diffuser-beta1.stl`<br>

\- `/Stealthburner/[a]_stealthburner_main_body_beta0.stl`<br>
\- `/Stealthburner/[c]_stealthburner_LED_carrier-beta0.stl`<br>
\- `/Stealthburner/[c]_stealthburner_LED_diffuser-beta0.stl`<br>

>Fixed a missing fillet on Stealthburner main_body which was causing slicing and print issues for some users.
>
>Revised LED carrier to accommodate some PCBs that have SMD components soldered wider than usual.
>
>Revised LED diffuser to add more clearance on top and re-designed internal structure of printed part for easier printing.
