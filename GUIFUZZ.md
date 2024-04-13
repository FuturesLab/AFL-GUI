afl director - /home/prikshit/work/AFL - ./afl-fuzz

afl-fuzz.c contains codebase of afl-fuzz

Compile afl-fuzz.c -> make afl-fuzz

Projects in - /home/prikshit/work/asst

Calculator directory -
/home/prikshit/work/asst/calc

Fuzzgoat directory -
/home/prikshit/work/asst/fuzzgoat

If you open a new terminal set -
export AFL_SKIP_CPUFREQ=1

Command to run -

/home/prikshit/work/AFL/afl-fuzz -t 30000+ -i in -o out -g /home/prikshit/Downloads/gui_interaction.py -n -- /usr/bin/gnome-calculator

Tail the logs -
tail -f -n 100 log.txt
