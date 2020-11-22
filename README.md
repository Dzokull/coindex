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

      $ coindex key set ```press_enter```
      
      ? Enter API Key ('https://nomics.com) ```enterAPIKey```

6. Check prices...

      $ coindex check price
      
## usage

#### coindex [options] [commands]

### options
-V  ---version

-h  ---displays command keys
  
### commands

#### key   [command]
  
    -set      --sets the API key

    -show     --Displays the current API key

    -remove   --Deletes the current API key
  
#### check [command]
   
     -price [Options]

        --coin=#coinID    -displays the coin of you liking by ID some ID eg.. BTC, ETH

        --cur=#currency    -default currency is in USD you can change it to like PKG, AUS ...

