#!/usr/bin/env ruby
#^syntax detection

forge "https://forgeapi.puppetlabs.com"

# Support for default hiera data in modules
mod "module-data",
  :git => "git://github.com/ripienaar/puppet-module-data.git",
  :ref => "0.0.4"

# Core modules for a basic development environment. You can replace
# some/most of these if you want, but it's not recommended.

mod "saz-dnsmasq", "1.1.0"  

# Optional/custom modules
mod "phathocker-profiles",
  :git => "git://github.com/phathocker/puppet-profiles.git",
  :ref =>"v0.1.0"

# use dependencies defined in metadata.json
#metadata

# use dependencies defined in Modulefile
# modulefile

# A module from the Puppet Forge
# mod 'puppetlabs-stdlib'

# A module from git
# mod 'puppetlabs-ntp',
#   :git => 'git://github.com/puppetlabs/puppetlabs-ntp.git'

# A module from a git branch/tag
# mod 'puppetlabs-apt',
#   :git => 'https://github.com/puppetlabs/puppetlabs-apt.git',
#   :ref => '1.4.x'

# A module from Github pre-packaged tarball
# mod 'puppetlabs-apache', '0.6.0', :github_tarball => 'puppetlabs/puppetlabs-apache'
