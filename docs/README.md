# Classify
- [🤗 HuggingFace](https://huggingface.co/TheDuyx)
- [📝 Train-test notebook](https://colab.research.google.com/drive/1w3ec_ry5XV4yTZ-v3HO-gWzp1hAJdx9_?usp=sharing)
- [📝 K-Fold notebook](https://colab.research.google.com/drive/1-I6tPCd4QZhS1xcFdkm1EXcGLXs2zIzP)
- [📝 Analysis notebook](https://colab.research.google.com/drive/1S24Ljh89GjxLtmrfNbjkxF2DoWJBnaJF?usp=sharing)
- [🍀 Overleaf](https://github.com/ThaDuyx/overleaf)
- [🐈‍⬛ Wavize: Webapp](https://github.com/ThaDuyx/wavize)

## Current results
### Accuracy
```
Correct guesses: 126 out of 138
Accuracy: 91.3%

slap - 20/21 ~ 95.24%
acid - 14/18 ~ 77.78%
brass - 16/16 ~ 100.0%
sub - 14/15 ~ 93.33%
reese - 17/17 ~ 100.0%
growl - 17/19 ~ 89.47%
808 - 28/32 ~ 87.5%
```
### Confusion Matrix
![alt text](https://github.com/ThaDuyx/Classify/blob/dev/main/evaluate/confusion_matrix.png?raw=true)

### ROC-Curve
![alt text](https://github.com/ThaDuyx/Classify/blob/dev/main/evaluate/roc_curve.png?raw=true)

### Performance Metrics
```
              precision    recall  f1-score     support
808            1.000000  0.875000  0.933333   32.000000
acid           0.875000  0.777778  0.823529   18.000000
brass          0.800000  1.000000  0.888889   16.000000
growl          0.944444  0.894737  0.918919   19.000000
reese          0.850000  1.000000  0.918919   17.000000
slap           1.000000  0.952381  0.975610   21.000000
sub            0.875000  0.933333  0.903226   15.000000
accuracy       0.913043  0.913043  0.913043    0.913043
macro avg      0.906349  0.919033  0.908918  138.000000
weighted avg   0.920793  0.913043  0.913259  138.000000
```
### slap
- ✅: slap / slap - AU_ESH2_bass_synth_one_shot_bristly_G#.wav
- ✅: slap / slap - AU_ESH2_bass_synth_one_shot_sharp_F.wav
- ✅: slap / slap - BOS_ADJ_Bass_Synth_One_Shot_Stepper_E.wav
- ✅: slap / slap - DS_DSH_bass_synth_one_shot_bad_blood_high_C.wav
- ✅: slap / slap - DS_DSH_bass_synth_one_shot_control_low_C.wav
- ✅: slap / slap - DS_DSH_bass_synth_one_shot_light_high_C.wav
- ❌: slap / acid - DS_DSH_bass_synth_one_shot_nothing_to_lose_high_C.wav
- ✅: slap / slap - DS_SSH_bass_synth_one_shot_boss_slap_C.wav
- ✅: slap / slap - DS_VEDMH_bass_slap_one_shot_way_C.wav
- ✅: slap / slap - FL_SH_Kit01_Bass_One_Shot_Synth.wav
- ✅: slap / slap - FL_SH_Kit04_Bass_One_Shot_Synth.wav
- ✅: slap / slap - FL_SH_Kit05_Bass_One_Shot_Synth.wav
- ✅: slap / slap - FL_VSH_Better_Bass_One_Shot_Deep_C.wav
- ✅: slap / slap - PM_GB_Bass_One_Shot_Click_F#.wav
- ✅: slap / slap - PM_GB_Bass_One_Shot_Short_G.wav
- ✅: slap / slap - STCR2_VPSH_Bass_One_Shot_Anthem_F.wav
- ✅: slap / slap - STCR2_VPSH_Bass_One_Shot_Gravity_A.wav
- ✅: slap / slap - TRKTRN_CSH_Bass_One_Shot_Anomaly_D#.wav
- ✅: slap / slap - TRKTRN_CSH_Bass_One_Shot_Kola_G.wav
- ✅: slap / slap - TRKTRN_CSH_Bass_One_Shot_Orchid_D#.wav
- ✅: slap / slap - TRKTRN_FISH_Bass_One_Shot_Legend_F#.wav

### acid
- ✅: acid / acid - Acid_1.wav
- ✅: acid / acid - Bpm138_C_Vindicator_Bass01.wav
- ✅: acid / acid - DASHA_RUSH_130_acid_loop_02_01.wav
- ✅: acid / acid - DASHA_RUSH_130_acid_loop_02_05.wav
- ❌: acid / brass - DS_T_136_bass_synth_loop_area_acid_F#min.wav
- ❌: acid / brass - DS_T_138_bass_synth_loop_universe_acid_F#min.wav
- ✅: acid / acid - FF_ATS_142_kit_quantum_bass_Dmin.wav
- ✅: acid / acid - GHD_Kit2_acid_shot_126_G#_minor.wav
- ✅: acid / acid - OS_SLT_C_Acid_Hit__Low_.wav
- ✅: acid / acid - PLX_ACT_synth_blade_Eb.wav
- ✅: acid / acid - PLX_ACT_synth_crisp_F.wav
- ❌: acid / growl - PLX_ACT_synth_ear_F.wav
- ✅: acid / acid - RU_IA_squelch_bass_C.wav
- ❌: acid / brass - STCR2_MTA_Synth_Lead_One_Shot_Acid_A.wav
- ✅: acid / acid - TL_Bass_07.wav
- ✅: acid / acid - plx_itt_synth_acid_growl_#D.wav
- ✅: acid / acid - pt_acid_128_burr_F.wav
- ✅: acid / acid - shs_rs_acid_shot_4_B.wav

### brass
- ✅: brass / brass - ABJP_Brass_19_Stab_A#__Low_.wav
- ✅: brass / brass - ABJP_Brass_20_Stab_D#m__Low_.wav
- ✅: brass / brass - BOS_ADJ_Bass_Synth_One_Shot_Mellow_F.wav
- ✅: brass / brass - D#_BrassStab_TL.wav
- ✅: brass / brass - DMVU_BRASS_STACC_D#.wav
- ✅: brass / brass - EHT_one_shot_melodic_brass_1_C.wav
- ✅: brass / brass - JPGC_one_shot_mr_brass_Dmaj.wav
- ✅: brass / brass - JUST_hit_brass_2.wav
- ✅: brass / brass - KSHMR_Brass_Stab_03_-__F_.wav
- ✅: brass / brass - OSKAR_FLOOD_hit_horn_blast_C.wav
- ✅: brass / brass - PMTQ_Brass_A#_Horn.wav
- ✅: brass / brass - PMTQ_Brass_F_Huge.wav
- ✅: brass / brass - RKU_NG_Bass_Synth_One_Shot_Grime_Brass_Stab_E.wav
- ✅: brass / brass - SO_BA_brass_themachine_triumphs_big_band_G.wav
- ✅: brass / brass - TDS_brass_stab_death_D.wav
- ✅: brass / brass - rss_brass_stab_D#maj.wav

### sub
- ✅: sub / sub - 808_VIRGOAPTO.wav
- ✅: sub / sub - 808_VIRGOCHESNUT.wav
- ✅: sub / sub - 808_VIRGOCHIKO.wav
- ✅: sub / sub - 808_VIRGOKRIST.wav
- ✅: sub / sub - 808_VIRGOPERFECT.wav
- ✅: sub / sub - Bass_Loops_Lo-Fi_Bass_06_85_G.wav
- ✅: sub / sub - DS_VTH_fx_one_shot_back_bass_sub_drop.wav
- ✅: sub / sub - H808_Bass_One_shot_Deep.wav
- ✅: sub / sub - KLAX_808_Hit_03_F.wav
- ❌: sub / reese - OS_GIRL_808_B_Cruz.wav
- ✅: sub / sub - OS_GIRL_808_G_Spy.wav
- ✅: sub / sub - PB_SUB.WAV
- ✅: sub / sub - RKU_NG_Bass_Synth_One_Shot_Fat_Sub_Stab_Clean_F#.wav
- ✅: sub / sub - SO_PTW_Jupiter_sub_note_Bb.wav
- ✅: sub / sub - STC2_VPSH_122_Kit_Loop_Asleep_Sub_Drop_G.wav

### reese
- ✅: reese / reese - AU_PM_bass_synth_one_shot_dream_myth_A.wav
- ✅: reese / reese - BOS_DBK_174_Bass_Reese_Loop_Deep_F.wav
- ✅: reese / reese - DS_MDH_120_bass_synth_loop_toxic_sub_Gmin.wav
- ✅: reese / reese - DS_PDH_120_bass_synth_loop_witness_reese_wide_D#min.wav
- ✅: reese / reese - DS_PDH_122_bass_synth_loop_wish_reese_agressive_Gmin.wav
- ✅: reese / reese - DS_VLUARR_128_bass_reese_loop_jungle_Amin.wav
- ✅: reese / reese - FL_ED_Kit01_808_One_Shot_F#.wav
- ✅: reese / reese - FL_ED_Kit02_808_One_Shot_G.wav
- ✅: reese / reese - FL_ED_Kit03_808_One_Shot_E.wav
- ✅: reese / reese - FMP_Kit1_115_Drone_Bass_Progression_1_C#_Major.wav
- ✅: reese / reese - MTW_loop_reese_bass_3_140_Amin.wav
- ✅: reese / reese - OS_MRS_140_synth_reese_bass_icebox_Dm.wav
- ✅: reese / reese - OS_SHD_135_Dm_Serial_Crunch_Bass_2.wav
- ✅: reese / reese - RKU_SRT_90_bass_reese_loop_sad_girl_first_Amin.wav
- ✅: reese / reese - RKU_SRT_90_bass_reese_loop_sad_girl_second_Amin.wav
- ✅: reese / reese - RST_Loop_Bass_Reese_Conor_120_G_Minor.wav
- ✅: reese / reese - ZEN_BPH_bass_one_shot_burgundy_F.wav

### growl
- ✅: growl / growl - Au5_bass_wet_growl_02_F.wav
- ✅: growl / growl - BOS_RHD_Bass_One_Shot_Full_Growl_F#.wav
- ✅: growl / growl - BOS_RHD_Bass_One_Shot_OG_Growl_D.wav
- ✅: growl / growl - CONVEX_bass_one_shot_phase_nasty_F.wav
- ✅: growl / growl - DS_SPP2_bass_one_shot_growl_vital_madness_old_D#.wav
- ✅: growl / growl - EFFIN_bass_double_dose_D.wav
- ✅: growl / growl - EFFIN_bass_laundry_F.wav
- ✅: growl / growl - EFFIN_bass_tumble_dry_F.wav
- ✅: growl / growl - EFFIN_bass_zipper_01_D#.wav
- ✅: growl / growl - FL_BRD_Kit05_Bass_One_Shot_Growl_02.wav
- ✅: growl / growl - HD_bass_growl_howler_F.wav
- ✅: growl / growl - MLEUC_bass_oneshot_growl_weird_E.wav
- ✅: growl / growl - MODE_BE2_bass_growl_solow_D#.wav
- ✅: growl / growl - PMHJ_Bass_E_Clunk.wav
- ❌: growl / acid - RICKYXSAN_growl_one_shot_06_F.wav
- ✅: growl / growl - SAMPLIFIRE_bass_one_shot_growl_bounce_back_D#.wav
- ❌: growl / brass - V_RIOT_bass_standart_growl_02_F.wav
- ✅: growl / growl - tp_macky_gee_bass_one_shot_car_horn_F.wav
- ✅: growl / growl - tp_macky_gee_bass_one_shot_donkey_F.wav

### 808
- ❌: 808 / sub - 808_VIRGLONG.wav
- ✅: 808 / 808 - 808_VIRGOANTICHRIS.wav
- ❌: 808 / reese - 808_VIRGOCROSSS.wav
- ✅: 808 / 808 - 808_VIRGOINDIGO.wav
- ❌: 808 / sub - 808_VIRGOLAGO.wav
- ✅: 808 / 808 - 808_VIRGOLESTAF.wav
- ✅: 808 / 808 - 808_VIRGOSHORDIE.wav
- ✅: 808 / 808 - 808_VIRGOSYNDICATE.wav
- ✅: 808 / 808 - 808_VIRGSHORT.wav
- ✅: 808 / 808 - JETSONMADE_808_alien_C.wav
- ✅: 808 / 808 - JETSONMADE_808_class2_C.wav
- ✅: 808 / 808 - JETSONMADE_808_lil83_C.wav
- ✅: 808 / 808 - JETSONMADE_808_rocket2_C.wav
- ✅: 808 / 808 - JETSONMADE_808_space2_C.wav
- ✅: 808 / 808 - OS_GIRL_808_A#_Block.wav
- ✅: 808 / 808 - OS_GIRL_808_A_Lowrider.wav
- ✅: 808 / 808 - OS_GIRL_808_A_Sunwave.wav
- ✅: 808 / 808 - OS_GIRL_808_B_Viking.wav
- ✅: 808 / 808 - OS_GIRL_808_C#_Heavy.wav
- ✅: 808 / 808 - OS_GIRL_808_C_Bubbly.wav
- ✅: 808 / 808 - OS_GIRL_808_D#_Crumz.wav
- ✅: 808 / 808 - OS_GIRL_808_D_Sargent.wav
- ✅: 808 / 808 - OS_GIRL_808_E_Resurrect.wav
- ✅: 808 / 808 - OS_GIRL_808_E_Stank.wav
- ✅: 808 / 808 - OS_GIRL_808_E_Thud.wav
- ✅: 808 / 808 - OS_GIRL_808_F_Dash.wav
- ❌: 808 / reese - OS_GIRL_808_F_Growl.wav
- ✅: 808 / 808 - OS_GIRL_808_F_Slapper.wav
- ✅: 808 / 808 - OS_GIRL_808_G#_Steady.wav
- ✅: 808 / 808 - OS_GIRL_808_G_Cash.wav
- ✅: 808 / 808 - OS_GIRL_808_G_March.wav
- ✅: 808 / 808 - OS_GIRL_808_G_Thump.wav
