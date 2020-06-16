//
//
// NOTE:  AUTOMATICALLY GENERATED FILE, ANY HAND EDITED COMMENTS WILL BE LOST!!!
// NOTE:  AUTOMATICALLY GENERATED FILE, ANY HAND EDITED COMMENTS WILL BE LOST!!!
// NOTE:  AUTOMATICALLY GENERATED FILE, ANY HAND EDITED COMMENTS WILL BE LOST!!!
//
// VOL_NORM		1.0f
//
//-----------------------------------------------------------------------------
// common attenuation values
//-----------------------------------------------------------------------------
//
// DON'T USE THESE - USE SNDLVL_ INSTEAD!!!
//	ATTN_NONE		0.0f	
//	ATTN_NORM		0.8f
//	ATTN_IDLE		2.0f
//	ATTN_STATIC		1.25f 
//	ATTN_RICOCHET	1.5f
//	ATTN_GUNFIRE	0.27f
//
//	SNDLVL_NONE		= 0,
//	SNDLVL_25dB		= 25,
//	SNDLVL_30dB		= 30,
//	SNDLVL_35dB		= 35,
//	SNDLVL_40dB		= 40,
//	SNDLVL_45dB		= 45,
//	SNDLVL_50dB		= 50,	= 3.9
//	SNDLVL_55dB		= 55,	= 3.0
//	SNDLVL_IDLE		= 60,	= 2.0
//	SNDLVL_TALKING		= 60,	= 2.0
//	SNDLVL_60dB		= 60,	= 2.0
//	SNDLVL_65dB		= 65,	= 1.5
//	SNDLVL_STATIC		= 66,	= 1.25
//	SNDLVL_70dB		= 70,	= 1.0
//	SNDLVL_NORM		= 75,
//	SNDLVL_75dB		= 75,	= 0.8
//	SNDLVL_80dB		= 80,	= 0.7
//	SNDLVL_85dB		= 85,	= 0.6
//	SNDLVL_90dB		= 90,	= 0.5
//	SNDLVL_95dB		= 95,
//	SNDLVL_100dB	= 100,	= 0.4
//	SNDLVL_105dB	= 105,
//	SNDLVL_120dB	= 120,
//	SNDLVL_130dB	= 130,
//	SNDLVL_GUNFIRE	= 140, = 0.27
//	SNDLVL_140dB	= 140,	= 0.2
//	SNDLVL_150dB	= 150,	= 0.2
//

//"water_flood_loop"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"0.400000"
//	"pitch"			"100"
//
//	"soundlevel"	"0"
//
//	"wave"			"ambient/water/seaice1_loop.wav"
//}

"water_flood_finished_loop"
{
	"channel"		"CHAN_STATIC"
	"volume"		"0.150000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_80dB"

	"wave"			"ambient/water/water_flow_loop1.wav"
}

//"container_sparks"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"0.8"
//	"pitch"			"100,120"
//
//	"soundlevel"	"SNDLVL_140db"
//
//	"rndwave"
//	{
//		"wave"	"ambient/energy/weld1.wav"
//		"wave"	"ambient/energy/weld2.wav"
//	}
//}

"stirrer_loop"
{
	"channel"		"CHAN_STATIC"
	"volume"		"VOL_NORM"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_65dB"

	"wave"			"vehicles/airboat/pontoon_fast_water_loop1.wav"
}

//"steamjet"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"VOL_NORM"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_65dB"
//
//	"wave"			"hl1/ambience/steamburst1.wav"
//}

"floodgate_move_short"
{
	"channel"		"CHAN_STATIC"
	"volume"		"1.000000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_100dB"

	"wave"			"ambient/machines/floodgate_move_short1.wav"
}

//"floodgate_move_long"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"1.000000"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_100dB"
//
//	"wave"			"ambient/machines/floodgate_move_long1.wav"
//}

"floodgate_stop"
{
	"channel"		"CHAN_STATIC"
	"volume"		"1.000000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_100dB"

	"wave"			"ambient/machines/floodgate_stop1.wav"
}

"floodgate_klaxon"
{
	"channel"		"CHAN_STATIC"
	"volume"		"0.800000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_100dB"

	"wave"			"ambient/alarms/klaxon1.wav"
}

"floodgate_alarmbell_loop"
{
	"channel"		"CHAN_STATIC"
	"volume"		"0.400000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_100dB"

	"wave"			"ambient/alarms/alarm1.wav"
}

"diesel_generator"
{
	"channel"		"CHAN_STATIC"
	"volume"		"0.600000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_80dB"

	"wave"			"vehicles/diesel_loop2.wav"
}

"wood_creak1"
{
	"channel"		"CHAN_STATIC"
	"volume"		"1.0"
	"pitch"			"100"
	"soundlevel"	"SNDLVL_140db"
	"rndwave"
	{
		"wave"  "ambient/materials/wood_creak1.wav"
		"wave"  "ambient/materials/wood_creak2.wav"
		"wave"  "ambient/materials/wood_creak3.wav"
		"wave"  "ambient/materials/wood_creak6.wav"
	}	
}

"catwalkgroan01"
{
	"channel"		"CHAN_STATIC"
	"volume"		"VOL_NORM"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_100dB"

	"wave"			"ambient/materials/metal_stress1.wav"
}

//"water_flood_in"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"VOL_NORM"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_100dB"
//
//	"wave"			"ambient/water/water_pump_drainin1.wav"
//}

//"water_flood_out"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"VOL_NORM"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_100dB"
//
//	"wave"			"ambient/water/water_pump_drainout1.wav"
//}

//"pipe_water_drip"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"VOL_NORM"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_80dB"
//
//	"wave"			"ambient/water/drip_loop1.wav"
//}

"train_move"
{
	"channel"		"CHAN_STATIC"
	"volume"		"1.000000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_130dB"

	"wave"			"ambient/machines/train_freight_loop1.wav"
}

//"train_wheels"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"1.000000"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_100dB"
//
//	"wave"			"ambient/machines/razor_train_wheels_loop1.wav"
//}

//"train_horn_01"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"0.750000"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_130dB"
//
//	"wave"			"ambient/alarms/razortrain_horn1.wav"
//}

//"train_horn_02"
//{
//	"channel"		"CHAN_BODY"
//	"volume"		"1.000000"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_120dB"
//
//	"wave"			"ambient/alarms/train_horn2.wav"
//}

"train_crossing_bell"
{
	"channel"		"CHAN_BODY"
	"volume"		"0.600000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_105dB"

	"wave"			"ambient/alarms/train_crossing_bell_loop1.wav"
}

//"train_freight_move1"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"1.000000"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_100dB"
//
//	"wave"			"ambient/machines/train_freight_loop2.wav"
//}

//"apc_moving_siren1"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"VOL_NORM"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_100dB"
//
//	"wave"			"ambient/alarms/apc_alarm_pass1.wav"
//}

//"apc_siren1"
//{
//	"channel"		"CHAN_BODY"
//	"volume"		"0.200000"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_80dB"
//
//	"wave"			"ambient/alarms/apc_alarm_loop1.wav"
//}

//"hoist"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"0.800000"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_90dB"
//
//	"wave"			"ambient/materials/metal_rattle2.wav"
//}

"rope_creak"
{
	"channel"		"CHAN_STATIC"
	"volume"		"0.800000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_90dB"

	"wave"			"ambient/materials/metal_stress5.wav"
}

//"rope_break"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"0.800000"
//	"pitch"			"60"
//
//	"soundlevel"	"SNDLVL_90dB"
//
//	"wave"			"ambient/materials/smallwire_pluck3.wav"
//}

//"boxcar_door_move"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"0.700000"
//	"pitch"			"PITCH_NORM"
//
//	"soundlevel"	"SNDLVL_NORM"
//
//	"wave"			"doors/door_metal_gate_move1.wav"
//}

"boxcar_door_stop1"
{
	"channel"		"CHAN_STATIC"
	"volume"		"0.500000"
	"pitch"			"PITCH_NORM"

	"soundlevel"	"SNDLVL_NORM"

	"wave"			"doors/door_metal_thin_open1.wav"
}

"boxcar_door_stop2"
{
	"channel"		"CHAN_STATIC"
	"volume"		"0.900000"
	"pitch"			"PITCH_NORM"

	"soundlevel"	"SNDLVL_NORM"

	"wave"			"doors/door_metal_thin_close2.wav"
}

//"siren01"
//{
//	"channel"		"CHAN_BODY"
//	"volume"		"1.000000"
//	"pitch"			"100"
//
//	"soundlevel"	"SNDLVL_140dB"
//
//	"wave"			"ambient/alarms/apc_alarm_loop1.wav"
//}

"heli_pass"
{
	"channel"		"CHAN_BODY"
	"volume"		"0.600000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_90dB"

	"wave"			"ambient/machines/heli_pass_quick1.wav"
}
	
//"body_fall_1"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"0.600000"
//	"pitch"			"PITCH_NORM"
//
//	"soundlevel"	"SNDLVL_70dB"
//
//	"wave"			"physics/body/body_medium_impact_hard1.wav"
//}

//"dam_water"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"0.60000"
//	"pitch"			"PITCH_NORM"
//
//	"soundlevel"	"SNDLVL_90dB"
//
//	"wave"			"ambient/levels/generic/dam_water_loop2.wav"
//}

"substation_generators"
{
	"channel"		"CHAN_VOICE"
	"volume"		"0.400000"
	"pitch"			"PITCH_NORM"

	"soundlevel"	"SNDLVL_80dB"

	"wave"			"ambient/atmosphere/indoor2.wav"
}

//"radio_dead"
//{
//	"channel"		"CHAN_STATIC"
//	"volume"		"0.250000"
//	"pitch"			"PITCH_NORM"
//
//	"soundlevel"	"SNDLVL_75dB"
//
//	"wave"			"hl1/ambience/deadsignal2.wav"
//}

"drivein_movie"
{
	"channel"		"CHAN_STATIC"
	"volume"		"1.0"
	"pitch"			"PITCH_NORM"

	"soundlevel"	"SNDLVL_120dB"

	// "wave"			"ambient/levels/trailerpark/lobby.wav"
	"wave"                 "common/null.wav"

}


// Whack-A-Mole!

"WAM.HighScore"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_80dB"
	"volume"		"1.0"
	"wave"		"level/highScore.wav"
}

"WAM.StartUp"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_65dB"
	"volume"		"1.0"
	"wave"		"level/startWAM.wav"
}


"WAM.CountDown"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"0.7"
	"wave"		"level/countDown.wav"
}

"WAM.LowScore"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"1.0"
	"wave"		"level/lowScore.wav"
}

"WAM.PointScored"
{
	"channel"		"CHAN_STATIC"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"1.0"
	"wave"		"level/pointScored.wav"
}

"WAM.popUp"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"1.0"
	"wave"		"level/popUp.wav"
}

"WAM.TimerBell"
{
	"channel"		"CHAN_STATIC"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"0.5"
	"wave"		"level/timer_bell.wav"
}

"WAM.Music"
{
	"channel"		"CHAN_AUTO"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"1.0"
	"wave"		"*music/WAM_music.mp3"
}

"WAM.GameOver"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_90dB"
	"volume"		"1.0"
	"wave"		"*level/loud/WAMover.wav"
}

"WAM.Attract"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_80dB"
	"volume"		"1.0"
	"pitch"			"110, 120"
	"rndwave"
	{
		"wave"			"npc\Moustachio\WHACKPOPUP01.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP02.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP09.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP13.WAV"
	}
}


// Strongman!

"Strongman.ImpactAdrenaline"
{
	"channel"		"CHAN_AUTO"
	"soundlevel"		"SNDLVL_90dB"
	"volume"		"1.0"
	"wave"		"level/loud/adrenaline_impact.wav"
}

"Strongman.Bell"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_100dB"
	"volume"		"1.0"
	"wave"		"level/bell_normal.wav"
}

"Strongman.BellBreakawy"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_100dB"
	"volume"		"1.0"
	"wave"		"level/loud/bell_break.wav"
}

"Strongman.BellImpact"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_100dB"
	"volume"		"1.0"
	"pitch"			"95, 105"
	"wave"		"level/bell_impact.wav"
}

"Strongman.PuckSlide_up"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"0.7"
	"pitch"			"95, 105"
	"wave"		"level/puck_slide_up.wav"
}

"Strongman.PuckSlide_down"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"0.7"
	"pitch"			"95, 105"
	"wave"		"level/puck_slide_down.wav"
}

"Strongman.PuckImpact"
{
 	"channel"     "CHAN_ITEM"
	"soundlevel"  "SNDLVL_90dB"
	"volume"      "0.8, 1.0"
	"pitch"				"95, 105"
	"wave"                 "level/puck_impact.wav"
}

"Strongman.puck_fail"
{
	"channel"	"CHAN_ITEM"
	"volume"	"0.7"
	"soundlevel"  "SNDLVL_75dB"
	"pitch"		"100"
	"wave"	"level/puck_fail.wav"
}

"Strongman.puck_tick"
{
	"channel"	"CHAN_ITEM"
	"volume"	"0.5, 0.6"
	"soundlevel"  "SNDLVL_75dB"
	"pitch"		"95, 105"
	"wave"	"buttons/button22.wav"
}

"Strongman.LightsOn"
{
	"channel"	"CHAN_ITEM"
	"volume"	"1.0"
	"soundlevel"  "SNDLVL_80dB"
	"pitch"		"95, 105"
	"wave"	"level/light_on.wav"
}


// Shooting Gallery!

"Gallery.StartLoop"
{
	"channel"		"CHAN_STATIC"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"1.0"
	"wave"		")level/start_and_loop.wav"
}

"Gallery.Stop" //this event must stop the looping soundevent above
{
	"channel"		"CHAN_STATIC"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"1.0"
	"wave"		")level/gallery_stop.wav"
}

"Gallery.Music"
{
	"channel"		"CHAN_AUTO"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"1.0"
	"wave"		"*)music/gallery_music.mp3"
}

"Gallery.GnomeFTW"
{
	"channel"		"CHAN_AUTO"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"1.0"
	"wave"		"level/gnomeFTW.wav"
}

"Gallery.PointScored"
{
	"channel"		"CHAN_STATIC"
	"soundlevel"		"SNDLVL_85dB"
	"volume"		"1.0"
	"wave"		"level/scoreRegular.wav"
}

"Gallery.PointScored100"
{
	"channel"		"CHAN_STATIC"
	"soundlevel"		"SNDLVL_85dB"
	"volume"		"1.0"
	"pitch"			"125"
	"wave"		"level/scoreRegular.wav"
}

"Gallery.Win"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"0.6"
	"wave"		"level/loud/gallery_win.wav"
}

"Gallery.Climber"
{
	"channel"		"CHAN_ITEM"
	"soundlevel"		"SNDLVL_NORM"
	"volume"		"0.5"
	"wave"		"level/loud/climber.wav"
}

//
"Gallery.Moustachio"
{
	"channel"		"CHAN_VOICE"
	"volume"		"1.0"
	"pitch"			"100"
	"soundlevel"		"SNDLVL_NORM"
	"rndwave"
	{
		"wave"			"npc\Moustachio\WHACKPOPUP01.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP02.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP03.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP04.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP05.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP06.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP07.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP08.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP09.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP10.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP11.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP12.WAV"
		"wave"			"npc\Moustachio\WHACKPOPUP13.WAV"
	}
}

//
"Gallery.Moustachio_hit"
{
	"channel"		"CHAN_VOICE"
	"volume"		"1.0"
	"pitch"			"100"
	"soundlevel"		"SNDLVL_85dB"
	"rndwave"
	{
		"wave"			"npc\Moustachio\WHACKSMASH01.WAV"
		"wave"			"npc\Moustachio\WHACKSMASH02.WAV"
		"wave"			"npc\Moustachio\WHACKSMASH03.WAV"
		"wave"			"npc\Moustachio\WHACKSMASH04.WAV"
		"wave"			"npc\Moustachio\WHACKSMASH05.WAV"
		"wave"			"npc\Moustachio\WHACKSMASH06.WAV"
		"wave"			"npc\Moustachio\WHACKSMASH07.WAV"
		"wave"			"npc\Moustachio\WHACKSMASH08.WAV"
		"wave"			"npc\Moustachio\WHACKSMASH09.WAV"
	}
}


//------------------------------------------
//  Roller Coaster sounds
//------------------------------------------

"Coaster.Loop"
{
	"channel"		"CHAN_STATIC"
	"soundlevel"		"SNDLVL_90dB"
	"volume"		"1.0"
	"pitch"			"95, 100"
	"wave"		")level/coaster_loop01.wav"
}

"Coaster.Loop2"
{
	"channel"		"CHAN_STATIC"
	"soundlevel"		"SNDLVL_90dB"
	"volume"		"1.0"
	"pitch"			"95, 100"
	"wave"		")level/coaster_loop02.wav"
}

"Coaster.Loop3"
{
	"channel"		"CHAN_STATIC"
	"soundlevel"		"SNDLVL_85dB"
	"volume"		"1.0"
	"pitch"			"95, 100"
	"wave"		")level/coaster_loop03.wav"
}

"Coaster.DownShort" 
{
	"channel"		"CHAN_AUTO"
	"soundlevel"		"SNDLVL_100dB"
	"volume"		"1.0"
	"wave"		")level/loud/downhill01.wav"
}

"Coaster.DownLong"
{
	"channel"		"CHAN_AUTO"
	"soundlevel"		"SNDLVL_100dB"
	"volume"		"1.0"
	"wave"		")level/loud/downhill02.wav"
}

"Coaster.Climb_Loop"
{
	"channel"                            "CHAN_ITEM"
	"soundlevel"                      "SNDLVL_100dB"
	"volume"                             "1.0"
	"wave"                 ")level/loud/climb_loop.wav"
}

"Coaster.Climb_End"
{
	"channel"                            "CHAN_ITEM"
	"soundlevel"                      "SNDLVL_100dB"
	"volume"                             "1.0"
	"wave"                 ")level/loud/climb_end.wav"
}


"Coaster.Stop"
{
	"channel"                            "CHAN_ITEM"
	"soundlevel"                      "SNDLVL_110dB"
	"volume"                             "1.0"
	"wave"                 ")level/loud/coaster_stop.wav"
}

"Coaster.Crash"
{
	"channel"                            "CHAN_ITEM"
	"soundlevel"                      "SNDLVL_120dB"
	"volume"                             "0.0"
	"wave"                 "common/null.wav"
}

//------------------------------------------
//  SCAVENGE
//------------------------------------------
"scavenge.generator_on_loop"
{
	"channel"		"CHAN_STATIC"
	"volume"		"1.000000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_85dB"

	"wave"			"level/generator_start_loop.wav"
}

"scavenge.generator_sputter_loop"
{
	"channel"		"CHAN_STATIC"
	"volume"		"1.000000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_85dB"

	"wave"			"level/generator_sputter.wav"
}

"scavenge.generator_turnoff"
{
	"channel"		"CHAN_STATIC"
	"volume"		"1.000000"
	"pitch"			"100"

	"soundlevel"	"SNDLVL_85dB"

	"wave"			"level/generator_stop.wav"
}

//------------------------------------------
//  Jukebox sounds
//------------------------------------------
"Jukebox.NeedleScratch"
{
	"channel"		"CHAN_ITEM"
	"volume"		"1.0"
	"soundlevel"	"SNDLVL_85dB"
	"wave"			"level/record_changer.wav"
}
"Jukebox.RecordStart"
{
	"channel"		"CHAN_STATIC"
	"volume"		"0.0"
	"soundlevel"	"SNDLVL_85dB"
	"wave"			"common/null.wav"
}
