using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _02_List_array
{
    class Program
    {
        static void Main(string[] args)
        {
            WriteLine("Enter no. of element to insert : ");
            int n = Convert.ToInt32(ReadLine());

            ArrayList arr1 = new ArrayList();
            WriteLine("Enter elements : ");
            for ( int i = 0; i < n; i++)
            {
                var s = ReadLine();
                arr1.Add(s);
            }
            WriteLine();
            WriteLine("You have entered : ");
            foreach (var i in arr1)
            {
                WriteLine(i);
            }
            WriteLine();
            WriteLine("Enter no. of element to delete: ");
            int m = Convert.ToInt32(ReadLine());
            WriteLine("Enter element to delete: ");
            for (int i = 0; i < m; i++)
            {
                string j = ReadLine();
                arr1.Remove(j);
            }
            WriteLine();
            WriteLine("Remaining element: ");
            foreach (var i in arr1)
            {
                WriteLine(i);
            }

        }
    }
}