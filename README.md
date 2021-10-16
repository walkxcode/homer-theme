# Getting started with Homer Theme!

### 1. Making sure your Homer is on Darkmode
On the top-right of Homer, you can find an icon to toggle dark-mode. Click it until the UI turns dark, and the icon looks like an empty circle!

### 2. Getting the assets files
**Clone [this repo](https://github.com/WalkxCode/Homer-Theme). You can do this by running:**
```bash
$ git clone https://github.com/WalkxCode/Homer-Theme.git
```
**Now cd into the newly created folder.**
```bash

$ cd Homer-Theme
```
**And now for the final step move the `assets` folder into your Homers `www` folder. You can find this directory by running**
```bash
$ sudo docker inspect -f '{{ .Mounts }}' homer
```

**Move the folder by running**
```bash
$ sudo mv assets /homer/www
```
_Make sure you replace `/homer/www` with the location of **your** www folder._

### 3. Go to your Homers IP and port and see the result!

#### To further customize the Dashboard, see the Wiki!
