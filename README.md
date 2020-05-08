# Serve a static dist folder w/ Laravel Valet 

Valet driver for serving static php files. By default, laravel valet will reroute all requests to the index.php. This will use a dist folder so can pull in the project and only run `npm run build` occasionally but still have it served under valet.

## Install
Download and copy the `DistFolderValetDriver.php` to `~/.config/valet/Drivers/DistFolderValetDriver.php`

Or run:
```bash
curl -o ~/.config/valet/Drivers/DistFolderValetDriver.php  https://raw.githubusercontent.com/gjrdiesel/static-valet-driver/master/DistFolderValetDriver.php 
```
