#!/bin/bash


count_files() {
  echo $(ls -1 | wc -l) #  
}


echo "how much"
correct_answer=$(count_files)

while true; do
  read -p "put your guess " guess


  if [[ $guess -eq $correct_answer ]]; then
    echo "congratulation."
    break
  elif [[ $guess -lt $correct_answer ]]; then
    echo "moin que."
  else
    echo "plus que."
  fi
done
