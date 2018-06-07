### Manual Installation (all OSes)

1. Install [Node.js](https://nodejs.org/en/). Use the __stable__ version

2. Install [Ruby](https://www.ruby-lang.org/en/documentation/installation/) if it's not already installed on your computer. You might want to install ruby using homebrew for the same reasons as above.

3. Clone this repo and `cd` into the new repo directory:

    ```shell
    git clone git@github.com:GCDigitalFellows/gcdigitalfellows.github.io.git
    cd gcdigitalfellows.github.io
    ```

4. Install node and ruby components:

    ```shell
    npm install jekyll
    sudo gem install sass -v 3.4.22
    ```
    
5. Run the update data script 
   ```shell
   node get_data
   ```
 Try to resolve `Error: Cannot find module 'X'` error with `npm install X`. Repeat until all packages are installed.
 
