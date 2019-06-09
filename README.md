# dxvk-ipc
Experimental, barely tested but somehow working PoC.<br>
Tested on [DXVK](https://github.com/doitsujin/dxvk) / [D9VK](https://github.com/Joshua-Ashton/d9vk) winelib builds, `GCC 9`, `/tmp` as `tmpfs`.
Any thoughts, proposals or critics are welcomed.

![dxvk-conky-poc-min](https://user-images.githubusercontent.com/10661854/59099400-af59ae80-892b-11e9-8a24-499a90b77db5.png)

 pros | cons
 ---- | ----
 out of game's window | no fullscreen (?)
 you chose how to read data | data not accurate
  ... | ...
 
```
$ ls -1 /tmp/dxvk/*
/tmp/dxvk/compiler
/tmp/dxvk/compute_pipelines
/tmp/dxvk/dev_driver
/tmp/dxvk/dev_name
/tmp/dxvk/dev_vulkan
/tmp/dxvk/dispatch_calls
/tmp/dxvk/draw_calls
/tmp/dxvk/dx_api
/tmp/dxvk/fps
/tmp/dxvk/frametime
/tmp/dxvk/frametime_max
/tmp/dxvk/frametime_min
/tmp/dxvk/graphics_pipelines
/tmp/dxvk/mem_alloc
/tmp/dxvk/mem_used
/tmp/dxvk/render_passes
/tmp/dxvk/samplers
/tmp/dxvk/submissions
/tmp/dxvk/version
``` 
## More examples

![d9vk-conky-poc4-min](https://user-images.githubusercontent.com/10661854/59165376-784ded80-8b23-11e9-8101-c2399c288347.png)

```
$ watch -d "cat /tmp/dxvk/*"
```
