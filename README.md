

===

### /clone_monster [id] [unit] [dropid]

| clone_monster | 
| description: Clone Monster At Player around |
| short form: cm |
| Values |
| id | unit | dropid | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /restore

| restore | 
| description: restore the hp |

===

### /set_rb mob [n] [id] [seconds]

| set_rbmob | 
| description: reborn mober binding |
| short form: set_rb |
| Values |
| n | id | seconds | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 
| short form: sr |
| Values |
| n | id | seconds | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /ls_rb

| ls_rb | 
| description: list reborn mober binding |
| short form: lr |

===

### /rm_rb mob

| rm_rbmob | 
| description: remove reborn mober binding |
| short form: rm_rb |
| number | |
|---|---|---|
| | | 
| short form: rr |
| number | |
|---|---|---|
| | | 

===

### /status

| status | 
| description: query the player's status |

===

### /clone item [item_id]

| cloneitem | 
| description: clone an item which template id is [item_id] |
| short form: clone_item |
| Values |
| item_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 
| short form: ci |
| Values |
| item_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /clone reward item [item_id] [item_num]

| clonereward item | 
| description: clone an item which template id is [item_id] |
| short form: clone_reward_item |
| Values |
| item_id | item_num | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: clri |
| Values |
| item_id | item_num | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /clone items [item_id] [item_num]

| cloneitems | 
| description: clone an item which template id is [item_id] and item quantity is [item_num] |
| short form: clone_items |
| Values |
| item_id | item_num | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: cls |
| Values |
| item_id | item_num | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /clone items [item_id] [item_num]

| cloneitems | 
| description: clone an item which template id is [item_id] and item quantity is [item_num] |
| short form: clone_items |
| Values |
| item_id | item_num | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: clone_stack_item |
| Values |
| item_id | item_num | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /clone_item_to [item_id] [to_loc]

| clone_item_to | 
| description: clone an item which template id is [item_id] and put into inventory at location [to_loc] |
| short form: clt |
| Values |
| item_id | to_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /say [message]

| say | 
| description: say something |
| short form: s |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /whisper [name] [message]

| whisper | 
| description: whisper someone something |
| short form: w |
| Values |
| name | message | |
|---|---|---|
| word | rest_input | |
|---|---|---|
| | | 

===

### /kill [monster_id]

| kill | 
| description: monster! DIE! |
| short form: k |
| Values |
| monster_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /gain_exp [number]

| gain_exp | 
| description: gain exp num |

===

### /mission_gain_exp [number]

| mission_gain_exp | 
| description: gain exp num |
| short form: mge |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /gain_gold [number]

| gain_gold | 
| description: gain gold num |
| short form: gg |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /goto [x] [y]

| goto | 
| description: goto x y |

===

### /users

| users | 
| description: list the node users info |

===

### /allusers

| allusers | 
| description: list whole world users |

===

### /transfer [id]

| transfer | 
| description: |

===

### /listarea

| listarea | 
| description: list the areas in the currently node |
| short form: lsa |

===

### /weak [player_id]

| weak | 
| description: let target player weak |

===

### /setra [node_id] [area_id]

| setra | 
| description: set revive area |
| short form: sra |
| Values |
| node_id | area_id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /transport_area [node_id] [area_id]

| transport_area | 
| description: transport to area |
| short form: tpa |
| Values |
| node_id | area_id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /transport_node [node_id]

| transport_node | 
| description: transport to node |
| short form: tpn |
| Values |
| node_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /drop_item [item_id] [number] [flag]

| drop_item | 
| description: drop item |

===

### /list_durability [container_id]

| list_durability | 
| description: list durability status |
| short form: ld |
| Values |
| container_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /shop [shop_type] [npc_template_id] [shop_id]

| shop | 
| description: enter shop |

===

### /shop [shop_type] [npc_id]

| shop | 
| description: enter spell shop |

===

### /effect_life [life_id] [effect_id] [duration] [factor] [isteam]

| effect_life | 
| description: |
| short form: elf |
| Values |
| life_id | effect_id | duration | factor | isteam | |
|---|---|---|
| number | number | number | number | number | |
|---|---|---|
| | | 

===

### /effect_loc [x] [y] [effect_id] [duration] [factor]

| effect_loc | 
| description: |
| short form: eloc |
| Values |
| x | y | effect_id | duration | factor | |
|---|---|---|
| number | number | number | number | number | |
|---|---|---|
| | | 

===

### /repairshop

| repairshop | 
| description: enter repair shtop |

===

### /invincible [01]

| invincible | 
| description: invincible mode 0 - off |
| short form: inv |
| Values |
| 01 | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /vanish [01]

| vanish | 
| description: invisible mode 0 - off |
| short form: van |
| Values |
| 01 | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /town

| town | 
| description: transport to town |

===

### /transport_to_character [given_name]

| transport_to_character | 
| description: transport to character with nickname |
| short form: tpc |
| Values |
| given_name | |
|---|---|---|
| word | |
|---|---|---|
| | | 

===

### /get_user_info [given_name]

| get_user_info | 
| description: findout about an nickname |
| short form: gui |
| Values |
| given_name | |
|---|---|---|
| word | |
|---|---|---|
| | | 

===

### /get_shortcuts

| get_shortcuts | 
| description: list shortcuts |

===

### /update_shortcut [page] [slot] [value]

| update_shortcut | 
| description: modify shortcuts (page and slot starts from 0) |
| short form: us |
| Values |
| page | slot | value | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /save_shortcut

| save_shortcut | 
| description: save shortcuts |

===

### /display_sum_node_users [01]

| display_sum_node_users | 
| description: |
| short form: dnu |
| Values |
| 01 | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /display_sum_world_users [01]

| display_sum_world_users | 
| description: list whole world users mode 0 - off |
| short form: dwu |
| Values |
| 01 | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /get_spellmaster [spellmaster_id]

| get_spellmaster | 
| description: get a spellmaster |

===

### /debug [01]

| debug | 
| description: debug mode 0 - off |

===

### /list_state

| list_state | 
| description: list my states |

===

### /shut_down [minutes]

| shut_down | 
| description: shut down in x minutes |

===

### /kick [nick_name]

| kick | 
| description: kick out character with name |

===

### /slayer [01]

| slayer | 
| description: slayer mode 0 - off |

===

### /announce [message]

| announce | 
| description: announce something |
| short form: gm |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /storage [npc_id] [01]

| storage | 
| description: enter storage 0 - Deposit |

===

### /querychar [charname]

| querychar | 
| description: |
| short form: qc |
| Values |
| charname | |
|---|---|---|
| word | |
|---|---|---|
| | | 

===

### /listenchant [charname]

| listenchant | 
| description: |
| short form: le |
| Values |
| charname | |
|---|---|---|
| word | |
|---|---|---|
| | | 

===

### /version

| version | 
| description: |

===

### /transport_and_deduct [area_id] [money]

| transport_and_deduct | 
| description: transport to area and deduct money |
| short form: tam |
| Values |
| area_id | money | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /query_npc [node_id] [npc_id]

| query_npc | 
| description: query npc [number] to show on map |
| short form: qn |
| Values |
| node_id | npc_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /party [message]

| party | 
| description: say something in party channel |
| short form: p |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /party [message]

| party | 
| description: say something in party channel |
| short form: party_2 |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /guild [message]

| guild | 
| description: say something in guild channel |
| short form: g |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /guild [message]

| guild | 
| description: say something in guild channel |
| short form: guild_3 |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /trade [message]

| trade | 
| description: say something in trade channel |
| short form: t |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /trade [message]

| trade | 
| description: say something in trade channel |
| short form: trade_4 |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /chat [message]

| chat | 
| description: say somehting in chat channel |
| short form: c |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /chat [message]

| chat | 
| description: say somehting in chat channel |
| short form: chat_5 |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /system [message]

| system | 
| description: announce something from system |

===

### /channel_limit [id] [minute]

| channel_limit | 
| description: channel usage limitation |
| short form: cl |
| Values |
| id | minute | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /flush_dba_data

| flush_dba_data | 
| description: Flush player DBAgent Data |

===

### /banchar [char_id] [minute]

| banchar | 
| description: ban character |
| short form: bc |
| Values |
| char_id | minute | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /identify_shop

| identify_shop | 
| description: enter identify shop |
| short form: id_shop |

===

### /disband_family

| disband_family | 
| description: |

===

### /select_family_leader [new_leader]

| select_family_leader | 
| description: |
| short form: sfl |
| Values |
| new_leader | |
|---|---|---|
| word | |
|---|---|---|
| | | 

===

### /listfms [ch_id] [mission_id]

| listfms | 
| description: list fms info on this character |
| short form: lsf |
| Values |
| ch_id | mission_id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /run [number]

| run | 
| description: Faster Walk |

===

### /drop stack item [item_id] [amount]

| dropstack item | 
| description: drop item by amount |
| short form: drop_items |
| Values |
| item_id | amount | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: drop_stack_item |
| Values |
| item_id | amount | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /allworld_cmd [rest_input]

| allworld_cmd | 
| description: all world text command |
| short form: aw |
| Values |
| rest_input | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /query_npc_involve [npc_id]

| query_npc_involve | 
| description: query npc [number] to list how many missionlist involved |
| short form: qni |
| Values |
| npc_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /channel_limit_name [charname] [minute]

| channel_limit_name | 
| description: channel usage limitation |
| short form: cln |
| Values |
| charname | minute | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /banchar_name [char_name] [minute]

| banchar_name | 
| description: ban character |
| short form: bcn |
| Values |
| char_name | minute | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /quest [message]

| quest | 
| description: say somehting in quest channel |
| short form: q |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /quest [message]

| quest | 
| description: say somehting in quest channel |
| short form: quest_6 |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /reset_attribute

| reset_attribute | 
| description: reset attribute point |
| short form: ra |

===

### /reset_skill

| reset_skill | 
| description: reset skill point |

===

### /reset_attribute_gold [how_much]

| reset_attribute_gold | 
| description: reset attribute point for gold |
| short form: rag |
| Values |
| how_much | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /reset_skill_gold [how_much]

| reset_skill_gold | 
| description: reset skill point for gold |
| short form: rsg |
| Values |
| how_much | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /get_spell [spell_id]

| get_spell | 
| description: get a spell |

===

### /inlay_shop [npc_id]

| inlay_shop | 
| description: enter inlay shop |
| short form: in_shop |
| Values |
| npc_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /broadcast_system_message [msg_id] [times] [interval] [msg]

| broadcast_system_message | 
| description: |
| short form: bsm |
| Values |
| msg_id | times | interval | msg | |
|---|---|---|
| number | number | number | rest_input | |
|---|---|---|
| | | 

===

### /echo [message]

| echo | 
| description: show message without prompt |

===

### /clone_monster_locate [mob_id] [absolute] [loc_x] [loc_y]

| clone_monster_locate | 
| description: clone monster in absolute/relate coordinate in same node with player |
| short form: cml |
| Values |
| mob_id | absolute | loc_x | loc_y | |
|---|---|---|
| number | number | number | number | |
|---|---|---|
| | | 

===

### /clone_monster_around [mob_id] [absolute] [angle] [range]

| clone_monster_around | 
| description: clone monster around player by absolute/relate angle |
| short form: cma |
| Values |
| mob_id | absolute | angle | range | |
|---|---|---|
| number | number | number | number | |
|---|---|---|
| | | 

===

### /npc_use_channel [npc_id] [channel_id] [type] [message]

| npc_use_channel | 
| description: let npc use channel to say something |
| short form: nuc |
| Values |
| npc_id | channel_id | type | message | |
|---|---|---|
| number | number | number | rest_input | |
|---|---|---|
| | | 

===

### /npc_use_spell [npc_id] [spell_id]

| npc_use_spell | 
| description: let npc use spell on pc in the same node |
| short form: nus |
| Values |
| npc_id | spell_id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /self_use_effect [effect_id] [duration]

| self_use_effect | 
| description: let pc use effect on self |
| short form: sue |
| Values |
| effect_id | duration | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /change_class [class_id]

| change_class | 
| description: change current class |
| short form: cc |
| Values |
| class_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /adjust_spell_anitime [spell_id] [animeTime_ofs]

| adjust_spell_anitime | 
| description: change spell animation time |
| short form: asa |
| Values |
| spell_id | animeTime_ofs | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /escape

| escape | 
| description: transfer team member to the last enter normal area |

===

### /set_level [level]

| set_level | 
| description: set character level |
| short form: sl |
| Values |
| level | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_monster_damage [monster id] [physico damage] [attack var] [physico defence] [magic damage] [magic attack var] [magic defence]

| set_monster_damage | 
| description: set monster damage |
| short form: smd |
| Values |
| monster id | physico damage | attack var | physico defence | magic damage | magic attack var | magic defence | |
|---|---|---|
| number | number | number | number | number | number | number | |
|---|---|---|
| | | 

===

### /set_monster_movement [monster id] [movement] [roammovement] [attack delay]

| set_monster_movement | 
| description: set monster |
| short form: smm |
| Values |
| monster id | movement | roammovement | attack delay | |
|---|---|---|
| number | number | number | number | |
|---|---|---|
| | | 

===

### /show_monster [template monster id]

| show_monster | 
| description: show monster information |
| short form: sm |
| Values |
| template monster id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_monster_sight [monster id] [sight]

| set_monster_sight | 
| description: set monster sight |
| short form: sms |
| Values |
| monster id | sight | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /test_character_attack [monster id]

| test_character_attack | 
| description: test character |
| short form: tca |
| Values |
| monster id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /test_monster_attack [monster id]

| test_monster_attack | 
| description: test monster |
| short form: tma |
| Values |
| monster id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /set_sevel_grow [con] [str] [int] [dex] [vol] [max_hp] [max_mp]

| set_sevel_grow | 
| description: set attr |
| short form: set_level_grow |
| Values |
| con | str | int | dex | vol | max_hp | max_mp | |
|---|---|---|
| number | number | number | number | number | number | number | |
|---|---|---|
| | | 

===

### /querylevelgrow

| querylevelgrow | 
| description: |
| short form: query_level_grow |

===

### /set_item [item id] [word] [number]

| set_item | 
| description: |

===

### /save_monster [template monster id]

| save_monster | 
| description: save monster to db |

===

### /get_effect_data [effect id]

| get_effect_data | 
| description: get effect data |
| short form: ged |
| Values |
| effect id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_effect_data [effect id] [family type] [target type] [duration] [period] [width] [height] [enchant type] [resist type] [param min] [param max] [next id] [level]

| set_effect_data | 
| description: set effect data |
| short form: sed |
| Values |
| effect id | family type | target type | duration | period | width | height | enchant type | resist type | param min | param max | next id | level | |
|---|---|---|
| number | word | word | number | number | number | number | word | word | number | number | number | number | |
|---|---|---|
| | | 

===

### /set_effect_command [effect id] [command type] [commands]

| set_effect_command | 
| description: set effect command |
| short form: sec |
| Values |
| effect id | command type | commands | |
|---|---|---|
| number | word | rest_input | |
|---|---|---|
| | | 

===

### /get_spell_data [spell id]

| get_spell_data | 
| description: get spell data |
| short form: gsd |
| Values |
| spell id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_reborn_monster [handle] [x] [y] [monster_temp_id] [amount] [seconds] [width] [height] [patrol_id]

| set_reborn_monster | 
| description: reborn mober binding |
| short form: srm |
| Values |
| handle | x | y | monster_temp_id | amount | seconds | width | height | patrol_id | |
|---|---|---|
| number | word | word | number | number | number | word | word | number | |
|---|---|---|
| | | 

===

### /get_all_template_monsters

| get_all_template_monsters | 
| description: get all template monster |
| short form: gatm |

===

### /monster_goto [monster id] [x] [y]

| monster_goto | 
| description: goto x y |
| short form: wm |
| Values |
| monster id | x | y | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /around_kill_all [radius]

| around_kill_all | 
| description: around kill all |
| short form: aka |
| Values |
| radius | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /around_kill [monster id] [radius]

| around_kill | 
| description: around kill |
| short form: ak |
| Values |
| monster id | radius | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /query_test_attack_monster

| query_test_attack_monster | 
| description: query test attack monster |
| short form: qtam |

===

### /reload_reborn_monster [node id]

| reload_reborn_monster | 
| description: reload reborn monster |
| short form: rrm |
| Values |
| node id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /list_pms [pms_id]

| list_pms | 
| description: list pms info on this character |
| short form: listpms |
| Values |
| pms_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /echobyid [greeting_id]

| echobyid | 
| description: show message without prompt by greeting_id |

===

### /change_hair_color [color_id]

| change_hair_color | 
| description: change character hair color |
| short form: chc |
| Values |
| color_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /change_hair [hair_id]

| change_hair | 
| description: change character hair |
| short form: ch |
| Values |
| hair_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /reload_effect

| reload_effect | 
| description: reload effect data |

===

### /reload_template_monster

| reload_template_monster | 
| description: reload template_monster data |

===

### /summon_pet [template_id]

| summon_pet | 
| description: summon pet |

===

### /gain_skill_point [number]

| gain_skill_point | 
| description: gain skill point |
| short form: gsp |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /node [message]

| node | 
| description: say to all man in node |
| short form: n |
| Values |
| message | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /system_area [area_id] [message]

| system_area | 
| description: announce something from system |
| short form: sysarea |
| Values |
| area_id | message | |
|---|---|---|
| word | rest_input | |
|---|---|---|
| | | 

===

### /fatality_damage [LiftEntity_id]

| fatality_damage | 
| description: set LiftEntity HP = MP = 1 |
| short form: fd |
| Values |
| LiftEntity_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /restore_all

| restore_all | 
| description: restore the hp |

===

### /clear_near_items

| clear_near_items | 
| description: clear near items around caster |

===

### /get_server_id

| get_server_id | 
| description: get zoneserver id |

===

### /test_durability [mob id] [loc] [durability]

| test_durability | 
| description: test durability decrease in attacked |
| short form: td |
| Values |
| mob id | loc | durability | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /test_spell_attack [monster id] [spell id] [spell lv] [number]

| test_spell_attack | 
| description: test character |
| short form: tsa |
| Values |
| monster id | spell id | spell lv | number | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /test_drop_treasure [monster id] [number]

| test_drop_treasure | 
| description: test drop treasure |
| short form: tdt |
| Values |
| monster id | number | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /test_pk [monster id]

| test_pk | 
| description: test pk |
| short form: tpk |
| Values |
| monster id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /surprise_box [SurpriseBoxID]

| surprise_box | 
| description: invoke surprise box |
| short form: sb |
| Values |
| SurpriseBoxID | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /SetExtBornMonster [num] [time sec]

| SetExtBornMonster | 
| description: extern born monster |
| short form: setextbornmonster |
| Values |
| num | time sec | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: sebm |
| Values |
| num | time sec | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /set_family_level [fm_level]

| set_family_level | 
| description: set family level |
| short form: sflv |
| Values |
| fm_level | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /family_level_up

| family_level_up | 
| description: family level up |

===

### /set_family_emblem [emblem1] [emblem2]

| set_family_emblem | 
| description: set family emblem |
| short form: sfe |
| Values |
| emblem1 | emblem2 | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /select_family_emblem

| select_family_emblem | 
| description: select family emblem |

===

### /open_exploit_rank

| open_exploit_rank | 
| description: Open Exploit Rank |

===

### /reload_formula_params

| reload_formula_params | 
| description: reload formula parameters |

===

### /reload_grow_table

| reload_grow_table | 
| description: reload grow table |

===

### /give_exploit [exploit amount],

| give_exploit | 
| description: |

===

### /RepairAllEquipment

| RepairAllEquipment | 
| description: RepairAllEquipment |
| short form: repairallequipment |

===

### /trace [receive_id] [target_name]

| trace | 
| description: Trace a character by name |

===

### /drill_item [slot] [number]

| drill_item | 
| description: DrillItem |

===

### /fubag [id]

| fubag | 
| description: fortune bag item |

===

### /aw_put_treasure [id] [amount]

| aw_put_treasure | 
| description: put treasure all world |
| short form: awpt |
| Values |
| id | amount | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /setfms [ch_id] [mission_id] [value]

| setfms | 
| description: set fms value on this character |
| short form: setf |
| Values |
| ch_id | mission_id | value | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /clone_quest_treasure [item_id] [number] [node_id] [x] [y] [template_id]

| clone_quest_treasure | 
| description: drop quest item |

===

### /set_bag_time [index] [time]

| set_bag_time | 
| description: set the due date for bags |
| short form: sbt |
| Values |
| index | time | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /gain_family_exp [number]

| gain_family_exp | 
| description: gain family exp |
| short form: gfe |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_prestige_level [prestige_id] [level]

| set_prestige_level | 
| description: set prestige level |
| short form: spl |
| Values |
| prestige_id | level | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /gain_prestige_exp [prestige_id] [exp]

| gain_prestige_exp | 
| description: gain prestige exp |
| short form: gpe |
| Values |
| prestige_id | exp | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /cast_spell [number] [number]

| cast_spell | 
| description: cast spell to life |
| short form: cs |
| Values |
| number | number | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /set_sys_var [word] [number]

| set_sys_var | 
| description: set system varaible |
| short form: ssv |
| Values |
| word | number | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /add_appellation [appellation_id]

| add_appellation | 
| description: add appellation |
| short form: aa |
| Values |
| appellation_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_present_appellation [appellation_id]

| set_present_appellation | 
| description: set present appellation |
| short form: spa |
| Values |
| appellation_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 
| short form: add_elf |
| Values |
| appellation_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 
| short form: ae |
| Values |
| appellation_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /remove_elf [elf_loc]

| remove_elf | 
| description: remove elf |
| short form: elf_skill |
| Values |
| elf_loc | |
|---|---|---|
| add 1/remove 0 | elf_loc | skill_id | |
|---|---|---|
| | | 
| short form: elf_skill |
| Values |
| elf_loc | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 
| short form: set_elf_level |
| Values |
| elf_loc | |
|---|---|---|
| elf_loc | level | |
|---|---|---|
| | | 
| short form: set_elf_level |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: sel |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: set_elf_mood |
| Values |
| elf_loc | |
|---|---|---|
| elf_loc | mood | |
|---|---|---|
| | | 
| short form: set_elf_mood |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: sem |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: use_item_to |
| Values |
| elf_loc | |
|---|---|---|
| inv/equ | container_index | loc | target_id | param | |
|---|---|---|
| | | 
| short form: use_item_to |
| Values |
| elf_loc | |
|---|---|---|
| word | number | number | number | rest_input | |
|---|---|---|
| | | 
| short form: uit |
| Values |
| elf_loc | |
|---|---|---|
| word | number | number | number | rest_input | |
|---|---|---|
| | | 
| short form: set_spell_card |
| Values |
| elf_loc | |
|---|---|---|
| index | item_number | |
|---|---|---|
| | | 
| short form: set_spell_card |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: ssc |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: gain_elf_exp |
| Values |
| elf_loc | |
|---|---|---|
| elf_loc | exp | |
|---|---|---|
| | | 
| short form: gain_elf_exp |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: gee |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: gain_elf_familiar |
| Values |
| elf_loc | |
|---|---|---|
| elf_loc | familiar | |
|---|---|---|
| | | 
| short form: gain_elf_familiar |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: gef |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: show_debug_message |
| Values |
| elf_loc | |
|---|---|---|
| 0/1 | |
|---|---|---|
| | | 
| short form: show_debug_message |
| Values |
| elf_loc | |
|---|---|---|
| number | |
|---|---|---|
| | | 
| short form: sdm |
| Values |
| elf_loc | |
|---|---|---|
| number | |
|---|---|---|
| | | 
| short form: set_log_level |
| Values |
| elf_loc | |
|---|---|---|
| server | level | |
|---|---|---|
| | | 
| short form: set_log_level |
| Values |
| elf_loc | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 
| short form: slog |
| Values |
| elf_loc | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 
| short form: set_assert |
| Values |
| elf_loc | |
|---|---|---|
| server | 0/1 | |
|---|---|---|
| | | 
| short form: set_assert |
| Values |
| elf_loc | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 
| short form: set_spell_card_attr |
| Values |
| elf_loc | |
|---|---|---|
| value | value | value | value | |
|---|---|---|
| | | 
| short form: set_spell_card_attr |
| Values |
| elf_loc | |
|---|---|---|
| number | number | number | number | |
|---|---|---|
| | | 
| short form: set_elf_action |
| Values |
| elf_loc | |
|---|---|---|
| loc | animation_id | |
|---|---|---|
| | | 
| short form: set_elf_action |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: sea |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: inside |
| Values |
| elf_loc | |
|---|---|---|
| class | |
|---|---|---|
| | | 
| short form: inside |
| Values |
| elf_loc | |
|---|---|---|
| number | |
|---|---|---|
| | | 
| short form: auction_sell |
| Values |
| elf_loc | |
|---|---|---|
| item_id | amount | |
|---|---|---|
| | | 
| short form: auction_sell |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: as |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: friend_together: player add frined |
| Values |
| elf_loc | |
|---|---|---|
| | | 
| short form: friend_together |
| Values |
| elf_loc | |
|---|---|---|
| | | 
| short form: reload_itemmall_db: reload itemmall db |
| Values |
| elf_loc | |
|---|---|---|
| | | 
| short form: reload_itemmall_db |
| Values |
| elf_loc | |
|---|---|---|
| | | 
| short form: set_node_exp: set node exp rate |
| Values |
| elf_loc | |
|---|---|---|
| | | 
| short form: set_node_exp |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: sne |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: set_node_gold: set node gold rate |
| Values |
| elf_loc | |
|---|---|---|
| | | 
| short form: set_node_gold |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: sng |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: set_node_drop: set node drop rate |
| Values |
| elf_loc | |
|---|---|---|
| | | 
| short form: set_node_drop |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: snd |
| Values |
| elf_loc | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: show_hate: Show Character All Hate |
| Values |
| elf_loc | |
|---|---|---|
| | | 
| short form: show_hate |
| Values |
| elf_loc | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /clone item [item_id] [combo_id]

| cloneitem | 
| description: clone an item which template id is [item_id] and combo id is [combo_id] |
| short form: clone_item |
| Values |
| item_id | combo_id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: ci |
| Values |
| item_id | combo_id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /clone item [item_id] [combo_id] [socket_amount]

| cloneitem | 
| description: clone an item which template id is [item_id] and combo id is [combo_id] |
| short form: clone_item |
| Values |
| item_id | combo_id | socket_amount | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 
| short form: ci |
| Values |
| item_id | combo_id | socket_amount | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /return item [receiver_id] [log]

| returnitem | 
| description: use mail return an item to player from log |
| short form: return_item |
| Values |
| receiver_id | log | |
|---|---|---|
| number | rest_input | |
|---|---|---|
| | | 
| short form: ri |
| Values |
| receiver_id | log | |
|---|---|---|
| number | rest_input | |
|---|---|---|
| | | 

===

### /call elf [loc]

| callelf | 
| description: call elf which loc is [loc] |
| short form: call_elf |
| Values |
| loc | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /return gold [receiver_id] [gold]

| returngold | 
| description: use mail return gold to player |
| short form: return_gold |
| Values |
| receiver_id | gold | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: rg |
| Values |
| receiver_id | gold | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: fight switch |
| Values |
| receiver_id | gold | |
|---|---|---|
| 0/1 | fight_tid | seconds | |
|---|---|---|
| | | 
| short form: fight_switch |
| Values |
| receiver_id | gold | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 
| short form: fs |
| Values |
| receiver_id | gold | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /clone_npc [npc_id]

| clone_npc | 
| description: clone npc |
| short form: cn |
| Values |
| npc_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /around_kill_all_player [radius]

| around_kill_all_player | 
| description: around kill all player |
| short form: akap |
| Values |
| radius | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /captcha_id [id] [type]

| captcha_id | 
| description: captcha_id [id] [type] |
| short form: capid |
| Values |
| id | type | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /captcha_name [given_word] [type]

| captcha_name | 
| description: captcha_name [given_name] [type] |
| short form: capname |
| Values |
| given_word | type | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /change_grow_type [growid]

| change_grow_type | 
| description: change_grow_type [growid] |
| short form: cgt |
| Values |
| growid | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /clear_bag_item

| clear_bag_item | 
| description: clear bag item |

===

### /set_statue [node] [id] [action] [key]

| set_statue | 
| description: set statue |
| short form: sst |
| Values |
| node | id | action | key | |
|---|---|---|
| number | number | number | number | |
|---|---|---|
| | | 

===

### /bf_ch_num [bf_type] [level_type] [number]

| bf_ch_num | 
| description: bf_ch_num |

===

### /bf_open [open] [bf_today_type]

| bf_open | 
| description: bf_open |

===

### /gain_love_coin [coin]

| gain_love_coin | 
| description: gain_love_coin |
| short form: glc |
| Values |
| coin | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /remove_enchant [id] [isteam]

| remove_enchant | 
| description: remove enchant |

===

### /visit_family_instance [family_name]

| visit_family_instance | 
| description: visit_family_instance |
| short form: vfi |
| Values |
| family_name | |
|---|---|---|
| word | |
|---|---|---|
| | | 

===

### /gain_building_exp [loc] [exp]

| gain_building_exp | 
| description: gain_building_exp |
| short form: gbe |
| Values |
| loc | exp | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /gain_family_treasury [money]

| gain_family_treasury | 
| description: gain family treasury |
| short form: gft |
| Values |
| money | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /gain_building_durability [loc] [durability]

| gain_building_durability | 
| description: gain building durability |
| short form: gbd |
| Values |
| loc | durability | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /achievement_item [achievement_id]

| achievement_item | 
| description: achievement_item |

===

### /create_town [node_id]

| create_town | 
| description: create_town |

===

### /set_territory_open [territory_tid] [duration]

| set_territory_open | 
| description: set_territory_open |

===

### /clone item [item_id] [combo_id] [socket_amount] [color]

| cloneitem | 
| description: clone an item which template id is [item_id] and combo id is [combo_id] |
| short form: clone_item |
| Values |
| item_id | combo_id | socket_amount | color | |
|---|---|---|
| number | number | number | number | |
|---|---|---|
| | | 
| short form: ci |
| Values |
| item_id | combo_id | socket_amount | color | |
|---|---|---|
| number | number | number | number | |
|---|---|---|
| | | 

===

### /screenmsg [type] [msg]

| screenmsg | 
| description: show screenmsg |

===

### /set_blocklogin [char_id] [flag_id]

| set_blocklogin | 
| description: set block login value |
| short form: sbl |
| Values |
| char_id | flag_id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /set_useblocklogin [flag_id]

| set_useblocklogin | 
| description: set use block login value |
| short form: subl |
| Values |
| flag_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /visit_player_room_id [room_id]

| visit_player_room_id | 
| description: visit player room_id |
| short form: vpri |
| Values |
| room_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /visit_player_room [ch_name]

| visit_player_room | 
| description: visit player room |
| short form: vpr |
| Values |
| ch_name | |
|---|---|---|
| word | |
|---|---|---|
| | | 

===

### /switch_player_room [01]

| switch_player_room | 
| description: switch player room 0 - off |
| short form: spr |
| Values |
| 01 | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /switch_room_decorating [room_id] [01]

| switch_room_decorating | 
| description: switch room decorating mode 0 - off |
| short form: sprd |
| Values |
| room_id | 01 | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /set_territory_status [number] [number]

| set_territory_status | 
| description: set territory status |

===

### /captcha_level [level]

| captcha_level | 
| description: captcha_level [level] |
| short form: caplv |
| Values |
| level | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_gm_map_open [node_id] [open]

| set_gm_map_open | 
| description: set gm map open |
| short form: sgmmo |
| Values |
| node_id | open | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /send_reward_item [number] [number] [number] [number] [number]

| send_reward_item | 
| description: send_reward_item |
| short form: sri |
| Values |
| number | number | number | number | number | |
|---|---|---|
| number | number | number | number | number | |
|---|---|---|
| | | 

===

### /set_achievement [achi_id] [point] [isteam]

| set_achievement | 
| description: |

===

### /gain_cs_gold [gold]

| gain_cs_gold | 
| description: |
| short form: gcg |
| Values |
| gold | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /send_sys_mall_queue [number]

| send_sys_mall_queue | 
| description: |
| short form: send_sys_mail_queue |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 
| short form: ssmq |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_territory_player_limit [territroy_id] [player_limit]

| set_territory_player_limit | 
| description: |
| short form: stpl |
| Values |
| territroy_id | player_limit | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /set_web_btn [number]

| set_web_btn | 
| description: |
| short form: swb |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /recover_territory_event [number]

| recover_territory_event | 
| description: |
| short form: rte |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /family_battle_restart

| family_battle_restart | 
| description: |

===

### /family_battle_setup_judge [phase_type] [phase_index] [family_name]

| family_battle_setup_judge | 
| description: |
| short form: fbsj |
| Values |
| phase_type | phase_index | family_name | |
|---|---|---|
| number | number | word | |
|---|---|---|
| | | 

===

### /family_battle_honor_switch [onoff]

| family_battle_honor_switch | 
| description: |
| short form: fbhs |
| Values |
| onoff | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /family_battle_end

| family_battle_end | 
| description: |

===

### /refresh_recommended_events [number]

| refresh_recommended_events | 
| description: refresh_recommended_events |
| short form: rre |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /family_battle_reset_week_update

| family_battle_reset_week_update | 
| description: |
| short form: fbrwu |

===

### /gain_family_honor [number]

| gain_family_honor | 
| description: |
| short form: gfh |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /cross_world [number]

| cross_world | 
| description: |
| short form: cw |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /countdown_msg [start_tim] [time_seconds] [msg]

| countdown_msg | 
| description: Countdown Msg |
| short form: cdm |
| Values |
| start_tim | time_seconds | msg | |
|---|---|---|
| number | number | rest_input | |
|---|---|---|
| | | 

===

### /show_countdown_msg

| show_countdown_msg | 
| description: Show Countdown Msg |
| short form: show_cdm |

===

### /del_countdown_msg

| del_countdown_msg | 
| description: Delete Countdown Msg |
| short form: del_cdm |

===

### /show_countdown_msg [number]

| show_countdown_msg | 
| description: Show Countdown Msg |
| short form: show_cdm |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /disband_family [name]

| disband_family | 
| description: |
| short form: df |
| Values |
| name | |
|---|---|---|
| word | |
|---|---|---|
| | | 
| short form: transport_to_npc |
| Values |
| name | |
|---|---|---|
| value | |
|---|---|---|
| | | 
| short form: transport_to_npc |
| Values |
| name | |
|---|---|---|
| number | |
|---|---|---|
| | | 
| short form: tpnpc |
| Values |
| name | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /reload_function_switch

| reload_function_switch | 
| description: reload function switch ini |

===

### /jail [given_name] [buff_id] [buff_time] [node_id] [gateway_id]

| jail | 
| description: jail character |
| short form: set_elf_star |
| Values |
| given_name | buff_id | buff_time | node_id | gateway_id | |
|---|---|---|
| elf_loc | star | |
|---|---|---|
| | | 
| short form: set_elf_star |
| Values |
| given_name | buff_id | buff_time | node_id | gateway_id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 
| short form: ses |
| Values |
| given_name | buff_id | buff_time | node_id | gateway_id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /change_gender [gender_id]

| change_gender | 
| description: change character gender |

===

### /trans_into_territory [territory_id] [area_id]

| trans_into_territory | 
| description: trans_into_territory |
| short form: tit |
| Values |
| territory_id | area_id | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /effect_map [effect_id] [duration]

| effect_map | 
| description: |
| short form: emap |
| Values |
| effect_id | duration | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /effect_map_time [map_id] [time] [effect_id]

| effect_map_time | 
| description: |
| short form: emtime |
| Values |
| map_id | time | effect_id | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /clone_monster_remote [id] [unit] [world_id] [node_id] [x] [y]

| clone_monster_remote | 
| description: Clone Monster At Player around |
| short form: cmr |
| Values |
| id | unit | world_id | node_id | x | y | |
|---|---|---|
| number | number | number | number | number | number | |
|---|---|---|
| | | 

===

### /set_territory_prepare_time [prepare_time]

| set_territory_prepare_time | 
| description: set_territory_prepare_time |
| short form: stpt |
| Values |
| prepare_time | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /player_room_release_node [number]

| player_room_release_node | 
| description: |

===

### /quiz_game_force_open [number]

| quiz_game_force_open | 
| description: |
| short form: qgfo |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /update_player_node_times [given_name] [node_id] [times]

| update_player_node_times | 
| description: |
| short form: upnt |
| Values |
| given_name | node_id | times | |
|---|---|---|
| word | number | number | |
|---|---|---|
| | | 

===

### /strenghten_equipments [number]

| strenghten_equipments | 
| description: |
| short form: se |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /gain_bind_gold [number]

| gain_bind_gold | 
| description: gain bind gold num |
| short form: gbg |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_node_pvp [number] [number]

| set_node_pvp | 
| description: set_node_pvp |
| short form: snp |
| Values |
| number | number | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /set_node_pvp_zone [number] [number]

| set_node_pvp_zone | 
| description: set_node_pvp_zone |
| short form: snpz |
| Values |
| number | number | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /event_showmsg [position] [rest_input]

| event_showmsg | 
| description: event trigger to show message |

===

### /set_node_exp_nb [number] [number]

| set_node_exp_nb | 
| description: set_node_exp_no_broadcast |
| short form: snen |
| Values |
| number | number | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /set_node_gold_nb [number] [number]

| set_node_gold_nb | 
| description: set_node_gold_no_broadcast |
| short form: sngn |
| Values |
| number | number | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /set_reborn_mob_pvp [min_left]

| set_reborn_mob_pvp | 
| description: set_reborn_mob_pvp |
| short form: srmp |
| Values |
| min_left | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /gain_coins

| gain_coins | 
| description: |
| short form: gco |
| number | number | |
|---|---|---|
| | | 

===

### /npc_talk,

| npc_talk | 
| description: |

===

### /blackout [textindex] [times]

| blackout | 
| description: |

===

### /bc_tran_msg [type] [msg] [screen_msg] [confirmmsg]

| bc_tran_msg | 
| description: broadcast transition msg |

===

### /node_black_out [target] [msg1] [time1] [msg2] [time2] [msg3] [time3]

| node_black_out | 
| description: play blackouting |

===

### /gain_eudemon_level [level]

| gain_eudemon_level | 
| description: gain eudemon level |
| short form: geul |
| Values |
| level | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /screen_effect [target] [effect_type] [effect_level] [effect_time]

| screen_effect | 
| description: screen effect |

===

### /gem_powerup [container_id] [loc] [level]

| gem_powerup | 
| description: gem level up |
| short form: gemup |
| Values |
| container_id | loc | level | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /play_cutscene [file_name] [target] [msg1]

| play_cutscene | 
| description: play cutscene |

===

### /add_memories [memories_id] [num]

| add_memories | 
| description: add memories |
| short form: amem |
| Values |
| memories_id | num | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /remove_memories [memoried_id]

| remove_memories | 
| description: remove memories |
| short form: rmem |
| Values |
| memoried_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /add_memoriesex [memories_id] [num] [extra_info]

| add_memoriesex | 
| description: add memories with extra |
| short form: amemex |
| Values |
| memories_id | num | extra_info | |
|---|---|---|
| number | number | rest_input | |
|---|---|---|
| | | 

===

### /open_fight [fight_tid] [duration] [one_side_number]

| open_fight | 
| description: open fight [fight id] [duration in sec] [persons need in one-side to open] |
| short form: of |
| Values |
| fight_tid | duration | one_side_number | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /set_lover_point_countdown_timer [number]

| set_lover_point_countdown_timer | 
| description: set_lover_point_countdown_timer |
| short form: lpcd |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /active_subweapon_to_character [given_name] [is_active]

| active_subweapon_to_character | 
| description: active subweapon to character |
| short form: aswtc |
| Values |
| given_name | is_active | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /select_family_leader2 [leader_id]

| select_family_leader2 | 
| description: |

===

### /switch_fight_time [switch]

| switch_fight_time | 
| description: |
| short form: sft |
| Values |
| switch | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /reset_daily_bonus [day_num]

| reset_daily_bonus | 
| description: |
| short form: rdb |
| Values |
| day_num | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /self_use_effect [effect_id] [duration] [stacks]

| self_use_effect | 
| description: let pc use stacks effect on self |
| short form: sue |
| Values |
| effect_id | duration | stacks | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /clear_fight [fight_id]

| clear_fight | 
| description: close and clear fight[fight_id] |
| short form: cf |
| Values |
| fight_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /family_diagram_vit [number]

| family_diagram_vit | 
| description: set player's diagram vit to [number] |
| short form: fdv |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /family_diagram_vit [number]

| family_diagram_vit | 
| description: set player's diagram vit to [number] |
| short form: family_diagram_progress |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 
| short form: fdp |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /family_diagram_node_state [node_id] [times]

| family_diagram_node_state | 
| description: set diagram[node_id] clear times to [times] |
| short form: fdns |
| Values |
| node_id | times | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /family_diagram_reset [reset_option

| family_diagram_reset | 
| description: reset diagram by [option] 0 only diagram group / 1 diagram group and progress |
| short form: fdr |
| Values |
| reset_option | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /begin_node_event [event_id]

| begin_node_event | 
| description: begin the event[event_id] at player's node |
| short form: bne |
| Values |
| event_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_hair_id [id]

| set_hair_id | 
| description: set character hair |
| short form: shid |
| Values |
| id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_face_id [id]

| set_face_id | 
| description: set character face |
| short form: sfid |
| Values |
| id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_hair_color [color]

| set_hair_color | 
| description: set character hair color |
| short form: shc |
| Values |
| color | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_skin_color [color]

| set_skin_color | 
| description: set character skin color |
| short form: ssc |
| Values |
| color | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_eyes_color [color]

| set_eyes_color | 
| description: set character eyes color |
| short form: sec |
| Values |
| color | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_helmet_color [color]

| set_helmet_color | 
| description: set character helmet color |
| short form: s0c |
| Values |
| color | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_clothes_color [color]

| set_clothes_color | 
| description: set character clothes color |
| short form: s1c |
| Values |
| color | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_cloak_color [color]

| set_cloak_color | 
| description: set character cloak color |
| short form: s2c |
| Values |
| color | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /update_closet [index]

| update_closet | 
| description: update current color to closet |
| short form: ucl |
| Values |
| index | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_spell_level [id] [level]

| set_spell_level | 
| description: set spell level |
| short form: spel |
| Values |
| id | level | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /add_class [id]

| add_class | 
| description: add class |

===

### /remove_class [id]

| remove_class | 
| description: remove class |
| short form: dcc |
| Values |
| id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_class_level [number]

| set_class_level | 
| description: set class level |
| short form: scl |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /get_license [number]

| get_license | 
| description: set license |
| short form: gel |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /remove_all_license

| remove_all_license | 
| description: remove all license |

===

### /set_all_spell_level [number]

| set_all_spell_level | 
| description: set all spell level |
| short form: sapl |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_node_np

| set_node_np | 
| description: set node np rate |
| short form: snn |
| number | number | |
|---|---|---|
| | | 

===

### /remove_family_emblem [number]

| remove_family_emblem | 
| description: remove family emblem |
| short form: rfe |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 
| short form: inside |
| Values |
| number | |
|---|---|---|
| class | level | |
|---|---|---|
| | | 
| short form: inside |
| Values |
| number | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /clear_cool_down_time

| clear_cool_down_time | 
| description: clear character's cool down time |
| short form: ccdt |

===

### /shop [shop_type] [npc_id] [level_min] [level_max]

| shop | 
| description: enter spell shop |

===

### /put_treasure [id] [amount]

| put_treasure | 
| description: put treasure at ground |

===

### /add_lottery_plus [value]

| add_lottery_plus | 
| description: add lottery plus |
| short form: alp |
| Values |
| value | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /reload_elf_lottery_db

| reload_elf_lottery_db | 
| description: reload elf lottery db |
| short form: reld |

===

### /lottery_week_update [day] [hour] [min]

| lottery_week_update | 
| description: reload week update |
| short form: lwu |
| Values |
| day | hour | min | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /clear_lover_disband

| clear_lover_disband | 
| description: clear lover disband |

===

### /super_clear_bag_item

| super_clear_bag_item | 
| description: super_clear_bag_item |

===

### /making_item [operation_type] [making_item_way_id]

| making_item | 
| description: learn new making item way |
| short form: mi |
| Values |
| operation_type | making_item_way_id | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /making_item [operation_type] [type] [exp]

| making_item | 
| description: add making item type exp |
| short form: mi |
| Values |
| operation_type | type | exp | |
|---|---|---|
| word | number | number | |
|---|---|---|
| | | 

===

### /add_hate [caster_id] [target_id] [target_type]

| add_hate | 
| description: add hate to life |
| short form: ah |
| Values |
| caster_id | target_id | target_type | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /achievement_screen_message [achieve_id] [ownder_id]

| achievement_screen_message | 
| description: show screen message when get achievement point |

===

### /active_subweapon [number]

| active_subweapon | 
| description: active subweapon |
| short form: asw |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 
| short form: confirmmsg |
| Values |
| number | |
|---|---|---|
| rest_input | |
|---|---|---|
| | | 

===

### /get_lover_point [number]

| get_lover_point | 
| description: get lover point |
| short form: glp |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_lover_level [number]

| set_lover_level | 
| description: set_lover_level |
| short form: sll |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /expand_elf_bank [number]

| expand_elf_bank | 
| description: expand_elf_bank |
| short form: eeb |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /add_attr_value [word] [number]

| add_attr_value | 
| description: add attr value |
| short form: atv |
| Values |
| word | number | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /reset_daily_mission

| reset_daily_mission | 
| description: reset daily mission |

===

### /transfer_name [given_name]

| transfer_name | 
| description: transport to character with nickname |
| short form: tn |
| Values |
| given_name | |
|---|---|---|
| word | |
|---|---|---|
| | | 

===

### /gain_dust [number]

| gain_dust | 
| description: gain dust num |
| short form: gd |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /reset_group_reward

| reset_group_reward | 
| description: reset group reward |

===

### /open_fortune_bag [fortune_bag_id] [times] [drop_rate]

| open_fortune_bag | 
| description: |
| short form: ofb |
| Values |
| fortune_bag_id | times | drop_rate | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /modify_durability [number] [number]

| modify_durability | 
| description: |
| short form: md |
| Values |
| number | number | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /captcha_wordtype_noise [number] [wordtype]

| captcha_wordtype_noise | 
| description: |
| short form: cawn |
| Values |
| number | wordtype | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /gainpp [pptype] [number]

| gainpp | 
| description: |

===

### /clear_spell

| clear_spell | 
| description: clear player all spell |

===

### /change_weapon_type [number] [number]

| change_weapon_type | 
| description: change my main or second weapon type |
| short form: cwt |
| Values |
| number | number | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /weapon_strengthen [number] [number] [number] [number]

| weapon_strengthen | 
| description: |
| short form: wpns |
| Values |
| number | number | number | number | |
|---|---|---|
| number | number | number | number | |
|---|---|---|
| | | 

===

### /gain_fragment [number]

| gain_fragment | 
| description: |
| short form: gf |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /clear_advenchants

| clear_advenchants | 
| description: clear adventure enchants |

===

### /set_elf_emblem_attr [number] [number] [number]

| set_elf_emblem_attr | 
| description: |
| short form: seea |
| Values |
| number | number | number | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /reset_timer [reset_type]

| reset_timer | 
| description: active reset time |
| short form: rtt |
| Values |
| reset_type | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /close_node [number] [number]

| close_node | 
| description: |

===

### /set_survival_ghost [name] [survivalmode]

| set_survival_ghost | 
| description: set character survival mode |
| short form: ssg |
| Values |
| name | survivalmode | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /set_personal_log_id [number]

| set_personal_log_id | 
| description: |
| short form: spli |
| Values |
| number | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /reload_trace_event

| reload_trace_event | 
| description: |
| short form: rlte |

===

### /update_rank_info [type] [reset]

| update_rank_info | 
| description: |
| short form: uri |
| Values |
| type | reset | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /gm_talk [charname] [message]

| gm_talk | 
| description: |
| short form: gt |
| Values |
| charname | message | |
|---|---|---|
| word | rest_input | |
|---|---|---|
| | | 

===

### /gm_talk_node [message]

| gm_talk_node | 
| description: |

===

### /check_player_pp [charname]

| check_player_pp | 
| description: |
| short form: cpp |
| Values |
| charname | |
|---|---|---|
| word | |
|---|---|---|
| | | 

===

### /close_shop [number] [number]

| close_shop | 
| description: |

===

### /reset_week_achievement [charname] [type]

| reset_week_achievement | 
| description: |
| short form: rwa |
| Values |
| charname | type | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /show_player_node_times [given_name] [node_id]

| show_player_node_times | 
| description: |
| short form: spnt |
| Values |
| given_name | node_id | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /reset_daily_achievement [charname]

| reset_daily_achievement | 
| description: |
| short form: rda |
| Values |
| charname | |
|---|---|---|
| word | |
|---|---|---|
| | | 

===

### /sky_tower_open_state [tower_id] [type] [param]

| sky_tower_open_state | 
| description: |
| short form: stos |
| Values |
| tower_id | type | param | |
|---|---|---|
| number | number | number | |
|---|---|---|
| | | 

===

### /check_achievement_group [charname] [id]

| check_achievement_group | 
| description: |
| short form: cag |
| Values |
| charname | id | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /bgw_account_clear [account_name] [accoount_id]

| bgw_account_clear | 
| description: |
| short form: bac |
| Values |
| account_name | accoount_id | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /reset_account_achievement [player_name]

| reset_account_achievement | 
| description: |
| short form: raa |
| Values |
| player_name | |
|---|---|---|
| word | |
|---|---|---|
| | | 

===

### /accept_mission [mission_id]

| accept_mission | 
| description: |
| short form: am |
| Values |
| mission_id | |
|---|---|---|
| number | |
|---|---|---|
| | | 

===

### /set_friend_level [name] [level]

| set_friend_level | 
| description: |
| short form: sfrl |
| Values |
| name | level | |
|---|---|---|
| word | number | |
|---|---|---|
| | | 

===

### /update_health_time [online_time] [offline_time]

| update_health_time | 
| description: |
| short form: uht |
| Values |
| online_time | offline_time | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /check_player_lottery [charname]

| check_player_lottery | 
| description: |
| short form: cpl |
| Values |
| charname | |
|---|---|---|
| word | |
|---|---|---|
| | | 

===

### /set_teach_mode [teach_type] [teach_step]

| set_teach_mode | 
| description: |
| short form: stm |
| Values |
| teach_type | teach_step | |
|---|---|---|
| number | number | |
|---|---|---|
| | | 

===

### /shut_down

| shut_down | 
| description: shut down |

===

### /kick_out [player_ip] [reason]

| kick_out | 
| description: kick out player |

===

### /exchange items [char id] [node_id] [pin] [size] [item_id] [item_number]

| exchangeitems | 
| description: ... |
| short form: exchange items |
| Values |
| char id | node_id | pin | size | item_id | item_number | |
|---|---|---|
| number | number | word | number | rest_input | |
|---|---|---|
| | | 

===

### /family_set_emblem_fail [char id] [node_id]

| family_set_emblem_fail | 
| description: |

===

### /trace_result [receiver_id] [target_id] [node_id]

| trace_result | 
| description: |

===

### /do_aw_put_treasure [receiver_id] [item_id] [node_id] [amount] [x] [y]

| do_aw_put_treasure | 
| description: |

===

### /update_prestige [ch_id] [node_id] [prestige_id] [level] [exp]

| update_prestige | 
| description: |

===

### /captcha_punish [ch_id] [punish_type] [duration]

| captcha_punish | 
| description: |

===

### /gm_tool_login_result [account] [account_id] [privilege]

| gm_tool_login_result | 
| description: |

===

### /gm_tool_ban_result [ch_name] [gm_name]

| gm_tool_ban_result | 
| description: |

===

### /get_net_cafe_vip [ch_id] [net_cafe_vip] [buff_type]

| get_net_cafe_vip | 
| description: |

===

### /sp_itemmall_req_buy [ch_id] [coin_type] [total_point] [item_id] [amount] [item_color] [due_date_time] [mall_group] [mall_item_index] [item_amount]

| sp_itemmall_req_buy | 
| description: |

===

### /check_communicate_lock_ret [ch_id] [type] [10]

| check_communicate_lock_ret | 
| description: check communicate lock result |

===

### /update_health [ch_id] [online_time] [offline_time]

| update_health | 
| description: |

===

### /health [ch_id] [health_rule] [online_time] [offline_time]

| health | 
| description: |

===

### /get_daily_bonus [ch_id] [daily_state] [request_id]

| get_daily_bonus | 
| description: |