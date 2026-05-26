# TF2Sounds
Here's some baseline rules I'll check for here (though I may deny a PR for any reason I see fit):

- MUST be MP3 files (for now), the files are cached this way and it'd be too expensive in terms of delay to convert on the fly
- Files must be named with only alphanumeric characters, the existing files here may break this rule however this will be updated in the future.
- Sounds cannot contain slurs or other inappropriate content

# TTS Commands
Here is a list of commands available on the TTS bot:

- !voice [voicename] | changes the current tts voice you're using. "voicename" options: ("dectalk", "espeak", "sam")
- !speed [voicespeed] | changes the speed at which the tts voice speaks when you talk. Only works with espeak and sam, dectalk requires you to use phoneme commands.
- !pitch [voicepitch] | changes the pitch at which the tts voice speaks when you talk. Only works with espeak and sam, dectalk requires you to use phoneme commands.
- !rqs [YouTube URL] | adds a specified YouTube URL to the song queue, only enabled on special occasions.
- !play [Sound] | plays the sound at the specified path on this GitHub repository.
- !stfu | exclusive to Festivized Killstreak Idiot, stops all speaking TTS voices.
- !okitsannoyingnow | exclusive to Festivized Killstreak Idiot, enables a spam filter.
- !skip | exclusive to Festivized Killstreak Idiot, skips the current song and goes to the next one.
- !timeout [playertotimeout] | exclusive to Festivized Killstreak Idiot, this will prevent a specified player's messages from being spoken by the program.

# TTS Shortcuts
Here is a list of TTS shortcuts to make the TTS bot say specific information about you:

- {/health} | makes the TTS say your current health.
- {/deaths} | makes the TTS say your current deaths on the scoreboard.
- {/sid32} | makes the TTS say your 32bit integer SteamID.
- {/name} | makes the TTS say your Steam Name.
- {/ping} | makes the TTS say your current ping.

DISCLAIMER: This is NOT a typical bot, I and only I am in control of my player and I have not modified the game in any way to achieve this functionality, there is no code injected in the game it is all an external program reading my TF2 console output using the con_logfile command + rcon with g15_dumpplayer for other information. By TTS bot I refer to a program that reads player text and outputs speech.
