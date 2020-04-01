---------------------------------------------------------------
mergeNotCombined
---------------------------------------------------------------
Merge Forward and reverse  reads<br/>
Example:<br/>
Forward: ACTG<br/>
Reverse: TACG (complement CGTA)<br/>
joinString: NNN<br/>
Merge: ACTGNNNCGTA<br/>

---------------------------------------------------------------
Running 
---------------------------------------------------------------
`mergetNotCombined` F1.fastq R1.fastq `joinString`<br/>
Example:<br/>
`mergetNotCombined` F1.fastq R1.fastq 'NNN'<br/>

---------------------------------------------------------------
License
--------------------------------------------------------------
This project is licensed under the GPLv3 License - see the [LICENSE](LICENSE) file for details<br/>

---------------------------------------------------------------
Authors
---------------------------------------------------------------
Benavides A(1), Alzate JF (2),(3) and Cabarcas F (1),(2)<br/>
1.	Grupo Sistemic, Departamento de Ingeniería Electrónica, Facultad de Ingenieria, Universidad de Antioquia.<br/>
2.	Centro Nacional de Secuenciacion Genomica-CNSG, Sede de Investigación Universitaria SIU, Universidad de Antioquia<br/>
3.	Grupo de Parasitología, Departamento de Microbiología y Parasitología, Facultad de Medicina, Universidad de Antioquia<br/>

