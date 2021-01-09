# Verctor_Reversal


## R function to reverse the order of a vector


### This code should do the work :smile:

```
vector_reversal <- function(Variable_to_be_reversed){


i <- 0
j <- 1


while(i > (-1*length(Variable_to_be_reversed))){
  
first_position_reversed <- length(Variable_to_be_reversed)

first_reversed <- Variable_to_be_reversed[first_position_reversed]

temp_variable <-  Variable_to_be_reversed[(first_position_reversed + (i))]


if(i == 0){
  reversed_vector <- c()
  
  reversed_vector[j] <- first_reversed
} else{
  reversed_vector[j] <- temp_variable  
}


i <- (i - 1)
j <- (j + 1)

}

print("Here is your reversed vector:")

print(paste(reversed_vector))  

}
```
