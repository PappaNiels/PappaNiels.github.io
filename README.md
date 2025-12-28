# Portfolio website source 

## Build locally
1. Install Ruby
    1. Download and install **Ruby+Devkit** from [RubyInstaller for Windows](https://rubyinstaller.org/). You'll see versions like `Ruby+Devkit 2.7.X (x64)`. Choose a version based on your Windows (64-bit or 32-bit). Most modern systems will use 64-bit.

    2. During the installation:
        - Use the default options.
        - Ensure the "Add Ruby executables to your PATH" option is checked.
        - Once the installation is finished, you'll be prompted to install MSYS2 development toolchain. Go ahead and let it install as it's required for Jekyll and some Ruby gems.

2. Navigate to the repository and open the terminal/command prompt 
3. Install Bundler and Jekyll
```bash
gem install jekyll bundler
```
4. Install Dependencies:
```bash
bundle install
```
5. Build and Run the Jekyll Site
```bash
bundle exec jekyll serve
```

Now, you should be able to access the site locally at [http://localhost:4000](http://localhost:4000).