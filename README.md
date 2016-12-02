# Fitnesse

Fitnesse is a wiki and acceptance testing framework.

# Building

You can build the image with the following docker command:

```
docker build -t fitnesse .
```

# Running

To run the new container locally, use the following command:

```
docker run -dP fitnesse
```

After that your container should be reachable at [localhost](http://localhost/)

# Adding Plug-ins