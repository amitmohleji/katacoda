### Quick start - XL Release

To start this image, use the following command:

```
$ docker run -d -e "ADMIN_PASSWORD=admin" -e "ACCEPT_EULA=Y" -p 5516:5516 --name xlr xebialabs/xl-jetpack-release:8.5
```

Set **ADMIN_PASSWORD** to the desired password for the admin user. Note that by running this command, you are accepting the End User License Agreement for XL JetPack.

Accessing the product

After the product starts, assuming Docker is running on your local machine, you can access it at https://[[HOST_SUBDOMAIN]]-5516-[[KATACODA_HOST]].environments.katacoda.com/. Log in with the user name admin and the password that you set in the Docker command.