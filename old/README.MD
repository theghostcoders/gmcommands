===
/clone_monster <id> <unit> <dropid>: Clone Monster At Player around,
clone_monster <number> <number> <number>,
cm <number> <number> <number>,
===
/restore: restore the hp ,mp to the max,
restore,
===
/set_rb mob <n> <id> <seconds>: reborn mober binding,
set_rb <number> <number> <number>,
sr <number> <number> <number>,
===
/ls_rb: list reborn mober binding,
ls_rb,
lr,
===
/rm_rb mob: remove reborn mober binding,

rm_rb <number>:,
rr <number>,
===
/status: query the player's status,
status,
===
/clone item <item_id>: clone an item which template id is <item_id>,
clone_item <number>,
ci <number>,
===
/clone reward item <item_id> <item_num>: clone an item which template id is <item_id>,
clone_reward_item <number> <number>,
clri <number> <number>,
===
/clone items <item_id> <item_num>: clone an item which template id is <item_id> and item quantity is <item_num>,

clone_items <number> <number>:,
cls <number> <number>,
===
/clone items <item_id> <item_num>: clone an item which template id is <item_id> and item quantity is <item_num>,

clone_items <number> <number>:,
clone_stack_item <number> <number>,
===
/clone_item_to <item_id> <to_loc>: clone an item which template id is <item_id> and put into inventory at location <to_loc>,

clone_item_to <number> <number>:,
clt <number> <number>,
===
/say <message>: say something,
say <rest_input>,
s <rest_input>,
===
/whisper <name> <message>: whisper someone something,

whisper <word> <rest_input>,
w <word> <rest_input>,
===
/kill <monster_id>: monster! DIE!,
kill <number>,
k <number>,
===
/gain_exp <number>: gain exp num,
gain_exp <number>,
===
/mission_gain_exp <number>: gain exp num,
mge <number>,
===
/gain_gold <number>: gain gold num,
gain_gold <number>,
gg <number>,
===
/goto <x> <y>: goto x y,
goto <number> <number>,
===
/users: list the node users info,
users,
===
/allusers: list whole world users,
allusers,
===
/transfer <id>:,
transfer <number>,
===
/listarea: list the areas in the currently node,
listarea,
lsa,
===
/weak <player_id>: let target player weak,
===
/setra <node_id> <area_id>: set revive area,
setra <number> <number>,
sra <number> <number>,
===
/transport_area <node_id> <area_id>: transport to area,
transport_area <number> <number>,
tpa <number> <number>,
===
/transport_node <node_id>: transport to node,
transport_node <number>,
tpn <number>,
===
/drop_item <item_id> <number> <flag>: drop item,
drop_item <number> <number> <rest_input>,
===
/list_durability <container_id>: list durability status,equipment 0  inventory 1,
list_durability <number>,
ld <number>,
===
/shop <shop_type> <npc_template_id> <shop_id>: enter shop,
shop <word> <number> <number>,
===
/shop <shop_type> <npc_id>: enter spell shop,
shop <word> <number>,
===
/effect_life <life_id> <effect_id> <duration> <factor> <isteam>:,
effect_life <number> <number> <number> <number> <number>,
elf <number> <number> <number> <number> <number>,
===
/effect_loc <x> <y> <effect_id> <duration> <factor>:,
effect_loc <number> <number> <number> <number> <number>,
eloc <number> <number> <number> <number> <number>,
===
/repairshop: enter repair shtop,
repairshop,
===
/invincible <0/1>: invincible mode 0 - off, 1 - on,
invincible <number>,
inv <number>,
===
/vanish <0/1>: invisible mode 0 - off, 1 - on,
vanish <number>,
van <number>,
===
/town: transport to town,
===
/transport_to_character <given_name>: transport to character with nickname,
transport_to_character <word>,
tpc <word>,
===
/get_user_info <given_name>: findout about an nickname,
get_user_info <word>,
gui <word>,
===
/get_shortcuts: list shortcuts,
get_shortcuts,
===
/update_shortcut <page> <slot> <value>: modify shortcuts (page and slot starts from 0),
update_shortcut <number> <number> <number>,
us <number> <number> <number>,
===
/save_shortcut: save shortcuts,
save_shortcut,
===
/display_sum_node_users <0/1>:,
display_sum_node_users <number>,
dnu <number>,
===
/display_sum_world_users <0/1>: list whole world users mode 0 - off, 1 - on,
display_sum_world_users <number>,
dwu <number>,
===
/get_spellmaster <spellmaster_id>: get a spellmaster,
get_spellmaster <number>,
===
/debug <0/1>: debug mode 0 - off, 1 - on,
debug <number>,
===
/list_state: list my states,
list_state,
===
/shut_down <minutes>: shut down in x minutes,
shut_down <number>,
===
/kick <nick_name>: kick out character with name,
kick <word>,
===
/slayer <0/1>: slayer mode 0 - off, 1 - on,
slayer <number>,
===
/announce <message>: announce something,
announce <rest_input>,
gm <rest_input>,
===
/storage <npc_id> <0/1>: enter storage 0 - Deposit, 1 - Withdraw,
storage <number> <number>,
===
/querychar <charname>:,
querychar <word>,
qc <word>,
===

/listenchant <charname>:,

listenchant <word>:,
le <word>,
===
/version:,
===
/transport_and_deduct <area_id> <money>: transport to area and deduct money,
transport_and_deduct <number> <number>,
tam <number> <number>,
===
/query_npc <node_id> <npc_id>: query npc <number> to show on map,
query_npc <number>,
qn <number>,
===
/party <message>: say something in party channel,
party <rest_input>,
p <rest_input>,
===
/party <message>: say something in party channel,
party_2 <rest_input>,
===
/guild <message>: say something in guild channel,
guild <rest_input>,
g <rest_input>,
===
/guild <message>: say something in guild channel,
guild_3 <rest_input>,
===
/trade <message>: say something in trade channel,
trade <rest_input>,
t <rest_input>,
===
/trade <message>: say something in trade channel,
trade_4 <rest_input>,
===
/chat <message>: say somehting in chat channel,
c <rest_input>,
===
/chat <message>: say somehting in chat channel,
chat_5 <rest_input>,
===
/system <message>: announce something from system,
system <rest_input>,
===
/channel_limit <id> <minute>: channel usage limitation,
channel_limit <number> <number>,
cl <number> <number>,
===
/flush_dba_data: Flush player DBAgent Data,
flush_dba_data,
===
/banchar <char_id> <minute>: ban character,
banchar <number> <number>,
bc <number> <number>,
===
/identify_shop: enter identify shop,
identify_shop,
id_shop,
===
/disband_family:,
===
/select_family_leader <new_leader>:,
select_family_leader <word>,
sfl <word>,
===
/listfms <ch_id> <mission_id>: list fms info on this character,
listfms <number> <number>,
lsf <number> <number>,
===
/run <number>: Faster Walk,
run <number>,
===
/drop stack item <item_id> <amount>: drop item by amount,
drop_items <number> <number>,
drop_stack_item <number> <number>,
===
/allworld_cmd <rest_input>: all world text command,
allworld_cmd <rest_input>,
aw <rest_input>,
===
/query_npc_involve <npc_id>: query npc <number> to list how many missionlist involved,
query_npc_involve <number>,
qni <number>,
===
/channel_limit_name <charname> <minute>: channel usage limitation,
channel_limit_name <word> <number>,
cln <word> <number>,
===
/banchar_name <char_name> <minute>: ban character,
banchar_name <word> <number>,
bcn <word> <number>,
===
/quest <message>: say somehting in quest channel,
quest <rest_input>,
q <rest_input>,
===
/quest <message>: say somehting in quest channel,
quest_6 <rest_input>,
===
/reset_attribute: reset attribute point,
reset_attribute,
ra,
===
/reset_skill: reset skill point,
reset_skill,
===
/reset_attribute_gold <how_much>: reset attribute point for gold,
reset_attribute_gold <number>,
rag <number>,
===
/reset_skill_gold <how_much>: reset skill point for gold,
reset_skill_gold <number>,
rsg <number>,
===
/get_spell <spell_id>: get a spell,
get_spell <number>,
===
/inlay_shop <npc_id>: enter inlay shop,
inlay_shop <number>,
in_shop <number>,
===
/broadcast_system_message <msg_id> <times> <interval> <msg>:,
broadcast_system_message <number> <number> <number> <rest_input>,
bsm <number> <number> <number> <rest_input>,
===
/echo <message>: show message without prompt,
echo <rest_input>,
===
/clone_monster_locate <mob_id> <absolute> <loc_x> <loc_y>: clone monster in absolute/relate coordinate in same node with player,
clone_monster_locate <number> <number> <number> <number>,
cml <number> <number> <number> <number>,
===
/clone_monster_around <mob_id> <absolute> <angle> <range>: clone monster around player by absolute/relate angle,
clone_monster_around <number> <number> <number> <number>,
cma <number> <number> <number> <number>,
===
/npc_use_channel <npc_id> <channel_id> <type> <message>: let npc use channel to say something,
npc_use_channel <number> <number> <number> <rest_input>,
nuc <number> <number> <number> <rest_input>,
===
/npc_use_spell <npc_id> <spell_id>: let npc use spell on pc in the same node,
npc_use_spell <number> <number>,
nus <number> <number>,
===
/self_use_effect <effect_id> <duration>: let pc use effect on self,
self_use_effect <number> <number>,
sue <number> <number>,
===
/change_class <class_id>: change current class,
change_class <number>,
cc <number>,
===
/adjust_spell_anitime <spell_id> <animeTime_ofs>: change spell animation time,
adjust_spell_anitime <number> <number>,
asa <number> <number>,
===
/escape: transfer team member to the last enter normal area,
escape,
===
/set_level <level>: set character level,,
set_level <number>,
sl <number>,
===
/set_monster_damage <monster id> <physico damage> <attack var> <physico defence> <magic damage> <magic attack var> <magic defence>: set monster damage,,
set_monster_damage <number> <number> <number> <number> <number> <number> <number>,
smd <number> <number> <number> <number> <number> <number> <number>,
===
/set_monster_movement <monster id> <movement> <roammovement> <attack delay>: set monster ,
set_monster_movement <number> <number> <number> <number>,
smm <number> <number> <number> <number>,
===
/show_monster <template monster id> : show monster information,
show_monster <number>,
sm <number>,
===
/set_monster_sight <monster id> <sight>: set monster sight,
set_monster_sight <number> <number>,
sms <number> <number>,
===
/test_character_attack <monster id>: test character ,
test_character_attack <number> <number>,
tca <number> <number>,
===
/test_monster_attack <monster id>: test monster ,
test_monster_attack <number> <number>,
tma <number> <number>,
===
/set_sevel_grow <con> <str> <int> <dex> <vol> <max_hp> <max_mp>: set attr ,
set_level_grow <number> <number> <number> <number> <number> <number> <number>,
===
/querylevelgrow :,
query_level_grow,
===
/set_item <item id> <word> <number>:,
set_item <number> <word> <number>,
===
/save_monster <template monster id>: save monster to db,
save_monster <number>,
===
/get_effect_data <effect id>: get effect data,
get_effect_data <number>,
ged <number>,
===
/set_effect_data <effect id> <family type> <target type> <duration> <period> <width> <height> <enchant type> <resist type> <param min> <param max> <next id> <level>: set effect data,
set_effect_data <number> <word> <word> <number> <number> <number> <number> <word> <word> <number> <number> <number> <number>,
sed <number> <word> <word> <number> <number> <number> <number> <word> <word> <number> <number> <number> <number>,
===
/set_effect_command <effect id> <command type> <commands>: set effect command,
set_effect_command <number> <word> <rest_input>,
sec <number> <word> <rest_input>,
===
/get_spell_data <spell id>: get spell data,
get_spell_data <number>,
gsd <number>,
===
/set_reborn_monster <handle> <x> <y> <monster_temp_id> <amount> <seconds> <width> <height> <patrol_id>: reborn mober binding,
set_reborn_monster <number> <word> <word> <number> <number> <number> <word> <word> <number>,
srm <number> <word> <word> <number> <number> <number> <word> <word> <number>,
===
/get_all_template_monsters: get all template monster,
get_all_template_monsters,
gatm,
===
/monster_goto <monster id> <x> <y>: goto x y,
monster_goto <number> <number> <number>,
wm <number> <number> <number>,
===
/around_kill_all <radius>: around kill all,
around_kill_all <number>,
aka <number>,
===
/around_kill <monster id> <radius>: around kill ,
around_kill <number> <number>,
ak <number> <number>,
===
/query_test_attack_monster: query test attack monster ,
query_test_attack_monster,
qtam,
===
/reload_reborn_monster <node id>: reload reborn monster,
reload_reborn_monster <number>,
rrm <number>,
===
/list_pms <pms_id>: list pms info on this character,
listpms <number>,
===
/echobyid <greeting_id>: show message without prompt by greeting_id,
echobyid <number>,
===
/change_hair_color <color_id>: change character hair color,
change_hair_color <number>,
chc <number>,
===
/change_hair <hair_id>: change character hair,
change_hair <number>,
ch <number>,
===
/reload_effect: reload effect data,
reload_effect,
===
/reload_template_monster: reload template_monster data,
reload_template_monster,
===
/summon_pet <template_id>: summon pet,
summon_pet <number>,
===
/gain_skill_point <number>: gain skill point,
gain_skill_point <number>,
gsp <number>,
===
/node <message>: say to all man in node,
node <rest_input>,
n <rest_input>,
===
/system_area <area_id> <message>: announce something from system,
system_area <word> <rest_input>,
sysarea <word> <rest_input>,
===
/fatality_damage <LiftEntity_id>: set LiftEntity HP = MP = 1,
fatality_damage <number>,
fd <number>,
===
/restore_all: restore the hp ,mp to the max on players around caster,
restore_all,
===
/clear_near_items: clear near items around caster,
clear_near_items,
===
/get_server_id: get zoneserver id,
get_server_id,
===
/test_durability <mob id> <loc> <durability>: test durability decrease in attacked,
test_durability <number> <number> <number>,
td <number> <number> <number>,
===
/test_spell_attack <monster id> <spell id> <spell lv> <number>: test character ,
test_spell_attack <number> <number> <number> <number>,
tsa <number> <number> <number>,
===
/test_drop_treasure <monster id> <number>: test drop treasure ,
test_drop_treasure <number> <number>,
tdt <number> <number>,
===
/test_pk <monster id>: test pk ,
test_pk <number> <number>,
tpk <number> <number>,
===
/surprise_box <SurpriseBoxID>: invoke surprise box,
surprise_box <number>,
sb <number>,
===
/SetExtBornMonster <num> <time sec>: extern born monster,
setextbornmonster <number> <number>,
sebm <number> <number>,
===
/set_family_level <fm_level>: set family level,
set_family_level <number>,
sflv <number>,
===
/family_level_up: family level up,
family_level_up,
===
/set_family_emblem <emblem1> <emblem2>: set family emblem,
set_family_emblem <number> <number>,
sfe <number> <number>,
===
/select_family_emblem: select family emblem,
select_family_emblem,
===
/open_exploit_rank: Open Exploit Rank,
===
/reload_formula_params: reload formula parameters,
reload_formula_params,
===
/reload_grow_table: reload grow table,
reload_grow_table,
===
/give_exploit <exploit amount>,
give_exploit <number>,
===
/RepairAllEquipment: RepairAllEquipment,
repairallequipment,
===
/trace <receive_id> <target_name>: Trace a character by name,
trace <number> <word>,
===
/drill_item <slot> <number>: DrillItem,
drill_item <number> <number>,
===
/fubag <id>: fortune bag item,
fubag <number>,
===
/aw_put_treasure <id> <amount>: put treasure all world,
aw_put_treasure <number> <number>,
awpt <number> <number>,
===
/setfms <ch_id> <mission_id> <value>: set fms value on this character,
setfms <number> <number> <number>,
setf <number> <number> <number>,
===
/clone_quest_treasure <item_id> <number> <node_id> <x> <y> <template_id>: drop quest item,
clone_quest_treasure <number> <number> <number> <number> <number> <number>,
===
/set_bag_time <index> <time>: set the due date for bags,
set_bag_time <number> <number>,
sbt <number> <number>,
===
/gain_family_exp <number>: gain family exp,
gain_family_exp <number>,
gfe <number>,
===
/set_prestige_level <prestige_id> <level>: set prestige level,
set_prestige_level <number> <number>,
spl <number> <number>,
===
/gain_prestige_exp <prestige_id> <exp>: gain prestige exp,
gain_prestige_exp <number> <number>,
gpe <number> <number>,
===
/cast_spell <number> <number>: cast spell to life,
cast_spell <number> <number>,
cs <number> <number>,
===
/set_sys_var <word> <number>: set system varaible,
set_sys_var <word> <number>,
ssv <word> <number>,
===
/add_appellation <appellation_id>: add appellation,
add_appellation <number>,
aa <number>,
===
/set_present_appellation <appellation_id>: set present appellation,
set_present_appellation <number>,
spa <number>,
===
add_elf <number>:, 
ae <number>,
===
/remove_elf <elf_loc>: remove elf,
remove_elf <number>,
===
elf_skill <add 1/remove 0> <elf_loc> <skill_id>: elf skill,
elf_skill <number> <number> <number>,
===
set_elf_level <elf_loc> <level>: set first elf level,
set_elf_level <number> <number>,
sel <number> <number>,
===
set_elf_mood <elf_loc> <mood>: set elf mood,
set_elf_mood <number> <number>,
sem <number> <number>,
===
use_item_to <inv/equ> <container_index> <loc> <target_id> <param>: use item to,
use_item_to <word> <number> <number> <number> <rest_input>,
uit <word> <number> <number> <number> <rest_input>,
===
set_spell_card <index> <item_number>:,
set_spell_card <number> <number>,
ssc <number> <number>,
===
gain_elf_exp <elf_loc> <exp>: gain elf exp,
gain_elf_exp <number> <number>,
gee <number> <number>,
===
gain_elf_familiar <elf_loc> <familiar>: gain elf familiar,
gain_elf_familiar <number> <number>,
gef <number> <number>,
===
show_debug_message <0/1>: show debug message,
show_debug_message <number>,
sdm <number>,
===
set_log_level <server> <level>: set server(m/w/z/all) log level,
set_log_level <word> <number>,
slog <word> <number>,
===
set_assert <server> <0/1>: set server(m/w/z/all) assert: 0 - off, 1 - on,
set_assert <word> <number>,
===
set_spell_card_attr <value> <value> <value> <value>: set spell card attr ,
set_spell_card_attr <number> <number> <number> <number>,
===
set_elf_action <loc> <animation_id>: set elf action ,
set_elf_action <number> <number> ,
sea <number> <number>,
===
inside <class>: test some information,
inside <number>,
===
auction_sell <item_id> <amount>: auction sell ,
auction_sell <number> <number>,
as <number> <number>,
===
friend_together: player add frined,
friend_together,
===
reload_itemmall_db: reload itemmall db,
reload_itemmall_db,
===
set_node_exp: set node exp rate,
set_node_exp <number> <number>,
sne <number> <number>,
===
set_node_gold: set node gold rate,
set_node_gold <number> <number>,
sng <number> <number>,
===
set_node_drop: set node drop rate,
set_node_drop <number> <number>,
snd <number> <number>,
===
show_hate: Show Character All Hate,
show_hate <number>,
===
/clone item <item_id> <combo_id>: clone an item which template id is <item_id> and combo id is <combo_id>,
clone_item <number> <number>,
ci <number> <number>,
===
/clone item <item_id> <combo_id> <socket_amount>: clone an item which template id is <item_id> and combo id is <combo_id>, socket amount <socket_amount>,
clone_item <number> <number> <number>,
ci <number> <number> <number>,
===
/return item <receiver_id> <log>: use mail return an item to player from log,
return_item <number> <rest_input>,
ri <number> <rest_input>,
===
/call elf <loc>: call elf which loc is <loc>,
call_elf <number>,
===
/return gold <receiver_id> <gold>: use mail return gold to player,
return_gold <number> <number>,
rg <number> <number>,
===
fight switch <0/1> <fight_tid> <seconds>: 0 - off, 1 - on,
fight_switch <number> <number> <number>,
fs <number> <number> <number>,
===
/clone_npc <npc_id>: clone npc,
clone_npc <number>,
cn <number>,
===
/around_kill_all_player <radius>: around kill all player,
around_kill_all_player <number>,
akap <number>,
===
/captcha_id <id> <type>: captcha_id <id> <type>,
captcha_id <number> <number>,
capid <number> <number>,
===
/captcha_name <given_word> <type>: captcha_name <given_name> <type>,
captcha_name <word> <number>,
capname <word> <number>,
===
/change_grow_type <growid>: change_grow_type <growid>,
change_grow_type <number>,
cgt <number>,
===
/clear_bag_item: clear bag item,
===
/set_statue <node> <id> <action> <key>: set statue,
set_statue <number> <number> <number> <number>,
sst <number> <number> <number> <number>,
===
/bf_ch_num <bf_type> <level_type> <number>: bf_ch_num,
bf_ch_num <number> <number> <number>,
===
/bf_open <open> <bf_today_type>: bf_open,
bf_open <number> <number>,
===
/gain_love_coin <coin>: gain_love_coin,
gain_love_coin <number>,
glc <number>,
===
/remove_enchant <id> <isteam>: remove enchant,
remove_enchant <number> <number>,
===
/visit_family_instance <family_name>: visit_family_instance,
visit_family_instance <word>,
vfi <word>,
===
/gain_building_exp <loc> <exp>: gain_building_exp,
gain_building_exp <number> <number>,
gbe <number> <number>,
===
/gain_family_treasury <money>: gain family treasury,
gain_family_treasury <number>,
gft <number>,
===
/gain_building_durability <loc> <durability>: gain building durability,
gain_building_durability <number> <number>,
gbd <number> <number>,
===
/achievement_item <achievement_id>: achievement_item,
achievement_item <number>,
===
/create_town <node_id>: create_town,
create_town <number>,
===
/set_territory_open <territory_tid> <duration>: set_territory_open,
set_territory_open <number> <number>,
===
/clone item <item_id> <combo_id> <socket_amount> <color>: clone an item which template id is <item_id> and combo id is <combo_id>, socket amount <socket_amount>, color <color>,
clone_item <number> <number> <number> <number>,
ci <number> <number> <number> <number>,
===
/screenmsg <type> <msg>: show screenmsg,
screenmsg <number> <rest_input>,
===
/set_blocklogin <char_id> <flag_id>: set block login value,
set_blocklogin <number> <number>,
sbl <number> <number>,
===
/set_useblocklogin <flag_id>: set use block login value,
set_useblocklogin <number>,
subl <number>,
===
/visit_player_room_id <room_id>: visit player room_id,
visit_player_room_id <number>,
vpri <number>,
===
/visit_player_room <ch_name>: visit player room,
visit_player_room <word>,
vpr <word>,
===
/switch_player_room <0/1>: switch player room 0 - off, 1 - on,
switch_player_room <number>,
spr <number>,
===
/switch_room_decorating <room_id> <0/1>: switch room decorating mode  0 - off, 1 - on,
switch_room_decorating <number> <number>,
sprd <number> <number>,
===
/set_territory_status <number> <number>: set territory status,
set_territory_status <number> <number>,
===
/captcha_level <level>: captcha_level <level>,
captcha_level <number>,
caplv <number>,
===
/set_gm_map_open <node_id> <open>: set gm map open,
set_gm_map_open <number> <number>,
sgmmo <number> <number>,
===
/send_reward_item <number> <number> <number> <number> <number>: send_reward_item,
send_reward_item <number> <number> <number> <number> <number>,
sri <number> <number> <number> <number> <number>,
===
/set_achievement <achi_id> <point> <isteam>:,
set_achievement <number> <number> <number>,
===
/gain_cs_gold <gold>:,
gain_cs_gold <number>,
gcg <number>,
===
/send_sys_mall_queue <number>:,
send_sys_mail_queue <number>,
ssmq <number>,
===
/set_territory_player_limit <territroy_id> <player_limit>:,
set_territory_player_limit <number> <number>,
stpl <number> <number>,
===
/set_web_btn <number>:,
swb <number>,
===
/recover_territory_event <number>:,
recover_territory_event <number>,
rte <number>,
===
/family_battle_restart:,
===
/family_battle_setup_judge <phase_type> <phase_index> <family_name>:,
family_battle_setup_judge <number> <number> <word>,
fbsj <number> <number> <word>,
===
/family_battle_honor_switch <onoff>:,
family_battle_honor_switch <number>,
fbhs <number>,
===
/family_battle_end:,
===
/refresh_recommended_events <number>: refresh_recommended_events,
refresh_recommended_events <number>,
rre <number>,
===
/family_battle_reset_week_update:,
family_battle_reset_week_update,
fbrwu,
===
/gain_family_honor <number>:,
gfh <number>,
===
/cross_world <number>:,
cw <number>,
===
/countdown_msg <start_tim> <time_seconds> <msg>: Countdown Msg,
countdown_msg <number> <number> <rest_input>,
cdm <number> <number> <rest_input>,
===
/show_countdown_msg: Show Countdown Msg,
show_countdown_msg,
show_cdm,
===
/del_countdown_msg: Delete Countdown Msg,
del_countdown_msg,
del_cdm,
===
/show_countdown_msg <number>: Show Countdown Msg,
show_countdown_msg <number>,
show_cdm <number>,
===
/disband_family <name>:,
disband_family <word>,
df <word>,
===
transport_to_npc <value>: transport to npc ,
transport_to_npc <number>,
tpnpc <number>,
===
/reload_function_switch: reload function switch ini,
reload_function_switch,
===
/jail <given_name> <buff_id> <buff_time> <node_id> <gateway_id>: jail character,
jail <word> <number> <number> <number> <number>,
===
set_elf_star <elf_loc> <star>: set elf mix star,
set_elf_star <number> <number>,
ses <number> <number>,
===
/change_gender <gender_id>: change character gender,
change_gender <number>,
===
/trans_into_territory <territory_id> <area_id>: trans_into_territory,
trans_into_territory <number> <number>,
tit <number> <number>,
===
/effect_map <effect_id> <duration>:,
effect_map <number> <number>,
emap <number> <number>,
===
/effect_map_time <map_id> <time> <effect_id>:,
effect_map_time <number> <number> <number>,
emtime <number> <number> <number>,
===
/clone_monster_remote <id> <unit> <world_id> <node_id> <x> <y>: Clone Monster At Player around,
clone_monster_remote <number> <number> <number> <number> <number> <number>,
cmr <number> <number> <number> <number> <number> <number>,
===
/set_territory_prepare_time <prepare_time>: set_territory_prepare_time,
set_territory_prepare_time <number>,
stpt <number>,
===
/player_room_release_node <number>:,
player_room_release_node <number>,
===
/quiz_game_force_open <number>:,
quiz_game_force_open <number>,
qgfo <number>,
===
/update_player_node_times <given_name> <node_id> <times>:,
update_player_node_times <word> <number> <number>,
upnt <word> <number> <number>,
===
/strenghten_equipments <number>:,
strenghten_equipments <number>,
se <number>,
===
/gain_bind_gold <number>: gain bind gold num,
gbg <number>,
===
/set_node_pvp <number> <number>: set_node_pvp,
set_node_pvp <number> <number>,
snp <number> <number>,
===
/set_node_pvp_zone <number> <number>: set_node_pvp_zone,
set_node_pvp_zone <number> <number>,
snpz <number> <number>,
===
/event_showmsg <position> <rest_input>: event trigger to show message,
event_showmsg <number> <rest_input>,
===
/set_node_exp_nb <number> <number>: set_node_exp_no_broadcast,
set_node_exp_nb <number> <number>,
snen <number> <number>,
===
/set_node_gold_nb <number> <number>: set_node_gold_no_broadcast,
set_node_gold_nb <number> <number>,
sngn <number> <number>,
===
/set_reborn_mob_pvp <min_left>: set_reborn_mob_pvp,
set_reborn_mob_pvp <number>,
srmp <number>,
===
/gain_coins:,
gain_coins <number> <number>,
gco <number> <number>,
===
/npc_talk,
npc_talk <number>,
===
/blackout <textindex> <times>:,
blackout <number> <number>,
===
/bc_tran_msg <type> <msg> <screen_msg> <confirmmsg>: broadcast transition msg,
bc_tran_msg <number> <word> <number> <number>,
===
/node_black_out <target> <msg1> <time1> <msg2> <time2> <msg3> <time3>: play blackouting,
node_black_out <number> <number> <number> <number> <number> <number> <number> <number>,
===
/gain_eudemon_level <level>: gain eudemon level,
gain_eudemon_level <number>,
geul <number>,
===
/screen_effect <target> <effect_type> <effect_level> <effect_time>: screen effect,
screen_effect <number> <number> <number> <number>,
===
/gem_powerup <container_id> <loc> <level>: gem level up,
gem_powerup <number> <number> <number>,
gemup <number> <number> <number>,
===
/play_cutscene <file_name> <target> <msg1>: play cutscene,
play_cutscene <word> <number> <number>,
===
/add_memories <memories_id> <num>: add memories,
add_memories <number> <number>,
amem <number> <number>,
===
/remove_memories <memoried_id>: remove memories,
remove_memories <number>,
rmem <number>,
===
/add_memoriesex <memories_id> <num> <extra_info>: add memories with extra,
add_memoriesex <number> <number> <rest_input>,
amemex <number> <number> <rest_input>,
===
/open_fight <fight_tid> <duration> <one_side_number>: open fight <fight id> <duration in sec> <persons need in one-side to open>,
open_fight <number> <number> <number>,
of <number> <number> <number>,
===
/set_lover_point_countdown_timer <number>: set_lover_point_countdown_timer,
set_lover_point_countdown_timer <number>,
lpcd <number>,
===
/active_subweapon_to_character <given_name> <is_active>: active subweapon to character,
active_subweapon_to_character <word> <number>,
aswtc <word> <number>,
===
/select_family_leader2 <leader_id>:,
select_family_leader2 <number>,
===
/switch_fight_time <switch>:,
switch_fight_time <number>,
sft <number>,
===
/reset_daily_bonus <day_num>:,
reset_daily_bonus <number>,
rdb <number>,
===
/self_use_effect <effect_id> <duration> <stacks>: let pc use stacks effect on self,
self_use_effect <number> <number> <number>,
sue <number> <number> <number>,
===
/clear_fight <fight_id>: close and clear fight<fight_id>,
clear_fight <number>,
cf <number>,
===
/family_diagram_vit <number>: set player's diagram vit to <number>,
family_diagram_vit <number>,
fdv <number>,
===
/family_diagram_vit <number>: set player's diagram vit to <number>,
family_diagram_progress <number>,
fdp <number>,
===
/family_diagram_node_state <node_id> <times>: set diagram<node_id> clear times to <times>,
family_diagram_node_state <number> <number>,
fdns <number> <number>,
===
/family_diagram_reset <reset_option: reset diagram by <option> 0 only diagram group / 1 diagram group and progress,
family_diagram_reset <number>,
fdr <number>,
===
/begin_node_event <event_id>: begin the event<event_id> at player's node,
begin_node_event <number>,
bne <number>,
===
/set_hair_id <id>: set character hair,
set_hair_id <number>,
shid <number>,
===
/set_face_id <id>: set character face,
set_face_id <number>,
sfid <number>,
===
/set_hair_color <color>: set character hair color,
set_hair_color <number>,
shc <number>,
===
/set_skin_color <color>: set character skin color,
set_skin_color <number>,
ssc <number>,
===
/set_eyes_color <color>: set character eyes color,
set_eyes_color <number>,
sec <number>,
===
/set_helmet_color <color>: set character helmet color,
set_helmet_color <number>,
s0c <number>,
===
/set_clothes_color <color>: set character clothes color,
set_clothes_color <number>,
s1c <number>,
===
/set_cloak_color <color>: set character cloak color,
set_cloak_color <number>,
s2c <number>,
===
/update_closet <index>: update current color to closet,
update_closet <number>,
ucl <number>,
===
/set_spell_level <id> <level>: set spell level,
set_spell_level <number> <number>,
spel <number> <number>,
===
/add_class <id>: add class,
add_class <number>,
===
/remove_class <id>: remove class,
remove_class <number>,
dcc <number>,
===
/set_class_level <number>: set class level,
set_class_level <number>,
scl <number>,
===
/get_license <number>: set license,
gel <number>,
===
/remove_all_license: remove all license,
remove_all_license,
===
/set_all_spell_level <number>: set all spell level,
set_all_spell_level <number>,
sapl <number>,
===
/set_node_np: set node np rate,
set_node_np <number> <number>,
snn <number> <number>,
===
/remove_family_emblem <number>: remove family emblem,
remove_family_emblem <number>,
rfe <number>,
===
inside <class> <level>: test some information,
inside <number> <number>,
===
/clear_cool_down_time: clear character's cool down time,
clear_cool_down_time,
ccdt,
===
/shop <shop_type> <npc_id> <level_min> <level_max>: enter spell shop,
shop <word> <number> <number> <number>,
===
/put_treasure <id> <amount>: put treasure at ground,
put_treasure <number> <number>,
===
/add_lottery_plus <value>: add lottery plus,
add_lottery_plus <number>,
alp <number>,
===
/reload_elf_lottery_db: reload elf lottery db,
reload_elf_lottery_db,
reld,
===
/lottery_week_update <day> <hour> <min>: reload week update,
lottery_week_update <number> <number> <number>,
lwu <number> <number> <number>,
===
/clear_lover_disband: clear lover disband,
clear_lover_disband,
===
/super_clear_bag_item: super_clear_bag_item,
===
/making_item <operation_type> <making_item_way_id>: learn new making item way,
making_item <word> <number>,
mi <word> <number>,
===
/making_item <operation_type> <type> <exp>: add making item type exp,
making_item <word> <number> <number>,
mi <word> <number> <number>,
===
/add_hate <caster_id> <target_id> <target_type>: add hate to life,
add_hate <number> <number> <number>,
ah <number> <number> <number>,
===
/achievement_screen_message <achieve_id> <ownder_id>: show screen message when get achievement point ,
achievement_screen_message <number> <number>,
===
/active_subweapon <number>: active subweapon,
active_subweapon <number>,
asw <number>,
===
confirmmsg <rest_input>: show confirm msg,
===
/get_lover_point <number>: get lover point,
get_lover_point <number>,
glp <number>,
===
/set_lover_level <number>: set_lover_level,
set_lover_level <number>,
sll <number>,
===
/expand_elf_bank <number>: expand_elf_bank,
expand_elf_bank <number>,
eeb <number>,
===
/add_attr_value <word> <number>: add attr value,
add_attr_value <word> <number>,
atv <word> <number>,
===
/reset_daily_mission: reset daily mission,
reset_daily_mission,
===
/transfer_name <given_name>: transport to character with nickname,
transfer_name <word>,
tn <word>,
===
/gain_dust <number>: gain dust num,
gain_dust <number>,
gd <number>,
===
/reset_group_reward: reset group reward,
reset_group_reward,
===
/open_fortune_bag <fortune_bag_id> <times> <drop_rate>:,
open_fortune_bag <number> <number> <number>,
ofb <number> <number> <number>,
===
/modify_durability <number> <number>:,
modify_durability <number> <number>,
md <number> <number>,
===
/captcha_wordtype_noise <number> <wordtype>:,
captcha_wordtype_noise <number> <number>,
cawn <number> <number>,
===
/gainpp <pptype> <number>:,
gainpp <number> <number>,
gainpp <number> <number>,
===
/clear_spell: clear player all spell,
clear_spell,
===
/change_weapon_type <number> <number>: change my main or second weapon type,
change_weapon_type <number> <number>,
cwt <number> <number>,
===
/weapon_strengthen <number> <number> <number> <number>:,
weapon_strengthen <number> <number> <number> <number>,
wpns <number> <number> <number> <number>,
===
/gain_fragment <number>:,
gf <number>,
===
/clear_advenchants: clear adventure enchants,
clear_advenchants,
===
/set_elf_emblem_attr <number> <number> <number>:,
set_elf_emblem_attr <number> <number> <number>,
seea <number> <number> <number>,
===
/reset_timer <reset_type>: active reset time,
reset_timer <number>,
rtt <number>,
===
/close_node <number> <number>:,
===
/set_survival_ghost <name> <survivalmode>: set character survival mode,,
set_survival_ghost <word> <number>,
ssg <word> <number>,
===
/set_personal_log_id <number>:,
spli <number>,
===
/reload_trace_event:,
rlte,
===
/update_rank_info <type> <reset>:,
update_rank_info <number> <number>,
uri <number> <number>,
===
/gm_talk <charname> <message>:,
gm_talk <word> <rest_input>,
gt <word> <rest_input>,
===
/gm_talk_node <message>:,
===
/check_player_pp <charname>:,
check_player_pp <word>,
cpp <word>,
===
/close_shop <number> <number>:,
===
/reset_week_achievement <charname> <type>:,
reset_week_achievement <word> <number>,
rwa <word> <number>,
===
/show_player_node_times <given_name> <node_id>:,
show_player_node_times <word> <number>,
spnt <word> <number>,
===
/reset_daily_achievement <charname>:,
reset_daily_achievement <word>,
rda <word>,
===
/sky_tower_open_state <tower_id> <type> <param>:,
sky_tower_open_state <number> <number> <number>,
stos <number> <number> <number>,
===
/check_achievement_group <charname> <id>:,
check_achievement_group <word> <number>,
cag <word> <number>,
===
/bgw_account_clear <account_name> <accoount_id>:,
bgw_account_clear <word> <number>,
bac <word> <number>,
===
/reset_account_achievement <player_name>:,
reset_account_achievement <word>,
raa <word>,
===
/accept_mission <mission_id>:,
accept_mission <number>,
am <number>,
===
/set_friend_level <name> <level>:,
set_friend_level <word> <number>,
sfrl <word> <number>,
===
/update_health_time <online_time> <offline_time>:,
update_health_time <number> <number>,
uht <number> <number>,
===
/check_player_lottery <charname>:,
check_player_lottery <word>,
cpl <word>,
===
/set_teach_mode <teach_type> <teach_step>:,
set_teach_mode <number> <number>,
stm <number> <number>,
===
/shut_down: shut down,
shut_down,
===
/kick_out <player_ip> <reason>: kick out player,
kick_out <number> <number>,
===
/exchange items <char id> <node_id> <pin> <size> <item_id> <item_number> :... ,
exchange items <number> <number> <word> <number> <rest_input>,
===
/family_set_emblem_fail <char id> <node_id>:,
family_set_emblem_fail <number> <number>,
===
/trace_result <receiver_id> <target_id> <node_id>:,
trace_result <number> <number> <number>,
===
/do_aw_put_treasure <receiver_id> <item_id> <node_id> <amount> <x> <y>:,
do_aw_put_treasure <number> <number> <number> <number> <number> <number>,
===
/update_prestige <ch_id> <node_id> <prestige_id> <level> <exp>:,
update_prestige <number> <number> <number> <number> <number>,
===
/captcha_punish <ch_id> <punish_type> <duration>:,
captcha_punish <number> <number> <number>,
===
/gm_tool_login_result <account> <account_id> <privilege>:,
gm_tool_login_result <word> <number> <number>,
===
/gm_tool_ban_result <ch_name> <gm_name>:,
gm_tool_ban_result <word> <word>,
===
/get_net_cafe_vip <ch_id> <net_cafe_vip> <buff_type>:,
get_net_cafe_vip <number> <number> <number>,
===
/sp_itemmall_req_buy <ch_id> <coin_type> <total_point> <item_id> <amount> <item_color> <due_date_time> <mall_group> <mall_item_index> <item_amount>:,
sp_itemmall_req_buy <number> <number> <number> <number> <number> <number> <number> <number> <number> <number>,
===
/check_communicate_lock_ret <ch_id> <type> <1/0>: check communicate lock result,
check_communicate_lock_ret <number> <number> <number>,
===
/update_health <ch_id> <online_time> <offline_time>:,
update_health <number> <number> <number>,
===
/health <ch_id> <health_rule> <online_time> <offline_time>:,
health <number> <number> <number> <number>,
===
/get_daily_bonus <ch_id> <daily_state> <request_id>:,
get_daily_bonus <number> <number> <number>,
===
