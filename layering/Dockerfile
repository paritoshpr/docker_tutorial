FROM pramanan3/home_example:latest 

#create working directory
WORKDIR /home/NASA_HOME/

#copy code from your machine (host) to the container youre creating
COPY ./ /home/NASA_HOME/

#make sure code can be executed with permissions
RUN chmod -R +x /home/NASA_HOME/

#run your code
CMD python ./hello-world2.py
