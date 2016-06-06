#-*-coding:utf-8-*-

import random,easygui

secret = random.randint(1,99)
guess = 0
tries = 0

easygui.msgbox('''哈哈...猜数字中文带窗口版本,来玩玩.从1到99.有6次机会.''')

while guess != secret and tries < 6:
	guess = easygui.integerbox('来,输入你觉得对的数字:')
	if not guess: break
	if guess < secret:
		easygui.msgbox(str(guess) + "你猜的数字小了,再来~")
	elif guess > secret:
		easygui.msgbox(str(guess) + "不,不,不...太大了")
	tries = tries + 1
	
if guess == secret:
	easygui.msgbox("恭喜你,猜对了,喜欢玩的话可以再运行一次,答案是不一样的哦~")
else :
	easygui.msgbox("噢,不好意思,6次机会已经用完了,再玩一次程序内部的数字将会改变,但你是可以无限次地运行我哦.")
