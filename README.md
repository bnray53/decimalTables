Notes:

a, b, and c will be integer variables incremented to give all possible variations within range

!!!Need to code some of these with ability to automatically skip those that can be reduced into already displayed form!!! This will be denoted by a * in the GCF column. This is a future project and as of now does not effect preformance just has reduciable fractions in the division tables.


Table Key

No.		Algebraic		code{result}				Range			Result	GCF 	Complete

1		(a*pi)/b		(a*Math.PI)/b				100>=a>0		10000	*		Y
													100>=b>0
2		be^a 			b*(Math.exp(a))				50>=a>=-50		10000			Y
													100>=b>0
3		ln(a/b)			Math.log((a/b))				100>=a>0		10000	*		Y
													100>=b>0
4		ln(be^a)		Math.log(b*Math.exp(a))		50>=a>=-50		10000			Y
													100>=b>0
5		ln((e^a)/b)		Math.log(Math.exp(a)/b)		50>=a>=-50		10000			Y
													100>=b>0
6		(e^a)/b 		Math.exp(a)/b 				50>=a>=-50		10000			Y
													100>=b>0	
7		c+(a*pi)/b		c+(a*Math.PI)/b				100>=a>0		300000	*		N
													100>=b>0									
													30>=c>=0
8		c-(a*pi)/b		c-(a*Math.PI)/b				100>=a>0		300000	*		N
													100>=b>0									
													30>=c>=0
9		(a*pi)/b-c		((a*Math.PI)/b)-c			100>=a>0		300000	*		N
													100>=b>0									
													30>=c>=0
													