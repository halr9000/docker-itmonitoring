# docker-itmonitoring
Includes Technical Add-ons (TAs) and Splunk Docker application to help you get immediate value in monitoring your docker ecosystem.

Want to get going and see the value of this image? Using the following getting started guide, https://github.com/splunk/docker-gettingstarted-conf2016.

## List of Technical Add-ons
1. ta-dockerlogs_fileinput: Uses Splunk's File & Directories monitoring to monitor all files generated by the docker json-file driver.  Please read the following docker logging drivers documentation to learn more about the logging options in docker, https://docs.docker.com/engine/admin/logging/overview/.

2. ta-dockerstats:  Uses [Docker Remote API](https://docker.github.io/engine/reference/api/docker_remote_api/) to collect Inspect, Top, and Events in Splunk;  This TA is also used to correlate container ids collected by the ta-dockerlogs_fileinput.

3. ta-dockerstats:  Uses [Docker Remote API](https://docker.github.io/engine/reference/api/docker_remote_api/) to collect Inspect, Top, and Events in Splunk;  This TA is also used to correlate container ids collected by the ta-dockerlogs_fileinput.

4. ta-ucplogs-sysloginput: is used to transform the UCP syslog (TCP/UDP) data in to a ucp source that can be more efficiently analyzed in Splunk.<br>
 

The IT Monitoring is build on top of the Splunk Enterprise and Splunk Universal Forwarder docker images.  For more details about these base images, please refer to the following repos in
  * GitHub: https://github.com/splunk/docker-splunk
  * Docker Hub:
   * Splunk Enterprise, https://hub.docker.com/r/splunk/splunk/
   * Splunk Universal Forwarder, https://hub.docker.com/r/splunk/universalforwarder/
   
# Get help and support

More information about the Docker images and how to pull and run them is available in the README for each image.

If you have questions or need support, you can:

* Post a question to [Splunk Answers](http://answers.splunk.com)
* Join the [Splunk Slack channel](http://splunk-usergroups.slack.com)
* Visit the #splunk channel on [EFNet Internet Relay Chat](http://www.efnet.org)
* Send an email to [docker-maint@splunk.com](mailto:docker-maint@splunk.com)
