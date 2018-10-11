# DevSecOps Reference Architectures

This is a collection of DevSecOps reference architectures. I was tired of crawling through low resolution slideshares and email-grabbing web forms, therefore I started this repo to share reference architectures - for free - for everyone.

### Contributing

Feel free to contribute via pull requests or issues. If you find slides in a higher quality, please let me know!

Please provide the following data for new architectures:
* Name of the source of the architecture
* Image of the reference architecture
* Year when the architecture was designed
* Optional: Link to the source for more information
* Optional: Summary of the architecture. What makes it special? Where does it differentiate? What is the problem it solves?
* Optional: Software stack. That makes it easier to search for architectures that use a specific tool.

### Acknowledgements

Thanks to [Sonatype](https://sonatype.com) and their [reference architecture slideset](https://de.sonatype.com/devsecops-reference-architectures) ([mirror](https://waterplacid.files.wordpress.com/2018/04/devsecops-reference-architectures-2018.pdf)). 

Most of the referenced tools can be found in the more structured [Awesome DevSecOps list](https://github.com/devsecops/awesome-devsecops).

## Architectures


### OWASP AppSec Rugged DevOps Pipeline Project - 2015

[OWASP AppSec Pipeline](https://www.owasp.org/index.php/OWASP_AppSec_Pipeline), 
[OWASP AppSec Pipeline Talks](https://www.owasp.org/index.php/OWASP_AppSec_Pipeline#tab=Presentations), 
[GitHub Repository incl. Docker containers](https://github.com/appsecpipeline/AppSecPipeline-Specification)

The OWASP AppSec Rugged DevOps Pipeline Project is the place to find the information you need to increase the speed and automation of your AppSec program. Using the sample implementation, documentation and references of this project will allow you to setup your own AppSec Pipeline.

Software Stack: [Bandit](https://github.com/PyCQA/bandit), [OWASP Dependency-Check](https://www.owasp.org/index.php/OWASP_Dependency_Check), [Checkmarx](https://www.checkmarx.com/), [SSLLabs](https://www.ssllabs.com/), [Arachni](http://www.arachni-scanner.com/), [wappalyzer](https://www.wappalyzer.com/), [Synk](https://snyk.io/), [WPScan](https://wpscan.org/), [brakeman](https://brakemanscanner.org/), [OWASP ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project), [Retire.js](http://retirejs.github.io/retire.js/)

![2015-owasp-appsec](https://github.com/ayeks/devsecops-reference-architectures/blob/master/img/2015-owasp-appsec.png)

### DevOpsSec - Jim Bird - 2016

[DevOpsSec - Jim Bird - O'Reilly Media](https://www.oreilly.com/library/view/devopssec/9781491971413/)

How do you build security and compliance into your DevOps platforms and pipelines? With this O’Reilly report, security analysts, security engineers, and pen testers will learn how to leverage the same processes and tools—such as version control, containers, and Continuous Delivery—that DevOps practitioners use to automate software delivery and infrastructure changes. In other words, you’ll understand how to use DevOps to secure DevOps.

Software Stack: [Upguard](https://www.upguard.com/), [Gauntlt](http://gauntlt.org/), [OWASP Dependency-Check](https://www.owasp.org/index.php/OWASP_Dependency_Check), [Bundler Audit](https://github.com/rubysec/bundler-audit), [Retire.js](http://retirejs.github.io/retire.js/), [OWASP SafeNuGet](https://www.owasp.org/index.php/OWASP_SafeNuGet), [Gerrit](https://www.gerritcodereview.com/), [Phabricator](https://www.phacility.com/), [Atlassian Crucible](https://www.atlassian.com/software/crucible), [Sonarqube](https://www.sonarqube.org/), [OWASP ZAP](https://www.owasp.org/index.php/ZAP), [Mittn](https://github.com/F-Secure/mittn), [Chef Vault](https://github.com/chef/chef-vault), [Keywhiz](https://github.com/square/keywhiz), [HashiCorp Vault](https://www.vaultproject.io/), [Netflix SimianArmy](https://github.com/Netflix/SimianArmy), [Signal Sciences](https://www.signalsciences.com/products/), [Alert Logic](https://www.alertlogic.com/), [CloudPassage Halo](https://www.cloudpassage.com/products/), [Dome9 SecOps](https://dome9.com/), [Evident](https://www.paloaltonetworks.com/products/secure-the-cloud/evident.html), [Illumio](https://www.illumio.com/), [Threat Stack](https://www.threatstack.com/), [Waratek](https://www.waratek.com/), [Prevoty](https://www.prevoty.com/), [Contrast Security](https://www.contrastsecurity.com/runtime-application-self-protection-rasp), [tCell](https://www.tcell.io/), [Twistlock](https://www.twistlock.com/),  [DevOps Audit Defense Toolkit](https://itrevolution.com/devops-audit-defense-toolkit/), 

![2016-bird-1](https://github.com/ayeks/devsecops-reference-architectures/blob/master/img/2016-bird-1.JPG)

![2016-bird-2](https://github.com/ayeks/devsecops-reference-architectures/blob/master/img/2016-bird-2.JPG)

### US Defense Threat Reduction Agency - Joint Improvised Thread Defeat Organisation - Leo Garciga - 2017

[All Day DevOps 2017 - Youtube](https://www.youtube.com/watch?v=LNL5J6gIkv0)

The talk goes into detail why they went DevOps, how DevOps can be secure according to NIST SP 800, how automation prevents human error and reduces human delay.

Software Stack: [Docker](https://www.docker.com/), [Jira](https://de.atlassian.com/software/jira), [Jenkins](https://jenkins.io/), [Selenium](https://www.seleniumhq.org/), [Twistlock](https://www.twistlock.com/), [Sonarqube](https://www.sonarqube.org/), [Sonatype](https://www.sonatype.com/), [Maven](https://maven.apache.org/)

![2017-garciga-1](https://github.com/ayeks/devsecops-reference-architectures/blob/master/img/2017-garciga-1.JPG)

![2017-garciga-2](https://github.com/ayeks/devsecops-reference-architectures/blob/master/img/2017-garciga-2.JPG)

### DevOps Audit Defense Toolkit - IT Revolution - 2015

[DevOps Audit Defense Toolkit - IT Revolution](https://itrevolution.com/devops-audit-defense-toolkit/)
[DevOps Audit Defense Toolkit - PDF Link](https://dl.orangedox.com/audit-defense)

The Toolkit summarizes the techniques they use to mitigate risk, and also provides a section answering the most common questions about value creation, compliance, and DevOps. The information in this document should help organizations wanting to pursue DevOps and continuous delivery explain their approach and improve communication between IT and audit

![2015-audit-defense](https://github.com/ayeks/devsecops-reference-architectures/blob/master/img/2015-audit-defense.JPG)
