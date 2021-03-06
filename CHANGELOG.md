# Changelog

## v0.0.4 Mar 14, 2016
- Fix #101: vagrant-service-manager version 0.0.4 release @navidshaikh
- Remove manually scp for TLS keys and use machine.communicate.download @bexelbie
- Fix #87 #83: Supports starting OpenShift service as part of config @budhrg @bexelbie @navidshaikh
- Fix #95: Update hook code to call other middleware first @bexelbie
- Fix #94: Do not exit if box is not supported @navidshaikh
- Fixed missing word for plugin installation in README @budhrg
- Fix #91: Renaming the method name flavor to os_variant @lalatendumohanty
- Fix links, typos, formatting in CONTRIBUTING.md @budhrg
- Fix #16 and #72: Enable private networking for VirtualBox if not set @budhrg

## v0.0.3 Mar 01, 2016
- Fix #74: vagrant-service-manager plugin version 0.0.3 release @navidshaikh
- Fix #12 and #21: Restart docker service on 'vagrant up' @budhrg
- Update CONTRIBUTING.md and README.md @bexelbie
- Fix #45: Adds exit status for commands and invalid commands @navidshaikh
- Enhanced the developer instructions for developing the plugin in README @budhrg
- Updated box versioning info @budhrg
- Fix #45: Adds exit status for commands and invalid commands @navidshaikh
- Renames the option machine-readable to script-readable @navidshaikh
- Fix #63: Adds --machine-readable option to box version command @navidshaikh
- Fix #66: Fixing gem build warning @lalatendumohanty
- Adds the filename as class constant @navidshaikh
- Fix #8: Adds subcommand for printing box version
- Fix #59: Prints the error message on stderr @navidshaikh
- Updates openshift connection information output @navidshaikh
- Extends help command with openshift example @navidshaikh
- Adds method to find if a service is running @navidshaikh
- Fix #23: Adds subcommand for displaying openshift information @navidshaikh
- Updates output docker info in README @navidshaikh

## v0.0.2 Feb 17, 2016
- Fixes #53: Prep for version v0.0.2
- Fixes #41: Plugin reports to bring up machine for even help command @navidshaikh
- Updates CHANGELOG.md @navidshaikh
- Fix #41: Fixes the check for finding vagrant box state @navidshaikh
- Adding a version.rb @lalatendumohanty
- Adding steps to build the plugin using Bundler @lalatendumohanty
- Update README with quick start steps @navidshaikh
- Fixes #31: Private key wasn't being sourced for libvirt @bexelbie
- Add notice when copying certificates @bexelbie
- `vagrant service-manager env` return all info @bexelbie
- Fix #4 and #5: Add running machine detection @bexelbie
- Adding objective to the README @lalatendumohanty
- Adds links to gemfile and copr build @navidshaikh
- Adds SPEC file for version 0.0.1 release @navidshaikh

## v0.0.1 Feb 09, 2016
- Updates the source git repository URL
- Restructure the lib directory and sources plugin from module
- Removes unused vagrant password from repository
- Uses net/scp module instead of scp command
- Adds a sub-command for configuring docker daemon vagrant-service-manager env docker
- Ports equivalent functionality of plugin for https://github.com/projectatomic/vagrant-adbinfo
- Renames the plugin and update the rest of repository

@navidshaikh @bexelbie

## Plugin is forked and extended from [vagrant-adbinfo](https://github.com/projectatomic/vagrant-adbinfo)
