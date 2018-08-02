# Computer_Graphics Room Design
## About Computer Graphics: 
```
•A powerful tool for the rapid and economical production of pictures.
•Computer Graphics Is a generalized tool for drawing and creating pictures.
•Simulate the real world situations within a small computer window.
```
## About OpenGL: 
```
•OpenGL is a device and operating system independent library for 3D graphics and rendering.
•OpenGL is a standard specification defining a cross-language, cross-platform API.
•The interface consists of many different function calls which can be used for building application programs.
•OpenGL is portable to many platforms and callable from many programming languages. 

```
## Built-in Library Function: 
```
 	glColor3f (0.0, 0.0, 0.0);
 	glBegin(GL_POLYGON);
 	glVertex2d (x,y);
 	glClear(GL_COLOR_BUFFER_BIT);
 	glClearColor(0, 0, 0, 0);
 	glMatrixMode(GL_PROJECTION);
 	gluOrtho2D(0, 110, 0, 70);     // for setting the transformation which here is 2D
 	glutInit(&agrc, argv);
 	glutInitDisplayMode(GLUT_SINGLE | GLUT_RGB);
 	glutInitWindowPosition(100, 50);
 	glutInitWindowSize(1000, 900);
 	glutCreateWindow("Md Shihab Ali ");       
 	init();
 	glutDisplayFunc(display);
 	glutMainLoop();
 	glEnd();
 	glFlush ();
```
## User defined functions:
```
 	room ();
 	BED();
 	//Window();
 	almira();
 	freezer();
 	TV();
 	ShowCase();
 	WallMate();
 	WallMate2();
 	door();
```
