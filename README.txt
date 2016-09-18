The following document contains the algorithms used implemented in C.
********************************
int max(int a, int b, int c)
{
    if (a > b)
        if (a > c)
            return a;
    else if (b > c)
        return b;
    else
        return c;
}
*******************************
*******************************
int min(int a, int b, int c)
{
    if (a < b)
        if (a < c)
            return a;
    else if (b < c)
        return b;
    else
        return c;
}
******************************






