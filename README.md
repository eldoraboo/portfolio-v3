# Portfolio using Create React App and Chakra UI

This portfolio is built using Create React App and Chakra UI. It allows you to quickly create and customize your portfolio website using markdown files.

## Getting Started

To get started with development, you can use the following commands:

```
# Install dependencies
yarn install

# Start the development server
yarn start

# Build the static files
yarn build
```

After running `yarn start`, your website should be available at `http://localhost:3000`.

## Editing Content

To edit the content on your website, refer to the markdown files located in the `public/content` folder.

### Experience.md

To edit your work experience, update the `Experience.md` file with the following format:

```
## Company Name
- *Role* | Period
- ![image_name](../assets/image_name.png)
- Tags: Work
- Badges:
  - BadgeContent [badge_colour]
- List Items:
  - Point 1
  - Point 2
```

### Projects.md

To edit your projects, update the `Projects.md` file with the following format:

```
## Project Name
- Description
- ![image_name](../assets/image_name.png)
- Tags: WebDev
- Badges:
  - BadgeContent [badge_colour]
- Buttons:
  - ButtonContent [button_link]
```

### OtherProjects.md

To edit other projects or items, update the `OtherProjects.md` file with the following format:

```
## Project Name
- Description
- Tags: WebDev
- Badges:
  - BadgeContent [badge_colour]
- Buttons:
  - ButtonContent [button_link]
```

## Customizing Design

You can customize the design of your website by modifying the `theme.js` file located in the `src` folder. Refer to the Chakra UI documentation for more information on how to customize your theme.

## License

This portfolio is licensed under the MIT License. See the LICENSE file for more information.