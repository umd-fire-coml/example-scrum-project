# Example Scrum Project
### Example Scrum Project is a example project meant to demonstrate git and our workflow
![symbol](img.jpg)
## Features
- well prepared code repo
- a good display of the use of [git](https://git-scm.com/)
- really well processed data
- creation of many [issues](https://guides.github.com/features/issues/)
- a well crafted readme
- An example to practice git with
## Example of Running the code
Start by running `python3 --version` and ensuring it is 3.6 or higher. \
Ensure you have the following libaries installed by running `pip freeze`
1) [Abseil](https://github.com/abseil/abseil-py)
2) [Beautiful Soup](https://github.com/waylan/beautifulsoup)
3) [Six](https://pypi.org/project/six/)
4) [Rickroll](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
5) [Numpy](https://numpy.org)
6) [Cython](https://github.com/cython/cython)
7) [Ninja](https://github.com/ninja-build/ninja)\
Next, clone the code though the following commands 
```bash
mkdir ~/src
cd ~/src
echo "dont actually do this"
git clone git@github.com:umd-fire-coml/example-scrum-project.git
cd example-scrum-project
sudo chmod 446 README.MD 
```
## Example table
|Name|Progress|Points|Description| Asignee|
---|:---:|:---:|:---|---:
`dp-download`| Done!| 1| Download the training data| Derek
`dp-unzip`| :heavy_check_mark: | 1 | Unzip the training data | Richard 
`dp-structure`| :heavy_check_mark:| 1| Create Structure of the directory| Richard
`dp-folder`| :heavy_check_mark: | 2 | Unzip the training data | Josh
`dp-visualization`| :x:| 5| Create a visualization of the training data| Vlad
`dp-jupyterlab`| :x: | 2 | Set up the jupyter lab | Josh 
`model-detection`| :x: | 1 | Create the model | :worried:
## Known issue with code
Add these lines of code to fix
```python
import os
txt = " your code is fixedaroni"
os.system('echo abracadabra%s'%(s))
print("everything is done")
```
