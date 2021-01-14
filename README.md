#1 Pip3 info for troubleshooting

1) pip3 freeze - tells all of the packages installed
2) dependencies - pip3 freeze --local > requirements.txt to create
3) pip3 uninstall flask
4) pip3 install -r requirements.txt (-r look at the requirements file over the package index)

#2 Bootstrap (downloading startbootstrap theme into a repository)
1) gitpod /workspace/practical-python $ mkdir static
2) gitpod /workspace/practical-python $ cd static
3) gitpod /workspace/practical-python/static $ wget https://github.com/startbootstrap/startbootstrap-clean-blog/archive/gh-pages.zip
4) gitpod /workspace/practical-python/static $ ls
5) gitpod /workspace/practical-python/static $ unzip gh-pages.zip
6) make sure all folders css, img etc are directly within the static folder - not in any sub folders

#3
1) POST vs GET retrieve from the server vs send to the server