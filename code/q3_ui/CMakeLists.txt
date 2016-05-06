cmake_minimum_required (VERSION 2.6.0)
project (Quake3_UI)

set (UI_SOURCES
  ui_main.c
  ../game/bg_misc.c
  ../game/q_math.c
  ../game/q_shared.c
  ui_addbots.c
  ui_atoms.c
  ui_cdkey.c
  ui_cinematics.c
  ui_confirm.c
  ui_connect.c
  ui_controls2.c
  ui_credits.c
  ui_demo2.c
  ui_display.c
  ui_gameinfo.c
  ui_ingame.c
  ui_menu.c
  ui_mfield.c
  ui_mods.c
  ui_network.c
  ui_options.c
  ui_playermodel.c
  ui_players.c
  ui_playersettings.c
  ui_preferences.c
  ui_qmenu.c
  ui_removebots.c
  ui_serverinfo.c
  ui_servers2.c
  ui_setup.c
  ui_sound.c
  ui_sparena.c
  ui_specifyserver.c
  ui_splevel.c
  ui_sppostgame.c
  ui_spskill.c
  ui_startserver.c
  ui_team.c
  ui_teamorders.c
  ui_video.c
  ../ui/ui_syscalls.c
)

add_library (ui SHARED ${UI_SOURCES})
