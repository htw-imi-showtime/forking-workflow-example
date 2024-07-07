pr=2
for c in 1 2 3; do echo "change $pr.$c" >> index.md ; git add . ; git commit -m "change $pr.$c" ; done


change 1.1
change 1.2
change 1.3

change 2.1
change 2.2
