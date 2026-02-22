# Obsidian Modified Plugin
> An Obsidian plugin that stamps on the current date to a markdown frontmatter property of your choosing.

At work I have my [Obsidian](https://obsidian.md/) daily note set up with a [base](https://help.obsidian.md/bases) to keep track of what tickets I've been working on. I initially tried filtering the notes using the Modified metadata property, but if I work on a ticket on two consecutive days, then modification to the note on the second day would update this property and thus remove it from the view of the first day.

After messing around with Agentic coding tools like Claude Code and Codex, I realised that this is a problem that I could totally solve with minimal time investment on my part. I've published the code for this plugin [here](https://github.com/MattPChoy/Experiments/tree/main/ObsidianModifiedPlugin), which you'll need to install as a local plugin [instructions]().

## Getting Started
To make use of this plugin, follow these steps (assuming that you nave node.js installed).

1. Clone down the repository using Git or download as a .zip file.
2. Navigate to the `ObsidianModifiedPlugin` directory.
3. Install the dependencies using `npm i` and run `npm run build` to create the main.js
4. In Obsidian, open the Community Plugins section in settings, and click on the folder icon to open the plugins folder.
5. Copy the built code (folder should contain a main.js) into the Obsidian plugins folder.
6. Restart obsidian, navigate back to the plugins settings page and enable the plugin.