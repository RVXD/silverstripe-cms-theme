# Silverstripe CMS Branding

Just a nice little UI change for the cms.

The theme supports an UploadField in the *Settings > Settings Tab > CMS Tab* for a logo to be displayed in the left-hand menu of the CMS.

## Configuration

You can either choose to upload a CMS logo through the Site Settings section of the CMS, or you can define it through a YML configuration like the below:

```yml
SiteConfig:
  cms_logo: 'mysite/images/cms_logo.png'
```

You can set the theme colour of the left menu by defining it through a YML configuration like the below:

```yml
LeftAndMain:
  cms_menu_background: '#ff0000'
  cms_menu_active_text_color: '#00ff00'
  cms_menu_active_background_color: '#0000ff'
```

### Example

![demo-image](https://cloud.githubusercontent.com/assets/1136811/7264694/a272d25c-e8e2-11e4-8981-4216ad31f09e.png)
