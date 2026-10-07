this is about restoring and reverting a text.
restoring is done after add command.
and revert command is applicable after commitment of the msg 
and after revert command we have to again commit the msg.
for restore: git add .
             git restore filename --staged
             git restore filename.
             git commit -m "important note"
             git push
for revert : git add .
             git commit -m "important note"
             git revert #code
             git commit -m "commit again
             git push
            
