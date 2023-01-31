# PorfolioAppDjango
Portfolio App using Django hosted on EC2 instance

## Purpose 
This is an ongoing project to test different deployement methods available with AWS. 
Initially this app is being developed in EC2 instance as a Dev instance. Later it will be published using AWS CI/CD tools.
Methods like ElasticBeanstalk, Amplify will also be tried and compared on different parameters like ease of use, cost etc.

## Dev Notes -
*Day1* - Created EC2 instance, created environment, connected git
  
    Issue #1 - Git has stopped passwork auth, classic tocken (from Developer settings) also did not work. 
    Resolution - fine-graned tockens worked 

    Issue #2 - SQLite version compatibility problem with DJango.  
    Resolution - https://github.com/Miserlou/Zappa/issues/1880#issuecomment-606710104
