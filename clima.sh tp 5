
API_KEY="TU_CLAVE_API"


CITY="bahia  blanca"

url="https:/api.weartheapi.cpm/v1/current.json?key=${api_key}&q=${CITY"

response=$(curl -s ${curl})




if [ $? -eq 0 ]; then

		temp_actual=$(echo ${response}  | jq '.current.temp_c')
		condicion=$(echo ${response}    | jq -r  '.current.condition.text')
		humedad=$(echo ${response}	| jq '.current.humidity')


		echo "clima actual en ${bahia blanca}:"
		echo" temperatura en ${bahia blanca}°c"
		echo " condicion en ${condicion}"
		echo "Humedad en ${humedad}%"
	else
		echo"error en obtener datos de la API"
	


	fi
