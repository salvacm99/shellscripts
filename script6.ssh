read -p "Introduce unos litros de agua " litros
while [[ $litros -lt 0 ]]
do read -p "Introduce unos litros de agua " litros
done
if [[ $litros -le 50 ]]
then 
let total=20
else if [[ $litros -le 200 ]]
then 
litrossinprimeros=$((litros-50))
total=`echo "$litrossinprimeros*0.2 + 20" | bc`
else if [[ $litros -gt 200 ]]
then 
litrossinprimeros=$((litros-200))
total=`echo "$litrossinprimeros*0.1 + 50" | bc`
fi
fi
fi
echo "El coste total es de $total"
