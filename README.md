# Serenity

An easy system for generating (and local development of) static sites, using variables and templates.

This is a WIP and it will be a while until it's stable for proper use. Please use with caution!


## Install

```bash
$ npm install -g serenity
```

Note: may require sudo to install globally!

## Usage
```bash
$ serenity
```

Running the serenity command will immediately start watching the current directory and build the site within ./_site. It will also serve the site on localhost:4000.

##Options
<table>
	<tr>
		<th>Short</th><th>Long</th><th>Description</th>
	</tr>
	<tr>
		<td></td><td>--no-server</td><td>If specified, no server will be started and the process will exit after generating the site.</td>
	</tr>
	<tr>
		<td>-p</td><td>--port</td><td>Number. Specify the port for the server to use, defaults to 4000.</td>
	</tr>
	<tr>
		<td>-c</td><td>--convert</td><td>Boolean. Default false. This will attempt to convert a Jekyll static site into a Templr one. Very beta. BEWARE!</td>
</table>

Configuration options can also be specified in a file named serenity.js in the root of your directory. Usage and options for this will be documented soon.
