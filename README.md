sumologic-eventcollect
======================

Sometimes we need to work with ingesting logs from legacy systems, 
where Open Telemetry, Syslog, WEC, or even an install collector is not an option.

In that case, a Sumo Logic design pattern is to build an intermediate server/image, 
and assemble data sources to that server, then uploading to Sumo Logic.

In an ideal situation, this should be an intermediary step, but the solution 
will easily scale using a set of "Sumo Logic Ingest Proxy" servers.

Installing the Project
======================

The steps are as follows: 

    1. Download and install git for your platform if you don't already have it installed.
       It can be downloaded from https://git-scm.com/downloads
    
    2. Open a new shell/command prompt. It must be new since only a new shell will include the new python 
       path that was created in step 1. Cd to the folder where you want to install the scripts.
    
    3. Clone this repo using the following command. This would create a new drectory

    4. Study and reuse the scripts as you need to. The idea is to install scripts on the Ingest Proxies.

    5. Test out ingest and conversion, and then consider using schtasks/at or cron
    
Dependencies
============

This assumes Windows, Powershell and Bash, where the level of Powershell is at least 2 or better.

License
=======

Copyright 2021 Wayne Kirk Schmidt
https://www.linkedin.com/in/waynekirkschmidt

Licensed under the Apache 2.0 License (the "License");

You may not use this file except in compliance with the License.
You may obtain a copy of the License at

    license-name   APACHE 2.0
    license-url    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Support
=======

Feel free to e-mail me with issues to: 

+   wschmidt@sumologic.com

+   wayne.kirk.schmidt@gmail.com

I will provide "best effort" fixes and extend the scripts.
