### Kafka Credentials Buildpack
This is an intermediate buildpack (non final) to automatically set up the app environment with kafka credentials from
plain environment variables exposed by a kafka credentials service.

An intermediate buildpack is not capable of executing anything, so another buildpack to "run" the application is still required.

NOTE: While the KAKFA_* environment variables will not show when SSH'ing into an app, they are available to the running application itself.

### References
https://docs.cloudfoundry.org/buildpacks/understand-buildpacks.html
https://docs.cloudfoundry.org/buildpacks/custom.html
https://github.com/SpringerPE/cf-monitoring-buildpack

### License

MIT License