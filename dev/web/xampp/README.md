# XAMPP

## Docker: Installatione and configuration
* [XAMPP Docker image](https://hub.docker.com/r/tomsik68/xampp/) by tomsik68
* Running the image (http port `8080`, SSH port `2222`) maps local `project_dir` to the container `/www`
  ```shell
  docker run --name myXampp -p 2222:22 -p 8080:80 -d -v ~/project_dir:/www tomsik68/xampp
  ```
* SSH user is `root` with password `root`
* Configuration files are in `/opt/lampp/etc/`
* Default Apache `htdocs` directory is `/opt/lampp/htdocs/`
  * Edit `index.php` here to modify default *dashboard* page dispaly by the server.
