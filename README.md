---------------------------------------------------------------
mergeNotCombined
---------------------------------------------------------------
Merge Forward and reverse  reads
Example:
Forward: ACTG
Reverse: TACG (complement CGTA)
joinString: NNN
Merge: ACTGNNNCGTA
---------------------------------------------------------------
Running 
---------------------------------------------------------------
`mergetNotCombined` F1.fastq R1.fastq `joinString`
Example:
`mergetNotCombined` F1.fastq R1.fastq 'NNN'
---------------------------------------------------------------
License
--------------------------------------------------------------
This project is licensed under the GPLv3 License - see the [LICENSE](LICENSE) file for details
