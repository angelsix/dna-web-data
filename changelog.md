## Change Log

### Version 1.0.4

- Fix include paths without file extension not working when filename has . in the name
- Fixed infinite refresh bug if URL has # in it
- Added ability to use relative `source` paths in **dna.live.config** files located on websites
- Added `new config` command to generate a fully filled out default **dna.config** file

### Version 1.0.3

- Process and Close won't spin up Live Servers
- Fix Live Server Auto-Refresh not always working
- Scss Files can not specify Output Style and Generate Source Map

### Version 1.0.2

- Live editing of dna.config file support without restarting DnaWeb
- Allow . in Live Variable/Template names
- Allow includes between engine types without file extension
- dna.config files now detects changes without having to restart

### Version 1.0.1.6

- Add Live Data Sources support for Live Variables and Live Templates
- Add Cache Path setting
- Add lots of commands into console

### Version 1.0.1.5

- Added LiveServer support so basic websites can be served
- Added Auto-Refresh support to LiveServers
- Fixed html include statement not finding partial files starting with _

### Version 1.0.1.4

- Added outputPath configuration setting to set default output path of all files, not just sass files
- Removed sassPath (replaced with outputPath)
- Added support for placing configuration files in any folder between the file and the root monitor path for tiered configurations
- Removed the need to specify include extensions if engine only monitors for one file type (i.e. including .dhtml files no longer needs the .dhtml in the include name)
- Removed the need to specify output extensions. If no extension is provided, the output extension because the engines default type (for example .html for the Html Engine)

### Version 1.0.1.3

- Changed Html engine extension to .dhtml
- Auto-set files starting with _ to partial files to match Sass behaviour

### Version 1.0.1.2

- Fixed bug in regex detecting Sass import paths

### Version 1.0.1.1

- Support for Sass Live processing
- Lots of speed improvements
- More dna.config configuration options including:
  - sassPath - specify a path for Sass output files
  - logLevel - The level of detail to output in the log
- Detecting already processed and already generated files and skipping them

