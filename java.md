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

### 문자열 반대로 출력
- __거꾸로__ 라는 단어가 나오면 __stack__ 사용하기  
  ```java
  import java.util.*;
  Stack st = new Stack();
  print(st) // stack 출력
  st.push(값);
  st.pop();
  ```
- 2가지 조건을 비교하면 될 때 __boolean__ 사용하기  
  ex) <~> 괄호 안의 내용 출력 : < 일 때 참, > 일 때 거짓  
