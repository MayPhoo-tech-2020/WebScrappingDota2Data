# WebScrappingDota2Data
In this project, I retrieve dota2 data with json format by using web scrapping technique.

#Sample retrieved data\n
"hero_name":"Earthshaker",
      "image":"https://cdn.cloudflare.steamstatic.com/apps/dota2/images/heroes/earthshaker_full.png?v=6120190?v=6120190",
      "bio":"Like a golem or gargoyle, Earthshaker was one with the earth but now walks freely upon it. Unlike those other entities, he created himself through an act of will, and serves no other master. In restless slumbers, encased in a deep seam of stone, he became aware of the life drifting freely above him. He grew curious. During a season of tremors, the peaks of Nishai shook themselves loose of avalanches, shifting the course of rivers and turning shallow valleys into bottomless chasms. When the land finally ceased quaking, Earthshaker stepped from the settling dust, tossing aside massive boulders as if throwing off a light blanket. He had shaped himself in the image of a mortal beast, and named himself Raigor Stonehoof. He bleeds now, and breathes, and therefore he can die. But his spirit is still that of the earth; he carries its power in the magical totem that never leaves him. And on the day he returns to dust, the earth will greet him as a prodigal son.",
      "roles":[
         "Melee",
         "Support",
         "Initiator",
         "Disabler",
         "Nuker"
      ],
      "stats":{
         "intelligence":"16 + 1.80",
         "agility":"12 + 1.40",
         "strength":"22 + 3.70",
         "attack":"27 - 37",
         "speed":"310",
         "defense":"3.68"
      },
      "statsByLevel":{
         "level":[
            "25",
            "15",
            "1"
         ],
         "hit_points":[
            "2,635",
            "1,552",
            "568"
         ],
         "mana":[
            "1,030",
            "536",
            "208"
         ],
         "damage":[
            "158-168",
            "101-111",
            "49-59"
         ],
         "armor":[
            "11",
            "6",
            "4"
         ],
         "sight_range":"1800 / 800",
         "attack_range":"150",
         "missile_speed":"N/A"
      },
      "abilitis":[
         {
            "name":"Fissure",
            "description":"Slams the ground with a mighty totem, creating an impassable ridge of stone while stunning and damaging enemy units along its line.",
            "image":"https://cdn.cloudflare.steamstatic.com/apps/dota2/images/abilities/earthshaker_fissure_hp2.png?v=6120190",
            "video":"http://www.youtube.com/embed/vTbNwc5Tqwc?hd=1&rel=0",
            "mana_cost":" Mana Cost: 110/130/150/170",
            "cooldown":" Cooldown: 21/19/17/15",
            "others":{
               "ability":"Point Target",
               "affects":"Enemy Units",
               "damage_type":"Magical",
               "pierces_spell_immunity":"No",
               "damage":"110 / 160 / 210 / 260",
               "fissure_duration":"6.5 / 7 / 7.5 / 8",
               "stun_duration":"1 / 1.25 / 1.5 / 1.75"
            }
         },
         {
            "name":"Enchant Totem",
            "description":"Empowers Earthshaker's totem, causing it to deal extra damage and have 75 bonus attack range on the next attack.",
            "image":"https://cdn.cloudflare.steamstatic.com/apps/dota2/images/abilities/earthshaker_enchant_totem_hp2.png?v=6120190",
            "video":"http://www.youtube.com/embed/OkSsLAN7mbk?hd=1&rel=0",
            "mana_cost":" Mana Cost: 35/40/45/50",
            "cooldown":" Cooldown: 5",
            "others":{
               "ability":"No Target",
               "affects":"Enemy Units",
               "damage":"0 / 0 / 0 / 0"
            }
         },
         {
            "name":"Aftershock",
            "description":"Causes the earth to shake underfoot, adding additional damage and stuns to nearby enemy units when Earthshaker casts his abilities.",
            "image":"https://cdn.cloudflare.steamstatic.com/apps/dota2/images/abilities/earthshaker_aftershock_hp2.png?v=6120190",
            "video":"http://www.youtube.com/embed/2xcM8xccDIs?hd=1&rel=0",
