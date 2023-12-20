# A Comprehensive List of Prompts and Responses in 'Blather Round!
A list of all the words, sentences, and phrases used by the game.

___


Hello! The title kind of explains it all. This was a project for school, telling me to analyse how games used JSON files, JET files, etc. to store and retrieve data, and so I did it with 'Blather Round! If you guys want more ripped JSONs from games, contact me at . See you guys later!

___


Psst! Protip: You can use this to cheat in 'Blather Round by using the adjectives to narrow down what the prompt is! Here is a jq query you can run online with a service like [JQPlay](https://jqplay.org): `.content[]|select(.tailoredWords as $adj|all("small", "meme"; IN($adj[].word)))|.password`. That should return `"Grumpy Cat"`
