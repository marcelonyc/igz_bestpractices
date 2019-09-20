# Taking a Nuclio function through its life cycle
Iguazio builts in the integratio with all the components needed to develop and deploy a Nuclio fucntion.
At a high level the cycle steps are:

* Write the function in an Iguazio Jupyter notebook
    * Leverage the %nuclio magic
    * Use #nuclio: ignore to ignore cells when deploying
    * Test before deploying
    * Use the V3IO_??? environment variables to contextualize
        * V3IO_USERNAME. You can make locations relative to the users name
* Use nuctl or python to deploy the function
* Commit to Git
* Use CI/CD tools to monitor changes
* Deploy to next step in cycle
    * nuctl or python script


# Artifacts in this section

 * portable_function_template.ipynb  	An example of a Nuclio function
 * tonuclio.ipynb				        An example of a deployment script
