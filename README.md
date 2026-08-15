#include <stdio.h>

int main()
{
    FILE *fp;

    fp = fopen("application.html", "w");

    if (fp == NULL)
    {
        printf("Unable to create website.\n");
        return 1;
    }

    fprintf(fp,
        "<!DOCTYPE html>\n"
        "<html>\n"
        "<head>\n"
        "<title>Student Application</title>\n"
        "</head>\n"
        "<body>\n"

        "<h1>Student Application Form</h1>\n"

        "<form>\n"

        "Name:<br>\n"
        "<input type='text' name='name'><br><br>\n"

        "Class:<br>\n"
        "<input type='text' name='class'><br><br>\n"

        "Date of Birth:<br>\n"
        "<input type='date' name='dob'><br><br>\n"

        "School Name:<br>\n"
        "<input type='text' name='school'><br><br>\n"

        "Mandal:<br>\n"
        "<input type='text' name='mandal'><br><br>\n"

        "Medium:<br>\n"
        "<select name='medium'>\n"
        "<option>Telugu</option>\n"
        "<option>English</option>\n"
        "<option>Urdu</option>\n"
        "</select><br><br>\n"

        "<input type='submit' value='Submit'>\n"

        "</form>\n"
        "</body>\n"
        "</html>\n"
    );

    fclose(fp);

    printf("Website created successfully!\n");
    printf("Open application.html in Chrome.\n");

    return 0;
}
