Alternativa ad [[Condizione|if - else]].

```Java
switch (espressione) {
	case val1:
		ist1;
	case val2:
		ist2;
		...
	case valN
		istN;
	default:
		ist;
}

// Esempio

char c = s.charAt(i);
switch (c) {
	case  'a' :
	case  'A' :
		contA++;
		break;
	case  'e' :
	case  'E' :
		contE++;
		break;
	case  'i' :
	case  'I' :
		contI++;
		break;
	...
}
```