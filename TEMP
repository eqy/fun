#include <stdio.h>
#include <string.h>
char bslash = 92;
char newline = 10;
char quote = 34;
char funstring[] = "#include <stdio.h>\n#include <string.h>\nchar bslash = 92;\nchar newline = 10;\nchar quote = 34;\nint main()\n{\nunsigned int i;\nfor(i = 0; i < 93; i++)\nprintf(\"%c\", funstring[i]);\nprintf(\"char funstring[] = \");\nprintf(\"%c\", quote);\nfor(i = 0; i < strlen(funstring); i++)\nif(funstring[i] == newline)\n{\nprintf(\"%c\", bslash);\nprintf(\"n\");\n}\nelse if(funstring[i] == quote)\n{\nprintf(\"%c\", bslash);\nprintf(\"%c\", quote);\n}\nelse\n{\nprintf(\"%c\", funstring[i]);\n}\nprintf(\"%c;\", quote);\nprintf(\"%c\", newline);\nfor(i = 93; i < strlen(funstring); i++)\nprintf(\"%c\", funstring[i]);\n}\n";
int main()
{
unsigned int i;
for(i = 0; i < 93; i++)
printf("%c", funstring[i]);
printf("char funstring[] = ");
printf("%c", quote);
for(i = 0; i < strlen(funstring); i++)
if(funstring[i] == newline)
{
printf("%c", bslash);
printf("n");
}
else if(funstring[i] == quote)
{
printf("%c", bslash);
printf("%c", quote);
}
else
{
printf("%c", funstring[i]);
}
printf("%c;", quote);
printf("%c", newline);
for(i = 93; i < strlen(funstring); i++)
printf("%c", funstring[i]);
}
