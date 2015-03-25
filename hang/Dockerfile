FROM busybox
RUN mkdir /code
WORKDIR /code
RUN echo "Built something" > /code/build_has_been_run
RUN echo "`date` About to sleep for 2 hours" >> /code/build_has_been_run
RUN sleep 7200
RUN echo "`date` Finished 2 hour sleep" >> /code/build_has_been_run
