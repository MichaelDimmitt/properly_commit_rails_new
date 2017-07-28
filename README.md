![decomposing_scaf](https://user-images.githubusercontent.com/11463275/28737691-b0109d00-73bd-11e7-8b3a-c4307364ab04.png)
<pre>
bundle --> Gemfile
rails s --> config/, bin/
rake db:migrate --> db/
rake --> Rakefile, test/

beginners can match commands to files!
cool lightning talk? or dumb?
</pre>

## Step 1 decompose a Rails scaffold 
<pre>
That project can be found here https://github.com/MichaelDimmitt/g-r-s-t-r-w-bts
obviously this was not productive at all. no new features were built.
But one day I thought, what would happen if I just sledgehammered a `rails new` scaffold? 
My plan was delete the files until all the commands broke. Removing bloat that I did not understand.
I never thought that individual commands would break as additional files were deleted.

My Rails story has been, do commands--> magic happens!
An unexpected discovery from this project: you can match commands to files!
</pre>
## Step 2 Commit a Rails scaffold correctly.
<pre>
Since I can match commands to files

Committing the initial project scaffold should not be one commit 
and as a commit message ```commit -m "initial project scaffold;```

Instead, a scaffold should consist of adding files 
and eluciadating the commands that require these files!
</pre>
### Buildings dont just happen.<br>You cant build at the top until you understand which ladders get you where.
![rails_image](https://user-images.githubusercontent.com/11463275/29998548-f474fa22-8ffb-11e7-9713-6b55da849db7.png)

