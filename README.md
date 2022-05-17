# What You’ll Need

If you are using MongoDB in the Cloud (Atlas) Or if you plan on using a local instance of MongoDB, you will need to:
>Install MongoDB and start up an instance to which you will connect.

# Install your client
To install Compass, see the Compass installation instructions

# Obtain your MongoDB connection
In order to connect to MongoDB, you will need a URI string. A URI (Uniform Resource Identifier) is similar to a URL.
> in my case i use the server ip, where i deployed the mongodb and its cluster run in localhost (http://127.0.0.1:27017).
# Connect to your MongoDB instance
If you wish to manually configure your Compass connection, load Compass and select the New Connection link. You will see a form where you can enter connection information for MongoDB.

![connect-to-host](https://user-images.githubusercontent.com/71556060/168813184-16a30543-abc8-40a9-9167-5da238f84619.png)

>in my case i use mongo-compass version 1.31

![image (1)](https://user-images.githubusercontent.com/71556060/168814437-c1c80620-6e30-426f-b530-7ec83b900bf2.png)

>the host name define your mongoDB cluster-IP,
you can see your cluster-IP in ubuntu on:
```
nano /etc/mongo.conf
```
>if your mongo-DB is bind with some external or internal IP, then use this URL.
>in my case my server-IP is public and mongo is runing on internal local host (IP=127.0.0.1).
![image (2)](https://user-images.githubusercontent.com/71556060/168815985-1fcb872f-3588-4562-964f-d2048c37e97c.png)

You will be prompted to populate the connection dialog. Click Yes.



# NOTE
Errors related to connecting through Compass will appear in red at the top of the Connect screen.

# Summary

Congratulations. If you have successfully completed this guide, you have connected to your MongoDB instance. In the next group of guides, you’ll learn how to create, read, update, and delete data in MongoDB.
