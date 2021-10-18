# Configuration
To apply these configurations, edit the `config.yml` file in homers `www/assets` folder.


## Custom tag colors
Homer uses Bulma CSS and you can apply their [color modifiers](https://bulma.io/documentation/overview/modifiers/) to the Tags.

Example:
```yaml
- name: "Homer Theme"
        logo: "assets/tools/github.png"
        subtitle: "The official Homer Theme github!"
        tag: "github"
        tagstyle: "is-primary" # This will display the is-primary color! Try changing it to; is-link, is-info, is-success, is-warning or is-danger!
        url: "https://github.com/WalkxCode/Homer-Theme"
        target: "_blank"
```

## Custom background
You can set a custom background on homer by replacing the default `wallpaper.jpeg` in homers `www/assets` folder and replacing it with your own custom wallpaper!

To apply the new wallpaper edit the following line:
```yaml
colors:
  dark:
    highlight-primary: "#181C3A"
    highlight-secondary: "#181C3A"
    highlight-hover: "#1F2347"
    background: "#12152B"
    card-background: "#181C3A"
    text: "#eaeaea"
    text-header: "#7C71DD"
    text-title: "#fafafa"
    text-subtitle: "#8B8D9C"
    card-shadow: rgba(0, 0, 0, 0.5)
    link: "#3273dc"
    link-hover: "#ffdd57"
    background-image: "../assets/wallpaper.jpeg" # Change wallpaper.jpeg to the name of your own custom wallpaper!
```

## Custom column amount
You can change the amount of columns by changing the following line:

```yaml
columns: "3" # You can change this to any number that is a factor of 12: (1, 2, 3, 4, 6, 12)
theme: default
```

## Custom icons
You can get custom icons for your Homer dashboard [here](https://github.com/WalkxCode/dashboard-icons).

To apply these icons, first download them into homers `www/assets/tools` folder. 

By running:
```sh
$ wget https://raw.githubusercontent.com/WalkxCode/dashboard-icons/master/png/example.png
```

Then change the following line:
```yaml
- name: "Homer Theme"
        logo: "assets/tools/github.png" # Change github.png to the name of your own custom icon!
        subtitle: "The official Homer Theme github!"
        tag: "github"
        tagstyle: "is-primary"
        url: "https://github.com/WalkxCode/Homer-Theme"
        target: "_blank"
```

#### Want to customize more? [Make an issue](https://github.com/WalkxCode/Homer-Theme/issues/new) and I'll help you!
