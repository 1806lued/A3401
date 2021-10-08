# A3401#!/usr/bin/env python3
# -*- coding: utf-8 -*-
"""
Created on Fri Oct  1 20:18:39 2021

@author: edwardlu
"""

import random

num = random.randint(0,100)

guess = int(input('請輸入一個數字'))

while True:
    if(guess > num):
        print('太大')
    elif (guess < num):
        print('太小')
        
    guess = int(input('請再輸入一次'))
    
    break
print("rite!!!!!")
