# Installation and Innitialization of Docker Image
In order to execute the following, you need to have installed *docker*. [Download Docker](https://www.docker.com/products/docker-desktop)

## Docker Build - Installation

In terminal navigate to *Feature_Generator* directory.

e.g.:
 ```
 cd .../Feature_Generator
 ```


## Docker Build - Installation

In terminal navigate to *Feature_Generator* directory.
e.g.: ```cd .../Feature_Generator```

Build docker image from docker file:
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
```
pip install -e .
```

# Using the application
Execute the following command:
```
python3 feature_generator_Part1.py
```
This will execute Part 1 of the pipeline. After annotation of the two tables, run:

```
python3 feature_generator_Part2.py
```

Now, in the docker console, run:
