# strapi-v4-color-picker
 
## Installation
- 1 Move "color-picker-v4" into the plugins folder
- 2 Enable the plugin in the "config\plugins.js" file

```
    'color-picker-v4': {
      enabled: true,
      resolve: './src/plugins/color-picker-v4'
    }
```

- 3 Overwrite line 246 in the strapi inputs component

"\node_modules\@strapi\admin\admin\src\content-manager\components\Inputs\index.js"
