# Restore raw_livox_20260626_094631_0.db3

The original rosbag is larger than the GitHub LFS single-file limit, so it is stored as split parts.

To restore it after cloning:

```bash
cd bags/raw_livox_20260626_094631
cat raw_livox_20260626_094631_0.db3.part-* > raw_livox_20260626_094631_0.db3
sha256sum -c raw_livox_20260626_094631_0.db3.sha256
```
