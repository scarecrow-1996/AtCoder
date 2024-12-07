# CMakeのバージョンを設定
cmake_minimum_required(VERSION 3.13)
# プロジェクト名と使用する言語を設定
project(AtCoder CXX)
# a.outという実行ファイルをmain.cppとhello.cppから作成
add_executable(AtCoder src/main.cpp)
