INC = include
SRC = src
OBJ = obj
BIN = bin

all: $(BIN)/ejercicio1 $(BIN)/ejercicio2 $(BIN)/ejercicio3 $(BIN)/ejercicio4 $(BIN)/ejercicio18 $(BIN)/ejercicio7 $(BIN)/ejercicioexamen $(BIN)/ej5examfeb2015 $(BIN)/ej2examfeb2015 $(BIN)/ej3examfeb2015 $(BIN)/ej4examfeb2015

$(BIN)/ejercicio1: $(OBJ)/ejercicio1.o
	${CXX} -o $(BIN)/ejercicio1 $(OBJ)/ejercicio1.o

$(OBJ)/ejercicio1.o: $(SRC)/ejercicio1.cpp $(INC)/bintree.h
	${CXX} -c $(SRC)/ejercicio1.cpp -o $(OBJ)/ejercicio1.o -I$(INC)

$(BIN)/ejercicio2: $(OBJ)/ejercicio2.o
	${CXX} -o $(BIN)/ejercicio2 $(OBJ)/ejercicio2.o

$(OBJ)/ejercicio2.o: $(SRC)/ejercicio2.cpp $(INC)/bintree.h
	${CXX} -c $(SRC)/ejercicio2.cpp -o $(OBJ)/ejercicio2.o -I$(INC)

$(BIN)/ejercicio3: $(OBJ)/ejercicio3.o
	${CXX} -o $(BIN)/ejercicio3 $(OBJ)/ejercicio3.o

$(OBJ)/ejercicio3.o: $(SRC)/ejercicio3.cpp $(INC)/bintree.h
	${CXX} -c $(SRC)/ejercicio3.cpp -o $(OBJ)/ejercicio3.o -I$(INC)

$(BIN)/ejercicio4: $(OBJ)/ejercicio4.o
	${CXX} -o $(BIN)/ejercicio4 $(OBJ)/ejercicio4.o

$(OBJ)/ejercicio4.o: $(SRC)/ejercicio4.cpp $(INC)/bintree.h
	${CXX} -c $(SRC)/ejercicio4.cpp -o $(OBJ)/ejercicio4.o -I$(INC)

$(BIN)/ejercicio5: $(OBJ)/ejercicio5.o
	${CXX} -o $(BIN)/ejercicio5 $(OBJ)/ejercicio5.o

$(OBJ)/ejercicio5.o: $(SRC)/ejercicio5.cpp $(INC)/bintree.h
	${CXX} -c $(SRC)/ejercicio5.cpp -o $(OBJ)/ejercicio5.o -I$(INC)

$(BIN)/ejercicio18: $(OBJ)/ejercicio18.o
	${CXX} -o $(BIN)/ejercicio18 $(OBJ)/ejercicio18.o

$(OBJ)/ejercicio18.o: $(SRC)/ejercicio18.cpp $(INC)/bintree.h
	${CXX} -c $(SRC)/ejercicio18.cpp -o $(OBJ)/ejercicio18.o -I$(INC)

$(BIN)/ejercicio7: $(OBJ)/ejercicio7.o
	${CXX} -o $(BIN)/ejercicio7 $(OBJ)/ejercicio7.o

$(OBJ)/ejercicio7.o: $(SRC)/ejercicio7.cpp $(INC)/bintree.h
	${CXX} -c $(SRC)/ejercicio7.cpp -o $(OBJ)/ejercicio7.o -I$(INC)

$(BIN)/ejercicioexamen: $(OBJ)/ejercicioexamen.o
	${CXX} -o $(BIN)/ejercicioexamen $(OBJ)/ejercicioexamen.o

$(OBJ)/ejercicioexamen.o: $(SRC)/ejercicioexamen.cpp $(INC)/bintree.h
	${CXX} -c $(SRC)/ejercicioexamen.cpp -o $(OBJ)/ejercicioexamen.o -I$(INC)

$(BIN)/ej5examfeb2015: $(OBJ)/ej5examfeb2015.o
	${CXX} -o $(BIN)/ej5examfeb2015 $(OBJ)/ej5examfeb2015.o

$(OBJ)/ej5examfeb2015.o: $(SRC)/ej5examfeb2015.cpp $(INC)/bintree.h
	${CXX} -c -std=c++11 $(SRC)/ej5examfeb2015.cpp -o $(OBJ)/ej5examfeb2015.o -I$(INC)

$(BIN)/ej2examfeb2015: $(OBJ)/ej2examfeb2015.o
	${CXX} -o $(BIN)/ej2examfeb2015 $(OBJ)/ej2examfeb2015.o

$(OBJ)/ej2examfeb2015.o: $(SRC)/ej2examfeb2015.cpp $(INC)/bintree.h
	${CXX} -c -std=c++11 $(SRC)/ej2examfeb2015.cpp -o $(OBJ)/ej2examfeb2015.o -I$(INC)

$(BIN)/ej3examfeb2015: $(OBJ)/ej3examfeb2015.o
	${CXX} -o $(BIN)/ej3examfeb2015 $(OBJ)/ej3examfeb2015.o

$(OBJ)/ej3examfeb2015.o: $(SRC)/ej3examfeb2015.cpp $(INC)/bintree.h
	${CXX} -c -std=c++11 $(SRC)/ej3examfeb2015.cpp -o $(OBJ)/ej3examfeb2015.o -I$(INC)

$(BIN)/ej4examfeb2015: $(OBJ)/ej4examfeb2015.o
	${CXX} -o $(BIN)/ej4examfeb2015 $(OBJ)/ej4examfeb2015.o

$(OBJ)/ej4examfeb2015.o: $(SRC)/ej4examfeb2015.cpp $(INC)/bintree.h
	${CXX} -c -std=c++11 $(SRC)/ej4examfeb2015.cpp -o $(OBJ)/ej4examfeb2015.o -I$(INC)

clean:
	rm $(OBJ)/*.o $(BIN)/*
