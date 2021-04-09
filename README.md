# DataBricks DeltaLake workshop 21-04-09
Hands-on workshop on using Spark + DeltaLake running in [MyBinder](https://mybinder.org/).

This repo is forked from https://github.com/thedatasociety/lab-spark and adjusted to install Spark 3.0.2 to support DeltaLake.
## Steps
1. [Launch the Binder environment](https://notebooks.gesis.org/binder/v2/gh/lassebenni/lab-spark/master?urlpath=lab). This will start a Dockerized version of the Repo on a public compute instance (hosted by gesis.org).
2. Binder will build and install Apache Hadoop 3.2.1 and Apache Spark 3.0.
3. Binder will start [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/) so we can use Jupyter Notebooks for the exercises.
4. The workshop notebooks will be downloaded from [The Delta Lake Workshop Repo](https://github.com/lassebenni/delta-lake-workshop). The notebooks contain the code to install and use [DataBricks DeltaLake[(https://docs.databricks.com/delta).
5. Enjoy the power of Spark and DeltaLake in your Browser!

### Warning: Download your Notebook changes
Be sure to download any changes to your notebooks since the Binder environment is temporary and does not persist changes after shutting down! If your browser session is inactive for more than 10 minutes (active window==active session), Binder will shutdown and you will lose all changes on the next launch since a copy of the master branch will be started again.

## Uses
- https://mybinder.org/
- https://github.com/delta-io/delta
- https://github.com/thedatasociety/lab-spark
- https://github.com/lassebenni/delta-lake-workshop
