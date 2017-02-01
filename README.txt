


To run a python script from the Docker image ags98234/python-ml use the following command:
 docker run -v `pwd`:/test ags98234/python-ml python /test/t.py
  - that will mount a volume of the pwd to /test in the image
  - t.py exists in the pwd (outside of the image) and therefore also in the /test directory in the image
  - the command python /test/t.py is submitted in the container


