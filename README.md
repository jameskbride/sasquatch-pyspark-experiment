# Sasquatch Pyspark Experiment

Pull down the pyspark-notebook:
`docker pull jupyter/pyspark-notebook`

Run the notebook from the root of this project (it will give you a link to click, which will take you to the notebook):
`docker run -it -v $PWD:/usr/local/data/sasquatch --rm -p 8888:8888 jupyter/pyspark-notebook`

That last command will start the pyspark-notebook container, which the current directory mounted, which will make the data in this project available to spark.
