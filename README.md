# BLUAlert
Updates to Windower's BLU Alert Addon because I don't know how to github.

Are you sick and tired of watching your chat log like a hawk when hunting for new Blue Magic spells, waiting for the monster to use that one ability? Are you sick and tired of going AFK until the monster dies, losing out on precious time that could be better spent in other areas of FFXI?

If so then your savior is here! BLUAlert!

This add-on will monitor monster abilities for Blue Magic spells that you don't know. When one is detected it will write a message into chat and play a sound to notify you.

Now you can relax while you AFK with the knowledge that you'll be able to come back and kill the monster right after it uses that one ability!

My update includes: 
  - Checking for if the player's main job is set to BLU, and then if so, it will play the alert sound for unknown magic used
  - Checking for player name and then playing a separate alert sound when the addon detects "[playername] learns" so signal when you've learned a spell. It is not 100% accurate; I suspect that the end-of-battle chat dump can be too large depending on RoE completions, etc., and sometimes it does not display the message or trigger the sound.
