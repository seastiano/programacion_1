# programacion_1
actividades de programación 1.sebastian ortiz soto
 %ejercicio graficacion 
 X=linspace(0,2*pi,20);
 Y=sin(X);
 Y1=cos(X);
 Y2=Y+Y1;
 Y3=Y-Y1;
 plot(X,Y,'-g')
 hold on
 plot(X,Y1,'-M')
 hold on
 plot(X,Y2,'K')
 hold on 
 plot(X,Y3,'r--')
 box on
 grid on
 xlabel('vector ´x´')
 ylabel('funcion aplicada a ´x´')
 title('ejerciocio de graficacion') 
 legend('sin','cos','y2','y3')
 
axis ('normal')
axis on
 
 
