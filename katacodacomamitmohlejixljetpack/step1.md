### Quick start

To start this image, use the following command:

```
$ docker run -e "ADMIN_PASSWORD=admin" -e "ACCEPT_EULA=Y" -p 4516:4516 --name 
xld xebialabs/xl-jetpack-deploy:8.5
```

Set **ADMIN_PASSWORD** to the desired password for the admin user. Note that by running this command, you are accepting the End User License Agreement for XL JetPack.

Accessing the product

After the product starts, assuming Docker is running on your local machine, you can access it at http://localhost:4516. Log in with the user name admin and the password that you set in the Docker command.