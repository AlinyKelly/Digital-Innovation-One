# Resolução da LISTA DE EXERCÍCIO 1 - NIVELAMENTO - URI Judge Online
**Linguagem: Java**

**UNIFOR - Universidade de Fortaleza**

**Curso** - Análise e Desenvolvimento de Sistemas 2021.2

**Disciplina** - Programação Orientada a Objetos

**Professor** - Maikol Magalhães Rodrigues

------------------------------------------------------------------------------------------

[Problema 1000 - Hello World](https://www.urionlinejudge.com.br/judge/pt/problems/view/1000)

**_Resolução_**

```
import java.io.IOException;
 
public class Main {
 
    public static void main(String[] args) throws IOException {
 
         System.out.println("Hello World!"); 
 
    }
 
}
```

[Problema 1001 - Extremamente Básico](https://www.urionlinejudge.com.br/judge/pt/problems/view/1001)

**_Resolução_**

```

```

[Problema 1004 - Produto Simples](https://www.urionlinejudge.com.br/judge/pt/problems/view/1004)

**_Resolução_**

```


```

[Problema 1005 - Média 1](https://www.urionlinejudge.com.br/judge/pt/problems/view/1005)

**_Resolução_**

```

```

[Problema 1035 - Teste de Seleção 1](https://www.urionlinejudge.com.br/judge/pt/problems/view/1035)

**_Resolução_**

```
import java.io.IOException;
import java.util.Scanner;
 
public class Main {
 
    public static void main(String[] args) throws IOException {
 
       Scanner input = new Scanner(System.in);
       
       int A = input.nextInt();
       int B = input.nextInt();
       int C = input.nextInt();
       int D = input.nextInt();
       
       if(B > C && D > A && C + D > A + B & C > 0 && D > 0 && A % 2 == 0){
           
           System.out.println("Valores aceitos");
       } else {
           System.out.println("Valores nao aceitos");
       }
       
       input.close();
 
    }
 
}
```

[Problema 1079 - Médias Ponderadas](https://www.urionlinejudge.com.br/judge/pt/problems/view/1079)

**_Resolução_**

```
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
        Scanner entrada = new Scanner(System.in);
        int i;
        int N = entrada.nextInt();
        for (i = 1; i <= N; i = i + 1) {
            float nota1 = entrada.nextFloat();
            float nota2 = entrada.nextFloat();
            float nota3 = entrada.nextFloat();
            float mediaPonderada = (nota1 * 2 + nota2 * 3 + nota3 * 5) / 10;
            System.out.printf("%.1f\n", mediaPonderada);
        }
    }
}

```

[Problema 1095 - Sequencia IJ 1](https://www.urionlinejudge.com.br/judge/pt/problems/view/1095)

**_Resolução_**

```
import java.io.IOException;

public class Main {
 
    public static void main(String[] args) throws IOException {
 
        int i = 1;
        for (int j = 60; j >= 0; j = j - 5) {
            System.out.println("I=" + i + " J=" +j);
            i = i + 3;
        }
    }
}

```

[Problema 1096 - Sequencia IJ 2](https://www.urionlinejudge.com.br/judge/pt/problems/view/1096)

**_Resolução_**

```
import java.io.IOException;

public class Main {
 
    public static void main(String[] args) throws IOException {
 
        int cont = 0;
        int seq = 7;
        for (int i = 1; i <= 9;) {
            System.out.println("I=" + i + " J=" + seq);
            seq--;
            cont++;
                if (cont == 3) {
                    i = i + 2;
                    cont = 0;
                    seq = 7;
                }
        }
 
    }
 
}

```

[Problema 1114 - Senha Fixa ](https://www.urionlinejudge.com.br/judge/pt/problems/view/1114)

**_Resolução_**

```
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
 
        Scanner input = new Scanner(System.in);
        int senha=0;

        while (senha != 2002) {
            senha = input.nextInt();
            if (senha != 2002) {
                System.out.println("Senha Invalida");
            } else {
                System.out.println("Acesso Permitido");
            }
        }
    }
}
```

[Problema 1145 - Sequência Lógica 2](https://www.urionlinejudge.com.br/judge/pt/problems/view/1145)

**_Resolução_**

```
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
 
        Scanner entrada = new Scanner(System.in);
		int X = entrada.nextInt();
		int Y = entrada.nextInt();
		int cont = 1;
		for (int i = 1; i <= Y; i++) {
			System.out.print(i);
			if (i % X == 0) System.out.println("");
			else System.out.print(" ");

		}
 
    }
 
}
```

[Problema 1151 - Fibonacci Fácil](https://www.urionlinejudge.com.br/judge/pt/problems/view/1151)

**_Resolução_**

```
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
 
       Scanner entrada = new Scanner(System.in);
        int N = entrada.nextInt();
        int proxN, antN = 0, atualN = 1;
        for (int i = 1; i <= N; i++) {
        	if (i == N) System.out.println(antN);
        	else System.out.print(antN + " ");
        	proxN = antN + atualN;
        	antN = atualN;
        	atualN = proxN;
        }
 
    }
 
}
```

[Problema 1153 - Fatorial Simples](https://www.urionlinejudge.com.br/judge/pt/problems/view/1153)

**_Resolução_**

```
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
 
        Scanner entrada = new Scanner(System.in);
        int N = entrada.nextInt();
        int fatorial = 1;
        for (int i = 1; i <= N; i++) {
        	fatorial *= i;
        }
        System.out.println(fatorial);
    }
 
}
```

[Problema 1155 - Sequencia S](https://www.urionlinejudge.com.br/judge/pt/problems/view/1155)

**_Resolução_**

```
import java.io.IOException;

public class Main {
 
    public static void main(String[] args) throws IOException {
 
       double S = 1;
    	for (int i = 2; i <= 100; i++) {
    		S += 1.00 / i;
    	}
    	System.out.println(String.format("%.2f", S));
 
    }
}
```

[Problema 1165 - Número Primo](https://www.urionlinejudge.com.br/judge/pt/problems/view/1165)

**_Resolução_**

```
import java.io.IOException;
import java.util.Scanner;

public class Main {
 
    public static void main(String[] args) throws IOException {
 
        Scanner entrada = new Scanner(System.in);
        int N = entrada.nextInt();
        int X, cont;
        for (int i = 0; i < N; i++) {
        	cont = 0;
        	X = entrada.nextInt();
        	for (int j = 2; j < X; j++) {
        		if (X % j == 0) cont++;
        	}
        	if (cont == 0) System.out.println(X + " eh primo");
        	else System.out.println(X + " nao eh primo");
        }
 
    }
 
}
```

[Problema 1193 - Conversão entre bases](https://www.urionlinejudge.com.br/judge/pt/problems/view/1193)

**_Resolução_**

```
import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
import java.io.PrintWriter;

/**
 * @author Brian Yeicol Restrepo Tangarife 
 */

public class Main {
    static BufferedReader in = new BufferedReader(new InputStreamReader(System.in));
    static PrintWriter out = new PrintWriter(System.out);
 
    public static void main(String[] args) throws IOException {
        int x = readInt();
        String[] cases;
        String number, base;
        int decimal;
        int caseNumber = 0;
        while (caseNumber++ < x) {
            cases = read().split("\\s");
            number = cases[0];
            base = cases[1];
            out.println("Case " + caseNumber + ":");
            switch (base) {
                case "bin":
                    decimal = Integer.parseInt(number, 2);
                    out.println(decimal + " dec");
                    out.println(Integer.toString(decimal, 16) + " hex\n");
                    break;
                case "dec":
                    decimal = Integer.parseInt(number);
                    out.println(Integer.toString(decimal, 16) + " hex");
                    out.println(Integer.toString(decimal, 2) + " bin\n");
                    break;
                case "hex":
                    decimal = Integer.parseInt(number, 16);
                    out.println(decimal + " dec");
                    out.println(Integer.toString(decimal, 2) + " bin\n");
                    break;
            }
        }
        out.close();
    }

    private static String read() throws IOException {
        return in.readLine();
    }

    private static int readInt() throws IOException {
        return Integer.parseInt(in.readLine());
    }
 
}
```

[Problema 2760 - Entrada e Saída de String](https://www.urionlinejudge.com.br/judge/pt/problems/view/2760)

**_Resolução_**

```
import java.io.IOException;
import java.util.Scanner;
import java.util.Locale;

/**
 * @author Rodrigo CavanhaMan 
 */

public class Main {
	public static void main(String[] args) {
		Locale.setDefault(new Locale("en", "US"));
		Scanner sc = new Scanner(System.in);

		String[] a = new String[40];
		String input = sc.nextLine();
		a = input.split("");
		int ta=a.length;
		
		String[] b = new String[40];
		input = sc.nextLine();
		b = input.split("");
		int tb=b.length;
		
		String[] c = new String[40];
		input = sc.nextLine();
		c = input.split("");
		int tc=c.length;
		
		for(int i=0 ; i<ta ; i++) System.out.printf("%s",a[i]);
		for(int i=0 ; i<tb; i++) System.out.printf("%s",b[i]);
		for(int i=0 ; i<tc; i++) System.out.printf("%s",c[i]);
		System.out.println();
		
		for(int i=0 ; i<tb ; i++) System.out.printf("%s",b[i]);
		for(int i=0 ; i<tc; i++) System.out.printf("%s",c[i]);
		for(int i=0 ; i<ta; i++) System.out.printf("%s",a[i]);
		System.out.println();
		
		for(int i=0 ; i<tc; i++) System.out.printf("%s",c[i]);
		for(int i=0 ; i<ta; i++) System.out.printf("%s",a[i]);
		for(int i=0 ; i<tb; i++) System.out.printf("%s",b[i]);
		System.out.println();
		
		if(ta>10)ta=10;
		if(tb>10)tb=10;
		if(tc>10)tc=10;
		for(int i=0 ; i<ta; i++) System.out.printf("%s",a[i]);
		for(int i=0 ; i<tb; i++) System.out.printf("%s",b[i]);
		for(int i=0 ; i<tc; i++) System.out.printf("%s",c[i]);
		System.out.println();
		
		sc.close();
	}
}
```

[Problema 2837 - Sequência](https://www.urionlinejudge.com.br/judge/pt/problems/view/2837)

**_Resolução_**

```

```