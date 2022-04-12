#include<windows.h>
#include <GL/glut.h>
#include<cmath>
float p=-10.0;


void drawLine(float x1, float y1, float x2, float y2)
{
    glBegin(GL_LINES);
    glVertex2f(x1,y1);
    glVertex2f(x2,y2);
    glEnd();
}
void makeCircle(float r, float x_center, float y_center)
{
    int deg = 0;
    float theta, x, y;
    glPointSize(4);
    glBegin(GL_POLYGON);

    while(deg < 360)
    {

        theta = (deg * M_PI) / 180;
        x = x_center + r*cos(theta);
        y = y_center + r*sin(theta);
        glVertex2f(x, y);
        deg++;
    }
    glEnd();
}

void stickman(float X2, float Y2)
{

    makeCircle(1,X2,Y2);
    drawLine(X2,-1+Y2,X2,-4+Y2);
    drawLine(-2.5+X2,-1.5+Y2,2.5+X2,-1.5+Y2);
    drawLine(X2,-4+Y2,-2+X2,-6+Y2);
    drawLine(X2,-4+Y2,2+X2,-6+Y2);

}

void shops(float x3,float y3)
{
    glBegin(GL_QUADS);
    glColor3f(1,1,1);
    glVertex2f(x3,y3);
    glVertex2f(x3+5,y3);
    glVertex2f(x3+3,y3-2);
    glVertex2f(x3-2,y3-2);
    glEnd();

}



void init(void)
{
    glClearColor(0.8, 1.0, 1.0, 0.0);

    glMatrixMode(GL_PROJECTION);
    gluOrtho2D(0.0, 100.0, 0.0, 80.0);
}

void drawShapes(void)
{
    glClear(GL_COLOR_BUFFER_BIT);


    glColor3f(0.0, 0.0, 0.0);

    glPointSize(5.0);



    glColor3f(1.0, 0.0, 0.0);



    //DIvidation
    glBegin(GL_QUADS);
    glColor3f(0.8, 1.0,1.0);
    glVertex2f(0.0,37.0);
    glVertex2f(0.0,80.0);
    glVertex2f(100.0,80.0);
    glVertex2f(100.0,37.0);

    glBegin(GL_QUADS);
    glColor3f(0.5,0.5,0.5);
    glVertex2f(0.0,37.0);
    glVertex2f(100.0,37.0);
    glVertex2f(100.0,0.0);
    glVertex2f(0.0,0.0);
    glEnd();

    //Melaaa

    shops(-2,4);
    shops(8,4);
    shops(18,4);
    shops(28,4);
    shops(38,4);
    shops(48,4);
    shops(58,4);
    shops(68,4);
    shops(78,4);
    shops(88,4);
    shops(98,4);




    shops(2,8);
    shops(12,8);
    shops(22,8);
    shops(32,8);
    shops(42,8);
    shops(52,8);
    shops(62,8);
    shops(72,8);
    shops(82,8);
    shops(92,8);


    shops(-4,12);
    shops(6,12);
    shops(16,12);
    shops(26,12);
    shops(36,12);
    shops(46,12);
    shops(56,12);
    shops(66,12);
    shops(76,12);
    shops(86,12);
    shops(96,12);


    shops(0,16);
    shops(10,16);
    shops(20,16);
    shops(30,16);
    shops(40,16);
    shops(50,16);
    shops(60,16);
    shops(70,16);
    shops(80,16);
    shops(90,16);
    shops(100,16);


    shops(-6,20);
    shops(4,20);
    shops(14,20);
    shops(24,20);
    shops(34,20);
    shops(44,20);
    shops(54,20);
    shops(64,20);
    shops(74,20);
    shops(84,20);
    shops(94,20);
    shops(104,20);


    shops(-12,24);
    shops(-2,24);
    shops(8,24);
    shops(18,24);
    shops(28,24);
    shops(38,24);
    shops(48,24);
    shops(58,24);
    shops(68,24);
    shops(78,24);
    shops(88,24);
    shops(95,24);
    shops(108,24);

    shops(-8,28);
    shops(2,28);
    shops(12,28);
    shops(22,28);
    shops(32,28);
    shops(42,28);
    shops(52,28);
    shops(62,28);
    shops(72,28);
    shops(82,28);
    shops(92,28);
    shops(102,28);
    shops(108,28);

    shops(6,32);
    shops(16,32);
    shops(26,32);
    shops(36,32);
    shops(46,32);
    shops(56,32);
    shops(66,32);
    shops(76,32);
    shops(86,32);
    shops(96,32);
    shops(106,32);
    shops(112,32);

    shops(10,36);
    shops(20,36);
    shops(30,36);
    shops(40,36);
    shops(50,36);
    shops(60,36);
    shops(70,36);
    shops(80,36);
    shops(90,36);
    shops(100,36);





//Main Temple Shape
    glBegin(GL_POLYGON);

    glColor3f(1.0,0.6,0);


    glVertex2f(30.0,29.0);
    glVertex2f(30.0,45.0);
    glVertex2f(29.0,47.0);
    glVertex2f(31.0,48.0);
    glVertex2f(31.0,50.0);
    glVertex2f(36.0,51.0);
    glVertex2f(33.0,56.0);
    glVertex2f(32.0,58.0);
    glVertex2f(37.0,59.0);
    glVertex2f(44.0,59.0);
    glVertex2f(44.0,60.0);
    glVertex2f(46.0,61.0);
    glVertex2f(52.0,61.0);
    glVertex2f(54.0,59.0);
    glVertex2f(54.0,57.0);
    glVertex2f(60.0,53.0);
    glVertex2f(60.0,50.0);
    glVertex2f(65.0,50.0);
    glVertex2f(68.0,48.0);
    glVertex2f(68.0,37.0);
    glVertex2f(70.0,36.0);
    glVertex2f(70.0,35.0);
    glVertex2f(59.0,23.0);
    glVertex2f(25.0,23.0);
    glVertex2f(25.0,25.0);
    glVertex2f(29.0,27.0);




    glEnd();
    //Designing Temple

    glLineWidth(1.5);
    glColor3f(1.0,0.0,0.0);
    drawLine(25.0,25.0,59.0,25.0);
    drawLine(59.0,25.0,59.0,23.0);
    drawLine(59.0,25.0,69.7,35.7);
    drawLine(27.8,27.0,56.0,27.0);
    drawLine(56.0,27.0,68.0,36.0);
    drawLine(68.0,36.0,68.0,37.0);
    drawLine(56.0,27.0,55.0,29.0);
    drawLine(55.0,29.0,55.0,45.0);
    drawLine(55.0,45.0,56.0,47.0);
    drawLine(56.0,47.0,48.0,50.0);
    drawLine(48.0,50.0,37.0,50.0);
    drawLine(37.0,50.0,29.0,47.0);
    drawLine(54.0,48.0,54.0,50.0);
    drawLine(54.0,50.0,48.0,52.0);
    drawLine(48.0,52.0,36.0,52.0);
    drawLine(48.0,52.0,36.0,52.0);
    drawLine(36.0,52.0,31.0,50.0);

    drawLine(51.0,51.0,51.0,57.0);
    drawLine(51.0,57.0,54.0,57.0);
    drawLine(51.0,57.0,45.0,59.0);
    drawLine(68.0,47.0,65.0,49.0);

    drawLine(54.0,49.0,65.0,49.0);
    drawLine(54.0,50.0,60.0,50.0);
    drawLine(25,25,25,23);
    drawLine(25,23,59,23);
    drawLine(59,23,70,35);
    drawLine(70,35,70,36);
    drawLine(65,50,68,48);
    drawLine(68,48,68,36);
    drawLine(65,50,65,34);
    drawLine(25,25,30,29);
    drawLine(30,29,29,47);

    drawLine(29,47,31,48);
    drawLine(31,48,31,50);
    drawLine(31,50,33,51);
    drawLine(31.5,50,32,58);
    drawLine(32,58,37,59);
    drawLine(37,59,44,59);
    drawLine(44,59,44,60);
    drawLine(44,60,46,61);
    drawLine(46,61,52,61);
    drawLine(52,61,54,59);
    drawLine(54,59,54,57);
    drawLine(54,57,60,53);
    drawLine(60,53,60,50);
    drawLine(60,50,65,50);
    drawLine(44,59,45,59);


    //Doors of temple
    glBegin(GL_POLYGON);
    glColor3f(0,0,0);
    glVertex2f(37,30);
    glVertex2f(38.5,32);
    glVertex2f(40,30);
    glVertex2f(40,27);
    glVertex2f(37,27);
    glEnd();

    glBegin(GL_POLYGON);
    glColor3f(0,0,0);
    glVertex2f(42,30);
    glVertex2f(43.5,32);
    glVertex2f(45,30);
    glVertex2f(45,27);
    glVertex2f(42,27);
    glEnd();

    glBegin(GL_POLYGON);
    glColor3f(0,0,0);
    glVertex2f(47,30);
    glVertex2f(48.5,32);
    glVertex2f(50,30);
    glVertex2f(50,27);
    glVertex2f(47,27);
    glEnd();

    glBegin(GL_POLYGON);
    glColor3f(0,0,0);
    glVertex2f(61,31);
    glVertex2f(61,33);
    glVertex2f(61.5,34);
    glVertex2f(62,33);
    glVertex2f(62,31.5);
    glEnd();


//windows of temple

    glBegin(GL_QUADS);
    glColor3f(0,0,0);
    glVertex2f(38,57);
    glVertex2f(41,57);
    glVertex2f(41,55);
    glVertex2f(38,55);
    glEnd();

    glBegin(GL_QUADS);
    glColor3f(0,0,0);
    glVertex2f(44,57);
    glVertex2f(47,57);
    glVertex2f(47,55);
    glVertex2f(44,55);
    glEnd();





    //Shops on left
    glBegin(GL_POLYGON);
    glColor3f(1.0,0.0,1.0);
    glVertex2f(0.0,10.0);
    glVertex2f(7.0,20.0);
    glVertex2f(14.0,20.0);
    glVertex2f(1.0,0.0);

    glVertex2f(0.0,0.0);

    glEnd();
    glBegin(GL_POLYGON);
    glColor3f(0.0,0.0,1.0);

    glVertex2f(14.0,20.0);
    glVertex2f(14.0,15.0);
    glVertex2f(5.0,0.0);
    glVertex2f(0.0,0.0);


    glEnd();
    glBegin(GL_POLYGON);
    glColor3f(0.0,0.5,1.0);

    glVertex2f(14.0,17.0);
    glVertex2f(14.0,15.0);
    glVertex2f(5.0,0.0);
    glVertex2f(4.0,0.0);


    glEnd();


//Ride On Right
    glBegin(GL_TRIANGLES);
    glColor3f(1.0,0.,.0);
    glVertex2f(85.0,8.0);
    glVertex2f(87.9,19.30);
    glVertex2f(90.0,8.0);
    glEnd();

    glBegin(GL_QUADS);
    glColor3f(.0,.0,.0);
    glVertex2f(81.0,23.0);
    glVertex2f(85.0,23.0);
    glVertex2f(85.0,21.0);
    glVertex2f(81.0,21.0);
    glEnd();

    glBegin(GL_QUADS);
    glColor3f(.0,.0,.0);
    glVertex2f(90.0,24.0);
    glVertex2f(94.0,24.0);
    glVertex2f(94.0,22.0);
    glVertex2f(90.0,22.0);
    glEnd();

    glBegin(GL_QUADS);
    glColor3f(.0,.0,.0);
    glVertex2f(82.0,15.0);
    glVertex2f(86.0,15.0);
    glVertex2f(86.0,13.0);
    glVertex2f(82.0,13.0);
    glEnd();

    glBegin(GL_QUADS);
    glColor3f(.0,.0,.0);
    glVertex2f(90.0,16.0);
    glVertex2f(94.0,16.0);
    glVertex2f(94.0,14.0);
    glVertex2f(90.0,14.0);
    glEnd();

    glLineWidth(5.0);
    glBegin(GL_LINES);

    glColor3f(.0,0.0,0.0);
    glVertex2f(84.0,15.0);
    glVertex2f(92.0,24.0);

    glVertex2f(83.0,23.0);
    glVertex2f(92.0,16.0);
    glEnd();

    //Wall of both Sides
    glBegin(GL_POLYGON);
    glColor3f(1.0,1.0,0.0);

    glVertex2f(0.0,37.0);
    glVertex2f(15.0,38.0);
    glVertex2f(29.45,38.0);
    glVertex2f(30.0,31.0);
    glVertex2f(15.0,31.0);
    glVertex2f(0.0,30.0);
    glEnd();

    glBegin(GL_POLYGON);
    glColor3f(1.0,1.0,0.0);

    glVertex2f(68.0,39.0);
    glVertex2f(85.0,39.0);
    glVertex2f(100.0,37.0);
    glVertex2f(100.0,33.0);
    glVertex2f(85.0,35.0);
    glVertex2f(70.0,35.0);
    glVertex2f(70.0,36.0);
    glVertex2f(68.0,37.0);


    glEnd();

    //SUN
    glColor3f(1.0,0.0,0.0);
    makeCircle(3.0,85.0,65.0);



//plane

    if(p<=95) //moving limit with the display measurement
        p=p+.04; // changing the object position for redisplaying

    else
        p=-60; // For backing the object continuously

    glutPostRedisplay();

    glColor3f(0.7,0.7,0.0);
    glBegin(GL_QUADS);
    glVertex2f(70-p,70);
    glVertex2f(85-p,70);
    glVertex2f(85-p,65);
    glVertex2f(70-p,65);
    glEnd();
    glBegin(GL_QUADS);
    glVertex2f(85-p,70);
    glVertex2f(90-p,75);
    glVertex2f(93-p,75);
    glVertex2f(85-p,65);
    glEnd();
    glColor3f(0.7,0.0,1.0);
    glBegin(GL_TRIANGLES);
    glVertex2f(65-p,66);
    glVertex2f(70-p,70);
    glVertex2f(70-p,65);
    glEnd();

    glColor3f(0,0,1);
    glBegin(GL_QUADS);
    glVertex2f(77-p,70);
    glVertex2f(81-p,74);
    glVertex2f(83-p,74);
    glVertex2f(80-p,70);
    glEnd();
    glBegin(GL_QUADS);
    glVertex2f(77-p,65);
    glVertex2f(80-p,65);
    glVertex2f(81-p,62);
    glVertex2f(79-p,62);
    glEnd();
//Flag

    glBegin(GL_QUADS);
    glColor3f(1.0,0.0,0.5);

    glVertex2f(50.0,64.0);
    glVertex2f(52.0,64.0);
    glVertex2f(52.0,63.0);
    glVertex2f(50.0,63.0);
    glEnd();


    glColor3f(1.0,0.0,0.5);
    glLineWidth(2.0);

    drawLine(50,61,50,64);






    //Stick Human
    glColor3f(1,0.2,.5);
    stickman(60,20);
    stickman(36,15);
    stickman(42,17);
    stickman(47,21.5);
    stickman(52,22);

    stickman(70,20);
    stickman(8,2);
    stickman(11,8);
    stickman(14,12);
    stickman(22,10);
    stickman(25,18);

    stickman(28,9);
    stickman(30,15);
    stickman(37,5);
    stickman(41,7);
    stickman(46,4);
    stickman(47,10);
    stickman(75,12);
    stickman(83,6);
    stickman(95,7);





    //tree1
    glColor3f(1.0,0.3,0.0);
    glBegin(GL_QUADS);
    glVertex2f(15,25);
    glVertex2f(16,35);
    glVertex2f(17.5,35);
    glVertex2f(17,25);
    glEnd();

    glBegin(GL_QUADS);
    glVertex2f(16,44);
    glVertex2f(17,44);
    glVertex2f(17.5,35);
    glVertex2f(16,35);
    glEnd();
    glColor3f(0.0,0.3,0.0);
    makeCircle(2,15,46);
    makeCircle(2,15,43);
    makeCircle(2,15,48);
    makeCircle(2,17,48);
    makeCircle(2,19,48);
    makeCircle(2,19,45);
    makeCircle(2,18,44);
//tree2
    glBegin(GL_QUADS);
    glColor3f(1.0,0.3,0.0);
    glVertex2f(75,25);
    glVertex2f(76,35);
    glVertex2f(77.5,35);
    glVertex2f(77,25);
    glEnd();

    glBegin(GL_QUADS);
    glVertex2f(76,44);
    glVertex2f(77,44);
    glVertex2f(77.5,35);
    glVertex2f(76,35);
    glEnd();
    glColor3f(0.0,0.9,0.0);
    makeCircle(2,75,46);
    makeCircle(2,75,43);
    makeCircle(2,75,48);
    makeCircle(2,77,48);
    makeCircle(2,79,48);
    makeCircle(2,79,45);
    makeCircle(2,78,44);
//tree3

    glBegin(GL_QUADS);
    glColor3f(1.0,0.3,0.0);
    glVertex2f(85,25);
    glVertex2f(86,35);
    glVertex2f(87.5,35);
    glVertex2f(87,25);
    glEnd();

    glBegin(GL_QUADS);
    glVertex2f(86,44);
    glVertex2f(87,44);
    glVertex2f(87.5,35);
    glVertex2f(86,35);
    glEnd();
    glColor3f(0.0,0.5,0.0);
    makeCircle(2,85,46);
    makeCircle(2,85,43);
    makeCircle(2,85,48);
    makeCircle(2,87,48);
    makeCircle(2,89,48);
    makeCircle(2,89,45);
    makeCircle(2,88,44);

    glFlush();
}

int main(int argc, char* argv[])
{
    glutInit(&argc, argv);						// Initalise GLUT
    glutInitDisplayMode(GLUT_SINGLE|GLUT_RGB);	// Set display mode

    glutInitWindowPosition(50, 100);				// Set window position
    glutInitWindowSize(1100,800);					// Set window size
    glutCreateWindow("Drawing of Kantajew Temple");	// Create display window

    init();							// Execute initialisation procedure
    glutDisplayFunc(drawShapes);		// Send graphics to display window
    glutMainLoop();					// Display everything and wait

    return 0;
}
