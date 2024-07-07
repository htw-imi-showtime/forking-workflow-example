pr=3
for c in 1 2 3; do echo "change by bkleinen $pr.$c" >> index.md ; git add . ; git commit -m "change by bkleinen $pr.$c" ; done

pr=3
for c in 1 2 3; do echo "change $pr.$c" >> index.md ; git add . ; git commit -m "change $pr.$c" ; done


change 1.1
change 1.2
change 1.3

change 2.1
change 2.2
change 2.3

change by bkleinen 3.1
