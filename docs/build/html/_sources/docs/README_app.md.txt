# Installation and Innitialization of Docker Image
<<<<<<< HEAD
In order to execute the following, you need to have installed *docker*. [Link to docker documentation](https://docs.docker.com/engine/install/ubuntu/)
=======

>>>>>>> main

## Docker Build - Installation

In terminal navigate to *Feature_Generator* directory.
<<<<<<< HEAD
e.g.:
 ```
 cd .../Feature_Generator
 ```

Build docker image from docker file:

=======
e.g.: ```cd .../Feature_Generator```

Build docker image from docker file:
>>>>>>> main
```
docker build -t feature_generator .
```

## Running Feature Generator
Each time, when running the application, run docker container first. Then follow the standard pipeline. 

### Run docker container from image
Execute in terminal: 
```
docker run -it --rm -v $PWD:/app feature_generator
```
Now, in the docker console, run:
```
pip install -e .
```

# Using the application
Execute the following command:
```
python3 feature_generator_Part1.py
```
<<<<<<< HEAD
This will execute Part 1 of the pipeline :ref: 'Explanation Feature Generator Pipeline'. After annotation of the two tables, run:
=======
This will execute Part 1 of the pipeline. After annotation of the two tables, run:
>>>>>>> main

```
python3 feature_generator_Part2.py
```
