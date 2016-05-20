# NPL Packages
NPL Packages provide a way to release your NPL modules to be used by someone else at development time.

## Where To Find NPL Packages
Each repository under [NPLPackages](https://github.com/NPLPackages/) is a valid npl_package managed by the community.
> Click [here](https://github.com/LiXizhi/NPLRuntime/wiki/npl_packages) for more details on NPL packages.

If one want to upload their own package here, please make an [issue here](https://github.com/NPLPackages/NPLPackages/issues), and provide links to its code.

## How To Install A Package
Simply create a folder under your development's working directory, create a sub folder called `npl_packages`.
And then run git clone from there. Like this:
```
cd npl_packages
git clone https://github.com/NPLPackages/main.git
```

## How To Load a Package
Any developer who wants to use other people's modules need to call something like:
```lua
NPL.load("npl_packages/some_test_module/")
```

