honestly I would just link to the tmux cheatsheet website




#general gist
	divides the terminals into windows and panes to multitask easier
#leader key
	all shortcuts must be preceded by the leader key to trigger tmux commands
	the default leader key is [CTRL+b]
	##configuring the default key
	the default leader key is dumb and requires some real finger acrobatics to activate
	most people change to [CTRL+a] (see config below for steps to change it)
#terminology
	1) panes
		panes are division of a window(screen)
	2) windows
		entirely new screens
	3) sessions
		all windows and panes are saved to sessions. 
		when you quit you can just jump back in to where you left off exactly as it is. panes and windows and directories will be restored as previously saved
#config
	
#Cheat Sheet
	##shortcut keys
			ctrl+d closes the current focused terminal
		##tmux shortcuts
			press the leader key in conjunction with the keys below
			###panes navigation
				%
				creates a vertical division on the screen
				
				" 
				creates a horizontal division on the screen
				
				;
				toggle to previous pane
				
				q (0-9)
				switch to specific pane by index
				
				z
				toggle zoom to focused pane
				
				
	##commands

