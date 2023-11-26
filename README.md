# Generative-Dashtoon
The dataset was taken from  https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz <br>
The code used Pythorch, torchvisionn numpy, pandas and matplotlib, make sure to install these libraries <br>
The code might throw error of PILLOW_VERSION cannot be imported, this is because this has been depreciated from newer version of torchvision, so we might have to edit the library in a specific folder as PILLOW_VERSION  by __version__  in functional.py at : Your_File_Path\Lib\site-packages\torchvision\transforms\functional.py
