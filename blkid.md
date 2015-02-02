# blkid

`util-linux` package.

Get UUID, label and filesystem type for all partitions

    sudo blkid

Sample output:

	/dev/sda2: LABEL="DATA" UUID="E4EEDB25EEDAEF34" TYPE="ntfs"
	/dev/sdb1: LABEL="ESP" UUID="9E91-F4F8" TYPE="vfat"
	/dev/sdb2: LABEL="DIAGS" UUID="ECC5-8CEC" TYPE="vfat"
	/dev/sdb4: LABEL="WINRETOOLS" UUID="0058C6EB58C6DE92" TYPE="ntfs"
	/dev/sdb5: LABEL="OS" UUID="4C38CCBD38CCA6F4" TYPE="ntfs"
	/dev/sdb6: LABEL="PBR Image" UUID="C2CE5FDBCE5FC677" TYPE="ntfs"
	/dev/sdb7: UUID="3fabbe75-0c62-4705-a3ad-4e87c5dcc143" TYPE="ext4"
	/dev/sdb8: UUID="56886cc6-e247-488a-9acf-a07a99cfa3ca" TYPE="ext4"
	/dev/sdb9: UUID="bbc2c9bf-4846-44d1-81c0-eade6d2dcefb" TYPE="swap"