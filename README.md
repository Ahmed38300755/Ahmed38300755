├── BCCD
│   ├── Annotations
│   │       └── BloodImage_00XYZ.xml (364 items)
│   ├── ImageSets       # Contain four Main/*.txt which split the dataset
│   └── JPEGImages
│       └── BloodImage_00XYZ.jpg (364 items)
├── dataset
│   └── mxnet           # Some preprocess scripts for mxnet
├── scripts
│   ├── split.py        # A script to generate four .txt in ImageSets
│   └── visualize.py    # A script to generate labeled img like example.jpg
├── example.jpg         # A example labeled img generated by visualize.py
├── LICENSE
└── README.md
<annotation>
	<folder>JPEGImages</folder>
	<filename>BloodImage_00000.jpg</filename>
	<path>/home/pi/detection_dataset/JPEGImages/BloodImage_00000.jpg</path>
	<source>
		<database>Unknown</database>
	</source>
	<size>
		<width>640</width>
		<height>480</height>
		<depth>3</depth>
	</size>
	<segmented>0</segmented>
	<object>
		<name>WBC</name>
		<pose>Unspecified</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>260</xmin>
			<ymin>177</ymin>
			<xmax>491</xmax>
			<ymax>376</ymax>
		</bndbox>
	</object>
    ...
	<object>
		...
	</object>
</annotation>
