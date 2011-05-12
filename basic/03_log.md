!SLIDE commandline incremental smaller

	$ svn log
	------------------------------------------------------------------------
	r3 | joseph | 2008-03-17 21:52:11 -0400 (Mon, 17 Mar 2008) | 1 line

	third
	------------------------------------------------------------------------
	r2 | joseph | 2008-03-15 16:40:33 -0400 (Sat, 15 Mar 2008) | 1 line

	second
	------------------------------------------------------------------------
	r1 | joseph | 2008-03-15 10:31:28 -0400 (Sat, 15 Mar 2008) | 1 line

	first
	------------------------------------------------------------------------

	$ git log
	commit ca82a6dff817ec66f44342007202690a93763949
	Author: Joseph Crail <xyz@gmail.com>
	Date:   Mon Mar 17 21:52:11 2008 -0400

	    third

	commit 085bb3bcb608e1e8451d4b2432f8ecbe6306e7e7
	Author: Joseph Crail <xyz@gmail.com>
	Date:   Sat Mar 15 16:40:33 2008 -0400

	    second

	commit a11bef06a3f659402fe7563abf99ad00de2209e6
	Author: Joseph Crail <xyz@gmail.com>
	Date:   Sat Mar 15 10:31:28 2008 -0400

	    first
