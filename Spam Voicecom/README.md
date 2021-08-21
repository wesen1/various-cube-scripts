# Spam: Voicecom

# Description
This script allows you to send random voicecom messages in a configurable interval.

# Installation
Copy the spam-voicecom.cfg file to your AssaultCube scripts folder.

# Usage

* Use `spamVoicecom <number of messages> <wait time between messages in milliseconds` to spam voicecom messages.

Note:

There are limits on how many messages you are allowed to send in a certain interval.

- Client :https://github.com/wesen1/AC/blob/752950989b4e286459ca9aee3d61a868d7b20fa4/source/src/audiomanager.cpp#L422
- Server: https://github.com/wesen1/AC/blob/752950989b4e286459ca9aee3d61a868d7b20fa4/source/src/server.cpp#L2950

You can disable your client side limit to hear the messages yourself in very short intervals, but it still won't affect other players because the server detects the voicecom messages as spam.
