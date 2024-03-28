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

File	 	    FunctionName		          StartLine	  EndLine		Cyclomatic complexity
Calculator	Operations::Operations	    15		      16			  1 (jednostavan kod, izuzetno nizak rizik)
Calculator	Operations::ToString	      18 		      20			  1 (jednostavan kod, izuzetno nizak rizik)
Calculator	Run			                    24		      26			  1 (jednostavan kod, izuzetno nizak rizik)
Calculator	evaluateExpression	        28		      72			  12 (umereno kompleksan kod,umeren rizik)
Calculator	Calculate		                74		      186			12  (umereno kompleksan kod,umeren rizik)


File Start
Cognitive complexiy: 5

File	 	FunctionName		StartLine	EndLine		Cyclomatic complexity
Start		Start::main		    5		     24			    3 (jednostavan kod, izuzetno nizak rizik)


