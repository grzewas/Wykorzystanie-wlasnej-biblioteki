public class Point – punkt, zawiera jego współrzędne w zmiennych typu double (X,Y)

public Point() – konstruktor tworzący punkt o współrzędnych (1,1)
public Point(double X, double Y) - konstruktor tworzący punkt o współrzędnych (X,Y)


public class Trojkat – trójkąt, zawiera dane o bokach tego trójkąta w zmiennych typu double (a,b,c)

public Trojkat() – konstruktor tworzący trójkąt o bokach 3,4,5
public Trojkat(double a, double b, double c) - konstruktor tworzący trójkąt o bokach a,b,c
public Trojkat(Point A, Point B, Point C) - konstruktor tworzący trójkąt o bokach a,b,c, licząc długości boków z punktów, które są wierzchołkami tego trójkąta
public double KatA() – metoda licząca kąt między bokami b,c
public double KatB() – metoda licząca kąt między bokami a,c
public double KatC() – metoda licząca kąt między bokami a,b
public double ObwodTrojkata() – metoda licząca obwód trójkąta
public double PoleTrojkata() – metoda licząca pole trójkąta



Do programu należy wpisać boki trójkąta (boki oznaczone symbolami a,b,c). Program po użyciu przycisku „LICZ!” policzy i wyświetli pole, obwód oraz wszystkie trzy kąty tego trójkąta w stopniach.





