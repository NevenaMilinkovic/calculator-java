Statička analiza koda

File name Calculator:


Linija koda	Zapažanje

1		Move tfhis file to a named package
4		Savetuje promenu klase u private tip
18		Preimenovati metod ’’ToString“ da se ne bi došlo do zabune jer u supraklasi java.lang.Objects postoji metod ’’toString’’
24		Preimenovati metod ’’Run’’
70		Automatski ispisuje vrednost i ne čuva je privremeno u promenljivoj 
		’’ textResult’’;
74		Preimenovati metod ’’Calculate’’
183		CodeSmell: nepotreban return



File name: Start

Linija koda	Zapažanje

1		Premestiti fajl u imenovani paket
6		Preimenovati lokalnu promenljivu ’’Expression’’
8		Preporučuje se da umesto ’’System.out.’’ koristimo ’’logger.’’ 
19.		Preporučuje se da umesto ’’System.out.’’ koristimo ’’logger.’’ 

LOC(zbirni za fajlove Calculator i Start)=188+26=214

File Calculator
Cognitive complexiy: 45

File	 	    FunctionName		         		
Calculator	Operations::Operations	      Cyclomatic complexity:  1 (jednostavan kod, izuzetno nizak rizik)
Calculator	Operations::ToString	      Cyclomatic complexity: 1 (jednostavan kod, izuzetno nizak rizik)
Calculator	Run			      Cyclomatic complexity: 1 (jednostavan kod, izuzetno nizak rizik)
Calculator	evaluateExpression	      Cyclomatic complexity: 12 (umereno kompleksan kod,umeren rizik)
Calculator	Calculate		      Cyclomatic complexity: 12  (umereno kompleksan kod,umeren rizik)


File Start
Cognitive complexiy: 5

File	 	FunctionName		StartLine	EndLine		Cyclomatic complexity
Start		Start::main		    5		     24			    3 (jednostavan kod, izuzetno nizak rizik)


