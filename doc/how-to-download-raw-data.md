# How to download raw data of Shinobi III gameplay for the VidGame-LLM project

## 1. Download the bk2 files
1.1 Go to https://github.com/courtois-neuromod/shinobi

1.2 Clone the repository locally  
```$ git clone https://github.com/courtois-neuromod/shinobi```

1.3 Go to the folder where the bk2 files are stored (example: subject 1 - session 3)  
```$ cd ~/shinobi/sub-01/ses-003/gamelogs```

1.4 Download the bk2 files with DataLad  
```$ datalad get *.bk2```

1.5 Copy the bk2 files to the appropriate folder in VidGame-LLM repository  
```$ cp *.bk2 ~/VidGame-LLM/data/raw_data/sub-01/ses-003/```

1.6 Do again for all subjects and sessions (ATTENTION: must create other session folders in VidGame-LLM repository first)

## 2. Download the event files

1.1 Go to the folder where the event files are stored (example: subject 1 - session 3)  
```$ cd ~/shinobi/sub-01/ses-003/func```

1.2 Download the event files with DataLad  
```$ datalad get *.tsv```

1.3 Copy the event files to the appropriate folder  
```$ cp *.tsv ~/VidGame-LLM/data/raw_data/sub-01/ses-003/```

1.4 Do again for all subjects and sessions
