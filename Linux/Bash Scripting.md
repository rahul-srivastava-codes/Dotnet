
# echo "date :" $date
# pwd
# cal
# res=$(pwd)
# echo $res 
# echo "hello" | rev
# whoami
# uname

# echo $USER

# read n1 n2
# res=$((n1+n2))
# res=$((n1+n2))
# r=$(expr $n1 + $n2)
# echo $r
# echo $res

# num1=1
# num2=2
# num3=3
# num4=4
# str="Rahul"
# echo $num1
# echo $num2
# echo $num3
# echo $num4
# echo $str
# echo "Directory: $num4"
# echo "Directory: $PWD"
# echo "Date: $(date)"
# date

# read l b
# area=$((l*b))
# area1=$(expr $l \* $b)
# echo $area
# echo $area1

read n1
# if [ n1 \% 2 == 0 ]
if (( n1%2 == 0))
then
    echo "Even"
else
    echo "Odd"
fi
