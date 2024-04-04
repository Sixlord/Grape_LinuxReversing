# Grape_LinuxReversing

breakpoint설정, 삭제 실습
![pwndbg breakpoint 실습](https://github.com/Sixlord/Grape_LinuxReversing/assets/157137422/6829f140-c9e1-4474-a61f-2617f164cb05)

pwndbg 16진수 출력
![pwndbg 16진수 출력](https://github.com/Sixlord/Grape_LinuxReversing/assets/157137422/f1559ece-3bbd-4fa9-b19f-a035aa1297e2)


hexedit
![hexedit patch](https://github.com/Sixlord/Grape_LinuxReversing/assets/157137422/31db70f2-18b2-4a81-9727-7f2169814e61)


메모리 값 수정
![hex 수정](https://github.com/Sixlord/Grape_LinuxReversing/assets/157137422/62903fcb-a593-4c2c-a4c0-fb0c6810a002)

패치 후 출력
![패치 후 출력](https://github.com/Sixlord/Grape_LinuxReversing/assets/157137422/1ab25636-e98e-4cc0-957c-020b07650ef5)
![패치 후 출력2](https://github.com/Sixlord/Grape_LinuxReversing/assets/157137422/49547426-b593-4f06-adc7-e4c170419021)


------------------------------------------------------------------------------------------------

### C 컴파일 명령어

gcc -o example example.c

### 디버깅, 디버거

→ 디버깅(Debugging) : 프로그램을 분석하는 행위

→ 디버거(Debugger) : 디버깅에 쓰이는 프로그램

### 컴파일과 인터프리팅

- 컴파일 : 고급 프로그래밍 언어로 작성된 소스코드를 기계어로 변환하는 것
- 인터프리팅 : 런타임 상태에 소스코드를 한줄씩 번역하여 프로그램을 구동하는 방식

### 어셈블과 디스어셈블

- 어셈블 : 어셈블리어 → 기계어
- 디스어셈블 : 기계어 → 어셈블리어

### 레지스터(register)

: 숫자를 저장할 수 있는 빠른 저장장치, 중간계산결과 등을 저장

- ebp, esp, eax, ebx, esi 등
- 32비트 앞글자 e, 64비트 앞글자 r

### 메인 메모리, 램(RAM)

: 레지스터보다 느리지만 크기 큰 저장장치

### 스택 메모리(Stack)

: 메모리를 구분한 구역 중 하나로, 프로그램이 실행하는데에 필요한 값을 저장함

- ebp, esp : 스택 메모리를 구분하는 레지스터
    - bp : base pointer, sp : stack pointer
    - ebp에 스택 시작되는 메모리 주소 저장
    - esp에 스택이 끝나는 메모리 주소 저장
