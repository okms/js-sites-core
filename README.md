# Using js-sites-core
Can be as simple as
```
jQuery.getScript(`${_spPageContextInfo.siteAbsoluteUrl}/SiteAssets/js/pzl.sites.core.js`, () => {
    Pzl.Sites.Core.init(siteTemplateConfig, { "On": true }).then(() => {               
        
    })
});
```

or with logging to file
```
jQuery.getScript(`${_spPageContextInfo.siteAbsoluteUrl}/SiteAssets/js/pzl.sites.core.js`, () => {
    Pzl.Sites.Core.init(siteTemplateConfig, { "On": true, "LoggingFolder": _spPageContextInfo.siteServerRelativeUrl + "/SiteAssets/logs" }).then(() => {               
        
    })
});
```

# Bower
js-sites-core is available through bower.

Package information
```powershell
    bower info js-sites-core
```

Install package
```powershell
    bower install js-sites-core
```

# Schema
[Schema 1.4.2](Schema-1.4.2.md)

# Samples
[Full Sample](samples/Full-Sample.md)
