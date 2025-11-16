# lingua_robot.cr
Web-API for www.linguarobot.io english dictionary API providing an access to data of over 800 000 english lexical entries, such as words, phrasal verbs, multi-word expressions.

## Example
```cr
require "./lingua_robot"

lingua_robot = LinguaRobot.new
entry = lingua_robot.get_an_entry(word="perfection")
puts entry
```
