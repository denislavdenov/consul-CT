# Consul-template example
### This example is based on this repository https://github.com/denislavdenov/consul-lab1
### We using the same configuration as repo above.

# How to use:
1. Fork and clone
2. Do `vagrant up` 
3. Enter in `10.10.66.11` and `10.10.66.12` - You will see that the Nginx welcome page is updated as per what is provided in the key/value
4. Go to localhost:8501 and edit the values for nginx keys
5. Refresh `10.10.66.11` and `10.10.66.12` and check how webpage is modified in real time
