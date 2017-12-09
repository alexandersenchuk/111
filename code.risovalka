namespace ConsoleApplication20
{
    class Program
    {
        static void Main(string[] args)
        {
            ConsoleKeyInfo key;
            int x = Console.WindowWidth / 2;
            int y = Console.WindowHeight / 2;
            Console.SetCursorPosition(x, y);
            key = Console.ReadKey();
            
            do
            {
                Console.SetCursorPosition(x, y);
                Console.WriteLine("*");
                key = Console.ReadKey();
                if (key.Key == ConsoleKey.UpArrow)
                {
                    Console.Write("*");
                    Console.SetCursorPosition(x, y - 1);
                    y--;
                }
                else if (key.Key == ConsoleKey.DownArrow)
                {
                    Console.Write("*");
                    Console.SetCursorPosition(x, y + 1);
                    y++;
                }
                else if (key.Key == ConsoleKey.LeftArrow)

                {
                    Console.Write("*");
                    Console.SetCursorPosition(x - 1, y);
                    x--;
                }
                else if (key.Key == ConsoleKey.RightArrow)
                {
                    Console.Write("*");
                    Console.SetCursorPosition(x + 1, y);
                    x++;
                }
            }
            while (key.Key != ConsoleKey.Escape);
            
        }
    }
}
