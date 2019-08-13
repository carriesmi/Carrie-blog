# Carrie's blog about anything and everything

### [HOME PAGE](./README.md)

## Customize your blog
This article explains how to customize various aspects of a blog created
using this repository.

### Index of this article
- **File locations**
- **Confiure site**
- **change appearence**

### File locations
Main files used to customize are located at `/_config.yml`, `/_layouts/default.html`, 
`/assets/css/style.scss`. We are using Dinky theme and you can refer [its documentation](https://github.com/pages-themes/dinky)
for more advanced customizations.  

### Confiure site
Blog's name and discription shown in left box can be modifed by specifying it 
in _config.yml file.  
for example
```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```
### change appearence'
You can change color, fonts etc using the `/assets/css/style.scss` file. first open
the `/_layouts/default.html` to see names of parts of webpage(for example header) then
modify corresponding css in the style.scss file.


Thank You
