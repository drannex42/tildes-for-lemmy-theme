# tildes-for-lemmy-theme
This is a theme built for the forum software Lemmy.ml inspired by(!) the design of tildes.net. 

![image](https://user-images.githubusercontent.com/4322153/186302981-0e682965-2f47-4f51-85c0-1c24efdf3ec5.png)

![image](https://user-images.githubusercontent.com/4322153/186303055-e54a3086-0276-474b-9075-9bec12771bb4.png)

This theme also has enhanced support for mobile. 

#### How to install theme on your server.
<sub>from https://github.com/LemmyNet/lemmy-docs/blob/main/src/en/administration/theming.md</sub>

> If you installed Lemmy with Docker, save your theme file to ./volumes/lemmy-ui/extra_themes. For native installation (without Docker), themes are loaded by lemmy-ui from ./extra_themes folder. A different path can be specified with LEMMY_UI_EXTRA_THEMES_FOLDER environment variable.

You may need to modify your docker-compose.yml file to see the extra_themes folder. Add this to the `lemmy-ui` section of that file. 

```
volumes:
      - ./volumes/lemmy-ui/extra_themes:/app/extra_themes
 ```
