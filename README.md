# betradar_api_client
Api Client of Betradar. We can simply use this client for the api calls.

In order to make it work make sure we have figaro gem installed.

# Update betradar_api_key and betradar_base_url 

In order to call any api we can use

# Betradar::Client.new

to make any Api call check methods available in modules of api folder.

E.g.

To Request recovery since after specific timestamp we have recovery_after_timestamp method available in `api/odds_recover.rb`

# Betradar::Client.new.recovery_after_timestamp
