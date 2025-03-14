<div style="text-align: center;">
  <img src="icon.svg" alt="tools-shared" style="width:200px; height:200px;"/>
</div>


# tools-shared
The reusable tools of lynx repository

## [Usage]
### Pull the source code
You can download the code of the tools-shared tool repository to your local machine via git clone or any other method.  

### Synchronize dependencies.
```bash
cd tools-shared
./hab sync -f .
```
### Initialize the environment.
After this step, a sub-command "git lynx check" will be added to the git tool.  
```bash
source envsetup.sh
```

### Run check
```bash
git lynx check --help
git lynx check --list
git lynx check
```

### Custom configuration
tools-shared has built-in default configurations. To meet your needs, you can manually provide a configuration file named tools-shared.yml in the root directory of the repository to override the default configurations.  

You can continue to check the detailed configuration information [here](./docs/README_CONFIGURATION.md).


### Contributing Guide
We welcome you to join and become a member of tools-shared Authors. It's people like you that make this project great.

Please refer to our [contributing guide](CONTRIBUTING.md) for details.


## [License]
tools-shared is Apache licensed, as found in the [LICENSE](LICENSE) file.
