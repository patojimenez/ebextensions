# ebextensions
Customizing and Configuring AWS Elastic Beanstalk (EBS) Environments

## How to Use
* Create .ebextensions directory under your project root.
* Copy the `*.config` files into the directory.
* Deploy project to EBS. 

## sidekiq
* Tested to be working on Configuration: 64bit Amazon Linux 2014.09 v1.2.0 running Ruby 2.1 (Passenger Standalone)
* Need to set `RAILS_ENV` environment variable which is used in `0003_sidekiq.config`.
* [Source](https://gist.github.com/gcarrion-gfrmedia/11396682).


