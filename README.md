# Oshw2

## 사용자 정의 메모리 할당 라이브러리 (smalloc)

# 소개
smalloc은 사용자가 메모리 할당 및 해제를 관리할 수 있도록 하는 사용자 정의 메모리 할당 라이브러리이다. 이 라이브러리는 mmap을 사용하여 메모리를 할당하며, 메모리 블록을 관리하기 위해 헤더 구조체를 사용한다.

# 기능
smalloc: 요청된 크기의 메모리 블록을 할당한다.
sfree: 할당된 메모리 블록을 해제한다.
srealloc: 할당된 메모리 블록의 크기를 재조정한다.
smalloc_mode: 다양한 할당 모드(best-fit, worst-fit, first-fit)를 사용하여 메모리를 할당한다.
smdump: 현재 할당된 메모리 블록과 해제된 메모리 블록의 상태를 출력한다.

# 사용법
smalloc.h와 smalloc.c 파일을 프로젝트에 포함시킨다.
smalloc.h 파일을 #include하여 사용한다.
Makefile을 사용하여 프로그램을 컴파일하고 실행한다.
