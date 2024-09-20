# This repository is deprecated   

## packages_for_gl_ax1800
适用于lean openwrt ipq6000库的插件      
主体采用lean的19.07分支库,缝合sdf8057的库   
## use
feed.conf    
```
src-git luci https://github.com/lazyoop/packages_for_gl_ax1800.git;luci-19.07
src-git packages https://github.com/lazyoop/packages_for_gl_ax1800.git;packages-19.07
```   
then   
```
./scripts/feeds update -a
./scripts/feeds install -a
```
finally
```
make menuconfig
```
# Enjoy~~~


