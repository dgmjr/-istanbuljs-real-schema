---
permalink: index.htm
---

# schema.place
## Generate and optionally publish JSON and YAML schemas from existing Java, JavaScript, TypeScript, or C# code and use them to validate your JSON and YAML files

## But why?  

### There are plenty of tools that do this already!
True!  But some projects define their "schemas" in terms of a data structure or class definition.  Now, you could just write your configuration file in the primary OO language you're using and be done with things.  But some tools are also written to be versatile and accept other formats like JSON or YAML.  That can be fine, but doesn't give you any validation of your file against the schema until the program actually tries to load it (i.e., you see your mistake at runtime).  With a schema for the file, it can be validated at code time by the IDE as well as offer code completion hints.

### Why shouldn't I just generate it myself and host it with [SchemaStore](https://www.schemastore.org)
You totes can!  But their site is intended for "commonly known JSON file formats."  If you're creating a schema for your own little project or anything else that's not well-known, [SchemaStore](https://www.schemastore.org) isn't the place for it.

### Where will my schema go?
You'll have several options, which will be generated in both JSON and YAML.
The extensions will be optional (i.e., you can use merely "/schema" or "/schema.json") and everything will still work.

#### Anywhere you want to put it! 
You can just generate it and save the file wherever you want without publishing it to the Web

#### Host it with us--there are lots of options:

###### With our URL at the front and all the information about your schema in the URL path:
* <span class="url-template">https://<span style='url-placeholder'>json/yaml</span>.schema.place/<span style='url-placeholder'>your-organization-name</span>/<span style='url-placeholder'>your-project-name</span>/<span style='url-placeholder'>your-namespace-name-path</span>/<span style='url-placeholder'>your-data-structure-name</span>/schema<span style='url-placeholder'>json/.yaml</span></span> <br/> (e.g., <span class="url-template">https&#8203;://json.schema.place/mcdowells/menu/burgers/big-mick.json</span>)
* https://**{json/yaml}**.schema.place/**{your-organization-name}**/**{your-project-name}**/**{your-namespace-name-path}**/**{your-data-structure-name}**/**{version}**/schema**{.json/.yaml}**
* https://**{json/yaml}**.schema.place/**{your-project-name}**/{your-namespace-name-path}/{your-data-structure-name}/{version}/schema{.json/.yaml}
* https://**{json/yaml}**.schema.place/**{your-project-name}**/{your-data-structure-name}/{version}/schema{.json/.yaml}
* https://**{json/yaml}**.schema.place/{your-data-structure-name}/{version}/schema{.json/.yaml}
* 
* https://{json/yaml}.schema.place/{your-organization-name}/{your-project-name}/{your-namespace-name-path}/{your-data-structure-name}/schema{.json/.yaml}
* https://{json/yaml}.schema.place/{your-project-name}/{your-namespace-name-path}/{your-data-structure-name}/schema{.json/.yaml}
* https://{json/yaml}.schema.place/{your-project-name}/{your-data-structure-name}/schema{.json/.yaml}
* https://{json/yaml}.schema.place/{your-data-structure-name}/schema{.json/.yaml}
