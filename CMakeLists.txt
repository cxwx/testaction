# =====================================================
# this part set in vimrc
# created by Chen Xu
# email: chenxu@mail.ustc.edu.cn
# copyright cx
# Darwin newas.local 17.6.0 Darwin Kernel Version 17.6.0: Tue May  8 15:22:16 PDT 2018; root:xnu-4570.61.1~1/RELEASE_X86_64 x86_64
# created: 2018年 7月10日 星期二 20时17分00秒 CST
# =====================================================
cmake_minimum_required(VERSION 3.0 FATAL_ERROR)
set(PROJECT_NAME cx_tmp)
set(RELEASE_DATE 2018-11-28)
set(PROJECT_VERSION "0.0.1")
set(PROJECT_DESC "chenxu CMakelist.txt tmp ")
set(PROJECT_URL "https://unknown")
set(PROJECT_ISSUES_URL "https://unknown")

add_executable(test p1_test.cpp)
