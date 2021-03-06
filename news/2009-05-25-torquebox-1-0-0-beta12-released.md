---
title: TorqueBox 1.0.0.Beta12 Released!
author: Bob McWhirter
version: 1.0.0.Beta12
layout: release
tags: [ releases ]
---
We've just released version 1.0.0.Beta12 of the TorqueBox Server.

This release includes updates to documentation, repackaging of Ruby bits as bonafide RubyGems, 
and respecting the TorqueBox-shipped JRuby gem repository from within the server.

This change means much easier configuration of a Rails project for running on TorqueBox.  
At this point, you only have to freeze Rails itself.  Other Gems you depend on may be used from TorqueBox the gem repository.

Additionally, this version of TorqueBox is based upon [JBoss AS 5.1.0.GA](http://www.jboss.org/jbossas/), released over the weekend.

The documentation regarding 
[preparing your Rails application for deployment on TorqueBox](/documentation/1.0.0.Beta12/rails-support.html#preparing-your-rails-application) 
describes the necessary steps.

Per usual, you can [browse the documentation](/documentation/#{page.version}/), [download the complete binary distribution](/download/), 
and [participate on the mailing lists](/community/mailing_lists/).

Here's the list of JIRA issues closed between 1.0.0.Beta11 and 1.0.0.Beta12:

## Bug

* [TORQUE-2](https://jira.jboss.org/jira/browse/TORQUE-2) - Rails support documentation is lacking
* [TORQUE-7](https://jira.jboss.org/jira/browse/TORQUE-7) - Fix endpoint_configuration per documentation

## Feature Request

* [TORQUE-1](https://jira.jboss.org/jira/browse/TORQUE-1) - Support JRUBY_HOME
* [TORQUE-3](https://jira.jboss.org/jira/browse/TORQUE-3) - Ruby packages should be packaged as .gems
* [TORQUE-4](https://jira.jboss.org/jira/browse/TORQUE-4) - JRuby shipped with TorqueBox should include JDBC and TorqueBox gems pre-installed

## Task

* [TORQUE-6](https://jira.jboss.org/jira/browse/TORQUE-6) - Upgrade included JBossAS to 5.1.0.GA


