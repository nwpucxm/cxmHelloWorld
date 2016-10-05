#include "stdio.h"
#include "stdlib.h"
#include "gl/glut.h"

int main (int argc, char * argv[])
{
	glutInit(&argc, argv);
	glutInitDisplayMode(GL_DEPTH | GL_DOUBLE | GL_RGB);
	glutInitWindowPosition(100, 100);
	glutInitWindowSize(400, 400);
	glutCreateWindow("cxmMyCode_Project_1);
	
	glShadeMode(GL_SMOOTH);
	glClearColor(0.0f, 0.0f, 0.0f, 0.0f);
	glClear(GL_COLOR_BUFFER_BIT || GL_DEPTH_BUFFER_BIT);
	glLoadIdentity();
	
	printf("hello world !");
}
