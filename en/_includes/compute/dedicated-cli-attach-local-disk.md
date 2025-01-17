`--attach-local-disk`: Properties of the local disk attached to the VM:

* `size`: Disk size in bytes. You can find the possible values in the [list of dedicated host types](../../compute/concepts/dedicated-host.md#host-types-list) and the `yc compute host-type list` command output. For example, for a host of the `intel-6338-c108-m704-n3200x6` type, set `3200000000000` (3200 × 10^9^ B, ~ 2.91 TB). You cannot set a size different from the host disk size.

The `--attach-local-disk` parameter is optional. To attach multiple local disks, specify the parameter as many times as required. For more information, see [{#T}](../../compute/concepts/dedicated-host.md#resource-disks).
