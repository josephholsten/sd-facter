Collecting Facts into Server Density with Facter
================================================

Facter is an easy way to add a bunch of new pieces of information to your Server Density monitoring. 

Installation
************

- Install the facter gem on your servers with `gem install facter`
- Go to http://plugins.serverdensity.com/list/
- Click "Install" on the Facter plugin
- Follow the install instructions

Usage
*****

Facter provides a number of metrics out of the box, but most of them are already provided by the default metrics.

The real advantage of using the facter plugin is to have access to any custom facts you've written.

You can learn more about adding custom facts in the Puppet Labs wiki: http://projects.puppetlabs.com/projects/1/wiki/Adding_Facts
