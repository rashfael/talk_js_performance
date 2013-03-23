{spawn} = require 'child_process'
os = require 'os'



task 'run', 'Launch the notes-server', ->
		spawn 'node', ['plugin/notes-server/index.js'], {stdio: 'inherit'}


task 'watch', 'Watches index.jade', ->
	spawn 'jade', ['-w', 'index.jade'], {stdio: 'inherit'}
	spawn 'node', ['plugin/notes-server/index.js'], {stdio: 'inherit'}
