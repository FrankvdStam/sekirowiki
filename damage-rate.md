---
title: Locational Damage (Damage Rate)
description: 
published: true
date: 2025-03-08T10:54:14.137Z
tags: dmgrate, partsatkparam, hitbox, hurtbox
editor: markdown
dateCreated: 2025-03-08T07:22:08.738Z
---

# Locational Damage (Damage Rate)
Internally, the enemy’s hitbox (also sometimes referred to as hurtbox) is divided up into different parts. All of the parts have a Damage Rate and a Stamina Damage Rate that determine how much damage will be dealt to the boss when that part is hit. HP and Poise damage are controlled by the Damage Rate and Posture damage is controlled by the Stamina Damage Rate. 

Most enemy parts will have the standard rate of 1.00, where damage is dealt normally, while others may have higher or lower rates. Let’s take an in-game example: Guardian Ape’s head has a Stamina Damage Rate of 2.00 and the default 1.00 Damage Rate. The rest of his body parts have 1.00 for both rates. Guardian Ape's head will therefore take double posture damage and normal poise and HP damage. He will take regular Posture, HP and Poise damage on the rest of his body.

There are also instances where enemies will have a Damage Rate lower than 1.00 and thus take reduced damage if you hit them on that part. Bull has a 0.40 Damage Rate (both types) on his body, which means that any attack to his body will deal only 40% of the normal damage. His head however, has a Damage Rate (both types) of 1.20, which means that hitting his head does 3 times as much damage of all 3 dmg types as hitting any other part of his body.