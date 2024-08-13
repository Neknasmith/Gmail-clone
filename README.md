# Gmail-clone
#WRITTEN BY NEKNA
#------------import-----------#
#------------color------------#
 bblack="\033[1;30m"            # Black
 M="\033[1;31m"             # Red
 H="\033[1;32m"          # Green
 byellow="\033[1;33m"         # Yellow
 bblue="\033[1;34m"           # Blue
 P="\033[1;35m"          # Purple
 C="\033[1;36m"             # Cyan
 B="\033[1;37m"            # White
 my_color = [
  B,C,P,H]
  warna = random.choice(my_color)
#------------linex def----------#
def linex():
 	print(f'{warna}----------------------------------------{B}')
#------------clear def------------#
def clear():
	clr("clear")
	print(logo)
#------------main def---------#
def NEKNA():
	clear()
	print(f'{B} [{warna}01{B}] RANDOM CLONING ')
	print(f'{B} [{warna}00{B}] EXIT CLONING ')
	option=input(f' {B}[{warna}??{B}] CHOICE MENU >> ')
	if option in ['01','1']:
#------------end--------------#
