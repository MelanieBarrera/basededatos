# basededatos
CREATE TABLE producto(
productoID INT, 
nombreproducto VARCHAR(20),
precioproducto FLOAT(2),
);

INSERT INTO pruductos VALUES (1,"manzana", 0,20)



CREATE TABLE "productos" (
	"productoID"	INTEGER NOT NULL UNIQUE,
	"nombreproducto"	TEXT NOT NULL UNIQUE,
	"precioproducto"	NUMERIC NOT NULL,
	PRIMARY KEY("productoID" AUTOINCREMENT)
);
