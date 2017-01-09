# Recursivitate
 //1.Fibonacci
 int fib(int n)
 {if(n<=2) return 1;
 else return fib(n-1)+fib(n-2);}//AutoApeluri
 
 //2.Cmmdc(Euclid)
 int cm(int a, int b)
 {if(b==0) return a;
 else return cm(b,a%b)}
 
 //3.Cmmdc(scaderi repetate)
 int cmsr(int a, int b)
 {if(a==b) return a;
    if(a>b) return cmsr(a-b,b)
    else return cmsr(a,b-a)}
    
 //4.Putere
 int put(int a, int b)
 {if(b==0)return 1;
 else retrun a * put(a,b-1);}
 
 //5.Suma cifre(a)
 int sc(int a)
 {if(a < 10) return a;
 else return a%10 +sc(a/10);}
 
 //6.Cifra minima a lui a
 int min(int a)
{if(a < 10) return a;
int m=min(a/10);
if(a%10< m) return a%10;
  else return m;}
  
  //7.Numarul de cifre
  int nrc(int a)
  {if(a< 10) return 1;
  else 1+nrc(a/10);}
  
  //8.Prim
  
  
  
  
  
  
  
  
