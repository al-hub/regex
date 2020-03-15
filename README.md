# regex


remove with 
( )	{ }	[ ]	⟨ ⟩
Round brackets	Curly brackets	Square brackets	Angle brackets
https://stackoverflow.com/questions/17522855/how-to-remove-square-brackets-and-any-text-inside

:%s/<[^>]*>//gc 
