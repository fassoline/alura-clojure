# forca

Project for Alura Clojure Class

## Usage Lein

	$ lein run

## Usage Java
	
	$ lein uberjar
    $ java -jar target/uberjar/forca-0.1.0-SNAPSHOT-standalone.jar

## Lein Repl History

	(map (fn [x] (* x 2)))
	(def carros [50000.0, 60000.0])
	(require '[forca.core :as forca] :reload)
	(contains? palavra "A")
	(filter (fn [x] (or (< x 2) (> x 4))) numeros)
	(remove (fn [x] (not= (rem x 2) 0)) numeros)
	(->> map map reduce)
	recursão de calda (recur ...)
	funcoes preguiçosas (map reduce filter)
	(def numeros #{1 2 3 4 5})
	(reduce (fn [soma x] (+ soma x) lista))
