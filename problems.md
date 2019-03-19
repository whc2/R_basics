### /tmp/ full
> df -lh /tmp/
```
Filesystem            Size  Used Avail Use% Mounted on
/dev/mapper/vg_qnode1-lv_root
                       50G   50G     0 100% /
```

tmp directory is full. So, we can't write temp files. When run R

> R

> Fatal error: cannot create 'R_TempDir'

remove useless files, to increase tmp disk.
