# Corewar

*Résumé: Ce projet a pour but de vous faire réaliser une "arène" virtuelle dans laquelle vont s’affronter des programmes (les "champions"). Vous allez également réaliser un assembleur permettant de compiler ces champions, ainsi qu’un champion pour montrer que vous savez créer de la vie à partir de café.*

## Téléchargement
```git clone https://github.com/manki23/Corewar.git ; cd Corewar ; make```
## Usage
```
Usage: ./corewar [-dump N -v N -c | -ncurse] [[-n number] champion1.cor] ...
#### TEXT OUTPUT MODE ##########################################################
	-dump N	: Dumps memory after N cycles then exits
	-v N	: Verbosity levels, can be added together to enable several
			- 0 : Show only essentials
			- 1 : Show lives
			- 2 : Show cycles
			- 4 : Show operations (Params are NOT litteral ...)
			- 8 : Show deaths
			- 16 : Show PC movements (Except for jumps)
	-c  	: Color, shows verbose with colors
#### NCURSES OUTPUT MODE #######################################################
	-ncurse	: Ncurses output mode
################################################################################
```
