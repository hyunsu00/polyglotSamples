# CMake 프로그램의 최소 버전
cmake_minimum_required(VERSION 3.0.0)

# 프로젝트 정보
project(HelloWorld VERSION 0.1.0)

# CTest는 cmake로 구성한 빌드환경에 빌드 및 테스트를 수행하고 
# 그 결과를 dashboard에 게재할 수 있도록 도와줍니다.
include(CTest)
enable_testing()

# 실행파일 생성
add_executable(HelloWorld main.cpp)

# 데비안 패키지 생성
# ex) make package
set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
