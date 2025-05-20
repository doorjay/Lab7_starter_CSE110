# Dorjé Pradhan

## Check Your Understanding 1
I think that putting our automated tests woulf be best done wihtin a Github action that runs whenever code is pushed.
This ensures that everytime you push code, it gets checked right then and there. It allows you to incrementally test
specific parts of your program automatically instead of havnig to do it manually or all at once when you think you're
"done". 

## Check Your Understanding 2
No. A unit test would be what you'd use to check expected output

## Check Your Understanding 3 
Navigation mode audits immediately after performing a full page load. It reloads the page and measures metrics that depend on navigating. It's better at capturing some initial performance issues when your site first renders
Snapshot mode does its audit in the sites *current state* without reloading. It is looking more at accessibility and other static criteria in the specific UI state. Since it doesn't load nything, most load-based performance metrics will not be able to be measured. 

## Check Your Understanding 4
According to the lighthouse results, a few things we should change are:
1. "properly size images"
2. "Serve images in next-gen formats"
3.  Add a <meta name="viewport"> tag with width or initial-scale. 
There were a few more suggestions like adding the lang attribute, but you only asked for three