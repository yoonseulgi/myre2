# java 

### 16진수
- Integer.parseInt(String, n진수)  
  ```java
  Scanner sc = new Scanner(System.in)
  String n = sc.next();
  System.out.println(Integer.parseInt(n, 16));
  ```
- 배열에 한 문자씩 저장하기  
  ```java
  String[] strArray = str.split("");
  ```
  
### 이항계수
- n! / (n-k)!k!  
  ```java
    int a = 1; 
    for(int i = 1; i <= n; i++) 
      a *= i;
  ```
  
### 공집합
- 띄어쓰기 입력 : sc.nextLine();
