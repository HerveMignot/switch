# switch
Switch is a framework for Jupyter notebooks industrialization without code extraction.

Industrializing data science use cases is a challenge nowadays with an increasing pressure for fast deployments in production.
Currently, many teams extract the code written by data scientists, typically from Jupyter notebooks to Python scripts.

Switch is a simple notebook deployment framework for data scientists, using the same notebook for development and production.
They can keep working with Jupyter, building their use case while preparing within the same notebook the industrialisation steps.
This framework relies strongly on coding conventions and magic commands.
It avoids extracting source code and refactoring to standalone scripts for deployment. Adaptations or bug fixing done during
industrialization are done within the same notebook, avoiding any code merge between production and development.

This framework supports industrialization with Apache Airflow or Luigi.
