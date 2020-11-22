# coindex

Coindex is a simple command line interface program that checks for the prices of crypto-currencies.
To be able to use Coindex you must have an API key from https://nomics.com. Its free (Please read carefully the Terms and conditions).

## installation
1. clone this repository
  
      $ git clone 'https://github.com/Dzokull/coindex.git'

2. initialize npm

      $ npm init

3. install npm pakages.

      $ npm install

4. Create a link to the terminal

      $ npm link
      
      --LINUX
      
      $ sudo npm link

5. Set API key..

      $ coindex key set ```press enter```
      
      ? Enter API Key ('https://nomics.com) ###enterKey

6. Check prices...

      $ coindex check prices
      

##usage

coindex [potions] [commands]

###options
-V  ---version

-h  ---displays command keys
  
###commands

key   Manage API Keys -- https://nomics.com
  
check

help
