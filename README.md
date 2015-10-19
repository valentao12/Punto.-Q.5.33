# Punto.-Q.5.33
Further Analysis
Load and run the script fi le, three_circ of Example 5.5.
% Script file: three _ circ

t = 0:0.01:2*pi;

X = cos(t);

Y = sin(t);

Area (X,Y)

hold on

X=2*cos(t);

Y= 2*sin(t);

plot (X,Y)

hold on

X=3*cos(t);Y=3*sin(t);

plot (X,Y)

axis([-3.5 3.5 -3.5 3.5]);

xlabel(‘X’), ylabel(‘Y’),title(‘3 concentric circles’)
