# There are plenty of tools that do this already!
True!  And defining a schema to describe or validate a data structure is great!  It allows the data to be validated at code time by the IDE as well as offer code completion hints so you can catch errors earlier.  And if you just need a one-off schema for your project, we suggest you use one of those other tools \(we do\!\).

# Why shouldn't/can't I host it with [SchemaStore](https://www.schemastore.org).  That's what they do!
Their site is intended for "commonly known JSON file formats."  If you're creating a schema for your own little project or anything else that's not "commonly known," [SchemaStore](https://www.schemastore.org) isn't the place for it.  But here, we don't discriminate.  :wink:

## Fine, my project isn't that special.  Now what?
First, your schema will be generated in all languages that are intended to describe that data structure to offer you maximum versatility in writing your code.  After that, it's up to you.

## You got options

- ### Just put it anywhere you goddamn want to
  - Save it privately and don't publish it to the Web
  - Host it on your own site or any other site you manage.  We let you pick the format for the *schema* property, so you tell us where it's going to go and that's the URL we'll populate that property with.

- ### Host it with us and use our base URI; there will be lots of patterns to choose from
  - <span class="url-template">https://<span style='url-placeholder'>json/yaml</span>.schema.place/<span style='url-placeholder'>your-organization-name</span>/<span style='url-placeholder'>your-project-name</span>/<span style='url-placeholder'>your-namespace-name-path</span>/<span style='url-placeholder'>your-data-structure-name</span>/schema<span style='url-placeholder'>json/.yaml</span></span> <br/> (e.g., <span class="url-template">https&#8203;://json.schema.place/mcdowells/menu/burgers/big-mick.json</span>)
  - <span class="url-template">https://<span class="url-fragment">schema-language<span class="url-fragment">.schema.place/<span class="url-fragment">your-organization-name<span>/<span class="url-fragment">your-project-name<span>/<span class="url-fragment">your-namespace-name-path<span>/<span class="url-fragment">your-data-structure-name<span>/<span class="url-fragment">version<span>/schema<span/>.schema-language<span>
  - <span class="url-template">https://<span>schema-language<span>.schema.place/<span>your-project-name<span>/<span>your-namespace-name-path<span/>/<span>your-data-structure-name<span>/<span>version<span>/schema<span>.schema-language<span></span>
  - <span class="url-template">https://<span class="url-fragment">schema-language<span class="url-fragment">.schema.place/<span class="url-fragment">your-project-name<span>/<span>your-data-structure-name<span/>/<span>version<span>/schema<span>.schema-language<span></span>
  - <span class="url-template">https://<span class="url-fragment">schema-language<span class="url-fragment">.schema.place/<span class="url-fragment">your-data-structure-name<span>/<span>version<span>/schema</span>.schema-language<span></span>
  - <span class="url-template">https://<span class="url-fragment">schema-language<span class="url-fragment">.schema.place/<span class="url-fragment">your-data-structure-name<span>/schema<span>.schema-language</span></span>
  - <span class="url-template">https://<span class="url-fragment">schema-language<span class="url-fragment">.schema.place/<span class="url-fragment">your-data-structure-name<span><span>.schema-language</span></span>
  - <span class="url-template">https://<span class="url-fragment">schema-language<span class="url-fragment">.schema.place/<span class="url-fragment">whatever-you-want<span><span class="url-fragment">.schema-language<span></span>
