## End to End Machine Learning Project

###for azure web app deployment 
## Run from terminal:

docker build -t testdockeratul.azurecr.io/studentperformance:latest .

docker login testdockeratul.azurecr.io

docker push testdockeratul.azurecr.io/studentperformance:latest
