## Changes

### 1.3.5 (pending)

* update antrun plugin 1.8 to 3.0
* update checkstyle plugin 3.1.0 to 3.1.1
* update dependency plugin 3.1.1 to 3.1.2
* update javadoc plugin 3.1.1 to 3.2.0
* update site plugin 3.8.2 to 3.9.0


### 1.3.4 (2020-02-04)

* update checkstyle 8.21 to 8.29
* update source plugin 3.2.0 to 3.2.1
* CAUTION: do not update release plugin 2.5.3 to 3.0.0-M1 because of https://issues.apache.org/jira/browse/MRELEASE-973


### 1.3.3 (2019-11-29)

* update enforder plugin 3.0.0-M2 to 3.0.0-M3


### 1.3.2 (2019-11-20)

* update surefire and failsafe plugin 2.22.2 to 3.0.0-M4
* update jar plugin 3.1.2 to 3.2.0
* update source plugin 3.1.0 to 3.2.0


### 1.3.1 (2019-08-08)

* update javadoc plugin 3.1.0 to 3.1.1
* update site plugin 3.7.1 to 3.8.2


### 1.3.0 (2019-06-24)

* run checkstyle during `validate` phase
* added war plugin 3.2.3 to the managed plugins
* update checkstyle plugin 3.0.0 to 3.1.0
* update checkstyle library 8.15 to 8.21
* update surefire+failsafe plugin 2.22.0 to 2.22.2
* update javadoc plugin 3.0.1 to 3.1.0
* update source plugin 3.0.1 to 3.1.0
* update spotbugs 3.1.8 to 3.1.11
* update help plugin 3.1.0 to 3.2.0
* update jar plugin 3.1.0 to 3.1.2
* update scm plugin 1.11.1 to 1.11.2
* update doxia markdown module 1.8 to 1.9


### 1.2.0 (2019-01-29)

* checkstyle update
  * update to checkstyle 8.15
  * change checkstyles rules to cip rules


### 1.1.0 (2018-12-07)

* inline foss-parent with these changes:
  * removed dependency management
  * removed profiles: foss-parent-run-its, foss-parent-enable-invoker-log-output-on-travis, 
    foss-parent-enable-githubreport-when-not-on-travis, foss-parent-spock-tests, plexus-component-metadata
  * removed plugins: assembly, findbugs, invoker, jacoco, jgitflow, pmd
  * removed properties: netbeans.checkstyle.format
  * re-enable *relaxed* enforcer rules
  * site
    * removes dependency-updates-report
    * removed test javadocs
    

### 1.0.4 (2018-11-22)

* update compiler plugin 3.6.1 to 3.8.0
* define release to compile against (https://stackoverflow.com/questions/43102787/what-is-the-release-flag-in-the-java-9-compiler)


### 1.0.3 (2018-11-14)

* update foss-parent 1.5.12 to 1.6.0
* reconfigue javadoc plugin to check syntax only


### 1.0.2 (2016-12-05)

* update foss-parent 1.5.10 to 1.5.12


### 1.0.1 (2016-07-08)

* update foss-parent 1.5.9 to 1.5.10

