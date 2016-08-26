# NFL PLayer Arrests

* The API http://nflarrest.com/api/ provides us details about NFL players and their arrest records

## Data download

* Using the API above, We would like to store data about NFL player's and their arrests 
* We have the following data: NFL players, The teams they belong to, Position they play, Category of Crimes, Crimes they were arrested for
* Design a schema that stores the above information. The Schema should be normalized
* Download the data and populate the schema


## Maintenance 
* Create a scheduled job that runs everyday to check if there is any latest information on players' arrest
* The details about the duration to execute the job should be stored in the database
* The status of each run should also be recorded (completed, errored)

## Technology to use
* Ruby 2.3.1
* Rails 5
* Postgres
* Sidekiq
* Sidekiq Cron
