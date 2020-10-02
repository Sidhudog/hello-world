//colourfulstones(simplified edition)
#include <iostream>
using namespace std;
int main()
{
    int i, n = 1, k = 0;
    string s, t;

    cin >> s >> t;
    if (s.length() >= t.length())
    {
        for (i = 0; i < t.length(); i++)
        {
            if (s[k] == t[i])
            {
                k++;
                n++;
            }
        }
    }
    else
    {
        for (i = 0; i < t.length(); i++)
        {
            if (s[k] == t[i])
            {
                k++;
                n++;
            }
        }
    }
        cout << n;

        return 0;
    }

   
