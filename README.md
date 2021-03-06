# Kodi Skill for Mycroft AI
## kodi-skill
Control KODI open source media center with Mycroft

## Description 
Utilize the kodi API and Python library for controlling the KODI open source media center with Mycroft.
## Examples 
* "turn kodi notifications on"
* "turn kodi notifications off"
* "move the cursor up / down / left / right / back / select / cancel" (Conversational Context)
* "play film Guardians of the galaxy"
* "play the movie spider man homecoming"
* "pause the movie"
* "re-start the movie"
* "stop the movie"
* "show the movie information"
* "hide the movie information"
## Conversational Context
* If mycroft.ai locates more than one movie that matches your request it will permit you to itterate through your requests
* using conversational context.
* eg. "hey mycroft:"
* Request: "play the move Iron Man"
* Response: "I have located 3 movies with the name Iron Man, would you like me to list them?"
* Request: "yes" / "no"
* Response: "Iron Man, to Skip, say Next, say play, to play, or Cancel, to stop"
* Request: "next" / "skip"
* Response: "Iron Man 2"
* Request: "play" / "select"
* Response: "o-k, attempting to play, Iron Man 2"
## Credits
PCWii
## Require 
Tested on platform_picroft (others untested) 
## Other Requirements
- [Mycroft](https://docs.mycroft.ai/installing.and.running/installation)
- kodipydent
## Further Reading
- [KODI API](https://kodi.wiki/index.php?title=JSON-RPC_API/v6)
## Installation Notes
- Configure Kodi to “allow remote control via HTTP”, under the Kodi settings:services
- Configure Kodi to “allow remote control from applications on other systems”, under the Kodi settings:services
- Under Kodi settings:services note the port number (8080)
- Configure home.mycroft.ai to set your kodi instanace ip address and port number
- username and password currently not supported
