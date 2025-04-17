
## Quarto Theme for Presentations and Websites

Work in progress, a template for adding UI branding elements to quarto websites and presentations. 

### Files

| File  | Contents and/or Purpose |
|----------|----------------------|
| *_brand.yml* | main branding file that is compatible with quarto sites |
| *_variables.scss* | original [quarto scss file](https://github.com/twbs/bootstrap/blob/main/scss/_variables.scss), kept for reference |
| *_ui_variables.scss* | updated version of *_variables.scss* with some UI branding elements |
| *font_header.html*  | header material for adding the 'Public Sans' Google font
| *ui_styles_extra.css* | some custom css to do special things |
| *uidaho.min.css*    | UIdaho's main CSS file taken straight off their main website |
| img directory | curently contains official UIdaho logos |

### Misc

* *_brand.yml* is still a WIP, more info on what that file can do [here](https://quarto.org/docs/reference/metadata/brand.html)
* not much has been done to *_ui_variables.scss* to make it more "UI" - it would be useful to try and integrate that with the *uidaho.min.css*, however, updating *_brand.yml* might cover enought aesthetic changes to make any presentation or website sufficiently UI branded. 
* [more info on quarto html theming](https://quarto.org/docs/output-formats/html-themes.html)
* Here are addition [University of Idaho brand resources](https://uidahophoto.photoshelter.com/galleries/root/C0000zqiKe.s7yWI/Brand-Resources)
