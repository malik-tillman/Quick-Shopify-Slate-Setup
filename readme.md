Quick Shopify Slate Setup
======
Use this to get started on developing a Shopify theme quick and easy. [Even though slate has been place on end of support](https://github.com/Shopify/slate#-slate---end-of-support-january-2020), it's my go to for developing Shopify themes. To get started, clone this repo and run the commands at the bottom. You can then either `migrate` an existing theme or generate a new `theme`. Use `slate -h` if anything. 


Steps
------

##### Install Slate and addition Slate helper tools. 

`npm i @shopify/slate @shopify/slate-tools`

`npm install`

`slate migrate`

or

`slate theme <theme-name>`

PRIMORDIALS IS NOT DEFINED!
===

Place this into `npm-shrinkwrap.json` and re-run `npm install`.

```json
{
  "dependencies": {
    "graceful-fs": {
        "version": "4.2.2"
     }
  }
}
```
