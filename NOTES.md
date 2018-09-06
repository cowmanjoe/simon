# Notes

This is the final version for the easy task. My main difficulty for this part was figuring out how to keep the timing of the notes while delaying the echo until 2.5 seconds after the last one. I ended up having to make an array of objects called echos that stored the note and unix millisecond timestamp. When 2.5 seconds passed since the last note, I would play the notes stored in the echos array using the timing offsets.  
