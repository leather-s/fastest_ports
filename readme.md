# Fastest Ports

## About

This script will loop through a range of ports on an ip address and return the fastest ports(proxies).

Iterates through a specified range of ports (5 times by default), and only returns proxies that are faster than your `ping_limit` on 4 of those 5 iterations.

## Installation
- install latest ruby
- clone this repository
- open terminal and navigate to cloned directory location
- run `gem install bundler`
- run `bundle install`

## Use
- open terminal and navigate to project folder
- run `ruby fastest_ports`

#### Now lets configure the script

- when prompted enter `1`
- when prompted enter url for test site
- when prompted enter your proxy address
- when prompted enter the `port_floor` which is a number indicating the lower limit in the range of ports to be tested.
- when prompted enter the `port_ceiling` which is a number indicating the upper limit in the range of ports to be tested.
- when prompted enter the `ping_limit` which is a number (milliseconds). This integer is the ping time that we want our ports to be faster than

### The script may take several minutes depending on how fast/slow your proxies are. If you have slower proxies I recommend only testing 20-50 ports at a time. If you have faster proxies I recommend testing larger ranges as they will be able to complete faster.  