# Copyright 2022, Antonio Alvarado Hernández

main.png: main.gv
	dot -Tpng -o main.png main.gv

main.gv: main.m4
	m4 main.m4 > main.gv

main.gv: global.gv usa.gv uk.gv germany.gv italy.gv spain.gv venezuela.gv

# EOF
