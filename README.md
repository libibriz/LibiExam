#convert


##built

docker built -t convert


##run

docker run -v $PWD/images:/app/images -v $(pwd)/output:/app/output convert images PDF_NAME=my_output_file




