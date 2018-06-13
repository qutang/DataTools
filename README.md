Read Me

Record Format

1. This tool is based on the Apple app TimeKeeper
2. start with ‘start’ or ’s’: s [action]
3. end with ‘end’ or ‘e’, you can omit the verb
4. if doing things by sequence, you can omit the end action
	       e.g.			    
	            s walk
	            end walk
              s run

         or
              s walk
              start run
5. please keep track of when you take off the sensor
6. the parser works according to time sequence order, so reverse the text file generated by the app before use it.

Tool Instruction:

1. For simply parsing the raw file to formatted annotation file, use command:
	STANDARD/CATEGORIZE [Original File Path] [Formatted Annotation File Path]
2. To split the file by hour and store them in separate folders of sensor dataL
	STANDARD/CATEGORIZE [Original File Path] [Formatted Annotation File Path] split
3. CATEGORIZE for categorize the raw activities to Sedentary, Ambulation or Other
