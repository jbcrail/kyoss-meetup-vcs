!SLIDE
## And the rest... ##

!SLIDE commandline incremental smaller

	$ svn help
	Available subcommands:
	   add
	   blame (praise, annotate, ann)
	   cat
	   changelist (cl)
	   checkout (co)
	   cleanup
	   commit (ci)
	   copy (cp)
	   delete (del, remove, rm)
	   diff (di)
	   export
	   help (?, h)
	   import
	   info
	   list (ls)
	   lock
	   log
	   merge
	   mergeinfo
	   mkdir
	   move (mv, rename, ren)
	   propdel (pdel, pd)
	   propedit (pedit, pe)
	   propget (pget, pg)
	   proplist (plist, pl)
	   propset (pset, ps)
	   resolve
	   resolved
	   revert
	   status (stat, st)
	   switch (sw)
	   unlock
	   update (up)

!SLIDE commandline incremental smaller

	$ git help
	The most commonly used git commands are:
	   add        Add file contents to the index
	   bisect     Find by binary search the change that introduced a bug
	   branch     List, create, or delete branches
	   checkout   Checkout a branch or paths to the working tree
	   clone      Clone a repository into a new directory
	   commit     Record changes to the repository
	   diff       Show changes between commits, commit and working tree, etc
	   fetch      Download objects and refs from another repository
	   grep       Print lines matching a pattern
	   init       Create an empty git repository or reinitialize an existing one
	   log        Show commit logs
	   merge      Join two or more development histories together
	   mv         Move or rename a file, a directory, or a symlink
	   pull       Fetch from and merge with another repository or a local branch
	   push       Update remote refs along with associated objects
	   rebase     Forward-port local commits to the updated upstream head
	   reset      Reset current HEAD to the specified state
	   rm         Remove files from the working tree and from the index
	   show       Show various types of objects
	   status     Show the working tree status
	   tag        Create, list, delete or verify a tag object signed with GPG

!SLIDE commandline

	$ git add -p
	# interactively add hunks of content to staging area

	$ git commit --amend
	# amend the message of most recent commit

	$ git log --oneline --graph
	# show history with shortened commit messages

	$ git grep <regexp>
	# search working directory for regexp

	$ git grep <regexp> $(git rev-list --all)
	# search all commits on current branch for regexp
