# tildes-for-lemmy-theme
This is a theme built for the forum software Lemmy.ml inspired by(!) the design of tildes.net. 

#### How to install theme on your server.
<sub>from https://github.com/LemmyNet/lemmy-docs/blob/main/src/en/administration/theming.md</sub>

> If you installed Lemmy with Docker, save your theme file to ./volumes/lemmy-ui/extra_themes. For native installation (without Docker), themes are loaded by lemmy-ui from ./extra_themes folder. A different path can be specified with LEMMY_UI_EXTRA_THEMES_FOLDER environment variable.

You may need to modify your docker-compose.yml file to see the extra_themes folder. Add this to the `lemmy-ui` section of that file. 

```
volumes:
      - ./volumes/lemmy-ui/extra_themes:/app/extra_themes
 ```
