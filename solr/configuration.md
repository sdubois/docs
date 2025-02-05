# Solr configuration

Amezmo configures the Solr instance for Drupal with default credentials. The autogenerated 
credentials may be found in your [dotenv](/docs/configuration/dotenv) file and within the 
Configuration tab in your Amezmo dashboard. See below for the configuration that Amezmo 
generates.

| Variable    | Value                                    |
--------------|------------------------------------------
| `SOLR_HOST` | _See your Application details panel*_
| `SOLR_CORE` | drupal                                  |
| `SOLR_PORT` | 8983

\* To access your Application details panel go to Overview > Application details.


The `SOLR_HOST` value is what you will provide to your Drupal configuration form. 
This is where your actual Solr server lives. This is unique to your instance and is only 
available after you launch it. See below for an example host name.

This screenshot highlights the Solr host which gets generated after your instance is launched.
The Solr host value exist only after the instance is created.

<img class="img-enlargable img-fluid" src="https://s3.us-east-2.amazonaws.com/static.amezmo.net/app-details-solr-host.png" />

To view your automatic dotenv variable set for Solr, see the screenshot below. This example shows 
which variable set Amezmo generates. 

<img class="img-enlargable img-fluid" src="https://s3.us-east-2.amazonaws.com/static.amezmo.net/solr-dotenv-vars.png" />

